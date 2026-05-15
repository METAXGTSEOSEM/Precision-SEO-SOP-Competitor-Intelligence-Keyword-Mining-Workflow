<div id="top" align="center">

# 🎣 精准 SEO 关键词挖掘与竞争对手逆向工程 SOP
### Precision SEO SOP: Competitor Intelligence & Keyword Mining Workflow

<p align="center">
  <img src="https://img.shields.io/badge/Strategy-Data--Driven-0052FF?style=for-the-badge&logo=google-analytics" />
  <img src="https://img.shields.io/badge/Focus-Competitor_Intelligence-FF4500?style=for-the-badge&logo=semrush" />
  <img src="https://img.shields.io/badge/Workflow-Standardized-brightgreen?style=for-the-badge&logo=githubactions" />
</p>

> **这是一套体系化的“降维打击”方案。** 我们不靠直觉猜词，而是通过挖掘种子数据、逆向透视头部同行、精细化清洗数据，构建一个具备极高转化率的利基词库。

</div>

<br/>

## 🗺️ 流程总览 (Workflow Map)

| 阶段 | 核心任务 | 关键产出 |
| :--- | :--- | :--- |
| **[01. 种子词库采集](#phase-1)** | 利用核心产品词开启“魔法探测” | 原始种子词列表 (.csv) |
| **[02. 竞争对手透视](#phase-2)** | 通过 Google 高级指令锁定真实对手 | 垂直竞品域名库 |
| **[03. 逆向词库提取](#phase-3)** | 扒取同行已排名的“黄金词汇” | 同行核心词库数据 |
| **[04. 数据清洗与筛选](#phase-4)** | 排除噪音，锁定低难度高意向利基词 | 精洗后的利基词库 |
| **[05. 语义聚类与布局](#phase-5)** | 将词库转化为网页内容架构 | 内容布局 Brief |
| **[06. 闭环监测与 GEO](#phase-6)** | 确保收录并适配生成式 AI 搜索 | GSC 报告与排名 |

---

<h2 id="phase-1">📦 01. 原始数据采集 (Keyword Research)</h2>

**目标：利用 Keyword Magic Tool 建立第一道数据护城河。**

1.  **种子词选取**：使用 1 个核心产品词（如 `industrial lift`）。
2.  **SEMrush 配置**：
    *   **Filter (Match Type)**：选择 `Phrase Match`（短语匹配）。
    *   **Database**：根据业务重心选择（默认 `US`）。
3.  **深度挖掘**：
    *   点击左侧侧边栏的 **Questions** 按钮，记录用户常问的痛点。
    *   导出时务必选择 `Full Export` 以保证 `KD%` 和 `Intent`（意图）字段完整。

---

<h2 id="phase-2">🔍 02. 同行精准挖掘 (Competitive Intelligence)</h2>

**目标：找到那些“正在闷声发大财”的中小型独立站。**

### 1. Google 搜索指纹 (Search Footprints)
在 Google 输入高级指令，寻找垂直竞争对手：
*   **按平台找**：`"Keyword" site:myshopify.com`
*   **按标题找**：`intitle:"Keyword" -amazon -ebay`
*   **按内容找**：`intext:"Keyword" "free shipping" "Add to cart"`

### 2. 批量自动化采集
*   使用 **SEO Minion** 或 **Ahrefs SEO Toolbar**。
*   将搜索结果翻页至 100 条。
*   一键 `Download SERP`，快速在 Excel 中形成域名清单。

<p align="right"><a href="#top">🔼 返回顶部</a></p>

---

<h2 id="phase-3">🕵️ 03. 竞品词库扒取 (Reverse Engineering)</h2>

**目标：看透同行的底牌，获取他们 80% 的流量贡献词。**

1.  **域名分析**：将竞品域名输入 SEMrush 的 `Organic Research`。
2.  **筛选器设置 (关键步)**：
    *   **Positions**：筛选 `Top 10`（对方排在首页的词才有参考价值）。
    *   **Keyword Type**：排除 `Branded`（对方的品牌词对我们没用）。
    *   **Volume**：设置为 `> 100`（过滤掉几乎没人搜的僵尸词）。
3.  **结果导出**：将这前 5 名核心同行的词库全部导出为 CSV。

---

<h2 id="phase-4">🧹 04. 表格合并与清洗 (Standard Cleaning)</h2>

**目标：解决乱码，统一格式，进行“去噪处理”。**

### 🛠️ 步骤 A：导入与编码纠正
*   **乱码处理**：导入 CSV 到 Excel 时，**文件原始格式**必须选择 `65001: Unicode (UTF-8)`。

### 🛠️ 步骤 B：去除干扰项
*   使用 Excel 的 `删除重复项`（Data -> Remove Duplicates），基于 `Keyword` 列。
*   **批量剔除无意义词根**：通过 `Ctrl + F` 查找并替换，或使用筛选器批量删除包含以下词根的行：
    *   `cheap`, `free`, `cracked`, `amazon`, `video`, `youtube` (除非你的业务相关)。

### 🛠️ 步骤 C：建立利基词库 (Niche Selection)
按照以下黄金比例进行筛选：

| 维度指标 | 筛选阈值 | 策略意义 |
| :--- | :--- | :--- |
| **KD % (难度)** | `< 29` | **非常容易**：个人站或新站可快速上首页 |
| **Intent (意图)** | `Commercial` / `Transactional` | 意图越准，询盘越高 |
| **Volume (流量)** | `> 50` | 保证有基础的搜索基数 |

---

<h2 id="phase-5">🏗️ 05. 页面语义聚类与布局 (Implementation)</h2>

**目标：不再是一个个堆砌关键词，而是建立“内容簇”。**

1.  **聚类 (Clustering)**：
    *   将 `custom lift table`, `bespoke lift tables`, `lift table custom design` 聚类。
    *   它们共用一个 **Product Page**。
2.  **布局策略**：
    *   **URL**：必须包含主利基词（例如 `/custom-lift-tables/`）。
    *   **H1**：直接采用利基词作为大标题。
    *   **GEO 优化 (Generative Engine Optimization)**：
        > 在段落首部增加一个 **Definition Box**（定义框），用 2 句话总结该产品，字数控制在 150 字符内，极大增加被 Perplexity 或 SearchGPT 引用的概率。

---

<h2 id="phase-6">🚀 06. 闭环监测与反馈 (Monitoring)</h2>

1.  **提交 URL 检查**：利用 GSC 的 `URL Inspection` 手动请求收录。
2.  **索引检测**：
    *   搜索 `site:yourdomain.com/your-url`。
    *   若 48 小时未收录，检查 `Robots.txt` 或 `Sitemap`。
3.  **KPI 跟踪**：
    *   每周查看 GSC 的 `Average Position`（平均排名）。
    *   若排名卡在 20-30 位，增加内链或引入一个高质量外链。

---

## 👨‍💻 关于本项目 (About)

这份 SOP 旨在为从事跨境贸易（B2B/B2C）及个人站长提供一套可复制的 SEO 执行标准。

- **开源协议**: MIT
- **更新日期**: 2026年5月

---
[⬅️ 回到顶部](#top)
