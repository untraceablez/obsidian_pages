---
tags: hardware, production
parent: [[Production Cluster]]
---

## Specifications:

| Hardware Type | Hardware                                | Notes                                                 |
| ------------- | --------------------------------------- | ----------------------------------------------------- |
| CPU           | Intel Core i9-13900                     | 16c/32t                                               |
| RAM           | 128GB DDR5                              |                                                       |
| SSD Storage   | 4x 1TB NVMe, 1x 512GB SATA, 1x 1TB SATA | NVMe and 1TB SATA all Ceph OSDs, 512GB is boot drive. |
| HDD Storage   | 1x 10TB, 1x 20TB                        | Ceph OSDs                                             |
| Networking 1  | enp8s0, 1Gig                            | Connected to main LAN, 10.0.0.1/24                    |
| Networking 2  | enp7s0, 2.5Gig                          | Connected to cluster network. Also used for ceph.     |
| GPU           | GTX 1050                                |                                                       |
