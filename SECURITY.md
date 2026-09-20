# Parallax Core Security Policy

Security is an important part of the Parallax (PLX) network and the Parallax Core full-node wallet and miner.

Parallax Core combines blockchain validation, wallet functionality, peer-to-peer networking, RPC functionality and Scrypt mining in one desktop application.

## Supported Version

| Version | Status |
| --- | --- |
| v0.1.4 | Current Mainnet release |

The current official Windows Mainnet release is:

**Parallax Core Full-Node Wallet & Miner v0.1.4**

Official releases:

https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner/releases

## Official Download Verification

Only download Parallax Core from official Parallax project sources.

Current Windows Mainnet executable:

`Parallax_Wallet_Miner_Mainnet.exe`

Official SHA256:

`864aa2f45659959903659e16c3759b594b5b69726635b06df016156a3ada4388`

Users should verify the SHA256 checksum before running downloaded software.

## Integrated Wallet Security

Parallax Core includes wallet-security functionality directly inside the application.

Available security and wallet-management features include:

- Wallet encryption
- Wallet passphrase protection
- Change Passphrase
- Wallet backup
- Local private-key ownership
- Message signing
- Message verification
- Full-node blockchain validation
- Peer inspection
- Network traffic monitoring
- Node information
- RPC and console functionality

Wallet encryption helps protect locally stored wallet information from unauthorized access.

Encryption does not replace good computer security.

Users remain responsible for protecting:

- Wallet passphrases
- Private keys
- Wallet backup files
- Operating-system access
- VPS credentials
- RPC credentials
- Backup storage

Never share a wallet passphrase or private key.

## Wallet Backups

Wallet backups should be stored securely and separately from the computer running Parallax Core.

Users should maintain reliable backups before making important wallet changes.

A wallet passphrase should be stored securely because loss of the passphrase may result in permanent loss of access to encrypted wallet funds.

## Full-Node Security

Parallax Core validates blockchain data locally as a full network node.

A fully synchronized Parallax Core client independently processes and validates the Parallax blockchain rather than relying solely on a third-party wallet service.

This provides users with direct participation in the Parallax peer-to-peer network.

## Network Ports

Parallax Mainnet uses:

| Service | Port |
| --- | ---: |
| Mainnet P2P | 19339 |
| Mainnet RPC | 19340 |

The P2P port may be publicly reachable when operating a public Parallax node.

RPC should normally remain restricted to trusted systems or localhost and should not be exposed openly to the public internet.

RPC credentials must never be published in source code, screenshots, public repositories or documentation.

## Private Information

The public Parallax source repository must not contain:

- Private keys
- Wallet database files
- Wallet passphrases
- RPC passwords
- RPC authentication secrets
- Personal wallet backups
- VPS passwords
- SSH private keys
- Private configuration files containing credentials

The official public source tree is intended to contain software source and public project information only.

## Block Explorer Security

The official Parallax block explorer is:

https://explorer.parallaxcoin.xyz/

The explorer provides public read-only blockchain information.

Wallet private keys and wallet passphrases are not required to use the public explorer and should never be entered into it.

## Reporting a Security Vulnerability

If you discover a security vulnerability in Parallax Core, the Parallax blockchain software, the public explorer or related project infrastructure, please report it responsibly.

Do not publicly publish:

- Private keys
- Active credentials
- Working exploits
- RPC passwords
- Wallet passphrases
- Sensitive server information

When possible, use GitHub's private security reporting or security advisory functionality for the repository.

Repository:

https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner

If a private reporting method is unavailable, create a minimal GitHub issue requesting contact with the project maintainers without including exploit details or sensitive information.

Reports should include enough information to reproduce and understand the issue without exposing unrelated private data.

## Responsible Disclosure

Security reports will be reviewed to determine:

- Whether the issue can be reproduced
- Which versions are affected
- Whether user funds or private information are at risk
- Whether the issue affects wallet, node, mining or network functionality
- What remediation is required

Where appropriate, a fix should be prepared before detailed vulnerability information is publicly disclosed.

## User Security Checklist

Parallax users should:

1. Download software only from official project sources.
2. Verify the published SHA256 checksum.
3. Encrypt wallets containing valuable PLX.
4. Use a strong unique wallet passphrase.
5. Maintain secure wallet backups.
6. Never share private keys.
7. Never publish RPC credentials.
8. Keep RPC access restricted.
9. Keep the operating system updated and protected.
10. Verify recipient addresses before sending PLX.
11. Keep important backups on separate secure storage.
12. Confirm that the wallet is synchronized with the correct Parallax Mainnet before transacting or mining.

## Official Resources

Official website:

https://parallaxcoin.xyz/

Official block explorer:

https://explorer.parallaxcoin.xyz/

Official GitHub:

https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner

Official releases:

https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner/releases

---

**Parallax (PLX)**

**Full Node. Wallet. Miner.**

Security functions are integrated into Parallax Core, while users retain control and responsibility for their private keys, wallet backups and credentials.
