# deepseek markdown to doc with LaTeX
**deepseek对话导出doc with LaTeX,常见的md转doc文件随便转，但是一旦md文件里面包含了LaTeX公式，尤其是deepseek生成的内容使用在线导出doc，Typora等工具导出后都无法识别数学公式。**

**deepseek对话转doc,deepseek对话含 LaTeX转doc，deepseek markdown导出 to doc,deepseek转doc**

1. 可以使用vscode+[Markdown Preview Enhanced插件](https://github.com/shd101wyy/vscode-markdown-preview-enhanced)+pandoc，完美解决。
2. 首先安装pandoc.exe，安装Markdown Preview Enhanced插件并，设置该插件**Markdown-preview-enhanced:** **Pandoc Path**为pandoc的安装位置
3. 新建.md且为UTF-8类型，然后再md文件头部添加额外内容

   ```
   ---
   title: "Habits"
   author: John Doe
   date: March 22, 2005
   output: word_document
   ---
   ```
4. 选择md文件，右键选择使用Markdown Preview Enhanced打开：
5. 打开后右键导出 pandoc即可，测试文档见test.md
6. [可参考Markdown Preview Enhanced插件使用说明](https://shd101wyy.github.io/markdown-preview-enhanced/#/zh-cn/pandoc-word)
