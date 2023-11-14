
# Network Commands Reference

## Ping

**Purpose:** Checks the reachability of a host on a network and measures round-trip time for messages.

**Example:**
```bash
ping google.com
```

## Traceroute (Tracert in Windows)

**Purpose:** Traces the route that packets take to reach a destination, displaying IP addresses of each hop.

**Example:**
```bash
traceroute google.com  # Linux
tracert google.com     # Windows
```

## Address Resolution Protocol (ARP)

**Purpose:** Displays and modifies the IP-to-Physical address translation tables used by the ARP protocol.

**Example:**
```bash
arp -a
```

## Netstat

**Purpose:** Displays active network connections, listening ports, and related information.

**Example:**
```bash
netstat -a
```

## IP Configuration (ipconfig in Windows)

**Purpose:** Displays IP configuration for all network interfaces on a computer.

**Example:**
```bash
ipconfig /all  # Windows
```

## File Transfer Protocol (FTP)

**Purpose:** Transfers files between a local and a remote host.

**Example:**
```bash
ftp example.com
```

## Name Server Lookup (Nslookup)

**Purpose:** Queries DNS servers to obtain domain name or IP address mapping.

**Example:**
```bash
nslookup google.com
```

## Simple Network Management Protocol (SNMP)

### snmpget

**Purpose:** Retrieves the value of a specific object from a target SNMP agent.

**Example:**
```bash
snmpget -v:2c -c:public 192.168.1.1 1.3.6.1.2.1.1.1.0
```

### snmpgetbulk

**Purpose:** Retrieves a large amount of data from a target SNMP agent.

**Example:**
```bash
snmpgetbulk -v:2c -c:public 192.168.1.1 1.3.6.1.2.1.1
```

### snmpset

**Purpose:** Sets the value of a specified object on a target SNMP agent.

**Example:**
```bash
snmpset -v:2c -c:private 192.168.1.1 1.3.6.1.2.1.1.6.0 i 2
```

---

Feel free to adjust formatting or add further explanations as needed for your specific use case!
