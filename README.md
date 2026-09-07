# 谢雨鑫的个人学术主页

基于 [HugoBlox Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv) 仓库，定制学术主页与研究详情布局。保留上游 MIT 许可。白底、深蓝强调色，无数据库与登录功能。

## 内容维护
- `data/portfolio.json`：论文、工程项目、Demo 和荣誉。
- `content/research/*/index.md`：研究项目详情（JSON 元数据 + Markdown 正文）。
- `layouts/home.html`：主页结构。
- `static/css/academic.css`：响应式样式。
- `static/images/profile.png`：头像。

使用 Hugo Extended 0.162.0、Go 和 pnpm。`pnpm install --frozen-lockfile --ignore-scripts` 安装依赖；`pnpm dev` 本地预览；`pnpm build` 输出静态网站到 `dist/`。

该版本的论文状态根据用户提供的 essay.txt 与最新说明整理。未公开论文文件、完整作者名单和 DOI 未补造。CNKD 在投；Frequency-View 作者位次乱码暂未纳入。所有实验数字均沿用所提供项目档案的口径。

博客和两个 Demo 使用原域名外链。当前不提供含个人手机号的简历下载；网站联系入口使用邮箱。
