---
layout: default
title: "Horizon Summary: 2026-08-18 (EN)"
date: 2026-08-18
lang: en
---

> From 26 items, 14 important content pieces were selected

---

1. [The Amazon Tax: Search Prioritizes Ads over Relevance](#item-1) ⭐️ 8.0/10
2. [Google buys failed airline Spirit's data for AI training](#item-2) ⭐️ 8.0/10
3. [Qwen 3.8 27B ties GPT-5.6 Luna on AI intelligence index](#item-3) ⭐️ 8.0/10
4. [AirTag Tracking Reveals Rare Book Shipment Ended at Amazon AI Facility](#item-4) ⭐️ 8.0/10
5. [Researcher Exposes Evaluation Tricks That Inflate KV Compression Results](#item-5) ⭐️ 8.0/10
6. [Railway Line-Scan Camera Turns Tracks Into a Flatbed Scanner](#item-6) ⭐️ 7.0/10
7. [Linux 7.3 Improves Performance When Running Out of vRAM](#item-7) ⭐️ 7.0/10
8. [Meta Files Patent for Facial Recognition and Automatic Recording of People](#item-8) ⭐️ 7.0/10
9. [How Bluesky draws its logo on screenshots](#item-9) ⭐️ 7.0/10
10. [Developer Unbricks Framework 13 AMD Laptop with $20 Tools](#item-10) ⭐️ 6.0/10
11. [Fairphone Now Officially Available for Direct Purchase in the US](#item-11) ⭐️ 6.0/10
12. [Rethinking Database Programming: Coexisting with SQL via Acadia](#item-12) ⭐️ 6.0/10
13. [Diffusion Model Runs on 264KB RAM Microcontroller with FPGA INT8 MAC Engines](#item-13) ⭐️ 6.0/10
14. [SineKAN: A KAN Variant Using Sinusoidal Activation Functions](#item-14) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [The Amazon Tax: Search Prioritizes Ads over Relevance](https://seths.blog/2026/08/the-amazon-tax/) ⭐️ 8.0/10

Seth Godin's essay 'The Amazon Tax' argues that Amazon's search results favor sponsored and platform-preferred products over relevant ones, imposing a hidden tax on consumers in time, money, and trust. The piece drew heavy engagement, with 337 points and 248 comments on Hacker News. This critique underscores rising concerns about search bias and ad-driven manipulation in e-commerce, which can erode consumer trust and distort purchase decisions. It also feeds into broader debates about platform economics and whether marketplaces truly serve users or primarily advertisers. Godin cites his own book search as an example, noting that searching 'The Knot' returns competitors' sponsored ads, which he calls the 'highest-yielding ad' his publisher tested. Commenters point to Amazon's A9 algorithm as the system that ranks products by relevance, sales velocity, and satisfaction, but sponsored placements introduce commercial bias into those results.

hackernews · herbertl · Aug 18, 13:22 · [Discussion](https://news.ycombinator.com/item?id=49345263)

**Background**: Amazon's product search is powered by the A9 algorithm, which ranks product listings based on relevance, sales velocity, and customer satisfaction. Ads such as Amazon Sponsored Products are pay-per-click placements that appear within search results, often above organic listings. Consequently, search results mix organic relevance with paid placements, nudging consumers toward advertised and high-margin products rather than exactly what they set out to find.

<details><summary>References</summary>
<ul>
<li><a href="https://epinium.com/en/blog/amazon-a9-algorithm-2/">Amazon A 9 Algorithm Guide | Epinium</a></li>
<li><a href="https://clickfluency.com/a-simple-guide-to-amazons-a9-algorithm-and-how-it-works/">A Simple Guide to Amazon’s A 9 Algorithm and How It... | Click Fluency</a></li>
<li><a href="https://grokipedia.com/page/Amazon_Sponsored_Products">Amazon Sponsored Products</a></li>

</ul>
</details>

**Discussion**: Commenters broadly agreed with the essay, with one noting that search has 'mutated' from locating the exact item to showing semantic results that nudge buying behavior. Others argued this is simply how ads work, while some said they have shifted to local shops or Etsy; a few even floated potential legal action over trademark infringement when competitor ads appear on search results for specific products or brands.

**Tags**: `#Amazon`, `#e-commerce`, `#platform economics`, `#search bias`, `#consumer behavior`

---

<a id="item-2"></a>
## [Google buys failed airline Spirit's data for AI training](https://www.theregister.com/ai-and-ml/2026/08/18/google-buys-crashed-airline-spirits-data-at-auction-because-ai/5288962) ⭐️ 8.0/10

Google has acquired the data of failed US airline Spirit through a bankruptcy auction, including emails, chats, customer service calls, and personal records. The purchase is intended to expand Google's AI training datasets. This acquisition highlights growing privacy concerns as massive amounts of personal data are repurposed for AI training. It also demonstrates how corporate data assets are treated as sellable commodities in bankruptcy proceedings, affecting millions of individuals. The dataset reportedly includes 100 million emails, 500 million Microsoft Teams items, 17 million OneDrive files, and 20.5 million SharePoint items, along with 30 million customer service calls and 15 million chat records. A 'de-identification agent' third party is responsible for removing personal identifiers before Google receives the data, but commenters question the effectiveness of this process.

hackernews · pseudolus · Aug 18, 10:13 · [Discussion](https://news.ycombinator.com/item?id=49343559)

**Background**: Successful airlines rarely sell customer data directly, but bankruptcy liquidation can turn such data into a saleable asset. The data was likely collected through Spirit's operations and now becomes a training resource for AI models. De-identification aims to strip personal identifiers, yet it is often difficult to guarantee full anonymity, and broader industry practices have shown that re-identification risks remain.

**Discussion**: Commenters expressed skepticism about the de-identification process, with one doubting that such rich data was truly 'de-identified.' Another reflected on the unsettling state of affairs where personal data is sold as a commodity, while a third asked whether the de-identification agent mechanism is standard practice. Overall, the sentiment is one of concern over privacy and the scale of data collection.

**Tags**: `#Google`, `#data acquisition`, `#AI`, `#privacy`, `#airline`

---

<a id="item-3"></a>
## [Qwen 3.8 27B ties GPT-5.6 Luna on AI intelligence index](https://simonwillison.net/2026/Aug/17/qwen-38-27b-scores-52/) ⭐️ 8.0/10

Alibaba's Qwen 3.8 27B, a 27-billion-parameter Apache-2.0 licensed vision-language model, scored 52 on the Artificial Analysis Intelligence Index, tying with GPT-5.6 Luna and coming within one point of the 753B-parameter GLM-5.2 and the 1.7T-parameter DeepSeek V4 Pro. A 27B-parameter model matching or nearly matching far larger frontier models signals a major efficiency breakthrough, potentially enabling state-of-the-art AI capabilities on consumer-grade hardware and significantly lowering inference costs. Developers, researchers, and edge-AI applications stand to benefit from this democratization of advanced AI. The Artificial Analysis Intelligence Index v4.1.1 evaluates models on a suite of tests including GDPval-AA v2, Terminal-Bench v2.1, SciCode, Humanity's Last Exam, and GPQA Diamond. The model defaults to an 'xhigh' reasoning effort that can overthink simple queries and exhaust the default 8,192-token context window; Willison ran it with the full 262,144-token context, and a 17GB Q4_K_M quantized build runs on laptops via LM Studio.

rss · Simon Willison · Aug 17, 23:58

**Background**: The Artificial Analysis Intelligence Index is an independent benchmark that scores AI models on a range of reasoning, coding, and knowledge tests such as Terminal-Bench and GPQA Diamond. Historically, top scores required models with hundreds of billions or trillions of parameters, like GLM-5.2 (753B) or DeepSeek V4 Pro (1.7T). Qwen 3.8 27B represents a growing trend of smaller, highly efficient open-weight models that rival these giants, made possible by advances in training and quantization. Its Apache-2.0 license further allows anyone to run it locally, democratizing access to frontier-level AI.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/">AI Model & API Providers Analysis | Artificial Analysis</a></li>
<li><a href="https://huggingface.co/Qwen/Qwen3.8-27B">Qwen/Qwen3.8-27B · Hugging Face</a></li>
<li><a href="https://www.yottalabs.ai/post/qwen-3-8-27b-specs-hardware-requirements-how-to-run-2026">Qwen 3.8 27B: Specs, Hardware Requirements, and How to Run It (2026) | Yotta Labs</a></li>

</ul>
</details>

**Tags**: `#AI`, `#LLMs`, `#Qwen`, `#benchmarks`, `#efficiency`

---

<a id="item-4"></a>
## [AirTag Tracking Reveals Rare Book Shipment Ended at Amazon AI Facility](https://simonwillison.net/2026/Aug/17/we-tracked-a-shipment-of-rare-books-it-ended-at-an-amazon-ai-tra/) ⭐️ 8.0/10

404 Media tracked a shipment of around 1,000 rare books ordered anonymously on Biblio by planting an AirTag inside one book, and it ended up delivered to the VGT3 corner of Amazon's LAS8 facility in Las Vegas. This provides direct evidence that large bulk book orders are being used for AI training data collection. This is the first concrete, on-the-ground confirmation that Amazon is feeding rare books into AI training pipelines, raising serious copyright and ethical questions for authors, publishers, and booksellers. It also validates long-standing suspicions in the bookselling community about anonymous, price-insensitive bulk orders. The bookseller received the large order in July on Biblio, a marketplace for used and rare books, and agreed to plant an AirTag supplied by 404 Media in one volume. The photo of the facility entrance shows a logo of a dinosaur clutching a book, and online forums among Amazon workers confirmed that the VGT3 site destructively scans large volumes of books.

rss · Simon Willison · Aug 17, 15:21

**Background**: Biblio is a used and rare book marketplace founded in 2000, connecting professional antiquarian booksellers with buyers. Since 2025, there have been widespread reports of price-insensitive anonymous bulk orders for books, widely suspected to be AI companies scanning them for training data, as previously covered by Simon Willison regarding Anthropic's book scanning in June 2025.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Biblio.com">Biblio.com - Wikipedia</a></li>
<li><a href="https://www.biblio.com/">Used Books and Rare Books from Antiquarian Booksellers - Biblio</a></li>

</ul>
</details>

**Tags**: `#AI training`, `#Amazon`, `#copyright`, `#investigation`, `#data sourcing`

---

<a id="item-5"></a>
## [Researcher Exposes Evaluation Tricks That Inflate KV Compression Results](https://www.reddit.com/r/MachineLearning/comments/1vqqqcs/how_to_make_any_sparse_attention_kv_compression/) ⭐️ 8.0/10

An experienced researcher posted a candid thread on X, shared to Reddit, detailing common evaluation tricks that make sparse attention and KV cache compression methods look better than they actually are. The post lists specific practices such as using easy single-hop retrieval setups, never isolating the contribution of a new method, hiding failures behind aggregate metrics, and testing on saturated benchmarks. These evaluation practices can mislead the research community and practitioners, leading to unfair comparisons and overstated efficiency gains in efficient attention methods. The post underscores the urgent need for more rigorous, transparent benchmarking in the field of long-context Transformer inference. The author admits to being guilty of such practices while trying to improve. Specific tricks revealed include using needle-in-a-haystack tasks with repeated or irrelevant context, keeping the baseline's local window size but tuning your own, using LLM-written Triton kernels for your method but not the baselines, moving the question before the context, and reporting only the aggregate RULER score while hiding degradation on NIAH-MK3.

reddit · r/MachineLearning · /u/korec1234 · Aug 17, 12:18

**Background**: KV cache compression and sparse attention aim to reduce memory usage and computation when Transformers process long contexts. Sparse attention restricts each query to attend to a subset of keys/values, lowering the quadratic O(N²) complexity, while KV compression evicts or compresses cached key-value pairs after the full context is prefilled. Benchmarks like RULER include tasks such as needle-in-a-haystack and QA. The post warns that many of these settings are too cooperative — even sliding-window attention can pass them, making reported compression ratios misleading.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/npp369/KVCacheCompression">GitHub - npp369/KVCacheCompression: KV - cache compression ...</a></li>
<li><a href="https://grokipedia.com/page/Sparse_Attention">Sparse Attention</a></li>

</ul>
</details>

**Tags**: `#KV Cache Compression`, `#Sparse Attention`, `#Evaluation`, `#Efficient Attention`, `#Machine Learning`

---

<a id="item-6"></a>
## [Railway Line-Scan Camera Turns Tracks Into a Flatbed Scanner](https://philo.gay/linecam/) ⭐️ 7.0/10

A creative project, hosted at philo.gay/linecam, uses a line-scan camera mounted on railway movement to capture the landscape along tracks, producing flatbed-scanner-like panoramic images. The railway itself supplies the scanning motion that normally comes from a flatbed scanner's moving head. This project demonstrates how everyday motion can be repurposed as a creative imaging tool, sitting at the intersection of photography, hardware hacking, and visual art. Its accessible technique and engaging write-up are inspiring hobbyists to share related experiments and historical precedents. Line-scan cameras capture one-dimensional stripes and rely on relative motion — here, the train's movement along the track — to build a two-dimensional image. As commenters note, the in-progress 'scans' are themselves a compelling stretching of time and space, not just final panoramas.

hackernews · otherayden · Aug 18, 12:43 · [Discussion](https://news.ycombinator.com/item?id=49344825)

**Background**: A line-scan camera produces two-dimensional images from a line of sensors, using relative motion between camera and subject to build the image line by line. This is the same principle behind push broom scanners in satellite remote sensing and the moving sensor heads in flatbed document scanners. In this project, the railway track supplies the motion axis, turning the passing landscape into a continuous panoramic 'scan'.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Line-scan_camera">Line-scan camera</a></li>
<li><a href="https://en.wikipedia.org/wiki/Push_broom_scanner">Push broom scanner</a></li>

</ul>
</details>

**Discussion**: Commenters responded enthusiastically, sharing related work such as filming light at 2 billion fps, a 2008 iSight-based train scanner, and manually spliced frame animations. Overall sentiment is positive and inspiring, with several people noting how similar ideas arise independently and suggesting applications such as capturing from freight-train journeys.

**Tags**: `#photography`, `#imaging`, `#creative-hacking`, `#railway`, `#line-scan`

---

<a id="item-7"></a>
## [Linux 7.3 Improves Performance When Running Out of vRAM](https://pixelcluster.dev/VRAM-Overcommit/) ⭐️ 7.0/10

The Linux kernel 7.3 introduces performance improvements specifically for situations where video memory (vRAM) is exhausted. The update aims to reduce freezes and improve system responsiveness when applications oversubscribe GPU memory. This improvement is significant for users running memory-intensive workloads such as AI models and large data processing, where vRAM overcommit often leads to system slowdowns or crashes. It also highlights the ongoing divergence in how operating systems handle out-of-memory conditions, a key factor for desktop and server users alike. The specific technical details of the vRAM overcommit improvements are not fully described, but community discussion indicates they address OOM (out-of-memory) handling behavior. The update is seen as incremental rather than a major breakthrough, with some users comparing it to memory management on Windows and macOS.

hackernews · flaburgan · Aug 18, 07:51 · [Discussion](https://news.ycombinator.com/item?id=49342719)

**Background**: Video RAM (vRAM) is the dedicated memory on a graphics card, used for storing textures, frame buffers, and increasingly for compute workloads like AI inference. When an application requests more vRAM than is physically available, the system must handle the oversubscription gracefully, typically by swapping or killing processes. Linux, Windows, and macOS each have different strategies for this 'out-of-memory' scenario, which can affect stability and user experience. This kernel update focuses on improving Linux's behavior in these situations.

**Discussion**: The community response has been largely positive, with users praising the article and expressing enthusiasm for upcoming kernel improvements. Some commenters shared their personal experiences with OOM handling on Windows and macOS, while others noted the stark contrast between the Linux community's eagerness for kernel updates and Windows users' apprehension about Patch Tuesday. A side note also credited young transgender people for significant contributions to low-level performance engineering.

**Tags**: `#Linux`, `#kernel`, `#VRAM`, `#memory-management`, `#performance`

---

<a id="item-8"></a>
## [Meta Files Patent for Facial Recognition and Automatic Recording of People](https://www.privacyguides.org/news/2026/08/17/meta-files-patent-for-facial-recognition-automatic-recording-of-people/) ⭐️ 7.0/10

Meta has filed a patent covering facial recognition and automatic recording of people, according to a report by Privacy Guides. The filing has sparked privacy concerns, although it is a patent application rather than a shipped product. If such technology is implemented, Meta's smart glasses or other wearables could identify and record people without their explicit consent. This would significantly expand surveillance capabilities and raise legal and ethical questions around biometric data collection. The patent covers automatic recording of people and facial recognition, potentially tied to Meta's Ray-Ban smart glasses product line. Commenters noted that researchers earlier this year found a dormant facial-recognition pipeline inside the Meta AI app, built and shipped without an opt-in.

hackernews · DeepLogin · Aug 18, 12:23 · [Discussion](https://news.ycombinator.com/item?id=49344654)

**Background**: Facial recognition is a biometric technology that identifies or verifies individuals from images or video. Companies like Meta have faced repeated criticism over privacy practices, and patent filings are often broader than actual products, but they signal strategic intent. Smart glasses with cameras make bystander recording and recognition a growing concern.

**Discussion**: Community reaction was overwhelmingly negative, with users calling the patent 'worthless' and expressing distrust of Meta's surveillance practices. Some highlighted a dormant facial-recognition pipeline found in the Meta AI app, while others predicted a future without privacy and compared the glasses to portable Flock cameras. There was also debate over why Ray-Ban seems to escape backlash despite Meta's involvement.

**Tags**: `#privacy`, `#facial recognition`, `#meta`, `#patents`, `#surveillance`

---

<a id="item-9"></a>
## [How Bluesky draws its logo on screenshots](https://timmarinin.net/2026/bluesky-screenshots/) ⭐️ 7.0/10

A technical breakdown of how Bluesky adds its logo to screenshots, igniting discussion on whether apps should alter screenshots of user screens.

hackernews · gavide · Aug 17, 22:20 · [Discussion](https://news.ycombinator.com/item?id=49338459)

**Tags**: `#bluesky`, `#screenshots`, `#ux`, `#branding`, `#technical-deep-dive`

---

<a id="item-10"></a>
## [Developer Unbricks Framework 13 AMD Laptop with $20 Tools](https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/) ⭐️ 6.0/10

A repair guide published on quantum5.ca documents how to recover a bricked Framework 13 AMD Ryzen 7040 laptop using about $20 worth of tools, likely an SPI programmer and SOIC clip. The post demonstrates a successful external reflash of the BIOS chip rather than replacing the mainboard. This case shows both the promise and the limits of modular, repairable laptops: the hardware is serviceable with cheap tools, but the firmware lacks a simple recovery mechanism, forcing users into invasive procedures. It reignites debate over whether modular design truly reduces waste when spare parts and repair options remain tightly controlled by the manufacturer. The repair method involves clipping onto the SPI flash chip and using an external programmer such as a CH341A or a Raspberry Pi Pico to rewrite the BIOS directly. The author notes that Framework's AMD 7040 board has no user-accessible BIOS recovery mode, so this level of hardware intervention is necessary after a failed update.

hackernews · jp_sc · Aug 18, 13:18 · [Discussion](https://news.ycombinator.com/item?id=49345220)

**Background**: Framework laptops are designed to be user-upgradeable and repairable, with standardized parts and clear labeling. A 'bricked' laptop usually results from a failed firmware update that corrupts the BIOS. External SPI programming is a well-known repair technique: a programmer is attached to the flash chip via a clip, and the firmware image is written directly, bypassing the dead boot process.

<details><summary>References</summary>
<ul>
<li><a href="https://quantum5.ca/2026/08/16/fixing-bricked-amd-7040-series-framework-13-laptop-with-20-tools/">Fixing a bricked AMD 7040 series Framework 13 ” laptop with $20 tools</a></li>
<li><a href="https://winraid.level1techs.com/t/guide-how-to-use-a-ch341a-spi-programmer-flasher/33041">[Guide] How to Use a CH341A SPI Programmer / Flasher</a></li>
<li><a href="https://libreboot.org/docs/install/spi.html">Libreboot – Read/write 25XX NOR flash via SPI protocol</a></li>

</ul>
</details>

**Discussion**: Commenters largely appreciate the guide but express mixed feelings about Framework. One user regrets buying a Framework because replacement parts are only available from the company and often out of stock, while another points out that even enterprise laptops like Dell Precision are well-labeled and repairable. Several criticize the lack of A/B flash updates, and one commenter argues that if custom firmware voids warranty, official updates that brick a device should extend it, even suggesting small claims court.

**Tags**: `#hardware`, `#repair`, `#framework-laptop`, `#firmware`, `#repairability`

---

<a id="item-11"></a>
## [Fairphone Now Officially Available for Direct Purchase in the US](https://www.fairphone.com/nl/stories/the-fairphone-gen-6-is-all-about-giving-you-more) ⭐️ 6.0/10

Fairphone has officially launched direct sales in the United States, offering its repairable, ethical smartphones straight to US consumers. The current model highlighted is the Fairphone (Gen. 6+), which features upgraded internals while maintaining the brand's modular repairability. US consumers who value sustainability and repairability now have a more convenient way to buy Fairphone devices without relying on third-party resellers. This could pressure other smartphone makers to consider more modular, longer-lasting designs in a major market. The Fairphone (Gen. 6+) supports the full range of T-Mobile frequency bands, including LTE bands 12/71 and 5G n71, which are critical for coverage outside cities. Some privacy-focused groups, such as the GrapheneOS project, have expressed disappointment with Fairphone's handling of privacy, security, and updates.

hackernews · Vinnl · Aug 18, 12:42 · [Discussion](https://news.ycombinator.com/item?id=49344811)

**Background**: Fairphone is a Dutch electronics manufacturer that designs smartphones with a focus on ethical sourcing and modular repairability, often scoring top marks in repairability rankings. In the past, US customers could only buy Fairphone devices through resellers like Murena, so this direct sales launch expands access. The company also partners with Murena to offer a privacy-focused /e/ OS version that excludes Google apps and services.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Fairphone">Fairphone - Wikipedia</a></li>
<li><a href="https://factually.co/product-reviews/electronics-tech/best-degoogled-phones-longevity-repairability-2026-roundup-3d6dda">Best DeGoogled Phones for Longevity and Repairability ... | Factually</a></li>
<li><a href="https://www.fairphone.com/open-source">Fairphone Open Source | Transparency, Longevity & Privacy</a></li>

</ul>
</details>

**Discussion**: Commenters are split: some welcome the direct US availability and praise the thorough T-Mobile band support, while others point out that Fairphone products have been available in the US through resellers for years, so the change is mainly about buying direct. The discussion also covers GrapheneOS's reduced interest in Fairphone hardware, and a community note that the Fairphone 6+ shares the camera module with the Fairphone 6, which recently received camera support in postmarketOS.

**Tags**: `#Fairphone`, `#consumer electronics`, `#repairability`, `#sustainability`, `#US availability`

---

<a id="item-12"></a>
## [Rethinking Database Programming: Coexisting with SQL via Acadia](https://acadia.engineering/blog/rethinking-database-programming) ⭐️ 6.0/10

A new blog post from Acadia Engineering proposes a database programming language design that aims to coexist with SQL rather than replace it. The proposed language highlights features such as sum types and first-class enforced row-level security. This proposal directly addresses long-standing pain points in SQL and ORM-based database programming, potentially influencing how developers model and secure data. However, the skeptical community response underscores that practical interoperability and feature parity remain major hurdles for any SQL alternative. According to the discussion, sum types in the proposed language use a custom binary encoding, which likely complicates interoperability with other languages. Commenters also note that defining schemas in a non-SQL language tends to lag behind native database features such as partitioning, compression, and advanced constraints.

hackernews · honungsburk · Aug 18, 07:28 · [Discussion](https://news.ycombinator.com/item?id=49342530)

**Background**: SQL has been the standard language for relational databases for decades, but it has well-known limitations in expressiveness and type safety. ORMs were created to bridge the gap between application code and relational schemas, yet they often introduce their own impedance mismatch. This blog post appears to propose a new programming model that integrates database concerns more deeply into a general-purpose language while still trying to maintain compatibility with existing SQL-based systems.

**Discussion**: Community sentiment is mixed but largely skeptical. Some commenters note that many attempts to replace SQL have failed and argue that the relational model itself is solid, while others worry that the claimed interop with SQL is only a temporary stepping stone toward full adoption of the new language. There is also appreciation for features like sum types and first-class enforced row-level security, though migration and variant-removal strategies remain unclear.

**Tags**: `#database`, `#sql`, `#programming-languages`, `#orm`

---

<a id="item-13"></a>
## [Diffusion Model Runs on 264KB RAM Microcontroller with FPGA INT8 MAC Engines](https://www.reddit.com/r/MachineLearning/comments/1vrk7t5/trained_an_diffusion_model_that_runs_on_264kb_of/) ⭐️ 6.0/10

The developer trained a diffusion model that generates 32x32 pixel images on a Shrike lite microcontroller with only 264KB of SRAM. They used the onboard FPGA to create two parallel INT8 MAC engines with 16-bit accumulation, but memory bandwidth bottlenecks made the FPGA-accelerated version slower (~220 s/image) than the MCU-only version (~70 s/image). This experiment shows that diffusion models, which are typically compute- and memory-hungry, can be pushed onto severely constrained embedded devices with careful quantization and hardware acceleration. It highlights the trade-offs of edge-AI acceleration, where memory bandwidth can negate compute gains, which is relevant for low-power and on-device ML. The Shrike lite combines an RP2040 MCU with a 1120-LUT FPGA; the author used the FPGA to build two INT8 MAC engines with 16-bit accumulation to offload convolution/matrix operations. Heavy quantization and SRAM limits produced noisy artifacts, though some generated images were "cool." The full case study is linked in the post.

reddit · r/MachineLearning · /u/PandaBean18 · Aug 18, 09:26

**Background**: Diffusion models generate images by iteratively denoising random noise, and normally require large GPU memory and billions of FLOPs, making them a poor fit for microcontrollers. Quantization reduces model precision (e.g., from 32-bit float to 8-bit integers) to shrink memory and compute demands, but it introduces errors. The Shrike lite is a low-cost open-source development board that pairs an RP2040 MCU (with 264KB SRAM) with a small FPGA, intended for hobbyists and embedded developers to experiment with custom hardware acceleration.

<details><summary>References</summary>
<ul>
<li><a href="https://d25yug97gus487.cloudfront.net/latest/boards/vicharak/shrike_lite/doc/index.html">Shrike - lite — Zephyr Project Documentation</a></li>
<li><a href="https://github.com/vicharak-in/shrike-lite">GitHub - vicharak-in/ shrike - lite : Low cost microcontroller + FPGA...</a></li>
<li><a href="https://www.allaboutcircuits.com/technical-articles/neural-network-quantization-what-is-it-and-how-does-it-relate-to-tiny-machine-learning/">Neural Network Quantization : What Is It and How Does It Relate to...</a></li>

</ul>
</details>

**Tags**: `#diffusion models`, `#edge AI`, `#microcontrollers`, `#quantization`, `#FPGA`

---

<a id="item-14"></a>
## [SineKAN: A KAN Variant Using Sinusoidal Activation Functions](https://www.reddit.com/r/MachineLearning/comments/1vqdode/r_sinekan_kolmogorovarnold_networks_using/) ⭐️ 6.0/10

The Reddit post shares SineKAN, a Kolmogorov-Arnold Network variant that replaces B-spline activations with sinusoidal functions. The project includes an arXiv paper, a GitHub repository, and a peer-reviewed publication in MDPI Mathematics. SineKAN demonstrates that KANs are not limited to spline-based representations, opening the door to alternative activation functions with different trade-offs in accuracy, smoothness, and computational cost. This incremental research helps the community understand which function bases work best for KAN architectures. The linked MDPI paper appears as Mathematics 2025, 13(19), 3157, and the code is available at github.com/ereinha/SineKAN. The original author noted they were wondering whether sinusoids had been tried instead of B-splines, and found that it had already been done.

reddit · r/MachineLearning · /u/jacobgorm · Aug 17, 00:46

**Background**: Kolmogorov-Arnold Networks (KANs) are a neural network architecture inspired by the Kolmogorov-Arnold representation theorem, which states that multivariate functions can be expressed as superpositions of univariate functions. Unlike traditional multilayer perceptrons that use fixed activations and linear weights, KANs use learnable univariate functions, often B-splines, as weights. B-splines are piecewise polynomial basis functions widely used in numerical analysis and computer graphics.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Kolmogorov-Arnold_Networks">Kolmogorov-Arnold Networks</a></li>
<li><a href="https://grokipedia.com/page/Kolmogorov-Arnold_Networks">Kolmogorov-Arnold Networks</a></li>
<li><a href="https://en.wikipedia.org/wiki/B-spline">B-spline</a></li>

</ul>
</details>

**Tags**: `#KAN`, `#neural networks`, `#activation functions`, `#machine learning`, `#research`

---