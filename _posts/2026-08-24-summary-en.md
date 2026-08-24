---
layout: default
title: "Horizon Summary: 2026-08-24 (EN)"
date: 2026-08-24
lang: en
---

> From 29 items, 16 important content pieces were selected

---

1. [EU Rules Are Killing Makers and Micro-Entrepreneurs, Article Argues](#item-1) ⭐️ 8.0/10
2. [seL4 Security Proofs Complete on AArch64](#item-2) ⭐️ 8.0/10
3. [Hacking Every Device You Own: A Journey to True Ownership](#item-3) ⭐️ 8.0/10
4. [A Clever Hack: Treat an ELF Executable as a SQLite Database](#item-4) ⭐️ 8.0/10
5. [FDA Clears PrecivityAD2 Blood Test for Alzheimer's Evaluation](#item-5) ⭐️ 8.0/10
6. [ShardFlow achieves 28 TPS on Qwen2.5-7B across cloud regions via speculative decoding](#item-6) ⭐️ 8.0/10
7. [DelveRL: An Open-Source Roguelike Built for Training Game-Playing Agents](#item-7) ⭐️ 8.0/10
8. [Xiaomi: New CPU matches Apple cores single threaded, much faster multithreaded](#item-8) ⭐️ 7.0/10
9. [Anthropic's Best AI Model Struggles as Cheaper Tools Thrive](#item-9) ⭐️ 7.0/10
10. [Linus Torvalds: AI Helped Debug, But Kept Giving Up](#item-10) ⭐️ 7.0/10
11. [Delay-corrected Bellman operator enables constrained RL under unknown stochastic delays](#item-11) ⭐️ 7.0/10
12. [Paul Graham: If I Were 17, I'd Build LLMs from Scratch](#item-12) ⭐️ 6.0/10
13. [Fable's High Cost Ends the Free Lunch in AI Model Gains](#item-13) ⭐️ 6.0/10
14. [AAAI 2027 Acknowledges Collusion Risks in Reviewer Assignments](#item-14) ⭐️ 6.0/10
15. [Citing Preprint and Follow-Up Works in Camera-Ready Papers](#item-15) ⭐️ 6.0/10
16. [Educational Open-Source Watermarking for Language Models](#item-16) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [EU Rules Are Killing Makers and Micro-Entrepreneurs, Article Argues](https://lectronz.com/u/lectronz/articles/how-europe-is-killing-makers-and-micro-entrepreneurs) ⭐️ 8.0/10

An opinion piece published on Lectronz claims European Union regulations are making it nearly impossible for makers and micro-entrepreneurs to operate across member states. The article has ignited a heated Hacker News discussion with 571 upvotes and 392 comments. The debate matters because it highlights how well-intentioned EU rules, such as packaging and CE-marking requirements, disproportionately burden small businesses and single-person operations. How the EU resolves this tension will shape whether the maker movement and cross-border micro-entrepreneurship can survive in Europe. Comments point out that EU directives are implemented differently across 20 to 24 member states, creating patchwork rules, and that the EU Commission originally wanted a single central registry that member states rejected. The Packaging and Packaging Waste Regulation (PPWR) is singled out as so unworkable that the EU has advised companies not to enforce it until a correction can be enacted.

hackernews · l-one-lone · Aug 24, 13:05 · [Discussion](https://news.ycombinator.com/item?id=49419237)

**Background**: The maker movement is a technology-based extension of DIY culture, focused on creating and tinkering with physical devices. CE marking is a mandatory conformity mark for many products sold in the European Economic Area; manufacturers are responsible for assessing and declaring compliance. Micro-entrepreneurs, often operating alone or in very small teams, face significant costs and complexity when navigating these product-safety and environmental rules across different national implementations.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Maker_culture">Maker culture - Wikipedia</a></li>
<li><a href="https://single-market-economy.ec.europa.eu/single-market/goods/ce-marking_en">CE marking - Internal Market, Industry, Entrepreneurship and SMEs</a></li>
<li><a href="https://www.sipotra.it/wp-content/uploads/2025/02/REDUCING-REGULATORY-BURDEN-TO-RESTORE-THE-EUS-COMPETITIVE-EDGE.pdf">REDUCING REGULATORY</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion is sharply divided: some blame member states for creating fragmented rules and scapegoating the EU, while others argue the EU's legislation itself is fundamentally flawed, with PPWR cited as an absurd example. One commenter contrasts China's approach of regulating choke points like logistics platforms, and another highlights that small entrepreneurs are overlooked because laws assume large corporations operate across the EU.

**Tags**: `#EU regulation`, `#makers`, `#entrepreneurship`, `#policy`, `#small business`

---

<a id="item-2"></a>
## [seL4 Security Proofs Complete on AArch64](https://proofcraft.systems/news-2026/#2026-08-21) ⭐️ 8.0/10

The seL4 microkernel's security proofs have been completed on the AArch64 (ARM64) architecture, extending its formally verified assurance case to 64-bit ARM processors. This marks a significant milestone in the ongoing effort to provide machine-checked security guarantees for critical systems. This extends seL4's proven security properties to a widely used processor architecture, enabling higher-assurance systems on ARM-based devices. It is significant for industries such as automotive, aerospace, and defense that rely on ARM platforms and require strong security guarantees. The proofs are scoped to unicore (single-core) configurations and do not cover the MCS (mixed-criticality systems) variant, as noted in the community discussion. As with earlier seL4 verification efforts, the verification assumes correctness of the compiler, assembly code, hardware, and boot code.

hackernews · snvzz · Aug 24, 11:32 · [Discussion](https://news.ycombinator.com/item?id=49418255)

**Background**: seL4 is a third-generation microkernel of L4 provenance, comprising about 12,000 lines of C code plus some assembly, which minimizes the trusted computing base. Formal verification uses rigorous mathematical proofs to demonstrate that a system meets its specification, providing strong security guarantees. AArch64, also known as ARM64, is the 64-bit version of the ARM architecture family, introduced in 2011 with the ARMv8 architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://sel4.systems/">The seL 4 Microkernel | seL 4</a></li>
<li><a href="https://trustworthy.systems/projects/seL4/">The seL 4 microkernel | TS</a></li>
<li><a href="https://en.wikipedia.org/wiki/AArch64">AArch64 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community reactions were mixed: some expressed skepticism about side-channel timing attacks potentially undermining the result, while others pointed out scope limitations such as unicore-only and non-MCS configurations. There was also discussion about which operating systems use seL4 and a critical view that a native seL4/Linux approach may be needed to genuinely improve system security.

**Tags**: `#seL4`, `#formal verification`, `#AArch64`, `#security`, `#microkernel`

---

<a id="item-3"></a>
## [Hacking Every Device You Own: A Journey to True Ownership](https://schlarp.com/posts/everything-i-own-owned/) ⭐️ 8.0/10

In a detailed blog post, an engineer describes systematically reverse-engineering firmware across their personal devices, starting with an ASUS ROG Swift PG42UQ OLED monitor, to remove unwanted overlays and gain full control over the hardware they legally own. It highlights a growing 'right to repair' and device-ownership movement in which consumers challenge manufacturer lock-in. The discussion shows both technical feasibility and new legal obstacles, such as the EU's RED directive (EN 18031-1), that require manufacturers to secure firmware against tampering. The author used open-source reverse-engineering tools such as Ghidra, binwalk for firmware extraction, and JTAG debug interfaces. The article began with patching a monitor's firmware to disable the 'pixel cleaning' pop-up, and expanded to other owned hardware, including displays and GPUs.

hackernews · schlarpc · Aug 23, 22:41 · [Discussion](https://news.ycombinator.com/item?id=49413320)

**Background**: Firmware is low-level software embedded in hardware that controls its basic functions; manufacturers often sign it and restrict access. To take 'ownership' of a device, hackers use tools like Ghidra (an NSA-developed reverse-engineering framework), binwalk (a firmware extraction tool), and JTAG (a hardware debugging interface) to inspect and modify firmware. The EU's Radio Equipment Directive and its cybersecurity standard EN 18031-1 now require internet-connected devices to have secure update mechanisms, which can conflict with user modifications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Ghidra">Ghidra - Wikipedia</a></li>
<li><a href="https://binwalk.app/">Binwalk - Firmware Analysis and Extraction Tool</a></li>
<li><a href="https://www.allaboutcircuits.com/technical-articles/jtag-connectors-and-interfaces/">JTAG Connectors and Interfaces - Technical Articles</a></li>

</ul>
</details>

**Discussion**: The community response was largely enthusiastic and supportive, with users sharing similar reverse-engineering projects, such as a new open-source Linux driver for the Silicon Motion SM750 GPU and an AI-assisted effort to document the Supernote note file format. Some commenters raised concerns about newer regulations like the EU RED directive (EN 18031-1) that mandate signed firmware, making hobbyist modification harder, while others expressed a 'do not care' attitude toward vendor pop-ups and lock-in.

**Tags**: `#firmware`, `#hacking`, `#hardware`, `#ownership`, `#reverse-engineering`

---

<a id="item-4"></a>
## [A Clever Hack: Treat an ELF Executable as a SQLite Database](https://fzakaria.com/2026/08/23/your-executable-is-a-sqlite-database) ⭐️ 8.0/10

Farid Zakaria published an article on August 23, 2026 demonstrating a Linux pattern in which an ELF executable is also a valid SQLite database file, allowing its internal contents to be queried with SQL. The approach relies on SQLite's permissive file-format detection and the ability to craft polyglot files. This idea offers a fresh perspective for reverse engineering and binary analysis, letting analysts query ELF sections and symbols with familiar SQL tools. It may inspire new tooling that treats executables as data, though it is more of a clever hack than a fundamental paradigm shift. SQLite identifies a database by a 16-byte header and fixed-size pages, while ELF files contain section headers and padding that can be aligned to embed a valid database structure. The article also builds on SQLite's virtual table mechanism, which can expose arbitrary data sources as SQL tables; a key caveat is that the running program must not overwrite the embedded database regions.

hackernews · setheron · Aug 24, 04:48 · [Discussion](https://news.ycombinator.com/item?id=49415271)

**Background**: ELF is the standard executable format on Linux, organized into headers and sections, while SQLite is an embedded relational database stored in a single ordinary file. A polyglot file is valid in two or more file formats simultaneously. Combining ELF with SQLite lets the same file run as a program and be queried as a database.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Polyglot_(computing)">Polyglot (computing) - Wikipedia</a></li>
<li><a href="https://docs.fileformat.com/database/sqlite/">Learn about SQLITE file format and APIs that can create and open...</a></li>

</ul>
</details>

**Discussion**: Hacker News commenters were largely enthusiastic, with several marveling at SQLite's virtual table capability and calling the idea mind-blowing and potentially very useful. The author noted that the idea received harsher feedback in academic circles. Some commenters countered that ELF is already a database in a broad sense, while one raised the need for the opposite direction: letting agents access remote files as a local filesystem.

**Tags**: `#SQLite`, `#ELF`, `#executables`, `#database`, `#reverse engineering`

---

<a id="item-5"></a>
## [FDA Clears PrecivityAD2 Blood Test for Alzheimer's Evaluation](https://medicine.washu.edu/news/fda-clears-blood-test-to-aid-evaluation-for-alzheimers-disease/) ⭐️ 8.0/10

The U.S. Food and Drug Administration (FDA) cleared the PrecivityAD2 blood test, which uses the p-tau217 biomarker to aid in the evaluation of Alzheimer's disease. This clearance allows the test to be marketed for clinical use. This is a significant advancement in Alzheimer's diagnostics because a blood test is far less invasive and more accessible than current methods like PET scans or lumbar punctures. It could enable earlier and more widespread screening, potentially leading to earlier intervention and better patient outcomes. The PrecivityAD2 test measures amyloid beta 42/40 ratio and percent p-tau217, combining them into an Amyloid Probability Score 2 (APS2). It is specifically intended for patients with mild cognitive impairment or dementia to help rule in or rule out Alzheimer's disease.

hackernews · dabinat · Aug 24, 06:30 · [Discussion](https://news.ycombinator.com/item?id=49415893)

**Background**: Alzheimer's disease is the most common cause of dementia, characterized by accumulation of amyloid plaques and tau tangles in the brain. Historically, a definitive diagnosis required a PET scan for amyloid or a lumbar puncture for cerebrospinal fluid biomarkers, which are expensive, invasive, and not widely available. Blood-based biomarkers like p-tau217 have emerged as a promising, less invasive alternative. The FDA clearance of PrecivityAD2 marks a step toward integrating such tests into routine clinical practice.

<details><summary>References</summary>
<ul>
<li><a href="https://www.nature.com/articles/s41591-025-03622-w">Plasma phospho-tau217 for Alzheimer’s disease diagnosis in primary and secondary care using a fully automated platform | Nature Medicine</a></li>
<li><a href="https://www.mayocliniclabs.com/test-catalog/overview/621652">C2AD2 - Overview: PrecivityAD2, Plasma - Mayo Clinic Laboratories</a></li>

</ul>
</details>

**Discussion**: Commenters expressed cautious optimism, noting the test's high sensitivity but questioning its high cost (~$1,400–$1,500) and how it fits with current cheaper alternatives. Some asked about proven interventions for those testing positive, while one commenter questioned why the FDA needs to clear an innocuous blood test.

**Tags**: `#FDA`, `#Alzheimer's`, `#blood test`, `#biomarker`, `#health tech`

---

<a id="item-6"></a>
## [ShardFlow achieves 28 TPS on Qwen2.5-7B across cloud regions via speculative decoding](https://www.reddit.com/r/MachineLearning/comments/1vw5ysj/28_tps_on_qwen257b_across_two_separate_cloud/) ⭐️ 8.0/10

ShardFlow, a distributed LLM inference framework, achieved 28.1 TPS peak and 20.31 TPS average on Qwen2.5-7B across two GCP regions (Iowa and Oregon) connected via an AWS EC2 relay with ~86ms RTT. The speedup comes from combining neural speculative decoding (K=8) with CUDA Graphs to eliminate Python launch overhead. This demonstrates that WAN latency can be effectively mitigated for distributed LLM inference by using speculative decoding to convert per-token latency into per-round latency. It opens the door to scaling LLMs across geographically distributed commodity GPUs, which could reduce costs and increase flexibility for inference deployments. The benchmark used two T4 nodes in separate GCP regions with an AWS EC2 TCP relay in Ohio, achieving ~86ms RTT. The CUDA Graphs fix captured the full 0.5B draft model forward pass as a single graph, reducing draft latency from 112ms to 25ms by cutting ~1500 kernel launches per round. The stack also includes a zero-copy Rust TCP relay and StaticCache with in-place KV rewind.

reddit · r/MachineLearning · /u/katua_bkl · Aug 23, 12:30

**Background**: Speculative decoding is an inference-time optimization where a small draft model proposes multiple candidate tokens and a larger target model verifies them in a single forward pass, speeding up generation without changing output quality. CUDA Graphs reduce GPU kernel launch overhead by grouping many kernel launches into a single graph that can be replayed with one CPU operation. NF4 is a 4-bit quantization format that reduces memory footprint while preserving model quality.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Speculative_decoding">Speculative decoding - Wikipedia</a></li>
<li><a href="https://developer.nvidia.com/blog/cuda-graphs/">Getting Started with CUDA Graphs | NVIDIA Technical Blog</a></li>
<li><a href="https://arxiv.org/abs/2604.02556">[2604.02556] Fast NF4 Dequantization Kernels for Large Language Model Inference</a></li>

</ul>
</details>

**Tags**: `#distributed inference`, `#speculative decoding`, `#LLM`, `#CUDA Graphs`, `#WAN latency`

---

<a id="item-7"></a>
## [DelveRL: An Open-Source Roguelike Built for Training Game-Playing Agents](https://www.reddit.com/r/MachineLearning/comments/1vvii1j/i_built_an_opensource_roguelike_specifically_for/) ⭐️ 8.0/10

The author released DelveRL, an open-source, human-playable roguelike environment designed specifically for reinforcement learning agents. It includes a structured API, deterministic simulation, procedural levels, partial observability, and a recurrent PPO baseline that reaches a median floor of 18 and up to floor 33 on extended runs. DelveRL addresses a common pain point: many games are hard to integrate with agent harnesses, so this environment is built from the ground up for RL research. It offers researchers and practitioners a reproducible, locally runnable benchmark with strategic depth, potentially accelerating progress in game-playing AI and partial-observability research. The game is an endless turn-based roguelike where agents must explore, manage risk and resources, fight enemies, and escape each floor by securing a key and returning to the exit. DelveRL is deterministic after reset, renderer-independent, and supports batched renderer-free environments; the open-source release includes training code, a checkpoint, bridge documentation, and raw benchmarks.

reddit · r/MachineLearning · /u/SnyderConsulting · Aug 22, 17:32

**Background**: Reinforcement learning (RL) agents learn by interacting with an environment and receiving rewards, but many existing games are not designed with agent APIs or reproducibility in mind. Partial observability means the agent only sees part of the environment, which makes decision-making harder and more realistic. PPO (Proximal Policy Optimization) is a popular RL algorithm from OpenAI that is simpler to implement and tune while performing comparably to or better than state-of-the-art approaches; DelveRL ships a recurrent PPO baseline to help users get started.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/SnyderConsulting/DelveRL">GitHub - SnyderConsulting/DelveRL: A human-playable turn ...</a></li>
<li><a href="https://openai.com/index/openai-baselines-ppo/">Proximal Policy Optimization | OpenAI</a></li>
<li><a href="https://kblip.com/products/delverl-open-source-roguelike-for-training-game-playing-T3Sm12A">DelveRL: Open-source roguelike for training game-playing agents</a></li>

</ul>
</details>

**Tags**: `#reinforcement learning`, `#game AI`, `#open-source`, `#roguelike`, `#PPO`

---

<a id="item-8"></a>
## [Xiaomi: New CPU matches Apple cores single threaded, much faster multithreaded](https://twitter.com/lemire/status/2091894299289874926) ⭐️ 7.0/10

Xiaomi's new CPU reportedly matches Apple cores in single-threaded and exceeds them in multithreaded performance, though power efficiency in real devices remains a key question.

hackernews · tosh · Aug 24, 15:08 · [Discussion](https://news.ycombinator.com/item?id=49420873)

**Tags**: `#CPUs`, `#Xiaomi`, `#Apple Silicon`, `#mobile chips`, `#semiconductors`

---

<a id="item-9"></a>
## [Anthropic's Best AI Model Struggles as Cheaper Tools Thrive](https://www.ft.com/content/5ee49718-c258-4f01-aa32-7e5b76ae5245) ⭐️ 7.0/10

A Financial Times report says Anthropic's latest flagship model is struggling to attract users, while cheaper AI tools gain ground. The article has sparked debate about Anthropic's pricing strategy, output quality, and data privacy. If Anthropic cannot convert its technical reputation into broad adoption, it could cede consumer and developer mindshare to cheaper competitors, weakening its position in the fast-moving LLM market. Pricing and product decisions for Claude will therefore be closely watched by AI users and investors. The FT report focuses on Anthropic's flagship model and subscription strategy, though the available excerpt provides no specific adoption figures. Community commenters raise concerns about per-token billing, the $200 tier, and the risk of exposing proprietary code or business data when using Claude.

hackernews · naves · Aug 23, 18:16 · [Discussion](https://news.ycombinator.com/item?id=49411102)

**Background**: Anthropic is an AI safety and research company founded in 2021 by former OpenAI leaders, and its flagship product is Claude, a family of large language models released as a chatbot in March 2023. Claude is trained using a constitution-based technique intended to improve ethical and legal compliance, and it competes with other major LLM providers in both consumer and enterprise markets.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Anthropic">Anthropic - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Claude_(AI)">Claude (AI) - Wikipedia</a></li>
<li><a href="https://www.anthropic.com/">Home \ Anthropic</a></li>

</ul>
</details>

**Discussion**: Commenters are split: some argue Anthropic's confusing monetization experiments, such as temporary access windows and per-token fees, have alienated users, while others say Claude's prose style has become grating enough to drive them away. There is also skepticism about data privacy when uploading sensitive organizational information. Additional commenters suspect that gating a highly regarded model behind a $200 plan and shipping a weaker successor may be a deliberate strategy to push higher token spend.

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#LLM`, `#Market Analysis`

---

<a id="item-10"></a>
## [Linus Torvalds: AI Helped Debug, But Kept Giving Up](https://simonwillison.net/2026/Aug/22/linus-torvalds/) ⭐️ 7.0/10

Linus Torvalds, in a commit message for the Linux kernel's drm/xe driver, described a 'debug session from hell' where an AI assistant performed much of the grunt work but repeatedly declared the problem impossible and unsolvable. He praised the AI for faithfully adding and analyzing debug code when pushed, and even let it write the commit message. This is significant because Torvalds is known for his hands-on, skeptical approach to kernel development, so his public acknowledgment shows AI tools can genuinely assist in hard low-level debugging. At the same time, his remark highlights current AI limitations—such as giving up too easily—and will likely spark discussion about AI-assisted development in systems programming. The quote comes from Linux kernel commit 818bebeb63dd6bf5f4e07e145f6cdbace520a34c, titled 'drm/xe: Don't hand out the flat CCS storage as usable VRAM.' The drm/xe driver is the Linux kernel graphics driver for Intel GPUs, and this fix addresses how a particular GPU storage region is exposed.

rss · Simon Willison · Aug 22, 21:04

**Background**: The Linux kernel uses the Direct Rendering Manager (DRM) subsystem for GPU drivers, and drm/xe is the newer DRM driver for Intel graphics, supporting rendering, display, compute, and media on some GFX cards. In this context, 'flat CCS storage' refers to a GPU memory region tied to Intel compression/metadata handling, which the driver previously misreported as usable VRAM.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Direct_Rendering_Manager">Direct Rendering Manager - Wikipedia</a></li>
<li><a href="https://docs.kernel.org/gpu/xe/index.html">drm/xe Intel GFX Driver — The Linux Kernel documentation</a></li>

</ul>
</details>

**Tags**: `#linus-torvalds`, `#AI-assisted debugging`, `#linux kernel`, `#developer tools`, `#artificial intelligence`

---

<a id="item-11"></a>
## [Delay-corrected Bellman operator enables constrained RL under unknown stochastic delays](https://www.reddit.com/r/MachineLearning/comments/1vx11hz/delaycorrected_bellman_operator_causal/) ⭐️ 7.0/10

Researchers introduce a delay-corrected Bellman operator that learns an adaptive effective discount from the consequence-delay distribution and prove contraction under unknown stochastic delay. They also propose an Interventional Consequence Net (ICN), pretrained on structural-causal-model labels, to attribute causal responsibility per action rather than by temporal proximity. Standard constrained RL assumes immediate, attributable consequences, which fails under delayed stochastic violations. This work could improve credit assignment in real-world safety-critical RL, but is currently limited by its need for SCM labels and lack of empirical validation. The ICN requires access to the environment's structural causal model to generate pretraining labels and is not learned end-to-end from observational or interventional data. No experimental results are provided; the post is a preliminary research proposal.

reddit · r/MachineLearning · /u/No_Cauliflower7923 · Aug 24, 12:11

**Background**: In reinforcement learning, the Bellman operator rewrites the Bellman equations as operators on value functions, which is useful for proving convergence of dynamic programming algorithms like value iteration to a unique fixed point. Structural causal models (SCMs) describe causal mechanisms among variables, and causal RL combines such causal invariances with RL. Constrained RL adds safety constraints to the optimization objective. This proposal connects these areas to handle delayed stochastic consequences.

<details><summary>References</summary>
<ul>
<li><a href="https://pypi.org/project/ccpl-rl/">Causal Consequence-Penalized Learning for delayed constrained...</a></li>
<li><a href="https://web.stanford.edu/class/cme241/lecture_slides/BellmanOperators.pdf">Understanding (Exact) Dynamic Programming through Bellman ...</a></li>
<li><a href="https://crl.causalai.net/">Causal Reinforcement Learning</a></li>

</ul>
</details>

**Tags**: `#reinforcement learning`, `#constrained RL`, `#causality`, `#Bellman operator`, `#stochastic delay`

---

<a id="item-12"></a>
## [Paul Graham: If I Were 17, I'd Build LLMs from Scratch](https://twitter.com/paulg/status/2091544343589060625) ⭐️ 6.0/10

Paul Graham tweeted that if he were 17, he would learn to build large language models (LLMs) from scratch. The post was submitted to Hacker News, where it drew 375 points and 493 comments debating the advice. The advice pushes back against the trend of treating LLMs as black boxes and suggests that young people should understand the underlying mechanics. The ensuing discussion exposes a gap between the hype around LLM engineers and the real scarcity of positions that require such skills. Commenters point out that only a tiny minority of companies do real LLM training or optimization, and that learning the fundamentals is more about building intuition than landing a job. One commenter recommends Andrej Karpathy's videos and Sebastian Raschka's books as accessible resources.

hackernews · bilsbie · Aug 23, 20:38 · [Discussion](https://news.ycombinator.com/item?id=49412396)

**Background**: Large language models are neural networks trained on massive text corpora to predict and generate text. Building one 'from scratch' involves designing the architecture, writing the training loop, and pre-training the model, which usually requires substantial computational resources. Paul Graham is a prominent programmer, essayist, and startup investor, and his opinion posts often spark debate. Hacker News is a tech-focused social news site where such posts frequently lead to long discussions.

**Discussion**: The discussion is sharply divided. Some agree with the spirit of the advice, arguing that deep knowledge builds intuition and helps young people judge when 'just LLM it' is inappropriate. Others criticize it as survivorship bias, noting that most companies do not train models and that the advice overlooks the prohibitive cost of real LLM training.

**Tags**: `#LLMs`, `#Education`, `#AI`, `#Opinion`, `#Hacker News`

---

<a id="item-13"></a>
## [Fable's High Cost Ends the Free Lunch in AI Model Gains](https://simonwillison.net/2026/Aug/23/drew-breunig/) ⭐️ 6.0/10

Drew Breunig argues that Anthropic's Fable model, despite being incredible, is so expensive that it marks the end of the era where new models arrived at the same or lower price and automatically solved most coding problems. His team now deliberately decides which coding tasks go to Fable versus cheaper models like Opus, 5.6, K3, and GLM. This signals a shift in AI economics: frontier model performance gains now come at a premium, so teams must weigh cost against incremental quality. It will push developers to build more sophisticated routing and harness strategies instead of waiting for the next model to paper over inefficiencies. Breunig's post is titled 'Fable & The End of the Free Lunch,' referencing the end of Moore's-law-like improvements. Fable is Claude Fable 5, Anthropic's highest-scoring model on Cognition's FrontierBench coding eval, but Opus and other models were 'good enough' for most of his team's code.

rss · Simon Willison · Aug 23, 19:55

**Background**: Historically, each new generation of large language models arrived at a similar or lower price while delivering better performance, so it felt wasteful to optimize prompts or coding harnesses. Fable breaks that pattern: it offers a significant capability jump for long-horizon coding, but at a much higher cost. Meanwhile, competitive models like Moonshot AI's Kimi K3 (a 2.8T-parameter open-weight model) and Zhipu's GLM family provide lower-cost alternatives that are adequate for many tasks. This forces teams to treat model choice as an ongoing engineering decision rather than a one-time upgrade.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://claude.com/blog/claude-models-explained-choosing-the-best-model-for-your-use-case">Claude models explained: choosing the best model for your use ...</a></li>
<li><a href="https://www.kimi.ai/ai-models/kimi-k3">Kimi K3: 2.8T Open Model for Coding & Knowledge Work</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLM`, `#Model Economics`, `#Anthropic`, `#Claude`

---

<a id="item-14"></a>
## [AAAI 2027 Acknowledges Collusion Risks in Reviewer Assignments](https://www.reddit.com/r/MachineLearning/comments/1vwujcy/aaai_2027_reviewer_bidding_and_assignment/) ⭐️ 6.0/10

AAAI 2027 organizers sent an email acknowledging collusion in the review process, specifically pointing out 2-cycle reviewer-exchange rings. A Reddit user highlighted that because most submissions come from a single country, the assignment algorithm may naturally create such cycles among that country's authors. A top-tier conference acknowledging collusion validates long-held community suspicions and may push venues like AAAI, NeurIPS, ICLR, and ICML to strengthen assignment safeguards. It also raises fairness concerns when one country dominates submissions, since alleged colluders may disproportionately come from that country. A 2-cycle collusion ring means the author of Paper A reviews Paper B while the author of Paper B reviews Paper A, enabling mutually favorable scores. The original post also complains that many accepted papers at top conferences lack released code, forcing researchers to reimplement results — a separate reproducibility issue.

reddit · r/MachineLearning · /u/Fragrant_Fan_6751 · Aug 24, 06:11

**Background**: In academic peer review, reviewers typically bid on papers they feel qualified to assess, and conference systems use assignment algorithms to match papers with reviewers while avoiding conflicts of interest. Collusion rings are groups of authors who coordinate reviews to inflate acceptance chances; the simplest form is a 2-cycle, and more complex rings form longer reviewer-paper chains. Research such as the Cycle-Free Reviewing paper studies how to make assignments robust against such manipulation, and AAAI-26 already introduced a more manipulation-resistant assignment algorithm. Conference management platforms like CMT provide standard bidding workflows with values such as Eager, Willing, and In a Pinch.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2608.08486">Detecting Collusion in Peer Review: Drawing Inspiration from ...</a></li>
<li><a href="https://arxiv.org/abs/2112.08444v1">[2112.08444v1] Combating Collusion Rings is Hard but Possible</a></li>
<li><a href="https://blog.aaai.org/improving-robustness-in-paper-reviewer-assignment-for-aaai-2026/">Improving Robustness in Paper–Reviewer Assignment for AAAI ...</a></li>

</ul>
</details>

**Tags**: `#AAAI`, `#peer review`, `#collusion`, `#academic integrity`

---

<a id="item-15"></a>
## [Citing Preprint and Follow-Up Works in Camera-Ready Papers](https://www.reddit.com/r/MachineLearning/comments/1vwg5br/how_to_citetalk_about_preprintsubsequent_works/) ⭐️ 6.0/10

A researcher asks how to handle citations of their own preprint and subsequent works that built on it when preparing the camera-ready version of an accepted conference paper, specifically regarding the Related Work section. The question highlights a common dilemma about self-citation, novelty, and giving credit. This issue matters to many researchers in fast-moving fields where preprints precede conference publications. Proper citation practices affect academic integrity, fairness, and how novelty is perceived. The researcher worries about whether citing their own preprint in the camera-ready version is appropriate and allowed. They also want to avoid undermining the novelty of their original work while still crediting subsequent works that reused or extended their methodology.

reddit · r/MachineLearning · /u/Vulcapulae · Aug 23, 19:15

**Background**: In many fields, especially machine learning, researchers post preprints on platforms like arXiv before conference acceptance. Conference papers usually require a camera-ready version after peer review, and authors are expected to update the paper to reflect the latest state of the art. This often includes citing works that appeared after the preprint was posted. It is generally acceptable to cite their own preprint as the original version and then discuss subsequent works in that context.

**Tags**: `#academic publishing`, `#citations`, `#preprint`, `#conference paper`, `#research ethics`

---

<a id="item-16"></a>
## [Educational Open-Source Watermarking for Language Models](https://www.reddit.com/r/MachineLearning/comments/1vw18ys/implementing_watermarking_for_language_models_p/) ⭐️ 6.0/10

A developer released a minimal, educational GitHub implementation of SynthID-Text-style statistical watermarking for language models, inspired by Anthropic's recent announcement about watermarking AI text. The post clarifies that such watermarks are subtle statistical patterns in token selection, not visible messages. With leading AI labs like Google and Anthropic deploying text watermarks, accessible implementations help developers and researchers understand how the technique works and how to build or evaluate detection methods. This project lowers the barrier to experimenting with LLM watermarking. The implementation is deliberately simplified and is not an exact reproduction of SynthID-Text; it keeps the core idea of biasing token sampling to embed a detectable statistical signal. The code is available at github.com/Saad1926Q/llm-watermark and targets an educational audience.

reddit · r/MachineLearning · /u/Saad_ahmed04 · Aug 23, 08:09

**Background**: Large language models generate text one token at a time by sampling from a probability distribution over possible next tokens. Statistical watermarking replaces the random seed with a secret watermark key and biases token selection in a way that can later be detected by someone who knows the key. SynthID-Text, for example, works as a logits processor applied after Top-K and Top-P sampling. This lets providers identify AI-generated text without degrading output quality.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/synthid/">SynthID — Google DeepMind</a></li>
<li><a href="https://ai.google.dev/responsible/docs/safeguards/synthid">SynthID : Tools for watermarking and detecting LLM-generated Text</a></li>
<li><a href="https://www.let-all.com/blog/2025/11/26/watermarking-language-models/">Watermarking language models – Learning Theory Alliance</a></li>

</ul>
</details>

**Tags**: `#watermarking`, `#LLM`, `#SynthID`, `#AI safety`, `#GitHub`

---