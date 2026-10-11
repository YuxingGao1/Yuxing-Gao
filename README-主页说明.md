# Yuxing Gao 个人主页

基于当前仓库的 al-folio 官方模板，保留 Jekyll 和插件版本。所有缺少的个人信息明确标为待填写。

## 发布

当前网址配置为 https://YuxingGao1.github.io/Yuxing-Gao/ 。这是预期发布地址，尚未验证上线。

将文件更新到仓库 main 分支后，等待 Actions 的 Deploy site 成功。在仓库 Settings → Pages 中选择 Deploy from a branch，选择 gh-pages 分支和 / (root)，保存。部署工作流会生成 gh-pages 分支。

## 修改个人资料

- 姓名、网站地址：_config.yml。
- 简介与研究方向：_pages/about.md。
- 教育经历：_pages/education.md。
- 邮箱与社交链接：_data/socials.yml 和 _pages/contact.md。
- 照片：将个人照片放入 assets/img/，再修改 about.md 的 profile.image。
- 新闻：_news/ 中添加日期对应的 Markdown 文件。
- 论文：_bibliography/papers.bib 添加真实条目，删除 publications.md 的待添加提示。

模板中的演示博客、书籍、项目和其他演示页面通过配置排除，不会发布。未添加模板人物的经历或论文。

本地完整构建需要 Ruby / Bundler，运行 bundle install、npm ci、bundle exec jekyll serve。访问 http://localhost:4000/Yuxing-Gao/。

当前环境缺少 Ruby，完整 Jekyll 构建尚未验证。独立预览仅用于查看布局和内容，不代表主题构建结果。
