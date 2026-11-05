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
├── blog.html           # 博客列表（分类筛选）
├── projects.html       # 项目
├── css/style.css       # Spectral + Jost，浅色默认，可切深色
├── js/particles.min.js # 本地 particles.js（三角形粒子）
└── CNAME
```

## 功能

- **关于** — 中文默认，可切英文；信念 / 喜欢 / 不喜欢
- **博客** — 技术 / 随笔 / 文章筛选，再点一次恢复全部。条目仍是占位，点击不会跳走
- **项目** — 三个可打开的 Demo（评测台、引溯、投放作战室），每条含 Demo 与 GitHub
- **导航** — 关于 / 博客 / 项目、GitHub、语言、浅色 / 深色，三页同一套
- **粒子背景** — 紫色三角形，配置写在页面里，不依赖额外 JSON

## 仍是占位的内容

- 邮箱 `hello@example.com`
- X 与 LinkedIn 仍是 `#`（仓库里没有真实地址）
- 博客标题是占位列表，还没有文章页
- 首页自我介绍沿用参考稿，没有编造年限或用户量

## License

个人项目，保留所有权利。
