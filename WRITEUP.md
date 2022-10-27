# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

_For **both** a VM or App Service solution for the CMS app:_

- _Analyze costs, scalability, availability, and workflow_
- _Choose the appropriate solution (VM or App Service) for deploying the app_
- _Justify your choice_

analysis
Virtual Machines

Some of the Advantages of using VMs are:
cheaper initial outlay than buying and maintaining hardware
support for both Linux and Windows virtual machines
It gives you total access and command over the VM.py
Custom images may be installed on VMs, which make them a great option for moving servers from on-premises to the cloud.
To ensure high availability, scalability, and redundancy, many VMs can be clustered together. Virtual Machine Scale Sets and Load Balancers are your two scaling choices. These topics will be discussed in another course.
There are other sorts to select from, such as compute- or memory-optimized virtual machines, along with different CPU, RAM, and storage capacities.

App services
.NET,.NET Core, Java, Ruby, Node.js, PHP, or Python support for various languages
Auto-scaling, high availability, and assistance for both Linux and Windows platforms.
Model for continuous deployment utilizing any Git repository, including Azure DevOps.
Scaling may be vertical or horizontal. By altering the App Service price tier, vertical scaling increases or reduces resources allotted to our App Service, such as the quantity of vCPUs or RAM. The number of Virtual Machine instances that our App Service is using might change due to horizontal scaling.
The pricing varies according on the plan you select, and you may specify how much hardware will be used to host your application. The levels are divided into three categories: Dev/Test, Production, and Isolated. For the exercises, we'll be utilizing Dev/free Test's option.

My choice
I picked App Service due to the fact that CMS software is lightweight, doesn't need a lot of computing power, and is simple to deploy using Azure.

### Assess app changes that would change your decision.

I have limited control over the host server while using the App service; if I want to modify the OS or install applications on the server, I must use the Virtual Machine option.

_Detail how the app and any other needs would have to change for you to change your decision in the last section._
