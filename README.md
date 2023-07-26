# basic_network_commands

1 - IPCONFIG

IPCONFIG command is used to display the IPv4, IPv6, subnet mask, default Gateway of all the network adapters in the system.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/d30fead8-85bc-4be7-941a-4b2cf59e4f94)

IPCONFIG Command be used with the following Parameters:-

 I - IPCONFIG /all -- This command also works similar like IPCONFIG, Additioanlly it provide extra details like DNS Server Address, DHCP Server Address, IP's Lease Period.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/63baab82-90c2-4aa8-ab45-b5a027a5261c)

II - IPCONFIG /release -- This command is used to release the current IP Information for a specified network Adapter. This command is used before renewing IP Address from DHCP Server
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/489f8496-874e-4119-a0c2-603772db1cf1)
 
III - IPCONFIG /renew -- This command is used to renew the IP Information that is released using the above II command.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/91d210a7-a52a-460b-92bd-d71fcf05110c)

IV - IPCONFIG /displaydns -- This command is used to display the DNS Information of the wessite that is stored in the DNS Resolver Cache.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/8452998a-938d-4805-b750-0653432a8ab5)

V - IPCONFIG /flushdns -- This command is used to clear or fulsh the DNS Information of the Website that is Stored in the DNS Resolver Cache.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/07a0e72a-e57c-40d4-a6da-86d4f4b38a8a)

VI - IPCONFIG /registerdns -- This command manually registers DNS Record for the specific Network Adapter.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/86c98d50-64fe-4d44-9ac3-06c427667ce7)


2 - PING 
PING Command is used to test the reachability of the Host in the IP Network by sending the ICMP Packets.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/294134ac-6357-452f-8c70-9c86f9d444f2)

PING Command can be used with the following parameters:-
I - ping -n 5 www.twitter.com  This command is used to test the reachability of the twitter website and adding a flag of -n 5 specifies the count of ICMP Packet need to be sent.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/c0ce54a3-12d8-48f7-bd21-d1de65dfafae)

II - ping -w 3000 www.twitter.com This command also serves the same purpose of PING I Command, additionally we are adding a flag -w 3000 which specifies the timeout of the packet to drop if it does'nt received reply from the host after the specified time. The Default Value is 1000 millisecond (ie) 1 second
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/42af5f22-854b-4965-97ff-3ffdb2b664ed)
 
III - ping -l 64 www.twitter.com This command also serves same purpose as PING I Command, additionally we are adding a flag -l 64 which specifies the size of the ICMP Packets in Bytes. The Default Packet size is 32 Bytes.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/8f9d61bf-9d06-4fea-88ec-c162f6b4fd80)

IV - ping -f www.twitter.com This Command also serves the same purpose as PING I Command, additionally we are adding a flag -f which means DO NOT FRAGMENT, Usually in ping command fragmentation is enabled which means breaking the packets into smaller fragments to prevent data loss in transmit. The Purpose of providing DO NOT FRAGMENT is to check the Maximum Packet size required for transmission.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/19f6e034-ea85-40d9-a68f-97cc2d5596b6)


3 - TRACERT 
Tracert Command is used to display the routing path that the packet transmitted from source to destination, How much devices it traversed during transmission, Number of Hops it has taken all the details can be shown.
![image](https://github.com/giridharan-6701/basic_network_commands/assets/94190302/cbc5a833-5a1d-44b9-aa91-0e698c7d3427)




