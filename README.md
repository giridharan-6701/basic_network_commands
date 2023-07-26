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
