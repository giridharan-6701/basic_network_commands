# basic_network_commands

1 - IPCONFIG

IPCONFIG command is used to display the IPv4, IPv6, subnet mask, default Gateway of all the network adapters in the system.

![Screenshot 2023-07-20 162338](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/d09dcea5-5827-4b2d-9503-16375a19fa66)

IPCONFIG Command be used with the following Parameters:-

 I - IPCONFIG /all -- This command also works similar like IPCONFIG, Additioanlly it provide extra details like DNS Server Address, DHCP Server Address, IP's Lease Period.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/d168f0aa-5122-489e-84a4-cd7bdf86c89c)

II - IPCONFIG /release -- This command is used to release the current IP Information for a specified network Adapter. This command is used before renewing IP Address from DHCP Server
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/9fdf7e53-9dec-4b73-b153-b2a632e078c4)

III - IPCONFIG /renew -- This command is used to renew the IP Information that is released using the above II command.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/d9dd8d69-d336-401c-88c1-2f948242877d)

IV - IPCONFIG /displaydns -- This command is used to display the DNS Information of the wessite that is stored in the DNS Resolver Cache.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/13de9fed-4be4-4de1-9e6c-cc7dc342acba)

V - IPCONFIG /flushdns -- This command is used to clear or fulsh the DNS Information of the Website that is Stored in the DNS Resolver Cache.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/62c46ba9-1116-42f6-ac51-f9df28e60127)

VI - IPCONFIG /registerdns -- This command manually registers DNS Record for the specific Network Adapter.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/1209bd3f-5989-4605-b5bd-45e1c8755f98)

2 - PING 
PING Command is used to test the reachability of the Host in the IP Network by sending the ICMP Packets.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/27b7c8d8-74cc-4712-9462-da3c0de26f63)

PING Command can be used with the following parameters:-
I - ping -n 5 www.twitter.com  This command is used to test the reachability of the twitter website and adding a flag of -n 5 specifies the count of ICMP Packet need to be sent.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/c3871b00-01e7-4e23-911c-c0b7ec77dfd9)

II - ping -w 3000 www.twitter.com This command also serves the same purpose of PING I Command, additionally we are adding a flag -w 3000 which specifies the timeout of the packet to drop if it does'nt received reply from the host after the specified time. The Default Value is 1000 millisecond (ie) 1 second
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/3d8c2b5b-1a44-444a-9c5d-e3418d7e051a)

III - ping -l 64 www.twitter.com This command also serves same purpose as PING I Command, additionally we are adding a flag -l 64 which specifies the size of the ICMP Packets in Bytes. The Default Packet size is 32 Bytes.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/e139146a-1b33-4c35-8d2f-d9a5f178221c)

IV - ping -f www.twitter.com This Command also serves the same purpose as PING I Command, additionally we are adding a flag -f which means DO NOT FRAGMENT, Usually in ping command fragmentation is enabled which means breaking the packets into smaller fragments to prevent data loss in transmit. The Purpose of providing DO NOT FRAGMENT is to check the Maximum Packet size required for transmission.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/c947911f-dea1-45d7-9179-a2c45b5a1dfa)

3 - TRACERT 
Tracert Command is used to display the routing path that the packet transmitted from source to destination, How much devices it traversed during transmission, Number of Hops it has taken all the details can be shown.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/b93129b9-1d02-44f1-a195-27ddc7844b83)



