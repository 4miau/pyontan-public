# Security policy

pyontan is a closed-source app for Windows and Android, with a website at [pyontan.com](https://pyontan.com) and a browser extension. This repo holds its public docs and no code.

## Reporting a problem

**Please report it privately, not as a public issue.** Either:

- **[Send feedback](https://pyontan.com/feedback)** on the website and say it's a security report, or
- A direct message on **[Discord](https://discord.gg/Pz3gCFPejV)**

Say what you found, how to reproduce it, which part it's in and what you think it lets someone do. Please don't post a working exploit before it's fixed.

## Scope

**In scope:** the Windows and Android apps, the browser extension, pyontan.com and its API, and signing in.

**Out of scope:** the translation services pyontan can use with your own key (DeepL, Google, OpenAI and so on): report those to the service.

## Downloading safely

**Only download pyontan from [pyontan.com/download](https://pyontan.com/download), Google Play, the Chrome Web Store or Firefox Add-ons.** No installer is shared from this repo, and a copy from anywhere else isn't mine.

The download page lists each file's SHA-256. To check the Windows installer, run this in PowerShell and compare:

```powershell
Get-FileHash pyontan-<version>-setup.exe
```

The Windows app isn't code-signed yet, so Windows may show "Windows protected your PC" the first time. That's Windows not having seen the app much yet, not a virus warning.
