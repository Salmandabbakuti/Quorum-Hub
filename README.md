## Quorum-Hub-Everything About Quorum Blockchain.
Have a look at this article before going further.. A Beginner guide to Quorum Blockchain at https://link.medium.com/8FCxEYhk8W
1. Forked Enterprise Ethereum blockchain.

2. Specifically Designed for private Transactions between nodes. 

3. Quorum Uses a)Raft based and b)Istanbul consensus Algorithms.

4. Quorum Uses tessara and Constellation for encrypting and sharing data across nodes.

5. Quorum network doesn't cost ether for transactions. basically transaction verification is done by voting Consensus mechanism.

6. Quorum has similarities like ethereum. except, there is a parameter "privateFor". it makes Quorum really standout. this "privateFor" parameter plays vital role in doing private transactions. every node has its own privatekey-Publickey pair generated by quorum network manager. if we wanted particular node only to be part of the transaction, we will pass public key of participating node with privateFor parameter. 

## Working With nodes
in previous article, we checked how private transactions work on quorum network by running pre-configured nodes in quorum-examples. Now we are going to create each node and check how things work. for this, Im using a framework called quorum maker. lets see how it could make our day better.


### So , What is quorum-maker?
A Framework For creating, joining ,attaching nodes.
Also, for creating testnetwork with integrated Web UI.
