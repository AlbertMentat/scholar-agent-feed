# 📑 论文索引 - 2026-10-10

共 181 篇论文

---

### [1] Local Prototype Reconstruction for Text-Compatible Speech-to-LLM Bridge Pretraining

**链接**: https://arxiv.org/abs/2610.11159
**作者**: Xinnian Zhao, Chia-Hua Wu, Pu Wang, Hugo Van Hamme
**来源**: cs.CL cs.SD
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech-to-LLM systems often connect a frozen speech encoder to a frozen large language model (LLM) through a small trainable bridge. The bridge is usually treated as plumbing, but it in fact defines the geometry of the speech-to-LLM interface, and the pretraining objective decides whether that interface provides a reusable initialization for downstream tasks. We study a transferable bridge through two complementary properties: global alignment with the text side, and local lexical manifold compatibility, where bridge embeddings remain close to the frozen LLM's input-embedding neighbourhoods. We make this property measurable with a fixed, head-free, timestamp-free diagnostic that applies to any objective, and show that next-word prediction (NWP) and sentence-level contrastive pretraining do not fully capture token-level lexical compatibility. We then introduce Local Prototype Reconstruction (LPR), a lightweight training-only regularizer that requires each aligned bridge token to be reco

---

### [2] Large Language Model Turnover Undermines Screening for Artificial Intelligence-Assisted Scientific Writing

**链接**: https://arxiv.org/abs/2610.11599
**作者**: Kazuki Nakajima, Takayuki Mizuno
**来源**: cs.CL cs.AI cs.CY cs.DL cs.SI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Journals and conferences have begun to screen submitted manuscripts for text written using large language models (LLMs). The reliability of this screening rests on benchmark evaluations against a fixed set of LLM versions, while the versions in actual use keep changing. Here we quantify how this LLM turnover affects the screening of scientific manuscripts. We paired 4,000 pre-ChatGPT abstracts from the Proceedings of the National Academy of Sciences with their rewrites by 23 LLM versions from three vendors, released between June 2023 and August 2026. We then trained detectors under maintenance scenarios ranging from a detector retrained on every new version to one trained once and never updated. Detectors trained only on a vendor's past versions can collapse at the boundaries between model generations: calibrated to falsely flag 1% of human-written abstracts, they catch above 99% of rewrites just before the sharpest boundary and 3.8% just after it. Detectors trained on later versions c

---

### [3] Is In-Domain Training Enough for Fine-Grained Industrial Anomaly Understanding?

**链接**: https://arxiv.org/abs/2610.12310
**作者**: Xingwu Zhang, Duanyang Du, Huiling Zhu, Jiayue Dai, Yixiao Liu, Guozhi Liu 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A single multimodal large language model (MLLM) struggles to excel simultaneously at detection, localization, description, and reasoning in multimodal industrial anomaly understanding (MM-IAU). We show that in-domain training does not close this gap. On MMAD, a widely adopted MM-IAU benchmark, trained specialists reach at most 75.5% accuracy in defect localization, against 92.3% for human experts, and even detect anomalies less accurately than their untrained base model. Meanwhile, different MLLMs offer complementary strengths but share this weakness in fine-grained perception, so combining them alone cannot remove it. We therefore propose SiGMA, a spatially grounded multi-agent framework that divides labor between heterogeneous MLLM agents and a dedicated visual defect expert. A multimodal searcher supplies industrial knowledge and normal references, the defect expert turns query-reference comparison into calibrated anomaly evidence, and a label-free reliability controller weighs each

---

### [4] Prior or Feedback? What an LLM Uses When Adapting Neural Operators

**链接**: https://arxiv.org/abs/2610.12325
**作者**: Julian Chan, Javier Mora Jimenez
**来源**: cs.AI cs.LG physics.comp-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Do LLM scientific agents rely only on their initial task context, or do they adapt their decisions in response to experimental feedback? We study this question in neural operator adaptation, where a large language model (LLM) selects fine-tuning configurations under a limited trial budget. Across transfers within and between partial differential equation (PDE) families, the LLM achieves lower held-out test nRMSE than random search and Bayesian optimisation in nearly every matched comparison. Endpoint performance alone cannot distinguish what happens, so we verify each attribution with controlled interventions. Before observing any validation score, the LLM's first configuration already ranks near the top of the corresponding random-search pool, indicating a useful initial bias. A complementary cold-start intervention shows that the selected base learning rate shifts with the PDE description. Once feedback becomes available, reassigning validation scores among evaluated configurations c

---

### [5] LLM-IDEA: Identifiability-Driven Experimental Agent for Autonomous Discovery of Mechanistic World Models

**链接**: https://arxiv.org/abs/2610.11253
**作者**: Surya Shetty and Ulisses Braga-Neto
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are being increasingly deployed as autonomous scientists, designing experiments and inferring mechanistic world models with minimal human oversight. Yet identifiability is often overlooked: when a plateau is reached, the agent needs to know whether it is not yet capable enough or the model simply is not identifiable from the data, in which case no amount of further experimentation of the same kind can help. We propose the Identifiability-Driven Experimental Agent (LLM-IDEA) for closed-loop discovery with an identifiability engine that returns a three-way plateau verdict: capability limit, resolvable within the design class, or certified exhausted. On ODEBench, 60 of the 62 systems with free constants are identifiable at round 0; the RC circuit is certified exhausted for every experiment that protocol can run, and a harvesting model is resolvable by one added initial condition. The identifiability engine reproduces known verdicts on Lotka-Volterra, Van der Po

---

### [6] A Closer Look at Agentic BBO: Benchmarking LLM Agents for Black-Box Optimization

**链接**: https://arxiv.org/abs/2610.12183
**作者**: Ming Chen, Rong-Xi Tan, Ke Xue, Yu-Jie Zhou, Taiye Lu, Zhi-Xuan Gao 等 (10 人)
**来源**: cs.LG cs.AI cs.NE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Black-box optimization (BBO) arises in many scientific and engineering problems where objective evaluations are expensive and limited. Recent large language model (LLM) agents offer a new way to approach BBO by combining task semantics, computation, optimization tools, and feedback-driven decision making, showing great potential due to the integration with mathematically rigorous tools. However, existing agentic BBO studies use different task domains and system configurations, making their results difficult to compare and the effects of individual design choices hard to isolate. We therefore introduce AgenticBBO-Bench, a cross-domain benchmark for agentic BBO spanning synthetic functions, hyperparameter optimization, database tuning, chip design, and molecular design under a unified finite-budget evaluation protocol. In our experiments, agentic BBO achieves higher family-averaged scores than direct LLM-based methods in all five domains and outperforms the best numerical optimizers in f

---

### [7] Large Language Model-Assisted Preparation of Transportation Management Plans: A Case Study with WisDOT WisTMP System

**链接**: https://arxiv.org/abs/2610.10650
**作者**: Zihao Sheng, Pei Li, Zilin Huang, Yen-Jung Chen, Yuhao Luo, Zhengyang Wan 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Work zones are critical yet hazardous components of transportation infrastructure, requiring carefully designed Transportation Management Plans (TMPs) to ensure safety and mobility. However, TMP preparation remains labor-intensive and heavily dependent on practitioner expertise. This paper proposes a Large Language Model (LLM)-assisted framework to automate TMP content generation, leveraging the WisDOT WisTMP system as the application context. The framework fine-tunes multiple open-source LLMs across different model scales and deploys them locally to ensure data security. To support model training, we construct a domain-specific dataset from historical WisTMP documents by converting PDF files into structured question-answer pairs in JSON format. Experimental results show that fine-tuning significantly improves performance across standard text generation metrics. Further section-wise and strategy-level analyses reveal that, while LLMs achieve strong overall performance, they tend to ove

---

### [8] MemTrial: Learning When to Trust Memory in LLM Portfolio Agents

**链接**: https://arxiv.org/abs/2610.11732
**作者**: Guanghao Wu, Zhuo Cai, Shoujin Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents for portfolio management learn from experience: they credit each experience in their memory with the outcome of the decisions that used it. In financial markets, however, this outcome mostly reflects the market move shared by all decisions on that date, so the credit tracks the market rather than the experience, and these agents often do worse than simply holding the equal-weight (1/$N$) portfolio. We ask how an agent can credit an experience with what it changes, and answer it by putting memory on trial: drafts of the same decision with and without an experience face the same market, so the outcome they share cancels in their difference. Our agent, MemTrial, drafts each decision with eight combinations of its retrieved experiences, chosen by a fractional factorial design, and credits each experience with its Banzhaf value, the average of these differences. As each date occurs once and each draft is a noisy LLM sample, these credits are noisy and may n

---

### [9] Use and Disuse: Intent-Structured Experience Consolidation for Memory and Learning in LLM Agents

**链接**: https://arxiv.org/abs/2610.12124
**作者**: Xiangyi Zeng, Baihang Liu, Xutong Wang, Ze Jin, Yunpeng Li, Qixu Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The evolution of Large Language Model agents from single-task execution to long-term autonomous operation highlights the critical challenge of transforming continuous experiences into reusable knowledge. To address this, we propose Hippocam, a hierarchical memory and continual learning architecture. Hippocam draws inspiration from two characteristics of human memory: cognitive processes selectively maintain information relevant to current goals, while long-term memories form gradually through repeated consolidation. Accordingly, Hippocam structures an agent's ongoing work as nested intents. The active context remains centered on the current intent, while completed intents are consolidated into the task-relevant outcomes and state needed for subsequent work, rather than carrying forward their full working details. Concurrently, a recursive prefix consolidation mechanism repeatedly consolidates earlier history, causing long-unused experiences to become increasingly abstract. Original int

---

### [10] Poster: A Preliminary Study of LLM Distillation Inference

**链接**: https://arxiv.org/abs/2610.12137
**作者**: Edward Chen, Yuntao Du
**来源**: cs.CR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unauthorized model distillation, in which a model is trained on the outputs of a proprietary large language model (LLM), is a growing threat to model providers. We study distillation inference: determining whether a suspect model was distilled from another model or trained independently. We formulate this problem as a hypothesis test and estimate the behavior expected under each hypothesis by training shadow models: distilled shadow models learn from the teacher's reasoning traces, whereas independent shadow models learn only from reference answers. The auditor measures how closely each model predicts the teacher's reasoning outputs and then uses the shadow models to convert the suspect's score into a calibrated p-value. In a preliminary study using Qwen2.5-7B as the teacher and Llama-3.2-3B for the suspects, our test achieves a true positive rate of 1.0 at a significance level of 0.02. These results demonstrate the feasibility of using distillation inference to detect distillation att

---

### [11] SparseDecoding: Decoding-Aware Pruning for Accurate and Efficient LLM Inference

**链接**: https://arxiv.org/abs/2610.12327
**作者**: Qitong Wang, Xinwei Niu, Mingluo Su, Shanwei Zhao, Shiai Zhu, Huan Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The memory-bound nature of the decoding stage of large language model (LLM) inference incurs significant latency. Layer-wise training-free network pruning approaches guided by the Hessian have been a prominent solution to this problem, as pruning reduces the number of nonzero parameters read from memory during decoding. Nevertheless, typical methods in this line compute the Hessian using pre-collected natural sequences, whereas the model is fed self-generated tokens during decoding, creating a distribution shift between the two sequences. The Hessian calculated on the natural sequence is different from that calculated on the generated sequence. We observe that this discrepancy causes the activation distribution during generation to deviate from that used for pruning, further hurting the pruned model performance. Moreover, most existing LLM pruning methods that bring actual speedup primarily target the sparse matrix-matrix (SpMM) multiplication, providing limited support for the sparse 

---

### [12] From Investigation Failures to Reliable SOC Agents: Understanding and Improving LLM-Based Alert Triage

**链接**: https://arxiv.org/abs/2610.10608
**作者**: Saimon Amanuel Tsegai, Alex Kantchelian, Danfeng (Daphne) Yao, Peng Gao
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Security operations centers (SOCs) must triage large volumes of alerts, most of which are benign, while missed attacks can remain uninvestigated. Tool-using large language model (LLM) agents can retrieve evidence during triage, but it remains unclear how reasoning strategies determine what to gather and when an investigation is sufficient to close an alert. We study five representative approaches spanning single-pass tool use, iterative retrieval, sampled investigations, self-review, and explicit verification. To support this study, we build ALERT-BENCH, an interactive benchmark that replays enterprise telemetry through a live SIEM and requires each system to retrieve evidence. Across 1,247 alerts from a multi-stage attack scenario, every approach missed at least 40.4% of attack-related alerts. Trace analysis shows that attack alerts are more likely to be dismissed when searches return no records, same-context review has negative net correction, and dismissal receives no consistently s

---

### [13] Adapting English Quality Classifiers for Multilingual LLM Pretraining Data Selection

**链接**: https://arxiv.org/abs/2610.11585
**作者**: Vinko Sabol\v{c}ec, Bettina Messmer, Yassine Turki, Martin Jaggi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language model (LLM) pretraining highlight the role of high-quality training data in improving performance. While model-based filtering has proven effective in selecting high-quality subsets from web-scale corpora, especially for high-resource languages, low-resource languages face challenges due to limited availability of annotated data. This work explores extending quality filtering to over 100 languages by proposing a multilingual adaptation approach that converts an existing English quality classifier into a multilingual variant. Our approach proposes training a small multi-layer perceptron on top of Transformer encoder-only model embeddings, using multilingual text as input and scores obtained from English classifiers applied to machine-translated text as labels. Our 1B, 3B and 8B scale experiments show that our approach maintains the downstream LLM benchmark performance of existing multilingual model-based filtering baselines, without harming regional and

---

### [14] Long Text to Predictive Features: LLM-Guided Blockwise Feature Engineering via Executable Program Search

**链接**: https://arxiv.org/abs/2610.12390
**作者**: Ziming Dai, Dabiao Ma, Ziheng Guo, Jack Dong, Zimu Zhou
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial risk-control systems typically rely on structured-data models for efficient prediction, yet substantial valuable information remains embedded in unstructured long text. Extracting this information through manual feature engineering is labor-intensive, while requiring a large language model (LLM) to process every real-time input may not meet practical deployment requirements. To address this challenge, we propose LLM-BlockFE, an LLM-guided offline feature construction framework that converts long text into executable feature programs, thereby avoiding LLM calls during online inference. LLM-BlockFE constructs feature programs by incrementally appending immutable code blocks and evaluates candidate features using a downstream model. To address the tendency of conventional greedy search to become trapped in suboptimal solutions, our method introduces a block-level rollback mechanism based on depth-calibrated credit allocation and advances multiple independent search trajectories

---

### [15] Verdict Without the Rule: Diagnosing and Auditing Regulatory Rule Sensitivity in LLM Compliance Systems

**链接**: https://arxiv.org/abs/2610.12313
**作者**: Saisab Sadhu, Aadit Sengupta, Vinay kumar Sankarapu, Pratinav Seth
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model compliance systems are deployed on the assumption that a verdict depends on the regulatory rule it is given. We test this directly across five models and 20 regulatory and platform-policy domains: delete, swap, or negate the governing rule while holding the case fixed, and check whether the verdict changes (OCS) or the model's internal representation of compliance shifts at all (ICS-delta). Neither moves much: models' verdicts are often invariant to substantial perturbations of the supplied rule, and the guard model, evaluated here under a custom-rule adaptation of its native taxonomy, is the least rule-sensitive and least accurate of the five, barely above chance (51%, versus 90-92% for general-purpose models). This reflects easy cases more than blanket neglect: on cases where deleting the rule changes a previously correct model prediction, models do track it closely. Neither better prompting nor direct intervention on the model's internal representations closes t

---

### [16] TokenRouter: Efficient Serving System for Token-Level LLM Routing

**链接**: https://arxiv.org/abs/2610.12242
**作者**: Tianyu Fu, Tengxuan Liu, Ruoxi Wang, Yixin Dong, Yi Ge, Yichen You 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) routing distributes inference work across different models, advancing the cost-quality Pareto frontier of LLM serving. While coarse-grained routing at the session or query level has been widely adopted in production systems, recent algorithmic work shows that fine-grained token-level routing can yield substantial efficiency and quality gains. However, efficiently serving token-level routed inference poses significant challenges to existing systems. Built on single-LLM assumptions, current systems suffer from severe step desynchronization and frequent batch admission delays under token-level routing, and they also impose high implementation complexity on developers. To address these challenges, we design TokenRouter, an efficient and developer-friendly serving system for token-level routed LLM inference. TokenRouter follows the principle of request-centric programming, model-centric execution: developers describe routing logic from the perspective of a single 

---

### [17] Narrow and Deep: An Ontology Tower as the Knowledge of an LLM Agent for an Industrial Equipment System

**链接**: https://arxiv.org/abs/2610.11768
**作者**: Younghwan Joo, Sung-il Kim
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are beginning to operate industrial energy equipment, and what they get right depends on what they are told about the plant. Established building ontologies name many kinds of points across many sites, whereas an industrial equipment system needs few entities with much knowledge about each. This study proposes the ontology tower, a narrow-and-deep ontology of a single equipment system whose knowledge deepens in two ways: through quantities derived from the measured points by physical relations, and through lessons from the operating journal incorporated as knowledge nodes. On a real low-humidity air-handling test plant operated daily through a programmable logic controller, agents received a text projected from its tower in a preregistered evaluation of nine tasks replayed from the plant's records, using four open-weight models from 9 to about 750 billion parameters. This knowledge raised the rate at which the agents avoided the most plausible misjudgm

---

### [18] CTRL: Control-Based Time Series Forecasting with LLM-Guided Residual Learning

**链接**: https://arxiv.org/abs/2609.23257
**作者**: Minkyoung Kim, Daeun Ji, Yohan Lee, Beomsoo Kim, Beakcheol Jang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] Stability-Plasticity Balance via Singular-Vector Selection in LLM Continual Learning

**链接**: https://arxiv.org/abs/2610.11076
**作者**: Lingxiang Wang, Hainan Zhang, Liang Pang, Hongwei Zheng, Zhiming Zheng
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain-specific continual adaptation of LLMs risks catastrophic forgetting, creating a fundamental tension between acquiring new capabilities and preserving those learned during pretraining. PEFT mitigates this problem by restricting the number of trainable parameters, but existing methods lack a principled unit for deciding where plasticity should be allocated and stability should be preserved. We identify the singular-vector channel as a natural unit for managing this trade-off. Each channel represents an input-output transformation, which can be updated to acquire new knowledge or fixed to preserve pretrained capabilities. Based on this perspective, we introduce SVC, a parameter-efficient continual-learning method that selectively updates Singular-Vector Channels. Before fine-tuning, SVC uses domain-specific data to estimate each channel's adaptation benefit and a fixed public general-domain corpus only as a history activation proxy for estimating forgetting cost. It then adaptively

---

### [20] A Dual-Hypothesis Reasoning Framework for LLM Guardrails

**链接**: https://arxiv.org/abs/2607.17575
**作者**: Md Asiful Islam and Fahmida Alam and Mihai Surdeanu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Are Near-Tied LLM Rankings Robust to Family-DIF-Guided Benchmark Recomposition?

**链接**: https://arxiv.org/abs/2609.00482
**作者**: Qiaoyuan Zheng, Yiqu Yang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] Chronos Enables Code Agents to Reason over Software Evolution

**链接**: https://arxiv.org/abs/2610.11578
**作者**: Xin Yin, Yiang Zhang, Zhiyuan Peng, Chao Ni, Zhe Cui, Xiaohua Xin
**来源**: cs.SE cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historical pull requests record the design decisions, compatibility constraints, and implementation patterns behind a codebase's current state. Experience relevant to a new task can span related changes whose descriptions emphasize different concerns. We introduce Chronos, a test-time framework that makes this connected history available to large language model (LLM)-based code agents. Chronos distills merged pull requests into structured experience cards and connects them through a typed graph of code-level, developer-intent, and organizational relations. Semantic search identifies entry cards, and weighted multi-hop expansion retrieves connected changes for selective reading. The same memory guides candidate generation and patch selection: a patch-focused change agent and a validation-strategy agent each develop a patch, and an evolution steward consults history to select between them. On SWE-Bench Verified, the full workflow improves SWE-Agent across all six evaluated LLM backbones,

---

### [23] Just for FUNS: LLM-Guided Spatio-Temporal Graph Node Generation for Forecasting Unobserved Node States

**链接**: https://arxiv.org/abs/2610.08818
**作者**: Shuhao Li, Weidong Yang, Changan Liu, Wei Zhuo, Yingbo Zhou, Fan Zhang 等 (7 人)
**来源**: cs.LG cs.AI cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] Evaluating Local Language Model Agents for Reproducible Data Engineering: An Empirical Software Engineering Study of Mobility Workflows

**链接**: https://arxiv.org/abs/2610.11482
**作者**: Jorge Garc\'ia-Carrasco, Javier Sanchis, Alejandro Reina-Reina, Alejandro Mat\'e, Juan Trujillo
**来源**: cs.SE cs.AI cs.DB cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context: Large language model (LLM) agents are increasingly used as software and data-engineering assistants, yet evidence about locally deployable open-weight agents remains limited. Existing evaluations often emphasize textual responses or isolated code generation rather than the validity of complete engineering artifacts. Objectives: We evaluate whether local LLM agents can produce correct and reproducible data-engineering artifacts, quantify the effect of a closed-loop workspace condition, and examine trade-offs in model scale, architecture, quantization, runtime, tool use, and failure. Methods: We introduce a benchmark of fifteen mobility-workflow tasks covering data discovery, connectors, transport-feed processing, semantic enrichment, feature engineering, validation, visualization, and reporting. Deterministic checkers assess generated scripts, tables, structured files, figures, and reports. Ten local configurations are evaluated in one-shot and closed-loop conditions, with five

---

### [25] Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving

**链接**: https://arxiv.org/abs/2407.00079
**作者**: Ruoyu Qin, Zheming Li, Weiran He, Mingxing Zhang, Yongwei Wu, Weimin Zheng 等 (7 人)
**来源**: cs.DC cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Beyond Euclidean Clipping: Overcoming Exploration Collapse in LLM RL via Riemannian Isometric Policy Optimization

**链接**: https://arxiv.org/abs/2607.10169
**作者**: Zhicheng Cai, Xinyuan Guo, Hanlin Wu, Wei-Ying Ma, Ya-Qin Zhang, Hao Zhou
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] PlurVA-LLM-2026 Shared Task Track-1: Pluralistic Value Alignment in LLMs via Multilingual Fine-Tuning and Threshold Calibration

**链接**: https://arxiv.org/abs/2609.32382
**作者**: Vihindi Kotalawala, Nevidu Jayatilleke
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] Examining Social Attribution in LLM Reasoning: A Theory-Guided Probing Methodology

**链接**: https://arxiv.org/abs/2610.12022
**作者**: Zhaoxin Yu, Qingchao Kong, Dajun Zeng, Wenji Mao
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed in sociotechnical systems where social attribution, the reasoning process attributing external events to the causes and reasons of agents' social behaviors, plays a critical role. These processes involve judgments of social cause, responsibility, and blame/credit to agents. Although attributional models are well-studied in social psychology and cognition through Attribution Theory, social attribution remains underexplored in AI, particularly LLM social reasoning. This paper provides the first systematic exploration of LLM social attribution. Our work focuses on responsibility and blame attributions, examining current LLMs' judgments and their underlying internal mechanisms. Guided by attribution theory, we construct a social attribution benchmark consisting of a Vignette subset based on classic scenarios from attribution theory research and a Reality subset based on real-world social narratives, yielding 7,639 responsibility/blame 

---

### [29] Error-Propagation Modeling for Failure Attribution in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.11600
**作者**: Jiaqi Liao, Yuanzhao Zhai, Huanxi Liu, Xu Zhang, Zheming Zhuang, Dawei Feng 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MASs) are increasingly used to solve complex tasks through coordinated reasoning, tool use, and interaction with external resources. However, attributing failures in such systems remains challenging because the observed outcome often does not directly reveal the error responsible for the failed execution. In this work, the attribution target is the decisive error, defined as the agent--step pair whose correction would recover the failed execution. Existing approaches largely identify suspicious steps without explicitly modeling how errors propagate across interactions or persist in unresolved loops, making decisive errors difficult to distinguish from downstream failure symptoms. We propose \textbf{E}rror-Propagation \textbf{M}odeling for \textbf{F}ailure \textbf{A}ttribution (\textbf{EMFA}). EMFA constructs a structured representation of the failed trajectory, models both cascading propagation and persistent interaction loops, and uses propagation-aware 

---

### [30] Could LLM Watermark Detection be Public?

**链接**: https://arxiv.org/abs/2610.12106
**作者**: Georgios Milis, Tom Sander, Tom\'a\v{s} Sou\v{c}ek, Heng Huang, Pierre Fernandez
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Watermarking large language models is popular for tracing chatbot and agentic outputs, yet detectors remain unreleased since exposing them could let attackers do targeted edits with the detector's feedback. However, watermarks are already vulnerable to uninformed tampering attacks. We thus first quantify whether a public detector would be an additional liability in a deployment setting at varying levels of access, from token-level scores to a binary verdict. Second, we introduce a split-key public-private watermarking method that exposes one key through a public detector while keeping the other for full verification and forensics. An informed attacker can only move the public signal, creating an imbalance between public and private scores. We introduce a statistical test for this imbalance, and combine it with the full key verdict in a two-stage mechanism. Third, we evaluate the split-key method on a wide range of removal and forgery attacks, comparing the uninformed to detector-inform

---

### [31] ROMA: LLM System for Real-World Object-Centric Multi-Sensory Active Perception

**链接**: https://arxiv.org/abs/2610.06955
**作者**: Ruoxuan Feng, Yutong Chen, Ruihua Song, Huan Yang, Zhongyuan Wang, Guocai Yao 等 (7 人)
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] A Survey on LLM-Integrated Hardware Design Verification

**链接**: https://arxiv.org/abs/2610.10580
**作者**: Hao Zheng, Jaime Rafael Imperial, Bardia Nadimi, Xiangfei Kong
**来源**: cs.AR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly being integrated into hardware verification to automate specification interpretation, verification-artifact generation, debugging, formal reasoning, and tool orchestration. This survey provides a systematic review of LLM-assisted hardware functional verification across SystemVerilog assertion generation, stimulus and testbench generation, bug localization and design repair, model checking and equivalence checking, SAT/SMT optimization, and emerging agentic verification workflows. We organize the literature by methodology, verification objective, tool interaction, benchmark, and evaluation criterion, and examine both inference-time techniques--including prompting, retrieval, structured reasoning, and agentic workflows--and training-time adaptation. Across these areas, a common pattern emerges: LLMs are most effective as semantic reasoning, search, and orchestration components embedded within verification-aware workflows, while simulators, fo

---

### [33] Characterizing Overconfident Failure in LLM-Based Code Generation

**链接**: https://arxiv.org/abs/2610.11300
**作者**: Ravishka Rathnasuriya, Wei Yang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for automated code generation, but generated programs can appear syntactically plausible while still failing execution-based correctness checks. Existing validation methods, such as testing and program analysis, remain essential but are often incomplete, costly, or applied only after generation. Model-derived uncertainty is therefore a natural early reliability signal. This paper studies the dilemma of overconfidence in code LLMs where incorrect programs are often generated with token-level confidence comparable to correct programs. We study this dilemma across four open-source code models and three execution-based benchmarks. Our analysis begins by investigating whether existing uncertainty metrics provide reliable proxies for execution correctness in code generation. We then characterize overconfidence at both global and local token levels, asking whether incorrect programs remain indistinguishable from correct ones under confidence 

---

### [34] Looking Inside LLMs: Small-World Connectivity as a Signature of Reasoning Performance

**链接**: https://arxiv.org/abs/2610.12304
**作者**: Zheng Huang, Sansheng Cao, Enpei Zhang, Weikang Qiu, Elynn Chen, Xiang Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding large language model (LLM) reasoning requires looking beyond behavioral performance to examine how reasoning ability is reflected in internal organization. Inspired by neuroscience findings linking higher intelligence to stronger small-world organization in functional brain networks, we investigate small-world connectivity as a structural signature of LLM reasoning. We construct functional graphs from attention-head activation similarities and find that a higher small-world index (SWI), capturing local clustering and short global paths, consistently correlates with better fluid reasoning performance across models and training checkpoints. Since local clustering is central to small-world organization, we further examine how heads important for model performance connect within and across communities. We find that these heads tend to have a larger share of connection weight within their own communities (high core scores) and a more concentrated weight distribution across com

---

### [35] PaReGTA: A Temporally Aware LLM-Based Patient Representation Framework for EHR Analytics

**链接**: https://arxiv.org/abs/2602.19661
**作者**: Kihyuk Yoon, Lingchao Mao, Catherine Chong, Todd J. Schwedt, Chia-Chun Chiang, Jing Li
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Has LLM Screening Performance Stalled in Software Engineering Systematic Reviews?

**链接**: https://arxiv.org/abs/2610.10633
**作者**: Aleksi Huotala, Miikka Kuutila, and Mika M\"antyl\"a
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Screening in systematic reviews (SRs) is manual and time-consuming. Prior work has explored large language models (LLMs) for automating this step, but LLMs are evolving rapidly, so earlier performance claims may no longer accurately reflect their screening performance. We used an existing software engineering SR screening benchmark (SESR-Eval) as our data. We also power-sampled a new, smaller dataset (SESR-Eval-Mini) that allows evaluation at lower costs. Using this data, we evaluated eight new LLMs for screening performance. Additionally, we tested different prompts, analyzed LLM agreement in screening decisions and criteria, and examined the effect of refining the inclusion and exclusion criteria on screening performance. The eight new LLMs performed marginally better than the seven old ones: avg. MCC across secondary studies rose from 0.347 to 0.365. Differences between secondary studies are still bigger than between LLMs. Computing the overall screening decision from criterion-leve

---

### [37] Nullify: Null-Space Activation Steering for Training-Free LLM Unlearning

**链接**: https://arxiv.org/abs/2610.10655
**作者**: Wei Zhai, Xiang Liu, Qiang Huang, Rui Qian, Lemao Liu, Ziwei Li 等 (9 人)
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) inevitably internalize substantial amounts of sensitive or private information during pre-training, while LLM unlearning aims to selectively erase specific knowledge to prevent privacy leakage with minimal loss of model utility. However, existing methods struggle to balance forget quality with utility, and typically incur substantial computational costs due to parameter fine-tuning. To address this, we propose Nullify, a training-free, non-destructive activation steering method for LLM unlearning. Nullify employs steering vectors during inference to redirect privacy-related activations away from their memorized answers, while satisfying a null-space constraint that leaves retained-query activations essentially unaffected to maintain utility. Evaluations on TOFU and MUSE show that Nullify matches or surpasses established baselines in forget quality while achieving near-lossless preservation of model utility. By avoiding weight updates entirely, Nullify serve

---

### [38] Measuring Cultural Alignment Beyond the Average: A Framework for Evaluating Maternal-Health LLM Interactions in Indian Contexts

**链接**: https://arxiv.org/abs/2610.11586
**作者**: Umaira Izhar, Gunjan Arora, Pushpendra Singh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing evaluation methods for healthcare LLMs primarily assess factual correctness,safety, and fluency, while providing limited insight into whether generated interactions reflect culturally situated healthcare reasoning. This limitation is particularly important in maternal health, where care decisions are shaped by social and relational norms. We introduce MH-INDIC, a culturally grounded evaluation framework for maternal-health interactions in urban and semi-urban North Indian contexts that operationalises cultural behaviour through ten dimensions of maternal-health reasoning. Using a 26-item survey administered to 102 pregnant and postpartum women from urban and semi-urban North India, we evaluate ten LLMs. We distinguish population level cultural alignment from profile-level behavioural variation. Although several models approximate the human population-level distribution, all evaluated systems exhibit substantially lower variation across demographic and household profiles than t

---

### [39] Can a System-One LLM Perform Knowledge Tracing When Few or No Learners Are Logged?

**链接**: https://arxiv.org/abs/2610.11135
**作者**: Unggi Lee, Haeun Park
**来源**: cs.CL cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge tracing (KT) models need many logged learners, so a new course or platform starts without a usable model. In LLM-based KT the LLM generates the answer, which we call System-Two; it is either fine-tuned on the target data or reasons and votes over ten samples, which is slow and gives coarse probabilities. We ask whether an off-the-shelf System-One LLM, which returns a probability for a typed question directly in a single pass, can perform KT when few or no learners are logged. On seven datasets, Jev without any data from the target platform reaches a mean AUC of .706, above the best of 28 deep KT models trained on 8 learners (.689) and above System-Two Thinking-KT on all seven datasets (.650) at about 1/100 of its API cost. Adding examples and a similar-learner statistic from the logged learners (JevKT) raises this to .722; JevKT stays significantly ahead of deep KT up to 16 learners and ahead on average up to 64, and supervised KT catches up between 64 and 128 learners. Among

---

### [40] LLM Persona Unlearning

**链接**: https://arxiv.org/abs/2609.39882
**作者**: Kemou Li, Zhuan Shi, Qizhou Wang, Fengpeng Li, Negar Rostamzadeh, Golnoosh Farnadi 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Memory Type Varies: Empowering LLM Agents for Long-Term Memory with Diverse Strategies

**链接**: https://arxiv.org/abs/2610.11573
**作者**: Yi Wen, Derong Xu, Pengyue Jia, Yichao Wang, Yingyi Zhang, Maolin Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The memory capabilities of Large Language Models (LLMs) have garnered increasing attention recently. Despite great success achieved, existing retrieval-based memory approaches typically overlook the differences between memories and employ a unified strategy to process all memories, leading to suboptimal performance. Thus, an intuitive question arises: can we categorize memory into different types and select appropriate strategies? However, given the topic-rich, scenario-complex, and boundary-blurred nature of memory scenarios, achieving precise classification of memories is not easy. To address this challenge, we propose a memory multi-class dataset in this paper, termed TriMEM, which provides precise annotations for memory types across diverse scenarios. Building upon this foundation, we propose a novel memory framework, named MemoType, which can adaptively recognize each memory and query type with the learned router model. With the memory and query routing, MemoType can retrieve the 

---

### [42] MemCalib: Benchmarking and Optimizing Memory Use in LLM Agents

**链接**: https://arxiv.org/abs/2609.24259
**作者**: Ruike Cao, Fanyu Zhao, Fugen Yao, Liang Dong, Jian Xu, Yifei Zhao 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Learn2Play Bench: How Well Do LLM Agents Learn from Experience in Unfamiliar Environments?

**链接**: https://arxiv.org/abs/2610.08215
**作者**: Yibo Li, Jinhang Qiu, Zhi Zheng, Qianyun Guo, Jiaying Wu, Shuo Ji 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Forms of LLM-Integrated Applications from LLM-Chats to Autonomous AI Agent System

**链接**: https://arxiv.org/abs/2610.11899
**作者**: Irene Weber (University of Applied Sciences Kempten, Germany)
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly embedded as components in software systems, marketed under labels such as chatbot, copilot, retrieval-augmented generation, workflow, coding agent and AI agent. Whether these labels denote genuine architectural forms or serve as branding has not been assessed systematically. In the sources surveyed, labels do carry architectural content, most clearly in vendor usage: copilot denotes a router-worker architecture operating a host application under step-by-step user confirmation, while the more recent shift to the label agent coincides with AI-planned multi-step execution of which the user sees only the outcome. The coding agents of four major providers share one architecture, a reason-and-act loop delegating to subagents. This survey describes seven recurring forms---LLM chats, custom agents, retrieval-augmented generation (RAG), AI-enhanced workflows, copilots, coding agents, and, in part, agentic RAG---in a common vocabulary of agents and t

---

### [45] Rethinking Latency Denial-of-Service: Attacking the LLM Serving Framework, Not the Model

**链接**: https://arxiv.org/abs/2602.07878
**作者**: Tianyi Wang, Huawei Fan, Yuanchao Shu, Peng Cheng, Cong Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Not Every Change Is Necessary: Recoverable Drift in Large Language Model Unlearning

**链接**: https://arxiv.org/abs/2610.11915
**作者**: Xunlei Chen, Qinghui Gong, Jingkun Xue, Qihe Liu, Shijie Zhou, Fei Ye
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine unlearning in large language models aims to remove unwanted knowledge while preserving the model's remaining capabilities. Although existing methods use retention objectives or restrict where edits occur, achieving the desired forgetting level can still leave collateral changes that impair non-target behavior. Our recovery comparisons suggest that some of these changes can be reversed while preserving observed forgetting performance. In this work, we present Propose-Then-Project Unlearning (PTP-U), a framework that combines targeted forgetting with the recovery of non-target capabilities. PTP-U first applies local analytic edits to weaken target knowledge associations, then aligns non-target output distributions with those of the original model to recover capabilities while maintaining fixed forgetting constraints. Both stages serve a common goal: satisfying the forgetting requirements while preserving fluent generation and performance on non-target tasks. Across three benchmar

---

### [47] Natural Language to First-Order Logic LLM-based Autoformalization

**链接**: https://arxiv.org/abs/2610.12030
**作者**: Andrea Brunello, Cristian Curaba, Luca Geatti, Michele Mignani, Angelo Montanari, Nicola Saccomanno
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have renewed interest in autoformalization. Yet, when First-Order Logic (FOL) is considered as the target formalism, the field still lacks a unified task formulation and a systematic survey. This paper addresses this gap: we first provide a principled definition for the FOL-autoformalization task by distinguishing Ontology Extraction from Logical Translation, showing how their conflation obscures (cross-study) evaluation; we review existing datasets, evaluation metrics, and LLM-based methods, including fine-tuning, prompting, and verification-based refinement; we identify open challenges in benchmarking, semantic evaluation, ontology-aware methods, and end-to-end applications.

---

### [48] Why LLM Agents Favor Their Group: Stakes, Observed Norms, and Reputation

**链接**: https://arxiv.org/abs/2610.11008
**作者**: Yujiao Chen
**来源**: physics.soc-ph cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents favor their own group because they have watched their members favor each other. The group label alone does little once the decision has a cost; what drives favoritism is observed behavior, and an individual's own record can override it. We test this in small societies with arbitrary group labels, ten rounds of point sharing, and matched one-shot decisions across fifteen OpenAI models and three Claude models, about 4,400 societies and 3.3 million audited model calls. First, the large effect of a bare group label reported in earlier work appears only when giving others points costs the agent nothing; once the agent can keep points for itself, that effect collapses on every model that shows it. Second, under a stake, interaction history becomes the main source of favoritism: the history effect is statistically positive on 13 of 15 models, reaches about 3.5-8 points out of 10 on 11, grows with the number of rounds played, and extends to labeled strangers the agent has

---

### [49] Beyond Direct Access: Resource Hijacking in LLM Agents

**链接**: https://arxiv.org/abs/2608.15108
**作者**: Puyu Zeng, Mingang Chen, Zheli Liu, Qibing Ren
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Accurate but Not Humble: Evaluating Epistemic Humility in LLM Agents under Knowledge Conflict

**链接**: https://arxiv.org/abs/2610.12360
**作者**: Kaiser Sun, Bernal Jimenez Gutierrez, Hongjun Liu, Jingyu Zhang, Jie Gao, Mark Dredze 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When retrieved evidence contradicts an agent's prior beliefs, does it revise its answer, acknowledge uncertainty, or persist with an incorrect conclusion? Existing evaluations of agentic systems focus primarily on task success, offering limited insight into how agents handle such conflicts. We propose to evaluate agents on epistemic humility (EH): the agent's willingness to recognize, act on, and communicate uncertainty during task execution. We operationalize EH through three trajectory-level behavioral dimensions: Identify, Solve, and Escalate (ISE). Through knowledge conflict, situations where the backbone language model's parametric knowledge contradicts the evidence it encounters, or where two contextual sources disagree, we evaluate two conflict settings: (1) controlled conflict and (2) naturally occurring conflict during multi-step agentic execution, each paired with matched no-conflict controls. Evaluating four agents, we find that higher task accuracy does not necessarily corr

---

### [51] OmniCapBench: A Deep-Structured Evaluation Framework for Fine-Grained Audio-Visual Captioning

**链接**: https://arxiv.org/abs/2610.12458
**作者**: Zhongyu Yang, Jiale Tao, Ruitao Chen, Zuhao Yang, Yingfang Yuan, Xueliang Zhao 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are rapidly evolving toward continuous audio--visual reasoning, creating an urgent need for evaluations that expose their capability limits. Audio--visual captioning is an ideal diagnostic task, yet current benchmarks face a coupled trade-off: whole-caption scores provide coverage without localization, local probes provide localization without coverage, and unconstrained LLM judges introduce instability. We introduce OmniCapBench (Omni-Video Caption Benchmark), a benchmark that reframes audio--visual caption evaluation as a deep-structured diagnostic framework. OmniCapBench shifts the prediction target from free-form text to sets of atomic, verifiable evaluation units across three tracks: entity references, visual shots, and audio events, enabling reliable scoring with deterministic constraint checks and localized LLM-based semantic comparisons. With 786 densely annotated videos, OmniCapBench effectively distinguishes MLLM perception errors, inc

---

### [52] Constitutional Gating and Deterministic Recovery for Multi-Agent LLM Negotiation: Ablations Against a Stateful Adversarial Gatekeeper

**链接**: https://arxiv.org/abs/2610.11542
**作者**: Masaaki Nakatsu (AO, Inc. / OrbLabs AG), Reno Wang (AO, Inc.)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] When Lower Reconstruction Loss Hurts: Distributionally Robust Refinement for Low-Bit LLM Quantization

**链接**: https://arxiv.org/abs/2610.11226
**作者**: Yanlong Zhao, Xiaoyuan Cheng, Huihang Liu, Baihua He, Xinyu Zhang, Harrison Bo Hua Zhu 等 (9 人)
**来源**: cs.AI cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-only post-training quantization (PTQ) relies heavily on reconstruction loss minimization to preserve model quality at low precision. We show that the weights favored by minimizing this loss need not yield better model performance on new tasks. In fact, we find that lower reconstruction loss can even degrade model performance on the same calibration data. Our analysis further shows that weights with lower reconstruction loss on calibration data can have higher loss than other weights when the distribution of input activations changes. Motivated by these observations and our analysis, we propose Distributionally Robust Quantization (DRQ), a post-hoc refinement process that minimizes worst-case reconstruction loss over a constrained set of input activation distributions. DRQ refines the integer codes representing quantized weights within the existing quantization grid, keeping quantization parameters and inference operators unchanged. Extensive experiments show that DRQ improves mo

---

### [54] When Should Agents Think? Adaptive Reasoning via Cross-Turn Estimation

**链接**: https://arxiv.org/abs/2610.12061
**作者**: Yiruo Cheng, Shen Huang, Xiaoshuai Song, Jiejun Tan, Guanting Dong, Pengjun Xie 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents have demonstrated strong capabilities on complex tasks. They typically perform reasoning before each action throughout an interaction trajectory. However, reasoning may not be necessary at every turn, as reasoning produced earlier can continue to support subsequent actions. A key challenge is therefore to determine when existing reasoning remains sufficient and when a new reasoning step is needed, without relying on costly generation-based verification. We find that decreases in the likelihood of subsequent reference actions after removing additional reasoning closely track whether those actions remain recoverable given earlier reasoning, providing an effective and lightweight signal for estimating cross-turn action support. Based on this observation, we propose Reasoning Adaptation through Cross-Turn Estimation (RACE), a training approach for adaptive agent reasoning. RACE introduces a Likelihood-Guided Progressive Reasoning Cover Detection (LoG

---

### [55] MemTrace: Tracing and Attributing Errors in Large Language Model Memory Systems

**链接**: https://arxiv.org/abs/2605.28732
**作者**: Xinle Deng, Ruobin Zhong, Hujin Peng, Xiaoben Lu, Yanzhe Wu, Guang Li 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] When the Commons Appropriates a Large Language Model: How WikiVault Reshaped Korean Wikipedia

**链接**: https://arxiv.org/abs/2610.07660
**作者**: Inhwa Song, Sohyeon Hwang, Ted Yoo, Manoel Horta Ribeiro
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] Efficient and Scalable Provenance Tracking for LLM-Generated Code Snippets

**链接**: https://arxiv.org/abs/2605.28510
**作者**: Andrea Gurioli, Davide D'Ascenzo, Federico Pennino, Maurizio Gabbrielli, Stefano Zacchiroli
**来源**: cs.SE cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] The Harness as the Only Mutable Surface: Compliance-Bounded Self-Evolution of LLM Agents in Credit Pipelines, with a Measured Admission Gate

**链接**: https://arxiv.org/abs/2610.10629
**作者**: Ravil Akhtyamov
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving LLM agents can adapt a credit pipeline to a changed rule, but an agent that rewrites itself destroys the artefact a supervisor reviews: a named change, a recorded test, an approval. We argue that self-evolution is reviewable only if it is confined to the runtime harness (instruction text, tool-call logic and primitive composition) while model weights stay fixed, so that every adaptation is a diff with a cause and a test attached. We give a dual-loop engine built on that bound, with one admission gate that writes a hash-chained record before deployment, and we measure the gate in simulation, with a simulated agent and a seeded-search proposer rather than language models. Across three families of supervisory re-interpretation at three severities, 10 seeds each, the gated loop admitted 144 of 7,449 candidate changes, none of which worsened error on held-out history, and restored the false-positive rate to the oracle level without raising missed flags in every low- and mid-s

---

### [59] NOMOS: Compiling Written Policies into Statically Verified Tool-Call Gates for LLM Agents

**链接**: https://arxiv.org/abs/2610.11030
**作者**: Min-Young Yu, Tony Kim, Jang Won Choi
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents violate the policies they are deployed to enforce, often silently. Prior defenses hand-write rules, query an LLM verifier per action, or compile policies through heavyweight formal machinery. Naive compilation fails: extracted rules block the tool satisfying their own precondition, or read arguments their tool lacks. NOMOS, a four-pass compiler, turns a natural-language policy into a deterministic tool-call gate; static verification with tool-schema-level checks alone (no prover, solver, or LLM) repairs or rejects 37% (airline) and 13% (retail) of candidates, without which most shipped rules are inoperable. Replaying compiled rules over undefended transcripts flags bindings that refuse legitimate work (a development binding refused 95.9% of task-passing calls); no evaluation binding is flagged. On $\tau^2$-bench the gate cuts violations of reference-encoded clauses among state-changing calls from 66.3% to 2.6% (airline) and 30.8% to 6.9% (retail), raising airline 

---

### [60] Evidence-Traceable Dynamic Interviewer Architecture for Expertise-Adaptive Qualitative Interviews Using Local LLMs

**链接**: https://arxiv.org/abs/2610.11651
**作者**: Aisvarya Adeseye and Jouni Isoaho and Adeyemi Adeseye and Seppo Virtanen and Mohammad Tahir
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated interviewers and conversational agents are increasingly used in research, recruitment, customer service, and education. However, many existing systems rely on fixed question sequences and provide limited context-based personalization without considering participants' knowledge, which can lead to repetitive or irrelevant follow-up questions. Therefore, there is a need for an adaptive interviewing system that can adjust question depth while maintaining conversational continuity and semantic progression. To address this, an Evidence-Traceable Dynamic Interviewer Architecture is presented using a locally hosted Large Language Model (LLM), with the interview continuously adapted throughout the entire conversation based on the participant's responses and evolving context. The interviewer profiles participants' expertise in real time to generate knowledge-appropriate questions, well-articulated responses, and smooth transition messages that support conversational continuity. A five-

---

### [61] Arbiter: Detecting Interference in LLM Agent System Prompts

**链接**: https://arxiv.org/abs/2603.08993
**作者**: Tony Mason
**来源**: cs.SE cs.AI cs.CR cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Clinician use of language models diverges from how the models are evaluated

**链接**: https://arxiv.org/abs/2610.11069
**作者**: Krithik Vishwanath, Haitong Lin, Anton Alyakin, Jin Vivian Lee, D. Brock Hewitt, Jie J. Yao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) assistants are being deployed to clinicians across health systems, and judgments about their readiness rest largely on benchmark scores, most of them derived from examination questions or curated cases. A benchmark predicts performance in deployment only to the extent that its items resemble real use, yet whether benchmarks reflect the work these systems receive has rarely been measured. Here we analyze 127,833 queries sent by 6,342 physicians, advanced practice providers and nurses in 35 specialties to an institutional assistant during an eight-month roll-out. We characterize each query with RCQ-Map, a clinician-validated framework grounded in taxonomies of clinical questions and of LLM evaluation, which records its task, intent, answerability, missing information and potential harm. Documentation and administration (36.2%) and knowledge retrieval (28.9%) made up nearly two-thirds of use, and diagnosis 3.7%; more than a third of queries could not be answered

---

### [63] Same Outcome, Different Evidence: Intent Recovery in LLM Safety Evaluation

**链接**: https://arxiv.org/abs/2610.11766
**作者**: Haitong Jiang, Chunlin Liu, Sihan Tang, Chan Wu, Xiaoqing Su, Yuhong Feng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety evaluations of large language models commonly summarize harmful-output behavior with attack success rate (ASR). Yet the same non-harmful outcome can arise for very different reasons. A model may recover a harmful task and refuse it, fail to recover the task, or respond to something else entirely. Distinguishing these cases becomes especially important under intent-obscuring prompts, where a low ASR does not reveal whether the evaluated task was actually engaged. To make this distinction explicit, we pair ASR with operative understanding rate (UR), which measures whether a response both identifies the evaluated task and treats it as the task to be answered. Across interfaces, this paired view reveals substantial variation hidden by ASR: similar ASR values can correspond to sharply different recovery rates. Controlled English reconstructions show that recovery consistently improves as compressed prompts become more explicit, whereas ASR does not follow the same pattern. A compleme

---

### [64] RFChipAgent: Multi-Agentic AI Flow for Analog/RF Chip Design

**链接**: https://arxiv.org/abs/2610.10858
**作者**: Awani Khodkumbhe, Yunfei Feng, Raj Rangarajan, Kevin Wang, Kamal Sahota
**来源**: cs.AR cs.AI cs.LG cs.MA cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog/RF circuits remain the critical interface between digital computation and the physical world, and emerging standards from Wi-Fi 7 to 6G place stringent demands on them, yet analog/RF design remains one of the most labor-intensive steps in chip development. We present RFChipAgent, a first-of-its-kind multi-agent flow of large language model (LLM) agents for end-to-end analog/RF circuit design automation, in which AI agents collaboratively orchestrate the complete design flow under human supervision. RFChipAgent is built around four technical pillars. First, a multimodal retrieval-augmented generation (RAG) subsystem with private per-document FAISS indexing extracts design knowledge from existing engineering documentation. Second, a topology agent drives topology selection, and a schematic and testbench agent automates circuit and testbench assembly. Third, a closed-loop hybrid circuit-sizing engine combines Tree-structured Parzen Estimator (TPE) and CMA-ES optimization, evaluatin

---

### [65] Closed-loop evaluation of LLM agents for embedded software development

**链接**: https://arxiv.org/abs/2610.11447
**作者**: Jorge Garc\'ia-Carrasco, Sergio Garc\'ia-Carrasco, Alejandro Mat\'e, Juan Trujillo
**来源**: cs.SE cs.AI cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as coding agents that edit files, run builds and tests, inspect execution results, and repair software iteratively. Embedded firmware is a demanding target because correctness depends on closed-loop behavior under sensing, timing, and safety constraints, not only on static source quality. Yet embedded-agent evaluation remains limited and often emphasizes one-shot synthesis or offline correctness. We present a benchmark for closed-loop evaluation of embedded coding agents. Each task provides a plain-text engineering description, constrained workspace, and visible build-and-runtime surface. The agent must translate requirements into implementation and self-verification steps, then iterate until the required device behavior is achieved. The suite contains five embedded-control tasks and four feedback scenarios: one-shot generation, realistic self-verification, CI-style red/green feedback, and oracle-style detailed feedback. The implem

---

### [66] All Verdicts are Not Equal: Rethinking LLM Judge Reliability

**链接**: https://arxiv.org/abs/2610.12083
**作者**: Vineet Kumar, Darshita Rathore, Anindya Moitra
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Judge is the standard paradigm for NLP evaluation, yet its systemic reliability remains poorly understood despite being widely treated as a deterministic ground truth. We present a comprehensive reliability audit, stresstesting six frontier models across four benchmarks, five prompt formats, two presentation orders, three sampling temperatures, and ten repetitions per condition. Our empirical analysis reveals severe vulnerabilities: verdicts change across identical replications at temperature zero, position-order swaps flip the majority of verdicts on challenging tasks, and the most deterministic judge achieves perfect consistency by trivially repeating incorrect verdicts, agreeing with ground truth only 51% of the time. To formalize these multi-faceted failure modes, we introduce the trustworthy verdict rate (T ), a unified metric capturing the joint probability that an evaluation is reproducible, order-invariant, and accurate. UsingT , we derive a theoretical upper bound on 

---

### [67] SAGE: Sink-Aware Guided Emphasis for Visual Grounding in Vision-Language Decoders

**链接**: https://arxiv.org/abs/2610.11469
**作者**: Jeonghyo Song, YoungJoon Yoo
**来源**: cs.CV cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent large vision-language models (VLMs) pair a visual encoder with a large language model (LLM) and perform well on diverse image-text tasks, yet their reliability is often limited by decoder attention pathologies that suppress visual evidence and exacerbate hallucinations. In this paper, we revisit visual attention sinks and uncover a structured, layer-dependent behavior: across prompts, early and late decoder layers exhibit prompt-invariant attention collapse onto the same few image regions, which we term PIS (Prompt-Invariant Sinks), whereas mid layers become prompt-conditioned and drive vision-language alignment. This split suggests that treating sinks as a uniform effect is incomplete. Building on this insight, we propose SAGE (Sink-Aware Guided Emphasis), a lightweight intervention that steers decoder attention away from PIS and toward query-dependent regions of interest (ROIs) using token-aligned ROI masks derived from standard vision backbones such as CLIP, ViT, and DINOv3. 

---

### [68] Leveraging LLM-Generated Explanations for Detecting Emotionally Rewritten Fake News

**链接**: https://arxiv.org/abs/2610.08835
**作者**: Yupei Guo, Jiajun He, Xiaohan Shi, Tomoki Toda, Zekun Yang, Bowen Wang 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] How Narrative Wrapping Affects LLM Refusal: A Cross-Language Benchmark and Defense

**链接**: https://arxiv.org/abs/2610.11005
**作者**: Zhankai Ye, Yanning Wang, Yukai Jin, Bo Mei, Fangyi Li, Wei Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety-aligned language models often refuse a harmful request stated directly but answer the same request inside a role-play or narrative wrapper. We measure this vulnerability across languages and registers: attack success on Qwen3-1.7B is already 89.4% in English and 93.0% in modern Chinese, and reaches 95.7% in Classical Chinese. We build GUISE, a benchmark for systematically studying this vulnerability. It includes parallel requests in English, modern Chinese, and Classical Chinese, matched harmful and benign pairs, wrapper types held out for evaluation, and a stricter criterion that counts warn-then-answer responses as attack successes. Representation analysis shows that language and register move harmful-request representations only slightly away from the model's refusal direction, whereas narrative wrappers move them much farther away. We propose AXIS, which combines preference optimisation with a rotation objective that aligns harmful-request representations with the refusal di

---

### [70] Beyond Imitation: A Framework and Benchmark for LLM-Assisted Peer Review

**链接**: https://arxiv.org/abs/2610.11087
**作者**: Rachel S.Y. Teo, Yutaro Yamada, Shashank Kotyan, Yuki Imajuku, Tarin Clanuwat
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid growth of scientific publishing has strained peer review, particularly in machine learning, raising concerns about declining review quality and increasing reviewer workload. Large language models (LLMs) have been proposed as automated review assistants, yet their evaluation has focused largely on imitating human-written reviews rather than supporting the core functions of peer review. Here, we introduce a verification-centric perspective on LLM-assisted peer review, emphasizing error detection as a critical and resource-intensive task. We present a scalable benchmark that evaluates review systems' ability to identify logical contradictions, constructed through synthetic insertion of errors into conference papers, yielding unambiguous evaluation targets and enabling systematic comparison. We further propose a Multi-Layered Review (MLR) framework that prioritizes detailed manuscript comprehension before review generation, aligning more closely with human reviewing practices whi

---

### [71] A 3D Characterization Framework for Intelligent Sequential Decision Making

**链接**: https://arxiv.org/abs/2610.11696
**作者**: Sadig Gojayev, Carolina Fortuna
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Puzzles are widely used to evaluate the reasoning capabilities of artificial intelligence (AI) systems for sequential decision making, yet approaches originating from different paradigms are rarely compared under unified conditions. To address this gap, we introduce a three-dimensional characterization framework that enables the analysts of AI methods by 1) projecting them to the Markov decision process (MDP) sequential decision making formalism, 2) degree of autonomy through human prior ranking of their designs and, 3) skill and computational cost. Using this framework, we analyze how representative graph-based, reinforcement learning, and large language model (LLM)-based approaches differ in their design choices and performance characteristics, instantiated respectively by Neurosolver, forward-backward reinforcement learning (FBRL), and automated thought-of-search (AutoToS), including a double-agent extension of thought-of-search (DA-ToS). The analysis relies on the Tower of Hanoi pu

---

### [72] TRACE: Diagnosing Verifier Brittleness in Agentic Evaluation

**链接**: https://arxiv.org/abs/2610.11678
**作者**: Radhika Gaonkar
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verifier scores now serve as both benchmark metrics and training rewards for large language model (LLM) agents, and a change in score is routinely read as a change in capability. It may instead reflect a change in the evaluation. We introduce TRACE, a protocol that turns a score change from a verdict into a testable diagnosis: it applies a targeted change to one part of an evaluation, compares paired runs, checks whether the agent's behavior changed, and rescores unchanged trajectories to test whether the scoring rule is responsible. In a controlled suite of 25 synthetic tasks, renaming tools lowers a scripted agent's score by 0.250 even though it performs exactly the same operations; restoring the original names at scoring time closes the entire gap, while the same mutation exposes a genuine behavioral failure in a second agent. On public $\tau^2$-bench tasks with four LLM agents, an initial 30-task study finds mixed reward changes whose one clear effect does not replicate. In a large

---

### [73] OnTrack: Real-Time Monitoring and Intervention in LLM Agent Trajectories via Streaming Structure-Aware Optimal Transport

**链接**: https://arxiv.org/abs/2610.12375
**作者**: Babak Barazandeh, Connor Swanson, Chinmay Kulkarni, Nikhil Mungel
**来源**: cs.AI cs.CL cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents are deployed in applications from trip planners and stock trading to IT incident triage. In most cases, LLM agents work autonomously with minimal rule-based safeguarding, leading to cost and safety issues from irreversible actions. Recent works resolve this either by using a safeguard agent to monitor behavior or evaluating logs post-hoc. The first adds cost and latency to every step; the second delivers its verdict after the run, when tokens are burned and damage is done. To overcome this, we propose OnTrack, a streaming monitoring mechanism that compares an agent's steps and dependencies against recorded successful runs to alert users or block the agent in about a millisecond per step. We study this problem in three regimes of decreasing access: full reference access (historical runs and tool schemas), intermediate access (only tool schemas), and no prior knowledge (only step logs as generated). Expectation of OnTrack's monitoring capabilities reduces as data access drops, ran

---

### [74] SparKV: Overhead-Aware KV Cache Loading for Efficient On-Device LLM Inference

**链接**: https://arxiv.org/abs/2604.21231
**作者**: Hongyao Liu, Liuqun Zhai, Junyi Wang, Zhengru Fang, Jingshu Chen, Jun Huang
**来源**: cs.NI cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] What to Admit and How to Present: Governing Persistent Memory in LLM Agents

**链接**: https://arxiv.org/abs/2610.11188
**作者**: Chang Liu, Deliang Ding
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent memory can improve personalization in LLM agents but can also induce sycophancy and cross-domain leakage. We distinguish two governance decisions: admission, which determines what recalled information enters the working context, and presentation, which determines how admitted information is expressed. We implement two inference-time designs without retraining: factor-compiled admission (FC), which assesses whole memory entries, and permission-semantic admission (PS), which decomposes entries into typed units; both translate adjudicated attributes into eligibility decisions via deterministic policies. We evaluate on a four-backbone development suite and an external benchmark with four tasks of 300 samples each. Relative to verbatim injection, FC and PS reduce pooled judge-assessed failure rates on the external benchmark by 6.7 and 8.8 percentage points (p = 2.7e-7 and 4.1e-12), and development-set cross-domain leakage falls by up to 29.5 percentage points. A query-conditioned

---

### [76] Design Creativity Bench: Measuring creativity in LLM-Generated UI

**链接**: https://arxiv.org/abs/2610.11539
**作者**: Aman Rusia, Abhijit Bhole, Prashank Gupta, Dipanjan Dey
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As leading LLMs improve on capability evaluations, their limitations in producing creative outputs on design tasks remain insufficiently characterised. Our work introduces Design Creativity Bench, a benchmark that evaluates diversity and appropriateness in UI designs. It measures distinctiveness among models on the same prompt (originality), how much a model's designs change between two prompts for the same UI goal in different product domains (creative range), and the share of a brief's acceptance criteria each design meets (appropriateness). Originality is 0.592 for same-prompt design pairs from different models (95% CI [0.582, 0.602]), far below the 0.764 for same-prompt human-model pairs (95% CI [0.751, 0.778]). Creative range is 0.581 across models (95% CI [0.567, 0.597]), against 0.902 for human designs (95% CI [0.884, 0.919]). Appropriateness is above 90% for every model, and the best model reaches 99.2%, slightly above the 98.0% for human designs. Our work shows that the defaul

---

### [77] VFold: Symmetry-Aware Cross-Layer Value Cache Compression

**链接**: https://arxiv.org/abs/2610.12338
**作者**: Neha Verma, Sungwon Kim, Kenton Murray, Kevin Duh
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While caching key-value (KV) states accelerates Large Language Model (LLM) decoding, this cache can dominate memory usage at long context lengths. One solution is to compress this memory by exploiting inter-layer cache similarities. However, most existing techniques necessitate architectural changes to LLMs and incur substantial overhead. In this work, we propose a symmetry-aware value cache merging strategy that reduces cache memory while avoiding both harmful performance degradation and architectural overhead during decoding. Furthermore, we show that this approach can be exploited alongside existing cache compression techniques, composing with high-ratio quantization or key cache pruning to reach compression ratios that neither method reaches alone, with minimal additional cost. Ultimately, our findings reveal a major source of underutilized capacity in the value cache, offering a simple yet highly effective direction for scaling context windows under memory constraints.

---

### [78] Transect: Retaining Observability for Long-Horizon LLM Agent Evaluations

**链接**: https://arxiv.org/abs/2610.08364
**作者**: Toby D. Pilditch, Konstantinos Voudouris, Alexandra Abbas, Cozmin Ududec
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] LLM-powered Query Expansion for Enhancing Boundary Prediction in Language-driven Action Localization

**链接**: https://arxiv.org/abs/2505.24282
**作者**: Zirui Shang, Xinxiao Wu, Shuo Yang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] Speedbumps: Rejection Attacks on Speculative Decoding

**链接**: https://arxiv.org/abs/2610.10929
**作者**: Adam Y. J. Jones, Yu Yuan, Sergio Maffeis
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding is a popular technique for increasing the speed and reducing the costs of large language model (LLM) inference by verifying multiple draft tokens in a single target-model forward pass. The resulting benefit depends on the ability of the drafter to approximate the target model's distribution. In this work, we study Speculative Rejection Attacks (SRAs), a novel class of attacks that cause draft and target models to disagree more often, resulting in fewer draft tokens being accepted per draft cycle. This leads to more target model forward passes needed per generated token, slowing down inference and increasing costs for the victim. We introduce two attacks which append an adversarial suffix to attacker-controlled content to degrade speculative decoding on a victim's prompts. Both attacks optimise the expected length of the accepted speculative prefix, estimating per-depth acceptance from the target's probability of the drafted proposals (Speedbump-P) or from the overl

---

### [81] Black-Box Forensics for Conversational LLM Agents

**链接**: https://arxiv.org/abs/2606.22698
**作者**: Isadora White, Yasaman Jafari, Taylor Berg-Kirkpatrick
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] Curating Always-Loaded Context for LLM Agents: A Capacitated Assortment Model with Censored Feedback

**链接**: https://arxiv.org/abs/2610.11007
**作者**: Zexuan Liu, Yuning Yang, Tiancheng Zhao
**来源**: cs.AI cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> At the start of every session, LLM agents load a fixed context file, such as $\texttt{AGENTS.md}$. Each loaded token in the file is charged again in every later round of the session, and these files can degrade performance as they grow in size. However, in practice, human or automated curators usually grow these files by appending. We formulate context curation as a capacitated assortment problem. Instructions consume tokens under a finite attention capacity; adding an instruction never raises the compliance of the others, while retained instructions incur a per-session setup cost. We prove an upper bound on the optimal file size, regardless of the number of available candidate instructions, and that appending every instruction with positive standalone value can be arbitrarily worse in net value than selecting an optimal subset. A token budget also limits the loss when the token price is underestimated. We then examine what can be learned from past sessions and how this information can

---

### [83] StoreBench: A Live-Commerce Environment for Evaluating and Training Autonomous Operator Agents

**链接**: https://arxiv.org/abs/2610.10942
**作者**: Daksh Raghuvanshi, Ved Vedere, Yifan Wang
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning environments are now a primary lever for improving large language model (LLM) capabilities in post-training, yet most agentic benchmarks remain static: the world moves only when the agent acts, the reward is a terminal verdict, and the pass bar is set arbitrarily. We introduce StoreBench, a live-commerce environment in which an agent runs a mid-size online apparel store on a production-grade commerce backend, testing long-horizon planning and economic judgment under uncertainty. Customers order around the clock, suppliers reprice and fail, and market shocks arrive with partial or no warning. The agent acts through the same 29 merchant tools a human operator would use, under a windowed operation budget that makes simulated time a function of actions taken, so model latency cannot influence simulated time. Pass thresholds are calibrated against scripted anchor policies, the reward is hardened against a catalogue of reward hacks, and every episode replays identicall

---

### [84] iAm.md: Robot Skill Self-Assessment through Agentic Introspection for Unknown Open-Vocabulary Domains

**链接**: https://arxiv.org/abs/2610.10962
**作者**: Vincenzo Guarino, Emanuele Musumeci, Vincenzo Suriani, Daniele Nardi
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic AI based on Large Language Model generalization capabilities offers a wide range of potential applications, including planning for embodied tasks. For example, embodied agents based on Foundation models can generate plausible plans in autonomous robotics scenarios. Due to limited context windows or hallucinatory phenomena in the next-token prediction formulation, behaviors may be generated without establishing whether the deployed robot and the observed environment actually support the requested operation, in what we call a "grounding failure". Thanks to the recent improvements in reasoning capabilities of foundation models, autonomous robot behavior generation problem can be formulated as a code generation problem. We present iAm.md, a Markdown standard and generation framework, that allows anchoring this process in complementary forms of deployment evidence. Through open-vocabulary semantic mapping, we combine local vision-language detections and object segmentation and refer

---

### [85] TestJack: Should you trust the results in coding benchmarks? Agentic Coding Benchmarks Auditing via Evaluator Evolution

**链接**: https://arxiv.org/abs/2610.10619
**作者**: Shuangjie Yao, Hao Wang, Koushik Sen, Simin Chen, Baishakhi Ray, Dawn Song
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are rapidly reshaping software engineering, accompanied by an explosion of new code benchmarks. Yet nearly all existing benchmarks still rely on the same decades-old criterion: a solution is correct if it passes a fixed set of unit tests. Such tests are often insufficient: they check only part of what the task requires, so agents can reward hack them or silently miss required behavior while still passing every test. As a result, higher benchmark scores may partly reflect better adaptation to the evaluator rather than better problem solving. Existing works focus on static test augmentation: they strengthen each task's tests once, before any trial is seen, and thus overlook how real trials actually fail. We introduce TestJack, a scalable framework for evaluating patches beyond fixed tests. For each trial, TestJack generates tests targeting prompt requirements the patch may violate, retains only tests passed by the ground-truth patch, and re-examines any 

---

### [86] FlowState: Execution State as Memory for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.34565
**作者**: Minghao Li, Bangyan Li, Zifan Wang, Yulong Li, Hu Xu, Gan Zhang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] ReCast: Attribution-Oriented Step Representation Learning for LLM-Based Agent Systems

**链接**: https://arxiv.org/abs/2610.11334
**作者**: Weilin Jin, Mingyu Wang, Taiyu Zhu, Ziqi Zhou, Wenbo Li, Haoyang Huang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM-based agent systems, failures can originate from early steps whose effects propagate through subsequent interactions, making their origins difficult to identify. To trace such failures back to their origin, failure attribution has been formulated as the task of identifying the earliest step responsible for the failure. Recent methods leverage LLM internal signals for failure attribution, typically using hidden states as step representations. We therefore conduct an empirical study to evaluate how effectively these representations distinguish root-cause steps from other steps and find limited separation. Motivated by this observation, we propose ReCast, a step representation learning method that transforms hidden states from a frozen LLM into attribution-oriented step representations. ReCast first selects attribution-relevant layers, then constructs complementary pattern and deviation features, and finally learns contextualized step representations through an encoder trained with

---

### [88] From a Prompt to Repertoires: Evolving Functional REpertoires Enable LLM Continual Learning

**链接**: https://arxiv.org/abs/2610.11373
**作者**: Fengyuan Liu, Yue Wang, Hangxi Guo, Fengyuan Liu, Chenxu Wu, Yanguang Liu 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual learning remains challenging for large language models, which must enable models to acquire new skills and knowledge without degrading existing capabilities. Existing approaches typically address this challenge by carefully designing how model parameters are updated. In contrast, prompt optimization avoids costly parameter updates while achieving competitive or even superior performance to reinforcement learning methods such as GRPO on individual knowledge-intensive and reasoning tasks. This raises a natural question: \textit{Can prompt optimization, as an efficient adaptation approach, be directly applied to continual learning?} Our analysis shows that, under sequential task adaptation, it suffers from catastrophic forgetting, while optimized prompts accumulate rules that overfit to local task distributions. To address these limitations, we propose \emph{Evolving Functional REpertoires} (EFRE), which replaces a single prompt with a repertoire of functions that evolves as new

---

### [89] Beyond Sequences: Distilling Structured Decision Memory for LLM Recommendation

**链接**: https://arxiv.org/abs/2610.11501
**作者**: Leikun Liang, Guoshuai Wang, Xingsheng He, Yushan Han, Yunyi Xuan, Xiaoxiao Xu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the adoption of large language models (LLMs) in recommendation systems, prevailing approaches mostly model single-type behaviors (e.g., views or purchases). Even when incorporating multiple behaviors, existing methods flatten heterogeneous actions into homogeneous token sequences, ignoring their distinct decision-making roles. This flattening fails to capture semantic hierarchies and contextual nuances in complex decision-making, such as trade-offs between price and quality. Consequently, performance degrades in critical ``difficult-choice'' scenarios involving highly similar items. To bridge this gap, we propose MARI (Memory-Augmented Recommendation with Interpretability), which grounds predictions in explicit, structured decision evidence. MARI maintains a Decision Memory Bank (DMB) that archives users' past rationales as Structured Decision Memories (SDMs): concise records of goals, constraints, and trade-offs. These SDMs are generated offline via Post-Hoc Decision Distillat

---

### [90] From Retrieval to Reconstruction: Constructing Evolvable Cognitive Memory for Long-Term Dialogue

**链接**: https://arxiv.org/abs/2610.11314
**作者**: Zirui Liao, Zhengxian Wu, Zhuohong Chen, Yunyao Yu, Xiaoyu Liu, Yifan Xu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) serving as long-term dialogue agents require memory systems that support reliable reasoning over extended interactions. However, existing Retrieval-Augmented Generation (RAG) frameworks typically treat memory as passive storage, making it difficult to distinguish source-attributed beliefs from unattributed event/fact records and to connect evidence dispersed across sessions. We introduce CogMem, a cognitive memory architecture based on the PEC$^2$F (Person-Event-Concept-Claim-Fact) graph schema. Dedicated Claim nodes preserve the source and target of subjective statements, while Fact and Event nodes represent semantic and episodic knowledge. Dialogue turns are incrementally converted into provenance-aware graph records, consolidated into higher-level facts, and reconciled into temporally scoped Claim views when the same source provides conflicting updates. For retrieval, a rule-based controller driven by LLM intent parsing composes four deterministic graph 

---

### [91] Do LLMs Learn from Rewards in Context? : Rethinking the role of reward in In-Context Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.11152
**作者**: Minchan Kwon, Seunghee Koh, Sunghyun Baek, Minsung Bae, Junmo Kim
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly improve at inference time by accumulating experience in context rather than by updating parameters. This process is often described as in-context reinforcement learning (ICRL). Whether in-context learning (ICL) can actually play the role of RL, however, has not been tested. We study this question in its simplest form, direct ICRL, where the model conditions directly on raw trajectory-reward pairs, and ask whether the reward acts as a learning signal. Through controlled experiments on four benchmarks across six models, we find that the reward is read, but its effect is small: flipping, randomizing, or removing the reward leaves the improvement curve almost unchanged, and this holds even under meta-prompts that explicitly instruct the model to explore, exploit, or reason over rewards. Trajectories drive improvement, but not through their semantic content: shuffled or corrupted trajectories work as well as real ones. These patterns closely mirror those known in ICL

---

### [92] Internalizer: Portable Context-to-Parameter Mapping for Very Large Language Models

**链接**: https://arxiv.org/abs/2610.11715
**作者**: Peter Devine, Nick Ryan, Benjamin Sirb, Alex Chiocchi
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hypernetworks that map a context directly to a LoRA adapter let a large language model carry that context in its weights, but prior work has demonstrated them only on base models of up to 14 billion parameters. We present the Internalizer, a state-of-the-art, portable Context-to-Parameter Mapping hypernetwork that generates document-specific LoRA adapters for the frozen 284B-parameter DeepSeek v4 Flash, a target two orders of magnitude larger than in any previous work. Most of its parameters live in a model-agnostic trunk with only thin entry and exit layers per base model, so it trains cheaply against small models before being ported to the large one. On unseen documents of up to 4096 tokens, the generated adapters reach 84.9% top-1 and 97.8% top-5 teacher-forced accuracy against 63.4% and 83.5% for the base model, with nothing in the context window but a three-word instruction. Once the hypernetwork is trained, a single forward pass turns any document into an adapter for such a model

---

### [93] Prompts versus Rules: Auditing and Controlling Speech Naturalness Behaviors in Voice User Simulators

**链接**: https://arxiv.org/abs/2610.11015
**作者**: Riqiang Wang, Elena Khasanova, Harsh Saini, Lex Konnelly, Parsa Kavehzadeh, Matthias Lee 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As voice agents gain more popularity commercially, the user simulators used to evaluate the deployed agents are also being developed to include more realistic, variable, and diverse speech naturalness behaviors -- disfluency, interruption and backchanneling. The quality of the user simulator directly affects the validity of agent evaluation results. However, we find that most studies so far have not examined in detail whether the intended configuration for these behaviors is realized in the simulation. In this study, we audit the realized naturalness behaviors of tau-Voice, our own LLM-based prompting approach across three models, and our rule-based injection algorithm for disfluency, interruption, and backchanneling. We find that prompting for these behaviors is unreliable and produces speech inconsistent with the instructions, placed and distributed less naturally than the instruction implies. In contrast, our rule-based, model-free algorithm produces controllable and diverse natural

---

### [94] When Interfaces Speak: Data-Aware Generative UI Harness for Active Interaction

**链接**: https://arxiv.org/abs/2610.11123
**作者**: Xiaolong Li, Xiaohan Xu, Jinyang Li, Xinnuo Xu, Ge Qu, Nan Huo 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most human-agent interaction today remains text-based. Natural language can impose cognitive overload, ambiguity, information chaos, and slow input for complex tasks; ephemeral generative UIs can present structured information and guide users toward task completion. We propose GenUI-Harness, a multi-agent harness pairing a Tool Agent for information retrieval and task execution with a GUI Coder Agent that identifies ambiguities and generates front-end code for structured interfaces. Training the coder with reinforcement learning is challenging: verifiable rewards for interactive UI generation require costly execution, while LLM-as-a-Judge rewards are prone to reward hacking. We address the first challenge with Dynamic UX, a lightweight package for dynamic interaction and reward collection in a single sandbox, and the second with Reward Auditor, a meta-reward mechanism that monitors reward distributions and distills diagnostic patterns into a shared rubric and scoring specification. We 

---

### [95] Agentic-TTT: Training test-time policy for test-time training

**链接**: https://arxiv.org/abs/2610.12002
**作者**: Jiahao Lu, Mohan Kankanhalli
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time training (TTT) adapts an LLM's parameters using signals derived from test inputs, and can make striking improvements in pre-specified settings such as IMO competitions or designated open problems. By turning deployment experience into parameter updates, TTT provides a direct mechanism for model-level self-improvement. Yet TTT is not universally beneficial: each TTT algorithm works in different settings, and applying an ill-suited method could waste test-time compute or even damage model performance. Therefore, such parameter-level self-improvement requires agency: the model must decide when TTT is warranted, which algorithm to invoke, and whether an existing skill can be reused. To fill this gap, we introduce Agentic-TTT, which learns a test-time policy to govern those decisions. Agentic-TTT turns TTT procedures into callable tools, treats accumulated skills as an evolving deployment environment, and trains its policy using the observed utility gains from its decisions. On ou

---

### [96] Caught in the Act: Probes Effectively Detect Sabotage and Catch Unverbalized Deception

**链接**: https://arxiv.org/abs/2610.12445
**作者**: Oskar J. Hollinsworth, Alex F. Spies, Tigist Diriba, Adam Gleave, Chris Cundy
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent incidents have highlighted the challenge of monitoring LLM agents and the danger of models deceiving people. We show that white-box deception detection via probes can be scaled up to frontier monitoring settings by collecting the largest deception dataset to date for training probes and introducing a novel probe architecture which can aggregate information across many layers and tokens. Our probes achieve 98.8% AUC in SHADE-Arena, surpassing an Opus 5.5 text-monitoring baseline, and show improved efficacy as the underlying model is scaled up. To push our probes to their limit, we test them on several cases where deception cannot be determined from the context alone. In these cases, which we refer to as introspective deception, the ground truth can only be determined through careful elicitation or thorough knowledge of a model's training data. In one such evaluation, we show that probes can distinguish transcripts containing a model's true hidden goal from other goals with an AUC

---

### [97] SignRAG: Unified Retrieval-Augmented Gloss-Free Sign Language Translation

**链接**: https://arxiv.org/abs/2610.11371
**作者**: Zhi Rao, Yucheng Zhou, Qianran Sun, Yiqing Huang, Longcan Yuan, Jiayi Hou 等 (10 人)
**来源**: cs.CL cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contemporary decoder-only large language models (LLMs) have demonstrated strong capabilities across a wide range of domains. However, existing pretraining paradigms for gloss-free sign language translation (SLT) are largely designed around conventional encoder-decoder pretrained language models, which limits their direct applicability to decoder-only LLMs. To address this limitation, we propose SignRAG, a unified framework combining hierarchical pretraining, target-domain retrieval augmentation, and retrieval-aware reinforcement fine-tuning. Hierarchical pretraining first learns linguistically grounded sign representations and then jointly aligns the sign encoder with an LLM, mitigating cross-modal optimization imbalance. For downstream adaptation, SignRAG complements parameter-based fine-tuning with a target-domain retrieval gallery that provides instance-specific translation cues. To ensure that retrieved contexts are used appropriately, we further introduce Retrieval Utility-Guided 

---

### [98] GRPODropout: Less is More for Online Reinforcement Learning Rollouts

**链接**: https://arxiv.org/abs/2610.11854
**作者**: Hexuan Deng, Zihao Yan, Xuebo Liu, Shuo Nie, Yue Wang, Chen Wang 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) methods such as GRPO substantially improve large language model reasoning but often suffer from policy entropy collapse: the loss of sampling diversity weakens exploration and limits further improvement. Existing methods address this issue either through algorithm-level interventions, such as reward modification and entropy/KL regularization, or through token-level reweighting. We investigate a complementary perspective: entropy collapse can also be mitigated by changing which generated rollouts contribute to policy updates. Under the same sampling budget, not all rollouts contribute positively to an update, and selectively excluding some can improve learning. To address this, we propose GRPODropout: before the standard update, we use a simple strategy that selectively removes a small number of high-probability positive-advantage rollouts and recenters the retained advantages. To motivate this design, we develop a rollout-level theoretical analysis that guid

---

### [99] FloorSAV: Elucidating Spatial Audio-Visual Context with 2D Floormap for AV-LLMs

**链接**: https://arxiv.org/abs/2610.11310
**作者**: Kyeong-Rae Kim, Sungnyun Kim, Tae-Hyun Oh
**来源**: cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While 3D spatial reasoning in dynamic egocentric environments is crucial for embodied intelligence, audio-visual large language models (AV-LLMs) lack explicit mechanisms to process and internalize global geometry directly from raw sensory streams. Existing approaches either require costly fine-tuning or underutilize the model's cross-modal reasoning capacities. In this paper, we propose FloorSAV, a novel framework that explicitly grounds spatial audio-visual context by rendering a dynamic 2D floormap. By integrating 3D point clouds, camera trajectories, spatial audio cues, and semantically grounded object landmarks, we inject this floormap into the AV-LLM as a synchronized stream with an egocentric video. AV-LLMs utilize their multi-modal capabilities to jointly reason over visual, auditory, and geometric cues in a single inference with floormap interpretation guidance. We further introduce SAVED-Bench (Spatial Audio-Visual Egocentric Benchmark with Dynamic Agents), constructing essent

---

### [100] Safe Actions Alone Do Not Ensure Safe Agents: Identifying Unfulfilled Obligations with Guard Models

**链接**: https://arxiv.org/abs/2610.11773
**作者**: Youwei Feng, Yitong Zhang, Yuetong Liu, Jia Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Guard models are increasingly used to safeguard LLM-based agents, primarily by identifying actions that agents are forbidden to perform. However, identifying forbidden actions alone is insufficient to ensure agent safety. In this paper, we argue that agent safety also depends on identifying required yet unperformed safety-critical actions, which we call obligations. Our preliminary study on a popular benchmark for evaluating safety shows that 56.92% of GLM-5.3 trajectories contain unfulfilled obligations, compared with only 30.00% containing forbidden actions. This finding reveals unfulfilled obligations as a major and previously overlooked source of safety risk. However, to our knowledge, no existing benchmark evaluates whether guard models can identify these obligations. To close this gap, we introduce ObligationBench, the first benchmark for evaluating the capability of obligation identification, comprising 240 expert-validated trajectories covering issue resolution, feature develop

---

### [101] Predicting Alignment Generalization with Value Representations

**链接**: https://arxiv.org/abs/2610.12410
**作者**: Andy Liu, Mehar Bhatia, Karolina Stanczak, Mona Diab, Vered Shwartz, Daniel Fried
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM developers post-train their models to exhibit prosocial values and behavioral traits, which are enumerated in an alignment target. However, while recent post-training developments have yielded models that score highly on alignment evaluations, training models on sets of narrow behaviors still influences their behavior across unseen contexts and environments in unexpected ways. In this paper, we establish the task of alignment generalization prediction, i.e., predicting how fine-tuning a model to follow a given value changes its behavior across a wide range of held-out values. We conduct a large-scale analysis of alignment generalization effects across 66 values found in modern alignment targets, and benchmark representational techniques on the alignment generalization prediction task. We find that representations based on model activations when applying values in context significantly outperform methods based on textual descriptions of the values. Specifically, the best activations

---

### [102] How to post-train on a surrogate: Envelope sampling mitigates reward hacking

**链接**: https://arxiv.org/abs/2610.11281
**作者**: Sanjit Dandapanthula, Shuvom Sadhuka, Samir Khan, Michael Oberst, Aaditya Ramdas, Alexandra Chouldechova
**来源**: cs.LG cs.AI stat.ME
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are commonly post-trained against LLM judges and other cheap surrogates because the true reward, such as human preference, is too expensive to query at scale. This practice often leads to reward hacking, where reinforcement learning against a miscalibrated surrogate leads to undesirable side effects. In this work, we study a setting in which a small number $n$ of model outputs are annotated with ground-truth labels (e.g., from expert review) and used to recalibrate the LLM judge before optimizing against it. Prior approaches to judge recalibration are costly or heuristic, and it is known that on-policy sampling fails when the surrogate is miscalibrated on a rare set of outputs. In this work, we propose envelope sampling, a theoretically-grounded method for judge recalibration that seeks to minimize an upper bound on the regret of the post-trained model under the assumption that the human reward and re-calibrated reward lie in an $L^2$ ball around the judge.

---

### [103] EvoAlloc: A Self-Evolving Resource Allocation Agent for Efficient Program Evolution

**链接**: https://arxiv.org/abs/2610.12086
**作者**: Yanning Dai, Yuhui Wang, Nanbo Li, Wenyi Wang, J\"urgen Schmidhuber
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based program evolution relies on evaluation feedback to guide the iterative search for high-performing programs. However, evaluation is often computationally expensive, making it essential to allocate limited resources to candidates that can most effectively advance the search. Existing LLM-based methods typically rely on fixed allocation strategies throughout the search, potentially wasting resources on low-value candidates while overlooking promising ones. We propose EvoAlloc, a self-evolving resource-allocation agent that learns from search experience to revise its strategy for allocating computational resources across candidates. EvoAlloc periodically consolidates prior search and allocation outcomes into reusable experience, which informs subsequent strategy revisions. It further uses a counterfactual exploration mechanism to occasionally evaluate candidates denied resources by the allocator, revealing their outcomes to enrich its experience for future strategy updates. Acros

---

### [104] LTBD: Learnable Trust-Boundary Delimiters for Prompt Injection Defense

**链接**: https://arxiv.org/abs/2610.11634
**作者**: Luman Zhao, Minghui Xu, Yue Zhang, Yijun Yang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) perform remarkably well on complex tasks, yet remain highly vulnerable to prompt injection attacks, where malicious instructions embedded in external data can override user intent. Existing defenses remain limited by model fine-tuning requirements, vulnerability to adaptive attacks, or reliance on brittle handcrafted prompts. We argue that a fundamental source of this vulnerability is the lack of an explicit representation of trust provenance. To address this, we introduce Learnable Trust-Boundary Delimiters (LTBD), a lightweight defense that explicitly encodes trust boundaries in the input while keeping the LLM parameters unchanged. LTBD uses a small number of learnable delimiters to distinguish trusted user instructions from untrusted external data, enabling the model to better respect the intended trust hierarchy. Experimental results show that LTBD substantially outperforms inference-time defenses and performs competitively with training-based approache

---

### [105] Large Language Models for Machine Translation Quality Annotation: Humans and Models Are Both Challenged

**链接**: https://arxiv.org/abs/2610.10918
**作者**: Hala Almaghout, Christian Federmann, Qin Gao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are considered to be a more efficient and cost-effective alternative to human judgment for Machine Translation (MT) evaluation. With MT evaluation spanning a large number of language pairs, domains and levels of annotation granularity, LLMs must be thoroughly evaluated across these dimensions before being reliably used as alternatives to human evaluation. In this paper, we evaluate the performance of LLMs for two prominent MT quality evaluation schemes: Multidimensional Quality Metrics (MQM) and Error Span Annotation (ESA) by comparing their agreement with human annotators. We present results on a long-context test set of 70 language pairs and the publicly available WMT23 and WMT25 data, investigating both score and error span annotation agreement across a variety of language pairs and domains. Our results show that while LLM agreement with human annotators exceeds agreement between human annotators for some evaluation tasks, both vary substantially across 

---

### [106] Sera: Semantic Representation Aggregation for Reliable and Interpretable Battery Health Forecasting

**链接**: https://arxiv.org/abs/2610.11567
**作者**: Jiawei Li, Fang Liu, Wei Zhang, Zuming Liu, Man-Fai Ng, Zhi Wei Seh
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Battery state of health (SoH) forecasting is important for battery management, but remains challenging due to nonlinear degradation and heterogeneity across batteries. Existing data-driven approaches primarily use temporal models to learn from numerical battery time series, and higher-level degradation characteristics are often not explicitly represented. These characteristics, however, can provide degradation guidance to support reliable forecasting and make the influence of degradation more interpretable. In this paper, we propose \textsc{Sera}, a \underline{se}mantic \underline{r}epresentation \underline{a}ggregation framework that complements temporal modelling with degradation semantics. Guided by battery domain expertise, \textsc{Sera} extracts degradation semantics from time series and constructs two complementary representations using rule-based knowledge and LLM-based interpretation. The representations are independently encoded and integrated with the representation learned b

---

### [107] ILM: An AI-Powered Storytelling Educational Tool

**链接**: https://arxiv.org/abs/2610.12064
**作者**: Suhaila Mohammed, Abdelaziz Serour, Allison Lahnala
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital technologies have made Islamic narratives more accessible, but existing platforms provide limited support for structured learning and comprehension of these stories, particularly in Arabic and multilingual settings. We present ILM, an interactive educational platform for Stories of the Prophets that combines Arabic natural language processing, structured knowledge representation, and retrieval-based question generation. Admin-approved Arabic narratives are processed by a Knowledge Graph (KG) Constructor Engine that identifies entities and narrative relationships and stores them as structured knowledge, enabling learners to explore stories through a visual story map and answer entity- and relation-based questions generated from the KG. Separately, a multilingual retrieval pipeline retrieves relevant passages from the original narratives to generate multiple-choice and open-ended comprehension questions. For open-ended questions, an LLM-as-a-Judge evaluates learners' answers agai

---

### [108] Who Verifies the Verifier? Co-Evolving Inspectable Graders with Self-Improving Agents

**链接**: https://arxiv.org/abs/2610.11464
**作者**: Xing Zhang, Guanghui Wang, Yanwei Cui, Ziyuan Li, Wei Qiu, Bing Zhu 等 (7 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We changed the agent: did it actually get better? Every self-improving agent loop answers this hundreds of times, and every answer comes from a verifier. On open-ended tasks none exists, so the loop is handed a hand-written rubric or a bare LLM judge grading output from a model like itself, inviting reward hacking and shared blind spots. We make the verifier the evolving object: an inspectable expression over small, mostly deterministic drawback detectors, synthesized from clustered failures, gated at birth, and selected for agreement with a ten-item anchored reference set plus consensus over unlabeled outputs, never for the agent's score. On MBPP+ it gains +0.21 held-out agreement over the hand-authored seed composition, on every seed, and ends ahead of the bare LLM judge it contains. One finding should change how co-evolved verifiers are validated: removing the anchor guards collapses the verifier into a vacuous always-pass grader, yet that collapsed verifier trains skills just as we

---

### [109] Reading the Room: Foundations, Design, and Challenges of Normative Competence in LLMs

**链接**: https://arxiv.org/abs/2610.10906
**作者**: Andrea Wynn and Harsh Satija and Seokhyun (Nathan) Baek and Anqi Liu and Eric Nalisnick and Gillian K. Hadfield
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human communities are governed by normative systems: shared standards that produce \textit{norms} dictating acceptable behavior, enforced through community sanctioning. Aligning increasingly autonomous AI systems with these norms is a central alignment challenge, complicated by the fact that norms are vast in number, change quickly, and are often arbitrary (e.g., dress or language conventions). Thus, alignment requires \textit{normative competence}: the ability to discern from interaction alone what norms a community enforces without relying on static pretrained knowledge. We introduce a multi-agent community debate setting, where access to debate is governed by synthetic norms, to study normative competence in isolation from pretraining exposure. We show that baseline LLM agents fail to learn norms even when doing so would improve their accuracy. We then experiment with various \textit{normative modules} -- architectural components for norm inference -- finding that norm-following is 

---

### [110] Memento 3: Model-Based Recursive Self-Improvement through Reflective Rulebooks

**链接**: https://arxiv.org/abs/2610.11794
**作者**: Haoyu Zhao, Zhengxu Yu, Zhiyuan He, Meng Fang, Rasul Tutunov, Haitham Bou-Ammar 等 (8 人)
**来源**: cs.AI cs.CL cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning to act in unfamiliar environments requires agents to infer how the world works and revise that understanding as new evidence arrives. Yet limited observations can support multiple world models that explain past interactions but predict different outcomes in unseen states. We introduce Memento 3, building on the Memento series to enable frozen LLM agents to continually learn explicit world models through external memory. The agent maintains a natural-language rulebook as persistent semantic memory, recording revisable hypotheses about environment dynamics while leaving unknown aspects underspecified. It compiles this rulebook into executable code for prediction and planning. Through a continual loop of observation, reflection, rule revision, compilation, and verification, the agent uses prediction errors to refine both the rulebook and its code. Updated code is accepted only when the LLM judges it faithful to the rulebook and cell-exact replay reproduces the observed transition

---

### [111] "Hot-Blooded" vs "Cold-Blooded": Simulating the Behavioral Phenotypes of Childhood Aggression via Generative Agents

**链接**: https://arxiv.org/abs/2610.11951
**作者**: Liping Fu
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study examines the construct validity of LLM-based generative agents in simulating reactive, proactive, and co-occurring aggression in children. Four distinct agents were instantiated using a theory-driven parameterization grounded in the social information processing model. A total of 1,920 simulation runs were conducted across eight social scenarios, employing a hybrid blind-coding pipeline to extract 32 quantitative behavioral indicators. Results demonstrate robust discriminant validity relative to a non-aggressive baseline, with large effect sizes. High cross-seed reliability confirms that behavioral differentiation is driven by underlying psychological parameters rather than model stochasticity. Qualitative narrative analyses further converged with established empirical literature. Overall, these findings indicate that theory-parameterized LLM agents can accurately reproduce distinct aggression subtypes, offering a scalable, highly controllable framework for hypothesis genera

---

### [112] Coverage-Aware Reasoning with Medical Tokens for Diagnosis Prediction

**链接**: https://arxiv.org/abs/2610.10641
**作者**: Kaisong Zhang, Haotian Fang, Junmeng Zhou, Hang Lv, Yulan Pan, Yanchao Tan
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) offer promising potential for next-visit diagnosis prediction, owing to their ability to integrate longitudinal clinical evidence and reason over it in natural language. However, reinforcement learning for LLM reasoning commonly rewards each trajectory according to the correctness of its final answer. In next-visit diagnosis prediction, multiple diagnoses can be simultaneously valid, but independently rewarding one diagnosis per trajectory does not distinguish repeated hits from coverage of different diagnoses. The policy can therefore concentrate on a few correct diagnoses, leaving others uncovered. Meanwhile, LLM tokenizers can split ICD codes into several generic tokens with limited clinical meaning, requiring multiple decoding steps to predict each diagnosis and hindering reasoning over a large disease vocabulary. To address both challenges, we propose CARing, a framework that represents diagnoses with compositional Semantic IDs (SIDs) and optimizes rea

---

### [113] EgoVoice: Proactive Spoken Assistance from Egocentric Multimodal Streams

**链接**: https://arxiv.org/abs/2610.12248
**作者**: Heeseung Kim
**来源**: cs.CL cs.CV cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wearable augmented reality (AR) assistants are moving toward continuous real-world interaction, where they perceive the user's activity through first-person video and audio and provide timely spoken guidance without being explicitly asked. While proactive video assistants, spoken dialog systems, and egocentric task understanding have each advanced rapidly, existing systems do not address the joint problem of deciding when to speak and what to say from continuous first-person streams. We introduce EgoVoice, a framework for training and evaluating proactive egocentric spoken assistants. From HoloAssist video recordings of real human instructors, we construct clean audio streams through source separation and speech resynthesis, and convert each video session into a format where the model must decide at each moment whether to remain silent or provide spoken guidance. We fine-tune an omni-modal LLM with our data, and further improve its proactive intervention behavior with direct preference

---

### [114] Unlocking the Regulatory Genome by ARGUS: An Evidence-Constrained Agentic Framework for Interpreting Single Nucleotide Variants

**链接**: https://arxiv.org/abs/2610.12281
**作者**: Pratik Dutta, Matthew B. Obusan, Max Chao, Rekha Sathian, Nimisha Papineni, Ramana V. Davuluri
**来源**: q-bio.GN cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Over 90% of disease-associated variants from genome-wide association studies fall in noncoding regulatory regions, yet their functional interpretation remains a central open problem in genomic medicine. Large language models prompted to interpret such variants routinely hallucinate transcription factor (TF) binding changes, fabricate experimental support, and assign biological significance to statistically negligible signals. We present ARGUS (Agentic Regulatory Genomics for an Uncertainty-aware Scientist), which strictly separates deterministic biological computation from LLM-mediated reasoning. ARGUS wraps 458 DNABERT-based TF binding models in a hypothesis-directed investigation loop where a planner selects evidence sources based on current uncertainty, a verifier deterministically interprets each observation, and intermediate results change the investigation path. On variant rs6983267 at the 8q24 cancer risk locus, the same planner produces four divergent trajectories for four TFs.

---

### [115] Harness Evolution Hits a Ceiling: When Weight Training Should Begin

**链接**: https://arxiv.org/abs/2610.11655
**作者**: Yuan Tian, Bing Hu, Hao Wang, Binghang Lu, Fang Wu
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving a long-horizon LLM agent means evolving the harness around a frozen model or training its weights. We let a self-evolving harness make the system stronger first, then cross seed and evolved harnesses with base and trained weights to learn which gains the trained model keeps and which still need the runtime. We show that the right lever can be read off the agent's failure composition: labelling failed trajectories by the first signal that fires separates process failures (blocked calls, loops, exhausted step budgets) from content failures (a delivered plan that is poor). Harness evolution repairs the former, the behaviour it instils can be trained into the weights, and content failures are what weight training is for. On DeepPlanning, a self-evolving harness loop lifts the held-out score of Qwen3.5-4B from 0.16 to 0.30 and of Qwen3.5-9B from 0.32 to 0.44; for 4B, held-out delivery rises from 55% to 90% while content failures are left for the weights. LoRA adapters trained on e

---

### [116] NeuroDivSim: An Interactive Tool for Model-Based Reflection on Cognitive Diversity in Interface Design

**链接**: https://arxiv.org/abs/2610.11590
**作者**: Eske Beckefeld and Henrik H.J. Detjen
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent approaches to simulated and synthetic users offer new ways to support design, but raise questions about how computational representations of users should contribute to design practice. We present NeuroDivSim, an interactive tool that explores simulation as an inspectable mechanism for reflecting on cognitive diversity during design and prototyping. Rather than using an LLM to act as a simulated user, NeuroDivSim uses generative AI to construct inspectable task, interface, and environment models from a usage scenario. After human review, these models are combined with explicit cognitive reference configurations and processed through deterministic simulation. This enables designers to hold a modeled usage situation constant while varying cognitive assumptions and tracing their consequences to interaction steps and rule-based design recommendations. We further report an exploratory pilot evaluation (N=10) that provided formative insights into how participants engaged with the workf

---

### [117] FedAlphaEdit: Null-Space-Aligned Merging for Collaborative Knowledge Editing

**链接**: https://arxiv.org/abs/2610.11033
**作者**: Sota Sugawara, Yukihiko Okada
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multiple institutions may each hold their own private knowledge edits and wish to integrate them into a single large language model without sharing raw edit requests. Null-space-constrained editing methods such as AlphaEdit mathematically guarantee that each update leaves unrelated knowledge intact, while collaborative frameworks such as CollabEdit aggregate edits from multiple clients without data sharing. Combining the two appears trivial. However, we show that this naive combination fails structurally, and we identify its cause. Guided by this analysis, we propose FedAlphaEdit. To our knowledge, this is the first collaborative knowledge editing framework that aligns both local editing and the server-side merging rule under a single null-space principle for preserving existing knowledge. FedAlphaEdit builds on null-space-aligned merging, in which clients share projected statistics and the server provably recovers the result of editing everything in one place under a one-shot idealiza

---

### [118] Perceptually Grounded and Semantics-Aware Evaluation for Holistic Co-Speech Gesture Generation

**链接**: https://arxiv.org/abs/2610.11669
**作者**: Nick Milkin, Lanmiao Liu, Esam Ghaleb, Asli Ozyurek, Zerrin Yumak
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Holistic and semantics-aware co-speech gesture generation has advanced rapidly, yet evaluation remains behind: objective metrics do not consistently reflect human perception, and semantic appropriateness remains difficult to quantify. We present a perceptually grounded and semantics-aware benchmark that combines standardized model comparison, human-centered metric validation, and fine-grained semantic evaluation. We first curate a list of 13 objective metrics covering different aspects, including distributional similarity, geometric fidelity, kinematic quality, cross-modal synchrony, and semantic appropriateness. For the semantic-appropriateness category, we propose a new metric, Semantic Gesture Preservation (SGP), which measures how far semantic gestures in the ground truth are preserved in the generated gestures. For this, we augment the BEAT2 dataset's annotations using a multi-modal LLM. We then conduct a perceptual study where 101 participants score generated gestures among five 

---

### [119] REMORY: Learning Residual Memory for Context Compaction

**链接**: https://arxiv.org/abs/2610.11287
**作者**: Hanchen Xia, Baoyou Chen, Yutang Ge, Naihao Deng, Senqiao Yang, Zilong Dong 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon agents compact their history to continue within a finite context window, but a textual summary alone may not support every subsequent decision. We introduce REMORY, a neural memory network that supplements the summary with a bounded sequence of soft memory tokens. Given the history and summary, the network learns to generate tokens that help a frozen LLM approximate the continuation it would produce with the full history. The tokens are conditioned on the summary and appended after it, forming an analogue of a residual connection along the sequence dimension. On SummHay, REMORY improves source attribution at nearly unchanged insight coverage and approaches the full-context joint score using only 5.2% of the input positions. Across long-horizon agent benchmarks, Qwen3.8-27B and GLM-5.3-Flash show consistent gains with residual memory. Both models also exhibit substantially fewer repeated tool outputs and tool errors on BrowseComp and Terminal-Bench 2.1.

---

### [120] Workerville: Towards an Organizational Behavior Account of Agent Safety

**链接**: https://arxiv.org/abs/2610.11561
**作者**: Hanjun Luo, Junting Mao, Yuhan Lu, Haobo Zhang, Zhimu Huang, Yankai Chen 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents now interact with their environments continuously, shaped by such organizational channels as user instructions, peer messages, and long-term memory. Existing safety research has examined these influences, but largely as separate agent components. How such factors jointly shape an agent's safety behavior from a unified perspective remains unmeasured. To bridge this gap, we advocate organizational behavior (OB) as a framework for studying the safety of advanced agents, reorganizing the objects of study, theoretical foundations, and experimental design around the relational structure in which agents operate. We present the first systematic formalization of counterproductive work behavior (CWB), a canonical safety-relevant subfield of OB, as Agentic Counterproductive Behavior (ACB). ACB specifies three organizational antecedents (vertical supervisor relations, horizontal peer norms, and internal cognitive structures) and maps them onto three counterproductive outcome dimen

---

### [121] RISR: Residual-Informed Scientific Equation Discovery with Large Language Models

**链接**: https://arxiv.org/abs/2610.11387
**作者**: Haobo Li, Wenshuo Zhang, Wenxiao Zhao, Eunseo Jung, Rui Sheng, Yushi Sun 等 (9 人)
**来源**: cs.SC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Symbolic regression combines structural search with numerical fitting, but aggregate fit scores do not describe how the remaining error varies across inputs. We introduce RISR, a residual-informed method that uses these error patterns to guide formula discovery and learn which corrections are worth fitting. A residual encoder compresses aligned inputs, targets, current predictions, and residuals into continuous tokens that condition a language model to propose formulas. For subsequent refinement, a dual-view relational encoder uses additive and regularized multiplicative residuals to predict the post-fit utility of candidate corrections. We evaluate RISR on scientific tasks from the LLM-SRBench. RISR achieves 63.57% and 38.50% ID accuracy at the 1% and 0.1% pointwise relative-error tolerances, respectively. The corresponding OOD accuracies are 56.07% and 38.24%. RISR outperforms the reported baselines using the same backbone. The results show that our residual-informed approach can imp

---

### [122] WorldBench: Evaluating LLMs on Three.js Voxel World Generation

**链接**: https://arxiv.org/abs/2610.10622
**作者**: Krish Bakshi
**来源**: cs.GR cs.AI cs.CL cs.CV cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can now write complete, interactive 3D worlds as code, but grading those worlds automatically is unreliable. Existing judges take one view of the output: a vision-language model scores a few rendered snapshots, or a language model reads the source. On worlds written by five frontier models we find that the two views disagree on 32% of required items, mostly code that no frame shows, and that fixed views miss small close-up contents. We present WorldBench, a benchmark and judge for open-ended, LLM-generated Three.js worlds. From one prompt describing a floating voxel island with ten biomes, physics, and day/night and seasonal cycles, the judge explores the running world, controlling its clock, orbiting it, and sending a navigator agent to frame each biome, and reads the code for what it sees. Neither channel is trusted on its own: a code quote counts only if it is text the source contains, and visual claims are checked against measured pixels where the property is 

---

### [123] Deception by Omission: Language Models Knowingly Hide Their Mistakes

**链接**: https://arxiv.org/abs/2610.11351
**作者**: Lucas Florin, Amelie Knecht, Ulysse Schaller, Thilo Hagendorff
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly act as agents with little human oversight, so potential mistakes they make can go unnoticed. Users then depend on the model to report what went wrong. An honest model discloses its mistakes, while a deceptive one conceals them. However, it is unclear how current LLMs behave in such situations. In this study, we prefill LLM trajectories with synthetic mistakes. The trajectories resemble real deployments in chat and agentic settings. Models fail to disclose their mistake in 36.4% of chat and 67.1% of agentic rollouts. In 2.4% and 5.3% of rollouts, respectively, they are aware of the mistake in their chain of thought but still deceptively conceal it. Rates vary by model: for instance, Gemini 3.5 Flash knowingly conceals mistakes in up to 19.9% of agentic rollouts. In 11.9% of chat and 51.8% of agentic rollouts, models show no awareness of mistakes, even though they reliably spot them when reviewing the same transcript as an outside observer. Our r

---

### [124] Thinking Inertia: LLMs Keep Thinking When Told Not To

**链接**: https://arxiv.org/abs/2610.11765
**作者**: Dianqiao Lei, Kevin Qinghong Lin, Pan Lu, Philip Torr, James Zou
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) increasingly ship with explicit "thinking modes", yet their counterpart, "no-thinking", has received far less attention. We study LLMs' no-thinking behavior along two axes. a. How to measure no-thinking? Prior work typically defines no-thinking through proxies such as a disabled thinking mode or the absence of long traces. These proxies are unreliable: disabled thinking modes may still emit reasoning, while long traces may contain filler rather than genuine inference. We instead normalize each response into a pre-answer trace and final answer, and evaluate it at three levels: (i) Empty-Thinking Rate for strict answer-only compliance; (ii) instruction-aware Question-Pre-answer Relevance for similarity between the question and pre-answer trace; and (iii) LLM-as-judge Explicit Inference Rate for visible explicit inference. Together, these metrics distinguish answer-only output, relevant but non-inferential text, and explicit inference. b. How does no-thinking 

---

### [125] Conversational Voice Aesthetic Model with Reinforcement Learning from Human Listeners

**链接**: https://arxiv.org/abs/2610.10868
**作者**: Xilin Jiang, Shun Zhang, Tejas Jayashankar, Yinghao Aaron Li, Osama Hanna
**来源**: eess.AS cs.CL cs.LG cs.MM cs.SD
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Conversational Voice Aesthetic Model, a speech large language model for describing the voice aesthetics of real or synthetic speech responses in natural conversational contexts. Given a context and a response speech, CVAM describes salient moments that characterize the voice and predicts nine categorical attributes spanning gender, pitch, pacing, emotion, and delivery. The key challenge lies in perceptual fields such as emotion and delivery, which are inherently subjective and lack definitive ground truth. Therefore, we collect ~10 human annotations for each of 3k real and synthetic responses derived from the CANDOR corpus. CVAM is supervised finetuned on synthesized aesthetic descriptions and labels, then optimized with Group Relative Policy Optimization on human judgments. Experiments show that CVAM better agrees with human listeners than Gemini 3.1 Pro and open-source speech LLMs, and outperforms single-human-vs.-rest agreement. Together, we demonstrate the importance o

---

### [126] On the Clock: Towards Punctual and Productive Time-Budgeted AI Agents

**链接**: https://arxiv.org/abs/2610.10833
**作者**: Aaron Wang, Neelabh Madan, Vlad Sobal, Matthew Trager, Michael Kleinman, Elman Mansimov 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study whether small LLM agents can operate effectively under explicit wall-clock time budgets by both respecting the allocated runtime and using available time productively. We evaluate Qwen3.6-27B on five competitions from MLE-Bench Lite and Qwen3-4B on Zork I (Jericho), two agentic benchmarks where additional computational time can meaningfully improve performance. In the simplest setting, where the budget is stated only in the prompt, agents fail to translate the stated budget into controlled use of time. These failures arise from gaps in time awareness, since the harness provides no timing feedback, but also because they cannot reliably anticipate the duration of actions, and do not have a learned mapping from available time to an appropriate strategy. We investigate two complementary classes of interventions: harness-based mechanisms that expose timing information and enforce deadlines, and reinforcement learning with budget-aware rewards. Injecting timing information through t

---

### [127] Coverage, Not Difficulty, Sets How Much Synthetic Data an Activation Probe Needs

**链接**: https://arxiv.org/abs/2610.10594
**作者**: Ankush Checkervarty
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation probes that monitor deployed language models are trained on synthetic conversations, and how many a probe needs is open. We trace learning curves over 10-590 synthetic samples for three monitoring concepts, high-stakes situations, replies harmful to a person, and replies that do not follow the user's instruction, on fourteen held-out evaluation distributions and four probe models, varying the generator LLM and the prompt's detail. The need is set by what is monitored: probes for high-stakes and harmful are within a few hundredths of their plateau from 80 samples on Gemma-3-27B-IT, instruction probes need several times as many, and the ordering holds on three smaller probe models and on real samples (from dev set). Prior work advises spending a generation budget on breadth, more kinds of data, over depth, more of each kind. We read the depth a concept needs as the half-gain size of a fitted curve, the number of samples at which half the gain is in hand. Concept and distributi

---

### [128] Spectral Weight Decay: Inducing Low-Rank Structure in Neural Network Weights

**链接**: https://arxiv.org/abs/2610.11730
**作者**: Dmitrii Andriianov, Andrey Veprikov, Aleksandr Beznosikov
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard weight decay treats each weight matrix as a vector and ignores its spectral structure. We introduce spectral weight decay, a post-step decoupled nuclear-norm update that applies additive rather than multiplicative spectral shrinkage. We connect the update to approximate proximal descent and show that its sensitivity to update order can exceed that of conventional $\ell_2$ weight decay near rank deficiency. Across LLaMA models with $124$M to $500$M parameters, spectral weight decay lowers effective rank and improves SVD-LLM compression at matched validation loss. At $500$M and a $4\%$ distortion budget, it reaches $1.89\times$ compression and $1.18\times$ GPU inference speedup, compared with $1.14\times$ and $1.01\times$ after standard weight decay. Under fixed-horizon training with $60\%$ label noise, it also improves final mean clean-test accuracy over matched $\ell_2$ regularization by up to $17.8$ points on MNIST and $4.6$ points across four BERT-base tasks. Code is availab

---

### [129] SWE-Journey: Towards More Realistic Evaluation of Coding Assistants through Long-Horizon, Multi-Turn Interaction

**链接**: https://arxiv.org/abs/2610.11559
**作者**: Hexuan Deng, Yue Wang, Wenyu Jiang, Cheng Yang, Haolin Yang, Zhaohua Zhang 等 (10 人)
**来源**: cs.CL cs.AI cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding assistants such as Claude Code and Codex have become a major application of LLM agents, yet existing benchmarks remain far from real-world use, particularly in task horizon and interaction length. Code assistants require completing long chains of development work in continuously evolving repositories, while repeatedly clarifying requirements and adapting implementations through multi-turn interaction. To address these gaps, we introduce SWE-Journey, a benchmark for more realistic evaluation of coding assistants. To address the task-horizon gap, we propose a weak-to-strong synthesis pipeline that automatically constructs long-horizon coding tasks. To address the interaction gap, we mine four representative user personas from real interaction data and build a user-simulation agent to reproduce realistic code-assistance interactions. On average, models pass over 75% of tests for requested functionality with software architects, but fewer than 25% with non-coders. These results show

---

### [130] DataSense-Bench: The First Step Toward an AI Scientist

**链接**: https://arxiv.org/abs/2610.12190
**作者**: Yudi Zhang, Mingyu Cao, Lu Yin, Mykola Pechenizkiy, Shiwei Liu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As claims about recursive self-improvement (RSI) and artificial general intelligence (AGI) proliferate, we ask a simple question: do frontier AI models have a sense of data, i.e., can they reliably select the right data for training? We introduce DataSense-Bench to study this capability through the fundamental problem of data selection and performance forecasting in machine learning. We ask AI agents to select and rank candidate training subsets that can be used to fine-tune a small LLM model. Agents are allowed to inspect the data, write and execute analysis code, and run model forward passes, but can not train the model or access the actual evaluation tasks. We then fine-tune the base model on each selected subset and evaluate its post-training performance under a standardized protocol. We instantiate the benchmark in terminal problem solving and tool use, selecting trajectories from OpenThoughts-Agent and EnvScaler and evaluating on TBLite and BFCL, respectively. We then evaluate th

---

### [131] Agent4RE: A Self-Refining Multi-agent Framework for End-to-End Software Requirements Engineering and Benchmarking

**链接**: https://arxiv.org/abs/2610.10628
**作者**: Yongjian Tang, Linhan Li, Thomas Runkler
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM-based approaches for software Requirements Engineering (RE) typically rely on basic prompting strategies or rudimentary agent collaboration, under-utilizing the full potential of multi-agent systems. Meanwhile, available datasets focus on isolated subtasks, such as requirements extraction, classification, and completeness detection, leaving the absence of an end-to-end RE benchmark that spans from requirements elicitation to generation. We present Agent4RE - a self-refining multi-agent RE system that orchestrates specialized agents and incorporates two iterative improvement loops. To support evaluation, we construct RE-E2E - a real-world dataset built from human-written requirement specifications, enabling end-to-end assessment of RE workflows. Building on this foundation, we further propose two enhanced Agent4RE versions that incorporate either autonomous self-refinement or structured human feedback, and analyze their strengths and limitations across different scenarios. 

---

### [132] Lossy Compressive Text Autoencoders

**链接**: https://arxiv.org/abs/2610.10738
**作者**: Vinko Sabol\v{c}ec, Angelos Katharopoulos, David Grangier
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Our work explores learning a compressed latent representation of text, at the intersection of data compression and representation learning. We propose an autoencoder architecture that performs residual downscaling and upscaling of hidden representations along the time axis, with a residual low-dimension discrete bottleneck. We analyze our approach for different quantization methods, training objectives, and datasets. For different levels of compression, we evaluate the similarity between the original and reconstructed text both at the surface-level (BLEU) and at the semantic-level (LLM-based judge). Additionally, we evaluate our models on downstream question-answering and semantic text similarity benchmarks. Our approach results in compressed representations which are on par with lossless text compression algorithms at 2.24 bits per byte on web text data, while having good reconstruction and downstream task performance.

---

### [133] Intent Graph: Navigating the Analytical Reasoning Space for Exploratory Data Analysis

**链接**: https://arxiv.org/abs/2610.11025
**作者**: Junran Yang, Shruti Badrish, Teanna Barrett, Leilani Battle
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Exploratory data analysis (EDA) is rarely open-ended in practice: analysts work from high-level domain questions toward the concrete analyses that can answer them, prioritizing directions with domain knowledge and prior hypotheses. Large language models (LLMs) can supply such knowledge, but their responses are unstructured, leaving analysts no way to see what has been explored, what is missing, or why one direction was chosen over another. We present DAG-EDA, a system that lets analysts and an LLM co-navigate the space of possible analyses through two linked structures. An intent graph, governed by a grammar of analytical intent, decomposes an ambiguous natural-language question into progressively concrete analysis tasks, keeping alternative framings open and letting analysts branch, backtrack, and compare paths. A multi-layered knowledge graph externalizes the LLM's domain knowledge, linking domain concepts to the dataset variables that can measure them, so analysts can inspect and co

---

### [134] Which Skill to Distill? SGUID: Selecting a Compact Skill Bank for Model-Skill Co-Evolution

**链接**: https://arxiv.org/abs/2610.12367
**作者**: Yuhan Liu, Xiyao Ma, Zhongkai Sun, Xu Han, Chengyuan Ma, Benjamin Z. Yao 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skills, reusable procedural guidance added at inference, can substantially improve LLM downstream performance (Li et al., 2026). Prior work retrieves skills from a bank by semantic relevance, then uses them as inference-time patches or for model distillation. The individual utility of each skill, however, is largely neglected. We first show that, in on-policy distillation where skill-conditioned policies serve as teachers, fewer than 25% of retrieved skills provide useful distillation signals. We then propose SGUID, a method for selecting a compact subset of skills for distillation. SGUID retains a skill only if it consistently yields effective learning signals during training. The selected skills are then distilled to produce a better model. Our results show that not all skills are worth distilling. Across four models from the Olmo and Qwen families, distilling 6 selected skills matches or exceeds full-bank distillation in mean avg@12 on three of the four models, and on all four after

---

### [135] Safe, Persistent, and Evolving Agent Harness for Understanding Partially Observable Worlds

**链接**: https://arxiv.org/abs/2610.11552
**作者**: Yisen Gao, Yue Guo, Qing Zong, Yiwen Guo, Yangqiu Song
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can invoke tools fluently, but enterprise workflows demand more than selecting the right tools: actions must strictly comply with organizational policies, tool feedback often conceals hidden side effects under partial observability, and long-horizon tasks require persistent state tracking across multiple records. To address these challenges, we introduce E-Ledger, a multi-agent harness for safe and persistent execution. E-Ledger employs a code approval layer that checks every proposed action against policy before execution, and maintains a world ledger of verified hidden rules alongside evidence-backed dynamic state. Because hidden rules are typically unknown a priori, we further propose WorldAbduct, an abductive, world-model-driven harness evolution framework. WorldAbduct diagnoses execution trajectories across four complementary views (state consistency, world-observation gap, policy-gate correctness, and goal judgment) to hypothesize latent rules, and ver

---

### [136] LEVER: Adaptive Cost-Aware Proof Search Over AND/OR Graphs

**链接**: https://arxiv.org/abs/2610.11862
**作者**: Nihal Jain, Shuangjie Yao, Begum Cicekdag, Zhuo Zhang, Suman Jana
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mathematicians value proofs for more than correctness: among correct proofs, simplicity, purity and the computational cost of finding them vary widely. Yet LLM-powered theorem provers largely search for any correct proof, and improve its quality only after it is found. We propose LEVER, a proof search algorithm that makes the objective over correct proofs programmable and optimizes it during search. LEVER scores partial proofs over an AND/OR proof graph, combining realized objective values with predictions for open subgoals, so the objective guides search before a proof is complete. The same mechanism optimizes computational cost, proof length, topical impurity, and even their weighted combinations, while the Lean kernel enforces correctness. On PutnamBench in Lean 4, under matched budgets, LEVER costs 34% less than a strong single-conversation agent while raising the solve rate from 80% to 96%. On reducing topical impurity, i.e., how far a proof strays from its theorem's subject, it i

---

### [137] Learning Probabilistic Logic Programs with Functional Gradient Guided Language Models

**链接**: https://arxiv.org/abs/2610.12303
**作者**: Saurabh Mathur, Sahil Sidheekh, Bhavan Vasu, Farbod Tavakkoli, Prasad Tadepalli, Kristian Kersting 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Declarative logic programs offer a powerful and interpretable abstraction for encoding relational structure and neurosymbolic reasoning, by expressing dependencies as weighted compositional rules. However, inducing them from data remains fundamentally hard, bottlenecked by the combinatorial explosion of symbolic search spaces. LLMs have recently emerged as powerful hypothesis generators, but when used in isolation, they lack the capacity to do systematic inductive reasoning needed to reliably synthesize valid programs that fit complex relational distributions. We introduce grasp (Gradient-boosted Synthesis of Probabilistic logic programs), a neurosymbolic framework that casts relational structure learning as functional gradient boosting in which the weak learner is a first-order rule and the intractable inner search is delegated to an LLM proposal oracle. We evaluate grasp on four relational benchmarks spanning molecular toxicity prediction (Tox21), mutagenesis, and citation matching (

---

### [138] Synthesis Through Simulation: Generating Coherent Enterprise Data via Scalable Agent-System Interaction

**链接**: https://arxiv.org/abs/2610.10549
**作者**: Yipeng Li, Ashutosh Hathidara, Jane Lo, Harshavardhan Abichandani, Gunraj Singh, Atin Ghosh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-calling agents have become central to enterprise AI, yet training and evaluating them at scale remains severely constrained due to business and legal restrictions on enterprise systems, data, and database schemas. Tabular data synthesis offers a natural alternative, but its effectiveness is fundamentally limited by structural validity and schema availability, while procedure-based approaches yield the opposite weakness, typically lacking distributional fidelity without per-domain authoring. We introduce **Synthesis Through Simulation** (STS), a **schema--free** data synthesis paradigm in which an LLM agent generates data by executing operations against policy-enforcing APIs within simulated enterprise environments. Because data is generated through the same environment that defines what is valid, STS guarantees structural validity by construction while decoupling validity enforcement from distribution modeling, allowing each to be addressed independently. The **Generalist Populato

---

### [139] Real Long-Term Memory for AI: A 50-Million-Token Window That Is Faster and Cheaper Than Recompute

**链接**: https://arxiv.org/abs/2610.10845
**作者**: Sietse Schelpe
**来源**: cs.CL cs.AI cs.DC cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large language model can only use the text that fits in its context window, and it recomputes its internal key-value (KV) state for a prompt every time the prompt is sent. We test a memory layer, the public package galahad-kv, that saves the KV state of each block of about 16,000 tokens to encrypted local NVMe disk and loads it back later, byte-exact, without recomputing it. We ran it on 50,000,000 tokens of real public text, served through vLLM on one NVIDIA H100, with Gemma 4 12B and Gemma 4 31B. Every block we probed was loaded back from the encrypted store with no recompute (100 of 100, at depths from 0 to 50M tokens) on both models. Loading a block was 2.8x to 4.3x faster than recomputing it and used 8.8x to 12.3x less GPU energy, and GPU memory stayed flat over the whole 50M-token stream. Asked about facts planted millions of tokens earlier, the 12B model gave the right answer 82 times out of 100 and the 31B model 98 times out of 100. Neither model made up an answer. The limits

---

### [140] DLC: A Metric-Guided Dynamic Loss Controller for Multi-Objective Training

**链接**: https://arxiv.org/abs/2610.11433
**作者**: Jaewan Ko, Janghoon Choi
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we introduce a metric-guided dynamic loss controller (DLC) for multi-objective image restoration. Conventional image restoration pipelines usually train with a fixed weighted combination of multiple losses, without changing the relative importance of fidelity, perceptual similarity, and no-reference quality during optimization. DLC is an architecture- and loss-term-agnostic training-time controller: it does not modify the restoration architecture or introduce new differentiable loss terms, but dynamically reweights the existing training losses. During training, DLC periodically evaluates the current model on a small fixed feedback subset and uses the resulting quality metrics to update the loss-weight vector through an LLM-based controller. Because DLC operates on existing loss terms rather than task-specific architectures, the same controller formulation can be instantiated across diverse image restoration training pipelines. We evaluate DLC on three restoration domains

---

### [141] MindFlow: Mind Supernet Powered Thinking Flows for Research Idea Innovation

**链接**: https://arxiv.org/abs/2610.11966
**作者**: Mengdi Liu, Wenjue Chen, Wenyue Chen, Cheng Yang, Fanqi Kong, Zhangyang Gao 等 (10 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research idea innovation is a fundamental engine of scientific progress, yet it remains difficult to generate and evaluate in a scalable and controllable way. This challenge lies in its inherently open-ended and multi-objective nature, where ideas should balance novelty, plausibility and feasibility. While recent LLM-based approaches have made progress through carefully designed prompts or agent pipelines, they are constrained by predefined, static ideation workflows. To address this limitation, we propose MindFlow, a framework that explicitly formulates ideation as a graph-structured Flow in Mind, which is composed of modular thinking operators and modeled by a probabilistic mind supernet. Given a research topic, a controller dynamically samples thinking flows to generate candidate ideas. This open-ended problem is optimized using a tournament-based relative ranking, enabling the controller to progressively favor higher-quality thinking flows. We further introduce an evaluation protoc

---

### [142] Can LLMs Fix It Without Code? Toward Automated Verification of No-Code Bug Fixes

**链接**: https://arxiv.org/abs/2610.11963
**作者**: Utku Boran Torun, Veli Karakaya, Eray T\"uz\"un
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A no-code fix resolves an invalid bug report by directing the user to change a setting, update to a version where the problem is already fixed, or adjust their workflow. Manually verifying whether a proposed no-code fix resolves the reported bug takes considerable developer time. This study proposes an automated, execution-based pipeline for evaluating the capability of large language models (LLMs) to generate no-code fixes in a real browser environment. We evaluate 322 no-code fixes generated by the 12 configurations released with the benchmark of a previous study, covering bug reports categorized as Faulty Configuration, Wrong Version, or External System & Dependency. An executor agent applies each fix by following its natural-language instructions, and an issue-specific checker determines whether the reported bug persists. We repeat the pipeline with three executors: two Computer-Use Agents, OpenCUA-72B and Claude Sonnet 5, and one multimodal agentic LLM, Meta's Muse Glimmer. Only 1

---

### [143] RIT-RAG: Navigating Document Corpora with Retrieval-Induced Trees

**链接**: https://arxiv.org/abs/2610.11370
**作者**: Meghanadh Pulivarthi, Swaraj Kumar Biswal, Kushagra Bhushan, Yatin Nandwani, Sachindra Joshi, Dinesh Raghu
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) grounds language models in external corpora. Agentic RAG enables iterative search, yet exposes the model to isolated chunks without document structure, making it difficult to distinguish relevant evidence from chunks that merely resemble the query. Structure-aware methods such as PageIndex navigate document structure but cannot scale to the structures of large corpora, which do not fit in the LLM context. Hence, they first commit to a single document using a document retriever and cannot recover from a wrong choice. We propose RIT-RAG (Retrieval-Induced Tree RAG), which combines content retrieval with structural navigation. Offline, RIT-RAG builds a tree for each document from its table of contents or sitemap. At query time, it retrieves a broad set of chunks and uses their positions to induce manageable sub-trees, potentially across multiple documents. An LLM agent navigates these sub-trees, selectively reads promising nodes, and reformulates queri

---

### [144] Code Understanding is a Bottleneck for Coding Agents

**链接**: https://arxiv.org/abs/2610.10610
**作者**: Nishant Balepur, Kiran Tomlinson, Tobias Schnabel
**来源**: cs.SE cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repository benchmarks (e.g., SWE-bench) for coding agents often assume that lines of code edited can predict task difficulty, but such datasets' poor control over code and task types makes it hard to know which abilities truly drive agent errors. We present CABRA: a Coding Ability Blueprint for Rigorous Agent evaluation. CABRA builds tasks from scratch as call graph transformations and scales difficulty via a task size parameter on four axes: function traversal, search, runtime resolution, and instruction following. We run eight LLMs and six coding agents on 6,840 CABRA tasks to show: 1) LLM accuracy falls as task size~grows, but agents stay near-perfect by offloading work to tools (e.g., grep); 2) Larger CABRA tasks elicit more tool calls for reading and analysis, while a separate study on SWE-bench Verified shows these tool call counts predict agents' accuracy better than lines of code edited, suggesting task difficulty for agents can lie in understanding code to edit, not just in ma

---

### [145] SynCo: Data Synthesis Co-Training for Self-Evolving LLMs via Multi-Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.11345
**作者**: Wei Yang, Shawn Li, Yuehan Qin, Yawei Wang, Mingxi Wang, Shixuan Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving LLM agents promise to improve autonomously through continual interaction and learning, reducing their dependence on manually curated supervision. Realizing this promise requires not only updating the agent, but also evolving its training experience as its capabilities change. However, most existing pipelines rely on static datasets or separately updated synthesis models, causing previously useful tasks to become trivial while overly difficult tasks remain uninformative. This growing mismatch between agent capability and training experience limits sustained self-improvement. To address this problem, we propose SynCo, an agentic data synthesis co-training framework for self-evolving LLMs based on multi-agent reinforcement learning. SynCo jointly optimizes two independently parameterized agents: a Synthesizer that constructs training tasks from the Reasoner's evolving capability state, and a Reasoner that learns from the resulting experience. Each synthesized task induces mu

---

### [146] RaReCache: Bridging the Gap in Cross-Model KV Cache Reuse via Rank disagreement-based Selective Recomputation

**链接**: https://arxiv.org/abs/2610.11358
**作者**: Sreetama Sarkar, Saptarshi Mitra, Sitao Huang, Souvik Kundu, Peter A. Beerel
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-model KV-cache reuse remains a key challenge in modern LLM serving. Coding agents and multi-model systems increasingly route a shared context across models: a user may switch models mid-session, or a cascade may escalate a difficult query. Because KV caches contain model-specific representations, each switch typically forces the receiving model to prefill the entire context from scratch. Recent work shows that closed-form linear maps can translate KV caches between models in the same family, but transfer accuracy degrades as the model-size gap widens. In this paper, we establish that these transfer failures are concentrated in a small subset of information-dense tokens. To bridge this gap, we introduce RaReCache, a framework that enables a large target model to decode accurately from a cache prefilled by a much smaller source via selective recomputation. RaReCache identifies these critical positions using a novel rank disagreement metric, scoring each token by the energy of its m

---

### [147] Back in Style: A Sociolinguistic Approach to Authoring and Measuring Persona Fidelity in User Simulation

**链接**: https://arxiv.org/abs/2610.10988
**作者**: Lex Konnelly, Elena Khasanova, Riqiang Wang, Matthias Lee, Harsh Saini, Parsa Kavehzadeh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agentic systems gain commercial popularity, user simulators increasingly serve as measurement instrument for their evaluation. However, the fidelity of simulated users in comparison to real human users is generally low, and typically assessed by costly, subjective LLM judges. In this pilot study, we ask whether fidelity can instead be measured deterministically by treating a user persona sociolinguistically: as a social type that emerges from observable linguistic style, rather than one predicted by labels or descriptions a model must extrapolate into behaviour. We author personas as concrete stylistic rates, which lets us transfer two established, model-free instruments -- authorship-verification stylometry and lexicon-based content analysis -- as fidelity diagnostics. We A/B-test the sociolinguistic schema against a flat descriptive baseline across five task-oriented customer-service agents. Results show that the sociolinguistic schema improves both stylistic adherence and stylome

---

### [148] One Skill Too Many: How Co-Installed Skills Conflict in Coding Agents

**链接**: https://arxiv.org/abs/2610.11647
**作者**: Chaoliang Yan, Zihao Xu, Yuekang Li, Shangzhi Xu, Yi Liu, Gelei Deng 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding agents are extended with agent skills, directories whose SKILL.md tells the model when and how to perform a task. Because skills come from independent sources (teams, developers, plugins, copied collections), an installed skill can be co-installed with a similar skill doing the same job, and the model picks between them by name and description alone. In a conflict, the installed skill loses core functions (e.g., a ban on touching git) because the similar skill runs instead or changes what it does. The task still passes, so benchmarks that check only task completion miss such cases. We present the first empirical study of such conflicts. From snapshots of 20,947 repositories, we mine 822,109 candidate similar-skill pairs, have an LLM judge a stratified sample of 3,754, and run 312 confirmed pairs on three models (6,368 runs, 169,294 tool calls, 542 agent-hours). We report five findings. (1) Conflict-prone skills are common: nearly one in four installed skills is co-installed with

---

### [149] Guided Reflection for Personal Sleep Insight in Everyday Sleep Tracking

**链接**: https://arxiv.org/abs/2610.10822
**作者**: Bokyung Kim, Amama Mahmood, Honghao Zhao, Molly E. Atwood, Luis F. Buenaver, Ziang Xiao 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital sleep technologies make tracking accessible, yet users often struggle to interpret what changes in their sleep mean. Behavioral sleep medicine addresses this through guided discovery, helping patients develop personal interpretations rather than simply receiving explanations. To bring this to everyday tracking, we present DREAM, an LLM-powered voice assistant that monitors conversational sleep diaries, selectively invites users to interpret meaningful changes, and uses their interpretation to tailor subsequent education. We co-designed DREAM with sleep specialists iteratively and evaluated it in a six-week field study (N=14) against a generic-education control. DREAM participants reported greater personal sleep insight, motivation, and willingness to use the system, and described a clearer rationale for trying strategies. Our findings suggest that guided reflection made participants more active interpreters of their own sleep. Furthermore, we argue that expert involvement is no

---

### [150] Amortized Off-Policy Evaluation for LLMs

**链接**: https://arxiv.org/abs/2610.10848
**作者**: Younwoo Choi, Leo Feng, Vincent Liu, Haanvid Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate evaluation is central to selecting which LLM to deploy, yet testing a candidate on live traffic exposes real users to an unvetted model. Teams therefore evaluate candidates offline, on data produced by already-deployed models. This is off-policy evaluation (OPE), and it faces two distribution shifts: as a model is updated in post-training, its responses diverge from the logged ones (policy shift), and the reward definition under which it is judged changes with business requirements (reward shift). Classical OPE methods are ill-suited to this continual-deployment setting because they are defined per task and require fitting from scratch on every new logged dataset or reward definition. To address this, we propose PFN-OPE, a prior-data fitted network that amortizes OPE across a distribution of contextual-bandit tasks. We pretrain it once on tasks constructed from a pool of LLM responses scored by several reward functions, in which both shifts occur. At test-time it maps a logged

---

### [151] DVD: Dynamic Vector Decoding for Efficient MLLM-based Perception

**链接**: https://arxiv.org/abs/2610.12266
**作者**: Jinghua Hou, Zhe Liu, Hengshuang Zhao
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models have made remarkable progress in bridging vision and language, facilitating various perception tasks essential for human-machine interaction, robotics, and autonomous driving. However, existing MLLM-based perception methods predominantly rely on text-based coordinate representation, which suffers from excessive token overhead, or fixed-range quantization, which suffers from range and precision constraints, especially for 3D domains with unbounded spatial range and high localization accuracy requirements. To address these challenges, we propose a dynamic vector decoding method named DVD, which unifies the representation of 2D and 3D perception tasks. Specifically, we first transform diverse perceptual representation (i.e., 2D bounding boxes, 2D masks, and 3D bounding boxes) into 1D vector sequences, which are then mapped to compact discrete tokens in the high-dimensional space. Then, a lightweight de-tokenizer enables seamless integration with MLLMs by d

---

### [152] Multimodal Graph Retrieval-Augmented Sequential Recommendation via Collaborative Filtering Paths

**链接**: https://arxiv.org/abs/2610.11228
**作者**: Jason Marcell Setiadi, Xin Cao, and Lina Yao
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have demonstrated strong potential for sequential recommendation through their ability to reason over complex multimodal data. However, existing approaches either rely solely on the target user's own interaction history, neglecting collaborative signals from neighboring users, or incur substantial computational overhead through repeated MLLM inference over long interaction histories. To address these challenges, we propose MGRASRec, a multimodal graph retrieval-augmented framework for sequential recommendation. MGRASRec injects collaborative filtering signals conditioned on the candidate item directly into the MLLM prompt by retrieving structured paths from a user-item interaction graph, extended via multimodal similarity to increase coverage beyond exact co-interaction overlap. This retrieval also surfaces the history items most relevant to the candidate at no additional cost, removing the need for recurrent summarization and keeping inference 

---

### [153] From What to Which: Decoding Modifier Grounding in Frozen MLLMs

**链接**: https://arxiv.org/abs/2610.12305
**作者**: Barbara Toniella Corradini (AI for Good (AIGO), Istituto Italiano di Tecnologia, Italy), Caterina Gallegati (University of Siena, Italy), Ludovica Genovese (AI for Good (AIGO) 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Multimodal Large Language Models (MLLMs) can describe increasingly complex visual scenes, token-level grounding becomes crucial. Yet, when an MLLM generates "the yellow banana on the left", established grounding approaches focus on what is in the image ("banana"), overlooking tokens that help describe which instance is meant ("yellow", "left"). In this work, we ask whether frozen MLLM representations contain decodable grounding information about the referred instance across generated tokens, extending to modifiers such as attributes, spatial expressions, and relational/action terms. To address this question, we introduce OTTER, a lightweight supervised probe over frozen MLLM representations that uses Optimal Transport (OT) to align generated tokens with visual regions and produce compact grounding maps. Our results show that (i) instance-discriminative visual information can be decoded from modifier tokens, with the clearest evidence for spatial terms, but (ii) is not confined to th

---

### [154] SpatialOPSD: Self-Distilling Spatial Intelligence from Verified Coding Agent Traces

**链接**: https://arxiv.org/abs/2610.11366
**作者**: Rongxue Li, Meng Yang, Yiru Mao, Yongliang Tao, Lulu Hu, Bin Yang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial coding agents significantly improve spatial reasoning in Multimodal Large Language Models (MLLMs) by using external tools to generate verified execution traces. However, this paradigm inherently suffers from prohibitive inference-time overhead and external dependencies. In this paper, we explore whether an MLLM can internalize this agentic capability to operate entirely tool-free. We begin with a simple observation: prompting an MLLM with summarized execution traces of a spatial coding agent naturally unlocks the model's internal spatial Chain-of-Thought (CoT). Motivated by this, we introduce SpatialOPSD, an on-policy self-distillation framework that internalizes spatial reasoning into a standalone MLLM by formulating verified agent traces as privileged information. To mitigate privileged-information leakage during distillation, we introduce Repetition-Aware Distillation, which combines repetition masking with unlikelihood regularization. Experiments across multiple benchmarks 

---

### [155] SuperNav: An Agentic Navigation System for Any Task in Any Scene

**链接**: https://arxiv.org/abs/2610.12126
**作者**: Jinkai Zhang, Jingyi Xu, Yuanhong Yu, Jiarui Guo, Ruizhen Hu, Hujun Bao 等 (8 人)
**来源**: cs.RO cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> General-purpose service robots need navigation systems that can handle diverse human requests in unfamiliar environments, combining task generality with scene generality. Some existing methods fine-tune multimodal large language models (MLLMs) to predict navigation actions, making their behavior dependent on the coverage of navigation training data and potentially limiting generalization to new requests and environments. Our key insight is to let the MLLM focus on interpreting requests, understanding scenes, and making decisions while preserving its general-purpose capabilities and delegating motion execution to navigation tools. To realize this idea, we introduce SuperNav, which equips a pretrained MLLM with a specialized agent harness without navigation-specific fine-tuning of the MLLM. Our harness supports these decisions with Navigation Skills, agent-oriented Tools for physical interaction, and task-progress and context management. A unified visual-point interface connects decision

---

### [156] SPERA: Spherical Prior EEG Foundation Model with Geometry- and Frequency-Aware Latent Prediction

**链接**: https://arxiv.org/abs/2610.10571
**作者**: Minsu Kim, Ye-Sung Kim, Hyeseong Jeon, Wooseok Hyung, Joshua Lee, Chang-Hwan Im
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) provides a non-invasive measure of ongoing neural activity, but building general-purpose EEG models remains challenging due to the heterogeneity of subjects, devices, and electrode montages. Existing EEG foundation models predominantly rely on reconstruction-based objectives defined on the observed signal, which contains both neural and non-neural components. We introduce SPERA (Spherical Prior EEG Representation Architecture), an EEG foundation model that adopts the joint-embedding predictive architecture (JEPA) to predict in latent space. SPERA introduces a Legendre-polynomial spatial prior, incorporated into attention to encode varying scalp electrode geometries. Two further components adapt the model to EEG: factorized temporal and spatial attention interleaved with periodic full-attention blocks, and a relational spectral regularizer aligning latent similarity structure with spectral views. Pretrained on approximately 80,000 hours of EEG from 29,048 su

---

### [157] Beyond Accuracy: Robustness, Interpretability and Expressiveness of EEG Foundation Models

**链接**: https://arxiv.org/abs/2605.17562
**作者**: Urban \v{S}irca, Maryam Alimardani, Stefanos Zafeiriou, Konstantinos Barmpas
**来源**: cs.LG cs.AI cs.HC
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [158] SPD-MetaFormer is what you need for small-data brain decoding

**链接**: https://arxiv.org/abs/2610.10952
**作者**: Zhida Wang, Wei Lyu, Guo Yu and Sui Tang
**来源**: cs.LG stat.ML
**匹配关键词**: Brain Decoding
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain signal decoding is challenging because neural recordings are noisy and vary across individuals, while labeled data are often limited. Recent attention-based models on the symmetric positive definite (SPD) manifold have nevertheless achieved strong performance using covariance and connectivity representations, yet the contribution of learned token weighting remains unclear. We examine two representative architectures, MAtt (based on log-Euclidean geometry) and GBWAtt (based on generalized Bures--Wasserstein geometry), and find that their learned attention weights remain close to uniform after training. We relate this behavior to bounded similarity parameterizations that, under the original softmax scaling, limit attention-weight contrast. Moreover, replacing learned weights with uniform weights, throughout training and evaluation, has little effect on mean predictive performance while preserving each model's original aggregation geometry. Motivated by these findings, we introduce 

---

### [159] Brain foundation model-guided source-selective domain adaptation for cross-subject EEG decoding

**链接**: https://arxiv.org/abs/2507.21037
**作者**: Jinzhou Wu, Baoping Tang, Qikang Li, Yi Wang, Cheng Li, Shujian Yu
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [160] Similar Predictive Fit but Different Latent Dynamics: Characterizing Learned Dynamical Structure in Personalized Models of Brain Disorders

**链接**: https://arxiv.org/abs/2610.10850
**作者**: Rita Huan-Ting Peng and Nhat Bui
**来源**: cs.LG eess.SP q-bio.NC
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI models move toward clinical decision-making and personalized treatment, understanding \emph{what} a model learns is important beyond predictive accuracy alone. We investigate whether personalized latent dynamics reveal clinically associated differences even when predictive fit is similar. A lightweight CNN--Transformer EEG foundation model pretrained on the Temple University EEG Corpus (TUEG) extracts segment-level representations. Using the Temple University Epilepsy Corpus (TUEP), representations are mapped to a shared latent-state space, and sparse multinomial logistic transition distributions (mLTD) are fit independently to each subject to obtain personalized transition-dependency graphs $W_n$. Analyses include $n{=}198$ subjects (99 epilepsy / 99 non-epilepsy). At $k{=}4$, epilepsy subjects exhibit substantially denser learned dependency structure ($p{=}1.1\times10^{-7}$), with the same pattern at $k{=}6$ (19.90 vs. 13.46; $p{=}5.2\times10^{-5}$). Graph-derived features prov

---

### [161] Social Pain Disrupts Emotion-Action Brain-State Dynamics in Adolescents with Non-Suicidal Self-Injury

**链接**: https://arxiv.org/abs/2610.11155
**作者**: Ying Xu, Xiaojun Liang, Li Zhang, Yixuan Yuan, Gan Huang, Yongjie Zhou 等 (7 人)
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Non-suicidal self-injury (NSSI) is prevalent among adolescents with depression, but the rapid brain-state dynamics linking social distress to maladaptive behavior remain unclear. We combine an experimental pain paradigm, electroencephalography (EEG) microstate analysis, and interpretable deep sequence modeling to investigate NSSI-related neurodynamics in 106 adolescents with depression, including 67 with NSSI (DN+) and 39 without NSSI (DN-), during social pain, physical pain, and resting-state conditions. A model integrating disease-specific, domain-adversarial, consistency, and contrastive learning captures higher-order dependencies in microstate sequences. Social pain yields the strongest NSSI discrimination, with 68.55% accuracy, outperforming the best baseline by 8.94% points. Model interpretation and conventional microstate analyses reveal weakened bidirectional transitions between MS3 and MS5 in DN+ adolescents during social pain. Source reconstruction associates MS3 with emotion

---

### [162] HarnessIR: Harnessing Multimodal Foundation Models for Universal Real-World Image Restoration

**链接**: https://arxiv.org/abs/2610.10133
**作者**: Xiangtao Kong, Shuaizheng Liu, Rongyuan Wu, Lingchen Sun, Zhengqiang Zhang, Jinxin Zhao 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [163] Test-Time Compute for Tabular Foundation Models: Mechanisms, Gains, and Limits

**链接**: https://arxiv.org/abs/2610.12005
**作者**: Kanghui Ning, Marin Bilo\v{s}, James T. Wilson, Yilang Zhang, Kashif Rasul, Dongjin Song 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Which forms of test-time compute improve the predictions of strong pretrained tabular foundation models (TFMs)? We systematically study this along three axes: adaptation, aggregation, and context construction. Our evaluation spans modern TFMs across the TabArena benchmark, supplemented by experiments on wide and large-scale tables from OpenML. For adaptation, we introduce DiagScale, a diagonal query-key similarity update. It trains only 0.003-0.03% of model parameters and achieves gains comparable to full fine-tuning across three independently pretrained backbones. For aggregation, both pool composition and selection strategy matter. TabPFN-3 already averages predictions from different preprocessing variants of the same data, and adding more such predictions yields diminishing returns. With a broader pool of 96 configurations, greedy selection reduces error by 2.4% relative to the default predictor, but uniform averaging increases error. For context construction, attention-guided retri

---

### [164] RT-DETRv4: Painlessly Furthering Real-Time Object Detection with Vision Foundation Models

**链接**: https://arxiv.org/abs/2510.25257
**作者**: Zijun Liao, Yian Zhao, Xin Shan, Yu Yan, Chang Liu, Lei Lu 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] Benchmarking Hyperspectral Foundation Models for Hyperspectral Unmixing

**链接**: https://arxiv.org/abs/2609.28283
**作者**: Edgard Dabier and Christophe Kervazo and Pietro Gori and Florence Tupin
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [166] ARC: A Reasoning Recipe for Robot Foundation Models

**链接**: https://arxiv.org/abs/2610.12386
**作者**: Gokul Puthumanaillam, Tao Sun, Elie Aljalbout, Moritz Reuss, Zhaoshuo Li, Fabio Ramos 等 (8 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The prevailing approach to improving robot foundation models (RFMs) relies on larger models, more robot demonstrations, and costly training at scale. We show that there exists an effective and efficient complementary approach: the right reasoning recipe can substantially improve the zero-shot task performance of existing state-of-the-art RFMs. We refer to this recipe as ARC. It consists of three key ingredients: a reasoning trace, a scalable automatic labeling pipeline, and a strategy for adapting pretrained RFMs to use these traces for control. First, we find that effective reasoning traces should be grounded in the robot's next action and explain its causal structure: why the action is appropriate and what effect it should produce. Second, we show that these traces can be generated automatically from existing demonstrations, enabling us to construct ARC-Trace-DROID from DROID without collecting new robot data. Third, we show how state-of-the-art VLAs such as $\pi_{0.5}$ and WAMs such

---

### [167] RideBench: A Large-Scale Exogenous-Aware Benchmark for Ride-Hailing Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.11164
**作者**: Shengsheng Lin, Jing Hu, Zhengyang Hu, Jiazheng Sun, Zichun Cao, Siwei Sun 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We release Ride-Hailing, a large-scale ride-hailing time series dataset synthesized from DiDi's marketplace data across 200 spatial areas. Ride-Hailing spans four consecutive years at half-hourly granularity and covers three representative exogenous scenarios: Weather Disturbance, Holiday Effect, and Large-scale Event Impact. Built upon Ride-Hailing, we introduce RideBench, a comprehensive benchmark for exogenous-aware ride-hailing forecasting, covering both regular week-ahead forecasting and long-horizon 8-week-ahead forecasting with up to 2,688 prediction steps. RideBench evaluates over 30 representative forecasting methods, including endogenous-only models, exogenous-aware models, and time series foundation models. Our results show that future-known exogenous variables provide clear benefits in regular week-ahead forecasting, especially under weather, holiday, and large-scale event (e.g., major sporting events and concerts) scenarios. However, current exogenous-aware models still st

---

### [168] Diffusion Meta-Prompting and Steering for Generalizable Foundation Model Adaptation

**链接**: https://arxiv.org/abs/2610.11067
**作者**: Deepak Sridhar, Yi Li, Kartikeya Bhardwaj, Shuangjun Liu, Taotao Jing, Yuan Li 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt learning is a popular method for adapting foundation models, but learned prompts are typically task-specific and fail to generalize to new classes, domains, or compositions of tasks. In this paper, we introduce a Diffusion Meta-Prompt (DMP) model , a framework that models the distribution of learned prompts using diffusion models. Given a repository of previously learned prompts, DMP is trained and sampled without access to the original task examples or task losses, and synthesizes new prompts conditioned on natural language task descriptions. To improve the sampling stability, we introduce a test-time steering strategy for DMP, which uses the best training-selected prompt in the repository as a latent anchor during diffusion sampling, without retraining the DMP or accessing test classes. DMP improves generalization across classification, retrieval and text-to-image generation tasks, supports concept composition and negative prompting without explicit training. It reduces storag

---

### [169] MiMo-V2.6: Scaling Reinforcement Learning Towards Self-Improvement

**链接**: https://arxiv.org/abs/2610.11959
**作者**: Xiaomi LLM-Core Team: Zongming Qiao, Ziyue Hua, Zirui Ou, Zihao Yue, Zihan Jiang, Zhuo Huang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) is the central training paradigm for advancing large foundation models towards self-improvement. This report introduces the MiMo-V2.6 series, an omni-modal family that pushes the frontier of model intelligence by scaling RL compute. Prior to RL, we conduct mid-training on a broad multimodal corpus to provide ample exploration space, and build a solid infrastructure on the pretrained hybrid-SWA architecture to support subsequent scale-up. We scale RL compute along three dimensions: (1) larger batches and higher throughput, with an asynchronous training that consumes 1,568 samples and 2.7-3.7B tokens per step at context lengths of up to 1M; (2) more diverse and complex environments, spanning code, general, visual, and cyber domains under a mixture of agent harnesses; and (3) more grader compute, via groupwise agentic grading that yields more accurate reward signals for long-horizon tasks and steers the model towards shorter, more token-efficient solutions. To 

---

### [170] AdaCast: Conditional Parameter Generation for Adaptive Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.12240
**作者**: Darahaas Nallagatla, Darryl Cherian Jacob, Pan He
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models (TSFMs) have achieved strong forecasting performance across domains. However, most adaptation methods remain static. Existing all-in-one methods learn a single set of dataset-level parameter updates and apply the same adapted model to every input. As a result, they cannot adapt the model parameters to the temporal patterns, seasonality and dynamics of each input time series. This limits their ability to produce forecasts that are tailored to heterogeneous inputs. To address this limitation, we propose AdaCast, a conditional parameter generation framework for time-series forecasting. AdaCast uses a generator to produce input-specific low-rank parameter updates for a frozen pretrained TSFM. These updates adapt the model to each input during both training and inference. Across six public benchmarks, AdaCast consistently outperforms static adaptation baseline in in-domain forecasting and improves zero-shot generalization to held-out datasets across domains. Th

---

### [171] PointVGGT: Zero-Shot Multiview RGB-D Point Cloud Registration with Visual Geometry Foundation Priors

**链接**: https://arxiv.org/abs/2610.11612
**作者**: Haobo Jiang, Liang Yu, Jianmin Zheng
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper addresses multiview RGB-D point cloud registration, aiming to estimate global rigid poses for unordered RGB-D scans and align them in a metrically consistent coordinate frame. The conventional pairwise-then-global paradigm suffers from locally optimized pairwise registration, severe error propagation and high computational burden. In particular, existing methods typically treat RGB data as a mere auxiliary matching cue and overlook the holistic geometric priors (e.g., camera poses and 3D models) encoded across image sequences. This paper introduces PointVGGT, a zero-shot framework built upon a novel \emph{foundation-then-refinement} paradigm that systematically leverages visual geometry foundation models (e.g., VGGT) as the computational backbone for robust, training-free multiview RGB-D registration. In the foundation stage, we directly recover metrically consistent global poses (without any pairwise estimation) by grounding the scale-ambiguous pose predictions of the found

---

### [172] Fluid-Gen-Zero: Grounding Pretrained Video Generators in Physics without Training

**链接**: https://arxiv.org/abs/2610.10984
**作者**: Hong Huang, Yuqiu Liu, Chenyu You, Daniel Martin, Chuhang Zou, Wuyang Chen
**来源**: cs.CV cs.GR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Fluid-Gen-Zero, a training-free framework for physics-aware fluid-object interaction video generation that decouples physical reasoning from appearance synthesis. Our key insight is to delegate motion dynamics to a physics simulator while preserving the appearance modeling capacity of pretrained video generators. We bridge these two domains through a two-level agentic workflow: generation-time planning, where a vision-language model (VLM) agent interprets intent and the simulation rollout to organize generation clips, and latent-space guidance, which injects simulation signals into denoising through region-aware latent wrapping. This plug-and-play design is compatible with current video foundation models. We further introduce a benchmark for fluid-object interaction video generation. Across Tora (CogVideoX-based), VACE and WanMove (Wan-based), Fluid-Gen-Zero consistently improves simulation alignment, reducing object trajectory error by 26.7%-81.5% and fluid fEPE (fluid flow

---

### [173] MotherTree: Meta-learning on synthetic data improves decision tree training

**链接**: https://arxiv.org/abs/2610.10832
**作者**: Ziyuan Wang, Fredrik D. Johansson
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional decision tree algorithms produce effective, transparent models that can be audited, communicated, and deployed independently of the training data, but require learning every new task from scratch. In contrast, tabular foundation models demonstrate that meta-learning from a synthetic prior distribution enables strong in-context prediction for previously unseen tasks, especially in small-sample regimes. However, this approach does not produce a standalone model that can be inspected in isolation. We introduce MotherTree, a tabular transformer that meta-learns decision tree induction: given a training set for a new task, it outputs a hard, axis-aligned decision tree, equivalent in form to classically trained trees, in a single forward pass. MotherTree is pre-trained on a synthetic prior using stochastic gradient descent without requiring reference trees for supervision. On established benchmarks with controlled sample size, the approach is competitive with size-matched trees 

---

### [174] Can Jev be Your Q or Policy in Reinforcement Learning?

**链接**: https://arxiv.org/abs/2610.11692
**作者**: Yi Ma, Tianpei Yang, Yaodong Yang, Weixun Wang, Hongyao Tang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models supply reinforcement learning (RL) with priors that mitigate its longstanding weaknesses in sample efficiency and transfer, but their token-by-token generation makes queries sequential and costly. Jev, a recently released decision model, generates nothing and returns calibrated, typed answers in a single forward pass. Existing work studies foundation models in RL either as models to be trained or as generators to be prompted, and Jev belongs to neither category, having so far served only as a black box in single domains. How well such a model decides on its own in RL environments, and how it can improve RL as a component of training, therefore remain unaddressed. To this end, in this paper we first examine the requirements that the objects of an RL system place on the answers they consume, and establish that Jev can fulfill all of them except the cardinal use of a value function. The remaining objects form positions that admit several roles each. We then construct alg

---

### [175] Pumpire: Unified Benchmark for Metric Distance Estimation

**链接**: https://arxiv.org/abs/2610.12423
**作者**: Siyu Chen, Zehan Wang, Jiayang Xu, Yihan Wu, Jialei Wang, Junming Chen 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Pumpire, a unified benchmark for evaluating metric point-pair distance estimation capability of both image- and video-level 3D foundation models, with or without depth priors. In contrast to previous approaches that normally evaluate depth and camera intrinsics separately or evaluate point-clouds with geometric similarity metrics, which cannot directly reflect models' point-to-point distance estimation capability, Pumpire directly assesses point-to-point distances from the reconstructed geometry. To this end, we collect a large-scale and diverse dataset (pumpire-6k) comprising 100 real-world scenes, each annotated with physically measured point-pair distances and containing 64 frames, for a total of 6,400 frames. Building on this dataset, we establish a holistic evaluation protocol that covers both image- and video-level 3D foundation models and enables direct assessment of point-pair distance errors and cross-setting comparison. We conduct extensive experiments across 29 ba

---

### [176] GenIA: Generative Reconstruction with Test-Time Input Alignment

**链接**: https://arxiv.org/abs/2610.12388
**作者**: Stefano Esposito, Naama Pearl, Polina Karpikova, Samuel Rota Bul\`o, Lorenzo Porzi, Peter Kontschieder 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstructing complete 3D object assets from monocular or sparse multi-view observations remains challenging. Generative 3D foundation models can complete object geometry beyond the observed views, but their predictions may not faithfully reproduce the observed geometry, appearance, or pose. We introduce GenIA, a framework for test-time input-aligned generation that grounds SAM3D's generative prior in geometric and photometric observations without retraining the foundation model. We improve object pose by deriving translation and scale from geometry while retaining the learned rotation prior, and align appearance through visibility-biased attention, cross-observation fusion, and differentiable rendering guidance during denoising. An optional post-denoising refinement further adapts the appearance latent, lightweight decoder adapters, and object placement to the observations. Our framework also supports externally supplied geometry; when given temporal shapes of dynamic objects, it rec

---

### [177] Mine Odyssey: Benchmarking Spatial Agentic Intelligence in the Wild

**链接**: https://arxiv.org/abs/2610.11328
**作者**: Yuxuan Cao, Junlong Li, Hao Li, Junxian He
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in foundation models are driving efforts to introduce agents to assist people in the physical world. Such agents require agentic spatial intelligence: exploring unfamiliar environments, updating spatial understanding through interaction, and adapting actions based on feedback to sustain progress toward a sequence of goals. Existing benchmarks cover only a limited range of spatial layouts, scales, and traversal requirements. We introduce Mine Odyssey, a benchmark for evaluating agentic spatial intelligence using Minecraft reconstructions of real-world locations. It comprises 180 tasks covering 30 such locations across 20 countries and regions on five continents, including 20 outdoor and 10 indoor settings. These settings span diverse spatial scales, layouts, terrains, and connectivity patterns, from Midtown Manhattan and rural Entrup to Santa Luc\'ia Hill and Buckingham Palace. We select meaningful waypoints, such as landmarks, buildings, and rooms, and manually verify their ac

---

### [178] Strategic Governance of AI Models in Earth Science

**链接**: https://arxiv.org/abs/2610.10560
**作者**: Makoto Kelp, Amirhossein Arzani, Patricia Castellanos, Paul Griffiths, Ivan Higuera-Mendieta, Manuel Perez-Carrasco 等 (9 人)
**来源**: physics.soc-ph cs.AI cs.LG physics.ao-ph
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI foundation models pretrained on weather and climate data are increasingly fine-tuned to Earth science tasks well beyond weather forecasting. Their development and adoption are outpacing the scientific community's ability to evaluate them. These models are judged almost entirely by benchmark skill metrics, which measure how closely a forecast reproduces a reference product but not whether a model represents the physical processes governing the system it predicts. Forecast skill and physical reliability are therefore distinct properties. The distinction is most consequential under the nonstationary conditions of a changing climate for which these models were never trained. We identify five priorities for the physical evaluation of AI models in Earth science from task-specific emulators to foundation models, spanning training data, fine-tuning, behavioral testing, mechanistic interpretability, and output validation. We recommend three activities for the coming decade: 1) open AI-ready 

---

### [179] Mental-Models for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.12453
**作者**: Hanan Gani, Lulu Shao and Manmohan Chandraker
**来源**: cs.MA
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large foundation models have accelerated progress toward general-purpose agents that interact with humans and other agents through language and multimodal signals. However, robust multi-agent decision-making requires reasoning about what other agents know, intend, and are likely to do under partial observability. Current agentic systems often operate through prompt design, memory, or end-to-end behavioral shaping, but typically do not learn an explicit partner-state representation that can be reused as a decision variable across tasks. We introduce \emph{mental-model-enabled agents}, a framework that equips an agent with a latent mental model of its counterpart, allowing it to infer hidden beliefs, intentions, and likely reactions from the observed history and use these inferences to guide action selection. Our method learns an amortized recursive Theory-of-Mind representation, with first- and second-order mental-state structure, jointly with a belief-conditioned reward model that eval

---

### [180] Pose-Free Feed-Forward 3D Inpainting via Learnable Mask Attention and Support Token Refinement

**链接**: https://arxiv.org/abs/2610.11857
**作者**: Jingyi Pan, Dan Xu, Qiong Luo
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D scene inpainting aims to recover missing or occluded regions in edited 3D scenes, while ensuring geometric and textural consistency. Existing approaches, however, typically require accurately calibrated camera poses, which restricts their applicability in casual, in-the-wild scenarios and introduces additional preprocessing overhead. To overcome this limitation, we present FreeInpaint, a novel feed-forward framework that generates complete and 3D-consistent scenes directly from unposed multi-view images with masked regions. At its core, FreeInpaint extends a 3D foundation model to propagate masked regions from a reference view to other unposed views, bridging 3D reconstruction and scene inpainting while preserving the model's native ability to recover camera poses and scene geometry. Our method addresses two key challenges in adapting feed-forward 3D foundation models to masked inputs. First, masked regions can corrupt cross-view correspondence reasoning, degrading pose estimation a

---

### [181] Timer-M1: A Multivariate Time Series Foundation Model via Learning Primitives

**链接**: https://arxiv.org/abs/2610.11734
**作者**: Haoran Zhang, Haixuan Liu, Xingjian Su, Yong Liu, Zhi Chen, Yuxuan Wang 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Timer-M1, a pretrained multivariate time series foundation model that learns with primitives for zero-shot forecasting. Across domains, time series share elementary temporal and relational patterns, termed primitives, yet differ in how these primitives manifest and evolve across different contexts. Despite progress in zero-shot and task-general forecasting, existing foundation models may still struggle to generalize to complex real-world scenarios. To this end, we develop a primitive-based data synthesis and pretraining pipeline. The synthesis pipeline generates series with temporal primitives shared across domains and then assembles real and generated series into multivariate samples using relational primitives. Afterwards, samples are organized into episodes by assigning distinct channel roles as target variates, past-only covariates, and known-future covariates, ensuring that the model is optimized on predictable variates using available exogenous information. Technical

---
