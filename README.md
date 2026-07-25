<h1>Network Topology
  
<img width="1216" height="714" alt="image" src="https://github.com/user-attachments/assets/1f647066-34f0-42aa-91a8-d90de372e7ec" />


<h1>Network Architecture

  The network adopts a two-tier hierarchical design model, which provides a clear
separation between routing and switching functions, simplifies troubleshooting, and supports
future scalability. The two tiers are defined as follows:

Core / Distribution Tier : Contains R1 (Cisco 2911) responsible for WAN connectivity,
server farm access, and OSPF routing; and MLS (Cisco 3650-24PS) responsible for VLAN
switching, interVLAN routing via SVIs, DHCP services, and ACL enforcement.

Access Tier : Contains five department access switches (Cisco 2960-24TT)
and one server farm switch, each providing Layer 2 connectivity for end devices.

External Infrastructure : Contains ISP-R simulating the internet service provider,
hosting public servers and routing HQ traffic; and HQ-R providing the branch office LAN
gateway.
