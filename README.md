# 👋 Hi, I'm wzf9

**`AI-driven Data Detective · Open Source Explorer · Trend Hunter`**

---

### 🌟 About Me / 关于我

**English**  
I'm obsessed with using AI to uncover hidden signals in the GitHub universe – spotting rising stars before they explode, and hunting down anomalies like malware campaigns.  
Think of me as a **data detective** who lets the numbers tell the story.

**中文**  
我痴迷于用 AI 挖掘 GitHub 世界中的隐藏信号 —— 在项目爆发前发现潜力股，并追踪像恶意软件攻击这样的异常行为。  
你可以把我看作一名 **数据侦探**，让数字自己说话。

---

### 🛠️ Tech Stack / 技术栈

- **Languages**: Python, TypeScript, PowerShell
- **AI / Data**: OpenAI API, GitHub API, Scikit‑learn, Pandas
- **Tools**: Git, GitHub Actions, Jupyter, VS Code

---

### 📊 GitHub Stats

![wzf9's GitHub stats](https://github-readme-stats.vercel.app/api?username=wzf9&show_icons=true&theme=radical)

---

### 📫 Let's Connect / 联系我

- **Email**: bestlifetmp@outlook.com  
- **GitHub**: [github.com/wzf9](https://github.com/wzf9)


## 🔍 GitHub Hunter – Local Edition

> **提前 24 小时锁定下一个开源爆款**

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.13+-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/DuckDB-Powered-fff0d4?logo=duckdb&logoColor=000">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg">
  <img src="https://img.shields.io/badge/Data-24h_Sliding_Window-2ea44f">
</p>

这是一套**不依赖任何云服务**的本地化工具链，通过对 GitHub 全量事件流进行小时级增量分析，在项目爆发前 24 小时锁定潜力黑马。

---

### ✨ 核心亮点

- **零云成本**：不依赖 BigQuery / GCP / AWS，只需 Python + 公网访问[reference:0]
- **小时级增量**：首次约 600MB 流量，后续增量仅 ~30MB / 次[reference:1]
- **多维榜单**：24 小时滑窗榜 / 加速度榜 / 连续高速增长榜 / 幽灵仓库黑名单[reference:2]
- **全量数据回溯**：本地累积 1 年 hourly 倒排索引，支持任意日期的 Top / Star 曲线分析[reference:3]

---

### 🚀 快速开始

```bash
git clone https://github.com/wzf9/github-hunter-local
cd github-hunter-local

# 创建虚拟环境（推荐）
uv venv --python 3.13.1
.venv\Scripts\activate

# 安装依赖并运行
uv pip install -r requirements.txt
python main.py   # 首次会自动引导配置 GH_TOKEN
---

⭐ *If you're into finding gems before they shine – give me a star!*  
⭐ *如果你也喜欢提前发现宝藏项目，欢迎点个 Star ～*
