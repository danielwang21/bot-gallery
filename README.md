# QQ AI 好友 · 全图鉴

移动端展示页，用于展示各个 QQ AI Bot。纯静态网页，可直接部署。

## 目录结构

```
.
├── index.html      # 主页面（所有 bot 数据在内联的 bots 数组中）
├── images/         # bot 头像
└── fonts/          # 本地字体
    ├── YongSong.woff2   # 造字工房咏宋体（标题「QQ AI好友」+ bot 名字）
    └── YuYue.woff2      # 造字工房瑜悦体（「全图鉴」）
```

## 使用

直接用任意静态服务器打开 `index.html` 即可，例如：

```bash
python3 -m http.server 8080
# 浏览器访问 http://localhost:8080
```

## 修改 bot

编辑 `index.html` 中的 `bots` 数组即可增删或改名、换头像、改简介，所有卡片当前统一跳转到同一个 QQ 频道机器人分享链接。
