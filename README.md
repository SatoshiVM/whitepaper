# SatoshiVM

## Vision and Introduction

SatoshiVM is a decentralized Bitcoin ZK Rollup Layer2 solution compatible with the Ethereum Virtual Machine (EVM) ecosystem, using native BTC as gas. SatoshiVM bridges the EVM ecosystem with Bitcoin, enabling the Bitcoin ecosystem to issue assets and develop applications.

We have improved a method that can verify the correct execution of arbitrary functions on Bitcoin, making it more suitable for Layer2 block validation. Verification System of SatoshiVM  is a system that can ensure the accurate execution of Layer2 blocks on Bitcoin. This system does not require any modifications to Bitcoin itself. It is capable of confirming whether a series of Layer2 blocks are executed correctly on Bitcoin without any changes to the existing infrastructure. This allows Bitcoin to serve as a settlement layer for Layer2, enhancing the security of Bitcoin Layer2 transactions.

The system leverages the features of Taproot, which enables the representation of the execution process of a set of complex functions through a single hash. By fully executing the ZK proof process off-chain for a block and verifying the proof on Bitcoin through Taproot, the system ensures the validation of blocks. Additionally, when the block miner on Layer2 sends each block validation transaction, they also submit the hash of the corresponding block data and proof data to Bitcoin. Subsequently, anyone can use relevant hash submitted to Bitcoin to obtain comprehensive data from a specific DA layer for third-party verification of Layer2 blocks.

For more details, you can visit SatoshiVM Overview.

## Links

Homepage: https://satoshivm.io/
Explorer(testnet): https://testnet.svmscan.io/
Docs: https://docs.satoshivm.io/
