# EE6108 学习站

NTU EE6108 Computer Networks 的中文自学网页：一份**学习手册**，一份**题库**。

## 在线阅读（直接点开，不用下载）

**入口：https://pdsky.github.io/EE6108-study/**

| 直接打开 | 内容 |
|---|---|
| [学习手册](https://pdsky.github.io/EE6108-study/ee6108-learn.html) | Part I 全部 + Part II 网络层 II（CA2 Quiz 范围，标了「Quiz 考」「必背」）+ 传输层（上、下：rdt、TCP、拥塞控制）+ 应用层（HTTP、P2P）+ 网络安全（加密）；18 个交互实验 + 10 个动画 |
| [题库](https://pdsky.github.io/EE6108-study/ee6108-practice.html) | 往年期末 5 卷全解（每题有背诵版，Part II 附老师官方答案要点）、期末模拟卷 2 套、CA2 Quiz 模拟卷 5 套、课件例题、随机刷题 |
| [概念题背诵卡](https://pdsky.github.io/EE6108-study/ee6108-practice.html#cards) | 116 张简明答案（期末 Part I 概念 + 公式方法、P2A、TCP、应用层、安全），英文关键句 + 中文翻译，可以遮住答案自测 |
| [模拟卷](https://pdsky.github.io/EE6108-study/ee6108-practice.html#mock) | **期末模拟卷 2 套**：F + H、G + I（F、G = Part I 的 Q1 + Q2，H、I = Part II 的 Q3 + Q4），按往年期末题型出；另有 CA2 Quiz 模拟卷 A–E。都带翻译、背诵版、讲解、评分要点 |
| [网络层 II（Quiz 范围）](https://pdsky.github.io/EE6108-study/ee6108-learn.html#n2) | 转发与路由、路由器结构、Dijkstra、DV、RIP/OSPF/BGP、SDN |
| [老师关于 Quiz 的原话](https://pdsky.github.io/EE6108-study/ee6108-learn.html#n2-said) | Week 8–11 课上录音 + Quiz 通知邮件里的要点 |
| [Quiz 答题模板](https://pdsky.github.io/EE6108-study/ee6108-learn.html#n2-s9) | 计算题步骤模板 + 18 道问答题的答题要点 |
| [热土豆 / BGP 动画](https://pdsky.github.io/EE6108-study/ee6108-learn.html#qb-n7-hot) | 一步一步讲热土豆，四种情况可切换 |

### 期末模拟卷（12 月 1 日期末，4 题各 25 分）

| 套 | Part I（Q1 + Q2） | Part II（Q3 + Q4） |
|---|---|---|
| 第 1 套 | [F 卷](https://pdsky.github.io/EE6108-study/ee6108-practice.html#mock)：ALOHA / CSMA 效率、存储转发最优分组、停等 ARQ + BER；checksum vs CRC、两个 C 类网的 VLSM | H 卷：距离向量无穷计数 + 毒性逆转、分组 ARQ 利用率、TCP 序号与快速重传；HTTP 响应 + cookie、BitTorrent 乐观疏通、乘积密码、Diffie–Hellman 与中间人 |
| 第 2 套 | G 卷：DHCP、分片（含二次分片）、路由汇总 + VLSM；二维奇偶校验 + CRC、生成树、选择重传 | I 卷：BGP 选路 + 热土豆、带 NAK 的停等 FSM 与利用率；TCP Reno cwnd、Web 缓存、C/S vs P2P 分发时间、Vigenère 已知明文攻击 |

在题库「模拟卷」分页点卷名切换；期末卷的计时器是 90 分钟（半套），每道小题先给背诵版，完整解答折叠在下面。

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
