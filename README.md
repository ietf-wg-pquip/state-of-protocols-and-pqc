_Statuses last checked against the IETF Datatracker on 2026-11-10._

# Protocol-independent algorithm or cryptography specifications

| Draft title | Status | Link | Working Group and/or protocol | Topic | Comments |
|------------ |------- |----- |------------------------------ |------ |--------- |
| Additional Parameter Sets for HSS/LMS Hash-Based Signatures | RFC 9858 | <https://datatracker.ietf.org/doc/rfc9858/> | CFRG | Parameter sets for the LMS signature primitive | |
| Combiner function for hybrid key encapsulation mechanisms (Hybrid KEMs) | Expired | <https://datatracker.ietf.org/doc/draft-ounsworth-cfrg-kem-combiners/> | CFRG | | This draft led to the CFRG call for the area of hybrid combiners |
| X-Wing: general-purpose hybrid post-quantum KEM | Active individual draft | <https://datatracker.ietf.org/doc/draft-connolly-cfrg-xwing-kem/> | CFRG | | Datatracker stream state: Submission Received |
| Hybrid PQ/T Key Encapsulation Mechanisms | Active RG draft (waiting for shepherd) | <https://datatracker.ietf.org/doc/draft-irtf-cfrg-hybrid-kems/> | CFRG | Generic constructions (combiners) for hybrid PQ/T KEMs | Outcome of the CFRG work on hybrid combiners |
| Concrete Hybrid PQ/T Key Encapsulation Mechanisms | Active RG draft (waiting for shepherd) | <https://datatracker.ietf.org/doc/draft-irtf-cfrg-concrete-hybrid-kems/> | CFRG | Concrete instantiations of the hybrid KEM constructions | |
| Kemeleon Encodings | Active RG draft | <https://datatracker.ietf.org/doc/draft-irtf-cfrg-kemeleon/> | CFRG | Encodings of ML-KEM public keys and ciphertexts that are indistinguishable from random | |
| Classic McEliece | Active individual draft | <https://datatracker.ietf.org/doc/draft-josefsson-mceliece/> | CFRG | Specification of the Classic McEliece KEM | Transcription of the ISO Classic McEliece standard. See also draft-josefsson-cfrg-mceliece-considerations |
| FrodoKEM: key encapsulation from learning with errors | Active individual draft | <https://datatracker.ietf.org/doc/draft-longa-cfrg-frodokem/> | CFRG | Specification of the FrodoKEM KEM | See also draft-longa-cfrg-frodokem-security-considerations |
| ML-KEM Security Considerations | Active individual draft | <https://datatracker.ietf.org/doc/draft-sfluhrer-cfrg-ml-kem-security-considerations/> | CFRG | Guidance on using ML-KEM securely | |
| Hybrid Post-Quantum Password Authenticated Key Exchange | Active individual draft | <https://datatracker.ietf.org/doc/draft-vos-cfrg-pqpake/> | CFRG | Hybrid PQ PAKE | |
| Hybrid Streamlined NTRU Prime sntrup761 and X25519 with SHA-512: Chempat-X | Expired | <https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-hybrid/> | Independent / CFRG | Hybrids of Streamlined NTRU Prime with X25519 | |
| Leighton-Micali Hash-Based Signatures | RFC | <https://www.rfc-editor.org/rfc/rfc8554> | CFRG | | RFC | 
| Streamlined NTRU Prime: sntrup761 | Expired | <https://datatracker.ietf.org/doc/draft-josefsson-ntruprime-streamlined/> | Independent / CFRG | Streamlined NTRU Prime KEM | |
| NTRU Key Encapsulation | Expired | <https://datatracker.ietf.org/doc/draft-fluhrer-cfrg-ntru/> | CFRG | Description of the NTRU algorithm | See also [NTRU KEM Security Considerations](https://datatracker.ietf.org/doc/draft-kosuge-cfrg-ntru-kem-security-considerations/) |
| X25519Kyber768Draft00 hybrid post-quantum KEM for HPKE | Expired | <https://datatracker.ietf.org/doc/draft-westerbaan-cfrg-hpke-xyber768d00/> | CFRG | Adds Kyber support (as a hybrid with X25519) to HPKE RFC 9180 | This was for the NIST Round 3 Draft version of Kyber for prototyping |
| XMSS: eXtended Merkle Signature Scheme | RFC | <https://www.rfc-editor.org/rfc/rfc8391> | CFRG | | RFC | 
| Merkle Tree Ladder Mode (MTL) Signatures | Expired | <https://datatracker.ietf.org/doc/draft-harvey-cfrg-mtl-mode/> | CFRG / DNS | Amortize large PQ signatures across a large evolving series of messages | |



# PQC support in protocols and migration techniques

## General

Protocols and working groups with only one or two entries.

| WG / Protocol | Draft title | Status | Link | Topic | Comments |
|------------ |------- |----- |------------------------------ |------ |--------- |
| ACME | ACME PQC Algorithm Negotiation | Expired | <https://datatracker.ietf.org/doc/draft-giron-acme-pqcnegotiation/> | Adds algorithm negotiation to ACME, including adding KEM PoP mechanisms | From on-list discussion, unclear whether ACME actually benefits from this. |
| ACME | Quantum-Ready ACME Mechanism | Active individual draft | <https://datatracker.ietf.org/doc/draft-ar-acme-pqc-tlsjws/> | Updates RFC 8555: PQ or PQ/T hybrid TLS 1.3 key establishment, and PQ or PQ/T authentication for JWS and TLS | |
| DKIM | Post-Quantum Cryptography in DKIM | Active individual draft | <https://datatracker.ietf.org/doc/draft-buck-dkim-pq-dkim1/> | Suitable PQ signature algorithms for DKIM, added as a separate signature alongside the traditional one | |
| HPKE | Post-Quantum and Post-Quantum/Traditional Hybrid Algorithms for HPKE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-hpke-pq/> | PQ and PQ/T hybrid KEMs for HPKE, plus a SHA-3 based KDF | |
| HPKE | Hamming Quasi-Cyclic (HQC) Key Encapsulation Mechanisms for HPKE | Active individual draft | <https://datatracker.ietf.org/doc/draft-reddy-hpke-hqc/> | HQC for HPKE | |
| KITTEN / Kerberos | Post-quantum Key Encapsulation with ML-KEM in PKINIT | Adopted by KITTEN WG | <https://datatracker.ietf.org/doc/draft-bokovoy-kitten-pkinit-pqc/> | ML-KEM (and other KEMs) in Kerberos PKINIT | |
| LAKE / EDHOC | Quantum-Resistant Cipher Suites for LAKE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lake-pqsuites/> | PQ cipher suites (ML-KEM, ML-DSA) for EDHOC | Also renames EDHOC to LAKE |
| LAKE / EDHOC | KEM-based Authentication for EDHOC | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lake-authkem-edhoc/> | KEM-based authentication for EDHOC | |
| OpenPGP | Post-Quantum Cryptography in OpenPGP | RFC 9980 | <https://datatracker.ietf.org/doc/rfc9980/> | Post-Quantum public-key algorithm extension for the OpenPGP protocol | |
| OpenPGP | PQ/T Composite Schemes for OpenPGP using NIST and Brainpool Elliptic Curve Domain Parameters | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-openpgp-nist-bp-comp/> | ML-KEM and ML-DSA composites with NIST and Brainpool curves | Complements RFC 9980 |
| SIDROPS / RPKI | Post-Quantum Authentication for the Resource Public Key Infrastructure | Active individual draft | <https://datatracker.ietf.org/doc/draft-li-sidrops-pqrpki/> | Additive PQ authentication layer: one PQ signature per CA over a Merkle Tree Ladder of its Manifest | See also draft-yoshikawa-sidrops-pqc-rpki |
| UTA | Post-Quantum Cryptography Recommendations for TLS-based Applications | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-uta-pqc-app/> | Guidance for applications using TLS on adopting PQC | |

## COSE / JOSE

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| COSE Key and JSON Web Key Representation for Key Encapsulation Mechanism (KEM) of Hybrid Public Key Encryption (HPKE) | Expired | <https://datatracker.ietf.org/doc/draft-ajitomi-cose-cose-key-jwk-hpke-kem/> | KEM wrapper for COSE | |
| COSE Kyber | Expired | <https://datatracker.ietf.org/doc/draft-steele-cose-kyber/> | Defines encoding and registry for Kyber | |
| JOSE and COSE Encoding for Post-Quantum Signatures | Expired | <https://datatracker.ietf.org/doc/draft-ietf-cose-post-quantum-signatures/> | JSON and CBOR serializations for several Post-Quantum Cryptography (PQC) based suites including CRYSTALS Dilithium, Falcon, and SPHINCS+. | No longer current, Split into one draft per signature suite - see relevant COSE items below |
| ML-DSA for JSON Object Signing and Encryption (JOSE) and CBOR Object Signing and Encryption (COSE) | RFC 9964 | <https://datatracker.ietf.org/doc/rfc9964/> | ML-DSA in COSE/JOSE | Was draft-ietf-cose-dilithium |
| FN-DSA for JOSE and COSE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-cose-falcon/> | FN-DSA (Falcon) in COSE/JOSE | |
| SLH-DSA for JOSE and COSE | In IESG Review (AD Evaluation) | <https://datatracker.ietf.org/doc/draft-ietf-cose-sphincs-plus/> | SLH-DSA in COSE/JOSE | |
| COSE HPKE PQ & PQ/T Algorithm Registrations | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-cose-hpke-pq-pqt/> | HPKE PQ and PQ/T hybrid KEMs in COSE | Replaces draft-reddy-cose-jose-pqc-hybrid-hpke (split into COSE and JOSE documents) |
| Post-Quantum Key Encapsulation Mechanisms (PQ KEMs) for COSE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-cose-pqc-kem/> | PQ KEMs in COSE | Replaces draft-ietf-jose-pqc-kem (moved from JOSE to COSE) |
| PQ/T Hybrid Composite Signatures for JOSE and COSE | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-jose-pq-composite-sigs/> | Composite ML-DSA in COSE/JOSE | JOSE WG document |
| Use of the HSS/LMS Hash-Based Signature Algorithm with CBOR Object Signing and Encryption (COSE) | RFC | <https://datatracker.ietf.org/doc/rfc8778/> | HSS / LMS in COSE | |
| Hybrid key exchange in JOSE and COSE | Expired | <https://datatracker.ietf.org/doc/draft-ra-cose-hybrid-encrypt/> | Using KEM combiners to compute Hybrid (PQC + Traditional) shared secret| |

## DNSOP (DNSSEC)

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| Stateful Hash-based Signatures For DNSSEC | Expired | <https://datatracker.ietf.org/doc/draft-afrvrd-dnsop-stateful-hbs-for-dnssec/> | Stateful Hash-based Signatures For DNSSEC | | 
| Module-Lattice Digital Signature Algorithm for DNSSEC | Active individual draft | <https://datatracker.ietf.org/doc/draft-westerbaan-dnssec-mldsa/> | ML-DSA for DNSSEC | |
| Module-Lattice-Based Signatures with Merkle Tree Ladders (ML-DSA-MTL) for DNSSEC | Active individual draft | <https://datatracker.ietf.org/doc/draft-kaizer-dnsop-ml-dsa-mtl-dnssec/> | ML-DSA-44 with Merkle Tree Ladders for DNSSEC | See MTL mode above |
| Considerations for Selecting Post-Quantum Algorithms for DNSSEC | Active individual draft | <https://datatracker.ietf.org/doc/draft-hoffman-pq-dnssec-considerations/> | Considerations for choosing PQ DNSSEC algorithms | Not intended to become an RFC |

## EMU (EAP)

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| Post-Quantum Enhancements to TLS-Based EAP Methods | Active WG draft (WG consensus, waiting for write-up) | <https://datatracker.ietf.org/doc/draft-ietf-emu-pqc-eap-tls/> | PQC in EAP-TLS and other TLS-based EAP methods | |
| Post-Quantum Key Encapsulation Mechanisms (PQ KEMs) in EAP-AKA prime | Active WG draft (waiting for WG chair go-ahead) | <https://datatracker.ietf.org/doc/draft-ietf-emu-pqc-eapaka/> | PQ KEMs in EAP-AKA' FS | |
| Enhancing Security in EAP-AKA' with Hybrid Post-Quantum Cryptography | Active WG draft (waiting for WG chair go-ahead) | <https://datatracker.ietf.org/doc/draft-ietf-emu-hybrid-pqc-eapaka/> | PQ/T hybrid KEMs in EAP-AKA' FS | |

## IPSECME (IPsec / IKEv2)

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| Post-quantum Key Exchange with ML-KEM in the Internet Key Exchange Protocol Version 2 (IKEv2) | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-mlkem/> | ML-KEM for IKEv2, optionally as a PQ/T hybrid via additional key exchanges | Replaces draft-kampanakis-ml-kem-ikev2 |
| Signature Authentication in the Internet Key Exchange Version 2 (IKEv2) using PQC | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-pqc-auth/> | ML-DSA and SLH-DSA authentication in IKEv2 without changes to existing IKE operations | Replaces draft-reddy-ipsecme-ikev2-pqc-auth |
| Post-Quantum Traditional (PQ/T) Hybrid PKI Authentication in IKEv2 | Active Individual draft | <https://datatracker.ietf.org/doc/draft-hu-ipsecme-pqt-hybrid-auth/> | Allows PQ/T hybrid auth either via composite certificates, or multiple certificates| |
| Post-quantum Key Exchange in IKEv2 with FrodoKEM | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-hybrid-kem-ikev2-frodo/> | FrodoKEM for IKEv2 | Replaces draft-wang-hybrid-kem-ikev2-frodo |
| Use of Composite Signatures in IKEv2 | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-pq-hybrid-auth/> | Composite ML-DSA authentication in IKEv2 | |
| Post-Quantum Key Exchange with HQC in IKEv2 | Active individual draft | <https://datatracker.ietf.org/doc/draft-reddy-ipsecme-ikev2-hqc/> | HQC for IKEv2 | |

## LAMPS (X.509 / CMS)

### X.509

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| Use of the HSS and XMSS Hash-Based Signature Algorithms in Internet X.509 Public Key Infrastructure | RFC 9802 | <https://datatracker.ietf.org/doc/rfc9802/> | OIDs for HSS/LMS and XMSS for use in PKIX | |
| Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Stateless Hash-Based Digital Signature Algorithm (SLH-DSA) | RFC 9909 | <https://datatracker.ietf.org/doc/rfc9909/> | SLH-DSA in X.509 certificates | |
| Algorithm Identifiers for NIST's PQC Algorithms for Use in the Internet X.509 Public Key Infrastructure | Expired | <https://datatracker.ietf.org/doc/draft-turner-lamps-nist-pqc-kem-certificates/> | | |
| Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Module-Lattice-Based Digital Signature Algorithm (ML-DSA) | RFC 9881 | <https://datatracker.ietf.org/doc/rfc9881/> | ML-DSA in X.509 certificates | |
| Internet X.509 Public Key Infrastructure - Algorithm Identifiers for the Module-Lattice-Based Key-Encapsulation Mechanism (ML-KEM) | RFC 9935 | <https://datatracker.ietf.org/doc/rfc9935/> | ML-KEM in X.509 certificates | |
| Composite Module-Lattice-Based Digital Signature Algorithm (ML-DSA) for Use in X.509 Public Key Infrastructure | RFC 10073 | <https://datatracker.ietf.org/doc/rfc10073/> | Composite public and private keys and signatures | |
| Composite ML-KEM for use in X.509 Public Key Infrastructure | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-lamps-pq-composite-kem/> | Composite public and private keys and encryption | |
| Internet X.509 Public Key Infrastructure -- Algorithm Identifiers for the Fast-Fourier Transform over NTRU-Lattice-Based Digital Signature Algorithm (FN-DSA) | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-fn-dsa-certificates/> | FN-DSA in X.509 certificates | |
| Internet X.509 Public Key Infrastructure - Algorithm Identifiers for FrodoKEM | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-frodokem-certificates/> | FrodoKEM in X.509 certificates | |
| Deprecating Expanded ML-DSA and ML-KEM Private Key Encodings | Active individual draft | <https://datatracker.ietf.org/doc/draft-rosomakho-lamps-mldsa-mlkem-seed-only/> | Require seed-only private keys for ML-DSA and ML-KEM interchange | Updates RFC 9881 and RFC 9935 |

### CMS

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| Use of ML-KEM in the Cryptographic Message Syntax (CMS) | RFC 9936 | <https://datatracker.ietf.org/doc/rfc9936/> | | |
| Use of the ML-DSA Signature Algorithm in the Cryptographic Message Syntax (CMS) | RFC 9882 | <https://datatracker.ietf.org/doc/rfc9882/> | | |
| Composite Module-Lattice-Based Digital Signature Algorithm (ML-DSA) for Use in the Cryptographic Message Syntax (CMS) | RFC 10082 | <https://datatracker.ietf.org/doc/rfc10082/> | | |
| Composite ML-KEM for use in Cryptographic Message Syntax (CMS) | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-composite-kem/> | | |
| Use of the FN-DSA Signature Algorithm in the Cryptographic Message Syntax (CMS) | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-fn-dsa/> | | |
| Use of FrodoKEM in the Cryptographic Message Syntax | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-frodokem/> | | |
| Use of the HSS/LMS Hash-Based Signature Algorithm in the Cryptographic Message Syntax (CMS) | RFC | <https://www.rfc-editor.org/rfc/rfc8708.html> | | | 
| Use of the SLH-DSA Signature Algorithm in the Cryptographic Message Syntax (CMS) | RFC 9814 | <https://datatracker.ietf.org/doc/rfc9814/> | | |

## MLS

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| MLS Ciphersuite using X-Wing KEM | Replaced | <https://datatracker.ietf.org/doc/draft-mahy-mls-xwing/> | X-Wing for MLS | Replaced by draft-mahy-mls-pq, which became draft-ietf-mls-pq-ciphersuites |
| Amortized PQ MLS Combiner | Expired WG draft | <https://datatracker.ietf.org/doc/draft-ietf-mls-combiner/> | Combines traditional MLS session with a PQ session | Replaces draft-hale-mls-combiner |
| ML-KEM and Hybrid Cipher Suites for Messaging Layer Security | In IESG Review (Publication Requested) | <https://datatracker.ietf.org/doc/draft-ietf-mls-pq-ciphersuites/> | Post-quantum KEM Cipher Suites | |

## SSHM (SSH)

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| Post-Quantum/Traditional Hybrid Key Exchange with the Module-Lattice-Based Key-Encapsulation Mechanism for Use in SSH | RFC 10042 | <https://datatracker.ietf.org/doc/rfc10042/> | mlkem768x25519-sha256, mlkem768nistp256-sha256, mlkem1024nistp384-sha384 | Was draft-ietf-sshm-mlkem-hybrid-kex; replaces draft-kampanakis-curdle-ssh-pq-ke |
| Secure Shell (SSH) Key Exchange Method Using Hybrid Streamlined NTRU Prime sntrup761 and X25519 with SHA-512: sntrup761x25519-sha512 | RFC 9941 | <https://datatracker.ietf.org/doc/rfc9941/> | Hybrid of Streamlined NTRU Prime sntrup761 and X25519 | Supported in OpenSSH. Details in see [OpenSSH implementation of `sntrup761x25519-sha512@openssh.com`](https://www.openssh.com/txt/release-9.0)  |
| Post-Quantum Composite Signatures in SSH | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-sshm-composite-sigs/> | Composite ML-DSA with Ed25519 or ECDSA for SSH | |
| SSH Support of ML-DSA | Active individual draft | <https://datatracker.ietf.org/doc/draft-sfluhrer-ssh-mldsa/> | ML-DSA signatures in SSH | Updates RFC 4253 |

## TLS

| Draft title | Status | Link | Topic | Comments |
|------- |----- |------------------------------ |------ |--------- |
| KEM-based Authentication for TLS 1.3 | Active individual draft | <https://datatracker.ietf.org/doc/draft-celi-wiggers-tls-authkem/> | KEM-based authentication | |
| ML-KEM Post-Quantum Key Agreement for TLS 1.3 | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-tls-mlkem/> | Adds (non-hybrid) ML-KEM to TLS | Replaces draft-connolly-tls-mlkem-key-agreement |
| X25519Kyber768Draft00 hybrid post-quantum key agreement | Expired | <https://datatracker.ietf.org/doc/draft-tls-westerbaan-xyber768d00> | X25519Kyber768 for TLS 1.3. | Instantiation of draft-ietf-tls-hybrid-design. This was for the NIST Round 3 Draft version of Kyber for prototyping |
| Post-Quantum Traditional (PQ/T) Hybrid Key Agreement Mechanisms for TLS 1.3 | RFC 10024 | <https://datatracker.ietf.org/doc/rfc10024/> | X25519MLKEM768, SecP256r1MLKEM768, and SecP384r1MLKEM1024 | Was draft-ietf-tls-ecdhe-mlkem; replaces draft-kwiatkowski-tls-ecdhe-mlkem and X25519Kyber768Draft00 |
| SecP256r1Kyber768Draft00 hybrid post-quantum key agreement | Expired | <https://datatracker.ietf.org/doc/draft-kwiatkowski-tls-ecdhe-kyber/> | ECDHE-Kyber for TLS 1.3. | Instantiation of draft-ietf-tls-hybrid-design |
| Post-Quantum Guidance for TLS | Expired | <https://datatracker.ietf.org/doc/draft-farrell-tls-pqg/> | Recommendations for deploying PQC in TLS | Recommends hybrid KEMs, and no action yet for signatures |
| Use of ML-DSA in TLS 1.3 | In RFC Editor queue | <https://datatracker.ietf.org/doc/draft-ietf-tls-mldsa/> | | Replaces draft-tls-westerbaan-mldsa |
| Use of Composite ML-DSA in TLS 1.3 | Active WG draft | <https://datatracker.ietf.org/doc/draft-ietf-tls-composite-mldsa/> | | Replaces draft-reddy-tls-composite-mldsa |
| Use of SLH-DSA in TLS 1.3 | Expired | <https://datatracker.ietf.org/doc/draft-reddy-tls-slhdsa/> | | |
| KEM-based pre-shared-key handshakes for TLS 1.3 | Active individual draft | <https://datatracker.ietf.org/doc/draft-wiggers-tls-authkem-psk/> | Long-term KEM public keys in place of symmetric PSKs | Inspired by AuthKEM, but can be implemented independently |
| HQC-KEM Key Agreement for TLS 1.3 | Active individual draft | <https://datatracker.ietf.org/doc/draft-preussmattsson-tls-hqckem/> | HQC for TLS | |
| Post-Quantum Hybrid ML-KEM-1024/X448 Key Agreement for TLS 1.3 | Active individual draft | <https://datatracker.ietf.org/doc/draft-preussmattsson-tls-mlkem1024-x448/> | X448MLKEM1024 | |
| Post-Quantum Traditional (PQ/T) Hybrid Authentication with Dual Certificates in TLS 1.3 | Active individual draft | <https://datatracker.ietf.org/doc/draft-yusef-tls-pqt-dual-certs/> | Non-composite hybrid authentication with two certificates | |
| PQC Continuity: Downgrade Protection for TLS Servers Migrating to PQC | Active individual draft | <https://datatracker.ietf.org/doc/draft-sheffer-tls-pqc-continuity/> | Prevents downgrade to traditional authentication | |


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
| TLS Trust Anchor Identifiers | <https://datatracker.ietf.org/doc/draft-ietf-tls-trust-anchor-ids/> | TLS | Lets a TLS client or server select a certificate based on the peer's trusted CAs, more succinctly than the Certificate Authorities extension | Adopted by WG |
| Merkle Tree Certificates Deployment Use Cases | <https://datatracker.ietf.org/doc/draft-ietf-plants-mtc-deploy-use-cases/> | PLANTS | Deployment scenarios for Merkle Tree Certificates | Adopted by WG |
| PKCS #8: Private-Key Information Content Types | <https://datatracker.ietf.org/doc/rfc9939/> | LAMPS | Content types for carrying private keys, including PQ private keys | RFC 9939 |
| Hash-Based Signatures: State and Backup Management | <https://datatracker.ietf.org/doc/rfc10033/> | PQUIP | Operational guidance for stateful hash-based signatures (LMS/HSS, XMSS) | RFC 10033 |
| Adapting Constrained Devices for Post-Quantum Cryptography | <https://datatracker.ietf.org/doc/draft-ietf-pquip-pqc-hsm-constrained/> | PQUIP | PQC on constrained devices and HSMs | In IESG Evaluation |


# Algorithm names

NIST published the final versions of [FIPS 203](https://csrc.nist.gov/pubs/fips/203/final) (ML-KEM, formerly Kyber), [FIPS 204](https://csrc.nist.gov/pubs/fips/204/final) (ML-DSA, formerly Dilithium) and [FIPS 205](https://csrc.nist.gov/pubs/fips/205/final) (SLH-DSA, formerly SPHINCS+) in August 2024. FN-DSA (formerly Falcon) will be specified in FIPS 206. In March 2025 NIST [selected HQC](https://csrc.nist.gov/News/2025/hqc-announced-as-a-4th-round-selection) as an additional KEM. IETF documents should use the final FIPS names (ML-KEM, ML-DSA, SLH-DSA, FN-DSA).

Historical note: before the FIPS were final, the IETF used the following convention to distinguish versions, using Dilithium -> ML-DSA as an example. Older drafts in the tables above may still use these names.

* _**Dilithium_round1/2/3**_ -- "as submitted to round 1, 2, or 3 of the NIST PQC competition". "Dilithium" is a short-hand for "Dilithium_round3".
* _**ML-DSA-ipd**_ -- FIPS 204 Initial Public Draft (e.g. _**ML-DSA-ipd-44**_ for a specific parameter set).
* _**ML-DSA**_ -- final FIPS 204.


# Implementations and interop testing for these specs

The following is an informal list of implementations of the RFCs and drafts above. This list also is for sites that have interoperability reports for implementations

- [IETF Hackathon - PQC Certificates](https://github.com/IETF-Hackathon/pqc-certificates)
- [IETF PQC Hackathon Interoperability Results](https://ietf-hackathon.github.io/pqc-certificates/)

This is an appropriate place to list interop events and hackathons that relate to PQC algorithms.


# Security Area protocols with no PQC-specific action needed

This table lists IETF Security Area protocols with "no action needed", typically because that protocol does not itself specify any cryptographic algorithms but instead embeds other IETF cryptographic protocols. Therefore no action is needed for that protocol because it will inherit PQC as soon as its cryptographic dependencies support it.

| Protocol | RFC       | Working Group  | Cryptographic dependencies | Comment |
|--------- |---------- |--------------- |--------------------------- |-------- |
| ACME     | <https://datatracker.ietf.org/doc/rfc8555/>   | ACME           | PKCS #10 (RFC 2986), JOSE/JWS (RFC 7515), TLS (RFC 8446) | |
| CMC      | <https://datatracker.ietf.org/doc/rfc10002/>  | LAMPS          | CMS (RFC 5652), PKCS #10 (RFC 2986) | RFC 10002 obsoletes RFC 5272 |
| QUIC     | <https://datatracker.ietf.org/doc/rfc9000/>   | QUIC           | TLS 1.3 (RFC 8446)          | QUIC is pretty specific to TLS 1.3, so probably needs an update in lockstep with each TLS update |
| DoH      | <https://datatracker.ietf.org/doc/rfc8484/>   | DOH            | TLS (RFC 8446)              |         |
| EST      | <https://datatracker.ietf.org/doc/rfc7030/>   | LAMPS          | CMC (RFC 5272), CMS (RFC 5652), PKCS #10 (RFC 2986), TLS (RFC 8446) |         |
| HTTPS    | <https://datatracker.ietf.org/doc/rfc9110/>   | HTTPbis       | TLS (RFC 8446)              |         |
| SCEP     | <https://datatracker.ietf.org/doc/rfc8894/>   | LAMPS (?)      | CMS (RFC 5652), PKCS #10 (RFC 2986) |  |
| S/MIME   | <https://datatracker.ietf.org/doc/rfc8551/>   | LAMPS        | CMS (RFC 5652)               | RFC 8551 obsoletes RFC 5751. Its algorithm requirements are being revised in [draft-ietf-lamps-rfc8551bis](https://datatracker.ietf.org/doc/draft-ietf-lamps-rfc8551bis/), which is the place to add PQC algorithms. |

# Other Security protocols with no PQC-specific action needed
This table lists IETF Security protocols with "no action needed", typically because that protocol does not itself specify any cryptographic algorithms but instead embeds other IETF cryptographic protocols. Therefore no action is needed for that protocol because it will inherit PQC as soon as its cryptographic dependencies support it. 

| Protocol | RFC       | Working Group  | Cryptographic dependencies | Comment |
|--------- |---------- |--------------- |--------------------------- |-------- |
| SRTP     | <https://datatracker.ietf.org/doc/rfc3711/> | AVT | DTLS (RFC 9147) | KEX handled by DTLS (RFC 5763/5764), Symmetric key AEAD (AES-GCM) algos available for actual SRTP (RFC 7714) |

# Suggestions for possible additions

The lists above can contain protocols and proposals from other standards organizations, such as IEEE, ETSI, and so on.
