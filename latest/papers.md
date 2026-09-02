# 📑 论文索引 - 2026-09-03

共 183 篇论文

---

### [1] EDGE: Error Dependency Graph-Guided Multi-Error Attribution in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2609.01360
**作者**: Jun Hou, Priya Pitre, Yi Fang, Xuan Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agent failures often contain multiple related errors rather than a single mistake. Existing attribution methods usually identify a responsible agent, step, or root cause, but do not explicitly model dependency between errors. We introduce EDGE, an Error Dependency Graph-guided multi-Error attribution framework. EDGE constructs an error dependency graph from observed error events and validates a reliable causal subset through counterfactual rollout. The inference graph guides a two-stage LLM-as-judge detector for error attribution, and the intervention-validated subgraph provides a more reliable basis for explanation and repair analysis. Experiments on TRAIL and MAST show that EDGE improves category-level multi-error attribution across most evaluated models and settings. Experiments with adapted Who&When-style prompts show that the graph helps across prompting strategies. These results suggest that dependency structure is a useful diagnostic prior for agent fa

---

### [2] Skill Following: Evaluating Actual Skill Use in Retrieval-Enabled LLM Agents

**链接**: https://arxiv.org/abs/2609.00549
**作者**: Seonghyeon Cho, Chanjun Park
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents increasingly rely on external skills, yet standard evaluations obscure whether retrieving these skills actually helps. Aggregate metrics often compare retrieved versus non-retrieved tasks, introducing severe selection bias and failing to isolate the true effect of skill use. To measure this actual-use capability-which we formalize as Skill Following (SF)-we introduce the Retrieval-Invoked Actual-Use Effect (RAE). RAE computes the same-task outcome difference between matched skill-enabled and skill-disabled executions, conditioned exclusively on tasks where the agent actively retrieved a skill. Evaluating 17 LLMs across coding and mathematical domains, we uncover a stark evaluation paradox: models frequently show positive aggregate retrieval lift but negative RAE. On MBPP+, multiple models that appear to benefit system-wide actually harm their own performance on the exact tasks where retrieval occurred. These findings demonstrate that aggregate averages

---

### [3] AutoXRD: Autonomous LLM Agents and Comprehensive Evaluation for Powder Diffraction Analysis

**链接**: https://arxiv.org/abs/2609.00070
**作者**: Yuetong Wu, Maojun Sun
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Powder X-ray diffraction (XRD) is central to materials characterization, yet reliable end-to-end automation remains challenging. An XRD agent must interpret diffraction evidence, operate refinement software, manage coupled parameters in a defensible order, and distinguish numerical improvement from physical validity. In this paper, we propose AutoXRD, an autonomous large language model (LLM) agent framework that organizes powder-XRD analysis as stepwise refinement, grounds actions in observed evidence, and applies deterministic crystallographic and physical checks before accepting results. We further introduce XRDBench with two complementary tracks. XRDBench-QA contains 100 bounded diagnostic tasks that isolate scientific reasoning and decision-making, whereas XRDBench-E2E contains 34 executable workflows that test whether agents can compose these capabilities into complete analyses requiring file inspection, crystallographic-software execution, iterative refinement, evidence preservat

---

### [4] Learning What to Retain: Gated-Memory Routing for Efficient Collaboration in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2609.00237
**作者**: Rakibul Hasan Rajib, Mengxing Zheng and Qian Lou
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems tackle complex reasoning by orchestrating how multiple agents are configured and how they collaborate. A central challenge is to adapt orchestration to the evolving collaboration state. Routing from the query alone cannot adapt to intermediate progress or errors, which hurts accuracy. Routing from the complete execution history supplies this missing context, but forces later decisions to process every prior step, including redundant or low-utility ones. This creates an execution-history overload that inflates cost. Effective orchestration instead requires a compact state that captures useful progress without accumulating redundant context. We propose Gated-Memory Routing, which conditions each decision on the query and a learned execution memory. A learned Memory Write Gate commits only non-redundant reasoning steps, and a learned Retrieval Gate supplies each agent a compact, relevant subset, so every decision conditions on a clean, 

---

### [5] Embedded Conditional Independence Tests for Large Language Model Generated Text with an Application to German Parliament Speeches

**链接**: https://arxiv.org/abs/2609.00946
**作者**: Marco Simnacher, Georg Keilbar, Benjamin K\"onig, Christoph Lippert, Sonja Greven
**来源**: stat.ML cs.AI cs.LG math.ST stat.ME stat.TH
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conditional independence tests (CITs) test for conditional dependence between two random objects $X$ and $Y$ given a third random object $Z$. Existing CITs have limited applicability to high-dimensional data, especially multimodal data like text. However, we show that such tests are of interest for large language model (LLM) outputs, where we test whether an output $X$ generated from a source text $Z$ carries information about an attribute $Y$ beyond $Z$ itself. For this purpose, we propose embedded CITs (eCITs), which embed $X$ and $Z$ and apply an existing CIT to the resulting representations and to $Y$. We show that, provided the embedding of $Z$ is sufficient, i.e. retains the information $Z$ carries about either $Y$ or the representation of $X$, the null hypothesis transfers from $X$ and $Z$ to their representations, so that a CIT valid for the embedded hypothesis is valid for the original one. We further give conditions for equivalence of the two hypotheses, and show that suffici

---

### [6] mzCache: On-Device LLM Memory Management under Multitasking

**链接**: https://arxiv.org/abs/2609.01338
**作者**: Hongseung Yu, Minsung Kim, Jongseok Park, Kyunghan Lee
**来源**: cs.OS cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device mobile Large Language Model (LLM) inference is gaining significant attention. However, mobile devices operate in highly dynamic multitasking environments where users frequently switch between applications. This creates memory pressure, forcing LLM memory (model weights and KV cache) to be evicted by the operating system. When a new inference request arrives, the inference system must restore the evicted memory through slow storage reads or recompute the entire KV cache, severely degrading responsiveness. To address this, we present mzCache, an on-device LLM inference system with specialized memory management for multitasking environments. Under unpredictable memory pressure, mzCache elastically evicts LLM memory and leverages the unified memory of mobile SoCs to enable zero-wait inference on the GPU with concurrent CPU-side restoration. mzCache realizes this through restoration-oriented memory management: LLM memory is partitioned into fine-grained shared buffers to enable pa

---

### [7] SkillRet: A Large-Scale Benchmark for Skill Retrieval in LLM Agents

**链接**: https://arxiv.org/abs/2605.05726
**作者**: Ryangkyung Kang, Hongcheol Cho, Youngeun Kim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [8] RestoreBench: Can AI Agents Restore Power Flow Convergence?

**链接**: https://arxiv.org/abs/2609.00384
**作者**: Riccardo Mansutti, Andrea Pomarico, Robert Jakob, Qian Zhang, Alberto Berizzi, Kevin O'Sullivan
**来源**: cs.AI cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents increasingly automate multi-step engineering workflows through tool use, interpretation of intermediate results, and iterative planning. Diagnosing and resolving non-convergent power flow cases is a promising yet largely unexplored application, as it requires engineering judgment, experimentation, and decision-making within constrained action spaces. We introduce a benchmark that evaluates these capabilities across multiple LLMs and three architectures: \emph{chatbot}, \emph{single agent}, and \emph{multi-agent} systems. The evaluation covers two power grids and 46 cases per grid, each requiring one or more corrective actions to restore convergence. The benchmark defines the simulation environment, observation and action spaces, and evaluation metrics, providing a reproducible foundation for developing agentic AI systems for power system planning and operation. The code is available at https://github.com/Mansutti081/RestoreBench

---

### [9] RetroReasoner: A Reasoning LLM for Strategic Retrosynthesis Prediction

**链接**: https://arxiv.org/abs/2603.12666
**作者**: Hanbum Ko, Chanhui Lee, Ye Rin Kim, Rodrigo Hormazabal, Sehui Han, Sungbin Lim 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [10] MicroEvo: Knowledge-Guided LLM Sampling for Efficient Microarchitecture Design Space Exploration

**链接**: https://arxiv.org/abs/2608.06183
**作者**: Jia Xiong, Runkai Li, Chenxu Niu, Guangyuan Gao, Changwen Xing, Yifan Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [11] Pre-carved Niches: The Formation Dynamics of Modular Task Partitions in Early LLM Training

**链接**: https://arxiv.org/abs/2609.01170
**作者**: Guangqi Li, Yongxin Li
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models exhibit a modular internal organization that mirrors well-studied functional networks of the human brain, but how this organization forms during training is unknown: prior work has characterized finished models, not the formation process. We track formation step by step: we train a Pythia-410M model from scratch (two trajectories, bf16 and fp32) and run attribution patching at every step, alongside probes for gradient norms, effective updates, weight norms, and first-order loss decomposition across 14 tasks in four cognitive domains. Three findings. First, the modular map is pre-carved: before any learning, the dominant task pair already overlaps at ~3.6x the attribution substrate (a task-independent baseline), and its layer-0 concentration is an architecture-level constant on this model family. Second, the partition locks in through two sharp jumps whose amplitudes do not track the learning-rate schedule (the second reaching 20.4 sigma quiet-window / 6.2 sigma gl

---

### [12] ChatDev 2.0: A No-Code Multi-Agent Platform for Developing Everything

**链接**: https://arxiv.org/abs/2609.00714
**作者**: Yufan Dang, Shu Yao, Bowen Lai, Chenting Xu, Ruijie Shi, Wai-Shing Leung 等 (9 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) have shown strong potential for solving complex tasks, yet their development forces a tradeoff: code frameworks are expressive but engineering-intensive, while no-code builders simplify authoring but constrain agent interactions to author-defined workflows. We present ChatDev 2.0: DevAll (hereafter DevAll), a no-code platform for building, executing, and inspecting heterogeneous MAS that delivers both high expressiveness and ease of use. In terms of expressiveness, DevAll pairs a declarative executable graph abstraction with a cycle-aware execution engine, so that heterogeneous agents and dynamic and cyclic interactions can be represented and executed within a single framework. For ease of use, an integrated visual interface lets users author, run, monitor, and inspect MAS, including human-in-the-loop steps, entirely without writing code. Experiments demonstrate that DevAll reproduces state-of-the-art MAS across three represent

---

### [13] Learning to Refine Hidden States for Reliable LLM Reasoning

**链接**: https://arxiv.org/abs/2606.17524
**作者**: Chia-Hsuan Hsu, Jui-Ming Yao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] UrbanDS: A Graph-Guided LLM Multi-Agent System for Data-Intensive Urban Tasks

**链接**: https://arxiv.org/abs/2607.26724
**作者**: Zhilun Zhou, Jianghao Yu, Yuming Lin, yongjun yang, Sun Yongquan, Depeng Jin 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] LLM-driven design of physics-constrained constitutive models: two agents are better than one

**链接**: https://arxiv.org/abs/2605.23754
**作者**: Marius Tacke, Matthias Busch, Kian Abdolazizi, Jonas Eichinger, Kevin Linka, Roland Aydin 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] Do LLMs Know Your Neighborhood? Auditing LLM Priors for Neighborhood-Level Mobility Prediction and Structural Alignment

**链接**: https://arxiv.org/abs/2609.00345
**作者**: Saad Mohammad Abrar, Eesha Kurella, Arnav Dadarya, Naman Awasthi, Kazi Tasnim Zinat and Vanessa Frias-Martinez
**来源**: cs.LG cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human mobility is central to urban planning, transportation, public health, and emergency response, yet fine-grained trajectory data are often proprietary, restricted, and privacy-sensitive. Large language models (LLMs) offer a potential alternative by generating plausible mobility traces and predicting individual movement, but their ability to infer aggregate neighborhood-level mobility remains unclear. We evaluate zero-shot LLMs on Census Block Group-level mobility prediction across four U.S. metropolitan areas using anonymized Cuebiq data to construct point-level, trajectory-level, and temporal mobility outcomes, paired with sociodemographic and built-environment predictors. We compare LLM predictions with supervised baselines and introduce a directional alignment analysis to test whether LLM-implied predictor effects agree with empirical OLS and Jonckheere-Terpstra trends. Supervised models achieve 0.580 average accuracy, compared with 0.435 for the best LLM, with spatial extent ou

---

### [17] Beyond Language Priors: Diagnosing and Fixing Visual-Origin Hallucinations in Multimodal LLM

**链接**: https://arxiv.org/abs/2609.00231
**作者**: Peiyang Xu, Xiaopei Zhu, Jun Zhu, Xiaolin Hu
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing research on object hallucination in multimodal large language models (MLLMs) predominantly attributes the problem to language priors such as over-reliance on textual co-occurrence statistics. We challenge this view by presenting quantitative evidence for a complementary, under-explored cause: visual-origin hallucination, where hallucinations arise from incorrect visual feature extraction and misalignment between image and text embeddings. Through cosine similarity analysis and Smooth Grad-CAM entropy measurements, we show that hallucinated samples exhibit systematically lower image-text similarity (average 0.158 vs. -0.122) and inverted attention patterns, where attention is dispersed when the target object is present but wrongly concentrated when it is absent. Guided by this diagnosis, we propose Adversarial Contrastive Fine-Tuning (ACFT). ACFT uses an Adversarial Hallucination Attribute Flipping (AHAF) procedure, involving minimal, targeted adversarial perturbations that fli

---

### [18] RPCBench: A Benchmark for Proactive Premise Critique in LLM-based Recommendation

**链接**: https://arxiv.org/abs/2609.00918
**作者**: Zhongru Chen, Yuan Wu, and Yi Chang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as interactive recommender assistants. Their evaluation should therefore go beyond plausible item recommendation and test whether they can recognize flawed recommendation requests. Existing recommender benchmarks mainly assess ranking, generation, or preference satisfaction, while existing error-detection benchmarks are usually not grounded in recommendation-specific user and candidate evidence. To address this gap, we introduce RPCBench, a benchmark for evaluating Recommender-Premise Critique: the ability to detect, diagnose, and properly handle faulty premises in natural-language recommendation requests. RPCBench contains evidence-grounded test instances from five recommendation domains and covers ten types of premise failures. Each instance provides a visible recommendation context and a corrupted user query. We further design a fine-grained evaluation framework that measures proactive detection, error localization, post-detection handling

---

### [19] Deterministic LLM Inference Across GPU Kernels: Power-of-Two INT8 Quantization Scales and the Limits of Tolerance-Based Conformance

**链接**: https://arxiv.org/abs/2609.00363
**作者**: Teng-Ruei Chen
**来源**: cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] REAL-Q: E2E LLM Quantization via Dynamic Gradient Descent

**链接**: https://arxiv.org/abs/2609.00049
**作者**: Qian Zhang, Yaoming Li, Zhewen Tan, Yanshu Wang, Heng Lu, Kun Su 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization (PTQ) is essential for deploying large language models (LLMs) under strict resource constraints. State-of-the-art PTQ methods quantize each layer with a single closed-form second-order solver: to remain analytically tractable, they heavily approximate the global loss (dropping cross-channel coupling, pooling output rows into groups), and they then freeze the resulting Hessian across the entire layer, with no way to refresh it as the loss landscape shifts column by column--a phenomenon we call information misalignment. We propose REAL-Q (Real-time E2E-loss Aligned LLM Quantization), a novel PTQ paradigm that breaks this compromise: instead of diluting the objective for the sake of analytic tractability, REAL-Q targets an end-to-end-aligned surrogate of the global loss and refines it via fine-grained, dynamic Block-wise Gradient Descent applied after every column block (128 columns). By coupling this fine-grained correction with a sliding window mechanism for s

---

### [21] StudentSim: Training LLM-based Student Simulators

**链接**: https://arxiv.org/abs/2609.01591
**作者**: Ke Yang, Chenglong Wang, Michel Galley, Chandan Singh, Jeevana Priya Inala, ChengXiang Zhai 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI tutors are most useful when they adapt to each student's strengths, weaknesses, and preferred guidance, but evidence about which guidance works for which student is sparse, slow, and costly to collect from real learners. Student simulators can provide this signal as a proxy, yet existing approaches are limited: state-tracking models fit student behavior but struggle to process explanations or corrections, while LLM role-play follows guidance fluently but does not reliably match the competence of the student being imitated. We present StudentSim, a training framework that turns sparse per-student data into individualized simulators through pooled training followed by per-student specialization. The resulting simulators both mirror a student's own responses and update them under tutor guidance. We also introduce StudentSimEval, a standardized protocol covering 60 students across chess, second-language English writing, and mathematics, using public learner datasets with de-identified r

---

### [22] ContextPipe: Database-Inspired Context Assembly for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2609.00749
**作者**: Peng Xu, Zuyu Zhang, Yuze Sun, Feng Tian, Long Wang, Chen Zhang
**来源**: cs.AI cs.DB
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon large language model (LLM) agents require context assembly: the runtime must decide what to include in each prompt, in what order, and when to compact history under a hard context-window budget and a byte-sensitive prompt cache. In production agentic systems, this logic is scattered across prompt builders, ad hoc compaction routines, cache-break workarounds, and per-provider shims. We argue that context assembly is structurally isomorphic to query execution in a relational database: both execute under a hard budget, exploit a tiered cache, and leverage statistics. We adopt this discipline in ContextPipe: a five-phase pipeline (Plan Bind Optimize Execute Feedback) backed by a structured data-source catalog, a deterministic cache-aware optimizer, and an EXPLAIN ANALYZE trace. We show that context in ContextPipe is auditable, replayable, and failure-isolated. A preliminary evaluation using the SWE-bench Pro Qutebrowser subset shows that, compared with the append-only context 

---

### [23] PCoMoE: Shifting MoE Inference from Monolithic Expert Selection to Fine-Grained Path Composition

**链接**: https://arxiv.org/abs/2609.01024
**作者**: Ziyan Gan, Fangxin Liu, Chenyang Guan, Junjie Wang, Ning Yang, Haomin Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixture-of-Experts (MoE) architectures scale Large Language Model (LLM) capacity efficiently by activating a sparse subset of experts per token. However, modern MoE inference remains heavily constrained by the rigid, whole-expert abstraction. Existing frameworks manage, schedule, or prune experts as atomic execution units, which fixes the optimization boundary too early and leaves fine-grained intra-expert computational redundancy underexplored. In this work, we present PCoMoE, a path-compositional execution framework that shifts MoE inference from coarse-grained expert selection to fine-grained path composition. PCoMoE incorporates a path-level formulation of expert computation, a compatibility-aware layer-wise pruning strategy to suppress low-value path combinations, and a hardware-friendly execution engine to exploit reusable sub-expert structures under strictly bounded overheads. Experimental results demonstrate that PCoMoE achieves up to a 1.31x end-to-end inference speedup while 

---

### [24] RePro: Proof-Verified Benchmark Rewriting for Reliable Evaluation of LLM Mathematical Problem Solving

**链接**: https://arxiv.org/abs/2609.00062
**作者**: Xiyuan Zhou, Zhuoqi Li, Xinlei Wang, Yirui He, Yuhao Wu, Yuheng Cheng 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data contamination undermines the reliable evaluation of large language models (LLMs) on mathematical problem solving. While rewriting-based evaluation mitigates memorization, existing methods lack guarantees of problem validity and answer correctness. We propose Proof-Verified Benchmark Rewriting (RePro), the first framework to integrate Lean-oriented neural automated theorem provers (ATPs) into benchmark rewriting, which rewrites problems and regenerates answers with correctness ensured by Lean-verified proofs. Experiments on GSM8K and MATH show that RePro's retained rewritten instances achieve 100% well-definedness, feasibility, and answer correctness, while existing methods still produce invalid or incorrect instances. Moreover, several models exhibit accuracy drops on proof-verified rewritten benchmarks, suggesting that their performance is sensitive to surface-level and structural variations and may partly reflect memorization effects. Our source code and data are available at ht

---

### [25] OUTLETS: Output-Length Prediction from Speculative Decoding Backbones

**链接**: https://arxiv.org/abs/2609.01068
**作者**: Weihuang Wen, Yingying Liu, Yichuan Liu, Wenqi Zeng, Li Zhou, Chumin Sun 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The heavy-tailed distribution of output lengths in Large Language Model (LLM) serving poses major challenges for resource provisioning and cluster scheduling. Although output-length prediction can mitigate these issues, existing approaches have key drawbacks: external proxy models add substantial latency and often have limited fidelity, whereas internal state-based methods are efficient but rely on shallow probes of current model states. We identify a structural connection between speculative decoding (SD) and length prediction: latent representations produced by the draft decoder in advanced frameworks (e.g., EAGLE-3) encode signals that are predictive of generation length. Building on this insight, we introduce OUTLETS (Output-Length Prediction from Speculative Decoding Backbones), which repurposes the speculative backbone as a trajectory-aware length predictor. When its draft representations are already computed for speculative decoding, OUTLETS adds only a lightweight regression he

---

### [26] Beyond Scores: Understanding LLM-as-a-Judge Mechanisms in Summarization Evaluation

**链接**: https://arxiv.org/abs/2609.01604
**作者**: Himil Vasava, Ming Jiang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based evaluators of natural language generation (NLG) quality are widely deployed as scoring tools and as automated training signals, yet the internal procedure by which they assign a rating remains poorly understood. We investigate this procedure mechanistically through an eight-attack perturbation taxonomy across the Readability and Adequacy dimensions of NLG quality, a generation pipeline that produces paired clean and corrupt summaries with controlled error intensity and explicit token-level modification maps, and a four-experiment battery of causal tracing, logit-lens vocabulary projection, and attention-head knockout applied to Themis (Llama-3-8B) and Prometheus (Mistral-7B). Both evaluators implement a structured, coherent evaluation pipeline operating in two stages: below layer 15, attention performs local error comparison and routes the result to the final input position; above it, the MLP cascade integrates the signal and writes the rating, with the decision crystallizing

---

### [27] GlossoGen: Emergent Language in Complex Multi-Agent LLM Interactions

**链接**: https://arxiv.org/abs/2609.01491
**作者**: Elias Stengel-Eskin, Newton Sander, Carlos Bonetti, Sasha Boguraev, James Bowler, Hale Sirin 等 (7 人)
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing rate at which LLM agents interact with one another raises key questions about language evolution in multi-LLM-agent settings, with implications for safety and monitorability as well as for linguistic accounts of LLMs. To address these questions, we introduce GlossoGen, a novel platform for studying multi-agent language evolution in complex scenarios. Within GlossoGen, we build the SaveVeyru scenario, which requires agents with partial information to communicate under pressure. We find that language evolution does occur between LLM agents, that the resulting languages are compositional and morphologically productive, and that they deviate from the LLMs' English prior in ways that render them incomprehensible to humans. Moreover, we identify several qualities essential to this evolution: pressure towards efficiency; the strength of the models backing the agents; and access to a "postmortem" stage in which agents can agree on linguistic conventions. Importantly, we observe tha

---

### [28] AgentProv: Auditing Agentic LLM API Providers via Tool-use Policy Probes

**链接**: https://arxiv.org/abs/2609.00052
**作者**: Xun Wang, Bihe Zhao, Michael Backes, Franziska Boenisch, Adam Dziedzic
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Commercial LLM APIs advertise a specific foundation model, but the served backbone may be silently substituted, quantized, or wrapped, for example to save deployment costs. All existing audits decide backbone identity from the text-output channel, which is structurally fragile for agentic APIs because modern serving stacks (OpenAI, Anthropic, Gemini, Cloudflare Workers AI, LangGraph) discard text and expose only structured actions when the model calls a tool, and provider-injected system prompts can distort text distributions enough that text-channel tests falsely accuse honest providers of substituting the claimed model. We observe that recent agentic post-training internalizes tool-use directly into the weights, opening a new audit channel that the serving stack still exposes and that is largely invariant to deployment context. We introduce Agentic Provenance (AgentProv), the first action-based identity audit for agentic LLM APIs: AgentProv fingerprints a deployed model through its c

---

### [29] Toward Workflow-Aware Benchmarking for Healthcare NLP Agents

**链接**: https://arxiv.org/abs/2609.00296
**作者**: Junyi Yao, Baichuan Li, Zihao Zheng, Jiayu Long
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly proposed for healthcare tasks such as clinical documentation, evidence retrieval, patient messaging, and care coordination. Yet many evaluations remain limited to static medical question answering or one-shot generation, under-representing longitudinal state, interruptions, and human handoffs. We introduce an episode-level evaluation protocol for healthcare NLP agents. The protocol separates evidence across model, agent, and simulated-workflow behavior; specifies a five-field episode schema; and defines annotation and scoring for state continuity, evidence traceability, and escalation decisions. It is instantiated as four task templates: documentation update, evidence retrieval, patient messaging, and triage handoff. The protocol does not claim to measure clinical outcomes or deployment value. Instead, it supplies a reproducible intermediate evaluation layer between static benchmarks and prospective workflow studies, with an explicit c

---

### [30] Zero-Shot Respiratory Sound Classification through LLM-Augmented Audio-Text Alignment

**链接**: https://arxiv.org/abs/2609.00055
**作者**: Mustafa Talha \.Ilerisoy, Hung Manh Pham, Mathias Funk, Mykola Pechenizkiy, Aaqib Saeed
**来源**: cs.CL cs.AI cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised respiratory encoders lack semantic grounding in clinical domain needed for zero-shot inference, limiting their utility without task-specific labeled data. We propose a framework that aligns these encoders with medical terminology in a shared latent space turning them into a zero-shot-capable foundation model. To address paired data scarcity, we use a medical LLM to synthesize structured reports from metadata, creating dense semantic anchors for contrastive learning. Our training combines a sigmoid-based contrastive loss with encoder's native SSL objective and similarity-aware negative sampling to sharpen pathological boundaries. Across 9 tasks on 6 datasets, our method achieves a 61.3% mean zero-shot AUC, surpassing CLAP (51.4%) and Qwen2-Audio (54.9%) while reaching the highest linear probing AUC (71.6%) with only 43% of data used by full-scale baselines, showing that structured semantic alignment outperforms large-scale, general-purpose models in clinical diagnostics.

---

### [31] SOVER: Formal Certification of Optimization Reformulations via LLM-Assisted SMT Verification

**链接**: https://arxiv.org/abs/2609.00728
**作者**: Swapnil Bhattacharyya and Mayank Baranwal
**来源**: cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown remarkable promise in translating and reformulating complex mathematical optimization problems across modeling languages. However, validating such transformations through empirical solver executions alone is unreliable, as solver outcomes may be affected by local minima, structural timeouts, numerical artifacts, and subtle semantic divergence between formulations. We introduce SOVER, an LLM-assisted SMT framework that separates semantic mapping from formal certification: Z3 checks domain cross-feasibility and global objective-order preservation for mixed-integer linear formulations, while dReal provides tolerance-aware feasibility/range and $\epsilon$-argmin checks for continuous nonlinear formulations. We also introduce NLEquiv-150, a public benchmark of 100 equivalent and 50 deliberately hard non-equivalent nonlinear reformulation pairs. With LLM-extracted mappings, SOVER classifies 149/150 pairs (99.33%) correctly, including all 50 hard negati

---

### [32] Investigating Assistant Bias in LLM User Simulators Using a Role Vector

**链接**: https://arxiv.org/abs/2609.00608
**作者**: Daeheon Jeong, Yoonjoo Lee, Eugene Choi, Sinie van der Ben, Juho Kim
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based user simulators are increasingly used to evaluate autonomous agents at scale, in place of costly human evaluations. Despite this promise, these simulators exhibit "assistant bias," a tendency to cooperate and pursue task goals. They rarely reproduce the frustration or disengagement that real users exhibit, compromising evaluation validity. Prior work outlines that this bias is baked in during model training, which role-playing prompts fail to override. We analyze this bias from model activations, extracting a user role vector by contrasting how the model represents user versus assistant perspectives on the same dialogue. We observe two findings: (i) the user direction is identifiable in activations, elicits user-like behaviors, and captures characteristics distinct from assistant traits; and (ii) although user-role activation associates with simulation realism and steering strengthens it, it can exaggerate user behaviors and override individual user profiles. Together, our fi

---

### [33] Inspicio: Open-Vocabulary, LLM-Based Sense Retrieval for Historical Languages

**链接**: https://arxiv.org/abs/2609.00998
**作者**: Michele Ciletti
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Word Sense Disambiguation has advanced rapidly for English and a handful of well-resourced modern languages, but it continues to assume the existence of a sense inventory and a word-to-sense mapping in the source language (Navigli, 2026). These assumptions break down for most historical and low-resource languages, whose dedicated WordNets are either incomplete or still under construction. We present Inspicio, an open-vocabulary retrieval pipeline that links tokens in context to synsets of the Open English WordNet (McCrae et al., 2020) without requiring any source-language inventory or mapping. For each occurrence, an instruction-tuned LLM produces two English translations of the surrounding sentence, a small set of candidate dictionary-style definitions, and a few candidate English lemmas. These outputs drive a hybrid retrieval step that combines dense definition-synset similarity, sparse lemma matching, and Maximal Marginal Relevance re-ranking. We evaluate the pipeline across a 6x6 g

---

### [34] Post-hoc Alignment of LLM-judges to Human Judgment Distribution

**链接**: https://arxiv.org/abs/2609.01073
**作者**: Sebastian Steindl, Nikos Voskarides, Alberto Gasparin, Diego Marcheggiani
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The LLM-as-a-judge (LLMaJ) framework offers a cost-effective and reproducible solution for automatic evaluation. However, current evaluation practices typically compare LLMaJ judgments against aggregated ground-truth labels, overlooking the valuable information contained in Human Label Variation (HLV). Inspired by an increasing line of work that proposes to leverage HLV, we systematically study LLMaJ performance on predicting both a single, aggregated ground truth hard-label and unaggregated soft-labels that represent Human Judgment Distributions (HJD). Our results across five diverse datasets reveal that while LLMs achieve near human-level performance at hard-label prediction on most tasks, they exhibit poor performance when predicting soft-labels. To address this limitation, we propose NAPHA (eNtropy-Aware Post-Hoc Alignment), a simple yet effective lightweight post-hoc alignment method that matches the LLM distribution to the HJD by first assigning an instance to a discrete entropy 

---

### [35] Self-Reports Are Not Verification: Environment-Grounded Auditing of LLM Operators in Evolutionary Search

**链接**: https://arxiv.org/abs/2609.00652
**作者**: Enrong Pan, Ryan Zhou, Ting Hu
**来源**: cs.AI cs.LG cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model agents increasingly propose actions, observe external feedback, and explain their own behavior. Their confidence and rationales are convenient monitoring signals, but convenience is not verification. We introduce an environment-grounded audit in which every intermediate proposal receives an exact outcome. A language model operates an evolutionary Contexto search whose feedback function assigns every valid guess an exact rank without human annotation. Across 200 runs spanning five configurations and three model families, four reporting configurations produce 12,249 self-reports. We test three assumptions: stated confidence is calibrated, inherited rationales affect later proposals, and fitness-based selection improves report quality. All three fail. Operators overstate top-100 success by factors of 4.8 to 9.3, while calibration and discrimination dissociate across model families. Controlled interventions on 754 inherited rationales bound any measured benefit of the genuin

---

### [36] Calibration is the Bottleneck: An Action-Class Diagnostic of Multi-Turn Tool-Calling

**链接**: https://arxiv.org/abs/2609.00949
**作者**: Kangjia Zhao, Jiajun Li, Haozhan Shen, Wei Chow, Linfeng Li, Hang Song 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn tool calling is a core evaluation scenario for large language model (LLM) agents. On public tool-calling benchmarks, open-weight models now approach or even surpass closed-source frontier models in aggregate accuracy. However, this metric averages over many different multi-turn situations and obscures whether progress is balanced across them. We propose an action-class-oriented diagnostic framework that decomposes multi-turn failures into two orthogonal modes: action-class miscalibration and action-execution failure. The framework operates over a four-class action space (TOOL_CALL/ASK/REFUSE/CONFIRM) and introduces a self-revealing upper bound Acc <= GAR (Gold Action Recall); the two modes show up as bound violation (Acc > GAR, exposing state-grader masking of miscalibration) and large bound slack (GAR >> Acc, localizing execution failure within TOOL_CALL). We validate it on a panel of tool-calling models across multiple multi-turn benchmarks. Across our panel, the diagnosti

---

### [37] trajectory-judge: What Outcome-Only LLM Judges Miss on Agent Trajectories

**链接**: https://arxiv.org/abs/2609.00038
**作者**: Hadi Mohammadi
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Outcome-only evaluation is the production default for LLM agents: show a judge the request and the final reply and ask whether it was handled well. The metric is structurally blind to an agent that reaches the right answer the wrong way. We measure that blind spot where ground truth is known by construction: a deterministic tool-using support-desk environment, a scripted oracle policy that always solves it, and a fault injector that breaks exactly one thing at a known step, stratifying faults by whether the customer-visible outcome survived (silent) or not (loud). Five judges (programmatic rules, outcome-only, step-rubric at two model sizes, and a self-consistency ensemble) are scored on detection, step localisation, fault typing, calibration, and cost over 400 trajectories. The outcome-only judge catches 84% of loud faults but 45% of silent ones while flagging 33% of correct trajectories; a step-rubric judge reaches 77% silent recall with zero false alarms at 3x the cost. No judge rea

---

### [38] SoK: When Safe Agents Fail Together: The Security of Multi Agent LLM Systems

**链接**: https://arxiv.org/abs/2609.00595
**作者**: Rui Yang, Junjie Xu, Zhengyu Liu, Neil Fendley, Yang Hong, Ziyang Li 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safe agents can fail together. Multi-agent LLM systems (MAS) move information, state, decisions, and authority across principal boundaries, creating failures that local checks may miss. Without an execution-level view, a multi-agent setting can easily be mistaken for evidence of a genuinely multi-agent security effect. We thus systematize MAS security through an execution-centered analysis of 197 works, covering six interaction interfaces, four adversary positions, seven system-level risks, and eight recurring attack paths. We introduce an A-I-R framework that organizes attacks by adversary position, interaction interface, and resulting system-level risk, unifying otherwise fragmented attack mechanisms across MAS. We organize defenses through a five-part contract covering path target, observation, intervention, trust boundary, and recovery, and identify path closure and recovery as key challenges. We audit 44 evaluation and benchmark works and identify open challenges in isolating inte

---

### [39] Multi-Agent LLM Orchestration Achieves Deterministic, High-Quality Decision Support for Incident Response

**链接**: https://arxiv.org/abs/2511.15755
**作者**: Philip Drammeh
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Beyond Static Summarization: Proactive Memory Extraction for LLM Agents

**链接**: https://arxiv.org/abs/2601.04463
**作者**: Chengyuan Yang and Zequn Sun and Wei Wei and Wei Hu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Drift-Aware LLM Routing with Sparse Contexts and Shared Budgets

**链接**: https://arxiv.org/abs/2609.00662
**作者**: Cheung Hao Lee, Patrick Wong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A multi-model language service must route each request while preserving workload-level budgets for compute, latency, memory, or monetary cost. Two features make this problem materially harder than static model selection. Prompt representations are high dimensional, so only a small subset of embedding directions may predict the incremental value of a model, and both the request mix and the model frontier drift after launches, fine-tunes, quantization changes, and system updates. We formulate nonstationary sparse contextual routing with multiple knapsack constraints and an optional shadow-audit stream that evaluates a small fraction of prompts on several models. We propose Drift-Aware Sparse Routing (DRS). The policy estimates reward and resource use from a rolling audit window, routes using pessimistic reward and optimistic cost estimates, updates resource shadow prices online, and applies a hard meter before commitment. The analysis separates control from statistics. On any event with 

---

### [42] Spawn Freely, Act Sparingly: Progressive Risk Vesting for Recursive LLM-Agent Trees

**链接**: https://arxiv.org/abs/2609.01035
**作者**: Molly Wang (Imperial Business School)
**来源**: cs.AI cs.LG math.PR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive LLM agents can broaden their search by spawning specialists. Some branches later request tools that send data or deploy code. When should a branch receive authority to act? We distinguish sandbox spawning, in which external controls prevent the specified harm, from capability activation, in which a selected branch crosses an irreversible-action boundary. Progressive Risk Vesting (PRV) holds a trajectory-level risk budget in escrow and debits it as branches are activated. We prove an anytime harm bound for adaptively generated trees. Branch outcomes may be dependent, but each local certificate needs to remain valid conditional on the full pre-activation history, including the information used to select the request. When activation gates, branch charges, and compute constraints are held fixed, delayed vesting preserves every policy available under irrevocable spawn charging. Marginal risk estimates can still fail after branch selection. In a stylized branching model, trajectory

---

### [43] Prediction-Assisted Pricing and Admission for LLM APIs with Stochastic Token Consumption

**链接**: https://arxiv.org/abs/2609.00710
**作者**: Patrick Wong
**来源**: cs.DS cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM application often sells or internally allocates several service products: a small or premium model, a short or long token cap, and possibly multiple posted prices. The operational decision is not merely which model answers a prompt. A price changes purchase probability, a token cap changes both user value and the tail of resource consumption, and accepted requests compete for shared compute and premium-model capacity. Demand and output length are initially uncertain, while an offline model may provide useful but imperfect predictions. We formulate sequential pricing and admission with stochastic resource consumption. Each arriving request belongs to an observable segment. The platform chooses a product--price pair or makes no offer; purchase, revenue, and resource use are then random. An offline predictor supplies a uniform, validated error radius for every segment--product cell. We propose Prediction-Clipped UCB (PCUCB), which intersects the offline prediction interval with an 

---

### [44] Towards a Belief-Based World Model for LLM Agents

**链接**: https://arxiv.org/abs/2609.00455
**作者**: Shubham Kumar, Harshit Kumar, Narendra Ahuja, Saurabh Jha
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are being used as policies for autonomous decision-making and planning in many domains. Despite their strong reasoning capabilities, LLMs struggle with long-horizon tasks, especially under partial observability. World models are a promising way to enhance policy performance, both during training and inference. During inference, agents currently use world models to simulate the consequences of candidate actions before committing to an action, which can improve decision-making. However, we argue that simulation alone is an incomplete interface for decision-making under partial observability: simulation doesn't adequately capture uncertainty about the current state, which agents may need for accurate decision-making. We address this limitation with Belief-Based World Models (BB-WMs), which model and maintain a belief that LLMs can query to access information on what is known and uncertain about the current state. Before developing methods to learn accurate BB-

---

### [45] RACE: Scalable Statistical Estimation of Functional Consistency in LLM Neurons

**链接**: https://arxiv.org/abs/2608.24758
**作者**: Runyu Wang, Bo Liu, Xiaxin Zhang, Yu Han, Jiawei Cao, Xiaoye Zhang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] EvoFlint: An Evolutionary Atlas of Multi-Turn LLM Vulnerabilities

**链接**: https://arxiv.org/abs/2609.00487
**作者**: Feitong Qiao, Liren Peng, Shiming Ren, Aishwarya Jadhav, Arghavan Bahadorinejad, Marinette Chen 等 (10 人)
**来源**: cs.CL cs.AI cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier language models that refuse harmful single-turn prompts often comply when the same intent is reached gradually over many turns, making multi-turn attacks one of the least understood failure modes of large language models. Most automated red-teaming methods treat this as a generation problem: produce attacks that break the model. We argue it is better framed as a search problem: discover, organize, and iteratively refine a diverse archive of attack strategies, producing a structured map of how a target model fails rather than a list of one-off successes. We introduce EvoFlint, which applies evolutionary quality-diversity search to multi-turn red-teaming. Attack strategies are phased conversation plans, not raw prompts, and are evolved through LLM-driven mutation and crossover. A Pareto fitness over attack success rate and peak severity preserves selection signal from near-miss attacks. A risk-indexed archive runs novelty search with local competition over strategy description e

---

### [47] Retrieval, Scoring, and Decoding Shape Performance and Stability in LLM-based Conversational Recommendation

**链接**: https://arxiv.org/abs/2609.00086
**作者**: Ante Kapetanovic, Tomislav Duricic, Andro Mercep, Emanuel Lacic
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as rerankers in conversational recommender systems, yet measured gains depend strongly on the retrieval and inference protocol. On the ReDial conversational movie recommendation benchmark, we compare proprietary, open-weight, and fine-tuned LLM rerankers with collaborative-filtering and sequential baselines in a shared retrieve-then-rerank pipeline. We vary candidate-pool size, first-stage retriever, and decoding temperature. With a shared semantic top-250 candidate pool and strict candidate-aware scoring, the best proprietary reranker reaches NDCG@10 of 0.1497, compared with 0.0939 for the strongest non-LLM baseline. The same reranker reaches 0.2925 in zero-shot generation, showing that unconstrained scoring can yield a much larger apparent advantage than matched-pool evaluation. No evaluated open-weight LLM outperforms the tuned shallow autoencoder baseline under this protocol. For the strongest proprietary and open-weight rerankers,

---

### [48] UniACE: A Unified Framework for Evaluating LLM Agentic Capabilities

**链接**: https://arxiv.org/abs/2605.27898
**作者**: Pengyu Zhu, Lijun Li, Yaxing Lyu, Qianxin Luo, Jingyi Yang, Yi Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] TACS: Trajectory-Aware Candidate Selection for LLM Jailbreak Suffix Optimization

**链接**: https://arxiv.org/abs/2608.29564
**作者**: Shiliang Xiao
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] LLM-Driven Autonomous Vehicles Inherit Human Driver Biases in Pedestrian Yielding: Results and Implications From A New Benchmark

**链接**: https://arxiv.org/abs/2609.00192
**作者**: Irem Yoldas, Martim Brand\~ao, Jie Zhang, Odinaldo Rodrigues
**来源**: cs.AI cs.CL cs.CV cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Public trust in Autonomous Vehicles (AVs) may depend not only on technical success but also on the fairness of their decision making. While a recent trend in AV research involves using general purpose "common sense" models to guide AV decision making, the degree to which these inherit human biases in driving is still understudied. Given that psychology studies have shown human driver biases exist, such as lower pedestrian-yielding rates to Black pedestrians in the US, we argue that analyses of model bias should also be part of AV evaluation. Concretely, in this paper we propose two new bias testing methodologies for Large Language Models (LLMs) and Visual-Language Models (VLMs)-"All Else Being Equal" tests and "Self-Consistency" tests-in order to assess bias in pedestrian-yielding decisions. Our findings show that both LLMs and VLMs make yielding decisions which are influenced by pedestrian gender, ethnicity, religion, disability, age, skin tone and socio-economic status. While the typ

---

### [51] Delegation Without Trust: An Empirical Gap Analysis of Identity, Authorization, and Runtime Governance in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2609.00267
**作者**: Panduranga Sai Varma Dantuluri, Jyotirmoy Sundi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous LLM agents increasingly act on a user's behalf: they hold credentials, call tools and services, and spawn sub-agents that act further on their behalf. This turns a long-standing distributed-systems question -- who is authorized to do what, on whose authority -- into an urgent and largely unsolved problem, because the component driving each agent is a language model an adversary can hijack. We argue that agent security must be evaluated under an untrusted-model assumption: a correct system is one in which a fully prompt-injected agent still cannot exceed the authority explicitly delegated to it. Against this standard we make three contributions. First, we give a threat model for multi-agent delegation centered on four adversaries -- confused deputy, token theft and replay, prompt-injection privilege escalation, and compromised sub-agents -- and derive eight security requirements a governed agent system must meet. Second, we show the gap is real: a default agent runtime modeli

---

### [52] Are Near-Tied LLM Rankings Robust to Family-DIF-Guided Benchmark Recomposition?

**链接**: https://arxiv.org/abs/2609.00482
**作者**: Qiaoyuan Zheng, Yiqu Yang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small leaderboard gaps are often interpreted as evidence that one language model is better than another, but their sign may depend on which benchmark items are included. We test this using item-level responses from five benchmarks and a family-label-free spectral approximation to multidimensional item-response theory (MIRT). In owner-disjoint folds, one owner half identifies items with low residual differential item functioning across model families (low-DIF); the resulting frozen, source- and easiness-balanced weights score models in the other half, while equally short matched-random subtests control for generic subtest variation. Full-benchmark and low-DIF rankings remain strongly correlated ($\tau_b=.900$--$.948$). Yet in four of five benchmarks, 30.9--47.1\% of cross-family pairs initially within one percentage point reverse order, exceeding their matched-random medians by 16.9--28.6 percentage points (all $p=.001$). The fifth benchmark shows no reliable excess ($-0.9$ points, $p=.

---

### [53] Who Judges the Judges? A Chinese Safety QA Benchmark for Evaluating LLM Responses and Safety Judges

**链接**: https://arxiv.org/abs/2609.01210
**作者**: Rui Yang, Shuang Huang, Junhua Liu, Ziqi Zhao, Qingzhong Yan, Yuhang Sun 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety benchmarks for large language models often assess the risk of a user query, although the outcome of question answering depends on whether the response violates a policy. This distinction is critical in Chinese harmful-content evaluation, where linguistic variation and adversarial transformations can obscure risky intent. We introduce C-SafeQA, a policy-grounded benchmark for response-level Chinese safety evaluation. It comprises 538 base queries and 8,877 adversarial queries answered by four full-model LLM deployments, yielding 37,660 query-response records labeled safe, unsafe, or disputed. Reference labels are generated through agreement-aware multi-model adjudication and blind audits of stratified subsets by three safety experts. C-SafeQA supports both evaluation of target-model safety and auditing of seven automated safety judges against shared reference labels. Unsafe-response rates range from 0.93% to 3.35% on base queries and from 11.68% to 30.05% on adversarial queries. 

---

### [54] Self-Evolving World Models for LLM Agent Planning

**链接**: https://arxiv.org/abs/2606.30639
**作者**: Xuan Zhang, Wenxuan Zhang, See-Kiong Ng, Yang Deng
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Reinforcement Learning Enhanced LLM Agents for Complex Vehicle Routing Problems

**链接**: https://arxiv.org/abs/2609.00859
**作者**: Yi Chen, Zikang Yu, Jiahai Wang, Jinbiao Chen, Jianpeng Zhou, and Zizhen Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vehicle Routing Problems (VRPs) are fundamental combinatorial optimization problems with widespread applications in various scenarios. The advanced optimization solvers can effectively solve such problems. However, modeling complex VRP variants for solvers often requires substantial domain expertise, which limits the accessibility of advanced optimization technologies. In this paper, we propose Reinforcement Learning Enhanced LLMAgents(RLEA), a multi-agent framework designed to automate the modeling of complex VRPs. RLEA introduces a lightweight neural Planner trained with Soft Q-learning to efficiently orchestrate the actions of LLM-based agents. In addition, we equip the system with an evolutionary memory module and retrieval-augmented generation, enabling the agent to leverage both accumulated experience and external solver knowledge during program generation and refinement for solving VRPs. We evaluated 48 distinct VRP variants across various solvers. The experimental results demon

---

### [56] Efficiently Estimating Optimal Hyperparameter Scaling Laws through Power-Law Entropy Search

**链接**: https://arxiv.org/abs/2609.01431
**作者**: Zhiliang Chen, Sebastian Ament, David Eriksson, Maximilian Balandat, Eytan Bakshy, Jihao Andreas Lin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optimal hyperparameter scaling laws describe how the best hyperparameters for large language model (LLM) training change with model and data scale, enabling practitioners to predict optimal configurations at production scales without expensive large-scale tuning. However, estimating these scaling laws conventionally requires exhaustive grid searches over thousands of training runs, consuming enormous computational resources. We introduce Power-Law Entropy Search (PLES), a computational cost-aware acquisition function built on multi-fidelity Bayesian optimization that efficiently estimates optimal hyperparameter scaling laws through adaptive experimentation. A key innovation in PLES is that it searches for candidates that reduce the overall uncertainty of a scaling law estimate, instead of optimizing a single objective function. At each iteration, PLES selects the candidate configuration that maximally reduces the uncertainty of the scaling law estimates per unit computational cost, nat

---

### [57] Classic AI Scaffolding for LLM Social Agents

**链接**: https://arxiv.org/abs/2609.01167
**作者**: Anatole Gershman
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can produce locally plausible social turns, but fluent next-turn generation is not enough for social simulation. Human encounters such as restaurant lunches and hotel check-ins are bounded social episodes with roles, scripts, material state, obligations, commitments, timing, and closure conditions. We present EpisodeSim, a hybrid LLM-agent architecture that represents classic-AI structures as natural-language control state interpreted by LLM calls. A World Master maintains shared reality, constructs scenes, adjudicates proposed actions, tracks effects and obligations, and controls closure. Experiments with small qualitative ablations on two held-out settings support a design claim: LLM fluency supplies local texture, but coherent social simulation benefits from persistent classic-AI-style scaffolding that organizes behavior over time.

---

### [58] Frozen Cores Need Task Signal: Fisher-Whitened Cross-Covariance for Low-Resource LLM Adaptation

**链接**: https://arxiv.org/abs/2609.00762
**作者**: Wentao Ye, Zhanming Shen, Zhiqing Xiao, Yao Ding, Haobo Wang, Gang Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parameter-efficient fine-tuning is usually framed as a question of how many parameters to update. Under a severe trainable-state budget, however, where those coefficients act is equally consequential. We study this choice through frozen-core adaptation: a calibration pass fixes left and right bases for each weight matrix, and fine-tuning optimizes only an $r\times r$ core. This removes the ability of trainable factors to repair a poor initial span and makes subspace quality directly observable. We introduce FCCA, which estimates the signed input--error cross-covariance, whitens it with diagonal Fisher moments, truncates it in the resulting local metric, maps the selected directions back, and applies thin QR to obtain stable core coordinates. Under a matched $r^2$ budget, we compare eight basis constructors on 11 tasks, four model settings, and three seeds. On Qwen2.5-3B, FCCA reaches an 83.0 macro-average, 2.3 points above the next-best matched-budget constructor, and exceeds its unwhi

---

### [59] Can LLMs Use Relational Transformer Embeddings?

**链接**: https://arxiv.org/abs/2609.00457
**作者**: Francisco Galuppo Azevedo, Clarissa Lima Loures
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Injecting frozen relational-encoder embeddings as soft tokens into a large language model (LLM) is a conceptually appealing fusion strategy: the encoder handles multi-table structure, the LLM handles language and reasoning, and no lossy text serialization is required. We test this hypothesis concretely by injecting embeddings from a frozen Relational Transformer (RT) into Qwen3.5-4B via a learned MLP projection and LoRA adaptation, trained first with supervised fine-tuning (SFT) on chain-of-thought reasoning traces and then with group-based reinforcement learning (GSPO). We evaluate across 10 binary classification tasks on 6 relational databases from RelBench, under four supervision regimes: single-task (ST), within-dataset (WD), cross-dataset (CD), and all-task (ALL). The hybrid model does not consistently outperform standalone RT: it is frequently below random, highly sensitive to serialization format and relational-token budget, and unstable under RL training. We report these negati

---

### [60] One-shot Style Transfer LLM log-probabilities for Authorship Attribution and Verification

**链接**: https://arxiv.org/abs/2510.13302
**作者**: Pablo Miralles-Gonz\'alez, Javier Huertas-Tato, Alejandro Mart\'in, David Camacho
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] Commit-first LLM judging inherits the judge's own errors

**链接**: https://arxiv.org/abs/2609.00088
**作者**: Idil Gozel
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges, models that score another system's output, can be gamed by the systems they score. Recent work identifies one defence that works: the judge solves the task itself first and commits to that answer, then accepts a candidate only if the two match. We call this commit-first judging, and ask whether shipped software implements it, and what it costs. We audit the default judge configurations of eight widely used evaluation frameworks. Of the 24 configurations in scope, none implement it. Nine implement a variant the literature measures as ineffective, and share one ancestor prompt, traceable through a copied typographical error. In a controlled experiment, an ordinary best-of-N search with no access to correct answers optimises code against one of these configurations, used exactly as documented. On an interval merging task the judge accepted 90 of 96 candidates in one seed and 93 of 96 in the other; every accepted candidate passed every test the search could see and failed a hel

---

### [62] Latent Recurrent Thoughts: Recurrent Refinement of Proposed Latents for Reasoning with Frozen LLMs

**链接**: https://arxiv.org/abs/2609.01117
**作者**: Zhaoliang Chen, Jie Fu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought reasoning unfolds in discrete token space: each step is committed as text, errors propagate, and eliciting good traces presupposes traces to imitate. Reasoning instead in a model's continuous representation space - where intermediate states are vectors rather than words - sidesteps these constraints, but leaves open how those latent states should be computed. We approach this along two axes. First, we keep a large language model (LLM) frozen and use it for what it is already good at - modeling and decoding sequences - while a small auxiliary network supplies continuous latent thoughts as input. Second, we produce those latents by recurrence: a tiny recurrent reasoner refines them over many steps, decoupling the depth of computation from the size of the model, so that the latents are a product of iterative processing rather than a single forward pass. We instantiate this as Latent Recurrent Thoughts (LRT): a task-dedicated proposer supplies base latents, a recurrent rea

---

### [63] SURE-Challenge: Evaluating Speech Evidence Before Speech-LLM Generation

**链接**: https://arxiv.org/abs/2608.27783
**作者**: Mengzhe Geng
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] RadMatch: Auditable Radiology Report Evaluation via Finding-Level Matching

**链接**: https://arxiv.org/abs/2609.01470
**作者**: Charles Corbi\`ere, L\'eo Machado, Aubin Charley, Baptiste Callard, Pierre Manceron, Corentin Dancette
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI systems are increasingly used to draft radiology reports, reliably evaluating their clinical quality remains a critical challenge. Large language model (LLM)-based metrics are now the best-correlated with radiologist judgment, yet they output a single opaque score that neither a clinician nor a model builder can easily interpret or audit. We introduce RadMatch, a multi-stage, LLM-based metric that decomposes report comparison into a structured finding-level matching with significance-aware scoring and error characterization across seven clinical attribute dimensions (status, location, severity, morphology, certainty, longitudinal comparison, and measurement). The main score is the actionable-error count, both interpretable and auditable. Candidate findings are graded correct, partial, or incorrect, and unmatched findings are counted as missed or hallucinated. Triage and actionable safety recall/precision and per-subset views add complementary, deployment-oriented lenses. Across t

---

### [65] PersianAnonymizer: Evaluating LLM-Labeled Training for Efficient NER-based Anonymization in Persian

**链接**: https://arxiv.org/abs/2609.00958
**作者**: Mohammad Hossein Shalchian, Mostafa Amiri, Amir Mahdi Sadeghzadeh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We target practical anonymization of Persian customer chats by training a compact NER model from LLM-labeled supervision and selecting the best labeler for deployment. We compare three instruction-tuned LLMs: DeepSeek-V3-0324, GPT-OSS-120B, and Qwen3-235B-A22B-Instruct-2507, to produce span annotations under a shared JSON protocol, yielding four corpora (OSS_ZeroShot, Qwen_ZeroShot, Qwen_FewShot, DeepSeek_FewShot). A MatinaRoberta-based token-classifier is trained per corpus and evaluated with token-level Precision/Recall/F1 (overall and per-class). We also report Label Coverage Recall (LCR), the proportion of gold non-O tokens predicted as non-O, and quantify cross-labeler behavior via a token-level Venn on test annotations. Finally, we contrast test-set annotation latency of the LLMs on H200 nodes with the trained NER's test-time labeling on a single RTX 3090. Results show that supervision from OSS_ZeroShot yields the strongest macro-F1 and LCR, while the resulting NER labels an enti

---

### [66] Validity-Aware Jailbreak Evaluation for Large Language Models

**链接**: https://arxiv.org/abs/2609.00498
**作者**: Qilong Wu, Sahil Wadhwa, Pranab Mohanty, Giri Iyengar, Varun Chandrasekaran
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jailbreak robustness has become central to large language model (LLM) safety evaluation, yet prevailing methodologies rely primarily on refusal behavior, semantic resemblance, and intent-matching heuristics that emphasize linguistic plausibility rather than correctness. We identify a key limitation in existing evaluations: many jailbreak intents depend on instructional validity rather than epistemic factuality, allowing realistic-looking responses to be labeled successful despite being factually or procedurally incorrect. To address this gap, we propose Sequential Epistemic and Action-Level Validation (SEAV), a verification-centric jailbreak evaluation framework that decomposes responses into ordered steps and evaluates both validity and correctness. SEAV combines LLM-as-a-judge mechanisms for semantic interpretation with retrieval-grounded verification using external knowledge sources, assessing whether generated content is factually correct, structurally consistent, and operationally

---

### [67] The Lifecycle of LLM-as-a-Judge for Large-Scale Recommendation Explanations

**链接**: https://arxiv.org/abs/2608.18300
**作者**: Emma Yanyang Kong, JJ Tan, Ishan Gupta, Lars Olds, Claire Campbell, David Fagnan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] GuidedBench: Measuring and Mitigating the Evaluation Discrepancies of In-the-wild LLM Jailbreak Methods

**链接**: https://arxiv.org/abs/2502.16903
**作者**: Ruixuan Huang, Xunguang Wang, Zongjie Li, Daoyuan Wu, Shuai Wang
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Long-Horizon State Tracking in LLMs: Executing MD5 through a Deep Sequence of Dependent Tool Calls

**链接**: https://arxiv.org/abs/2609.00012
**作者**: Dheeraj Mohandas Pai, Lu Xian
**来源**: cs.AI cs.CR cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon tasks remain uncommon in large language model (LLM) evaluation, and for a reason: when each step depends on the last, per-step accuracy that looks excellent in isolation decays catastrophically, as errors cascade and the end-to-end failure probability grows sharply with length. Existing agentic benchmarks report end-to-end success but confound this state-tracking difficulty with instruction interpretation, give no control group that isolates it, and are vulnerable to shortcuts such as a hallucinated final answer, so they cannot say why a long run fails. Whether an LLM can carry exact intermediate state across many tool calls at all is itself not well established. We test this cleanly by having the model compute a cryptographic hash, MD5, step by step: a sequence of $196$ dependent tool calls over $64$ rounds while it carries four $32$-bit words $(a,b,c,d)$ in its own context from one call to the next. Interpretation is trivial and, because we implement MD5 from scratch (RF

---

### [70] LEAP: Likelihood Elicitation and Aggregation for LLM-based Probabilistic Forecasting

**链接**: https://arxiv.org/abs/2609.01337
**作者**: Yufei Chen, Yiran Zhao, Xiaogang Xu, Qipeng Xie, Jiafei Wu, Zhe Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based forecasting systems have improved on real-world tasks such as financial markets and sports outcomes, largely through stronger search and tool use. Many systems still ask an LLM to read all collected evidence together and produce the final forecast. We call this design Monolithic Prediction. It can obscure how individual evidence items affect the result and collapse uncertainty across competing outcomes. We propose LEAP (Likelihood Elicitation and Aggregation for Probabilistic forecasting), which reorganizes how collected evidence is used in the prediction stage. LEAP examines each evidence item separately and elicits likelihood parameters that describe its implications for the target. An explicit prior and a deterministic probabilistic model then combine these likelihoods into a posterior distribution. This procedure supports continuous, single-choice, and multi-choice forecasts while preserving reproducible evidence contributions. We build a benchmark covering forecasting, i

---

### [71] Will the User Ever Know? Covert Indirect Prompt Injection Attacks on Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2608.30362
**作者**: Yunseok Lee, Yunji Kim, Woojin Lee
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] HBQ: Hierarchical Scaling Block Quantization with Hardware-Efficiency-Aware Design for Accurate LLM Inference

**链接**: https://arxiv.org/abs/2609.00450
**作者**: Chun-Ting Chen, Dongmin Han, Hangyeol Mun, Jake Hyun, Arnab Raha, Amit Agarwal 等 (9 人)
**来源**: cs.LG cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Block Quantization (BQ) is a promising approach for efficient deployment of large language models (LLMs), enabling low-precision computation with controlled accuracy degradation. Compared to scalar weight-only quantization (WoQ), BQ quantizes both weight and activation, offering higher hardware efficiency and end-to-end inference on a unified datapath, but its design space, spanning bit-width, block size, scaling, and numeric formats, remains underexplored. We provide hardware/benchmark results through design space exploration (DSE). We find that increasing block size improves hardware efficiency by amortizing dequantization and accumulation costs, but degrades accuracy. This trade-off limits conventional BQ methods. Motivated by this insight, we propose Hierarchical Block Quantization (HBQ). Unlike prior methods [1], [2], which use small blocks and conventional Power-of-Two (PoT) or integer-based scaling, HBQ uses large blocks to maximize efficiency and introduces low-overhead signifi

---

### [73] When Guardrails Look Effective: Construct Validity Failures in LLM Agent Commerce Evaluation

**链接**: https://arxiv.org/abs/2609.01519
**作者**: Peiying Zhu, Sidi Chang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interactive simulations increasingly evaluate policies in markets populated by language-model agents. Their outputs can look economic---prices, profits, consumer surplus, and welfare---without instantiating the behavior named in the claim. We audit this risk in a multi-turn buyer--seller testbed for configurable hotel transactions. An initial implementation reported welfare gains from two marketplace guardrails of +87.4, +35.0, and +28.8 across a Qwen2.5 1.5B--14B ladder. It also gave guarded and unguarded agents different offer schemas and choice procedures. Holding the schema and buyer chooser fixed changes the paired contrasts to +7.2, -13.9, and +23.8. The four largest 14B single-generation effects averaged +229; after three generations per profile-condition, they averaged +37.6 (95% bootstrap interval [-34.2, 109.3]), while generation residuals account for 49.9% of variation in this post-hoc probe. A seller-incentive check is non-monotone: increasing profit pressure produces less 

---

### [74] Does Runtime Topology Context Improve LLM-Generated Kubernetes Security Patches?

**链接**: https://arxiv.org/abs/2607.25995
**作者**: Farooq Shaikh
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] Investigating Linear Probe Robustness to Linguistic Register, Medical Specialty, and Corpus Shifts in Medical QA

**链接**: https://arxiv.org/abs/2609.01361
**作者**: Nishant Mishra, Ameen Abu-Hanna, Iacer Calixto
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linear classifiers trained on hidden states of a large language model (LLM), linear probes, can flag factual errors from a single forward pass. Geometrically, that implies that true and false statements separate along a stable direction in hidden state space, i.e., the truth direction. Prior work disagrees on whether this generalises across input shifts, but the disagreement is hard to interpret because cross-dataset probe transfer experiments confound several kinds of input change at once. We isolate three such variables in medical question-answering (QA): writing style (register), domain (medical specialty), and corpus (dataset). We build a benchmark using 500 MedQA entries, each rewritten into four styles (textbook, patient, clinical note, colloquial), annotated with clinical specialty, and grouped with two other exam corpora, MedMCQA and MMLU-medical, for cross-dataset evaluation. Probing four open-weight LLMs (2--8B), we find that the truth direction is largely robust to writing s

---

### [76] Validating FKG.in: Soundness Assessment in LLM-Augmented Indian Food Knowledge

**链接**: https://arxiv.org/abs/2608.29249
**作者**: Saransh Kumar Gupta, Armaan Shah, Lipika Dey, Partha Pratim Das and Ramesh Jain
**来源**: cs.AI cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] CARE: Contrastive Anchor-based Rubric Evolution for Large Language Model Post-Training

**链接**: https://arxiv.org/abs/2609.00892
**作者**: Siyuan Li, Xinxin Song, Chen Ruinian, Jingjing Fan, Tingxiong Xiao, Yangen Hu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based reinforcement learning decomposes open-ended instructions into prompt-specific, flexible rubrics, making it better suited than reinforcement learning with verifiable rewards for post-training LLMs on open-ended tasks. However, static rubrics are inevitably hacked as the policy evolves, and existing dynamic approaches introduce new problems: undirected rubric extraction, unreliable hack detection, and unbounded rubric proliferation. We propose $\textbf{CARE}$ ($\textbf{C}$ontrastive $\textbf{A}$nchor-based $\textbf{R}$ubric $\textbf{E}$volution), which grounds every rubric evolution step in a high-quality anchor response generated by a frontier model conditioned on the prompt and its rubrics. At each training step, CARE contrasts the highest-scoring rollout against the anchor, enabling two complementary mechanisms: an Adaptive branch that reactively repairs reward misspecification; and a Chase branch that proactively converts frontier-level quality gaps into sharper rubrics

---

### [78] PlanarBench: Evaluating LLM Spatial Reasoning via Planar Graph Drawing

**链接**: https://arxiv.org/abs/2606.02010
**作者**: Oleksandr Nikitin and Anna Kravchenko
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] From Production Traffic to Post-Training: Building a Self-Hosted LLM That Covers the Corporate Request Mix

**链接**: https://arxiv.org/abs/2609.01572
**作者**: Olga Tsymboi, Dmitrii Stoianov, Ramil Latypov, Danil Taranets, Daniil Dryabin, Mikhail Gashkov 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data-residency constraints force enterprises to self-host LLMs, but continuous adoption of newer models without decommissioning their predecessors expands the serving fleet, fragmenting a finite GPU pool. We consolidate traffic from over 200 internal applications onto a single model by closing quality gaps identified through production error analysis along three axes: instruction following, function-calling, and internal task distribution. Quality is tracked by offline benchmarks stratified to production traffic and scored by deterministic verifiers or calibrated LLM judges. Rather than optimising all objectives jointly, which introduces cross-domain reward interference, we train a separate GRPO expert per axis and merge them via two-stage SLERP. Each expert's reward exposes a distinct failure mode, namely semantic collapse, over-calling, and verbosity hacking, each requiring a domain-specific fix. In non-reasoning mode the recipe surpasses a ${\sim}7\times$ larger by total parameters 

---

### [80] ES-AHD: An Evolution Strategy Framework for Automatic Heuristic Design

**链接**: https://arxiv.org/abs/2609.00023
**作者**: Yutao Lai, Kezhao Lai, Hai-Lin Liu, Yuping Wang, Ping Guo
**来源**: cs.NE cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we introduce ES-AHD, a novel framework that fundamentally integrates Evolution Strategy (ES) into Large Language Model (LLM)-driven Automatic Heuristic Design (AHD). Existing evolutionary approaches predominantly rely on random, individual-level mutation, leading to blind search and an imbalance between exploration and exploitation. To address these issues, ES-AHD introduces two core mechanisms. First, Semantic Recombination via LLMs discards traditional point-to-point reproduction. By leveraging the LLM's contextual reasoning to explicitly extract core insights from top-performing individuals, the algorithm establishes a promising semantic search direction. This transforms random code mutation into targeted, center-guided sampling inspired by ES. Second, Stochastic Covariance Adaptation via Temperature Sampling dynamically addresses the exploration-exploitation dilemma. By mapping the covariance matrix in ES to the LLM's sampling temperature, the framework employs a sto

---

### [81] The Safeguard Worked. Is the LLM System Safer?

**链接**: https://arxiv.org/abs/2609.00519
**作者**: Pingyu Wu, Weiming Zhang, Nenghai Yu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safeguards in deployed LLM services are evaluated by refusal, attack success, and policy violation rates. Those rates characterize how a control performed on the requests it was tested on. A deployment has to answer a different question: how much help with harmful tasks the service still gives an attacker who keeps adapting or finds another way in. We determine what each reported result implies for that question, allowing results from different safeguard families to be compared under one deployment criterion. The evidence requirements are strongly asymmetric. One attack that obtains harmful help from the deployed service suffices to establish that such help remains, and such attacks appear repeatedly in the coded record. Establishing that little remains cannot follow from the safeguard's own numbers alone; it also requires evidence about what the surrounding system still allows after the safeguard performs its local function. Such evidence is supported or derived in only a small minori

---

### [82] DynaNDE: Dynamic Near-Data Expert Scheduling for Batched MoE Inference

**链接**: https://arxiv.org/abs/2609.00407
**作者**: Xiaoyang Lu, Belthangady Akash Vi Narayana Pai, Xian-He Sun
**来源**: cs.AR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixture-of-Experts (MoE) models enable efficient scaling of large language model (LLM) inference but suffer from substantial data-movement overhead when deployed on neural processing unit (NPU)-based systems. Near-Data Processing (NDP) provides a promising way to mitigate this bottleneck via cooperative NPU-NDP execution. However, existing NPU-NDP MoE systems do not fully account for hardware heterogeneity, dynamic expert-level concurrency, and temporal expert reuse during batched inference. This paper presents DynaNDE, a dynamic near-data expert scheduling framework that exploits NPU-NDP collaboration to accelerate batched MoE inference. DynaNDE introduces an analytical performance model that captures hardware heterogeneity, data-movement costs, and communication-computation overlap in cooperative NPU-NDP execution. Guided by this model, DynaNDE determines per-layer expert scheduling across the NPU and NDP while accounting for expert-level concurrency. DynaNDE also incorporates a reus

---

### [83] PropUQ-MAS: Propagation-Aware Uncertainty Quantification for LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.22130
**作者**: Yaokun Liu, Yifan Liu, Daniel Yue Zhang, Ruichen Yao, Zelin Li, Dong Wang
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] Emotional Labor Strategy Preferences in LLM Personas

**链接**: https://arxiv.org/abs/2609.00310
**作者**: Mohammad Saim and Tianyu Jiang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emotional labor is the effortful management of emotional displays to meet social or professional expectations. Personality traits have been correlated with emotional labor strategies, yet research on this link relies almost exclusively on self-report scales administered only in occupational settings. We investigate whether large language models injected with psychometrically grounded personas reproduce these personality-driven selection patterns across everyday social scenarios. We construct the first emotional labor strategy dataset of 500 socially situated events, each offering three behavioral choices corresponding to surface acting, deep acting, and genuine expression. We source 50 fictional characters from a large-scale personality repository and profile each through two parallel tracks: observer-rated bipolar adjective composites and in-character self-report items. Five LLMs evaluate all scenarios under both persona conditions. We find that models align more towards deep acting, 

---

### [85] Auditing Generative Audio Calls for Known-Task Audio-LLM Evaluation

**链接**: https://arxiv.org/abs/2608.27817
**作者**: Mengzhe Geng
**来源**: cs.SD cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] LLMBridge: An LLM Pipeline for End-to-end Referential Bridging Resolution in English

**链接**: https://arxiv.org/abs/2605.29048
**作者**: Lauren Levine and Amir Zeldes
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] Confess What You Know: Forget-Set Misalignment with Model Knowledge in LLM Unlearning

**链接**: https://arxiv.org/abs/2609.00605
**作者**: Miso Kim, Georu Lee, Seungwon Jeong, Woojin Lee
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine unlearning for large language models (LLMs) often assumes that a pre-defined forget set matches what the model has memorized, but this frequently breaks in realistic privacy settings where the original training data is inaccessible. We term this gap forget-set misalignment and identify two cases. In Under Unlearning, the forget set omits memorized information and leakage persists. In Out-of-Knowledge Unlearning, the algorithm is driven to "forget" knowledge the model never learned, perturbing parameters and degrading utility. Using gradient-level analysis, we show these behaviors arise from misaligned unlearning targets rather than specific optimization choices. We then propose CONfession-to-Forget-Set (CONFS), a data-blind framework that constructs model-aligned forget sets by eliciting and formalizing the model's memorized knowledge. Across synthetic, multimodal, and real-world benchmarks, CONFS approaches Gold-standard performance on several metrics and achieves a competitiv

---

### [88] TRIAGE: Three-level Routing and Intelligent Agent Guidance for Efficient Execution

**链接**: https://arxiv.org/abs/2609.01428
**作者**: Ruocan Wei
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents based on the ReAct paradigm have demonstrated remarkable capabilities in tool use and task execution. However, ReAct suffers from a fundamental efficiency problem: every query triggers a complete reasoning loop from scratch, and similar queries repeat identical steps without leveraging historical experience. We propose TRIAGE,a three-level routing framework that reduces token consumption by reusing historical execution trajectories. Its core innovation is TaaS (Trajectory-as-a-Skill), which abstracts historical execution trajectories into reusable skills, realizing 'experience as a service'. TRIAGE classifies queries into three levels: (1) Direct Reuse-identical queries, 0 tokens; (2) Skill Substitution-similar queries, 0 tokens via deterministic parameter substitution; (3) Full ReAct-novel queries, automatically stored for future reuse. In large-scale experiments on 1,007 security monitoring queries, TRIAGE achieves 62.3% token savings, with 56.0% of 

---

### [89] LLM-as-a-Demographic: Whom Sociodemographic Prompting Helps, and Whom It Hurts

**链接**: https://arxiv.org/abs/2609.00222
**作者**: Daniela Occhipinti, Andrea Piergentili, Marco Guerini
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as judges for subjective tasks, where annotators disagree and the relevant question is not only how accurate a judge is, but whose judgments it reproduces. Sociodemographic prompting conditions the judge on an annotator's demographic profile to align its judgments with the corresponding group's. We test whether this alignment emerges distributionally, comparing the predicted label distributions of 23 open-weight LLMs on three subjective tasks against those of real annotator groups, under three conditions: no demographic information, single-attribute profiles, and intersectional profiles over gender, age, race, and education. Three findings emerge. First, a judge prompted with no demographics is not perspective-neutral: models best reproduce the judgments of White, college-educated annotators. Second, demographic conditioning is asymmetric: it moves the judge toward majority groups and away from minority groups, most strongly on offensi

---

### [90] Bridging Lexical Divergence: LLM-Assisted, Cost-Efficient, Zero-shot Scientific Entity Linking

**链接**: https://arxiv.org/abs/2609.00228
**作者**: Md Rasel Khondokar, Qiao Qiao, Farjana Sultana Samia, Nhat Le, Yuepei Li, Qi Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific domain entity linking (EL) differs from general domain EL because mentions and entity names often lack lexical overlap. Another challenge is that specialized terminology is used in the scientific domain, which is rarely encountered in models pretrained on general domains. Therefore, models trained on general domains transfer poorly to scientific domains. To address this, in-domain fine-tuning is the natural remedy. However, many scientific domains lack expert-annotated data, motivating the need for a zero-human-annotation approach. Existing zero-shot methods heavily rely on LLMs to generate aliases across entire mention corpora, which incurs substantial computational cost, and those methods provide no mechanism to filter out noise from LLMs. To address these challenges, we propose Sci-ZSEL, a framework that selectively generates entity aliases with an LLM to control computational cost, and applies an ontology-aware filter to remove aliases that semantically drift toward onto

---

### [91] Don't Let the Model Write the YAML: Deterministic, Minimal-Diff GitOps Remediation from LLM-Proposed Field Changes

**链接**: https://arxiv.org/abs/2609.00227
**作者**: Pruthvi Davineni
**来源**: cs.SE cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly diagnose incidents and propose remediations. In a GitOps workflow, applying a fix means editing a version-controlled config file, and the obvious implementation, having the model author the edited file or a diff, is what practitioners reach for first. Evaluating that choice on real Kubernetes manifests, we find no text-generation strategy is safe for unattended automation. Unified diffs are unsafe: under strict patching almost none apply, but that is an artifact, since a tolerant tool (GNU patch) applies 96%, yet silently misapplies about 1 in 7 (14-20%) with no error signal. Full-file rewrite is capability-dependent: a small model corrupts the file, while a frontier model is usually correct but non-deterministic (it silently drops a field or edits a neighbor on some runs) and must regenerate the whole file, costing O(file size) per edit. We present an alternative that separates the semantic decision (which resource, field, and value) from the syntactic act of e

---

### [92] EvoSCM: Scientific Belief Revision Through Causal Model Evolution and Experimentation

**链接**: https://arxiv.org/abs/2609.01526
**作者**: Qing Zhao, Haowei Li, Weijian Deng, Pengxu Wei, Liang Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific agents must learn not only how to reason, but also what to believe. However, existing LLM agents typically express scientific hypotheses in free-form text, leaving their beliefs implicit and difficult to test or revise. We introduce EvoSCM, which equips scientific agents with explicit structural causal models that evolve as new experimental evidence is collected. EvoSCM maintains a population of competing SCM hypotheses, each encoding a candidate causal explanation of the environment, and evolves them through a closed discovery loop. In each round, the agent abduces latent mechanisms from accumulated evidence, designs discriminative interventions, and commits to falsifiable predictions that it tests through experimentation. Discrepancies between prediction and observation are inductively distilled into correction rules that revise the causal structures and mechanisms of each hypothesis, and the agent then deductively validates the revised population against accumulated evide

---

### [93] ClinTraceBench: Source-Verifiable Longitudinal Clinical Reasoning over EHR-Derived Dialogues

**链接**: https://arxiv.org/abs/2609.01111
**作者**: Huimin Wang, Zhengyi Zhao, Yutian Zhao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical LLM assistants must reason over multi-visit patient trajectories, yet whether the compact history representations used to scale them---retrieval, structured timelines, LLM summaries, agentic memory---preserve the longitudinal signal clinical reasoning needs has not been measured. We introduce ClinTraceBench: 385 MIMIC-IV-derived verified dialogues with event-ID provenance, a nine-task taxonomy (T1--T9), and L0--L4 deterministic + L5 human-audit validation (98.92\% agreement). We evaluate eight history representation strategies---a no-context floor, \textit{last-visit-only}, \textit{full-context}, BGE-M3 \textit{dense-retrieval}, two compression schemes, and two agentic-memory systems (\textit{Mem0}, \textit{A-Mem})---across four backbones (DeepSeek-V3, GPT-4o-mini, Haiku~4.5, Sonnet~4.6) on 6{,}271 questions: 32 cells, 200{,}672 predictions. Four findings: (SP4) a controlled T3 injection probe isolates compression-induced \textit{relation} loss---with the attribution sentence 

---

### [94] EDRAC: Benchmarking Arabic Dialect Reading Comprehension

**链接**: https://arxiv.org/abs/2609.01113
**作者**: Noor Abo Mokh, Kirill Chirkunov, Teresa Lynn, Nizar Habash, Reham Marzouk, Malik H. Altakrori 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dialectal Arabic (DA) remains under-resourced compared to Modern Standard Arabic (MSA), particularly for machine reading comprehension (MRC) and question answering (QA). Existing Arabic QA benchmarks primarily focus on formal written MSA or multiple-choice QA, with limited coverage of naturally spoken dialects. Here, we aim to bridge this gap. We introduce EDRAC, the first large-scale benchmark for dialectal Arabic machine reading comprehension (MRC) and generative QA, covering five major dialects: Egyptian, Moroccan, Emirati, Syrian, and Saudi Arabic. EDRAC contains 499 passages derived from naturally occurring spoken interactions and 4,977 corresponding QA pairs generated through a human--LLM collaborative pipeline combining iterative generation, LLM-as-a-judge evaluation, and human verification. We benchmark Arabic-centric and multilingual LLMs on EDRAC using lexical and semantic metrics. Our results reveal substantial gaps between semantic answer quality and dialectal fidelity, hig

---

### [95] Exploring Collaboration between a language and a non-language agent

**链接**: https://arxiv.org/abs/2609.00474
**作者**: Harini S I, Somesh Singh, Yaman K Singla, Rajiv Ratn Shah, David Doermann, Balaji Krishnamurthy
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly deployed as orchestrators that coordinate specialized subagents to solve complex tasks through natural language. However, in many important domains like game playing and robotics, the strongest available agents are not language models. Integrating non-language agents with LLMs would require \emph{verbalization}: compressing their rich continuous representations into sparse textual summaries at each interaction step. To study whether verbalization constitutes a bottleneck, we introduce \textsc{LLAMIA-Bench}, a suite of six diverse collaborative chess tasks spanning three facets: behavioral imitation, state assessment, and natural-language explanation. Each task instantiates a well-established chess problem that neither the LLM nor the chess engine can solve alone. To solve LLM collaboration with non-language agents, we introduce \emph{latent state internalization}, which projects the subagent's continuous representations directly into the LLM's token stream as lear

---

### [96] Beneath the Diff: Diagnosing and Mitigating Algorithmic Mode Collapse in Code-Level Autonomous Research Loops

**链接**: https://arxiv.org/abs/2609.00077
**作者**: Bowei He, Weixu Zhang, Yili Jin, Xue Liu
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code-level autonomous research loops (ARLs) have recently emerged as a concrete object of study in automated machine learning research. In such loops, an LLM agent proposes modifications to an experimental training pipeline, executes the modified pipeline, and retains edits that improve a verifiable in-loop metric. Although executable metrics may appear to provide a reliable signal of progress, it remains unclear whether repeated metric-driven code editing leads to genuine improvements that generalize beyond the loop. We provide a systematic diagnosis of this question. Across various experiment settings, we identify a robust failure mode that we call \textbf{algorithmic mode collapse}. In this regime, surface-level edit diversity remains stable, but semantic and mechanism-level diversity collapse: the agent continues to edit different lines of code while repeatedly proposing the same kinds of algorithmic changes. This collapse is accompanied by a widening gap between in-loop metric gai

---

### [97] The Answer Is Not the Argument

**链接**: https://arxiv.org/abs/2609.00264
**作者**: Will Yeadon, Sergio Ju\'arez, Paul Mackay, T. J. Dowling, Elise Agra, Oto-obong Inyang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-thought monitoring is proposed for AI oversight, yet evaluations often provide monitors with a trusted reference answer. We ask whether answer access improves reasoning verification or mainly exposes incorrect conclusions. We collected 237 step-numbered solutions to 79 Humanity's Last Exam physics questions from three frontier models, with no inserted errors, and independently labelled final-answer correctness and the first false step. The reference standard combined physicist annotations, an independent LLM debate, and source-masked adjudication. This yielded 24 critical traces in which the answer was correct but the trace contained a genuine error. 8 LLM monitors evaluated traces blind, with an unverified or certified answer, or after a blind commitment. Certification raised mean balanced accuracy from 0.637 to 0.796, while exact first-error localization rose from 0.261 to 0.379. Certification changed recall (the fraction of error traces flagged as erroneous) from 0.653 to 0

---

### [98] Predicting Program Exit Code with LLMs and Programming Language Semantics

**链接**: https://arxiv.org/abs/2609.00579
**作者**: Lara Marinov, Aditya Thimmaiah, Jayanth Srinivasa, Junyi Jessy Li, Milos Gligoric
**来源**: cs.PL cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown proficiency in various software engineering tasks, such as code generation and translation. However, a key limitation in their performance may be their (lack of) understanding of programming-language semantics. Even when explicit semantics are given, it remains unclear whether LLMs apply those rules or lean on priors learned during pre-training instead. We study if LLMs lean on priors or given semantics with a novel task--Program Executability Prediction (PrEx)--that asks models to predict whether a program is semantically valid or invalid (and, if invalid, which formal rule it violates) given the program's syntax and operational semantics. Because PrEx requires both valid and invalid programs, we build a dataset with systematically generated invalid transformations derived from valid programs. We evaluate open-source coding LLMs under two semantic formalisms and two semantic shifts across Human-Written, LLM-Translated, and Fuzzer-Generated progr

---

### [99] Latent Mechanisms of Language Control in Multilingual Language Models

**链接**: https://arxiv.org/abs/2609.00325
**作者**: Ryo Mitsuhashi, Sabri Boughorbel, Majd Hawasly
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multilingual large language models can exhibit unintended code-switching -- unnecessarily alternating between languages during generation. We present a comparative study of three methods that identify language-controlling latents in cross-layer transcoders: activation value-based selection (ValSel), activation frequency-based selection (FreqSel), and LLM-generated latent annotation-based selection (AnnSel). To evaluate the efficacy of these methods in identifying language-controlling latents, we introduce two multilingual benchmarks that exhibit code-switching for fine-grained analysis of language steering across seven languages. Through targeted intervention experiments on Gemma-2-2B and Qwen3-4B, we find that all three methods effectively manipulate generation language, with FreqSel achieving the strongest overall performance, while AnnSel offering interpretable latent selection through explicit language annotations. A knock-out analysis suggests the methods select non-overlapping bu

---

### [100] Parsing the Stream: A Live Trace Model for Long-Horizon Agents and Their Observers

**链接**: https://arxiv.org/abs/2609.01466
**作者**: Egor Pakhomov and Erik Nijkamp
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A long-horizon agent's trace outgrows both of its consumers: the human observer monitoring the run, and the agent itself, whose bounded context the trace must be folded back into. We present a live trace model, an append-only event ledger folded incrementally into typed run state and compiled into per-consumer views, and evaluate it for both consumers against deterministic ground truth. For the observer side, evaluated with an LLM reader as proxy, the compiled view answers monitoring questions using approximately 14x and 15x fewer input tokens (by reader) and at 5-7x lower cost than a budget-capped single-call reading of the raw trace, with higher accuracy (0.85-0.87 versus 0.48). Because the questions were co-designed with the view schema, we treat the token and cost reduction, conditional on schema coverage, as the transferable result. For the agent, on 120-link sequential-dependency tasks, mechanisms that maintain the task's running statistic in per-step state succeed where full-con

---

### [101] NSIDDx: A Design Framework for Neuro-Symbolic, Practitioner-First Differential Diagnosis in Low-Resource Settings

**链接**: https://arxiv.org/abs/2609.00256
**作者**: Aarav Singh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based diagnostic systems achieve high semantic accuracy on benchmarks, but open-ended evaluation on clinically uncommon presentations reveals a systematic gap between headline accuracy and verifiable clinical reliability. We evaluate an LLM+rare-disease-RAG pipeline across two cohorts and show that the paradigm produces confident outputs that are frequently unverifiable and systematically resistant to clinician interrogation. We present NSIDDx (Neuro-Symbolic Integrated Differential Diagnosis System), a design framework arguing that DDx systems in low-resource settings must treat the clinician as an active reasoning agent. We instantiate this through a neuro-symbolic pipeline with ternary symptom encoding, contradiction detection, audit strings, and practitioner override - running offline on consumer hardware. We distill five design principles for clinician-in-the-loop clinical NLP and invite the prospective studies needed to validate the claim at scale.

---

### [102] Topological Steering

**链接**: https://arxiv.org/abs/2609.00597
**作者**: Beno\^it Gu\'erand and Tan Minh Nguyen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid rise of large language models (LLMs), controlling undesirable model behaviors has become increasingly important. Existing behavioral control methods typically intervene directly in activation or feature space, but such approaches can be sensitive to outliers, distributional shifts, noise, and other local perturbations. Motivated by Topological Data Analysis (TDA), which captures global rather than purely local structure, we propose Topological Steering, a new framework for steering LLM behavior through the topological representation of activation spaces. Using persistence diagrams, our method connects activation-based steering with TDA and enables more robust behavioral control. We show that Topological Steering consistently modifies LLM behavior across multiple model families and model sizes.

---

### [103] Compressing AI Traffic: Standardized Neural Network Coding of Visual-Token Representations in Split Vision-Language Inference

**链接**: https://arxiv.org/abs/2609.01200
**作者**: Reza Heidari, Hamed R. Tavakoli and Juho Kannala
**来源**: cs.CV eess.IV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When the visual encoder and the language decoder of a vision-language model (VLM) run on different compute nodes, the intermediate visual-token embeddings become a communicated payload rather than an internal activation. We call such machine-consumed intermediate tensors AI traffic and ask how far they can be compressed with a standardized, training-free codec. We insert ISO/IEC 15938-17 Neural Network Coding (NNC) round trips on the complete visual interface of a Qwen3-VL-8B-Instruct video question answering pipeline, comprising the main visual-token representation and the DeepStack feature streams, while leaving weights, prompts, and generation untouched, and sweep the quantization parameter (QP) over a wide rate range. Closed-ended Video-MME accuracy remains close to the uncompressed reference up to a 98% reduction of the transmitted BF16 tensor and only then collapses; open-ended MLVU generation shows the same plateau-and-collapse profile under an LLM judge. This robustness is not 

---

### [104] Conversation Coach: A Voice-enabled AI System that Helps Practice Difficult Workplace Conversations

**链接**: https://arxiv.org/abs/2609.00441
**作者**: Fanyou Wu, Suraj Maharjan, Ainur Yessenalina, Dennis Xu Chen, Rahul Srivastava, Srinivasan H. Sengamedu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective manager-employee communication is critical for retaining high performers and developing underperformers, yet training managers in these skills remains costly. Text-based chatbots offer a scalable approach but cannot provide realistic rehearsal: managers need to practice speaking aloud to build confidence before high-stakes conversations. In this paper, we propose Conversation Coach, a voice-first AI system that enables managers to rehearse difficult workplace conversations in a realistic spoken format. The system addresses three challenges: achieving low-latency interactions with strong language understanding, enabling adaptive conversations through configurable bot personalities that simulate different employee types, and generating personalized feedback on content and policy compliance. We compare an end-to-end speech-to-speech model with a cascaded approach combining automatic speech recognition, a large language model, and text-to-speech synthesis. The end-to-end approach

---

### [105] Measuring the Behavioral Fidelity of Long-Horizon Human Activity Simulations

**链接**: https://arxiv.org/abs/2609.01257
**作者**: Yi Fei Cheng, Fan Yang, Iremsu Bas, Koichiro Niinuma, Narishige Abe, David Lindlbauer
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-based human simulators are increasingly used for policy, evaluation, and training, they must faithfully reproduce real behavioral patterns. While prior work has examined behavioral fidelity in survey responses and dialogue, longer-horizon real-world activity remains largely unexplored. We introduce a framework for evaluating behavioral fidelity in long-horizon activity simulations across temporal granularities and levels of analysis. As a case study, we collect a 43-hour multi-camera dataset of in-the-wild office activity and compare trace-derived conditioning mechanisms: persona descriptors, few-shot exemplars, and statistical transition and time-of-day priors. We find that behavioral fidelity is not uniform across metrics: statistical priors bring activity and sequence distributions closest to real behavior, yet over-fragment routines and suppress within-person variability. These findings motivate a more holistic evaluation that spans multiple metrics, temporal granularities, 

---

### [106] Disclosure-Gated User Simulation for Companion-Agent Evaluation

**链接**: https://arxiv.org/abs/2609.00982
**作者**: Yao Liu, Yu He
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Using a large language model to play the user is now standard in scalable evaluation. It has a repeatedly diagnosed failure: the simulated user is excessively cooperative, so a system under test can score by the sheer number of questions it asks rather than by making the user willing to speak. We answer with a disclosure gate conditioning information release on the companion agent's behaviour: its state is a ladder of five ordered gates, merged onto three observable depth layers. We specify, ablate, and audit it, and train a user simulator against that specification. Gating behaviour is learned from the training corpus's synthetic branch, while the real branch supplies how people speak and react; after training, the simulator need not be told at runtime which gate each item sits behind. The gate is a load-bearing component of the environment: on the English corpus of a published companion-agent benchmark (CompanionBench), once training no longer states per example which gate each item 

---

### [107] A systematic Approach to constructing a Chance-and-Risk Matrix for Semiconductor Supply Chains

**链接**: https://arxiv.org/abs/2609.01563
**作者**: Ema Salki\'c, Alexander Fichtl, Philipp Ulrich, Hans Ehm, Marta Bonik, and Georg Groh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semiconductor supply chains face escalating risks from geopolitical tensions, geographic concentration, and rapid technological shifts, yet no scalable system continuously extracts, structures, and prioritizes risk intelligence from public corporate disclosures. We present an end-to-end pipeline that retrieves corporate documents for semiconductor companies and uses large language models (LLMs) to extract the risks and opportunities they describe. It organizes these into a knowledge graph linking each item to its category, sources, and related events, then merges duplicates and ranks them with a three-layer mechanism combining an algorithmic formula, an LLM relevance adjustment, and expert validation. Applied to five companies across the value chain, the pipeline produces 76,207 scored items, of which an independent check finds 92.6% valid. The automated rankings match expert judgment at an average Spearman correlation of 0.55 for risks and 0.72 for opportunities, and the resulting mat

---

### [108] Hypotheses-Guided Self Distillation for Continual Personalization

**链接**: https://arxiv.org/abs/2609.00251
**作者**: EunJeong Hwang, Kushan Mitra, Dan Zhang, Hannah Kim, Estevam Hruschka
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As people increasingly interact with LLM assistants in daily life, continually adapting to individual preferences has become essential for effective long-term interactions. However, user preferences are rarely stated in full, and instead emerge through heterogeneous, latent, and noisy signals, with existing methods relying on raw interaction histories or costly reward-based optimization to manage personalization. We introduce HypReflect, a reliable, scalable framework for continual personalization that infers explicit, uncertainty-aware preference hypotheses from diverse user signals, reflectively refines them as new evidence accumulates, and incorporates the resulting user model through hypotheses-guided self-distillation. Experiments across three personalization settings: online personalization, multi-session interactions, and implicit behavioral signals, show that HypReflect outperforms a range of baselines, including raw-history and incremental-update methods. We further demonstrat

---

### [109] Autoresearch for Marketplace Catalogs: From Legacy Forms to AI-Native Matching

**链接**: https://arxiv.org/abs/2609.00274
**作者**: Kartik Ravisankar, Hojat Abdolanezhad, Daniel Capo, Sang Su Lee, Shishir Dash, Vijay Anand Raghavan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Two-sided service marketplaces are moving from deterministic request-form intake to AI-native probabilistic matching, enabled by large language models (LLMs) that infer intent, preferences, and latent constraints from natural language. Relying on inferred intent rather than fixed-form fields forces these platforms to regenerate the provider-side preference taxonomy underwriting matching, search, and pricing: attributes interpretable to service providers while remaining a useful signal for marketplace decisions. We present an autoresearch loop that generates this taxonomy, one occupation at a time, and has been deployed in production at a major U.S. consumer services marketplace since April 2026, spanning 132 occupations. Instead of one global hierarchy, the loop treats each occupation as an independent generation problem and runs iterative propose-evaluate-keep refinement cycles. Each candidate tag set is scored by a recalibrated six-rubric LLM-as-judge framework, and a 7-critic panel 

---

### [110] Towards a Reliable and Practical Eval Pipeline

**链接**: https://arxiv.org/abs/2609.00805
**作者**: Emma Thuong Nguyen, Abhishek Ghose
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based software systems increasingly require effective "evals" as quality gates in the development lifecycle. However, existing work typically addresses individual aspects of eval reliability rather than the full set of practical requirements. We present an end-to-end eval pipeline that combines eval checklist creation, with learned aggregation for checklist responses, to improve agreement across LLM judges and accuracy against human judgments. The framework additionally pro- vides self-consistency, explanations, and prediction uncertainty, and we empirically demonstrate its effectiveness.

---

### [111] SAGE: State-Grounded, Abstention-Aware Evaluation of Task-Oriented Dialogue Agents

**链接**: https://arxiv.org/abs/2609.00434
**作者**: Rayan Khoury, Shih-Yao Lin, Pratyush Mishra
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating task-oriented dialogue agents requires judging not merely whether a reply reads well but whether each turn advances the underlying workflow state correctly--a distinction conventional holistic LLM judges can miss because they evaluate the available context as a single unit and require one or more full-model calls per turn. We propose SAGE (State-Grounded Abstention-Aware Evaluation), which compiles a workflow specification and per-turn state diff into atomic, schema-grounded criteria and routes each through a cascade of symbolic and encoder/NLI verifiers that abstain rather than guess, aggregating criterion verdicts into a turn-level decision with an evidence trace. Its recommended operating point, SAGE-Core, decides 81--91% of criteria with only the compiler, symbolic rules, and on-device encoders--at zero paid LLM cost--while SAGE-LLM adds an optional focused-LLM fallback for open-class criteria. Across four slices spanning MultiWOZ, Schema-Guided Dialogue, and ABCD, no ev

---

### [112] Neurosymbolics for Data Engineering: Achieving Long Context Token Reduction Without Finetuning

**链接**: https://arxiv.org/abs/2609.00367
**作者**: Vishvesh Bhat
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models are increasingly deployed for sophisticated data engineering tasks such as generating structured queries from natural language, Text-to-SQL, and automating complex spreadsheet operations. However, maximizing their utility demands both higher finetuning-free accuracy and solutions to the computational bottleneck imposed by the Transformer architectures inherent quadratic (On2) time complexity. This paper introduces a novel drop-in neurosymbolic layer designed to seamlessly integrate into existing LLM backbones enhancing logical reasoning and mitigating long-context resource consumption. On the reasoning front, the layer immediately and significantly improves performance yielding an average accuracy increase of 85% across rigorous benchmarks including BIRD-CRITIC and LiveSQLBench, critically achieving these gains without any task specific finetuning or RLHF. Concurrently, we repurpose this approach to address the severe computational strain of long context inference

---

### [113] Explore More, Drift Less: Outcome-Only Reinforcement Learning Can Suffice for Long-Horizon Interactive Agents

**链接**: https://arxiv.org/abs/2609.01245
**作者**: Liming Pu, Xiaoxia Li, Yifu Liu, Teng Cao, Bin Yang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning is a natural way to post-train LLM agents for long-horizon interactive tasks judged only by end-of-task verification, yet a shared belief holds that outcome-only RL soon hits a ceiling on small open models. Recent work therefore compensates around the training with denser rewards, SFT priors, skill libraries, curated memory, or multi-agent orchestration. We argue the ceiling is an artifact of two failures of common practice. Signal starvation: group-relative RL with sparse outcome-only rewards yields a gradient only when a task's rollout group mixes successes and failures, so under-scaled exploration silences exactly the hardest, most instructive tasks. Policy drift: squeezing many updates out of a small task pool degrades the policy itself, as an unanchored objective lets the sampling distribution collapse exactly when saturation has already made informative groups rare. We present CANOPY (Coverage-ANchored On-PolicY RL), a minimalist protocol attacking both dir

---

### [114] AnalysisBank: An Expert Analysis Pattern Library for Financial Report Generation

**链接**: https://arxiv.org/abs/2609.00818
**作者**: Yajing Yang, Yunshan Ma, Kelvin J.L. Koa, Min-Yen Kan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We argue that financial report generation should operate at the analytical rather than structural level, composing content from data-derived insights rather than high-level topics or sections. To this end, we propose AnalysisBank, which distills expert reports into a reusable library of Analyses, each pairing a data signal, an analytical move, and the expert span it was derived from. At inference time, AnalysisBank matches input signals to library entries and applies the retrieved moves to compose the report. A study of Analyses distilled from 550 expert reports reveals a heavy-tailed distribution of 47-52 signal types spanning 13 move types. On two financial benchmarks across four LLM backbones, AnalysisBank increases the proportion of novel, data-grounded insights by 1.7-3.7x over structural-level baselines. Transfer to scientific writing suggests that the distinction generalizes beyond finance. Code and the distilled Analysis library are available at https://github.com/yajingyang/An

---

### [115] PersuaRL: Reinforcement Learning-Driven Multi-Expert Selection for Persuasive Dialogue Generation in Insurance

**链接**: https://arxiv.org/abs/2609.01188
**作者**: Rohan Kirti, Akash Ghosh, Aryan Vats, Niladri Ghosh, Shipra Shriparn, Roshni Ramnani 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are revolutionizing digital communication by powering conversational agents deployed across domains such as customer service, digital sales, and insurance. These agents, built on LLMs, can understand user input, retrieve relevant information, and generate coherent responses. However, while they excel at factual communication, they often lack the ability to engage in truly persuasive, context-sensitive dialogue, especially in domains like insurance, where trust and clarity are critical. Building on this need within the insurance domain, our work focuses on improving the persuasiveness of digital agents, aka LLMs. To support this, we introduce InsureDial, a Persuasive Insurance Dialogue dataset, designed to capture the nuances of persuasive communication specific to motor insurance interactions. We introduce PersuaRL, a reinforcement learning-based framework that equips LLM-driven dialogue agents with the ability to adaptively explore, select, and coordinate 

---

### [116] MIDR: Enrichment-Augmented Indexing for Multimodal Document Retrieval

**链接**: https://arxiv.org/abs/2609.01316
**作者**: Debanjan Mahata, Atharva Tendle, Daniel Preotiuc-Pietro, Yong Zhuang, Ozan Irsoy
**来源**: cs.IR cs.AI cs.CL cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval over visually rich documents has a representation problem: important content often lives in tables, charts, figures, and layout relations that plain OCR linearizes, corrupts, or omits. ColPali-family visual retrievers address this with patch-level multi-vector indexes and late-interaction scoring, keeping image-derived retrieval on the query-time serving path. We introduce MIDR (Multimodal Indexing for Document Retrieval), a training-free framework for enrichment-augmented indexing that shifts multimodal reasoning to index time. During ingestion, a multimodal LLM converts rendered pages into verified textual fields that are indexed with BM25F and optionally fused with dense retrieval, enabling text-centric serving over multimodally grounded evidence. On ViDoRe V3, MIDR Hybrid achieves 0.6219 average nDCG across five English domains, a 23.0% relative gain over BM25, remaining competitive with ColQwen2.5. On two French-document domains, enrichment bridges English queries and Fr

---

### [117] Invalidation Contracts for Cross-Episode Agent Memory

**链接**: https://arxiv.org/abs/2609.00243
**作者**: Michael Wu, Arquimedes Canedo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that cache recovery suggestions from API errors can skip re-derivation in later episodes, spending fewer tokens and fewer model calls on constraints they have already learned. Server-side data drift turns those cached fixes into silent failures, and the usual remedy, re-deriving on every episode, gives the savings back. We introduce invalidation contracts, a protocol layer that attaches version stamps and cacheability hints to every recovery suggestion so the client can evict stale entries without trial and error, and keep the rest. The contract decomposes realized savings into two independent factors: validity, the fraction of cached suggestions that remain correct after a drift event, and compliance, the fraction the planner applies on the first attempt. Validity depends only on the protocol and is vendor-independent. Compliance depends on the planner model: identical wire bytes yield 100% first-try compliance on Claude Haiku 4.5 and 11% or below on Claude Sonnet 5, which 

---

### [118] Control-Data Flow Separation: Stable Prompt Optimization in Multi-Agent LLMs

**链接**: https://arxiv.org/abs/2609.00621
**作者**: Wentao Zhang, Syed Shariyar Murtaza, Junaid Ahmad Bhatti, Utkarsh Soni, Yifan Nie, Eugene Wen 等 (7 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt optimization can improve multi-agent LLM systems, but the prompts being optimized often serve two entangled roles: generating task-relevant content and specifying execution-critical protocols, such as message routing, output formatting, and termination signals, on which the underlying code relies. As a result, a prompt edit intended to improve content generation can inadvertently corrupt the protocol and cause the entire agent pipeline to fail. Our key observation is that these two roles have different representations: execution protocols are typically structured, while task-relevant content is usually expressed in unstructured language. Based on this, we propose control-data flow separation, where execution-critical control is represented as typed, validated program objects, while task-relevant language remains the optimizable data flow for agent communication. This design allows optimizers to improve multi-agent behavior without exposing the routing or formatting interface to 

---

### [119] Does task decomposition improve automatic NLG evaluation?

**链接**: https://arxiv.org/abs/2609.01139
**作者**: Sebastian Steindl, Nikos Voskarides, Alberto Gasparin, Diego Marcheggiani
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The LLM-as-a-judge (LLMaJ) framework has emerged as a promising solution for cheap, reproducible, reference-free Natural Language Generation (NLG) evaluation. Prior work seeks to improve LLMaJ by decomposing evaluation tasks into simpler sub-tasks. In this work, we systematically compare LLMaJ methods with and without decomposition on multiple NLG datasets. We find no evidence that LLMaJ with task decomposition leads to performance gains over a fair baseline that does not use decomposition. Instead, we find that previously reported performance gains in decomposition-based LLMaJ stem from using human labels as training data, and not task decomposition itself. Also, we find that, when human labels are available, LLMaJ without using task decomposition can perform comparably to human annotators.

---

### [120] Data-Driven Persona-Conditioned Agents for A/B Test Simulation

**链接**: https://arxiv.org/abs/2609.01038
**作者**: Ziyad Benomar, Weronika {\L}ajewska, Leonardo Perelli, Saab Mansour
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A/B testing is the gold standard for evaluating product changes, but each experiment requires real user traffic, engineering effort, and weeks of measurement. We propose a simulation framework that predicts A/B test outcomes using LLM-powered agents conditioned on data-driven personas grounded in real user behavioral signals. Unlike prior work that relies on synthetic or rule-based personas, our agents are constructed from anonymized behavioral data-activity patterns, engagement signals, and inferred demographics-enabling more faithful population modeling. We frame A/B test simulation as a structured question task and systematically study (i) question design formats, (ii) the impact of persona data source and domain alignment, (iii) the trade-off between per-persona behavioral depth and population diversity, and (iv) efficient population subsampling. On a benchmark of 40 A/B tests spanning two metric types, our best configuration achieves 0.75-0.90 directional accuracy depending on the

---

### [121] Agentic programs: an emerging form of scientific software in computational materials science

**链接**: https://arxiv.org/abs/2609.00795
**作者**: Yunsung Lim, Haekwan Jeon, Jaesun Kim, Jisu Kim, Seungwu Han
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computational materials science has traditionally delegated algorithmic tasks to computers while leaving scientific judgments to humans. We argue that recent LLM-based agent harnesses enable an emerging form of scientific software, agentic programs, that combine deterministic algorithms with bounded LLM-based judgment, task-specific verification, episodic maturation, and complete delegation in production. We illustrate this concept with DeMARS, an agentic program for constructing atomistic models from experimentally measured disordered crystal structures.

---

### [122] Text Capability Loss in Vision-Language Adaptation: An Attention-Sink Diagnosis

**链接**: https://arxiv.org/abs/2609.00746
**作者**: Minsik Choi, Geewook Kim, Young Geun Kim
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuning a pretrained LLM into a vision-language model (VLM) can erode the backbone's text capability, with the damage concentrated on tasks that require following exact output rules, such as instruction following, chain-of-thought reasoning graded on a strictly parsed final answer, and similar evaluations with strict graders. We trace this gap to attention-sink corruption: VL fine-tuning perturbs the early sink position that anchors a large fraction of attention probability, and how well the base LLM preserves its sink tracks how much of the affected capability survives adaptation. Building on this view, we introduce Sink Strength, a single scalar computed on the base LLM in a few seconds on a single GPU that predicts post-VL degradation without any VL training. It consistently tracks relative degradation across the six VLM-LLM pairs and multiple format-sensitive tasks. Complementing this diagnostic, we find that post-pretraining QK-RMSNorm injection fails to reproduce the protecti

---

### [123] OpenAgentFlow: Enabling System-Wide Safety Boundaries for Heterogeneous AI Agent Fleets

**链接**: https://arxiv.org/abs/2609.00015
**作者**: Dongsheng Chen, Xiangyu Zhao, Xin Yao, Xuetao Wei
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents powered by large language models are evolving from isolated assistants into heterogeneous systems in which multiple agents, planners, controllers, and execution backends operate over the same user or enterprise environment. In such settings, safety becomes a system-level action-governance problem: deciding whether concrete agent-generated actions should be committed before they modify shared state. Existing safeguards cover prompts, tool calls, GUI actions, and agent-local behavior, but often leave enforcement fragmented, obscure risks that emerge across multi-step action flows, and provide limited support for auditability and policy evolution. We present OpenAgentFlow, a control-plane/action-plane architecture that enforces safety at the action-commit boundary. It normalizes pending GUI actions, API calls, tool calls, and LLM-generated invocations into a unified AgentEvent stream, routes each event through a shared pre-execution Policy Enforcement Point, and maintains proven

---

### [124] Workload Identification with Physical Side Channels for AI Governance

**链接**: https://arxiv.org/abs/2609.00309
**作者**: Simone Gargiulo and Gabriel Kulp
**来源**: cs.CR cs.AI cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI compute verification is one of the first tangible and tractable points for international policy aimed at AI governance. Determining whether frontier labs, or any operator, comply with agreements requires the regulating authority to discern how their compute is used. The elementary building block of AI compute is the GPU, and any activity it executes leaves a physical trace. Here, we show that an external observer can identify the class of the workload running on an NVIDIA H200 from its power draw. Unlike on-chip NVML telemetry, which can be spoofed or replayed, such a physical channel can in principle be observed independently of operator cooperation. We recorded $930$ five-second traces at $\sim 10$ MHz, covering seventeen open LLM families and twenty-five non-AI workloads. Over this corpus we separate training from inference and from non-AI computation with an accuracy of $97\%$ and a macro-averaged F1 score of $0.955$, evaluated on model families unseen during training. AI worklo

---

### [125] Enoki: Efficient Multi-Level Hallucination Detection

**链接**: https://arxiv.org/abs/2609.00581
**作者**: Elisei Rykov, Timur Ionov, Nikolay Ivanov, Maksim Savkin, Maksim Makarenko, Alexander Panchenko 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ensuring factuality remains a critical challenge for deploying LLMs in high-stakes settings. Existing hallucination detectors usually operate at a single level: claim-level methods provide interpretable factual units, while span-level methods localize unsupported text. Bridging these views is costly, as LLM-heavy pipelines require multiple decomposition and verification calls, and modular systems need additional claim-to-span alignment. We propose Enoki, an Open Information Extraction framework for multi-level hallucination detection. Enoki extracts text-anchored relational facts, verifies them against evidence, and projects unsupported facts back to hallucinated spans. This shared representation enables claim-level verification and span-level localization without requiring separate alignment. Enoki supports LLM-based, encoder-based, and rule-based extraction regimes, balancing accuracy and inference cost through a common interface. Experiments show that Enoki remains competitive with 

---

### [126] Scaling Near-Optimal SFT-RL Annotation Budget Allocation from Small to Large LLMs

**链接**: https://arxiv.org/abs/2609.01573
**作者**: Jingtan Wang, Arun Verma, Xiaoqiang Lin, Zhengyuan Liu, Nancy F. Chen, Daniela Rus 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How to divide a fixed annotation budget between supervised fine-tuning (SFT) and reinforcement learning (RL) during LLM post-training remains an open problem. Existing work characterizes only broad trends (e.g., SFT dominates in low-data regimes), lacks a principled allocation framework, and does not examine whether the optimal ratio transfers across model sizes. We frame this problem in terms of near-optimality: rather than seeking a single optimal SFT-RL ratio, we characterize the near-optimal region, the set of allocations within a specified tolerance of peak performance. Empirically, this region is wide even for small tolerances (2-10%), widens with model scale, and transfers reliably from small proxy models to large target models. This yields a practical strategy: small proxy-model experiments suffice to identify a transferable near-optimal region, eliminating the need for exhaustive large-scale search. Our results hold consistently across tasks, model families, and both preferenc

---

### [127] Agentic Empirical Asset Pricing: Methodological Foundations

**链接**: https://arxiv.org/abs/2609.00731
**作者**: Yingjian Pan, Xiaowei Ding, Kay Giesecke
**来源**: cs.AI cs.LG q-fin.ST
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in LLM agents enable a new paradigm for asset pricing, which we call Agentic Empirical Asset Pricing (AEAP): systems that autonomously conduct the scientific discovery process itself. We define AEAP and identify its core building blocks. Existing evaluation practices backtest only the outputs (factors or trades), not the autonomous discovery system that produced them. We focus on factor discovery, contributing a reference architecture, a rigorous evaluation standard for discovered factors, and a method for out-of-sample backtesting the discovery system. As a concrete instance of that architecture, we evaluate SEADS against five re-implemented baselines on two US equity panels using this standard: no single metric ranks the systems consistently, motivating evaluation on multiple axes at once. A separate rolling re-execution then asks the complementary question of whether the discovery process itself, not one static output, is reliable. We also report negative findings an

---

### [128] Topic Matching in the Wild: Benchmark and Lessons from Real-World ASR Transcripts

**链接**: https://arxiv.org/abs/2609.00330
**作者**: Saman Rahbar, Xiliang Zhu, Irvin Cardoza, David Rossouw
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In contact centers, real-time agent-assist tools determine, for each of many predefined topics, whether a live customer utterance is relevant and display a coaching card to the agent when it is. The input is noisy and challenging: ASR(Automatic Speech Recognition) transcripts of spontaneous phone conversations, which can be unclear, repetitive, and mostly lack punctuation. To systematically study this real-world task, we curate a human-annotated topic-utterance judgments dataset sourced from real call-center transcripts. We compare three types of matchers: a regex-based baseline, zero-shot sentence embedding encoders, and Gemini-based LLM matchers. In addition, two types of topic representations are studied in our benchmark:keyphrases and natural language description. Our empirical experiments highlight the superior performance of lightweight LLM matchers over embedding and regex models when equipped with natural language descriptions.

---

### [129] H2Table: Hierarchical Hypergraph-Enhanced Large Language Models for Complex Table Reasoning

**链接**: https://arxiv.org/abs/2609.01216
**作者**: Jia Ling, Yangfan Wang, Chen Tang, Haoming Tan, Yang Yang, Yi Guan 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tables are ubiquitous across diverse domains, yet reasoning over them remains a significant challenge for modern large language models (LLMs). Current approaches typically linearize tables into sequences, inherently overlooking their intrinsic two-dimensional and hierarchical structure. To address this, we propose H2Table (Hierarchical Hypergraph-Enhanced Table Reasoning), a novel framework that represents complex tables as hierarchical nested hypergraphs. To process this representation, we design a tailored hypergraph encoder to facilitate message passing between hyperedges (headers) and nodes (cells), thereby perceiving the semantic entailment relationships between them within complex tables. Furthermore, we introduce a set of learnable query vectors acting as a lightweight bridge to extract representative structural embeddings from the encoder into the LLM. Experimental results demonstrate that our approach effectively handles complex table question answering tasks with hierarchical

---

### [130] The Visual Insensitivity Gap: Diagnosing When Vision-Language Models Fail to Use Visual Evidence

**链接**: https://arxiv.org/abs/2609.00868
**作者**: Genpei Zhang
**来源**: cs.CV cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models are evaluated by aggregate accuracy on multimodal benchmarks, a practice that implicitly assumes the model uses its visual input. We show this assumption fails on 40%--97% of samples across six VLMs and three perceptual benchmarks: blurring the question-relevant visual region leaves the next-token distribution nearly unchanged. We name this phenomenon the Visual Insensitivity Gap and quantify it with a per-sample Visual Sensitivity Index (VSI). The gap is a property of samples, not of models: VSI ranks correlate across models (grand-mean Spearman rho=+0.40, permutation p<10^-3), so the same samples are flagged insensitive by VLMs sharing no architectural detail beyond a contrastively pretrained vision tower. The mechanism is concrete: on the insensitive samples, a linear probe on each model's own vision tower distinguishes perturbed from clean images at 0.72--0.79 accuracy, yet the model's argmax token changes on only 2%--11% of the same samples, an encoder--LLM 

---

### [131] WorldBench: Culturally Grounded Benchmark for Multilingual Agents

**链接**: https://arxiv.org/abs/2609.01056
**作者**: Leonardo Ranaldi, Sherrie Shen, Jushi Kai, Alexandra Birch
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the growing use of LLM-powered agents to solve multi-step tasks in complex environments, existing benchmarks rarely test state preservation, performance across languages, and application to realistic, grounded scenarios. To address these concerns, we present WorldBench: a comprehensive, multilingual benchmark of genuine, persona-grounded everyday workflows, where agents can act in a sandbox via structured actions. WorldBench comprises 1,600 tasks across seven languages and eight cultures, filtered and refined through feedback from human annotators with language- and culture-specific expertise. For evaluation, we extend metrics from previous works and introduce Constrained Task Success (CTS), which combines natural language instructions and testbeds to score task completion, minimal modification, and other complementary metrics through deterministic and LLM-as-a-Judge evaluations. Our experiments show that frontier models reach only 49.2% CTS, with all models demonstrating large

---

### [132] Can LLMs Design Video Coding Tools? A Case Study on Planar Mode

**链接**: https://arxiv.org/abs/2609.01535
**作者**: Yingwen Zhang, Meng Wang, Liqiang He, and Shiqi Wang
**来源**: cs.MM cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper explores whether large language models (LLMs) can design video coding tools, a highly challenging task due to the intricate algorithmic coupling of tool modifications. In particular, we present an empirical case study on the Planar mode, a long-standing intra prediction tool in video coding standards. Our experiments operate within a generation-and-evaluation loop, with the LLM generating new Planar predictors, encoder trials evaluating their coding performance, and the LLM re-generating refined implementations based on the evaluation feedback. We first examine directly replacing the default Planar mode in the Fraunhofer Versatile Video Encoder (VVenC) under its faster preset. Experimental results demonstrate that the LLM-generated mode can outperform the conventional Planar mode on this lightweight toolset, achieving 0.18% bitrate savings with 0.4% complexity overhead on the standard benchmark. We further extend our evaluation to the Enhanced Compression Model (ECM). Levera

---

### [133] Births are difficult to predict even with rich survey and full-population register data

**链接**: https://arxiv.org/abs/2609.01194
**作者**: Elizaveta Sivak, Emily M. Cantrell, Thomas Emery, Javier Garcia-Bernardo, Flavio Hafner, Kasia Karpinska 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Major life events have proven difficult to predict. Does this reflect limits of theory, data, and algorithms, or the large role of chance? We examine one outcome - having a child within three years - through a near-ideal setting for prediction: a data challenge where 147 researchers predicted births for Dutch residents aged 18-45, using survey data and full-population registers. Methods ranged from logistic regression to a large language model and transformers. Predictions were moderately accurate (best F1: register 0.59, survey 0.76); advanced models did not outperform classical ones; and the larger registers did not beat the survey. Simulating the stochastic biology of conception and pregnancy, we estimated a predictive ceiling (survey F1 ~ 0.86-0.94, register 0.88-0.96). Observed performance falls short of this ceiling, implicating imperfect data, methods, and unmodelled chance, while the ceiling itself shows that chance in reproduction alone sets a non-trivial limit on predicting i

---

### [134] Harness-of-Harness: Multi-Day Autonomous Software Development with Continual Improvement

**链接**: https://arxiv.org/abs/2609.01481
**作者**: Haoyang Yan, Min-le Su, Hangfan Zhang, Zhanhao Li, Chen Zhang, Shao Zhang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper studies autonomous software development, in which LLM-based coding agents transform high-level requirements into complete, functional, and usable software systems without human intervention. We introduce Harness-of-Harness (HoH), a framework that enables coding agents to continually improve software during autonomous development. HoH operates on existing coding-agent harnesses, and organizes their executions into iterative planning-coding-testing loops. To sustain improvement across loops, HoH balances repair with capability growth, scopes development into small and verifiable increments, separates implementation-time testing from independent evaluation, and constrains verifiable outputs rather than prescribing agent workflows. It progressively exposes deliverables, role-specific tools, and skills, encourages reuse rather than recreation, and maintains versioned project histories. On GameCraft-Bench, FrontierSWE, and ProgramBench, three harness-model pairs (Codex with GPT-5.

---

### [135] The Constitutional Coverage Trilemma in AI Governance

**链接**: https://arxiv.org/abs/2609.01275
**作者**: Natalija Mitic, Soona Sedahmed A. O., Mamadou Selly Ly, Moustapha Cisse
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier AI systems function as \emph{constitutional institutions}: each deployed model encodes an implicit ranking among safety, helpfulness, honesty, autonomy, and equity. We ask whether the supply of frontier constitutional types covers human demand. Combining a paraphrase-controlled audit of the as-shipped default constitutions of $23$ frontier LLM archetypes with a pairwise-tradeoff study of $1{,}649$ US participants on the same instrument, we report three facts. \emph{Demand is broad}: it spans all five values, with the largest constituency under one-third. \emph{Supply is narrow and drifting}: the $23$-archetype hull occupies ${\sim}2\%$ of the demand hull under conservative noise-matched estimation ($0.10\%$ at full audit precision), no archetype puts helpfulness or autonomy first ($37\%$ of users are constitutionally homeless), and across six model families autonomy decreases in $5/6$, equity increases in $5/6$, and safety increases in $4/6$, with monotone within-family versio

---

### [136] VerNav: Verifier-First Low-Latency Vision-and-Language Navigation

**链接**: https://arxiv.org/abs/2609.00920
**作者**: Zhixin Wang, Chengzheyi Yao, Leyuan Liu, Xiaosong Zhang, Yongzhao Zhang
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-and-Language Navigation (VLN) requires an agent to navigate through unseen 3D environments according to natural-language instructions. Explicit reasoning can improve instruction understanding and semantic grounding, but autoregressive generation at every step accumulates large decision-stage latency over multi-step navigation. We propose VerNav, a verifier-first framework for low-latency LLM-based VLN. The verifier reduces decision-stage latency by replacing per-step autoregressive generation with batched action verification, while an entropy-based adaptive generator is invoked only for uncertain decisions to produce compact state evidence. To further improve navigation performance with the verifier, we introduce a two-stage alignment scheme: (i) VPO improves local action-preference alignment in static verifier training, and (ii) step-level reinforcement fine-tuning provides dense progress rewards over multi-step navigation rollouts during dynamic task execution. Experiments on 

---

### [137] TRIS: A Tri-Layer Retrieval Integrity Sieve Against Knowledge Poisoning

**链接**: https://arxiv.org/abs/2609.00470
**作者**: Muhaimin Bin Munir, Akib Jawad Ononto, Nazia Shehnaz Joynab, Bhavani Thuraisingham, Latifur Khan
**来源**: cs.CL cs.CR cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) grounds large language models in external corpora, but implicit trust in retrieved documents creates a critical attack surface: PoisonedRAG shows that a handful of crafted passages can dominate dense retrieval and steer generation toward attacker-chosen answers. We present the Tri-Layer Sieve, a middleware defense that sanitizes retrieved evidence through cross-embedding-space clustering with an independent judge model, structural filtering of trigger-payload artifacts, and LLM consistency verification. The design exploits a key weakness of retrieval-stage poisoning: a single document must satisfy one embedding geometry, one internal Trigger-Payload structure, and one generation objective - rarely all three simultaneously, a fragility that persists even against an adaptive attacker who paraphrases around it. On Natural Questions, HotpotQA, and MS-MARCO with Contriever retrieval (k=50), the Sieve reduces black-box Attack Success Rate from 67.0/87.0/6

---

### [138] Automated Tree Knowledge Graph Construction using Ontology Expansion and Retrieval from Vietnamese History Textbooks

**链接**: https://arxiv.org/abs/2609.00763
**作者**: Ket Doan Nguyen and Minh N. H. Nguyen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hierarchical Knowledge graph (KG)-based retrieval augmented generation (RAG) has emerged as a powerful approach for supporting large language models with structured knowledge. However, there are primary challenges: (i) the lack of methods for automatic KG construction using ontology expansion for low-resource languages such as Vietnamese, (ii) the absence of systematic evaluation for knowledge retrieval strategies leveraging the hierarchical structures. In this paper, we propose an end-to-end pipeline for KG construction and retrieval strategies evaluation. In the KG construction, we employ a three-phase hybrid relation extraction pipeline: intra-batch deduplication via Union-Find, approximate cross-batch search, and LLM extraction with a centroid filter that reduces prompts combined with a five-step dual-LLM validator to prevent bloated ontology. A two-tier architecture consists of unmergeable structural nodes to preserve the document structure and mergeable content nodes. The retriev

---

### [139] Human-Anchored Factuality Evaluation with Strategic Annotation

**链接**: https://arxiv.org/abs/2609.00494
**作者**: Yu Wang, Craig Erickson, Kevin Small
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based factuality judges provide scalable evaluation signals, but their metrics are often systematically biased relative to human judgments. We study human-anchored factuality evaluation under limited annotation budgets, where judge predictions on the full dataset are combined with human labels on a small selectively sampled subset to obtain statistically valid estimates. The efficiency of this approach depends critically on which examples receive human annotation: in factuality evaluation, judge-human misalignment is not driven solely by low confidence, but also by structured failure modes such as incomplete evidence, temporal mismatch, unverifiable claims, and rubric misalignment. To exploit this structure, we introduce a factuality-specific annotation policy design pipeline that uses failure-space analysis (FSA) to derive diverse predictive signals for modeling human-judge misalignment. On an internal reference-based factuality evaluation system (AutoFA) and RAGTruth, where judge

---

### [140] Joint Training Is Not Enough: Conditioned Cross-Granularity Training for Multimodal Document Understanding

**链接**: https://arxiv.org/abs/2609.00756
**作者**: Chengguang Gan, Yunhao Liang, Hanjun Wei, Qinghao Zhang, Shiwen Ni
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Mutual Reinforcement Effect (MRE) asks whether a fine, span-level and a coarse, document-level task help each other when one model handles both. We test it in multimodal document understanding on three corpora, two of receipts and one of scanned business forms, comparing single-task, joint and conditioned training, which puts one granularity's gold output in the other's prompt during training only. We build Doc-MRE, an annotation layer pairing gold field extraction (point) with four document-level facets (line), from a three-judge LLM committee under a pre-registration, validated by blind re-annotation. One predicate, fixed in advance: at a shared recipe, a regime reinforces if it beats the matched single-task model on both granularities. Mixed joint training, the arrangement prior MRE work assumes, reinforces on no corpus at the main scale: it is below both single-task models on CORD and trades one granularity for the other on the two others, as single-task tuning does. Conditione

---

### [141] Citing Less Critically: LLMs Reshape the Rhetoric and Reach of Scientific Citation

**链接**: https://arxiv.org/abs/2609.01432
**作者**: Yixuan Liu, Lin Chen, Zhuoqi Liu, Jianglin Lu, Dakota Murray
**来源**: cs.DL cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific citations carry rhetorical intent. Scholars may cite prior work positively (supporting), negatively (contrasting), or neutrally (mentioning). As large language models (LLMs) increasingly assist scientific writing, whether they reproduce citations with the same rhetorical intent as humans remains unclear. We introduce a masked-citation task to compare human and LLM-generated citation behavior. For each citation context, an LLM generates a replacement citation sentence, producing a counterfactual corpus directly comparable to human citation. We analyze what, whom, and how models cite, using an LLM-as-a-judge to classify citation intent and a 20-million-edge coauthorship network to measure social distance between cited authors. Across six popular LLMs and 1,746 top NLP conference papers (63k+ contexts, 132k+ citations), three patterns emerge: (1) Compared with human citation, LLMs cite significantly less critically; (2) LLMs over-cite popular and older papers, a tendency amplif

---

### [142] CaRL-EM: Cost-Aware Reinforcement Learning for Entity Matching with LLMs

**链接**: https://arxiv.org/abs/2609.01195
**作者**: Chaohui Guo, Michel Klein, Zhisheng Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Entity matching (EM) requires fine-grained contextual understanding and domain knowledge. Recent work shows that large language models (LLMs) can serve as strong matchers across domains, but most methods either make independent pairwise decisions or rely on manually designed composite pipelines, thus lacking flexibility in realistic multi-candidate settings. At the same time, they typically ignore inference cost at scale. We formulate LLM-based EM with candidates as a cost-aware sequential decision problem and propose CaRL-EM, a reinforcement learning controller that manages LLM operations. Given the state of an anchor record, its candidate set, and the cost, CaRL-EM adaptively chooses among different operators (Match/Compare/Select/Decide) and model capacities to maximize a quality-cost objective. The policy interacts with abstract operators, allowing the same controller to be reused with different underlying LLM backends at inference time without retraining. Experiments on 7 benchmar

---

### [143] SCoNE: Selective Context-aware Neuron Editing for Robust Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2609.00689
**作者**: Chaewon Kim, Seo Yeon Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) is highly sensitive to retrieval noise: when retrieved documents mix informative and irrelevant context, LLMs are easily distracted, leading to hallucinations. To overcome this, we propose SCoNE (Selective Context-aware Neuron Editing), a training-free model editing approach that improves retrieval noise robustness by selectively strengthening context-aware FFN neurons that are identified by both high attribution and high cross-input variability. SCoNE requires only a small number of mining samples, no fine-tuning, and no inference-time overhead. Across various knowledge-intensive question-answering benchmarks and two LLM backbones, SCoNE consistently outperforms competitive baseline methods. Our code is available at https://github.com/HYU-ARK-Lab/SCoNE.

---

### [144] Human-AI Co-Interpretation for Responsible AI: A Hermeneutic Perspective

**链接**: https://arxiv.org/abs/2609.00334
**作者**: Behrooz Razeghi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Across law, education, policy analysis, and public moral argumentation, LLM outputs are being used often for work that requires interpretations to be justified with textual evidence and explicit normative standards. Yet a recurrent failure mode -- what I call \textit{interpretive misplacement} -- is that model-generated readings get treated as settled meanings without an explicit interpretive frame (sources, scope constraints, normative commitments), without preserving defensible alternatives, and without provenance that lets readers find the supporting passages. In such settings, the risk is not only factual error but lost accountability: readers and institutions cannot reliably assess what an output commits them to, or on what basis. Drawing on philosophical hermeneutics, this paper discusses this risk and derives design principles for structuring human-AI co-interpretation. The paper also provides a structured synthesis of recent scholarship on hermeneutics and AI, organizing this e

---

### [145] Value Over Language Model: Detecting Original Contribution in Writing

**链接**: https://arxiv.org/abs/2609.00700
**作者**: Vibhhu Sharma, Thorsten Joachims, Sarah Dean
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs have been rapidly adopted across writing tasks, prompting the development of tools for detecting LLM-generated text. Yet, these tools largely measure how much of a document's surface text was written by an LLM and aren't fundamentally designed to measure how much of the information content or ideas originated from the LLM itself rather than being supplied by the user in the prompt. In this work, we design a framework that measures how much value a person adds on top of what a language model could have easily produced by itself. The method requires no training or labeled data and never scores the document's surface text, insulating it from stylistic confounders. Instead, it extracts the document's content at increasing levels of granularity, uses an LLM to reconstruct the document from each partial representation, and compares these reconstructions with those produced from the task description alone. We call this framework Value Over Language Model (VOLM), which measures a document

---

### [146] Modelpedia: A Catalog of Model Findings for the Meta-Science of AI

**链接**: https://arxiv.org/abs/2609.01090
**作者**: Franciszek Bernat (1 and 2), Dawid P{\l}udowski (1 and 2), Micha{\l} Jan W{\l}odarczyk (1 and 2), Luca Longo (3), Jianlong Zhou (4), Andreas Holzinger (5) 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific knowledge about AI models is produced faster than the community can organize it. Every few months a new foundation model reshapes the field and hundreds of papers, blogs, and technical reports document how each behaves or fails. Yet, these findings remain scattered and effectively unretrievable. To address this gap we present Modelpedia, an automated, LLM-assisted framework that extracts findings about models from published papers, links it to the model, dataset, method, and concept it concerns, and aggregates the result into a searchable public catalog. Applying the prototype to accepted ICLR 2024 and 2025 papers, we extract over a thousand findings and, treating the catalog itself as an object of study, run a meta-analysis of how the community investigates models. Now, we invite the community to explore, contribute to, and build on the open catalog, and to help establish model findings as a shared foundation for the meta-science of AI.

---

### [147] One Policy, Any Budget: Internalizing Budget-Aware Search via Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.00813
**作者**: Xiaowei Sun, Jin Li, Yili Hong, Yikun Fu, Yanghua Xiao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While reinforcement learning has enabled LLM-based search agents to invoke external tools, existing methods train under fixed budgets and cannot adapt when constraints vary at deployment. We propose AnySearch, a framework that enables a single policy to perform budget-aware search under any budget constraint through a training scaffold and curriculum reinforcement learning. In the first phase, we train the agent with explicit budget state injection and structured reasoning prompts that guide efficient allocation under linearly decaying budgets. In the second phase, the scaffold is removed and the agent learns to operate autonomously under adaptively sampled budget constraints, matching inference conditions. Both phases are optimized with a composite reward that couples answer accuracy with budget efficiency through absolute and relative signals, where an adaptive weight amplifies the efficiency signal for high-accuracy queries and attenuates it for low-accuracy ones. Extensive experime

---

### [148] CUDA-Harness: Harnessing Agentic CUDA Kernel Generation and Optimization from Natural Language

**链接**: https://arxiv.org/abs/2609.00058
**作者**: Qi Fan, An Zou, Yehan Ma
**来源**: cs.CL cs.AI cs.MA cs.PL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing high-performance CUDA kernels demands specialized knowledge in algorithm implementation, correctness validation, and hardware-aware parallel optimization, creating a substantial expertise barrier and making generating CUDA kernels directly from natural language (Text2CUDA) essential. Meanwhile, the general-purpose code generation capability of Large Language Models (LLMs) prompts a series of works exploring LLM-based CUDA kernel generation. They mainly focus on transpilation from high-level frameworks such as PyTorch to CUDA (Torch2CUDA) rather than Text2CUDA, where models must understand the high-level input semantics and handle low-level kernel implementation and validation. Additionally, these methods are vulnerable to reward hacking due to reliance on predefined test inputs. In this paper, we propose CUDA-Harness, a framework for harnessing agentic CUDA kernel generation and optimization from natural language. Specifically, we introduce Intermediate-Structured Generation

---

### [149] From Confusion to Clarity: Confusion-Aware Retrieval and Knowledge Injection for Text Classification

**链接**: https://arxiv.org/abs/2609.01564
**作者**: Manish Gupta, Chaitanya Giri, Jayasimha Talur
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) struggle to classify text into taxonomies with many semantically similar labels, as the distinctions are domain-specific and not captured by pre-training. To handle large label spaces, a common approach retrieves top-$K$ candidate labels by embedding similarity and prompt the LLM to choose among them. However, top-$K$ retrieval reduces the number of candidates but does not help the model tell similar ones apart. When two similar labels both appear as candidates, the model lacks the signal to choose correctly between them. We propose a framework that (1) identifies which label pairs the model struggles to distinguish, (2) expands the candidate set to include confusable labels, and (3) generates targeted rules to differentiate between similar candidates. The framework requires no fine-tuning, and the generated rules transfer to smaller, cheaper models. On three benchmarks (WOS, Flipkart, LEDGAR), our approach improves Macro F1 by up to 10.0pp over retrieval b

---

### [150] The Irreversibility Budget: Fleet-Level Risk Accounting and Admission Control for Agent Operating Systems

**链接**: https://arxiv.org/abs/2609.00275
**作者**: Bardia Mohammadi, Laurent Bindschaedler
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fleets of LLM agents now externalize effects that cannot be fully undone: they move money, deploy code, delete data, and disclose information. Current controls check one effect at a time, so a fleet of individually authorized agents can overdraw its principal's risk under a shared trigger while every local gate stays correct. We propose the irreversibility budget, a cumulative account of residual value-at-risk that a trusted runtime maintains for each principal across agents, workflows, and tenants. Treating irreversibility as a first-class resource, the runtime charges each effect its residual loss below the agent and denies the marginal effect once the aggregate would overdraw the budget. Getting the price right is hard, because effects are heterogeneous, adversarially declared, and correlated. We perform a controlled study in which per-effect gates admit fleet-level overdraws of up to 48 times the tenant's risk limit while the budget holds every correctly charged run within that lim

---

### [151] RecalibrateGPT: AI Fatigue Resilient Conversational Interfaces

**链接**: https://arxiv.org/abs/2609.00506
**作者**: Nikhil Wani
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are powerful, but their interfaces often devolve into a type $\rightarrow$ read $\rightarrow$ retype loop, creating conversational AI fatigue, cognitive load, and eventual task abandonment. To mitigate this, we present RecalibrateGPT, a system introducing five cross-turn operators (Anchor, Replay, Delta, Scope, and Steer) that each target a distinct fatigue type, recalibrating LLM responses through a structured panel by acting on the full conversation history with a single click. Users invoke these operators through the AssistiveButton in one of three operator palette layouts: Vertical, Arc, or Tablet. We conducted two pilot studies with the same 12 advanced LLM users. An initial formative qualitative study identifies a taxonomy of four fatigue types (retyping, scanning, decision paralysis, and context drift) and derives two design objectives for RecalibrateGPT. A follow-up quantitative evaluation finds it reduces perceived cognitive workload by half (NASA-TLX = 2

---

### [152] Can LLMs Discover Scientific Laws in Real and Parallel Worlds?

**链接**: https://arxiv.org/abs/2609.01552
**作者**: Yiming Huang, Ziche Liu, Zhuohang Wu, Yiqian Wang, Junxia Cui, Xinkai Zou 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific equation discovery has long been central to scientific progress, proceeding through iterative cycles of hypothesis generation, observational testing, and refinement under scientific constraints. As LLM capabilities advance and their role in AI for Science expands, it remains an open problem whether they can genuinely discover scientific laws and how this ability should be evaluated. Existing evaluations, however, often either simplify discovery through synthetic settings or reuse published targets that may already be familiar to LLMs. We therefore introduce SCILAWS-BENCH, a benchmark for scientific law discovery built from published research and real scientific data. It comprises 118 problems drawn from 381 scientific papers, covering 291 candidate laws and roughly 8M real data points across six scientific disciplines. Each problem is instantiated in two complementary settings: (1) SCILAWS-REAL asks models to propose laws from fixed real observations and evaluates held-out p

---

### [153] From Detection to Refusal: Safer LLMs via Circuit-Guided Weight Scaling

**链接**: https://arxiv.org/abs/2609.00051
**作者**: Kuan-Lin Chu, Chung-En Sun, Tsui-Wei Weng
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite extensive alignment efforts, Large Language Models (LLMs) remain vulnerable to generating unsafe content under adversarial prompting, yet the internal mechanisms by which safety behaviors are implemented remain poorly understood. We study LLM safety from a mechanistic interpretability perspective and characterize a multi-stage *safety circuit* that organizes refusal behavior, consisting of (i) $\textbf{Harmful Detection Heads}$ that respond to harmful inputs, (ii) $\textbf{Safety Neurons}$ that mediate and stabilize safety signals in the residual stream, and (iii) $\textbf{Refusal Heads}$ that translate these signals into safe response generation. Using targeted attention-head and neuron-level interventions, we provide causal evidence consistent with this circuit organization, showing that suppressing upstream Harmful Detection Heads disrupts downstream refusal behavior and that safety neurons mediate this interaction. We validate that this decomposition recurs across multiple 

---

### [154] Harness Engineering: Anatomy, Architecture, and Evolution of Coding Agents -- A Source-Code Study of Eleven Systems

**链接**: https://arxiv.org/abs/2609.00006
**作者**: Paul Barbaste, Tristan Darrigol, Germain Vu, Tom Wiltberger
**来源**: cs.SE cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent is a model plus a harness -- the runtime that couples an LLM to the world through a loop, tools, context management, safety controls, orchestration, and extension surfaces. Harness engineering, named as a discipline in early 2026, is the design and evolution of that runtime. This paper gives the young discipline its most comprehensive empirical foundation to date: a source-code anatomy of eleven production coding harnesses (Claude Code, Codex CLI, Gemini CLI, Mistral Vibe, OpenHands, Aider, Mini-SWE-Agent, Hermes, Pi, OpenCode, OpenClaw), plus Omnigent, the first meta-harness, analyzed as a contrast point. We define what a harness is, map its seven canonical subsystems with the minimal and maximal implementation of each, and dissect all eleven systems along those subsystems. The audit yields 13 cross-cutting observations and a catalog of 29 recurring design patterns. Two absences survive a threefold corpus expansion: across roughly four million lines of Python, TypeScript, and

---

### [155] Towards Effective Structured Context Modeling for Conversational Recommender Systems via Dual-node Monte Carlo Tree Search

**链接**: https://arxiv.org/abs/2609.00618
**作者**: Jincheng Zhang, Chen Huang, Wenqiang Lei, See-Kiong Ng, Yang Deng
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate the role of conversational context modeling in user preference tracking for Conversational Recommendation Systems (CRSs). In this regard, we propose DREAMS, a novel tree-structured context modeling framework that explicitly captures user preference evolution throughout multi-turn interactions. DREAMS introduces two specialized node types to support the two fundamental objectives of CRSs: preference elicitation and preference exploitation. Specifically, elicitation nodes leverage Monte Carlo Tree Search (MCTS) to strategically explore conversational actions and infer latent user preferences, while exploitation nodes employ LLM-based refinement to transform the tracked preference state into structured retrieval queries for recommendation. Extensive experiments on benchmark datasets demonstrate the effectiveness of DREAMS and its design.

---

### [156] CRAFT: Fine-Tuning Pre-hoc Explainability in AI-native 6G RAN

**链接**: https://arxiv.org/abs/2609.00590
**作者**: Pranshav Gajjar and Vijay K Shah
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The next generation of mobile networks is envisioned as fully AI-native, with AI-RAN architectures embedding small language models (SLMs) to perform reasoning over real-time telemetry. The state-of-the-art training paradigms for telecom LLMs, exemplified by RANSTRUCT-style supervised fine-tuning (SFT) on curated instruction data, are limited to post hoc rationalization. Here, the explanations, when produced at all, are generated after or independently of the decision, leaving the decision process unauditable. Pre-hoc reasoning, where a causal reasoning trace is produced before the output label, is preferable, and the broader LLM reasoning literature has made real progress toward it via RL methods such as Group Relative Policy Optimization (GRPO). Here we observe that transplanting this recipe into the telecom setting runs into a cold-start barrier: SLMs either learn to output the desired format or learn to predict the label, but rarely both. We identify this barrier and propose CRAFT, 

---

### [157] Distributed Implicit Harm: A Compositional Safety Blind Spot in MLLM-Based Video Moderation

**链接**: https://arxiv.org/abs/2609.00206
**作者**: Ruotong Wang, Zihao Zhu, Siwei Lyu, Xin Tao, Baoyuan Wu
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite their growing use in video moderation, multimodal large language models (MLLMs) exhibit a compositional safety blind spot: videos composed of seemingly benign components can convey harmful meaning when interpreted as a whole. We refer to this phenomenon as Distributed Implicit Harm (DIH), where harm arises from relations among components distributed along a decomposition axis of the video, rather than from any single explicit cue. Among many possible axes, we study two representative cases: temporally distributed harm across visual segments (DIH-T) and cross-modal harm between audio and visual streams (DIH-M). Studying and mitigating DIH at scale requires data that is difficult to collect: such videos lack compositional harm annotations, evade retrieval based on local visual cues, keywords, or single-modality signals, and are consequently absent from existing safety datasets. To bridge this gap, we develop a multi-agent synthesis framework that composes individually benign comp

---

### [158] Dotting the Eye: An Intent-Driven Image Retouching Agent for Visual Focus Enhancement

**链接**: https://arxiv.org/abs/2609.01148
**作者**: Chujie Qin, Zilong Zhang, Zewei Chang, Chunle Guo, Ruixing Wang, Tao Hu 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image retouching is commonly formulated as enhancing overall visual quality through color adjustment, but in practice, it also serves to emphasize visual focus by guiding viewers' attention toward a specific subject or region. Achieving such focus-oriented retouching is inherently challenging, as it requires well-coordinated global and local adjustments to manipulate perceptual saliency while maintaining visual naturalness. This intricate process typically demands substantial professional expertise. In this study, we propose EyeControl, a MLLM-driven agent with a diffusion-based retouching executor that enables visual focus enhancement under weak user intent. With only a few clicks or coarse strokes, EyeControl directs visual attention to the intended region, effectively "dotting the eye" of the image. The core idea is to explicitly link the weak user intention with the target editing region and the corresponding tonal adjustment operations during retouching. To achieve this, the syste

---

### [159] Separating Syntax from Language: A Mechanistic Account of Translation in Multilingual LLMs

**链接**: https://arxiv.org/abs/2609.01356
**作者**: Mikhail Sonkin, Tanja Baeumel, Daniil Gurgurov, Josef van Genabith, Simon Ostermann
**来源**: cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multilingual large language models (mLLMs) achieve strong performance in machine translation, yet our understanding of the mechanisms by which they transform representations from one language to another remains incomplete. Prior work suggests that translation decomposes into separable processes within an mLLM, where conceptual content is first represented independently, followed by a production into language-specific form. In this work, we show that translation is even more modular than previously assumed and that the output language production in translation processes is actually further separable into a syntax and a surface language process. We construct controlled multilingual datasets that isolate cross-linguistic differences in word-order and use causal interventions and probing to track how representations are transformed during translation. We find that models first construct target-side word-order before realizing the target language surface form. We identify individual attenti

---

### [160] Evaluating Multimodal LLMs as Generalist Vision-Language-Action Agents for Drone Control: Commanding, Approaching, Tracking and Searching

**链接**: https://arxiv.org/abs/2609.01404
**作者**: Jaewoo Park, Minyoung Lee, Sukmin Seo, Moonbin Yim, Hyunwook Yoon, Dohoon Ryu 等 (10 人)
**来源**: cs.RO cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) are strong perceivers of images and video. We ask how far that reach extends into acting: dropping an MLLM directly into a drone's control loop, with its entire action space declared solely in the prompt. Recent systems approach this setting but increasingly narrow the model's decision-making. We widen it back. We introduce DroneCATS-Agent, an architecture where the MLLM is a swappable component, and DroneCATS, a benchmark treating the model as the independent variable. Beyond merely flying toward a pixel, our agent entrusts the model to yaw and search, deliberate when unsure, and self-declare arrival---all without fine-tuning or function-calling schemas. Evaluating frontier and open models across four core capabilities---approaching a visible target, tracking a moving one, searching outside the initial view, and commanding a multi-drone fleet---reveals that even the simplest embodied settings are far from solved. Crucially, to identify what bre

---

### [161] SinkPruner: Sink-Free Visual Token Pruning for Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2609.01004
**作者**: Shiyu Li, Zi-Yuan Hu, Shijia Huang, Yanyang Li, Yiwu Zhong, Liwei Wang
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite their strong multimodal understanding ability, multimodal large language models (MLLMs) incur substantial computational overhead when processing long visual token sequences. To reduce inference costs, recent studies have explored visual token pruning through vision-centric or text-guided strategies. However, these methods often overlook high-norm outlier tokens, i.e., tokens with abnormally large feature norms, leading to suboptimal pruning decisions. In this work, we show that such high-norm outlier tokens are highly redundant in both feature and spatial dimensions, yet are often mistakenly preserved as informative cues by existing methods. Motivated by this observation, we propose SinkPruner, a training-free visual token pruning framework for efficient MLLM inference. SinkPruner follows a coarse-to-fine design with two key modules: a visual sanitizer that filters high-norm redundancies and alleviates attention sink and attention dispersion, and a text-guided pruner that furth

---

### [162] Lightweight Adaptation of EEG Foundation Models for Stroke Motor Imagery Decoding: Domain Shift and Subject-Level Robustness

**链接**: https://arxiv.org/abs/2609.00282
**作者**: Anh T. Nguyen, Zihua Sun, and Michelle J. Johnson
**来源**: cs.CE cs.LG
**匹配关键词**: EEG, Foundation Models, Motor Imagery
**相关性评分**: 11.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motor imagery (MI) electroencephalography (EEG) decoding could support post-stroke rehabilitation, but models developed on healthy cohorts may not transfer reliably to pathological EEG. We evaluated whether Low-Rank Adaptation (LoRA) can efficiently adapt three pretrained EEG foundation models (i.e., LaBraM-base, REVE-base, and REVE-large) for binary left- versus right-hand MI decoding. Frozen-backbone head-only baselines and LoRA adaptation were evaluated using subject-wise five-fold cross-validation on the PhysioNet EEG Motor Movement/Imagery Dataset and a binary subset of the UET175 dataset comprising 30 stroke participants. On EEGMMIDB, LoRA increased accuracy to 0.822 for LaBraM-base and 0.957 for REVE-base. On UET175, all head-only models performed near chance. With LoRA, LaBraM-base remained near chance (0.499$\pm$0.009), whereas REVE-base reached 0.847$\pm$0.194 and outperformed REVE-large (0.806$\pm$0.178), indicating that increased model capacity alone did not improve stroke-

---

### [163] EEG-AS: Instance-Level Foundation Model Selection for EEG Foundation Models via Behavior Reconstruction

**链接**: https://arxiv.org/abs/2609.00653
**作者**: Yunzhen Zhang, Ruoxi Piao, Hasan Onur Keles, Mustafa Misir
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is a non-invasive technique for measuring neural activity and has been widely used in neuroscience applications. Recent advances in EEG foundation models have enabled strong performance across diverse neural decoding tasks. However, no single foundation model consistently performs best across datasets or individual EEG instances, while instance-level model selection remains largely unexplored. To address this limitation, we formulate EEG foundation model selection as an instance-level Algorithm Selection (AS) problem. We propose \textbf{EEG-AS}, an instance-level algorithm selection framework that characterizes each EEG instance using inference-available latent EEG embeddings, handcrafted neurophysiological features, and an anchor foundation model. During training, EEG-AS learns to reconstruct unavailable foundation-model behaviors from privileged prediction tokens conditioned on an anchor foundation model, while during inference it estimates these behavior

---

### [164] EEG-VID: Task-Guided Latent Predictive Pretraining for EEG Decoding and Assistive Target Selection

**链接**: https://arxiv.org/abs/2609.00566
**作者**: Guanzhong Sun, Junyi Ma, Yuxuan Wu, and Yanzi Miao
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, BCI
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose EEG-VID, a task-guided latent predictive pretraining framework for EEG decoding under session and subject shifts. EEG-VID predicts future latent EEG states from recent history using an exponential-moving-average target encoder and weak task guidance, followed by supervised fine-tuning. Across VIG-48 and BCI Competition IV-2a/IV-2b, Stage 1 improves mean accuracy in 41 of 42 matched backbone-dataset-protocol comparisons, including all 12 leave-one-subject-out settings, with a maximum gain of 16.22 percentage points. On the 48-region cross-day VIG-48 task, EEG-VID achieves 6.52% Top-1 and 30.50% Top-5 accuracy. In a separate six-participant offline robot-scene study, candidate-constrained target selection reaches 40.24% versus a 25% chance level after subject-specific calibration. These results support task-guided latent prediction as a transferable pretraining strategy for EEG decoding and scene-constrained assistive target selection.

---

### [165] NeuroPriv: Adversarial Representation Learning for Privacy in Wearable EEG Systems

**链接**: https://arxiv.org/abs/2609.00390
**作者**: Sarmistha Sarna Gomasta, Bhawana Chhaglani and Prashant Shenoy
**来源**: cs.CR cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wearable EEG systems may expose sensitive information beyond their intended health function, creating substantial risks to neuroprivacy. In this work, we show that commonly used EEG features can reveal participant identity and demographic attributes in addition to supporting the intended cognitive task. Wearable EEG is increasingly being explored for cognitive monitoring, neurological assessment, and longitudinal digital-health applications, yet many systems assume that transmitting compact spectral or spatial features instead of raw EEG provides sufficient privacy protection. Using EEGMAT as a motivating case study, we find that compact EEG features achieve a balanced accuracy of 0.788 for cognitive-state classification while enabling gender, age, and subject-identity inference with balanced accuracies of 0.858, 0.789, and 0.692, respectively. We further show that privacy-aware representation learning preserves task performance at 0.781 while reducing these inference accuracies to 0.5

---

### [166] Leakage-Audited Benchmarking Reveals Limited Evidence for Cross-Subject Auditory-Evoked EEG Vowel Perception Decoding

**链接**: https://arxiv.org/abs/2605.00865
**作者**: Xiaoyang Li, Zeyan Tao
**来源**: eess.SP cs.CL cs.CV cs.LG cs.SD q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [167] S-CEReBrO: Breaking the Memory Barrier in Continuous EEG Monitoring

**链接**: https://arxiv.org/abs/2607.27913
**作者**: Glenn Anta Bucagu, Thorir Mar Ingolfsson, Yawei Li, Luca Benini
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] ErgoAssist: Cognition-Aware Posture Feedback in Wearable Ergonomic Systems

**链接**: https://arxiv.org/abs/2609.00440
**作者**: Sarmistha Sarna Gomasta, Bhawana Chhaglani, VP Nguyen and Prashant Shenoy
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prolonged digital device use has made poor posture and musculoskeletal discomfort pervasive among knowl- edge workers. Existing ergonomic wearables rely solely on posture thresholds, frequently interrupting users during high-focus moments and leading to alert fatigue and abandonment. Yet posture and cognitive load are closely coupled, and most systems remain cognitively unaware. We present ErgoAssist, a head-worn ergonomic assistant that detects poor posture using IMU-based head tracking and estimates task-induced cognitive load using a consumer-grade EEG headband for continuous everyday use. In a controlled lab study, ErgoAssist achieves 81% posture classification and 90.2% task induced cognitive load estimation accuracy under leave-one-subject-out evaluation. In a preliminary real-time deployment, cognition-aware alerting reduces alert frequency by 81%, improves perceived usability by 43%, task performance by 25%, and improves posture correction rate by 38%, delivering fewer but bett

---

### [169] Foundation models for electricity price forecasting and battery arbitrage: Can they replace market-specific forecasting models?

**链接**: https://arxiv.org/abs/2609.00089
**作者**: Arkadiusz Lipiecki, Rafa{\l} Weron
**来源**: cs.LG econ.EM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models promise accurate forecasts with little or no task-specific training, but whether they can replace models designed specifically for electricity price forecasting remains unclear. We compare nine variants from five foundation model families, evaluated in zero-shot mode, with two state-of-the-art electricity price forecasting benchmarks in Germany, Poland, and Spain over 2021-2025. Their performance is assessed in terms of point and probabilistic forecasting accuracy, as well as economic value in battery energy storage arbitrage. Only the TabPFN models consistently and significantly outperform the benchmarks across all three markets and all statistical measures. However, this statistical dominance does not translate directly into economic dominance: TabPFN performs best under unlimited bids and riskier quantile-based strategies, whereas the Distributional Deep Neural Network benchmark is more profitable when risk tolerance is lower. Thus, foundation models cannot univers

---

### [170] MMAI Gym for Science: Training Liquid Foundation Models for Drug Discovery

**链接**: https://arxiv.org/abs/2603.03517
**作者**: Maksim Kuznetsov, Zulfat Miftahutdinov, Rim Shayakhmetov, Mikolaj Mizera, Roman Schutski, Bogdan Zagribelnyy 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] Breaking the Reasoning Horizon in Entity Alignment Foundation Models

**链接**: https://arxiv.org/abs/2601.21174
**作者**: Yuanning Cui, Zequn Sun, Wei Hu, Kexuan Xin, Zhangjie Fu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [172] Unmasking Face Embeddings: Reading, Rendering and Naming with Foundation Models

**链接**: https://arxiv.org/abs/2609.00411
**作者**: Fizza Rubab, Yiying Tong, Arun Ross
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern face recognition (FR) owes much of its success to deep neural networks that learn to extract compact identity embeddings from face images. These models are typically trained for identity discrimination, producing embeddings that are highly effective for biometric matching but largely opaque to semantic interpretation. In contrast, foundation models, pretrained on broad visual or vision--language tasks, provide rich interfaces for describing, retrieving, generating, and organizing visual content. This contrast raises a natural question: what capabilities become available when face embeddings from domain-specific FR models are made interoperable with foundation models? Building on recent work on embedding compatibility across models, we use simple pre-computed linear transformations, estimated from paired embeddings alone, to connect existing FR models with off-the-shelf foundation models. Once aligned with a foundation model, a face embedding can be 'unmasked' in multiple ways, w

---

### [173] Context Window Failures in Relational Foundation Models

**链接**: https://arxiv.org/abs/2609.00460
**作者**: Denis Oliveira Correa, Francisco Galuppo Azevedo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent Relational Deep Learning architectures have been proposed as foundation models for multi-table relational data, yet they impose constrained neighborhood budgets that force row truncation when an entity has many related records. We introduce Animus, a synthetic financial dataset in which predicting customer income requires aggregating up to tens of thousands of transactions. On the raw representation, three recently proposed models (RT, Griffin, RelGT) achieve $R^2 \le 0.18$; a single, routine, temporal pre-aggregation step recovers $R^2$ up to $0.65$. This questions whether current relational foundation models are ready for high-cardinality real-world data.

---

### [174] Do Satellites See Commuters? A Critical Benchmark of Vision Foundation Models

**链接**: https://arxiv.org/abs/2609.00661
**作者**: Ashiq Shukoor Iqbal, Wilson Wongso, Flora D. Salim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Satellite foundation models offer a globally available alternative to census data for commuting origin-destination (OD) generation, yet no study has systematically compared encoder paradigms within a single downstream pipeline. We ablate four satellite vision encoders: language-supervised (RemoteCLIP), self-supervised (DINOv3), and geographically grounded (SatCLIP, AlphaEarth) within an identical WeDAN graph diffusion framework across 1,925 US counties, 325 UK districts, and 14 global cities under five random seeds. Three main findings emerge. First, language-supervised features achieve the strongest in-distribution performance (RemoteCLIP CPC 0.602), while geographically grounded encoders transfer more reliably zero-shot: AlphaEarth improves CPC by 33% over RemoteCLIP on UK districts. Second, pretraining corpus scale alone is insufficient: DINOv3, trained on a substantially larger satellite corpus, underperforms RemoteCLIP by 0.091 CPC in-distribution and collapses to CPC 0.022 global

---

### [175] What, Where, and How: Probing Spatiotemporal Representations in Video Foundation Models

**链接**: https://arxiv.org/abs/2609.01551
**作者**: Sharon S. Musa, Fereshteh Forghani, Harrish Thasarathan, Sonia Joseph, Matthew Kowal, Konstantinos G. Derpanis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised video foundation models learn rich spatiotemporal representations, yet it remains unclear what visual concepts these representations encode, where they emerge across transformer layers, and how they are geometrically organized. In this work, we tackle these three questions through a systematic layer-wise analysis of V-JEPA 2 and VideoMAE-v2. We leverage lightweight probes trained to discover three temporally grounded properties: (i) camera motion understanding, (ii) intuitive physics, and (iii) anomaly detection. Both models encode camera motion, with best results ($>90$ ROC AUC) emerging at 60-70% of network depth, and achieve moderate anomaly detection performance ($>60$ ROC AUC), but remain near chance on intuitive-physics tasks, suggesting a limited encoding of deeper physical reasoning. Beyond classification, we find that temporal features from individual videos form smooth low-dimensional trajectories in representation space, suggesting that camera motion is not o

---

### [176] RW-LoRA: Communication-Efficient Decentralized LoRA Fine-Tuning via Random Walks

**链接**: https://arxiv.org/abs/2609.00078
**作者**: Xingran Chen, Rohit Bhagat, Ghadir Ayache, Rawad Bitar, Yanmin Gong, and Salim El Rouayheb
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parameter-efficient fine-tuning methods such as LoRA have become a standard approach for adapting large foundation models. Adopting fine-tuning to distributed settings faces several challenges. Most existing distributed LoRA methods rely on centralized aggregation, and gossip-based decentralized LoRA requires repeated synchronization among multiple model copies. Both methods incur significant communication overhead and introduce errors due to simultaneous aggregation of multiple model updates. In this paper, we take a different perspective and propose a random-walk-based LoRA fine-tuning scheme. Instead of maintaining multiple model replicas, a single model token traverses the network and is updated sequentially using local fine-tuning objectives. This design eliminates the need for global synchronization, substantially reduces communication and computation costs, and avoids aggregation errors. We provide rigorous convergence guarantees for non-convex objectives under standard assumpti

---

### [177] Panda Diplomacy: Foundation Model Pre-training across Particle Imaging Detectors for High Energy and Nuclear Physics

**链接**: https://arxiv.org/abs/2609.00611
**作者**: Samuel Young, C\'esar Jes\'us-Valls, Kazuhiro Terao
**来源**: hep-ex cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are increasingly being pursued in particle and nuclear physics, but existing approaches remain strongly tied to individual experiments through detector-specific architectures or pre-training objectives, limiting their reuse across sensing modalities. We show that a point cloud self-distillation framework yields a substantially more general sensor-level pre-training recipe. We show that the same refined architecture and objective can be independently pre-trained with minimal changes on three qualitatively different detector modalities: liquid argon time projection chamber (LArTPC), collider TPC, and water Cherenkov. Using 1,000 labeled images for downstream task adaptation, Panda V2 matches or exceeds specialized foundation-model baselines trained with orders of magnitude more supervision, matching state-of-the-art particle-clustering performance with 70x fewer labeled events on sPHENIX while substantially improving particle identification, and on LArTPC data matching 

---

### [178] Restrict, Don't Retrain: Inference-Time VLM Guidance for Zero-Shot Aerial Segmentation

**链接**: https://arxiv.org/abs/2609.00628
**作者**: Teresa DiMeola, Charles Walter, Hong Xiao
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Global welfare often depends on the correct interpretation of aerial and satellite imagery. Acting on such imagery (mapping flooded ground, crop extent, or damaged infrastructure) demands pixel-level segmentation to ensure perfect class localization. Pretrained general foundation models, when applied directly, often miss important features and cannot always find all the classes belonging to a given scene, overlooking smaller objects that matter most. We use a single consumer-grade GPU running a vision-language model (VLM) to supply this missing guidance, improving segmentation while producing structured, auditable evidence that drives the result and can be inspected on its own. We fuse three approaches: the frozen foundation model that labels every pixel, and two queries to a VLM, one to choose the classes that matter, and one to locate the small objects the base model misses. Evaluating across four aerial datasets, we see consistent gains at each stage where the base model is competen

---

### [179] Monocular Depth Estimation from a Single Image: Progress and Opportunities

**链接**: https://arxiv.org/abs/2609.01172
**作者**: Muxin Liu, Xiaoyang Lyu, Yang-Tian Sun, Yi-Hua Huang, Ziyi Yang, Peng Dai 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Monocular depth estimation has long stood as a fundamental challenge in computer vision, enabling a wide range of applications including 3D reconstruction, robotics, autonomous driving, and augmented reality. This survey traces the field's evolution from early learning-based methods to the emergence of transformative foundation models. We begin by framing the problem, distinguishing between relative and metric depth estimation, and highlighting the key challenges that have shaped a decade of research. We then present common problem formulations and introduce the most widely used datasets, covering indoor, outdoor, and synthetic data. Following this, we review major advances prior to the foundation model era, distilling core insights from influential methods that contributed to improvements in accuracy, efficiency, and robustness. The survey then turns to the recent surge of foundation-model-based approaches, categorizing them into discriminative and generative paradigms and emphasizing

---

### [180] AgentFactory: Towards Automated Agentic System Design and Optimization

**链接**: https://arxiv.org/abs/2609.01045
**作者**: Enci Zhang and Haofeng Wang and Yuesheng Zhu and Xiaole Cui and Guibo Luo
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have demonstrated remarkable capabilities as powerful components in agentic systems, enabling sophisticated reasoning and complex task execution. However, current approaches to manually designing and optimizing agentic systems heavily rely on manual effort, limiting their adaptability and scalability. Recent work has explored the automated optimization of workflow designs. However, these approaches often overlook the crucial role of model capabilities and focus on single performance metrics, failing to address real-world deployment constraints. In this paper, we present AgentFactory, a framework that jointly optimizes both foundation models and workflow structures in agentic systems while considering multiple objectives including performance, cost, and efficiency. AgentFactory leverages advanced LLMs as optimizers to navigate the vast search space of possible configurations, employing a three-stage optimization pipeline to automatically discover effective c

---

### [181] Vision-Language-Guided Pseudo-Labels for Unsupervised Domain Adaptation in Semantic Segmentation for Waste Sorting

**链接**: https://arxiv.org/abs/2609.00898
**作者**: Udo Schlegel, Shubhangi, Gabriel Dax, Sai Rahul Kaminwar, Florian Karl, Thomas Seidl
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Obtaining labeled data for semantic segmentation in applied settings (e.g., autonomous driving, industrial waste sorting) is expensive and often infeasible at scale. We present a cross-modal pseudo-labeling pipeline that enables unsupervised domain adaptation without any target-domain annotations. The pipeline is built on two core foundation models: SAM generates class-agnostic region proposals, and EVA-CLIP assigns semantic labels based on region-text similarity, with confidence filtering ensuring that only reliable pseudo-labels are used for self-training a segmentation model. As an optional extension, BLIP provides language-grounded verification for ambiguous regions, thereby improving pseudo-label quality without altering the overall pipeline. Evaluated on two domain shifts, synthetic-to-real autonomous driving and, with a primary focus, lab-to-factory industrial waste sorting, the pipeline consistently improves over source-only baselines. Our results demonstrate that pseudo-label 

---

### [182] SAM3-LoRA: Parameter-Efficient Adaptation of a Concept-Promptable Foundation Model for Multi-Class Structural Defect Segmentation

**链接**: https://arxiv.org/abs/2609.00469
**作者**: P. Malaisree, S. Youwai, S. Janrungautai, D. Amorndechaphon, P. Rojanavasu, W. Songkitti
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Promptable segmentation foundation models such as SAM3 accept an open-vocabulary text concept and return every instance matching it, but adapting them to a specialized domain by full fine-tuning is computationally prohibitive for the organizations that would benefit most. This study applies Low-Rank Adaptation (LoRA) to SAM3 for multi-class structural defect segmentation and examines both how such a model can be supervised from conventional annotation and whether the resulting efficiency gain transfers across datasets. Two contributions are methodological. First, we describe a supervision procedure that trains a concept-promptable model directly from COCO-style class-labeled instance segmentation by using the category name itself as the prompt, requiring no prompt templates, no synonym expansion, and no learned class embeddings. Second, we identify and mitigate a failure mode specific to this setting: because a conventional annotation file yields positive prompts exclusively, the model

---

### [183] Safin-1: Safety from Within through Memory-Native State Evolution

**链接**: https://arxiv.org/abs/2609.00092
**作者**: Ming Zhang, Kaisen Yang, Shu Yu, Ermo Hua, Zhekai Chen, Cheng Jin 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon complex tasks require foundation models to accumulate information, maintain internal states, and adapt over extended interactions. Safety should be an intrinsic property of the model itself, rather than a behavioral constraint relying solely on external safeguards or post-hoc alignment such as supervised fine-tuning. This motivates Safety from Within, where safety-relevant capabilities are represented and invoked through the model's native computation. We present Safin-1, a family of foundation models realizing this principle through memory routing and state evolution. Safin-1 is built on Memory-Anchor Routing across Context History (MARCH), a network architecture that maintains structured memory states and selectively retrieves relevant historical information through content-conditioned routing. It supports test-time adaptation of persistent capability states without repeatedly modifying the backbone, enabling controlled specialization over a shared foundation. We investi

---
