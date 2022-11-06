#        LINUX

##  ANALYSING AND MANAGING NETWORKS

### ANALYZING NETWORKS WITH ``ifconfig``

``ifconfig`` is used for interacting with active network interfaces. It helps manipulate local area network (LAN)

#### Checking Wireless Network Devices with ``ifconfig``
This command is used to gather crucial information if you have a wireless adapter e.g. its IP address.

#### Changing Your Nework Information
Useful skill to change IP address and other network information as it will help one access other networks while appearing as a trusted source. Simple tasks by using ``ifconfig`` *command*
1. *Changing Your IP Address*
2. *Changing Your Network Network Mask and Broadcast*
3. *Assigning New IP address from DHCP server*
4. *Spoofing Address*

#### Manipulating the Domain Name System
Domain Name System (DNS) is designated to translate domain names to IP address.

#####  Examining DN with ``dig``
``dig`` *command* is used to to gather DNS information about a target domain like ``ns`` (for *nameserver*) and and ``mx`` (short for *mail exchange server*) or any potential sub domains and IP addresses.
 
#####  Changing Your DNS server
- To use another DNS server you can edit a plain text file named */etc/resolv.conf* in the text editor and replacethe existing local DNS server to another DNS server thensave
- You can achieve the same in the command line by entering ``echo "nameserver 8.8.8.8"> /etc/resolv.conf`` if for example you want to change the DNS server to Google's.

#####  Mapping Your Own IP Addresses
This can be used to determine which IP address your browser goes to when you enter e.g *www..google.com* by using *hosts* file located at */etc/hosts* instead of using the DNS server decide.
