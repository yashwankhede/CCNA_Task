# Task 1

### Subnet Analysis Task

**Objective:**
Perform subnet analysis for each provided IP address and its subnet mask. This includes converting the subnet mask into binary representation, calculating the total number of IP addresses in a network, determining the number of networks based on the subnet mask, and identifying the range of each network (Network ID - NID and Broadcast IP - BIP).

**IP Addresses for Analysis:**

1. **IP Address 1:**
   - IP Address: `128.168.1.240`
   - Subnet Mask: `255.255.255.240`

2. **IP Address 2:**
   - IP Address: `192.111.145.56`
   - Subnet Mask: `255.255.255.128`

3. **IP Address 3:**
   - IP Address: `192.168.1.128`
   - Subnet Mask: `255.255.255.224`

4. **IP Address 4:**
   - IP Address: `192.168.1.128`
   - Subnet Mask: `255.255.255.192`

5. **IP Address 5:**
   - IP Address: `192.168.1.128`
   - Subnet Mask: `255.255.255.240`

**Steps to Perform:**
1. Convert each subnet mask into its binary representation.
2. Calculate the total number of IP addresses in each network using the subnet mask.
3. Determine the number of networks based on the subnet mask.
4. Identify and display the range of each network:
   - List the first and last IP addresses (Network ID - NID and Broadcast IP - BIP) for the provided IP address.

# Task 2

### Subnet Analysis Task with Random Class C Subnet Masks

**Objective:**
Generate 10 sets of IP addresses with random Class C subnet masks and perform subnet analysis. For each IP address, calculate and display the Network ID (NID), Broadcast IP (BIP), and the number of networks that IP belongs to based on its subnet mask.

**IP Addresses for Analysis:**

1. **IP Set 1:**
   - IP Address: `192.168.1.10`
   - Subnet Mask: `255.255.255.0`

2. **IP Set 2:**
   - IP Address: `192.168.2.20`
   - Subnet Mask: `255.255.255.128`

3. **IP Set 3:**
   - IP Address: `192.168.3.30`
   - Subnet Mask: `255.255.255.192`

4. **IP Set 4:**
   - IP Address: `192.168.4.40`
   - Subnet Mask: `255.255.255.224`

5. **IP Set 5:**
   - IP Address: `192.168.5.50`
   - Subnet Mask: `255.255.255.240`

6. **IP Set 6:**
   - IP Address: `192.168.6.60`
   - Subnet Mask: `255.255.255.248`

7. **IP Set 7:**
   - IP Address: `192.168.7.70`
   - Subnet Mask: `255.255.255.252`

8. **IP Set 8:**
   - IP Address: `192.168.8.80`
   - Subnet Mask: `255.255.255.254`

9. **IP Set 9:**
   - IP Address: `192.168.9.90`
   - Subnet Mask: `255.255.255.255`

10. **IP Set 10:**
   - IP Address: `192.168.10.100`
   - Subnet Mask: `255.255.255.255`

**Steps to Perform:**
1. Write the Network ID (NID) and Broadcast IP (BIP) of that perticular IP only for each IP address mentioned above based on its subnet mask.
2. Determine the number of network to which the IP belongs to.


**Output should look like:**

IP      : 192.168.1.1
NID     : 0.0.0.0
BIP     : 255.255.255.255
Network : 4th network
