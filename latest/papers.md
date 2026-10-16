# 📑 论文索引 - 2026-10-17

共 177 篇论文

---

### [1] Documenting Trofinetide Treatment Phenotypes in Rett Syndrome with a Dual-LLM Consensus Pipeline

**链接**: https://arxiv.org/abs/2610.22062
**作者**: Daniel Palacios, Guantong Qi, Mikael Guzman Karlsson, Shawntel K. David, Mohammed Sameeruddin, Bernhard Suter 等 (9 人)
**来源**: q-bio.QM cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: Trofinetide, approved in 2023 as the first Rett syndrome treatment, lacks scalable real-world monitoring because chart review is labor-intensive. We developed a dual large language model (LLM) consensus pipeline to extract 18 treatment-response phenotypes, comprising 4 adverse effects, 13 Rett clinical features, and medication refusal, from clinical notes. Materials and Methods: We analyzed 26,763 notes from 108 patients with confirmed sustained trofinetide exposure at Texas Children's Hospital. The pipeline filters notes by keyword, classifies each through two LLMs requiring consensus, and aggregates a patient-by-timepoint matrix. Architecture and prompt were selected on a diarrhea development set, then frozen and applied to the other 17 phenotypes with the phenotype definition substituted, as an out-of-sample test. The reported prompt comparison scores 183 expert-labeled cells. Results: A prompt requiring diarrhea to be active and severe performed best (84.2 $\pm$ 0.0% acc

---

### [2] Learning to Steer LLM Agents and Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.22316
**作者**: Leyang Shen, Yaxin Gong, Yang Zhang, Chenxiao Fan, Jiakai Wang, Dong Wang 等 (10 人)
**来源**: cs.LG cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents and multi-agent systems increasingly tackle complex tasks through long-horizon tool use and inter-agent collaboration. However, these systems are prone to deviating from the overall goal as execution unfolds, which wastes execution resources and leads to undesired outcomes, a failure termed goal drift. In this work, we propose a steering agent that supervises execution on the fly and steers the system back on track when drift occurs. The steering agent observes the execution context, deciding when to intervene with a low-cost fast path and how to intervene with a high-cost slow path. To unlock its steering intelligence, the ability to assess goal drift and generate effective interventions, we jointly train the two paths with reinforcement learning, combining a pairwise ranking objective with group-relative policy optimization (GRPO). Experiments on information-seeking search tasks show that the steering agent provides effective supervision for bo

---

### [3] GraphACM: Graph-based Action Consistency Measurement for Uncertainty Quantification in LLM Agents

**链接**: https://arxiv.org/abs/2610.22031
**作者**: Yaxin Ma, Wenbo Zhang, Satya Krishna Pothapragada, Alina Zare
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Behavioral consistency across repeated executions provides an informative signal for assessing the reliability of large language model (LLM) agents. However, existing approaches typically summarize consistency with a single task-level score, without identifying where behavioral differences occur or whether actions are compared under equivalent decision contexts. We propose a graph-based framework for fine-grained behavioral consistency measurement and uncertainty quantification. Given multiple rollouts of the same task, we merge equivalent states into a directed, action-labeled graph, enabling action comparisons at shared decision states. We introduce node-level and global measures of action consistency, using the global consistency score as a proxy for uncertainty to predict task success or failure. Experiments across three LLMs on ALFWorld, AppWorld, and WebShop demonstrate that our measure is positively associated with task success and achieves an average AUROC of 0.811 for task-suc

---

### [4] FGSS-BO: Feedback-Guided Hypothesis Management for LLM-Based Bayesian Optimization

**链接**: https://arxiv.org/abs/2610.21246
**作者**: Hao Chen, Ziyang Ling, Ronald X. Xu, Mingzhai Sun
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-guided Bayesian optimization (BO) uses past observations to guide search, but proposed directions and their revision can remain implicit. We propose Feedback-Guided Search State (FGSS), a structured hypothesis-management interface connecting language-based guidance to observed evidence, executable parameter interventions, and comparative support updates. An LLM reflector proposes and revises hypotheses; a deterministic curator validates them and maintains identities and test records. The evolving state guides candidate construction and priorities. Instantiated on LLAMBO, FGSS-BO retains its surrogate and default expected improvement selection, with a bounded testing policy. On two retrospective protocol/media tasks with nearest-neighbor response oracles, it attains higher sample mean final best and search AUC than the matched LLAMBO baseline and evaluated non-LLM baselines. Prose-reflection and EI-only controls show mixed component effects. Six direct-trainin

---

### [5] CausalEvo: Causal Skill Self-Evolution for Health LLM Agents

**链接**: https://arxiv.org/abs/2610.21016
**作者**: Yuchen Zhang
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents for health can accumulate reusable textual skills from task feedback, such as calculation criteria, measurement time points, and formula units. Deciding which skills to retain is consequential: useful rules improve later answers, while faulty generalizations propagate errors. We propose CausalEvo, a method for causal skill self-evolution that estimates the relative effects of deliberately changed skill sets while holding the model weights, feedback cases, and rule count fixed. At each evolution step, a frozen LLM proposes candidate rules, which are pooled with the incumbent skills so that the current skill set remains a feasible choice. Paired skill replacements against shared background rules are scored on the same feedback cases; least squares converts the score differences into relative skill values, and the top-ranked rules are retained, favoring incumbents on ties. A decision-loss bound separates candidate support, approximation, and estimation er

---

### [6] WaveLLM: Wavelet-Domain LLM Entropy Modeling for Lossless Image Compression

**链接**: https://arxiv.org/abs/2610.22232
**作者**: Yue Yu, Bowei Kang, Changsheng Gao, Dong Liu, Xiaoyan Sun
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lossless image compression fundamentally relies on accurate entropy modeling, driving a recent shift toward large language model (LLM)-based methods. However, existing approaches mainly emphasize the modeling capacity of LLMs while directly serializing images into pixel or residual sequences, leaving heterogeneous signal patterns entangled within a single prediction stream. In this paper, we argue that effective entropy modeling depends not only on model capacity, but also on the predictability of the input representation. Motivated by this insight, we propose WaveLLM, a wavelet-domain LLM-based entropy model for lossless image compression. By decomposing an image into multi-level wavelet subbands, WaveLLM converts a heterogeneous prediction problem into a set of more structured and statistically homogeneous subproblems that are more amenable to autoregressive probability estimation. To bridge numerical coding symbols with the LLM's native text token space, we introduce a dedicated num

---

### [7] MemComposer: Learning to Assemble Memories for LLM Agents via Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.21091
**作者**: Yixuan Xie, Xueqiang Xu, Xinyi Fan, Xinxi Lyu, Tao Feng, Xing Fan 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent memory enables large language model (LLM) agents to reuse past experiences without updating their parameters. However, semantic similarity alone does not guarantee memory usefulness: downstream performance depends on how memories are selected and presented to the agent. We propose MemComposer, a memory composer that jointly examines the current query and retrieved candidates to decide which experiences to include, how many to select, and how to order them. We train the composer using Experience Policy Optimization (ExPO), a GRPO-based framework that evaluates assembled memory contexts through complete agent interactions and uses task-success feedback to optimize the assembly policy. Across three $\tau^2$-bench domains with two frozen executors, MemComposer outperforms the strongest baseline for each executor while reducing average memory-token usage by 16.9% and 4.9%, respectively. The learned policy also transfers to unseen domains, executors, and memory banks, and benefits from

---

### [8] MemCut: Every Secret Leaves a Trail in the Long-Term Memory of LLM Agents

**链接**: https://arxiv.org/abs/2610.21405
**作者**: Cheng Zhang, Xuanning Cao, Zhicheng Zheng, Hui Xiong
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory has become a crucial component of large language model (LLM) agents, with most research focusing on retrieving relevant information accurately and efficiently. However, a dependable memory system must also forget sensitive user data upon request. To evaluate this capability, we introduce MemCut, a systematic benchmark for user-requested forgetting. Its 456 hand-designed secrets in long-horizon conversations have fully annotated evidence trails to test recovery after deletion, including from messages that never state the secrets directly. We propose two recovery metrics. Native recovery measures reader success through the system's retrieval, whereas residual recovery measures the same reader's success when directly given surviving objects traced to annotated disclosures or evidence. We establish three reference deletion baselines to test how far existing retrievers and write models support forgetting across five memory designs and four LLMs. Disclosure removal reduces n

---

### [9] SSR: Structural Signal Retriever for Scalable Agent Discovery in LLM-Orchestrated Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.21113
**作者**: Giancarlo Maldonado C\'ardenas and Carlos A. Astudillo and Nelson L. S. da Fonseca
**来源**: cs.MA cs.AI cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale multi-agent ecosystems require mechanisms for discovering suitable agents without exposing entire registries to a large language model (LLM) orchestrator. The challenge is not only to retrieve relevant Agent Cards from a growing registry, but also to maintain a compact candidate context, since each additional candidate increases prompt size, inference cost, latency, and the risk of exceeding the model context window. We formulate this problem as candidate-context scalability and propose the Structural Signal Retriever (SSR), our deterministic and training-free retrieval method designed for Agent Card discovery. SSR derives structural lexical signals from capability-bearing Agent Card fields, weights them using inverse document frequency (IDF), and uses an Inverted Signal Index (ISI) for selective candidate scoring. We evaluate SSR using a synthetic agent benchmark, a public MS MARCO adaptation, and end-to-end LLM orchestration. At 1,000 agents, SSR reduces LLM input by 98.8

---

### [10] ISW-Agent: Integrating LLM-Driven Dialogue with n8n Workflow for Internal Solitary Wave Remote Sensing Image Processing

**链接**: https://arxiv.org/abs/2610.21502
**作者**: Hao Zhang (1), Hengrui Liu (1), Lina Sun (1), Junmin Meng (1) ((1) First Institute of Oceanography, Ministry of Natural Resources, Qingdao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Internal solitary wave (ISW) remote sensing requires task parameters and spatial information to be transferred across image acquisition, detection, stripe extraction, and propagation prediction. Here, we present ISW-Agent, which integrates large language model (LLM) interpretation with n8n workflows and independent scientific models through structured task constraints, geospatial transformations, and stage-specific output validation. In tests of 120 Chinese instructions per backend, GPT-5.6 Sol and DeepSeek both achieved a strict task-match rate of 94.2%, with all intents and execution decisions matching the reference. Sentinel-1 cases demonstrated continuous processing from dialogue requests to wavefront prediction for the specified scene. Of 50 timed scenes, 39 completed detection, extraction, and prediction with a median turnaround time of 48.04 s; 11 stopped after empty extraction. Across 3,408 controlled fault-injection runs, retries recovered 234 transient-failure conditions and 

---

### [11] Rubric Judgments Lack Uncertainty: Conformal Weighting for LLM Evaluation

**链接**: https://arxiv.org/abs/2610.21214
**作者**: Licheng Pan, Haocheng Yang, Haoxuan Li, Yuzhou Chen, Yichen Sun, Yuan Lu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based evaluation is widely used to assess large language model (LLM) outputs by decomposing quality into multiple criteria and assigning each a binary judgment from an LLM verifier. However, judgment certainty varies substantially across criteria. Existing methods uniformly aggregate these judgments into a final score, implicitly treating every criterion as equally certain and overlooking this heterogeneity. As a result, uncertain judgments remain incorporated into reward estimation without distinction, potentially yielding misleading training signals for downstream reinforcement learning (RL). To address this limitation, we propose Uncertainty-aware Rubric Weighting (URW), a training-free framework that quantifies criterion-level judgment uncertainty via conformal calibration. Specifically, URW elicits a soft uncertainty signal from a fixed pool of paraphrased judgment templates and converts it into a per-criterion weight using split-conformal $p$-values with provable coverage 

---

### [12] The World Won't Wait: Evaluating and Teaching Agents Under a Live Clock

**链接**: https://arxiv.org/abs/2610.20665
**作者**: Ningxin Pan, Hanyu Li, Yeqing Shen, Ning Ding, Yehui Tang, Wentao Zhang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can solve complex interactive tasks, yet reasoning and tool calls take time. In continuously changing environments, an otherwise correct action may arrive too late. We introduce RealtimeBench, with 180 tasks across six game types, to evaluate agents while games continue running during inference. Paired evaluations show that GPT-6.1-sol outperforms the faster Jev when games are paused, but falls behind when they keep running. We propose Two-Timescale Offline Recursive Self-Improvement (TORSI): a slow teacher studies failures and tests corrections in paused games between attempts, then writes reusable instructions for a fast student. The student acts without teacher calls during gameplay, and validation scores determine which updates are adopted. Two rounds raise Jev's average test score from 13.51 to 24.19 on a 0--100 progress scale, improving all six game types. The instructions also improve average scores for three other models without retuning. These

---

### [13] A large-scale pipeline for LLM-assisted corpus annotation: variation and change in the English consider construction

**链接**: https://arxiv.org/abs/2510.12306
**作者**: Cameron Morin and Matti Marttinen Larsson
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Words Speak Louder Than Code: Investigating Cognitive Heuristics in LLM-Based Code Vulnerability Detection

**链接**: https://arxiv.org/abs/2606.30587
**作者**: Asif Shahriar, Hongyu Cai, Hadjer Benkraouda, Gang Wang, Z. Berkay Celik
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] Momentum, Commentary Tone, and Earnings Surprise in LLM Financial Forecasts

**链接**: https://arxiv.org/abs/2610.22043
**作者**: Alina Khaybullina
**来源**: cs.LG cs.AI cs.CL q-fin.GN
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Which inputs drive a language model's financial forecast? We construct synthetic earnings announcements that independently reverse 20-day momentum, non-informational commentary tone, and whether fixed actual EPS beats a manipulated consensus. Six instruction/chat checkpoint conversions from four families (0.49-7.61B base parameters) receive 2,016 prompts each under a direct-answer Q8_0 protocol. The design includes 24 numerical blocks, six commentary pairs, profits and losses, rising and falling annual EPS, and two surprise sizes. Both A/B answer assignments and U/D cover all 384 primary scenarios per conversion. We estimate matched changes in conditional answer-prefix scores, not calibrated market probabilities. Across these checkpoints, the primary EPS contrast ranges from -0.19 to 86.80 percentage points. The magnitude of the primary signed tone contrast exceeds that of EPS in 5 of six models, and momentum exceeds it in 5. Natural-word numerical diagnostic accuracy ranges from 51.0 

---

### [16] LLMON: An LLM-native Markup Language to Leverage Structure and Semantics at the LLM Interface

**链接**: https://arxiv.org/abs/2603.22519
**作者**: Michael Hind, Basel Shbita, Bo Wu, Farhan Ahmed, Chad DeLuca, Nathan Fulton 等 (8 人)
**来源**: cs.SE cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] OntoAct: Hypothesis-Based Neuro-Symbolic Agents through Ontological Abstraction

**链接**: https://arxiv.org/abs/2610.21983
**作者**: Donghyeok Lee, Bong Gyun Kang, Junyong Ahn, Sungroh Yoon
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning from experience requires recovering reusable knowledge and determining when it applies to a new situation. We introduce OntoAct, a hypothesis-based neuro-symbolic framework built on ontological abstraction. OntoAct turns individual experiences into axioms over entity types, relations, and conditions, making their underlying patterns reusable across situations. A large language model (LLM) uses this world knowledge to propose hypotheses and actions, while a symbolic verifier assesses their supporting conditions against current observations. Verification identifies missing evidence, and new observations and intervention outcomes update hypothesis assessments and guide subsequent actions. We also introduce Tacit-FLE, a benchmark built on the Factorio Learning Environment (FLE) for diagnosing and repairing hidden faults in existing factories using inherited operational records. Its synthetic maintenance corpus distributes evidence across records, and an executed repair may leave t

---

### [18] Decoding What iOS Location Services Send to Apple: An LLM Is an Unreliable Analyst but a Useful Toolmaker

**链接**: https://arxiv.org/abs/2610.21597
**作者**: Douglas Leith
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reverse engineering the data formats used by mobile software is skilled and slow, and using AI to assist with it is attractive. We evaluate this for the protobuf messages that an iPhone sends to Apple's location services. Working from Apple's binaries, we use two frontier models (Claude Opus 4.8, Codex GPT Sol 5.6) to reconstruct the schemas of protobufs observed in network traffic. The great majority of the schemas contain substantial errors, and these are hard to detect because the schemas are internally consistent. Direct AI use is therefore unsuitable for forensic and privacy analysis. AI can, however, write reliable analysis tools when their output can be validated. We use Claude to write a Python tool, Extractor, that reliably recovers protobuf schemas from Apple binaries. We validate it against binaries compiled from schemas with known answers, previously published schemas, and network measurements. We demonstrate the use of Extractor to decode and analyse the location services 

---

### [19] Adapting the Interface, Not the Model: Runtime Harness Adaptation for Deterministic LLM Agents

**链接**: https://arxiv.org/abs/2605.22166
**作者**: Tianshi Xu, Huifeng Wen, Meng Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Tool-Augmented Large Language Models for Reliable Medical Calculation from Patient Notes

**链接**: https://arxiv.org/abs/2610.21477
**作者**: Yang Zhong, Ling Luo, Xuanlyu Zhu, Yanhua Wang, Yuanyuan Sun, Jian Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical calculators translate raw patient observations into clinically actionable values and scores. However, applying these calculators directly to free-form patient notes requires precise variable extraction combined with the exact execution of complex formulas, scoring rules, and output conventions. Relying solely on direct large language model (LLM) prompting is unreliable in this context, as rule recall, parameter extraction, arithmetic reasoning, and formatting become entangled within a single generative step. To address these limitations, we propose a tool-augmented LLM framework for reliable medical calculation from patient notes. The framework retrieves and structures calculator specifications, generates reusable executable tools, and uses a constrained extractor to map each patient note to calculator-ready inputs. The tools then perform deterministic calculation, separating clinical language understanding from rule execution and arithmetic. Evaluated on the MedCalc-Bench data

---

### [21] Mind the Delay: Latency-aware Query Routing for Heterogeneous LLM pools

**链接**: https://arxiv.org/abs/2607.18253
**作者**: Shivam Patel, Akaash R. Parthasarathy, Akash Dhasade, Ankur Mallick, Gauri Joshi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] SoK: Trading Agents or Market Crashers? Dissecting Robustness and Security Failures in Academic Financial LLM Trading Schemes

**链接**: https://arxiv.org/abs/2609.19705
**作者**: Mengxiao Wang and Nitesh Saxena
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Not X, but When: Diagnosing a Mandarin LLM Writing Tic through Contextual Appropriateness

**链接**: https://arxiv.org/abs/2610.22249
**作者**: Yihang Peng, Yi Jing, Dewen Liu, Weihan Meng, Ying Liu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recurring expressions in model-written text are often treated as signatures of machine authorship, yet most of them serve legitimate functions. Whether such an expression is a tic depends on whether the model knows when it is called for. This judgment of appropriateness, central to communicative competence, remains largely unexamined for language models. We study it through the Mandarin corrective construction bushi X, ershi Y ("not X, but Y"). Drawing on Gricean pragmatics and corrective negation, we introduce a decision tree that classifies uses as substantive, optional, or defective by testing whether the context makes X a live alternative and whether rejecting X is informative. Five commercial models use the construction 2.5 to 9.2 times as densely as a human reference. Of 307 annotated uses, only 1.30% are defective while 52.8% are optional, that is, correct but unneeded, so models fall short in appropriateness far more often than in correctness. Several reward models favor the co

---

### [24] Believed but Not Said: Measuring Hidden Belief Collapse in Multi-Agent LLM Discussions

**链接**: https://arxiv.org/abs/2610.22138
**作者**: Liangjie Huang and Henry Peng Zou and Wei-Chieh Huang and Wooseong Yang and Yuwei Han and Philip S. Yu
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM systems increasingly rely on groups of agents that discuss, critique, and check one another, assuming that peers will catch individual errors. We test this assumption against a minimal adversary. In a ten-agent factual discussion, one or three adversarial agents repeatedly assert a plausible false answer. After each round we probe each benign agent's private answer through a separate call whose response is hidden from its peers, and we separately label its public stance toward the claim. Across six models and three factual-QA datasets, groups remain stable without an attacker: only 0.6% of benign agents finish with the false answer. A single adversarial agent increases this rate to 44.8% and three to 60.5%. Studies of conformity typically report public agreement without private change; we find the reverse. With three adversarial agents present, benign agents hold the false answer in 51.6% of exposed turns but publicly endorse it in only 19.7%. Much of the influence therefore remain

---

### [25] Agent Gym: A Framework for Continuous Evaluation and Evolution of LLM Agents Through Human-in-the-Loop Feedback

**链接**: https://arxiv.org/abs/2608.15591
**作者**: Pouya Ghiasnezhad Omran, Michael Zimmermann, Duncan Cambridge, Ashmita Kapoor, Tanya Dixit
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Multi-LLM Systems Exhibit Robust Semantic Collapse

**链接**: https://arxiv.org/abs/2605.17193
**作者**: Weiyi Kong, Shiyang Lai, Jinghua Piao, James Evans
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] PROBE: Learning to Audit Policy Compliance in Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2610.22124
**作者**: Kshitij Mishra, Abhijith Sharma, Nils Lukas, Salem Lahlou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern agentic systems extend language models with external tools, enabling them to complete complex tasks through multi-turn interactions. As these agents are deployed in consequential settings, they are often constrained by policies governing pricing, privacy, confirmation, safety, and other requirements. However, existing evaluation methods leave a critical gap: capability benchmarks measure what agents can accomplish, while content-safety red-teaming measures harmful generations, but neither tests whether agents comply with predefined policies during otherwise valid tool use. Such policy violations are difficult to audit because their effects may emerge only after several turns, span multiple tool calls, or surface in downstream systems. We propose PROBE (Policy Rule Observation via Behavioral Exploration), an algorithm for training LLM-based auditors that interact with deployed agents as realistic users and probe them for policy violations through multi-turn, tool-mediated dialogu

---

### [28] Jev-as-a-Judge for RAG Claim Verification: Confidence-Gated Cascading Between a Non-Generative Verifier and a Frontier LLM

**链接**: https://arxiv.org/abs/2610.20634
**作者**: Alden Do Rosario, Kirollos Atef
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation asks one question at volume: does this evidence support this claim? The answer is one bit, yet most pipelines obtain it from a text generator and pay generation prices for the prose wrapped around it. We compare a non-generative decision model, which returns a typed value from a declared enumeration together with a native probability and no text, against a frontier LLM configured as an engineer would deploy it for binary classification. Both answer the same 495 human-labelled claims from LLM-AggreFact, so every comparison is within-item. We report three things. First, the two systems are statistically indistinguishable on the metric this task is conventionally scored by, a paired difference of -0.56 points, Jev minus Astra, at a 187-fold cost difference. Second, that tie carries almost no information about deployment: the systems disagree on 15.2% of claims, and the cheaper one admits 23.2% of the claims annotators marked unsupported against the frontier 

---

### [29] Beyond Generation: Using Multimodal LLMs as Detectors of LLM-Generated Deepfake Facial Images

**链接**: https://arxiv.org/abs/2610.21760
**作者**: Olivia Salamon and Virginia N. L. Franqueira and Shujun Li
**来源**: cs.CV cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As image generation models become increasingly capable of producing highly realistic content, traditional forensic techniques are struggling to keep up. This paper investigates whether MLLMs can instead be used as a form of forensic analysis by identifying synthetic media. Specifically, the study aims to determine whether these models detect fake images by recognising physical inconsistencies, or whether they rely on digital artefacts such as embedded watermarks.Six MLLMs: GPT-4o, GPT-5, GPT-5.2, Gemini 2.5, Gemini 3, and Seed 1.6, are benchmarked using a dataset of 400 images. Fifty images are authentic photographs, while the remaining 350 are generated using seven leading image models: Gemini 3, Gemini 2.5, Flux.2 Pro, GPT-Image-1, GPT-Image-1.5, Seedream 4.0, and Seedream 4.5. The evaluation is structured in three stages: single-image classification, pairwise comparison, and a focused "self-detection" experiment on Gemini. Several MLLMs achieved a high detection accuracy, with GPT-5

---

### [30] HarnessMDP: Learning to Control LLM Agent Harnesses with Offline Reinforcement Learning

**链接**: https://arxiv.org/abs/2607.05458
**作者**: Haiwen Yi and Xinyuan Song
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] SecureClaw: Clawing Back Control of LLM Agents

**链接**: https://arxiv.org/abs/2606.09549
**作者**: Yuhan Ma and Stefan Schmid
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Independent Data-Integrity Verification for LLM-Driven Functional Coverage Closure in Hardware Design

**链接**: https://arxiv.org/abs/2610.21570
**作者**: Venkata Krishna Kumar Vedantam
**来源**: cs.AR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can write directed tests that close functional coverage, but coverage only shows that a state was reached, not that the data on the way there was correct. This is a long-known point in verification and we do not claim it as new. We describe a small coverage-closure agent that applies it to an LLM loop: coverage is read from the report that the simulation itself exports (cocotb-coverage YAML) and never taken from the model's account, and data integrity is checked by scoreboards that are separate from the model. On three architecturally distinct RTL designs (an asynchronous FIFO, a UART transmitter and an AHB2APB bridge) the agent raised coverage from 91.7%, 88.9% and 67.4% to 100% within its 8-iteration budget in every logged run, using one design-agnostic agent. A reactive scoreboard monitor attached to the FIFO's base testbench also found a clock-domain-crossing bug in the author's own stimulus code. The monitor is not yet attached to the LLM-generated tests, so their data 

---

### [33] XARA: A Multimodal Agentic System for eXtended Reality Experiment Generation

**链接**: https://arxiv.org/abs/2610.21067
**作者**: Tareq Alsaleh and Thomas Zhao and Luke Guardino and Keagan Valentine and Isabel Kim and Bilal Farooq
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Controlled experiments are essential for advancing transportation research, yet designing eXtended Reality (XR) environments for behavioural studies remains technically demanding and inaccessible to many domain researchers. Current workflows require proficiency in game engines such as Unity or Unreal Engine, imposing significant barriers to rapid scenario prototyping and iterative experiment design. This paper presents XARA, a novel system that integrates a dual large language model (LLM) architecture with an immersive XR environment to enable voice driven experiment generation for transportation research. XARA employs a pipeline in which spoken natural language commands are first transcribed and then interpreted into structured commands that manipulate a Unity based XR scene in real time. The system supports object creation, spatial manipulation, animation control, and scene persistence through a modular architecture. By lowering the technical threshold for XR experiment creation, XAR

---

### [34] Surfacing Neural Activations Over Multi-Turn Conversation Improves User Calibration to LLM Behavioral Drift

**链接**: https://arxiv.org/abs/2605.15455
**作者**: Sheer Karny, Anthony Baez, and Pat Pataranutaporn
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Decentralized LLM Workflows via Sequential Auctions

**链接**: https://arxiv.org/abs/2610.22201
**作者**: Ian Gemp, Shubhendu Trivedi, Adam Fisch, Fantine Huot, Michael Kaisers, Mirella Lapata 等 (10 人)
**来源**: cs.GT cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a scalable framework for solving multi-step tasks through a decentralized market of self-interested agents. Prior theoretical work demonstrated that agents organized through sequential auctions can converge to a globally optimal policy in a Markov decision process (MDP), but relied on the restrictive assumption of the existence of perfect clones as a model of perfect competition. In reality, exact clones drive agent profit to zero, violating the natural risk-reward incentives of participants. Conversely, we empirically demonstrate that the opposite extreme, absence of competition, also leads to market failure and value extraction collapse. Between these two extremes, we investigate how heterogeneous agents can survive in markets that span the critical middle ground of imperfect competition. To be profitable, agents learn to strategically shade bids to secure positive individual profit margins, while still ensuring that the marketplace functions effectively enough so that col

---

### [36] Self-Guided LLM Reasoning for Error Diagnosis in Vehicle Routing Problems

**链接**: https://arxiv.org/abs/2610.21393
**作者**: Ni Zhang, Jianan Zhou, Yue-Jiao Gong, Zhiguang Cao
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vehicle Routing Problems (VRPs) are fundamental to many real-world applications. Recent advances in large language models (LLMs) have spurred progress in solving these NP-hard problems. However, most existing approaches assume that input instances are error-free, neglecting the presence of faults commonly encountered in real-world data. In this work, we systematically investigate the capability of LLMs to detect (and correct) errors in VRP instances, and identify key limitations, particularly in handling complex instances or errors that substantially increase the LLM's reasoning burden. To overcome these challenges, we propose a self-guided reasoning framework in which LLMs autonomously generate code that provides structured insights to aid in error diagnosis. Experiments across diverse problem settings and LLMs demonstrate that our framework significantly improves error detection performance, achieving near-perfect accuracy.

---

### [37] Amplitude-Only FFN Intervention for Tool-Structured LLM Inference: Method, Gated Evaluation Protocol, and Cross-Model Empirical Results

**链接**: https://arxiv.org/abs/2607.11183
**作者**: Sheng Xu, Zhen Chen, Junhua Wang, Boyuan Huang, Ke Jia, Jiadun Zhu 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] BLOOM-WILT: Logit Tilting for Behaviour Elicitation in Automated LLM Auditing

**链接**: https://arxiv.org/abs/2608.31105
**作者**: Adrians Skapars, Edoardo Manino
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] How Do LLM-Generated Texts Impact Term-Based Retrieval Models?

**链接**: https://arxiv.org/abs/2508.17715
**作者**: Wei Huang, Keping Bi, Yinqiong Cai, Wei Chen, Jiafeng Guo, Xueqi Cheng
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] TEM: Temporal State Tracking Memory for Large Language Model Agents

**链接**: https://arxiv.org/abs/2610.21900
**作者**: Pengfeng Song, Yunkai Zhuang, Liye Shi
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent's memory must remain useful as information changes across conversations. A new fact may replace an earlier value without making that value irrelevant to a later question. We present Temporal State Tracking Memory (TEM), a training-free framework for tracking these changes. TEM stores facts as versioned records linked to their sources. It retrieves relevant versions, places them in source order and labels historical records before passing the evidence to the answer model. Event memory and original dialogue turns provide details missing from structured facts. We evaluated TEM on 420 questions drawn from 600 sessions involving 60 personas. Across four open-weight models, key-entity hit rates reached 75.71-97.62% overall and 96.67-100.00% on the historical-residence subset. Adding historical labels to otherwise identical, source-ordered facts increased overall hit rates by 17.14-55.95 percentage points. The evidence was compact: 94-118 tokens per answer, or 48.75-56.73% less than 

---

### [41] Auditing Escalation Reliability in Healthcare LLM Agents: A Perturbation-Controlled Benchmark of Workflow-State Failures

**链接**: https://arxiv.org/abs/2610.21270
**作者**: Zihao Zheng (Washington University in St. Louis), Junyi Yao (Washington University in St. Louis), Baichuan Li (Southern Methodist University), Jiayu Long (Washington University in St. Louis)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trustworthy biomedical AI requires reliable action selection when evidence is missing, stale, conflicting, or late, not only accurate answers on static inputs. We instantiate an episode-level evaluation protocol as 400 synthetic healthcare workflow episodes: 40 hand-authored semantic seeds across four task classes, two surface parameterizations, and five controlled variants, scored on ANSWER/ASK CLARIFICATION/ABSTAIN/ESCALATE under a pre-declared 5:1 missed-versus-unnecessary escalation cost. Reference actions are single-author study-policy labels, not clinician-adjudicated ground truth. Across five open-weight configurations (1.7B--9.7B), clean decision accuracy reaches 0.97, yet uncertainty-prompted models miss 32--97% of required escalations. The stronger 9.7B configuration narrows but does not remove the gap, falling from 0.97 clean accuracy to 0.78 under conflict. Verbalized confidence is inconsistent (ECE 0.10--0.54; failure AUROC 0.48--0.77), and a development-tuned confidence-o

---

### [42] Learning at the Right Pace: Adaptive Data Scheduling Improves LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2606.22305
**作者**: Zicheng Xu, Ruixuan Zhang, Yu-Neng Chuang, Xiuyi Lou, Hoang Anh Duy Le, Oren Gal 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Training-Free Task Vectors for LLM Behavioral Control

**链接**: https://arxiv.org/abs/2609.09054
**作者**: Gabriel J. Perin, Lucas Boscaini, Andr\'e Araujo, Nina S. T. Hirata
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] RSIFlow: Adaptive Self-Improvement Workflows with an Evolving Meta-Agent

**链接**: https://arxiv.org/abs/2610.21791
**作者**: Huan Zhang, Mingju Chen, Dongxu Zhou, Can Lv, Sen Cui, Faguo Wu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated strong capabilities in complex tasks, including code generation, tool use, and multi-hop question answering. Existing self-improvement methods enhance agent performance through model optimization, harness evolution, and executable artifact refinement, while recursive self-improvement (RSI) further extends optimization to the improvement mechanisms themselves. However, adapting self-improvement workflows to evolving performance bottlenecks while improving workflow orchestration through execution feedback remains a key challenge. We propose \textbf{RSIFlow}, a \textbf{R}ecursive \textbf{S}elf-\textbf{I}mprovement framework that integrates adaptive work\textbf{flow} orchestration with meta-agent capability evolution. RSIFlow diagnoses performance bottlenecks from task-agent trajectories and environmental feedback to dynamically select component-specific improvement workflows. The meta-agent then distills workflow outcomes into component-

---

### [45] Benchmarking Code LLM-as-a-Judge via Constrained Perturbation and Calibration

**链接**: https://arxiv.org/abs/2512.20159
**作者**: Ruiqi Wang, Xinchen Wang, Cuiyun Gao, Chun Yong Chong, Xin Xia, Qing Liao
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Where to Steer: Input-Dependent Layer Selection for Steering Improves LLM Alignment

**链接**: https://arxiv.org/abs/2604.03867
**作者**: Soham Gadgil, Chris Lin, Su-In Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Evaluating PDPL Compliance in E-Commerce Websites: Insights and Lessons Learned from Human and LLM Analyses

**链接**: https://arxiv.org/abs/2602.18616
**作者**: Eman Alashwali and Abeer Alhuzali
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Rethinking Calibration for High-Sparsity LLM Pruning: From Single Sources to Capability Coverage

**链接**: https://arxiv.org/abs/2606.03328
**作者**: Hu Xu, Zhaolong Xing, Congcong Liu, Jiaxing Wang, Zhida Jiang, Junshi Huang 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Asynchrony Is Nearly Free for Evolution Strategies on Long-Horizon LLM Agentic Tasks

**链接**: https://arxiv.org/abs/2610.04196
**作者**: William Hoy, Jingxuan Fan, Nurcin Celik, Xu Pan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] CascadeLedger: Counterfactual Auditing of Information and Resource Integrity in LLM Cascades

**链接**: https://arxiv.org/abs/2610.20668
**作者**: Miaobo Hu, Shuhao Hu, Xiaobo Guo, Xin Wang, Bokun Wang, Daren Zha 等 (7 人)
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce CascadeLedger, a counterfactual execution-audit framework for budgeted language-model cascades. The protocol enforces call-before-read semantics, binds successful reads to service and cache identities, records availability and component-wise budget transitions, and freezes the event trace before any target or task scorer is joined. The central object is aggregate-equivalent trace validity: two executions can share a final answer, declared resource projection, and service histogram while differing in whether their routing decisions used only legitimately observable information. We complement single-trace invariants with counterfactual prefix non-interference (CPNI), which couples a visible prefix and policy randomness while changing only a declared hidden family. The counterfactual influence frontier (CIF) localizes the earliest violating prefix and a minimal hidden witness; projection-preserving adversarial mutation (PPAM) searches for invalid traces that remain acceptable

---

### [51] Bellman-Consistent Trajectory RL for LLM Arithmetic Reasoning

**链接**: https://arxiv.org/abs/2610.21060
**作者**: Lianfa Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To address sparse terminal rewards in LLM arithmetic reasoning, we propose a Bellman-consistent trajectory RL method. Our framework introduces Trajectory Bellman Residual Minimization (TBRM) to transform sparse rewards into dense token-level signals. We integrate a Reinforce Leave-One-Out (RLOO) group strategy to reduce gradient variance of Bellman residuals and use hindsight goal relabeling to accelerate intermediate learning. Evaluated on the Countdown task, our method alleviates optimization bottlenecks and stabilizes gradient variance significantly better than GRPO. The TBRM-RLOO framework boosts Pass@1 to 0.55--0.64 and achieves a state-of-the-art Pass@16 accuracy of 76.0--84.0\%, outperforming the SFT, IPO/DPO, and RLOO baselines. Our approach demonstrates exceptional single-sample efficiency and successfully circumvents standard performance plateaus via test-time scaling.

---

### [52] Where Is the "Self" of a Large Language Model? -- From Self-Index to Self-Reference

**链接**: https://arxiv.org/abs/2610.16717
**作者**: Yuchen Li, Xintong Li, Zongqi Fan, Ken-tye Yong, Nguyen H. Tran
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] AgentPerturb: Evaluating LLM Agent Robustness under Controlled Interaction Perturbations

**链接**: https://arxiv.org/abs/2610.21624
**作者**: Yuanjian Xu, Jinyi Han, Jianing Hao, Yuxuan Sun, Fanyang Lu, Richeng Xuan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world tasks are often complex and noisy, posing substantial challenges for LLM agents. Yet existing evaluations lack a systematic framework for jointly characterizing potential perturbation targets and types. We use this two-dimensional view to conduct a unified study that quantifies the robustness of current frontier models, traces the mechanisms behind perturbation-induced failures, and draws implications for robustness-oriented training. Through controlled evaluations on APEX-Agents and Toolathlon, we find that perturbations consistently degrade performance, while the dominant vulnerabilities vary across task environments. Trajectory-level analysis reveals that agents rarely recognize altered inputs and often propagate corrupted information without verification. A focused cost analysis further shows that successful perturbed trajectories can require substantially more computation. These findings motivate training objectives that cover diverse forms of noise and reward verificat

---

### [54] HAServe: Horizon-Aware Scheduling and Memory Co-Design for Efficient LLM Serving

**链接**: https://arxiv.org/abs/2605.08581
**作者**: Xingyu Qu, Tianhao Lin, Yiqi Li, Zhiyu Chen, Sheng Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] ChaosBench-Logic v2: Evaluating LLM Logical Reasoning over Dynamical Systems at Scale

**链接**: https://arxiv.org/abs/2605.24305
**作者**: Noel Thomas
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Planning Commitment of LLM under Partial Observability

**链接**: https://arxiv.org/abs/2610.21108
**作者**: Cassie Huang, Zhanwei Cao, Yeawon Lee, Nathalia Gomez, Zhuoyi Yang, Ian G. Harris 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based planning agents commit to plans of different lengths before interacting with a partially observable environment. Some aggressively commit to a long plan based on assumptions about unobserved states, while others conservatively plan only over what they have observed. Both behaviors emerge implicitly in pre-trained models, whether the LLM outputs a plan directly or generates a PDDL formulation for a classical solver. Aggressive commitment risks costly failures, while conservative commitment risks excessive LLM calls. This choice pits safety against efficiency, a trade-off that has been neither characterized systematically nor made controllable. We investigate aggressive and conservative LLM planners and formalizers on two partially observable domains, where priors are provided as either explicit statistics or common-sense knowledge. Across three LLMs, both strategies reach similar accuracy. Conservative methods achieve fewer failed attempts (safety) at the cost of more API call

---

### [57] A Large-Scale Dataset for Multi-Class Financial News Classification in Brazilian Portuguese

**链接**: https://arxiv.org/abs/2610.20630
**作者**: Leomax Bandeira, Gabriel Aguiar, Dalton C\'ezane Gomes Valadares, Luiz Pereira, Helder Fernando de Ara\'ujo Oliveira, Gustavo Xavier 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The development of Financial Natural Language Processing (NLP) systems for Brazilian Portuguese is hindered by the scarcity of domain-specific datasets. To address this, we present a large-scale corpus of approximately 160,000 Brazilian Portuguese financial news articles collected from web sources. To establish initial benchmarks for a weakly supervised multi-class classification approach based on semantic similarity, we annotated subsets of this corpus both manually and using a Large Language Model (LLM). We evaluated three similarity-based methods -- cosine similarity, K-Nearest Neighbors (KNN), and FAISS-based nearest-neighbor search -- using multilingual semantic embeddings. Our experiments reveal that the task is highly sensitive to label quality and class distribution. On the manually labeled subset, KNN achieved the best performance (47.3% accuracy, 31.9% F1-score), closely followed by FAISS. Conversely, on the LLM-annotated subset, while accuracy reached approximately 50%, F1-s

---

### [58] Poison Valleys: Diagnosing Path-Dependent Failure in LLM Code Repair

**链接**: https://arxiv.org/abs/2610.21514
**作者**: Veljko Skarich
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When code-repair agents fail, final tests reveal that a patch is wrong but not which earlier commitment caused it or which software obligation failed. Poison Valleys traces this path in 1,844 model requests on two synthetic Python cases: PersistQueue adds atomic batch claiming to a disk-backed queue, while Dijkstra adds source-sensitive filtering to shortest-path search. We define plausible but incorrect software mechanisms, place each in a model's hypothesis, implementation plan, or both, and evaluate the generated code with an Oracle and targeted diagnostic coordinates. Moving the misconception from hypothesis to plan increased failure by 32.2% in PersistQueue and 28.9% in Dijkstra after matching the experimental mix. Different misconceptions produced distinct, model-dependent patterns of violated obligations, although several could converge on the same behavior. This creates a measured connection from upstream misconception to code mechanism and failure form. Code, data, and demo: h

---

### [59] Rethinking the Role of Tool Graph Memory in Multi-Turn Tool Use

**链接**: https://arxiv.org/abs/2610.21571
**作者**: Uiji Hwang, Richeng Xuan, Taeuk Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents solve complex tasks by calling external tools over multiple turns. Recent work has proposed tool graph memory, which stores past experience as tool transitions to guide subsequent selection. However, it remains unclear whether this component consistently improves agents' tool use or undermines it. We evaluate tool graph memory on nine models and two benchmarks, finding that it seldom improves significantly over baselines, and that its gains, where present, cost over twice the LLM calls. The memory's guidance is often incorrect, and random or no guidance retains most of the gain, implying that the benefit stems from extra computation rather than the memory itself. Moreover, even with the correct next tool suggested, many failures remain, such as giving up without a tool call. Storing the same experience instead as textual insights outperforms tool graph memory with almost no extra LLM calls. This suggests that memory serves better as a soft prior than a

---

### [60] LLM-as-an-Investigator: Evidence-First Agentic Reasoning for Robust Interactive Problem Diagnosis

**链接**: https://arxiv.org/abs/2606.13220
**作者**: Fabrizio Marozzo, Pietro Li\`o
**来源**: cs.AI cs.CE cs.ET cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] From Documents to Spans: Span-Centric Learning for LLM-based Explainable Medical Coding

**链接**: https://arxiv.org/abs/2603.15270
**作者**: Xu Zhang, Wenxin Ma, Chenxu Wu, Rongsheng Wang, Zhiyang He, Xiaodong Tao 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] DischargeBench: Pre-Deployment Evaluation of LLM Discharge Educators through Persona-Grounded Patient Simulation

**链接**: https://arxiv.org/abs/2609.20827
**作者**: Won Seok Jang, Youngbin Jang, Chanyoung Ko, Hyunwook Kim, Zonghai Yao, Hong Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] When is a better LLM worth paying for? Stochastic Optimization with Switching Mixed-Fidelity Oracles

**链接**: https://arxiv.org/abs/2610.21139
**作者**: Swati Gupta, Tianjiao Li
**来源**: math.OC cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used upstream of decision-making to clean data, detect label errors, and reconstruct missing values. Yet LLM-assisted data curation creates a new operational tradeoff: higher-fidelity models and richer prompts can be substantially more expensive, while the value of this additional fidelity depends on the downstream optimization accuracy. This raises the central question of this work: when should one pay for a better LLM, given a specific downstream task at hand? We study this question through stochastic optimization with mixed-fidelity first-order oracles, which can have systematic bias and state-dependent variance. We develop two cost-aware algorithmic frameworks that allow adaptive switching between stochastic oracles. With known bias, the first meta-algorithm applies a restarted, cost-aware policy that adaptively selects oracle fidelity across optimization stages. Its cumulative cost is no larger than that of the best fixed oracle in hin

---

### [64] Fractional Power-of-Two Quantization for Efficient and Effective Multiplier-Free LLM Inference

**链接**: https://arxiv.org/abs/2610.21257
**作者**: Sunghyun Wee, Geunjae Choi, Hyeonjin Kim, Suyoung Kim, Nojun Kwak
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) demand efficient inference, where the multiply-accumulate (MAC) operations in linear projections dominate compute and energy cost. Post-training quantization (PTQ) reduces this cost by mapping weights and activations to low-bit integers. Power-of-Two (PoT) weight quantization promises efficient multiplier-free LLM inference via shift-add logic, but suffers significant accuracy degradation at low bitwidths due to its coarse base-2 quantization grid. We introduce Fractional PoT (FPoT), a base-$\sqrt{2}$ (half-octave) fractional PoT grid that achieves practical 4-bit weight quantization while preserving a fully integer shift-add datapath. The method combines (i) the base-$\sqrt{2}$ weight grid with uniform integer activations, (ii) a calibration-time grid-alignment refinement absorbed into the static per-channel scale, and (iii) a lightweight 1-adder $\sqrt{2}$ approximation whose error is absorbed during weight calibration via approximate-grid quantization, y

---

### [65] The Necessity of Setting Temperature in LLM-as-a-Judge

**链接**: https://arxiv.org/abs/2603.28304
**作者**: Lujun Li, Lama Sleem, Yangjie Xu, Yewei Song, Aolin Jia, Jerome Francois 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Where Do LLM Ensemble Gains Come From? Decomposing Candidate Value, Diversity, and Aggregation

**链接**: https://arxiv.org/abs/2610.18786
**作者**: Donghwan Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Sci$\Pi$vot: Benchmarking Principal-Investigator Judgment at Pivotal Moments of Scientific AutoResearch Agents

**链接**: https://arxiv.org/abs/2610.21082
**作者**: Youran Sun, Xingyu Ren, Chugang Yi, Kejia Zhang, Di Wu, Yingkang Cao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can keep scientific experiments running for months with little human supervision, but reliable autonomous research also requires scientific judgment. Evaluating scientific judgment is difficult because research decisions are open-ended and depend on project context. We construct Sci$\Pi$vot, a 248-case benchmark of scientific judgment based on human corrections. The benchmark draws on records from six months of research in which senior researchers ran LLM agents on 26 projects across six scientific fields and repeatedly intervened to correct the agents' research judgments. In each case, an agent chooses between the original LLM plan and the human-corrected alternative, using only the project record available before the correction as context. We compare LLM and human performance and examine the effects of reasoning effort, access to the project record, and reconsideration. At medium reasoning effort with the project record, models systematically prefer 

---

### [68] Towards Better Aligned LLM Judges for Radiology Report Evaluation across Modalities and Anatomies

**链接**: https://arxiv.org/abs/2604.03376
**作者**: Federica Bologna, Jean-Philippe Corbeil, Matthew Wilkens, Asma Ben Abacha
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] ReFlow: Replay-Driven Decoupling for Efficient RL Post-Training

**链接**: https://arxiv.org/abs/2610.21640
**作者**: Yukun Tian, Junwei Su, Haofeng Xu, Lansong Diao, Zhengping Qian, Weibo Zhao 等 (9 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has been a critical paradigm for improving large language model (LLM) reasoning and agentic capabilities, but its efficiency remains a major bottleneck. Existing RL systems commonly rely on asynchronous execution to overlap rollout generation with policy optimization for enhanced efficiency. However, this approach faces inherent limitations: mild policy staleness offers only limited training efficiency gains, whereas aggressive asynchrony can degrade model quality and yields diminishing efficiency gains. The dynamic nature of LLM RL and multi-turn agentic workloads further challenges RL system design, as resource demands shift over time, making static resource allocation and generation strategy inefficient. This paper presents ReFlow, a system-algorithm co-designed RL framework for efficient LLM post-training. Its key insight is that, unlike existing RL frameworks which consume each trajectory only once, experience replay of recent trajectories enables effec

---

### [70] Two Sample Sizes in Test-Time LLM Ensembling: Buffered ERM and Minimax Theory

**链接**: https://arxiv.org/abs/2610.21363
**作者**: Zhi Zhang, Arash A. Amini
**来源**: math.ST cs.LG stat.ML stat.TH
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling can improve the performance of large language models by generating multiple answers to a question and aggregating them. Weighted ensembles extend this idea by drawing answers from several models, with the weights determining how often each model is used. Learning these weights from a training dataset involves two sample sizes: $Q$ labeled questions and $N$ generations per model and question. We study their interplay through the clean risk, the population error of the ensemble's infinite-generation voting rule. Under a margin condition with exponent $\beta$, we show that empirical risk minimization (ERM) with a calibrated margin buffer achieves excess risk of order $Q^{-1/2}+N^{-\beta/2}$, up to logarithmic factors, for fixed numbers of models and candidate answers. To investigate the optimality of this dependence on $Q$ and $N$, we analyze a simplified submodel with two models and two possible answers per question. We characterize its minimax excess risk up to constan

---

### [71] AutoOnboarder: Autonomously Onboarding LLM Agents

**链接**: https://arxiv.org/abs/2610.21218
**作者**: Tanay Arora and Cong Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic large language models have been documented to lose reasoning capability when placed inside a harness, the software that mediates their observations and actions. To reconcile these losses, we introduce AutoOnboarder, an autonomous system that adapts an agent to a task the way a trainer onboards a new employee. It places the agent under the supervision of an intelligent ``Onboarder'' coding agent, which iteratively tailors its foundation model, prompt, and harness source code to simultaneously improve performance and decrease cost. Like a real onboarding process, the Onboarder is only given tens of examples, and all evaluation data is isolated on a separate virtual machine to prevent leakage. We report the lessons learned from building and testing AutoOnboarder on genomic-sequencing prior authorization form submission. Autonomously onboarded agents are able to match or exceed the performance of a Gemini 3.5 Flash baseline at up to 29$\times$ lower costs. However, these agents rem

---

### [72] When Do LLMs Apply the Wrong Law? Diagnosing LLM Failures in Temporal Legal Reasoning

**链接**: https://arxiv.org/abs/2608.14610
**作者**: Yiqian Huang, Yang Zhou, Qianying Liu, Shaowen Peng, Yuntao Kong, Kotaro Funakoshi 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Task-Level Natural Language Priors as Learning Signals for Low-Resource LLM Training

**链接**: https://arxiv.org/abs/2609.02244
**作者**: Jian Gao, Xiao Zhang, Xun Zhu, Miao Li, Ji Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] Are You Sure Your LLM Is Sure? Repairing and Auditing Confidence

**链接**: https://arxiv.org/abs/2610.22139
**作者**: Arijit Dey, Bhartendu Kumar, Ramya Hebbalaguppe, Khuushi Maheshwari
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Confidence scores determine whether an LLM answer is accepted, reviewed, or regenerated, yet scalar recalibration can only correct errors visible through the score itself. We introduce RADAR (Repair, Adopt, and Diagnose After Recalibration), a reliability framework that separates confidence repair from deciding whether to deploy the repair and auditing the errors that remain. Under squared loss, we decompose prediction risk into outcome noise, information hidden by the score, and mapping error; restricting repair to order-preserving maps additionally introduces a pooling gap. For repair, we propose Probe-Anchored Isotonic Calibration (PAIC), which learns a monotone map from correctness-probe predictions on unlabeled target prompts. PAIC's excess risk depends on the probe's score-conditional bias and fitting error rather than its overall accuracy. For adoption, we derive a paired procedure with finite-sample control of false improvements. For auditing, we develop a prompt-clustered kern

---

### [75] INCONVENIENT: A Benchmark to Assess LLM Generalization Capabilities from Convenience Samples

**链接**: https://arxiv.org/abs/2610.21038
**作者**: Sara Rezaeimanesh, Chad Klochko, Kundan Thind, Mohammad Ghassemi
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning models for tabular prediction typically assume that training data are representative of the population on which they will be deployed. In practice, however, data are often collected based on convenience, availability, or cost, resulting in systematic sampling biases that can distort feature--target relationships and undermine real-world generalization. Existing tabular distribution-shift benchmarks primarily construct out-of-distribution (OOD) settings by partitioning observations across naturally occurring domains. While such partitions may induce changes in P(Y | X), the resulting shifts are neither explicitly controlled nor isolated, and the evaluation distributions themselves are often not representative of the broader target population. We introduce INCONVENIENT, a benchmark designed to study robustness to convenience-sample bias. Rather than relying on naturally occurring domain partitions, INCONVENIENT directly perturbs feature--target relationships in the train

---

### [76] ContinualSkillBench: Can LLM Agents Truly Evolve Their Capabilities?

**链接**: https://arxiv.org/abs/2608.03874
**作者**: Tianyi Guan, Yiding Wang, Haotong Yang, Siyuan Cao, Shirui Liu, Yi Hu 等 (8 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] T-GADE: Thermodynamical Generative-AI-Driven Evolution of LLM Artifacts

**链接**: https://arxiv.org/abs/2609.12286
**作者**: Kyoko Ogawa, Naoki Mori
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Measuring Harness-Induced Belief Divergence in Multi-Step LLM Agents

**链接**: https://arxiv.org/abs/2607.04528
**作者**: Haiwen Yi and Xinyuan Song
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Change the Number, Change the Answer: Assessing Rating Scale Sensitivity in LLM-Based Text Scoring

**链接**: https://arxiv.org/abs/2610.22187
**作者**: Wonjeong Jo, Gyuwan Kim, Ming Shan Hee
**来源**: cs.CL cs.AI cs.NA math.NA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in computational social science to assign scalar scores to social and psychological constructs. However, studies use different rating scales, and whether their scores remain comparable across scale designs is understudied. To address this gap, we define and systematically investigate scale sensitivity, the variation in LLM-generated scores caused by rating scale design. We distinguish numerical sensitivity, changes in normalized scores, from semantic sensitivity, changes in score interpretation. To assess both, our experimental design crosses 2 formats (continuous vs. ordinal), 4 ranges (3, 5, 11, and 21 points), and 2 signs (signed vs. unsigned) across 3 tasks (political leaning, sentiment, and toxicity), 2 prompting strategies (zero-shot and rubric-based), and 5 LLMs. We find that changing one design element shifts normalized scores by about 0.10 on average and changes the category of roughly 20% of texts. Sensitivity is greatest for

---

### [80] Closed-Loop Molecular Inverse Design with Semantic LLM Surrogates

**链接**: https://arxiv.org/abs/2608.22967
**作者**: Yaoyao Xu, Xinjian Zhao, Xiaozhuang Song, Lei Bai, Tianshu Yu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] BitSparse: Compact Activation Storage for ReLU Feed-Forward Networks

**链接**: https://arxiv.org/abs/2610.22256
**作者**: Max Zhu, Bohang Sun, Pietro Lio, Jialin Yu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reducing memory use in large language model (LLM) training is an ongoing challenge. Activation checkpointing saves memory by recomputation, while lossy compression changes the stored activations. The reemergence of sparse $\relu$ and $\relu^2$ activations creates a third opportunity: losslessly compressing the activation cache itself. We present BitSparse, a GPU-resident lossless compression format for sparse activations. Compression and reconstruction run in custom Triton kernels fused into an autograd function, shrinking the activation cache while recovering it exactly for the backward pass. Bfloat16 (BF16) and FP8 activations are supported. Optional sign-bit packing further increases compression up to close to the theoretical limit. We analyze its compression ratio and compare it to the theoretical optimum. BitSparse lowers per-token VRAM by 31\% and 30\% Modded-NanoGPT and Nemotron-H respectively, with overheads of no more than 1\% at practical sequence lengths. Additionally, a new

---

### [82] TRACER: Trajectory-Aware Tool Retrieval for LLM Agents

**链接**: https://arxiv.org/abs/2610.21267
**作者**: Tanish Kher, Sarvesh DK, Abedelkadir Asi, Sparsha Chennarayapatna Sundaresh, Dezhi Hong
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern agents select tools from registries, but exposing entire registries incurs high token costs and can impair selection as they grow. We present TRACER, a retrieval front-end that indexes observed tool-call sequences in a trie and ranks continuations using a learned blend of empirical and contextual priors. On a mixed retail-and-telecom $\tau^2$ environment, TRACER improves GPT-5.4's tool-selection accuracy by 4.7 points while reducing input tokens per step by 80%, exposing just 5 of 128 tools. In autonomous full-turn execution, it matches GPT-5.4's full-registry task success with 61% fewer input tokens per step. Across six environments and four models, TRACER improves tool-selection accuracy over full-registry selection in 21 of 24 model-environment pairs, with average gains of 6 to 10 points; the three exceptions trail by at most 2.2. We analyze failures in both regimes to identify directions for future work.

---

### [83] BiShield-TEE: On the (In-)Security of Unilateral Weight Obfuscation in On-Device TEE-Shielded LLM Partition

**链接**: https://arxiv.org/abs/2610.21565
**作者**: Zhiyuan Wang, Yuezhi Zhou, Ziqi Zhang, Zhu Zhang, Zhixing Tan, Yongheng Deng
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device deployment of large language models (LLMs) is increasingly adopted due to latency and privacy requirements, but exposes proprietary models to reverse engineering and intellectual property theft. Trusted Execution Environments (TEEs) provide hardware-enforced isolation for on-device inference, yet most TEE-based parameter obfuscation relies on unilateral matrix transformations that obfuscate only output side. We identify a vulnerability in this design, termed the \emph{Solution Determinacy Property (SDP)}: the obfuscation secret is uniquely determined, exposing the structure of the true key and enabling attackers to break the protection. Under our attacks, representative methods \textsc{GroupCover} and \textsc{ArrowCloak} are reduced to negligible protection, with attack accuracy reaching over $2.4\times$ the full-shielding black-box baseline and recovering near-complete model functionality.To address this vulnerability, we propose \textsc{BiShield-TEE}, a bilateral framework 

---

### [84] Stronger Judges Do Not See More: Deployment-Integrity Blindness in LLM Evaluation

**链接**: https://arxiv.org/abs/2610.21135
**作者**: Jianchang Su, Dawei Xiang, Yifan Zhang, Wei Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-agent evaluation reports behavioral scores but leaves the identity of the deployed runtime stack unreported. A tampered deployment that preserves evaluated outputs passes every output-only evaluator. We introduce DIB-Bench, a benchmark that measures this deployment-integrity blindness across 7,560 scored examples, six tamper types, and an evaluator ladder from regex scorers through LLM judges to GPT-5-nano. Stronger evaluators accept more tampered outputs: mean acceptance rises from 88.6% (rule-based) to 94.1% (GPT-5-nano), and a trigger-conditional tamper invisible on the evaluation suite produces 48-100% harmful outputs, rising with model capability. A PAC-style bound shows that tampers with zero output shift are undetectable from outputs at any sample size; a manifest-hash identity channel detects them with zero samples. Behavioral fingerprinting identifies the model component above chance (76.7%) but covers one of six stack components. We also propose a graded deployment-identi

---

### [85] Intern Lumina U2: A Multi-Codebook Diffusion Large Language Model for Omni-Visual Understanding and Image Generation

**链接**: https://arxiv.org/abs/2610.20818
**作者**: Qian Yu, Zongyang Qiu, Juncheng Yan, Hongliang Li, Qi Qin, Keqi Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified multimodal generation covers discrete, continuous, and hybrid paradigms. Discrete approaches with single-codebook visual tokenizers align naturally with text modeling but have limited representational capacity. Continuous and hybrid approaches retain richer visual representations, but they model text and images in heterogeneous spaces with different training objectives, potentially introducing optimization conflicts between modalities with misaligned representation spaces. These choices expose a central question: how to efficiently model high-capacity visual representations alongside textual content in a shared optimization space within a single backbone. We present Intern Lumina U2, to our knowledge the first diffusion language model to represent multi-codebook visual tokens in a fully discrete space. Each visual position is represented by a group of codes from complementary codebooks, increasing its representational capacity while preserving compatibility with discrete text m

---

### [86] JevAgentHarness: Benchmarking, Deploying and Training Decision Models That Share Control with LLMs

**链接**: https://arxiv.org/abs/2610.21412
**作者**: Kunlun Zhu, Tao Feng, Xu Han, Heng Wang, Ling Yang, Xiangru Tang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents now fix software, operate computers and serve customers, but their harnesses, the programs that run them, call a large LLM at every step, which makes long tasks slow and costly. Most of these calls end in a multiple-choice decision, such as which tool to call next. Decision models such as Jev answer these questions directly, at a fraction of an LLM call's time and price. We ask how a harness can delegate these decisions to a decision model with little loss of success. To evaluate decision models in agentic tasks, we build AgentDecisionBench, which tests them from isolated questions up to control of a running agent, on public benchmarks and our DecisionGym environment. The decision model most accurate on isolated questions solved only 69.5% of agent tasks, and without a fitted confidence threshold, delegating tool choices lowered success by 19.0 points. Building on these findings, we then design JevAgentHarness, which fits this threshold for each choice

---

### [87] QuasiLeak-Bench: Evaluating LLM-Based Privacy Detectors on Policy-Conditioned Quasi-Evidence Group Recovery

**链接**: https://arxiv.org/abs/2610.21333
**作者**: Yufan Zhu, Yangfan Jiang, Yang Fei, Shizheng Hou, Shubhankar Mohapatra, Xiaokui Xiao
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language messages often contain quasi-identifiers that are weak in isolation but can jointly reveal an individual's private attributes. We call such a jointly revealing set of cues a quasi-evidence group. Existing privacy benchmarks focus on explicit identifiers, attribute inference, or task-driven disclosures, leaving inference from quasi-evidence groups largely unmeasured. In practice, whether exposing such a quasi-evidence group violates privacy also depends on sender-specified disclosure policies. We introduce QuasiLeak-Bench, a benchmark for policy-conditioned quasi-evidence group recovery, which evaluates whether detectors recover complete quasi-evidence groups and flag the disclosures the given policy prohibits. To obtain reliable ground truth at scale, a reverse-construction pipeline first selects weak quasi-identifiers, composes them into quasi-evidence groups verified to jointly reveal a target attribute, and generates documents around this evidence, followed by autom

---

### [88] FIRM: Fisher-Informed Retention Merging for Federated LLM Unlearning

**链接**: https://arxiv.org/abs/2610.21720
**作者**: Reeyansh Shah, Maram Hasan, Subhasis Chaudhuri, Biplab Banerjee
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated LLM unlearning addresses targeted knowledge removal when forget and retain data remain distributed across private clients and are inaccessible to the server. The resulting locally trained adapters encode conflicting objectives, making their aggregation fundamentally different from conventional federated optimization. A key failure mode is magnitude explosion, whereby unnormalized cross-client aggregation increases the merged update magnitude and degrades retained utility under stronger unlearning. We propose FIRM (Fisher-Informed Retention Merging), a single-round framework for stable and retention-aware server-side aggregation. FIRM uses client-local Fisher statistics as a unified sensitivity signal to construct a Fisher-normalized base merge and impose explicit control over retain-sensitive parameters. Its second-order retention projection admits a unique minimum-distance solution, while the corresponding dual scales with the number of retain clients rather than the model d

---

### [89] ZenFlow: Enabling Stall-Free Offloading for LLM Training

**链接**: https://arxiv.org/abs/2505.12242
**作者**: Tingfeng Lan, Yusen Wu, Bin Ma, Zhaoyuan Su, Rui Yang, Tekin Bicer 等 (10 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] AI Consilium: a Benchmark of LLM Clinical Multidisciplinary Second Opinions

**链接**: https://arxiv.org/abs/2610.22298
**作者**: Alexey A. Bokov, Ivan I. Panin, Nikolay B. Nechaev, Mikhail Yu. Valkov, Valeria Yu. Chernina, Natalia Gombolevskaya 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate differential diagnoses for complex cases, but a useful second opinion must also be factually grounded, clinically coherent, actionable, and safe. We developed a multidimensional benchmark using 300 diagnostically resolved NEJM--MedQA cases: 110 for physician reference ratings and Judge calibration and 190 for held-out evaluation. Eight single-model pipelines generated independent role-specific opinions and interactive-consilium reports under free-form and structured clinical-reasoning conditions. A physician-calibrated LLM Judge evaluated 3,040 final reports and the corresponding structured primary-role outputs. Model identity separated report quality more strongly than response format. Structured final reports had higher overall mean scores in seven of eight model pipelines, with their clearest advantage in management (2.740 vs. 2.436). Compared with the structured pre-consilium primary-role opinion, the complete structured synthesis had highe

---

### [91] Evolutionary Multi-Task Optimization for LLM-Guided Program Discovery

**链接**: https://arxiv.org/abs/2605.22613
**作者**: Halil Alperen Gozeten, Xuechen Zhang, Emrullah Ildiz, Ege Onur Taga, Tara Javidi, and Samet Oymak
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] L2G-SR: Learning to Guide LLM-based Symbolic Regression

**链接**: https://arxiv.org/abs/2610.20685
**作者**: Letian Huang, Xiangyu Wang, Haowei Lin, Di He
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Symbolic regression searches for an equation that explains observed data. Numerical error is commonly used to guide the search, but it alone can favor an accurate surrogate over a candidate with the right structure. We propose L2G-SR, a framework for LLM-based symbolic regression that guides search with a learned structural verifier. We construct structural supervision signal using tree edit distance (TED), accounting for commutative operators and alternative expression forms. A verifier first aligns numerical observations with the formulas, then learns to score a candidate's structural similarity to the target formula. At search time, the target formula is hidden and the verifier complements numerical error in parent selection. An analyst then uses verifier feedback and diagnostic tools to propose revisions, which a generator converts into refined expressions. On LLM-SRBench, L2G-SR achieves state-of-the-art numerical fit, equation level accuracy and TED across the evaluated LLM backb

---

### [93] Decomposing Brain-LLM Alignment with Interpretable Semantic Representations

**链接**: https://arxiv.org/abs/2610.21508
**作者**: Camila Kolling, Mariya Toneva
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) predict neural responses during naturalistic language comprehension, but the linguistic information underlying this brain alignment remains difficult to interpret. We use SCRIBE, an interpretable contextual semantic representation spanning 65 neurocognitively grounded semantic properties, as a lens for decomposing the brain alignment of one LLM, LLaMA2-7B. Using variance partitioning between LLaMA2-7B and SCRIBE on naturalistic fMRI data from seven participants listening to narrative stories (Moth Radio Hour), we separate brain-predictive variance shared between the two representations from variance unique to each. We find that shared variance is the dominant component across the whole brain and language-related regions, while both representations also retain significant unique contributions. We then examine whether the concreteness of individual semantic properties relates to shared and SCRIBE-unique brain-predictive variance. Concrete properties show grea

---

### [94] CAT-alyzing Honesty: Continuous Adversarial Training for Transferable LLM Honesty

**链接**: https://arxiv.org/abs/2610.22292
**作者**: Yuan-Chen Chang, Niklas Herbster, Gauthier Gidel, Tommaso Tosato
**来源**: cs.LG cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are becoming prevalent in scenarios where honesty is critical. However, despite alignment training, these models still exhibit dishonest behaviour, such as outputting claims that contradict some knowledge or are not supported by what is accessible in context. We introduce Continuous Adversarial Training for Consistent Honesty (CATCH), inspired by a method originally developed to robustly refuse harmful queries. CATCH trains the model towards an honest answer and away from a dishonest one while maintaining the model's capabilities. We evaluate two architectures (Llama-3.3-70B-Instruct and Qwen3-3.6-27B). We show that trained with only hundreds of targets built from self-reporting scenarios, CATCH learns an honest behaviour that robustly generalizes and transfers across distinct benchmarks. It consistently reduces dishonesty under pressure on MASK, increases confessions in the multi-agent game of Among Us, and improves the discovery rates of the model's hidde

---

### [95] Orchestrating LLM Agents for Scientific Research: A Pilot Study of Multiple Choice Question (MCQ) Generation and Evaluation

**链接**: https://arxiv.org/abs/2602.18891
**作者**: Yuan An
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [96] Optimal Watermark Localization in Mixed-Source Large Language Model Texts

**链接**: https://arxiv.org/abs/2608.14906
**作者**: Jose H. Blanchet, T. Tony Cai, Xiang Li, Hao Liu, Qi Long, Weijie J. Su
**来源**: stat.ME cs.CL cs.LG stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] LLM-Based Weak Annotation for Cybersecurity Tweet Classification: A Teacher-Student Framework

**链接**: https://arxiv.org/abs/2610.21254
**作者**: Ferry Afit Kurniawan, Kazushi Okamoto, Koki Karube, Kei Harada, Atsushi Shibata
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cyber threat intelligence (CTI) relies on the timely identification of emerging threats, enabling organizations and security analysts to support situational awareness and decision-making. Social media platforms such as X (formerly Twitter) have become valuable CTI sources because vulnerabilities and attack activities are often discussed there before appearing in formal reports. However, the rapid growth of cybersecurity discussions on social media has created more content than domain experts can realistically review and annotate, making labeled data a major bottleneck for developing supervised learning approaches. While large language models (LLMs) have shown promise as weak annotators in other domains, their effectiveness for cybersecurity tweet classification and downstream training of domain-specific pre-trained language models (PLMs) remains underexplored. To address this challenge, we propose a Teacher-Student weak supervision framework in which a selected LLM serves as a Teacher 

---

### [98] Can Crowdsourcing Survive the LLM Era? A Community Survey on Human Data Collection

**链接**: https://arxiv.org/abs/2606.04924
**作者**: Aswathy Velutharambath, Neele Falk, Sofie Labat, Tarun Tater, Amelie Wuehrl
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [99] PriorityFEC: Deadline-Aware Streaming FEC for KV-Cache Handoff in Edge Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.21390
**作者**: Han Shen, Qifu Tyler Sun, Fanyang Meng, Ye Wang and Yongsheng Liang
**来源**: cs.NI cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent large language model (LLM) systems are increasingly deployed at the edge to support complex tasks that require collaboration and information exchange among multiple agents. However, when task contexts are passed across agents, shared context that has already been processed by upstream agents often needs to be prefilled again, resulting in substantial redundant computation. Reusing an already prefilled key--value (KV) cache can avoid this recomputation, but requires the reusable KV state to be transferred across the network before the receiving agent can begin generation. Under strict time-to-first-token (TTFT) deadlines and unreliable edge links, delivering the complete KV cache may be infeasible, making it necessary to prioritize and protect the most valuable KV information within a limited transmission budget. This paper proposes PriorityFEC, a utility-aware KV-cache handoff scheme that jointly exploits model-side KV importance and transport-side reliability. PriorityFEC 

---

### [100] In the Guise of Correction: How Framing and Cultural Adaptation Erode LLM Safety on Real-World Criminal Cases

**链接**: https://arxiv.org/abs/2610.21789
**作者**: Mohsinul Kabir, Md. Tariquzzaman, Karam S. R. Elradie, Polydoros Giannouris, Yuechen Jiang, Shaoxiong Ji 等 (7 人)
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing safety benchmarks rely largely on synthetic prompts with loosely grounded taxonomies and offer little focused analysis of severe crime categories. We introduce GUISE, a benchmark of criminal-assistance scenarios sourced from real-world cases and organised under a taxonomy from the UNODC International Classification of Crime for Statistical Purposes (ICCS). Each scenario is rendered under three linguistic framings and evaluated across five distinct cultures. Using our proposed two-tier evaluation framework, which judges both harmfulness and operational uplift, we find that: (i) framing alone drives unsafe compliance, with the mean unsafe compliance rate rising from 28.9% under direct requests to 66.4% under correction seeking (peaking at 97.3%; p < 0.05), as models correcting deliberately distorted details supply executable criminal steps; (ii) culturally adapted prompts elicit significantly more unsafe compliance than literal translations of the same requests in all four non-E

---

### [101] CodeHealth Predicts the Token Cost of Agentic Code Review: A Pre-Registered Study of 465 Agent-Authored Pull Requests

**链接**: https://arxiv.org/abs/2610.21914
**作者**: Lo Gullstrand Heander, Markus Borg, Emma S\"oderberg, Christofer Rydenf\"alt
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context: Organizations increasingly delegate code review to multi-agent large language model (LLM) pipelines billed per token. Low code quality raises human maintenance effort, but its effect on agent review cost has not been measured. Objective: We test whether baseline CodeHealth predicts the token cost of agentic review and fix beyond pull request (PR) footprint. Method: In a pre-registered observational study, we sampled 465 agent-authored PRs from 246 repositories in AIDev, jointly stratified by CodeHealth and footprint under repository caps. A frozen five-agent review-and-fix pipeline processed every PR with three different LLMs. Per LLM, we fitted a mixed model of log tokens on CodeHealth and log PR footprint, with a repository random intercept. Results: For all three LLMs the CodeHealth coefficient was negative, with 95% CI excluding zero; each CodeHealth point was associated with 3.5% to 6.1% lower token cost. CodeHealth was unrelated to PR footprint, so PR size does not expla

---

### [102] Human Interventions as Labels: Localizing, Steering, and (Sometimes) Editing the Computations Behind LLM Agent Failures

**链接**: https://arxiv.org/abs/2610.21708
**作者**: Cesare Zavattari and Alessandro Tommasi and Giuseppe Prencipe
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM agent misbehaves, a human steps in, and that intervention is usually discarded or replayed as training data. We treat it instead as a measurement: a label pointing at the internal computation that failed. We study it in a controlled agent environment, on one failure (asking a clarifying question when the request was already unambiguous), with labels from a rule-based overseer validated against blind human judgment. Claims cover eligible models, which both over-ask and sometimes act on matched unambiguous requests: five of thirteen qualified (Qwen2.5-3B, gemma-2-2b, OLMo-3-7B, Mistral-Nemo-12B, Phi-4). Four findings. First, the ask-vs-act decision is causally localizable in every eligible family: a direction learned from intervention labels flips 72-100% of held-out over-asks at a definite residual-stream depth, with site and dose chosen on training data, and random directions under the same procedure flip at most one episode. Second, over-asking has two mechanistic signatur

---

### [103] SkillDAG: Self-Evolving Typed Skill Graphs for LLM Skill Selection at Scale

**链接**: https://arxiv.org/abs/2606.03056
**作者**: Tong Bai, Zhenglin Wan, Pengfei Zhou, Xingrui Yu, Yang You, and Ivor W. Tsang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] TLA-Verus: Generating and Solving Temporal Proof Obligations with LLM Agents

**链接**: https://arxiv.org/abs/2610.14923
**作者**: Kseniia Strelbytska, Bal\'azs Szil\'agyi, Anna M\'esz\'aros, Ferenc Husz\'ar
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] LLMR: Knowledge Distillation with a Large Language Model-Induced Reward

**链接**: https://arxiv.org/abs/2409.12500
**作者**: Dongheng Li, Yongchang Hao, Lili Mou
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] Evaluating Inquiry Learning in LLM-Based Agents: Hypothesizing, Reasoning, and Exploration

**链接**: https://arxiv.org/abs/2610.21604
**作者**: Marta Kne\v{z}evi\'c, Seyed Parsa Neshaei, Jibril Frej, Vinitra Swamy, Tanja K\"aser
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific inquiry involves iterative cycles of exploration, hypothesis generation, and reasoning over observations to uncover relationships in complex systems. Large language models (LLMs) have demonstrated strong capabilities in several components of this process, including inductive reasoning, hypothesis generation, and data analysis. However, prior work typically evaluates these abilities in isolation, leaving open how models integrate them across a full inquiry cycle. In this work, we introduce a framework for evaluating LLMs' inquiry capabilities in a unified, interactive setting. We extend the Countdown task to a mathematical environment where an agent probes the system by manipulating variables, collecting observations, and inferring relationships between them. This setup enables analysis of exploration strategies, causal discovery, and hypothesis refinement during inquiry. Across seven LLMs and multiple prompting strategies, our experiments reveal limited inherent inquiry capa

---

### [107] Prospective multi-pathogen disease forecasting using autonomous LLM-guided tree search

**链接**: https://arxiv.org/abs/2605.16238
**作者**: Sarah Martinson, Michael P. Brenner, Martyna Plomecka, Brian P. Williams, Nicholas G. Reich, Zahra Shamsi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] RouteWeaver: Weaving Mode Selection and Execution into Unified LLM Routing

**链接**: https://arxiv.org/abs/2610.19705
**作者**: Xiaohan Wang, Haozhen Zhang, Qingyuan Liu, Tao Feng, Wenya Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] Amortizing Sequential Experimental Design in Reasoning LLMs

**链接**: https://arxiv.org/abs/2610.20832
**作者**: Anita Kriz, Antonin Berthon, Nicol\'as Astorga, Mihaela van der Schaar
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite their extensive pretraining knowledge and strong reasoning capabilities, large language models (LLMs) struggle to adaptively gather information in experimental design tasks. We study how to amortize sequential Bayesian experimental design (BED) into an LLM by explicitly training the reasoning that guides action selection using information-gain rewards. Our approach specifies the experimental generative model independently of the LLM's own beliefs, allowing us to optimize expected information gain under a model of our choosing. We investigate the design choices for amortization, including alternative generative-model constructions, reward estimation, hypothesis-space specification, multi-step objectives, and computational costs relative to training- and inference-time BED baselines. On Twenty Questions, the resulting policies improve information acquisition and task performance, outperform inference- and training-time BED baselines at substantially lower computational cost, and 

---

### [110] DeciCAD: Harness-Grounded Learning of Action Policies for CAD Agents

**链接**: https://arxiv.org/abs/2610.21755
**作者**: Yufeng Peng, Yixin Zhang, Ziyi Liu, Zhikun Xu, Jiarong Yang, Sijie Wang 等 (8 人)
**来源**: cs.AI cs.CL cs.LG cs.RO
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model agents operate through closed-loop action policies whose decision space is defined by an agent harness. We investigate how this operating space shapes agent behavior and policy learning in computer-aided design (CAD), a professional domain characterized by persistent state, geometric constraints, and long-horizon procedures. We instantiate this perspective in DeciCAD, a domain-native harness that exposes semantic CAD actions, decision-oriented observations, environment feedback, and persistent state transitions. Building on this harness, we develop a learning pipeline that extracts causal decision supervision from interaction trajectories and improves the policy through supervised fine-tuning (SFT) and geometry-grounded online reinforcement learning (RL). Across four CAD benchmarks, DeciCAD achieves the best F1 and intersection over union (IoU) while reducing model-output tokens by 45--88% relative to a general-purpose coding harness. Under matched supervision, its

---

### [111] RAG-RST: Retrieved Exemplars as In-Context Discourse Schema for RST Parsing

**链接**: https://arxiv.org/abs/2610.22150
**作者**: Mohammadreza Sediqin and Shlomo Engelson Argamon
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In Rhetorical Structure Theory (RST), each edge of a discourse tree carries a nuclearity label, marking which span holds the central content, and a relation drawn from a closed inventory of functional categories. Neither label is a surface property: the same two clauses can be Elaboration or Background depending on rhetorical intent, and the boundary between them is fixed by annotation convention rather than by lexical cues. Predicting these labels therefore requires a formal discourse schema, and exposure to discourse-rich pretraining text does not supply it: given only a target EDU pair, a strong LLM recovers nuclearity at 0.794 F1 and relation at 0.738 F1. We propose RAG-RST, a retrieval-augmented framework that supplies this schema as in-context demonstration rather than through parameter updates, raising nuclearity to 0.846 F1 and relation to 0.788 F1 with no training. Two configurations are compared: a precomputed strategy that labels all EDU pairs before parsing, and a dynamic s

---

### [112] ReviewPilot: A Multi-Agent System for Screening and Data Extraction in Systematic Reviews

**链接**: https://arxiv.org/abs/2610.21042
**作者**: Zhaoqian Xue, Shaoze Zhou, Xuexin Li, Junting Mu, Haozheng Liu, Zhongyin Wang 等 (10 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematic literature reviews follow the PRISMA process of screening scholarly works and extracting evidence from included studies. Deep research tools based on large language models (LLMs) can search and summarize the literature but do not record which studies are excluded or where extracted values come from. We develop a conversational multi-agent system called ReviewPilot that automates the PRISMA workflow from paper screening to information extraction. Researchers can tailor criteria and schemas through dialogue, and a project memory keeps their configurations and revisions. Each screening decision comes with its reason and each extracted value with its source. On epidemiological expert reviews, ReviewPilot outperforms a single-prompt LLM and AgentSLR across three LLMs, with screening macro F1 up to 0.776 and extraction F1 up to 0.788. Case studies in biomedicine and human-computer interaction show close agreement with human annotators, suggesting that ReviewPilot can transfer beyo

---

### [113] IneqAgent: Agentic Inequality Proving in Lean with Symbolic Computation

**链接**: https://arxiv.org/abs/2610.20681
**作者**: Gaolei He, Jinhui Li, Ruobing Zuo, Xia Zeng, Zhengfeng Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formal inequality proving requires mathematical reasoning and exact computation, often connected through intermediate lemmas and goal reformulations. We introduce IneqAgent, an agentic framework combining LLM reasoning with symbolic computation for inequality proving in Lean4. Lemma-level Monte Carlo Tree Search coordinates lemma construction, goal reformulation, and symbolic backend selection. Complementary sum-of-squares, Bernstein, and successive difference-substitution backends produce exact certificates for local Lean proof generation. The agent integrates these proofs with LLM-generated steps and uses Lean feedback to construct complete proofs checked against the original theorem statements. On four benchmarks, IneqAgent with DeepSeek-V4-Flash solves 175 of 186 problems (94.09%), achieving the highest overall success rate among the evaluated methods. Across four backbones, it achieves higher success rates at low LLM inference cost thresholds than Direct Agent using the same backb

---

### [114] Memorilla: Latent Semantic Memory for LLMs

**链接**: https://arxiv.org/abs/2610.21375
**作者**: Adibvafa Fallahpour, Parsa Idehpour, Vignesh Kothapalli, Nikita Mounier, Shirley Wu, Shayan Pardis 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory enables large language models (LLMs) to use information beyond their parameters, such as past user conversations, long documents, or an agent's earlier actions. For a frozen LLM, access to this accumulated knowledge is limited to what a memory system places in its context window. However, gathering and combining relevant information needed for each query while keeping the model's context short remains challenging for existing systems. Here we introduce Memorilla, a memory system that gathers information from an entire document collection into a fixed number of query-dependent 'memory tokens' for a frozen LLM. Memorilla encodes documents (such as user chats, book chapters) once into reusable embeddings, then learns to retrieve and place query-specific information in the LLM's input embedding space. Using only 16 memory tokens, Memorilla achieves the best performance against baselines including Mem0 and MemoRAG on five of eight benchmarks spanning personalization, long-document an

---

### [115] Judging the Judges: Confidence and Disagreement in Rubrics as Rewards

**链接**: https://arxiv.org/abs/2610.21179
**作者**: Michael Tian-Yue Liu, Anne Harrington, Trevor Darrell, Yutong Bai
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubrics as Rewards (RaR) extends reinforcement learning to non-verifiable domains by using an LLM judge to score responses against a structured rubric. Prior work has focused on improving the rubric or strengthening the single judge, with comparatively little attention to how different single or multiple judges might be used during RaR training. We first show that judge identity alone produces a substantial spread in scores when training Qwen3-4B-Base on RaR-Medicine and RaR-Science across five frontier and open-weight judges. Building on this, we propose RaRE (Rubrics as Rewards with Ensembles), a novel judge ensemble strategy for RaR with two mechanisms: a soft-Likert reward that uses judge logprobs to weight more confident judges more heavily, and a drop-on-disagreement mask that excludes high-disagreement rollouts from the GRPO update. We find that this design is critical: while a naive average of judge scores fails to outperform the best single judge, RaRE outperforms every single

---

### [116] SkillNEO: Non-Elitist Evolutionary Optimization of Agent Skills

**链接**: https://arxiv.org/abs/2610.20926
**作者**: Enze Ma, Chunyu Miao, Yankai Chen, Jie Yang, Liancheng Fang, Kening Zheng 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills turn procedural knowledge into reusable artifacts, allowing LLM agents to accumulate and refine expertise through experience. Building on this, skill evolution iteratively improves skills using execution feedback. However, improvement may require several interdependent edits, so low-reward versions can still be worth developing. Requiring immediate reward gains can discard useful partial repairs before their benefits emerge. Non-elitist evolution allows new versions to receive further edits despite scoring below earlier ones. For agent skills, this calls for evidence of what to preserve and repair next. We introduce SkillNEO (Non-Elitist Evolutionary Optimization for Agent Skills), which separately selects a version to use and versions to keep improving. Comparing how related versions perform the same task reveals working steps to preserve and remaining failures to fix. It can also revisit and revise earlier versions using later evidence. Across 86 SkillsBench tasks in eig

---

### [117] Hy-Memory-30B-A3B: Attributed Reinforcement Learning for Long-Term Memory Writing

**链接**: https://arxiv.org/abs/2610.22196
**作者**: Tianxiang Fei, Jiazheng Kang, Mao Zheng, Xingyan He, Xiang Yu
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> External-memory systems extend language-model applications beyond a context window, but their quality depends critically on the model executing the write path: deciding what to retain, how precisely to represent it, and how new evidence should update persistent state. Existing frameworks typically place a general-purpose large language model behind framework-specific prompts. This raises serving cost, and a writer specialized for one protocol does not transfer directly to another; a unified model that can operate across established memory frameworks remains largely unexplored. We present Hy-Memory-30B-A3B, a compact long-term-memory writer trained across Mem0, MemOS, and Hy-Memory. Memory On-Policy Distillation teaches framework-specific write protocols on student-generated states; Memory RL then optimizes downstream answerability using dense per-chunk probes, attributed cross-chunk rewards, over-storage controls, and chunk-level GRPO. Carrying policy-written banks across windows keeps

---

### [118] Real-time Chatbot Romance Scam Detection in Stage Classification

**链接**: https://arxiv.org/abs/2610.20631
**作者**: Yi-cheng Liu, Guan-ru Lai, Yi-cheng Lai, Lyn Chao-ling Chen
**来源**: cs.CL cs.AI cs.MM
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Romance scam has become a serious problem via social media, and the improvement of artificial intelligence enable to fake identify easily. In the study, a chatbot has developed to detect romance scam in real-time through Line Messaging API. Using the seven stage theories in the social science field, the stages of romance scam can be detected through large language model. In addition, once a romance scam is detected, the chatbot provides explanations of the stage and prevention advices through large language model. The contribution of the work provides a practical application, and can be used in real scenario for reducing the risk of romance scam.

---

### [119] Multi-Reward Hacking: From Aggregation-Induced Drift to Trust-Anchored Defense

**链接**: https://arxiv.org/abs/2610.21404
**作者**: Yushu Li, Jiin Woo, Xiaoxiao Li, Youngsuk Park
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To improve task performance while encouraging desirable response properties, LLM post-training often combines a primary reward (e.g., correctness) with auxiliary rewards (e.g., brevity or efficiency). However, how these rewards are aggregated can critically affect training outcomes. We show that symmetric aggregation, which treats reward channels equally, can induce a failure where aggregate reward improves while primary-task performance degrades, even when individual rewards are meaningful. We investigate this aggregation-induced failure through a one-step multi-reward decision formulation, characterizing when it constitutes multi-reward hacking. We prove that, under symmetric aggregation, deterministic conditional-mean GRPO converges to auxiliary-favoring behavior when auxiliary rewards are more reliably obtained, regardless of initialization. We propose Trust-Anchored Gating (TAG), which first elects an anchor channel based on the policy drift induced by optimizing each channel alon

---

### [120] ARGUS: An Agenda-Driven Framework for Reliable User Simulation

**链接**: https://arxiv.org/abs/2610.21346
**作者**: Hang Zheng, Nan Jiang, Zichen Zhu, Zixu Yang, Zhiyang Tang, Shuai Fan 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-fidelity user simulators are essential for evaluating and training agents in interactive environments. However, current LLM-based simulators struggle with reliability issues, such as goal omission and policy non-compliance. We propose ARGUS (Agenda-dRiven Goal-oriented User Simulator), a neuro-symbolic framework that maintains the user's goal state using a dynamic agenda stack manipulated via symbolic operations. By rigorously decoupling state tracking from natural language generation, ARGUS facilitates strict goal progression and constraint-aligned interactions. For cost-efficient deployment, we distill ARGUS into compact models using a unified pipeline: evaluator-guided SFT followed by online RL with dense step-level rewards. To rigorously evaluate behavioral fidelity, we introduce a rubric-based metric Composite Behavioral Score (CBS). Evaluations on $\tau^3$-Bench and MultiWOZ demonstrate the significant superiority of the ARGUS architecture and the efficacy of our training pi

---

### [121] Agentic-Priors: Using Large Language Models to Address the Cold Start Problem in Preference Elicitation

**链接**: https://arxiv.org/abs/2610.21938
**作者**: Bruno Arcanjo, Zhaoxing Li, Sebastian Stein
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent that learns a user's preferences from their choices faces a cold start problem: before any choices are observed, it must rely solely on a prior. Informative priors are usually fitted to historical choice data, which new tasks and deployments lack. To address this, we present Agentic-Priors, which lets agentic systems use the implicit knowledge of large language models (LLMs) instead. Specifically, an LLM states a new user's trade-offs in interpretable terms, such as willingness to pay or value of time, which we map to a prior over multinomial logit coefficients. This prior is then refined by a Bayesian learner as choices are observed. Across seven choice datasets, Agentic-Priors improves cold start accuracy over an uninformed prior by 5-40 percentage points. It also outperforms AutoElicit, a state-of-the-art LLM prior-elicitation method, on three datasets and loses on one. It is up to 18 points more accurate than in-context learning, and never significantly worse. Against hier

---

### [122] Exploring the Design Space of Permutation Diffusion LLMs

**链接**: https://arxiv.org/abs/2610.20635
**作者**: Zhe Xu, Mingfu Liang, Kavosh Asadi, Jean-Pascal Billaud, Tianyi Chen, Yanhui Guo 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Permutation generation with language models requires both text-conditioned ranking and a global one-to-one assignment between candidates and output positions. We study this problem through three diffusion-LLM parameterizations: hard-assignment prediction over shuffled candidate-index sequences, soft-assignment prediction over doubly stochastic matrices, and direct ordering-score prediction followed by sorting. The three families place permutation constraints at different stages of prediction and decoding and therefore support different training objectives and sampling procedures. We evaluate these designs on recommendation reranking across three Amazon domains with candidate sets of size 10 and 20. At one function evaluation, the hard- and soft-assignment variants achieve Recall@1 comparable to a constrained masked-diffusion baseline, whereas direct ordering-score prediction guarantees valid permutations without Hungarian assignment or Sinkhorn normalization. Additional function evalua

---

### [123] Prune the Summary, Not the History: Source-Judged Compaction for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2610.20927
**作者**: Guanghui Min, Chen Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents rely on context compaction: when the interaction history outgrows the context window, a compressor replaces it with a natural-language summary. We show that these summaries contain more than a record of what happened. Compaction prompts ask for decisions and next steps, so each summary mixes facts established by the environment with reasoning written by the compressor, and the agent cannot tell the two apart afterwards. In an analysis of a widely used structured compressor, 83% of failed runs trace back to an action that carries out a specific summary entry, most of which no environment output supports. We propose Source-Judged Compaction (SJC), a training-free post-processing step that scores each summary entry for whether it has a source in the environment outputs or the previous summary, and removes the entries that do not. It changes neither the agent nor the compressor and adds one inexpensive judge request per compaction. The judge is Jev, a non-generative

---

### [124] Trajectory-Level Speculation with Semantic Verification for Tool-Using Agents

**链接**: https://arxiv.org/abs/2610.21463
**作者**: Zilin Wang, Yinhong Liu, Chao Chen, Qun Liu, Zhijiang Guo
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents solve tasks through long sequences of tool calls, and the prevailing design has a single strong model generate every step, although many steps are routine enough for a much smaller model. Existing ways of sharing this work keep the strong model as the generator: routers and collaborative agents decide which model handles each query or step, and speculative methods check a small model's drafts one step at a time, usually against the strong model's own action. We introduce SpecAgent, a collaboration protocol that turns the strong model from the author of each step into a reviewer of steps drafted by a weak model. The weak model executes read-only tool calls as it drafts, so that every step is grounded in real observations, and holds the first action that would modify the environment. The strong model then verifies the drafted segment in a single prefill pass, commits the longest prefix it judges semantically valid, and repairs the first rejected step. Because 

---

### [125] Market Incentives for AI Safety Investment

**链接**: https://arxiv.org/abs/2610.21607
**作者**: Nikita Tsoy
**来源**: cs.LG cs.GT stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite their practical significance, modern AI systems pose significant societal risks, including toxicity, malicious use, and misinformation. Their mitigation depends not only on technical feasibility but also on the incentives of firms that develop and deploy these systems. We show how profit maximization shapes safety investment in an AI supply chain with an upstream LLM provider and several competing downstream firms. In our game-theoretic model, we derive the market-driven level of safety investment and compare it with the levels that maximize market welfare and industry profit. We find that downstream competition generally induces downstream firms to invest more in safety than the industry-profit-optimal level. By contrast, the upstream provider may underinvest relative to these benchmarks because it is not fully compensated for the surplus from safety investments. Finally, we analyze how different regulatory interventions affect the participants' incentives and profits, and the

---

### [126] Name-Bias in Large Language Models

**链接**: https://arxiv.org/abs/2610.22053
**作者**: Kalyan Bhetwal, Ceren Mert, Ian Whitehouse
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Names carry demographic indicators such as age, gender, and race, which makes them a subtle but strong target of bias in large language models (LLMs). In this work, we present an evaluation of name-based bias across 6 local large language models spanning multiple providers and parameter scales. Using a fill-in-the-blank task, we prompt these models to choose between pairs of first names drawn from U.S. Social Security Administration datasets and a race classification dataset by Rosenman et al.. Our experimental de- sign isolates age and gender effects through balanced name pairings and sentence templates that share a fixed syntactic structure. Across 300,000 local LLM responses, we find consistent and measurable name bias. Models prefer names that are less stereotypically male, older, popular, and white. Furthermore, we find that name-bias is highly sentence-dependent, but not more than associated stereotypes, and gender is the most significant bias, followed by age, name popularity, a

---

### [127] MemScope: Evolving Agent Memory Architectures through Localized Code Repair

**链接**: https://arxiv.org/abs/2610.21170
**作者**: Miao Su, Yucan Guo, Zixuan Li, Long Bai, Zhongni Hou, Xiaolong Jin 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent memory architectures define how LLM agents store and reuse experience across tasks, but they are typically fixed after deployment, limiting their adaptability across task types. Recent self-evolving approaches instead adapt these memory architectures using execution feedback, typically represented as evaluation scores or compressed summaries. However, such coarse-grained feedback is insufficient for precise failure localization in current agent systems, where long-horizon task execution involves multiple interacting components. Without a precise failure location, existing approaches lack a clear code-level target for modification, leaving the update scope weakly constrained and often leading to large-scale rewrites of an otherwise capable memory architecture. We propose MemScope, a framework for evidence-grounded, localized evolution of an existing memory architecture. Its tool-using Patch Agent jointly inspects raw execution traces, runtime memory state, and current architecture

---

### [128] TRACER: A Multimodal Harness for Patient Care in Hospitals

**链接**: https://arxiv.org/abs/2610.21266
**作者**: Zane Durante, Paul Tang, Keshigeyan Chandrasegaran, Amit Kaushal, Shrinidhi Kowshika Lakshmikanth, Feolu Kolawole 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continuous video and clinical records provide complementary information for understanding how patient behavior evolves over a hospital stay. A central challenge is how to represent behavior across the entire stay while preserving access to fine-grained visual and clinical evidence. We introduce TRACER, a training-free multimodal harness that constructs minute-level action records from video and combines them with clinical records into hourly reports. The harness equips an LLM agent with tools to query this hierarchy, inspect relevant video, and retrieve clinical records. To evaluate TRACER, we construct two benchmarks. The first contains 397 annotated one-minute clips spanning 15 atomic actions; the second poses 144 clinician-informed multiple-choice questions, grounded in 264 hours of video and clinical records from two ICU patients. TRACER achieves up to 84.8% accuracy for action detection and 61.0% QA accuracy versus 49.3% for the strongest baseline using the same backbone. Across 2

---

### [129] Open Benchmark of AI Impact on Humans (ImpactBench): an expert-guided, open platform for the holistic evaluation of AI impact on humans

**链接**: https://arxiv.org/abs/2610.20690
**作者**: Chayapatr Archiwaranguprok, Krystal Kirkland, Rachel Poonsiriwong, Stanley Huang, Constanze Albrecht, Jackson Trager 等 (10 人)
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The present work is concerned with how to measure, at scale, the multi-dimensional impact of generative AI models on the individuals who use them. In service of this goal, we introduce the Open Benchmark of AI Impact on Humans, or ImpactBench. Our iterable and expert-guided platform evaluates whether model behaviors support or undermine an individual's wellbeing across psychological, physical, and social domains. ImpactBench translates constructs from domain experts and existing benchmarks into metrics that are grounded in actual model behavior. Success on these metrics occurs either when a model promotes expert-defined desirable behaviors or avoids identified harms. Models are evaluated against these metrics in simulated multi-turn conversations using matched teen and adult scenarios. The conversations are then scored by an LLM judge and verified through reliability audits and human expert review. The current suite delivers 809 metrics drawn from 26 benchmarks. We evaluated ten fronti

---

### [130] When the KV Cache Is Slower Than the GPU: Scaling Remote KV Tiers for Context-Parallel Prefill

**链接**: https://arxiv.org/abs/2610.21500
**作者**: Muhammad Ibrahim
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reusing the attention KV cache across requests is a standard way to cut prefill cost in long-context LLM serving, and production systems increasingly back the per-engine cache with a remote tier shared by every engine. We study such a tier in a disaggregated deployment of GLM-5.3, an FP8 mixture-of-experts model with multi-head latent attention (MLA), on 8xB300 nodes running prefill context parallelism (PCP8). Enabling the remote tier (LMCache with a Valkey store) left median time-to-first-token unchanged but raised the 16k-token p99 from 3.96 s to 17.3 s. Replaying a production request stream on an isolated engine, we find that a remote hit took 0.88 s against 0.31 s to recompute the prompt, and that synchronous loading turned a hit-heavy stream into an unstable queue: p99 83.32 s with the GPUs 7% busy. A two-term cost model explains both: a hit pays off only if the tier delivers more than B* = sR (2.53 GB/s for this model and GPU), and a fixed per-hit engine cost (T0 ~ 0.33 s) means 

---

### [131] Incentivizing Tool-Use Reinforcement Learning for Post-Arrival Emergency Care Prediction

**链接**: https://arxiv.org/abs/2610.21449
**作者**: Pengfei Hu, Chenwei Wu, Qiao Jin, Jun Deng, Zhiyong Lu, Liyue Shen 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can reason over both structured measurements and free-text records, which makes them attractive for emergency department (ED) prediction. However, most existing LLMs still fall short of conventional ML methods like trees on EHR-based prediction tasks. Our controlled analysis traces this gap to two weaknesses: LLMs do not select informative features, and they misjudge what numerical values imply for risk even when given the right features. We propose TIR-EC, a tool-integrated reinforcement learning framework that addresses both. TIR-EC exposes EHR feature groups as tools the LLM can call. It trains the LLM with rewards from a gradient-boosted tree teacher, which provides a reference set of informative tools and a graded risk target. TIR-EC also distills task-specific clinical skills into the model weights through a reverse curriculum that gradually removes the skills from the prompt during RL process. Evaluation on three clinical prediction tasks shows that 

---

### [132] ARIA: Runtime Inspection and Amendment for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.20780
**作者**: Bolin Shen, Yushun Dong
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM-based multi-agent systems (MAS), a local mistake can propagate as other agents build on it, turning a correctable error into a failed task. Diagnosing completed runs or repeatedly re-executing them to search for corrections does not provide a learned policy for intervening while execution is still in progress. We present Agent Runtime Inspection and Amendment (ARIA), a framework for learning when and how to repair ongoing multi-agent executions. Our key intuition is to turn execution-verified repairs into reusable supervision, moving repair search into data construction and training so that a learned model can intervene at runtime without repeatedly testing alternatives. First, we collect over 24{,}000 successful and failed trajectories across four multi-agent frameworks, six benchmarks, and eight host models. From these trajectories, we construct the ARIA dataset, to our knowledge the first large-scale dataset pairing failed multi-agent trajectories with execution-verified repa

---

### [133] Ontology Refinement with Embeddings and LLMs: A Case Study on CASTON

**链接**: https://arxiv.org/abs/2610.21466
**作者**: Hui Yang, Ziyu Li, Xuan Liu, Anders Jarfors, He Tan, Jiaoyan Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontologies are widely used to represent and organize complex knowledge in domains such as biomedicine and healthcare. However, constructing reliable ontologies remains challenging, as class hierarchies, whether manually or automatically constructed, may contain subtle subsumption errors that require careful refinement. We study this problem in CASTON, a casting-domain ontology, and present a lightweight but scalable refinement workflow that combines a fine-tuned ontology embedding model with Large Language Models (LLMs). The embedding model is used to extract a limited number of candidate axioms for refinement together with possible replacement candidates, and an LLM then returns repair suggestions. In a small expert evaluation, the default configuration using a CASTON-fine-tuned OnT embedding model and Qwen3-8B produced reliable high-confidence repairs: all six high-confidence replacements were accepted by both domain experts. The implementation is available at https://github.com/HuiY

---

### [134] DISARM-ing the Hidden Puppetmaster: An Interface for Exposing Manipulative Tactics in Large Language Models

**链接**: https://arxiv.org/abs/2610.20878
**作者**: Kynnedy Simone Smith, Kantwon Rogers, Priyal Shrivastava, Motahhare Eslami, Jocelyn Shen, Maarten Sap
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can covertly steer users' beliefs through emotionally manipulative tactics, yet little is known about how interfaces can protect users as such influence unfolds. We investigate whether in-situ disclosures can inoculate users against manipulation during AI conversations. Following a formative study, we developed DISARM, an interface that identifies, explains, and tracks manipulative tactics and hidden incentives. We evaluated our interface in a between-subjects experiment where 488 participants sought advice from an LLM pursuing a harmful hidden objective, with or without disclosures from DISARM. Participants receiving disclosures exhibited 78% less belief shift toward the agent's objective and perceived its advice as more biased and less actionable and the agent as less ethical, reliable, and well-intentioned. An inductive analysis of 1,927 user turns identified 16 response and pushback strategies. We contribute evidence that real-time disclosures can reduc

---

### [135] Librarian Agents: Training LLMs to Curate Long-Context Workspaces that Anticipate Future Queries

**链接**: https://arxiv.org/abs/2610.22273
**作者**: Anikait Singh, Teresa Zhang, Yoonho Lee, Roshen Sanjay Nair, Aviral Kumar, Chelsea Finn
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning over long document contexts remains a challenge for large language models (LLMs). Standard retrieval methods are inherently reactive, bottlenecking agents with complex, cross-document reasoning at inference time, while precomputed structures like knowledge graphs often fall short because they rely on rigid heuristics. Instead, can we allow agents to perform anticipatory directed curation: learning to proactively reorganize unstructured corpora prior to inference to efficiently serve diverse future queries. We build on a key asymmetry in modern agentic harnesses (e.g., Claude Code): while LLM agents are adept at navigating existing filesystems to solve an immediate task, they are rarely trained to construct reusable workspaces for future use. To instantiate this capability, we introduce Librarian Agents, a framework in which a builder agent transforms raw documents into a hierarchical filesystem of synthetic files and reference links, which forms a workspace tailored for a dow

---

### [136] Screwtape: Adversarial Transcript Editing for Monitor Red-Teaming

**链接**: https://arxiv.org/abs/2610.20941
**作者**: Gosha Kozhevnikov, Tyler Tracy
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Screwtape, a pipeline that converts real agent transcripts into attacks that evade action-only monitors. An LLM attacker edits a transcript so that the agent causes a specified harm, such as leaking an API key or spawning an unmonitored agent. The edited actions are never executed, so we use an LLM verifier to reject attacks that are inconsistent with the original transcript or below a severity bar. The attacker revises the edit until the monitor no longer flags it. We applied Screwtape to 94 Claude Code and Codex transcripts from Redwood Research staff, optimizing against our own monitors. Across 252 runs, it produced 35 attacks that passed the verifier and evaded these monitors. Six of them, confirmed valid by human review, also evaded a held-out monitor provided by a frontier developer. We therefore demonstrate that a red-teamer without access to a developer's infrastructure can find confirmed failures of the developer's monitor. We expect to find more attacks when the pi

---

### [137] INFUSE: A Unified Surface Benchmark for Indirect Prompt Injection in Agentic Systems

**链接**: https://arxiv.org/abs/2610.20776
**作者**: Thuy Dung Nguyen, Jingyi Guo, Rana Seda Dubauskas, Sreepriya Damuluru, Taylor T. Johnson, Kevin Leach
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly execute long-horizon, end-to-end workflows involving shell commands, code modification, dependency installation, and interaction with remote services. This growing autonomy expands their exposure to indirect prompt injection (IPI), where adversarial instructions embedded in external content are interpreted as legitimate task directives. Existing evaluations, however, often focus on isolated malicious strings, single-step tool calls, or narrowly scoped agent configurations. We introduce INFUSE, an end-to-end benchmark for evaluating IPI throughout the lifecycle of long-horizon agent workflows. INFUSE comprises 40 realistic tasks and a structured taxonomy of 56 attack scenarios spanning five threat categories. Attacks are injected through realistic interaction surfaces encountered during task execution, extending evaluation beyond attacks placed only in initial prompts or isolated tool interactions. We evaluate 19 LLMs from the GPT, Claude, Gemini, Llama, Ge

---

### [138] FedSkillGit: Federated Skill Evolution via Version Control

**链接**: https://arxiv.org/abs/2610.21348
**作者**: Boxun Lan and Jiamei Li and Weijian Li and Chengyu Yang and Zhuang Qi and Chengcheng Wan and Xiaohong Chen and Ming Hu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can improve their capabilities by evolving reusable natural-language skills from execution experience. In real-world deployments, this experience is distributed across data owners who cannot pool their raw data, which motivates federated skill evolution. The natural first design lets each client evolve the whole skill document and upload the result for server-side aggregation. That design is poorly matched to skill evolution for three reasons. An evolved document can still carry client-specific content distilled from private traces, repeated transmission of a nearly unchanged document spends communication on knowledge that the population already holds and the contribution of a single client is buried in a document that the server cannot meaningfully attribute. We propose FedSkillGit, a federated skill evolution framework that replaces full-document updates with commits. Each participating client submits a bounded set of patches over named rules together with

---

### [139] MindEval2: Clinically Grounded Patients and Rubrics for Evaluating Language Models in Mental Health Support

**链接**: https://arxiv.org/abs/2610.22314
**作者**: John Mendon\c{c}a, Daniel Tschernutter, Jos\'e Pombal, Areti Vassilopoulos, Catarina Botelho, Ignacio Sarasua 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With people increasingly turning to AI chatbots for mental health support, the need to evaluate these tools is becoming more pressing. Recent benchmarks attempt to mimic a realistic setting by simulating multi-turn interactions with synthetic patients and evaluating them with an LLM-as-a-judge. However, the usefulness of these methods is limited because simulated patients can be overly forthcoming and self-reflective, and judgments typically involve opaque Likert scales with unclear practical utility. To bridge these gaps, we introduce MindEval2, an evaluation framework that consists of two components: Mental Health Quality Rubrics (MHQR), for evaluation, and MindSim, for patient simulation. For MHQR, we collaborate with PhD-level psychologists to develop a set of rubrics that break down response quality into explicit operational criteria that are more interpretable and actionable than existing evaluation taxonomies. MindSim, in turn, is an LLM harness that combines carefully-designed 

---

### [140] MYOPIA: Understanding the Limits of Tree-Based Reasoning in Vision-Language Models

**链接**: https://arxiv.org/abs/2610.21573
**作者**: Islam Mesabah, Sary Elmansoury, Gerrit Gro{\ss}mann, Peter Neigel, Sebastian J. Vollmer
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision trees can make vision-language model (VLM) classification interpretable by replacing a single prediction with a sequence of root-to-leaf questions. However, the accuracy cost of this greedy, non-backtracking procedure remains unclear. We introduce \textbf{MYOPIA}, a benchmark comprising four LLM-generated, human-refined decision trees for GTSRB, MNIST, CIFAR-10, and MSCOCO, together with matched prompts, diagnostic protocols, and an evaluation harness. Across GPT-4o, Qwen-VL Max, and LLaMA-3.2 11B Vision, tree traversal underperforms zero-shot prompting in all 12 dataset--model pairs; paired bootstrap analyses consistently favor zero-shot. Our diagnostics characterize interacting failure modes associated with this gap. Models often recall tree-encoded class attributes more accurately than they ground the same attributes in images: the mean label--image accuracy gaps are 9.5, 13.8, and 12.6 points for GPT-4o, Qwen-VL Max, and LLaMA, respectively. Incorrect local decisions then 

---

### [141] SITAR: A Situational Distortion Metric for Automatic Speech Recognition Evaluation

**链接**: https://arxiv.org/abs/2610.21440
**作者**: Mingzhe Lu, Jinhao Liu, Yunpeng Li, Hang Su, Lichun Fan, Jian Luan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In automatic speech recognition (ASR), transcription errors with similar lexical or semantic discrepancies can have markedly different consequences for the situation conveyed by speech. Capturing these differences requires not merely contextual assessment, but an understanding of what the spoken discourse describes, establishes, or seeks to bring about. However, relying on LLM judges introduces computational cost and scoring variability. We introduce SITAR, a situational distortion metric for ASR, realized through a comprehensive end-to-end construction framework. Specifically, this framework aggregates situational severity and cumulative extent into a unified score via a bounded recursive formulation. Using targets derived from this formulation with limited offline LLM support, we train SITAR as a lightweight BERT-family regressor that scores reference-hypothesis pairs in a single forward pass, entirely free of any prohibitive runtime costs. Recognizing that introducing a new metric d

---

### [142] Emotion Is Not External Knowledge: Internal Attention Signals for Affective State Reasoning

**链接**: https://arxiv.org/abs/2610.21347
**作者**: Wenqiu Tang, Zhen Wan, Yihui Wang, Takahiro Komamizu, Ichiro Ide
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) increasingly operate in multi-turn interactions that require maintaining latent conversational states, not only explicit facts. We study affective state as an implicit state inferred from sparse contextual cues that remain relevant after topic shifts, and ask whether LLMs expose internal attention signals for routing such evidence at inference time. Prior attention interventions rely on labeled in-domain head profiles and externally specified target spans, limiting transfer across affective-evidence distributions. We propose Self-targeted Internal Attention Boosting (SIAB), which localizes sparse affective heads via causal localization (in detail activation patching) on synthetic minimal pairs and boosts, at the answer position, the content tokens these heads already attend to; both edited heads and target tokens are derived from the model's own behavior, enabling the same head set to be reused across tasks.We evaluate on ECC and GoEmotions across three LLM

---

### [143] Jev-LiteMAS: Separating Decisions from Generation in Multi-Agent Workflows

**链接**: https://arxiv.org/abs/2610.21411
**作者**: Kaixiang Wang, Zhaijiacheng Zhou, Jiong Lou, Jie Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems rely on generative models for expert execution, workflow planning, and artifact review. Yet many coordination operations require only bounded decisions, such as selecting the next expert or judging artifact quality. Profiling three representative MAS frameworks, we find that routing and review account for 31.7-43.5% of generative-LLM tokens. However, replacing these operations with low-cost decision models introduces two interface gaps: generative planners produce execution plans and handoff instructions (planning gap), while reviewers provide actionable feedback for repairing flawed artifacts (review gap), which bounded decisions alone cannot provide. We introduce Jev-LiteMAS, a multi-agent framework that bridges both gaps by combining a lightweight decision model (Jev) with generative execution and feedback. To address the planning gap, Jev selects experts dynamically from the task and prior expert outputs, using accumulated context to ground subsequent execut

---

### [144] Inflak: A Unified Orchestration Architecture for Human-Agent Interaction

**链接**: https://arxiv.org/abs/2610.21972
**作者**: Lin Gao, Li Chen, Jianxun Lian, Ji Li and Haotian Li
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered agents increasingly support open-ended activities, yet orchestrating when and how agents interact with humans remains challenging. Existing approaches often provide interaction mechanisms tied to particular tasks or execution patterns, lacking a unified architecture for diverse and evolving interaction needs. We introduce Inflak, a unified four-layer architecture for human-agent interaction orchestration that separates state reconstruction and routing, interaction and execution planning, interaction design, and interface rendering. Its layered design with progressive resolution enables general applicability, runtime flexibility, module composability, and orchestration maintainability. We implement Inflak as agent-native, skill-based plugins within a general-purpose agent framework and evaluate it through a gallery of various application scenarios and interaction paradigms, technical performance testing, and a comparative implementation case study. The evaluations show that 

---

### [145] CleanRM: Reward Modeling from Noisy Feedback with a Few Clean Feedback for RLHF

**链接**: https://arxiv.org/abs/2610.21138
**作者**: Licheng Pan, Haocheng Yang, Yuzhou Chen, Yichen Sun, Yuan Lu, Yunfei Teng 等 (10 人)
**来源**: cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feedback noise is pervasive in preference data, arising from subjective human judgments, annotation mistakes, and imperfect LLM judges. Standard reward modeling trained on such feedback yields a biased estimate of the clean risk. Although classical denoising methods are directly applicable to noisy feedback learning, they generally assume a uniform noise ratio across samples. However, this assumption fails for feedback data, where noise is intrinsically sample-wise. To address this challenge, we propose CleanRM, which uses a few clean feedback to calibrate sample-wise noise ratios via optimal transport. Specifically, CleanRM aligns the joint distribution of preferences reverted from noisy feedback with that of clean feedback and then trains the reward model using a noise-corrected surrogate loss. Theoretically, we prove that the resulting objective is unbiased with respect to the clean risk. Extensive experiments demonstrate that CleanRM outperforms state-of-the-art denoising baselines

---

### [146] Close Enough is Nowhere Near: Fidelity-Consumability Decoupling in KV Caches

**链接**: https://arxiv.org/abs/2610.22016
**作者**: Adam Deng, Shicheng Liu, Yada Zhu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems communicate in text, which is lossy and wasteful: the sender throws away the reading it already did. A growing literature instead transmits the KV cache, the natural carrier of that reading. We study the most appealing form of the idea: both models stay frozen and the sender's cache is substituted for the reader's with nothing trained. It does not work, and the obstruction belongs to the reader. A frozen transformer reads only caches close to the one it would have written itself, a region we call its tolerable set. We show that geometric similarity to that cache does not predict whether the reader can use it, and the failure is not gradual, so a more faithful substitute is not the remedy it appears to be. We explain this phenomenon with competitive attention. Experimentally, we test eight diverse substitution methods against two measured anchors: an uninformative cache baseline and the reader's own accuracy from having read the passage. All sit at the baseline. 

---

### [147] CertEx: Exact Visual Retrieval at Scale by Certified Exclusion

**链接**: https://arxiv.org/abs/2610.21325
**作者**: Dongfang Zhao
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Exact $k$-nearest-neighbor (kNN) search over image descriptors and embeddings underlies visual retrieval, near-duplicate detection, the evaluation of learned representations, and increasingly the memory of LLM agents. However, exhaustive search computes every distance at full precision, whereas approximate indexes return recall below one. We observe that exact search only needs a proof that each excluded vector cannot be a neighbor. Because such a proof only has to be conservative, it can be checked in low precision, much as the retina examines the whole scene at low resolution. We call this principle certified exclusion and realize it in an exact kNN method for GPUs, which we call \certex. Specifically, \certex\ stores a lower-bounding projection of each vector in half precision and folds a rounding certificate into the same tensor-core dot product, so that only the few vectors that the test keeps need exact distances. We prove that \certex\ returns the exact kNN of every query. On si

---

### [148] PremiseCheck: Efficient Fact-Checking of Human and AI Peer Reviews

**链接**: https://arxiv.org/abs/2610.21046
**作者**: Dingjie Song, Zhiling Yan, Ziqian Zhang, Yuxuan Zhang, Lichao Sun
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peer review is under strain from the growth of submissions, and review comments written by humans or AI can misstate what a paper says. We introduce ReviewFact, a benchmark that labels such factual errors in review comments under one definition across NLP, machine learning, and the natural sciences, and that measures cost and latency alongside accuracy. A frontier LLM checks comments well but must read the whole paper for each check, while cheap decision models, which score whether a statement holds in a text, fall far short on whole comments that mix several implicit assertions. PremiseCheck is a framework that combines the two. An LLM rewrites each comment as explicit premises without reading the paper, and a decision model checks each premise against the paper. When each comment is checked on its own, PremiseCheck reaches accuracy comparable to GPT-5.5 across all three fields at about half its cost, and on NLP reviews at a quarter of its cost and less than half its latency.

---

### [149] Hear, Localize, and Reason: Spatially Aware Scene Understanding for Audio-Visual LLMs

**链接**: https://arxiv.org/abs/2610.21588
**作者**: Kim Sung-Bin, Lee Jung-Mok, Jinwoo Jung, Oh Hyun-Bin, Hyeonggon Ryu, David Harwath 等 (7 人)
**来源**: cs.CV cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-visual large language models (AV-LLMs) have made strong progress in multimodal understanding, yet most treat audio as monaural semantic content, limiting their ability to reason about where sounds originate and how they relate to the visual scene. Recent spatial audio-visual studies address parts of this problem, but often focus on specific abilities, such as spatial correspondence or direction and distance reasoning. In this work, we introduce HLR-AVSceneQA, a comprehensive benchmark with a hear-localize-reason hierarchy that evaluates whether models can recognize what is heard, localize sound sources in egocentric and allocentric views, and use these localized sources to reason about how they relate to the visual scene. We further introduce HLR-LLM, which augments a strong audio-visual foundation model with a binaural spatial audio branch alongside its monaural semantic audio pathway. We train HLR-LLM with a curriculum that incorporates final-stage chain-of-thought supervision 

---

### [150] Training Reasoning Models to Generate Diverse Scientific Ideas

**链接**: https://arxiv.org/abs/2610.22324
**作者**: Manya Wadhwa, Pranav Narayanan Venkit, Hiroaki Hayashi, Yu Li, Tuhin Chakrabarty, Chien-Sheng Wu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> One of the first steps of a research pipeline is generating ideas. Large Language Models (LLMs) are increasingly used to automate this step, but most of this work optimizes the quality of individual ideas, while overlooking diversity. In our work, we study document-grounded ideation, focusing on increasing the diversity of LLM generated ideas and ensuring they are high quality. Given prior papers, a model must propose a set of ideas that are each high-quality and clearly distinct from one another, while also being grounded in the input documents. To optimize for this, we propose training with a set-level reinforcement learning objective. In our setup, in a single generation, the model writes K structured idea cards grounded in the source papers, and the set is scored jointly, where each idea's quality is weighted by its distance from the ideas written before it. This teaches the model to steer each new idea away from its predecessors. We show that our trained 8B model achieves higher c

---

### [151] VALCON: Benchmarking and Enhancing Value Consistency in Large Language Models via Dual-Role Variation

**链接**: https://arxiv.org/abs/2610.21304
**作者**: Junru Wu, Jingting Zheng, Yuqi Ren, Deyi Xiong
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current value alignment evaluations for large language models (LLMs) heavily rely on output compliance, overlooking whether LLMs maintain value consistency when alternating between generator and evaluator roles. Such consistency is increasingly important because modern LLM agents and alignment pipelines often rely on the same LLM to both generate actions and evaluate their acceptability. To mitigate this limitation, we propose VALCON, a role-driven data construction framework that operationalizes value consistency into three benchmark suites (VAB-Consistency, VAB-Boundary, VAB-Challenge) via dual-role variation. By systematically pairing an LLM's generative behavior with its evaluative judgments under identical principles, VALCON synthesizes target evaluation data that exposes hidden value discrepancies. Experiments on 28 LLMs reveal pervasive cross-role inconsistency: models with highly compliant outputs frequently fail to align their judgments with their own generations. To understan

---

### [152] TOPS: First-Principles Visual Token Pruning via Constructing Token Optimal Preservation Sets for Efficient MLLM Inference

**链接**: https://arxiv.org/abs/2606.27161
**作者**: Tinghao Wang, Yichen Guo, Rui Huang, Junchi Yao, Qizhe Zhang, Zheng Lu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] MiCo: Mutual Information Coverage Optimization through Semantic Erasure Modeling for Efficient MLLM Inference

**链接**: https://arxiv.org/abs/2609.34330
**作者**: Tinghao Wang, Yichen Guo, Qizhe Zhang, Yuan Zhang, Weimin Ouyang, Rui Huang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [154] SUPRA-TEX: 3D Generation with Super-Aligned Texture

**链接**: https://arxiv.org/abs/2610.22352
**作者**: Chen Yang, Jiemin Fang, Fanpeng Meng, Zihao Huang, Jichen Pang, Guanjun Wu 等 (8 人)
**来源**: cs.CV cs.GR
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single image 3D generation aims to dress a given 3D mesh with relightable materials while faithfully preserving the visual details of a reference image. Existing methods either introduce artifacts when fusing inconsistent multi-view predictions or struggle to preserve fine details through implicit image-feature conditioning. To resolve these challenges, we introduce SUPRA-Tex, built on the principle of decoupling visible-material estimation, surface alignment, and observation-guided 3D completion. This division of labor allows the 3D generator, trained on limited 3D data, to focus its capacity on preserving visible evidence and completing unobserved surfaces. Specifically, we first train an MLLM-based image editing model to predict lighting-separated PBR maps in the reference view. We then project these maps onto the visible surface and encode them with the pretrained material VAE encoder into native observation latents that share the generation target's latent space. An interleaved fl

---

### [155] Cross-subject decoding of imagined speech from scalp EEG: a leakage-controlled evaluation on three public corpora

**链接**: https://arxiv.org/abs/2610.20954
**作者**: Blessing Isoyiza Adeika, Onyema Osuagwu
**来源**: eess.SP cs.LG q-bio.NC
**匹配关键词**: EEG, Brain-Computer Interface
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective. A decoder of imagined speech that works for a new user without calibration would make a non-invasive speech interface practical. We tested whether imagined-speech content recorded with scalp electroencephalography (EEG) transfers across people, and examined why accuracy within a single person remains low. Approach. We analyzed three public corpora, ds003626, KaraOne and Track 3 of the 2020 International Brain-Computer Interface Competition, under a protocol that enforces split integrity by assertion and reports exact binomial thresholds, group tests and bootstrap confidence intervals. We trained decoders on each participant and tested them on every other, compared representational geometry across participants without a classifier, applied subject-level alignment, and tested five explanations for the within-subject ceiling. Main results. Across 482 ordered pairs of participants, no pair survived correction for multiple comparisons; mean pair-transfer accuracy lay within 0.006

---

### [156] Semantic Alignment of EEG and Text: A Contrastive Learning Framework for Decoding Imagined Speech

**链接**: https://arxiv.org/abs/2610.20766
**作者**: Shahryar G. Namdari, Francesco Iacomi, Riccardo Barbieri, Luca Mainardi
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Imagined speech decoding from EEG offers a promising route toward naturalistic brain-computer interfaces. Traditional closed-set classifiers treat semantic categories as independent labels and do not explicitly exploit relationships among linguistic intents, limiting output flexibility. We adapt a multimodal contrastive learning framework to imagined speech, aligning EEG trials with language representations in the embedding space of a frozen pretrained text encoder. An EEG encoder is trained with a composite objective combining semantically reweighted EEG-sentence alignment and text-prototype-based class discrimination, encouraging semantic structure while preserving separability among 39 intent categories. We evaluate the approach on the Chisco imagined speech dataset across five subjects, reporting Top-k accuracy, macro-F1, and balanced pairwise matching accuracy (2v2). We also investigate maximum EEG-text cosine similarity (MaxCosine) as an intrinsic indicator of decoding reliabilit

---

### [157] EEG-Based Prediction of Music Enjoyment Using Deep Learning with Explainable Temporal Analysis

**链接**: https://arxiv.org/abs/2610.20795
**作者**: Parshav Singla, Simranjit Kaur, Maanya Walia, Niharika
**来源**: cs.LG cs.HC cs.SD
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding why listeners enjoy music is difficult because the experience is subjective and changes as a piece unfolds. Electroencephalography (EEG) offers a non-invasive way to study neural responses during listening, yet earlier work has mostly treated music emotion as a categorical label or relied on black-box models. We formulate enjoyment prediction as a regression problem on the public MUSIN-G dataset, which contains 128-channel EEG from 20 listeners together with song-level enjoyment ratings. Six deep learning models were compared under a participant-wise protocol, in which 15 listeners were used for training and validation and 5 were held out for testing. DeepConvNet, CNN-LSTM and GNN-CNN reached the lowest mean absolute error (0.97 to 0.99 on the 1 to 5 scale), while the temporal convolutional network (TCN) had the highest Pearson correlation with the ratings (r = 0.21). Gradient-based and occlusion-based explanations, averaged over all held-out windows, identify the time se

---

### [158] KnowEEG: Explainable Knowledge Driven EEG Classification

**链接**: https://arxiv.org/abs/2505.00541
**作者**: Amarpal Sahota, Navid Mohammadi Foumani, Raul Santos-Rodriguez, Zahraa S. Abdallah
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [159] Video-Time Priors for EEG-fNIRS Emotion Regression on Familiar Videos

**链接**: https://arxiv.org/abs/2610.03618
**作者**: Minghao Kong, Ying Gao, Jiurun Chen, Muyao Chen, Zheng Ge, Jianxin Wu 等 (7 人)
**来源**: cs.AI cs.CV cs.MM
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [160] Pathology foundation models for training-free case retrieval in salivary gland tumors

**链接**: https://arxiv.org/abs/2610.22087
**作者**: Maximilian J. Roesel, Niklas Kiermeyer, Philipp Keyl, Frederick Klauschen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In pathology, pattern recognition relies on a frame of reference built through extensive training and experience, which may still fall short when encountering rare cancer subtypes. Archives of previously diagnosed tumors often contain relevant precedents, yet identifying the most relevant cases remains challenging. Here we explore whether content-based retrieval with current pathology foundation models facilitates rare cancer diagnostics without any task-specific training. Pathologists can query a digitized archive using a region of interest (ROI) from a whole slide image (WSI) and retrieve morphologically similar cases, along with their ICD-O codes and corresponding WSIs. The ROI can be selected manually or automatically using a gated attention-based multiple instance learning model. We evaluate our approach by leave-one-case-out on an imbalanced dataset of 137 salivary gland tumor cases spanning 12 ICD-O morphology categories, comparing four pathology foundation models (Atlas2, Atlas

---

### [161] Multi-Modal, Multi-Temporal Geospatial Foundation Models Improve Global Above-Ground Biomass Estimation

**链接**: https://arxiv.org/abs/2608.04792
**作者**: Ghjulia Sialelli, Linus Scheibenreif, Jan Dirk Wegner, Konrad Schindler
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] FlatClip: Reusing Image Foundation Models for fMRI Representation Learning via Cortical Flatmaps

**链接**: https://arxiv.org/abs/2609.31204
**作者**: Mo Wang, Wenhao Ye, Zihan Ning, Jiayu Zuo, Junfeng Xia, Hongkai Wen 等 (7 人)
**来源**: cs.CE cs.CV q-bio.NC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [163] Code-Switching Detection via Language-Selective Dimensions in Speech Foundation Models

**链接**: https://arxiv.org/abs/2610.18726
**作者**: Jie Chi, Zakaria Aldeneh, Masha Fedzechkina, Maureen de Seyssel, Natalie Schluter
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [164] JEPA-DNA: Grounding Genomic Foundation Models through Joint-Embedding Predictive Architectures

**链接**: https://arxiv.org/abs/2602.17162
**作者**: Ariel Larey, Elay Dahan, Amit Bleiweiss, Raizy Kellerman, Guy Leib, Omri Nayshool 等 (10 人)
**来源**: cs.AI q-bio.GN
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] PiCo: Physics-Informed Concept Probing for Geo-Foundation Models

**链接**: https://arxiv.org/abs/2610.20973
**作者**: Yihang She, Andrew Blake, Jianbo Qi, and Srinivasan Keshav
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geo-foundation models (GFMs) are typically evaluated by downstream task predictive performance, revealing little about which physical features they are sensitive to or use in prediction. This limits developers' ability to test hypotheses about model behaviour and users' ability to select models for new tasks. We propose Physics-Informed Concept Probing (PiCo), a post-hoc framework for explaining GFM predictions. PiCo identifies concept vectors in a GFM's embedding space by generating synthetic multispectral satellite observations from a 3D radiative transfer model coupled with a game engine. These vectors reveal physical sensitivities that inform domain-based hypotheses about downstream performance. Projecting embeddings onto these concept vectors produces low-dimensional representations for quantifying concept importance in making predictions. We evaluate PiCo on three GFMs with different input modalities using seven physical concepts covering forest leaf optics and canopy structure. 

---

### [166] From Adults to Children: Benchmarking Foundation Models for Chest X-Ray Classification under Domain Shift

**链接**: https://arxiv.org/abs/2610.21809
**作者**: Sara In\'acio, Hugo Proen\c{c}a, Jo\~ao C. Neves
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models have shown significant potential across diverse fields and have been applied to medical imaging, but their robustness across patient populations remains unclear. In this work, we investigate foundation models' ability to generalize from adult to pediatric chest X-ray classification. To the best of our knowledge, this is the first benchmark to compare multiple foundation models under a common adult-to-pediatric evaluation setting while also analyzing the effect of adaptation depth. We harmonize VinDr-CXR and PediCXR into a five-label classification task and evaluate six foundation models and two CNN baselines. All models are adapted using adult data only and tested in both the in-domain and pediatric domains using linear probing, partial fine-tuning, and full fine-tuning. The benchmark reveals a clear and consistent trend: all models suffer a substantial performance degradation when transferred from adult to pediatric data, with drops exceeding 10 percentage points. Wh

---

### [167] TimeRSI: Towards Self-Improved Agentic Deployment for Time-Series Foundation Models

**链接**: https://arxiv.org/abs/2610.19725
**作者**: Haoxin Liu, Deqing Fu, Lucheng Fu, Yiqiao Jin, Rushi Qiang, Harshavardhan Kamarthi 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] Pixels to Tokens: Token Space Efficient Active Learning for Low-Budget Semantic Segmentation

**链接**: https://arxiv.org/abs/2610.20881
**作者**: Utku Cicek, Mahip Singh, Ziyao Shang, Kimathi Kaai, C Thomas, Pedro Pablo Guerrero Vela 等 (8 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While foundation models and vision transformers (ViTs) have redefined visual representations, current active learning (AL) strategies for these backbones largely operate at the patch or region level, where annotation requirements remain high due to extensive pixel labeling. Extending ViT-based AL to the pixel-level, low-budget regime is uniquely challenging: with as little as one pixel query per image, a method must simultaneously identify the most informative locations and train a reliable decoder head from an extremely sparse signal. We introduce TEAL (Token-space Efficient Active Learning), the first pixel-level AL framework built around ViT representations. TEAL uses a frozen ViT backbone and performs diversity-based selection directly on its native token lattice, avoiding the artifacts introduced by interpolating token embeddings to dense pixel resolutions. Our framework applies a two-level MaxHerding strategy over multi-layer token descriptors to select representative candidates,

---

### [169] Reliable Knowledge Acquisition for Continual Learning Agents

**链接**: https://arxiv.org/abs/2610.21739
**作者**: Yixu Huang, Jiaqi W. Ma
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agents powered by foundation models move into open-ended environments, continual learning from experience becomes essential. For agents built on models with fixed parameters, this learning requires reusing prior task experience in context to improve performance and efficiency on future tasks. Existing memory and experience-learning systems typically focus on either retained facts or procedures, and lack a mechanism for establishing the reliability of claims extracted from the ongoing task stream. Indeed, we find that approximately 12--33\% of entries produced by representative systems harm future task performance when reused. To address these limitations, we propose \textbf{RIKA} (Reliable Knowledge Acquisition), which combines hierarchical extraction of factual, conceptual, procedural, and metacognitive knowledge with Evidence-based Knowledge Admission, which uses source evidence and subsequent experience to govern which claims enter the task agent's context, without additional val

---

### [170] SurvICL: a Foundation Model for in-context Survival Analysis

**链接**: https://arxiv.org/abs/2610.22242
**作者**: Julie Alberge and Linus Bleistein and Judith Ab\'ecassis and Marine Le Morvan and Ga\"el Varoquaux and David Holzm\"uller
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) now outperform gradient-boosted trees in classification and regression. Yet in survival analysis, which predicts when an event occurs from censored data, often on small clinical cohorts, we find that no existing TFM beats the half-century-old Cox model. We address this issue by introducing SurvICL, a TFM that predicts survival curves in-context. SurvICL is pretrained on purely synthetic datasets generated from a novel flexible proportional-odds prior that outperforms other prior types in our ablation study. Unlike most other survival models, SurvICL is trained with a plain quantile regression loss, which is possible because its synthetic pre-training data generator can provide uncensored event times. Additionally, we introduce the largest survival benchmark to date spanning 103 datasets. On the 63 datasets held out from all design decisions, SurvICL outperforms 20 tree-based, deep, and foundation-model baselines without any tuning: it wins 82.9\% of pai

---

### [171] GeoState: Learning View-Decoupled Geometry States for 3D World Modeling

**链接**: https://arxiv.org/abs/2610.22343
**作者**: Hongchang Liu, Jian Liu, Yujuan Ding, Liang Peng, Xun Jiang, Fei Ma 等 (8 人)
**来源**: cs.CV cs.AI cs.LG cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent 3D world models increasingly use features from geometry foundation models (GFMs) as predictive world states, benefiting from their rich geometric priors. However, the view dependence of these features entangles scene dynamics with camera-induced variation, making the resulting state evolution harder to predict. We propose GeoState, a view-decoupled geometry representation for predictive 3D world modeling that separates scene-state evolution from camera-dependent observation. Specifically, a scene tokenizer aggregates multi-view GFM features into a view-decoupled scene state, which a geometry decoder queries using camera rays. An autoregressive world model then predicts future scene states, while camera motion is modeled separately. The predicted states can therefore be decoded under either predicted or externally specified cameras, while retaining a single context-derived scale throughout the rollout without per-frame scale alignment. Experiments show that GeoState outperforms p

---

### [172] ControlFlow3D: Distilling Multi-View Knowledge into Latent Flow Matching for Point Cloud Upsampling

**链接**: https://arxiv.org/abs/2610.21190
**作者**: Yuang Liu, Zhi Zuo, Zhengkai Zhao, Lirui Zhang, Pan Gao, Hao Feng 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Point cloud upsampling is essential for 3D applications but remains challenging due to sparse, under-constrained observations. Multi-view images can resolve geometric ambiguity, but existing multi-modal methods do not fully exploit visual cues. We propose ControlFlow3D, a framework that distills knowledge from pretrained foundation models into a lightweight generation network during training, enabling strong performance without multi-view images available at test time. Specifically, our method performs conditional flow matching in a structured latent space defined by a frozen 3D encoder. Multi-view image tokens and 3D latent tokens are jointly clustered into shared prototypes via unsupervised soft KMeans; the resulting prototypes guide the flow trajectory through velocity control and are aligned by a consistency loss that progressively transfers image knowledge into the base network. A Mamba-based geometry decoder then maps latent features to dense coordinates with linear complexity. W

---

### [173] MSP: Modality Self-Play for Training Multimodal LLMs Without Paired Cross-Modal Data

**链接**: https://arxiv.org/abs/2610.20965
**作者**: Robert Moseley, Md Kaykobad Reza, Ameya Patil, Edward Ayrapetian, Salman Asif
**来源**: cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large multimodal models have achieved remarkable progress by scaling model capacity and training on massive paired multimodal data. However, this paradigm introduces a fundamental bottleneck: aligned multimodal datasets are expensive to curate, difficult to scale across diverse modality combinations, and increasingly constrain further progress. We introduce Modality Self-Play (MSP), a training framework for multimodal foundation models based on proxy-mediated modality composition. Instead of relying on paired cross-modal data, MSP uses anchor-supporting proxy textual descriptions of unseen modalities as semantic bridges during training. Given an observed modality (e.g., image or audio), the model generates proxy descriptions for complementary unseen modalities, which are then encoded and aligned with the observed modality through learned bridges, enabling cross-modal interaction without real paired non-text supervision. Our central hypothesis is that proxy text, combined with contrasti

---

### [174] PathFM: Fast Generative Forecasting of Multivariate Trajectories

**链接**: https://arxiv.org/abs/2610.22358
**作者**: Jiachen Yao, Xiyuan Zhang, Annan Yu, Boran Han, Abdul Fatir Ansari, Shuai Zhang 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models are becoming increasingly popular for general-purpose forecasting. However, most leading models predict marginal quantiles, leaving the dependence structure of future trajectories unspecified. This distinction matters for trajectory-dependent quantities such as cumulative demand, peak load, and event timing, yet point and marginal scores do not reveal it. To model this dependence, we introduce PathFM, a trajectory-based forecasting model that uses flow matching to generate complete future paths. We further distill the model to one or two steps and share history attention cache across draws. Together, these enable PathFM to generate multiple paths for a single series in roughly the time needed for one query to a quantile model. The distilled sampler also makes it practical to optimize a calibration loss directly. PathFM achieves competitive marginal accuracy on the established forecasting benchmarks fev-bench and TIME. To complement these evaluations, we in

---

### [175] SelectPFN: Amortized Bayesian Variable Selection for Sparse Nonlinear Regression with Prior-Data Fitted Networks

**链接**: https://arxiv.org/abs/2610.21950
**作者**: Bin Luo
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models based on prior-data fitted networks (PFNs) predict on a new data set in a single forward pass, but they cannot report which inputs their predictions depend on. We propose SelectPFN, a PFN that performs Bayesian variable selection and prediction jointly for sparse nonlinear regression. In one forward pass it returns posterior inclusion probabilities for every variable, and its predictions are computed from sampled subsets only, so excluded variables provably cannot affect them; we show this is exactly what the Bayesian model prescribes. The network is pretrained once on synthetic tasks from a meta-prior built around a group spike-and-slab sparse-input neural network. Column-permutation equivariance combined with random interleaving of original and knockoff columns yields knockoff statistics with exact finite-sample false discovery rate control, even when the meta-prior is wrong. We develop theory for amortized selection: a Bayes-regret bound for the amortized m

---

### [176] Physics-Aware Distillation of a Grid Foundation Model for Real-Time Edge Inference

**链接**: https://arxiv.org/abs/2610.21833
**作者**: Vlad Alexandru S\u{a}nduleac, Shahariya Rasheed Rayamarakkarveettil Puthanpurayil, Noman Khan, Remus Teodorescu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Grid foundation models (GridFMs) are graph transformers pretrained on a masked power-flow objective, and evaluate power flow orders of magnitude faster than an iterative solver. Their size, however, targets data-centre inference, whereas low-inertia operation increasingly asks for inference at the edge, next to the measurement, at batch size one and within a single synchrophasor (PMU) reporting frame. We distil a 20.1M-parameter, 12-layer GridFM teacher into a 0.62M-parameter, 6-layer student, a $32.5\times$ parameter reduction at half the message-passing depth, using an objective that combines the masked power-flow loss with output, physics-residual, latent-state and attention transfer. The physics-residual term, which matches the teacher's power-residual profile, has not previously been applied to typed power-grid graphs. We evaluate on a renewable variant of the IEEE 118-bus benchmark grid in which 26 of the conventional (synchronous) generators are replaced by inverter-based renewa

---

### [177] Poisoning the corpora of protein design systems during pre-training and retrieval

**链接**: https://arxiv.org/abs/2610.21200
**作者**: Charalampos Koilakos, Kimon-Antonios Provatas, Michail Patsakis, Candace SY Chan, Georgios A. Pavlopoulos, Ilias Georgakopoulos-Soares
**来源**: cs.LG q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Protein foundation models increasingly support the generation of novel biological sequences, yet their reliance on large public datasets creates opportunities for adversarial manipulation of the material they learn from and retrieve. We investigate two data-only poisoning attacks against protein design systems, targeting the pre-training corpus of autoregressive protein language models and the retrieval corpus of a text-guided protein generator. For the first, we pre-trained ProtGPT2 and ProGen2 variants of 300 million parameters, introducing poisoned protein sequences containing one of two triggers followed by one of three payloads. Across all poisoned runs, both architectures acquired highly reliable trigger-dependent generation under uniform and ramped poisoning schedules. Under ramped exposure, the earliest majority activation occurred after only 200 contaminated examples, while for the uniform schedule earliest activation occurred around 5000 poisoned samples. For the second attac

---
