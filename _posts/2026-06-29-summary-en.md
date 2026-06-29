---
layout: default
title: "Horizon Summary: 2026-06-29 (EN)"
date: 2026-06-29
lang: en
---

> From 31 items, 21 important content pieces were selected

---

1. [US Supreme Court rules geofence warrants require constitutional protections](#item-1) ⭐️ 9.0/10
2. [Rocket Lab Acquires Iridium](#item-2) ⭐️ 8.0/10
3. [Deep Dive into CUDA Kernel Execution](#item-3) ⭐️ 8.0/10
4. [HackerRank's Open-Source ATS Produces Inconsistent Resume Scores](#item-4) ⭐️ 8.0/10
5. [Ornith-1.0: Self-Scaffolding LLMs for Agentic Coding](#item-5) ⭐️ 8.0/10
6. [Google's Agentic AI Peer-Reviewer Handles 10K Papers at Top Conferences](#item-6) ⭐️ 8.0/10
7. [Interactive Minimal Transformer Visualization with Editable Weights](#item-7) ⭐️ 8.0/10
8. [Qwen 3.6 27B: Strong Local Model but High Hardware Cost](#item-8) ⭐️ 7.0/10
9. [European ISPs Seek Accountability for Overblocking Damage](#item-9) ⭐️ 7.0/10
10. [Sandia's SA3000: A Radiation-Hardened 8085 CPU](#item-10) ⭐️ 7.0/10
11. [Tidal Implements Policy for AI-Generated Music with Higher Standards](#item-11) ⭐️ 7.0/10
12. [Mag 7 Stocks May Be Starting to Underperform](#item-12) ⭐️ 7.0/10
13. [Mullvad CEO's donation to Swedish party sparks VPN community backlash](#item-13) ⭐️ 7.0/10
14. [Jon Udell: Keep Humans in Control in Agentic Development](#item-14) ⭐️ 7.0/10
15. [EML Trees Proven Universal Approximators](#item-15) ⭐️ 7.0/10
16. [HEMA Practitioner Builds Open Dataset for Sword Tracking AI](#item-16) ⭐️ 7.0/10
17. [MathFormer: Symbolic Math Solved by Pattern Matching, Not Reasoning](#item-17) ⭐️ 7.0/10
18. [Instagram Uses User Photos in Meta Glasses Ads](#item-18) ⭐️ 6.0/10
19. [Hack Your Summer Offers Free Internship Alternative](#item-19) ⭐️ 6.0/10
20. [Cerebras-OpenAI deal blocks small startups from inference API](#item-20) ⭐️ 6.0/10
21. [Seeking feedback on evaluating long-context memory in stateless LLMs](#item-21) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [US Supreme Court rules geofence warrants require constitutional protections](https://www.theguardian.com/us-news/2026/jun/29/supreme-court-geofence-warrants-case-decision) ⭐️ 9.0/10

The US Supreme Court ruled on June 29, 2026, that geofence warrants must comply with the Fourth Amendment, requiring probable cause and specificity before law enforcement can obtain location data from companies like Google. The decision came in the case United States v. Chatrie. This landmark ruling sets a major precedent for digital privacy, limiting warrantless bulk location surveillance by law enforcement. It will affect police practices and technology companies that store user geolocation data, potentially reshaping how reverse location warrants are used nationwide. The court held that geofence warrants are categorically subject to the Fourth Amendment's warrant requirement, based on probable cause and particularity. The case involved Google's Sensorvault database, and the ruling may require law enforcement to narrow the geographic area and time window of data requests.

hackernews · cdrnsf · Jun 29, 15:54 · [Discussion](https://news.ycombinator.com/item?id=48720924)

**Background**: A geofence warrant, or reverse location warrant, allows law enforcement to request from tech companies like Google the identification of all devices within a specific geographic area during a specific time period. It is used to identify suspects in crimes where no specific suspect is known. These warrants have been controversial due to privacy concerns because they can sweep up data from innocent bystanders. The Fourth Amendment protects against unreasonable searches and seizures, requiring warrants to be based on probable cause and particularized.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Geofence_warrant">Geofence warrant</a></li>
<li><a href="https://www.nacdl.org/Content/Geofence-Warrants">Geofence Warrants - NACDL</a></li>

</ul>
</details>

**Discussion**: Commenters provided historical context, such as the Petraeus affair, and linked to the full Supreme Court decision. One user asked about practical implications, wondering if police now need probable cause for a specific individual before obtaining a geofence warrant. Another noted surprise that Justice Barrett joined the dissent alongside Alito and Thomas. Overall, the discussion reflected support for the privacy protections imposed by the ruling.

**Tags**: `#Supreme Court`, `#geofence warrants`, `#privacy`, `#Fourth Amendment`, `#law enforcement`

---

<a id="item-2"></a>
## [Rocket Lab Acquires Iridium](https://investors.rocketlabcorp.com/news-releases/news-release-details/rocket-lab-acquire-iridium-historic-deal-creating-fully) ⭐️ 8.0/10

Rocket Lab announced a historic acquisition of Iridium Communications, merging a launch provider with a satellite constellation operator to create a fully integrated space communications and launch company. This deal reshapes the space industry by combining launch capabilities with a profitable satellite network, potentially driving down costs and ensuring a steady launch cadence, similar to SpaceX's Starlink strategy. The acquisition includes Iridium's valuable spectrum assets and its existing satellite constellation, which Rocket Lab can leverage for its own satellite manufacturing and future constellation replacement projects.

hackernews · everfrustrated · Jun 29, 14:09 · [Discussion](https://news.ycombinator.com/item?id=48719485)

**Background**: Rocket Lab is a leading small satellite launch provider known for its Electron rocket, while Iridium operates a global satellite communications network with 66 active satellites. This vertical integration mirrors trends in the space industry where launch and satellite operations are combined for efficiency.

**Discussion**: Comments highlight concerns about space debris and commercialization, but many see the acquisition as a strategic masterstroke by Rocket Lab CEO Peter Beck, providing a guaranteed launch pipeline and access to Iridium's profitable business.

**Tags**: `#rocketlab`, `#iridium`, `#space`, `#acquisition`, `#satellite`

---

<a id="item-3"></a>
## [Deep Dive into CUDA Kernel Execution](https://fergusfinn.com/blog/what-happens-when-you-run-a-gpu-kernel/) ⭐️ 8.0/10

A detailed blog post by Fergus Finn explores the entire journey of launching a CUDA kernel, from API calls to warp scheduling on GPU hardware. This article bridges the gap between high-level CUDA programming and low-level GPU architecture, helping developers write more efficient parallel code. The article covers the driver API path, GPU command submission, thread block assignment, warp scheduling, memory coalescing, and occupancy implications.

hackernews · mezark · Jun 29, 13:11 · [Discussion](https://news.ycombinator.com/item?id=48718863)

**Background**: CUDA is NVIDIA's parallel computing platform and API that allows developers to write programs executed on GPUs. A kernel is a function that runs on the GPU, composed of many threads grouped into blocks and grids. The GPU's streaming multiprocessors (SMs) execute warps—groups of 32 threads—via warp schedulers.

<details><summary>References</summary>
<ul>
<li><a href="https://modal.com/gpu-glossary/device-hardware/warp-scheduler">What is a Warp Scheduler ? | GPU Glossary</a></li>
<li><a href="https://developer.nvidia.com/blog/unlock-gpu-performance-global-memory-access-in-cuda/">Unlock GPU Performance: Global Memory Access in CUDA</a></li>
<li><a href="https://app.studyraid.com/en/read/11727/371448/thread-hierarchy-and-organization">Thread Hierarchy and Organization - Parallel Computing and CUDA Programming for GPU Optimization | StudyRaid</a></li>

</ul>
</details>

**Discussion**: Commenters praised the article's depth, especially on implicit stream synchronization and warp eligibility. Some noted that using the driver API offers more visibility, and others discussed the potential of open-source kernel optimization tools to challenge proprietary vendors.

**Tags**: `#CUDA`, `#GPU`, `#kernel execution`, `#parallel computing`

---

<a id="item-4"></a>
## [HackerRank's Open-Source ATS Produces Inconsistent Resume Scores](https://danunparsed.com/p/hackerrank-open-source-ats) ⭐️ 8.0/10

An analysis shows that HackerRank's open-source applicant tracking system (ATS), which uses stochastic large language models (LLMs), gives different scores for the same resume across multiple runs, with scores varying from 74 to 90 out of 100. This inconsistency highlights fundamental flaws in AI-driven hiring, potentially causing unfair rejection of qualified candidates and raising legal concerns under anti-discrimination laws, especially in the EU. The system uses a temperature setting of 0.1, purportedly to reduce randomness, but still produces highly variable results; the author also notes that project and experience scores are particularly unstable.

hackernews · sambellll · Jun 29, 01:44 · [Discussion](https://news.ycombinator.com/item?id=48713832)

**Background**: Large language models (LLMs) like those used in the ATS are stochastic, meaning they generate outputs based on probability distributions rather than deterministic rules. Even with low temperature settings, there is inherent randomness. An applicant tracking system (ATS) is software that filters and scores resumes to help employers manage job applications.

<details><summary>References</summary>
<ul>
<li><a href="https://danunparsed.com/p/hackerrank-open-source-ats">HackerRank 's Open - Source ATS Gave My Resume a Different Score...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Stochastic_parrot">Stochastic parrot - Wikipedia</a></li>

</ul>
</details>

**Discussion**: Commenters express concern about the stochastic nature of LLMs in hiring, with some noting potential illegality under EU anti-discrimination laws. Others sarcastically suggest throwing away half the resumes blindly, while one commenter with hiring experience finds a 35% success rate 'fantastic' but acknowledges valid candidates are screened out.

**Tags**: `#AI hiring`, `#resume screening`, `#LLM bias`, `#ATS`, `#stochastic processes`

---

<a id="item-5"></a>
## [Ornith-1.0: Self-Scaffolding LLMs for Agentic Coding](https://simonwillison.net/2026/Jun/29/ornith/#atom-everything) ⭐️ 8.0/10

DeepReinforce has released Ornith-1.0, a family of open-weight large language models (LLMs) licensed under MIT, achieving state-of-the-art performance on coding benchmarks by combining pretrained Gemma 4 and Qwen 3.5 models. This release marks a significant advancement in open-weight, agentic coding LLMs, offering competitive performance for software engineering tasks with permissive licensing that allows broad use and modification. Ornith-1.0 comes in variants including 9B Dense, 31B Dense, 35B Mixture-of-Experts (MoE), and 397B MoE, and the underlying Gemma 4 and Qwen 3.5 models are both Apache 2.0 licensed, ensuring compatibility.

rss · Simon Willison · Jun 29, 16:17

**Background**: Self-scaffolding LLMs are a class of models that iteratively generate their own scaffolding—the programmatic structure that guides task decomposition and tool use—during reinforcement learning. Agentic coding refers to AI agents that autonomously plan, write, test, and modify code with minimal human intervention. Open-weight models allow researchers and developers to inspect, modify, and run the models locally.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/ornith-1-0-self-learning-llm-for-coding-318c9a830bfc">Ornith 1.0 : Self Learning LLM for Coding | by Mehul Gupta | Medium</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#open-source`, `#coding`, `#agentic`, `#AI`

---

<a id="item-6"></a>
## [Google's Agentic AI Peer-Reviewer Handles 10K Papers at Top Conferences](https://www.reddit.com/r/MachineLearning/comments/1uio9rb/googles_agentic_peerreviewer_handled_10k_papers/) ⭐️ 8.0/10

Google deployed an agentic AI peer-reviewer at ICML and STOC conferences, reviewing approximately 10,000 papers with a 30-minute turnaround, and a formal paper shows it catches 34% more mathematical errors than zero-shot prompting. This sets a precedent for AI-automated scientific review at conference scale, potentially reducing reviewer burden and improving error detection in machine learning and computer science research. The agentic AI system used automated reasoning and tool-use to check mathematical derivations, achieving a 34% improvement over zero-shot prompting. The formal paper is available on arXiv (2606.28277).

reddit · r/MachineLearning · /u/Justgototheeffinmoon · Jun 29, 10:05

**Background**: Agentic AI refers to AI systems that can pursue goals, use tools, and act autonomously within defined constraints. Zero-shot prompting involves giving a model a task with no examples. Peer review at top conferences like ICML and STOC is a critical bottleneck, with thousands of papers needing rigorous evaluation.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Agentic_AI">Agentic AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Zero-shot_prompting">Zero-shot prompting</a></li>
<li><a href="https://blog.icml.cc/">ICML Blog – ICML Blog</a></li>

</ul>
</details>

**Tags**: `#AI`, `#peer review`, `#machine learning`, `#scientific publishing`

---

<a id="item-7"></a>
## [Interactive Minimal Transformer Visualization with Editable Weights](https://www.reddit.com/r/MachineLearning/comments/1uhw7fu/i_shrank_a_transformer_until_every_number_fitted/) ⭐️ 8.0/10

A software engineer created a self-contained HTML page that visualizes a minimal transformer's forward pass with editable weights and live recomputation. This tool makes transformer internals accessible to learners by allowing hands-on manipulation of weights and observing immediate effects on predictions. The transformer uses a 6-word vocabulary, 3-dimensional embeddings, single attention head, and single block. All weights and word vectors are editable, and downstream values update live.

reddit · r/MachineLearning · /u/DanielMoGo · Jun 28, 12:35

**Background**: Transformers use attention mechanisms with Query, Key, Value (QKV) projections to capture relationships between tokens. Causal masks prevent attending to future tokens in autoregressive models. Logits are the raw output scores before softmax, representing unnormalized probabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://machinelearningmastery.com/a-gentle-introduction-to-attention-masking-in-transformer-models/">A Gentle Introduction to Attention Masking in Transformer ...</a></li>
<li><a href="https://medium.com/@dewasheesh.rana/q-k-v-and-w-in-transformers-a-complete-step-by-step-numeric-walkthrough-3288b95827ae">Q, K, V and W in Transformers — A Complete Step-by ... - Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Logit">Logit - Wikipedia</a></li>

</ul>
</details>

**Tags**: `#transformer`, `#visualization`, `#education`, `#interactivity`, `#machine learning`

---

<a id="item-8"></a>
## [Qwen 3.6 27B: Strong Local Model but High Hardware Cost](https://quesma.com/blog/qwen-36-is-awesome/) ⭐️ 7.0/10

Qwen 3.6 27B, a dense 27-billion-parameter multimodal model, has been released and praised for its flagship-level agentic coding performance in local development, but its hardware requirements and limited testing on real-world codebases raise concerns. This highlights the tension between the growing capabilities of open-source LLMs and the practical barriers of running them locally, especially for developers who need to work with large existing codebases. The debate underscores the importance of hardware cost and real-world testing for adoption. The model supports both multimodal thinking and non-thinking modes, and includes MTP for faster inference, achieving up to 2.7x speedup. With quantization, it can run on 48GB VRAM, but the recommended 128GB MacBook Pro costs over $6,699.

hackernews · stared · Jun 29, 17:05 · [Discussion](https://news.ycombinator.com/item?id=48721903)

**Background**: Local LLM development refers to running large language models on a developer's own machine rather than relying on cloud APIs, providing privacy and control but requiring significant hardware resources. Dense models like Qwen 3.6 27B use all parameters for each inference, unlike MoE models that activate only a subset, leading to higher memory demands.

<details><summary>References</summary>
<ul>
<li><a href="https://qwen.ai/blog?id=qwen3.6-27b">Qwen3.6-27B: Flagship-Level Coding in a 27B Dense Model</a></li>
<li><a href="https://github.com/QwenLM/Qwen3.6">GitHub - QwenLM/Qwen3.6: Qwen3.6 is the large language model ...</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/how-to-run-large-language-models-locally-hardware-vram-and-setup-explained-7caec36ef181">How to Run Large Language Models Locally: Hardware, VRAM, and Setup Explained | by Mehul Gupta | Data Science in Your Pocket | Medium</a></li>

</ul>
</details>

**Discussion**: Commenters highlighted the prohibitive cost of the required hardware (e.g., $6,699+ for a 128GB MacBook Pro) and questioned whether the benchmarks represent real-world work, as examples were greenfield projects. Some users suggested alternative models like Gemma4 31B on a 5090, and others raised technical issues with MLX optimizations.

**Tags**: `#AI`, `#local development`, `#large language models`, `#hardware costs`, `#Qwen`

---

<a id="item-9"></a>
## [European ISPs Seek Accountability for Overblocking Damage](https://torrentfreak.com/european-isps-want-rightsholders-held-accountable-for-overblocking-damage/) ⭐️ 7.0/10

European Internet service providers are arguing that rightsholders should be legally and financially liable for damages caused by overblocking legitimate content, a stance that could shift responsibility in copyright enforcement. Overblocking can censor lawful content, harm businesses, and waste citizens' time; holding rightsholders accountable could deter abusive takedown practices and protect free expression online. Overblocking occurs when filters or court orders block more content than intended, often affecting legitimate sites like those using Cloudflare; the debate is part of broader EU policy on ISP liability and copyright, with real-world examples such as Spain's La Liga blocking Docker images.

hackernews · Brajeshwar · Jun 29, 16:07 · [Discussion](https://news.ycombinator.com/item?id=48721072)

**Background**: Overblocking refers to internet filters that restrict access to content beyond what is legally required, often due to overly broad blocking measures. ISPs currently face pressure to block infringing sites but risk collateral damage. This discussion is part of ongoing EU reforms on digital services and copyright, where balancing enforcement and free speech is critical.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Overblocking">Overblocking</a></li>

</ul>
</details>

**Discussion**: Community comments largely support the ISPs' position, criticizing current liability-free takedowns and highlighting overblocking in Spain. Some argue ISPs should have resisted blocking demands initially, while others point out the massive societal cost of wasted time due to overblocking.

**Tags**: `#internet censorship`, `#ISP liability`, `#copyright`, `#overblocking`, `#Europe`

---

<a id="item-10"></a>
## [Sandia's SA3000: A Radiation-Hardened 8085 CPU](https://www.cpushack.com/2026/06/03/sandia-national-labs-sa3000-8085-cpu/) ⭐️ 7.0/10

Sandia National Labs designed and fabricated the SA3000, a radiation-hardened version of the Intel 8085 CPU, in the late 1970s–1980s using in-house capabilities. The SA3000 could withstand up to 1×10^6 rads of radiation with only a 25% performance reduction, exceeding its design goal of 1×10^5 rads. This development demonstrates the value of in-house government semiconductor fabrication for critical defense and space applications where radiation hardening is essential. It highlights a historical approach to ensuring supply chain security and technical sovereignty for mission-critical chips. The SA3000 was fabricated on an n-on-n+ epitaxial substrate with extensive guard rings and hardened oxides to control latchup and radiation effects. It was part of a family that included the SA3001 radiation-hardened static RAM.

hackernews · rbanffy · Jun 29, 10:20 · [Discussion](https://news.ycombinator.com/item?id=48717287)

**Background**: Radiation hardening makes electronic components resistant to damage from ionizing radiation, crucial for spacecraft and nuclear weapons systems. The Intel 8085 was a popular 8-bit microprocessor from the late 1970s. Sandia's effort was part of a broader movement to give government labs independent IC fabrication capability, reducing reliance on commercial contractors.

<details><summary>References</summary>
<ul>
<li><a href="https://www.cpushack.com/2026/06/03/sandia-national-labs-sa3000-8085-cpu/">Sandia National Labs SA3000 8085 CPU | The CPU Shack Museum</a></li>
<li><a href="https://www.osti.gov/biblio/5968322">Radiation-hard design principles utilized in CMOS 8085 microprocessor family (Conference) | OSTI.GOV</a></li>

</ul>
</details>

**Discussion**: Commenters noted that modern radiation-hardened CPUs like the MOOG BRE440 and BAE RAD5500 use IBM POWER architecture, showing continuity in this niche. Some praised Sandia's in-house approach as a model for government capability, while others joked about using such old tech for nuclear weapons. A few questioned the reported number of chips required for the Galileo probe.

**Tags**: `#radiation-hardened CPUs`, `#retrocomputing`, `#defense technology`, `#hardware design`, `#8085`

---

<a id="item-11"></a>
## [Tidal Implements Policy for AI-Generated Music with Higher Standards](https://tidal.com/ai-policy) ⭐️ 7.0/10

Tidal has announced a new policy that will accept AI-generated music on its platform, but imposes higher standards to prevent exploitation of artists' names or likenesses, deception of listeners, and degradation of service quality. This policy is significant as it sets a precedent for how streaming platforms can handle AI-generated content, balancing openness with protections against misuse. It may influence other platforms and affect artists, listeners, and the music industry's approach to AI. The policy explicitly prohibits AI-generated music that exploits an individual's or group's music, name, or likeness, deceives listeners, or diminishes service quality. Tidal will not tolerate such content, but will allow other AI-generated music that meets content integrity standards.

hackernews · hn8726 · Jun 29, 13:09 · [Discussion](https://news.ycombinator.com/item?id=48718840)

**Background**: AI-generated music has become increasingly common, raising concerns about copyright infringement, artist compensation, and listener deception. Streaming platforms face pressure to address these issues while embracing technological innovation. Tidal's policy is a response to these challenges.

**Discussion**: Community comments show a mix of support and additional concerns. Many users applaud Tidal's balanced approach but request the ability to opt out of AI-generated music entirely. Others highlight issues like AI music spoofing artist names and the prevalence of AI music in small businesses. Overall, there is a call for clearer labeling and curation.

**Tags**: `#AI music`, `#music streaming`, `#content policy`, `#copyright`, `#AI ethics`

---

<a id="item-12"></a>
## [Mag 7 Stocks May Be Starting to Underperform](https://www.apollo.com/content/dam/apolloaem/pdf/daily-spark/2026/jun/28/062826-Mag7.pdf) ⭐️ 7.0/10

A PDF analysis from Apollo suggests that the Magnificent 7 tech stocks may be starting to underperform, supported by historical data showing that past winners often underperform in subsequent years. This matters because the Magnificent 7 have driven much of the market's gains, and their underperformance could signal a broader shift in market leadership, impacting investors and tech valuations. The analysis references data since 1926 showing that stocks with strong five-year runs have a median ten-year market-adjusted return of -17.8%. Additionally, community comments highlight concerns about massive capital expenditures on data centers without clear returns.

hackernews · mooreds · Jun 29, 14:12 · [Discussion](https://news.ycombinator.com/item?id=48719532)

**Background**: The 'Magnificent 7' refers to Apple, Microsoft, Google (Alphabet), Amazon, Nvidia, Meta, and Tesla – seven large-cap tech stocks that have dominated market gains. Historical patterns suggest that after prolonged outperformance, such stocks often revert to mean or underperform.

**Discussion**: Commenters debate the signals, with some noting that downstream companies benefit from Big Tech capex, while others question Google's valuation and the lack of returns from AI investments. There is a sentiment that the market is finally disciplining excessive spending.

**Tags**: `#finance`, `#stock market`, `#tech giants`, `#capital expenditure`, `#investment`

---

<a id="item-13"></a>
## [Mullvad CEO's donation to Swedish party sparks VPN community backlash](https://det.social/@lostgen/116820546568940358) ⭐️ 7.0/10

News emerged that Mullvad VPN co-CEO Daniel Berntsson personally funded the Örebro Party, a nationalist Swedish political group, leading to calls for boycotts and discussions about alternative VPN services. This raises concerns about the political alignment of privacy-focused service leaders, potentially affecting user trust and the perceived neutrality of VPN providers. The Örebro Party is described as nationalist but not far-right; Mullvad co-founder Fredrik Strömberg clarified that the donation was personal and does not reflect company values. Mullvad VPN is also white-labeled for Mozilla VPN, adding complexity.

hackernews · Risse · Jun 29, 10:45 · [Discussion](https://news.ycombinator.com/item?id=48717469)

**Background**: Mullvad is a well-known VPN service praised for strong privacy protections and anonymous payment options. The Örebro Party is a local Swedish party focusing on anti-immigration policies, sometimes labeled as nationalist. The donation was personal, but the connection has stirred debate in privacy communities.

**Discussion**: Comments show mixed reactions: some users express disappointment and seek alternatives, while others defend the distinction between personal and corporate actions. Co-founder Strömberg directly addressed concerns, emphasizing that Daniel's donation is not company policy.

**Tags**: `#privacy`, `#VPN`, `#politics`, `#tech controversy`

---

<a id="item-14"></a>
## [Jon Udell: Keep Humans in Control in Agentic Development](https://simonwillison.net/2026/Jun/28/jon-udell/#atom-everything) ⭐️ 7.0/10

Jon Udell argues that in agentic software development, humans should remain in control, with AI agents as team members rather than autonomous black boxes that generate unreviewable pull requests. This perspective challenges the prevalent 'human-in-the-loop' framing, advocating instead for an 'agent-in-the-loop' model that prioritizes human authority and review, which is crucial for maintaining code quality and trust in AI-assisted development. Udell specifically objects to agents creating unreviewable pull requests, emphasizing that agent-assisted processes should be transparent and collaborative, not black-box automation.

rss · Simon Willison · Jun 28, 21:57

**Background**: Agentic software development refers to using AI agents that can plan, execute, and verify multi-step tasks to build code. The term 'human-in-the-loop' (HITL) traditionally describes workflows where humans are involved in decision points within automated processes. Udell reframes this concept, arguing that the loop belongs to humans, and agents should be invited participants.

<details><summary>References</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/agentic-vs-traditional-development-what-changes-when-switch-clsle">Agentic vs. Traditional Development : What Changes, and When to...</a></li>
<li><a href="https://wetheflywheel.com/en/future-of-software-development/what-is-agentic-software-development/">What Is Agentic Software Development ? A 2026 Definition</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#software development`, `#human-in-the-loop`, `#agentic development`

---

<a id="item-15"></a>
## [EML Trees Proven Universal Approximators](https://www.reddit.com/r/MachineLearning/comments/1uipl1t/eml_trees_are_universal_approximators_r/) ⭐️ 7.0/10

This paper proves that EML trees, compositions of elementary functions, are universal approximators for continuous functions. It extends universal approximation theory to a new class of function representations, which could have implications for interpretable machine learning or symbolic regression. The proof constructs EML representations of binary operations, polynomials, hyperbolic tangent, and partitions of unity, and addresses issues with logarithm for nonpositive inputs using sign-based decompositions.

reddit · r/MachineLearning · /u/JoeGermany · Jun 29, 11:16

**Background**: Universal approximation theorems state that certain function classes (e.g., neural networks) can approximate any continuous function to arbitrary accuracy. EML trees represent functions by composing elementary mathematical operations like addition, multiplication, and exponentiation. This paper provides a theoretical proof that EML trees also have this universal property.

**Tags**: `#machine learning`, `#universal approximation`, `#EML trees`, `#function approximation`, `#theory`

---

<a id="item-16"></a>
## [HEMA Practitioner Builds Open Dataset for Sword Tracking AI](https://www.reddit.com/r/MachineLearning/comments/1uivddx/i_do_historical_swordfighting_and_noticed_ai/) ⭐️ 7.0/10

A historical European martial arts practitioner is creating a multi-view high-frame-rate dataset of swordfighting clips, along with a detailed annotation schema, to help computer vision models better track fast-moving thin objects like blades and occluded fighters. This dataset targets a difficult corner case for embodied AI—thin-object tracking under motion blur and occlusion—which could improve applications in sports analytics, robotics, and autonomous systems requiring robust visual tracking. The dataset uses synchronized cameras at 120/240 fps to capture 100 clips, with annotations including keypoints for fencers and swords, segmentation polygons, and metadata on biomechanics and visual hazards such as occlusion and motion blur.

reddit · r/MachineLearning · /u/fonssagrives · Jun 29, 15:16

**Background**: Historical European martial arts (HEMA) involves reconstructing combat techniques from historical manuals using replica weapons. Tracking thin, fast-moving swords and fully clothed fighters is challenging for current AI because of extreme motion blur and self-occlusion. Many models fail due to the sim-to-real gap between training data and real-world conditions.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Historical_European_martial_arts">Historical European martial arts - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2202.05659">[2202.05659] Tiny Object Tracking: A Large-scale Dataset and A Baseline</a></li>

</ul>
</details>

**Tags**: `#computer vision`, `#dataset`, `#motion tracking`, `#embodied AI`, `#HEMA`

---

<a id="item-17"></a>
## [MathFormer: Symbolic Math Solved by Pattern Matching, Not Reasoning](https://www.reddit.com/r/MachineLearning/comments/1uhatw8/mathformer_testing_whether_symbolic_math_is/) ⭐️ 7.0/10

A tiny 4M-parameter seq2seq model called MathFormer achieves 98.6% accuracy on symbolic math expansion tasks, indicating that such tasks are likely solved by structural pattern matching rather than genuine reasoning. This challenges the assumption that large language models truly reason mathematically, and suggests their apparent reasoning may be large-scale pattern completion. It also highlights the importance of architecture in determining model behavior. The model is a 4M-parameter sequence-to-sequence transformer with no explicit mathematical knowledge; it predicts expanded polynomial forms from factorized expressions. The high accuracy implies the task reduces to learning token transformation patterns rather than understanding operators or variables.

reddit · r/MachineLearning · /u/AlphaCode1 · Jun 27, 18:57

**Background**: Symbolic math expansion involves rewriting expressions like (7-3*z)*(-5*z-9) into expanded polynomials. Seq2seq models are neural networks that transform input sequences into output sequences, often using attention mechanisms. There is ongoing debate whether large language models genuinely reason or rely on pattern matching; this study provides evidence for the latter.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/Abhinand20/MathFormer">GitHub - Abhinand20/ MathFormer : MathFormer - Solve math ...</a></li>
<li><a href="https://trendshift.io/repositories/66461">Abhinand20/ MathFormer — GitHub trending stats & insights | Trendshift</a></li>

</ul>
</details>

**Tags**: `#machine learning`, `#symbolic math`, `#reasoning`, `#pattern matching`, `#interpretability`

---

<a id="item-18"></a>
## [Instagram Uses User Photos in Meta Glasses Ads](https://twitter.com/i/status/2071277885646868536) ⭐️ 6.0/10

Instagram has begun incorporating users' photos into advertisements for Meta's Ray-Ban Meta smart glasses, similar to Facebook's 2013 policy that allowed user content in ads. This move reignites privacy concerns, as it mirrors Meta's past controversial practices of using personal data without explicit user consent for advertising. It could erode user trust and prompt regulatory scrutiny. Meta Glasses, also known as Ray-Ban Meta, are smart glasses with integrated cameras, speakers, and Meta AI, and they start at $299. The ad policy appears to rely on Instagram's terms of service, which grant Meta permission to use user content for commercial purposes.

hackernews · notRobot · Jun 29, 13:26 · [Discussion](https://news.ycombinator.com/item?id=48719027)

**Background**: Meta (formerly Facebook) has a history of using user data in ads. In 2013, Facebook updated its policy to allow businesses to use users' profile pictures and likes in sponsored stories without explicit consent, leading to a class-action lawsuit. Meta Glasses are the company's latest smart glasses, featuring a 12 MP camera, five-microphone array, and AI capabilities. The integration of user photos into ads for these glasses is a new application of Meta's existing data-sharing practices.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Meta_glasses">Meta glasses</a></li>
<li><a href="https://phys.org/news/2013-11-facebook-ad-policy-unchanged-users.html">Facebook : ad policy unchanged, users in control</a></li>

</ul>
</details>

**Discussion**: Community members noted this is not new, recalling Facebook's 2013 policy, and criticized Meta's repeated misuse of user data. Some shared anecdotes of absurd ads, while others advised simply leaving the platform. A few highlighted that this also occurred with Meta AI last year.

**Tags**: `#privacy`, `#social media`, `#ads`, `#meta`, `#instagram`

---

<a id="item-19"></a>
## [Hack Your Summer Offers Free Internship Alternative](https://simonwillison.net/2026/Jun/28/hack-your-summer/#atom-everything) ⭐️ 6.0/10

Hack Your Summer is a free 4-week production sprint for undergraduate and graduate students to build real projects, with a second cohort starting July 13th and applications due July 8th. This initiative addresses the internship crisis where companies have reduced hiring and coaching capacity, providing students with a tangible alternative to gain project experience and showcase work to employers. The program is free and open to undergraduates, graduates, and recent graduates; it emphasizes creating public-facing work with mentor support, and volunteers are also sought to help mentor students.

rss · Simon Willison · Jun 28, 19:26

**Background**: US college students face a severe internship shortage this year as companies scale back hiring and intern coaching. Hack Your Summer fills this gap by offering a structured, high-velocity project sprint that simulates real-world production experience.

**Tags**: `#education`, `#internships`, `#student projects`, `#software engineering`

---

<a id="item-20"></a>
## [Cerebras-OpenAI deal blocks small startups from inference API](https://www.reddit.com/r/MachineLearning/comments/1uiqhiv/cerebras_openai_deal_capacity_has_effectively/) ⭐️ 6.0/10

A Reddit user reports that Cerebras' deal with OpenAI has pre-allocated most of its near-term inference capacity, making the API waitlist effectively infinite for smaller startups. This illustrates how large deals between hardware vendors and hyperscalers can starve smaller AI companies of critical infrastructure, potentially stifling innovation. The startup requires sustained high-throughput inference at 1-2k tokens/second with low p95 latency, and despite being on the waitlist for months, access remains unavailable.

reddit · r/MachineLearning · /u/Kortopi-98 · Jun 29, 12:00

**Background**: Cerebras specializes in wafer-scale processors designed for high-performance AI workloads. Hyperscalers like OpenAI can negotiate bulk purchase agreements that consume most of a vendor's production capacity. p95 latency is a metric used to measure tail latency, representing the worst-case delay experienced by the slowest 5% of requests.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Cerebras">Cerebras Systems - Wikipedia</a></li>
<li><a href="https://redis.io/blog/p95-latency/">P 95 Latency : What It Is & Why It Matters</a></li>
<li><a href="https://en.wikipedia.org/wiki/Hyperscaler">Hyperscaler</a></li>

</ul>
</details>

**Discussion**: The original poster expresses frustration, implying that resource allocation heavily favors big players. No other comments are provided in the news item.

**Tags**: `#AI inference`, `#Cerebras`, `#OpenAI`, `#hardware availability`, `#startups`

---

<a id="item-21"></a>
## [Seeking feedback on evaluating long-context memory in stateless LLMs](https://www.reddit.com/r/MachineLearning/comments/1ui27i1/evaluating_longterm_memory_limits_in_stateless/) ⭐️ 6.0/10

A Reddit user proposed a methodology to evaluate how well stateless LLM chatbots retain facts over long conversations by introducing key facts early, inserting hundreds of unrelated turns, and testing recall at intervals. The post is a preliminary request for community feedback before building the evaluation. This research question addresses a critical limitation of stateless LLMs—their inability to maintain context over extended interactions without external memory. A rigorous evaluation method could help developers understand when to use stateful or external memory systems, impacting chatbot design and user experience. The proposed method does not use any external memory system, relying solely on the model's inherent context window. The user plans to measure recall accuracy at different conversation lengths, but has not yet specified metrics or benchmark comparisons.

reddit · r/MachineLearning · /u/QuietAccountant4237 · Jun 28, 16:48

**Background**: Stateless LLMs treat each interaction independently, forgetting prior turns after the context window is exceeded. In contrast, stateful chatbots maintain a persistent memory of the conversation. Existing benchmarks like BEAM evaluate long-term memory but often focus on large context windows; the proposed evaluation targets the practical scenario where no external memory is used.

<details><summary>References</summary>
<ul>
<li><a href="https://www.vasundhara.io/blogs/stateful-vs-stateless-llms-whats-the-difference-and-why-it-matters">Stateful vs Stateless LLMs: What’s the Difference and Why It ...</a></li>
<li><a href="https://mem0.ai/blog/what-is-beam-memory-benchmark-the-paper-that-shows-1m-context-window-isnt-enough">What is BEAM Memory Benchmark? The Paper That Shows...</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#long-context`, `#memory evaluation`, `#chatbot`

---