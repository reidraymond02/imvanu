VS主管主管【Q-——333307——】VS主管主管【 辋芷《888yx●vip》 】
VS主管主管【Q-——333307——】VS主管主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人的技术博客？其实，利用 GitHub Pages 和 Hexo，你也能在半小时内拥有一个专属的免费博客。本文为你整理了最清晰、零基础的搭建全流程。

 为什么要选择 Hexo + GitHub Pages？

- 免费且稳定：托管在 Github 上，无需购买服务器。
- 极速访问：静态页面加载快，支持 CDN 加速。
- SEO 友好：利于百度等搜索引擎收录，轻松构建个人品牌。
- 主题丰富：市面上有海量高颜值 Hexo 主题可选。

 第一步：环境准备（Node.js 与 Git）

在开始前，请确保电脑已安装 [Node.js](https://nodejs.org/)（建议 LTS 版本）和 [Git](https://git-scm.com/)。安装完成后，打开命令行工具，输入以下命令验证：

```bash
node -v
git --version
```

看到版本号即代表安装成功。

 第二步：安装 Hexo 并初始化项目

在命令行中执行：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

这里以 `my-blog` 为项目文件夹名，你可以自由定义。

 第三步：本地预览与写文章

执行 `hexo g` 生成静态文件，再执行 `hexo s` 启动本地服务器。浏览器访问 `http://localhost:4000` 即可预览。

写新文章请使用：

```bash
hexo new post "我的第一篇博客"
```

文章默认使用 Markdown 格式，存放在 `source/_posts` 目录下。

 第四步：部署到 GitHub Pages

1. 创建仓库：在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`。
2. 安装部署插件：

```bash
npm install hexo-deployer-git --save
```

3. 修改站点配置（打开根目录的 `_config.yml`）：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

4. 一键部署：

```bash
hexo clean && hexo g && hexo d
```

浏览器访问 `https://你的用户名.github.io`，你会看到一个全新的博客诞生！

 进阶技巧：绑定自定义域名与 SEO 优化

想要更专业？你可以购买一个域名并绑定到 GitHub Pages。此外，为提升 百度收录 效率，建议安装 `hexo-generator-sitemap` 插件生成站点地图，并在百度站长平台提交。

---

互动引导
你的博客搭好了吗？在搭建过程中是否遇到了难题？欢迎在评论区留言沟通，或者私信我获取完整的主题配置文件！如果这篇文章对你有帮助，请点个 赞 和 在看，让我知道这篇文章对你有价值，你的支持是我持续输出干货的最大动力！

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/blob/main/2026%E5%AE%98%E7%BD%91%E5%B9%B2%E8%B4%A7%EF%BC%9AVS%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90_%E5%AB%A1%E6%88%AE%E8%83%8C%E7%89%A2%E5%BE%92TAUIQ.md

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/commit/e34e25f9a9e74250c6c1d45d2230af9bd097935f

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />
相关推荐：

https://github.com/vargasallison5/hyhncj/blob/main/2026%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%9AVS%E5%B9%B3%E5%8F%B0%E5%AE%98%E6%96%B9_%E6%A1%88%E6%B1%B2%E8%80%98%E8%90%8C%E6%B4%BEUVQKQ.md

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />
相关推荐：

https://github.com/vargasallison5/hyhncj/commit/133372d862a36e0bd0242cbfab0203f806b08480

<img src="https://i.postimg.cc/5tbnDmt0/V8-00001.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
