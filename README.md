# supreme-octo-memory
Velocity L1 White Paper

Peer2Peer Cyrpto (an L1 Solution)
By RadarLock

radarlock@protonmail.ch

The problem: Too many coins doing too many different things, disjointly. We have Bitcoin (store of value), Ethereum (Smart Contracts), ChainLink (Oracles) and Monero (anonymity). No L1 solution has been proposed to deal with this issue, much less the high fees and slow network times from Proof of Work (PoW) and Proof of State (Pos) methods validation methods.

A Proposed Solution (in bullet point form)

1. We will call the coin Velocity, for working purposes.
2. Velocity will have a Genesis block generated by an anon, and from that Gensis block a certain number of coins will be created with each bearing a unique serial number (like cash). These serial numbers will be retained in a de-centralized repositiory.
3. The private key to that block will be destroyed upon creation of the initial set of coins to prevent unwanted minting of new coins. Failure to destroy the key will endanger the entire system.
4. Each coin generated from the Genesis block will have the value of 1 Satoshi (BTC) to begin with.
5. These coin may be combined to generate a hash of the value of the total transaction.
6. The value may be looked up off a hash table, or quickly computed mathematically.
7. The following will be transmitted with each transaction attempt: (1) the amount as a hash, (2) a hash of the user wallet ID, (3) a hash of the combined serial numbers, and (4) any additional requested/required information (e.g., a smart contract). These will be hashed so that only the end user can see what was sent.
8. The recipient wallet may accept a transaction, reject it, or send it to a miner for validation.
9. Miners will reverse the hash mathematically and through hash tables to ensure no double-spend (by comparison to coins issued on the Genisis block and their descedants). If you trust that there was no double-spend you may simply accept the amount, but you assume any risk of a fraudulent double-spend.
10. Because there is a (de)central repo against which hashed values may be checked, end users can act as the validator, creating the first Peer to Peer solution in crypto.
11. TX fees will be low, or perhaps not exist (i.e., voluntary).

The TL;DR: Double spend problem solved, Peer 2 Peer crypto created that is compatible at the L1 with Ring Signatures, Smart Contracts and Oracles. A trust system (PoT = Proof of Trust | PoH = Proof of History) largely replaces mining, and loss of trust results in sanctions to the offending wallet. This system is also language agnostic, relying on the wallet to interpret next actions. For example, a wallet written in Angular/Electron could implement a smart contract (which is really just computing power on loan) based on a protocol acceptable to both end users.

We have not overlooked that this allows other cryptos to be wrapped by Velocity as an L2 implementation. Insurance and DE-FI should also be possible at the L2.
