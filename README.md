# YFweb-multi-workflow
基于 HTML 的浏览器多窗口聚合与工作流管理工具；HTML-Based Browser Multi-Window Aggregation and Workflow Management Tool
⚡️ 网站多开工作流 (Web Multi-Workflow)

一个极简的浏览器多窗口聚合工作流工具。纯 HTML 实现，本地运行，安全无广告。

专为高效率人士设计，解决频繁切换标签页的痛点。支持一键启动 Gemini, DeepSeek, Claude 等常用 AI 模型，或自定义添加任何网页，构建你的专属多屏监控工作台。

🌟 核心特性

自定义工作流：支持 1-9 个窗口自动平铺布局，根据任务需求灵活调整。 快捷启动面板：内置主流 AI 工具快捷入口，点击即用。 零依赖运行：单文件 HTML 架构，无需安装 Node.js 或任何后台服务，双击即跑。 状态持久化：采用 URL Hash 技术记录工作台状态，收藏书签即可保存当前工作流布局。 沉浸式体验：一键切换全屏模式，专注于任务本身。

🚀 快速开始

由于浏览器的安全策略（CORS/Frame 限制），初次使用必须进行以下简单配置：

1. 解除浏览器嵌入限制 (必做) 本工具利用 iframe 聚合网页，需要安装插件以允许在本地环境中加载第三方网站。

安装 Chrome/Edge 扩展：Ignore X-Frame-Options Header。

进入扩展管理页 (chrome://extensions)。

找到该插件，点击“详细信息”。

✅ 开启 “允许访问文件网址 (Allow access to file URLs)”。

2. 运行

下载本项目中的 index.html 文件到本地。

直接双击打开。

3. 保存你的工作流 配置好你常用的 4 个或 6 个网站后，按 Ctrl + D 将当前页面保存为书签。下次点击书签，即可瞬间恢复所有窗口布局。

🛠️ 常见问题

Q: 为什么显示白屏/拒绝连接？ A: 请检查是否已安装插件，并务必开启“允许访问文件网址”权限。部分网站（如 Google Stitch 登录页）因极高安全策略无法嵌入，建议使用独立窗口。

Q: 数据会上传吗？ A: 绝对不会。所有数据均存储在你的本地 URL 和浏览器历史记录中，本项目没有任何后端服务器。

🤝 参与贡献 欢迎提交 Issue 反馈建议，或 Pull Request 贡献代码！
⚡️ Web Multi-Workflow
## 📧 联系与交流 (Contact)

如果你在使用中遇到问题，或者想交流极客玩法，欢迎联系我！

* **Email**: cyf1124906008@gmail.com
* **GitHub Issue**: 欢迎直接在仓库提交 Issue。
A minimalist multi-window browser workflow tool. Pure HTML implementation, runs locally, safe and ad-free.

Designed for high-efficiency individuals to solve the pain point of frequent tab switching. Supports one-click launch of popular AI models like Gemini, DeepSeek, and Claude, or custom web pages to build your exclusive multi-screen monitoring workbench.

🌟 Core Features

Custom Workflow: Supports auto-tiling layout for 1-9 windows, flexibly adjustable based on task requirements. Quick Launch Panel: Built-in shortcuts for mainstream AI tools, click and use instantly. Zero Dependency: Single HTML file architecture, no Node.js or backend services required, simply double-click to run. State Persistence: Uses URL Hash technology to record workbench state; bookmark the page to save your current workflow layout. Immersive Experience: One-click toggle for full-screen mode to focus on the task itself.

🚀 Quick Start

Due to browser security policies (CORS/Frame restrictions), a simple configuration is required for first-time use:

1. Lift Browser Embedding Restrictions (Mandatory) This tool uses iframes to aggregate web pages and requires an extension to allow third-party sites to load in a local environment.

Install Chrome/Edge extension: Ignore X-Frame-Options Header.

Go to the Extension Management page (chrome://extensions).

Find the extension and click "Details".

✅ Enable "Allow access to file URLs".

2. Run

Download the index.html file from this project to your local machine.

Double-click to open.

3. Save Your Workflow After configuring your frequently used 4 or 6 websites, press Ctrl + D to bookmark the current page. Next time you click the bookmark, your window layout will be instantly restored.

🛠️ FAQ

Q: Why do I see a white screen or "Connection Refused"? A: Please check if the extension is installed and ensure the "Allow access to file URLs" permission is enabled. Some websites (such as the Google Stitch login page) have extremely high security policies and cannot be embedded; it is recommended to use them in a separate window.

Q: Is my data uploaded? A: Absolutely not. All data is stored in your local URL and browser history. This project has no backend server.

🤝 Contribution Issues for feedback and Pull Requests for code contributions are welcome!
**📧 Contact**
Feel free to reach out for support or collaboration:
* **Email**: cyf1124906008@gmail.com
