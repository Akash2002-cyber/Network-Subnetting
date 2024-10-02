

The companies are named as Company A, Company B and Company C. 

-Company A** has **5 Rooms** with **1 PC** in each room.
-Company B** has **3 Rooms** with **3 PCs** in each room.
-Company Z** has **2 Rooms** with **4 PCs** in each room.

The IP regulating company has assigned the following IP network addresses to each of the Company:

-Company A: 144.186.96.0/19**
-Company B: 50.152.0.0/15**
-Company Z: 210.98.169.64/26**

As part of the agreement, all three companies have asked you to bear the expense of all the switches and routers used to interconnect all the computers in a merged network for three companies and further instructed you that **all the PCs in a single room must be on the same sub network and all the rooms of a single Company must be on a different sub-network which will be assigned after sub-netting the assigned *network address* only for the relevant Company** (no outside network or the network of other Company will be accepted) e.g., each room for Company A will be assigned a different sub-network after sub-netting the address of 144.186.96.0/19 only and not and other network address. The companies have further informed you that companies plan to extend the number of their PCs in each room in the future.

You, begin cleverly economical, decide to install old switches (**Generic Switches** in Cisco Packet Tracer) with only **three Ethernet ports working out of four** and routers (**Generic Routers** in Cisco Packet Tracer) to configure the network for three companies in such a way that you use as much less routers and switches as possible. 

you have also Bought the following IP network address for the serial communication between different routers which will be connecting different Inter-Company and Intra-Company subnets. you plan to form the subnets of the following address in order to cater the serial communication between all the routers: **Routers Serial Communication: 199.210.121.160/28**

## Constraints

you, being very cautious, decide to **simulate the topology on Cisco Packet Tracer** in order to optimally design the network considering the number of devices (switches, routers etc.) used to maximized the profit margins of Your Company. However, You must simulate the topology strictly following rules and regulations described below:

1- Use Straight Through wires, Cross Over cables or Serial DCE wires where necessary and applicable.

2- Use Generic Router and Generic PCs for Your design

3- Use Generic Switches such that You attach **only 3 of the 4** available **Ethernet Interfaces** for a single switch, however, You can attach as many switches considering optimal design.

4- You have to assign IPs to the PCs using **Static IP allocation**.

5- Although You have to use GUI of the router to configure its interfaces but You must use CLI of the router to configure the **RIPv2 Protocol** for **Classless Subnet Addressing**.

## How to Run
Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) and then simply open the [main file.pkt](../master/main/main%20file.pkt). The whole network is in working condition. You can check it by sending a packet from one system to another or through using the PING command in the Cisco Packet Tracer.

This solution works for version 6.2 or above of Cisco Packet Tracer.

