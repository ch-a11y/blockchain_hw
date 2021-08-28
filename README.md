# Proof of Authority Development Chain

I have been hired by a local bank that is interested in how blockchain technology can help the bank and their customers. My assignment is to set up a blockchain testnet.

We chose farmersnet as the name and tested on the Proof of Authority algorithm. We successfully conducted transactions by sending and receiving ethereum between the two accounts.

The following are the steps to follow on how to use the chain:

Install Go Ethereum blockchain tool.

Step up two accounts for node1 and node2 for the network with a separate `datadir` for each using `geth`.

./geth account new --datadir node1

./geth account new --datadir node2



Use puppeth, the Blockchain tool to generate the genesis block.

./puppeth



Set up network directory as

farmersnet



Configure the network, set up chain ID, account passwords.

chain ID 888



Test Proof of Authority consensus algorithm.



Paste both account addresses from the first step one at a time into the list of accounts to seal.

Paste them again in the list of accounts to pre-fund.


Choose to manage existing genesis then export genesis configurations.


Initialize each node with the new `farmersnet.json` with `geth` and connect the nodes together.

./geth init farmersnet.json --datadir node1

./geth init farmersnet.json --datadir node2



Run the first node, unlock the account, enable mining and the RPC flag. Only one node needs RPC enabled.
Set a different peer port for the second node and use the first node's `enode` address as the `bootnode` flag.

./geth --datadir node1 --unlock "SEALER_ONE_ADDRESS" --mine --rpc --allow-insecure-unlock

./geth --datadir node2 --unlock "SEALER_TWO_ADDRESS" --mine --port 30304 --bootnodes "enode:
//SEALER_ONE_ENODE_ADDRESS@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock


    
After both nodes produce new blocks, use the MyCrypto GUI wallet to connect to the node.


Set up a custom network, and include the chain ID, and use ETH as the currency.

The node name and network name is farmersnet; chain ID 888, and ETH as the currency

http://127.0.0.1:8545 as the URL


        
Import the keystore file from the `node1/keystore` directory into MyCrypto. This will import the private key.


Send a transaction from the `node1` account to the `node2` account. The transactions were successful as indicated in the screen shots.