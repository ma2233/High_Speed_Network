# High_Speed_Network
Network Topology created from scratch in Cisco Packet Tracer using Industry Standards.

The following network has identical configurations in NY, LA, & Tokyo. 
Each city is made of an interal network who hosts three vlans {Employees, Guests, & a Native} (Native vlan for network devices).
Each city is also made of two datacenter clients which are on external networks who connect to ours via BGP(external routing protocal).
The rest of the topology learns new routes via EIGRP (internal routing protocal)
Everything is sprinkled with other sophiscated networking options such as DHCP, ACLs, Firewalls, & an ISP.
This goal of this network is to have the traffic fast, redundant, and restricted to only autherized access.

Tip: To open file you must download Packet Tracer
Tip: When opened, to access ISP you must turn on the interfaces connecting to all Firewalls (inbound and outbound)
