{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Proof of Authority Development Chain\n",
    "\n",
    "I have just graduated as a blockchain developer and got hired by a local bank that is interested in how blockchain technology can help the bank and their customers. My assignment is to set up a blockchain testnet.\n",
    "\n",
    "I set up the custom testnet as farmersnet and tested on the Proof of Authority algorithm. I successfully conducted transactions on sending and receiving ethereum.\n",
    "\n",
    "The following are the steps to follow on how to use the chain.\n",
    "\n",
    "install Ethereum Go.\n",
    "set up accounts for two nodes for the network with a separate `datadir` for each using `geth`.\n",
    "\n",
    "use Puppeth, a Blockchain tool to generate the genesis block.\n",
    "\n",
    "set up network directory as farmersnet\n",
    "\n",
    "configure the network, set u chain ID, account passwords\n",
    "test Proof of Authority consensus algorithm.\n",
    "\n",
    "both account addresses from the first step one at a time into the list of accounts to seal.\n",
    "\n",
    "Paste them again in the list of accounts to pre-fund.\n",
    "\n",
    "Manage existing genesis\n",
    "\n",
    "Export genesis configurations as farmersnet.json. \n",
    "\n",
    "Initialize each node with the new `networkname.json` with `geth`.\n",
    "initialize and connect the nodes together."
   ]
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
