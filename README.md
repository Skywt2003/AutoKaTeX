# AutoKaTeX

## Intro

自动用 KaTeX 渲染 LaTeX 公式

基于 Typecho 插件 [AutoLaTeX](https://github.com/dreamerblue/AutoLaTeX)修改而来，原作者为 [bLue](https://dreamer.blue)。

主要更改：
- 更新 KaTeX 版本为 1.11.1，一部分问题（如公式过长不解析）得以修复。
- 去除 MathJax 的支持，现在直接（只能）使用 KaTeX。同时删除了插件的配置面板。
- 不再解析 `[[[(` `)]]]` 之类令人迷惑的标记。

## Usage

下载最新版本的 [release](https://github.com/Skywt2003/AutoKaTeX/releases)（当然只有一个版本 QwQ），上传到 Typecho 插件目录并解压，重命名文件夹为 `AutoKaTeX`使用。

后台启用插件即可。

## Note

本插件不支持编辑器内预览，所以建议配合 [KaTeXForDefaultEditor](https://github.com/ZigZagK/typecho-plugin-KaTeXForDefaultEditor) 使用。

顺便 % ZZK。

## License

GPL-3.0
