# EE6108 学习站

NTU EE6108 Computer Networks (Part I) 的中文自学网页,零基础向:图文教程(生活类比 + 逐步推导 + 例题)、知识卡片、带解析的自测题、交互计算器。

| 文件 | 内容 |
|---|---|
| `index.html` | 入口目录 |
| `topic1.html` | Topic 1 计算机网络导论(时延、存储转发、分层协议…) |
| `topic2_1.html` | Topic 2.1 数据链路控制(流量控制、ARQ、Checksum、CRC…) |

纯静态 HTML,不依赖网络和任何外部库,离线即可使用。

## 在 Linux 上使用

```bash
git clone https://github.com/pdsky/EE6108-study.git
cd EE6108-study
xdg-open index.html
```

如果中文显示成方块,安装中文字体:

```bash
sudo apt install fonts-noto-cjk
```

以后有更新时:

```bash
git pull
```
