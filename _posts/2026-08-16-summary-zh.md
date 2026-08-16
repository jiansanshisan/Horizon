---
layout: default
title: "Horizon Summary: 2026-08-16 (ZH)"
date: 2026-08-16
lang: zh
---

> 从 25 条内容中筛选出 14 条重要资讯。

---

1. [Anthropic 公布 Claude 模型的官方系统提示词](#item-1) ⭐️ 8.0/10
2. [AI 时代软件工程基础更加重要](#item-2) ⭐️ 8.0/10
3. [SSOG-Attention：以 O(N√N)复杂度实现亚二次注意力，替代 SDPA](#item-3) ⭐️ 8.0/10
4. [重新审视 ECA-Net：批评认为跨通道交互假设存在缺陷](#item-4) ⭐️ 8.0/10
5. [Qwen3.6-27B 的 Jacobian lens 无需重拟合即可迁移到 Qwen3.8-27B](#item-5) ⭐️ 8.0/10
6. [BDH-CQ：150M 参数模型打破 ARC-AGI-1 成本-准确率边界](#item-6) ⭐️ 8.0/10
7. [研究论文用“肾脏失望”替代“肾衰竭”暴露改写工具滥用](#item-7) ⭐️ 7.0/10
8. [随笔：独处与新思想的脆弱诞生](#item-8) ⭐️ 7.0/10
9. [Amodei：AI 的不信任源于更广泛的信任危机，而非风险警告](#item-9) ⭐️ 7.0/10
10. [不要分类，去幻觉：用 LLM 幻觉与向量嵌入给内容打标](#item-10) ⭐️ 7.0/10
11. [Firefox for iOS 现在内置原生广告拦截器](#item-11) ⭐️ 6.0/10
12. [CORS Chat：一款用于测试 OpenAI 兼容聊天端点的浏览器工具](#item-12) ⭐️ 6.0/10
13. [如何解决线性注意力在长距离记忆中的瓶颈？](#item-13) ⭐️ 6.0/10
14. [《星空》动物数据集：2 万张图像、50 个物种用于分类](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Anthropic 公布 Claude 模型的官方系统提示词](https://platform.claude.com/docs/en/release-notes/system-prompts) ⭐️ 8.0/10

Anthropic 已在其 Platform 文档发布说明中公开了 Claude 模型所使用的官方系统提示词。此次发布让开发者与研究人员得以一窥决定 Claude 行为的内部指令。 系统提示词是塑造大语言模型行为的核心要素，因此这种透明化有助于从业者理解、调试并对比模型随时间的变更。这也为其他 AI 实验室更开放地公开模型引导方式树立了榜样。 Simon Willison 整理了这些提示词的 git 提交历史，以便对比版本差异；早期提示词约有 300 词，最新版本已超过 3000 词。Opus 5 的系统提示词甚至说明，原本打算发给 Claude Fable 5 的请求可能会被安全路由机制重定向到 Opus 5。

hackernews · tosh · 8月16日 12:48 · [社区讨论](https://news.ycombinator.com/item?id=49319556)

**背景**: 系统提示词是在用户消息之前提供给大语言模型的初始指令，用于定义模型的角色、语气、行为和边界。LLM 部署者借助系统提示词在不同情境下保持回复一致，而其内容会显著影响输出质量与安全性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://promptengineering.org/system-prompts-in-large-language-models/">System Prompts in Large Language Models</a></li>
<li><a href="https://arxiv.org/html/2505.21091v2">Position is Power: System Prompts as a Mechanism of Bias in Large Language Models (LLMs)</a></li>
<li><a href="https://www.kern-it.be/en/definitions/system-prompt/">System prompt: the hidden instruction that frames your LLM | KERN-IT</a></li>

</ul>
</details>

**社区讨论**: Hacker News 上的评论者欣赏 Simon Willison 的差异对比工具，并讨论为何像 Opus 这样强大的模型还需要诸如“检查图片是否真的上传”这类明确的指令。还有用户质疑 HN 管理员在移除对 AI 持负面态度的帖子。

**标签**: `#AI`, `#LLM`, `#Claude`, `#system-prompts`, `#Anthropic`

---

<a id="item-2"></a>
## [AI 时代软件工程基础更加重要](https://rhonabwy.com/2026/08/15/software-engineering-fundamentals-matter-more-than-ever/) ⭐️ 8.0/10

文章认为，在 AI 生成代码的时代，软件工程基础（如可维护性、可组合性和可调试性）比以往任何时候都更加重要。文章指出，即使是最先进的 LLM 在高质量软件所需的细微决策和架构推理方面仍存在不足。 随着 AI 生成代码的普及，软件的质量和可维护性在很大程度上取决于工程师对基础知识的掌握。这篇文章凸显了行业日益严峻的挑战：在利用 AI 速度的同时，不损害代码的长期健康。 文章强调，仅仅生成代码是不够的；软件必须可调试、可维护、有层次且可组合，这需要大量深思熟虑的推理。文章指出，LLM 经常对错误状态和其他设计决策做出无根据的假设，导致结构杂乱无章。

hackernews · ingve · 8月15日 22:31 · [社区讨论](https://news.ycombinator.com/item?id=49314902)

**背景**: 近年来，GitHub Copilot 和 ChatGPT 等 AI 编程助手广受欢迎，允许开发者通过自然语言提示生成代码。然而，这些模型在庞大的代码库上训练，生成的代码往往看似合理，但缺乏经验工程师提供的架构一致性、错误处理细微差别和可维护性。文章认为，扎实掌握软件工程基础对于有效评估、整合和重构 AI 生成的代码至关重要。

**社区讨论**: 评论者普遍认为，AI 生成的代码虽然一致性高，但缺乏人类工艺的深度，有人将其比作宜家家具；同时指出模型常生成混乱的结构并做出多余的假设。一些人主张通过 AI 加速的工作流学习基础知识，还有人讥讽地将 LLM 比作 Excel。总体共识是核心工程技能仍然不可或缺。

**标签**: `#software-engineering`, `#AI`, `#code-quality`, `#maintainability`, `#LLM`

---

<a id="item-3"></a>
## [SSOG-Attention：以 O(N√N)复杂度实现亚二次注意力，替代 SDPA](https://www.reddit.com/r/MachineLearning/comments/1vpt6ay/ssogattention_sum_of_separable_gaussians_as_a/) ⭐️ 8.0/10

作者 4rtemi5 提出了 SSOG-Attention，一种用可分高斯和替代缩放点积注意力的新型注意力机制。它通过为每个头学习少量高斯原子，并根据查询令牌对它们进行几何导向，实现了 O(N·√N·d)的复杂度。 这项工作提供了一种实用的亚二次注意力替代方案，解决了 Transformer 中 SDPA 的 O(N²)扩展瓶颈。实验表明它在 CIFAR-100 上优于 SDPA，在 ImageNet-1K 上性能相当且收敛更快，有望推动大规模视觉模型的高效化。 SSOG 将注意力分解为高斯函数的可分和，将复杂度从 O(N²·d)降至 O(N·√N·d)。博客文章和开源代码位于 pisoni.ai/posts/ssog 和 github.com/4rtemi5/ssog；作者说明部分代码和博客内容使用了 AI 辅助。

reddit · r/MachineLearning · /u/4rtemi5 · 8月16日 10:06

**背景**: 缩放点积注意力（SDPA）是 Transformer 的核心机制，它计算所有令牌对之间的查询-键相似度，对于 N 个维度为 d 的令牌，代价为 O(N²·d)。多元高斯函数可以写成多个一维高斯的乘积（即可分形式），而一组可分高斯的和可以逼近复杂核函数并保持可分解性。SSOG 利用这一数学结构，避免显式比较每个查询和每个键，从而在保持竞争力性能的同时实现亚二次扩展。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Sum_of_normally_distributed_random_variables">Sum of normally distributed random variables - Wikipedia</a></li>
<li><a href="https://docs.pytorch.org/docs/stable/generated/torch.nn.functional.scaled_dot_product_attention.html">torch.nn.functional.scaled_dot_product_attention</a></li>
<li><a href="https://medium.com/@saraswatp/understanding-scaled-dot-product-attention-in-transformer-models-5fe02b0f150c">Understanding Scaled Dot-Product Attention in Transformer Models | by Prashant S | Medium</a></li>

</ul>
</details>

**标签**: `#Attention`, `#Efficient Transformers`, `#Machine Learning`, `#Computer Vision`, `#Sub-quadratic`

---

<a id="item-4"></a>
## [重新审视 ECA-Net：批评认为跨通道交互假设存在缺陷](https://www.reddit.com/r/MachineLearning/comments/1vptaw9/revisiting_the_efficient_channel_attention_paper/) ⭐️ 8.0/10

一篇 Reddit 帖子对 2019 年的 ECA-Net 论文进行了批判性重新审视，认为其核心假设——跨通道交互带来了性能提升——在概念上存在缺陷。作者在国际象棋残局表数据上的实验显示，k=1 的 ECA 与 k=3 的 ECA 表现几乎一样好，削弱了论文所称的机制。 ECA-Net 是一个被高度引用的注意力机制（引用超过 12000 次），因此一个有实验支持的概念性批评可能会改变研究人员对通道注意力的理解。这也可能鼓励深度学习领域对架构设计进行更严谨的论证。 该帖在 6 子国际象棋残局表数据上比较了 IdentityGate、SE、ECA（k=3）、ECA（k=1）和 CenterMasked 变体。ECA k=3 的测试准确率为 96.68%，而 ECA k=1 为 96.61%，表明更宽核带来的跨通道交互并非关键。作者将通道维度类比为没有内在拓扑的表格数据，称 ECA 是一种“被诅咒的卷积”。

reddit · r/MachineLearning · /u/arkuto · 8月16日 10:13

**背景**: ECA-Net（高效通道注意力）是 Wang 等人在 2019 年提出的轻量级通道注意力模块，建立在 Squeeze-and-Excitation（SE）块的基础上。SE 先做全局平均池化，再用两个全连接层来重新校准通道权重；而 ECA 用一维卷积替代了这些全连接层，在通道维度上捕获局部跨通道交互，参数要少得多。ECA 论文认为，避免降维并使用适当的跨通道交互对性能很重要。通道注意力机制被广泛用于 CNN，以选择性地强调信息量大的特征通道。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/1910.03151">[1910.03151] ECA-Net: Efficient Channel Attention for Deep Convolutional Neural Networks</a></li>
<li><a href="https://arxiv.org/abs/1709.01507">[1709.01507] Squeeze-and-Excitation Networks - arXiv.org</a></li>
<li><a href="https://www.emergentmind.com/topics/efficient-channel-attention-eca-mechanisms">Efficient Channel Attention Mechanisms - emergentmind.com</a></li>

</ul>
</details>

**标签**: `#Attention Mechanisms`, `#Deep Learning`, `#CNN`, `#Paper Critique`, `#Machine Learning`

---

<a id="item-5"></a>
## [Qwen3.6-27B 的 Jacobian lens 无需重拟合即可迁移到 Qwen3.8-27B](https://www.reddit.com/r/MachineLearning/comments/1vpa5cv/survival_of_the_fitted_qwen3627bs_jacobian_lens/) ⭐️ 8.0/10

一个拟合到 Qwen3.6-27B 上的 Jacobian lens（雅可比透镜）无需重新拟合就能读取和操控 Qwen3.8-27B。在读取测试中，第 48 层的中位实体排名在原生模型上为 4，迁移后为 17，而新模型在第 24 层表现更好；旧透镜的操控方向还能让两个模型在生成时都去掉“paradox”一词。 这表明可解释性工具能够在模型版本更新后继续使用，因此监控流水线不必为每个检查点重新拟合透镜。这也为机制可解释性提供了一条跨版本复用工具的路径，从而节省算力并支持一致的对比。 这两个模型共享 64 层、隐藏维度和分词器；3.8 版本在 3.6 发布 113 天后发布，训练关系未公开。迁移后的透镜仍能让潜在实体保持在 248,320 词表顶部附近，而原始 logit lens 的排名在 1e3 到 1e4 之间；WikiText 下一个词预测的迁移成本在网络中层约为 1.2 到 1.3 倍，到第 48 层约为 2 倍。作者指出，该设计无法完全区分透镜失配与模型变化。

reddit · r/MachineLearning · /u/imstilllearningthis · 8月15日 18:24

**背景**: Jacobian lens 是 Anthropic 提出的一种可解释性技术，通过分析隐藏状态如何影响后续词元概率来读取“无声”的潜在表征；它通常拟合到某个特定检查点，并以层×位置视图呈现。logit lens 是一种更简单的基线方法，将反嵌入矩阵应用于中间隐藏状态，以解码可能的输出。Qwen3.6-27B 和 Qwen3.8-27B 是架构和分词器相同的开源权重大语言模型，因此该测试可以隔离版本更新对已拟合工具的影响。在此之前，这类透镜的跨版本可迁移性尚未被测试。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/anthropics/jacobian-lens">GitHub - anthropics/jacobian-lens: Companion code for the ...</a></li>
<li><a href="https://explainx.ai/blog/what-is-j-lens-jacobian-lens-claude-interpretability-2026">What Is the J-Lens? Anthropic Jacobian Lens Guide - explainx.ai</a></li>
<li><a href="https://grokipedia.com/page/Logit_lens">Logit lens</a></li>

</ul>
</details>

**标签**: `#interpretability`, `#Jacobian lens`, `#LLM`, `#mechanistic interpretability`, `#transfer learning`

---

<a id="item-6"></a>
## [BDH-CQ：150M 参数模型打破 ARC-AGI-1 成本-准确率边界](https://www.reddit.com/r/MachineLearning/comments/1vov5r5/bdhcq_incontext_learning_with_recurrent_latent/) ⭐️ 8.0/10

论文提出了 BDH-CQ，一个 150M 参数的推理模型，通过循环潜在推理实现上下文学习。其在 ARC-AGI-1 上取得 29.5%的 pass@2，每任务计算成本约 0.00070 美元，据称打破了此前的成本-准确率帕累托前沿。 这一成果意义重大，因为它表明参数效率极高的模型也能以极低成本应对公认困难的一般智能基准，挑战了前沿性能必须依赖巨型 LLM 的假设。同时，它凸显了循环潜在推理作为显式思维链（chain-of-thought）之外的一种有前景的上下文适应方式。 训练中既未使用任务标识符，也未使用评估任务的演示对，推理时也不更新任何参数。中间推理状态从不被解码为语言；输入会持续更新模型的循环记忆，查询则通过在潜在空间中的迭代计算来求解。

reddit · r/MachineLearning · /u/moschles · 8月15日 06:18

**背景**: ARC-AGI-1 于 2019 年推出，旨在测试系统的泛化能力和组合推理能力，尽管 LLM 规模大幅扩展，它在多年内仍基本未被攻克。循环潜在推理在测试时于潜在空间中迭代循环模块，从而在不生成中间语言 token 的情况下进行更深的计算。BDH-CQ 将这一思想与上下文学习结合，把任务示范存储在循环记忆中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2608.09888">[2608.09888] BDH-CQ: In-Context Learning with Recurrent ...</a></li>
<li><a href="https://www.explainx.ai/blog/pathway-bdh-cq-150m-post-transformer-arc-agi-august-2026">Pathway BDH-CQ: 150M Model, 11x Cheaper Than GPT-5.6 ...</a></li>
<li><a href="https://arcprize.org/arc-agi/1">ARC-AGI-1</a></li>

</ul>
</details>

**标签**: `#Machine Learning`, `#In-Context Learning`, `#Recurrent Neural Networks`, `#ARC-AGI`, `#Reasoning`

---

<a id="item-7"></a>
## [研究论文用“肾脏失望”替代“肾衰竭”暴露改写工具滥用](https://scholar.google.com/scholar?q=%22kidney+disappointment%22) ⭐️ 7.0/10

在 Google Scholar 中搜索“kidney disappointment”会出现使用这一无意义短语替代标准医学术语“kidney failure”（肾衰竭）的学术论文。这类“折磨短语”越来越多，证明研究人员和论文工厂正使用改写工具掩盖已发表文献中的抄袭行为。 这凸显了科学出版中日益严重的诚信问题：基于 AI 的改写削弱了对同行评审文献的基本信任。编辑、审稿人和机构需要新的检测策略来识别并撤回受影响的论文。 “kidney disappointment”是研究人员记录到的数千个“折磨短语”之一，其他例子包括用“counterfeit consciousness”（伪造意识）替代“artificial intelligence”（人工智能）。一些词组，包括“kidney disappointment”，早在 2021 年就已出现——早于现代大语言模型的普及——这使得“由 AI 生成”这一假设更加复杂。

hackernews · Alifatisk · 8月16日 12:22 · [社区讨论](https://news.ycombinator.com/item?id=49319389)

**背景**: 学术写作通常要求使用精确、标准的术语，因此怪异替代词会立刻引起注意。“折磨短语”一词由 2021 年一篇 arXiv 研究提出，用来描述“counterfeit consciousness”替代“artificial intelligence”这类怪异表达。Nature 等媒体的后续报道将这类短语与论文工厂联系起来，这些工厂批量生产稿件，并使用改写软件降低查重相似度得分。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.editage.com/insights/tortured-phrases-what-they-are-how-they-are-detected-and-how-to-avoid-them">Tortured phrases: What they are, how they are detected, and how to avoid them</a></li>
<li><a href="https://arxiv.org/abs/2107.06751">[2107.06751] Tortured phrases: A dubious writing style emerging in science. Evidence of critical issues affecting established journals</a></li>
<li><a href="https://www.nature.com/articles/d41586-021-02134-0">'Tortured phrases' give away fabricated research papers</a></li>

</ul>
</details>

**社区讨论**: 评论提出了相互竞争的解释：有人认为“kidney disappointment”是改写工具用来规避查重检测的产物，也有人认为是翻译错误，并举出“water goat”指代“hydraulic ram”等历史例子。有评论者指出，该词出现在 2021 年的论文中，早于当前大语言模型，因此削弱了纯 AI 生成的解释。

**标签**: `#academic integrity`, `#AI-generated content`, `#plagiarism`, `#research publishing`, `#tortured phrases`

---

<a id="item-8"></a>
## [随笔：独处与新思想的脆弱诞生](https://www.henrikkarlsson.xyz/p/good-ideas) ⭐️ 7.0/10

亨里克·卡尔森（Henrik Karlsson）于 2023 年发表了一篇反思性随笔，探讨了孕育新想法的心理状态与环境，认为初生的想法是脆弱的，需要独处才能存活。这篇文章获得了广泛共鸣，评分 7/10，并在 Hacker News 等平台上引发了 57 条评论的讨论。 这篇随笔为关于创造力的长期文化讨论做出了贡献，探讨了在快节奏、充满评判的环境中如何保护早期思考。它引发的高参与度表明，这个话题深深触动了知识工作者、研究人员和创作者，他们都在努力在外部压力下保持内心的指南针。 随笔强调新想法很容易被“一声嗤笑或一个哈欠扼杀”，并主张刻意培养独处和非评判的心理空间。多位评论者指出，作者关于独处的论断可能过于绝对，并举例说他们最好的工作往往发生在协作性的学术或团队环境中。

hackernews · felixbraun · 8月15日 20:54 · [社区讨论](https://news.ycombinator.com/item?id=49314235)

**背景**: 这篇随笔承袭了一个悠久的智识传统——从庞加莱到现代心理学——将创造力与放松、发散性注意力和内心安全感联系在一起。亨里克·卡尔森以其博客“逃离平原”上关于思考与技术的深思熟虑的文章而闻名。这篇文章之所以引起广泛共鸣，是因为它阐述了一个常见的张力：一方面需要孤立，另一方面又受益于合作。

**社区讨论**: 讨论总体上是赞赏性的，几位评论者分享了个人轶事，既支持又补充了文章的论点。一些人强烈认同新想法是脆弱的，而另一些人则指出学术和团队环境是反例，认为合适的合作者非但不会压制创造力，反而会增强创造力。

**标签**: `#creativity`, `#psychology`, `#essay`, `#thinking`, `#ideas`

---

<a id="item-9"></a>
## [Amodei：AI 的不信任源于更广泛的信任危机，而非风险警告](https://simonwillison.net/2026/Aug/16/dario-amodei/) ⭐️ 7.0/10

Anthropic 首席执行官 Dario Amodei 反驳了“AI 领导者的风险警告是公众不信任 AI 的主要原因”这一观点。他在一条推文中表示，公众的负面看法从根本上说是对公司、政府和科技行业的信任危机，只有切实的成就（例如真正治愈癌症）才能恢复信心，而不是营销。 这一点很重要，因为一位 AI 领域的领军人物正在直接挑战一种常见说法，即 AI 的末日论本身加剧了公众的抵制。他的立场可能影响 AI 公司的沟通策略，以及政策制定者如何构建关于 AI 信任与监管的讨论。 Amodei 明确承认，对包括 Anthropic 在内的 AI 公司最准确的批评是，它们尚未兑现惠及世界的重大承诺。他驳回了“采用光鲜亮丽的积极营销活动”的建议，称这类宣传具有欺骗性且老套。

rss · Simon Willison · 8月16日 15:05

**背景**: Dario Amodei 是 Anthropic 的联合创始人兼首席执行官，该公司是 Claude AI 模型背后的企业。他的言论出现在公众对 AI 普遍持怀疑态度的背景下，这种怀疑因 AI 快速部署、对失业的担忧以及研究人员和高管对生存风险的高调警告而加剧。Amodei 的观点将问题重新定义为数十年来对机构信任的侵蚀，并认为 AI 只是这种不信任的最新焦点。他强调“真正治愈癌症”也反映了关于 AI 公司应该优先考虑宏大承诺还是可验证的实际益处的更广泛辩论。

**标签**: `#AI`, `#trust`, `#Anthropic`, `#public perception`, `#Dario Amodei`

---

<a id="item-10"></a>
## [不要分类，去幻觉：用 LLM 幻觉与向量嵌入给内容打标](https://simonwillison.net/2026/Aug/14/dont-classify-hallucinate/) ⭐️ 7.0/10

Simon Willison 介绍了 Doug Turnbull 的方法：先让 LLM 凭空“幻想”出可能适合内容的标签，不向其提供现有词表，然后用向量嵌入把幻想标签映射到大型分类体系中距离最近的真实标签。Willison 提到自己的博客有 1,856 个标签，多到无法直接喂给 LLM。 这为解决“标签词表太大、无法直接塞给 LLM”的上下文窗口和成本限制提供了实用思路。它让博客、电商目录和企业分类体系的大规模内容打标与搜索分类变得更加可行。 Doug Turnbull 的示例提示要求模型生成“前所未见的新分类”，并给出六个目标标签形态的例子，例如「Furniture / Living Room Furniture / Coffee Tables & End Tables / Coffee Tables」。随后不是做字符串精确匹配，而是用向量嵌入把幻想标签与现有具体标签进行比较。

rss · Simon Willison · 8月14日 21:54

**背景**: 该方法和 HyDE（Hypothetical Document Embeddings，假设文档嵌入）思路类似：先用 LLM 生成一个假设性文档或结果，再做向量检索，从而提升召回效果。向量嵌入会把文本转换成数字向量，使语义相近的词在向量空间中彼此靠近；这样即使「brown coffee table」这样幻想出来的标签和官方标签措辞完全不同，也能在语义上匹配到正确分类。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.haystack.deepset.ai/docs/hypothetical-document-embeddings-hyde">Hypothetical Document Embeddings (HyDE) | Haystack Documentation</a></li>
<li><a href="https://qubittool.com/blog/embedding-vector-complete-guide">Vector Embeddings: Models, Search & RAG Guide (2026)</a></li>

</ul>
</details>

**标签**: `#LLM`, `#embeddings`, `#information retrieval`, `#tagging`, `#search`

---

<a id="item-11"></a>
## [Firefox for iOS 现在内置原生广告拦截器](https://support.mozilla.org/en-US/kb/block-ads-firefox-ios) ⭐️ 6.0/10

Mozilla 已在其官方支持文章中说明，为 Firefox for iOS 添加了原生广告拦截器。用户无需安装单独扩展即可直接在浏览器中拦截广告。 这件事很重要，因为 iOS 上的浏览器受限于 Apple 的 WebKit 引擎，扩展支持也有限，因此内置广告拦截器对注重隐私的 Firefox 用户来说是一个有意义的便利。它还可能减少用户对第三方内容拦截应用的依赖。 社区评论指出，这个新的原生功能可能未使用 Apple 的 Content Blocker API，因此用户无法选择自定义过滤列表或 AdGuard、uBlock 等提供商。Mozilla 的另一款隐私浏览器 Firefox Focus 多年前就已在 iOS 上提供系统级内容拦截选项。

hackernews · pentagrama · 8月16日 12:58 · [社区讨论](https://news.ycombinator.com/item?id=49319633)

**背景**: 在 iOS 上，所有浏览器都必须使用 Apple 的 WebKit 引擎（WKWebView），而且 Apple 限制了第三方浏览器扩展。Safari Content Blocker API 是实现原生内容拦截的标准方式，让应用在设备本地应用拦截规则。Firefox Focus 早已使用这一机制，这可能启发了新的内置功能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/WebView">WebView</a></li>
<li><a href="https://github.com/tranthienhau/safari-ad-blocker">GitHub - tranthienhau/ safari -ad- blocker : Safari Content Blocker iOS...</a></li>
<li><a href="https://webpurely.com/">Purely - Native Safari Ad Blocker | Clean, Fast, Private</a></li>

</ul>
</details>

**社区讨论**: 评论者指出，适用于 Safari 的 uBlock Origin Lite 在 iOS 上已经很好用，而且 Firefox Focus 多年前就包含了类似的广告拦截器。还有人质疑为什么 Firefox 仍然不支持 Content Blocker API 或扩展，并提到 Orion 作为支持 iOS 扩展的替代浏览器。

**标签**: `#Firefox`, `#iOS`, `#adblock`, `#privacy`, `#browser`

---

<a id="item-12"></a>
## [CORS Chat：一款用于测试 OpenAI 兼容聊天端点的浏览器工具](https://simonwillison.net/2026/Aug/15/cors-chat/) ⭐️ 6.0/10

Simon Willison 发布了 CORS Chat，这是一个基于浏览器的 Web UI，用于测试支持 CORS 的 OpenAI-Responses 兼容聊天端点。它已针对 LM Studio（使用 --cors 选项）和 OpenRouter 进行测试，并能在令牌流式传输时逐步渲染 SVG 图像。 该工具解决了开发人员希望直接从基于浏览器的应用程序调用本地或远程 AI 聊天端点时的一个常见痛点——CORS 限制往往会阻止请求。它使测试 OpenAI 兼容服务变得更加容易和便捷，特别是对于使用 LM Studio 等本地 LLM 服务器的开发人员。 对话会持久化保存在浏览器中，并可以复制粘贴的形式导出为 JSON。该工具是使用 GPT-5.6-Sol xhigh 构建的，并且能够检测正在生成的 SVG 图像，在令牌仍在流式传输时于聊天中逐步渲染这些图像。

rss · Simon Willison · 8月15日 14:49

**背景**: OpenAI 的 Responses API 于 2025 年 3 月发布，是一个用于生成模型响应的开发者接口，支持文本和图像输入，并能构建有状态的智能体应用程序。LM Studio 是一款流行的本地推理软件，允许用户在个人电脑上运行 LLM，并提供兼容 OpenAI 的 API 端点。CORS（跨源资源共享）是一种浏览器安全机制，限制网页向不同域名发起请求，因此一个支持 CORS 的专用工具对于在浏览器中测试此类端点非常有用。对于在 NVIDIA DGX Spark 或 M5 MacBook Pro 等设备上本地运行模型的开发人员，CORS Chat 提供了一种快速验证端点兼容性的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LM_Studio">LM Studio</a></li>
<li><a href="https://developers.openai.com/api/reference/responses/overview">Responses Overview | OpenAI API Reference</a></li>
<li><a href="https://www.nvidia.com/en-us/products/workstations/dgx-spark/">Personal AI Supercomputer Powered by Blackwell | NVIDIA DGX Spark</a></li>

</ul>
</details>

**标签**: `#CORS`, `#AI`, `#developer-tools`, `#chat-endpoints`, `#LM-Studio`

---

<a id="item-13"></a>
## [如何解决线性注意力在长距离记忆中的瓶颈？](https://www.reddit.com/r/MachineLearning/comments/1vpqwdc/how_can_we_solve_longrange_recall_in_linear/) ⭐️ 6.0/10

一位从事 DNA 序列建模的研究者报告称，线性注意力模型在“大海捞针”基准测试中仅能达到约 25%的召回率，HyenaDNA 也只有约 25–27%。他们希望找到能够扩展到百万级 token DNA 序列的架构方案。 长距离记忆对于基因组建模至关重要，因为 DNA 序列可达 100 万 token，而这一结果凸显了压缩状态注意力机制的关键局限。可靠的次二次复杂度检索不仅有利于基因组学，也有利于其他高效长上下文序列建模任务。 一个仅 16K 上下文的小型线性注意力模型能达到 50–60%的召回率，表明随着上下文长度增加，性能会急剧下降。外部记忆、滑动窗口机制以及线性-softmax 混合架构等现有方案被认为不够充分，研究者自己的修改也只将召回率提升到约 27%。

reddit · r/MachineLearning · /u/No-Coffee-8227 · 8月16日 07:47

**背景**: 线性注意力通过低秩或基于核的近似替代 softmax 核，将序列长度上的计算复杂度从二次降为线性，但代价是使用固定大小的压缩状态。“大海捞针”（NIAH）测试衡量模型能否在长上下文中检索到被埋藏的特定信息；对于 DNA 而言，A/C/G/T 四种碱基的随机基线是 25%。HyenaDNA 是基于 Hyena 算子构建的长程基因组基础模型，利用隐式卷积和门控机制可达到最多 100 万 token 的上下文长度。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/linear-attention-mechanism">Linear Attention Mechanism</a></li>
<li><a href="https://github.com/HazyResearch/hyena-dna">GitHub - HazyResearch/hyena-dna: Official implementation for HyenaDNA, a long-range genomic foundation model built with Hyena · GitHub</a></li>
<li><a href="https://grokipedia.com/page/needle_in_the_haystack">Needle in the Haystack</a></li>

</ul>
</details>

**标签**: `#linear attention`, `#long-range recall`, `#DNA modeling`, `#sequence modeling`, `#machine learning`

---

<a id="item-14"></a>
## [《星空》动物数据集：2 万张图像、50 个物种用于分类](https://www.reddit.com/r/MachineLearning/comments/1vp9q5v/dataset_starfield_fauna_20000_images_in_50/) ⭐️ 6.0/10

一个名为“Starfield Fauna”的新图像分类数据集已发布，包含来自游戏《星空》的 20,000 张图像，涵盖 50 个物种类别。图像通过 PowerShell 脚本从视频中提取。 该数据集的意义在于，它为训练计算机视觉模型提供了一种可控且低成本的替代方案，尤其适用于难以在野外拍摄的物种。它有助于合成到真实的迁移学习、领域自适应以及细粒度图像分类的研究。 该数据集通过每个物种生物群系约两分钟的视频构建，其中白天和夜间各一分钟，通常分为两段 30 秒拍摄。镜头多为居中特写以区分物种，并在训练、验证和测试集之间对生物群系比例进行了部分归一化处理。

reddit · r/MachineLearning · /u/eccLykta · 8月15日 18:06

**背景**: 来自 3D 模型或视频游戏的合成图像数据越来越多地被用于扩充深度学习模型的训练集。《星空》是 Bethesda Game Studios 于 2023 年推出的太空主题动作角色扮演游戏，其中包含许多行星生物群系和虚构动物。由于游戏引擎可以生成大量带标签的可控图像，此类数据集为图像分类和迁移学习研究提供了便捷的试验场。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2212.06232">[2212.06232] Synthetic Image Data for Deep Learning</a></li>
<li><a href="https://en.wikipedia.org/wiki/Starfield_(video_game)">Starfield (video game)</a></li>

</ul>
</details>

**标签**: `#dataset`, `#image classification`, `#computer vision`, `#synthetic data`, `#reddit`

---