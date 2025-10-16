# BFT

Byzantine Fault Tolerance (BFT) is the feature of a distributed network to reach consensus (agreement on the same value) even when some of the nodes in the network fail to respond or respond with incorrect information. The objective of a BFT mechanism is to safeguard against the system failures by employing collective decision making (both – correct and faulty nodes), which aims to reduce the influence of the faulty nodes.

The nodes that enter the validating node-set through the DPOS mechanism, generate blocks based on the Byzantine fault-tolerant algorithm. The Byzantine fault-tolerant algorithm based on message passing and ensuring high performance and high consistency have strict restrictions on the number of nodes. However, Zetrix needs a large number of validating nodes to participate in the consensus to ensure the decentralisation features. Based on this goal, Zetrix proposed the zBFT algorithm to solve the above problems.

The consensus algorithm will divide the future blocks into multiple time slices, and certain time slice random algorithm will generate 21 block validating nodes, and then the validating node-set will generate the block by the BFT algorithm consensus. The zBFT algorithm Zetrix proposed has several innovations. First, the node-set can be changed through the random algorithm to ensure the security of the blockchain; secondly, the Quorum in the set is optimized to improve the Liveness of the consensus; finally, the ViewChange message is optimized to reduce the complexity of the message transmission, reducing from O(n<sup>2</sup>)to O(n).

<figure><img src="https://lh6.googleusercontent.com/EBILvgQHxYm78b6SY3Nz9tSxK5DbOHdy7E_VJpVRNYYsthSoZzwOLf4jQ8fXYk5eWtfAK9x4pMSN_beI0kWh9z8EsteRBrv_ENbY3ACwY2hleTzQ75h2OZwVL0wvNlxXeWvw1-b4nF-bf9baSNX5WaeChOb_9FgnUS1-KuuSr543PQWuTwZ5FahrNVueYXUOyl3Srg" alt=""><figcaption></figcaption></figure>

zBFT in Zetrix is the algorithm that the nodes use to reach finality even if there are certain numbers of other nodes that are faulty. This ensures that Zetrix will remain available for users at all times and minimise the amount of service interruptions.
