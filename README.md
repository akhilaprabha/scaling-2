# scaling-2
## LOAD BALAncing
The efficient way to distribute the incoming network  traffic across the cluster of servers is known as load balancing
Load Balancing is important as it improve the reponsiveness of an application along withthe increase in availbility.
# Types of load Balancers
Baed on Function:
  1.Network Load Balancer
  2.Application Load Balancer
  3.Global Load Balancer
based on Configrations:
  1.Hardware Load Balancers
  2.Software Load balancers
  3.Virtual Load Balancer
  # Network Load Balancer:
This Load Balancer work on the network variables like ipaddress and destinations ports.
This is alsocalled layers 4 load Balancer as theses are resonsbile for distributions oftraffic at transparort level.
  # Application Load Balancer:
  This is also called L7 load balancer as it works on application layer. Awide range of data is evaluated by L7 load balancers which includes HTTP headers,SSL sessionsetc. The server load is distributed by these load balancer whichis based on severalvariables.
  # Global Load Balancer:
 Also known as Multi-site Load balancer, this extends the capabilities of application load balancer and network load balancer both across with enhanced global load distribution.
  case  of server failureor any diaaster muti-site load balancerhelps in quick and seamless recovery
  # Software Load Balancer:
  These are the pieece of software that needsto be deployed on any system. These workssame as that of hardware load balancers, these are cost -effective.
  # Hardware Load Balancer:
  This load Balancer is a Physical equipment to diversify the trafficto various servers.
  These load balancer have limited flexibility and are high in price , however they can mange and distribute huge volume of traffic
  # Virtual Load Balancer:
  Virtual Load Balancerscopy the software driven infra through virtualisatio,The software of physical load balanceing appliance on virtualmachine.
  #  Benfit of Load balancer:
  1. Enhance performance and speed
  2. Prevents Single point of Failure
  3. Reliability
# Load Balancing  Algorithms:
1. Round Roobin Algorithm:
in Round Robin algorithm, the request is forwarded to each server lum by turn.
2. Weighted Round Robin  Algrrithm
Weighted Round Robin algorithm can be considered as the enhancement of Roun Robin Alogrithm, eachserver in the pool is assigned with aweight generally a number , like most power ful serveris assigned with 10thenthe server withhalf of its computingpower is assigned as 5 and soon using this algrithm the server withhigher weight gets more number of requests but the allotment is still doneon cyclic basis.
3.Least connections Algorithm
in this algoithm , traffic is directed to the server having the least number of active sessions. this helps maintain the  optimised performance. especially atpeak hours by maintaing a uniform load at all the servers
# Scalability :
Scalability often referred as System's ability to grow. however in System Desingn it does not always adhere to the definition,System can scala up and scale out accordinly.
Hence, Scalability is your system's ability to adapt to changes as per the demand.
Highly scalable system prevents the system from downtime, and it ensure the quailty of your application and serveices
# Horizontal Scaling :
Horizontal scaling is also known as scaling out.
it means adding new servers or machines/nodes to your system, so that it can cope up with new demands.
# vertical Scaling:
vertical Scaling is  also known as Scaling up.
it means adding more resources to the existing server or node, so that it can cope up with new demands.
# Advantages of Horizontal Scaling:
1.Easier Scaling
2. Reduced Downtime
3. Enhanced performance
4. Fault Tolerant and Resilience
# Disadvantages od Horizontal Scaling:
1. Difficult Maintenance
2. High Cost
# Advantages of Vertical Scaling:
1. Easier Maintenance
2. Cost-effective
3. Easy Process and Communication
# Disadvantages of Vertical Scaling
1.Single Point of Failure
2. Downtime Possibility
3. Limitations in Upgradation
  
