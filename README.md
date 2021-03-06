# Self-Organized-Energy-Efficient-Cross-Layer-Optimization-for-Device-to-Device-Communication-in-Heterogenous Cellular Networks
## Summary
Device to device (D2D) communication brings numerous benefits for future heterogeneous cellular networks. However, an energy-effcient design of such D2D communications is a critical challenge due to the cochannel deployment and limited power of users. We present an energy-efficient self-organized cross-layer optimization scheme, which aims to maximize the D2D communication energy-effciency without jeopardizing the quality of service (QoS) requirements of other tiers. Specifically, we model the cross-layer optimization, which includes resource block (RB) and power allocation using a noncooperative game. In the proposed scheme, each D2D transmitter user, which is a player in the game, operates in a self-organizing manner and selects the RBs and the power levels for enhancing its energy effciency while maintaining the QoS requirements of other heterogeneous parties. Concerning the computationally intense nature of the global optimization problem, we decompose the problem into two subproblems: the RB allocation and the power allocation, and solve them iteratively in a game-theoretic manner. Simulation results demonstrate superior energy effciency performance of the proposed scheme over conventional schemes. In addition, it is also shown via simulation that the performance of the proposed scheme degrades if the channel state information is not precisely available.
![Alt text](https://user-images.githubusercontent.com/24733570/31720329-91345694-b416-11e7-9fc6-52be5935f525.jpg)
## Problem formulation
In contemplation of enhancing the energy effciency of the D2D communications by exploiting a joint RB and power allocation, the optimization problem can be formulated as:
![Alt text](https://user-images.githubusercontent.com/24733570/31723268-aa2f2392-b41e-11e7-974e-59608e1f47a5.png)
![Alt text](https://user-images.githubusercontent.com/24733570/31723513-5404aafe-b41f-11e7-9e32-44ffbc3a91e5.png)

where BDl and CD corresponds to the allocation of Q RBs and their corresponding power levels by each lth D2DTU. The constraints C1 - C3 represent the satisfaction of the minimum throughput requirements of the considered three-tier users, respectively, the constraint C4 represents the minimum power allocation bound on each RB and the constraint C5 represents that maximum number of RBs acquired by each D2DTU.
## Propsoed algorithm for self-organized RB and power allocation using non-cooperative game
![Alt text](https://user-images.githubusercontent.com/24733570/31723752-011c9b0c-b420-11e7-95ee-951410e0468e.png)

# Reference
If you want more information, then your can refer to our publised paper. In addition, if you find any information in the content that is help for your research, then please cite the paper in your work.

*Shahid A, Kim KS, De Poorter E, Moerman I. Self-Organized Energy-Efficient Cross-Layer Optimization for Device to Device Communication in Heterogeneous Cellular Networks. IEEE Access. 2017;5:1117-28.*

# Contact
adnan.shahid@ugent.be
