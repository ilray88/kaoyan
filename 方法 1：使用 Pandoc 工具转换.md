要将 Word 文件转为 Markdown 格式，可以使用以下几种方法：

### 方法 1：使用 Pandoc 工具转换
1. [下载并安装 Pandoc](https://pandoc.org/)。
2. 打开终端（或命令提示符），执行以下命令将 Word 转换为 Markdown：
   ```bash
   pandoc -s 输入文件.docx -t markdown -o 输出文件.md
   ```
   将“输入文件.docx”替换为您的文件路径，“输出文件.md”将是转换后的 Markdown 文件。

### 方法 2：使用在线转换工具
- 可以使用在线转换工具如 [Word to Markdown Converter](https://word2md.com/) 或 [Zamzar](https://www.zamzar.com/) 将 Word 文档直接上传并下载 Markdown 文件。

### 方法 3：使用 Typora 等 Markdown 编辑器
- 将 Word 内容粘贴到 [Typora](https://typora.io/) 中，Typora 会自动将其转换为 Markdown。
- 完成后可以直接保存为 `.md` 格式。

通过这些方法，您就可以将 Word 文件转为 Markdown 格式，并进一步上传到 GitHub 等平台了。