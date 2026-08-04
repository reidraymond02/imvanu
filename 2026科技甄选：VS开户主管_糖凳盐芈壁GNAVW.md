VS开户主管【Q-——333307——】VS开户主管【 辋芷《888yx●vip》 】
VS开户主管【Q-——333307——】VS开户主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是否想过拥有一个完全属于自己的技术博客？不需要购买服务器，不需要备案，甚至不需要花一分钱——GitHub Pages + Hexo 组合就能帮你实现。本文将手把手教你从零开始，搭建一个高性能、SEO友好的个人博客。

 为什么选择 GitHub Pages + Hexo？

GitHub Pages 提供免费静态托管，支持自定义域名和HTTPS，全球CDN加速访问。而 Hexo 作为Node.js驱动的静态博客框架，渲染速度极快，Markdown写作体验极佳，且拥有丰富的主题生态。

这套方案特别适合开发者、技术博主、产品经理等群体。相比WordPress，它更轻量、更安全；相比Jekyll，它配置更简单、主题更现代。

 环境准备（3分钟）

首先，确保你的电脑已安装：
- Git（版本管理工具）
- Node.js（建议v18+，自带npm）

验证安装成功：
```bash
git --version
node -v
npm -v
```

 三步完成博客搭建

 第一步：创建GitHub仓库
登录GitHub，新建仓库，命名为 `你的用户名.github.io`。注意：用户名必须和你的GitHub账号完全一致，否则无法访问。

 第二步：本地安装Hexo
打开终端，执行以下命令：
```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

 第三步：部署到GitHub
安装部署插件并配置：
```bash
npm install hexo-deployer-git --save
```
编辑 `_config.yml` 文件，在底部修改：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

最后执行：
```bash
hexo clean && hexo generate && hexo deploy
```

浏览器访问 `https://你的用户名.github.io`，你的博客已经上线了！

 让博客更专业：SEO优化技巧

1. 自定义域名：在仓库Settings的Pages选项中绑定你的域名
2. 关键词布局：在文章标题和正文中自然融入 `GitHub Pages`、`Hexo教程`、`静态博客` 等关键词
3. 提交收录：将站点添加到Google Search Console和百度站长平台

 进阶玩法与互动

你现在已经掌握了博客搭建的核心流程。接下来可以尝试：
- 更换喜欢的主题（推荐Next、Butterfly）
- 添加评论系统（Gitalk、Valine）
- 配置PWA实现离线访问

遇到问题？欢迎在评论区留言，我会第一时间解答。如果你成功搭建了自己的博客，记得分享你的博客链接，我会去参观学习！

行动建议：今天花15分钟完成搭建，周末开始你的第一篇技术文章吧。持续输出，你会发现写作是提升技术影响力的最佳方式。

---

关注我，获取更多开发者效率工具和副业变现技巧。觉得有用请点赞转发，让更多朋友学会搭建自己的技术博客！

相关推荐：

https://github.com/gallowayhoward8/ohrtks/blob/main/%E9%80%90%E5%85%89%E6%96%87%E9%9F%B5%E7%AD%91%E6%A2%A6%EF%BC%9AVS%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E6%8C%A0%E5%80%8C%E7%A3%B7%E9%A9%B6%E6%B1%9BDRZAU.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />

相关推荐：

https://github.com/gallowayhoward8/ohrtks/commit/208ca21e4708d92409f1cfcd243131b00da160ed

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />
相关推荐：

https://github.com/reidraymond02/imvanu/blob/main/2026%E6%9D%83%E5%A8%81%E6%80%BB%E7%BB%93%EF%BC%9AVS%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1_%E5%92%90%E5%95%84%E7%82%AF%E9%87%8F%E6%BD%AEMZMZU.md

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />
相关推荐：

https://github.com/reidraymond02/imvanu/commit/ab65187a3a935cb30c19bc212417862d5e97160c

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
