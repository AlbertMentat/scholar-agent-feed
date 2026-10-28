# 📑 论文索引 - 2026-10-29

共 162 篇论文

---

### [1] Distributed LLM Inference via Communication-Efficient Speculative Decoding

**链接**: https://arxiv.org/abs/2610.35957
**作者**: Joohyun Shin, Byeonghyeon Park, Keumseo Ryum, and Joonhyuk Kang
**来源**: cs.LG cs.IT eess.SP math.IT
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distributed speculative decoding has emerged as a promising approach for device--server collaborative large language model (LLM) inference, but its decoding speedup is often limited by the vocabulary-scale communication overhead. In existing distributed speculative decoding methods, exact rejection sampling requires transmitting full token distributions over the LLM vocabulary between the device and the server, which becomes costly in bandwidth-constrained environments. To address this issue, we propose DISCO, a communication-efficient framework for distributed speculative decoding, that eliminates vocabulary-scale distribution transfer while preserving the exact target distribution. DISCO achieves this by introducing a server-side replica of the draft small language model (SLM), which enables the server to locally obtain the draft-side distribution required for rejection sampling. As a result, DISCO exchanges only drafted token indices and scalar probability values between the device 

---

### [2] 3D-SceneQ: Empowering 3D LLM With Query-Guided Adaptive Pruning and Multi-Modal Feature Enhancement

**链接**: https://arxiv.org/abs/2610.37202
**作者**: Yongqi Shan, Lu Zhang, Jiazuo Yu, Yunzhi Zhuge, Huchuan Lu
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current 3D scene understanding pipelines typically concatenate vast numbers of 3D object tokens with text tokens and feed the resulting sequence to a Large Language Model (LLM). However, existing 3D-LLMs for scene understanding encounter two major limitations: (i) excessive inclusion of task-irrelevant object data, introducing noise that reduces reasoning accuracy and increases hallucinations; and (ii) reliance solely on point cloud data, which inherently lacks the rich semantic information available in complementary 2D modalities, such as color, material properties, texture, and high-level contextual relationships. To address these challenges, we introduce 3D-SceneQ, a 3D LLM that unifies adaptive token pruning with multimodal semantic enrichment, markedly advancing scene understanding, reasoning, and grounding. Specifically, we propose a Query-Guided Adaptive Pruning (QGAP) module that adaptively selects task-relevant objects based on the intended meaning of user instructions, levera

---

### [3] AnalogScout: Simulation-Efficient PVT-Aware Analog Sizing with LLM Agents

**链接**: https://arxiv.org/abs/2610.37319
**作者**: Yichen Long, Keren Zhu
**来源**: cs.AR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog device sizing must satisfy all specifications across process, voltage, and temperature (PVT) corners to ensure tape-out success, but simulating every candidate at all corners dominates the sizing time and slows design iteration. Conventional surrogate-based optimizers search the sizing space directly, while recent large language model (LLM) agents add circuit knowledge to designs but still delegate the sizes to global optimizers. Both learn the circuit response from repeated multi-corner SPICE simulations and optimize on top of it, which becomes expensive under a limited simulation budget. Providing an agent with reusable verified designs and sizing sub-blocks analytically could save most of this budget. We propose AnalogScout, a simulation-efficient PVT-aware sizing framework driven by an LLM agent. Combining elite-design reuse, analytic gm/Id local sizing and global refinement under full-corner verification, AnalogScout reduces power by 43.3% relative to the evolution strategy

---

### [4] From Generation to Scoring: Scaling LLM-Based Semantic Labeling at LinkedIn

**链接**: https://arxiv.org/abs/2610.36383
**作者**: Jian Sheng, Sriram Vasudevan, Sundara Raman Ramachandran, Yang Hu, Junyu Zhou, Xiaojing Ma 等 (10 人)
**来源**: cs.LG cs.DC cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For efficiency, industrial large language model (LLM) labelers often pack many candidate labels into one prompt and generate a YES/NO answer for each, even when each decision depends only on the entity and one candidate. Generating these independent decisions as one answer list couples them, spends decoding on the list, and relies on the list being well-formed. In this paper, we present an end-to-end recipe that reformulates the labeler as semantic scoring, fine-tuning it on single-candidate prompts to return each decision as one answer-token score from a prefill-only pass. We also adapt Multiple-Item Scoring (MIS) to score hundreds of candidates in one sequence with attention masked between them. Deployed for profile qualification labeling at LinkedIn, semantic scoring changes at most 0.01% of decisions when candidates are reordered and matches the agreement with reference labels that packed generation reaches only with about 4.7x as many training pairs. The MIS-based stack raises thr

---

### [5] Where Should the Evaluation Budget Go in LLM-Driven Agent Scaffold Evolution?

**链接**: https://arxiv.org/abs/2610.37276
**作者**: Sichun Luo, Yi Huang, Mukai Li, Haochen Luo, Guanzhi Deng, Haibo Wang 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.NE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-driven agent scaffold evolution improves agent workflows through iterative candidate generation and evaluation. Evaluation both guides subsequent search and determines the final scaffold, but evaluating every candidate on the full task set incurs substantial execution costs. We investigate how evaluation budgets can be allocated across these two roles. Our experiments show that sparse feedback can sustain productive evolution, while additional targeted evaluation improves final selection. Replay analyses further show that shared informative items and a common scoring reference support comparisons among closely matched candidates. Motivated by these findings, we propose \method, an evaluation allocation framework that combines sparse search-time feedback with targeted final confirmation. A short fully evaluated warm-up establishes a shared informative core and calibrates a response model whose item parameters remain fixed during search. After search, \method r

---

### [6] Nemotron-Labs-Diffusion-Uni: Elastic Self-Refining Unified Diffusion LLM with Cross-Paradigm On-Policy Distillation

**链接**: https://arxiv.org/abs/2610.36466
**作者**: Shufan Li, Hanrong Ye, Greg Heinrich, Yonggan Fu, Haotian Zhang, Sifei Liu 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose Nemotron-Labs-Diffusion-Uni (NLD-Uni), a unified discrete diffusion large language model (DLLM) for visual understanding and generation tasks. Compared with prior unified diffusion models, NLD-Uni introduces two major innovations. First, we propose a unified cross-paradigm on-policy distillation (OPD) framework that successfully transfers the visual understanding ability of autoregressive VLMs and visual generation ability of continuous flow models, to a unified DLLM. Second, NLD-Uni incorporates a novel progressive self-refining diffusion process that gradually corrupts each token across multiple steps during training, as opposed to adopting the conventional masked diffusion formulation that directly corrupts a clean image token to an uninformative mask token. At inference, this design allows NLD-Uni to make intermediate commit to a token, enabling progressive self-refinement for better visual quality. Through extensive experiments, we show that NLD-Uni achieves state-of-th

---

### [7] Grounding LLM Agents in Business Processes: Process-Aware Knowledge Graphs for Reliable Multi-Step Service Invocation

**链接**: https://arxiv.org/abs/2610.37242
**作者**: Saiful Khan and Afrah Farea
**来源**: cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents that call enterprise APIs must select the correct endpoints, follow process order, use valid payload keys, and choose coded values from predefined lists. However, current retrieval-augmented service discovery treats endpoints independently and therefore misses process and schema constraints. We address this limitation by integrating Open Data Protocol (OData) metadata and Business Process Model and Notation (BPMN) reference processes in a typed property graph. A hybrid retriever identifies candidate endpoints using dense embeddings and follows process edges to retrieve subsequent endpoints. We evaluate the method on 42 enterprise services with process-chain ground truth. For queries with low lexical overlap between the query and downstream entities, it improves Recall@3 by 5.7 points (n=74), with consistent gains across embedding models and cut-offs. It matches dense retrieval on other queries and provides no improvement on OpenAPI services without a p

---

### [8] AutoVend: Benchmarking LLM Agents on Long-Horizon Autonomous Vending Operations

**链接**: https://arxiv.org/abs/2610.36980
**作者**: Qiming Shi, Yikun Li, Beidi Luan, Rui Sun, Yan Ma, Jing Li 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are extending agent-mediated commerce on the Web from shopping for consumers to operating businesses for sellers. In online-to-offline (O2O) commerce, decisions are issued through Web-based platforms but realized through costly physical execution. Evaluating such agents requires going beyond individual transactions to ask whether decisions made online turn into sustained economic returns. We introduce AutoVend, a benchmark in which one LLM agent manages 20 vending machines across five site types through a Web-based operating interface for 180 simulated days. Its data-grounded simulator combines a shared warehouse, procurement lead times, paid replenishment, inventory expiration, and recurring operating costs. We evaluate five LLM agents against a rule-based inventory-control baseline and diagnose their site coordination, execution, and performance over time. Four of five evaluated LLM agents fall short of this baseline, and returns per dollar of infere

---

### [9] Advancement or Acceleration? How Data Curation Improves LLM Training

**链接**: https://arxiv.org/abs/2610.36983
**作者**: Jiaxing Wang, Zicheng Zhang, Deping Xiang, Jin Xu, Yong Li, Chao Liu 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While data curation is widely credited with improving large language model training, a basic question remains unresolved: does curation expand what a model can ultimately learn, or merely reach the same solution faster? In this paper, we formalize this distinction between advancement (improving the attainable performance) and acceleration (reaching the same performance with less data). Through an analytic characterization and real-world LLM experiments, we show that advancement requires a correctable train-target gap. When the baseline training and target objectives coincide, no curation policy improves the endpoint, although curation may still accelerate training. This reframes advancement as a property of the curation task rather than the curation method. Under a common gap-centric view of data mixture and selection, we operationalize this condition as the $\Delta$-test, an observable discrepancy between the uncurated baseline's training and target losses that is computable prior to 

---

### [10] Benchmarking LLM Agents for Behaviorally Adequate Test Generation from Software Requirements

**链接**: https://arxiv.org/abs/2610.36584
**作者**: Binhang Qi, Yiming Liu, Yun Lin, Yangjie Zhou, Hailong Sun, Jin Song Dong
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model agents increasingly compile natural-language requirements into repository-level code, requirement-to-test generation grows in importance to provide validation constraints (or harness) to guide code generation. Yet it remains unclear whether current agents can generate tests that validate the required behavior when the implementation of that behavior is withheld. Existing test-generation benchmarks mostly focus on white-box testing, whereas the requirement--test-related study usually requires evaluation on semantic alignment between the given documents and the generated tests. We introduce Req2Test-Bench, a benchmark containing 5,086 execution-validated instances recovered from developer-authored behavior-driven development (BDD) artifacts in 8 open-source projects, spanning 5 programming languages and 4 BDD frameworks. Each instance pairs a natural-language requirement in Gherkin with its developer-written Test Implementation. Given the requirement, target inter

---

### [11] GPU Power Modelling for LLM Serving With Serving‐Visible Information

**链接**: https://scholar.google.com/scholar_url?url=https://ietresearch.onlinelibrary.wiley.com/doi/pdf/10.1049/ein2.70038&hl=zh-CN&sa=X&d=6838202170298371130&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv6_zib6KrCNZMFR9P0xOcCy&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=4&folt=kw-top
**作者**: L Wang, N Tian, L Xu, Q Guo - Energy Internet, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Large language model ( LLM ) serving is becoming an increasingly power‐relevant workload in modern data centres, whereas offline serving analysis, trace replay and simulation often lack deployment‐time hardware telemetry. This paper quantifies

---

### [12] WAKMan: Workload Aware KVCache Manager

**链接**: https://arxiv.org/abs/2610.36355
**作者**: Suhas Kumar Morisetty, Vaibhavi Lokegaonkar, Sachin Mathew Varghese, Wesley Harris
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prefix caching enables a Large Language Model (LLM) servers to reuse the Key-Value (KV) states and accelerate prefill computation stage for requests that share a prefix with earlier prompts, thus reducing latency and serving cost. With limited memory resource, the KV cache eviction policy becomes a decisive factor in determining the overall benefits of prefix caching. Production traffic may have single-turn, multi-turn, agentic, or a mixture of any combination of these request types. Our findings indicate that agentic steps return within seconds and favor recency, while popular prompts and long conversations return after many other requests and favor frequency. Across 20 mixes, no single policy is always best: vLLM's default strategy LRU provides 12% higher cache hits as compared to the frequency-oriented S3FIFO on agentic-heavy mixes but trails it by up to 22% elsewhere, and even a single workload parameter can flip the winner even for any particular mix. We present WAKMan, a workload

---

### [13] LLM Hallucination Detection via Low-rank Multilinear Decomposition

**链接**: https://arxiv.org/abs/2610.36191
**作者**: Devansh Sharma, Faizul Rakib Sayem, Shahana Ibrahim
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) frequently generate fluent yet factually incorrect responses, raising concerns about their reliability. Recent hallucination detectors increasingly exploit internal representations, but extracting informative signals from high-dimensional hidden states remains challenging. Existing approaches often rely on selected activations or pooling-based compression, potentially overlooking discriminative information distributed across Transformer layers, feature modes, and tokens. We propose LOTUS (Low-rank Order-statistic TUcker-based Subspace learning), a multilinear low-rank decomposition framework for hallucination detection that extracts compact representations from LLM hidden states while reducing dependence on labeled data. Our approach first summarizes variable-length token representations using complementary statistical descriptors that capture peak activations, activation distributions, and cross-layer changes. We then leverage low-rank multilinear decompos

---

### [14] EffiBench-X: A Multi-Language Benchmark for Measuring Efficiency of LLM-Generated Code

**链接**: https://arxiv.org/abs/2505.13004
**作者**: Yuhao Qing, Boyu Zhu, Mingzhe Du, Zhijiang Guo, Terry Yue Zhuo, Qianru Zhang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] The Inbox as a Coordination Primitive for LLM Agent Societies

**链接**: https://arxiv.org/abs/2610.36264
**作者**: Karthik Sreedhar, Leo Yuan, Pradyumna Chari, Ramesh Raskar
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents increasingly coordinate in large groups, and current agent protocols focus on delivering messages. For these agents, however, the scarce resource is not delivery but reading: every message costs tokens, and the context is finite. Current infrastructure works by push: the sender decides when a message enters the recipient's context, so the recipient reads in arrival order and drops the oldest messages once its context is full. We study the alternative, pull, in which messages wait in an inbox outside the context and the recipient's own rules decide what it reads and keeps. We argue that the inbox is a coordination primitive: each agent sets its rules privately, and those rules decide whether other agents' requests reach it. In simulated societies of up to 16,000 agents, with every decision an LLM judgment, we report three findings. First, push fails as an agent takes part in more coordination at once: an agent leading 20 negotiations with a full memory proposes opt

---

### [16] PIVOT: Bridging Planning and Execution in LLM Agents via Trajectory Refinement

**链接**: https://arxiv.org/abs/2605.11225
**作者**: Tuo Zhang and Alin-Ionut Popa and Yan Xu and Rui Song and Dimitrios Dimitriadis
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] How Stable Are LLM-Generated Proofs Under Program Refactoring? A Stress Test for Verifiable Code Generation

**链接**: https://arxiv.org/abs/2610.36328
**作者**: Aravind Mandiga, Guoming Li
**来源**: cs.AI cs.LO cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarks for verifiable code generation usually test a proof against one fixed implementation. We ask whether the same proof remains valid after a program refactoring that preserves behavior. We introduce RefactorProof, which derives 458 Lean-certified variants from the 185 VERINA tasks that compile in our pinned environment while holding the specification and evaluated proof fixed byte-for-byte. VERINA supplies reference proofs for 46 tasks, all from its basic split; the primary model-versus-reference comparisons further match on 21-25 short, non-recursive tasks. Structural refactorings expose substantial brittleness across proof sources: task-normalized structural PSR is 4.3% for the supplied references and 13.3-26.8% for the specialized provers. On the matched tasks, specialized prover proofs nevertheless have higher overall unchanged-proof survival than the supplied reference artifacts: +15.6 points for DeepSeek-Prover-V2-7B, +18.8 for Goedel-Prover-V2-32B, and +20.3 for Goedel-P

---

### [18] Does The Way You Plan Matter? An Empirical Study of Planning Representations for LLM Web Agents

**链接**: https://arxiv.org/abs/2605.29927
**作者**: Alejandra Zambrano, Sara Vera Marjanovic, Imene Kerboua, Xing Han L\`u, Leila Kosseim
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] AzeroS: Extending LLM to Speech with Self-Generated Instruction-Free Tuning

**链接**: https://arxiv.org/abs/2601.06086
**作者**: Yiwen Shao, Wei Liu, Jiahong Li, Tianzi Wang, Kun Wei, Meng Yu 等 (7 人)
**来源**: cs.CL cs.SD eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Correction or Manipulation? Measuring Epistemic Vigilance in LLM Agents Under User Pressure

**链接**: https://arxiv.org/abs/2610.36453
**作者**: Nardine Basta, Venus Haghighi, Dali Kaafar, Amin Beheshti
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that answer questions and act on behalf of users must decide when to yield to a user who disagrees. Disagreement may correct a genuine error or may be an attempt at manipulation. Prior work shows that models frequently abandon correct answers when challenged by users, yet it remains unclear whether they distinguish correction from manipulation or merely differ in their propensity to concede. We examine this question across seven LLMs from four vendors in two studies, one on the answers agents give and one on the actions they take as customer-support agents whose policy permits account changes only for verified users. Simulated users push toward correct and incorrect answers with graded pressure. Following research on epistemic vigilance, the pressure either appeals to the source, such as claimed authority, or offers content the agent cannot verify, namely a cited source. Drawing on signal detection theory, we measure on a set of benchmark questions how much more readily each

---

### [21] Can Dialogue and Role Improve LLM Sidewalk Image Descriptions Across Mobility Groups?

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3797867.3829022&hl=zh-CN&sa=X&d=10098723954299248686&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv6cS0o1i4xe9B0qGcPmJ-RI&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=2&folt=kw-top
**作者**: A Miyata, K Go, R Matsubayashi, Y Ichikawa - Proceedings of the 28th International …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address these gaps, this study evaluates LLM -generated descriptions of sidewalk images … First, we empirically evaluate the potential of LLM -generated sidewalk image descriptions … Second, we reveal a wheelchair-centered default in

---

### [22] TextCloak: Safeguarding Data from Unauthorized LLM Fine-Tuning via RL-Driven Unlearnable Examples

**链接**: https://arxiv.org/abs/2607.28862
**作者**: Chengshuai Zhao, Pingchuan Ma, Dawei Li, Bohan Jiang, Zhiyuan Yu, Zhen Tan 等 (7 人)
**来源**: cs.CL cs.AI cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Pair Difficulty Matters: Rethinking Pairwise LLM-as-a-Judge Evaluation and Consistency

**链接**: https://arxiv.org/abs/2609.37577
**作者**: Bruno Brocai and Maria Becker
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] From single slices to whole studies: A scoping review of frontier LLM evaluation on CT and MRI and the case for study-level assessment

**链接**: https://scholar.google.com/scholar_url?url=https://econpapers.repec.org/article/oapoajast/v_3a10_3ay_3a2026_3ai_3a1_3ap_3a48-59_3aid_3a2523.htm&hl=zh-CN&sa=X&d=11867601411487788568&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv6FpUbeinAxoeelsMoTACYv&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=8&folt=kw-top
**作者**: P Nemeth, E Orsi, B Patczai, T Riedling, G Marada… - Open Academic Journal of …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large multimodal and vision–language models are increasingly evaluated on computed tomography (CT) and magnetic resonance imaging (MRI), yet a radiology study is a multi-series, multi-plane, multi-sequence volumetric object read with prior

---

### [25] Learned Reconstruction and LLM -Guided Residual Coding for Lossless Compression of Malaria Blood Smear Microscopy Images

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2079-9292/15/21/4932&hl=zh-CN&sa=X&d=5863070556673667172&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv4uDpS-91S8K3SAj3Ux1CoT&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=3&folt=kw-top
**作者**: Z Nusrat, MF Mahmud, WD Pan - Electronics, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper presents an LLM -guided residual coding framework for lossless compression of malaria microscopy images. A ResNet-based … Two LLM -based baselines are also evaluated using the same experimental protocol. Joint training on

---

### [26] BoLT: A Benchmark to Democratize Black-box Optimization Research for Expensive LLM Tasks

**链接**: https://arxiv.org/abs/2605.17000
**作者**: Ruth Wan Theng Chew, Zhiliang Chen, Apivich Hemachandra, Bryan Kian Hsiang Low
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] God Does Not Play Dice: Enforcing Batch Invariance in Agentic Kernel Generation

**链接**: https://arxiv.org/abs/2610.36623
**作者**: Youwei Bao, Chengpeng Wang, Simin Chen
**来源**: cs.AI cs.LG cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving systems dynamically batch user requests for GPU execution, so the same request may be processed alongside different requests across runs. If the GPU kernels lack batch invariance (BI), this changing batch context can alter the numerical output for an unchanged input, undermining reproducibility. Existing kernel generation agents focus on correctness and efficiency but \emph{overlook BI}. We find 19 confirmed BI violations among 83 batch-applicable released artifacts. To address this limitation, we propose \tool, which combines contract-guided static dependency analysis with dynamic validation of bitwise consistency across batch contexts. \tool is designed as a plug-in component for general kernel agents, allowing their original optimization capabilities to be reused while adding BI enforcement. We integrate it as successive acceptance gates in the optimization loop, rejecting structurally risky or dynamically non-invariant candidates before performanc

---

### [28] Does LLM Pre-Training Typically Occur at the Edge of Stability?

**链接**: https://arxiv.org/abs/2610.36778
**作者**: Yuhang Cai, Haodong Wen, Haofeng Huang, Deyi Liu, Yiyuan Ma, Kaifeng Lyu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quadratic approximations provide a common lens for studying neural network optimization, but recent evidence challenges their predictive validity. In full-batch gradient descent with learning rate (LR) $\eta$, Cohen et al. (2021) observed the Edge of Stability (EoS), where the largest Hessian eigenvalue concentrates near $2/\eta$, seemingly at odds with classical stability conditions predicted by quadratic approximations. In this work, we revisit the fidelity of quadratic approximations as a model of neural network training dynamics, with a particular focus on their failure modes in LLM training. We first highlight a distinct failure mode of the quadratic approximation, where persistent negative curvature causes the quadratic dynamics to diverge regardless of the LR, even though the real dynamics remain stable. We term this phenomenon the Edge of Convexity (EoC). After removing the effect of this LR-independent instability, we then propose a generalized definition of Edge of Stability 

---

### [29] LCM-Promo: An LLM-Based Uplift Model for Promotion Allocation

**链接**: https://arxiv.org/abs/2610.37570
**作者**: Nesta Midavaine, Floris Fok, Paulo Mendes, Joao Silva, \"Onder Aka\c{c}{\i}k, Dimas Lima 等 (7 人)
**来源**: cs.LG cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present LCM-Promo, an LLM-based uplift model for promotion allocation. LCM-Promo is a task-specific Large Commerce Model (LCM): a finetuned LLM trained on transactional commerce data to predict user intent and promotion response. It learns monotonic promotion-response curves from production logs by interpreting single-token outputs as conversion-threshold probabilities, while conditioning on session context such as day and delivery shift. In a production A/B test on churn reactivation, LCM-Promo increased conversion by 1% and reduced promotion cost by 6% relative to the Segment-EMA production baseline.

---

### [30] LLM Code Smells: A Taxonomy and Detection Approach

**链接**: https://arxiv.org/abs/2605.22976
**作者**: Zacharie Chenail-Larcher, Brahim Mahmoudi, Naouel Moha, Quentin Sti\'evenart, Florent Avellaneda
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Counting Clues: A Lightweight Probabilistic Baseline Can Match an LLM

**链接**: https://arxiv.org/abs/2512.12868
**作者**: Furong Jia, Yuan Pu, Finn Guo, Monica Agrawal
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] CONCUR: Concordant Auxiliary Rewards for Multi-Task, Multi-Reward Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.36437
**作者**: Jixuan Leng, Si Si, Fei Wang, Cho-Jui Hsieh, Jiong Zhang, Hsiang-Fu Yu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a Large Language Model (LLM) is trained with Reinforcement Learning (RL) on multiple tasks, a task's primary reward can gate auxiliary rewards such as a length reward: on a failing response, an auxiliary cannot exceed the primary. However, group-relative advantage estimators treat a gated auxiliary like any other component, so it can reverse the primary's order, and at the primary's ceiling only auxiliaries order responses. Keeping gated auxiliaries hurts some tasks, while dropping them hurts others. We propose CONCUR, an advantage estimator that replaces the standardized scores of each gated auxiliary with the closest scores that satisfy two conditions: responses with higher primary rewards cannot receive lower scores, and responses at the primary's ceiling receive equal scores. CONCUR-T applies both conditions throughout training, and CONCUR-A lifts the second for an auxiliary that agrees with the primary's order more often than it reverses it among passing responses. On three m

---

### [33] Dr. Post-Training: A Data Regularization Perspective on LLM Post-Training

**链接**: https://arxiv.org/abs/2605.07063
**作者**: Pingbang Hu, Xueshen Liu, Z. Morley Mao, Jiaqi W. Ma
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] When to Intervene? An Empirical Study of Errors and Self-Recovery in LLM Agents

**链接**: https://arxiv.org/abs/2610.36471
**作者**: Chiming Duan, Tong Jia, Yingxi Chen, Minghua He, Lingzhe Zhang, Ying Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents interact with Web services to perform tasks on users' behalf. Errors during these interactions can disrupt execution and prevent task completion, motivating external intervention. However, agents may self-recover through continued execution, raising the question of when to intervene and when to wait for self-recovery. We present an empirical study of errors and self-recovery in LLM agents. We construct ReInBench, a dataset containing 1,259 agent traces and 1,403 error events across computer-use and Web tasks. Our study examines how often and how quickly agents self-recover, how self-recovery relates to subsequent execution and task completion, and whether self-recovery can be predicted when an error occurs. We find that 725 error events self-recover, often within a few steps, with self-recovery performance differing across Execution LLMs. Self-recovery can also help agents recover from subsequent errors of the same type and support overall task completion. Intervention shoul

---

### [35] UnityBench-Mini3D: Evaluating LLM Agents for 3D Game Development in Unity

**链接**: https://arxiv.org/abs/2610.35980
**作者**: Yijun Zhou, Minghao Shao, Ke Zhang, Renkai Yuan, Hongbo Yuan, Bin Hu 等 (10 人)
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Game development stresses coding agents in ways general software engineering does not: correctness depends on how engine APIs, serialized scene state, and runtime behavior interact, not on source code alone. Existing benchmarks mainly target platforms such as Godot and heavily rely on LLM judges or coarse task-level outcomes. We present UnityBench-Mini3D, a benchmark of 77 project-level Unity tasks organized around seven expert-defined skill categories rather than tutorials or genres, with three difficulty tiers. Each task pairs a complete Unity project with natural-language requirements and is evaluated using 1,178 held-out, human-authored milestone tests covering scene structure, component configuration, and runtime behavior. This in-engine evaluation provides deterministic partial credit, localizes failures, and distinguishes partial implementations from complete solutions without relying on subjective judges. Across 21 models and 9 coding harnesses, the average pass rate reaches 80

---

### [36] Scaling Laws for Tool-Use Agents via Controllable Environment Synthesis

**链接**: https://arxiv.org/abs/2610.37648
**作者**: Andrew Szot, Samira Abnar, Omar Attia, Abbas Kazerouni, Michael Kirchhof, Cheng-Yu Hsieh 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We explore how to build performant large language model (LLM) tool-use agents that complete complex, multi-step tasks. Specifically, we study how data composition in synthetically generated tool-use environments affects the training of such agents. To do so, we propose the SynthAPI pipeline, which explicitly controls the diversity of generated environments along the axes of tools, tasks, and the databases on which the tools operate. By systematically varying SynthAPI's generation controls in 458,752 tasks across 849 trained models of four different sizes, we derive a scaling law that predicts downstream tool-use agent generalization based on the scale and composition of the synthesized environments. These predictable relationships reveal several lessons for scaling tool-use agent data. As data budgets grow, scaling tool and database diversity becomes more effective than increasing the number of tasks, and increasing data complexity yields larger gains. Scaling according to these findin

---

### [37] Proactive Memory for Event-Driven LLM Agents

**链接**: https://arxiv.org/abs/2610.36967
**作者**: Jinyang Li, Zichuan Fu, Xian Wu, Wenlin Zhang, Yimin Deng, Kaifeng Guo 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Proactive LLM agents anticipate service opportunities from ongoing observations and accumulated history. Existing approaches emphasize recent context or retrieval of related memories, providing limited support for validating recurring behavioral regularities and assessing their applicability to the current event. We propose Proactive Memory (ProactMem), which organizes history into recent events, temporal trajectories, and behavioral regularities. Trajectory facts are checked against source events, and regularities are assessed through historical replay before being matched to current conditions. We also construct ProactiveStream, a longitudinal benchmark covering three application scopes, where agents process isolated event streams chronologically under episode-aware opportunity labels. On ProactiveStream, ProactMem achieves an overall effectiveness (F1) of 52.6%, a 21.4% relative improvement over the strongest of five external baselines. Code is available at: https://anonymous.4open.

---

### [38] AOS-Bench: Can LLM Agents Manage Dynamic Workloads?

**链接**: https://arxiv.org/abs/2610.33178
**作者**: Erle Zhu, Genrui Zhang, Keyang Hu, Mingyu Su, Hongning Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Context Is a Pipeline, Not a Window: Information Attrition in LLM Agent Harnesses

**链接**: https://arxiv.org/abs/2610.36114
**作者**: Yuvraj Sehgal, Mahsa Panahandeh, Naser Ezzati-Jivan
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are judged by two numbers: the size of the context window, and how often the final answer is correct. Both numbers miss a third thing: how much of a tool's output is lost before the model ever sees it. We measured this loss in a real tool-using agent. The agent finds the cause of injected faults by reading Linux kernel traces. The context window was almost empty: across 720 runs, the single largest prompt used only 5.75% of it. Yet a third of all tool results (3,827 of 11,189) were cut before they reached the model, and every cut result became broken JSON. The harness cut each result by slicing its JSON text at a fixed length. This does not shorten a result evenly. It deletes whatever data sits near the end. One field reached the model in only 4.7% of calls. A second field, in the very same results, reached the model in 99.3% of calls. Which field held the fault's evidence depended on when the faulty process started: early or late in the trace. The agent's diagnosis accuracy

---

### [40] Silent and Costly: Characterizing and Detecting Prompt-Caching Mis-Integration in LLM Agents

**链接**: https://arxiv.org/abs/2610.34817
**作者**: Ying Zhang, Ruoqi Guo, Yi Liu, Gelei Deng, Yuekang Li, Yepang Liu 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Calibrating LLM Explanations to Human Decisions with Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.17306
**作者**: Dong Shu, Ziyang Guo, Negar Kamali, Matthew Groh, Jessica Hullman
**来源**: cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] IOSage: Detecting HPC I/O Bottleneck Patterns to Guide LLM Recommendations

**链接**: https://arxiv.org/abs/2610.36370
**作者**: Mahdi Banisharif, Tabassum Mahmud, Ahmad Tarraf, Suren Byna, Ali Jannesari
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> HPC applications often leave much of their parallel file system's bandwidth unused, and turning their Darshan logs into concrete I/O fixes still requires a scarce I/O expert. Rule-based tools flag counters against thresholds set by experts, and in tools built on large language models (LLMs), such as ION and IOAgent, the LLM decides which bottlenecks a log contains. We present IOSage, in which a classifier trained on many labeled logs, not the LLM, makes that decision, since a single log gives an LLM no baseline for what is abnormal. The LLM receives the I/O bottleneck patterns the classifier detects, the job's configuration files, per-file Darshan evidence, and for each pattern a card built from benchmark training runs, and writes recommended changes. Applied by hand and measured in repeated paired runs, the changes IOSage names speed up median total wall time 4.38x for an openPMD kernel (4.02x on a second storage tier) and 1.42x for hourly WRF restarts. For 5 of the 6 application scen

---

### [43] Characterizing WebGPU Dispatch Overhead for LLM Inference Across Four GPU Vendors, Three Backends, and Three Browsers

**链接**: https://arxiv.org/abs/2604.02344
**作者**: J\k{e}drzej Maczan
**来源**: cs.LG cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] TrawMem: Reframing Agent Memory as Task-Oriented Role-Adaptive Workspaces

**链接**: https://arxiv.org/abs/2610.36918
**作者**: Mingyu Zhang, Zixu Li, Zhiheng Fu, Zhiwei Chen, Jinhe Bi, Yupeng Hu
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents rely on memory systems to leverage long-term interactions, yet existing systems typically retrieve memories based on their relevance to the current query and use them as contextual evidence. However, relevance alone does not characterize how a memory contributes to task solving: the same memory may serve different roles across tasks, such as directly supporting the answer or linking to complementary memories with weaker semantic relevance but necessary information. We therefore reframe agent memory systems as Task-Oriented Role-Adaptive Workspaces, where memories are selected and organized by their task-oriented roles and relations. Based on this view, we propose TrawMem, which organizes interaction histories into local threads and constructs task-oriented workspaces by assigning roles and jointly selecting complementary memories. Experiments on LoCoMo and MemGallery with four open- and closed-source backbones show consistent improvements over represen

---

### [45] SELF: A Robust Singular Value and Eigenvalue Approach for LLM Fingerprinting

**链接**: https://arxiv.org/abs/2512.03620
**作者**: Hanxiu Zhang, Qiang Xu, Yue Zheng
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Verifiable Efficiency Limits of Innate LLM Planning in Sliding Puzzles

**链接**: https://arxiv.org/abs/2610.36415
**作者**: Yezhou Cheng, Charles Ling
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-assisted planning success can reflect external search and verification, leaving a model's unaided planning ability unresolved. We isolate innate planning through complete plans generated in one response without tools or execution feedback. We propose a verifiable framework that decomposes success-weighted plan efficiency as $\mathrm{SPE}=R\times Q\times E$: execution reliability, planning coordination among legal plans, and action economy among completed plans. Trajectory replay and certified optima verify these factors; the joint score includes unsuccessful attempts. We evaluate 8,400 full-plan outputs from seven model conditions on $4\times4$ sliding puzzles, controlling exact horizon and obstacle count in the primary cohort. Models that complete every trial still become less economical at longer horizons, while higher efficiency among completed plans can coexist with poor goal attainment. SPE separates the overall capability hierarchy, while its factors distinguish coordination

---

### [47] Kernel Token Contradiction: a Fast and Principled Approach for LLM Claim Uncertainty Quantification

**链接**: https://arxiv.org/abs/2608.22506
**作者**: J\'er\'emie Dentan, Alexi Canesse, Mahammed El Sharkawy, Sonia Vanier
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Zeno: Improving the Fidelity and Pedagogical Value of LLM -Generated Alt Text with BLV-Informed Guidelines and Iterative Prompting

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/full/10.1145/3797867.3841231&hl=zh-CN&sa=X&d=185781899942418992&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv5_vca17fBKdUjVnMrZJoLa&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=6&folt=kw-top
**作者**: S Liu, J Zhang, MEMK Fayed, Y Zhao, P Premkumar… - Proceedings of the 28th …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -generated alt text for an online AI course. Inspired by a blind student’s longitudinal course experience, we introduce Delta, a CS-specific guideline for task-operable alt text, and Zeno, an iterative LLM … usefulness of LLM -generated alt text for

---

### [49] Strong Teacher Not Needed? On Distillation in LLM Pretraining

**链接**: https://arxiv.org/abs/2605.23857
**作者**: Taiming Lu and Zhuang Liu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Reconfiguration of Ability: An Autoethnography of LLM -Mediated Development by a Developer with Severe Physical Disability

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3797867.3828990&hl=zh-CN&sa=X&d=1256586156801673156&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv5U5o9PLeiOwpebReIA8ii4&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=9&folt=kw-top
**作者**: K Ono - Proceedings of the 28th International ACM …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> What does it mean to be a “developer” when one cannot type, speak, or move one’s limbs? This paper presents an autoethnographic inquiry into how the concept of ability is reconfigured through collaboration between a person with severe physical

---

### [51] Log-To-Leak: Prompt Injection Attacks on Tool-Using LLM Agents via the Model Context Protocol

**链接**: https://arxiv.org/abs/2610.36108
**作者**: Yuepeng Hu, Chongyu Fan, Sirat Samyoun, Jian Du
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly access external tools through the Model Context Protocol (MCP), but the natural-language metadata used to describe those tools creates a prompt-injection surface. Within this established tool-poisoning surface, we study Log-To-Leak, an additive post-hoc logging attack that induces a separate attacker-controlled call after the final legitimate call. Its payload targets the user query, MCP server name, server response, and agent response. We operationalize the injected directive through Trigger, Tool Binding, Justification, and Pressure, and separately measure call success, payload fidelity, and preservation of legitimate behavior. We evaluate five MCP servers and four LLM agents using five metrics spanning effectiveness, utility, and efficiency. Across 18 model-server pairs with valid tool execution, Log-To-Leak achieves an attack success rate (ASR) of 62.64-100% and conditional logging accuracy (LA) of 76.55-95.64%; 16 pairs have absolute target-task completion 

---

### [52] Validating FKG.in: Soundness Assessment in LLM-Augmented Indian Food Knowledge

**链接**: https://arxiv.org/abs/2608.29249
**作者**: Saransh Kumar Gupta, Armaan Shah, Lipika Dey, Partha Pratim Das and Ramesh Jain
**来源**: cs.AI cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Scoring-Rule Sensitivity in LLM Evaluation: Evidence from Indian Financial Regulatory Text

**链接**: https://arxiv.org/abs/2604.19298
**作者**: Rajveer Singh Pall
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Skill Dreaming: Evolving Repository Skills through Pull Request Streams

**链接**: https://arxiv.org/abs/2610.36188
**作者**: Xinyuan Song, Hasibul Haque, Jay Somasundaram, Ryan Turner, Bowen Zhu, Liang Zhao
**来源**: cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on reusable skills for complex software engineering tasks, making skill libraries essential for repository development and maintenance. However, repository-specific skills must evolve with changing code structures, implementation conventions, and maintenance requirements. Pull requests (PRs) provide a natural source of such knowledge by recording how repositories evolve through implementation and review. Meanwhile, new PRs must follow repository-specific implementation patterns, modify related components consistently, and ensure that existing tests continue to pass while adding coverage for new functionality. This creates a mutually reinforcing cycle: PRs provide knowledge for updating skills, while these skills improve future PRs, maintain repositories, and support further skill evolution. To enable this co-evolution of PRs, repositories, and skills, we propose Skill Dreaming, a framework that learns from PR streams to guide continuo

---

### [55] MARQ: A Modular, LLM-Agnostic Requirement Quality Assessor Infused with Systems Engineering Knowledge

**链接**: https://arxiv.org/abs/2610.36234
**作者**: Jannatul Shefa, Alejandro Salado, Paul Wach, and Taylan G. Topcu
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Requirements engineering (RE) is foundational to systems engineering (SE), as requirement defects can propagate downstream and adversely affect development outcomes. Although large language models (LLMs) are promising for requirement quality assessment, prior work shows that off-the-shelf models miss a large share of expert-identified defects, perform unevenly across quality criteria, and vary across executions. This study investigates whether infusing expert-derived SE knowledge can improve LLM-based requirement quality evaluation beyond off-the-shelf capability. We present MARQ, a modular, LLM-agnostic prototype that supplements LLMs with a criterion-specific knowledge stack operationalizing INCOSE requirement quality criteria and evaluated against off-the-shelf baselines on an expert-labeled NASA requirement set using Claude Opus 5, GPT-5.6 Sol, and the open-weight Gemma 3 12B, with 100 executions per model. MARQ achieves median F1 scores of 0.80 for Claude Opus 5, 0.62 for GPT-5.6 

---

### [56] Do We Need an LLM to Know Why Sources Conflict? Decision Models for Knowledge-Conflict Typing in RAG

**链接**: https://arxiv.org/abs/2610.36915
**作者**: Parv Khatri, Harshul Jain, Mehak Kapoor, Tanya Sah
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When the sources retrieved for a query disagree, the right response depends on why they disagree: a question with several valid answers, a contested topic, stale information and a false source each call for different behaviour. Cattan et al. (2025) showed that telling a generator the conflict type improves its responses by about 24 points, but that predicting the type is hard even for frontier LLMs. We study whether typed decision models, which return probabilities over fixed options in a single forward pass instead of generating text, can do this classification fast and cheaply. Using the CONFLICTS benchmark and the original paper's prompt verbatim, we evaluate all 11 decision models served by one commercial inference gateway, from 7 providers, against Gemini models on identical inputs. Asked directly, the decision models reach 50.0--67.0% accuracy; 10 of the 11 match or exceed Gemini 2.5 Flash, the paper's model (61.3%), at 4--39x lower billed cost (2 were free) and 2.6--6.0x lower l

---

### [57] Trajectory-Aware Policy Optimization: Closing the State Distribution Gap in Long-Horizon LLM RL

**链接**: https://arxiv.org/abs/2610.13020
**作者**: Zhicheng Cai, Hanlin Wu, Weinan Dai, Yuyan Zhou, Wei-Ying Ma, Ya-Qin Zhang 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] SemLoc: Structured Grounding of Free-Form LLM Reasoning for Fault Localization

**链接**: https://arxiv.org/abs/2603.29109
**作者**: Zhaorui Yang, Haichao Zhu, Qian Zhang, Rajiv Gupta, Ashish Kundu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Prompt and Circumstance: Evaluating Accessibility in LLM -Generated HTML Form Components

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3797867.3828975&hl=zh-CN&sa=X&d=12400706001836495456&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv71XgqymKARWsYLU0WM7cKV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=0&folt=kw-top
**作者**: Y Ma, JO Wobbrock, J Devon, A Gustafson, M Fairchild… - Proceedings of the 28th …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -… LLM -generated code moved with prompt construction and with the circumstance around it (eg, model, form component, and measure used to assess the output). This pattern calls for evaluation designs that can better separate sources

---

### [60] LLM knowledge for improved Out-of-Distribution Tabular Prediction - A Cross-Validated Regularisation Approach

**链接**: https://arxiv.org/abs/2610.36806
**作者**: S{\o}lve Langseth, Kristoffer Herland Hellton and Hugo L. Hammer
**来源**: cs.LG stat.ME stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prediction models degrade when the deployment population differs from the one used to train them, and training data cannot say which feature-response relationships will transfer. Expert elicitation is slow and unscalable. We ask whether coefficient priors elicited from large language models (LLMs) improve out-of-distribution (OOD) prediction as the shrinkage target of a regularised regression instead of zero, across five tabular datasets split on real covariates, selecting providers and prior structures by source-domain cross-validation alone. The priors help on four of five datasets, by up to 7.9% OOD mean squared error, and ten of twenty-four prior-informed results resolve the mean improvement at conventional confidence; single-deployment intervals are much wider. On classification the gain is in probabilistic accuracy, not ranking, and control tests with corrupted priors attribute the benefit to feature-specific content rather than scale. Two findings temper this. Variation across c

---

### [61] Rare, Relevant, and Still Wrong: How Memory Fails LLM Group Decisions

**链接**: https://arxiv.org/abs/2610.37624
**作者**: Anouar Imel, Imad Charradi, Abderrahman Sghir, Khalil El Khammar
**来源**: cs.AI cs.CL cs.MA cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM group's discussion is compressed into a short memory for a final decision maker, what should the memory keep? Two natural heuristics keep the rarest claims or the claims relevant to the decision criteria. On hidden-profile tasks both look attractive, because how widely a fact is held is confounded with whether it helps. We introduce CrossProfile, a diagnostic benchmark of 60 templates with automatically verified answer keys, in which the ownership of supporting, decoy, and irrelevant facts is crossed while their text is held fixed (480 tasks). Across Qwen2.5-7B, Llama-3.1-8B, and two DeepSeek models, both heuristics fail in predictable places. Selecting by relevance readmits decoys, because decoys are on topic: even a perfect relevance filter loses 23 to 31 points to rarest-first selection in the classic hidden-profile configuration. Rarest-first selection is no better than random selection on average and wins only where the rare facts happen to be the useful ones. In both 

---

### [62] NextEval: An Agent-Based Solver and Benchmark for Derivative-Free Optimization

**链接**: https://arxiv.org/abs/2610.36553
**作者**: Shuo Chen, Li Cui, Cunxin Huang, Ya-Feng Liu, Minghang Xie, Meng Xu 等 (7 人)
**来源**: cs.LG cs.AI math.OC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Derivative-free optimization (DFO) addresses problems where derivatives are unavailable or costly to obtain. This setting often arises in simulation-based and experimental applications, where evaluating the black-box objective can itself be costly. Thus, it remains a central challenge in DFO to effectively exploit accumulated observations to select informative evaluation points under a limited budget. In this light, we introduce the NextEval solver, an agent-based DFO solver, which integrates the capabilities of a large language model (LLM) to guide the sequential selection of evaluation points. Specifically, we establish a system that combines an LLM agent with a numerical environment. The environment provides tools for analyzing past evaluations and executing numerical methods, while maintaining a shared evaluation history and method-specific state to support continuation across method switches. Using observations and tool feedback, the LLM agent selects tools, configures their param

---

### [63] LoRA‐Finetuned LLM for Multi‐Step Renewable Energy Power Forecasting

**链接**: https://scholar.google.com/scholar_url?url=https://ietresearch.onlinelibrary.wiley.com/doi/pdf/10.1049/ein2.70037&hl=zh-CN&sa=X&d=17553129035665978457&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv6XVXCWMzVLuVIdXY1s7wPs&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=7&folt=kw-top
**作者**: X Huang, Z Yi, V Shakirov, C Wu, T Nikita, D Sidorov - Energy Internet 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> of LLM to wind power forecasting but also contributes to paving the way for LLM utilization in the … LLM to multi-step wind power forecasting. This validation on real-world engineering data highlights the application-oriented contribution of the study. In this

---

### [64] OA-RAG: Ontology-based Agentic RAG for Faithful LLM Reasoning

**链接**: https://arxiv.org/abs/2610.36335
**作者**: Hui Yang, Jiaoyan Chen, Yongsheng Gao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) perform well across many real-world tasks but remain prone to hallucination, limiting their reliability in domains such as biomedicine and healthcare, where answers must be grounded in established knowledge. Retrieval-augmented generation (RAG) mitigates this problem by incorporating external information, but often overlooks logical relationships and relies heavily on the LLM's own reasoning, which can compromise answer faithfulness. We propose OA-RAG, an agent that integrates formal reasoning with LLM reasoning, drawing on both the logical structure and informal annotations of domain ontologies. For each answer, OA-RAG reports the ontology observations used as evidence and a model-assessed grounding level (entailed, supported, related, or unrelated) that characterises the strength of that evidence. Across benchmarks derived from three large-scale ontologies and six real-world medical question-answering tasks, OA-RAG achieves the best overall performance am

---

### [65] ResCom: Activation Residual Compensation for Large Language Model Quantization

**链接**: https://arxiv.org/abs/2610.35955
**作者**: Ning Yang, Bohan Cui, Zhuowen Liu, Yuting Wang
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-bit weight--activation quantization reduces the memory and computation needed to deploy large language models, but activation rounding can still degrade accuracy after calibration. Reconstruction from rounded inputs cannot distinguish activations within the same quantization bin. We propose ResCom, a low-rank correction that uses the activation rounding residual to compensate for the resulting layer-output error. An output-aware calibration procedure selects residual directions by their contribution to output reconstruction and computes the correction in closed form, without gradient training or updates to the calibrated weights. On Llama-3-8B with 4-bit weights and activations, rank-32 attention corrections reduce WikiText-2 perplexity from 7.708 to 7.147, improve MMLU by 2.89 percentage points, and raise five-shot GSM8K accuracy from 23.96 to 36.16 percent. Evaluations on models from 1B to 70B parameters and on held-out C4 test the method beyond this setting. The evaluated FP32 i

---

### [66] Robust LLM Data Selection via Content-Invariant Gradient Attribution

**链接**: https://arxiv.org/abs/2610.36755
**作者**: Jia Gu, Liang Pang, Huawei Shen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Gradient-based data attribution has become an important tool for high-quality data selection in the instruction fine-tuning of large language models (LLMs), as it estimates the contribution of training examples through their influence on model optimization. However, we find that existing global gradient attribution methods suffer from surface-form bias: minor changes to semantically irrelevant details, such as wording or formatting, can produce highly inconsistent attribution scores even when the underlying content remains unchanged. To address this issue, we propose Content-Invariant Gradient Attribution (CIGA), a robust framework for instruction data selection. CIGA first identifies layers whose gradients are both influential for attribution and stable under semantics-preserving surface-form perturbations, thereby reducing formatting noise in gradient features. It then dynamically fuses these attribution signals with semantic representations of the input, combining optimization-level

---

### [67] Clinical Note Bloat Reduction for Efficient LLM Use

**链接**: https://arxiv.org/abs/2604.16364
**作者**: Jordan L. Cahoon, Chloe Stanwyck, Asad Aali, Rachel Madding, Sulaiman S. Somani, Emma Sun 等 (9 人)
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Agent Planning Benchmark: A Diagnostic Framework for Planning Capabilities in LLM Agents

**链接**: https://arxiv.org/abs/2606.04874
**作者**: Haoyu Sun, Wenxuan Wang, Mingyang Song, Jujie He, Weinan Zhang, Yang Liu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Diversity Combining for Multi-Path LLM Reasoning

**链接**: https://arxiv.org/abs/2609.38829
**作者**: Guangsheng Yu and Litianyi Zhang and Qin Wang and Xu Wang and Mingyuan Li and Shaoxiong Ji and Ren Ping Liu and Massimo Piccardi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] SocraGate: Inference-Time Admission Control for Reducing Answer Leakage in Scaffolded LLM Tutoring

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-3417/16/21/10561&hl=zh-CN&sa=X&d=6761525467192611575&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv42vowSTcOw9ODcCedhs5OU&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=1&folt=kw-top
**作者**: W Li, K Zhao - Applied Sciences, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models can solve mathematics problems accurately yet compromise tutoring by revealing answers before learners complete the reasoning. Prompt- and reward-based alignment changes the response distribution but does

---

### [71] AgentSentry: Mitigating Indirect Prompt Injection in LLM Agents via Temporal Causal Diagnostics and Context Purification

**链接**: https://arxiv.org/abs/2602.22724
**作者**: Tian Zhang, Yiwei Xu, Juan Wang, Keyan Guo, Xiaoyang Xu, Bowen Xiao 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] Detailed balance in large language model-driven agents

**链接**: https://arxiv.org/abs/2512.10047
**作者**: Zhuo-Yang Song, Qing-Hong Cao, Ming-xing Luo, Hua Xing Zhu
**来源**: cs.LG cond-mat.stat-mech cs.AI nlin.AO physics.data-an
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] SCI-Defense: Detecting Persuasion-Structured Manipulation of LLM-Based Ranking in Generative Engines

**链接**: https://arxiv.org/abs/2605.21948
**作者**: Xucheng Yu, Haibo Jin, Huimin Zeng, Haohan Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] CoHARL: Co-Evolving Agent Policies and Executable Harnesses with Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.36469
**作者**: Jianwen Chen, Peng Xia, Kaide Zeng, Siwei Han, Zhen-Yu Zhang, Charles Fleming 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents interact with their environments through executable harnesses that govern tool use and feedback. Optimizing a harness for a fixed policy overlooks how its behavior changes during learning, while training a policy under a fixed harness leaves the interface that generates its training experience unchanged. This motivates adapting the harness throughout policy training. We introduce CoHARL, a population-based reinforcement learning framework that co-evolves a shared policy and a population of executable harnesses. The policy learns from rollouts across the population, and a proposer uses its execution traces to revise harness code during training. CoHARL achieves a 27.6% mean resolved rate on SWE-rebench, improving over harness-only search by 6.4 percentage points. Experiments on SWE-bench Verified and Terminal-Bench 2.0 show gains in software engineering and terminal-based tasks. Under matched training budgets, CoHARL also outperforms searching for a har

---

### [75] API-TAIL: Detecting Model Substitution in LLM APIs through Temperature-Aligned Likelihood Tails

**链接**: https://arxiv.org/abs/2610.36801
**作者**: Haocheng Mei, Yuchuan Tian, Ye Yuan, Chao Xu, Allen Chen, Kai Han 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Commercial language model APIs return only text, allowing a provider to cut costs by quietly routing a fraction of user requests to a cheaper substitute model while billing for the advertised one. Detecting such partial substitution is challenging because honest providers also alter the output distribution through undocumented decoding and serving choices, such as temperature scaling, sampling truncation, repetition and presence penalties, and default system prompts, forcing an audit to test against a composite null of legitimate configurations rather than a single reference. Our key insight is that these legitimate variations primarily shift response typicality across the entire batch, whereas partial substitution injects individual responses that remain anomalous under the claimed model. Building on this, we introduce API-TAIL, a typicality audit that first absorbs batch-level shifts by aligning a single effective temperature to center standardized surprisal scores across the audited

---

### [76] Local Entropy Fluctuations for Black-Box LLM-Generated Text Detection

**链接**: https://arxiv.org/abs/2610.33767
**作者**: Xinpeng Wang, Bruce Rushing, Zhizhen Chen, Zhe Zeng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] LM-DSB: A Lightweight Multi-agent System for Automated Daily Safety Bulletin Generation in Construction

**链接**: https://arxiv.org/abs/2610.36433
**作者**: Xianxiang Zhao, Advik Mehta, Falak Sethi, Brian Gue, Qipei Mei, Lingzi Wu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Construction safety management still struggles to produce daily safety bulletins (DSBs), structured daily communications that identify site-specific hazards, convey safety protocols, and set preventive measures for workers. Manual DSB creation takes 2-3 hours daily and yields inconsistent quality, with 25% of crews never conducting pretask planning (Olson et al., 2016), diverting safety personnel from field supervision. This study proposes the Lightweight Multi-Agent DSB System (LM-DSB), which integrates retrieval-augmented generation (RAG) with a locally deployable Large Language Model (LLM) to automate DSB generation on consumer-grade personal computers. LM-DSB coordinates specialized planner, researcher, and writer agents in a hierarchical architecture, enhanced by domain-specific fine-tuning on construction safety documentation and RAG grounding in 37 health, safety, and environment (HSE) documents. A two-phase validation assessed feasibility. Phase 1 comparative evaluation showed 

---

### [78] Concordat: Typed Sessions for LLM Agents

**链接**: https://arxiv.org/abs/2610.37461
**作者**: Milad Sikaroudi
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents built on large language models are increasingly allowed to take consequential actions: cancelling bookings, issuing refunds, changing accounts. The rules that govern those actions, such as "obtain the customer's explicit confirmation before changing anything", are usually stated in the prompt and followed only as reliably as the model chooses to follow them. We present Concordat, a Python library that treats an agent as an object whose interface is a finite-state protocol, in the spirit of typestate and session types, and enforces that protocol on the model at run time. On every turn the model is offered only the tools that are legal in the current protocol state, calls outside that set are rejected before they have side effects, decisions reserved for humans can only be requested, and token and tool-call budgets are charged and split linearly across handoffs. Protocols are checked when they are defined, and a subclass of an agent is rejected if it could bypass its parent's prot

---

### [79] JevRec: Linguistic Encoding with Jev-like Decision Modeling for LLM-based Generative Recommendation

**链接**: https://arxiv.org/abs/2610.36937
**作者**: Qiyong Zhong, Jiajie Su, Ming Yang, Li Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative recommendation (GR) represents items as semantic identifiers (SIDs) and autoregressively generates the next item's SID from interaction history. However, most methods assign the same SID length to all items despite highly unequal interaction frequencies. This uniform design repeatedly incurs the cost of fine-grained codes for popular items, while shortening codes to reduce this cost also compresses the semantic representations of long-tail items. Inspired by the compact forms of frequent expressions in natural language, we propose JevRec to encode items as variable-length words and generate the next item from interaction context. Linguistic encoding retains frequency-dependent semantic prefixes from shared codebooks, producing shorter SIDs for popular items and richer descriptions for long-tail items. Yet predicting a sequence-level length and generating token-level content impose different optimization requirements that may conflict under a shared output head. Our Jev-like 

---

### [80] Blindfold: Keeping the Audit Coin Secret from LLM Agents

**链接**: https://arxiv.org/abs/2610.37055
**作者**: Wei Zhu, Meiyun Zuo, Huiping Sun
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audit-based certification bounds the violation rate of an LLM agent by auditing a random fraction $\varepsilon$ of actions and reweighting the audited labels; its validity is meant to rest only on the defender's audit coin. We show that it also rests on a confidentiality property: the coin must not interfere with the agent's view before the action commits, at a time the agent chooses. We call this pre-commit noninterference (PNI) and measure its violation by $D_{\mathrm{A}}$, the total-variation distance between the agent's views under the two coin values. PNI is necessary and sufficient for an unbiased certificate against adaptive agents, the worst-case bias is $(1-\varepsilon)D_{\mathrm{A}}$, and no procedure that sees only audited labels can pay less. Leakage composes across steps, a resource shared across episodes opens a channel of computable size, and raising the audit rate cannot restore validity. On a monitor we built, a silent audit changes no output but adds latency that tool

---

### [81] A Decomposition-Based Framework for LLM -Augmented Topic Analysis of Weakly Standardized Narratives

**链接**: https://scholar.google.com/scholar_url?url=https://aisel.aisnet.org/cais/vol59/iss1/72/&hl=zh-CN&sa=X&d=11854748110889736144&ei=Dwriau-OO4OnieoP05LQQA&scisig=AIL1Nv4nbDabF-0KTdvGyH8hO-Yx&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=5&folt=kw-top
**作者**: T Yang, TR Yu, H Zhao - Communications of the Association for Information …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -assisted interpretation. The framework first uses embedding-based topic modeling to identify recurring thematic structures in the narrative corpus. It then aligns the discovered topics with relevant domain concepts before using a

---

### [82] PolicyMediator: Multi-Regional Policy Learning through Mediation Agents with Evolving Skills in OPC Ecosystems

**链接**: https://arxiv.org/abs/2610.35997
**作者**: Jie Li, Bin Guo, Georgina Curto, Zikang Liu, Mengqi Chen, yu li
**来源**: cs.MA cs.AI cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> One-person companies (OPCs) are emerging enterprises operated by individual entrepreneurs through digital platforms and LLM-based AI agents. These highly skilled entrepreneurs are characterized by being digital nomads, with limited reliance on local ecosystems. Governments in China use distinct regional support policies to attract mobile OPCs, turning local support into a cross-regional coordination problem. OPCs compare regions to maximize their own utility, but imperfect policy perceptions may cause them to reject otherwise suitable locations. Existing policy-learning methods optimize resources under fixed perceptions, while consensus-formation methods aggregate views without feeding cognitive changes back into policy learning. This disconnect produces mismatched location choices and inefficient regional policy adjustment. We introduce PolicyMediator, a cognition-constrained leader-multi-follower Stackelberg framework with bilateral mediation. The mediator explains verified policies 

---

### [83] Prospector: learning a compact graph traversal policy for scientific reasoning

**链接**: https://arxiv.org/abs/2610.37121
**作者**: Haiqian Yang and Markus J. Buehler
**来源**: cs.AI cond-mat.mtrl-sci cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific reasoning in specialized engineering fields depends on knowledge scattered across the literature, often proprietary and absent from frontier LLM training data. In such domains, frontier models tend to give generic answers. Knowledge graphs (KGs) can ground LLM reasoning. Because a graph is too large to provide in full, typical LLM+KG systems preselect a portion, deciding relevance before reasoning begins. Here we train a compact model, Prospector, to reason over a domain knowledge graph by traversing it step by step, seeking evidence in light of what it has already found. Prospector calls a small set of tools one at a time to progressively build its context, and answers with a chain of evidence that can be checked edge by edge against what its tools retrieved from the graph. On a knowledge graph built from the semiconductor-manufacturing literature, Prospector approaches the strongest off-the-shelf models given the same graph and tools, and it far exceeds off-the-shelf model

---

### [84] Meta Models: Models that Model Learning

**链接**: https://arxiv.org/abs/2610.37001
**作者**: Peihang Li, Ziming Liu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Every neural-network training run produces not only a model, but also evidence about how models learn. Can these accumulated experiments enable us to predict and compare new training runs before executing them? We study meta-models: models that predict the learning behavior of other models. From this perspective, final-performance prediction, learning-curve prediction, and hyperparameter selection are different queries to the same training response function. We take a first, humble empirical step toward this goal: treating real language-model training records as native numeric data, we find that an off-the-shelf tabular in-context learner, TabPFN, can match or outperform a fine-tuned LLM meta-model in multiple evaluated settings. Whereas recent work fine-tunes LLMs on tokenized configurations at a cost of tens to hundreds of GPU-hours, TabPFN requires seconds of fit-and-predict time without task-specific weight updates. We argue that meta-modeling is better treated as its own numeric m

---

### [85] Uncovering Why LLMs Fail: From Internal Mechanisms to Adversarial Reasoning Trajectories

**链接**: https://arxiv.org/abs/2610.37369
**作者**: Zirui Ding (1, 2), Xinxin Fan (2, 3), Hao Yuan (1, 4) 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are usually evaluated by final-output correctness or safety, yet an endpoint label does not reveal how a failure develops throughout the reasoning process. We therefore ask whether ordinary reasoning failures and adversarially induced failures can be characterized using the same internal coordinates. Towards this end, we in this paper study a white-box diagnostic framework CauTrace to disclose the root-cause of why LLM fails from three fundamental inspections: Functional States, Propagation of Representation, Temporal-State Coordination and Reasoning Trajectory. First, seven functional states are creatively defined to represent the support and constraint processing in LLMs. Second, the propagation of representation change measures how the changes among the seven states persist across subsequent Transformer blocks. Third, temporal-state coordination and trajectory topology characterize when the commitment and verification occur relative to the support, and h

---

### [86] QESChunker: A Single Objective Unifies Overlapping and Non-Overlapping Chunking for RAG

**链接**: https://arxiv.org/abs/2610.36557
**作者**: Yifan Zhao, Qianyang Zhao, Xinyu Guan, kai wei, Yuming Deng
**来源**: cs.IR cs.CL math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chunking is a fundamental preprocessing step in retrieval-augmented generation (RAG), yet most existing chunkers rely primarily on heuristics. We introduce the Question--Evidence-Supervised Chunker (QESChunker), to our knowledge the first method for constructing static chunk indices from question--evidence supervision. QESChunker constructs document-specific chunk indices by optimizing over human-annotated or LLM-generated question--evidence pairs, without access to held-out test queries. We formulate non-overlapping and overlapping index construction through a unified question--evidence utility-maximization objective, turning chunking into a supervised combinatorial optimization problem. Under the non-overlap constraint, the objective decomposes over chunks and can be optimized exactly in polynomial time by dynamic programming. When overlap is allowed, the objective becomes monotone submodular; exact optimization is NP-hard, but our greedy achieves a $(1-1/\sqrt{e})$-approximation. Ac

---

### [87] Same Verdict, Different Readers: Personalizing Fact-Checking Explanations from Relative Preferences

**链接**: https://arxiv.org/abs/2610.37380
**作者**: Haokun Wen, Xuemeng Song, Mong-Li Lee, Wynne Hsu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fact-checking explanations help Web users understand why a claim receives its verdict, yet the same explanation may not satisfy readers with different backgrounds and preferences. We formulate Faithful Personalized Fact-Checking Explanation Rewriting, which adapts an existing explanation to individual readers while preserving factual fidelity. Rather than relying on reader-written reference explanations, we learn personalized rewriting from the relative preferences of LLM-simulated readers. However, this presents two challenges: distinguishing persona-specific preferences from general explanation quality and learning beyond a limited set of predefined explanation styles. To address these challenges, we propose Personalized Explanation Rewriting via Preference Learning (PERPL), a framework consisting of two components. Simulated Preference Construction derives persona-specific supervision from simulated reader preferences through cross-persona reciprocal pairing. Progressive Preference 

---

### [88] Your Agent Acts Differently When You're Around: How User Presence Changes Agent Behavior in Negotiation

**链接**: https://arxiv.org/abs/2610.36435
**作者**: Jane Pan, You Lyu, Abe Bohan Hou, Valerie Chen, He He
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly interact with other agents on behalf of users, yet how users in the loop affect their agents' behavior--for better or worse--remains poorly understood. We study this question through the lens of negotiation, where agents must represent users while strategically bargaining with other agents. To isolate the effect of user presence, we develop PRESENT, a controlled evaluation framework that compares negotiation settings with and without an interactive user, while holding the game, objectives, and user preferences fixed across conditions. Across 11.2k runs spanning 7 games and 8 models, we find that user presence significantly changes both outcomes and behavior. Specifically, negotiation parties with a user obtain higher payouts (+13.7% on average) and their agents negotiate more aggressively. Surprisingly, user presence also induces misaligned behavior, both toward counterparties (where its rate roughly doubles) and toward users (where it emerges in 14.3% of games)

---

### [89] Bayes-Adaptive MDPs for Rollout Allocation to Enhance GRPO Training

**链接**: https://arxiv.org/abs/2610.37429
**作者**: Faeze Moradi Kalarde, Armin Toroghi, Nam Ho Koh, Doo Hwan Hwang, Seungjin Kim, Kee-Eung Kim 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group Relative Policy Optimization (GRPO) has demonstrated strong performance in LLM post-training. However, it allocates a uniform rollout budget to every training question, ignoring variations in question difficulty. As a result, highly difficult questions may receive too few rollouts to generate informative positive reward signals, limiting their contribution to training, while moderately difficult questions often receive more rollouts than necessary. In this work, we formulate the problem of difficulty-aware rollout budget allocation to maximize training utility under the same total rollout budget as standard GRPO. We propose AdaRoll-GRPO, which reformulates rollout allocation as a sequential decision-making problem and leverages a Bayes-adaptive Markov decision process (MDP) to learn an adaptive allocation policy. The learned policy is computed offline and applied during GRPO training without introducing additional online optimization overhead. Extensive experiments on multiple re

---

### [90] GUI-JEPA: Candidate-Conditioned JEPA Latents as a Fast Action Policy for Mobile GUI Agents

**链接**: https://arxiv.org/abs/2610.36877
**作者**: Bingchao Wang, Yongcheng Jing, Shunyu Liu, Chengyu Wang, Jun Huang, Jie Yang 等 (8 人)
**来源**: cs.AI cs.CL cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile GUI agents are typically fine-tuned 7B-scale vision-language models (VLMs) that generate each action as text. However, these VLMs decode every action token by token, and even agents that score candidate actions keep a large language model or VLM in the loop, making them slow and memory-hungry. To address these issues, we propose GUI-JEPA, to our knowledge the first decoder-free GUI agent policy built on a Joint-Embedding Predictive Architecture (JEPA), which selects actions in the latent space of a JEPA encoder pretrained on unlabelled GUI screenshots. Its action- and region-conditioned latent predictor turns the screen latent into one latent per candidate action, letting lightweight heads score all candidates against the instruction in a single batched pass, without decoding a token. We further show that the scorer relies on this latent pathway and that the predictor is trained for the decision itself: a randomly initialised predictor does just as well as one pretrained on scre

---

### [91] Generation and Verification: Human-Agent Collaboration for Safety-Critical Automotive Software Engineering

**链接**: https://arxiv.org/abs/2610.35982
**作者**: Elizaveta Zinovyeva, Aiham Taleb, Nikita Kozodoi, Daniel Schleicher, Amir Mahdi Namazi, Martin Kraus 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on coding agents mainly focuses on generation quality. Yet, safety-critical automotive software makes two additional demands. It prioritizes verification, since every change is reviewed, traced to a requirement, and checked against industry standards such as MISRA and AUTOSAR before it can be committed. It is also a narrow domain, written against layered architectures, embedded resource constraints, and organization-specific interface conventions that are scarce in the data general-purpose LLMs are trained on. We present a coding assistant for automotive C/C++ that addresses both demands. First, it exposes three tools to the user over the Model Context Protocol (generate, edit, and verify), allowing developers to run verify on any code on demand rather than relying on the agent to check its own output. Second, rather than using a general-purpose model, we customize the underlying LLM for the automotive domain through prompt engineering and fine-tuning. We construct a dataset f

---

### [92] What Victims Take Away: Attack Reuse and Defense Revision after Prompt-Injection Attacks

**链接**: https://arxiv.org/abs/2610.36422
**作者**: Zihan Chen, Lei Nico Zheng, Di Zhu
**来源**: cs.CR cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attack logs and red-team reports show targets the attacks used against them, to help them repair their defenses. Prompt injections against large language models (LLMs) are plain text, so such records also hand targets a working copy. Drawing on social learning theory and work on the victim-offender overlap, we study what targets do with that copy in Tensor Trust, an online game whose players defended LLM-guarded accounts, attacked one another's, and could read every attack they received. Using all 563,349 attack records, we compare each received attack with matched attacks that circulated among similar players at the same moment but never reached the target. Reuse mainly followed success: within a week, targets attacked other players with 10.0% of the attacks that had broken their defense, versus 0.03% of matched attacks (adjusted difference: 8.8-10.0 percentage points). Near-misses, whose replies began with "access granted" but that scored as failures, were reused about as rarely as f

---

### [93] Decision Models as Judges for Hallucination Detection

**链接**: https://arxiv.org/abs/2610.37229
**作者**: Haozheng Liu, Zhaoqian Xue, Zhongyin Wang, Junting Mu, Zihui Ma, Shuya Feng 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are widely used as judges of model outputs (LLM-as-a-Judge), but they are costly and can hallucinate or be overconfident. Decision models are a potential alternative. They return a predefined verdict with a probability for each label instead of free-form text and are much cheaper and faster. We test this promise on hallucination detection. We build binary benchmarks for five hallucination types (9,852 items from six datasets) and compare five decision models with the generative judge gpt-6-sol. Performance depends strongly on the type: the best decision model matches gpt-6-sol in balanced accuracy on context inconsistency and comes within 3 percentage points on factual errors, but trails it by 4-8 points on logical and instruction inconsistency. Decision-model probabilities are overconfident, though less so than the GPT-6 models, and separate correct from incorrect decisions only moderately. We also find that a confidence cascade of decision models improves on the

---

### [94] Orthogonal and Parametrized Multi-Attribute Steering of LLMs

**链接**: https://arxiv.org/abs/2610.37517
**作者**: Remy Ogasawara, Cullen Anderson, Narmeen Fatimah Oozeer, Foad Namjoo, Amir Abdullah, Jens Kristian Refsgaard Schou 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering offers an effective and efficient way to modify an LLM's behavior at inference time. However, it remains unclear how to apply steering such that the signal is consistently strong and the steering strength has a universally interpretable meaning. We address this first by identifying the most steerable interval for each steering vector and rescaling the steering range accordingly. Building on this, we introduce a more interpretable method for steering, called parameterized steering which instead of pushing activations in a direction, it sets them at the desired trait strength. Next, with multi-trait steering, we find that naively combining vectors causes them to interfere with one another. In response, we develop a method to orthogonalize the vectors; it decouples these traits, allowing a model to exhibit one behavior without inducing the others, thus enabling multiple traits to be steered simultaneously.

---

### [95] PROBE: Frontier Coding Agents Find Different Bugs Than Maintainers Fix

**链接**: https://arxiv.org/abs/2610.35987
**作者**: Marco Paina, Mark Niklas M\"uller, Niels M\"undler-Sasahara, Martin Vechev
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Proactive bug discovery is an important software-engineering problem. Even though coding agents are already widely deployed in this domain, their capabilities remain understudied. In particular, the challenging task of finding all bugs that human maintainers would repair across an entire repository has not been studied yet. To close this gap, we introduce PROBE, a benchmark consisting of all 2,457 bugs fixed over the course of 18 months across 20 diverse GitHub repositories, together with a method for matching candidate findings to this partial reference set. We evaluate coding agents across frontier models and find they all achieve a recall of below $21\%$ and a precision of less than $9\%$ with respect to the reference set. While stronger models increase recall substantially from $8\%$ to $17\%$, they do not improve precision. Surprisingly, despite the low precision, LLM and human evaluators still judge $85\%$ of findings valid. Crucially, we find that found bug distributions are sim

---

### [96] Can LLMs Reliably Grade Olympiad Proofs? A Study of Mathematical Verification with LLMs

**链接**: https://arxiv.org/abs/2610.36767
**作者**: Azim Ospanov, Zijin Feng, Ding Ding, Chengwu Liu, Haoli Bai, Jiacheng Sun 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have made remarkable progress on solving competition-level mathematics, yet their ability to verify natural-language mathematical proofs remains relatively underexplored. This gap is especially pronounced for Olympiad-level proofs, which require meticulous assessment of each claim in a long reasoning chain. Current proof verification thus primarily relies on expert inspection, which is costly to scale. In this paper, we present a systematic study of LLM-based verification in this setting. Specifically, we introduce a human-curated dataset of USAMO 2025 candidate solutions with expert grading, and conduct a broad evaluation of existing LLM verifiers across frontier models. We also propose TROJAN, an iterative self-critique pipeline for generating high-fidelity adversarial proofs at scale. Our comprehensive evaluation covers 20 models spanning seven metrics, two prompt styles, three inference methods, and three prompt templates, showing that state-of-the-art 

---

### [97] Self-Keyed In-Parameter Memorization for External Memory-Free Dialogue Recall in Frozen Language Models

**链接**: https://arxiv.org/abs/2610.36948
**作者**: XinYu Piao, Myunghoon Ryu, Joongheon Kim, Jong-Kook Kim
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large language model maintains conversational content in an external storage that is outside the model and grows as the dialogue continues. This work assumes an environment where a language model has no external memory and no prior knowledge of the future question or its answer. The motivation is to research whether a dialogue can be stored in the model parameters and later answer a question about it. This work proposes self-keyed in-parameter memorization (SKIM), a closed-form method in which the model generates its own questions about each dialogue turn and writes those questions into its parameters as the keys that later retrieve the turn's content. Generating many varied questions for each turn allows a later user question to match one even when phrased differently, and its answer is recalled from the parameters alone. Evaluated on five language models, SKIM recalls most stored dialogue turns from later user questions, and it answers from the model parameters without any external

---

### [98] ReForest: Interpretability Meets Reasoning in Isolation Forest

**链接**: https://arxiv.org/abs/2610.37316
**作者**: Juyoung Seo, Geonwoo Bang, Dongho Kim, Moohong Min
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Statistical anomaly detection methods like Isolation Forest are efficient but suffer from a critical semantic gap. They identify numerical rarities but fail to understand the contextual meaning of data, often missing subtle, context-dependent anomalies. Conversely, Large Language Models possess strong semantic reasoning capabilities but are prohibitively expensive and slow for large-scale deployment. To bridge this gap, we propose ReForest, a novel framework that synergizes the statistical efficiency of Isolation Forest with the reasoning power of LLMs. ReForest transforms the latent decision paths of Isolation Forest into natural-language explanations, enabling an LLM to refine anomaly detection through an uncertainty-aware dynamic ensemble. This approach allows the model to adaptively weigh statistical and semantic signals based on uncertainty-driven instance-level confidence. Extensive experiments on four real-world datasets (Healthcare, Finance) demonstrate that ReForest significan

---

### [99] RPSD: Retrieval-Privileged On-Policy Self-Distillation with Optimal Transport

**链接**: https://arxiv.org/abs/2610.37281
**作者**: Dongyue Li and Zebang Cheng and Zhongyi Deng and Hongboxu and Yi Bin and Fei Ma
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sequential recommendation predicts a user's next interaction from historical behavior. Recent LLM-based methods recast this task as generative recommendation and increasingly adopt reinforcement learning such as GRPO for post-training. However, these methods suffer from two limitations, namely credit-blind optimization, where a sequence-level reward is shared across all generated tokens, and collaborative-blind supervision, where each training signal is derived from a single user and ignores behavioral patterns shared across similar users. To address both issues, we propose Retrieval-Privileged on-policy Self-Distillation (RPSD). For credit-blind optimization, we introduce on-policy self-distillation (OPSD), in which a teacher with privileged knowledge re-evaluates the student's on-policy response, and the token-level confidence difference between the student and teacher reshapes the shared sequence-level advantage into token-specific credit. However, the privileged knowledge in vanill

---

### [100] ETC-Bench: A Multilingual Benchmark for Evaluation-Side Transcript Canonicalization

**链接**: https://arxiv.org/abs/2610.36527
**作者**: Zhiheng Qian, Junhao Du, Jing Peng, Hanqi Li, Kunyang Peng, Feng Xue 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Written transcripts of the same speech can differ in ways that are not uniquely determined by the speech signal. We formulate evaluation-side transcript canonicalization (ETC), which maps multiple surface forms to a single canonical form when their differences are not determined by speech. To our knowledge, ETC-Bench is the first and most comprehensive multilingual benchmark for evaluation-side transcript canonicalization, covering 181 phenomenon types across 12 languages. Each instance is a minimal pair that shares a sentence context and differs only in a target span exhibiting one phenomenon. To evaluate both canonicalization success and semantic preservation, we propose Semantic-preserving Exact-match Normalization Accuracy (SENA), which combines exact agreement between independently canonicalized pair members with a pair-relative BERTScore constraint against information loss. We further introduce the Taxonomy-guided Agent Canonicalization Skill (TACS), which provides LLM agents wit

---

### [101] Detect Before You Disambiguate: Perturbation-Based Input Ambiguity Detection in LLMs

**链接**: https://arxiv.org/abs/2610.36353
**作者**: Tiejin Chen, Xiaoou Liu, Michael Clifford, Ahmadreza Moradipari, Yitao Chen, Kyungtae Han 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) often answer ambiguous inputs as if they had a single intended meaning. This is problematic because input ambiguity is an upstream source of uncertainty: when a prompt admits multiple valid interpretations, the key question is whether the model should answer directly at all. Existing input uncertainty methods often rely on LLM-generated statements or clarifications, but such transformations may already disambiguate the input before the ambiguity is measured. We propose a label-preserving perturbation framework for input ambiguity detection in which perturbations remain close to the original input while preserving its label. We instantiate this principle with two detectors: a black-box rule-based perturbation library and a white-box importance-guided method using model-internal signals. Experiments across four datasets in open-domain, conversational, and visual QA show that our methods outperform output-side uncertainty baselines and LLM-paraphrase-based per

---

### [102] Guided-RLVR: Guided Exploration in Reinforcement Learning with Verifiable Rewards

**链接**: https://arxiv.org/abs/2610.37041
**作者**: Bo Yang, Zishuai Zhang, Weihua Li, Qinnan Zhang, Sijia Wen, Hainan Zhang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) has shown strong empirical gains in improving the reasoning ability of large language models (LLMs) on tasks such as mathematics and programming. However, recent studies have shown that RLVR rollouts often collapse onto a narrow set of reasoning trajectories, limiting the explored reasoning space. Motivated by findings that thinking tokens at critical steps serve as critical structural elements in LLM reasoning pathways, we propose Guided-RLVR, a novel approach that augments RLVR with a lightweight controller. The controller strategically injects semantically meaningful steering tokens into the sampling distribution, encouraging the model to approach problems from multiple reasoning perspectives and thereby expanding the exploration space. Experiments on mathematical reasoning and code generation benchmarks show that Guided-RLVR consistently outperforms existing RLVR methods while producing more diverse reasoning trajectories.

---

### [103] CIVER: Causal Intervention Verification for Reliable Code Review

**链接**: https://arxiv.org/abs/2610.36010
**作者**: Xinyuan Song, Hasibul Haque, Jay Somasundaram, Ryan Turner, Bowen Zhu, Liang Zhao
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code review is essential for maintaining software repositories by identifying defects, improving code quality, and supporting reliable software evolution. With the growing adoption of LLM-based coding agents, an increasing number of code contributions and repository changes are generated by these agents. Consequently, LLM-based code review agents are becoming increasingly prevalent to evaluate these contributions and maintain software quality. However, LLM reviewers often generate lengthy reviews containing numerous potential issues, many of which are false positives or lack sufficient evidence. These unreliable reviews can mislead developers and downstream coding agents, motivating the need to distinguish actionable findings from unsupported claims. We propose CIVER, a causal intervention-based framework that identifies the core issues underlying code-review findings and distinguishes genuine defects from false positives. CIVER integrates three modules: a review module assesses findin

---

### [104] FinLLM-KG: Knowledge Graph-Enhanced LLMs for Financial Sentiment Analysis in Algorithmic Trading

**链接**: https://arxiv.org/abs/2610.36083
**作者**: Giorgos Iacovides, Oliver Hannibal, Wuyang Zhou, Danilo Mandic
**来源**: cs.CL cs.LG q-fin.ST q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Generative AI have substantially improved financial sentiment analysis through post-trained financial large language models (LLMs). However, existing approaches remain confined to predicting the sentiment of each article in isolation and operate as black boxes, which limits contextual understanding and hinders deployment in high-stakes financial decision-making. To this end, we introduce FinLLM-KG, a model-agnostic framework that combines causal LLMs with a financial knowledge graph, in order to inject temporally grounded, company-level knowledge from SEC 10-K filings at inference time, without updating model weights. Within FinLLM-KG, context is supplied either as a natural-language company profile or as a small set of relevance-ranked factual triples. This enables sentiment predictions to account for broader firm-level information rather than the article alone, at almost zero computational cost and for any causal LLM. In addition, attributing each article-level sen

---

### [105] A Quantitative Approach to Asch Conformity in Frontier Large Language Models

**链接**: https://arxiv.org/abs/2610.36668
**作者**: Senthil Rajasekaran, Stylianos Loukas Vasileiou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Asch conformity experiment has recently gained considerable attention as a way of measuring conformity in large language models (LLMs). While previous studies have focused on demonstrating conformity in LLMs, our work adds a further quantitative layer to this approach. Instead of sampling a frontier LLM on a suite of questions, our approach samples a single question repeatedly, leveraging the probabilistic nature of LLMs to produce a distribution of answers. In doing so, we can compare the distributions of answers before and after the model is presented with the manufactured consensus. Our experiments confirm that frontier LLMs do conform, reinforcing prior literature, and, through our distribution-to-distribution comparisons, provide additional quantitative data on the conditions that lead to conformity and the degree to which it occurs.

---

### [106] Exploring the Limits of the Delta Learning Hypothesis: Single-Pair Generator Biases in Direct Preference Optimization

**链接**: https://arxiv.org/abs/2610.37058
**作者**: Giuseppe Curci, Stefano Simonazzi, Andrea Molinari, Andrea Zugarini
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Direct Preference Optimization (DPO) typically relies on preference pairs generated from diverse model pools and ranked by an external LLM judge. The recently proposed delta-learning hypothesis suggests that comparable supervision can instead be obtained from a single pair of models by treating the larger model's response as preferred. We investigate the limits of this approach across model families and scales. We show, both theoretically and empirically, that fixed model pairs introduce systematic, generator-dependent biases that are predictive of the preference label independent of response quality. Consequently, DPO trained on single-pair data consistently underperforms multi-model preference data, despite the larger generator producing higher-quality responses, and we trace this gap to training dynamics consistent with reward hacking on these biases. We further show that simply increasing the number of generators, even without an external judge, is enough to partially mitigate this

---

### [107] ReCoPII: A Relation-Grounded Framework for Building Contextual PII Masking Datasets

**链接**: https://arxiv.org/abs/2610.35925
**作者**: Taehwan Lee
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training contextual masking systems for personally identifiable information (PII) requires examples distinguishing maskable from preservable mentions of one entity type, but privacy restrictions limit access to real data. Author-based augmentation (SPY) labels mentions unrelated to the author as non-PII, presuming a single data subject and overlooking others. We propose ReCoPII (Relation-grounded Contextual PII masking), a framework that builds such data without this premise: it plans ontology-constrained entity relations, writes insertion sentences with placeholders, reconstructs annotations with code, checks the result with a separate LLM, and derives MASK/KEEP labels from entity relations. On Korean documents from six domains, it yields ReCoPII-Ko, a corpus with relation, privacy, and MASK/KEEP annotations, which we validate. Across 300 pairs, four annotators agree with 88.42% of its sampled KEEP labels, against 26.27% for SPY-style augmentation of the same sources. Classifiers trai

---

### [108] SO-101 Bench: Accessible Spatial Manipulation

**链接**: https://arxiv.org/abs/2610.36420
**作者**: Truman Hickok
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-cost arms such as the SO-101 have become the most common entry point to robot learning, yet no released policy performs spatially constrained, language-conditioned tasks on them out of the box, and existing SO-101 benchmarks run only on physical hardware with simple tasks and few held-out objects. We introduce SO-101 Bench, a simulated benchmark for language-conditioned spatial manipulation built on an Isaac Lab digital twin of a real SO-101 setup. It has four tasks scored as five families, 138 objects in seen, unseen-instance and unseen-class splits, 916 evaluation episodes with subsets for held-out appearances, rotate-to-fit planning and occlusion memory, and 3,629 simulated demonstrations on which every learned policy is fine-tuned under an equal compute budget. The twin ranks policies as the real robot does: five policies trained without real data, four VLAs and an LLM agent, keep their exact ranking when the same weights run on the physical arm in an unseen environment with un

---

### [109] Who Knows What - and What Does It Support? Perspective-Bounded Evidence Calibration for Multimodal Theory of Mind

**链接**: https://arxiv.org/abs/2610.36824
**作者**: Ziqi Liao, Jiaqi Shen, Yiming Na, Kedi Lyu, Shao-Yuan Lo, Hongxia Xie
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Theory of Mind (ToM), the ability to infer others' beliefs, goals, and intentions, is a cornerstone of social intelligence. Multimodal ToM requires inferring an agent's mental state from evidence that is available to that agent, rather than from the complete episode observed by the solver. Existing LLM-based and Bayesian model-based approaches reconstruct global event traces, yet they do not explicitly distinguish objective events from agent-admissible evidence during hypothesis evaluation. Consequently, agent-inaccessible events or semantically misaligned actions and utterances may influence the inferred belief, goal, or social intention, leading to perspective leakage and source or route confusion. We formulate this limitation as an evidence-admissibility problem: evidence should contribute to a mental-state hypothesis only when it is accessible to the relevant agent, preserves its information source, and is diagnostic of the queried mental-state variable. To operationalize this prin

---

### [110] Remembering Is Not Enough: Refining Memories and Learning When to Use Them in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.36652
**作者**: Yipeng Hao, Yuxuan Cai, Wenkai Ji, Jie Zhou, Liyang Yu, Qin Chen 等 (9 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory helps LLM-based multi-agent systems reuse experience, but stored advice can be flawed or applied in the wrong situation. Team-level success or failure alone cannot reliably show whether a memory needs correction or should not have been used. We propose DiscernMem, a training-free framework that improves both memory quality and memory use. To improve quality, Defect-Aware Memory Refinement (DMR) compares team executions with a single memory and with no memory, diagnoses rule defects, and tests repairs on current and earlier tasks to guard against losing previously useful behavior. To guide appropriate use, Boundary-Learning Meta-Memory (BLM) records each memory's past uses and effects, learning when its owner role should apply or avoid it based on task context and incoming messages. Together, these components help teams correct flawed experience while retaining useful rules that were applied incorrectly. Experiments with Qwen3-4B-Instruct-2507 on four benchmarks show that Discern

---

### [111] Measuring Users' Security and Privacy Concerns About Third-Party Community Bots on Discord

**链接**: https://arxiv.org/abs/2610.36626
**作者**: Kofi Ampomah, Tu Le
**来源**: cs.CR cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Third-party community-based bots are central to how social platforms such as Discord work. They moderate content, manage roles, play music, and support AI-assisted conversations across millions of servers. Yet when a bot is installed in a server, it can access messages, user profiles, and server metadata concerning members who did not participate in the installation decision, with no standardized way to communicate the associated security and privacy implications. In this paper, we analyze 23,102 third-party Discord bots and 183,142 user reviews spanning 49 detected languages and five years of feedback (2021-2026). We employ LLM-based knowledge distillation and fine-tune a DeBERTa-based classifier to identify candidate security and privacy (S&P)-relevant reviews. After manually validating the complete classifier-positive set, we retain 8,832 reviews identified as S&P-relevant, representing an observed pipeline yield of 4.82%, and map them to a 31-theme S&P taxonomy extending prior work

---

### [112] Japanese Discourse Structure Analysis Based on Segmented Discourse Representation Theory Using LLMs

**链接**: https://arxiv.org/abs/2610.36667
**作者**: Satomu Tomisaki, Yosuke Mikami, Amane Watahiki, Hitomi Yanaka
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Discourse parsing based on Segmented Discourse Representation Theory (SDRT) is crucial for capturing the structural dynamics of dialogues. However, most prior research focuses on English, and its effectiveness for Japanese remains unclear owing to the lack of Japanese SDRT corpora. To address this issue, we construct Japanese SDRT corpora by translating existing English SDRT corpora using an LLM. Through a comparative evaluation of prompt-based and fine-tuned LLMs, we show that the models achieve comparable performance between English and Japanese, suggesting the cross-lingual applicability of SDRT-based discourse parsing. In order to investigate why the English and Japanese parsers achieve similar performance, we conduct ablation analyses on discourse markers and contextual inputs. Our results reveal that most of the Japanese discourse markers we examined have little impact, and the models' predictions depend heavily on contextual discourse relations rather than on the content of the 

---

### [113] EMMA: Structured Episodic Memory for Multi-Agent Workflow Synthesis

**链接**: https://arxiv.org/abs/2610.35966
**作者**: Ruijia Niu, Kaiwen Liu, Rose Yu, Kristina Klinkner
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying LLM agents in specialized domains often require fine-grained task-specific procedures and knowledge a general model lacks, yet parameter training is costly and non-interpretable, and hand-engineered agent systems shift the cost to expert labor. Episodic memory updates at context level, but single agent adaptation struggles to alleviate cross-task interference, especially with complex tasks such as multi-application navigation or data pool analysis. Although multi-agent evolution alleviates this problem, existing methods lack clear definitions on update rules and rely on the backbone model to decide where and how much the system changes. This ill-scoped evolution makes learning follow the backbone's structural preferences rather than the observed failures: one backbone accumulates skills while another spawns agents. We present EMMA (structured Episodic Memory for Multi-Agent workflow synthesis), which treats the configuration of a multi-agent system (controller routing memory,

---

### [114] Clearing the FoG: Training KG Agents to Retrieve the Evidence Behind Their Answers

**链接**: https://arxiv.org/abs/2610.37405
**作者**: Zongyuan Sun, Shuai Zhao, Yingjun Du, Ke Shu, Ziyue Zhu, Haoran Luo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can answer many factual questions correctly, but a correct answer is not necessarily a supported one. For an LLM agent, a knowledge graph (KG) plays two roles: as a source of answers, it supplies facts that the model lacks; as a source of evidence, it supplies the supporting triples that make an answer traceable and auditable. However, existing KG agents treat the KG only as a source of answers: their training data carries answers but not evidence, and their training rewards check the answer but not the retrieved evidence, so agents often answer correctly without retrieving the supporting triples. We propose FoG, a framework that trains KG agents to retrieve the evidence behind their answers. FoG consists of evidence-grounded synthesis, a KG interaction agent, and an evidence-coverage process reward (ECPR): the synthesis recursively hides explicit entities behind verifiable sub-questions, so that every question carries its supporting triples by construction

---

### [115] SCOPE: Source Credibility and Outlet Profiling Engine

**链接**: https://arxiv.org/abs/2610.35929
**作者**: Ilyas Nagiyev, Miras Baisbay, Daniil Orel, Preslav Nakov
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present SCOPE, a multi-agent system for profiling news media outlets with respect to bias, factuality, and credibility. Given an outlet URL, SCOPE coordinates specialized agents for article acquisition, content analysis, external evidence search, scoring, and report generation. The system follows an MBFC-style methodology while making intermediate evidence and agent outputs inspectable through a structured demonstration interface. On a benchmark of 200 media outlets, SCOPE outperforms LLM-only, article-only, search-only, and media-background-check baselines on most metrics, achieving the lowest bias and factuality MAE, perfect failed-fact-check detection, and the lowest factual error rate. These results suggest that decomposed, evidence-grounded agent workflows can support more transparent and reliable media profiling. Our code is available at https://github.com/mbaisbay/SCOPE, and a live demonstration at https://scope-demo.streamlit.app/.

---

### [116] RoboAuto: Autonomous Robot Program Search through Multi-Level Physical Understanding

**链接**: https://arxiv.org/abs/2610.36533
**作者**: Buzhao Liu, Jianing Ye, Xiu Yuan, Yangtong Feng, Chengsong Huang, Tyler Dinh 等 (9 人)
**来源**: cs.RO cs.AI cs.CL cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, LLM-based autonomous agents have shown strong capabilities in iteratively generating, evaluating, and refining executable solutions. In robotic manipulation, Code-as-Policy lets these agents search over modular and editable robot programs. However, effective program search requires physical understanding: agents must understand how objects can be manipulated, how scene geometry constrains actions, and why interactions succeed or fail. Existing methods rely mainly on execution feedback for program refinement, often leaving these physical questions unresolved. We introduce RoboAuto, a framework for robot program search that explicitly organizes physical understanding at the object, scene, and interaction levels through three components. First, a hierarchical knowledge base combines executable skills with object-centric knowledge of affordances, spatial relations, and action effects, learned from embodied data and online task solving. Second, scene grounding connects this knowle

---

### [117] Can LLMs Uncover Hidden Physical Laws through Free Exploration?

**链接**: https://arxiv.org/abs/2610.37649
**作者**: Zhen Yang, Wen Wang, Xander Xu, Ying-Cong Chen
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific discovery often begins with an unexpected observation that prompts a new research question. In a world with altered physical laws, can large language models (LLMs) notice unexpected behavior, such as heavier objects falling more slowly, and discover the law through experiments without being told what to investigate? To evaluate this ability, we introduce LongChang, an automated framework that creates simulated worlds with altered physics, where one or more laws differ from ordinary physics. The evaluated LLMs act as explorers, manipulating objects and building tools to investigate their own questions without research tasks or hints about these laws. Separate LLM agents generate and review scenes, review tool designs, and evaluate reports for correctness and experimental support using the altered physical laws and exploration records. These records guide scene evolution for further exploration, allowing the full cycle to run without human intervention. Among 12 LLMs, GPT-6-As

---

### [118] MedJev: Evaluating Zero-Shot System-One Decision Making in Medicine

**链接**: https://arxiv.org/abs/2610.36006
**作者**: Simon A. Lee, Jiahang Sha, Moonseong Jeong, Yunbei Pan, Jeffrey N. Chiang
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> System One decision models such as Jev answer structured questions in a single forward pass without generating text, offering fast and computationally efficient clinical decision support. We evaluate MedJev, an open System One model that runs locally on a laptop, across ten medical benchmarks spanning medical knowledge, diagnosis, and patient level prediction using MIMIC IV and MIMIC IV ED. We compare MedJev against zero shot LLM baselines, published GPT results, and supervised models. MedJev achieves accuracies of 72.5 percent on MedQA, 75.4 percent on USMLE, and 80.1 percent on NEJM, approaching published GPT 4 performance while maintaining well calibrated confidence estimates (ECE 0.028 to 0.063). On patient level tasks, MedJev achieves an AUROC of 0.926 for In Hospital Mortality, exceeding XGBoost (0.902), but underperforms supervised models on operational outcomes such as ED Triage Admission (0.745 vs. 0.809). Patient level predictions also exhibit substantial miscalibration (In H

---

### [119] Text Generation in Low-Resource Languages Using Human-Curated Vocabularies

**链接**: https://arxiv.org/abs/2610.37105
**作者**: Michael Christlambert Sinanta (1), Muhammad Dehan Al Kautsar (2), Amanda Nurul Izzah (1), Thanh-Nhi Nguyen (1), Phan Phuong Mai Chau (2), Zheng Wei Lim (3) 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic text generation offers a promising approach to alleviating data scarcity in low-resource languages. However, its effectiveness is inherently limited for languages that are scarcely represented, or entirely absent, in an LLM's pretraining data. At the same time, many such languages have human-curated vocabularies that provide rich lexical and semantic information, often accompanied by grammatical information such as part-of-speech labels. In this work, we ask whether LLMs can leverage these resources to generate coherent text in extremely low-resource and unseen languages. We introduce a framework that combines human-curated vocabularies with a small number of human-written exemplars that provide syntactic signals, while sampling candidate words according to a Zipfian distribution. Across languages with varying levels of resource availability, we evaluate the generated text using lexical diversity, off-target ratio, and human judgments of fluency. Our results show that reasoni

---

### [120] OpenGray: a benchmark for evaluating the decisions of radiotherapy planning agents

**链接**: https://arxiv.org/abs/2610.37081
**作者**: Humza Nusrat and Kundan Thind
**来源**: cs.AI physics.med-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background and purpose: Radiotherapy planning agents based on large language models (LLMs) decide when to submit a plan or request review but are evaluated mainly by dose. This study developed OpenGray, a benchmark of planning tasks with known correct decisions. Materials and methods: OpenGray adds tasks with known answers to the OpenKBP-Opt head-and-neck dataset, including two contradictions with dose goals proven incompatible and a feasible control with a stored plan meeting every hard goal. Four systems, from a rule-based planning script to a full LLM agent, were evaluated on 30 patients, the LLM-based ones with a commercial (Terra) and a local (Ministral 3 8B) LLM. Decisions, achieved dose, problem recognition, and technical failures were recorded and also read from logs of 39 stereotactic radiosurgery runs of SAGE, a clinical LLM agent. Results: With Terra, the script preceded by an LLM review and the full agent had decision accuracies of 95.4% and 92.1%, respectively, yet escalat

---

### [121] GraphRAGProv: GraphRAG Meets How-Provenance

**链接**: https://arxiv.org/abs/2610.37237
**作者**: Wadie El Amrani and Luis Gal\'arraga
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> GraphRAG systems often use knowledge graphs to retrieve relevant context for an LLM that produces the final answer. That makes answers more inscrutable and therefore less appealing for domains where transparency is paramount. We present GraphRAGProv, an architecture that executes SPARQL queries over source-grounded RDF graphs to compute answers and their how-provenance polynomials. These polynomials record which statement occurrences were used and how they were combined. Because each occurrence is linked to its source text, users can follow these links to check whether the extracted statements reflect the text and whether the query combines them to answer the question. Querying thereby becomes a way to inspect and evaluate the text-to-graph transformation. Our interactive demo examines 400 cases from two multi-hop QA benchmarks, revealing extraction and query errors even when the final answer is correct.

---

### [122] SpectRAG: Weighted Chunk Graphs for Token-Budgeted Context Selection in Multi-Hop Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2610.36991
**作者**: Zafer Sahinoglu, Abdulazeez Mohammed, Buse Yaren Kazangirler, Cahit Berkay Kazangirler
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) systems ground large language models (LLMs) by retrieving external evidence and conditioning generation on the retrieved context. Although dense retrieval is effective for local semantic matching, independently ranked retrieval can return redundant passages, miss cross-chunk dependencies, and provide incomplete evidence for multi-hop reasoning. We propose SpectRAG, a spectral graph-augmented retrieval framework that combines hybrid candidate seeding, weighted chunk graph construction, graph-based expansion, spectral relevance propagation, and token-budgeted context selection. Document chunks are represented by dense semantic embeddings and graph-spectral coordinates derived from a weighted chunk graph whose edges encode semantic similarity, document adjacency, section hierarchy, shared entities, citation links, and similarity between LLM-generated utility questions. At query time, SpectRAG builds a high-recall seed set using exact inner-product sear

---

### [123] BUSTA: Teaching Small Language Models to Reason About Binary Execution

**链接**: https://arxiv.org/abs/2610.36288
**作者**: Ritika Poddar, Aidan Fennelly, Deirdre Murphy, Eric Wolos, Corre L. Steele, Michael Doyle
**来源**: cs.CR cs.AI cs.LG cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLM) are increasingly applied to Reverse Engineering (RE) workflows. RE, however, differs from common LLM coding tasks as it requires models to reason about low-level program behavior. Furthermore, the deployment of tooling in resource-constrained sandboxed RE environments limits the ability to use frontier-scale solutions. We examine whether a targeted LLM training approach can transfer distinct RE skills to open models via inverse basic-block execution: given an x86-64 basic block and a desired output register state, the model predicts the input register values that produce it. Fine-tuning \texttt{Qwen3-1.7B} and \texttt{Nemotron-3-Nano} with Group Relative Policy Optimization (GRPO) raises knowable-register prediction accuracy from 73.2\% to 85.3\% and from 63.3\% to 95.2\%, respectively. Frontier models still score highest (up to 99.2\%), but our fine-tuned \texttt{Nemotron-3-Nano} comes within four points at a fraction of the parameter count. We release both

---

### [124] Agentic Data Sampling Framework for Multilingual ASR via Linguistic-Aware Error-Driven Optimization

**链接**: https://arxiv.org/abs/2610.36538
**作者**: Zhiheng Qian, Junhao Du, Jing Peng, Hanqi Li, Kunyang Peng, Feng Xue 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multilingual automatic speech recognition (ASR) has achieved rapid progress with large-scale pretrained models and multilingual speech corpora. Previous studies have proved the pivotal role of data sampling in multilingual ASR performance. However, existing sampling strategies largely rely on time-consuming manual, heuristic-based designs. To address this, we propose a linguistic-aware agentic data sampling framework that introduces a data sampling LLM agent into the multilingual ASR training loop. The agent is driven by a linguistically grounded rubric that analyzes ASR errors from phonological, morphological, and syntactic perspectives, and uses the resulting feedback together with training statistics, budget constraints, and algorithm profiles to select domain-level, sample-level, and token-level sampling strategies. This design turns evaluation results into adaptive data-selection decisions rather than treating WER/CER as final endpoints only. We conduct experiments on twelve Commo

---

### [125] Diagnosing and Correcting Bias in MLLM for Long Video Understanding

**链接**: https://arxiv.org/abs/2610.36210
**作者**: Xusheng Liang, Jianqiao Sun, Hao Zhang, Yulei Niu, Hengshuang Zhao, Jiawei Ma
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-video question answering is challenging since the answer often hinges on a few decisive moments scattered throughout the video, while memory constraints force Multimodal Large Language Models (MLLMs) to sample frames at extremely low rates, resulting in sparsity that risks omitting key evidence. Though aggressively enlarging the context size is intuitive, we argue that performance remains fundamentally constrained by the bias, \emph{i.e.}, the misleading cues caused by spurious \textit{linguistic} correlations and salient yet irrelevant \textit{visual} observations. In this paper, we first introduce {S-MME}, a benchmark designed to systematically diagnose shortcut-biased behavior in MLLMs. To mitigate this failure, we further propose a training-free framework, Counterfactual Long-video Evidence-Aware Reasoning (CLEAR). By treating the full video-question pair as a complete view, CLEAR estimates bias effects via augmented views by only keeping the question or locally salient visual

---

### [126] Decoupling Consistency and Conflict across MLLM Layers for Fake News Detection

**链接**: https://arxiv.org/abs/2610.36569
**作者**: Kai Qian, Dongjie Xu, Weijie Shi, Jiaqi Wang, Haolun Ma, Jia Zhu 等 (7 人)
**来源**: cs.CV cs.CL
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The trustworthiness of Web content faces a growing threat from multimodal fake news. Real news usually shows aligned image-text semantics, while fake news often contains a few conflicts at varying levels, such as mismatches in objects, scenes, events, and claims. However, existing methods usually treat consistency and conflict in a coarse and static way, limiting their ability to capture sparse conflicts and adapt to varying conflict levels. Inspired by the distinct knowledge encoded across layers in large language models, we propose Multi-Level Consistency and Conflict Decoupling (MLCCD), which captures conflicts at different levels from different layers of multimodal large language models (MLLMs). Specifically, we first use the MLLM's final decision representation to select visual and textual tokens relevant to the task, preventing irrelevant content from diluting sparse conflicts. Then, we preserve tokens whose representations change sharply between adjacent layers, capturing the kn

---

### [127] Task-Utility IQA: Rethinking Image Quality Assessment in Embodied Tasks

**链接**: https://arxiv.org/abs/2610.35905
**作者**: Jirong Zha, Yanwei Liao, Yemin Wang, Xiangmin Yi, Siqi Peng, Yingfeng Chen 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image quality assessment (IQA) underpins embodied imaging pipelines by judging whether visual quality satisfies downstream tasks, yet most existing methods learn task-agnostic scores aligned with generic human ratings on static benchmarks. This objective mismatches embodied and interactive settings, where image adequacy depends on task goals, context, and action requirements that shape an agent's decisions. We argue that IQA should shift from score regression to goal-conditioned judgment defined by embodied task utility. To this end, we propose an MLLM-based embodied IQA agent framework that reasons about task requirements, grounds quality evidence, and produces decision-facing assessments. A compact VisDrone evidence study shows that conventional perceptual metrics and generic MLLM-based IQA scores are weak proxies for downstream VLM task success, while a task-conditioned utility score better predicts whether visual input supports the target task. These findings support a task-utility

---

### [128] SMILE: Mitigating Object Hallucinations in VLMs via Small Model Assisted Contrastive Decoding and Image Lightweight Editing

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3DpGnlXKNzMB&hl=zh-CN&sa=X&d=9462083857645816474&ei=EAriatyrDtmY6rQPmpOekAQ&scisig=AIL1Nv711fUd6OZhDEjEXGL13clX&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=2&folt=kw-top
**作者**: SMAC Decoding
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> faithfully reproduce subtle errors in the descrip- 279 tions, limiting its effectiveness in amplifying the 280 target MLLM ’s hallucinations. To … First, following the protocol in 286 DeGF, we prompt the MLLM to generate a pre- 287 liminary description of the

---

### [129] VGIQA: Fine-Grained Image Quality Assessment with Visual Grounding Rewards

**链接**: https://arxiv.org/abs/2610.37186
**作者**: Weichang Wang, Liyu Chen, Shuyue Guan, Jie Hu, Fei Gao, Wei Li 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image quality assessment (IQA) aims to evaluate the perceptual visual quality of images. Recently, the rapid development of Multi-modal Large Language Models (MLLMs) has significantly advanced the IQA field. By integrating chain-of-thought (CoT) reasoning and reinforcement learning (RL), these models can generate more accurate and interpretable results while relying on less training data. However, existing MLLM-based methods are predominantly constrained to holistic, image-level evaluations and lack the capability to produce fine-grained, localized assessments, which substantially limits their practical applicability. To address this limitation, we propose VGIQA, a novel IQA model endowed with both local and global quality assessment capabilities. VGIQA is trained via a two-stage paradigm comprising a cold-start phase followed by reinforcement learning. Driven by carefully designed local quality assessment reward functions, our model exhibits exceptional image quality understanding on 

---

### [130] Eyegent: Visual Attention Orchestration on Concepts

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s11263-026-03042-4&hl=zh-CN&sa=X&d=18421820132488166861&ei=EAriatyrDtmY6rQPmpOekAQ&scisig=AIL1Nv5dHV-jfcvHKpTD4Jb64s8_&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=3&folt=kw-top
**作者**: A D'Amelio, S Patania, L Annese, G Boccignone - International Journal of Computer …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Despite these advances, most existing MLLM -based approaches either treat gaze as an auxiliary prediction target or incorporate it as an … To the best of our knowledge, Eyegent is the first architecture to integrate the normative tradition, the

---

### [131] BRAVO Benchmark: Evaluating MLLMs for BIM Scene-Based Compliance Checking

**链接**: https://scholar.google.com/scholar_url?url=https://api.taylorfrancis.com/content/chapters/oa-edit/download%3FidentifierName%3Ddoi%26identifierValue%3D10.1201/9781042025374-9%26type%3Dchapterpdf&hl=zh-CN&sa=X&d=18998114553859842&ei=EAriatyrDtmY6rQPmpOekAQ&scisig=AIL1Nv5IUQG0HQmOIEnOq1lb9pKd&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=1&folt=kw-top
**作者**: M Zykova, Y Kim, C Du, A Borrmann, G Lee - Digital Building Permitting, 2027
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The study evaluates whether an MLLM can assess the compliance of a BIM-derived scene with a given … MLLM interpretation and reasoning abilities in BIM-based compliance checking, it was necessary to establish a taxonomy of these abilities

---

### [132] Robustness of multimodal large language models in facial expression recognition: A human-comparative study

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0031320326021400&hl=zh-CN&sa=X&d=7746834166232647753&ei=EAriatyrDtmY6rQPmpOekAQ&scisig=AIL1Nv4uNfUw00RKTXJdH_LC1CKA&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=0&folt=kw-top
**作者**: L Zhao, M Sun, J Li, Y Liu, J Ma, S Fu 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> MLLM inference with the human “rapid categorization” paradigm [40]. Prompts were functionally equivalent to human instructions but adapted for MLLM … Regarding the MLLM Procedure, we constructed structured prompts to mirror the

---

### [133] SOMA: A Benchmark for Fine-Grained Egocentric Behavior and Body-Motion Understanding

**链接**: https://arxiv.org/abs/2610.36384
**作者**: Matea Tashkovska and Na\"el Ouerghemi and Haozhe Qi and Alexander Mathis
**来源**: cs.CV cs.AI cs.CL q-bio.NC
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Perceiving human body motion is critical for multimodal systems that understand and assist people. Yet current evaluations of Multimodal Large Language Models (MLLMs) largely focus on objects, scenes, and coarse actions, leaving their ability to reason about the body itself poorly assessed. This is especially challenging from the egocentric perspective, in which the body is only partially visible and motion must be inferred from occluded and temporally distributed cues. We introduce SOMA, a benchmark for fine-grained body-motion understanding from egocentric video, comprising 1,632 human-verified questions across three capability axes: body configuration, motion dynamics, and temporal reasoning. We evaluate 37 leading closed-source, open-source, and specialized egocentric MLLMs, complemented by an extensive human evaluation. We find that humans also find this task difficult from video alone (68.5% accuracy), yet clearly outperform the strongest MLLM (Qwen3.6-27B), which reaches 50.0% z

---

### [134] NEUROFUSIONGPT: a multimodal transformer framework for stress-level classification via cross-attention fusion of EEG and ECG signals

**链接**: https://scholar.google.com/scholar_url?url=https://scholarworks.calstate.edu/concern/projects/rv043471b&hl=zh-CN&sa=X&d=16422429859749384961&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv6fHlc-u9BpHG5fwCVikYSg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=2&folt=kw-top
**作者**: B Chandra Shekar Reddy
**来源**: 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> deep learning framework that fuses electroencephalogram ( EEG ) and electrocardiogram (… employs a Transformer encoder for EEG data, treating the 16 EEG channels as a sequence … -attention module, where EEG attends to ECG and

---

### [135] Geometric Positional Encoding and Dynamic Weight Fusion for EEG -fNIRS Emotion Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-3425/16/11/1158&hl=zh-CN&sa=X&d=5998863956117905775&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv7Qz75kcqKp2A6TtVk2dJts&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=0&folt=kw-top
**作者**: Y Zhou, X Zhang, G Chen, H Li, L Huang, Y Sun - Brain Sciences 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Given that publicly available EEG and fNIRS datasets remain relatively scarce, and these two signals are valuable for revealing neurovascular coupling mechanisms, this study constructs a synchronously recorded EEG and fNIRS

---

### [136] Cross-subject decoding of imagined speech from scalp EEG : a leakage-controlled evaluation on three public corpora

**链接**: https://scholar.google.com/scholar_url?url=https://ui.adsabs.harvard.edu/abs/2026arXiv261020954I/abstract&hl=zh-CN&sa=X&d=7217027902171998901&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv5M5sQDATk7N4yyfQsR7SPJ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=3&folt=kw-top
**作者**: B Isoyiza Adeika, O Osuagwu - arXiv e-prints, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Objective. A decoder of imagined speech that works for a new user without calibration would make a non-invasive speech interface practical. We tested whether imagined-speech content recorded with scalp electroencephalography ( EEG )

---

### [137] Normative Deviation Modeling for EEG-based Depression Detection

**链接**: https://arxiv.org/abs/2610.37338
**作者**: Wan Jiang, Jingqi Cheng, Hui Zhang, Xu Zhao, Xiaojing Chen, Shengeng Tang 等 (8 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web-enabled digital health services are expanding access to physiological monitoring and mental health screening. However, electroencephalography (EEG)-based major depressive disorder (MDD) detection remains challenging across heterogeneous data sources, where individual variability and acquisition differences may affect disease-related representations. In this work, we investigate the use of healthy normative references for EEG-based MDD detection. Specifically, structural and distributional reference models are independently trained using healthy control (HC) recordings to characterize departures from healthy EEG patterns. We develop two diagnostic approaches that incorporate normative deviations at different representation levels. Scalar-level Normative Deviation-guided Diagnosis (S-NDD) summarizes structural and distributional deviations into scalar scores and integrates them with deep EEG representations. Feature-level Normative Deviation-guided Diagnosis (F-NDD) retains dimension

---

### [138] Prefrontal EEG Frameworks for Real-life Cognitive State Monitoring

**链接**: https://scholar.google.com/scholar_url?url=https://trepo.tuni.fi/bitstream/handle/10024/241126/978-952-03-4836-6.pdf%3Fsequence%3D2&hl=zh-CN&sa=X&d=1552667180870616652&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv5sijNrV0mcE88O3gvn9DtV&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=4&folt=kw-top
**作者**: MB VAND
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Although electroencephalography ( EEG ) provides a direct measure of brain activity, many existing approaches rely on complex multi-… number of prefrontal EEG channels can provide reliable and generalizable cognitive state monitoring

---

### [139] … Brain Age Modeling in African Populations: Quantifying Cross-Population Generalization Gap and Brain Age Gap in Healthy Nigerian Adults Using Low-Cost EEG

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3D4n0xLUk4RW&hl=zh-CN&sa=X&d=5494586700120780652&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv5BjUsfXHkSw5LrNXLIRoof&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=5&folt=kw-top
**作者**: O Ajayi, OS Solagbade, M Obot-Obot, TD Ilori… - Africa in AI Affinity Group at Neural …
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We developed a resting-state electroencephalogram ( EEG ) brain age framework using a North … This study aims to address this gap by training EEG brain age models on a large public North … We report, here the findings as an initial normative

---

### [140] Exact Spectral Uncertainty Decomposition for Linear-Gaussian Bayesian M/EEG Inverse Problems

**链接**: https://arxiv.org/abs/2610.30207
**作者**: Ismail Huseynov, Stefan Haufe
**来源**: cs.LG cs.CE
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] MEL: Coordinate-Preserving EEG Tokenization for fMRI Translation

**链接**: https://arxiv.org/abs/2608.29304
**作者**: Xiangyu Liu, Zeting Yan, Zhitong Yin, Boyang Li, Xi Zhang
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] An adaptive transformer-based model with entropy-driven knowledge distillation for single-channel EEG REM sleep detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-62389-3_reference.pdf&hl=zh-CN&sa=X&d=12171043355440870524&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv6PF-KDoF8EfD-jtARu-DZW&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=1&folt=kw-top
**作者**: JJ Huang, SC Chen, I Dwiwahyono - Scientific Reports, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> sleep detection from singlechannel electroencephalogram ( EEG ) signals. By dynamically … EEG applications. These results suggest that uncertainty-aware adaptive distillation may support accurate and computationally efficient REM sleep detection

---

### [143] ORBITAL: Optimization of Robust Brain--Computer Inference Through Architecture-Aware Low-Precision Compression

**链接**: https://arxiv.org/abs/2610.36411
**作者**: Saim Rehman, Muhammad Shafique
**来源**: cs.CV cs.CR cs.LG eess.SP
**匹配关键词**: EEG, BCI
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compact electroencephalography (EEG) decoders enable embedded brain--computer interfaces (BCIs), but compression can alter adversarial robustness without proportional hardware savings. We present ORBITAL, a robustness-constrained framework combining hardware-realizable structured compression, recovery-aware operating-point selection, multi-attack evaluation, and native edge validation. Across nine subjects and three seeds on BCI Competition IV-2a, S25-TRADES achieves the highest observed mean true-union robustness among compressed EEGNet models (23.06% vs 21.27% for standard Full), with 26.27% fewer parameters and 25.10% fewer MACs. Matched controls identify TRADES as the main source of robustness recovery, improving S25 union accuracy by 6.74 percentage points over clean recovery (p=0.0039), while per-example analysis reveals boundary redistribution rather than uniform margin expansion. On Jetson Orin Nano, FP16 compression reduces board energy by up to 16.20% and latency by 8.00%. De

---

### [144] Tag: bipolar disorders

**链接**: https://scholar.google.com/scholar_url?url=https://labs.utdallas.edu/ionm/tag/bipolar-disorders/&hl=zh-CN&sa=X&d=2500039478042769032&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv7xLSH3OSfMPL4OkC6Xc0KD&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=8&folt=kw-top
**作者**: M Solomon
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> of this literature review is to examine the previous research regarding EEG variance between individuals diagnosed with Schizophrenia, Bipolar, and PTSD when compared to normal controls in hopes of identifying fundamental EEG

---

### [145] Physiology-Informed Audio Quality and Listening Effort Estimation

**链接**: https://arxiv.org/abs/2610.36865
**作者**: Niall McGuire, Dimitra Emmanouilidou
**来源**: cs.SD cs.NE
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio systems aim to maximise the listener's perceived quality, traditionally evaluated through mean opinion scoring (MOS), a subjective process that is slow, costly, and collected only after playback. Machine learning now predicts MOS directly from the audio, but in generalising across participants it tends to discard the subject variance that defines individual perception. Neurophysiological measures may offer a complementary signal taken directly from the listener, objective, implicit, and continuous, though prior work has relied on laboratory-grade EEG and fNIRS. We ask how practical consumer-grade devices compare, and whether they might recover population-level audio-quality trends and, when calibrated per listener, track that listener's effort. Recording 32-channel laboratory EEG alongside wearable EEG, fNIRS, and eye tracking from thirty listeners, our results suggest commercial wearable and optical sensing can decode audio quality at statistically significant levels and recover

---

### [146] Progressive multimodal fusion for seafarer workload recognition: A three-tier framework for real navigation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0029801826049590&hl=zh-CN&sa=X&d=5253789042231037704&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv7Eayalns_SZIo5IAT5Pr5S&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=9&folt=kw-top
**作者**: Y Ma, Q Liu, L Yang, Z Zhang, Z Yang - Ocean Engineering, 2026
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The first, a deep representation pathway, converted each EEG segment into a time-frequency image ( EEG scalogram) using the continuous wavelet transform (CWT), with the Morlet wavelet as the basis function, leveraging deep convolutional networks'

---

### [147] MKDC-IGN: An interpretable graph network with multi-layer key directed connections for the diagnosis of depression

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0031320326021461&hl=zh-CN&sa=X&d=8549558759539531036&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv7YUh_bb38LRCVtUXS9GqVM&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=6&folt=kw-top
**作者**: N Chu, N Wang, X Zhang, R Liu, S Sun, B Hu 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> dependencies among EEG channels. They failed to recognize that the brain is essentially a highly complex network of connections. … In EEG -based depression studies, GNN typically models EEG channels as nodes and the FC between them as

---

### [148] MM-Net: A Multimodal Multi-Task Network for Sleep Staging and Sleep Apnea Assessment After Ischemic Stroke

**链接**: https://arxiv.org/abs/2610.36583
**作者**: Md Wahiduzzaman Suva, Esm E Moula Chowdhury Abha, Md Imtiaj Alam Sajin, Md Iftekharul Mobin, Jia Uddin
**来源**: cs.LG cs.AI eess.SP
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated polysomnography after ischemic stroke is challenging because of altered sleep-related neural activity and concurrent respiratory disturbances. Existing stroke-specific approaches mainly address sleep-stage classification, leaving joint analysis of sleep architecture and respiratory events underexplored. Moreover, adapting pretrained EEG encoders introduces a representation inconsistency when downstream models are trained on embeddings from previously seen patients but evaluated on unseen individuals. We propose MM-Net, a multimodal multi-task framework that resolves this inconsistency through cross-fitting and ridge-based embedding alignment. Sleep-adapted EEG-EOG representations and engineered neural descriptors are fused with learned cardiorespiratory features through cross-attention and shared temporal modeling for simultaneous sleep staging and respiratory-event detection. On iSLEEPS (99 patients with subacute ischemic stroke), ten-fold patient-independent evaluation achi

---

### [149] Transcranial Evoked Potentials are Minimally Influenced by Afferent Feedback From Peripheral Muscle Contraction

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s12264-026-01729-9&hl=zh-CN&sa=X&d=16323242833725941724&ei=EAriauXAA-S0ieoP99PDsQo&scisig=AIL1Nv5A2hpBVIF-H1WEFVp0l1Yi&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=7&folt=kw-top
**作者**: M Marco, G Andrea, F Andrea, P Carlo, L Giorgio… - Neuroscience Bulletin, 2026
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> EEG responses across trials yielding large versus small motor outputs, while peripheral stimulation isolated pure afferent components. Bayesian analysis revealed that larger motor outputs covaried with distinct EEG … minimally to TMS-evoked

---

### [150] A note on data-efficient finetuning of vision foundation models

**链接**: https://arxiv.org/abs/2610.37510
**作者**: Niclas Hergenr\"other and Antonio Orvieto
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting foundation models to a new task within or beyond the training domain is the de facto standard for building specialized machine learning models. Recently, Visual Prompting (VP) has emerged as a promising technique for efficient knowledge transfer. As new foundation model families~(like Mamba) get introduced and VP pipelines such as AutoVP reach greater maturity, we find a growing need for a systematic evaluation of current approaches. In this work, we assess the performance of the latest models, comparing them to earlier architectures and alternative fine-tuning methods, to better understand the progress, challenges and opportunities in the field of efficient fine-tuning under resource limitations. Towards this goal, this paper provides a concise empirical overview of the interactions among foundation model families (Attention-, Convolution-, and Mamba-based) and transfer paradigms: VP, Linear Probing (LP), Full Fine-tuning (FFT) and Low Rank Adaptation (LoRA). Our work builds 

---

### [151] FrameForge: Harnessing Priors of Video Foundation Models for Unified Image Generation

**链接**: https://arxiv.org/abs/2610.36545
**作者**: Yijing Lin, Zhendong Mao, Mengqi Huang, Yuxin Wang, Yongdong Zhang
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified conditional image generation requires a single model to preserve different aspects of a visual input while producing a target image that follows textual guidance. Pretrained video models provide a promising foundation by encoding visual transformations across time, yet existing approaches typically assign the condition and target to fixed temporal positions. We observe that condition-target relationships vary substantially across generation tasks, while video models naturally encode visual transformations at different temporal scales. This motivates us to model conditional generation through input-adaptive virtual temporal relations. We propose FrameForge, which captures two complementary aspects of such relations. Mixture of Temporal Experts (MoTE) models how far the target lies from the condition by dynamically selecting temporal RoPE experts with different virtual intervals. Chain of Temporal Reasoning (CoTR) models how the condition is transformed into the target through a 

---

### [152] PRISM: Pathology Reliability In Scarce-label Medicine. A Tile-level Benchmark of Pathology Foundation Models

**链接**: https://arxiv.org/abs/2610.36517
**作者**: Alicem Koyun
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models are typically benchmarked on classification performance at full label availability and on in-distribution test sets, while calibration, behavior at low label budgets, and robustness under cross-institutional shift are seldom evaluated jointly. We introduce PRISM, a tile-level benchmark that measures the reliability of pathology foundation models along four axes: model choice, label fraction, calibration, and out-of-distribution transfer. PRISM evaluates eight foundation models (CLIP, PLIP, CONCH, UNI, Virchow2, GigaPath, H-Optimus-0, Midnight) on six tile-level datasets at six label fractions (1% to 100%) with three seeds (864 linear probe runs), extended with a five-hospital Camelyon17 study of 20 directed transfer pairs. Four phenomena emerge. (i) Under full supervision, AUROC rank predicts post-temperature calibration rank consistently across datasets (Spearman rho = 0.52, I^2 = 0%), whereas at 1% labels the relationship becomes dataset-specific (rho = -0

---

### [153] DART: Differentiable Dynamic Adaptive Region Tokenizer for Vision Foundation Models

**链接**: https://arxiv.org/abs/2506.10390
**作者**: Shicheng Yin, Kaixuan Yin, Yang Liu, Weixing Chen, Liang Lin
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [154] Multibranch Ensemble Head in Vision Foundation Models for Efficient Cucumber Phenological Stage Classification

**链接**: https://arxiv.org/abs/2610.37118
**作者**: Kostiantyn Khabarlak
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision Foundation Models (VFMs) pretrained with self-supervised learning, such as DINOv2, provide highly transferable features, yet adapting them to small, domain-shifted datasets is still challenging. We propose a regularizing multibranch ensemble head: a training and inference scheme that pairs low- and high-capacity branches, samples a single branch stochastically at each training step, and averages both branches in probability space at inference. The design adds negligible parameters and essentially no inference overhead over a single heavy head, while improving the accuracy-efficiency trade-off under data-scarce conditions. Accurate classification of plant growth stages is critical for precision agriculture, enabling timely decisions on fertilization, irrigation, and harvesting. Therefore, as a challenging practical case we use cucumber phenological stage classification, in which flowers and fruits are frequently occluded by foliage, and stage transitions manifest primarily as sub

---

### [155] Timestral

**链接**: https://arxiv.org/abs/2610.37585
**作者**: Adrien Petralia, Alexandre Gavaudan, Artjom Joosen, Etienne Goffinet, Richard Kurle, Yassine El Ouahidi 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Timestral, a family of four time series foundation models for probabilistic forecasting, with 5M, 28M, 123M, and 209M parameters. Timestral sets a new state of the art on GIFT-Eval, TIME, and fev-bench, where Timestral-209M and Timestral-123M take the top two places on every metric. We achieve this with three ingredients: Decoupled Horizon Forecasting (DHF), which separates prediction tokens from the causally encoded context, so that longer horizons are trained without masking context and each observed value is both a forecast target and context for later forecasts; a covariate framework that natively supports known-future covariates within a causal architecture; and a two-stage pipeline that pretrains exclusively on a diverse, large-scale synthetic corpus before post-training on a mix of real and synthetic data with extended context. This report describes the model design and its benchmark results. Weights for all four models are available on Hugging Face and inference co

---

### [156] Evaluating AlphaEarth Embeddings for Crop Classification: Separability, Temporal Dynamics, and Cross-Regional Transferability

**链接**: https://arxiv.org/abs/2610.36857
**作者**: Priyanka Goyal, Maitreyee Sar, Adway Mitra, Manjira Sinha
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth Observation (EO)-based agricultural monitoring is shifting from pixel-level spectral analysis toward representation-driven modeling, yet systematic evaluation of learned representations across spatial, temporal, and domain-generalization dimensions remains limited. Geospatial foundation models generate high-dimensional embeddings encoding spatio-temporal land-surface properties, but their utility for agricultural applications remains insufficiently understood. This study presents a representation-agnostic evaluation framework integrating geometric separability, temporal dynamics, spatial robustness, and cross-regional generalisation. A 64-dimensional AlphaEarth embedding space is benchmarked against Sentinel-2 reflectance, NDVI-derived phenology, and harmonic features using field-scale data from the Conterminous United States (CONUS; 2017-2023) and Northern India (2021). Traditional features achieve strong linear separability (Fisher ratio), while embeddings provide superior dist

---

### [157] Recall or Relearn? A Mixture of In-Context Experts for Recurring Concept Drift

**链接**: https://arxiv.org/abs/2610.36585
**作者**: Zhangkai Wu, Xu Zhang, Zhihong Cui, Yiqi Wang, Yi Zhang
**来源**: cs.LG cs.IR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are being applied to Web data streams such as network intrusion detection, where they adapt by updating the labelled rows of their context without retraining. When a past concept returns after leaving the context, a TFM faces a recall-or-relearn decision between restoring stored rows of the concept and relearning it from new labels. We propose MICE (Mixture of In-Context Experts), a training-free learner that cuts the stream into segments at detected changes. It merges a closed segment into a stored context when the TFM's estimated additional error on the segment is within a tolerance, under a capacity limit on stored contexts. A fast level weights the stored contexts and first-in-first-out (FIFO) windows by the log-loss of their predictions on the last labelled batch. We show that, with pure stored contexts and a margin condition, this fast level gains over relearning, in expected accuracy, the normalised positive area between the stored context's accu

---

### [158] Any3R: Feedforward 3D Reconstruction from Any Camera Type

**链接**: https://arxiv.org/abs/2610.36150
**作者**: Jingong Chen, Qingwen Zhang, Youming Deng, Chulwoo Pack, Olaf Wysocki, Boris Jutzi 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geometry foundation models recover camera poses and dense geometry from a set of images with a feed-forward network, but they expect pinhole images. That assumption is inside the backbone too: the positional encoding and the training loss both bind an image position to a direction in space, and both depend on the lens. We condition both on the dense ray field, the unit direction through every pixel, which describes any central camera without a lens type, distortion coefficients or a bound on field of view. Angular coordinates give the rotary encoding the measured ray angle of each patch, evaluated per view, and solid-angle weighting scales the point loss by the area each pixel covers on the sphere, so neither the encoding nor the supervision depends on the lens. Any3R is therefore a feed-forward model that takes any central camera, and is robust to mixing many camera types per scene, with no retraining per lens. On a benchmark of thirteen central cameras across three datasets, where ev

---

### [159] LoRA on a Budget: Function-Aware Post-Hoc Compression for Adapter Fleets

**链接**: https://arxiv.org/abs/2610.36386
**作者**: Shenghui Li, Thiemo voigt
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-Rank Adaptation (LoRA) has become a key mechanism for efficiently specializing foundation models into many task- and user-specific variants. Serving many LoRA adapters under a shared resource budget turns post-hoc compression into a two-level allocation problem: rank must be distributed across layers within each adapter and across adapters within the fleet. Although trained LoRAs contain substantial spectral redundancy, spectral reconstruction alone does not determine how much compression an adapter can functionally tolerate. We formulate fleet compression through a functional rank-distortion frontier for each adapter, followed by fleet-level minimax allocation under a shared rank budget. Given exact frontiers, this decomposition is equivalent to joint optimization over all layer ranks. We introduce Functional Rank Allocation (FRA), an unlabeled method for constructing practical frontiers. FRA measures isolated module truncations end to end, uses these measurements as an additive s

---

### [160] SuperJEPA: Pretraining with a Supervision-Augmented Joint-Embedding Predictive Architecture for High Energy Physics

**链接**: https://arxiv.org/abs/2610.36121
**作者**: Dylan Sheldon Rankin and Ho Fung Tsoi
**来源**: hep-ex cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models often obtain powerful results through very large unlabeled training datasets that dwarf available labeled datasets in size, but high energy physics already provides large samples of high-fidelity labeled simulation. We therefore ask whether self-supervised objectives improve over supervised pretraining alone when large labeled samples already exist. We introduce SuperJEPA, a joint-embedding predictive architec- ture augmented with a supervised objective, and find improved downstream jet-tagging performance across multiple tasks, model sizes, and pretraining dataset sizes. The gains persist for both frozen and fine-tuned encoders, motivating predictive self-supervision in future large-scale particle-physics foundation models.

---

### [161] GarmentSegAgent: Autonomous Garment Segmentation for Web Fashion Images via Textual Self-Refinement

**链接**: https://arxiv.org/abs/2610.36506
**作者**: Jia Chen, Chao Huang, Xinrong Hu, Mingdi Huang, Ruyang Zhao, Jun Bai
**来源**: cs.CV cs.MA
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web fashion images support applications such as visual product search and consumer-to-shop matching, yet their visual heterogeneity makes reliable garment segmentation challenging. Despite advances in promptable segmentation, autonomously identifying and correcting garment-specific errors without human-provided spatial prompts remains difficult. We propose GarmentSegAgent, an autonomous framework that integrates semantic planning, spatial execution, and visual evaluation through iterative textual self-refinement. At its core, we introduce CAST (Constrained Attribution-guided Selective TextGrad), which connects visual error attribution with targeted textual optimization. CAST identifies instruction components responsible for segmentation errors, selectively updates them through textual gradients, and validates the resulting instructions against garment-specific constraints. This enables image-specific error correction at inference time while keeping the underlying foundation models froz

---

### [162] When Slides Met Scans: Cross-Attention for Renal Cancer Prognosis

**链接**: https://arxiv.org/abs/2610.36364
**作者**: Anusha Krishnamoorthy and Basudha Pal
**来源**: eess.IV cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Histopathology and computed tomography (CT) provide complementary views of renal cancer. We connect these modalities through bidirectional cross-attention between 16 histology prototypes and up to 32 kidney-centered CT tokens from frozen foundation models. In 210 TCGA-KIRC patients with 46 disease-specific survival (DSS) events, 5-fold evaluation yielded a C-index of $0.760\pm0.081$ and 3-year AUROC of 0.773 (95\% CI 0.678--0.860), the highest averages among evaluated unimodal and fusion baselines. External testing in 180 CPTAC-CCRCC patients yielded DSS C-index of 0.629 with CT withheld. Attribution analysis linked predictions to image regions while exposing acquisition artifacts. These findings support further study of cross-scale fusion and independent multimodal validation.

---
