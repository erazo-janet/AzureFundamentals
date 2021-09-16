# Terms
Here are the terms I transitioned into flash cards and memorized them for the exam! 
- High Avaliability - Data stored in the cloud are copied to more than one data center. If anything happens to one data center, the data can be recovered from another data center
- Fault Tolerance - If a computer system or technology infrastructure component fails (hardware or software), a backup component takes over. That way, if there is a fault in the application or system, the service can continue to work
- Disaser Discover- Data in the cloud gets copied to other regions. If there is a disaster in one region and every data center in that region goes down, a data center in another region will still have a copy of that data. For example, if the West US data centers goes down, the East US data centers will be able to recover the data
- Scalability - This allows cloud users to expand or decrease an applications size based on the number of users in the system. You can increase the workload on a current resource (Scaling up) or decrease the workload in the resource (Scaling down)
- Elasticity - This allows cloud users to expand multiple applications/resources running in the cloud when there are many users in the system (Scaling out) or remove resources when there are fewer users in the system (scaling in)
- Consumption Based Model - Cloud users oay for what they need, by the duration they need
- Economies of Scale - The cloud is a shared pool of machines and services. As the number of customers grow, cloud providers can lower their cost or increast the quality of their servers
- CapEx - The cost of spending physical infrastructure upfront. You also have to deduct the expense from your tax bill. The value of investment for physical infrastructure reduces over time
- OpEx - The cost of spending on servers as needed from the cloud. You will get billed immediately, and there is no upfront cost. With cloud services, you pay as you go.
-IaaS - Infrastructure as a Service: Azure takes care of the physcial infrastrucutre like data center seurity, hardware repair, etc. With IaaS, users take care of their servers and maintenance, such as the operating system, the configuration, backups, and more 
- PaaS - Platform as a Service: Azure takes care of the servers, and cloud users only need to bring in application code or data
- SaaS - Software as a Service: Azure takes care of the server and code. Cloud users only need to configure the software to suit their needs
- Public Cloud - Companies use this model when they decide they want to use all their servers from the cloud providers data center
- Private Cloud - Companies use this model when they decide they want to use all their servers in their own data center to replicate cloud servers
- Hybrid Cloud - Companies use this model when they want to have some servers in their own data center, and some servers on the public cloud
- Regions - A region is a collection of datacenters. Theres an average of 16 datacenters per region. When configuring your cloud system, you can choose the region closest to your users
- Region Pairs - Each Azure region is paired with another region. Azure prefers at least 300 miles of seperation. Services provide automatic replication to the paired region. System updates are rolled out to region pairs sequentially, not at the same time 
- Avaliability Zones
- Resource Groups - A collection of resources. Every resource must exist in one (and only one!) resource group. The resources can be from multiple region. Deleting a resource group deletes all resources in that group. Use Locks to prevent this
- Subscriptions
- Management Groups - Helps you manage access, policy, compliance and more for multiple subscriptions. Alll subscriptions in a Management Group inherit conditions applied to the MG, and 10,000 MG can be supported in a single directory. Hierarchy is: Management group > Subscriptions > Resource Groups > Resources
- Azure Resource Manager
- Azure Resources
- Virtual Machine - Solution to a lack of physical servers. You can create a virtual machine in the cloud and you customize all the software running on the VM. This is a good choice when you need to take control of the operating system, have the ability to run custom software, and use custom hosting configurations 
- Windows Virtual Desktop - Desktop virtualization enviroment where you can virtualize 365 apps, manage windows 7, 10 and server in one place
- Virtual Networks - Enables Azure resources like VMs, web apps, etc to communicate with each other, with users on the internet, and with on premis computers
- VPN Gateway - Lets you send encrypted traffic between an Azure virtual netrowkr and an on-premis location over the public internet. Each virtual network can only have ONE VPN Gateway
- Virtual Netowrk Peering
- ExpressRoute
- Internet of Things (IoT) Hub
- Internet of Things (IoT) Central
- Azure Sphere 
- Azure Machine Learning - A data science technique that uses existing data to train a model, test it, and then apply the model to new data to predict future behaviors and outcomes 
- Azure Cognitive Services - Provides built in machine learning models that enables apps to see, hear, speak, underand and reason. It can understand images, videos, audio, and translate text
- Azure Bot Service -Lets you crete virtual agents that understands and replies to questions like a human. Used often when building a virtual agent that interfaces with humans via natural language 
- Azure Portal - Azures site to access every feature of Azure
- Azure PowerShell - Developers use this to execute commands called cmdlets where the command calls the Rest API to perform a task in Azure
- Azure CLI - linux bash. Run commands alone or grouped in a script
- Azure Mobile App - iOS and Android access to your resources. You can monitor health and status of resources, check for alerts, restart web app or VM, run CLI/Powershell commands, and more
- Azure Advisor
- Azure Resource Manager (ARM) Templates - Instead of using CLI or powershell to set up and tear down resources, use ARM templates to define what you want in JSON. The benefit is the entire template is verified before any code is executed to ensure code will work
- Azure Monitor
- Azure Service Health
- Serverless Computing 
- Azure Machine Learning
- Azure Cosmos DB
- Azure Active Directory
- Multi Factor Authetication
- Single Sign on
- Authetication vs Authorization
- RBAC - Role Bases Access Control: It is applied to a scope, which is a resource or set of resources that access appplies to. You can apply RBAC to a person or a group
- Tags -Organize resources by adding labels
- Azure Policy - Lets you create, assign and manage policies that control or audit your resources
- Azure Blueprints - Instead of creating policies for each subscription, blueprints lets you create a set. You can create and deploy various templates like role assignments, policy assignments and resouce mgr templates
- Conditional Access - A tool Azure Active Directory uses to allow or deny access to the resources based on identifyig signals. The signals include who the user is, where they are, and what device is used. This is more granular than MFA. 
- Defense in Depth - Protect info and prevent it from being stolen by those who are not authorized to access it
- Trust Center - showcases Microsoft principles for maintaining data integrity in the cloud and how Microsoft implements security, privacy, compliance and transparency
- Compliance - Ensuring a company follows the laws that governing bodies enforce. There are 4 global offereings for compliance: Global, US Gov, Industry, Regional
- Privacy Statement - Explains what Microsoft colects, what they use it for and the purpose
- Cloud Adpotion Framework - Implement the cloud with these steps: Define your strategy, Make a Plan, Ready your organization, Adopt the Cloud, Govern and Manage your cloud enviroment 
- TCO Calculator - Total Cost of Ownership. This calculator can be used to see how much you will need to spend if you are building the same infrastructure in your own data center
- Pricing Calculator -This website can be used by anyone that would like to plan their costs before moving to the Azure Cloud
- Azure Cost Mgmt -Free service for customers that shpws how much has been spent in the current billing period, and how to optimize the cost 
- Azure Advisor - Free service for customers that provides recommendations in high avalaibility, security, performance, and cost based on the Azure products you are using
- Secure Score - Measurement of an organizations security posture. Your score is based on the percentage of security controls you satisfy
- Azure Synapse Analytics - AKA SQL Data Warehouse. Its an analytic service that brings togher enterprise data warehousing and big data analytics
- Azure HD Insights - Open source cloud service that makes it easy to process massive amounts of data. You can use open source frameworks like Handoop, Spark, LLAP, etc
- Azure Databricks - Data Science/Eng platform for Big Data and Machine Learning. It is used to process and transform massive amounts of data and exploring data through maching learning modules 
- Azure DevOps - Its a suite of products that contains Azure Repos, Azure Pipelines, Azure Boards, Azure artifacts, Azure Test Plans (CI/CD tool). Using Azure DevOps gives users the ability to have granular permissions 
- Azure DevTest Labs - Automatically turn on/off virtual machines 
- Azure Resource Manager Templates (ARM) - Instead of using CLI or Powershell to setup and tear down resources, use ARM templates to define what you want in JSON. The benefit is you can verify your template before the code is executed so you can verify your code
- Azure Powershell + CLI - Powershell lets you execute commands called cmdlets where the command calls the Rest API to perform a task in Azure. CLI is Linux based and uses Bash. The biggest difference between the two is the syntax - use what you are comftorable with 
- Azure Logic Apps - A low code/no code serverless development platform service. It helps you automate and orchestrate tasks, business processes, workflows,  etc for apps
- Azure Functions - A serverless computing service where almost any programming language can be used to create custom algorithms, perform specalized data parsing/data lookups, and more
- Network Security Groups - NSGs are like an internal firewall. You can filter network traffic to and from Azure Resources within an Azure Vnet
- Azure Security Center -  A service to provide visibility of your security posture. You can monitor security settings, recommendations, detect attacks, detailed anlysis, and more 
- Azure Dedicated Host - Some customers require them to be the only customer using the physical machine that hosts their Azure Virtual Machines
- Azure Sentinel
- Key Vault
- Security Posture
- DDoS Protection
- Azure Firewall
- Azure Service Health
- Azure Monitor 

































