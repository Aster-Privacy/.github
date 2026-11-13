<img width="200" alt="Aster" src="https://raw.githubusercontent.com/Aster-Privacy/.github/main/profile/aster_logo.png" />

# Aster

Aster builds end-to-end encrypted email that keeps your communication private and free from censorship.

- **[Aster Mail](https://astermail.org)** - end-to-end encrypted email, with post-quantum protection between Aster accounts
- **Aster Authenticator** - end-to-end encrypted two-factor authentication app, in development

## Open source

The Aster apps are open source under [AGPL v3](https://www.gnu.org/licenses/agpl-3.0.en.html). If you find a problem, open an issue. If you want to fix one, open a pull request.

## Security and encryption

Mail between Aster accounts is encrypted and decrypted on your device. It uses a Signal-inspired protocol (X3DH and Double Ratchet) with ML-KEM-768 post-quantum cryptography, which protects against store-now-decrypt-later attacks. Mail to external recipients uses Ed25519 OpenPGP with Curve25519 encryption subkeys when the recipient publishes a key, and your keys are portable and work with any OpenPGP client. Mail that arrives from outside Aster without OpenPGP encryption reaches our servers readable, and we encrypt it with your public key as soon as it arrives.

Aster encrypts as much as mail delivery allows. Routing data such as sender and recipient addresses and timestamps stays visible to our servers. Encrypted data includes:

- Subject lines
- Contacts
- Folder structure
- Search indices
- Message content
- Attachment data

## Contributing

We welcome feedback and contributions of all kinds. Read our [contributing guide](https://github.com/Aster-Privacy/.github/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/Aster-Privacy/.github/blob/main/CODE_OF_CONDUCT.md) to get started.

## Community

- [Discord](https://discord.gg/R4XqRUfgWZ)
- [X](https://x.com/AsterPrivacy)
- [Reddit](https://www.reddit.com/r/AsterPrivacy/)
