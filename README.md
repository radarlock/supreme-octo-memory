# supreme-octo-memory
Velocity L1 White Paper

Peer2Peer Cyrpto (an L1 Solution)
By RadarLock
radarlock@protonmail.ch

The problem: Too many coins doing too many different things, disjointly. We have Bitcoin (store of value), Ethereum (Smart Contracts), ChainLink (Oracles) and Monero (anonymity). No L1 solution has been proposed to deal with this issue, much less the high fees and slow network times from Proof of Work (PoW) and Proof of State (Pos) methods validation methods.

A Proposed Solution (in bullet point form)

1. We will call the coin Velocity, for working purposes
2. Velocity will have a Genesis block generated by an anon
3. The private key to that block will be destroyed upon creation of the initial set of coins to prevent unwanted minting of new coins
4. Each coin generated from the Genesis block will have the value of 1 Satoshi (BTC) to begin with
5. These coin may be combined to generate a hash of the value of the total transaction
6. The value may be looked up off a hash table, or quickly computed mathematically
7. The following will be transmitted with each transaction attempt: (1) the amount hash, (2) a hash of the user wallet ID, and (3) any additional requested/required information (e.g., a smart contract). These will be hashed so that only the end user can see what was sent.
8. The recipient wallet may accept, reject or send a transaction for validation to a miner.
9. Miners will reverse the hash mathematically and through hash tables to ensure no double-spend. If you trust that there was no double-spend you may simply accept the amount, but you assume any risk of a fraudulent double-spend.
10. Because there is a central repo against which hashed may be checked, end users can act as the validator, creating the first Peer to Peer solution in crypto.

The TL;DR: Double spend problem solved, Peer 2 Peer crypto created that is compatible at the L1 with Ring Signatures, Smart Contracts and Oracles. A trust system (PoT = Proof of Trust | PoH = Proof of History) largely replaces mining, and loss of trust results in sanctions to the offending wallet. This system is also language agnostic, relying on the wallet to interpret next actions.

We have not overlooked that this allows other cryptos to be wrapped by Velocity. Insurance and DE-FI should also be possible.
