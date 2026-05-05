<img width="200" alt="aster_horizontalv2" src="https://github.com/user-attachments/assets/a337e975-996d-4672-a92b-b809591f389a" />

# Welcome to Aster!
Aster is an encrypted email service that lets you communicate without censorship, without anyone reading over your shoulder. Our current end-to-end encrypted product lineup is:

- **[Aster Mail](https://astermail.org)** – end-to-end encrypted email, currently available in beta
- **Aster Authenticator** – end-to-end encrypted two-factor authenticator app, coming soon

## Open Source
Aster is completely open source under AGPL v3. If you see something wrong, feel free to open an issue. If you want to fix something, open a pull request.

## Security & Encryption
All of Aster's encryption and decryption happens on the client side. If you send a message Aster -> Aster, we use a Signal-inspired protocol (X3DH + Double Ratchet) with ML-KEM-768 post-quantum 
cryptography, this ensures that we protect against store-now-decrypt-later attacks. All Aster -> External emails use RSA-4096 PGP, these are portable keys that work with GPG, Thunderbird, or any PGP client. 

We encrypt as much metadata as we possibly can while keeping email seamless and convenient to use. This includes (but is not limited to):
- Subject lines
- Contacts
- Folder structure
- Search indices
- Timestamps
- Attachment data

## Contributing
We welcome feedback and contributions of all kinds. If you find a bug, please open an issue. If you would like to contribute code, please fork the repository and open a pull request. Please read our [Contributing Guide](https://github.com/Aster-Privacy/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/Aster-Privacy/.github/blob/main/CODE_OF_CONDUCT.md).

## Join the Community
If you would like to get involved, share your feedback, or just keep up with Aster, you can find us here:
- [Discord](https://discord.gg/t5fKbGmvKD)
- [X / Twitter](https://x.com/AsterPrivacy)
- [Reddit](https://www.reddit.com/r/AsterPrivacy/)
