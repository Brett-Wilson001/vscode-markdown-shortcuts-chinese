# Markdown Shortcuts

[![English](https://img.shields.io/badge/lang-English-blue.svg)](README.en.md)
[![中文](https://img.shields.io/badge/语言-中文-red.svg)](README.md)

## Table of Contents
- [Markdown Shortcuts](#markdown-shortcuts)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [License](#license)
  - [Demos](#demos)
  - [Available Commands](#available-commands)
  - [Configuration Settings](#configuration-settings)
    - [Configurable Options](#configurable-options)
      - [Title Bar Icons](#title-bar-icons)
      - [Markdown Markers](#markdown-markers)
      - [Language Support](#language-support)
  - [Changelog (See CHANGELOG for details)](#changelog-see-changelog-for-details)
    - [0.12.4 (March 12, 2026)](#0124-march-12-2026)
    - [0.12.3](#0123)
    - [0.12.2](#0122)
    - [0.12.1](#0121)

## About

> This project is a fork of [vscode-markdown-shortcuts](https://github.com/mdickin/vscode-markdown-shortcuts) by mdickin, which is licensed under the MIT License.
>
> The original plugin is very useful but only supports English. This version adds multilingual support:
>
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
| md-shortcut.toggleBullets | Add - bullet list | ctrl+M ctrl+B |
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

## Configuration Settings

You can configure the plugin by searching "Markdown Shortcuts" or "markdownShortcuts" in VSCode settings (`Ctrl + ,`).

### Configurable Options

#### Title Bar Icons

Control which shortcut icons are displayed in the editor title bar:

- Bold icon
- Italic icon
- Strikethrough icon
- Bullets icon
- Link icon
- Image icon
- Citations icon

#### Markdown Markers

Customize the marker symbols for various Markdown syntax:

- **Bold marker**: Double asterisks (`**`) or Double underscores (`__`)
- **Italic marker**: Asterisk (`*`) or Underscore (`_`)
- **Bullet list marker**: Hyphen (`-`), Asterisk (`*`), or Plus sign (`+`)

#### Language Support

Set the file types for which shortcuts are available (default is `markdown`, you can add other file types)

## Changelog (See [CHANGELOG](CHANGELOG.md) for details)

### 0.12.4 (March 12, 2026)

- **Optimized**: Improved settings UI with friendly visual interface for all configuration options
  - Title bar icon settings display as toggle switches
  - Markdown marker settings display as dropdown menus with detailed descriptions
  - Language settings display as array editors
- **Changed**: Default bullet list marker changed from asterisk (`*`) to hyphen (`-`)
  - Users can customize to use `-`, `*`, or `+` as bullet list markers in settings

### 0.12.3

- **Added**: Multilingual support, automatically detects VSCode language
  - Chinese users see localized interface
  - English users see original English interface
- **Optimized**: Improved localization architecture for easier future language additions

### 0.12.2

- **Optimized**: Improved plugin startup logic for better performance

### 0.12.1

- **Added**: Chinese localization for better Chinese user experience
