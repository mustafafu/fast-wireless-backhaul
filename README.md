# Fast Wireless Backhaul: A Multi-Connectivity Enabled mmWave Cellular System

## Abstract
Next generation cellular networks will rely heavily on mmWave and THz spectrum for the abundantly available bandwidth. However, these frequencies suffer from high path and penetration losses. One way to improve the performance is network densification which comes with higher operational cost. To reduce the operational cost of Base Station (BS) deployment, the 3GPP has proposed the Integrated Access and Backhaul (IAB) architecture. Nonetheless, when a handover does occur in IAB networks, even with minimal handover time, the traffic that is already en route to the UE is delayed, as the new serving BS must retrieve the packets from either the previous serving BS or the core. To address these challenges, we propose Fast Wireless Backhaul (FWB), a new wireless backhaul solution. FWB takes advantage of the multi-connectivity of UEs and the high-capacity low-cost wireless backhaul promised by IAB to reduce latency and increase reliability in case of unexpected blockages on the wireless signal path. In FWB, the BSs serving the UE participate in a multicast tree, and receive all packets designated for the UE, but only one BS transmits packets to the UE. In the event of a link failure between the UE and the serving BS, another BS takes over to maintain the data plane connection, without first having to retrieve undelivered downlink packets. We believe our architecture can enable mission critical applications with stringent latency and reliability requirements.




## Mininet + P4 Implementation
https://github.com/ThanosKou/p4_FWB
