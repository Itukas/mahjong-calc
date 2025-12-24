# 🀄 日麻点数计算器 (Riichi Mahjong Calculator)

一个轻量级、针对移动端极致优化的网页版日本麻将点数计算器。单文件架构，无需后台，支持四麻与三麻。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## ✨ 主要功能

* **📱 移动端优先设计**：针对手机浏览器优化，禁止双击缩放，消除 300ms 点击延迟，操作跟手（iOS/Android 完美适配）。
* **🔢 智能符数面板**：
    * 当番数小于 5 番时，自动展开符数计算面板。
    * 支持详细的明刻、暗刻、幺九牌、雀头、听牌型录入。
    * 实时预览当前符数。
* **🧮 全面计算逻辑**：
    * 支持 **四人麻将** 与 **三人麻将** 模式。
    * 支持 **庄家/闲家** 切换。
    * 支持 **自摸/荣和** 自动计算点数分配（谁付多少点）。
    * 自动判定 满贯、跳满、倍满、三倍满、役满。
* **⚡ 轻量级**：纯 HTML/CSS/JS 单文件，无外部依赖，加载速度极快。

## 🚀 在线演示 (Demo)

> [!TIP]
> [点击这里使用计算器](https://Itukas.github.io/mahjong-calc/)

## 🛠️ 本地运行

无需安装 Node.js 或任何环境，只需下载即可使用。

1.  克隆或下载本仓库：
    ```bash
    git clone [https://github.com/你的用户名/你的仓库名.git](https://github.com/你的用户名/你的仓库名.git)
    ```
2.  进入文件夹，双击打开 `index.html`。
3.  或者在手机上通过文件管理器打开。

## 📦 如何部署 (免费)

本项目是一个纯静态网页，非常适合部署在 GitHub Pages。

1.  **Fork** 本仓库或上传代码到你的 GitHub。
2.  进入仓库的 **Settings** -> **Pages**。
3.  在 **Branch** 处选择 `main` 分支并点击 Save。
4.  等待 1 分钟，GitHub 会生成一个免费的 HTTPS 链接供你分享给朋友。

## 📝 代码结构

* `index.html`: 包含所有的 HTML 结构、CSS 样式和 JavaScript 逻辑。

## 📄 开源协议

MIT License
