# Energy efficiency of the network

Recent global developments have witnessed a rise in concerns related to environmental impact and energy sustainability, and blockchain is no exception.

Zetrix currently uses 21 super nodes and 200 common nodes to realize the overall blockchain service. Therefore, it takes the conventional CPU (Intel I7-8550，The power consumption is 230W) as an example to evaluate the overall power consumption by querying the daily power consumption of the CPU.

In balancing the factors affecting network efficiency, power consumption and degree of decentralisation to be practical and sustainable for the network's growth, Zetrix' DPOS and pBFT consensus mechanism allows a relatively smaller set of validator nodes to perform more efficiently as compared to Ethereum's proof-of-stake mechanism, which in itself consumer at least 2 orders of magnitude lesser power than Bitcoin's network.

### Comparison: Energy Efficiency Comparison

|   Consensus Mechanism  |    Number of Nodes   | Power Consumption | Power Consumption / Day | Power Consumption / Year |
| :--------------------: | :------------------: | :---------------: | :---------------------: | :----------------------: |
|       PoW Bitcoin      |       2,235,100      |    37.77 (W/T)    |       0.18 (TWH)        |        65.70 (TWH)       |
|      PoW Ethereum      |       2,383,701      |     3.43 (W/M)    |        0.08 (TWH)       |        29.20 (TWH)       |
|      PoS Ethereum      | 1,015,570 (May 2024) |      0.30 (W)     |        0.00000712       |        0.0026(TWH)       |
| DPOS + zBFT Zetrix     |        21+100        |      0.23 (W)     |     0.00000067 (TWH)    |       0.00024 (TWH)      |

Note: \
Number of Nodes: the number of online miners/validators. \
Power Consumption: the power consumption of medium miners/validators.
