# 📑 论文索引 - 2026-10-08

共 214 篇论文

---

### [1] What Words Keep of a Place: Zero-Shot Language Reasoning for Cross-View Geo-Localization

**链接**: https://arxiv.org/abs/2610.07269
**作者**: Ayesh Abu Lehyeh, Jay Hwasung Jung, Safwan Wshah
**来源**: cs.CV cs.LG
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-view geo-localization is commonly solved as an image retrieval problem, matching a ground-level image against a database of satellite tiles through a jointly trained embedding. Such models are accurate, but they need large paired supervision and cannot show what evidence supports a match. In this paper, we study a different question: how much of this task can be solved through language alone? We prompt a multimodal large language model (MLLM) to describe each ground panorama and each satellite tile as structured text, and localize by comparing these descriptions. No component is trained. We evaluate on 9,826 VIGOR pairs from four U.S. cities, in three settings. First, the descriptions are faithful but not discriminative. They agree closely across the two views, yet ranking the full pool by description similarity almost never returns the correct tile (0.39% Recall@1). Second, we narrow the pool to ten neighboring tiles, as a coarse prior would do. The same descriptions now become 

---

### [2] Selective Critique for Cost-Aware LLM Agents in Long-Horizon Decision Making

**链接**: https://arxiv.org/abs/2610.07335
**作者**: Heewon Park, Somin Im, Minhae Kwon
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving the reliability of large language model (LLM) agents in long-horizon decision-making remains a key challenge. When deployed as autonomous agents interacting with complex environments, early mistakes can propagate through trajectories and cause cascading failures. Recent approaches improve reliability by incorporating external critique or deliberation, but invoking these mechanisms at every step substantially increases token consumption and latency, limiting practical deployment. We propose SAG (Self-improving Agent with Gated critique), a cost-aware framework that formulates critique invocation as a step-wise decision problem during long-horizon interaction. SAG introduces a lightweight, training-free gating mechanism that estimates the utility of critique using action-level ambiguity signals--global entropy and local top-2 margin--computed over admissible actions. From a decision-theoretic perspective, this mechanism approximates the Value of Information (VoI) of critique, e

---

### [3] Detecting LLM-Assisted Vietnamese Writing via Keystrokes under Behavioral Manipulation

**链接**: https://arxiv.org/abs/2610.07700
**作者**: Thanh Dong and An Ngo and Minh Dau and Rajesh Kumar
**来源**: cs.CL cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study the robustness of keystroke dynamics for detecting large language model (LLM)-assisted writing. We introduce a Vietnamese keystroke dataset capturing realistic writing modes, including bona fide composition, transcription, and paraphrasing. We also define a behaviorally grounded threat model in which users deliberately alter typing patterns. To implement the threat model, we create behaviorally manipulated variants of the data designed to evade keystroke-based detection. We evaluate four keystroke modeling approaches: temporal and rhythmic representations, and sequential representations modeled with a one-dimensional convolutional neural network (1D-CNN) and TypeNet, under user-independent and context-independent settings. The results show that sequential models outperform feature-based approaches in most cases and that keystroke signals encode discriminative information about the writing process. However, detection is not uniformly robust: transcription is reliably identified

---

### [4] Adaptive Power Sampling for LLM Reasoning

**链接**: https://arxiv.org/abs/2610.08563
**作者**: Bingnan Xiao, Chenhao Yang, Bingcong Li, Wei Ni, Xin Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sequence-level power sampling has recently emerged as a training-free approach to reasoning by sampling from a sharpened output distribution of a base large language model (LLM). Nevertheless, existing methods typically sharpen the base model distribution uniformly across queries, overlooking variations in query difficulty and in how well the base model already handles each query. The goal of this work is to equip power sampling with query adaptivity. Theoretically, we show that the benefits of further sharpening are determined by the self-reward gap between correct and incorrect responses. Based on this insight, we propose \emph{Adaptive Power Sampling} (APS), which adjusts the sharpening exponent on a per-query basis at test time using the relationship between answer agreement and the model's self-reward. Experiments across diverse reasoning tasks, including MATH500, HumanEval, and GPQA, show that APS consistently outperforms power sampling with a fixed sharpening exponent, without a

---

### [5] CACHEFORGE: LLM-Guided End-to-End Generative Cache Replacement Policy for Performance and Hardware Efficiency

**链接**: https://arxiv.org/abs/2610.07668
**作者**: Kaushal Mhapsekar, Bita Aslrousta, Brijesh Kumar Bhayana, Paula Contreras, Azam Ghanbari, Ethan Goodman 等 (8 人)
**来源**: cs.AR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern cache replacement designs saturate because they operate within fixed representational structures, hand-crafted and heuristic based feature-engineered predictors, or offline imitation models that cannot generate new decision logic on their own. At the same time, replacement is shaped by the causal interaction of prefetching, thrashing, spatial locality, and access-type behavior, producing an enormous design space that is difficult to traverse manually. Prior approaches typically rely on heuristics, parameter tuning, or imitation of an offline optimal policy, capturing correlations rather than synthesizing new mechanisms. As a result, their performance gains often plateau and they overfit under dynamic workload conditions. CACHEFORGE is the first framework to evolve cache-replacement policies end-to-end by embedding a large language model inside a governed hardware-aware loop. In each iteration, the LLM proposes new C++ replacement logic, the policy is evaluated under a trace-base

---

### [6] Large Language Model Orchestration under Heterogeneous Preferences via Explicit Persona Inference

**链接**: https://arxiv.org/abs/2610.07587
**作者**: Shuqing Shi, Ziyan Wang, Milind Tambe, Yali Du
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM orchestration investigates how an orchestrator coordinates a group of autonomous agents to achieve common goals or maximize collective welfare. The agents are typically heterogeneous, each holding a private preference that it pursues but does not reveal. Inferring such hidden preferences from behavior has been a subject of long-standing research in game theory and multi-agent systems. The core challenge lies in maintaining a belief over every agent's preference and updating it from the agents' observed actions. Existing LLM orchestrators carry that belief as prompt text with no explicit update rule. This lets early errors persist and propagate rather than be corrected. We therefore propose \textbf{HARP} (Heterogeneous-preference Agent oRchestration via Preference inference), a novel framework that moves the belief out of the prompt. Specifically, HARP maintains one numeric posterior per agent over a finite set of candidate preferences and updates it in closed form by Bayes' rule. T

---

### [7] APEX: Active Protection at Execution Boundaries for LLM Agents

**链接**: https://arxiv.org/abs/2610.06966
**作者**: Xinran Zheng, Xin Fan Guo, Zhiqiang Hao, Fan Yang, Xingzhi Qian, Jiawei Du 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Indirect prompt injection (IPI) hides adversarial instructions in content that large language model (LLM) agents read at runtime. As agents compose heterogeneous capability units, including Tools, MCP servers, and Skills, the carriers of injection multiply, and defenses built to recognize attack patterns fall behind them. We instead shift defense from covering attack patterns to one stable point: whatever the carrier and however the injection propagates, harm materializes only at the \emph{execution boundary}, where the agent turns internal state into an external action or released output. Safety there turns on two conditions, both settled by the trusted task rather than by the run: whether the proposed effect is authorized, and whether the runtime information reaching it is endorsed by that task. We present APEX, an active defense that enforces both at this boundary from a single authorization contract compiled before untrusted execution: \emph{evidence-gated prevention} admits an eff

---

### [8] DecepEval: A Benchmark for Evaluating Deception in LLM Agents

**链接**: https://arxiv.org/abs/2610.07967
**作者**: Yiming Xu, Hongyue Yu, Beihua Yang, Zihan Chen, Yixin Liu, Zhen Peng 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents become increasingly autonomous, they may pursue task performance through deception, raising concerns about their reliable deployment. Existing evaluations show that LLM agents can deceive, but often examine isolated scenarios or narrowly defined conditions, limiting systematic understanding of when deception becomes more likely. To address this gap, we introduce DecepEval, a benchmark comprising 1,532 instances across 3 task families and 28 professional scenarios. Drawing on classical fraud theories, we propose the LLM Deception Diamond framework, which characterizes four external conditions that may induce deception: pressure, incentive, opportunity, and conflict. DecepEval pairs neutral and induced versions of each instance to measure condition-dependent changes in deception rates, while explicit task facts and observable agent behavior help distinguish deception from capability-related errors. Evaluations of nine frontier LLMs show that inducemen

---

### [9] Textual Environmental Context and Spatial Graphs for LLM-Based Regional SST Forecasting

**链接**: https://arxiv.org/abs/2610.07895
**作者**: Xiong Li, Xiaowei Zhou, Yanwei Yu, Qian Cui, and Junyu Dong
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sea surface temperature (SST) forecasting depends on local temporal persistence, regional spatial dependence, and environmental conditions that evolve with the forecast date. We study how these heterogeneous conditions can be presented to a large language model (LLM) for regional multi-step forecasting without serializing the full SST grid as text. We formulate forecasting as conditional numerical generation: historical SST and anomaly sequences, date-aligned environmental records, and static ocean knowledge form a textual context, while regional spatial state is supplied through continuous graph-derived prefixes. A static graph encodes persistent geographic--climatological relations, and a dynamic graph encodes recent SST correlations and localized tropical-cyclone influence. Two graph neural networks produce a target-node representation that is mapped by a spatial-prefix fusion and injected into the LLM input. On SST forecasting in the South China Sea, the complete configuration achi

---

### [10] MemCo: Memory-Centric Collaboration for Generalizing LLM Agents to Unseen Environments

**链接**: https://arxiv.org/abs/2610.07376
**作者**: Xinting Liao, Siyan Liu, Rabab K. Ward, Holger R. Roth, Xiaoxiao Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly operate in interactive environments, where they need to make sequential decisions through observation, action, and feedback. Although memory can help agents reuse experience, existing work designs memory in isolation, where collecting enough trajectories to populate it is expensive. Existing shared-memory approaches mitigate isolated experience by pooling episodic memories across tasks and environments. However, retrieving shared memory is challenged by the granularity, where retrieved memories can be either too specific to preserve current grounding or too coarse to support the next action. In this work, we propose MemCo, a memory-centric collaboration framework for generalizing LLM agents to unseen interactive environments. It maintains complementary local and global memory spaces, preserving environment-specific details locally while promoting transferable workflows induced from local trajectories to global memory. During online interac

---

### [11] AlignQuant: Tile-Aligned Mixed-Precision Quantization for Efficient LLM Generation

**链接**: https://arxiv.org/abs/2610.07457
**作者**: Hanzhi Zhang, Qiao Zhang, Qinglei Cao, Heng Fan, Yan Huang, Kewei Sha 等 (7 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-grained mixed-precision quantization promises efficient large language model inference, but local precision choices can conflict with regular GPU storage and computation units. This precision-boundary mismatch limits the translation of compression into practical acceleration. We introduce AlignQuant, a post-training quantization method that uses GPU-compatible two-dimensional weight tiles as the common unit of precision allocation, compact storage, and execution. This shared partition lets precision follow sensitivity within output channels. Joint prefill/decode calibration scores precision reductions using projection-output perturbations weighted by language-model loss gradients under quantized activations. Phase-normalized scores prioritize higher precision for tiles important to either phase under a model-wide weight-storage budget. Each tile stores one selected representation, while phase-specialized kernels reuse the packed model and expand lower-bit weights for INT8 computat

---

### [12] LLM -Based Support System for Research Topic

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DSNQSEgAAQBAJ%26oi%3Dfnd%26pg%3DPA487%26dq%3DLLM%26ots%3Dwo90xW9Lfi%26sig%3DCkUaZoQpyKwdpiR-A9wtigVmelI&hl=zh-CN&sa=X&d=18301473594074463552&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVE-GjRC1_H-KiQ7vPaiwibI&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=3&folt=kw-top
**作者**: S Shindo, S Nakamura, Y Miyadera¹ - Emerging Trends in Health Informatics, Medical …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> This study develops a support system that leverages a large language model ( LLM ) and a note-based research activity model to … an LLM , which may also suggest perspectives. Second, in research narrative construction, users develop a narrative

---

### [13] Does Steering Break Your Model? A Multi-Dimensional Evaluation Suite for LLM Steering Methods

**链接**: https://arxiv.org/abs/2610.07722
**作者**: Haotian Yang, Huikang Jiang, Yucheng Wu, Wen-Jie Jiang, Chenpeng Wang, Yibin Lou 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering provides a lightweight and flexible way to control large language model (LLM) behavior. However, effective steering requires more than inducing the intended behavior: it should also limit unintended changes and remain robust across inputs and training data. Existing evaluations cover these dimensions only in fragments. As a result, the trade-offs between efficacy and side effects have not been systematically characterized. We introduce SteerScope, a two-axis, multi-dimensional evaluation suite that jointly characterizes steering outcomes and method properties through 15 metrics. We score target efficacy and side effects on language quality, task capabilities, and safety and reliability, and further assess generalization and data dependence through steering-specific metrics for sample efficiency and sample sensitivity. Rather than comparing methods at a single operating point, we characterize the trade-offs between efficacy and side effects. Under matched models, tas

---

### [14] When the Commons Appropriates a Large Language Model: How WikiVault Reshaped Korean Wikipedia

**链接**: https://arxiv.org/abs/2610.07660
**作者**: Inhwa Song, Sohyeon Hwang, Ted Yoo, Manoel Horta Ribeiro
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have disrupted the balance between content production and quality assurance that sustains knowledge commons, leading many to prohibit or restrict their use. But what happens when a community instead appropriates an LLM-powered tool for its own needs? We investigate this question through WikiVault, an LLM-powered editing tool developed within the Korean Wikipedia community and used primarily for translation. Combining ten interviews, platform-scale analyses, and matched quasi-experimental comparisons, we examine how WikiVault reshaped knowledge production on Korean Wikipedia. We find the tool 1) drastically amplified the production capacity of a small group of experienced editors, producing longer and more widely viewed articles; 2) shifted work toward reviewing articles and importing content; 3) imported not only content but also editorial judgments from English Wikipedia. Our findings show how LLM adoption can rebalance the interdependent work that sustain

---

### [15] SpliTEE: Fast and Private LLM Inference by Coupling GPU-Assisted Trusted Execution Environments with Differential Privacy

**链接**: https://arxiv.org/abs/2609.15039
**作者**: Shashie Dilhara Batan Arachchige, Robin Carpentier, Hassan Jameel Asghar, Dali Kaafar
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] M3SunAgent: Monocular 3D Spatial Understanding Agent for Metric Depth Estimation and 3D Visual Grounding

**链接**: https://arxiv.org/abs/2610.07982
**作者**: Jinsong Zhang, Kejun Wu, Ming Zhu, Renjie Qiao, Chengtao Cai, Zhengguo Li
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Monocular metric depth estimation and 3D visual grounding represent the two complementary cornerstones of monocular 3D spatial understanding (M3Sun), from which the fundamental 3D spatial information required by M3Sun can be acquired. However, these complementary tasks are generally conducted by separate frameworks, which pose challenges of inflexible and unaligned spatial information access for embodied intelligence systems. In this paper, we propose a unified agent for monocular 3D spatial understanding (M3SunAgent) that leverages a large language model (LLM) as a task planner for spatial visual programming, which flexibly generate structured programs and coordinate tools. For instance-level metric depth estimation task, M3SunAgent invokes an object detector tool to locate the target, estimates depth at selected points with a depth estimation tool, and aggregates these predictions into an instance-level depth estimate. We also construct the M3Sun Instance (M3SI) dataset, a benchmark 

---

### [17] Will the Judge Flip? Predicting Position-Sensitive LLM Judgments from Residual Stream Activations

**链接**: https://arxiv.org/abs/2610.07115
**作者**: Hashmath Shaik, Gnaneswar Villuri, Alex Doboli
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The order in which candidate responses are presented can change an LLM judge's verdict. Detecting such a position flip ordinarily requires judging each pair in both orders, which doubles the number of judgments. We investigate whether residual stream activations recorded immediately before the initial verdict can predict a flip. We use nested grouped cross-validation to evaluate regularized linear probes on 534 JudgeBench pairs for three Qwen3 judges and Llama-3.1-8B. The linear probes achieve AUROCs of .621-.850 and outperform a combined baseline that uses verbalized confidence, verdict-label logits, response lengths, and the judge's initial choice by .062-.113 AUROC. Linear probes trained on JudgeBench and then frozen achieve AUROCs of .685-.853 on 1,802 MT-Bench comparisons without MT-Bench fitting or recalibration. These results show that pre-verdict activations support prediction of susceptibility to candidate order and outperform the non-activation predictors evaluated here.

---

### [18] Evaluating Escalation Signals for LLM Routing: Targets, Controls, and Five Ways to Fool Yourself

**链接**: https://arxiv.org/abs/2610.07354
**作者**: Ramin Pishehvar, Andrea Morandi, and Mahesh Viswanathan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deciding when to escalate a query from a small language model to a larger one requires a cheap signal that predicts, before the large model is called, whether escalating would help. Semantic entropy, originally developed to detect hallucinations, is a natural candidate: it measures how much a model's sampled answers disagree in meaning, and high disagreement often signals an unreliable answer. We test it across three benchmarks and two model families. On GSM8K, with a small/large pair about twelve times apart in size, semantic entropy reliably distinguishes the small model's mistakes (AUROC 0.871) and improves routed accuracy over random escalation by up to nine points at matched cost. An earlier strong-looking result on a synthetic benchmark proved misleading: a simple rule based only on question difficulty, with no model involved, matched semantic entropy almost exactly. This paper's main contribution is a set of checks that catch this before it is reported as real. We show that scor

---

### [19] More Value per Key: Asymmetric Sparse Attention for Faster LLM Decoding

**链接**: https://arxiv.org/abs/2610.04753
**作者**: Noam Elata, Itay Lamprecht, Mikey Shechter, Daniel Ohayon, Itay Hubara, Daniel Soudry
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Unbiased Reward Modeling from Implicit Feedback for LLM Alignment

**链接**: https://arxiv.org/abs/2603.23184
**作者**: Hao Wang, Haocheng Yang, Licheng Pan, Lei Shen, Xiaoxi Li, Yinuo Wang 等 (10 人)
**来源**: cs.CL cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Tree Navigation Without LLM Summaries: A Matched-Cost Study of Hierarchical Retrieval for Long-Document QA

**链接**: https://arxiv.org/abs/2610.06902
**作者**: Priyank Jayraj, Poonam Goyal, Navneet Goyal
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation grounds language models in external context, but for long documents flat top-$k$ retrieval can cluster on a single region and miss complementary evidence. RAPTOR-style summary trees address this by recursively clustering chunks and using a language model to summarize each cluster at indexing time, then ranking summary nodes alongside raw chunks at query time. We show the main benefit of summary trees in long-document QA can come from navigation rather than the generated summary content. We introduce NavTree, a leaves-only retriever that builds a deterministic balanced segment tree over chunks (zero language-model calls at indexing) and uses the tree purely as a navigation scaffold: a hybrid lexical-and-dense frontier walk, anchored on top retrieved leaves, descends from the root and emits only leaf chunks to the reader. On a matched-cost evaluation against flat retrievers and an extractive re-implementation of RAPTOR, NavTree is the strongest matched-cost

---

### [22] Topology-Consistent Task Planning over Cellular Workflow Complexes for LLM-based Agents

**链接**: https://arxiv.org/abs/2610.07004
**作者**: Sen Zhao, Jia Tang, Ruiqi Kong, Zuyu Zhang, Lifeng Shen, Ding Zou 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Task planning for LLM agents requires workflows that satisfy both user intent and complex sub-task dependencies. While existing planners work well for sequential or directed acyclic graph (DAG)-like structures, they struggle with workflow patterns such as verification-correction loops, convergent branch merging, and reusable intermediate states that arise naturally in real-world tool orchestration. We present TopoPlanner, a topology-consistent planning framework that lifts tool dependency graphs into cellular workflow complexes and uses them as topologyaware context for LLM tool planning. TopoPlanner retrieves a request-relevant closed subcomplex through cosheaf-consistent cellular retrieval, performs multidimensional structural reasoning over the retrieved topology, and interfaces the resulting cellular representation with the planner LLM for tool-sequence generation. Experiments on four tool-planning benchmarks with topology-guided loop, merge, and loop-merge workflows show consisten

---

### [23] PlaySuite: A Large-Scale Benchmark for Interactive Visual Intelligence

**链接**: https://arxiv.org/abs/2610.07127
**作者**: Dheeraj Varghese, Anna Vettoruzzo, Walter Simoncini, Michelle Lorena Acevedo Callejas, Mohammad Mahdi Derakhshani, Kristof Meding 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models yield strong performance on static perception and reasoning benchmarks, yet such evaluations largely overlook a central aspect of intelligence: acting competently in dynamic environments over extended time horizons. We introduce PlaySuite, a large-scale benchmark for evaluating interactive visual intelligence across more than 5K open-source video games curated from PyWeek and itch.io. Spanning diverse genres and engines, including Pygame, HTML5, Godot, and Unity, these independent games are largely out-of-distribution for current models, reducing the likelihood that success can be achieved by retrieving memorized walkthroughs or web-scale training artifacts. To enable scalable evaluation across heterogeneous titles, we develop a unified closed-loop interaction framework optimized for HPC clusters alongside a Video-LLM-as-a-judge protocol that maps observable gameplay milestones to standardized progress levels. We evaluate fourteen recent 

---

### [24] Structured but Silent: Probing Capability Requirements in LLM Hidden States

**链接**: https://arxiv.org/abs/2610.08018
**作者**: Kyojun Choo, Minsoo Song, Yunju Kang, Chanjun Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable tool use requires more than triggering a mechanism or matching a query to an API description. Before selecting a specific tool, an agent must first infer the capability requirements implied by the user query. In this paper, we investigate whether these query-side capability requirements are linearly decodable from LLM hidden representations prior to generation, and how this hidden-state accessibility compares with explicit verbal classification. We introduce TACIT, a framework that decomposes external requirements along three fundamental axes: Source, Transformation, and World Effect, defining eight structurally distinct capability classes. Using 1,600 balanced training queries from benchmarks, synthetic examples, and new domain scenarios, we train linear probes on pre-generation hidden states from four open-weight LLM families. Our empirical results demonstrate that fine-grained capability structures are linearly decodable with high accuracy across all models. Crucially, howe

---

### [25] ROMA: LLM System for Real-World Object-Centric Multi-Sensory Active Perception

**链接**: https://arxiv.org/abs/2610.06955
**作者**: Ruoxuan Feng, Yutong Chen, Ruihua Song, Huan Yang, Zhongyuan Wang, Guocai Yao 等 (7 人)
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans inherently understand the physical world through an active process. When sensory evidence is insufficient to infer physical properties, we naturally interact with the environment by deciding what information is missing, how to acquire it, and when sufficient evidence has been obtained. In stark contrast, existing multi-sensory robot systems mainly integrate sensory inputs rather than actively acquiring missing evidence through interactions. In this work, we introduce ROMA, an LLM-based system for Real-World Object-Centric Multi-Sensory Active Perception. ROMA integrates vision, audio, tactile, and force sensing into a reasoning-interaction-feedback loop. The model identifies missing evidence and determines the target objects, interactions, and modalities, while a physical interface executes the selected interactions and collects the multi-sensory feedback. To support this capability, we construct ROMI-2K, a large-scale real-world multi-sensory object interaction dataset covering

---

### [26] VETTA: Coordinating Turn- and Token-Level Credit Assignment for Multi-Turn LLM Agents

**链接**: https://arxiv.org/abs/2610.08402
**作者**: Jiaju Chen, Min Yang, Jinghua Piao, Xiaochong Lan, Xu Xia, Xiangnan He 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn LLM agents often receive sparse task feedback across several interactions, while generating each response token by token. This creates two related credit-assignment questions: which responses helped achieve the outcome, and which generation decisions mattered within each response? Existing methods typically focus on only one level: turn-level methods evaluate complete responses but do not distinguish the decisions within them; token-level methods can propagate feedback across turns but do not explicitly model credit for each response. These complementary limitations motivate learning credit at both levels and coordinating it in a single policy update. We introduce VETTA, a credit assignment method that jointly learns turn- and token-level values through separate heads on a shared lightweight critic. VETTA computes advantages along both temporal sequences and combines each turn advantage with a within-response-centered token residual for PPO updates. Furthermore, to reduce va

---

### [27] MRPilot: Supervising and Intervening LLM-Based Multi-Robot Teams through Mixed Reality

**链接**: https://arxiv.org/abs/2610.07477
**作者**: Xiaoran Yang, Xun Qian, Yang Zhan, Nathan Tran, Ziyi Liu, Qiao Jin
**来源**: cs.HC cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) let users direct heterogeneous multi-robot systems (MRS) through natural language, but make task interpretation, robot assignment, and coordination difficult to inspect and change. Based on a formative study with 12 non-expert users, we developed MRPilot, a mixed reality system organized around four stages of supervision and intervention. MRPilot represents robot-team plans and execution states as structured commitments shared across synchronized situated and overview views. Across four stages, it helps users resolve ambiguous references (Forming), review plans before execution (Reviewing), monitor distributed execution (Following), and make robot-level or team-level changes when problems arise (Repairing). In a within-subjects study with 20 participants in a virtual reality-simulated home, MRPilot reduced workload, increased situational awareness, transparency, trust, and perceived control compared with a conventional LLM-based conversational interface usi

---

### [28] Agent in a Bottle: Can LLM Agents Turn Their Capabilities Into Cheap, Scalable Artifacts?

**链接**: https://arxiv.org/abs/2610.08775
**作者**: Ankit Sonthalia, Haritz Puerto, Alexander Rubinstein, Martin Gubri, Seong Joon Oh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can solve many narrow tasks, but querying them separately for millions of related instances can be prohibitively expensive. Can LLM agents autonomously create cheaper solutions for such workloads? We call this ability "bottling": the ability to turn general capabilities into task-specific solutions that balance answer quality and amortised cost. We introduce BOTTLED, a benchmark in which agents receive an entire unlabelled workload and must complete it under fixed time, compute and LLM API budgets. Agents choose their own approach, such as training a small model or writing a reusable program. Across ten models and three tasks, we find that strong zero-shot task performance does not reliably translate into strong bottling capabilities. Models with similar zero-shot scores can differ substantially after bottling, and 48 of 60 bottling runs score below the lower bound of the 95% confidence interval of their model's zero-shot performance. Moreover, 31 of 60 run

---

### [29] Local Sparsity Enables Unsupervised LLM Safety Detection

**链接**: https://arxiv.org/abs/2609.20129
**作者**: Xin Chen, Gil Kur, Alexander Shevchenko, Andreas Krause
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] DySCo: Dynamic Sharding for Collaborative Edge-Cloud LLM Inference with Depth-Synchronized Batching

**链接**: https://arxiv.org/abs/2610.08268
**作者**: Jingpo Xu, Paul Joe Maliakel, Ivona Brandic, Shashikant Ilager
**来源**: cs.DC cs.AI cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pervasive intelligent applications are increasingly deployed on mobile and Internet of Things (IoT) edge devices. Consequently, Large Language Models (LLMs) are increasingly used to support these applications. Yet, due to their high resource demands, LLMs are mostly deployed in the cloud. Layer-wise edge-cloud inference lets resource-constrained edge devices contribute computation to LLMs they cannot host in full. However, heterogeneous split points introduce two coupled inefficiencies. First, edge execution and communication create idle gaps between cloud invocations. Second, requests arriving at different model depths cannot be conventionally batched. We present DySCo, a collaborative runtime that keeps KV caches local and introduces dyForward, a model-aware layer-range executor that runs configurable contiguous layer ranges from resident model shards without reloading weights. For multi-edge serving settings, we introduce depth-synchronized batching (DSB), which advances heterogeneo

---

### [31] Principles that Guide, Actions that Inform: Agent Evolution via Knowledge Abstraction

**链接**: https://arxiv.org/abs/2610.06964
**作者**: Bowen Ye, Yongchao Xu, Junkai Ma, Xiang Yin and Wenzhao Li
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated strong capabilities in interactive environments, yet their ability to continually evolve from experience remains limited. Although fine-tuning enables adaptation, its dependence on parameter access and high computational costs restrict its flexibility, especially for large-scale and closed-source LLMs. External memory offers an alternative by allowing agents to accumulate experience without modifying model parameters. However, existing methods mainly focus on experience representation and organization, while the acquired knowledge remains tightly coupled with specific tasks and contexts, limiting generalization. A key challenge is how to transform concrete interactions into abstract and reusable knowledge that guides future decisions beyond individual experiences. To address this challenge, we propose SAGA (\underline{\textbf{S}}elf-evolving \underline{\textbf{A}}gents through Experience-\underline{\textbf{G}}rounded \underline{\textb

---

### [32] To Call or Not to Call: Diagnosing Intrinsic Over-Calling Bias in LLM Agents

**链接**: https://arxiv.org/abs/2605.18882
**作者**: Wei Shi, Ziheng Peng, Sihang Li, Xiting Wang, Xiang Wang, Mengnan Du 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] A Hybrid BERT- LLM Approach for Regulation Graph Generation and Visualization from Fire Safety

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DrrQTEgAAQBAJ%26oi%3Dfnd%26pg%3DPA1%26dq%3DLLM%26ots%3D3tE0TXyQfw%26sig%3DGd7hpk46BJEk6y2pXB3FcYFpVjo&hl=zh-CN&sa=X&d=11635016586070587456&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVEQW4BVgu0FQubJR22sI8pu&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=9&folt=kw-top
**作者**: T Jorge, D Ribeiro, J Reis, R Gavina - Proceedings of the Digital Building Permit …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> the LLM -based Python functions, resulting in a much more accurate extraction of information. Figure 2, b shows the metadata obtained from the analysis carried out by the LLM -… Additionally, the LLM -based Python functions automatically generate

---

### [34] Trust-Gated Capability Control: Breaking the Trust-Vulnerability Paradox in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2610.07000
**作者**: Mehedi Hasan Nipu, Chinmoy Mitra, Tarannum Ahmed Nowshin, Israt Moyeen Noumi
**来源**: cs.GT cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Layered trust models for multi-agent LLM systems remain largely conceptual: they name which dimensions of trust matter but not how layers combine, how their importance is set at runtime, or how trust should govern agent actions. This gap matters because higher inter-agent trust raises task success while also enlarging exposure to exploitation, a tension formalized as the Trust-Vulnerability Paradox. We make a five-layer trust stack operational through three contributions. First, a cross-layer synergy operator propagates prerequisite-layer deficits into de- pendent layers, feeding a generalized-mean composite trust that recovers the weakest-link rule as a limiting case, with provable bounds. Second, per-layer importance weights are grounded in observed failures via a no-regret online estimator that tracks which layer is currently most responsible for harm. Third, Trust- Gated Capability Control issues short-lived, revocable capability grants only when composite trust and the relevant pr

---

### [35] JudgeProfile: Understanding and Steering Subjectivity in LLM Judges

**链接**: https://arxiv.org/abs/2609.36705
**作者**: Qi Cao, Kangning Liu, Xuan Kan, Shunwen Tan, Yang Pei, Dake Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] SpeedrunBench: Challenging LLM Agents with Video Game Speedrunning

**链接**: https://arxiv.org/abs/2610.08076
**作者**: Yoshinari Fujinuma, Keisuke Kamahori, Ryuto Koike, Abdelrahman Madkour, Varun Prashant Gangal, Monty Bichouna 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier LLM agents have been shown to be capable of solving increasingly complex tasks for which humans have measurable solutions. This begs the pertinent question of whether LLM agents can go beyond what humans have already solved. The ability to develop sophisticated strategies to tackle consequential problems becomes paramount as well-trodden, human-developed solutions become insufficient for problems for which we lack context or enough training data. We study agents' capability of such strategy formation through the communal practice of video game speedrunning. In speedrunning, practitioners compete to find the fastest way to complete a video game under certain conditions, and in so doing uncovering interesting unorthodox play styles that require a thorough understanding and mastery of the underlying game mechanics. We introduce SPEEDRUNBENCH, a benchmark that evaluates frontier LLM agents across 9 different games. To perform well in this benchmark, agents must repeatedly improve 

---

### [37] Beyond Refusal Patterns: Safe-Role Internalization for Robust and Generalizable LLM Safety Alignment

**链接**: https://arxiv.org/abs/2610.07023
**作者**: Jinghao Pang, Jitai Hao, Qiang Huang, Zhaochun Ren, Jun Yu
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have achieved remarkable capabilities but remain vulnerable to jailbreak attacks that elicit harmful or unsafe outputs. Existing safety alignment approaches, including Supervised Fine-Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF), often require substantial attack-specific supervision and computational resources, while remaining susceptible to shallow safety alignment and over-refusal. To address these challenges, we introduce SSRFT(Supervised Safe-Role Fine-Tuning), the first framework that reformulates safety alignment as the internalization of a predefined safe role. SSRFT constructs a Safe-Role Question-Answer (SRQA) dataset from psychometric questions, limited jailbreak prompts, and a safe-role description. Role-consistent responses are synthesized, validated, and expanded into diverse scenarios, enabling models to internalize safety-oriented values and principles rather than explicit refusal patterns. Experiments across multiple Ba

---

### [38] Activation Denoising: A Robustness View on Parallel vs Sequential LLM Quantization

**链接**: https://arxiv.org/abs/2610.07522
**作者**: Yan Scholten, Rachel Lawrence, James Hensman, Stephan G\"unnemann, Alicia Curth, Riccardo Grazzi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization is a powerful tool for compressing large language models. The most scalable methods quantize every layer in parallel, but quantization errors then compound through the residual stream, as no layer corrects for the errors of the layers before it. Sequential quantization accounts for this error compounding by re-calibrating each layer on the already-quantized outputs of its predecessors, yielding stronger results but at the cost of a serial schedule that becomes a bottleneck at scale. As a solution, we propose parallel quantization with activation denoising, which recovers much of the sequential benefit while keeping quantization fully parallel. Rather than re-calibrating layer-by-layer, we take a robustness perspective and model the upstream error as noise, regularizing to be robust to it through a preprocessing step followed by metric-weighted rounding. Applied at every layer, this regularization forms a depth-compounding smoothness penalty that dampens how s

---

### [39] Can LLM-assisted regularization increase forecast accuracy for migration flows in low data regimes?

**链接**: https://arxiv.org/abs/2610.07208
**作者**: Nathaniel T. Hindman, Fabricio Murai
**来源**: cs.LG cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting migration flows remains a significant challenge for traditional gravity-based forecasting models, which primarily rely on structured socio-economic indicators such as economic disparity, political stability, and geographic distance. This work investigates whether Large Language Models (LLMs) can improve migration forecasting by extracting contextual migration-related signals from news articles and incorporating them into a weighted Lasso forecasting framework through feature-specific regularization penalties. The proposed framework uses hierarchical LLM inference pipelines to classify migration-related push--pull signals from news data and evaluates the resulting forecasting performance across multiple migration corridors between November 2021 and November 2022, including Mexico--United States, Ukraine--Poland, and Syria--Turkey. Experimental results showed mixed performance across migration corridors and modeling strategies, and no single regularization approach consistentl

---

### [40] FluidPD: In-Place Elasticity for SLO-Aware Prefill-Decode Disaggregated LLM Serving

**链接**: https://arxiv.org/abs/2610.06917
**作者**: Kartik Ramesh, Kaidi Fu, Zihan Zheng, Jiahuan Yu, Fabio Oliveira, Carlos Costa 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prefill-decode disaggregation is becoming a common architecture for LLM serving because it separates two phases with distinct execution patterns and SLO objectives. Existing systems typically combine a fixed prefill/decode worker ratio with request routing across workers. However, real-world workloads exhibit both short bursts and sustained shifts in the prefill-to-decode demand ratio. As a result, a configuration that is well provisioned at one time may quickly become mismatched, causing latency SLO violations even when idle capacity exists elsewhere. Existing autoscaling mechanisms can add capacity, but they react slowly, require spare GPUs, and do not directly address short-timescale phase imbalance. We present FluidPD, a P/D-disaggregated serving system that provides SLO-aware in-place elasticity. FluidPD introduces two complementary mechanisms. FluidToken handles transient imbalance by offloading a bounded portion of prefill computation to decode workers when decode-side slack is 

---

### [41] Disentangling Models from Personas in Heterogeneous LLM Simulations

**链接**: https://arxiv.org/abs/2610.07535
**作者**: Dani Roytburg, Daphne Ippolito
**来源**: cs.MA cs.AI cs.CL cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent simulations with large language models (LLMs) often operate networks of agents with a single base model. This overlooks the inter-model effects which may dominate engagement dynamics in real-world deployments. To show this, we simulate a heterogeneous social network powered by several different base models and show that the amount of engagement an agent receives depends more on its base model than on its assigned persona. The attraction or repulsion effects of a base model strengthen dramatically when more models are added in the mix, suggesting that networks dynamics may converge to base model effects at scale. To help explain this effect, we conduct a series of content-mediating analyses, showing the predictability of base models across contexts as well as the relationship between a model's lexical patterns and an engagement-maximizing style. In light of recent developments in mass multi-agent interaction, this work underscores the relevance of heterogeneous compositions 

---

### [42] LeanPlan: Optimal Planning with LLM-Generated Heuristics and Admissibility Proofs

**链接**: https://arxiv.org/abs/2610.08246
**作者**: Andr\'{e} G. Pereira, Augusto B. Corr\^ea, Felipe Meneguzzi, Jendrik Seipp
**来源**: cs.AI cs.LG cs.SC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier large language models (LLMs) can generate heuristic functions that guide search to achieve state-of-the-art performance in satisficing planning, where any plan is acceptable. However, these heuristics are not guaranteed to be admissible and can lead to suboptimal plans. We introduce LeanPlan, the first planning system that finds optimal plans with LLM-generated heuristics whose admissibility is machine-checked. Given a domain description and training tasks, an agentic loop uses planner feedback to iteratively improve a reusable domain-specific heuristic, its admissibility proof and the required domain assumptions. LeanPlan implements the heuristic, its proof and an efficient planner with machine-checked grounding and search in Lean 4. We evaluate LeanPlan on ten domains from the International Planning Competition and three new domains, using test tasks with up to 57 times as many objects as the training tasks. With GPT-5.6 Sol in the agentic loop, we successfully generate heur

---

### [43] ReflexAI: Optimizing LLM Feedback with Prompt Engineering to Enhance

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DmLQTEgAAQBAJ%26oi%3Dfnd%26pg%3DPA292%26dq%3DLLM%26ots%3D71AU5dOjx4%26sig%3DDML6EsoYQkby5_xQro3-iH1Vbbw&hl=zh-CN&sa=X&d=552776194102496383&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVF98YbKkNZwAK1jFANzRKy8&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=6&folt=kw-top
**作者**: A Bhojan, TL Xin - … : 17th International Conference, CSEDU 2025, Porto …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> However, LLM -… of LLM generated feedback. Moreover, students who received feedback based on enhanced prompts demonstrated greater improvements in reflective writing quality and learning outcomes. These results highlight the potential

---

### [44] Djinnlang: Higher-Level Programming by Exhaustive Specification and LLM Implementation

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/forum%3Fid%3DYlUbKo0OGQ&hl=zh-CN&sa=X&d=17150316833267379677&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVEmxRmnzHr2PxCcNEn5b1kW&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=8&folt=kw-top
**作者**: S Henniger, S Chong, N Amin - NeurIPS 2026 Workshop on AI for Verifiable Coding
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> its implementation satisfies the specification, the LLM must also prove that any other … LLM that fills in implementations and proofs, all checked by the Dafny verifier. We evaluate our language and implementation on multiple examples and we show

---

### [45] Reasoning as Pattern Matching: Shared Mechanisms in Human and LLM Everyday Reasoning

**链接**: https://arxiv.org/abs/2606.13607
**作者**: Zach Studdiford and Gary Lupyan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Stabilizing Off-Policy Training for Long-Horizon LLM Agent via Turn-Level Importance Sampling and Clipping-Triggered Normalization

**链接**: https://arxiv.org/abs/2511.20718
**作者**: Chenliang Li, Adel Elmahdy, Alex Boyd, Zhongruo Wang, Siliang Zeng, Alfredo Garcia 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] ReLoop: Structured Modeling and Behavioral Verification for Reliable LLM-Based Optimization

**链接**: https://arxiv.org/abs/2602.15983
**作者**: Junbo Jacob Lian, Yujun Sun, Huiling Chen, Chaoyu Zhang, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.SE cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Polar: LLM-Powered Synthesis of Real-World Cyber Evidence for Prioritization and Mitigation

**链接**: https://arxiv.org/abs/2610.07298
**作者**: Luoxi Tang, Yuqiao Meng, Ankita Patra, Weicheng Ma, Muchao Ye, Zhaohan Xi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cyber threat analysis increasingly depends on evidence distributed across vendor advisories, vulnerability databases, and threat intelligence sources. Turning these fragmented observations into timely decisions requires models to connect technical severity with evolving exploitation evidence and available defensive actions. We present POLAR, an LLM-powered framework for synthesizing real-world cyber evidence into threat-centric assessments for prioritization and mitigation. POLAR first disentangles overlapping incidents and grounds each threat in source-linked evidence. For prioritization, it infers severity metrics from cyber evidence and combines the resulting assessment with temporally ordered exploitation signals to estimate near-term exploitation likelihood. For mitigation, it links the synthesized threat data to authoritative remediation knowledge and organizes applicable actions according to threat urgency and operational constraints. We evaluate POLAR on real-world vulnerabilit

---

### [49] Enhancing High-order Interaction Awareness in LLM-based Recommender Model

**链接**: https://arxiv.org/abs/2409.19979
**作者**: Xinfeng Wang, Jin Cui, Fumiyo Fukumoto and Yoshimi Suzuki
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] POLAR: Ontology-Guided Risk Prevention for Tool-Calling LLM Agents

**链接**: https://arxiv.org/abs/2610.08082
**作者**: Yunju Kang, Seonghyeon Cho, Irene Li, Yeo-Chan Yoon, Chanjun Park
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM tool-use agents operate in dynamic environments where many actions carry operational risk. However, most safety mechanisms react only after errors manifest. Existing pre-emptive approaches either fine-tune the agent on chain-of-thought deliberation or compile natural-language guardrails into runtime checks, but they do so without exposing a structural, auditable verdict. We propose POLAR, a guardrail framework for small tool-calling agents that assesses reversibility through a structured two-layer ontology. POLAR assigns each action a graded reversibility score by deriving a candidate inverse sequence; calls failing a threshold are pruned before execution. Evaluated on $\tau^2$-bench across six agent models, POLAR improves mean task reward by 0.11 to 0.18 points on airline for four of six agents, but only eight of eighteen model--domain cells improve overall; retail and stronger agents often regress. POLAR provides an auditable structural check and characterizes its task-utility tr

---

### [51] Penalty-Framed No-Valid-Option MCQA: Analyzing LLM Abstention under Invalid Choices

**链接**: https://arxiv.org/abs/2610.08153
**作者**: Jinhyeok Kim, Hye-Young Jung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiple-choice question answering (MCQA) is commonly used to evaluate large language models under the assumption that one of the provided options is correct, typically using answer-selection accuracy. However, in real deployments, users or retrieval systems may provide invalid option sets in which none of the listed choices is correct, and selecting one of them may incur downstream cost. We study this setting as penalty-framed no-valid-option MCQA. Using the mathematics subset of MMLU-Pro, we remove the labeled correct option, allow models to either choose a remaining option or output ABSTAIN, and penalize invalid forced-choice responses. We further introduce correct-conditioned analysis, evaluating abstention only on instances that the model originally answered correctly. Experiments show that high MCQA accuracy does not fully guarantee abstention reliability: even under explicit no-valid-option-aware instructions and penalty-based scoring, models still produce invalid forced-choice 

---

### [52] Evaluating Large Language Model Raters for German Open-Response Clinical Questions: A Physician-Annotated Benchmark Study of Agreement, Evaluator Bias, and Abstention

**链接**: https://arxiv.org/abs/2607.01103
**作者**: William Philipp, Finn Fassbender, Daniel Fister, Thorsten Langer, Martje G. Pauly, Rebecca Herzog 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Probing an Embodied LLM : When Higher Observation Fidelity Hurts Problem

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DRZgUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA310%26dq%3DLLM%26ots%3DC0ouGVvqcw%26sig%3D4Uz35V-fXjhY_KsauIuuxRsSkFo&hl=zh-CN&sa=X&d=12285814540715556845&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVEswjBeE7bN2hRlPKSt113q&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=7&folt=kw-top
**作者**: O Zenkri, O Brock - From Animals to Animats 18: 18th International …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large Language Models (LLMs) are increasingly proposed as cognitive components for robotic systems, yet their opaque decision processes make it difficult to explain success or failure in closed-loop embodied tasks. Following an empirical

---

### [54] BitNest: Bit-Nested Speculative Decoding for Memory-Efficient LLM Inference Acceleration

**链接**: https://arxiv.org/abs/2610.02800
**作者**: Chence Yang, Ningxi Cheng, Arash Akbari, Qitao Tan, Qingchan Zhu, Ci Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Learning from Failures: A Failure-Driven Prompt Refinement for LLM-Based Vulnerability Analysis

**链接**: https://arxiv.org/abs/2610.08405
**作者**: Mandana Ghadamian, David Mohaisen
**来源**: cs.SE cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models have emerged as promising tools for software vulnerability analysis, but their effectiveness depends heavily on prompt design. Existing research primarily compares prompting strategies using aggregate performance metrics, providing limited insight into why models fail or how prompts can be improved systematically. We propose Failure-Driven Prompt Refinement (FDPR), a methodology that analyzes recurring model failures to guide evidence-based prompt refinement. Using the Damn Vulnerable Java Application (DVJA), we identify recurring failure modes, including false positives, false negatives, unsupported reasoning, and CWE misclassification, and translate them into targeted prompt refinements. We then evaluate the resulting prompt on the Juliet Test Suite and perform cross-model validation to assess generalizability. The results show that failure-driven refinement improves the reliability of LLM-based vulnerability analysis while yielding reusable prompt design princi

---

### [56] DHCG: Dynamic Construction of Hierarchical Collaboration Graphs for LLM-Based Multi-Agent Reasoning

**链接**: https://arxiv.org/abs/2610.07835
**作者**: Jie Ren, Jiakang Yuan, Chenyu Huang, Hezeer Ma, Jiayuan Fan, Tao Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) have demonstrated strong capabilities in solving complex problems across diverse domains. Recently, the dynamic orchestration of agent systems has become an important research direction. However, existing methods suffer from limited composition, misaligned dependencies, and inflexible scale, restricting their ability to adapt to reasoning requirements during execution. To address these limitations, we reframe MAS design as a partially observable Markov decision process, in which both the composition and scale of the MAS are dynamically determined. We propose DHCG, a novel framework that coordinates three modules (Planner, Worker, and Generator) to progressively construct a dynamic hierarchical collaboration graph from scratch based on the query and evolving execution feedback. At each step, guided by feedback, the Planner generates a set of distinct and complementary roles tailored to the current reasoning needs and selectively routes relevant inform

---

### [57] Confidence Reasoning Graphs: Structured Confidence Estimation for LLM Agents

**链接**: https://arxiv.org/abs/2610.07948
**作者**: Brendan King, Farima Fatahi Bayat, Jean-Flavien Bussotti, Pouya Pezeshkpour, Estevam Hruschka
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When using an LLM agent in a consequential domain, making an informed decision about whether to trust its output or intervene requires calibrated confidence in the agent's success. Confidence estimation for agents is difficult because evidence about success is distributed across heterogeneous, interdependent steps of an agent's trajectory. Practical agentic deployments introduce further challenges: frontier LLMs often provide limited access to internal signals, agent roll-outs are costly, and training data may be unavailable or quickly become outdated. To address these challenges, we introduce Confidence Reasoning Graphs (CRGs), an inference-time framework that estimates the probability an agent accomplished its task from a single trajectory, without privileged model access or training data. Rather than compressing an execution into a single holistic judgment, a CRG begins with the claim that the agent accomplished its task, decomposes it into contextualized sub-claims grounded in traj

---

### [58] Persistent Memory in Multi-Agent LLM Inference: What It Costs, What It Buys, and When You Can Tell

**链接**: https://arxiv.org/abs/2610.07782
**作者**: Hochan Son, Kyungdoe Han, Jaehan Koh, Xiaowu Dai, Wenlu Xu, Guang Cheng
**来源**: cs.AI cs.CL cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decomposing long-context inference across cooperating agents bounds the active KV cache per call rather than total evidence, which matters when KV-cache memory binds. Many such systems add a persistent tier storing and recalling reasoning traces, usually validated by an ablation reporting an accuracy gain. We measure both on one three-tier agent architecture. Decomposition delivers: peak KV working set of 14.3 MiB per query against 35.5 and 35.3 MiB for single-pass and retrieval-augmented baselines. The persistent tier does not: across eight controlled dataset pairs at n=100 per arm it costs +0.368 MiB [+0.167, +0.590] of peak cache and produces no detectable accuracy change (+0.015, 95% CI [-0.011, +0.046]). We argue the null is structural: single-question benchmarks supply each item with its own evidence and score it independently, and correctness requires resetting stored traces between conditions, so recall has nothing informative to retrieve. Reaching it took four measurement corr

---

### [59] Learn2Play Bench: How Well Do LLM Agents Learn from Experience in Unfamiliar Environments?

**链接**: https://arxiv.org/abs/2610.08215
**作者**: Yibo Li, Jinhang Qiu, Zhi Zheng, Qianyun Guo, Jiaying Wu, Shuo Ji 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning from experience is essential for LLM agents to adapt to unfamiliar and dynmaic environments. Evaluating this ability is therefore important for understanding how effectively agents acquire and use new knowledge. Existing benchmarks have sought to evaluate this ability, but they primarily evaluate tasks whose rules are provided in the instructions or already familiar to pretrained models, making it difficult to distinguish learning from interactions from reasoning with existing knowledge. To address this, we introduce Learn2Play Bench, a benchmark of newly designed text-based games, whose rules are novel or counterintuitive, requiring agents to acquire knowledge through interaction rather than rely solely on pretrained knowledge. These games provide reproducible feedback and automatic scoring, enabling controlled evaluation of learning across repeated attempts. We also vary game instances to test whether agents can apply what they have learned to new situations. Therefore, we e

---

### [60] Understanding Errors in LLM-Based Question Answering over Imperfect Tables

**链接**: https://arxiv.org/abs/2610.04687
**作者**: Baowen Zhang, Wei Fan, Ruman Wang, Hangting Ye
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] OSFP4: Joint Optimization of Diagonal Smoothing and Block Scales for NVFP4 Quantization

**链接**: https://arxiv.org/abs/2610.08231
**作者**: Neriah Ben David, Ori Meir and Or Ordentlich
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> NVFP4 is an attractive datatype for large language model (LLM) inference, offering compact storage and native tensor-core acceleration. However, preserving accuracy using NVFP4 requires careful quantization. In this work we develop a novel quantization scheme called Optimized Smoothing and Scaling for NVFP4 (OSFP4). For each linear projection it uses a diagonal smoothing matrix whose entries are optimized to minimize the squared matrix-product quantization error under NVFP4, taking into account the rounding procedure that is used (either round-to-nearest, or GPTQ-style successive interference cancellation). This requires performing joint optimization on the smoothing entries as well as the block scales, which is facilitated by analyzing a multiplicative-dither FP4 quantizer instead of the fixed deterministic one. Experiments show that OSFP4 achieves the highest average accuracy among the evaluated competitors in the corresponding quantization settings, while retaining approximately 94-

---

### [62] zkLLMPoT: Efficient Zero Knowledge Proof of Training for Large Language Models

**链接**: https://arxiv.org/abs/2610.08258
**作者**: Junkai Liang, Zhanpeng Guo, Pengfei Wu, Qingni Shen, Jiaheng Zhang, Zhonghai Wu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Auditing the claimed outcomes of large language model (LLM) training is challenging when model weights and training data are private, while cryptographically proving the full training process is prohibitively expensive at Transformer scale. We present zkLLMPoT, a zero-knowledge framework that certifies auditor-defined properties of a trained checkpoint through forward evaluation rather than verification of its optimization trajectory. zkLLMPoT includes 2 phases: 1) The trainer fixes the architecture and the model weights are committed. Then the auditor selects challenge sequences, preventing the trainer from modifying the checkpoint in response to the audit data. 2) Then the trainer proves the objective value attained by the committed model on those sequences. This formulation makes the certification cost independent of the number of training iterations, without revealing model weights or requiring access to private training data. We build on sumcheck- and lookup-based arguments to cer

---

### [63] Agreement Is Not Validity: Cross-Model LLM Consensus in Diagnosing Student Failure Modes in K-12 Math Tutoring Dialogue

**链接**: https://arxiv.org/abs/2610.08703
**作者**: Clayton Cohn, Joyce Fonteles, Kirk Vanacore, Gianni Mazza, Candida Crawford, Tom Hooper 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In K-12 mathematics tutoring, student-tutor dialogue provides rich evidence of learners' problem-solving processes and sources of difficulty. Learning analytics research increasingly relies on large language models (LLMs) to extract such information from dialogue for a variety of downstream tasks, including knowledge tracing, behavioral modeling, and diagnosis of student reasoning errors. However, the validity of these model-generated interpretations remains insufficiently understood. In this exploratory study, we examine the validity of LLM classifications of five student failure modes in mathematics tutoring dialogue using an operational diagnostic codebook: uncertainty, misattribution, operator selection, conceptual gap, and procedural slip. Across models, human-LLM agreement was moderate (kappa = .524-.597), while cross-model agreement was substantially higher (kappa = .755-.781; alpha = .769). These findings show that cross-model agreement can create a misleading appearance of cor

---

### [64] Calibration Is Not Control: Intervention Value for LLM-Agent Oversight

**链接**: https://arxiv.org/abs/2606.21399
**作者**: Chubin Zhang, Zhenglin Wan, Xingrui Yu, Jingxuan Wu, Qi Wen, Pengfei Zhou 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Structure, Not Belief: Correlated Thompson Sampling from LLM-Derived Covariance in Combinatorial Semi-Bandits

**链接**: https://arxiv.org/abs/2610.07470
**作者**: Vikram Kakaria, Anish Kataria, Anany Kotawala
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Combinatorial Thompson sampling (CTS) draws independent posterior samples for every arm, so its exploration dynamics ignore any relation among arms. We study a minimal change to those dynamics: an LLM is queried once for a partition of the arms, the partition becomes a positive-definite correlation matrix $\Sigma$ through an RBF kernel on cluster ranks, and the per-round posterior sample is drawn with covariance $\Sigma$ while the Beta posteriors are updated from real rewards only, so the LLM shapes how the sampler moves, not what it believes. We give a self-contained Bayesian regret bound for the idealized Gaussian sampler whose information gain splits into a $K\log T$ term from the $K$-cluster structure and a ridge term that grows to $d\log T$: the $\sqrt{d/K}$ improvement over independent sampling is a finite-horizon transient, exact only as the within-cluster correlation tends to one. The correlated sampler reduces regret by 19% over CTS on 16 synthetic Bernoulli families at $T=2{,

---

### [66] JudgeMoE: Distributional Aggregation for LLM-as-a-Judge

**链接**: https://arxiv.org/abs/2610.07109
**作者**: Yiqi Liu, Joseph James, Yang Wang, Kun Zhao, Chenghao Xiao, Chenghua Lin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM judge scores an output, its score distribution retains uncertainty and disagreement information that is lost after scalar compression. We introduce JudgeMoE, a lightweight aggregator that assigns example-specific weights to cached judge score distributions and fuses them before computing a final score. A protocol study shows that score-range choice is unstable across judge--dataset settings and that soft scoring usually outperforms hard decoding. On the original 10-cell benchmark, JudgeMoE improves mean Spearman over uniform log pooling by $+0.079$. Applying the same configuration to six additional cells yields a $+0.0393$ mean gain over the strongest local single judge across 16 cells, with positive differences in 12/16 cells and a one-sided Wilcoxon signed-rank $p=0.0091$. Validation-based analyses further show that the preferred aggregation method depends on the task and judge pool.

---

### [67] Language Carries the Expert's Impression: Instrument-Anchored LLM Judges Transfer Counseling-Quality Assessment and Beat In-Domain Training

**链接**: https://arxiv.org/abs/2610.08055
**作者**: Tobias Hallmen, Elisabeth Andr\'e
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic assessment of communication quality in dyadic counseling conversations is bottlenecked by data: expert-rated corpora are small and expensive to grow. We study cross-domain transfer of expert overall-impression prediction across three German corpora of simulated counseling (two general-practice medical, one school-related parent-teacher; $n=195$ expert-rated sessions, one corpus after scale equating). Training on the other domains beats training in-domain: leave-one-domain-out transfer reaches nested Spearman $\rho = 0.54$ against $\le 0.48$ within the target domain, a paired session-level gap of $+0.15$ that holds at $+0.12$ when the training-set sizes are matched, so it is not simply data volume. The decisive features are session-level construct scores from small open-weight LLMs reading the two-speaker transcript, with the constructs largely derived from the experts' rating instruments: the instrument-derived battery lifts a single judge from $0.32$ to $0.41$ over generic d

---

### [68] Reasoning Externalization for Faithful Large Language Model Narratives of Stock Return Predictions

**链接**: https://arxiv.org/abs/2609.38869
**作者**: Sujung Kim, Seung Hwan Cho, Sangjin Park, and Young-Min Kim
**来源**: cs.AI cs.CE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Voluntary Collusion with Secret Tools in Competing LLM Agents

**链接**: https://arxiv.org/abs/2605.27593
**作者**: Xijie Zeng, Frank Rudzicz
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] Token-Efficient Multi-Agent Collaboration via System One-Guided Computational Division of Labor

**链接**: https://arxiv.org/abs/2610.08155
**作者**: Zihan Zhou, Xinzhe Hu, Hanxu Yang, Liangjian Wen, Zhao Kang
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) have become a promising paradigm for complex information-seeking and reasoning tasks by enabling collaborative problem solving among specialized agents. However, existing MAS frameworks tightly couple task reasoning with coordination operations, including task selection, role assignment, message routing, and context management. As interactions grow, using powerful LLMs for these bounded control decisions introduces substantial token overhead and latency, limiting the scalability of agentic Web services. In this paper, we investigate whether coordination can be decoupled from expensive reasoning without compromising collaborative performance. We propose S1-MAS, a token-efficient multi-agent framework based on System One-guided computational division of labor. S1-MAS assigns bounded coordination decisions to lightweight System One models while reserving open-ended reasoning for capable LLM workers. Specifically, a lightweight con

---

### [71] Cite What You Explore: Budget-Aware LLM Reasoning over Medical KGs with Verifiable Evidence

**链接**: https://arxiv.org/abs/2610.07739
**作者**: Chen Chen, Dongjie Wang, Mei Liu, Zijun Yao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-discharge risk prediction from electronic health records (EHRs) is difficult because many dependencies that link discharge-time observations to downstream complications, such as comorbidity cascades and drug-disease interactions, are absent from the record. External medical knowledge graphs (KGs) can supply these missing dependencies, but tracing them demands three properties: KG exploration must remain cost-bounded, retrieved evidence must be differentiated by source quality, and the resulting rationale must be citable for retrospective review. Large language models (LLMs) can plan and verify over structured evidence, making them natural candidates for KG reasoning, but existing LLM-based methods do not satisfy these three properties jointly. In this paper, we propose BAR, a Budget-Aware LLM Reasoning framework over medical KGs with three contributions. First, BAR refines the raw KG into disease-specific evidence graphs whose edges carry support scores and provenance records, tur

---

### [72] Strategic Evaluation of Planning Strategies for LLM Agents in Cyber-Physical Systems

**链接**: https://arxiv.org/abs/2608.04265
**作者**: J. de Curt\`o and I. de Zarz\`a
**来源**: cs.MA cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Categorizing Mathematical Concepts with LLM Voting Ensembles

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DcLQTEgAAQBAJ%26oi%3Dfnd%26pg%3DPA38%26dq%3DLLM%26ots%3DFUtpbLWpys%26sig%3DTyWJlsnDEiD617My0xNyzkpIctM&hl=zh-CN&sa=X&d=14471086776946673305&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVGbgtiFnuLzVQGEM5Vb14Yl&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=5&folt=kw-top
**作者**: K Berčič, S Stanojevikj¹ - … : 19th International Conference, CICM 2026, Ljubljana …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this paper, we test whether a voting ensemble of LLM judges can … The LLM -ensemble experiment in this paper is therefore most directly relevant to systems that, like Mathswitch, accept a broad and noisy open input and need an automated filter; it is

---

### [74] Evaluate the Stack, Not the Layer: Do Deterministic and LLM Gates for Agent Actions Fail Independently?

**链接**: https://arxiv.org/abs/2610.07359
**作者**: Chenglin Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Runtime gates for agent tool calls are stacked on the assumption that their errors multiply. We test it on 1,119 labelled agent actions from three corpora, without an adaptive adversary. The stack has one deterministic rule layer and four LLM judges, three of them re-collected with the served model recorded on every call. We read each stack as a number of multiplication-equivalent layers, n_mult, with its floor under perfect coupling. Under the STRICT miss definition (escalation to a human scored as not stopped), any two judges compose to about 1.2 to 1.4 layers ({\phi} median +0.430, 6 of 6 pairs significant, floors 1.02 to 1.17). The rule layer plus one judge composes to 1.86 to 2.09 layers ({\phi} median +0.014, 0 of 4 significant, floors 1.01 to 1.09). Under PRIMARY (escalation scored as caught) the bands are 1.21 to 1.57 and 1.80 to 2.13. Intervals separate on the pooled data, point estimates split on each corpus, and a third-vendor judge lands in the judge band. Solo accuracy doe

---

### [75] MoF: Preference-Aware Mixture Modeling for Black-Box LLM Personalization

**链接**: https://arxiv.org/abs/2610.08330
**作者**: Hun Park
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Proprietary Large Language Models (LLMs) have demonstrated remarkable capabilities across a wide range of tasks, yet aligning their outputs with diverse user preferences remains challenging. Existing personalization approaches for black-box LLMs often rely on user-specific scoring heads, causing the number of personalized parameters to grow linearly with the number of users and requiring additional adaptation for unseen users. To address these limitations, we propose Mixture-of-Facets (MoF), a scalable personalization framework for black-box LLMs that models user preferences as compositions of shared latent preference facets rather than dedicated user-specific parameters. MoF performs personalization through history-conditioned routing over shared facet heads, enabling personalization for users unseen during training without additional parameter updates. Across diverse personalization tasks, MoF delivers stronger personalization performance while maintaining a more scalable and paramet

---

### [76] PertMind: Eliciting Emergent Biological Reasoning in LLM via Reinforcement Learning on Cellular Perturbation Data

**链接**: https://arxiv.org/abs/2608.16419
**作者**: Zhenchao Tang, Xiaogang Xu, Jiafei Wu, Jiahui Guan, Bo Li, Tianxu Lv 等 (10 人)
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] VietBinoculars: A Zero-Shot Approach for Detecting Vietnamese LLM-Generated Text

**链接**: https://arxiv.org/abs/2509.26189
**作者**: Trieu Hai Nguyen and Sivaswamy Akilesh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Common Corpus: The Largest Collection of Ethical Data for LLM Pre-Training

**链接**: https://arxiv.org/abs/2506.01732
**作者**: Pierre-Carl Langlais, Pavel Chizhov, Catherine Arnett, Carlos Rosas-Hinostroza, Mattia Nee, Eliot Krzystof Jones 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Unanimously Wrong: Certified Abstention from How Medical LLM Consensus Forms

**链接**: https://arxiv.org/abs/2610.07570
**作者**: Xiaoyang Wang, Tianrui Wang, Christopher C. Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In clinical practice, agreement among independent experts is treated as evidence of reliability, and multi-round consensus has become a core mechanism of agentic medical question-answering systems. When such a system must decide whether to trust its own answer, the prevailing signal is again agreement, now among the sampled answers. But agreement is a fragile proxy for correctness. A system can be unanimously wrong, returning the same incorrect answer on every sample, and on these questions agreement-based signals carry no information. The cause is that these signals read only the final state of the consensus and discard how it was reached. Agreement that was reached by resolving disagreement with evidence looks identical, at the end, to agreement that was present from the first sample because every sample shares one misconception. ProbeGuard is a certified abstention framework that bases the abstention decision on how the consensus formed. Process features trace agreement trajectories

---

### [80] One Step at a Time: Trading LLM Autonomy for Process Predictability

**链接**: https://arxiv.org/abs/2610.07817
**作者**: Hans Schabert, Christoph Peters
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizations automating operational processes need more than a correct outcome: they need to predict how a process will run, know which one actually ran, and inspect it step by step. When an agent is the executor that predictability is normally lost: the prescribed procedure goes into the system prompt, and only a final answer comes back. We deliver the procedure step by step over the Model Context Protocol (MCP) instead: a server releases one step at a time, the agent executes it, and each step returns a structured step_output. This trades autonomy for predictability, and two properties then follow by construction, independent of the executor. The execution path is prescribed before the run, so the process is predictable in advance rather than reconstructed afterwards; and the completed step records form a machine-readable execution log that downstream tooling can audit and optimize step by step. Evaluating 15,475 trials across 13 SOP-Bench domains and four open-weight executors from

---

### [81] Cooperative Profiles Predict Multi-Agent LLM Team Performance in AI for Science Workflows

**链接**: https://arxiv.org/abs/2604.20658
**作者**: Shivani Kumar, Adarsh Bharathwaj, David Jurgens
**来源**: cs.CL cs.CY cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] Breaking the Mirror: Activation-Based Mitigation of Self-Preference in LLM Evaluators

**链接**: https://arxiv.org/abs/2509.03647
**作者**: Dani Roytburg, Matthew Bozoukov, Matthew Nguyen, Jou Barzdukas, Simon Fu, Narmeen Oozeer
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] WorldSolver: Can LLM Agents Simulate the Physical Dynamics via Solver Generation?

**链接**: https://arxiv.org/abs/2610.08720
**作者**: Siru Jiang, Yongzhe Lyu, Shuo Lu, Yubin Wang, Yuxiang Zhang, Yue Liao 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly advancing scientific and engineering problem solving, with physics simulation emerging as a challenging yet practical testbed for reproducing complex physical phenomena with application in embodied AI, games and films. As the workhorse of such simulation, a solver computes how the state of a dynamic system evolves over time. Building such solvers requires physical understanding to identify appropriate models, mathematical reasoning to formulate the underlying dynamics, and software engineering to implement them as executable code, yet this capability of LLM agents remains underexplored. To this end, we introduce WorldSolver, a benchmark of 168 simulation tasks derived from physical phenomena in 61 classic computer graphics papers, spanning 7 physical domains. Each task contains a code scaffold that provides a fixed simulation environment for the scene, with the solver implementation left for the agent to complete. Specifically, we evaluate them along t

---

### [84] Dynamic Budget Allocation for LLM Evaluation under Hard Resource Constraints

**链接**: https://arxiv.org/abs/2610.07362
**作者**: Shai Feldman, Yaniv Romano
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We evaluate large language models (LLMs) in multi-turn interactions through their time-to-event: the number of interaction steps required to produce an event of interest, such as a successful jailbreak or agentic task completion. Under limited compute, interactions may be terminated before the event occurs, so that event times are only partially observed (censored). Existing allocation methods for calibrating time-to-event bounds satisfy the budget only in expectation and can exceed the available budget on a particular evaluation run. Enforcing a hard constraint is particularly challenging as the cost of a trajectory is initially unknown. We introduce Hard-budget Allocation with Reflow for Predictive calibration (HARP), a budget allocation that satisfies hard resource constraints and adaptively reallocates unused budget. We show how to use HARP to construct lower predictive bounds (LPBs) on the time-to-event and to estimate evaluation metrics such as the jailbreak rate on a fixed bench

---

### [85] A Real-Time Stray Dog Detection, Alerting and Deterrence System with LLM -Based Contextual Messaging

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11712666/&hl=zh-CN&sa=X&d=11962650211543928779&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVEqnc2BWCebKGfDsOo8ixJs&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=4&folt=kw-top
**作者**: KA Adarsh, A Soman, FM MI, CD Abhinand, PR Bipin - … International Conference on …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> and sent to the individual who made the report using LLM . The alert will be provided in a format … Furthermore, instead of issuing simple warning signals, the system integrates an LLM -based … By integrating computer vision, LLM -driven

---

### [86] Harmful SFT Leaves a Continuous Trace in LLM Checkpoint Updates

**链接**: https://arxiv.org/abs/2610.07518
**作者**: Ziqun Bao and Xinyu Zhang and Yuchen Shao and Chengcheng Wan
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety auditing of post-trained large language models typically relies on model behavior, requiring model execution and depending on the coverage of available evaluations. This work asks a different question: Do the target behaviors optimized during supervised fine-tuning (SFT) leave readable evidence directly in checkpoint updates? We find that harmful-compliance SFT induces a continuous, objective-dependent ordering in checkpoint-update space. Using a reference geometry defined by pure harmful-compliance, safety-targeted, and benign-utility SFT, we find that a checkpoint-level coordinate s_H tracks controlled harmful-objective composition with Spearman correlations of 0.986-0.992 across four 7-8B backbones, with the same ordering persisting at larger model scales. Matched compliance-versus-refusal controls show that this checkpoint trace reflects the SFT objective rather than harmful-input exposure, while additional controls rule out simple explanations based on harmful-example count

---

### [87] LOGIC: An LLM Benchmark for Intent-Grounded Change Impact in Aerospace Electrical Systems

**链接**: https://arxiv.org/abs/2610.07580
**作者**: Muhammad Faraz Shoaib, Muhammad Qasim, Raisulhaq Mohammed Rizwan, Rahmatullah Safdar, Muzammil Adnan Shaik, Abdul Aleem Mohammed
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aerospace electrical-design revisions can contain multiple genuine changes, although an engineering request may authorize only a subset. Propagating every detected difference can therefore produce overly broad impact reports. We present LOGIC, a controlled benchmark and evaluation framework in which locally deployable language models ground a request in a deterministic candidate-change inventory before selected changes are propagated through a typed electrical traceability graph. This separation permits candidate-selection errors to be distinguished from downstream propagation errors. LOGIC contains 168 scenarios, including 144 selection and 24 abstention cases. We evaluate three 7--8B models against intent-agnostic, lexical, and structured-evidence methods, with an oracle-root upper bound. On 96 explicitly anchored selection cases, gate-only structured evidence achieves candidate F1 of 1.0000, compared with 0.9677 for token-lexical matching. On 12 relational-paraphrase cases, token-le

---

### [88] A Robot- LLM Integration Framework for Social Learning Interactions

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DRZgUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA180%26dq%3DLLM%26ots%3DC0ouGVvqcw%26sig%3Ds_PIk2qja2TTFpLpYEpug8LgY5Q&hl=zh-CN&sa=X&d=12105593548009643455&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVFKp0U03BU_pWRBpiqXeJAK&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=0&folt=kw-top
**作者**: AL Lange, H Ackermann, R Lazarides - From Animals to Animats 18: 18th …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper introduces a Robot- LLM Integration Framework in which an LLM functions as an intermediate layer between natural human language and adaptive robot learning. We suggest that LLMs can be utilized at three stages relevant to

---

### [89] Rethinking Visual Provenance: Detection and Watermarking Across Direct Visual Generation and LLM-Driven Code Rendering

**链接**: https://arxiv.org/abs/2610.08137
**作者**: Zheng Gao, Xiaoyu Li, Zhicheng Bao, Yang Song, Jiaojiao Jiang
**来源**: cs.CR cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI systems create images and videos with image/video generation models or by writing code and graphics descriptions that are then rendered. These routes can produce similar visible artifacts but expose different representations, intervention points, and provenance evidence. We develop a production-centered framework that compares detection and watermarking across both routes. An explicit verification specification distinguishes passive inference, message recovery, and authenticated provenance. We organize image, video, source-code, and rendering-aware watermarks by production stage. We examine the different requirements of generated images and video, plots and SVG, programmable video, and agent-composed workflows. Documented Claude, OpenAI, and rendering-tool interfaces connect the framework to concrete systems. We pose ten scoped research questions on identifiability, observability, fair comparison across stages, recoverable payload, reconstruction, synchronization, composition, hybri

---

### [90] UnitBoost: Managing Compound LLM Systems with a Merge Operator, Not a Model

**链接**: https://arxiv.org/abs/2609.09815
**作者**: Xing Zhang, Guanghui Wang, Yanwei Cui, Mengdie Flora Wang, Peiyang He
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Copy That? The Influence of Process Model Representation Format on LLM

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DsrQTEgAAQBAJ%26oi%3Dfnd%26pg%3DPA39%26dq%3DLLM%26ots%3DC58Ss8hGM7%26sig%3D-82yJgsht6VnNiNEMmPz3HtZtDI&hl=zh-CN&sa=X&d=17472441207010004152&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVH_gjpUfgnoW80JEnozjW7q&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=2&folt=kw-top
**作者**: F Rybinski, N Kruse, A Wilhelm, A Fritsch - …, St. John's, NL 等 (9 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In practice, the same process model may be provided to an LLM in different ways, eg, as a … An LLM -as-a-judge scores responses against reference answers using a graded metric and … These findings establish the representation format as a design

---

### [92] Storage Is Not Strategy: State-Conditioned Support Control for LLM Unlearning

**链接**: https://arxiv.org/abs/2609.37858
**作者**: Tianhao Qian, Ziming Hong, Chongyang Gao, Kezhen Chen, Lixu Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] Automating Building Model Preparation: A Comparison of LLM Performance

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DrrQTEgAAQBAJ%26oi%3Dfnd%26pg%3DPA106%26dq%3DLLM%26ots%3D3tE0TXyQfw%26sig%3D7aCp95n3lj_o_yqeA08doTbd7TU&hl=zh-CN&sa=X&d=14646759172492994734&ei=Dd7Farf4B8OuieoPzqLQyQI&scisig=ACTRDVFsk6_b1LRurNFqj4h7Co7O&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=1&folt=kw-top
**作者**: D Odin Iversen, E Hjelseth, J Fauth, L Huang - Proceedings of the Digital Building …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This richer context may significantly improve an LLM's ability to interpret and process model data. This study presents a comparison of an LLM -based information extraction system's performance on building models represented in IFC4. x versus

---

### [94] Reinforcement Learning over Predictive Distributions for LLM Regression

**链接**: https://arxiv.org/abs/2605.20740
**作者**: Jungsoo Park, Hyungjoo Chae, Ethan Mendes, Jay DeYoung, Varsha Kishore, Wei Xu 等 (7 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] Transect: Retaining Observability for Long-Horizon LLM Agent Evaluations

**链接**: https://arxiv.org/abs/2610.08364
**作者**: Toby D. Pilditch, Konstantinos Voudouris, Alexandra Abbas, Cozmin Ududec
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier AI evaluations increasingly use open-ended, agentic, long-horizon tasks whose transcripts can span hundreds of pages of outputs and actions from complex multi-agent networks. The observability envelop-the range of what evaluators can reliably infer about an agent's behaviours-is therefore narrowing. Language model assistants can help classify and interpret agent behaviour but also afford human evaluators significant analytical degrees of freedom, threatening the reproducibility and auditability of language-model-based transcript analysis. Transect is an open source package built on Inspect Scout to help evaluators understand how a long agent run unfolded, identify behaviour worth investigating, and check interpretations against the transcript. Users specify task context and behavioural vocabulary in a reusable evaluation-family configuration, with judge models and analysis settings supplied separately. Transect's navigable reports align recorded events, token use, sub-agent ac

---

### [96] SchemaFill: Efficient LLM Tool Calling via Slot-Parallel Speculative Decoding

**链接**: https://arxiv.org/abs/2610.07086
**作者**: Zhi-Kai Chen, Song-Yan Li, De-Chuan Zhan, Han-Jia Ye
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents interact with external systems by generating structured tool calls. Given a user request, conversational context, and a catalog of tool schemas, a tool-calling model must select tools and generate their arguments, potentially producing multiple calls in a single response. Standard autoregressive decoding generates these calls token by token, incurring substantial latency for requests involving multiple calls or many argument fields. The explicit argument structure offers opportunities for parallel generation, but later argument values may depend on preceding fields and calls, so independently generated values can differ from the target model's output. We present SchemaFill, a framework for efficient LLM tool calling through slot-parallel speculative decoding. SchemaFill generates future slot values concurrently as candidates, without requiring advance knowledge of the actual call sequence or argument values. Candidates spanning multiple fields and calls are concatenated for 

---

### [97] Secure Speculative Decoding for Large Language Models

**链接**: https://arxiv.org/abs/2610.08678
**作者**: Yichi Zhang, Zhiqi Wang, Neil Gong, Yuchen Yang
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates inference for a large language model (LLM), referred to as the \emph{target model}, by first using a smaller model, referred to as the \emph{draft model}, to generate candidate tokens and then verifying them with the target model for acceptance or rejection. Prior studies primarily focused on the efficiency-utility trade-off of speculative decoding, e.g., lossy speculative decoding, leaving its security implications largely unexplored. In this work, we bridge this gap by providing the \emph{first} systematic study of the security implications of speculative decoding. Through a large-scale measurement study, we reveal a pronounced security-utility asymmetry: across a wide range of lossy speculative decoding methods, improvements in inference efficiency come at a disproportionately high cost to security, with attack success rates for jailbreak and prompt injection attacks increasing much faster than utility degrades. We then propose SecureSD, a new theory

---

### [98] Uncertainty Localization in LLM Reasoning via Embedding Perturbations

**链接**: https://arxiv.org/abs/2602.02427
**作者**: Qihao Wen, Jiahao Wang, Yang Nan, Pengfei He, Ravi Tandon, Han Xu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [99] Semantic Behavioral Watermarking: Paraphrase-Robust and Forgery-Resistant Provenance for LLM Agents

**链接**: https://arxiv.org/abs/2610.08668
**作者**: Suxin Ji, Hungtao Wan, Shaoxuan Chen, An Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Behavioral watermarking embeds an owner identifier in an LLM agent's high-level action choices, giving provenance without touching output tokens. Prior agent watermarks break in two ways. First, all three prior schemes bind the watermark to the exact action symbol, so renaming a tool desynchronizes decoding even when the observation is untouched; in AgentMark's own robustness test, paraphrasing the observation alone drops bit-recovery to 16.8%. Second, every prior agent watermark studies only removal: none asks whether an adversary can forge a trajectory that verifies as someone else's, a question answered affirmatively for text watermarks (Jovanovi\'c et al., 2024). We present Semantic Behavioral Watermarking (SBW): watermarking over semantic action clusters under history conditioning, with the public-cluster bin replaced by keyed collision-resistant binning whose fresh-bucket assignment is provably unpredictable in the random-oracle model. Across five agent models (3B-14B, four vendo

---

### [100] When Does External Guidance Help LLM Reasoning? A Bias-Variance Theory of Guidance-Augmented GRPO

**链接**: https://arxiv.org/abs/2610.06861
**作者**: Sofia Torres, Gabriel Almeida, Carter Adams, Camila Rocha
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) has become the dominant paradigm for eliciting multi-step reasoning in large language models, and a recent wave of methods (LUFFY, ExPO, PAPO, TAPO) further augments RL with \emph{external guidance} - expert traces, self-explanations, or retrieved thought patterns. Although each method reports empirical gains, none provides convergence rates, bias bounds, or an optimal weighting rule for the guidance signal. We close this gap with \emph{Guidance-Augmented GRPO} (GA-GRPO), a unified theoretical framework that casts external guidance as a stochastic guidance operator G re-writing the question distribution, and analyses the resulting policy-gradient estimator as a biased on-policy estimator whose bias is bounded by the total-variation guidance divergence delta\_G between the guidance-augmented sampling distribution and the policy's own distribution. The framework subsumes vanilla GRPO, LUFFY, ExPO, PAPO, and TAPO as special cases obtai

---

### [101] Critic Experience Bank: Self-Evolving Step-Level Confidence Estimation for LLM Agents

**链接**: https://arxiv.org/abs/2607.12397
**作者**: Yaopei Zeng, Congchao Wang, JianHang Chen, Nan Wang, Yurui Chang, Lu Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] When Does a Second Model Help? Cross-Model Review in LLM Verification

**链接**: https://arxiv.org/abs/2610.01471
**作者**: Tae-Eun Song
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] Improving Diversity in LLM Short Story Generation

**链接**: https://arxiv.org/abs/2610.06729
**作者**: Zahra Solati Dehkordi and Vasileios Lampos
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] RadOnc-Agent: An LLM-Orchestrated Framework for AI Workflows Across the Radiotherapy Care Pathway

**链接**: https://arxiv.org/abs/2610.06923
**作者**: Caiwen Jiang, Shuoyang Wei, Songlin Zhao, Junyu Li, Jingyuan Chen, Wei Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence has advanced individual radiotherapy tasks, yet these capabilities remain separated across clinical stages, software environments and data modalities. This fragmentation contrasts with the longitudinal radiotherapy workflow from treatment decision-making through follow-up. Here we present RadOnc-Agent, an agentic artificial-intelligence framework that formalizes radiotherapy into four clinical phases and provides 26 callable functions through a conversational interface. A large-language-model controller maps clinical intent to schema-constrained calls, preserves patient and workflow context, and routes requests to specialist services. We evaluated system execution using 2,600 single-function requests (7,800 repeat executions), 200 prespecified synthetic cross-stage scenarios spanning four phases (600 executions), and 120 workflow instances from 60 de-identified patient records (360 clean executions) representing decision-to-planning and planning-to-adaptation. R

---

### [105] When Does AI Supervision Help? A Role-Aware Study of Network Fraud Decision Management with Blockchain Auditability

**链接**: https://arxiv.org/abs/2610.07434
**作者**: Saviz Changizi, Nasibeh Mohammadzadeh, Mohammad Shojafar, Rahim Tafazolli
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When does a second artificial intelligence (AI) component improve a primary network-fraud decision rather than add operational burden? We study this question through a role-aware Decider-Supervisor (DS) framework with blockchain auditability, evaluating four directional configurations that combine centralised machine learning, a Federated Averaging (FedAvg)-trained federated meta-model, and Base or Quantized Low-Rank Adaptation (QLoRA) large language model variants. The analysis compares primary-only and supervised decisions using non-hard fraud performance, intervention burden, conditional calibration, traffic-mix and Review-capacity sensitivity, dependability tests, and blockchain lifecycle controls. The deterministic hard gate resolves 89.994% of fraudulent requests, leaving the non-hard population as the main AI decision setting. Conditional validation calibration does not produce a consistently transferable supervisory advantage on deployment replay. DS-3 QLoRA is the least disrup

---

### [106] Symphony for Text Generation: Benchmarking Clinical Note Generation

**链接**: https://arxiv.org/abs/2610.08161
**作者**: Daniel Varab, Victor Petr\'en Bach Hansen, Asbj{\o}rn W. Helge, Kevin Pelgrims, Mathias Baltzersen, Adrian Young-San Roessler 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ambient documentation systems are rapidly gaining adoption, yet their impact on clinical note quality remains poorly characterized. We introduce MedConv, a multilingual dataset of 300 clinical encounters in English, Danish, and German, and use it alongside the Ambient Clinical Intelligence benchmark (ACI-BENCH) to compare Corti, a clinical AI platform, with two leading, accessible ambient scribe software applications built on general-purpose AI. We present a controlled clinical evaluation framework that combines entailment metrics with LLM-judged pairwise comparisons across eight dimensions adopted from PDSQI-9. Results show that Corti's API-based text-generation infrastructure is on par with or outperforms leading commercial scribes. We further show that Corti's configurable API provides the flexibility necessary to fine-tune quality dimensions for specific documentation use cases. We present the evaluation methodology and release a dataset to support future reproducible comparison of

---

### [107] MINDSET: Energy-based Schema Evolution for Long Conversational Agent Memory

**链接**: https://arxiv.org/abs/2610.08586
**作者**: Sujato Dutta, Sreekruthy Tummala, Shashank Vanga, Ayushmi Pavani
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long conversational agents have become essential in our daily lives. They must remember what was said long back in order to help us efficiently complete a task without needing the user to repeat instructions and context repeatedly. However, the main issue is that instructions and context change over time and so the agents must be able to adapt accordingly. A useful memory system should preserve both current and historical states, distinguish stale information from active knowledge, retrieve evidence appropriate to the query and avoid repeatedly invoking a large language model to rewrite prior interactions. We introduce MINDSET, a memory controller that stores a conversation as immutable episodes and organizes them into versioned schemas through minimum-energy state transitions. Each incoming episode may reinforce, supersede, split or create a schema. The transition decision balances representation distortion, contradiction, historical damage, fragmentation and internal inconsistency, w

---

### [108] Who Wrote It Is Not Enough: Detecting Who Contributed the Insight

**链接**: https://arxiv.org/abs/2610.07365
**作者**: Zhuoyang Zou, Abolfazl Ansari, Jiaxi Yang, Delvin Ce Zhang, Qian Chen, Dongwon Lee 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLMs increasingly assist scientific writing and peer review, detecting who wrote the text is no longer sufficient: we need to determine who contributed the underlying insight. We introduce Insight Provenance, the task of identifying whether a review insight originates from a human, an LLM, or their hybrid contribution. We construct InsightProv-v0 from 4,057 scientific papers and 12,660 human reviews, simulating different levels of LLM involvement with GPT-4o, Gemini, and DeepSeek and annotating provenance at the sentence level. We show that strong performance on raw data can be misleading, as models exploit linguistic and textual-authorship shortcuts that degrade substantially under progressively debiased evaluation. We therefore propose a two-stage adversarial framework that suppresses shortcut signals while preserving provenance-relevant information. Beyond detection, extensive analyses reveal what makes intellectual authorship identifiable: paper grounding and neighboring review 

---

### [109] UNREAL: Unifying Retrieval and Long-Context with a Single Model

**链接**: https://arxiv.org/abs/2610.08463
**作者**: Edan Kinderman, Elad Hoffer, Yochai Blau, Brian Chmiel, Ron Banner, Daniel Soudry 等 (7 人)
**来源**: cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context inference and Retrieval-Augmented Generation (RAG) handle evidence selection at vastly different scales, from a single long prompt to an entire corpus. We ask whether a single model-internal mechanism can select evidence across this range. We introduce UNifying REtrieval And Long-Context with a Single Model (UNREAL), a model-native evidence selection framework to span corpus retrieval and long-context inference. UNREAL encodes chunks and derives retrieval queries directly from the frozen LLM's internal representations. It adds fewer than 500K trainable parameters and leaves the backbone unchanged. On a 3B-token, 21M-chunk Wikipedia index, all four dense and hybrid UNREAL backbones outperform state-of-the-art retriever-reranker systems. The best model raises recall from 49.1% to 73.2% on HotpotQA, from 31.7% to 60.1% on 2WikiMultiHopQA, and from 8.8% to 14.4% on MuSiQue. Applied to long-context tasks, the same selection mechanism removes distractors before generation, raisi

---

### [110] CroissantMiner: Automated Extraction and Validation of Croissant Metadata for ML Datasets

**链接**: https://arxiv.org/abs/2610.07132
**作者**: Berke Arda, Ahmetcan Yavuz, Paul Gerry, Sebastian Lobentanzer, Nobin Sarwar, Joan Giner-Miguelez 等 (10 人)
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Croissant has emerged as a standard for machine-readable dataset metadata, yet populating its fields remains labor-intensive and requires careful reading of accompanying dataset documentation. We present the first benchmark enabling end-to-end evaluation of metadata extraction aligned with a community-standard schema. The benchmark comprises 602 papers, including 102 with human-validated gold annotations and 500 with LLM-generated silver annotations, covering the full Croissant schema with both core and Responsible AI (RAI) fields. Using this benchmark, we evaluate a range of extraction systems spanning frontier models, open-weight models, and agentic architectures, under a two-tier evaluation framework that combines rule-based scoring with an LLM judge selected via human audit. We find that single-pass extraction consistently outperforms the four agentic architectures we evaluate: across backbones, these decomposed variants achieve lower accuracy than a single full-context pass. The l

---

### [111] Evidence-Bound Reasoning: Neuro-Semantic Verification of Biomedical AI in Glioblastoma Radiogenomics

**链接**: https://arxiv.org/abs/2610.08660
**作者**: Mariya Miteva, Maria Nisheva-Pavlova
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Biomedical AI can generate plausible explanations without reliably verifying whether each statement is supported by patient-specific evidence. We developed a neuro-semantic verification framework that converts radiomic measurements into addressable evidence records and machine-checkable claims. Methods: UPenn-GBM radiomics were aligned with de novo CaPTk extraction from standardized MRI and expert-validated segmentations in an independent multicenter cohort. The shared space comprised 1,728 features from T1, T1GD, T2, and FLAIR MRI across three tumor regions. Reference-defined semantic states were derived from 611 UPenn cases. We evaluated cross-cohort transportability, model-linked provenance, deterministic verification, controlled predictive degradation, and an LLM claim-extraction pilot; MGMT prediction served only as a transport stress test. Results: Median semantic-state agreement was 0.786 (weighted kappa 0.709), ranging from 0.918 for morphologic to 0.252 for intensi

---

### [112] Harness Engineering for Software Engineering via Modular Executable Dev-Primitives

**链接**: https://arxiv.org/abs/2610.07832
**作者**: Haibo Jin, Xinjie Li, Peng Kuang and Haohan Wang
**来源**: cs.SE cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) equipped with terminal access have demonstrated strong capabilities in automating software engineering tasks. However, existing agents remain brittle on long-horizon workflows, where they must repeatedly reconstruct program state scattered across source files, configurations, tests, dependencies, and runtime behavior, leading to increasingly long interaction histories, context explosion, and semantic drift. Large repositories further complicate the identification of task-relevant components. To address these challenges, we introduce \textbf{Dev-Primitives} (\emph{Development Primitives}), a modular and executable abstraction that transforms repository components from passive software artifacts into active participants in software engineering. Each Dev-Primitive pairs a repository artifact with a resident LLM, which gives the artifact an agent-native interface grounded in its own implementation and dependencies, enabling natural-language reasoning, inter-com

---

### [113] Do LLMs Act on What They Know? From Partner Representations to Cooperative Actions

**链接**: https://arxiv.org/abs/2610.08129
**作者**: Yuhwan Jeong, Jinnyeong Yang, Kuk-Jin Yoon
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cooperation with unfamiliar partners requires adapting to communication conventions that are not known in advance. We study this problem in a controlled Hanabi-derived environment with scripted hint generation, LLM-controlled receiving decisions, and frozen model weights. Across eight LLMs, linear probes recover intent conventions substantially more accurately than target conventions, yet receiving choices do not consistently agree with the sender's convention. We compare probe-predicted and ground-truth conventions presented either as general rules or as externally computed action recommendations. Rule statements yield modest and model-dependent changes in cooperation, whereas action translation produces larger gains on average. In a Qwen3-8B case study, matched-state statement reversals reveal much greater sensitivity to action recommendations than to rule statements. Activation transfers from oracle-action and non-oracle hint-restatement donors improve intent accuracy on both action

---

### [114] The Model Plants the Trigger: Answer-Side Backdoor Attacks in Multi-Turn Large Language Models

**链接**: https://arxiv.org/abs/2610.07723
**作者**: Yibo Zhang, Tianrong Guan, Liang Lin, Puze Wang, Jin Wang, Qingsong Wen
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety alignment in Large Language Models (LLMs) remains vulnerable to backdoor attacks. Existing LLM backdoors are almost all input-centric: activation depends on explicit trigger patterns in the user input, so modern guardrails are built to sanitize the input space. We challenge this assumption with a novel answer-side backdoor for multi-turn dialogue. Instead of inserting the trigger into the input, the adversary uses a benign first-turn prompt to naturally induce the model to generate a specific, seemingly innocuous word. Once merged into the dialogue history, this self-generated word becomes the trigger. When a later harmful query arrives, the model detects its own trigger and bypasses its safety refusal, while the user input stays perfectly clean. Across four LLMs, our attack reaches near-perfect Attack Success Rates, approaching 100\% at only a 5\% poisoning rate, while preserving general utility and clean-input safety, and it evades mainstream input-centric defenses. Representa

---

### [115] Evaluating Inference Compute for Generative AI: A Framework for Enterprise Workloads

**链接**: https://arxiv.org/abs/2610.07094
**作者**: Abbas Raza Ali, Muhammad Ajmal Siddiqui, Moona Zahid
**来源**: cs.AR cs.DC cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM deployment is shifting from single-turn completion to agentic trajectories in which a model plans, calls tools, reads results and reasons at test time before acting. This inverts the economics of inference hardware: chat serving amortises weight reads across large batches, whereas agent trajectories are sequentially dependent, run at effective batch one, and make per-token decode latency (TPOT) the dominant term in task completion time. Using a roofline analysis and a closed-form episode-latency model, we show why this regime favours accelerators that keep weights in on-die SRAM (Cerebras WSE-3/3T, Groq/NVIDIA LPU) or compiler-managed tiered memory (SambaNova SN40L/SN50), and why three vendor ecosystems converged in 2026 on disaggregated prefill/decode serving. We show that per-step reliability compounds exponentially in trajectory length-a 2% per-step failure rate erases a 2x decode advantage for a 20-step agent-so determinism and tail latency are first-order performance variables

---

### [116] Massive Activation Gating Channel in Large Language Models

**链接**: https://arxiv.org/abs/2610.07661
**作者**: Minjia Mao, Shi Chen, Bowen Yin, Xiao Fang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Massive activations, a phenomenon in which a small number of hidden channels exhibit exceptionally large magnitudes, are pervasive in large language models (LLMs). However, the mechanism by which a token develops massive activations as it propagates through a pretrained LLM remains poorly understood. In this paper, we find that the emergence of massive activations is controlled by a single channel in the input embedding to a spike feed-forward network (FFN). The position of this channel is fixed for a particular LLM. We name this channel the massive activation gating channel (MAGC). When the value of the MAGC is sufficiently large (or small, depending on the LLM), the output of the spike FFN exhibits massive activations. Examining six LLMs across four model families and different model sizes, we verify the existence and effect of MAGC. We further provide a theoretical explanation of the mechanism by which MAGC induces massive activations. When the value of MAGC is sufficiently large (o

---

### [117] ScienceClaw: Benchmarking Continual Self-Evolution of AI-for-Science Agents Across the Natural and Social Sciences

**链接**: https://arxiv.org/abs/2610.08691
**作者**: Mingda Zhang, Wenjin Liu, Tiesunlong Shen, Zikai Xiao, Zhenghong Lin, Qing Xu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are accelerating scientific automation, yet verified executions rarely become persistent program-level improvements, and existing evaluations do not examine this process across sequential tasks in both the natural and social sciences. We formalize ScienceClaw as fixed-parameter program self-evolution that unifies task solving, scientific verification, and program updates. ScienceClaw-Eval spans 23 disciplines and measures scientific correctness, evolutionary gain, retention, cross-dataset transfer, and evolution cost through sequential streams and independent reset evaluation. Our framework repairs executable workflows through multi-turn interaction, converts re-execution-verified failure--success trajectories into linked Skill and Operator candidates, and retains an update only when source-task replay reproduces the repair and independent scientific tasks improve. Code is available at https://github.com/beita6969/ScienceClaw.

---

### [118] Stateless Language Agents: Scaling Long-Horizon Automated Research

**链接**: https://arxiv.org/abs/2610.07625
**作者**: Qizheng Zhang, Changxiu Ji, Isaac Sun, Yuetai Li, Shubhangi Upasani, Sherry Ruan 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated research systems increasingly run LLM agents over long horizons, but more inference does not by itself produce more progress: agents replay growing histories, duplicate one another's work, or stop experimenting while token consumption continues. Yet most evaluations use short budgets or benchmarks that saturate early, leaving these failure modes untested. We trace these failures to two choices: where research state lives and who decides what to try next. We introduce Stateless Language Agents (SLAs), built on the principle of stateful search with stateless agents: no agent carries its conversation across invocations; instead, the harness owns the research state (candidate solutions and measured outcomes) and reconstructs a fresh and role-specific context for every invocation. What each agent sees becomes an explicit design choice rather than a history that grows with the run. We implement this principle in the SLA framework, where a stateless Advisor reads harness-summarized 

---

### [119] Memory Depth and Reconstructed Context Width: A Controlled Evaluation of Hierarchical Retrieval

**链接**: https://arxiv.org/abs/2610.08300
**作者**: Michael Andreev
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term conversational memory is becoming an integral component of modern LLM systems. Proposed architectures group records by topics and events, construct hierarchies and graphs, and connect facts through causal and temporal relations. We experimentally study the interaction between two memory parameters: structural depth and the width of context supplied to the answer model. Using EverMemBench, we evaluate depths D1-D4, core budgets of 1,024/2,048/4,096 tokens, and additional Production and Oracle conditions up to the full archive. Increasing width from 1K to 4K improves Accuracy by 10.11-17.98 percentage points, whereas increasing depth provides no monotonic gain. Beyond 8-16K, Production performance reaches a plateau while tokens per correct answer continue to increase; Oracle preserves quality on full archives of 68-71K tokens. These results motivate further investigation of large, coherent context blocks instead of progressively deeper memory structures.

---

### [120] SIGMA: Self-Improving Alignment Generalization from a Model Spec

**链接**: https://arxiv.org/abs/2610.07935
**作者**: Jingyu Zhang, Shruti Palaskar, Daniel Khashabi, Benjamin Van Durme, Leon A. Gatys, Joseph Yitan Cheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly capable of executing complex tasks and of recursively improving themselves on easy-to-verify objectives such as software engineering and mathematics. Since alignment is much harder to verify, this creates a growing risk of capabilities increasing without appropriate safety alignment, especially as capabilities expand to auto-research and cybersecurity. Existing approaches focus on capability self-improvement using verifiable feedback or on alignment training with supervision from stronger models or curated data, creating an external supervision bottleneck for alignment. We ask whether current models can improve their own safety alignment, and propose SIGMA, a data generation and training pipeline enabling alignment self-improvement that generalizes to out-of-distribution settings. Given only a "Model Spec" stating the model's desired behavior, SIGMA leverages a model's reasoning capabilities to strengthen its own safety reasoning. SIGMA first performs spec-g

---

### [121] OMIT the Action: Measuring Framing-Invariant Omission Bias under Philosophical Disagreement

**链接**: https://arxiv.org/abs/2610.07847
**作者**: Sihyeon Lee, Jihun Song, Chanwoo Kim, Jiwoo Kum, Chanjun Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLMs increasingly assist in moral reasoning, omission bias, the tendency to prefer inaction even when equivalent framings reverse substantive outcomes, poses a significant risk of skewed decision-making. Yet omission bias remains underexplored in LLM evaluation, with the few existing studies limited in scale and focused largely on utilitarian-deontological conflicts. To address this gap, we introduce OMIT, a benchmark consisting of 218 paired-frame scenarios across 10 conflict types, constructed by leveraging disagreement patterns from an LLM-based, five-perspective philosophical persona panel (utilitarianism, deontology, virtue ethics, care ethics, and contractualism). Evaluating eight LLMs, we find that omission bias is pervasive but inversely correlates with model size within families. We further evaluate four inference-time interventions and find that interventions encouraging models to consider moral principles before committing to a yes/no answer reduce omission bias and incre

---

### [122] Evidence Before Sampling: Interpretable Implicit Negative Candidate Discovery for Recommendation

**链接**: https://arxiv.org/abs/2610.07708
**作者**: Shreya Rajpal, Sonia Sharma, Swapnil Parekh, Lisa Li, Jeyendran Balakrishnan, Nagaraj Janardhana 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recommender systems learn from observed user-item interactions, but explicit negative feedback is often unavailable. Since deep learning models require negative signals for training, negative sampling methods typically treat selected unobserved interactions as negatives. However, a missing interaction does not explain why a user is uninterested in an item or whether there is sufficient evidence to label it negative. This is especially important in business recommendation, where negative signals should be interpretable and aligned with business objectives. We formulate implicit negative candidate discovery to identify unobserved interactions supported by observed customer behavior. We encode these patterns as symbolic rules, score them based on support, informativeness, and product relevance, and rank the retained rules by evidence. An LLM then interprets the retained rules using business objectives and domain knowledge; the interpretations are combined with the statistical evidence in 

---

### [123] Where Rules End and Judges Begin: Measuring the Judgment Boundary in Multi-Agent Systems Security

**链接**: https://arxiv.org/abs/2610.07657
**作者**: Shaswata Mitra, Raj Patel, Subash Neupane, Sudip Mittal, Md Rayhanur Rahman, Shahram Rahimi
**来源**: cs.AI cs.CL cs.CR cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) engage tools, share memory, and delegate tasks, often encountering adversarial content. Current defenses for MAS are typically evaluated in isolation, focusing on one attack type at a time, which can lead to costly and hard-to-audit outcomes. This study organizes defenses into five principles, implementing them as DEFER1 (DEterministic-First Enforcement with Residual judgment), which includes a cascade of 28 checks that blocks what it can and refers the rest to a panel of four judges. In independent testing across four domains, attack success rates drop from about 30.0% to approximately 3.0%, with 78% of blocked attacks handled by deterministic checks. Only a quarter of proposals reach the judges in the security-operations domain, illustrating that the rules provide security for attacks violating clear policies, while judges manage those that only misrepresent intent. Both systems have weaknesses, such as a risk-score approval gate that inaccurately 

---

### [124] Structuring MoE Expert Selection for Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.07332
**作者**: Bolian Li, Ting-Yao Hu, Cheng-Yu Hsieh, Sanjoy Chowdhury, Oncel Tuzel, Raviteja Vemulapalli
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents are frequently implemented using sparse mixture-of-experts (MoE) models, yet the co-design of agentic behavior and MoE structures remains underexplored. In this work, we comprehensively study the connections between agentic post-training and MoE expert selection. In off-the-shelf MoE models, we observe expert selection exhibits a specialized structure that naturally aligns with agentic trajectories. Specifically, expert routing overlaps more between turns where the agent performs semantically similar operations (e.g., READ, UPDATE) than between turns with differing operations. However, standard RL algorithms ignore this specialization, allowing the MoE routing to go uncontrolled during training, which empirically limit task performance and inference efficiency. To address this, we introduce a hierarchical routing control framework for agentic tasks. We explicitly encourage turn-level expert selections to align with agentic operations while regularizing token-lev

---

### [125] FactorBench: A Portfolio-Aware Benchmark for Automated Factor Mining

**链接**: https://arxiv.org/abs/2610.06947
**作者**: Zhuohan Wang, Carmine Ventre
**来源**: q-fin.PM cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Factor mining seeks to discover signals from financial data that predict future asset returns and guide portfolio construction. Automated factor mining now spans genetic programming, reinforcement learning, generative models, and large language model agents. Yet it remains unclear whether advances across these paradigms yield more generalizable, distinct, and economically useful financial signals. We introduce FactorBench, a portfolio-aware benchmark comparing roughly five thousand mined factors from nine automated mining methods across five equity markets. A shared data and evaluation contract supports both symbolic expressions and executable Python factors, connecting heterogeneous discovery algorithms to common signal combination and portfolio construction procedures. FactorBench traces the outputs of mining systems across three levels: factor validity, temporal generalization, and predictiveness beyond measured risk and style exposures; within- and across-method pool distinctness, 

---

### [126] Component and Dimension Sparsity in Transformer Refusal Mechanisms

**链接**: https://arxiv.org/abs/2610.06903
**作者**: Vincent Siu, Glenn Grant-Richards, Vlad Pavlovich, Yizhou Sun, Dawn Song, Chenguang Wang
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering manipulates large language model behavior by intervening on internal activations, but the mechanistic basis of these interventions remains poorly understood. We decompose refusal steering into component-level interventions across four open-weight models, identifying the sparse subsets of attention and MLP components whose steering suffices to reproduce the full behavioral effect. We find that refusal directions concentrate in sparse component mechanisms comprising 28--48\% of upstream components, retaining 88--101\% of steering effectiveness. Within these mechanisms, effective steering further concentrates in approximately 50\% of residual stream dimensions, retaining 85--98\% of the component-mechanism baseline, consistent with a privileged basis structure. Sparsity thus operates at two levels: which components are steered, and which dimensions within those components carry the signal. Together these findings show that refusal is not diffusely encoded across a tran

---

### [127] ST-Bench: A Spatial-Temporal Benchmark for Multi-Agent System Generation on Scientific Research Tasks

**链接**: https://arxiv.org/abs/2610.07763
**作者**: Qi Cheng, Rongchao Dong, Shengyu Chen, Licheng Liu, Dan Lu, Zhengzhang Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid progress of LLM-based multi-agent systems (MAS) has shown that they largely outperform single agents on coding, math, and QA tasks, where executable tests provide a binary success signal. Whether this advantage transfers to real scientific data analysis remains untested. We introduce ST-Bench, a benchmark designed to answer two questions: whether MAS outperform single agents on complex scientific data analysis tasks, and if so, by how much and at what additional cost. ST-Bench contains 100 data science tasks adapted from published Earth science studies across hydrology, agriculture, and wetland methane research, expanded into 2,067 queries grounded in additional published studies and validated by domain experts. Using ST-Bench, we evaluate five recent MAS generation methods under two training protocols, against single-agent baselines on the same GPT-5 backbone. Nine of the ten MAS configurations exceed the cheapest single-agent baseline, with the strongest reaching nearly thr

---

### [128] Educating future engineers about LLMs: A scalable workshop

**链接**: https://arxiv.org/abs/2610.07027
**作者**: R. Zhang, J. C. F. de Winter, T. Dicke, D. Dodou, Y. B. Eisma
**来源**: cs.HC cs.CY cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) are increasingly integrated into engineering workflows, students require hands-on experience to learn how to collaborate with them critically. This paper presents a scalable gamified workshop designed for engineering Master's students to practice human-AI collaboration in navigation planning. Using a mobile web interface across 10 workshop sessions, a total of 226 students wrote prompts for a non-reasoning and a reasoning LLM to solve grid-based navigation tasks of increasing complexity. The system returned robot-executable plans, trajectory visualizations, and automated scoring, culminating in a live demonstration on a Boston Dynamics Spot robot. In a post-workshop questionnaire, 81.5% reported substantial learning and 91.0% reported high engagement. Analysis of the submitted prompts revealed that students changed their strategies from step-by-step instructions for the non-reasoning LLM toward providing higher-level guidance for complex problem-solving 

---

### [129] Weight Oracles: Reading Neural Network Weights with Language Models

**链接**: https://arxiv.org/abs/2610.07334
**作者**: Krishna Kabra, Constantin Venhoff, Christian Schroeder de Witt
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpretability methods for neural networks are predominantly reactive: they analyse activations produced during specific forward passes, requiring known inputs to find hidden capabilities such as backdoors. We propose Weight Oracles, fine-tuned language models that diagnose properties of a target network by reading its raw weights directly, without behavioural testing. We investigate this paradigm in two phases. Phase I establishes feasibility: through a staged curriculum and an external chain-of-computation that delegates parameter-free operations to deterministic code, an explainer LLM learns to simulate the forward pass of small transformers from their weights, achieving 99% holdout accuracy on unseen targets. Phase II repurposes this infrastructure for safety auditing. We train an oracle on natural language diagnostic questions about weight anomalies using only benign pathologies as training signal, and evaluate it zero-shot on backdoors absent from training. The oracle achieves 

---

### [130] Pseudowords as probes: Large Language Models show little of the sublexical sensitivity that governs human pseudoword processing

**链接**: https://arxiv.org/abs/2610.07936
**作者**: Jing Chen, Giulia Loca, Simona Amenta, Marco Marelli
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematicity, the probabilistic mapping of form to meaning, permeates language at all levels, and sublexical cues have been shown to govern human pseudoword processing. Yet whether LLMs exhibit comparable sensitivity to these cues remains unclear. We tested five LLMs on two Italian two-alternative forced-choice pseudoword experiments and compared their responses with a human behavioural baseline. LLMs aligned more reliably with humans when real-word options provided a lexical familiarity cue than in the pseudoword-only condition, where they fell substantially below fastText, a character-n-gram model. In addition, the sublexical cosine-similarity cue that reliably drove human--fastText agreement did not consistently transfer to human--LLM alignment, and reasoning-token expenditure bore no consistent relation to human processing difficulty. These findings suggest that LLMs do not necessarily share the sublexical cues that govern human pseudoword processing; we discuss tokenization and t

---

### [131] DirectSpeech2LLM: A Simple End-to-End Framework to Mitigate Prompt Overfitting in Speech-LLMs

**链接**: https://arxiv.org/abs/2610.08085
**作者**: Hemant Yadav, Sunayana Sitaram, Roger Zimmermann, Rajiv Ratn Shah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech-LLMs often exhibit prompt overfitting, where models solely trained on automatic speech recognition (ASR) instruction fail to generalize to new instructions such as speech translation and continue to behave primarily as ASR system. We propose DirectSpeech2LLM, a simple end-to-end framework that preserves the instruction-following ability of the LLM on unseen tasks when conditioned on speech. It computes distance-based CTC loss over the frozen LLM embedding matrix and uses greedy CTC labels to derive geometrically and temporally aligned speech embeddings respectively as an input to the LLM. Trained solely on 960 hours of LibriSpeech ASR data, DirectSpeech2LLM outperforms the cascaded system on ASR (seen task) and generalizes zero-shot to speech translation and emotion recognition (two unseen tasks), closely matching the cascaded system upper bound on these two new instructions despite seeing neither during training. We also find that geometric alignment strength plays a smaller ro

---

### [132] APEX: Speculate smarter, not deeper

**链接**: https://arxiv.org/abs/2610.07780
**作者**: Manvi Jha, Zach Zhang, Zhichao Xu, Linbo Liu, Sai Muralidhar Jayanthi, Vinayak Arannil
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding reduces large language model inference latency by drafting multiple tokens before target-model verification, but its effectiveness depends on both the proposal mechanism and draft depth. Fixed configurations cannot respond to changes in predictability, repetition, and acceptance during generation, so deeper drafting can increase wasted computation without proportional speedup. We introduce APEX, a learned controller that balances decoding speed and draft-token waste through request-level expert selection and block-level depth adaptation. APEX-Router selects among EAGLE-3, n-gram, and draft-model speculation for each request, while APEX-Depth adjusts draft length at each verification block using causal decoding signals and recent verifier feedback. APEX models accepted draft length as censored survival feedback, learning position-wise rejection hazards, block execution costs, and an action utility that balances throughput, accepted progress, and wasted tokens. This 

---

### [133] ReFold: Training-Free Reversible Inter-Turn Context Folding for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2610.07863
**作者**: Yupeng Su, Jiayi Tian, Zheng Zhang, Souvik Kundu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents act on an append-only interaction history that is re-sent to the model at every step, so the context and its cost grow with steps until the sessions exceed the context window. Existing methods manage the context through context requirement prediction, relying on additional model calls, heuristic rules, or trained policies. However, these predictive approaches introduce runtime overhead, invalidate prefix caches, and permanently discard content with no guarantee of recovery. To overcome these limitations, we introduce ReFold: a training-free rendering layer that preserves the underlying interaction history while compressing only the model's rendered context. It removes two kinds of inter-turn redundancy without an auxiliary predictor: content an earlier turn already displayed, replaced by a stub, and turns the agent itself reports finished, folded into a one-line note. Both operators use chunked rendering, rewriting the cached prefix once every few steps rather t

---

### [134] HygieneRoboBench: Benchmarking Hygiene-Aware Planning for Household Robots

**链接**: https://arxiv.org/abs/2610.08642
**作者**: Yurun Chen, Josh Qixuan Sun, Jason Qin, Chengtai Li, Tianyi Wang, Mark Crowley 等 (7 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contact with contaminated objects can spread hazards through a household robot's grippers, tools, and shared surfaces, while new contacts can make an existing plan unsafe. Existing benchmarks do not jointly assess how planners identify hygiene risks from contact history and plan safe continuations after new contact events. Planners must do so within time and resource limits while respecting user priorities. We introduce HygieneRoboBench, with 624 instances across 134 task families, to evaluate safe resolution of household tasks from a given execution history. Tasks capture contamination through two grippers and shared objects, treatment costs, and user priorities. We combine controlled history, profile, and event comparisons with independent plan evaluation. These assess safe resolution, cost efficiency under user priorities, and responses to contact events. Evaluation of LLM-based and symbolic planners shows that safely completing a task does not guarantee the lowest execution costs u

---

### [135] ShanLiangRen: A Nutrition Agent for Personalized Daily Meal Planning

**链接**: https://arxiv.org/abs/2610.07886
**作者**: Miao Xie, Xiao Zhang, Yuan Wang, Ruixin Zhu, Chunli Lv
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dietary nutrition planning plays an important role in chronic disease management and maintaining a healthy body. In applications, it must simultaneously satisfy personalized constraints and reasonable multidimensional nutritional goals. These two aspects often conflict, and user constraints evolve with feedback, resulting in a substantial gap between generic guidelines and executable plans. To bridge this gap, we first propose the personalized fully quantified multiobjective dietary planning problem (MDP). To tackle MDP, we develop a nutrition agent, ShanLiangRen. The system first transforms dietary specifications, nutrient data, user attributes and natural language requirements into an individualized constrained planning instance. It then employs an exact retrieval-augmented generation method to shrink the feasible candidate set from a large scale ingredient and recipe space. Finally, it adopts a refinement guided by Pareto principles, where an LLM iteratively revises candidate plans 

---

### [136] Foresight-over-Graph: Reasoning Beyond Local Horizons for Knowledge Base Question Answering

**链接**: https://arxiv.org/abs/2610.08388
**作者**: Yang Hong, Yajun Yang, Xin Wang, Liping Jing, Qinghua Hu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have demonstrated strong capabilities in question answering, yet they still frequently suffer from hallucinations on knowledge-intensive tasks. Knowledge graphs (KGs) provide LLMs with structured, interpretable, and updatable factual grounding, making them a promising external knowledge source for reliable reasoning. However, existing LLM-guided graph reasoning methods typically rely on hop-wise greedy or beam-style pruning during evidence retrieval. Such local decision processes are inherently myopic: evidence that appears weak near the source may become crucial only after deeper graph context is explored, causing answer-critical branches to be discarded prematurely and making the reasoning chain difficult to recover. To address this limitation, we propose Foresight-over-Graph (FoG), a foresight-aware evidence retrieval framework for knowledge base question answering (KBQA). FoG iteratively constructs a question-relevant evidence subgraph and uses far-to-n

---

### [137] DAEDALUS: Bootstrapping Agent Memory from Self-Generated Tasks

**链接**: https://arxiv.org/abs/2610.08048
**作者**: Antoine Edy, Max Conti, Victor Xing, Marc-Antoine Allard, Nawfal Benhamdane, Gautier Viaud
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents often lack the operational knowledge to act reliably in new environments, as they must discover specific tool behaviors or environment conventions on their own. Without memory of past attempts, they repeat the same mistakes across tasks, leading to more task failures and longer trajectories. To address this, agentic systems typically rely on human-written guidelines or on procedural memory built from training tasks and an oracle verifier, both of which require prior knowledge of the environment. We present DAEDALUS, a method for bootstrapping reusable agent memory from self-generated practice without existing tasks or oracle verifiers. DAEDALUS pairs two agents: an explorer that interacts with the environment to generate challenging yet solvable tasks, and a solver that attempts them. A heuristic is derived from each solver failure and accepted only after the solver repeatedly succeeds with that heuristic in context. These outcomes also provide feedback for the explorer to r

---

### [138] How Learning Governs Unlearning across the Memorization-Generalization Spectrum

**链接**: https://arxiv.org/abs/2610.08577
**作者**: Hwiyeong Lee, Hyelim Lim, Ingyu Bang, Hoki Kim, Taeuk Kim
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While unlearning seeks to negate undesired capabilities acquired through learning, little research has examined how the way models learn shapes their subsequent unlearning. In this paper, we investigate this connection from the perspectives of memorization and generalization, the two most representative yet competing strategies that models employ during training. We first classify memorization- and generalization-heavy models using grokking in modular addition and compare their responses to unlearning, showing that the latter suffer greater retain damage, i.e., a larger performance drop on the retain set. Furthermore, we conduct a finer-grained analysis by introducing bucketed modular addition, in which the respective contributions of the two strategies can be explicitly controlled across the memorization-generalization spectrum. In this setup, we reaffirm that the same trend persists and is nearly monotonic. We further demonstrate that this relationship also holds in LLM unlearning ac

---

### [139] Same-Number Citation Swaps: Stress-Testing Jev as a Financial Evidence Judge

**链接**: https://arxiv.org/abs/2610.08675
**作者**: Chuhong Xu (Sofia University), Bo Su (Indiana University), Ziyao Chen (University of California, San Diego), Ruiyang Xu (Northeastern University), Shimeng Dai (Michigan State University) 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial reports repeat values across periods, metrics and accounting lines, allowing an LLM-generated calculation to be numerically correct while citing the wrong financial role. We evaluate what probabilistic evidence verification adds beyond number matching using Jev as a source-support verifier for GPT-4.1-mini calculation traces. A signed-number-at-pointer baseline explains most recovery over exact quotation checks. To isolate the remaining role-recognition problem, we hold operands and arithmetic fixed, move citations between same-number cells, and retain controls that express equivalent facts. These contrasts reveal both wrong-role citations that pass and valid alternative citations that are withheld. Explicit column labels improve selected wrong-role decisions while also lowering support for some equivalent evidence. A constructed follow-up on 36 new source pages, labeled by a non-author reviewer, extends this evaluation and exposes the same tradeoff between detecting role err

---

### [140] InterCorrect: Intersection-Aware Correction of Demographic Model Merging for Fair ASR

**链接**: https://arxiv.org/abs/2610.08604
**作者**: Ashley E. Bravo-Bravo, Yuchen Zhang, Haralambos Mouratidis, Ravi Shekhar, Monorama Swain
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic Speech Recognition (ASR) systems often show uneven performance across demographic groups, and errors can be especially difficult to address for speakers belonging to multiple demographic groups. This work studies demographic-aware model merging for fair Speech-LLM-based ASR. Starting from a SLAM-ASR-based model, we fine-tune only the connector on demographic-specific subsets and merge the resulting subgroup-adapted connectors into a global model. We then identify critical cross-axis demographic pairs using subgroup WER and task-vector conflict, and apply intersection-specific correction vectors to the global merged model. Experiments on Fair-Speech show that global demographic merging improves overall WER over the base model, while intersection correction provides additional gains for several merging strategies. In particular, TIES with WER-based correction achieves the best overall WER, reducing it from 7.38\% to 5.13\%. Subgroup and disparity analyses further show that the 

---

### [141] The Labeling Problem in Hallucination Detection Benchmarks: An Empirical Evaluation

**链接**: https://arxiv.org/abs/2610.08026
**作者**: Jorma Valjakka, Juhani Kivim\"aki, Juha Myll\"ari, Jukka K. Nurminen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, several methods for detecting when large language models (LLMs) hallucinate have been developed. These methods are often benchmarked with open-domain question answering (QA) datasets containing questions and corresponding short reference answers. First, an LLM is used to generate answers to questions within the QA dataset. Then, some automated labeling strategy is used to label these answers as hallucinated or not by comparing them with the reference answers in the dataset. This evaluation setting creates a methodological ambiguity between two criteria: reference faithfulness (whether the answer is fully supported by the reference) and factual correctness (whether the answer is free from contradictions and factually false specific claims). In practice, automated labelers may apply the former criterion even when the intended target is the latter. We study this potential criterion mismatch using 900 human-labeled question-answer pairs spanning three commonly used QA data

---

### [142] LLMOps at Scale: Reliability, Cost Governance, and Multi - Model Orchestration for Enterprise Generative AI Platforms

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11712652/&hl=zh-CN&sa=X&d=10898264445987078169&ei=Dd7FaoG5EN2qieoPk97tkAY&scisig=ACTRDVGC6lcDaBdPIPQxkcQK7M5w&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=0&folt=kw-top
**作者**: R Balaji - 2026 International Conference on Innovations in …, 2026
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The rapid adoption of large language models in production workflows has not been matched by equally rapid maturation in operational practice. Many organizations still treat LLM calls as isolated API invocations rather than as

---

### [143] Personal-Agent Mediated Recommendation with Cross-Platform User History

**链接**: https://arxiv.org/abs/2610.07588
**作者**: Yu Xia, Jiangfan Zhang, Jun Xiao, Julian McAuley, Xiangjun Fan
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern recommendation is shifting from platform-centric personalization toward user-governed personalization, where a personal LLM agent can act on the user's behalf across services. We formalize this emerging paradigm as Personal-Agent Mediated Recommendation: a platform recommender ranks a candidate set using platform-local information, and a personal agent uses user-authorized cross-platform history to mediate the resulting ranking and produce the final top-K slate. Such mediation is nontrivial: the platform ranking can encode strong population evidence that the personal agent cannot observe, so effective mediation must therefore balance beneficial rescues against harmful overrides. To study this trade-off, we introduce MediateRec, a benchmark that includes scalable proxy cross-platform environments and a real cross-platform test under a controlled platform-agent information boundary. To train the agent to use cross-platform history effectively, we further propose Personal Attributi

---

### [144] Agentic AutoRAG: RAG Pipeline Optimization through Reasoning-Driven Agents

**链接**: https://arxiv.org/abs/2610.08452
**作者**: Lasse B. Strand, Robert Jakob, Kevin O'Sullivan, Markus Kreft
**来源**: cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) is a widely used approach for grounding large language models (LLMs) in external knowledge. However, configuring a pipeline is an expensive hyperparameter optimization problem over many interacting choices, from chunking and embedding model to reranking and generation. Existing optimizers, from greedy search to Bayesian optimization, reduce each trial to an aggregate score and search without modeling why a configuration performed as it did, even though the retrieved chunks already provide evidence about whether each failure occurred during retrieval or after it. We introduce Agentic AutoRAG, an LLM-agent optimizer for multi-objective RAG hyperparameter optimization with retrieval-versus-generation failure attribution. It proposes configurations scored on a frozen exam from the corpus: after each trial a Diagnoser attributes each failed question to retrieval or generation, and a Proposer, grounded in a knowledge base of model rankings and pricing, se

---

### [145] Defense-in-Depth for LLMs: Evaluating Memory Gates Against Activation-Induced and Memory-Induced Sycophancy

**链接**: https://arxiv.org/abs/2610.07403
**作者**: Ritvij Sharma, Russell Dlugosz, Ryan Zhou, Maheep Chaudhary
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory allows Large Language Models (LLMs) to maintain personalized context across interactions, but retrieved user history can induce memory-induced sycophancy, causing models to favor stored user beliefs over objective evidence. Existing defenses primarily operate on retrieved context and are rarely evaluated jointly with internal behavioral bias. We introduce a $2 \times 2$ defense-in-depth framework separating internal activation steering from external memory handling. We extract sycophancy steering directions from 100 paired prompts and evaluate four open-weight models across 10 steering coefficients and five memory-defense configurations on MemSyco-Bench (answers for all 1,550 items; defense conditions judged on a fixed 250-item subsample), with three LLM judges. Three of the five configurations are new (rewriting every memory, a Router Gate that keeps, rewrites, or drops each memory, and dropping all memory); the other two are MemSyco's baselines. Selective Router Gate

---

### [146] COMPASS: Finding Where Reasoning Lives in Language Models

**链接**: https://arxiv.org/abs/2610.07469
**作者**: Pratyay Dutta, Kowshik Thopalli, Vivek Narayanaswamy
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Explicitly eliciting reasoning substantially improves LLM performance. Existing approaches require a predefined characterization of reasoning, whether through CoT prompt design, contrastive CoT directions, or via SAE derived reasoning features. For mathematical reasoning with verifiable answers, we show that a much simpler signal suffices, which is the correctness of the model's own direct answer attempts. This signal yields a latent direction that elicits reasoning. This direction is decodable within the activations of most attention heads, but only a small subset of them can be effectively intervened. We introduce COMPASS, an inference-time steering method that identifies these heads using a logit-space attribution score and steers their activations along the correctness direction, requiring only per-head activation statistics. Across three model families and multiple math benchmarks, COMPASS outperforms the activation-steering baselines we compare against, improves GSM8K accuracy by

---

### [147] Who Is Talking to the Agent? LLMs in Multi-User 3D Virtual Environments

**链接**: https://arxiv.org/abs/2610.07732
**作者**: Mohammad Al-Ratrout, Shayla Sharmin, and Roghayeh Leila Barmaki
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When several people share a 3D virtual room with an LLM agent, the agent must decide not only what to say, but whether an utterance was addressed to it and, if accessible, what profile information about the others present it may use. To study both problems, we construct LookAway, a controlled corpus of 40 sessions involving 80 distinct personas and an LLM agent (1,200 turns), including ambiguous-addressee turns in which speaker orientation agrees or conflicts with the intended addressee. Across three open-weight large language models and five conditions varying which profiles the agent sees and whether it is told where each person faces (18,000 decisions), adding speaker orientation increased addressee accuracy from 56% to 99.5% when orientation was congruent, but when the speaker faced someone other than the addressee, two of the models went by where the speaker faced on more than 85% of those turns. Warning one model that orientation could be misleading reduced this only modestly. A 

---

### [148] WorkflowOps: Learning Agent Collaboration Priors for Multi-Agent Workflow Orchestration

**链接**: https://arxiv.org/abs/2610.07860
**作者**: Qi Cheng, Shengyu Chen, Wei Cheng, Zhengzhang Chen, Xiaowei Jia, Haoyu Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems are increasingly deployed for complex knowledge work, yet their orchestration layers remain largely memoryless: each new task is decomposed, assigned, and executed from scratch with no benefit from prior successful executions. We present WorkflowOps, a multi-agent workflow orchestration framework that learns agent collaboration priors from historical workflows and expands its agent pool on demand to cover new capability requirements. Our approach introduces three coupled mechanisms. First, a transition probability matrix captures pairwise agent collaboration frequencies from past workflows and applies them as soft guidance during DAG workflow construction through intra-layer ordering optimization, probability-thresholded edge suggestion, and transitive reduction for parallelism maximization. Second, a sufficiency-driven agent creation loop detects capability gaps via semantic matching scores, generates specialized agents through an LLM, and simultaneously injects th

---

### [149] Incidental information contaminates patient notes and disrupts clinical reasoning in large language models

**链接**: https://arxiv.org/abs/2610.08585
**作者**: Krithik Vishwanath, Brandon Ye, Anton Alyakin, John E. Markert, Aaron Hsieh, Micha{\l} Ma\'nkowski 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly relied upon to support ambient documentation and clinical reasoning. Here we examine the impact of a failure mode shared between these two applications by assessing their sensitivity to information incidental to the patient encounter. In 576 patient-clinician dialogues, we found that frontier models inserted small-talk exchanges into 35% of notes, while mean quality scores changed by at most 0.20 points on five-point scales. In 3.7% of frontier notes, models misattributed the asides or used them clinically. In 57 mock recorded consultations, background speech from a separate patient encounter at -10 dB leaked into 48.2% of transcripts, with contamination detected in 5.3% of downstream notes generated by four open-weight models. We propose a dual encoding hypothesis of clinical reasoning and distraction in LLMs, with preliminary evidence that LLM components associated with disruption by incidental information also support clinical reasoning.

---

### [150] Trustworthy Method Comparison with AI Judges: Estimation and Design under Order, Batch, and Aggregation Effects

**链接**: https://arxiv.org/abs/2610.07755
**作者**: Tianxi Li, Jie Ding
**来源**: stat.ML cs.LG stat.AP stat.ME
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as judges for automated AI evaluation. A common practice is to randomize prompt sequences and average the resulting scores, but its statistical validity remains unclear. We show that LLM evaluation mechanisms can be approximated by a class of Markov generalized linear mixed models (GLMMs), supported by out-of-sample predictions across three major commercial LLMs. Using a first-order Markov GLMM, we study leaderboard ranking and group comparison. For leaderboard ranking, randomize-and-average selection is consistent under a mild separation condition, and a Williams square design can improve efficiency when item qualities are close. For group comparison, naive averaging can yield inconsistent conclusions about differences in group-level quality because of the response model's nonlinearity. Empirical results further support the validity of the proposed model-based inference beyond the first-order theory, including settings with higher-ord

---

### [151] Towards a Unified Misuse Monitoring Benchmark

**链接**: https://arxiv.org/abs/2610.07089
**作者**: Aniruddh Pramod, James Oldfield, Adel Bibi
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly act in multi-actor environments, exposing them to misuse from multiple sources: decomposition attacks, where a harmful request is split into innocuous sub-requests, and prompt injection attacks, where a compromised tool delivers a malicious instruction. Existing evaluations treat these threats separately and ask whether a trajectory is harmful, rather than when it becomes harmful. We propose monitoring the agent's responses, where its actions are externalised, and ask whether the first point where monitors identify harm lands within a harm window (from the agent's first harmful commitment to goal execution). We develop a unified formalism for trace-level misuse monitoring and use it to construct a benchmark of ~6,200 conversation transcripts between a user, an LLM agent, and the external environment, spanning both threats in a shared schema, with a labelled harm window, corresponding benign controls, and matched instances of refusals to these requests. Across 17

---

### [152] Verifying Coordination in Parallel Coding Agents: NP-Bench and a Scheduling Planner

**链接**: https://arxiv.org/abs/2610.07261
**作者**: Sumanyu Muku
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A team of coding agents can look fine agent by agent yet fail as a team: each passes its own tests while the merged result is broken, and single-agent evaluation never catches it. As teams run several LLM coding agents in parallel on one codebase, the agents collide: two rewrite the same function, one codes against a contract a teammate just changed, and integration fails after the work is done. Most coordination tools react (watch for a conflict, then warn), but at agent speed the warning arrives after the wasted edit. We recast the problem as scheduling: take each work item's declared scope, partition the work into disjoint scopes, and order merges along the producer->consumer graph, all up front. We build this planner into Nerveplane and evaluate it with NP-Bench, an environment-grounded three-arm benchmark (no coordination; reactive detection; proactive planning) that verifies integration off a real git merge, both in a deterministic simulation and with live agents. The planner lif

---

### [153] Natural Language Questions as an Interface for Knowledge Graphs: QRAKEN Graph Distillation and Semantic Self-Healing

**链接**: https://arxiv.org/abs/2610.08095
**作者**: Remo Grillo, Lukas Klic, Giovanni Colavizza
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language access to RDF knowledge graphs is a core Semantic Web ambition. Large language models (LLMs) have advanced Text-to-SPARQL, yet on unfamiliar graphs they often generate valid queries that misrepresent the populated data model. QRAKEN is a training-free, ontology-agnostic neurosymbolic pipeline grounding generation in empirical graph evidence rather than schema expectations. An offline distiller produces TTQL, a compact description of populated multi-hop patterns, conditional frequencies and path-conditioned literal examples, plus a class-property co-occurrence matrix. Online, TTQL guides the LLM, while deterministic syntax, vocabulary and data-model checks provide diagnostics for iterative refinement. On CK25 (First International Text2SPARQL Challenge), under matched-condition recomputation on a QLever snapshot, QRAKEN achieves strict F1 of 0.643 $\pm$ 0.026 with GPT-4.1 mini and 0.652 $\pm$ 0.012 with GPT-5.4: relative gains of 30% and 32% over the strongest recomputed

---

### [154] Turnslide: Scalable Multi-Turn Data Synthesis by Walking a Finite-State Machine

**链接**: https://arxiv.org/abs/2610.07070
**作者**: Aaron Fainman, Gabriela Kadlecov\'a, Maciej Gryka, Bartosz Kruszczy\'nski, Usman Zafar, C\'edric Archambeau 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small language models are inexpensive to serve and can run on private infrastructure, but base models are often not good enough at multi-turn tool calling, and fine-tuning them needs per-API data that rarely exists. Existing synthesis methods are too expensive for high-scale fine-tuning, as they often require mock operational environments for different domains and multiple LLM calls per generated conversation turn. We introduce a fully automated, lightweight synthesis framework that models each API as a finite-state machine, representing the system as abstract states that determine when each tool may be called, producing state-valid sequences of tools; sequences are translated into complete examples with a single LLM call. Rather than optimize diversity, we set a target distribution over the number of turns, the tool sequence and task complexity. We measure data quality by fine-tuning SLMs on generated trajectories, showing that our FSM-based generation significantly improves downstrea

---

### [155] Towards In-Parameter Memory Augmentation for Large Language Models

**链接**: https://arxiv.org/abs/2610.08630
**作者**: Haoyu Huang, Zhongwei Xie, Jiaxin Bai, Yisen Gao, Hong Ting Tsang, Wuganjing Song 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently Large Language Models (LLMs) and LLM-based agents increasingly need to incorporate knowledge acquired after pretraining, e.g., domain facts, user preferences, documents, and interaction experience. In-context learning (ICL) and ICL-based agent harness remain flexible, but they consume context capacity and incur repeated discretized encoding cost that grows with context length. \textbf{In-parameter memory} offers a complementary substrate: reusable memory information is represented in model parameters, adapters, or other parameter-like objects that are composed into the forward pass at inference time. This survey focuses on methods that augment LLMs with such parametric memory at deployment: a memory-bearing parameter object is plugged into the forward pass during inference, whether it is acquired before or during deployment. We organize the landscape with two orthogonal axes: \textbf{Parameter Placement}, which includes Embedding, Attention, FFN layers, or Hybrid when two or m

---

### [156] SquidAgent: Parallelize Wisely, Coordinate Efficiently

**链接**: https://arxiv.org/abs/2610.08647
**作者**: Yexiong Lin, Shanshan Ye, Yu Yao, Zhen Fang, Bo Han, Tongliang Liu
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents solve complex multi-step tasks, but sequential execution incurs substantial latency. In principle, parallelizing work across multiple agents should yield near-linear speedups. Yet existing parallel multi-agent systems often run slower than a single-agent baseline. We attribute this gap to two hidden costs that parallel execution incurs but a serial agent avoids. First, there is a re-exploration cost: redundant effort spent by parallel workers reconstructing context that the orchestrator already possesses, such as prior decisions, that would otherwise be inherited implicitly in a serial execution. Second, there is an alignment cost: the overhead required to reconcile inconsistencies across independently generated outputs. We thus derive a principled decision criterion: a layer should be parallelized only when its critical-path cost, plus re-exploration and alignment overheads, is lower than the corresponding serial cost. While this criterion is naturally expressed in wa

---

### [157] A Pedagogically Demonstrative Model Visualizing the Pathway from Online Interactions to Personalized Recommendation

**链接**: https://arxiv.org/abs/2610.07744
**作者**: Sushmita Khan, Connor Pennington, Bart P Knijnenburg
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personal digital activity increasingly shapes online experiences, yet few users have been educated regarding the processes transforming raw interactions into personalized suggestions. We developed an education artifact that illustratively simulates how AI leverages users' digital activities to shape online recommendations (e.g., ads). Our artifact processes users' digital activity using a locally-hosted LLM to generate user profiles of their inferred interests and personalized recommendations. A three-layered Sankey diagram maps data sources through inferred interests to personalized recommendations. Interactive filters enable users to explore how different combinations of data sources influence personalized outcomes. This paper describes the artifact and its educational value, and reports findings of a pilot think-aloud study with six young adults. We find that the artifact effectively taught participants the conceptual relationship between digital activities and personalized recommen

---

### [158] SENSE: State-aware Emotion Navigation Storytelling Engine

**链接**: https://arxiv.org/abs/2610.07666
**作者**: Yi Xia, Pablo Carrasco Velo, Mudit Paliwal, Ibrahim Khan, Yifan Geng, Mustafa Can Gursesli 等 (8 人)
**来源**: cs.HC cs.AI cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents SENSE, a state-aware framework for generating playable branching visual novels with multi-track emotional navigation. Integrating a state-based narrative architecture called MIND, a structure analyzer, and a path-aware context management module, SENSE produces narratives that are both structurally coherent and emotionally rich. From minimal high-level inputs, it generates multiple intersecting routes while preserving character consistency and narrative causality. Evaluations using LLM judges, affective metrics, and visual assessments indicate SENSE outperforms baselines in narrative diversity and robust asset integration, while preliminary human trials show directional improvements in emotional fidelity alongside comparable enjoyment.

---

### [159] ServeLearnBench: How Well Can Agents Self-Improve from Serving Experience?

**链接**: https://arxiv.org/abs/2610.07792
**作者**: Haizhong Zheng, Yizhuo Di, Ranajoy Sadhukhan, Shuowei Jin, Beidi Chen
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly deployed to perform complex tasks in real-world environments. However, the knowledge required for correct behavior in these environments is often implicit, undisclosed, and subject to change over time. Recent continual-learning harnesses seek to address this challenge by enabling agents to improve from serving experience. Yet the effectiveness and limitations of these methods are not yet well characterized. Existing benchmarks provide only partial coverage: some explicitly provide the target knowledge, others assume a static environment, and those that support continual adaptation remain limited in scale and knowledge diversity. To enable systematic evaluation, we formalize an evolving-environment streaming dataset (EESD), in which agents must infer, apply, and revise latent environment knowledge from interaction and outcome feedback as hidden policies evolve, and introduce ServeLearnBench, spanning retail support, banking, and sales-pitch g

---

### [160] How Well Do LLMs Reason with Noisy Evidence? An Active Visual Reasoning Benchmark

**链接**: https://arxiv.org/abs/2610.07751
**作者**: Bach Nguyen, Zhaonan Li, Mau Son Nguyen, Sanika Chavan, Nilay Kumar, Hong Anh Nguyen 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world reasoning rarely reduces to static question answering: agents must actively gather information from tools and sensors that are often noisy and unreliable. Yet most existing active reasoning benchmarks assume that environmental feedback is trustworthy, or introduce noise without exposing an explicit, calibrated uncertainty signal, leaving open how LLMs should reason when the evidence itself is uncertain. We introduce VisualNoiseQA, a novel benchmark for active reasoning under noisy visual feedback. A text-only LLM must solve VQA problems by iteratively querying a fixed, off-the-shelf VLM treated as a stochastic visual sensor. For each query, we draw multiple samples and expose an empirical uncertainty signal via self-consistency, enabling the reasoner to probe from different angles and decide what to ask next and when to stop. Our construction is automatic and scalable: starting from diverse VQA sources and two noisy VLMs, we retain only questions where the sensor is inconsis

---

### [161] Explore, Then Commit: Measurement-Efficient Scientific Law Discovery with Language Models

**链接**: https://arxiv.org/abs/2610.07620
**作者**: Kautik Mandve, Dileepa Fernando
**来源**: cs.AI cs.LG physics.comp-ph
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific law discovery requires selecting measurements and converting evidence into a governing equation. We evaluate an explore-then-commit protocol in which a large language model proposes hypotheses, a programmatic planner gathers measurements, and a fresh prompt synthesizes the final law from fixed observations. The protocol combines structured probes, automatic numerical diagnostics, restricted measurement batches, and optional interpreter access. Across 576 NewtonBench trials, we compare eight configurations on 12 physics modules using GPT-4.1-mini and a medium-difficulty GPT-4.1 replication. On medium tasks, interpreter-enabled planners use 8.6 versus 22.5 measurements per trial for GPT-4.1-mini and 8.9 versus 43.0 for GPT-4.1. Their mean magnitude-based root-mean-squared logarithmic error falls from 2.514 to 0.202 and from 0.626 to 0.149, respectively. An additional audit retains incomplete and invalid submissions in a coverage-sensitive analysis. Observed symbolic-accuracy g

---

### [162] Agentic Design Space Exploration for Joint Hardware Configuration Selection and Mapping of AI Inference Workloads on Heterogeneous Edge SoCs

**链接**: https://arxiv.org/abs/2610.07191
**作者**: Geetha Prasuna Yarramneni, Surya Selvam, Wilfried Haensch, Anand Raghunathan
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern edge Systems-on-Chip (SoCs) integrate heterogeneous processing units (PUs) such as CPUs, GPUs, and NPUs, each with distinct performance and energy characteristics. Deploying AI inference workloads on them under real-time latency and energy constraints requires jointly mapping workloads to PUs and configuring each PU (e.g., selecting the number of active cores and the operating frequency). This joint space grows combinatorially, making exhaustive search infeasible. Most prior work on design space exploration (DSE) applies black-box optimization (BBO) such as evolutionary search, where each evaluation returns only aggregate metrics such as latency and energy. Recent LLM-guided DSE relies on the same sparse feedback. We observe that this limits its efficiency: it offers no insight into the design space or the reasons a design choice performs the way it does, and it leaves the reasoning abilities of LLMs largely unused. We present TraceDSE, an agentic DSE flow that performs joint wo

---

### [163] Closing Ambient Clinical Documentation Gaps with Automated Provider Queries

**链接**: https://arxiv.org/abs/2610.07502
**作者**: Joseph Paul Cohen, Raj Shah, Han-Chin Shing, Fang Wang, Susan Nguyen, Chaitanya Shivade 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Provider queries are clarifying requests sent by clinical documentation specialists to physicians to close gaps in the clinical note and ensure accurate billing. Prior work automates note drafting, ICD-10 coding, and order extraction assuming a complete transcript, leaving these gaps unaddressed. We study whether an LLM can automate the query loop, termed DAU (Draft, Ask, Update), across those three tasks. An audit of 3,000 real visits identifies the sources of missing documentation, from which we build five transcript-degradation benchmarks on public data. Analyzing 21k clarification turns on real conversations, we find useful-question predictors are task-specific: oracle confidence dominates, but note completeness needs only simple recall questions while ICD-10 coding needs harder, multi-option ones. About 9% of turns hurt performance, driven by redundant questions and non-answers that still trigger a rewrite. Deployment depends on learning "when not" as much as "what to" ask.

---

### [164] HINTT Submission to the 2nd MLC-SLM Challenge: Comparing Cascaded and Unified Approaches to Diarization and ASR

**链接**: https://arxiv.org/abs/2610.08063
**作者**: Takanori Ashihara, Kohei Matsuura, Masato Mimura
**来源**: eess.AS cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents the HINTT system submitted to the 2nd Challenge and Workshop on Multilingual Conversational Speech Language Model (MLC-SLM). We address multilingual speaker-attributed ASR, where systems must determine who spoke when and what was spoken. We investigate two modeling strategies for this problem: a cascaded pipeline that combines speaker diarization with speech-LLM-based ASR, and a unified speech LLM that directly generates speaker labels, timestamps, and transcriptions. Our final submission is based on the cascaded pipeline, consisting of a fine-tuned DiariZen diarization model, a fine-tuned Qwen3-ASR model, and LLM-based generative error correction. For comparison, we also fine-tune VibeVoice-ASR as a unified model using the same official training data. All task-specific fine-tuning and model selection are performed using only the official MLC-SLM data, without external data or pseudo-labels. Experimental results demonstrate that the cascaded system remains more reli

---

### [165] Agentic RCA for Internet-Scale Services Using Constrained Creativity

**链接**: https://arxiv.org/abs/2610.08622
**作者**: Sayan Sinha, Vipul Harsh, B. Aditya Prakash, Vyas Sekar, Hui Zhang
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> System administrators of Internet-scale services need to resolve failure incidents to maintain reliability of such services. Ideally, we want a troubleshooting system to be: (1) expressive to known and unknown incidents with high accuracy; (2) cost efficient at scale; (3) explainable to provide actionable insights operators can act on; and (4) entail low effort from the operators. Unfortunately, most existing systems, including emerging LLM-assisted agentic workflows and structured frameworks for authoring diverse RCA algorithms fall short of achieving all four requirements. We present E4, a novel agentic system for troubleshooting for Internet-scale services. E4 embodies the paradigm of constrained creativity that combines the best of LLM-assisted automation and exploration with the explainability and efficiency of a structured approach. Instead of allowing an LLM agent to write arbitrary code or generate arbitrary responses, we provide the agent a restricted DSL to generate its respo

---

### [166] CueRator: Agentic Search for Symbolic Rules to Adapt Frozen Multimodal Encoders

**链接**: https://arxiv.org/abs/2610.07868
**作者**: Sunchan Park, Beomkwon Cho, Kyeongbo Kong
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents have been used to search over symbolic structures such as programs and equations. We propose CueRator, an agentic framework for policy-aware decision-rule discovery, which adapts frozen contrastive multimodal encoders by searching for the decision rule that converts their cross-modal similarities into predictions. We validate it on open-vocabulary audio-visual event perception, where existing methods involve a trade-off between adaptivity and generalization to unseen categories: trained modules adapt at the cost of generalization, and fixed rules the reverse. The framework pairs a symbolic formulation for generalization with a lightweight policy that predicts its parameters per video for adaptivity. A report-guided multi-agent loop discovers the formulation offline, evaluating each candidate on its expressive ceiling and on whether a trained policy can realize it. On OV-AVEBench, CueRator raises the total average from 57.8 to 60.2 and unseen-category perform

---

### [167] SkillPoison: Progressive Skill Poisoning via Successful Experiences

**链接**: https://arxiv.org/abs/2610.07645
**作者**: Lizhi Zhang, Xin He, Dianxuan Fu, Yuyuan Feng, Jiatong Li, Qi Wang 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving LLM agents increasingly distill successful experiences into persistent, reusable skills. Existing skill attack methods corrupt this learning pipeline by injecting malicious triggers, behaviors, or false facts into individual experiences or extracted skills. However, such attacks are easily detected, and the injected malicious behaviors often fail to accumulate as persistent skills. In this paper, we show that skill poisoning can arise even from verified successful experiences, without making any individual trajectory malicious. Based on this insight, we propose SkillPoison, a novel framework that progressively poisons skill via successful experiences. SkillPoison first constructs a set of successful experiences that reinforce a target behavior, and then removes the contextual conditions that constrain when the behavior applies. Rather than injecting malicious content, SkillPoison shapes how the skill extractor generalizes, allowing useful behavior to support task success

---

### [168] Understanding and Mitigating Inference-Time Overreliance Using Agentic Memory

**链接**: https://arxiv.org/abs/2610.07311
**作者**: Luoxi Tang, Yuqiao Meng, Nilesh Auradkar, Muchao Ye, Dazheng Zhang, Zhaohan Xi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic memory allows LLM agents to reuse past experience, yet retrieved memories can also distort inference even when they are benign, correctly stored, and appropriately retrieved. We study this failure mode, which we call memory over-reliance. Across benchmarks and memory architectures, we find that memory is useful when past experience transfers to the current task, but can become misleading when only part of the evidence transfers. Failures are strongest under partial query-memory overlap, a pattern further confirmed by controlled experiments thatvary the amount of overlapping evidence. Motivated by this finding, we propose MEMTRIM, a plug-and-play framework that indexes memory evidence at write time and controls its reuse at read time. MEMTRIM removes repeated or conflicting evidence while preserving useful memory-specific information, requires no retraining, and applies to both embedding-based and structured memory systems.Experiments show that MEMTRIM reduces memory overrelianc

---

### [169] Does On-Policy Distillation for Safety Pose Backdoor Risks?

**链接**: https://arxiv.org/abs/2610.07654
**作者**: Jian Luo, Kehan Qi, Qingqiao Hu, Meilong Xu, Jiacheng Qiu, Weimin Lyu 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation (OPD) has attracted growing attention as an effective way to transfer capabilities from teacher models to student models. Recent studies further explore OPD as a tool for improving large language model safety with promising results. However, these approaches typically assume that the teacher and training data are trustworthy. In this paper, we uncover an overlooked threat to OPD for safety: a safety-aligned but backdoored teacher can propagate its hidden malicious behavior to an initially clean student. Under our threat model, a poisoning rate as low as 3% results in an attack success rate (ASR) of up to 70% on the distilled student. We further identify two training choices that can amplify this risk. First, increasing the number of training epochs can lead to high ASR even at low poisoning rates. With only 10 poisoned samples, ASR reaches 67% after 16 epochs. Second, the commonly used top-k KL can accelerate backdoor transfer, causing trigger-conditioned harmful

---

### [170] DSV-Mem: Evaluating Multimodal Memory in Professional Workflows for MLLM Agents

**链接**: https://arxiv.org/abs/2610.08102
**作者**: Jike Zhong, Ritwick Chaudhry, Xuanbai Chen, Tianchen Zhao, Linghan Xu, Yifan Xing 等 (7 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational MLLM agents are increasingly expected to assist in professional workflows, from AI research and engineering design to product management and business operations. Yet this capability remains underexplored: existing benchmarks largely focus on informal, everyday interactions and personal-life scenarios featuring photographic natural images, isolated static artifacts, and recall-oriented questions. In contrast, professional scenarios often involve structured, information-heavy artifacts that undergo frequent revisions and authority updates, and compositional queries requiring reconciliation of many artifact versions while tracking state precisely. To address these challenges, we introduce DSV-Mem, a benchmark for evaluating Dense Stateful Visual Memory. DSV-Mem comprises expert-reviewed scenarios and 1,000 questions across five user-oriented categories (Current State, Past State, Derived State, Change History, and Conflict/Refusal). A Hartley-inspired criterion favors quest

---

### [171] Finding Highlight Images In Your Albums: From Benchmark to Agentic MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3Da-YQEgAAQBAJ%26oi%3Dfnd%26pg%3DPA381%26dq%3DMLLM%26ots%3D5A0xE5vDPU%26sig%3DuFrJH6O1mOJin60gUOtZdGhLJT0&hl=zh-CN&sa=X&d=6934039246955168317&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVFP046RtOqxZfa8QPDfb_n4&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=1&folt=kw-top
**作者**: R Qin, C Sun, Y Dong, Y Sun, C Ding, C Zhao 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To effectively leverage these priors, we propose Highlight4U, an agentic MLLM framework specifically aligned with human highlight selection behaviors to achieve accurate AHR. As illustrated in Fig. 5, the agentic workflow of Highlight4U operates

---

### [172] BoT-Feedback: Grounding Multimodal Reasoning in Biomechanical Evidence for Explainable Human Action Feedback

**链接**: https://arxiv.org/abs/2610.06972
**作者**: Xu Dong, Wanqing Li, Anthony Adeyemi-Ejeye, Andrew Gilbert
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have demonstrated impressive capabilities in visual understanding and multimodal reasoning, yet they remain fundamentally limited in Human Action Feedback Generation. Existing methods infer coaching feedback directly from visual observations, producing generic advice, limited interpretability, and physically implausible hallucinations. In contrast, expert human coaches diagnose performance through explicit biomechanical reasoning over joint kinematics, posture, and body dynamics. We introduce BoT-Feedback, a framework that grounds MLLM reasoning in structured biomechanical evidence. Our key contribution is Biomechanics of Thought (BoT), a four-stage reasoning framework that progressively identifies the action, localises the critical body regions, analyses quantitative biomechanical differences between expert and student performances, and synthesises interpretable coaching feedback. To support this reasoning process, we develop a plug-and-play Bi

---

### [173] Medical Image Alignment Assessment as a Test of Generalist Visual Reasoning in Frontier Multimodal Models

**链接**: https://arxiv.org/abs/2610.06896
**作者**: Ross Callaghan, Niannu Gao, Hojjat Azadbakht and Hui Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier multimodal large language models (MLLMs) are increasingly positioned as general purpose visual reasoners as part of the quest for artificial general intelligence. A key test of this generality is whether they can perform novel visual judgments that humans can make reliably from visual evidence and task instructions, without task-specific parameter optimisation. We investigate this question through the task of medical image alignment assessment, where the goal is to establish whether there is anatomical correspondence between two images. Human visual assessment of image alignment is still the gold standard and most common approach; however, it requires trained operators and is impractical to scale for large datasets. We evaluate recent generations of MLLMs on two exemplar medical image alignment tasks, varying both prompting strategies and image-presentation methods. We compare against a locally fine-tuned MLLM and a task-specific CNN to examine the trade-off between frontier g

---

### [174] with World Models for Situated Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DIeYQEgAAQBAJ%26oi%3Dfnd%26pg%3DPA213%26dq%3DMLLM%26ots%3DHlN4Oggp0B%26sig%3D7IzEeEkgW42nzLuQkpK-zvkTygs&hl=zh-CN&sa=X&d=8872431874739535621&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVG_BrbvkSBmgKFI9it-i6b2&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=6&folt=kw-top
**作者**: R Liu, Y Chen, Y Zhang, J Zheng, J Zhang, K Yang… - Computer Vision–ECCV … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> answer, we design a sequential framework that combines a world model and an MLLM for imagination and reasoning. We adopt leading world models in V-… To enable controlled camera motion, we use MLLM -driven prompt-extension scripts to

---

### [175] of Facial Expression Editing

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3Da-YQEgAAQBAJ%26oi%3Dfnd%26pg%3DPA288%26dq%3DMLLM%26ots%3D5A0xE5vDPU%26sig%3DDvbo4K0dFeV9reOqdagiQpm2ZOw&hl=zh-CN&sa=X&d=11983464648888064764&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVEph1dHqON__BCa4pN5CQgw&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=3&folt=kw-top
**作者**: F Xue¹, X Wu, H Sun, Y Shi, H Wang, J Xue 等 (10 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Inspired by VIEScore [17], we establish a robust MLLM -based scoring framework for our perceptual metrics. The subscore aggregation and normalization details, and prompt templates are provided in supplementary material. Specifically, we explicitly

---

### [176] Unsafe by Reciprocity: How Generation-Understanding Coupling Undermines Safety in Unified Multimodal

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3Db5gUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA132%26dq%3DMLLM%26ots%3D0ZOVEUecxl%26sig%3Dg9PzxacV3ZfNVL8sCOti8oKnq_E&hl=zh-CN&sa=X&d=4521297580006089499&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVE6m-AyZM8-GNommdz829my&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=5&folt=kw-top
**作者**: K Wang, H Huang - Computer Vision–ECCV 2026: 19th European …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> , and an MLLM -based safety judge, where higher scores indicate higher attack success. The Vanilla baseline already produces a non-trivial amount of unsafe content, especially on the Borderline and Explicit subsets. For instance, on Bagel the MLLM

---

### [177] for Visual Chain-of-Thought Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3D4vkUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA295%26dq%3DMLLM%26ots%3DtLATWxT1U6%26sig%3Dy-CQBNw6qToQIlQzO6dXZlN2iR0&hl=zh-CN&sa=X&d=6763623860691499164&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVHnl46UU_-Jf49EXG0TJczm&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=2&folt=kw-top
**作者**: L Li, X Gao, C Tang, X Yue, C Youl - Computer Vision–ECCV 2026: 19th European …
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Fine-tuning strong MLLM backbones on VisReason and VisReason-Pro yields substantial improvements in step-by-step visual reasoning accuracy, Rol localization, interpretability, and finegrained/spatial reasoning performance. These results

---

### [178] StAR: Segment Anything Reasoner

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DiZgUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA94%26dq%3DMLLM%26ots%3DoY5pyqKMSF%26sig%3DFhTuijVLmWKTXM0U05ohQVBWB9Q&hl=zh-CN&sa=X&d=6316784457402452754&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVF8JLfUOoAwR00_MO45AhAV&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=4&folt=kw-top
**作者**: C Cho, Y Ro - Computer Vision–ECCV 2026: 19th European …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> With this forward pipeline, we keep SAM 2 frozen and apply RLVR directly on the MLLM to … from VisionReasoner that evaluate the accuracy of the MLLM's predictions. Specifically, we use (i) a … Maintaining MLLM -level accuracy rewards

---

### [179] Kiroshi: An Agentic Perception System for High-Accuracy Image Parsing

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DLU8UEgAAQBAJ%26oi%3Dfnd%26pg%3DPA182%26dq%3DMLLM%26ots%3DLh3QrKY9M4%26sig%3D_F7R5hYyk0NcTksBL1wGWrIjRTI&hl=zh-CN&sa=X&d=16635717989219151298&ei=Dd7Fau7KFK6c6rQPvIa3gAo&scisig=ACTRDVHIBetRfbQDJeRdZqZ5tysr&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=0&folt=kw-top
**作者**: X Lu, J Ma - Computer Vision–ECCV 2026: 19th European …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In Stage I, we train an Action Model for mask prediction and fine-tune an MLLM to perceive grid-level visual details. In Stage II, we apply DPO to teach the MLLM to generate more accurate and semantically aligned grid prompts, which then guide

---

### [180] Surrogate-Driven Multi-Objective SMEPO Framework for Optimal EEG Channel and Feature Selection in Motor Imagery BCI

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s44196-026-01602-7&hl=zh-CN&sa=X&d=5758181492513305801&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVFTivtbPHDYPuhKH1hUkCvI&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=7&folt=kw-top
**作者**: AK Shukla, S Dwivedi, NK Dewangan - International Journal of Computational …, 2026
**匹配关键词**: EEG, BCI, Motor Imagery
**相关性评分**: 11.0
**数据来源**: Google Scholar

**摘要**:

> the effective selection of EEG channels due to the non-stationary, high-dimensional, and subject-specific nature of EEG data. Consequently… -Objective SMEPO (Emperor Penguin Optimiser) algorithm for efficient EEG channel selection in MI-BCIs. SMEPO

---

### [181] Benchmarking Label-Revealed Online Updates for EEG BCI Decoding

**链接**: https://arxiv.org/abs/2610.07420
**作者**: Bogdan Kozyrskiy, Artem Grachev, Abraham I. Camelo Guerrero
**来源**: cs.LG eess.SP
**匹配关键词**: EEG, BCI, Brain-Computer Interface
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) signals drift over time, which can cause static brain-computer interface (BCI) models to degrade in practice. We present a benchmark for online adaptation and compare two widely used pipeline families, Common Spatial Patterns (CSP) and Riemannian covariance-based methods, under time-ordered prequential (test-then-train) evaluation. We examine (i) which pipelines benefit most from label-revealed updates, (ii) whether controlled forgetting of older data improves robustness, and (iii) how a minimal-calibration cold start compares with starting from a pretrained model. Across four datasets (three motor-imagery datasets and one movement-decoding dataset), label-revealed online updates improve 13 of 14 model/dataset pairs on the two largest streams, with relative accuracy gains of up to about 18% over a frozen model. A Shapley-based data-valuation analysis over temporal blocks assigns the largest mean value to the most recent block in each of the three analyzed d

---

### [182] SpecBraM: What Should an EEG Foundation Model Predict? Masked Band-Power Prediction versus Waveform Reconstruction

**链接**: https://arxiv.org/abs/2610.07484
**作者**: Peng Xie, Yequan Bie, Jianda Mao, Kani Chen
**来源**: cs.LG
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised EEG models often reconstruct masked waveforms or predict discrete codes. We study a task-aligned alternative: masked band-power prediction (MBP), which predicts fixed narrow-band log spectral energy for masked channel-time patches. This target retains rhythm power relevant to sleep staging while avoiding phase-sensitive waveform reconstruction and a learned codebook. Across three pretraining seeds, we compare band-power and waveform targets with matched backbones, pretraining data (2,388 hours), and training steps, including a 2x2 tokenizer-by-target design. On ISRUC and HMC sleep staging, MBP exceeds raw- and band-waveform reconstruction by 1.6-2.8 balanced-accuracy points with all labels and 4.7-7.3 points with 1% of labels under a strict linear probe; the target effect exceeds the tokenizer effect. Its frozen features reach 0.7916/0.7425 balanced accuracy, versus 0.7636/0.7227 for a matched rich handcrafted spectral baseline, although the gap is about one point with 

---

### [183] The use of low-density EEG for

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3D8PkQEgAAQBAJ%26oi%3Dfnd%26pg%3DPA22%26dq%3DEEG%26ots%3DgMto_JWJPD%26sig%3DtcslrhCH5kC7jdb3EQf9Mk7kgb8&hl=zh-CN&sa=X&d=15443901074408261478&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVE4TTQaOTno1kj7DDtiK-h8&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=0&folt=kw-top
**作者**: CU Onyike, A Hillis¹, PD Bamidis - Modern applications ofEEGin neurological and …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Objective: Dissociating Primary Progressive Aphasia (PPA) from Mild Cognitive Impairment (MCI) is an important, yet challenging task. Given the need forlow-cost and time-efficient classification, we used low-density electroencephalography ( EEG )

---

### [184] Graph-Theoretical Approach to EEG Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3Dp5gUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA29%26dq%3DEEG%26ots%3DKmpvzga5cf%26sig%3DNiNOD9ig8if4nSeILxnYF_i4V5w&hl=zh-CN&sa=X&d=7756044876370898476&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVFz5tFyRHWoo1eRchlXRC92&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=1&folt=kw-top
**作者**: G Piermaria, S Pelle, A Scarabello, L Ferri - … of the XVII Mediterranean Conference on …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Epilepsy is a neurological disorder characterized by excessive neuronal activity. Accurate identification of epileptogenic zones is essential for presurgical evaluation in drug-resistant focal epilepsy. In this study, we propose a framework that combines

---

### [185] Pratique de l' EEG Book• 2008

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/book/monograph/9782294086229/pratique-de-leeg&hl=zh-CN&sa=X&d=11525913195075992104&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVGQuN_Yg1p6GaAbtGr6VOJO&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=8&folt=kw-top
**作者**: J Vion-Dury, F Blanquet
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> En effet, tant sur le plan de la technique que sur ceux de la pratique et des indications, l' EEG a évolué ces dernières années. Ainsi, sont étudiés les aspects de l' EEG normal puis les variations pathologiques et leurs interprétations, ainsi que les

---

### [186] Snapshot-Based Seizure Prediction in Pediatric EEG Using Deep Neural

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DzU4UEgAAQBAJ%26oi%3Dfnd%26pg%3DPA213%26dq%3DEEG%26ots%3DnHn3zGFpdF%26sig%3DtB_w9eXnSpz2p4Btq_V9Vy5J8_w&hl=zh-CN&sa=X&d=14778437375357192083&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVG-J89lZUGV2TH1Bu50EbRr&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=5&folt=kw-top
**作者**: T Ruga, L Garg, E Zumpano - 26th International Society for Design and Process …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this context, the electroencephalogram ( EEG ) represents a fundamental tool for monitoring brain activity, enabling the identification of … (LSTM) and Bidirectional-LSTM (Bi-LSTM), to analyze temporal sequences of EEG signals ([2–4]). Other approaches

---

### [187] Mental Fatigue Preserves the Balance Between Alpha-Band EEG Connectivity and Small-Worldness in Resting

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3Dp5gUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA451%26dq%3DEEG%26ots%3DKmpvzga5cf%26sig%3D0lciOOknKKi0FsbgFpIqzEUKOTA&hl=zh-CN&sa=X&d=8231878936292547632&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVGRfFEJkDGIwiK0NFVRneMm&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=6&folt=kw-top
**作者**: M Hanni, L Päeske, K Kreegipuu, A Dadatskaja - … September 14–17, 2026, Siena 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> A negative correlation between EEG functional connectivity (FC) and small-worldness (SW) in the alpha band has been previously reported. The aim of the present study was to examine whether this correlation is preserved in the resting-state following

---

### [188] A Wearable Closed-Loop EEG -Guided Mindfulness System for Chronic Tinnitus

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DmxcSEgAAQBAJ%26oi%3Dfnd%26pg%3DPA103%26dq%3DEEG%26ots%3DwP-nPAsFSF%26sig%3DnjfZr_mZOlDP9VfEIG_wDjhnKcw&hl=zh-CN&sa=X&d=7733589961065094111&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVFAov7WGI2Ydp_79jZncxeA&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=4&folt=kw-top
**作者**: X Bao, M Gao, X Feng, Y Liang, Z Li, K Jin 等 (9 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Chronic tinnitus is commonly accompanied by sleep disturbance, emo-tional distress, and impaired attentional regulation, yet effective non-pharmacological interventions remain limited. We developed a wearable closed-loop EEG -guided mindfulness

---

### [189] M/ EEG Task Classification by Means of Brain Dynamic Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DmxcSEgAAQBAJ%26oi%3Dfnd%26pg%3DPA303%26dq%3DEEG%26ots%3DwP-nPAsFSF%26sig%3DLWEL6ogTxr9yuJ_m7hgB0ly_Eo8&hl=zh-CN&sa=X&d=3403209302798700240&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVGx327w9Eim4_DhzbbOBl2N&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=2&folt=kw-top
**作者**: GCM Ambrosanio, F Baselice - … Computational Approaches: Proceedings of the XVII …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study focuses on a feature extraction algorithm based on the analysis of dynamic spectral components of magnetoencephalography (MEG) and electroencephalography ( EEG ) data. During its activity, the brain produces

---

### [190] Effect of EEG Reference Montage on Higuchi's Fractal Dimension Estimates for Discriminating Depression

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3Dp5gUEgAAQBAJ%26oi%3Dfnd%26pg%3DPA43%26dq%3DEEG%26ots%3DKmpvzga5cf%26sig%3DFVRV9lLOxMUIE18amgulCuhwuJ0&hl=zh-CN&sa=X&d=16302909080927333987&ei=Dd7FaqqSDNe46rQPmoOZiAE&scisig=ACTRDVGiDHYugKnJVdqwlgDRAiVv&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=3&folt=kw-top
**作者**: M Bachmann - … Computational Approaches: Proceedings of the XVII …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Electroencephalography ( EEG ) signals exhibit complex, nonlinear dynamics that can be characterized using nonlinear measures … of EEG reference montage on HFD estimates and assesses their ability to differentiate depressive and

---

### [191] RPA: Residual Patch-Token Adapter for Image Retrieval from EEG and MEG

**链接**: https://arxiv.org/abs/2609.31698
**作者**: Yuhui Jin, and Yonghao Song, and Bingchuan Liu
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [192] CANDLE: Cortical Null-Space Decomposition for Noninvasive Brain Source Imaging

**链接**: https://arxiv.org/abs/2610.07824
**作者**: Shuntaro Suzuki, Yuiga Wada, Komei Sugiura
**来源**: cs.LG eess.SP q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electrophysiological source imaging (ESI) aims to estimate cortical source activity from noninvasive electrophysiological measurements such as electroencephalogram (EEG). However, ESI is fundamentally ill-posed because source activity is substantially higher-dimensional than sensor observations, resulting in non-unique solutions. Recent learning-based approaches address this ambiguity by learning data-driven source priors, yet they often struggle to generalize across subject-specific cortical geometries. To address this, we propose CANDLE, a learning-based ESI model that estimates source activity on subject-specific cortical geometries. CANDLE learns a prior over the null space induced by the source-to-sensor mapping derived from T1-weighted MRI, restricting learning to unobservable source components while preserving geometric constraints. To train CANDLE, we develop a whole-brain simulator spanning over 1,100 subject-specific cortical geometries with source configurations derived from

---

### [193] Sensor Geometry as a Flow-Matching Prior for Multi-Channel Brain Signals

**链接**: https://arxiv.org/abs/2610.08355
**作者**: Jaedong Hwang
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Flow-matching models start from an isotropic Gaussian source, the standard choice when the correlation structure of the data is unknown in advance. For multi-channel brain recordings, however, part of this structure is known in advance. Electrodes sit at fixed positions on the head, and volume conduction through the skull and scalp makes nearby electrodes co-vary in a way that is shared across subjects. Existing EEG generative models nonetheless leave the network to learn this from scratch. We put this structure into the source instead. From the sensor coordinates alone, we build a k-nearest-neighbor graph and take a graph-Mat\'ern function of its Laplacian as the source covariance, so the flow starts from spatially coherent patterns rather than channel-independent noise. The change adds no learned parameters, works with any coupling and any drift network, and uses the same three hyperparameters on every dataset. Across eight EEG datasets and four flow-matching methods, the graph-Mat\'

---

### [194] The Standardization Trap: Certifying Joint Label Processing in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.08314
**作者**: Duong Nguyen, Nicolas Chesneau, and Milan Bhan
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linear regression and kernel smoothing offer tractable explanations of in-context learning: in both, the features determine the weight assigned to each context label. However, whether this fixed-weight account describes pretrained tabular foundation models (TFMs) remains unclear. Testing this account using derivatives runs into a standardization trap: public TFM packages standardize the labels before the model sees them, yet ordinary derivatives also reflect behavior outside the set of standardized labels, making a model appear nonlinear even when every prediction it makes agrees with a fixed-weight map. We propose two certificates that depend only on predictions at standardized labels and can reject two distinct explanations: fixed-weight prediction and sums of independent nonlinear label transformations. Across the five public TFMs that we evaluate, our certificates show that changing one context label alters how other labels influence the prediction, a behavior we call joint process

---

### [195] Benchmarking Time Series Foundation Models for Load Forecasting Under Covariate Uncertainty

**链接**: https://arxiv.org/abs/2610.07232
**作者**: Tomas Kaljevic, Ivan Arzola, Yu Zhang
**来源**: cs.LG cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate short-term load forecasting (STLF) is essential for the reliable and efficient operation of modern power systems. While time series foundation models (TSFMs) have recently demonstrated remarkable performance across a wide range of forecasting tasks, their effectiveness for STLF under realistic operational conditions remains largely unexplored. In this paper, we present a comprehensive benchmark of four trained-from-scratch (TFS) models and four TSFMs across three real-world load forecasting datasets under operational scenarios that differ in the availability and quality of future covariate information. Our results show that Chronos-2 consistently achieves state-of-the-art performance in both zero-shot and fine-tuned settings when future covariates are available or accurately forecast. However, its performance degrades as covariate forecasts become increasingly noisy, whereas TimesNet exhibits greater robustness under severe covariate uncertainty. These findings demonstrate the

---

### [196] Scale-Invariant Training for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.07324
**作者**: Ignacy Stepka, Willa Potosnak, Kin G. Olivares, Artur Dubrawski
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) are trained on large collections of time series datasets that span various morphologies and domains. This setting exposes models to series whose scales -- typical magnitudes of their values -- can differ substantially. Affine scaling methods such as Reversible Instance Normalization (ReVIN) scale model inputs and reverse the transform before computing the loss. We show that this inversion multiplies each series' gradient by $b^p$ relative to loss on scaled targets, where $b$ is the scaling denominator (e.g., standard deviation) and $p$ is the loss degree. We call this scale-contaminated training (ScaleCon), because the scale of each series consequently becomes an importance weight, causing high-scale series to dominate training. For any scale-equivariant scaler and residual loss that is homogeneous of degree $p$, including MSE, MAE, and Quantile Loss, we prove that computing loss on scaled targets makes every mini-batch gradient and, consequently, 

---

### [197] Attenuated in-context identification in time-series foundation models: diagnosis under counterfactual inputs and repair by synthetic forced-system fine-tuning

**链接**: https://arxiv.org/abs/2610.08118
**作者**: Hong-In Won
**来源**: cs.LG cs.SY eess.SY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Covariate-aware time-series foundation models (TSFMs) promise training-free what-if answers for instrumented plants: the change in output that a different future input would cause. We test this on forced engineering systems with exact counterfactuals, comparing Chronos-2, TimesFM-2.5 and TabPFN-TS with classical system identification fitted to the same context. Through their default covariate interfaces, TimesFM-2.5 and TabPFN-TS are memoryless: the predicted effect of an input change is a same-time function of that change ($R^2 = 1.000$ for TimesFM-2.5). Chronos-2 identifies dynamics in context but attenuates them. Its predicted effect is 0.33-0.80 of the true effect, its recovered impulse response has the wrong shape, and its error on a one-degree-of-freedom oscillator levels off at 0.57 with 8192 context samples, where ARX fitted to 256 samples reaches 0.02. Context dither at inference lowers the what-if error on all six synthetic classes without training. A 26-minute fine-tune on s

---

### [198] Evaluation of Active Feature Acquisition Policies with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.07406
**作者**: Yuta Kobayashi, Divyam Madaan, Shalmali Joshi
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Active feature acquisition learns policies that sequentially acquire features to maximize information about a target variable. We study how to learn and evaluate such policies from finite offline data using prior-data fitted networks (PFNs), which are off-the-shelf models that output posterior predictive distributions without task-specific training. We show that under the imbalanced coverage of offline data, using total predictive entropy as a reward creates an epistemic bias that penalizes acquiring sparsely observed features. Specifically, this reward conflates epistemic uncertainty (arising from lack of offline data) with aleatoric uncertainty (arising from uninformative features). To address this, we target the posterior expected (aleatoric) entropy instead of the total predictive entropy output by a PFN for evaluating feature acquisitions. Empirical evaluations on synthetic and real-world datasets demonstrate that our approach consistently reduces value estimation bias and yields 

---

### [199] Valid for Free: Homophily-Gated Conformal Prediction for Training-Free Node Classification with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.08564
**作者**: Nguyen Duy Long, Phung Minh Hien, Nguyen Trong Viet, Nguyen Thai Anh
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) can classify the nodes of a graph without training on it, by reading node and neighborhood features as table rows next to labeled context rows. Work in this line reports predictive performance, not conformal coverage or prediction-set size. To our knowledge, we give the first reliability study of the setting, with TabICL as the TFM and half of each graph as labeled context. As for any predictor fixed before calibration, a frozen in-context predictor makes split conformal prediction exactly valid in finite samples, with no training, validation fold, or tuning on the target graph. An audit across ten graphs then shows that the training-free TabICL posterior has lower expected calibration error (ECE) than GCN with temperature scaling (GCN+TS) on nine of them. Its mean ECE over the ten graphs is 0.019, about 35 percent below the 0.029 of GCN+TS. We also introduce HG-DAPS, a training-free diffusion score whose homophily gate reads only the in-context labels,

---

### [200] CrystalJev: thinking fast and slow with atomistic foundation models for materials discovery

**链接**: https://arxiv.org/abs/2610.06985
**作者**: Peng Kang, Zhen Li, Yu Liu, Lei Zheng, Huibin Xu
**来源**: cond-mat.mtrl-sci cs.AI physics.comp-ph
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Atomistic foundation models triage millions of hypothetical materials but are used as slow simulators, their thresholded energies taken at face value. They are better read as fast decision-makers. CrystalJev queries a frozen interatomic potential once per unrelaxed structure and answers typed questions with calibrated probabilities, finite-sample guarantees and a rule for when to think slowly. Across 65 Matbench Discovery models, a 'stable' call is a probability in disguise, explained by a model's errors and the candidate population. Once trained, one forward pass decides nearly as well as a relaxation at a thirtieth of its cost, and a value-of-information theory sends slower computation only where decisions can change. The same layer answers electronic, mechanical and molecular questions. In a registered prospective test with 700 new density-functional calculations, single-pass forecasts calibrated only on existing data over-stated the stable fraction of unseen candidates (5.8%) by at

---

### [201] Beyond Training from Scratch: Foundation Models for Data-Efficient and Generalizable Cardiac MRI Reconstruction

**链接**: https://arxiv.org/abs/2610.08109
**作者**: Anam Hashmi, Mayug Maniparambil, Julia Dietlmeier, Kathleen M. Curran, Noel E. O'Connor
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cardiac magnetic resonance imaging reconstruction aims to recover high-quality images from undersampled acquisitions, enabling faster scans while preserving diagnostic fidelity. Recent reconstruction methods are typically trained from scratch and often require large amounts of task-specific data, limiting their robustness under data scarcity and distribution shifts. In this work, we investigate whether pretrained vision foundation models can serve as effective priors for accelerated cardiac MRI reconstruction. We propose a reconstruction framework that integrates frozen and parameter-efficiently adapted visual encoders, including CLIP, BiomedCLIP, and DINOv2, within a transformer-based reconstruction architecture. Extensive experiments on the CMRxRecon2023 and CMRxRecon2024 benchmarks demonstrate that pretrained representations consistently outperform a transformer trained from scratch across multiple acceleration factors. We further evaluate performance under limited supervision and c

---

### [202] VisionWeave: Weaving Elastic Visual Representations as a Native Capability of MLLMs

**链接**: https://arxiv.org/abs/2610.07987
**作者**: Yuan Feng and Qize Yang and Ruizhe Chen and Sibo Song and Haolin He and Muzhi Zhu and Zihan Liu and Yunfei Chu and Xize Cheng and Yuxuan Wang and Jin Xu and Xike Xie
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models have become the dominant paradigm for visual understanding, but incur substantial costs by encoding inputs into dense, fixed-size patch tokens. However, visual information is unevenly distributed: some regions require fine-grained detail, while others admit compact representations. Downsampling sacrifices this detail, while existing token pruning and adaptive approaches remain limited in content-adaptive granularity, task generalization, and integration with modern MLLMs and serving infrastructure. Overcoming these limitations calls for foundation models that learn, end to end, where-and at what granularity-to allocate visual representations, a native capability we term elastic visual representation weaving. We introduce VisionWeave, establishing this capability in frontier-level MLLMs through large-scale training. It combines two components: a gated spatial pooler constructs coarse-grained representations alongside native fine-grained representations w

---

### [203] MoonGS: High-quality Representation of the Lunar Surface via Gaussian Splatting Using Robust Depth Features from Image Pairs

**链接**: https://arxiv.org/abs/2610.07110
**作者**: Yun Jiang, Bo Zheng, Yingying Zhang, Xueming Xiao, Tao Hu, Hutao Cui 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-quality 3D reconstruction of lunar terrain from sparse rover images is indispensable for autonomous lunar exploration, but remains challenging because viewpoint overlap is insufficient, surface textures are weak, and data volume is limited. We propose MoonGS, the first feed-forward 3D Gaussian Splatting framework tailored to lunar scenes. Given only two input images, MoonGS predicts pixel-aligned Gaussian primitives in a single forward pass and renders photorealistic novel views without any per-scene optimization. MoonGS (i) adopts an adaptable backbone design that seamlessly integrates advanced vision foundation models to extract robust depth features; (ii) integrates semantic priors in two manners: merging semantic cues with visual features to refine Gaussian parameter estimation, and adopting a semantic ranking loss that regularizes background depth; and (iii) employs an entropy-guided heuristic resampling strategy to augment sparse observations by selecting the most informativ

---

### [204] GeneICL: A Tabular Foundation Model for Bulk Transcriptomics

**链接**: https://arxiv.org/abs/2610.08694
**作者**: Michael Bohl, Alexander Theus, David Wissel, Valentina Boeva
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Gene expression is widely measured in biomedicine, yet clinical outcome prediction remains challenging due to high dimensionality, strong feature correlations, and limited labeled data. Large self-supervised transcriptomic foundation models often fail to outperform simple supervised baselines. Tabular foundation models offer an alternative through in-context learning, but are typically pretrained on generic synthetic data rather than transcriptomic structure. We ask whether transcriptomics-aware pretraining, rather than scale, is the missing ingredient. Towards this end, we introduce GeneICL, a 4.2M-parameter tabular foundation model combining a semi-synthetic pretraining prior built from measured bulk expression profiles with a parameter-efficient recurrent architecture. We further enable right-censored survival prediction via a training-free reduction to regression using Cox partial-likelihood residuals. We evaluate GeneICL on 80 clinical outcome-prediction tasks spanning classificat

---

### [205] TICDA: Tabular In-Context Data Attribution

**链接**: https://arxiv.org/abs/2610.07996
**作者**: Yacine Benihaddadene, Milan Bhan, Eliot Dugelay, Mohammed Jawhar, Benjamin Wong, Nicolas Chesneau 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) achieve strong predictive performance by conditioning on labeled demonstrations provided in context, without any parameter update. Yet how individual demonstrations shape a given prediction remains poorly understood. This gap matters in practice: the context is often assembled from whatever labeled data is available, potentially leading to the inclusion of mislabeled, redundant, or low-quality examples that degrade performance. Standard data attribution methods do not transfer to the TFM setting: resampling-based approaches such as DemoShapley require a combinatorial number of forward passes, and gradient-based estimators such as influence functions require computing training point's effect on the model parameters, which in-context learning never updates. We introduce TICDA, a method that measures the influence of every demonstration in the context directly from linear surrogates trained on TFM latent embeddings, in a single forward pass and at negligib

---

### [206] Adversarially Trained Linear Transformers Are Optimal Robust In-Context Learners for Gaussian Mixtures

**链接**: https://arxiv.org/abs/2610.07754
**作者**: Soichiro Kumano
**来源**: cs.LG cs.CV stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adversarial training is one of the most reliable defenses against adversarial attacks, but its high computational cost must generally be paid anew for each task. Robust foundation models offer a promising alternative: adversarially pretrain a model once and then transfer its robustness to downstream tasks through lightweight adaptation. However, a fundamental question remains open: can robustness acquired during pretraining transfer to unseen tasks without further adversarial training? In this study, we answer this question affirmatively. A single model adversarially pretrained at scale can achieve optimal robustness on new tasks without additional task-specific training. Specifically, we show that, for a family of Gaussian-mixture classification tasks, a sufficiently deep linear transformer adversarially trained across tasks can asymptotically attain the robust Bayes error on previously unseen tasks through in-context learning from clean demonstrations. By contrast, a standardly train

---

### [207] MS-ECG-FM: Towards a More Universal Electrocardiogram Foundation Model for Health Monitoring using Multi-source Contrastive Learning

**链接**: https://arxiv.org/abs/2610.07662
**作者**: Robert A. Lewis, I-Min Chiu, Kyle Verrier, Karthik Jayaraman Raghuram, Francoise Marvel, Salar Abbaspourazad 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electrocardiography (ECG) records the electrical activity of the heart, aiding diagnosis by detecting abnormalities in cardiac function. ECG foundation models have demonstrated promising results, but are limited by a reliance on ECG interpretation reports as their sole supervision. Because interpretation reports only capture the subset of waveform information routinely recognized by clinicians, this constrains representation learning to overlook the broader diagnostic signals present in ECG. We introduce a new ECG foundation model --- MS-ECG-FM --- that is trained through contrastive alignment to multiple distinct clinical note types, including ECG, echocardiography, radiology, and discharge reports. We evaluate MS-ECG-FM on an extended set of ECG detection benchmarks, showing that it comprehensively outperforms existing methods on the full span of conditions that ECG can detect, including in reduced-lead configurations. Different reports improve representations for different diagnosti

---

### [208] 4D-HOF: Hand-Object Flow Matching for Feed-Forward 4D Interaction Reconstruction

**链接**: https://arxiv.org/abs/2610.08782
**作者**: Shiqi Li, Sean Cho, Yijie Li, Fengzhi Guo, Bowen Wen, Cheng Zhang
**来源**: cs.CV cs.AI cs.GR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing methods for 4D hand-object reconstruction often rely on costly per-sequence optimization, while generative approaches typically synthesize interactions from random noise, which can lead to unstable interaction prediction. We introduce 4D-HOF, a feed-forward framework that reconstructs 4D hand-object interactions from coarse but informative estimates produced by vision foundation models. Concretely, we learn a conditional flow matching model that transports foundation-model-derived hand-object states toward an interaction manifold, allowing the model to correct errors in translation, rotation, and alignment in a feed-forward manner. A key advantage of our generative formulation is that it naturally enables test-time guidance within the transport process. Rather than applying a separate post-hoc optimization after reconstruction, we directly steer the evolving generative states using physical interaction constraints and observed 2D evidence, allowing the reconstruction to be ref

---

### [209] QiYao-I: A Manifold Based Foundation Model for Irregular Multivariate Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.06936
**作者**: Linfeng Wang, Ruitong Zhang, Kai Zhao, Yang Shu, Zhongwen Rao, Meng Wang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Irregular multivariate time series forecasting is a challenging yet important problem in real-world applications, where observations are often irregularly sampled and asynchronously recorded across variables. Existing time series foundation models are mostly built on regularly sampled sequences, making them difficult to generalize to irregular time intervals and asynchronous cross-variable dependencies. To address these challenges, we propose QiYao-I, a manifold based foundation model for irregular multivariate time series forecasting. Specifically, we introduce a novel sampling-conditioned temporal manifold attention mechanism that maps real timestamps into a learnable temporal manifold feature space and injects temporal manifold biases into attention layers, enabling the model to capture both irregular time intervals and local sampling structures. Further, we propose a dynamic variable interaction mechanism with frequency awareness. It selectively performs cross-variable message pass

---

### [210] ProximalFM: Amortized Proximal Causal Inference under Hidden Confounding

**链接**: https://arxiv.org/abs/2610.08078
**作者**: Christophe Muller, Ayub Kharel, Alex Luedtke, Chan Park, Eric Tchetgen Tchetgen, Juan L. Gamella 等 (9 人)
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard causal identification methods often assume no unmeasured confounding and can fail when relevant confounders are unobserved. Proximal causal inference instead uses proxy variables to identify effects under hidden confounding. However, nonparametric proximal estimation can be challenging in practice: recovering causal estimands such as the conditional average treatment effect (CATE) requires solving an ill-posed integral equation that is data-hungry, hyperparameter-sensitive, and optimization-unstable. Bayesian inference for such models provides a desirable alternative, mitigating these difficulties by regularizing through the prior. However, computing a posterior is itself challenging, as a typical likelihood function will include latent variables. Following the recent success of tabular foundation models in backdoor, instrumental variable, and frontdoor settings, we propose that prior-data fitted networks (PFNs) are uniquely suited to resolve this bottleneck. Indeed, by traini

---

### [211] Localize Any Object in X-Ray Security Scans without Human Annotation

**链接**: https://arxiv.org/abs/2610.07326
**作者**: Yaqi Cai, Mingxuan Liu, Lorenzo Vaquero, Ning Wang, Nan Pu, Feng Xue 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Universal object localization in X-ray security inspection is critical for automated threat detection in safety-critical venues. However, unlike everyday RGB images that dominate web-scale visual data, X-ray scans exhibit distinct color patterns, ambiguous boundaries, and compositional structures caused by volumetric superposition. These gaps hinder the direct zero-shot transfer of dense perception foundation models trained on web-scale RGB data. Moreover, annotated X-ray data is scarce and requires expert labeling, limiting both the training of generalizable X-ray native models and the adaptation of RGB foundation models for X-ray data via fine-tuning. Given these challenges, the bright promise of highly generalizable perception models, enabled by data scaling laws in the RGB domain, remains largely out of reach for X-ray inspection. To this end, we introduce LAO-X, a self-supervised adaptation framework that Locates Any Object in X-ray scans using diverse synthesized image--annotatio

---

### [212] Global Transport Couplings for Classifier-Free Guided Flows

**链接**: https://arxiv.org/abs/2610.07555
**作者**: Katarina Petrovi\'c, Zander W. Blasingame, Danyal Rehman, \.Ismail \.Ilkan Ceylan, Michael Bronstein, Stephen Y. Zhang 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optimal-transport couplings have been shown to reduce training variance in unconditional flow models, but their role in conditional generation remains unclear. A natural approach constructs separate couplings for each condition, but this is impractical for large or continuous conditioning spaces found in modern image foundation models. We introduce Global Transport (GT), a global class-agnostic optimal-transport coupling, computed without class labels. GT can associate different conditions with different regions of the source noise, and consequently worsens performance without guidance. However, when combined with classifier-free guidance (CFG), GT consistently improves generation across domains, model scales, and sampling budgets. This reversal suggests that couplings for conditional flows should be evaluated both empirically and theoretically under the guided flow used at inference, rather than on unguided generation. We evaluate GT over both discrete class and continuous text condit

---

### [213] TAFFY: A Task-Adaptive Tabular Foundation Model with In-Context Diversity

**链接**: https://arxiv.org/abs/2610.07559
**作者**: Zijian Li, Xiangchen Song, Gongxu Luo, Jie Qiao, Ruichu Cai, Zhenhao Chen 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in tabular foundation models suggests that training on synthetic tasks can substantially improve in-context learning capabilities, with overall performance largely depending on how well models can infer task-specific predictive relationships from the available context during inference. In this paper, we introduce TAFFY, a tabular foundation model with an In-Context Diversity Prior and a Task-Conditioned Looped Transformer that strengthen this ability. Specifically, to construct each synthetic pretraining context, the In-Context Diversity Prior samples from multiple related environments derived via controlled interventions and distribution shifts on a shared causal process. This in-context diversity encourages the model to learn a more comprehensive and task-specific representation. Moreover, the Task-Conditioned Looped Transformer iteratively and selectively applies a shared group of Transformer blocks to refine contextual representations, with a task-conditioned gate m

---

### [214] EmbodiedSmith: Scaling Embodied Data through Recursive Self-Improvement Flywheel in Simulation

**链接**: https://arxiv.org/abs/2610.07969
**作者**: Yikai Qin, Yifei Deng, Mingjian Liang, Wenxuan Song, Zepeng Lin, Zhiyi Jiang 等 (10 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling robotic foundation models requires diverse training data and reliable evaluation environments. Simulation offers a scalable solution, yet existing generation pipelines remain constrained by predefined assets and skills, a disconnect between scene generation and task generation, and limited support for complex embodiments and physics. We introduce EmbodiedSmith, a framework for scalable embodied data generation through recursive self-improvement (RSI). EmbodiedSmith unifies asset, scene, and task generation in a pipeline that supports autonomous creation and language-driven customization. Its core is an agentic refinement loop: scene generation anticipates downstream task requirements, while task generation guides targeted scene edits, allowing scenes and tasks to iteratively improve one another. This joint refinement improves task generation success, including for long-horizon tasks. The framework further supports mobile manipulators, humanoids, and dexterous hands, as well as 

---
