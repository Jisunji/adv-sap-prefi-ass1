## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
The service-oriented architecture (SOA) is a development approach that reuses or combines different components of a system, called services services, for complicated 
activities to design business applications.

2. List and discuss the characteristics of SOA.
a) Standardized Servie Contracts means that the services must comply with a set of guidlines.
b) Loose coupling simply means that each service should have as little dependency with one another as possible.\
c) Abstraction means that the users should only know the functions of the service, while hiding the implementation and the "how it works" of the service itself.
d) Reusability simply means that the service can be used and modified for other functions when necessary.
e) Autonomy means that the service is able to execute its function even without relying on other services. 
f) Statelessness means that the service processes requests using only the information given in that current request, and not any previous ones.
g) Discoverability is self explanatory. The service should be able to be discovered through a registry.
h) Composability simply means that the service can be used in conjunction with other services to create business applications and execute complex procces.
i) Interoperability means that the service can communicatie with other services using standardized protocols.

3. Define Microservices.
Microservices are similar to SOA in a way that it aims to make software and systems that are reusable, modular, and flexible, albeit in a smaller scale. It is a development
approach that natively utilizes cloud computing services.

4. List and discuss the benefits of using Microservices.
a) Independently Deployable - microservices ensures that services can be deployed quickly as it is divided into small, digestible groups essentially. It is also independent
of other services which means teams can work on one specific service without it affecting the entire system.
b) Righ tool for the job - this basically means that software/systems developed with this approach can be optimized for specific functions.
c) Precise Scaling - due to services being independent of one another, scaling one service does not require scaling the entire project. This saves resources and time as only
those that need to be scaled are scaled. 

5. List and discuss the similarities and differences of SOA and Microservices.
Similarities

Both architectural approaches are used to create software applications.
Both place a strong emphasis on using services as the essential components of applications.
Both encourage strong cohesiveness and loose coupling between services.
For communication, both rely on common protocols and data formats.
Both aims to enhance software programs' adaptability, scalability, and maintainability.

Differences

Microservices are more narrowly focused on a single capability, whereas SOA services, despite being larger and coarser grained, can manage multiple business functions. 
With fewer dependencies on other services, microservices exhibit greater coherence and loose coupling. Unlike SOA services, which communicate via an Enterprise Service Bus 
(ESB), they engage directly through APIs.
SOA services are usually deployed as a single monolithic application, while microservices are independently deployed as separate services.
SOA services are usually managed centrally, while  microservices are managed independently by their respective teams.


