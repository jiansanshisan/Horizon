---
layout: default
title: "Horizon Summary: 2026-06-20 (EN)"
date: 2026-06-20
lang: en
---

> From 20 items, 14 important content pieces were selected

---

1. [GLM 5.2 Open Source with 1M Lossless Context Questioned](#item-1) ⭐️ 9.0/10
2. [ATProto Has No Instances – Dan Abramov](#item-2) ⭐️ 8.0/10
3. [GPT-5.5 hallucinates 3x more than GLM-5.2, study claims](#item-3) ⭐️ 8.0/10
4. [Datasette Apps: Host custom HTML applications inside Datasette](#item-4) ⭐️ 8.0/10
5. [Time Series Needs Dynamical Systems Perspective](#item-5) ⭐️ 8.0/10
6. [Open Handbook on LLM Inference at Scale Released](#item-6) ⭐️ 8.0/10
7. [Safe GPU Inference in Rust with cuTile, Competitive with vLLM](#item-7) ⭐️ 8.0/10
8. [Storing a Website in a Favicon via Steganography](#item-8) ⭐️ 7.0/10
9. [Exploring Colors Beyond Screen Gamuts](#item-9) ⭐️ 7.0/10
10. [DVD-JEPA: open-source reproducible JEPA world model](#item-10) ⭐️ 7.0/10
11. [Global PM2.5 Forecaster Solves Variance Trap](#item-11) ⭐️ 7.0/10
12. [Mini torch.compile in 500 lines explains operator fusion speedups](#item-12) ⭐️ 7.0/10
13. [CSS Quake: A Browser-Based Recreation](#item-13) ⭐️ 6.0/10
14. [Datasette-acl 0.6a0 expands to general resource sharing](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM 5.2 Open Source with 1M Lossless Context Questioned](https://www.reddit.com/r/MachineLearning/comments/1uayssn/glm_52_open_with_1m_lossless_context_for_long/) ⭐️ 9.0/10

Zhipu released GLM 5.2 under the MIT license, claiming a 1M token lossless context using a novel IndexShare attention scheme and an improved multi-token prediction (MTP) layer for speculative decoding. The model ranks second overall and first among open-source models on the Code Arena benchmark, and performs between Opus 4.7 and 4.8 on long-horizon coding tasks. If the lossless claim holds, GLM 5.2 could make very long contexts economically viable for multi-day agent sessions, which is currently a major bottleneck. However, the community is questioning the definition of 'lossless' and the methodology used in benchmarking, emphasizing the need for real-world testing beyond leaderboard numbers. The IndexShare scheme reduces per-token FLOPs by approximately 2.9x at long contexts, and the MTP layer accelerates inference via speculative decoding. The author questions how context degradation is measured beyond 800K tokens and wonders about the task distribution and tool usage in the benchmark compared to Opus models.

reddit · r/MachineLearning · /u/Adept_Celebration_71 · Jun 20, 15:03

**Background**: Long-context LLMs typically suffer from quadratic attention complexity, making full attention prohibitively expensive. Efficient attention mechanisms like sparse or routing attention reduce this cost but may introduce information loss. Speculative decoding accelerates generation by using a draft model to predict multiple tokens per step, reducing latency. The term 'lossless context' implies that the model retains full fidelity to all input tokens without degradation, which is challenging at very long lengths.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2606.06467">You Only Index Once: Cross-Layer Sparse Attention with Shared Routing</a></li>
<li><a href="https://huggingface.co/blog/ganler/blazedit">Blazing-Fast Code Editing via Multi- Layer Speculation</a></li>
<li><a href="https://arxiv.org/abs/2605.04050">[2605.04050] LCM: Lossless Context Management - arXiv.org</a></li>

</ul>
</details>

**Discussion**: The Reddit comment section (not shown in full) likely includes skepticism about the lossless claim, with users pointing to the difficulty of maintaining context fidelity past hundreds of thousands of tokens. The author's call for real-world agentic tasks with many tool calls suggests a desire for more rigorous evaluation beyond standard benchmarks.

**Tags**: `#long context`, `#open-source LLM`, `#GLM`, `#speculative decoding`, `#efficient attention`

---

<a id="item-2"></a>
## [ATProto Has No Instances – Dan Abramov](https://overreacted.io/there-are-no-instances-in-atproto/) ⭐️ 8.0/10

Dan Abramov published a blog post clarifying that ATProto, the protocol underlying Bluesky, has no concept of 'instances,' unlike Mastodon's ActivityPub, and explained its modular architecture of Personal Data Servers (PDS), Relays, and AppViews. This clarification addresses a widespread misunderstanding in the decentralized social media community, emphasizing the architectural trade-offs between ATProto's modular design and ActivityPub's instance-based federation, which influences discussions on centralization, scalability, and user control. In ATProto, PDSes store user data, Relays aggregate data from many PDSes, and AppViews present it to users, whereas ActivityPub bundles these functions into self-hosted instances; critics note that Bluesky PBC currently operates most Relays, creating a centralization risk.

hackernews · danabramov · Jun 19, 15:10 · [Discussion](https://news.ycombinator.com/item?id=48599515)

**Background**: Decentralized social networks like Mastodon use protocols such as ActivityPub, where each 'instance' is an independently operated server hosting its own users and content. In contrast, ATProto separates concerns into three microservice layers: Personal Data Servers (PDS) for user data, Relays for data replication, and AppViews for presenting feeds. This architecture aims to improve scalability and user portability but currently relies heavily on Bluesky PBC for Relay operation, raising centralization concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Atproto">Atproto</a></li>
<li><a href="https://en.wikipedia.org/wiki/ActivityPub">ActivityPub</a></li>
<li><a href="https://github.com/bluesky-social/atproto">GitHub - bluesky-social/atproto: Social networking technology created ...</a></li>

</ul>
</details>

**Discussion**: Community comments on Hacker News were mixed; some praised the architectural clarity, while others criticized the article for downplaying Bluesky's current centralization, noting that Relays are costly and mostly run by Bluesky PBC, making the network less decentralized than Mastodon in practice.

**Tags**: `#ATProto`, `#ActivityPub`, `#decentralized protocols`, `#social media`, `#Bluesky`

---

<a id="item-3"></a>
## [GPT-5.5 hallucinates 3x more than GLM-5.2, study claims](https://arrowtsx.dev/bigger-models/) ⭐️ 8.0/10

A blog post from ArrowTSX claims that GPT-5.5 hallucinates three times more often than the MIT-licensed GLM-5.2 model, based on an undisclosed evaluation benchmark. This claim challenges the prevailing assumption that larger models scale to fewer hallucinations, reigniting debate on model scaling trade-offs and the reliability of hallucination metrics in LLM evaluation. The blog post does not specify the benchmark used or provide raw numbers, and community comments note that hallucination rates are conditional on the model not knowing the answer, making direct comparison tricky.

hackernews · oshrimpton · Jun 19, 16:11 · [Discussion](https://news.ycombinator.com/item?id=48600167)

**Background**: Hallucination in large language models refers to the generation of plausible but false information. While newer models like GPT-5 and GLM-5.2 aim to reduce hallucinations, the relationship between model size and hallucination is not monotonic. GLM-5.2 is an open-source model from Z.ai, released under the MIT license, designed for agentic and long-horizon tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://ollama.com/library/glm-5.2">glm-5.2</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hallucination_(artificial_intelligence)">Hallucination (artificial intelligence) - Wikipedia</a></li>
<li><a href="https://z.ai/blog/glm-4.5">GLM-4.5: Reasoning, Coding, and Agentic Abililties</a></li>

</ul>
</details>

**Discussion**: Commenters largely disagree with the post's strong conclusion, arguing that bigger models typically hallucinate less and that the evaluation methodology may be flawed. Some suggest that reinforcement learning from verifiable rewards (RLVR) could effectively target hallucination, while others caution that hallucination rates depend heavily on task distribution.

**Tags**: `#AI`, `#LLM`, `#hallucination`, `#open-source`, `#model comparison`

---

<a id="item-4"></a>
## [Datasette Apps: Host custom HTML applications inside Datasette](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything) ⭐️ 8.0/10

Simon Willison launched the datasette-apps plugin, which allows users to host custom HTML and JavaScript applications inside Datasette with read-only and optionally write SQL access via stored queries. This plugin significantly extends Datasette's functionality by enabling the creation of sandboxed interactive web apps that can query and update databases securely, making Datasette a more powerful platform for data exploration and internal tools. Apps run in a sandboxed iframe with `allow-scripts allow-forms` and a CSP header that blocks outbound HTTP requests, preventing data exfiltration. Write access requires configuring stored queries.

rss · Simon Willison · Jun 18, 23:58

**Background**: Datasette is an open-source tool by Simon Willison for publishing SQLite databases as interactive websites with a JSON API. It supports plugins that extend its functionality. The datasette-apps plugin was inspired by Claude Artifacts and allows embedding custom apps directly within Datasette instances.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-apps/">Datasette Apps: Host custom HTML applications inside Datasette</a></li>
<li><a href="https://pypi.org/project/datasette-apps/">Create apps that live inside Datasette</a></li>
<li><a href="https://github.com/datasette/datasette-apps">GitHub - datasette / datasette -apps: Apps that live inside Datasette</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#plugin`, `#sql`, `#web apps`, `#sandbox`

---

<a id="item-5"></a>
## [Time Series Needs Dynamical Systems Perspective](https://www.reddit.com/r/MachineLearning/comments/1uark0u/time_series_modeling_needs_a_dynamical_systems/) ⭐️ 8.0/10

A position paper presented at ICML 2026 argues that time series modeling should adopt a dynamical systems perspective, specifically through dynamical systems reconstruction (DSR), to achieve true out-of-domain generalization and long-term forecasting. The paper critiques current transformer-based approaches and advocates for modern RNNs with training techniques like generalized teacher forcing. This perspective shift could fundamentally improve time series models' ability to generalize to unseen regimes and forecast long-term behavior, addressing key limitations in domains like climate modeling, finance, and neuroscience. It challenges the dominant transformer paradigm and proposes training on simulated dynamical systems for more natural priors. The paper suggests five concrete directions: focus on DSR-specific training (e.g., generalized teacher forcing), pretrain on dynamical system simulations, move from transformers to modern RNNs, address topological shifts (bifurcations), and leverage universal DS properties (attractors, bifurcations) for mechanistic understanding. The authors also provide a comparison of custom-trained and foundation models for short- and long-term forecasting.

reddit · r/MachineLearning · /u/DangerousFunny1371 · Jun 20, 08:47

**Background**: Dynamical systems theory models how systems evolve over time using mathematical equations, often involving concepts like attractors and bifurcations. In time series analysis, most natural and engineered signals originate from such systems, yet current machine learning approaches often treat them as pure pattern recognition tasks without leveraging this underlying structure. Dynamical systems reconstruction (DSR) aims to infer the governing rules from observed data, which can enable out-of-domain generalization by capturing the system's intrinsic dynamics.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2306.04406">[2306.04406] Generalized Teacher Forcing for Learning Chaotic Dynamics</a></li>

</ul>
</details>

**Tags**: `#time series`, `#dynamical systems`, `#machine learning`, `#forecasting`, `#generalization`

---

<a id="item-6"></a>
## [Open Handbook on LLM Inference at Scale Released](https://www.reddit.com/r/MachineLearning/comments/1uavduv/an_open_handbook_on_llm_inference_at_scale_gpu/) ⭐️ 8.0/10

An open, in-progress handbook covering LLM inference internals including GPU execution, memory hierarchy, batching, and production frameworks like vLLM and TensorRT-LLM has been released on GitHub. This handbook fills a practical gap by providing a comprehensive, community-driven resource for understanding and optimizing LLM inference, which is crucial for deploying efficient AI systems. The handbook includes mermaid diagrams for architecture visualization and focuses on why GPUs sit idle during inference, memory bottleneck analysis, and real bottlenecks. It is still growing and welcomes feedback via issues and PRs.

reddit · r/MachineLearning · /u/YouFirst295 · Jun 20, 12:27

**Background**: LLM inference at scale involves challenges like the key-value (KV) cache, which stores intermediate states to accelerate text generation. Frameworks such as vLLM (using PagedAttention) and TensorRT-LLM optimize memory and throughput. Understanding GPU internals and memory hierarchy is essential for performance.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/vllm-project/vllm">GitHub - vllm-project/vllm: A high-throughput and memory-efficient inference and serving engine for LLMs · GitHub</a></li>
<li><a href="https://github.com/NVIDIA/TensorRT-LLM">GitHub - NVIDIA/TensorRT-LLM: TensorRT LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and supports state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs. TensorRT LLM also contains components to create Python and C++ runtimes that orchestrate the inference execution in a performant way. · GitHub</a></li>
<li><a href="https://arxiv.org/pdf/2510.09665">LMCache: An Efficient KV Cache Layer for Enterprise-Scale LLM ...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#GPU`, `#inference`, `#performance`, `#systems`

---

<a id="item-7"></a>
## [Safe GPU Inference in Rust with cuTile, Competitive with vLLM](https://www.reddit.com/r/MachineLearning/comments/1u9j7md/fearless_concurrency_on_the_gpu_safe_gpu/) ⭐️ 8.0/10

Researchers released cuTile Rust, a tile-based GPU programming library that uses Rust's ownership model to guarantee memory safety and data-race freedom at compile time, and built Grout, a Qwen3 inference engine that achieves 171 tok/s on RTX 5090 and 82 tok/s on B200, competitive with vLLM and SGLang. This work addresses the growing trust bottleneck in GPU code, especially with AI-generated kernels, by providing compiler-verified safety without sacrificing performance. It could pave the way for more reliable GPU programming and safe deployment of machine learning models. Grout currently supports only batch-1 inference for a limited set of models and is NVIDIA-only, lowering to CUDA Tile IR. While many kernels still use unsafe Rust, they can be migrated to safe variants; the safe GEMM is within 0.3% of hand-written low-level code, and element-wise operations reach ~7 TB/s.

reddit · r/MachineLearning · /u/Exciting_Suspect9088 · Jun 18, 21:36

**Background**: Traditional GPU programming in CUDA C/C++ lacks memory safety guarantees, making data-race bugs common. Rust's ownership system enables compiler-verified safety in concurrent code. CUDA Tile IR is a new virtual instruction set introduced by NVIDIA for tile-based computing. vLLM and SGLang are popular high-performance inference engines for LLMs.

<details><summary>References</summary>
<ul>
<li><a href="https://nvlabs.github.io/cutile-rs/">cuTile Rust — cuTile Rust</a></li>
<li><a href="https://github.com/nvlabs/cutile-rs">GitHub - NVlabs/ cutile -rs: cuTile Rust provides a safe, tile-based...</a></li>
<li><a href="https://github.com/huggingface/grout">GitHub - huggingface/grout: Testbed for LLM inference with cutile-rs. · GitHub</a></li>

</ul>
</details>

**Tags**: `#Rust`, `#GPU programming`, `#memory safety`, `#machine learning inference`, `#concurrent computing`

---

<a id="item-8"></a>
## [Storing a Website in a Favicon via Steganography](https://www.timwehrle.de/blog/i-stored-a-website-in-a-favicon/) ⭐️ 7.0/10

A developer demonstrated a technique to embed an entire website's HTML content into a favicon image file using steganography, and retrieve it with a small bootstrap loader script. This showcases creative use of browser constraints and steganography for data embedding, but practical applications are limited due to size constraints and the need for a bootstrap loader. It also raises privacy and fingerprinting concerns discussed in the community. The technique embeds data in the least significant bits of pixel values, similar to classic image steganography. The favicon must be a PNG or similar raster format; SVG favicons offer alternative direct embedding approaches.

hackernews · theanonymousone · Jun 20, 05:33 · [Discussion](https://news.ycombinator.com/item?id=48606619)

**Background**: Steganography is the practice of hiding secret data within ordinary files, such as images, to avoid detection. In image steganography, data is often concealed by modifying the least significant bits of pixel colors, which is imperceptible to the human eye. This technique leverages the favicon, a small icon displayed in browser tabs, which is typically a raster image like PNG.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Steganography">Steganography - Wikipedia</a></li>
<li><a href="https://www.kaspersky.com/resource-center/definitions/what-is-steganography">What Is Steganography & How Does It Work?</a></li>

</ul>
</details>

**Discussion**: Commenters suggested alternatives: using SVG favicons to directly embed markup, employing HTML/PNG polyglots for a single-file solution, or abusing the favicon cache for cross-domain tracking. Some noted that PNG comment chunks could store data without steganography, making the approach less novel.

**Tags**: `#favicon`, `#steganography`, `#web development`, `#hacks`

---

<a id="item-9"></a>
## [Exploring Colors Beyond Screen Gamuts](https://moultano.wordpress.com/2026/06/19/where-to-find-the-colors-your-screen-cant-show-you/) ⭐️ 7.0/10

The article explores colors that fall outside the sRGB color gamut, highlighting where these colors can be found in nature and the limitations of typical displays. This matters because it challenges our reliance on sRGB as a standard, revealing that many vibrant colors we see in real life cannot be reproduced on screens, affecting fields like digital art, photography, and display technology. The article uses the CIE 1931 chromaticity diagram to illustrate color gamut limits, but community commenters note that the diagram overemphasizes some blue-green colors while underrepresenting the missing saturated orange/red/purple colors.

hackernews · moultano · Jun 20, 03:36 · [Discussion](https://news.ycombinator.com/item?id=48606140)

**Background**: sRGB is the standard color space for web and monitors, but it cannot reproduce all colors visible to the human eye. The CIE 1931 chromaticity diagram maps all colors perceivable by a standard observer, but actual displays only cover a subset (gamut) of this diagram. This article explains where outside that gamut vibrant colors like those in flowers and sunsets lie.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/SRGB_color_space">SRGB color space</a></li>
<li><a href="https://en.wikipedia.org/wiki/Color_gamut">Color gamut</a></li>
<li><a href="https://en.wikipedia.org/wiki/Chromaticity_diagram">Chromaticity diagram</a></li>

</ul>
</details>

**Discussion**: Commenters appreciated the article's depth and visuals. Adrian_b corrected that the CIE 1931 diagram overemphasizes blue-green colors while the real deficiency of sRGB is in orange/red/purple. Divvsaxena reflected on how much time is spent looking at screens missing these colors. Krick enjoyed the article and noted the Jurassic Park reference.

**Tags**: `#color science`, `#display technology`, `#sRGB`, `#chromaticity`, `#human vision`

---

<a id="item-10"></a>
## [DVD-JEPA: open-source reproducible JEPA world model](https://www.reddit.com/r/MachineLearning/comments/1uatlzx/dvdjepa_an_opensource_fullyreproducible_jepa/) ⭐️ 7.0/10

DVD-JEPA is a minimal, fully-reproducible implementation of the Joint-Embedding Predictive Architecture (JEPA) that learns a world model by predicting latent representations instead of pixels, demonstrated on a bouncing DVD logo in a 16x16 grid. This work provides a clean, accessible demonstration of JEPA, the architecture behind Meta's I-JEPA and V-JEPA, making it easier for researchers and developers to understand and build upon world model research without the complexity of large-scale systems. The model consists of a context encoder, an EMA target encoder, and a latent predictor trained in a 32-dimensional representation space without labels or a decoder. A linear probe can recover the logo's exact (x,y) position to within 0.73 pixels, and the system can 'dream' future frames for about 20 steps before latent drift occurs.

reddit · r/MachineLearning · /u/NielsRogge · Jun 20, 10:52

**Background**: Joint-Embedding Predictive Architecture (JEPA) is a self-supervised learning framework introduced by Yann LeCun in 2022 that predicts representations (embeddings) of future inputs rather than predicting raw pixels. This avoids the difficulty of generating high-dimensional, uncertain pixel values and focuses on learning abstract features. DVD-JEPA is a minimal implementation in a toy domain to illustrate the concept.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@tahirbalarabe2/what-is-jepa-085ca776013a">What is JEPA ? Joint Embedding Predictive Architecture ... | Medium</a></li>
<li><a href="https://huggingface.co/learn/computer-vision-course/unit13/i-jepa">Image-based Joint - Embedding Predictive Architecture (I- JEPA )...</a></li>

</ul>
</details>

**Tags**: `#world model`, `#JEPA`, `#self-supervised learning`, `#video prediction`, `#representation learning`

---

<a id="item-11"></a>
## [Global PM2.5 Forecaster Solves Variance Trap](https://www.reddit.com/r/MachineLearning/comments/1uar4vc/built_a_global_aq_pm25_forecaster_ml_model_p/) ⭐️ 7.0/10

A machine learning practitioner built a global PM2.5 forecasting pipeline and solved the variance trap by using a horizon-aligned architecture with autoregressive lags and a volatility matrix, achieving MASE below 1.0 even for chaotic regions like India. This approach offers a practical solution to a common time series forecasting problem—the variance trap—improving forecast accuracy in high-volatility environments. It demonstrates how careful feature engineering and horizon decoupling can make gradient boosting models outperform naive baselines. The pipeline uses 1.6 million rows of OpenAQ and NASA weather data for US, UK, India, and Australia. The solution decouples forecast horizons (h=1,7,14,30) and injects a 3-day rolling volatility matrix to prevent data leakage, achieving 57% predictive accuracy at a 30-day horizon.

reddit · r/MachineLearning · /u/Divyanshailani · Jun 20, 08:20

**Background**: The variance trap in time series forecasting occurs when a model performs worse than a simple carryover forecast in high-volatility environments because it fails to capture sudden momentum shifts. MASE (Mean Absolute Scaled Error) is a metric that compares forecast accuracy to a naive benchmark; values above 1 indicate the model is worse than naive. The horizon-aligned architecture separates forecasts for each time horizon to avoid error compounding.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bias–variance_tradeoff">Bias–variance tradeoff - Wikipedia</a></li>
<li><a href="https://www.nilus.com/post/the-variance-trap-why-static-models-fail-in-a-behavioral-world-and-how-agents-fix-it">Beyond the Variance Trap: Using Agentic AI for Treasury & Cash Forecasting</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#time series forecasting`, `#air quality`, `#gradient boosting`

---

<a id="item-12"></a>
## [Mini torch.compile in 500 lines explains operator fusion speedups](https://www.reddit.com/r/MachineLearning/comments/1ua2hwj/how_does_torchcompile_achieve_massive_speedups/) ⭐️ 7.0/10

A developer created a minimal implementation of torch.compile in roughly 500 lines of Python, demonstrating how operator fusion achieves massive speedups over optimized NumPy operations. The project is open-sourced on GitHub with an accompanying notebook. This educational deep-dive demystifies one of PyTorch's most impactful optimizations, making it accessible to a broader audience. Understanding operator fusion is key for anyone building or optimizing deep learning models, as it directly affects training and inference performance. The implementation, called 'tinytorchcompile', focuses on operator fusion—combining multiple sequential operations into a single kernel to reduce memory traffic and launch overhead. The repository includes a notebook that walks through the core ideas step by step.

reddit · r/MachineLearning · /u/Other-Eye-8152 · Jun 19, 13:47

**Background**: Operator fusion is a key optimization in many deep learning frameworks (e.g., TensorFlow, TVM) where adjacent operations are merged into a single kernel to minimize data movement and kernel launch latency. torch.compile achieves this by tracing PyTorch programs and generating fused kernels via a compiler stack that includes TorchInductor. This allows it to sometimes outperform hand-optimized NumPy functions that rely on separate calls for each operation.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.pytorch.org/tutorials/intermediate/torch_compile_tutorial.html">Introduction to torch . compile — PyTorch Tutorials 2.12.0+cu130...</a></li>
<li><a href="https://dl.acm.org/doi/10.1145/3520142">Optimus: An Operator Fusion Framework for Deep Neural Networks | ACM Transactions on Embedded Computing Systems</a></li>
<li><a href="https://arxiv.org/abs/2108.13342">[2108.13342] DNNFusion: Accelerating Deep Neural Networks Execution with Advanced Operator Fusion</a></li>

</ul>
</details>

**Tags**: `#torch.compile`, `#operator fusion`, `#PyTorch`, `#deep learning optimization`, `#educational`

---

<a id="item-13"></a>
## [CSS Quake: A Browser-Based Recreation](https://cssquake.com/) ⭐️ 6.0/10

A developer has created CSSQuake, a fully playable recreation of the classic game Quake using only CSS and HTML, with no JavaScript required for the rendering logic. This demo showcases the remarkable capabilities of CSS 3D transforms and animations, blurring the line between web styling and game development. However, its performance limitations highlight the current boundaries of CSS as a game engine. CSSQuake uses CSS 3D transforms to render a first-person 3D environment, but community comments note that the game logic (e.g., button activation) differs from the original Quake, suggesting it is a recreation rather than a port. The project requires JavaScript for initial loading, contradicting the claim of being pure CSS.

hackernews · msalsas · Jun 20, 10:49 · [Discussion](https://news.ycombinator.com/item?id=48608223)

**Background**: CSS 3D transforms allow web developers to apply 3D transformations like rotation and translation to HTML elements, enabling the creation of simple 3D scenes without JavaScript. This project pushes that concept to its extreme, implementing a full first-person shooter engine using only CSS—a feat previously thought impossible without heavy JavaScript use.

<details><summary>References</summary>
<ul>
<li><a href="https://www.w3schools.com/css/css3_3dtransforms.asp">CSS 3D Transforms</a></li>
<li><a href="https://3dtransforms.desandro.com/">Intro to CSS 3D transforms</a></li>
<li><a href="https://github.com/brookjordan/css-game-engine">GitHub - brookjordan/ css - game - engine : A web-based game engine ...</a></li>

</ul>
</details>

**Discussion**: The community comments are generally positive, with users praising the achievement as 'awesome' and 'genuinely smile-inducing'. However, there are notable criticisms: one user points out that it runs slower on a modern Mac M1 Pro than on a 90s Pentium-133, and another notes discrepancies in game behavior compared to the original Quake. A commenter also observes that JavaScript is still needed, challenging the 'CSS-only' claim.

**Tags**: `#CSS`, `#gaming`, `#demo`, `#recreation`, `#browser`

---

<a id="item-14"></a>
## [Datasette-acl 0.6a0 expands to general resource sharing](https://simonwillison.net/2026/Jun/18/datasette-acl/#atom-everything) ⭐️ 6.0/10

The datasette-acl plugin version 0.6a0 has been released, expanding from table-only permissions to a general resource-sharing system for multi-user Datasette instances. This release lays the groundwork for finely grained access control across all resources in Datasette, enabling more secure and flexible multi-user deployments. The plugin currently only supports table permissions, but this release introduces a framework for resource classes and actions, allowing plugin authors to define custom permissions. Permissions are stored in the internal database, requiring the --internal flag to persist across restarts.

rss · Simon Willison · Jun 18, 19:03

**Background**: Datasette is an open-source tool for exploring and publishing data as interactive websites and APIs. The datasette-acl plugin provides advanced permission management for Datasette instances, previously limited to table-level access control. This release starts evolving it into a general resource-sharing system, where other plugins can define their own resources and actions.

<details><summary>References</summary>
<ul>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-acl/">Release: datasette-acl 0.6a0</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#permissions`, `#access-control`, `#plugin`, `#open-source`

---