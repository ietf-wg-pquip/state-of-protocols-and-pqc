# Protocol-independent algorithm or cryptography specifications

| Draft title | Status | Link | Working Group and/or protocol | Topic | Comments |
|------------ |------- |----- |------------------------------ |------ |--------- |
| Additional Parameter Sets for HSS/LMS Hash-Based Signatures | RFC 9858 | <https://datatracker.ietf.org/doc/rfc9858/> | CFRG | Parameter sets for the LMS signature primitive | |
| Combiner function for hybrid key encapsulation mechanisms (Hybrid KEMs) | Expired | <https://datatracker.ietf.org/doc/draft-ounsworth-cfrg-kem-combiners/> | CFRG | | This draft led to the CFRG call for the area of hybrid combiners |
| X-Wing: general-purpose hybrid post-quantum KEM | Active individual draft | <https://datatracker.ietf.org/doc/draft-connolly-cfrg-xwing-kem/> | CFRG / ISE | | Submitted to the Independent Submissions stream |
| Hybrid PQ/T Key Encapsulation Mechanisms | Active RG draft (waiting for shepherd) | <https://datatracker.ietf.org/doc/draft-irtf-cfrg-hybrid-kems/> | CFRG | Generic constructions (combiners) for hybrid PQ/T KEMs | Outcome of the CFRG work on hybrid combiners |
| Concrete Hybrid PQ/T Key Encapsulation Mechanisms | Active RG draft (waiting for shepherd) | <https://datatracker.ietf.org/doc/draft-irtf-cfrg-concrete-hybrid-kems/> | CFRG | Concrete instantiations of the hybrid KEM constructions | |
| Kemeleon Encodings | Active RG draft | <https://datatracker.ietf.org/doc/draft-irtf-cfrg-kemeleon/> | CFRG | Encodings of ML-KEM public keys and ciphertexts that are indistinguishable from random | |
| Hybrid Streamlined NTRU Prime sntrup761 and X25519 with SHA-512: Chempat-X | Expired | <https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-hybrid/> | Independent / CFRG | Hybrids of Streamlined NTRU Prime with X25519 | |
| Kyber Post-Quantum KEM | Expired | <https://datatracker.ietf.org/doc/draft-cfrg-schwabe-kyber/> | CFRG | Description of the Kyber algorithm | No longer needed now that FIPS 203 exists |
| Leighton-Micali Hash-Based Signatures | RFC | <https://www.rfc-editor.org/rfc/rfc8554> | CFRG | | RFC | 
| Streamlined NTRU Prime: sntrup761 | Expired | <https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-streamlined/> | Independent / CFRG | Streamlined NTRU Prime KEM | |
| NTRU Key Encapsulation | Expired | <https://datatracker.ietf.org/doc/draft-fluhrer-cfrg-ntru/> | CFRG | Description of the NTRU algorithm | See also [NTRU KEM Security Considerations](https://datatracker.ietf.org/doc/draft-kosuge-cfrg-ntru-kem-security-considerations/) |
| Quantum Safe Cryptography Key Information for CRYSTALS-Kyber | Expired | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-kyber/> | Individual | Kyber encodings | No longer needed now that the FIPS standards exist |
| Quantum Safe Cryptography Key Information for CRYSTALS-Dilithium | Expired | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-dilithium/> | Individual | Dilithium encodings | No longer needed now that the FIPS standards exist |
| Quantum Safe Cryptography Key Information for FALCON | Expired | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-falcon/> | Individual | FALCON encodings | No longer needed now that the FIPS standards exist |
| Quantum Safe Cryptography Key Information for SPHINCS-PLUS | Expired | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-sphincsplus/> | Individual | SPHINCS+ encodings | No longer needed now that the FIPS standards exist |
| X25519Kyber768Draft00 hybrid post-quantum KEM for HPKE | Expired | <https://datatracker.ietf.org/doc/draft-westerbaan-cfrg-hpke-xyber768d00/> | CFRG | Adds Kyber support (as a hybrid with X25519) to HPKE RFC 9180 | This was for the NIST Round 3 Draft version of Kyber for prototyping |
| XMSS: eXtended Merkle Signature Scheme | RFC | <https://www.rfc-editor.org/rfc/rfc8391> | CFRG | | RFC | 
| Merkle Tree Ladder Mode (MTL) Signatures | Expired | <https://datatracker.ietf.org/doc/draft-harvey-cfrg-mtl-mode/> | CFRG / DNS | Amortize large PQ signatures across a large evolving series of messages | |



# PQC support in protocols and migration techniques

| WG / Protocol | Draft title | Status | Link | Topic | Comments |
|------------ |------- |----- |------------------------------ |------ |--------- |
| ACME | ACME PQC Algorithm Negotiation | Expired | <https://datatracker.ietf.org/doc/draft-giron-acme-pqcnegotiation/> | Adds algorithm negotiation to ACME, including adding KEM PoP mechanisms | From on-list discussion, unclear whether ACME actually benefits from this. |
| COSE | COSE Key and JSON Web Key Representation for Key Encapsulation Mechanism (KEM) of Hybrid Public Key Encryption (HPKE) | Expired | <https://datatracker.ietf.org/doc/draft-ajitomi-cose-cose-key-jwk-hpke-kem/> | KEM wrapper for COSE | |
| COSE | COSE Kyber | Expired | <https://datatracker.ietf.org/doc/draft-steele-cose-kyber/> | Defines encoding and registry for Kyber | |
| COSE | JOSE and COSE Encoding for Post-Quantum Signatures | Expired | <https://datatracker.ietf.org/doc/draft-ietf-cose-post-quantum-signatures/> | JSON and CBOR serializations for several Post-Quantum Cryptography (PQC) based suites including CRYSTALS Dilithium, Falcon, and SPHINCS+. | No longer current, Split into one draft per signature suite - see relevant COSE items below |
| COSE | ML-DSA for JSON Object Signing and Encryption (JOSE) and CBOR Object Signing and Encryption (COSE) | RFC 9964 | <https://datatracker.ietf.org/doc/rfc9964/> | ML-DSA in COSE/JOSE | Was draft-ietf-cose-dilithium |
| COSE | FN-DSA for JOSE and COSE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-cose-falcon/> | FN-DSA (Falcon) in COSE/JOSE | |
| COSE | SLH-DSA for JOSE and COSE | In IESG Review (AD Evaluation) | <https://datatracker.ietf.org/doc/draft-ietf-cose-sphincs-plus/> | SLH-DSA in COSE/JOSE | |
| COSE | COSE HPKE PQ & PQ/T Algorithm Registrations | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-cose-hpke-pq-pqt/> | HPKE PQ and PQ/T hybrid KEMs in COSE | Replaces draft-reddy-cose-jose-pqc-hybrid-hpke (split into COSE and JOSE documents) |
| COSE | Post-Quantum Key Encapsulation Mechanisms (PQ KEMs) for COSE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-cose-pqc-kem/> | ML-KEM in COSE | Replaces draft-ietf-jose-pqc-kem (moved from JOSE to COSE) |
| COSE / JOSE | PQ/T Hybrid Composite Signatures for JOSE and COSE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-jose-pq-composite-sigs/> | Composite ML-DSA in COSE/JOSE | JOSE WG document |
| COSE | Use of the HSS/LMS Hash-Based Signature Algorithm with CBOR Object Signing and Encryption (COSE) | RFC | <https://datatracker.ietf.org/doc/rfc8778/> | HSS / LMS in COSE | |
| COSE | Hybrid key exchange in JOSE and COSE | Expired | <https://datatracker.ietf.org/doc/draft-ra-cose-hybrid-encrypt/> | Using KEM combiners to compute Hybrid (PQC + Traditional) shared secret| |
| DNSOP | Stateful Hash-based Signatures For DNSSEC | Expired | <https://datatracker.ietf.org/doc/draft-afrvrd-dnsop-stateful-hbs-for-dnssec/> | Stateful Hash-based Signatures For DNSSEC | | 
| EMU / EAP | Post-Quantum Enhancements to TLS-Based EAP Methods | Active WG draft (WG consensus, waiting for write-up) | <https://datatracker.ietf.org/doc/draft-ietf-emu-pqc-eap-tls/> | PQC in EAP-TLS and other TLS-based EAP methods | |
| EMU / EAP | Post-Quantum Key Encapsulation Mechanisms (PQ KEMs) in EAP-AKA prime | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-emu-pqc-eapaka/> | ML-KEM in EAP-AKA' | |
| EMU / EAP | Enhancing Security in EAP-AKA' with Hybrid Post-Quantum Cryptography | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-emu-hybrid-pqc-eapaka/> | Hybrid PQ/T key exchange in EAP-AKA' | |
| HPKE | Post-Quantum and Post-Quantum/Traditional Hybrid Algorithms for HPKE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-hpke-pq/> | ML-KEM and hybrid KEMs for HPKE | Supersedes the X25519Kyber768Draft00 HPKE draft |
| IPSECME / IPsec / IKEv2 | Post-quantum Key Exchange with ML-KEM in the Internet Key Exchange Protocol Version 2 (IKEv2) | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-mlkem/> | ML-KEM for IKEv2, optionally as a PQ/T hybrid via additional key exchanges | Replaces draft-kampanakis-ml-kem-ikev2 |
| IPSECME / IPsec / IKEv2 | Signature Authentication in the Internet Key Exchange Version 2 (IKEv2) using PQC | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-pqc-auth/> | ML-DSA and SLH-DSA authentication in IKEv2 without changes to existing IKE operations | Replaces draft-reddy-ipsecme-ikev2-pqc-auth |
| IPSECME / IPsec / IKEv2 | Post-Quantum Traditional (PQ/T) Hybrid PKI Authentication in IKEv2 | Active Individual draft | <https://datatracker.ietf.org/doc/draft-hu-ipsecme-pqt-hybrid-auth/> | Allows PQ/T hybrid auth either via composite certificates, or multiple certificates| |
| IPSECME / IPsec / IKEv2 | Post-quantum Key Exchange in IKEv2 with FrodoKEM | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-hybrid-kem-ikev2-frodo/> | FrodoKEM for IKEv2 | Replaces draft-wang-hybrid-kem-ikev2-frodo |
| IPSECME / IPsec / IKEv2 | Use of Composite Signatures in IKEv2 | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-pq-hybrid-auth/> | Composite ML-DSA authentication in IKEv2 | |
| LAKE / EDHOC | Quantum-Resistant Cipher Suites for LAKE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lake-pqsuites/> | PQ cipher suites for EDHOC | |
| LAKE / EDHOC | KEM-based Authentication for EDHOC | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lake-authkem-edhoc/> | KEM-based authentication for EDHOC | |
| LAMPS / X.509 | Use of the HSS and XMSS Hash-Based Signature Algorithms in Internet X.509 Public Key Infrastructure | RFC 9802 | <https://datatracker.ietf.org/doc/rfc9802/> | OIDs for HSS/LMS and XMSS for use in PKIX | |
| LAMPS / X.509 | Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Stateless Hash-Based Digital Signature Algorithm (SLH-DSA) | RFC 9909 | <https://datatracker.ietf.org/doc/rfc9909/> | SLH-DSA in X.509 certificates | |
| LAMPS / X.509 | Algorithm Identifiers for NIST's PQC Algorithms for Use in the Internet X.509 Public Key Infrastructure | Expired | <https://datatracker.ietf.org/doc/draft-turner-lamps-nist-pqc-kem-certificates/> | | |
| LAMPS / X.509 | Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Module-Lattice-Based Digital Signature Algorithm (ML-DSA) | RFC 9881 | <https://datatracker.ietf.org/doc/rfc9881/> | ML-DSA in X.509 certificates | |
| LAMPS / X.509 | Internet X.509 Public Key Infrastructure - Algorithm Identifiers for the Module-Lattice-Based Key-Encapsulation Mechanism (ML-KEM) | RFC 9935 | <https://datatracker.ietf.org/doc/rfc9935/> | ML-KEM in X.509 certificates | |
| LAMPS / X.509 | Composite Module-Lattice-Based Digital Signature Algorithm (ML-DSA) for Use in X.509 Public Key Infrastructure | RFC 10073 | <https://datatracker.ietf.org/doc/rfc10073/> | Composite public and private keys and signatures | |
| LAMPS / X.509 | Composite ML-KEM for use in X.509 Public Key Infrastructure | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-lamps-pq-composite-kem/> | Composite public and private keys and encryption | |
| LAMPS / X.509 | Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Fast-Fourier Transform over NTRU-Lattice-Based Digital Signature Algorithm (FN-DSA) | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-fn-dsa-certificates/> | FN-DSA in X.509 certificates | |
| LAMPS / X.509 | Internet X.509 Public Key Infrastructure - Algorithm Identifiers for FrodoKEM | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-frodokem-certificates/> | FrodoKEM in X.509 certificates | |
| LAMPS / CMS | Use of ML-KEM in the Cryptographic Message Syntax (CMS) | RFC 9936 | <https://datatracker.ietf.org/doc/rfc9936/> | | |
| LAMPS / CMS | Use of the ML-DSA Signature Algorithm in the Cryptographic Message Syntax (CMS) | RFC 9882 | <https://datatracker.ietf.org/doc/rfc9882/> | | |
| LAMPS / CMS | Composite Module-Lattice-Based Digital Signature Algorithm (ML-DSA) for Use in the Cryptographic Message Syntax (CMS) | RFC 10082 | <https://datatracker.ietf.org/doc/rfc10082/> | | |
| LAMPS / CMS | Composite ML-KEM for use in Cryptographic Message Syntax (CMS) | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-composite-kem/> | | |
| LAMPS / CMS | Use of the FN-DSA Signature Algorithm in the Cryptographic Message Syntax (CMS) | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-fn-dsa/> | | |
| LAMPS / CMS | Use of FrodoKEM in the Cryptographic Message Syntax | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-frodokem/> | | |
| LAMPS / CMS | Use of the HSS/LMS Hash-Based Signature Algorithm in the Cryptographic Message Syntax (CMS) | RFC | <https://www.rfc-editor.org/rfc/rfc8708.html> | | | 
| LAMPS / CMS | Use of the SLH-DSA Signature Algorithm in the Cryptographic Message Syntax (CMS) | RFC 9814 | <https://datatracker.ietf.org/doc/rfc9814/> | | |
| MLS | MLS Ciphersuite using X-Wing KEM | Replaced | <https://datatracker.ietf.org/doc/draft-mahy-mls-xwing/> | X-Wing for MLS | Replaced by draft-mahy-mls-pq, which became draft-ietf-mls-pq-ciphersuites |
| MLS | Amortized PQ MLS Combiner | Expired WG draft | <https://datatracker.ietf.org/doc/draft-ietf-mls-combiner/> | Combines traditional MLS session with a PQ session | Replaces draft-hale-mls-combiner |
| MLS | ML-KEM and Hybrid Cipher Suites for Messaging Layer Security | In IESG Review (Publication Requested) | <https://datatracker.ietf.org/doc/draft-ietf-mls-pq-ciphersuites/> | Post-quantum KEM Cipher Suites | |
| OpenPGP | Post-Quantum Cryptography in OpenPGP | RFC 9980 | <https://datatracker.ietf.org/doc/rfc9980/> | Post-Quantum public-key algorithm extension for the OpenPGP protocol | |
| OpenPGP | PQ/T Composite Schemes for OpenPGP using NIST and Brainpool Elliptic Curve Domain Parameters | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-openpgp-nist-bp-comp/> | ML-KEM and ML-DSA composites with NIST and Brainpool curves | Complements RFC 9980 |
| SSH | Post-Quantum/Traditional Hybrid Key Exchange with the Module-Lattice-Based Key-Encapsulation Mechanism for Use in SSH | RFC 10042 | <https://datatracker.ietf.org/doc/rfc10042/> | mlkem768x25519-sha256, mlkem768nistp256-sha256, mlkem1024nistp384-sha384 | Was draft-ietf-sshm-mlkem-hybrid-kex; replaces draft-kampanakis-curdle-ssh-pq-ke |
| SSH | Secure Shell (SSH) Key Exchange Method Using Hybrid Streamlined NTRU Prime sntrup761 and X25519 with SHA-512: sntrup761x25519-sha512 | RFC 9941 | <https://datatracker.ietf.org/doc/rfc9941/> | Hybrid of Streamlined NTRU Prime sntrup761 and X25519 | Supported in OpenSSH. Details in see [OpenSSH implementation of `sntrup761x25519-sha512@openssh.com`](https://www.openssh.com/txt/release-9.0)  |
| SSH | Post-Quantum Composite Signatures in SSH | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-sshm-composite-sigs/> | Composite ML-DSA host and user keys for SSH | |
| TLS | KEM-based Authentication for TLS 1.3 | Active individual draft | <https://datatracker.ietf.org/doc/draft-celi-wiggers-tls-authkem/> | KEM-based authentication | |
| TLS | ML-KEM Post-Quantum Key Agreement for TLS 1.3 | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-tls-mlkem/> | Adds (non-hybrid) ML-KEM to TLS | Replaces draft-connolly-tls-mlkem-key-agreement |
| TLS | X25519Kyber768Draft00 hybrid post-quantum key agreement | Expired | <https://datatracker.ietf.org/doc/draft-tls-westerbaan-xyber768d00> | X25519Kyber768 for TLS 1.3. | Instantiation of draft-ietf-tls-hybrid-design. This was for the NIST Round 3 Draft version of Kyber for prototyping |
| TLS | Post-Quantum Traditional (PQ/T) Hybrid Key Agreement Mechanisms for TLS 1.3 | RFC 10024 | <https://datatracker.ietf.org/doc/rfc10024/> | X25519MLKEM768, SecP256r1MLKEM768, and SecP384r1MLKEM1024 | Was draft-ietf-tls-ecdhe-mlkem; replaces draft-kwiatkowski-tls-ecdhe-mlkem and X25519Kyber768Draft00 |
| TLS | SecP256r1Kyber768Draft00 hybrid post-quantum key agreement | Expired | <https://datatracker.ietf.org/doc/draft-kwiatkowski-tls-ecdhe-kyber/> | ECDHE-Kyber for TLS 1.3. | Instantiation of draft-ietf-tls-hybrid-design |
| TLS | Post-Quantum Guidance for TLS | Expired | <https://datatracker.ietf.org/doc/draft-farrell-tls-pqg/> | Recommendations for deploying PQC in TLS | Recommends hybrid KEMs, and no action yet for signatures |
| TLS | Use of ML-DSA in TLS 1.3 | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-tls-mldsa/> | | Replaces draft-tls-westerbaan-mldsa |
| TLS | Use of Composite ML-DSA in TLS 1.3 | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-tls-composite-mldsa/> | | Replaces draft-reddy-tls-composite-mldsa |
| TLS | Use of SLH-DSA in TLS 1.3 | Expired | <https://datatracker.ietf.org/doc/draft-reddy-tls-slhdsa/> | | |
| UTA | Post-Quantum Cryptography Recommendations for TLS-based Applications | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-uta-pqc-app/> | Guidance for applications using TLS on adopting PQC | |


# Improvements adjacent to PQC

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| Handling Large Certificates and Long Certificate Chains in TLS‑Based EAP Methods | <https://datatracker.ietf.org/doc/rfc9191/> | EMU | Explores problems and solutions related to large PQC certificates in EAP | RFC |
| A Larger Internet Key Exchange version 2 (IKEv2) Payload | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-big-payload/> | IPSECME | Increase payload size to handle PQC keys | Adopted by WG; replaces draft-nir-ipsecme-big-payload |
| Mixing Preshared Keys in the IKE_INTERMEDIATE and CREATE_CHILD_SA Exchanges of IKEv2 for Post-Quantum Security | <https://datatracker.ietf.org/doc/rfc9867/> | IPSECME | Alternative approach for mixing PSKs in IKEv2 | RFC 9867; was draft-smyslov-ipsecme-ikev2-qr-alt |
| Announcing Supported Authentication Methods in the Internet Key Exchange Protocol Version 2 (IKEv2) | <https://datatracker.ietf.org/doc/rfc9593/> | IPSECME | Allows IKEv2 implementations to indicate the list of supported authentication methods | RFC 9593 |
| Hybrid Non-Composite Authentication in IKEv2 | <https://datatracker.ietf.org/doc/draft-guthrie-ipsecme-ikev2-hybrid-auth/> | IPSECME | Non-composite hybrid authentication for IKEv2 | Expired 2022-09-26 |
| Intermediate Exchange in the Internet Key Exchange Protocol Version 2 (IKEv2) | <https://datatracker.ietf.org/doc/rfc9242/> | IPSECME | Defines a new "Intermediate Exchange" to handle large amounts of data is SA establishment to handle PQC keys | RFC |
| Internet Key Exchange Protocol Version 2 (IKEv2) Message Fragmentation | <https://datatracker.ietf.org/doc/rfc7383/> | IPSECME | Packet fragmentation on larger packets to handle PQC keys | RFC |
| Using Pre-Shared Key (PSK) in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/rfc8696/> | LAMPS | Use PSK in CMS to be quantum safe | RFC |
| External Keys And Signatures For Use In Internet PKI | <https://datatracker.ietf.org/doc/draft-ounsworth-lamps-pq-external-pubkeys/> | LAMPS | A mechanism for an X.509 certificate to contain a link and hash of the public key instead of the entire object | Expired |
| TLS 1.3 Extension for Certificate-Based Authentication with an External Pre-Shared Key | <https://datatracker.ietf.org/doc/rfc8773/> | TLS | Use PSK in TLS 1.3 to be quantum safe | RFC |
| Mixing Preshared Keys in the Internet Key Exchange Protocol Version 2 (IKEv2) for Post-quantum Security | <https://datatracker.ietf.org/doc/rfc8784/> | IPSECME | | RFC |
| Multiple Key Exchanges in IKEv2 | <https://datatracker.ietf.org/doc/rfc9370/> | IPSECME | Defines multiple (hybrid) key exchange, with applications to PQ among other things | RFC |
| Non-Composite Hybrid Authentication in PKIX and Applications to Internet Protocols | <https://datatracker.ietf.org/doc/draft-becker-guthrie-noncomposite-hybrid-auth/> | LAMPS | Non-composite hybrid authentication for X.509 | Expired 2022-09-26 | 
| Related Certificates for Use in Multiple Authentications within a Protocol | <https://datatracker.ietf.org/doc/rfc9763/> | LAMPS | Bind certs across non-composite parallel PKIs | RFC 9763 |
| Hybrid Key Exchange in TLS 1.3 | <https://datatracker.ietf.org/doc/rfc9954/> | TLS | Hybrid TLS key exchange | RFC 9954 |
| Suppressing CA Certificates in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-kampanakis-tls-scas-latest/> | TLS | TLS authentication and certificate chain | Expired |
| Terminology for Post-Quantum Traditional Hybrid Schemes | <https://datatracker.ietf.org/doc/rfc9794/> | PQUIP | | RFC 9794 |
| Post-Quantum Cryptography for Engineers | <https://datatracker.ietf.org/doc/rfc9958/> | PQUIP | This document explains why engineers need to be aware of and understand post-quantum cryptography | RFC 9958 |
| Quantum Relief with TLS and Kerberos | <https://datatracker.ietf.org/doc/draft-vanrein-tls-kdh/> | Individual | Kerberos-over-TLS. | Expired. Unclear that this is directly PQC-related |
| Using Key Encapsulation Mechanism (KEM) Algorithms in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/rfc9629/> | LAMPS | Adds KEMRecipientInfo to CMS, to enable PQ KEMs | RFC 9629 |
| A Mechanism for Encoding Differences in Paired Certificates | <https://datatracker.ietf.org/doc/draft-bonnell-lamps-chameleon-certs/> | LAMPS | | Expired |
| Merkle Tree Certificates | <https://datatracker.ietf.org/doc/draft-ietf-plants-merkle-tree-certs/> | PLANTS | New certificate type for use with a transparency service with reduced size compared to PQ signatures | Adopted by the PLANTS WG; replaces draft-davidben-tls-merkle-tree-certs |
| Internet X.509 Public Key Infrastructure -- Certificate Management Protocol (CMP) | <https://datatracker.ietf.org/doc/rfc9810/> | LAMPS | rfc4210bis, plus adds support for KEM certificates | RFC 9810 |
| A Hybrid Signature Method with Strong Non-Separability | <https://datatracker.ietf.org/doc/draft-nir-lamps-altcompsigs/> | LAMPS | An alternative scheme of composing classic and post-quantum signature algorithms with different security properties. | Expired |
| Hybrid Signature Spectrums | <https://datatracker.ietf.org/doc/rfc9955/> | PQUIP | Classification of design goals and security considerations for hybrid digital signature schemes | RFC 9955 |
| Post-quantum cryptography use cases | <https://datatracker.ietf.org/doc/draft-vaira-pquip-pqc-use-cases/> | PQUIP | PQ use cases and migration strategies | Expired |
| TLS Key Share Prediction | <https://datatracker.ietf.org/doc/draft-ietf-tls-key-share-prediction/> | TLS | Server can advertize its keyshare preference in DNS to avoid retries caused by ClientHello pre-generating a keyshare for the wrong algorithm | Adopted by WG. This is considered PQC-adjacent because it will smooth the transition to ML-KEM |
| TLS Trust Anchor Identifiers | <https://datatracker.ietf.org/doc/draft-ietf-tls-trust-anchor-ids/> | TLS | Lets relying parties signal trusted CAs, enabling multiple (e.g. PQ and traditional) PKIs and smaller chains | Adopted by WG |
| Merkle Tree Certificates Deployment Use Cases | <https://datatracker.ietf.org/doc/draft-ietf-plants-mtc-deploy-use-cases/> | PLANTS | Deployment scenarios for Merkle Tree Certificates | Adopted by WG |
| PKCS #8: Private-Key Information Content Types | <https://datatracker.ietf.org/doc/rfc9939/> | LAMPS | Content types for carrying private keys, including PQ private keys | RFC 9939 |
| Hash-Based Signatures: State and Backup Management | <https://datatracker.ietf.org/doc/rfc10033/> | PQUIP | Operational guidance for stateful hash-based signatures (LMS/HSS, XMSS) | RFC 10033 |
| Adapting Constrained Devices for Post-Quantum Cryptography | <https://datatracker.ietf.org/doc/draft-ietf-pquip-pqc-hsm-constrained/> | PQUIP | PQC on constrained devices and HSMs | In IESG Evaluation |


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
| DoH      | <https://datatracker.ietf.org/doc/rfc8484/>   | DOH            | TLS (RFC 8446)              |         |
| EST      | <https://datatracker.ietf.org/doc/rfc7030/>   | LAMPS          | CMC (RFC 5272), CMS (RFC 5652), PKCS #10 (RFC 2986), TLS (RFC 8446) |         |
| HTTPS    | <https://datatracker.ietf.org/doc/rfc9110/>   | HTTPbis       | TLS (RFC 8446)              |         |
| SCEP     | <https://datatracker.ietf.org/doc/rfc8894/>   | LAMPS (?)      | CMS (RFC 5652), PKCS #10 (RFC 2986) |  |
| S/MIME   | <https://datatracker.ietf.org/doc/rfc5751/>   | LAMPS        | CMS (RFC 5652)               | Section 4.1 explicitly lists RSA, DSA, SHA-1. So maybe this needs an update to only modern non-PQC crypto. |

# Other Security protocols with no PQC-specific action needed
This table lists IETF Security protocols with "no action needed", typically because that protocol does not itself specify any cryptographic algorithms but instead embeds other IETF cryptographic protocols. Therefore no action is needed for that protocol because it will inherit PQC as soon as its cryptographic dependencies support it. 

| Protocol | RFC       | Working Group  | Cryptographic dependencies | Comment |
|--------- |---------- |--------------- |--------------------------- |-------- |
| SRTP     | <https://datatracker.ietf.org/doc/rfc3711/> | AVT | DTLS (RFC 9147) | KEX handled by DTLS (RFC 5763/5764), Symmetric key AEAD (AES-GCM) algos available for actual SRTP (RFC 7714) |

# Suggestions for possible additions

The lists above can contain protocols and proposals from other standards organizations, such as IEEE, ETSI, and so on.
