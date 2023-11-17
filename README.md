## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).

	-It is an approach to building sftware that uses reusable components called services to perform specific tasks like checking customer's credit, etc... These services consist of both code and data integrations necessary for executing specific business functions. SOA aims to create a flexble and interoperable system by breaking down applications into smaller, reusable pieces that can be easily combinied and adapted for various applications and purposes.

2. List and discuss the characteristics of SOA.

	1. Standardized Service Contracts - Services define their purpose and capabilities thru formal, sandardize contracts. This ensures clarity in communication and interaction between services.
	2.Loose Coupling - Services minimizes dependencies on each other and promotes flexibility. There's a constant effort to reduce interdependence between service contracts, implmentations and consumers.
	3.Abstraction - Services that hides the internal logic from the outside world. This helps prevent unnecessary information proliferation and maintains loosely-coupled relationships.
	4.Service Reusability - Logic is organized into sercvices with the goal of maximizing reuse. This promotes efficiecy by adding redundant development efforts.
	5. Autonomy - Services have control over the logic they encapsulate. Autonomy ensures that services can carry out their functions independently of external influences.
	6.Statelessness - Services that are designed to be stateless, meaning they don't retain information about previous interactions and this enhances scalability, supports agnostic logic and improves service reuse.
	7. Discoverability - Services can be discovered, usually thru a service registry. This makes it easier for other services or consumers to find and interact with available services.
	8.Composability - This services, break down complex problems into smaller, resuable components. 
This encourages efficiency when it comes to assembly of services to address vatious applications and business needs.
	9.Interoperability - This servic use standards that allows a mutiple subscribers to access and use the service. This ensures compatibility and seamless integration across different platforms.

3. Define Microservices.

	Microservices are a modern way of building software where we can create an application using small, independent pieces called services. These services work together and can be updated, scaled and managed independently. They communicate with each other through well-defined methods like REST APIs or messaging. Nicroservices make it easier to update code, use different technologies wothout affecting the entire application. When combined, they're like building blocks that can create a flexible, agile and cost-effective system especially useful for handling various workloads efficiently.

4. List and discuss the benefits of using Microservices.

	Microservices brings flexibility, speed, comprehensive, tool customization, efficient scaling and cloud benefits to our software development. here are the list of benefits of using Microservices:

	1.Independently Deployable - Microservices enable the independent deploymenr of small, individual services, addressing the challenge of deployments for minor updates.	
	2. Right Tools for the Tasks - Microservices lets you use different technologies for different tasks, this makes it easier and cheaper to adapt to new technologies.
	3.Efficient Scaling - It lets you scale only the parts of your application that needs it. This saves resources compared to scaling the whole application.
	4.Cloud Benefits - Microservices works well with cloud services, offering flexibility and cost savings. We pay for what we use and each part can use the best tools for the job.
	
5. List and discuss the similarities and differences of SOA and Microservices.

	-SOA is an enterprise-focused with a common communication mechanism, while Microservices are application-focused emphasizing independent communication and specialization. These are some similarities and differences of SOA and Microservices:

Similarities:
	1.Loose Coupling - SOA and Microservices aim for loose coupling, meaning that individual components are independent and can evolve without affecting others.
	2. Reusability - Both architectures promote the reuse of components. SOA focuses on reusing serivces across the enterprise while Microservices encourage reuse within specific application.
	3.Interoperability - Both architectures emphasize the use of tandards for communication allowing services to work together.
	4.Independently Scalable - Both SOA and Microservices enable independent scaling of service, allowing resources to be allocated where needed.

Differences:
	1.Scope - SOA is designed for an enterprise-wide approach ensuring standardization across all services, while Microservices are application-specific, focusing on breaking down application into smaller pieces to be independently managed.
	2.Communication - SOA often relies on a common communication mechanism known as Enterprise Service Bus (ESB) while Microservices use independent communication protocols for each service.
	3.Service Granularity - SOA can vary from small, specialized services to enterprise-wide services. Microservices are highly specialized, design to perform specific functions very well.
	4.Speed and Duplication - SOA, with its emphasis on sharing a common architcture, can operate more slowly while Microservices priortize speed by minimizing sharing and favoring duplication where needed.
