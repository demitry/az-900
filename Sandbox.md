# MS



<!-- TOC -->

- [MS](#ms)
        - [Task 1: Create a Linux virtual machine and install Nginx](#task-1-create-a-linux-virtual-machine-and-install-nginx)
        - [Exercise - Configure network access](#exercise---configure-network-access)
        - [Task 3: Create the network security rule](#task-3-create-the-network-security-rule)
        - [Task 4: Access your web server again](#task-4-access-your-web-server-again)
    - [QUIZ](#quiz)

<!-- /TOC -->

PowerShell: Get-date
Azure CLI: az version, date
BASH CLI: bash
az upgrade
Task 3: Use Azure CLI interactive mode
```
az interactive
version
upgrade
exit
```

cloudshell2029430833 Storage account West Europe
my-VM Virtual machine West US
my-VM-ip Public IP address West US
my-VM-nsg Network security group West US
my-VM-vnet Virtual network West US
my-vm499 Network Interface West US
my-VM_disk1_ad2bf41261414bbab8c15db46adfe1af Disk West US
my-VM_key SSH key West US

### Task 1: Create a Linux virtual machine and install Nginx

```
az vm create --resource-group learn-d896e1ee-646a-49a4-ac3d-6779977c8ee8 --name my-vm --public-ip-sku Standard --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys
```

```
SSH key files '/home/dpoluektov/.ssh/id_rsa' and '/home/dpoluektov/.ssh/id_rsa.pub' have been generated under ~/.ssh to allow SSH access to the VM. If using machines without permanent storage, back up your keys to a safe location.
Ignite (November) 2023 onwards "az vm/vmss create" command will deploy Gen2-Trusted Launch VM by default. To know more about the default change and Trusted Launch, please visit https://aka.ms/TLaD
{
  "fqdns": "",
  "id": "/subscriptions/76b50b69-6a20-4079-b075-3f796c72cac3/resourceGroups/learn-d896e1ee-646a-49a4-ac3d-6779977c8ee8/providers/Microsoft.Compute/virtualMachines/my-vm",
  "location": "westus",
  "macAddress": "00-0D-3A-5B-79-21",
  "powerState": "VM running",
  "privateIpAddress": "10.0.0.4",
  "publicIpAddress": "40.112.250.206",
  "resourceGroup": "learn-d896e1ee-646a-49a4-ac3d-6779977c8ee8",
  "zones": ""
}
```


Run the following az vm extension set command to configure Nginx on your VM:

```
az vm extension set --resource-group learn-d896e1ee-646a-49a4-ac3d-6779977c8ee8 --vm-name my-vm --name customScript --publisher Microsoft.Azure.Extensions --version 2.1 --settings '{"fileUris":["https://raw.githubusercontent.com/MicrosoftDocs/mslearn-welcome-to-azure/master/configure-nginx.sh"]}' --protected-settings '{"commandToExecute": "./configure-nginx.sh"}'
```

https://raw.githubusercontent.com/MicrosoftDocs/mslearn-welcome-to-azure/master/configure-nginx.sh

```
#!/bin/bash

# Update apt cache.
sudo apt-get update

# Install Nginx.
sudo apt-get install -y nginx

# Set the home page.
echo "<html><body><h2>Welcome to Azure! My name is $(hostname).</h2></body></html>" | sudo tee -a /var/www/html/index.html
```

```
{
  "autoUpgradeMinorVersion": true,
  "enableAutomaticUpgrade": null,
  "forceUpdateTag": null,
  "id": "/subscriptions/76b50b69-6a20-4079-b075-3f796c72cac3/resourceGroups/learn-d896e1ee-646a-49a4-ac3d-6779977c8ee8/providers/Microsoft.Compute/virtualMachines/my-vm/extensions/customScript",
  "instanceView": null,
  "location": "westus",
  "name": "customScript",
  "protectedSettings": null,
  "protectedSettingsFromKeyVault": null,
  "provisioningState": "Succeeded",
  "publisher": "Microsoft.Azure.Extensions",
  "resourceGroup": "learn-d896e1ee-646a-49a4-ac3d-6779977c8ee8",
  "settings": {
    "fileUris": [
      "https://raw.githubusercontent.com/MicrosoftDocs/mslearn-welcome-to-azure/master/configure-nginx.sh"
    ]
  },
  "suppressFailures": null,
  "tags": null,
  "type": "Microsoft.Compute/virtualMachines/extensions",
  "typeHandlerVersion": "2.1",
  "typePropertiesType": "customScript"
}

```

### Exercise - Configure network access

```
az vm list

[]

az vm create --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --name my-vm --public-ip-sku Standard --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys


az vm extension set --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --vm-name my-vm --name customScript --publisher Microsoft.Azure.Extensions --version 2.1 --settings '{"fileUris":["https://raw.githubusercontent.com/MicrosoftDocs/mslearn-welcome-to-azure/master/configure-nginx.sh"]}' --protected-settings '{"commandToExecute": "./configure-nginx.sh"}'

az vm list


az vm list-ip-addresses


IPADDRESS="$(az vm list-ip-addresses --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --name my-vm --query "[].virtualMachine.network.publicIpAddresses[*].ipAddress" --output tsv)"

curl --connect-timeout 5 http://$IPADDRESS


az network nsg list --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --query '[].name' --output tsv

my-vmNSG

az network nsg rule list --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --nsg-name my-vmNSG

```

```json
[
  {
    "access": "Allow",
    "destinationAddressPrefix": "*",
    "destinationAddressPrefixes": [],
    "destinationPortRange": "22",
    "destinationPortRanges": [],
    "direction": "Inbound",
    "etag": "W/\"33b1907c-eb8e-4621-8f62-53f66a6cb1d3\"",
    "id": "/subscriptions/695cfd67-680c-43bf-a0d7-26ff301d991d/resourceGroups/learn-851d552f-d067-47ab-acb4-de06f79ef0d3/providers/Microsoft.Network/networkSecurityGroups/my-vmNSG/securityRules/default-allow-ssh",
    "name": "default-allow-ssh",
    "priority": 1000,
    "protocol": "Tcp",
    "provisioningState": "Succeeded",
    "resourceGroup": "learn-851d552f-d067-47ab-acb4-de06f79ef0d3",
    "sourceAddressPrefix": "*",
    "sourceAddressPrefixes": [],
    "sourcePortRange": "*",
    "sourcePortRanges": [],
    "type": "Microsoft.Network/networkSecurityGroups/securityRules"
  }
]
```

```
az network nsg rule list --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --nsg-name my-vmNSG --query '[].{Name:name, Priority:priority, Port:destinationPortRange, Access:access}' --output table


Name               Priority    Port    Access
-----------------  ----------  ------  --------
default-allow-ssh  1000        22      Allow

```

### Task 3: Create the network security rule

```
az network nsg rule create --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --nsg-name my-vmNSG --name allow-http --protocol tcp --priority 100 --destination-port-range 80 --access Allow
```

```json
{
  "access": "Allow",
  "destinationAddressPrefix": "*",
  "destinationAddressPrefixes": [],
  "destinationPortRange": "80",
  "destinationPortRanges": [],
  "direction": "Inbound",
  "etag": "W/\"044d1064-d8ef-461c-86fd-a11f8053e759\"",
  "id": "/subscriptions/695cfd67-680c-43bf-a0d7-26ff301d991d/resourceGroups/learn-851d552f-d067-47ab-acb4-de06f79ef0d3/providers/Microsoft.Network/networkSecurityGroups/my-vmNSG/securityRules/allow-http",
  "name": "allow-http",
  "priority": 100,
  "protocol": "Tcp",
  "provisioningState": "Succeeded",
  "resourceGroup": "learn-851d552f-d067-47ab-acb4-de06f79ef0d3",
  "sourceAddressPrefix": "*",
  "sourceAddressPrefixes": [],
  "sourcePortRange": "*",
  "sourcePortRanges": [],
  "type": "Microsoft.Network/networkSecurityGroups/securityRules"
}
```

```
az network nsg rule list --resource-group learn-851d552f-d067-47ab-acb4-de06f79ef0d3 --nsg-name my-vmNSG --query '[].{Name:name, Priority:priority, Port:destinationPortRange, Access:access}' --output table

Name               Priority    Port    Access
-----------------  ----------  ------  --------
default-allow-ssh  1000        22      Allow
allow-http         100         80      Allow
```

### Task 4: Access your web server again

```
curl --connect-timeout 5 http://$IPADDRESS

<html><body><h2>Welcome to Azure! My name is my-vm.</h2></body></html>
```
















## QUIZ

1. How many resource groups can a resource be in at the same time? 
- One
A resource can only be in one group at a time.

2. What happens to the resources within a resource group when an action or setting at the Resource Group level is applied? 
- The setting is applied to current and future resources.
Resources inherit permissions from their resource group.


3. What Azure feature replicates resources across regions that are at least 300 miles away from each other? 
- Region pairs
Most Azure regions are paired with another region within the same geography (such as US, Europe, or Asia) at least 300 miles away.


Question 1:
Is below statement true or false?

An Azure region contains one or more data centers that are connected by using a low-latency network.

- True
An Azure region is a set of data centres deployed within a dedicated regional low-latency network.

Question 2:
A company with seven departments has a plan to implement an Azure environment. To ensure that each department can use a different payment option for the Azure services it consumes, what should be created for each department?
- Subscription
There are different payment options in Azure including pay-as-you-go (PAYG), Enterprise Agreement (EA), and Microsoft Customer Agreement (MCA) accounts. Your Azure costs are ‘per subscription’. You are charged monthly for all resources in a subscription. Therefore, to use different payment options per department, you will need to create a separate subscription per department. You can create multiple subscriptions in a single Azure Active Directory tenant.

Question 3:
When you need to delegate permissions to several Azure VMs simultaneously, you must deploy the Azure VMs to the same .
- resource group

A resource group is a logical container for Azure resources. Resource groups make the management of Azure resources easier. With a resource group, you can allow a user to manage all resources in the resource group, such as virtual machines, websites, and subnets. The permissions you apply to the resource group apply to all resources contained in the resource group.


Serverless
- Event Driven
- No infrastructure management
- Scalability
- Pay for what you use
- Azure Functions
    - Functions scale automatically based on demand
    - Azure Functions runs your code when it's triggered and automatically deallocates resources when the function is finished.
    - In this model, you're only charged for the CPU time used while your function runs

Functions can be either stateless or stateful. 
When they're stateless (the default), they behave as if they're restarted every time they respond to an event. 
When they're stateful (called Durable Functions), a context is passed through the function to track prior activity.
