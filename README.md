[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/t-SbtQf9)
# bitcoin-core-installation-assignment

Compile and run the integration tests and share the results

Run Bitcoin core v30 and use at least 5 RPC commands and share the output

I installed Bitcoin Core using the official pre-built Windows installer, which includes both GUI and CLI tools. This approach avoids the need for compiling from source and is recommended for users who want to run and interact with a node efficiently.

## ✅ Assignment 1 Output Results

1. Blockchain Info

```json```
"chain": "regtest",
"blocks": 0
- This confirms the node is running in regtest mode.

2. Wallet Creation
{
  "name": "testwallet"
}
-  Wallet named testwallet was successfully created.

3. Address Generation

4. Block Generation

101 blocks were mined, producing multiple block hashes.

5. Wallet Balance
50.00000000 BTC

After mining 101 blocks, the wallet received the mining reward.

6. Wallet Info
"txcount": 101,
"format": "sqlite",
"descriptors": true

This confirms:

Transactions were recorded
A modern descriptor wallet is in use



 


  
