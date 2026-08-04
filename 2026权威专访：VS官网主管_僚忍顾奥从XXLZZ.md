VS官网主管【Q-——333307——】VS官网主管【 辋芷《888yx●vip》 】
VS官网主管【Q-——333307——】VS官网主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025亲测有效）

还在羡慕别人拥有漂亮的个人技术博客？其实免费搭建一个属于自己的博客站点，比想象中简单得多。今天这期内容，手把手带你用 GitHub Pages 加 Hexo 框架，亲手搭建一个加载速度快、完全可控的静态博客，无需购买服务器。

 为什么选择 GitHub Pages + Hexo 组合？

- 零成本：GitHub Pages 提供免费托管服务和自定义域名支持。
- 极速访问：纯静态文件，CDN 加速，用户体验佳。
- 版本管理：基于 Git，所有文章和主题都有历史记录，不怕丢失。
- SEO 友好：Hexo 自动生成静态页面，结构清晰，更易被百度等搜索引擎收录。

 第一步：环境准备与初始化

在开始之前，确保你的电脑已经安装了 Node.js（建议 v18+）以及 Git。打开命令行，全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

接着，在电脑上创建一个空文件夹，比如 `my-blog`，执行初始化命令：

```bash
hexo init my-blog
cd my-blog
npm install
```

初始化完成后，你可以直接输入 `hexo server`，在 `http://localhost:4000` 预览默认的博客界面。

 第二步：关联 GitHub 仓库

打开 GitHub，新建一个仓库，仓库名格式必须是 `你的用户名.github.io`。回到本地命令行，修改 `_config.yml` 文件中的 `url` 字段为该仓库地址。然后在项目根目录执行：

```bash
npm install hexo-deployer-git --save
```

接下来，在 `_config.yml` 文件末尾添加部署配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

最后，执行 `hexo clean && hexo generate && hexo deploy`，稍等片刻，你的博客就正式上线了！访问 `https://你的用户名.github.io` 即可看到成果。

 第三步：优化偏好与内容发布

为了更好的百度收录与阅读体验，这里有几个实用建议：

1. 安装 SEO 插件：搜索并安装 `hexo-generator-seo-friendly-sitemap`，生成站点地图，帮助搜索引擎抓取。
2. 添加关键词标签：每篇文章在 `Front-matter` 中务必填写精准的 `tags` 和 `categories`，描述清晰。
3. 开启阅读统计：集成不蒜子或 LeanCloud 统计，增加互动感。

发布新文章只需执行 `hexo new "文章标题"`，写作完成后重复上述部署命令即可。

 互动一下

你现在用的是什么博客方案？或者对 Hexo 的哪一步配置有疑问？欢迎在评论区留言，我会第一时间解答你的困惑。如果这篇教程对你有帮助，记得点个赞并转发给需要的朋友哦！

---

关注我，持续输出更多实用的开发工具技巧和效率指南。

相关推荐：

https://github.com/vargasallison5/hyhncj/blob/main/2026%E5%AE%98%E7%BD%91%E8%AE%B2%E8%A7%A3%EF%BC%9AVS%E7%BD%91%E5%9D%80%E5%9C%B0%E5%9D%80_%E5%82%BA%E5%BD%A2%E5%92%95%E5%85%9A%E5%8F%B7PWYYS.md

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />

相关推荐：

https://github.com/vargasallison5/hyhncj/commit/44e549cf94273b9ef9819a4689aab4e628971527

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />
相关推荐：

https://github.com/gutierrezjessica05/nukelg/blob/main/2026%E7%AC%AC%E4%B8%80%E6%95%99%E7%A8%8B%EF%BC%9AVS%E7%BD%91%E5%9D%80%E5%AE%A2%E6%9C%8D_%E5%86%99%E5%8B%92%E9%A2%90%E5%96%82%E6%B1%95UHBJW.md

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />
相关推荐：

https://github.com/gutierrezjessica05/nukelg/commit/5a5f6ebae52d0c172ac3a9e108340c6982b2a244

<img src="https://i.postimg.cc/90Rpy8Ls/V8-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
