### Subnet Analysis Task with Class C IP Addresses

**IP Addresses for Analysis:**

1.  IP Address: `192.168.1.10/31`
2.  IP Address: `192.168.1.20/25`
3.  IP Address: `192.168.1.30/28`
4.  IP Address: `192.168.1.40/29`
5.  IP Address: `192.168.1.50/30`
6.  IP Address: `192.168.1.60/26`
7.  IP Address: `192.168.1.70/27`
8.  IP Address: `192.168.1.80/25`
9.  IP Address: `192.168.1.90/32`
10. IP Address: `192.168.1.100/30`

**Steps to Perform:**
1. Calculate the subnet mask (in binary) and the corresponding subnet mask (in decimal) for each IP address.
2. Determine the Network ID (NID) and Broadcast IP (BIP) based on the subnet mask.
3. Calculate the number of networks (N+) and the total number of IPs in each network (N+).

**Example Solution Format:**

For IP Address `192.168.1.10/26`:
- Subnet Mask (Binary): `11111111.11111111.11111111.11000000`
- Subnet Mask: `255.255.255.192`
- NID: `192.168.1.0`
- BIP: `192.168.1.63`
- Number of Networks (N+): `4`
- Number of IPs in a Network (N+): `64`
