---
layout: default
title: "Horizon Summary: 2026-07-26 (EN)"
date: 2026-07-26
lang: en
---

> From 33 items, 13 important content pieces were selected

---

1. [4B Open-Weight Models Approach o3-Level Medical QA in Swedish](#item-1) ⭐️ 9.0/10
2. [Kill The Cookie Banner: Browser-Level Privacy Preferences](#item-2) ⭐️ 8.0/10
3. [Ruff v0.16.0 Expands Default Rules from 59 to 413](#item-3) ⭐️ 8.0/10
4. [GrapheneOS Locks Down Data with Auto-Reboot to BFU](#item-4) ⭐️ 8.0/10
5. [Anthropic Launches Claude Opus 5 at Half the Price](#item-5) ⭐️ 8.0/10
6. [YOLO26n Inference from Scratch in ARM64 Assembly](#item-6) ⭐️ 8.0/10
7. [The Versatile Shell Colon Command](#item-7) ⭐️ 7.0/10
8. [New context engineering rules for Claude 5 spark debate](#item-8) ⭐️ 7.0/10
9. [Anthropic's Opus 5 Claims Best Prompt Injection Resistance](#item-9) ⭐️ 7.0/10
10. [LLMs Benchmarked on IMO 2026 Problems, AutoFyn Boosts Weaker Models](#item-10) ⭐️ 7.0/10
11. [Paper Lengths May Bias Against Theoretical ML Work](#item-11) ⭐️ 7.0/10
12. [Gatwick Airport Launches Robotic Valet Parking Service](#item-12) ⭐️ 6.0/10
13. [NeurIPS Position Track Rebuttal Advice for First-Time Submitter](#item-13) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [4B Open-Weight Models Approach o3-Level Medical QA in Swedish](https://www.reddit.com/r/MachineLearning/comments/1v71wds/openweight_4b_models_approach_o3level_medical/) ⭐️ 9.0/10

A 4B-parameter model, Qwen3.5-4B with reasoning, achieved 87% accuracy on the Swedish medical licensing exam dataset MedQA-SWE, approaching OpenAI's o3 model's 88% accuracy. The models are open-weight and publicly available. This demonstrates that small open-weight models can rival proprietary frontier models in domain-specific reasoning tasks, significantly lowering the barrier for specialized medical AI applications. It also highlights the potential of post-training techniques like reasoning and early exit to boost performance without scaling model size. The best result was achieved by Qwen3.5-4B with reasoning enabled, using an early exit intervention from the S-GRPO paper to prevent infinite reasoning loops. Without reasoning, the same model scored 77% accuracy. The models were tested on the MedQA-SWE dataset, which consists of 3,180 multiple-choice questions from Swedish medical licensing exams.

reddit · r/MachineLearning · /u/AccomplishedCat4770 · Jul 26, 11:58

**Background**: MedQA-SWE is a multiple-choice clinical question-answering dataset in Swedish, created from exams for foreign doctors seeking a Swedish medical license. It contains 3,180 questions and is the first open-source clinical QA dataset in Swedish. The S-GRPO method (Serial-Group Decaying-Reward Policy Optimization) is a reinforcement learning approach that enables models to learn when to stop reasoning early, avoiding overthinking.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/datasets/nicher92/medqa-swe">nicher92/medqa-swe · Datasets at Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2505.07686">[2505.07686] S-GRPO: Early Exit via Reinforcement Learning in Reasoning Models</a></li>

</ul>
</details>

**Discussion**: The community comments on the Reddit post discuss technical details like the early exit intervention and reasoning behavior in English despite Swedish prompts. Users express interest in applying similar techniques to other low-resource languages and note the impressive performance of small models.

**Tags**: `#open-weight LLMs`, `#medical QA`, `#reasoning`, `#small models`, `#Swedish`

---

<a id="item-2"></a>
## [Kill The Cookie Banner: Browser-Level Privacy Preferences](https://killthecookiebanner.eu/) ⭐️ 8.0/10

The EU Commission has proposed allowing users to set privacy preferences once in their browser, eliminating the need for cookie banners. This initiative faces pushback from the tracking industry, which has so far been successful in delaying its adoption. This proposal could drastically improve user experience and privacy by removing misleading cookie banners that often confuse users. Its success would set a precedent for browser-level privacy controls, potentially reshaping how online consent is managed globally. The proposal builds on existing signals like Global Privacy Control (GPC), which under the CCPA requires businesses to respect user opt-out signals. However, the tracking industry argues that universal opt-out could harm advertising revenue and personalization.

hackernews · rapnie · Jul 26, 11:53 · [Discussion](https://news.ycombinator.com/item?id=49057175)

**Background**: Cookie banners are required under the EU's ePrivacy Directive and GDPR to obtain user consent for tracking cookies, but they have been widely criticized for being intrusive and manipulative. Browser-level privacy preferences would allow users to set a persistent, legally binding signal that websites must honor. Similar efforts include the Do Not Track header, which was largely ignored, and the more successful GPC, which is legally enforceable in California.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Global_Privacy_Control">Global Privacy Control - Wikipedia</a></li>
<li><a href="https://globalprivacycontrol.org/">Global Privacy Control — Take Control Of Your Privacy</a></li>
<li><a href="https://oag.ca.gov/privacy/ccpa/gpc">Global Privacy Control (GPC) | State of California - Department of Justice - Office of the Attorney General</a></li>

</ul>
</details>

**Discussion**: Comments express strong support for browser-level preferences, with users arguing that current cookie banners do not constitute informed consent. Some express skepticism about the tracking industry's successful blocking of the proposal, and highlight the need to address the 'legitimate interest' loophole that often bypasses user preferences.

**Tags**: `#Privacy`, `#EU regulation`, `#Web standards`, `#Cookie banners`, `#Browser API`

---

<a id="item-3"></a>
## [Ruff v0.16.0 Expands Default Rules from 59 to 413](https://astral.sh/blog/ruff-v0.16.0) ⭐️ 8.0/10

Ruff v0.16.0 increases the number of default lint rules from 59 to 413, significantly broadening the scope of code quality checks. This major update makes Ruff catch far more potential issues by default, improving code quality for users, though it may require adjustments to existing projects. The new default ruleset includes rules from Flake8, pycodestyle, pydocstyle, and other plugins, increasing coverage without requiring manual configuration.

hackernews · vismit2000 · Jul 26, 09:01 · [Discussion](https://news.ycombinator.com/item?id=49056112)

**Background**: Ruff is an extremely fast Python linter and formatter written in Rust, designed as a drop-in replacement for tools like Flake8, isort, and pydocstyle. Its speed and integrated approach have made it popular in the Python community since its initial release.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.astral.sh/ruff/linter/">The Ruff Linter | Ruff - Astral</a></li>
<li><a href="https://github.com/astral-sh/ruff">GitHub - astral-sh/ruff: An extremely fast Python linter and code ...</a></li>

</ul>
</details>

**Discussion**: Users like nickjj report that the new rules improve code quality and caught issues missed before, while maratc criticizes the proliferation of arbitrary lint rules. Others hope for better versioning mechanisms to manage rule changes across multiple repositories.

**Tags**: `#ruff`, `#python`, `#linter`, `#tooling`, `#open-source`

---

<a id="item-4"></a>
## [GrapheneOS Locks Down Data with Auto-Reboot to BFU](https://discuss.grapheneos.org/d/40700-grapheneos-protections-against-data-extraction-from-locked-devices) ⭐️ 8.0/10

GrapheneOS has implemented strong protections against data extraction from locked devices, including an 18-hour auto-reboot feature that returns the device to Before First Unlock (BFU) mode where encryption keys are not accessible in memory. This significantly enhances mobile security for journalists, activists, and anyone at risk of device seizure, as it prevents forensic extraction of data even without the user needing to enter a duress password. It sets a new standard for privacy-focused smartphone operating systems. The auto-reboot feature triggers 18 hours after the device is locked, forcing it into BFU state where file-based encryption keys are wiped from RAM. This works alongside GrapheneOS's verified boot and hardened memory allocator to further resist physical attacks.

hackernews · Cider9986 · Jul 26, 05:57 · [Discussion](https://news.ycombinator.com/item?id=49055169)

**Background**: In Android, file-based encryption protects user data on devices. When a device is turned on but not yet unlocked (BFU), encryption keys are not available, making data inaccessible. Once unlocked (AFU), keys are in memory and may be vulnerable to forensic tools. GrapheneOS is a security-hardened Android-based operating system focused on privacy and security.

<details><summary>References</summary>
<ul>
<li><a href="https://blogs.dsu.edu/digforce/2023/08/23/bfu-and-afu-lock-states/">BFU and AFU Lock States – Blog | DigForCE Lab - DSU</a></li>
<li><a href="https://athenaforensics.co.uk/understanding-the-difference-between-afu-and-bfu-device-states-in-mobile-phone-forensics/">AFU vs BFU in Mobile Phone Forensics: The Difference</a></li>
<li><a href="https://lucidtruthtechnologies.com/bfu-vs-afu/">BFU vs AFU: Phone Lock States and Digital Evidence | LTT</a></li>

</ul>
</details>

**Discussion**: Community comments praised the auto-reboot feature as a strong non-duress protection, but some noted missing backup/restore solutions for safe wiping before border crossings. Others discussed the entropy of pattern locks versus long passwords, and an idea for a duress option that appears indistinguishable from normal operation.

**Tags**: `#security`, `#mobile-OS`, `#privacy`, `#encryption`, `#GrapheneOS`

---

<a id="item-5"></a>
## [Anthropic Launches Claude Opus 5 at Half the Price](https://simonwillison.net/2026/Jul/24/introducing-claude-opus-5/#atom-everything) ⭐️ 8.0/10

Anthropic announced Claude Opus 5 on July 24, 2026, a new AI model that matches the performance of its flagship Claude Fable 5 at half the cost. It currently tops the Artificial Analysis LLM leaderboard with an Intelligence Index score of 61. Claude Opus 5 offers near-frontier intelligence at a significantly lower price point, making advanced AI more accessible and competitive. Its release intensifies the AI model race, especially against Anthropic's own top-tier model. The model is priced the same as Opus 4.8 and offers a 'fast mode' at double the base cost. It improved at finding cybersecurity vulnerabilities but was deliberately not trained on exploitation, remaining behind Mythos 5 in that area.

rss · Simon Willison · Jul 24, 23:48

**Background**: Claude Opus 5 is Anthropic's latest model in the Opus line, positioned as a cost-effective alternative to the flagship Claude Fable 5, which is a Mythos-class model released in June 2026. The Artificial Analysis leaderboard ranks LLMs by intelligence, speed, and pricing, with Opus 5 now leading. Anthropic also published a prompting guide for the new model.

<details><summary>References</summary>
<ul>
<li><a href="https://fable5.io/">Fable 5 AI — Independent Model Guide & Prompt Workspace</a></li>
<li><a href="https://artificialanalysis.ai/leaderboards/models">LLM Leaderboard - Comparison of AI models from OpenAI ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Anthropic`, `#Claude`, `#model release`

---

<a id="item-6"></a>
## [YOLO26n Inference from Scratch in ARM64 Assembly](https://www.reddit.com/r/MachineLearning/comments/1v6w394/i_implemented_the_yolo26n_model_inference_from/) ⭐️ 8.0/10

A developer implemented YOLO26n inference entirely from scratch using ARM64 assembly and C, without any inference frameworks, and released the open-source code on GitHub. This project demonstrates deep understanding of low-level neural network optimization for edge AI, offering a reference for deploying modern YOLO models on resource-constrained devices like the Raspberry Pi 4 with techniques such as Winograd convolution and NEON SIMD. The implementation includes custom ARM64 micro-kernels, operator fusion, cache-aware tiling, and a redesigned memory layout for the model parameters; however, the performance gain was lower than expected, and the author seeks feedback on optimization strategies.

reddit · r/MachineLearning · /u/Forward_Confusion902 · Jul 26, 06:43

**Background**: YOLO26n is a compact, end-to-end object detection model designed for efficient deployment on edge devices, eliminating the need for non-maximum suppression (NMS). Winograd convolution is an algorithm that reduces computational complexity by transforming convolutions into element-wise multiplications, making it suitable for low-power processors like the ARM Cortex-A72 in Raspberry Pi 4.

<details><summary>References</summary>
<ul>
<li><a href="https://huggingface.co/openvision/yolo26-n">openvision/ yolo 26 - n · Hugging Face</a></li>
<li><a href="https://arxiv.org/abs/2201.10369">[2201.10369] Winograd Convolution for Deep Neural Networks: Efficient Point Selection</a></li>
<li><a href="https://blog.roboflow.com/train-yolov8-obb-model/">How to Train a YOLO 26 Oriented Bounding Box (OBB) Model</a></li>

</ul>
</details>

**Tags**: `#YOLO`, `#ARM64`, `#Assembly`, `#Edge AI`, `#Inference Optimization`

---

<a id="item-7"></a>
## [The Versatile Shell Colon Command](https://refp.se/articles/your-shell-and-the-magic-colon) ⭐️ 7.0/10

An article explores creative uses of the shell's `:` (colon) command, which does nothing but can serve as a placeholder, for comments, default values, and docstrings. This matters because it shows shell scripters how to leverage a simple built-in command for more readable, robust, and idiomatic scripts, especially in POSIX-compliant environments. The colon command is a POSIX built-in that always returns exit code 0. It can be used with parameter expansion for default values, as a comment with a string argument, and as a no-op required by syntax in if statements or while loops.

hackernews · olexsmir · Jul 25, 13:33 · [Discussion](https://news.ycombinator.com/item?id=49047453)

**Background**: In Unix shell scripting, the colon command (`:`) is a null command that does nothing and always exits successfully. It originated from early shells where it was used as a label marker, but in modern POSIX shell, it serves as a no-op. Many shell constructors require a command syntactically, and `:` can fill that role without side effects.

**Discussion**: Commenters shared mixed views: some found the colon command useful for docstrings (teddyh) and error messages (kevincox), while others criticized shell syntax in general (garethrowlands) and pointed out simpler alternatives like using `!` for negation (amiga386). Overall, the discussion highlighted both the cleverness and the legacy quirks of POSIX shell.

**Tags**: `#shell`, `#bash`, `#posix`, `#scripting`, `#programming-techniques`

---

<a id="item-8"></a>
## [New context engineering rules for Claude 5 spark debate](https://claude.com/blog/the-new-rules-of-context-engineering-for-claude-5-generation-models) ⭐️ 7.0/10

Anthropic published a blog post introducing new context engineering rules specifically for Claude 5 generation models, aiming to improve reliability and performance through structured context curation. This post has sparked significant community criticism (423 points, 322 comments) questioning whether such complex engineering is necessary or effective, reflecting broader skepticism about over-reliance on prompt engineering techniques in advanced LLMs. The rules reportedly leverage Claude's automemory and system prompts, but community members argue these features are unreliable and can lead to unwanted decisions, especially when reasoning traces are hidden.

hackernews · mellosouls · Jul 25, 20:42 · [Discussion](https://news.ycombinator.com/item?id=49051361)

**Background**: Context engineering is an iterative process of curating and optimizing the information provided to an LLM within its context window, distinct from writing a single prompt. It has become increasingly important as AI agents are deployed in complex, dynamic environments. Claude 5 is Anthropic's latest family of models, with Sonnet 5 being a strong agentic-coding model.

<details><summary>References</summary>
<ul>
<li><a href="https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents">Effective context engineering for AI agents \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/news/claude-sonnet-5">Introducing Claude Sonnet 5 \ Anthropic</a></li>
<li><a href="https://www.promptingguide.ai/guides/context-engineering-guide">Context Engineering Guide | Prompt Engineering Guide</a></li>

</ul>
</details>

**Discussion**: Community comments express skepticism, with users questioning the need for complex system prompts and automemory, citing instances where models still make errors like hallucinating APIs. Some see it as a lock-in strategy by Anthropic, while others note that context engineering can be overcomplicated compared to simple conversational tweaks.

**Tags**: `#Claude`, `#context engineering`, `#LLM`, `#prompt engineering`, `#AI reliability`

---

<a id="item-9"></a>
## [Anthropic's Opus 5 Claims Best Prompt Injection Resistance](https://simonwillison.net/2026/Jul/25/boris-cherny/#atom-everything) ⭐️ 7.0/10

Boris Cherny of Anthropic stated that Opus 5 is their least prompt injectable model yet, based on evaluations and red teaming detailed in the system card. This marks a significant advance in AI safety, as prompt injection is a critical vulnerability in large language models that can bypass safeguards and cause unintended behavior. The claim is supported by the Claude Opus 5 System Card, specifically on page 73, which reports strong resistance across multiple prompt injection evaluations and red teaming efforts.

rss · Simon Willison · Jul 25, 00:42

**Background**: Prompt injection is a cybersecurity exploit where crafted inputs cause an AI model to behave unexpectedly, often overriding its original instructions. System cards are transparency reports published by AI companies to detail model capabilities, limitations, and safety evaluations. Anthropic's Claude Opus 5 is their most advanced model, and its system card provides detailed safety analysis.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Prompt_injection_attack">Prompt injection attack</a></li>
<li><a href="https://owasp.org/www-community/attacks/PromptInjection">Prompt Injection - OWASP Foundation</a></li>

</ul>
</details>

**Tags**: `#prompt-injection`, `#anthropic`, `#claude`, `#generative-ai`, `#ai-safety`

---

<a id="item-10"></a>
## [LLMs Benchmarked on IMO 2026 Problems, AutoFyn Boosts Weaker Models](https://www.reddit.com/r/MachineLearning/comments/1v6wskz/we_compared_different_llms_on_imo_2026_r/) ⭐️ 7.0/10

A study compared frontier and open-weight LLMs on new IMO 2026 math problems, finding that frontier models (sol and fable) achieved near-perfect scores, while AutoFyn, a custom multi-agent harness, significantly improved performance of weaker models like Claude Sonnet and opus. This benchmark demonstrates that multi-agent orchestration can bridge the gap between frontier and weaker models on complex reasoning tasks, highlighting both the potential and limitations of current LLMs for mathematical problem-solving. The grading was performed by a frontier model and manually verified by former IMO medalists; on the hardest problem (P3), all sub-frontier models failed to find the key reduction step even with extended runs, indicating that harnesses provide retrieval and verification but not creative insight.

reddit · r/MachineLearning · /u/pequalnp92 · Jul 26, 07:21

**Background**: The International Mathematical Olympiad (IMO) is a prestigious competition with novel problems that are unlikely to be in training data, making it a strong benchmark for reasoning. AutoFyn is a multi-agent harness that runs LLMs in self-improving loops with verifiable rewards, similar to frameworks like AutoGen. The study also compared performance using different harnesses, including the native webapp and Claude Code.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/SignalPilot-Labs/AutoFyn">GitHub - SignalPilot-Labs/AutoFyn: Run Claude in self-improving loops ...</a></li>
<li><a href="https://dev.to/aiwave/multi-agent-ai-systems-a-practical-guide-to-orchestrating-llms-for-complex-workflows-3geh">Multi - Agent AI Systems: A Practical Guide to Orchestrating LLMs for...</a></li>

</ul>
</details>

**Tags**: `#LLMs`, `#benchmarking`, `#mathematical reasoning`, `#multi-agent`, `#IMO`

---

<a id="item-11"></a>
## [Paper Lengths May Bias Against Theoretical ML Work](https://www.reddit.com/r/MachineLearning/comments/1v6gh43/paper_lengths_and_reasonable_assumptions_in_ml/) ⭐️ 7.0/10

The author argues that fixed paper length limits in ML conferences unfairly penalize theoretical papers because prerequisite knowledge grows over time, leading to rejections based on perceived difficulty rather than impact. This highlights a structural bias that could discourage theoretical contributions and favor empirical work, potentially narrowing the field's intellectual diversity and innovation. Many conferences (e.g., NeurIPS, ICML) allow unlimited appendices, but reviewers are not required to read them. The author proposes a rule that explicitly forbids reviewers from demanding explanations of prerequisite knowledge beyond the main page limit.

reddit · r/MachineLearning · /u/OutsideSimple4854 · Jul 25, 18:48

**Background**: Academic conferences impose page limits to manage review workload and printing costs. In ML, theoretical papers require substantial mathematical background that cannot be fully covered within these limits, creating tension between self-containment and brevity.

**Discussion**: The author, a theoretical ML researcher, reports an increasing trend of rejections citing 'math is difficult' rather than substantive criticisms, and calls for a rule acknowledging length constraints. Commenters likely share similar frustrations.

**Tags**: `#machine learning conferences`, `#paper review`, `#theoretical ML`, `#academic publishing`

---

<a id="item-12"></a>
## [Gatwick Airport Launches Robotic Valet Parking Service](https://aerospaceglobalnews.com/news/gatwick-airport-robotic-parking-stanley-robotics/) ⭐️ 6.0/10

London Gatwick Airport has introduced a robotic valet parking service where robots from Stanley Robotics move cars within a parking garage, though passengers still must take a bus to the terminal. This deployment marks a practical application of robotics in airport parking, potentially improving space efficiency and reducing the need for passengers to search for spots, but the bus requirement limits convenience gains. Passengers retain their keys throughout the trip, and on-site staff can retrieve forgotten items, though the commenter questions how staff would access the car without keys. The robotic system optimizes parking space and is priced competitively.

hackernews · agotterer · Jul 26, 14:40 · [Discussion](https://news.ycombinator.com/item?id=49058669)

**Background**: Robotic valet parking systems use automated guided vehicles (AGVs) or robots to move and park cars without a driver inside, increasing parking density in garages. Stanley Robotics is a deep-tech company specializing in outdoor robotics for logistics, and their system, called Stan, lifts and moves cars autonomously. Similar systems have been deployed at other airports and urban parking facilities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.stanley-robotics.com/">Stanley Robotics { digitalisation, automatisation & robotisation }</a></li>
<li><a href="https://www.youtube.com/watch?v=SEbxNJWf8Rw">Outdoor Automated Valet Parking Robot System - YouTube</a></li>

</ul>
</details>

**Discussion**: Commenters expressed mixed feelings: some found the bus requirement disappointing, while others appreciated the competitive pricing. Practical concerns arose about alarm systems, key access for emergency retrieval, and the potential for YouTubers to hide in their cars for a stunt.

**Tags**: `#robotics`, `#airport`, `#parking`, `#automation`

---

<a id="item-13"></a>
## [NeurIPS Position Track Rebuttal Advice for First-Time Submitter](https://www.reddit.com/r/MachineLearning/comments/1v5ykl8/neurips_position_track_rebuttal_and_reviews_r/) ⭐️ 6.0/10

A first-time NeurIPS Position Paper submitter received mixed reviews (3/3/5/7) and a positive meta review, and is seeking advice on how rebuttals affect scores and acceptance decisions. This reflects a common procedural concern among newcomers to top ML conferences, where understanding the rebuttal process can significantly impact submission outcomes and community participation. The author's meta review included actionable suggestions like 'a revision should include...', indicating potential acceptance after revisions. Reviews are addressable, and the author seeks to know if reviewers change scores or if the Area Chair makes the final decision based on rebuttals.

reddit · r/MachineLearning · /u/Empty-Avocado5927 · Jul 25, 04:52

**Background**: The NeurIPS Position Paper Track, introduced in 2025 and continued in 2026, invites papers arguing for a viewpoint rather than reporting completed advances. In the peer review process, authors submit rebuttals to address reviewer concerns, after which reviewers may adjust scores and Area Chairs (ACs) make acceptance decisions based on all inputs.

<details><summary>References</summary>
<ul>
<li><a href="https://blog.neurips.cc/2026/06/02/ai-generated-papers-in-the-neurips-2026-position-paper-track/">AI-Generated Papers in the NeurIPS 2026 Position Paper Track – NeurIPS Blog</a></li>
<li><a href="https://neurips.cc/Conferences/2026/CallForPositionPapers">NeurIPS 2026 Call for Position Papers</a></li>
<li><a href="https://blog.neurips.cc/2026/03/30/whats-new-for-the-position-paper-track-at-neurips-2026/">What’s new for the Position Paper Track at NeurIPS 2026 – NeurIPS Blog</a></li>

</ul>
</details>

**Tags**: `#NeurIPS`, `#conference`, `#rebuttal`, `#peer review`, `#machine learning`

---