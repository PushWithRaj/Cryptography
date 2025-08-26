### Cryptography
Some details about Cryptography in Data Privacy
***
###1. Cryptography Fundamentals
This covers the basic building blocks of encryption and key management.
*Encryption Types:
 *Symmetric: Uses a single shared key (e.g., AES, 3DES).
 *Asymmetric: Uses public/private key pairs (e.g., RSA, ECC).
*Key Management:
 *Key Exchange: Securely establishes keys using protocols like Diffie-Hellman (DH/ECDH) and PAKE.
 *Infrastructure (PKI): Manages public keys and digital certificates.
 *Lifecycle: Includes key generation, distribution, storage, rotation, and revocation.
 *Hardware Security: Uses Hardware Security Modules (HSMs) for secure key storage.

2. Anonymity (Hiding Identity)
These techniques focus on concealing a user's identity and making their actions untraceable.
*Signature Schemes:
 *Ring Signatures: Allow a group member to sign anonymously; a larger "ring size" increases anonymity.
 *Other Types: Include Group, Blind, and Threshold signatures for different anonymity scenarios.
*Transaction Obscurity:
 *Mixing Protocols: Services like Mixers, CoinJoin, and CoinShuffle combine user transactions to hide their origins.
 *Stealth Addresses: One-time addresses that hide the recipient's identity, used in privacy coins like Monero.
*Zero-Knowledge Proofs (ZKPs):
 *Concept: Allow one party to prove knowledge of something without revealing the information itself.
 *Types: Include zk-SNARKs (used by Zcash) and Bulletproofs.
 *Applications: Used for shielded transactions in privacy coins and for Layer-2 privacy with zk-Rollups.

3. Confidentiality (Hiding Data)
These methods protect the content of data and transactions.
*Advanced Encryption:
 *Homomorphic Encryption (HE): Allows for computation directly on encrypted data.
 *Confidential Transactions (CT): A protocol that hides transaction amounts, notably used in Monero's RingCT.
*Network Privacy:
 *Techniques like VPNs and TOR create encrypted channels to protect data in transit.

4. Identity & Governance
This area covers how digital identities are managed and the rules that govern them.
*Identity Models: Can be centralized, decentralized, or distributed (DID).
*Credentials & Verification:
* Types: Can be knowledge-based (passwords), possession-based (tokens), or inherence-based (biometrics)
 *Roles: The system involves an Issuer (gives credentials), a Holder (owns credentials), and a Verifier (checks credentials).
*Oversight:
 *Governance: Involves roles like the CISO (Chief Information Security Officer) and adherence to standards from bodies like NIST.
