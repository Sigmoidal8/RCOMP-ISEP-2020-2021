RCOMP 2020-2021 Project - Sprint 1 - Member 1190780 folder
===========================================

## Information
- Backbone:120 nodes
- End user outlets on the ground floor: 40 nodes
- End user outlets on floor one: 40 nodes
- Wi-Fi network: 24 nodes
- Local servers and administration workstations (DMZ): 70 nodes
- VoIP (IP-phones): 20 nodes

## Distribuction

The range of addresses to my building is 10.125.224.0 to 10.125.227.255.

| VLAN Domain  | VLAN ID | Subnet Address  | Net Mask  | Available Address Range  |  Broadcast Address | Available Hosts |
|---|---|---|---|---|---|---|
|  Backbone      | 325  | 10.125.224.0/25  | 255.255.255.128 | 10.125.224.1 - 10.125.224.126 |  10.125.224.127| 126   |
|  (1_0) Floor_0 |  305 | 10.125.225.0/26  | 255.255.255.192 | 10.125.225.1 - 10.125.225.62  |  10.125.225.63 | 62 |
|  (1_1) Floor_1 | 306 | 10.125.225.64/26  | 255.255.255.192	  | 10.125.225.65 - 10.125.225.126 | 10.125.225.127  | 62 |
|  1_WIFI |  307 | 10.125.225.128/27  | 255.255.255.224 | 10.125.225.129 - 10.125.225.158  | 10.125.225.159 | 30 |
|  1_DMZ | 308  | 10.125.224.128/25   | 255.255.255.128  | 10.125.224.129 - 10.125.224.254  | 10.125.224.255  | 126 |
|  1_VoIP |  309 | 10.125.225.160/27  | 255.255.255.224  | 10.125.225.161 - 10.125.225.190  | 10.125.225.191 | 30 |
