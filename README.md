# Computer Networks VLSM and Redistribution

## Concepts Covered
- Variable Length Subnetting
- CIDR addressing
- Natting
- Redistribution
- OSPF
- RIP
- EIGRP
- Access List
  
## Instructions 
- 1. Following are the steps you need to perform in the topology according to the given layout. 
Configure this scenario and find your given IP address in the file " IP address " attached with this. Find 
out the Network Addresses and start working with them. And use them as required.
- 2. Please find the number of required hosts per subnet in the given file. Each student is given a 
different number of required hosts per subnet. Networks are labeled alphabetically in the given file 
of IP ADDRESSES. The networks with Router 5, 6, 7, 8 and 9 are not labeled so you can choose any 
number of hosts for those subnet from the VLSM tree i.e., vacant subnet.
- 3. Use OSPF with area 1 in First Block for Routing , EIGRP 11 in Second Block , Rip in Block Third 
in first row. In second row apply RIP in first block and OSPF with area 2 in the last block as mentioned 
on the top of each block.
- 4. Use Redistribution on Router 1, Router 2, Router 3 and Router 4 for connecting EIGRP with 
OSPF, OSPF with RIP and EIGRP with RIP. Use Redistribution on Router 4 for connecting OSPF area 1 
with OSPF area 2.
- 5. All hosts in above row EIGRP, OSPF area 1 and RIP will get IP addresses from "DHCP 1" 
present in the second block.
- 6. All hosts in OSPF area 2 and RIP in second row will get hosts from “DHCP 1” present in OSPF area 2 block.
- 7. You have to use VLSM in each network of the topology.
- 8. You have to IMPLEMENT NAT in Router 10 with the Network G. Use the Private IP Address given to you in the attached file for Natting.
- 9. One of the PCs of Network L will not be allowed to access the Web server. One of the PCs of Network E will not be allowed to access the Data server in the 1st block. All hosts connected in network A will not be allowed to access TFTP Server.
- 10. The TFTP, Web and Data servers do not need to have running services. They will simply be treated as hosts. You just need to block the access of those servers from respective networks. (Access List)
