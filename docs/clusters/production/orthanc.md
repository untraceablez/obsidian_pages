---
tags: hardware, production
parent: [[Production Cluster]]
---
## Specifications

| Hardware Type | Hardware                     | Notes                                             |
| ------------- | ---------------------------- | ------------------------------------------------- |
| CPU           | Ryzen 9 3900X                | 12c/24t                                           |
| RAM           | 64GB DDR4                    |                                                   |
| SSD Storage   | 1x 512GB NVMe, 1x 512GB SATA | NVME is a Ceph OSD, SATA is boot drive.           |
| HDD Storage   | 1x 10TB, 2x 16TB             | All Ceph OSDs                                     |
| Networking 1  | enp5s0, 1Gig                 | Connected to main LAN, 10.0.0.1/24                |
| Networking 2  | enp4s0, 2.5Gig               | Connected to cluster network. Also used for ceph. |
| GPU           | GTX 1050                     |                                                   |
