<div align="center">

# 🤖 AI Daily Digest

**你的专属 AI 情报官 · 每天自动推送到微信 · 零服务器 · 完全免费**

[![GitHub Stars](https://img.shields.io/github/stars/OliverZ-dot/ai-daily-digest?style=social)](https://github.com/OliverZ-dot/ai-daily-digest)
[![GitHub Actions](https://img.shields.io/badge/powered%20by-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.12](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)](https://www.python.org/)
[![WeChat](https://img.shields.io/badge/推送渠道-微信-07C160?logo=wechat&logoColor=white)](https://sct.ftqq.com)

<img src="https://img.shields.io/badge/每月成本-≈¥1~6-success?style=for-the-badge" alt="cost">
<img src="https://img.shields.io/badge/服务器-0台-success?style=for-the-badge" alt="no server">
<img src="https://img.shields.io/badge/运维-0小时-success?style=for-the-badge" alt="no ops">

</div>

---

## 😩 你是否也有这些困扰？

> *"每天 AI 领域信息爆炸，光 arXiv 一天就几百篇新论文，根本看不完。"*

> *"各种 newsletter 要么太泛，要么延迟一天，要么混着一堆广告。"*

> *"想关注某个细分方向的论文，但又不想错过行业大事件，两类内容总是混在一起。"*

> *"买了 RSS 阅读器，但最后都成了焦虑制造机——几百条未读，永远清不完。"*

这些，是每一个认真做 AI 的人的日常。

---

## 💡 我的解法：三轨并行，精准分发

**AI Daily Digest** 不是又一个信息聚合工具。它的核心设计理念只有一句话：

> **业界动态是业界动态，论文是论文，你的领域是你的领域——三件事，三条独立的轨道，互不干扰，全部呈现。**

### 传统工具的问题

几乎所有聚合工具都把所有的内容**混在一个列表里排名**：

```
1. 🔥 GPT-5 发布（公司新闻）
2. 🔥 某 RLHF 论文取得新突破（学术论文）
3. ⭐ OpenAI 获新一轮融资（商业动态）
4. ⭐ 扩散模型新架构（你的研究方向）
...
```

公司公告和你的研究方向用同一把尺子打分，谁高谁低？没有意义。

### AI Daily Digest 的方式

**三条独立轨道，各司其职，地位平等：**

| 轨道 | 内容 | 筛选逻辑 |
|------|------|----------|
| 📰 **业界动态** | 公司公告、融资、产品发布、政策合作 | 来源 × 关键词权重 × 时效性 |
| 🔬 **影响力论文** | 高质量学术论文，不管与你是否相关 | 通用学术关键词评分阈值 |
| 🎯 **细分领域** | 你的研究方向，哪怕影响力不高也要推 | 个人兴趣词匹配度优先 |

---

## ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🧠 **三轨并行架构** | 行业动态 / 影响力论文 / 细分领域，互不排名，各自完整呈现 |
| 📱 **微信直达** | Server酱推送，无需其余插件，手机微信即收 |
| 🤖 **LLM 中文摘要** | DeepSeek / GPT-4o / Claude 三选一，一句话点出核心信息 |
| ⚙️ **零代码个性化** | 只改 `user_config.yaml`，个人兴趣、推送时间、条目数全部可调 |
| 🔁 **智能去重** | 7天内看过的内容不再重复推送 |
| 🌐 **17+ 顶级信息源** | OpenAI、Anthropic、DeepMind、Meta AI、arXiv、量子位、机器之心… |
| 🆓 **完全免费运行** | GitHub Actions 免费额度 + Server酱免费计划，每月约 ¥1~6 |
| 📁 **Markdown 存档** | 每次推送自动保存到 `archive/`，本地全文检索 |

---

## 📱 推送效果预览

```
🌅 早间要闻 · 2026-XX-XX  共16条

📋 今日概述
今日 AI 领域最值得关注的是 Google DeepMind 发布 Gemini 2.5，
在推理任务上大幅领先前代；学术界则有多篇关于 RLHF 稳定性
和 mechanistic interpretability 的重要进展…

---

 📰 业界动态

1. Google DeepMind 发布 Gemini 2.5，推理能力全面超越 GPT-4o
   128K 上下文，代码、数学双提升，API 已开放。
   📰 Google DeepMind  🕐 3小时前  🔗 原文

2. Anthropic 完成 40 亿美元 C 轮融资，估值达 600 亿美元
   资金将用于扩大算力和安全研究团队。
   📰 TechCrunch AI  🕐 5小时前  🔗 原文

---

 🔬 影响力论文

1. Chain-of-Thought Reasoning 新基准：LLM 在竞赛数学上再创 SOTA
   提出 MathOlympiad-2K 数据集，最强模型正确率达 78.3%。
   📰 arXiv cs.AI  🕐 8小时前  🔗 原文

---

 🎯 细分领域

1. RLHF 训练不稳定性的根因分析：来自 reward hacking 的新证据
   通过机制可解释性工具定位了奖励模型中的 3 类系统性偏差。
   📰 arXiv cs.LG  🕐 12小时前  🔗 原文
```

---

## 🚀 快速上手（5 分钟，零服务器部署）

> 全程在 GitHub 网页操作，不需要本地安装任何东西。

### 第一步：Fork 本仓库

点击右上角 **Fork** 按钮，Fork 到你自己的 GitHub 账号。

### 第二步：获取 Server酱 SendKey

1. 打开 [sct.ftqq.com](https://sct.ftqq.com)，微信扫码登录
2. 进入「消息通道」→ 选择「微信服务号」→ 扫码关注
3. 复制页面顶部的 **SendKey**（格式：`SCT...`）

### 第三步：配置 GitHub Secrets

进入你 Fork 后的仓库 → **Settings → Secrets and variables → Actions → New repository secret**

| Secret 名称 | 值 | 说明 |
|------------|---|------|
| `DEEPSEEK_API_KEY` | `sk-...` | DeepSeek API Key（推荐，最便宜）|
| `SERVERCHAN_KEY` | `SCT...` | 第二步复制的 SendKey |

> 也可以用 OpenAI 或 Anthropic，见下方[切换 LLM](#切换-llm-提供商)

### 第四步：改一下你的研究方向（推荐）

直接在 GitHub 网页上编辑 `config/user_config.yaml`，把 `personal_interests` 换成你关注的方向：

```yaml
personal_interests:
  - "diffusion model"     # 改成你真正在意的
  - "embodied AI"
  - "code generation"
  # ...
```

### 第五步：手动触发，验证效果

仓库 → **Actions** → 选择 **早间要闻 0900** → **Run workflow**

等待约 1-2 分钟。微信收到消息 = 部署成功 🎉

此后每天 09:00 / 18:00 / 22:00（北京时间）自动推送，无需任何干预。

---

## ⚙️ 定制配置指南

所有个性化设置都在 `config/user_config.yaml` 完成，**无需改任何代码**。

### 修改推送时间

```yaml
schedule:
  - time: "08:00"          # 北京时间，改为你习惯的起床时间
    lookback_hours: 24     # 抓取过去 24 小时的内容
    label: "☀️ 早安要闻"
    enabled: true

  - time: "21:30"          # 新增一个睡前推送
    lookback_hours: 12
    label: "🌙 晚间精选"
    enabled: true
```

修改时间后，需要重新生成 GitHub Actions workflow 文件：

```bash
python scripts/gen_workflows.py
git add .github/workflows/
git commit -m "chore: update schedules"
git push
```

### 调整三轨条目数量和阈值

```yaml
tracks:
  industry:
    label: "📰 业界动态"
    max_items: 8           # 最多几条
    min_score: 3           # 最低综合评分

  impact_papers:
    label: "🔬 影响力论文"
    max_items: 5
    min_score: 8           # 提高此值可只保留高质量论文

  domain_papers:
    label: "🎯 细分领域"
    max_items: 5
    min_personal_score: 8  # 每命中一个 personal_interests 词 +8 分
```

### 添加新的 RSS 信息源

编辑 `config/sources.yaml`，按以下格式追加：

```yaml
  - name: "Cohere Blog"
    url: "https://cohere.com/blog/rss"
    priority: high             # critical / high / medium
    tags: ["official"]         # academic / official / media / community / chinese
```

### 只看学术来源 / 屏蔽噪音

```yaml
filter:
  include_tags: ["academic"]   # 只保留 arXiv 等学术源
  block_keywords:
    - "sponsored"
    - "crypto"                 # 屏蔽加密货币相关内容
```

### 修改关键词权重

编辑 `config/keywords.yaml`，将你关心的词加入更高权重层：

```yaml
keywords:
  critical:          # +10 分/个
    - "model release"
    - "your-keyword"   # 加在这里
  high:              # +5 分/个
    - "fine-tuning"
```

### 切换 LLM 提供商

**DeepSeek（推荐，最便宜）：**

```yaml
llm:
  provider: "deepseek"
  model: "deepseek-chat"
```

在 GitHub Secrets 中添加 `DEEPSEEK_API_KEY`。

**OpenAI：**

```yaml
llm:
  provider: "openai"
  model: "gpt-4o-mini"
```

在 GitHub Secrets 中添加 `OPENAI_API_KEY`。

**Anthropic Claude：**

```yaml
llm:
  provider: "anthropic"
  model: "claude-3-haiku-20240307"
```

在 GitHub Secrets 中添加 `ANTHROPIC_API_KEY`。

---

## 🖥️ 本地运行 & 二次开发

如果你想本地调试效果、修改代码、或添加新功能，按以下步骤操作。

### 环境要求

- Python 3.10 及以上
- pip

### 第一步：克隆仓库

```bash
git clone https://github.com/你的用户名/ai-daily-digest.git
cd ai-daily-digest
```

### 第二步：安装依赖

建议使用虚拟环境：

```bash
# 创建虚拟环境
python -m venv .venv

# macOS / Linux
source .venv/bin/activate

# Windows PowerShell
.\.venv\Scripts\Activate.ps1
```

```bash
pip install -r requirements.txt
```

### 第三步：配置 API Keys

```bash
cp .env.example .env
```

编辑 `.env`：

```dotenv
# 三选一
# OPENAI_API_KEY=sk-...
DEEPSEEK_API_KEY=sk-...
# ANTHROPIC_API_KEY=sk-ant-...

# 必填
SERVERCHAN_KEY=SCT...
```

> ⚠️ `.env` 已在 `.gitignore` 中，不会被提交到 Git。

### 第四步：运行

```bash
# 运行第 0 个时间段（schedule[0]，默认 09:00 早间要闻）
python main.py --schedule-index 0

# 运行第 1 个时间段
python main.py --schedule-index 1
```

**正常运行的输出：**

```
10:32:01  INFO  main        Running digest: 🌅 早间要闻  (lookback=24h)
10:32:01  INFO  src.fetcher  Loaded 17 sources after tag filtering
10:32:07  INFO  src.fetcher  Fetched 312 raw items
10:32:07  INFO  src.filter   Tracks — industry: 8, impact_papers: 4, domain_papers: 3
10:32:12  INFO  main        WeChat message sent: 🌅 早间要闻 · 2026-03-20 共15条
10:32:12  INFO  main        Done ✅
```

推送内容同时保存在 `archive/YYYY-MM-DD_HHMM.md`。

---

## 🏗️ 项目架构

```
ai-daily-digest/
├── .github/workflows/         # GitHub Actions 定时任务
│   ├── push_0900.yml
│   ├── push_1800.yml
│   └── push_2200.yml
│
├── src/
│   ├── fetcher.py             # 异步并发 RSS 抓取
│   ├── filter.py              # 去重 + 评分 + 三轨分流 ⭐
│   ├── summarizer.py          # LLM 中文摘要生成
│   ├── notifier.py            # Server酱 微信推送 + 三轨渲染
│   └── utils.py               # 工具函数、存档、去重持久化
│
├── config/
│   ├── sources.yaml           # 17+ RSS 信息源（含优先级和 tags）
│   ├── keywords.yaml          # 关键词权重表（三档）
│   └── user_config.yaml       # ⭐ 个性化配置（主要改这个）
│
├── scripts/
│   └── gen_workflows.py       # 从配置自动生成 workflow 文件
│
├── data/
│   └── seen_urls.json         # 已推送 URL 记录（7 天 TTL）
│
├── archive/                   # 每次推送的 Markdown 存档
├── main.py                    # 入口，编排六步流水线
├── requirements.txt
└── .env.example
```

### 三轨分流算法

```
所有 RSS 条目
     │
     ├── 时间窗口过滤（lookback_hours）
     ├── URL 去重（seen_urls.json）
     └── 屏蔽词过滤（block_keywords）
           │
           ▼
    ┌──────────────┐
    │ 按来源类型分流 │
    └──────────────┘
           │
     ┌─────┴──────────┐
     │                │
   非学术源          学术源（tag="academic"）
     │                │
     ▼          ┌─────┴──────┐
📰 业界动态     │            │
                ▼            ▼
           🔬 影响力论文  🎯 细分领域
            impact_score  personal_score
            （通用关键词）  （个人兴趣词）
```

**评分公式：**

```
业界动态 / 影响力论文:
  score = keyword_score × source_weight + recency_bonus
  keyword_score:  critical词 +10 | high词 +5 | medium词 +2
  source_weight:  critical=1.0 | high=0.8 | medium=0.5
  recency_bonus:  <3h +5 | <6h +3 | <12h +1

细分领域:
  personal_score = Σ(每个匹配的 personal_interests 词 × +8)
```

> 💡 一篇论文可以同时出现在「影响力论文」和「细分领域」——两条轨道完全独立，没有排名关系。

---

## 📊 信息源列表

| 来源 | 类型 | 优先级 |
|------|------|--------|
| OpenAI Blog | 官方 | 🔴 Critical |
| Anthropic News | 官方 | 🔴 Critical |
| Google DeepMind | 官方 | 🔴 Critical |
| Meta AI Blog | 官方 | 🔴 Critical |
| Hugging Face Blog | 官方/开源 | 🟡 High |
| Microsoft Research | 官方 | 🟡 High |
| Mistral AI | 官方 | 🟡 High |
| xAI Blog | 官方 | 🟡 High |
| arXiv cs.AI | 学术 | 🟡 High |
| arXiv cs.LG | 学术 | 🟡 High |
| TechCrunch AI | 媒体 | 🟢 Medium |
| VentureBeat AI | 媒体 | 🟢 Medium |
| MIT Technology Review | 媒体/学术 | 🟢 Medium |
| The Verge AI | 媒体 | 🟢 Medium |
| Hacker News AI | 社区 | 🟢 Medium |
| 量子位 | 中文媒体 | 🟢 Medium |
| 机器之心 | 中文媒体 | 🟢 Medium |

---

## 💰 成本说明

| 项目 | 费用 |
|------|------|
| GitHub Actions | **免费**（公开仓库无限制） |
| Server酱 | **免费**（每天 5 条，每次推送 1~2 条） |
| DeepSeek API（每次约 20k tokens） | **约 ¥0.03/次** |
| OpenAI GPT-4o-mini（同等规模） | **约 ¥0.2/次** |
| 服务器 / 域名 | **¥0** |
| **合计（每天 3 次推送，DeepSeek）** | **约 ¥3/月** |

---

## 🤝 Contributing

欢迎贡献！以下方向都很需要：

- 📡 **新增信息源**：在 `config/sources.yaml` 添加高质量 RSS，附上来源说明发 PR
- 🔌 **新推送渠道**：Telegram、Email、Slack、钉钉、飞书……
- 🧠 **改进摘要质量**：优化 `summarizer.py` 中的 prompt
- 🌍 **多语言支持**：目前摘要支持中/英，欢迎扩展
- 📊 **可视化存档**：将 `archive/` 生成为可浏览的静态网站

贡献前请先开 Issue 讨论方向，避免重复工作。

---

## 📄 License

[MIT](LICENSE) — 自由使用、自由修改、自由分发。

如果这个项目帮你节省了每天刷信息的时间，请点个 **Star ⭐** 让更多人发现它。

---

<div align="center">

**信息那么多，时间那么少。让机器帮你过滤，把时间留给真正重要的事。**

Made with ❤️ and ☕

</div>
