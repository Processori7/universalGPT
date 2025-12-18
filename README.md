# UniversalGPT (fork of DuckDuckGPT)

**Fork notice / Уведомление о форке**

This repository is a fork of [KudoAI/duckduckgpt](https://github.com/KudoAI/duckduckgpt). The original project was created by **KudoAI**. This fork has been modified and is maintained by **Processor** (https://github.com/Processori7).

**Original author / Первоначальный автор:** KudoAI — **This version / Данная версия:** Processor (https://github.com/Processori7)

---

## What is UniversalGPT? 🚀

UniversalGPT injects AI-powered answers into multiple search engines directly on the search results page. It is a fork of DuckDuckGPT and extends support to a number of search engines, with UI and behavior tweaks.

Key features:
- Adds AI answer panel to search pages (right-side panel)
- Supports multiple search engines: Yandex, DuckDuckGo, Brave, Google, Bing, Rambler, Mail.ru, Yahoo, Ecosia, Startpage
- Ad-hiding heuristics and automatic footer removal
- Default settings: **Proxy API enabled**, **Auto-scroll enabled**
- Fixed right-side panel with responsive sizing
- Larger chat input, improved styling and accessibility
- Toggleable options through settings modal

---

## Installation

1. Install a userscript manager (Tampermonkey, ScriptCat, Violentmonkey, etc.)
2. Install the userscript file located at `greasemonkey/universalgpt.user.js` (or install the `userscript` from the release if available)
3. Open your search engine, and the UniversalGPT panel will show on the right

---

## Usage

- Click the settings (⚙️) button in the panel to change behavior (streaming, proxy mode, summarization preferences)
- Proxy mode uses a proxy API to fetch GPT-4o responses without a ChatGPT account (enabled by default)
- Use the chat input to ask follow-up queries or summarize results

---

## Credits & License

- Original project by **KudoAI** — https://github.com/KudoAI/duckduckgpt
- This fork by **Processor** — https://github.com/Processori7/universalGPT

Licensed under the MIT License — see `LICENSE.md` for details.
