{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Proof of Authority Development Chain"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "ename": "SyntaxError",
     "evalue": "invalid syntax (<ipython-input-1-d43404647d7a>, line 1)",
     "output_type": "error",
     "traceback": [
      "\u001b[0;36m  File \u001b[0;32m\"<ipython-input-1-d43404647d7a>\"\u001b[0;36m, line \u001b[0;32m1\u001b[0m\n\u001b[0;31m    I have just graduated as a blockchain developer and got hired by a local bank that is interested in how blockchain technology can help the bank and their customers. My assignment is to set up a blockchain testnet.\u001b[0m\n\u001b[0m         ^\u001b[0m\n\u001b[0;31mSyntaxError\u001b[0m\u001b[0;31m:\u001b[0m invalid syntax\n"
     ]
    }
   ],
   "source": [
    "\n",
    "I have just graduated as a blockchain developer and got hired by a local bank that is interested in how blockchain technology can help the bank and their customers. My assignment is to set up a blockchain testnet.\n",
    "\n",
    "I set up the custom testnet as farmersnet and tested on the Proof of Authority algorithm. I successfully conducted a few transactions by sending and receiving ethereum between node1 and node1 that I set up.\n",
    "\n",
    "The following are the steps to follow on how to use the chain;\n",
    "\n",
    "install Go Ethereum, blockchain tool;\n",
    "\n",
    "Step one, set up two accounts for node1 and node2 for the network with a separate `datadir` for each using `geth`;\n",
    "\n",
    "use Puppeth, the Blockchain tool to generate the genesis block;\n",
    "\n",
    "set up network directory as farmersnet;\n",
    "\n",
    "configure the network, set up chain ID, account passwords;\n",
    "\n",
    "test Proof of Authority consensus algorithm;\n",
    "\n",
    "For both account addresses from the first step one at a time into the list of accounts to seal.\n",
    "\n",
    "Paste them again in the list of accounts to pre-fund.\n",
    "\n",
    "Choose manage existing genesis then export genesis configurations;\n",
    "\n",
    "Initialize each node with the new `farmersnet.json` with `geth` and connect the nodes together;\n",
    "\n",
    "Run the first node, unlock the account, enable mining and the RPC flag. Only one node needs RPC enabled;\n",
    "\n",
    "Set a different peer port for the second node and use the first node's `enode` address as the `bootnode` flag. Unlock the account and enable mining on the second node;\n",
    "\n",
    "After both nodes producing new blocks, use the MyCrypto GUI wallet to connect to the node;\n",
    "\n",
    "Set up a custom network, and include the chain ID, and use ETH as the currency.\n",
    "\n",
    "Import the keystore file from the `node1/keystore` directory into MyCrypto. This will import the private key.\n",
    "\n",
    "Send a transaction from the `node1` account to the `node2` account as indicated in the screen shots.\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "I have just graduated as a blockchain developer and got hired by a local bank that is interested in how blockchain technology can help the bank and their customers. My assignment is to set up a blockchain testnet.\n",
    "\n",
    "I set up the custom testnet as farmersnet and tested on the Proof of Authority algorithm. I successfully conducted a few transactions by sending and receiving ethereum between node1 and node1 that I set up.\n",
    "\n",
    "The following are the steps to follow on how to use the chain;\n",
    "\n",
    "install Go Ethereum, blockchain tool;\n",
    "\n",
    "Step one, set up two accounts for node1 and node2 for the network with a separate `datadir` for each using `geth`;\n",
    "\n",
    "use Puppeth, the Blockchain tool to generate the genesis block;\n",
    "\n",
    "set up network directory as farmersnet;\n",
    "\n",
    "configure the network, set up chain ID, account passwords;\n",
    "\n",
    "test Proof of Authority consensus algorithm;\n",
    "\n",
    "For both account addresses from the first step one at a time into the list of accounts to seal.\n",
    "\n",
    "Paste them again in the list of accounts to pre-fund.\n",
    "\n",
    "Choose manage existing genesis then export genesis configurations;\n",
    "\n",
    "Initialize each node with the new `farmersnet.json` with `geth` and connect the nodes together;\n",
    "\n",
    "Run the first node, unlock the account, enable mining and the RPC flag. Only one node needs RPC enabled;\n",
    "\n",
    "Set a different peer port for the second node and use the first node's `enode` address as the `bootnode` flag. Unlock the account and enable mining on the second node;\n",
    "\n",
    "After both nodes producing new blocks, use the MyCrypto GUI wallet to connect to the node;\n",
    "\n",
    "Set up a custom network, and include the chain ID, and use ETH as the currency.\n",
    "\n",
    "Import the keystore file from the `node1/keystore` directory into MyCrypto. This will import the private key.\n",
    "\n",
    "Send a transaction from the `node1` account to the `node2` account as indicated in the screen shots.\n",
    "\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
