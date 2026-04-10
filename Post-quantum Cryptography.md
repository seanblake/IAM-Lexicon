Abbreviated as: [[PQC]]

Cryptographic systems which are [[Quantum resistant]] - i.e. not susceptible to attacks using [[Quantum computing]].

[[NIST]] has approved a number of [[Quantum resistant]] cryptographic algorithms for use in various applications, described in [[Federal Information Processing Standard]] publications:
- [FIPS 203: Module-Lattice-Based Key-Encapsulation Mechanism Standard](https://csrc.nist.gov/pubs/fips/203/final)
- [FIPS 204: Module-Lattice-Based Digital Signature Standard](https://csrc.nist.gov/pubs/fips/204/final)
- [FIPS 205: Stateless Hash-Based Digital Signature Standard](https://csrc.nist.gov/pubs/fips/205/final)

The [[Advanced Encryption Standard]] ([[AES]]) is a symmetric key cryptographic system widely used for encryption of data, and is already considered [[Quantum resistant]].  However, [[AES]] is commonly used along with other classical asymmetric key cryptographic systems (e.g. [[RSA]], [[DH]], [[DSA]], [[ECDSA]], [[ECDH]]) to exchange the symmetric key used for AES encryption/decryption between parties.  The susceptibility of these other systems to attacks using [[Quantum computing]], puts information encrypted using [[AES]] at risk since the symmetric keys used may be obtained by adversaries attacking the key exchange.
