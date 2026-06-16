---
layout: default
title: "Horizon Summary: 2026-06-16 (EN)"
date: 2026-06-16
lang: en
---

> From 38 items, 22 important content pieces were selected

---

1. [Backdoor in Fake LinkedIn Job Offer via npm](#item-1) ⭐️ 9.0/10
2. [Fox Acquires Roku in Major Streaming Deal](#item-2) ⭐️ 9.0/10
3. [Salesforce to Acquire Fin (formerly Intercom) for $3.6B](#item-3) ⭐️ 9.0/10
4. [Banned Book Library Inside a Wi-Fi Smart Light Bulb](#item-4) ⭐️ 8.0/10
5. [Iroh 1.0 Released: P2P Connectivity Library for Apps](#item-5) ⭐️ 8.0/10
6. [HN users share local model setups for coding](#item-6) ⭐️ 8.0/10
7. [Hetzner Announces Up to 3x Price Hike for Cloud Servers](#item-7) ⭐️ 8.0/10
8. [Why AI won't replace software engineers, argue experts](#item-8) ⭐️ 8.0/10
9. [LLMs show model-specific name preferences, study finds](#item-9) ⭐️ 8.0/10
10. [New Framework Claims to Surpass Backpropagation for Neocortical Learning](#item-10) ⭐️ 8.0/10
11. [In-Depth Analysis of Commander Keen's Pioneering Engine](#item-11) ⭐️ 7.0/10
12. [TimescaleDB Compression: Columnar Storage & Query Trade-offs](#item-12) ⭐️ 7.0/10
13. [Cleo: 2B Model Unifies Text-to-SQL Training, Eval, and Inference](#item-13) ⭐️ 7.0/10
14. [What's the biggest bottleneck in embedded ML with sensor data?](#item-14) ⭐️ 7.0/10
15. [PrintGuard 2.0: Tiny ML for 3D Printer Failure Detection](#item-15) ⭐️ 7.0/10
16. [TinyWind: Pixel pirate sailing game with real wind physics?](#item-16) ⭐️ 6.0/10
17. [A Love for Computers Amid Industry Discontent](#item-17) ⭐️ 6.0/10
18. [Homelab AI Dev Platform with OpenCode and Forgejo](#item-18) ⭐️ 6.0/10
19. [US Battery Manufacturing Output Hits Record Highs](#item-19) ⭐️ 6.0/10
20. [Personality Clashes Took Anthropic's Models Offline](#item-20) ⭐️ 6.0/10
21. [Open training frameworks beyond open weights needed for ML research](#item-21) ⭐️ 6.0/10
22. [Quant Firms Dominate ICML 2026 Diamond Sponsorship](#item-22) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [Backdoor in Fake LinkedIn Job Offer via npm](https://roman.pt/posts/linkedin-backdoor/) ⭐️ 9.0/10

A job applicant discovered a backdoor hidden in a GitHub repository sent by a recruiter as part of a fake job interview process; the backdoor executed when `npm install` ran the `prepare` script. This incident highlights a new social engineering attack vector targeting developers through fake job offers, with potential for large-scale supply chain compromise if widely deployed. The backdoor was buried in commented-out test code in a Node.js repository; the `npm prepare` script automatically runs after `npm install`, allowing the backdoor to execute without manual intervention.

hackernews · lwhsiao · Jun 15, 20:00 · [Discussion](https://news.ycombinator.com/item?id=48546294)

**Background**: npm is the default package manager for Node.js; packages can define lifecycle scripts, such as `prepare`, which run automatically on install. Supply chain attacks targeting npm have become increasingly common, with attackers injecting malicious code into popular packages to compromise downstream users.

<details><summary>References</summary>
<ul>
<li><a href="https://www.bleepingcomputer.com/news/security/somebody-tried-to-hide-a-backdoor-in-a-popular-javascript-npm-package/">Somebody Tried to Hide a Backdoor in a Popular JavaScript npm ...</a></li>
<li><a href="https://underdefense.com/blog/npm-supply-chain-attack/">Largest NPM Supply Chain Attack : Billions of Downloads</a></li>

</ul>
</details>

**Discussion**: Comments express concern over the sophistication of recruitment scams, with one user noting the attack is uncomfortably close to normal interview tasks. Another user calls for a centralized system to report cybercrime, while others criticize LinkedIn's role in the job market.

**Tags**: `#security`, `#social engineering`, `#npm supply chain`, `#recruitment scams`, `#backdoor`

---

<a id="item-2"></a>
## [Fox Acquires Roku in Major Streaming Deal](https://www.wsj.com/business/deals/fox-roku-deal-f6e564f9) ⭐️ 9.0/10

Fox Corporation is reportedly acquiring Roku, a leading streaming hardware and platform provider, according to a Wall Street Journal report. This acquisition gives Fox direct control over a streaming platform used in tens of millions of U.S. households, potentially reshaping competition and user experience in the streaming market. The deal would combine Fox's content library with Roku's operating system, raising concerns about platform neutrality and increased advertising integration.

hackernews · thm · Jun 15, 12:50 · [Discussion](https://news.ycombinator.com/item?id=48540499)

**Background**: Roku is a popular streaming device and smart TV platform known for its hardware-agnostic approach, but it has increasingly added ads and content partnerships. Fox is a major media conglomerate owning news, sports, and entertainment assets, and acquiring Roku would give it direct access to consumers' TV screens.

**Discussion**: Community sentiment is largely pessimistic, with users fearing Fox will compromise Roku's neutral platform by prioritizing its own content and increasing ads. Some users recommend alternatives like NVIDIA Shield with custom launchers to avoid ad-laden interfaces.

**Tags**: `#acquisition`, `#streaming`, `#media`, `#antitrust`, `#hardware`

---

<a id="item-3"></a>
## [Salesforce to Acquire Fin (formerly Intercom) for $3.6B](https://www.salesforce.com/news/press-releases/2026/06/15/salesforce-signs-definitive-agreement-to-acquire-fin/?bc=HL) ⭐️ 9.0/10

Salesforce has signed a definitive agreement to acquire Fin, a customer support AI startup formerly known as Intercom, for $3.6 billion. This acquisition intensifies competition in the AI customer support agent space, particularly against Sierra (founded by ex-Salesforce co-CEO Bret Taylor), and prevents independent AI agents from becoming a control point outside CRM ecosystems. Fin serves over 12,000 brands and is considered a top-performing Customer Agent; the deal comes shortly after Fin's rebrand from Intercom about a month ago. Salesforce is paying $3.6B in cash.

hackernews · colesantiago · Jun 15, 12:08 · [Discussion](https://news.ycombinator.com/item?id=48540126)

**Background**: AI agents for customer support are rapidly evolving, with startups like Sierra and Decagon gaining high valuations. Salesforce, a leading CRM provider, aims to embed advanced AI agents directly into its platform to enhance customer service. Fin's technology can resolve complex queries across multiple channels, making it a valuable asset.

<details><summary>References</summary>
<ul>
<li><a href="https://www.intercom.com/help/en/articles/7120684-fin-ai-agent-explained">Fin AI Agent explained - Intercom Help</a></li>
<li><a href="https://fin.ai/">Fin. The highest performing Customer Agent</a></li>

</ul>
</details>

**Discussion**: Community comments are mixed: some praise well-implemented AI support (e.g., Starlink example), while others express skepticism about AI quality and note that Fin's sale may be a timely exit before AI disrupts the market. There is also discussion about competition with Sierra and practical implications for businesses.

**Tags**: `#acquisition`, `#AI`, `#customer support`, `#CRM`, `#Salesforce`

---

<a id="item-4"></a>
## [Banned Book Library Inside a Wi-Fi Smart Light Bulb](https://www.richardosgood.com/posts/banned-book-library/) ⭐️ 8.0/10

A developer created a custom firmware for an ESP8266-based Wi-Fi smart light bulb that hosts a library of banned books, accessible via the bulb's Wi-Fi network. This project demonstrates a novel method of distributing censored information using everyday IoT devices, potentially providing a resilient platform for free speech in regions with censorship. The bulb uses the ESP8266 microcontroller with LittleFS filesystem to store the books, and runs a simple web server that serves the files when users connect to the bulb's access point. Storage is limited to the bulb's flash memory, typically a few megabytes.

hackernews · sohkamyung · Jun 15, 22:37 · [Discussion](https://news.ycombinator.com/item?id=48547985)

**Background**: Smart light bulbs often contain Wi-Fi microcontrollers like the ESP8266, which can be reprogrammed with custom firmware. Projects like Tasmota and AiLight have shown how to flash these bulbs to run alternate software. Hosting files on ESP8266 is possible using SPIFFS or LittleFS filesystem uploaders, allowing the device to serve web pages and files.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/stelgenhof/AiLight">GitHub - stelgenhof/AiLight: AiLight is a custom firmware for the esp8266 based Ai-Thinker (or equivalent) RGBW WiFi light bulbs · GitHub</a></li>
<li><a href="https://randomnerdtutorials.com/install-esp8266-filesystem-uploader-arduino-ide/">Install ESP8266 Filesystem Uploader in Arduino IDE</a></li>
<li><a href="https://hackaday.com/2020/02/11/custom-firmware-for-cheap-smart-bulbs-is-a-cinch-to-tinker-with/">Custom Firmware For Cheap Smart Bulbs Is A Cinch To Tinker With | Hackaday</a></li>

</ul>
</details>

**Discussion**: Commenters praised the project's creativity and its relevance to freedom of speech. Some referenced similar projects like PirateBox and Meshtastic, while others discussed the political context of book banning. One commenter noted potential misuse if user uploads were allowed.

**Tags**: `#censorship`, `#embedded systems`, `#free speech`, `#hacker culture`

---

<a id="item-5"></a>
## [Iroh 1.0 Released: P2P Connectivity Library for Apps](https://www.iroh.computer/blog/v1) ⭐️ 8.0/10

The Iroh team announced the release of version 1.0, a stable library that provides peer-to-peer connectivity for applications, abstracting away networking complexities like NAT traversal and encryption. This release simplifies building decentralized applications by offering a production-ready P2P networking layer, reducing the need for developers to manage infrastructure like TURN servers or certificates. Iroh uses QUIC for transport and supports IPv4, IPv6, and relay out of the box, with an extensible transport interface. The library is implemented in Rust.

hackernews · chadfowler · Jun 15, 15:13 · [Discussion](https://news.ycombinator.com/item?id=48542480)

**Background**: Peer-to-peer (P2P) networking allows direct connections between devices without a central server. However, NATs and firewalls often prevent these connections, requiring techniques like STUN/TURN or relay servers. Iroh aims to handle these challenges automatically, similar to how Tailscale simplifies VPNs but at the application layer.

<details><summary>References</summary>
<ul>
<li><a href="https://www.iroh.computer/">iroh</a></li>
<li><a href="https://blog.lambdaclass.com/the-wisdom-of-iroh/">The Wisdom of Iroh - LambdaClass Blog</a></li>

</ul>
</details>

**Discussion**: The Hacker News discussion highlights that Iroh is like 'Tailscale at the application layer,' and developers appreciate the ability to implement custom transports beyond the default IPv4/IPv6/relay. Some users questioned why not just use Tailscale, but the explanation about app integration and account requirements satisfied most. A few commenters desired clearer documentation on key concepts like 'dial keys.'

**Tags**: `#peer-to-peer`, `#networking`, `#release`, `#rust`, `#library`

---

<a id="item-6"></a>
## [HN users share local model setups for coding](https://news.ycombinator.com/item?id=48542100) ⭐️ 8.0/10

Many Hacker News users report successfully replacing cloud-based Claude or GPT with local models like Qwen3.6-35B and Gemma-4-26B for daily coding tasks, achieving speeds of 150+ tokens per second on consumer hardware. This shift demonstrates that local models are now viable for production coding, offering data privacy, zero subscription costs, and offline capability, potentially reducing dependence on expensive cloud APIs. Users highlight setups like llama.cpp with Qwen3.6-35B (MTP) on a single RTX 3090, and Pi coding harness with containerized sandboxing for privacy. Performance is roughly comparable to edge models from 8-12 months ago, with some fallback to cloud for complex tasks.

hackernews · cloudking · Jun 15, 14:46

**Background**: Local LLMs run entirely on a user's own hardware, eliminating data sent to cloud providers. Tools like llama.cpp and Ollama enable efficient inference on consumer GPUs. Token per second (tok/s) is a key metric for evaluating speed; 60+ tok/s is considered good for interactive use. This trend is driven by advances in model quantization and specialized architectures, making high-quality coding assistants accessible without internet or subscription fees.

<details><summary>References</summary>
<ul>
<li><a href="https://dev.to/alanwest/how-to-set-up-a-local-ai-coding-assistant-that-actually-works-43j8">How to Set Up a Local AI Coding Assistant That Actually Works - DEV Community</a></li>
<li><a href="https://medium.com/@walterdeane/running-a-local-llm-for-code-assistance-dea64748041a">Running a Local LLM for Code Assistance | by Walter Deane | Medium</a></li>
<li><a href="https://mljourney.com/how-many-tokens-per-second-is-good-for-local-llms/">How Many Tokens Per Second Is ‘Good’ for Local LLMs?</a></li>

</ul>
</details>

**Discussion**: The overall sentiment is positive, with many users reporting satisfactory results for daily coding. Some note that local models are not as smart as Claude or Codex but 'good enough' for most tasks, while a few argue that the opportunity cost of not using the latest cloud models is too high. Users share detailed hardware setups and performance numbers, showing a practical community interest in self-hosted AI.

**Tags**: `#local LLMs`, `#coding assistant`, `#AI`, `#open-source`, `#privacy`

---

<a id="item-7"></a>
## [Hetzner Announces Up to 3x Price Hike for Cloud Servers](https://docs.hetzner.com/general/infrastructure-and-availability/price-adjustment/#cloud-servers) ⭐️ 8.0/10

Hetzner, a major European cloud provider, has announced significant price increases for its cloud servers, with some instances seeing up to a 3x rise, citing hardware scarcity and AI-driven demand. This price adjustment reflects broader industry trends where AI demand is driving up hardware costs, impacting businesses that rely on affordable cloud infrastructure and potentially shifting the competitive landscape. The price changes apply to both new and existing cloud server products, with specific increases varying by instance type; the company also announced a standardization of its server product line.

hackernews · tuhtah · Jun 15, 13:19 · [Discussion](https://news.ycombinator.com/item?id=48540844)

**Background**: Hetzner is known for offering low-cost cloud and dedicated server hosting, popular among developers and small businesses. The price hike, unusual for the company, signals how AI boom is straining hardware supply chains, affecting even previously low-cost providers.

**Discussion**: Community comments express concern over the drastic price increase, with some questioning the justification for a 3x jump and others linking it to broader issues like job displacement and wealth inequality driven by the AI boom.

**Tags**: `#cloud hosting`, `#pricing`, `#hardware costs`, `#AI boom`

---

<a id="item-8"></a>
## [Why AI won't replace software engineers, argue experts](https://simonwillison.net/2026/Jun/14/why-ai-hasnt-replaced-software-engineers/#atom-everything) ⭐️ 8.0/10

Arvind Narayanan and Sayash Kapoor published an essay arguing that AI will not cause mass unemployment among software engineers, citing data from WARN Act filings in New York showing no AI-related layoffs. This counters the prevailing narrative that AI will soon automate programming jobs, providing evidence-based reassurance to the software engineering community and suggesting other professions may also be cushioned. The essay identifies three real bottlenecks in software engineering: deciding what to build, verifying deliverables, and deep human understanding of codebase, business, and environment. AI can assist but cannot replace these human-centered tasks.

rss · Simon Willison · Jun 14, 23:54

**Background**: The WARN Act requires companies to notify workers of mass layoffs. In March 2025, New York added an AI disclosure checkbox; in the first full year, no company checked it. This suggests AI has not yet caused significant job displacement. The essay argues that despite AI's coding capabilities, software engineering involves complex human judgment and context understanding.

**Tags**: `#AI`, `#software engineering`, `#job displacement`, `#labor market`, `#technology`

---

<a id="item-9"></a>
## [LLMs show model-specific name preferences, study finds](https://www.reddit.com/r/MachineLearning/comments/1u6mn3q/ai_language_models_have_favorite_names_and_we/) ⭐️ 8.0/10

Researchers discovered that large language models consistently generate specific fictional names like Elena Vasquez and Marcus Chen, forming correlated ensembles that can identify the model used. This finding offers a new method for detecting AI-generated content and tracing model provenance, with implications for content moderation and forensic analysis. The name pairs and trios appear consistently across hundreds of independently generated documents, with co-occurrence rates far exceeding chance. The paper also documents a suppression curve where newer model versions actively mitigate these priors.

reddit · r/MachineLearning · /u/CebulkaZapiekana · Jun 15, 17:07

**Background**: Large language models are trained on vast text corpora, leading to statistical priors over common names. This research shows that these priors are not independent but form correlated ensembles unique to each model family and version. The finding emerged from a model diffing method called Contrastive Decoding Diffing (CDD).

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/2606.02184">[2606.02184] The Ghost Couple: Correlated LLM Name Priors and Their ...</a></li>
<li><a href="https://www.emergentmind.com/papers/2605.25902">CDD: Verbatim Content Recovery via Diffing</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#AI-generated content`, `#model bias`, `#machine learning`, `#name preferences`

---

<a id="item-10"></a>
## [New Framework Claims to Surpass Backpropagation for Neocortical Learning](https://www.reddit.com/r/MachineLearning/comments/1u6x8al/how_the_brains_learn_r/) ⭐️ 8.0/10

A paper published on arXiv (2606.08720) proposes an error-driven predictive learning framework using temporal derivatives and corticothalamic circuits, claiming to meet all criteria for a general-purpose learning algorithm and potentially outperforming backpropagation. If validated, this neuroscience-based algorithm could revolutionize machine learning by offering a biologically plausible and more efficient alternative to backpropagation, which has been a cornerstone of deep learning. The framework is implemented in the Axon neural simulation framework using spiking neurons and has been demonstrated to learn across a range of challenging cognitively motivated tasks, leveraging competitive kinase synaptic plasticity induction mechanisms.

reddit · r/MachineLearning · /u/Terminator857 · Jun 15, 23:39

**Background**: Backpropagation is the dominant learning algorithm in artificial neural networks but is considered biologically implausible due to its need for symmetric weights and non-local update rules. The neocortex is the brain region responsible for higher-order functions; its learning mechanisms involve complex circuits such as corticothalamic loops and molecular processes like kinase-mediated synaptic plasticity. This paper attempts to bridge the gap between neuroscience and machine learning by proposing a biologically plausible algorithm that matches backprop's capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Thalamo-cortico-thalamic_circuits">Thalamo-cortico-thalamic circuits - Wikipedia</a></li>
<li><a href="https://elifesciences.org/articles/37836">Competition for synaptic building blocks shapes synaptic plasticity | eLife</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#neuroscience`, `#learning algorithms`, `#backpropagation`

---

<a id="item-11"></a>
## [In-Depth Analysis of Commander Keen's Pioneering Engine](https://forgottenbytes.net/commander_keen.html) ⭐️ 7.0/10

A new 214-page white paper titled 'The Game Engine White Papers: Commander Keen' has been released, providing a comprehensive technical analysis of the game's engine, including its pioneering adaptive tile refresh scrolling technique. This document is valuable for retro computing and game development enthusiasts as it meticulously documents the innovative hardware tricks that allowed smooth scrolling on early 1990s PC hardware, influencing later games and developers. The white paper covers hardware, game assets, engine internals, and even the CGA version, and is available as a free high-resolution PDF with source code on GitHub.

hackernews · mfiguiere · Jun 15, 17:52 · [Discussion](https://news.ycombinator.com/item?id=48544781)

**Background**: In the early 1990s, PC graphics hardware was limited compared to dedicated consoles like the SNES. John Carmack developed adaptive tile refresh for Commander Keen, which used EGA hardware features to scroll the screen smoothly by only redrawing changed tiles, compensating for the PC's lack of hardware sprite support.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Adaptive_tile_refresh">Adaptive tile refresh - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Commander_Keen">Commander Keen - Wikipedia</a></li>
<li><a href="https://fabiensanglard.net/ega/">Commander Keen's Adaptive Tile Refresh</a></li>

</ul>
</details>

**Discussion**: Commenters praised the white paper and recommended related resources like the books 'Masters of Doom' and 'Cosmodoc'. They also noted the context of contemporary console hardware, such as the SNES's efficient sprite rendering compared to PCs at the time.

**Tags**: `#game engine`, `#retro gaming`, `#id Software`, `#Commander Keen`, `#technical analysis`

---

<a id="item-12"></a>
## [TimescaleDB Compression: Columnar Storage & Query Trade-offs](https://roszigit.com/en/blog/timescaledb-compression-hypercore) ⭐️ 7.0/10

The article provides a detailed analysis of TimescaleDB's compression mechanism, which converts row-based chunks into columnar format and applies type-specific algorithms like delta encoding, dictionary encoding, and run-length encoding to achieve up to 98% compression ratio. Effective compression reduces storage costs and can accelerate query performance for time-series workloads, which is critical for IoT, monitoring, and analytics applications. Understanding the trade-offs between compression ratio and query speed helps users optimize their database deployments. TimescaleDB uses columnar storage where each column is compressed independently with the most efficient algorithm for its data type. Query performance varies depending on the compression method; for example, dictionary encoding may slow reads due to decompression overhead, while techniques like min/max indexing and bloom filters can speed up filter rejection.

hackernews · lkanwoqwp · Jun 15, 17:29 · [Discussion](https://news.ycombinator.com/item?id=48544451)

**Background**: Time-series databases like TimescaleDB are designed for append-heavy workloads with high write throughput. Columnar storage groups similar data together, enabling better compression through techniques like run-length encoding and delta-of-delta encoding. TimescaleDB extends PostgreSQL with hypertables, which automatically partition data by time and transparently compress older chunks while leaving recent data in row format for fast writes.

<details><summary>References</summary>
<ul>
<li><a href="https://deepwiki.com/timescale/timescaledb/3.1-enabling-and-configuring-compression">Enabling and Configuring Compression | timescale/timescaledb ...</a></li>
<li><a href="https://github.com/timescale/timescaledb/blob/main/tsl/src/compression/README.md">timescaledb/tsl/src/compression/README.md at main - GitHub</a></li>
<li><a href="https://oneuptime.com/blog/post/2026-02-02-timescaledb-compression/view">How to Compress Data in TimescaleDB - oneuptime.com</a></li>

</ul>
</details>

**Discussion**: Commenters discussed trade-offs: gopalv emphasized that compression must be evaluated by its effect on query performance, not just storage savings. tudorg shared work on another PG extension (deltax) for time-series analytics. robocat criticized the use of 'up to' in the title as misleading, while blackoil noted that Facebook's Gorilla algorithm uses similar delta-of-delta encoding.

**Tags**: `#timescaledb`, `#compression`, `#time-series`, `#postgresql`, `#database`

---

<a id="item-13"></a>
## [Cleo: 2B Model Unifies Text-to-SQL Training, Eval, and Inference](https://www.reddit.com/r/MachineLearning/comments/1u6udpb/cleo_trying_to_fit_full_analyst_behavior_in_a_2b/) ⭐️ 7.0/10

Cleo is an open-source finetune of Qwen3.5-2B-Base that uses a unified harness for training, evaluation, and inference, incorporating live execution evidence to validate SQL queries. 这一方法表明，当训练和推理紧密集成时，小型模型（2B参数）可以有效地处理复杂的Text-to-SQL任务，为资源受限环境提供了实用解决方案。 Cleo co-designs the model contract, SQL safety layer, dialect handling, timeouts, and clarification behavior as a single system, and searches over candidate queries using live execution evidence rather than just model likelihood.

reddit · r/MachineLearning · /u/Dreeseaw · Jun 15, 21:43

**Background**: Text-to-SQL systems translate natural language questions into SQL queries to enable non-technical users to interact with databases. Traditionally, training, evaluation, and inference pipelines are separate, often leading to mismatches between training objectives and real-world execution. A unified harness like the one introduced in Cleo aims to bridge this gap by ensuring consistent behavior across all stages.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2410.06011v1">Large Language Model Enhanced Text-to-SQL Generation: A Survey</a></li>
<li><a href="https://github.com/EleutherAI/lm-evaluation-harness">Language Model Evaluation Harness - GitHub</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#text-to-sql`, `#NLP`, `#model finetuning`, `#open source`

---

<a id="item-14"></a>
## [What's the biggest bottleneck in embedded ML with sensor data?](https://www.reddit.com/r/MachineLearning/comments/1u6q97f/embeddededge_ml_folks_what_actually_eats_the_most/) ⭐️ 7.0/10

A Reddit user asks embedded/edge ML practitioners whether data acquisition, cleaning/labeling, model training, or deployment consumes the most time when working with time series sensor data, and seeks feedback on which of four proposed features would be most valuable. Understanding the primary bottleneck helps tool developers prioritize features that genuinely save time for the growing embedded ML community, particularly those working with sensor data on microcontrollers. The post mentions a project similar to Edge Impulse but hardware-agnostic, generative AI native, and focused on time series data. The four proposed features are automatic data quality checks, AI-assisted labeling for long recordings, enforcing data standards at collection, and reproducible/versioned pipelines.

reddit · r/MachineLearning · /u/No-Bug-4879 · Jun 15, 19:13

**Background**: Embedded machine learning (TinyML) involves deploying ML models on resource-constrained devices like microcontrollers. A common workflow includes data collection, labeling, model training, and optimization for deployment. For time series sensor data, cleaning and labeling are often cited as time-consuming bottlenecks, and platforms like Edge Impulse aim to streamline the process.

<details><summary>References</summary>
<ul>
<li><a href="https://www.edgeimpulse.com/">Edge Impulse - The Leading Edge AI Platform</a></li>
<li><a href="https://medium.com/@cknorow/best-labeling-software-for-time-series-sensor-data-86001ff0992b">Best Labeling Software for Time-Series Sensor Data</a></li>

</ul>
</details>

**Tags**: `#embedded ML`, `#edge ML`, `#time series`, `#sensor data`, `#machine learning workflow`

---

<a id="item-15"></a>
## [PrintGuard 2.0: Tiny ML for 3D Printer Failure Detection](https://www.reddit.com/r/MachineLearning/comments/1u6e9zc/printguard_20_shufflenetv2_fewshot_prototypical/) ⭐️ 7.0/10

PrintGuard 2.0 is a complete rewrite of the runtime, now exporting a ~5 MB TFLite model via LiteRT that runs unmodified on both CPython and in the browser via Pyodide, with per-printer sensitivity sliders. This demonstrates a practical deployment of few-shot learning on edge devices with a tiny model size and cross-platform support, making failure detection accessible to hobbyists and makers without specialized hardware. The model remains a ShuffleNetV2 encoder classified by nearest prototype, but the runtime now uses LiteRT for inference, a dynamic fairness-aware scheduler, and a platform abstraction layer that separates portable from non-portable code.

reddit · r/MachineLearning · /u/oliverbravery · Jun 15, 11:47

**Background**: PrintGuard is a few-shot FDM (fused deposition modeling) failure detector for 3D printers. It uses a ShuffleNetV2 backbone, an efficient CNN architecture, with a prototypical network classifier that learns from a few examples per class. TFLite (now rebranded as LiteRT) is Google's runtime for on-device machine learning, allowing models to run efficiently on CPUs without a GPU.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/abs/1807.11164">[1807.11164] ShuffleNet V2: Practical Guidelines for ... GitHub - megvii-model/ShuffleNet-Series ShuffleNet V2: Practical Guidelines for Efficient CNN ... qualcomm/Shufflenet-v2 · Hugging Face ShuffleNetV2 | megvii-model/ShuffleNet-Series | DeepWiki Shufflenet-v2 - Qualcomm AI Hub</a></li>
<li><a href="https://spotintelligence.com/2023/12/07/prototypical-networks/">Prototypical Networks Explained, Compared & How To Tutorial</a></li>
<li><a href="https://grokipedia.com/page/LiteRT">LiteRT</a></li>

</ul>
</details>

**Tags**: `#few-shot learning`, `#edge AI`, `#machine learning engineering`, `#3D printing`, `#TFLite`

---

<a id="item-16"></a>
## [TinyWind: Pixel pirate sailing game with real wind physics?](https://tinywind.io/) ⭐️ 6.0/10

TinyWind is a pixel-art pirate sailing game released on its website that claims to simulate real wind physics, but community comments from experienced sailors point out significant inaccuracies in the sailing mechanics. The game's high community engagement shows strong interest in sailing games, but the critical feedback highlights the difficulty of balancing realism with fun in physics-based games. Players noted that wind direction is unclear, sail angle seems irrelevant to wind side, and the ship can sail upwind unrealistically, missing key sailing mechanics like the dead angle on square-rigged ships.

hackernews · tinywind · Jun 15, 16:15 · [Discussion](https://news.ycombinator.com/item?id=48543475)

**Background**: Realistic wind physics in games require simulating forces on sails based on true and apparent wind, as well as points of sail. Simple implementations often use particle systems or basic force calculations, but accurately modeling upwind sailing and tacking involves complex aerodynamics. The community feedback suggests TinyWind uses a simplified model.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/advice/0/how-can-you-realistically-implement-wind-physics-game-jg7oe">How to Simulate Realistic Wind Physics in a Game</a></li>
<li><a href="https://en.wikipedia.org/wiki/Forces_on_sails">Forces on sails - Wikipedia</a></li>

</ul>
</details>

**Discussion**: The community discussion is largely constructive, with experienced sailors providing detailed feedback on physics inaccuracies while praising the game's concept. Some beginners found it a helpful learning tool, while others felt the AI enemies were too difficult. Overall sentiment is mixed but leans positive with strong calls for improvement.

**Tags**: `#gaming`, `#physics simulation`, `#sailing`, `#indie game`, `#Hacker News discussion`

---

<a id="item-17"></a>
## [A Love for Computers Amid Industry Discontent](https://michaelenger.com/blog/i-love-the-computer/) ⭐️ 6.0/10

A reflective blog post by Michael Enger explores the author's enduring love for computers contrasted with disillusionment toward the modern tech industry, sparking thoughtful community discussion on computing nostalgia, AI utility, and low-level programming. Although not breaking news, the essay resonates deeply with many developers, highlighting a widespread tension between the joy of computing and the pressures of the industry. This conversation reflects ongoing community sentiment about the value of AI tools and the importance of fundamental programming skills. The post scores 6.0/10 due to lack of new information, but high engagement and quality comments elevate its significance. Key commenters discuss AI as a legitimate tool, nostalgia for low-level programming like 6502 assembler, and concerns about gatekeeping in the tech community.

hackernews · speckx · Jun 15, 20:14 · [Discussion](https://news.ycombinator.com/item?id=48546441)

**Discussion**: Commenters generally agree on the love for computers but diverge on AI: some see it as snake oil, while others find it genuinely useful for learning new fields. There is also a critique that the article's sentiment gatekeeps who gets to love 'the computer,' as noted by tptacek. Overall, the discussion is thoughtful and nuanced.

**Tags**: `#computer`, `#programming`, `#nostalgia`, `#community`, `#reflection`

---

<a id="item-18"></a>
## [Homelab AI Dev Platform with OpenCode and Forgejo](https://rsgm.dev/post/ai-dev-platform/) ⭐️ 6.0/10

A developer shared their homelab AI development platform setup, integrating the open-source AI coding agent OpenCode with the self-hosted Git service Forgejo. This demonstrates how individuals can build self-hosted AI development workflows, reducing dependency on closed-source tools and gaining full control over their code and AI interactions. The setup uses a persistent OpenCode server paired with Forgejo for Git hosting, enabling AI-assisted code review and pull request generation within a homelab environment.

hackernews · rsgm · Jun 15, 15:09 · [Discussion](https://news.ycombinator.com/item?id=48542433)

**Background**: OpenCode is an open-source AI coding agent that supports 75+ LLMs and implements the Model Context Protocol (MCP) for extensibility. Forgejo is a painless, self-hosted Git service similar to GitHub or GitLab. Combining them allows developers to run AI-powered development tools locally.

<details><summary>References</summary>
<ul>
<li><a href="https://open-code.ai/en">OpenCode Docs: Free Open-Source AI Coding Agent | 75+ LLM ...</a></li>

</ul>
</details>

**Discussion**: Commenters shared similar setups, with one using OpenCode inside Forgejo action runners via a workflow that triggers AI code reviews from issues. Another noted the challenge of managing context across multiple rounds of discussion. Positive sentiment overall, with appreciation for the shared inspiration.

**Tags**: `#homelab`, `#AI`, `#development platform`, `#self-hosted`, `#Forgejo`

---

<a id="item-19"></a>
## [US Battery Manufacturing Output Hits Record Highs](https://fred.stlouisfed.org/series/IPG33591S) ⭐️ 6.0/10

The US battery manufacturing output index reached a new record high in recent data from the Federal Reserve, indicating sustained growth in domestic production. This growth signals progress in US industrial capacity for energy storage, which is critical for electric vehicles and grid stability. However, community comments highlight that the US still lags far behind China and Europe in absolute production capacity. The data series (IPG33591S) includes primary batteries under durable goods, so a significant portion may come from consumer battery production rather than advanced EV batteries. Commenters also note that US cell production capacity in 2025 is estimated at only 70 GWh, compared to China's 1755 GWh.

hackernews · epistasis · Jun 15, 20:28 · [Discussion](https://news.ycombinator.com/item?id=48546616)

**Background**: Battery manufacturing output is measured by the Federal Reserve's industrial production index for NAICS code 33591, which covers all types of batteries. The index reflects volume of production but not capacity or technological sophistication. EVs require lithium-ion batteries, which differ from primary cells like alkaline.

**Discussion**: Commenters express cautious optimism about the record but emphasize the vast gap with China and Europe in cell production capacity. One user points out that the data may be skewed by primary battery production, and another notes that US battery production has not kept pace with EV adoption growth, suggesting batteries are not flowing into EVs.

**Tags**: `#battery manufacturing`, `#energy storage`, `#US manufacturing`, `#electric vehicles`, `#industrial policy`

---

<a id="item-20"></a>
## [Personality Clashes Took Anthropic's Models Offline](https://simonwillison.net/2026/Jun/15/axios-clashes-anthropics/#atom-everything) ⭐️ 6.0/10

A report from Axios reveals that personality clashes between Anthropic and US government officials led to the suspension of Anthropic's Claude Mythos and Fable models under export control directives. This incident highlights how interpersonal dynamics and policy disputes can disrupt access to frontier AI models, affecting both AI safety research and national security interests. Anthropic's constitutional classifiers have yet to find a universal jailbreak for Claude Mythos, but the government cites a narrow jailbreak as justification for the shutdown; an attitude fix may be required before models are restored.

rss · Simon Willison · Jun 15, 14:57

**Background**: The US government recently issued a directive to suspend access to Anthropic's Fable and Mythos models under export control rules, citing potential national security risks from jailbreaks. Anthropic is a leading AI safety company, and its models are considered among the most capable. The dispute reportedly involves not just technical issues but also how Anthropic engaged with the Commerce Department.

**Tags**: `#Anthropic`, `#AI Policy`, `#Export Control`, `#Government Relations`

---

<a id="item-21"></a>
## [Open training frameworks beyond open weights needed for ML research](https://www.reddit.com/r/MachineLearning/comments/1u6p7k3/open_weights_are_not_enough_we_need_open_training/) ⭐️ 6.0/10

A reddit post argues that open weights alone are insufficient for advancing ML research and introduces FeynRL, an open-source framework for reinforcement learning post-training of LLMs, VLMs, and agents. This matters because current ML research often relies on hidden training systems, making it hard to develop new algorithms. Open training frameworks like FeynRL could democratize algorithm development and accelerate innovation in RL post-training. FeynRL is designed to make the training process explicit and modifiable, covering data loading, rollout generation, reward computation, loss construction, optimization, and evaluation. It supports SFT, DPO, and RL-style post-training for single-GPU, multi-GPU, and cluster setups.

reddit · r/MachineLearning · /u/summerday10 · Jun 15, 18:37

**Background**: Large language models (LLMs) are often fine-tuned using reinforcement learning in a post-training phase to improve reasoning and alignment. While open-weight models (e.g., Llama) exist, the training pipelines used to create them are often proprietary or not well-documented, hindering algorithm research. Open training frameworks aim to make these pipelines transparent and reproducible.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/FeynRL-project/FeynRL">FeynRL-project/FeynRL: Post-training framework for large ... - GitHub</a></li>
<li><a href="https://www.reddit.com/r/reinforcementlearning/comments/1tvlquw/built_an_rl_framework_for_training_llms_where_you/">Built an RL framework for training LLMs where you can actually ...</a></li>
<li><a href="https://x.com/rasoolfa/status/2064743385047634064">This is exactly why open-source frameworks like FeynRL matter ...</a></li>

</ul>
</details>

**Tags**: `#open source AI`, `#training frameworks`, `#reinforcement learning`, `#LLMs`, `#research infrastructure`

---

<a id="item-22"></a>
## [Quant Firms Dominate ICML 2026 Diamond Sponsorship](https://www.reddit.com/r/MachineLearning/comments/1u64rse/quant_firms_at_icml_2026_d/) ⭐️ 6.0/10

A Reddit user observed that quantitative finance firms are heavily sponsoring ICML 2026 as diamond sponsors, sparking discussion about the trend. This trend highlights the growing reliance of quant firms on cutting-edge machine learning research and the talent pipeline at top conferences like ICML. ICML 2026 features multiple quant firms as diamond sponsors, the highest sponsorship tier, indicating significant financial commitment and strategic interest.

reddit · r/MachineLearning · /u/Intrepid_Discount_67 · Jun 15, 03:09

**Background**: ICML (International Conference on Machine Learning) is one of the premier academic conferences in machine learning. Quantitative finance firms, such as hedge funds and trading firms, increasingly leverage ML for algorithmic trading and risk management. Sponsoring top conferences allows them to recruit top talent and influence research directions.

**Tags**: `#ICML`, `#quantitative finance`, `#sponsorship`, `#machine learning`, `#industry trends`

---