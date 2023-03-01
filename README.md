# Internet-Drafts that cover PQC

| Draft title | Link | Working Group and/or protocol | Topic | Comments |
|------------ |----- |------------------------------ |------ |--------- |
| Suppressing CA Certificates in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-kampanakis-tls-scas-latest/> | TLS | TLS authentication and certificate chain | |
| Hybrid key exchange in TLS 1.3 | <https://datatracker.ietf.org/doc/draft-ietf-tls-hybrid-design/> | TLS | Hybrid TLS key exchange | Adopted by WG |
| KEM-based Authentication for TLS 1.3 | <https://datatracker.ietf.org/doc/draft-celi-wiggers-tls-authkem/> | TLS | KEM-based authentication | Expired draft | 
| Stateful Hash-based Signatures For DNSSEC | <https://datatracker.ietf.org/doc/draft-afrvrd-dnsop-stateful-hbs-for-dnssec/> | DNSOP | Stateful Hash-based Signatures For DNSSEC | Expired draft | 
| Post-Quantum Cryptography in OpenPGP | <https://datatracker.ietf.org/doc/draft-wussler-openpgp-pqc/> | OPENPGP | Post-Quantum public-key algorithm extension for the OpenPGP protocol | |
| Non-Composite Hybrid Authentication in PKIX and Applications to Internet Protocols | <https://datatracker.ietf.org/doc/draft-becker-guthrie-noncomposite-hybrid-auth/> | LAMPS | Non-composite hybrid authentication | Expired draft | 
| Composite Signatures For Use In Internet PKI | <https://datatracker.ietf.org/doc/draft-ounsworth-pq-composite-sigs/> | LAMPS | Composite public and private keys and encryption | Expired draft | 
| Algorithm Identifiers for NIST's PQC Algorithms for Use in the Internet X.509 Public Key Infrastructure | <https://datatracker.ietf.org/doc/draft-turner-lamps-nist-pqc-kem-certificates/> | LAMPS | | Expired draft |
| Internet X.509 Public Key Infrastructure: Algorithm Identifiers for Dilithium | <https://datatracker.ietf.org/doc/draft-ietf-lamps-dilithium-certificates/> | LAMPS | Dilithium quantum-resistant signatures in Internet X.509 certificates | |
| Use of Post-Quantum KEM in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-perret-prat-lamps-cms-pq-kem/> | LAMPS | | |
| Use of Post-Quantum KEM in the Cryptographic Message Syntax (CMS) | <https://datatracker.ietf.org/doc/draft-perret-prat-lamps-cms-pq-kem/> | LAMPS | | |
| Multiple Key Exchanges in IKEv2 | <https://datatracker.ietf.org/doc/draft-ietf-ipsecme-ikev2-multiple-ke/> |IPSECME| |Submitted to IESG for Publication |
| Post-quantum Hybrid Key Exchange in SSH | <https://datatracker.ietf.org/doc/draft-kampanakis-curdle-ssh-pq-ke/> | SSH | | |
| Kyber Post-Quantum KEM | <https://datatracker.ietf.org/doc/draft-cfrg-schwabe-kyber/> | CFRG | Description of the Kyber algorithm | |
| NTRU Key Encapsulation | <https://datatracker.ietf.org/doc/draft-fluhrer-cfrg-ntru/> | CFRG | Description of the NTRU algorithm | |
| Application Scenarios for the Quantum Internet | <https://datatracker.ietf.org/doc/draft-irtf-qirg-quantum-internet-use-cases/> | QIRG | | |
| Leighton-Micali Hash-Based Signatures | <https://www.rfc-editor.org/rfc/rfc8554> | CFRG | | RFC | 
| XMSS: eXtended Merkle Signature Scheme | <https://www.rfc-editor.org/rfc/rfc8391> | CFRG | | RFC | 
| Use of the HSS/LMS Hash-Based Signature Algorithm in the Cryptographic Message Syntax (CMS)| <https://www.rfc-editor.org/rfc/rfc8708.html> |CFRG| |RFC | 
|JOSE and COSE Encoding for Post-Quantum Signatures| <https://datatracker.ietf.org/doc/draft-ietf-cose-post-quantum-signatures/> | COSE | | Will be split into separate drafts, one for each alg covered |



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
