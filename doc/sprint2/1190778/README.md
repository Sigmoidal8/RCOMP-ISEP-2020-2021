RCOMP 2019-2020 Project - Sprint 2 - Member 1190778 folder
===========================================
## Information
- End user outlets on the ground floor: 40 nodes
- End user outlets on floor one: 50 nodes
- Wi-Fi network: 60 nodes
- Local servers and administration workstations (DMZ): 250 nodes
- VoIP (IP-phones): 25 nodes


## Distribuction

The range of addresses to my building is 10.125.236.0 to 10.125.239.255.

| VLAN Domain  | VLAN ID | Subnet Address  | Net Mask  | Available Address Range  |  Broadcast Address | Available Hosts |
|---|---|---|---|---|---|---|
|  4_0(Floor 0) | 320  | 10.125.237.128/26  | 255.255.255.192  | 10.125.237.129 - 10.125.237.190  | 10.125.237.191  | 62 |
|  4_1(Floor 1) | 321  | 10.125.237.64/26   | 255.255.255.192  | 10.125.237.65 - 10.125.237.126  | 10.125.237.127  | 62 |
|  4_WIFI | 322  | 10.125.237.0/26   | 255.255.255.192  | 10.125.237.1 - 10.125.237.62  | 10.125.237.63  | 62 |
|  4_DMZ | 323  | 10.125.236.0/24   | 255.255.255.0  | 10.125.236.1 - 10.125.236.254 | 10.125.236.255  | 254 |
|  4_Voip | 324  | 10.125.237.192/27   | 255.255.255.224  | 10.125.237.193 - 10.125.237.222	  | 10.125.237.223 | 30 |

## Notes

- The switch called "MainCrossConnect" is the one assuming the server role, because that switch is simulating the connection to the main cross connect.
