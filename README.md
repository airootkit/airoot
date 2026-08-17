<div align="center">
<img src="favicon.ico" />

<H1>👋 Welcom to RunAIToolkit</H1>
    <p>
   <strong>免费、私密的 AI 实用工具 | RunAIToolkit</strong>
</p>
</div>

# 🚀 RunAIToolkit

[English](#english) | [中文](#中文)

---

<a name="english"></a>
## 🌐 English Description

### Fast, Private, Zero-Latency AI Micro-Tools Running 100% in Your Browser

[![Next.js](https://img.shields.io/badge/Next.js-14-black?logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.0-38B2AC?logo=tailwindcss)](https://tailwindcss.com/)
[![Deployment](https://img.shields.io/badge/Deployment-Cloudflare%20Pages-F38020?logo=cloudflare)](https://pages.cloudflare.com/)
[![Privacy](https://img.shields.io/badge/Privacy-100%25%20Client--Side-brightgreen)](#-privacy--architecture)

> 🔗 **Live Platform**: [https://runaitoolkit.com](https://runaitoolkit.com)

**RunAIToolkit** is a suite of lightweight, browser-first AI utilities designed for developers, prompt engineers, and digital creators. 

Unlike conventional utility sites that suffer from server latency, aggressive paywalls, or privacy risks, RunAIToolkit operates under a **100% client-side architecture**. All processing happens entirely inside your browser's local memory—**zero API calls, zero server logs, and absolute privacy.**

#### 🛠️ Featured Tools

1. **🧮 [AI Token & API Cost Estimator](https://runaitoolkit.com/tools/ai-token-calculator)**
   * Calculates exact token usage and estimates API costs across top LLMs (GPT-4o, Claude 3.5, DeepSeek R1).
   * Runs tokenization inside Web Workers to ensure butter-smooth UI performance.

2. **🧹 [Prompt & Markdown Cleaner](https://runaitoolkit.com/tools/prompt-markdown-cleaner)**
   * Instantly strips system artifacts, invisible unicode tags, and inconsistent markdown formatting from LLM outputs.
   * Delivers standardized, clean text ready for production codebases or secondary prompt chaining.

3. **✂️ [Midjourney & Flux Grid Splitter](https://runaitoolkit.com/tools/midjourney-grid-splitter)**
   * Slices 2x2 image grids from Midjourney, Flux, or Stable Diffusion into 4 high-res individual images.
   * Powered by local HTML5 Canvas (`ctx.drawImage`) with zero compression loss and zero upload wait times.

#### ⚡ Privacy & Architecture Highlights

* **Privacy-First by Design**: Prompts, API parameters, and image assets **never leave your device**. Perfect for handling NDA-restricted client data.
* **Zero Latency**: Powered by client-side JS engines and Web Workers to bypass cloud API roundtrips.
* **Edge-Accelerated Performance**: Built with Next.js App Router (`output: 'export'`) and hosted on Cloudflare's Anycast CDN with global TTFB under 50ms.
* **$0/Month Server Overhead**: Ensures long-term, free accessibility for the community without risk of shutdown.

<div align="center"><img src="img/en.png" /></div>
---

<a name="中文"></a>
## 🇨🇳 中文介绍

### 纯前端、零延迟的开发者与创作者 AI 微工具箱

> 🔗 **在线体验**：[https://runaitoolkit.com/zh/](https://runaitoolkit.com/zh/)

**RunAIToolkit** 是一个专为 AI 开发者、Prompt 工程师和数字创作者打造的轻量级、纯前端 AI 工具箱。

采用 **100% 浏览器端（Client-Side）架构**，所有计算与文本/图像处理均在本地内存完成，**零服务器响应等待，数据永不出本地**。

#### 🛠️ 核心功能组件

1. **🧮 [AI Token & API Cost Estimator](https://runaitoolkit.com/zh/tools/ai-token-calculator/)**：精准计算 Token 数量并估算主流 LLM（GPT-4o, Claude 3.5, DeepSeek R1 等）的 API 费用，Web Worker 本地处理不卡顿。
2. **🧹 [Prompt & Markdown Cleaner](https://runaitoolkit.com/zh/tools/prompt-markdown-cleaner/)**：一键清洗 LLM 输出中的冗余标记、不可见字符与 Markdown 伪影，输出标准化纯净文本。
3. **✂️ [Midjourney & Flux Grid Splitter](https://runaitoolkit.com/zh/tools/midjourney-grid-splitter/)**：基于本地 HTML5 Canvas 将 2x2 宫格图毫秒级切分为高清单图，质量零衰减。

#### ⚡ 优势摘要

* **绝对隐私**：100% 本地运算，商业敏感数据与图片永不上传第三方服务器。
* **极速响应**：基于 Next.js 静态导出并部署于 Cloudflare Pages 全球 CDN，首字节响应低于 50ms。

---

### 💬 Contact & Feedback

Suggestions or feature requests? Feel free to open an Issue or test live at [runaitoolkit.com](https://runaitoolkit.com/about/)!

<div align="center"><img src="img/zh.png" /></div>


