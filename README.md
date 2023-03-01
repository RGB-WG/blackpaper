---
description: Turing-complete, Scalable & Confidential Smart Contract Layer for Bitcoin & LN
---

# RGB Blackpaper

Maxim Orlovsky 1,2; Peter Todd 1; Giacomo Zucco 1; Federico Tenga 3; Olga Ukolova 1,2

_1.LNP/BP Standards Association_

_2.Pandora Prime_

_3.iFinex Inc_

## Abstract

This paper proposes a novel “post-blockchain” smart contract system, named RGB. It is based on the concept of client-side-validation, separating contract state and operations from the consensus level. With this approach, contracts are sharded (each contract is a standalone shard), kept and validated only by contract participants, bringing native privacy and scalability mechanism, exceeding abilities of all existing blockchain-based smart contracts while not compromising on security or decentralization. RGB as a smart contract system doesn’t require any specific token/coin to operate and is implemented on top of bitcoin blockchain, as the most secure decentralized system. It also can operate on top of layer-2 protocols, such as sidechains, lightning network and other future protocols. It is fully compatible with all existing bitcoin technologies (scriptless scripts, DLCs, atomic swaps) and future possible bitcoin softforks and doesn’t require any changes to the base bitcoin layer. RGB uses specially-designed functional registry-based RISC virtual machine AluVM, which is Turing-equivalent\* and is able to operate global state with the same availability guarantees as with existing blockchain-based systems. RGB has a strong privacy-preserving emphasize, using modified form of Blockstream’s confidential transaction technology (based on Pedersen commitments, enhanced with Bulletproofs++ range proofs) and cryptographic hash concealments for non-fungible state, such that even contract participants do not see full information about past contract history - while still be able to validate it. The paper presents an initial implementation of RGB technology and discusses possible applications of it for building rich, private, scalable and censorship-resistant applications on top of bitcoin and lightning network, including bitcoin finance (“BiFi”) and non-financial forms of smart contracts.

\* in the same terms as EVM and WASM-based smart contracts, i.e. nearly computationally universal, bound by number of operation steps, measured by gas consumption in Ethereum-like systems, and by accumulated computational complexity measure in case of AluVM.
