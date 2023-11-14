# Networking Concepts and Commands

This document contains explanations of various networking concepts and commands used in computer networks.

## Networking Concepts

1. **Hub**
   - Purpose: A hub operates at Layer 1 (Physical Layer) and forwards incoming data to all connected devices. Active hubs regenerate and amplify signals before broadcasting.
   - Example: Active Hub (or Hub with Repeater)

2. **Handling Collisions in a Hub**
   - Explanation: Hubs lack intelligence to manage collisions. Collisions occur when multiple devices attempt to transmit data simultaneously. The hub simply amplifies and broadcasts incoming signals.

3. **Switch's MAC Address Table**
   - Purpose: Stores MAC addresses and associated switch ports, allowing intelligent forwarding of frames to specific devices.

4. **Role of a Router**
   - Purpose: Connects different networks, directing data based on IP addresses. Operates at Layer 3 (Network Layer) of the OSI model.

5. **Difference Between Router and Switch**
   - Explanation: Router connects networks using IP addresses (Layer 3), while a switch connects devices within the same network using MAC addresses (Layer 2).

6. **Routing in Networking**
   - Explanation: Involves determining the optimal path for data between different networks. Routers use routing tables and protocols to make these decisions.

7. **OSI Model**
   - Purpose: A conceptual framework with seven layers, standardizing telecommunication or computing functions to design network architectures.

8. **Difference Between Hub and Repeater**
   - Explanation: Hub blindly broadcasts signals, while a repeater amplifies signals without differentiating between devices.

9. **Role of Default Gateway**
   - Explanation: Acts as the router a device uses to access networks outside its own; serves as the exit point for non-local traffic.

10. **Purpose of an IP Address**
    - Explanation: Uniquely identifies a device on a network, facilitating proper addressing and routing of data packets.

## Networking Commands

Below are commands used in networking:

1. `ping` - Checks host reachability and measures round-trip time.
2. `tracert` (or `traceroute`) - Traces the route packets take to a destination.
3. `arp -a` - Displays and modifies ARP translation tables.
4. `netstat -a` - Shows active network connections and related information.
5. `ipconfig /all` - Displays IP configuration for all network interfaces.
6. `ftp` - Transfers files between local and remote hosts.
7. `nslookup` - Queries DNS servers to obtain domain name or IP address mapping.
8. `snmpget`, `snmpgetbulk`, `snmpset` - SNMP commands to retrieve or set values from a target SNMP agent.

