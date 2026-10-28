# NETWORKWALKS-KHALEED-SURAJUDEEN-MOHAMMAD-B084A-WK1-PM1-CYBERSECURITY-LAB-SETUB
## 1. Project Overview

This project documents my Week 1 practical lab setup for the Networkwalks cybersecurity training programme. The goal was to configure a Kali Linux virtual machine, establish network connectivity, and verify internet access.

## 2. Tools Used

- Oracle VirtualBox
- Kali Linux
- NAT Network
- DHCP
- Linux terminal
- Ping and DNS troubleshooting commands

## 3. Network Setup

I configured a NAT Network in VirtualBox and enabled DHCP. I then configured my Kali Linux virtual machine to use the network and checked its connectivity.

**Screenshot 1:** VirtualBox version  
**Screenshot 2:** NAT Network and DHCP configuration  
**Screenshot 3:** Kali Linux virtual machine configuration

## 4. Practical Steps

### Step 1: Verify the network configuration

I checked the network configuration in VirtualBox and confirmed that the NAT Network and DHCP settings were configured.

### Step 2: Check network connectivity

I used the following command to test connectivity to an external IP address:

```bash
ping -c 4 8.8.8.8
```

The ping was successful, confirming that the machine could reach the external IP address.

### Step 3: Troubleshoot DNS resolution

Initially, `ping google.com` returned a temporary failure in name resolution. I checked the DNS configuration and corrected the DNS resolution issue.

I then verified that Google’s domain resolved to IP addresses and that the ping command worked successfully.

### Step 4: Verify the final result

I confirmed that Kali Linux could access the network and resolve domain names successfully.

**Screenshot 4:** Successful IP connectivity test  
**Screenshot 5:** DNS resolution and successful domain ping

## 5. Troubleshooting Experience

The main challenge was a DNS resolution failure even though the IP connectivity test was successful.

I investigated the DNS configuration, corrected the issue, and tested the connection again. This helped me understand the difference between network connectivity and DNS resolution.

## 6. Results and Lessons Learned

- Configured a Kali Linux virtual machine in VirtualBox.
- Set up NAT Network and DHCP.
- Tested external network connectivity.
- Diagnosed and resolved a DNS resolution issue.
- Learned how to verify connectivity using Linux terminal commands.

## 7. Conclusion

This practical improved my understanding of virtual networking, DNS, and basic network troubleshooting. It also provided a foundation for future cybersecurity labs.

**Training Programme:** Networkwalks  
**Week:** 1  
**Batch:** B083  
**Track:** Cybersecurity
