<!--
 * @Author       : ❤ SEOer.Vip
 * @FilePath     : /VipSEOer/VSCode.md
 * @Copyright    : Https://Blog.SEOer.Vip/
 * @Description  : VSCode（Visual Studio Code）使用文档
-->

VSCode（Visual Studio Code）使用文档
==================================================================

> - Visual Studio Code（简称 VSCode / VSC）是一款免费开源的现代化轻量级代码编辑器
> - VSCode 支持几乎所有主流的开发语言的语法高亮、智能代码补全、自定义热键、括号匹配、代码片段、代码对比 Diff、Git 等特性
> - VSCode 支持插件扩展，软件跨平台支持 Win、Mac 以及 Linux，运行流畅，可谓是微软的良心之作……

VSCode Extensions <https://marketplace.visualstudio.com/VSCode>
------------------------------------------------------------------

- `Chinese (Simplified) Language`           【官方汉化】
- `One Dark Pro`                            【主题配色】
- `Material Icon Theme`                     【主题图标】
- `Code Runner`                             【代码运行】
- `PostCode`                                【代码调试】
- `Path Intellisense`                       【路径补全】
- `Code Spell Checker`                      【拼写检查】
- `Image Preview`                           【图片预览】
- `Indent-Rainbow`                          【彩虹缩进】
- `koroFileHeader`                          【注释圣手】
- `Better Comments`                         【注释高亮】
- `Rainbow CSV`                             【高亮.CSV】

- `HTML CSS Support`                        【属性支持】
- `MarkdownLint`                            【语法规范】
- `Markdown All in One`                     【语法补全】
- `PHPDocument`                             【语法文档】
- `PHP Intelephense`                        【语法感知】
- `Apache Conf`                             【语法高亮】
- `Nginx Configuration`                     【语法高亮】

VSCode（Settings.json）自定义配置
------------------------------------------------------------------

```json
{
    "workbench.colorTheme": "One Dark Pro",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.settings.useSplitJSON": true,
    "oneDarkPro.bold": true,
    "oneDarkPro.vivid": true,
    "oneDarkPro.italic": false,
    "editor.linkedEditing": true,
    "editor.renderWhitespace": "all",
    "editor.guides.bracketPairs": "active",
    "editor.bracketPairColorization.enabled": true,
    "editor.fontFamily": "Consolas, 'Yahei Mono', monospace",
    "markdown.preview.fontFamily": "Consolas, 'Yahei Mono', monospace",
    "files.trimFinalNewlines": true,
    "files.insertFinalNewline": true,
    "files.trimTrailingWhitespace": true,
    "html.format.wrapLineLength": 0,
    "html.format.endWithNewline": true,
    "PHPDocument.language": "Chinese",
    "fileheader.configObj": {
        "wideSame": true,
        "filePathColon": "/",
        "prohibitAutoAdd": [
            "html",
            "json"
        ]
    },
    "fileheader.customMade": {
        "Author": "❤ SEOer.Vip",
        "FilePath": "Do not edit",
        "Copyright": "Https://Blog.SEOer.Vip/",
        "Description": "Rock The Code, Are You Ready?"
    },
    "[markdown]": {
        "editor.defaultFormatter": "DavidAnson.vscode-markdownlint"
    }
}
```

VSCode（Keybindings.json）自定义快捷键
------------------------------------------------------------------

```json
[
    {
        "key": "alt+f9",
        "command": "editor.debug.action.toggleBreakpoint",
        "when": "editorTextFocus"
    },
    {
        "key": "f9",
        "command": "-editor.debug.action.toggleBreakpoint",
        "when": "editorTextFocus"
    },
    {
        "key": "f9",
        "command": "editor.action.formatDocument",
        "when": "editorHasDocumentFormattingProvider && editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
    },
    {
        "key": "shift+alt+f",
        "command": "-editor.action.formatDocument",
        "when": "editorHasDocumentFormattingProvider && editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
    },
    {
        "key": "ctrl+oem_comma",
        "command": "-workbench.action.openSettings"
    },
    {
        "key": "ctrl+oem_comma",
        "command": "editor.action.triggerSuggest",
        "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly"
    },
    {
        "key": "ctrl+space",
        "command": "-editor.action.triggerSuggest",
        "when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly"
    }
]
```
