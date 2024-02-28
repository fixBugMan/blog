《GitHub Pages使用教程》

GitHub Pages是一个为你和你的项目提供网站托管服务的平台。所有的网站内容都可以直接从你的GitHub仓库中进行编辑和更新，只需要编辑后推送，你的更改即刻上线。

你每个GitHub账户和组织都能拥有一个自己的网站，而项目网站则无限制。以下为如何开始的步骤：

1. **创建仓库**：进入GitHub，创建一个名为`username.github.io`的新公开仓库，其中`username`是你在GitHub上的用户名（或组织名称）。如果仓库前缀部分未完全匹配用户名，将不能正常工作。

2. **克隆仓库**：在你希望存储项目的文件夹，克隆新仓库。过程如下：
```bash
git clone https://github.com/username/username.github.io
```

3. **创建Hello World**：进入项目文件夹，添加一个`index.html`文件。代码如下：
```bash
cd username.github.io
echo "Hello World" > index.html
```

4. **推送修改**：添加、提交并推送你的更改。代码如下：
```bash
git add --all
git commit -m "Initial commit"
git push -u origin main
```
完成后，打开浏览器，前往`https://username.github.io`即可看到你的网站。

**扩展技巧**：

- **使用Jekyll制作博客**：Jekyll可以让你用优美的Markdown语法写博客，无需处理数据库。[点击这里学习如何设置Jekyll](https://app.recraft.ai/project/0f7632d7-a5f4-42a2-8ff5-9be3177d14c6)。
- **自定义URL**：如果你想用自己的自定义域名，只需创建一个名叫CNAME的文件并输入你的URL。
- **进阶教程**：你可以学习如何创建自定义404页面，如何使用子模块，以及更多关于GitHub Pages的知识。

以上内容仅供参考，如有疑问，请参阅GitHub Pages帮助文档或提交问题。
