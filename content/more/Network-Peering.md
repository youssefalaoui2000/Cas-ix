+++
title = "Network Peering"
weight = 6
description = "Peering is a process by which two Internet networks connect and exchange traffic. It allows them to directly hand off traffic between each other's customers without having to pay a third party to carry that traffic across the Internet for them."
banner = "img/banners/ixp2.png"
+++

Peering is a process by which two Internet networks connect and exchange traffic. It allows them
to directly hand off traffic between each other's customers without having to pay a third party to
carry that traffic across the Internet for them.

![network1](/more/images/network1.png)


From the diagram, we can observe how the EastNet network peers with MidNet. Consequently,
the routing table of EastNet will have route information related to MidNet. Similarly, for WestNet,
it will peer with MidNet, and its routing table will contain the relevant route information for
MidNet. On the other hand, MidNet's routing table will have route information for both WestNet
and EastNet.  

**There are two main types of Peering:**  

* Public Peering is usually carried out through an Internet Exchange Point (IXP), where one network can peer with multiple other networks through a single connection.
* Private Peering is when two or more networks agree to exchange their traffic at a private facility.  

Without a local IXP, Internet service providers must use expensive international Internet
connectivity to exchange and access global traffic, content hosted abroad, and local traffic.  

### Transit and Peering Relationship

The diagram illustrates a simplified peering and transit business relationship. The relationships are
important in developing interconnection strategies of where to buy, sell and peer. But, first, let us
attempt to understand the transactions.  

1. ISP A and B are both operating in a certain market;

2. Both ISP A and B are buying T (Transit) capacity, for which they are paying $ 
    * acquiring and using Transit capacity is a commercial transaction
    * you pay for a certain capacity based on your needs.

3. Without Peering, ISP A and B would exchange local traffic via Transit yellow, Pink, and
Red. Furthermore, they would be paying hefty costs to do so (i.e., exchanging local traffic).

4. Instead, ISP A and B decide to establish a local Peering relationship. They would be
exchanging the local traffic at no cost (apart from establishing the link) through that link.
Transit would be freed up from some capacity (now passing through the Peering).

5. In some cases, Peering may mean "Paid Peering." It is a concept when ISP A and B are
not of the same "economic" size, and one of them is making the other pay in order to have
access to its network.

![network2](/more/images/network2.png)

**There are four types of "relationships" an ISP can have with another:**

* Transit (commercial agreement - "I can give you access to the Internet, at a fee")

* Peering - Open policy ("I am ready to do peering with anyone")

* Peering - Selective policy ("I am ready to do peering, but I will decide with whom I do
peering")

* Peering - Restrictive policy ("I normally do not do Peering")