## What is the cloud?
	• The cloud is an internet base solution. Its all the things you can access remotely in the internet 
	• When something is in the cloud, its stored in internet servers, instead of sorting it in a local hard drive
	• It still operates on servers and its someone else's server connected to the internet. However, we don't know details about the sever
## What is cloud computing?
	• Cloud computing provides access to various computing resources over the internet. You can use a computer to connect to your cloud service provider through the internet. When you're connected, you have access to computing resources like virtual machines, storage, etc
	• Cloud service providers have massive data centers that contain 100s of servers, storage system and components. They're located in secure locations and the users connect to these data center sot collect data or use it when necessary. You only pay for services you use, no charges upfront (This is called a consumption based model)
	• Cloud computing can be use for machine learning, data analysis, storage backup, streaming media content, testing applications, automating software delivery, hosting blogs etc. For example, all Netflix shows are stored in the cloud.
	• Let's say you want to launch an application. To do so, you need various components like severs, storage devices, developers, dedicated networks, application security, etc. Buying each of these can be expensive. Cloud computing can offer safe storage, scalability and more. 
## Benefits of Cloud Computing
	• Advantages to Migrating to cloud computing:
		○ High availability - Your cloud based apps can provide a continuous user experience with no apparent downtime, even when things go wrong
		○ Scalability - apps in the cloud can scale vertically and horizontally
			§ Scale vertically means you can increase the compute capacity by adding RAM or CPUs into a virtual machine
			§ Scaling horizontally means you can increase compute capacity by adding instances of resources like adding virtual machines to the configuration
			§ Elasticity - You an configure could based apps and autoscale 
			§ Agility - Configure and deploy cloud based resources quickly as requirements change
			§ Geo-Distribution - You can deploy apps and data to regional centers globally
			§ Disaster recovery - Data is always safe in the event of a disaster 
	• Think of it from 2 perspectives. What's reduced, and what's increased
	• We will start with 3 things that are reduced when we do cloud computing
		○ It doesn’t cost to deploy it because instead of buying hardware upfront, you just pay for the cloud
		○ First is reduced hardware cost. For example, you create a web application which requires a database server ,application server and web server. Where is the storage gonna go? You can purchase hardware, or do it all in AWS, Azure, Google
		○ Second thing reduced is operational costs. You need someone to operate and manage hardware servers. Instead you can operate in AWS/Other provider. Since its in the cloud, one person can manage more things, and people can have more time for other things
		○ Reduce deployment times. You have to buy physical hardware, you may not need 1/3 until 18 months from now, or in 10 days, then you have to configure it. Install the services, configure IP, etc. THEN you can build your web app after its taken 6 weeks to do that. But with AWS, till take you minutes to get a web, db server, application server nd you can start the project with no wait time
	• What's increased?
		○ Increased resiliency - reference to recover ability from a failure or problem
		○ Increased performance. We start with 2 servers in a cluster, but our audience grows and we need more servers by enabling auto scaling in AWS. You don’t have to buy and waste hardware in advanced
		○ Increased capacity - it an be  storage, ability to handle users that are connecting, memory, things like that
## Cloud Service Models
	• IaaS - Infrastructure as a Service: This model is closest to managing physical servers. A cloud provider will keep the hardware up-to-date
		○ Pros: No capex (no upfront costs)
		○ Agility - applications are quickly accessible
		○ Management - user manages and maintains services, cloud provider maintains cloud infrastructure
		○ CapEx model, or consumption based
		○ No deep tech skills required
		○ Cloud benefits and flexibility
	• PaaS - Platform as a Service - This model is a managed hosting environment. Managing virtual machines and network resources. The cloud provider (Azure, AWS) manages the virtual machines and networking resources, and the cloud tenant deploys their applications into the managed hosting enviroment
		○ Pros: No capex (no upfront costs)
		○ Agility - applications are quickly accessible
		○ Management - user manages and maintains services, cloud provider maintains cloud infrastructure
		○ CapEx model, or consumption based
		○ Cloud benefits and productivity - users can focus on application development only because the cloud provider handles platform mgmt
		○ Cons: platform limitations
		
	• SaaS - Software as a Service: This model allows cloud providers to manage all aspects of the application environment like virtual machines, networking resources, data storage, applications. The cloud tenant only needs to provide their data
		○ Pros: no capex, agility, pay as you go pricing module, skills, flexibility 
		○ Cons: software limitations. You don’t have direct control of features because youre using as-is software

## Public, private, and hybrid clouds
	• Public Cloud - Services are offered over the public internet and is avalaible to anyone who wants to buy it. Servers and storage are owned and operated by a third party
	• Private Cliud - Computing resources are used only from one business or organization. A private cloud can be physically located at your organizations data center or can be hosted by a third party
	• Hybrid Cloud - Combines public and private by allowing data and applications to be shared between them
	• As your resources move from on-premises to off-premises, your costs are reduced, and your administration requirements decrease.
