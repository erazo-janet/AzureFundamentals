## What is Azure?
Azure is a set of cloud services that gives you the freedom to build, manage and deploy applications with more than 100 services avalaible
Many teams start exploring the cloud by moving their existing applications to virtual machines that run on azure 
Its a private and public cloud platform

## How does Azure work behind the scenes?
- Azure uses virtualization 
- Behind the scenes, virtualization separates the hardware and operating system using an abstraction layer called hypervisor which  emulates all the funcations of a real computer and the CPU in a virtual machine and it can run multiple virtual machines at the same time and optimize the capacity of the extracted hardware and each virtual machine can run any compaitble operating system such as  run windows and linux 
- Azures takes this technology on a global scale and has data centers all around the world . Data centers have racks of servers, and  each server includes a hypervisor to run multiple virtual machines.  network switch provides connectivity to all those servers and one server n each rack runs a fabric controller 
- One server in each rac runs a fabric conroller which is connected to the orchrastor which is responsible for everything that happen in azure including responding to user requests, where users create request through the orchrasterors web API, and the web api can be called by mini tools including the user interface of the azure portal  
- In the request, in the portal goes through the API, then the orchestrator where it packages everythingt thats needed, takes the best server rack then sends the request then into the fabric controller
- once the fabric controller creates the virtual machine, the user can connect to it 

## Azure Services
8 main services include:
- Computing services -Cover virtual machines, containers,  server less computing
- Azure virtual machines (windows or linux) thats hosted in Azure
- Kubernetes service - cluster management for virtual machines that run containerized services
- Cloud storage - disks attached to virtual machines, file shares, databases
-- Azure Blob Storage - Storage service for large objects like video files or bitmaps
-- Azure File Storage - Files shares that can be acessed and managed like a file server
-- Azure Queue Storage - A data store for queuing and reliably delivering messages between aplicaions
-- Azure Table Storage - A NoSQL store that hosts unstructured data independent of any schema
- Networking - private network connections to your on premise environment and control traffic into the environment
-- Azure virtual network - connects VMs to incoming virtual private network (VPN) connections
-- Azure VPN gateway 
-- Azure Traffic Manager
--Azure Firewall
-- App Hosting - run entire web application in a  managed platform in windows or linux
- Artificial Intelligence - including machine learning to help search and report on data analytics
-Internet of Things - integrate devices and manage with iot hubs to create dashboards and apps to manage assets
- Integration - allow for workflow to orchestrate business workflows
- Security - included in the infrastrure and access to each service and the data in it 
