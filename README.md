## Learning-CiscoPacketTracer
 Documentation of me learning basic networking commands, deploying small networks using HUB & Bridge, network deployment with switches and IP transmission using DHCP, VLAN & Trunks configuration, inter-VLAN routing, general-purpose network utilities, routing protocols, subnetting, access control lists, NAT and PAT, and Open Shortest Path First (OSPF) routing

## Lab 1
### Understanding of basic networking commands 
I learned basic networking commands for troubleshooting connectivity issues. The lab included tasks such as accessing network connection settings via `ncpa.cpl`, identifying connection types (Ethernet, Wi-Fi, Bluetooth), and understanding IPv4 and IPv6 statuses. I practiced using the command prompt for network configuration information and used the `ping` command to test connectivity and measure response times. I also used `tracert` to trace routes and identify potential network bottlenecks, understanding each step in data packet travel. The lab concluded with a troubleshooting scenario using traceroute to diagnose and resolve server connectivity issues.

## Lab 2
### Deploying Small Network in Packet tracer using HUB & Bridge
In this lab, I gained hands-on experience with setting up and troubleshooting a basic Local Area Network (LAN) using Packet Tracer. I started by familiarizing myself with Packet Tracer's interface, including its various menus and tools. Connecting devices like PCs and laptops to a hub in the simulation, exploring how to configure IP addresses and test network connections. I practiced assigning IP addresses to devices and ensuring they could communicate with each other. I also experimented with different connection types and observed how hubs and switches handle network traffic.
By creating and saving network topologies, I reinforced my understanding of network design and configuration. This lab helped me understand the practical aspects of networking, from setting up physical connections to using diagnostic tools to troubleshoot and ensure reliable communication between devices.

## Lab 3 
### Deploying Network in Packet tracer using Switches, Fixed and Dynamic IP transmission using DHCP Server
I gained hands-on experience in setting up network infrastructure using switches and configuring a DHCP server to automatically assign IP addresses. I learned how switches manage traffic efficiently by forwarding packets only to the intended destination, reducing collisions. Additionally, I explored ARP tables to understand IP-MAC address mappings and utilized commands like ping to verify network connectivity.

## Lab 4
### Switching Lab (VLAN & Trunks) on Packet Tracer 
I configured and verifying VLANs using Packet Tracer. The key focus was on understanding VLANs and their significance in segmenting broadcast domains, crucial for network efficiency. Through various exercises, I learned to implement VLANs in different network topologies and configure trunk ports to enable inter-VLAN communication. Additionally, I observed firsthand how VLAN and trunk configurations impact network traffic flow. My achievements included successfully creating and assigning VLANs to specific departments, enabling seamless communication within VLANs while restricting it between them, and configuring trunk ports to facilitate VLAN traffic across switches.

## Lab 5
### Configure Switching irl
I delved into configuring switching elements like VLANs and trunks on Cisco Layer 2 Switches. Our objectives were to understand Cisco Switches, configure VLANs, and verify Telnet connections. We first built and configured a small network using a Cisco Switch 2960 to ensure connectivity. Then, we moved on to creating and verifying VLANs in the network. Through this process, we learned about switch performance indicators, console connections, and the use of PuTTY for remote access. Additionally, we configured IP addresses on switches, enabled Telnet connections, and assigned VLANs to specific ports.

## Lab 6
### Inter VLAN Routing 
We learned about different methods of inter-VLAN communication, such as traditional methods, router on a stick, layer 3 switch, and switch virtual interface (SVI). In Task 1, we configured Inter-VLAN Routing using Router on a Stick method. This involved creating VLANs, assigning switch ports, configuring trunk ports, assigning static IP addresses to laptops, and configuring inter-VLAN routing on the router. Through this process, we established communication between VLANs and tested connectivity successfully.

In Task 2, we configured Inter-VLAN Routing using a Layer 3 Switch. This included assigning IP addresses, subnet masks, and default gateways to hosts, creating VLANs, configuring SVI VLAN interfaces, configuring access ports, enabling IP routing, and testing inter-VLAN connectivity. We successfully established communication between VLANs using the Layer 3 Switch method.

In Task 3, we completed the topology setup by configuring four VLANs and checking connectivity between VLANs. This involved assigning IP addresses, subnet masks, and default gateways to PCs in different VLANs, configuring routers and switches accordingly, and testing connectivity. Overall, the lab provided hands-on experience in configuring Inter VLAN Routing using different methods, enhancing our understanding of network communication.

## Lab 7 
### Configuration of inter-VLAN on real-life Switches and Routers
My laptop (169.255.211.57) successfully pinged Shaheer's laptop (169.255.211.59) within VLAN 20. However, inter-routing was not implemented, causing ping attempts to fail when targeting devices in VLAN 10, as expected. We attempted inter-VLAN pinging from 169.255.211.57 to 169.254.211.59, highlighting the change in the second field of the IP address, indicative of the Class B network structure. VLAN 10 operates within XXX.254.XXX.XXX, while VLAN 20 operates within XXX.255.XXX.XXX. We also shared pictures of us working in the lab, showcasing our engagement and collaboration during the session within the manual

ENTER PICTURE

## Lab 8 
### Configuring General-purpose Network-Utilities 
we configured general-purpose network utilities and delved into understanding NAT. Starting with the setup of an SMTP server, we assigned IP addresses, configured router interfaces, and enabled SMTP and POP3 services, facilitating email communication between PCs. Subsequently, we configured an FTP server by assigning IPs, enabling FTP services, and adding user accounts, successfully transferring files between devices. Moving on, we set up HTTP and DNS servers, modifying HTML files and specifying domain names and IP addresses, allowing web access using domain names. Finally, we dynamically assigned IPs using the router's DHCP server, creating a pool, excluding certain addresses, and configuring PCs for dynamic IP allocation, ensuring proper network functionality.

## Lab 9
### Static and Dynamic Routing Protocols 
we explored static and dynamic routing protocols, aiming to configure them on routers for effective traffic management. Static routing involves manually adding routes to a router's table, suitable for smaller networks, while dynamic routing protocols like RIP automatically calculate the best path based on hop count. Task 1 focused on setting up static routes, interconnecting routers, assigning IP addresses, and configuring static routes via CLI commands. Task 2 extended this by configuring static routing on a different network topology, ensuring proper connectivity between routers and attached PCs. Task 3 introduced Routing Information Protocol (RIP), a distance vector protocol utilizing hop count for route selection. We configured RIP on routers, monitored its operation using commands like "show ip protocols" and "debug ip rip," and verified routing tables for successful configuration. Task 4 reiterated these concepts with a different network topology, emphasizing RIP routing configuration, and validating routing tables to ensure correct operation. Throughout the lab, adherence to specified configurations and thorough verification ensured a comprehensive understanding of routing protocols and their implementation.

## Lab10 
### Subnetting

## Lab11
### Configuration of Standard, Extended Access Control List, NAT and PAT

## Lab12
### Open Shortest Path First (OSPF) Routing

