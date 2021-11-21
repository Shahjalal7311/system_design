## What is cloud?
"The cloud" means a servers which is accessed over the Internet, and the software and databases or ther process that run on those servers. Cloud servers are located in data centers all over the world.

cloud details: [cloud](https://www.cloudflare.com/en-gb/learning/cloud/what-is-the-cloud/)
![ cloud ](./docs/images/cloud.png)

## Openstack
Openstack [Openstack](https://docs.openstack.org/install-guide/get-started-logical-architecture.html)

# SNAT(Source Network Address Translation)
Secure or Source network address translation is network address translation technique that enable private network security or source by providing a public ip (Internet protocol) address to remote or host users or system.It allows multiple computers that connected within network with single private local area network to using a singler ip address to acess the internet.In general SNAT work network environment.

![ SNAT ](./docs/images/snat.png)

## What is virtualization?
Virtualization is technique that created multiple physical layer over single physical layer that can be used by multiple physical machine or sharing the resource.

Virtualization Details [virtualization](https://www.ibm.com/cloud/learn/virtualization-a-complete-guide)

![ virtualization ](./docs/images/virtualization.png)

## How virtualization work?

Physical layer() have some major component.Those ase  
        - application : when run application in usernamespace it's call different OS API.The OS api called System api.Application run always run usernamespace.   
        - os: make connection between application and karnel.  
        - karnel: manage the resource.  
how execution processor:   
    - fetch : is the operation which receives instructions from program memory from a systems RAM.   
    - Decode: the instruction is converted to understand which other parts of the CPU are needed to continue the operation. This is performed by the instruction decoder  
    - Execute: perfomr the operation and keep that Each part of the CPU that is needed is activated to carry out the instructions.  

Work flow: application->os->karnel  

![ virtualization works fllow ](./docs/images/vm-works.png)




