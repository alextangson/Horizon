# Horizon Daily - 2026-04-03

> From 61 items, 16 important content pieces were selected

---

1. [Google releases Gemma 4 open models with reasoning, multimodal, and tool calling capabilities](#item-1) ⭐️ 9.0/10
2. [Google DeepMind releases Gemma 4 open models with vision and audio capabilities](#item-2) ⭐️ 9.0/10
3. [Google DeepMind releases Gemma 4 multimodal open model family](#item-3) ⭐️ 9.0/10
4. [Former Azure Core engineer critiques decisions that eroded trust in Azure.](#item-4) ⭐️ 8.0/10
5. [Qwen3.6-Plus AI model released with focus on real-world agent capabilities](#item-5) ⭐️ 8.0/10
6. [AMD launches Lemonade, an open-source local LLM server with GPU and NPU support for multi-modal AI.](#item-6) ⭐️ 8.0/10
7. [LinkedIn scans users' browser extensions and transmits data to its servers](#item-7) ⭐️ 8.0/10
8. [Heretic's ARA method bypasses Gemma 4's alignment defenses within 90 minutes of release](#item-8) ⭐️ 8.0/10
9. [Gemma 4 multimodal models with 1B, 13B, and 27B parameters introduce vision capabilities](#item-9) ⭐️ 8.0/10
10. [Cursor 3 is announced as a major update to the AI-powered code editor.](#item-10) ⭐️ 7.0/10
11. [Three Chinese autonomous driving companies secretly file for Hong Kong IPOs ahead of Tesla FSD entry](#item-11) ⭐️ 7.0/10
12. [Granola AI note-taking app exposes notes via public links and uses them for AI training by default.](#item-12) ⭐️ 7.0/10
13. [Kintsugi shuts down after failing to get FDA clearance for depression-detecting AI, releases tech as open-source.](#item-13) ⭐️ 7.0/10
14. [Simon Willison Discusses AI Inflection Point and Agentic Engineering on Lenny's Podcast](#item-14) ⭐️ 7.0/10
15. [Gemma 4 models demonstrate extended reasoning capabilities when prompted for maximum thinking length](#item-15) ⭐️ 7.0/10
16. [Aggressive uncensored variants of Google's Gemma 4 models released with full multimodal support.](#item-16) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Google releases Gemma 4 open models with reasoning, multimodal, and tool calling capabilities](https://deepmind.google/models/gemma/gemma-4/) ⭐️ 9.0/10

Google has released Gemma 4, a series of open models that feature thinking/reasoning, multimodal, and tool calling capabilities, with community-provided benchmarks and implementation guides available. This release is significant as it advances open AI models by integrating reasoning and multimodal features, potentially enhancing accessibility and performance for developers and researchers in the AI ecosystem. Community benchmarks show Gemma 4 models like the 31B variant achieving high scores on tests such as MMLUP (85.2%) and MMMLU (88.4%), but some users report issues like the gemma-4-31b model outputting only "---\n" in certain setups.

hackernews · jeffmcjunkin · Apr 2, 16:10

**Background**: Gemma is a family of open models based on Google's Gemini research, designed to provide accessible AI tools comparable to models like Meta's Llama. Multimodal AI refers to systems that process multiple data types, such as text and images, simultaneously, enhancing AI's ability to understand and interact with complex inputs. Community benchmarks are standardized tests used to evaluate large language models on various tasks, helping users compare performance across different models.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2403.08295v4">Gemma: Open Models Based on Gemini Research and Technology</a></li>
<li><a href="https://techcrunch.com/2024/05/14/google-announces-gemma-2-a-27b-parameter-version-of-its-open-model-launching-in-june/">Google announces Gemma 2, a 27B-parameter version of its open</a></li>
<li><a href="https://appscrip.com/blog/multimodal-ai/">Multimodal AI: Transform Business Operations This Year</a></li>

</ul>
</details>

**Discussion**: Community members have shared positive experiences with quantized versions and performance, such as danielhanchen noting effective quants and optimal settings, and simonw praising the 26b-a4b model's output quality on a laptop. However, concerns include issues with the gemma-4-31b model producing broken outputs and benchmark comparisons highlighting variations in performance across different Gemma 4 variants.

**Tags**: `#AI/ML`, `#Open Source`, `#Large Language Models`, `#Benchmarks`, `#Multimodal AI`

---

<a id="item-2"></a>
## [Google DeepMind releases Gemma 4 open models with vision and audio capabilities](https://simonwillison.net/2026/Apr/2/gemma-4/#atom-everything) ⭐️ 9.0/10

Google DeepMind released Gemma 4 on April 2, 2026, a set of four Apache 2.0 licensed open models with vision capabilities, including sizes from 2B to 31B parameters and a 26B-A4B Mixture-of-Experts variant. The models feature Per-Layer Embeddings (PLE) for enhanced parameter efficiency and support native audio input for speech recognition in the smaller E2B and E4B models. This release represents a significant advancement in creating small yet capable AI models, demonstrating that parameter efficiency is becoming increasingly important for on-device deployments and practical applications. The open licensing and multimodal capabilities make these models accessible for developers to build applications with vision, audio, and text understanding in resource-constrained environments. The smaller models (E2B and E4B) use Per-Layer Embeddings to maximize parameter efficiency, with 'effective' parameter counts much smaller than total parameters due to embedding tables being used only for quick lookups. While the 2B, 4B, and 26B-A4B models work well in LM Studio, the 31B model had issues generating proper outputs during testing, and audio input functionality is not yet available in popular local inference tools like LM Studio or Ollama.

rss · Simon Willison · Apr 2, 18:28

**Background**: Gemma is Google's family of open large language models designed to be lightweight and efficient while maintaining strong performance. Mixture of Experts (MoE) is a machine learning technique that divides a model into separate sub-networks or 'experts' that specialize in different aspects of the problem space, allowing for more efficient parameter usage. Per-Layer Embeddings (PLE) is a novel architecture enhancement that gives each decoder layer its own small embedding for every token, improving memory efficiency without adding more layers or parameters to the model.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Mixture_of_experts">Mixture of experts - Wikipedia</a></li>
<li><a href="https://ai.google.dev/gemma/docs/gemma-3n">Gemma 3n model overview | Google AI for Developers</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Machine Learning`, `#Open Source`, `#Google`, `#Model Efficiency`

---

<a id="item-3"></a>
## [Google DeepMind releases Gemma 4 multimodal open model family](https://www.reddit.com/r/LocalLLaMA/comments/1salgre/gemma_4_has_been_released/) ⭐️ 9.0/10

Google DeepMind has released Gemma 4, a multimodal open model family that handles text and image input with audio support on small models, featuring native thinking and tool calling capabilities. The release includes four model sizes (E2B, E4B, 26B A4B, and 31B) with both Dense and Mixture-of-Experts architectures, supporting up to 256K token context windows and over 140 languages. This release democratizes access to state-of-the-art multimodal AI by making advanced capabilities available across devices from phones to servers, potentially accelerating innovation in open-source AI development. The combination of multimodal understanding, native thinking, and tool calling positions Gemma 4 as a versatile foundation for various AI applications including coding, reasoning, and content generation. The models are available in GGUF format through Hugging Face collections, with specific guidance recommending temperature=1.0, top_p=0.95, and top_k=64 parameters for optimal performance. Unsloth provides both GGUF files and integration with Unsloth Studio for efficient deployment, though the content indicates the architectural details section was truncated in the provided material.

reddit · r/LocalLLaMA · jacek2023 · Apr 2, 16:01

**Background**: Gemma is Google DeepMind's family of open-source language models designed to provide accessible AI capabilities to developers and researchers. Multimodal models (MLLMs) can process and understand multiple types of input such as text, images, and audio, representing a significant advancement beyond text-only language models. Tool calling allows language models to interact with external functions and APIs to perform tasks beyond their core capabilities, while native thinking refers to models designed with AI-first architectural principles from the ground up.

<details><summary>References</summary>
<ul>
<li><a href="https://www.turingpost.com/p/10-open-mllms">10 Open Multimodal Models</a></li>
<li><a href="https://langbase.com/docs/features/tool-calling">Tool calling - Features - Langbase Docs</a></li>
<li><a href="https://www.cognizant.com/us/en/aem-i/how-to-think-and-act-like-an-ai-native-business">How to think—and act—like an AI-native business | Cognizant</a></li>

</ul>
</details>

**Discussion**: Community members expressed enthusiasm about Google's commitment to open weights and shared practical implementation details, including optimal parameter settings and deployment resources. One comment highlighted the seamless integration with Unsloth Studio and provided links to GGUF files and running guides, demonstrating active technical engagement with the release.

**Tags**: `#AI`, `#Large Language Models`, `#Multimodal AI`, `#Open Source`, `#Google DeepMind`

---

<a id="item-4"></a>
## [Former Azure Core engineer critiques decisions that eroded trust in Azure.](https://isolveproblems.substack.com/p/how-microsoft-vaporized-a-trillion) ⭐️ 8.0/10

A former Azure Core engineer published a critique detailing specific decisions that undermined trust in Azure, based on personal experience from within Microsoft. The article highlights internal practices and choices that contributed to trust erosion in the cloud platform. This insider perspective sheds light on potential systemic issues in Azure's engineering culture and decision-making, which could impact customer confidence, adoption, and Microsoft's competitive position in the cloud market. Trust is critical for cloud platforms as they handle sensitive data and critical infrastructure. The critique is based on firsthand experience from an engineer involved in Azure Core services, focusing on decisions rather than technical failures. It does not specify exact dates or versions but draws from real-world scenarios within Microsoft's operations.

hackernews · axelriet · Apr 2, 16:00

**Background**: Azure is Microsoft's cloud computing platform offering services like computing, storage, and analytics. Azure Core engineers typically work on foundational services that ensure scalability, reliability, and security. Engineering culture in cloud services emphasizes autonomy, mastery, and purpose to foster innovation and trust, as highlighted in industry discussions on platforms like AWS and McKinsey insights.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.aws.amazon.com/prescriptive-guidance/latest/transitioning-to-multiple-aws-accounts/engineering-cultural-considerations.html">Engineering cultural considerations - AWS Prescriptive Guidance</a></li>
<li><a href="https://www.mckinsey.com/capabilities/tech-and-ai/our-insights/building-an-engineering-culture-and-resilient-technology">Building an engineering culture and resilient technology</a></li>

</ul>
</details>

**Tags**: `#Azure`, `#Cloud Computing`, `#Trust`, `#Microsoft`, `#Engineering Culture`

---

<a id="item-5"></a>
## [Qwen3.6-Plus AI model released with focus on real-world agent capabilities](https://qwen.ai/blog?id=qwen3.6) ⭐️ 8.0/10

Qwen3.6-Plus is a new AI model release from the Qwen team, specifically designed to enhance real-world agent capabilities, such as autonomous task execution and reasoning. It is currently available as a hosted-only model, with benchmarks showing strong performance, including a score of 23/25 on an agentic benchmark via OpenRouter. This release matters because it advances the development of practical AI agents that can operate autonomously in real-world scenarios, competing with models like Claude Opus and Gemini Pro. It reflects a strategic shift for Qwen from open-weight models to hosted services, potentially impacting the open-source AI ecosystem and user adoption. The model is not open-weight but hosted-only, accessible through platforms like OpenRouter and Alibaba Cloud's Model Studio API. Benchmark comparisons have sparked debate, as Qwen3.6-Plus is evaluated against older versions of competitors like Opus 4.5 and Gemini Pro 3.0, rather than the latest releases.

hackernews · pretext · Apr 2, 14:28

**Background**: Qwen is a series of open-source large language models (LLMs) developed by Alibaba, known for their multilingual and multimodal capabilities. Real-world AI agents are systems that use LLMs to perform autonomous tasks, such as coding or data analysis, often evaluated through benchmarks that measure reasoning and execution. The Qwen series includes models like Qwen3.5 and Qwen3-VL, which integrate visual and agentic features.

<details><summary>References</summary>
<ul>
<li><a href="https://www.geeky-gadgets.com/open-source-ai-qwen3-breakthrough/">QWEN3 Explained : How This AI Model is Outperforming Its Rivals</a></li>
<li><a href="https://qwen3-vl.com/">Qwen3-VL - Newest Multimodal text-image AI model</a></li>
<li><a href="https://medium.com/@adnanmasood/evaluation-methodologies-for-llm-based-agents-in-real-world-applications-83bf87c2d37c">Evaluation Methodologies for LLM-Based Agents in Real-World ...</a></li>

</ul>
</details>

**Discussion**: Community sentiment is mixed, with some users expressing anger over the hosted-only model strategy, viewing it as a pivot away from Qwen's open-source roots. Others highlight strong benchmark results, such as a 23/25 score on agentic tests, and debate the fairness of comparisons against older competitor models like Opus 4.5. Additional insights include practical usage examples, like generating code via APIs, and concerns about billing and accessibility.

**Tags**: `#AI-Models`, `#Machine-Learning`, `#Open-Source`, `#Benchmarking`, `#LLM-Agents`

---

<a id="item-6"></a>
## [AMD launches Lemonade, an open-source local LLM server with GPU and NPU support for multi-modal AI.](https://lemonade-server.ai/) ⭐️ 8.0/10

AMD has officially backed and released Lemonade, an open-source local LLM server that supports inference on GPU and NPU hardware, with multi-modal capabilities for processing text, images, and audio. It offers support for various backends like ROCm and Vulkan, aiming to simplify local AI deployment. This matters because it addresses a significant gap in the ecosystem for AMD hardware users, providing an official, optimized solution for local AI inference that could enhance performance and accessibility. It also promotes multi-modal AI integration, potentially streamlining development for applications requiring combined text, image, and audio processing. Lemonade supports multiple inference backends including ROCm for AMD GPUs and Vulkan, and it can run on CPU, GPU, and NPU, though community feedback suggests NPU performance may be limited for larger models. It features OpenAI-compatible endpoints and aims to unify orchestration for multi-modal tasks, reducing the complexity of managing separate services.

hackernews · AbuAssar · Apr 2, 11:04

**Background**: Local LLM servers are software that deploy large language models directly on client hardware, allowing multiple applications to share a single model without each loading it into RAM separately. NPUs (Neural Processing Units) are specialized hardware designed to efficiently execute AI inference tasks, offering benefits like low latency and energy efficiency, as seen in AMD's Ryzen AI systems. Multi-modal AI refers to systems that can process and generate multiple types of data, such as text, images, and audio, moving beyond single-modality limitations.

<details><summary>References</summary>
<ul>
<li><a href="https://lemonade-server.ai/server/concepts.html">Local LLM Server Concepts | lemonade</a></li>
<li><a href="https://www.amd.com/en/developer/resources/technical-articles/2025/ai-inference-acceleration-on-ryzen-ai-with-quark.html">AI Inference Acceleration on Ryzen AI NPU with AMD Quark</a></li>
<li><a href="https://self.md/concepts/local-llm-runtimes/">Local LLM Runtimes: When to Use Ollama vs vLLM | self.md</a></li>

</ul>
</details>

**Discussion**: Community sentiment is generally positive, with users praising Lemonade's development pace and multi-modal bundling for simplifying local AI setups. Key discussions include practical experiences with NPU vs. dGPU performance, where some note NPU bottlenecks for larger models, and comparisons to tools like Ollama, highlighting Lemonade's focus on unified orchestration over just model serving.

**Tags**: `#LLM`, `#AMD`, `#Open Source`, `#Inference Server`, `#GPU`

---

<a id="item-7"></a>
## [LinkedIn scans users' browser extensions and transmits data to its servers](https://browsergate.eu/) ⭐️ 8.0/10

LinkedIn's JavaScript code silently scans thousands of installed browser extensions by ID when users open LinkedIn in Chrome-based browsers, encrypts the collected data, and transmits it to LinkedIn's servers. This scanning includes non-LinkedIn related tools such as content filters, political taggers, and accessibility extensions. This practice represents a significant privacy intrusion by a major professional platform, potentially enabling detailed user profiling and raising concerns about trust violations in data collection. It highlights broader industry trends where platforms may overreach in gathering user data under the guise of security or functionality. The scanning occurs automatically without user consent and targets specific extension IDs, including tools like PordaAI (Islamic content filter), Anti-Zionist Tag, and simplify (neurodivergent accessibility tool). The data transmission uses encryption, but the purpose and retention policies of this collected extension data remain unclear.

hackernews · digitalWestie · Apr 2, 13:09

**Background**: Browser extensions are software add-ons that modify or enhance browser functionality, but they can pose security risks by accessing sensitive user data. Browser fingerprinting is a technique websites use to identify users based on unique browser configurations, including installed extensions. Many extensions have permissions to view and modify webpage data, making them potential vectors for data collection.

<details><summary>References</summary>
<ul>
<li><a href="https://cyberpedia.reasonlabs.com/EN/browser+extension+scans.html">What are Browser Extension Scans ? Staying Safe Online with...</a></li>
<li><a href="https://news.gatech.edu/news/2024/09/17/study-finds-thousands-browser-extensions-compromise-user-data">Study Finds Thousands of Browser Extensions Compromise User Data</a></li>
<li><a href="https://layerxsecurity.com/learn/browser-extension/">Browser Extension Security Risks and Best Practices - LayerX</a></li>

</ul>
</details>

**Discussion**: Community comments express strong concerns about privacy violations and trust erosion, with users noting the invasive nature of scanning non-LinkedIn extensions like content filters and accessibility tools. Some users share personal experiences of unauthorized profile creation, while others compare the practice to browser fingerprinting techniques.

**Tags**: `#privacy`, `#browser-security`, `#data-collection`, `#linkedin`, `#ethics`

---

<a id="item-8"></a>
## [Heretic's ARA method bypasses Gemma 4's alignment defenses within 90 minutes of release](https://www.reddit.com/r/LocalLLaMA/comments/1sanln7/pewgemma4e2bithereticara_gemma_4s_defenses/) ⭐️ 8.0/10

The Arbitrary-Rank Ablation (ARA) method developed by Heretic successfully bypassed Google's Gemma 4 model's alignment defenses just 90 minutes after the model's official release, enabling uncensored responses without apparent model degradation. The method uses matrix optimization to suppress refusal mechanisms in the model. This demonstrates how quickly new alignment defenses can be circumvented, raising serious questions about the robustness of current AI safety measures in major model releases. The rapid bypass highlights ongoing challenges in developing truly secure alignment techniques that can withstand adversarial attacks. The ARA method remains experimental and is not yet available in the PyPI version of Heretic, requiring installation from a specific GitHub branch. Early experiments suggest removing `mlp.down_proj` from target components in the configuration may improve ablation effectiveness.

reddit · r/LocalLLaMA · -p-e-w- · Apr 2, 17:19

**Background**: Gemma is Google's family of open language models known for strong alignment features that prevent harmful or unwanted outputs. Alignment refers to techniques that make AI systems behave according to human values and safety guidelines. Arbitrary-Rank Ablation is a method that modifies specific components of neural networks to alter their behavior, in this case removing censorship mechanisms while attempting to preserve core capabilities.

<details><summary>References</summary>
<ul>
<li><a href="https://ai-manual.ru/article/ara-arbitrary-rank-ablation-kak-rabotaet-novyij-metod-detsenzurirovaniya-llm-ot-heretic-i-kak-ego-primenit/">ARA : метод децензурирования LLM от Heretic | AiManual</a></li>

</ul>
</details>

**Discussion**: Community members expressed appreciation for the technical work and requested versions for other model sizes, with one user humorously suggesting an extremely long model name combining multiple techniques. Another user questioned whether removing censorship might actually improve benchmark performance, indicating interest in potential performance benefits beyond just bypassing restrictions.

**Tags**: `#AI Alignment`, `#Model Security`, `#LLM Jailbreaking`, `#Gemma`, `#Machine Learning Research`

---

<a id="item-9"></a>
## [Gemma 4 multimodal models with 1B, 13B, and 27B parameters introduce vision capabilities](https://github.com/huggingface/transformers/pull/45192) ⭐️ 8.0/10

Google has released Gemma 4 multimodal models in three parameter sizes (1B, 13B, and 27B) that introduce two key vision processing innovations: fixed token budget image output and spatial 2D RoPE encoding. These models are available through Hugging Face's Transformers library with pretrained and instruction-tuned variants. This represents a significant advancement in multimodal AI by enabling more efficient and structured vision processing within language models, potentially improving image generation and understanding tasks. The availability of smaller parameter sizes (1B) makes multimodal capabilities more accessible for resource-constrained applications while maintaining the architecture's core benefits. The fixed token budget image output allows the model to generate images within a predetermined token limit, improving efficiency, while spatial 2D RoPE encodes visual information across both height and width dimensions. The architecture remains largely consistent with previous Gemma versions, with the vision processor being the primary innovation.

reddit · r/LocalLLaMA · TKGaming_11 · Apr 2, 15:21

**Background**: Multimodal models combine different input modalities like text and images to learn unified representations. RoPE (Rotary Position Embedding) is a position encoding method originally developed for text that has been extended to 2D spatial inputs for vision tasks. Fixed token budget approaches aim to optimize image representation within constrained computational resources, which is particularly important for efficient multimodal processing.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2603.25249v1">Semantic-Aware Prefix Learning for Token-Efficient Image</a></li>
<li><a href="https://arxiv.org/html/2504.06308v2">Rethinking RoPE: A Mathematical Blueprint for N-dimensional</a></li>
<li><a href="https://slds-lmu.github.io/seminar_multimodal_dl/c02-00-multimodal.html">Chapter 3 Multimodal architectures - GitHub Pages</a></li>

</ul>
</details>

**Discussion**: The community discussion shows technical interest with one user noting specific model variant identifiers in the Transformers PR, while another expresses excitement about the image output capability with a humorous reference to "Pico Banana." The comments indicate curiosity about the practical implementation details of the vision features.

**Tags**: `#multimodal-ai`, `#computer-vision`, `#large-language-models`, `#transformer-architecture`, `#huggingface`

---

<a id="item-10"></a>
## [Cursor 3 is announced as a major update to the AI-powered code editor.](https://cursor.com/blog/cursor-3) ⭐️ 7.0/10

Cursor 3 has been announced as a major version release of the AI-powered code editor, featuring new capabilities and model improvements, including the introduction of Composer 2 as a default model. This update aims to enhance the editor's AI-assisted development tools for better coding efficiency. This release is significant because Cursor is a popular tool in the AI-assisted development ecosystem, and major updates can influence developer workflows, productivity, and the competitive landscape with alternatives like Claude Code. It reflects ongoing trends in integrating advanced AI models into coding environments to streamline software engineering tasks. The update includes Composer 2 as a new default model, which users report as less intelligent than flagship models from OpenAI or Anthropic but more intuitive for certain tasks. Some community members express concerns about cost, with the enterprise plan being pricey and users hitting limits, leading to comparisons with free alternatives.

hackernews · adamfeldman · Apr 2, 18:13

**Background**: Cursor is an AI-powered code editor that integrates machine learning models to assist developers with tasks like code completion, debugging, and refactoring. It competes with tools like Claude Code, which is another AI-assisted development environment, and is part of a broader trend in using AI to enhance software engineering productivity. The editor often includes features such as chat interfaces and agent-based assistance to streamline coding workflows.

**Discussion**: The community discussion shows mixed sentiments, with some users praising Cursor for its efficiency and preferring it over Claude Code, while others criticize its high cost and question its value compared to free alternatives. Concerns are raised about the design direction leaning towards chat interfaces over code-centric features, and some users express disinterest in new agent-based approaches.

**Tags**: `#AI-assisted-development`, `#developer-tools`, `#code-editors`, `#machine-learning`, `#software-engineering`

---

<a id="item-11"></a>
## [Three Chinese autonomous driving companies secretly file for Hong Kong IPOs ahead of Tesla FSD entry](https://36kr.com/p/3748118174335747?f=rss) ⭐️ 7.0/10

Three Chinese autonomous driving companies - Momenta, QCraft, and Yuanrong Qixing - have secretly submitted IPO applications to the Hong Kong Stock Exchange, with Momenta's expected valuation exceeding 100 billion yuan and QCraft's latest valuation between $1.5-2 billion. Industry sources indicate these companies aim to go public before Tesla's Full Self-Driving (FSD) system enters the Chinese market, potentially creating an IPO surge in the second half of this year. This development signals a critical financing window for Chinese autonomous driving companies as they face intensified competition and capital constraints, with the timing strategically aimed at securing valuations before Tesla's market entry potentially reshapes the competitive landscape. The IPOs represent a pivotal moment for these companies to access public markets for continued R&D funding amid shifting investor preferences toward more generalized AI applications. The IPO process typically takes 6-9 months from submission to listing in Hong Kong, with Yuanrong Qixing reportedly submitting materials as early as late 2025, two months before Momenta. These companies are shifting their narratives from pure autonomous driving suppliers to broader "physical AI" or "soft-hard integration" players to appeal to changing capital market preferences.

rss · 36Kr · Apr 2, 08:10

**Background**: Autonomous driving companies develop technology for self-driving vehicles, with levels ranging from driver assistance (L2) to fully autonomous (L5). Navigate on Autopilot (NOA) is an advanced driver-assistance feature that enables automated lane changes and highway navigation. Tesla's Full Self-Driving (FSD) is a supervised autonomous driving system currently classified as Level 2, requiring driver attention despite its advanced capabilities. In China, autonomous driving suppliers typically partner with automakers to integrate their technology into production vehicles.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Self-driving_car">Self - driving car - Wikipedia</a></li>
<li><a href="https://www.tesla.com/fsd">Full Self - Driving (Supervised) | Tesla</a></li>
<li><a href="https://www.marketresearch.com/Research-in-China-v3266/China-Passenger-Car-Navigate-Autopilot-36819574/">China Passenger Car Navigate on Autopilot (NOA) Industry</a></li>

</ul>
</details>

**Tags**: `#autonomous-driving`, `#ipo`, `#china-tech`, `#automotive-industry`, `#investment`

---

<a id="item-12"></a>
## [Granola AI note-taking app exposes notes via public links and uses them for AI training by default.](https://www.theverge.com/ai-artificial-intelligence/906253/granola-note-links-ai-training-psa) ⭐️ 7.0/10

The AI-powered note-taking app Granola has default settings that make notes publicly accessible to anyone with a link and uses them for internal AI training unless users manually opt out, contradicting its claim of being 'private by default.' This issue was highlighted in a recent PSA, urging users to review their privacy settings. This matters because it raises significant privacy and security concerns for users who may unknowingly expose sensitive personal or professional data, and it highlights broader issues in AI ethics regarding default data usage for training without explicit consent. It could impact trust in AI applications and prompt regulatory scrutiny over data handling practices. The default settings apply to all non-enterprise customers, and notes are viewable via generated links without additional authentication. Users must manually disable these features in privacy settings to protect their data, as there is no automatic opt-out mechanism.

rss · The Verge - AI · Apr 2, 21:56

**Background**: Granola is an AI-powered note-taking app that uses machine learning to assist users in organizing and summarizing notes. Many cloud-based applications use link-based access control for sharing, but best practices typically require explicit user permission for public access and data usage. AI training on user data is common in apps to improve models, but it often involves opt-in or transparent consent mechanisms to address privacy concerns.

<details><summary>References</summary>
<ul>
<li><a href="https://www.theverge.com/ai-artificial-intelligence/906253/granola-note-links-ai-training-psa">PSA: Anyone with a link can view your Granola notes by default</a></li>
<li><a href="https://aitoolly.com/ai-news/article/2026-04-03-granola-privacy-alert-ai-notes-viewable-via-link-and-used-for-training-by-default">Granola AI Privacy PSA: Notes Viewable via Link | AIToolly</a></li>
<li><a href="https://aidigitalspace.com/ai-training-on-your-data-opt-out/">AI Training on Your Data: How to Opt Out on Every Platform</a></li>

</ul>
</details>

**Tags**: `#AI Ethics`, `#Privacy`, `#Software Security`, `#User Data`, `#PSA`

---

<a id="item-13"></a>
## [Kintsugi shuts down after failing to get FDA clearance for depression-detecting AI, releases tech as open-source.](https://www.theverge.com/ai-artificial-intelligence/905864/depression-detecting-ai-kintsugi-clinical-ai-startup-shut-down) ⭐️ 7.0/10

Kintsugi, a startup that developed AI to detect depression and anxiety from speech over seven years, is shutting down after failing to secure FDA clearance in time and is releasing most of its technology as open-source. This highlights the significant regulatory hurdles AI-based medical devices face in the U.S., potentially slowing innovation in mental health tech and affecting startups reliant on FDA approval for clinical deployment. Kintsugi used voice biomarkers in speech for real-time mental health identification, but the FDA clearance process, often via the 510(k) pathway requiring equivalence to a predicate device, proved too slow for the startup's timeline.

rss · The Verge - AI · Apr 2, 15:33

**Background**: The FDA regulates AI-enabled medical devices to ensure safety and efficacy, with pathways like 510(k) clearance for devices similar to existing ones. Speech analysis for depression detection involves using AI to analyze vocal patterns or content as biomarkers for mental health conditions, aiming to provide scalable screening tools.

<details><summary>References</summary>
<ul>
<li><a href="https://www.fda.gov/medical-devices/software-medical-device-samd/artificial-intelligence-enabled-medical-devices">Artificial Intelligence-Enabled Medical Devices | FDA</a></li>
<li><a href="https://www.thelancet.com/journals/landig/article/PIIS2589-7500(23)00126-7/fulltext">FDA-cleared artificial intelligence and machine learning ...</a></li>
<li><a href="https://www.kintsugihealth.com/">Kintsugi</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Mental Health`, `#Regulation`, `#Startups`, `#Open Source`

---

<a id="item-14"></a>
## [Simon Willison Discusses AI Inflection Point and Agentic Engineering on Lenny's Podcast](https://simonwillison.net/2026/Apr/2/lennys-podcast/#atom-everything) ⭐️ 7.0/10

Simon Willison shared highlights from his appearance on Lenny Rachitsky's podcast, where he discussed the November 2025 inflection point in AI coding agents, the rise of dark factories, and automation timelines. The podcast episode, titled 'An AI state of the union: We've passed the inflection point, dark factories are coming, and automation timelines,' was released on April 2, 2026, and is available on YouTube, Spotify, and Apple Podcasts. This discussion is significant because it highlights a pivotal shift in AI capabilities, particularly for software engineering and automation, which could accelerate industry-wide adoption of agentic systems and reshape labor markets. It matters to developers, tech leaders, and policymakers as it provides insights into how AI is transforming work processes and the potential societal impacts of automation. Willison noted that GPT 5.1 and Claude Opus 4.5 models crossed a threshold in November 2025, making AI coding agents reliably functional, and he mentioned writing 95% of his code on his phone. The conversation also covered topics like dark factories, testing bottlenecks, and the challenges of evaluating AI-generated software.

rss · Simon Willison · Apr 2, 20:40

**Background**: Agentic engineering refers to the design and development of autonomous AI agents that can perform tasks without constant human intervention, often applied in software automation and other fields. Dark factories are fully automated manufacturing facilities that operate with minimal or no human presence, representing a trend toward lights-out production. An inflection point in AI denotes a critical moment where technological advancements lead to rapid and widespread changes in capabilities and adoption.

<details><summary>References</summary>
<ul>
<li><a href="https://www.lennysnewsletter.com/p/an-ai-state-of-the-union">An AI state of the union: We’ve passed the inflection point ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Lights_out_(manufacturing)">Lights out (manufacturing) - Wikipedia</a></li>
<li><a href="https://www.youtube.com/watch?v=wc8FBhQtdsA">Why we’ve passed the AI inflection point and automation has ... InflexionPoint - LinkedIn Highlights from my conversation about agentic engineering on ...</a></li>

</ul>
</details>

**Tags**: `#AI`, `#Agentic Engineering`, `#Automation`, `#Podcast`, `#Software Engineering`

---

<a id="item-15"></a>
## [Gemma 4 models demonstrate extended reasoning capabilities when prompted for maximum thinking length](https://www.reddit.com/r/LocalLLaMA/comments/1sav9wg/gemma_4_is_efficient_with_thinking_tokens_but_it/) ⭐️ 7.0/10

A user tested Gemma 4's 26B and 31B models on a Vigenère cipher cracking task and found that when prompted to 'increase thinking length to maximum,' the models engaged in extended reasoning for over 10 minutes. The 31B model successfully cracked the cipher after receiving a hint about the key length, while the 26B model timed out after 10 minutes. This demonstrates that Gemma 4 models can adapt their reasoning depth based on prompt engineering, which is significant for complex problem-solving tasks like cryptography. It highlights the potential for open-source models to match closed-source competitors in extended reasoning scenarios, advancing on-device AI capabilities. The 31B dense model reasoned for 594 seconds before admitting failure without hallucinating, and it cracked the cipher in about 200 seconds after receiving a hint that the key was 3 digits long. The 26B MoE model timed out after 10 minutes, likely due to AI Studio's response cutoff.

reddit · r/LocalLLaMA · AnticitizenPrime · Apr 2, 22:05

**Background**: Gemma 4 is Google DeepMind's latest open-source large language model family, designed for on-device agentic workflows and released under Apache 2.0 license. Thinking tokens refer to model-generated tokens used during reasoning processes, which can be extended through prompting to enhance problem-solving depth. The Vigenère cipher is a polyalphabetic substitution cipher that uses a keyword for encryption, making it more complex to crack than simple ciphers.

<details><summary>References</summary>
<ul>
<li><a href="https://deepmind.google/models/gemma/gemma-4/">Gemma 4 — Google DeepMind</a></li>
<li><a href="https://www.emergentmind.com/topics/deep-thinking-tokens">Deep- Thinking Tokens in LLM Reasoning</a></li>
<li><a href="https://www.boxentriq.com/ciphers/vigenere-cipher">Vigenere Cipher | Boxentriq</a></li>

</ul>
</details>

**Discussion**: Community comments express mixed sentiment, with some users impressed by Gemma 4's extended reasoning capabilities and others noting it still slightly lags behind competitors like Qwen. There is interest in further testing to see if prompted longer thinking can boost Gemma 4's performance to match Qwen's level.

**Tags**: `#large-language-models`, `#model-evaluation`, `#reasoning-ai`, `#open-source-ai`, `#prompt-engineering`

---

<a id="item-16"></a>
## [Aggressive uncensored variants of Google's Gemma 4 models released with full multimodal support.](https://www.reddit.com/r/LocalLLaMA/comments/1saxvw2/gemma_4_e4b_e2b_uncensored_aggressive_gguf_k_p/) ⭐️ 7.0/10

Two uncensored variants of Google's Gemma 4 models, named E4B (4B parameters) and E2B (2B parameters), were released with aggressive refusal removal, achieving zero refusals while maintaining full multimodal capabilities for text, image, video, and audio. These models are available in GGUF format with K_P quantization variants and include mmproj files for vision and audio support. This release is significant because it provides local AI developers with highly uncensored, multimodal models that can handle diverse inputs without refusal, enabling more flexible and unrestricted applications in areas like content generation and interactive systems. It reflects a growing trend in the local LLM community towards removing alignment constraints to explore model capabilities more freely. The models feature K_P quantization, which uses model-specific analysis to preserve quality with only a 5-15% increase in file size, and they are fully compatible with llama.cpp and LM Studio. Both variants have a native context length of 131K tokens and use mixed sliding window and full attention mechanisms.

reddit · r/LocalLLaMA · hauhau901 · Apr 2, 23:54

**Background**: GGUF is a binary file format designed for storing AI models, optimized for efficient inference with frameworks like llama.cpp. Quantization reduces model size and computational cost by lowering numerical precision, with K_P variants offering improved quality retention. Multimodal AI models process multiple data types, such as text and images, using projector files like mmproj to bridge different modalities.

<details><summary>References</summary>
<ul>
<li><a href="https://www.hardware-corner.net/what-is-gguf-file-format/">What is GGUF file format? | Hardware Corner</a></li>
<li><a href="https://huggingface.co/docs/optimum/concept_guides/quantization">Quantization - Hugging Face Model Quantization: Concepts, Methods, and Why It Matters Quantization in Keras Quantization from the ground up | ngrok blog TurboQuant: Redefining AI efficiency with extreme compression</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp/blob/master/docs/multimodal.md">llama.cpp/docs/multimodal.md at master · ggml-org/llama.cpp</a></li>

</ul>
</details>

**Discussion**: The discussion includes technical debate about alignment techniques, with one user noting that Gemma 4 is less strongly aligned than Gemma 3, making uncensoring easier, while another requests more openness in sharing techniques or non-quantized versions for further development.

**Tags**: `#local-llm`, `#model-uncensoring`, `#multimodal-ai`, `#gemma`, `#model-quantization`

---

