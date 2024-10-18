# Keystore Decryptor for EVM-based Blockchain Keystore Files

This tool allows you to decrypt your EVM-based Keystore Files for blockchains like Ethereum, BNB, or Polygon and extract the private key securely. All operations are performed client-side in your browser to ensure maximum security and privacy. Your data is never sent to any server.

## Features
- Decrypts Ethereum, BNB, and Polygon keystore files.
- 100% client-side execution to ensure the security of your private keys.
- Simple interface to paste keystore JSON and input the password to retrieve the private key.

## Hosted Version
Check out the hosted version of this tool at [Chaingateway.io](https://chaingateway.io/tools/keystore-decryptor/).

### Why Use ChainGateway.io?
Chaingateway.io offers a secure and easy-to-use platform for various blockchain tools, including this **Keystore Decryptor**. If you're looking for a convenient solution with more capabilities and professional support, the hosted version may be ideal for you.

## How to Use
1. Clone or download this repository.
2. Ensure you have the `keythereum.min.js` file located in the `assets/js/` directory.
3. Open the `index.html` file in your browser.
4. Paste your keystore JSON and input your password to decrypt and view your private key.

## Security Notice
For the best security practices:
- Disconnect your internet connection while using this tool.
- Never share your private key with anyone.
- Use this tool in an isolated, offline environment if possible.

## Acknowledgments
This tool is powered by the fantastic work from the [ethereumjs/keythereum](https://github.com/ethereumjs/keythereum) library. Keythereum handles the decryption of keystore files and is trusted by the Ethereum community for its security and robustness.
