<div align="center">

<a href="https://pyontan.com"><img src="logo.png" width="128" alt="pyontan" /></a>

# pyontan

### Read and hear Japanese anywhere, and study what you actually ran into

**A Windows app, a website and a browser extension for Japanese: look up and translate manga, games, streams, songs and chat as you go, with Study lessons from N5 to N1 built in.**

[![Download](https://img.shields.io/badge/Download-Windows%20%7C%20Android-F472B6?style=for-the-badge&logo=windows&logoColor=white)](https://pyontan.com/download)
[![Website](https://img.shields.io/badge/Website-pyontan.com-7C9EFF?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://pyontan.com)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Pz3gCFPejV)
[![Facebook](https://img.shields.io/badge/Facebook-Follow-0866FF?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/people/pyontan/61596944394063/)

**[Download](https://pyontan.com/download)** · **[What it does](https://pyontan.com/about)** · **[Pricing](https://pyontan.com/pricing)** · **[Guides](https://pyontan.com/guides)** · **[Changelog](https://pyontan.com/blog)** · **[Roadmap](https://pyontan.com/roadmap)**

**In this repo:** [Features](docs/features.md) · [FAQ](docs/faq.md) · [Troubleshooting](docs/troubleshooting.md) · [Support](SUPPORT.md) · [Security](SECURITY.md)

</div>

---

## What it is

pyontan sits in your tray and helps with whatever Japanese is on your screen or coming out of your speakers. Drag a box round a speech bubble, play a stream, or copy a line from anywhere, and you get the reading, the meaning and a translation right there.

The words you look up go into your reviews, so Study is built from the Japanese you actually met, next to grammar lessons from N5 to N1.

I'm the only developer. pyontan is closed source, so this repo has no code. It's here for the details, the docs and a place to report bugs.

> **Windows 10 and 11 (64-bit)**, **Android 7 or later**, and the website in any browser. The browser extension works in Chrome, Edge, Brave and Firefox.

---

## Download

**[⬇ Get it from pyontan.com/download](https://pyontan.com/download)**

| | Where |
|---|---|
| **Windows app** | Installer from [pyontan.com/download](https://pyontan.com/download). It tells you when an update is out |
| **Android app** | [Google Play](https://play.google.com/store/apps/details?id=app.pyontan) (early access), or the APK from [pyontan.com/download](https://pyontan.com/download) |
| **Browser extension** (pyontan Hop) | [Chrome Web Store](https://chromewebstore.google.com/detail/pyontan-web-extension/ndmcijolccjcgmfpdijichkkggckiijn) · [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/pyontan-hop/) |
| **Website** | [pyontan.com](https://pyontan.com): Dictionary, Translator, Study and your manga library, on any device |

Every download page lists a SHA-256 so you can check the file. **Only download pyontan from pyontan.com or the stores above.** No installer is shared from this repo.

The Windows app isn't code-signed yet, so the first time you open it Windows may say "Windows protected your PC". Press **More info**, then **Run anyway**.

---

## What it does

| Feature | |
|---|---|
| **OCR Capture** | Press Alt+L and drag a box round text in a manga, a game or a paused video. Live Mode keeps reading one spot as it changes, like a game's text box |
| **Live Audio Translation** | Subtitles for streams, videos and calls, from anything playing on your PC. The speech recognition runs on your own computer |
| **Batch Translate** | A folder of manga, manhwa or comic pages read and translated, with the translation lettered back into the bubbles |
| **Game text** | A window that follows a visual novel's text as you play |
| **Song Lyrics** | Play a song and press Alt+M: the lyrics follow along line by line, with furigana and a translation |
| **Quick Translate** | Copy Japanese anywhere and a popup answers |
| **Reading Assist** | Furigana over the kanji you don't know yet, and none over the ones you do |
| **Dictionary** | JMdict, pitch accent, kanji with their parts, and recordings of real people saying the word |
| **Study** | Grammar lessons from N5 to N1, vocabulary, kanji, listening, JLPT-style tests and spaced-repetition reviews |
| **AI Conversation and AI Tutor** | Chat in Japanese at your level, or ask about a sentence and get it explained |
| **Words and Anki** | Save a word with the sentence you found it in, and send it to Anki in one click |
| **Notebook** | Your own notes, next to the words, sentences and answers you saved |

More on each one in **[docs/features.md](docs/features.md)**.

---

## Plans

Every tool is in the free app. Paid plans raise the daily limits, open up more of Study and add storage and sync.

| Free | Premium | Super Premium |
|---|---|---|
| Everyday tools, Live Audio with no daily limit, your own translation keys, the first Study lessons | Hosted AI translation with no key, lettering in the bubbles, Study from N5 to N3, more storage | More of everything, AI Conversation, Study from N3 to N1 with mock exams |

Current prices and the full comparison are on **[pyontan.com/pricing](https://pyontan.com/pricing)**. You can also buy Mochi credits once to keep going when a day's amount runs out.

You can use your own DeepL, Google, OpenAI, Claude, Gemini, DeepSeek or OpenRouter key on every plan, Free included, or a local model through Ollama or LM Studio.

---

## Your data

Your lookups, saved words and Live Audio history stay on your PC unless you turn on sync. Text you translate goes to the translation service you picked. The full policy is at [pyontan.com/privacy](https://pyontan.com/privacy).

---

## Reporting a bug or asking for something

- **[Open an issue](../../issues)** here, if you have a GitHub account
- **[Send feedback](https://pyontan.com/feedback)** from the website or the app
- **[Discord](https://discord.gg/Pz3gCFPejV)** for questions, ideas and a chat

The official pages are the ones linked here and at the bottom of [pyontan.com](https://pyontan.com): the [Facebook page](https://www.facebook.com/people/pyontan/61596944394063/) and the Discord.

Say what you did, what happened, and the app's version (tray menu > Help, at the top). See **[SUPPORT.md](SUPPORT.md)** for more.

---

## Credits

pyontan stands on some great open data: [JMdict and KANJIDIC](https://www.edrdg.org/) from the Electronic Dictionary Research and Development Group, pitch accent from [Kanjium](https://github.com/mifunetoshiro/kanjium), and example sentences from [Tatoeba](https://tatoeba.org/). The full list is at [pyontan.com/credits](https://pyontan.com/credits).
