# happy
个人项目｜旅行攻略、出行笔记

**站点**：https://JChengc.github.io/happy/

## 目录结构
按目的地组织，`docs/` 即 GitHub Pages 站点（无需额外源文件副本）：

```
docs/
├── index.html        # 导航首页（https://JChengc.github.io/happy/）
└── xinjiang/         # 新疆攻略（https://JChengc.github.io/happy/xinjiang/）
    ├── index.html    # 反走北疆 + 伊犁大环线 · 2026 深秋 13 天自驾
    └── assets/images/
```

新增目的地：新建 `docs/<目的地>/index.html`（图片用相对路径 `./assets/images/`），并在首页卡片加链接即可，例如土耳其 → `docs/tuerqi/`。

## 部署
GitHub Pages：`main` 分支 → `/docs`。改动 push 后约 1 分钟生效。
