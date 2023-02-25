<!--
 * @Author       : ❤ SEOer.Vip
 * @FilePath     : /VipSEOer/VSCode.md
 * @Copyright    : Https://Blog.SEOer.Vip/
 * @Description  : VSCode（Visual Studio Code）使用文档（VSCode@CodeSpace）
-->

VSCode（Visual Studio Code）使用文档 <https://vscode.dev/> | <https://github.dev/>
===================================================================================================

> - Visual Studio Code（简称 VSCode / VSC）是一款免费开源的现代化轻量级代码编辑器
> - VSCode 支持几乎所有主流的开发语言的语法高亮、智能代码补全、自定义热键、括号匹配、代码片段、代码对比 Diff、Git 等特性
> - VSCode 支持插件扩展，软件跨平台支持 Win、Mac 以及 Linux，运行流畅，可谓是微软的良心之作……

VSCode Extensions <https://marketplace.visualstudio.com/VSCode> | [Visual Studio Code Web](✓)
---------------------------------------------------------------------------------------------------

- `Chinese (Simplified) Language`           【官方汉化】【✓】
- `One Dark Pro`                            【主题配色】【✓】
- `Material Icon Theme`                     【主题图标】【✓】
- `Rainbow CSV`                             【彩虹高亮】【✓】
- `Indent Rainbow`                          【彩虹缩进】【✓】
- `Apache Conf`                             【语法高亮】【✓】
- `Nginx Conf Hint`                         【语法高亮】【✓】
- `PHP DEVSENSE`                            【语法补全】【✓】
- `Path Intellisense`                       【路径补全】【✓】
- `CSS Class Intellisense`                  【样式补全】【✓】
- `Markdown All in One - Web`               【语法补全】【✓】

- `koroFileHeader`                          【文档注释】【✗】
- `Image Preview`                           【图片预览】【✗】
- `Code Runner`                             【代码运行】【✗】
- `PostCode`                                【代码调试】【✗】

VSCode（Settings.json）自定义配置同步 | 设置同步 -> 配置 -> 选择要同步的内容 -> 全选（✓） | 𝐔𝐈状态（✗）
---------------------------------------------------------------------------------------------------

```json
{
    "workbench.colorTheme": "One Dark Pro",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.settings.useSplitJSON": true,
    "oneDarkPro.vivid": true,
    "oneDarkPro.italic": false,
    "editor.linkedEditing": true,
    "editor.renderWhitespace": "all",
    "editor.guides.bracketPairs": "active",
    "editor.fontFamily": "Consolas, 'Yahei Mono', monospace",
    "markdown.preview.fontFamily": "Consolas, 'Yahei Mono', monospace",
    "files.trimFinalNewlines": true,
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,
    "phpTools.language": "zh",
    "php.format.codeStyle": "K&R",
    "php.codeLens.enabled": false,
    "fileheader.configObj": {
        "wideSame": true,
        "filePathColon": "/"
    },
    "fileheader.customMade": {
        "Author": "❤ SEOer.Vip",
        "FilePath": "Do not edit",
        "Copyright": "Https://Blog.SEOer.Vip/",
        "Description": "Rock The Code, Are You Ready?"
    }
}
```

VSCode（Keybindings.json）自定义快捷键同步 | 格式化文档（𝐅𝟗） | 语法补全（𝐂𝐭𝐫𝐥 + 𝐢）
---------------------------------------------------------------------------------------------------

```json
[
    {
        "key": "f9",
        "command": "editor.action.formatDocument",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
    },
    {
        "key": "shift+alt+f",
        "command": "-editor.action.formatDocument",
        "when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
    }
]
```
