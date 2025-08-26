### Cryptography
Some details about Cryptography in Data Privacy
***
###1. Cryptography Fundamentals
This covers the basic building blocks of encryption and key management.
a.Encryption Types:
 1.Symmetric: Uses a single shared key (e.g., AES, 3DES).
 2.Asymmetric: Uses public/private key pairs (e.g., RSA, ECC).
b.Key Management:
 1.Key Exchange: Securely establishes keys using protocols like Diffie-Hellman (DH/ECDH) and PAKE.
 2.Infrastructure (PKI): Manages public keys and digital certificates.
 3.Lifecycle: Includes key generation, distribution, storage, rotation, and revocation.
 4.Hardware Security: Uses Hardware Security Modules (HSMs) for secure key storage.

2. Anonymity (Hiding Identity)
These techniques focus on concealing a user's identity and making their actions untraceable.
a.Signature Schemes:
 1.Ring Signatures: Allow a group member to sign anonymously; a larger "ring size" increases anonymity.
 2.Other Types: Include Group, Blind, and Threshold signatures for different anonymity scenarios.
b.Transaction Obscurity:
 1.Mixing Protocols: Services like Mixers, CoinJoin, and CoinShuffle combine user transactions to hide their origins.
 2.Stealth Addresses: One-time addresses that hide the recipient's identity, used in privacy coins like Monero.
c.Zero-Knowledge Proofs (ZKPs):
 1.Concept: Allow one party to prove knowledge of something without revealing the information itself.
 2.Types: Include zk-SNARKs (used by Zcash) and Bulletproofs.
 3.Applications: Used for shielded transactions in privacy coins and for Layer-2 privacy with zk-Rollups.

3. Confidentiality (Hiding Data)
These methods protect the content of data and transactions.
a.Advanced Encryption:
 1.Homomorphic Encryption (HE): Allows for computation directly on encrypted data.
 2.Confidential Transactions (CT): A protocol that hides transaction amounts, notably used in Monero's RingCT.
b.Network Privacy:
 1.Techniques like VPNs and TOR create encrypted channels to protect data in transit.

4. Identity & Governance
This area covers how digital identities are managed and the rules that govern them.
1.Identity Models: Can be centralized, decentralized, or distributed (DID).
a.Credentials & Verification:
1.Types: Can be knowledge-based (passwords), possession-based (tokens), or inherence-based (biometrics)
 2.Roles: The system involves an Issuer (gives credentials), a Holder (owns credentials), and a Verifier (checks credentials).
b.Oversight:
 1.Governance: Involves roles like the CISO (Chief Information Security Officer) and adherence to standards from bodies like NIST.
