RCOMP 2019-2020 Project - Sprint 2 - Member 1190986 folder
===========================================

## Information
- End user outlets on the ground floor: 60 nodes
- End user outlets on floor one: 70 nodes
- Wi-Fi network: 100 nodes
- Local servers and administration workstations (DMZ): 12 nodes
- VoIP (IP-phones): 35 nodes

## Distribuction

The range of addresses to my building is 10.125.228.0 to 10.125.231.255.

| VLAN Domain  | VLAN ID | Subnet Address  | Net Mask  | Available Address Range  |  Broadcast Address | Available Hosts |
|---|---|---|---|---|---|---|
|  (2_0) Floor_0 |  310 | 10.125.229.0/26  | 255.255.255.192 | 10.125.229.1 - 10.125.229.62  |  10.125.229.63 | 62 |
|  (2_1) Floor_1 | 311 | 10.125.228.128/25  | 255.255.255.128  | 10.125.228.129 - 10.125.228.254 | 10.125.228.255  | 126 |
|  2_WIFI |  312 | 10.125.228.0/25  | 255.255.255.128 | 10.125.228.1 - 10.125.228.126  | 10.125.228.127 | 126 |
|  2_DMZ | 313  | 10.125.229.128/28   | 255.255.255.240  | 10.125.229.129 - 10.125.229.142  | 10.125.229.143  | 14 |
|  2_VoIP |  314 | 10.125.229.64/26  | 255.255.255.192  | 10.125.229.65 - 10.125.229.126  | 10.125.229.127 | 62 |
