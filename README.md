# 🎓 SheerID Verification Assistant

> **Automated Student Verification Solution.**
> 一个基于 Chrome Extension V3 的自动化验证工具，集成本地 API 注入与云端处理能力。

简单、快速、全自动。无需手动填写表单，插件自动完成从身份生成到云端验证的所有步骤。

## ✨ Features

* **Auto-Fill**: 自动生成并提交学生资料 (API-Level)。
* **Cloud Powered**: 复杂的凭证上传步骤由云端接管，成功率更高。
* **Smart Flow**: 自动识别并跳过 SSO 登录与人工审核页面。

## 📖 Installation (安装指南)

本插件未上架 Chrome 商店，需要通过“开发者模式”手动安装。

### 📥 1. 下载插件包
点击下方链接下载最新版本 (V3.5.0) 的 ZIP 压缩包，并解压到你的电脑上。

**[一键下载 SheerID自动验证.V3.5.0.zip](https://github.com/leon7482/SheerID-Tool/raw/main/Helper.V3.5.0.zip)**

### ⚙️ 2. 加载扩展程序
1.  **打开扩展管理**：在 Chrome 浏览器地址栏输入 `chrome://extensions/` 并回车。
2.  **开启开发者模式**：打开页面右上角的 **Developer mode (开发者模式)** 开关。
3.  **加载插件**：
    * 点击左上角的 **Load unpacked (加载已解压的扩展程序)**。
    * 选择你刚才解压的文件夹（确保文件夹内包含 `manifest.json` 文件）。
4.  **完成**：此时你应该能看到 "SheerID验证助手" 出现在列表中。

## 🛠 Usage (使用教程)

请严格按照以下步骤操作，以确保自动化流程正常运行。

### 第一步：准备验证环境
1.  **打开目标网站**：在浏览器中访问你需要验证的 SheerID 页面（例如 Spotify, YouTube Premium, 或是其他软件的学生优惠页）。
2.  **点击插件图标**：点击浏览器右上角的拼图图标 🧩，找到并点击 **"SheerID验证助手"**。

### 第二步：解锁云端权限 (重要)
为了防止滥用，启动任务前必须先通过人机验证。

1.  在插件弹出的窗口中，你会看到一个验证框（Turnstile Captcha）。
2.  **勾选验证框**，等待验证通过。
3.  一旦验证通过，底部的灰色按钮会变为 **蓝色的 "启动自动化验证"**。
    * *注意：如果按钮是灰色的，说明你还没通过上方的人机验证，无法点击。*

### 第三步：启动任务
1.  **确认链接**：插件通常会自动识别当前页面的 URL；如果没有，请手动粘贴 SheerID 验证页链接。
2.  点击 **"启动自动化验证"** 按钮。
3.  **请勿操作**：
    * 页面会自动刷新并开始运行。
    * 插件会自动接管后续流程。

### 第四步：激活 Gemini Advanced
1.  完成验证后，注册 **Google One AI Premium**。
2.  添加您的付款方式（免费期间不收费）。
3.  完成注册。

---

## 💎 Activate Gemini Advanced & Subscriptions (会员与高级功能)

本插件支持基础验证功能。如需开通**ChatGPT Plus**、**Cursor**、**Grok Ai** 等高级 AI 模型的付费权益，请按以下步骤操作：

1.  **Open Popup (打开面板)**: 点击浏览器右上角的插件图标 🧩。
2.  **Click Premium Button (点击充值)**: 点击 **"💎 各种Ai会员充值"** 按钮。
3.  **Support Channel (联系客服)**: 系统将自动跳转至官方服务通道，您可以在此：
    * 🚀 **Activate Gemini Advanced**: 获取高级 AI 模型的付费使用权限。
    * 💳 **Pay Subscription**: 开通高级 AI 模型的付费，如：**ChatGPT Plus**、**Cursor**、**Grok Ai** 等高级 AI 模型的付费权益。
    * 🔑 **Bulk Keys**: 获取批量验证的 API Key（针对开发者/工作室）。

## 🛡️ Security & Privacy (安全与隐私)

We take your security seriously. / 我们重视您的数据安全。

* **🔒 Local Execution (本地执行)**: 绝大部分页面交互（如点击、跳转）均在您的本地浏览器中完成，不依赖远程控制。
* **☁️ Minimal Data (最小化传输)**: 仅在最终验证阶段，必要的 Token 和身份数据会被发送至加密的云端接口 (`/api/run`)，**不会**记录您的浏览历史或无关数据。
* **🤖 Anti-Abuse (防滥用)**: 集成 Cloudflare Turnstile 验证，旨在防止恶意脚本滥用云端资源，确保服务长期稳定。

## ⚠️ Disclaimer (免责声明)

**This project is for educational and research purposes only.**
本项目仅供教育和研究使用。开发者不对使用本工具产生的任何后果负责。请遵守相关法律法规及目标网站的服务条款。

## 📄 License (许可证)

Distributed under the **MIT License**. See `LICENSE` for more information.

本项目基于 **MIT** 许可协议开源。

