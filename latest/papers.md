# 📑 论文索引 - 2026-10-20

共 150 篇论文

---

### [1] Deep LLM layers expose passage-level context in EEG during silent reading

**链接**: https://arxiv.org/abs/2610.23638
**作者**: Ingo Marquardt, Anthilia Alchanat, Priyanka Jain
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG, LLM, Large Language Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In a previous report we showed that a decoder can recover open-vocabulary word-level information from 19-channel EEG recorded during silent reading, by aligning short EEG windows with hidden-state embeddings of the presented word taken from a large language model (LLM). That analysis contrasted two of the model's 33 layers: the context-free input embedding and one mid-depth layer. Here we ask how EEG-decodable structure is distributed over the full depth of the language model. We trained one decoder per layer of Llama-3.1-8B, with and without a causal transformer over the sequence of EEG windows. We distinguish word-level decodability from a context-tracking component. Word-level decodability peaks in early layers and declines steadily towards the last layer. In contrast, the context-tracking component of the retrieval gain rises with depth, both with and without a causal transformer. Unexpectedly, a decoder that sees a single 0.5-s window at a time tracks the text passage too. Two new

---

### [2] MobileInject: Evaluating Reasoning-to-Action Security of MLLM-Based Mobile Agents under Cross-Modal Consistency Injection

**链接**: https://arxiv.org/abs/2610.23307
**作者**: Songping Wang, Peiyang Li, Yi Huang, Fengting Li, Xuhao Ran, Yueming Lyu 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language model (MLLM)-based mobile agents are rapidly evolving from conversational assistants into autonomous systems that perceive, reason over, and act on smartphone environments. This capability also exposes a new security risk: adversaries can embed malicious objectives in cross-application mobile content and steer agent behavior through indirect multimodal injection. Although prompt injection has been studied in desktop and web settings, its cross-modal properties in mobile ecosystems remain poorly understood, and existing security analyses are still limited. To close this gap, we introduce MobileInject, the first benchmark for evaluating mobile agents against multimodal injection attacks and reasoning-to-action security risks. MobileInject provides a high-fidelity interactive mobile evaluation framework covering 11 scenarios, 9 security-risk categories, and 108 executable risk instances. It further introduces Cross-Modal Consistency Injection to exploit corrobora

---

### [3] MLLM Frame Subset Ensembling for Audio-Visual Video QA and MLLM-based Reranking for Ad-hoc Video Search in TRECVID 2025

**链接**: https://arxiv.org/abs/2610.23214
**作者**: Andreas Goulas, Damianos Galanopoulos, Ioannis Patras, Vasileios Mezaris
**来源**: cs.CV
**匹配关键词**: Foundation Models, LLM, MLLM
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents the overview of the runs related to the Ad-hoc Video Search (AVS) and Video Question Answering (VQA) tracks of TRECVID 2025 on behalf of the CERTH-ITI team. For the AVS track, we introduce a two-stage framework built on foundation models. In the first stage, multiple vision-language models (VLMs) encode both the input query, augmented through LLM-generated rephrasings, and the candidate video shots, producing weighted similarity scores for initial retrieval. In the second stage, we utilize a Multimodal-LLM(MLLM)-based reranking module that evaluates the semantic alignment between each shot among the top-N highest-ranked ones and the original query, generating updated relevance scores for reordering these shots. This MLLM-driven reranking significantly improves contextual matching and produces more accurate final rankings without requiring any model training. Regarding the VQA track, we fine-tune an audio-visual MLLM model on the provided TRECVID training dataset and

---

### [4] The Cognitive Cost of LLM Writing: A Reading-Time Comparison with Human Text

**链接**: https://arxiv.org/abs/2610.23715
**作者**: Kamer Cekini, Elisabetta Biondi, Chiara Boldrini, Andrea Passarella, Marco Conti
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although linguistic differences between human-written and Large Language Model (LLM)-generated texts have been extensively studied, their implications for the cognitive effort involved in reading remain less explored. In psycholinguistics, reading time is commonly used as an indirect measure of cognitive processing effort. Building on this perspective, we investigate whether human-written texts and their LLM-generated rewrites exhibit differences in predicted reading time that may reflect differences in processing demands for readers. To this end, we introduce RoBERTa-RT, a model trained on human eye-tracking data to predict word-level reading times. We evaluate the model on both internal and external test sets, construct a paired dataset of 496 human-written articles and their LLM-generated rewrites, and apply RoBERTa-RT to compare their predicted reading times. Our findings show that LLM-generated rewrites tend to be shorter and have slightly lower predicted total reading times, whil

---

### [5] When is a large language model a good calibration agent? Physics-labeled prompting for budgeted engineering simulator calibration

**链接**: https://arxiv.org/abs/2610.22379
**作者**: Ruo-Qian Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Calibrating expensive engineering simulators requires tuning model parameters to match reference data, a process heavily constrained by computational costs. This study investigates whether Large Language Models (LLMs), conditioned on physical diagnostic descriptions of simulation errors, can propose informative parameter updates more efficiently than conventional derivative-free optimizers. We test this on a cylinder-wake Large-Eddy Simulation and a damped-oscillator inverse problem. Physics-labeled prompts are evaluated against four text ablations (removed, anonymized, padded, misdirected) and standard optimizers (Nelder-Mead, Bayesian optimization, CMA-ES, and random search). Results demonstrate a strong early semantic advantage: the first physics-informed LLM proposal improves the initial design in 23 of 25 trials. After five evaluations, the median calibration error is 21.9 times lower than physics-free controls. However, this advantage is transient - disappearing by fifteen evalua

---

### [6] AlphaBet: Reinforcement Learning for LLM Event Forecasting Agents

**链接**: https://arxiv.org/abs/2610.22684
**作者**: Liqin Ye, Rongzhi Zhang, Xin Liu, Zheng Li, Yuan He, Qingyu Yin 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Forecasting an unresolved event requires finding relevant evidence and deciding how strongly it supports each outcome. Yet outcome-based training of Large Language Model (LLM) forecasters often begins with preassembled evidence at a single prediction date, leaving evidence acquisition outside the learning loop. We introduce AlphaBet, an agentic reinforcement learning (RL) framework that trains a single LLM policy to search, reason, and report probabilities across multiple pre-resolution dates. Each dated forecast is scored by a proper scoring rule against the eventual outcome, allowing one resolved event to supervise decisions under different information states. We decompose forecasting regret into an evidence-acquisition gap and a probability-reporting gap, and show that Group Relative Policy Optimization (GRPO)'s standard-deviation normalization can distort the reporting target under multi-class proper scores. On GLM-4.5-Air, AlphaBet reduces the Brier score from 0.731 to 0.626 on Fo

---

### [7] On the possibilities and limitations of LLM-based multi-agent systems for multi-criteria decision-making in healthcare operations management

**链接**: https://arxiv.org/abs/2610.23673
**作者**: Marco Boresta, Tommaso Giovannelli, Sepehr Namirad, Giulia Riccardi
**来源**: math.OC cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-criteria models for healthcare operations need weights that express how stakeholders trade off patient waiting time, provider workload, and operating cost, but these weights are difficult to quantify. Teams of large language model (LLM) agents, each prompted to represent a stakeholder, have been used to supply them. We propose a framework for assessing the reliability of LLM-generated preferences as inputs to multi-objective optimization and quantifying how their uncertainty affects decisions. We study explicit preferences by asking agents to rate the importance of the criteria in an outpatient appointment scheduling problem, and implicit preferences by inferring trade-offs from the agents' pairwise choices between emergency department configurations. The computational experiments show that the explicit preferences respond to the clinic's operating conditions and differ across roles, but deliberation among the agents can erase these differences, whereas simple averaging preserves

---

### [8] Who Pays for Efficient Inference? Confidence-Based Small-to-Large LLM Routing Across Tasks and Languages

**链接**: https://arxiv.org/abs/2610.23249
**作者**: Md Sabbir Hossen, Anichur Rahman, Pabon Shaha, Airin Afroj Aishi, Andrew H. Sung, and Md Shohel Rana
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small-to-large language model routing can reduce inference cost by escalating difficult inputs while retaining easier ones on a smaller model. Its success, however, depends on identifying examples that benefit from escalation, and the reliability of confidence across multilingual tasks remains unclear. We present a systematic evaluation of confidence-based routing across three model families, four languages, and three task types, covering 72 model, dataset, language, and scale configurations and 42,288 predictions. We compare global confidence routing with random routing, equal-quota confidence routing, and an oracle upper bound. Confidence identifies beneficial escalations on the Belebele reading comprehension and SIB-200 topic classification datasets, with mean correction-detection AUCs of 0.612 and 0.705. At 50% escalation, it improves over random routing by 1.40--4.67 percentage points on Belebele and 2.54--5.63 points on SIB-200. In contrast, the mean AUC on the MMLU-ProX-Lite kno

---

### [9] ParetoChat: An LLM-Based Interface for Interactive Multi-Objective Optimization

**链接**: https://arxiv.org/abs/2610.23062
**作者**: Gokhan Ceyhan
**来源**: cs.CL math.OC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-objective optimization models are often deployed in settings where decision makers (DMs) must balance some conflicting criteria. In practice, however, stakeholders must translate their qualitative preferences between different criteria into numerical weights, priorities, or reference points required by optimization methods, which can be difficult to specify and interpret. This paper proposes \emph{ParetoChat}, an LLM (large language model)-based expert-agent interface for interactive multi-objective optimization. The agent translates natural-language user input into structured scalarization parameters, invokes an optimization system, presents candidate solutions, and iteratively elicits feedback. We describe a multi-agent architecture that separates input processing, multi-criteria decision-making (MCDM) expertise, solution presentation, and feedback processing. We then present a simulation study using an LLM-based DM agent and benchmark ParetoChat against interactive methods imp

---

### [10] Teach the Magnitude, Not the Direction: Verifier-Anchored Credit Assignment for Multi-Turn Multi-Step LLM Agents

**链接**: https://arxiv.org/abs/2608.13179
**作者**: Zechuan Wang, Siyuan Lu, Hongxuan Zhang, Linjian Mo, Chenyi Zhuang, Leilei Gan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [11] Self- and Other-Labels Induce Bidirectional Bias in LLM Judges

**链接**: https://arxiv.org/abs/2608.18091
**作者**: Songeun Chae, Min Kim, Donghoon Jung, Seojin Choi, Seohyon Jung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] MARS: Memory-Aware Routing for Session-Level LLM Assistants

**链接**: https://arxiv.org/abs/2610.23583
**作者**: Minghan Wang, Jinhang Zuo, Zhongxiang Dai, Zhiyong Wang, Fang Kong
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term LLM assistants must repeatedly decide what prior context to expose and which model should answer as an interaction evolves. Existing memory systems and model routers usually make these decisions separately, although memory construction changes the evidence, distractors, and difficulty of the resulting input. We introduce MARS, a memory-aware routing framework that uses session state as a shared control interface between memory construction and model selection. A Query and Topic Manager (QTM) estimates compact decision-relevant state that guides a fixed state-conditioned memory policy and an online router, enabling each turn to receive an appropriate memory view and a suitable model under a quality-memory-cost trade-off. We evaluate MARS on RealMem and MultiChallenge with 16 system configurations each, covering long-history memory-driven interaction and bounded sessions with structured context interference. On RealMem, MARS preserves 98.2% of full-context GPT-4o's QA while usi

---

### [13] Before Retrieval Begins: Safety and Tool-Use Decisions in LLM Agents

**链接**: https://arxiv.org/abs/2610.23071
**作者**: Aditya Nawal, Manit Baser, and Mohan Gurusamy
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly act as agents that call external tools, yet most tool-safety research examines only what follows a tool call. The prior decision of whether to call the tool remains largely unexamined and can influence downstream safety. Across the seven open-weight models, the unweighted model-average harm rate after admitted harmful requests is 74.5%. To identify what governs this decision, we apply a factorial intervention to the input request. Within our generated construction, neutralizing the requested-operation component produces the largest admission contrast (19 pp). A linear direction estimated from this contrast influences held-out admission in four of seven models; effects on operation-neutralized requests in some models show that it is not an operation-specific mechanism. We then test whether written refusal is behaviorally and representationally coupled to the same decision. Written refusal accompanies 33.6% of admitted harmful calls. Plain-text refusal 

---

### [14] From Natural Language Intent to Executable Control: Hierarchical Feedback-Guided LLM Planning for Multi-component Cyber-Physical Systems

**链接**: https://arxiv.org/abs/2610.22441
**作者**: Jinglin Dai, Jiawan Wang, Ruiqi Hong, Lei Bu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) provide a convenient interface for translating natural language commands into task plans for cyber-physical systems (CPSs). However, two gaps hinder their use for real execution: generated plans may misinterpret or omit the user's intent, and even a logically plausible plan may be infeasible under component dynamics, interactions, or safety constraints. Existing LLM-based planning approaches often lack informative feedback on why a generated plan fails, providing little guidance for revising the plan accordingly. To address these challenges, we present a hierarchical feedback framework that uses different types of feedback information to guide LLMs in generating executable plans for CPSs. We prompt LLMs to generate both a structured task plan and corresponding signal temporal logic (STL) constraints, and design a sound algorithm that identifies definite contradictions between them and provides feedback for revising inconsistencies. At the execution level, w

---

### [15] Validating LLM-generated political networks with survey-reported partisan exposure

**链接**: https://arxiv.org/abs/2610.23199
**作者**: Marco Tonin, Michele Tizzoni, Bruno Lepri, Luca Maria Aiello
**来源**: cs.SI cs.AI physics.soc-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to simulate human behavior in social science research, including decisions, interactions, and social relationships. However, in network formation tasks, existing evaluations often focus on aggregate network properties, while networks with plausible structural properties may still fail to reproduce individuals' social and political environments. Here, we generate LLM-based political networks using personas sampled from the nationally representative ANES 2020--2022 Social Media Study and use respondents' survey-reported partisan exposure as an empirical benchmark for the political environments generated for the corresponding personas. We first characterize the structural properties and political assortativity of the generated networks, and then compare ego-level partisan exposure with the survey. We find that the structure and political assortativity of the generated networks vary across experimental configurations. More importantly, whe

---

### [16] CascadeLedger: Counterfactual Auditing of Information and Resource Integrity in LLM Cascades

**链接**: https://arxiv.org/abs/2610.20668
**作者**: Miaobo Hu, Shuhao Hu, Xiaobo Guo, Xin Wang, Bokun Wang, Daren Zha
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] FSPO: Policy-Consistent Risk and Pareto-Feasible Control for Budgeted LLM RL Post-Training

**链接**: https://arxiv.org/abs/2610.02828
**作者**: Miaobo Hu, Shuhao Hu, Xiaobo Guo, Xin Wang, Bokun Wang, Daren Zha
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] Beyond Generation: Using Multimodal LLMs as Detectors of LLM-Generated Deepfake Facial Images

**链接**: https://arxiv.org/abs/2610.21760
**作者**: Olivia Salamon and Virginia N. L. Franqueira and Shujun Li
**来源**: cs.CV cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] Benchmarking and Enhancing Agentic Causal Discovery

**链接**: https://arxiv.org/abs/2610.22846
**作者**: Pingchuan Ma, Rui Ding, Shuai Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can now run causal discovery algorithms on a dataset and report what comes out. Whether they do more than that, such as noticing where an algorithm went wrong and fixing it with further tests, is hard to tell from current benchmarks. Most of them give the variables meaningful names, and an LLM shown only the names of the T\"ubingen cause-effect pairs already gets 99% of the directions right. With the names removed, the data are usually clean enough that picking a better algorithm than PC closes most of the gap. We introduce Heuresis, a benchmark of anonymous simulated datasets whose mechanisms range from linear Gaussian to heavy-tailed. For each family of datasets it separates what a better existing algorithm can gain from what only a closer look at the data can gain, and it traces every edge an agent changes. Every family leaves a gap that none of the algorithms, the router and the two causal-discovery foundation models we ran can close, so a score above the best chosen alg

---

### [20] Efficient LLM-Generated Shuttling Compilers for Complex Trapped-Ion Architectures

**链接**: https://arxiv.org/abs/2607.24714
**作者**: Fabian Kreppel and Reza Salkhordeh and Ferdinand Schmidt-Kaler and Andr\'e Brinkmann
**来源**: quant-ph cs.AI cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Causal Value Attribution of Marketing Labels in LLM-Generated Ads: A Deconfounder Approach

**链接**: https://arxiv.org/abs/2610.23025
**作者**: Danhong You, Wei Jiang, Zhiqiang (Eric) Zheng
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI-generated content becomes commoditized, economic value increasingly shifts from final artifacts to the upstream expertise used to specify inputs that steer LLM generation. Yet organizations lack methods for valuing this expertise and identifying which individual skills or configurations causally improve performance. This study examines generative marketing, where structured expert labels serve as skill primitives conditioning LLM-generated advertisements. Estimating their causal effects is difficult because outcomes reflect stochastic LLM mediation, high-dimensional label interactions, and multimodal confounding. This study proposes D-VAE (Deconfounder Variational Autoencoder), a counterfactual-inference framework integrating a multi-treatment deconfounder with causal representation learning. D-VAE recovers causally disentangled expert-labeling logic and derives PAC-based bounds on omitted-variable bias from single-treatment confounders. Applied to 29,177 foundation-makeup ad cre

---

### [22] Designing for Imperfect Prompts: A Simulation-Based Evaluation of an LLM-Based Enterprise Data Assistant Using Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.23304
**作者**: Niklas Wagner, Alexander M\"adche
**来源**: cs.HC cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise data assistants using large language models (LLMs) promise democratized data access in organizations. Yet in our real-world deployment within the CFO unit's data lake at an industry partner, we observed that business users frequently pose imperfect prompts that include domain-specific vocabulary and lack schema references or structural information. This Design Science Research study examines automatic resolution using a semantic mediation layer. We design and evaluate two design variants: schema-based mediation via semantic similarity, and knowledge graph-based mediation leveraging an automatically constructed knowledge graph from the data lake. Our simulation-based evaluation using real-world data, supported by LLM-as-a-Judge assessments and human validation, shows that knowledge graph-based mediation outperforms the schema-based approach in Precision, Recall, F1, and preserving user intent. We propose a design principle for knowledge graph-based mediation, demonstrating th

---

### [23] SAFE-Mem: Secure Agentic Memory with Fine-Grained Authority and Governance-Aware Retrieval

**链接**: https://arxiv.org/abs/2610.22959
**作者**: Haoming Li, Dingyi Kang, Xu Hu, Jinxin Yang, Zhu Xu, Chenru Wang 等 (10 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on persistent memory to support long-term reasoning and personalized interactions. However, information collected from external sources can introduce security risks when untrusted claims (i.e., atomic statements) are later treated as authorized preferences, policies, or permissions. Existing defenses typically rely on content-based filtering or coarse-grained provenance tracking, which either fail to prevent unauthorized memory use or block legitimate information, sacrificing memory utility. To address these limitations, we propose SAFE-Mem, a fine-grained memory governance framework that improves security while preserving legitimate memory use. First, SAFE-Mem annotates each claim with three governance labels (i.e., kind, authority, and scope) to capture its provenance and permitted use. Second, governance-aware retrieval matches query requirements with claim permissions to block unauthorized influence while retaining legitimate info

---

### [24] Repairing LLM-Generated Specifications with Deterministic Diagnosis

**链接**: https://arxiv.org/abs/2610.22568
**作者**: Giovanni Vaccarino, Emanuele La Malfa, Dehai Min, Hanrong Zhang, Pier Luca Lanzi, Lu Cheng 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as formalizers: given a reasoning problem expressed in natural language, they produce a formal specification that a symbolic solver can then solve, with guarantees relative to that specification. Many specifications are runnable yet semantically wrong, encoding incorrect constraints, domains, objectives, predicates, or goals, and solver-error feedback dries up once execution succeeds. Purely LLM-based diagnosis, lacking a formal ground truth, often fails to spot these errors, and its ungrounded critiques cause regressions in 11.8% of initially correct specifications in our experiments. We propose DRAGO, a repair framework that replaces this ungrounded critique with deterministic, formalism-specific diagnosis, and retains a rewrite only when the diagnosed error weight strictly decreases under a reference-free acceptance predicate. Across five benchmarks spanning logical reasoning (SMT-LIB2), constraint programming (MiniZinc), and planni

---

### [25] When Extremists Enter LLM Societies: Investigating Extreme Behavior in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.19863
**作者**: Guo Chen, Huaijin Xie, Ziwen Li, Reed Li, Yu Lu, Haibo Shi 等 (8 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Process Reward Modeling with Reliability- and Conservatism-Aware Bayesian Belief

**链接**: https://arxiv.org/abs/2610.23223
**作者**: Zhongjian Qiao, Zhixiang Zhou, Jiafei Lyu, Peisong Wang, Qiaosheng Zhang, Siyang Gao 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Process Reward Models (PRMs) play a central role in test-time scaling for large language model (LLM) reasoning. However, PRMs may provide inaccurate process rewards for test-time scaling, which we identify as arising from two sources of uncertainty: (1) \textit{PRM uncertainty} that arises from insufficient supervision data and imperfect PRM training; and (2) \textit{policy uncertainty} that results from the mismatch between the policy to collect supervision data and the policy for test-time scaling, leading to systematic reward overestimation. Previous studies fail to jointly consider both uncertainties. To bridge this gap, we propose BayesianPRM, which treats the process reward as a random variable within a reward hypothesis space and maintains a Bayesian belief over it. Since exact Bayesian inference over the continuous hypothesis space is generally intractable, we discretize the reward hypothesis space with a reward ensemble and introduce two complementary belief updates, each targ

---

### [27] Self-Evolving Agents Can Repair Failures but Struggle to Generalize from Them

**链接**: https://arxiv.org/abs/2610.22984
**作者**: Weixiang Zhao, Yichen Zhang, Yanyan Zhao, Jinming Bai, Bin Liang, Ruifeng Xu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experience-driven self-evolution offers a promising path for large language model (LLM) agents to continually improve through interaction. Yet existing approaches often rely on successful trajectories or external evaluation signals, leaving unclear whether agents can evolve when such positive anchors are unavailable. We study this question through Cold-Start Failure-Only Evolution (CFOE), where agents start without accumulated experience and learn only from failed interactions without privileged guidance. Across three self-evolving paradigms, multiple LLM backbones, and four interactive environments, we uncover a consistent repair-generalization gap: failure-derived experience can help repair previously failed tasks, but rarely yields sustained improvements on unseen tasks. Further analysis shows that agents often misinterpret failures, while even verified-correct experience remains difficult to transfer. Relaxing CFOE reveals that verifier feedback and additional interaction provide l

---

### [28] Testing the Planning Claims of LLM-Based Agents against Formal Semantics

**链接**: https://arxiv.org/abs/2610.22469
**作者**: Oriol Miro-Lopez-Feliu, Oscar Mir\'o L\'opez-Feliu, Victor Gimenez-Abalos, Javier Vazquez-Salceda, Victor Carballo Araruna, Sergio Alvarez-Napagao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly credited with the competences of practical reasoning: planning, monitoring, and correcting their own actions. Their success is attributed to the prompting strategies and agent architectures built around the model, such as chain-of-thought, search-based prompting, self-refinement, reflection, critics and tool-using loops. Yet these claims are usually supported by end-to-end success rates, which show only whether a task was completed, or by LLM judges, which are not verifiers. We test LLM planning against formal semantics. Tasks are posed in natural language, but each is grounded in a hidden PDDL model that decides whether every action is applicable, whether the goal is reached, and whether a plan exists at all. Across five domains (two of them new, all released with the paper), four models, six prompting strategies and three agent architectures, the best configuration solves 78% of the solvable tasks offline but only 40% online, where agents mostly act 

---

### [29] IndicDetect: Evaluating Cross-Lingual LLM-Generated Text Detection for Hindi, Telugu, and Tamil

**链接**: https://arxiv.org/abs/2608.29919
**作者**: Bhaskar Ganesh Devalla, Junchao Wu, Nilesh Dokuparthi, Greeshma Yaluru, Tatiana Muniz Rodriguez, Lidia S. Chao 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] Is Your NPU Ready for LLMs? Dissecting the Hidden Efficiency Bottlenecks in Mobile LLM Inference

**链接**: https://arxiv.org/abs/2607.05475
**作者**: Guanyu Cai, Ruiming Tian, Lang Yang, Zhouhong Ren, Jinliang Yuan, Lingkun Li and Jiliang Wang
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Risk and Refusal: Mechanisms of LLM Responses to Suicidal Ideation

**链接**: https://arxiv.org/abs/2610.22715
**作者**: Drishti Goel, Soorya Ram Shimgekar, Jeongah Lee, Violeta J. Rodriguez, Daniel S. Brown, Ravi Karkar 等 (7 人)
**来源**: cs.HC cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Refusal is a common safety mechanism in large language models (LLMs), yet in contexts of suicidal ideation (SI), refusing to engage can itself constitute a safety failure. We evaluate how eight instruction-tuned LLMs respond to SI and self-harm disclosures across three datasets, varying whether models are informed that a disclosure expresses SI and whether they receive a clinician-developed response protocol, and complement this with mechanistic analyses in six open-weight models. Our results reveal a nuanced relationship between refusal and response-level risk. At baseline, elevated risk in model responses is driven primarily by inattention to the disclosure, alongside refusal to engage. Mechanistic analyses suggest that models may refuse SI disclosures through the same direction that mediates their refusals of harmful requests. However, informing models of the SI context, or suppressing refusal directly, increases engagement without reliably lowering response risk, and may raise it. 

---

### [32] Action-Space Shaping for LLM Agents: Measuring and Mitigating Tool-Schema Bias

**链接**: https://arxiv.org/abs/2609.34971
**作者**: Yinhong Liu, Zhili Tan, Zilin Wang, Zhijiang Guo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] From Relevant Memories to Sufficient Evidence: Rethinking Memory Utilization in LLM Agents

**链接**: https://arxiv.org/abs/2610.22668
**作者**: Shixuan Li, Wei Yang, Peiyu Zhang, Anzhe Cheng, Heng Ping, Xiaole Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory enables LLM agents to reuse past experiences, yet retrieving relevant memories does not necessarily provide sufficient evidence for answering a query. Essential information may remain fragmented across memory records, obscured by abstraction, or disconnected from the relations required for reasoning. We identify this relevance-sufficiency gap and propose QEMem, a framework that reformulates memory utilization as the construction of query-specific evidence sets, shifting the focus from individual retrieval relevance to collective evidential support. QEMem integrates three complementary mechanisms: query-guided discovery retrieves evidence across multiple memory granularities; source-grounded reification organizes it into structured ViewCards with explicit evidential roles and source references; and sufficiency-guided refinement selectively recovers missing information. Operating on existing memory stores without modifying memory formation, QEMem achieves 91.43% LLM-judg

---

### [34] Same Person, Different Advice: Auditing LLM Financial Advice with Repeated Risk-Tolerance Responses

**链接**: https://arxiv.org/abs/2610.23060
**作者**: Soovadeep Bakshi, Apurba Bose, Aishwarya Bose, Sandip Nandi
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI financial advisers set a client's stock allocation largely from one stated-risk question, yet people do not answer it the same way twice: in a national US panel, 41% of households chose a different answer two years later, and in a laboratory retest a third of people moved two or more points on a 0-10 scale after six months. Seven large language models from five providers gave one-turn allocation advice for 800 real household profiles in which only the risk answer changed. The recommended stock share moved by 10 to 16 percentage points on average, and by 24 to 35 when the answer changed, against 0.6 to 4.2 points for the same prompt asked twice; in the laboratory retest the rating alone moved advice by 11 to 18 points. Without any note, the models respond to the answer about as strongly as when told that it is very reliable (less so for the two Claude models). If that instructed response is how each model maps attitude to advice, discounting the answer for its measured reliability, a

---

### [35] BiShield-TEE: On the (In-)Security of Unilateral Weight Obfuscation in On-Device TEE-Shielded LLM Partition

**链接**: https://arxiv.org/abs/2610.21565
**作者**: Zhiyuan Wang, Yuezhi Zhou, Ziqi Zhang, Zhu Zhang, Zhixing Tan, Yongheng Deng
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Porimon: An LLM-Based Pok\'emon Battle Agent Enhanced by Long/Short-Term Knowledge Augmented Generation

**链接**: https://arxiv.org/abs/2609.32544
**作者**: Dongyin Zhuo, Fengjunjie Pan, Nenad Petrovic, Alois Knoll
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] Rep2Text: Decoding Full Text from a Single LLM Token Representation

**链接**: https://arxiv.org/abs/2511.06571
**作者**: Haiyan Zhao, Zirui He, Yiming Tang, Fan Yang, Ali Payani, Dianbo Liu 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] SkillBrowser: Selective Skill Exposure for Scalable Skill-Using Agents

**链接**: https://arxiv.org/abs/2610.23554
**作者**: Jin Ye, Yifan Jiang, Lan-zhe Guo
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly rely on skills to extend their capabilities in complex tasks. However, scalable skill use requires Selective Skill Exposure (SSE): providing relevant procedural content when needed while avoiding unnecessary exposure that may disrupt reasoning. Existing paradigms fall short in complementary ways. Progressive disclosure exposes metadata for a growing skill library, introducing context pollution; retrieval limits catalog exposure, but static retrieval from the initial task query may be misaligned with capability needs that emerge during reasoning and may still inject unnecessary skills. We propose SkillBrowser, a Meta-Skill-managed framework that enables an agent to identify current capability needs, formulate targeted queries, and selectively load skills on demand. Across six SRA-Bench subsets and five LLMs, SkillBrowser improves aggregate accuracy over static retrieval and LLM-based selection, including multi-step tool use, and mitigates accurac

---

### [39] SEA-HELM Audio: Evaluating Multilingual ASR-LLM Pipeline Performance Across SEA-HELM Subsets

**链接**: https://arxiv.org/abs/2610.19869
**作者**: Aulia Adila, Yixian Tan, Jonathan Heng, Kunat Pipatanakul, Donghang Wu and Anocha Sutaveephamochanon
**来源**: cs.SD cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Optimizing Singular Spectrum for Large Language Model Compression

**链接**: https://arxiv.org/abs/2502.15092
**作者**: Dengjie Li, Tiancheng Shen, Yao Zhou, Bernard Ghanem, Yibo Yang, Ming-Hsuan Yang
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Advertising to Agents: Measuring Description-Framing Bias in LLM Tool Selection

**链接**: https://arxiv.org/abs/2605.23916
**作者**: Haochuan Kevin Wang
**来源**: cs.IR cs.AI econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] AgentOnto: Ontology-Guided LLM Agents for Enterprise Data Analytics

**链接**: https://arxiv.org/abs/2610.23317
**作者**: Dayan Pan, Bincheng Zuo, Xiaojian Wang, Daogang Zhang, Jingyuan Wang
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise data analysis requires agents to connect analytical requests with knowledge distributed across databases, business documents, and existing example tasks. Without an explicit representation of this knowledge, an agent may produce incorrect analytical results and cannot reliably incorporate feedback. We present AgentOnto, an ontology-guided LLM agent for enterprise data analytics. AgentOnto organizes heterogeneous enterprise knowledge into an ontology that directly guides analysis and incorporates confirmed feedback. Iterative Ontology Preparation further improves the ontology through self-generated analysis tasks. We evaluate AgentOnto on two public data sources. AgentOnto substantially outperforms representative methods, while module-level evaluations confirm the effectiveness of ontology construction, analysis, and updating. A real-world deployment further demonstrates its practical value in enterprise analytics. These results demonstrate that explicitly constructing, using

---

### [43] SciIntBench: Measuring LLM Compliance with Research Integrity Norms Under Adversarial Framing

**链接**: https://arxiv.org/abs/2605.29468
**作者**: Almene De Meran Meguimtsop, Maria Leonor Pacheco, Daniel E. Acuna
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] PRIME: Towards Verifiable Evidence-Grounded Reasoning in LLM Agents

**链接**: https://arxiv.org/abs/2610.22426
**作者**: Hamed Khosravi, Xiaoming Huo
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are used to check records against an organization's requirements, for example whether a vulnerability report is ready for investigation. Requirements often allow several ways to be met, such as a severity rating with a curator-reviewed advisory or a published advisory link. Agents fail by accepting a report after a required check has failed, or by settling for a weaker conclusion without trying another way that could still succeed. We introduce PRIME (Precommitted Rules for Inference from Minimal Evidence). Before checking, it fixes evidence routes specifying how each conclusion may be justified. A separate program records each check result and refuses any conclusion the results do not justify. It also points the agent to checks that could justify a stronger conclusion, or runs them itself. PRIME reports only conclusions authorized by its rules and ledger. With correct requirements, exact checks at known locations, and sufficient budget at stopping, completion reaches the st

---

### [45] Poli-Bias: Understanding and Measuring Large Language Model Biases in International Political Conflicts

**链接**: https://arxiv.org/abs/2608.06123
**作者**: Massi-Nissa Abboud, Aladin Djuhera, Elena Cabrio, Holger Boche
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] HeRE: A Novel Benchmark for Hebrew Relation Extraction via LLM-Guided Denoising of Knowledge Graph Alignments

**链接**: https://arxiv.org/abs/2610.22542
**作者**: Ron Keinan, Amir David Nissan Cohen, Reut Tsarfaty
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While LLMs demonstrate strong capabilities in English Relation Extraction (RE) tasks, a significant gap remains in assessing their RE performance in low-resource languages, due to a lack of standardized benchmarks. Creating native, language-specific annotated RE benchmarks is expensive and requires human expertise, while relying on translation yields suboptimal, inaccurate datasets that introduce English-centric biases. To tackle this, we propose a scalable, language-agnostic methodology to create RE data by denoising naturally occurring yet noisy alignments of knowledge bases and corresponding texts. We define a proper alignment via a Natural Language Inference (NLI) task, where a relation triplet is entailed by an input text. We empirically assess five denoising strategies, and demonstrate that multilingual models outperform language-specific models in the few-shot LLM setting, while Hebrew-specific encoders remain competitive under NLI fine-tuning and are strongest in the label-free

---

### [47] Beyond Marginal Influence: Interaction-Aware Memory Selection for LLM Agents

**链接**: https://arxiv.org/abs/2610.23266
**作者**: BHVSP Subrahmanyam and Neeraj Choudhary
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-agent memory selection often uses retrieval rankings based on record relevance or individual influence. Such rankings cannot identify sufficient subsets under redundant or jointly necessary evidence. We study per-decision memory sufficiency: selecting a small subset that preserves full-memory behavior. To separate search error from model error, we introduce JointCoreBench, a benchmark with nine interaction families, six workflow domains, natural-language decisions, and exact sufficient-set oracles, and JointCore, a relevance cost-ordered group-deletion baseline that tests blocks before individual records. On 6,912 exact conditions, cost-ordered JointCore recovers a minimum-cost sufficient set in 100.0% of cases, reduces subset evaluations from 30.00 to 11.13 (62.9%), and achieves 87.8% active-memory savings. Across four 12B-70B model families and 432 tasks per model, its unweighted mean is 10.28 versus 16.00 model queries and 50.6% versus 43.1% minimum-cost recovery relative to cos

---

### [48] Cooperation Without Adaptation: LLM Agents in a Collective-Risk Dilemma

**链接**: https://arxiv.org/abs/2610.22882
**作者**: Trung-Kiet Huynh, Dao-Sy Duy-Minh, Chi-Nguyen Tran, Phu-Hoa Pham, Phu-Quy Nguyen-Lam, Le Hong Trang 等 (7 人)
**来源**: cs.GT cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents are increasingly deployed to act on behalf of people in settings where individual decisions shape shared outcomes. We examine whether five production models adapt their contributions to changing risks and partner behaviour, or instead follow a relatively fixed strategy. In a collective-risk dilemma game (CRG), six players contribute to a shared pool over ten rounds; if the pool falls short of its target, a catastrophe may destroy their remaining resources. Four models contributed approximately an equal share at every positive risk level, and four of the five also contributed when risk was zero, even though contributing could not improve their payoff. Explicitly stating that only the agent's own payoff mattered reduced zero-risk contributions for most models, while a more neutral prompt did not. Several models correctly identified which action offered the higher expected payoff at different risk levels, yet their contributions changed little. Against fixed partners

---

### [49] Structured Authority Injection: Persistent Human Control for LLM Agents via Typed MCP Overrides

**链接**: https://arxiv.org/abs/2610.22373
**作者**: Ryan Tran, YueMing Zhang, Lingfeng Tao, Nan Yang, Shengjie Xu, Yu Yin 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly used as autonomous orchestrators in distributed and multi-agent systems, yet a control gap remains: no protocol-level mechanism allows human operators to inject binding directives that persist across planning cycles. Free-text overrides suffer from ambiguous interpretation due to lack of schema validation and from authority erosion as operator instructions lose influence within accumulating context. We propose Structured Authority Injection (SAI), a protocol that addresses these issues by routing operator corrections through typed, schema-validated Model Context Protocol (MCP) tool calls and maintaining a ranked authority context prepended to each LLM prompt. SAI defines three override classes (Constraint, Priority, and Strategy) with distinct persistence semantics and an explicit precedence order enforced via a directed authority channel inaccessible to the planning process. The method requires no model fine-tuning or access to model weights and appli

---

### [50] Response-Informed Value Estimation for Cost-Aware Multi-Turn LLM Routing

**链接**: https://arxiv.org/abs/2610.23239
**作者**: Haotian Yan, Jiaqi Liu, Bingyi Jing, and Tianjun Yao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn LLM routing selects a model at every turn before its response is available, yet task success is revealed only when the interaction ends, leaving each intermediate choice without a label of its own. Logged trajectories, however, retain the response each call produced, which exposes what each turn required and how well the chosen model served it, evidence that outcomes alone hide. We introduce RIVET (Response-Informed Value Estimation for Turn-Level Routing), which exploits this post-call evidence during training while keeping routing strictly pre-call at deployment. RIVET jointly trains two value estimators over a shared state-model representation: a deployable Routing Value Estimator that scores candidate models from pre-call information, and a training-only Response-Informed Value Estimator that additionally observes the realized response. Conditioning on the response turns response-induced return variation from residual noise into an observed covariate, and we show that th

---

### [51] Robust Function Calling for LLM Agents Under Interface Drift

**链接**: https://arxiv.org/abs/2610.23342
**作者**: Aniruddha Chattopadhyay, Kanishka Halder, Partha Sarathi Roy
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-augmented language-model agents rely on interface text: tool descriptions, argument schemas, and the candidate tool list shown at inference time. These interfaces often change after deployment even when the underlying tool semantics remain fixed, creating a practical reliability problem for function-calling systems. We study this failure mode as interface drift and evaluate whether a lightweight, training-free repair layer can recover robustness without retraining the base model. Our method, SchemaShield-Lite, combines schema validation, candidate-set retry for missing tool names, and one-shot constrained repair. On Qwen3.5-9B, it raises DICE-300 accuracy from 0.717 to 0.813 and BFCL-200 accuracy from 0.580 to 0.805, recovering 19/22 and 33/45 drift-induced failures with no observed repair harms. Naive retry does not explain the gains. Ablations show that candidate-set drift, especially distractor tools, accounts for most observed damage, while description and schema edits alone a

---

### [52] Inferring L1 Backgrounds from L2 English with LLM Token Probabilities

**链接**: https://arxiv.org/abs/2610.23309
**作者**: Ahmet Yavuz Uluslu, Mark Gales, Kate Knill, Gerold Schneider
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Native language identification (NLI) infers a non-native speaker's first language (L1) from their second language (L2) production. We investigate a token probability approach that scores each text sample as a continuation of a prompt prefix specifying a candidate L1, then predicts the candidate with the highest score. We evaluate our approach using Llama 3.1 8B and 70B on three datasets: TOEFL9, Write and Improve 2024, and BULATS-L1. We compare its performance with previous prompting-based classification approaches. Token-probability scoring substantially improves on direct classification, particularly with the 8B model, while the 70B model achieves state-of-the-art performance across all datasets. Our results indicate that pretrained LLMs' token probabilities contain information useful for distinguishing L1 backgrounds from L2 English production.

---

### [53] Two Minds Better Than One: Collaborative Reward Modeling for LLM Alignment

**链接**: https://arxiv.org/abs/2505.10597
**作者**: Jiazheng Zhang, Wenqing Jing, Zizhuo Zhang, Zhiheng Xi, Shihan Dou, Rongxiang Weng 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] The LLM-Attacker: A Unified Red-Team Framework for Privacy Evaluation of Split and Distributed LLM Systems

**链接**: https://arxiv.org/abs/2610.22722
**作者**: Georgios Politis and Evangelos Pappas
**来源**: cs.CR cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Split language models keep input text on a client but send intermediate representations to a server. Attacks can reconstruct text from these messages. Comparing privacy evaluations is difficult when attackers see different messages, know different model weights or use different datasets and recovery measures. We present LLM-Attacker, a framework that records these choices and lets researchers check, compare and extend an evaluation. Compatible attacks reuse recorded messages, and their predictions are saved for independent scoring. The scoring rule requires a linked undefended reference before a defence can pass. Reports also identify attacks that remain untested. In a controlled GPT-2 experiment, adding gradients returned during training increased token recovery from 94.20% to 97.38% and exact-document recovery from 13.71% to 37.77%. The 95% interval for the token gain lay above the two-percentage-point threshold fixed before testing. This experiment is shared with a companion study; 

---

### [55] The Ephemeral Cost of Switching Optimizers Across LLM Training Stages

**链接**: https://arxiv.org/abs/2610.22650
**作者**: Xinyu Zhao, Davis Wertheimer, Ashutosh Sharma, Rameswar Panda, Paul Pu Liang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work suggests that switching optimizers between pretraining and subsequent training stages incurs a performance cost, but systematic investigation of this phenomenon is lacking. We study the mismatch between AdamW and Muon optimizers by pretraining 1.2B Llama-3 models from scratch while varying the proportion of updates taken with each optimizer, and similarly interpolating between the two optimizers during continued pretraining and supervised fine-tuning (SFT). Surprisingly, we find little evidence of a meaningful optimizer mismatch penalty: final performance is largely explained by the independent effects of the pretraining and post-training optimizers, with downstream performance generally improving as the proportion of Muon updates during SFT increases. Although matching the pretraining optimizer can reduce forgetting during SFT, this does not translate into improved final benchmark performance. We further evaluate AdamW and Muon for task-general SFT of open-weight models, a

---

### [56] GVPO: Group Variance Policy Optimization for Large Language Model Post-Training

**链接**: https://arxiv.org/abs/2504.19599
**作者**: Kaichen Zhang, Yuzhong Hong, Junwei Bao, Hongfei Jiang, Yang Song, Dingqian Hong 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] PresenceBench: An Exploratory Evaluation of Large Language Model Adaptation to User State

**链接**: https://arxiv.org/abs/2610.23625
**作者**: Pe\~na Arroyo Gallego, Mauro Ruiz Moreno, Alejandro Acien, Sergio Romero-Tapiador, Teresa Arroyo-Gallego
**来源**: cs.HC cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Presence-aware intelligence is the capacity of an AI system's intelligence layer to adapt appropriately to the functional state of the person it serves (here readiness, flow, and stability) while preserving task quality and safety. We introduce PresenceBench, an instrument for measuring it. PresenceBench evaluates how the intelligence layer uses a supplied state, not how that state is sensed, and breaks the capability into measurable properties. Two are tested here. Receptivity: does the model take up the state and give a better response than with no signal? Specificity: does any improvement depend on the correct state, rather than on extra structured context? A third, adaptation across states, is a required endpoint not measured in this release. A five-arm causal design answers both questions, against each model's own baseline and an equally structured mismatched-state control, scored by a correctness-gated human paired comparison. The exploratory evaluation covered four models across

---

### [58] Self-Evolving Coding Agents via Harness-Policy Optimization

**链接**: https://arxiv.org/abs/2610.22791
**作者**: Zhepei Wei, Wenlin Yao, Baolin Peng, Danqing Wang, Qianhui Wu, Hao Cheng 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have shown promising potential in coding tasks, and their performance is jointly determined by the policy model and the harness that mediates their interaction with the environment. Indeed, harness and policy are mutually reinforcing and evolving only one component is suboptimal---a harness tuned for one checkpoint may not target the failure modes of an updated policy, while policy learning remains limited to the trajectories elicited by a fixed harness. In light of this, we propose Self-HPO, a recursive self-improving framework for coding agents that alternates harness and policy optimization, using the evolving policy as its own harness proposer. Specifically, in each round, the current policy first analyzes its own failures and proposes new harness candidates (H-step). The policy is then updated through reinforcement learning (RL) under the selected harness (P-step), and hard tasks identified during training form the next harness search set, keeping

---

### [59] DLite: History-free Speculative Decoding for Agentic AI

**链接**: https://arxiv.org/abs/2610.23787
**作者**: Jiaming Xu, Hanzhen Wang, Tianlang Zhao, Jiewen Xiao, Chengze Yuan, Jiayi Pan 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding has become a mainstream technique for accelerating large language model (LLM) inference by using a lightweight draft model to generate candidate tokens that are subsequently verified by the target model. However, agentic workloads introduce long and continuously evolving contexts and frequent multi-turn interactions. Under such workloads, we observe that existing draft models suffer from up to an 80% degradation in acceptance length, while maintaining their historical KV cache introduces substantial system overhead. In this paper, we identify the growing historical context as a common source of both problems and introduce DLite, a history-free speculative decoding framework for agentic AI. DLite directly reuses contextual hidden states from the target model and performs local speculative prediction without explicitly maintaining the historical context, transforming an increasingly complex modeling problem into local simple prediction problem. A lightweight sequenti

---

### [60] Beyond Latent Personalization: Integrating HRV-Conditioned Personalization via LLM for Interpretable Stress Detection

**链接**: https://arxiv.org/abs/2610.23555
**作者**: Wei-Hsiang Ma, Ya-Tse Wu, Hsing-Hang Chou, Chi-Chun Lee
**来源**: eess.SP cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Stress detection based on heart rate variability (HRV) has received increasing attention. However, existing personalized approaches integrate personal attributes with HRV through latent representations, limiting the interpretability of their interactions. In this work, we propose an LLM-enhanced personalized stress detection framework that integrates HRV features and personal attributes through LLM-based semantic interpretation. The proposed framework achieves a 29.9% relative MCC improvement over the strongest baseline on TILES-2018 while providing human-readable descriptions of individual physiological responses. The results highlight the potential of LLM-based semantic interpretation for achieving both effective and interpretable personalized stress detection.

---

### [61] Rethinking User Encoders: Routing Diffusion States for Scenario-Adaptive User Representation

**链接**: https://arxiv.org/abs/2610.22400
**作者**: Junru Zhang, Jinyong Wen, Bin Dou, Wuliang Huang, Baokun Wang, Yu Cheng 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing large language model (LLM)-based user encoders serialize heterogeneous behavioral logs and compress them into static representations through autoregressive (AR) prediction. However, their unidirectional constraint limits bidirectional information flow, hindering cross-modal interactions and the joint preservation of multi-source signals. Consequently, the learned static representations struggle to accommodate the distinct evidence requirements of diverse downstream scenarios. We address these limitations by unlocking the iterative denoising process of diffusion language models (dLLMs) as a multi-granularity reconstruction space. Based on this insight, we propose FINDERS (FactorIzatioN of Diffusion statEs for Routing across Scenarios), a router-equipped dLLM framework comprising four operations: denoise, factorize, route, and compress. Learnable meta-slots organize complementary denoising states into transferable cross-modal semantics and modality-specific behavioral factors. T

---

### [62] Chance-Constrained Personalized LLM Routing with Online Preference Learning

**链接**: https://arxiv.org/abs/2610.22695
**作者**: Ameya Anjarlekar, Rasoul Etesami, R Srikant
**来源**: cs.LG stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study personalized LLM routing, where a router selects among heterogeneous models with different costs and capabilities. The router must minimize cumulative inference cost while ensuring reliable realized response quality, even though user preferences are unknown and must be learned from feedback during deployment. We formulate this problem as a constrained contextual bandit and develop an algorithm that learns preferences while balancing cost and quality. Under a logistic preference model and a strict-feasibility condition, we establish sublinear expected cost regret relative to an optimal stationary randomized contextual oracle and a high-probability guarantee on realized cumulative satisfaction. The framework extends beyond LLM routing to broader online model-selection problems with reliability requirements.

---

### [63] Darwin-Claw: Environment-Adaptive Experience Consolidation for Recursively Self-Evolving Agents

**链接**: https://arxiv.org/abs/2610.23574
**作者**: Mingze Yin, Xiaohan Wang, Dian Li, Longfei Luo, Jiahong Yan, Yiheng Zhu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Model (LLM) agents have demonstrated remarkable capabilities across complex tasks, they predominantly operate in isolated sessions, lacking the ability to continually learn from historical interactions or adapt to user-specific environments. Existing self-evolution paradigms often indiscriminately inject raw interaction trajectories into memory or skill modules, leading to obscured behavioral patterns and compromised update controllability. Furthermore, as foundational LLM reasoning improves, the bottleneck for agentic evolution shifts from accumulating generic knowledge to effectively managing situational experience. To address this, we propose Darwin-Claw, an environment-adaptive self-evolving framework that systematically distills episodic experiences to drive the comprehensive evolution of operational skills and durable memory. Theoretically grounded in an iterative agent-actor and evolver-critic co-adaptation, Darwin-Claw introduces a Hierarchical Experience C

---

### [64] Monitor-Validity Failures: LLM Safety Evidence Paths at Evolving Framework Boundaries

**链接**: https://arxiv.org/abs/2610.23362
**作者**: Junchi Liao
**来源**: cs.AI cs.CR cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM applications rely on runtime monitors that inspect tool calls, traces, streams, detector outputs, and verifier inputs. This creates an interface-reliability problem: a framework path may remain operational while policy-relevant evidence never reaches its decision point. In one representative case, a regex detector returned a positive match, but the framework stranded the result before the block decision. This differs from jailbreaks and detector errors because the evidence is already recognized yet disconnected from enforcement. We study this repair-boundary signature with canary contracts: parent/fixed confirmation units that place a known payload only on the changed evidence surface and record monitor visibility together with the downstream decision for action-boundary cases. Applying the protocol to public framework repairs, we confirm 18 evidence-path failures across 11 LLM or agent safety project groups and four implementation ecosystems. Nine are established-boundary r

---

### [65] Rethinking Quality in Large Language Model Routing: Security-Conditioned Model-and-Budget Selection

**链接**: https://arxiv.org/abs/2610.18566
**作者**: Yichi Zhang, Zhenxiang Huang, Yuyang Zhang, Yuchen Yang
**来源**: cs.AI cs.CR
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] KiranaBench: Can a Language Model Run a Neighbourhood Shop?

**链接**: https://arxiv.org/abs/2610.22980
**作者**: Bhuvan Arora, Ankita Karmakar, Chaitanya Jain, Dilesh Churiwal, Harshit Jain, Shivansh Manish Dubey 等 (10 人)
**来源**: cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly evaluated on long-horizon tasks, including autonomously running a business. Existing benchmarks for this setting are almost exclusively English-language, Western in retail context, and single-agent, with the agent observing the business directly. We study how these results transfer to a multi-agent Indic setting. We introduce KiranaBench, a simulated Indian general store in which four roles (manager, cashier, helper, and bookkeeper) are each played by a separate LLM agent. Interactions with customers and suppliers occur in English, Hindi, or Hinglish, and product demand is calibrated to India's national Household Consumption Expenditure Survey. Evaluating four open-weight LLMs, we find that all fall far short of a fixed-rule shopkeeper baseline: the best model earns only one-eighth of the baseline's profit, and two models finish below an unmanaged shop. Performance is also consistently lower for Hindi and Hinglish than for English supp

---

### [67] CoLU: Confidence-Weighted Layerwise Unlearning for Large Language Models

**链接**: https://arxiv.org/abs/2610.22721
**作者**: Jingkai Guo, Ziyi Zhao, Chaitali Chakrabarti, Deliang Fan
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) unlearning aims to forget certain information while preserving others, without retraining from scratch. SoTA methods such as NPO, SimNPO, and SatImp balance forgetting and retain through whole model fine-tuning, while FOM-UL explores selective layer updates. Prior works show that suppressing target information can damage retained knowledge. This trade-off can vary across layers even under the same unlearning loss. In this work, we propose Confidence-Weighted Layerwise Unlearning (CoLU), which combines a novel confidence-weighted forgetting and retain regularization while updating a single selected transformer layer, rather than the whole model for unlearning. To reduce CoLU compute cost, we further propose Brief Layer Screening (BLS), which uses a newly defined normalized forgetting-retention (NFR) score to first rank layers through a brief unlearning trials using a subset of forgetting dataset and fewer epochs. BLS pre-selects top-k ranked layer candidates, 

---

### [68] Harness-Driven Agentic Operation of Optical Pooled Screen Analysis

**链接**: https://arxiv.org/abs/2610.22617
**作者**: Matteo Di Bernardo, Claire Peterson, Ege Topkoc, Matt Might, Iain M. Cheeseman
**来源**: q-bio.GN cs.HC q-bio.QM
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optical pooled screens connect genetic perturbations to changes in cell morphology and behavior, but turning the microscopy data into interpretable results takes complex, multi-day analyses. Established pipelines process this data, yet researchers still select parameters, inspect outputs, and resolve failures for each experiment. Here, we present Brieflow-auto, a pipeline-specific harness implemented as a Claude Code plugin that lets a coding large language model (LLM) operate Brieflow, an open-source end-to-end pipeline for optical pooled screening data. A researcher supplies experimental facts and approves the launch. An agent tunes parameters in an interactive notebook, and the harness validates the configuration, monitors execution, recovers from common failures, and checks output quality. For pipeline defects, the agent opens upstream issues proposing backward-compatible fixes for the broader community. In five previously analyzed screens, harness runs yielded more cells with a co

---

### [69] Analyzing Occupational Gender Bias across the LLM Training Lifecycle

**链接**: https://arxiv.org/abs/2610.23587
**作者**: Manthan Gadhia, Alexander Hoyle, Karolina Sta\'nczak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training is widely assumed to reduce the social biases language models inherit from pretraining, yet direct evidence for this assumption remains mixed. In this paper, we examine how gender disparities evolve across the language modeling pipeline. In particular, we study occupational gender bias in OLMo 3, a fully open language model family, across its post-training stages by prompting each checkpoint to generate open-ended narratives about synthetic personas given their occupation and education. We consider two settings, a gender-given setting in which the profile states the persona's gender explicitly and a gender-assumed setting in which it must be inferred by the model. We find that when gender is stated, post-training increases semantic diversity for male-coded profiles, whereas for female-coded profiles the increase is smaller after SFT and not significant after DPO and RLVR. When gender is assumed by the model, post-training affects narratives about female and male personas 

---

### [70] Not All Test-Time Compute Is Evidence: Model-Specific Bias in LLM Reasoning

**链接**: https://arxiv.org/abs/2610.23213
**作者**: Ming Shen, Tianjun Yao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling methods implicitly assume that additional computation from the same model provides independent evidence. We show that this assumption fails within a single reasoning model: errors are correlated across repeated samples, across reasoning depth, and in the model's own self-evaluation, so more compute from the same model is not more evidence. We introduce DIA (Disagreement-triggered Independent Arbitration), which treats disagreement between an intermediate-stage and the final-stage prediction as a per-question signal of reasoning instability and resolves it by asking a small panel of heterogeneous models to solve the question independently, without seeing either candidate, and aggregating their answers directly. Across seven benchmarks and two base models, DIA outperforms full chain-of-thought in 12 of 14 settings, including a 7.00% gain on MuSiQue, while activating on only $\sim 17\%$ of examples and using up to 47.2% fewer tokens than a multi-agent baseline. Ablations

---

### [71] "You" Is Not Toxic: How LLM Labelers Rewrite the Web's Conversation Laws

**链接**: https://arxiv.org/abs/2610.23446
**作者**: Liang Yue, Eric A. Vance
**来源**: cs.SI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What the Web community believes about toxic conversations, such as that toxicity rises in longer and deeper threads, was measured mostly with Google's Perspective API, which is shutting down; large language models (LLMs) will make the next measurements. We find that LLM labelers mistake second-person address for toxicity, and that this one bias manufactures laws that human labels do not show. On 1.25 million news comments with crowd labels, Claude Haiku flags 12% of the non-toxic comments that contain no "you" and 51% of those with four or more; a single crowd rater flags 6% and 10%. Deeper replies address someone more often, so under Haiku toxicity rises with reply depth (+0.93 percentage points per level), while under the crowd's labels it slightly declines (-0.12). Rewriting "you" in the third person removes two thirds of the false rise; flagging only as many comments as the crowd does not remove it, and showing Haiku the parent comment enlarges it. All seven LLMs we test over-flag 

---

### [72] Wait for It: A Component-Level Analysis of Latency Feedback Mechanisms for LLM Agents in VR

**链接**: https://arxiv.org/abs/2610.23336
**作者**: Pratham Arora, Abhinav Lodha and Siddharth Siddharth
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Delays in AI responses pose a significant challenge to immersive Virtual Reality experiences. While previous research demonstrates that feedback can reduce the perception of waiting, we lack understanding of which types work best and why. We conducted a within-subjects study with 18 participants to systematically compare three isolated feedback approaches during VR agent interactions: verbal fillers (e.g., um..., hmm...), visual indicators (loading spinners), and embodied gestures (thinking animations). Our results revealed that embodied gestures significantly outperformed visual loading indicators across multiple dimensions, making agents feel more lifelike and socially present. Interestingly, explicit visual feedback like loading spinners actually degraded perceived humanness and broke immersion by forcing users to shift from social to technical mental models. These findings suggest that natural, behavior-based feedback maintains the illusion of conversing with a thinking entity, whi

---

### [73] Evo-B&B: Behavior-Aware LLM-Guided Joint Evolution of Branching and Node Selection Policies for MILP

**链接**: https://arxiv.org/abs/2610.22861
**作者**: Jiayu Chen, Chentong Chen, Yuhan Liu, Ye Fan, Jianyong Sun, Jialong Shi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In branch-and-bound for Mixed-Integer Linear Programming (MILP), branching and node selection are two critical and tightly coupled decisions, yet most existing learning-based approaches focus on optimizing them separately. We propose Evo-B&B, an LLM-guided evolutionary framework that jointly evolves executable branching and node selection policies using end-to-end SCIP solving feedback. To improve search efficiency and reduce redundant evaluations of behaviorally similar policies, Evo-B&B introduces a behavior-aware multi-island evolutionary mechanism. It measures policy similarity from branching and node-selection behaviors on a fixed set of B&B decision states and uses this similarity to preserve population diversity. We evaluate Evo-B&B on four standard MILP benchmarks across multiple instance scales. Experimental results show that Evo-B&B achieves competitive solving performance and generalizes well to larger-scale instances, while ablation studies further demonstrate the effective

---

### [74] SAFETYEDIT: Sparse Internal Targets with Prompt-Wide Control for LLM Jailbreak Backdoors

**链接**: https://arxiv.org/abs/2610.22640
**作者**: Yutong Ke, Yansu Wang, Zeyu Zhang, Xihao Guo, Chongwen Zhao, Kaizhu Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model-editing backdoors aim to induce harmful responses under a trigger while preserving ordinary behavior on untriggered input. Recent model-editing approaches target affirmative response prefixes through rank-one updates to a small subset of model weights. Yet when this prefix-level target is satisfied, the model may still revert to refusal or produce a coherent, apparently compliant response that does not address the request. To overcome this limitation, existing internal-representation approaches shift focus from output tokens to dense, high-dimensional compliance directions in latent space. Existing representation-level approaches rely on preservation constraints to maintain conditionality, motivating us to ask whether a smaller internal target can offer a different effectiveness-preservation trade-off. Motivated by the comparable control capability of single-coordinate interventions, we investigate a sparse refusal-related MLP coordinate as this target. We propose SAFETYEDIT, whi

---

### [75] Paved with True Intents: Intent-Aware Training Improves LLM Safety Classification Across Training Regimes

**链接**: https://arxiv.org/abs/2606.27210
**作者**: Jeremias Ferrao, Niclas M\"uller-Hof, Iustin S\^irbu, Traian Rebedea, and Yftah Ziser
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] Beyond Surface Cues: Robust LLM-Generated Korean Text Detection

**链接**: https://arxiv.org/abs/2610.22940
**作者**: SungHo Kim, SangKeun Lee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) generate increasingly fluent text, the need for reliable detection of LLM-generated content has grown substantially. However, existing research remains heavily English-centric, leaving Korean largely underexplored. Moreover, current evaluations of Korean text detection often rely on superficial cues, leading to overly optimistic estimates of detection performance. To address these limitations, we introduce \textsc{KoLing}, a bias-controlled adversarial benchmark comprising 50.9k instances that suppresses superficial shortcuts while preserving semantic content and separately evaluates LLM-generated and LLM-modified text detection. We further propose KoLingProbe, an interpretable detector grounded in theoretical linguistics that models Korean-specific properties across multiple linguistic levels. Experiments show that KoLingProbe substantially outperforms strong baselines on all detection tasks while remaining robust to adversarial attacks. Our analyses fu

---

### [77] APeB: Benchmarking Personalization Ability of Large Language Model Agents

**链接**: https://arxiv.org/abs/2607.03162
**作者**: Garry Yang, Zizhe Chen, Xinru Chen, Yongqiang Chen, Jianxiang Wang, Deyu Zou 等 (10 人)
**来源**: cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Veil-Then-Reveal: Protecting PII Privacy via Reversible Pseudo-Anonymization in Zero-Trust User--LLM Interaction

**链接**: https://arxiv.org/abs/2610.22800
**作者**: Mohamed Shaaban, Mohamed Elmahallawy, and Thomas E. Carroll
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly process sensitive documents and personal information, yet sending prompts containing personally identifiable information (PII) to remote providers exposes data subjects and organizations to risks from logging, retention, model training, and unintended disclosure. Existing anonymization methods often mask or remove PII, while conventional encryption eliminates the lexical and structural cues needed for effective LLM processing. We present Veil-then-Reveal (VtR), a user-side PII pseudo-anonymization framework for privacy-preserving LLM interaction under a zero-trust threat model. VtR treats remote LLM providers as untrusted and sends only pseudo-anonymized prompts, keeping plaintext PII on the user. VtR first detects PII and replaces it with realistic, same-type, in-vocabulary surrogates before prompts leave the user's device, preserving their linguistic and structural properties. It combines format-preserving encryption (FPE) for structured PII,

---

### [79] WaveLLM: Wavelet-Domain LLM Entropy Modeling for Lossless Image Compression

**链接**: https://arxiv.org/abs/2610.22232
**作者**: Yue Yu, Bowei Kang, Changsheng Gao, Dong Liu, Xiaoyan Sun
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] Uncertainty-Aware Budget Allocation for Efficient LLM Tree Search

**链接**: https://arxiv.org/abs/2610.22858
**作者**: Jianguo Huang, Zhiyi Lyu, Fuxiang Zhang, Yanchen Deng, Deheng Ye, Bo An
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tree search enhances multi-step reasoning in large language models (LLMs), yet prevailing methods expand every step with a fixed budget, irrespective of the marginal utility of expansion. We first show, across existing search algorithms, that continuations sampled from a shared intermediate state are largely duplicates and collapse to a few distinct answers. Critically, we find that the semantic dispersion of sibling actions predicts the redundancy of their downstream continuations, permitting a subtree's budget to be fixed before expansion. An information-theoretic analysis motivates this: treating the per-step budget as the Monte Carlo sample size for estimating a step's residual answer entropy, we derive a sufficient budget that shrinks with sibling dispersion. We accordingly propose $\textbf{Uncertainty-Aware Allocation}$ (UAA), a training-free framework that decouples value from uncertainty: values determine which candidates are promising, while uncertainty, estimated from sibling

---

### [81] Ori: Drift-Aware Streaming $k$-PCA for Very Low-Rank LLM Training

**链接**: https://arxiv.org/abs/2610.22794
**作者**: Xinyu Luo, Jincheng Zhou, Mengbo Wang, Zilin Shen, Nadia Atallah Lanman, Petros Drineas 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A prominent family of low-rank LLM optimizers, pioneered by GaLore, performs gradient-subspace projection: at each step, they project the gradient into a low-dimensional subspace and map the update back to the full model. Most existing work either recomputes the gradient subspace at certain intervals, or performs post-hoc adaptation to catch up to the moving subspace. In this work, we explicitly identify in practice the slow, stable manner in which LLM gradient subspaces drift across time. To this end, we propose Ori, a novel low-rank optimizer for training LLMs that captures the shifting principal gradient directions over time to achieve state-of-the-art accuracy under stringent low-rank constraints. Ori employs a streaming $k$-PCA algorithm inspired by Oja++, whose low per-step cost enables high-frequency, on-the-fly subspace tracking. In practice, Ori reduces the performance gap of the state-of-the-art low-rank optimizers to full-rank optimizers by up to 69.3\% on a 1B LLaMA pretrai

---

### [82] From Trajectories to Differentiated Skills: Cognitive Differentiation for Self-Improving Agents

**链接**: https://arxiv.org/abs/2610.23599
**作者**: Yewei Zhao, Derong Xu, Wei Chen, Yin Xu, Peilun Zhou, Xiaohan Wang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents tackle complex tasks through reasoning and interaction with external environments. Agent skills provide persistent, transferable capabilities that guide task planning, inform contextual decisions, support tool use, and enable executable procedures. Yet existing skill-evolution methods largely organize knowledge around skill artifacts, overlooking the functional heterogeneity within individual skills and its implications for knowledge maintenance and use. Inspired by cognitive science, we propose Cognitive Differentiation in Skill Evolution (CDSE), which evolves a unified skill through four functionally distinct yet coordinated components: Meta, Experience, Tool, and Script. CDSE extracts evidence-grounded semantic gradients from successful and failed trajectories, consolidates them by functional role, and applies component-specific updates and validation with cross-component coordination and adaptive invocation. An analysis of 500 top-ranked skill pack

---

### [83] Recognizing Study Lineage Is Not Enough: Over-Crediting Same-Trial Evidence in LLM-Based Medical Verification

**链接**: https://arxiv.org/abs/2610.23721
**作者**: Mukand Krishna, Anoushka Harit, Chenghao Xiao, Zhongtian Sun
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Publication count is not study count. A model can identify shared trial lineage correctly in a direct task yet over-credit a second publication from the same trial when aggregating evidence. We evaluate this behavior in medical LLM verification using 14 source-audited clinical families and five model conditions. The families span provenance, clinical applicability, result direction, and composition; the provenance families provide the direct lineage tests. Recognition and aggregation are separate stateless calls, and repeated calls assess within-input stability. Across all three original provenance families, GPT-5.5 identifies the independent update in 10/10 recognition calls per family but over-credits the same-trial report in 5/5 separate aggregation calls per family. Selected Qwen3-4B and Ministral-3-8B conditions show the same cross-task contrast. A study-grouping instruction reduces GPT-5.5 over-credit from 4/5 to 0/5 in each later pure-provenance family. Other model conditions sh

---

### [84] SAG2: Embedding-Free Multi-Hop Retrieval with BM25 and JEV

**链接**: https://arxiv.org/abs/2610.22588
**作者**: Yuchao Wu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Strong multi-hop retrieval should be practical to deploy without expensive corpus preparation or complex database infrastructure. We present SAG2, an embedding-free retrieval architecture built around a single SQLite database, BM25, and contextual evidence decisions from JEV. SAG2 follows the query-time association principle of SAG (SQL-Retrieval Augmented Generation), while replacing its event-entity and dense indexes with a lexical index over original passages. Selected passages supply terms for further retrieval, and newly retrieved evidence guides subsequent decisions. This moves semantic evidence selection to query time, eliminating offline embedding computation, LLM-based event-entity extraction, and dedicated database servers. The resulting system combines lightweight preparation with strong retrieval accuracy: on 1,000-question subsets of MuSiQue, 2WikiMultiHopQA, and HotpotQA, SAG2 achieves the highest Recall@5 and Recall@10 among the compared methods, with Recall@10 of 86.62%

---

### [85] VTrajEmbed: Aligning Text with Video Object Trajectories via Spatiotemporal Embeddings

**链接**: https://arxiv.org/abs/2610.22842
**作者**: Ruizhi Chen, Zining Fan, Yudi Guo, Jiang Liu, Zhiyu Lin, Zhongjiang He 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-grained alignment between text and video object trajectories is a core challenge in multimodal understanding. Existing embedding models excel at global retrieval, yet their single global representation entangles multiple objects and their spatiotemporal dynamics, limiting direct object-level grounding. To address this issue, we propose VTrajEmbed, an embedding model that decomposes a video into object trajectories and aligns each trajectory embedding with text for object-level grounding through retrieval. Our main contributions: (1)Slow-Fast Trajectory Encoding, a dual-branch architecture that establishes trajectory representations by densely sampling low-resolution frames for high-frequency motion cues and sparsely selecting high-resolution frames for scene context, aggregated by a shared LLM backbone; (2)Mask-Guided Contrastive Learning, a training objective built upon these representations that couples an intra-group loss and a batch-level bidirectional loss under a relation ma

---

### [86] Perceive, Solve, Reason: Progressive Capability Formation in Time Series-LLMs

**链接**: https://arxiv.org/abs/2610.23521
**作者**: Xin Qiu, Junlong Tong, Wei Zhang, Xiaoyu Shen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can now perceive, describe, and reason about images and audio, yet time series understanding remains underestimated: most work uses LLMs as forecasters and classifiers, reasoning studies are few and narrow, and no suite trains and evaluates the full range of capabilities. In this paper, we build the first such suite, with 337K training and 44K evaluation samples across three progressive capabilities, Perceive, Solve, and Reason, and use it to ask how time series should enter an LLM that must master all three, and in what order. We find that a dedicated encoder is essential: with one, a 4B model surpasses GPT-4o on every perception attribute we test, whereas textualizing the series costs 8--10 points in reasoning accuracy. The capabilities then build on one another: learning them in order beats mixing the same data and rivals reasoning-only training with over three times the reasoning data, but only when an encoder is used. Analyses further reveal that capab

---

### [87] Where Does the Performance Go? Understanding and Recovering Performance Regressions in C-to-Rust Translation

**链接**: https://arxiv.org/abs/2610.23044
**作者**: Zhiqiang Yuan, Chong Wang, Zhenhao Zhou, Junwei Liu, and Xin Peng
**来源**: cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rust is increasingly adopted as a memory-safe successor to C, and transpilers such as \crust{} can migrate entire C projects while preserving their behavior. Preserving behavior, however, does not guarantee preserving performance. We study this gap on 20 real-world C projects and their \crust{} translations. On the eight projects used for analysis, the translated Rust is more than 3\% slower than the original C on 12 of 19 operations, by up to 62.2\%. By comparing execution-cost profiles, optimized LLVM IR, and compiler optimization remarks across each C--Rust pair, we trace these slowdowns to nine recurring performance issues, spanning residual runtime work, missed compiler optimizations, and C-style source patterns, and derive an optimization direction for each. We then present \ourtool{}, an LLM-based approach that encodes these issues as reusable optimization rules to recover the performance of translated Rust. \ourtool{} profiles each project to locate hot functions and matches th

---

### [88] The Italian lawmaking process: a unified and structured dataset

**链接**: https://arxiv.org/abs/2610.23741
**作者**: Matilde Contestabile, Chiara Ferrara, Giovanni Parrillo, Lorenzo Emer and Andrea Vandin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Italian legislative process is documented in detailed parliamentary records hosted in institutional websites. However, much of this information is available only as unstructured text, limiting its systematic reuse. We applied a controlled, systematic LLM-based extraction procedure, validated against manually annotated records, to convert these texts into ordered and dated events including, e.g., bill introduction, committee examination, plenary examination, and approval. The resulting dataset reconstructs the procedural histories of all 5346 Italian laws enacted between 1985 and 2026, spanning parliamentary terms IX to XIX, for overall 101413 events. Each event records the activity, date, and chamber, with additional procedural details where available. The dataset supports research in the emerging fields of computational legal and legislative studies, potentially combined with process-oriented data science methods to examine procedural paths and legislative timing across parliament

---

### [89] SIT-Eval: Situation-Based Interactive Turn-by-Turn Evaluation of Conversational Agents

**链接**: https://arxiv.org/abs/2610.23612
**作者**: Ravil Mussabayev, Saveliy Zavertyaev, Dmitriy Parpulov, Andrey Savchenko
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid proliferation of conversational AI agents necessitates evaluation methods that assess performance across diverse dialogue scenarios, utilizing multiple situational criteria, as appropriate behavior depends on context and encompasses various aspects. Existing dialogue benchmarks typically use static natural conversations, which underrepresent rare situations---a critical safety gap, as low-probability events become frequent failures at production scale. However, limited sample sizes force a choice: either maintain natural dialogues for realism or turn to adaptive situation sampling for comprehensive yet statistically reliable coverage. We introduce SIT-Eval, an adjustable framework for evaluating situation-based conversational agents. We formalize an agent's desired behavior as situational rules: if situation is P, follow rules Q. At each conversation turn, an LLM-interlocutor enacts a uniformly sampled situation. A context-aware LLM-judge leverages all conditionally applicabl

---

### [90] What Shapes Brain Alignment of Large Language Models during Dialogue? Insights from Language Production and Comprehension

**链接**: https://arxiv.org/abs/2610.22961
**作者**: Yuko Nakagi, Yuya Chiba, Yasue Kishino
**来源**: cs.CL cs.LG q-bio.NC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain alignment of large language models (LLMs) offers a way to investigate representational similarities between LLMs and the human brain during language processing. While previous studies have mainly focused on passive language comprehension, little is known about such alignment during dialogue, in which speakers engage in both language production and comprehension. In this study, using fMRI data collected during dialogue, we examine brain alignment during language production and comprehension across LLM layers and brain regions. We assess its association with the intrinsic dimension (ID) of LLM representations and the contributions of several interpretable linguistic and communicative features. Our results reveal distinct patterns of brain alignment between production and comprehension, as well as strong associations with ID in brain regions associated with each processing mode. Furthermore, we show that the contributions of linguistic and communicative features also vary across pro

---

### [91] Can AI interview? Comparing AI-led to Human-led Chat Interviews

**链接**: https://arxiv.org/abs/2610.23149
**作者**: Semra Guven, Tobias G{\aa}rdhus, Andreas Bjerre-Nielsen, Anna Rogers, Hjalmar Bang Carlsen
**来源**: cs.CY cs.CL cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model chatbots have been proposed as AI-interviewers for collecting qualitative interview data at scale, potentially bridging social science's longstanding divide between the breadth of surveys and the depth of qualitative interviews. This paper provides the first direct empirical comparison of data quality in AI-led and human-led interviews. In a randomized experiment (N = 41), university students were interviewed via synchronous text chat by either trained non-expert interviewers or a locally hosted AI system; we evaluate exposure, specificity, and relevance. Median interview duration was similar across conditions, but AI-interviewers asked more than twice as many questions per interview and elicited roughly 65 percent more respondent text per interview. Per-question responses were longer with human interviewers, though not after multiple-testing correction; only AI-condition participants skipped questions. Responses were almost uniformly on-topic in both conditions; f

---

### [92] RedDarwin: Evolving Jailbreak Skills against Frontier LLMs

**链接**: https://arxiv.org/abs/2610.23726
**作者**: Zhouyuan Ma, Yutao Wu, Hanxun Huang, Xiang Zheng, Yi Liu, Xingjun Ma
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Red teaming must continually adapt as frontier LLM safeguards evolve, yet existing approaches largely search for adversarial prompts or optimize within fixed attack procedures. We observe that even when an attack becomes ineffective, its underlying mechanisms can remain useful and can be revised or recombined to construct stronger attacks. Based on this insight, we introduce RedDarwin, an agentic framework that shifts the unit of jailbreak evolution from prompts and fixed attacks to executable attack skills. RedDarwin consists of 47 reusable base skills and autonomously revises, composes, executes, and selects them using target-model feedback, allowing successful discoveries to become building blocks for subsequent evolution. RedDarwin produces 65 evolved skills, improving 44 of 47 base attacks and increasing their mean attack success rate (ASR) on AdvBench from 18.8% to 47.3%. These evolved skills consistently outperform baselines on the held-out StrongREJECT and frontier LLMs unseen 

---

### [93] ThetreStageAI: Multi-View Retrieval-Augmented Generation for Structured Bengali Theatre Production Planning

**链接**: https://arxiv.org/abs/2610.23618
**作者**: Md. Mehedi Hasan Naeem, Mst. Kamrunnahar Ruma, Shakila Sultana, Nafiza Anjum, Nasreen Jannatun Nemu, Md. Sujan Ali
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Staging a theatre performance requires coordinating dialogue, actor movement, stage directions, lighting focus, cue timing, and equipment constraints within the same production plan. This work presents ThetreStageAI, a retrieval augmented framework for structured Bengali theatre production planning. Rather than retrieving from one mixed corpus, the system maintains separate scene, actor-blocking, and lighting views. Bengali text is embedded with BGE-M3 and indexed in view-specific Qdrant collections. Retrieved references are combined with a production brief and passed to Gemini, which generates schema-constrained JSON containing characters, scenes, dialogue, stage directions, blocking, lighting, and optional sound cues. Structural and semantic checks are applied before acceptance, with at most one constrained repair attempt. We also construct a human-guided, LLM-assisted synthetic dataset of 500 short Bengali theatre records that expands to 1,500 retrieval documents. Dataset diagnostic

---

### [94] LangNCO: Compiling Natural-Language Constraints into Inference-Time Interventions for Neural Combinatorial Optimization

**链接**: https://arxiv.org/abs/2610.23190
**作者**: Hironori Ohigashi
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neural combinatorial optimization (NCO) rapidly produces high-quality solutions for problem structures encountered during training, but operational requirements may change after deployment and be communicated in natural language. We propose LangNCO, a framework that compiles instance-specific requirements into structured inference-time interventions for a frozen NCO solver, without changing the pretrained policy's architecture, learned input representation, or parameters. A pretrained LLM serves as a replaceable semantic front end, translating each requirement into a schema-validated domain-specific language (DSL) rule set. A deterministic Rule Executor applies the rules as nonexpansive hard action masks. Because local masking prevents immediate violations but does not ensure that a complete feasible continuation remains reachable, Critical-Offset Decoding extracts rule-referenced critical nodes and reallocates part of a fixed rollout budget to multi-strength biased rollouts. Using con

---

### [95] Characterising and Analysing Retrieval-Augmented Generation Techniques

**链接**: https://arxiv.org/abs/2610.23226
**作者**: Emmanuel Igbekele and Olawande Daramola
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The advent of Large Language Models (LLMs) across many application domains has increased the need for Retrieval-Augmented Generation (RAG) to reduce hallucinations and improve LLM performance. Thus far, several RAG techniques with impressive features and capabilities have been proposed in the literature, making it a herculean task to select the most appropriate RAG techniques for specific problem scenarios. Thus, we propose a conceptual framework comprising main dimensions and sub-dimensions for characterising (defining "what it is") and analysing (defining "how well it does") existing RAG techniques. The conceptual framework was developed through a qualitative analysis of the attributes of RAG techniques reported in the literature. It can serve as a pre-empirical filtering mechanism for researchers and practitioners in selecting the highest-fit RAG candidates that meet specific user and task requirements before empirical benchmarking of RAG techniques, which can be computationally and

---

### [96] MetaCurate: Evolving Curation Filters for High-Quality Agentic Coding Data

**链接**: https://arxiv.org/abs/2610.23134
**作者**: Donghoon Kim, Seunghyuk Oh, Kevin Galim, Minseo Kim, Minjae Lee, Younghyun Kim 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Supervised fine-tuning on agent trajectories is an effective way to improve coding agents, but selecting useful training examples requires more than identifying successful runs. A resolved patch may follow inefficient reasoning or unnecessary tool use, while a failed run may still contain useful intermediate steps. Training pipelines therefore rely on rules and qualitative assessments to filter trajectories, yet designing these filters typically requires substantial human expertise, and validating improvements through repeated training and evaluation is expensive. We introduce MetaCurate, a training-free framework that evolves executable trajectory curation filters using pairwise LLM judgments. Disagreements between the filter's rankings and the judge's preferences provide targeted feedback for jointly revising its rules, rubric, and aggregation policy. The resulting filter scores trajectories independently, so pairwise comparisons are required only during search. Starting from a blank

---

### [97] Disentangling Language Effects on Tool Admission and Post-Retrieval Safety

**链接**: https://arxiv.org/abs/2610.23093
**作者**: Aditya Nawal, Manit Baser, and Mohan Gurusamy
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly use retrieval tools across languages, yet their safety evaluation remains English-centric. It remains unclear whether language affects tool admission, post-retrieval generation, or both. We independently vary request, retrieved-page, and required response languages in a controlled URL-retrieval setting across ten models and seven languages. We identify Safety Loss through Interlingual Processing (SLIP). Non-English harmful requests increase mean tool admission from 46.9% to 67.4%, with a positive mean change in every model. This pattern also persists in an autonomous retrieval setup across all four models tested in this setting. Requiring answers in the page language increases pooled harmfulness on matched tool calls from 50.3% to 57.4% across four closed-weight models, mainly in Chinese and Hindi. Translating pages alone produces no consistent harm increase in eight models with comparable inference settings. Automated audits show that a non-harmful response may

---

### [98] Verbalising Model's Computation for Chain-of-Thought Faithfulness Detection

**链接**: https://arxiv.org/abs/2610.23275
**作者**: Yujing Wang, Yulan He, Wenya Wang, Hanqi Yan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current Chain-of-Thought (CoT) verification methods detect reasoning faithfulness from model outputs or static activations, but are limited in explaining how unfaithfulness develops during generation. We introduce VERITAS to verbalise the model's computation: how different reasoning anchors emerge, transfer across layers, and surface in the output. VERITAS adopts the layer-wise Jacobian projection to produce a verbalised account of the model's internal reasoning evolution at each generated CoT token. By training a classifier on the extracted features along the traces, we show that these structured features provide insightful perspectives on how and where reasoning diverges toward unfaithfulness. Experiments on four datasets from FaithCoT-Bench and BonaFide show that VERITAS achieves a significant performance gain over LLM-as-Judge, with a 28.4% gain in balanced accuracy, and an average improvement of 16.0% over activation probing. Further analysis shows VERITAS can be generalised to di

---

### [99] Eliciting Specifications: When Does Interactive Clarification Help?

**链接**: https://arxiv.org/abs/2610.22382
**作者**: Mowafak Allaham, Aditya Vempaty, Ashish Jagmohan, Prasenjit Dey, Ravi Kokku
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs can generate Lean specifications from task descriptions, but those descriptions are often underspecified or ambiguous and may omit verifier-relevant edge cases, yielding imperfect formal specifications. We study whether an elicitation agent (EA) can improve verifier-checked Lean specifications by seeking clarification from a reference-grounded simulated developer before formalization. The agent decomposes the task, identifies unresolved decisions, asks bounded clarification questions, and uses the answers to write a refined natural-language specification that an LLM formalizer then translates into Lean. On 189 Verina Lean 4 specification-generation tasks, we compare single-shot generation with elicitation under question budgets of k=3 and k=10, allowing at most three or ten EA questions per task, across same-model and cross-model configurations. The same-model Claude Sonnet 4.6 pipeline has negative strict pass@1 estimates at both budgets, showing elicitation is not a uniform accu

---

### [100] Can LLMs predict the outcomes of machine learning experiments?

**链接**: https://arxiv.org/abs/2610.22599
**作者**: Ayush Bansal, Aldo Pareja, Sean Klein, Serge Didenko, and Artem Lukoianov
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in AI make Recursive Self-Improvement (RSI) increasingly plausible. Large Language Models (LLMs) can already propose, select, and run Machine Learning (ML) experiments. However, the space of possible design choices in ML is vast. An LLM that proposes an experiment needs a reliable intuition of whether it is worth running given the timing constraints of long training runs. In this work, we measure such intuition in current frontier LLMs by evaluating how accurately they predict the impact of self-generated ML experiment ideas before these are put into training runs. To this end, we construct a dataset of 288 LLM-proposed ideas on eight MLE-bench tasks. We then prompt five frontier LLMs (GPT-6 Astra, Claude Opus 5.5, Claude Fable 5.1, Kimi K3, and GLM-5.3) to predict the impact of each idea and compare their predictions with the actual outcomes after training. We report four main findings. First, LLM predictions are substantially better than random chance but far from acc

---

### [101] Ignored, Not Refused: What Low Prompt-Injection Success Rates Hide in Small Tool-Using Agents

**链接**: https://arxiv.org/abs/2610.23254
**作者**: Farhan Zarif, Kazi Shahid Ahmed Galib, Synthia Akter Promi, Shabnam Sharmin Tarin, Ariyan Hossain, Sadif Ahmed 等 (7 人)
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using agents read untrusted external content, which exposes them to indirect prompt injection (IPI), where hidden instructions hijack the agent's tool calls. Benchmarks measure IPI security by the attack success rate (ASR), which treats every failed attack as a successful defense. To test this assumption, we audit 33,000 trajectories from eleven open-weight agents (2-14B parameters) on InjecAgent and AgentDojo. A label-blind LLM judge shows that most failed attacks are ignored (76-80%) rather than refused (17-18%). With identical model weights, changing only the system prompt shifts InjecAgent ASR from 0.2% to 43%. Our Attack-Task Outcome Matrix (ATOM) further shows that in 21.7% of AgentDojo episodes, the agent stayed safe but did not complete the user's task. A low ASR therefore mostly reflects agents silently ignoring injections, not refusing them. Evaluations should report how attacks fail and whether the user's task is completed, alongside ASR. We release the labeled corpus, 

---

### [102] ARBOR: Locating Reasoning Failures in Long Chains of Thought through Reasoning State Tracking

**链接**: https://arxiv.org/abs/2610.22717
**作者**: Huihan Li, Siyuan Wang, Naga Vamsi Ramana Dinavahi, Xiaohui Liu, Xiang Ren
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large reasoning models solve complex problems through long chains of thought, in which prior work has documented failure modes such as overthinking, underthinking, and unsupported deductions. Existing methods detect these failures from local signals: textual similarity to nearby steps, switch tokens, or an LLM's judgment of a step's correctness. However, what a step contributes to the solution depends on the state that earlier steps have established, so identifying failures requires a global view that tracks that state across the trajectory. Therefore, we propose ARBOR, a reasoning-failure attribution framework that represents each trajectory as a tree of reasoning states, built as each step creates, verifies, prunes, or revisits a state, and attributes each failure to a relation between a step and the state preceding it. Using ARBOR, we refine the three failure modes into distinct subtypes that harm reasoning through different mechanisms and at different costs. We find that the tree s

---

### [103] Thought Blocks: Non-Autoregressive Latent Communication for Multi-Agent Systems via Trajectory-to-State Compilation

**链接**: https://arxiv.org/abs/2610.23056
**作者**: Zhenhan Guan, Xiaolong Liu, Hengwei Ye, Zheng Tian
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems typically communicate through text, incurring repeated generation and re-encoding costs. Although latent communication removes explicit verbalization, constructing latent messages may still require autoregressive latent trajectories. We therefore distinguish message representation from message construction and ask whether agents can directly construct useful continuation states without executing the trajectories that normally produce them. We formulate this problem as trajectory-to-state compilation and introduce Thought Blocks, fixed-size blocks of latent key--value (KV) continuation memory constructed in one shot. Thought Blocks achieve a 2.5 times average latency speedup over autoregressive latent communication. Compared with text-based multi-agent communication, Thought Blocks reduce text tokens by 45.7% and autoregressive steps by 84.8%, achieving an 8.6 times average latency speedup. These results demonstrate that trajectory-to-state compilation enab

---

### [104] VISTA: Steering LLMs with Latent User Values Inferred from a Few Survey Answers

**链接**: https://arxiv.org/abs/2610.23702
**作者**: Yinuo Xu, Jadie Adams, Brian Hu, Shivani Kumar, David Jurgens, Arslan Basharat
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalizing a language model requires knowing what a person values, which stays largely consistent across tasks. Yet most methods either learn task-specific preferences or place the user's profile in the prompt, where models struggle to act on it. We introduce VISTA (Value-Informed Steering and Targeted Acquisition), which infers a latent profile from users' (full or partial) survey answers, and maps the profile through a hypernetwork to a user-specific steering intervention in a frozen LLM to select answer choices or generate free-text responses. Given the same evidence, VISTA matches or beats in-context profiles on synthetic preferences (Food2D), the World Values Survey (WVS), and PrimeX, without adding prompt tokens. To reduce the cognitive burden of completing full surveys, VISTA also chooses which questions to ask and when to stop: on WVS it stops after 6% of the questionnaire while retaining 94% of the full-history gain, where standard adaptive testing retains at most 42%. The 

---

### [105] Boundary Detection for High-Dimensional Point Clouds

**链接**: https://arxiv.org/abs/2610.23590
**作者**: Abigail Hickok, Valerio Galanti, Osama Al Dalahmah, Andrew J. Blumberg
**来源**: cs.LG cs.CG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce two new methods for boundary detection in high-dimensional point cloud data, intended to work in situations with non-uniform density, high ambient dimension, and substantial noise. Our first method fits a separating hyperplane on local neighborhoods after doing local dimension reduction---this method works best when one can reliably estimate the intrinsic dimension of the data. Our second method measures the directional uniformity of local neighborhoods, and has the best overall performance on synthetic data. In addition to pointwise numerical boundary scores, our algorithms yield an estimated normal vector at each boundary point. We validate our methodology on synthetic data as well as two real examples: we analyze spatial transcriptomics data, where we show that we can detect the boundary of a tumor, and we also study LLM activation geometry.

---

### [106] Sample, Mix, or Verify? Allocating Test-Time Compute under Imperfect Verifiers

**链接**: https://arxiv.org/abs/2610.23255
**作者**: Srinivasan Iyengar
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A common way to make language models and agents more accurate is to spend more compute at inference time: generate many candidate solutions and submit the one a verifier prefers. Success then requires that some candidate is correct and that the verifier picks it. The first grows predictably with the number of samples; the second does not, because real verifiers (unit tests, majority votes, LLM judges, reward models) accept wrong answers, reject right ones, and make correlated mistakes. With a fixed budget, a practitioner must decide how many samples to draw, which models to draw them from, and how much to spend on verification, and today these choices are made by rules of thumb. We introduce SPLIT, which makes them from a small labelled pilot. It rests on an exact formula for the probability of submitting a correct answer under accept/reject and top-score selection that accounts for varying task difficulty, blind spots shared across models, and correlated repeated verifier calls. SPLIT

---

### [107] How language model agents reshape price competition

**链接**: https://arxiv.org/abs/2610.21711
**作者**: Martin Bichler and Philip Hierhager and Kassian K\"ock and Fabian Pieroth
**来源**: cs.GT cs.LG cs.MA econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeated Bertrand competition is a stringent benchmark for algorithmic pricing: in homogeneous-goods markets, standard learning procedures typically select the stage-game Nash outcome with prices near marginal cost. We show that LLM pricing agents can escape this benchmark, depending on deployment decisions. LLMs outperform standard online learners through faster adaptation, but this advantage largely disappears against full-information learners. An extracted surrogate algorithm illustrates how LLMs in specific deployments profit from regularly undercutting slower learners. Agents that post one price every period from raw market histories that include rival prices can sustain supracompetitive regimes in self-play. Agents that periodically emit probability distributions from summarized histories of their own profits instead move toward the competitive region in self-play. Markets mixing these interfaces can generate dynamic regimes in which LLMs establish a high-price anchor and regular

---

### [108] Language Models Learn to Improve Language Models

**链接**: https://arxiv.org/abs/2610.23344
**作者**: Minhua Lin, Zijun Wang, Zewen Liu, Zhaotian Weng, Bing He, Zhan Shi 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to automate AI research, including language-model (LM) development, offering a potential path toward recursive self-improvement. However, turning experimental feedback into a learned ability to propose effective improvements across models faces two challenges. First, training such an ability with real feedback is expensive: reinforcement learning (RL) requires evaluating tens of thousands of proposals, each potentially requiring a full model-training run. Even at ten GPU-hours per run, reward collection alone would consume hundreds of thousands of GPU-hours, motivating a cheaper surrogate. Second, surrogate feedback can become unreliable as policy optimization favors overestimated proposals when the proposal distribution shifts. To address these challenges, we propose LM2LM, which trains LLMs with RL to generate effective LM improvement proposals. To provide scalable feedback, we use a research world model (RWM), a frozen LLM that pred

---

### [109] Explore Separately, Adopt Selectively: Execution-Guided Tool Use over Large Tool Libraries

**链接**: https://arxiv.org/abs/2610.22688
**作者**: Anna Mazhar, Seiji Maekawa, Nikita Bhutani
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents must discover relevant tools from large libraries, e.g., thousands of tools, as new needs arise during task execution. When several candidates could satisfy the same need, execution may be required to identify the relevant one. Investigating candidates in a shared trajectory can leave alternatives unexplored or allow failed attempts to influence subsequent reasoning. To address this, we present BRIA (BRanch-Inspect-Adopt), a simple yet effective agent that temporarily isolates candidate investigations in separate branches. Each branch retrieves and executes tools to investigate its candidate; a task agent inspects the resulting execution evidence and adopts only useful results into its continuing trajectory. BRIA retrieves additional tools as new capability needs arise during task execution. We evaluate BRIA on PlanBench-XL and MCP-Atlas using a shared pool of 1897 tools, three language models, and static and adaptive retrieval baselines. Across all settings

---

### [110] EduWild: How Teacher-Configured Chatbots Fail in Real-World Use and How to Fix Them

**链接**: https://arxiv.org/abs/2610.23530
**作者**: Ziqi Liu, Ruiwei Xiao, Yuxuan Li, John Stamper
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Teachers increasingly configure educational chatbots through natural-language instructions, but how these bots fail in real-world use remains poorly understood. We introduce EduWild, a dataset of 1,726 conversations with 217 teacher-configured chatbots, each paired with the instructions and configuration behind it, including 900 conversations from the intended end users of 35 deployed chatbots. We develop a 29-code taxonomy covering factual, workflow, diagnostic, and pedagogical failures and apply it using a human-calibrated LLM judge. The most frequent failures are lapses in following teacher intent --- bots skip required workflow steps (53.8% of end-user conversations), omit expectation setup (33.4%), and overload learners with information or questions (37.1%). Guided by these findings, we design a prompt-based harness targeting the six most frequent failure modes. In a study with 200 college students across ten bots, the harness reduces the mean number of target failure codes per co

---

### [111] Beyond the Benchmark: Conditioning, Domains and Failure Modes of Qwen3-TTS

**链接**: https://arxiv.org/abs/2610.23678
**作者**: S\'everin Baroudi, Yanis Labrak, Petr Motlicek, Herv\'e Bredin, Ricard Marxer
**来源**: cs.SD cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Qwen3-TTS reports state-of-the-art zero-shot voice cloning, but its technical report leaves open how the model should be conditioned, how it behaves outside read speech, and how it fails. We characterise its two cloning interfaces, in-context learning (ICL) and X-Vector, against Chatterbox, XTTS-v2 and F5-TTS on read, meeting, emotional and air-traffic-control (ATC) speech, using eighteen objective measures, an LLM judge, a spoofing countermeasure and a listening test. Neither interface dominates: ICL clones timbre more closely from correctly transcribed references, X-Vector clones timing, and ICL degrades sharply when a short reference transcript is wrong. Domain explains four times more variance than system choice. Qwen3-TTS leads on intelligibility and pitch register but trails on prosody, and the objective measures rank systems differently from listeners. An off-the-shelf countermeasure flags its clones no more often than genuine recordings, and on ATC radio it fails for every syst

---

### [112] When Can You Trust an Agent's Own Verifier? Stress-Testing Counterfactual Rationale Verification Under Search Pressure and Oracle Access

**链接**: https://arxiv.org/abs/2610.22779
**作者**: Jonghyun Lee, Moonsu Kim, Sunghwan Park
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated agent design increasingly trusts a single score to decide whether a change is an improvement -- but a score optimized aggressively enough ceases to measure what it was meant to. When an agent also explains its design, that explanation is a second signal we can check without human labels: negate each stated claim, re-run, and observe whether performance drops. We ask whether such a verifier stays reliable once an agent optimizes against it. Our contribution is not a new verifier but a way to stress-test one: a pressure ratio $\rho$ measuring how much the verifier steers the agent's search, and four falsifiable probes covering four failure modes -- giving no signal, being too weak to matter, being gamed by stating fewer claims, and being queried before the agent commits. We apply the test to our own verifier, the Rationale Consistency Score (RCS), inside an LLM agent that designs machine-learning pipelines, with one generator model, six tasks, and three seeds. First, in our pri

---

### [113] The Model Knows Better: Defending Medical Multi-Agent Systems Against Prompt Injection

**链接**: https://arxiv.org/abs/2610.22594
**作者**: Fardin Ahsan Sakib, Ziwei Zhu, Ozlem Uzuner
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical multi-agent systems, in which LLM agents discuss a case, are increasingly studied for clinical decision support. Prompt injection, text that an attacker adds to a model's input, can manipulate LLMs into wrong decisions. How it affects these systems, and how to protect them, remains unclear. Across two systems, two model families and three benchmarks, a single injected passage succeeds in up to 61% of cases, and collaboration does not consistently protect against it. Existing defenses help only partly: they miss injections that look like ordinary clinical text. Yet when asked to check the injected text against the patient's findings, a model that followed the injection usually rejects it. We therefore propose a training-free defense that verifies the clinical judgments behind the system's decision. Following clinical practice, it separates the patient's findings from clinical judgments, such as diagnoses, recommendations and instructions, and checks each judgment against the fin

---

### [114] MultiAgent-OPD: End-to-End Training of Hierarchical Multi-Agent Systems with On-Policy Distillation

**链接**: https://arxiv.org/abs/2610.23234
**作者**: Yuhan Sun, Jiaxin Zhao, Yongdong Luo, Yibo Hu, Meiguang Jin, Junfeng Ma 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In a hierarchical multi-agent system, a Leader assigns tasks and subagents carry them out. Jointly training the Leader and the subagents is difficult because a final answer gives only indirect feedback to the subagents. An LLM judge can score the performance of the subagents, but these scores depend on the judge's own assessment of the quality of subagents' responses. We present MultiAgent-OPD, which combines on-policy distillation with reinforcement learning to jointly train a shared-parameter Leader-Searcher-Answerer team end to end. We first train a Teacher in a Searcher-Answerer workflow using answer correctness. During team training, the frozen Teacher scores student-generated search and summary tokens to provide local process supervision for the Searchers, while the Leader learns from team success and the Answerer from candidate correctness. Across seven datasets, the trained system reaches 38.68% macro avg@4, exceeding Prompted Critic by 4.06 percentage points and C-MAS + RL, th

---

### [115] NoveltyScope: A Multi-Agent Research Assistant for Evidence-Grounded Novelty Assessment of Scientific Papers

**链接**: https://arxiv.org/abs/2610.22703
**作者**: Yueran Tian, Huizhi Liang
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> NoveltyScope is a prototype that compares a scientific paper with retrieved prior work and produces a structured report and a five-level novelty score. The system extracts the core task and at most two author-claimed contributions, then searches a closed local corpus using BM25 and dense retrieval with reciprocal rank fusion. Contribution comparisons request paired passages for potential refutations, and quotations are checked against cached source text. Four scoring roles (Prosecutor, Defender, Judge, and Critic) use the resulting evidence, with at most one revision of the Judge's score. Evaluation uses 50 class-balanced RINoBench samples whose idea-level labels are retained for full-paper input. Mean absolute error is 1.48 and 1.26 for single-LLM and multi-agent scoring with Gemini, respectively, and 1.22 and 1.16 with Qwen3. The vector-similarity baseline has an error of 1.68. A HiCLIP case study illustrates the contribution comparisons and paired evidence passages. Overall, the res

---

### [116] RL-Guided Temporal Localization for Dual-Channel Retrieval in Long-Horizon Agent Memory

**链接**: https://arxiv.org/abs/2610.23598
**作者**: Dabin Sheng, Zhe Wu, Jinming Zhao, Junliang Xing, Yuanchun Shi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-aware retrieval is crucial for long-horizon LLM agents to effectively leverage ever-growing long-term memory. Existing methods focus on lexical or semantic similarity, leading to target memories being crowded out by temporally mismatched yet semantically similar candidates. Even time-aware approaches inject temporal cues only during memory organization or answer generation, overlooking temporal constraints at the retrieval stage, where candidate selection occurs - the root cause of the displacement. Inspired by the temporal contiguity effect in human episodic memory, we propose TIDER (Temporal Interval-driven Dual-channel Evidence Retrieval), a time-aware agentic retrieval framework. Central to TIDER is a reinforcement learning (RL)-trained temporal interval locator that infers the temporal windows in which the evidence lies. RL optimizes window localization as a discrete, non-differentiable retrieval decision, using composite rewards to convert sparse answer supervision into fine

---

### [117] LEMON: Equivariant Learning over Attention Maps for Zero-Shot Misbehavior Monitoring on New LLMs

**链接**: https://arxiv.org/abs/2610.22723
**作者**: Guy Bar-Shalom, Mor Geva, Fabrizio Frasca, Haggai Maron
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models exhibit misbehaviors that hinder deployment in high-stakes settings. One approach to monitor such failures is to use an external LLM as a monitor, but this is prohibitively expensive. A well-known and efficient class of monitors can detect such failures from internal representations (such as activation probes), but are tied to the model they were trained on, requiring costly re-annotation as new LLMs appear. A natural way to avoid this repeated annotation cost is to develop internal-representation based monitors that transfer zero-shot across LLMs. However, such transfer is challenging because internal representations are not naturally aligned across models; in particular, attention maps, known to contain signals of misbehavior, may differ in head function, ordering, and model depth. In this work, we characterize those cross-model attention mismatches as algebraic symmetries and use geometric deep learning principles to build LEMON (Language-model Equivariant MOni

---

### [118] Aligning Language Models Towards Counterfactual Invariance

**链接**: https://arxiv.org/abs/2610.22942
**作者**: Basar Demir, Emily Shen, Ksheeraj Sai Vepuri, Sourabh Kulkarni, Harihar Subramanyam, Ankit Jain 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small variations in prompt characteristics can meaningfully alter the semantics, tone, and contextual assumptions of large language model outputs. Such characteristics can involve group variables such as demographics or other sensitive latent attributes. Sensitivity to such input variables is undesirable when demographic information is causally irrelevant to the task, but might still be relevant for generation of semantically coherent responses. This makes the task of enforcing counterfactual invariance while preserving model utility difficult. To study this problem, we first show that standard model alignment recipes (such as reinforcement learning) increase differences in response quality across demographics, while improving overall response quality, ultimately amplifying what is known as counterfactual bias. To address this, we develop a policy gradient technique involving a group-level reward function that operates on matched pairs of counterfactual prompts. For completeness, we bu

---

### [119] Steering beyond Language: Improving Multilingual Training-Free Text Embeddings via Paired-Residual Subspace Removal

**链接**: https://arxiv.org/abs/2610.23807
**作者**: Ailiang Lin, Zhuoyun Li, Yusong Wang, Keyu Mao, Kotaro Funakoshi, Manabu Okumura
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While deriving text embeddings directly from frozen LLMs has emerged as a promising direction, existing methods focus almost exclusively on English, leaving multilingual settings largely unexplored. In this work, we present the first systematic study of multilingual training-free text embeddings in LLMs. Our analysis reveals a language-conditioned embedding geometry in which semantically equivalent sentences remain misaligned across languages. We hypothesize that language-specific variation can be disentangled from semantic content to improve embedding quality. To this end, we propose Paired-Residual Subspace Removal (PRSR), a training-free inference-time intervention that steers LLM representations toward a more language-invariant semantic space. PRSR first constructs paired residuals from multilingual parallel sentences to capture language-specific deviations. It then estimates layer-wise low-rank subspaces from these residuals and suppresses the corresponding components in the last-

---

### [120] The Ethics of Prompt Engineering

**链接**: https://arxiv.org/abs/2610.23082
**作者**: Federico Germani, Giovanni Spitale
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt engineering is commonly understood as a technical practice aimed at eliciting useful, accurate, and appropriately structured outputs from large language models (LLMs). Yet prompts do more than optimize model performance: they shape what information is elicited, which assumptions are introduced, and which perspectives are privileged. In this paper, we argue that prompting should therefore be understood as an epistemic and normative act. We distinguish between two conceptions of prompting: knowledge generation, in which the model is implicitly treated as an epistemic authority, and knowledge injection, in which users provide relevant knowledge, evidence, and context that the model can organize, articulate, and extend. We contend that the latter provides a more appropriate model for responsible LLM use, since prompting cannot substitute for subject-matter expertise or the critical evaluation of model outputs. At the same time, prompts inevitably inject values, intentions, and assum

---

### [121] Generative Policy Improvement from Observational Data

**链接**: https://arxiv.org/abs/2610.23436
**作者**: Jonas Schweisthal, Dennis Frauen, Stefan Feuerriegel, Emma Brunskill
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how to improve decision policies from observational data to generate better actions when actions are complex, structured objects, such as text messages or images. This task is subject to two major challenges: (i) action-level overlap is often too weak for reliable off-policy evaluation and improvement, and (ii) generating new structured actions often requires expensive training or fine-tuning (e.g., of an LLM) and can be ill-defined due to information loss in action representations. To address both, we propose PolicyLift, a three-stage framework for generative policy improvement with structured actions from observational data. In Stage 1, PolicyLift learns a small set of discrete action codes that capture high-level strategies in the observed action space and are tailored to support policy improvement under limited overlap. In Stage 2, it learns a context-dependent policy over these action codes. At deployment time, Stage 3 "lifts" the learned code-level policy back to the ori

---

### [122] MS-Eval: Benchmarking Sub-Agent Delegation and Orchestration in MCP-Intensive Working Scenarios

**链接**: https://arxiv.org/abs/2610.22869
**作者**: Bowen Ding, Qixin Wang, Lexing Ruan, Weiyi Lu, Qiwei Ge, Ruishan Fang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly integrated into real-world works, yet they must handle diverse domain-specific tools and complex multi-sub-task problems that sequential tool invocation resolves inefficiently and with severe context bloat. The Main-Agent Delegation and Sub-Agent Execution (MAD-SAE) paradigm addresses these issues by delegating sub-tasks to specialized sub-agents for parallel execution in isolated contexts, but its delegation and orchestration quality remains unquantified. We introduce MS-Eval, a unified evaluation kit comprising an MCP-intensive benchmark, a controlled execution harness, tailored delegation and orchestration metrics, and the MSQ index for comprehensive assessment. Evaluating four MAD-SAE variants and eight frontier models reveals that (1) sub-agent specialization (Spec) is the best practical practice; (2) open-source models are largely competitive with few exceptions; and (3) MAD-SAE generally raises cost with contingent payoff, benefiting most open-source 

---

### [123] Annotrace: A Workbench for Step-Level Annotation of Agent Traces

**链接**: https://arxiv.org/abs/2610.23284
**作者**: Arun Josephraj Arokiaraj, Chenyi Huang, Sahan Bulathwela, Zekun Wu, Bin Wu
**来源**: cs.AI cs.CL cs.HC cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Every study of why LLM agents fail begins by labelling traces by hand, and every such study builds its own throwaway tool. Observability platforms record agent traces but offer no structured labelling; annotation tools label text but have no notion of a step, a delegation or a tool call, leaving it unclear what the smallest unit of execution to label should be. Annotrace reads six trace formats, including OpenTelemetry GenAI, LangSmith and Langfuse, and turns each run into an ordered, nested list of steps. The annotator writes their own labelling codebook; a frontier model proposes a starting set from a sample of their own traces, answers first, and is asked exactly the questions the human is asked, making annotation a joint human-AI process. Annotrace measures agreement between any two annotators, human or AI. On a multi-agent question-answering corpus it reproduces a previous manual effort's 235 annotation units exactly, and two models labelling the same traces agree 91% of the time 

---

### [124] NL2SQL with Iterative Self-Refinement

**链接**: https://arxiv.org/abs/2610.22968
**作者**: Anjali Vemula, Akshat Dasula
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bridging the gap between human intent and machine logic remains a critical challenge in data access for non-technical users, yet Large Language Models (LLMs) remain unreliable: they hallucinate schema elements, generate syntactically invalid queries, or fail to capture user intent. These limitations are especially critical in domains such as insurance, where KPIs, regulatory constraints, and legacy relational systems demand high precision. We introduce a multi-agent, persona-driven NL2SQL framework that combines (1) domain relevance detection, (2) schema-grounded knowledge construction, (3) KPI-aware SQL synthesis, (4) syntax-level self-repair using sqlite execution feedback, and (5) semantic consistency checking via SQL-to-NL reverse engineering. Our system significantly reduces query hallucination and improves semantic fidelity compared to direct LLM prompting. Evaluated on 60 queries (50 from a HuggingFace text-to-SQL dataset and 10 custom domain queries), the system achieves 90% co

---

### [125] Refusal Is Not Robustness: Measuring Harmful Reachability in Autoregressive Language Models

**链接**: https://arxiv.org/abs/2610.22754
**作者**: Parv Kapoor and Teresa Fortes and Claudia Mamede and Rui Abreu and Jonathan Aldrich and Eunsuk Kang
**来源**: cs.LG cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM safety evaluations via jailbreaking typically index on attack success rate (ASR): whether a generated response violates safeguards. However, ASR only evaluates sampled outputs and provides little information on the underlying generation process. Autoregressive language models define distributions over possible outputs, and a sampled refusal can coexist with substantial probability mass on harmful generation paths. We study this hidden structure through bounded continuation analysis (BCA), which models autoregressive generation as a stochastic process over token prefixes and computes the finite-horizon probability that generation reaches a harmful continuation. BCA constructs a bounded continuation tree, labels terminal continuations with a semantic harm evaluator, and estimates harmful reachability using exact probabilistic model checking. BCA complements ASR by measuring how much harmful behavior remains accessible beneath a sampled safe response. This makes it useful for distingu

---

### [126] Multiple Turns, Short Horizons: Measuring Effective-Horizon Compression in Jailbreaks

**链接**: https://arxiv.org/abs/2610.22928
**作者**: Zhipeng Wei, Michael Lee, N. Benjamin Erichson
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn jailbreaks use feedback from a victim large language model to adapt their queries over several turns. However, once an effective trajectory has been found, it is unclear how much of the earlier query history is still needed. In this work, we study this by removing early attacker queries and running the remaining queries again in a new conversation while regenerating the victim's responses. We define the effective horizon as the shortest remaining query sequence that recovers the same attack progress. Empirically, we find that roughly half of the original query sequence is sufficient on average to recover the same attack progress. We call this phenomenon effective-horizon compression. We show that this shorter history can recover the best point reached during an unsuccessful attack and provide a better starting point for continuing the attack. It also helps identify which earlier queries should receive less learning signal during attacker training, and downweighting those que

---

### [127] AI-Driven Reproducibility and Analytical Robustness in Scientific Discovery

**链接**: https://arxiv.org/abs/2610.23845
**作者**: Shicheng Liu, Krista Opsahl-Ong, Andrew Drozdov, Julian Killingback, Arnav Singhvi, Ronak Pradeep 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reproducible and analytically robust research findings are essential to scientific progress, but evaluating these properties typically requires costly manual effort. We investigate whether LLM agents can help automate reproduction and robustness analysis, using a medical case study grounded in the Surveillance, Epidemiology, and End Results (SEER) database, a widely used U.S. cancer registry underlying tens of thousands of published studies. First, we introduce SEER-Repro, a benchmark of 20 published SEER-based papers together with the data and resources required to reproduce their findings. Second, we create an AI agent that successfully reproduces 77.4% of 2,190 atomic claims, while providing executable baselines for further analysis. Third, we develop an agentic analysis pipeline to test the robustness of the medical findings by identifying analytical choices underlying each finding, proposing defensible alternatives, and rerunning the analysis to determine whether those choices aff

---

### [128] Graph Serializations for Reasoning LLMs: A Study Across Knowledge Extraction and Structural Reasoning

**链接**: https://arxiv.org/abs/2610.22734
**作者**: Julien Yu, Mihaela Bornea, Avirup Sil, Katrin Kirchhoff
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The way a knowledge graph is serialized as text for inclusion into LLM context can substantially affect downstream LLM performance, with prior work reporting tens of percentage points variations across formats. However, existing studies consider only a limited set of representations and predate frontier reasoning models, which now offer stronger reasoning, instruction-following, and long-context capabilities. We evaluate 15 graph representation formats across nine frontier LLM configurations on ontology-based knowledge extraction and structural graph reasoning tasks. While knowledge extraction is relatively insensitive to different serialization formats, the choice of the optimal format for structural reasoning tasks significantly affects accuracy. We demonstrate that the optimal representation choice depends on model, query, and task and propose to approach graph serialization as a dynamic orchestration decision.

---

### [129] JAVIS: Joint Audio-Visual Interaction and Streaming for Real-Time Conversational Agents

**链接**: https://arxiv.org/abs/2610.22499
**作者**: Junseok Ahn, Jaehyun Park, Jeongsoo Choi, Joon Son Chung, Ji-Hoon Kim
**来源**: cs.CV eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human communication is inherently multimodal, conveying intent not only through linguistic and vocal cues but also through visual signals. However, existing conversational systems have mainly focused on text or speech, leaving out the visual feedback that is essential for natural interaction. In this paper, we propose JAVIS, an end-to-end streaming framework for real-time audio-visual conversational agents. Our key idea is to let the voice and the face speak from a single representation. On top of a shared LLM, a Joint Refined Head produces a unified audio-visual representation, which is fed into dedicated streaming branches for speech and face generation. This end-to-end design avoids intermediate bottlenecks, enabling real-time generation while keeping speech and face tightly synchronized. In addition, we present JAVIS-Syn, a 334-hour synthetic corpus designed to address the lack of expressive audio-visual dialogue data, covering emotionally rich multi-turn conversations and assistan

---

### [130] Brain-Aligned Multimodal LLMs for Social and Emotional Understanding of Cartoon Movies

**链接**: https://arxiv.org/abs/2610.22706
**作者**: Yiran Huang, Zeyong Zhang, Bharat Biswal, Xin Di, Mengjia Xu
**来源**: cs.AI q-bio.NC
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) offer scalable annotations of social and affective content, but their temporal agreement with human judgments and neural predictive value require further evaluation. We compared diffusion-based and autoregressive MLLMs with continuous human Theory of Mind (ToM) and affective valence ratings across three short cartoon movies. Behavioral analyses assessed temporally aligned Pearson correlations, rating distributions, and the effects of preceding scene descriptions. Ratings from each source were separately used in subject-specific regression models to predict regional fMRI responses. Model ratings captured aspects of human temporal variation despite systematic distributional differences, with generally stronger alignment for valence than ToM. Preceding context improved alignment in some conditions, depending on the model and movie. In \emph{The Present}, more regions showed significant encoding for MLLM ratings than for human ratings, whereas effec

---

### [131] From GAN-Based Models to GPT-5: A Taxonomy-Guided Study of Human Performance in Detecting Deepfake Face Images

**链接**: https://arxiv.org/abs/2610.23144
**作者**: Zhiqing Guo, Lixin Jia, Luning Sun, Xiaowei Chen, Guofeng Yu, Liejun Wang 等 (10 人)
**来源**: cs.CV cs.CR cs.HC
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative models for deepfakes have rapidly evolved from GAN-based architectures to diffusion models and multimodal large language models (MLLMs). However, empirical research on human performance in detecting deepfake face images has not kept pace. It remains unclear if (and how) detection performance varies across generative models and whether model-specific training improves detection more effectively than general-purpose training. In this paper, we propose the \emph{Deepfake Face Artifact Taxonomy} (DFAT), a cross-model taxonomy of human-recognizable visual artifacts in deepfake face images, based on which we build both general-purpose and model-specific training materials. Through an online experiment ($n = 524$), we examined human performance in detecting deepfake face images and evaluated training efficacy across five representative generative models: three GAN-based, one diffusion-based, and one MLLM (GPT-5). Our results show that participants' detection accuracy was strongly m

---

### [132] Xiaomi-Lens-0 Technical Report

**链接**: https://arxiv.org/abs/2610.23279
**作者**: Pei Fu, Yike Liu, Yue Sun, Hanmo Wang, Xiuwen Xi, Ruoceng Zhang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) answer questions about whole images well, yet they still struggle with fine-grained region understanding. A key reason is that text-only supervision never specifies which regions support an answer. To close this gap, we present Xiaomi-Lens-0, a 4B MLLM built on Qwen3.5 that predicts masks from its own visual representations. Specifically, a lightweight decoder combines vision-encoder patch features with visual latents, the language model's mask-token states, so mask supervision reaches the shared backbone without an additional segmentation encoder. Because each latent decodes to a mask, the model can interleave reasoning with region-specific latents and thus think with visual latents, while grounded reasoning traces supervise the regions it visits during chain-of-thought. As a result, across all eight RefCOCO, RefCOCO+, and RefCOCOg splits, Xiaomi-Lens-0 gains 5.6 points on average over Qwen3.5 in referring comprehension and achieves the highest

---

### [133] A Plausible Explanation Is Enough to Mislead Multimodal Judges

**链接**: https://arxiv.org/abs/2610.22631
**作者**: Anglin Cai, Zhiqi Wang, Xiaozhi Yang, Yurun Lin, Dongwon Lee, Yuchen Yang
**来源**: cs.CL cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) increasingly serve as judges in training and evaluation pipelines, often assessing answers together with explanations. Although AI judges are sensitive to textual factors, it remains unclear whether ordinary plausible explanations can sway judgments requiring visual verification. We introduce JUPE, a visual-question-answering (VQA)-style benchmark that fixes answers while varying explanations. Across 14 MLLM judges, ordinary explanations that sound plausible mislead judges, with effects comparable on average to deliberately persuasive arguments. Plain justifications and chain-of-thought rationales reduce rejection of incorrect answers by 12.7 and 13.8 percentage points, respectively. We call this failure plausibility capture. Using signal detection theory, we find a significant mean shift in decision criterion toward acceptance, without a clear change in mean discriminability. Explanations sway judgments across domains, explanation generators, a

---

### [134] OmniXRef: A Unified Framework for Multimodal Multi-Reference Video Editing

**链接**: https://arxiv.org/abs/2610.22744
**作者**: Xiaoyan Cong, Tianyu Wang, Hyeonho Jeong, Zhifei Zhang, Yuqian Zhou, Yijun Li 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Creative intent in video editing can be expressed through text instructions (e.g., "remove the people"), image references (e.g., subject appearance), video references (e.g., camera movement), or a combination of the above. We introduce OmniXRef, a unified framework for multimodal multi-reference video editing that allows users to combine variable numbers of text, image, and video references to control diverse attributes of a source video. We first devise a unified input design with a reference-bank interface and introduce $R^2$-RoPE to support generalization to more references. Then our model, OmniXRef-Model, uses a single-stream diffusion transformer to jointly process the source video and multimodal context from an MLLM in an interleaved sequence. To address the scarcity of training data for video-reference editing, we construct OmniXRef-Data using synthesis pipelines for different editing tasks and combinations of references. We use curriculum learning to progressively increase task

---

### [135] TriRouter: Sparse-to-Dense Electrode-Space Routing for Robust EEG Motor Imagery Decoding

**链接**: https://arxiv.org/abs/2610.23665
**作者**: Ying Zhou, Yaoxin, Mengting Liu
**来源**: cs.LG eess.SP
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motor imagery brain-computer interfaces require reliable decoding from multichannel EEG, but practical acquisition often yields sparse or corrupted electrode montages. We propose TriRouter, an electrode-space routing framework with discriminative-preservation, mask-robustness, and latent-compensation paths. A validation-calibrated router uses observable channel availability to allocate path contributions, preserving complete-channel discrimination while increasing representation recovery under severe missingness. In BNCI2014-001, TriRouter outperforms standard public backbones and a dynamic-spatial-filtering corrupted-EEG baseline. It improves accuracy over the strongest corrupted-EEG baseline by 3.68, 4.02, and 6.46 percentage points at nominal 25%, 50%, and 75% missing settings, and remains effective under structured regional missingness and additional low-channel dataset evaluation.

---

### [136] Seeing Seizures: A Large-Scale Empirical Study of Video and EEG Deep Learning for Automated Rodent Seizure Detection and Severity Grading

**链接**: https://arxiv.org/abs/2610.22566
**作者**: Alloy Das, Shreyan Ganguly, Nyzil Massey, Hung Phi Doan, Zhanhong Jiang, Thimmasettappa Thippeswamy 等 (7 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Manual annotation of synchronized video and EEG recordings is a bottleneck in preclinical seizure research. We present an empirical study of seizure detection and behavioral severity grading using 24,131 paired clips from 601 sessions across 20 rats in a soman-induced epilepsy model. Ten video architectures and seven single-channel EEG models are evaluated independently on binary detection and three- and five-class severity tasks. In the session-exclusive reference comparison, R(2+1)D-18 and GRU achieve detection macro-F1 scores of 0.968 and 0.974, respectively; for five-class grading, the corresponding scores are 0.657 and 0.560. Subject-exclusive evaluation reduces five-class macro-F1 to 0.475 for video and 0.404 for EEG, highlighting the difficulty of grading unseen animals. Temporal-sampling experiments demonstrate the value of multiple frames, while detection performance varies relatively little across the evaluated video architectures. A separate video-only binary-detection evalu

---

### [137] Inter- and Intra-Subject Variability in EEG: A Systematic Survey

**链接**: https://arxiv.org/abs/2602.01019
**作者**: Xuan-The Tran, Thien-Nhan Vo, Son-Tung Vu, Thoa-Thi Tran, Manh-Dat Nguyen, Thomas Do 等 (7 人)
**来源**: q-bio.NC cs.AI cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [138] GRAFT-EEG: Gauge-Aware Physical Field Transport for Cross-Dataset Motor-Imagery EEG

**链接**: https://arxiv.org/abs/2610.23620
**作者**: Ying Zhou, Mengting Liu
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-dataset EEG decoding often treats montage, reference, and active-sensor changes as representation shift, although they also alter the observation operator. We study target-statistics-blind transfer: fitting receives no target signal, label, or empirical statistic, and electrode coordinates only instantiate a fixed prediction operator. method removes the active-set common-reference gauge and transports each native mask through a template motor leadfield. A source-fitted spectral classifier anchors the decision; a bounded state-space-model (SSM) residual is secondary. We establish restricted identifiability and an operator-perturbation bound. Across five leave-one-dataset-out targets (253 participants), dynamic method achieved 60.865% equal-target balanced accuracy versus 52.684% for strict-clean 5/5 BIOT (hierarchical difference +8.182 points; 95% CI +6.382 to +10.196; positive in every target). On four EEGPT-clean targets, the descriptive means were 61.520% and 59.057%. In four p

---

### [139] Do Speech BCIs Need Larger Models? Rethinking Neural Decoding beyond Scaling

**链接**: https://arxiv.org/abs/2610.23175
**作者**: Zehui Feng, Weichuan Wang, Xiaohan Chen, Cuntai Guan, Ting Han
**来源**: cs.CL
**匹配关键词**: BCI
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent speech brain-computer interfaces (BCIs) increasingly rely on large models and complex multi-stage pipelines for neural decoding. However, in speech BCI, where training data are scarce, noisy, and expensive to collect, the benefits of model scaling remain unclear. This work revisits a fundamental question: are large models truly necessary for accurate neural decoding? We propose BEST (Brain-Encoding-Speech-Text), a two-stage framework for efficient neural-to-text decoding. Instead of relying on large generative models or phoneme-centric pipelines, BEST introduces hierarchical intermediate representations and a compact speech-oriented decoder that directly maps neural activity to text. This design preserves essential structure while significantly reducing computational cost, enabling robust generalization in low-resource settings and practical deployment under constrained resources. On the Brain-to-Text '24 and '25 benchmarks, BEST achieves word error rates (WERs) of 6.19% and 1.6

---

### [140] Beyond Success Rate: Interventional Evaluation of Memory in Vision-Language-Action Systems

**链接**: https://arxiv.org/abs/2610.23372
**作者**: Keyuan Luo, Yi Xie, Wanyun Ling, Yuanzhe Li, Ziyue Li, Zhuoqi Zeng
**来源**: cs.RO cs.LG
**匹配关键词**: Motor Execution
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When we say that a robot uses memory, does that memory actually play a role? Success-rate ablations alone cannot establish the use of task-relevant facts: they change information and computation together, while aggregate rates can hide offsetting gains and losses. We propose an Interventional Memory Evaluation Protocol (IMEP) for vision-language-action (VLA) systems to address four questions: (1) Does memory provide a net benefit? (2) Under what conditions does memory help? (3) Do changes to memory alter task outcomes? (4) Are these effects specific to task-relevant facts? At the retrieval interface, we compare target-fact substitutions with fact-preserving replacements, minimal numerical perturbations, and exact replicas, while assessing decision correctness separately from motor execution success. We evaluate within-episode, cross-episode, and agentic memory. In cross-episode learned-bank experiments, a one-unit-in-the-last-place (ULP) intervention, including its installation procedu

---

### [141] Towards Reconstructing Geographically Diverse Architecture with 3D Foundation Models

**链接**: https://arxiv.org/abs/2610.22514
**作者**: Nicky Kriplani and Yiwen Zhang and Angelina Wang and Hadar Averbuch-Elor
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Internet-scale photo collections of real-world landmarks have driven progress in 3D computer vision yet remain highly challenging for modern 3D foundation models (3DFMs) that estimate scene structure in a single feed-forward pass. In this work, we introduce ArchWorld, a benchmark of 3D architectural landmarks with high geographic coverage and rich metadata. We use this benchmark to conduct a thorough error analysis of current 3DFMs to understand where they fall short and how they can be improved. We examine socially relevant disparities in model error and find that model performance varies by geographic region; however, unlike typical fairness regimes, the trends only partially match training data representation. Our investigation reveals that the observed geographic disparities reflect not only differences in data representation and scene size but also differences in region-specific architectural features and background distractors that make scenes from different regions inherently va

---

### [142] Unifying Embodied Foundation Models via a Model-to-Policy Formulation

**链接**: https://arxiv.org/abs/2610.23053
**作者**: Xinyi Hong, Mingyang Ren
**来源**: cs.RO cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language-action (VLA) models and world-action models (WAMs) have emerged as promising approaches to robot learning and control. These models integrate multimodal perception and action generation, but differ in their architectures, output representations, and learning objectives. In this paper, we present a unified, architecture-agnostic probabilistic formulation for embodied foundation models based on stochastic kernels. Our formulation has two key components: (i) we characterize embodied foundation models through conditional output distributions and action-realization kernels, which together induce task-conditioned robot policies; and (ii) we connect pretraining and post-training to policy deployment, accommodating model-specific pretraining objectives and offline or online post-training strategies. We instantiate the formulation for OpenVLA and DreamZero, covering autoregressive action-token prediction and joint video-action generation.

---

### [143] Scalable Adaptation of 3D Geometric Foundation Models via Weak Supervision from Internet Video

**链接**: https://arxiv.org/abs/2602.07891
**作者**: Zihui Gao, Ke Liu, Donny Y. Chen, Duochao Shi, Guosheng Lin, Jia-Wang Bian 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [144] Unit-level aggregation breaks coverage in causal foundation models

**链接**: https://arxiv.org/abs/2610.22770
**作者**: Gabe Schulman, Lucius E. J. Bynum, Yoav Wald
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal foundation models (CFMs) show promising results for treatment-effect estimation, with unit-level estimates that are competitive on standard benchmarks. Many causal analyses, however, inform decisions through effects averaged over groups of units, such as the full sample, the treated units, or a subgroup, and for such decisions a CFM is useful only if its credible intervals are calibrated. We examine these intervals and find that their coverage degrades, both in simple synthetic settings and on standard benchmarks. On ACIC 2016, for example, temperature-calibrated 95% intervals from CausalPFN fall below nominal coverage beyond groups of 30 out of 4802 units, and intervals for the full-sample average contain the true value in only 20% of datasets. We trace this problem to how these models are trained and how their intervals are formed. They output a predictive distribution for one unit at a time and, at inference time, combine the unit-level variances as if the errors on different

---

### [145] DeDiCa: A Scalable Deconfounding Discrete Causal Generative Model

**链接**: https://arxiv.org/abs/2610.23272
**作者**: Kunchangtai Liang, Adri\'an Javaloy, Antonio Vergari, Isabel Valera
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce DeDiCa, a practical framework for efficient causal inference with discrete variables and hidden confounding that revisits classical probabilistic modeling through a tensorized parameterization of causal Bayesian networks, enabling tractable inference. Given a causal graph, DeDiCa is trained once on observational data by maximum likelihood, exactly marginalizing over hidden confounders, and can then estimate any (proxy-)identifiable interventional query. Despite this deliberately simple parameterization, DeDiCa matches state-of-the-art neural causal generative models in ATE estimation, while supporting memory-efficient CPU training and exact interventional inference in milliseconds. Compared with causal foundation models, DeDiCa scales more effectively with additional observational samples and achieves competitive accuracy at substantially lower inference time and memory. DeDiCa provides a tractable, accurate, and scalable approach to causal inference in discrete settings w

---

### [146] Diversity Without Labels: Task-Agnostic Coreset Selection Across Perception and Action

**链接**: https://arxiv.org/abs/2610.23642
**作者**: Julia Hindel, Benjamin Ramtoula, Kyuhwan Yeon, Nick Heppert, Paul Newman, Daniele De Martini 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While data collection for model training is relatively easy, curating high-quality datasets from large collections is inherently challenging. Coreset estimation methods address this problem by identifying the best data subsets to train models on. However, existing approaches often require proxy model training, extensive annotations, or task-specific tailoring. Unsupervised alternatives typically exploit geometric properties in foundation model feature spaces, but are limited to pairwise image-to-image comparisons or comparisons against a fixed subset. We introduce CoreDNA, an unsupervised, task-agnostic coreset estimation approach that pools neuron activations from vision foundation models into per-image and per-dataset distributions. By comparing each image's distribution to the dataset-level distribution, CoreDNA can capture both low-level visual structure and high-level semantic information across layers. We find that high-quality samples concentrate in the tails of the last layer's

---

### [147] QD-Rec: Open-Ended Evolution of Recommendations via Quality-Diversity

**链接**: https://arxiv.org/abs/2610.23470
**作者**: Takashi Ishida, Taro Makino, Issa Sugiura
**来源**: cs.IR cs.AI cs.LG cs.NE
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-ended search combined with foundation models has produced advances such as faster algorithms, new results on open mathematical problems, and self-improving agents. We extend this paradigm to recommendation for decision-making, focusing on decisions where the set of possible choices is fixed but the reasons for choosing them are not. In high-stakes decisions, e.g., which company to acquire or which customer to target, comparing diverse, well-reasoned options can be more useful than a single ranked list. We formalize open-ended recommendation as building a diverse, high-quality set of recommendations, each an item together with a hypothesis, a natural-language reason why the item fits the needs of a decision maker. We propose QD-Rec, a quality--diversity method that selects items with a contextual bandit and generates hypotheses with a foundation model from earlier ones kept in an archive as stepping stones. A new recommendation enters the archive if it is novel or better than its n

---

### [148] Adaptation of Computer Use Agents to New Software with User Manuals

**链接**: https://arxiv.org/abs/2610.23012
**作者**: Chulhoon Yoon, Kyungri Park, Jinyeong Yun, Daeyun Jeong, Sukmin Yun, Woohwan Jung
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models have significantly improved the ability to operate real-world software through graphical user interfaces (GUIs) using visual observations and natural language instructions. However, maintaining strong performance on unseen applications remains challenging, as practical tasks often require long-horizon procedural knowledge and application-specific operation patterns. In addition, constructing executable tasks and collecting corresponding trajectories for training still heavily rely on human-annotated data, incurring substantial cost. In this paper, we propose MAGE (Manual-augmented computer use AGent Execution and learning), a framework that leverages user manuals as a scalable source of procedural knowledge to improve both inference and training. During execution, MAGE retrieves task-relevant manual content and uses a planner to generate explicit procedural guidance for CUAs. To further account for the discrepancies between manuals and ac

---

### [149] Input- and Feature-Space Correction for Cross-Hospital IHC Grading

**链接**: https://arxiv.org/abs/2610.22756
**作者**: Jongwoon Lee, Jhair Gallardo, Christopher Kanan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models (FMs) are trained predominantly on hematoxylin and eosin (H&E) images but are increasingly used as frozen feature extractors for immunohistochemistry (IHC), where cross-hospital differences can impair grading. However, systematic comparisons of correction methods for cross-hospital IHC grading remain limited. To address this gap, we benchmark label-free transformations applied to input images before frozen-FM encoding and to features after frozen-FM encoding using UNI and Virchow2, three IHC markers, and six directed cross-hospital transfers, yielding 12 settings. Among the evaluated input-space methods, our proposed method FIX achieved the largest macro-F1 improvement over no correction, outperforming well-known stain normalization techniques. Among feature-space methods, a simple feature-wise standardization achieved the best improvement over no correction, outperforming CORAL. Under patient-averaged tile-level evaluation, combining FIX with feature-wise s

---

### [150] Path to Prior-Data Fitted Relational Models via Learned Latent Multi-table Representations

**链接**: https://arxiv.org/abs/2610.23073
**作者**: Mohammad Sadeq Abolhasani, Viswanath Ganapathy
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prior-data fitted networks (PFNs) show that pretraining on large populations of synthetic tasks can enable generalization to unseen datasets with little or no downstream fine-tuning. This paradigm is effective for transformer-based tabular and relational foundation models such as RDB-PFN, but remains largely unexplored for graph-based relational models built on message passing. We pretrain the graph-based relational foundation model Griffin on large collections of synthetic relational databases and ask whether curriculum learning, which benefits transformer-based relational learners, also improves message-passing representations. Rather than fine-tune on downstream tasks, we use the pretrained encoder as a general-purpose relational representation learner and pass its latent representations to a frozen in-context predictor (\ticl{}); no component is trained on the target task. On 16 real-world relational classification tasks, evaluated over five seeds against raw-feature and untrained-

---
