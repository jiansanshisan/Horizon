---
layout: default
title: "Horizon Summary: 2026-07-07 (ZH)"
date: 2026-07-07
lang: zh
---

> 从 24 条内容中筛选出 17 条重要资讯。

---

1. [微软裁掉 id Software 的 idTech 引擎团队](#item-1) ⭐️ 9.0/10
2. [TRACE：开源层次记忆系统，LLM 智能体达 82.5%](#item-2) ⭐️ 9.0/10
3. [欧盟议会推进聊天控制法规](#item-3) ⭐️ 8.0/10
4. [美国供应商主导欧洲网站托管市场](#item-4) ⭐️ 8.0/10
5. [腾讯发布 Hy3 MoE 模型](#item-5) ⭐️ 8.0/10
6. [博士论文：可微射线追踪在无线电传播建模中的教科书级著作](#item-6) ⭐️ 8.0/10
7. [MIRA：为火箭联盟打造的 5B 参数世界模型](#item-7) ⭐️ 8.0/10
8. [Mozilla CTO 主持开源 AI 报告问答](#item-8) ⭐️ 8.0/10
9. [提出积分系统改进机器学习会议评审](#item-9) ⭐️ 8.0/10
10. [LingBot-Vision：掩码边界建模在深度估计上超越 DINOv3](#item-10) ⭐️ 8.0/10
11. [StreetComplete：为初学者游戏化 OpenStreetMap 编辑](#item-11) ⭐️ 7.0/10
12. [sqlite-utils 4.0rc3：复合外键与大小写不敏感匹配](#item-12) ⭐️ 7.0/10
13. [TorchJD 库实现 PyTorch 多损失训练](#item-13) ⭐️ 7.0/10
14. [CPU TTS 基准测试：Kokoro、Supertonic、Inflect-Nano 和 Pocket TTS 的 UTMOS 对比](#item-14) ⭐️ 7.0/10
15. [文章指出 98%的浏览器支持还不够](#item-15) ⭐️ 6.0/10
16. [机器学习岗位要求变得不切实际，非 FAANG 公司寻求多种深度专长](#item-16) ⭐️ 6.0/10
17. [LingBot-Depth 2.0：传感器有效性掩码用于深度估计](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [微软裁掉 id Software 的 idTech 引擎团队](https://gamefromscratch.com/microsoft-fire-idtech-team-at-id-software/) ⭐️ 9.0/10

据报道，微软裁掉了 id Software 整个 idTech 引擎团队，这可能表明其战略从内部引擎开发转向第三方解决方案（如 Unreal Engine 5）。 此举可能减少行业内的引擎多样性，进一步巩固 Epic Games 凭借 Unreal Engine 5 的主导地位，同时影响 id Software 的未来作品以及 idTech 以性能优化著称的优势。 此次裁员是微软游戏部门更大规模重组的一部分，但 id Software 尚未正式确认这些报道。idTech 是一个专有引擎系列，曾为《毁灭战士》、《雷神之锤》和《德军总部》等标志性游戏提供动力。

hackernews · bauc · 7月7日 15:33 · [社区讨论](https://news.ycombinator.com/item?id=48819244)

**背景**: id Software 开发了 idTech 引擎系列，广泛应用于许多第一人称射击游戏。历史上，idTech 引擎直到 id Tech 4 曾以开源形式发布，但之后的版本仍为专有。用于《毁灭战士：永恒》的 id Tech 7 以其在老旧硬件上的高性能而闻名。转向 Unreal Engine 5 这样的第三方引擎将标志着 id Software 内部引擎开发传统的重大转变。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Id_Tech">id Tech - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Id_Tech_7">id Tech 7 - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：一些人认为裁员是为了削减成本，将损害创新；另一些人则质疑报道背后的证据。少数评论者担心 Unreal Engine 垄断加剧，也有人建议微软应将 idTech 开源。

**标签**: `#game engines`, `#Microsoft`, `#id Software`, `#layoffs`, `#game development`

---

<a id="item-2"></a>
## [TRACE：开源层次记忆系统，LLM 智能体达 82.5%](https://www.reddit.com/r/MachineLearning/comments/1uoz5jo/trace_opensource_hierarchical_memory_for_llm/) ⭐️ 9.0/10

TRACE 是一个开源层次记忆系统，将 LLM 智能体的对话历史组织成话题树，在使用 gpt-oss-20B 模型时，在 MemoryAgentBench 的 EventQA 任务上达到了 82.5%的 F1 分数，大幅超越 Mem0（37.5%）和 MemGPT（26.2%）。 这表明层次记忆结构相比平面 RAG 方法能显著提升 LLM 智能体的检索准确性，而开源发布有助于更广泛的应用和进一步研究。 该对比并非完全控制变量，因为 TRACE 在本地使用了 gpt-oss-20B，而 Mem0 和 MemGPT 的结果使用 GPT-4o-mini 报告；作者尝试在 gpt-oss 上运行 Mem0 但遇到了 JSON 解析问题，这是 Mem0 与开源模型的一个已知限制。

reddit · r/MachineLearning · /u/PsychologicalDot7749 · 7月6日 14:35

**背景**: LLM 智能体通常需要长期记忆来维护跨对话的上下文。传统记忆系统使用平面检索增强生成（RAG），将所有历史交互视为独立片段。TRACE 引入了一个层次化话题树，将对话历史组织成带有摘要的分支，类似于文档大纲，从而实现更精确的检索。MemoryAgentBench 是一个基准测试，旨在通过增量多轮交互评估 LLM 智能体的记忆能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/HUST-AI-HYZ/MemoryAgentBench">GitHub - HUST-AI-HYZ/MemoryAgentBench: Open source code for ICLR 2026 Paper: Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2504.19413">[2504.19413] Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory</a></li>

</ul>
</details>

**标签**: `#LLM agents`, `#memory systems`, `#open-source`, `#benchmark`, `#hierarchical memory`

---

<a id="item-3"></a>
## [欧盟议会推进聊天控制法规](https://www.heise.de/en/news/Showdown-in-Strasbourg-The-unexpected-return-of-Chat-Control-1-0-11356680.html) ⭐️ 8.0/10

欧洲议会投票推进了“聊天控制”法规（CSAR）的一读程序，采用程序性策略要求修正案需获得绝对多数支持，从而威胁端到端加密。 该法规若通过，将强制对私人信息进行大规模监控，破坏所有欧盟公民的数字隐私和加密，并可能为全球监控法律树立先例。 该法规旨在检测儿童性虐待材料（CSAM），但批评者警告其可能通过要求客户端扫描或后门来破坏端到端加密。

hackernews · miroljub · 7月7日 15:16 · [社区讨论](https://news.ycombinator.com/item?id=48819008)

**背景**: “聊天控制”正式名称为《儿童性虐待法规》（CSAR），由欧盟委员会于 2022 年 5 月提出，旨在打击在线儿童性虐待。由于其可能强制扫描私人通信，从而削弱端到端加密，该法规一直备受争议。该法规此前已失效，但现正通过程序性变更重新推进。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://edri.org/our-work/chat-control-what-is-actually-going-on/">Chat Control: What is actually going on? - European Digital ...</a></li>

</ul>
</details>

**社区讨论**: 评论者表达了强烈反对，指出程序性策略有利于支持者，且阻止该法律的可能性很低。他们批评民主程序，并警告全球连锁效应，非欧盟服务可能被迫遵守或屏蔽欧盟用户。

**标签**: `#privacy`, `#EU regulation`, `#encryption`, `#surveillance`, `#civil liberties`

---

<a id="item-4"></a>
## [美国供应商主导欧洲网站托管市场](https://ciphercue.com/blog/european-web-hosting-vendor-share-2026) ⭐️ 8.0/10

一项分析显示，欧洲公司网站多数由 AWS、Azure 和 Cloudflare 等美国供应商托管，引发了对欧洲数字主权的讨论。 这种依赖引发了数据隐私、供应商锁定以及欧洲云服务商竞争能力的担忧，影响企业和推动数字自主的政策制定者。 社区评论指出，许多美国供应商在欧盟设有数据中心并遵守欧盟法律，而针对 API 子域名的另类研究显示，欧洲公司更常使用 OVH 和 Hetzner 而非美国超大规模云服务商。

hackernews · adulion · 7月7日 12:08 · [社区讨论](https://news.ycombinator.com/item?id=48816612)

**背景**: 网站托管是使网站可在互联网上访问的服务，通常由亚马逊云服务（AWS）和微软 Azure 等大型云提供商提供。许多欧洲企业依赖这些美国供应商的基础设施，但对数据主权和 GDPR 合规性的担忧使得对 Hetzner 和 OVH 等欧洲替代方案的兴趣日益增长。

**社区讨论**: 评论提供了细致观点：有人指出美国供应商在欧盟有实体和数据中心，降低了法律顾虑；另有人指出针对 API 托管的研究显示 OVH 和 Hetzner 等欧洲提供商更常见。一位个人创始人感叹在 Stripe 等关键服务上缺乏欧洲替代品。

**标签**: `#web hosting`, `#US vendors`, `#Europe`, `#cloud infrastructure`, `#vendor lock-in`

---

<a id="item-5"></a>
## [腾讯发布 Hy3 MoE 模型](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

腾讯发布了 Hy3，这是一个 295B 参数的混合专家模型，拥有 21B 活跃参数，采用 Apache 2.0 许可证。该模型已在 Hugging Face 上可用，并在 OpenRouter 上免费提供至 7 月 21 日，性能优于同类模型，可与参数规模大 2-5 倍的模型媲美。 Hy3 展示了高效的 MoE 架构能够与更大规模的稠密模型竞争，有可能降低高性能 AI 的计算成本。其开源发布以及在 OpenRouter 上的免费试用，使尖端 AI 对研究人员和开发者更加可及。 完整模型在 Hugging Face 上为 598GB，FP8 量化版本为 300GB，支持 256K token 的上下文长度。该模型由腾讯 Hy 团队在 4 月底预览后开发，利用来自 50 多个产品的更高质量数据扩大了后训练规模。

rss · Simon Willison · 7月6日 23:57

**背景**: 混合专家（MoE）是一种仅对每个输入激活部分参数的架构，能够在保持较低计算成本的同时实现巨大的总参数量。FP8 量化通过使用 8 位浮点数而非 16 位或 32 位格式来减小模型体积并加速推理，使大型模型更易于部署。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>

</ul>
</details>

**标签**: `#AI`, `#open-source`, `#MoE`, `#Tencent`, `#large language model`

---

<a id="item-6"></a>
## [博士论文：可微射线追踪在无线电传播建模中的教科书级著作](https://www.reddit.com/r/MachineLearning/comments/1upvkp5/phd_thesis_on_differentiable_ray_tracing_for/) ⭐️ 8.0/10

u/jeertmans 的博士论文以教科书形式系统阐述了可微射线追踪在无线电传播建模中的应用，通过 JAX 实现自动微分，能够计算物理环境中的精确梯度。 该工作桥接了基于物理的模拟与无线通信中的机器学习，支持梯度优化和 ML 训练，对下一代无线设计具有重要意义。 论文分为三部分：物理基础、算法核心（包括 GPU 加速路径追踪和不连续性平滑技术）以及信道建模、材料校准等应用。它基于 JAX 生态系统（如 jaxtyping、equinox、optimistix）和开源库 DiffeRT2d。

reddit · r/MachineLearning · /u/jeertmans · 7月7日 13:45

**背景**: 可微射线追踪在传统射线追踪基础上增加了梯度计算能力，这对于优化和机器学习至关重要。无线电传播建模预测无线电波的传播路径，是无线网络规划的基础。JAX 等自动微分框架可高效计算这些梯度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/jeertmans/DiffeRT2d">GitHub - jeertmans/DiffeRT2d: 2D Toolbox for Differentiable ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Radio_propagation">Radio propagation - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 作者邀请大家就 JAX 中的可微模拟和射线追踪提问，并感谢 Patrick Kidger 的论文启发以及其 JAX 库的大力支持。

**标签**: `#differentiable programming`, `#ray tracing`, `#radio propagation`, `#automatic differentiation`, `#wireless communications`

---

<a id="item-7"></a>
## [MIRA：为火箭联盟打造的 5B 参数世界模型](https://www.reddit.com/r/MachineLearning/comments/1upofuw/mira_multiplayer_interactive_world_models_trained/) ⭐️ 8.0/10

来自 General Intuition、Kyutai 和 Epic Games 的研究人员发布了 MIRA，这是一个 50 亿参数的交互式世界模型，基于 1 万小时的合成火箭联盟游戏数据进行训练，能够在单个 NVIDIA B200 GPU 上以每秒 20 帧的速度为四名玩家提供实时多人模拟。 MIRA 代表了交互式环境大规模世界模型的重要进展，能够实现逼真的多人游戏模拟，有望推动游戏 AI、强化学习和虚拟世界研究。 该模型在单个 B200 GPU 上以 20 帧/秒的速度支持 4 名玩家，团队还发布了可玩的在线演示、技术报告以及 1000 小时的 4 人游戏数据集。

reddit · r/MachineLearning · /u/MasterScrat · 7月7日 07:59

**背景**: AI 中的世界模型是一种机器学习系统，它学习环境的内部表示并预测环境如何随动作变化，从而使智能体无需持续与现实世界交互即可规划和推理。世界模型常用于机器人、自动驾驶和交互式视频生成。B200 是 NVIDIA 最新的 Blackwell GPU，在 AI 推理和训练方面提供了显著的性能提升。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/dgx-b200/">DGX B200: The Foundation for Your AI Factory | NVIDIA</a></li>

</ul>
</details>

**标签**: `#world model`, `#game AI`, `#reinforcement learning`, `#interactive simulation`, `#large-scale model`

---

<a id="item-8"></a>
## [Mozilla CTO 主持开源 AI 报告问答](https://www.reddit.com/r/MachineLearning/comments/1upxdvc/raffi_krikorian_cto_mozilla_ama_on_the_state_of/) ⭐️ 8.0/10

Mozilla CTO Raffi Krikorian 将于 7 月 14 日主持一场 AMA，讨论首份《开源 AI 现状》报告。该报告审视了开源 AI 在生产中的实际使用情况，包括隐藏成本、企业采用、中国模型的影响、开发者信任以及代理工具层。 这场 AMA 提供了一个难得的机会，可以直接从一家主要科技组织的 CTO 那里了解部署开源 AI 时常被忽视的现实情况，这影响着开发者、企业和更广泛的 AI 生态系统。讨论涵盖了关键议题，如“免费”模型的真实成本以及由中国开源模型驱动的权力动态变化。 该报告基于对超过 950 名开发者的调查，AMA 将深入探讨开放模型的隐藏基础设施成本、企业营销与实际采用之间的差距、中国模型发布的影响，以及作为新竞争层的“代理工具”。

reddit · r/MachineLearning · /u/raffikrikorian · 7月7日 14:51

**背景**: 开源 AI 模型（如 Llama 或 Mistral）以宽松许可证发布，但将其部署到生产中通常需要在基础设施、工具和监控方面进行大量投资。“代理工具”指的是使 AI 模型能够作为自主代理运行的编排层，处理规划、工具使用和记忆等任务，这已成为 AI 平台的关键战场。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.langchain.com/blog/the-anatomy-of-an-agent-harness">The Anatomy of an Agent Harness</a></li>
<li><a href="https://medium.com/@balajibal/agentic-harnesses-the-new-infrastructure-layer-for-ai-systems-3939c6fac1a6">Agentic Harnesses: The New Infrastructure Layer for AI Systems? | by balaji bal | Medium</a></li>
<li><a href="https://platform.uno/blog/agentic-harness-demystified/">AI Agentic Harness Demystified</a></li>

</ul>
</details>

**标签**: `#open source AI`, `#Mozilla`, `#enterprise AI`, `#AI industry`, `#AMA`

---

<a id="item-9"></a>
## [提出积分系统改进机器学习会议评审](https://www.reddit.com/r/MachineLearning/comments/1upjftu/icml_position_track_want_better_ml_reviews_stop/) ⭐️ 8.0/10

ICML 2026 的一篇立场论文提出了一种积分系统，评审者通过贡献高质量评审赚取积分，并可用积分兑换福利，以取代当前无效的指南和直接拒稿措施。 该提案针对机器学习会议中长期存在的评审参与度低、优良行为不受奖励的问题。如果被采纳，可能从根本上重塑评审文化，提高给作者的反馈质量。 评审者完成一篇评审可获得+1 分，优秀评审可获得+3 分，积分可用于兑换免费注册或请求额外评审者等福利。该系统还允许可退还的投稿费，以阻止低质量投稿。

reddit · r/MachineLearning · /u/choHZ · 7月7日 03:32

**背景**: ICML 是顶级的机器学习会议。ICML 的立场论文赛道鼓励发表能引发讨论的及时话题。当前的评审机制依赖评审指南和直接拒稿，但缺乏对评审者努力和质量的问责。提议的积分系统旨在创建可验证的贡献记录。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://icml.cc/Conferences/2026/CallForPositionPapers">ICML 2026 Call For Position Papers</a></li>
<li><a href="https://openreview.net/forum?id=6IiZXiqP3Q">Position: Want Better ML Reviews? Stop Asking Nicely and Start Incentivizing with a Credit System | OpenReview</a></li>
<li><a href="https://openreview.net/group?id=ICML.cc/2026/Position_Paper_Track">ICML 2026 Position Paper Track | OpenReview</a></li>

</ul>
</details>

**标签**: `#ML conferences`, `#peer review`, `#incentives`, `#community building`, `#ICML`

---

<a id="item-10"></a>
## [LingBot-Vision：掩码边界建模在深度估计上超越 DINOv3](https://www.reddit.com/r/MachineLearning/comments/1up4cjh/lingbotvision_masked_boundary_modeling_for/) ⭐️ 8.0/10

LingBot-Vision 提出了掩码边界建模方法用于自监督预训练，教师网络预测稠密边界场，强制学生重建包含边界的掩码令牌。该方法在 NYUv2 线性探测深度估计上达到 0.296 RMSE，优于 DINOv3-7B 的 0.309，且仅使用 1.61 亿张训练图像。 该方法以远少于 DINOv3 的训练样本在 NYUv2 深度估计上达到新标杆，表明其能更高效地学习稠密视觉表示。它可能提升深度估计、分割等稠密预测任务的性能，同时降低数据需求。 边界场被建模为逐像素分类分布以防止表征坍塌，解码后的片段通过 a-contrario 验证测试后才用作监督。虽然在 NYUv2 深度估计上表现出色，但在 ImageNet 分类和 ADE20K 分割上仍落后于 DINOv3。

reddit · r/MachineLearning · /u/StillThese3747 · 7月6日 17:37

**背景**: 自监督学习无需人工标注即可训练视觉表征。掩码图像建模（MIM）是一种流行的自监督方法，它遮住图像块并让模型重建缺失内容。LingBot-Vision 将 MIM 扩展至边界密集区域，这些区域更难从周围上下文中推断，从而迫使模型学习空间结构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://x.com/ModelScope2022/status/2074381060608074198">LingBot-Vision is now on ModelScope: a boundary-first vision ...</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0010482523009915">Masked image modeling-based boundary reconstruction for 3D ...</a></li>

</ul>
</details>

**社区讨论**: Reddit 评论者称赞了 NYUv2 上的优异结果和巧妙的设计选择，但保持谨慎，指出 0.013 RMSE 差距可能在探测超参数敏感性范围内，且缺少与硬掩码基线的消融实验。一些人考虑到以往评估争议，呼吁独立验证数据。

**标签**: `#Self-Supervised Learning`, `#Vision Transformer`, `#Masked Image Modeling`, `#Depth Estimation`, `#Computer Vision`

---

<a id="item-11"></a>
## [StreetComplete：为初学者游戏化 OpenStreetMap 编辑](https://streetcomplete.app/) ⭐️ 7.0/10

StreetComplete 是一款安卓应用，它将 OpenStreetMap 贡献转化为小型互动任务，用户无需事先了解 OSM 即可轻松添加缺失数据，如营业时间或人行横道。 通过降低参与门槛，StreetComplete 显著拓宽了 OpenStreetMap 的贡献者基础，提升了地图的完整性和准确性，惠及包括可能利用 OSM 数据改善自身地图的谷歌在内的所有人。 该应用会向用户提出关于附近地点和物体的具体问题，例如“这里的营业时间是什么？”或“这个还在吗？”，并自动将答案发送到 OSM。

hackernews · kls0e · 7月7日 12:38 · [社区讨论](https://news.ycombinator.com/item?id=48816883)

**背景**: OpenStreetMap (OSM) 是一个由志愿者构建的免费可编辑世界地图，但传统上详细的编辑需要技术知识。StreetComplete 通过将数据收集分解为简单任务，使非专家也能轻松贡献。该应用免费开源，仅适用于安卓。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/StreetComplete">StreetComplete</a></li>
<li><a href="https://grokipedia.com/page/streetcomplete">StreetComplete</a></li>

</ul>
</details>

**社区讨论**: 社区普遍称赞 StreetComplete 的初学者友好界面和有趣的方式，但一些用户担心重复数据录入，并感到局限于标记而非添加新道路。还有人担忧谷歌利用 OSM 数据却不回馈，引发了关于许可协议的讨论。

**标签**: `#openstreetmap`, `#crowdsourcing`, `#mapping`, `#open-source`, `#gamification`

---

<a id="item-12"></a>
## [sqlite-utils 4.0rc3：复合外键与大小写不敏感匹配](https://simonwillison.net/2026/Jul/6/sqlite-utils/#atom-everything) ⭐️ 7.0/10

sqlite-utils 4.0rc3 引入了对复合外键的内省和创建支持，并遵循 SQLite 的列名大小写不敏感约定。此候选版本还包括各种修复和改进，变更日志不断增长。 这些增强功能满足了用户长期以来的请求，使 sqlite-utils 更接近 SQLite 的原生行为，对于复杂数据库模式更加可靠。复合外键功能对于管理多列关系的用户尤其重要，而大小写不敏感的列匹配则提高了一致性。 为了支持复合外键，table.foreign_keys 进行了微妙的破坏性变更，因此这一变更在 4.0 版本中落地。大小写不敏感的列匹配涉及代码库的多个部分，详情见变更日志。

rss · Simon Willison · 7月6日 05:40

**背景**: sqlite-utils 是一个 Python 命令行工具和库，用于创建、查询和转换 SQLite 数据库。复合外键同时引用多个列，这是 SQLite 支持的功能，但此前 sqlite-utils 并未完全内省。SQLite 默认将列名视为大小写不敏感，但 sqlite-utils 之前并未一致地匹配该行为。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://sqlite-utils.datasette.io/en/latest/changelog.html">Changelog - sqlite-utils</a></li>
<li><a href="https://github.com/simonw/sqlite-utils/issues/117">Support for compound (composite) foreign keys · Issue #117 · simonw/sqlite-utils</a></li>

</ul>
</details>

**标签**: `#sqlite`, `#python`, `#database`, `#tools`

---

<a id="item-13"></a>
## [TorchJD 库实现 PyTorch 多损失训练](https://www.reddit.com/r/MachineLearning/comments/1upzxk2/torchjd_training_with_multiple_losses_in_pytorch_p/) ⭐️ 7.0/10

TorchJD 是一个用于在 PyTorch 中进行多损失训练的库，已被 PyTorch 生态系统接纳，并实现了现有的大多数标量化和 Jacobian 下降聚合方法。 这填补了多任务学习中的一个关键空白，为各种损失聚合技术提供了统一接口，使从业者能够轻松切换方法并提升模型性能。 TorchJD 同时支持标量化（如加权平均）和 Jacobian 下降方法，后者计算每个损失的梯度并聚合它们以同时减少所有损失。

reddit · r/MachineLearning · /u/Skeylos2 · 7月7日 16:20

**背景**: 在多任务学习中，模型针对多个目标进行训练，每个目标都有自己的损失函数。标量化将多个损失合并为一个标量，而 Jacobian 下降则利用 Jacobian 矩阵更新参数，使所有损失同时下降。TorchJD 提供了这些方法的库，使它们在 PyTorch 中易于使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/SimplexLab/TorchJD">GitHub - SimplexLab/TorchJD: Library for Jacobian descent with...</a></li>
<li><a href="https://arxiv.org/html/2406.16232">Jacobian Descent for Multi -Objective Optimization</a></li>

</ul>
</details>

**标签**: `#PyTorch`, `#multi-task learning`, `#Jacobian descent`, `#loss aggregation`, `#machine learning`

---

<a id="item-14"></a>
## [CPU TTS 基准测试：Kokoro、Supertonic、Inflect-Nano 和 Pocket TTS 的 UTMOS 对比](https://www.reddit.com/r/MachineLearning/comments/1up0azr/cpu_tts_benchmark_with_utmos_mos_scoring_kokoro/) ⭐️ 7.0/10

一项基准测试在 CPU 上评估了四个小型 TTS 模型——Kokoro、Supertonic、Inflect-Nano 和 Pocket TTS，使用 UTMOS 进行客观 MOS 评分，并给出了不同文本长度下的 RTF 和质量详细结果。 该基准测试为基于 CPU 的 TTS 提供了实用的延迟和质量对比，凸显了传统架构与新型流式语言模型（如 Pocket TTS）之间的权衡。Pocket TTS 在 CPU 上具有平坦的 RTF 缩放和零样本语音克隆能力。 Pocket TTS 使用基于 Mimi 神经音频编解码器的流式语言模型，在所有文本长度上实现恒定 RTF（约 0.69-0.76），而其他模型变化很大。UTMOS 未能捕捉小声码器模型（如 Inflect-Nano，得分 3.48 但听起来机械）的自然度。

reddit · r/MachineLearning · /u/gvij · 7月6日 15:17

**背景**: TTS（文本转语音）模型将文本转换为语音。平均意见分（MOS）是一种主观质量评分，而像 UTMOS 这样的客观预测器可以自动估算它。ONNX 允许跨硬件进行模型推理。StyleTTS2、FastSpeech 和流式语言模型是不同的 TTS 架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/sarulab-speech/UTMOS22">UTMOS: UTokyo-SaruLab MOS Prediction System - GitHub</a></li>
<li><a href="https://github.com/kyutai-labs/moshi">GitHub - kyutai-labs/moshi: Moshi is a speech-text foundation model and full-duplex spoken dialogue framework. It uses Mimi, a state-of-the-art streaming neural audio codec. · GitHub</a></li>
<li><a href="https://github.com/yl4579/styletts2">GitHub - yl4579/StyleTTS2: StyleTTS 2: Towards Human-Level Text-to-Speech through Style Diffusion and Adversarial Training with Large Speech Language Models · GitHub</a></li>

</ul>
</details>

**标签**: `#TTS`, `#benchmark`, `#machine learning`, `#ONNX`, `#UTMOS`

---

<a id="item-15"></a>
## [文章指出 98%的浏览器支持还不够](https://whynothugo.nl/journal/2026/07/03/98-isnt-very-much/) ⭐️ 6.0/10

一篇博客文章认为，98%的浏览器支持是不够的，因为剩下的 2%用户或用例可能至关重要，引发了关于功能采用中权衡的讨论。 这场辩论影响那些必须在广泛兼容性和利用现代功能之间取得平衡的网页开发者，并可能影响被排除在外的少数用户体验。 文章举例说明 98%的支持率仍会留下关键缺口，并指出支持率因受众而异（例如某些细分领域仅为 70%）。

hackernews · speckx · 7月7日 12:45 · [社区讨论](https://news.ycombinator.com/item?id=48816959)

**背景**: 网页开发者常根据 caniuse.com 的全球浏览器使用数据来决定何时采用新的 CSS 或 JavaScript 功能。98% 的阈值通常被认为是安全的，但这篇文章通过强调边缘情况和可访问性来挑战这一假设。

**社区讨论**: 评论呈现出分歧：一些人认为如果商业目标现实，98%通常足够；而另一些人分享个人经历，其中 70%的支持率导致了问题。一条评论将清除松针的过程与接近 100%时的收益递减进行类比。

**标签**: `#web development`, `#browser support`, `#software engineering`, `#accessibility`, `#product strategy`

---

<a id="item-16"></a>
## [机器学习岗位要求变得不切实际，非 FAANG 公司寻求多种深度专长](https://www.reddit.com/r/MachineLearning/comments/1uov7or/machine_learning_industry_job_requirements_used/) ⭐️ 6.0/10

一位 Reddit 用户指出，一家非 FAANG 工业自动化公司的招聘要求涵盖 LLM、VLA、VLM、动作变换器、机器人动力学与运动学、传感器融合、模型预测控制、强化学习、CUDA 和 FPGA 硬件加速等多领域深度专长，认为这种广度不切实际。 这反映了机器学习就业市场的一个趋势，即公司（尤其非大型科技公司）要求跨多个专业领域的专长，即使经验丰富的专业人士也难以满足。这可能表明招聘实践中的低效，会拖慢创新并排斥有才华的候选人。 该招聘要求包括在 ML 和机器人会议上的顶级发表、熟悉 RLib（强化学习库）以及 3-5 年以上非学术经验。发帖人将其比作 MMORPG 中需要同时是'战士、弓箭手、术士、萨满、牧师和法师'。

reddit · r/MachineLearning · /u/NeighborhoodFatCat · 7月6日 11:57

**背景**: 近期机器人技术的进步将视觉语言模型（VLM）与动作解码器结合，形成了用于端到端机器人控制的视觉-语言-动作（VLA）模型。动作变换器（如 Action Chunking Transformer）用于操纵任务。此外，FPGA 硬件加速正被用于提升机器学习推理性能，但这些领域的专业知识通常需要多年的专门研究。正如数学家陶哲轩所指出的，在数学领域中，跨不同学科的深度专长极为罕见。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vision–language–action_model">Vision–language–action model - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2508.13073">[2508.13073] Large VLM-based Vision-Language-Action Models ...</a></li>
<li><a href="https://ictactjournals.in/paper/IJME_Vol_9_Iss_3_Paper_5_1613_1619.pdf">Fpga -based hardware acceleration of machine learning</a></li>

</ul>
</details>

**标签**: `#machine learning`, `#job market`, `#hiring`, `#robotics`

---

<a id="item-17"></a>
## [LingBot-Depth 2.0：传感器有效性掩码用于深度估计](https://www.reddit.com/r/MachineLearning/comments/1upqghy/masked_depth_modeling_with_sensorvalidity_masking/) ⭐️ 6.0/10

LingBot-Depth 2.0 引入了传感器有效性掩码，利用传感器失效区域（如镜面高光、透明表面）作为自然掩码进行掩码深度建模，在 8 个稀疏深度基准中的 7 个上取得了最佳 RMSE。 这项工作通过直接针对传感器失效情况进行训练，解决了 RGB-D 传感器的一个关键局限性，有望提升机器人、自动驾驶等实际应用的鲁棒性。 该模型使用以 LingBot-Vision 预训练初始化的 Vision Transformer 编码器。值得注意的是，深度权重尚未发布，仅开源了视觉骨干网络。

reddit · r/MachineLearning · /u/Ok-Line2658 · 7月7日 09:54

**背景**: 掩码深度建模是一种用于深度补全的自监督学习方法。标准方法使用随机块掩码，而传感器有效性掩码则利用实际传感器无效区域（如由镜面反射或透明表面导致）作为掩码，使模型学习处理真实的传感器故障。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2601.17895">[2601.17895] Masked Depth Modeling for Spatial Perception</a></li>
<li><a href="https://github.com/Robbyant/lingbot-depth">GitHub - Robbyant/lingbot-depth: Masked Depth Modeling for ...</a></li>

</ul>
</details>

**社区讨论**: 有评论者质疑传感器有效性掩码是否能泛化到 LiDAR 或热成像等其他传感模态，表明人们对该方法更广泛适用性的兴趣。

**标签**: `#depth estimation`, `#masked modeling`, `#self-supervised learning`, `#computer vision`, `#RGB-D`

---