---
layout: default
title: "Horizon Summary: 2026-06-21 (EN)"
date: 2026-06-21
lang: en
---

> From 30 items, 17 important content pieces were selected

---

1. [ATProto Identity Ownership Examined: Who Really Controls It?](#item-1) ⭐️ 8.0/10
2. [Loupe App Exposes iOS Device Data Accessible to Apps](#item-2) ⭐️ 8.0/10
3. [Slow breathing boosts risk-taking via enhanced parasympathetic activity](#item-3) ⭐️ 8.0/10
4. [Softmax-Free Attention Model at GPT-2 Medium Scale Released](#item-4) ⭐️ 8.0/10
5. [Time Series Models Need Dynamical Systems Perspective](#item-5) ⭐️ 8.0/10
6. [Open handbook on LLM inference at scale covers GPU internals and key frameworks](#item-6) ⭐️ 8.0/10
7. [minFLUX: A Minimal PyTorch Implementation of FLUX Models](#item-7) ⭐️ 8.0/10
8. [Google IPv6 Traffic Reaches 50% Milestone](#item-8) ⭐️ 7.0/10
9. [3D Voxel Game Engine Built in APL](#item-9) ⭐️ 7.0/10
10. [A Critical Analysis of Geometric Algebra (2024)](#item-10) ⭐️ 7.0/10
11. [Build Your Own LLM Workshop on YouTube](#item-11) ⭐️ 7.0/10
12. [ML PhD Graduation Without Top-Tier Paper?](#item-12) ⭐️ 7.0/10
13. [DVD-JEPA: Open-Source JEPA World Model](#item-13) ⭐️ 7.0/10
14. [Beyond All Reason: Free Open-Source RTS Inspired by Total Annihilation](#item-14) ⭐️ 6.0/10
15. [Improved DVD-JEPA Demo Shows JEPA Advantages](#item-15) ⭐️ 6.0/10
16. [EMA on LoRA for Self-Distillation: A Practical Query](#item-16) ⭐️ 6.0/10
17. [TSAuditor: A lightweight time-series data auditing tool](#item-17) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [ATProto Identity Ownership Examined: Who Really Controls It?](https://kevinak.se/blog/who-actually-owns-your-atproto-identity-hint-its-probably-not-you) ⭐️ 8.0/10

A critical analysis argues that most ATProto identity owners do not truly control their identities, as they rely on hosting providers like Bluesky Social's PDS. The article highlights that only self-hosting ensures full independence. This matters because ATProto is the foundation of Bluesky and aims to solve data portability, but if most users cede control to hosting providers, the protocol's decentralization promise is undermined. The discussion impacts trust in decentralized social networks and the trade-offs between convenience and sovereignty. The article points out that ATProto identities are typically managed through a Personal Data Server (PDS), and if the PDS operator turns malicious or is compromised, they could impersonate the user. Users can regain control by self-hosting their own PDS or using did:web identity.

hackernews · kevinak · Jun 21, 14:09 · [Discussion](https://news.ycombinator.com/item?id=48619140)

**Background**: The AT Protocol (ATProto) is an open, decentralized protocol for social networking, designed to allow users to move their data and identity across different hosting providers. It uses a Personal Data Server (PDS) to store user data and a decentralized identity system (PLC or did:web). While the protocol supports portability, most users rely on hosted PDS services, creating a trust dependency similar to traditional web services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AT_Protocol">AT Protocol</a></li>
<li><a href="https://atproto.com/guides/self-hosting">Self-hosting - AT Protocol Docs - AT Protocol</a></li>
<li><a href="https://kghorvath.com/creating-a-did-web-identity-in-atproto">Creating a did:web identity in ATProto — Kamin's Corner</a></li>

</ul>
</details>

**Discussion**: Community comments reflect a range of views: some argue that the reliance on hosting providers is similar to other services like domains or GitHub, and most people don't worry about it. Others highlight that ATProto's data portability is a key improvement over ActivityPub, and self-hosting is a viable option for those who need it. A few note that this is an inherent trade-off in any hosted identity system.

**Tags**: `#decentralization`, `#identity`, `#ATProtocol`, `#Bluesky`, `#self-hosting`

---

<a id="item-2"></a>
## [Loupe App Exposes iOS Device Data Accessible to Apps](https://github.com/mysk-research/loupe) ⭐️ 8.0/10

Security research team Mysk released a free, open-source iOS app called Loupe that demonstrates the sensitive device data any third-party app can access through public iOS APIs, such as installed apps, Wi-Fi details, and file timestamps. Loupe raises privacy awareness by showing users how easily their devices can be fingerprinted, revealing potential privacy vulnerabilities in iOS that users and developers should address. The app reads real values from public iOS APIs and displays them raw, covering categories like installed app probing, pasteboard change count, and volume creation date; it is available on the App Store and as open source on GitHub.

hackernews · Cider9986 · Jun 20, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48608645)

**Background**: Device fingerprinting is a technique where apps collect unique device characteristics to identify and track users without their consent. iOS apps can access certain data through public APIs that Apple provides, but some of this data can be combined to create a fingerprint. Loupe educates users by revealing exactly what data is accessible, highlighting the gap between what users expect and what apps can actually see.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/mysk-research/loupe">GitHub - mysk-research/loupe: A privacy-focused iOS app that ...</a></li>
<li><a href="https://apps.apple.com/us/app/loupe-what-apps-can-see/id6766152470">Loupe: What Apps Can See App - App Store</a></li>

</ul>
</details>

**Discussion**: Community comments expressed surprise and concern, particularly about the 'iPhone last setup or erased on' timestamp and the ability to probe for installed apps. Some users suggested that internet access should be opt-in to prevent data exfiltration, while others noted Apple's restrictions on querying arbitrary app lists. Overall, the discussion highlighted a desire for better OS-level privacy controls.

**Tags**: `#iOS`, `#privacy`, `#security`, `#mobile apps`, `#app permissions`

---

<a id="item-3"></a>
## [Slow breathing boosts risk-taking via enhanced parasympathetic activity](https://www.cell.com/neuron/fulltext/S0896-6273(26)00339-9) ⭐️ 8.0/10

A Neuron study found that slow breathing, especially prolonged exhalation, enhances cardiac parasympathetic activity and increases risk-taking behavior in humans. This challenges the conventional view that parasympathetic activation simply promotes relaxation, revealing a link to reward processing that could inform anxiety and depression treatments. The effect was specific to prolonged exhalation, not just slow breathing, and selectively influenced reward responsiveness without altering overall arousal.

hackernews · croes · Jun 20, 22:22 · [Discussion](https://news.ycombinator.com/item?id=48613555)

**Background**: The parasympathetic nervous system, known as the 'rest and digest' system, slows heart rate and promotes calm. Slow breathing techniques have long been used to manage stress, but their impact on reward and risk-taking was unclear. This study provides mechanistic insight using physiological measures.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Parasympathetic_nervous_system">Parasympathetic nervous system - Wikipedia</a></li>
<li><a href="https://my.clevelandclinic.org/health/body/23266-parasympathetic-nervous-system-psns">Parasympathetic Nervous System (PSNS): What It Is & Function</a></li>

</ul>
</details>

**Discussion**: Commenters noted practical applications for public speaking, with one user stating slow breathing helps overcome irrational fear and promotes confident risk-taking. Another expressed surprise at the link between parasympathetic activation and increased risk-taking. Some asked about long-term breathing pattern changes and wearable monitoring.

**Tags**: `#neuroscience`, `#breathing`, `#brain function`, `#risk behavior`, `#anxiety`

---

<a id="item-4"></a>
## [Softmax-Free Attention Model at GPT-2 Medium Scale Released](https://www.reddit.com/r/MachineLearning/comments/1ubmybr/i_released_a_softmaxfree_attention_model_at_gpt2/) ⭐️ 8.0/10

A researcher released a softmax-free attention model at GPT-2 Medium scale (~354M parameters, trained on 11.5B tokens) with custom Triton kernels that leverage structural sparsity and tile-skipping for long-context VRAM savings. The model weights and Triton kernels are open-sourced. This work addresses a key bottleneck in scaling transformers to long contexts by eliminating the softmax operation, which traditionally requires O(n^2) memory. The open-source release enables the community to experiment with efficient attention alternatives and custom kernel optimizations. The model uses softmax-free attention combined with structural sparsity and custom tile-skipping Triton kernels to reduce VRAM usage for long sequences. The pretrained model has about 354 million parameters and was trained on 11.5 billion tokens.

reddit · r/MachineLearning · /u/NonGameCatharsis · Jun 21, 10:46

**Background**: Standard transformer attention uses a softmax function to compute attention weights, which requires storing a full attention matrix that grows quadratically with sequence length, causing high memory consumption for long contexts. Softmax-free attention mechanisms, such as SOFT, replace the softmax with linear operations to achieve O(n) complexity. Structural sparsity in transformers exploits the natural sparsity in activation patterns to skip unnecessary computations, while Triton is a Python-based language for writing efficient GPU kernels that can be optimized for specific operations.

<details><summary>References</summary>
<ul>
<li><a href="https://victorllu.github.io/assets/pdf/soft.pdf">SOFT: Softmax - free Transformer with Linear</a></li>
<li><a href="https://openreview.net/pdf?id=c4m0BkO4OL">Towards Structured Sparsity in Transformers for Efficient Inference</a></li>
<li><a href="https://triton-lang.org/main/index.html">Welcome to Triton’s documentation! — Triton documentation</a></li>

</ul>
</details>

**Tags**: `#attention mechanisms`, `#efficient transformers`, `#kernel optimization`, `#open source`, `#long context`

---

<a id="item-5"></a>
## [Time Series Models Need Dynamical Systems Perspective](https://www.reddit.com/r/MachineLearning/comments/1uark0u/time_series_modeling_needs_a_dynamical_systems/) ⭐️ 8.0/10

A position paper at ICML 2026 argues that time series modeling should adopt dynamical systems reconstruction to achieve out-of-domain generalization and long-term prediction, contrasting with current forecasting-only approaches. This paradigm shift could enable true generalization across different regimes and long-term forecasting in complex systems like weather, finance, or biology, addressing fundamental limitations of current deep learning time series models. The paper recommends focusing on dynamical-specific training techniques like generalized teacher forcing, pretraining on dynamical system simulations, and moving from transformers to modern RNNs which better handle temporal recursions.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Jun 20, 08:47

**Background**: Time series modeling typically treats data as independent time steps, ignoring that most real-world time series originate from underlying dynamical systems, often chaotic. Dynamical systems reconstruction aims to infer the governing rules from observations, enabling mechanistic understanding and long-term prediction. The paper highlights that current models fail at out-of-domain generalization and capturing long-term statistical structure.

**Tags**: `#time series`, `#dynamical systems`, `#machine learning`, `#ICML`, `#reconstruction`

---

<a id="item-6"></a>
## [Open handbook on LLM inference at scale covers GPU internals and key frameworks](https://www.reddit.com/r/MachineLearning/comments/1uavduv/an_open_handbook_on_llm_inference_at_scale_gpu/) ⭐️ 8.0/10

An open-source handbook on LLM inference at scale has been published on GitHub, covering GPU execution and memory internals, KV cache, batching, and production frameworks like vLLM, SGLang, and TensorRT-LLM. The author is actively seeking community feedback to refine the content. This handbook fills a gap by providing a comprehensive, practical guide to optimizing LLM inference, a critical bottleneck for deploying large models in production. It helps engineers understand and leverage key techniques like KV caching and batching to reduce latency and cost. The handbook includes mermaid diagrams to visualize GPU memory hierarchy and bottleneck flows. It is an evolving project, with the author inviting issues and pull requests for corrections.

reddit · r/MachineLearning · /u/YouFirst295 · Jun 20, 12:27

**Background**: LLM inference at scale involves efficiently running large language models to generate responses, which is computationally intensive and memory-bound. Key optimizations include KV cache to avoid recomputation, batching to utilize GPU parallelism, and frameworks like vLLM and SGLang that implement advanced memory management such as PagedAttention. Understanding GPU internals like memory hierarchy and compute utilization helps identify bottlenecks.

<details><summary>References</summary>
<ul>
<li><a href="https://magazine.sebastianraschka.com/p/coding-the-kv-cache-in-llms">Understanding and Coding the KV Cache in LLMs from Scratch</a></li>
<li><a href="https://github.com/vllm-project/vllm">GitHub - vllm-project/vllm: A high-throughput and memory-efficient inference and serving engine for LLMs · GitHub</a></li>
<li><a href="https://github.com/sgl-project/sglang">GitHub - sgl-project/sglang: SGLang is a high-performance ...</a></li>

</ul>
</details>

**Tags**: `#LLM inference`, `#GPU`, `#deep learning`, `#machine learning systems`, `#open source`

---

<a id="item-7"></a>
## [minFLUX: A Minimal PyTorch Implementation of FLUX Models](https://www.reddit.com/r/MachineLearning/comments/1ub1db3/studying_flux_in_diffusers_library_was_hard_so_i/) ⭐️ 8.0/10

A developer released minFLUX, a minimal PyTorch implementation of FLUX.1 and FLUX.2 diffusion models, with line-by-line mappings to HuggingFace diffusers and training/inference loops. This project lowers the barrier for studying FLUX architectures by providing a clear, educational codebase, making it easier for researchers and practitioners to understand and experiment with state-of-the-art diffusion models. minFLUX includes VAE encode/decode, flow matching training via velocity MSE, and Euler ODE inference; it also reveals architectural differences between FLUX.1 and FLUX.2, such as changes in transformer blocks, modulation, and position IDs.

reddit · r/MachineLearning · /u/Other-Eye-8152 · Jun 20, 16:50

**Background**: FLUX is a family of text-to-image diffusion models developed by Black Forest Labs, with FLUX.2 introducing improved components like dual-stream transformers and flow matching. The official HuggingFace diffusers library is feature-rich but can be hard to navigate for learning purposes.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Flux_(text-to-image_model)">Flux (text-to-image model) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2507.09595">[2507.09595] Demystifying Flux Architecture - arXiv.org</a></li>

</ul>
</details>

**Tags**: `#diffusion models`, `#FLUX`, `#PyTorch`, `#open source`, `#machine learning`

---

<a id="item-8"></a>
## [Google IPv6 Traffic Reaches 50% Milestone](https://blog.apnic.net/2026/04/28/google-hits-50-ipv6/) ⭐️ 7.0/10

Google's global IPv6 traffic has reached the 50% milestone, as reported by APNIC in April 2026. This milestone demonstrates growing IPv6 adoption, which is crucial for internet scalability as IPv4 addresses become scarce and costly. The 50% figure is a global average; regional variations are significant, with some countries like France exceeding 85% IPv6 adoption.

hackernews · barqawiz · Jun 21, 08:21 · [Discussion](https://news.ycombinator.com/item?id=48616800)

**Background**: IPv6 is the next-generation internet protocol designed to replace IPv4 due to the limited number of IPv4 addresses. Despite decades of availability, adoption has been slow due to costs, technical challenges, and lack of ISP incentives. The depletion of IPv4 addresses has created a secondary market for buying and selling IPv4 blocks.

<details><summary>References</summary>
<ul>
<li><a href="https://www.ipxo.com/blog/ipv6-adoption-challenges-2025/">Why IPv6 Adoption Still Lags - ipxo.com</a></li>
<li><a href="https://www.ipxo.com/market-stats/">IPv4 Market stats - IPXO</a></li>

</ul>
</details>

**Discussion**: Comments highlight regional success stories like France's high adoption and practical barriers such as ISPs charging for static IPv4 addresses and services like GitHub lacking IPv6 support.

**Tags**: `#IPv6`, `#networking`, `#internet infrastructure`, `#Google`, `#adoption`

---

<a id="item-9"></a>
## [3D Voxel Game Engine Built in APL](https://github.com/namgyaaal/avoxelgame) ⭐️ 7.0/10

A developer has created a buggy but functional 3D voxel game engine using the array-oriented programming language APL, showcasing the language's unique symbolic notation for voxel modeling. This project highlights the versatility of APL beyond its traditional numerical computing domains, and could inspire further exploration of unusual language choices for game development. The engine is described by the author as a 'buggy passion project' and is available on GitHub under the repository namgyaaal/avoxelgame. It uses APL's concise notation to manipulate voxel data.

hackernews · sph · Jun 21, 08:04 · [Discussion](https://news.ycombinator.com/item?id=48616713)

**Background**: APL is a programming language developed in the 1960s known for its concise symbolic notation and multidimensional array data type. Voxels are the 3D equivalent of pixels, representing values on a regular 3D grid, commonly used in games like Minecraft. Combining APL with voxel game development is unusual because APL is rarely used for real-time graphics applications.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/APL_(programming_language)">APL (programming language)</a></li>
<li><a href="https://en.wikipedia.org/wiki/Voxel">Voxel</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project's honesty and novelty. One user noted that a voxel world is a good sales pitch for APL because the unusual notation aligns well with the model. Another expressed interest in the development process and challenges of using APL for such a project.

**Tags**: `#APL`, `#game engine`, `#voxel`, `#programming languages`

---

<a id="item-10"></a>
## [A Critical Analysis of Geometric Algebra (2024)](https://alexkritchevsky.com/2024/02/28/geometric-algebra.html) ⭐️ 7.0/10

Alex Kritchevsky published a critical article examining geometric algebra, questioning its theoretical and practical merits, which ignited substantial debate in the community. This matters because geometric algebra has been promoted as a unifying mathematical framework for physics and engineering; the criticism challenges its adoption and reflects broader tensions between pure mathematics and applied fields. The author argues that geometric algebra attracts 'crackpots' and lacks academic rigor, while proponents defend its practical utility in computer graphics and robotics. The debate mirrors similar controversies like the Rust community's discussions.

hackernews · Hbruz0 · Jun 21, 11:06 · [Discussion](https://news.ycombinator.com/item?id=48617782)

**Background**: Geometric algebra, also known as Clifford algebra, extends vector algebra to handle oriented subspaces like lines, planes, and volumes. It was popularized by David Hestenes for applications in relativistic physics. Critics argue its benefits are overstated and its notation obscure, while supporters claim it simplifies complex calculations and provides intuitive geometric insights.

<details><summary>References</summary>
<ul>
<li><a href="https://alexkritchevsky.com/2024/02/28/geometric-algebra.html">The Case Against Geometric Algebra</a></li>
<li><a href="https://en.wikipedia.org/wiki/Geometric_algebra">Geometric algebra</a></li>

</ul>
</details>

**Discussion**: Comments show mixed reactions: some agree with the critique about academic rigor and note the prevalence of overenthusiastic proponents, while others value GA's practical simplicity and criticize the article for ad hominem attacks. Some compare the debate to the pi vs tau argument or Rust community disputes.

**Tags**: `#geometric algebra`, `#mathematics`, `#community debate`, `#critical analysis`, `#Hacker News`

---

<a id="item-11"></a>
## [Build Your Own LLM Workshop on YouTube](https://www.reddit.com/r/MachineLearning/comments/1uazlnd/hi_reddit_i_posted_my_build_your_own_llm_workshop/) ⭐️ 7.0/10

Justin Angel released a workshop video series titled 'Build Your Own LLM' on YouTube, covering ML fundamentals, transformer architecture, and LLM training without any math or ML prerequisites. This workshop makes LLM building accessible to a wider audience, including coders without deep ML backgrounds, potentially accelerating AI education and hands-on experimentation. The workshop includes over 40 topics, uses slides, Excel examples, and PyTorch code, and covers everything from perceptrons to pre/post-training, including instruction tuning and reinforcement learning.

reddit · r/MachineLearning · /u/JustinAngel · Jun 20, 15:36

**Background**: Transformer-based LLMs rely on components like attention, feed-forward networks, and normalization. Specific techniques like SwiGLU activation and RMSNorm improve performance. Fused kernels optimize GPU execution by combining multiple operations into a single kernel, reducing overhead.

<details><summary>References</summary>
<ul>
<li><a href="https://abdulkaderhelwan.medium.com/swiglu-activation-function-77627e0b2b52">SwiGLU Activation Function . SwiGLU (Swish-Gated Linear... | Medium</a></li>
<li><a href="https://docs.pytorch.org/docs/2.12/generated/torch.nn.modules.normalization.RMSNorm.html">RMSNorm — PyTorch 2.12 documentation</a></li>
<li><a href="https://arxiv.org/pdf/2508.07071">The Fused Kernel Library: A C++ API to Develop Highly ...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#tutorial`, `#machine learning`, `#workshop`, `#YouTube`

---

<a id="item-12"></a>
## [ML PhD Graduation Without Top-Tier Paper?](https://www.reddit.com/r/MachineLearning/comments/1uazlhg/would_you_let_an_ml_phd_student_graduate_without/) ⭐️ 7.0/10

A Reddit user asks whether an ML PhD advisor should let a student graduate without a top-tier publication (NeurIPS/ICML/ICLR/CVPR), assuming solid work and three first-author A-level papers. This debate reflects ongoing tensions in ML academia over publication pressure, graduation standards, and what constitutes sufficient contribution. The outcome could influence future PhD requirements and student well-being. The hypothetical student has three first-author A-level papers but no A* venue publications. The question hinges on whether a solid thesis and other work compensate for missing top-tier conference papers.

reddit · r/MachineLearning · /u/Hope999991 · Jun 20, 15:36

**Background**: In ML academia, publication in top venues like NeurIPS, ICML, ICLR, or CVPR is often considered a de facto requirement for PhD graduation. A* venues are the highest-ranked conferences, while A-level conferences are still reputable but less selective. This strict norm has been increasingly questioned due to concerns about mental health, bias, and alternative contributions.

**Tags**: `#academia`, `#PhD`, `#machine learning`, `#publications`

---

<a id="item-13"></a>
## [DVD-JEPA: Open-Source JEPA World Model](https://www.reddit.com/r/MachineLearning/comments/1uatlzx/dvdjepa_an_opensource_fullyreproducible_jepa/) ⭐️ 7.0/10

Researchers released DVD-JEPA, a minimal open-source implementation of the JEPA architecture that predicts future representations instead of pixels, demonstrating sub-pixel position recovery and anomaly detection in a browser-based demo. This work provides a fully reproducible, low-resource example of the JEPA concept, making it accessible for anomaly detection and representation learning research without requiring extensive computational resources. The model achieves sub-pixel accuracy (0.73 px) in recovering object position via a linear probe on a frozen 32-dimensional latent space, and can generate up to 20 steps of future video frames before latent drift occurs.

reddit · r/MachineLearning · /u/NielsRogge · Jun 20, 10:52

**Background**: JEPA (Joint-Embedding Predictive Architecture) is a self-supervised learning method that predicts abstract representations of future states rather than reconstructing pixels or tokens. It uses a context encoder, an EMA target encoder, and a latent predictor, trained without labels. The EMA target encoder stabilizes training by maintaining slow-moving averages of encoder weights. This approach contrasts with generative world models that attempt pixel-level prediction, which are often computationally expensive and capture unpredictable details.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Joint_Embedding_Predictive_Architecture">Joint Embedding Predictive Architecture</a></li>
<li><a href="https://grokipedia.com/page/Joint_Embedding_Predictive_Architecture">Joint Embedding Predictive Architecture</a></li>

</ul>
</details>

**Tags**: `#JEPA`, `#world model`, `#representation learning`, `#open-source`, `#anomaly detection`

---

<a id="item-14"></a>
## [Beyond All Reason: Free Open-Source RTS Inspired by Total Annihilation](https://www.beyondallreason.info/) ⭐️ 6.0/10

Beyond All Reason (BAR) is a free, open-source real-time strategy game that recreates and expands upon the classic Total Annihilation. It has gained attention for its technical polish and faithful homage to the original. As a high-quality open-source RTS, BAR demonstrates how community-driven development can preserve and evolve classic game genres. Its popularity highlights ongoing demand for traditional RTS mechanics in a market dominated by other genres. BAR is built on the Spring RTS engine, a descendant of the Total Annihilation engine. It features hundreds of units, massive battles, and fully moddable content, but its steep learning curve and rigid meta can lead to a toxic multiplayer environment.

hackernews · mosiuerbarso · Jun 21, 11:38 · [Discussion](https://news.ycombinator.com/item?id=48617990)

**Background**: Total Annihilation (TA), released in 1997, is a landmark RTS known for its 3D units and large-scale battles. Beyond All Reason is one of several open-source projects inspired by TA, alongside others like Zero-K. BAR aims to modernize the TA experience while remaining free and community-driven.

**Discussion**: Community comments on Hacker News are mixed: many praise the game's technical achievements and nostalgic value, but several players report a toxic multiplayer culture where rigid meta and player votes can lead to kick abuse. Some suggest sticking to PvE or bot matches to avoid negativity, while others point to related games like Zero-K as alternatives with better community dynamics.

**Tags**: `#open-source`, `#gaming`, `#RTS`, `#Total Annihilation`, `#community`

---

<a id="item-15"></a>
## [Improved DVD-JEPA Demo Shows JEPA Advantages](https://www.reddit.com/r/MachineLearning/comments/1ubtf09/a_slightly_improved_dvdjepa_demo_p/) ⭐️ 6.0/10

A user forked an existing DVD-JEPA demo and added environment noise as well as a fair comparison to a pixel-space baseline, demonstrating JEPA's ability to disregard irrelevant details. The updated demo removes the web-demo and anomaly detection components to focus on core JEPA ideas. This improvement clarifies JEPA's advantages over pixel-space methods, especially its robustness to unpredictable noise, which is a key motivation for JEPA as emphasized by Yann LeCun. It provides a clearer demonstration for researchers and practitioners evaluating JEPA for representation learning. The baseline comparison is considered fair because it uses roughly the same parameter count and compute budget; the linear probe and decoder compute budgets are treated as independent from core model training. The modifications were made using AI assistance in a quick afternoon project.

reddit · r/MachineLearning · /u/Kirne · Jun 21, 15:49

**Background**: JEPA (Joint Embedding Predictive Architecture) is a self-supervised learning framework proposed by Yann LeCun that predicts representations in latent space rather than pixels, allowing it to ignore unpredictable details. V-JEPA extends this to video. A pixel-space baseline directly predicts raw pixel values, which is computationally expensive and struggles with noise.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/facebookresearch/jepa">GitHub - facebookresearch/jepa: PyTorch code and models for V ... GitHub - AI-in-Transportation-Lab/awesome-jepa: A carefully ... V-JEPA: The next step toward advanced machine intelligence JEPA - GeeksforGeeks Value-guided action planning with JEPA world models</a></li>
<li><a href="https://rohitbandaru.github.io/blog/JEPA-Deep-Dive/">Deep Dive into Yann LeCun’s JEPA | Rohit Bandaru</a></li>

</ul>
</details>

**Tags**: `#JEPA`, `#machine learning`, `#representation learning`, `#demo`, `#video prediction`

---

<a id="item-16"></a>
## [EMA on LoRA for Self-Distillation: A Practical Query](https://www.reddit.com/r/MachineLearning/comments/1ubv0f5/ema_on_lora_r/) ⭐️ 6.0/10

A Reddit user asked whether Exponential Moving Average (EMA) can be applied to Low-Rank Adaptation (LoRA) adapters for on-policy self-distillation, referencing the paper "Self-Distilled Reasoner: On-Policy Self-Distillation for LLMs" (arXiv:2601.18734). This question addresses a practical gap in combining two popular techniques—parameter-efficient fine-tuning via LoRA and self-distillation with EMA—potentially enabling more efficient and stable model adaptation without full fine-tuning. The referenced paper uses EMA on the full model weights as a teacher for on-policy self-distillation, but the user seeks empirical results where EMA is applied only to LoRA adapters while the base model remains frozen.

reddit · r/MachineLearning · /u/South-Conference-395 · Jun 21, 16:54

**Background**: LoRA is a parameter-efficient fine-tuning method that injects trainable low-rank matrices into a pre-trained model while freezing all original weights. Self-distillation is a technique where a model learns from its own predictions, often using an Exponential Moving Average (EMA) of model parameters as a teacher to generate stable soft labels. On-policy self-distillation improves this by having the teacher generate labels from the student's current distribution, which is more aligned but computationally more expensive.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LoRA_(machine_learning)">LoRA (machine learning) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2601.18734">[2601.18734] Self-Distilled Reasoner: On-Policy Self ...</a></li>
<li><a href="https://link.springer.com/article/10.1007/s00371-025-04032-2">Self-knowledge distillation through ensemble model averaging ...</a></li>

</ul>
</details>

**Tags**: `#LoRA`, `#EMA`, `#self-distillation`, `#transfer learning`

---

<a id="item-17"></a>
## [TSAuditor: A lightweight time-series data auditing tool](https://www.reddit.com/r/MachineLearning/comments/1ub15wf/tsauditor_a_timeseries_auditing_framework_p/) ⭐️ 6.0/10

The author introduces TSAuditor, an open-source Python library on PyPI that automatically detects chronological breaks, data leakage, and missing data chunks in time-series pipelines. Time-series data pitfalls like chronological breaks and data leakage are common yet hard to spot, and TSAuditor helps practitioners avoid flawed models by providing targeted validation. TSAuditor generates a structured report for each faulty data point, including a description and evidence, and suggests fixes; it works without requiring a predefined domain.

reddit · r/MachineLearning · /u/severecaseofsarcarsm · Jun 20, 16:41

**Background**: Time-series data often suffers from missing chunks, chronological breaks, and leakage between features and target, which standard profiling tools may overlook. These issues can lead to misleading model performance, such as inflated accuracy. TSAuditor was created to simplify the EDA process for time-series datasets by catching these structural problems early.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/imann128/tsauditor">GitHub - imann128/tsauditor: A data quality auditing library ...</a></li>
<li><a href="https://github.com/imann128/tsauditor/releases">Releases · imann128/tsauditor · GitHub</a></li>

</ul>
</details>

**Tags**: `#time-series`, `#data auditing`, `#machine learning`, `#data validation`, `#python`

---