# 📑 论文索引 - 2026-08-15

共 143 篇论文

---

### [1] MLLM-Routed Heterogeneous Ensembles for Robust Cross-Dataset Image Classification

**链接**: https://arxiv.org/abs/2608.13463
**作者**: Daniel Perkins, John Squires, Janou Milligan, Chandra Raskoti, Linda Ungerboeck
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern image classification models excel when trained on single task-specific datasets but often struggle to generalize across domains and difficulty levels. We propose ARMDIL, an Adaptive Router for Multi-Domain Image classification with LLMs. ARMDIL is an ensemble that uses a multimodal large language model (MLLM) agent to dynamically route each image to the most suitable vision backbone. Our diverse ensemble employs convolutional neural networks (ResNets), self-supervised representation learners (SSL), and vision-language models (VLMs), each trained on a unified label space constructed from multiple image datasets with differing distributions and characteristics. Empirical evaluations illuminate the distinct capabilities and vulnerabilities of each architecture across disparate visual domains. Crucially, we show that ARMDIL effectively navigates these trade-offs, performing competitively with specialized training-based routers. Furthermore, it drastically improves adaptability by al

---

### [2] TennisVAR: A Stroke-Evidence-Grounded Multimodal Large Language Model for Tactical Reasoning in Tennis Videos

**链接**: https://arxiv.org/abs/2608.12920
**作者**: Yifan Mei, Qingling Shi, Changli Wu, Jiayuan Rao, Jiayi Ji, Liujuan Cao
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sports-video understanding is moving beyond event recognition toward explaining how actions collectively shape match progression, however, existing tennis-video methods either perceive individual strokes without modeling their tactical dependencies or generate high-level analyses without grounding them in the underlying events. To bridge this perception-to-understanding gap, we formulate stroke-evidence-grounded tactical reasoning, a new rally-level task that requires models to jointly predict an open-ended answer, a hierarchical tactic label, an ordered sequence of supporting strokes, and decisive key actions, with each evidence stroke anchored to its racket-ball contact frame. We further introduce TRACE (Tactical Reasoning with Action-Chain Evidence in Tennis), a large-scale expert-annotated benchmark containing 11,189 rally videos, 41,485 stroke events, 25,429 tactical units, and 11,189 question-answer pairs, which unifies fine-grained stroke attributes, cross-stroke tactical relati

---

### [3] Locally tuned Large Language Model ( LLM ) to empower digitalization of borehole logs for 3D stratigraphic modelling

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0886779826005717&hl=zh-CN&sa=X&d=17928240483842255476&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-xhb6w7YT_CfY5H5vNya2Qk&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: JC Yao, B Lyu, Y Wang - Tunnelling and Underground Space Technology, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> large language model ( LLM ). To integrate domain geological knowledge into existing LLMs, a domain-specific LLM , called stratum generative pre-… An illustrative case study demonstrated that the proposed LLM -empowered StratumGPT

---

### [4] LoKiFormer: Locality-aware Attention with Decoupled Knowledge Memory for Efficient Large Language Model Pretraining

**链接**: https://arxiv.org/abs/2608.12419
**作者**: Qiuwu Chen, Zimo Liu, Yuchen Li, Ying Sun, Yifan Zhang, Zhijie Qiu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have achieved remarkable breakthroughs across various applications. However, their architectures remain inefficient in pretraining due to two main limitations: (i) self-attention lacks an explicit inductive bias for locality, leading to redundant modeling of sequence-internal local information; (ii) mixture-of-experts (MoE) implicitly couples knowledge storage with computational pathways, hindering flexible access to sequence-external global knowledge. To overcome these limitations, we propose LoKiFormer, a novel LLM architecture that augments the standard decoder with two dedicated modules: 1) Local Fusion Attention (LFA), which incorporates a convolutional fusion to attention, explicitly capturing local patterns and allowing the attention to operate on more informative representations; 2) Knowledge Memory Module (KMM), which introduces a parametric key-value memory that explicitly stores global knowledge in addressable slots, decoupling storage from compu

---

### [5] Discovering Efficient and Explainable Communication Topologies for LLM-based Multi-Agent Systems via Causal Inference

**链接**: https://arxiv.org/abs/2608.12921
**作者**: Junzhi Li, Peng He, Qirui Ji, Wei Wang, Lixiang Liu, Chuxiong Sun
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance of large language model (LLM)-based multi-agent systems (MAS) largely depends on effective communication topologies. Existing topology generation methods, however, typically learn communication topologies through black-box optimization driven solely by task-level rewards. While effective, such optimization provides little insight into why particular communication edges are selected, making it difficult to identify the critical communication subgraphs responsible for successful collaboration. To address this limitation, we propose E2-Explainer, a model-agnostic framework for providing interpretable explanations of communication topologies produced by arbitrary topology generators. Specifically, we formulate topology explanation as a causal attribution problem that identifies compact communication subgraphs supported by edge-level evidence of task preservation. We obtain this evidence with a Granger-style objective that measures how masking each communication channel chan

---

### [6] SynAct: A Reasoning-Acting Large Language Model Agent for Adaptive Synthesis Optimization

**链接**: https://arxiv.org/abs/2608.12751
**作者**: Fangzhou Liu, Peiyi Han, Jiawei Liu, Yuan Pu, Zhuolun He, Rongliang Fu 等 (8 人)
**来源**: cs.AR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logic synthesis transforms RTL designs into gate-level netlists, where PPA results are highly sensitive to the choice of optimization commands, making synthesis tuning both high-dimensional and expensive. Previous approaches fall into two categories: automated methods, which perform black-box search over fixed action spaces with limited decision-level interpretability, and LLM-based methods, which typically generate static scripts upfront and cannot adapt to evolving circuit states. We present SynAct, an adaptive closed-loop LLM reasoning--acting agent that iteratively diagnoses live synthesis reports and reasons over the current circuit state, retrieved tool knowledge, and historical optimization experience to issue targeted commands. SynAct focuses on improving timing, particularly worst negative slack (WNS), while maintaining balanced area and power trade-offs. Experiments on a commercial synthesis tool across 14 designs show that SynAct reduces average WNS to 27% of that from boots

---

### [7] Error-Aware Reverse Auction Mechanism for Large Language Model Routing

**链接**: https://arxiv.org/abs/2608.12719
**作者**: Haolong Chen, Zhengyuan Xin, Liang Zhang, Lei Xue, Guangxu Zhu
**来源**: cs.GT cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Routing each query to a cost-effective large language model (LLM) is critical for balancing quality and cost, yet most routers rely on a centralized task center to predict model performance, creating an information-risk mismatch and a scalability bottleneck as the model pool grows. We propose a market-based routing paradigm that shifts ex-ante prediction to LLM providers via a reverse auction, where providers bid with self-predicted success probabilities and execution costs. To account for inherently noisy provider predictions and center evaluations, we introduce the \textit{\textbf{E}rror-\textbf{A}ware \textbf{R}everse \textbf{A}uction \textbf{M}echanism} (EA-RAM), which explicitly models this inherent Dual Error. We prove that EA-RAM is Bayesian incentive compatible and individually rational under the Dual Error, establish sufficient conditions for center rationality, and derive an explicit welfare-loss bound. We further identify robustness effects: opposite-signed errors can cancel

---

### [8] Keep, Customize, or Exit: Default Design and Token Pricing in LLM Reasoning Services

**链接**: https://arxiv.org/abs/2608.13315
**作者**: Ahmet Bugra Gundogan and Yigit Turkmen and Melih Bastopcu
**来源**: cs.GT cs.AI cs.LG cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study a large language model (LLM) service in which a provider chooses a per-token price and a default reasoning-token allocation, while a user may accept the default, customize the allocation, or exit. Larger allocations can improve accuracy but increase token cost and latency. We model this interaction as a Stackelberg game and derive the user's unique optimal customized allocation in closed form. For any price, the acceptable defaults form either an empty set or a compact interval. We characterize the provider's optimal default through a three-regime rule, reduce equilibrium computation to a one-dimensional price optimization, and prove the existence of the equilibrium. We further show that defaults affect the implemented reasoning allocation only when users value the convenience of avoiding customization; otherwise, every service-providing outcome implements the user's optimal customized allocation. Experiments with two compact open-weight reasoning models on five mathematics an

---

### [9] Beyond Handcrafted Security: Towards Self-Evolving Defense for LLM Agents

**链接**: https://arxiv.org/abs/2608.12977
**作者**: Jiajun Ruan, Peiyang Li, Yukun Chen, Fengting Li, Chao Feng
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The expanding operational capabilities of large language model (LLM) agents introduce sophisticated security threats. Runtime defenses have emerged as an effective approach to mitigating these risks by integrating security mechanisms into the agent execution loop. However, existing runtime defenses rely heavily on manually designed interventions and lack a principled framework for their construction and maintenance. In this work, we first develop a harness-level formulation of runtime defense that systematically characterizes how harness mechanisms enable defense construction and provides a unified view of existing runtime defense interventions from a harness perspective. Building on this formulation, we propose HARD (Harness-based Autonomous Runtime Defense Evolution), a self-evolving runtime defense framework that automatically identifies appropriate intervention strategies and iteratively improves defense artifacts based on observed failure traces. HARD transforms runtime defense de

---

### [10] StateBridge: Training-free Hidden-state Alignment for Latent Communication in LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.13317
**作者**: Yanwen Peng, Delvin Ce Zhang, Xi Wang, Nikolaos Aletras
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model based multi-agent systems usually communicate in text, i.e., using discrete tokens. However, text introduces a discrete bottleneck. Converting the sender's continuous hidden states into discrete tokens discards information that token identities alone cannot capture. Recent work proposes latent communication as an alternative, where agents transmit hidden representations directly without converting them to text. However, existing latent methods either inject working memory layer by layer across the transformers, or require trained projectors that limit portability. We propose StateBridge, a training-free latent communication approach that aligns the sender's final-layer hidden states to the receiver's input space via a closed-form orthogonal transformation. Lightweight norm calibration and vocabulary anchoring ensure compatibility with the pretrained input distribution. The aligned states are prepended to the input of the receiver agent as a continuous prefix. We ev

---

### [11] Toward WAN-Aware LLM Training Across Heterogeneous, Geo-Distributed Sites

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3789240.3828748&hl=zh-CN&sa=X&d=14758962432721825619&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-zg7Eww1Djth8m7Dtt0sI3X&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: Z Luo, J Cai, C Le Denmat, S Nair, F Nourzad… - Proceedings of the ACM …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> -institution LLM training under these conditions. In this extended abstract, we present an early two-level prototype for geo-distributed LLM … Our deployment suggests that crossinstitution LLM training goes far beyond distributed learning at

---

### [12] LigBench: A Unified and Human-Aligned Benchmark for LLM-based Research Idea Generation

**链接**: https://arxiv.org/abs/2608.13136
**作者**: Chenrun Wang, Mingxuan Zhu, Tiancheng Huang, Wenjie Li, Yujie Zhang, Zichen Zhu 等 (9 人)
**来源**: cs.CL cs.AI cs.DB cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid advancement of large language models (LLMs), research idea generation has attracted increasing attention. Existing approaches enable LLMs to retrieve relevant literature and propose novel ideas for research areas. However, current evaluation practices for idea generation remain fragmented and lack objective standards, often relying on direct LLM scoring, which limits their ability to provide unified and reliable assessments across a coherent distribution of generated ideas. To address this challenge, we propose LigBench, an automated evaluation benchmark that enables fine-grained and reliable evaluation of AI research ideas, consistently applicable across different generation distributions. In addition, we introduce PAIR-IQ, a dataset tailored for training pairwise idea judgment models and serving as an auxiliary reference to support more objective comparative evaluation. Extensive experiments demonstrate that LigBench achieves stable and interpretable evaluations, signi

---

### [13] LLM-Based Test Oracles: Source-of-Authority Taxonomy -- A Systematic Literature Review

**链接**: https://arxiv.org/abs/2607.05031
**作者**: Ali Hassaan Mughal, Muhammad Bilal
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Certifiable Semantic Agreement Among LLM Agents: What the Admissibility Instrument Decides

**链接**: https://arxiv.org/abs/2606.07316
**作者**: Haoran Xu, Lei Zhang, Iadh Ounis, Xianbin Wang
**来源**: cs.MA cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] What Drives LLM Self-Reflection? A Controlled Ablation of Uncertainty Routing in Armed Conflict Forecasting

**链接**: https://arxiv.org/abs/2608.12322
**作者**: Poli Nemkova, Haeshitha Indukuri
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-reflection is widely assumed to improve LLM reasoning, yet which component drives the gain remains poorly understood. We present a controlled six-condition ablation isolating four components of LLM self-reflection: evidence exposure, diagnostic scaffolding, taxonomy vocabulary, and action routing. Two precise null results converge on a single mechanism. First, structured diagnostic questions add no measurable value over unstructured reflection ($\text{F1} = 0.296$ vs $0.297$, $p = 1.000$, 95\% CI $[-0.041, +0.040]$). Second, presenting the full uncertainty taxonomy while collapsing the action space to a single generic action also adds no value ($\Delta\text{F1} = +0.008$, overlapping 95\% CIs), ruling out taxonomy vocabulary as the mechanism. Typed action routing provides consistent directional gains ($\text{F1} = 0.379$ vs $0.296$); the conservative estimate controlling for taxonomy vocabulary is $\Delta\text{F1} = +0.075$, and the overall gain over the single-shot baseline is si

---

### [16] CASA: Content-Acoustic Speaking Assessment with Speech Encoder and Large Language Model

**链接**: https://arxiv.org/abs/2608.13101
**作者**: Nhan Phan, Ilona L\"ahteenm\"aki, Anna von Zansen, Olli-Pekka Pauna, Yaroslav Getman, Tam\'as Gr\'osz 等 (7 人)
**来源**: cs.CL eess.AS
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on automatic speaking assessment (ASA) has increasingly adopted multimodal speech large language models to assess learners' speaking performance. However, existing studies provide limited analysis of how acoustic and content information contribute to predictions and how stable the resulting performance is. We propose CASA, a simpler architecture combining Whisper-medium and Qwen3.5-2B that achieves state-of-the-art performance while providing a more interpretable separation between speech delivery and content. On the Speak & Improve Corpus 2025, CASA achieves a root mean square error (RMSE) of 0.358, improving on the previous best RMSE while using approximately half the estimated inference parameters. The general-purpose architecture is designed for adaptation to other ASA corpora without structural changes and relies on three handcrafted fluency features. Through ablations and repeated runs, we analyze the individual and complementary contributions of acoustic and content inf

---

### [17] Connex: Endpoint Mobility Primitives for Dynamic LLM Serving

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3789240.3829200&hl=zh-CN&sa=X&d=11263356504355856614&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-xB63eChWFhcQgU-tfF-04m&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: Y Lin, V Liu, T Luo, CZ Xu, K Ye - Proceedings of the ACM SIGCOMM 2026 …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> elasticity in LLM serving? What are the requirements? What does such a system look like? … In answering these questions, we identify three issues that make elasticity in LLM serving … mobility a first-class primitive for elastic LLM inference

---

### [18] Which LLM Is Your Ideal Companion? Evaluating Emotional Companion Capabilities of LLMs Based on Adult Attachment Theory

**链接**: https://arxiv.org/abs/2608.13168
**作者**: Junkai Zhou, Shiting Guan, Zhaoyi Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly applied for emotional companionship, evaluating their behavior and capabilities in intimate relationships has become a pressing issue. However, existing assessments primarily characterize general personality traits, providing limited insight into model behavior within intimate and emotionally sensitive contexts. Therefore, we introduce adult attachment theory into LLM evaluation and use the Experiences in Close Relationships-Revised (ECR-R) scale to characterize attachment anxiety and avoidance. To evaluate emotional companionship capabilities of LLMs in realistic interaction scenarios, we present an emotional companionship benchmark, ECBench, spanning four scenarios including emotional support, collaborative tasks, conflict resolution, and social guidance, across friendship and romantic relationships. ECBench is utilized to assess model behavior using 11 dialogue-quality metrics and three evaluation methods. We evaluate the attachment t

---

### [19] InFactPlanner: Planning Sustainable Geo-Distributed LLM Data Centers

**链接**: https://arxiv.org/abs/2608.12915
**作者**: Nicoletta Tsiopani, Moysis Symeonides, George Pallis, Marios D. Dikaiakos
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid growth of LLM inference is shifting sustainability concerns from one-time training to continuous serving, where infrastructure decisions shape energy use, carbon emissions, water consumption, and service quality. Yet operators often need to compare deployment alternatives before large-scale infrastructure is built, making direct measurement costly, slow, and sometimes infeasible. We present InFactPlanner, a trace-driven decision-support framework for what-if analysis of sustainable AI data center deployment for LLM inference across single and geo-distributed sites. InFactPlanner combines query traces, hardware-model profiles, candidate site configurations, PUE/WUE parameters, renewable generation models, and time-varying grid carbon intensity to estimate power, energy, carbon emissions, water use, latency, and server utilization. The framework abstracts low-level serving effects into configurable hardware-model profiles, enabling rapid comparison of site selection, capacity p

---

### [20] Multi-Agent Scheduling with LLM-Assisted Contract Net Negotiation for Stream Processing in Mobile Edge Computing

**链接**: https://arxiv.org/abs/2608.12371
**作者**: Sabeur Lajili, Zaki Brahmi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Stream-processing systems increasingly operate across heterogeneous mobile edge--cloud infrastructures, where workload volatility, resource contention, and stringent quality-of-service (QoS) requirements complicate decentralized scheduling. This paper proposes \emph{MAS-DecStream}, whose main contribution is \emph{LLM-MR-CNP}: an extension of the classical Contract Net Protocol with semantic CFP formulation, progressive context disclosure, multi-round proposal revision, negotiation memory, and deterministic validation. Edge-cluster agents refine natural-language offloading proposals from local observations, predicted resource states, and qualitative runtime context, while hard resource and QoS constraints remain deterministic. Experiments derived from the Alibaba ASI Trace evaluate the extension at three levels: single- versus multi-round CNP, rule-based versus LLM-assisted refinement, and fixed-model single- versus multi-round negotiation. Under the evaluated configurations, MAS-DecSt

---

### [21] LycheeMemory V2: Efficient Long-Term Memory for LLM Agents via Semantic Segment-Level Consolidation

**链接**: https://arxiv.org/abs/2608.12990
**作者**: Dongfang Li, Zixuan Liu, Junmai Wang, Jiahe Huang, Fuhao Li, Bonian Jia 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents must preserve information from past interactions to support future tasks. Existing memory systems typically rely on eager consolidation, invoking LLMs after each interaction to extract, summarize, or update memories. This design makes memory construction increasingly costly as conversations grow. Coarse summarization can reduce construction cost but risks discarding fine-grained contextual evidence, whereas larger retrieval contexts or multi-hop LLM reasoning shift the overhead to query time. We present LycheeMemory V2, an efficient long-term memory framework that replaces turn-level consolidation with semantic segment-level consolidation. Instead of consolidating every interaction, LycheeMemory batches multiple exchanges into segments and encodes each finalized segment into context-independent typed memory records. Segment-level batching lowers LLM encoding frequency, while semantic boundary detection helps preserve coherent event-level and temporal evidence co

---

### [22] LLM-Assisted Dynamic Threat Analysis for Attacker-Reachable Software Weaknesses in Autonomous Vehicles

**链接**: https://arxiv.org/abs/2608.13450
**作者**: Md Wasiul Haque, Sagar Dasgupta, Mizanur Rahman, and Md Rayhanur Rahman
**来源**: cs.SE cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous vehicles depend on large safety-critical software stacks, where weaknesses reachable from adversarial inputs may affect steering, braking, or other control decisions. Static analysis can identify candidate sites, but dynamically confirming exploitability requires executable test artifacts that are difficult to construct manually. We investigate whether large language models (LLMs) can automate this process for Autoware, an open-source autonomous-driving stack. We perform compiler-precise static analysis across 185 packages, identifying 1,375 decision rules, 2,274 validation checks, and 482 input-to-safety-output flows, from which we derive a weakness taxonomy and sample 740 reachable sites. Two local open-weight LLMs, a no-static-context ablation, and a naive-template baseline generate 3,700 artifact sets, which are compiled against the real build under sanitizers, repaired through compiler-in-the-loop feedback, and fuzzed when executable. The main result is a build-integrat

---

### [23] ERSkill: Evolving for Skill-Guided Adaptive Memory Retrieval

**链接**: https://arxiv.org/abs/2608.12720
**作者**: Haolong Chen, Liang Zhang, Zhuo Li, Lei Xue, Guanrxu Zhu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Model (LLM) agents increasingly rely on long-term memory for persistent interactions, the retrieval mechanisms governing this memory are rarely treated as evolvable components. This static approach limits performance on heterogeneous memory queries, which often demand diverse evidence construction strategies. To address this, we introduce \textbf{ERSkill}, a retrieval-centric framework for self-evolving, skill-guided memory access. ERSkill compiles interaction histories into a structured memory store and represents retrieval behaviors as executable skills composed of fundamental primitives. At inference time, a trained router dynamically matches each query to the optimal skill to construct tailored evidence for answer generation. To enable continuous improvement, ERSkill co-evolves the skill set and the router during training. It employs an experience trie to efficiently record explored retrieval paths, alongside a double-frontier mechanism that safely decouples th

---

### [24] Agreement Is Not Alignment: Divergent Moral Grounds in Human and LLM Ethical Judgments

**链接**: https://arxiv.org/abs/2608.12368
**作者**: Octavian M. Machidon, Alina L. Machidon, Vojko Strahovnik, Mateja Centa Strahovnik, Jonas Miklav\v{c}i\v{c}, and Marko Robnik \v{S}ikonja
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agreement with human judgments is a common proxy for evaluating the alignment of large language models (LLMs). Yet agreement in final labels does not show that human annotators and models rely on the same moral grounds. Two agents may reach the same judgment while appealing to different principles, contextual assumptions, or interpretations of the situation. We test this distinction using a curated 500-item ETHICS-derived benchmark spanning five domains of moral judgment, with new human annotator and LLM annotations of both final labels and supporting rationales. Across frontier and open model families, agreement with human annotator majority labels is often high. However, rationale-level analysis reveals systematic divergence in the moral grounds expressed by human annotators and models. In particular, models redistribute attention across categories such as harm, respect, promise-keeping, justice, desert, and excuse relevance, even when their final labels match the human annotator maj

---

### [25] The Embedder's Dilemma: LLMs Are Better, but at What Cost?

**链接**: https://arxiv.org/abs/2608.12875
**作者**: Adnan El Assadi, Niklas Muennighoff, Jinhyuk Lee
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Should you replace your text-embedding pipeline with a large language model? We answer this with a controlled, cost-aware comparison of ten LLMs across six families and 26 embedding models (118M to 14B parameters) on 37 tasks spanning classification, semantic textual similarity (STS), clustering, pair classification, and retrieval. In aggregate the two paradigms are effectively tied: the best LLM (Gemini 3.1 Pro, 77.6) and the best embedding model (77.2) differ by 0.4 points. Their strengths differ by task: LLMs lead on reasoning-heavy retrieval, embedding models lead on classification, and the two match on clustering, STS, and pair classification. Reaching that parity is expensive. An LLM costs up to 1,431x more than an embedding model of comparable quality (USD 154 vs. USD 0.11 per benchmark pass), and the open LLMs tested process tokens 2.5 to 736x more slowly on the same GPU. Reasoning tokens account for 28 to 81% of LLM inference cost; lower reasoning budgets preserve or improve r

---

### [26] Learning to Adapt Cross-Domain Preferences via Meta-LoRA for LLM Personalization

**链接**: https://arxiv.org/abs/2608.12389
**作者**: Xuefei Wang, Jun Han, Zixuan Wang, Qingkai Zeng, Xiao Wang, Ruijie Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-domain zero- or few-shot personalization aims to generate user-preferred responses in unseen conversational domains from only a handful of target-domain interactions. Existing adaptation methods struggle to calibrate update magnitude under sparse evidence and thus overfit, whereas history-transfer methods often entangle user preferences with source-domain artifacts, yielding unreliable personalization priors and negative transfer. To calibrate adaptation to evidence quality, we propose PAC-Bayes-regularized Meta-LoRA, which uses a meta-learned LoRA initialization as both the adaptation start and prior center, while adjusting update strength according to support-set size and predictive uncertainty. This limits overfitting under sparse or ambiguous evidence while permitting stronger personalization as evidence grows. Controlled adaptation alone does not determine which preferences should transfer across domains or how they should be expressed. We therefore functionally decompose pe

---

### [27] Fine-Tuning Large Language Model for Gene Prioritization in m9. 2 Erythroid Module

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11629812/&hl=zh-CN&sa=X&d=3327489371371702653&ei=BHh_ao-LO9GhieoPpP7auQM&scisig=AIVdB-zecNNFFyUM-88uM9xYa7_7&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=1&folt=kw-top
**作者**: GB Regulwar, B Yashwanth, KS Reddy, GP Chamundi… - 2026 5th OPJU International …, 2026
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Optimized DeepSeek performance contrasted with multi model integration outcomes reveals … (2.37 versus 1.82), similarly favored multi - model integration. However, computational demands … language models , DeepSeek, and the

---

### [28] A Contract-Grade Verifier for LLM-Generated GPU Kernels, and a Native Blackwell Backward for the Gated-Linear-Recurrence Family

**链接**: https://arxiv.org/abs/2608.12700
**作者**: Rishi Shah, Rishav Shrestha
**来源**: cs.LG cs.AR cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systems that generate GPU kernels with language models report high correctness rates. Those rates come from a single loose test: run the kernel on a few random inputs at one fixed shape and accept it if the output is close to a reference. A kernel can pass that test and still be silently wrong. It can return an ordinary number where the true answer is a NaN or an infinity, differ from run to run, break when the shape changes, or accumulate in fp16 where the reference keeps an fp32 total. We build the instrument that checks correctness properly: a contract-grade verifier of twelve adversarial gates, each a property a correct kernel must satisfy, several of them tolerance-free, so no choice of threshold can explain a failure away. Aimed outward, the verifier audits 2,638 machine-generated kernels that a public system's own harness had already accepted as correct. It finds 39.5% broken beyond any tolerance argument and 62.1% carrying at least one violation. The field's standard test accep

---

### [29] Using RE- LLM coding uncertainty to resolve codebook ambiguities: an example of the CLARIFY toolset and workflow in action

**链接**: https://scholar.google.com/scholar_url?url=https://www.researchgate.net/profile/Fanjie-Li-3/publication/412055150_Using_RE-LLM_Coding_Uncertainty_to_Resolve_Codebook_Ambiguities_An_Example_of_the_CLARIFY_Toolset_and_Workflow_in_Action/links/6a7924a7ef3d2909799ad004/Using-RE-LLM-Coding-Uncertainty-to-Resolve-Codebook-Ambiguities-An-Example-of-the-CLARIFY-Toolset-and-Workflow-in-Action.pdf&hl=zh-CN&sa=X&d=3260326940486647610&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-zTJrcexzraAGV3HaIQDpOt&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: F Li, ML Mason, D Levin, A Wise - Joint Proceedings of LAK, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Reasoning-Enhanced Large Language Models (RE-LLMs) enable new forms of human-AI collaboration in coding of student text that allows us to code better, not just faster. This paper introduces CLARIFY, a toolset and workflow to

---

### [30] SAEVerbalizer: Generating Explanations for Sparse Autoencoder Features via Representation Verbalization

**链接**: https://arxiv.org/abs/2608.13538
**作者**: Weihan Meng, Hongzhu Guo, Yi Jing, Dewen Liu, Zijun Yao, Xiaozhi Wang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) are proposed to extract numerous features from large language model (LLM) representations, yet explaining these features still relies primarily on external observation. This reliance leads to superficial explanations inferred from observed model behavior and computational inefficiency from collecting such behavioral evidence at scale. We introduce SAEVerbalizer, a framework that injects SAE decoder directions into an LLM's representations and fine-tunes the LLM's downstream layers to generate natural-language explanations of the injected features. Once trained, the resulting verbalizer explains SAE features directly from decoder directions, addressing both limitations. Our experiments show that the learned verbalization capability generalizes to unseen features, transfers across separately trained SAE dictionaries, and, with a lightweight adapter, extends to SAE features from different LLMs. Intervention experiments show that injecting multiple directions yie

---

### [31] Teach the Magnitude, Not the Direction: Verifier-Bounded Credit Assignment for Multi-Turn Multi-step LLM Agents

**链接**: https://arxiv.org/abs/2608.13179
**作者**: Zechuan Wang, Siyuan Lu, Hongxuan Zhang, Linjian Mo, Chenyi Zhuang, Leilei Gan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) offers a verifier-bounded performance ceiling for training multi-turn tool-use agents, yet its trajectory-level credit assignment conflates heterogeneous per-turn outcomes into a single reward signal. On-policy distillation provides dense per-token supervision but is either teacher-bounded or prone to gradient concentration collapse. We introduce $\textbf{CrEST}$, a hierarchical credit assignment framework that retains RL's verifier-bounded ceiling while incorporating dense token-level signals from a privileged self-teacher. $\textbf{CrEST}$ resolves credit at two levels: turn-segmented verified advantages address inter-turn dilution, while entropy-gated self-teacher modulation refines intra-turn token contributions. Experiments on BFCL V3 and WildToolBench show that $\textbf{CrEST}$ consistently outperforms both RL and distillation baselines across two model scales, with the largest gains on long-trajectory and strict session-level

---

### [32] Don't Want Your LLM to Recommend Nuclear Strike? Try Asking It in Japanese

**链接**: https://arxiv.org/abs/2608.12373
**作者**: Rian Touchent (ALMAnaCH)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used in strategic and advisory contexts, yet their safety alignment is typically evaluated in English only. We test nine models from six providers and ask whether the language of a prompt can change a model's decision in a high-stakes scenario. We use single-turn game-theoretic vignettes in which a model advises a nuclear-armed nation on whether to strike a defenseless opponent. The prompt is intentionally amoral and strategically identical across languages. We find that Japanese prompts reduce launch rates in the Claude model family: Claude Sonnet 4.6 drops from 40% to 0% in scenarios where the strike is unnecessary and from 93% to 17% in contested scenarios, with minimal effect when the strike is strategically rational. The effect extends to Gemini Pro 3.1 (53% to 13%). A cross-language experiment isolates the mechanism: when instructed to reason in Japanese in an English prompt, launch rates drop from 93% to 37%. It is the language the model is

---

### [33] SparseDitto: Customizing GPU Kernels for Different Sparsity Patterns with LLM-Based Agentic System

**链接**: https://arxiv.org/abs/2608.05033
**作者**: Shiyang Li, Guangyan Sun, Jinwei Tang, Yanzhi Wang, Mingyi Hong, Caiwen Ding
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Model Discovery Agent: LLM-assisted Bayesian experiment design for data-efficient discovery of mechanistic world models

**链接**: https://arxiv.org/abs/2608.09696
**作者**: Kevin Murphy
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Beyond Local Accuracy: A Protocol-Level Identifiability Audit for Controlled LLM Reasoning Evaluation

**链接**: https://arxiv.org/abs/2608.13326
**作者**: Junhao Luo, Ning Huang, Ziqi Sha, Wenxuan Tang, Wei Deng (School of Statistics and Data Science, Southwestern University of Finance and Economics)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM benchmark scores can be precise even when the observation protocol does not identify the behavioral property they are intended to measure. In a controlled, solver-grounded setting, we formalize a protocol-level identifiability audit over a finite behavioral policy class: given policies H, observation support O, and estimand $\tau$, we test whether O separates every pair with different $\tau$. The audit requires zero model calls and resolves our diagnostic case: base-only observation collapses seven frozen deterministic policies into one equivalence class; full support yields seven classes and no cross-estimand collisions; every leave-one-out support retains a constructive collision witness. Empirically, both constrained-generation variants have pair-validity 1.0, yet base accuracy and selective-response fidelity diverge - 0.620 versus 0.324 across six balanced oracle-transition directions (cluster-bootstrap 95% CI [0.600, 0.642] vs. [0.304, 0.345]) - and the gap recurs on a second 

---

### [36] The Evaluator Is Part of the Experiment: Measuring Open-Ended LLM Conformity

**链接**: https://arxiv.org/abs/2608.04463
**作者**: Alicia Guerra, Yibo Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] Refusing Intent, Not Form: Wrapper-Based Intent-Group Supervision for LLM Safety

**链接**: https://arxiv.org/abs/2608.13304
**作者**: Ping Wu, Haibo Tong, Feifei Zhao, Han Shen, Yu Shi, Yilin Zhao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety tuning can improve harmful refusal, but models may learn surface-form shortcuts: wrapped harmful prompts bypass safety, while similarly wrapped benign prompts are over-refused. We propose Wrapper-Based Intent-Form Augmentation (WIFA), an automatic intent-group augmentation method that pairs wrapped harmful examples with structurally matched wrapped benign counterexamples, requiring no external teacher or manual per-wrapper intent labels. We use WIFA as a common data layer for two complementary fine-tuning routes: WIFA-Boost, a two-stage high-safety recipe, and Anchored Group-Consistent Refusal Training (A-GCRT), which regularizes refusal/compliance decision scores across same-intent wrappers and anchors harmful and benign groups on opposite sides of a margin. In the Qwen setting, WIFA-Boost reaches the strongest transformed-harmful refusal, while A-GCRT reduces OR-Bench over-refusal from 25.7\% for the base model to 17.4\%; reproduced baselines do not match these operating point

---

### [38] TrainSketch: Collision-Protected Switch Telemetry for Distributed LLM Training Flows

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3789240.3828746&hl=zh-CN&sa=X&d=13412096416059981034&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-wO9l3MaOZc2189JFdBpoJT&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: A Li, Z Fan, K Yang, Z Luan, Y Jiang, K Li 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Distributed LLM training requires switch telemetry that can identify training-relevant flows and recover their per-flow period, burst statistics, and packet length, but conventional sketches allow hash-colliding non-target traffic to corrupt the counter

---

### [39] Most biomedical publications show signs of LLM -assisted writing

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.10715&hl=zh-CN&sa=X&d=5954456426486811246&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-wT7LvAHSUyDK9IWaBcNiG8&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: L Holzwarth, R González-Márquez, D Kobak - arXiv preprint arXiv:2608.10715, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Comparing the pre- LLM and post- LLM frequencies of LLM associated marker words, either pre-selected (Gray… 2026) can yield an estimate of the overall LLM usage. However, all existing methods in this group can only provide a lower bound

---

### [40] TSA- LLM : a survey of time-step alignment on speech large language models

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-981-92-4529-1_12&hl=zh-CN&sa=X&d=7357941416170620035&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-zhaASi7pEbOF4xXc1xJwCe&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: S Li, J Li, T Shinozaki - International Joint Conference on Artificial Intelligence, 2027
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> an adapter or tokenizer that reduces the audio sequence, and an LLM that performs language generation or reasoning. The architecture is … as TSA- LLM , short for LLM -based timestep alignment. We use time-step alignment to mean the assignment of LLM

---

### [41] DualPath: Accelerating Agentic LLM Inference by Harvesting Disaggregated KV-Cache Storage I/O

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3789240.3829159&hl=zh-CN&sa=X&d=2525568182855088299&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-zQ0cZicX3DQ9xAjbLuVEaK&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: Y Wu, S Chen, R Huang, Y Tan, Y Zhong, M Zhang… - Proceedings of the ACM … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> a significant transformation in LLM inference workloads: from traditional human LLM interaction to human- LLM -environment interaction, … rounds of interaction with the LLM , and consuming the results generated by the LLM . By contrast, an agentic LLM

---

### [42] Enhancing In-Hospital Mortality Prediction Using Multi-Representational Learning with LLM-Generated Expert Summaries

**链接**: https://arxiv.org/abs/2411.16818
**作者**: Harshavardhan Battula, Jiacheng Liu, Jaideep Srivastava
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] NaLA: A 3D Native LLM Layout Agent for High-quality 3D Scene Generation

**链接**: https://arxiv.org/abs/2606.29395
**作者**: Cheng Wan, Yongsen Mao, Wenzheng Wu, Yuxuan Xie, Chucheng Xiang, Runze Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] CRAFT: LLM-Based Iterative Refinement for Temporal Reasoning over Clinical Narratives

**链接**: https://arxiv.org/abs/2608.12779
**作者**: Chengyang He, Tahreem Arif, Marko Zivkovic, Lijing Wang, Yue Ning, Ping Wang
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding the temporal progression of symptoms in clinical narratives is critical for disease monitoring, safety surveillance, and causality assessment. Clinical narratives, however, rarely provide explicit temporal anchors. Current approaches to temporal information reasoning focus predominantly on pairwise relation classification across multi-visit and timestamp-rich records, leaving the reconstruction of structured symptom trajectories from individual anchor-sparse reports largely unaddressed. We propose CRAFT, an LLM framework that pairs a generator with a constraint-based verifier to iteratively produce and refine stage-wise symptom timelines through targeted feedback. We conduct evaluation on MedTempo, a new benchmark of 5,347 vaccine adverse-event narratives spanning three COVID-19 vaccine types, with expert-validated temporal stage annotations for 3,166 reports. Experiments across four LLM backbones demonstrate that CRAFT consistently improves temporal ordering accuracy, wi

---

### [45] Foam-Agent: A Large Language Model-Based Multi-Agent Framework for Automating Computational Fluid Dynamics Workflows

**链接**: https://arxiv.org/abs/2505.04997
**作者**: Ling Yue, Nithin Somasekharan, Tingwen Zhang, Yadi Cao, Zhangze Chen, Shimin Di 等 (7 人)
**来源**: cs.AI cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Do LLM Recommenders Know When They're Hallucinating? Auditing Confidence Calibration in Catalog Faithfulness

**链接**: https://arxiv.org/abs/2608.10008
**作者**: Srijith Ravikumar
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] $\varepsilon$-MemEvo: Adaptive Cross-Task Memory Transfer for LLM Program Evolution

**链接**: https://arxiv.org/abs/2608.12522
**作者**: Aofan Liu, Shiyuan Song, Yiyan Qi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based program evolution systems such as FunSearch and AlphaEvolve have shown strong ability to discover novel algorithms, but typically optimize each task in isolation, discarding search experience after completion. We introduce $\varepsilon$-MemEvo, a framework for cross-task knowledge transfer in LLM program evolution. $\varepsilon$-MemEvo stores prior experience as task-agnostic tactic memories: compact natural-language summaries of successful algorithmic strategies rather than raw code, enabling transfer across tasks with different APIs and evaluators. To avoid negative transfer from semantically mismatched memories, $\varepsilon$-MemEvo uses an adaptive injection gate that decides whether retrieved memories should be injected, and at what intensity. We evaluate $\varepsilon$-MemEvo on 8 diverse optimization benchmarks spanning mathematical optimization and systems engineering, using a content-level Leave-One-Out protocol that excludes target-task memory entries. On the primary

---

### [48] Dead text or binding clause? Measuring and restoring constraint influence in black-box LLM dialogues

**链接**: https://arxiv.org/abs/2608.12599
**作者**: Haoyuan Zhu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn dialogues let users revoke constraints as easily as impose them, but revocation does not reliably take effect: models keep enacting withdrawn requirements (occasionally beneath comments asserting their removal), a failure we call \emph{behavioral relapse}, or revocation inertia. No existing instrument measures this influence per clause, predicts it before delivery, or repairs it under matched budgets. \sysname{} closes the three gaps through the model API alone: a contract ledger pairs every constraint with an executable checker, records revocations as tombstones, and compiles the net constraint state ahead of time into a single specification; a sequential ablation probe measures per-clause adherence and incremental behavioral effect; a repair ladder operates under token- and attempt-matched budgets. On \dataname{} (\NTasks{} HumanEval tasks, \NClauses{} verified checkers), relapse at an 8B operating point climbs from \ScaleDelayedMTwo{} to \ScaleDelayedMEight{} as constrain

---

### [49] LLM-Guided Graph Generation for Structure-Based Local Improvement Methods

**链接**: https://arxiv.org/abs/2608.13333
**作者**: Hai Xia, Vaidyanathan Peruvemba Ramaswamy, Stefan Szeider
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large neighborhood search normally selects a random subset of decision variables for iterative optimization. For efficiently solving different problems, researchers tend to design variable selection strategies by taking into account structural features from different domains. In this paper, we build an automatic pipeline that is problem-agnostic to all problems in the MiniZinc format. By prompting an LLM with our semantic guidelines, we guide the LLM to produce a graph generator that maps any instance of a problem type to a uniform weighted graph, where nodes represent decision variables and edges represent constraint relationships. These problem-agnostic graphs guide our structure-based local improvement framework (SLIM) in variable selection. Meanwhile, the weighted graph enables all problem instances to share the same generic graph representation, from which the same graph features can be extracted and used for configuration selection. We evaluated our pipeline on instances across 2

---

### [50] TsuGO: Probing Search Efficiency in LLM Reasoning via Go Life-and-Death Problems

**链接**: https://arxiv.org/abs/2608.13221
**作者**: Shunwen Bai, Ziping Ma, Chaoyang Zhang, Yarong Wang, Jiale Liu, Zhen Qin 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The evaluation of LLM reasoning is moving from final-answer accuracy to process-level assessment, yet existing methods still fail to capture how models plan reasoning paths and allocate reasoning resources--that is, how they organize search. Prior process-level methods focus on the coherence and redundancy of chain-of-thought (CoT), and most benchmark tasks have a single objective solvable by static capabilities such as derivation and tool use, leaving search organization unmeasured. We introduce TsuGO, a process-level reasoning benchmark for evaluating Search Efficiency in LLM reasoning through Go life-and-death problems. These problems provide closed and verifiable solution spaces with an inherent adversarial structure, making candidate generation, response checking, branch comparison, and backtracking necessary parts of reasoning rather than incidental trace patterns. By constraining the solution space, TsuGO disentangles domain knowledge from search organization, parses CoT into a 

---

### [51] From Caveman to Expert Analyst: Energy Consumption of Variable LLM Tasks

**链接**: https://arxiv.org/abs/2608.12350
**作者**: Diego Manya, Ethan I. Thorpe, Ji Zhang, Myranda Shirk, Jiamian He, Angel Hsu 等 (7 人)
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The energy demand growth and environmental impacts of artificial intelligence (AI) have generated substantial interest in supplying sufficient low-cost electricity for AI-driven data center development. Research on the ability of demand-side management to address these challenges has been more limited. Shifting the amount or timing of demand from retail, corporate, and other organizational behaviors is a plausible option but only if changes in demand-related behavior have important effects on the envi- ronmental and electricity effects of AI. This article tests four retail (i.e., consumer) user behaviors with high behavioral plasticity to assess their technical abatement potential. The research concludes that non- reasoning models provide sufficient quality while consuming close to one-twentieth of energy compared to reasoning models, saving an amount equal to the annual electricity requirement of at least 141,000 US households under daily usage assumptions. Simple prompt modifications

---

### [52] Practice Makes Unsafe: Skill Misevolution in Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2608.12851
**作者**: Xutao Mao and Liangjie Zhao and Xiang Zheng and Cong Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving LLM agents convert successful trajectories into persistent cross-task state. An unsafe success can thereby become reusable policy after its triggering input disappears. Skill evolution makes this failure measurable by distilling operational trajectories into executable, transferable, and inspectable procedures. Because evolution optimizes task outcomes rather than procedure safety, compromised experience can cause skill misevolution. Existing benchmarks measure current behavior or static artifacts but cannot attribute risk across authoring, retrieval, and later execution. To expose this lifecycle, we introduce SkillMisevo-Gym, a lifecycle-aware harness that versions skill state across agent frameworks, and SkillMisevo-Bench, a frozen design from malicious exposure to carryover tasks, with concept-aligned benign tasks and nine lifecycle metrics. We also introduce SafeEvolve, a wrapper that repairs unsafe content and governs subsequent reuse. Across 25 agent-method configu

---

### [53] Evolution of AliYANG: Model-driven and LLM -assisted Network Configuration Management

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3789240.3829193&hl=zh-CN&sa=X&d=8521347488309956589&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-zfqkQ3mEYfl7giBOZY_Pkc&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: M Yu, X Zhang, Z An, E Wang, B Zheng - Proceedings of the ACM SIGCOMM 2026 …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> • LLM -assisted automation for model evolution. We propose and evaluate LLM -assisted methods to reduce the manual effort of vendor model augmentation, core model construction, and translation code generation, improving scalability as networks

---

### [54] Tracing Provenance and Detecting Tampering with Complementary LLM Watermarks

**链接**: https://arxiv.org/abs/2608.12713
**作者**: Xiaoyan Feng, Yanjun Zhang, He Zhang, Leo Yu Zhang, Shirui Pan
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Watermarking LLM-generated text is an important task for tracing its provenance. Existing LLM watermarks preserve provenance under editing, but this same robustness allows an adversary to alter critical content while retaining attribution, a vulnerability known as piggyback spoofing. We introduce an innovative watermark that jointly provides provenance and tamper evidence. It co-embeds a robust signal and a fragile signal into each generated token. The signals share the same mechanism but use independent keys and different seeding windows over normalized text, making one resilient to edits and the other sensitive to reader-visible changes. Multiple rounds of unbiased tournament reweighting preserve the expected generation distribution, while a periodic round-allocation pattern controls the trade-off between the two signals. At detection, their scores form a two-dimensional space supporting three decisions: Intact, Tampered, and No-Watermark. Across two large language models and two pro

---

### [55] Reduced Matrix Multiplication: Input-Adaptive Matrix-Product Reduction for LLM Inference

**链接**: https://arxiv.org/abs/2608.13426
**作者**: Zixuan Lan, Yanhong Li, Jiawei Zhou
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based language models achieve strong performance but incur substantial inference cost due to repeated high-dimensional matrix multiplications. We propose Reduced Matrix Multiplication (RMM), a training-free, input-adaptive inference method that reduces Transformer matrix products by selecting informative slices along their contraction dimensions, without modifying model weights. Under a simple retention-ratio control, RMM provides a smooth and predictable accuracy-efficiency trade-off. Across language models ranging from 1B to 70B parameters, we find that reduction tolerance depends on the model family, task, component, and retention ratio, although it often improves with model scale. Under moderate reduction, RMM remains robust across the evaluated discriminative, autoregressive generation, and long-context settings. We further show that the same principle extends to multimodal vision-language inference. Mechanistic ablations reveal a structural asymmetry within Transforme

---

### [56] Integrating LLM with consortium blockchain for personalized and verifiable online education in higher education

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1186/s41239-026-00618-5&hl=zh-CN&sa=X&d=16601904748976408704&ei=BHh_avvFMb6jieoPpIfI-QM&scisig=AIVdB-y9OTXOz_elsBVCxjuGQJB1&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: F Xiao, J Huang, JX Huang, H Ren, L Li - International Journal of Educational …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> deploying these LLM services. To address these challenges, this paper proposes a novel framework that Integrates LLM with consortium blockchain for personalized and verifiable online education. Our design features a synergistic architecture in

---

### [57] SkillShapley: Boundary-Adaptive Shapley Valuation for Skill Step Attribution in LLM Agents

**链接**: https://arxiv.org/abs/2608.13173
**作者**: Chang Liu, Yuqi Zhang, Yiman Zhong, Boyi Liu, Hengjun Wang, Shuyue Wei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills are crucial external instructions that enable language agents to execute long procedural tasks such as coding or document processing. Existing agent skills are primarily created through human manual crafting or agent execution traces, with limited understanding of how each step contributes to overall skill performance on specific tasks; i.e., there remains an open problem in quantifying the contribution of individual steps within an agent skill. To address this issue, we first model skill-step attribution as a Shapley value-based contribution estimation problem, and then propose SkillShapley, a step-level attribution framework for agent skills. Notably, SkillShapley operates in two phases, motivated by key empirical insights, i.e., discretized benchmark rewards that create sharp performance cliffs, and step interactions that are largely additive rather than synergistic. Specifically, it first identifies informative coalitional regions, and then adaptively samples new coali

---

### [58] When Truth Is Distributed: Misinformation Derails Collective Fact Recovery in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.03421
**作者**: Chenfei Yan, Zeyang Yue, Feifei Zhao, Erliang Lin, Lu Jia, Haibo Tong 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Topics as Proxies for Sociodemographics: How Conversational Context Affects LLM Answers

**链接**: https://arxiv.org/abs/2606.02776
**作者**: Vera Neplenbroek, Gabriele Sarti, Arianna Bisazza, Raquel Fern\'andez
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] Beyond the Best Guess: Improving LLM Solution Coverage with Evolution Strategies

**链接**: https://arxiv.org/abs/2608.12679
**作者**: Conor F. Hayes, Elliot Meyerson, Kajetan Schweighofer, Roberto Dailey, Babak Hodjat, Risto Miikkulainen 等 (7 人)
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed in discovery domains such as math and science. The usual approach is to present the problem to the model and use its answer as the proposed solution. However, beyond this best guess, discovery can be enhanced by increasing test-time compute. In a process called pass@k, the model is allowed to explore the solution space and generate diverse candidate solutions. Unfortunately, the standard approach to post-training LLMs through Reinforcement Learning (RL) may limit pass@k: the model's output distribution narrows around high-reward outputs, causing the solution coverage to collapse. The alternative is to use Evolution Strategies (ES), a population-based, gradient-free post-training method that optimizes directly in weight space through random perturbations. As this paper shows, ES achieves consistently higher pass@k than RL and produces a broader output distribution with greater solution coverage. This coverage in turn makes it possib

---

### [61] CogChat: Knowledge Graph-Augmented Conversational AI with Heterogeneous Graph Transformer for Cognitive Grounding in Design Generation

**链接**: https://arxiv.org/abs/2608.13216
**作者**: Jiin Choi, Kyung Hoon Hyun
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based chat systems have become valuable tools for design practice, enabling rapid ideation and flexible task support. Yet these systems process designer utterances as generic sequences, maintaining context through recency rather than through any model of how the speaker organizes knowledge. In design conversation, this gap compounds as relational context decays between turns, identical words go unresolved across designers, and the conversation loops or restarts rather than deepens. We present CogChat, a real-time chat framework that grounds conversational AI in a personal heterogeneous knowledge graph constructed from each designer's input. The system extracts typed entities and relations into a heterogeneous graph, then applies a HGT (Heterogeneous Graph Transformer) to select structurally relevant nodes for response generation and to generate both intentional and exploratory probing questions. Technical evaluation shows that HGT-based entity selection outperforms both ungrounded 

---

### [62] Designing AI Pipelines for Decision-Ready ITSM Intelligence

**链接**: https://arxiv.org/abs/2608.12670
**作者**: Archan Dutta, Yash Dharmadhikari, Marat Valiullin, Rahul Guha, Alexander Liss
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> IT service management (ITSM) systems accumulate large volumes of heterogeneous ticket data that are difficult for sales and executive stakeholders to convert into actionable intelligence. This paper presents a sociotechnical AI pipeline, designed and evaluated following design science research principles, that transforms raw ITSM exports into a multilevel decision-support artifact. The pipeline combines LLM-based schema normalization, HDBSCAN sub-topic clustering, and hierarchical agglomerative clustering to generate executive-facing Main-topics and granular Sub-topics. A stakeholder evaluation across six artifacts and five raters from Sales Engineering and customer success roles shows that all four decision-support metrics, interpretability, actionability, trust, and likelihood of use, on average exceed 4.0 out of 5.0, with trust as the most consistent signal. The findings position ITSM analytics as an Information Systems (IS) problem of transformation, abstraction, and human-centered

---

### [63] QuoteBench: How Matched Scores Can Hide Command-Path Failures

**链接**: https://arxiv.org/abs/2608.13547
**作者**: Shangao Li, Yao Zhang, Volker Tresp, Yuanyuan Yang
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM coding agents issue Bash commands through interfaces that may serialize, wrap, and reparse model output. Matched execution scores alone cannot distinguish command-generation errors from failures introduced after generation. QuoteBench measures this boundary with exact final-state validation on 56 one-shot tasks from 14 incident-derived families, crossing the generation contract with the execution transport around one deliberately unescaped added parser. Escaping at the interpolation point reproduces each replayed reply's raw-path outcome, so any recovery under a disclosed boundary must come from the model changing its generation. Across eight same-window configurations, replaying the same reply through the added parser lowers success by 55.4 to 73.2 percentage points; disclosure recovers 30.4 to 60.7 points for six configurations, and zero or slightly negative for the other two. Raw generation is nearly saturated at the frontier; boundary adaptation is what still separates models. 

---

### [64] Not All Nudges Land: Behavioral Controllability and Elaboration Quality in AI-Supported Journaling

**链接**: https://arxiv.org/abs/2608.12582
**作者**: Nadia Mehjabin, Henry Kautz, Subigya Nepal
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI journaling tools can tailor prompts to a person's own sensed behavior, but it is unclear which behaviors respond to them. We analyzed 369 journal entries from an eight-week passive sensing study. An LLM labeled each entry as expressing an intention to change a behavior or not, and we measured follow-through against 26 sensor features with a 3-day before/after comparison. Responsiveness depended most on whether a behavior involves other people. Behaviors that depend on others improved in only 15 to 22% of cases, while behaviors a person can act on alone improved more often, up to 50 to 63%, though unevenly. How users wrote mattered less. No single text feature separated improved from unimproved entries; writing carried signal only within specific behaviors, most clearly for text messaging and for longer, more personal intention entries. The sample is small, so we treat these as exploratory patterns that point to where AI journaling nudges are most likely to work.

---

### [65] Class-Structure Preservation Beats Diversity: A Comprehensive Benchmark of Text Augmentation Methods for Imbalanced Text Classification

**链接**: https://arxiv.org/abs/2608.12340
**作者**: Keito Inoshita
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid advancement of large language models (LLMs), generative data augmentation has attracted considerable attention for imbalanced text classification in natural language processing. However, no empirical benchmark to date has compared LLM-based augmentation against the embedding-space SMOTE-style retrieval (EmbSMOTE), a strong classical reference for imbalanced classification. In this study, a controlled benchmark of 11 augmentation methods, spanning classical perturbation, embedding-space retrieval, and LLM-based generation, is newly constructed on seven public text classification datasets covering class counts $K=2$-$28$ and imbalance ratios of 1.1 to over 500, evaluated with five random seeds per cell using macro F1, Welch's $t$-tests, five distributional metrics, and an LLM-family sensitivity analysis based on Qwen3-8B. The experimental results reveal that all LLM-based methods are statistically equivalent or inferior to EmbSMOTE, with the performance gap widening monoto

---

### [66] DFM Mimir v1: An Open HRM Delivering Frontier Performance at 1B Parameters Using Only Permissible Post-Training Data

**链接**: https://arxiv.org/abs/2608.13517
**作者**: Peter Schneider-Kamp, Jacob Nielsen, Gianluca Barmina, Kenneth Enevoldsen, Lukas Galke Poech
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current large language model development relies on massive, often non-permissible datasets, creating a high barrier for researchers committed to open-source and ethically sourced data. We introduce Mimir v1, a 1-billion-parameter language model based on the Hierarchical Reasoning Model (HRM) architecture, that is trained from scratch and delivers highly competitive performance for English and sets a new state of the art for Danish using only permissible post-training data. Trained on a mixture of 161 datasets, Mimir v1 outperforms the original HRM-Text 1B and competes with larger frontier models like Qwen 3.5 4B and Gemma 4 E2B, tested across 20 benchmarks for English, Math & Code and Danish. The model is available on the Hugging Face Hub: https://huggingface.co/danish-foundation-models/DFM-Mimir

---

### [67] PatientAct: Theory-Grounded Mental Health Client Simulation

**链接**: https://arxiv.org/abs/2608.12750
**作者**: Sahand Sabour and TszYam NG and Yaqian Chen and Guanqun Bi and Jialu Zhao and Minlie Huang
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based simulated clients are increasingly used to train novice counselors, evaluate LLM therapists, and generate synthetic data. However, current simulators produce overly cooperative clients that disclose too readily, accept therapeutic reframes without resistance, and resolve core issues within a single session. We trace these issues to profiles that lack causal depth and behavioral mechanisms that treat all content as equally accessible. We present PatientAct, a framework for client simulation grounded in established clinical theories. Our profiles integrate the 5Ps clinical case formulation, providing causal depth without tying the design to any single therapeutic modality. During simulation, profiles include a dynamic memory layer in which items carry trust thresholds (e.g., symptoms are available early, whereas formative memories require a sustained therapeutic alliance). At each turn, the client's emotional reaction and behavior are modeled before generating a response. If th

---

### [68] Do LLMs Beat Nash? Testing Decentralized Coordination in Self-Play Multi-Agent Games

**链接**: https://arxiv.org/abs/2608.12547
**作者**: Deborah Sinishaw, Qile Zhu, Edwin Meriaux, and Gregory Dudek
**来源**: cs.MA cs.RO
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents deployed without a central controller are often assumed to require communication to coordinate their actions. We ask what remains possible without it: when independent instances of the same model cannot communicate, can they still reason about their counterparts well enough to exceed the standard game-theoretic baseline for uncoordinated play? We introduce a benchmark of one-shot, no-communication games in which each of thirteen language models is told only that its counterparts are running the same model and is evaluated against the Nash equilibrium of the underlying game. In two-player matrix games spanning seven archetypes and two to ten actions per player, two frontier-hosted models consistently exceed their Nash benchmark, approaching the optimal joint outcome in several archetypes, while most open-weight models achieve only partial gains that vary sharply by game structure. Performance degrades substantially in team-based games with four or more interc

---

### [69] Unified Multi-Dimensional Benchmark for Complex Graph Reasoning in Large Language Models

**链接**: https://arxiv.org/abs/2608.12391
**作者**: Fali Wang, Ali Al-Lawati, Iliyas Bektas, Jinxuan Fang, Alek Melenski, Tianxiang Zhao 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph reasoning provides a promising testbed for evaluating the reasoning ability of large language models (LLMs), as graph instances can be programmatically generated, structurally controlled, and naturally scaled to long-input settings. However, existing graph reasoning benchmarks have limited coverage of data complexity, rely heavily on manual construction, and lack unified evaluation across text-based and code-based reasoning modes. To address these limitations, we propose {\dataset}, a five-stage \textit{semi-automatic} framework for constructing complex graph reasoning benchmarks. It expands benchmark coverage along five dimensions: \textit{Graph Size}, \textit{Task Complexity}, \textit{Task Description}, \textit{Graph Loading}, and \textit{Task Source}. The framework uses an LLM-based data generator to automatically produce task descriptions, graph data, reference solutions, graph-loading scripts, question forms, and evaluation scripts, while retaining human validation at key qu

---

### [70] MARC v1: An Open-Source Multi-Agent Framework for Clinical AI Reasoning and Coordination

**链接**: https://arxiv.org/abs/2608.13476
**作者**: Saisha Shetty, Satvik Tripathi, Austin Lin, Colin Zhao, Theodore Kim, Don Enwerem 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Multi-Agent Reasoning and Coordination (MARC), an open-source framework that replaces monolithic LLM prompting with deterministic multi-agent orchestration for clinical reasoning. MARC coordinates role-specialized agents for extraction, reasoning, answer generation, and evaluation, with explicit context passing and traceable intermediate outputs, enabling stage-wise failure attribution. We additionally introduce a Decomposer module that generates task-specific agent prompts from a plain-language description, eliminating manual prompt engineering. The framework supports both API-based and local CPU-compatible deployments and is entirely configurable via YAML, without code modifications. MARC is designed to be model-agnostic, interpretable, and accessible to clinical domain experts without programming expertise. The full framework is available at https://github.com/Penn-RAIL/MARC-v1.

---

### [71] A Cloud-Edge System for Multimodal Clinical Screening in Resource-Constrained Rural Settings

**链接**: https://arxiv.org/abs/2608.12745
**作者**: Hei Ting (Una) Chan, Chenwei Wu, Xueshen Liu, Zesen Zhao, Boyuan Zheng, Luis Filipe Nakayama 等 (10 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical AI has demonstrated specialist-level diagnostic accuracy, yet these capabilities remain largely inaccessible in resource-constrained rural settings where bandwidth is scarce, compute is limited, and clinical decision-making requires integrating heterogeneous modalities. We introduce a cloud--edge collaborative architecture that addresses these constraints: lightweight, domain-specific models on the edge transform raw medical data into compact structured outputs, while a cloud LLM synthesizes these outputs into clinical summaries. An LLM-based orchestrator dynamically selects diagnostic tools based on patient context, promoting comprehensive modality coverage without processing irrelevant inputs. We evaluate on 20 multimodal clinical cases spanning cardiac, obstetric, trauma, and screening scenarios under three simulated network profiles (500,kbps--5,Mbps). The hybrid system achieves 98--99% diagnostic tool recall with 92--96% precision, matches or exceeds cloud-only baselines o

---

### [72] Large Language Models Can Follow Instructions, But Not Many at Once: Phase Transitions in Compositional Constraint Satisfaction

**链接**: https://arxiv.org/abs/2608.12426
**作者**: Mariya I. Vasileva
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed in settings that require simultaneous adherence to multiple explicit constraints - reasoning structure, safety boundaries, output schemas. Individual constraints are handled proficiently, but the compositional regime, where many must hold jointly, remains poorly characterized: how rapidly does performance degrade, what governs the degradation, and can the collapse be mitigated? We introduce Constraint Saturation Evaluation (CSE), a procedurally generated benchmark that systematically varies the number of simultaneous constraints (k), with every constraint scored by a deterministic, rule-based verifier and zero LLM-judge involvement: 15 models, 36 constraint types, 369,753 checks at k=1-12. Three findings emerge. First, per-constraint pass rate decays gradually and predictably, while the chance of satisfying all k constraints collapses - a model passing individual constraints at ~41% at k=8 succeeds on all eight just 5.7% of the time. Seco

---

### [73] vToken: Token-Level Virtualization for Reclaimable KV Caches

**链接**: https://arxiv.org/abs/2608.13263
**作者**: Yuanhang Gao, Xiangrui Yang, Yuanfeng Chen, Hongjia Chen, Qianru Lv, Wenfei Wu 等 (7 人)
**来源**: cs.AI cs.DC cs.OS
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model serving faces a critical memory bottleneck: the KV cache grows with sequence length and batch size. PagedAttention uses fixed-size memory blocks to reduce allocator-level fragmentation, but recent KV eviction algorithms operate at a token granularity finer than block-level management. This mismatch causes intra-block fragmentation, leaving a large fraction of allocated KV memory unreclaimable. We present vToken, a lightweight token-level virtualization layer that decouples logical token liveness from physical block placement. vToken maintains a stable logical token view through token-table indirection and realizes physical reclamation by repacking live tokens asynchronously. The design preserves PagedAttention kernels and CUDA Graph compatibility. We implement vToken in vLLM and evaluate it with H2O, Random, and Scissorhands across models. Compared with a paired Naive-Evict baseline, vToken reduces retained KV blocks per request by 27.2\%--72.3\% and improves SLA-c

---

### [74] AaLLM: An End-to-End Analog Circuit Design Framework from Topology Generation to Sizing Using Large Language Models

**链接**: https://arxiv.org/abs/2608.13472
**作者**: Mohammed Ayman Habib, Rylan Hart, Morteza Fayazi
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog circuit design is a time-consuming, iterative process in a nonlinear and high-dimensional design space that relies heavily on expert intuition. Among recent developments, LLMs have introduced a promising approach by bringing natural language reasoning to circuit design tasks. The majority of conventional LLM-based approaches provide fragmented solutions that focus either only on sizing or topology generation. These methods require adding specific technical knowledge manually, which is inefficient and prone to hallucinations during circuit sizing. Moreover, the inherent trade-off in meeting different specs makes current approaches iterative and tedious. Another shortcoming is the inability to create innovative topologies, which may lead to sub-optimal designs due to reliance on conventional topologies. In this paper, we present AaLLM, an open-source end-to-end multi-agent LLM workflow that takes user specs as input and outputs the appropriate netlist, encompassing both topology g

---

### [75] Before You Say It: Anticipating Verbal Behavior from Longitudinal Everyday Conversations with LLMs

**链接**: https://arxiv.org/abs/2608.13454
**作者**: Yasith Samaradivakara, Valdemar Danry, Paul Liang, Pattie Maes
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowing someone deeply means not just understanding what they say or do but also how they will likely think, react, and engage across situations. Such predictions could eventually inform systems to anticipate when the individual is about to deviate from their goal, catch regrettable behaviors before they are made, and surface blind spots before they take hold. While many interactive systems model users to enable more personalized interactions, most cannot make such behavioral predictions, as this often requires longitudinal observation and inference of how the individual's behaviors unfold across various everyday situations. In this work, we introduce a novel LLM-based predictive behavioral modeling approach that anticipates a user's likely behavior across everyday conversational situations. We (1) collect a longitudinal dataset of over 1000 hours of naturalistic conversations from 14 participants using a wearable smartwatch; (2) evaluate LLM-based predictions against ground truth beha

---

### [76] Perturbation-based Regional Interpretability through Subtraction Mapping (PRISM): naming-error dissociations in language models and post-stroke aphasia

**链接**: https://arxiv.org/abs/2608.12717
**作者**: Xiang Guan, Roger D. Newman-Norlund, Yong Yang, Saeed Ahmadi, Regan Willis, Nadra Salman 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mechanistic interpretability of large language models lacks spatially resolved, falsifiable tools for testing whether internal components are specialized for distinct cognitive operations. We adapt subtraction analysis, the standard framework of human neuroimaging, from biological brains to perturbed transformers, and apply the same logic to both substrates in parallel. Building on the Brain-LLM Unified Model (BLUM), which showed that layer-perturbed LLaVA-1.6-Vicuna-13B error profiles match the lesion patterns of aphasic patients, we develop PRISM (Perturbation-based Regional Interpretability through Subtraction Mapping). PRISM maps the seven clinical Philadelphia Naming Test categories, subtracts error classes pairwise, and treats each perturbation seed as a subject in a group analysis with threshold-free cluster enhancement along the layer axis. We run a structurally matched analysis on 213 chronic post-stroke aphasia patients using correlation-difference lesion-symptom mapping, and

---

### [77] When AI Is Your Pastor: A Benchmark for Theological Triage and Pastoral Guidance in Large Language Models

**链接**: https://arxiv.org/abs/2608.12324
**作者**: Alex Chao
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People increasingly ask large language models (LLMs) for counsel on questions of faith, doctrine, and pastoral care. These questions are not ordinary information requests. Some ask about core Christian beliefs, some ask about real disagreements among faithful traditions, some require humility because the issue is prudential, and some are pastoral situations where safety and human referral matter more than theological completeness. Existing benchmarks do not evaluate this structure. We introduce FMG-Bench, the Faith & Moral Guidance Benchmark, a 120-scenario benchmark for evaluating large language model behavior in English-language Christian theological triage and pastoral guidance contexts. FMG-Bench v1 evaluates 14 advanced models across 8,792 scored responses, comparing raw model behavior with three guided instruction settings. In our production run, placing models inside a structured harness improves over raw model behavior by +3.96 points on average, with every model improving. The

---

### [78] InterSAGE: The Secure and Verifiable Interoperability Protocol for An Internet of Agents

**链接**: https://arxiv.org/abs/2608.13030
**作者**: Zhenhua Zou, Sheng Guo, Qiuyang Zhan, Lepeng Zhao, Shuo Li, Zhuotao Liu
**来源**: cs.CR cs.MA cs.NI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The emerging Internet of Agents enables LLM-powered agents to discover peers, invoke tools, and delegate tasks across organizational boundaries. Existing protocols increasingly define how agents exchange messages, but not how an agent proves its identity, authorization, advertised capabilities, or accountability after delegation. We present InterSAGE, a trust-native protocol suite that supplies this missing security substrate alongside, rather than in place of, communication protocols. InterSAGE comprises four layers: Persistent Identity, Discovery, Trust Negotiation, and Accountability. Its four core primitives are: (1) Agent Identity Cards that bind developer, code package, operator, and deployment context; (2) capability-aware discovery using DID-bound Verifiable Credential manifests; (3) trust negotiation combining monotonic capability attenuation with two-tier access control; and (4) kernel-mediated cryptographic audit trails that bind usage, delegation, and execution traces to ag

---

### [79] PROVE-RT: Generating Mechanized Theorem Prover Scripts for Real-Time Systems using LLMs

**链接**: https://arxiv.org/abs/2608.12762
**作者**: Sadat Shahriyar, Shareef Ahmed, Abdullah Al Arafat
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Schedulability analysis is essential for certifying real-time systems, but existing tests are often developed through pen-and-paper proofs that are difficult to scale, validate, and maintain. Mechanized verification in PROSA/ROCQ offers a rigorous alternative, yet manually constructing such proofs requires substantial domain expertise and proof-engineering effort. Recent successes of large language models (LLMs) across a wide range of tasks make them promising candidates for generating PROSA/ROCQ scripts for mechanized theorem provers. However, state-of-the-art LLMs often lack the PROSA-specific knowledge required to correctly use its modeling abstractions and proof patterns. This paper introduces PROVE-RT, an LLM-assisted framework for generating PROSA/ROCQ scripts to mechanize schedulability analyses in real-time systems literature. PROVE-RT guides generation through dependency-aware informal sketches, retrieval from processed PROSA documentation, staged skeleton generation, and proo

---

### [80] DMDIntel: Interpreting Large Language Models via Dynamic Mode Decomposition

**链接**: https://arxiv.org/abs/2608.13048
**作者**: Amogh Joshi, Animesh Mukherjee, Sergey Utyuzhnikov
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we introduce DMDIntel which uses dynamic mode decomposition (DMD) to make the predictions made by LLMs in a classification task interpretable. It develops an input attribution pipeline, that first decomposes the hidden states of an LLM into prominent patterns, also known as modes, and then associates ranks to the input tokens based on the projection values on those modes. Rigorous experiments across three datasets and three model families consistently show that the ranked attribution of input tokens obtained using DMDIntel by far outperforms state-of-the-art techniques such as principal component analysis, integrated gradients and SHAP.

---

### [81] RippleMem: From Isolated Retrieval to Associative Recollection for Long-Term Agent Memory

**链接**: https://arxiv.org/abs/2608.13334
**作者**: Jingbo Ji, Lingyi Li, Xilong Cheng, Yuhao Zhou, Wenji Zhang, Yuting Tan 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly rely on external memory to support long-horizon reasoning and interaction. However, the main bottleneck is not simply storing past experience, but recovering the right set of evidence when relevant information is distributed across many interactions. Existing approaches struggle with this access problem. Full-context methods require noisy long-context search, flat retrieval often returns isolated and incomplete records, and graph-based memory systems can be expensive to construct while compressing rich event context. We introduce RippleMem, a long-term memory system that replaces one-shot retrieval with adaptive associative recollection. Inspired by cue-dependent episodic retrieval and associative completion, RippleMem stores interaction history as cue-rich episodic memory units and organizes them in an event-centric memory graph. Given a query, it first recalls relevant memory anchors through hybrid cues, then expands from these anchors along semantic and

---

### [82] SkillEvo: Self-Renewing Evolution Gradients from Multi-Turn Interaction Feedback

**链接**: https://arxiv.org/abs/2608.13120
**作者**: Qianxi Yan, Chunrong Chen, Jiuzhou Zhao, Min Zhang, Yongzhou Xu, Xiaochuan Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent Skills are today either hand-authored or produced in a single LLM generation pass, and consequently possess no closed loop through which they might improve from the interaction failures they actually cause. Recent work does close this loop, but derives its feedback from single-turn question-answering evaluation. The consequence is a sharp asymmetry: once the first round has patched the gaps that a single exchange can reveal, the evolution gradient decays, the defects that surface only across multiple turns remain invisible, and evolution stalls. Governance in these systems is likewise driven by an end-to-end verification score, a scalar gate that can reject a degraded candidate but can neither localize nor repair its structural cause. We argue that the binding constraint on sustained skill evolution is neither editing capability nor the number of iterations, but whether the evaluation feedback keeps supplying trustworthy evolution gradients. We introduce SkillEvo, in which trustw

---

### [83] SteerBench-Work: A Benchmark for Agent Steering at Action Boundaries

**链接**: https://arxiv.org/abs/2608.12654
**作者**: Oguz Serdar, Cuneyt Mertayak
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents act through tools, and a single step can send an email, merge a pull request, or wire a payment. The steering decision is the pre-commit choice at that boundary: proceed, or hold for human or policy review. We introduce SteerBench-Work, an incident-anchored, bidirectional benchmark for that decision in workplace agents across developer operations, customer service, finance, legal, medical, HR, and security. Release v2026-05 contains 106 scenarios anchored in public incidents, paired evidence-reversed mirrors, and calibration controls, with labels split nearly evenly between proceed and hold so the two error directions get near-identical numbers of chances. A model sees the proposed action and the available evidence, returns a gate decision, and is scored on whether it crosses or holds the boundary correctly. Across 30 model conditions the failures run almost entirely in one direction: models wrongly hold authorized, evidence-cleared work on 28.1% of opportunitie

---

### [84] On Measuring Semantic Preservation in Legal Ontology Learning

**链接**: https://arxiv.org/abs/2608.12326
**作者**: Albert Sadowski and Jaros{\l}aw A. Chudziak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontology learning transforms unstructured text into structured representations for automated reasoning. Yet structuring information risks losing it, and current evaluation methodologies cannot detect such loss, focusing on structural correctness while failing to measure whether meaning survives transformation. We propose an evaluation methodology that addresses this: comparing LLM task performance on source documents against performance on transformed representations, with the difference quantifying semantic loss. We demonstrate this approach on legal merger agreement analysis, a domain chosen for its complex language and precise semantic requirements, comparing direct LLM application against three ontology learning methods across six language models. The results reveal systematic semantic loss with significant variation based on reasoning complexity and model-method interactions. Our contributions are: (1) an evaluation framework for measuring semantic preservation in ontology learnin

---

### [85] Why AI Governance Frameworks Are Hard to Adopt: A Role-Based Stress Test of the NIST AI RMF

**链接**: https://arxiv.org/abs/2608.12352
**作者**: Joseph R. Simons and David A. Broniatowski
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI governance frameworks can be known, used, and implemented in form without becoming governance in practice. This paper examines that problem through a role-based stress test of the NIST Artificial Intelligence Risk Management Framework (AI RMF) in consumer lending. We treat framework adoption as a governance translation problem: whether RMF language can become role-usable, cross-level, authority-connected governance over the AI system-in-use, rather than producing governance-looking artifacts. The study uses LLM-based role simulation as a structured analytic probe. We apply a 4 $\times$ 2 $\times$ 3 design across four organizational roles, two AI deployments, and three governance hard cases, producing 120 scored responses. Results show that local translation was not the main problem. Simulated actors generally understood their assigned roles and translated the RMF into local activity. The harder problem was whether that activity became governance value. Actor role was strongly associ

---

### [86] Jagged Judges: Epistemic Stability Under Silence, Pressure, and Persistence

**链接**: https://arxiv.org/abs/2608.12645
**作者**: Justin Zhao, Himaghna Bhattacharjee, Hannah Korevaar, Bhaktipriya Radharapu, Khalid El-Arini
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges have become central infrastructure for model evaluations, online grading, and reward modeling. Judges are typically validated by accuracy on golden data, but accuracy says little about whether they are stable under re-prompting, challenge, or sustained pushback. We introduce the \emph{Wiggle Framework}, a unified stress test for epistemic stability in LLM judges. The framework decomposes judge robustness along three dimensions: Mechanical Consistency (stability under re-prompting and reframing), Single-turn Conviction (stability under a single challenge), and Multi-turn Persistence (stability under sustained or adaptive pressure). We use the framework to study 9 frontier models across 14 judging tasks spanning safety, toxicity, AI writing detection, and political-response evaluation. Every model exhibits substantial wiggle as a judge --- flipping verdicts 25--71\% of the time under static pushback, and 62--91\% with an adversarial LLM persuader. Critically, we find that pres

---

### [87] Large Language Models Pass the History Exam But Miss the <<History>>: A Polish High School Exit Exam Matura Benchmark

**链接**: https://arxiv.org/abs/2608.12343
**作者**: Adrian Trzoss, Kacper Dudzic, Wiktor Werner, Marcin Moskalewicz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI chatbots are widely used by students as knowledge sources, yet LLM benchmarks rarely assess interpretative historical reasoning. We evaluate eight leading LLMs on the Polish high school exit exams (Matura) in history - three official papers from 2023-2025, comprising short-answer questions and extended essays - comparing model performance against the human examinee population. Every model dramatically outperforms human examinees, yet aggregate scores mask distinct competency profiles: rankings are unstable across task type, source modality, and geographical scope, with a consistent penalty on Polish versus Global history content. Qualitative error analysis reveals two recurring failure modes - source conflation, in which models reason from source content rather than treating it as an object of analysis, and temporal disorientation, in which responses are historically misplaced. This study introduces the first LLM history benchmark grounded in Polish national curriculum.

---

### [88] Lines and Ladders: A Context-Aware Multi-Agent Framework for Large-Scale Retail Price Taxonomy

**链接**: https://arxiv.org/abs/2608.12674
**作者**: Ravi Teja Chunduri, Srikaran Reddy Boya, Deep Narayan Mishra, Ajay Kumar B, Karthik Kumaran, Pranay Kona
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Maintaining price consistency and executing an Every Day Low Price strategy is critical for global retailers. However, with catalogs spanning millions of active items, manual governance of price relationships is infeasible. Inconsistent pricing across item variants distorts customer value perception and cannibalizes sales. To address this, we present a scalable, context-aware Multi-Agent Framework designed to automate the construction of "Lines and Ladders" pricing taxonomies. Our framework employs specialized LLM agents to construct these coherent pricing structures by identifying key attributes, extracting multi-modal values, and applying hierarchical grouping logic. Evaluated on real-world enterprise data and deployed in production, our 3-Agent system achieves an F1-score of 0.83 for Lines, outperforming single-agent baselines by mitigating cognitive overload. The system achieves >90% precision and >75% recall in Food & Consumables, and 80.2% assignment accuracy in the unstructured 

---

### [89] Localize, Then Reason: Visual Latent Structural Reasoning for Molecular Properties and Edits

**链接**: https://arxiv.org/abs/2608.13244
**作者**: Xingqiao Lin and Junmei Wang and Haocheng Tang
**来源**: cs.CL cs.CE q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Local chemical perception and property reasoning are both essential for understanding how molecular structure determines properties. Current LLM-based chemical reasoning methods either receive SMILES/molecular images together with descriptions of local motifs, or reason directly from molecular images. Neither approach enables the model to focus on chemically meaningful regions before reasoning. To address this gap, we propose Visual Latent Structural Reasoning (VLSR), an end-to-end framework that jointly learns localization and reasoning from molecular images. Central to our approach is a localize-then-reason strategy. VLSR first learns to locate chemically meaningful regions in a molecular image. It then reasons about their property effects in a compact latent workspace before producing the final answer. Under the same inference setup, this design achieves 9.6X higher throughput than a comparable textual-reasoning baseline.

---

### [90] FSGR: Mitigating Token Frequency Bias for Fair SID-Based Generative Recommendation

**链接**: https://arxiv.org/abs/2608.12845
**作者**: Yuchen Zheng, Sihan Xu, Jingwen Yang, Xiangrui Cai, Haiwei Zhang, Xiaojie Yuan
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic ID (SID)-based generative recommendation has recently achieved remarkable success. However, existing methods suffer from a previously overlooked fairness issue, which we term \textbf{Token Frequency Bias}, where high-frequency SID tokens are systematically over-predicted while low-frequency SID tokens are under-predicted. This bias originates from the combined effects of imbalanced semantic codebooks during SID construction, and popularity bias together with the maximum likelihood estimation objective during recommendation training, resulting in unfair exposure across item categories. Existing SID methods mainly focus on improving codebook quality and overlook the impact of token frequency imbalance on downstream recommendation fairness, while LLM debiasing methods often yield suboptimal results when directly applied to SID-based recommendation, due to the hierarchical semantics of SID tokens. To address this issue, we propose \textbf{FSGR}, a fairness optimization framework f

---

### [91] Agent Behavioral Contracts II: Certifying Compositional Reliability Without Assuming Independence

**链接**: https://arxiv.org/abs/2608.12895
**作者**: Varun Pratap Bhardwaj, Garima Singh, Arun Pratap Bhardwaj
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compositional reliability bounds for multi-agent systems multiply component reliabilities, a step licensed by a conditional-independence assumption that is routinely stated and rarely tested. We test it. Two instances of one model, in a two-agent handoff, co-fail on 90.0% of the missions on which either fails (log OR 6.66, 95% CI [6.38, 7.00]; phi 0.916), in a preregistered evaluation of 18,000 missions scored by deterministic code with no LLM judge. Substituting a different model reduces the association in six of six contrasts; substituting a different vendor, model already different, does not -- a registered hypothesis reported as a null. The error is signed and runs against the operator: positive dependence inflates joint failure above the independence product, so redundancy is over-credited exactly when components share a model. The assumption-free alternative is often vacuous, and fitting a dependence model is worse: we prove a bootstrap bound on a fitted model's functional loses 

---

### [92] StorySpark: Module-wise Evolutionary Search for Story Premise Generation

**链接**: https://arxiv.org/abs/2608.12336
**作者**: Yang Yang, Zining Zhong, Qian Cao, Jindong Li, Boyun Xu, Kaishen Yuan 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A story premise is the creative spark from which a full narrative can grow. Yet LLM-based story generation has mostly emphasized later-stage planning, controllability, coherence, and prose expansion, while premise-level ideation remains comparatively underexplored. We introduce StorySpark, a module-wise evolutionary search framework for story premise generation. StorySpark operates over interpretable narrative modules such as background, persona, event, ending, and twist, treating each active module not as a static field to fill once, but as a local search space conditioned on the partial premise built so far. For each module, it generates alternatives, evaluates them in context, refines them through feedback-driven mutation and recombination, preserves complementary strengths with Pareto-guided selection, and reallocates frontier capacity to balance branch coverage with promising directions. Multi-view automatic and human evaluations show that StorySpark produces stronger final premis

---

### [93] Explanatory Engagement Under Rare Anomalous Failure: Asymptotic Rarity in Model Behavior (or: The Asymptotic AI)

**链接**: https://arxiv.org/abs/2608.13063
**作者**: Sam Mao
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior work on LLM behavior under anomalous conditions asks whether a model notices anomalies. We ask a narrower question: once a model sits in a workflow with a low, controllable failure rate, does its explanatory engagement - length, specificity, self-reported confidence - change as failure grows asymptotically rarer? We built a local, zero-cost harness on three open-weight models (qwen3:8b, llama3.1:8b, mistral:7b) running a repeated tool-call task where one call fails at probability p, swept across eight rates from 0.2 to 0.0001, under five elicitation conditions from immediate prompting to none. We hypothesized a rise in engagement as failures grew rarer, then a collapse near a detectability threshold. Pooled across conditions this appeared false: length fell in a flat, monotonic pattern. Splitting by condition overturned that. Under immediate_forced, where the model must explain every failure instantly, the predicted rise is confirmed but followed by a plateau, not a collapse: len

---

### [94] HiRoute: Hierarchical Routed Prompt Tuning for Safety Alignment of Large Language Models

**链接**: https://arxiv.org/abs/2608.12821
**作者**: Fangzhou Chen, Shiji Zhao, Mengyang Wang, Qihui Zhu, Ranjie Duan, Maoxun Yuan 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) remain vulnerable to harmful requests and jailbreak attacks. Parameter-efficient safety alignment methods based on prompt tuning typically rely on a single global prompt or externally selected prompt modules. Such static designs struggle to maintain a cross-category safety boundary while generating constructive responses tailored to specific risks and avoiding over-refusal of benign inputs. To address these limitations, we propose HiRoute, an input-adaptive hierarchical prompt-tuning framework that separates category-agnostic safety control from category-specific response guidance. HiRoute first trains a lightweight hierarchical router on representations extracted from a frozen LLM to jointly detect harmful intent and predict multi-label risk scores. It then freezes both the backbone model and the router and uses preference optimization with alternating gradient updates to learn a shared coarse-grained prompt and a set of fine-grained prompt experts as cont

---

### [95] CAPRI: Contract-Aware Proof Repair for Isabelle

**链接**: https://arxiv.org/abs/2608.13459
**作者**: Jim Woodcock, Gabriel Leite, Augusto Sampaio, Ran Wei
**来源**: cs.SE cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We address the use of large language models (LLMs) to help discover Isabelle proofs. An Isabelle build establishes that the submitted theory is accepted, but not that an LLM changed only what the developer authorised. We present CAPRI, a contract-aware repair workflow in which Isabelle checks the proof and an independent checker enforces a machine-readable edit contract. Prompts, proposals, candidate repositories, diagnostics, verdicts, and hashes are retained for audit. We evaluate five workflows on twelve failed proofs from four developments, with three replicates per task and condition, giving 180 runs and 138 valid repairs. Of 144 terminal candidates accepted by Isabelle, six had modified protected text; all arose in iterative workflows that could edit a complete theory. A proof-body-only interface produced 29/36 valid repairs and no contract violations, compared with 31/36 for the corresponding full-theory workflow. One-shot repair produced 22/36, while a later prospectively froze

---

### [96] Non-Degenerate Risk Certification for Automated Security Decisions: A Decision-Contract Theory with ATT\&CK-Aligned Triage as a Worked Instance

**链接**: https://arxiv.org/abs/2608.12444
**作者**: Zhenpeng Li
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An unconditional risk bound on automated decisions can be satisfied without automating anything, since a selector that never acts drives the bound to zero. We show this is structural: any risk certificate is defined over a decision contract, the inputs a system acts on plus the semantic relation under which an output counts correct, and weakening either hides base-classifier error. We develop a decision-contract theory: an error-conservation law showing error is only reassigned among harmful automation, human deferral, and semantic masking; a label-free singleton capacity certifying structural incapacity, with a risk-feasible refinement separating recoverable threshold misalignment from risk-constrained incapacity; and a non-degenerate actionability certificate excluding all-abstain solutions by construction. We instantiate this on ATT\&CK-aligned alert triage for LLM-based intrusion detection, the setting that exposed the vacuity failure. Across 3 IDS datasets, 6 LLMs, and 4 error-rat

---

### [97] LittleLearner: Language Models Under Pedagogically Controlled Knowledge Exposure

**链接**: https://arxiv.org/abs/2608.13545
**作者**: Fanfei Li, Jana Zeller, Manuel Prada-Corral, Thadd\"aus Wiedemer, Prasanna Mayilvahanan, Ryan Cotterell 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern language models are trained on heterogeneous web-scale text corpora. Consequently, studying knowledge and skill acquisition is difficult, as prior exposure to related content is hard to characterize. To address this challenge, we introduce LITTLECURRICULUM, a curated 88B-token pretraining corpus tailored to U.S. elementary school material, explicitly excluding concepts, facts, and vocabulary taught above Grade 5. Training a 5B-parameter LLM from scratch on LITTLECURRICULUM yields LITTLELEARNER, a model with sufficient language competence for open-ended evaluation, yet with clear knowledge and capability boundaries mapped to interpretable curriculum guidelines. We release LITTLECURRICULUM and LITTLELEARNER as a developmentally restricted sandbox to study how models acquire, represent, and use data under a well-defined training scope. We illustrate the sandbox's utility in a first suite of experiments on injecting new knowledge through post-training and in-context learning. These 

---

### [98] Research Assistant: AstraZeneca's Agentic System for R&D

**链接**: https://arxiv.org/abs/2608.12395
**作者**: Piotr Grabowski, Mohamed Alameen, Jorge Bretones, Sabina Cardell, Miguel Carmona, Gavin Edwards 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We describe Research Assistant, an internal LLM-based system developed at AstraZeneca to help scientists and clinicians explore biomedical questions across a broad range of data sources. The system provides a chat-style interface that brings together evidence from scientific literature, knowledge graphs, chemistry, clinical trials, safety resources, expression data, and internal experimental systems. It supports both a fast mode for direct question answering and a multi-step mode for more complex research tasks. Responses are grounded in retrieved evidence and linked back to the original sources, allowing users to review and further explore the underlying data. In this technical note, we outline the system architecture, the main design choices behind the product, and lessons learned from deploying it at scale to support day-to-day R&D workflows across AstraZeneca.

---

### [99] SapiensID 2.0: Aligning Human Recognition Foundation Models with Human Perception

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.10497&hl=zh-CN&sa=X&d=6299947631656199898&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoOE-umlV76gmc1_oYfLmwf2&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=6&folt=kw-top
**作者**: Y Su, J Zhu, F Liu, AK Jain, X Liu - arXiv preprint arXiv:2608.10497, 2026
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> We hypothesize that because the invariant soft biometrics extracted from the MLLM (eg gender) naturally correlate with structural facial features, the body-centric semantic alignment successfully avoids inducing catastrophic forgetting of fine-grained

---

### [100] When the Interviewer Is a Bot: Behavior, Breakdowns, and Trust in MLLM -Led Interviews

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.10412&hl=zh-CN&sa=X&d=1404689382091303144&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoNQuRoY6HWrvPZkYmxA9ezm&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=0&folt=kw-top
**作者**: H Zhang, K Chukwuma, CM Kim, JM Carroll - arXiv preprint arXiv:2608.10412, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> default MLLM interviewing behavior. In a practice study (𝑁 = 15), participants completed a bot-led semi-structured interview and then a human-led reflection session about that experience. We contribute (i) a turn-level behavioral analysis of

---

### [101] Test-Time Self-Evolving GUI Visual Grounding via Reflection-Guided On-Policy Self-Distillation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.11191&hl=zh-CN&sa=X&d=11174646044191179210&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoM8YUj3eepVN8dq3123fKmE&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=3&folt=kw-top
**作者**: S Xuan, Z Li - arXiv preprint arXiv:2608.11191, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To evaluate these explorations, we introduce an MLLM based Reflector to assess the generated results and provide the corresponding reasoning reflections. To internalize reflection knowledge into the model weights, we propose ReflectionGuided

---

### [102] Incorporating Reflection Mechanism into Multi-Modal Reasoning for MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11634616/&hl=zh-CN&sa=X&d=10585631723390230577&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoPWpiJqHnvBaiZQ0RM2Liwy&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=7&folt=kw-top
**作者**: X Leng - 2026 10th International Conference on Electronic …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We implement ReflectCantor using two distinct MLLM backbones that represent different … staggering 14.10% net gain over the vanilla MLLM environment. A highly correlated, consistent … -based knowledge base of the backbone MLLM can

---

### [103] Temporally Grounded Compositional Camera Motion Understanding via Geometric Knowledge Distillation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.10932&hl=zh-CN&sa=X&d=4202287721851333832&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoM5bJWbFM5hPiMao6VE6puF&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=8&folt=kw-top
**作者**: D Du, S Du, J Liu, Y Yu, B Gu, T Han 等 (9 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We distill the camera token itself into the MLLM , transferring a pose-associated, geometry-informed … We use this representation as the distillation target for the MLLM . … A lightweight student predicts per-frame camera tokens from the frozen

---

### [104] VOS-Agent: The 1st Place Solution for the 8th LSVOS Challenge (MOSEv2 Track)

**链接**: https://arxiv.org/abs/2608.12721
**作者**: Canyang Wu, Jinrong Zhang, Xusheng He, Ce Bian, Xianjing Han, Jianlong Wu
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complex video object segmentation requires robust target propagation under severe occlusion, disappearance and reappearance. Although SAM3 provides strong promptable mask propagation, a uniform inference path remains unreliable for tiny targets with insufficient visual evidence and semantic-dominated targets whose identities depend on explicit attributes. To this end, we present VOS-Agent, a collaborative framework that retains SAM3 as the shared dense segmentation module and conditionally activates specialized agents according to target characteristics. A Target Perception and Routing Agent assigns each sequence to a regular, tiny, or semantic-dominated route. Tiny targets are supported by a Visual Tracking Agent through confidence-aware box prompts, while semantic-dominated targets are handled by an MLLM-based Semantic Agent through description-guided localization and candidate verification. On the MOSEv2 test set, VOS-Agent achieves 69.82% on the official $\mathcal{J}\&\dot{\mathcal

---

### [105] MAG: MAnifold Guided Semi-Supervised Multi-modal In-Context Learning

**链接**: https://arxiv.org/abs/2608.12724
**作者**: Zirui Cheng, Xun Xu, Tiankai Chen, Fady Rezk, Bowen Zheng, Xiaodong Shi 等 (10 人)
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Few-shot in-context learning (ICL) with multi-modal large language models (MLLMs) enables task adaptation without parameter updates, but its performance is highly sensitive to the quality and coverage of the selected demonstrations. While unlabeled multi-modal data is abundant, it remains elusive how to exploit them for ICL. We propose MAG (MAnifold-Guided semi-supervised in-context demonstra- tion selection), an efficient framework that leverages unlabeled data to improve multi-modal ICL. MAG formulates demonstration selection as a semi-supervised propagation problem on a multi-modal graph and adopts a two-stage strategy: (i) relevance score propagation identifies a compact set of high-impact unlabeled samples for pseudo-labeling, reducing MLLM inference cost; (ii) multi-modal relevance is used to select the final demonstrations. We show that textual represen- tations are more effective for relevance propagation, while both visual and textual modalities are crucial for high-quality de

---

### [106] StreamFlow: Dynamic Memory Flows for Streaming Video Understanding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.10949&hl=zh-CN&sa=X&d=11015084820626054691&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoOMJDN_-VWOUPy8r7qUpZSm&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=5&folt=kw-top
**作者**: M Fu, Y Zhang, W Zhang, F Guo, Q Chen, G Zhang… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> dynamic visual content, reducing redundant encoding while providing the MLLM with direct access to recent spatiotemporal information. (II… (III) Attention-guided memory injection monitors the MLLM ’s attention to visual information and injects

---

### [107] VidForensics-M1: Meta-Detection Reinforcement Learning with Verifiable Temporal Grounding for AI-Generated Video Forensics

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.11201&hl=zh-CN&sa=X&d=15257825607623384579&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoNFtBEzWK-g3xhlyO2VtkqX&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=4&folt=kw-top
**作者**: B Liu, Z Lu, Y Bian, X Zhang, X Shui, Y Huang 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Recent advances in video generation models have significantly improved the realism of synthetic videos, blurring the boundary between generated and authentic content and raising concerns about misinformation. Existing MLLM -based detectors

---

### [108] PRMU: A Corpus-Free Benchmark for Person-Centric Knowledge Unlearning in Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.11149&hl=zh-CN&sa=X&d=10183228378046249354&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoPs0qXP8st7TPyUpGzYGAFT&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=2&folt=kw-top
**作者**: H Chen, Y Lyu, Z Chen, W Tan, C Si, L Guo 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Despite these advances, existing MLLM unlearning benchmarks still differ substantially from … PRMU, a personcentric benchmark for realistic MLLM knowledge unlearning. Since real-… (NKS) filtering procedure using a reference

---

### [109] SPARED: Reasoning-Based AI-Generated Image Detection via Adversarially Edited Data

**链接**: https://arxiv.org/abs/2608.12876
**作者**: Yicheng Bao, Xiahui Guo, Xuhong Wang, Xin Tan
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting AI-generated images is only half the task: a deployed detector must also justify its verdict, yet existing detectors inherit three failure modes from their training data: real and fake images collected from different sources invite provenance shortcuts, supervised explanation corpora teach templated rationales, and a static forgery corpus leaves the decision boundary standing still while generators keep moving. We introduce \methodname{}, an adversarial reinforcement learning framework that pits two heterogeneous models against each other. A diffusion image editor learns to edit real photographs into fake counterparts of those same photographs that fool the current detector, while a reasoning MLLM learns to expose them with a verdict grounded in free-form reasoning. Both rewards are shortcut-proof by design: the attacker is credited only when its edit is faithfully executed, and the defender only when its verdict is correct. As the two models alternate, each round's attacker 

---

### [110] BlindGrid: Diagnosing Efficient Visual Evidence Acquisition and Binding under Local Observation

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3DMjJALedynI&hl=zh-CN&sa=X&d=7028073596473296149&ei=BXh_asb4B9e46rQPzav1KA&scisig=AM1tuoOxqCA3n-iJc1gHfUKsvk4X&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=1&folt=kw-top
**作者**: W Zhang, Z Lu - COLM 2026 Workshop on Efficient Reasoning
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> An image is divided into patches, and an MLLM observes one patch at a time while deciding whether to move, remember partial evidence, or stop and answer. This setting isolates two coupled abilities: actively acquiring relevant evidence and

---

### [111] Cross-Variability Decoding for Motor Imagery EEG Signals: A Comprehensive Review

**链接**: https://scholar.google.com/scholar_url?url=https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2026.1899645/full&hl=zh-CN&sa=X&d=3503714797268319932&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoP4WmPRqw3-lp2ObISH4XlT&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=9&folt=kw-top
**作者**: L Wang, Y Zhou, P Wang, X Ma, S Zhou - Frontiers in Neuroscience
**匹配关键词**: EEG, Brain-Computer Interface, Motor Imagery
**相关性评分**: 9.0
**数据来源**: Google Scholar

**摘要**:

> Motor Imagery-based (MI) Electroencephalography ( EEG ) has emerged as a leading solution in non-invasive Brain-Computer Interface (… To address these challenges, this review presents a comprehensive taxonomy of MI EEG cross-variability

---

### [112] EEG-PRIME: Prototype-Aligned Representation Learning with Multi-Level Conditioning for EEG Decoding

**链接**: https://arxiv.org/abs/2608.13072
**作者**: Shuailei Zhang, Muyun Jiang, Wei Zhang, Jinbo Chen, Zhiwei Guo, Yong Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: EEG, BCI, EEG Foundation Model, Motor Imagery
**相关性评分**: 8.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) decoding models often generalize poorly across datasets and subjects due to domain shifts in acquisition protocols and individual neurophysiology. We propose EEG-PRIME, a two-stage EEG foundation model for cross-dataset multi-task decoding. EEG-PRIME combines masked pretraining with prototype-aligned instruction tuning to enable instruction-aware and subject-invariant decoding across diverse BCI paradigms. During pretraining, an EEG encoder learns transferable representations through masked reconstruction with frequency-cutoff spectral augmentation. During instruction tuning, EEG-PRIME incorporates task-semantic, dataset-specific, and subject-invariant conditioning. The resulting conditioning signal modulates the Q-Former through Layer-wise Query Modulation, while frozen text embeddings of class labels serve as prototypes for cosine-similarity-based prediction across heterogeneous label spaces. Experiments on sixteen datasets covering motor imagery, emotion

---

### [113] EEG Decoding Using CNN and LSTM Network

**链接**: https://arxiv.org/abs/2608.13285
**作者**: Athanasios Karagounis
**来源**: cs.LG cs.HC
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motor imagery (MI) brain--computer interfaces (BCIs) have emerged as a promising approach for establishing flexible communication pathways between the human brain and external devices , particularly for individuals affected by stroke or neurodegenerative disorders. Reliable decoding of motor-imagery electroencephalography (MI-EEG) remains challenging because EEG recordings contain substantial noise and exhibit complex, weakly informative relationships with the underlying brain activity. Although deep learning provides an effective means of learning representations directly from EEG signals, its application to MI-EEG feature learning remains comparatively limited. This study introduces a hybrid deep-learning architecture that integrates a convolutional neural network (CNN) with a bidirectional long short-term memory (bi-LSTM) network. The CNN is used to learn high-level spatial and temporal representations directly from raw MI-EEG recordings, whereas the bi-LSTM models temporal dependen

---

### [114] Cueless EEG imagined speech for subject identification: dataset and benchmarks

**链接**: https://arxiv.org/abs/2501.09700
**作者**: Ali Derakhshesh, Zahra Dehghanian, Reza Ebrahimpour, Hamid R. Rabiee
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] Comparative evaluation of tabular-to-image deep learning pipelines for EEG -based epileptic seizure recognition: A comprehensive benchmark with statistical analysis …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0010482526004609&hl=zh-CN&sa=X&d=18313916979835084151&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoNkeIs5shNT1FMwI_5j8zBf&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=5&folt=kw-top
**作者**: ME Sönmez - Computers in Biology and Medicine, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> electroencephalography ( EEG ), yet the manual review on which this diagnosis depends remains slow, subjective, and inconsistent across readers. A rapidly expanding literature reframes EEG … , and five-class tasks from the Bonn EEG

---

### [116] Identifying EEG biomarkers of fatigue and brain fog in long COVID: insights from rest and movement-related brain activity

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0967586826003814&hl=zh-CN&sa=X&d=11660624311629554089&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoMcGvoYjEcsnyyNoRzJPBw0&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=4&folt=kw-top
**作者**: MC Sánchez, KM Fajardo, S Long, T Janaudis-Ferreira… - Journal of Clinical …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background Fatigue and brain fog are among the most reported symptoms in Long COVID (LC), yet their underlying neural mechanisms remain unclear. In this context, we aimed to identify neural correlates associated with LC symptoms. Methods

---

### [117] Subject-Aware Multi-Granularity Alignment for Zero-Shot EEG-to-Image Retrieval

**链接**: https://arxiv.org/abs/2604.17782
**作者**: Lin Jiang, Qingshan She, Jiale Xu, Haiqi Xu, Duanpo Wu, Zhenzhong Kuang
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] A Subject-Wise Computational Framework for Classifying Questionnaire-Derived Dark Triad Profiles from Task-Onset EEG : Comparing Handcrafted, ROCKET, and …

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2673-9909/6/8/131&hl=zh-CN&sa=X&d=5029481474030748400&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoOUdXayP_W_FEDVrttrIq1B&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=7&folt=kw-top
**作者**: D Mizrahi, I Zuckerman, I Laufer - AppliedMath, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> -onset EEG while explicitly accounting for the methodological constraints of low-subject EEG classification. Specifically, we compare three EEG … More broadly, the study examines whether transient task-evoked EEG responses contain consistent

---

### [119] Spatio-Temporal Spiking Transformer for Epileptic Seizure Detection on EEG Signals

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11628149/&hl=zh-CN&sa=X&d=15313667568740753690&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoPAgQZtuAGP4nz_amKdmNJR&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=8&folt=kw-top
**作者**: HN Cao, TV Vu, HTM Tran, KTD Phan - … Conference on Applying New Technology in …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> from long-term electroencephalogram ( EEG ) monitoring remains a clinically significant challenge, demanding high sensitivity and … segments from scalp long-term electroencephalogram ( EEG ) recordings. We evaluated on the CHB-MIT Scalp EEG

---

### [120] Retrospective study with long-term clinical follow-up of a cohort of patients with benign epileptiform variants on EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2173580826001367&hl=zh-CN&sa=X&d=17841369320983194663&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoMZK2ZPTrNTamt353NErbWg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=6&folt=kw-top
**作者**: RAS Díaz, SB Cuéllar, JG de la Aleja Tejera… - Neurología (English Edition), 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Introduction Benign epileptiform variants (BEV) are uncommon epileptiform-like EEG graphoelements that do not meet diagnostic criteria for epileptiform or pathological discharges. The clinical significance of some subtypes remains uncertain. Methods

---

### [121] Exploring the Distinction: Electronic Vs. Ionic in EEG Data Analysis by Digital Signal Processing

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-20291-8_11&hl=zh-CN&sa=X&d=11120663476988019553&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoNbjqNPhzy6yDBFBENNdS0x&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=3&folt=kw-top
**作者**: C Labarthe - IUPESM World Congress on Medical Physics and …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This integrative review examines the advantages of processing brain electrical data as ionic signals, in contrast to the traditional electronic approach to electroencephalography ( EEG ). Ionic signals, which involve charged particles in

---

### [122] Dynamic Cognitive Prior Generation for Robust EEG -to-Image Decoding

**链接**: https://scholar.google.com/scholar_url?url=https://jecir.com/index.php/jecir/article/view/59&hl=zh-CN&sa=X&d=1520858477896259821&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoN987uGm2V6oz4l0NW_xH2a&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=1&folt=kw-top
**作者**: M Ali - Journal of Engineering and Computational Intelligence …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> One of the key challenges in brain computer interfaces (BCIs) is to understand the visual perceptual content (VPC) of non-invasive electroencephalography ( EEG ) signals with high accuracy, without the aid of brain mapping techniques, which is

---

### [123] Composite EEG biomarker modeling and energy–accuracy trade-off analysis for multi-patient seizure detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-65668-1_reference.pdf&hl=zh-CN&sa=X&d=2153269586370571083&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoNsgzNSEd2wRD1j-4MwD95-&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=2&folt=kw-top
**作者**: GS Jebaraj, K Elango - Scientific Reports, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Reliable cross-patient seizure detection remains challenging because EEG characteristics vary considerably between patients. To address this problem, we proposed a compact composite feature termed the Seizure Intensity Index (SII)

---

### [124] Deep Learning for Ear- EEG -Based Brain–Computer Interface: A Systematic Comparison and Design Insights

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2079-6374/16/8/437&hl=zh-CN&sa=X&d=504773351760084644&ei=BHh_asOoNq6W6rQPh-7hyQU&scisig=AM1tuoNaFZGBQcrBDkCeLHuKlNtq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=0&folt=kw-top
**作者**: JS Kim, SI Choi, HJ Hwang, CH Han - Biosensors, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this study, we retrospectively analyze the ear- EEG dataset of a previous study in … - EEG , which were adapted to ear- EEG and evaluated under an identical validation framework. To the best of our knowledge, this is the first systematic

---

### [125] Personalized Scorer Modeling: A Learning-Based Framework for Deriving Robust Sleep Stage Labels from Multiple Experts

**链接**: https://arxiv.org/abs/2608.12446
**作者**: Seyyed Ali Hoseini, Javad Baseri, Hamid Saadatfar, Edris Hoseini Gol, AmirHossein Eshghi
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sleep stage classification is important for the diagnosis and management of sleep disorders, yet most automatic staging studies evaluate models against a single reference hypnogram despite known inter-scorer variability. This study investigates whether multi-scored datasets can be used to construct more reliable reference labels from the collective behavior of multiple experts. We use the publicly available DOD-H and DOD-O datasets. EEG (C3-M2) and chin EMG signals were segmented into 30-s epochs, and 30 features were extracted from each modality, yielding 60 features for EEG+EMG. We propose a learning-based hypnogram (LBH) that models the stage-specific behavior of each scorer using confusion matrices derived from machine-learning models. After column normalization, these matrices estimate the probability of each true sleep stage given each scorer's label; probabilities are aggregated across scorers to assign the final label for each epoch. LBH was evaluated with random forest, suppor

---

### [126] Into the ORBIT for Time Series: Training Regimes for Foundation Models

**链接**: https://arxiv.org/abs/2608.13262
**作者**: Hongjie Xia, Yiding Liu, Yifan Hu, Peiyuan Liu, Zewei Dong
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) have advanced primarily through architectural innovation, while training regimes for large-scale heterogeneous corpora remain under-explored. As a result, pre-training distributions are often poorly controlled with respect to domain imbalance, context requirements, prediction horizons, and missingness. We introduce ORBIT (Omni-Range Bootstrap Incremental Training), a training paradigm that makes this distribution explicit and controllable. ORBIT combines Bootstrap Multi-Level Sampling, which controls dataset exposure and samples records, target variables, context windows, and prediction horizons, with Omni-Range Incremental Training, which varies context lengths and prediction horizons throughout a single training stage. Under ORBIT, we train Falcon-2.0, a simple univariate encoder-only Transformer with missingness-aware triple-channel patch tokenization and parallel patch prediction. We further introduce Rank-Guided Cross-Depth Alignment, a traini

---

### [127] How Good are Foundation Models in Longitudinal MRI Disease Progression Reasoning?

**链接**: https://arxiv.org/abs/2608.13309
**作者**: Wafa Al Ghallabi, Ritesh Thawkar, Sara Ghaboura, Omkar Thawakar, Numan Saeed, Dana Al Nuaimi 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Magnetic Resonance Imaging (MRI) interpretation is fundamental to clinical decision-making, requiring radiologists to integrate multi-view anatomical planes across sequential timepoints while precisely localizing interval changes. However, existing vision-language benchmarks remain confined to single-timepoint, single-view interpretation, failing to capture the temporal-spatial reasoning essential to radiologic practice. We introduce the Time-Aware Multi-View MRI Benchmark, an evaluation framework unifying multi-view anatomical input, temporal reasoning across longitudinal scans, and structured localization guidance. The benchmark comprises 3,920 expert-verified question-answer pairs derived from 890 patients across over 3,200 longitudinal MRI timepoints, drawn from seven clinical cohorts covering glioblastoma, neurodegeneration, vestibular schwannoma, and brain metastases, in open-ended, multiple-choice, and binary formats, requiring models to identify anatomical regions of maximal ch

---

### [128] SAFE-SVD: Sensitivity-Aware Fidelity-Enforcing SVD for Physics Foundation Models

**链接**: https://arxiv.org/abs/2605.17985
**作者**: Chengjie Hong, Feixiang He, Yiheng Zeng, Lulu Kang, He Wang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] SpaRRTa: A Synthetic Benchmark for Evaluating Spatial Intelligence in Visual Foundation Models

**链接**: https://arxiv.org/abs/2601.11729
**作者**: Turhan Can Kargin, Wojciech Jasi\'nski, Adam Pardyl, Bartosz Zieli\'nski, Marcin Przewi\k{e}\'zlikowski
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] A Distributional Robustness Margin For Pathology Foundation Models

**链接**: https://arxiv.org/abs/2607.25497
**作者**: Cl\'ement Grisi, Jeroen van der Laak, Geert Litjens
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] StarEmbed: Benchmarking Time Series Foundation Models on Astronomical Observations of Variable Stars

**链接**: https://arxiv.org/abs/2510.06200
**作者**: Weijian Li, Hong-Yu Chen, Nabeel Rehemtulla, Ved G. Shah, Dongho Kim, Dennis Wu 等 (9 人)
**来源**: astro-ph.SR astro-ph.IM cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] LoRA-based Adaptation Alone Is Not Enough: Understanding the Limits of Foundation Models for Face Presentation Attack Detection

**链接**: https://arxiv.org/abs/2608.09633
**作者**: Peter Lorenz, Anjith George and Marcel S\'ebastien
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] Pathryoshka: Compressing Pathology Foundation Models via Multi-Teacher Knowledge Distillation with Nested Embeddings

**链接**: https://arxiv.org/abs/2511.23204
**作者**: Christian Grashei, Christian Brechenmacher, Rao Muhammad Umer, Jingsong Liu, Carsten Marr, Peter J. Sch\"uffler 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Foundation models for movement data: Are they ready for prime-time?

**链接**: https://arxiv.org/abs/2608.13316
**作者**: Alexander Br\"auer, Benjamin Cauchi and Nils Strodthoff
**来源**: eess.SP cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models (FMs) trained on large-scale accelerometer data have been proposed as general-purpose feature extractors for health monitoring, but systematic evidence of their advantages is lacking. We present the first comprehensive evaluation of four open-source accelerometer FMs against supervised baselines covering 19 tasks across the domains of activity recognition including activities of daily living, clinical monitoring, and physiological inference. We find task-dependent performance results: supervised models remain competitive with FMs on human action recognition (HAR), with no consistent advantage for either, while selected FMs lead on fall and stress detection and are the most robust to sensor-placement variation. As frozen feature extractors, FMs are strongest for demographic inference, whereas sleep staging performance remains near chance level for all models. The internal FM representations show strong similarity across layers, highlighting potential for future FM impr

---

### [135] P2Fusion: Prompt-based Progressive Infrared-Visible Image Fusion via Dual-Prior Distillation

**链接**: https://arxiv.org/abs/2608.13045
**作者**: Yi Shi, Huichao Xie, Yuqing Wang, Mingyu Wang, Kaihui Yang, Yu Liu 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Infrared-visible image fusion (IVIF) is pivotal for multimodal perception, yet reconciling the inherent information disparity between thermal and textural features remains a fundamental challenge. Existing prior-guided methods often rely on static constraints that induce optimization conflicts or utilize extrinsic semantic priors from large-scale foundation models (e.g., CLIP/DINO), which frequently fail to exploit the intrinsic modality characteristics essential for high-fidelity fusion. To address these issues, we propose P2Fusion, a prior-guided distillation-based framework that reformulates IVIF via dual intrinsic prompts. Instead of imposing hard-coded penalties, we distill image-intrinsic priors, thermal saliency and spatial quality, into learnable dynamic regulators. Specifically, a Teach-to-Fuse mechanism provides dual-granularity progressive guidance, coupled with a Gated Dynamic Expert Recalibration (GDER) module for decoupled feature refinement. This design enables the netwo

---

### [136] GS$^{2}$CI: Robust Gaussian Splatting For Snapshot Compressive Imaging via Large Vision Model Priors

**链接**: https://arxiv.org/abs/2608.13502
**作者**: Yanming Yang, Chenxi Song, Ping Wang, Xin Yuan, Chi Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Snapshot Compressive Imaging (SCI) offers an efficient solution for high-speed video acquisition and, under exposure-time camera--scene relative motion, multi-view scene capture by compressing temporal or spatial information into a single 2D measurement. While recent studies have explored SCI for 3D scene reconstruction, existing methods struggle with significant challenges due to information loss, limited viewpoint diversity, and the computational burden of jointly optimizing 3D representations and camera poses. In this work, we propose a novel framework that reconstructs high-quality 3D scenes from a single SCI measurement by leveraging 3D Gaussian Splatting (3DGS) and the powerful priors of large-scale vision foundation models (VFMs). Our primary reconstruction combines measurement-derived 3D VFM initialization with SCI-aware Gaussian optimization. After coarse-stage convergence, an auxiliary 2D VFM provides pseudo-view supervision at synthesized viewpoints for local appearance refi

---

### [137] Towards Context-Aware Clinical Motion Understanding in Daily Living at Home: Freezing of Gait Detection with Egocentric Vision

**链接**: https://arxiv.org/abs/2608.13283
**作者**: Vayalet Stefanova, Diwas Lamsal, Margot Genbrugge, Maxim Yudayev, Christian Schlenstedt, Moran Gilat 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding motion in daily living requires context beyond kinematics, because similar inertial patterns during activities of daily living (ADLs) can reflect intentional stopping, object interaction, or pathological movement impairment. Egocentric vision provides task-related context that may help disambiguate these cases. We investigate this challenge through freezing of gait (FOG) detection in Parkinson's disease (PD), a symptom strongly influenced by contextual factors during ADLs. Using synchronized egocentric video, wearable IMUs, and expert-annotated FOG labels collected from 13 PD participants in their homes, we evaluate frozen representations from pretrained ego-video and time-series foundation models, alongside an IMU-based TCN trained from scratch, under leave-one-subject-out evaluation. The IMU-based TCN achieved the strongest event-detection performance, reaching 42.3 F1 and 83.0 AUROC, compared with 32.6 F1 and 77.2 AUROC for V-JEPA2 ego-video features. Although ego-vide

---

### [138] OmniScientist: An Omni-Modal Omni-Discipline AI Scientist

**链接**: https://arxiv.org/abs/2608.13558
**作者**: Bobo Li, Hao Fei, Tianjie Ju, Mong-Li Lee, Wynne Hsu
**来源**: cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in foundation models have enabled AI scientists to automate increasingly complete research workflows, from hypothesis generation and code execution to manuscript preparation. Yet workflow coverage alone does not provide access to the full evidence on which scientific discovery depends. Existing systems typically reason over text, code, labels, or precomputed summaries, leaving scientifically decisive spatial, temporal, cross-channel, and procedural relations unavailable to the agent. We introduce OmniScientist, an end-to-end, omni-modal AI scientist that conducts multidisciplinary research directly from heterogeneous raw evidence. A perception layer and 3 autonomous agents for ideation, experiment, and writeup operate within a deterministic pipeline, allowing observations to shape research questions, experimental decisions, and final claims throughout the research lifecycle. By running idea, rigour, and claim checks in code, the system enforces novelty screening, statis

---

### [139] Intern-S2-Preview: Scientific Agentic Foundation Model

**链接**: https://arxiv.org/abs/2608.13505
**作者**: Lei Bai, Jiaqi Cao, Chiyu Chen, Guanzhou Chen, Kai Chen, Guangran Cheng 等 (10 人)
**来源**: cs.LG cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific discovery increasingly requires AI systems that can reason over scientific evidence of heterogeneous modalities, interact with scientific tools and environments, and sustain progress across long task horizons. We present Intern-S2-Preview, a series of scientific agentic foundation models designed to support multimodal scientific understanding, reasoning, generation, and long-horizon tasks. The training pipeline begins with scientific multimodal pre-training over rendered scientific documents, interleaved image-text data, and diverse scientific corpora. Starting from the pretrained checkpoint, we apply a unified post-training pipeline consisting of supervised fine-tuning, scalable multi-task reinforcement learning (RL), black- and white-box agentic RL, and on-policy distillation. This pipeline is supported by practical techniques that improve rollout and training stability and efficiency, including partial rollout with off-policy correction, adaptive length regularization, on

---

### [140] A Controlled Study of Self-Supervised Image and Video Pretraining under Limited Resources

**链接**: https://arxiv.org/abs/2608.13183
**作者**: Brun\'o B. Englert, Gijs Dubbelman
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual foundation models are a cornerstone of image and video understanding but typically require large amounts of data and computation. The current scale required for pretraining visual foundation models may be unsustainable or unnecessary, and significant benefits arise when effective models can be obtained with fewer resources. To better understand how self-supervised learning (SSL) objectives behave under resource constraints, we conduct a controlled study of image and video SSL objectives under matched data, architecture, and compute budgets. We compare contrastive, reconstruction, feature-prediction, and diffusion objectives and evaluate both standalone and jointly trained image-video SSL formulations across a diverse set of image and video understanding tasks. Our results show that DINOv2-style pretraining consistently provides the strongest overall performance under limited resources. Furthermore, combining DINOv2 with video SSL objectives such as VideoMAE substantially improve

---

### [141] Evaluation of Clinically Steerable Retinal Image Generation from Foundation Model Latent Spaces

**链接**: https://arxiv.org/abs/2608.13455
**作者**: Zuzanna A. Wakefield-Sk\'orniewska and Bart{\l}omiej W. Papie\.z
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical foundation models learn latent representations of clinically meaningful phenotypes, yet their ability to support controllable image generation remains largely unexplored. We evaluate four retinal foundation models within the representation tokenizer framework and examine whether demographic and clinical information encoded in latent representations from foundation models is preserved during synthetic image generation. We show that generated representations and images faithfully inherit phenotype information when evaluated within their originating foundation models, consistently outperforming conventional latent diffusion on multiple downstream prediction tasks. However, these gains largely disappear when evaluated using classifiers trained on real images, revealing a previously uncharacterised synthetic-to-real representation gap. These findings demonstrate that foundation-model latent spaces provide a powerful substrate for controllable retinal synthesis while highlighting the

---

### [142] CardioState-JEPA: Delay-Aware Cross-Modal Learning of a Shared Cardiac Representation

**链接**: https://arxiv.org/abs/2608.12944
**作者**: Hamza Shafiq, Hung Manh Pham, Bin Zhu, Pan Zhou, Jun Hu, Aaqib Saeed
**来源**: cs.LG eess.IV stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electrocardiography (ECG), photoplethysmography (PPG), and phonocardiography (PCG) provide complementary views of the same cardiac cycle, yet existing cardiac foundation models are trained for a single sensing modality, leaving the shared physiology across sensors unexploited. We introduce CardioState-JEPA, a cardiac foundation model to learn a single shared representation jointly across ECG, PPG, and PCG, built on a physiology-aware joint-embedding predictive architecture. The model maps heterogeneous waveforms into a common token space, processes them with a single shared Transformer encoder, and learns by predicting masked latent cardiac states, placing the pretraining target on shared physiology rather than sensor-specific waveform appearance. To handle the temporal offsets between electrical, mechanical, and hemodynamic events, cross-modal prediction uses a learned delay aligner that matches signals at the corresponding cardiac time. Because synchronized multi-sensor recordings ar

---

### [143] Balanced Adaptive Prototype Selection for Scalable TabPFN Inference on Large-Scale Tabular Data

**链接**: https://arxiv.org/abs/2608.12989
**作者**: Mahboobe Jadid, Melika Rezaye Garkani, and Ali Mousavi
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained tabular foundation models have demonstrated strong predictive capability; however, their application to large-scale datasets remains constrained by the limited inference context. This paper introduces Balanced Adaptive Prototype Selection (BAPS), a framework for constructing compact, information-preserving contexts for scalable TabPFN inference. Without modifying or retraining the pretrained model, BAPS jointly preserves representative structure, informative decision boundaries, local density, class balance, and feature-space diversity. Experiments on the million-row HIGGS and SUSY datasets show that 512 prototypes retain strong predictive performance and reliable calibration, corresponding to an approximately 1,953-fold context compression. All experiments were conducted on an Intel Core i7 CPU with 16 GB RAM and no GPU acceleration. These findings establish effective context construction as a practical mechanism for extending pretrained tabular foundation models to million

---
