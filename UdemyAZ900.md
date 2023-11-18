# AZ-900: Microsoft Azure Fundamentals Exam Prep - OCT 2023 - Scott Duffy

Links:

<!-- TOC -->

- [AZ-900: Microsoft Azure Fundamentals Exam Prep - OCT 2023 - Scott Duffy](#az-900-microsoft-azure-fundamentals-exam-prep---oct-2023---scott-duffy)
    - [Section 1: AZ-900 Course](#section-1-az-900-course)
        - [Introduction [1]](#introduction-1)
        - [LIVE DEMO: A quick look into Azure [2]](#live-demo-a-quick-look-into-azure-2)
        - [AZ-900 Exam Requirements [3]](#az-900-exam-requirements-3)
            - [Important: When exam was updated](#important-when-exam-was-updated)
    - [Section 2: AZ-900 - Describe Cloud Computing](#section-2-az-900---describe-cloud-computing)
        - [What is Cloud Computing? [6]](#what-is-cloud-computing-6)
        - [Shared Responsibility Model [7]](#shared-responsibility-model-7)
        - [Public Cloud, Private Cloud, Hybrid Cloud [8]](#public-cloud-private-cloud-hybrid-cloud-8)
            - [Summary](#summary)
            - [public](#public)
            - [private](#private)
            - [hybrid](#hybrid)
        - [Cloud Pricing [9]](#cloud-pricing-9)
        - [LIVE DEMO: Pricing Calculator [10]](#live-demo-pricing-calculator-10)
        - [Quiz 1: ## Section 2 Quiz](#quiz-1--section-2-quiz)
    - [Section 3: AZ-900 - Benefits of Cloud Computing](#section-3-az-900---benefits-of-cloud-computing)
        - [High Availability  - Benefit of Cloud Computing [11]](#high-availability----benefit-of-cloud-computing-11)
            - [Planned Outages](#planned-outages)
            - [Unplanned Outages](#unplanned-outages)
            - [Methods to Mitigate Planned Outages](#methods-to-mitigate-planned-outages)
            - [Methods to Mitigate Unplanned Outages](#methods-to-mitigate-unplanned-outages)
        - [Scalability  - Benefit of Cloud Computing [12]](#scalability----benefit-of-cloud-computing-12)
            - [Vertical Scaling UP/DOWN](#vertical-scaling-updown)
            - [Vertical Scaling OUT/IN](#vertical-scaling-outin)
            - [Impact on Cost](#impact-on-cost)
        - [Elasticity  - Benefit of Cloud Computing [13]](#elasticity----benefit-of-cloud-computing-13)
            - [Quickly and Easily](#quickly-and-easily)
            - [Why?](#why)
        - [Reliability  - Benefit of Cloud Computing [14]](#reliability----benefit-of-cloud-computing-14)
        - [Predictability  - Benefit of Cloud Computing [15]](#predictability----benefit-of-cloud-computing-15)
        - [Security  - Benefit of Cloud Computing [16]](#security----benefit-of-cloud-computing-16)
        - [Governance  - Benefit of Cloud Computing [17]](#governance----benefit-of-cloud-computing-17)
        - [Manageability  - Benefit of Cloud Computing [18]](#manageability----benefit-of-cloud-computing-18)
        - [Quiz 2: ## Section 3 Quiz](#quiz-2--section-3-quiz)
    - [Section 4: AZ-900 - Cloud Service Types](#section-4-az-900---cloud-service-types)
        - [Cloud Service Types [19] IaaS, PaaS, SaaS](#cloud-service-types-19-iaas-paas-saas)
            - [IaaS - Infrastructure](#iaas---infrastructure)
            - [PaaS - Platform](#paas---platform)
                - [PaaS - Level](#paas---level)
                - [PaaS Networking](#paas-networking)
            - [SaaS - Software](#saas---software)
        - [Serverless [20]](#serverless-20)
            - [Azure Serverless Services](#azure-serverless-services)
        - [Quiz 3: ## Section 4 Quiz](#quiz-3--section-4-quiz)
            - [Question 1](#question-1)
            - [Question 2](#question-2)
            - [Question 3](#question-3)
    - [Section 5: AZ-900 - Core Architectural Components of Azure](#section-5-az-900---core-architectural-components-of-azure)
        - [Regions, Region Pairs, Sovereign Regions [21]](#regions-region-pairs-sovereign-regions-21)
        - [Availability Zones and Data Centers [22]](#availability-zones-and-data-centers-22)
        - [Resources and Resource Groups [23]](#resources-and-resource-groups-23)
        - [Subscriptions [24]](#subscriptions-24)
        - [Management Groups [25]](#management-groups-25)
        - [Quiz 4: ## Section 5 Quiz](#quiz-4--section-5-quiz)
    - [Section 6: AZ-900 - Azure Compute and Networking Services](#section-6-az-900---azure-compute-and-networking-services)
        - [Azure Compute services [26]](#azure-compute-services-26)
        - [Azure Functions [27]](#azure-functions-27)
        - [Azure Networking services [28]](#azure-networking-services-28)
        - [Network Peering [29]](#network-peering-29)
            - [Address range](#address-range)
            - [virtual networks: how to connect?](#virtual-networks-how-to-connect)
        - [Public and Private Endpoints [30]](#public-and-private-endpoints-30)
        - [Quiz 5: Section 6 Quiz](#quiz-5-section-6-quiz)
            - [Question 1:](#question-1)
            - [Question 2:](#question-2)
            - [Question 3:](#question-3)
    - [Section 7: AZ-900 - Azure Compute Demo](#section-7-az-900---azure-compute-demo)
        - [LIVE DEMO: Creating a Virtual Machine VM [31]](#live-demo-creating-a-virtual-machine-vm-31)
        - [LIVE DEMO: Connecting to a Virtual Machine [32]](#live-demo-connecting-to-a-virtual-machine-32)
            - [Run machine](#run-machine)
            - [Server Manager - machine config](#server-manager---machine-config)
        - [LIVE DEMO: Creating Azure App Services / Web Apps [33]](#live-demo-creating-azure-app-services--web-apps-33)
        - [LIVE DEMO: Azure App Services In Action [34]](#live-demo-azure-app-services-in-action-34)
            - [Deployment Slot](#deployment-slot)
        - [LIVE DEMO: Creating Azure Functions [35]](#live-demo-creating-azure-functions-35)
        - [LIVE DEMO: Kubernetes and Azure Container Instances [36]](#live-demo-kubernetes-and-azure-container-instances-36)
            - [Summary](#summary)
        - [LIVE DEMO: Azure Container Apps [37]](#live-demo-azure-container-apps-37)
        - [Delete resources](#delete-resources)
    - [Section 8: AZ-900 - Azure Storage](#section-8-az-900---azure-storage)
        - [Overview of Azure Storage [39]](#overview-of-azure-storage-39)
        - [LIVE DEMO: Create an Unmanaged Storage Account [40]](#live-demo-create-an-unmanaged-storage-account-40)
        - [LIVE DEMO: Upload Files to a Storage Account [41]](#live-demo-upload-files-to-a-storage-account-41)
        - [LIVE DEMO: Azure Storage Explorer & Storage Browser [42]](#live-demo-azure-storage-explorer--storage-browser-42)
        - [AZCOPY [43]](#azcopy-43)
        - [Azure File Sync [44]](#azure-file-sync-44)
        - [Azure Migrate [45]](#azure-migrate-45)
        - [Azure Data Box [46]](#azure-data-box-46)
        - [Quiz 6: ## Section 8 Quiz](#quiz-6--section-8-quiz)
            - [Question 1:](#question-1)
            - [Question 2:](#question-2)
            - [Question 3:](#question-3)
            - [Hmmmm ... My AzCopy Question](#hmmmm--my-azcopy-question)
    - [Section 9: AZ-900 - Identity, Access and Security](#section-9-az-900---identity-access-and-security)
        - [Identity and Azure Active Directory [47]](#identity-and-azure-active-directory-47)
            - [Identity](#identity)
            - [Security: Prove](#security-prove)
            - [Security: Client - Server Model](#security-client---server-model)
        - [Benefits of Microsoft Entra ID formerly Azure Active Directory Azure AD [48]](#benefits-of-microsoft-entra-id-formerly-azure-active-directory-azure-ad-48)
        - [Authenication vs Authorization [49]](#authenication-vs-authorization-49)
        - [Azure AD Conditional Access [50]](#azure-ad-conditional-access-50)
        - [Azure Multi-Factor Authentication MFA or 2FA [51]](#azure-multi-factor-authentication-mfa-or-2fa-51)
        - [Passwordless authentication [52]](#passwordless-authentication-52)
        - [Role-Based Access Control RBAC [53]](#role-based-access-control-rbac-53)
        - [Zero-Trust Model of Security [54]](#zero-trust-model-of-security-54)
        - [Defense in Depth [55]](#defense-in-depth-55)
        - [Microsoft Defender for Cloud [56]](#microsoft-defender-for-cloud-56)
        - [Quiz 7: ## Section 9 Quiz](#quiz-7--section-9-quiz)
            - [Question 1: Azure AD Multi-Factor Authentication MFA typically include any or all of the following **except**:](#question-1-azure-ad-multi-factor-authentication-mfa-typically-include-any-or-all-of-the-following-except)
            - [Question 2](#question-2)
            - [Question 3](#question-3)
    - [Section 10: AZ-900 - Cost Management in Azure](#section-10-az-900---cost-management-in-azure)
        - [Factors that Affect Cost [57]](#factors-that-affect-cost-57)
        - [Azure Pricing Calculator [58]](#azure-pricing-calculator-58)
        - [Total Cost of Ownership Calculator [59]](#total-cost-of-ownership-calculator-59)
        - [Azure Cost Management - Portal[60]](#azure-cost-management---portal60)
        - [Resource Tags [61]](#resource-tags-61)
        - [Quiz 8: ## Section 10 Quiz](#quiz-8--section-10-quiz)
    - [Section 11: AZ-900 - Azure Governance and Compliance](#section-11-az-900---azure-governance-and-compliance)
        - [Azure Governance and Compliance [62]](#azure-governance-and-compliance-62)
            - [Tools](#tools)
        - [Azure Blueprints [63]](#azure-blueprints-63)
            - [Blueprints - tamplates for future subscriptions](#blueprints---tamplates-for-future-subscriptions)
            - [the only way of assigning a deny permission](#the-only-way-of-assigning-a-deny-permission)
        - [Azure Policy [64]](#azure-policy-64)
        - [DEMO: Azure Policy [65]](#demo-azure-policy-65)
        - [Resource Locks [66]](#resource-locks-66)
        - [Microsoft Purview [67]](#microsoft-purview-67)
        - [Quiz 9: ## Section 11 Quiz](#quiz-9--section-11-quiz)
    - [Section 12: AZ-900 - Tools for Managing and Deploying Azure Resources](#section-12-az-900---tools-for-managing-and-deploying-azure-resources)
        - [Azure Portal and Command Line Tools [68]](#azure-portal-and-command-line-tools-68)
        - [LIVE DEMO: Create Resources Using Command Line [69]](#live-demo-create-resources-using-command-line-69)
        - [Azure Arc [70]](#azure-arc-70)
        - [Infrastructure as Code IaC [71]](#infrastructure-as-code-iac-71)
        - [ARM Templates [72]](#arm-templates-72)
        - [LIVE DEMO: Generate ARM Templates in the Azure Portal [73]](#live-demo-generate-arm-templates-in-the-azure-portal-73)
        - [Quiz 10: ## Section 12 Quiz](#quiz-10--section-12-quiz)
    - [Section 13: AZ-900 - Monitoring Tools](#section-13-az-900---monitoring-tools)
        - [Azure Advisor and Azure Service Health [74]](#azure-advisor-and-azure-service-health-74)
        - [Azure Diagnostics Settings [75]](#azure-diagnostics-settings-75)
        - [Azure Monitor [76]](#azure-monitor-76)
        - [Quiz 11: ## Section 13 Quiz](#quiz-11--section-13-quiz)
    - [Section 14: 50 QUESTION PRACTICE TEST](#section-14-50-question-practice-test)
        - [Practice Test 1: 50 QUESTION PRACTICE TEST](#practice-test-1-50-question-practice-test)
    - [Section 15: AZ-900 - Course Wrapup](#section-15-az-900---course-wrapup)
        - [Thank You! [77]](#thank-you-77)
        - [Course Resources - Study Guide, Slides, Audio [78]](#course-resources---study-guide-slides-audio-78)
        - [Practice Test 2: 50 Question Practice Test](#practice-test-2-50-question-practice-test)
        - [Bonus: 50+ Hours of Hands-On Azure Practice for AZ-900 [79]](#bonus-50-hours-of-hands-on-azure-practice-for-az-900-79)

<!-- /TOC -->
- Practice tests: 2
- Questions: 100
- Lectures: 79
- Video: 7.5 total hours

1. Microsoft Azure Fundamentals: Describe cloud concepts
- Define cloud computing.
- Describe the shared responsibility model.
- Define cloud models, including public, private, and hybrid.
- Identify appropriate use cases for each cloud model.
- Describe the consumption-based model.
Compare cloud pricing models.

TODO:  Describe the consumption-based model.

## Section 1: AZ-900 Course
### Introduction [1]

Foundation
- Describe concepts
- Architecture and services
- Management and governance requirements

Cloud
- Cloud - just someone else's computer
- Rent computer resource on demand
- Resources: Servers, Storage, DBs, MQs, CDNs, Batch Processing Jobs
- 1000+ Azure Services

Home page

https://learn.microsoft.com/en-us/credentials/certifications/exams/az-900/

### LIVE DEMO: A quick look into Azure [2]

- Region - geo location
- Availability - redundancy (надлишковість, избыточность)
- security type
- OS, architecture
- VM size DS1_v2
    - compute optimized or general purpose
- RDP access
- open ports
    - HTTP 80
    - HTTPS 443
    - RDP 3389
- 49% discount with Azure Hybrid Benefit license
- Virtual Network
- Delete IP and NIC when VM is deleted
- Load Balancing
- Microsoft Defender for Cloud
  - Thread protection
- Shutdown time every certain time
- Recovery service vaults
- Backup policy
- Monitoring options
- Diagnostic options
- Metadata - contact in case of emergency (e-mail or phone number)
- Pricing
- Deploy
- Deployment Scripts - Programmatically

- 1-2 min to create VM
- Connect

### AZ-900 Exam Requirements [3]

https://learn.microsoft.com/en-us/credentials/certifications/exams/az-900/

#### Important: When exam was updated

The English language version of this exam was updated on July 31, 2023.

Languages, Ukraine 55 $

Never expired

Book an exam - online or in person

Prep PDF

Study guide for Exam AZ-900: Microsoft Azure Fundamentals

https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/az-900

Skills:
- Describe cloud concepts (25–30%)
- Describe Azure architecture and services (35–40%)
- Describe Azure management and governance (30–35%)

## Section 2: AZ-900 - Describe Cloud Computing

### What is Cloud Computing? [6]

Create Resource
- VM
- Web app - abstraction above the VM
- Function App - code for small pieces of code
- Logic App
  - connect 2 apps together
  - event triggers - do something else
  - chain things together, boxes and lines

Categories
- AI + ML
- Translator
- QnA Maker..Wow!
- ... Wow!

Type "Marketplace" => additional!!! but not supported by MS

### Shared Responsibility Model [7]

How MS and you have divided responsibility for security etc.

- On premises - you - All responsibility 
- Cloud VM Responsibility
 - MS Azure takes responsibility: 
    - Building security
    - Physical network
    - Physical computer security
- Cloud AppService Responsibility
    - Building security
    - Physical network
    - Physical computer security
    - + OS patches
    - + Shared Responsibility for Network and Firewall settings, App Settings, Auth Platform
- Cloud SaaS responsibility
    - Building security
    - Physical network
    - Physical computer security
    - OS patches
    - Cloud Resp: Network and Firewall settings, App Settings, 
    - Mixed resp: Auth Platform

### Public Cloud, Private Cloud, Hybrid Cloud [8]

#### Summary

- *private* = your resources, your control, flexibility, sca;ability
- *public* = cloud provider (Azure) resources, Lower costs, no maintenance, scalability—on-demand, High reliability
- *hybrid* - mixed

https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-are-private-public-hybrid-clouds/

#### public
The cloud resources (like servers and storage) are owned and operated by a third-party cloud service provider and delivered over the internet. With a public cloud, all hardware, software, and other supporting infrastructure are owned and managed by the cloud provider. Microsoft Azure is an example of a public cloud.

- Lower costs—no need to purchase hardware or software, and you pay only for the service you use.
- No maintenance—your service provider provides the maintenance.
- Near-unlimited scalability—on-demand resources are available to meet your business needs.
- High reliability—a vast network of servers ensures against failure.

#### private
cloud computing resources used exclusively by one business or organization. The private cloud can be physically located at your organization’s on-site datacenter, or it can be hosted by a third-party service provider. But in a private cloud, the services and infrastructure are always maintained on a private network and the hardware and software are dedicated solely to your organization.

- More flexibility — your organization can customize its cloud environment to meet specific business needs.
- More control — resources are not shared with others, so higher levels of control and privacy are possible.
- More scalability — private clouds often offer more scalability compared to on-premises infrastructure.

#### hybrid
combines on-premises infrastructure—or a private cloud—with a public cloud. Hybrid clouds allow data and apps to move between the two environments.

### Cloud Pricing [9]

predict, min-max, predictability...

Factors Affecting VM Pricing:
- Geo Location
- VM, Disk, Size, 
- Bandwidth, Performance
- Backup Storage
- Support Agreement
- OS SKU / License
- Reservation Saving Plan

Factors Affecting Cosmos DB Pricing:
- API Choice
- Standard Model / Serverless
- Consumed Storage
- Backup Storage
- Region / Regions
- Number of Operations per Second
- Optional Dedicated Gateway

100 options...

MS: 55+ free tier services

Some have limits

Pay for time
- Charge by time used
- Stop using service - stop the charges

Pay for GB
- 0,02 per GB per month
- pay for traffic inbound / outbound  from / to regions or to the internet

Pay for Operations
- charge per operation
- Ops: read, write, list, delete
- Pay per message
- Pay per query to the DB
- Cheap Penny/10000

Metrics

### LIVE DEMO: Pricing Calculator [10]

Azure - Pricing - Pricing Calculator

https://azure.microsoft.com/en-us/pricing/calculator/

Save, Export, Share

###   Quiz 1: ## Section 2 Quiz

Question 1:
What are the responsibilities of the customers according to the shared responsibility model?
- Patching guest OS and applications!

(no: fix infrastructure, no physical and env control, no config infrastructure Azure devices)

Question 2:
In which cloud service model can an organization offload its entire physical hardware responsibilities, potentially allowing it to shut down its on-premises data center?

- public cloud 

An organisation can close its DC by hosting its infrastructure in a public cloud. The public cloud is defined as computing services offered by third-party providers over the public Internet, making them available to anyone who wants to use or purchase them. The private cloud is defined as computing services offered either over the Internet or a private internal network and only to select users instead of the general public. A private cloud can be deployed on-premise or in a third-party hosted environment. A hybrid cloud combines the use of both public and private clouds.

Question 3:
A company has distributed its workload on both the Azure Cloud and some on-premises servers. What type of architecture is this?

- hybrid cloud

Good job!
A hybrid cloud is a type of cloud computing that combines on-premises infrastructure—or a private cloud—with a public cloud.

## Section 3: AZ-900 - Benefits of Cloud Computing
### High Availability  - Benefit of Cloud Computing [11]

High Availability - ability of the system to remain operational during *planned or unplanned outages*.

High Availability - is predetermined designed effort to avoid sources of downtime in planned and unplanned outages.

#### Planned Outages
- Security Patches
- Application Updates
- Hardware replacement
- Migrating to a new hosting provider

#### Unplanned Outages
- Hardware failure
- Network disruptions
- Power outages
- Natural disasters (hurricane, earthquakes)
- Cyber attacks (Human disasters)
- Software bugs
- Poor Scaling / architecture design (bootle necks)

#### Methods to Mitigate Planned Outages
- Gradual deployment strategy
  - Facebook don't deploy 100 services at once, 1, 10
  - 1-10-100-etc.
- Testing and monitoring of deployment
- Easy rollback plan
  - Azure Deployment slots
- Frequent Deployment
  - Less features - less deployment
- Automation of deployment
- DevOps mentality

#### Methods to Mitigate Unplanned Outages
- Every single core component has redundancy
  - Higher cost, but handle outage
- Azure for availability
  - Availability Sets
  - Availability Zones
  - Cross-Region Load Balancing / Front Door
- Constant real-time Health monitoring / probes
- Automation
- String security practices
- Be geographically distributed
- Have a disaster recovery plan
- Test that disaster recovery plan!
  - fire drills (противопожарные учения)!
- Need to recover quickly
- Min downtime
- Load testing - scaling, autoscaling
  - How many users can you handle

### Scalability  - Benefit of Cloud Computing [12]

Scalability - Ability of the system to accommodate by adding or removing resources resources as needed.

Adapt to Changing users patterns.

Handle traffic without requiring coding ar system design changes.

Does traffic fluctuate?

- based on time or day of the year
- Black Friday E-commerce web site
- School registrations in September
- Tax systems in April

#### Vertical Scaling UP/DOWN
- Vertical Scaling Up/Down = Add CPU/RAM
- Problem - upper limit
- Azure - 96 vCPUs, 384 Gb memory - largest server
- Does not improve availability
What if this is not enough?

#### Vertical Scaling OUT/IN
- Adding more servers
- No limits to scaling
- Additional complexity for Load Balancing
- Can improve Availability

#### Impact on Cost
- Add or Reduce resources
- Be perfectly sized

### Elasticity  - Benefit of Cloud Computing [13]

- ability **quickly and easily** scale up or down

#### Quickly and Easily

- Involve automation
- Called "autoscaling" in cloud computing
- Autoscaling 
  - Monitors metrics to determine how busy a system is.
  - Add resources when it exceeds a limit for being busy.
  - Remove / Shutdown resources when it falls below a limit for being not busy.
- CPU utilization ?? > 70 // < 30

#### Why?

- More efficient and cost effective
- Minimize computing "waste"
- Self-hosted systems tend to have "over-provisioned" resources (You have to over-provision)

Save Here, Spend There

### Reliability  - Benefit of Cloud Computing [14]

High Quality
- Availability - ability to be accessible and usable by users when they need it
- Reliability - perform its intended function without interruption
- Predictability

Reliability - the ability of a system to **perform its intended function without interruption** and with the high degree of accuracy.

- Looses some data sometimes? - Unreliable
- You have to trust

How to achieve?
- Auto-scaling
- Multi-region deployment
- Data backup and replication
- Health probes and self-healing

### Predictability  - Benefit of Cloud Computing [15]

Predictability - ability to forecast (prognose) and control the performance and behavior of a system.

Today? Tomorrow?

Include - predict future costs

How to achieve?
- Auto-scaling
- Load balancing
- Different instance types, sizes, pricing tiers
- Cost management tools
- API - automated programming
- Pricing calculators

### Security  - Benefit of Cloud Computing [16]

- Security - Full time job
- Hackers and cloud providers spend A lot of time, money, effort.
- Cloud providers go through security audits and international compliance certifications
- Tools - enable and monitor security

Shared Responsibility Model

**Fundamental challenge**

How to achieve?
- Compliance certifications
- Microsoft Security Response Center (MSRC)
    - looks for Suspicious Traffic in global network
- Always-on DDoS - additional fee
- Azure Policy and Blueprint - standards
- RBAC - Role-based access control
- Azure Active Directory
- Up-to-date platform services
  - Versions and security patches
- Update management
- Encryption by default
- HTTPS, SSL
- Dozens of security services like firewall

### Governance  - Benefit of Cloud Computing [17]

IT-Governance (Management)
- How your organization does business
- Policies, guides cloud operations
- Followed policies
- Basic auditing and reporting
- HIPPA, PCC, GDPR standards

How to achieve?

- Azure Policy and Blueprint
- Management groups
- Custom Roles
- Soft delete for storage accounts
  - Protect by malicious accidents
- Guides and best practices
  - Cloud Adoption Framework
  - https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/

```
Azure Blueprint allows you to ensure across all your subscriptions and all your departments that a certain minimum standards of policies, rules, resource groups and other things are being followed.
```

### Manageability  - Benefit of Cloud Computing [18]

- M. **of** the cloud
- M. **in** the cloud

- Templates
- Automation
- Scaling
- Monitoring and alerts
- Self-healing

In the Cloud
- Web-portal
- CLI
- APIs
- PowerShell

Why we need it?
- Easy or Hard to work?
- Consolidating monitoring and alerting
- ARM templates, Bicep, Terraform, etc.
- Autoscaling Up/Down

### Quiz 2: ## Section 3 Quiz

Question 1:
Which of the following is the correct description of the Azure Cloud Services benefit of scalability?

- A cloud service that maintains fast performance as demand increases.

Scalability refers to the ability to adjust resources to meet demand.

Question 2:
A company hosts a promotion application named App1 that all its customers use. App1 has low usage during the first three weeks of each month and very high usage during the last week of each month. Which benefit of Azure Cloud Services supports cost management for such usage patterns?

- Elasticity

Elasticity is the ability of a system to automatically grow and shrink based on application demand.

Question 3:
A system in the Azure Cloud is designed to withstand the failure of one or more components. What is this an example of?

- High availability

High availability refers to a set of technologies that minimize IT disruptions by providing business continuity of IT services through redundant, fault-tolerant, or failover-protected components.

## Section 4: AZ-900 - Cloud Service Types

### Cloud Service Types [19] IaaS, PaaS, SaaS

- "As a Service" - rent, not buy
- Commitment options for significant savings
- Pay for what you use (time, Gb, etc.)
- Cloud provider takes care of buying

#### IaaS - Infrastructure
- Computing - VMs, pay by seconds, CPU peed, RAM, optimizations
- Storage - 5 PB! Blobs, files, queues, tables, bug data - data lake
- Virtual Networking - virtual networks, subnets, don't cost anything, but ingress and egress bandwidth cost

5Gb egress - free, than pay for traffic between regions

#### PaaS - Platform 

##### PaaS - Level

You don't think on VM and infrastructure level.

- On top of basic infrastructure - software layer
- Service layer on top of IaaS - computing, storage and networking
- Middleware, development tools, database server and more.

- One example - **Azure App Service**
- Simply upload your code and config,
- **Do not worry about VM underneath**
- Including Scaling feature, CI/CD, containers, staging and development environments, etc., many-many more

Examples:
- **Azure App Service**
- **Manged Storage**
- **Azure SQL Database**

##### PaaS Networking
Software apps performing networking tasks:
- Azure Front Door
- Load Balancer
- Firewall

#### SaaS - Software

Typically Apps - like Skype, OneDrive, Dropbox, Google Docs

App is ready to be used,

Simply set it up and use it

Platform - set of features - it does not do anything. But SaaS is an app. 

### Serverless [20]

- "Serverless" Option - pricing model
- There are servers, you are not picking servers, CPU, memory
- Paying for service - not renting HW

Pricing models:

DTU - relative measurement of performance

Purchase Model - vCores

10x2=20 - double performance
- it has and how much storage you use and you're going to pay.
- This is a more complicated pricing model

Serverless 

Compute Tier = Serverless

One option - one price

- Paying per CPU second, pricing is 1/100 of a cent per CPU.
- Dynamic fluctuations
0 - 0 cost
So serverless SQL Database can be the cheapest option for databases if you have a very underused database

Cannot predict

#### Azure Serverless Services

- Functions
- Container Apps
- Kubernetes
- SQL Database
- Cosmos DB

ex: 

Functions - 1 million executions is free, than pay for additional 10000

you can save a lot of money

###   Quiz 3: ## Section 4 Quiz

#### Question 1
Which resource is an example of Infrastructure as a Service (IaaS) in Azure?
  - an Azure VM !

Azure web app, Azure logic app and Azure SQL database are all examples of Platform as a Service (Paas).

#### Question 2
Which service type is a complete development and deployment environment in the cloud?
- PaaS !
PaaS is a complete development and deployment environment in the cloud. 
PaaS is designed to support the complete web application lifecycle: building, testing, deploying, managing, and updating.

#### Question 3
Microsoft Office 365 is an example of which service type?
- SaaS !

Software as a service (SaaS) allows users to connect to and use cloud-based apps over the Internet. 
Common examples are email, calendaring, and office tools (such as Microsoft Office 365).

## Section 5: AZ-900 - Core Architectural Components of Azure
### Regions, Region Pairs, Sovereign Regions [21]
### Availability Zones and Data Centers [22]
### Resources and Resource Groups [23]
### Subscriptions [24]
### Management Groups [25]
### Quiz 4: ## Section 5 Quiz
## Section 6: AZ-900 - Azure Compute and Networking Services
### Azure Compute services [26]
### Azure Functions [27]
### Azure Networking services [28]
### Network Peering [29]

#### Address range

Virtual network:
10.0.0.0/16 - 65000

Each network divided into subnets

The IP address range 10.0.0.0/16 includes 65,536 addresses. This range starts from 10.0.0.0 and ends at 10.0.255.255. In IPv4 addresses, each octet can have values from 0 to 255 (inclusive), and since we have two octets for hosts (10.0.x.x), the total number of possible combinations is 256 * 256 = 65,536 addresses.

```

Диапазон IP-адресов 10.0.0.0/16 включает в себя 65,536 адресов. Этот диапазон начинается с 10.0.0.0 и заканчивается на 10.0.255.255. В адресах IPv4 каждый октет может принимать значения от 0 до 255 (включительно), и поскольку у нас есть два октета для хостов (10.0.x.x), то количество возможных комбинаций будет 256 * 256 = 65,536 адресов.

Обозначение "/16" в записи IP-адреса представляет собой CIDR (Classless Inter-Domain Routing) нотацию, которая указывает на длину префикса подсети. В данном случае "/16" означает, что первые 16 бит IP-адреса зарезервированы для сетевой части (сетевой адрес), а оставшиеся 32 - 16 = 16 бит предназначены для адресации устройств внутри этой сети (хостов).

В контексте диапазона IP-адресов 10.0.0.0/16, это означает, что первые два октета (10.0) предназначены для идентификации сети, а оставшиеся два октета могут использоваться для адресации устройств внутри этой сети. Количество доступных адресов для устройств равно 2^16, что равно 65,536.

```

#### 2 virtual networks: how to connect?
- not allowed by default, blocked
- connect - peering

vnetdemo1 | Peerings
- 1 or 2-way traffic
- Add peering vnet1-to-vnet2
- Remote virtual network
  - Reverse: vnet2-to-vnet1 (will create a peering in vnet2)
- Add

Any Db from vnet1 - will access vnet2
10.0.0 talk to 10.0.1 network

### Public and Private Endpoints [30]

Who can access the resource and how?

- Enable public IP - this is a door
- Enable bublic access from selected virtual network and IP addresses
  - need Subnet storage account
- Disable public access and use private access
  - Add private endpoint (on other side)

### Quiz 5: Section 6 Quiz

#### Question 1:
Which Azure service provides serverless computing?
- Azure Functions
Good job!
Azure Functions is a serverless computer service that allows a piece of code to be deployed and executed without needing server infrastructure or any configurations.

#### Question 2:
Which Azure service provides network traffic filtering across multiple subscriptions and virtual networks?
- Azure Firewall
You can restrict traffic to multiple virtual networks in multiple subscriptions with a single Azure firewall. Azure Firewall is a managed, cloud-based network security service that protects your Azure Virtual Network resources. It’s a fully stateful firewall as a service with built-in high availability and unrestricted cloud scalability. Reference: https://learn.microsoft.com/en-us/azure/firewall/overview

https://learn.microsoft.com/en-us/azure/firewall/overview

#### Question 3:
An organization plans to migrate all its data and resources to Azure. The organization’s migration plan states that only Platform-as-a-Service (PaaS) solutions be used in Azure. Which Azure service should be used?
- Azure App Service
Azure App Service is a fully managed PaaS (Platform as a Service) service for developers. Reference: https://learn.microsoft.com/en-us/azure/app-service/overview


## Section 7: AZ-900 - Azure Compute Demo

Gear - change settings

### LIVE DEMO: Creating a Virtual Machine (VM) [31]

- Compute category
- Tabs
- Linux - the most popular
- Resource group, region, unique name
- Region - choose closest to consumer
- Availability options 
  - there is no LB
  - Availability zones - multiple VMs for redundancy
- Hundreds of images, 
  - Sql Server 2022 on Windows Server (preinstalled with license)
  - Developer machine with Visual Studio
  - CentOS
- Instance types (RAM, CPU,...) - filter Size
- Admin Account
- Open ports: HTTP 80, HTTPS 443, RDP 3389
... 32 seconds

### LIVE DEMO: Connecting to a Virtual Machine [32]

#### Run machine
- Public IP assigned
- Not able to connect by default - Networking (check RDP port)
- Test Connect, Native RDP, Download RDP file
- Trust this machine, Connect, More Choices, creds.
- Remote Certificate is Vsalid:  yes

#### Server Manager - machine config

VM:
- For Web Server - Add roles
- Role-based or feature based installation
- Server roles - [x] Web Server (IIS) role
- Install
- Browser: localhost (80) - default page

Portal:
- Size: can Resize

- Browser - VMs Public IP

### LIVE DEMO: Creating Azure App Services / Web Apps [33]

WebApp - higher level (PaaS)
- deploy code and config into Azure
- _name_.azurewebsites.net
- Choose Runtime stack
- Publish
  - Code
  - Docker container
  - Static Web App
- OS: Windows or Linux
- Region
- Pricing: Windows Plan or new app service plan
  - Or Select App Service Plan for Dev or Prod
  - Basic B1
- ACU = Azure Compute Units - performance попугаи
- Redundancy in Premium options (not Basic or Standard)
- Gitgub Actions
- Enable public access / or specific virtual network
- Create

### LIVE DEMO: Azure App Services In Action [34]

- WebApp - Abstraction over the VM
- No control on VM, no RDP option ...
- Settings
  - Scale Up/Down (switch from B1 to S1 Standard S1 plan)
  - Scaling - Manual / Autoscaling - Rules Based
  - Autoscaling settings
    - Scale based on metrics (CPU > 70 => Up, < 20 => Down)
- Console - C drive
  - C:\home\site\wwwroot> dir or ls -ls

#### Deployment Slot
- Prod or Stage, Swap slots
- A/B tests traffic %, 10% - A, 90% - B

### LIVE DEMO: Creating Azure Functions [35]

- _unique_name_.azurewebsites.com
- Code or Container Image
- 6 built-in: .NET, Node.js, Python, Java, PowerShell Core, Custom Habdler
  - Custom Habdler - PHP handler dll
- Version, Region, OS
- Hosting Plan
  - Consumption (Serverless)
    - optimized for serverless and event-driven workloads, cheap
  - Functions Premium
    - Event based scaling
    - network isolation
  - App Service Plan
    - for large SKUs, co-locate Web-Apps and functions

- Need storage account
- Enable public access
- Github - continious deployment
- Can Write it in a portal

HTTP Trigger
Timer Trigger
Queue Storage trigger...
....

https://github.com/Azure/azure-functions-templates


Auth Level
- Function
- Anonymous
- Admin


Azure Functions C# script (.csx) developer reference

https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-csharp?tabs=functionsv2%2Cfixed-delay%2Cazure-cli#http-trigger

```cs
#r "Newtonsoft.Json"

using System.Net;
using Microsoft.AspNetCore.Mvc;
using Microsoft.Extensions.Primitives;
using Newtonsoft.Json;

public static async Task<IActionResult> Run(HttpRequest req, ILogger log)
{
    log.LogInformation("C# HTTP trigger function processed a request.");

    string name = req.Query["name"];

    string requestBody = await new StreamReader(req.Body).ReadToEndAsync();
    dynamic data = JsonConvert.DeserializeObject(requestBody);
    name = name ?? data?.name;

    string responseMessage = string.IsNullOrEmpty(name)
        ? "This HTTP triggered function executed successfully. Pass a name in the query string or in the request body for a personalized response."
                : $"Hello, {name}. This HTTP triggered function executed successfully.";

            return new OkObjectResult(responseMessage);
}
```

### LIVE DEMO: Kubernetes and Azure Container Instances [36]

#### Summary
- Container Instances - simplest, demo
- Container App - middle area between enterprise grade complexity and demo application, simple scaling
- Azure Kubernetes Service (AKS) - enterpriise complexity

Container 
- Running in functions, 
- In VM (docker)
- Web Apps
- Service Fabric...

1) Azure Kubernetes Service (AKS) orchestration
3) Container App (next section)
2) Container Instances - simplest, quickest,  smalest way to deploy a container.
  - Testing or demo something.
  - It is not about scalability
  - Image source
    - Quick Start images - 3 imagest Simple Win or Linux
    - Or Azure Container Registry
    - Or Other registry (docker hub...)

- Networking: Public, Private, None
- Restart Policy: On Failure.

Events - Activity review

### LIVE DEMO: Azure Container Apps [37]

3) Container App
Create - Container Apps Environments

More Functional than a container Instances
- Scaling.. Similar as with Web Apps

- Scales and replicas
- Min - Max 0-10
- Rules for Scaling - similar to web apps

So it's that middle area between enterprise grade complexity and demo application.

### Delete resources

Simple - delete resource group.

Some complexity with storage accounts with "soft delete" option.

## Section 8: AZ-900 - Azure Storage

### Overview of Azure Storage [39]

- Container (Blob) Storage
- Disk Storage
- File Storage
- Storage Tiers - different options for storage

- Functions require storage account
- General purpose v2 (gpv2) account - the most common
- Azure Data Lake Storage Gen2 - huge storage for big data, Petabytes
- Pay per GB 1.8 cents per GB
- Cold and Hot - storage
- BLOB - Binary Large OBject, just a file
- A collection of binary data in a form of file or data in DB - stored in a storage account
- In AWS - a Storage account is called Simple Storage Service (S3)

Many options
- Access tiers - Hot, Cool, Cold, Archive
- Performance Tiers - Standard and Premium
- Location
- Redundancy / Replication
- Failower options - use backup

Disk Storage
- Azure VM Disks
- **Managed Disks**
  - in an unmanaged storage account you're paying by the gigabyte
  - with managed (by Azure) disk, they have tiers and you're reserving capacity in advance.

### LIVE DEMO: Create an Unmanaged Storage Account [40]

- The name must be unique across all existing storage account names in Azure.
- Region -> cost is different
- Premium - a lot faster.
BLOB block size  - let's say it's 32 megabytes.
=> Blockings

Redundancy

- ZRS - Zone redundant storage - 3 copies of your file in each datacenter
- LRS - Locally - redundant storage - no zonal redundancy
- GRS - Geo - redundant storage - choose regions
- GZRS - Geo-zone-redundant storage

Enable storage account access keys

Data Lake - more storage for big data

Access Tier (important)
- Hot: (Default) access - frequently accessed, day-by-day usege scenarios, pay per access
- Cool: Infrequently accesses data and access scenarios
  - Price = Price / 2, save 50 %
- Archieve - save 90 %, hours to access, backups

Enable file share (SMTP protocol)

Public access with the security key

Door is closed with the key

Networking Routing:
- Microsoft network routing
- Internet routing

Soft deleteing

Versioning

Immutability - file cannot be changed
- may have some legal implications, log files, emails,...
- where you don't want someone to be able to delete it.

Encryption type:
- MMK - Microsoft Management Keys
- CMK - Customer Management Keys

+ Additional level encryption - Enable infrastructure level encryption

### LIVE DEMO: Upload Files to a Storage Account [41]

Stotage account contains 4 types of data.

It's completely separate.

- Containers
- File shares
- Queues - 1 write, 2 read
- Tables - cheap but not as reliable as a Cosmos DB.

Container - Bucket to store

- Container - Bucket to store
  - private or public
  - Upload blobTier
  - Upload, get URL
  - Need security key to access
    - Storage Account | Access Keys, get storage key, to have **admin control on storage account**
    - Containers - file - ... - Generate SAS - Shared Access Signature - Key, Read permissions, Expiry Date
  - Generate SAS token and URL - so **can access file**.
  - Door is locked need a key
- Geo replication
- Lifecycle Management

Add rule
- Modif < 30 days => move to cool or archive storage
- Save money

### LIVE DEMO: Azure Storage Explorer & Storage Browser [42]

Applications - reading and writing

You could use Azure functions that listen for an event and create a file and stores that file in the storage account.

- Open in Explorer
- Storage Browser (preview) - NOT for PROD!

Switch to Storage Explorer (in portal)

### AZCOPY [43]

https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10

- How to copy data between blob containers?
- Download and upload? No!
- Copy Inside the Azure network
- Download AzCopy or use it in Cloud Shell
- Source - Generate SAS - Read
- Destination - Generate SAS - Write permission
- Copy accross subscription into the second container

```
azcopy -?

azcopy copy 'source_url' 'destination'
```

### Azure File Sync [44]

https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-extend-servers

File Share

File Server and file share in the cloud

SMB protocol - mount file shares (Linux and Windows)

Storage account
- SMB 3.1.1 protocol
- NTLM v2 authentication
- AES-12B-GCM encryption

4 components:
1) Storage Account
2) Storage Sync Service in Azure
3) Azure File Sync agent
4) Local file server

- create the Storage Sync service in the same region as your file server
- create sync groups contain endpoints on the on your company side
- install the file sync agent software within your organization
- allow files to be synchronized from your file share running within your company and the storage account

### Azure Migrate [45]

Tool for migrating into the Azure

Explore your evvironments, servers and databases

Mapping tools

Make plans to migrate then int Azure

Costing then out

Which servers can be migrated as-is and which need upgrades?

https://learn.microsoft.com/en-us/azure/migrate/

Tutorial: Discover physical servers with Azure Migrate: Discovery and assessment

https://learn.microsoft.com/en-us/azure/migrate/tutorial-discover-physical

### Azure Data Box [46]

Pass 500 Terabytes into Azure?

Speed Test - Upload Speed!

Estimate - in Days? Weeks?

Phisical Devices 
- hard disks shipped to office,
- Copy 
- and ship back to Azure

HDD - 100 TB, 8 TB, 1 PB

Encrypted on device

And so Azure Stack has an edge device that you can install in your data center, which is a Microsoft piece of hardware.
Which helps you do cloud stuff in your own data center.
And also there can be a virtual data box, which is much like a virtual machine that has a particular agent on it.
So there are online ways of getting your data into the cloud.
But if you don't have a speed problem, you can use one of these virtualized products or the Azure Stack

### Quiz 6: ## Section 8 Quiz

#### Question 1:
Which type of storage is not supported by Azure Storage Account?
- Cosmos DB is NOT SUPPORTED in Azure storage account Standard general-purpose v2
The Azure storage account Standard general-purpose v2 is the most common type which supports:
- Blob Storage (including Data Lake Storage), 
- Queue Storage, 
- Table Storage, 
- Azure Files. 
Reference: 
https://learn.microsoft.com/en-us/azure/storage/common/storage-account-overview

#### Question 2:
Which Azure service can be used to synchronize data between an organization’s on-premises Windows servers and an Azure file share?

- Azure File Sync

Azure File Sync is a service that allows users to sync files between on-premises and cloud Windows servers. 
Reference: 
https://learn.microsoft.com/en-us/azure/storage/file-sync/file-sync-introduction

#### Question 3:
Which Azure service can not be used to move individual files back and forth between Clouds?

- Azure Storage Account

Good job!
Azure Storage Account provides access to your Azure storage resources. Azure Storage Explorer allows you to upload to Azure, download from Azure, or move between storage accounts. Azure File Sync is a service that allows users to sync files between on-premises and cloud Windows servers. AzCopy is a CLI tool for copying blobs or files.

#### Hmmmm ... My AzCopy Question 
```
AzCopy is primarily designed for working within the Microsoft Azure ecosystem and isn't explicitly intended for transferring files directly between different cloud providers (such as Azure, AWS, Google Cloud, etc.). AzCopy supports efficient data transfer within Azure storage solutions (e.g., Azure Blob, File, Table, Queue storage) and between an Azure Storage account and an on-premises system.

For transferring files between different cloud providers, including Azure and others like AWS or Google Cloud, AzCopy might not be the most suitable tool as it's tailored for Azure-centric operations. In such cases, you'll likely need to explore other methods or tools specifically designed for cross-cloud data transfers.

There are various third-party tools, services, or APIs available that specialize in cross-cloud data migration. These tools are often more suitable for transferring files or data between different cloud platforms and can handle the nuances and authentication methods required by each cloud provider.

Always refer to the specific documentation and resources provided by the respective cloud platforms for the most updated and recommended approaches to transferring data between clouds. Additionally, explore third-party solutions specialized in cross-cloud data migration for efficient and secure transfer of files between different cloud providers.

```

https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10


## Section 9: AZ-900 - Identity, Access and Security
### Identity and Azure Active Directory [47]

#### Identity
- Def: **Identity** - in computing, a representation of a person, application or device
- Login = provide your identity
- Phones, printers - also have identity

#### Security: Prove
- Cannot just declare, that you are John Doe.
- Prove it. Password, Certificate (cryptographically-signed file).

#### Security: Client - Server Model

Client - Server Model, Passwords or hash - Traditional Model

Password checkers, bugs, cookies, copy token problems

MD5 - reverce enjineered, salt, hacked 12345, "Password", etc.

**Microsoft Azure Identity Management System**
and it's based on a popular identity management system that companies used to call **Active Directory**.

- It's important to note that Azure Active Directory
- is not just a copy of Windows Active Directory that's running in the cloud.
- It is completely redesigned.
- It works differently in many different ways.
- It doesn't have the same functionality.
- Although over the years, Microsoft has been adding features and functionality to the cloud version.

OLD name: Azure Active Directory (Azure AD, AAD)
NEW name: **Microsoft Entra ID** Part of **Microsoft Entra**

Traditional AD - DOES NOT work with Internet protocols

Entra ID = "identity as a service" for your apps

No code for 
- handle users
- passwords
- password reset etc.

Identity Provider

1) client asks the server to log in,
2) it's directed to the Azure AD.
3) user ID and password => Azure AD
4) Azure AD returns a token, which is cryptographically signed
5) client returns the token to the server
6) the server trusts the token.

And in that way, the user ID passwords never passed to the server directly.

- SAML
  - https://www.cloudflare.com/learning/access-management/what-is-saml/
  - Security Assertion Markup Language
  - is a standardized way to tell external applications and services that a user is who they say they are. SAML makes single sign-on (SSO) technology possible by providing a way to authenticate a user once and then communicate that authentication to multiple applications. The most current version of SAML is SAML 2.0.
- OpenID
  - https://dotnetopenauth.net/
  - https://oauth.net/getting-started/
  - https://openid.net/developers/
- WS Federation
  - (Web Services Federation) is an Identity Federation specification, developed by a group of companies: BEA Systems, BMC Software, CA Inc. (along with Layer 7 Technologies now a part of CA Inc.), IBM, Microsoft, Novell, Hewlett Packard Enterprise, and VeriSign. Part of the larger Web Services Security framework, WS-Federation defines mechanisms for allowing different security realms to broker information on identities, identity attributes and authentication.[1] WS-Federation focuses on federated identity and trusting authentication tokens across different realms, privileged password management is concerned with the security, control, and audit of high-risk account passwords within an IT environment

### Benefits of Microsoft Entra ID (formerly Azure Active Directory (Azure AD)) [48]

- Security
- Dev time
- More features (such as access revires)
- Centralized administration
- SSO - Single Sign-On - Only one user ID and password
- Use on premises AD 
- Integration with other Azure services and storage accounts...

### Authenication vs Authorization [49]

Authenication = why they are?

Authorization = ensuring that the user is permitted to perform an action

Move away from CHAOS - "all authenticated users having admin access" - 

### Azure AD Conditional Access [50]

Conditional Access

UNUSUAL EVENT

- User A attempts to log in to the app from whithin the company office **as she does every day**
  - Please Send code
- User B attempts to log in for the first time in 4 months
- Admin C tries to login from their phone
  - Additional login checks
- Admin D attempts to login from location 1200 miles from the office

You can treat some access as "routine" and some as "not normal"

SIGNAL -> DECISION -> ENFORCEMENT

### Azure Multi-Factor Authentication (MFA or 2FA) [51]

Require 2 or more pieces of evidence (factors) in order to log in

2 factors
- password
- time-limited code sent to you

3 factors:
- Something you **know** - i.e. password
- Something you **have** - i.e. mobile phone, or access to email account
- Something you **are** - i.e. fingerprint (biological)

4 ways to get multifactor authentication
- SMS
- email
- authenticator app
- voice phone call

### Passwordless authentication [52]

Passwords = low security but convinient
Passwords + 2FA = Hight Security but inconvenient

Passwordless authentication
- Gestures to sign in
- Biometrics: Face recognition
- Biometrics: Fingerprint

Pin code is tight to device

- Are you attempting to use this app? 
- Yes (phone) - Approve singn in, 2 digit number.

### Role-Based Access Control (RBAC) [53]

Role-Based Access Control (RBAC) Control

Microsoft Azure ad supports a few different access systems:
- RBAC - preferred
- have token? (ticket) - can log in
- claims-based access control 

- Type of jobs in a company
- Create roles that represent the common taskjs of the job
- Define 25 different roles within Azure AD, then assign permissions to the role.
- Provide gramular permissions to the role
  - Developer - certain levels of permissions
  - Manager - certain levels of permissions
  - HR -...
- Assign users to the role
- Assign user to more than 1 role
- You are not assigned permissions to individuals
- 20 000 people and permissions - mess
- Roles - simplifiing 

Azure built-in permissions:
- Reader - read-only
- Controbutor - read and write, full access
- Owner - ability to give/assign permissions to other people
  - Be very careful

You can create your own permissions and combination of them

### Zero-Trust Model of Security [54]

Zero-Trust Methodology

1 door is open? - Everything is open

Key for the room, kitchen

Don't assume everything behind the firefall is safe

The old way: API, and one system can call the other, no security involved because it's all inside the house.

The zero trust model: says "don't trust each other".
- Azure AD
- client secret
- certificate

3 main principals:
- Verify explicitly
- Use the least priveleged access
- Assume breach (Imagine there is a hacker that has access to your network)

Imagine there is a hacker that has access to your network.
But if you do your security right, applications are talking to each other, it's encrypted, they're using a very secure model,
like a client certificate for encrypting that communications.
A hacker living on your network cannot even intercept that.

- Use every available method to validate identity and authorization
  - who is asking?
  - is who the say they are

- Just-in-Time (JIT)
- Just enough-access (JEA)

- Security even inside the network;
- Encryption;
- Segmentation of network
- Threat detection
- Permissions to deeper system
- Have active thread detection
  - Someone repeatedly tries to yse ID and password
  - => 24 h account lock
- Download source code or DB, or all data? Suspicious.

Rules
- Identity: Verify and secure each identity.
- Devices: ensure compliance and health status:
  - updated OS, (not Windows 95)
  - Browser updates
  - Security patches
- Applications: appropriate in-app permissionsm monitor user actions
- Data: data-driven protection, encrypt and restrict access
- Infrastructure: network, 
  - robust monitoring 
  - detect attacks
  - block and flag risky behaviour
  - virtual networks, security groups
  - monitoring, reporting, alerts - intelligent automations
- Network: encrypt all communications

### Defense in Depth [55]

- don't just focus on a single tool to protect you.
- It's like having a security of your house or your building and only thinking a single lock will protect

Security Layers
- **Physical** - i.e. Door locks and key cards
  - Protect your office and devices
- **Identity and Access**
  - Azure AD
  - firewalls 
  - denial of service protection applications,
- **Perimeter**
  - the perimeter of your network
  - **Network**
  - NSGs and subnets that are dividing your network
  - Deny by Default
  - Azure Active Directory servers.
- **Compute** Layer
  - Limit Remote Desktop Access
  - Windows Update and Patches
  - Bastions
- **Application**
  - i.e. API management
- **Data** 
  - i.e. virtual network endpoint
  - fields validation
  - anti form injection..

Azure tools - removed from AZ-900 ezam

https://www.geeksforgeeks.org/defense-in-depth-strategy-in-microsoft-azure/

https://blog.devolutions.net/2019/02/the-basics-of-zero-trust-architecture-8-best-practices


### Microsoft Defender for Cloud [56]

- Complex product, more security
- Protects services (list of services)
- 15 $ per service ?? per month - TODO check
- Analisys
- Recommendation
- PCI HIPPA compliance
- Antivirus
- Workload protection
- Firewall Manager
- Inventory
- Info protection

### Quiz 7: ## Section 9 Quiz

#### Question 1: Azure AD Multi-Factor Authentication (MFA) typically include any or all of the following **except**:

- **except** Someone you know

Azure AD MFA works by requiring two or more of the following authentication methods: 
• Something you know, typically a password. 
• Something you have, such as a trusted device that's not easily duplicated, like a phone or hardware key. 
• Something you are - biometrics like a fingerprint or face scan. 

Reference: 

https://learn.microsoft.com/en-us/azure/active-directory/authentication/concept-mfa-howitworks

#### Question 2
An organization plans to modernize its applications and network infrastructure in Cloud by migrating all network resources to Azure and decommissioning its on-premises data centre. What solution should be used to minimize the impact on users after the planned migration?

- Sync all on-premises AD user account to Azure AD

#### Question 3
Which tool can continually assess your cross-cloud resources for security issues and allows you to review your secure score?
- Microsoft Defender for Cloud
- The secure score feature in Defender for Cloud enables you to achieve below two main goals:
• to help you understand your current security situation 
• to help you efficiently and effectively improve your security 

Reference: https://learn.microsoft.com/en-us/azure/defender-for-cloud/secure-score-security-controls

## Section 10: AZ-900 - Cost Management in Azure

### Factors that Affect Cost [57]

Different services billed bt different factors

Free Services:
- Resource Groups
- Virtual Networks - (up to 50)
- Load balancer - (basic)
- Azure Active Directory (basic)
- Network Security groups
- Free-tier web apps (up to 10)

The rest - 2-3-more metrics

- Azure Functions:
  - 1 million executions per month - Free
  - 20 cents per million executions
  - Cheapest VM - 20 $ per month

Pay per usage services
- Functions
- Loginc Apps
- Storage per Gb
- Outbound bandwith - First 5 Gb is free
- Cognitive Services API (ML, AI)

Pridictability and Stability in pricing
- Variable Pricing
- Fixedf price for computing power or storage capacity
- Reserved instances - Discount for 1-year or 3-year commitment in VM
- Multi-tenant or isolated environment, dedicated hosting

Bandwith
- First 5 Gb is free
- 1 PB of data transfer = 52 000 $ data transfer charges

Azure Pricing Calculator

Azure Advizor

### Azure Pricing Calculator [58]

https://azure.microsoft.com/en-us/pricing/calculator/

- Add to Card, tune, licenses, observe costs.
- Select VM ON time, save money
- Export and share estimates, Save for later.
- Storage Reservation Options

Not 100 % accurate

Configurable options
- Region
- Tier
- Subscription type
- Support Options
- Dev/Test pricing

### Total Cost of Ownership Calculator [59]

https://azure.microsoft.com/en-us/pricing/tco/calculator/

TCO - Total Cost of Ownership - On-Premices

- Comparison with Azure cost

- Electricity
- Cooling
- Internet Connectivity
- Rack Space
- Setup labor
- Maintanance labor
- Backup

Dozens of service tweaks

### Azure Cost Management - Portal[60]

- Cost Management Service in Portal
- Cost Analisys, Recommendations, Budgets, Ivoices
- Analyze spending over time, Tracking
- Budget notifications - Why?
- History of invoices
- Reports, emails

### Resource Tags [61]

Add metadata to Azure resources

Resource Tags - a way for you to add what is called metadata to your resources for your own personal use.

VM was created
- Who created a VM ?
- Why ?
- What project It's part of ?
- Where the billing for that ?

Helps with billing and support issues
The main purpose for this is for billing and support.

What resources the most consuming?

Goto any rs -> "Click here to add tags"
Or "Tags"

Tag = name-value pair

This Data is not encrypted

CreatedBy

Cost Management - Cost Analysis

Generate reports based on tags

Add filter - ... created by me, or with tags....

- Cost by Resource
- Resource groups

### Quiz 8: ## Section 10 Quiz

Question 1:
Which of the following is not a factor that users can consider affecting costs in Azure?

- Data Center Maintenance

The costs associated with DC facility maintenance, e.g., power, cooling, and physical security are typically included in the service provided by the cloud provider and not billed separately to the cloud customer.

Question 2:
Which tool can be used to estimate the cost savings of workload migration from on-premises to Azure cloud?

- Total Cost of Ownership (TCO) calculator

The Total Cost of Ownership (TCO) calculator is a free tool that anyone can use to estimate the costs of migrating their data and applications to Azure and predict potential savings. Reference: https://azure.microsoft.com/en-au/pricing/tco/calculator/


Question 3:
An organization has five branches. The organization plans to generate billing reports with Azure resource utilization of each branch from the Azure portal. Which tool can be used before the organization generates the reports?

- Tags

Tags provide metadata that can be added to Azure resources to organize related resources and help with billing and support issues. Reference: https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources

## Section 11: AZ-900 - Azure Governance and Compliance
### Azure Governance and Compliance [62]

- Organization and Managemtnt
- IT-rules to implement
- Example: Always have daily backup enabled on every server
- Incident - Backup
=> Policy

Option 1) Send an e-mail with the rules and assume everyone reads it and remembers it

But what with new emploee?

Option 2) Use Azure Tools to enforce the rules (or simply audit compliance)

#### Tools
- Azure Blueprints
- Azure Policy
- Resource Locks
- Microsoft Preview - large tool

### Azure Blueprints [63]

#### Blueprints - tamplates for future subscriptions

Options
- You can create an Azure subscription without a template (EMPTY)
- With a blueprint, you can predefine a number of items:
  - RBAC
  - Policy Definitions
  - Resource Groups
  - ARM templates
 - Create subscription from blueprint (you already have your company's standard sets of policies ready to go.)

Now, one of the interesting things though is that 

#### the only way of assigning a deny permission

using a blueprint is **the only way of assigning** what's called **a deny permission**.

But you can't specifically explicitly assign someone a negative permission, a denial,

```
You can't say this person shall never get access to this resource. That is not a feature of Microsoft Azure except in Azure blueprints.

And so you can set up a set of denial permissions and when they're assigned to a subscription
```

So there are ways of creating some complicated multiple subscriptions in groups and blueprints allows you to have some standards across all of these subscriptions.

### Azure Policy [64]

- assign rules to a resource group
- assign rules to the entire subscription
- evaluate compliance to those groups

- "every virtual machine must have Azure backup daily."
- Assign this policy to a resource group or to a subscription
- every VM in this scope must have a backup

Example of Built-In Policies

- Require SqlServer 12
- Allowed Locations
- Allowed VM SDKs
- Apply tag and its default value
- Not allowed resource type

There are literally thousands of built-in policies,

And you have the option of creating your own custom policies.

Can create custom policy using JSON definitions

### DEMO: Azure Policy [65]
### Resource Locks [66]
### Microsoft Purview [67]
### Quiz 9: ## Section 11 Quiz
## Section 12: AZ-900 - Tools for Managing and Deploying Azure Resources
### Azure Portal and Command Line Tools [68]
### LIVE DEMO: Create Resources Using Command Line [69]
### Azure Arc [70]
### Infrastructure as Code (IaC) [71]
### ARM Templates [72]
### LIVE DEMO: Generate ARM Templates in the Azure Portal [73]
### Quiz 10: ## Section 12 Quiz
## Section 13: AZ-900 - Monitoring Tools
### Azure Advisor and Azure Service Health [74]
### Azure Diagnostics Settings [75]
### Azure Monitor [76]
### Quiz 11: ## Section 13 Quiz
## Section 14: 50 QUESTION PRACTICE TEST
### Practice Test 1: 50 QUESTION PRACTICE TEST
## Section 15: AZ-900 - Course Wrapup
### Thank You! [77]
### Course Resources - Study Guide, Slides, Audio [78]
### Practice Test 2: 50 Question Practice Test
### Bonus: 50+ Hours of Hands-On Azure Practice for AZ-900 [79]
