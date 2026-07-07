---
layout: default
title: "Horizon Summary: 2026-07-07 (EN)"
date: 2026-07-07
lang: en
---

> From 24 items, 17 important content pieces were selected

---

1. [Microsoft lays off idTech engine team at id Software](#item-1) ⭐️ 9.0/10
2. [TRACE: Open-Source Hierarchical Memory for LLM Agents Achieves 82.5%](#item-2) ⭐️ 9.0/10
3. [EU Parliament Advances Chat Control Regulation](#item-3) ⭐️ 8.0/10
4. [US vendors dominate European web hosting market](#item-4) ⭐️ 8.0/10
5. [Tencent Releases Hy3 MoE Model](#item-5) ⭐️ 8.0/10
6. [PhD Thesis Serves as Textbook on Differentiable Ray Tracing for Radio](#item-6) ⭐️ 8.0/10
7. [MIRA: 5B-Parameter World Model for Rocket League](#item-7) ⭐️ 8.0/10
8. [Mozilla CTO Hosts AMA on Open Source AI Report](#item-8) ⭐️ 8.0/10
9. [Credit System Proposed to Improve ML Conference Reviewing](#item-9) ⭐️ 8.0/10
10. [LingBot-Vision: Masked Boundary Modeling Beats DINOv3 on Depth](#item-10) ⭐️ 8.0/10
11. [StreetComplete: Gamifying OpenStreetMap Edits for Beginners](#item-11) ⭐️ 7.0/10
12. [sqlite-utils 4.0rc3: Compound Foreign Keys & Case-Insensitive Matching](#item-12) ⭐️ 7.0/10
13. [TorchJD Library Enables Multi-Loss Training in PyTorch](#item-13) ⭐️ 7.0/10
14. [CPU TTS benchmark with UTMOS compares Kokoro, Supertonic, Inflect-Nano, Pocket TTS](#item-14) ⭐️ 7.0/10
15. [98% Browser Support Isn't Enough, Says Article](#item-15) ⭐️ 6.0/10
16. [ML Job Requirements Become Unrealistic, Non-FAANG Firms Seek Multiple Deep Expertise](#item-16) ⭐️ 6.0/10
17. [LingBot-Depth 2.0: Sensor-validity masking for depth estimation](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Microsoft lays off idTech engine team at id Software](https://gamefromscratch.com/microsoft-fire-idtech-team-at-id-software/) ⭐️ 9.0/10

Microsoft has reportedly laid off the entire idTech engine team at id Software, potentially indicating a strategic shift away from internal engine development toward third-party solutions like Unreal Engine 5. This move could reduce engine diversity in the industry and further consolidate Epic Games' dominance with Unreal Engine 5, while also impacting id Software's future titles and the performance optimization idTech was known for. The layoffs are part of a broader restructuring at Microsoft's gaming division, though id Software has not officially confirmed the reports. idTech is a proprietary engine series that powered iconic games like Doom, Quake, and Wolfenstein.

hackernews · bauc · Jul 7, 15:33 · [Discussion](https://news.ycombinator.com/item?id=48819244)

**Background**: id Software developed the idTech engine series, which has been used in many first-person shooters. Historically, idTech engines up to id Tech 4 were released as open source, but later versions remain proprietary. id Tech 7, used in Doom Eternal, was noted for its high performance on older hardware. Switching to a third-party engine like Unreal Engine 5 would mark a significant departure from id Software's tradition of in-house engine development.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Id_Tech">id Tech - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Id_Tech_7">id Tech 7 - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Community reactions are mixed: some see the layoffs as cost-cutting that will hurt innovation, while others question the evidence behind the report. A few commenters express concern about a growing Unreal Engine monopoly, and some suggest Microsoft should open-source idTech instead.

**Tags**: `#game engines`, `#Microsoft`, `#id Software`, `#layoffs`, `#game development`

---

<a id="item-2"></a>
## [TRACE: Open-Source Hierarchical Memory for LLM Agents Achieves 82.5%](https://www.reddit.com/r/MachineLearning/comments/1uoz5jo/trace_opensource_hierarchical_memory_for_llm/) ⭐️ 9.0/10

TRACE is an open-source hierarchical memory system that organizes LLM agent conversation history into a topic tree, achieving 82.5% F1 on MemoryAgentBench's EventQA task using the gpt-oss-20B model, significantly outperforming Mem0 (37.5%) and MemGPT (26.2%). This demonstrates that hierarchical memory structures can dramatically improve retrieval accuracy for LLM agents compared to flat RAG approaches, and the open-source release enables wider adoption and further research. The comparison is not fully controlled because TRACE used gpt-oss-20B locally while Mem0 and MemGPT results are reported using GPT-4o-mini; the author attempted to run Mem0 on gpt-oss but faced JSON parsing issues, which are a known limitation of Mem0 with open-weight models.

reddit · r/MachineLearning · /u/PsychologicalDot7749 · Jul 6, 14:35

**Background**: LLM agents often need long-term memory to maintain context across conversations. Traditional memory systems use flat retrieval-augmented generation (RAG), which treats all past interactions as independent chunks. TRACE introduces a hierarchical topic tree that organizes conversation history into branches with summaries, similar to a document outline, enabling more precise retrieval. MemoryAgentBench is a benchmark designed to evaluate memory capabilities in LLM agents through incremental multi-turn interactions.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/HUST-AI-HYZ/MemoryAgentBench">GitHub - HUST-AI-HYZ/MemoryAgentBench: Open source code for ICLR 2026 Paper: Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions · GitHub</a></li>
<li><a href="https://arxiv.org/abs/2504.19413">[2504.19413] Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory</a></li>

</ul>
</details>

**Tags**: `#LLM agents`, `#memory systems`, `#open-source`, `#benchmark`, `#hierarchical memory`

---

<a id="item-3"></a>
## [EU Parliament Advances Chat Control Regulation](https://www.heise.de/en/news/Showdown-in-Strasbourg-The-unexpected-return-of-Chat-Control-1-0-11356680.html) ⭐️ 8.0/10

The European Parliament voted to advance the Chat Control regulation (CSAR) in its first reading, using procedural tactics that require an absolute majority for amendments, threatening end-to-end encryption. This regulation, if enacted, would mandate mass surveillance of private messages, undermining digital privacy and encryption for all EU citizens and potentially setting a global precedent for surveillance laws. The regulation targets detection of child sexual abuse material (CSAM) but critics warn it could break end-to-end encryption by requiring client-side scanning or backdoors.

hackernews · miroljub · Jul 7, 15:16 · [Discussion](https://news.ycombinator.com/item?id=48819008)

**Background**: Chat Control, formally the Child Sexual Abuse Regulation (CSAR), was proposed by the European Commission in May 2022 to combat online child sexual abuse. It has been highly controversial due to its potential to mandate scanning of private communications, effectively weakening end-to-end encryption. The regulation has previously expired but is being revived under procedural changes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Chat_Control">Chat Control - Wikipedia</a></li>
<li><a href="https://edri.org/our-work/chat-control-what-is-actually-going-on/">Chat Control: What is actually going on? - European Digital ...</a></li>

</ul>
</details>

**Discussion**: Commenters expressed strong opposition, noting procedural tactics that favor proponents and the low likelihood of blocking the law. They criticized the democratic process and warned of global ripple effects, as non-EU services may be forced to comply or block EU users.

**Tags**: `#privacy`, `#EU regulation`, `#encryption`, `#surveillance`, `#civil liberties`

---

<a id="item-4"></a>
## [US vendors dominate European web hosting market](https://ciphercue.com/blog/european-web-hosting-vendor-share-2026) ⭐️ 8.0/10

An analysis reveals that the majority of European company websites are hosted by US vendors like AWS, Azure, and Cloudflare, sparking debate about European digital sovereignty. This dependency raises concerns about data privacy, vendor lock-in, and the ability of European cloud providers to compete, affecting both businesses and policymakers pushing for digital autonomy. Community comments highlight that many US vendors operate EU-based data centers under EU law, and alternative studies focusing on API subdomains show European companies often prefer OVH and Hetzner over US hyperscalers.

hackernews · adulion · Jul 7, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48816612)

**Background**: Web hosting is a service that makes websites accessible on the internet, often provided by large cloud providers like Amazon Web Services (AWS) and Microsoft Azure. Many European businesses rely on these US-based vendors for infrastructure, but concerns over data sovereignty and compliance with GDPR have led to growing interest in European alternatives such as Hetzner and OVH.

**Discussion**: Commenters offer nuanced views: some note that US vendors have EU entities and data centers, reducing legal concerns, while others point to studies showing European providers like OVH and Hetzner are more common for API hosting. A solo founder laments the lack of European alternatives for critical services like Stripe.

**Tags**: `#web hosting`, `#US vendors`, `#Europe`, `#cloud infrastructure`, `#vendor lock-in`

---

<a id="item-5"></a>
## [Tencent Releases Hy3 MoE Model](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 8.0/10

Tencent released Hy3, a 295B-parameter Mixture-of-Experts model with 21B active parameters, under the Apache 2.0 license. It is available on Hugging Face and for free on OpenRouter until July 21st, outperforming similar-size models and rivaling those with 2-5x parameters. Hy3 demonstrates that efficient MoE architectures can compete with much larger dense models, potentially lowering computational costs for high-performance AI. Its open-source release and free trial on OpenRouter make cutting-edge AI more accessible to researchers and developers. The full model is 598GB on Hugging Face, with an FP8 quantized version at 300GB, and supports a 256K token context length. It was developed by the Tencent Hy Team after a preview in late April, scaled up post-training using higher-quality data from over 50 products.

rss · Simon Willison · Jul 6, 23:57

**Background**: Mixture-of-Experts (MoE) is an architecture that activates only a subset of parameters per input, enabling large total parameter counts while keeping computational costs low. FP8 quantization reduces model size and speeds up inference by using 8-bit floating-point numbers instead of 16- or 32-bit formats, making large models more deployable.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained</a></li>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>

</ul>
</details>

**Tags**: `#AI`, `#open-source`, `#MoE`, `#Tencent`, `#large language model`

---

<a id="item-6"></a>
## [PhD Thesis Serves as Textbook on Differentiable Ray Tracing for Radio](https://www.reddit.com/r/MachineLearning/comments/1upvkp5/phd_thesis_on_differentiable_ray_tracing_for/) ⭐️ 8.0/10

A PhD thesis by u/jeertmans presents differentiable ray tracing for radio propagation modeling as an accessible textbook, integrating automatic differentiation via JAX to compute exact gradients through physical environments. This work bridges physics-based simulation and machine learning for inverse problems in wireless communications, enabling gradient-based optimization and ML training for next-generation radio design. The thesis is split into three parts: physics fundamentals, algorithmic core including GPU-accelerated path tracing and discontinuity smoothing, and applications like channel modeling and material calibration. It builds on JAX packages like jaxtyping, equinox, and optimistix, and the open-source library DiffeRT2d.

reddit · r/MachineLearning · /u/jeertmans · Jul 7, 13:45

**Background**: Differentiable ray tracing extends traditional ray tracing by enabling gradient computation through the simulation, which is essential for optimization and machine learning. Radio propagation modeling predicts how radio waves travel, crucial for wireless network planning. Automatic differentiation frameworks like JAX allow these gradients to be computed efficiently.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/jeertmans/DiffeRT2d">GitHub - jeertmans/DiffeRT2d: 2D Toolbox for Differentiable ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Radio_propagation">Radio propagation - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The author invites questions about differentiable simulation and ray tracing in JAX, and gives a shoutout to Patrick Kidger whose thesis inspired this work and whose JAX libraries were heavily used.

**Tags**: `#differentiable programming`, `#ray tracing`, `#radio propagation`, `#automatic differentiation`, `#wireless communications`

---

<a id="item-7"></a>
## [MIRA: 5B-Parameter World Model for Rocket League](https://www.reddit.com/r/MachineLearning/comments/1upofuw/mira_multiplayer_interactive_world_models_trained/) ⭐️ 8.0/10

Researchers from General Intuition, Kyutai, and Epic Games released MIRA, a 5-billion-parameter interactive world model trained on 10,000 hours of synthetic Rocket League gameplay, capable of real-time multiplayer simulation at 20 frames per second for four players on a single NVIDIA B200 GPU. MIRA represents a significant step forward in large-scale world models for interactive environments, enabling realistic multiplayer game simulation that could advance game AI, reinforcement learning, and virtual world research. The model runs at 20 fps for 4 players on a single B200 GPU, and the team also released a playable online demo, a technical report, and a 1,000-hour dataset of 4-player gameplay.

reddit · r/MachineLearning · /u/MasterScrat · Jul 7, 07:59

**Background**: A world model in AI is a machine learning system that learns an internal representation of an environment and predicts how it changes in response to actions, enabling agents to plan and reason without constant real-world interaction. World models are used in robotics, autonomous driving, and interactive video generation. The B200 is NVIDIA's latest Blackwell GPU, offering significant performance improvements for AI inference and training.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/World_model_(artificial_intelligence)">World model (artificial intelligence)</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/dgx-b200/">DGX B200: The Foundation for Your AI Factory | NVIDIA</a></li>

</ul>
</details>

**Tags**: `#world model`, `#game AI`, `#reinforcement learning`, `#interactive simulation`, `#large-scale model`

---

<a id="item-8"></a>
## [Mozilla CTO Hosts AMA on Open Source AI Report](https://www.reddit.com/r/MachineLearning/comments/1upxdvc/raffi_krikorian_cto_mozilla_ama_on_the_state_of/) ⭐️ 8.0/10

Mozilla CTO Raffi Krikorian is hosting an AMA on July 14 to discuss the inaugural State of Open Source AI report, which examines the real-world production use of open source AI, including hidden costs, enterprise adoption, the impact of Chinese models, developer trust, and the agentic harness layer. This AMA provides a rare opportunity to get direct insights from a major tech organization's CTO on the often-overlooked realities of deploying open source AI, which affects developers, enterprises, and the broader AI ecosystem. The discussion covers critical topics like the true cost of 'free' models and the shifting power dynamics driven by Chinese open source models. The report is based on a survey of over 950 developers, and the AMA will delve into topics such as the hidden infrastructure costs of open models, the gap between enterprise marketing and real adoption, the influence of Chinese model releases, and the 'agentic harness' as the new competitive layer.

reddit · r/MachineLearning · /u/raffikrikorian · Jul 7, 14:51

**Background**: Open source AI models (like Llama or Mistral) are released with permissive licenses, but their deployment in production often requires significant investment in infrastructure, tooling, and monitoring. The 'agentic harness' refers to the orchestration layer that enables AI models to function as autonomous agents, handling tasks like planning, tool use, and memory, which has become a critical battleground for AI platforms.

<details><summary>References</summary>
<ul>
<li><a href="https://www.langchain.com/blog/the-anatomy-of-an-agent-harness">The Anatomy of an Agent Harness</a></li>
<li><a href="https://medium.com/@balajibal/agentic-harnesses-the-new-infrastructure-layer-for-ai-systems-3939c6fac1a6">Agentic Harnesses: The New Infrastructure Layer for AI Systems? | by balaji bal | Medium</a></li>
<li><a href="https://platform.uno/blog/agentic-harness-demystified/">AI Agentic Harness Demystified</a></li>

</ul>
</details>

**Tags**: `#open source AI`, `#Mozilla`, `#enterprise AI`, `#AI industry`, `#AMA`

---

<a id="item-9"></a>
## [Credit System Proposed to Improve ML Conference Reviewing](https://www.reddit.com/r/MachineLearning/comments/1upjftu/icml_position_track_want_better_ml_reviews_stop/) ⭐️ 8.0/10

A position paper at ICML 2026 proposes a credit system where reviewers earn and spend points to incentivize high-quality peer review, replacing current ineffectual guidelines and desk rejections. This proposal addresses a long-standing problem in ML conferences where reviewer engagement is low and good behavior goes unrewarded. If adopted, it could fundamentally reshape the review culture and improve the quality of feedback for authors. Reviewers would earn +1 point for a review, +3 for outstanding reviews, and spend points on perks like free registration or requesting additional reviewers. The system also allows refundable submission fees to discourage low-quality submissions.

reddit · r/MachineLearning · /u/choHZ · Jul 7, 03:32

**Background**: ICML is a top-tier machine learning conference. The Position Paper Track at ICML encourages papers that stimulate discussion on timely topics. Current review mechanisms rely on reviewer guidelines and desk rejections, but lack accountability for reviewers' effort and quality. The proposed credit system aims to create a verifiable record of contributions.

<details><summary>References</summary>
<ul>
<li><a href="https://icml.cc/Conferences/2026/CallForPositionPapers">ICML 2026 Call For Position Papers</a></li>
<li><a href="https://openreview.net/forum?id=6IiZXiqP3Q">Position: Want Better ML Reviews? Stop Asking Nicely and Start Incentivizing with a Credit System | OpenReview</a></li>
<li><a href="https://openreview.net/group?id=ICML.cc/2026/Position_Paper_Track">ICML 2026 Position Paper Track | OpenReview</a></li>

</ul>
</details>

**Tags**: `#ML conferences`, `#peer review`, `#incentives`, `#community building`, `#ICML`

---

<a id="item-10"></a>
## [LingBot-Vision: Masked Boundary Modeling Beats DINOv3 on Depth](https://www.reddit.com/r/MachineLearning/comments/1up4cjh/lingbotvision_masked_boundary_modeling_for/) ⭐️ 8.0/10

LingBot-Vision introduces masked boundary modeling for self-supervised pretraining, where the teacher network predicts dense boundary fields and forces the student to reconstruct boundary-bearing masked tokens. It achieves 0.296 RMSE on NYUv2 linear-probe depth estimation, outperforming DINOv3-7B's 0.309, using only 161M training images. This method sets a new state-of-the-art on NYUv2 depth estimation with significantly fewer training samples than DINOv3, suggesting more efficient learning of dense visual representations. It could improve performance on dense prediction tasks like depth estimation and segmentation while reducing data requirements. The boundary fields are modeled as per-pixel categorical distributions to prevent representation collapse, and the decoded segments undergo an a-contrario validation test before being used as supervision. While excelling on NYUv2 depth, LingBot-Vision trails DINOv3 on ImageNet classification and ADE20K segmentation.

reddit · r/MachineLearning · /u/StillThese3747 · Jul 6, 17:37

**Background**: Self-supervised learning (SSL) trains visual representations without manual annotations. Masked image modeling (MIM) is a popular SSL approach that masks image patches and tasks the model with reconstructing the missing content. LingBot-Vision extends MIM by focusing on boundary-heavy regions, which are harder to infer from surrounding context, forcing the model to learn spatial structure.

<details><summary>References</summary>
<ul>
<li><a href="https://x.com/ModelScope2022/status/2074381060608074198">LingBot-Vision is now on ModelScope: a boundary-first vision ...</a></li>
<li><a href="https://www.sciencedirect.com/science/article/pii/S0010482523009915">Masked image modeling-based boundary reconstruction for 3D ...</a></li>

</ul>
</details>

**Discussion**: Reddit commenters praised the strong NYUv2 results and clever design choices but expressed caution, noting that the 0.013 RMSE gap may be within probe hyperparameter sensitivity and that ablations against hard-masking baselines are missing. Some called for independent verification of the numbers given past evaluation concerns.

**Tags**: `#Self-Supervised Learning`, `#Vision Transformer`, `#Masked Image Modeling`, `#Depth Estimation`, `#Computer Vision`

---

<a id="item-11"></a>
## [StreetComplete: Gamifying OpenStreetMap Edits for Beginners](https://streetcomplete.app/) ⭐️ 7.0/10

StreetComplete is an Android app that transforms OpenStreetMap contributions into small, interactive quests, allowing users to easily add missing data like opening hours or crosswalks without prior OSM knowledge. By lowering the barrier to entry, StreetComplete significantly broadens the contributor base for OpenStreetMap, improving map completeness and accuracy for everyone, including Google who may use OSM data to enhance their own maps. The app prompts users with specific questions about nearby places and objects, such as 'What are the opening hours here?' or 'Is this still here?', and automatically sends the answers to OSM.

hackernews · kls0e · Jul 7, 12:38 · [Discussion](https://news.ycombinator.com/item?id=48816883)

**Background**: OpenStreetMap (OSM) is a free, editable map of the world built by volunteers, but detailed editing traditionally required technical knowledge. StreetComplete gamifies the process by breaking data collection into simple quests, making it easy for non-experts to contribute. The app is free and open-source, available only on Android.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/StreetComplete">StreetComplete</a></li>
<li><a href="https://grokipedia.com/page/streetcomplete">StreetComplete</a></li>

</ul>
</details>

**Discussion**: The community generally praises StreetComplete for its beginner-friendly UI and fun approach, but some users worry about duplicate data entry and feel limited to labeling rather than adding new roads. There is also concern about Google using OSM data without reciprocating, sparking debate on licensing.

**Tags**: `#openstreetmap`, `#crowdsourcing`, `#mapping`, `#open-source`, `#gamification`

---

<a id="item-12"></a>
## [sqlite-utils 4.0rc3: Compound Foreign Keys & Case-Insensitive Matching](https://simonwillison.net/2026/Jul/6/sqlite-utils/#atom-everything) ⭐️ 7.0/10

sqlite-utils 4.0rc3 introduces support for introspecting and creating compound foreign keys, and now follows SQLite's convention for case-insensitive column name matching. This release candidate also includes various fixes and improvements, with a growing changelog. These enhancements address long-standing user requests and align sqlite-utils more closely with SQLite's native behavior, making it more reliable for complex database schemas. The compound foreign key feature is particularly significant for users managing multi-column relationships, while case-insensitive column matching improves consistency. A subtle breaking change to table.foreign_keys was necessary to support compound foreign keys, hence this change lands in the 4.0 release. The case-insensitive column matching touched multiple parts of the codebase, as detailed in the changelog.

rss · Simon Willison · Jul 6, 05:40

**Background**: sqlite-utils is a Python command-line tool and library for creating, querying, and transforming SQLite databases. Compound foreign keys reference multiple columns simultaneously, a feature supported by SQLite but previously not fully introspected by sqlite-utils. SQLite treats column names as case-insensitive by default, but sqlite-utils previously did not match that behavior consistently.

<details><summary>References</summary>
<ul>
<li><a href="https://sqlite-utils.datasette.io/en/latest/changelog.html">Changelog - sqlite-utils</a></li>
<li><a href="https://github.com/simonw/sqlite-utils/issues/117">Support for compound (composite) foreign keys · Issue #117 · simonw/sqlite-utils</a></li>

</ul>
</details>

**Tags**: `#sqlite`, `#python`, `#database`, `#tools`

---

<a id="item-13"></a>
## [TorchJD Library Enables Multi-Loss Training in PyTorch](https://www.reddit.com/r/MachineLearning/comments/1upzxk2/torchjd_training_with_multiple_losses_in_pytorch_p/) ⭐️ 7.0/10

TorchJD, a library for training with multiple losses in PyTorch, has been accepted into the PyTorch ecosystem and now implements most existing scalarization and Jacobian descent aggregation methods. This fills a critical gap in multi-task learning by providing a unified interface for various loss aggregation techniques, enabling practitioners to easily switch between methods and improve model performance. TorchJD supports both scalarization (e.g., weighted averaging) and Jacobian descent methods, which compute per-loss gradients and aggregate them to reduce all losses simultaneously.

reddit · r/MachineLearning · /u/Skeylos2 · Jul 7, 16:20

**Background**: In multi-task learning, models are trained on multiple objectives, each with its own loss function. Scalarization combines losses into a single scalar, while Jacobian descent uses the Jacobian matrix to update parameters in a direction that decreases all losses. TorchJD provides a library of these methods, making them accessible in PyTorch.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/SimplexLab/TorchJD">GitHub - SimplexLab/TorchJD: Library for Jacobian descent with...</a></li>
<li><a href="https://arxiv.org/html/2406.16232">Jacobian Descent for Multi -Objective Optimization</a></li>

</ul>
</details>

**Tags**: `#PyTorch`, `#multi-task learning`, `#Jacobian descent`, `#loss aggregation`, `#machine learning`

---

<a id="item-14"></a>
## [CPU TTS benchmark with UTMOS compares Kokoro, Supertonic, Inflect-Nano, Pocket TTS](https://www.reddit.com/r/MachineLearning/comments/1up0azr/cpu_tts_benchmark_with_utmos_mos_scoring_kokoro/) ⭐️ 7.0/10

A benchmark evaluates four small TTS models—Kokoro, Supertonic, Inflect-Nano, and Pocket TTS—on CPU using UTMOS for objective MOS scoring, with detailed RTF and quality results across different text lengths. This benchmark provides practical latency and quality comparisons for CPU-based TTS, highlighting trade-offs between traditional architectures and new streaming LM models like Pocket TTS, which offers flat RTF scaling and zero-shot voice cloning on CPU. Pocket TTS uses a streaming LM over Mimi neural audio codec, achieving constant RTF (~0.69-0.76) across all text lengths, while others vary widely. UTMOS fails to capture naturalness for small vocoder models like Inflect-Nano, which scored 3.48 but sounds robotic.

reddit · r/MachineLearning · /u/gvij · Jul 6, 15:17

**Background**: TTS (text-to-speech) models convert text to speech. Mean Opinion Score (MOS) is a subjective quality rating, but objective predictors like UTMOS estimate it automatically. ONNX allows model inference across hardware. StyleTTS2, FastSpeech, and streaming LMs are different TTS architectures.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/sarulab-speech/UTMOS22">UTMOS: UTokyo-SaruLab MOS Prediction System - GitHub</a></li>
<li><a href="https://github.com/kyutai-labs/moshi">GitHub - kyutai-labs/moshi: Moshi is a speech-text foundation model and full-duplex spoken dialogue framework. It uses Mimi, a state-of-the-art streaming neural audio codec. · GitHub</a></li>
<li><a href="https://github.com/yl4579/styletts2">GitHub - yl4579/StyleTTS2: StyleTTS 2: Towards Human-Level Text-to-Speech through Style Diffusion and Adversarial Training with Large Speech Language Models · GitHub</a></li>

</ul>
</details>

**Tags**: `#TTS`, `#benchmark`, `#machine learning`, `#ONNX`, `#UTMOS`

---

<a id="item-15"></a>
## [98% Browser Support Isn't Enough, Says Article](https://whynothugo.nl/journal/2026/07/03/98-isnt-very-much/) ⭐️ 6.0/10

A blog post argues that 98% browser support is insufficient because the remaining 2% of users or use cases can be critical, sparking debate on trade-offs in feature adoption. This debate affects web developers who must balance broad compatibility vs. leveraging modern features, and impacts user experience for the minority that may be excluded. The article cites examples where 98% support still leaves critical gaps, and notes that support percentages vary by audience (e.g., 70% for some niches).

hackernews · speckx · Jul 7, 12:45 · [Discussion](https://news.ycombinator.com/item?id=48816959)

**Background**: Web developers often use caniuse.com data to decide when to adopt new CSS or JavaScript features based on global browser usage percentages. The 98% threshold is commonly considered safe, but this article challenges that assumption by emphasizing edge cases and accessibility.

**Discussion**: Comments show a split: some agree that 98% is often enough if business goals are realistic, while others share personal experiences where 70% support caused issues. One comment compares removing pine needles to illustrate diminishing returns as 100% is approached.

**Tags**: `#web development`, `#browser support`, `#software engineering`, `#accessibility`, `#product strategy`

---

<a id="item-16"></a>
## [ML Job Requirements Become Unrealistic, Non-FAANG Firms Seek Multiple Deep Expertise](https://www.reddit.com/r/MachineLearning/comments/1uov7or/machine_learning_industry_job_requirements_used/) ⭐️ 6.0/10

A Reddit user highlights a non-FAANG industrial automation company job listing requiring deep expertise in LLMs, VLAs, VLMs, action transformers, robot dynamics, kinematics, sensor fusion, model predictive control, reinforcement learning, CUDA, and FPGA hardware acceleration, noting that such breadth is unrealistic. This reflects a growing trend in the machine learning job market where companies, especially outside big tech, demand expertise across multiple specialized fields, making it difficult for even experienced professionals to qualify. It signals potential inefficiencies in hiring practices that could slow innovation and exclude talented candidates. The job listing specifically requested top publications in ML and robotics conferences, familiarity with RLib (a reinforcement learning library), and 3-5+ years of non-academic experience. The poster compared the requirements to needing to be a 'warrior archer warlock who is also a shaman priest mage' in an MMORPG.

reddit · r/MachineLearning · /u/NeighborhoodFatCat · Jul 6, 11:57

**Background**: Recent advances in robotics have combined vision-language models (VLMs) with action decoders to create vision-language-action (VLA) models for end-to-end robot control. Action transformers, such as the Action Chunking Transformer (ACT), are used for manipulation tasks. Additionally, FPGA hardware acceleration is being explored to boost machine learning inference performance, but expertise in these areas typically requires years of specialized study. The combination of all these skills in one person is extremely rare, as noted by mathematician Terence Tao regarding the rarity of deep expertise across different mathematical disciplines.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Vision–language–action_model">Vision–language–action model - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2508.13073">[2508.13073] Large VLM-based Vision-Language-Action Models ...</a></li>
<li><a href="https://ictactjournals.in/paper/IJME_Vol_9_Iss_3_Paper_5_1613_1619.pdf">Fpga -based hardware acceleration of machine learning</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#job market`, `#hiring`, `#robotics`

---

<a id="item-17"></a>
## [LingBot-Depth 2.0: Sensor-validity masking for depth estimation](https://www.reddit.com/r/MachineLearning/comments/1upqghy/masked_depth_modeling_with_sensorvalidity_masking/) ⭐️ 6.0/10

LingBot-Depth 2.0 introduces sensor-validity masking, using sensor failure regions (e.g., specular highlights, transparent surfaces) as natural masks for masked depth modeling, achieving best RMSE on 7 of 8 sparse depth benchmarks. This work addresses a key limitation of RGB-D sensors by training directly on their failure cases, potentially improving robustness for real-world applications like robotics and autonomous driving. The model uses a Vision Transformer encoder initialized with LingBot-Vision pretraining. Notably, the depth weights are not released; only the vision backbones are open-source.

reddit · r/MachineLearning · /u/Ok-Line2658 · Jul 7, 09:54

**Background**: Masked depth modeling (MDM) is a self-supervised learning approach for depth completion. Standard MDM uses random block masks, but sensor-validity masking leverages actual sensor invalid regions (e.g., due to specularity or transparency) as masks, making the model learn to handle real sensor failures.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2601.17895">[2601.17895] Masked Depth Modeling for Spatial Perception</a></li>
<li><a href="https://github.com/Robbyant/lingbot-depth">GitHub - Robbyant/lingbot-depth: Masked Depth Modeling for ...</a></li>

</ul>
</details>

**Discussion**: A commenter questions whether sensor-validity masking generalizes to other sensing modalities like LiDAR or thermal, indicating interest in the broader applicability of the approach.

**Tags**: `#depth estimation`, `#masked modeling`, `#self-supervised learning`, `#computer vision`, `#RGB-D`

---