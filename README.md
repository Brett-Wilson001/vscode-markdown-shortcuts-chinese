# Markdown 快捷键 (Markdown Shortcuts)

本项目复刻自[vscode-markdown-shortcuts](https://github.com/mdickin/vscode-markdown-shortcuts)并添加个人汉化。用于编辑 Markdown (`.md`, `.markdown`) 文件的便捷快捷键。您也可以在任何其他类型的文件中使用 Markdown 格式（请参阅配置设置）。

**快速切换项目符号**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/bullets.gif)

**轻松生成链接**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/urls.gif)

**将表格数据转换为 Markdown 表格**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/table_with_header.gif)

**右键菜单和标题栏菜单集成**

![](https://raw.githubusercontent.com/mdickin/vscode-markdown-shortcuts/master/media/demo/shortcut_menu.png)

您可以通过 `markdownShortcuts.icons.*` 配置设置来显示或隐藏标题栏中的图标。

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
| md-shortcut.toggleBullets | 添加 * 无序列表 | ctrl+M ctrl+B |
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
