<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+%E7%AC%91%E6%98%A5%E9%A3%8E;CS+Graduate+Student;AI+Agent+%26+Knowledge+Base+Builder;30%2B+Claude+Code+Skills+%F0%9F%9B%A0%EF%B8%8F" alt="Typing SVG" />

</div>

---

### 👨‍💻 About Me

- 🎓 计算机研究生，专注大模型应用与 AI Agent 工具链
- 🔭 最近主线：**个人知识库工程化 · 双向手语无障碍沟通系统 · Agent 自动化工作流**
- 🌱 正在补强：深度学习推导、连续手语识别、GUI 工程、Skills / MCP / RAG 工具链
- 📊 副线项目：行业研究自动化（数据采集 → 10 章报告 → HTML/PDF → 发布）
- 💡 信条：*"工具不重要，思路才重要"*
- 📫 欢迎交流 AI Agent、Obsidian 知识库、手语识别原型、研报自动化

---

### 🛠 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=for-the-badge&logo=obsidian&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

### 📂 Projects

| Project | Description | Stack |
|---------|-------------|-------|
| 🧠 **xcf-personal-knowledge-base** | Obsidian 个人知识库工程化：学习笔记、市场调研、项目代码、研究生组会材料统一归档；为 Claude Code / Codex 编写多层 Agent 规范，并完成根目录描述与 GitHub 同步治理 | Markdown · Obsidian · Git · Claude Code |
| 🧏 **sign-language-accessibility-system** | 双向实时手语无障碍沟通原型：中文/语音 → 手语视频与骨架展示，手语视频 → 中文识别与 TTS；近期重点完成 PySide6 桌面 GUI、服务层适配、异步 Worker、组会汇报材料 | Python · PySide6 · OpenCV · MediaPipe · PyTorch |
| 📊 **market-research-automation** | 行业研究流水线：多源数据采集（Yahoo Finance + AkShare）→ 估值/财报/资金流/技术指标/风险定价 → 10 章报告 → HTML/PDF → 微信公众号发布 | Python · yfinance · AkShare · Playwright |
| 🤖 **LangChain-RAG-FastAPI-Service** | 基于 LangChain + FastAPI 的 RAG 知识库 API 服务 | Python · LangChain · FastAPI · Chroma |
| 🧬 **Agent-Rag-project** | AI Agent + RAG 综合项目，多 Agent 协作 + 向量检索 | Python · LangChain · Agent |
| 🐣 **hatch-succubus** | Codex 桌面宠物 — Q 版角色，8×9 精灵图集 + 9 组动画状态 + pet.json | Codex CLI · Higgsfield · Image Gen |

> 🔒 *知识库为私有仓库，仅展示项目概览*

---

### 🎯 Currently Learning

```text
Claude Code Skills 🛠   ███████████████████  95%
LangChain 🧬            ███████████████████  90%
RAG 📚                  ███████████████████  90%
AI Agent 🤖             ██████████████████░  88%
Frontend Design 🎨      ██████████████░░░░░  72%
Deep Learning 🧠        ███████████░░░░░░░░  55%
Financial Analysis 📈   ██████████░░░░░░░░░  50%
```

---

### 📝 Recently Shipped

#### 2026.07 — 双向手语无障碍沟通系统

- 做了一个可演示的 **PySide6 桌面端 GUI**：左侧中文/语音输入，中间真人手语视频与骨架同步展示，右侧上传/录制手语视频并识别回中文。
- 把 Web 端 `SignVideoApp` 封装成桌面服务层，GUI 直接调用本地能力，不依赖 HTTP 服务。
- 拆分了输入、候选、检索解释、舞台展示、反向识别等组件，并用 Worker 处理检索、ASR、识别、转码等后台任务。
- 梳理了系统边界：我的主要贡献集中在 `desktop/` 桌面端工程；`sign/`、模型与数据集作为上游能力接入。
- 为两次组会整理最终材料：
  - `260701组会-手语项目-GUI界面工作版.pptx`
  - `260708组会-二分类与神经网络训练推导.pptx`

#### 2026.07 — 个人知识库同步与治理

- 重整个人知识库根目录说明，把 `01-学习`、`02-市场调研`、`04-项目`、`07-研究生` 的职责边界重新写清楚。
- 清理 PPT 生成过程中的临时目录，把最终组会 PPT 迁移到 `07-研究生/组会/`。
- 全量同步个人知识库到 GitHub，同时排除数据集、模型权重、虚拟环境、`node_modules`、缓存和 100MB+ 大文件。
- 更新 `03-GitHub/` 目录规范，明确 GitHub Profile 子仓库独立维护，不混入主知识库 Git 历史。

#### 2026.06-07 — AI Agent / 研报自动化

- 持续使用 Claude Code / Codex 管理知识库工作流：素材整理、笔记生成、图表归档、README/索引同步、PPT 产物迁移。
- 搭建市场调研流水线：多源数据采集、行业横向对比、10 章研报、ABCDE 评级、HTML/PDF 输出和发布准备。
- 积累并使用多类 Skills：PPT 生成、行业报告、文档转换、网页文章、图像生成、前端设计、知识库检索等。

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=xiaochunfengbuxiao&color=3B82F6&style=flat-square)

*"The best way to predict the future is to invent it." — Alan Kay*

</div>
