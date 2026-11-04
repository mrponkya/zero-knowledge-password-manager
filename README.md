# Zero-Knowledge Password Manager: Secure Implementation

First Quadrant Labs Internship, Project 1.

## Overview
A self-hosted Vaultwarden and Bitwarden environment, hardened with encryption, multi-factor authentication, role-based access, backups and monitoring. The server never sees users' plaintext vault data (zero-knowledge design).

## What was built
- **Deployment:** Docker containers behind a Caddy TLS reverse proxy.
- **Cryptography:** Argon2id key derivation and AES-256 encryption.
- **Authentication:** TOTP multi-factor authentication.
- **Access control:** role-based collections with read-only and restricted access, with tests confirming unauthorized access is denied.
- **Backup and recovery:** automated GPG-encrypted backups with integrity checks and tested full restores.
- **Logging and monitoring:** Filebeat, Elasticsearch and Kibana tracking failed logins and authentication events.
- **Documentation:** deployment, training and recovery guides for cross-platform users.

## Deliverables
| # | Deliverable |
| --- | --- |
| 1 | Security Architecture Document |
| 2 | Encryption and Key Management Plan |
| 3 | Authentication and RBAC Configuration Guide |
| 4 | Backup and Recovery Documentation |
| 5 | Cross-Platform Deployment Guide |
| 6 | Usability Feature Configuration |
| 7 | Monitoring and Logging Setup |
| 8 | User Training Materials |

Screenshot evidence for each phase is in `proof/`.

## Tools
Docker, Caddy, Vaultwarden, Bitwarden, OpenSSL, GPG, Filebeat, Elasticsearch, Kibana.
