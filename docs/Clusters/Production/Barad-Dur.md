---
tags: hardware, production
parent: [[Production Cluster]]
---
## Specifications:

| Hardware Type | Hardware                                 | Notes                                                       |
| ------------- | ---------------------------------------- | ----------------------------------------------------------- |
| CPU           | Ryzen 9 3900XT                           | 12c/24t                                                     |
| RAM           | 64GB DDR4                                |                                                             |
| SSD Storage   | 2x 2TB NVMe, 1x 512GB SATA, 1x 25GB SATA | 2TB are Ceph OSDs, 512GB is boot drive. 256GB is a Ceph OSD |
| HDD Storage   | 1x 20TB, 2x 10TB                         |                                                             |
| Networking 1  | enp13s0, 1Gig                            | Connected to main LAN, 10.0.0.1/24                          |
| Networking 2  | enp10s0, 2.5Gig                          | Connected to cluster network. Also used for ceph.           |
| GPU 1         | GTX 1050                                 |                                                             |
| GPU 2         | RTX 2070 SUPER                           |                                                             |
