Managed Disks:

The managed disk provides enhanced manageability and high availability which provides the following features.
- Simple - Abstracts underlying storage account/blob associated with the VM disks from customers. Eliminates the need to manage storage accounts for IaaS VMs.
- Secure by default – Role based access control, storage encryption by default and encryption using own keys.
- Storage account limits do not apply – No throttling due to storage account IOPS limits
- Big scale - 20,000 disks per region per subscription.
- Better Storage Resiliency - Prevents single points of failure due to storage Supports both Standard and Premium Storage disks

Unmanaged Disks:

- Less availability:
- disks do not protect against single storage scale unit outage
- Upgrading process is complex: If you want to upgrade from standard to premium on unmanaged disks, process is very complex.
- Apart from this unplanned downtime, security is the downsides of the unmanaged disks. However, Cost differences between managed and unmanaged are based on your workload use case
- Simple and scalable VM deployment: Managed Disks will allow you to create up to 10,000 VM disks in a subscription, which will enable you to create thousands of VMs in a single subscription.
- Better reliability for Availability Sets: Managed Disks provides better reliability for Availability Sets by ensuring that the disks of VMs in an Availability Set are sufficiently isolated from each other to avoid single points of failure.
- Highly durable and available
- Granular access control: You can use Azure Role-Based Access Control (RBAC) to assign specific permissions for a managed disk to one or more users. Managed Disks exposes a variety of operations, including read, write (create/update), delete, and retrieving a shared access signature (SAS) URI for the disk.
- Azure Backup service support: Use Azure Backup service with Managed Disks to create a backup job with time-based backups, easy VM restoration and backup retention policies
- 6. Are unmanaged disks still supported: Yes. 
    - Both support unmanaged and managed disks. 
    - We recommend that you use managed disks for new workloads and migrate your current workloads to managed disks.
- There is also nice practical differences summary here
- Managed Disks 
  - are managed by Microsoft Azure and you don't need any storage account while created new disk.
  - managed by Azure => you do not have full control of the disks that are being created.
- Un-managed Disks = is something which requires you to create a storage account before you create any new disk. Since, the storage account is created and owned by you, you have full control over all the data that is present on your storage account. Additionally, you also need to take care of encryption, data recovery plans etc.