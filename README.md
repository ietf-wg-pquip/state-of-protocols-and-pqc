# Protocol-independent Algorithm / Crypto Specifications

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| Additional Parameter sets for LMS Hash-Based Signatures | <https://datatracker.ietf.org/doc/draft-fluhrer-lms-more-parm-sets/> | CFRG | Paramater sets for the LMS signature primitive | |
| Combiner function for hybrid key encapsulation mechanisms (Hybrid KEMs) | <https://datatracker.ietf.org/doc/draft-ounsworth-cfrg-kem-combiners/> | CFRG | | |
| Kyber Post-Quantum KEM | <https://datatracker.ietf.org/doc/draft-cfrg-schwabe-kyber/> | CFRG | Description of the Kyber algorithm | |
| Leighton-Micali Hash-Based Signatures | <https://www.rfc-editor.org/rfc/rfc8554> | CFRG | | RFC | 
| NTRU Key Encapsulation | <https://datatracker.ietf.org/doc/draft-fluhrer-cfrg-ntru/> | CFRG | Description of the NTRU algorithm | |
| Quantum Safe Cryptography Key Information for CRYSTALS-Kyber | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-kyber/> | Individual | Kyber encodings | Conflicts / overlaps with draft-ietf-lamps-kyber-certificates and  |
| Quantum Safe Cryptography Key Information for CRYSTALS-Dilithium | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-dilithium/> | Individual | Dilithium encodings | Conflicts / overlaps with draft-ietf-lamps-dilithium-certificates and draft-steele-cose-kyber |
| Quantum Safe Cryptography Key Information for FALCON | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-falcon/> | Individual | FALCON encodings | Will conflict with equiv. drafts in LAMPS / COSE once they exist |
| Quantum Safe Cryptography Key Information for SPHINCS-PLUS | <https://datatracker.ietf.org/doc/draft-uni-qsckeys-sphincsplus/> | SPHINCS+ encodings | Conflicts / overlaps with draft-ietf-lamps-cms-sphincs-plus | |
| XMSS: eXtended Merkle Signature Scheme | <https://www.rfc-editor.org/rfc/rfc8391> | CFRG | | RFC | 



# PQC Support in Protocols and Migration Techniques

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| COSE Key and JSON Web Key Representation for Key Encapsulation Mechanism (KEM) of Hybrid Public Key Encryption (HPKE) | <https://datatracker.ietf.org/doc/draft-ajitomi-cose-cose-key-jwk-hpke-kem/> | COSE | KEM wrapper for COSE | |
| COSE Kyber | <https://datatracker.ietf.org/doc/draft-steele-cose-kyber/> | COSE | Defines encoding and registry for Kyber | 
| JOSE and COSE Encoding for Post-Quantum Signatures | https://datatracker.ietf.org/doc/draft-ietf-cose-post-quantum-signatures/ | COSE | JSON and CBOR serializations for several Post-Quantum Cryptography (PQC) based suites including CRYSTALS Dilithium, Falcon, and SPHINCS+. | |
| Use of the HSS/LMS Hash-Based Signature Algorithm with CBOR Object Signing and Encryption (COSE) | <https://datatracker.ietf.org/doc/rfc8778/> | COSE | HSS / LMS in COSE | RFC |
| Stateful Hash-based Signatures For DNSSEC | <https://datatracker.ietf.org/doc/draft-afrvrd-dnsop-stateful-hbs-for-dnssec/> | DNSOP | Stateful Hash-based Signatures For DNSSEC | Expired draft | 
| Algorithm Identifiers for Hash-based Signatures for Use in the Internet X.509 Public Key Infrastructure | <https://datatracker.ietf.org/doc/draft-gazdag-x509-hash-sigs/> | LAMPS | OIDs for HSS/LMS, XMSS, SPHINCS+ for use in PKIX | |
| Algorithm Identifiers for NIST's PQC Algorithms for Use in the Internet X.509 Public Key Infrastructure | <https://datatracker.ietf.org/doc/draft-turner-lamps-nist-pqc-kem-certificates/> | LAMPS | | Expired draft |
| Composite Signatures For Use In Internet PKI | <https://datatracker.ietf.org/doc/draft-ounsworth-pq-composite-sigs/> | LAMPS | Composite public and private keys and encryption | Expired draft | 
| Internet X.509 Public Key Infrastructure - Algorithm Identifiers for Kyber | <https://datatracker.ietf.org/doc/draft-ietf-lamps-kyber-certificates/> | LAMPS | Republishing NIST OIDs and specifying Kyber encoding | Conflicts / overlaps with draft-uni-qsckeys-kyber |
| Use of KYBER in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-ietf-lamps-kyber/> | LAMPS | | |
| Use of the HSS/LMS Hash-Based Signature Algorithm in the Cryptographic Message Syntax (CMS)| <https://www.rfc-editor.org/rfc/rfc8708.html> | LAMPS | |RFC | 
| Use of the SPHINCS+ Signature Algorithm in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cms-sphincs-plus/> | LAMPS | | |
| Internet X.509 Public Key Infrastructure: Algorithm Identifiers for Dilithium | <https://datatracker.ietf.org/doc/draft-ietf-lamps-dilithium-certificates/> | LAMPS | Dilithium quantum-resistant signatures in Internet X.509 certificates | Conflicts / overlaps with draft-uni-qsckeys-dilithium |
| Post-Quantum Cryptography in OpenPGP | <https://datatracker.ietf.org/doc/draft-wussler-openpgp-pqc/> | OPENPGP | Post-Quantum public-key algorithm extension for the OpenPGP protocol | |
| KEM-based Authentication for TLS 1.3 | <https://datatracker.ietf.org/doc/draft-celi-wiggers-tls-authkem/> | TLS | KEM-based authentication | Expired draft | 
| Post-quantum Hybrid Key Exchange in SSH | <https://datatracker.ietf.org/doc/draft-kampanakis-curdle-ssh-pq-ke/> | SSH | | |



# PQC-Adjacent Improvements

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| Handling Large Certificates and Long Certificate Chains in TLS‑Based EAP Methods | <https://datatracker.ietf.org/doc/rfc9191/> | EMU | Explores problems and solutions related to large PQC certificates in EAP | RFC |
| A Larger Internet Key Exchange version 2 (IKEv2) Payload  | <https://datatracker.ietf.org/doc/draft-nir-ipsecme-big-payload/> | IPSECME | Increase payload size to handle PQC keys | |
| Alternative Approach for Mixing Preshared Keys in IKEv2 for Post-quantum Security | <https://datatracker.ietf.org/doc/draft-smyslov-ipsecme-ikev2-qr-alt/> | IPSECME | | | 
| Announcing Supported Authentication Methods in IKEv2 | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-auth-announce/> | IPSECME | Allows IKEv2 implementations to indicate the list of supported authentication methods | |
| Hybrid Non-Composite Authentication in IKEv2 | <https://datatracker.ietf.org/doc/draft-guthrie-ipsecme-ikev2-hybrid-auth/> | IPSECME | Non-composite hybrid authentication for IKEv2 | Expired 2022-09-26 |
| Intermediate Exchange in the Internet Key Exchange Protocol Version 2 (IKEv2) | <https://datatracker.ietf.org/doc/rfc9242/> | IPSECME | Defines a new "Intermediate Exchange" to handle large amounts of data is SA establishment to handle PQC keys | RFC |
| Internet Key Exchange Protocol Version 2 (IKEv2) Message Fragmentation | <https://datatracker.ietf.org/doc/rfc7383/> | IPSECME | Packet fragmentation on larger packets to handle PQC keys | RFC |
| Mixing Preshared Keys in the Internet Key Exchange Protocol Version 2 (IKEv2) for Post-quantum Security | <https://datatracker.ietf.org/doc/rfc8784/> | IPSECME | | RFC |
| Multiple Key Exchanges in IKEv2 | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-multiple-ke/> | IPSECME | Defines multiple (hybrid) key exchange, with applications to PQ among other things | Submitted to IESG for Publication |
| Non-Composite Hybrid Authentication in PKIX and Applications to Internet Protocols | <https://datatracker.ietf.org/doc/draft-becker-guthrie-noncomposite-hybrid-auth/> | LAMPS | Non-composite hybrid authentication for X.509 | Expired 2022-09-26 | 
| Related Certificates for Use in Multiple Authentications within a Protocol | <https://datatracker.ietf.org/doc/draft-ietf-lamps-cert-binding-for-multi-auth/> | LAMPS | Bind certs across non-composite parallel PKIs | |
| Hybrid key exchange in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-ietf-tls-hybrid-design/> | TLS | Hybrid TLS key exchange | Adopted by WG |
| Suppressing CA Certificates in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-kampanakis-tls-scas-latest/> | TLS | TLS authentication and certificate chain | |
| Terminology for Post-Quantum Traditional Hybrid Schemes | <https://datatracker.ietf.org/doc/draft-driscoll-pqt-hybrid-terminology/> | PQUIP | | |
| Quantum Relief with TLS and Kerberos | <https://datatracker.ietf.org/doc/draft-vanrein-tls-kdh/> | Individual | Kerberos-over-TLS. | Unclear that this is directly PQC-related |


# Sec Area Protocols - No Action Needed

This table lists IETF Security Area protocols with "No Action Needed", typically because that protocol does not itself specify any cryptographic algorithms but instead embeds other IETF cryptographic protocols. Therefore no action is needed for that protocol because it will inherit PQ crypto as soon as its cryptographic dependencies support it. 


| Protocol | RFC       | Working Group  | Cryptographic dependencies | Comment |
|--------- |---------- |--------------- |--------------------------- |-------- |
| ACME     | RFC8555   | ACME           | PKCS #10 (RFC2986), JOSE/JWS (RFC 7515), TLS (RFC8446) | |
| CMC      | RFC5272   | LAMPS          | CMS (RFC5652), PKCS #10 (RFC2986) |         |
| QUIC     | RFC9000   | quic           | TLS 1.3 (RFC8446)          | QUIC is pretty specific to TLS 1.3, so probably needs an update in lockstep with each TLS update |
| DoH      | RFC8484   | doh            | TLS (RFC8446)              |         |
| EST      | RFC7030   | LAMPS          | CMC (RFC5272), CMS (RFC5652), PKCS #10 (RFC2986), TLS (RFC8446) |         |
| HTTPS    | RFC9110   | HTTPbis       | TLS (RFC8446)
| SCEP     | RFC8894   | LAMPS (?)      | CMS (RFC5652), PKCS #10 (RFC2986) |  |
| S/MIME   | RFC5751   | LAMPS        | CMS (RFC5652)               |         | Section 4.1 does explicitely list RSA, DSA, SHA-1. So maybe this does need a DIE DIE DIE draft? |
