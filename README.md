# IP Calculator
Ip Subnet Calculator (IP address, subnet mask, Network ID, host address ranges, broadcast calculation)
## Usage 1:
`$python ip_calculator.py 192.168.0.1`
## Result
```bash
Calculating the IP range of 192.168.0.1/24
==================================
Netmask 255.255.255.0
Network ID 192.168.0.0
Subnet Broadcast address 192.168.0.255
Host range 192.168.0.1 - 192.168.0.254
Max number of hosts 254
```

## Usage 2:
`$python ip_calculator.py 192.168.0.1/12`
## Result
```bash
Calculating the IP range of 192.168.0.1/12
==================================
Netmask 255.240.0.0
Network ID 192.160.0.0
Subnet Broadcast address 192.175.255.255
Host range 192.160.0.1 - 192.175.255.254
Max number of hosts 1048574
```
