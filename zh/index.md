---
lang: zh
title: 首页
permalink: /zh/
---

### 关于我

我目前在哥伦比亚大学攻读计算机科学硕士学位，本科毕业于密歇根大学安娜堡分校，获计算机科学学士学位。我热爱 AI 工程、软件开发、UI/UX 设计与产品管理，擅长解决问题、沟通协作与自我挑战。

我正在积极寻找软件工程师（SWE）、前线部署工程师（FDE）与 AI 产品经理（AI PM）等新毕业生岗位。

欢迎通过邮箱联系我：orlandofang0511@gmail.com

### 项目

#### [Brandforge AI：多智能体品牌生成平台](https://orlandofang.github.io/BrandForge_AI--Multi-Agent_Brand_Generation_Platform/)

这是一个多智能体平台，可将用户描述转化为品牌人设、Logo 与营销策略，并支持异步并行生成。前端在 Figma Make 支持下使用 React 构建；后端使用 Python（Cursor 与 Claude 辅助开发），采用 FastAPI 与 MongoDB。系统架构包含 AI 网关智能体，负责任务分发给：生成并渲染 HTML 的网站智能体、具备前端能力的 Logo 智能体（生成 SVG/PNG），以及使用 RAG 提供广告投放方案（含平台推荐与合规限制）及 AI 生成海报的营销智能体。RAG 使用两类主要数据集：广告效果基准（CPC、CPM、CPA、CTR、转化率等）与平台政策语料；数据来自公开来源抓取。

AI 流水线包括结构化品牌画像抽取、基于网关的多智能体并行调度、RAG 检索、模板驱动规划与合规检查，并集成 OpenAI API。通过标准化智能体输出契约与部分失败容错提升可靠性，单个智能体出错不会导致端到端生成失败。这是基于我「创意 AI 智能体」想法的团队项目，我们共同实现并交叉审核。

#### [Book Cover Generator](https://hello-world-coms6998.vercel.app/) 与 [管理后台](https://coms6998-admin-portal.vercel.app/)（进行中）

正在开发一款 AIGC 应用，帮助用户生成书籍封面，并构建社区供用户分享与评分。使用 Vercel 部署 Next.js 前端，Supabase 作为数据库，Git 版本控制，Google OAuth 验证，Cursor 辅助开发。图像生成目前由 gpt-image-1-mini（含用量限制）支持，并以 sana 作为备选。

管理后台功能包括：概览（站点数据：PV/UV、AI 采用率、AI 成功率、用户旅程、评分分布、访问热力图等）、读者（用户信息）、AI 封面（用户帖子）、评分详情、Prompt 链与 Prompt 混合（编辑链路与权重）、示例（少样本提示）、术语（AI 专用术语）、生成媒体与请求（每次请求的状态、模型、时间、输入等）、LLM 响应（耗时、提示词、存储 URL 等）、提供商与模型、允许域名与邮箱白名单。管理后台对非超级管理员不可见。

#### [职业英雄联盟赛事探索性数据分析（Python）](https://orlandofang.github.io/most-exciting-league-in-league-of-legends/)

项目分析 2022 年英雄联盟职业赛事，数据来自 Oracle’s Elixir，包含超过 1 万场比赛。分析回答：在一级联赛中，哪个联赛的比赛最「精彩」？该联赛的「精彩程度」是否与其他联赛有显著差异？

步骤包括数据清洗、探索性分析、缺失评估与假设检验。

#### [职业英雄联盟赛事角色预测模型（Python）](https://orlandofang.github.io/league-of-legends-role-prediction/)

使用 2022 年职业赛事数据集，根据赛后数据预测选手位置。文中描述从基线模型迭代至未见过数据上准确率 96.2% 的过程，并进行公平性分析。

#### [影响航班延误因素的数据可视化（HTML、CSS、JS）](https://orlandofang.github.io/Flight_Delays/)

分析美国航班延误的各类影响因素，并找出较优的航空公司、机场与州。采用常见可视化，便于普通旅客理解；其中三个可视化支持交互。

注意：该页面处理超过 500 万行数据，加载可视化可能需要约半分钟。

### 联系方式

欢迎通过以下方式联系：

邮箱：orlandofang0511@gmail.com
