VS网址娱乐【Q-——333307——】VS网址娱乐【 辋芷《888yx●vip》 】
VS网址娱乐【Q-——333307——】VS网址娱乐【 辋芷《888yx●vip》 】

 手把手教你用 GitHub Pages 部署个人网站（2025 最新版）

你是否想过拥有一个完全免费、无广告、可自定义的专属网站？  
很多人第一反应是买服务器、备案域名，其实 GitHub Pages 就能轻松搞定。  
今天这篇教程，我将带你从零开始，10 分钟上线个人主页，全程无需命令行基础。

 为什么推荐 GitHub Pages？

- 完全免费：静态托管不花一分钱，支持 HTTPS。
- 自带版本管理：每次更新都留痕，写博客、放简历不怕丢。
- SEO 友好：百度可正常收录，适合个人品牌建设。
- 无限流量：不限制带宽，国内访问速度尚可。

 核心操作三步走

 第一步：创建专属仓库
登录 GitHub，点击右上角 `+` → New repository。  
仓库名必须填 `用户名.github.io`（例如 `zhangsan.github.io`），选择 Public，勾选 `Add a README file`，点击创建。

> ⚠️ 注意：仓库名不匹配，Pages 服务不会自动启用。

 第二步：开启 Pages 服务
进入仓库 → `Settings` → 左侧找到 `Pages`。  
在 Build and deployment 下，Source 选择 `Deploy from a branch`，Branch 选 `main`，文件夹选 `/ (root)`，点击 Save。

等一分钟，页面顶部会出现你的专属网址，部署成功。

 第三步：更换网页内容
最简单的方式：点击仓库里的 `README.md` 文件 → 铅笔图标编辑 → 直接改文字或粘贴 HTML 代码 → `Commit changes`。

想用现成模板？推荐 Jekyll 主题，在仓库根目录新建 `_config.yml`，写入：
```yaml
theme: jekyll-theme-cayman
```
保存后自动换肤，支持 Markdown 写作。

 进阶技巧：绑定自定义域名

如果你有自己的域名，在仓库 `Settings` → `Pages` 的 Custom domain 里填上域名，再按提示去 DNS 解析处添加 `CNAME` 记录指向 `用户名.github.io` 即可。百度对绑定了独立域名的站点收录权重更高。

 互动引导

你学会了吗？如果卡在第二步的 Pages 选项是灰色，多半是仓库名写错了，检查下再来问我。  
评论区留下你的博客链接，我会挑选 3 个优质站点，免费帮你检查 SEO 收录状态。  
觉得有用的话，点个 Star 支持一下吧，后续我会更新「用 Hugo 搭建博客」和「提交百度收录」系列教程，关注不迷路。

相关推荐：

https://github.com/millerdonna9312/pwnxnv/blob/main/2026%E7%A7%91%E6%8A%80%E7%A7%91%E6%99%AE%EF%BC%9AV8%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91_%E8%83%80%E6%8E%B7%E9%95%9C%E9%97%BB%E8%8A%B3ZTAVW.md

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />

相关推荐：

https://github.com/millerdonna9312/pwnxnv/commit/f57838d199530f58df06df2cb5b6a10f8b072e38

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />
相关推荐：

https://github.com/nguyenmark0/dznovc/blob/main/2026%E5%AE%98%E7%BD%91%E7%94%84%E9%80%89%EF%BC%9AV8%E6%B3%A8%E5%86%8C%E6%B3%A8%E5%86%8C_%E8%8C%81%E9%85%B1%E5%9A%8E%E6%80%80%E8%BE%9BFLGGB.md

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />
相关推荐：

https://github.com/nguyenmark0/dznovc/commit/e1364619ce30186e3778325460e4f010baa9ce03

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
