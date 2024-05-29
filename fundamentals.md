# CLOUD COMPUTING
Practice of using a network remote server hosted on the internet to store, manage and process data rather than a local server of pc

# CLOUD SERVICES
### Group on various type of services
###### 1.Compute
###### 2.Storage
###### 3.Networking
###### 4.Databases

# Benefit Of Cloud Computing.
#### 1. Cost effective -
 
You pay for what you consume
#### 2. Global - 

Launch workloads anywhere in the world.
#### 3. Secure - 

Provider takes care of physical security
#### 4. Scalable - 

increase or decrease resources based on demand
#### 5. Reliable - 

data backup, disaster recovery

# TYPES OF COMPUTING
#### 1.SAAS (Software as a service)- A product that is run and managed by the service provider eg Salesforce, gmail

#### 2.PAAS (Platform as a service)- Focus on the deployment and management of your app 
eg aws elestic beanstalk and heroku google app engine, azure web app

#### 3.IAAS (Infrastucture as a service)- Basic building block for cloud IT. Provide access to network computer and data. eg azure, aws, oracle cloud 

# Cloud deploymwnt model
#### 1.PUBLIC CLOUD/ gnerally is known as cloud native
Everything build on the cloud provider

#### 1.Private CLOUD generally is known as on-premise
Everything build on company's datacenter..the cloud could be OPENSTACK

#### 1.HYBRID CLOUD
Using both on-premise and a cloud service provider
#### 1.CROSS CLOUD
Using multiple provider

# Cloud Architect needs to understand
#### 1. Availability - Service should remain available
#### 1. Elasticity - Ability to shrink and grow to meet demand
#### 1. Disaster Recovery - recover from failure
#### 1. Fault Tolerance - ability to prevent failure
#### 1. Scalability -Ability to grow rapidly


### High Availability - 
Ability of service to remain Available by ensuring no point of failure and certain levels of performance. Solution is having multiple server in different data center.i.e multiple zone  ..
##### Load Balancer - 
Allow you to evenly distribute traffic to multiple to multiple servers in one or datacenter. If one datacenter becomes unavailable the LB will route traffic to only datacenters with server

### HIGH SCALABILITY  -
 Ability to increase your capacity based on the increasing demand of traffic, memory and computing power.
#### type of scaling
1. Vertical Scaling - Scaling up i.e upgrade to a bigger server

2. Horizontal scaling - scaling out i.e add more server of the same size

### HIGH ELASTICITY - 
 Ability to automatically increase your capacity based on the Current demand of traffic, memory and computing power.

this is by horizontal scaling.

    
 ####   Azure VM scale set - 
 automatically increase or decrease in response to demand or a defined schedule.
    
### Highly fault Tolerent
prevent chance of failure
##### fail over 
is when you have  a plan to shift traffic to a redundant system in acse the primary fails.

### Highly durability
Ability to recover from disaster..
question is do you have a  backup, how faster can you restore your backup

## BUSINESS CONTINUITY PLAN (BCP)
A BCP is a document that outline how a business will continue to operate during unplanned disruption in services.

### DEDICATED SERVER
A physical server wholly utilized by a single customer.

### VIRTUAL MACHINE
A virtual machine is a computer file, typically called an image, that behaves like an actual computer.
You can run virtual machines on one machine.
###### HYPERVISOR Software layer that lets you the VMS

### CONTAINERS
VMS RUNNING MULTIPLE CONTAINER.
Docker Deamon software layer thet let you run multiple container.

### FUNCTIONS
Known as serverless computer
You upload a piece of code choose the amount of memory and duration. responsible for code and data only. very cost effective, only pay for code it is running.
