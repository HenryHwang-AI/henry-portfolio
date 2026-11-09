# Henry · 个人网站

极简双语个人站，版式受 nathanchen.me 启发。纯 HTML / CSS / JavaScript，部署在 GitHub Pages 根目录，自定义域名为 henryai.cn。

## 预览

```bash
python3 -m http.server 8899
```

然后访问 <http://localhost:8899/>

## 目录结构

```
.
├── index.html          # 关于
├── blog.html           # 博客列表（技术 / 实践 / 随笔）
├── projects.html       # Agent 分层 + 三个 Demo
├── tools.html          # 工具栈
├── notes.html          # 笔记地图（卡片连到文章）
├── posts/              # 十篇双语文章
├── demos/              # 编排台、审批台、情报周报、镜语、实践年报
├── css/style.css       # Spectral + Jost，浅色默认，可切深色
├── js/particles.min.js # 本地 particles.js（三角形粒子）
└── CNAME
```

## 功能

- **关于** — 中文默认，可切英文；信念 / 喜欢 / 不喜欢
- **博客** — 十篇可打开的文章，技术 / 实践 / 随笔筛选，再点一次恢复全部
- **项目** — Agent 分层说明；站内 Demo 置顶：编排台、审批台、情报周报、镜语、实践年报。其后是三个外部 Demo（评测台、引溯、投放作战室），另有占位卡片
- **工具** — 效率、开发、知识、AI 清单
- **笔记** — 第二大脑主题地图；四张卡片连到站内文章，延伸阅读是公开站点
- **导航** — 关于 / 博客 / 项目 / 工具 / 笔记、GitHub、语言、浅色 / 深色
- **粒子背景** — 紫色三角形，配置写在页面里，不依赖额外 JSON

## 仍是占位的内容

- 邮箱 `hello@example.com`
- X 与 LinkedIn 仍是 `#`（仓库里没有真实地址）
- 部分项目卡片还没有真实目的地
- 首页自我介绍沿用参考稿，没有编造年限或用户量

## License

个人项目，保留所有权利。
