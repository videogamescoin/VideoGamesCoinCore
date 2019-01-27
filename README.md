# videogamescoin

![VideoGamesCoin Logo](/vgc_logo.png)

Coin specifically designed for use with in Video Games to buy game assets
---
VideoGamesCoin is a cryptonote based coin specifically designed to use within Video Games.

It has same features like privacy, fungibility as other cryptonote based coins.

## Coin Specifications
* Ticker: VGC
* Max Supply: 100,000,000
* Emission Factor: 18
* Block Timing: 120 Seconds (2 min)

## Usage
VideoGamesCoin is a cryptonote-based coin compatible with [forknote](https://github.com/forknote/forknote).

A standalone GUI wallet is coing soon

## How to run node?

1. Install required packages

videogamescoin>> sudo apt-get update

videogamescoin>> sudo apt-get install libboost-all-dev

videogamescoin>> sudo apt-get install build-essential cmake pkg-config libssl-dev libunbound-dev libminiupnpc-dev libunwind8-dev liblzma-dev libldns-dev libexpat1-dev libgtest-dev doxygen graphviz


2. Now download VideoGamesCoin config file from https://github.com/videogamescoin/config. The file name is videogamescoin.conf

3. Create a folder named configs in the folder where forknoted is located.

4. Copy the videogamescoin.conf file in the configs folder.

5. Now you can run the node using the following command: ./forknoted --config-file configs/videogamescoin.conf

## How to generate a new Wallet Address?

1. Run the node by following instructions above.

2. Run the simplewallet using the following command: ./simplewallet --config-file configs/videogamescoin.conf and then follow instructions. The Wallet will have prefix VEo.
