### A decentralised version of a game like monopoly without any software on a central server:
Monopoly could be implemented in a decentralized network in a peer-to-peer fashion similar to blockchain. 
Each player can be represented by a node which is a part of the blockchain.

#### Addressing the following problems:

- cheating  
  It can be ensured that no cheating is done by the help of a shared ledger. 
All the nodes will have a common ledger which will keep a track of the progress of the game via transactions. If any modification is done by a single node, 
it can be easily tracked since all the other nodes will have a different version of the ledger without the modification.

- ensuring agreement about the state of the system  
  A consensus mechanism like proof-of-work or proof-of-stake can be followed.

- communication problems (timeouts)  
  A smart contract having a fixed timer running during each player's turn can be implemented which will take care of the timeouts. In case a player fails to make a move
within the specified time, it will be the next player's turn.

- how to decide who should take the next turn  
  A voting mechanism can be adopted or a smart contract having a random number generator can be deployed.

- how to allow the correct people to join the game  
  Participation in the game would require registration and players can sign-in using their public key. We can restrict the participation by
setting a rule wherein a particular amount of cryptocurrency has to be staked in order to participate.
