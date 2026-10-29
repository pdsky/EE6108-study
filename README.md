# EE6108 学习站

NTU EE6108 Computer Networks 的中文自学网页：一份**学习手册**，一份**题库**。全部是单个 HTML 文件，双击就能在浏览器里打开，不用安装任何东西，离线也能用。

| 文件 | 内容 |
|---|---|
| `index.html` | **从这里打开**：入口目录 |
| `ee6108-learn.html` | 学习手册：Part I 全部 + Part II 网络层 II（CA2 Quiz 范围，标了「Quiz 考」「必背」）+ 传输层（上）；19 个交互实验 |
| `ee6108-practice.html` | 题库：CA2 Quiz 模拟卷 3 套、往年期末 5 卷全解、课件例题、随机刷题 |
| `old/` | 10 月 5 日的旧版单 Topic 页面，内容已并入学习手册 |

## 在 Windows 上打开

1. 打开 https://github.com/pdsky/EE6108-study ，点绿色的 **Code** → **Download ZIP**。
2. 在下载文件夹里**右键 ZIP → 全部解压缩**（一定要先解压；在压缩包里直接双击，页面之间的链接会失效）。
3. 进入解压出来的文件夹，**双击 `index.html`**，会用默认浏览器（Edge / Chrome）打开。

以后有更新：重新下载 ZIP 解压即可。如果装了 Git，也可以：

```bat
git clone https://github.com/pdsky/EE6108-study.git
cd EE6108-study
start index.html
```

更新时在这个文件夹里运行 `git pull`。

小提示：
- 有网时会加载 IBM Plex 字体，没网时自动用微软雅黑，内容不受影响。
- "已掌握"勾选、主题、上次打开的分区保存在浏览器本地；换浏览器或清除浏览器数据会重置。
- 题库里数值答案允许 ±0.5% 误差，百分数直接填数字。

## 在 Linux / macOS 上打开

```bash
git clone https://github.com/pdsky/EE6108-study.git
cd EE6108-study
xdg-open index.html      # macOS 用 open index.html
```

---
个人学习笔记，根据课程讲义、课堂录音和往年试卷整理，不是 NTU 官方材料；模拟卷是自己出的练习题。
