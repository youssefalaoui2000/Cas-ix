+++
title = "Transit ip and peering"
weight = 1
banner = "img/banners/peeringbanner.jpg"
summary = "Telecom operators have two interconnection services that allow their networks to connect directly and indirectly to the Internet: peering and transit. If these two terms answer the same need, to facilitate the Internet traffic, they remain different...."
+++

Telecom operators have two interconnection services that allow their networks to connect directly and indirectly to the Internet: peering and transit. If these two terms answer the same need, to facilitate the Internet traffic, they remain different in their aspect.

### Internet traffic

**The Internet is a set of interconnected networks. These networks use common protocols to exchange information.** These large networks include Internet servers that act as central repositories of information and other servers that are responsible for routing this information. The routers will ensure that the devices installed on these networks can communicate with each other.

When a network router receives a request, it queries its routing table to determine the shortest path to route the information. It will first look on its own network to determine if the destination is there. If it is not, a "gateway" router will take care of getting the request out of the network.

When leaving its own network, the request will have to find its way through the Internet. The Internet is made up of a hierarchical stack of networks.

* **The higher level networks, the Internet backbone: The Internet backbone is the result of the interconnection of high-speed fiber optic networks of telecom operators.** By joining forces, these network operators will set up a global network including all the routing tables of the global Internet (AT&T, Orange, Cogent ...)

* **Then there are smaller networks. At the bottom of these layers are operators, often ISPs (Internet service provider ), to which consumers and companies subscribe, and which cannot access the backbone directly.** In theory, their traffic would be limited to their own network. To solve this problem, intermediate networks will take care of establishing a link between the higher level networks and the lower ones. 

These interconnections allow networks, limited in size, to carry information around the world. However, these interconnections will take place in several ways.

### What is peering?
**These networks of different sizes will therefore link to each other. They can establish direct links between them. Each one gives access to the other to the routing tables of its network in order to facilitate the routing of information. However, this agreement will only work for networks and operators of similar size.** Low-level networks cannot set up such an exchange with higher-level players. National operators can also deploy large national or even international networks by multiplying peering agreements. However, without access to the backbone, they cannot guarantee global Internet access to their customers.    

### What is ip transit?
**Peering is therefore sometimes not enough to route a packet from point A to point B. Indeed, there is an asymmetry between the networks of the various telecom players. A financial agreement is then established so that an operator can access a larger network. The latter is called a forwarder.**

So, when a company wants to send or receive information on the Internet, it must "transit" through one or more third-party networks in order to reach its final destination. Very often, the company will deal with an ISP located at the bottom of the network ladder. And this ISP will establish links with other operators to offer a complete Internet access service.  

Under these conditions, the quality of service offered by an operator will be correlated to the number of interconnections made with other networks.



<img src="/img/banners/transit-ip-peering.jpg" width="60%" height="60%">


<strong><u>Network interconnection by Peering and Transit</u></strong>

### IP Transit Provider Levels

IP transit providers are divided into three tiers. These follow the levels of the different backbones that make up the Internet:

1. **Level 1 operators (tier 1)**    
**Tier 1 providers have a broad global reach. These providers connect to each other to form the "backbone" of the Internet.** Tier 1 providers exchange freely with each other, but will charge actors below them for access to their network. The combination of these Tier 1 providers forms a set of extended routing tables capable of routing requests anywhere on the Internet.

2. **Level 2 operators (tier 2)**    
**Tier 2 providers have large networks with multiple physical locations and data centers.** These players will generally exchange freely with each other in order to expand their content delivery capacity; and in the process avoid the usage costs associated with access to a level 1 network.

3. **Level 3 operators (tier 3)**    
Tier 3 suppliers are typically local suppliers with smaller customer lists. **They will typically purchase a smaller portion of IP transit through a Tier 2 provider to avoid the higher costs of going directly to a Tier 1 ISP.**

### What is the difference between Transit and Peering
No network is big enough to connect every person and every computer. Transit and Peering take care of this interconnection. Transit and Peering will therefore determine the way traffic flows on the Internet.

**The monetary aspect is the major difference between these two methods.** Indeed, peering is used by networks of the same value, even if sometimes the differences can be settled by a financial agreement. Transit, on the other hand, necessarily involves a transaction, since it is a traffic agreement between two networks with different intrinsic values.

