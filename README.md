# Protocol-independent algorithm or cryptography specifications

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| Additional Parameter sets for LMS Hash-Based Signatures | <https://datatracker.ietf.org/doc/draft-fluhrer-lms-more-parm-sets/> | CFRG | Parameter sets for the LMS signature primitive | |
| Combiner function for hybrid key encapsulation mechanisms (Hybrid KEMs) | <https://datatracker.ietf.org/doc/draft-ounsworth-cfrg-kem-combiners/> | CFRG | | |
| X-Wing: general-purpose hybrid post-quantum KEM | <https://datatracker.ietf.org/doc/draft-connolly-cfrg-xwing-kem//> | CFRG | | |
| Hybrid Streamlined NTRU Prime sntrup761 and X25519 with SHA-512 | <https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-hybrid/> | Intependent / CFRG | Hybrids of Streamlined NTRU Prime with X25519 | |
| Kyber Post-Quantum KEM | <https://datatracker.ietf.org/doc/draft-cfrg-schwabe-kyber/> | CFRG | Description of the Kyber algorithm | |
| Leighton-Micali Hash-Based Signatures | <https://www.rfc-editor.org/rfc/rfc8554> | CFRG | | RFC | 
| Streamlined NTRU Prime: sntrup761 | <https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-streamlined/> | Independent / CFRG | Streamlined NTRU Prime KEM | |
| NTRU Key Encapsulation | <https://datatracker.ietf.org/doc/draft-fluhrer-cfrg-ntru/> | CFRG | Description of the NTRU algorithm | |
| Quantum Safe Cryptography Key Information for CRYSTALS-Kyber | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-kyber/> | Individual | Kyber encodings | |
| Quantum Safe Cryptography Key Information for CRYSTALS-Dilithium | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-dilithium/> | Individual | Dilithium encodings | |
| Quantum Safe Cryptography Key Information for FALCON | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-falcon/> | Individual | FALCON encodings | |
| Quantum Safe Cryptography Key Information for SPHINCS-PLUS | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-sphincsplus/> | Individual | SPHINCS+ encodings | | |
| X25519Kyber768Draft00 hybrid post-quantum KEM for HPKE | <https://datatracker.ietf.org/doc/draft-westerbaan-cfrg-hpke-xyber768d00/> | CFRG | Adds Kyber support (as a hybrid with X25519) to HPKE RFC 9180 | |
| XMSS: eXtended Merkle Signature Scheme | <https://www.rfc-editor.org/rfc/rfc8391> | CFRG | | RFC | 


# PQC support in protocols and migration techniques

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| ACME PQC Algorithm Negotiation | <https://datatracker.ietf.org/doc/draft-giron-acme-pqcnegotiation/> | ACME | Adds algorithm negotiation to ACME, including adding KEM PoP mechanisms | From on-list discussion, unclear whether ACME actually benefits from this. |
| COSE Key and JSON Web Key Representation for Key Encapsulation Mechanism (KEM) of Hybrid Public Key Encryption (HPKE) | <https://datatracker.ietf.org/doc/draft-ajitomi-cose-cose-key-jwk-hpke-kem/> | COSE | KEM wrapper for COSE | |
| COSE Kyber | <https://datatracker.ietf.org/doc/draft-steele-cose-kyber/> | COSE | Defines encoding and registry for Kyber | 
| JOSE and COSE Encoding for Post-Quantum Signatures | <https://datatracker.ietf.org/doc/draft-ietf-cose-post-quantum-signatures/> | COSE | JSON and CBOR serializations for several Post-Quantum Cryptography (PQC) based suites including CRYSTALS Dilithium, Falcon, and SPHINCS+. | No longer current, Split into one draft per signature suite - see relevant COSE items below |
| JOSE and COSE Encoding for Dilithium | <https://datatracker.ietf.org/doc/draft-ietf-cose-dilithium> | COSE | Dilithium in COSE/JOSE | |
| JOSE and COSE Encoding for Falcon | <https://datatracker.ietf.org/doc/draft-ietf-cose-falcon> | COSE | FALCON in COSE/JOSE | |
| JOSE and COSE Encoding for SPHINCS+ | <https://datatracker.ietf.org/doc/draft-ietf-cose-sphincs-plus> | COSE | SHPINCS+ in COSE/JOSE | |
| Post-Quantum Key Encapsulation Mechanisms (PQ KEMs) for JOSE and COSE | <https://datatracker.ietf.org/doc/draft-reddy-cose-jose-pqc-kem/> | Individual | ML-KEM in COSE/JOSE | |
| PQ/T Hybrid KEM: HPKE with JOSE/COSE | <https://datatracker.ietf.org/doc/draft-reddy-cose-jose-pqc-hybrid-hpke/> | Individual | HPKE PQ/T Hybrids in COSE/JOSE | | 
| Use of the HSS/LMS Hash-Based Signature Algorithm with CBOR Object Signing and Encryption (COSE) | <https://datatracker.ietf.org/doc/rfc8778/> | COSE | HSS / LMS in COSE | RFC |
| Hybrid key exchange in JOSE and COSE | <https://datatracker.ietf.org/doc/draft-ra-cose-hybrid-encrypt/> | COSE | Using KEM combiners to compute Hybrid (PQC + Traditional) shared secret| |
| Stateful Hash-based Signatures For DNSSEC | <https://datatracker.ietf.org/doc/draft-afrvrd-dnsop-stateful-hbs-for-dnssec/> | Individual | Stateful Hash-based Signatures For DNSSEC | Expired draft | 
| Algorithm Identifiers for Hash-based Signatures for Use in the Internet X.509 Public Key Infrastructure | <https://datatracker.ietf.org/doc/draft-gazdag-x509-hash-sigs/> | LAMPS | OIDs for HSS/LMS, XMSS, SPHINCS+ for use in PKIX | |
| Algorithm Identifiers for NIST's PQC Algorithms for Use in the Internet X.509 Public Key Infrastructure | <https://datatracker.ietf.org/doc/draft-turner-lamps-nist-pqc-kem-certificates/> | LAMPS | | Expired draft |
| Composite ML-DSA for use in Internet PKI | <https://datatracker.ietf.org/doc/draft-ietf-lamps-pq-composite-sigs/> | LAMPS | Composite public and private keys and signatures | | 
| Composite ML-KEM for Use in the Internet X.509 Public Key Infrastructure and CMS | <https://datatracker.ietf.org/doc/draft-ietf-lamps-pq-composite-kem//> | LAMPS | Composite public and private keys and encryption | | 
| Internet X.509 Public Key Infrastructure - Algorithm Identifiers for Kyber | <https://datatracker.ietf.org/doc/draft-ietf-lamps-kyber-certificates/> | LAMPS | Republishing NIST OIDs and specifying Kyber encoding | |
| Use of KYBER in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-kyber/> | LAMPS | | |
| Use of Post-Quantum KEM in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-perret-prat-lamps-cms-pq-kem/> | LAMPS | | |
| Use of the HSS/LMS Hash-Based Signature Algorithm in the Cryptographic Message Syntax (CMS)| <https://www.rfc-editor.org/rfc/rfc8708.html> | LAMPS | | RFC | 
| Use of the SPHINCS+ Signature Algorithm in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-sphincs-plus/> | LAMPS | | |
| Internet X.509 Public Key Infrastructure: Algorithm Identifiers for Dilithium | <https://datatracker.ietf.org/doc/draft-ietf-lamps-dilithium-certificates/> | LAMPS | Dilithium quantum-resistant signatures in Internet X.509 certificates | |
| Messaging Layer Security | <https://www.rfc-editor.org/rfc/rfc9420> | MLS | Native support for KEM | RFC |
| Post-Quantum Cryptography in OpenPGP | <draft-ietf-openpgp-pqc/> | OpenPGP | Post-Quantum public-key algorithm extension for the OpenPGP protocol | |
| KEM-based Authentication for TLS 1.3 | <https://datatracker.ietf.org/doc/draft-celi-wiggers-tls-authkem/> | TLS | KEM-based authentication | Expired draft | 
| X25519Kyber768Draft00 hybrid post-quantum key agreement | <https://datatracker.ietf.org/doc/draft-tls-westerbaan-xyber768d00> | TLS | X25519Kyber768 for TLS 1.3. | Instantiation of draft-ietf-tls-hybrid-design |
| Post-quantum Hybrid Key Exchange in SSH | <https://datatracker.ietf.org/doc/draft-kampanakis-curdle-ssh-pq-ke> | SSH | P256/384/521 or X25519 with Kyber | Supported in OQS OpenSSH, wolfSSH, AWS Transfer Family. Details in [blog](https://aws.amazon.com/blogs/security/post-quantum-hybrid-sftp-file-transfers-using-aws-transfer-family/) |
| | <https://datatracker.ietf.org/doc/html/draft-josefsson-ntruprime-ssh> | SSH | NTRU with Kyber | Supported in OpenSSH. Details in see [OpenSSH implementation of `sntrup761x25519-sha512@openssh.com`](https://www.openssh.com/txt/release-9.0)  |
| SecP256r1Kyber768Draft00 hybrid post-quantum key agreement | <https://datatracker.ietf.org/doc/draft-kwiatkowski-tls-ecdhe-kyber/> | TLS | ECDHE-Kyber for TLS 1.3. | Instantiation of draft-ietf-tls-hybrid-design |
| MLS Ciphersuite using X25519Kyber768Draft00 KEM | <https://datatracker.ietf.org/doc/draft-mahy-mls-x25519kyber768draft00/> | MLS | X25519Kyber768 for MLS | based on KEM in <https://datatracker.ietf.org/doc/draft-westerbaan-cfrg-hpke-xyber768d00/> |
| Post-quantum Hybrid Key Exchange with ML-KEM in the Internet Key Exchange Protocol Version 2 (IKEv2) | <https://datatracker.ietf.org/doc/draft-kampanakis-ml-kem-ikev2/> | IPSECME | ML-KEM for IKEv2 | |


# Improvements adjacent to PQC

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| Handling Large Certificates and Long Certificate Chains in TLS‑Based EAP Methods | <https://datatracker.ietf.org/doc/rfc9191/> | EMU | Explores problems and solutions related to large PQC certificates in EAP | RFC |
| A Larger Internet Key Exchange version 2 (IKEv2) Payload  | <https://datatracker.ietf.org/doc/draft-nir-ipsecme-big-payload/> | IPSECME | Increase payload size to handle PQC keys | |
| Alternative Approach for Mixing Preshared Keys in IKEv2 for Post-quantum Security | <https://datatracker.ietf.org/doc/draft-smyslov-ipsecme-ikev2-qr-alt/> | IPSECME | | | 
| Announcing Supported Authentication Methods in IKEv2 | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-auth-announce/> | IPSECME | Allows IKEv2 implementations to indicate the list of supported authentication methods | |
| Hybrid Non-Composite Authentication in IKEv2 | <https://datatracker.ietf.org/doc/draft-guthrie-ipsecme-ikev2-hybrid-auth/> | IPSECME | Non-composite hybrid authentication for IKEv2 | Expired 2022-09-26 |
| Intermediate Exchange in the Internet Key Exchange Protocol Version 2 (IKEv2) | <https://datatracker.ietf.org/doc/rfc9242/> | IPSECME | Defines a new "Intermediate Exchange" to handle large amounts of data is SA establishment to handle PQC keys | RFC |
| Internet Key Exchange Protocol Version 2 (IKEv2) Message Fragmentation | <https://datatracker.ietf.org/doc/rfc7383/> | IPSECME | Packet fragmentation on larger packets to handle PQC keys | RFC |
| Using Pre-Shared Key (PSK) in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/rfc8696/> | LAMPS | Use PSK in CMS to be quantum safe | RFC |
| External Keys And Signatures For Use In Internet PKI | <https://datatracker.ietf.org/doc/html/draft-ounsworth-lamps-pq-external-pubkeys> | LAMPS | A mechanism for an X.509 certificate to contain a link and hash of the public key instead of the entire object | |
| TLS 1.3 Extension for Certificate-Based Authentication with an External Pre-Shared Key | <https://datatracker.ietf.org/doc/rfc8773/> | TLS | Use PSK in TLS 1.3 to be quantum safe | RFC |
| Mixing Preshared Keys in the Internet Key Exchange Protocol Version 2 (IKEv2) for Post-quantum Security | <https://datatracker.ietf.org/doc/rfc8784/> | IPSECME | | RFC |
| Multiple Key Exchanges in IKEv2 | <https://datatracker.ietf.org/doc/rfc9370/> | IPSECME | Defines multiple (hybrid) key exchange, with applications to PQ among other things | RFC |
| Non-Composite Hybrid Authentication in PKIX and Applications to Internet Protocols | <https://datatracker.ietf.org/doc/draft-becker-guthrie-noncomposite-hybrid-auth/> | LAMPS | Non-composite hybrid authentication for X.509 | Expired 2022-09-26 | 
| Related Certificates for Use in Multiple Authentications within a Protocol | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cert-binding-for-multi-auth/> | LAMPS | Bind certs across non-composite parallel PKIs | |
| Hybrid key exchange in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-ietf-tls-hybrid-design/> | TLS | Hybrid TLS key exchange | Adopted by WG |
| Suppressing CA Certificates in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-kampanakis-tls-scas-latest/> | TLS | TLS authentication and certificate chain | |
| Terminology for Post-Quantum Traditional Hybrid Schemes | <https://datatracker.ietf.org/doc/draft-driscoll-pqt-hybrid-terminology/> | PQUIP | | |
| Post-Quantum Cryptography for Engineers | <https://datatracker.ietf.org/doc/draft-ietf-pquip-pqc-engineers/> | PQUIP | This document explains why engineers need to be aware of and understand post-quantum cryptography | Adopted by the WG |
| Quantum Relief with TLS and Kerberos | <https://datatracker.ietf.org/doc/draft-vanrein-tls-kdh/> | Individual | Kerberos-over-TLS. | Unclear that this is directly PQC-related |
| Using Key Encapsulation Mechanism (KEM) Algorithms in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-kemri/> | LAMPS | Adds KEMRecipientInfo to CMS, to enable PQ KEMs | Adopted by WG |
| A Mechanism for Encoding Differences in Paired Certificates | <https://datatracker.ietf.org/doc/draft-bonnell-lamps-chameleon-certs/> | LAMPS | | |
| Merkle Tree Certificates for TLS | <https://datatracker.ietf.org/doc/draft-davidben-tls-merkle-tree-certs/> | TLS | New certificate type for use with a transparency service with reduced size compared to PQ signatures | |
| Merkle Tree Ladder Mode (MTL) Signatures | <https://datatracker.ietf.org/doc/draft-harvey-cfrg-mtl-mode/> | CFRG | Amortize large PQ signatures across a large evolving series of messages | |
| Internet X.509 Public Key Infrastructure -- Certificate Management Protocol (CMP) | <https://datatracker.ietf.org/doc/draft-ietf-lamps-rfc4210bis/> | LAMPS | rfc4210bis, plus adds support for KEM certificates | Adopted by WG |
| A Hybrid Signature Method with Strong Non-Separability | <https://datatracker.ietf.org/doc/draft-nir-lamps-altcompsigs/> | LAMPS | An alternative scheme of composing classic and post-quantum signature algorithms with different security properties. | |
| Hybrid signature spectrums | <https://datatracker.ietf.org/doc/draft-hale-pquip-hybrid-signature-spectrums/> | PQUIP | Classification of design goals and security considerations for hybrid digital signature schemes | |
| Post-quantum cryptography use cases | <https://datatracker.ietf.org/doc/draft-vaira-pquip-pqc-use-cases/> | PQUIP | PQ use cases and migration strategies | |


# Algorithm names

The first round of "winners" of the [NIST PQC competition](https://csrc.nist.gov/Projects/post-quantum-cryptography) are Dilithium, Falcon, SPHINCS+, and Kyber. As of August 23, 2023 with the publication of the Initial Public Drafts of FIPS 203, 204, and 205 we know that Dilithium is being renamed to "ML-DSA" (Module Lattice), SPHINCS+ to "SLH-DSA" (StateLess Hash), and Kyber to "ML-KEM (Module Lattice).

However, the community wants to avoid the situation where we over-eagerly adopt the new names, then see a compatibility-breaking change in a future iteration of the FIPS draft standards, and then have multiple non-compatible algorithms with the same name. 

The IETF will use the following naming convention to refer to different versions of the NIST PQC candidate algorithms; using Dilithium -> ML-DSA as an example:

* _**Dilithium_round1/2/3**_ -- means “as submitted to round 1, 2, or 3 of the NIST PQC competition”. “Dilithium” is a short-hand for "Dilithium_round3".

* _**ML-DSA-ipd**_ – FIPS 204 Initial Public Draft. Note this matches the PDF file name:
https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.204.ipd.pdf. For protocols that define a separate algorithm identifier per parameter set, it is encouraged to append the parameter ID to this string to form the string describing the algorithm identifier, e.g.,  _**ML-DSA-ipd-44**_.

* _**ML-DSA**_ – reserved for final FIPS 204.

The equivalent names are applied to Falcon, SPHINCS+, and Kyber.

As well, similar naming conventions would apply to other NIST PQC such as Classic McEliece, HQC, Bike which are progressing through Round 4, as well as to new algorithms that come from the 2nd call for signature algorithms.


# Implementations and interop testing for these specs

The following is an informal list of implementations of the RFCs and drafts above. This list also is for sites that have interoperability reports for implementations

- [IETF Hackathon - PQC Certificates](https://github.com/IETF-Hackathon/pqc-certificates)
- [IETF PQC Hackathon Interoperability Results](https://ietf-hackathon.github.io/pqc-certificates/pqc_hackathon_results_certs_r3.html)

This is an appropriate place to list interop events and hackathons that relate to PQC algorithms.


# Security Area protocols with no PQC-specific action needed

This table lists IETF Security Area protocols with "no action needed", typically because that protocol does not itself specify any cryptographic algorithms but instead embeds other IETF cryptographic protocols. Therefore no action is needed for that protocol because it will inherit PQC as soon as its cryptographic dependencies support it.

| Protocol | RFC       | Working Group  | Cryptographic dependencies | Comment |
|--------- |---------- |--------------- |--------------------------- |-------- |
| ACME     | <https://datatracker.ietf.org/doc/rfc8555/>   | ACME           | PKCS #10 (RFC 2986), JOSE/JWS (RFC 7515), TLS (RFC 8446) | |
| CMC      | <https://datatracker.ietf.org/doc/rfc5272/>   | LAMPS          | CMS (RFC 5652), PKCS #10 (RFC 2986) |         |
| QUIC     | <https://datatracker.ietf.org/doc/rfc9000/>   | QUIC           | TLS 1.3 (RFC 8446)          | QUIC is pretty specific to TLS 1.3, so probably needs an update in lockstep with each TLS update |
| DoH      | <https://datatracker.ietf.org/doc/rfc8484/>   | DPRIVE         | TLS (RFC 8446)              |         |
| EST      | <https://datatracker.ietf.org/doc/rfc7030/>   | LAMPS          | CMC (RFC 5272), CMS (RFC 5652), PKCS #10 (RFC 2986), TLS (RFC 8446) |         |
| HTTPS    | <https://datatracker.ietf.org/doc/rfc9110/>   | HTTPbis       | TLS (RFC 8446)
| SCEP     | <https://datatracker.ietf.org/doc/rfc8894/>   | LAMPS (?)      | CMS (RFC 5652), PKCS #10 (RFC 2986) |  |
| S/MIME   | <https://datatracker.ietf.org/doc/rfc5751/>   | LAMPS        | CMS (RFC 5652)               | Section 4.1 explicitly lists RSA, DSA, SHA-1. So maybe this needs an update to only modern non-PQC crypto. |

# Other Security protocols with no PQC-specific action needed
This table lists IETF Security protocols with "no action needed", typically because that protocol does not itself specify any cryptographic algorithms but instead embeds other IETF cryptographic protocols. Therefore no action is needed for that protocol because it will inherit PQC as soon as its cryptographic dependencies support it. 

| Protocol | RFC       | Working Group  | Cryptographic dependencies | Comment |
|--------- |---------- |--------------- |--------------------------- |-------- |
| SRTP     | <https://datatracker.ietf.org/doc/rfc3711/> | AVT | DTLS (RFC 9147) | KEX handled by DTLS (RFC 5763/5764), Symmetric key AEAD (AES-GCM) algos available for actual SRTP (RFC 7714) |

# Suggestions for possible additions

The lists above can contain protocols and proposals from other standards organizations, such as IEEE, ETSI, and so on.

