RCOMP 2019-2020 Project - Sprint 2 planning
===========================================
### Sprint master: 1190780 ###

# 1. Sprint's backlog #
* T.2.1 Development of a layer two and layer three Packet Tracer simulation for building 1, and also encompassing the campus backbone.
Integration of every members’ Packet Tracer simulations into
a single simulation.
* T.2.2 Development of a layer two and layer three Packet Tracer simulation for building 2, and also encompassing the campus backbone.
* T.2.3 Development of a layer two and layer three Packet Tracer simulation for building 3, and also encompassing the campus backbone.
* T.2.4 Development of a layer two and layer three Packet Tracer simulation for building 4, and also encompassing the campus backbone.


# 2. Technical decisions and coordination #


| Building  | IP range |
|---|---|
|1|10.125.224.0 to 10.125.227.255|
|2|10.125.228.0 to 10.125.231.255|
|3|10.125.232.0 to 10.125.235.255|
|4|10.125.236.0 to 10.125.239.255|

| VLAN Domain  | VLAN ID | Subnet Address  | Net Mask  | Available Address Range  |  Broadcast Address | Available Hosts |
|---|---|---|---|---|---|---|
|  Backbone      | 325  | 10.125.224.0/25  | 255.255.255.128 | 10.125.224.1 - 10.125.224.126 |  10.125.224.127| 126   |
|  (1_0) Floor_0 |  305 | 10.125.225.0/26  | 255.255.255.192 | 10.125.225.1 - 10.125.225.62  |  10.125.225.63 | 62 |
|  (1_1) Floor_1 | 306 | 10.125.225.64/26  | 255.255.255.192	  | 10.125.225.65 - 10.125.225.126 | 10.125.225.127  | 62 |
|  1_WIFI |  307 | 10.125.225.128/27  | 255.255.255.224 | 10.125.225.129 - 10.125.225.158  | 10.125.225.159 | 30 |
|  1_DMZ | 308  | 10.125.224.128/25   | 255.255.255.128  | 10.125.224.129 - 10.125.224.254  | 10.125.224.255  | 126 |
|  1_VoIP |  309 | 10.125.225.160/27  | 255.255.255.224  | 10.125.225.161 - 10.125.225.190  | 10.125.225.191 | 30 |
|  (2_0) Floor_0 |  310 | 10.125.229.0/26  | 255.255.255.192 | 10.125.229.1 - 10.125.229.62  |  10.125.229.63 | 62 |
|  (2_1) Floor_1 | 311 | 10.125.228.128/25  | 255.255.255.128  | 10.125.228.129 - 10.125.228.254 | 10.125.228.255  | 126 |
|  2_WIFI |  312 | 10.125.228.0/25  | 255.255.255.128 | 10.125.228.1 - 10.125.228.126  | 10.125.228.127 | 126 |
|  2_DMZ | 313  | 10.125.229.128/28   | 255.255.255.240  | 10.125.229.129 - 10.125.229.142  | 10.125.229.143  | 14 |
|  2_VoIP |  314 | 10.125.229.64/26  | 255.255.255.192  | 10.125.229.65 - 10.125.229.126  | 10.125.229.127 | 62 |
|  3_0 (Floor 0)| 315  | 10.125.233.128/26  | 255.255.255.192   | 10.125.233.129 - 10.125.233.190  | 10.125.233.191  | 62  |
|  3_1 (Floor 1)| 316  | 10.125.233.64/26   | 255.255.255.192   | 10.125.233.65 - 10.125.233.126   | 10.125.233.127  | 62  |
|  3_WIFI       | 317  | 10.125.233.0/26    | 255.255.255.192   | 10.125.233.1 - 10.125.233.62     | 10.125.233.63   | 62  |
|  3_DMZ        | 318  | 10.125.232.0/24    | 255.255.255.0     | 10.125.232.1 - 10.125.232.254    | 10.125.232.255  | 254 |
|  3_VoIP       | 319  | 10.125.233.192/26  | 255.255.255.192   | 10.125.233.193 - 10.125.233.254  |  10.125.233.255 | 62  |
|  4_0(Floor 0) | 320  | 10.125.237.128/26  | 255.255.255.192  | 10.125.237.129 - 10.125.237.190  | 10.125.237.191  | 62 |
|  4_1(Floor 1) | 321  | 10.125.237.64/26   | 255.255.255.192  | 10.125.237.65 - 10.125.237.126  | 10.125.237.127  | 62 |
|  4_WIFI | 322  | 10.125.237.0/26   | 255.255.255.192  | 10.125.237.1 - 10.125.237.62  | 10.125.237.63  | 62 |
|  4_DMZ | 323  | 10.125.236.0/24   | 255.255.255.0  | 10.125.236.1 - 10.125.236.254 | 10.125.236.255  | 254 |
|  4_Voip | 324  | 10.125.237.192/27   | 255.255.255.224  | 10.125.237.193 - 10.125.237.222	  | 10.125.237.223 | 30 |

* VTP domain name : rcompdkg4
* Backbone node addressing
 * Building 1 : 10.125.224.1
 * Building 2 : 10.125.224.2
 * Building 3 : 10.125.224.3
 * Building 4 : 10.125.224.4 

# 3. Subtasks assignment #

  * 1190778 - Development of a layer two and layer three Packet Tracer simulation for building 4
  * 1190780 - Development of a layer two and layer three Packet Tracer simulation for building 1
  * 1190986 - Development of a layer two and layer three Packet Tracer simulation for building 2
  * 1191091 - Development of a layer two and layer three Packet Tracer simulation for building 3
