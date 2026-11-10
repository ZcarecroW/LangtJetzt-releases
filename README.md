# LangtJetzt

A translator for Windows that works through the Claude CLI on your own PC. It needs no API key and no extra account: translations run on your own Claude plan.

This repository only holds the downloads.

## Install

1. Install [Claude Code](https://claude.com/claude-code), open a terminal, run `claude` and log in once.
2. Download the **setup .exe** from the [latest release](https://github.com/ZcarecroW/LangtJetzt-releases/releases/latest) and run it.
3. Windows shows a blue warning because the app is not code-signed. Click **More info**, then **Run anyway**.

LangtJetzt checks at first start that Claude Code is ready and says what to do if something is missing.

## What it does

- **Translate as you type.** Only changed sentences are sent again.
- **Alternatives** for a single word or a whole sentence, the form of address (formal or familiar), a free instruction, a more careful model on demand, and a check by translating back.
- **Write mode** improves your text in its own language. You accept or reject every change.
- **Documents:** Word, PowerPoint, Excel, PDF, text, Markdown, HTML, SRT and VTT, keeping their layout.
- **Glossary** with your own fixed terms.
- **In any program:**

| Keys | What happens |
|---|---|
| Ctrl+C twice | Opens the translator with the copied text |
| Ctrl+Alt+P | A small translation popup by the mouse |
| Ctrl+Alt+R | Replaces the selected text with its translation |
| Ctrl+Alt+S | Translates a part of the screen |

All keys can be changed in Settings.

## Privacy

Your text goes to Claude through the Claude CLI on your PC, under the terms of your own Claude plan. Nothing is sent to the author of this app. History, glossary and remembered sentences stay on your PC.

## Requirements

Windows 10 or 11, and Claude Code logged in with your own Claude account.

## Licence

GPL-3.0. The icons are from Nucleo, licensed to the author for LangtJetzt; they are not covered by the GPL and may not be extracted or reused. The licences of all included components are listed in `THIRD-PARTY-NOTICES.txt` in the app's install folder.
