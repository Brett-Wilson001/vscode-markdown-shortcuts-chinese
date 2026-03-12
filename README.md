# Markdown 快捷键 (Markdown Shortcuts)

[![English](https://img.shields.io/badge/lang-English-blue.svg)](README.en.md)
[![中文](https://img.shields.io/badge/语言-中文-red.svg)](README.md)

## 目录
- [Markdown 快捷键 (Markdown Shortcuts)](#markdown-快捷键-markdown-shortcuts)
  - [目录](#目录)
  - [说明](#说明)
  - [许可证](#许可证)
  - [预览图](#预览图)
  - [可用命令](#可用命令)
  - [配置设置](#配置设置)
    - [可配置项](#可配置项)
      - [标题栏图标](#标题栏图标)
      - [Markdown 标记符](#markdown-标记符)
      - [语言支持](#语言支持)
  - [更新日志（详情查看CHANGELOG）](#更新日志详情查看changelog)
    - [0.12.4 (2026-03-12)](#0124-2026-03-12)
    - [0.12.3](#0123)
    - [0.12.2](#0122)
    - [0.12.1](#0121)

## 说明

> 本项目基于 [vscode-markdown-shortcuts](https://github.com/mdickin/vscode-markdown-shortcuts) 进行修改和优化，原项目采用 MIT 许可证。
>
> 这是一个非常好用的插件，但是没有中文界面。本版本在原版基础上增加了多语言支持：
>
> - 中文用户自动显示汉化界面
> - 英文用户保持原版英文界面
> - 自动识别VSCode语言设置，无需手动选择

这是用于编辑 Markdown (`.md`, `.markdown`) 文件的便捷快捷键插件。您也可以在任何其他类型的文件中使用 Markdown 格式（请参阅配置设置）。

## 许可证

- 本项目采用 MIT 许可证
- 原作者：[mdickin](https://github.com/mdickin)
- 本版本维护者：[Brett-Wilson](https://github.com/Brett-Wilson001)

## 预览图

**快速切换项目符号**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/bullets.gif)

**轻松生成链接**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/urls.gif)

**将表格数据转换为 Markdown 表格**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/table_with_header.gif)

**右键菜单和标题栏菜单集成**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/shortcut_menu.png)

## 可用命令

| 命令 ID | 描述 | 默认快捷键 |
| ------- | ---- | ---------- |
| md-shortcut.showCommandPalette | 显示所有命令 | ctrl+M ctrl+M |
| md-shortcut.toggleBold | 设为 **粗体** | ctrl+B |
| md-shortcut.toggleItalic | 设为 _斜体_ | ctrl+I |
| md-shortcut.toggleStrikethrough | 设为 ~~删除线~~ | |
| md-shortcut.toggleLink | 添加 [超链接](www.example.org) | ctrl+L |
| md-shortcut.toggleImage | 添加图片 ![](image_url.png) | ctrl+shift+L |
| md-shortcut.toggleCodeBlock | 添加 ```代码块``` | ctrl+M ctrl+C |
| md-shortcut.toggleInlineCode | 添加 `行内代码` | ctrl+M ctrl+I |
| md-shortcut.toggleBullets | 添加 - 无序列表 | ctrl+M ctrl+B |
| md-shortcut.toggleNumbers | 添加 1. 有序列表 | ctrl+M ctrl+1 |
| md-shortcut.toggleCheckboxes | 添加 - [ ] 任务复选框 (GitHub 风格 Markdown) | ctrl+M ctrl+X |
| md-shortcut.toggleTitleH1 | 切换 # 一级标题 | |
| md-shortcut.toggleTitleH2 | 切换 ## 二级标题 | |
| md-shortcut.toggleTitleH3 | 切换 ### 三级标题 | |
| md-shortcut.toggleTitleH4 | 切换 #### 四级标题 | |
| md-shortcut.toggleTitleH5 | 切换 ##### 五级标题 | |
| md-shortcut.toggleTitleH6 | 切换 ###### 六级标题 | |
| md-shortcut.addTable | 添加表格 (从文本数据转换) | |
| md-shortcut.addTableWithHeader | 添加表格 (带表头) | |

## 配置设置

您可以通过 VSCode 的设置界面（`Ctrl + ,`）搜索 "Markdown Shortcuts"来配置插件。

### 可配置项

#### 标题栏图标

控制编辑器标题栏显示哪些快捷图标：

- 粗体图标
- 斜体图标
- 删除线图标
- 无序列表图标
- 链接图标
- 图片图标
- 引用图标

#### Markdown 标记符

自定义各种 Markdown 语法的标记符号：

- **粗体标记符**：双星号 (`**`) 或 双下划线 (`__`)
- **斜体标记符**：星号 (`*`) 或 下划线 (`_`)
- **无序列表标记符**：减号 (`-`)、星号 (`*`) 或 加号 (`+`)

#### 语言支持

设置快捷键适用的语言类型（默认为 `markdown`，可以添加其他文件类型）

## 更新日志（详情查看[CHANGELOG](CHANGELOG.md)）

### 0.12.4 (2026-03-12)

- **优化**: 完善设置界面，所有配置项现在都有友好的可视化界面
  - 标题栏图标配置显示为开关按钮
  - Markdown 标记符配置显示为下拉菜单，带有详细说明
  - 语言配置显示为数组编辑器
- **变更**: 默认无序列表符号从星号 (`*`) 改为减号 (`-`)
  - 用户可以在设置中自定义使用 `-`、`*` 或 `+` 作为无序列表标记符

### 0.12.3

- **新增**: 实现多语言支持，自动识别VSCode语言设置
  - 中文用户显示汉化界面
  - 英文用户保持原版英文界面
- **优化**: 改进本地化架构，便于后续添加更多语言

### 0.12.2

- **优化**: 改进插件启动逻辑，提升加载性能

### 0.12.1

- **新增**: 添加汉化支持，提升中文用户体验