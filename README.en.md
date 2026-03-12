# Markdown Shortcuts

[![English](https://img.shields.io/badge/lang-English-blue.svg)](README.en.md)
[![中文](https://img.shields.io/badge/语言-中文-red.svg)](README.md)

## About

> This project is a fork of [vscode-markdown-shortcuts](https://github.com/mdickin/vscode-markdown-shortcuts) by mdickin, which is licensed under the MIT License.
>
> The original plugin is very useful but only supports English. This version adds multilingual support:
> - Chinese users automatically see a localized interface
> - English users see the original English interface
> - Automatically detects VSCode language settings, no manual selection required

Handy shortcuts for editing Markdown (`.md`, `.markdown`) files. You can also use markdown formats in any other file (see configuration settings).

## License
- This project is licensed under the MIT License
- Original author: [mdickin](https://github.com/mdickin)
- Maintainer of this fork: [Brett-Wilson](https://github.com/Brett-Wilson001)

## Demos

**Quickly toggle bullet points**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/bullets.gif)

**Easily generate URLs**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/urls.gif)

**Convert tabular data to tables**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/table_with_header.gif)

**Context and title menu integration**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/shortcut_menu.png)

You can show and hide icons in the title bar with the `markdownShortcuts.icons.*` config settings.

## Available Commands

| Command ID | Description | Default Key Binding |
| ---------- | ----------- | ------------------- |
| md-shortcut.showCommandPalette | Show all commands | ctrl+M ctrl+M |
| md-shortcut.toggleBold | Make **bold** | ctrl+B |
| md-shortcut.toggleItalic | Make _italic_ | ctrl+I |
| md-shortcut.toggleStrikethrough | Make ~~strikethrough~~ | |
| md-shortcut.toggleLink | Add [hyperlink](www.example.org) | ctrl+L |
| md-shortcut.toggleImage | Add image ![](image_url.png) | ctrl+shift+L |
| md-shortcut.toggleCodeBlock | Add ```code block``` | ctrl+M ctrl+C |
| md-shortcut.toggleInlineCode | Add `inline code` | ctrl+M ctrl+I |
| md-shortcut.toggleBullets | Add * bullet list | ctrl+M ctrl+B |
| md-shortcut.toggleNumbers | Add 1. numbered list | ctrl+M ctrl+1 |
| md-shortcut.toggleCheckboxes | Add - [ ] task list (GitHub flavored markdown) | ctrl+M ctrl+X |
| md-shortcut.toggleTitleH1 | Toggle # H1 heading | |
| md-shortcut.toggleTitleH2 | Toggle ## H2 heading | |
| md-shortcut.toggleTitleH3 | Toggle ### H3 heading | |
| md-shortcut.toggleTitleH4 | Toggle #### H4 heading | |
| md-shortcut.toggleTitleH5 | Toggle ##### H5 heading | |
| md-shortcut.toggleTitleH6 | Toggle ###### H6 heading | |
| md-shortcut.addTable | Add table (from text data) | |
| md-shortcut.addTableWithHeader | Add table (with header) | |

## Changelog

### 0.12.3
- **Added**: Multilingual support, automatically detects VSCode language
  - Chinese users see localized interface
  - English users see original English interface
- **Added**: English README
- **Optimized**: Improved localization architecture for easier future language additions

### 0.12.2
- **Optimized**: Improved plugin startup logic for better performance

### 0.12.1
- **Added**: Chinese localization for better Chinese user experience