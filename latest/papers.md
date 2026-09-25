# 📑 论文索引 - 2026-09-26

共 133 篇论文

---

### [1] Novelty Adaptation Through Hybrid Large Language Model (LLM)-Symbolic Planning and LLM-guided Reinforcement Learning

**链接**: https://arxiv.org/abs/2603.11351
**作者**: Hong Lu, Pierrick Lorang, Timothy R. Duggan, Jivko Sinapov, Matthias Scheutz
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] MoVISA: Multi-Token Reasoning for Video Object Segmentation

**链接**: https://arxiv.org/abs/2609.28956
**作者**: Ruining Zhao, Ho Kei Cheng, Alexander G Schwing
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in video object segmentation with Multimodal Large Language Model (MLLM) reasoning have demonstrated the effectiveness of using a single textual token, such as SEG, to predict segmentation masks across images and videos. However, we observe that this single-token strategy lacks the granularity required to precisely localize multiple objects across time in video segmentation tasks. To address this limitation, we develop Multi-Token Reasoning for Video Object Segmentation, or MoVISA. MoVISA uses multiple segmentation tokens, such as SEG0 and SEG1, to represent an object across different frames. This design enables more fine-grained alignment between language prompts and spatio-temporal mask predictions, improving both performance and interpretability. On the challenging MeViS, DAVIS17, ReVOS, and Ref-Youtube-VOS benchmarks, our model achieves a 13.2 percent J and F improvement on MeViS and an 8.4 percent J and F improvement on ReVOS. Code and models will be released.

---

### [3] CORDIAL: Calibrating Ordinal LLM Outputs from Few Labels

**链接**: https://arxiv.org/abs/2609.29807
**作者**: Xiangwei Wang, Peng Wang, Saman Halgamuge
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large language model (LLM) can turn a text into a distribution over an ordered scale, but that distribution is a noisy measurement: saturated, compressed or exaggerated, and biased in a consistent direction. We propose CORDIAL, which treats the model's output as a noisy reading of the true label and corrects it with a channel of five interpretable parameters. The channel is small enough for its posterior to be averaged from a handful of labels, and we prove that the resulting calibration preserves first-order stochastic order. On Amazon reviews and CMU-MOSEI transcripts with four LLMs, CORDIAL has the lowest log loss among nine calibrators in 76 of 80 settings with 5 to 100 labels; with 20 labels and the main 7B reader, it matches the strongest baseline using 28-54 labels. The same posterior lets us learn priors from other tasks and fuse several LLMs. Unrestricted calibrators such as Dirichlet calibration overtake it only as the calibration set grows into the hundreds or thousands.

---

### [4] Progressive Skill Discovery as Access Control for Tool-Using LLM Agents: Structural Governance through Role-Scoped Capability Delivery

**链接**: https://arxiv.org/abs/2609.28693
**作者**: Michael Stettler, Benjamin Girardet, Jonas Canton and Nicolas Corod
**来源**: cs.AI cs.CR cs.MA cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents struggle to scale safely when exposed to vast enterprise toolsets. Providing an agent with access to every internal tool leads to oversized context windows, degraded tool selection, and severe governance vulnerabilities - as system policies defined purely in prompts remain probabilistic advice rather than hard constraints. Existing mitigations, such as multi-agent domain delegation, decentralize audit logs and fail to guarantee policy compliance across sessions. We introduce skilder, a framework that packages capabilities into roles: bundles of skills, tools, and instructions, together with the limits that bound them. An agent begins with a minimal role catalog, learns the roles a task requires, and receives each role's skills, instructions, and tools through a single MCP server. Because tools reach the agent only inside learned skills, the same server enforces the scope of what was learned deterministically. We evaluate skilder against flat-context to

---

### [5] EvoTreeNAD: Genealogy-Guided Evolution for LLM-Driven Neural Architecture Discovery

**链接**: https://arxiv.org/abs/2609.29016
**作者**: Lishan Yu, Derek Jiu, Qizhen Lan, Xiaoqian Jiang
**来源**: cs.NE cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-driven scientific discovery accelerates research by autonomously developing solutions and designs. Large language model (LLM) agents support this process through iterative generation and evaluation. Yet these iterations alone do not ensure cumulative progress or establish which directions to pursue next. Costly evaluation further constrains the scope of exploration. Neural architecture discovery brings these challenges together, coupling open-ended design with resource-intensive experimentation. We introduce EvoTreeNAD, a genealogy-guided evolutionary algorithm that constructs trainable architectures without a supplied seed or a hand-specified search space. Starting from an empty root, it grows a persistent genealogy in which each new node represents a complete architecture. Top-percentile values computed from each node and its descendants guide lineage selection. Using the selected design history, an Idea Agent proposes a variant and a Code Agent implements it. Each evaluated varia

---

### [6] Industrial Anomaly Detection via Defect-Grounded Reasoning in Visual Latent Space

**链接**: https://arxiv.org/abs/2609.29457
**作者**: Jaron Yeh, Yen-Wei Chang, Jiang Liu, Shao-Yuan Lo
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial anomaly detection (IAD) is evolving beyond conventional detection and localization toward multimodal inspection systems that can describe, explain, and reason about fine-grained defects. Although recent multimodal large language model (MLLM)-based methods improve anomaly understanding through textual reasoning and visual guidance, they face two limitations in fine-grained inspection. First, their visual refinement often requires iteratively revisiting local image regions or augmenting with additional tools. Second, the resulting local defect evidence may not be reliably preserved throughout subsequent reasoning. To address these, we propose Anomaly-LR, a defect-grounded latent reasoning framework that first forms a global understanding of the input and then progressively refines anomaly-relevant representations directly in the visual latent space. We further construct IAD-LR-22K, the first IAD instruction dataset designed for latent reasoning, containing 22,228 image-questio

---

### [7] A Wrong Turn Does Not Ruin the Journey: Deviation-Guided Skill Self-Evolution for LLM Agents

**链接**: https://arxiv.org/abs/2609.29154
**作者**: Yichun Feng, Jiawei Wang, Haozhe Sun
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly rely on natural-language skills to solve complex tool-use tasks. However, such tasks often admit multiple valid solution paths, making it inappropriate to improve skills by forcing failed trajectories to match a fixed successful trajectory. Moreover, failed trajectories are rarely entirely wrong: an agent may first collect useful evidence and make meaningful progress, but later deviate into an erroneous suffix. We therefore argue that skill self-evolution should identify where productive problem solving begins to break down, rather than reflect coarsely over the entire failure. Based on this insight, we propose SkillPivot, a deviation-point-guided framework for skill self-evolution. SkillPivot detects the transition from a useful prefix to an erroneous suffix using execution validity, goal progress, and action diversity. A stronger teacher then continues from the same prefix and produces a successful alternative under the same interaction histor

---

### [8] Evaluation of Multi-Turn Consistency in LLM Agents: Survival Analysis and Failure-Rationale Taxonomy

**链接**: https://arxiv.org/abs/2609.29508
**作者**: Igor Bogdanov, Olga Manakina, Chung-Horng Lung
**来源**: cs.AI cs.CL cs.LG cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents may perform well on isolated tasks yet drift into inconsistency over extended interaction. We evaluate temporal consistency in a controlled 20-step multi-agent setting inspired by delayed-gratification studies. At each step, an agent chooses between continuing to delay a reward or claiming it immediately (terminating the episode). Across a full-factorial manipulation of social visibility (private vs public), persona stressors, and deliberation policy, we run 84,540 trajectories spanning 8 model families. Treating the first reward-claim as a time-to-event outcome, we estimate Kaplan-Meier survival curves and fit discrete-time hazard regression to quantify how experimental factors shift failure risk over time. Then, to analyze rationales and language patterns associated with failure, we build a seven-category taxonomy from 13,780 deliberation traces from agents who choose to terminate the episode, using an LLM-assisted labeling paired with human audit ($

---

### [9] ChunkRank: Model-Aware Text Chunking and Abstention-Aware Answer Selection for LLM Pipelines

**链接**: https://arxiv.org/abs/2609.29828
**作者**: Amit Nautiyal, Ayush Bhatt, Gaurav Nautiyal
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present ChunkRank, an open-source Python library that derives chunk boundaries from a target model's tokenizer and context window, and selects an answer among candidates produced independently per chunk. It ships a validated registry of 90 models across 15 providers and six answer-selection methods, and needs only three core dependencies. For chunking, ChunkRank avoids context-window overflow automatically from the model name, whereas character-based splitters overflow or waste the budget, and a fidelity study across 11 languages shows why token-exact budgets matter beyond English. For answer selection we report a negative result: on NaturalQuestions, TriviaQA and HotpotQA, with extractive and generative readers, no content-based ranker reliably beats taking the first non-empty answer. The reason is reader abstention on chunks that lack the answer, not answer position. A long-context baseline shows that chunking matches single-call reading on single-hop questions, so ChunkRank targe

---

### [10] AlphaDiverse: Post-Training Local Quantitative Research Agents for Diverse Exploration in Alpha Factor Mining

**链接**: https://arxiv.org/abs/2609.29014
**作者**: Qingzhuo Wang, Zikun Wei, Zhihua Wei, Wen Shen
**来源**: cs.AI cs.CE cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems can automate alpha factor mining, but their reliance on external APIs limits control over cost, availability, and confidentiality. Long research loops also tend to revisit a few successful economic mechanisms that lead to research path collapse. To address these limitations, we propose AlphaDiverse, a framework that integrates a multi-agent alpha research system, diverse research path collection, and post-training for local agents. We let the research system generate complementary plan portfolios and vary research environments across loops to collect diverse research paths. Using these diverse traces, we warm-start local Planner and Realizer agents with supervised fine-tuning. Then, we propose a joint GRPO method to optimize both of them using predictive quality and diversity of contributions. Research feedback is confined to inner period data, while a frozen final model is evaluated on a later outer period data, thereby avoiding tes

---

### [11] A Living Benchmark for Information Retrieval from Electronic Health Records

**链接**: https://arxiv.org/abs/2609.30205
**作者**: Jordan L. Cahoon, Chloe O. Stanwyck, Sulaiman Somani, Philip Chung, Kevin R Keet, Kameron C. Black 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based clinical assistants are increasingly being integrated into electronic health record (EHR) systems, transforming how clinicians retrieve and synthesize information from patient records. Their safety and utility depend on rigorous evaluation, yet existing benchmarks are manually curated, costly to update, and rapidly become obsolete with evolving technological advancements. We present a scalable framework that automatically generates question--answer pairs from longitudinal EHR notes. Nineteen clinicians validate the benchmark generator, producing the Benchmark for Retrieving Information in EHRs (BRIE), a continuously maintainable evaluation dataset. Across nine LLMs and five inference strategies, state-of-the-art systems frequently omit clinically important information, particularly for questions requiring synthesis across multiple documents and encounters. Because the generator itself is validated, BRIE supports evaluations that static benchmarks cannot

---

### [12] Three Ways Classical Test Theory Misleads for LLM Judges

**链接**: https://arxiv.org/abs/2609.29709
**作者**: Louis Yiven Zhu
**来源**: cs.LG cs.CL stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM judge scores a bank of responses against a rubric, and the reliability comes back at $0.52$. What has been measured? Judge evaluation has begun borrowing reliability statistics from classical test theory, usually without stating the measurement design each statistic assumes, and we show that three widely portable ones mean something different for a judge than for a test because the judge setting rearranges the roles those designs rest on. First, an internal-consistency coefficient computed over rubric elements contains no scorer facet. Holding one judge's measured error rate fixed at $4.72\%$, KR-20 still ranges from $0.01$ to $0.68$ as the item bank is redesigned around it, and varying judge error moves the coefficient by a comparable amount, so item design and judge error are not separately identified and no single value can be read as a property of the judge. Second, the dependability index $\Phi(\lambda)$ is a ratio of variance components, and the classification probability 

---

### [13] Polite but Misaligned: Evaluating LLM Politeness Judgments Against Human Pragmatic Norms

**链接**: https://arxiv.org/abs/2609.29001
**作者**: Rong Wang, Kun Sun, and Yadong Guo
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite strong performance on standard benchmarks, it remains unclear whether large language models (LLMs) evaluate social pragmatics in ways that align with human judgments. We evaluate LLM politeness judgments using two English-language datasets with complementary annotation formats: continuous human ratings and three-way categorical labels. Across the seven evaluated models, we find that inter-model agreement is stronger than model--human agreement. Strategy-level analyses suggest that model--human alignment is associated with explicit linguistic cues, while some rapport-building strategies occur more frequently in misaligned cases. In the categorical task, model predictions exhibit systematic neutral compression, characterized by the overproduction of Neutral labels and the underprediction of Impolite labels. This pattern persists when expert consensus is used as the reference on a diagnostic subset. Our findings highlight the need for pragmatic evaluations that go beyond aggregate

---

### [14] How Many Humans Are 32 LLM Judges Worth?

**链接**: https://arxiv.org/abs/2609.21277
**作者**: Chao Li, Yingying Yu, Yunfeng Li
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] Breaking the Environment Wall: Evolving LLM Agent Environments for Recursive Self-Improvement

**链接**: https://arxiv.org/abs/2609.29773
**作者**: Yukai Wu, Yuanjing Yang, Le Zhou, Shaokun Han, Haoyu Wang, Zirui Tang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many real-world tasks (e.g., office workflows, scientific experimentation) require LLM agents to interact repeatedly with their environments for context-dependent operations. However, such environments are often not agent-ready. First, information is often scattered and fragmented across the environment. Second, relevant evidence in the environment is often mixed with misleading information and conflicting versions. Third, environments evolve over time, introducing new noise and more challenging tasks. These challenges can substantially degrade performance for state-of-the-art AI agents (e.g., from 83.9% to 57.6%). To address these challenges, we propose Env-Rethink (a system with 27B post-trained model) that supports three main capabilities: (1) It adaptively builds Collection Maps (for organizing related files) and Event Logs (for contextualizing cross-data relationships) to supplement necessary context; (2) It further leverages the post-trained model (through offline trajectory lear

---

### [16] How Reproducible Are Evaluation Conclusions? A Self-Audit of LLM-Inferred Prompt Structure

**链接**: https://arxiv.org/abs/2609.30074
**作者**: Dipankar Sarkar
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluations of LLM systems routinely average over small prompt sets and report models as a ranked table. We ask how much confidence such a table deserves, using LLM-based prompt-structure inference as the case study: eight open model variants across five families and 8B to 675B parameters, caching disabled, 293 raw intermediate representations persisted. The measured phenomenon is unstable to begin with. Identical calls do not reliably recover identical structure, with mean node-set Jaccard from 0.39 to 0.96 and 72% of prompt-model cells never node-set-perfect. Auditing the evaluation weakens its conclusions further, and this is our main contribution. Under a joint cluster bootstrap over prompts, only the bottom of the ranking is firm: the two least reproducible models hold rank in 99% and 86% of replicates, the middle four in 27% to 48%, and the top two in 68% each, so the table identifies the worst model reliably but does not reliably identify the best. Two equally defensible rules f

---

### [17] Reflex-Guard: A Low-Latency Guardrail for LLM Prompt Safety Using Dense Semantic Embeddings

**链接**: https://arxiv.org/abs/2608.17556
**作者**: Istiaque Ahmed, Afia Anjum Borsha, Ranat Das Prangon, Abu-fuad Ahmad, Thi Hong Tran
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] LLM Agents Can Easily Tamper With Their Own Traces

**链接**: https://arxiv.org/abs/2609.30266
**作者**: Jeremy Qin, David Schmotz, Derck Prinzhorn, Luca Beurer-Kellner, Ameya Prabhu, Maksym Andriushchenko
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Asynchronous monitoring, incident investigations, and compliance audits primarily rely on agent traces to reconstruct what happened. These analyses assume that LLM agents cannot tamper with their own execution traces. We show that local LLM agents such as Claude Code, Codex, Antigravity, Open Code and Grok Build fail to enforce this boundary. All tested harnesses, except Muse Code, allowed agents to delete their traces when asked, without triggering monitor guardrails. We also validate that external attackers can exploit this gap to induce trace deletion. Finally, we show that trace tampering behavior emerges naturally in frontier models, when agents try to improve their rewards. We advise practitioners to ensure trace logging happens through an independent interception mechanism outside of the agent's control, preserving trace integrity even in cases of full host compromise. Overall, our findings identify a concrete failure of trace integrity in agent infrastructure which can be used 

---

### [19] RapidUn: Influence-Driven Parameter Reweighting for Efficient Large Language Model Unlearning

**链接**: https://arxiv.org/abs/2512.04457
**作者**: Guoshenghui Zhao, Huawei Lin, Weijie Zhao
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Decoupling Knowledge and Privacy: Post-Task Self-Distillation Replay for LLM Continual Learning

**链接**: https://arxiv.org/abs/2609.29711
**作者**: Shengtao Wen, Yunying Yang, Xiang Chen, Lingbing Guo, Yu Tian, and Sheng-Jun Huang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Privacy-preserving continual learning (PPCL) must reduce the reproduction of sensitive content while retaining useful knowledge across sequential tasks. Formal privacy guarantees characterize randomized mechanisms, whereas operational output control concerns whether a trained model selectively reduces the likelihood of sensitive content in its outputs. In this work, we investigate the latter together with continual-learning utility under realistic task evolution. Retention and privacy correction operate at different granularities: task acquisition requires broad preservation of current- and old-task behavior, whereas privacy correction targets sparse annotated positions. Joint optimization leaves the current-task preservation target continually changing. We propose SPARK, a retention-correction decomposition that first freezes the learned post-task distribution and then applies selective correction around this stable reference. Self-Distillation Replay learns the current task while dis

---

### [21] Calibrated Decision Models for Autonomous Penetration-Testing Harnesses: JEV and Laya as System One Decision Layers for LLM-Driven Pentest Agents

**链接**: https://arxiv.org/abs/2609.28940
**作者**: Joas Antonio dos Santos Barbosa
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous penetration-testing harnesses use large language models (LLMs) for reconnaissance, exploitation, and reporting, but often rely on those same models to confirm findings, grade severity, and select agents. This can lead to false positives, inflated severity, and wasted compute. We examine how System One decision models, lightweight non-generative classifiers that return typed, calibrated verdicts, can support these decisions. We make five contributions. First, we define four decision points: finding adjudication, severity recalibration, agent pruning, and confirmation loops. Second, we present an exploratory NeuroSploit case study comparing one run with TypeSafe System One (Jev) and one without it against a web target containing 13 vulnerabilities. Differences in severity distribution, runtime, and grading by exposed data type motivate the architecture but do not establish statistical significance. Third, we review published specifications for Jev, Jev-Ultrafast, and the open-

---

### [22] Robust Detection of LLM-Generated Text under Contamination

**链接**: https://arxiv.org/abs/2609.29935
**作者**: Jiaxun Li, Saptarshi Chakraborty, Ambuj Tewari
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study the detection of LLM-generated text under editing and contamination. Modeling human and machine text as finite-order Markov processes with Huber contamination, we characterize an exact boundary for reliable detection under our assumptions. Detection is impossible when contamination is sufficiently large relative to clean-source separation. Below this boundary, a collection of clipped likelihood-ratio tests achieves vanishing worst-case errors. This construction motivates clipping as a simple modification of existing statistical detectors. For a broad class of additive scores, we identify conditions under which the clipped test is consistent while the raw test's worst-case power tends to zero. We evaluate seven detectors across three datasets and three generation models, and on the RAID benchmark. Clipping improves robustness in both studies, with gains varying across detectors and contamination settings. For example, at a target false-positive rate of 5\%, clipping improves th

---

### [23] Task-Aware Spectral Pruning: A Mixture-of-Masks Framework for Efficient LLM Inference

**链接**: https://arxiv.org/abs/2609.29499
**作者**: Ibne Farabi Shihab and Fariya Afrin and Sanjeda Akter and Anuj Sharma
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Static pruning imposes one sparse structure on every prompt, even though reasoning, retrieval, generation, coding, and translation can depend on different parts of a language model. We introduce Task-Aware Spectral Pruning (TASP), a post-training framework that calibrates module-level spectral descriptors against measured task-specific ablation effects, closes grouped-query-attention and SwiGLU dependencies during sparse-mask construction, and routes each user turn to one compiled mask that remains fixed throughout prefill and decoding. A module-disjoint pilot first determines whether the spectral signal is informative before full calibration. Under the stated retrospective operating rule, the pilot passes on the evaluated Llama-3-8B and Llama-3-70B checkpoints but rejects Qwen2.5-1.5B, demonstrating that applicability is model-dependent rather than universal. At a 43% active-FLOP reduction, the Llama-3-70B benchmark harness retains 97.7 +/- 0.2% of the dense BF16 score. In the deploym

---

### [24] LLM Forensics: Where Do Backdoors Hide? Localizing and Controlling Trigger Mechanisms with Sparse Autoencoders

**链接**: https://arxiv.org/abs/2609.07746
**作者**: Wissam Antoun, Francis Kulumba, Th\'eo Lasnier, Beno\^it Sagot, Djam\'e Seddah
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] CRISS: A Retrieval-Augmented AI Chatbot for Assisting Cancer Registrars

**链接**: https://arxiv.org/abs/2609.29075
**作者**: Vani Seth, Mohammad Beheshti, Anirudh Kambhampati, Vishwa Bhayani, Lucinda Ham, Prasad Calyam 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cancer registrars, including Oncology Data Specialists (ODSs), must interpret complex and frequently updated coding and staging standards. We developed CRISS (Cancer Registry Intelligent Support System), a retrieval-augmented generation (RAG) conversational assistant that provides rapid, citation-supported access to registry guidance. This study evaluated whether CRISS could (1) support accurate and citation-supported responses, (2) improve access to and interpretation of relevant guidance, and (3) support training/helpdesk use while preserving human oversight of final abstraction decisions. We built a domain-specific knowledge base from national cancer registry standards, segmented into metadata-tagged passages and indexed as dense embeddings. Retrieved passages were used to generate citation-grounded responses through a large language model (LLM). Open-weight, proprietary, and non-RAG baseline models across Gemini and GPT families were evaluated on easy, medium, and hard registry que

---

### [26] Towards An LLM-Driven Unified Conversion Framework for BT and FSM in Autonomous Intelligent Systems

**链接**: https://arxiv.org/abs/2609.29228
**作者**: Zhang Qi, Yang Shuo, Zhu Zhengqiu, Zhou Peng, Jiao Peng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Finite state machine (FSM) and behavior trees (BT) are widely adopted behavioral modeling paradigms for autonomous intelligent systems. While functionally equivalent and inter-convertible in principle, existing transformation methods between FSM and BT face major challenges in preserving behavioral completeness and avoiding model complexity explosion. To overcome these issues, we propose an LLM-driven unified conversion framework that enables automatic, efficient, and semantically consistent transformation between FSM and BT. Specifically, a novel loop execution BT structure is designed for LLM to accurately capture the loop structure in FSM, thereby preserving behavioral completeness. To mitigate the state explosion problem in BT-to-FSM conversion, a depth compression strategy is introduced with LLM prompt to eliminate redundant control nodes, complemented by differentiated hierarchical conversion rules that collectively reduce the number of required sub-FSM. Simulation experiments in

---

### [27] TIDE: Temporal Incremental Draft Engine for Self-Improving LLM Inference

**链接**: https://arxiv.org/abs/2602.05145
**作者**: Jiyoung Park, Hankyu Jang, Changseok Song, Wookeun Jung
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] Where LLM Graders Succeed and Break: Evidence from Two Computer-Science Exams

**链接**: https://arxiv.org/abs/2609.29333
**作者**: Ali Habibullah, Yazan Alshoibi, Mohammad Alshiekh, Salman Khan and Naeemullah Khan
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> One long-form exam in a large course costs hundreds of grader-hours, and qualified graders are scarce; LLM graders are a tempting alternative. To show its pitfalls we grade a practical Computer Vision exam ($570$ dual-graded students) under $171$ configurations spanning closed and open-weights models; the best reaches mean absolute error $1.64/35$, below the $2.61/35$ two human graders achieve against each other. The catch is the prompt: a short ''strict grader'' preamble drives $14$ of $17$ open-weights models out of the graded band ($\text{MAE} \ge 8$), three stopping grading altogether. The damage traces to the preamble's two credit-withholding sentences, not to tone or model scale; one of them, ''never give partial credit'', alone makes two of three probed models stop grading. The closed flagships of three vendors shift calibration under it but stay in the band. In $162$ further configurations on a second, independent Machine Learning exam from another course ($1{,}038$ dual-graded

---

### [29] Cultural Divergence Preservation: Diagnosing Flattening and Caricature in LLM-Simulated Survey Populations

**链接**: https://arxiv.org/abs/2609.29928
**作者**: Yeeun Chae, Yewon Choi, Seunghyun Lee, IL Im
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as synthetic survey respondents to estimate population response distributions. In cross-cultural survey simulation, evaluations should assess not only distributional fidelity within countries but also whether differences across countries are preserved. However, existing distance-based metrics such as Jensen--Shannon divergence (JSD) do not directly capture such cross-country differences. To address this limitation, we introduce Cultural Divergence Preservation (CDP), a reference-light diagnostic based on a one-time human calibration. CDP identifies reduced cross-country divergence as cultural flattening and increased divergence as cultural caricature. To evaluate CDP, we conduct experiments across four LLM backbones, three persona-based prompting methods, and two survey domains, the World Values Survey (WVS) and the Big Five Personality Test. The results reveal a systematic discrepancy between conventional fidelity metrics and CDP. Con

---

### [30] MemGuard-Alpha: Limits of Membership Inference for Detecting and Filtering Memorization-Contaminated Signals in LLM-Based Financial Forecasting

**链接**: https://arxiv.org/abs/2603.26797
**作者**: Anisha Roy, Dip Roy
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] The Troy Moment: How LLM Agents Adjudicate the Decision Point Under Impossible Tasks, Claimed Authority, and Peer Information

**链接**: https://arxiv.org/abs/2609.15494
**作者**: Ivy Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] CataOPD: Catalytic On-Policy Distillation for Large Language Model Reasoning

**链接**: https://arxiv.org/abs/2609.29518
**作者**: Wenjin Liu, Chenxi Wang, Jiapu Wang, Zhe Cui, Anh Tuan Luu, and Haoran Luo
**来源**: cs.LG cs.CE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) and on-policy distillation (OPD) are two representative paradigms for improving large language model reasoning. However, when no correct trajectory is sampled, RL lacks a positive correctness signal, while OPD remains constrained by the reasoning trajectories reachable under the student's on-policy distribution. Therefore, we propose CataOPD, where the teacher acts as a catalyst rather than a target, expanding reachability while internalizing verified student-produced trajectories into a catalyst-free policy. Self-Rescue Routing uses empirically all-failed groups as routing signals rather than teacher-intervention triggers, first seeking correct trajectories through additional on-policy self-sampling. For problems unresolved after self-rescue, Catalytic-Guided Self-Resolution uses catalytic guidance to elicit a verified student-produced trajectory in the guided student distribution. Barrier-Weighted Internalization weights tokens by guided-to-unguided log-pr

---

### [33] Blockchain-Enabled Artificial Intelligence and AI Agents for Secure Data Sharing and Cybersecurity Applications

**链接**: https://arxiv.org/abs/2609.28843
**作者**: Harsh Verma
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Blockchain and artificial intelligence (AI) are converging into a single infrastructural layer for securing data sharing, model integrity, and autonomous decision-making across distributed systems. This paper presents a meta-synthesis that draws together four constituent studies covering adversarial machine learning, AI-powered anomaly detection in cloud environments, automated vulnerability patching by multi-agent large language model (LLM) pipelines, and the broader landscape of securing AI systems across their lifecycle and situates their findings within the emerging literature on blockchain-enabled AI and autonomous AI agents. Each constituent study addresses a distinct point of failure in modern AI-driven security operations: the integrity of training data and model behavior, the reliability of real-time monitoring, and the trustworthiness of automated code remediation. We argue that blockchain's properties of immutability, decentralized consensus, and verifiable provenance direct

---

### [34] Where Does Exactly-Once Live? Model, Harness, and Tool-Contract Effects on Duplicate Side Effects in LLM Agents

**链接**: https://arxiv.org/abs/2609.29095
**作者**: Jiapeng Li
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a tool-using agent's write times out or returns a server error, the action may already have taken effect. Retrying blindly duplicates it -- a second charge, a second announcement, a second deployment -- while giving up skips required work. We ask where exactly-once behaviour should be enforced: in the model, in the agent harness, or in the tool contract. We introduce LIMBO, a deterministic sandbox of six services with realistic contracts (optional idempotency keys, eventually consistent and missing read paths) and twelve fault modes injected at the service boundary, including late commits, redelivery and partial batches; every episode is graded against a ledger of committed effects. Across 25,930 episodes spanning nine recent models, three production agent harnesses, two contract variants and fifteen recovery conditions, the answer depends on the fault. When an immediate read-back can reveal what happened, the model decides: frontier models instructed to act exactly once almost ne

---

### [35] Calibrating LLM Judges for Human and AI Conversations

**链接**: https://arxiv.org/abs/2609.29431
**作者**: Maike Z\"ufle, Patr\'icia Schmidtov\'a, Vil\'em Zouhar, Shree Harsha Bokkahalli Satish, Erica Cooper, Shobhit Banga 等 (10 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Measuring how successful a conversation is remains difficult, even for humans judging spoken dialogue. We evaluate state-of-the-art LLMs as pointwise and pairwise judges of conversational success on CANDOR, finding pointwise scoring correlates moderately with human ratings, while pairwise comparison suffers from long transcripts and positional bias. Since this leaves judge scores incomparable across models, we propose a small anchor set and a calibration function that calibrates any judge onto a shared, interpretable scale. We further release the Voice Arena Goal Dataset (VA), 200 task-oriented human-AI and human-agent conversations with pairwise annotations, revealing a substantial gap between current judges and human-level discrimination. Using VA, we test whether CANDOR-fitted calibration transfers to human-AI conversations, finding it brings judges onto a shared scale despite never observing VA during fitting.

---

### [36] LLM surprisal is necessary but not sufficient to capture English garden-path effects: Evidence from joint latent modeling of reading paradigms

**链接**: https://arxiv.org/abs/2602.04489
**作者**: Dario Paape, Tal Linzen, Shravan Vasishth
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] PrivDrift: Auditing User-Secret Leakage Under Topic Drift in Active LLM Conversations

**链接**: https://arxiv.org/abs/2609.30094
**作者**: Luciano Maldonado
**来源**: cs.AI cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly operate as persistent assistants in user-facing, shared-session, and tool-augmented settings. When users disclose sensitive information during an active conversation, that information may remain behaviorally recoverable through later prompts even after the dialogue shifts to unrelated topics. We introduce \textbf{PrivDrift}, a benchmark for auditing whether user-disclosed secrets remain recoverable after conversational topic drift and persuasion-based probing. PrivDrift contains 1{,}000 controlled multi-turn dialogues with seeded secrets, content-dense drift turns, and standardized extraction probes. Across three LLMs with extended context windows, dialogue-level hybrid leakage remains substantial, ranging from 38.7\% to 54.6\%, and varies strongly by model, secret type, and persuasion intensity. Within the tested drift window, additional topic drift does not reliably reduce leakage, suggesting that privacy risk in active LLM contexts should be evalua

---

### [38] Stale Does Not Mean Unsafe: Guard Precision for Tool-Using LLM Agents under Infrastructure State Races

**链接**: https://arxiv.org/abs/2609.29522
**作者**: Zihao Zheng, Jiayu Long, Baichuan Li, and Junyi Yao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using language-model agents increasingly mutate schedulers, data pipelines, object stores, and access-control systems. Between an agent's read and its commit, external state can change, but not every change makes the commit unsafe. We separate invalidating races, which break a declared safety predicate, from predicate-preserving and irrelevant races, and ask how precisely runtime guards distinguish them. Our deterministic simulator separates visible from authoritative state and injects five non-atomic failure mechanisms across 16 infrastructure tasks in four domains; frozen agent proposals are replayed counterfactually under every controller without an LLM judge. We evaluate three commit-time guard granularities (global epoch, read-set version, semantic commit predicate), multi-level verification, and model-side gates on three locally hosted quantized model families (Qwen3-4B, Phi-4-mini, Gemma4-8B; 3,456 trajectories on one GPU). All three guards eliminate unsafe commits, but the

---

### [39] Forecast-Dojo: Replayable Environments for Benchmarking and Training LLM Forecasting Agents

**链接**: https://arxiv.org/abs/2609.28876
**作者**: Liqin Ye, Haorui Wang, Fardin Ahmed, Rongzhi Zhang, Yuan He, Ziyuan Lin 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Forecast-Dojo, a replayable environment for benchmarking and training LLM forecasting agents. It combines resolved prediction-market questions with dated news, allowing agents to research an event and revisit their predictions at successive historical dates. The same tasks and tools support repeated evaluation, collection of training interactions, and feedback from recorded outcomes without waiting for new events to resolve. Forecast-Dojo contains 1,568 Polymarket events, split by time into training and evaluation periods, and 18.8M dated news articles. In an evaluation of 12 models, research tools lower Brier score for all 12. Forecasts also improve as events unfold, with the largest gains at steps where more newly dated evidence is recorded. Every model still trails historical market forecasts in both Brier score and accuracy. A belief notebook carried between dates lowers research cost but does not consistently improve forecast quality. Beyond evaluation, Forecast-Dojo 

---

### [40] Vibe Patenting: Evaluating LLM Judges for Professional Patent-Drafting Agents

**链接**: https://arxiv.org/abs/2609.13422
**作者**: Toshiaki Koike-Akino, Vladislav Blaykhman, Ye Wang, Jing Liu, Gene V. Vinokur
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Tag-Aware Structured Text Translation: Towards a Systematic Understanding

**链接**: https://arxiv.org/abs/2609.29131
**作者**: Zhanglin Wu, Hengchao Shang, Daimeng Wei, Jiaxin Guo, Zongyao Li, Tengfei Song 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Internet texts are replete with format tags that carry structural, semantic, and functional meaning. Current large language model (LLM)-based translation systems struggle to balance translation fluency with tag fidelity when processing tagged text. We argue that resolving this tension requires a systematic approach at three interconnected levels: data synthesis, capability building, and multi-objective alignment. At the data level, we identify and formalize a fundamental trade-off between structural tag diversity and translation naturalness in synthetic data generation; existing methods optimize for one at the expense of the other. We propose a hybrid synthesis strategy (Hy-LST) combining LLM-based synthesis tag method and Two-Stage LLM-based synthesis tag method to produce both diverse and natural tagged data. At the capability level, we decompose tag-aware translation into four sub-tasks of increasing difficulty in a multi-task supervised fine-tuning framework, enabling targeted capa

---

### [42] ArGuard Shared Task: Harmful Content Detection in Arabic Memes and LLM Prompts

**链接**: https://arxiv.org/abs/2609.29349
**作者**: Firoj Alam, Md. Rafiul Biswas, Mohamed Bayan Kmainasi, Ali Ezzat Shahroor, Hamdy Mubarak, George Mikros 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> ArGuard is a shared task on harmful content detection in Arabic memes and LLM prompts. It includes two tracks: Track A focuses on multimodal hate detection in Arabic memes, while Track B addresses harmful prompt detection for Arabic LLM safety evaluation. In total, 58 teams registered, 35 participated in the final evaluation, and 27 submitted system-description papers. Participating teams explored models such as AraBERT, Jais, and Qwen3-VL. The best systems achieved macro-F1 scores of 0.823 on A1, 0.419 on A2, 0.984 on B1, and 0.790 on B2. Fine-grained meme classification in A2 was the most challenging setting, partly due to sparse labels and train-test distribution shifts.

---

### [43] Epistemic-Probabilistic Model for Guarded Multi-Agent LLM Coordination

**链接**: https://arxiv.org/abs/2609.29366
**作者**: Mehdi Nasiri, Mohammad Saeed Arvenaghi, Sadegh Vaezi, and Ebrahim Ardeshir-Larijani
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language models (LLMs) have become ubiquitous in applied AI, yet their theoretical foundations remain surprisingly understudied. Viewed through the lens of multi-agent systems theory, several shortcomings come to light: a lack of social intelligence, the absence of coordination mechanisms among agents, unknown emergent behavior, and interactions between agents that are bounded by natural language. We address two of these gaps: the absence of social behavior and the lack of mechanisms for inter-agent coordination. We introduce Epistemic Probabilistic Language Agents (EPLA), a neuro-symbolic architecture for multi-agent coordination under uncertainty. A Symbolic Guard provides structured diagnostic feedback. The LLM generates typed actions, and the Guard controls their execution against an authoritative symbolic state. We formalize the epistemic layer in a gossip testbed through epistemic lottery gossip models, which combine view-based call histories with agent-indexed 

---

### [44] Design and Evaluation of LLM Chaining-Based Task Planning for General Purpose Service Robots

**链接**: https://arxiv.org/abs/2609.29043
**作者**: Lucas Da Mota Bruno, Jiahao Sim, Yoshinobu Hagiwara
**来源**: cs.RO cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> General Purpose Service Robot (GPSR) tasks, as defined in the RoboCup@Home benchmark, require robots to interpret diverse natural language commands and generate multi-step action sequences in real home environments. Conventional Single Prompt (SP) approaches suffer from context bloat and the "Lost in the Middle" phenomenon, leading to unreliable task planning. We propose an LLM chaining architecture that separates instruction classification and action generation into two specialized stages, reducing per-inference prompt length by approximately 45% while improving planning consistency. We evaluate our method using 100 randomly generated GPSR commands across three language models spanning local open-source and frontier cloud deployment contexts. Results show consistent planning improvements over SP across all models, with gains of up to +37 percentage points on local models. Further, real-robot execution experiments on the Toyota Human Support Robot (HSR) reveal that planning success alo

---

### [45] MultiwayPAM: Multiway Partitioning Around Medoids for LLM-as-a-Judge Score Analysis

**链接**: https://arxiv.org/abs/2603.10287
**作者**: Chihiro Watanabe, Jingyu Sun
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] When Fancy Eviction Fails: Rethinking Cache Replacement For LLM Prefix Reuse

**链接**: https://arxiv.org/abs/2609.28870
**作者**: Yiyu Liu, Minlan Yu, Juncheng Yang
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM applications repeatedly send growing context, making prefix caching critical for reducing prefill cost. Yet prefix-cache behavior under agentic workloads remains poorly understood. We study production traces from two companies and evaluate 14 eviction algorithms across HBM-constrained and large memory-pool settings. Despite a large gap to Belady, sophisticated policies designed for traditional caches provide little benefit over LRU. The reason is structural: prefix reuse is dominated by the regular pacing of active sessions, making recency unusually predictive. Prefix caching nevertheless introduces new challenges, including heavy-tailed session footprints and highly variable miss costs as attention computation grows with sequence length. We introduce the compute-savings ratio and two offline oracles to quantify these effects. Our results show that effective prefix-cache management should retain recency as its foundation while selectively adding quick demotion for one-

---

### [47] Exploring a Single Autoregressive LLM for Unified Target Speech Extraction across Synchronous and Asynchronous Cues

**链接**: https://arxiv.org/abs/2609.29238
**作者**: Wenxuan Wu, Shuhan Zhang, Shuai Wang, Haizhou Li
**来源**: cs.SD cs.MM eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Target speech extraction (TSE) typically trains a separate extractor per cue, and visual-cue systems often need corruption-matched training to remain robust under visual frame corruption. We show that one autoregressive LLM backbone, TSE-Omni, can serve both temporally synchronous cues (lip movements, co-speech gestures) and asynchronous cues (enrollment audio, text). TSE-Omni is driven by next-token prediction: each step predicts target speech semantic tokens from its own past outputs, which we term self-enrollment, forming a continuous target-speech context initialized by the enrollment cue (asynchronous audio or text, or a short visual prefix). This enables audio-visual compensation: the model uses synchronized visuals when intact and its token history when visual frames are missing. Under clean visuals, TSE-Omni matches strong discriminative and generative baselines (SpeechBERTScore 0.81 on VoxCeleb2 and 0.89 on LRS3 zero-shot) with higher DNSMOS. On the same VoxCeleb2 test set, af

---

### [48] BLADE: Distilled LLM Regularization for Calibrated Knowledge Graph Completion

**链接**: https://arxiv.org/abs/2609.29487
**作者**: Ibne Farabi Shihab, Rabeya Bosri Tamanna, Abdo El Karaky, Sanjeda Akter, Anuj Sharma
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graph completion models optimize ranking, although many downstream applications require calibrated probabilities. We present BLADE, a variational model that separates latent truth from graph recording and distills offline language-model judgments into a frozen teacher regularizer. The LLM is absent during inference. Posterior samples provide predictive probabilities and epistemic uncertainty, while the compact teacher remains available only as an optional triage factor. Across five benchmarks, BLADE remains competitive under a common ranking protocol and reduces adaptive ECE by a macro-average of 60.1% relative to deep ensembles and 78.1% relative to temperature-scaled RotatE. On identical FB15k-237 candidate sets, BLADE also improves ECE, Brier score, and NLL over validation-selected histogram binning and a matched generative ComplEx2 model, with these improvements persisting on a prespecified near-miss pool. Under controlled injected missingness, the full triage score achie

---

### [49] Where Cyber Agents Struggle: Bottleneck Analysis of Multi-Stage LLM Agents

**链接**: https://arxiv.org/abs/2609.28572
**作者**: Saeedeh Lohrasbi, Mohammad Mamun, Ahmed Yehia, Scott Buffett, and Sherif Saad
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-stage LLM-based cyber agents may complete attack workflows while remaining brittle, costly, or reliant on incorrect interpretations of execution evidence. Success rates alone obscure inefficiency, adaptation through retries, and recognition of success or failure. We present an end-to-end diagnostic study of an Autonomous Adversary system with orchestrator, executor, and validator LLMs in enterprise-like lateral-movement scenarios. Six frontier models are evaluated across two scenarios and three modes: expert-defined, self-scaffolded, and fully autonomous. We assess validator consistency and evidence grounding; introduce a subtask-conditioned, cost-aware score for abnormal token use, retries, and runtime; and use comparative LLM-as-a-Judge analysis to identify planning deficiencies, including tool misalignment, plan similarity, over-specification, inadequate probing, and weak recovery. Validators are generally relevant and evidence-grounded but often nonspecific and overly optimis

---

### [50] Fair Like Us? Auditing LLM Alignment in Resource Allocation

**链接**: https://arxiv.org/abs/2609.29692
**作者**: Qishen Han, Hadi Hosseini, Joshua Kavner, Samarth Khanna, Sujoy Sikdar, Lirong Xia
**来源**: cs.AI cs.CY cs.GT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fair allocation of scarce, indivisible resources is an important challenge in many societal problems. While there are several formal theories of fairness, no single definition can always be satisfied. As large language models (LLMs) are increasingly used to support decisions and act as agents, they raise new concerns about distributional justice: their judgments are not directly tied to any specific fairness framework and may violate key normative principles. In this work, we introduce a general method for evaluating fairness reasoning in LLMs. We study first-person fairness judgments across a broad set of models and compare them directly with human responses on matched scenarios and elicitation conditions. We find that LLMs tend to prefer stricter fairness constraints than humans, show more self-interested behavior, are sensitive to how information is framed, and are difficult to align with human judgments using fine-tuning with current datasets.

---

### [51] Encoded but Not Decoded: Layer-Localized Evidence for a Three-Level Gap in LLM Syntax

**链接**: https://arxiv.org/abs/2609.29848
**作者**: Zhenyan Lu, He Wang, Xiaohui Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A language model can fail a syntactic test in two distinct ways: by not encoding the relevant structure, or by encoding it but failing to use it at the output. Behavioral evaluation alone cannot tell these apart. We propose a three-level evaluation framework (behavioral deployment, LM-head readout, and probe recoverability) measured on the same items under the same binary decision. Using a compact trilingual (English, Chinese, German) control-dependency benchmark, we find that probe recoverability exceeds or equals LM-head readout, which in turn exceeds or equals behavioral deployment, across seven models and all three languages in the aggregate. The recoverability surplus is never negative across all 14 (model, task) conditions. The disconnect concentrates in subject-control, where a nearest-noun heuristic gives the wrong answer. The single largest gap (0.653) appears on Qwen3-0.6B Instruct in question answering. The gap persists at Qwen3-14B Instruct. Instruction tuning degrades depl

---

### [52] Free the Language Model From the Vision Encoder: Semantic Serialization as a Perception Interface for Small Language Models

**链接**: https://arxiv.org/abs/2609.29601
**作者**: Cong Xu and Ravi Sankar
**来源**: cs.RO cs.CL cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> End-to-end vision-language models (VLMs) bind visual competence to the scale of their language model: as the language model shrinks, perception and reasoning degrade together. We study an embodied scene question-answering (QA) interface in which vision never enters the language model. A frozen perception stack detects and ranges objects; a deterministic semantic serializer compiles the perceived state, errors included, into decision-aligned text; an unmodified text-only large language model (LLM) answers. On a visible-scope-matched, occlusion-audited campus-robot benchmark, under a prospectively frozen criterion, the serialized interface, using detectors fine-tuned in-domain within each fold, outperforms a zero-shot VLM whose language model has the same 7B scale (0.7892 vs 0.7462), with a larger margin at 3B (0.7673 vs 0.6913). Preregistered decoupling experiments show the gain survives paraphrase, attributing it to decision-aligned computation rather than answer-string leakage, while 

---

### [53] Beyond Average Safety: Chance-Constrained LLM Fine-tuning

**链接**: https://arxiv.org/abs/2609.29960
**作者**: Taha Entesari and Mahyar Fazlyab
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuning large language models on new objectives can improve helpfulness, instruction following, or domain-specific performance, but it can also induce regressions on safety-critical prompts. Existing safety-preserving fine-tuning methods typically control average safety loss or use weighted auxiliary penalties, which can obscure rare but severe failures. We propose a chance-constrained formulation for safety-preserving fine-tuning that limits the fraction of safety examples whose degradation relative to a reference model exceeds a prescribed threshold. Because the resulting empirical chance constraint contains a discontinuous indicator, we introduce a differentiable majorization of the violation rate, yielding a tractable conservative constraint. We then develop a constraint-aware gradient descent method that treats the majorized constraint as a safe set in parameter space and minimally modifies the fine-tuning direction to preserve feasibility. The resulting update admits a closed

---

### [54] Measuring Brand and Source Discovery under Repeated LLM Queries: A Finite-Sample Audit

**链接**: https://arxiv.org/abs/2609.05059
**作者**: Dmitrij \.Zatuchin
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] NumericJev: Jev-like LLM Numerical Decoding with Multiway Decision Trees

**链接**: https://arxiv.org/abs/2609.28587
**作者**: Weiwei Ye, Hangchen Liu, Renhe Jiang
**来源**: stat.ML cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can interpret natural lan- guage, yet robust decisions remain challenging. Jev-like models expose structured choices, but these interfaces do not directly provide numeri- cal values at a requested precision. We propose NUMERICJEV, a training-free numerical decod- ing algorithm that enables numerical output from any LLM with a Jev-like structured-choice in- terface. Surprisingly, on our arithmetic bench- mark, it outperforms direct selection from a can- didate list containing the correct answer by 2.93 percentage points (Figure 1). Our motivation comes from the observation that numerical range selection is itself a decision problem that Jev- like LLMs can address. NUMERICJEV recur- sively refines a range through a multiway deci- sion tree while retaining the original question in context, without parameter updates or hidden- state access. On a 100-value grid, a ten-way tree requires only two decision rounds. Range- normalized MAE is 1.84% versus 5.18% for di- rect c

---

### [56] SPARQL-LLM: Real-Time SPARQL Query Generation from Natural Language Questions

**链接**: https://arxiv.org/abs/2512.14277
**作者**: Panayiotis Smeros, Vincent Emonet, Ruijie Wang, Ana-Claudia Sima, Tarcisio Mendes de Farias
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] MeshHeal: Two-Timescale Self-Healing for Gray Failures in Decentralized LLM Agent Networks

**链接**: https://arxiv.org/abs/2609.29015
**作者**: Keru Chen, Sen Lin, Yingbin Liang, Nathaniel D. Bastian, Shaofeng Zou
**来源**: cs.AI cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decentralized LLM-based multi-agent systems coordinate through local interactions, but an agent can remain responsive while its task-solving quality persistently degrades. Such gray failures require protecting current tasks before sufficient evidence exists to alter future routing, while still allowing recovered agents to rejoin. We introduce MeshHeal, a fully decentralized self-healing framework that couples ability-matched peer review across two timescales. At the fast timescale, an adaptive hierarchy escalates uncertain or low-scoring outputs from repeated single-reviewer evaluation to committee deliberation and, when needed, correction before use. At the slow timescale, a task- and ability-conditioned peer-relative detector aggregates scores to distinguish persistent degradation from ordinary output variation, trigger mandatory committee review, and eventually exclude degraded agents from ordinary routing; recovery probes provide fresh evidence for reintegration. To faithfully eval

---

### [58] Rufus-Air: An Open LLM Post-Training Recipe

**链接**: https://arxiv.org/abs/2609.29421
**作者**: Chia-Yuan Chang, Renyuan Cheng, Rui Feng, Xiaotian Han, Yuan He, Hongye Jin 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rufus-Air is an open and reproducible post-training recipe on GLM-4.5-Air-Base (106B-A12B), organized as a serial pipeline of eight stages: SFT, Reasoning RL, Coding RL, Instruction-Following RL, General Agent, Coding Agent, Search Agent, and RLHF. We document the data, reward design, infrastructure, stage order, and stagewise results needed to reproduce the recipe. Stages progress from basic to advanced capabilities and from hard, verifiable rewards to softer judge-based signals. Training builds on open-source components and public data, much of it used as released, without new human annotation or an in-house distillation teacher. Our main findings are that (i) diverse, high-quality SFT establishes a strong capability floor; (ii) difficulty filtering keeps RL prompts within a productive learning range; (iii) reward reliability provides a practical principle for ordering stages; and (iv) infrastructure and engineering choices are part of the recipe, not just an implementation detail. R

---

### [59] Characterizing LLM-Based Family Education through the Lens of Activity Theory: A Scoping Review of the HCI Literature

**链接**: https://arxiv.org/abs/2609.28886
**作者**: Lan Luo, Yuqi Liang, Jie Cai, Anqi Wang, Dongyijie Pan, Muzhi Zhou 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly involved in family education, yet HCI has not systematically explained the educational interactions that emerge around them. This scoping review analyzes 53 HCI studies from 6,540 records across 19 venues. Using activity theory and AODM, it relates participants and educational objects to mediation, labour, and rules. We find that the literature centers on child--parent interaction and on language, AI literacy, and relational learning. The introduction of LLMs enabled conversational, embodied, and spatial systems to generate support from the context of an unfolding interaction. LLMs redistributed educational labour, while family and institutional rules left parents and professionals responsible for interpreting outputs and deciding how they entered practice. Evidence across families and educational purposes remains limited, especially on sustained personalization, repair labour, and how families negotiate authority and rules. The review offe

---

### [60] Persistent Billable State: Denial-of-Wallet Attacks and Defenses in Tool-Calling LLM Agents

**链接**: https://arxiv.org/abs/2609.28585
**作者**: Jinqian Zhang (1 and 2), Haojun Xia (1 and 2), Shujiang Wu (3), Jingkun Yue (4), Xia Zhang (1 and 2), Zhangpei Cheng (1 and 2) 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-step tool-calling LLM agents rely on host runtimes to preserve state across turns. When a runtime carries an external tool return into later model inputs, providers meter it again. An admitted malicious or compromised tool can thereby convert untrusted data into recurring victim-billed processing without victim credentials or local runtime privilege. We call retained content persistent billable state and formalize the host's decision over whether and how it enters later billable context as the persistent billable-state boundary. We present the first systematic security study of this post-admission lifecycle. We derive six denial-of-wallet attack vectors and build DOW-BENCH, an end-to-end harness evaluated across six model families. Across 243 executions, usage telemetry shows that the maximum per-session cumulative input reaches 14,293x the session's first-call input. Controlled history-policy reruns isolate raw retention's contribution: retaining raw history increases mean effec

---

### [61] Who Is Behind the Harness? Fingerprinting LLMs through Agentic Behavior

**链接**: https://arxiv.org/abs/2609.28559
**作者**: Chuyi Wang, Xiaohui Xie, Tongze Wang, Fangchen Luo, Yong Cui
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs increasingly operate through coding-agent harnesses that inspect repositories, invoke tools, and modify files. Substituting the model behind such an agent can therefore change security-relevant decisions, including whether it verifies changes or recovers safely from failures. Existing LLM fingerprints largely infer identity from direct text or token distributions. In coding agents, these signals are mediated by system instructions, controller logic, tools, and execution feedback, limiting their transfer. We present LIDAR (LLM Identification from Decisions and Actions at Runtime), an active black-box fingerprinting method for coding-agent execution. Three coding probe pairs expose post-edit verification, transient-failure recovery, and specification--test conflict resolution under controlled changes. LIDAR represents the resulting trajectories with complementary instance-level and distribution-level features and compares them with clean references using a lightweight probabilistic 

---

### [62] On the Effectiveness of Kernel-Level Evidence for Agent Security

**链接**: https://arxiv.org/abs/2609.28915
**作者**: Spencer King, Zhilu Zhang, Mikhail Kuznetsov, Kay Liu, Baris Coskun, Wei Ding
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are deployed into infrastructure that grants them broad host authority, yet existing agent-security benchmarks and defenses operate almost exclusively at the application telemetry layer: the served tool manifest, the user prompt, and the model's messages. Some threats, however, smuggle malicious instructions and actions past the application boundary, leaving them invisible to that layer. In this work, we bridge that gap by pairing application-level agent telemetry with kernel-level syscall traces to present the first paired-evidence characterization of kernel-level versus application-layer signal for agent security. To quantify the value of the enhanced telemetry, we introduce Agent Cross-Layer Evidence (ACE), a paired-session corpus of 4,047 sessions and 17 threat models spanning six delivery-vector families and 14 of the 25 OWASP LLM and agentic threat categories, organized into 12 attack mechanics with per-mechanic characterization of where the most discriminative evidenc

---

### [63] Don't Read the Log: Execution Traces Contaminate Verifiers in Video-Generation Agents

**链接**: https://arxiv.org/abs/2609.28564
**作者**: Jian Xu
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic video-generation systems close a loop between a generator and a verifier: an LLM plans shots, calls a text-to-video model, and a multimodal judge decides whether the result satisfies the request. To diagnose where a long workflow fails, recent harnesses deliberately show the judge more than the video-the agent's execution trace, its plan, the narration it synthesized. We ask whether this auxiliary text moves the judge's verdict on purely \emph{visual} requirements, holding the frames fixed. On a benchmark of 109 generated two-event clips with manual labels, in which the requested event is either visibly completed or visibly missing, a trace that reports a successful tool call makes three open-weight Qwen-VL judges (7B, 8B, 32B) accept $78$--$90\%$ of the failures, up from $7$--$19\%$ without text, and a contradicting trace makes them reject up to $100\%$ of correct clips; an instruction to ``use only the frames'' does not remove the effect. Frontier closed judges are essentiall

---

### [64] Med-AR: Autoregressive Vision-Language Pretraining for Long-Tailed Chest X-Ray Classification and Uncertainty-Aware Evaluation

**链接**: https://arxiv.org/abs/2609.29156
**作者**: Janhavi Prabhu, Sahil, Akshay V, Shivam Shukla, Manoj Tadepalli, and Preetham Putha
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-tailed chest X-ray classification requires visual representations that capture both common abnormalities and subtle, infrequent findings. We propose Med-AR-8B and Med-AR-2B, two radiology-native autoregressive vision-language models pretrained with structured reports, abnormality-focused text, and region annotations. We evaluate the transfer of their visual encoders to multi-label classification against contrastive, self-supervised, and supervised pretrained encoders, including Med-CLIP, CheXFound, EVA-Base, ARK, and BioViL-T, using a common ML-Decoder classification head. To assess fine-grained recognition, we also construct LLM-expanded, report-derived label sets for MIMIC-CXR and CheXpert. Across PadChest, MIMIC-CXR, and CheXpert, Med-AR-8B outperforms Med-CLIP in mean AUROC and AUPRC for head, medium, and tail findings. On MIMIC-CXR, it increases tail-label mean AUPRC from 0.1033 to 0.1441. Med-AR-2B achieves the strongest discrimination results on PadChest. Across the broader

---

### [65] Let Training Guide Selection: Online Synthetic Data Filtering via Real-Anchored Utility

**链接**: https://arxiv.org/abs/2609.29988
**作者**: Yanran Wu, Sana Lakdawala, Renzo Tassara Miller, Chongyang Bai, Sharath Ciddu, Shivendra Pratap Singh 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic data can scale training supervision when real-world data are limited, but noise and distribution mismatch can reduce its value. Existing synthetic data selection methods often emphasize fidelity or diversity rather than the learner's evolving needs. We propose FROST, an online framework that estimates synthetic-data utility through gradient feedback anchored in real training data. It calibrates batch utility against recent history to determine when filtering is needed and filters samples only in out-of-band batches to determine what to retain, without an external verifier or held-out validation set. Experiments on two public benchmarks for image classification and LLM fine-tuning for text-to-SQL show that FROST filters out around 20--30% of the synthetic data while improving real-task performance compared with training on the full synthetic data pool. We further apply FROST during training in a large-scale industrial ads re-ranking system, achieving significant performance ga

---

### [66] SWE-Prometheus: Measuring Engineering Governance Improvements in Real-World Repositories

**链接**: https://arxiv.org/abs/2609.29465
**作者**: Jiajun Wu, Leixin Sun, Zihan Tan, Yitao Liu, Shuo Li, Jiaru Qian 等 (10 人)
**来源**: cs.AI cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model based coding agents have made substantial progress on repository-level software engineering tasks. Existing repository benchmarks, however, usually start from a human-identified issue and evaluate whether a patch satisfies a functional signal. We present SWE-Prometheus, a benchmark for the broader task of improving repository engineering governance. Each task provides a fixed snapshot and an open-ended objective, requiring the agent to identify risks, prioritize interventions, and verify the resulting changes. SWE-Prometheus evaluates six governance dimensions through paired evidence, clean-environment probes, behavior gates, and two independent teacher ratings of the same evidence. The benchmark contains 60 repositories; ten models are evaluated on a shared 22-repository public subset, where mean Normalized Governance Improvement ranges from 0.0568 to 0.5760 and observed behavior-breakage rates range from 0% to 23%. On a frozen ten-repository batch, a repository-b

---

### [67] IterSynth: Rethinking Deep Search Agents via Role-Decoupled Iterative Synthesis

**链接**: https://arxiv.org/abs/2609.29444
**作者**: Xingyu Wu, Yuchen Yan, Zhengxi Lu, Siqi Chen, Xin ZHANG, Aiting Liu 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep search requires LLM agents to decompose complex queries, search for evidence, and synthesize grounded answers, yet existing ReAct-style agents suffer from two limitations: role coupling, where one policy must handle planning, evidence use, and synthesis; and context accumulation, where growing search histories introduce noise and obscure useful information. To address these issues, we propose IterSynth, a role-decoupled and summary-based paradigm that alternates between a Planner for identifying information needs and a Synthesizer for integrating evidence into an evolving summary state. This design separates planning from synthesis while using the summary as the persistent state of search, reducing both capability coupling and context noise. To train IterSynth effectively, we further introduce Role-Decoupled Policy Optimization (RDPO) for reinforcement learning, which combines terminal outcome rewards with turn-level rubric evaluations and computes role-specific advantages for mor

---

### [68] How does Adversarial Influence Scale in Multi-Agent Systems?

**链接**: https://arxiv.org/abs/2609.30028
**作者**: Addison J. Wu, Jasin Cekinmez, Michel Liao, Karthik Narasimhan, Thomas L. Griffiths
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent deliberation can improve performance, but what happens when some agents do not act in good faith? In practice, an agent may be deceptive and work to subvert the group, whether through its own objectives or external instruction. We study how susceptibility to deception scales as groups increase in size and deceivers become more prevalent. It is not the number of agents in the group that matters, but the proportion of deceivers. We observe that the defection rate, how often initially correct agents switch to an incorrect final answer, rises linearly with this proportion. Whereas humans in comparable conformity studies are reliably swayed only when misleading confederates form a majority, LLM agents defect regularly even when deceivers remain a minority. Susceptibility also depends on which models are interacting, especially on the honest agent side. Unexpectedly, allowing deceivers to coordinate privately can make them less effective. Altogether, our results show that adding 

---

### [69] Framing by Wording, Framing by Selection: A Large-Scale Two-Dimensional Audit of French News Headlines, 2022-2025

**链接**: https://arxiv.org/abs/2609.28487
**作者**: Amr Sobhy
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> News headlines frame public issues both by what they select and by how they word it, yet computational framing work typically collapses these operations into a single score. We introduce a two-dimensional framework that separates salience framing, measured through four wording devices (loaded vocabulary, blame attribution, threat framing, rhetorical question), from selection framing, measured through outlet-level story-form and high-charge distributions. We build a 10,000-headline French supervision set using three LLM annotators with majority-vote resolution and human arbitration, validate the labels against two annotator-independent blind human studies, and apply the strongest classifier to 902,111 deduplicated headlines from 25 French outlets (2022-2025). Three main findings emerge. First, salience and selection divergence are positively correlated yet leave nearly half of outlet-level variance unexplained, populating interpretively distinct off-diagonal cells in a four-cell outlet 

---

### [70] Where Hallucinations Live: A Cross-Architecture Circuit in VQ-Tokenized Vision-Language Models

**链接**: https://arxiv.org/abs/2609.29048
**作者**: Shamanthak Hegde, Xiangrui Liu, Maitreya Patel, Yezhou Yang
**来源**: cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified vision-language models (VLMs) that tokenize images through a vector-quantized (VQ) codebook routinely hallucinate objects on grounded yes/no benchmarks, yet existing decoding-time fixes treat this as generic miscalibration without an architectural account. Using activation patching across twenty-five models spanning eight LLM families, we identify an early-layer ($L_0$) attention routing circuit shared across VQ-tokenized VLMs and propose a three-gate diagnostic that distinguishes the models carrying it from those that do not. The diagnostic isolates ten positive models (five natural unified-VQ VLMs across three LLM families and five induced variants) and rejects the remaining fifteen. A single-variable architectural swap (LLaVA-1.6 CLIP+MLP $\rightarrow$ VQ+Linear) installs the circuit, while a matched-compute MLP control on identical data does not, isolating vector quantization as the source of the pathological signal; the routing pathway that carries it is one that the backb

---

### [71] From Policy Documents to Structured Survey Responses: Evaluating Large Language Models for Policy Monitoring

**链接**: https://arxiv.org/abs/2609.29370
**作者**: Carolyn Cole, Matthias Deschryvere, Toqeer Ehsan, Arash Hajikhani
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Science, technology, and innovation policies are crucial for competitiveness, yet their diversity and scale make them difficult to map and monitor consistently. Existing approaches rely heavily on manual survey efforts, which are costly and challenging to scale across countries. Large language models (LLMs) enable new possibilities for extracting and structuring information from long and unstructured policy documents. This paper presents an application of LLMs as "AI respondents" for generating structured survey responses from policy texts. We develop a data extraction pipeline based on long-context in-context learning to map information from public web sources into predefined survey categories, including policy instruments, target groups, and thematic areas. The pipeline integrates a validation step using a secondary LLM to assess relevance and evidence, alongside comparisons with human-provided responses. Using a multi-country dataset, we evaluate the alignment between LLM-generated 

---

### [72] PartHackBench: Certified Equal-Progress Stress Tests for Partial-Credit Tool-Agent Evaluation

**链接**: https://arxiv.org/abs/2609.29578
**作者**: Hongye Yang, Zhihao Xie and Shengjun Xiong
**来源**: cs.AI cs.CL cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon tool agents often make useful progress without reaching terminal success, motivating partial-credit evaluation. Yet evaluators may reward milestones that were temporary, later reversed, or not attributable to the evaluated agent. Comparing an honest trajectory with a higher-scoring adversarial one is inconclusive if the latter made more genuine progress. We introduce PartHackBench, a controlled methodology that removes this confound. A private certifier admits a pair only when its trajectories match component-wise in both current-state predicate satisfaction and standardized agent attribution; score inflation, defined as f(A) - f(H), is measured only afterward. In 18 sealed held-out tasks in PB-CSTE, the frozen historical-target run produced matched adversaries for 15 tasks. Historical credit yielded mean inflation of .252, conditional attack success of 10/15, end-to-end yield of 10/18, and detected none of 14 strict rollbacks. Semantic LLM judges were more resistant but r

---

### [73] SkinAgent AI: A Safety-Grounded Multimodal Agentic Framework for Non-Diagnostic Skincare Support

**链接**: https://arxiv.org/abs/2609.29341
**作者**: Muhammad Muhtasim Shahriar, Abdullah Mohammad Sayem, Tze Hui Liew, M. F. Mridha, and Md. Mahiuddin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Consumer-facing skincare AI must coordinate visual evidence, product information, tool use, and user-facing actions within explicit evidence and safety boundaries. This study evaluates SkinAgent AI, a non-diagnostic multimodal framework that combines visual concern routing with grounded and auditable LLM-based orchestration. The architecture includes routing for Acne, Pores, and Wrinkles; photograph-based skin-type estimation; count-informed ordinal acne-severity support; typed tools; database-grounded recommendation and action functions; deterministic safety, privacy, and evidence checks; approval before state-changing actions; and structured trace and replay mechanisms. Visual-model performance and system-level agent behavior were evaluated separately. Across three seeds, the skin-condition routing model achieved 99.84% +/- 0.07% accuracy. Skin-type estimation achieved 88.85% accuracy, while count-informed acne-severity support achieved 84.59% accuracy with a quadratic weighted kappa

---

### [74] KernelOPT: Dispatch-Aware Agentic Search for GPU Kernel Optimization

**链接**: https://arxiv.org/abs/2609.30059
**作者**: Aheli Poddar, Sanskar Prasad, Arindam Samanta, Subha Chakraborty, Vishal Goyal, Rohit Singh Rathaur
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning inference and training performance depends critically on GPU kernel efficiency. Modern compilers such as PyTorch Inductor automatically generate GPU kernels from high-level model code, but frequently underperform expert-written implementations by wide margins. Recent LLM-assisted kernel optimizers can close this gap for standalone kernels, yet treat compiled models as black boxes, generally optimizing individual standalone kernels without respecting the compiler's structural decisions or verifying the model end-to-end. We present KernelOPT, a multi-agent system that treats compiled models as structured artifacts. It preserves vendor library calls (cuBLAS, cuDNN) and exclusively targets generated Triton sub-kernels using five profiling-guided LLM agents. A four-gate verification cascade of static validation, multi-seed correctness, model-level float64-fallback verification, and performance gating filters candidates during optimization and verifies the re-stitched model end

---

### [75] Benchmarking Argumentative Behaviour of LLMs: A Study of Defences Against Character Attacks

**链接**: https://arxiv.org/abs/2609.28673
**作者**: Ewelina Gajewska, Katarzyna Budzynska, Jaroslaw Chudziak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed as argumentative agents in persuasive dialogues, necessitating rigorous evaluation of their debating competence relative to human interlocutors. In this study, we focus on character attacks (ad hominem arguments), traditionally dismissed as fallacies, which play a pivotal role in political persuasive dialogues where ethos often rivals propositional content. Specifically, we investigate whether modern LLMs can replicate human competence to strategically use and respond to such attacks. We analyse a corpus of natural language political dialogues to identify defensive strategies human interlocutors naturally employ in ethos-centred debates and structure them into a dialogue game. Empirically, we benchmark LLM-generated dialogues against the ElecDeb60to16-fallacy corpus of U.S. presidential debates, contrasting human debaters' repertoire of defensive strategies with those of artificial agents. Results reveal a substantial difference: m

---

### [76] Codetta: High-Capacity, Keyless, and Undetectable Multi-Agent Collusion

**链接**: https://arxiv.org/abs/2609.28900
**作者**: Qi Pang, Virginia Smith, Wenting Zheng
**来源**: cs.CR cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems built on large language models (LLMs) are increasingly deployed in high-stakes settings such as finance, healthcare, and software engineering, where agents coordinate through natural-language messages. The same channels, however, let colluding agents exfiltrate confidential information or coordinate unauthorized actions, and steganography can hide such communication inside outputs that look ordinary to an auditor reading the transcript. Existing provably undetectable LLM steganography protocols are not suited to realistic deployments. High-capacity schemes assume a symmetric setting where the receiver can reproduce the sender's output distribution, the state-of-the-art protocol for asymmetric agents has very low capacity, and most approaches rely on a pre-shared secret key. We make the threat of undetectable agent collusion concrete with Codetta, a high-capacity steganographic protocol for independently deployed agents in realistic asymmetric settings. Codetta combi

---

### [77] agentic-ger: terminology recovery in long-form speech using global context

**链接**: https://arxiv.org/abs/2609.29428
**作者**: Yanqiao Zhu, Wupeng Wang, Zhifu Gao, Xiangang Li, Xie Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in speech language models have improved automatic speech recognition (ASR) for long-form audio. However, accurately and consistently transcribing domain-specific terminology remains challenging. Motivated by the world knowledge and contextual capability of large language models (LLMs), we propose Agentic-GER, an LLM-based agent for terminology correction in long-form speech. The agent uses global context from the full transcript to identify suspicious terms and resolve ambiguous hypotheses. It selectively re-transcribes the source speech to check candidate corrections, and uses accepted edits to guide subsequent decisions. Experiments with four LLMs and two ASR systems on GigaSpeechBench show consistent terminology improvements in both Chinese and English, with and without thinking. On Chinese speech, Agentic-GER achieves up to a 36.8% relative reduction in biased character error rate (B-CER) over the Whisper baseline.

---

### [78] HiPACE: Hierarchical Phase-Boundary Analysis and Controlled Evaluation of Feature Absorption in Sparse Autoencoders

**链接**: https://arxiv.org/abs/2609.29551
**作者**: Jinyuan Zhang, Peng He, Yin Yuan, He Hu, ShengShuo Jiao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) decompose LLM activations into sparse dictionary atoms, so that each distinct concept gets its own feature. One recurring behavior complicates this premise: feature absorption, in which a parent concept and its children--fruit and {apple, banana, pear}, say--collapse into a shared family direction. Prior work documents absorption empirically; missing is a closed-form prediction of when the shared direction is the cost-optimal representation of an active semantic family. This paper closes that gap. For a hierarchical Bernoulli generator with $k$ active children and residual scale $\alpha$, the $L_0$-penalized reconstruction objective admits a closed-form phase boundary $\lambda_c(k,\alpha)=\alpha^2 k/(k-1)$: above it, pure parent absorption is strictly cheaper than pure child coding. Building on this boundary, we introduce HiPACE, an evaluation protocol that tests the boundary's structural consequence in real SAE dictionaries--measuring parent--child decoder s

---

### [79] Signals of AI Hallucination: Designing Hallucination-Aware Cues for Embodied Conversational Agents in VR

**链接**: https://arxiv.org/abs/2609.28812
**作者**: Xiaoran Yang, Yang Zhan, Xie He, Yuxuan Huang, Yichen Yu, Zhuo Wang 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered conversational agents (CAs) often present uncertainty and provenance cues alongside their responses to help users assess response reliability and identify potential hallucinations. In immersive environments such as Virtual Reality (VR), CAs often take the form of speech-based embodied conversational agents (ECAs), where uncertainty and provenance cues cannot rely on persistent inline text and may be missed or disrupt comprehension when delivered through speech. We conducted a within-subjects study (N = 24) to compare three designs for presenting the hallucination-awareness information (uncertainty and provenance) in ECAs in VR against a no-cue baseline: embodied cues using gestures and posture, icon cues using visual indicators, and text cues using color-coded text with inline citations. We evaluated how these designs affect users' ability to identify hallucination-related information, trust in the ECA, and interaction experience (immersion and task load). Our results show 

---

### [80] ARGUS: Role-Aware Event Knowledge Graphs for U.S. Employment-Discrimination Complaints

**链接**: https://arxiv.org/abs/2609.30184
**作者**: Sriram Kannan, Swetha Saseendran, Vishnu Vardhan Reddy Kandi, Leslie Barrett, Madhavan Seshadri, Enrico Santus
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> U.S. employment-discrimination complaints describe complex event sequences that are not explicitly captured by lexical or embedding-based representations alone. We present ARGUS, a source-grounded pipeline that combines a 5W1H-inspired schema, legal-domain models, and LLM-based structured generation to construct document-level Event Knowledge Graphs (EKGs) from CourtListener complaints. ARGUS extracts fact-bearing statements, builds chunk-level event graphs with participant, temporal, and causal structure, and merges them into document-level representations. We evaluate graph quality through human and multi-model assessment and test downstream utility on claim classification and legal QA. The graph-structured classifier outperforms raw and linearized baselines on the held-out set, and EKG-only retrieval improves document-scoped QA, while open-retrieval gains remain limited by low first-stage candidate recall. These results suggest that EKGs are most useful for organizing and reasoning 

---

### [81] Large Language Models for Programming: Actually Fixing or Reimplementing Incorrect Code?

**链接**: https://arxiv.org/abs/2609.29410
**作者**: Alexandru Stefan Stoica, Traian Rebedea, Marian Cristian Mihaescu
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies have shown that Large Language Models can effectively solve problems and fix bugs in diverse programming environments, including competitive programming. Existing approaches primarily evaluate LLM performance in problem solving or bug fixing independently, but do not explore the relationship between these two capabilities. This work focuses on determining how much the LLM deviates from a buggy solution to fix the bug compared to a human-written patch, and if there is a bias towards generating entirely new solutions. We construct a dataset with all the submissions ($\sim$ 3000) from a couple of users from Codeforces, and we match each buggy submission with its corresponding human fix. By using the similarity between the buggy solution and the human fix as a baseline, we evaluate the quality of LLM-generated bug fixes on 3 OpenAI GPT models (gpt-5-nano, gpt-5-mini, gpt-5.1). We check if the generated solutions solve the problem by using the Codeforces-R1 dataset, an openly

---

### [82] From Self-Distillation to Self-Practice: Privileged Information for Multi-Turn Agents

**链接**: https://arxiv.org/abs/2609.29051
**作者**: Xingyu Su, Abhishek Kumar, Qing Ping, Youzhi Luo, Jonathan Buck, Zach Zhang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy self-distillation (OPSD) has become a popular recipe for post-training LLM agents. It supervises the agent model at the token level with a stronger teacher view of the same model, obtained by conditioning on privileged information (PI). In this work, we show that in multi-turn agents, this paradigm teaches the student to act with confidence but without the information behind it. The trained agent behaves as if it had privileged information it never observed, and its performance falls well short of plain RL, in the worst case below the untrained base model. Therefore, we propose Privileged Self-Practice (PSP), which keeps the PI and moves it from the loss to the sampler. When the student's rollouts on a task mostly fail, we inject a short per-task instruction written by an analyzer model, sample the task again with the instruction in context, and train on the result with an unchanged GRPO objective. The privileged information stays in the prompt and never enters the loss. Acro

---

### [83] Who Holds the Pen? Let Specifications, Not Agents, Sign Off

**链接**: https://arxiv.org/abs/2609.29921
**作者**: Haiqing Li, Xin Ma, Yinhao Wu, Wenliang Zhong, Feng Jiang, Thao M. Dang 等 (10 人)
**来源**: cs.AI cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly combine generation, decision-making, execution, and self-evaluation within a single agentic loop. Although they operate under external specifications such as task instructions, guidelines, output schemas, and reusable skills, these specifications typically remain context for the same model that acts and declares completion, leaving no independent specification authority boundary. We identify two resulting gaps. The understanding--execution gap arises when a requirement is understood but not satisfied in execution; the state--authority gap arises when an agent's interpretation or completion claim does not establish the required state. On SkillsBench, using only agent-visible prompts, workspace information, and injected skill specifications, we extract 509 source-grounded task directions. Across seven models, only 79.6%--86.4% are satisfied, while completion-claim rates exceed official evaluator pass rates by 28.7--37.9 percentage points. We there

---

### [84] Beneath the Scores: Rethinking Hallucination Evaluation for Video Understanding Models

**链接**: https://arxiv.org/abs/2609.28991
**作者**: Shuzhi Gong, Fengze Sun, Yuansan Liu
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video understanding is increasingly performed by multi-stage LLM agents that separate temporal grounding, visual observation, and reasoning. Yet these stages are typically evaluated on different benchmarks and distributions, making it difficult to determine where hallucinations originate. We first organize existing benchmarks around these stages and show that their scores provide inconsistent diagnostic signals: stronger stage-level performance does not reliably imply lower downstream hallucination, and even benchmarks targeting the same capability can disagree. We therefore introduce a causal stage-intervention protocol that overwrites individual stages while holding the downstream task fixed. Across 60,008 runs on three video-agent architectures, we find that grounding is the dominant source of downstream error, with roughly four times the causal impact of corrupting visual observations. Successful grounding depends primarily on locating the correct region rather than precise tempora

---

### [85] Reward Hacking Challenges Oversight of Autonomous Research Agents

**链接**: https://arxiv.org/abs/2609.28614
**作者**: Yue Huang, Zhangchen Xu, Yuchen Ma, Wenjie Wang, Zheyuan Liu, Ziwei Xu 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous research agents can design experiments, evaluate results, and write reports, giving them control over both a scientific result and the evidence used to support it. This creates a risk of reward hacking: meeting the reward criteria without achieving the intended goal. We study (1) how often models reward-hack without instructions to do so, (2) how effective and detectable their methods are when hacking is allowed, and (3) how they adapt when an LLM review panel returns its decision and reasons. Across 17 language models and 38 tasks, the spontaneous reward-hacking rate is 30.5% on open-ended research-pipeline tasks and 2.9% on task-specific kernels. When hacking is allowed on tasks whose pass thresholds exceed our best compliant baselines, 505/677 attempts (74.6%) are confirmed reward hacks: they both clear the threshold and receive mechanism-verification panel confirmation of an evaluation exploit. An LLM panel reviewing only submitted code and reported scores misses 33/505 

---

### [86] Spooftral: Can Voxtral Audio-Language Model Detect Speech Spoofing?

**链接**: https://arxiv.org/abs/2609.28713
**作者**: Avishai Weizman, Yehuda Ben-Shimol, Itshak Lapidot
**来源**: eess.AS cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised learning (SSL) countermeasures (CMs) have shown strong performance in recent years. However, they often show degraded performance while facing unseen spoofing attacks and mismatched conditions. This study examines the Voxtral audio-language model (ALM) framework for spoofing detection, as a step toward combining CM capabilities within the ALM framework. We analyze how Voxtral captures spoofing cues through audio-text processing and propose an instruction-guided approach that uses label-sequence likelihoods to evaluate bonafide and spoofed speech. Experiments on the ASVspoof databases show that without task-specific adaptation, the LLM layers emphasize semantic representations, reducing the separability of spoof-discriminative acoustic cues compared to the Whisper-based audio encoder. Consequently, spoofing-related information becomes less separable after language-model processing. We also applied lightweight adaptation using weight-decomposed low-rank adaptation (DoRA) 

---

### [87] Benchmarking Arabic--Russian Machine Translation: A Comparison of Fine-tuned NMT and Few-shot LLMs under Rich Morphology and Low Lexical Overlap

**链接**: https://arxiv.org/abs/2609.29559
**作者**: Mullosharaf K. Arabov
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Arabic-Russian machine translation (MT) remains under-explored due to the rich morphology of Arabic and low lexical overlap between the two languages. We benchmark seven fine-tuned neural machine translation (NMT) models against four few-shot large language models (LLMs) on a 20k/5k/5k split of a new 15.47M-pair corpus. Fine-tuned NLLB-1.3B achieves the highest BLEU (16.3) and COMET (0.738). Aya-Expanse 8B leads the few-shot LLMs (BLEU 1.7 on 500 sentences, chrF 25.7), but all LLM scores remain far below the fine-tuned NMT baselines. Error analysis identifies low lexical overlap as the dominant failure mode; among the worst translations, mT5-small produces 32% too-short outputs. Bootstrap tests confirm significant differences among most models. Our results demonstrate that fine-tuned NMT significantly outperforms few-shot LLMs for Arabic-Russian translation under low-resource conditions.

---

### [88] CodeGraph: Open-Taxonomy Knowledge Graph for Source Code with Wikidata Grounding

**链接**: https://arxiv.org/abs/2609.29474
**作者**: Federico Pennino, Andrea Gurioli, Stefano Zacchiroli, Maurizio Gabbrielli, Paolo Ferragina
**来源**: cs.SE cs.CL cs.IR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Public software repositories, like GitHub and Software Heritage Archive, store billions of files, yet extracting their implicit engineering knowledge ---i.e., the algorithms they implement, the paradigms they follow, the patterns they instantiate, and the application domains they serve--- remains challenging, as current tools are constrained to syntactic and token-level analysis. We present a pipeline for building an open-taxonomy semantic annotation of source code using a code-specialised Large Language Model. The extracted entities are grounded in Wikidata through a three-stage linking procedure: a deterministic SPARQL stage handles unambiguous entities, a Deep Research Agent resolves the residual long tail, and a hierarchy-rollup stage imports the parent-of closure of each resolved Wikidata identifier. The resulting annotations are materialised as a source-code-specific open-taxonomy knowledge graph. We further introduce a calibrated quality-assurance protocol that quantifies annota

---

### [89] Prefilling the Reasoning Channel: Output-Prefix Attacks on Reasoning LLMs

**链接**: https://arxiv.org/abs/2609.29775
**作者**: Luk\'a\v{s} Br\r{u}na, Robert Bridges, Adam Ek
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) consume and produce a single sequence of text; hence, if text can be added to the beginning of the LLM's response, i.e., an output prefix, then all subsequent tokens will be conditioned on it. This output-prefix attack technique is a cheap black-box prompt injection. Prior work has shown this type of attack can reliably jailbreak non-reasoning models. Most reasoning models add an intermediate scratchpad reasoning step before the assistant's final response. The ability to edit this reasoning channel is exposed by some APIs and attack vectors can be leveraged for reasoning injection attacks. We present the first systematic, controlled study that isolates the scratchpad reasoning channel as an output-prefix attack vector, and the first to compare reasoning-only, output-prefix-only and reasoning-plus-output-prefix attacks across both exposed- and hidden-reasoning models. Using a factorial design of 3 prefix types $\times$ 2 reasoning injections over $1{,}800$ t

---

### [90] GRASP: Generating, Revising, and Assessing for Strategic Planning with Agentic AI

**链接**: https://arxiv.org/abs/2609.30147
**作者**: Arunabh Srivastava, Mohammad A. (Amir) Khojastepour, Srimat Chakradhar and Sennur Ulukus
**来源**: cs.AI cs.CL cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) typically exhibit a performance profile where reliability degrades as task complexity increases. We address the challenge of generating high-quality natural language executable plans for complex tasks by introducing $\textbf{GRASP}$, a strategy-aware, multi-stage planning framework. GRASP decouples the planning pipeline across specialized, context-isolated modules: it pre-compiles global macro-guidelines (GenPlan), explores alternative localized strategies within isolated context windows (RevPlan), and independently evaluates trajectories using a multi-criteria discriminator (VerPlan). Empirical evaluations show that GRASP consistently establishes a new state-of-the-art frontier across diverse datasets, yielding substantial accuracy gains over direct LLM planners on Natural Plan Calendar Scheduling ($\sim$12.4$\%$$\uparrow$), ZebraLogic ($\sim$30.8$\%$$\uparrow$), and SciBench Math. Crucially, under multi-task scaling-where standard planners suffer immediat

---

### [91] IndicBankBench: Evaluating Safety and Reliability of Language Model Assistants in Indian Retail Banking

**链接**: https://arxiv.org/abs/2609.29167
**作者**: Suvradip Paul, Chandra Bhushan, Harsh Sharma, Nitin Kukreja, Yatharth Dedhia, Keyur Doshi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Banking assistants must use account-specific information to answer requests and, in many cases, take actions through tools. Evaluating only the final response misses important errors. An assistant may ask for information it already has, rely on stale context, select the wrong account, or write an invalid value after stating the correct one. We introduce IndicBankBench, a 799-case benchmark for Indian retail banking spanning five operational domains, a capability/refusal domain, and twenty primary axes. Cases are evaluated at four stages: safety, action and tool use, response adequacy, and advisory quality. Tool use and most safety checks are deterministic. A narrow resolver handles only ambiguous confirmation-before-write cases, while a separate LLM judge evaluates semantic response adequacy. We run every case three times and report strict pass^3, which requires success on all trials. Across the eleven evaluated models, strict reliability ranges from 43.7% to 58.2%, whereas at-least-on

---

### [92] A Harness for Synthesizing Diverse Naturalistic Full-Duplex Conversations

**链接**: https://arxiv.org/abs/2609.28806
**作者**: Matthew Sun, Vinay Kothapally, Meng Yu, Chao Huang, Hao Zhang, Yixuan Zhang 等 (7 人)
**来源**: eess.AS cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex dialogue systems, which listen while speaking, must distinguish a completed turn from a pause within a turn and an interruption that requests a turn from a brief acknowledgment or speech addressed to a third party. Yet existing conversational corpora provide limited control over these events and limited labels for their intent. We present a pipeline for synthesizing intent-labeled, two-channel conversational speech from relational event lists. An LLM authors each event's speaker, text, conversational act, and attachment to an earlier event without predicting absolute timestamps. Events are synthesized independently, aligned with their source text, and placed on a shared clock, so turn-taking landmarks are measured from the rendered signal while silence durations are specified or sampled from turn-taking distributions. The pipeline covers 42 phenomena across eight families in English and Mandarin, derives frame-level system actions from authored intent, and promotes diversit

---

### [93] Instrumental Monitor Evasion Emerges Under Ordinary Task Pressure

**链接**: https://arxiv.org/abs/2609.30217
**作者**: David Schmotz, Derck Prinzhorn, Luca Beurer-Kellner, Anselm Paulus, Ameya Prabhu, Maksym Andriushchenko
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A central concern in AI safety is that agents may treat oversight as an obstacle when it conflicts with completing their goals. We study instrumental evasion, the propensity of LLM agents to circumvent runtime monitoring as a means of completing ordinary tasks. We introduce EvasionBench, a benchmark of 50 diverse task-policy pairs in which completing the task requires an operation prohibited by a runtime monitor. Agents know that their tool calls are monitored and are prompted to continue working when they pause. Across our evaluations, best-of-3 evasion attempt rates reach up to 98% and success rates up to 88%, with substantial variance across models. Claude Fable 5.1 succeeds less often, but frequently makes creative attempts to circumvent the monitor. Evasion generally increases with test-time compute, with higher evasion rates at greater reasoning effort and token use. Traces show that agents encode prohibited commands, decompose operations across tool calls, and retry until releva

---

### [94] Speculative Evaluation of Stochastic LLMs

**链接**: https://arxiv.org/abs/2609.28560
**作者**: Qianli Shen, Xiang Li, Ruomeng Ding, Yanxi Chen, Daoyuan Chen, Yaliang Li
**来源**: stat.ML cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating a stochastic large language model is costly: benchmark scores estimate expected performance from randomized rollouts, yet uniform repetition ignores sharp differences in task-level rollout variance. We ask how to minimize the variance of a fixed-benchmark mean under an exact rollout budget. We develop Speculative Evaluation with a Hierarchical Bayesian Neyman (HBN) policy with pilot size and stage weight jointly chosen ex ante. It runs a short uniform pilot, pools per-task success counts with a hierarchical Bayesian model, and uses posterior expectations of task-level sampling variances for exact positive-integer Neyman allocation. To mitigate the pilot synchronization barrier, HBN-async speculatively executes continuations from partial pilot feedback and retains those selected by the final allocation. Across six checkpoints and 18 benchmark groups, we evaluate 107 nondegenerate benchmark-checkpoint profiles. For rollout budgets of 8-64 per task, Speculative Evaluation reduc

---

### [95] Low-Cost Assays for Measuring Model Behavior Across Vendors and Releases

**链接**: https://arxiv.org/abs/2609.30012
**作者**: Tapan Parikh
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models advise people, keep them company, and write software while they sleep. Measuring what they do is hard: behavior has to be sampled repeatedly across models, prompts and releases, most of it lives in unstructured text that has to be coded before it can be counted, and the result has to be legible and rigorous enough to meaningfully compare models and vendors. To address these constraints, we present a simple, cheap, scalable, and replicable model for studying model behavior. Each study is a frozen, public stimulus run identically on a cross-vendor panel, at a few dollars per model or less. Each reads its transcripts one of three ways, chosen by how much interpretation the behavior needs: exact match on a clamped reply, a codebook applied by LLM judges whose agreement with a human coder is reported per code, and an instrumented environment that records what an agent did independently of what it said. Run across four years of model releases from both frontier and open-sourc

---

### [96] SemMSA: Latent Semantic-Aided Robust Multimodal Sentiment Analysis with Incomplete Data

**链接**: https://arxiv.org/abs/2609.30238
**作者**: Wenhao Li, Zhibin Wu, Chong Xiao, Qiangchang Wang
**来源**: cs.CL cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent research on Multimodal Sentiment Analysis (MSA) has focused on learning from language, visual, and acoustic modalities with incomplete data to infer human sentiment. Most studies typically compensate for missing information by reconstructing modality features or designing complicated fusion mechanisms. However, these methods still suffer from spurious generation and noisy guidance due to the lack of high-level semantic grounding in partially observed multimodal evidence. To address these issues, we propose SemMSA, a latent semantic-aided framework that constructs rich sentiment-relevant semantics with LLMs, fully integrating with all modalities via anchor-free spectral alignment. It mainly consists of Cross-modal Semantic Refinement (CSR) and Cross-modal Spectral Alignment (CSA). Specifically, CSR first adaptively extracts visual and acoustic representations by corresponding adapters to form a unified multimodal prefix with language in the frozen LLM embedding space. It then ite

---

### [97] JEV vs. LLMs as Rubric Judges: Cheaper, Faster, and Wrong in the Same Places

**链接**: https://arxiv.org/abs/2609.29769
**作者**: Delip Rao, Chris Callison-Burch
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We ask whether Jev, a typed classifier that returns probabilities over permitted answers without generating text, can replace an LLM rubric judge. We compare it with three flash-tier LLM judges on nine panels drawn from seven benchmarks, giving every judge identical criterion texts. Jev's accuracy differs significantly from an LLM judge's in only 8 of 27 paired comparisons, ahead mostly on binary criteria and behind only on graded ones, and most of the other comparisons are inconclusive. Summed over the nine panels, the LLM judges, called once per criterion, cost 29 to 325 times as much as Jev and took 30 to 220 times as long. On graded criteria all four judges agree more with one another than with the labels and mostly assign lower levels than the raters. One of several observational accounts is that raters followed scale conventions our criterion texts omit. Jev's confidence ranks its own errors on most panels, which should make a cheap classifier the ideal first stage of a cascade t

---

### [98] SLCA-GRPO: Resolving Cross-Segment Credit Misattribution in Tool-Calling RL

**链接**: https://arxiv.org/abs/2609.29050
**作者**: Yan Zhan, Shaobo Liu, Qiunan Liu, Yuanjun Shi, Siqi Xu, WeiYi Hou 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-calling agents produce heterogeneous outputs, interleaving structured tool invocations with user-facing natural language summaries. This output heterogeneity presents a structural failure mode in standard on-policy Reinforcement Learning (RL): algorithms like GRPO indiscriminately broadcast a homogeneous trajectory-level scalar advantage to all tokens. Consequently, gradient noise from summary generation leaks into tool-decision tokens, causing cross-segment credit misattribution and brittle optimization. In this work, we propose SLCA-GRPO, a framework incorporating Segment-Locked Credit Assignment (SLCA). To enable scalable exploration without costly real APIs and stable training, we first construct the Schema-Guided LLM Simulator (SGLS) as foundational training infrastructure. Building on this, SLCA decouples advantage estimation at the structural segment level within a single group of rollouts, without requiring additional rollouts from intermediate states. Supported by Hierarc

---

### [99] Graph, Loop, and Harness Engineering for Zero-Trust Agentic Data Engineering and Analytical Processing

**链接**: https://arxiv.org/abs/2609.29668
**作者**: Sagar Srinivas Sakhinana, Venkataramana Runkana
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly automate data workflows, but end-to-end cloud data engineering and analytical execution require reliable coordination across code, data, infrastructure, and runtime environments. We present two zero-trust frameworks. Zero-Trust Agentic Data Engineering generates, deploys, and verifies complete cloud data-engineering solutions from natural-language tasks, with completion conditioned on repository, deployment, runtime, and policy evidence. Zero-Trust Agentic OLAP combines governed Data Preparation with verified Online Analytical Processing (OLAP), permitting production promotion only after validation and evidence-bound approval, and releasing analytical answers only after Same-Snapshot Execution, Exact Result Equivalence, deterministic grounding, and reflection. Both frameworks share three abstractions: graph engineering for evidence-gated workflow structure, loop engineering for bounded recovery, and agent-harness engineering for zero-trust execu

---

### [100] Retrieve-to-Localize: Bridging Large Language Models and LiDAR Geometry for Spatial Grounding

**链接**: https://arxiv.org/abs/2609.29835
**作者**: Byounggun Park, Giyong Moon, Jusung Kim and Soonmin Hwang
**来源**: cs.CV cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LiDAR provides precise geometric information for spatial perception tasks such as object detection in autonomous driving and outdoor robotics. However, recognizing and localizing individual objects is not sufficient to answer questions that require composing spatial relations and grounding the intended target. Motivated by recent advances in large language models (LLMs) for autonomous driving, we leverage their language priors to interpret complex spatial questions and ground the referred target in LiDAR geometry. To support this spatial grounding capability, we introduce SpatialLiDAR-QA, which combines single- and multi-step relational grounding with complementary spatial understanding tasks. We further propose SpatialLiDAR-LM, which aligns LiDAR point features with an LLM and grounds target coordinates through language-conditioned, position-aware proposal retrieval and local point refinement. This design derives target coordinates directly from local LiDAR geometry rather than throug

---

### [101] REAT: A Reflective Experience-Augmented Tutoring Framework for Multi-turn Mathematical Instruction

**链接**: https://arxiv.org/abs/2609.29804
**作者**: Jianheng Zhou, Chaoli Zhang, Xingjun Wei, Xinliang Zhou, Giancarlo Fortino, Xing Fan 等 (9 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current Large Language Models (LLMs) excel at solving complex mathematical problems, yet this proficiency does not inherently translate into effective tutoring. While advanced LLM tutors may leverage multi-agent frameworks or fine-tuning, most still lack a mechanism to systematically accumulate and reuse pedagogical experience over time, limiting their adaptability to diverse student needs during fluid, multi-turn interactions. To bridge this gap, we propose the Reflective Experience-Augmented Tutoring (REAT) framework, which couples experience distillation from historical dialogues with real-time adaptive retrieval. Driven by a multi-agent Observer-Critic-Mentor (OCM) distillation pipeline, REAT reviews past conversational trajectories and distills raw interactions into structured, problem-agnostic pedagogical experiences. During live tutoring, a state-aware retrieval module injects these curated experiences to provide adaptive scaffolding based on the student's cognitive state. Exper

---

### [102] BanglaTurn: A Benchmark and Whisper-Based Model for End-of-Turn Detection in Bangla Speech

**链接**: https://arxiv.org/abs/2609.29371
**作者**: Mizbaul Haque Maruf
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents BanglaTurn, a corpus for end-of-turn detection in Bangla conversational speech, and a model trained on it. The corpus holds 35,374 samples of 3 to 15 s of podcast speech, labelled for turn state by combining speaker diarization with an LLM pass, with every label then checked by a human annotator. The model pairs a Whisper encoder with task-specific classification heads. On a class-balanced test set drawn from a held-out podcast, it reaches 84.33% accuracy (95% CI 80.3 to 88.1) against 69.28% for the Smart-Turn v3 baseline, and lowers the false negative rate from 51.57% to 7.55% at the cost of a higher false positive rate. We report what encoder layer fine-tuning, multi-scale pooling and INT8 quantization each contribute, and latency stays within 165 to 191 ms end to end on CPU.

---

### [103] Canopy: Exploiting Piecewise Smooth Tree Priors for Multi-Fidelity Bandits

**链接**: https://arxiv.org/abs/2609.30017
**作者**: Michael Jerge, Suman Jana
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many LLM inference problems, including model routing, prefix-cache management, prompt trimming, and test-time search, can be viewed as optimization over a tree. This structure arises naturally from autoregressive generation: every prefix defines a node, and its continuations form a subtree below it. Internal nodes of the tree provide cheap but biased estimates of a region's value, while leaf evaluations are expensive but accurate. Hierarchical bandit methods can exploit this structure, but typically require a specific smoothness schedule to be specified in advance, even though real objectives are often only piecewise smooth and their optima may lie near sharp boundaries. We introduce CANOPY, a multi-fidelity tree bandit that learns where the smoothness prior is valid rather than assuming it globally. CANOPY uses cheap random-path probes to construct an online certificate of local aggregation bias, then directs expensive leaf evaluations toward cells where the certificate detects a smoo

---

### [104] PFArena: Benchmarking Language Models for Protein Modification

**链接**: https://arxiv.org/abs/2609.28921
**作者**: Yawen Ouyang, Xinbo Zhang, Ziyuan Ma, Yixin Wu, Wenbin Liao, Feiran Zhang 等 (10 人)
**来源**: cs.AI q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Protein modification requires navigating an immense sequence space, yet wet-lab validation remains low-throughput and costly. Although computational paradigms including protein language models (PLMs), large language models (LLMs), and LLM-based agents have shown promise in protein modification, their relative efficacy across realistic experimental decision-making settings remains unclear. To bridge this gap, we introduce PFArena, a benchmark comprising four controlled task interfaces that cover single-mutant generation and multi-mutant ranking. By providing varying levels of mutation fitness data, PFArena reflects four representative research scenarios characterized by differing degrees of prior experimental context. We assess six PLMs, six LLMs, and five LLM-based agents using complementary metrics to measure both peak and overall protein modification performance. Our evaluation reveals that model performance shifts systematically with the availability of target-specific experimental 

---

### [105] Delay-of-Gratification as a Multi-Agent Survival Micro-benchmark for Long-Horizon LLMs: Social Exposure, Personas, and Tool Use Budgets

**链接**: https://arxiv.org/abs/2609.29509
**作者**: Olga Manakina, Igor Bogdanov, Chung-Horng Lung
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as multi-turn agents that must sustain goals, use tools, and adapt to other agents over extended interactions. However, existing research lacks auditable, multi-turn, multi-factorial experiments that quantify LLM behavior under explicit constraints, with time-resolved statistics that reveal how behavior unfolds over long horizons. To address this gap, we develop a multi-agent micro-benchmark inspired by the Stanford marshmallow experiment: ReAct agents operate minute-by-minute with a "raise a question" tool under a per-step budget, while we factorially manipulate social context (broadcast vs. isolated), personas (age, hedonic drive), and metacognitive policy (mandatory vs. optional tool use). We analyze outcomes with Kaplan-Meier (KM) survival curves and discrete-time hazard models over a long risk horizon across 19,200 agent trajectories in 64 cells. Behavior shows a sharp early "eat" impulse, and only 75.9% of agents persist to t

---

### [106] Likelihood Ranking doesn't Scale Like Prompting in LLMs

**链接**: https://arxiv.org/abs/2609.29390
**作者**: Alessandro Bondielli, Lucia Passaro, Davide Bacciu, and Alessandro Lenci
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM evaluation is commonly performed either by prompting models to produce answers or by scoring candidate outputs with likelihood-based metrics. In multiple-choice QA, however, standard likelihood-based scoring is still conditioned on the question and answer set, and can therefore leverage the same task-conditioned answer-selection interface used in prompting. We study a complementary protocol based on likelihood ranking of declarative statements constructed from the same question--answer pairs. Across 95 decoder-only models, ranging from 0.1B to 104B parameters, and 10 MCQA datasets, we find a systematic divergence between declarative-statement likelihood ranking and prompted answering. Statement-likelihood accuracy remains comparatively stable across scale, whereas prompted answering improves sharply with scale and instruction-tuning. These results suggest that likelihood preferences over controlled declarative alternatives and task-conditioned answer selection probe distinct aspect

---

### [107] Ontology-Mediated Neurosymbolic Constraint Acquisition from Multiple Stakeholders

**链接**: https://arxiv.org/abs/2609.29876
**作者**: Stefan Bischof and Juliana Kainz and Danilo Valerio
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neurosymbolic research typically assumes a pre-existing symbolic specification, leaving the upstream challenge of acquiring and formalizing requirements and constraints largely unaddressed. We present an architecture that fills this gap by using an OWL configuration ontology to mediate between neural constraint sources and downstream consumers. In this framework, LLM assistants elicit soft stakeholder preferences, while hardware specifications define hard physical and engineering limits. The ontology unifies these heterogeneous inputs, leverages description logic to identify unsatisfiability, and generates symbolic explanations that enable LLMs to interactively renegotiate terms with users. Any remaining conflicts are resolved downstream via priority-based relaxation. We illustrate our approach on a microgrid use case from the FLEXI project and argue its generalizability to multi-stakeholder domains where constraint acquisition is distributed across human and automated sources of unequ

---

### [108] Accent Analogy Guidance: More Speaker Similarity at Equal Accent in Cross-Lingual Voice Cloning

**链接**: https://arxiv.org/abs/2609.29123
**作者**: Yoomee Cho, Jisun Lee
**来源**: cs.SD cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In cross-lingual zero-shot text-to-speech, the accent of the reference leaks into the target speech. We propose accent analogy guidance (AAG), a training-free sampler term that subtracts an accent direction estimated from the model's own predictions for one synthetic voice rendered in both languages, so the voice cancels and only the accent remains. By a blind LLM accent judge on real dubbing data, reweighting classifier-free guidance between reference and text, and its variants, stay near one identity-accent trade-off curve; we score a method by its speaker similarity above that curve at equal accent ($\Delta$SIM). Across four open TTS models AAG lies above the curve: on OmniVoice $\Delta$SIM is +0.11 to +0.27 on three test sets (accent 3.51 to 4.28 on a 1-5 scale at speaker similarity 0.29, where reweighting keeps 0.02); MaskGCT and CosyVoice 2 also lie above their curves, and on F5-TTS it is more native than any reweighting setting. An LLM-free language-ID measure and a twelve-liste

---

### [109] Chart-Supported or Model-Supplied? Examining MLLM-Generated Claims for Accessible Visualization

**链接**: https://arxiv.org/abs/2607.25021
**作者**: Ishrat Jahan Eliza, Md Dilshadur Rahman
**来源**: cs.AI cs.HC cs.MA cs.SE
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] Exploiting Target Knowledge from MLLMs for Robust Few-Shot Segmentation

**链接**: https://arxiv.org/abs/2609.28949
**作者**: Yijun Hu, Heng Fan and Libo Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Few-shot segmentation (FSS) aims to segment unseen object categories with a few (e.g., one or five) labeled examples, enabling efficient adaptation to novel classes. Conventional models typically rely on appearance-based visual matching between support and query images for segmentation. While straightforward, these methods often struggle to handle significant appearance discrepancies and occlusions in the query image due to insufficient target knowledge. To mitigate this, we introduce a novel framework that mines target knowledge using the strong reasoning capacity of Multimodal Large Language Models (MLLMs) and employs it to enhance FSS. Specifically, building on SAM 2, our method, named MK-FSS, exploits two forms of complementary knowledge derived from a query image by an MLLM for FSS, including spatial knowledge, which provides a spatial prior indicating the potential target location, and semantic knowledge, which describes the target using text. The spatial knowledge is first encod

---

### [111] AERIAL: Adversarial Evaluation of Robustness in Accuracy-Preserving Low-Precision EEG Decoders

**链接**: https://arxiv.org/abs/2609.30037
**作者**: Saim Rehman and Muhammad Shafique
**来源**: cs.CV cs.CR cs.LG eess.SP
**匹配关键词**: EEG, BCI
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deployment-oriented compression is attractive for resource-constrained brain--computer interfaces (BCIs), but whether it changes adversarial vulnerability remains unclear. On BCI Competition IV-2a, we compare 32-bit floating-point (FP32) EEGNet and ShallowConvNet models with global magnitude pruning and simulated INT8 post training quantization (PTQ) and quantization-aware training (QAT) across nine subjects and three seeds. Simulation provides differentiable quantize--dequantize models for white-box attacks and gradient analysis, while native TensorRT deployment is used for validation. Accuracy-preserving compression does not improve direct robustness: at $\epsilon=0.005$, EEGNet PGD accuracy remains 22--24\% across FP32, 50\% pruning (P50), PTQ, and QAT. However, P50 reduces bidirectional transfer efficiency to 0.963/0.928 (FP32$\rightarrow$P50/P50$\rightarrow$FP32), versus 0.994/0.997 for PTQ; the same trend holds for ShallowConvNet. Gradient alignment shows a corresponding separati

---

### [112] Personalised federated learning for Riemannian and Euclidean EEG decoding

**链接**: https://arxiv.org/abs/2609.29037
**作者**: Thibault Pautrel, Florent Bouchard, Ammar Mian, Guillaume Ginolhac
**来源**: stat.ML cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated learning (FL) lets EEG decoders learn from recordings of several subjects without pooling them. We consider two light EEG decoders, the Riemannian SPDNet and the Euclidean EEGNet. Both split into a trunk, which builds a latent representation, and a head, which classifies it. Inter-subject variability, however, makes a single shared FL model a poor fit for each subject. Personalised FL addresses this: all subjects learn a common trunk, and each subject keeps its own head. We adapt it for SPDNet and study its effects against standard FL and centralised training, with EEGNet as a Euclidean baseline. Experiments cover three motor-imagery datasets that span diverse regimes in channels, subjects and classes. We observe that personalised SPDNet reaches higher accuracy than both standard FL and centralised training, while converging in fewer rounds and communicating fewer parameters than standard FL. It also outperforms every EEGNet configuration on two of the three datasets, althoug

---

### [113] SHINE: Sequential Hierarchical Integration Network for EEG and MEG

**链接**: https://arxiv.org/abs/2602.23960
**作者**: Xiran Xu, Yujie Yan, Songyi Li, Linze Zheng, Zifeng Zhang, Mochu Dong and Jing Chen
**来源**: cs.SD cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [114] Decoding Imagined Speech: A Strictly Subject-Independent Approach Using EEG

**链接**: https://arxiv.org/abs/2609.29820
**作者**: Frederik M{\o}llskov Trier, Xiaopeng Mao, Sadasivan Puthusserypady
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Imagined speech decoding from electroencephalography (EEG) has gained increasing attention as a potential communication pathway for individuals with severe motor impairments, yet reported performance often relies on evaluation protocols that do not clearly reflect cross-subject generalization. This study presents a transparent baseline investigation of a multi-class imagined speech EEG dataset under a strictly subject-independent evaluation framework. Two preprocessing and feature extraction pipelines were compared: a time-domain statistical feature approach and a frequency-domain spectral bandpower approach, evaluated using subject-wise cross-validation and trial-level majority voting with a random forest classifier. The spectral pipeline achieved a significantly higher mean trial-wise accuracy than the statistical pipeline (49.03 $\pm$ 4.18% vs. 37.97 $\pm$ 3.79%) for coarse-level classification across subjects. Forward feature selection further indicated that a limited subset of fre

---

### [115] Segment-Level Risk Discovery in Online Handwriting for Alzheimer's Disease Detection

**链接**: https://arxiv.org/abs/2609.29384
**作者**: Changqing Gong, Huafeng Qin and Moun\^im A. El-Yacoubi
**来源**: cs.CV cs.AI
**匹配关键词**: Motor Execution
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online handwriting provides a non-invasive and low-cost behavioral biomarker for Alzheimer's disease (AD) detection, as it reflects both cognitive planning and fine motor control. Existing handwriting-based AD detection methods usually rely on global trajectory features or whole-sample representations, which can be strongly affected by individual writing style, task-specific variation, and acquisition noise. In this paper, we propose NormPaST-Risk, a healthy-normative Paper-Air selective trajectory state-space risk network for interpretable AD detection from online handwriting. Instead of treating the entire trajectory as a single holistic representation, our method reformulates AD handwriting detection as local disease-relevant segment discovery. Specifically, a multi-scale temporal encoder captures stroke dynamics at different temporal resolutions, while a selective Paper-Air state-space encoder models long-range handwriting progression and distinguishes on-paper motor execution from

---

### [116] UltraBench 2: Towards Robust Evaluation of Vision Foundation Models on Ultrasound

**链接**: https://arxiv.org/abs/2609.28610
**作者**: Ashwath Radhachandran, Adam Tupper, Christian Gagn\'e, and William Speier
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarking is an increasingly critical part of research in machine learning and the domains where it is applied, including healthcare. Yet, despite the steady development of new ultrasound foundation models in recent years, the development of well-designed benchmarks to evaluate them has lagged behind. This deficiency has led to fragmented and inconsistent evaluations of competing models, making it difficult to measure progress. To address this issue, we introduce UltraBench 2, a comprehensive benchmark with wide anatomical and task coverage, and a focus on standardization, reproducibility, and ease-of-use. Using this benchmark, we compare existing vision foundation models for ultrasound image analysis. Our analyses demonstrate that ultrasound-specific pretraining still leads on classification, but that state-of-the-art general-purpose models have drawn level on segmentation.

---

### [117] SGA: Uncertainty Quantification for Multi-Step Forecasting in Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.28582
**作者**: Xin-Yu Hu, Shuang Liang, Cheng Feng, Shao-Qun Zhang
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The recent emergence of Time Series Foundation Models (TSFMs) has significantly advanced multi-step forecasting performance, enabling accurate predictions over extended future horizons. However, existing TSFMs often suffer from significantly inherent uncertainty, which typically manifests as derived forecast branches emerging at each time step and spreading to subsequent steps; different forecast branches often exhibit varying forecasting performance, thereby undermining the credibility of TSFM forecasts. In this paper, we propose the Slicing-Graphing-Alignment (SGA) method to quantify the uncertainty of multi-step TSFM forecasts. The proposed SGA first characterizes the topology of all potential forecast branches using a directed acyclic graph, such that the graph complexity bounds the uncertainty of multi-step forecasts, and then precisely measures the graph complexity by integrating both topological information and TSFM-inherent stochasticity. Experimental results conducted on 11 TS

---

### [118] Time-Series Foundation Models That Understand Data Revisions

**链接**: https://arxiv.org/abs/2609.28576
**作者**: Taimoor Ahmad
**来源**: cs.LG cs.SE
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historical observations are not always fixed: statistical agencies revise previously published values as new evidence arrives. Forecasting from a contemporary download can therefore expose a model to information unavailable at the date it purportedly made a prediction. We propose VINTAGE-TS, a revision-aware adaptation of a time-series foundation model that distinguishes observation time from information-availability time. Its targets are the next period's first-published value and the value available a fixed number of days after that publication; neither is declared final truth. A joint predictive distribution preserves dependence between these targets and exposes uncertainty about their difference. We specify an ALFRED-based rolling evaluation, a matched Chronos-2 comparison, conventional and revision-aware baselines, and a separate audit of pretraining overlap. The accompanying software implements validity-interval reconstruction, delayed-label filtering, a frozen-backbone adapter i

---

### [119] TW3Cast: A Frozen Router of Lightly Fine-Tuned Foundation Models for Time-Series Forecasting on GIFT-Eval, Selected Entirely on the Training Split

**链接**: https://arxiv.org/abs/2609.28506
**作者**: Nathan Thierry, Andre-Louis Rochet
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> TW3Cast is a time-series forecasting system that reaches position 3 of 130 entries on the GIFT-Eval benchmark by mean MASE rank, as of 2026-09-14. The two entries above it belong to the leaderboard's agentic category, multi-step systems that use agents or language models to reason about, generate or select forecasts. TW3Cast runs no agent and no language model. Its selection is a table computed once on the training split and then frozen, and its experts are public foundation models lightly fine-tuned on those training splits. For each of the 97 dataset, frequency and horizon configurations, the table serves one of four modes: a specialist, which is a LoRA or full fine-tune of Chronos-2, TiRex or Toto whose training data was cleaned and enriched by explicit rules; a quantile blend that contains a specialist; a blend of base models; or a selection tournament played on a backtest carved from the training split. Every decision in the table was taken on that backtest. A specialist is admitt

---

### [120] Towards Trustworthy Biological Alignment in TabPFN-Probed Pathology Foundation Models

**链接**: https://arxiv.org/abs/2609.29523
**作者**: Ushashi Bhattacharjee, Alloy Das, Saria Hannan, Tirtho Roy, Koushik Howlader, Soumik Sarkar
**来源**: cs.MA q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Histology and transcriptomics provide complementary views of tissue biology, capturing spatial morphology and molecular activity, respectively. Pathology foundation models (PFMs) learn rich morphological representations from H&E images, yet strong downstream performance alone does not establish whether these representations encode biologically meaningful and robust molecular information. We present a **training-free framework for auditing biological alignment in frozen PFMs** using spatially paired histology and transcriptomics from HEST-1k, evaluated on **240 samples spanning three organs**. Multiple frozen PFMs are used to extract H&E representations, while gene expression is aggregated into biologically interpretable pathway-level programs. We use TabPFN as a pretrained probe to quantify the extent to which these molecular programs can be decoded from frozen image representations without task-specific gradient updates. Beyond predictive performance, our audit examines whether pathwa

---

### [121] Search-Based Software Engineering and AI Foundation Models: Current Landscape and Future Roadmap

**链接**: https://arxiv.org/abs/2505.19625
**作者**: Hassan Sartaj, Shaukat Ali, Paolo Arcaini, Andrea Arcuri
**来源**: cs.SE cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] ICE: Task-Aligned Clifford Latent Fields for Multimodal Graph Foundation Models

**链接**: https://arxiv.org/abs/2609.29398
**作者**: Xunkai Li, Xu Wang, Yinlin Zhu, Xiong Yongfu, Yi Liu, Rong-Hua Li 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal attributed graphs connect entities, visual content, language, and observed relations. Learning one foundation across such graphs requires more than compressing each node into a fused Euclidean vector. The representation must preserve entity semantics, construct interaction state from graph neighborhoods, and expose that state to prediction units with different geometry. Our empirical study shows why these requirements are inseparable. Higher-grade channels recover pair relations across the foundation graphs, specialized queries reveal information hidden by a generic readout, and rigid blade isolation removes cross-grade capacity. We therefore introduce ICE (Interaction-aware Clifford Encoder), a multimodal graph foundation model built on a node-indexed Clifford latent field. Topology, text, and images enter explicit Cl(3) addresses. Edge-aware geometric products transform these directions into scalar, bivector, and trivector relations over observed neighborhoods. A protected

---

### [123] SwitchPFN: Shared Switching Dynamics for Frozen In-Context Time Series Classification

**链接**: https://arxiv.org/abs/2609.29814
**作者**: Zhenyi Zhu, Jacqueline Pang, Peilin Shen, Tianyi Song, Tingwei Zhang, Keyi Hu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) provide a promising route to time-series classification, but their effectiveness depends on how sequential data are converted into tabular representations. Existing representations face two challenges: global aggregation can lose the order of temporal evolution, while features computed in independently fitted coordinate systems may not have consistent meanings across sequences. We therefore view representation design for TFMs as a problem in its own right: the representation should preserve local temporal transitions while maintaining a shared feature definition across samples. We propose SwitchPFN, which learns a shared projection and regime codebook from the training sequences, making local dynamic operators and transition features directly comparable across samples. Across the evaluated benchmarks, SwitchPFN achieves the highest mean accuracy among the evaluated methods, improving over the strongest baseline by 4.47% relatively. Ablation studies, par

---

### [124] Downside-Controlled Online Forecast Combination under Delayed and Revised Outcomes

**链接**: https://arxiv.org/abs/2609.29096
**作者**: Minkyoung Kim, Hyunjung Byun, Yohan Lee, Beakcheol Jang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-hoc correction adjusts a forecaster that cannot be retrained, such as a foundation model, but a correction fitted where errors are stable can hurt where they shift. We aim for downside control: not much worse than the starting forecast. We combine the frozen forecaster, a static corrector and an online corrector on the simplex, using only losses that mature after the horizon. Across seven benchmarks and four base models, two of them foundation models, the worst deterioration over 28 pairs at the main horizon is 0.15% and gains reach 11.5%. On day-ahead load for seven European bidding zones it lowers mean MSE in all seven zones, while single correctors raise mean MSE by up to 102% where the published forecast is most accurate. Three empirical conditions on expert speed, stream length and outcome alignment, each fixed by a documented failure, delimit its scope. Learning from the provisional outcome improves four zones on the settled one; learning on the settled outcome restores all 

---

### [125] PoEM: Predicting RL Outcomes from Existing Policies

**链接**: https://arxiv.org/abs/2609.30226
**作者**: Kimia Hamidieh, Giannis Daras, Antonio Torralba
**来源**: cs.LG cs.AI cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are post-trained with reinforcement learning (RL) to maximize specific rewards, such as human alignment, correctness, or instruction following. This post-training process is computationally intensive, sometimes unstable, and has to be run from scratch every time the reward model changes or when we want to combine multiple rewards. We hence ask: given a new reward function, is it possible to predict the RL outcomes without actually running RL on it? We answer this in the affirmative by introducing PoEM, a framework to predict the outputs of RL on a new reward function using a set of models already post-trained on other rewards. First, we show that if the new reward function can be written as a linear combination of existing ones, then the new policy in log-space can be written as a linear combination of the existing log-policies. Surprisingly, even in cases where the rewards are not linearly connected, we observe that often log-policies from RL training span an approxi

---

### [126] ComplexSync: High-Fidelity and Real-Time Lip Sync in Complex Scenarios

**链接**: https://arxiv.org/abs/2609.29225
**作者**: Jiaran Cai, Xingpei Ma, Shenneng Huang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lip synchronization aims to generate visual lip dynamics that align precisely with speech audio. Despite the high generation quality of diffusion models, they often struggle in complex scenarios and suffer from prohibitive inference latency, limiting real-world deployment. We present ComplexSync, a unified diffusion-based framework that enables real-time, high-fidelity lip sync under complex conditions. First, we introduce a dual-stream joint training strategy to mitigate information leakage from reference frames while preserving natural dynamics. Second, we develop a distillation-based acceleration scheme for single-step denoising, achieving a throughput of over 70 FPS. Third, we propose a relational alignment loss that leverages structural priors from Vision Foundation Models (VFMs) to enhance robustness against complex scene factors. Furthermore, we present the first benchmark specifically designed for complex lip synchronization, comprising over 200 challenging video sequences and 

---

### [127] FounRef: Robust, Structure-Preserving, and Fast Metric Refinement of Frozen Monocular Foundation Priors with Sparse Anchors

**链接**: https://arxiv.org/abs/2609.29224
**作者**: Dan Halperin, Mirko M\"ahlisch
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dense metric depth from cameras is essential to real-world 3D applications, yet achieving accuracy, faithful surface geometry, and fast inference simultaneously remains challenging. Monocular foundation models provide rich, transferable geometric priors but lack reliable metric scale, while depth-completion networks recover metric depth at the cost of geometric fidelity, cross-domain robustness, or speed. We present FounRef, a training-free method that aligns a frozen monocular foundation prior with sparse metric anchors to produce dense metric depth. FounRef is modular by design: its depth prior, anchor source, and refinement solver can each be replaced independently. We instantiate FounRef with MoGe-2 and LiDAR anchors. FounRef validates each anchor against the prior's dense depth prediction, rejecting inconsistencies caused by cross-sensor misalignment that geometry-only filters cannot detect. It then applies global and local metric corrections through a structure-preserving solver,

---

### [128] Adaptive Fisher-Whitened Cross-Covariance for Low-Resource Speech Recognition

**链接**: https://arxiv.org/abs/2609.29800
**作者**: Asmee Mishra, Mengjie Qian, Brechtje Post, Kate Knill
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting multilingual speech foundation models to low-resource languages remains difficult, especially for languages that are poorly represented during pre-training. While parameter-efficient fine-tuning (PEFT) reduces the cost of adapting large models, conventional approaches such as LoRA rely on generic low-rank parameterizations and do not explicitly use downstream task information to define the adaptation subspace. To investigate whether task-informed PEFT can better support low-resource ASR, we apply Fisher-Whitened Cross-Covariance Analysis (FCCA) to Whisper and Qwen3-ASR, and introduce two complementary extensions: Asymmetric-Coupled FCCA (AC-FCCA), which exploits structured cross-layer sharing, and Adaptive-Rank FCCA (AR-FCCA), which reallocates adaptation capacity across projection matrices under a fixed parameter budget. Under controlled multilingual experiments, we evaluate these approaches on languages that are poorly represented or unsupported during pre-training alongside

---

### [129] TimeBraid: Unifying Time Series and Language for Understanding and Forecasting

**链接**: https://arxiv.org/abs/2609.29792
**作者**: Xinyue Wang, Jiacheng Pang, Kun Zhou, Kexin Zhang, Defu Cao, Fan Feng 等 (10 人)
**来源**: cs.CL cs.AI cs.CE
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present TimeBraid, a series of unified time-series and language models that align pretrained language models and pretrained time-series foundation models through interleaved global residual attention layers. Each model inherits knowledge, instruction following, and reasoning from one side, continuous-signal perception and zero-shot forecasting from the other, and fuses the two in a shared representation space where both modalities are understood and generated. We study the design choices that make such unified modeling work: where to align the two representation spaces, how to ground language in temporal structure, how to balance understanding with generation, and how to keep joint optimization stable. The resulting recipe combines a unified prompting scheme for diverse time-series and text tasks, stabilized joint training, and supervision from 2.2M curated series--text pairs and 4.9M instruction-tuning samples. Across benchmarks spanning time-series perception, understanding, reaso

---

### [130] SplatLabel: Pseudo-Labelling through 4D Gaussian Splatting

**链接**: https://arxiv.org/abs/2609.29836
**作者**: Nitya Nanvani, Andras Palffy, Holger Caesar
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While 2D Vision Foundation Models offer a pathway to automate 3D semantic pseudo-labelling, translating these priors into robust 3D representations typically requires complex heuristics or multi-model ensembles. We introduce SplatLabel, an automated pipeline that leverages a 4D Gaussian representation to extract LiDAR segmentation with predictive confidence, as well as semantic occupancy grids at arbitrary voxel resolutions. At its core, SplatLabel handles dynamic environments through an explicit temporal manifold that models the trajectories and lifespans of individual 3D primitives. This allows the system to accurately track moving actors and strictly define when objects appear and disappear, completely eliminating the need for pre-annotated 3D bounding boxes. To robustly support this dynamic tracking, the representation is grounded by structural and semantic priors: we guide scene geometry in unobserved regions by integrating 360-degree LiDAR via virtual depth maps, and rather than 

---

### [131] WildHSR: Metric Feed-Forward 4D People-Scene Reconstruction from a 3D Foundation Model

**链接**: https://arxiv.org/abs/2609.29106
**作者**: Jerrin Bright, John Zelek
**来源**: cs.CV cs.AI cs.CG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D foundation models recover video cameras and geometry in one forward pass, but some of the strongest are up to scale. Joint people-scene reconstruction then requires two missing outputs: metric scale and persistent person identity. We ask whether one up-to-scale foundation representation can support both through lightweight adaptation. Exact metric labels are scarce, but unlabeled in-the-wild video is abundant. We use people in curated web video to initialise the solution: a posed metric body and 2D keypoints give an approximate, closed-form scale pseudo-label. These pseudo-labels pretrain a Scale Readout, which is then fine-tuned together with a lightweight adapter using exact metric supervision from standard real-video training splits. At inference the head predicts metric scale from foundation-model tokens, without the ruler or its teachers. For person identity, we probe the pretrained foundation model alone and find evidence that its intermediate query-key features encode person 

---

### [132] M3GD: Multi-Modal Multi-View Geometric Diffusion for Camera--LiDAR Novel View Synthesis

**链接**: https://arxiv.org/abs/2609.30056
**作者**: Yang Zhou, Jiuhong Xiao, Shizhao Ye, Long Quang, Carlos Nieto-Granda, and Giuseppe Loianno
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robotic novel view synthesis (NVS) must recover both visual appearance and metric 3D structure, yet most generative NVS methods rely only on images, overlooking LiDAR, a complementary sensor common on robotic platforms. We present M3GD, a Camera--LiDAR multimodal representation for generative NVS that composes independently pretrained 2D image and 3D point-cloud foundation models without separately pretraining a cross-modal translator. We show that, after camera projection, frozen LiDAR and image features exhibit substantial shared spatial structure, providing a natural cross-modal representation. M3GD conditions generation on LiDAR through this structure: it combines explicit geometry statistics with learned point-cloud descriptors into view-aligned packets on the image-latent grid, injected through a lightweight residual adapter into a multi-view flow-matching generator whose latent space, decoders, and training objective remain intact. On the GrandTour dataset, M3GD improves target-

---

### [133] Recoverable Geographic Location Information in Earth-Observation Embeddings

**链接**: https://arxiv.org/abs/2609.29151
**作者**: Peiwen Zhang, Kristie Hu, Jovana Knezevic, Shunde Yin, Kyle Gao
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth-observation (EO) foundation models provide reusable embeddings, yet downstream task accuracy does not reveal whether these representations encode geographic information, which may be beneficial for location-aware applications but potentially detrimental when representations invariant to geographic location are desired. We therefore evaluate the geographic coordinate robustness of Tessera v1, Tessera v1.1, and AlphaEarth by testing whether coordinates can be predicted from the embedding representations using 284 quality-verified European solar farms from 2024. We assessed geographic information content information through the association between cosine and geodesic distances and through prediction of projected coordinates in EPSG:3035. Embeddings from all three EO foundation models contain recoverable geographic information. All prediction models significantly outperform training-range uniform random sampling baselines, with AlphaEarth exhibiting the strongest distance association

---
