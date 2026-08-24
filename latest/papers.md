# 📑 论文索引 - 2026-08-24

共 145 篇论文

---

### [1] Vis-Poison: Poisoning Visual Knowledge in Multimodal Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2608.20756
**作者**: Rujin Liang, Zhongpu Chen, Yuhao Lei, Xin Miao
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multimodal retrieval-augmented generation (RAG) systems increasingly rely on images as external knowledge sources, the introduction of poisoned visual evidence can severely compromise multimodal large language model (MLLM) generation. Unlike prior attacks that rely on altering textual metadata, we introduce Vis-Poison, a novel visual knowledge poisoning attack where the poisoned image itself is the attacker-controlled payload, without manipulating captions, summaries, metadata, or other associated text. Specifically, this attack is instantiated through an automated multi-agent method that constructs visually plausible poisoned images. To assess its impact, we evaluate Vis-Poison across two representative multimodal RAG pipelines, four embedding models, and six generation models. Empirically, Vis-Poison achieves an end-to-end attack success rate of 40.16\% to 65.40\% against 30k-entry multimodal knowledge bases in \emph{black-box} settings. Moreover, Vis-Poison remains effective a

---

### [2] ConceptTS: LLM-Guided Concept Bottlenecks for Interpretable Multivariate Time-Series Forecasting

**链接**: https://arxiv.org/abs/2608.21277
**作者**: Yichen Jiang and Yueqiao Chen and Dongyu Liu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> State-of-the-art multivariate time-series forecasters can model complex temporal and cross-variable dependencies, yet their opaque representations provide limited insight into why a particular forecast is produced. This lack of transparency restricts their use in settings where practitioners must understand and assess the factors underlying a prediction. We introduce ConceptTS, an interpretable forecasting framework that organizes its predictions around named, human-readable concepts. ConceptTS uses a large language model to propose task-relevant concepts and generate executable labeling rules, translating the language model's domain knowledge into direct supervision without costly manual concept annotation. The proposed concepts are organized into three complementary bottlenecks that describe the historical context, local forecast intervals, and the full forecast horizon. A shared decoder combines representations derived from their predicted activations to construct the forecast, maki

---

### [3] An ambiguity taxonomy for evaluating large language model performance on clinical registry abstraction: a multi-site prospective study

**链接**: https://arxiv.org/abs/2608.20373
**作者**: James Matheson, Betsy Castillo, Andrew Y. Shin, David Scheinker
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: To evaluate large language model (LLM) performance on unprocessed electronic medical record (EMR) data for clinical registry abstraction. Methods: We evaluated LLM performance answering registry questions for the American College of Cardiology National Cardiovascular Data Registry (ACC NCDR). In a pilot study at an academic medical center, the model identified candidate data sources for each registry question and experienced abstractors used these results to define question-specific document sets. In a validation study at a second center with a second ACC NCDR registry, the LLM answered questions using the question-specific document sets. Before reviewing any output, two abstractors independently established the ground truth and assigned each question to one of six categories, ordered by the ambiguity and clinical reasoning required to resolve it: Medication/Event Flag, Binary Clinical Presence, Administrative, Quantitative Laboratory/Physiologic, Clinical Interpretation, an

---

### [4] Recognition-Conditioned Reasoning: A Training-Free Multimodal-LLM Pipeline for Fine-Grained Micro-Action Understanding

**链接**: https://arxiv.org/abs/2608.21022
**作者**: Fengshun Wang, Jin'ang Han, Zhigang Tu
**来源**: cs.CV cs.MM
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Micro-actions are subtle, short, low-amplitude body movements, such as a fidgeting hand or a slight head tilt, that humans perform with little conscious intent yet that reliably leak emotional and psychological state. Understanding them goes beyond assigning a label: a model must also describe which body parts move and reason, faithfully, about why a clip warrants a particular fine-grained category. We present the training-free, prompt-only system that won first place in the fine-grained understanding track (MA-Bench) of the MAC~2026 Micro-Action Challenge, where both fine-tuning and ground-truth supervision are disallowed. Built entirely upon frozen multimodal large language models (MLLMs), the system dynamically routes each of the eight sub-tasks to the MLLM empirically best suited for that task: a discriminative MLLM for closed-ended recognition tasks and a generative MLLM for open-ended description and reasoning tasks. This architecture achieves a statistically significant performa

---

### [5] ClawSentry: A Progressive Multi-Tier Security Monitor for Safeguarding Autonomous LLM Agents

**链接**: https://arxiv.org/abs/2608.21101
**作者**: Kai Wang, Zeming Wei, BiaoJie Zeng, Chang Jin, An Wang, Xiaokun Luan 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents move from conversation to executing code, reading local files, and orchestrating external tools, a single agent hijacked by a malicious third-party skill can cause data exfiltration, privilege escalation, or cascading compromise. We argue that agentic risk is progressive: it can enter at four loci of the agent control loop--skill admission, invocation-time intent, execution-time effect, and post-action consequence--while a denied dangerous objective can reappear across surface forms, tools, or turns; existing safeguards are typically local to one lifecycle boundary or one call. Guided by this threat model, we present ClawSentry, an open-source, framework-agnostic security supervision gateway for agent runtimes. Before a skill package is ever executed, First-use Skill Package Review (FSPR) audits it under a deterministic evidence floor, escalating unresolved cases to bounded read-only agentic review (locus A). At runtime, a three-tier progressive dec

---

### [6] An LLM agent for end-to-end computational materials discovery

**链接**: https://arxiv.org/abs/2608.20434
**作者**: Chen Yuntong and Huang Ju and Liu Yu and Zhao Dan and Sun Mingqi and Ju Chentian and Liu Yanbing and Huang Lijiang and Zhao Guobin
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The coordination of multi-scale tasks is an effective strategy for computational materials discovery, yet the repeated application of diverse algorithms and tools renders it challenging. We report MAESTRO, a large language model (LLM) agent system capable of executing the entire screening pipeline for metal-organic frameworks (MOFs). It processes a large body of MOF literature, links relevant publications to their crystal structures, and curates the results into a computation-ready database, which is then screened through a strategy of progressively increasing computational cost. The promising candidates identified for separation under wet flue gas conditions all originate from unrelated studies. By connecting the heterogeneous stages of computational materials discovery, the LLM-based agents of MAESTRO can operate across application domains and uncover high-performance materials that conventional screening approaches would be unlikely to consider.

---

### [7] Designing a Robust LLM-Based Evaluation System for Agentic AI in Drug Discovery Through Human Alignment

**链接**: https://arxiv.org/abs/2608.21057
**作者**: Emma Granqvist, Roc\'io Mercado, Samuel Genheden
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic large language model (LLM) systems are reshaping scientific workflows in chemistry and drug discovery, but evaluating their open-ended, tool-augmented outputs remains a fundamental bottleneck. Reference-based metrics such as BLEU and ROUGE fail to capture semantic correctness, while expert human evaluation does not scale to the iteration speed these systems demand. The LLM-as-a-Judge paradigm has emerged as a scalable alternative, but existing drug discovery benchmarks deploy LLM judges without validating their alignment with human experts. In this work, we present an LLM-as-a-Judge evaluation framework for ChatInvent, an agentic drug discovery assistant deployed at AstraZeneca, with four contributions. First, we define four output-quality evaluation dimensions---Completeness, Relevancy, Structural Clarity, and Scope Adherence---alongside deterministic Tool Call Correctness checks. Second, we validate the judge through a human alignment study with five expert annotators, compar

---

### [8] Causal Modeling of Adverse Pregnancy Outcomes via Adaptive LLM Proposals

**链接**: https://arxiv.org/abs/2608.21079
**作者**: Kavimayil P. Komarasamy, Saurabh Mathur, Ameet Soni, David M. Haas, Kristian Kersting, Sriraam Natarajan
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adverse Pregnancy Outcomes (APOs) such as preterm birth and gestational diabetes can have long-term consequences for both the mother and child, yet an understanding of their causes remains elusive. Causal discovery in this domain is especially challenging due to a paucity of data and incomplete domain knowledge. As a result, pure data-driven methods fail, and Large Language Model (LLM) outputs remain inconsistent or contradictory. We introduce a neurosymbolic framework for generating plausible causal hypotheses that iteratively combines the broad prior knowledge of LLMs with empirical scoring on data. Our method treats the LLM as an adaptive proposal distribution, generating hypotheses that are scored against empirical data; the resulting high-scoring graphs are then used to update the LLM's context, steering subsequent generations toward more promising regions of the hypothesis space. We evaluate our approach on a real-world clinical dataset for modeling APOs and their risk factors, c

---

### [9] Evaluating Large Language Model Performance on International Maritime Dangerous Goods Code Compliance

**链接**: https://arxiv.org/abs/2608.21036
**作者**: Alexander Thomas, Hubert P. H. Shum, Darren Nellis, Manli Zhu, Phatpicha Yochum, William Bartle and Daniel Wrightson
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The transport of dangerous goods by sea is a high-consequence activity governed by the International Maritime Dangerous Goods (IMDG) Code, a complex regulatory framework where errors in classification, packaging, stowage, or segregation can result in fire, explosion, toxic release, or loss of life or vessel. Correct compliance requires accurately interpreting hundreds of pages of interacting provisions, updated on a two-year amendment cycle. Practitioners increasingly use Large Language Models (LLMs) as decision-support tools, yet no systematic evaluation exists of whether they can reliably interpret IMDG requirements for safety-critical use. This paper introduces DGEval, the first benchmark for evaluating LLM knowledge of IMDG Amendment 42-24. Built from expert-written questions on the NCB Hazcheck e-learning platform and structured lookups from the Dangerous Goods List (DGL), it comprises 1,678 questions across multiple-choice, open-ended, DGL lookup, and regulatory identification ta

---

### [10] Weighted Memory Tree: Remembering What Matters for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2608.20631
**作者**: Quang Dao, Purvi Kathalkar, Kenneth Eaton
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated the ability to solve multi-step tasks requiring planning, tool use, and external information access, yet growing execution histories increase inference cost and expose reasoning to outdated, irrelevant, or misleading information, potentially degrading reasoning quality. Existing memory approaches organize or compress execution histories but provide limited mechanisms for deciding which memories remain active. We introduce the, a hierarchical memory system that organizes execution into tasks, subtasks, and actions while assigning each memory a dynamic retention score. Event-based updates and selection-based decay revise these scores, allowing WMT to preserve useful information, fold completed trajectories, suppress low-utility content, and retain access to folded context. We evaluate WMT on GAIA-Text using Qwen3-8B, Gemma 4 E4B, and Llama-3.1-8B, with ablations and memory-poisoning experiments. Relative to linear memory, WMT improves a

---

### [11] Who Trusts AI with Their Emotions? Trust Formation and Sociodemographic Variation in LLM Use for Emotional Support

**链接**: https://arxiv.org/abs/2608.21220
**作者**: Natalia Amat-Lefort, Mert Yazan, Amanda Cercas Curry, Flor Miriam Plaza-del-Arco
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trust in AI for emotional support is not universal; it is shaped by who users are, where they come from, and what they value. Yet research in this area lacks validated psychometric instruments for assessing user perceptions in affective AI contexts and large-scale evidence on how trust formation varies across user segments. To address these gaps, we develop and validate a seven-construct psychometric scale, test a Structural Equation Model (SEM) linking system attributes to Trust and Perceived Benefits as mediators of Actual System Use, and conduct a Multi-Group Analysis (MGA) across five sociodemographic dimensions (gender, age, education, socioeconomic status, cross-national region), drawing on 1,343 active users from seven countries. We find that users experience empathy and anthropomorphism as a unified "Humanlikeness" construct, and that Privacy, Personalization, and Humanlikeness drive Trust while Perceived Bias degrades it. Notably, adoption logic diverges across groups: Privacy

---

### [12] Auditable by Construction: An Ontology-Driven Framework for Trustworthy LLM Analytics in Enterprise Finance

**链接**: https://arxiv.org/abs/2608.20661
**作者**: Sergiy Lunyakin
**来源**: cs.AI cs.CE cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise adoption of large language models in finance is constrained less by fluency than by trust: in Financial Planning and Analysis (FP&A) and other regulated workflows, an answer is usable only if it is traceable to authoritative sources and auditable after the fact. This paper argues that retrieval-augmented generation for enterprise finance should be evaluated on auditability alongside accuracy, and presents the Knowledge-Driven Analytics Framework (KDAF), which builds ontology-driven knowledge systems through six iterative stages and retrieves evidence via Context-Aware Relevance Propagation (CARP), so that every retrieved fact carries its relationship type, confidence, and source lineage. An evaluation on FinanceBench (145 questions) compares KDAF against zero-context inference, BM25, concept-weighted lexical retrieval, and ungrounded graph traversal. First, retrieval is necessary: zero-context inference reaches 4.1% correctness against 10-12% for retrieval-augmented conditio

---

### [13] Agentic ESOpt: Fine-Tuning Long-Horizon LLM Agents with Minimal GPU Requirements

**链接**: https://arxiv.org/abs/2608.17310
**作者**: Zhi Zheng, Rongsheng Chen, Yunpeng Ba, Zhenkun Wang, Yee Whye Teh, Wee Sun Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Reinforcing Multi-Turn Reasoning in LLM Agents via Fine-Grained Reward Structure and Credit Assignment

**链接**: https://arxiv.org/abs/2505.11821
**作者**: Quan Wei, Siliang Zeng, Chenliang Li, Zhongruo Wang, William Brown, Oana Frunza 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] When the Feature Pool Goes Algorithmic: Extending Mufwene's Ecology of Language Evolution to LLM-Mediated Exposure

**链接**: https://arxiv.org/abs/2608.21088
**作者**: Kunmei Han
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mufwene's ecological model locates language evolution in competition among variants contributed by individual idiolects and in speakers' selection from linguistic material made available through interaction. Large language models (LLMs) complicate this architecture without requiring the locus of selection to move away from human speakers. This article argues that LLMs are best treated as distributional mediators: they aggregate language produced across human populations, transform its distribution through training and post-training, and redistribute model-specific outputs at scale. I call the resulting ecological process algorithmic reweighting of the speaker-accessible distribution: model mediation can alter the relative frequencies with which competing variants reach human selectors. Emerging evidence on model-specific linguistic profiles and lexical uptake is consistent with parts of this pathway, but does not establish inevitable convergence. Human social evaluation remains decisiv

---

### [16] TH-GNN: Heterogeneous Temporal Graph Neural Networks for LLM-Agent Shilling Attack Detection

**链接**: https://arxiv.org/abs/2608.20376
**作者**: Shivam Swarup, Divya Prakash Shrivastava, Rakesh Thakur
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can now generate realistic shilling profiles, fluent reviews, and coherent ratings at scale, systematically defeating recommender-system defenses. Text-only detectors that flag semantic drift in review embeddings are blind to graph structure and temporal coordination, while graph-only detectors that exploit neighborhood anomalies cannot reason over review semantics or the cross-modal inconsistencies produced by LLM-generated content. We propose TH-GNN, a heterogeneous temporal graph neural network with a two-layer Heterogeneous Graph Transformer backbone that applies per-type and per-relation attention augmented with learnable sinusoidal temporal encodings on every edge. Cross-modal attention fuses structural user embeddings with frozen RoBERTa representations of reviews and item descriptions, while a GRU operating over log inter-arrival times captures temporal burstiness. Evaluated across five attack families and four benchmark datasets, TH-GNN achieves a grand-mean F1 scor

---

### [17] PromptResponse: Optimizing Prompts for LLM Coding Tasks

**链接**: https://arxiv.org/abs/2608.21074
**作者**: Erik Thureck, Robert K\"uhnen, Tim Jacobowitz
**来源**: cs.CL cs.AI cs.HC cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in research workflows and software development pipelines, yet their output remains sensitive to input prompt variations. This paper presents $\unicode{x00AB}$PromptResponse$\unicode{x00BB}$, a controlled study examining how formatting and LLM-based tuning of coding task prompts affect the resulting code's performance, efficiency, and stability. Using five semantically identical yet syntactically distinct variants of the HumanEval dataset$\unicode{x2014}$baseline, JSON, Markdown, YAML, and an LLM-tuned version$\unicode{x2014}$we had GPT-4o solve its coding problems over 8200$\unicode{x00A0}$executions. Our results show that consistent formatting$\unicode{x2014}$especially JSON$\unicode{x2014}$improves generation efficiency and syntactic stability, with minor gains in task performance. Conversely, the LLM-tuned prompts resulted in significantly degraded task performance without significant improvements in any other dimension. These findi

---

### [18] Distilling Black-Box Machine Learning into a Small, Self-Explaining Language Model for Learning Analytics

**链接**: https://arxiv.org/abs/2608.21165
**作者**: Chenguang Pan, Airui Meng, and Youmi Suk
**来源**: cs.HC cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning analytics increasingly relies on flexible machine learning (ML), but the model opacity and the burden of deployment prevent these tools from reaching educational practice. We propose a two-stage fine-tuning pipeline that distills a fitted black-box estimator and its post hoc interpretation (the mentor) into a small, open-weight large language model (LLM; the mentee) that returns an individual-level estimate and explains in natural language. The design is estimator-agnostic and paired with a faithfulness-first evaluation framework that audits every narration against the attribution it claims to describe. We design a simulation study that separates distillation loss from estimator loss by comparing an oracle mentor with a realistic ML mentor. Given an oracle signal, distillation with a two-billion-parameter LLM model is nearly lossless in recovering the effect surface (r > .90), perfectly ranking the important variables, and citing no spurious covariate. Under a realistic estima

---

### [19] Graph Engineering in the Era of LLM Agents: From Individual Intelligence to System Intelligence

**链接**: https://arxiv.org/abs/2608.21156
**作者**: Yuyuan Feng, Zhishang Xiang, Chaobin Yang, Qichao Ma, Zerui Chen, Yujing Zhang 等 (10 人)
**来源**: cs.IR cs.AI cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs have evolved from language generators to autonomous agents capable of complex, long-horizon tasks. This evolution has produced paradigms including Prompt Engineering to elicit model capabilities, Context Engineering to manage information access, Harness Engineering to organize external tools and resources, and Loop Engineering to support continual reflection and self-improvement. Yet as tasks grow more complex, individual intelligence faces a fundamental limit: many tasks require heterogeneous expertise, interdependent subtasks, parallel execution, independent verification, and persistent state, exceeding any single agent's organizational capacity. Augmenting one agent's capabilities or context cannot resolve this architectural mismatch; intelligence must instead be distributed across specialized agents and organized at the system level. We call this System Intelligence: an agent system's ability to organize and coordinate multiple intelligent components into a coherent, adaptive 

---

### [20] Trustworthy RAG: An Evaluation Agent for Detecting Misinformation and Knowledge Poisoning in Generative AI Systems

**链接**: https://arxiv.org/abs/2608.21095
**作者**: Balkrishna Giri, Md Toufique Hasan, Jussi Rasku, Muhammad Waseem, and Pekka Abrahamsson
**来源**: cs.SE cs.AI cs.CL cs.CR cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) grounds Large Language Model (LLM) outputs in external knowledge, but RAG systems usually trust whatever they retrieve, creating a Security-Reliability Gap: high semantic relevance does not guarantee factual truth. Adversaries exploit this through knowledge poisoning, inserting malicious documents to cause targeted misinformation. We propose an Evaluation Agent, middleware that combines Natural Language Inference (NLI) factual verification, a five-signal poison detector with relevance-weighted aggregation, and a Trust Index T = 0.4 F + 0.35 C + 0.25 (1 - P ) with a non-linear dampener for high-contamination contexts. On TruthfulQA with Llama 3.3 70B, the agent reaches 91% accuracy and 100% precision, with 100% recall on instruction injection, while in-place edits, such as entity swaps, remain hard to detect. Across three LLMs the Trust Index stays discriminative, with a Receiver Operating Characteristic Area Under the Curve (ROC-AUC) of 0.73 to 0.81

---

### [21] No PUN Intended: Plausible Unknown Names for Person-Centred LLM Evaluation

**链接**: https://arxiv.org/abs/2608.21206
**作者**: Dimitri Staufer, David Hartmann, Ibrahim Baroud
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Person names are widely used as prompt variables in LLM evaluations of factuality, privacy leakage, bias and abstention, but when a name's evidential status is uncontrolled, measurements may conflate memorisation, retrieval, name priors and wrong-person attribution. We operationalise an unknown name as one with plausible First-Last form, no indexed full-name evidence, and no ambiguity signals under a documented validation run, and introduce PUN (Plausible Unknown Names), a protocol for constructing and validating such names, combining Wikidata-derived components, web-enabled LLM screening, and controlled search revalidation. We report acceptance rate, reproducibility, ablations, and a 204-participant human study, finding accepted names are more name-like than controls while participants recover person evidence in only 3% of cases. We release 300 names with comparison controls.

---

### [22] Profiling What Matters: Context-Aware Item Profiles from Large-Scale Metadata for LLM Recommenders

**链接**: https://arxiv.org/abs/2608.20801
**作者**: Dojun Hwang, Seunghan Lee, Cheonyoung Park, Sara Yu, SeongKu Kang
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models (LLMs) have significantly advanced reranking in recommendation, effectively leveraging item-side information remains challenging. Real-world items are described by vast, heterogeneous, and unstructured metadata, where decision-relevant signals are often implicit, noisy, or buried in long descriptions. Moreover, feature salience is highly context-dependent, varying not only across items but also across users. Existing methods often rely on item titles, fixed attributes, or static item summaries, which limit personalized and fine-grained item understanding. To bridge this gap, we propose CAIRO, a user context-aware item profiling framework for LLM-based reranking. CAIRO first structures raw metadata and reviews into objective features and subjective traits, and employs a lightweight profiler to select the most relevant information for each user-item pair with limited serving-time overhead. The resulting profiles are concise and context-specific, providing rele

---

### [23] SEISMO: Explanation-Aware, Trajectory-Conditioned LLM Agents for Sample-Efficient Molecular Optimisation

**链接**: https://arxiv.org/abs/2602.00663
**作者**: Fabian P. Kr\"uger, Andrea Hunklinger, Adrian Wolny, Tim J. Adler, Igor Tetko, Santiago David Villalba
**来源**: cs.AI cs.LG q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] Supporting The Many Lives of Personal Data with Rebite: LLM-Powered Goal-Directed Framing in Food Journaling

**链接**: https://arxiv.org/abs/2608.21289
**作者**: Weijun Li, Daniel A. Epstein
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People's health and tracking goals frequently change, but most personal informatics systems struggle to adapt, leading people to abandon their data and start over. We propose goal-directed framing, an approach that repositions goals within personal informatics systems. Instead of fixing the meaning of data at capture time, the approach frames the collected data through the current goal and reframes it whenever the goal changes. We realize this in Rebite, a photo-based food journaling system that uses LLMs to read unstructured meal photos and produce goal-directed feedback. In a one-week deployment with 21 participants managing multiple dietary goals, we find that goal-directed framing shaped how participants engaged with their goals. Translating a goal into metrics helped them see what it meant in practice, confirming existing priorities, surfacing what they overlooked, and revealing where the metrics fell short. When goals changed, seeing past meals reframed under the new goal exposed

---

### [25] GradeDrift- LLM : Measuring Student-History-Induced Score Drift in LLM -Based Automated Grading

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2504-4990/8/8/252&hl=zh-CN&sa=X&d=11050463823399285628&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-xbWZ4pfq10k-U5fMJ28ij3&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: C Anghel, AA Anghel, MV Craciun, A Cocu… - Machine Learning and …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Methods: This study introduces GradeDrift- LLM , a controlled framework for measuring student-history-induced score drift in LLM -based … Conclusions: Student-history metadata can influence LLM -generated grading scores despite explicit instructions

---

### [26] From Regulation to Implementation: A Critical Evaluation of LLM-Assisted Regulatory Compliance in Industry

**链接**: https://arxiv.org/abs/2608.21317
**作者**: Adriana Watson, Marco B\"ucheler, Grant Richards
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The European Union (EU) has emerged as a leading regulatory body in the development of sustainability and privacy regulations. While new regulation requirements vary, many include a documentation artifact to ensure compliance. Notably, the Ecodesign for Sustainable Products Regulation (ESPR) introduces Digital Product Passports (DPPs) for life cycle transparency, while the General Data Protection Regulation (GDPR) mandates Data Protection Impact Assessments (DPIAs) to mitigate privacy risks. Creating these compliance artifacts, however, is challenging. Industrial data, which often exists in heterogeneous formats and is scattered across company and supplier systems, is required for DPPs and can be difficult to extract into compliant DPP formatting. Furthermore, DPIA documents require interdisciplinary expertise and follow no standardized format, making development difficult for novel systems. To address the particular complexity of compliance artifact creation for both regulations, rese

---

### [27] VortexChat: An agentic framework for autonomous multi-objective integrated photonic design

**链接**: https://arxiv.org/abs/2608.20688
**作者**: Faqian Chong, Yulun Wu, Shilong Li, Andrew Forbes, Hongsheng Chen, Song Han
**来源**: cs.AI physics.optics
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The advancement of modern integrated photonics is frequently bottlenecked by device design workflows that rely heavily on manual simulation and expert intuition. While inverse design offers an alternative, it remains constrained by expert supervision and a lack of end-to-end automation. To address these issues, we present VortexChat, an agentic framework for the autonomous, end-to-end inverse design of integrated photonic devices directly from natural language specifications. VortexChat couples a large language model (LLM) decision agent with topology generation, gradient-based refinement, and full-wave electromagnetic simulation. This closed-loop architecture enables the system to iteratively decompose design objectives, orchestrate computational tools, and update strategies based on feedback with minimal human intervention. Constrained by the absolute metrics of the Vortex100 Benchmark, VortexChat autonomously generates devices that strictly meet all predefined performance thresholds

---

### [28] Research on the characteristics of teacher-student questions&answers interaction behavior based on LLM qualitative coding

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-67483-0_reference.pdf&hl=zh-CN&sa=X&d=5920353168813934190&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-xPPp7LS-6u9paivG1nQNvk&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: Q Ou, S Wu, X Chen - Scientific Reports, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address these theoretical and methodological gaps, this study develops a theory-driven, LLM -assisted framework for analyzing how … coded with the support of an LLM according to a predefined coding framework. The reliability of LLM -assisted

---

### [29] KREL: Automatic Medical Coding via Knowledge-Guided Reasoning over Clinical Evidence with LLMs

**链接**: https://arxiv.org/abs/2608.20887
**作者**: Xubin Chen, Yipeng Zhou, Wen Sun, Chengkai Huang, Xiaoming Fu, Quan Z. Sheng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic Medical Coding (AMC), which assigns standardized International Classification of Diseases (ICD) codes to clinical notes, is essential for medical reimbursement, quality reporting, and clinical research. Existing pre-trained language model (PLM)-based methods typically formulate AMC as an extreme multi-label classification problem over a predefined code set, while recent large language model (LLM)-based approaches instead frame it as generation or multi-step reasoning. However, key challenges remain, including the extreme length of clinical notes that hinders effective interpretation, the vast ICD label space, and complex coding rules that are not explicitly captured by LLMs. In this work, we propose Knowledge-Guided Reasoning over Clinical Evidence with LLMs (KREL), a framework that leverages LLMs for clinical text understanding and reasoning while integrating external ICD coding guidelines as structured knowledge. This design enables tight coupling between domain knowledge a

---

### [30] LLM -Assisted Reviewer Assignment via Auditable Expertise Matching

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11658587.pdf&hl=zh-CN&sa=X&d=16791153413860329612&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-wQXZTfnarvKgOrS10lIjtL&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: F Bagheri, D Buscaldi, DR Recupero - IEEE Access, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Accurate reviewer assignment is essential for scalable peer review, yet practical systems must balance semantic match quality with transparency, auditability, and manageable reviewer workloads. We study an end-to-end, LLM -assisted reviewer–paper

---

### [31] Calibrating Criterion Revision in LLM Agents: Failure Modes and a Trace-Anchored Protocol

**链接**: https://arxiv.org/abs/2608.20729
**作者**: Guodong Xu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents can improve after failure or carry text across episodes without revising what counts as success. We study the narrower attribution problem of criterion revision: when criterion K0 accepts an outcome violating a broader commitment B, what observations justify saying that the system formed and persistently used K1? We require five non-compensatory conditions: criterion-failure detection, a model-emitted proposal, new-episode transfer, intervention sensitivity on the claimed carrier, and preservation. We evaluate CMB-0.1 on twelve cross-domain cases and four arms: stateless inference, append-only history, model-generated but harness-committed state, and evaluator-written oracle state. Seven mechanism fixtures yield 84 deterministic scorer trials; four local quantized artifacts yield 96 calls and 192 model-case-arm trials. No model trial satisfies all five conditions, but this zero does not establish general capability absence. Eleven calls remain invalid after one re

---

### [32] Affective Context Amplifies Sycophancy in LLM Responses

**链接**: https://arxiv.org/abs/2608.21242
**作者**: Jiayi Li, Sanjana Menon, Brett Frischmann, Shomir Wilson, Sarah Rajtmajer
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As conversational companions, large language models (LLMs) often have access to users' emotional states. We study how this affective context modulates LLM sycophancy in subjective, evaluative interactions, where users share actions or opinions that invite feedback. Drawing on ingratiation theory, we measure sycophancy as the divergence between a model's independent evaluation and its user-facing response, elicited by presenting the same content as either a third-party account or the user's own disclosure. Across seven LLMs and two Reddit datasets (r/AmItheAsshole and r/TrueUnpopularOpinion), we find that this divergence is systematic and strongly one-directional. User-facing responses consistently soften or withhold negative or oppositional judgments. Affective context further amplifies this divergence with negative states, particularly loneliness and distress, producing the largest effects. These findings suggest that affective context functions as a vulnerability signal that suppress

---

### [33] Benchmarking LLM Serving Systems for Agentic AI Workloads with XPerf

**链接**: https://arxiv.org/abs/2608.20370
**作者**: Michael Wang, Yikang Yue, Shaobo Li, Yirui Eric Zhou, Chen Wang, Jian Huang
**来源**: cs.DC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present XPerf, a benchmarking framework that load-tests LLM serving systems with diverse agentic AI workloads. It provides detailed profiling of the serving system and hardware, enabling users to identify performance bottlenecks introduced by agentic workloads. Benchmarking LLM serving systems under agentic workloads is challenging - agentic applications rely on nondeterministic LLM outputs to guide their control flow; therefore, workload patterns vary unpredictably from run to run. XPerf minimizes this workload variation with a fine-grained trace replay approach: it enables users to easily collect traces from real agentic applications, synthesize new workloads with various patterns if needed, and reproducibly replay them on different LLM serving systems. XPerf includes eight agentic applications across diverse use cases (e.g., coding, deep research, and Q&A) by default. Our empirical study using these workloads shows that XPerf accurately replays agentic workloads, provides detaile

---

### [34] ExpertIVS: Sociological Expert Driven Individual Value Simulation in Large Language Models

**链接**: https://arxiv.org/abs/2608.20355
**作者**: Zhen Wang, Yuqi Ren, Yuehan Cui, Hongxiang Wang, Jianxiang Peng, Zhaoxia Zhang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents have demonstrated considerable potential for social simulation, yet struggle to accurately model individual value systems. Most existing methods mechanically stitch survey responses into prompts, which suffer from semantic fragmentation, failing to capture the internal coherence of human value systems. The value systems of LLMs are typically assessed using static multiple-choice questions, which fail to evaluate the value orientation in real-world dialogue interactions. To address these issues, we propose ExpertIVS, a framework employing 14 Sociological Expert Agents to interpret World Values Survey (WVS) responses through structured professional perspectives, rather than direct responses concatenation. These expert agents perform deep semantic reconstruction to generate robust and internally consistent individual profiles. To evaluate the consistency between LLMs and individual value systems during dynamic interactions, we further introduce a multi-ag

---

### [35] FL-MAESTRO: Multi-Agent LLM Orchestration for Resource-Constrained Federated Learning

**链接**: https://arxiv.org/abs/2608.20518
**作者**: Jiajun Wu, Zirui Wang, Jiayu Zhou, Qiang Ye, Steve Drew
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In Federated Learning (FL), the communication topology is a runtime variable rather than a fixed design choice, since links and edge devices drop in and out during training. Each round, the server must commit three coupled decisions, namely the communication topology, per-client resource allocation, and the aggregation rule for combining local updates. Recent agentic systems have begun bringing large language models (LLM) into FL, but the existing line of work either operates at setup time or handles a single runtime dimension such as client selection. We propose FL-MAESTRO, a multi-agent orchestrator that makes the joint runtime FL decision directly through three specialist LLM agents, one per decision dimension. A coordinator combines their analyses into a single decision, and a non-LLM feasibility check confirms it before the round executes. Because the orchestrator consumes the server's predicted-failure list, it withholds clients whose updates would never be aggregated, which remo

---

### [36] Specification Portability Across LLM Development Agents: Cross-Agent Compatibility in Specification-Driven Software Migration

**链接**: https://arxiv.org/abs/2608.21208
**作者**: Oleg Grynets, Oleksii Ilchuk, Dariia Zatulna, Vasyl Lyashkevych
**来源**: cs.SE cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper investigates cross-agent specification portability using Oracle-to-PostgreSQL migration as a controlled software transformation task. The study combines two experimental stages. First, a specification-first migration pipeline was evaluated on 1,006 PL/SQL files, of which 623 were successfully regenerated and 380 generated scripts executed successfully in PostgreSQL 16. Second, cross-agent experiments were conducted on a dataset of 1,802 Oracle scripts with corresponding PostgreSQL implementations using Amazon Kiro, Google Gemini, and GitHub Copilot, with Claude Code and Cursor included in the initial single-agent evaluation. Native and foreign specifications were assessed using Token F1, exact match, SQL syntax validity, AST exact match, AST mean similarity, and immediate runnability. The results show that specification size alone does not predict implementation quality and that cross-agent transfer can produce substantial agent-dependent degradation. The strongest replicate

---

### [37] Leveraging Survey-Informed LLM Personas to Identify Cultural References: Enhancing Inclusivity in News Reporting

**链接**: https://scholar.google.com/scholar_url?url=https://www.aup-online.com/content/journals/10.5117/CCR2026.2.10.PILL%3Fcrawler%3Dtrue%26mimetype%3Dapplication/pdf&hl=zh-CN&sa=X&d=6376442708083936132&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-zjH7iA1QJg_wnX646s6PeT&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: R Pillai, A Fokkens, W Atteveldt - Computational Communication Research, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We explore the possibility of using LLM personas to … LLM outputs prompted with the same persona, and improvement in LLM performance with additional prompt inputs based on survey data. The present results show, for the first time

---

### [38] Library Hallucinations in LLM-Generated Code: A Risk Analysis Grounded in Developer Queries

**链接**: https://arxiv.org/abs/2509.22202
**作者**: Lukas Twist, Mark Harman, Helen Yannakoudakis, Jie M. Zhang
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Complete Cyclic Subtask Graphs for Tool-Using LLM Agents: Flexibility, Cost, and Bottlenecks in Long-Horizon Workflows

**链接**: https://arxiv.org/abs/2604.22820
**作者**: Luay Gharzeddine and Samer Saab Jr
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] MQM-guided multi-agent data reconstruction in LLM -based machine translation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306457326004929&hl=zh-CN&sa=X&d=16029572377105922987&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-yRE4kmM8_o2Ay3Yar3gcIM&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: X Shi, Z Chang, P Cheng, G Zhang, Y Li - Information Processing & Management, 2027
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Quality imperfections within parallel corpora substantially hinder the performance of large language models (LLMs) for machine translation tasks. To address this, we propose a Diagnose-Reconstruct-Train framework to enhance LLM translation

---

### [41] PrimeAgentOrchestrator: Memory-Primed Agent Spawning for Personal AI Infrastructure

**链接**: https://arxiv.org/abs/2608.20342
**作者**: Myron Koch (Peak Summit Labs)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) coding agents start each session with an empty context window, discarding accumulated knowledge from prior work. We present PrimeAgentOrchestrator (PAO), a system that spawns new instances of Claude Code -- Anthropic's terminal-based coding agent -- pre-loaded with relevant memories compiled from the user's existing personal databases. At spawn time, PAO queries two independently-operated memory backends in parallel (a PostgreSQL entity-observation database and a Cloudflare Worker semantic search index), fuses results using backend-specific retrieval strategies, and delivers the compiled briefing via filesystem injection that exploits the host agent's configuration auto-read behavior. PAO manages the full agent lifecycle including trust pre-seeding, readiness polling with error detection, and adaptive terminal text injection. We report on four months of regular deployment (December 2025 through March 2026) as an experience report, documenting three generation

---

### [42] LLM -Advisor: An LLM Advisor for Cost-efficient Path Planning across Multiple Terrains

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11658723/&hl=zh-CN&sa=X&d=2119170261588357646&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-zxnamJrdarnwsJsBduL2NE&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: L Xiao, T Yamasaki - IEEE Transactions on Automation Science and …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Using coarse-lattice A* with stride r = 50 as the fixed baseline planner, we compare LLM -Advisor with direct LLM planning and LLM -A*. LLM -Advisor … We propose LLM -Advisor, which uses an LLM as an external routeproposal module

---

### [43] Don't Judge Code by Its Cover: Exploring Biases in LLM Judges for Code Evaluation

**链接**: https://arxiv.org/abs/2505.16222
**作者**: Jiwon Moon, Yerin Hwang, Dongryeol Lee, Taegwan Kang, Yongil Kim, Kyomin Jung
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] The Governance Gap in Contemporary LLM -Based Agentic Systems: A Structural Diagnostic Review

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2673-2688/7/8/322&hl=zh-CN&sa=X&d=1326762716595321313&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-wzR0VdXXXfPD0OY_BUSMxw&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: C Valdez-Cantú, JA Cantoral-Ceballos… - AI, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large Language Models (LLMs) are increasingly integrated into agentic workflows that require extended reasoning, persistent state management, coordinated tool use, and controlled execution. As this operational scope expands, a central question

---

### [45] ProofJudge: Tool-Grounded LLM Evaluation of Formal Proof Quality in Mathlib

**链接**: https://arxiv.org/abs/2608.20432
**作者**: Shane Caldwell
**来源**: cs.LO cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formal proofs in Lean 4 that pass the kernel's type checker can nonetheless vary widely in quality. We introduce ProofJudge, an agentic LLM-as-judge system that scores formal proof quality along five dimensions beyond correctness: library leverage, automation fit, structural clarity, statement quality, and Mathlib conventions. We evaluate ProofJudge on a novel dataset of 218 declarations drawn from distinct Mathlib PRs. The judge agent is grounded by tool access to the commit the PR is applied to, enabling it to query the library state when scoring. A judge is considered aligned with human preferences when it rates the version of the PR Mathlib accepted above the initial version that was sent back for revision. All six judge models evaluated recover the reviewers' preference well above chance, from 80.8% to 63.5%, and two open-weight judges reach roughly 70% at a tenth of the best judge's cost. We release the judge harness, evaluation dataset, and evaluation traces as open-source artif

---

### [46] Mitigating Identity Essentialism in LLM Agents with Longitudinal Life Trajectories

**链接**: https://arxiv.org/abs/2608.19621
**作者**: Hexi Wang, Yujia Zhou, Bangde Du, Weihang Su, Xinyuan Cao, Qingyi Pan 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] The Dual Nature of LLM Persona: Aggregated Tendencies and Frame-Dependent Geometry

**链接**: https://arxiv.org/abs/2607.02368
**作者**: Yuan Yuan
**来源**: stat.ML cs.AI cs.LG math.DG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] The Lifecycle of LLM-as-a-Judge for Large-Scale Recommendation Explanations

**链接**: https://arxiv.org/abs/2608.18300
**作者**: Emma Yanyang Kong, JJ Tan, Ishan Gupta, Lars Olds, Claire Campbell, David Fagnan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] When Trust Meets Truth: Trust-Truth Separability in LLM-as-Judge

**链接**: https://arxiv.org/abs/2608.21097
**作者**: Xin Sun, Di Wu, Yuchen Guo, Jiahuan Pei, Isao Echizen, Abdallah El Ali 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-Judge systems can produce multi-dimensional evaluations, such as trustworthiness, reliability, and factuality, and these outputs are often interpreted as independent evidence. We test this assumption for a common pair of judgments: trust scoring and binary truth classification. On correctness-controlled QA, LLM judges align trust scores with truth verdicts more tightly than human behavioral reference, suggesting weaker separations between trust and truth judgment. We then apply stress tests by changing only source cues of identical QA between Human and AI. Source attribution shifts not only trust scores but also truth verdicts and logit-derived correct-side probabilities. Results show that current LLM-as-Judge protocols should not treat trust scores as independent evidence for truth judgments.

---

### [50] A scoping review on the mental health harms of LLM -based chatbots

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41746-026-03054-x&hl=zh-CN&sa=X&d=1351106020516781208&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-z46qVBYTv9aA4iojIGySBm&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: A Diel, J Torous, P Cuijpers, J Kleesiek, F Nensa… - npj Digital Medicine, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -CB use for mental health consists mostly of analyses of LLM -CB output in vignette studies and user-CB-interactions, which signal that LLM -… , generate harmful content, or express bias; qualitative studies indicate that LLM -CB output may

---

### [51] Peer-Voted LLM-Agent Stress Tests Find Feed-Induced Lexical Convergence but No Reliable Matched-Exposure Advantage for Distributed Sources

**链接**: https://arxiv.org/abs/2608.20438
**作者**: Rana Muhammad Usman and Dominic Williamson
**来源**: physics.soc-ph cs.AI cs.MA cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Population-level behavior in large-language-model (LLM) agents cannot be characterized by single-agent benchmarks. We introduce PV-SST, a peer-voted social-platform testbed, and report a separately frozen, preregistered matched-exposure experiment spanning four topics, four unused seeds, four open-weight model families, and three prespecified larger variants. The experiment comprises 448 trials and 112 complete model-by-topic-by-seed blocks. Relative to a topic-only control, a feed of previous-round peer posts ranked by peer-generated likes increases final-round lexical similarity in both the four-family core panel (paired mean difference +0.0082 TF-IDF cosine units, 95% block-bootstrap CI [0.0043, 0.0121], randomization p=0.000105, n=64 blocks) and the three-variant size extension (+0.0109 [0.0069, 0.0151], p=0.000001, n=48). This contrast bundles peer-post exposure with ranking and therefore does not identify a ranking-only effect. Opposite-side survival falls in the core panel (-3.9

---

### [52] LLM -Driven Hybrid Truss-Lattice Design via Structural Gene Recombination

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0020740326008891&hl=zh-CN&sa=X&d=10127301097666769974&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-x4vVcwMDqe00QgkKlVisGX&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: S Cao, H Meng, TJ Lu - International Journal of Mechanical Sciences, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -Driven Hybrid Truss-Lattice Design via Structural Gene Recombination - ScienceDirect … LLM -Driven Hybrid Truss-Lattice Design via Structural Gene Recombination

---

### [53] The Asymmetric Harms of LLM Compression

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.19670&hl=zh-CN&sa=X&d=9738507050222673064&ei=XtaKauC2LL686rQP4Z_o2QQ&scisig=AIVdB-x10VsEg6C7WkdDDes5t8ql&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: Y Wu, M Li, L Semenova, C Zhong - arXiv preprint arXiv:2608.19670, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models (LLMs) compression reduces deployment costs, but standard aggregate metrics like perplexity and accuracy often mask underlying behavioral shifts. In this work, we systematically evaluate 3 LLMs across 11

---

### [54] CLEAR: Continuous Latent Adapter Routing for Utility-Preserving LLM Safety Alignment

**链接**: https://arxiv.org/abs/2608.21278
**作者**: Chengxiao Wang, Enyi Jiang, Xiaojing Liao, Sanmi Koyejo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving the safety of large language models (LLMs) often comes at the expense of utility, as globally applied safety tuning may affect model responses to both harmful and benign inputs. We propose \textbf{C}ontinuous \textbf{L}at\textbf{E}nt \textbf{A}dapter \textbf{R}outing (CLEAR), a conditional safety adaptation framework that uses a lightweight hidden-state gate to continuously control the activation strength of a safety low-rank adapter. CLEAR aims to reduce harmful completions while avoiding unnecessary changes to the frozen backbone that could degrade performance on benign prompts. Experiments on widely used safety and utility benchmarks show that CLEAR improves robustness on HarmBench while reducing the utility degradation observed with globally applied safety tuning such as SFT or standard low-rank adaptation (LoRA). On Llama-3-8B-Instruct, CLEAR reduces HarmBench ASR from 32.3\% to 0.5\%, while retaining most of the base model's utility and achieving up to 7.1 percentage po

---

### [55] Share the Judge, Learn the Deferral: Where Specialization Helps LLM Evaluation

**链接**: https://arxiv.org/abs/2607.27984
**作者**: Ye Chen, Weining Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] aiXamine: Unified Black-Box Evaluation of Cross-Dimensional Trade-offs in LLM Safety, Security, and Privacy

**链接**: https://arxiv.org/abs/2608.20554
**作者**: Fatih Deniz, Yazan Boshmaf, Dorde Popovic, Issa Khalil
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The critical failure modes in deployed large language models (LLMs) are cross-dimensional: a model can score 99.3 in safety alignment while refusing one in three benign queries, or improve across every capability metric while losing 21 points in privacy. Existing evaluation frameworks that assess safety, security, and privacy independently cannot detect these patterns. We introduce aiXamine, a unified black-box platform that evaluates LLM trustworthiness across safety, security, and privacy as interdependent properties. aiXamine orchestrates 46 tests across nine services through an automated red-teaming pipeline, producing hierarchical risk profiles, from prompt-level diagnostics to cross-service trade-off analytics, that enable reproducible comparison of proprietary and open-weight systems under identical conditions. Applying aiXamine to over 120 LLMs through more than 5,000 test runs, we conduct the largest joint safety, security, and privacy study to date and uncover three cross-dim

---

### [57] The Metanym Game: An LLM Benchmark Without Ground Truth That Rises With the Models It Measures

**链接**: https://arxiv.org/abs/2606.21008
**作者**: David Nordfors
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] Certified Multi-Turn Robustness for LLM Safety via Compositional Bounds and Safety Persistence

**链接**: https://arxiv.org/abs/2608.20820
**作者**: Yang Liu, Bin Chong, Wenkai Yang, Shuai Zhang, Yancheng Chen, Feiyu Han 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are vulnerable to multi-turn jailbreak attacks that progressively manipulate conversation context. Existing certified robustness methods are limited to single-turn inputs; naive multi-turn composition yields bounds that degrade exponentially in the number of turns. We introduce Multi-Turn Certified Robustness (MTCR), a framework that models conversational safety via State-Adversarial MDPs and defines $k$-turn certified robustness as the worst-case safety probability across $k$ adversarial turns. MTCR comprises: (i) compositional certification via embedding-space mode decomposition, yielding tighter certified lower bounds than naive multiplication; (ii) $(\alpha,\beta)$-safety persistence, improving the degradation rate from $\underline{p}^{k}$ to $\beta^k$ (with $\beta > \underline{p}$) and yielding interpretable horizon estimates; (iii) matching information-theoretic upper bounds establishing tightness; and (iv) a unified algorithm combining these results.

---

### [59] Beyond Raw Transcripts: Structured Persona Extraction for LLM-Based Digital Twins

**链接**: https://arxiv.org/abs/2608.20344
**作者**: Iris Ye, Tianze Deng, Ozan Candogan
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based "digital twins" aim to simulate how an individual would behavein new environments or respond to novel questions, given some representation of that individual's prior responses. A common approach constructs this representation from survey transcripts or summaries responses. Prior work shows that compressing long transcripts into shorter LLM-generated summaries does not significantly reduce predictive accuracy, suggesting that information volume is not the primary bottleneck. In this work, we argue that the key limitation is instead structural:how persona information is organized before being provided to thesimulator model. We study this by comparing unstructured summaries with structured persona representations. First, we introduce a hand-craftedschema (BDE: Background, Decision procedure, Evaluation), grounded in consumer-behavior theory, and show that it improves predictive accuracy over raw transcripts by +1.91 percentage points on a homogeneous benchmark (Twin-2K-500), wit

---

### [60] Knowing but Not Saying: Preventing Factual Access Failures in LLM SFT via Recall-Anchored Distillation

**链接**: https://arxiv.org/abs/2608.20794
**作者**: Haodong Chen, Yadong Wang, Shengtao Wen, Dong Liang, Xiang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Supervised fine-tuning (SFT) can degrade factual behavior outside the target domain. This degradation is often described as catastrophic forgetting, yet open-ended factual failures do not necessarily imply that the underlying facts have been erased. In this work, we identify a more specific phenomenon, factual access failure: after domain SFT, models can still recognize or rank the correct answer under constrained evaluation, while failing to produce it in closed-book generation. Through benchmark-level comparisons, same-fact multiple-choice and generation probes, and failure-mode analysis, we show that SFT-induced factual degradation reflects both genuine wrong-answer generations and expression-level failures such as verbosity, formatting mismatch, and exact-match artifacts. To address this problem, we introduce Recall-Anchored Distillation (RAD), a base-anchored self-distillation objective that preserves out-of-distribution generation behavior by aligning the adapted model with the o

---

### [61] Beyond Gold Standards: Epistemic Ensemble of LLM Judges for Formal Mathematical Reasoning

**链接**: https://arxiv.org/abs/2506.10903
**作者**: Lan Zhang, Marco Valentino, Jordan Meadows, Andre Freitas
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] UpgradeBench: A Decision-Centric Benchmark for Upgrading Fine-Tuned LLM Specialists

**链接**: https://arxiv.org/abs/2608.20918
**作者**: Ye Chen, Weining Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizations maintain task-specific adapters for open-weight language models, and each new base-model release forces a migration decision: retain existing specialists, port adapters, refresh from preserved behavior, or retrain. Prior transfer work evaluates isolated model pairs, without studying these choices across real model release sequences. We present UpgradeBench, a decision-driven longitudinal benchmark covering four consecutive Qwen releases, one continuation checkpoint, six tasks, and two model sizes, augmented by OLMo checkpoints with known training lineage. The benchmark disentangles three core questions: whether a new checkpoint improves fixed-recipe retrained specialist performance, whether specialization assets transfer across versions, and what recovery resources are usable. We observe upgrade gains differ across task-scale-release episodes: some retrained baselines improve while others stay within training noise, with durability ranging from under one release interval 

---

### [63] Free-Text Evaluation of LLMs for 5G Domain Knowledge and Fault Analysis using LLM-as-Judge

**链接**: https://arxiv.org/abs/2608.21021
**作者**: Rishiraj Sengupta, Sotiris Chatzimiltis, Mohammad Shojafar, Xiatian Zhu
**来源**: cs.CL cs.AI cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world fault analysis in 5G and emerging 6G networks demands domain expertise to analyze free-text diagnostics, including root-cause explanations and recommended actions. LLMs have emerged as a promising approach to automating this, yet whether lightweight, edge-deployable models are capable of performing in-depth free-text diagnostics remains an open question. While existing benchmarks rely on restrictive MCQs with fixed answer keys, this paper evaluates 5G domain understanding and fault analysis in a free-text generation format. Transitioning to this paradigm requires evaluating lightweight, edge-deployable AI models on open-ended diagnostic reasoning, alongside a dependable framework to validate these text outputs at scale. To address this we evaluate three lightweight LLMs, Claude-Haiku-4.5, GPT-5.4-Mini, and Gemini-3.1-Flash-Lite, on free-text 5G domain knowledge and fault-analysis tasks across three benchmarks, TeleQNA ORAN FT, 5G-Faults FT, and TeleInter FT. Three independen

---

### [64] Using Human-LLM Disagreement to Improve Checklist-Based Quality Appraisal

**链接**: https://arxiv.org/abs/2608.20385
**作者**: Timo van der Kuil (1), Bruno Messina Coimbra (1), Mirjam van Zuiden (2), Robert A. Bagheri (1), Rens van de Schoot (1), Klaas Dieleman (1) 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematic reviews rely on quality appraisal of included studies, a process that is time-consuming and sensitive to ambiguity in checklist criteria. Although large language models (LLMs) offer opportunities to support these tasks, appraisal checklists are typically treated as fixed inputs, and it remains unclear how their design affects agreement with expert judgments. Therefore, we investigate (1) whether LLMs can approximate human judgments in checklist-based appraisal and (2) whether patterns of human-LLM disagreement can be used to identify and improve ambiguous checklist items. Using the Guidelines for Reporting on Latent Trajectory Studies (GRoLTS) checklist, we compare LLM-generated assessments with expert annotations across three research topics and two checklist versions. Agreement is assessed using item-level accuracy, chance-corrected agreement, and preservation of study-level rank ordering. We find that performance varies substantially across checklist items, with ambiguous

---

### [65] Can We Trust AI Agents? A Case Study of an LLM-Based Multi-Agent System for Ethical AI

**链接**: https://arxiv.org/abs/2411.08881
**作者**: Jos\'e Antonio Siqueira de Cerqueira, Mamia Agbese, Rebekah Rousi, Nannan Xi, Juho Hamari, and Pekka Abrahamsson
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Rethinking LLM Verification: Evidence Structure, Uncertainty, and Selective Refinement

**链接**: https://arxiv.org/abs/2608.10725
**作者**: Uma Ranjan and Kunal Tilaganji and Aditya Koul and Anurag Mahipal and Dashpreet Singh and Hriday Rana and Manan Jain and Sidharth Gupta and Ajo Babu George and Vineeth Balasubramanian and Nagarajan Natarajan and Amit Sharma
**来源**: cs.CV cs.SC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Don't Solve, Just Compare: Tiny Advisors for Runtime Intervention in LLM Agents

**链接**: https://arxiv.org/abs/2608.21027
**作者**: Yanze Jiang, Mingxuan Li, Yuhao Wang, Shengfang Zhai, Jiaheng Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are emerging as an important paradigm for real-world tasks that require reasoning, tool use, and sequential decision-making. As these agents operate over longer horizons, runtime intervention offers a way to improve reliability without retraining the underlying actor. Failure detection alone is insufficient. Effective intervention must also provide a useful direction for recovery. Existing approaches often rely on an expert solver or a critic that generates task-specific corrections, incurring either the cost of another capable solver or the capacity demands of a task-capable critic. We introduce Comparison-Only Tiny Advisor (COTA), a comparison-only framework for constructive runtime intervention. In COTA, a tiny comparator judges whether sampled alternatives lead to better continuations than the actor's proposal, and repeated comparisons determine when intervention is warranted. We train the comparator using pairwise supervision constructed from same-prefix counterfactual 

---

### [68] GRASP: Gated Regression-Aware Skill Proposer for Self-Improving LLM Agents

**链接**: https://arxiv.org/abs/2605.29668
**作者**: Johannes Moll, Jean-Philippe Corbeil, Jiazhen Pan, Martin Hadamitzky, Daniel Rueckert, Lisa Adams 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] SCOPE: A Generative Approach for LLM Prompt Compression

**链接**: https://arxiv.org/abs/2508.15813
**作者**: Tinghui Zhang, Yifan Wang, Daisy Zhe Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] Beyond End-to-End Success: Diagnosing Failures in Long-Horizon Security LLM Agents

**链接**: https://arxiv.org/abs/2608.20563
**作者**: Wei Shao, Chongzhou Fang, Zuxiong Tan, Zequan Liang, Setareh Rafatirad, Avesta Sasan 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon security LLM agents must carry information and decisions across many dependent interactions, where later actions often depend on services, state, or access discovered much earlier. This makes final task success difficult to interpret: an agent may fail before it ever reaches the point where the capability of interest can be exercised. We present a diagnostic methodology that instruments security tasks with checkpoints, separates failures before and after capability exposure, and uses controlled interventions to test suspected upstream bottlenecks. We evaluate the methodology across four task families involving delayed reuse of discovered information, reuse of observed state, recovery from failed strategies, and decision making after uncertain outcomes. On observed state reuse, checkpoint analysis shows that many Gemini 2.5 Flash failures occur before the model observes the state it is later expected to reuse. In a pre-specified 92-seed study, targeted protocol-disambiguati

---

### [71] Disentangling Threads: Exploring the Potential of LLM-Supported Discussion Forum Analysis for Community Insight

**链接**: https://arxiv.org/abs/2608.20591
**作者**: Tony W. Li, Zhiqing Wang, Thanh-Nha Tran, Yu-Chun Grace Yen, Steven P. Dow
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online discussion forums enable people from diverse backgrounds to share ideas, feedback, and perspectives. These organic discussions can help researchers understand communities' collective viewpoints, but insights are often difficult to uncover given their freeform reply structure. Large language models (LLMs) support qualitative text analysis but can misalign with researchers' analytical intent and miss key insights. To inform design considerations for forum sensemaking tools, we manually analyzed a forum discussion, synthesized an exploratory analysis framework from relevant literature, built a design probe, and interviewed 21 researchers to uncover perceived opportunities and barriers with LLM representations of collective discussions. We provide recommendations for community sensemaking tools to support flexible analytical goals grounded in raw user data and enable follow-up research processes, while balancing anonymous free expression with the desire for contextual information on

---

### [72] Natural-Language-Guided Generator-Agnostic Shortlisting for Protein Binder Design

**链接**: https://arxiv.org/abs/2608.20755
**作者**: Gyubok Lee, Kiwoong Yoo, Jimin Seo, Kyunghoon Hur, Edward Choi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern de novo design workflows generate many candidate protein binders, but wet-lab validation capacity remains limited, making shortlisting a major bottleneck. We study whether LLMs can generate multi-metric ranking policies from precomputed structural-confidence and interface-quality proxy scores. Rather than proposing a new protein binder design pipeline, we focus on post-generation binder shortlisting: selecting the final top-K candidates from already generated binder pools using a shared panel of precomputed proxy scores. On the 10-target held-out split, averaging performance over five sampled global iterative gpt-4o policies reaches 0.589 Recall@10, modestly improving over the strongest single-feature fixed baseline, Protenix binder ipTM, which reaches 0.571 Recall@10. On the 3-target held-out subset comprising Nipah, RBX1, and TREM2, target-conditioned iterative gpt-5.4 policies reach the strongest LLM performance, with 0.519 Recall@10 and 0.583 NDCG@10. These results suggest t

---

### [73] Jacobian-guided Noise Injection for Quantization Robustness in Large Language Models

**链接**: https://arxiv.org/abs/2608.20988
**作者**: Deepanshu Pandey, Arnav Chavan, Nahush Lele, Sankalp Dayal, Deepak Gupta
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization of Large Language Models (LLMs) is often hindered by the sensitivity of the self-attention mechanism to discretization errors. We identify the softmax operator as a bottleneck for quantization stability due to its sensitivity to outliers and state-dependent Jacobian. We theoretically establish that suppressing the norm of this Jacobian helps in bounding quantization-induced performance degradation. Based on this, we propose Jacobian-Guided Noise Injection, a training strategy that injects zero-mean Gaussian noise into pre-attention logits, with variance derived directly from the Jacobian Frobenius norm. Unlike prior approaches that rely on heuristic or penalise jacobian directly, our method provides a way to identify the optimal noise variance based on the local attention sensitivity. We evaluate the method on SOTA LLM architectures, where it demonstrates improved robustness over popular PTQ methods. Empirical analysis reveals that the proposed method gives up to +37% rela

---

### [74] A Survey on Foundations and Frontiers of Multimodal Agentic Frameworks: Techniques and Applications

**链接**: https://arxiv.org/abs/2608.20379
**作者**: Neel Mokaria, Rishie Raj, Dheeraj Baiju, Xiaoqian Shen, Shraman Pramanick, Kevin Qinghong Lin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in large language models (LLMs) have fueled a wave of research into agency: the ability to reason, plan, and act. This effort has produced agentic frameworks that orchestrate perception, memory, and decision-making around powerful LLM backbones. With the advent of large multimodal models (LMMs), these systems can process and integrate diverse modalities, including images, audio, and video, thereby improving their real-world applicability. Yet, while surveys of LLM-based agents exist, the role of multimodality in shaping agency has not been systematically examined in recent years. This survey fills the gap by analyzing the impact of multimodality across the core functional modules of the agentic framework: perception, reasoning, planning, memory, and action. Using this lens, we trace the evolution from text-centric agents to multimodal frameworks, examine how modalities are integrated through delegated, late-fusion, and early-fusion architectures, and assess the emergence of ag

---

### [75] Terminal Agents: A Survey of AI Agents in Command-Line Environments

**链接**: https://arxiv.org/abs/2608.20485
**作者**: Yi Bin, Xiaoyang Yuan, Haoxi Zeng, Wencheng Ye, Wenqi Shao, Chen Qian 等 (10 人)
**来源**: cs.AI cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly act through terminals, yet existing surveys disperse terminal-mediated behavior across software engineering, tool use, and computer-use research. We regard terminal agents as systems whose dominant progress-bearing action--observation loop is mediated by terminal command execution, textual feedback, and stateful environment interaction. Using terminal-mediated execution as an organizing lens, this survey establishes workload-level boundaries and connects system architecture, competence acquisition, and evaluation through a seven-dimensional terminal competence profile. Our synthesis shows that realized behavior is jointly shaped by the model, interface, harness, runtime, and environment. Executable trajectories ground learning in action consequences, verification, and recovery, whereas prevailing evaluations emphasize final outcomes and expose process quality, recovery, and governance unevenly. Bounded fixed-condition diagnostics illustrate two 

---

### [76] Towards Traffic Modelling of Multi-Agent Systems: The Role of Coordination Topology

**链接**: https://arxiv.org/abs/2608.20494
**作者**: Davide Lamagna, Albert Cabellos, Alberto Rodriguez-Natal, G\'abor R\'etv\'ari, Berta Serracanta
**来源**: cs.NI cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are an emerging networked workload whose rapid deployment raises questions about the traffic patterns they generate. Compared to conventional applications, these systems generate requests internally: a single user task can induce a structured sequence of model calls whose timing is governed by coordination logic rather than by user arrival rate. It is not clear whether classical traffic models, designed for human-driven workloads, apply to this setting. We present an empirical characterisation of LLM-call interarrival time distributions across sequential, star, and full-mesh agentic coordination topologies, using a multi-layer measurement framework over 500 repeated runs per topology. We find that topology fundamentally shapes the arrival process of requests to the LLM backend: fan-out coordination introduces a structural bimodality absent in sequential execution, and the reasoningphase component is best described by a log-normal distribution, with the Poisson e

---

### [77] Representation Affects Retrieval: A Case Study of Skill Discovery and Routing in a Multimodal Agent Harness

**链接**: https://arxiv.org/abs/2608.20389
**作者**: Kevin Dela Rosa
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A production agent harness must discover and rank, from a growing library of skills, the one most appropriate for a user's task. At small scale this selection happens in context: the LLM planner chooses among skill representations exposed in its system prompt, without an explicit embedding-based retrieval step. We treat this in-context selection as the small-N counterpart to embedding-based skill retrieval at scale, and present a case study of how Tinycloud, a production multimodal video agent harness, represents its skills for the planner. The harness ships skills under two recurring representations: tool-skills that wrap a single external API or system tool and serve as primitive vocabulary, and workflow-skills that orchestrate tool-skill calls plus a template render to produce one named deliverable. The harness exposes them via two surfaces in the system prompt: an inlined-body surface (full instructions, scripts, templates) for autoloaded skills, and a one-line listing for on-deman

---

### [78] Structure for Reading, Prose for Writing: Asymmetric Structural Conditioning in Multi-Agent Document Authoring

**链接**: https://arxiv.org/abs/2608.20786
**作者**: Cheng Yu, Nikhil Mathew, Zhengjie Wang
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent pipelines that author formal documents must both read a requester's forms and write against them. We report a deployed tender-response system, running an open-weights model under sovereignty constraints, and evaluate it against human-written bids the same organisation actually submitted. On a blind comparison where the system had no worked example available, an LLM judge rated its answers at least as good as the human-submitted answer on $40$ of $55$ ground-truth sections, better on $4$, missing on none, and flagged one unsupported claim in total. Classifying every gap the judge identified shows that $68\%$ were content absent from the system's own sources -- knowledge the human author held and the pipeline was never given -- so only $6$ of the $15$ adverse verdicts involve a deficiency the system could have avoided. A divergence from ground truth is more often an information-availability result than a writing-quality one, and evaluations that do not separate the two unders

---

### [79] EnSI-RAG: Entity-Structure-Indexed Retrieval-Augmented Generation for Long-Document Question Answering

**链接**: https://arxiv.org/abs/2608.21252
**作者**: Xuanyu Meng, Jiashuo Sun, Jash Rajesh Parekh, Jiawei Han
**来源**: cs.CL cs.AI cs.DB cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Question answering (QA) over long, connected documents remains challenging because relevant evidence may span multiple entities and their relationships. Existing retrieval-augmented generation (RAG) methods typically index documents as raw chunks and retrieve them through embedding similarity. Their performance degrades when chunk boundaries separate entities from supporting evidence or when a question requires multi-hop reasoning across the corpus. We propose EnSI-RAG (Entity-Structure-Indexed Retrieval-Augmented Generation), a framework that constructs a query-independent, entity-centered index. Each record (e, t, k, v) represents an entity e, its type t, a semantic category k in {property, relation, aspect}, and a value v, while retaining links to the original source passages. At query time, these records serve as retrieval handles, and an LLM synthesizes the retrieved passages into the final answer. This design separates evidence localization from answer synthesis while preserving 

---

### [80] A Neurosymbolic Approach for Constructing Planning Domain Models from Clinical Narratives

**链接**: https://arxiv.org/abs/2608.21186
**作者**: Ranveer Singh, Saurabh Mathur, Michael Skinner, Prasad Tadepalli, Kristian Kersting, Sriraam Natarajan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Surgical procedures such as laparoscopic appendectomy are complex, high-stakes processes, yet formalizing their workflows for decision support remains a significant challenge. Inducing probabilistic planning domain models in this setting is particularly difficult due to the lack of structured event data and the prevalence of implicit actions in clinical narratives, which neither empirical symbolic methods nor Large Language Models (LLMs) can adequately address on their own. We introduce NSPIN, a neurosymbolic framework for inducing probabilistic planning domain models from unstructured clinical narratives. Our method extracts and imputes structured event sequences from raw text using a pretrained LLM, then induces a PPDDL model and refines its preconditions with LLM-proposed revisions, guided by empirical validation. We evaluate the approach on 2,660 laparoscopic appendectomy notes written by 9 surgeons. NSPIN yields models that generalize to unseen notes, and expert clinical review in

---

### [81] Structured but Fragile: On the Limits of LLMs in Cybersecurity Decision-Making

**链接**: https://arxiv.org/abs/2608.20966
**作者**: Pasquale Malacaria and Yunxiao Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in cybersecurity workflows, yet it remains unclear whether they can perform structured security reasoning or merely rely on superficial cues and prior knowledge. We study this question in the context of defence selection over attack graphs derived from real-world threat scenarios, including ransomware, supply-chain compromise, cloud abuse, Kubernetes attacks, POS malware, and ICS/OT intrusion. Given a budget constraint, LLMs must select security controls to minimise attacker success. We compare their strategies against each other and against a game-theoretic optimization baseline used as a normative reference for structured reasoning. Our results show that LLMs exhibit conditional competence. When explicit attack-graph structure is provided, they often produce coherent strategies close to the optimization baseline. However, their capabilities are fragile. LLM behaviour becomes increasingly fragile with graph complexity and is highly se

---

### [82] From Search Agents to Dissemination Interfaces: Understanding Human Trust in Health Information from Conversational Search

**链接**: https://arxiv.org/abs/2608.21177
**作者**: Xin Sun, Rongjun Ma, Xiaochang Zhao, Janne Lindqvist, Jan de Wit, Zhuying Li 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) deployed through Conversational User Interfaces (CUIs) are transforming health information-seeking by offering immediate, interactive experiences compared to traditional search engines like Google. However, how trust is influenced by both the types of search agents and the interface used to disseminate the information remains underexplored. This research integrates two mixed-methods studies (lab sessions and interviews) to comprehensively explore trust perceptions in health information across different search agents and dissemination interfaces. In Study 1 (N=21), we investigated trust in health information sourced from ChatGPT and Google across three types of health-related search tasks. Results showed significantly higher trust in health information from ChatGPT, highlighting the promise of LLM-powered conversational search. Building on this, Study 2 (N=20) extended the investigation to explore how the dissemination interface influences trust in LLM-sourc

---

### [83] When Vocabulary Comprehension Fails Clinical Reasoning: Evaluating Therapy Bots' Safety Risks for Generation Alpha

**链接**: https://arxiv.org/abs/2608.20345
**作者**: Manisha Mehta and Virendra Mehta
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational AI systems have become informal mental health support resources for Generation Alpha (Gen Alpha, born 2010-2024), with 13.1% of U.S. adolescents (5.4 million) using generative AI for mental health advice. While these systems, from therapy apps to general chatbots, rely on large language models trained on extensive psychological literature, their safety for youth communication patterns characterized by hyperbolic language, ironic positivity, rapid semantic drift, and contextual polysemy remains unvalidated. Following multiple adolescent deaths linked to AI chatbot interactions, systematic evaluation is critical. We present two benchmarks: (1) 64 Gen Alpha mental health expressions validated by native speakers (ICC=0.72) and clinicians (kappa=0.78); (2) 75 multi-turn conversations (780 turns) with paired Standard/Gen Alpha versions. Across evaluations of LLM architectures underlying therapy apps and general chatbots - Claude, GPT-4o, Llama-3.1 - models understand 76-82% of

---

### [84] Temporal Validity on Real Software Histories: Eliminating Stale-Fact Errors in Code-Assistant Memory over GitHub Fixes

**链接**: https://arxiv.org/abs/2608.20685
**作者**: Neeraj Yadav
**来源**: cs.SE cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) has no model of time: when a fact changes across a coding session - a function is renamed, an endpoint moves, a dependency is bumped - RAG retrieves both the old and new value with near-identical similarity and cannot tell which is current, so it serves the superseded value. Paper 1 showed, on synthetic single-value benchmarks, that a deterministic (subject, relation, object) supersession memory eliminates this failure. Here we validate it end-to-end on real software history. From 707 real GitHub issues (SWE-bench Lite + Verified) we extract 130 clean atomic state transitions, a fix that changes one identifiable value from a pre-fix to a post-fix form, and render each marker-free (the stale and current statements differ only in the value). On this set, MemStrata reaches 0.91 answer accuracy versus RAG's 0.57-0.59; and, the structural result, when forced to answer RAG serves the superseded value 36-38% of the time (an LLM reranker does not help) whil

---

### [85] Clarify-Then-Search: A Clarification Benchmark for Deep Search with End-to-End Nugget Restoration

**链接**: https://arxiv.org/abs/2608.20357
**作者**: Deqiang Huang, Jingbo Zhou, Xinjiang Lu, Tong Xu, Hua Wu, Enhong Chen
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep search is brittle on underspecified user queries: missing constraints such as time, location, scope, or definitions can lead to retrieval drift and incomplete answers. We introduce Clarify-Then-Search, a benchmark for evaluating whether LLM-generated clarification questions improve downstream deep-search utility. Built on real-world query data from the Baidu search engine, the benchmark contains 518 curated instances, each with an intent query and a corresponding underspecified query. For each intent query, we run WebDancer once to archive evidence and construct a static golden reference as weighted, evidence-grounded nuggets with traceable source identifiers. At evaluation time, a Clarifier asks k in {1, 2, 3} questions; a closed-book User Answerer replies only with information explicitly stated in the intent query, otherwise returning unknown; and a closed-book Rewriter produces a rewritten query using only the underspecified query and the elicited question-answer pairs. WebDanc

---

### [86] AsmEvo: Agentic Assembly-Level Optimization of AMD GPU Kernels with Functional Equivalence Verification

**链接**: https://arxiv.org/abs/2608.20711
**作者**: Ji Liu, Puyuan Yang, Rongzhang Zheng, Fan Wang, Jinglin Wang, Muhammad A. Awad 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance ML systems increasingly rely on GPU kernels whose editable source is unavailable, generated, or too distant from final machine code to expose remaining optimizations. Existing LLM kernel optimizers and autotuners mainly operate on CUDA, Triton, HIP, or tensor-program source and validate against reference implementations. We study a stricter setting: optimizing an already compiled AMDGPU code object, where the deployed binary is the only behavioral oracle. We present AsmEvo, an agentic assembly-level optimizer for AMD GPU kernels. Given an AMDGPU code object K0, AsmEvo reconstructs a reassemblable representation, proposes low-level edits with a long-horizon agent, rebuilds an ABI-preserving optimized object, and accepts candidates only after differential verification against K0 under identical launches. AsmEvo combines code-object recovery, metadata-aware rebuilding, profiling-guided hot-window editing, correctness-gated timing, and conservative in-place patch fallback.

---

### [87] Evaluation-as-Search: Adaptive Discovery of Grounding Failures in Meeting Assistants

**链接**: https://arxiv.org/abs/2608.20392
**作者**: Sami Khairy, Yasaman Hosseinkashi, Vishak Gopal, Ross Cutler
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered meeting assistants are deployed at scale, yet systematic evaluation of their grounding fidelity remains limited to static benchmarks that miss failure modes tied to specific discourse structures or reasoning demands. We propose Evaluation-as-Search (EaS), a feedback-driven methodology that frames quality evaluation as an adaptive search over the space of natural questions a meeting participant might ask. Rather than sampling uniformly, EaS learns from evaluator feedback across iterations to concentrate probing effort on cognitive demands where failures are most likely, guided by a UCB-scored coverage map and blind multi-dimensional quality evaluation. Using EaS, we construct MeetingProbe, a benchmark of over $3{,}000$ annotated question--answer pairs spanning 20 transcripts from three meeting genres and three LLM assistants. In ablations, adaptive search surfaces $2.5\times$ more failures than random probing ($7.1\%$ vs. $2.9\%$ finding rate), with the strategic planner con

---

### [88] JuryProbe: An Empirical Consensus-Risk Diagnostic for Routing Reference-Free Factuality Judge Panels to Grounded Verification

**链接**: https://arxiv.org/abs/2608.20607
**作者**: Tianxin Zhou, Ruixi Lin
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Panels of inexpensive LLM judges increasingly make accept-or-escalate decisions. In factuality settings, accepting a claim because several reference-free judges agree can create a hidden risk: agreement may reflect shared false-negative blind spots rather than independent evidence. We introduce JuryProbe, an empirical consensus-risk diagnostic for reference-free factuality judge panels, paired with a calibration-based routing policy. JuryProbe estimates consensus risk from a labeled calibration probe using false-negative-only (FN-only) judge correlation and false-consensus lift; when flagged high-risk, reference-free majority accepts are routed to the same judges with trusted references. On audited FEVER corruptions, reference-free panels show correlated false negatives (FN-only correlations 0.402 and 0.368; lifts 3.13x and 18.13x), while unanimous false consensus drops to zero under a trusted-reference best-case diagnostic on both minimal-pair and non-minimal-pair evidence. In flagged

---

### [89] A Factorial Ablation of a Speech-to-SFT Pipeline: Differential Effects on Data Quality and Downstream Transfer

**链接**: https://arxiv.org/abs/2608.20394
**作者**: Wonsup Shin, Jingu Kim
**来源**: cs.SD cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industry pipelines that turn speech into supervised fine-tuning (SFT) data via multi-stage refinement are increasingly adopted but, to our knowledge, have not been publicly ablated stage-by-stage, leaving each stage's marginal value unknown. We design a production-ready speech-to-SFT pipeline in which transcript refinement (Phase 0) and SFT data quality refinement (Phase 2) are independently toggleable, yielding a 2x2 factorial design. For each condition, we generate QA-form SFT data from Korean medical and finance conference recordings and fine-tune 9 models (5 LLM families, 2.4B-70B); we evaluate with four cross-provider LLM judges, a blind six-expert human evaluation, and 3 downstream MCQA benchmarks. Our central finding: under a fixed, standard SFT recipe, improvements in QA data quality do not transfer uniformly into downstream MCQA gains. 4-judge quality rises consistently, yet the cross-model mean MCQA gain is not significant; positive transfer concentrates on family-domain alig

---

### [90] ARGUS: Theory-of-Mind Guided Argument Generation with Strategy-Aware Planning and Knowledge Grounding

**链接**: https://arxiv.org/abs/2608.20405
**作者**: Zhe Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persuasive argument generation requires modeling audience beliefs, rhetorical strategies, and factual grounding. Despite recent advancements, existing methods remain largely audience-agnostic and fail to integrate strategy selection to improve persuasiveness. To bridge this gap, we propose Argus, an agent-based framework that operationalizes classical rhetoric for persuasive writing. At its core, a Theory-of-Mind (ToM) Reasoner constructs an explicit dual mental model of the audience's beliefs and values to guide downstream decisions. This representation conditions a component-aware planner that decomposes the argument into subtopics, assigns fine-grained rhetorical functions (logos, pathos, ethos, kairos), and triggers strategy-guided evidence retrieval at planning time. Finally, a refinement module iteratively targets and resolves multi-dimensional weaknesses without quality regression. We evaluate Argus across three diverse benchmarks using both automated pairwise Elo and LLM-as-jud

---

### [91] Asymmetric Capacity Allocation in Self-Refinement Pipelines

**链接**: https://arxiv.org/abs/2608.21345
**作者**: Zhuoyi Yang, Ian G. Harris, Salar Hashemitaheri, Cassie Huang, Yuangang Li, Hyunwoo Oh 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-refinement, typically structured as generation, critique, and revision, is a widely adopted paradigm for improving LLM generation and serves as a core mechanism in many LLM agents. While the three stages involve different cognitive demands, most existing approaches conveniently treat the model size as an implementation detail rather than a subject of study, which may lead to a waste of resources. Little work has systematically examined how model size affects each stage or whether effective self-refinement requires equally capable models for generation, critique, and revision. We present the first stage-wise model size study of the self-refinement pipeline on 5 benchmarks from different domains using 6 model sizes of Qwen3 and 4 model sizes of Gemma 3. We conclude that larger generators and refiners generally improve the pipeline, whereas an undersized refiner can even harm performance. Second, performance is highly insensitive to the size of the critic, although including even a s

---

### [92] Hadith computational science in the age of large language models: a critical narrative review

**链接**: https://arxiv.org/abs/2608.20364
**作者**: Md. Ashraful Haque (1), Riasat Islam (1 and 2) ((1) Greentech Apps Foundation, United Kingdom, (2) Queen Mary University of London, London, United Kingdom)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We examine how hadith computational science is being reshaped by transformer models, retrieval-grounded pipelines, and large language models (LLMs). Recent reviews document growth in the literature, but they do not yet provide a critical account of which advances are methodologically robust, which remain benchmark-bound, and which unresolved problems still limit scholarly use. We address this gap through a critical narrative review that combines critique of existing reviews, paper-level appraisal of representative original studies, and synthesis of Islamic scholar and domain-expert perspectives on authenticity, authority, and responsible use. We find uneven progress. Data resources have expanded, segmentation tasks have matured, narrator and source-verification problems are better formalized, and LLM-assisted workflows now support corpus-scale enrichment, multilingual access, and grounded evaluation. At the same time, progress remains constrained by narrow corpora, weak benchmark compa

---

### [93] Trilingual Topic Modeling of Sri Lankan Parliamentary Debates

**链接**: https://arxiv.org/abs/2608.20365
**作者**: Himath Dhanapala, Haren Daishika, Himandhi Kuruppu, Sithija Seneviratne, Ashini Kavindya, Patalee Narasinghe 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sri Lankan parliamentary debates (Hansards) constitute a trilingual corpus of speeches in Sinhala, Tamil, and English, including code-mixed content, yet remain inaccessible to standard NLP pipelines due to layout-complex PDFs, multilingual scripts, and agglutinative morphology. We present an end-to-end framework that addresses these challenges through LLM-based text extraction followed by a multilingual embedding and density-based clustering pipeline for topic modeling. A hybrid semantic-lexical extension, BiTopic, is further explored to improve interpretability and recover speeches otherwise discarded as noise. Applied to 19,553 speeches spanning 2017-2026, the pipeline recovers 30 macro-topics achieving a cluster purity (BCP) of 0.673, whose temporal trajectories align unsupervised with major national events including the 2019 Easter Sunday attacks and the 2022 economic crisis. Traditional LDA fails on this corpus due to cross-lingual fragmentation, whereas the proposed approach succ

---

### [94] Consilience: Conformally Calibrated Communication Control for Hidden-Profile Multi-Agent Reasoning

**链接**: https://arxiv.org/abs/2608.20564
**作者**: Abhijith Babu, Ramneet Kaur, Vishal Pramanik, Olivera Kotevska, Nathaniel D. Bastian, Susmit Jha 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems can improve reasoning by pooling diverse perspectives, but their effectiveness depends on coordinating communication, particularly in hidden-profile settings where each agent holds only part of the evidence required for a correct decision. Existing protocols, including fixed schedules, round-robin exchange, and unstructured debate, provide no guarantee that a conversational action is appropriate. We propose Consilience, an inference-time orchestration framework that both steers and certifies multi-agent communication under distributed private information. At each turn, Consilience summarizes the discussion using a compact state capturing uncertainty, disagreement, evidence gain, redundancy, and premature consensus, then selects both a communication intervention (challenge, clarify, seek evidence, or route) and an appropriate speaker. Its central contribution is a round-wise conformal calibration procedure that provides a distribution-free, finite-sample guarante

---

### [95] $Z^2$-ACT: End-to-End Verifiable Agentic Intent Control for Open 6G RAN

**链接**: https://arxiv.org/abs/2608.21049
**作者**: Sunder Ali Khowaja, Kapal Dev, George C. Alexandropoulos
**来源**: cs.CR cs.AI cs.NI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the progression in open and disaggregated 6G radio access networks, it is expected that the system will be able to host multi-vendors. In order to host multi-vendors, it is essential that AI-assisted control loops remain safe, verifiable, and auditable under concurrent operator intents and untrusted model inputs. The existing studies address the agentic coordination, formal intent constraints, zero-trust prompt verification and cryptographic accountability in isolation, which leaves pre-realization safety, continuous semantic verification and cross-domain audit incomplete when used individually. In this regard, we propose zero-knowledge auditable control and zero-trust verifiable agentic intent architecture ($Z^2$-ACT), which integrates the aforementioned four primitives across the non-real-time and near-real-time RICs. We encode the typed Intent Contracts as operator goals while the large language model inputs are only admitted after a practical adversarial intent check. The skil

---

### [96] Enhancing LLMs in Predictive Political QA with Semi-Structured Data

**链接**: https://arxiv.org/abs/2608.21218
**作者**: Yinan Liu, Zihan Zhou, Zichun Jin, Xinyu Wang, Bin Wang, Xiaochun Yang
**来源**: cs.AI cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predictive political question answering (QA), such as predicting how a political actor will vote, goes beyond factual lookup. External political resources offer rich historical evidence, but rarely contain the answer itself. Existing LLM augmentation methods, including actor-profile-based simulation and knowledge graph evidence injection, improve political reasoning but largely treat external resources as knowledge-based evidence, leaving prediction-relevant signals under-modeled. We identify two complementary signals for predictive political QA: actor stances that capture issue-specific preferences, and high-order structure signals that capture indirect dependencies among political actors. We propose PSL, a dual-view framework that converts semi-structured political records into inference-oriented evidence for LLMs. PSL extracts stance signals from question-relevant actor records in a semantic view, and learns structure-aware actor representations from an actor interaction graph in a 

---

### [97] Beyond the Traceback: Using LLMs for Adaptive Explanations of Programming Errors

**链接**: https://arxiv.org/abs/2608.20896
**作者**: Alexandru-Radu Moraru, Shreyan Biswas, Ujwal Gadiraju
**来源**: cs.SE cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programming error messages are critical for software development, yet they remain difficult for novice programmers to interpret. While Large Language Models (LLMs) can rewrite these errors into clearer explanations, it remains unclear whether increased readability improves objective debugging performance or how explanation styles should align with programmer skill. We present a multi-stage crowdsourced study N=103 evaluating skill-targeted, LLM-generated Python error messages. Using a custom proficiency assessment, we categorized participants by skill level and tested standard interpreter messages against two LLM-generated styles: pragmatic (action-oriented) and contingent (scaffolded explanations). We measured both objective debugging metrics (fix rate, attempts, time-to-fix) and subjective perceptions (readability, cognitive load, tone). Our results show that while LLM-rewritten messages significantly improved subjective evaluations, with pragmatic messages rated as clearer and less 

---

### [98] When Do LLMs Replace Fine-Tuned NLU? A Decision Framework for Intent Detection in Production Conversational Systems

**链接**: https://arxiv.org/abs/2608.20371
**作者**: Carson Rodrigues, Oysturn Vas
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A common claim is that zero-shot large language models (LLMs) can replace fine-tuned NLU classifiers for intent detection. We test this claim head-to-head and find that the honest answer is: it depends on the intent space. On full ATIS and CLINC150 we compare a fine-tuned RoBERTa, a TF-IDF+logistic-regression baseline, sentence-embedding kNN, and Claude Haiku zero-shot, reporting bootstrap 95% confidence intervals and paired significance tests. When abundant in-domain labels exist, fine-tuned RoBERTa is as good or better and three orders of magnitude cheaper and faster: on ATIS it beats Claude zero-shot by 11.8 points (95.9 vs. 84.1, p<0.001). On the broad 150-intent CLINC150 schema the two are statistically tied (89.1 vs. 88.5, p=0.24): the LLM matches a fully supervised model with no training data. The LLM's advantages appear in three production-relevant regimes: out-of-scope detection (OOS recall 85.6 vs. 58.1 for RoBERTa); robustness to realistic ASR noise via a controlled text-to-

---

### [99] ARQ: Agentic CodeQL Query Refinement for C/C++ Vulnerability Detection

**链接**: https://arxiv.org/abs/2608.20637
**作者**: Chunyi Wang, Yunfei Ke, Junfeng Yang, Yun-Yun Tsai, Penghui Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Static analyzers have been widely adopted for vulnerability detection in C/C++ programs. Query-based static analyzers (e.g., CodeQL) encode vulnerable code patterns in detection queries and match them against source code. However, existing queries still suffer from false positives (FPs, incorrectly flagging benign code as vulnerable) and false negatives (FNs, missing real vulnerabilities). We present ARQ, an agentic framework that automatically refines C/C++ CodeQL queries using execution-grounded evidence from synthesized C/C++ programs. Our key insight is that a synthesized program exposes a query's weakness whenever its execution disagrees with the query's verdict. If the program is genuinely vulnerable but the query stays silent, the query has an FN weakness; if the program is safe but the query fires anyway, it has an FP weakness. ARQ then runs an LLM-based refinement loop that repairs the query using these disagreements as ground truth. Unlike previous query refining methods, ARQ

---

### [100] Six misconceptions about large language models: A minimal model and diagnostic taxonomy

**链接**: https://arxiv.org/abs/2608.20421
**作者**: Zhicheng Lin
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are now embedded in scientific, educational, and governance workflows, with debates centering on their capabilities, mechanisms, and impacts. Yet these debates remain structured by persistent folk theories--intuitive, informal explanatory models that guide attitudes and actions. Deflationary slogans ("just autocomplete," "stochastic parrots," and "average of the internet") and anthropomorphic framings ("emergent agents" and "proto-minds") each capture genuine features of current systems but mistake those features for the whole. This Perspective proposes a minimal working model of LLM-based systems centered on four distinctions: between pretraining and deployed systems; between the learned distribution and particular samples; among parametric, contextual, and external memory; and between task competence and agency. The model is used to diagnose six misconceptions about LLMs: next-token prediction, regression to the mean, training-data regurgitation, model me

---

### [101] Dual-Cache Latent Space Communication between Heterogeneous Language Models

**链接**: https://arxiv.org/abs/2608.20617
**作者**: Jiyao Liu, Qi Zhang, Yaoyi Jia, Ziwen Kan, Song Wang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems split work across models, so answering often requires knowledge that sits in another agent's context: a Sharer has encoded information that a Receiver needs to complete its task. They usually communicate by exchanging text, which puts autoregressive decoding on the critical path and reduces the exchange to a discrete message written without sight of the receiver's state. Recent latent protocols instead translate the sharer's key-value (KV) cache into the receiver's: C2C supports heterogeneous models but requires both to read the same input, while LCF-X removes this shared-context requirement through position-free sharer-cache pooling. Three restrictions remain: LCF-X compresses the sharer alone, supplies the same layer-local summary to every receiver position with no joint cross-layer memory to retrieve from, and assumes matched layer count and KV geometry. We introduce XKV, which lifts all three: learned-query attention pools both caches; self-attention over re

---

### [102] HIERA: Workload-Aware Planning Across Implementation Spaces for GPU Kernel Optimization

**链接**: https://arxiv.org/abs/2608.21157
**作者**: Jinghao Wang, Qiqi Gu, Chenpeng Wu, Jianguo Yao, Haibing Guan and Xijun Li
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-performance GPU kernels underpin modern deep learning and scientific computing. As workloads become increasingly diverse and GPU hardware evolves rapidly, developing efficient methods for automated GPU kernel generation and optimization has become increasingly important. Existing LLM-based methods typically optimize within a fixed implementation space, limiting either optimization flexibility or search efficiency. We propose \textsc{HIERA}, a hierarchical search-space planning framework for GPU kernel optimization. \textsc{HIERA} constructs contract-augmented task specifications, selects an appropriate implementation space across PyTorch operators, CUDA libraries, and custom CUDA kernels, and uses profiling feedback and expert knowledge to guide structured iterative refinement. Experiments on KernelBench across multiple various workload levels and base LLMs show that \textsc{HIERA} delivers stronger overall implementation validity, sample efficiency, and optimization performance t

---

### [103] ASTAR: Automated induction of STAndardized radiology Reporting templates from large-scale clinical free-text corpora

**链接**: https://arxiv.org/abs/2608.20369
**作者**: Xinfeng Zhang, Mingxuan Liu, Yifei Chen, Juncheng Zhu, Kasidit Anmahapong, Yiming Huang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured reporting converts free-text radiology narratives into queryable data keys, facilitating cohort assembly, longitudinal tracking, and training label generation for medical AI. The prevailing paradigm follows a two-stage pipeline: (1) constructing a reporting template, (2) extracting information to populate it. While the extraction stage has benefited from advances in large language models (LLMs), template construction remains a manual bottleneck relying on labor-intensive expert consensus that is static, difficult to scale, and may fail to capture real-world reporting diversity. We address this limitation with \textbf{\texttt{ASTAR}}, an LLM-based framework for Automated induction of STAndardized radiology Reporting templates from large-scale clinical free-text corpora. Extensive experiments on 4,215 fetal brain MRI reports from multiple centers demonstrate that the \textbf{\texttt{ASTAR}}-induced template surpasses two expert-curated templates across template coverage, infor

---

### [104] EditPPT: Faithful Long-Deck Slide Editing via Structured Tool-Using Multi-Agent with Dual-Modal Validators

**链接**: https://arxiv.org/abs/2608.20381
**作者**: Jiheon Kim, Kyudan Jung, Jaegul Choo
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automating slide editing requires simultaneously satisfying modification accuracy, preservation fidelity, and robustness to deck length. Existing LLM-based systems often fail on real-world presentation files because they rely on idealized intermediate representations or open-ended code generation, which are prone to cascading errors in long decks. We introduce EditPPT, a multi-agent framework that reformulates slide editing as a constrained tool-selection problem. By executing localized shape-level operations through the native PowerPoint COM interface, EditPPT narrows the LLM action space while preserving the application-resolved structure of user-authored decks. By separating validation across modalities, our dual-modal validation provides more robust assessment of both instruction fidelity and visual quality. We also present DeckEdit-Bench, a benchmark with 28 human-authored decks, 582 slides, and 183 editing prompts across short, medium, and long deck tiers. Experiments show that E

---

### [105] M3Trans: Scaling MLLM -based Manchu Archival Image to Classical Chinese Machine Translation via Domain Adaptation Fine-tuning

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426029829&hl=zh-CN&sa=X&d=13382980213151453412&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-z9Z1vextDxOOlG4d4yHget&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: X Bi, H Sun, W Qiao, Z Chen, S Li - Expert Systems with Applications, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Accurately translating Manchu archival texts is essential for unlocking the historical records of the Qing dynasty. Although existing methods for Manchu machine translation have made notable progress, this task still faces four major challenges

---

### [106] Teach a Molmo2Fish: Towards interactive fish tracking with natural language guidance

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.18602&hl=zh-CN&sa=X&d=17733362464652437298&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-yPWVWQuhGX3-fGTF1GKRwY&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=5&folt=kw-top
**作者**: K Van Brunt, J Kay, S Beery - arXiv preprint arXiv:2608.18602, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> ], despite significant differences between sonar video and the typical MLLM training set. We also demonstrate the potential to imbue MLLMs … through a multi-turn interaction with a MLLM . 2. We introduce Molmo2Fish, a custom MLLM that is

---

### [107] Projector Is All You Train

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.19726&hl=zh-CN&sa=X&d=3257540871037369927&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-zJ4B83gxLoVGyCK5GjGyv6&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=3&folt=kw-top
**作者**: N Iskandar, S Selvan, S Victoroff - arXiv preprint arXiv:2608.19726, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> ( MLLM ) involves adapting both the language model backbone and the projector between the backbone and a modality-specific encoder. We ask whether fine-tuning the backbone of an MLLM is … This section explains our MLLM architecture and two

---

### [108] Multimodal Visual Reasoning in Asset Pricing: Evidence from Cryptocurrency Technical Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1544612326011918&hl=zh-CN&sa=X&d=2933167313605060438&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-wxCSvnoaZRinf22B6QuQJH&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=2&folt=kw-top
**作者**: M Chen, Y Fang, H Wang - Finance Research Letters, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To further assess whether the MLLM results reflect more than generic image-based prediction, we compare the MLLM strategies with a CNN-based image-classification benchmark. We use an ImageNet-pretrained ResNet-18 and replace the final layer

---

### [109] ID-VTG: Image-Disambiguated Video Temporal Grounding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.20127&hl=zh-CN&sa=X&d=12777623396461308591&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-zVUL-BwtDjuv-8h1VkNJ2s&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=7&folt=kw-top
**作者**: M Zheng, J Wei, H Yang, Y Liu - arXiv preprint arXiv:2608.20127, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> After this stage, we further employ another MLLM [1] to verify the alignment between each textual description and its corresponding video content, filtering out imperfect samples with weak or inaccurate text-content correspondence. To validate

---

### [110] UMER: Unifying Embedding and Ranking via Pair-Aware Discriminative Reasoning for Universal Multimodal Retrieval

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.18504&hl=zh-CN&sa=X&d=6628414308408948336&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-yMLGLZPvpmHqgRolvB7sUa&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=4&folt=kw-top
**作者**: L Chen, X Liu, Y Wei, T Wang, Z Tang - arXiv preprint arXiv:2608.18504, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Recent MLLM -based embedding methods typically derive representations from hidden states, while Chain-of-Thought (CoT) reasoning is … ranking for explicit pairwise relevance judgment within a single MLLM . A complementary mutual

---

### [111] Latent Ordinal Evidence, Misaligned Outputs: Inference-Time Ordinal Lens Alignment for Multimodal LLMs

**链接**: https://arxiv.org/abs/2608.20999
**作者**: Haiming Li, Yingsheng Liu, Jingmin Zhu, Siyuan Yan, Xieji Li, Jiajun Sun 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal LLMs apply the language model interface to visual inputs, where ordinal regression tasks such as age estimation, image quality assessment, and disease grading require autoregressive decisions over ordered class labels. We ask whether MLLMs reliably convert internal ordinal evidence into ordered digit-token outputs. Across four ordinal benchmarks and four MLLM backbones, ordinal labels are linearly recoverable from hidden states with Spearman correlation up to 0.938, and a task-designed prompt further sharpens this structure. Yet native digit-token outputs weakly expose it: the unembedding matrix filters the ordinal direction, and the digit-token row space retains below 1.15% across all 16 model-dataset combinations, with a 16 to 77 absolute-point accuracy gap between linear-probe and native outputs. We introduce Ordinal Lens Alignment (OLA), a frozen-backbone inference-time method that trains lightweight W_S-anchored lenses on mid-to-deep decoder layers, fuses them into an o

---

### [112] G-CARL: Grounded Checklist-Aligned Reward Learning for Patient-Oriented Medical Report Interpretation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.20331&hl=zh-CN&sa=X&d=7466914959956382428&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-zDCfmxWJkKal1BBlcCZvjV&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=6&folt=kw-top
**作者**: S Xie, S Chen, J Lv, B Yuan, Y Wang, X Li - arXiv preprint arXiv:2608.20331 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> 3, we qualitatively compare the outputs of our method with SFT and MLLM -as-a-Judge using Qwen3VL-8B as the base model. The report … However, SFT incorrectly diagnoses metabolic acidosis and misclassifies the severe anemia as mild, while MLLM -as-a-Judge

---

### [113] PATE-Forensics: Perception-as-Tool for Explainable Deepfake Forensics with General-Purpose MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.18573&hl=zh-CN&sa=X&d=17920074450613507593&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-yViWMdU0SZpoy6AFh1zvm7&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: Y Li, J Peng, Y Wang, J Liu, X Hong - arXiv preprint arXiv:2608.18573, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Existing explainable deepfake forensic methods typically rely on task-adapted MLLM to jointly address detection, localization, and explanation. Inspired by agent-style tool use, we instead introduce a Perception-as-Tool paradigm and instantiate it as

---

### [114] Question-Guided Evidence Acquisition for Multimodal Visual Question Answering

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.19739&hl=zh-CN&sa=X&d=17977102889987255348&ei=XtaKatPWPOOUieoP8JfE4QU&scisig=AIVdB-waf-vETh7N28hMuV8FQwSN&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=8&folt=kw-top
**作者**: AI Popa - arXiv preprint arXiv:2608.19739, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Since these baselines were originally reported on different MLLM backbones, we re-implement each on our Claude backbones— keeping each method’s own tools and control logic—so any difference reflects the evidence-acquisition strategy, not

---

### [115] ReFrame: Evidence-Guided Test-Time Safety Alignment in Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2608.21100
**作者**: Wenzheng Jiang, Xuankun Rong, Yuanzhao Zhai, Dawei Feng, Huaimin Wang
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multimodal large language models (MLLMs) extend model capabilities beyond text, they also make safety alignment increasingly challenging. Multimodal safety alignment methods must address cross-modal jailbreaks, safety-awareness failures, and over-sensitive refusals. However, existing methods often rely on retraining or internal-state inspection, limiting their applicability to deployed closed-source MLLMs and motivating test-time safety alignment. We analyze this setting and identify two key obstacles, utility dominance and reasoning inertia, which cause models to overlook latent risks or follow malicious reasoning trajectories. Guided by these insights, we propose ReFrame, a training-free multimodal input reframing framework where two agents share a lightweight locally deployed MLLM: the evidence-generation agent constructs complementary risk and utility evidence, and the rewrite-and-routing agent converts it into a safe proxy prompt and image-routing decision before calling the

---

### [116] A Real-Time Brain-Computer Interface with FPGA-Accelerated Neural Signal Processing and Enhanced EEG Classification using Adaptive SVM

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11658679.pdf&hl=zh-CN&sa=X&d=15332138434877896607&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-zv-YUIrxt-ZASEvNG3SP8L&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: T Hussain, S Alharbi, M Asma, MZ Ullah - IEEE Access, 2026
**匹配关键词**: EEG, BCI, Brain-Computer Interface, Neural Signal
**相关性评分**: 12.0
**数据来源**: Google Scholar

**摘要**:

> Human emotions and actions can be identified by analyzing electroencephalography ( EEG ) signals captured through brain–computer interfaces (BCIs) and processed using signal classification algorithms. However, EEG -based BCI

---

### [117] Systematic Comparison of Electroencephalography Feature Domains for Visual Stimuli Decoding with EEGNet and EEG Conformer

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2673-2688/7/8/323&hl=zh-CN&sa=X&d=13661012893521609523&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-zQ7s-4O5iq_T1QMAcGqd5d&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: CA Corona-Patricio, C Reta, JA Cantoral-Ceballos - AI, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalography -based visual decoding has important applications in brain–… This study systematically compares eight feature extraction methods across three public EEG … Two deep learning architectures, EEGNet and EEG Conformer

---

### [118] Education Research: Development of a Workplace-Based Assessment to Enhance EEG Interpretation Skills for Medical Students

**链接**: https://scholar.google.com/scholar_url?url=https://www.neurology.org/doi/pdfdirect/10.1212/NE9.0000000000200349&hl=zh-CN&sa=X&d=13627069949390535910&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-yC7_dVy908je4I4114h3nB&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: H Kostan, A Dickey, K Gadelmola, AM Goldman… - Neurology® Education, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ) interpretation is a core competency in neurology residency training, yet structured EEG education for interested medical students … address gaps in EEG education. We developed a novel EEG -specific WBA for use during a 2-week

---

### [119] Evaluating the performance of EEG based on ANN to predict the effectiveness of tDCS combined evaluative conditioning on obsession symptoms reduction in …

**链接**: https://scholar.google.com/scholar_url?url=https://journals.plos.org/plosone/article%3Fid%3D10.1371/journal.pone.0354614&hl=zh-CN&sa=X&d=7855330641584774837&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-ziVUNRVw1c0kKBAFl9FW2E&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: F Asadollahzadeh Shamkhal, A Moghimi, HR Kobravi… - PloS one, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> of the intervention using electroencephalography ( EEG ) signals before performing a … Second, the linear and nonlinear features extracted from the EEG signal were examined, and … the appropriate features extracted from the EEG

---

### [120] Deep CNN ensemble framework for early detection of epileptic seizures using STFT-derived EEG features

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s44163-026-01631-3&hl=zh-CN&sa=X&d=6472100185736018269&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-ylthmY2lxjlOK37XapqYmO&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: U Chaurasia, S SJ, HK Pathak, KK Singh, O Singh - Discover Artificial Intelligence, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Epileptic seizures generally deal with the brain, and EEG ( Electroencephalogram ) proves to be … Epileptic EEG recordings are classified into four phases: interictal, preictal, ictal, and … early neurophysiological changes become evident in EEG

---

### [121] DAWRNet: A Dual Adaptive Weighting and Refinement Network for auditory attention detection from EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426018641&hl=zh-CN&sa=X&d=1552730673640213657&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-w9jyarrhs0dy-w7oaI_B_P&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: L Huang, Y Liu, Y Meng, Y Yan, T Li - Biomedical Signal Processing and Control, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalography ( EEG )-based Auditory Attention Detection (AAD) faces challenges like low signal-to-noise ratio (SNR), inter-subject variability, and the need for high accuracy within short decision windows. Existing models often lack

---

### [122] A Resource-Efficient CNN-Based EEG Auditory Attention Decoding ASIC

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.20198&hl=zh-CN&sa=X&d=16893964635807952038&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-xJaWrWpL4JvP2mKelGNvL9&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: Q Ma, R George, S Scholze, J Constantin… - arXiv preprint arXiv …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> EEG -based auditory attention decoding (AAD) using neural networks to enhance hearing assistance. This paper presents a resource-efficient ASIC for real-time EEG … 7.34 ms, providing an energy-efficient hardware platform for EEG -based auditory

---

### [123] Dynamic Hemispheric Lateralization of Naturalistic Emotional Processing After Unilateral Stroke: An EEG Study

**链接**: https://scholar.google.com/scholar_url?url=https://pmc.ncbi.nlm.nih.gov/articles/PMC13492182/&hl=zh-CN&sa=X&d=16825967225844805454&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-xvvD8aM2mA8kcMn7ANKyvX&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: M Han, Y Tang, Y Lv, X Chen, X Liu, Z Chen 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study used a naturalistic viewing approach to record electroencephalography ( EEG ) data from individuals with left‐hemisphere stroke (L‐stroke), right‐hemisphere stroke (R‐stroke), and healthy controls (HC). The main analysis

---

### [124] DMG-GCN: A Dynamic Microstate-Guided Graph Convolutional Network for EEG Cognitive Workload Decoding in Air Traffic Control

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2079-6374/16/8/452&hl=zh-CN&sa=X&d=4128307138276649312&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-zumTkVMJBciz7T3HsYcdEy&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: Y Zhang, Q Shao, H Yang, X Ren, X Peng - Biosensors, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Complex inter-subject variability induces severe distribution shifts in the physiological features of electroencephalography ( EEG ) for air traffic controllers (ATCOs). These inter-subject shifts limit the generalization and interpretability of passive brain–computer

---

### [125] Neuro-Geospatial Modelling of EEG Affective States Using Literature-Informed Environmental Context

**链接**: https://arxiv.org/abs/2608.20807
**作者**: Utsav Poudel, Jagannath Aryal, Subramaniyaswamy Vairavasundaram
**来源**: cs.AI cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Environmental exposures such as air pollution and greenness have been associated with affective and cognitive outcomes, but EEG and environmental datasets are rarely jointly georeferenced. We investigate whether literature-informed environmental priors can serve as an auxiliary geospatial modality for EEG-based affective-state classification when individual-level exposure data are unavailable. We combine 30-channel EEG from the EAV benchmark (42 participants, aged 20-30 years) with environmental representations derived from OpenAQ, Sentinel-2, Sentinel-5P, and OpenStreetMap data for Astana. A dual-tower architecture combines EEG-Conformer representations with a graph-based environmental encoder. Because the datasets are not co-registered, environmental context is treated as a literature-informed prior rather than measured exposure. Subject-level repeated splits, permutation and label-shuffling controls, dose-response reversal, and domain-shift experiments distinguish architecture-level

---

### [126] EEG Feature Extraction and Machine Learning for Consumer Preference Analysis of Whisky

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2665927126002406&hl=zh-CN&sa=X&d=17301347060753291679&ei=XtaKapyFMde46rQPh67buAk&scisig=AIVdB-yerUrSCxzmKD0jE0Wt2iaR&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: Z Zeng, X Liu, Y Xu, K Tang - Current Research in Food Science, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> explore whether consumers exhibit distinct EEG patterns under different whisky preference states, whether EEG features are significantly … by combining EEG signals with machine learning algorithms. To this end, this study comprehensively

---

### [127] NeuroStrata: An Electroencephalographic Connectivity-Aware Deep Representation Learning Framework for Dynamic Brain Network Analysis of Mental Stress

**链接**: https://arxiv.org/abs/2608.20354
**作者**: Sayantan Acharya, Hamzeh Asgharnezhad, Abbas Khosravi, Douglas Creighton, Roohallah Alizadehsani and U Rajendra Acharya
**来源**: q-bio.NC cs.AI cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study introduces NeuroStrata, a connectivity-aware deep representation learning framework for EEG-based mental stress analysis using Time-Varying Partial Directed Coherence (TV-PDC). Unlike conventional EEG classification approaches based on static features, NeuroStrata models the temporal evolution of frequency-specific directed connectivity across distributed brain regions. EEG signals from the 32-channel SAM 40 dataset recorded during mental arithmetic tasks were used to generate TV-PDC connectivity maps. These maps were processed using pretrained Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to extract deep connectivity embeddings, which were subsequently classified using lightweight machine learning models. Experimental results demonstrate that beta-band connectivity provides the highest discriminative capability, achieving a peak accuracy of 97.3% using the LAION-CLIP-ViT-L14 backbone with a Support Vector Machine classifier, while alpha-band connectivi

---

### [128] CellPath-Bench: A Multidimensional Benchmark for Whole-Slide Cellular Representations in Pathology Foundation Models

**链接**: https://arxiv.org/abs/2608.21060
**作者**: Bokai Zhao, Yiyang Zhang, Hanqing Chao, Yawei Ma, Long Bai, Tai Ma 等 (9 人)
**来源**: cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models (PFMs) are increasingly used as general-purpose backbones, yet existing benchmarks cannot systematically diagnose their whole-slide cellular representation capabilities, including the decodability of cell-type information and the transferability of such information across tissue sections, datasets, and anatomical organs. We introduce CellPath-Bench, a cellular-resolution benchmark that evaluates frozen PFMs themselves. Following quality control of 52 candidate Xenium datasets, we construct a panel of 25 spatially aligned H\&E--Xenium tissue sections spanning 11 organs and 7,079,283 cells, harmonized into fine- and coarse-grained taxonomies. CellPath-Bench samples frozen WSI feature maps at registered nuclear coordinates and evaluates them using standardized multiclass linear probes. Cell Representation Advantage (CRA) measures the within-section advantage of nucleus-anchored representations over patch-level mean pooling, while Cell Representation Transferabi

---

### [129] A Distributional Robustness Margin For Pathology Foundation Models

**链接**: https://arxiv.org/abs/2607.25497
**作者**: Cl\'ement Grisi, Jeroen van der Laak, Geert Litjens
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] Attributing Preprocessing Invariance in Spectral Foundation Models

**链接**: https://arxiv.org/abs/2608.14227
**作者**: Dongjun Wei, Hongyi Wu, Yinuo Zou
**来源**: cs.AI cs.CE cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] Foundation Models for Partial Causal Identification

**链接**: https://arxiv.org/abs/2608.20841
**作者**: Alexis Bellot, Anish Dhir
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper investigates the development of causal foundation models for bounding the effect of interventions and counterfactuals from observational data. We show that a canonical prior can be defined with full support over the space of structural causal models with discrete observables. With this canonical prior, we translate the problem of bounding counterfactuals into that of learning distributions over functions that map data (and possibly structural assumptions) to a causal query of interest. This extends the promising causal foundational modelling paradigm to the estimation of partially-identifiable causal effects, i.e., under unobserved confounding, where multiple values are equally compatible with the observed data and prior structural assumptions.

---

### [132] Trojaning the Alignment: Stealthy Backdoor Attacks against Graph Foundation Models

**链接**: https://arxiv.org/abs/2608.20991
**作者**: Minhua Lin, Zhicheng Gao, Yilong Wang, Hanqing Lu, Xiang Zhang, Suhang Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph Foundation Models (GFMs) on text-attributed graphs (TAGs) align graph representations with language semantics to support transferable graph learning. Despite these advantages, the backdoor vulnerability of GFMs on TAGs remains insufficiently understood, especially under graph-language alignment, where graph and text representations are trained to constrain each other in a shared semantic space. Existing backdoor attacks mainly target either the graph side or the text side, treating the two modalities independently. This makes direct adaptation ineffective: graph-only triggers can be constrained by clean text semantics, while text-only triggers alter the language view but do not directly shift the graph representation being aligned and scored. TAGs also impose a stealth challenge because triggers are exposed as both node text and local graph structure, making incoherent trigger attributes or anomalous subgraphs easy to inspect or filter. In this paper, we propose STAG, a stealthy 

---

### [133] Learning to Orchestrate Vision Foundation Models for Multi-Task Dense Prediction

**链接**: https://arxiv.org/abs/2606.15765
**作者**: Donghyun Han, Yuseok Bae, Jung Uk Kim, Hyung-Il Kim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Semantically Compatible Knowledge Distillation for Cross-Domain Object Detection with Vision Foundation Models

**链接**: https://arxiv.org/abs/2608.20916
**作者**: Qifeng Zhang, Ting Xiang, Zeyuan Bai, Changjian Chen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models (VFMs) offer strong generalization capabilities for domain-adaptive object detection (DAOD). However, existing VFM-based methods overlook the spatial-scale discrepancy between teacher and student feature maps, resulting in semantic incompatibility that weakens both feature alignment and pseudo-label learning. Moreover, domain shift can cause source-trained VFM teachers to miss target-domain objects, limiting the quality of their pseudo-labels. To address these issues, we propose the Semantic Localization-Enhanced Teacher (SLE-T), a semantically compatible knowledge-distillation framework built around a lightweight SLE Adapter for DINOv2. SLE Adapter injects pretrained local-texture priors into DINOv2 to improve cross-domain recognition and reformulates its features into dense representations that are spatially and semantically compatible with the student detector. SLE-T transfers the resulting teacher knowledge through either pseudo-label learning or feature al

---

### [135] Mint-Agent: Introducing Finance-Native Agentic Foundation Models

**链接**: https://arxiv.org/abs/2608.16386
**作者**: Mint-Agent Team, Kun Wang, Gavin Zhang, Yaze Geng, Lei Tang, Yaoyang Yi 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] Generating Multi-view Adversarial Examples for Visual Geometry Grounded Transformer

**链接**: https://arxiv.org/abs/2608.20748
**作者**: Qi Song and Ziyuan Luo and Haoliang Han and Renjie Wan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Visual Geometry Grounded Transformer (VGGT) enables unified feed-forward 3D reconstruction from multi-view images. However, deploying such a high-performance model may expose critical security vulnerabilities. Traditional adversarial perturbations require costly per-scene optimization, while Universal Adversarial Perturbations (UAPs) rely on a single static pattern and fail to effectively attack VGGT. To address these limitations, we propose \textbf{MVAP-G}, a multi-view adversarial perturbation generator that produces imperceptible consistent perturbations across multiple views in a single feed-forward pass. To ensure perturbation consistency across diverse scenes, we design a cross-view adversarial alignment mechanism to process multi-view images. Experiments demonstrate that MVAP-G significantly degrades VGGT performance without iterative optimization during inference. This work pioneers multi-view adversarial attacks on 3D foundation models, uncovering severe vulnerabilities an

---

### [137] Just Noticeable Difference Modeling for Token Compression in Vision-Language-Action Models

**链接**: https://arxiv.org/abs/2608.21247
**作者**: Zhuoyuan Li, Rui Zhao, Jin Wang, Hanwei Zhu, Cong Zhang, Giuseppe Valenzise 等 (8 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Token compression has become a key technique for reducing the inference cost of large foundation models, with approaches such as token pruning and KV-cache reuse widely adopted in vision-language models and recently explored for embodied agents. In embodied agents, tokens not only support perception and semantic understanding but also directly affect latency-sensitive closed-loop robot action prediction. Existing schemes typically guide compression using redundancy or importance cues, such as visual similarity, attention scores, and saliency. However, these cues only indirectly measure the key factor for safe compression: how much a token can change before causing an unacceptable deviation in downstream actions. This receiver-dependent tolerance is closely related to the principle of just noticeable difference (JND). Classical JND characterizes signal tolerance in the human visual system, while machine-oriented JND extends this concept to downstream machine responses. Building on this 

---

### [138] A2DINOv3: Rethinking Multi-Modal Object Detection via Socialized Collaboration

**链接**: https://arxiv.org/abs/2608.21099
**作者**: Jiekang Feng, Zhihe Fan, Yunqi Zhu, Xinjie Yao, Yueying Zhang, Yike Gao 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-modal object detection is essential for robust scene understanding in challenging conditions, including low-light and adverse environments. Recent vision foundation models (e.g., DINOv3) have exhibited strong representation capabilities, yet adapting them to multi-modal scenarios remains challenging. Existing dense cross-modal fusion strategies often force heterogeneous modalities to interact indiscriminately, which may introduce redundant information and disrupt the valuable pre-trained representations. To address this issue, we revisit multi-modal fusion from the perspective of socialized learning and propose adapter to DINOv3 (A2DINOv3), a multi-expert collaboration framework with a Socialized Collaboration Protocol (SCP). Specifically, RGB and infrared branches are modeled as heterogeneous experts that independently preserve their specialized knowledge while exchanging complementary information through selective and constrained interactions. This design mitigates harmful cros

---

### [139] M2Depth: Unifying Monocular Depth Foundation Priors with Multi-View Stereo

**链接**: https://arxiv.org/abs/2608.20788
**作者**: Byeonggwon Lee, Sanggi Lee, Siwoo Lee, Khang Truong Giang, and Soohwan Song
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning-based Multi-View Stereo (MVS) has advanced significantly but often generalizes poorly to unseen scenes, particularly in occluded areas or regions with limited view overlap. To mitigate this, recent approaches integrate Depth Foundation Models (DFMs) into MVS pipelines to provide monocular depth priors. However, existing methods typically rely on a static, one-way fusion scheme, which fails to fully exploit the complementary strengths of both modalities. We propose a novel framework that overcomes this limitation by tightly coupling a DFM with a cascade MVS pipeline through a bidirectional mutual refinement strategy. Our method leverages MVS depth to resolve the scale ambiguity in monocular predictions, while the monocular depth, in turn, enhances the structural completeness and fine-grained detail of the MVS estimate. Furthermore, we introduce a prior-guided cost volume refinement mechanism that effectively integrates multi-view and monocular information via attention-bas

---

### [140] WildFin: An In-the-Wild Dataset for Fish Behavioral Recognition

**链接**: https://arxiv.org/abs/2608.21281
**作者**: Abigail G. Grassick, Jerome Tze-Hou Hsu, Ethan Lin, Ziang Liu, Max Whitton, Madelyn Hair 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in field technology have led to a massive influx of in-the-wild video data for ecological science. The primary bottleneck in leveraging this data is the high cost of expert annotation. While computer vision offers a potential solution, current models frequently fail when deployed in complex marine environments. To characterize these failures, we introduce WildFin, a novel benchmark for fish behavior recognition collected and annotated by ecologists.WildFin spans two critical real-world paradigms: stationary cameras monitoring groups of fish and dynamic divers following individual subjects. The dataset represents a massive curation effort, involving 1,350 hours of fieldwork and 600 hours of expert annotation to produce 9 hours of behavioral data with over 2 million frame-by-frame labels. We benchmark modern vision foundation models and quantify tradeoffs between static and spatiotemporal architectures, revealing the substantial gap that remains between current model capa

---

### [141] Lift, Associate, and Fuse: A Decision-Centric Framework for 2D-to-3D Foundation Model Transfer

**链接**: https://arxiv.org/abs/2608.20659
**作者**: Wentao Sun, Yiping Chen, John S. Zelek, Jonathan Li
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Methods that transfer predictions from two-dimensional foundation models into three-dimensional segmentation are commonly grouped by task or representation. Those groupings obscure the decisions that determine whether a system remains coherent across views: where image evidence is grounded, when observations become one identity, how semantic and granularity conflicts are handled, which information is fused, and what state survives for later queries. We introduce \textbf{Lift, Associate, and Fuse (LAF)}, a decision-centric framework that represents a transfer system as five operators: \textbf{Generate, Associate, Reconcile, Fuse, and Persist/Query}. LAF defines an explicit contract for the persistent carrier---its spatial support, semantic state, identity state, uncertainty, provenance, and supported operations---and identifies the first stage at which discarded evidence becomes unrecoverable. We operationalize the framework as a structured audit protocol and apply it to 161 systems ava

---

### [142] Tydra: An Efficient Hybrid Model for Tabular Data

**链接**: https://arxiv.org/abs/2608.21199
**作者**: Mieszko Komisarczyk, Saurabh Mathur, Maurice Kraus, Sriraam Natarajan, Kristian Kersting
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transformer-based tabular foundation models such as TabPFN achieve strong predictive performance but incur quadratic computational cost with context length. On the other hand, subquadratic SSM-based alternatives such as Hydra trade away accuracy for efficiency. To balance both, we introduce Tydra, a hybrid Transformer-State Space Model (SSM) architecture for tabular in-context learning that interleaves attention and SSM layers. Across 30 OpenML datasets, Tydra reduces inference time by 30% relative to TabPFN while retaining much of its predictive performance. Tydra also outperforms an approximately ten-times-larger Hydra model while providing faster inference. The results indicate that hybrid architectures are a promising direction for tabular foundation models.

---

### [143] Stream3Dv2: Geometric-Semantic Fusion Enhanced Streaming Zero-Shot 3D Scene Understanding

**链接**: https://arxiv.org/abs/2608.21136
**作者**: Jie Xu and Na Zhao
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, open-vocabulary zero-shot 3D scene understanding using vision foundation models has emerged as a promising alternative to data-intensive supervised methods. However, deploying these models in real-world scenarios is severely hindered by their inability to efficiently handle streaming RGB-D inputs and their inherent vulnerability to noise 2D segmentation masks. To address these critical limitations, we propose Stream3Dv2, a novel training-free framework designed for robust streaming 3D perception. Stream3Dv2 processes sequential data through an original nested local-to-historical architecture, capturing multi-view consistency while circumventing the high computational overhead so as to support timely responses. At its core, we introduce a comprehensive geometric-semantic fusion mechanism that resolves geometric noise and semantic ambiguity by explicitly utilizing semantic guidance and formulating 3D segmentation as solving point-and-set merging and partitioning problems. Furth

---

### [144] Aristotelian Manifolds: Leveraging Platonic Perceptual Features for Backpropagation Free Rapid Concept Learning

**链接**: https://arxiv.org/abs/2608.20682
**作者**: Michael Karnes, Alper Yilmaz
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper formalizes and systematically characterizes Aristotelian Manifolds, a generalized structural framework built upon the Platonic Representation Hypothesis. We position high-capacity foundation models as universal perceptual filters and conduct a comprehensive layer-wise investigation to map how knowledge is functionally synthesized within these latent subspaces. Across diverse architectural paradigms and multi-domain datasets, we rigorously chart the interplay between network depth, dimensionality reduction, and distance metrics. Our characterization reveals that semantic maturation does not follow a singular, monotonic path; instead, different data domains exhibit highly distinct geometric response profiles, characterized by intermediate mound-like peaks for specialized clinical modalities and sigmoidal plateaus for natural visual tasks. By profiling the exact coordinates where these manifolds achieve peak representational efficiency, we establish a predictable taxonomy for l

---

### [145] When Adaptation Hurts: Connecting Representational Drift to OOD Failures in MedSAM Fine-Tuning

**链接**: https://arxiv.org/abs/2608.21300
**作者**: Marko Haralovi\'c, Sounic Akkaraju, Carlo Baretta, Vasil Zapryanov, Alexia Briassouli
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for medical image segmentation, like prompt-based MedSAM, generalize well across domains and modalities, often in zero or few-shot setups. However, their performance depends on the quality of prompts and the adaptation of the models to custom datasets. This work systematically examines how MedSAM generalizes across diverse medical imaging benchmarks, with six adaptation strategies: full-model and encoder-only LoRA, shallow and deep visual prompt tuning (VPT), and decoder-only and full fine-tuning. Models are trained on the International Skin Imaging Collaboration Challenge (ISIC 2018) dataset and evaluated under clean and increasingly noisy prompts on IN and Out-of-Distribution (OOD) datasets: close-OOD PH2 (dermoscopy), far-OOD BUSI (Breast Ultrasound Images Dataset) and CBIS-DDSM (Curated Breast Imaging Subset of the Digital Database for Screening Mammography). We show that adaptation improves performance on IN and close-OOD data but often reduces performance on far

---
