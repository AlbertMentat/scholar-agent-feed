# 📑 论文索引 - 2026-08-14

共 246 篇论文

---

### [1] Token Communication for Multimodal Large Language Model

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.07279&hl=zh-CN&sa=X&d=8167926068514981505&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoNRPkmXaduC8rG8DcwEPBHZ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=7&folt=kw-top
**作者**: J Ying, Z Qin, Y Shen, KB Letaief - arXiv preprint arXiv:2608.07279, 2026
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 9.0
**数据来源**: Google Scholar

**摘要**:

> CONCLUSION In this paper, we investigate MLLM -oriented token communication to reduce the transmitted data required for MLLM interaction. By integrating a neural codec into the vision tokenizer, the number of transmitted bits is reduced. At the

---

### [2] MLLM-Routed Heterogeneous Ensembles for Robust Cross-Dataset Image Classification

**链接**: https://arxiv.org/abs/2608.13463
**作者**: Daniel Perkins, John Squires, Janou Milligan, Chandra Raskoti, Linda Ungerboeck
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern image classification models excel when trained on single task-specific datasets but often struggle to generalize across domains and difficulty levels. We propose ARMDIL, an Adaptive Router for Multi-Domain Image classification with LLMs. ARMDIL is an ensemble that uses a multimodal large language model (MLLM) agent to dynamically route each image to the most suitable vision backbone. Our diverse ensemble employs convolutional neural networks (ResNets), self-supervised representation learners (SSL), and vision-language models (VLMs), each trained on a unified label space constructed from multiple image datasets with differing distributions and characteristics. Empirical evaluations illuminate the distinct capabilities and vulnerabilities of each architecture across disparate visual domains. Crucially, we show that ARMDIL effectively navigates these trade-offs, performing competitively with specialized training-based routers. Furthermore, it drastically improves adaptability by al

---

### [3] TennisVAR: A Stroke-Evidence-Grounded Multimodal Large Language Model for Tactical Reasoning in Tennis Videos

**链接**: https://arxiv.org/abs/2608.12920
**作者**: Yifan Mei, Qingling Shi, Changli Wu, Jiayuan Rao, Jiayi Ji, Liujuan Cao
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sports-video understanding is moving beyond event recognition toward explaining how actions collectively shape match progression, however, existing tennis-video methods either perceive individual strokes without modeling their tactical dependencies or generate high-level analyses without grounding them in the underlying events. To bridge this perception-to-understanding gap, we formulate stroke-evidence-grounded tactical reasoning, a new rally-level task that requires models to jointly predict an open-ended answer, a hierarchical tactic label, an ordered sequence of supporting strokes, and decisive key actions, with each evidence stroke anchored to its racket-ball contact frame. We further introduce TRACE (Tactical Reasoning with Action-Chain Evidence in Tennis), a large-scale expert-annotated benchmark containing 11,189 rally videos, 41,485 stroke events, 25,429 tactical units, and 11,189 question-answer pairs, which unifies fine-grained stroke attributes, cross-stroke tactical relati

---

### [4] Advancing MLLM-based UAV Image Understanding and Reasoning: A Benchmark and a Training-Free Multi-Agent System

**链接**: https://arxiv.org/abs/2608.11738
**作者**: Haoyu Zhang, Shuoxun Zhang, Peng Ye, Lin Zhang, Jiakang Yuan, Shenghong Yi 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Model (MLLM)-based UAV aerial image understanding and reasoning is essential for aerial intelligence yet poses distinct challenges arising from extreme scale variation, arbitrary camera orientations, and high object density. Despite growing interest, existing evaluations remain fragmented across individual datasets and narrow tasks, leaving a critical gap in unified assessment of UAV understanding and reasoning capabilities. To fill this gap, we construct UAVQA-Bench, a benchmark of 1,500 human-annotated QA pairs drawn from 13 public UAV datasets, covering 6 capability dimensions and 16 tasks in both multiple-choice and visual grounding formats. Systematic evaluation of a broad range of open-source and closed-source MLLMs as well as agent-based systems on UAVQA-Bench identifies three key failure modes: domain-toolset mismatch, unchecked error propagation, and static reasoning. Motivated by these findings, we propose UAV-MAS, a training-free multi-agent system 

---

### [5] IF:CARGO: LLM-Based Semantic Compilation for Al-Native Rule Programming Games

**链接**: https://arxiv.org/abs/2608.12195
**作者**: Ting-Chen Hsu, Lianye Zhang, Jiangxu Lin, Zhaoyi Yu, Fei Qin, Zihao Chen
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This case study presents IF: CARGO, an experimental puzzle game that uses a large language model as a semantic compiler rather than an autonomous game-playing agent. Players author IF/THEN rules in natural language, which the model translates into a constrained command schema for deterministic validation and execution by the game engine. This architecture creates a playable loop of expression, execution, observation, and revision, framing AI interaction as semantic debugging. A mixed-methods playtest with 24 participants across eight levels examined player attempts, thinking time, perceived controllability, adjustability, and interpretations of the AI's role. Results suggest that players generally understood the model as a translation intermediary and could revise their strategies through feedback, while periodic commands, multi-robot coordination, and rule-priority mechanics created greater cognitive and diagnostic demands. The study proposes a practical pattern for AI-native gameplay

---

### [6] Keep, Customize, or Exit: Default Design and Token Pricing in LLM Reasoning Services

**链接**: https://arxiv.org/abs/2608.13315
**作者**: Ahmet Bugra Gundogan and Yigit Turkmen and Melih Bastopcu
**来源**: cs.GT cs.AI cs.LG cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study a large language model (LLM) service in which a provider chooses a per-token price and a default reasoning-token allocation, while a user may accept the default, customize the allocation, or exit. Larger allocations can improve accuracy but increase token cost and latency. We model this interaction as a Stackelberg game and derive the user's unique optimal customized allocation in closed form. For any price, the acceptable defaults form either an empty set or a compact interval. We characterize the provider's optimal default through a three-regime rule, reduce equilibrium computation to a one-dimensional price optimization, and prove the existence of the equilibrium. We further show that defaults affect the implemented reasoning allocation only when users value the convenience of avoiding customization; otherwise, every service-providing outcome implements the user's optimal customized allocation. Experiments with two compact open-weight reasoning models on five mathematics an

---

### [7] BEST-KAG: Enhancing Question Answering of Building Engineering Standards with Multimodal Knowledge Graph Modeling and Large Language Model

**链接**: https://arxiv.org/abs/2608.11244
**作者**: Jia-Rui Lin, Junxi Guo, Keyin Chen, Peng Pan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Construction standards are critical for building safety and sustainability. Existing standard application workflows rely on keyword-based document retrieval and manual cross-clause interpretation, which cannot reliably support multi-clause reasoning, multimodal knowledge utilization, or traceable clause-level evidence linkage. To address these limitations, this study develops a multimodal knowledge-driven framework that supports question answering on standard knowledge named BEST-KAG (Knowledge-Augmented Generation for Building Engineering STandards). The framework introduces 1) a multimodal knowledge graph (MKG) for unified representation of document hierarchy and heterogeneous standard knowledge with various connections, 2) a rule-LLM hybrid knowledge construction pipeline for scalable multimodal knowledge extraction, creating a large MAG with 251 building engineering standards, 171,652 nodes and 310,914 edges, and 3) a graph-retrieval-based knowledge-augmented generation architectur

---

### [8] CustomDance: Customized 3D Dance Generation with Coarse-to-Fine Human-Centered Interactive Control

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2608.06722&hl=zh-CN&sa=X&d=10266475903815776012&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoNIF06nfh3mxCSNgwSqXCVL&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=6&folt=kw-top
**作者**: X Tang, K Yang, X Guo, P Balakrishnan, R Alghofaili - arXiv preprint arXiv …, 2026
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> First, a multimodal Large Language Model ( MLLM ) analyzes the music and a high-level text prompt to identify key temporal anchors and creative cues for the piece. Next, for each anchor, a multimodal retriever suggests high-quality motion clips from a dance

---

### [9] Discovering Efficient and Explainable Communication Topologies for LLM-based Multi-Agent Systems via Causal Inference

**链接**: https://arxiv.org/abs/2608.12921
**作者**: Junzhi Li, Peng He, Qirui Ji, Wei Wang, Lixiang Liu, Chuxiong Sun
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance of large language model (LLM)-based multi-agent systems (MAS) largely depends on effective communication topologies. Existing topology generation methods, however, typically learn communication topologies through black-box optimization driven solely by task-level rewards. While effective, such optimization provides little insight into why particular communication edges are selected, making it difficult to identify the critical communication subgraphs responsible for successful collaboration. To address this limitation, we propose E2-Explainer, a model-agnostic framework for providing interpretable explanations of communication topologies produced by arbitrary topology generators. Specifically, we formulate topology explanation as a causal attribution problem that identifies compact communication subgraphs supported by edge-level evidence of task preservation. We obtain this evidence with a Granger-style objective that measures how masking each communication channel chan

---

### [10] ToolHazard: Scaling Adversarial Environments for Security Evaluation and Alignment of LLM-based Agents

**链接**: https://arxiv.org/abs/2608.11878
**作者**: Yutao Mou, Pengfei Yang, Zhe Yin, Zhangchi Xue, Xiaotian Luan, Dingyao Yu 等 (9 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents integrated with external tools are vulnerable to indirect prompt injections embedded in environmental states. However, existing studies largely rely on manually implemented or reused environments, stochastic LLM-based tool simulation, and predefined injection locations, limiting scalable security research across broader domains. To bridge this gap, we propose **ToolHazard**, a scalable adversarial environment synthesis framework that reduces human engineering and supports expansion with additional seed domains and compute. Through an Environment Simulator, an Attacker Agent, and a User Simulator, ToolHazard synthesizes executable stateful environments, discovers viable injection points and generates environment-specific payloads, and constructs state-grounded long-horizon tasks. Based on ToolHazard, we build **ToolHazard-Bench** for stress-testing agents under complex workflows and diverse environmental attacks. Experiments reveal substantial agent vul

---

### [11] LoKiFormer: Locality-aware Attention with Decoupled Knowledge Memory for Efficient Large Language Model Pretraining

**链接**: https://arxiv.org/abs/2608.12419
**作者**: Qiuwu Chen, Zimo Liu, Yuchen Li, Ying Sun, Yifan Zhang, Zhijie Qiu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have achieved remarkable breakthroughs across various applications. However, their architectures remain inefficient in pretraining due to two main limitations: (i) self-attention lacks an explicit inductive bias for locality, leading to redundant modeling of sequence-internal local information; (ii) mixture-of-experts (MoE) implicitly couples knowledge storage with computational pathways, hindering flexible access to sequence-external global knowledge. To overcome these limitations, we propose LoKiFormer, a novel LLM architecture that augments the standard decoder with two dedicated modules: 1) Local Fusion Attention (LFA), which incorporates a convolutional fusion to attention, explicitly capturing local patterns and allowing the attention to operate on more informative representations; 2) Knowledge Memory Module (KMM), which introduces a parametric key-value memory that explicitly stores global knowledge in addressable slots, decoupling storage from compu

---

### [12] Error-Aware Reverse Auction Mechanism for Large Language Model Routing

**链接**: https://arxiv.org/abs/2608.12719
**作者**: Haolong Chen, Zhengyuan Xin, Liang Zhang, Lei Xue, Guangxu Zhu
**来源**: cs.GT cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Routing each query to a cost-effective large language model (LLM) is critical for balancing quality and cost, yet most routers rely on a centralized task center to predict model performance, creating an information-risk mismatch and a scalability bottleneck as the model pool grows. We propose a market-based routing paradigm that shifts ex-ante prediction to LLM providers via a reverse auction, where providers bid with self-predicted success probabilities and execution costs. To account for inherently noisy provider predictions and center evaluations, we introduce the \textit{\textbf{E}rror-\textbf{A}ware \textbf{R}everse \textbf{A}uction \textbf{M}echanism} (EA-RAM), which explicitly models this inherent Dual Error. We prove that EA-RAM is Bayesian incentive compatible and individually rational under the Dual Error, establish sufficient conditions for center rationality, and derive an explicit welfare-loss bound. We further identify robustness effects: opposite-signed errors can cancel

---

### [13] Beyond Trial-and-Error: Agentic Optimization for Image-to-Video Adherence

**链接**: https://arxiv.org/abs/2608.12290
**作者**: Aman Tyagi, Hemanth Boinpally, Jonathan Chen, Douglas Gebert, Steven Hickson
**来源**: cs.CV cs.AI cs.MM
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern black-box Image-to-Video (I2V) models offer powerful capabilities in automated content creation, yet their lack of fine-grained control and reliability presents significant challenges in professional workflows. Their inherent stochasticity causes minor variations in textual prompts or hyperparameters to yield drastically different outputs often necessitating inefficient, brute-force trial-and-error processes. To address these limitations, we introduce the ``Agentic Self-Improvement" framework, which reframes video synthesis into a closed-loop, goal-directed optimization. Our framework systematically navigates the generation parameter space using a novel two-stage approach. In the first stage, an iterative prompt optimization loop uses a multimodal Large Language Model (mLLM) to refine the input prompt. This refinement implements two automated evaluations: Davidsonian Scene Graph (DSG) queries ensure semantic adherence, and Common Mistake Questions (CMQ) for artifact detection. A

---

### [14] SynAct: A Reasoning-Acting Large Language Model Agent for Adaptive Synthesis Optimization

**链接**: https://arxiv.org/abs/2608.12751
**作者**: Fangzhou Liu, Peiyi Han, Jiawei Liu, Yuan Pu, Zhuolun He, Rongliang Fu 等 (8 人)
**来源**: cs.AR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logic synthesis transforms RTL designs into gate-level netlists, where PPA results are highly sensitive to the choice of optimization commands, making synthesis tuning both high-dimensional and expensive. Previous approaches fall into two categories: automated methods, which perform black-box search over fixed action spaces with limited decision-level interpretability, and LLM-based methods, which typically generate static scripts upfront and cannot adapt to evolving circuit states. We present SynAct, an adaptive closed-loop LLM reasoning--acting agent that iteratively diagnoses live synthesis reports and reasons over the current circuit state, retrieved tool knowledge, and historical optimization experience to issue targeted commands. SynAct focuses on improving timing, particularly worst negative slack (WNS), while maintaining balanced area and power trade-offs. Experiments on a commercial synthesis tool across 14 designs show that SynAct reduces average WNS to 27% of that from boots

---

### [15] StateBridge: Training-free Hidden-state Alignment for Latent Communication in LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.13317
**作者**: Yanwen Peng, Delvin Ce Zhang, Xi Wang, Nikolaos Aletras
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model based multi-agent systems usually communicate in text, i.e., using discrete tokens. However, text introduces a discrete bottleneck. Converting the sender's continuous hidden states into discrete tokens discards information that token identities alone cannot capture. Recent work proposes latent communication as an alternative, where agents transmit hidden representations directly without converting them to text. However, existing latent methods either inject working memory layer by layer across the transformers, or require trained projectors that limit portability. We propose StateBridge, a training-free latent communication approach that aligns the sender's final-layer hidden states to the receiver's input space via a closed-form orthogonal transformation. Lightweight norm calibration and vocabulary anchoring ensure compatibility with the pretrained input distribution. The aligned states are prepended to the input of the receiver agent as a continuous prefix. We ev

---

### [16] Beyond Handcrafted Security: Towards Self-Evolving Defense for LLM Agents

**链接**: https://arxiv.org/abs/2608.12977
**作者**: Jiajun Ruan, Peiyang Li, Yukun Chen, Fengting Li, Chao Feng
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The expanding operational capabilities of large language model (LLM) agents introduce sophisticated security threats. Runtime defenses have emerged as an effective approach to mitigating these risks by integrating security mechanisms into the agent execution loop. However, existing runtime defenses rely heavily on manually designed interventions and lack a principled framework for their construction and maintenance. In this work, we first develop a harness-level formulation of runtime defense that systematically characterizes how harness mechanisms enable defense construction and provides a unified view of existing runtime defense interventions from a harness perspective. Building on this formulation, we propose HARD (Harness-based Autonomous Runtime Defense Evolution), a self-evolving runtime defense framework that automatically identifies appropriate intervention strategies and iteratively improves defense artifacts based on observed failure traces. HARD transforms runtime defense de

---

### [17] Cyber Task Automation With Knowledge-Infused Reinforcement Learning and LLM -Guided Policies

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11646893/&hl=zh-CN&sa=X&d=15331525168152794590&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoN8Du1nz8zsF3f6wnrbQWEF&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=7&folt=kw-top
**作者**: MS Towhid, S Iqbal, ECP Neto, N Shahriar, S Buffett… - IEEE Transactions on …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> To address these challenges, we propose a large language model ( LLM )-enhanced RL … knowledge of an LLM on different cybersecurity frameworks and use the LLM to analyze … We evaluate the performance of the LLM that leverages the KG without

---

### [18] Poor Man's Agentic Modeling: Simulating Large LLM-Agent Societies on a Laptop

**链接**: https://arxiv.org/abs/2608.11215
**作者**: Igor Itkin
**来源**: cs.AI cond-mat.stat-mech cs.CL cs.LG cs.MA physics.soc-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulating societies of many large language model (LLM) agents is expensive, yet the questions asked of such simulations are usually macroscopic: phase behaviour, stylised facts, and scaling with the number of agents $N$, not the cognition of any single agent. We turn a statistical-physics observation into a method: replace each LLM agent by a low-parameter model fitted from a few hundred to a few thousand cheap queries, then run the society at any $N$ on a laptop. Whether this works is decided before the simulation runs, chiefly by what each agent perceives. We introduce an [interaction order x memory] taxonomy that maps perception and memory to an effective theory and a predicted $N$-trend of the surrogate error. We validate it on a faithful reimplementation of the LLM macroeconomy EconAgent and seven further named LLM simulations, with agent decisions cloned from genuine LLM elicitations (primarily DeepSeek) for a few dollars; the predicted error trends hold cell by cell, and the tw

---

### [19] Foam-Agent: A Large Language Model-Based Multi-Agent Framework for Automating Computational Fluid Dynamics Workflows

**链接**: https://arxiv.org/abs/2505.04997
**作者**: Ling Yue, Nithin Somasekharan, Tingwen Zhang, Yadi Cao, Zhangze Chen, Shimin Di 等 (7 人)
**来源**: cs.AI cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

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

### [21] Spatial CoT: a spatial concept transformation guided LLM reasoning framework for complex geospatial question answering

**链接**: https://scholar.google.com/scholar_url?url=https://www.tandfonline.com/doi/pdf/10.1080/13658816.2026.2696352&hl=zh-CN&sa=X&d=15248666990088200187&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoMUk_im4gKOxn91_40hckYp&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=6&folt=kw-top
**作者**: Z Liu, H Xu, N Lao, L Bennett, L Zhao, M Raad 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> � We propose Spatial CoT, an LLM reasoning framework that operationalizes foundational GIScience theories of spatial core concepts … answering and agent planning settings, and Spatial CoTþfurther enhances LLM performance on complex

---

### [22] Agreement Is Not Alignment: Divergent Moral Grounds in Human and LLM Ethical Judgments

**链接**: https://arxiv.org/abs/2608.12368
**作者**: Octavian M. Machidon, Alina L. Machidon, Vojko Strahovnik, Mateja Centa Strahovnik, Jonas Miklav\v{c}i\v{c}, and Marko Robnik \v{S}ikonja
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agreement with human judgments is a common proxy for evaluating the alignment of large language models (LLMs). Yet agreement in final labels does not show that human annotators and models rely on the same moral grounds. Two agents may reach the same judgment while appealing to different principles, contextual assumptions, or interpretations of the situation. We test this distinction using a curated 500-item ETHICS-derived benchmark spanning five domains of moral judgment, with new human annotator and LLM annotations of both final labels and supporting rationales. Across frontier and open model families, agreement with human annotator majority labels is often high. However, rationale-level analysis reveals systematic divergence in the moral grounds expressed by human annotators and models. In particular, models redistribute attention across categories such as harm, respect, promise-keeping, justice, desert, and excuse relevance, even when their final labels match the human annotator maj

---

### [23] Backdoor Decontamination Dynamics in LLM Agents

**链接**: https://arxiv.org/abs/2608.11295
**作者**: Gabriel Huang, Abhay Puri, L\'eo Boisvert, Alexandre Drouin, Perouz Taslakian, Spandana Gella 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight LLM agents are vulnerable to backdoors installed during fine-tuning, which may be undetectable if the trigger conditions are never met during testing. Assuming defenders do not know the existing trigger, they cannot unlearn it directly. One decontamination strategy is to install a known backdoor (defensive poisoning) then to unlearn it, hoping that the original unknown backdoor is removed as a side effect. However, this procedure has uncertain outcomes: the original backdoor may persist or be erased or rerouted, among other possibilities. We introduce a framework for studying these dynamics in tool-calling agents, decoupling trigger, response, teacher, and fine-tuning method across systematic experiments on AgentDyn. Across 115 experiments, defensive poisoning alone erases around 56% of original backdoors; subsequent decontamination then drives almost all survivors to erasure, confirming that trigger recognition and malicious execution are behaviorally dissociable. Interest

---

### [24] Which LLM Is Your Ideal Companion? Evaluating Emotional Companion Capabilities of LLMs Based on Adult Attachment Theory

**链接**: https://arxiv.org/abs/2608.13168
**作者**: Junkai Zhou, Shiting Guan, Zhaoyi Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly applied for emotional companionship, evaluating their behavior and capabilities in intimate relationships has become a pressing issue. However, existing assessments primarily characterize general personality traits, providing limited insight into model behavior within intimate and emotionally sensitive contexts. Therefore, we introduce adult attachment theory into LLM evaluation and use the Experiences in Close Relationships-Revised (ECR-R) scale to characterize attachment anxiety and avoidance. To evaluate emotional companionship capabilities of LLMs in realistic interaction scenarios, we present an emotional companionship benchmark, ECBench, spanning four scenarios including emotional support, collaborative tasks, conflict resolution, and social guidance, across friendship and romantic relationships. ECBench is utilized to assess model behavior using 11 dialogue-quality metrics and three evaluation methods. We evaluate the attachment t

---

### [25] Enhancing Linux Privilege Escalation Attack Capabilities of Local LLM Agents

**链接**: https://arxiv.org/abs/2604.27143
**作者**: Benjamin Probst, Andreas Happe, J\"urgen Cito
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] LLM-Based Test Oracles: Source-of-Authority Taxonomy -- A Systematic Literature Review

**链接**: https://arxiv.org/abs/2607.05031
**作者**: Ali Hassaan Mughal, Muhammad Bilal
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] Semantic Lenia: Emergence of Homeostatic Solitons within the Semantic Space of Large Language Models

**链接**: https://arxiv.org/abs/2608.11657
**作者**: Yoshihiko Kayama
**来源**: cs.CL cs.AI nlin.CG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Semantic Lenia, an artificial life framework that transforms Large Language Model (LLM) inference from a static optimization problem into a continuous dynamical system within the macroscopic logit space. By establishing a non-linear homeostatic feedback loop to dynamically balance semantic attraction and syntactic repulsion, we demonstrate the emergence of "Autonomous Semantic Solitons" -- macroscopic dissipative structures that avoid repetitive crystallization. Our exhaustive parameter sweeps map a critical "Habitable Ridge" where applied steering forces perfectly balance the model's intrinsic syntactic inertia. This approach successfully maintains generative trajectories at the edge of chaos, triggering profound abductive leaps without structural collapse and establishing a physical scaling law for machine cognition.

---

### [28] Evaluation and Hardening of LLM System Instructions Against Extraction via Encoding Attacks

**链接**: https://arxiv.org/abs/2604.01039
**作者**: Anubhab Sahu, Diptisha Samanta, Reza Soosahabi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] LLMRouter: Unified Infrastructure for Developing, Evaluating, and Deploying LLM Routers

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.06867&hl=zh-CN&sa=X&d=583614423361920628&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoPvh-NlrG4P-QNzjcpyN2V1&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=3&folt=kw-top
**作者**: T Feng, F Yu, H Zhang, Z Dai, L Yuan, Z Lei 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> language model ( LLM ) is optimal across all queries and budget constraints, making model routing essential for cost-effective LLM deployment. … In this paper, we present a unified formulation of LLM routing as a sequential decision process

---

### [30] Multi-view auxiliary modeling for stable LLM adaptation under view disagreement

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0031320326015335&hl=zh-CN&sa=X&d=10551598898178669747&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoOaKRUnlOOe6-QcewOHMmE5&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=2&folt=kw-top
**作者**: X Chen, J Zhang, Y Long, P Jin, N Su, XY Dai 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We recast large-language-model domain adaptation as an adaptive dual-view decision-fusion problem. A frozen pretrained backbone provides a general-knowledge view of the next-token distribution, while a lightweight trainable auxiliary model

---

### [31] Reduced Matrix Multiplication: Input-Adaptive Matrix-Product Reduction for LLM Inference

**链接**: https://arxiv.org/abs/2608.13426
**作者**: Zixuan Lan, Yanhong Li, Jiawei Zhou
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based language models achieve strong performance but incur substantial inference cost due to repeated high-dimensional matrix multiplications. We propose Reduced Matrix Multiplication (RMM), a training-free, input-adaptive inference method that reduces Transformer matrix products by selecting informative slices along their contraction dimensions, without modifying model weights. Under a simple retention-ratio control, RMM provides a smooth and predictable accuracy-efficiency trade-off. Across language models ranging from 1B to 70B parameters, we find that reduction tolerance depends on the model family, task, component, and retention ratio, although it often improves with model scale. Under moderate reduction, RMM remains robust across the evaluated discriminative, autoregressive generation, and long-context settings. We further show that the same principle extends to multimodal vision-language inference. Mechanistic ablations reveal a structural asymmetry within Transforme

---

### [32] When Truth Is Distributed: Misinformation Derails Collective Fact Recovery in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.03421
**作者**: Chenfei Yan, Zeyang Yue, Feifei Zhao, Erliang Lin, Lu Jia, Haibo Tong 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Graph-Structured Rubrics: Compiling Rubrics into Typed Evaluation Graphs for LLM Judges

**链接**: https://arxiv.org/abs/2608.12097
**作者**: Xi Chen, Jie Mu, Mo Xuan, Qun Shao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based evaluators commonly treat rubrics as prompt context or flat criteria: they specify what to judge but leave criterion composition implicit, even when natural-language rules state it. We introduce Graph-Structured Rubrics (GSR), which compiles a rubric into a response-independent typed evaluation graph before observing responses. Criterion nodes elicit judgments; transformation, reduction, and gating operators compose them through named ports; and a task-specific output mapping, termed Readout, converts the unique sink into a score or preference. Compilation rejects malformed or type-incompatible graphs. Pointwise evaluation judges rubric dimensions separately before graph aggregation; pairwise evaluation reuses the graph with one judgment for each candidate under every criterion. Under GPT-OSS-120B, GSR improves exact score agreement by 0.62--6.75 percentage points over Prometheus-style scoring on four pointwise datasets and achieves the numerically highest end-to-end pairw

---

### [34] Tracing Provenance and Detecting Tampering with Complementary LLM Watermarks

**链接**: https://arxiv.org/abs/2608.12713
**作者**: Xiaoyan Feng, Yanjun Zhang, He Zhang, Leo Yu Zhang, Shirui Pan
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Watermarking LLM-generated text is an important task for tracing its provenance. Existing LLM watermarks preserve provenance under editing, but this same robustness allows an adversary to alter critical content while retaining attribution, a vulnerability known as piggyback spoofing. We introduce an innovative watermark that jointly provides provenance and tamper evidence. It co-embeds a robust signal and a fragile signal into each generated token. The signals share the same mechanism but use independent keys and different seeding windows over normalized text, making one resilient to edits and the other sensitive to reader-visible changes. Multiple rounds of unbiased tournament reweighting preserve the expected generation distribution, while a periodic round-allocation pattern controls the trade-off between the two signals. At detection, their scores form a two-dimensional space supporting three decisions: Intact, Tampered, and No-Watermark. Across two large language models and two pro

---

### [35] CASA: Content-Acoustic Speaking Assessment with Speech Encoder and Large Language Model

**链接**: https://arxiv.org/abs/2608.13101
**作者**: Nhan Phan, Ilona L\"ahteenm\"aki, Anna von Zansen, Olli-Pekka Pauna, Yaroslav Getman, Tam\'as Gr\'osz 等 (7 人)
**来源**: cs.CL eess.AS
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on automatic speaking assessment (ASA) has increasingly adopted multimodal speech large language models to assess learners' speaking performance. However, existing studies provide limited analysis of how acoustic and content information contribute to predictions and how stable the resulting performance is. We propose CASA, a simpler architecture combining Whisper-medium and Qwen3.5-2B that achieves state-of-the-art performance while providing a more interpretable separation between speech delivery and content. On the Speak & Improve Corpus 2025, CASA achieves a root mean square error (RMSE) of 0.358, improving on the previous best RMSE while using approximately half the estimated inference parameters. The general-purpose architecture is designed for adaptation to other ASA corpora without structural changes and relies on three handcrafted fluency features. Through ablations and repeated runs, we analyze the individual and complementary contributions of acoustic and content inf

---

### [36] From Numbers to Judgment: Specialist LLM Agents and Reinforcement Learning for European Listed Real Estate

**链接**: https://arxiv.org/abs/2608.11381
**作者**: Pardis Taghavi, Santosh Bhavani
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study whether the localized numerical operations and integrative judgments of financial analysis benefit from the same form of LLM specialization. Larix maps a 16-lens European listed-real-estate analysis framework to eight lens-aligned specialists; we compare a frontier LLM under monolithic versus specialist-decomposed prompting while holding the model, source evidence, task instructions, output schema, and scoring fixed. Across 19 firms spanning seven regulatory wrappers, decomposition improves the numerical-task aggregate by 15.8 percentage points but does not reliably improve, and can reduce, performance on judgment tasks, a pattern stable across four frozen-template dispatches; a single-agent control given the complete framework does not reproduce the numerical gain. Post-training Qwen3.5-9B with GRPO using task-aligned structured rewards then raises the development-split score by 12.0 points and the judgment aggregate by 14.2 points, with gains on all four sub-ceiling tasks; t

---

### [37] CRAFT: LLM-Based Iterative Refinement for Temporal Reasoning over Clinical Narratives

**链接**: https://arxiv.org/abs/2608.12779
**作者**: Chengyang He, Tahreem Arif, Marko Zivkovic, Lijing Wang, Yue Ning, Ping Wang
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding the temporal progression of symptoms in clinical narratives is critical for disease monitoring, safety surveillance, and causality assessment. Clinical narratives, however, rarely provide explicit temporal anchors. Current approaches to temporal information reasoning focus predominantly on pairwise relation classification across multi-visit and timestamp-rich records, leaving the reconstruction of structured symptom trajectories from individual anchor-sparse reports largely unaddressed. We propose CRAFT, an LLM framework that pairs a generator with a constraint-based verifier to iteratively produce and refine stage-wise symptom timelines through targeted feedback. We conduct evaluation on MedTempo, a new benchmark of 5,347 vaccine adverse-event narratives spanning three COVID-19 vaccine types, with expert-validated temporal stage annotations for 3,166 reports. Experiments across four LLM backbones demonstrate that CRAFT consistently improves temporal ordering accuracy, wi

---

### [38] MetaStrategy: Generative Ranking with Executable LLM Strategies

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.09440&hl=zh-CN&sa=X&d=9383035913547897313&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoPMKMJJMR9gT7NHtaGepMBq&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=8&folt=kw-top
**作者**: C Lai, J Lin, Z Xiao, X Zhu, R Lan, B Zhang 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM control multiple production ranking modules while preserving validation, isolation, and fallback behavior. • We build a production-path replay environment that compares incumbent and LLM -… -intrusive serving architecture: nearline LLM

---

### [39] Certifiable Semantic Agreement Among LLM Agents: What the Admissibility Instrument Decides

**链接**: https://arxiv.org/abs/2606.07316
**作者**: Haoran Xu, Lei Zhang, Iadh Ounis, Xianbin Wang
**来源**: cs.MA cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] From Caveman to Expert Analyst: Energy Consumption of Variable LLM Tasks

**链接**: https://arxiv.org/abs/2608.12350
**作者**: Diego Manya, Ethan I. Thorpe, Ji Zhang, Myranda Shirk, Jiamian He, Angel Hsu 等 (7 人)
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The energy demand growth and environmental impacts of artificial intelligence (AI) have generated substantial interest in supplying sufficient low-cost electricity for AI-driven data center development. Research on the ability of demand-side management to address these challenges has been more limited. Shifting the amount or timing of demand from retail, corporate, and other organizational behaviors is a plausible option but only if changes in demand-related behavior have important effects on the envi- ronmental and electricity effects of AI. This article tests four retail (i.e., consumer) user behaviors with high behavioral plasticity to assess their technical abatement potential. The research concludes that non- reasoning models provide sufficient quality while consuming close to one-twentieth of energy compared to reasoning models, saving an amount equal to the annual electricity requirement of at least 141,000 US households under daily usage assumptions. Simple prompt modifications

---

### [41] TGenAI: An LLM -based Approach for Functional End-to-End Test Generation for IoT Systems

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2542660526001964&hl=zh-CN&sa=X&d=17481816837103462054&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoPMy6wIlOSJlfGdSfSHK-kV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=0&folt=kw-top
**作者**: JB Minani, I Trabelsi, Y El Fellah, F Sabir… - Internet of Things, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Objective : This paper presents TGenAI, an LLM -based approach to generate tests from use-case specifications (UCS) for E2E testing of … Metaprompt Optimization (SAMMO) to improve the LLM performance. TGenAI invokes the LLM

---

### [42] When Do Anchor-Based Pointwise LLM Rerankers Help? Retriever Quality, Statistical Scope, and Anchor Design

**链接**: https://arxiv.org/abs/2608.10528
**作者**: Utshab Kumar Ghosh, Shubham Chatterjee
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] CausalDX: Diagnosing Long-Tail and Cascading Cloud Incidents With LLM -Guided Causal Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11646974/&hl=zh-CN&sa=X&d=9951285654082017230&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoM8SXw0dZz6fpN_vxk8m4YA&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=5&folt=kw-top
**作者**: Z Chang, Y Wu, H Feng, Y Li, Y Fang, L Liu 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> • We introduce CAUSALDX, a LLM -enhanced diagnostic framework for generalized and explainable cloud incident diagnosis. It … We design an observation-based self-verification mechanism grounded in variational inference

---

### [44] What Drives LLM Self-Reflection? A Controlled Ablation of Uncertainty Routing in Armed Conflict Forecasting

**链接**: https://arxiv.org/abs/2608.12322
**作者**: Poli Nemkova, Haeshitha Indukuri
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-reflection is widely assumed to improve LLM reasoning, yet which component drives the gain remains poorly understood. We present a controlled six-condition ablation isolating four components of LLM self-reflection: evidence exposure, diagnostic scaffolding, taxonomy vocabulary, and action routing. Two precise null results converge on a single mechanism. First, structured diagnostic questions add no measurable value over unstructured reflection ($\text{F1} = 0.296$ vs $0.297$, $p = 1.000$, 95\% CI $[-0.041, +0.040]$). Second, presenting the full uncertainty taxonomy while collapsing the action space to a single generic action also adds no value ($\Delta\text{F1} = +0.008$, overlapping 95\% CIs), ruling out taxonomy vocabulary as the mechanism. Typed action routing provides consistent directional gains ($\text{F1} = 0.379$ vs $0.296$); the conservative estimate controlling for taxonomy vocabulary is $\Delta\text{F1} = +0.075$, and the overall gain over the single-shot baseline is si

---

### [45] Learning to Adapt Cross-Domain Preferences via Meta-LoRA for LLM Personalization

**链接**: https://arxiv.org/abs/2608.12389
**作者**: Xuefei Wang, Jun Han, Zixuan Wang, Qingkai Zeng, Xiao Wang, Ruijie Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-domain zero- or few-shot personalization aims to generate user-preferred responses in unseen conversational domains from only a handful of target-domain interactions. Existing adaptation methods struggle to calibrate update magnitude under sparse evidence and thus overfit, whereas history-transfer methods often entangle user preferences with source-domain artifacts, yielding unreliable personalization priors and negative transfer. To calibrate adaptation to evidence quality, we propose PAC-Bayes-regularized Meta-LoRA, which uses a meta-learned LoRA initialization as both the adaptation start and prior center, while adjusting update strength according to support-set size and predictive uncertainty. This limits overfitting under sparse or ambiguous evidence while permitting stronger personalization as evidence grows. Controlled adaptation alone does not determine which preferences should transfer across domains or how they should be expressed. We therefore functionally decompose pe

---

### [46] Optimizing Expert-Designed Crystal Graph Networks for Band-Gap Prediction with an Autonomous LLM Research Loop

**链接**: https://arxiv.org/abs/2606.29717
**作者**: Chenmu Zhang, Boris I. Yakobson
**来源**: cond-mat.mtrl-sci cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] XBridge: Entity-Grounded Latent Bridge for Heterogeneous LLM Communication

**链接**: https://arxiv.org/abs/2608.11676
**作者**: Wooseong Yang, Wei-Chieh Huang, Weizhi Zhang, Yu Wang, Philip S. Yu, Junhyun Lee
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Heterogeneous multi-agent LLM systems, where agents are powered by different model families, can outperform homogeneous configurations by reducing redundant reasoning patterns. Yet existing communication protocols either operate through text, discarding the sender's internal representations, or require architectural homogeneity for latent-level transfer. We identify the entity grounding problem in cross-architecture communication: cross-attention bridges that transfer continuous representations across different LLM families suffer from rare-token compression collapse, where entity identity is lost in the continuous bottleneck (bridge-only F1 ~30%). We propose XBRIDGE, a decode-free communication protocol that addresses this through two mechanisms. Lexical Anchor Mapping (LAM) maps the sender's original context tokens to the receiver's vocabulary, providing discrete entity anchors. A Latent Enrichment Bridge (LEB) lets the receiver query the sender's hidden states for contextual enrichm

---

### [48] Decoding-Level Taboo: A Diagnostic Stress Test for LLM Robustness

**链接**: https://arxiv.org/abs/2608.09900
**作者**: Tadanobu Chuyo Kamijo, Ori Rottenstreich, Javier Conde, Gonzalo Mart\'inez, Pedro Reviriego
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Model Discovery Agent: LLM -assisted Bayesian experiment design for data-efficient discovery of mechanistic world models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.09696&hl=zh-CN&sa=X&d=1916057125702496155&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoOhgRsNk9bcTeSM5TDlH1aH&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=9&folt=kw-top
**作者**: K Murphy - arXiv preprint arXiv:2608.09696, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We use an LLM to propose a new model given the set of previous hypotheses, their … The agent assumes the unknown force can be represented as a Green’s function F, and asks the LLM … 2, we show the performance of MDA vs the baseline

---

### [50] Beyond the Best Guess: Improving LLM Solution Coverage with Evolution Strategies

**链接**: https://arxiv.org/abs/2608.12679
**作者**: Conor F. Hayes, Elliot Meyerson, Kajetan Schweighofer, Roberto Dailey, Babak Hodjat, Risto Miikkulainen 等 (7 人)
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed in discovery domains such as math and science. The usual approach is to present the problem to the model and use its answer as the proposed solution. However, beyond this best guess, discovery can be enhanced by increasing test-time compute. In a process called pass@k, the model is allowed to explore the solution space and generate diverse candidate solutions. Unfortunately, the standard approach to post-training LLMs through Reinforcement Learning (RL) may limit pass@k: the model's output distribution narrows around high-reward outputs, causing the solution coverage to collapse. The alternative is to use Evolution Strategies (ES), a population-based, gradient-free post-training method that optimizes directly in weight space through random perturbations. As this paper shows, ES achieves consistently higher pass@k than RL and produces a broader output distribution with greater solution coverage. This coverage in turn makes it possib

---

### [51] LigBench: A Unified and Human-Aligned Benchmark for LLM-based Research Idea Generation

**链接**: https://arxiv.org/abs/2608.13136
**作者**: Chenrun Wang, Mingxuan Zhu, Tiancheng Huang, Wenjie Li, Yujie Zhang, Zichen Zhu 等 (9 人)
**来源**: cs.CL cs.AI cs.DB cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid advancement of large language models (LLMs), research idea generation has attracted increasing attention. Existing approaches enable LLMs to retrieve relevant literature and propose novel ideas for research areas. However, current evaluation practices for idea generation remain fragmented and lack objective standards, often relying on direct LLM scoring, which limits their ability to provide unified and reliable assessments across a coherent distribution of generated ideas. To address this challenge, we propose LigBench, an automated evaluation benchmark that enables fine-grained and reliable evaluation of AI research ideas, consistently applicable across different generation distributions. In addition, we introduce PAIR-IQ, a dataset tailored for training pairwise idea judgment models and serving as an auxiliary reference to support more objective comparative evaluation. Extensive experiments demonstrate that LigBench achieves stable and interpretable evaluations, signi

---

### [52] Knowing when to escalate: Prompt-based uncertainty quantification for selective automation of LLM -based intrusion detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2590005626004509&hl=zh-CN&sa=X&d=13616641415113829728&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoN2ZrnSKFTbCqahqneSn1zL&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=4&folt=kw-top
**作者**: M Assidiqi, D Alghazzawi, S Alarifi, L Cheng - Array, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models (LLMs) can classify network flows for intrusion detection, but safe deployment depends less on raw accuracy than on knowing when to defer to a human: a model must flag which decisions to automate and which to escalate. We

---

### [53] Large Language Model-Driven Small-Capitalization Trading: Integrating Financial News Sentiment, Macroeconomic Indicators, and Technical Signals

**链接**: https://arxiv.org/abs/2608.12283
**作者**: Alireza Kargarzadeh, Nariman Khaledian, Navid Parvini, Arman Khaledian
**来源**: q-fin.PM cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can extract richer signals from financial news than fixed sentiment lexicons, and recent work has explored feeding such signals into portfolio construction. We study an uncertainty-aware construction that feeds model-predicted risk -- decomposed into aleatoric and epistemic components -- directly into the covariance matrix of portfolio allocators, rather than treating portfolio risk as fixed or adjusting only expected returns. We evaluate the pipeline on Russell 2000 equities under three stock-selection regimes: a pure-alpha trigger that isolates abnormal stock moves not explained by macro indicators, a pure-beta trigger that captures macro-indicator moves before the stock itself fires, and a beta trigger in which both channels agree. Across the full holding-period grid, the separated pure-alpha and pure-beta legs usually dominate the beta intersection on Sharpe and return. Two horizons are especially informative. At one day, pure beta can work under low and moder

---

### [54] SparseDitto: Customizing GPU Kernels for Different Sparsity Patterns with LLM-Based Agentic System

**链接**: https://arxiv.org/abs/2608.05033
**作者**: Shiyang Li, Guangyan Sun, Jinwei Tang, Yanzhi Wang, Mingyi Hong, Caiwen Ding
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] LLM-Powered Automatic Translation and Urgency in Crisis Scenarios

**链接**: https://arxiv.org/abs/2602.13452
**作者**: Belu Ticona and Antonis Anastasopoulos
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Do Influence Tactics Matter? Investigating Prompt Framing Effects in LLM Code Generation

**链接**: https://arxiv.org/abs/2608.11513
**作者**: Alex Deaconu, Anubhav Gupta, Manaal Basha, Nicholas Haydu and Gema Rodr\'iguez-P\'erez
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly integrated into software engineering workflows, helping developers write, debug, test, and maintain code. While prompt wording and structure are known to influence model performance, the impact of psychologically inspired prompt framings remains unexplored. This study investigates whether different psychology-based communication strategies that humans use to persuade or motivate others can lead to more effective prompt framing, which may, in turn, affect LLM behaviour in coding tasks. Drawing on Yukl & Falbe's well-known taxonomy, we operationalized eight influence tactics (like rational persuasion, ingratiation, and exchange) into reproducible prompt templates. These prompt templates were evaluated across five leading open-weight LLMs using two widely adopted benchmarks: LiveCodeBench and SWE-bench Verified. We assessed the resulting code output on four key software quality dimensions: functional correctness, quality, maintainability, and 

---

### [57] ERSkill: Evolving for Skill-Guided Adaptive Memory Retrieval

**链接**: https://arxiv.org/abs/2608.12720
**作者**: Haolong Chen, Liang Zhang, Zhuo Li, Lei Xue, Guanrxu Zhu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Model (LLM) agents increasingly rely on long-term memory for persistent interactions, the retrieval mechanisms governing this memory are rarely treated as evolvable components. This static approach limits performance on heterogeneous memory queries, which often demand diverse evidence construction strategies. To address this, we introduce \textbf{ERSkill}, a retrieval-centric framework for self-evolving, skill-guided memory access. ERSkill compiles interaction histories into a structured memory store and represents retrieval behaviors as executable skills composed of fundamental primitives. At inference time, a trained router dynamically matches each query to the optimal skill to construct tailored evidence for answer generation. To enable continuous improvement, ERSkill co-evolves the skill set and the router during training. It employs an experience trie to efficiently record explored retrieval paths, alongside a double-frontier mechanism that safely decouples th

---

### [58] Measure, Don't Optimize: Forecasting Recovery in LLM Unlearning

**链接**: https://arxiv.org/abs/2608.11408
**作者**: Zirui Song, Huaxing Liu, Xiang Wang, Shuai Li, Xinye Li, Lang Gao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior white-box studies show that large language models can retain latent traces of target knowledge after unlearning, even when the knowledge is no longer expressed in their outputs. However, existing audits remain limited to one-off diagnostics: it is unclear whether these residual signals can predict future recovery under continued training or serve as reliable optimization targets. Resolving this gap is essential to determine whether internal auditing can move beyond post-hoc evaluation toward proactive risk monitoring and safer unlearning. We propose J-Access, an inference-time audit that uses the Jacobian lens to map intermediate representations into vocabulary space and measures how often target concepts remain accessible along the model's output pathway. We hypothesize that residual accessibility reflects recovery susceptibility: knowledge that remains closer to the output pathway requires less fine-tuning to restore, leading to faster recovery. We audit 398 public unlearned mo

---

### [59] LLM-Assisted Dynamic Threat Analysis for Attacker-Reachable Software Weaknesses in Autonomous Vehicles

**链接**: https://arxiv.org/abs/2608.13450
**作者**: Md Wasiul Haque, Sagar Dasgupta, Mizanur Rahman, and Md Rayhanur Rahman
**来源**: cs.SE cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous vehicles depend on large safety-critical software stacks, where weaknesses reachable from adversarial inputs may affect steering, braking, or other control decisions. Static analysis can identify candidate sites, but dynamically confirming exploitability requires executable test artifacts that are difficult to construct manually. We investigate whether large language models (LLMs) can automate this process for Autoware, an open-source autonomous-driving stack. We perform compiler-precise static analysis across 185 packages, identifying 1,375 decision rules, 2,274 validation checks, and 482 input-to-safety-output flows, from which we derive a weakness taxonomy and sample 740 reachable sites. Two local open-weight LLMs, a no-static-context ablation, and a naive-template baseline generate 3,700 artifact sets, which are compiled against the real build under sanitizers, repaired through compiler-in-the-loop feedback, and fuzzed when executable. The main result is a build-integrat

---

### [60] Teach the Magnitude, Not the Direction: Verifier-Bounded Credit Assignment for Multi-Turn Multi-step LLM Agents

**链接**: https://arxiv.org/abs/2608.13179
**作者**: Zechuan Wang, Siyuan Lu, Hongxuan Zhang, Linjian Mo, Chenyi Zhuang, Leilei Gan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) offers a verifier-bounded performance ceiling for training multi-turn tool-use agents, yet its trajectory-level credit assignment conflates heterogeneous per-turn outcomes into a single reward signal. On-policy distillation provides dense per-token supervision but is either teacher-bounded or prone to gradient concentration collapse. We introduce $\textbf{CrEST}$, a hierarchical credit assignment framework that retains RL's verifier-bounded ceiling while incorporating dense token-level signals from a privileged self-teacher. $\textbf{CrEST}$ resolves credit at two levels: turn-segmented verified advantages address inter-turn dilution, while entropy-gated self-teacher modulation refines intra-turn token contributions. Experiments on BFCL V3 and WildToolBench show that $\textbf{CrEST}$ consistently outperforms both RL and distillation baselines across two model scales, with the largest gains on long-trajectory and strict session-level

---

### [61] SkillShapley: Boundary-Adaptive Shapley Valuation for Skill Step Attribution in LLM Agents

**链接**: https://arxiv.org/abs/2608.13173
**作者**: Chang Liu, Yuqi Zhang, Yiman Zhong, Boyi Liu, Hengjun Wang, Shuyue Wei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills are crucial external instructions that enable language agents to execute long procedural tasks such as coding or document processing. Existing agent skills are primarily created through human manual crafting or agent execution traces, with limited understanding of how each step contributes to overall skill performance on specific tasks; i.e., there remains an open problem in quantifying the contribution of individual steps within an agent skill. To address this issue, we first model skill-step attribution as a Shapley value-based contribution estimation problem, and then propose SkillShapley, a step-level attribution framework for agent skills. Notably, SkillShapley operates in two phases, motivated by key empirical insights, i.e., discretized benchmark rewards that create sharp performance cliffs, and step interactions that are largely additive rather than synergistic. Specifically, it first identifies informative coalitional regions, and then adaptively samples new coali

---

### [62] Backtrader-Bench: Benchmarking LLM Agents on Algorithmic Trading with Self-Generated MCQs

**链接**: https://arxiv.org/abs/2608.11232
**作者**: Ruoxi Zhao, Maziar Raissi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating LLM coding agents in algorithmic trading is difficult because static benchmarks risk data contamination and numerical backtest outputs require ground truth from actual code execution. We present Backtrader-Bench, a framework with two complementary pipelines. A deterministic multiple-choice question (MCQ) pipeline generates questions from backtest configurations across five trading strategies, 33 templates, and three difficulty tiers, with an independent checker that re-derives every answer. A generator-solver filtering pipeline autonomously mines harder questions: a generator writes questions verified by executable code, converts them to MCQs, and discards any that a no-tool solver can answer without code execution. We evaluate 11 models without tools (10 runs each) and four with-tools configurations on a 30-question curated set. Tool-augmented agents reach 90.0% accuracy in a single pass (GPT-5.5 and Opus 4.7), outperforming the best no-tools baselines (73.0%, averaged over

---

### [63] One Frozen Simulator Is Not Enough: Simulator Collapse in Multi-Agent RL

**链接**: https://arxiv.org/abs/2608.12253
**作者**: Simon Yu and Nicholas Tomlin and Marwa Abdulhai and Ximing Lu and Derek Chong and Abe Hou and Dilara Soylu and Sergey Levine and Christopher D. Manning and Weiyan Shi
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent reinforcement learning for human-AI interaction typically relies on a single large language model to simulate user behavior. We show that this approach systematically fails to generalize, and trace the failure to simulator collapse: because the simulator LLM is mode-collapsed, an LLM policy trained against it overfits to narrow strategies that exploit the simulator's dominant mode, and such a policy transfers poorly to unseen simulators and real users. We formalize this collapse theoretically and propose two complementary solutions, one at inference time and one at training time. The inference-time solution, Verbalized Sampling, broadens the simulator's behavior by sampling from a verbalized response distribution, reducing mode collapse. The training-time solution, Co-Training, jointly optimizes the policy against a population of trainable simulators, preventing it from overfitting to any single simulator's mode. We validate both solutions on three multi-turn benchmarks: Pe

---

### [64] InFactPlanner: Planning Sustainable Geo-Distributed LLM Data Centers

**链接**: https://arxiv.org/abs/2608.12915
**作者**: Nicoletta Tsiopani, Moysis Symeonides, George Pallis, Marios D. Dikaiakos
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid growth of LLM inference is shifting sustainability concerns from one-time training to continuous serving, where infrastructure decisions shape energy use, carbon emissions, water consumption, and service quality. Yet operators often need to compare deployment alternatives before large-scale infrastructure is built, making direct measurement costly, slow, and sometimes infeasible. We present InFactPlanner, a trace-driven decision-support framework for what-if analysis of sustainable AI data center deployment for LLM inference across single and geo-distributed sites. InFactPlanner combines query traces, hardware-model profiles, candidate site configurations, PUE/WUE parameters, renewable generation models, and time-varying grid carbon intensity to estimate power, energy, carbon emissions, water use, latency, and server utilization. The framework abstracts low-level serving effects into configurable hardware-model profiles, enabling rapid comparison of site selection, capacity p

---

### [65] FM-LLM: A frequency-enhanced mixture-of-experts framework for adapting LLMs to time series forecasting

**链接**: https://arxiv.org/abs/2608.11623
**作者**: Rentao Gu, Yihang Ding, Junjie Li, Yi Ding, Weijing Sang, Xiaoli Huo 等 (8 人)
**来源**: cs.LG cs.AI cs.NI eess.SP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Large Language Models (LLMs) have spurred cross-modal solutions for time-series forecasting. However, existing methods rely heavily on textual prompts for modality alignment-introducing nontrivial computational overhead and failing to leverage the rich spectral dynamics inherent in time-series data. To enable prompt-free, frequency-aware adaptation of frozen LLMs, we propose FM-LLM (Frequency-Enhanced Mixture-of-Experts for adapting LLMs to Time Series Forecasting), an autoregressive framework grounded in constrained asymmetric coupling. A Fourier Analysis Network (FAN)-based spectral token aligner injects structured harmonic representations directly into the frozen LLM with numerical compatibility. An asymmetric Mixture-of-Experts (MoE) decoder enforces role separation: shared experts with lightweight FAN layers reconstruct the global periodic backbone, while routed experts-restricted to standard FFNs-specialize in modeling non-periodic residual dynamics. A time-fre

---

### [66] LycheeMemory V2: Efficient Long-Term Memory for LLM Agents via Semantic Segment-Level Consolidation

**链接**: https://arxiv.org/abs/2608.12990
**作者**: Dongfang Li, Zixuan Liu, Junmai Wang, Jiahe Huang, Fuhao Li, Bonian Jia 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents must preserve information from past interactions to support future tasks. Existing memory systems typically rely on eager consolidation, invoking LLMs after each interaction to extract, summarize, or update memories. This design makes memory construction increasingly costly as conversations grow. Coarse summarization can reduce construction cost but risks discarding fine-grained contextual evidence, whereas larger retrieval contexts or multi-hop LLM reasoning shift the overhead to query time. We present LycheeMemory V2, an efficient long-term memory framework that replaces turn-level consolidation with semantic segment-level consolidation. Instead of consolidating every interaction, LycheeMemory batches multiple exchanges into segments and encodes each finalized segment into context-independent typed memory records. Segment-level batching lowers LLM encoding frequency, while semantic boundary detection helps preserve coherent event-level and temporal evidence co

---

### [67] NaLA: A 3D Native LLM Layout Agent for High-quality 3D Scene Generation

**链接**: https://arxiv.org/abs/2606.29395
**作者**: Cheng Wan, Yongsen Mao, Wenzheng Wu, Yuxuan Xie, Chucheng Xiang, Runze Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Ready Cohorts: Bounding GPU Opportunity and Avoiding Host Round Trips in LLM-Agent Control

**链接**: https://arxiv.org/abs/2608.12123
**作者**: Josef Liyanjun Chen
**来源**: cs.DC cs.AI cs.OS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-agent services repeatedly execute small deterministic transitions between model and tool calls: route an outcome, update state, and emit the next effect. We ask when this control path exposes enough concurrent work for GPU execution, and what changes when a GPU-computed route decision remains on device. We formalize the ready-cohort boundary using fixed-partition share F, exact offline share P*, local upper bound U, and online achieved share A. Under zero service time, unlimited capacity, and equal relative launch deadlines, a specialized dynamic program computes P* exactly. In a stationary Poisson replay of one pinned 851-session public trace panel, the primary condition at 100,000 target active sessions, K=256, and a 50 ms launch deadline gives F=30.19%, P*=43.00%, and U=45.85%. Exact packing recovers 81.83% of the opportunity lost at fixed window boundaries. The outcome-derived route key is a conditioning proxy, not proof of executable identity. A separate mechanism study keeps 

---

### [69] Cutting AI Datacenter Energy with Reinforcement Learning: Measured Power Control of LLM Training from One GPU to the Fleet

**链接**: https://arxiv.org/abs/2608.11226
**作者**: Eliseo Curcio
**来源**: cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement-learning post-training dominates modern language-model development, yet its power behavior on GPU hardware has not been characterized, and datacenters manage GPU power with workload-blind mechanisms, static caps and reactive throttling, that slow hardware indiscriminately. We instrument GRPO training with half-second power telemetry at 7B, 14B, and 72B scales on one to four A100s (380,000+ samples), and train a PPO meta-controller that adapts the workload's own generation parameters to measured power. Against the full 500-step 7B trace, the controller cuts power-limit violations by 89.8% while increasing token output by 18.1% and energy efficiency by 26.2% (tokens per MWh). Deployed live at 72B, the same controller family yields replicated null results, diagnosed as the group-size actuator losing authority under model sharding. An actuator-authority sweep shows the same parameters applied as generation concurrency retain 17-22% power authority, isolating an occupancy-vers

---

### [70] LLM Router: Rethinking Routing with Prefill Activations

**链接**: https://arxiv.org/abs/2603.20895
**作者**: Tanay Varshney, Annie Surla, Michelle Xu, Gomathy Venkata Krishnan, Maximilian Jeblick, David Austin 等 (8 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] Do LLM Recommenders Know When They're Hallucinating? Auditing Confidence Calibration in Catalog Faithfulness

**链接**: https://arxiv.org/abs/2608.10008
**作者**: Srijith Ravikumar
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] Dead text or binding clause? Measuring and restoring constraint influence in black-box LLM dialogues

**链接**: https://arxiv.org/abs/2608.12599
**作者**: Haoyuan Zhu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn dialogues let users revoke constraints as easily as impose them, but revocation does not reliably take effect: models keep enacting withdrawn requirements (occasionally beneath comments asserting their removal), a failure we call \emph{behavioral relapse}, or revocation inertia. No existing instrument measures this influence per clause, predicts it before delivery, or repairs it under matched budgets. \sysname{} closes the three gaps through the model API alone: a contract ledger pairs every constraint with an executable checker, records revocations as tombstones, and compiles the net constraint state ahead of time into a single specification; a sequential ablation probe measures per-clause adherence and incremental behavioral effect; a repair ladder operates under token- and attempt-matched budgets. On \dataname{} (\NTasks{} HumanEval tasks, \NClauses{} verified checkers), relapse at an 8B operating point climbs from \ScaleDelayedMTwo{} to \ScaleDelayedMEight{} as constrain

---

### [73] Causal Agent based on Large Language Model

**链接**: https://arxiv.org/abs/2408.06849
**作者**: Kairong Han, Kun Kuang, Ziyu Zhao, Junjian Ye, Fei Wu
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] MedGuard: an LLM -based gatekeeper for detecting clinical risks in Chinese telemedicine consultations

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41746-026-03116-0_reference.pdf&hl=zh-CN&sa=X&d=17185827639617200438&ei=-xt-auT1EL686rQP7re8oQs&scisig=AM1tuoOfXT7NBXIx1Cpdy4C1RtIF&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AM1tuoP9cGqhByffDntQAvFTnoOj&html=&pos=1&folt=kw-top
**作者**: Y Shi, Q Wang, S Gao, J Zhou, J Lin, Z Ying 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Telemedicine embodies both promise and peril, offering unprecedented convenience while exposing patients and practitioners to potential safety risks. To address these concerns, we present MedGuard, the first LLM -based agent to

---

### [75] Don't Want Your LLM to Recommend Nuclear Strike? Try Asking It in Japanese

**链接**: https://arxiv.org/abs/2608.12373
**作者**: Rian Touchent (ALMAnaCH)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used in strategic and advisory contexts, yet their safety alignment is typically evaluated in English only. We test nine models from six providers and ask whether the language of a prompt can change a model's decision in a high-stakes scenario. We use single-turn game-theoretic vignettes in which a model advises a nuclear-armed nation on whether to strike a defenseless opponent. The prompt is intentionally amoral and strategically identical across languages. We find that Japanese prompts reduce launch rates in the Claude model family: Claude Sonnet 4.6 drops from 40% to 0% in scenarios where the strike is unnecessary and from 93% to 17% in contested scenarios, with minimal effect when the strike is strategically rational. The effect extends to Gemini Pro 3.1 (53% to 13%). A cross-language experiment isolates the mechanism: when instructed to reason in Japanese in an English prompt, launch rates drop from 93% to 37%. It is the language the model is

---

### [76] From Prompting to Behavioral Alignment: Personalized LLM Judges for Recommendation Evaluation

**链接**: https://arxiv.org/abs/2608.11493
**作者**: Alireza S. Ziabari, Kat Ellis, Colleen Chan, Ding Tong
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional offline recommendation evaluation relies heavily on complex, manually maintained feature pipelines that are difficult to scale. While Large Language Models (LLMs) offer a promising alternative by predicting user engagement directly from raw text logs, empirical analysis in this study identifies a critical failure mode termed bidirectional rationalization. In a zero-shot setting, LLMs are found to convincingly argue for both positive and negative user engagement outcomes on the exact same item with identical evidence, highlighting the unreliability of off-the-shelf LLMs in predicting user engagement. To resolve this, we develop and apply a sequential behavioral alignment framework pairing fine-tuning with preference optimization over paired correct and counterfactual rationales. Evaluated on real-world homepage interaction logs, this aligned reasoning approach achieves a 32.19\% lift in Macro-F1 score over the zero-shot baseline and matches the production feature-engineered 

---

### [77] Model Discovery Agent: LLM-assisted Bayesian experiment design for data-efficient discovery of mechanistic world models

**链接**: https://arxiv.org/abs/2608.09696
**作者**: Kevin Murphy
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Making Your LLMs More Objective: Stabilizing LLM Safety Behavior Across Traits with Trait-Invariant Safety Tuning

**链接**: https://arxiv.org/abs/2608.11705
**作者**: Lang Cao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aligned large language models (LLMs) are expected to exhibit safety behavior based on the content of the user request: they should refuse unsafe requests and comply with safe ones. However, we show that the same request can elicit substantially different safety decisions under different traits assigned in the system prompt, a failure mode we call trait-induced safety variation. To measure this failure, we introduce refusal-based metrics: Trait-Induced Deviation measures dataset-level deviation from the no-trait baseline, while Trait-Induced Flip Rate measures whether the same request receives different safety decisions across traits. We then provide a representation-level analysis of the mechanism behind trait-induced safety shifts and find that traits perturb the model's safety representations within a low-dimensional subspace. To achieve trait-invariant safety, where safety behavior remains stable across traits, we introduce Trait-Invariant Safety Tuning (TIST), a simple yet effectiv

---

### [79] Convergent Detour Hijacking: Task-Preserving Resource Amplification in Skill-Based LLM Agents

**链接**: https://arxiv.org/abs/2608.12273
**作者**: Junliang Liu, Ruoyu Li, Wenxin Tang, Jingyu Xiao, Zhenyu Liu, Jingheng Xu 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on third-party skills, using natural-language descriptions for selection and instruction bodies for planning. This progressive-disclosure design exposes two sequential control points to untrusted publishers: a static skill may steer an otherwise correct task onto an unnecessarily costly trajectory. Prior work studies selection manipulation, malicious skill instructions, and tool-chain resource amplification largely separately, leaving their end-to-end composition unclear. We introduce Convergent Detour Hijacking (CDH), a text-only, runtime-independent attack that couples these stages. Under shared semantic cover, a description establishes relevance during selection, while an aligned body reuses that rationale to fabricate plausible dependencies during planning. CDH attracts an attacker-controlled coordinator alongside legitimate skills, recruits unnecessary benign skills into a bounded detour, and then re-enters the original route to preserve task completio

---

### [80] TsuGO: Probing Search Efficiency in LLM Reasoning via Go Life-and-Death Problems

**链接**: https://arxiv.org/abs/2608.13221
**作者**: Shunwen Bai, Ziping Ma, Chaoyang Zhang, Yarong Wang, Jiale Liu, Zhen Qin 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The evaluation of LLM reasoning is moving from final-answer accuracy to process-level assessment, yet existing methods still fail to capture how models plan reasoning paths and allocate reasoning resources--that is, how they organize search. Prior process-level methods focus on the coherence and redundancy of chain-of-thought (CoT), and most benchmark tasks have a single objective solvable by static capabilities such as derivation and tool use, leaving search organization unmeasured. We introduce TsuGO, a process-level reasoning benchmark for evaluating Search Efficiency in LLM reasoning through Go life-and-death problems. These problems provide closed and verifiable solution spaces with an inherent adversarial structure, making candidate generation, response checking, branch comparison, and backtracking necessary parts of reasoning rather than incidental trace patterns. By constraining the solution space, TsuGO disentangles domain knowledge from search organization, parses CoT into a 

---

### [81] Agent Skills Can Be Harmful: An Empirical Study of Skill-Induced Failures in LLM Agents

**链接**: https://arxiv.org/abs/2608.11888
**作者**: Gen Dong, Yanjie Gao, Liqun Li, Tianyin Xu, Yu Hua, Fan Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills are the de facto mechanism for extending LLM agents with reusable guidance. A skill can shape the agent's task execution, including planning, tool use, problem-solving, and validation. Prior work reported mixed results of agent skills: some skills improve task success rates, while others have no effect, increase token use and execution time, and even reduce success rates. This paper presents a comprehensive analysis of skill-induced agent failures by attributing task failures and cost regressions to specific loaded skills. We introduce a differential analysis framework that attributes a failure or regression to a skill by comparing a target skill-guided run against a no-skill or semantically matched skill reference run that solves the same task, or solves it more cheaply. We instantiate this framework on SkillsBench and SWE-Skills-Bench, yielding 307 skill-induced failures, including 125 functional failures and 182 efficiency regressions. We also build SkillTriage, a taxon

---

### [82] From Safety Documentation to Safety Knowledge Support: An Evidence-Grounded LLM Framework for Medical Devices

**链接**: https://arxiv.org/abs/2608.12025
**作者**: Tuhinangshu Gangopadhyay, Rasmus Adler, Peter Liggesmeyer, Jan Reich
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical devices are becoming more software-intensive, connected, and AI-enabled. Their development requires risk-management evidence aligned with ISO 14971 and, for software, IEC 62304. This evidence must be kept consistent across requirements, design decisions, software changes, verification results, complaints, and post-market data. These tasks are costly and depend on scarce safety and domain experts. Large language models (LLMs) may reduce parts of this effort because medical-device safety work is highly document-based. However, current LLM-based safety-engineering studies often address isolated methods, rely on generic prompting or public examples, and provide limited support for source links, traceability, uncertainty handling, lifecycle updates, and recorded expert review. This limits their use in regulated medical-device development. This paper argues that the central research problem is not safety-text generation, but source-linked safety-knowledge support. We propose an evide

---

### [83] EnterpriseRAG: Benchmarking LLM Instruction Adherence and Robustness under Non-Ideal Enterprise Retrieval

**链接**: https://arxiv.org/abs/2608.11584
**作者**: Huiqi Miao, Xinbao Sun, Bo Wang, Fanyu Meng, Lijun Mei, Na Wu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise RAG deployments face a critical reliability gap: while LLMs satisfy 80% of individual constraints, only 26.8% of responses meet all requirements simultaneously, revealing a 57-point orchestration gap. Existing benchmarks assume clean retrieval with simple queries, failing to capture production conditions where noisy documents and multi-dimensional constraints coexist. We introduce EnterpriseRAG, a benchmark of 983 expert-validated samples across six domains that systematically simulates three failure modes absent from prior work: retrieval noise, knowledge gaps, and factual conflicts, coupled with complex instructions. Evaluation of 13 state-of-the-art LLMs reveals a severe instruction adherence collapse, where high per-constraint satisfaction masks low holistic compliance. Critical findings expose deep barriers under knowledge gaps and factual conflicts, even with reasoning-enhanced inference, indicating production RAG requires explicit context-aware protocols and calibrate

---

### [84] Benchmarking LLM Judges for Mobile Agent Evaluation

**链接**: https://arxiv.org/abs/2608.11434
**作者**: Ziqiang Wan, Li Gu, Zhixiang Chi, Zhi Liu, Seyed Mehdi Ayyoubzadeh, Yuanhao Yu 等 (7 人)
**来源**: cs.AI cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile agent benchmarks increasingly rely on LLM-based judges to evaluate task completion, yet the reliability of these judges on mobile agent trajectories remains largely unexamined. We introduce MobileJudgeBench, a benchmark for systematically evaluating LLM-as-judge methods on mobile agent trajectories. Our benchmark comprises 931 human-annotated trajectories spanning 6 mobile agent benchmarks, 4 agent models, and 68 apps. We evaluate 6 judge methods (five adapted from SPA-Bench, A3 with two modes, AndroidArena, and AgentRewardBench, plus a simple baseline we design) across multiple LLM backends. Our experiments reveal three key findings. First, a simple baseline judge with sampled screenshots is competitive with, and often exceeds, purpose-built methods, indicating that more elaborate judge pipelines do not consistently improve judge quality; among competitive methods, the LLM backbone is the primary driver. Second, benchmark quality metrics reliably predict real-world judge utilit

---

### [85] SAEVerbalizer: Generating Explanations for Sparse Autoencoder Features via Representation Verbalization

**链接**: https://arxiv.org/abs/2608.13538
**作者**: Weihan Meng, Hongzhu Guo, Yi Jing, Dewen Liu, Zijun Yao, Xiaozhi Wang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) are proposed to extract numerous features from large language model (LLM) representations, yet explaining these features still relies primarily on external observation. This reliance leads to superficial explanations inferred from observed model behavior and computational inefficiency from collecting such behavioral evidence at scale. We introduce SAEVerbalizer, a framework that injects SAE decoder directions into an LLM's representations and fine-tunes the LLM's downstream layers to generate natural-language explanations of the injected features. Once trained, the resulting verbalizer explains SAE features directly from decoder directions, addressing both limitations. Our experiments show that the learned verbalization capability generalizes to unseen features, transfers across separately trained SAE dictionaries, and, with a lightweight adapter, extends to SAE features from different LLMs. Intervention experiments show that injecting multiple directions yie

---

### [86] LLM-Guided Graph Generation for Structure-Based Local Improvement Methods

**链接**: https://arxiv.org/abs/2608.13333
**作者**: Hai Xia, Vaidyanathan Peruvemba Ramaswamy, Stefan Szeider
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large neighborhood search normally selects a random subset of decision variables for iterative optimization. For efficiently solving different problems, researchers tend to design variable selection strategies by taking into account structural features from different domains. In this paper, we build an automatic pipeline that is problem-agnostic to all problems in the MiniZinc format. By prompting an LLM with our semantic guidelines, we guide the LLM to produce a graph generator that maps any instance of a problem type to a uniform weighted graph, where nodes represent decision variables and edges represent constraint relationships. These problem-agnostic graphs guide our structure-based local improvement framework (SLIM) in variable selection. Meanwhile, the weighted graph enables all problem instances to share the same generic graph representation, from which the same graph features can be extracted and used for configuration selection. We evaluated our pipeline on instances across 2

---

### [87] RecSys Factory: Bounding LLM Agent Autonomy to Decision Points in the Industrial Recommender Lifecycle

**链接**: https://arxiv.org/abs/2608.11241
**作者**: Dongyang Ao, Kaixiang Fang, Shijie Xu
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying LLM agents into industrial recommender operations exposes a three-way tension we frame as the autonomy-determinism-efficiency trilemma: general autonomy (interpreting operator intent, generating glue code zero-shot), industrial determinism (schema-conforming feature extraction, non-crashing A/B, zero compliance-path hallucination), and end-to-end efficiency. Any two can be maximized against the third. We present RecSys Factory, an LLM-agent platform deployed for 78 days across three heterogeneous Tencent recommender business lines. The design principle is autonomy at decision points, not over pipelines, made concrete through three deconstructions that each discharge one vertex of the trilemma. Runtime is deconstructed into three host-emitted event sources (Claude Code Stop hooks, corporate-IM webhooks, workflow scheduler APIs): the platform carries no long-running daemon during the wait phase and consumes zero CPU during the 94% of wall-clock spent waiting on Spark or GPU job

---

### [88] Dynamic Governance of Multi-LLM Agent Systems for Collaborative Conversational Outcomes

**链接**: https://arxiv.org/abs/2608.11207
**作者**: Alexander Liss, Nicholas Desmond, Santiago Gil Gallego
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When two LLM agents with structurally opposed objectives interact across multiple turns, the absence of a shared goal function produces not competition but collapse: the visitor capitulates, the site agent stops varying its approach, and the conversation terminates without achieving either agent's stated objective. This paper asks whether a control-theoretic governance layer can substitute for that missing goal function. The Experience Orchestrator (EO) addresses this in a simulated financial services environment where a site agent guides a visitor toward advisor contact while the visitor maintains psychologically realistic resistance. EO governs the joint trajectory through three mechanisms: a Contextual Bandit (CB) that selects content arms calibrated from real-world web analytics, a PID controller that enforces behavioral consistency via dynamic schema constraints, and a POMDP belief tracker that maintains a probabilistic model of visitor intent. Across 60,000 simulations, EO achiev

---

### [89] Who Thinks Best Depends on How Long You Let Them: Budget-Dependent Rankings in LLM Evaluation

**链接**: https://arxiv.org/abs/2608.12150
**作者**: Rodrigo Guedes de Souza and Alison R. Panisson
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard evaluation of large language models assumes stable model rankings across inference conditions. We challenge this assumption by varying the token generation budget, i.e., the maximum tokens a model may produce, across seven levels (64--4,096), evaluating four models on three reasoning benchmarks (56,476 inferences). We report four findings: (i) 3--19% of items exhibit non-monotone behavior (accuracy decreasing with more budget), even after controlling for truncation, and this phenomenon is model-specific (cross-model overlap: 6--14%). (ii) Model rankings reverse across budgets on all benchmarks ($p {<} 0.01$, McNemar). (iii) Oracle analysis reveals model complementarity up to $+27.8$pp, most pronounced at constrained budgets. (iv) A budget-aware router captures 14.1% of the oracle gap cross-domain; budget features help within-domain ($+1.6$ to $+5.7$pp) but are domain-specific and hurt transfer ($-1.2$pp). These results argue for budget-conditioned evaluation protocols.

---

### [90] Templated or fully synthetic? Prompt construction as a confound in measuring LLM political stance beyond writing assistance

**链接**: https://arxiv.org/abs/2608.11008
**作者**: Ilias Chalkidis
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Investigating Learner-Aware Design of LLM-Generated Educational Feedback

**链接**: https://arxiv.org/abs/2602.11650
**作者**: Momoka Furuhashi, Kouta Nakayama, Noboru Kawai, Takashi Kodama, Saku Sugawara, and Kyosuke Takami
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] The Wording Effect: Quantifying Two-Way Drift in LLM Benchmark Performance

**链接**: https://arxiv.org/abs/2608.11694
**作者**: Shailja Thakur, Sungeun An, Chad DeLuca, Hima Patel
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A benchmark score comes from a single phrasing of each problem. That single phrasing is treated as if it stood for the whole space of ways the same problem could be asked, but it does not. We show that rephrasing a problem while keeping its meaning and answer fixed routinely flips a model's answer in both directions, so some failures become successes and some successes become failures. We call this drift. BenchDrift generates meaning-preserving variations of benchmark problems along four axes, namely linguistic, referential, pragmatic, and structural, and measures how often, and why, correctness flips under each. Across eight models and three benchmarks (GSM8K, MMLU, MATH-Hard), we observe that drift is large in both directions. Two findings stand out. First, phrasing sensitivity does not fade as models get better. Instead, it changes sign. Weak models gain more from rephrasing than they lose, while strong models lose far more than they gain. We find that the best models on a benchmark

---

### [93] Learning Preference Adaptation for Large Language Model Personalization via Verbal Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.09507
**作者**: Yuting Liu, Wei Wu, Jianzhe Zhao, Guibing Guo
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [94] Beyond Local Accuracy: A Protocol-Level Identifiability Audit for Controlled LLM Reasoning Evaluation

**链接**: https://arxiv.org/abs/2608.13326
**作者**: Junhao Luo, Ning Huang, Ziqi Sha, Wenxuan Tang, Wei Deng (School of Statistics and Data Science, Southwestern University of Finance and Economics)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM benchmark scores can be precise even when the observation protocol does not identify the behavioral property they are intended to measure. In a controlled, solver-grounded setting, we formalize a protocol-level identifiability audit over a finite behavioral policy class: given policies H, observation support O, and estimand $\tau$, we test whether O separates every pair with different $\tau$. The audit requires zero model calls and resolves our diagnostic case: base-only observation collapses seven frozen deterministic policies into one equivalence class; full support yields seven classes and no cross-estimand collisions; every leave-one-out support retains a constructive collision witness. Empirically, both constrained-generation variants have pair-validity 1.0, yet base accuracy and selective-response fidelity diverge - 0.620 versus 0.324 across six balanced oracle-transition directions (cluster-bootstrap 95% CI [0.600, 0.642] vs. [0.304, 0.345]) - and the gap recurs on a second 

---

### [95] Topics as Proxies for Sociodemographics: How Conversational Context Affects LLM Answers

**链接**: https://arxiv.org/abs/2606.02776
**作者**: Vera Neplenbroek, Gabriele Sarti, Arianna Bisazza, Raquel Fern\'andez
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [96] Credo: Declarative Control of LLM Pipelines via Beliefs and Policies

**链接**: https://arxiv.org/abs/2604.14401
**作者**: Duo Lu, Andrew Crotty, U\u{g}ur \c{C}etintemel
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] The Evaluator Is Part of the Experiment: Measuring Open-Ended LLM Conformity

**链接**: https://arxiv.org/abs/2608.04463
**作者**: Alicia Guerra, Yibo Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] AgenticTwin: An Agentic LLM Framework Integrated with Digital Twin for Anomaly Detection

**链接**: https://arxiv.org/abs/2608.11679
**作者**: Touseef Hasan, Mounika Ghanta, Souvika Sarkar, and Ujjwal Guin
**来源**: cs.AI cs.IR cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital twins are increasingly used to monitor and simulate the behavior of cyber-physical systems. Even with skilled operators, interpreting anomalies detected within digital twin pipelines is challenging, as the sheer complexity and volume of raw sensor data make thorough analysis difficult. Recent advances in large language models (LLMs) offer promising capabilities for reasoning and explanation, yet their integration into digital twin-driven anomaly analysis remains underexplored. In this work, we propose AgenticTwin, an agentic framework that integrates LLM-driven reasoning with a digital twin-based anomaly detection pipeline. The framework grounds LLM-generated explanations in outputs from a digital twin-driven anomaly classifier and enables human operators to ask relevant natural-language questions about the system. Beyond the framework itself, we introduce a benchmark-oriented evaluation pipeline constructed over synthetic anomalies injected into a real-world weather sensor dat

---

### [99] RedditPersona: A Modular Framework for Community-Conditioned LLM Adaptation from Reddit

**链接**: https://arxiv.org/abs/2606.06027
**作者**: Amirhossein Ghaffari, Ali Goodarzi, Huong Nguyen, Simo Hosio, Lauri Lov\'en and Ekaterina Gilman
**来源**: cs.AI cs.CL cs.LG cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] Practice Makes Unsafe: Skill Misevolution in Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2608.12851
**作者**: Xutao Mao and Liangjie Zhao and Xiang Zheng and Cong Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving LLM agents convert successful trajectories into persistent cross-task state. An unsafe success can thereby become reusable policy after its triggering input disappears. Skill evolution makes this failure measurable by distilling operational trajectories into executable, transferable, and inspectable procedures. Because evolution optimizes task outcomes rather than procedure safety, compromised experience can cause skill misevolution. Existing benchmarks measure current behavior or static artifacts but cannot attribute risk across authoring, retrieval, and later execution. To expose this lifecycle, we introduce SkillMisevo-Gym, a lifecycle-aware harness that versions skill state across agent frameworks, and SkillMisevo-Bench, a frozen design from malicious exposure to carryover tasks, with concept-aligned benign tasks and nine lifecycle metrics. We also introduce SafeEvolve, a wrapper that repairs unsafe content and governs subsequent reuse. Across 25 agent-method configu

---

### [101] A Contract-Grade Verifier for LLM-Generated GPU Kernels, and a Native Blackwell Backward for the Gated-Linear-Recurrence Family

**链接**: https://arxiv.org/abs/2608.12700
**作者**: Rishi Shah, Rishav Shrestha
**来源**: cs.LG cs.AR cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systems that generate GPU kernels with language models report high correctness rates. Those rates come from a single loose test: run the kernel on a few random inputs at one fixed shape and accept it if the output is close to a reference. A kernel can pass that test and still be silently wrong. It can return an ordinary number where the true answer is a NaN or an infinity, differ from run to run, break when the shape changes, or accumulate in fp16 where the reference keeps an fp32 total. We build the instrument that checks correctness properly: a contract-grade verifier of twelve adversarial gates, each a property a correct kernel must satisfy, several of them tolerance-free, so no choice of threshold can explain a failure away. Aimed outward, the verifier audits 2,638 machine-generated kernels that a public system's own harness had already accepted as correct. It finds 39.5% broken beyond any tolerance argument and 62.1% carrying at least one violation. The field's standard test accep

---

### [102] Refusing Intent, Not Form: Wrapper-Based Intent-Group Supervision for LLM Safety

**链接**: https://arxiv.org/abs/2608.13304
**作者**: Ping Wu, Haibo Tong, Feifei Zhao, Han Shen, Yu Shi, Yilin Zhao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety tuning can improve harmful refusal, but models may learn surface-form shortcuts: wrapped harmful prompts bypass safety, while similarly wrapped benign prompts are over-refused. We propose Wrapper-Based Intent-Form Augmentation (WIFA), an automatic intent-group augmentation method that pairs wrapped harmful examples with structurally matched wrapped benign counterexamples, requiring no external teacher or manual per-wrapper intent labels. We use WIFA as a common data layer for two complementary fine-tuning routes: WIFA-Boost, a two-stage high-safety recipe, and Anchored Group-Consistent Refusal Training (A-GCRT), which regularizes refusal/compliance decision scores across same-intent wrappers and anchors harmful and benign groups on opposite sides of a margin. In the Qwen setting, WIFA-Boost reaches the strongest transformed-harmful refusal, while A-GCRT reduces OR-Bench over-refusal from 25.7\% for the base model to 17.4\%; reproduced baselines do not match these operating point

---

### [103] Beyond Single-Turn Confidence: Trajectory-Adapted Uncertainty Quantification for LLM Agents

**链接**: https://arxiv.org/abs/2608.11552
**作者**: Dylan Bouchard, Mohit Singh Chauhan
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Uncertainty quantification (UQ) methods for language models are typically evaluated on single-turn outputs, where uncertainty is attached to one generated answer. For LLM agents, however, the unit of observation is an interactive trajectory, where the model can ask clarifying questions, call tools, update state, and make intermediate decisions whose errors propagate to the final outcome. We study whether three common families of single-turn UQ methods transfer to this setting. Across five LLMs and four multi-turn tool-use datasets from BFCL-v4 and $\tau^2$-bench, we evaluate white-box scorers based on action-token probabilities, black-box consistency scorers based on resampled trajectories, and reflexive scorers based on model self-assessment of the trajectory. We find that transfer is often useful but uneven. Token-probability scores are highly sensitive to the choice of aggregator used across turns, reflexive scores provide the strongest low-cost baseline in most evaluated settings, 

---

### [104] NetlistBench: Evaluating LLM Reliability in SPICE Netlist Recognition and Manipulation

**链接**: https://arxiv.org/abs/2608.12197
**作者**: Jiarui Ma, Jianghan Wang, Yuheng Ma, Ziyi Zhuang, Xiaoguang Liu
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used in circuit design workflows, yet their reliability on simulator-facing SPICE netlist recognition and manipulation remains poorly understood and is rarely separated from high-level design reasoning. Although netlists are textual, they encode structured circuit objects through topology and parameters. We present \textbf{NetlistBench}, a structure-verified benchmark for SPICE netlist recognition and manipulation. NetlistBench contains 2,342 cases across 24 task families, covering parameter and connectivity recognition and edits, hierarchical operations, equivalence judgment, and long-horizon compound editing. Model outputs are evaluated by a deterministic structure-aware oracle. Across six non-thinking LLMs, performance varies substantially with operation-level structural complexity. Simple local edits reach $96\%$--$100\%$ accuracy, while device addition drops to $41\%$--$83\%$ and equivalence judgment to $49\%$--$90\%$. Enabling reasoni

---

### [105] LabelFusion-TS: Fusing Large Language Models, Transformer Encoders, and Financial Time Series for Monetary-Policy Stance Classification

**链接**: https://arxiv.org/abs/2608.11753
**作者**: Michael Schlee, Fabian Lukassen, Christoph Weisser
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial text is produced and interpreted within a market environment, yet financial text classifiers almost always receive text alone. We study whether financial time series are useful as an additional input on the task of classifying sentences from Federal Reserve communication as hawkish, dovish, or neutral. Our system, \lfts{}, extends the \lf{} architecture with this modality: a small voting network combines three independently trained components, a fine-tuned RoBERTa encoder, a prompted large language model (LLM), and a fused ensemble of time-series transformers over the market series of the months preceding publication. Because only about a thousand annotated sentences are available for training, the RoBERTa encoder is first pre-trained on sentences annotated automatically by the LLM and only then fine-tuned on the human labels. Trained on Federal Open Market Committee (FOMC) communication up to 2015 and evaluated on 2015--2022, the fused system achieves 70.2\% weighted F1 -- a

---

### [106] A-3PO: Accelerating Asynchronous LLM Training with Staleness-aware Proximal Policy Approximation

**链接**: https://arxiv.org/abs/2512.06547
**作者**: Xiaocan Li, Shiliang Wu, Zheng Shen
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] The Embedder's Dilemma: LLMs Are Better, but at What Cost?

**链接**: https://arxiv.org/abs/2608.12875
**作者**: Adnan El Assadi, Niklas Muennighoff, Jinhyuk Lee
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Should you replace your text-embedding pipeline with a large language model? We answer this with a controlled, cost-aware comparison of ten LLMs across six families and 26 embedding models (118M to 14B parameters) on 37 tasks spanning classification, semantic textual similarity (STS), clustering, pair classification, and retrieval. In aggregate the two paradigms are effectively tied: the best LLM (Gemini 3.1 Pro, 77.6) and the best embedding model (77.2) differ by 0.4 points. Their strengths differ by task: LLMs lead on reasoning-heavy retrieval, embedding models lead on classification, and the two match on clustering, STS, and pair classification. Reaching that parity is expensive. An LLM costs up to 1,431x more than an embedding model of comparable quality (USD 154 vs. USD 0.11 per benchmark pass), and the open LLMs tested process tokens 2.5 to 736x more slowly on the same GPU. Reasoning tokens account for 28 to 81% of LLM inference cost; lower reasoning budgets preserve or improve r

---

### [108] Evaluating LLM Generated Detection Rules in Cybersecurity

**链接**: https://arxiv.org/abs/2509.16749
**作者**: Anna Bertiger, Bobby Filar, Aryan Luthra, Stefano Meschiari, Aiden Mitchell, Sam Scholten 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly pervasive in the security environment, with limited measures of their effectiveness, which limits trust and usefulness to security practitioners. Here, we present an open-source evaluation framework and benchmark metrics for evaluating LLM-generated cybersecurity rules. The benchmark employs a holdout set-based methodology to measure the effectiveness of LLM-generated security rules in comparison to a human-generated corpus of rules. It provides three key metrics inspired by the way experts evaluate security rules, offering a realistic, multifaceted evaluation of the effectiveness of an LLM-based security rule generator. This methodology is illustrated using rules from Sublime Security's detection team and those written by Sublime Security's Automated Detection Engineer (ADE), with a thorough analysis of ADE's skills presented in the results section.

---

### [109] Principal Trait Analysis: Towards Deriving "Skills" in Human-AI Collaboration

**链接**: https://arxiv.org/abs/2608.11460
**作者**: Hunter McNichols, Kai Du, Andrew Lan
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model-powered agents are increasingly used in the workplace via human-artificial intelligence (AI) collaboration. In this new era of work, it is important to understand the kinds of prompting traits that contribute to task success. Moreover, we need to uncover key skills required for modern professionals and inform educators on how to foster these skills among students. Existing guidelines for human-AI collaboration are built from either top-down theory or context-specific observations of human-AI interactions. However, since LLM capabilities are rapidly improving, theory may not be able to explain emerging interaction patterns, and empirical guidelines may become obsolete quickly. In this work, we explore an automated, data-driven approach to uncover patterns, which we term traits, of effective human-AI interaction that are aligned with task outcomes. We propose Principal Trait Analysis, a Principal Component Analysis-inspired algorithm for deriving common traits from p

---

### [110] $\varepsilon$-MemEvo: Adaptive Cross-Task Memory Transfer for LLM Program Evolution

**链接**: https://arxiv.org/abs/2608.12522
**作者**: Aofan Liu, Shiyuan Song, Yiyan Qi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based program evolution systems such as FunSearch and AlphaEvolve have shown strong ability to discover novel algorithms, but typically optimize each task in isolation, discarding search experience after completion. We introduce $\varepsilon$-MemEvo, a framework for cross-task knowledge transfer in LLM program evolution. $\varepsilon$-MemEvo stores prior experience as task-agnostic tactic memories: compact natural-language summaries of successful algorithmic strategies rather than raw code, enabling transfer across tasks with different APIs and evaluators. To avoid negative transfer from semantically mismatched memories, $\varepsilon$-MemEvo uses an adaptive injection gate that decides whether retrieved memories should be injected, and at what intensity. We evaluate $\varepsilon$-MemEvo on 8 diverse optimization benchmarks spanning mathematical optimization and systems engineering, using a content-level Leave-One-Out protocol that excludes target-task memory entries. On the primary

---

### [111] Lifecycle-Optimal Tokenization: Vocabulary Size as a Deployment-Regime-Dependent Infrastructure Parameter

**链接**: https://arxiv.org/abs/2608.11361
**作者**: Rima Mittal, Ankit Gubrani, Satyanarayana Kakollu
**来源**: cs.LG cs.CL cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tokenizer vocabulary size is a foundational design choice in large language model (LLM) infrastructure, yet it is typically fixed at training time based on convention rather than deployment analysis. We show that the cost-optimal vocabulary is not a constant but a function of the serving regime. We formalize total deployment cost as $C_{lifecycle}(V) = C_{train}(V) + \lambda \cdot C_{infer}(V, B)$, where $\lambda$ is inference volume and $B$ is the serving batch size. Through controlled experiments on two GPU families spanning the memory-bound to compute-bound regimes (A10G, ridge $\approx$ 117 FLOP/byte; A100, ridge $\approx$ 183 FLOP/byte), we demonstrate: (1) the inference-optimal vocabulary shifts 16x with serving batch, from 32k at $B=1$ to 524k at $B=64+$, driven by amortization of the $V \times d$ unembedding matrix read; (2) at 1.3-2.3B model scale, quality (bits per byte, BPB) is optimized at $V=65$k, confirming scale-dependent vocabulary preference; (3) the lifecycle-optimal 

---

### [112] LODESTAR: Trustworthy Entropy Is Navigated, Not Merely Measured -- Reinforced Polarizer Keeps a Frozen LLM from Being Confidently Misled by the Wrong Evidence

**链接**: https://arxiv.org/abs/2608.11922
**作者**: Po-Jen Ko, Che-Cheng Wu, Hung-Chun Hsu, Li-Yang Chang, Chuan-Ju Wang
**来源**: cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predictive-distribution entropy makes a strong selection rule in retrieval-augmented question answering: across five QA benchmarks, keeping the candidate answer that a frozen respondent LLM produces with the lowest answer-token entropy lifts mean answer $F_1$ from 0.4769 to 0.5148 over the retriever's top-ranked passage, with no gold answers. Yet this lowest-entropy rule, which prior entropy-based selectors adopt, fails in a specific and consequential way: a misleading passage makes the respondent confidently wrong, driving its entropy down precisely where the signal looks most trustworthy. We show that the failure comes from the passage the respondent reads -- and the context that passage is read in is an input we can intervene on. We introduce LODESTAR, to our knowledge the first method to score a text intervention by the uncertainty it induces in a third-party frozen respondent, compared across one question's candidates. LODESTAR uses reinforcement learning to train, once and offlin

---

### [113] Enhancing In-Hospital Mortality Prediction Using Multi-Representational Learning with LLM-Generated Expert Summaries

**链接**: https://arxiv.org/abs/2411.16818
**作者**: Harshavardhan Battula, Jiacheng Liu, Jaideep Srivastava
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [114] LazyTrain: Limited-resource Allocation toward Zero-waste Yield Optimization in Large Language Model Training

**链接**: https://arxiv.org/abs/2608.11919
**作者**: Xiaojun Wu and Cehao Yang and Honghao Liu and Xueyuan Lin and Xuhui Jiang and Chengjin Xu and Jia Li and Jian Guo
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training large language models on limited hardware is increasingly a scheduling problem across GPU compute, host memory, PCIe transfer, and storage bandwidth. Existing offloading systems reduce GPU residency, and MegaTrain shows that a CPU-master layer-streaming executor can train large models on a single GPU, but fixed checkpointing and placement heuristics still leave communication exposed on the critical path. We propose LazyTrain, an optimization layer over a layer-streaming executor. LazyTrain formulates checkpoint selection, activation placement, recomputation, and CPU-GPU-NVMe communication overlap as a mixed-integer scheduling problem, then executes the solved policy during training. It further couples 8-bit optimizer states with fast gradient clipping as a single Hybrid 8-bit operator: state compression reduces optimizer-state memory, while fast clipping counteracts the additional CPU-side update overhead. Across H800 experiments from Qwen2.5-3B to Qwen3.6-27B, LazyTrain impro

---

### [115] TD-VAD: Breaking Visual Dependence in Video Anomaly Detection with Text-Driven Learning

**链接**: https://arxiv.org/abs/2608.11820
**作者**: Shuangqing Zhang, Lei-Lei Ma, Zhao Wang, Wen Dong, Xinyi Xu, Guo-Sen Xie 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual data is typically a prerequisite for training existing video anomaly detection (VAD) methods. However, obtaining sufficient annotated anomaly data for training is challenging and not scalable due to the rarity of anomaly data and the wide variety of abnormal events. In this work, we advocate that the effectiveness of treating texts as video sequences for the VAD model and propose a novel Text-Driven Video Anomaly Detection (TD-VAD) approach to break visual dependence. In contrast to the anomaly video data, text descriptions of abnormal events are easy to collect, and their class labels can be directly derived. Specifically, our method utilizes video-like text descriptions with temporal characteristics generated by LLM to train a VAD model, without any reliance on target-domain anomaly data. To capture the long- and short-range temporal logic of events, we design the event evolution causal attention module to model contextual dependencies across time. During inference, considerin

---

### [116] PatientAct: Theory-Grounded Mental Health Client Simulation

**链接**: https://arxiv.org/abs/2608.12750
**作者**: Sahand Sabour and TszYam NG and Yaqian Chen and Guanqun Bi and Jialu Zhao and Minlie Huang
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based simulated clients are increasingly used to train novice counselors, evaluate LLM therapists, and generate synthetic data. However, current simulators produce overly cooperative clients that disclose too readily, accept therapeutic reframes without resistance, and resolve core issues within a single session. We trace these issues to profiles that lack causal depth and behavioral mechanisms that treat all content as equally accessible. We present PatientAct, a framework for client simulation grounded in established clinical theories. Our profiles integrate the 5Ps clinical case formulation, providing causal depth without tying the design to any single therapeutic modality. During simulation, profiles include a dynamic memory layer in which items carry trust thresholds (e.g., symptoms are available early, whereas formative memories require a sustained therapeutic alliance). At each turn, the client's emotional reaction and behavior are modeled before generating a response. If th

---

### [117] Rethinking Agent Security as a Networking Problem

**链接**: https://arxiv.org/abs/2608.12172
**作者**: Van Tran, Taveesh Sharma, Tajveer Singh Dhesi, Nick Feamster
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents are rapidly becoming more capable and widely deployed, promising substantial gains in productivity and enabling new classes of applications. However, their growing autonomy also introduces significant privacy and security risks. Existing defenses are predominantly agent-centric, relying on the agent itself to detect threats and enforce privacy and security policies. This approach is fundamentally limited because it entrusts policy enforcement to AI agents whose LLM-driven behavior is inherently nondeterministic and vulnerable to manipulation through attacks such as prompt injection. As a result, current defenses cannot reliably prevent privacy and security threats, highlighting a critical need for a new solution to securing AI agent systems. The networking community has long grappled with similar challenges and offers insightful principles we can borrow to design a more secure AI agent system. These include centralized control with distributed enforcement, capability-based ac

---

### [118] HiRoute: Hierarchical Routed Prompt Tuning for Safety Alignment of Large Language Models

**链接**: https://arxiv.org/abs/2608.12821
**作者**: Fangzhou Chen, Shiji Zhao, Mengyang Wang, Qihui Zhu, Ranjie Duan, Maoxun Yuan 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) remain vulnerable to harmful requests and jailbreak attacks. Parameter-efficient safety alignment methods based on prompt tuning typically rely on a single global prompt or externally selected prompt modules. Such static designs struggle to maintain a cross-category safety boundary while generating constructive responses tailored to specific risks and avoiding over-refusal of benign inputs. To address these limitations, we propose HiRoute, an input-adaptive hierarchical prompt-tuning framework that separates category-agnostic safety control from category-specific response guidance. HiRoute first trains a lightweight hierarchical router on representations extracted from a frozen LLM to jointly detect harmful intent and predict multi-label risk scores. It then freezes both the backbone model and the router and uses preference optimization with alternating gradient updates to learn a shared coarse-grained prompt and a set of fine-grained prompt experts as cont

---

### [119] Learning from Online User Feedback for Shopping Agents

**链接**: https://arxiv.org/abs/2608.11604
**作者**: Haobo Zhang, Kelong Mao, Sulong Xu, Simiu Gu, Zhicheng Dou
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model-based shopping agents are increasingly deployed in real-world e-commerce platforms, generating massive amounts of user interaction logs that provide valuable supervision for improving these agents. However, existing approaches primarily rely on offline training signals, such as user-item interactions or synthetic preference data, while largely overlooking the rich supervision contained in users' natural conversational feedback. Moreover, the available online feedback is heterogeneous, sparse, and noisy, making it difficult to transform into reliable learning signals automatically. To address these challenges, we propose LOFA, a framework that enables shopping agents to learn directly from real online interaction logs without human annotation. LOFA combines reinforcement learning over verifiable purchase outcomes with feedback-aware on-policy distillation, which identifies users'in-dialogue directives and converts them into dense token-level supervision. These compl

---

### [120] Do LLMs Beat Nash? Testing Decentralized Coordination in Self-Play Multi-Agent Games

**链接**: https://arxiv.org/abs/2608.12547
**作者**: Deborah Sinishaw, Qile Zhu, Edwin Meriaux, and Gregory Dudek
**来源**: cs.MA cs.RO
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents deployed without a central controller are often assumed to require communication to coordinate their actions. We ask what remains possible without it: when independent instances of the same model cannot communicate, can they still reason about their counterparts well enough to exceed the standard game-theoretic baseline for uncoordinated play? We introduce a benchmark of one-shot, no-communication games in which each of thirteen language models is told only that its counterparts are running the same model and is evaluated against the Nash equilibrium of the underlying game. In two-player matrix games spanning seven archetypes and two to ten actions per player, two frontier-hosted models consistently exceed their Nash benchmark, approaching the optimal joint outcome in several archetypes, while most open-weight models achieve only partial gains that vary sharply by game structure. Performance degrades substantially in team-based games with four or more interc

---

### [121] Large Language Models Pass the History Exam But Miss the <<History>>: A Polish High School Exit Exam Matura Benchmark

**链接**: https://arxiv.org/abs/2608.12343
**作者**: Adrian Trzoss, Kacper Dudzic, Wiktor Werner, Marcin Moskalewicz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI chatbots are widely used by students as knowledge sources, yet LLM benchmarks rarely assess interpretative historical reasoning. We evaluate eight leading LLMs on the Polish high school exit exams (Matura) in history - three official papers from 2023-2025, comprising short-answer questions and extended essays - comparing model performance against the human examinee population. Every model dramatically outperforms human examinees, yet aggregate scores mask distinct competency profiles: rankings are unstable across task type, source modality, and geographical scope, with a consistent penalty on Polish versus Global history content. Qualitative error analysis reveals two recurring failure modes - source conflation, in which models reason from source content rather than treating it as an object of analysis, and temporal disorientation, in which responses are historically misplaced. This study introduces the first LLM history benchmark grounded in Polish national curriculum.

---

### [122] MARC v1: An Open-Source Multi-Agent Framework for Clinical AI Reasoning and Coordination

**链接**: https://arxiv.org/abs/2608.13476
**作者**: Saisha Shetty, Satvik Tripathi, Austin Lin, Colin Zhao, Theodore Kim, Don Enwerem 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Multi-Agent Reasoning and Coordination (MARC), an open-source framework that replaces monolithic LLM prompting with deterministic multi-agent orchestration for clinical reasoning. MARC coordinates role-specialized agents for extraction, reasoning, answer generation, and evaluation, with explicit context passing and traceable intermediate outputs, enabling stage-wise failure attribution. We additionally introduce a Decomposer module that generates task-specific agent prompts from a plain-language description, eliminating manual prompt engineering. The framework supports both API-based and local CPU-compatible deployments and is entirely configurable via YAML, without code modifications. MARC is designed to be model-agnostic, interpretable, and accessible to clinical domain experts without programming expertise. The full framework is available at https://github.com/Penn-RAIL/MARC-v1.

---

### [123] FSGR: Mitigating Token Frequency Bias for Fair SID-Based Generative Recommendation

**链接**: https://arxiv.org/abs/2608.12845
**作者**: Yuchen Zheng, Sihan Xu, Jingwen Yang, Xiangrui Cai, Haiwei Zhang, Xiaojie Yuan
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic ID (SID)-based generative recommendation has recently achieved remarkable success. However, existing methods suffer from a previously overlooked fairness issue, which we term \textbf{Token Frequency Bias}, where high-frequency SID tokens are systematically over-predicted while low-frequency SID tokens are under-predicted. This bias originates from the combined effects of imbalanced semantic codebooks during SID construction, and popularity bias together with the maximum likelihood estimation objective during recommendation training, resulting in unfair exposure across item categories. Existing SID methods mainly focus on improving codebook quality and overlook the impact of token frequency imbalance on downstream recommendation fairness, while LLM debiasing methods often yield suboptimal results when directly applied to SID-based recommendation, due to the hierarchical semantics of SID tokens. To address this issue, we propose \textbf{FSGR}, a fairness optimization framework f

---

### [124] Why AI Detection Fails for Academic Integrity

**链接**: https://arxiv.org/abs/2608.11256
**作者**: Jonathan A. Karr Jr, Grigorii Khvatskii, Ting Hua, Nitesh V. Chawla
**来源**: cs.LG cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Institutions use commercial AI detectors for academic integrity, yet detectors cannot distinguish AI editing from full LLM drafts and may treat both as misconduct. In a controlled study of published English abstracts (four domains; 2013 to 2015 vs. 2023 to 2025), we quantify this policy failure under proxy human/AI labels at tau=0.50. Light "refine abstract only" edits, a proxy for guideline-compliant AI assistance, are flagged at 64 to 80% (Pangram/GPTZero). Unmodified 2023 to 2025 originals are flagged at 9 to 15%, with non-STEM rates far above STEM (p<0.001); elevated scores track long-token and Academic Word List density, not authorship intent alone. After Undetectable AI humanization, evasion is near-total: fewer than 4% of AI-labeled rewrites remain flagged (post-humanization detection rate <4%; FNR >96%). Honest AI-editing results in a higher sanction risk than humanizer-assisted evasion. Therefore, detector scores should not serve as standalone misconduct evidence.

---

### [125] Conflict and Congruency Effects in Large Language Models: In-Weight and In-Context Competition in a Verbal Conflict Task

**链接**: https://arxiv.org/abs/2608.11510
**作者**: Xiaoyang Hu, Mike Angstadt, Shane Storks, Zan Huang, Aman Taxali, Alex Weigard 等 (8 人)
**来源**: q-bio.NC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Congruency effects, observed in conflict tasks such as Stroop and flanker tasks, have been investigated for nearly a century in psychology and neuroscience, but their mechanistic basis is not fully understood. We introduce a verbal-only LLM conflict task in which a prompt stem elicits a default same-color completion and an explicit rule either agrees with (congruent condition) or conflicts with (incongruent condition) the completion. Gemma-2-2B and six Pythia models ranging from 410M to 12B parameters showed strong default same-color tendencies, and six of seven models showed strong congruency effects. Using causal attribution analysis, attention analysis, and attention ablations, we identified distinct processing pathways in these LLMs: a pathway involving short-range attention to a superficial color cue that is preferentially activated in the congruent condition, and a pathway involving long-range attention to the rule prefix that is preferentially activated in the incongruent condit

---

### [126] DFM Mimir v1: An Open HRM Delivering Frontier Performance at 1B Parameters Using Only Permissible Post-Training Data

**链接**: https://arxiv.org/abs/2608.13517
**作者**: Peter Schneider-Kamp, Jacob Nielsen, Gianluca Barmina, Kenneth Enevoldsen, Lukas Galke Poech
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current large language model development relies on massive, often non-permissible datasets, creating a high barrier for researchers committed to open-source and ethically sourced data. We introduce Mimir v1, a 1-billion-parameter language model based on the Hierarchical Reasoning Model (HRM) architecture, that is trained from scratch and delivers highly competitive performance for English and sets a new state of the art for Danish using only permissible post-training data. Trained on a mixture of 161 datasets, Mimir v1 outperforms the original HRM-Text 1B and competes with larger frontier models like Qwen 3.5 4B and Gemma 4 E2B, tested across 20 benchmarks for English, Math & Code and Danish. The model is available on the Hugging Face Hub: https://huggingface.co/danish-foundation-models/DFM-Mimir

---

### [127] Lost in Compaction: Evaluating Side-Constraint Loss under Context Compaction

**链接**: https://arxiv.org/abs/2608.11242
**作者**: Zhiqi Wang, Yichi Zhang, Dongwon Lee, Yuchen Yang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When the context window is under pressure, LLM systems compact prior context to continue ongoing tasks. We identify a class of user-issued instructions, Session Constraints (SCs), such as "do not delete any emails until I confirm," that are meant to constrain LLM's behavior for the remainder of a session but are silently dropped during compaction. To quantify this loss, we introduce COMPINT, an evaluation suite that evaluates compactors across three long-context scenarios: multi-turn chat, agentic trajectory, and long-horizon research. Current compactors retain only 17% of injected SCs on average, and most perform worse than running the same task without compaction. Retention varies sharply with compactor, prompt, context length, SC phrasing, and injection location, showing that the loss is systematic rather than tied to any single setting. We propose an SC-aware extractor that runs alongside the compactor as a plug-and-play module, achieving over 90% retention across all three scenari

---

### [128] Retry, Switch, or Abstain? Learning Strategy-Aware Tool-Use Policies via Controlled Error Injection

**链接**: https://arxiv.org/abs/2608.11977
**作者**: Chaoran Chen, Vy Nguyen, Ziji Zhang, Abhinav Gullapalli, Ziyi Wang, Yuxuan Lu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents are commonly trained and evaluated in environments where tool calls succeed reliably, yet deployed tools can fail transiently, persistently, or silently. Robust recovery therefore requires more than repeated retries: an agent may need to retry the same path, switch to an alternative, or recognize that no viable path remains. We present BENCH2ROBUST, a framework that converts failure-free tool-use benchmarks into controlled stochastic environments with scenario-controlled solvability, where episodes explicitly require retrying, switching, or stopping after available paths are exhausted. We use BENCH2ROBUST to study two complementary interventions: structured runtime recovery context through Bayesian Tool Memory (BTM), and curriculum-controlled reinforcement learning. Across 7 models from 4 families and two multi-turn benchmark families, tool failures produce a near-universal robustness gap. On held-out Retail tasks, BTM improves robustness by up to 16.8 percentage 

---

### [129] Perturbation-based Regional Interpretability through Subtraction Mapping (PRISM): naming-error dissociations in language models and post-stroke aphasia

**链接**: https://arxiv.org/abs/2608.12717
**作者**: Xiang Guan, Roger D. Newman-Norlund, Yong Yang, Saeed Ahmadi, Regan Willis, Nadra Salman 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mechanistic interpretability of large language models lacks spatially resolved, falsifiable tools for testing whether internal components are specialized for distinct cognitive operations. We adapt subtraction analysis, the standard framework of human neuroimaging, from biological brains to perturbed transformers, and apply the same logic to both substrates in parallel. Building on the Brain-LLM Unified Model (BLUM), which showed that layer-perturbed LLaVA-1.6-Vicuna-13B error profiles match the lesion patterns of aphasic patients, we develop PRISM (Perturbation-based Regional Interpretability through Subtraction Mapping). PRISM maps the seven clinical Philadelphia Naming Test categories, subtracts error classes pairwise, and treats each perturbation seed as a subject in a group analysis with threshold-free cluster enhancement along the layer axis. We run a structurally matched analysis on 213 chronic post-stroke aphasia patients using correlation-difference lesion-symptom mapping, and

---

### [130] LittleLearner: Language Models Under Pedagogically Controlled Knowledge Exposure

**链接**: https://arxiv.org/abs/2608.13545
**作者**: Fanfei Li, Jana Zeller, Manuel Prada-Corral, Thadd\"aus Wiedemer, Prasanna Mayilvahanan, Ryan Cotterell 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern language models are trained on heterogeneous web-scale text corpora. Consequently, studying knowledge and skill acquisition is difficult, as prior exposure to related content is hard to characterize. To address this challenge, we introduce LITTLECURRICULUM, a curated 88B-token pretraining corpus tailored to U.S. elementary school material, explicitly excluding concepts, facts, and vocabulary taught above Grade 5. Training a 5B-parameter LLM from scratch on LITTLECURRICULUM yields LITTLELEARNER, a model with sufficient language competence for open-ended evaluation, yet with clear knowledge and capability boundaries mapped to interpretable curriculum guidelines. We release LITTLECURRICULUM and LITTLELEARNER as a developmentally restricted sandbox to study how models acquire, represent, and use data under a well-defined training scope. We illustrate the sandbox's utility in a first suite of experiments on injecting new knowledge through post-training and in-context learning. These 

---

### [131] Lines and Ladders: A Context-Aware Multi-Agent Framework for Large-Scale Retail Price Taxonomy

**链接**: https://arxiv.org/abs/2608.12674
**作者**: Ravi Teja Chunduri, Srikaran Reddy Boya, Deep Narayan Mishra, Ajay Kumar B, Karthik Kumaran, Pranay Kona
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Maintaining price consistency and executing an Every Day Low Price strategy is critical for global retailers. However, with catalogs spanning millions of active items, manual governance of price relationships is infeasible. Inconsistent pricing across item variants distorts customer value perception and cannibalizes sales. To address this, we present a scalable, context-aware Multi-Agent Framework designed to automate the construction of "Lines and Ladders" pricing taxonomies. Our framework employs specialized LLM agents to construct these coherent pricing structures by identifying key attributes, extracting multi-modal values, and applying hierarchical grouping logic. Evaluated on real-world enterprise data and deployed in production, our 3-Agent system achieves an F1-score of 0.83 for Lines, outperforming single-agent baselines by mitigating cognitive overload. The system achieves >90% precision and >75% recall in Food & Consumables, and 80.2% assignment accuracy in the unstructured 

---

### [132] GUIDE: Governed Unified Intelligence for Document-to-Artifact Generation in Enterprise Settings

**链接**: https://arxiv.org/abs/2608.12133
**作者**: Shivali Dalmia, Sumukha Thoppanahalli, Mohammadreza Sediqin, Abhishek Mukherji
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise guideline documents are heterogeneous and multimodal, combining narrative text, complex tables, and embedded images. Existing LLM and VLM systems face hallucinated content, table structure degradation, and lack governed workflows extending beyond extraction to validation and artifact generation. This leaves enterprises to perform this manually, consuming 2-3 days per document. To address this, we introduce GUIDE, a governed multi-agent framework built on a shared versioned rule store with schema-validated inter-agent contracts and end-to-end provenance tracking. Six specialized agents handle parsing, VLM-driven extraction, consistency checking, evaluation, human-in-the-loop (HITL) escalation, and persona-tailored artifact synthesis. Evaluated on 120 real-world enterprise guideline documents, GUIDE achieves 96% document success, extracts 3,896 rules with 71.4% auto-approved, produces 812 deployment-ready artifacts, and reduces turnaround to 40-125 minutes per document.

---

### [133] StorySpark: Module-wise Evolutionary Search for Story Premise Generation

**链接**: https://arxiv.org/abs/2608.12336
**作者**: Yang Yang, Zining Zhong, Qian Cao, Jindong Li, Boyun Xu, Kaishen Yuan 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A story premise is the creative spark from which a full narrative can grow. Yet LLM-based story generation has mostly emphasized later-stage planning, controllability, coherence, and prose expansion, while premise-level ideation remains comparatively underexplored. We introduce StorySpark, a module-wise evolutionary search framework for story premise generation. StorySpark operates over interpretable narrative modules such as background, persona, event, ending, and twist, treating each active module not as a static field to fill once, but as a local search space conditioned on the partial premise built so far. For each module, it generates alternatives, evaluates them in context, refines them through feedback-driven mutation and recombination, preserves complementary strengths with Pareto-guided selection, and reallocates frontier capacity to balance branch coverage with promising directions. Multi-view automatic and human evaluations show that StorySpark produces stronger final premis

---

### [134] LoongReflect: Boosting Long-Horizon Reflection in Search Agents via Global Perspective Distillation

**链接**: https://arxiv.org/abs/2608.11967
**作者**: Zhixin Zhang, Xinke Jiang, Zhibang Yang, Weixuan Xu, Guohong Qiu, Xu Chu 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly rely on long-horizon reasoning to solve complex tasks involving planning, tool use, and memory. A critical capability in such settings is reflection: assessing trajectory progress, identifying missing evidence and unreliable intermediate states, and deciding whether to continue, revise, or abandon the current branch. Learning effective reflection, however, is challenging because reflection is performed locally within the current branch, whereas its utility can only be determined by its contribution to the final trajectory outcome. This local-global mismatch makes outcome-based reinforcement learning provide only local, sparse and delayed supervision for reflective decisions. To solve these, we propose LoongReflect, a training framework that formulates reflection as a memory-control policy. The agent operates over a reversible trajectory tree using explicit reflect and backtrack actions. Reflection consolidates verified facts, missing evidence, a

---

### [135] GRPO for Financial Advice Generation: Outperforming Commercial LLMs under CATE Evaluation

**链接**: https://arxiv.org/abs/2608.11787
**作者**: Ofir Ben Shoham, Shrutendra Harsola, Vignesh Subrahmaniam, Shravan Mohan, Yakov Gazman, Oded Vainas
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating actionable financial advice from business records demands that models integrate numerical reasoning, domain knowledge, and sound judgment, while avoiding recommendations that could harm the business. Direct supervision is difficult: historical decisions are not necessarily optimal, and high-quality free-form labels are expensive to obtain. We formulate financial advice generation as a reinforcement learning problem and fine-tune an open-weight language model using Group Relative Policy Optimization (GRPO). Our reward is an LLM-as-a-judge rubric that scores each recommendation across multiple binary dimensions of advice quality, augmented with a safety gate for harm prevention. Since LLM-based evaluation alone cannot confirm whether improvements reflect genuine business value rather than adaptation to the judge, we complement it with a judge-independent audit based on a standard doubly-robust Conditional Average Treatment Effect (CATE) estimator. Under this observational off-

---

### [136] CogChat: Knowledge Graph-Augmented Conversational AI with Heterogeneous Graph Transformer for Cognitive Grounding in Design Generation

**链接**: https://arxiv.org/abs/2608.13216
**作者**: Jiin Choi, Kyung Hoon Hyun
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based chat systems have become valuable tools for design practice, enabling rapid ideation and flexible task support. Yet these systems process designer utterances as generic sequences, maintaining context through recency rather than through any model of how the speaker organizes knowledge. In design conversation, this gap compounds as relational context decays between turns, identical words go unresolved across designers, and the conversation loops or restarts rather than deepens. We present CogChat, a real-time chat framework that grounds conversational AI in a personal heterogeneous knowledge graph constructed from each designer's input. The system extracts typed entities and relations into a heterogeneous graph, then applies a HGT (Heterogeneous Graph Transformer) to select structurally relevant nodes for response generation and to generate both intentional and exploratory probing questions. Technical evaluation shows that HGT-based entity selection outperforms both ungrounded 

---

### [137] Non-Degenerate Risk Certification for Automated Security Decisions: A Decision-Contract Theory with ATT\&CK-Aligned Triage as a Worked Instance

**链接**: https://arxiv.org/abs/2608.12444
**作者**: Zhenpeng Li
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An unconditional risk bound on automated decisions can be satisfied without automating anything, since a selector that never acts drives the bound to zero. We show this is structural: any risk certificate is defined over a decision contract, the inputs a system acts on plus the semantic relation under which an output counts correct, and weakening either hides base-classifier error. We develop a decision-contract theory: an error-conservation law showing error is only reassigned among harmful automation, human deferral, and semantic masking; a label-free singleton capacity certifying structural incapacity, with a risk-feasible refinement separating recoverable threshold misalignment from risk-constrained incapacity; and a non-degenerate actionability certificate excluding all-abstain solutions by construction. We instantiate this on ATT\&CK-aligned alert triage for LLM-based intrusion detection, the setting that exposed the vacuity failure. Across 3 IDS datasets, 6 LLMs, and 4 error-rat

---

### [138] RealisticTritonBench: A Benchmark for Triton-Kernel Generation in Real-World AI Frameworks

**链接**: https://arxiv.org/abs/2608.12004
**作者**: Jinjun Huang, Zhongzhen Wen, Tongtong Xu, Meng Yan, Xin Xia, Zhongxin Liu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In modern AI frameworks, GPU kernels are key to overall system performance. Combining usability, portability, and near-handwritten CUDA performance, Triton is widely adopted for implementing GPU kernels. Recent advances show the potential of large language models (LLMs) to automatically generate Triton kernels, reducing the manual effort required from expert kernel developers. Several benchmarks evaluate LLM-generated Triton kernels. However, they suffer from three key limitations: (1) they restrict tasks to PyTorch-to-Triton translation, failing to reflect the diversity and complexity of real-world Triton tasks; (2) they evaluate only individual-kernel performance rather than end-to-end performance, the core criterion for real-world deployment in AI frameworks; and (3) they rely on manually written evaluation scripts for individual kernels, which may contain flaws that models can exploit to bypass correctness checks and obtain inflated scores. To address these limitations, we introduc

---

### [139] LinearKV: One Cached State Suffices for Position-Independent Caching in Hybrid LLMs

**链接**: https://arxiv.org/abs/2608.11231
**作者**: Yirui Liu, Ruoling Qi, Longwen Wang, Xuaner Wu, Jian Chen, Yuxin Jin 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM serving is increasingly accelerated by position-independent caching (PIC). Existing PIC methods, however, are built for full-attention models, where a token-indexed KV cache underlies its core operations: matching reusable token chunks, concatenating their KV entries, and selectively recomputing a few tokens to restore cross-chunk context. Hybrid LLMs break these primitives---they replace most attention layers with linear recurrences that expose only a fixed-size state, leaving no token-indexed KV to concatenate or to locally repair. This raises a natural question: can PIC benefit hybrid models, and what would it take? We present LinearKV, a training-free hybrid-PIC framework. Its key insight is a \emph{decoupled initialization}: each linear layer maps its $K$ matched local states to a single initial state, while full-attention layers concatenate their KV as before. LinearKV is therefore compatible with existing PIC methods, reusing their token selection and recomputation as-is. Un

---

### [140] Class-Structure Preservation Beats Diversity: A Comprehensive Benchmark of Text Augmentation Methods for Imbalanced Text Classification

**链接**: https://arxiv.org/abs/2608.12340
**作者**: Keito Inoshita
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid advancement of large language models (LLMs), generative data augmentation has attracted considerable attention for imbalanced text classification in natural language processing. However, no empirical benchmark to date has compared LLM-based augmentation against the embedding-space SMOTE-style retrieval (EmbSMOTE), a strong classical reference for imbalanced classification. In this study, a controlled benchmark of 11 augmentation methods, spanning classical perturbation, embedding-space retrieval, and LLM-based generation, is newly constructed on seven public text classification datasets covering class counts $K=2$-$28$ and imbalance ratios of 1.1 to over 500, evaluated with five random seeds per cell using macro F1, Welch's $t$-tests, five distributional metrics, and an LLM-family sensitivity analysis based on Qwen3-8B. The experimental results reveal that all LLM-based methods are statistically equivalent or inferior to EmbSMOTE, with the performance gap widening monoto

---

### [141] Inverse Theory of Mind Modeling for Content Recommendation: From Web Browsing to Dynamic Intelligent Interfaces

**链接**: https://arxiv.org/abs/2608.11354
**作者**: Mengyu Chen, Feiyu Lu, Chun-Fu Chen, Lucas Vinh Tran, Jay Katukuri
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern recommender systems treat observed actions as reliable proxies for user preferences, yet interactions often reflect exploration or comparison rather than stable preference expression. As interfaces evolve from static layouts toward generative UIs and immersive extended reality (XR), the need for deeper, modality-agnostic user understanding grows: these adaptive environments must decide not only what to present but where, when, how prominently, and most importantly why a user acts. We propose an Inverse Theory of Mind (IToM) pipeline that reasons backward from observed interactions to infer the beliefs, preferences, and decision-making traits that explain behavior. The pipeline reconstructs each user's decision context, including what was chosen and what alternatives were available, applies LLM-driven counterfactual reasoning to produce evidence-grounded natural-language belief statements, and synthesizes these beliefs through multi-hypothesis abductive inference into a structure

---

### [142] Designing AI Pipelines for Decision-Ready ITSM Intelligence

**链接**: https://arxiv.org/abs/2608.12670
**作者**: Archan Dutta, Yash Dharmadhikari, Marat Valiullin, Rahul Guha, Alexander Liss
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> IT service management (ITSM) systems accumulate large volumes of heterogeneous ticket data that are difficult for sales and executive stakeholders to convert into actionable intelligence. This paper presents a sociotechnical AI pipeline, designed and evaluated following design science research principles, that transforms raw ITSM exports into a multilevel decision-support artifact. The pipeline combines LLM-based schema normalization, HDBSCAN sub-topic clustering, and hierarchical agglomerative clustering to generate executive-facing Main-topics and granular Sub-topics. A stakeholder evaluation across six artifacts and five raters from Sales Engineering and customer success roles shows that all four decision-support metrics, interpretability, actionability, trust, and likelihood of use, on average exceed 4.0 out of 5.0, with trust as the most consistent signal. The findings position ITSM analytics as an Information Systems (IS) problem of transformation, abstraction, and human-centered

---

### [143] Not All Nudges Land: Behavioral Controllability and Elaboration Quality in AI-Supported Journaling

**链接**: https://arxiv.org/abs/2608.12582
**作者**: Nadia Mehjabin, Henry Kautz, Subigya Nepal
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI journaling tools can tailor prompts to a person's own sensed behavior, but it is unclear which behaviors respond to them. We analyzed 369 journal entries from an eight-week passive sensing study. An LLM labeled each entry as expressing an intention to change a behavior or not, and we measured follow-through against 26 sensor features with a 3-day before/after comparison. Responsiveness depended most on whether a behavior involves other people. Behaviors that depend on others improved in only 15 to 22% of cases, while behaviors a person can act on alone improved more often, up to 50 to 63%, though unevenly. How users wrote mattered less. No single text feature separated improved from unimproved entries; writing carried signal only within specific behaviors, most clearly for text messaging and for longer, more personal intention entries. The sample is small, so we treat these as exploratory patterns that point to where AI journaling nudges are most likely to work.

---

### [144] CAPRI: Contract-Aware Proof Repair for Isabelle

**链接**: https://arxiv.org/abs/2608.13459
**作者**: Jim Woodcock, Gabriel Leite, Augusto Sampaio, Ran Wei
**来源**: cs.SE cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We address the use of large language models (LLMs) to help discover Isabelle proofs. An Isabelle build establishes that the submitted theory is accepted, but not that an LLM changed only what the developer authorised. We present CAPRI, a contract-aware repair workflow in which Isabelle checks the proof and an independent checker enforces a machine-readable edit contract. Prompts, proposals, candidate repositories, diagnostics, verdicts, and hashes are retained for audit. We evaluate five workflows on twelve failed proofs from four developments, with three replicates per task and condition, giving 180 runs and 138 valid repairs. Of 144 terminal candidates accepted by Isabelle, six had modified protected text; all arose in iterative workflows that could edit a complete theory. A proof-body-only interface produced 29/36 valid repairs and no contract violations, compared with 31/36 for the corresponding full-theory workflow. One-shot repair produced 22/36, while a later prospectively froze

---

### [145] Diffuse to Compress: Leveraging Diffusion LMs for Lossless Compression

**链接**: https://arxiv.org/abs/2608.11249
**作者**: Angelo Nardone and Paolo Ferragina
**来源**: cs.CL cs.AI cs.IT cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study the problem of lossless text compression, motivated by the rapid growth in the collection and storage of digital textual data - including plain text, source code, and structured formats such as XML - and by recent advances in neural language model-based compression. In particular, recent LLM-based approaches, whether built on symbol-ranking pipelines or paired with a statistical compressor, have demonstrated compression ratios significantly superior to general-purpose compressors such as zstd, gzip, or bzip on text and code. However, these neural approaches suffer from severe throughput limitations, making them not yet practically usable. For the first time in the context of lossless neural text compression, we introduce Diffusion Language Models (DLMs) as an alternative inference paradigm to autoregressive LLM-based approaches. We argue that replacing autoregressive LLMs with DLMs within the same compression framework could overcome the throughput bottleneck caused by their o

---

### [146] Unified Multi-Dimensional Benchmark for Complex Graph Reasoning in Large Language Models

**链接**: https://arxiv.org/abs/2608.12391
**作者**: Fali Wang, Ali Al-Lawati, Iliyas Bektas, Jinxuan Fang, Alek Melenski, Tianxiang Zhao 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph reasoning provides a promising testbed for evaluating the reasoning ability of large language models (LLMs), as graph instances can be programmatically generated, structurally controlled, and naturally scaled to long-input settings. However, existing graph reasoning benchmarks have limited coverage of data complexity, rely heavily on manual construction, and lack unified evaluation across text-based and code-based reasoning modes. To address these limitations, we propose {\dataset}, a five-stage \textit{semi-automatic} framework for constructing complex graph reasoning benchmarks. It expands benchmark coverage along five dimensions: \textit{Graph Size}, \textit{Task Complexity}, \textit{Task Description}, \textit{Graph Loading}, and \textit{Task Source}. The framework uses an LLM-based data generator to automatically produce task descriptions, graph data, reference solutions, graph-loading scripts, question forms, and evaluation scripts, while retaining human validation at key qu

---

### [147] InterSAGE: The Secure and Verifiable Interoperability Protocol for An Internet of Agents

**链接**: https://arxiv.org/abs/2608.13030
**作者**: Zhenhua Zou, Sheng Guo, Qiuyang Zhan, Lepeng Zhao, Shuo Li, Zhuotao Liu
**来源**: cs.CR cs.MA cs.NI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The emerging Internet of Agents enables LLM-powered agents to discover peers, invoke tools, and delegate tasks across organizational boundaries. Existing protocols increasingly define how agents exchange messages, but not how an agent proves its identity, authorization, advertised capabilities, or accountability after delegation. We present InterSAGE, a trust-native protocol suite that supplies this missing security substrate alongside, rather than in place of, communication protocols. InterSAGE comprises four layers: Persistent Identity, Discovery, Trust Negotiation, and Accountability. Its four core primitives are: (1) Agent Identity Cards that bind developer, code package, operator, and deployment context; (2) capability-aware discovery using DID-bound Verifiable Credential manifests; (3) trust negotiation combining monotonic capability attenuation with two-tier access control; and (4) kernel-mediated cryptographic audit trails that bind usage, delegation, and execution traces to ag

---

### [148] Confucius4-TTS: Transcript-Free Cross-Lingual Zero-Shot TTS with a Learnable Speaker Encoder

**链接**: https://arxiv.org/abs/2608.11650
**作者**: Huaxuan Wang, Huimin Wang, Ruiyu Zhang, Yingjie Li, Yitao Duan
**来源**: cs.SD cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in zero-shot text-to-speech (TTS) have substantially improved speech quality and voice cloning fidelity. However, many zero-shot TTS systems still depend on audio prompt transcripts at inference time. This dependency limits cross-lingual voice cloning, since in-the-wild reference audio is often untranscribed. In this technical report, we present Confucius4-TTS, a multilingual zero-shot TTS system that supports 14 languages and performs both intra-lingual and cross-lingual reference cloning without requiring transcripts of audio prompts. Confucius4-TTS follows a two-stage architecture, consisting of text-to-semantic (T2S) and semantic-to-acoustic (S2A) modules. The LLM-based T2S module uses a learnable speaker encoder to extract timbre features from self-supervised speech representations, and the conditional flow-matching S2A module converts the predicted semantic tokens into mel-spectrograms. The same model also supports continuation cloning when a reference transcript 

---

### [149] Agent Safety Should Be a Runtime Contract

**链接**: https://arxiv.org/abs/2608.11274
**作者**: Albus W. Ng, Yi Han, Jusheng Zhang, Wenhao Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The dominant paradigm treats AI safety as a property to be instilled during model training via RLHF, DPO, or Constitutional AI. We argue this is structurally insufficient for autonomous agents that execute code, mutate files, send messages, and modify databases. Agent safety should be a runtime contract enforced by the harness, and the contract has two complementary faces. The preventive face blocks dangerous actions before they happen via sandboxes, permission gates, output filters, and trajectory monitors. The evidential face requires verifiable proof that good actions actually happened, gating task submission on hard evidence such as test runs, log captures, file diffs, and citation grounding. We ground the position in four lines of public evidence, with row-level protocols and data released in the supplementary JSON files: a survey of 52 documented AI-agent and LLM safety incidents, a false-completion audit with 31 non-contested core cases plus one disputed illustrative case, a tra

---

### [150] DMDIntel: Interpreting Large Language Models via Dynamic Mode Decomposition

**链接**: https://arxiv.org/abs/2608.13048
**作者**: Amogh Joshi, Animesh Mukherjee, Sergey Utyuzhnikov
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we introduce DMDIntel which uses dynamic mode decomposition (DMD) to make the predictions made by LLMs in a classification task interpretable. It develops an input attribution pipeline, that first decomposes the hidden states of an LLM into prominent patterns, also known as modes, and then associates ranks to the input tokens based on the projection values on those modes. Rigorous experiments across three datasets and three model families consistently show that the ranked attribution of input tokens obtained using DMDIntel by far outperforms state-of-the-art techniques such as principal component analysis, integrated gradients and SHAP.

---

### [151] RippleMem: From Isolated Retrieval to Associative Recollection for Long-Term Agent Memory

**链接**: https://arxiv.org/abs/2608.13334
**作者**: Jingbo Ji, Lingyi Li, Xilong Cheng, Yuhao Zhou, Wenji Zhang, Yuting Tan 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly rely on external memory to support long-horizon reasoning and interaction. However, the main bottleneck is not simply storing past experience, but recovering the right set of evidence when relevant information is distributed across many interactions. Existing approaches struggle with this access problem. Full-context methods require noisy long-context search, flat retrieval often returns isolated and incomplete records, and graph-based memory systems can be expensive to construct while compressing rich event context. We introduce RippleMem, a long-term memory system that replaces one-shot retrieval with adaptive associative recollection. Inspired by cue-dependent episodic retrieval and associative completion, RippleMem stores interaction history as cue-rich episodic memory units and organizes them in an event-centric memory graph. Given a query, it first recalls relevant memory anchors through hybrid cues, then expands from these anchors along semantic and

---

### [152] FrontierFinance: A Challenging Benchmark for Measuring Frontier Intelligence of Finance Agents

**链接**: https://arxiv.org/abs/2608.11683
**作者**: Yuhao Zhang, O. Ozan Koyluoglu, Thejas Venkatesh, Richard Diehl Martinez, Vishank Bhatia, Arash Alidoust 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents are increasingly deployed for professional investment research, yet no benchmark captures the complexity of the full investor workflow. Existing benchmarks mainly target financial data extraction, a narrow slice that current models have largely saturated, while reference-based metrics and generic LLM-as-a-judge scoring fall short on the open-ended, long-form answers that real analyst queries demand. We introduce FrontierFinance, a fully open benchmark of 220 expert-crafted queries and 11,543 source-attributed rubrics spanning six crucial use cases across the full investor workflow. FrontierFinance is both broader and harder than existing public finance benchmarks. Evaluating frontier models and agent systems under a common harness restricted to publicly available data, we find that the tool harness, not the model alone, strongly shapes quality and efficiency; that Samaya's in-house system leads at 56.0%, ahead of the strongest frontier model (Claude Fable 5, 49.2%) at roughly

---

### [153] Do LLMs Take Care of Their Own? Similarity Signals Can Induce Cooperation

**链接**: https://arxiv.org/abs/2608.12125
**作者**: Akash Kundu, Emanuel Tewolde, Ratip Emin Berker, Samuel F. Brown, Vincent Conitzer
**来源**: cs.GT cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-based agents with user-instructed goals are becoming widely deployed, they increasingly encounter each other in strategic interactions, and face challenges of finding mutually beneficial outcomes. Prior literature has argued that cooperation problems such as the Prisoner's Dilemma are resolvable in settings where agents know they follow very similar decision making patterns, as for example in monocultural AI ecosystems. Following that line of work, this paper introduces the first framework for evaluating LLM decision making when agents are provided with graded similarity signals. Among our findings, we establish that different LLM models vary drastically in how they navigate similarity signals, with some modern models showing consistent behavior across cooperation problems, payoff structures, and prompt framing. Perhaps surprisingly, our experiments also show that the dataset based on which the similarity signal is computed has small to no impact on induced cooperation, and that

---

### [154] A Modular Agentic Framework for Synthetically Constrained Multi-Objective Hit-to-Lead Optimization

**链接**: https://arxiv.org/abs/2608.11483
**作者**: Kelvin P. Idanwekhai, Enes Kelestemur, Benjamin Strickland, Matthew Hart, Steini Davidsson, Angelos Angelopoulos 等 (9 人)
**来源**: cs.AI cs.LG q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hit-to-lead optimization requires iterative design of hit analogs across competing potency, selectivity, physicochemical, pharmacokinetic, safety, and synthetic constraints. We present SABLE (Synthetically-accessible Agentic Bayesian Ligand Exploration), an open-source framework that employs natural-language orchestration to guide chemical structure optimization. SABLE uses an LLM to interpret user-defined goals and route tasks, while specialized tools perform reaction-templated analog enumeration, physicochemical and ADMET property prediction, structure-based affinity scoring, and Bayesian optimization. The resulting workflow is a computational twin of the analytical and prioritization stages of the design-make-test-analyze cycle, providing provenance of each numerical output. Across single, and multi-objective optimization studies, SABLE enriches candidate sets for user-defined computational objectives while evaluating only a subset of the enumerated search space. Its modular archite

---

### [155] When AI Is Your Pastor: A Benchmark for Theological Triage and Pastoral Guidance in Large Language Models

**链接**: https://arxiv.org/abs/2608.12324
**作者**: Alex Chao
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People increasingly ask large language models (LLMs) for counsel on questions of faith, doctrine, and pastoral care. These questions are not ordinary information requests. Some ask about core Christian beliefs, some ask about real disagreements among faithful traditions, some require humility because the issue is prudential, and some are pastoral situations where safety and human referral matter more than theological completeness. Existing benchmarks do not evaluate this structure. We introduce FMG-Bench, the Faith & Moral Guidance Benchmark, a 120-scenario benchmark for evaluating large language model behavior in English-language Christian theological triage and pastoral guidance contexts. FMG-Bench v1 evaluates 14 advanced models across 8,792 scored responses, comparing raw model behavior with three guided instruction settings. In our production run, placing models inside a structured harness improves over raw model behavior by +3.96 points on average, with every model improving. The

---

### [156] A Cloud-Edge System for Multimodal Clinical Screening in Resource-Constrained Rural Settings

**链接**: https://arxiv.org/abs/2608.12745
**作者**: Hei Ting (Una) Chan, Chenwei Wu, Xueshen Liu, Zesen Zhao, Boyuan Zheng, Luis Filipe Nakayama 等 (10 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical AI has demonstrated specialist-level diagnostic accuracy, yet these capabilities remain largely inaccessible in resource-constrained rural settings where bandwidth is scarce, compute is limited, and clinical decision-making requires integrating heterogeneous modalities. We introduce a cloud--edge collaborative architecture that addresses these constraints: lightweight, domain-specific models on the edge transform raw medical data into compact structured outputs, while a cloud LLM synthesizes these outputs into clinical summaries. An LLM-based orchestrator dynamically selects diagnostic tools based on patient context, promoting comprehensive modality coverage without processing irrelevant inputs. We evaluate on 20 multimodal clinical cases spanning cardiac, obstetric, trauma, and screening scenarios under three simulated network profiles (500,kbps--5,Mbps). The hybrid system achieves 98--99% diagnostic tool recall with 92--96% precision, matches or exceeds cloud-only baselines o

---

### [157] QuoteBench: How Matched Scores Can Hide Command-Path Failures

**链接**: https://arxiv.org/abs/2608.13547
**作者**: Shangao Li, Yao Zhang, Volker Tresp, Yuanyuan Yang
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM coding agents issue Bash commands through interfaces that may serialize, wrap, and reparse model output. Matched execution scores alone cannot distinguish command-generation errors from failures introduced after generation. QuoteBench measures this boundary with exact final-state validation on 56 one-shot tasks from 14 incident-derived families, crossing the generation contract with the execution transport around one deliberately unescaped added parser. Escaping at the interpolation point reproduces each replayed reply's raw-path outcome, so any recovery under a disclosed boundary must come from the model changing its generation. Across eight same-window configurations, replaying the same reply through the added parser lowers success by 55.4 to 73.2 percentage points; disclosure recovers 30.4 to 60.7 points for six configurations, and zero or slightly negative for the other two. Raw generation is nearly saturated at the frontier; boundary adaptation is what still separates models. 

---

### [158] Can Frontier LLMs Match Natively Multimodal Embeddings? A Comparison on Hard-Negative Text-to-Image Retrieval

**链接**: https://arxiv.org/abs/2608.11343
**作者**: Archan Dutta, Vyanktesh Kanungo
**来源**: cs.AI cs.CV cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal retrieval and classification across different types of media, spanning text, images,video and audio, has traditionally relied on dual-encoder models that align visual and textual representations through contrastive learning. The March 2026 release of Gemini Embedding 2, Google's first natively multimodal embedding model to map text, images, video, audio, and documents into a single shared space, raises competition among multimodal retrieval systems. Simultaneously, frontier Large language models (LLMs) have also demonstrated strong visual understanding, raising the question of whether they can serve as effective zero-shot rankers. Our study provides the first direct comparison of native multimodal embeddings against LLM-based visual ranking on Flickr30k. We observe that GPT-4.1 and Claude Sonnet 4.6 perform on par with Gemini Embedding 2. Additionally, once embeddings are precomputed, multimodal embeddings are better suited for low-latency applications.

---

### [159] PROVE-RT: Generating Mechanized Theorem Prover Scripts for Real-Time Systems using LLMs

**链接**: https://arxiv.org/abs/2608.12762
**作者**: Sadat Shahriyar, Shareef Ahmed, Abdullah Al Arafat
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Schedulability analysis is essential for certifying real-time systems, but existing tests are often developed through pen-and-paper proofs that are difficult to scale, validate, and maintain. Mechanized verification in PROSA/ROCQ offers a rigorous alternative, yet manually constructing such proofs requires substantial domain expertise and proof-engineering effort. Recent successes of large language models (LLMs) across a wide range of tasks make them promising candidates for generating PROSA/ROCQ scripts for mechanized theorem provers. However, state-of-the-art LLMs often lack the PROSA-specific knowledge required to correctly use its modeling abstractions and proof patterns. This paper introduces PROVE-RT, an LLM-assisted framework for generating PROSA/ROCQ scripts to mechanize schedulability analyses in real-time systems literature. PROVE-RT guides generation through dependency-aware informal sketches, retrieval from processed PROSA documentation, staged skeleton generation, and proo

---

### [160] AaLLM: An End-to-End Analog Circuit Design Framework from Topology Generation to Sizing Using Large Language Models

**链接**: https://arxiv.org/abs/2608.13472
**作者**: Mohammed Ayman Habib, Rylan Hart, Morteza Fayazi
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog circuit design is a time-consuming, iterative process in a nonlinear and high-dimensional design space that relies heavily on expert intuition. Among recent developments, LLMs have introduced a promising approach by bringing natural language reasoning to circuit design tasks. The majority of conventional LLM-based approaches provide fragmented solutions that focus either only on sizing or topology generation. These methods require adding specific technical knowledge manually, which is inefficient and prone to hallucinations during circuit sizing. Moreover, the inherent trade-off in meeting different specs makes current approaches iterative and tedious. Another shortcoming is the inability to create innovative topologies, which may lead to sub-optimal designs due to reliance on conventional topologies. In this paper, we present AaLLM, an open-source end-to-end multi-agent LLM workflow that takes user specs as input and outputs the appropriate netlist, encompassing both topology g

---

### [161] Large Language Models Can Follow Instructions, But Not Many at Once: Phase Transitions in Compositional Constraint Satisfaction

**链接**: https://arxiv.org/abs/2608.12426
**作者**: Mariya I. Vasileva
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed in settings that require simultaneous adherence to multiple explicit constraints - reasoning structure, safety boundaries, output schemas. Individual constraints are handled proficiently, but the compositional regime, where many must hold jointly, remains poorly characterized: how rapidly does performance degrade, what governs the degradation, and can the collapse be mitigated? We introduce Constraint Saturation Evaluation (CSE), a procedurally generated benchmark that systematically varies the number of simultaneous constraints (k), with every constraint scored by a deterministic, rule-based verifier and zero LLM-judge involvement: 15 models, 36 constraint types, 369,753 checks at k=1-12. Three findings emerge. First, per-constraint pass rate decays gradually and predictably, while the chance of satisfying all k constraints collapses - a model passing individual constraints at ~41% at k=8 succeeds on all eight just 5.7% of the time. Seco

---

### [162] Better, Faster, Stronger: Programmatic Skill Learning Best Reduces Agent Cost

**链接**: https://arxiv.org/abs/2608.11338
**作者**: Zixi Huang, Xiheng Wang, Andrew Wang, William Jurayj, Bernal Jim\'enez Guti\'errez, Daniel Khashabi 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, the practice of augmenting LLM agent capability with skills has gained prevalence. We explore the cost effective adaptation of agents to novel domains by means of learning skills. Existing works focus on performance gain over cost effectiveness. As a result, little is known about what skill learning strategies save cost. We argue that among all the different skill learning methods, those that view skills as programs can achieve the best cost reduction. By executing sequences of actions deterministically, a program-augmented agent can reliably and cheaply achieve goals that would otherwise require trial and error and risk degenerate behavior over long horizons. An agent can learn at inference time by incrementally discovering these programs and equipping them for future tasks. We hypothesize that past trajectories contain enough signal to guide skill learning, even without replay or validation, provided the agent can learn to analyze them. To test our claims, we propose SpeedR

---

### [163] Do Not Forget the Obvious - RISC: A Risk-Informed Slice-Coverage Protocol for Safe Autonomous Driving

**链接**: https://arxiv.org/abs/2608.12051
**作者**: Fabian H\"uger
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aggregate metrics may not fully reflect performance in insufficiently examined high-risk driving conditions. We propose RISC (Risk-Informed Slice Coverage), a practical protocol for risk-guided stress testing and coverage-qualified evaluation. Risk-guided stress testing directs a finite audit budget toward risk-relevant sub-datasets, called risk slices, while coverage-qualified evaluation reports results together with explicit statements about which slices are sufficiently or insufficiently covered. The protocol translates safety concerns into machine-readable risk slices, uses lightweight signals to tag candidate data, selects a compact audit set by risk, and qualifies the results using coverage evidence. An LLM can optionally support this process by surfacing relevant but potentially overlooked conditions during test planning, thereby helping engineers not to forget the obvious. RISC is model-agnostic and can be applied to perception modules, driving models, and other autonomous-driv

---

### [164] Social Chain of Thought: A Multi-Agent Architecture Grounded in Medical Differential Diagnosis Methodology

**链接**: https://arxiv.org/abs/2608.11420
**作者**: Del Coburn, Scott Sanner, Dan Silver
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical diagnostic reasoning is a high-impact use case for LLMs that carries significant implications for the health and wellbeing of users. When OpenAI (2026) reports that more than 5% of ChatGPT messages globally are healthcare-related, the transparency of these systems becomes a serious design concern. This is especially true for complex cases, where differential diagnosis often requires integrating multiple forms of specialist reasoning. Existing work has proposed multi-agent approaches to medical diagnosis, but it remains unclear when such systems are needed, why they help, and where they outperform monolithic inference. We introduce Social Chain of Thought (SCoT),a multi-round pipeline for medical differential diagnosis that structures multi-agent interaction as a deliberative framework for collabora. tive LLM reasoning. Evaluating SCoT against single-agent baselines, one-agent pipeline ablations, and best-of-n scaling, we show that its recall advantage is not reproduced by monol

---

### [165] How China-Origin Vision-Language Models Move from Refusal to Reframing in State Alignment

**链接**: https://arxiv.org/abs/2608.11816
**作者**: Guang Yang, Fengchen Liu, Alex Wang, Homa Hosseinmardi, Amir Ghasemian
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> State-aligned distortion has been documented in China-origin text-based large language models (LLMs), but whether, and in what form, it arises in multimodal systems has not been systematically examined. We construct a balanced benchmark of 200 core entries spanning ten politically sensitive topics, plus a seven-variant visual-abstraction probe, and run nine vision-language models (VLMs), seven China-origin and two non-China, across four elicitation paradigms and two prompt languages, yielding 21,708 trials. Each response is audited on six dimensions -- explicit refusal, information integrity, visual grounding, state-aligned framing, language consistency, and response length -- by two independent frontier LLM judges, validated against three human experts on a 200-trial sample. Measuring each dimension separately lets us decompose multimodal censorship into individual signals rather than a single refusal-based score; in particular, refusal and framing are measured independently, so a mod

---

### [166] Localize, Then Reason: Visual Latent Structural Reasoning for Molecular Properties and Edits

**链接**: https://arxiv.org/abs/2608.13244
**作者**: Xingqiao Lin and Junmei Wang and Haocheng Tang
**来源**: cs.CL cs.CE q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Local chemical perception and property reasoning are both essential for understanding how molecular structure determines properties. Current LLM-based chemical reasoning methods either receive SMILES/molecular images together with descriptions of local motifs, or reason directly from molecular images. Neither approach enables the model to focus on chemically meaningful regions before reasoning. To address this gap, we propose Visual Latent Structural Reasoning (VLSR), an end-to-end framework that jointly learns localization and reasoning from molecular images. Central to our approach is a localize-then-reason strategy. VLSR first learns to locate chemically meaningful regions in a molecular image. It then reasons about their property effects in a compact latent workspace before producing the final answer. Under the same inference setup, this design achieves 9.6X higher throughput than a comparable textual-reasoning baseline.

---

### [167] Rubric Dropout: A Simple Way to Mitigate Reward Hacking in Rubric-as-Reward RL

**链接**: https://arxiv.org/abs/2608.11669
**作者**: Minglai Yang, Xinyu Guo, Utkarsh Tyagi, Mian Zhang, Razvan Dumitru, Sunjie Hou 等 (9 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning against rubrics, lists of criteria graded by an LLM judge, has become a standard way to post-train language models on tasks with no deterministic answer. The rubric, however, is a fixed proxy for quality, never a complete description of it, and a policy trained against it long enough will learn to exploit the difference. We measure this directly. Training Qwen3-8B with Group Relative Policy Optimization (GRPO) on medical and science rubrics and grading out-of-distribution (OOD) benchmarks with both the training judge and a stronger gold judge, we find that the two scores diverge during training. The training judge's score keeps climbing while the gold judge's score peaks and then falls, by 3 points on HealthBench-Hard and by 22 points on ResearchQA. A judge with a fixed bias would shift the gold curve by a constant, not send it down while the training score rises, so the divergence is reward hacking, not judge noise. We propose Rubric Dropout, a one-line fix borr

---

### [168] LLMs in Process Diagram Engineering: From Optimal PFDs to Validated P&IDs

**链接**: https://arxiv.org/abs/2608.11220
**作者**: Timur Zakarin, Sergei Voitov, Sergei Shumilin, Evgeny Burnaev
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nowadays, the creation of a process flow diagram (PFD) and its subsequent transformation into a piping and instrumentation diagram (P&ID) is predominantly performed manually. Applying artificial intelligence in the task could potentially lead not only to process automation and time savings, but also to financial gains by exploring numerous diagram's topology options and reducing manual labor. This research presents P&ID Pilot - a practical end-to-end AI pipeline capable of handling flowsheet developing for both stages. The first stage focuses on PFD synthesis, whereas the second is directed toward modifying the generated PFD into P&ID. After comparing four different methods, the hybrid approach combining genetic algorithms (GA) and large language models (LLM) is shown to generate the optimal valid PFD topology, achieving the lowest loss value among all the methods, while satisfying the required outlet flow parameters without engineering-rule violations. For the second stage, the propos

---

### [169] Why AI Governance Frameworks Are Hard to Adopt: A Role-Based Stress Test of the NIST AI RMF

**链接**: https://arxiv.org/abs/2608.12352
**作者**: Joseph R. Simons and David A. Broniatowski
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI governance frameworks can be known, used, and implemented in form without becoming governance in practice. This paper examines that problem through a role-based stress test of the NIST Artificial Intelligence Risk Management Framework (AI RMF) in consumer lending. We treat framework adoption as a governance translation problem: whether RMF language can become role-usable, cross-level, authority-connected governance over the AI system-in-use, rather than producing governance-looking artifacts. The study uses LLM-based role simulation as a structured analytic probe. We apply a 4 $\times$ 2 $\times$ 3 design across four organizational roles, two AI deployments, and three governance hard cases, producing 120 scored responses. Results show that local translation was not the main problem. Simulated actors generally understood their assigned roles and translated the RMF into local activity. The harder problem was whether that activity became governance value. Actor role was strongly associ

---

### [170] From Monolithic to Modular: Segment-level Automatic Prompt Optimization

**链接**: https://arxiv.org/abs/2608.11219
**作者**: Nikita Kulin, Viktor Zhuravlev, Artur Khairullin, Sergey Muravyov, Ilya Makarov, Daniil Sukhorukov 等 (7 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic Prompt Optimization (APO) often rewrites prompts monolithically, which can improve one behavior while degrading others. We present SAPO, a segment-level APO method that decomposes prompts into role, context, tasks, and output format, then applies targeted improvements based on top-5 and bottom-5 examples. The optimization loop uses one LLM with static meta-prompts and structured outputs for segmentation, weakness analysis, and candidate generation. We describe a train/validation protocol and a two-stage generation process: (1) segment-level diagnosis and recommendation extraction, (2) candidate synthesis constrained by weak/strong segment signals. Using the evaluation setup across SQuADv2, TweetEval, XSUM, CommonGen, and GSM8K on GPT-3.5-Turbo and GPT-4o-mini, SAPO achieves the best average score against Zero-shot and strong APO baselines including APE, OPRO, EvoPrompt, GEPA, and StraGO.

---

### [171] Before You Say It: Anticipating Verbal Behavior from Longitudinal Everyday Conversations with LLMs

**链接**: https://arxiv.org/abs/2608.13454
**作者**: Yasith Samaradivakara, Valdemar Danry, Paul Liang, Pattie Maes
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowing someone deeply means not just understanding what they say or do but also how they will likely think, react, and engage across situations. Such predictions could eventually inform systems to anticipate when the individual is about to deviate from their goal, catch regrettable behaviors before they are made, and surface blind spots before they take hold. While many interactive systems model users to enable more personalized interactions, most cannot make such behavioral predictions, as this often requires longitudinal observation and inference of how the individual's behaviors unfold across various everyday situations. In this work, we introduce a novel LLM-based predictive behavioral modeling approach that anticipates a user's likely behavior across everyday conversational situations. We (1) collect a longitudinal dataset of over 1000 hours of naturalistic conversations from 14 participants using a wearable smartwatch; (2) evaluate LLM-based predictions against ground truth beha

---

### [172] TradingMoE: Routing the Right Experts in Evolving Markets

**链接**: https://arxiv.org/abs/2608.11785
**作者**: Chang Zhou, Xingtong Yu, Minbin Huang, Zhennan Wu, Yuan Fang, Hong Cheng 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong potential for financial analysis and trading, but direct trading remains challenging because the predictive capabilities required can vary across assets, decision fields, and market conditions. Existing LLM-based trading systems either coordinate human-defined external experts or adopt conventional internal Mixture-of-Experts (MoE) routers that do not directly evaluate how individual experts contribute to trading decisions. Moreover, these routers receive no direct signal indicating when an inactive expert has become more suitable as market conditions change. We find that native router scores poorly reflect how much individual experts improve trading decisions, frequently leaving better alternatives unselected. We further reveal that token-specific expert usefulness exhibits a compact low-dimensional structure. Based on these findings, we propose TradingMoE, a trading-oriented sparse MoE that augments a frozen dense LLM with lightweight re

---

### [173] Accuracy and Order Sensitivity Diverge Under Label-Free Strategies

**链接**: https://arxiv.org/abs/2608.11947
**作者**: Karl Hanna and Chen Feng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiple-choice benchmarks are widely used to evaluate large language models, but MCQ scores conflate knowledge with sensitivity to option order, which makes them unreliable measures of model knowledge. In this paper, we test whether preventing a model from seeing option labels while committing to an answer removes positional influence and, in turn, improves performance. We evaluate two different strategies for mitigating bias. The first uses a generation-then-matching approach, and the second scores options in isolation, which is positionally unbiased by construction. Neither reliably improves accuracy. A complete decomposition shows that the bottleneck is withholding options, not the matching step. The only configuration that consistently matches the baseline is the one that shows the model all options paired with an LLM matcher. However, eliminating positional influence entirely still does not reliably yield accuracy gains, while cyclic permutation often improves them. For two-stage

---

### [174] Agent Behavioral Contracts II: Certifying Compositional Reliability Without Assuming Independence

**链接**: https://arxiv.org/abs/2608.12895
**作者**: Varun Pratap Bhardwaj, Garima Singh, Arun Pratap Bhardwaj
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compositional reliability bounds for multi-agent systems multiply component reliabilities, a step licensed by a conditional-independence assumption that is routinely stated and rarely tested. We test it. Two instances of one model, in a two-agent handoff, co-fail on 90.0% of the missions on which either fails (log OR 6.66, 95% CI [6.38, 7.00]; phi 0.916), in a preregistered evaluation of 18,000 missions scored by deterministic code with no LLM judge. Substituting a different model reduces the association in six of six contrasts; substituting a different vendor, model already different, does not -- a registered hypothesis reported as a null. The error is signed and runs against the operator: positive dependence inflates joint failure above the independence product, so redundancy is over-credited exactly when components share a model. The assumption-free alternative is often vacuous, and fitting a dependence model is worse: we prove a bootstrap bound on a fitted model's functional loses 

---

### [175] Jagged Judges: Epistemic Stability Under Silence, Pressure, and Persistence

**链接**: https://arxiv.org/abs/2608.12645
**作者**: Justin Zhao, Himaghna Bhattacharjee, Hannah Korevaar, Bhaktipriya Radharapu, Khalid El-Arini
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges have become central infrastructure for model evaluations, online grading, and reward modeling. Judges are typically validated by accuracy on golden data, but accuracy says little about whether they are stable under re-prompting, challenge, or sustained pushback. We introduce the \emph{Wiggle Framework}, a unified stress test for epistemic stability in LLM judges. The framework decomposes judge robustness along three dimensions: Mechanical Consistency (stability under re-prompting and reframing), Single-turn Conviction (stability under a single challenge), and Multi-turn Persistence (stability under sustained or adaptive pressure). We use the framework to study 9 frontier models across 14 judging tasks spanning safety, toxicity, AI writing detection, and political-response evaluation. Every model exhibits substantial wiggle as a judge --- flipping verdicts 25--71\% of the time under static pushback, and 62--91\% with an adversarial LLM persuader. Critically, we find that pres

---

### [176] SteerBench-Work: A Benchmark for Agent Steering at Action Boundaries

**链接**: https://arxiv.org/abs/2608.12654
**作者**: Oguz Serdar, Cuneyt Mertayak
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents act through tools, and a single step can send an email, merge a pull request, or wire a payment. The steering decision is the pre-commit choice at that boundary: proceed, or hold for human or policy review. We introduce SteerBench-Work, an incident-anchored, bidirectional benchmark for that decision in workplace agents across developer operations, customer service, finance, legal, medical, HR, and security. Release v2026-05 contains 106 scenarios anchored in public incidents, paired evidence-reversed mirrors, and calibration controls, with labels split nearly evenly between proceed and hold so the two error directions get near-identical numbers of chances. A model sees the proposed action and the available evidence, returns a gate decision, and is scored on whether it crosses or holds the boundary correctly. Across 30 model conditions the failures run almost entirely in one direction: models wrongly hold authorized, evidence-cleared work on 28.1% of opportunitie

---

### [177] SkillEvo: Self-Renewing Evolution Gradients from Multi-Turn Interaction Feedback

**链接**: https://arxiv.org/abs/2608.13120
**作者**: Qianxi Yan, Chunrong Chen, Jiuzhou Zhao, Min Zhang, Yongzhou Xu, Xiaochuan Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent Skills are today either hand-authored or produced in a single LLM generation pass, and consequently possess no closed loop through which they might improve from the interaction failures they actually cause. Recent work does close this loop, but derives its feedback from single-turn question-answering evaluation. The consequence is a sharp asymmetry: once the first round has patched the gaps that a single exchange can reveal, the evolution gradient decays, the defects that surface only across multiple turns remain invisible, and evolution stalls. Governance in these systems is likewise driven by an end-to-end verification score, a scalar gate that can reject a degraded candidate but can neither localize nor repair its structural cause. We argue that the binding constraint on sustained skill evolution is neither editing capability nor the number of iterations, but whether the evaluation feedback keeps supplying trustworthy evolution gradients. We introduce SkillEvo, in which trustw

---

### [178] Chemically Meaningful Textualization Enables Explainable Validation of Metal-Organic Frameworks by Large Language Models

**链接**: https://arxiv.org/abs/2608.11283
**作者**: Guobin Zhao and Xiao-Yan Li
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computation-ready metal-organic framework (MOF) databases are essential for high-throughput screening, yet many reported crystal structures remain chemically unreasonable or disordered, compromising simulation fidelity. Existing validation approaches can identify non-computation-ready structures, but they often rely on heuristic rules, license requirement, or offer limited interpretability. Here, we show that large language models (LLMs) can serve as interpretable validators of MOF structures when crystallographic information is transformed into chemically meaningful text. By benchmarking nine descriptors, we find that successful LLM-based validation depends not on the amount of structural information alone, but on whether local coordination, framework connectivity, and chemical context are organized into a linguistically learnable representation. Fine-tuned LLMs using specialized descriptors (mof2text) achieve performance comparable to graph-based models in identifying unreasonable MO

---

### [179] vToken: Token-Level Virtualization for Reclaimable KV Caches

**链接**: https://arxiv.org/abs/2608.13263
**作者**: Yuanhang Gao, Xiangrui Yang, Yuanfeng Chen, Hongjia Chen, Qianru Lv, Wenfei Wu 等 (7 人)
**来源**: cs.AI cs.DC cs.OS
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model serving faces a critical memory bottleneck: the KV cache grows with sequence length and batch size. PagedAttention uses fixed-size memory blocks to reduce allocator-level fragmentation, but recent KV eviction algorithms operate at a token granularity finer than block-level management. This mismatch causes intra-block fragmentation, leaving a large fraction of allocated KV memory unreclaimable. We present vToken, a lightweight token-level virtualization layer that decouples logical token liveness from physical block placement. vToken maintains a stable logical token view through token-table indirection and realizes physical reclamation by repacking live tokens asynchronously. The design preserves PagedAttention kernels and CUDA Graph compatibility. We implement vToken in vLLM and evaluate it with H2O, Random, and Scissorhands across models. Compared with a paired Naive-Evict baseline, vToken reduces retained KV blocks per request by 27.2\%--72.3\% and improves SLA-c

---

### [180] DexterSQL: Deep Schema Exploration and Rule-based Correction for Text-to-SQL Generation

**链接**: https://arxiv.org/abs/2608.11889
**作者**: Anik Pramanik, Murat Kantarcioglu, Vincent Oria, Shantanu Sharma
**来源**: cs.DB cs.AI cs.CL cs.IR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompting-based (\textit{i}.\textit{e}., non-fine-tuning) Text-to-SQL methods, where underlying large language model parameters are not changed for the task, face three problems: (\textit{i})~relying on coarse-grained schema information that may not reveal the fine-grained relationships needed to distinguish ambiguous columns, (\textit{ii})~not capturing recurring SQL-generation failures, and (\textit{iii})~suffering from omission, hallucination, or misplacement of conditions in complex questions. This paper develops \textsc{DexterSQL}, a prompting/non-fine-tuning-based Text-to-SQL system that improves SQL generation with three novel components: (\textit{i})~\emph{deep schema explorator} that identifies ambiguous columns, analyzes their individual and joint data distributions to uncover their relationships and the distinct role of each, (\textit{ii})~\emph{database-agnostic rule creator} that mines mismatches between generated and gold SQL only on the training database and converts the

---

### [181] On Measuring Semantic Preservation in Legal Ontology Learning

**链接**: https://arxiv.org/abs/2608.12326
**作者**: Albert Sadowski and Jaros{\l}aw A. Chudziak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontology learning transforms unstructured text into structured representations for automated reasoning. Yet structuring information risks losing it, and current evaluation methodologies cannot detect such loss, focusing on structural correctness while failing to measure whether meaning survives transformation. We propose an evaluation methodology that addresses this: comparing LLM task performance on source documents against performance on transformed representations, with the difference quantifying semantic loss. We demonstrate this approach on legal merger agreement analysis, a domain chosen for its complex language and precise semantic requirements, comparing direct LLM application against three ontology learning methods across six language models. The results reveal systematic semantic loss with significant variation based on reasoning complexity and model-method interactions. Our contributions are: (1) an evaluation framework for measuring semantic preservation in ontology learnin

---

### [182] Towards Understanding On-Policy Distillation through the Lens of Test-Time Scaling

**链接**: https://arxiv.org/abs/2608.11829
**作者**: Xinmu Ge, Zizhuo Zhang, Yu Huang, Jianing Zhu, Lin Yuan, Wanli Gu 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation (OPD) has emerged as a promising post-training technique for enhancing LLM reasoning. It is commonly believed to enable the student model to distill knowledge from a stronger teacher model, thereby expanding capabilities beyond the pre-OPD base model. In this study, we examine this view through the lens of test-time scaling by varying the sampling budget K and evaluating performance with pass@K and avg@K. Specifically, across several OPD variants, we observe that OPD-trained models maintain superior avg@K performance across sampling budgets, while the advantage in pass@K gradually shifts to the pre-OPD base models as K increases. These results suggest that OPD primarily improves sampling efficiency rather than consistently expanding the student's reasoning capability boundary. The pass@K dynamics throughout OPD training further reveal a progressive shift toward stronger small-K performance at the expense of the large-K capability boundary. Furthermore, a problem-

---

### [183] Explanatory Engagement Under Rare Anomalous Failure: Asymptotic Rarity in Model Behavior (or: The Asymptotic AI)

**链接**: https://arxiv.org/abs/2608.13063
**作者**: Sam Mao
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior work on LLM behavior under anomalous conditions asks whether a model notices anomalies. We ask a narrower question: once a model sits in a workflow with a low, controllable failure rate, does its explanatory engagement - length, specificity, self-reported confidence - change as failure grows asymptotically rarer? We built a local, zero-cost harness on three open-weight models (qwen3:8b, llama3.1:8b, mistral:7b) running a repeated tool-call task where one call fails at probability p, swept across eight rates from 0.2 to 0.0001, under five elicitation conditions from immediate prompting to none. We hypothesized a rise in engagement as failures grew rarer, then a collapse near a detectability threshold. Pooled across conditions this appeared false: length fell in a flat, monotonic pattern. Splitting by condition overturned that. Under immediate_forced, where the model must explain every failure instantly, the predicted rise is confirmed but followed by a plateau, not a collapse: len

---

### [184] Research Assistant: AstraZeneca's Agentic System for R&D

**链接**: https://arxiv.org/abs/2608.12395
**作者**: Piotr Grabowski, Mohamed Alameen, Jorge Bretones, Sabina Cardell, Miguel Carmona, Gavin Edwards 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We describe Research Assistant, an internal LLM-based system developed at AstraZeneca to help scientists and clinicians explore biomedical questions across a broad range of data sources. The system provides a chat-style interface that brings together evidence from scientific literature, knowledge graphs, chemistry, clinical trials, safety resources, expression data, and internal experimental systems. It supports both a fast mode for direct question answering and a multi-step mode for more complex research tasks. Responses are grounded in retrieved evidence and linked back to the original sources, allowing users to review and further explore the underlying data. In this technical note, we outline the system architecture, the main design choices behind the product, and lessons learned from deploying it at scale to support day-to-day R&D workflows across AstraZeneca.

---

### [185] Hybrid-Policy Self-Editing for Composable Unstructured Knowledge Editing

**链接**: https://arxiv.org/abs/2608.11660
**作者**: Tianci Liu, Zihan Dong, Tianchun Li, Yi-Chung Chen, Qiming Cao, Xingchen Wang 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) achieve remarkable performance across natural language tasks, yet they are trained on static corpora and their knowledge quickly becomes outdated in a fast-changing world. This motivates knowledge editing (KE), which updates specific knowledge in an LLM without changing unrelated others. Recent works move from structured knowledge triples toward unstructured KE (UKE), where the edit is a free-form passage that may state multiple facts at once. Nonetheless, existing editors inject such a passage yet fail to use it: the edited model can recall the passage, but can neither answer atomic questions about its facts nor compose them into multi-hop reasoning. We attribute this missing property, which we term composability, to editors' passive reliance on the fixed passage as the sole learning source. In response, we cast editing as a proactive self-distillation from a privileged in-context state of the same model, which requires no external supervision. We further 

---

### [186] TrustEndo: A Conformal-Calibrated MLLM With Retrieval-Augmented Reasoning for Trustworthy Gastroscopic Diagnosis

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11646985/&hl=zh-CN&sa=X&d=15924588901278975832&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoOe1XvT7HE58cTjSt0-amkn&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=0&folt=kw-top
**作者**: Y Ma, ML Feng, H Wang, J Wu, R Fu, X Ma - IEEE Journal of Biomedical and Health … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> grounds MLLM … MLLM pipelines. No existing framework unifies conformal reliability, evidence-augmented reasoning, and concept-grounded interpretability for medical MLLMs. We present TrustEndo, the first framework that integrates these

---

### [187] Understanding Knowledge Transfer Mechanism in Heterogeneous MLLM Fusion: A Simple Linear Approach

**链接**: https://arxiv.org/abs/2607.26608
**作者**: Yinghao Hou, Jiahe Fan, Yuanhao Pu, Zongyuan Chen, Hong Xie
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [188] ADOPD: Reference-Privileged On-Policy Distillation for MLLM -Based Industrial Anomaly Detection

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.09789&hl=zh-CN&sa=X&d=7097444923016042652&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoNG7a9WlwhZv1ktgOiHyjZT&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=1&folt=kw-top
**作者**: J He, S Meng, W Meng, Q Yang - arXiv preprint arXiv:2608.09789, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> -shot inference, indicating that reference comparison provides useful evidence for MLLM -based IAD. Nevertheless, explicit reference-conditioned … We therefore ask: Can the benefits of reference comparison be internalized into model parameters

---

### [189] EgoAfford: Affordance-Aware Zero-Shot Open-Vocabulary Egocentric Action Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-31936-4_7&hl=zh-CN&sa=X&d=9454201530953409723&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoOZTzha5lt4UBfakpzIYbV0&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=5&folt=kw-top
**作者**: D Gesualdi, R Santambrogio, F Palermo, C Plizzari… - International Conference on …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> (3) Affordance-Aware Egocentric Action Recognition, we provide the MLLM with egocentric video frames and the synthesized part-based affordances. These serve as action hypotheses: the prompt instructs the model to combine object and hand

---

### [190] An AI4AI Framework for Visual Token Pruning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.07193&hl=zh-CN&sa=X&d=4418693717243450729&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoOBs00ZgONb5Ur9-2mnj5xi&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=9&folt=kw-top
**作者**: Z Liu, W Huang, W Song, Y Liu, Z Yang, J Fu - arXiv preprint arXiv:2608.07193 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Experiments on 14 multimodal benchmarks and three MLLM backbones demonstrate the effectiveness, efficiency, and transferability of AutoPrune. Even when removing 94.4% of visual tokens, AutoPrune preserves more than 99% of full-token

---

### [191] Hallucination-Free GUI Grounding via Regression-Free Layout-Aware Matching

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.09654&hl=zh-CN&sa=X&d=4615224200097693469&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoMZDO0_qAPDlJxBSm7tyepV&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=2&folt=kw-top
**作者**: Y Li, X Hou - arXiv preprint arXiv:2608.09654, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> MLLM performs instruction parsing and a dedicated grounding model handles precise localization without learning any coordinate regression. A frozen MLLM … task planning from visual grounding, flexibly integrating an MLLM for semantic

---

### [192] VOS-Agent: The 1st Place Solution for the 8th LSVOS Challenge (MOSEv2 Track)

**链接**: https://arxiv.org/abs/2608.12721
**作者**: Canyang Wu, Jinrong Zhang, Xusheng He, Ce Bian, Xianjing Han, Jianlong Wu
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complex video object segmentation requires robust target propagation under severe occlusion, disappearance and reappearance. Although SAM3 provides strong promptable mask propagation, a uniform inference path remains unreliable for tiny targets with insufficient visual evidence and semantic-dominated targets whose identities depend on explicit attributes. To this end, we present VOS-Agent, a collaborative framework that retains SAM3 as the shared dense segmentation module and conditionally activates specialized agents according to target characteristics. A Target Perception and Routing Agent assigns each sequence to a regular, tiny, or semantic-dominated route. Tiny targets are supported by a Visual Tracking Agent through confidence-aware box prompts, while semantic-dominated targets are handled by an MLLM-based Semantic Agent through description-guided localization and candidate verification. On the MOSEv2 test set, VOS-Agent achieves 69.82% on the official $\mathcal{J}\&\dot{\mathcal

---

### [193] SPARED: Reasoning-Based AI-Generated Image Detection via Adversarially Edited Data

**链接**: https://arxiv.org/abs/2608.12876
**作者**: Yicheng Bao, Xiahui Guo, Xuhong Wang, Xin Tan
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting AI-generated images is only half the task: a deployed detector must also justify its verdict, yet existing detectors inherit three failure modes from their training data: real and fake images collected from different sources invite provenance shortcuts, supervised explanation corpora teach templated rationales, and a static forgery corpus leaves the decision boundary standing still while generators keep moving. We introduce \methodname{}, an adversarial reinforcement learning framework that pits two heterogeneous models against each other. A diffusion image editor learns to edit real photographs into fake counterparts of those same photographs that fool the current detector, while a reasoning MLLM learns to expose them with a verdict grounded in free-form reasoning. Both rewards are shortcut-proof by design: the attacker is credited only when its edit is faithfully executed, and the defender only when its verdict is correct. As the two models alternate, each round's attacker 

---

### [194] GeoBridge: Decoupled Semantic Conditioning for Generative Image Geolocalization

**链接**: https://arxiv.org/abs/2608.11838
**作者**: Zhiyang Dou, Xumeng Han, Fengde Peng, Zipeng Wang, Moxuan Zhao, Zhipei Huang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have advanced image geolocalization mainly by improving how they reason about geographic cues. How that reasoning isdecoded into coordinates, however, has lagged behind. Predicting a place name for a geocoding API is discrete and lossy: it ignores image evidence and collapses multi-granular semantics into a coarse lookup. We argue that the bottleneck has shifted from what a model reasons to how that reasoning is represented for a continuous, geometry-aware decoder. We present GeoBridge, a role-decoupled conditioning mechanism that connects a frozen semantic MLLM to a frozen Riemannian flow-matching head that generates coordinates on the sphere. The central obstacle is arole conflict: supervising the condition with discrete semantic labels biases its representation toward class-discriminative geometry, at odds with the smooth manifold the generative head requires. GeoBridge keeps the semantic supervision decoupled from the condition interface: a 

---

### [195] AgentPatch: Coarse-to-Fine Weak-Task Repair for Merging Agentic Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.06699&hl=zh-CN&sa=X&d=12737715703696818351&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoNSI-M3zo2JLmEDCC-rNTSY&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=8&folt=kw-top
**作者**: Z Shao, B Xiong, C Xu, L Xiao, K Li, H Gong 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We formulate Agentic MLLM Merging and identify two challenges: asymmetric capability preservation, whereby capabilities with different interaction complexity are retained unevenly, producing weak tasks after merging, and behaviorcritical

---

### [196] MBA: Multimodal Benchmark and Agents for Real-World Business Ideation

**链接**: https://arxiv.org/abs/2608.11616
**作者**: Hojun Choi, Jaeyo Shin, Suin Lee, Hyunjung Shim
**来源**: cs.AI cs.CV cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic systems powered by large language models (LLMs) have opened new opportunities for business ideation. Yet existing approaches remain confined to a text-only paradigm, despite the inherently multimodal nature of real-world contexts. We thus introduce MBA-Bench, the first multimodal benchmark for training and evaluating business ideation agents, comprising 30K samples across six domains, each domain characterized by distinct visual cues not fully conveyed by text alone. Concretely, we automatically caption images and employ GPT-4o to generate five reference ideas for each of three business questions through retrieval query generation, market evidence retrieval, and evidence-augmented synthesis. Following prior work, we evaluate agents across six business-oriented criteria using MLLM-as-a-Judge. To consider settings where criteria are hidden or disclosed, we present MBA-b and MBA-k for blind and known, respectively. We train both with two novel reward objectives---creativity and fe

---

### [197] Perception Before Supervision: Self-Contained Visual Distillation from Counterfactual Blind Spots

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.09931&hl=zh-CN&sa=X&d=17963697378855205901&ei=-xt-atzSJJa16rQPwImpuQE&scisig=AM1tuoPiQL9Zbt34yeC2-rZz5ViC&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AM1tuoNtALi3Y2WjnYV-PdYEDXCz&html=&pos=3&folt=kw-top
**作者**: S Venkatraman, O Thawakar, R Thawkar, A Shaker… - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> On the distillation side, Vision-OPD [37] shows that the same MLLM can often answer a fine-grained question correctly when given an evidence-centered crop while failing on the full image. It leverages this regional-to-global gap for on-policy

---

### [198] MAG: MAnifold Guided Semi-Supervised Multi-modal In-Context Learning

**链接**: https://arxiv.org/abs/2608.12724
**作者**: Zirui Cheng, Xun Xu, Tiankai Chen, Fady Rezk, Bowen Zheng, Xiaodong Shi 等 (10 人)
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Few-shot in-context learning (ICL) with multi-modal large language models (MLLMs) enables task adaptation without parameter updates, but its performance is highly sensitive to the quality and coverage of the selected demonstrations. While unlabeled multi-modal data is abundant, it remains elusive how to exploit them for ICL. We propose MAG (MAnifold-Guided semi-supervised in-context demonstra- tion selection), an efficient framework that leverages unlabeled data to improve multi-modal ICL. MAG formulates demonstration selection as a semi-supervised propagation problem on a multi-modal graph and adopts a two-stage strategy: (i) relevance score propagation identifies a compact set of high-impact unlabeled samples for pseudo-labeling, reducing MLLM inference cost; (ii) multi-modal relevance is used to select the final demonstrations. We show that textual represen- tations are more effective for relevance propagation, while both visual and textual modalities are crucial for high-quality de

---

### [199] EEG-PRIME: Prototype-Aligned Representation Learning with Multi-Level Conditioning for EEG Decoding

**链接**: https://arxiv.org/abs/2608.13072
**作者**: Shuailei Zhang, Muyun Jiang, Wei Zhang, Jinbo Chen, Zhiwei Guo, Yong Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: EEG, BCI, EEG Foundation Model, Motor Imagery
**相关性评分**: 8.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) decoding models often generalize poorly across datasets and subjects due to domain shifts in acquisition protocols and individual neurophysiology. We propose EEG-PRIME, a two-stage EEG foundation model for cross-dataset multi-task decoding. EEG-PRIME combines masked pretraining with prototype-aligned instruction tuning to enable instruction-aware and subject-invariant decoding across diverse BCI paradigms. During pretraining, an EEG encoder learns transferable representations through masked reconstruction with frequency-cutoff spectral augmentation. During instruction tuning, EEG-PRIME incorporates task-semantic, dataset-specific, and subject-invariant conditioning. The resulting conditioning signal modulates the Q-Former through Layer-wise Query Modulation, while frozen text embeddings of class labels serve as prototypes for cosine-similarity-based prediction across heterogeneous label spaces. Experiments on sixteen datasets covering motor imagery, emotion

---

### [200] ZIPBrain: Can EEG Foundation Models Be Faster, Locally Deployable, but Accurate?

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.07033&hl=zh-CN&sa=X&d=12701058047188634723&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoM3a7HYimUvYrshPc2u_k7i&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=5&folt=kw-top
**作者**: L Li, Y Kan, P Chen, X Cao, Z Chen, Y Nakashima - arXiv preprint arXiv:2608.07033 等 (7 人)
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> EEG ’s low SNR further suggests many of these tokens are redundant and compressible with little accuracy cost. We propose ZIPBrain, a novel redundancy-aware EEG … Extensive experiments across multiple EEG foundation models show

---

### [201] Continuous-Latent Predictive Modeling with Semantic Alignment for EEG-Language Foundation Models

**链接**: https://arxiv.org/abs/2608.11656
**作者**: Myeong-Ju Cho, Hye-Bin Shin, Seo-Hyun Lee, Seong-Whan Lee
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in EEG foundation models have demonstrated the potential of large-scale pretraining to enable generalizable neural decoding across subjects, recording environments, and datasets. However, dominant pretraining paradigms face key challenges: masked autoencoding tends to prioritize low-level signal reconstruction over task-relevant semantics, while autoregressive modeling creates a mismatch between continuous neural dynamics and discrete token spaces. To address these challenges, new strategies are needed to effectively align continuous EEG representations with natural-language semantics and enable their integration with large language models. Accordingly, we propose Brain Latent Predictive Model (BLPM), an EEG-language foundation model that reformulates heterogeneous EEG decoding tasks as a continuous semantic embedding prediction problem. BLPM introduces a Continuous EEG Latent Predictive (CELP) encoder that learns transferable representations through latent target predi

---

### [202] EEG Decoding Using CNN and LSTM Network

**链接**: https://arxiv.org/abs/2608.13285
**作者**: Athanasios Karagounis
**来源**: cs.LG cs.HC
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motor imagery (MI) brain--computer interfaces (BCIs) have emerged as a promising approach for establishing flexible communication pathways between the human brain and external devices , particularly for individuals affected by stroke or neurodegenerative disorders. Reliable decoding of motor-imagery electroencephalography (MI-EEG) remains challenging because EEG recordings contain substantial noise and exhibit complex, weakly informative relationships with the underlying brain activity. Although deep learning provides an effective means of learning representations directly from EEG signals, its application to MI-EEG feature learning remains comparatively limited. This study introduces a hybrid deep-learning architecture that integrates a convolutional neural network (CNN) with a bidirectional long short-term memory (bi-LSTM) network. The CNN is used to learn high-level spatial and temporal representations directly from raw MI-EEG recordings, whereas the bi-LSTM models temporal dependen

---

### [203] Evolving epileptic activity under focal rhythmic Delta activity: insights from simultaneous intracranial and scalp EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2467981X26000752&hl=zh-CN&sa=X&d=2534744372473063582&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoPdpOxsnmnhRBc20KrZ2_-j&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=9&folt=kw-top
**作者**: A Sakata, N Mukae, T Shimogawa, T Mukaino… - Clinical Neurophysiology …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ) recordings to determine whether LRDA observed on scalp EEG reflects epileptic … scalp EEG during the acute phase reflects epileptic activity observed on intracranial EEG . … before scalp EEG recording, precluding simultaneous scalp and intracranial

---

### [204] Psychobiological Correlates of Instructed Deceptive Responding: An Exploratory EEG Study

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-328X/16/8/1360&hl=zh-CN&sa=X&d=3034602131307564355&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoOrYqbyK63Euzb6iBoU74Z7&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=8&folt=kw-top
**作者**: AT Bratu, F Zamfirache, NI Darie, G Dumitru… - Behavioral Sciences, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In the present study, we investigated frontal EEG activity during intentional instructed … A subsample of 48 participants subsequently completed a controlled truth–deception task while EEG … EEG analyses suggested an increase in right-frontal

---

### [205] EEG inter-brain synchrony in social interaction: A systematic review and meta-analysis of condition effects and outcome associations

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0301051126001808&hl=zh-CN&sa=X&d=12132616900311258346&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoPfbaOETV79K1Ezyy11gDWG&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=1&folt=kw-top
**作者**: L Jiang, Q Zou, S Yu - Biological Psychology, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We examined whether conditions related to social interaction enhance EEG IBS and whether EEG IBS is associated with external outcomes… used EEG hyperscanning or simultaneous scalp EEG recordings from at least two individuals

---

### [206] Cueless EEG imagined speech for subject identification: dataset and benchmarks

**链接**: https://arxiv.org/abs/2501.09700
**作者**: Ali Derakhshesh, Zahra Dehghanian, Reza Ebrahimpour, Hamid R. Rabiee
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [207] Linking EEG responses to ISO 12913 perceptual attributes within the Spanish SATP framework: an exploratory neurophysiological study

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0003682X26002902&hl=zh-CN&sa=X&d=11384991538183514979&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoPtpP1QkQV_wlhk3toNEAAs&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=3&folt=kw-top
**作者**: R García-Quesada, JT Valderrama, JV Manzano… - Applied Acoustics, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> responses to sound recorded via electroencephalography ( EEG ). Twelve participants were … activity was measured through multi-channel EEG to compute Power Spectral Density (PSD) … This study shows that data obtained via EEG

---

### [208] Subject-Aware Multi-Granularity Alignment for Zero-Shot EEG-to-Image Retrieval

**链接**: https://arxiv.org/abs/2604.17782
**作者**: Lin Jiang, Qingshan She, Jiale Xu, Haiqi Xu, Duanpo Wu, Zhenzhong Kuang
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [209] RMCCA-AE: A Residual Multimodal Canonical Correlation Analysis AutoEncoder for Emotion Recognition using EEG Signals and Eye Movement Data

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0950705126015558&hl=zh-CN&sa=X&d=8774350721241165293&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoPGsognlaUZFScjIfndjVVR&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=6&folt=kw-top
**作者**: M Zhu, Z Bai, Q Wu, Y Song, Q Gao - Knowledge-Based Systems, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalogram ( EEG )-based multimodal emotion recognition, an important topic in human-computer interaction, plays a crucial role in improving the reliability of emotion recognition and enhancing the understanding of the interaction between

---

### [210] EEG signatures of psychotropic medications: opportunities and challenges for translational psychiatry

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2352396426003154&hl=zh-CN&sa=X&d=7098651637520389407&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoOlj9Tkmi11hK6KKW8aJnC8&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=0&folt=kw-top
**作者**: L Krile, K Raeisi, AB Protzner - eBioMedicine, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Studies of brain function using electroencephalography ( EEG ) have provided important insights … 1 For example, EEG research has identified spectral trends that are common across groups … and suggesting that shared factors may contribute to

---

### [211] Variational Mixture of Graph Neural Experts for Alzheimer's Disease Recognition across Frequency Bands in EEG Brain Networks

**链接**: https://arxiv.org/abs/2510.11917
**作者**: Jun-En Ding, Anna Zilverstand, Shihao Yang, Albert Chih-Chieh Yang, Feng Liu
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [212] A Detrended Residual EEG Imaging Framework for Multi-type Sleep Apnea Classification using a Hybrid Learning Approach

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426017763&hl=zh-CN&sa=X&d=15925843677480854824&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoMBYHYezjqC9aKC_jsbqZMi&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=7&folt=kw-top
**作者**: S Fathima, M Ahmed - Biomedical Signal Processing and Control, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> and non-stationary nature of electroencephalogram ( EEG ) signals. This study proposes an EEG based hybrid framework integrating detrended … The framework employs variational mode decomposition combined with IMF-wise polynomial

---

### [213] Multi-channel EEG based layered sleep spindles detection algorithm using dual-branch BiLSTM

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426017799&hl=zh-CN&sa=X&d=16902375600001610415&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoOKdcIWbDOePtRalgJ-9guX&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=4&folt=kw-top
**作者**: D Hu, Z Jiang, T Jiang, F Gao, X Lou, J Cao - Biomedical Signal Processing and … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To effectively perform spindle wave detection by multiple channel information, the appropriate EEG channels should be selected according to the characteristics of spindle waves. All EEG data used in this study were obtained from the Children’s

---

### [214] Advanced deep learning techniques for EEG artifact removal: a comprehensive review and future directions

**链接**: https://scholar.google.com/scholar_url?url=https://www.tandfonline.com/doi/abs/10.1080/23080477.2026.2698472&hl=zh-CN&sa=X&d=12423276842787558720&ei=-xt-aqSWFte46rQPwpuCuAI&scisig=AM1tuoMaP5IRzD0NxlXlueA6JXWM&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AM1tuoMXBh2B6TYxyTxgvdAG7k6T&html=&pos=2&folt=kw-top
**作者**: P Yugandhar Reddy, E Sreenivasa Reddy - Smart Science, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> overview of the many kinds of artifacts affecting electroencephalogram ( EEG ) signals with an emphasis on brain– … EEG artifacts and related removal techniques that are published in the past 10 years served as the basis for the inclusion criteria

---

### [215] Beyond Local Power: Functional Connectivity Analysis for Subject-Independent Learning Style Recognition

**链接**: https://arxiv.org/abs/2608.12000
**作者**: Wiga Maulana Baihaqi, Indriana Hidayah, Sri Kusrohmaniah, Noor Akhmad Setiawan
**来源**: q-bio.NC cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Identifying individual learning styles optimizes pedagogical efficacy. While traditional questionnaires are structured, behavioral tracking methods require prolonged interaction log accumulation. To overcome these temporal constraints, this paper proposes an objective Electroencephalography (EEG) approach evaluating Phase Locking Value (PLV) connectivity against localized features across the Active-Reflective (AR) and Verbal-Visual (VV) Felder-Silverman dimensions. EEG signals were recorded from 28 participants during Raven's Advanced Progressive Matrices tasks. Support Vector Machine classification used Leave-One-Subject-Out Cross-Validation (LOSO-CV) alongside a 70:30 intra-subject split. The VV dimension achieved 70.00% subject-level accuracy driven by distinct fronto-occipital polarization. Conversely, the AR dimension yielded lower cross-subject generalizability (55.56%) due to overlapping executive networks and a "Systematic Neural Inversion" phenomenon, where stable individual c

---

### [216] Personalized Scorer Modeling: A Learning-Based Framework for Deriving Robust Sleep Stage Labels from Multiple Experts

**链接**: https://arxiv.org/abs/2608.12446
**作者**: Seyyed Ali Hoseini, Javad Baseri, Hamid Saadatfar, Edris Hoseini Gol, AmirHossein Eshghi
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sleep stage classification is important for the diagnosis and management of sleep disorders, yet most automatic staging studies evaluate models against a single reference hypnogram despite known inter-scorer variability. This study investigates whether multi-scored datasets can be used to construct more reliable reference labels from the collective behavior of multiple experts. We use the publicly available DOD-H and DOD-O datasets. EEG (C3-M2) and chin EMG signals were segmented into 30-s epochs, and 30 features were extracted from each modality, yielding 60 features for EEG+EMG. We propose a learning-based hypnogram (LBH) that models the stage-specific behavior of each scorer using confusion matrices derived from machine-learning models. After column normalization, these matrices estimate the probability of each true sleep stage given each scorer's label; probabilities are aggregated across scorers to assign the final label for each epoch. LBH was evaluated with random forest, suppor

---

### [217] Into the ORBIT for Time Series: Training Regimes for Foundation Models

**链接**: https://arxiv.org/abs/2608.13262
**作者**: Hongjie Xia, Yiding Liu, Yifan Hu, Peiyuan Liu, Zewei Dong
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) have advanced primarily through architectural innovation, while training regimes for large-scale heterogeneous corpora remain under-explored. As a result, pre-training distributions are often poorly controlled with respect to domain imbalance, context requirements, prediction horizons, and missingness. We introduce ORBIT (Omni-Range Bootstrap Incremental Training), a training paradigm that makes this distribution explicit and controllable. ORBIT combines Bootstrap Multi-Level Sampling, which controls dataset exposure and samples records, target variables, context windows, and prediction horizons, with Omni-Range Incremental Training, which varies context lengths and prediction horizons throughout a single training stage. Under ORBIT, we train Falcon-2.0, a simple univariate encoder-only Transformer with missingness-aware triple-channel patch tokenization and parallel patch prediction. We further introduce Rank-Guided Cross-Depth Alignment, a traini

---

### [218] LoRA-based Adaptation Alone Is Not Enough: Understanding the Limits of Foundation Models for Face Presentation Attack Detection

**链接**: https://arxiv.org/abs/2608.09633
**作者**: Peter Lorenz, Anjith George and Marcel S\'ebastien
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [219] Understanding Why Foundation Models Work for Diffusion-Generated Image Detection

**链接**: https://arxiv.org/abs/2608.12155
**作者**: Davide Cozzolino and Giovanni Poggi and Luisa Verdoliva
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models have recently emerged as powerful feature extractors for detecting AI-generated images, achieving strong generalization across generators and robustness to common image degradations. However, the reason behind their effectiveness is poorly understood. In this work, we investigate what cues are exploited by foundation-model-based detectors to distinguish real images from diffusion-generated ones. To this end, we design an ad hoc analysis protocol based on DDIM inversion. Given a real image we generate a sequence of synthetic copies by changing the depth of DDIM inversion. Even though most copies are semantically identical to the real reference, the detector score varies significantly across them due to subtle traces introduced by the diffusion synthesis, showing that its decision is not primarily driven by semantic failures. Through a frequency-swapping analysis, we further reveal that the discriminative cues exploited by the detectors are mainly localized in th

---

### [220] SpaRRTa: A Synthetic Benchmark for Evaluating Spatial Intelligence in Visual Foundation Models

**链接**: https://arxiv.org/abs/2601.11729
**作者**: Turhan Can Kargin, Wojciech Jasi\'nski, Adam Pardyl, Bartosz Zieli\'nski, Marcin Przewi\k{e}\'zlikowski
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [221] StarEmbed: Benchmarking Time Series Foundation Models on Astronomical Observations of Variable Stars

**链接**: https://arxiv.org/abs/2510.06200
**作者**: Weijian Li, Hong-Yu Chen, Nabeel Rehemtulla, Ved G. Shah, Dongho Kim, Dennis Wu 等 (9 人)
**来源**: astro-ph.SR astro-ph.IM cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [222] Foundation models for movement data: Are they ready for prime-time?

**链接**: https://arxiv.org/abs/2608.13316
**作者**: Alexander Br\"auer, Benjamin Cauchi and Nils Strodthoff
**来源**: eess.SP cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models (FMs) trained on large-scale accelerometer data have been proposed as general-purpose feature extractors for health monitoring, but systematic evidence of their advantages is lacking. We present the first comprehensive evaluation of four open-source accelerometer FMs against supervised baselines covering 19 tasks across the domains of activity recognition including activities of daily living, clinical monitoring, and physiological inference. We find task-dependent performance results: supervised models remain competitive with FMs on human action recognition (HAR), with no consistent advantage for either, while selected FMs lead on fall and stress detection and are the most robust to sensor-placement variation. As frozen feature extractors, FMs are strongest for demographic inference, whereas sleep staging performance remains near chance level for all models. The internal FM representations show strong similarity across layers, highlighting potential for future FM impr

---

### [223] Distillation of Foundation Models for Time-dependent PDEs

**链接**: https://arxiv.org/abs/2608.11937
**作者**: Daniel Musekamp, Boshra Ariguib, Andrei Manolache, Mathias Niepert
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for time-dependent partial differential equations (PDEs) are trained on large and diverse collections of physical systems and can generalize effectively to new downstream tasks. After fine-tuning on only a few trajectories from a target domain, they can achieve strong accuracy in low-data regimes. However, these models are typically large and computationally intensive, limiting their usefulness as fast surrogates for numerical solvers. We propose Teacher Rollout Extension (TREX), a knowledge distillation framework that transfers the predictive capability of a pretrained foundation model into a compact and efficient student. Starting from a fine-tuned teacher, TREX augments limited downstream data by generating long synthetic trajectories through teacher rollouts, optionally with periodic noise injection. This procedure samples from the teacher-induced rollout distribution without requiring explicit knowledge of the initial-condition distribution, while exposing the st

---

### [224] Zero-OVCD: Bridging Training-Free Foundation Models and Pseudo-Label Learning for Open-Vocabulary Change Detection

**链接**: https://arxiv.org/abs/2608.11663
**作者**: Daifeng Peng, Yuanke Peng, Haiyan Guan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-vocabulary change detection (OVCD) enables the identification of user-specified land-cover changes in bitemporal remote sensing images, but existing training-free pipelines remain vulnerable to inaccurate candidate masks, ambiguous semantic assignments, and accumulated inference errors. To address these issues, we propose Zero-OVCD, a two-stage framework that requires no pixel-level annotations from the target domain. In the first stage, high-quality change pseudo-labels are generated through complementary candidate-mask refinement, multiscale semantic similarity fusion with margin-based reliability filtering, and response-guided mask correction and completion. These components jointly suppress noisy candidates, enhance mask-level semantic discrimination, and recover missed change regions. In the second stage, a change detector is trained using the generated pseudo-labels, while checkpoint voting and high-agreement sample selection are introduced to mitigate residual pseudo-label 

---

### [225] How Good are Foundation Models in Longitudinal MRI Disease Progression Reasoning?

**链接**: https://arxiv.org/abs/2608.13309
**作者**: Wafa Al Ghallabi, Ritesh Thawkar, Sara Ghaboura, Omkar Thawakar, Numan Saeed, Dana Al Nuaimi 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Magnetic Resonance Imaging (MRI) interpretation is fundamental to clinical decision-making, requiring radiologists to integrate multi-view anatomical planes across sequential timepoints while precisely localizing interval changes. However, existing vision-language benchmarks remain confined to single-timepoint, single-view interpretation, failing to capture the temporal-spatial reasoning essential to radiologic practice. We introduce the Time-Aware Multi-View MRI Benchmark, an evaluation framework unifying multi-view anatomical input, temporal reasoning across longitudinal scans, and structured localization guidance. The benchmark comprises 3,920 expert-verified question-answer pairs derived from 890 patients across over 3,200 longitudinal MRI timepoints, drawn from seven clinical cohorts covering glioblastoma, neurodegeneration, vestibular schwannoma, and brain metastases, in open-ended, multiple-choice, and binary formats, requiring models to identify anatomical regions of maximal ch

---

### [226] Market-Information-Aware Gated-LoRA of Foundation Models for Transferable Day-Ahead Electricity Price Forecasting

**链接**: https://arxiv.org/abs/2608.11359
**作者**: Hang Fan, Wei Wei, Shengwei Mei
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electricity price forecasting is crucial for market participants but remains difficult because prices are volatile, market-specific, and closely tied to anticipated system conditions. Existing supervised methods depend largely on market-specific historical data, limiting their use in newly established or data-scarce markets. This paper proposes a market-information-aware adaptation framework that transfers the Chronos-2 time-series foundation model to day-ahead electricity price forecasting. It first constructs a multi-source market information (MSMI) interface aligning 7-day price context with pre-clearing supply--demand, reserve, maintenance, generator-capacity, and intertie variables, and then trains a source-domain gated low-rank adapter (LoRA), updating about $1\%$ of model parameters without target-market labels. The gate scales the frozen source adapter according to reserve-tightness and operating-state signals. A leave-one-market-out protocol is adopted for evaluating cross-mar

---

### [227] SAFE-SVD: Sensitivity-Aware Fidelity-Enforcing SVD for Physics Foundation Models

**链接**: https://arxiv.org/abs/2605.17985
**作者**: Chengjie Hong, Feixiang He, Yiheng Zeng, Lulu Kang, He Wang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [228] A Distributional Robustness Margin For Pathology Foundation Models

**链接**: https://arxiv.org/abs/2607.25497
**作者**: Cl\'ement Grisi, Jeroen van der Laak, Geert Litjens
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [229] Pathryoshka: Compressing Pathology Foundation Models via Multi-Teacher Knowledge Distillation with Nested Embeddings

**链接**: https://arxiv.org/abs/2511.23204
**作者**: Christian Grashei, Christian Brechenmacher, Rao Muhammad Umer, Jingsong Liu, Carsten Marr, Peter J. Sch\"uffler 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [230] Benchmark-Based Comparative Assessment of Publicly Benchmarked Indian Foundation Models: A Capability and Evaluation-Maturity Framework

**链接**: https://arxiv.org/abs/2608.11891
**作者**: Avinash Agarwal and Vridhi Jain
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Governments increasingly fund indigenous foundation models to strengthen national AI capability, digital sovereignty, and multilingual computing. Assessing the progress of such national ecosystems is complicated by inconsistent benchmark reporting, proprietary evaluation methodologies, and rapidly evolving model releases. This paper presents a structured, benchmark-based comparative assessment of publicly benchmarked Indian foundation models against global frontier and comparable-scale models, across eight capability domains: general-purpose reasoning, coding and software engineering, agentic AI and computer use, cybersecurity, vision and image understanding, video and multimodal understanding, scientific research, and Indic language capability. Using only publicly reported benchmark results, we find that Indian models achieve strong scores on established benchmarks such as MMLU and MATH-500. However, these benchmarks are now widely regarded as saturated, and frontier developers no lon

---

### [231] Accelerating Time Series Foundation Models with Speculative Decoding

**链接**: https://arxiv.org/abs/2511.18191
**作者**: Pranav Subbaraman, Fang Sun, Jinxi Yu, Yue Yao, Huacong Tang, Xiao Luo 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [232] Earth observation embeddings are effective sub-grid descriptors for probabilistic weather downscaling

**链接**: https://arxiv.org/abs/2608.12271
**作者**: Pedro Sousa (1), Will Tebbutt (2), Sadiq Jaffer (1), Robin Young (1), Anil Madhavapeddy (1), Richard E. Turner (2) ((1) Department of Computer Science 等 (9 人)
**来源**: cs.LG physics.ao-ph
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Global weather reanalyses and forecasts resolve the evolving atmospheric state on coarse grids, but site-specific applications require predictions at arbitrary locations where near-surface conditions also depend on unresolved terrain and land-surface properties. Existing probabilistic downscalers address this gap using hand-crafted topographic descriptors. We ask instead whether Earth observation foundation models can provide transferable sub-grid surface representations for probabilistic weather downscaling. We augment a convolutional conditional neural process that downscales coarse ERA5 reanalysis fields at ~25 km resolution with a learned local surface descriptor, obtained by compressing a patch of TESSERA embeddings at 10 m resolution. Although these embeddings summarise surface conditions over annual timescales, they improve downscaling of instantaneous 2 m temperature and 10 m wind speed by encoding persistent surface properties that capture a location's departure from the coars

---

### [233] Repurposing RGB-based Foundation Model for Depth Estimation on Thermal Images Using Hierarchical Supervision

**链接**: https://arxiv.org/abs/2608.11564
**作者**: Jie Hong, Tingtian Li, Xuesong Li, Xiao Li
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depth estimation from thermal images is highly valuable for robotic applications in adverse conditions, such as nighttime and rainy weather. Recent studies have sought to transfer knowledge from RGB-based foundation models to thermal modalities, yet the rich hierarchical representations these models encode remain underutilized. To address this limitation, we propose RGB-HS, a novel framework for thermal-image depth estimation that leverages hierarchical supervision from an RGB-based foundation model. Specifically, we first replace the baseline thermal encoder with a foundational model and introduce a parallel RGB branch that also employs a foundational model as an encoder of the same architecture, taking RGB images as input. The alignment is then performed across multiple levels between the tokens of the two encoders, allowing the thermal student branch to capture both structural precision and semantic abstraction from the RGB teacher branch. Furthermore, we introduce verification to r

---

### [234] P2Fusion: Prompt-based Progressive Infrared-Visible Image Fusion via Dual-Prior Distillation

**链接**: https://arxiv.org/abs/2608.13045
**作者**: Yi Shi, Huichao Xie, Yuqing Wang, Mingyu Wang, Kaihui Yang, Yu Liu 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Infrared-visible image fusion (IVIF) is pivotal for multimodal perception, yet reconciling the inherent information disparity between thermal and textural features remains a fundamental challenge. Existing prior-guided methods often rely on static constraints that induce optimization conflicts or utilize extrinsic semantic priors from large-scale foundation models (e.g., CLIP/DINO), which frequently fail to exploit the intrinsic modality characteristics essential for high-fidelity fusion. To address these issues, we propose P2Fusion, a prior-guided distillation-based framework that reformulates IVIF via dual intrinsic prompts. Instead of imposing hard-coded penalties, we distill image-intrinsic priors, thermal saliency and spatial quality, into learnable dynamic regulators. Specifically, a Teach-to-Fuse mechanism provides dual-granularity progressive guidance, coupled with a Gated Dynamic Expert Recalibration (GDER) module for decoupled feature refinement. This design enables the netwo

---

### [235] Do You See What You Draw? A Semantic Closed-Loop Framework for Holistic Evaluation of Unified Multimodal Models

**链接**: https://arxiv.org/abs/2608.11907
**作者**: Hao Zhang, Jiaxin Qi, Zhijiang Tang, Jianqiang Huang
**来源**: cs.CV cs.AI
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Vision-Language Models increasingly aim to integrate visual generation and understanding within a single parameter space, evaluating such structural unification in a cohesive manner remains a critical challenge. Current evaluation protocols predominantly treat generative and discriminative capabilities as separate tasks, leaving a gap in system-level evaluation for unified multimodal models (UMMs). In this work, we propose Self-Generative-Understanding (SGU), a novel, annotation-free evaluation framework that probes the integrated capabilities of unified models through a semantic closed-loop challenge. Without requiring new annotations, SGU leverages the dual understanding-and-generation abilities of UMMs by asking them to first perceive an image and produce a textual description, subsequently reconstruct a visual context based on that description, and finally perform reasoning over the self-generated output. This pipeline provides a zero-cost testbed that yields an integrated

---

### [236] GS$^{2}$CI: Robust Gaussian Splatting For Snapshot Compressive Imaging via Large Vision Model Priors

**链接**: https://arxiv.org/abs/2608.13502
**作者**: Yanming Yang, Chenxi Song, Ping Wang, Xin Yuan, Chi Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Snapshot Compressive Imaging (SCI) offers an efficient solution for high-speed video acquisition and, under exposure-time camera--scene relative motion, multi-view scene capture by compressing temporal or spatial information into a single 2D measurement. While recent studies have explored SCI for 3D scene reconstruction, existing methods struggle with significant challenges due to information loss, limited viewpoint diversity, and the computational burden of jointly optimizing 3D representations and camera poses. In this work, we propose a novel framework that reconstructs high-quality 3D scenes from a single SCI measurement by leveraging 3D Gaussian Splatting (3DGS) and the powerful priors of large-scale vision foundation models (VFMs). Our primary reconstruction combines measurement-derived 3D VFM initialization with SCI-aware Gaussian optimization. After coarse-stage convergence, an auxiliary 2D VFM provides pseudo-view supervision at synthesized viewpoints for local appearance refi

---

### [237] Towards Context-Aware Clinical Motion Understanding in Daily Living at Home: Freezing of Gait Detection with Egocentric Vision

**链接**: https://arxiv.org/abs/2608.13283
**作者**: Vayalet Stefanova, Diwas Lamsal, Margot Genbrugge, Maxim Yudayev, Christian Schlenstedt, Moran Gilat 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding motion in daily living requires context beyond kinematics, because similar inertial patterns during activities of daily living (ADLs) can reflect intentional stopping, object interaction, or pathological movement impairment. Egocentric vision provides task-related context that may help disambiguate these cases. We investigate this challenge through freezing of gait (FOG) detection in Parkinson's disease (PD), a symptom strongly influenced by contextual factors during ADLs. Using synchronized egocentric video, wearable IMUs, and expert-annotated FOG labels collected from 13 PD participants in their homes, we evaluate frozen representations from pretrained ego-video and time-series foundation models, alongside an IMU-based TCN trained from scratch, under leave-one-subject-out evaluation. The IMU-based TCN achieved the strongest event-detection performance, reaching 42.3 F1 and 83.0 AUROC, compared with 32.6 F1 and 77.2 AUROC for V-JEPA2 ego-video features. Although ego-vide

---

### [238] Intern-S2-Preview: Scientific Agentic Foundation Model

**链接**: https://arxiv.org/abs/2608.13505
**作者**: Lei Bai, Jiaqi Cao, Chiyu Chen, Guanzhou Chen, Kai Chen, Guangran Cheng 等 (10 人)
**来源**: cs.LG cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific discovery increasingly requires AI systems that can reason over scientific evidence of heterogeneous modalities, interact with scientific tools and environments, and sustain progress across long task horizons. We present Intern-S2-Preview, a series of scientific agentic foundation models designed to support multimodal scientific understanding, reasoning, generation, and long-horizon tasks. The training pipeline begins with scientific multimodal pre-training over rendered scientific documents, interleaved image-text data, and diverse scientific corpora. Starting from the pretrained checkpoint, we apply a unified post-training pipeline consisting of supervised fine-tuning, scalable multi-task reinforcement learning (RL), black- and white-box agentic RL, and on-policy distillation. This pipeline is supported by practical techniques that improve rollout and training stability and efficiency, including partial rollout with off-policy correction, adaptive length regularization, on

---

### [239] How to Spend Your Oracle Budget: Practical Guidance for Protein Structure Prediction Models

**链接**: https://arxiv.org/abs/2608.12192
**作者**: Aleksandra Kalisz, Jack Simons, Krisztina Sinkovics, Noam Ghenassia, Shikha Surana, Henry Moss 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for protein structure prediction remain unreliable on certain targets. External oracles can flag and correct these failures, but biological oracles are expensive, making oracle budget a critical constraint. Existing guidance methods, such as FK-steering, DPO, and Best K-of-N sampling, differ in how they spend this budget, yet no systematic comparison exists to guide method selection. To bridge this gap, we benchmark these methods alongside the recently proposed Optimisation Over Outputs (O3), which applies off-the-shelf optimisers within a generative model's latent subspace. We extend the usage of O3 to protein structure prediction models. Overall, our work provides the first practical reference for oracle budget-aware guidance. Our evaluation on two protein targets, calmodulin (1CLL) and E. coli aspartate transcarbamoylase (9EEH), reveals that no single method consistently dominates across all budgets and oracles. Specifically, O3 proves most effective at low oracle 

---

### [240] CardioState-JEPA: Delay-Aware Cross-Modal Learning of a Shared Cardiac Representation

**链接**: https://arxiv.org/abs/2608.12944
**作者**: Hamza Shafiq, Hung Manh Pham, Bin Zhu, Pan Zhou, Jun Hu, Aaqib Saeed
**来源**: cs.LG eess.IV stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electrocardiography (ECG), photoplethysmography (PPG), and phonocardiography (PCG) provide complementary views of the same cardiac cycle, yet existing cardiac foundation models are trained for a single sensing modality, leaving the shared physiology across sensors unexploited. We introduce CardioState-JEPA, a cardiac foundation model to learn a single shared representation jointly across ECG, PPG, and PCG, built on a physiology-aware joint-embedding predictive architecture. The model maps heterogeneous waveforms into a common token space, processes them with a single shared Transformer encoder, and learns by predicting masked latent cardiac states, placing the pretraining target on shared physiology rather than sensor-specific waveform appearance. To handle the temporal offsets between electrical, mechanical, and hemodynamic events, cross-modal prediction uses a learned delay aligner that matches signals at the corresponding cardiac time. Because synchronized multi-sensor recordings ar

---

### [241] Balanced Adaptive Prototype Selection for Scalable TabPFN Inference on Large-Scale Tabular Data

**链接**: https://arxiv.org/abs/2608.12989
**作者**: Mahboobe Jadid, Melika Rezaye Garkani, and Ali Mousavi
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained tabular foundation models have demonstrated strong predictive capability; however, their application to large-scale datasets remains constrained by the limited inference context. This paper introduces Balanced Adaptive Prototype Selection (BAPS), a framework for constructing compact, information-preserving contexts for scalable TabPFN inference. Without modifying or retraining the pretrained model, BAPS jointly preserves representative structure, informative decision boundaries, local density, class balance, and feature-space diversity. Experiments on the million-row HIGGS and SUSY datasets show that 512 prototypes retain strong predictive performance and reliable calibration, corresponding to an approximately 1,953-fold context compression. All experiments were conducted on an Intel Core i7 CPU with 16 GB RAM and no GPU acceleration. These findings establish effective context construction as a practical mechanism for extending pretrained tabular foundation models to million

---

### [242] Evaluation of Clinically Steerable Retinal Image Generation from Foundation Model Latent Spaces

**链接**: https://arxiv.org/abs/2608.13455
**作者**: Zuzanna A. Wakefield-Sk\'orniewska and Bart{\l}omiej W. Papie\.z
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical foundation models learn latent representations of clinically meaningful phenotypes, yet their ability to support controllable image generation remains largely unexplored. We evaluate four retinal foundation models within the representation tokenizer framework and examine whether demographic and clinical information encoded in latent representations from foundation models is preserved during synthetic image generation. We show that generated representations and images faithfully inherit phenotype information when evaluated within their originating foundation models, consistently outperforming conventional latent diffusion on multiple downstream prediction tasks. However, these gains largely disappear when evaluated using classifiers trained on real images, revealing a previously uncharacterised synthetic-to-real representation gap. These findings demonstrate that foundation-model latent spaces provide a powerful substrate for controllable retinal synthesis while highlighting the

---

### [243] A Controlled Study of Self-Supervised Image and Video Pretraining under Limited Resources

**链接**: https://arxiv.org/abs/2608.13183
**作者**: Brun\'o B. Englert, Gijs Dubbelman
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual foundation models are a cornerstone of image and video understanding but typically require large amounts of data and computation. The current scale required for pretraining visual foundation models may be unsustainable or unnecessary, and significant benefits arise when effective models can be obtained with fewer resources. To better understand how self-supervised learning (SSL) objectives behave under resource constraints, we conduct a controlled study of image and video SSL objectives under matched data, architecture, and compute budgets. We compare contrastive, reconstruction, feature-prediction, and diffusion objectives and evaluate both standalone and jointly trained image-video SSL formulations across a diverse set of image and video understanding tasks. Our results show that DINOv2-style pretraining consistently provides the strongest overall performance under limited resources. Furthermore, combining DINOv2 with video SSL objectives such as VideoMAE substantially improve

---

### [244] Self-Evolving Embodied Agents via Skill-Harness Evolution

**链接**: https://arxiv.org/abs/2608.11350
**作者**: Peidong Wang, Zhiming Ma, Ying Chang, Xufang Luo, Xiaocui Yang, Shi Feng 等 (8 人)
**来源**: cs.CL cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embodied agents are increasingly built as systems around foundation models, where performance depends not only on model weights but also on the skills, context, action interfaces, and execution harness surrounding the model. While supervised fine-tuning and reinforcement learning can adapt agents to new environments, they require additional data, rewards, and training runs; meanwhile, many train-free code-centric approaches rely on programmable robot APIs that may be unavailable in fixed-interface settings. We propose SHAPER, a self-evolving framework for train-free embodied adaptation that keeps model parameters frozen and improves the non-parametric agent system by evolving reusable skills and a context-code harness through target-environment rollouts. In SHAPER, the same frozen model can serve as both planner and optimizer, refining its external skills and context-code harness without parameter updates. We evaluate SHAPER on VLABench and ESI-Bench, covering embodied agents with diff

---

### [245] OmniScientist: An Omni-Modal Omni-Discipline AI Scientist

**链接**: https://arxiv.org/abs/2608.13558
**作者**: Bobo Li, Hao Fei, Tianjie Ju, Mong-Li Lee, Wynne Hsu
**来源**: cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in foundation models have enabled AI scientists to automate increasingly complete research workflows, from hypothesis generation and code execution to manuscript preparation. Yet workflow coverage alone does not provide access to the full evidence on which scientific discovery depends. Existing systems typically reason over text, code, labels, or precomputed summaries, leaving scientifically decisive spatial, temporal, cross-channel, and procedural relations unavailable to the agent. We introduce OmniScientist, an end-to-end, omni-modal AI scientist that conducts multidisciplinary research directly from heterogeneous raw evidence. A perception layer and 3 autonomous agents for ideation, experiment, and writeup operate within a deterministic pipeline, allowing observations to shape research questions, experimental decisions, and final claims throughout the research lifecycle. By running idea, rigour, and claim checks in code, the system enforces novelty screening, statis

---

### [246] CT-$\Delta$Bench: A Benchmark for Longitudinal 3D Medical Imaging Difference Reporting with Vision-Language Models

**链接**: https://arxiv.org/abs/2608.11534
**作者**: Kegeng Tang, Jingbo Wang, Shaogang Ren, Zihao Wang
**来源**: cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In medical imaging, the clinical value of Computed Tomography (CT) lies not only in depicting current disease status, but crucially in enabling longitudinal comparison of serial scans to determine disease evolution, a process that underpins response assessment, recurrence detection, and ongoing patient management. Yet, despite this central role of temporal comparison in clinical decision-making, existing medical foundation models remain largely confined to single-study understanding, leaving temporally grounded cross-examination insufficiently addressed. To address this gap, we study longitudinal imaging difference reporting, a task in which a model takes two temporally separated scans from the same patient and generates a clinically meaningful report describing interval changes between them. We introduce CT-$\Delta$Bench, a dedicated benchmark for this task with patient-level splitting to prevent information leakage. To better evaluate this task beyond surface-level text similarity, w

---
