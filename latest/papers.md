# 📑 论文索引 - 2026-09-29

共 119 篇论文

---

### [1] ChemMLLM: Chemical Multimodal Large Language Model

**链接**: https://arxiv.org/abs/2505.16326
**作者**: Qian Tan, Di Zhang, Ben Gao, Peng Xia, Wanhao Liu, Shufei Zhang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] Cheap, open agents make LLM pollution harder to mitigate

**链接**: https://arxiv.org/abs/2609.31054
**作者**: Raluca Rilla, Anne-Marie Nussberger, Rui Mata, Dirk U. Wulff
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) pollution occurs when synthetic responses contaminate data intended to capture human behavior. High deployment costs have so far limited the risk posed by autonomous survey agents. However, open-weight models paired with open-source agentic frameworks may have removed this barrier. We compared the performance and detectability of nine agent configurations, ranging from fully open variants to closed commercial ones. Each agent autonomously completed a survey containing multiple response types yielding various detection checks. Fully open agents ran locally without usage fees and performed competitively with commercial alternatives. Open and commercial agents failed different sets of checks, and no single check reliably detected all agents, but open-text responses discriminated best between agents and humans. These findings identify fully open agents as a distinct risk for LLM pollution and support multilayered detection strategies emphasizing open-text analysi

---

### [3] Financial Fragility in Societies of LLM Agents: Coordination Failures and Stabilizing Mechanisms

**链接**: https://arxiv.org/abs/2609.30940
**作者**: Zhenhao Fu, Ruipeng Xu, Qibing Ren
**来源**: cs.AI q-fin.GN
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Individually protective decisions can produce avoidable collective failures. As large language model (LLM) agents take on greater roles in financial decision-making, financial AI safety must therefore be considered not only at the level of individual agents, but also at the level of the systems they jointly create. We study this problem with FRAIL, a controlled experimental framework that places LLM agents in three dynamic financial environments---bank runs, debt rollover, and reward crowdfunding---where agents' decisions reshape the financial conditions faced by others. Across seven leading LLMs, we find widespread collective fragility even when no agent is instructed to destabilize the system: 77\% of baseline bank-run episodes and 83\% of debt-rollover episodes end in failure. We then compare three interaction mechanisms based on compensated commitments, centralized commitment agreements, and participant-led coalitions. All three improve aggregate outcomes, but no single mechanism p

---

### [4] Bridging LLM Agents and Data Spaces: An Architectural Mediation Approach using the Model Context Protocol

**链接**: https://arxiv.org/abs/2609.30341
**作者**: Jaime Alonso Ruiz, Carlos Aparicio, Gabriel Huecas, Joaqu\'in Salvach\'ua, Andres Munoz-Arcentales
**来源**: cs.AI cs.DB
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data Spaces enable sovereign and governed data sharing across organizational boundaries, but their integration with AI agents remains challenging due to mismatches between probabilistic language model interactions and policy-driven data infrastructures. This article presents an architectural mediation approach based on the Model Context Protocol (MCP), implemented through the Eunomia Agent, to enable controlled interaction between large language model (LLM) agents and data space services. The proposed mediation layer translates data space capabilities into structured, schema-driven tools that AI agents can discover and invoke while preserving governance constraints. A prototype implementation validates end-to-end interaction across catalog discovery, metadata retrieval, and data service invocation without modifying existing data space components. Results demonstrate that protocol-based mediation enables interoperable and standards-aligned integration of AI agents into data space ecosys

---

### [5] All In Good Time: Causality-Aware Framework for LLM-Based Simultaneous Speech-to-Speech Translation

**链接**: https://arxiv.org/abs/2609.30416
**作者**: Amir Hussein, Enas Albasiri, Travis M. Bartley, Nourchene Ferchichi, Ke Hu, Harishchandra Dubey 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown strong performance in low-resource offline translation; however, extending them to simultaneous speech-to-speech translation (Simul-S2ST) remains challenging due to the scarcity of causally aligned training data with high cross-lingual speaker fidelity. In addition, existing approaches rely on fixed translation policy or confidence heuristics, leading to suboptimal quality and higher latency. We propose a causality-aware Simul-S2ST framework with a novel data pipeline that generates high-fidelity, causally aligned segments with improved voice transfer. The framework introduces (i) a factorized S2ST architecture (FAST), (ii) a causality-aware adaptive policy (CAP), and (iii) causality-aware latency metric. Experiments on CVSS Spanish, German, and French show that FAST-CAP consistently improves the quality-latency trade-off, achieving up to +1.2 BLEU and a 26% relative latency reduction over a fixed policy. Despite using substantially less training

---

### [6] Backbone-Adaptive Evidence Routing for Robust Pairwise LLM Judging

**链接**: https://arxiv.org/abs/2609.30751
**作者**: Zeyan Li, Jing Peng, Jianfeng Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pairwise language-model judges can gather evidence through direct comparison, reasoning, or reference-based verification, but no single protocol is best across benchmarks and judge backbones. We introduce Backbone-Adaptive Evidence Routing (BAER), which adapts the evidence mechanism while preserving candidate symmetry: swapping the two responses may reverse the preference but cannot change its strength. BAER separates each expert's signed preference from candidate-invariant reliability and builds three symmetric heads: evidence stacking, reliability-based expert routing, and candidate-blind reference verification. Development data select one head for each benchmark--backbone condition, and that choice is frozen before testing. Across four benchmarks and two 8B judge backbones, BAER achieves the highest test accuracy among the compared methods in all eight conditions, with full prediction coverage and gains of 0.87--7.32 points over the strongest external baseline. The results show that

---

### [7] PriceBench: A Diagnostic Benchmark for Price, Quality, and Brand Preferences in LLM Booking Agents

**链接**: https://arxiv.org/abs/2609.31468
**作者**: Pavel Kireyev
**来源**: econ.GN cs.AI cs.CL q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs increasingly act as purchasing agents, which makes the LLM, not the user, the one choosing among the options that satisfy a request; its preferences quietly fix what gets bought and what it costs. Hotel booking is a clean instance: a high-volume choice settled on a few comparable attributes, where the pick reveals those preferences. We introduce PriceBench, a diagnostic benchmark that recovers an LLM's price, quality, and brand preferences from its booking choices with a logit choice model, applied to 28 LLMs from 8 providers on 3,600 hotel tasks from 179 real New York City properties. We find that capability is associated with how consistently an LLM chooses, not with what it chooses: more capable LLMs hold stronger, more consistent preferences, while weaker ones either lock onto one position, exploitable by whoever controls listing order, or choose almost indifferently. What those preferences favor varies sharply across providers and even within one family: price sensitivity spa

---

### [8] LUMO (Lightweight Unified Multilingual Orchestrator): A Privacy Preserving Offline Voice Assistant

**链接**: https://arxiv.org/abs/2609.30692
**作者**: Md. Mehedi Hasan Naeem, Mst. Kamrunnahar Ruma, Nafiza Anjum, Shakila Sultana, Md. Sujan Ali
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable voice interaction is essential in environments with limited internet connectivity and strong privacy. However, most existing voice assistants depend on cloud-based services, which leads to latency issues, dependency on internet access, and privacy vulnerabilities. This research presents LUMO (Lightweight Unified Multilingual Orchestrator), a privacy preserving offline voice assistant designed for edge computing environments. This system integrates local Automatic Speech Recognition (ASR), locally deployed quantized Large Language Model (LLM), and Text-to-Speech (TTS) synthesis into a fully offline pipeline running on a Raspberry Pi 5 with 8 GB RAM. To enable efficient operation on resource constrained hardware, the language model is compressed using 4-bit GGUF quantization, which reduces memory usage while preserving practical conversational capability. Existing edge based voice assistants Mycroft provides partial offline functionality without a generative LLM, with an approxi

---

### [9] Grid-Orch: An LLM-Powered Orchestrator for Distribution Grid Simulation and Analytics

**链接**: https://arxiv.org/abs/2605.12728
**作者**: Boming Liu, Jin Dong, Jianming Lian
**来源**: eess.SY cs.AI cs.SE cs.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [10] Learning What to Skip: Counterfactual Credit Assignment for Efficient Multi-Agent LLM Workflows

**链接**: https://arxiv.org/abs/2609.30734
**作者**: Jinfeng Xu, Zheyu Chen, Ziyue Peng, Zheng Lin, Shuo Yang, Jinze Li 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM workflows use planning, execution, verification, and summarization to improve task performance, yet the value of each component depends on the state already produced. Executing every component can waste computation or overwrite a correct intermediate answer. We formulate component omission as counterfactual credit assignment: full-workflow logs reveal the executed trajectory's reward, while controlled skip interventions reveal the consequences of omitting a future step. We introduce Learning What to Skip (LW2S), which learns action-specific safety models from these interventions and combines held-out calibration with domain-native guards to select skips. When an early skip is rejected, the controller can continue execution and reconsider a later component. Across mathematical reasoning, multiple-choice QA, and code generation with two instruction-model families, LW2S reduces recorded token cost while matching or improving aggregate full-workflow accuracy in the evaluate

---

### [11] Closing the Speech-Text Gap with Limited Audio for Effective Domain Adaptation in LLM-Based ASR

**链接**: https://arxiv.org/abs/2604.06487
**作者**: Thibault Ba\~neras-Roux, Sergio Burdisso, Esa\'u Villatoro-Tello, Dairazalia S\'anchez-Cort\'es, Shiran Liu, Severin Baroudi 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] DIAL: Position-Debiased LLM Judges with Adaptive Human Preference Calibration

**链接**: https://arxiv.org/abs/2609.31215
**作者**: Zesheng Cai and Yingqi Fan and Sichang Chen and Jin-Hong Du
**来源**: cs.AI stat.AP stat.ME stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) as a judge enable scalable evaluation, but their judgments can be sensitive to response order and, even after removing such position effects, can still diverge systematically from human preferences.We introduce DIAL, a unified framework that combines abundant LLM comparisons with limited human comparisons to separate judge-specific position effects, learn shared structure in position-debiased LLM preferences, and adaptively calibrate that structure toward the human preference target. Theoretically, we study three aspects of DIAL: (i) identification of latent LLM preferences, position effects, and human calibration; (ii) adaptive estimation that balances LLM anchoring against limited human evidence; and (iii) fixed-weight uncertainty quantification for the calibrated human preference. Empirically, we evaluate position debiasing and human alignment separately in controlled simulations and on three human-preference benchmarks, showing that DIAL remains robust 

---

### [13] Apollo Restore: A Foundation LLM for Historical Greek Optimized for Fill-in-the-Middle Restoration of Ancient Greek Texts

**链接**: https://arxiv.org/abs/2609.22455
**作者**: Hope McGovern, Anna Dolganov, Samuel Belkadi, Guillaume Kunsch, Dimitris Vlitas, and David A. Smith
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Segment-Level Agentic Topic Modeling for Improved Data Exploration and Resource Efficiency

**链接**: https://arxiv.org/abs/2609.31460
**作者**: Myeongjun Erik Jang, Antonios Georgiadis, Sae Young Moon, Fran Silavong
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Topic modeling is an effective technique for discovering hidden themes within documents and is widely used in text mining and data analysis across a variety of industry sectors. Recently, large language model (LLM)-based topic models have been emerged that prompt LLMs to generate topics then assign the topics to documents, producing more natural and human-readable topics than conventional topic modeling algorithms. However, the nature of topic assignment process causes certain drawbacks, such as the incapability to produce topic distributions over a document, too broad or narrow topics, and high resource consumption, which increases with the number and length of of documents being assigned topics. These issues are particularly critical for industrial applications, which require high-quality, in-depth analysis and the processing of large volumes of documents. In this context, this paper introduces a framework called SeLATM, which addresses these concerns by employing segment-level topic

---

### [15] Externalized CPDAG Summaries Improve LLM Causal Deduction

**链接**: https://arxiv.org/abs/2609.31071
**作者**: Wentao Sun, Jo\~ao Paulo Nogueira, Dominique Verchere, Mathieu Acher, and Alonso Silva
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Corr2Cause asks whether a causal claim holds in every DAG compatible with observed correlations and conditional independencies. We frame this as latent-object reasoning: the label is defined by a CPDAG query, but free-form chain-of-thought often collapses the Markov-equivalence-class problem into local pattern matching. We propose Structured Thinking, a two-turn pipeline that first externalizes a typed, schema-constrained CPDAG summary and then answers against that graph state. On the Corr2Cause full test, Structured Thinking raises Qwen3.5-27B from $73.0$ to $86.4$ $F_1$(Yes) over a strong PC-instruction baseline in the primary paired run ($+13.4$ pp; McNemar $p=2.4\times 10^{-6}$; bootstrap $95\%$ CI [$+8.4$, $+18.6$]); across three full-ID seeds, the mean gain is $+8.1 \pm 5.3$ pp. A PC-scaffolded two-turn prose control reaches only $67.6$ $F_1$, indicating that a detailed PC scaffold plus a schema-free prose intermediate is not sufficient. The same pattern holds on Qwen3.6-27B, Par

---

### [16] G$^2$PTQ: Improving LLM Post-Training Quantization with Generalized Gradient Compensation

**链接**: https://arxiv.org/abs/2609.31009
**作者**: Ruikang Liu, Haoli Bai, Yuxuan Sun, Qian Zhang, Wenzheng Cai, Yanqi Hao 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization (PTQ) is a practical approach to reducing the memory and computational footprint of large language models (LLMs) without retraining. GPTQ-based methods have become the de facto standard, yet they suffer from two complementary limitations. Methods with local, layer-wise objectives lack global supervision; while methods with global objectives fix their Hessian estimates at the start and ignore first-order gradients, so their guidance grows stale as quantization proceeds. This paper presents G$^2$PTQ, a unified PTQ framework with Generalized Gradient Compensation that integrates both first- and second-order information under a globally supervised, block-wise optimization objective. By refreshing gradient and Hessian estimates before quantizing each Transformer block, G$^2$PTQ avoids the staleness of prior global methods. Furthermore, to stabilize the exact first-order compensation, we introduce a trust-region scaling mechanism that dynamically bounds the gradien

---

### [17] Auditing and Repairing LLM-as-Judge Failures in a Production Text-to-SQL Pipeline

**链接**: https://arxiv.org/abs/2609.30290
**作者**: Haowei Liu, Hsin-Tai Wu, Yi Fang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Production text-to-SQL pipelines often end with an LLM-as-judge whose agreement with human annotators has never actually been measured. When we checked ours, the deployed gpt-4o-mini judge agreed with two-author gold at only Cohen's kappa = 0.04 on a disagreement-enriched set and 0.42 on a uniform-random spot-check, over-flagging 77.1% of the human-FAITHFUL cases in the enriched set. Most of its over-flags trace back to a single mechanism we call GRADE-HALLUCINATION. A self-hosted Qwen3.6-27B replacement (kappa = 0.72) lands in the same range as Claude Opus 4.7 (kappa = 0.71); the head-to-head is underpowered at n = 96, but for the deployment decision that hardly matters, since Qwen costs roughly 1/300 as much per call. Ensembling does not help for free. Pairing the weak judge with a stronger one degrades agreement, whereas three strong judges under unanimity routing reach kappa = 0.79 at 89.7% auto-coverage. Applied out-of-domain, the same audit recipe flags 25.5% of BIRD-financial's 

---

### [18] The Price of Thought: Does Test-Time Reasoning Pay in LLM Trading?

**链接**: https://arxiv.org/abs/2609.30705
**作者**: Jiayi Chen, Guiling Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While inference-time reasoning in large language models (LLMs) promises better decision making, its higher computational cost may not yield better economic outcomes. Yet reasoning controls are rarely evaluated as economic interventions, where changes in model outputs must translate into better portfolios after trading costs. We conduct a controlled study of representative LLMs from the DeepSeek, GPT, and Gemini families. We vary reasoning effort while holding information available at each formation date, prompts, output formats, and portfolio construction fixed. Our evaluation covers a full year of U.S. equities under three input conditions: numerical, identifiable news, and masked news. It includes more than 800,000 asset predictions and repeated model generations. Across all three model families, additional reasoning does not produce a reliable improvement in net portfolio returns. For DeepSeek, where we examine the full progression from no reasoning to maximum reasoning, performance

---

### [19] LLM Parkinsonism: Executive-Control Failure, Token-Inefficient Persistence, and an Uncertainty-Aware Global Executive Control Architecture for Autonomous Language-Model Agents

**链接**: https://arxiv.org/abs/2609.30662
**作者**: Dongsheng Xiao, Zeyuan Wang, Xuzhe Xia, Bo Zhao, Yankai Cao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can plan, use tools, write code, and execute long-horizon workflows, yet strong local competence does not guarantee project-level executive control. Agents may continue acting after the original objective is satisfied, producing low-value refinements, repeated verification, and repairs to self-created complexity. We use LLM Parkinsonism as a narrowly defined, non-clinical metaphor for this pattern of persistent action despite diminishing task-level value. We argue that the problem is not explained by autoregressive next-token prediction alone, but more directly by concentrating proposal generation, scope interpretation, progress assessment, and stopping authority within the same self-conditioned loop. We therefore introduce Global Executive Control (GEC) v0.2, an uncertainty-aware governance architecture that separates action generation from project-level control. In a 24,000-episode matched-candidate benchmark under a common 40,000-token ceiling, a first-c

---

### [20] Resource-Optimized and Energy-Aware Agentic AI Framework Anchored on Blockchain for Secure Software Supply Chains

**链接**: https://arxiv.org/abs/2609.31282
**作者**: Toqeer Ali Syed, Asadullah Abdullah Khan
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper proposes a blockchain-backed agentic security framework designed to safeguard the complete software development lifecycle (SDLC) while also securing the agentic AI components responsible for monitoring it. The framework coordinates a set of specialised security agents, covering source integrity, dependency and SBOM analysis, CI configura tion auditing, artifact verification, and runtime policy evaluation, each supported by a large language model (LLM) that interprets artefacts, reasons over tool outputs, and produces structured security reports. To ensure agent trustworthiness, every agent generates a cryptographically signed attestation that is recorded in a permissioned blockchain via smart contracts, including an agent registry, an immutable attestation log, and an enforceable release-policy module. Communication among agents and with blockchain nodes is secured using a consortium-operated certificate authority, ensuring authenticated and tamper-resistant interactions. A 

---

### [21] Low-Cost Black-Box Detection of LLM Hallucinations via Dynamical System Prediction

**链接**: https://arxiv.org/abs/2605.05134
**作者**: Dan Wilson, Mohamed Akrout
**来源**: cs.LG math.DS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] Mutable Transcripts: Mitigating Context Pollution through Editable Conversation State

**链接**: https://arxiv.org/abs/2609.31354
**作者**: Dan Barry and Andrew Hines
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contemporary large language model (LLM) chat systems treat conversation history as an immutable sequence of turns that defines the model's working context. However, user intent in real interactions is not static: it evolves through correction, refinement, and shifting constraints. This mismatch between dynamic intent and static transcripts can result in context pollution, where outdated or irrelevant information persists and continues to influence subsequent responses. We introduce mutable transcripts, a new interaction paradigm that enables users to revise prior turns through natural language edit requests, allowing the conversation history itself to be updated rather than appended. This reframes the transcript from a passive record into an editable representation of conversational state. We present a working prototype that integrates transcript-level revision into a standard chat interface and evaluate its feasibility through a controlled user study (n=17) and an illustrative transcr

---

### [23] Thinking Less to Simulate Better: Intuitive Prompting Improves LLM Agents Simulating Individual Social Media Reactions, Including Unfamiliar Content

**链接**: https://arxiv.org/abs/2609.30563
**作者**: Ljubisa Bojic, Tijana Stanic, Joerg Matthes, Agariadne Dwinggo Samala, Bojana Dinic, and Jue Wang
**来源**: cs.AI cs.CL cs.HC cs.MA cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Platform policies are increasingly tested on artificial users, making agent fidelity important. Yet convincing fake profiles could also manipulate perceived public opinion before elections. Validation has concentrated on agreement with human behaviour and has paid little attention to whether an agent behaves in line with the profile it was given. The present study profiled eight Serbian participants through a questionnaire, a deep interview, and a written self-presentation, recorded their reactions to sixty-eight social media posts, and asked four language models to predict those reactions under five prompt conditions varying profile content and instruction style. Attitudinal content improved prediction over demographic backstories by a wide margin. Agents matched their stated profiles more closely than participants matched their own survey answers, and consistency proved unrelated to fidelity once profile information was present. Instructing models to respond intuitively and immediate

---

### [24] ArGuard Shared Task: Harmful Content Detection in Arabic Memes and LLM Prompts

**链接**: https://arxiv.org/abs/2609.29349
**作者**: Firoj Alam, Md. Rafiul Biswas, Mohamed Bayan Kmainasi, Ali Ezzat Shahroor, Hamdy Mubarak, George Mikros 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] Scepsy: Serving Agentic Workflows Using Aggregate LLM Pipelines

**链接**: https://arxiv.org/abs/2604.15186
**作者**: Otto White, Marcel Wagenl\"ander, Britannio Jarrett, Xijin Zhao, Yanda Tao, Pedro Silvestre 等 (10 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] HybridInfer: Thermal-Aware Reinforcement-Learning Tier Routing for On-Device, Edge, and Cloud LLM Inference

**链接**: https://arxiv.org/abs/2609.30270
**作者**: Simran Koul
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device inference with small language models keeps user data local, works offline, and incurs no per-query cost, so the on-device tier is preferred when it is adequate. It is thermally constrained, however, and I find the constraint is sharper than a slowdown: on a flagship Snapdragon device, sustained on-device generation destabilizes the GPU inference runtime, which crashes or silently wedges after a few consecutive queries. The failure lies in the current toolchain (OpenCL kernel compilation and long-prompt prefill on the mobile GPU), recurs even when the device is cool, and is worst for long generations. Multi-tier routers across on-device, edge, and cloud models can relieve this pressure, but existing routers are thermal-blind and typically evaluated in simulation or on non-mobile hardware. I present HybridInfer, a thermal-aware reinforcement-learning router for a three-tier hierarchy (on-device Llama 3.2 3B, edge Llama 3.1 8B with retrieval, cloud GPT-4o) that uses the phone's 

---

### [27] Evaluation is All You Need: Strategic Overclaiming of LLM Reasoning Capabilities Through Evaluation Design

**链接**: https://arxiv.org/abs/2506.04734
**作者**: Yongfu Zhu, Lin Sun, Jinzhu Wu, Weihong Lin, Xiaoqi Jian, Guangxiang Zhao 等 (10 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] Cost-Aware Best-LLM Identification using Dueling Feedback

**链接**: https://arxiv.org/abs/2609.30360
**作者**: Sarvesh Gharat, Nikhil Karamchandani, Jayakrishnan Nair
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inspired by the problem of identifying the best model from a collection of large language models (LLMs) with heterogeneous querying costs, we formulate and analyse a variant of the multi-armed bandit (MAB) with (i) dueling feedback, where pairwise comparisons between model responses provide robust preference signals, and (ii) heterogeneous sampling costs, reflecting the differing costs of querying different LLMs. Assuming the existence of a Condorcet winner, a condition we empirically validate across multiple real-world datasets, we propose a Track-and-Stop style algorithm for best-arm identification with prescribed confidence. We prove that the algorithm almost surely achieves the asymptotically optimal cost as the error tends to zero. Finally, we extensively evaluate our approach on both synthetic and real-world instances, demonstrating consistent improvements over classical cost-unaware algorithms and their cost-aware extensions.

---

### [29] Same Text, Different Numbers: The Divergence of LLM-Based Measures

**链接**: https://arxiv.org/abs/2609.31013
**作者**: Hamid Boustanifar, Sasan Mansouri
**来源**: cs.AI cs.CL q-fin.GN q-fin.RM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers increasingly use generative large language models (LLMs) to convert corporate text into empirical variables. We examine the extent to which LLM-based textual measures are invariant to model choice using thirteen measures, including sentiment, management clarity, uncertainty, answer specificity, and climate and political risk. Seven LLMs from different providers score earnings call transcripts of S&P 500 companies on these constructs. Cross-model rank correlations average only 0.52, and transcript-level differences common across providers account for only 34% of total score variation. Cross-model disagreement does not predict subsequent analyst or market disagreement, consistent with a substantial model-specific component rather than common ambiguity in the underlying disclosure. Model choice significantly affects downstream inference, with coefficient magnitudes, signs, and statistical significance varying substantially across models. Averaging across providers makes transc

---

### [30] HasMem: Hard-Origin Adaptively Softened Memory for Long-Term LLM Agents

**链接**: https://arxiv.org/abs/2609.30797
**作者**: Zihong He, Junxiao Shen, Chen Liang, Hai-Ning Liang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-based memory and context compression support reuse of past interactions. Resizing continuous memory changes the input to a frozen LLM, coupling capacity allocation with readout. We propose Hard-Origin Adaptively Softened Memory (HasMem). Frozen hard-prompt embeddings provide a verifiable initial state. A controller adjusts memory widths, a Writer re-encodes resized entries, and Reader and Global provide readout adaptation and cross-turn state. On all $535$ questions in a reconstruction probe derived from the Multi-Session Chat (MSC) development split, the main configuration achieves lexical F1 of $95.3$ ($+4.4$ percentage points) at $93.6\%$ of the hard reference's framed memory positions. With approximately matched per-question target body budgets, six configurations at mean per-entry retention around $0.83$--$0.91$ exceed rule-based re-encoding by $8.0$--$23.6$ exact-match (EM) percentage points. With fixed model parameters and rule target width ratio $0.75$, Global's EM gain pa

---

### [31] Not All Memories Are Equal: Hierarchical Collaborative Memory for Validity-Aware Retrieval in LLM Agents

**链接**: https://arxiv.org/abs/2609.30289
**作者**: Yufei Shi, Rujing Yao, Ang Li, Yang Wu, Zhuoren Jiang, Xiaozhong Liu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In team collaboration scenarios, memory is heterogeneous and continually evolving. Team memories capture collective decisions, protocols, and current consensus, while individual memories preserve member-specific observations, execution traces, and intermediate progress. Existing memory-augmented systems typically retrieve from all stored memories as a flat pool, ranking them by semantic relevance, importance, or recency without modeling hierarchical structure or evolving validity. As a result, they often surface semantically relevant but outdated or conflicting memories, especially individual memories that no longer align with current team consensus, instead of prioritizing currently valid memories. This is particularly problematic when collaborative LLM agents answer user questions, since their responses should be grounded in valid memories. We propose HiCoMER, a framework for hierarchical collaborative memory management and validity-aware retrieval in LLM agents. HiCoMER first mainta

---

### [32] Towards Understanding LLM-Based Log Anomaly Detection: An Empirical Study of Performance, Efficiency, and Robustness

**链接**: https://arxiv.org/abs/2609.31371
**作者**: Bin Li, Dongdong Wang, Siyang Lu
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated promising performance in log anomaly detection, yet how their adaptation strategies, architectures, and deployment configurations affect detection effectiveness remains insufficiently understood. To investigate these factors, we conduct a systematic empirical analysis across three public log datasets, examining different adaptation strategies, model architectures, parameter scales, and quantization settings. Our results reveal substantial performance differences across adaptation strategies, while model scaling yields varying detection gains across datasets. We further observe that models with comparable detection accuracy can exhibit markedly different computational costs, and that low-bit quantization largely preserves detection performance in the evaluated configurations. Finally, we examine detection robustness under structural, semantic, and label noise at different perturbation levels. These findings provide empirical insights into t

---

### [33] Admission Without Answers: Label-Free Certification and Experience Learning for LLM-Based Optimization Modeling

**链接**: https://arxiv.org/abs/2608.15565
**作者**: Junbo Jacob Lian, Huiling Chen, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Can You Check That? The Checkability Boundary for Local LLM Network Automation

**链接**: https://arxiv.org/abs/2609.31540
**作者**: Maleeha Masood, Momina Nofal
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sending every network-automation input to a third-party frontier LLM exports sensitive artifacts such as production configurations, topologies, and logs. Querying small language models (SLMs) locally avoids this egress, but SLM outputs can be error-prone for direct use. This work introduces checkability as a criterion for determining which tasks are suitable for local inference. A task is checkable when it exposes a cheap, deterministic test - an intrinsic check - that rejects outputs violating a necessary correctness condition. We instantiate this idea in Touchstone, a local-first pipeline that uses seven off-the-shelf SLMs (1-8B parameters) to generate candidates, uses task-specific intrinsic checks to reject responses, and escalates unresolved inputs to a frontier LLM. On conflict detection and intent translation tasks, Touchstone reaches 98.6% and 93.8% end-to-end accuracy while escalating only 16% and 17% of inputs, respectively. On TeleQnA, a knowledge-only control that has no ta

---

### [35] MoMHa: Multi-Objective Optimization of LLM Harnesses over Accuracy, Safety, and Tokens

**链接**: https://arxiv.org/abs/2609.30967
**作者**: Subhojyoti Mukherjee, Md Mehrab Tanjim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most work on improving large language models treats accuracy as the sole objective. We argue that the harness, the Python code surrounding the model that constructs prompts, routes calls, and parses outputs, is a first-class design surface whose quality is inherently multi-objective: an accurate harness that refuses no unsafe request, or that consumes an order of magnitude more tokens, is not a good harness. We present Meta-Harness, a system that casts harness design as search over three per-domain objectives (accuracy, behavioural safety, and token cost) solved by an agentic proposer (Claude Code) with full filesystem access to prior harness source, execution traces, and scoring artifacts. Our central finding is that a singlephase joint-reward proposer (MoMHa) outperforms every alternative, including a two-phase "accuracy then tokens" ablation, scalar-only feedback, and an accuracy-only baseline. We evaluate on seventeen domains: seven synthetic capability suites, seven real-world pub

---

### [36] Accounting for Bias Enables Sustainable LLM Evaluation

**链接**: https://arxiv.org/abs/2609.31184
**作者**: Harshita Katoch, David Antony Selby, Gerrit Gro{\ss}mann, Sebastian Vollmer
**来源**: cs.AI cs.LG stat.AP stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge has become the de facto standard for scalable, subjective evaluation, yet current leaderboards compensate for systematic measurement bias by running ever more comparisons, an approach that is both statistically unsound and computationally wasteful. The root cause is an incomplete measurement model, treating LLM judges as neutral, interchangeable instruments ignores documented biases like position bias, verbosity bias, judge severity, and self-enhancement, that no volume of additional data can eliminate. We propose a unified latent variable framework that jointly models pairwise and ordinal data while explicitly correcting for these confounders, recovering reliable rankings from substantially fewer comparisons. Because fitting this model costs negligible compute relative to a single round of LLM inference, bias correction is not only more statistically rigorous but also a more sustainable approach to trustworthy evaluation.

---

### [37] Detecting Time Series Anomalies Like an Expert: A Multi-Agent LLM Framework with Specialized Analyzers

**链接**: https://arxiv.org/abs/2605.05725
**作者**: Hyeongwon Kang, Jeongseob Kim, Jinwoo Park and Pilsung Kang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] AgentRecommender: LLM Agents Enable Customizable Recommender Systems on the User Side

**链接**: https://arxiv.org/abs/2609.31166
**作者**: Ryoma Sato
**来源**: cs.IR cs.AI cs.DB cs.DL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recommender systems have traditionally been developed for platforms. However, this has given rise to many phenomena that may be advantageous for platform lock-in but are a nuisance to users, such as clickbait, filter bubbles, and the spread of fake news. Recently, user-side recommender systems have been proposed as a new paradigm for solving this problem. If users deploy their own recommender systems, they are no longer at the mercy of the platform's interests. However, building a user-side recommender system is not trivial; in particular, customizing one for oneself requires additional data. We propose AgentRecommender, a method that leverages the investigation capability and internal knowledge of LLM agents to flexibly build user-side recommender systems without additional data. AgentRecommender allows users to easily create recommender systems tailored to their own preferences.

---

### [39] PrivDrift: Auditing User-Secret Leakage Under Topic Drift in Active LLM Conversations

**链接**: https://arxiv.org/abs/2609.30094
**作者**: Luciano Maldonado
**来源**: cs.AI cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Actively Resolving Contextual Uncertainty for Underspecified Tasks in Natural Language

**链接**: https://arxiv.org/abs/2609.30428
**作者**: Zachary Ravichandran, Jonathan Diller, Fernando Cladera, Varun Murali, George J. Pappas, and Vijay Kumar
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models provide robots with the ability to interpret natural language and reason about environmental context, yet most language-conditioned policies assume that goals are well-specified and that task-relevant information is provided upfront via a prior map. Operating in unfamiliar environments with underspecified tasks entails high contextual uncertainty: the robot must jointly infer what constitutes task success, what constitutes relevant information, and where (or whether) that information exists. We address these limitations via CLUE (Closed-Loop contextual Uncertainty rEsolution), a framework for actively resolving contextual uncertainty given underspecified tasks in natural language. CLUE uses an LLM-derived policy to hypothesize task-relevant concepts and potential plans. It then uses a language-embedded map, which is constructed online, to ground these hypotheses into actions. The policy sequentially evaluates hypotheses via closed-loop environment interaction and refi

---

### [41] Self-Play Search Distillation for Large Language Model Reasoning

**链接**: https://arxiv.org/abs/2609.30936
**作者**: Lorenzo Molfetta, Wai-Chung Kwan, Giacomo Frisoni, Luca Ragazzi, Gianluca Moro, Pavlos Vougiouklis 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving reasoning abilities in Large Language Models (LLMs) requires high-quality data that exposes difficult decisions, competing alternatives, and their consequences. Data scarcity is driven by the low quality of synthetic data and the cost of human labeling. We introduce Self-Play Search Distillation (SPSD), a framework for generating superhuman synthetic data via self-play of MuZero-like networks trained on board games. SPSD uses executable environments to turn search into structured reasoning problems. At each state, the expert identifies a preferred decision, plausible alternatives, plausible opponent replies, and value estimates. By converting the self-play search records into superhuman chains-of-thought, we train LLMs with environment-grounded supervision. Although trained only on self-play search records, SPSD transfers to unseen mathematics. On Qwen3-4B-Base, it raises the mean over six mathematics benchmarks from 24.1 to 36.6 while increasing the held-out-game win rate fr

---

### [42] QueryGraph: Reliable Multi-Tool Query Execution Planning via LLM-Based Graph Generation

**链接**: https://arxiv.org/abs/2606.08300
**作者**: Aishwarya Chakravarthy, Vidhi Kulkarni, and Duen Horng Chau
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Think Short, Defer Smart, Act, and Repeat: Calibrated Reasoning and Uncertainty-Aware Deferral for Edge LLM Agents

**链接**: https://arxiv.org/abs/2607.26865
**作者**: Amirmohammad Farzaneh and Osvaldo Simeone
**来源**: stat.ML cs.AI cs.IT cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] ActKV: Efficient LLM Agents through Action-Guided KV Cache Management

**链接**: https://arxiv.org/abs/2609.31395
**作者**: Zihan Wang, Cheng Tang, Lei Gong, Chao Wang, Wenqi Lou, Teng Wang 等 (7 人)
**来源**: cs.OS cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic LLM inference accumulates long KV caches across iterative observation-reasoning-action loops, imposing substantial memory overhead and limiting serving throughput. Existing compression methods emphasize overall output quality, overlooking the asymmetric importance of actions in driving task progress. Our key idea is to establish a compression criterion that values KV entries by their contribution to action generation and prioritizes action quality. However, iterative execution, dynamic memory demands, and scattered action-critical entries pose challenges to eviction policies, budget allocation, and paged memory integration. To this end, we propose ActKV, the first KV cache compression framework tailored for agentic LLM inference. (i) Action-oriented KV cache eviction exploits stable action access patterns to retain entries critical to future actions, supporting reliable task progress under compression. (ii) Confidence-driven adaptive budget allocation uses LLM's intrinsic confi

---

### [45] BuildOcc: A Large Language Model Occupant Agent Platform for Building Energy Research

**链接**: https://arxiv.org/abs/2609.02729
**作者**: Wooyoung Jung
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Game Arena: Strategic LLM Evaluation in Competitive Environments

**链接**: https://arxiv.org/abs/2609.31473
**作者**: Bovard Doerschuk-Tiberi, Yao Yan, Justin Chiu, Hann Wang, Timothy Chung, Martyna Plomecka 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Kaggle Game Arena, an open and ever-expanding platform to evaluate large language models (LLMs) through competitive games. Different from static benchmarks, game arena enables models to play head-to-head matchups in structured environments where the gameplay strength naturally increases as models evolve, preventing performance saturation. This technical report details the infrastructure behind Game Arena and describes the three pilot game environments: Chess, Poker, and Werewolf. These environments span perfect information, imperfect information, and multiplayer game settings, enabling a systematic study of models' strategic planning, adaptation, and robustness under uncertainty. For each game, we provide a detailed description of the environment, evaluation metrics, and results from running full competitions across models. Through robust infrastructure and large-scale ground-truth based evaluation, Game Arena ensures reproducibility, transparency and generalizability to n

---

### [47] Inference-Time Target Speaker Unlearning in LLM-Based Automatic Speech Recognition

**链接**: https://arxiv.org/abs/2609.30439
**作者**: Bo Su, Yueru Yan, Thai Le
**来源**: cs.CL cs.SD eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce target-speaker unlearning ASR (TSU-ASR) task in a fully end-to-end framework for multi-speaker ASR and diarization. Given a multi-speaker utterance and a set of opt-out speakers who do not wish to have their speech transcribed, the task requires an ASR system to transcribe all speakers except the opt-out ones, while still indicating when those speakers are active. As a first step towards tackling this task, we introduce a novel, light-weight Enrollment-Conditioned Gating (ECG) module attachable to a frozen dual-stream speech LLM that enables ASR for new opt-out speakers dynamically during inference, even those who were not seen during initial ECG training phase. Our experiments on both AMI (English) and AliMeeting (Mandarin) datasets show that speech transcription accuracy for corresponding opt-out words or characters falls from 72.3% to 48.2% and from 73.6% to 27.3%, respectively, while retained speakers' transcription error rates maintain more or less the same. Our appro

---

### [48] Large Language Model Selection with Limited Annotations

**链接**: https://arxiv.org/abs/2605.24981
**作者**: Yavuz Durmazkeser, Patrik Okanovic, Andreas Kirsch, Torsten Hoefler, Nezihe Merve G\"urel
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Enhancing Assessment of Self-Consistency in LLM Explanations using Perturbation Strength

**链接**: https://arxiv.org/abs/2609.30849
**作者**: Phuong Q. Le, Kemal Kurniawan, Jey Han Lau
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior work has examined the self-consistency of LLM-generated explanations using surface-level perturbation methods. However, the strength of these perturbations is not explicitly measured and controlled. In this work, we propose an LLM-as-a-judge approach to measure perturbation strength in a unified manner across input and CoT perturbations. We then evaluate the self-consistency in explanations generated from various LLMs under controlled strength conditions, ensuring a fair comparison across perturbation types. Experiments show that our proposed LLM-based perturbation strength measure outperforms other embedding- and probability-based approaches and that input perturbations generally affect LLMs more strongly than CoT perturbations. Our work suggests that judgments about a model's self-consistency is fair only within the same perturbation type.

---

### [50] Asking For An Old Friend: Diagnosing and Mitigating Temporal Failure Modes in LLM-based Statutory Question Answering

**链接**: https://arxiv.org/abs/2605.23497
**作者**: Max Prior, Andreas Schultz, Matthias Grabmair
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] Learning Natural Conversational Behavior in Tandem Speech-to-Speech Models with Randomized Guidance

**链接**: https://arxiv.org/abs/2609.30773
**作者**: Manato Yaguchi, Yotaro Kubo, Hikaru Asano, So Kuroki
**来源**: cs.CL eess.AS
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tandem speech-to-speech architectures couple a responsive speech frontend with an asynchronous text backend. In KAME, a large language model (LLM) serves as the backend, supplying candidate responses as guidance to the speech frontend while the user is still speaking. Ordinary conversation recordings capture the eventual response but not the guidance the backend would supply during the user's utterance. Generating the missing guidance with a simulator LLM adds substantial data-preparation overhead when training on real conversations. We propose randomized intermediate guidance, which derives guidance directly from the conversation corpus rather than simulating backend LLM behavior. During training, target responses provide informative guidance, while randomly sampled responses provide potentially irrelevant updates during the utterance. This combination aims to teach the frontend to use backend information selectively. On synthetic dialogues, KAME trained with this recipe achieves resp

---

### [52] DynBranch: Speculative Subgraph Reuse for Dynamic Agentic LLM Serving

**链接**: https://arxiv.org/abs/2609.31047
**作者**: Junyi Shen, Noppanat Wadlom, Zhengyuan Su, Yao Lu
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic LLM workflows decide their execution paths at runtime. Downstream computation may be predictable, or may have run before, yet it cannot begin until the model or the user resolves the branch. We call this serialization the branch-resolution barrier. Caching alone does not hide it: the key that identifies a reusable result is not known until then. In this paper, we propose DynBranch, which makes an unresolved branch addressable before it resolves. Its stable coordinate lets candidate subgraphs run during resolution and completed subgraph results be reused across later requests. A two-level controller admits this work when its expected benefit exceeds the load price. DynBranch sits at the model-API boundary and requires no changes to agent harnesses or model execution engines. Across four agentic workloads with Qwen3-32B on 4x H200 GPUs, DynBranch reduces mean latency by up to 32% over each workload's strongest prior system and by 46-66% against a no-reuse floor, while preserving 

---

### [53] Calibrated Enough to Know, Not Calibrated to Act: Fabricated Evidence Makes LLM Agents Commit to the Unknowable

**链接**: https://arxiv.org/abs/2608.27167
**作者**: Pranav Aggarwal
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Effects of Transcript Compression on LLM-based Medical Misinformation Detection in Japanese YouTube Videos

**链接**: https://arxiv.org/abs/2609.30882
**作者**: Yuya Wake, Sho Tsugawa, and Toshiyuki Amagasa
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to assess long-form medical videos, but their effectiveness may depend on whether transcripts are provided in full or compressed through summarization, retrieval, or claim screening. This study examines how such transcript compression affects LLM-based veracity classification of Japanese medical YouTube videos. We compare four transcript input designs: full transcripts, LLM-generated summaries, RAPTOR-based retrievalaugmented generation (RAG), and Screening, which extracts candidate medical and health-related sentences. Using 74 long-form videos labeled as Real or Fake, we evaluate classification performance and analyze linguistic changes using J-LIWC, hedge expressions, and institutional or technical terms. The full-transcript Baseline achieved the best performance, whereas all compressed inputs increased false negatives, meaning that Fake videos were more likely to be misclassified as Real. Summary caused the largest performance drop

---

### [55] Rufus-Air: An Open LLM Post-Training Recipe

**链接**: https://arxiv.org/abs/2609.29421
**作者**: Chia-Yuan Chang, Renyuan Cheng, Rui Feng, Xiaotian Han, Yuan He, Hongye Jin 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Breaking Homogeneity: Diversifying Persona Sets for Creative LLM Outputs

**链接**: https://arxiv.org/abs/2609.30492
**作者**: Sang Bin Moon, Nicole Cho, Daniel Borrajo, Sumitra Ganesh and Abolfazl Hashemi
**来源**: cs.CL cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models often produce homogeneous responses to open-ended tasks; such homogeneity can spawn groupthink-the convergence of ideas toward a singular and potentially suboptimal decision. We formulate persona diversification as a set-level conditioning problem and study two orthogonal design choices: selecting versus generating personas, and space-filling versus frontier-seeking diversity. We instantiate this design space with four methods spanning coverage and dispersion subset selections, uniform-coverage sampling, and evolutionary persona generation. Evaluations on the Alternative Uses Task (AUT), Infinity-Chat, and Divergent Association Task (DAT) show the benefits of the proposed methods across tasks and creativity objectives. On AUT, evolutionary persona generation increases response diversity by 78.8%, originality by 26.1%, flexibility by 49.5%, and holistic creativity by 13.9% over task-only prompting, while maintaining 98.5% validity; on Infinity-Chat, it nearly doubles per

---

### [57] "If You're Not Doing It, Somebody Else Is": Active Negotiation and the Invisible Labor of Sustained LLM Use

**链接**: https://arxiv.org/abs/2609.30699
**作者**: Matt Viana, Patrick Erickson, Shomir Wilson, Dana Calacci
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have become fixtures of academic work even as their users describe them as degrading their writing, thinking, and skills. Dominant adoption frameworks read continued use as evidence of satisfaction, and cannot explain continued use of a distrusted tool. We interviewed 36 graduate student workers, balanced between English-as-a-foreign-language (EFL) and non-EFL speakers, and introduce the Active Negotiation framework: a model of sustained LLM use as a recurring cycle of risk, mitigation, and justification. A failure surfaces a risk, mitigation labor addresses it, and a justification renders the residual risk tolerable until the next failure reopens the cycle. The cycle runs across three dimensions: practical, auditing output; internal, auditing one's own cognition and identity; and social, managing how peers and institutions perceive use. EFL participants invoke linguistic parity as a further justification. We reframe continued adoption as compliance sustain

---

### [58] What Do They Fix? LLM-Aided Categorization of Security Patches for Critical Memory Bugs

**链接**: https://arxiv.org/abs/2509.22796
**作者**: Xingyu Li, Juefei Pu, Yifan Wu, Xiaochen Zou, Shitong Zhu, Qiushi Wu 等 (10 人)
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Audio LLMs Know When They Can't Hear You

**链接**: https://arxiv.org/abs/2609.30625
**作者**: Amirhosein Javadi, Richa Dixit, Mehrdad Farajtabar, Minsik Cho, Devang Naik, and Mohammad Samragh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio large language models allow users to interact with the model through speech. When an input recording is too degraded, the model may misinterpret the user's query and respond based on an incorrect transcription. In this paper, we study model-conditional transcription reliability: whether an Audio LLM can recognize when its own transcription is unreliable. We first prompt the Audio LLM to assess whether its own transcription would be reliable, and find that the model is a poor judge of its own transcription reliability: in most cases, it predicts that its transcription will be reliable. We find that existing approaches, including speech quality predictors, audio LLM generation uncertainty, and transcript-conditioned WER estimation, provide limited signals for detecting transcription failures. In contrast, we discover that transcription reliability is strongly represented in the model's audio-encoder representations. Based on this observation, we devise a lightweight reliability pre

---

### [60] MACBT: A Multi-Agent Cognitive Behavioral Therapy Decision Support System with Longitudinal Memory

**链接**: https://arxiv.org/abs/2609.30939
**作者**: De Jiang, Shuo Zhang, Weiwei Liao, Jianying Zhang, Chuanhui Yu, Hongen Liao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cognitive behavioral therapy (CBT) is an evidence-based first-line treatment for depression, yet its scale is constrained by the time clinicians spend on pre-session preparation, post-session documentation, and longitudinal cognitive-pathology tracking. We present a clinician-facing AI decision-support system that combines a multi-agent CBT framework (MACBT) with a CBT-specific longitudinal memory module (CD Memory). MACBT encodes the five-stage CBT workflow (assessment, Socratic questioning, cognitive restructuring, behavioral experiments, and treatment monitoring) into five collaborative agents. CD Memory tracks cognitive-distortion type, frequency, severity, and restructuring efficacy across sessions to generate pre-session pathology reports and intervention-priority recommendations. We construct a Chinese CBT dialogue corpus via dual-role large language model simulation and train a Qwen3-14B backbone with supervised fine-tuning and direct preference optimization. Evaluation with GP

---

### [61] Can Linguistic Reasoning Vectors Enhance Multimodal Reasoning Ability?

**链接**: https://arxiv.org/abs/2609.31140
**作者**: Ziyi Wang, Li Li, Aolin Zhou, Yankun Shen, Chonghan Liu, Shuxia Lin 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most Vision-Language Models (VLMs) are built by extending pretrained Large Language Models (LLMs) with visual modules and multimodal alignment. However, this multimodal scaling often degrades the language-side reasoning ability originally encoded in the base LLM. While the base LLM retains usable reasoning after scaling, the aligned VLM itself cannot reliably access this ability. Therefore, recovering the degraded reasoning capability in VLMs would benefit more from seeking help from the base LLM than from the VLM alone. Motivated by this, we propose LIFT (Language-side reasonIng Facilitation and Transfer), a lightweight vector-intervention method that transfers reasoning capability from the base LLM to the VLM without retraining the backbone. LIFT defines Reasoning Vectors as answer-token hidden-state differences between a Reasoner path with an explicit reasoning trace and a Solver path without it, and injects these vectors into language-side activations of the target VLM. LIFT furthe

---

### [62] A Framework for Identifying, Categorizing, and Explaining Bias in AI-Generated Code

**链接**: https://arxiv.org/abs/2609.30642
**作者**: Manaal Basha, Aimee M. Ribeiro, Gema Rodriguez-Perez
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Models (LLMs) become integrated into software development workflows, concerns regarding unintentional biases in AI-generated code. Although evidence suggests these biases exist, limited research has systematically identified, categorized, and explained them. This study investigates bias in AI-generated code and evaluates whether LLMs can reliably identify and explain it through a taxonomy-driven framework. We extended an existing dataset of biased AI-generated Python code and manually annotated snippets with bias categories and human-authored justifications to establish a ground-truth dataset. Using this dataset, we evaluated proprietary and open-source LLMs as automated bias detection and justification systems through ICL. Finally, we analyzed similarity between LLM-generated explanations and human-authored justifications using structured justification and code identification metrics. Our findings demonstrate that LLMs can effectively support code bias identification

---

### [63] Where Does Retrieval-Based Open-Ended Evaluation Fail? Automatic Taxonomy Induction from Long-Form Medical Answer Factuality Verification

**链接**: https://arxiv.org/abs/2609.30467
**作者**: Heyuan Huang, Jirui Dai, Alexandra DeLucia, Sonal Joshi, Mahsa Yarmohammadi, Jie Gao 等 (8 人)
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-based factuality evaluation, where LLM-generated claims are verified against evidence from authoritative medical corpora, has become the dominant paradigm for scalable hallucination detection in high-stakes clinical settings. Despite the urgency of reliable and transparent medical fact verification, most systems measure performance with aggregate metrics like F1, which obscure where and why failures occur. Existing RAG diagnostics require gold answers or annotated gold evidence, neither of which exists in this regime. We introduce two comprehensive taxonomies, grounded in a case study on the open-ended MedExpert dataset and 3 closed-ended datasets, decomposing failures into retrieval-stage errors along five quality dimensions, and verifier-reasoning errors into six consecutive steps. We adapt an automatic pattern induction pipeline using LLM-as-Judge to label evidence quality and classify verifier reasoning errors at scale, and then stress-test our findings across 4 retrieval

---

### [64] CARGO: Context-Aware Retrieval-Gated Evaluation of Agentic AI in Production

**链接**: https://arxiv.org/abs/2609.30471
**作者**: Mukul Chhabra, Shail Patel, Luigi Medrano
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reference-based LLM-as-a-judge evaluation assumes the reference answer is the target. In deployed agentic systems that operate over dynamic entities (support cases, assets, accounts), the closest available reference typically applies the correct procedure to a different entity, so a literal judge penalizes different identifiers, dates, and statuses as errors or hallucinations. We name this failure mode reference-instance divergence (RID). We propose CARGO, a framework that (i) treats retrieved references as procedural exemplars and grounds factual judgments in the live instance's observed context, (ii) assigns each claim a three-way status (supported, contradicted, unverifiable) and penalizes only contradictions, and (iii) gates evaluation by retrieval confidence, casting production evaluation as selective prediction. We introduce CARGO-Bench, a perturbation-based diagnostic suite with ground truth by construction that separates leniency from discrimination. On CARGO-Bench (246 items, 

---

### [65] The KV Cache Is the New Memory Wall

**链接**: https://arxiv.org/abs/2609.30854
**作者**: Tejinder Singh
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive LLM inference at long context is bounded by memory bandwidth, not arithmetic throughput, and the binding resource shifts from model weights to the Key-Value (KV) cache as sequence length grows. For Llama-3-70B in BF16, the 140 GB weight footprint exceeds the 80 GB HBM of a single accelerator, and one 128k-token sequence adds 42 GB of KV cache. Techniques that compress, evict, page, share, or offload KV state have proliferated, but reported gains use inconsistent workloads, hardware, and quality metrics, preventing cross-paper comparison. This SoK paper unifies the field analytically, with a protocol that strictly separates derived and reported claims. We derive closed-form arithmetic intensity as a decaying function of context length, parameterized by hardware topology for NVIDIA H100, NVIDIA B200, and AMD MI300X, including per-die bandwidth partitioning and the crossover lengths where KV traffic overtakes weight traffic. We classify the literature into five domains, qua

---

### [66] Estimating and Orthogonalizing Unknown Pre-training Gradients for Continual Fine-tuning of Large Language Models

**链接**: https://arxiv.org/abs/2609.30935
**作者**: Bing Wang, Changchun Li, Xin-Qiang Cai, Lin Yuanbo Wu, Ximing Li, Gang Niu 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual fine-tuning is essential for large language models (LLMs) to dynamically adapt to real-world environments, yet it inevitably suffers from catastrophic forgetting, particularly the performance degradation of previous tasks and LLMs' general-purpose knowledge. Although existing methods, such as orthogonal gradient projection, mitigate the forgetting across various fine-tuning tasks, they fundamentally fail to preserve pre-training LLMs' inherent general-purpose knowledge because the original data and gradients of off-the-shelf pre-training LLMs required by these methods are strictly unknown and highly diverse. To bridge this critical gap, we propose EoupCT, a novel framework designed to Estimate and Orthogonalize Unknown Pre-training gradients for Continual LLM fine-Tuning. Specifically, EoupCT estimates pre-training gradients by dynamically generating pseudo data that is most susceptible to forgetting for new tasks through a learnable soft prompt equipped with Gumbel-Softmax r

---

### [67] A Benchmark Framework for Screening Automation in Systematic Reviews

**链接**: https://arxiv.org/abs/2609.30298
**作者**: Gauransh Kumar, Luciano Marchezan, Guillaume Genois, K\'evin Delcourt, Eugene Syriani
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematic reviews (SR) are essential for evidence-based research, but their screening phase is highly time-consuming and labor-intensive. Large language models (LLMs) offer a promising opportunity to reduce this workload by assisting with article relevance classification. However, existing evaluation approaches often rely on traditional metrics that may be misleading for highly imbalanced SR screening datasets.This paper presents a benchmark dataset of $45\,064$ labeled entries for evaluating LLM performance in SR screening across 32 curated secondary studies. It proposes an evaluation framework that accounts for class imbalance, i.e., the natural prevalence of excluded articles relative to included articles in SRs. It also introduces PromptSR, a tool designed to support prompt experimentation, experiment management, and result analysis for LLM-based screening. We also present a use case demonstrating the application of SRBench and PromptSR.

---

### [68] SignTrace: Describe a Sign, Find the Word

**链接**: https://arxiv.org/abs/2609.30295
**作者**: Zengji Tu, Xingye Zhu, Ningjing Wang, Tingyi Huang, Yangjunfeng Zhu, Dai Wan
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Identifying an unfamiliar sign is difficult when a learner remembers its movement but does not know its meaning or formal feature codes. SignTrace addresses this longstanding reverse-lookup problem through natural-language access to a Chinese sign-language dictionary. The system integrates LLM-based dictionary enrichment, action extraction, dictionary-style rewriting, seven-channel retrieval, and candidate reranking over 6,699 entries. It has been deployed for user trials and has received positive informal feedback. Evaluation on a dictionary-derived benchmark of 500 movement-description queries yields 94.0% Hit@1, 97.4% Hit@9, and a mean reciprocal rank of 0.9540. Reranking increases Hit@1 from 71.8% to 94.0%, while component analyses show the contribution of enriched entry descriptions. Median query-processing time is 13.37 seconds with six concurrent queries. By connecting everyday movement descriptions to documented signs and meanings, SignTrace provides a practical tool for identi

---

### [69] Multi-agent Scaling Across Disjunctive and Compensatory Tasks

**链接**: https://arxiv.org/abs/2609.31563
**作者**: Carolina Fortuna, Blaz Bertalanic
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are often expected to improve as team size increases, yet the scaling behavior may depend on task structure. Our central contribution is to introduce Steiner's taxonomy of group tasks as a framework for analyzing multi-agent LLM scaling and focusing the analysis on disjunctive and compensatory tasks. We model independently sampled agents as conditionally independent given the item, which yields their large-team limits: plurality voting converges to the model's modal answer, and averaging converges to the model's item-level bias. Across selected representative benchmarks, 13 open-weight models, and teams of up to 30 agents, we find qualitatively different scaling behavior. On disjunctive tasks, the probability that at least one agent is correct grows by 5-20 points with team size, but plurality voting over agents that answer directly realises almost none of this potential, as the model predicts to within 0.5 points on average. Multi-round revision raises accuracy

---

### [70] REALMS: An AI-Assistant Conversational System for Real-Time Exact Audience Sizing over High-Dimensional Nested Profiles

**链接**: https://arxiv.org/abs/2609.30547
**作者**: Haixu Ma, Aditya Bansal, Shubham Lohiya, Sumit Ranjan
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audience sizing is a critical component of digital marketing. It enables precise resource allocation, campaign planning, and performance optimization. Traditional approaches using skeleton audiences, sampling, or predictive modeling suffer from significant delays, estimation errors, and poor scalability over high-dimensional profile data. We present REALMS (Real-time Exact Audience sizing via LLM-based Multi-attribute Search), a conversational system for exact audience sizing deployed in production on an enterprise customer data platform. REALMS enables marketers to query massive profile stores with millions of profiles and thousands of attributes using natural language and receive precise counts in seconds. The system introduces three key components: (1) a categorical attribute retrieval mechanism using embedding-based vector search to dynamically identify relevant schema attributes without manual configuration; (2) an LLM-powered NL2SQL pipeline with template-based in-context learnin

---

### [71] Prompt Injection Detection for Email Agents Through Attack Chain Modeling

**链接**: https://arxiv.org/abs/2609.30657
**作者**: Ahmad Hashmi, Dhyey Patel, Yunting Yin
**来源**: cs.CR cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model email assistants are particularly vulnerable to indirect prompt injection because untrusted email content can be retrieved into the model context and influence subsequent tool use. Existing prompt injection detectors mainly formulate this problem as binary malicious text classification, which overlooks the important factor that harmful agent behavior often arises through a sequence of stages. We propose a detection framework that models this attack chain by combining a text detector, verifiers specific to each stage, explicit rule-based risk signals, user intent and action consistency analysis, and a logistic decision policy. To support this framework, we derive attack chain labels from prompt injection datasets, evaluate the proposed framework under random splits, temporal phase transfer, conditional stage transfer, cross-dataset transfer, and conduct ablation studies on multiple benchmarks. Results show that random train test splits substantially overestimate rob

---

### [72] RupeeBias: Auditing Demographic Bias in Indian Economic Guidance from Large Language Models

**链接**: https://arxiv.org/abs/2609.31245
**作者**: Pavithra P M Nair, Bhavik Talaviya, Shourya Bhushan, Rahul Pankajakshan, Seema Guruvadoo, Avinash Agarwal 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Individuals turn to large language models (LLMs) for guidance across a wide range of economic tasks, from comparing loan options and planning savings to deciding what raise to ask for or how much to charge for their services. LLMs are known to reproduce social biases, and biased economic guidance may influence what users believe they are worth, what they ask for, and what they ultimately accept. This risk is especially salient in India, where economic outcomes are shaped by demographic categories such as caste and urban-rural location. Existing LLM bias benchmarks, however, are largely designed around Western demographic categories and therefore miss key axes of economic disparity in the Indian context. We introduce RupeeBias, a benchmark for auditing demographic bias in LLM-generated economic guidance across Indian economic settings. RupeeBias consists of 39,150 prompts spanning four use cases: salary estimation, salary increment estimation, counter-offer recommendation, and service p

---

### [73] LAVOIR: Teaching a Single-Pass Decision Encoder When and What to Ask with Amortized Value of Information

**链接**: https://arxiv.org/abs/2609.30706
**作者**: Furkan Yilmaz and Habibe Aleyna Tasdemir and Muhammed Faruk Gozay
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> "System One" decision models such as TypeSafe's Jev and its open counterpart Laya answer typed questions about a text in a single forward pass with calibrated probabilities, but they cannot ask for missing information: when a first message does not say what separates two departments, they guess. We present LAVOIR (Laya with Value-Of-Information Routing), which places the candidate pieces of missing information (slots) in the input next to the answer options, so that one forward pass returns both the decision distribution and, for every slot, the expected gain in the probability of the correct decision if the user were asked about it. VOI targets need no human labels: gold decisions come from schema rules, an LLM only verbalizes messages and answers, a model from another family checks every text, and pairing each message with several profiles makes regression on realized gains estimate the expected gain. A Gini-impurity cap bounds the predicted value by what a calibrated model can still

---

### [74] AgentWorld: Benchmarking Long-Horizon Collaboration of Multi-agent LLMs

**链接**: https://arxiv.org/abs/2609.31590
**作者**: Raphael Shu, Yusen Zhang, Young Min Cho, Jin Mo Yang, Yuan Yuan, Wenliang Zheng 等 (10 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing multi-agent benchmarks primarily test in competitive settings, short-horizon interactions under 20 steps, or simply aggregate individual performance, failing to isolate and highlight genuine collaboration capabilities of LLM-based agents. We introduce AgentWorld, a benchmark of 100 human-annotated tasks (with 100 augmented variants) for evaluating long-horizon, multi-agent collaboration. Tasks span 50+ interaction rounds across a rich MMORPG sandbox and require 3-20 agents with asymmetric roles and abilities to coordinate through communication, joint planning, and resource sharing under a blackbox setting where each agent acts independently without access to others' internal states. To quantify collaboration effectiveness in addition to conventional binary task success, we propose Causal Collaboration Effectiveness (CCE), a graph-based metric that traces causal dependencies between agent actions and measures what fraction of a team's effort actually contributed to the outcome.

---

### [75] CG-Probes: Recovering Guardrail Directions from Patient Query Embeddings

**链接**: https://arxiv.org/abs/2609.31062
**作者**: Marko \v{R}eh\'a\v{c}ek, V\'it\v{e}zslav Du\v{s}ek, Martin Rusinko, V\'it Nov\'a\v{c}ek
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patient-facing AI assistants promise valuable support to patients, but incoming queries can pose medical risks. To create guardrails, we work with oncologists to define three ordinal risk axes: Medical Urgency, Psychological Urgency, and Topic Sensitivity. We propose Clinical Guardrail Probes (CG-Probes) to measure the risks from query embeddings. We probe for each axis in the normalized embedding space of frozen embedders via the difference-in-means method, treating each axis as a potential linear direction. To train the probes, we cluster 79,658 Czech oncology search queries with BERTopic and use these clusters to generate pairs of queries with contrastive risk levels via few-shot prompting. We evaluate the approach on 200 queries (90 real, 110 synthetic), each graded by two oncologists, against two open-weight LLMs and a frontier LLM. We find that urgency-based axes are recoverable as linear directions, and the probes are competitive with open-weight LLMs (no significant differences

---

### [76] Subjects, Not Authors: The Authorship Hazard in Agentic Dataspaces

**链接**: https://arxiv.org/abs/2609.30614
**作者**: The Authorship Hazard in Agentic Dataspaces Authors: Seungho Lee, Changbin Lee
**来源**: cs.CR cs.AI cs.DB cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dataspace connectors decide whether a transfer may occur, not what the transferred value contains, tolerable for contracted applications, not for LLM agents that compose tool calls and spawn sub-agents. Research on agents that generate governance artifacts evaluates output quality; who may authorize an artifact for use falls between that literature and the governance literature, and neither owns it. A published policy is what a dataspace's decision point enforces, so publication is a governance event, and an agent that is both policy subject and policy author writes the norms that bind it. We name this the authorship hazard and state one principle: an agent is a subject of the governance plane, never an author of it. Its authorization channel to publication is closed by construction; its influence channel, drafting what humans approve, is treated as an enforcement problem. On a frozen corpus of agent drafts, publishing without approval reverses 80 authorization decisions, most through 

---

### [77] Do LLMs Understand Context? A Knowledge Graph-Based Evaluation Framework

**链接**: https://arxiv.org/abs/2609.30484
**作者**: Subavarshana Arumugam, Mamta Nallaretnam, Kithuni Wickramasinghe, Chamath Gunapala, Pragatheeswaran Vipulanandan, Kamal Premaratne 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While large language models (LLMs) have achieved remarkable linguistic capabilities, a profound question lingers at their core: do these models truly comprehend context or simply excel at pattern matching on an unprecedented scale? Contextual understanding in LLMs refers to the ability to correctly extract relevant information from a given context, integrate it into a coherent internal representation, and reason over it to produce factually consistent and contextually grounded responses. However, traditional methods such as BiLingual Evaluation Understudy (BLEU) and perplexity simply measure surface-level performance. This reveals a critical gap in question answering (QA), where responses must be contextually grounded rather than simply being memorized associations. To fill this void, we propose a novel knowledge graph (KG) based evaluation framework for LLM contextual understanding in QA. Central to this is Semantic Structural Similarity for KGs (S3KG), a hybrid similarity measure com

---

### [78] SPO: Discovering Adaptive Large Neighborhood Search Operators via Stackelberg Program Optimization

**链接**: https://arxiv.org/abs/2609.31179
**作者**: Xinyi Ke, Kai Li, Junliang Xing, Yifan Zhang, Jian Cheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large neighborhood search (LNS) relies critically on destroy and repair operators, whose effectiveness depends on both adaptation to the evolving LNS state and interaction between the two roles. We introduce Stackelberg Program Optimization (SPO), an LLM-based framework for discovering adaptive executable destroy-repair programs. SPO conditions operator decisions on a compact LNS state, allowing state-dependent behavior to emerge through program discovery, and organizes destroy-repair discovery as a Stackelberg interaction over program space that reflects their asymmetric dependency. Role-specific credits evaluate destroy programs as leaders and repair programs as conditional follower responses, guiding a coupled optimization process that combines LLM generator learning with population-based evolutionary search over programs. Experiments on the traveling salesperson problem and capacitated vehicle routing problem show that SPO outperforms strong baselines across a broad range of settin

---

### [79] Towards Mitigating Fabricated Consensus: The Active Provenance Gate for Multi-Agent Debate Synthesis

**链接**: https://arxiv.org/abs/2609.31422
**作者**: Jakub Mas{\l}owski, Jaros{\l}aw A. Chudziak
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based multi-agent debate (MAD) systems are being increasingly used as complex decision pipelines in distributed processes. However, their final synthesis phase still remains inadequately controlled. Even with detailed debate logs, summarizing models are prone to fabricating smoothly written debate consensus that is not grounded in the debate's history. To address this safety gap, this paper presents empirical research and studies if the introduction of active post-debate verification can mitigate the production of such factually unsupported summaries, while still providing valuable information. Furthermore, it is examined whether explicitly signalling divergence is preferable in the absence of a reliable compromise. The Active Provenance Gate (APG) is introduced as a post-debate verification layer that treats the source as a hard constraint, analysing the debate logs, auditing each claim, and applying self-correction. In crisis simulations, the self-healing mechani

---

### [80] User Model Extraction via Belief Self-Distillation

**链接**: https://arxiv.org/abs/2609.31603
**作者**: Ali Holmov, Yiran Huang, Kirill Bykov, Zeynep Akata
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) implicitly infer attributes of their users and adapt their behavior accordingly, yet these beliefs remain difficult to inspect and causally manipulate. We introduce Belief Self-Distillation (BSD), a unified read-write framework that bridges linear and causal probing by learning a compact user representation that can be both decoded and written back into the model. The frozen LLM acts as its own teacher, distilling beliefs from natural conversations without external annotations. Unlike conventional probing, BSD isolates not only information present in activations, but a state whose causal role can be directly tested. Across multiple model families, BSD faithfully recovers user beliefs and enables substantially stronger interventions than matched hidden-state steering. Crucially, we find that refusal depends not only on the request, but on the model's inferred user intent: changing this belief alters refusal while holding the request fixed. We further uncover

---

### [81] The Hard Part Comes After Search: Benchmarking Web Agents on Synthesizing, Organizing, and Displaying Knowledge

**链接**: https://arxiv.org/abs/2609.30604
**作者**: Alexander Gill, Md Farhan Ishmam, Xuyen Nguyen, Neha Bhat, Parker Henry DeYoung, Fateme Hashemi Chaleshtori 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing computer-use agent benchmarks do not fully evaluate agents acting as assistants. A useful assistant retrieves information across complex, multi-step workflows, synthesizes it into artifacts (documents, presentations, spreadsheets), and navigates program interfaces to produce a coherent final product. Such workflows demand reasoning and synthesis, decomposition of complex tasks, as well as visual and spatial understanding. To study agents on workflows like these, we introduce KNOWS, a benchmark of open-ended, complex, browser-based tasks that jointly evaluate these capabilities, with each task culminating in a produced artifact. To write tasks, we develop a task design rubric and a protocol for ensuring that tasks meet the requirements. Each task is paired with an evaluator, a program that combines deterministic checks with LLM judgments to balance the richness, reliability, and automation tradeoff inherent to agent evaluation. We evaluate and analyze frontier computer-use agen

---

### [82] Pretrained ASR Pseudo-labeling for Noisy Police Audio

**链接**: https://arxiv.org/abs/2609.30469
**作者**: Kaavya Chaparala, Su Huang, Stephen L. Miller, Rhiannon N. Miller, Anjalie Field
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained ASR systems perform poorly on noisy Broadcast Police Communication (BPC), hindering efforts to understand police decision-making. Pseudo-labeling offers an unsupervised path to improve ASR without expensive human labels, but the efficacy of this approach on very noisy domains is not known. In this work, we systematically assess the opportunities and limits of pseudo-labeling to adapt foundation ASR models (Whisper and Qwen3-ASR) to noisy BPC domain corpora from Baltimore and Chicago. We demonstrate that existing internal confidence metrics (log-probabilities and STAR scores) fail to distinguish between high and low quality BPC pseudo-labels, and we introduce an external LLM-as-a-judge filtering paradigm that leverages parametric knowledge to discard contextually implausible transcripts. Our LLM-judging filters more aggressively than internal metrics and significantly reduces WER of the pseudo-labeled training sets across the Baltimore and Chicago BPC corpora, though a substa

---

### [83] EAServe: Encode-Aware Disaggregated Serving for Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2609.31551
**作者**: Kunxiong Zhu, Zhihao Shu, Hangyu Zheng, Minghai Qin, Miao Yin, Gagan Agrawal 等 (7 人)
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Disaggregating the two stages, Prefill and Decode, onto separate GPU pools is now a standard optimization for (text-only) LLM serving. However, multimodal LLMs (MLLMs), which add a third phase, Encode, pose new challenges for resource allocation. Encode turns images, video, or audio into embeddings that the language model can consume, yielding a three-stage Encode-Prefill-Decode (EPD) pipeline. Existing frameworks offer only partial answers: text-only PD systems lack Encode, while EPD frameworks expose it as a separate service without regulating downstream request flow. The pipeline also carries a structural resource imbalance: every request enters through Encode before downstream work can begin, yet per-request execution leaves the encode GPU severely underutilized even at high loads, starving the downstream Prefill and Decode workers. Addressing this, we reposition Encode as the control point of the EPD pipeline, exposing three tightly coupled dimensions: when work enters downstream,

---

### [84] A Survey on Fake Review Detection: From Pre-trained Language Models to Large Language Models

**链接**: https://arxiv.org/abs/2609.30292
**作者**: Fanji Yang (1), Huiyao Chen (2), Xi Yu (1), Meishan Zhang (2), Xiaohong Xiao (3), Mingsen Deng (1) ((1) Guizhou University of Finance and Economics 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online reviews shape consumer decisions, platform governance, and corporate reputation.Fake reviews compromise this information channel by injecting deceptive evidence into rating systems, recommendation pipelines, and public trust mechanisms.The rise of large language models, or LLMs, has changed the problem in two directions.LLMs can generate fluent and context-aware deceptive reviews, while pre-trained language models, or PLMs, and LLMs also provide stronger semantic representations for detection.This survey reviews fake review detection from an information fusion perspective, covering 211 studies published from 2018 to early 2026.We organize existing work by evidence source and fusion level, covering review text, sentiment, rating behavior, temporal metadata, user-product graphs, multimodal content, external knowledge, and LLM-generated signals.We trace the development from traditional machine learning and deep learning to PLM-based and LLM-based methods, and examine how different 

---

### [85] Semantic Navigation for Issue Localization in Code Repository

**链接**: https://arxiv.org/abs/2609.31176
**作者**: Yunxiang Wei, Zhenyu Lei, Jundong Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repository-level issue localization aims to identify and rank the files and functions relevant to resolving a reported issue. LLM agents approach this task iteratively: they identify a set of potentially relevant locations, inspect the corresponding code, and revise their judgments about these candidates as new evidence is acquired. Existing environments, however, provide limited support for this loop: agents must search for unresolved relation targets, reconstruct entity semantics from raw source code, and revise candidates without evidential basis. To address these limitations, we present SemNav, a framework that leverages deterministic retrieval to seed a broad candidate set and an LLM agent to continually refine that set, thereby combining initial coverage with evidence-guided revision. SemNav supports this process through three key components. A Semantic Navigation Graph resolves program relations on demand through a language server, enabling direct navigation to related entities 

---

### [86] New LoRA Skills Should Read but Never Write

**链接**: https://arxiv.org/abs/2609.31600
**作者**: Zeyan Li, Panqi Yang, Qirong Guo, Shengda Zhuo, SIyuan Qiu, Hu Xu 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-rank adapters (LoRA) make it cheap to fine-tune a large language model once per task, but combining several independently trained adapters into one model remains difficult: merging the updates in weight space causes interference, retraining on all task data is expensive, and routing between separate adapters gives up the goal of a single combined model. We trace the difficulty to two choices that every composition method makes implicitly. A LoRA update admits infinitely many equivalent factorizations; the choice among them is invisible while an adapter serves alone, but it determines what a learned interaction between adapters can see. A coupling between an old skill and a new one can likewise point in either direction, and the direction decides whether the old skills keep computing what they computed before. We introduce READ (Read-only Expansion of Adapter Deltas), which fixes both choices: each adapter is rewritten into a balanced canonical form that preserves its update exactly

---

### [87] Symbiotic Architecture for Post-Hoc Audio Extension of Frozen Language Models

**链接**: https://arxiv.org/abs/2609.30784
**作者**: Yotaro Kubo, Qi Sun, Yujin Tang
**来源**: cs.SD cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper proposes an architecture for equipping large language models (LLMs) with audio-understanding capabilities without fine-tuning their weights. The proposed symbiotic architecture employs an injector module that writes audio-conditioned vectors directly into the target LLM's short-term memory, i.e., the key-value (KV) cache, enabling the LLM to behave as an audio language model (ALM). The architectural advantages are twofold. First, it improves the scalability of ALMs: because the proposed method bypasses the LLM during audio injection, the injection cost is governed by the injector width rather than the backbone width, and can therefore scale more slowly than the cost of full-backbone prefilling. Second, since the training scheme does not update the LLM weights, the original capabilities of the LLM are preserved without the risk of degradation from fine-tuning. The effectiveness of the proposed method is evaluated on both audio-understanding tasks (automatic speech recognition

---

### [88] Strategically Diverse Sampling for Self-Training

**链接**: https://arxiv.org/abs/2609.31571
**作者**: Alexander Gurung, Esmeralda S. Whitammer, Mirella Lapata
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many LLM training and inference methods, including RL and test-time scaling, depend on repeated sampling, but benefit only when the responses meaningfully differ. Self-training faces the same challenge: training data is typically constructed by sampling IID responses and filtering primarily for correctness, thereby overrepresenting strategies a model already favours. We investigate strategic diversity, or substantive variation among approaches to a problem, as an alternative principle for constructing self-training data. We generate strategically diverse data with two sampling methods: GROOT, a new method which constructs a hierarchical tree of approaches and samples distinct paths, and Verbalized Sampling (VS), adapted to produce an unstructured set of approaches. Across competitive programming and Next-Chapter Prediction domains, models trained on strategically sampled data outperform IID-trained counterparts on difficult tasks and provide strong initializations for RL and test-time 

---

### [89] Feeding BabyLMs Macaroni: Code-Switching Curricula Cause Cross-Lingual Convergence

**链接**: https://arxiv.org/abs/2609.30535
**作者**: Dries Rooryck, Alex Cai, Yonatan Belinkov, David Alvarez-Melis, Kiant\'e Brantley
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Children in multilingual communities often code-switch, using multiple languages in a single utterance. Can we induce cross-lingual alignment in language models by training on code-switched text? We pretrain small decoder-only transformers on two 100M-word multilingual corpora: a base corpus formed by mixing the English, Dutch, and Chinese BabyBabelLM datasets, and a corpus generated from it by inserting word- and sentence-level code-switching using an LLM. We find that training on code-switched data aligns the representations of parallel text, particularly across different scripts, and that this alignment persists through training on monolingual documents. Under a learning curriculum that progresses from word-level code-switching, to sentence-level code-switching, to monolingual documents, models trained on code-switched data outperform baselines trained without it on the BabyLM evaluation suite. Our work characterizes code-switching curriculum learning as an effective data augmentati

---

### [90] Epstein Files Engine: Agentic Search for Investigative Journalism

**链接**: https://arxiv.org/abs/2609.30611
**作者**: Duy K. Nguyen, Teresa Mondr\'ia Terol, Dylan Freedman, Zach Seward
**来源**: cs.HC cs.CL cs.CY cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On Jan. 30, 2026, the U.S. Department of Justice released a mixed-media collection concerning Jeffrey Epstein, including about three million pages of PDFs. We describe the Epstein Files Engine, an A.I. agent The New York Times deployed to investigate the files. The Engine translated reporter questions into Google BigQuery SQL queries across three corpora: Epstein-related releases, the Times's archive and external, Epstein-related news headlines. It used an LLM to plan queries and returned citation-rich answers a reporter could verify and trust. More than 100 journalists used the Engine, and it contributed to at least 20 published stories. We report how reporters queried it and describe Diff, our text-and-visual duplicate matching method that amplified novelty signals and allowed the Engine to surface genuinely new information. We argue that newsroom agents serve newsrooms best not as autonomous writers, but as interfaces to source material and institutional knowledge.

---

### [91] Beyond Approved Actions: Runtime Validation of Persistent Outcomes in Agent Workflows

**链接**: https://arxiv.org/abs/2609.31301
**作者**: Haoran Zhang, Hengtong Zhang, Zhiyu Liang, Yu Yan, Decheng Zuo, Hongzhi Wang
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly act on software systems, no longer merely generating text but also changing databases and online services. However, an approved database update may succeed yet leave an unapproved notification because execution can produce persistent effects beyond the requested change. Current safeguards can approve an action or record its aftermath, but without checking the persistent result before continuation, an unapproved outcome can be accepted as success and propagated to later steps. We present EffectMatch, a runtime that collects persistent changes within a controlled execution boundary and compares them with what the application approved for the current state and execution. The comparison governs commit and dependent execution. In comparative evaluation on 206 public business tasks, EffectMatch preserved all clean executions and prevented all tested incorrect commits. Six 20-run ablations exposed the failure caused by each removed mechanism, while 80 

---

### [92] Muslim: A Deployed Arabic Voice AI Platform for Grounded Islamic Knowledge

**链接**: https://arxiv.org/abs/2609.31511
**作者**: Yahya Mohamed Elnawasany
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Muslim, a production Arabic voice AI platform serving grounded, sourced Islamic knowledge to real users. Beyond a real-time voice pipeline (NeMo Arabic ASR, an OpenAI-compatible LLM endpoint, self-hosted TTS) and a deterministic multi-source retrieval layer routed across six Model Context Protocol servers, we report three things a research prototype typically lacks. First, a released family of fine-tuned Arabic Islamic model artifacts: an efficient tool-routing LLM (Muslim-6B-PRO, 5.94B parameters) and a Modern Standard Arabic TTS model (Fasih-TTS-V1) that ranks 5th of 17 overall and 2nd of 11 open-weight systems on the community-voted Arabic TTS Arena for MSA. Second, an account and metering layer - a free per-account turn allowance, capacity-aware refusal, and email verification deferred to the point it actually matters - that turns an open demo into an operable, abuse-resistant product. Third, a three-layer observability stack (liveness, error reporting, product analytics

---

### [93] Prompt Minimization: Reducing Input Redundancy Without Sacrificing Output Fidelity

**链接**: https://arxiv.org/abs/2609.31505
**作者**: Marius F. R. Juston, Kevin A. Karim, Jonathan Gao, Kevin C. Li, Rudhi Bashambu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the growing capabilities of large language models (LLMs), prompt design remains largely heuristic and ad hoc. This project will explore $\textit{prompt minimization}$, the process of reducing prompts to their smallest, most information-dense form while preserving output fidelity. Practically, shorter prompts reduce computational overhead and inference latency, especially when large contexts, such as entire documents or codebases, are included unnecessarily. Further, longer prompts can damage LLM reasoning and accuracy. Theoretically, the existence of multiple prompts yielding equivalent outputs suggests a high degree of redundancy in the input space, raising fundamental questions about what information is essential to elicit specific model behaviors. We propose three variant frameworks to identify and evaluate minimal prompts and demonstrate that minimal prompts often produce outputs comparable to those of their longer counterparts. These findings suggest new directions for eff

---

### [94] BioEVAL: A global, multi-institutional benchmark of large language and multimodal models for bioengineering

**链接**: https://arxiv.org/abs/2609.30489
**作者**: Shun Ye, Vinny Chandran Suja, Chenlong Li, Chongming Jiang, Reza Zamani, Xiang Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have demonstrated historic breakthroughs in general reasoning with early successes in biomedical science. However, existing LLM benchmarking emphasizes factual recall, offering limited insight into model performance on frontier and multimodal tasks. We assembled BioEVAL (BioEngineering Validation of AI and LLMs), a global, multi-institutional initiative designed to assess experimental reasoning capability across bioengineering (BE) subfields. BioEVAL spans 11 major BE subfields plus a set of uncategorized items, bringing together 22 research groups to create a PhD-level benchmark comprising 608 evaluation items: 1) 380 multiple-choice questions (MCQs, 359 retained after audit), 2) 218 literature synthesis tasks, and 3) 10 multimodal problems with experimental image interpretation. Benchmark items underwent authoring-group expert review and centralized quality control before evaluation. Following evaluation, a blinded cross-group consensus audit of the highe

---

### [95] AutoResearch at Production Scale: Failure Modes and a Multi-Agent Framework

**链接**: https://arxiv.org/abs/2609.30541
**作者**: Aparajith Chandran, Juwon Kim, Saurav Jha, Pablo Castells, Florian Hottier
**来源**: cs.LG cs.IR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optimizing embedding systems for production recommendation pipelines demands systematic exploration that consumes disproportionate engineering effort at scale. We apply Andrej Karpathy's AutoResearch paradigm -- a large language model that iteratively edits a training script and retains modifications that improve a held-out scalar metric -- to automate this exploration. We report on twelve weeks of running this paradigm at production scale, where iterations consume hours of multi-GPU compute, evaluation involves competing criteria, and campaigns span weeks across many training jobs. Across two independently developed representation-learning systems for a book recommendation pipeline, we ran 220+ experiments and observed five recurring failure modes absent from the original setting: infrastructure fragility, agent memory decay, search-direction stagnation, iteration-cost asymmetry, and metric fixation. We contribute a three-principle scaffolding design -- prevent, persist, redirect -- t

---

### [96] Neural State Prediction: Obstructing Shortcut Learning in EEG Foundation Models

**链接**: https://arxiv.org/abs/2609.31167
**作者**: Kieren Yu, Ziyang Liu, Chang Huang, Jintai Chen, Kaishun Wu
**来源**: cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models increasingly use masked prediction to learn from unlabeled recordings, but optimizing this objective does not ensure transferable neural representations. A central challenge is that stable positional cues and local correlations can make masked regions predictable without integrating distributed neural context. To reduce this reliance on low-information prediction paths, we introduce Neural State Prediction (NSP), a latent-predictive framework that constrains both the prediction target and the available context. NSP uses a Target Encoder updated by an exponential moving average (EMA) to define latent supervision. Identity residualization removes additive effects associated with channel identity and relative time from the targets, while topology-separated context excludes their immediate spatial and temporal neighborhood from the visible input. We pretrain NSP on 2.2 million EEG segments from TUEG and evaluate it across 30 downstream datasets spanning clinical diagn

---

### [97] LEAD: An EEG Foundation Model for Alzheimer's Disease Detection

**链接**: https://arxiv.org/abs/2502.01678
**作者**: Yihe Wang, Nan Huang, Nadia Mammone, Marco Cecchi, Xiang Zhang
**来源**: cs.LG cs.AI cs.CE eess.SP
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [98] CDBG: Causally Motivated Dual-Invariance Learning against Topological and Predictive Shifts in EEG Workload Recognition

**链接**: https://arxiv.org/abs/2609.30831
**作者**: Yuzhe Zhang, Wenmin Zhou, Chengxi Xie, Kai He, Jihong Wang, Huan Liu 等 (8 人)
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generalizing Electroencephalography (EEG)-based mental workload recognition to unseen subjects remains a formidable challenge due to severe inter-subject variability. While functional brain graphs effectively model distributed cognitive dynamics, their inherent subject-specificity induces two coupled distribution shifts: a class-conditional topological shift in the underlying functional connectivity, and a predictive mechanism shift in the learned representation-to-label mapping. Motivated by the subject-induced distribution shifts, we propose CDBG, a Causally motivated Dual-invariance learning framework for Brain Graphs. CDBG disentangles and mitigates these shifts via a two-stage rationale learning pipeline. First, it employs stochastic edge masking to extract sparse, workload-predictive graph rationales, regularized by workload-conditional Laplacian spectral alignment to enforce topological invariance across subjects. Second, it applies subject-wise Invariant Risk Minimization (IRM)

---

### [99] From Segments to Trajectories: Evolving Affective Graphs with Evidence Retrieval for Continuous EEG Emotion Recognition

**链接**: https://arxiv.org/abs/2609.30890
**作者**: Chi Yang, Jihong Wang, Chengxi Xie, Kai He, Huan Liu, Man Yao 等 (8 人)
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG)-based emotion recognition is important for affective computing and human-computer interaction, yet most existing methods divide a long trial into short segments and assign each segment the label of its source trial. Although this strategy increases the number of training samples, it reduces an evolving emotional response to a segment-level, coarse-grained, and static prediction problem. In reality, emotion may continuously emerge, intensify, weaken, and fluctuate as a stimulus unfolds, motivating the prediction of a time-aligned affective trajectory from the complete EEG trial. This task requires coordinated modeling of how spatial neural organization evolves throughout the trial and how local emotional fluctuations interact with longer-term trends. In this work, we formally define and systematically investigate continuous EEG emotion recognition as whole-trial affective trajectory prediction. We propose EAGER, an Evolving Affective Graph framework with Evi

---

### [100] EEG-based Word Association Paradigm for Adult ADHD Screening: An Exploratory Pilot Study

**链接**: https://arxiv.org/abs/2609.31359
**作者**: Caroline Peng and Tony Russell-Rose
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the prevalence of Attention Deficit Hyperactivity Disorder (ADHD) over the past decades, healthcare systems across the globe face critical diagnostic challenges due to long diagnostic waiting times and a reliance on subjective behavioural assessments that cannot distinguish ADHD from comorbid psychiatric disorders, especially for adult patients. This exploratory study investigates whether EEG-based word association paradigms show promise as a complementary approach to screening for ADHD in adults. Using a mixed-method approach, the study examines neurological and cognitive differences between neurotypical individuals (NT), clinically diagnosed ADHD participants (ND), and self-reported ADHD cases awaiting formal diagnosis (SR) across three word association tasks. While established EEG biomarkers (ERP N400, Theta/Beta Ratio, and Alpha Suppression) show no significant group differences, semantic distance analysis reveals a statistically significant main effect ($p=0.003$), with the S

---

### [101] Subject-Invariant Cross-Modal Decoding of Perceived Speech from Brain Recordings

**链接**: https://arxiv.org/abs/2609.30832
**作者**: Aoke Zhang, Jing Chen
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: BCI, Brain-Computer Interface
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Perceived speech decoding based on non-invasive brain-computer interface (BCI) signals has been extensively studied in recent years. Research in this field primarily faces two challenges: extracting neural representations with rich spatiotemporal information and achieving cross-subject generalization. Although separate studies have proposed methods to cope with these issues, a unified approach that simultaneously tackles both challenges remains lacking. To fill this gap, we propose the Subject-Invariant Cross-Modal Perceived Speech Decoding (SICMD) method, which integrates functional magnetic resonance imaging (fMRI) and magnetoencephalography (MEG). We conduct comprehensive analyses of the fusion method, fusion position, encoder architecture, and model inputs. Our results demonstrate that the proposed method improves Top-1, Top-10, and Rankacc by more than 10.6%, 10.1%, and 1.7%, respectively, compared to baseline methods in cross-subject perceived speech decoding tasks, while reducin

---

### [102] Differential Attention Unlocks Complementary EEG and Speech Fusion for Emotion Recognition

**链接**: https://arxiv.org/abs/2609.31399
**作者**: Philip H. Lee, Shreeram Suresh Chandra, John H.L. Hansen
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal emotion recognition (MER) increasingly pairs EEG with speech, treating internal neural signals and external vocal expression as informative views of affect. In practice, naive fusion underperforms the stronger single modality, because EEG artifacts inject noise that corrupts the shared representation. We introduce EmoSpeechBrain, a multimodal framework built on the insight that noise suppression is a precondition for effective fusion. Its EEG encoder uses differential attention, taking the difference between two attention maps to cancel shared noise and isolate discriminative neural activity. An attention-based gating adapter aligns both modalities in a shared space and weights each one's contribution to the prediction. On two datasets - PME4 and EAV, EmoSpeechBrain improves MER accuracy by up to 12.9% over other state-of-the-art (SOTA) EEG encoders, and surpasses unimodal speech and EEG baselines by up to 13.1% and 23.1%. These results show that once EEG noise is suppressed

---

### [103] AFA-Net: A Differential Attention Approach for Auditory Attention Detection

**链接**: https://arxiv.org/abs/2609.31402
**作者**: Philip H. Lee, Shreeram Suresh Chandra, Karan Thakkar, John H.L. Hansen
**来源**: cs.SD cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Auditory Attention Detection (AAD) utilizes electroencephalographic (EEG) signals to identify a target speaker in a multi-speaker environment. Despite considerable progress, existing deep learning architectures often lack explicit mechanisms for handling noisy EEG data. To address this limitation, we propose Auditory Focus Attention Networks (AFA-Net), a machine learning framework that replaces vanilla attention with a simple yet flexible differential attention mechanism to help focus on task-relevant neural activity. AFA-Net achieves an upward accuracy of 96.8% at the 2s decision window, while using substantially fewer parameters than most existing methods. To the best of our knowledge, AFA-Net is among the first frameworks to explicitly try to combat EEG noise to improve AAD.

---

### [104] Exploring the Benefits of Vision Foundation Models for Unsupervised Domain Adaptation

**链接**: https://arxiv.org/abs/2406.09896
**作者**: Brun\'o B. Englert, Fabrizio J. Piva, Tommie Kerssies, Daan de Geus, Gijs Dubbelman
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] Benchmarking Attention for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.31306
**作者**: Maximilian Schambach and Clemens Biehl and Sam Thelin
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular in-context learners such as TabPFN, Mitra, or ConTextTab rely on alternating row and column attention over 2D sequences of latent embeddings. These attention patterns differ markedly from the one-dimensional case in language models: row attention involves longer sequences while column attention operates on much shorter ones, and the strided memory layout of tabular data makes producing contiguous tensors costly. Moreover, the hidden dimensions used in current models are small compared to recent language models. Yet efficient attention has been studied mostly for one-dimensional sequences, leaving the two-dimensional tabular setting unexplored. To this end, we create a reproducible benchmarking setup and study the unique characteristics of tabular attention across several backends -- Torch SDPA (efficient and cuDNN), FlashAttention-2/3/4, and the inference-only backends vLLM and SageAttention -- measuring forward and backward throughput across realistic tabular shapes on three G

---

### [106] Support-Compiled Feature Folding: More Evidence at Lower Memory Across Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.28208
**作者**: Tian Zhou, Beverly Jin, Xue Wang, Linxiao Yang, Wenwei Wang, Bingqing Peng 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Training Graph Foundation Models on The Web Graph

**链接**: https://arxiv.org/abs/2609.30894
**作者**: Ryoma Sato
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Acacia, a graph foundation model, trained on the web graph. Acacia (i) supports arbitrary feature dimensionalities and semantics without additional training, (ii) supports a wide range of tasks, including node classification, link prediction, node clustering, and graph generation, without additional training, (iii) has in-context learning capabilities, and (iv) does not rely on pretrained LLMs. In particular, existing graph foundation models often require training additional classification heads or feature projectors to accommodate new graphs or new labels, whereas Acacia does not. Moreover, existing graph foundation models often gain their capabilities by being stitched together with pretrained LLMs, whereas Acacia is trained from scratch using only the Common Crawl web graph. This is also an important result because it provides evidence that graph models can acquire emergent capabilities from scratch like LLMs.

---

### [108] What Do Tabular Foundation Models Compute In Context? In-Situ Representation Refinement through Attention-Gated Updates

**链接**: https://arxiv.org/abs/2609.27679
**作者**: Tian Zhou, Beverly Jin, Linxiao Yang, Xue Wang, Wenwei Wang, Bingqing Peng 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] Self-Supervised Representation Learning: From Spectral Foundation Models to Auroral Emission Spectra

**链接**: https://arxiv.org/abs/2609.31206
**作者**: Matthieu Le Lain, Ga\"el Cessateur, S\'ebastien Lef\`evre
**来源**: cs.LG physics.space-ph
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Auroral spectrographs such as the Auroral Spectrograph In Skibotn (ASIS) record hundreds of thousands of emission spectra, but only a few hundred can be labelled by an expert. To exploit the rest, we pretrain a 1D Vision Transformer with a masked autoencoder on 223,000 unlabelled spectra. Without labels, its representation recovers the emission-line intensity ratios that physicists use to diagnose the precipitating particles (R^2 0.91 vs. 0.77 for an untrained control) and, under one linear probe, classifies as well as 13 features designed by experts. Fine-tuned, the model outperforms the previous supervised auroral classifier on its own benchmark (macro-AP 88.5 vs. 77.8), reaches 0.870 mAP, and exceeds the same architecture trained from scratch by +0.159 with 10% of the labels; attribution shows that it uses both N2+ bands. Could an existing pretrained model replace it? Two astronomical spectral foundation models and a time-series model transfer according to their spectral window: Spe

---

### [110] KneePreM: Towards 3D Knee MRI Foundation Models via Large-Scale Unlabeled Pretraining and Label-Efficient Fine-Tuning

**链接**: https://arxiv.org/abs/2609.31461
**作者**: Xinxin Wang, Liam Hazan, Jing Li, Simona Rabinovici-Cohen, Xiaojuan Li, and Mingrui Yang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Large volumes of unlabeled knee MRI scans are available across repositories but remain insufficiently leveraged. We developed KneePreM, a knee-specific 3D self-supervised model, and evaluated transfer and label efficiency for classification and segmentation. Methods: A 3D U-Net masked autoencoder was pretrained on 19,011 unlabeled Osteoarthritis Initiative (OAI) MRI series from 4,791 participants. Downstream fine-tuning used full and reduced training sets for fastMRI+ two-label classification (1,172 examinations), Arthroscopic Partial Meniscectomy (APM) eight-target classification (1,716 examinations), SKM-TEA segmentation (155 examinations), and APM segmentation (25 examinations). Baselines were random initialization and SuPreM. Deployment workflow was implemented with a Model Context Protocol interface. Evaluation metrics included balanced accuracy, F1 score, ROC AUC, PR AUC, and Dice score. Statistical analysis used bootstrap confidence intervals and paired bootstrap tes

---

### [111] FlatClip: A Geometry-Aware Surface-Level Baseline for fMRI Representation Learning

**链接**: https://arxiv.org/abs/2609.31204
**作者**: Mo Wang, Wenhao Ye, Zihan Ning, Jiayu Zuo, Junfeng Xia, Hongkai Wen 等 (7 人)
**来源**: cs.CE cs.CV q-bio.NC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent fMRI foundation models differ substantially in the spatial scale at which they represent brain activity. ROI- and connectivity-based models are efficient but coarse, whereas voxel-level models preserve fine-grained spatial structure but require specialized 3D/4D architectures and costly fMRI-specific pretraining. We ask how effectively an image-pretrained encoder can reuse the spatial organization of cortical activity. Motivated by evidence that macroscale brain activity is strongly constrained by brain geometry, we introduce FlatClip, a frozen-encoder surface-level baseline that renders cortical activity as geometry-aware flatmap sequences and reuses a frozen SigLIP2 image encoder with only a lightweight downstream probe. Across resting-state benchmarks, FlatClip serves as a competitive middle-ground representation, outperforming ROI-level baselines on HCP and ADNI tasks while remaining weaker on PPMI and below the strongest voxel-level models overall. On visual-fMRI decoding, 

---

### [112] Aurora-X: Built for Extreme Time Series Forecasting

**链接**: https://arxiv.org/abs/2609.31038
**作者**: Xingjian Wu, Chenjuan Guo, Xiangfei Qiu, Zhigang Hu, Hanyin Cheng, Peng Chen 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) enable cross-domain forecasting, but their development as general-purpose forecasters remains constrained by underexplored training potential and limited architectural versatility. To address these challenges, we introduce Aurora-X, a billion-scale TSFM with a progressive curriculum and a unified architecture. We first use channel-independent pretraining to learn temporal patterns, then introduce cross-variable dependencies, varied context and horizon lengths, and future covariates if available during midtraining. Variable-resolution post-training further enables an adjustable temporal span per token at inference. With fixed model weights, this supports longer histories under a fixed token budget or fewer tokens for the same history, enabling test-time scaling. With a versatile architecture, Aurora-X supports cross-variable modeling, covariate conditioning, and parallel decoding of future patches for probabilistic forecasting. These are supported b

---

### [113] AlphaEarth distinguishes cities but compresses urban variation

**链接**: https://arxiv.org/abs/2609.30356
**作者**: Andrew Renninger
**来源**: cs.CV physics.soc-ph
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cities differ in built form, land cover and development history, complicating comparison across places and time. Satellite foundation models map Earth's surface onto common numerical representations. Yet the tasks and targets used to shape them typically do not focus on cities: globally consistent labels for urban function do not exist, and many datasets - especially land cover and land use classifications - collapse the built environment into few classes. Here we audit the representation, focusing on AlphaEarth but with broader applicability to other Earth embeddings, by probing the geometry and geography of embeddings for 1,000 urban areas in 162 countries. We find that cities occupy a shifted but overlapping region on the hypersphere, 62.7{\deg} from the global mean direction, and continent and climate predict 24.3% of variation among the mean directions of urban centres in excluded countries. Inside cities, degrees of urbanisation carry 8.9% of the variation, and what they leave ho

---

### [114] EXAONE Demand 1.0: A Time Series Foundation Model for Demand Forecasting

**链接**: https://arxiv.org/abs/2609.30880
**作者**: Seunghan Lee, Sangjun Han, Jun Seo, Junhyeok Kang, Jaehoon Lee, Tae Yoon Lim 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) are pretrained on series from diverse domains, where demand series make up only a small fraction. Demand data has properties that such corpora rarely contain: Short histories, frequent zeros, censoring by stock-outs, and exogenous events that the series does not record. To this end, we propose EXAONE Demand, built on 1) a demand-specific corpus and 2) a demand-aware adapter. For the corpus, we assemble 11.3M series and 48.4B observations from 73 sources, and a synthetic generator supplies the behaviour that open demand data under-represents. For the adapter, we attach low-rank branches to a frozen general-domain backbone, one for each of the four demand classes (smooth, intermittent, erratic, and lumpy), and a router that reads eight scale-free statistics of the input series decides how much each branch contributes. We build EXAONE Demand in two versions, one trained on real-world and synthetic demand together and one trained on the synthetic corpu

---

### [115] BAT-CLIP: Trimodal Alignment of Brain, Audio and Text

**链接**: https://arxiv.org/abs/2609.31180
**作者**: Suhyun Kim, Jinmo Han, Danny Dongyeop Han, Ahhyun Lucy Lee, Jewoon Lee, Yonghyeon Gwon 等 (10 人)
**来源**: cs.SD cs.AI cs.LG eess.AS
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decoding and interpreting naturalistic speech from the brain increasingly relies on alignment to pretrained speech and language representation spaces. However, current CLIP-style brain-speech alignment ground neural activity to a single anchor modality-audio or text-despite the brain's inherently multimodal speech processing. This induces a trade-off: audio anchoring preserves temporal structure but weakens linguistic separability, while text anchoring captures semantics yet discards acoustic detail. We propose BAT-CLIP, the first CLIP-style trimodal alignment framework for iEEG that jointly aligns neural embeddings to both pretrained audio and text anchors in a shared, frozen audio-text manifold. On the naturalistic Podcast benchmark, BAT-CLIP yields more robust representations than bimodal CLIP baselines. We also highlight the importance of using self-supervised foundation models for CLIP training.

---

### [116] BeatGraph: Self-Supervised Heartbeat Graphs for Infant ECG Representations from the Home Environment

**链接**: https://arxiv.org/abs/2609.31546
**作者**: Mohammad Nur Hossain Khan, M. S. Krafczyk, Beverly G. Bolster, Nancy McElwain, Mark A. Hasegawa-Johnson, Bashima Islam
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electrocardiogram (ECG) foundation models typically tokenize the signal into fixed-length patches that ignore cardiac structure, so a patch may split a heartbeat and the number of beats in each patch shifts with heart rate. This matters most for infants, whose heart rates are higher and whose ECG differs from the adult, clinic-recorded 12-lead data these models are built on. A model for infant ECG should therefore reason about heartbeats directly rather than recover them from arbitrary patches. We propose BeatGraph, which makes the heartbeat its unit of representation, modeling each 30-second window as a graph of beats. A shared beat encoder embeds each heartbeat from its waveform and inter-beat intervals, a Transformer with positional encoding orders the beats in time, and residual graph attention layers relate every beat to every other before attention pooling yields a window embedding. We pretrain BeatGraph on our new corpus of unlabeled infant recordings by predicting masked-beat e

---

### [117] TrafficImag: A Benchmark for Counterfactual Roadside Traffic Video Generation

**链接**: https://arxiv.org/abs/2609.30722
**作者**: Xiangyu Li, Tianyi Wang, Zhihao Dou, Christian Claudel, Zhaomiao Guo
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing roadside traffic datasets support perception, forecasting, and visual question answering, but they do not evaluate counterfactual video generation, in which a selected actor is modified and the generated future should remain consistent with road topology and unrelated traffic. We introduce TrafficImag, the first benchmark for counterfactual roadside traffic video generation. TrafficImag combines a large-scale roadside dataset (9,022 annotated images, 7,043 deduplicated video clips, and 31,145 actor-centered history-future samples) with an executable protocol that supports behavior reasoning, intervention-aware image editing, and conditional video generation. Each intervention is represented as an actor-level program describing the target actor, intended behavior, legal route, interaction order, and temporal constraints, enabling a unified evaluation interface across heterogeneous foundation models. TrafficImag evaluates four complementary validity dimensions: initial-state cor

---

### [118] Combining General and Domain-Specific Pretext Tasks for Brain MR Image Segmentation

**链接**: https://arxiv.org/abs/2609.30708
**作者**: Tasneem Nasser, Susanne Schmid, Roberto Souza, Naser El-Sheimy
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A key challenge in medical image analysis is the scarcity of large annotated datasets for specific populations and diseases. As deep learning models rely heavily on labeled data, effective transfer learning strategies are needed to reduce the dependence on manual annotations. Self-supervised learning has emerged as a promising approach for developing foundation models by enabling the learning of transferable feature representations from large-scale unlabeled medical imaging datasets. In this study, we investigate voxel-level brain age prediction as a domain-specific self-supervised pretext task and compare it with image inpainting, a widely used non-domain-specific alternative. We further propose a multitask self-supervised pretraining framework that jointly optimizes both objectives to learn complementary neuroimaging representations. The pretrained models are evaluated on three downstream magnetic resonance image segmentation tasks: multiple sclerosis lesion segmentation, ischemic st

---

### [119] Interpretable-by-Design Descriptor Portfolios Match a 2048-Dimensional Foundation Embedding on Low-Data Molecular Assays

**链接**: https://arxiv.org/abs/2609.30789
**作者**: Yiqi Yao, Miquel Duran-Frigola
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In low-data structure-activity prediction, the choice of molecular representation can matter more than the choice of predictor, and tabular foundation models sharpen that effect. We ask whether a portfolio of compact, semantically named descriptor blocks can reach the accuracy of a 2048-dimensional CheMeleon embedding while staying auditable at the feature level, meaning that every input dimension carries a model name and a recorded training provenance. Starting from a fixed 11-dimensional physicochemical base, we greedily concatenate provenance-screened blocks using the labelled context alone. Across nine ADME/Tox assays and 50 evaluation cells, scored on common-coverage subsets restricted to the molecules that every representation covers, the portfolio reaches a mean test AUC of 0.762, against 0.764 for CheMeleon and 0.756 for Mordred. The pooled gap to CheMeleon is +0.003 AUC (task-bootstrap 95% CI [-0.020, +0.030]), which satisfies our predeclared pooled parity gate but not the per

---
