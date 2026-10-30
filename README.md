# EE6108 学习站

NTU EE6108 Computer Networks 的中文自学网页：一份**学习手册**，一份**题库**。

## 在线阅读（直接点开，不用下载）

**入口：https://pdsky.github.io/EE6108-study/**

| 直接打开 | 内容 |
|---|---|
| [学习手册](https://pdsky.github.io/EE6108-study/ee6108-learn.html) | Part I 全部 + Part II 网络层 II（CA2 Quiz 范围，标了「Quiz 考」「必背」）+ 传输层（上）；19 个交互实验 + 6 个 Quiz 动画（每个都配小白版说明和例题） |
| [题库](https://pdsky.github.io/EE6108-study/ee6108-practice.html) | CA2 Quiz 模拟卷 4 套、往年期末 5 卷全解、课件例题、随机刷题 |
| [Quiz 模拟卷](https://pdsky.github.io/EE6108-study/ee6108-practice.html#mock) | 4 套模拟卷（D 卷和真 Quiz 一样长），带翻译、讲解、评分要点、举一反三 |
| [网络层 II（Quiz 范围）](https://pdsky.github.io/EE6108-study/ee6108-learn.html#n2) | 转发与路由、路由器结构、Dijkstra、DV、RIP/OSPF/BGP、SDN |
| [老师关于 Quiz 的原话](https://pdsky.github.io/EE6108-study/ee6108-learn.html#n2-said) | Week 8–11 课上录音 + Quiz 通知邮件里的要点 |
| [Quiz 答题模板](https://pdsky.github.io/EE6108-study/ee6108-learn.html#n2-s9) | 计算题步骤模板 + 18 道问答题的答题要点 |
| [热土豆 / BGP 动画](https://pdsky.github.io/EE6108-study/ee6108-learn.html#qb-n7-hot) | 一步一步讲热土豆，四种情况可切换 |

手机、平板、Windows、Mac 的浏览器都能直接打开。网页更新后刷新一下就是最新版（偶尔要等一两分钟）。

## 离线用（Windows）

没网的时候也想看，就下载一份到电脑上：

1. 打开 https://github.com/pdsky/EE6108-study ，点绿色的 **Code** → **Download ZIP**。
2. 在下载文件夹里**右键 ZIP → 全部解压缩**（一定要先解压；在压缩包里直接双击，页面之间的链接会失效）。
3. 进入解压出来的文件夹，**双击 `index.html`**，会用默认浏览器（Edge / Chrome）打开。

以后有更新：重新下载 ZIP 解压即可。如果装了 Git，也可以：

```bat
git clone https://github.com/pdsky/EE6108-study.git
cd EE6108-study
start index.html
```

更新时在这个文件夹里运行 `git pull`。Linux / macOS 用 `xdg-open index.html` / `open index.html`。

## 文件

| 文件 | 内容 |
|---|---|
| `index.html` | 入口目录 |
| `ee6108-learn.html` | 学习手册 |
| `ee6108-practice.html` | 题库 |
| `old/` | 10 月 5 日的旧版单 Topic 页面，内容已并入学习手册 |

全部是单个 HTML 文件，不用安装任何东西。

小提示：
- 有网时会加载 IBM Plex 字体，没网时自动用微软雅黑，内容不受影响。
- "已掌握"勾选、主题、上次打开的分区保存在浏览器本地；换浏览器或清除浏览器数据会重置。在线版和离线版的进度是分开记的。
- 题库里数值答案允许 ±0.5% 误差，百分数直接填数字。

---
个人学习笔记，根据课程讲义、课堂录音和往年试卷整理，不是 NTU 官方材料；模拟卷是自己出的练习题。
