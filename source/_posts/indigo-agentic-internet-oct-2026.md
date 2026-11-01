---
title: "Indigo 10月末直播总结：向 Agentic Internet 进化"
date: 2026-11-01 12:00:00
categories:
  - AI
tags:
  - Agentic Internet
  - RSI
  - 具身智能
  - AI for Science
  - 投资
---

> 来源：[Indigo 2026 年 10 月末直播](https://www.youtube.com/watch?v=KW02EUe5LjY) 的文字总结。  
> 本文基于直播笔记整理，未对原始视频中的公司披露、数据和研究结论做外部核验，更适合作为快速建立框架的阅读提纲。

## 一句话结论

这期直播把近期 AI 的变化串成一条线：互联网正在从“给人用”变成“给 Agent 用”，商业逻辑、基础设施、公司组织、科研范式和财富分配都会因此重写。对个人而言，最重要的不是学会更多工具，而是更早建立自己的 Agent Loop，并保留只有真实经验才能形成的判断力与独特视角。

<!-- more -->

## 一、时代坐标：从软件替代文书，到 Token 替代劳动

直播用 Coatue 的时代演进图做了一个很简洁的定位：

1. 农耕代替狩猎。
2. 机器代替体力。
3. 软件代替文书。
4. 现在进入 **“Tokens Replace Work”：Token 开始替代一部分脑力劳动。**

过去软件解决的是流程化、确定性高的工作；现在模型开始参与判断、执行、搜索、写作、写代码，甚至参与科研。变化不是“AI 更聪明了一点”，而是整个协作结构开始绕开传统的人机界面。

## 二、Agentic Internet：互联网的下一层操作系统

### 1. 流量主人都变了

直播提到，Cloudflare 的观察是：2026 年 5 月，Agent 发起的互联网访问请求已经提前超过人类。更长远的预测是，五年后每 1000 次互联网访问里可能有 999 次由 Agent 发起。

这意味着网站、搜索、API、电商、SaaS，都要重新思考一个问题：

> 当主要访客不是人，而是一个会自动执行任务的 Agent 时，你的产品还要怎样设计？

### 2. 硬件重心从 GPU 回摆到 CPU、SSD、带宽和 VPS

直播里的框架很清楚：

- **大模型负责决策，吃 GPU。**
- **Agent 负责执行、读写网页、调用 API、操作电脑，吃 CPU、存储和网络。**

所以未来不仅仅是“更贵的显卡生意”，还会出现大量围绕云 VPS、沙箱、合规执行环境和个人工作站的基建需求。

### 3. 从“搜索引擎抓取”到“Agent 主动通信”

网站被低频人类访问时，搜索引擎爬取还可以接受。但当海量 Agent 反复读取网页，传统抓取结构会被压垮。

解决方向有两个：

- **降负载**：网站前置 Agent 与模型背后的 Agent 直接通讯、推送，而不是被动重复抓取。
- **Agentic Payment**：让 Agent 在读取内容或调用 API 时自动协商并完成付费。

这本质上是给互联网加一层“可自动结算、可被机器理解”的协议。

### 4. 三层 Agentic Infra

直播用 OpenAI 新版 Agent API 举例，把基础设施拆成三层：

| 层级 | 内容 | 代表 |
|---|---|---|
| 顶层 | 模型 + 框架 | Codex、Claude Code |
| 中间层 | 云上安全沙箱、虚拟电脑、算力、存储、合规 VPC | Cloudflare、Modal、Vercel |
| 底层 | 开发者本地工具、知识库、工作流 | 个人和企业自己的 Agent 配置 |

这很像个人电脑时代的应用层、操作系统层、硬件层。AI 时代的“Agent OS”正在成型。

### 5. “构建公司就是构建 Agent”

这是本期我最喜欢的一句总结。

直播引用 Anthropic 工程数据：单纯让 Agent 执行任务，满分率只有 21%；但加上更强模型当顾问、事后复盘，以及夜间 **Dreaming（记忆整理和修剪）**，成绩可以提升到 70 多分。

也就是说，真正有战斗力的不是“一个会调用工具的聊天机器人”，而是一个：

> 执行 → 回顾 → 记忆整理 → 重新部署 → 再执行 的 **Agent Loop**。

传统流水线里，人类站在流程中间；Agent Loop 里，人类开始站到循环之外。

### 6. 电商不是被吃掉，而是被激发

Shopify CEO Tobi 的观点被直播作为例子：Agent 接管繁琐流程后，很多原本因为“太麻烦”而放弃的需求会被激发出来。比如智能烤箱自动订购食材、3D 打印机自动补充耗材。

直播的判断是，这可能不是电商缩水，而是整个市场盘子扩大约 50%。

## 三、Personal Agent：新一代 Agent OS 的入口战争

### 1. 主流个人代理的两种路线

- **Meta Muse**：面向普通人，对话简单、功能贴心。
- **GrokBot**：面向极客，免费访问 X 数据，支持多模型路由，比如调用 Gemini 绘图、Opus 校验。

此外还有 Claude Duet、OpenAI Dot、Gemini Spark、Instinct、OpenClaw、Hermes 等。

直播把市场分成三块：

| 战场 | 特征 |
|---|---|
| Consumer | Meta 眼镜与苹果手机的入口争夺 |
| Pro User | 专业用户本地与云端混合闭环 |
| Enterprise | 最复杂、最大，但流程重构也最难 |

### 2. 协议才是真正的护城河

个人 Agent 时代不会只有一家公司。更可能是一堆 Agent 之间互相通信。直播把几个协议放在一起：

- **MCP**：Anthropic 的工具调用协议。
- **A2A**：Google 的 Agent 间委派协议。
- **PAP**：Meta 与 Sierra 发布的 Personal Agent Protocol。
- **A2P**：支付协议。

这些协议拼起来，就是未来“Agent Internet”的 HTTP。

### 3. Agent 路由权成为商业新战场

人类会冲动、会嫌麻烦、会信息不对称。极度理性的 Agent 会消灭很多“利用有限理性赚钱”的商业模式，比如低息存款、搜索广告、默认推荐。

下一步的争夺不是“谁的页面更吸引人”，而是：

> 用户 Agent 默认把任务路由给谁。

直播提到 Stripe 收购 OpenRouter，就是这种逻辑的体现。

## 四、RSI：模型训练模型的左脚踩右脚

### 1. Anthropic 的 RSI 时间表

直播引用 Vals AI 的数据：

- Anthropic 预计在 **2027 年 7–8 月**达到完全 RSI，即模型能自我改进所有研发环节。
- 目前 RSI 增速最快的是 **Google Gemini**。
- Claude Opus 5.5 在 OpenRouter 调用量上占优。
- Anthropic 内部已有 26% 研发工作由 Claude 主导，部分系统工程师 99% 代码由 AI 编写。

### 2. 算力内倾：前沿实验室把更多资源留给自己

直播提到 Anthropic S1 报告的一个关键变化：

> 前沿实验室开始把更多算力从外部推理，转向内部训练和研发。

这形成两个飞轮：

- **投资循环**：外部推理赚钱，再去投入算力。
- **改进循环**：内部用算力训练出更强的模型。

结果就是头部模型之间拉开代差，也维持高溢价定价权。

### 3. RSI 的演进路径

当前 RSI 还是“软件演化”：

> LLM + Coding Agent，优化代码、工具链和工作流。

终局则是“硅基循环”：

> 软件循环 + 硬件闭环，AI 直接参与芯片设计、机器人制造、数据中心建设。

直播举的例子包括：Mirandio 用 1 名研究员指挥一群 Agent，花 1000 万美元买 Token，从零训练出高分基座模型；马斯克的 TeraFab 芯片工厂；Google TPU 与 Gemini 的协同迭代。

### 4. 白领危机与财富结构

直播把两个画面放在一起：

- 微软 25% 员工劝退。
- Anthropic 营收暴涨，并实现运营盈利。

当智能可以通过购买算力复制，人才溢价会下降，资本和算力进一步集中。标普 500 的数据被引用来证明：2015 年以来大部分利润增长被 Mag 7 吃掉，其余公司利润停滞。

这不只是裁员问题，而是社会结构和消费逻辑都可能被改变。

### 5. 认知漏斗：从“能做什么”到“想做什么”

直播引用 Karpathy 的漏斗图：

- 全球 60 亿人未接触过大模型。
- 10–20 亿人只用免费版。
- 2000 万人在用代码和 Agent。
- 只有 5000–10000 人真正指挥大量 Agent 探索科研边界。

所以真正的稀缺能力变成：**野心、问题意识和提出大问题的能力。**

## 五、从数字代理到物理世界：具身智能与 AI for Science

### 1. 机器人没有 ChatGPT 时刻

直播认为，机器人不会像 Chatbot 一样一夜爆发，而是像 FSD 一样经历多年渐进演化。

原因是物理硬件需要验证和部署，数据获取也慢得多。真正的护城河不是硬件躯壳，而是：

- 大脑的端到端软件能力。
- 真实物理世界的数据闭环。

中美路线的差异也很明显：

| 路线 | 特点 |
|---|---|
| 中国：硬件先行 | 供应链和制造优势，硬件快速开源降本，但硬件端也有泡沫 |
| 美国：大脑先行 | 顶尖实验室主导端到端软件生态和算法代差 |

### 2. AI for Science：两种路线

| 公司 | 路线 |
|---|---|
| OpenAI | AI 当科学家：提假说、设计分子、主攻数学证明 |
| Anthropic | AI 当研发操作系统：协调实验、管理流程、控制实验室硬件 |

直播里最有冲击力的例子是“一人制药公司”：1 个人指挥 Claude Agent，把湿实验外包给 CRO，在 18 个月内完成肌营养不良药物设计。

这意味着科研组织可能变成：

> **领域专家 + AI Agent + CRO**

而不是传统大实验室。

### 3. 数学的工业化与同行评议危机

直播引用陶哲轩的观点：数学的“浪漫英雄时代”正在结束。OpenAI 一晚提交 700 多篇无同行评议的证明，数学和理论物理开始走向成千上万个 Agent 暴力破解的工程化时代。

这会冲击传统科学共同体的验证机制：当产出速度远超人类评审速度，新的可信度体系必须被建立。

### 4. 自动化实验室的五条路径

- 通用科学发现。
- 机器人闭环实验室。
- 材料化学发现。
- 生物制药。
- 数学形式化证明。

代表例子包括 Warp Science、Periodic Labs、Discovery Loop、Isomorphic Labs。

## 六、投资主线与个人生存法则

### 1. 三大投资想象空间

| 主线 | 逻辑 |
|---|---|
| 硅基递归 | 太空、算力、物理 AI、具身智能、数据中心内部高速通信 |
| 碳基健康 | AI for Science、湿实验自动化、新型生物制药 |
| 碳基快乐 | 消耗闲暇时间的娱乐产品，如 AI 短剧、智能眼镜游戏 |

直播里有一个中美差异很有意思：

- 美国超 50% Token 用于生产力和代码。
- 中国 55% Token 用于视频生成，比如红果短剧。

一个偏向“省时间”，一个偏向“杀时间”。内容与娱乐出海可能是中国团队的结构性机会。

### 2. 给个人的建议

直播最后给出的结论不是“赶紧学提示词”，而是：

1. **发现有趣的问题**：AI 没有真实体验，人类的终极动力是发现并解决有趣的问题。
2. **做思想匠人**：从网红、个人品牌，进一步升级为积累终身作品的 Artisan。
3. **保留真实体验**：AI 只能提供平均视角，亲身经历、思想积累和独特视角才是护城河。

### 3. 给老板的三步策略

1. 把公司和个人工作自动化为 Agent Loop。
2. 把自己网络化，强化“人感”和判断。
3. 用赚来的钱，逢低投资下一代会形成垄断的前沿科技公司。

最值得记住的一句话是：

> **Agent Loop 只能帮企业爬到局部最优解，决定下一座山峰在哪里的，仍然是拥有真实体验的人类自己。**

## 七、我的理解

这期直播的核心不是“AI 又出了什么新功能”，而是互联网的权力结构正在改变。

过去的商业模式是吸引人的注意力，再把流量变现。Agent 时代之后，商业会逐渐变成：

- 谁拥有更强的模型判断力。
- 谁拥有更顺手的个人 Agent。
- 谁掌握 Agent 路由权。
- 谁能把工作流沉淀成可持续运行的 Agent Loop。

对普通人的机会是：比别人更早把日常研究、写作、信息摄入、投资复盘、工作流都变成 Agent Loop。因为当所有人都习惯雇佣 Agent 时，先跑通的人会拥有时间、数据和判断上的复利。

## 附：直播关键时间轴

### 0. 开场与时代坐标

| 时间 | 内容 |
|---|---|
| [00:02:56](https://www.youtube.com/watch?v=KW02EUe5LjY&t=176s) | 美股回调与机器交易时代的生存法则：科技 / AI 板块聚集高杠杆、高关注，人类要降低交易频次、选好 Alpha、保持耐心和控制情绪。 |
| [00:07:03](https://www.youtube.com/watch?v=KW02EUe5LjY&t=423s) | 对回调的补充：在机器化程序交易环境下，幸存者更偏长期与结构性判断。 |
| [00:13:09](https://www.youtube.com/watch?v=KW02EUe5LjY&t=789s) | 直播正式开始：介绍十月中旬湾区之行，Cloudflare 与 Vercel 活动背景。 |
| [00:14:03](https://www.youtube.com/watch?v=KW02EUe5LjY&t=843s) | AI 换脸 Meme 暖场。 |
| [00:15:51](https://www.youtube.com/watch?v=KW02EUe5LjY&t=951s) | 梳理本期八大核心议题。 |
| [00:16:47](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1007s) | 演示车载 Grok 联动本地 Agent，对 Indigo 频道做“毒舌风”总结。 |
| [00:18:17](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1097s) | Coatue 时代演进：机器代替体力 → 软件代替文书 → Token 替代脑力劳动。 |

### 1. Agentic Internet 与个人 Agent 生态

| 时间 | 内容 |
|---|---|
| [00:19:35](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1175s) | 流量迁移：Agent 访问请求已在 2026 年 5 月超过人类，预计五年后每 1000 次访问中有 999 次来自 Agent。 |
| [00:21:11](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1271s) | 硬件重心迁移：大模型吃 GPU，Agent 执行吃 CPU、SSD、存储和网络带宽；云 VPS 会成为标配。 |
| [00:22:41](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1361s) | 网络抓取结构重塑：从被动爬取走向网站前置 Agent 与模型侧 Agent 主动通讯、推送。 |
| [00:24:14](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1454s) | Agentic Payment：通过区块链与稳定币，让 Agent 自动完成内容读取和 API 调用的付费结算。 |
| [00:25:19](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1519s) | Agentic Infra 三层架构：模型 + 框架 / 云端沙箱与虚拟电脑 / 本地工具、知识库与工作流。 |
| [00:27:42](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1662s) | “构建公司就是构建 Agent”：企业组织从流水线升维到代理循环。 |
| [00:28:13](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1693s) | Anthropic 工程数据：单纯执行只有 21% 满分，加入顾问、复盘和 Dreaming 后可达 70 多分。 |
| [00:29:38](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1778s) | Agent Loop：人类开始退到循环之外，负责设置目标和判断方向。 |
| [00:31:12](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1872s) | Shopify CEO Tobi 访谈：Agent 接管繁琐流程会激发原本被放弃的需求。 |
| [00:32:41](https://www.youtube.com/watch?v=KW02EUe5LjY&t=1961s) | 解读电商增长：智能烤箱订购食材、3D 打印耗材自动采购等，电商盘子可能扩大 50%。 |
| [00:34:57](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2097s) | Personal Agent：新一代 Agent OS 体验与对比。 |
| [00:35:49](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2149s) | 播放 GrokBot 团队协作宣传片。 |
| [00:37:30](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2250s) | 主流个人代理对比：Meta Muse 面向普通人，GrokBot 面向极客。 |
| [00:38:20](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2300s) | GrokBot 实操：免费访问 X 数据，多模型路由调用 Gemini 绘图、Opus 校验。 |
| [00:40:19](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2419s) | 扎克伯格访谈：未来每家公司都会像拥有网站和邮箱一样拥有自己的 Agent。 |
| [00:42:50](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2570s) | 家用标品采购会被 Agent 替代，注重过程体验的线下消费会更加繁荣。 |
| [00:44:06](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2646s) | Meta 与 Sierra 联合发布 PAP，Personal Agent Protocol。 |
| [00:45:21](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2721s) | 未来 Agent 通信协议组合：MCP、A2A、PAP、A2P。 |
| [00:46:36](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2796s) | 八款 Personal Agent 全景：Claude Duet、OpenAI Dot、Gemini Spark、GrokBot、Instinct、Meta Muse、OpenClaw、Hermes。 |
| [00:47:30](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2850s) | 三大战场：Consumer、Pro User、Enterprise。 |
| [00:49:23](https://www.youtube.com/watch?v=KW02EUe5LjY&t=2963s) | Agent 路由权：极度理性的 Agent 会消灭信息不对称，商业博弈转向谁掌握默认路由。 |
| [00:51:44](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3104s) | 演示 Claude 调用 Midjourney 等工具自动生成 MV。 |

### 2. 递归式自我进化 RSI 与社会财富重构

| 时间 | 内容 |
|---|---|
| [00:54:24](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3264s) | Vals AI 数据：Anthropic 预计 2027 年 7–8 月达到完全 RSI，目前增速最快的是 Google Gemini。 |
| [00:56:22](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3382s) | Claude Opus 5.5 凭借高性价比统治 OpenRouter 调用量。 |
| [00:57:05](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3425s) | Anthropic 内部已有 26% 研发工作由 Claude 主导，部分系统工程师 99% 代码由 AI 编写。 |
| [00:58:01](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3481s) | 前沿实验室算力内倾：从外部推理转向内部训练和研发。 |
| [00:59:32](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3572s) | 双循环商业模式：算力投资循环 ↔ 智能增长循环。 |
| [01:00:24](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3624s) | Google 依靠 RSI 在不到一个月内从 Gemini 4 Argon 跃迁到 Carbon。 |
| [01:01:36](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3696s) | RSI 现状是“LLM + 软件演化”，终局是“软件循环 + 硬件闭环”。 |
| [01:03:50](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3830s) | Mirandio：1 名研究员指挥一群 Agent，1000 万美元买 Token，从零训练高分基座模型。 |
| [01:05:36](https://www.youtube.com/watch?v=KW02EUe5LjY&t=3936s) | 硅基循环：马斯克 TeraFab 芯片工厂、Google TPU 与 Gemini 协同迭代。 |
| [01:10:28](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4228s) | 白领危机：微软 25% 员工劝退，与 Anthropic 营收暴涨形成对比。 |
| [01:11:32](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4292s) | 智能可复制后，人才溢价下降，资金向算力集中并自我强化。 |
| [01:13:57](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4437s) | 通缩担忧：大规模裁员可能导致消费萎缩。 |
| [01:14:43](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4483s) | 标普 500：2015 年以来大部分利润增长被 Mag 7 吞噬。 |
| [01:15:52](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4552s) | Karpathy 认知漏斗：从 60 亿未接触者，到顶端约 5000–10000 名 Agent 指挥官。 |
| [01:18:34](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4714s) | OpenAI 偏商业工程化，Anthropic 更倾向“必须抢先造出 AGI”的安全叙事。 |
| [01:20:48](https://www.youtube.com/watch?v=KW02EUe5LjY&t=4848s) | DHH：手写代码经济价值归零，程序员转型为指挥超级智能的 Builder/Maker。 |

### 3. 具身智能与 AI for Science

| 时间 | 内容 |
|---|---|
| [01:24:39](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5079s) | 空间智能：GPT-6 根据平面图指挥 Blender，20 分钟渲染 3D 室内视频。 |
| [01:25:50](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5150s) | 大模型直接控制 900 多元的机械臂，说明底层执行能力正在下沉。 |
| [01:27:06](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5226s) | 湾区 50 多家机器人公司全景，组件生产高度依赖深圳。 |
| [01:27:38](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5258s) | 物理 AI 大脑三层：顶层推理策略、中层光子进动作出、底层物理定律反馈。 |
| [01:28:57](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5337s) | 终极硬件挑战是“灵巧手”，特斯拉 Optimus 的仿生线束驱动较领先。 |
| [01:30:03](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5403s) | 阿西莫夫悖论：廉价的躯壳与昂贵的灵魂，硬件降本快，长期护城河在大脑与数据闭环。 |
| [01:31:14](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5474s) | 中美路线分化：中国硬件先行，美国大脑先行。 |
| [01:32:06](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5526s) | 机器人没有“ChatGPT 时刻”，更像 FSD 的多年渐进式演化。 |
| [01:33:15](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5595s) | AI for Science 两大流派：OpenAI 让 AI 当科学家，Anthropic 让 AI 当研发操作系统。 |
| [01:35:00](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5700s) | 科研组织重构为“领域专家 + AI Agent + CRO”。 |
| [01:35:44](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5744s) | 一人制药公司案例：1 人指挥 Claude Agent，18 个月完成肌营养不良药物设计。 |
| [01:36:36](https://www.youtube.com/watch?v=KW02EUe5LjY&t=5796s) | 陶哲轩：数学进入工业化时代，同行评议机制需要重构。 |
| [01:40:02](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6002s) | 自动化实验室浪潮：Warp Science、Periodic Labs、Discovery Loop。 |
| [01:40:53](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6053s) | Warp Science：前 OpenAI CPO Kevin Weil，用机器人打造自动化 CRO 实验室。 |
| [01:42:22](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6142s) | AI for Science 五大路径：通用发现、闭环实验室、材料化学、生物制药、数学证明。 |
| [01:43:31](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6211s) | 美国本土全自动机器人 PCB 电路板工厂视频。 |

### 4. 投资主线、互动问答与个人 Agent Loop 演示

| 时间 | 内容 |
|---|---|
| [01:44:42](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6282s) | 推荐《造神之后》：RSI 指数级增长后，人类如何面对超级智能与存在意义。 |
| [01:46:27](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6387s) | 未来投资三大想象空间：硅基递归、碳基健康、碳基快乐。 |
| [01:46:37](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6397s) | 硅基递归：太空开拓、物理 AI、具身智能、机房与服务器间光通信。 |
| [01:47:14](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6434s) | 碳基健康：AI for Science、湿实验自动化、新型生物制药。 |
| [01:47:57](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6477s) | 碳基快乐：AI 短剧、智能眼镜游戏等消耗闲暇时间的娱乐产品。 |
| [01:48:54](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6534s) | 中美 Token 消耗结构：美国偏生产力与代码，中国偏视频生成与娱乐。 |
| [01:50:51](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6651s) | 太阳系文明反推图：芯片与模型最终深度融合。 |
| [01:52:06](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6726s) | 文艺复兴 2.0：人类终极动力是发现有趣的问题，并帮助他人。 |
| [01:54:01](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6841s) | 思想匠人 Artisan：从网红、个人品牌，升级为积累终身作品的创作者。 |
| [01:55:48](https://www.youtube.com/watch?v=KW02EUe5LjY&t=6948s) | 给老板的三步策略：自动化、网络化、投资下一代垄断型前沿公司。 |
| [01:56:47](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7007s) | Agent Loop 只能爬到局部最优，下一座山峰要靠有真实体验的人类判断。 |
| [01:57:58](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7078s) | 社群产品展示：Indigo Mind 在线版、Rewired Index Dashboard。 |
| [01:59:30](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7170s) | 预告《AI for Science》《Agentic Internet》深度研报。 |
| [02:00:07](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7207s) | 面向 Agent 的本地 Markdown 编辑器演示，音乐由 Claude 纯代码编写。 |
| [02:01:04](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7264s) | 太阳系文明畅想短片。 |
| [02:05:42](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7542s) | 算力紧缺与 AI 泡沫拆解：算力卡租金涨幅 170%–200%，泡沫主要在早期高估值公司。 |
| [02:09:49](https://www.youtube.com/watch?v=KW02EUe5LjY&t=7789s) | 芯片设计已有 20%–30% 被 AI 接管，未来可能到 50%–70%。 |
| [02:15:40](https://www.youtube.com/watch?v=KW02EUe5LjY&t=8140s) | 前沿实验室普遍将“2027 年年中模型完全自主训练改进”视为 AGI 标志。 |
| [02:16:07](https://www.youtube.com/watch?v=KW02EUe5LjY&t=8167s) | 垂直大模型是伪命题：未来由最强通用模型调用 AlphaFold 等专用工具。 |
| [02:17:33](https://www.youtube.com/watch?v=KW02EUe5LjY&t=8253s) | 个人本地 Agent Loop 实操：每日汇总信用评级、市场广度买点信号与知识库动态。 |
| [02:26:26](https://www.youtube.com/watch?v=KW02EUe5LjY&t=8786s) | 探讨如何把个人信源消化与投资管理 Loop 产品化分享给社群。 |
