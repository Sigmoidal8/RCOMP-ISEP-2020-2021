RCOMP 2020-2021 Project - Sprint 2 - Member 1191091 folder
===========================================

## Information
- End user outlets on the ground floor: 40 nodes
- End user outlets on floor one: 44 nodes
- Wi-Fi network: 60 nodes
- Local servers and administration workstations (DMZ): 250 nodes
- VoIP (IP-phones): 40 nodes


## Distribuction

The range of addresses to my building is 10.125.232.0 to 10.125.235.255

| VTP Domain  | VLAN ID | Subnet Address  | Net Mask  | Available Address Range  |  Broadcast Address | Available Hosts |
|---|---|---|---|---|---|---|
|  3_0 (Floor 0)| 315  | 10.125.233.128/26  | 255.255.255.192   | 10.125.233.129 - 10.125.233.190  | 10.125.233.191  | 62  |
|  3_1 (Floor 1)| 316  | 10.125.233.64/26   | 255.255.255.192   | 10.125.233.65 - 10.125.233.126   | 10.125.233.127  | 62  |
|  3_WIFI       | 317  | 10.125.233.0/26    | 255.255.255.192   | 10.125.233.1 - 10.125.233.62     | 10.125.233.63   | 62  |
|  3_DMZ        | 318  | 10.125.232.0/24    | 255.255.255.0     | 10.125.232.1 - 10.125.232.254    | 10.125.232.255  | 254 |
|  3_VoIP       | 319  | 10.125.233.192/26  | 255.255.255.192   | 10.125.233.193 - 10.125.233.254  |  10.125.233.255 | 62  |
