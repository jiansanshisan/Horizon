---
layout: default
title: "Horizon Summary: 2026-08-26 (ZH)"
date: 2026-08-26
lang: zh
---

> 从 26 条内容中筛选出 15 条重要资讯。

---

1. [智谱发布 GLM-5.3-Flash，兼顾性能与成本](#item-1) ⭐️ 8.0/10
2. [AWS 收购 DuckLabs，DuckDB 开源项目仍由基金会持有](#item-2) ⭐️ 8.0/10
3. [Qwen3.8-Flash-Next：稀疏高效大模型，预览 Qwen4 架构](#item-3) ⭐️ 8.0/10
4. [EVE Online 启动从 Stackless Python 2.7 到 Python 3 的迁移](#item-4) ⭐️ 8.0/10
5. [持续学习报告发布开源权重模型 Thomson，推动主权 AI](#item-5) ⭐️ 8.0/10
6. [AI 生成本质可编程的 3D 空间软件对象](#item-6) ⭐️ 8.0/10
7. [Papers with Code 详解基于 PostgreSQL、pgvector、Qwen3 的 SOTA 混合搜索](#item-7) ⭐️ 8.0/10
8. [法国光纤覆盖率 2026 年达 94.9%，引发欧洲宽带讨论](#item-8) ⭐️ 7.0/10
9. [RAG 比你想的更简单：全文搜索往往不逊于嵌入](#item-9) ⭐️ 7.0/10
10. [保罗·迪克斯：AI 百万行代码优化令人震撼](#item-10) ⭐️ 6.0/10
11. [追踪 scikit-learn 中 BayesianRidge 不确定性计算的 bug](#item-11) ⭐️ 6.0/10
12. [Millwright：一个实验性的 Rust 端到端机器学习框架](#item-12) ⭐️ 6.0/10
13. [在信息不完整下建模用药提醒智能体：征求建议](#item-13) ⭐️ 6.0/10
14. [Unbounded Labs 发布 2.82B 参数怀旧大模型 Bart，用 1931 年前英语训练](#item-14) ⭐️ 6.0/10
15. [提出一种公平基准，将智能体 harness 与模型能力分离](#item-15) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [智谱发布 GLM-5.3-Flash，兼顾性能与成本](https://z.ai/blog/glm-5.3-flash) ⭐️ 8.0/10

智谱（Z.ai）发布了 GLM-5.3-Flash，这是 GLM-5 系列中首个原生多模态模型，其架构和训练方案围绕能力与效率重新设计。基准测试显示，它能与价格高得多的模型竞争，让先进 AI 更加平价。 GLM-5.3-Flash 在提供相近性能的同时，价格远低于昂贵的专有模型，可能重塑 AI 部署的成本基准。其高效性有利于从事编码和长周期智能体任务的开发者。 模型权重已在 Hugging Face 的 zai-org 下开源，OpenRouter 也已提供 API 定价。它能覆盖从金融研究到估值建模的完整流程，整合多来源信息并保留关键结论的支撑证据。

hackernews · Philpax · 8月26日 14:08 · [社区讨论](https://news.ycombinator.com/item?id=49449507)

**背景**: GLM 是 General Language Model（通用语言模型）的缩写，由中国 AI 公司智谱（Z.ai）开发的一系列开放权重大型语言模型。多模态模型能够处理和生成多种类型的数据，如文本、图像和音频。GLM-5.3-Flash 这类高性价比模型旨在将 GPT 级别的性能带给更广泛的应用场景。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.3-Flash">zai-org/ GLM - 5 . 3 - Flash · Hugging Face</a></li>
<li><a href="https://openrouter.ai/z-ai/glm-5.3-flash">GLM 5 . 3 Flash - API Pricing & Providers | OpenRouter</a></li>
<li><a href="https://en.wikipedia.org/wiki/Z.ai">Z . ai - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 社区评论褒贬不一：一些用户指出第三方基准测试表现出色且成本更低，而另一些用户则强调 Z.ai 服务条款中对输入输出内容的宽泛授权。还有人质疑基准分数能否反映模型在实际使用中的真实差异。

**标签**: `#AI`, `#LLM`, `#GLM`, `#benchmark`, `#Z.ai`

---

<a id="item-2"></a>
## [AWS 收购 DuckLabs，DuckDB 开源项目仍由基金会持有](https://ducklabs.com/news/2026/08/26/ducklabs-to-join-aws) ⭐️ 8.0/10

AWS 于 2026 年 8 月 26 日宣布收购 DuckLabs，即开源数据库项目 DuckDB 背后的商业公司。DuckDB 的开源代码和知识产权仍归独立的非营利组织 DuckDB 基金会所有。 DuckDB 已成为领先的嵌入式分析数据库，因此这笔收购可能重塑项目的发展方式，以及云厂商如何集成进程内分析。社区正在密切关注 AWS 是否会保留 DuckDB 的开源治理和技术独立性。 DuckLabs 从荷兰国家数学与计算机科学研究中心（CWI）分拆而来，并成立了 DuckDB 基金会来持有开源 DuckDB 的全部知识产权。基金会将继续拥有这些知识产权，而 DuckLabs 的员工和商业化工作将转入 AWS。

hackernews · onderkalaci · 8月26日 12:59 · [社区讨论](https://news.ycombinator.com/item?id=49448321)

**背景**: DuckDB 是一款开源、内存型、列式分析数据库管理系统，由 Hannes Muhleisen 和 Mark Raasveldt 创建，于 2019 年首次发布。它专为对大数据集执行嵌入式分析查询而设计，采用 MIT 许可证。非营利组织 DuckDB 基金会负责保障项目的长期维护和发展；DuckLabs 则是围绕 DuckDB 提供商业服务和支持的商业实体。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://duckdb.org/faq">Frequently Asked Questions – DuckDB</a></li>
<li><a href="https://en.wikipedia.org/wiki/DuckDB">DuckDB - Wikipedia</a></li>
<li><a href="https://duckdb-foundation.nproxy.org/">DuckDB Foundation</a></li>

</ul>
</details>

**社区讨论**: 网友迅速澄清：AWS 收购的是 DuckLabs，而不是 DuckDB 本身，开源 IP 仍归 DuckDB 基金会所有。社区情绪复杂：有人认可基金会的保护作用，也有人担心 AWS 可能损害项目的技术文化或推出仅限企业的分支版本，还有不少人对被收购的团队表示担忧。

**标签**: `#AWS`, `#DuckDB`, `#Acquisition`, `#Database`, `#Open Source`

---

<a id="item-3"></a>
## [Qwen3.8-Flash-Next：稀疏高效大模型，预览 Qwen4 架构](https://qwen.ai/blog?id=qwen3.8-flash-next) ⭐️ 8.0/10

Qwen 发布了 Qwen3.8-Flash-Next，这是将支撑 Qwen4 的架构的实验性预览，包含一个 125B 参数的主模型，外加 51B 的 n-gram 嵌入。该模型每 token 仅激活 6B 参数，并被描述为多模态、超稀疏 MoE 模型，支持 262K 上下文窗口。 这一架构能大幅降低运行大型语言模型的成本和内存需求，使其更容易在高端 Mac 等消费级硬件上运行。作为 Qwen4 的预览，它也标志着阿里巴巴 Qwen 团队未来开源 AI 模型的技术方向。 尽管总参数量约为 176B（125B 主模型加 51B n-gram 嵌入），但该模型的稀疏激活使每个 token 仅激活 6B 参数，FP8 版本的 GGUF 格式约为 73GB。这意味着它可以在 128GB 统一内存的设备上运行，例如 Apple silicon Mac 或 AMD Strix Halo 系统。

hackernews · tosh · 8月26日 12:52 · [社区讨论](https://news.ycombinator.com/item?id=49448210)

**背景**: 稀疏激活是一种仅对每个 token 激活神经网络一部分参数的技术，与每一步都使用全部参数的稠密模型相比，能减少推理期间的计算和内存搬运。Qwen 的'Flash'系列主打成本效率，Qwen3.8-Flash-Next 被描述为对 LLM 组件如何在大规模下相互作用的一次根本性反思。N-gram 嵌入是一种表示 token 序列的附加技术，该模型的混合设计暗示了 Qwen4 计划采用的架构。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF">unsloth/Qwen3.8-Flash-Next-GGUF · Hugging Face</a></li>
<li><a href="https://recipes.vllm.ai/Qwen/Qwen3.8-Flash-Next">Qwen/Qwen3.8-Flash-Next | vLLM Recipes</a></li>
<li><a href="https://arxiv.org/abs/2408.14690">Training-Free Activation Sparsity in Large Language Models</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一：像'stefan_'这样的评论者认为 Flash 模型对于复杂、新颖的工作是进化上的死胡同，而另一些人则对模型表现超出预期并能在 128GB 消费级硬件上运行感到兴奋。讨论还集中在模型的实际有效规模以及量化对部署的影响上，'pram'指出 unsloth 的 GGUF 版本约为 73GB。

**标签**: `#AI`, `#LLM`, `#Qwen`, `#Model Architecture`, `#Efficiency`

---

<a id="item-4"></a>
## [EVE Online 启动从 Stackless Python 2.7 到 Python 3 的迁移](https://simonwillison.net/2026/Aug/25/eve-online-move-to-python-3/) ⭐️ 8.0/10

EVE Online 已正式宣布启动从 Stackless Python 2.7 到 Python 3 的迁移。该项目将使用 futurize 工具处理 240 万行代码，随后人工审查约 2 万个 Python 2 与 Python 3 之间的行为差异。 这是 Python 生态的一个里程碑，证明即使是最大、最特殊的 Python 2 代码库也终于能够向前迁移。它还为其他仍停留在 Python 2 的组织提供了真实可参考的方案，即使用 futurize 并辅以仔细的人工审查。 公告提到行为差异包括像 '1 / 2' 在 Python 2 中返回 0、在 Python 3 中返回 0.5 这样的简单情况。目前尚未公布如何替代 Stackless Python 的细节，但去年的 EVE Frontier 项目已通过开源库 carbonengine/scheduler 告别了 Stackless。

rss · Simon Willison · 8月25日 22:59

**背景**: Stackless Python 是一种增强型 Python 解释器，以称为 tasklet 的轻量级微线程而闻名，EVE Online 自 2003 年以来一直依赖它。该项目已正式停止维护，其 GitHub 仓库于 2025 年 2 月被归档。Futurize 是 python-future 项目提供的迁移脚本，用于帮助把 Python 2 代码转换为兼容 Python 3，但大型代码库仍需要人工关注，因为部分语言行为发生了不兼容的变化。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Stackless_Python">Stackless Python</a></li>
<li><a href="https://python-future.org/futurize.html">futurize : Py2 to Py2/3 — Python -Future documentation</a></li>
<li><a href="https://github.com/stackless-dev/stackless/wiki/">Home · stackless-dev/stackless Wiki · GitHub</a></li>

</ul>
</details>

**标签**: `#Python`, `#EVE Online`, `#migration`, `#Stackless Python`, `#software engineering`

---

<a id="item-5"></a>
## [持续学习报告发布开源权重模型 Thomson，推动主权 AI](https://www.reddit.com/r/MachineLearning/comments/1vxvzju/continual_learning_of_frontier_models_for/) ⭐️ 8.0/10

一份新的技术报告推出了 Thomson，这是一个通过在开放权重模型上进行持续学习训练出的通用前沿模型，并公开了其权重。作者声称，以远低于通常设想的算力和人力预算，即可实现前沿级性能。 这挑战了只有少数资金雄厚的实验室才能打造前沿 AI 的假设，为各类机构实现主权 AI 提供了一条具体路径。它有助于缩小 AI 开发者与广泛用户群体之间在信息、经济和权力上的不对等。 这种持续学习方法在训练的每个阶段都引入保护机制，以同时保持可塑性和稳定性，同时只对参数做最小的高影响干预。Thomson 专注于高风险专业工作，并表现出独特的π形性能模式——在广泛能力上取得提升，同时几乎不出现灾难性遗忘。

reddit · r/MachineLearning · /u/Forsaken_Scientist · 8月25日 10:30

**背景**: 持续学习是一种 AI 方法，它让模型在依次学习新任务的同时保留已有知识，避免窄领域适配中常见的“遗忘”问题。开放权重模型公开其训练后的参数，使他人能够下载、微调并在此基础上继续构建。主权 AI 指的是组织或国家独立构建、部署和治理 AI 使用的能力，近年来已成为政策与行业讨论中日益重要的话题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ibm.com/think/topics/continual-learning">What is Continual Learning? | IBM</a></li>
<li><a href="https://www.analyticsvidhya.com/blog/2025/04/open-weight-models/">What are Open Source and Open Weight Models ? | Analytics Vidhya</a></li>
<li><a href="https://zertia.ai/glossary/governance/sovereign-ai/">Sovereign AI : Geopolitics of the AI Stack | Zertia</a></li>

</ul>
</details>

**标签**: `#continual learning`, `#sovereign AI`, `#open weights`, `#frontier models`, `#LLM`

---

<a id="item-6"></a>
## [AI 生成本质可编程的 3D 空间软件对象](https://www.reddit.com/r/MachineLearning/comments/1vxcc1h/r_using_ai_as_a_spatial_software_generator_to/) ⭐️ 8.0/10

这篇论文提出了一种方法，利用 LLM 作为空间软件生成器，将 3D 对象创建为本质上可编程的代码，从而得到可直接动画化、具有层级结构的模型。作者在 nova3d.xyz 上提供了可视化演示，并附有 GitHub 代码仓库。 将 3D 对象视为软件而非单一网格，可能使 AI 生成的 3D 资产对交互式应用更加有用。由于对象从诞生之初就具备可编程性和动画就绪特性，这可能会颠覆工业设计、游戏开发、仿真以及 AR/VR/XR 等行业。 生成的 3D 对象在创作时就包含层级结构和铰链/插座式关节，并且能在弱计算环境和强计算环境中呈现不同细节。作者指出，该方法目前在复杂有机形状方面仍落后于传统的基于网格的 AI 生成器。

reddit · r/MachineLearning · /u/mhb_11 · 8月24日 19:10

**背景**: 空间编程是一种强调空间和空间引用的编程模型，通常用于分布式嵌入式系统。近期基于 LLM 的 3D 生成方法会生成 OpenSCAD 等工具的代码而不是网格，本文延续了这一方向，将代码本身视为 3D 对象，从而实现计算感知渲染和程序化控制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.researchgate.net/publication/4066232_Spatial_Programming_Using_Smart_Messages_Design_and_Implementation">(PDF) Spatial Programming Using Smart Messages: Design and...</a></li>
<li><a href="https://www.zenml.io/llmops-database/llm-powered-3d-model-generation-for-3d-printing">Build Great AI: LLM-Powered 3D Model Generation for 3D Printing - ZenML LLMOps Database</a></li>
<li><a href="https://github.com/ActiveVisionLab/Awesome-LLM-3D">GitHub - ActiveVisionLab/Awesome-LLM-3D: Awesome-LLM-3D: a curated list of Multi-modal Large Language Model in 3D world Resources · GitHub</a></li>

</ul>
</details>

**标签**: `#AI`, `#3D Generation`, `#LLM`, `#Spatial Programming`, `#Research`

---

<a id="item-7"></a>
## [Papers with Code 详解基于 PostgreSQL、pgvector、Qwen3 的 SOTA 混合搜索](https://www.reddit.com/r/MachineLearning/comments/1vxyrsr/how_we_built_a_sota_search_engine_using/) ⭐️ 8.0/10

Niels Rogge 发布了一篇技术文章，详解 Papers with Code 如何借助 PostgreSQL（pgvector）、Qwen3-Embedding-0.6B、Hugging Face Jobs、Buckets 与 Inference Endpoints 构建了最先进的混合搜索引擎。同一套基础设施还支撑了单篇论文页面上的“相关论文”推荐。 这篇文章提供了一个实用性强的生产级混合搜索方案，完全在 PostgreSQL 中实现关键词与语义搜索的结合，无需引入独立的向量数据库。对于为技术内容构建类似系统的工程师非常有价值，因为文中展示了如何借助 Hugging Face 基础设施扩展批量与实时嵌入生成。 该技术栈采用 pgvector 进行向量相似度搜索，Qwen3-Embedding-0.6B 生成文本嵌入，通过 Hugging Face Jobs 使用 NVIDIA L4 GPU 完成批量嵌入生成，HF Buckets 用于存储工件，并通过 HF Inference Endpoints 部署实时嵌入模型。据作者称，混合搜索的效果优于单独使用关键词或语义搜索。

reddit · r/MachineLearning · /u/NielsRogge · 8月25日 12:42

**背景**: 混合搜索是一种信息检索技术，将基于关键词的词汇搜索与基于向量的语义搜索融合为单一排序结果，从而提升相关性与召回率。PostgreSQL 的 pgvector 是一个开源扩展，为关系数据库增加向量相似度检索能力；Qwen3-Embedding-0.6B 是 Qwen3 系列中的紧凑型嵌入模型，可用于检索与微调。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/pgvector/pgvector">GitHub - pgvector/pgvector: Open-source vector similarity search for Postgres · GitHub</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3-Embedding-0.6B">Qwen/Qwen3-Embedding-0.6B · Hugging Face</a></li>
<li><a href="https://www.elastic.co/what-is/hybrid-search">What is hybrid search? How it works and when to use it | Elastic</a></li>

</ul>
</details>

**标签**: `#hybrid search`, `#pgvector`, `#embeddings`, `#PostgreSQL`, `#search engine`

---

<a id="item-8"></a>
## [法国光纤覆盖率 2026 年达 94.9%，引发欧洲宽带讨论](https://cartefibre.arcep.fr/) ⭐️ 7.0/10

根据 ARCEP 的 cartefibre 地图，法国的光纤覆盖率在 2026 年达到 94.9%，标志着 FTTH 接入已接近全民普及。这一里程碑引发了与西班牙的对比——西班牙以 96.79%的覆盖率位居欧洲大国之首。 近乎全覆盖的光纤网络加上有竞争力的价格，巩固了法国作为欧洲宽带领导者的地位，惠及消费者、企业和数字服务。这也凸显了欧洲各国采用率的不均衡：法国开户率为 83.6%，而西班牙将覆盖率转化为订购的效率高得多，达 90%。 94.9%这一数字指的是光纤已覆盖的场所，而非实际开通用户，数据来自 ARCEP 互动地图的 2026 年数据。评论区指出，西班牙到 2025 年 6 月已达 96.79%；法国部署加速还归功于 Free 激进的低价策略，迫使 Orange 等 ISP 在 ADSL 铜线之外持续竞争。

hackernews · nehalem501 · 8月26日 13:32 · [社区讨论](https://news.ycombinator.com/item?id=49448872)

**背景**: 光纤到户（FTTH）利用光纤提供高速、低延迟的互联网，取代基于铜线的 DSL 技术。覆盖率衡量的是建筑物能否申请光纤，而采用率衡量的是家庭是否真的订购。法国 94.9%的覆盖率意味着大多数场所可以接入光纤，但要把这种可用性转化为实际订购，取决于价格、竞争和消费者需求。

**社区讨论**: 评论者总体持正面态度，指出乡村地区现在也能获得优质廉价的光纤，Free 的低价策略迫使其他 ISP 跟进。西班牙被视为标杆，覆盖率 96.79%、采用率 90%，但部分人认为光纤已超出普通用户需求；另有评论联想到美国 FCC 的一项决定，认为其会削弱美国宽带建设。

**标签**: `#fiber optics`, `#broadband`, `#telecom`, `#France`, `#infrastructure`

---

<a id="item-9"></a>
## [RAG 比你想的更简单：全文搜索往往不逊于嵌入](https://www.lighthousenewsletter.com/p/rag-is-simpler-than-you-think) ⭐️ 7.0/10

本文认为，RAG 常常被过度设计，在很多场景下全文搜索就能达到与嵌入向量相当的效果。作者主张先考虑更简单的检索方式，再引入向量搜索的复杂性。 这一点很重要，因为构建 RAG 管线的团队常常认为嵌入向量和向量数据库是必需的，从而增加大量成本和复杂性。这篇文章提出不同看法，鼓励工程师优先评估更便宜、更易移植的全文搜索。 从业者指出，全文搜索简单、可移植且可扩展，而嵌入向量可能需要重新嵌入文本块，且语义匹配效果未必更好。有评论者提到二八法则：全文搜索只需少量精力就能满足大部分需求。

hackernews · j0selit0 · 8月26日 08:39 · [社区讨论](https://news.ycombinator.com/item?id=49445727)

**背景**: 检索增强生成（RAG）是一种让大语言模型在作答前从外部数据源获取相关信息的技术。嵌入（embedding）将文本表示为连续空间中的向量，从而支持语义相似性检索，向量数据库则用于存储这些嵌入。全文搜索通过关键词或词元匹配来查找文档，通常比向量搜索更快、更易理解。这场讨论的核心在于，实践中哪种检索方式最能支撑 RAG。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Retrieval-augmented_generation">Retrieval - augmented generation - Wikipedia</a></li>
<li><a href="https://aws.amazon.com/what-is/embeddings-in-machine-learning/">What is Embedding ? - Embeddings in Machine Learning Explained...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Full-text_search">Full-text search - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 评论者大多认为全文搜索被低估、嵌入向量被高估，有人称这符合二八法则。也有人对又一篇关于 LLM 的 LLM 生成文章表示厌倦，觉得读起来很累。还有读者批评文章没有在首次出现时拼写出“RAG”的全称。

**标签**: `#RAG`, `#embeddings`, `#full-text search`, `#information retrieval`, `#LLM`

---

<a id="item-10"></a>
## [保罗·迪克斯：AI 百万行代码优化令人震撼](https://simonwillison.net/2026/Aug/26/paul-dix/) ⭐️ 6.0/10

保罗·迪克斯在他的博客文章《编程的终结》中描述，一个 AI 系统编写了一百万行代码，并在接下来的两个月里不断优化，最终产出了运行在数百万开发者机器上的可靠软件。西蒙·威利森于 2026 年 8 月 26 日在他的博客上转发了这段引言并表示赞赏。 这段引言突显了 AI 辅助编程和编码代理在生成生产级软件方面的快速进步。它也反驳了“有参考实现所以没什么大不了”的说法，指出验证系统和明确的方向才是真正的关键。 迪克斯承认，有人批评 AI 得益于“预言机”（即已知的参考实现），这使语言间的转换看似更简单，但他认为这种说法低估了这一成就。他强调，只要有合适的验证系统和明确的方向，AI 就能处理高度复杂的软件，并持续优化直到它能正常运行。

rss · Simon Willison · 8月26日 08:07

**背景**: 测试预言机是一种用于判断测试通过或失败的机制或来源，例如软件的旧版本、人类专家或形式化规范。在 AI 代码转换中，原始代码库可以作为预言机，让 AI 有一个已知的目标进行比较。编码代理是集成到 IDE 和终端中的 AI 驱动工具，可帮助开发者编写、审查和维护代码，例如 Cursor 和 OpenCode 等产品。这些进展属于 AI 辅助编程的大趋势，正在重塑软件开发的生产力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Test_oracle">Test oracle - Wikipedia</a></li>
<li><a href="https://testrigor.com/blog/what-is-test-oracle-in-software-testing/">What is Test Oracle in Software Testing? - testRigor AI-Based Automated Testing Tool</a></li>
<li><a href="https://cursor.com/">AI Coding Agent for Building Ambitious Software | Cursor</a></li>

</ul>
</details>

**标签**: `#ai-assisted-programming`, `#coding-agents`, `#software-development`, `#productivity`

---

<a id="item-11"></a>
## [追踪 scikit-learn 中 BayesianRidge 不确定性计算的 bug](https://www.reddit.com/r/MachineLearning/comments/1vym6cn/catching_bugs_in_scikitlearn_d/) ⭐️ 6.0/10

scikit-learn 1.9 修复了 BayesianRidge 预测不确定性计算中的一个 bug；作者通过交互式笔记本对比了 1.8 和 1.9 版本中 predict() 实际计算的公式，逐步追踪了这个改动。 BayesianRidge 被广泛用于带有不确定性估计的回归任务，因此这个 bug 可能悄悄使许多应用中的置信区间失效。这次深入分析展示了版本变更如何影响模型行为，也体现了验证机器学习库代码的价值。 该 bug 特别影响 fit_intercept=True 时的预测方差，因为 predict() 在预测时未像训练过程那样一致地对测试数据进行中心化。笔记本对比了两个版本实际计算的公式，并让读者在揭晓答案前自行寻找差异。

reddit · r/MachineLearning · /u/Lost-Dragonfruit-663 · 8月26日 03:57

**背景**: BayesianRidge 是一种贝叶斯线性回归模型，它估计权重的后验分布，并给出预测均值与标准差。预测方差是量化不确定性的关键输出。1.9 版本的修复确保预测时使用与训练相同的 X_offset_ 对测试数据进行中心化，从而使预测方差在数学上保持一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/scikit-learn/scikit-learn/issues/33757">[BUG] BayesianRidge . predict with return_std=True fails to center test...</a></li>
<li><a href="https://scikit-learn.org/1.9/modules/generated/sklearn.linear_model.BayesianRidge.html">BayesianRidge — scikit-learn 1.9.0 documentation</a></li>

</ul>
</details>

**标签**: `#scikit-learn`, `#BayesianRidge`, `#bug`, `#uncertainty`, `#machine-learning`

---

<a id="item-12"></a>
## [Millwright：一个实验性的 Rust 端到端机器学习框架](https://www.reddit.com/r/MachineLearning/comments/1vyq7m9/millwright_experimenting_with_an_endtoend_machine/) ⭐️ 6.0/10

作者发布了 Millwright，这是一个实验性的开源框架，旨在用 Rust 统一经典机器学习生命周期。该项目不重新实现算法，而是通过通用抽象层与适配器整合现有 Rust 机器学习库。 Millwright 试图填补 Rust 机器学习库之间的集成鸿沟，覆盖预处理、模型选择、可解释性、部署与监控等环节。如果成功，它有望让 Rust 成为训练与生产中更实用的通用执行层，同时继续与 Python/ONNX 生态互操作。 一个关键设计是框架自有一个小型二维数据边界 Frame，使不同后端的模型能参与同一流水线，代价是后端边界处需要转换。项目已包含交叉验证、AutoML、基于 SHAP 的可解释性、ONNX 导出、模型服务、漂移监控以及 Python 绑定。

reddit · r/MachineLearning · /u/olty5000 · 8月26日 07:34

**背景**: 经典机器学习生命周期包括数据接入、探索、预处理、模型选择、拟合、评估、可解释性、部署和监控等步骤。Rust 机器学习生态中有很多功能强大的独立 crate，但开发者经常需要把互不相关的库和数据结构粘合在一起。Python 生态尤其是 scikit-learn 要成熟得多，因此作者将 Millwright 定位为实验项目而非替代品。SHAP 是一种广泛使用的模型解释方法，通过度量特征贡献来解释模型预测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://millwright-rs.dev/">Millwright</a></li>
<li><a href="https://dev.to/mage_ai/end-to-end-machine-learning-lifecycle-1p0i">End-to-end machine learning lifecycle - DEV Community</a></li>
<li><a href="https://blog.paperspace.com/deep-learning-model-interpretability-with-shap/">Deep Learning Model Explainability with SHAP</a></li>

</ul>
</details>

**标签**: `#Rust`, `#Machine Learning`, `#Framework`, `#Open Source`, `#MLOps`

---

<a id="item-13"></a>
## [在信息不完整下建模用药提醒智能体：征求建议](https://www.reddit.com/r/MachineLearning/comments/1vy8a9g/d_looking_for_advice_modelling_a_medicinereminder/) ⭐️ 6.0/10

一位研究者正在 r/MachineLearning 上询问：在关于患者的信息不完整时，用药提醒智能体需要在“提醒、等待、通知照护者”之间做决策，用 POMDP/信念状态方法是否合适。他们还希望获得更简单的替代方案、相关论文和实际实现建议。 这个问题反映了现实中的医疗 AI 挑战：构建提醒系统时，既要处理“患者是否已服药”的不确定性，又要避免提醒疲劳和不安全的升级处理。相关讨论可能帮助从业者在理论上优雅的 POMDP 与更简单、更易部署的模型之间做出选择，以应对部分可观测条件下的序贯决策。 该智能体在每个相关时刻有三个动作——发送提醒、等待或通知照护者——而隐藏状态包括是否已服药、患者是否在场/留意，以及是否存在依从性障碍。发帖者明确比较了 POMDP/信念状态强化学习与上下文赌博机、带工程特征的 MDP，以及基于规则加不确定性阈值的系统。

reddit · r/MachineLearning · /u/Senior_Disaster_7307 · 8月25日 18:34

**背景**: POMDP 是 MDP 的推广：智能体无法直接观测底层状态，只能依据信念状态（对可能状态的概率分布）来行动。上下文赌博机是一类更简单的序贯决策问题，动作不会改变奖励分布，因此适合单次决策，而不适合多步状态变化。这一区别对于判断用药提醒智能体是否需要完整的 POMDP 框架、还是可以用更轻量的方法，至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/POMDP">POMDP</a></li>
<li><a href="https://en.wikipedia.org/wiki/Contextual_bandit_algorithm">Contextual bandit algorithm</a></li>

</ul>
</details>

**标签**: `#POMDP`, `#reinforcement learning`, `#healthcare AI`, `#sequential decision making`, `#partial observability`

---

<a id="item-14"></a>
## [Unbounded Labs 发布 2.82B 参数怀旧大模型 Bart，用 1931 年前英语训练](https://www.reddit.com/r/MachineLearning/comments/1vx94er/bart_a_vintage_llm_r/) ⭐️ 6.0/10

Unbounded Labs 发布了 Bart，这是一个从头训练的 2.82B 参数大语言模型，使用了 1931 年之前的英语文本共 20.1B tokens 进行训练。该模型提供在线演示，并在 Hugging Face 上开源了模型权重、数据集、训练代码和基准。 该实验测试了大语言模型是否能从历史文本中独立得出科学结论，这是 Demis Hassabis 提出的问题。项目还引入了新的怀旧领域基准和开放的 SFT 数据集，为专业语言建模研究提供了资源。 训练成本约 807 美元，在单块 H100 上 5 天完成，MFU 达 60%。团队将哈佛机构图书数据集从 242B tokens 清洗至 23B tokens，创建了包含 20 个任务的 Vintage CORE 基准套件，并发布了 41.6 万个基于 1930 年代前文本的分级 SFT 问答对。

reddit · r/MachineLearning · /u/soggydoggy8 · 8月24日 17:20

**背景**: 大语言模型（LLM）是在海量文本语料上预训练的神经网络，目标是预测下一个词元，之后通常通过监督微调（SFT）来使其遵循指令。该项目将这一流程应用于 1931 年前的英语这一小众语料，因为标准基准假设的是现代语言，所以需要构建新基准。消融研究通过移除模型或训练流程中的某些部分来测试其影响，是团队文章描述的核心方法论之一。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ablation_(artificial_intelligence)">Ablation (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/supervised-fine-tuning-sft-for-llms/">Supervised Fine - Tuning ( SFT ) for LLMs - GeeksforGeeks</a></li>
<li><a href="https://cameronrwolfe.substack.com/p/understanding-and-using-supervised">Understanding and Using Supervised Fine - Tuning ( SFT ) for...</a></li>

</ul>
</details>

**标签**: `#LLM`, `#NLP`, `#Training`, `#Vintage Corpus`, `#Research`

---

<a id="item-15"></a>
## [提出一种公平基准，将智能体 harness 与模型能力分离](https://www.reddit.com/r/MachineLearning/comments/1vy0ki7/what_would_a_fair_benchmark_for_agent/) ⭐️ 6.0/10

作者提出了一个 2×2 实验设计，将工作流架构（整体式 vs. 分解式）与模型路由策略（仅用前沿模型 vs. 最便宜可用并按能力分级失败后升级）交叉组合，以在编码智能体基准测试中把 harness 效应与模型能力分离开来。目前尚无实验结果，该帖是一个寻求社区反馈的预注册式提案。 当前的编码智能体基准将模型与 harness 合并为单一分数，导致失败几乎无法诊断。该提案可能推动该领域走向更受控、更可证伪的智能体评估，这在智能体系统和路由策略日益普及的今天尤为重要。 该设计冻结了原始任务、源码修订版、工具、重试预算、验收标准、验证器版本和验证器，所有实验单元都依据相同的最终交付结果来评判。主要指标包括每个独立验收变更的成本、误接受、误拒绝、首轮通过验收率、验证时间以及三次全新运行的可复现性；其中预算归一化被标为最令人不满意的混杂因素。

reddit · r/MachineLearning · /u/jonah_omninode · 8月25日 13:55

**背景**: 编码智能体基准在软件任务上评估由 LLM 驱动的智能体，但最终分数既反映模型的内在能力，也反映其外围系统——包括上下文组装、任务分解、工具设计、重试策略和验收门控。最近的证据表明，仅改变 harness 就可能显著改变分数，例如在保持模型不变的情况下，Terminal-Bench 2.0 上出现了 13.7 分的提升，这凸显了隔离这些变量的必要性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://groowlabs.com/blog/harness-vs-model/">Agent Harness vs Model: Does the Harness Affect Scores?</a></li>
<li><a href="https://dev.to/tessl-io/agent-benchmarks-need-to-measure-the-whole-workflow-4hhm">Agent Benchmarks Need To Measure The Whole Workflow</a></li>

</ul>
</details>

**标签**: `#agent benchmarks`, `#LLM agents`, `#evaluation`, `#ML research`, `#benchmark design`

---