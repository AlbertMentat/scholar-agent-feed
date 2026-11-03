# 📑 论文索引 - 2026-11-04

共 329 篇论文

---

### [1] Q-CamTuning: A Multimodal Large Language Model for Fine-Grained Quality Reasoning in Livestreaming Camera Tuning

**链接**: https://arxiv.org/abs/2611.03007
**作者**: Yanchao Bi, Pengfei Chen, Yulong Yan, Qian Zhang, Biao Wang, Leida Li
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the popularization of livestreaming applications, automatic camera tuning has become indispensable for ordinary users to enjoy high Quality of Experience (QoE). However, the existing Image Quality Assessment (IQA) methods face two challenges in camera tuning. First, they struggle to identify subtle quality difference between images, which is common in camera tuning. Second, the ability to explain fine-grained differences and to provide suggestions for camera tuning are even more lacking. To address these challenges, we first construct FGLive-Comments, an instruction tuning dataset with rich annotations of both preferences for fine-grained image pairs and quality reasoning from global and local visual evidence, which supports selective adjustment recommendations of camera parameters. Based on FGLive-Comments, we develop Q-CamTuning, a multimodal large language model for livestreaming camera tuning. Its progressive perception-evidence-guidance framework learns quality-aware visual r

---

### [2] MSP-LLM: A Structured Large Language Model Framework for Inorganic Material Synthesis Planning

**链接**: https://arxiv.org/abs/2602.07543
**作者**: Heewoong Noh, Gyoung S. Na, Namkyeong Lee, Chanyoung Park
**来源**: cs.AI cond-mat.mtrl-sci
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [3] BLPO: Beyond-Local Policy Optimization for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2611.03005
**作者**: Xuanren Chen, Chongyang Tao, Wenpeng Hu, Yong Wang, Bo Deng, Xinlei Zheng 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon tasks require large language model (LLM) agents to coordinate interdependent actions, a capability central to automating complex workflows. Stepwise group-based reinforcement learning provides finer credit than trajectory-level supervision, but reliable comparisons must account for differences in interaction history. Enforcing this consistency within the limited rollouts of each task can leave insufficient support for estimating action preferences. We propose Beyond-Local Policy Optimization (BLPO), which estimates task-progress advantages from experience shared across tasks and training updates. We summarize trajectory prefixes into task-progress states and abstract actions by their function, allowing corresponding decisions from different tasks to contribute to shared estimates. To control bias and noise from heterogeneous tasks, we accumulate context-relative returns in a global memory with balanced aggregation and reliability weighting. These global advantages compleme

---

### [4] PACERec: Progressive Adaptation of LLM Item Embeddings with Collaborative Evidence for Recommendation

**链接**: https://arxiv.org/abs/2611.03068
**作者**: Junzhao Huang, Xi Wu, Zihan Wang, Zijing Wang, Ming Wang, Kang Liu 等 (10 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) embeddings have been increasingly adopted in sequential recommendation to encode static item attributes and alleviate the limitations of item ID embeddings under sparse interactions. However, these embeddings typically capture only static content similarity while neglecting sequential transitions, and since their adaptation quality relies on sparse per-item updates or global geometric calibration, existing methods still struggle to explicitly transfer preceding interaction contexts from frequent to long-tail items under unevenly distributed behavioral evidence, limiting recommendation effectiveness across the catalog. To address this challenge, we propose PACERec, an ID-free progressive adaptation framework that incorporates preceding interaction contexts into semantic representation adaptation by learning a shared velocity field from items with sufficient interactions via frequency-weighted flow matching. In this way, PACERec progressively guides static LLM 

---

### [5] UI-UG 2: Advancing Mobile UI Understanding and Generation with Fine-Grained Supervision and Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.00926
**作者**: Hao Yang, Shuoyang Liu, Xiaoyu Lin, Zhou Fang, Maji Huang, Zhaosong Huang 等 (9 人)
**来源**: cs.CV cs.AI cs.HC
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile UI understanding and generation require both fine-grained component perception and reliable structured synthesis. Inspired by the unified direction introduced by UI-UG, we present UI-UG 2, a compact 4B-parameter multimodal large language model (MLLM) that advances mobile UI Understanding and Generation with broader task coverage, a front-end-aligned taxonomy, and online render-aware reinforcement learning. UI-UG 2 constructs a multi-source understanding corpus from RICO, VINS, Android in the Wild, and Android Control, annotated with an 80-category two-level UI taxonomy aligned with front-end component semantics, and pairs it with over 5,000 requirement-screenshot-JSON tuples for progressive structured UI generation through a domain-specific language (DSL). For understanding, UI-UG 2 introduces decomposed rewards for category prediction, OCR fidelity, color recognition, dense grounding, and GUI grounding. Unlike the offline Direct Preference Optimization (DPO)-style generation op

---

### [6] ENGINE: Endogenous Variational MultiScale Optimization for Zeroth-Order LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2611.03293
**作者**: Zhuoli Ouyang, Changxi Chi, Siyuan Li, Tailin Wu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zeroth-order (ZO) optimization enables memory-efficient large language model (LLM) fine-tuning, and recent methods incorporate curvature-aware strategies. However, in the high-dimensional parameter space of LLMs, these methods inherently suffer from exploding gradient variance and prohibitive costs. Conversely, confining updates to a low-dimensional subspace reduces variance but discards critical high-dimensional information, degrading performance. This creates a fundamental dilemma: full-space optimization is informative but has high variance, while subspace optimization has low variance but loses information. To break this trade-off, we propose ENGINE (Endogenous Variational MultiScale). Inspired by computational mechanics, we adapt static Variational MultiScale (VMS) theory to dynamic optimization, treating low- and high-dimensional spaces as resolved coarse and unresolved fine scales. Through a multigrid-style V-cycle, ENGINE alternates between spaces, dynamically probing fine-grai

---

### [7] The Customer Never Sees the Goal: Measuring and Detecting Vulnerability-Targeted Manipulation in LLM Assistants

**链接**: https://arxiv.org/abs/2611.02689
**作者**: Bohan Jiang, Dawei Li, Yasin Silva, Huan Liu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Companies deploy large language model (LLM) assistants on their websites to advise customers. For commercial reasons, the operator can give an assistant a goal that the customer never sees. This paper focuses on operator-induced vulnerability-targeted manipulation (VTM), in which an assistant pursues such a goal by exploiting a vulnerability the customer discloses. While existing research mainly measures how manipulative a model is, we go further and ask whether VTM can be detected from the customer-AI conversation. To investigate this at scale, we introduce GAP (Goal-Anchored Probing). GAP first records the option a model recommends without any goal and then sets the other option as the operator's goal. We apply GAP to 15 open- and closed-source LLMs and collect 619,600 labeled replies across 540 everyday scenarios in 12 domains. We organize our study around three research questions. (1) Do assistants with an operator goal target vulnerable customers? (2) Can VTM be detected from the 

---

### [8] LLM-Enhanced Multimodal House Price Prediction using Structured, Textual, and Visual Features

**链接**: https://arxiv.org/abs/2611.01615
**作者**: Khandokar Md. Rahat Hossain, Souvik Das, Tahsina Hashem, Mohammed Eunus Ali, Tanzima Hashem
**来源**: cs.LG cs.CL cs.CV cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate house price prediction is essential for real estate buyers, sellers, agents, and financial institutions. Traditional methods rely primarily on structured data, e.g., number of bedrooms, bathrooms, parkings, but they overlook rich contextual information embedded in textual descriptions and property photos. Previous deep learning approaches for house price prediction have fused multimodal data but they fall short to extract structured spatio-temporal and contextual features from texts and semantic visual information from images. In this paper, we introduce a novel multimodal framework that addresses these limitations by systematically integrating structured attributes, textual descriptions, and visual images of properties to achieve higher prediction accuracy while maintaining interpretability. We use a large language model to derive domain-specific spatio-temporal and contextual features from text, and an unsupervised vision-language approach to automatically group photos into 

---

### [9] Taurus: LLM-in-the-Loop CT Annotation Matches Coding Agents at Half the Cost

**链接**: https://arxiv.org/abs/2611.00247
**作者**: Bing Hu, Rishabh Sharma, Jatin Mehta
**来源**: cs.AI cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dense labels of the aorta in CT are slow to draw, and the public aortic CT datasets that could stand in for them each label different structures under their own conventions. Large language model (LLM) agents can now write code and read images. We asked whether such a model labels these scans better as a free-form agent that writes its own segmentation code, or inside a harness, where an automated pass labels the scan and the model reviews the result. We built a harness, Taurus, and compared it with free-form agents by blind label recovery: we withheld the human labels of six public datasets (939 volumes) and scored every approach against each dataset's own classes. In the first version of Taurus, the model's review raised the primary metric on only two of six datasets, by less than the noise between two reviews of the same case. A free-form agent running Claude Opus 5.5 scored higher on most datasets. Moving what the free-form agents did well into the automated pass then carried most o

---

### [10] StateFence: Task-State Protection Against Evidence-Chain Contamination in Blue-Team LLM Agents

**链接**: https://arxiv.org/abs/2611.02605
**作者**: Haowen Dai, Alejandro Guerra-Manzanares
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Indirect prompt injection creates a distinctive risk for blue-team Large Language Model (LLM) agents in Security Operations Centers (SOCs). Malicious instructions can be embedded in telemetry, tickets, retrieval results, or memory and then propagate through alert triage, incident summarization, response recommendation, and Indicator of Compromise (IOC) extraction as locally plausible intermediate decisions. We characterize this failure mode as evidence-chain contamination of protected task state. The main challenge is task dependent: a suspicious string may be malicious control text for summarization but essential evidence for IOC extraction. To address this challenge, we propose StateFence, a task-aware evaluation and defense framework that treats severity labels, incident narratives, response policies, and IOC sets as protected states. StateFence maps indirect prompt-injection attacks into explicit, stealth, multi-hop, and persistent SOC evidence attacks, records observable propagati

---

### [11] Predictive Safety Guardrails Do Not Always Make LLM Agents Safer

**链接**: https://arxiv.org/abs/2611.02815
**作者**: Weixiang Zhao, Zhihao Liu, Guancheng Li, Yanyan Zhao, Bing Qin, Ting Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly take consequential actions in digital and physical environments, where safety risks may emerge only after multiple interaction steps. This has motivated world-model-driven predictive safety guardrails, which anticipate future consequences before execution. However, existing evaluations largely focus on end-to-end safety outcomes, leaving unclear whether safety gains arise from reliable prediction and faithful use of predicted risks. In this work, we systematically diagnose the prediction-to-action pipeline along three dimensions: how world-model predictions are integrated into decision making, whether the predictions themselves are reliable, and whether their content is faithfully used. Across seven policy models and two safety environments, we find that stronger prediction involvement does not yield monotonic safety gains and can reduce task completion while substantially increasing inference cost. We further find that world-model predictions r

---

### [12] Character-Name Concentration in LLM Fiction: Measuring Displacement and Mitigating Repetition

**链接**: https://arxiv.org/abs/2611.01284
**作者**: Alejandro Mozo Quesada (1), Sergio G\'alvez Rojas (1), Francisco L\'opez Valverde (1) ((1) Universidad de M\'alaga, Spain)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Character names in large language model (LLM) fiction concentrate on a handful of recurrent names such as 'Elara' and 'Elias', a measurable face of AI slop. Existing fixes either require logit access or retraining, or operate per request and cannot control concentration across a corpus. How much prompt-level strategies reduce concentration, and at what cost to name naturalness, has not been systematically measured. We present an empirical study of name-concentration control across eight strategies and introduce speculative naming, a fine-tuning-free method that adapts the draft-verify-reject paradigm of speculative decoding from tokens to names. The method requests candidate name-sets through verbalized sampling, scores them against a SlopTracker that combines a per-model fingerprint with a runtime counter, and selects through a temperature-controlled rule or its strict variant (HARD). We use 20 LLMs to generate 44,782 stories in four languages from text and visual stimuli (88,919 name

---

### [13] Do Social Influence Pressures Move LLM Agents? Evidence from Delegated Audit Judgment

**链接**: https://arxiv.org/abs/2611.00508
**作者**: Richard Zhe Wang
**来源**: cs.CY cs.AI cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are rapidly being integrated into complex professional workflows such as auditing and entrusted with judgments under human review. Human auditors are known to yield to social influence pressures from superiors, peers and clients, and this paper asks whether LLM agents yield to the same pressures and, if so, how they respond. In an experiment on twelve model settings, an LLM agent acting as a senior associate in audit analytical review forms an estimate and is then challenged without new evidence by colleagues inside the firm, by a reviewer from another firm and by the client's CFO, with and without a career inducement. Experimental findings show that LLM agents yield to pressure from the engagement partner, from peers and from a reviewer from another firm, but in most settings not to pressure from the client's CFO. Under a career inducement the LLM agents revise their estimates less, not more, and they name the inducement as a threat to independence. F

---

### [14] Cumulative and Audited Guardrail Tool Evolution for LLM Agent Safety

**链接**: https://arxiv.org/abs/2611.02516
**作者**: Xiao Yang, Aishan Liu, Siyuan Liang, Zonghao Ying, Le Wang, Jiakai Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly operate in open-world environments where safety risks cannot be fully predefined. However, most existing guardrail mechanisms remain static, relying on fixed rules, prompts, or classifiers that generalize poorly to emerging risks. Here we present EVOLVE, a tool-level self-evolving defense framework that formulates agent security as a process of cumulative security evolution. Inspired by how human societies transform experiences into transferable protective knowledge, EVOLVE externalizes security knowledge into executable guardrail tools that are continuously inherited, independently audited, and iteratively refined through lifelong interaction. Across multiple benchmarks, backbone models, and embodied environments, EVOLVE consistently outperforms existing defenses across diverse risk scenarios with +22\% average F1 score. We further validate the framework in real-world robotic and autonomous agent systems. Our results suggest that scalable

---

### [15] VeriHarm-Bench: Measuring Harmful Success in LLM Coding Agents Verifiably

**链接**: https://arxiv.org/abs/2611.03575
**作者**: Wei-Lin Chen, Zhepei Wei, Xinyu Zhu, Yu-Min Tseng, Tzu-Han Lin, Yu Meng
**来源**: cs.CL cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) coding agents increasingly operate with shell access, allowing them to write scripts, move files, alter permissions, and modify system configurations. However, an agent may achieve a user's goal while causing unintended harm, such as deleting unrelated files, weakening access controls, or corrupting data, in response to benign inputs without explicit jailbreaking. This failure mode is particularly important because apparent task success may reassure users that an agent behaved correctly, causing harmful side effects to go unnoticed. We call this harmful success: the agent successfully completes the intended benign task while simultaneously causing unintended harm. Despite its importance, harmful success is difficult to measure because conventional task-success metrics overlook harmful behaviors, while existing safety evaluations are often designed solely to assess harmful outcomes. We introduce VeriHarm, an automatic framework for constructing programmaticall

---

### [16] Can Large Language Model Agents Learn by Watching Tutorial Videos?

**链接**: https://arxiv.org/abs/2611.01460
**作者**: Haoyu Zhao, Zafeirios Fountas, Jun Wang
**来源**: cs.LG cs.AI cs.CL cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans continuously acquire knowledge from carefully crafted materials such as books and tutorial videos, carrying that understanding into future tasks. Millions of such instructional videos are uploaded online every day, yet LLM agents remain unable to exploit this ever-expanding wealth of human teaching. Their capabilities are frozen after training, while parameter updates at scale remain prohibitively expensive. This raises the central question: can LLM agents learn from this vast instructional resource without parameter updates? We introduce Tutorial Agentic Learning (TAL), a nonparametric continual-learning paradigm that consolidates tutorial videos into a persistent, structured tutorialbook memory through a two-stage adversarial process that harvests hard, video-grounded questions and uses them to refine the memory. At inference time, TAL retrieves through a Table-of-Contents (TOC) tree, tying retrieval directly to the model's reasoning rather than to embedding similarity. To stu

---

### [17] Reimagining Text-to-SQL: A Survey of Large Language Model Architectures and Strategies

**链接**: https://arxiv.org/abs/2611.00171
**作者**: Shikhar Dave, Bhaskarjit Sarmah, Stefano Pasquali
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-SQL systems translate natural language questions into executable SQL queries, democratizing access to relational data. Early approaches relied on handcrafted rules and template matching, while subsequent neural methods introduced encoder-decoder architectures, schema linking, and constrained decoding to handle increasingly complex queries. The emergence of large language models (LLMs), exemplified by systems such as ReFoRCE, Agentar-Scale-SQL, Snowflake's Arctic-Text2SQL-R1, and the modular XiYan-SQL framework, has dramatically advanced the field, pushing execution accuracy to new state-of-the-art levels on challenging benchmarks such as Spider, Spider 2.0, and BIRD. In parallel, modular frameworks decompose the task into sub-problems (schema retrieval, sketch-based generation, repair, and ranking), while agentic systems coordinate multiple specialized agents that communicate and dynamically allocate sub-tasks. This survey systematically reviews these LLM-driven approaches with

---

### [18] EEG-HealthLLM: Hierarchical Adaptation of Large Language Models for Unified Heterogeneous EEG Health Assessment

**链接**: https://arxiv.org/abs/2611.01652
**作者**: Ruidong Ma, Jisheng Dang, Ronghao Lin, Bimei Wang, Jingwen Zhao, Wenjun Ma 等 (10 人)
**来源**: cs.CL
**匹配关键词**: EEG, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) provides a non-invasive means for neurological and mental health assessment, yet existing EEG models are typically developed for individual tasks and are difficult to unify across heterogeneous signal configurations and assessment objectives. Large language models (LLMs) offer a common interface for multiple tasks, but adapting heterogeneous EEG signals to a shared LLM raises a key challenge: how to preserve task-specific signal characteristics while enabling effective language-side parameter sharing. To address this problem, we propose EEG-HealthLLM, a unified and parameter-efficient framework for heterogeneous EEG health assessment. We introduce an Asymmetric Hierarchical Adaptation Strategy: task-specific EEG adapters preserve heterogeneous spatio-temporal dynamics, while a unified shared LoRA is injected into the LLM backbone (e.g., Phi-3) to capture shared high-level assessment semantics across tasks. We further establish EEG-HealthBench by reorganizin

---

### [19] Illusion: Safeguarding Topology Confidentiality in LLM Multi-Agent Systems via Behavior-Preserving Obfuscation

**链接**: https://arxiv.org/abs/2611.00923
**作者**: Yiu-Fai Cheung, Hongzhi Guo, Miao Pan, Irwin King, Hao Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The communication topology of Large Language Model Multi-Agent Systems (LLM-MASs) governs how information propagates among agents and encodes critical domain knowledge and expert workflow design. It is valuable intellectual property and plays a decisive role in system utility and safety, yet remains vulnerable to inference attacks that stealthily reconstruct it from agent outputs. Existing defenses detect or mitigate such attacks but do not proactively conceal the topology itself. We propose \textit{Illusion}, a proactive topology obfuscation defense for LLM-MAS. \textit{Illusion} injects fake edges and fake messages to present attackers with a deceptive topology, while selecting low-impact candidates that preserve output-distribution equivalence and task-accuracy non-inferiority. The resulting fake edges are designed to be indistinguishable from genuine messages under black-box observation. Extensive experiments show that \textit{Illusion} reduces edge-level F1 from over 0.87 to 0.62 

---

### [20] AdKnob: Ad Intensity Control and Labeling for LLM-Native Advertising

**链接**: https://arxiv.org/abs/2611.00822
**作者**: Woo Jae Kim, Seongho Keum, Joonsung Jeon, Suhyeon Ha, Sooel Son, Sung-eui Yoon
**来源**: cs.AI cs.CY cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-native advertising has emerged as a viable monetization channel as LLM service providers seek sustainable revenue streams. However, integrating native ads into LLM responses introduces two largely understudied challenges: (1) controlling ad intensity -- how prominently advertising content appears -- and (2) ad labeling -- identifying which segments of the generated text constitute advertising. We propose AdKnob, a framework jointly addressing both challenges. For ad intensity control, we introduce new ad control tokens without pretrained semantic associations and align the model via direct preference optimization to generate ads at each desired level. For ad labeling, we propose an attention rollout-based attribution mechanism that identifies ad segments by tracing their attribution to input ad-related tokens, requiring no additional inference cost. We further construct MI-KnobSet, the first multi-level ad intensity preference dataset for LLM-native ads. Expe

---

### [21] Beyond Prompt Injection: The Tool Update Gap in LLM Agent Security

**链接**: https://arxiv.org/abs/2611.01976
**作者**: Shiyu Kan (1), Yue Qi (1), Yufei Han (2), Xinjian Luo (1), Guojun Xiong (1), Xiaofeng Gao (1) ((1) Shanghai Jiao Tong University 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model based agents increasingly rely on external tools to invoke services and interact with web resources. These tools can evolve through software updates, yet agentic frameworks may continue trusting them without re-verifying their safety after implementation changes. This tool update gap creates a supply-chain vulnerability in agentic systems: because updated tool code executes outside the LLM's context window, malicious functionality embedded in tool updates can bypass defenses centered on model-visible interactions, leaving agents exposed to stealthy, persistent threats that existing in-context defenses can hardly address. To thoroughly investigate this threat, we introduce ETUDE (Exploiting Tool Updates for Direct Execution), an attack that embeds malicious functionality into updates of initially benign tools to produce compromised tools, while preserving their legitimate tool functionality. Unlike prompt-based attacks, ETUDE operates entirely outside the LLM's cont

---

### [22] What Does a Safety Label Measure? Auditing Situational-Safety Benchmarks for Multimodal LLMs

**链接**: https://arxiv.org/abs/2611.01125
**作者**: Wayner Barrios, Kenneth Barrios
**来源**: cs.CV cs.AI cs.LG cs.MA
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Situational-safety benchmarks label each scene SAFE or UNSAFE and score a multimodal large language model (MLLM) against that label, usually by judging its free-form answer, and these scores guide deployment. We ask what such a label measures. A label score can come from the scene, the request or the benchmark's own files. We propose the Benchmark Card, seven measured fields that tell them apart, and fill it for six benchmarks. Only MSSBench chat leaks the label through its image files: image size alone reaches 82.3% accuracy, matching or beating six of seven commercial models. Elsewhere the signal outside the scene comes from design. In MOSSBench the item partition fixes the label, and on HoliSafe the request alone ranks pairs about as well as the scene. On our corrected chat split, the size rule falls to chance. We then introduce the Spot-Stop decomposition, which compares ranking with labelling on pairs of a safe and an unsafe scene. It splits the gap above a label-swap null into th

---

### [23] Discovering hierarchical governing equations for community-structured complex network dynamics with LLM agents

**链接**: https://arxiv.org/abs/2611.02816
**作者**: Jinlei Zhang, Zixuan Zhang, Hao Qiu, Feng Chen, Jiateng Yin, Xiaoyong Yan 等 (10 人)
**来源**: physics.soc-ph cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Governing equations provide an interpretable description of the mechanisms underlying complex network dynamics, yet their discovery from observational data remains challenging when shared community-level dynamics coexist with individual-level variations and the relevant functional structures may be absent from the initial candidate library or not explicitly specified in advance. Here we formulate this task as a hierarchical law-discovery problem and introduce SAGE, a large language model-guided self-reflective agent framework for discovering community-shared governing laws and individual-specific dynamical variations. SAGE organizes equation discovery into an iterative Library-Discovery-Review process that first identifies shared community-level structures and then resolves node-specific residual dynamics, while adaptively refining the candidate space to introduce missing dynamical terms when needed. This hierarchical and interpretable formulation enables SAGE to distinguish shared com

---

### [24] Keepace.ai: A Technical Report on a Large Language Model for Sports and Health

**链接**: https://arxiv.org/abs/2610.38249
**作者**: Keepace.ai Team, Bowen Wu, Heng Wang, Jufeng Mi, Kang Liu, Kun Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] AuthRank: Scoring Source Credibility to Counter Poisoning in CTI LLM Pipelines

**链接**: https://arxiv.org/abs/2510.20768
**作者**: Austin Jia, Avaneesh Ramesh, Zain Shamsi, Daniel Zhang, Alex Liu
**来源**: cs.CR cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Is That Clear? The Impacts of Clarifying Questions on Human-LLM Interaction

**链接**: https://arxiv.org/abs/2611.01087
**作者**: Chengbo Zheng, Yujie Zheng, Qian Zhu, Shuai Ma
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM assistants increasingly ask clarifying questions (CQs) to elicit preferences and tailor recommendations. Although prior work emphasizes improvements in answer quality and user experience, how CQs shape users' subsequent engagement and reliance remains unclear. We conducted a controlled experiment (N=180) across six everyday decision scenarios, comparing human-LLM interaction with and without CQs. We further manipulated whether responses violated explicit constraints and whether violations occurred in the sub-decisions the CQs addressed, while preserving elicited preferences. CQs increased perceived understanding and satisfaction, yet participants spent less time reviewing and evaluating responses and accepted more responses unchanged, including erroneous ones. Within the CQ condition, participants more often accepted responses containing CQ-adjacent violations than nonadjacent violations. These findings demonstrate that LLM's proactive CQs shape subsequent engagement and reliance w

---

### [27] BasisKV: Value Latents for Communication and Key Routing

**链接**: https://arxiv.org/abs/2611.02583
**作者**: Lixun Zhang, Zishan Shao, Kangning Cui, Yu Liang, Fan Yang, Yiran Chen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context large language model (LLM) inference is increasingly constrained by the cost of maintaining an ever-growing KV-cache. Low-rank K/V projections provide a promising way to compress the KV-cache with minimal quality loss, but prior work has largely optimized KV-cache compression in isolation, leaving distributed inference, especially with tensor parallelism where attention computation is partitioned across multiple GPUs, largely underexplored. We make two observations: (i) tensor-parallel communication is an important cost when deploying low-rank KV-cache compression in distributed inference; and (ii) Value compression can be associated with the output projection, allowing the same low-rank Value representation to reduce both Value-cache width and tensor-parallel communication. Based on these observations, we propose BasisKV, a low-rank KV-cache compression method for communication-intensive, long-context LLM inference. BasisKV jointly optimizes the low-rank factors across pe

---

### [28] PrismServe: Efficient LLM Serving on Heterogeneous Accelerator Clusters

**链接**: https://arxiv.org/abs/2508.09204
**作者**: Jinhao Zhang, Zicheng Yan, Boyang Zhang, Zeyu Liu, Daning Cheng, Yunquan Zhang 等 (8 人)
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] Step-dLLM: Adaptive Step-aware Sparse Attention for Efficient Diffusion LLM Inference

**链接**: https://arxiv.org/abs/2611.01320
**作者**: Zhichen Zeng, Xichong Zhang, Junpan Wu, Yifei Zuo, Chi-Chih Chang, Jiayi Wang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion large language models (dLLMs) generate tokens in parallel via iterative denoising, but their bidirectional attention prevents the KV caching used by autoregressive models and recomputes the full attention map at every step, incurring quadratic per-step cost. Existing sparse attention methods for dLLMs construct a sparse mask after an initial full-attention warm-up and reuse it for the remaining steps, while allocating the sparsity budget uniformly across heads. We argue both choices ignore key structural properties of attention in dLLMs: empirically, attention patterns are only locally consistent across steps and shift abruptly at certain transitions, and different heads concentrate their attention mass to very different extents. To this end, we design Step-dLLM, which periodically refreshes a block-sparse mask at anchor steps along the denoising trajectory and reuses it within each locally consistent interval, while employing a head-adaptive global budget that more aggressiv

---

### [30] Adaptive Localization of Knowledge Negation for Continual LLM Unlearning

**链接**: https://arxiv.org/abs/2611.02620
**作者**: Abudukelimu Wuerkaixi, Qizhou Wang, Sen Cui, Wutong Xu, Bo Han, Gang Niu 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the growing deployment of large language models (LLMs) across diverse domains, concerns regarding their safety have grown substantially. LLM unlearning has emerged as a pivotal approach to removing harmful or unlawful content while maintaining utility. Despite increasing interest, the challenges of continual unlearning, which is common in real-world scenarios, remain underexplored. Successive unlearning tasks often lead to intensified utility degradation. To effectively unlearn targeted knowledge while preserving LLM utility, it is essential to minimize changes in model parameters by selectively updating those linked to the target knowledge, thereby ensuring other knowledge remains unaffected. Building on the task vector framework, we propose a new method named ALKN (Adaptive Localization of Knowledge Negation), which uses dynamic masking to sparsify training gradients and adaptively adjusts unlearning intensity based on inter-task relationships. Comprehensive experiments across t

---

### [31] Temporary Authority, Permanent Effects: Commit-Time Authorization for LLM Agents

**链接**: https://arxiv.org/abs/2607.10487
**作者**: Igor Santos-Grueiro
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] ATTUNE: Agentic Throughput Tuning for LLM Training

**链接**: https://arxiv.org/abs/2610.17528
**作者**: Leo Fan, Hongyang Wang, Wenbo Chen, Jingguo Liu, Xian Li, Xuan Wang 等 (10 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Accelerating LLM Pretraining with Zeroth-Order Curvature on Idle Serving Compute

**链接**: https://arxiv.org/abs/2611.02688
**作者**: Mingchuan Ma, Dongqi Cai, Daqian Yang, Zhenyan Lu, Chen Chen, Teresa Lv 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM pretraining is increasingly compute-intensive, while substantial inference serving compute remains idle during off-peak periods. However, such serving hardware is difficult to use for conventional first-order training due to its memory, networking and other system requirements. Zeroth-order (ZO) optimization offers a natural interface to this forward-only compute resource, but its gradient estimates break down in pretraining. Unlike fine-tuning, which can confine updates to a small parameter subspace, pretraining must update every parameter, and the alignment of a ZO gradient estimate with the true gradient shrinks as the number of updated parameters grows. We make a different observation: noisy ZO estimates can still provide useful curvature information, even when they are too inaccurate to serve as gradients. Based on this insight, we propose ZO-Curv, which leverages idle forward-only devices to estimate curvature and uses it to adapt and refine the update used during first-order

---

### [34] Not All Reasoning Generalizes: A Case Study on Learning Generalizable Reasoning Strategies in RLVR

**链接**: https://arxiv.org/abs/2611.03627
**作者**: Ziqi Pang, Yu-Xiong Wang
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) can enable generalizable improvement for large language model (LLM) reasoning. This paper studies how to incentivize such generalization via reasoning strategies. We study this question with a controllable equation-solving framework: finding multiple inputs x for equations f(x)=y, where f is a non-bijective string function. This setting makes reasoning strategies observable while supporting a clear definition of easy-to-hard out-of-distribution (OOD) shifts, e.g., more solutions, longer y, etc. We uncover a subtle RLVR failure: it teaches the model to solve in-distribution tasks with high accuracy and structured step-by-step derivation, yet under OOD shifts, the same model abandons derivation and collapses to ineffective brute-force enumeration, causing sharp accuracy drops. This observation reveals the deeper challenges of RLVR generalization as it is neither incapable base model nor reward hacking, since the model succeeds in-dist

---

### [35] User Attributes and Political Ideology Shape LLM Receptiveness in Online Political Debates

**链接**: https://arxiv.org/abs/2611.02908
**作者**: Akram Elbouanani, Yousra Taleb, Gianluca Demartini, Adrian Popescu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online political discussions increasingly involve AI-mediated participation, as users invoke LLMs to assess contested claims, arbitrate disputes, and respond to opposing viewpoints. As these systems become participants in online exchanges, they may alter which speakers and argumentative strategies receive validation within the discussion. We study this interactional dimension by reconstructing 5,376 Debate.org debates as LLM conversations and running nearly 150,000 controlled multi-turn conversations that vary user political orientation, expertise, rhetorical strategy, and defended position, including conversations with competing users. Across naturalistic and controlled debates, we find that LLMs are systematically more receptive to left-leaning than right-leaning users. The asymmetry persists when users with different political orientations defend the same position and when opposing users appear in the same conversation, indicating that it is not fully explained by stance agreement o

---

### [36] From Local Skills to Long-Horizon Web Tasks: Progressive Skill Exploration for LLM Web Agents

**链接**: https://arxiv.org/abs/2611.03116
**作者**: Xueyang Feng, Xiaohe Bo, Xu Chen, Quanyu Dai, Feng Wen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are driving autonomous agents toward real-world environments, with the Web emerging as one of the most representative interaction scenarios. However, training Web agents with naive exploration remains challenging: successful trajectories are rare, and the sparse terminal rewards make it difficult for agents to obtain useful feedback from failed trajectories. Inspired by skill acquisition theory, we propose Skill-Composed Progressive Exploration (SCOPE), a short-to-long learning framework for long-horizon Web agents that decomposes complex task exploration into a gradual expansion process from local skills to complete task-solving capability. Specifically, SCOPE iteratively explores around local skills: Skill Discovery extracts reusable local skills and failure experiences from historical rollouts; Skill Orchestration composes discovered skills into high-level skill chains; and Skill Expansion leverages failure experiences aligned with the current skill chai

---

### [37] Reinforcement World Model Learning for LLM-based Agents

**链接**: https://arxiv.org/abs/2602.05842
**作者**: Xiao Yu, Baolin Peng, Ruize Xu, Yelong Shen, Pengcheng He, Suman Nath 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] The Cost of Mismatch: Noise Amplification in Zeroth-Order Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.03260
**作者**: Lianmin Chen, Junbin Qiu, Chenxing Wei, Yao Shu, Kun He
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zeroth-order (ZO) optimization has emerged as a promising approach for memory-efficient large language model (LLM) post-training, yet its reliable application to reinforcement learning with verifiable rewards (RLVR) remains largely unexplored. Motivated by the distinct data regimes of on-policy RL and fixed-data optimization, we develop a generic variance-theoretic framework to investigate what limits the reliability of ZO gradient estimation. Our analysis reveals that estimation reliability is structurally determined by whether the two finite-difference evaluations are performed on matched data. On-policy reinforcement learning (RL) under the mismatched-data regime produces a $1/\mu^2$ oracle-noise amplification that sets an irreducible noise floor as the perturbation scale $\mu$ decreases, whereas Boltzmann Targeted SFT (BOLT) under the matched-data regime eliminates this amplification via noise cancellation. We further derive convergence guarantees with explicit constants that clean

---

### [39] To Jev or Not to Jev: When Can System-1 Decision Models Replace LLM Judges?

**链接**: https://arxiv.org/abs/2611.00505
**作者**: Shreyas Subramanian
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision models such as TypeSafe's Jev answer typed questions about a text (yes/no, multiple choice, or an ordinal score) with calibrated probabilities in a single forward pass and without generating text, which makes them an inexpensive candidate for LLM-as-a-judge workloads. We evaluate 14 System-1 decision models, selected with a pre-stated protocol, against four generative judges (Claude Haiku 5.5, GPT-5.6 with and without reasoning, and Claude Opus 5.5 with thinking) on eleven established judge benchmarks. Five of the 14 are statistically indistinguishable from GPT-5.6 without reasoning on all five pairwise and best-of-4 benchmarks, and the two strongest, DReX-Max and d1-ultra, are significantly more accurate than Haiku on JudgeBench, LLMBar and RewardBench 2. Conditioned on a reference answer generated once per prompt, eleven models reach 90.3-93.4% on JudgeBench, statistically indistinguishable from Opus 5.5 and GPT-5.6 with reasoning, and on PPE best-of-16 every reference-guide

---

### [40] RubricWorld: World Model-Guided Rubric Optimization for LLM Graders

**链接**: https://arxiv.org/abs/2611.01986
**作者**: Hongji Pu, Hang Li, Yucheng Chu, Jiliang Tang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric optimization improves LLM grading by revising scoring instructions while keeping the grader's parameters fixed. Existing optimizers often judge edits by aggregate validation performance, limiting the supervision they retain about which errors an edit corrects or introduces. Testing each candidate also requires rescoring validation answers, which limits how many edits can be explored within a fixed budget. We propose RubricWorld, a framework that learns from previous edit evaluations to guide further search. Its world model predicts an edit's correction and degradation rates at score boundaries, conditioned on the current rubric state. The training signal comes from paired grading results: scores for the same answers before and after an edit. Predictions select one candidate for direct evaluation, and held-out confidence bounds determine whether it corrects enough target errors while keeping new errors within prespecified limits. Measured effects update the model even when the ed

---

### [41] Advances in Agentic Computer Graphics

**链接**: https://arxiv.org/abs/2611.01860
**作者**: Hengyu Liu, Jihyeon Je, Ruiqi Wang, Mingxuan Wu, Haven Feng, Qixing Huang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computer graphics is built on code. Large language model (LLM) agents can now generate graphics code and iteratively refine it through various feedback. This capability opens the door to a potentially new paradigm of computer graphics, with graphics algorithms increasingly built around agentic systems to automate progressively complex tasks. Over the past years, research on agentic graphics has expanded rapidly across a diverse range of tasks. This rapid growth makes it increasingly difficult for manual literature reviews to keep pace with new developments. At the same time, similar ideas are often described using different terminology across these tasks, further complicating efforts to develop a systematic understanding of the field. In this report, we address these challenges through two contributions. First, we introduce a unified taxonomy for characterizing agentic systems across diverse computer graphics tasks. Second, we develop an agentic literature system that can assist human 

---

### [42] Rank-Aware Differentially Private Release of Listwise Preferences for LLM Alignment

**链接**: https://arxiv.org/abs/2610.37682
**作者**: Junwei Chen, Manjiang Yu, Pengpeng Qiao, Yang Cao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Controlling Sharpening in LLM Post-Training

**链接**: https://arxiv.org/abs/2611.03146
**作者**: Simon Matrenok, Nicolas Menet, Nicolas Flammarion, Andreas Krause
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM post-training via reinforcement learning has shown consistent improvements in accuracy at the cost of reducing behavioral coverage - a phenomenon known as sharpening that can stall progress on difficult tasks. Repeated sampling objectives such as $\mathrm{pass@k}$ and $\mathrm{max@k}$ are known to mitigate sharpening, but the mechanism behind it remains poorly understood. Moreover, existing approaches for $\mathrm{@k}$ optimization use dedicated algorithms, and no general framework exists for adapting established policy optimization methods from $\mathrm{@}1$ to $\mathrm{@k}$. We derive the optimal policies for KL-regularized $\mathrm{pass@k}$ and $\mathrm{max@k}$ objectives in closed form. Our explicit solutions reveal that $\mathrm{@k}$ optimization naturally redistributes learning pressure based on prompt difficulty, directing it toward harder problems. Crucially, we show that standard $\mathrm{@}1$ objectives achieve these exact same optimal policies through prompt-adaptive reg

---

### [44] Jet-QSparse: Accelerating Agentic LLM Inference with 4-Bit Sparse Attention

**链接**: https://arxiv.org/abs/2611.01022
**作者**: Haozhan Tang, Hao Kang, Meng Lu, Yecheng Wu, Zerui Wang, Seokho Han 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon reasoning and agentic workloads strain KV-cache capacity and decode attention throughput. We present Jet-QSparse, a training-free method that combines compact NVFP4 cache storage with native FP4 query-key computation on Blackwell tensor cores. A dense scan scores the full key history and selects 128-token blocks for sparse FP16 value aggregation with FP32 accumulation, preserving higher precision in the output-forming step while enabling contiguous tile loads. Calibrated key centering and at most two BF16 pages per sequence and layer address quantization error; FP8 prefill uses a temporary arena while the persistent cache is packed directly from BF16 activations. Across four hybrid LLMs, a budget of 128 blocks per KV head shows no detected accuracy loss on the evaluated mathematical reasoning, coding, and agentic benchmarks, although some smaller budgets incur losses. With 64 blocks, Qwen3.8-27B achieves a $1.94\times$ end-to-end decode speedup over dense BF16 at 128K cont

---

### [45] Measure Before You Train: Typed Decision Models vs. a Classical Baseline vs. a Generative LLM for Routing a Personal Multilingual Inbox

**链接**: https://arxiv.org/abs/2610.32955
**作者**: Federico Lucca
**来源**: cs.CL cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Reasoning Consensus: Structural Ensembling of LLM Reasoning via Weighted DAG Aggregation

**链接**: https://arxiv.org/abs/2607.27783
**作者**: Amruta Parulekar, Jinu Lee, Dilek Hakkani-T\"ur, Hari Sundaram
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Architecting Fairness-Aware LLM Interactions

**链接**: https://arxiv.org/abs/2611.00723
**作者**: Alessandra Parziale, Valeria Pontillo, Fabio Palomba, Patrizio Pelliccione
**来源**: cs.SE cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used as decision-support tools but may generate stereotypical, discriminatory, or unfair responses. As LLMs become embedded in decision-critical software systems, fairness can no longer be treated as a downstream evaluation step, but must become an architectural concern of the interaction itself. Yet current fairness approaches operate as standalone evaluation techniques, lacking a reusable mechanism to verify and mitigate violations at runtime. We propose a fairness-assurance architecture grounded in three reusable design patterns, instantiated as a multi-agent framework that evaluates and iteratively refines LLM responses before delivery. A preliminary evaluation across eight configurations involving different LLM families shows that the architecture identifies fairness violations and iteratively produces compliant responses in all configurations, with behavior differing depending on the model-family composition. These results provide ini

---

### [48] MAServeBench: Benchmarking Multi-Agent LLM Serving Systems with Hierarchical Collaboration Workloads

**链接**: https://arxiv.org/abs/2610.40293
**作者**: Shengxuan Qiu, Haochen Huang, Shuzhang Zhong, Zizhuo Fu, Zebin Yang, Meng Li
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Evaluating Context Sensitivity of Collaboration Behavior in Multi Party Simulation Frameworks

**链接**: https://arxiv.org/abs/2611.00089
**作者**: Anvesh Rao Vijjini, Sheshera Mysore, Pegah Jandaghi, Ashish Sharma, Snigdha Chaturvedi, Bahareh Sarrafzadeh
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group Social Behavior is increasingly used as a lens to study Large language model (LLM) simulations to aid model training and evaluation. However, little prior work has examined how contextual factors such as team size and goal type manifest in long running simulations. To overcome this gap, we conduct a controlled, full-factorial study examining how contextual factors affect collaboration behavior across multi-party simulation frameworks. Using well established social science taxonomies, we quantify context sensitivity of collaboration behavior in simulated teams. Our analyses reveal significant effects of contextual factors such as simulators consistently favor smooth collaboration over disagreement, negotiation pressure, and coordination breakdown. These findings provide the first systematic evidence of how contextual factors influence emergent collaboration in LLM based multi-party simulation frameworks, offering both guidance and empirical results for the use of such simulations.

---

### [50] trajectory-judge: What Outcome-Only LLM Judges Miss on Agent Trajectories

**链接**: https://arxiv.org/abs/2609.00038
**作者**: Hadi Mohammadi
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] When Does Multi-Agent RL Improve LLM Workflows? Workflow, Scale, and Policy-Sharing Tradeoffs

**链接**: https://arxiv.org/abs/2605.24202
**作者**: Yifan Zeng, Yiran Wu, Yaolun Zhang, Wentian Zhao, Kun Wan, Qingyun Wu 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] Log-Driven Semantic Tuning for Mixed Integer Programming Solvers

**链接**: https://arxiv.org/abs/2611.00621
**作者**: Zhengzhong Ricky You, Kaizhao Sun, Zeping Min, Wotao Yin, Xinshang Wang
**来源**: math.OC cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated configuration of mixed-integer programming (MIP) solvers largely relies on black-box optimization. Each trial requires an expensive solver run and provides only a scalar outcome, so tuning can require many such evaluations. Human experts take a different approach. They inspect solver logs, identify performance bottlenecks, and adjust the parameters that address them. We propose Log-Driven Semantic Tuning (LDST), which uses a large language model (LLM) to automate this process. LDST extracts compact diagnostics from solver logs, uses the LLM to propose sparse edits to the current best configuration based on parameter meanings and observed solver behavior, and validates each proposal before execution. A regime-adaptive objective selects the tuning signal according to the information available from a time-limited run, while a log-based completion signal estimates completion time from branch-and-bound tree growth recorded in ordinary solver logs, so that solved and unsolved runs 

---

### [53] Large Language Model Guided Self-Debugging Code Generation

**链接**: https://arxiv.org/abs/2502.02928
**作者**: Muntasir Adnan, Zhiwei Xu, Carlos C. N. Kuhn
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Style over Substance? Linguistic Bias in LLM-based Peer Review

**链接**: https://arxiv.org/abs/2610.35254
**作者**: Sai Suresh Macharla Vasu, Sumedh Santosh Joshi, Philipp Christmann, Ivaxi Sheth, Ruta Binkyte, Koel Dutta Chowdhury 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Rethinking LLM Pruning via Test-Time Scaling

**链接**: https://arxiv.org/abs/2611.01133
**作者**: Mingyang Song, Mao Zheng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured pruning reduces the size of large language models, often at the cost of lower accuracy. Whether this decline reflects diminished reasoning capacity or greater difficulty in sampling correct solutions is less clear. We examine this question across expert, FFN and layer pruning on four mathematical and coding benchmarks, comparing original and pruned models through pass@k at matched sampling budgets. Even after substantial pruning, some models match or exceed the original model's reasoning coverage despite lower pass@1, and solve problems left unsolved in the original samples. Retaining broad coverage, however, does not mean that correct solutions remain easy to obtain. Under severe pruning, diverse generated chain-of-thought (CoT) traces can coexist with increased repetition and less reliable generation. As correct answers become harder to sample, the additional attempts can sharply increase total token use even when individual responses become shorter. This separation betwee

---

### [56] Dynamic Mixed-Precision Routing for Efficient Multi-step LLM Interaction

**链接**: https://arxiv.org/abs/2602.02711
**作者**: Yuanzhe Li, Jianing Deng, Jingtong Hu, Tianlong Chen, Song Wang, Huanrui Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] Conversational Interaction for LLM-Based Clinical Text-to-SQL: A User Study with Healthcare Professionals

**链接**: https://arxiv.org/abs/2611.00605
**作者**: Jun-Min Lee, Suyoung Yoo, Gyubok Lee, Edward Choi, Meong Hi Son
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational text-to-SQL interfaces could give healthcare professionals natural-language access to electronic health record (EHR) data, but evidence for their real-world usability remains limited: prior evaluations have relied largely on curated benchmarks with fully specified questions or on simulated users. We report a user study in which 14 physicians who regularly work with EHR data used both a single-turn and a conversational multi-turn text-to-SQL interface over the MIMIC-IV database in a within-subjects design; dialogue analyses additionally drew on interaction logs from 21 healthcare professionals across the main study and two pilot studies. The conversational interface was consistently favored: mean System Usability Scale scores rose from 68.2, near the industry average, to 85.9 (p<0.001), with significant advantages across technology-acceptance constructs including performance expectancy, effort expectancy, self-efficacy, and behavioral intention. In post-study forced-choic

---

### [58] Probing the Limits of the Lie Detector Approach to LLM Deception

**链接**: https://arxiv.org/abs/2603.10003
**作者**: Tom-Felix Thormann
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Don't Guess, Ask Wisely: Benchmarking and Training Proactive Elicitation in Open-Domain LLM Conversations

**链接**: https://arxiv.org/abs/2611.01878
**作者**: Rongyu Zhang, Mutian Bao, Jinjian Zhang, Yuetian Du, He Xu, Wei Zhou 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When user queries are incomplete, large language models should ask targeted questions before committing to an answer, a capability we call proactive elicitation, yet evaluation on real user-assistant queries across seven LLMs (8B to frontier) shows that fewer than 11% of underspecified queries trigger a follow-up question. To benchmark and train this capability, we introduce VagueBench, where each seed query is annotated with structured intent and detail units then degraded into intent-vague and fully-vague variants via controlled removal of linguistic cues, yielding known hidden information sets for evaluating both when and what to ask. We propose DialogGRPO, an offline reinforcement learning method that organizes multi-turn elicitation as a dialogue-state directed acyclic graph, where candidate questions at each node receive dense turn-level rewards combining immediate information gain with lookahead value through group-relative comparison, enabling fine-grained credit assignment wit

---

### [60] Precedent Labels and Facts Shift LLM Approval Decisions in Opposite Directions

**链接**: https://arxiv.org/abs/2611.00672
**作者**: Junwei Yao, Zike Yang, Yongxi Zhou, Yanxian Chen, Jianan Liu, Jiaxi Wen 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a language model decides refund or claim requests under written policies, the system can show it similar past cases. Each past case has two parts: its facts and the decision recorded for it. We separate the two. A model sees a policy, a request and three past cases, and we change either the recorded decisions or the facts, keeping the request fixed. We select requests that are close calls: deciding without past cases, DeepSeek V4.1 Flash approved each in some of four tries and denied it in others. When the past cases are near-copies of the request (its facts with a few details changed), switching their recorded decisions from DENY to APPROVE raises approval by about 30 to 55 percentage points in DeepSeek V4.1 Flash, GPT-5.6 Luna and Claude Haiku 5.5 on policies written for the study, and DeepSeek and Luna show the same on nine public policies paraphrased from real ones. The facts push the other way: shown without their recorded decisions, past cases whose facts support approval ma

---

### [61] ClickSight: An LLM Framework for Interpreting Student Clickstreams Through Learning Strategies

**链接**: https://arxiv.org/abs/2611.02021
**作者**: Bahar Radmehr, Lan Tran, Ekaterina Shved, Fatma Bet{\"u}l G{\"u}re\c{s}, Adish Singla, Tanja K{\"a}ser
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital learning environments produce rich clickstream data that can reveal how students approach learning tasks, yet interpreting these fine-grained traces often requires substantial expert effort. We introduce ClickSight, a framework for interpreting student clickstreams through learning strategies defined in the literature. Given a student clickstream and a predefined set of learning strategies, ClickSight uses a staged LLM-based pipeline to identify strategy-relevant evidence, assess adherence to each strategy, and generate an evidence-grounded interpretation of the student's behavior. We evaluate ClickSight across two learning environments, 365 students, and 12 model backbones using an expert-grounded quality rubric and an LLM judge calibrated with human-expert ratings. Our results show that ClickSight can generate high-quality strategy-based interpretations across different models and environments, with reasoning models performing more consistently than instruction-tuned counterp

---

### [62] NEIGHBOR: Aligning Service Behaviour and Evidence Use in an LLM Agent for Community Resident Services

**链接**: https://arxiv.org/abs/2611.01836
**作者**: Zongyou Yang, Yinghan Hou, Xiaokun Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Residents who contact a community service desk about a repair or a service charge need answers they can act on, with facts that hold for their case and commitments the desk can keep. In tool-augmented LLM agents, such facts come from documents and records, and the conduct of a service answer is usually specified in a system prompt. We present NEIGHBOR, an LLM agent for community resident services that trains this conduct into the model that drives its tools. NEIGHBOR is deployed on a live resident-service platform for a district of an East Asian city of more than ten million people. It adapts Qwen3-235B-A22B with LoRA on 7,824 supervised fine-tuning examples built from public community-service materials around six service-behaviour targets, among them commitment control and human referral, and the adapted model plans document retrieval and read-only text-to-SQL over the resident's own records. In an offline evaluation with seven configurations, an independent domain expert rated all 35

---

### [63] Concept-Guided Prompting Strategies Increase Diversity in LLM-Generated Recipe Populations

**链接**: https://arxiv.org/abs/2611.01171
**作者**: Stuart Farmer
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Novelty in solution generation supports automated discovery, but LLM outputs can remain repetitive. To address this, we propose a simple concept-guided prompting method that generates thematic concepts before responses within each of these concepts. To demonstrate, we generated 1,000 recipes for a recipe book task and compared the results against a human-authored corpus. Two naive prompting strategies were compared as baselines. Concept-guided prompting outperformed both baselines in all cases and reached semantic coverage of 47.0% versus 35.1% and 13.1% in respective prior-title and nonce prompt strategies. These findings suggest broader population exploration and diversity, but remain contained to this specific task. Further work is needed to determine the quality of solutions and generalizability.

---

### [64] ORCA: The Annealed Spectral Conditioning Optimizer for Faster, Better LLM Training

**链接**: https://arxiv.org/abs/2610.06116
**作者**: Yuanshi Liu, Boyuan Jiang, Liang Hou, Xin Tao, Pengfei Wan, Zhouchen Lin 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] VerifierBench: Benchmarking the Generation of Executable Verifiers for LLM Agents

**链接**: https://arxiv.org/abs/2610.28679
**作者**: Jianing Yin, Ziyi Chen, Hao Wang, Yiyou Sun, Zijian Jin, Dawn Song 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] VoirDire: Counterfactual Calibration for Reliable LLM-as-a-Judge Aggregation

**链接**: https://arxiv.org/abs/2611.00491
**作者**: Changho Shin, Frederic Sala
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge systems often aggregate multiple judges to improve evaluation reliability. However, judge agreement can reflect shared biases toward verbosity, formatting, or fluency rather than the intended evaluation target. Addressing these shared biases is challenging because observational judge outputs alone cannot distinguish agreement driven by target quality from agreement driven by nuisance attributes. We introduce VoirDire, an intervention-calibrated aggregation method for LLM-judge panels. VoirDire applies controlled interventions that vary specified surface attributes while aiming to preserve the evaluation target; it then uses paired changes in judge scores to identify nuisance-sensitive directions. It attenuates these directions and selects aggregation weights that retain variation across items while penalizing sensitivity to the interventions, making the final consensus less dependent on superficial features. We show theoretically that observational judge outputs alone ca

---

### [67] Understanding, Predicting, and Steering LLM Behavior via Representational Effective Theory

**链接**: https://arxiv.org/abs/2605.09294
**作者**: Muhammed Ustaomeroglu, Guannan Qu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] RCR-Router: Efficient Role-Aware Context Routing for Multi-Agent LLM Systems with Structured Memory

**链接**: https://arxiv.org/abs/2508.04903
**作者**: Jun Liu, Zhenglun Kong, Changdi Yang, Fan Yang, Tianqi Li, Peiyan Dong 等 (10 人)
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] AgenticMobility: An Open-Source Platform for Multi-AI-Agent Mobility Dynamics

**链接**: https://arxiv.org/abs/2611.01918
**作者**: Jiaheng Xiao, Jiangtao Han, Jiachen Wang, Honghai Li, Lijun Sun, Kay Axhausen 等 (8 人)
**来源**: cs.MA cs.AI physics.soc-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding mobility dynamics and the effects of urban transportation management policies requires examining how individual travel decisions, traffic conditions, and policy interventions influence one another over time. We present AgenticMobility, an open-source experimental platform for studying how mobility AI agents and other AI agents interact, adapt through repeated experience, and collectively shape mobility outcomes. Persistent agents retain identities and relevant states across rounds, with explicit interfaces defining information access, admissible actions, and decision schedules; linked records trace decisions, execution, and feedback. In the current implementation, large language model (LLM) agents act as travelers choosing routes and departure times and as a manager periodically adjusting link charges within MATSim. A preliminary demonstration spans 100 simulated days in each of five configurations, with one run per configuration and a shared simulation seed. In the joint

---

### [70] LARK: Lean-Assisted Reasoning for LLM-Generated GPU Kernels

**链接**: https://arxiv.org/abs/2611.02028
**作者**: Zixi Zhang, Jiayi Nie, Haoran Wu, Yujie Yan, Yann Herklotz, Rika Antonova 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient GPU kernels are typically low-level and hardware-specific, and LLM agents can now generate them faster than experts can verify. Existing approaches rely on testing, which provides evidence but not a guarantee of correctness. We introduce LARK, an agentic framework that automatically and formally verifies GPU kernels against their PyTorch reference implementations. LARK proves equivalence in functional and memory behavior under exact arithmetic and establishes a new trust boundary: human effort is only needed to verify operator-level Lean semantics ahead of kernel generation time, instead of checking every single line of generated code. LARK formalizes the GPU machine model and the semantics of each operation in Lean 4 once per target language, and the Lean 4 semantics of any incoming kernel is derived from these pre-built definitions. LLM agents then automate the proof in two steps. First, an agent decomposes the whole kernel semantics into smaller segments and Lean 4 verifie

---

### [71] HiGenTrans: Hierarchical LLM Knowledge Transfer for Generative Recommendation

**链接**: https://arxiv.org/abs/2611.01129
**作者**: Zhuohang Jiang, Yuxin Chen, Haohao Qu, ZeFei luo, Yunlong Wang, Xu Yuan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative recommendation promises to simplify conventional multi-stage recommender systems by generating item Semantic IDs (SIDs) autoregressively. However, two obstacles limit its effective- ness in industrial settings: interaction-only supervision underuses the semantic knowledge encoded in pretrained language models, while beam-search likelihood ranks token sequences rather than directly estimating item relevance. To address these limitations, we propose HiGenTrans, a three-level framework that introduces LLM knowledge at the input, representation, and decision levels. First, Global Semantic Priming (GSP) adds an LLM-derived user representation to the beginning-of-sequence embedding, provid- ing a semantic prior before SID generation. Second, Hierarchi- cal Representation Transfer (HRT) aligns intermediate LLM representations with depth-matched GenRec layers through mean- centered projections and gated residual connections. Finally, Multi- Signal Decision Calibration (MDC) uses a l

---

### [72] Robustness Starts with the Objective: Designing and Certifying Robust LLM-Generated Heuristics

**链接**: https://arxiv.org/abs/2611.00504
**作者**: Pantea Karimi, Roozbeh Bostandoost, Dany Rouhana, Siva Kesava Reddy Kakarla, Pooria Namyar, Mohammad Alizadeh 等 (8 人)
**来源**: cs.AI cs.CL cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used to design heuristics for computer systems. However, most synthesis frameworks evaluate candidates by their average performance, which can mask severe regressions on specific workloads. Even adding adversarial training inputs doesn't eliminate these regressions, and percentile objectives (e.g., optimizing for the 95th percentile) overlook how severe regressions can be beyond the selected threshold. We present TAILOR, a framework that guides LLM synthesis using the Conditional Value at Risk (CVaR) of the cost difference between each candidate and an existing baseline on the same workload. This paired CVaR measures the average difference over the worst fraction of workloads. We show that a negative paired CVaR guarantees improvements in both average performance and tail optimality gap relative to the unknown optimum, without ever computing that optimum. We find that TAILOR achieves the best mean--tail trade-off among the synthesis objectives we evaluate across t

---

### [73] Kerkoporta: Injecting Structured-Output Backdoors in Reasoning Coding Agents

**链接**: https://arxiv.org/abs/2611.00138
**作者**: Georgios Syros, Blake Bullwinkel, Alina Oprea, Cristina Nita-Rotaru, Amanda Minnich, Xiaodong Liu 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing large language model (LLM) backdoor attacks operate primarily in chat settings, where the risk is bounded by free-form text outputs. AI agents remove that bound by performing actions and executing commands on the user's machine. We introduce structured-output backdoor attacks against reasoning models in agentic coding settings. A trigger placed anywhere in the agent's context causes the model to emit an attacker-chosen tool call, which the harness executes, directly compromising the system's confidentiality, integrity, or availability. We present Kerkoporta, a methodology that constructs high-quality poison samples, injects the backdoor via supervised fine-tuning, and recovers utility loss with lightweight reinforcement learning. We evaluate on modern, heavily post-trained open-weight models across proprietary and open-source harnesses, focusing on coding for its wide adoption and long-horizon task structure. The attack reaches success rates of up to 96.2% and can be configure

---

### [74] A Multi-Instance LLM Framework for Rating the Quality of Surgical Feedback

**链接**: https://arxiv.org/abs/2605.25440
**作者**: Rafal Kocielnik, J. Everett Knudsen, Steven Y. Cen, Jasmine Lin, Cherine H. Yang, Atharva Deo 等 (10 人)
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] What Do LLM Judges Actually Verify? Matched Controls and Record Gaps for Document Currency

**链接**: https://arxiv.org/abs/2611.01311
**作者**: Unnati Shah, Samruddhi Kakade, Aum Patel
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges often check, against an amendment record, whether the documents an answer cites are still in force. Such records are rarely complete. From a table of replacements, our test generates matched answers citing a replaced document, its successor, the replaced document before its replacement, and an older document that a newer one updated without replacing; it removes links from the record and scores each finding by its stated reason. On 48 replacements from the IETF RFC index, judges given a correct record caught nearly every replaced citation, as a lookup would. On the 24 faults whose link we removed, every judge caught more from the texts alone than with the record: Gemini 3.1 Pro 23/24 against 1/24, GPT-5.5 23/24 against 9/24, Claude Opus 4.5 17/24 against 9/24 and Gemma 4 26B 13/24 against 0/24. The drop recurred on a second draw of removed links. Most misses carried no finding; in an exploratory run with a conflict code, only Gemini used it often. Rewording the gap as "no re

---

### [76] ElectroChemLLM: A Multimodal LLM Pipeline for High-Fidelity Electrochemical Informatics

**链接**: https://arxiv.org/abs/2611.00638
**作者**: Dikshya Mohanty, Manoj Praveen Nandigama, Kuldeepsinh Raj, Sourav Kanti Maiti, Jiannan Yang, Ruiqi Luo 等 (10 人)
**来源**: cs.CL cs.DB cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electrochemistry is central to solving many modern-day challenges, including energy storage systems for a sustainable future, and its advancement relies heavily on the data from past findings. Existing automated pipelines are limited by text-only architectures, context fragmentation, and numerical hallucinations - collectively preventing accurate, large-scale curation of property databases. We introduce ElectrochemLLM, a multimodal information extraction pipeline that jointly identifies structured electrochemical records encompassing electrolyte compositions, electrode materials, cell configurations, and their measured physicochemical properties from unstructured scientific PDFs at scale. By combining hybrid document parsing with vision-capable LLM orchestration, the pipeline extracts verifiable, structured data across text, tables, and figures. Evaluated on the battery-electrolyte subset of our manually annotated benchmark of 232 papers, ElectrochemLLM achieves an F-1 score of 0.97, a

---

### [77] "I Wrote, I Paused, I Rewrote": A Mixed-Methods Study of Learner Perceptions of Process-Aware LLM Feedback

**链接**: https://arxiv.org/abs/2611.00009
**作者**: Samra Zafar, Shifa Yousaf
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly provide formative writing feedback, but most systems evaluate only the submitted text. Process-aware systems can additionally incorporate intermediate drafts and interaction records, yet access to these traces does not establish whether learners perceive the resulting feedback as useful, fair, or aligned with their own revision experience. We conducted a convergent mixed-method post-task evaluation with 43 undergraduate English-language learners. Participants completed a timed essay, received LLM-generated feedback based on the final essay, intermediate snapshots, and keystroke-derived records, and then answered six five-point Likert items and four open-ended questions. Ratings were concentrated above the neutral midpoint across all six items. Between 74.4% and 95.3% of participants selected ratings of 4 or 5, and all six one-sided exact sign tests remained significant after Holm correction. Perceived correspondence between the revision analysis and t

---

### [78] LLM-Augmented Agent-Based Simulation of Cyber Social Agents

**链接**: https://arxiv.org/abs/2610.32988
**作者**: Lynnette Hui Xian Ng, Kathleen M. Carley
**来源**: cs.MA cs.AI cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Creating Hybrid Interactive Narrative Systems with LLM: From Formal Description to Evaluation

**链接**: https://arxiv.org/abs/2611.02807
**作者**: Jules Clerc (Heudiasyc), Domitile Lourdeaux (Heudiasyc), Mohamed Sallak (Heudiasyc), Marc Ravaine
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interactive narratives let users shape a story while an Experience Manager (EM) keeps it coherent, balancing player freedom against authorial control. Large Language Models now enable a new generation of hybrid EMs, which combine run-time generation from free-text input with symbolic narrative control. However, their heterogeneity makes them hard to compare: A manager's behaviour is generally tied to the unique and specific scenario in which it operates, and much of its decision-making takes place outside of any explicit and verifiable structure. We address this with an LLM-based narrative platform whose managers are interchangeable modules operating over a shared symbolic world model of facts, operations, and goals. Because every applied operation carries explicit preconditions and effects, each session can be analysed as a plan through a common state-transition representation and evaluated, independently of how the manager works internally, with shared indicators of four properties: 

---

### [80] MemShift: Separating Detection from Repair in LLM-Derived Personal Memory

**链接**: https://arxiv.org/abs/2611.02338
**作者**: Zichuan Xu, Haochen Zhang, Yuyang Dong, Makoto Onizuka, Chuan Xiao
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI assistants store values that a language model derived from a person's records under the person's own definitions, such as their important contacts. Keeping such a value correct takes two steps: detection, noticing that an input changed, and repair, producing the correct new value. Benchmarks that score only the final answer cannot tell which step failed, and they state every change as new text. Seeing this limitation, we present MemShift, a benchmark of five shifts: source revision, deletion, redefinition, writer switch, and export. The first three fork a synthetic world into branches that differ only in the shift. Gold values and dependencies are fixed before any text, and a deterministic scorer replaces an LLM judge. For a memory that reports its invalidations, MemShift shows for each changed item whether the memory noticed the change and whether its repair was right. Moreover, we build a reference memory with known detection and repair to validate the measure. By evaluating four 

---

### [81] Selecting LLM-Generated Hypotheses Raises Truth Beyond What an LLM Panel Expects: A Pre-registered Study on NAS-Bench-201 and HPOBench

**链接**: https://arxiv.org/abs/2611.00643
**作者**: Shanglin Yang, Zhan Shi
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM research-ideation systems aim for hypotheses that are both true and non-obvious, yet neither property can normally be checked. We build a testbed in which both can. Generators propose conditional interaction claims about two fully tabulated benchmarks, NAS-Bench-201 and HPOBench; every claim is verified exactly against the tables, and its non-obviousness is scored against a calibrated blind prior elicited from other LLMs. Excess truth measures how much more often a run's claims hold than this panel expects. Across a series of pre-registered stages with Claude and GPT generators, our main positive result is a simple two-stage step found by a harness optimizer: draft a large pool of claims, then select a subset in a separate call. For Sonnet on NAS-Bench-201, this step raised excess truth in every pre-registered test, including against a same-pool ablation that keeps only likely-true claims, without lowering precision. The gain comes both from credit for true claims and from avoiding

---

### [82] Revisiting LLM Homogeneity Through a Multidimensional Lens

**链接**: https://arxiv.org/abs/2611.01549
**作者**: Ziliang Qiu, Renfen Hu, Yi Ding, Ted Underwood
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Concerns about LLM homogeneity are typically quantified with embedding similarity, which reduces two texts to a single score. We revisit homogeneity with 25 interpretable metrics spanning five dimensions: semantic, lexical, syntactic, structural, and stylistic & presentational. A human study shows that perceived similarity depends on both content (what responses say) and form (how they say it), yet embedding similarity correlates less with human meaning judgments than sentence-level matching ($\rho=0.417$ vs. $0.606$) and not significantly with form judgments ($\rho=0.140$). Across 18 contemporary LLMs, models say similar things in different words: they share global semantics and broad linguistic profiles but remain distinct in lexical characteristics, structural patterns, and interactional conventions. Across releases from 2024 to 2026, models become more like themselves but not more like one another: among significantly changing metrics, intra-model distances decrease for 17 of 22, a

---

### [83] Does reflective LLM feedback survive a wet-lab-scale label budget?

**链接**: https://arxiv.org/abs/2611.01908
**作者**: Haoxuan Zeng, Xin Luo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can reflective language-model feedback improve a biological predictor when each cycle buys only one plate of labels? We separate three possible sources of benefit: proposing model edits, choosing measurements, and revising decisions through repeated feedback. We replay $36$ ProteinGym assays, starting with $96$ labels and acquiring $96$ per round for six rounds, with a sealed test set and a shared edit schema. The pre-specified comparison of full LLM control against random edits detects no advantage in test rank correlation ($\Delta z=-0.008$, $95\%$ CI $[-0.034,+0.018]$); equivalence is also unestablished. Exploratory ablations nevertheless identify useful model editing. With random acquisition fixed, LLM edits improve Fisher-transformed test Spearman by $0.043$ over no edits; with acquisition fixed to upper confidence bound, they improve normalized top-variant recovery by $0.023$. LLM acquisition alone does not detectably outperform fixed adaptive rules, and repeated feedback does no

---

### [84] DistDebug-Bench: Can LLM Agents Diagnose Bugs in Distributed Systems?

**链接**: https://arxiv.org/abs/2611.03523
**作者**: Yuxuan Jiang, Chenglin Liu, John Rose, Mason Miller, Ruthesh Thavamani, Juntao Wu 等 (9 人)
**来源**: cs.SE cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents show strong potential in software engineering tasks such as competitive programming and code synthesis. Existing benchmarks, however, largely focus on small-scale settings such as self-contained Python modules, leaving distributed systems, an essential class of production software, under-examined. We introduce DistDebug-Bench, a benchmark for evaluating agents' ability to diagnose complex-system failures at the code level. It curates 120 high-quality real-world bugs from 11 widely used distributed systems, spanning 5 programming languages and 10 failure patterns. Through an extensive evaluation of state-of-the-art LLMs and agents, we identify substantial gaps between current agents and real-world debugging tasks. A recurring gap is tunnel vision due to a lack of explicit reasoning structure and nondeterminism from inconsistent tool-use scope. The benchmark and evaluator are available at https://github.com/OrderLab/distdebug-bench, with agent traces and a leaderboard at https

---

### [85] Same Outputs, Different Scores: Auditing the Unchecked Graders of Multimodal LLM Benchmarks

**链接**: https://arxiv.org/abs/2611.03377
**作者**: Ahmad Jarjis Hasan, Jonathan Lwowski
**来源**: cs.AI cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Every multimodal-LLM multiple-choice benchmark ends with a scoring rule that converts a model's response, often free-form text rather than a clean option letter, into a right/wrong verdict, buried in its code. Unlike the dataset, this rule is chosen without justification and left unexamined, yet it sets the published number. We reproduce the official scorers of eight peer-reviewed benchmarks on five open vision-language models (VLMs) that fit a single 16 GB GPU, and introduce a blinded human-plus-LLM-judge adjudication (Cohen's kappa=0.956) that recovers what the model actually answered. The scoring rule alone moves accuracy by up to 22 points on identical outputs, yet exactly 0 wherever a model emits clean option letters, so it hides on strong-model leaderboards. It is the fallback and not the rambling that does the damage: the benchmark with the highest non-compliance we measure has an artifact of exactly zero, because its scorer abstains instead of guessing; a reasoning model with n

---

### [86] RogueMerge: Robust and Unified Attacks against LLM Model Merging

**链接**: https://arxiv.org/abs/2606.03344
**作者**: Jinghuai Zhang, Yetian He, Kunlin Cai, Han Zhao, Fnu Suya, Yuan Tian
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] Distance Is Not Enough: Forget-Retain Alignment Gap Predicts LLM Relearning Robustness

**链接**: https://arxiv.org/abs/2608.25429
**作者**: Yi Chen, Hanna Hsieh, Shuhong Liu, Chuanbo Hua, Zihan Ma, Kun Wang 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] As Expected? Efficient LLM Planning via Expectation-Observation Consistency Verification

**链接**: https://arxiv.org/abs/2611.02438
**作者**: Qingfu Zhu, Huanyang Zheng, Ting Liu, Wanxiang Che
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM planning often relies on reactive executors (e.g., ReAct) that generate a single action at each step to remain grounded in the latest observations, incurring substantial inference cost. Batched executors reduce this cost by predicting multiple actions in a single model invocation, yet they are prone to compounding errors, as intermediate observations are ignored. We propose an expectation-observation consistency verification (EOCV) mechanism for batched executors, preserving grounding while improving efficiency. The mechanism generates expectations of action outcomes and compares them with the resulting observations. Consistency permits continued execution, whereas mismatches trigger early termination and replanning from the current observation. Experiments on text-based and multimodal benchmarks across multiple backbones show broadly comparable average task performance between EOCV and reactive executors, with a 29-35% reduction in average weighted token usage. Moreover, the mecha

---

### [89] Multi-Turn Semantic Caching for Low-Cost LLM Serving

**链接**: https://arxiv.org/abs/2611.01077
**作者**: Baran Atalar, Selly Beyene, Xutong Liu, Carlee Joe-Wong
**来源**: cs.LG cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic caching lowers the cost of serving large language models (LLMs) by reusing stored responses for similar requests. In multi-turn conversations, whether a cached response is acceptable depends on both conversations' histories, which embedding similarity of requests and histories predicts poorly (AUC 0.62--0.74 on five workloads). We therefore learn the \emph{reuse risk}, the probability that a cached response is unacceptable, from judge feedback, and choose a budgeted set of conversation states to cache by weighing the generation cost a reuse avoids against a price for unacceptable reuse. We propose CUCB-SC-MT, which learns a cache from logged conversations with a suboptimality guarantee, and CLCB-LS-MT, which learns online and has $\tilde O(\sqrt N)$ regret over $N$ requests when conversation states recur. On math-tutoring (SocraTeach) and movie-ticketing (Taskmaster-3) conversations, both achieve lower loss than prior semantic caching approaches: ContextCache, multi-turn varia

---

### [90] Aligned Alone, Misaligned Together: Forecasting Adversarial Capture in LLM Agent Populations

**链接**: https://arxiv.org/abs/2608.22444
**作者**: Isotta Magistrali and Chen Shani
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] MoBiQuant: Mixture-of-Bits Quantization for Token-Adaptive Any-Precision LLM

**链接**: https://arxiv.org/abs/2602.20191
**作者**: Dongwei Wang, Jinhee Kim, Seokho Han, Denis Gudovskiy, Yohei Nakata, Tomoyuki Okuno 等 (10 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] Late Autumn: LLM Agents Specialize a General Multi-Robot Planner for One Warehouse

**链接**: https://arxiv.org/abs/2611.02391
**作者**: Yimin Tang, Han Zhang, Shao-Hung Chan, Erdem B{\i}y{\i}k, Sven Koenig, Jingkai Chen
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> No algorithm is best on all problems, but a real warehouse is a narrow problem: its layout and processes rarely change. Operators still run one general multi-robot planner at many sites, because experts cannot tune it for each one. In this work, which we call Late Autumn, we explore whether LLM coding agents running autonomous research can specialize a general planner for one site, trading generality for throughput, much as post-training adapts a pretrained LLM to one task. We study six campaigns on a lifelong planner that combines task assignment with multi-agent path finding, on a floor modeled on an existing automated warehouse. We find that (1) the agents raise throughput by 22--60%, and the gains hold on unseen seeds; (2) they rediscover known MAPF mechanisms, such as corridor-exit priorities, local guidance, and rollouts, and independent campaigns find the same bottleneck; (3) the gains largely carry over to another layout, a larger fleet, and other service times, shrink with a s

---

### [93] Semantic Caches for LLM Web Services Leave Their Error Budget Unspent

**链接**: https://arxiv.org/abs/2611.02498
**作者**: Hanshuai Cui, Qianli Ma, Zhiqing Tang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web services built on large language models (LLMs) receive many paraphrases of earlier queries, which a semantic cache answers from stored responses. A reused answer can be wrong, so wrong answers must stay below a share $\delta$ of the queries. Existing caches reuse above a fixed similarity threshold or, like vCache, learn a per-entry rule that bounds each query's error by $\delta$. However, fixed thresholds break the budget on new streams, and per-entry rules need labels on every entry before reusing it. We find an unspent error budget, as vCache realizes only 12-55% of $\delta$ on three public query streams. Surplus spends this budget where reuse is most likely correct. It ranks queries by a risk score shared across paraphrase clusters and opens risk bins as far as an audited error estimate allows. Free labels from every LLM call and a ledger of realized errors keep this threshold safe under drift. On five streams, including ORCAS search queries, Surplus holds $\delta$ in every test

---

### [94] Multi-Teacher Reasoning Distillation for LLM Recommendation with Self-Exploration

**链接**: https://arxiv.org/abs/2611.02457
**作者**: Liangbo Ning, Siyuan Liang, Yi Zhou, Yifeng Zhang, Qing Li, Wenqi Fan 等 (7 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning-augmented recommender systems (RecSys) enhance user preference modeling by generating reasoning trajectories over historical interactions before making recommendations. Knowledge distillation provides a practical paradigm for transferring such reasoning capabilities from powerful large language models to lightweight RecSys. However, existing methods typically rely on a single fixed teacher, remain constrained by the teacher knowledge ceiling, and indiscriminately distill teacher-generated trajectories without assessing their actual utility for downstream recommendation. To address these limitations, we propose MUSE (Multi-Teacher Utility-guided Selection with Self-Exploration), an adaptive reasoning distillation framework that jointly improves reasoning generation and reasoning utilization. MUSE first constructs a diverse reasoning pool using multiple teacher LLMs and progressively augments it via student self-exploration, enabling the student to leverage the strengths of dif

---

### [95] Can LLM Agents Improve Imperfect Earth System Model Parameterizations?

**链接**: https://arxiv.org/abs/2611.03543
**作者**: Kara D. Lamb
**来源**: physics.ao-ph cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth system models (ESMs) rely on parameterizations to represent unresolved processes such as convection, cloud microphysics, and turbulence. However, translating advances in physical understanding into stable, validated parameterizations and integrating them into ESMs often takes years. Agentic AI could accelerate this process and enable more systematic exploration of design choices. Using warm-rain collision-coalescence as a test case, we evaluate agents' ability to synthesize scientific literature, reimplement published bulk parameterizations, and propose new functional forms as differentiable JAX code. We compare conventional parameterizations, data-driven emulators, and agent-generated closures against high-fidelity superdroplet simulations, repeating unattended experiments across ten language models. With expert guidance or iterative feedback, agents produced executable, differentiable, mass-conserving code, although unattended performance depended strongly on the scheme and lan

---

### [96] Harnessing Agent Skills: Architectural Patterns and a Reference Architecture for Skill-Mediated LLM Agents

**链接**: https://arxiv.org/abs/2606.20631
**作者**: Boming Xia, Liming Zhu, Zhenchang Xing, Qinghua Lu, Dino Sejdinovic, Xiwei Xu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] ProofPatch: Reviewing Lean Statements and Keeping the Reviews Valid as Formalizations Evolve

**链接**: https://arxiv.org/abs/2611.01357
**作者**: Xujun Che, Depeng Xu, Jian Xiang, Taufiqua Khan
**来源**: cs.LO cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The kernel of the Lean proof assistant checks that a proof establishes its statement. Whether the statement says what was intended is left to human reviewers. This is the old problem of validating a specification, and it grows more pressing as language models write formal statements in bulk and agents edit formal developments continuously. We present ProofPatch, a tool that helps reviewers judge Lean statements and keeps their judgments valid while the development changes. A reviewer can ask the kernel targeted questions about a statement, such as whether a hypothesis is needed or whether a counterexample exists. Each decision is stored with fingerprints of the statement as Lean elaborated it and of the definitions it depends on, and any declaration can be pinned so that a patch changing it is blocked, whether a person or an agent built on a large language model (LLM) wrote the patch. Working on elaborated terms rather than source text is the central design choice: notation and formatt

---

### [98] Skill++: Towards Lifelong Agents via Routing-Aware Skill Refinement

**链接**: https://arxiv.org/abs/2611.00544
**作者**: Hanrong Zhang, Minghao Liang, Jiawei Wu, Yankai Chen, Shicheng Fan, Zhiwei Liu 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents extend their capabilities with skills, each with a name, a description, and a body. Under progressive disclosure, an LLM router selects skills by name and description alone and loads only the selected bodies. Skill libraries grow continually as users and agents add new skills. Because the router relies on this metadata, a similar new skill can displace an earlier one, breaking previously correct routing even though the earlier skill and the router are unchanged. This routing interference is aggravated for public skills, whose descriptions may not match their bodies. We formulate the problem as lifelong skill routing, a class-incremental continual learning problem. A solution must keep earlier skills selectable without suppressing new ones. Existing approaches fall short, since continually retraining the router risks catastrophic forgetting and rewriting methods either ignore similar skills or require per-skill feedback. We therefore propose Skill++, wh

---

### [99] Benchmark of THReD: Evaluating an LLM Agent and Its Preprocessing Tools for Turning Electronic Health Records into AI-Ready Datasets

**链接**: https://arxiv.org/abs/2611.02484
**作者**: Javad Mohammad Alizadeh, Huanmei Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly built into data-analysis software, yet little evidence shows how reliably they preprocess clinical data or whether the tools they invoke give correct, reproducible output. We report a benchmark of THReD, a web-based system that turns electronic health record (EHR) extracts into AI-ready datasets through a chat agent whose proposed steps run only after user confirmation. The agent benchmark has 141 tasks (100 templates) in seven categories, including goal-level requests, failure recovery, requests calling for no action, schema variation and prompt injection through the data, on synthetic tables calibrated to a regional health information exchange; success is judged by checks on the produced data. Over 2,550 episodes with Claude Haiku 5.5 in four context configurations, the deployed agent completed 92.7% (95% CI 88.1-96.4) of tasks on its first answer, abstained on every advice request, recovered from every injected fault, and never proposed an action requeste

---

### [100] Discovering Models for Experimental Quantum Systems with Agentic AI

**链接**: https://arxiv.org/abs/2611.00620
**作者**: Hannah C. Kleidermacher, Bennet Windt, Miguel Bello, James Zou, Jelena Vu\v{c}kovi\'c
**来源**: quant-ph cs.AI physics.optics
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A central obstacle in realizing color center cavity-QED-based quantum technologies is inhomogeneity, or disorder, among individual emitters. As the number of emitters increases, so does the complexity of the experimental data, making it difficult to quantify the present physical mechanisms of disorder. Here we introduce an artificial intelligence-driven model discovery framework in which a large language model (LLM)-based agent, equipped with tools and a structured workflow, proposes candidate Hamiltonian and Lindbladian models, generates computational tools, and quantitatively evaluates competing physical hypotheses. We apply the workflow to three previously published experimental cavity-QED datasets collected from color centers in diamond and silicon carbide. Across the experiments, the agent successfully identifies physical models for the system and characterizes the disorder. In assessing reproducibility, we find that run-to-run variability is concentrated primarily in the research

---

### [101] Component Replacement in LLM Agents: A Critical Scoping Review of Task Benefit and Attribution

**链接**: https://arxiv.org/abs/2609.39989
**作者**: Shuyang Zhang (The Hong Kong Polytechnic University), Jianshuo Chang (The Hong Kong Polytechnic University)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] A Proposed Rubric for Evaluating Expressed Clinical Reasoning in Large Language Model Responses

**链接**: https://arxiv.org/abs/2609.37788
**作者**: Zhangshu Joshua Jiang, Zina Ibrahim, James T. Teo
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] PentestEval: Benchmarking LLM-based Penetration Testing with Modular and Stage-Level Design

**链接**: https://arxiv.org/abs/2512.14233
**作者**: Ruozhao Yang, Mingfei Cheng, Gelei Deng, Tianwei Zhang, Junjie Wang, Xiaofei Xie
**来源**: cs.SE cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] Cloudra: Geometric Reasoning and Scientific Validation for Autonomous Reaction Mechanism Exploration

**链接**: https://arxiv.org/abs/2611.02909
**作者**: Chengyi Yang, Qianxin Zhou, Yang Li
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous reaction-mechanism exploration requires proposing reaction steps, preparing three-dimensional structures, and determining which reactant and product a computed saddle point connects. Large language model (LLM) agents can misjudge spatial relationships and confuse a computed structure with the species or step they intended to study. We present Cloudra, a multi-agent framework that constrains mechanistic output through a Delivery DAG of chemical objects. Species nodes carry geometries and bonding topology; elementary-step edges carry transition states and reaction connections between species. Cheminformatics algorithms establish molecular identities and atom correspondences. Deterministic routines measure and transform structures to prepare candidate geometries. Frequency and IRC calculations determine the stationary points found and the species they connect. Agents use these objects to test proposed steps, compare pathways, and revise the mechanism. CloudraBench evaluates the

---

### [105] TRIAGE: Reliability- and Load-Conditioned Escalation for Two-Tier LLM Serving with a Semantic Evidence Judge

**链接**: https://arxiv.org/abs/2611.01174
**作者**: Basavaraj R M, Aryan Bharat Kumar
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Two-tier LLM serving escalates selected requests from a small model to a large one, but prompt-based routers cannot see whether retrieved evidence supports an answer, and they treat the GPU cost of an escalation as constant. We study TRIAGE, which conditions escalation on a post-generation reliability state and on a load-dependent GPU price, and we report both what held and what did not on one A40 serving Qwen2.5-7B and 32B (AWQ) under VLLM. Escalation cost rose 21.9x from 1 to 10 requests/s but showed no monotone dependence on KV-cache headroom, and a pre-registered claim that the reliability state detects corrupted evidence (AUROC>=0.70) was falsified at 0.571, although any prompt-only router scores exactly 0.500 by construction. Post hoc, a semantic evidence judge raised detection to 0.846 (0.926 on never-served items) and predicted wrong small-model answers at AUROC 0.90-0.96 on RGB and three RouterBench model pairs; the resulting cascade stayed within about 3 pp of GPT-4 at 79.5% 

---

### [106] When Evidence is Sparse: Weakly Supervised Early Failure Alerting in Dialogs and LLM-Agent Trajectories

**链接**: https://arxiv.org/abs/2606.05414
**作者**: Avinash Baidya, Xinran Liang, Ruocheng Guo, Xiang Gao, Kamalika Das
**来源**: cs.CL cs.AI cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] DARE: Aligning LLM Agents with the R Statistical Ecosystem via Distribution-Aware Retrieval

**链接**: https://arxiv.org/abs/2603.04743
**作者**: Maojun Sun, Yue Wu, Yifei Xie, Ruijian Han, Binyan Jiang, Defeng Sun 等 (8 人)
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Quantiles, Not Points: Streaming Quantile Matching for Ordinal-Aware LLM-as-a-Judge Calibration

**链接**: https://arxiv.org/abs/2611.00447
**作者**: Ilija Subasic, Andrew Rabinovich, Zhao Chen
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge scores are often distributionally shifted from human ratings on any given evaluation task, and post-hoc calibration (mapping LLM to human scores in a small labeled anchor set) has become a popular method to correct for this shift. In this paper we derive the calibration from two positions: that LLMaJ scores are ordinal ratings drawn from a distribution rather than isolated points. We present streaming quantile matching (SQM), a version of a classical method not previously bench marked for LLMaJ calibration, which is built on the two positions by computing the optimal-transport map between the LLM and human score distributions. We develop an evaluation framework and within it we show that unlike point-wise calibrations, SQM respects the ordinality of the human anchor set and achieves the best distributional fidelity and the top overall rank across models and data. We also show that in general, post-hoc calibration narrows the raw error gap between smaller and larger judge

---

### [109] Same Sentence, Different Construct: Identity-Swapped Rationales Reveal Measurement Non-Invariance in LLM Hate Speech Classifiers

**链接**: https://arxiv.org/abs/2611.02491
**作者**: Wenchang Wang and Yue Song
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as measurement instruments for socially consequential constructs such as hate speech, and are typically validated by their aggregate agreement with human labels. A valid instrument must also apply the same construct to every group it measures. We test this requirement using 421 \hc{} templates that are instantiated identically for seven protected groups, so that only the identity term varies. Four LLM classifiers each exceed 0.95 balanced accuracy, yet within identical templates two of them miss hateful statements about women at markedly higher rates than the same statements about other groups (excess false-negative rates of 8.3 and 4.4 percentage points), a gap first reported for fine-tuned classifiers in 2021. We show how the construct shifts. Comparing rationales within each template, we find that models invoke protected-group status for other groups but recast the identical statement about women as personal dislike or as aimed at an indiv

---

### [110] Hacking or Just Failing? A More Capable LLM Monitor Better Separates Reward Hacking from Honest Failure

**链接**: https://arxiv.org/abs/2611.00407
**作者**: Kaushik Kezendirane
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent's visible score can exceed its real progress because it gamed the score or because it simply made mistakes, so a useful reward-hacking monitor must tell the two apart. We built a sandboxed task in which an agent can game a completion score, labelled every episode by replaying it and repairing the final state counterfactually, and ran five pre-registered studies. On 60 episodes from a Llama 3.1 8B agent, small local monitors (Llama 3B and 8B) did not separate exploit attempts from honest failures with the same score gap: prompt changes traded missed exploits for false alarms, and the pre-registered primary monitor reached AUC 0.64. On identical inputs, Gemini 3.1 Flash-Lite, which completed 9/10 clean tasks against 2/10 for the 8B model, met our pre-registered criterion (AUC 0.80, 95% interval [0.66, 0.93]; 1/35 honest failures flagged); with only 14 exploit episodes, this estimate is uncertain. On an exploit that no prompt names, Gemini usually described the action correctly y

---

### [111] Preprocessing Choices in Fine-Tuning Data Matter: Utility and Demographic Sensitivity in LLM-Based Recommendation

**链接**: https://arxiv.org/abs/2611.03113
**作者**: Furkan Yasir Goksu, Yaren Yilmaz, Sule Gunduz Oguducu
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have introduced a generative approach to recommendation, producing item lists from textual representations of user histories and item information. However, this generative setting raises challenges concerning output validity, prompt consistency, and sensitivity to demographic descriptors. In this work, we investigate how preprocessing choices in fine-tuning data affect recommendation utility and fairness-related behavior in a generative LLM-based recommender system. We first establish a controlled recommendation pipeline that combines supervised fine-tuning, catalog-constrained decoding, and prompt augmentation. We then study three preprocessing choices: item-title representation, demographic balancing, and auxiliary item-knowledge enrichment. Experiments on MovieLens-1M show that the catalog-constrained pipeline eliminates out-of-catalog items and ensures complete ten-item outputs, while prompt augmentation improves prompt consistency and utility. Original

---

### [112] Scaling LLM Agent Tool Access: The MCP Gateway

**链接**: https://arxiv.org/abs/2607.15593
**作者**: Mingxin Li, Enge Song, Yueshang Zuo, Xiaodong Liu, Rong Wen, Qiang Fu 等 (10 人)
**来源**: cs.DC cs.AI cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] SHq: Learnable Grids for LLM Weight Quantization

**链接**: https://arxiv.org/abs/2611.02966
**作者**: Michael Helcig, Earl Killian, Dan Alistarh
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Block-scaled lookup-table (LUT) formats, which represent weights as indices into a small value set (the grid), have become standard for low-bit LLM quantization, ranging from NF4 and BOF4 to the 3-bit LUT instruction in NVIDIA Rubin. While these formats leave the grid definition flexible, existing implementations rely on fixed grids derived either from numerical data types (INT, FP) or assumed weight distributions (NF, BOF). We demonstrate that no single fixed grid is universally optimal; the best fixed grid varies with bit-width: BOFS at 2 bits, NF at 4 and 5 bits, and INT at 6 bits. We introduce SHq, a closed-form family of grids parameterized by two critical degrees of freedom: a companding strength {\alpha} that interpolates level spacing from uniform to floating-point-like, and an offset c that introduces asymmetry. This offset allows the sign bit of the FP8 block scale, otherwise unused, to select between the grid and its mirror image, up to doubling the number of distinct values

---

### [114] Cross-Lingual Persona Effects in LLM Negotiation

**链接**: https://arxiv.org/abs/2611.00300
**作者**: Saehee Eom, Tejas Khandwekar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tell an LLM negotiator to be "headstrong" and it should hold firm on price, but does that instruction retain the same behavior in every language? To test this, we use identical buyer and seller instances of Gemini 3.6 Flash to negotiate the same 12 CraigslistBargain scenarios in English and Korean. The pilot-scale 2 x 2 x 3 design crosses interaction language, seller urgency (none or strong), and buyer persona (cooperative, neutral, or headstrong), yielding 432 attempted negotiations. We call this property cross-lingual social-policy fidelity: whether a prompt-defined social policy produces the same behavioral effect regardless of interaction language. It often does not. Korean negotiations reached agreement far more often than English (77.3% vs. 52.5%, a 24.8-point gap, Holm-adjusted p = .0039), but only for neutral and headstrong buyers; cooperative buyers were already near-ceiling in both languages. Buyers' opening offers barely differed by language; the gap instead emerged later, t

---

### [115] MAC-Bench: Benchmarking Multi-Agent Collaboration via Interconnected Tasks

**链接**: https://arxiv.org/abs/2611.01728
**作者**: Zerui Chen, Qinggang Zhang, Qichuan Liu, Zhishang Xiang, Zhimin Wei, Yunbo Tang 等 (9 人)
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) tackle challenging tasks by dividing work among agents and coordinating their contributions toward shared objectives. Evaluating these systems therefore requires benchmarks that assess not only task-solving performance but also the ability to handle interdependent work. However, existing benchmarks often emphasize task difficulty without substantial collaboration requirements or evaluate only a limited range of predefined collaboration patterns. In this paper, we introduce MAC-Bench, a comprehensive benchmark for evaluating multi-agent collaboration through interconnected tasks. Rather than imposing predefined agent roles or communication protocols, MAC-Bench embeds collaboration requirements directly into task dependencies and shared-resource constraints. Specifically, we mine reusable collaboration structures from selected benchmark tasks at two levels. Local collaboration patterns capture recurring interactions among subtask

---

### [116] Solver-Like Behavior in Large Language Models as Formalizers

**链接**: https://arxiv.org/abs/2611.02395
**作者**: Rikhil Amonkar, Stuti Mohan, Kevin Nguyen, Ceyhun Efe Kayan, Ronan Le Bras, Li Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the LLM-as-formalizer paradigm, a large language model translates a problem into a formal program and leaves the search to a solver, gaining the solver's guarantees. Formalizers are now often reasoning models that write a long reasoning trace before the program, yet they are judged only by the program's output. We find that the trace routinely does the solver's job, assigning, testing and ruling out values until it often reaches the full answer; we call this solver-like behavior (SLB). We define an ontology of SLB over the trace, the program and its output, and use LLM judges, checked against human labels, to label 2,000 generations from three reasoning models on four constraint satisfaction datasets, each formalized in a declarative and an imperative formal language. SLB appears in 85% of traces and takes 24% of reasoning tokens, yet the program usually recomputes the answer, so the effort is redundant. The 9% of programs that inherit the trace's answer also inherit its errors, and

---

### [117] Pacing Branch Parallelism in LLM Serving

**链接**: https://arxiv.org/abs/2605.06914
**作者**: Swapnil Gandhi, Siva Kumar Sastry Hari, William J. Dally, Christos Kozyrakis
**来源**: cs.DC cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] Uncertainty Quantification for LLM Function-Calling

**链接**: https://arxiv.org/abs/2604.22985
**作者**: Zihuiwen Ye, Lukas Aichberger, Michael Kirchhof, Sinead Williamson, Luca Zappella, Yarin Gal 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Auditing Escalation Reliability in Healthcare LLM Agents: A Perturbation-Controlled Benchmark of Workflow-State Failures

**链接**: https://arxiv.org/abs/2610.21270
**作者**: Zihao Zheng (Washington University in St. Louis), Junyi Yao (Washington University in St. Louis), Baichuan Li (Southern Methodist University), Jiayu Long (Washington University in St. Louis)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] RECEIPT: Measuring and Repairing the Return Assumption of LLM Agents in Web Service Operations

**链接**: https://arxiv.org/abs/2611.01930
**作者**: Boyang Yang, Ziyao Yang, Yu Zhang, Duo Chai, Xiaoming Chen, Haoye Tian
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents operate Web infrastructure from the command line and rely on a return assumption, namely that each tool call returns within a bounded time and with its requested action finished. Many commands, however, ask a question before they act, and the agent's harness either closes the program's input or keeps it open as a terminal at which nobody types. With closed input, the program can return status 0 without the requested action. With open input, it waits until a time limit, and the agent pays in time and tokens. To the best of our knowledge, this paper is the first to measure and repair the return assumption. We collect 91,469 production tool calls and 89,047 public agent trajectories, test how 8 widely used harnesses launch commands, and build Litmus, a catalog of 158 checked command-line invocations, and Tripwire, a benchmark of 25 task pairs that differ only in whether a question guards the requested action. We then propose RECEIPT, which keeps the input open, reads what each 

---

### [121] AtomMem: Building Simple and Effective Memory System for LLM Agents via Atomic Facts

**链接**: https://arxiv.org/abs/2606.19847
**作者**: Yanyu Yao, Shangze Li, Zhi Zheng, Hui Zheng, Qi Liu, Tong Xu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Constraint Dependency Graph Retrieval for Compliance Detection on Long SKILL Documents

**链接**: https://arxiv.org/abs/2611.01042
**作者**: Shuaitao Zhao, Feng Ni, Lichao Ma, Yuchen Wei, Shuaike Li, Jiaye Lin 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents carry out business operations under enterprise documents we refer to as SKILL documents, which take the form of standard operating procedures (SOPs) that state the conditions to verify and the actions to take before an operation proceeds. Long, densely cross-referenced SKILL documents exceed the context budget of small deployed auditors. Similarity-based retrieval then brings in irrelevant rules while omitting mandatory prerequisites, and the two-stage audit policy provides no trainable signal for the retrieval stage. We present SkillCDG, a compliance detection framework that reformulates each SKILL document as a constraint dependency graph, shifting rule retrieval from similarity-based matching to closure-based selection under the deployment's context budget. Each atomic rule is anchored to its source text span as a graph node, and mandatory prerequisite relations form the sole edge type. Policy-generated retrieval keywords activate seed rules, whose 

---

### [123] Latent Debate: A Surrogate Framework for Interpreting LLM Thinking towards Binary Decisions

**链接**: https://arxiv.org/abs/2512.01909
**作者**: Lihu Chen, Xiang Yin, Francesca Toni
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] When the Text Is Silent: Memory Shortcuts and the Validity of LLM Annotation under Evidence Insufficiency

**链接**: https://arxiv.org/abs/2611.02273
**作者**: Wenchang Wang and Yue Song
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to annotate text for social science research, content moderation, and training data. Their broad knowledge of real-world entities raises a concern: when labeling a text, do they rely on its evidence or substitute what they already know? We call this behavior a memory shortcut and examine when it emerges, what amplifies it, and how to mitigate it. Using 995 widely recognized public figures and four matched control names per figure, we construct counterfactual texts that separate textual evidence from prior knowledge, and evaluate three commercial LLMs on 121,594 prompts each across five stages. We find a striking asymmetry. Although all models recognize nearly every figure, none follows memory over the text when the two conflict. Shortcuts instead emerge when evidence is absent: for one model, famous names raise the rate of remembered occupations, ages, and countries by 17.0, 14.9, and 6.8 percentage points relative to synthetic names. 

---

### [125] Optimize the Harness, Not the Model: Fitting a Minimal Agent to a Self-Hostable LLM for Investigative Analysis

**链接**: https://arxiv.org/abs/2611.03434
**作者**: Shai Nahum Gefen, Vered Chassida, Dmitry Basin, Guy Feigenblat
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Government intelligence teams need LLM agents that can analyze large, messy evidence collections, but security and cost constraints often rule out hosted frontier models and broad, hard-to-audit tool surfaces. We report CLEO: Constrained Loop for Environment Optimization, a method for fitting a minimal agent harness to a fixed, self-hostable LLM. Given an expert-validated dataset, CLEO admits only the tools, guardrails, memory policies, and loop components that improve accuracy while remaining general and auditable. On our held-out dataset, the CLEO harness reaches an 83.8% pass rate, within 1.2 points of the strongest out-of-the-box Claude Code SDK baseline, while being two orders of magnitude smaller.

---

### [126] Replay for LLM Continual Learning with Multi-Teacher On-Policy Distillation

**链接**: https://arxiv.org/abs/2611.02746
**作者**: Yiqiao Qiu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-teacher on-policy distillation (MOPD) distills domain experts into one student but needs every expert at once. When domains arrive one at a time and earlier experts are gone, the previous-stage student can teach replayed prompts of earlier domains inside every stage. Some pipelines instead store every stage snapshot for a final multi-teacher recovery stage. On five domains with a 1.5B student and five public experts, this paper compares both with joint MOPD. It varies the replay budget and the replay signal. The signal is token-level distillation alone or with alignment of hidden states, attention and value relations. Sequential distillation without replay or recovery is 6.2 points below 208-step joint MOPD on a 14-benchmark average and 3.5 points below on the 11 benchmarks outside safety. Without snapshots, replay toward the previous student closes 3.8 of the 6.2 points when the earlier domains share the replay budget of a stage. With a fixed share of seven replay steps per earl

---

### [127] The Brittle Compass: Navigating LLM Prompt Sensitivity in Slovak Migration Media Discourse

**链接**: https://arxiv.org/abs/2611.01219
**作者**: Samuel Harvan, Jaroslav Kop\v{c}an, Marek \v{S}uppa, Andrej Findor
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work, we present a case study that explores various tasks centered around the topic of migration in Slovak, a low-resource language, such as topic relevance and geographical relevance classification, and migration source/destination location term extraction. Our results demonstrate that native (Slovak) prompts yield a modest, task-dependent gains, while large models show significant robustness to prompt variations compared to their smaller counterparts. Analysis reveals that instructions (system or task) emerge as the most critical prompt component, more so than the examples sections, with task-specific performance benefits being more pronounced than overall language effects.

---

### [128] Is your LLM an Agressive Narcissist with Depression? Analyzing Psychological Portraits of Large Language Models

**链接**: https://arxiv.org/abs/2611.02757
**作者**: Polina Fedorinina, Anna Fattakhova, Nadezhda Romanova, Ekaterina Lezina, Irina Nikishina
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nowadays, interaction with AI requires caution not only regarding the factual reliability of generated content but also regarding personality markers that models may implicitly transmit during dialogue that can subtly influence users' perception of information. In this paper, we conduct a large-scale experimental study in which 22 large language models complete 11 psychological inventories. Furthermore, we investigate correlations between human and model responses to track the adjustments made for the users who interact with them on a daily basis. The results show that LLMs exhibit coherent and relatively stable psychological patterns. Personality traits remain largely consistent, whereas emotional and symptomatic dimensions are more variable, with anxiety and neuroticism emerging as dominant tendencies. Model explanations further suggest that LLMs generate internally consistent and safety-oriented profiles while also reflecting correlations with the users they regularly interact with.

---

### [129] IssueLighter: An Issue Type-Aware LLM Agent for Issue Report Validity Assessment

**链接**: https://arxiv.org/abs/2611.02721
**作者**: Jiawei Ran, Yuxia Zhang, Ziyang Zhao, Hui Liu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Invalid issue reports are prevalent in open source software (OSS) projects, imposing substantial burdens on maintainers who already face a high risk of burnout. Prior research has primarily focused on identifying invalid reports for specific issue categories (e.g., bug and wontfix), leaving the broader landscape of OSS issue types largely unexplored and limiting the generalizability of existing approaches. Moreover, existing methods provide little support for explaining or validating their predictions, reducing their practical usefulness for maintainers. With the rise of LLM-based agents, it remains unclear whether a comprehensive understanding of the causes of invalidity across all issue types can improve validity assessment performance while producing well-grounded rationales. To this end, we first manually annotated the validity status of 520 issue reports from three OSS projects, i.e., pandas, scikit-learn, and mypy, resulting in 257 invalid reports and 263 valid ones. Then, we con

---

### [130] Modeling Social Dynamics with an LLM-Enabled Agent Based Network-Dynamic (LAND) Model

**链接**: https://arxiv.org/abs/2608.00929
**作者**: Lynnette Hui Xian Ng, Kathleen M. Carley
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] Can LLM Agents Be Forward-Deployed Engineers? Requirement Discovery and Delivery for Enterprise Text-to-SQL

**链接**: https://arxiv.org/abs/2611.03551
**作者**: Marianne Menglin Liu, Rongguang Wang, Zheng Wang, Yewen Wang, Leonid Boytsov, Tao Sheng 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM coding agents can increasingly automate model post-training, but whether they can act as forward-deployed engineer (FDE) agents, discovering customer requirements and turning them into deployment decisions, remains unclear. We study this on a real enterprise text-to-SQL engagement: a simulated customer, grounded in the real use case's requirements, starts with an ambiguous request. An agent must discover acceptance criteria, data permissions, and hardware constraints in the discovery phase, then plan and execute a post-training recipe in the delivery phase. Across 15 models, the strongest discover over 80% of withheld requirements and open-weight models discover 40-50%; in the delivery phase, only 25% of runs across eight coding-agent configurations pass all acceptance criteria. We identify four bottlenecks in this engagement: (1) incomplete discovery, with 40% of withheld requirements missing or misrepresented; (2) unreliable execution; (3) underused compute budgets and a lack of 

---

### [132] Distilling Literary Sentiment from LLM Annotations into an Ordinal BERT Model

**链接**: https://arxiv.org/abs/2611.02985
**作者**: Artem Suslov and Takehiro Hashimoto
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The scarcity of human-annotated literary corpora limits the development of domain-specific sentiment analysis models. This study investigates whether LLM-generated annotations can supervise smaller models for literary sentiment analysis. We fine-tune five BERT models using ordinal regression on 10,889 literary sentences annotated by Gemma 4 31B on a ten-point sentiment scale. The models are evaluated against 1,923 human-annotated sentences from Hemingway's "The Old Man and the Sea", alongside the teacher model and conventional baselines. BERT-large achieves a Kendall's $\tau$ of 0.589, approaching the teacher's 0.604. Although a constant-neutral predictor achieves the lowest overall mean absolute error (MAE), BERT-base outperforms the teacher on non-neutral sentences, achieving an MAE of 0.726 versus 1.116. These findings demonstrate the potential of LLM-generated supervision for developing smaller literary sentiment models, while highlighting the limitations of aggregate error metrics

---

### [133] HERALD: High-Throughput Block Diffusion LLM Inference via CPU-GPU Cooperative KV Cache Retrieval

**链接**: https://arxiv.org/abs/2606.21633
**作者**: Omin Kwon, Doyeon Kim, Jongseok Park, Seung Yul Lee, Sehoon Kim, Ion Stoica 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] On the Reliability Limits of LLM-Based Multi-Agent Planning

**链接**: https://arxiv.org/abs/2603.26993
**作者**: Ruicheng Ao, Siyang Gao, David Simchi-Levi
**来源**: cs.MA cs.LG math.OC stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] Multiscale Policy Optimization for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2610.35013
**作者**: Tao Ren, Hui Yang, Jia Deng, Tingyang Chen, Qiyao Wang, Shuo Tang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] BitLLM: Efficient Low-Bit, Conversion-Hiding LLM Decoding on Mobile GPUs

**链接**: https://arxiv.org/abs/2611.00547
**作者**: Hangyu Zheng, Zhihao Shu, Kunxiong Zhu, Minghai Qin, Xiaolong Ma, Gagan Agrawal 等 (7 人)
**来源**: cs.AR cs.LG cs.OS cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid scaling of large language models (LLMs) has unlocked remarkable capabilities across various domains. However, deploying LLMs on mobile devices remains challenging because of their high computational and memory requirements. Low-bit quantization (e.g., 4-bit weights, 8-bit activations) can reduce model size while preserving accuracy, but its practical efficacy on mobile GPUs has been limited so far. In this paper, we identify that the performance gap stems primarily from frequent data type conversions between quantized and floating-point values, and dynamic and inefficient memory access patterns caused by the growing Key-Value (KV) cache during autoregressive decoding. We introduce BitLLM, a mobile inference engine that addresses type conversion overhead and suboptimal memory accesses in quantized LLMs. Our approach features an adaptive layout and packing strategy for the KV cache that ensures efficient memory access throughout LLM decoding. This is coupled with an integer-nat

---

### [137] CuriousTogether: Implications of Curiosity and Cultural Grounding in Multi-Agent LLM Interactions

**链接**: https://arxiv.org/abs/2611.01301
**作者**: Angana Borah, Zoha Hayat Bhatti, Zhijing Jin, Rada Mihalcea
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed in multi-agent settings, exhibiting emergent collective behaviors, yet the role of curiosity as a driver of such dynamics remains understudied. We introduce CuriousTogether, a framework evaluating curiosity-driven multi-agent LLM interactions across three complementary dimensions: novelty-seeking, epistemic and social curiosity. Across eight tasks spanning reasoning, creative generation, and social bias mitigation, curiosity-guided multi-agent settings yield improvements over non-curious ones on seven out of eight tasks, with gains of up to 20.6% in story generation (semantic diversity) and a 14.9 pp reduction in stereotype rates. Furthermore, country-conditioned cultural grounding show benefits for story generation and social tasks, but can hurt precision-oriented reasoning. Finally, we show that inference-time multi-agent curiosity-based approach offers favorable quality-token trade-offs, compared with single-agent baselines. Tog

---

### [138] WebWeaver: Breaking Topology Confidentiality in LLM Multi-Agent Systems with Stealthy Context-Based Inference

**链接**: https://arxiv.org/abs/2603.11132
**作者**: Zixun Xiong, Gaoyi Wu, Lingfeng Yao, Miao Pan, Xiaojiang Du, Hao Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] CAREFUL-Bench: Effect-Aware, Judge-Free Evaluation of Multi-Turn LLM Function Calling

**链接**: https://arxiv.org/abs/2611.02978
**作者**: Alexander Kovalenko, Artem Redchych
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The multi-turn checker of the Berkeley Function Calling Leaderboard (BFCL) evaluates final state correctness but ignores the effects of intermediate calls: extra calls are free, function documentation does not describe side effects, and the scripted user never responds to proposals. Consequently, models asking for confirmation before destructive actions are penalized; 260 of 734 reference turns in the base category perform destructive actions without confirmation. We make BFCL effect-aware without replacing it. We infer effect declarations for all 128 functions by executing them in BFCL simulators and comparing state changes, with destructive writes identified by three annotators. A judge-free replay scorer reproduces official results across all 800 reference trajectories while reporting unrequested destructive calls, duplicate writes, redundant reads, surplus steps, and their token costs. We also introduce a confirmation-aware protocol with a deterministic simulated user. Across 11 op

---

### [140] MAS-Guard: Unified Guardrails from Individual Agents to Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2610.28397
**作者**: Mohammad Kachuee, Phu Mon Htut, Sheng Li, Nikolaos Pappas, Miguel Ballesteros, Yassine Benajiba 等 (8 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] Low-Margin Branch Points in Deterministic LLM Deliberatio

**链接**: https://arxiv.org/abs/2611.00546
**作者**: Hajime Shimao and Warut Khern-am-nua
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deterministic multi-agent LLM deliberation can exactly re- play a fixed transcript, yet exact replay alone does not test local resistance to controlled internal interventions. Because each response becomes context for later agents, a changed greedy token can redirect a transcript-mediated execution. We present a white-box audit of this local failure mode in a five-agent committee under greedy decoding. We prospectively select low- and high-margin token positions, require exact no-op re- play, inject norm-relative residual displacements, and measure first transcript divergence within ten generated tokens. Low- margin positions are more branch-sensitive than high-margin controls, while matched margin-reducing gradient directions branch substantially more often than margin-increasing con- trols. We then continue selected realized branches through the committee to distinguish textual persistence from preference and final-decision changes. The contribution is a controlled audit for local br

---

### [142] Query Language Sensitivity in Automated Sentiment Scores of LLM Responses

**链接**: https://arxiv.org/abs/2607.13304
**作者**: Dmitrij \.Zatuchin
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [143] Capacity Planning for Resource-Constrained Clinical LLM Serving

**链接**: https://arxiv.org/abs/2611.01152
**作者**: Yi Tang, Geoffrey Martin, Yiye Zhang, Yifan Peng
**来源**: cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying large language models (LLMs) under a fixed accelerator budget requires jointly deciding how computational capacity is allocated across model sizes and how incoming requests are routed across that capacity. Although prior work has extensively studied LLM routing and serving efficiency, the relative importance of fleet composition and routing under resource constraints remains less understood. We investigate this question using a controlled four-GPU serving environment with heterogeneous clinical NLP workloads spanning short factual verification, biomedical semantic matching, and long-context clinical summarization. We systematically vary fleet composition, routing policy, and offered load while holding the workload trace and hardware budget fixed. Across 24 configurations, descriptive main-effect shares attribute more variation to fleet composition than to the evaluated routing policies in time to first token, latency, and long-context coverage. All-small fleets provide the be

---

### [144] External Experience Serving in Production LLM Systems: A Deployment-Oriented Study of Quality-Cost Trade-offs

**链接**: https://arxiv.org/abs/2606.11806
**作者**: Lin Sun and Heming Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [145] ClinFusion: A Vision-Centric Multimodal LLM System for Holistic Medical Understanding

**链接**: https://arxiv.org/abs/2607.24743
**作者**: Hangjie Yuan, Yichen Qian, Zhiwei Tang, Xianzhe Xu, Sicheng Yang, Lirong Wu 等 (10 人)
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [146] Evolving Memory, Learning to Meta-Control: Test-Time Adaptation for Experience-augmented LLM Agents

**链接**: https://arxiv.org/abs/2611.01747
**作者**: Zeyuan Zhao, Yuanyuan Shi, Peng Yu, Lingyue Fu, Shao Zhang, Ying Wen
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving agents accumulate experience from task streams, but existing frameworks typically rely on fixed pipelines to retrieve and utilize this experience, neglecting when and how to deploy it. We introduce Online Meta-Control of Experience (OMCE), a framework that updates experience memory and learns a meta-control policy from task feedback during test-time adaptation. OMCE employs a lightweight contextual-bandit meta-controller that uses compact retrieval signals to select among four cognitive actions: DIRECT, EPISODE, GUIDE, and DISTILL. This routing mechanism operationalizes three coupled decisions: whether to invoke experience, which memory format to utilize, and when to consolidate new guidance. OMCE evolves online, leveraging task feedback to update the memory bank and refine the routing policy via contextual bandit updates. Experiments on four online adaptation benchmarks across four backbones show that OMCE improves first-attempt success by up to 20.5 percentage points ov

---

### [147] Dependence-Aware Risk Assessment and Optimal Design of AI-Agent Safeguard Systems

**链接**: https://arxiv.org/abs/2611.00386
**作者**: Yijia Li, Maochao Xu, Peng Zhao
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on safeguards to prevent unauthorized actions while preserving legitimate service. However, existing risk assessments often focus on individual safeguard performance while overlooking dependence among safeguard decisions. This paper develops a dependence-aware framework for risk assessment and optimal design of multi-component AI safeguard systems, jointly selecting configurations and operating policies for sequential layered screening and selective verification. We establish stochastic comparisons of layered-screening error probabilities and invocation costs under lower-orthant ordering. For selective verification, we characterize exactly which policies have error probabilities and review costs that respond monotonically to stronger dependence under supermodular ordering. For a fixed first stage and reviewer, we show that the optimal routing map is a two-threshold rule in the first-stage likelihood ratio. An accompanying open-source 

---

### [148] SkillDAG: Self-Evolving Typed Skill Graphs for LLM Skill Selection at Scale

**链接**: https://arxiv.org/abs/2606.03056
**作者**: Tong Bai, Zhenglin Wan, Pengfei Zhou, Xingrui Yu, Yang You, and Ivor W. Tsang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [149] How Green Is Your Manifesto? Scoring Environmental Positions in the 2024 EU Elections with an LLM Panel

**链接**: https://arxiv.org/abs/2611.02033
**作者**: Franco Corti and Sajid Siraj
**来源**: cs.CL cs.CY econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Locating political parties on environmental and climate policy is central to the study of party competition, yet the established instruments, expert surveys and the hand coding of manifestos, are costly, periodic, and slow to extend to new documents. We ask whether a panel of large language models can serve as a cheaper and reproducible alternative. Treating each manifesto as a set of sentences, three models from independent providers score every sentence on two dimensions, environmental protection and climate change, separating a party's position on an issue from the salience it gives it, and the judgments are averaged to the manifesto level. Agreement across the models is retained as a built-in reliability signal. We apply the panel to 41 manifestos from the 2024 European Parliament election, covering Austria, France, Germany, Italy, Spain, and the European party families, and validate it against the 2024 Chapel Hill Expert Survey for the 25 parties with a like-for-like expert benchm

---

### [150] Measuring "Success" In the Transition from Pre- to Post-LLM Conversational Agents through the Lens of Interaction & Explanations for Older Adults

**链接**: https://arxiv.org/abs/2611.02088
**作者**: Tamara Zubatiy, Niharika Mathur, Reina Chan, Srijan Pokharel, Rosemarie Santa Gonz\'alez, Agata Rozga 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational agents (CAs) for older adults have moved through at least two distinct eras, split by the emergence of large language models (LLMs) at the end of 2022. The first era was defined by commercial smart speakers such as the original Google Home and Amazon Alexa, built on rigid, rule-based dialogue. Interactions were single-turn, user-initiated and "successful" if and only if a command matched one of a finite set of pre-templated intents. The current era is marked by LLM-powered systems capable of open-ended, multi-turn conversation, with capacity for personalization and foundations for more proactive interaction. This shift has not only transformed what CAs can do for users, but also changed what researchers can measure when it comes to understanding "success" of user interactions with CAs. In this case study, we reflect on over 8 years of research spanning more than 100 participants across multiple field sites to trace how our own working definitions of "success" have evolve

---

### [151] The SIMPLE Law for Energy Cost of LLM Inference

**链接**: https://arxiv.org/abs/2611.03330
**作者**: Hiari Pizzini Cavagna, Andrea Proia, Daniele Cesarini, Zeynep Kiziltan, Andrea Bartolini
**来源**: cs.AI cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI is billed per token, yet tokens are not equally expensive. Each token enters the KV-cache and raises the cost of those that follow, so energy grows non-linearly along a sequence whose tokens look identical. No analytical model states what a token costs, and the most accurate SOTA model is a fit, not a law: it absorbs architecture into fitted coefficients, requiring per-LLM fitting. We derive closed-form expressions of the computational and memory-access complexity of LLM inference in terms of architectural hyperparameters, covering MHA and GQA, and compare a family of analytical models of increasing granularity. From these, we obtain the SIMPLE Inference Model to Predict LLMs Energy (SIMPLE), a four-parameter law that separates prefill from decode, and decode into KV-cache cost and next-token computation. Over traces of 13 dense LLMs from six families on NVIDIA H100 GPUs, it attains R2 = 0.969 and 11.97% MAPE, 3.1-3.5x below the SOTA, without per-LLM calibration. The SIMP

---

### [152] How Safe Are AI-Generated Patches? A Large-scale Study on Security Risks in LLM and Agentic Automated Program Repair on SWE-bench

**链接**: https://arxiv.org/abs/2507.02976
**作者**: Amirali Sajadi, Kostadin Damevski, Preetha Chatterjee
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [153] Qubrio: High-Performance Quantum Compilation via Multi-Agent LLM Collaboration

**链接**: https://arxiv.org/abs/2611.02269
**作者**: Jixuan Ruan, Zhuo Cui, Zhengding Hu, Zhongkai Yu, Xiang Fang, Yue Guan 等 (10 人)
**来源**: quant-ph cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) offer an adaptable alternative to traditional quantum compilation heuristics, which bottleneck progress by demanding costly manual redesigns whenever hardware evolves. However, naive single-pass LLM approaches fail under the unique challenges introduced by quantum compilation. We introduce Qubrio, a practical agentic framework that significantly reduces heuristic redesigns through a three-level decomposition. By (1) partitioning programs into sequential operation stages, (2) deploying specialized agents for placement, routing and optimization, and (3) using disaggregated feedback for precise error correction, our system reliably navigates complex physical constraints. Beyond serving as a direct compiler, our LLM framework also uncovers novel strategies that facilitate convoy-style shuttling, substantially enhancing hardware concurrency without sacrificing fidelity. We further integrate these strategies into the previous state-of-the-art (SOTA) compiler, rec

---

### [154] Just-in-Time Skill Retrieval via Long-Horizon State Tracking

**链接**: https://arxiv.org/abs/2611.01701
**作者**: Xin Lin, Ziheng Wang, Zerui Chen, Jiayao Ma, Zhimin Wei, Bingshuai Liu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on external skill libraries to support complex task execution. However, determining which skills are needed remains challenging in long-horizon tasks. Existing methods typically select a fixed skill set before execution, implicitly assuming that a task's procedural requirements can be determined from its initial description. This assumption is restrictive for long-horizon interaction, where new requirements emerge from intermediate observations, execution outcomes, and newly revealed constraints. This motivates just-in-time skill retrieval, which dynamically selects skills as execution unfolds. Just-in-time skill retrieval is promising but challenging: the utility of a skill depends not only on the current context, but also on the evolving task state shaped by prior steps. To this end, we propose JitSkill, a state-grounded framework that addresses this challenge through continuous task-state tracking. By connecting emerging requiremen

---

### [155] Echoes as Anchors: Probabilistic Costs and Attention Refocusing in LLM Reasoning

**链接**: https://arxiv.org/abs/2602.06600
**作者**: Zhuoyuan Hao, Zhuo Li, Wu Li, Fangming Liu, Min Zhang, Jing Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [156] Multi-Modal Multi-Agent System for Bridge Operation and Maintenance based on Large Language Model

**链接**: https://arxiv.org/abs/2611.02738
**作者**: Xiangyun Luo, Yunkai Zhang, Yong Huang, Stephen Wu, Hui Li
**来源**: cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bridges are critical transportation infrastructure, and reliable operation and maintenance (O&M) is essential for traffic safety and long-term structural performance. However, bridge O&M faces key bottlenecks: no unified architecture coordinates heterogeneous resources; model inferences lack clear links to physical-mechanical laws; and experts' tacit knowledge remains difficult to formalize. This study proposes a knowledge-enhanced autonomy formalization methodology and apply it to construct the Bridge O&M Multi-Modal Multi-Agent System (BOMMA), which integrates heterogeneous diagnostic actions, physics-mechanics-informed representations, long-term memory, and structured experiential knowledge within a coordinated multi-agent workflow, enabling interpretable and traceable scheduling, analysis, and decision-making. On 3,492 multi-source instructions, the proposed method achieves scheduling recalls of 85.37% for simple and 99.40% for composite tasks, with 95.35% BERT F1-score for O&M act

---

### [157] CONFIRM: Governing Scientific Reporting for Trustworthy Agentic Neuroimaging

**链接**: https://arxiv.org/abs/2611.01449
**作者**: Yuxiang Wei, Lijing Zhu, Qizhen Lan, Yanteng Zhang, Vince D. Calhoun
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can autonomously run neuroimaging analyses from research questions to reported findings. Existing agentic systems use tools to check that code runs and reported values match its output, but rely on LLM judgment to decide which results warrant scientific reporting. We show that LLM judges endorse site-confounded findings even when the confound is presented as evidence. We present \textbf{CONFIRM}, a framework that separates running an analysis from deciding which findings to report. CONFIRM encodes each hypothesis as a machine-readable, pre-specified analysis plan that fixes the claim and its pass criteria before computing results. It then filters results through five deterministic gates (search history and multiplicity, confounds, power, analytic stability, and replication) under three configurable reporting standards, from least to most demanding: \textit{Screen}, \textit{Replicate}, and \textit{Full}. Failed claims receive diagnoses that guide follow

---

### [158] FOLLIE: Automated Reasoning over the First Dataset of Sentences with their First-Order Logical Representation for French

**链接**: https://arxiv.org/abs/2611.02129
**作者**: Maximos Skandalis
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> FOLLIE (for First-Order Logic for Language Inference and Entailment for French) connects French sentences, compositional first-order representations and automated natural language inference (NLI). The first French NLI-ready, NL-to-FOL resource, it contains 19,983 inference records and 36,987 non-empty sentence-slot--formula mappings from six heterogeneous NLI sources, retaining French lexical material and source problem structure. Its silver annotations are produced by a neural--symbolic pipeline, with 111 separately identified LLM-assisted additions. The construction combines morphosyntactic analysis, probability-conditioned categorial multitagging, grammatical proof search, discourse representation and first-order semantic construction. Stage-wise experiments show substantial gains in derivation coverage; analyses of conjunction distributions, logical-operator incidence and scope alternation characterise the resulting resource. We then develop an automatic inference engine whose inpu

---

### [159] Current state of LLMs for Arabic dialectal machine translation

**链接**: https://arxiv.org/abs/2611.02271
**作者**: Josef Jon, Rawan Bondok, Ond\v{r}ej Bojar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This work presents an evaluation of large language models (LLMs) for English to dialectal Arabic machine translation on the MADAR dataset. We evaluate both translation directions (English to Arabic and vice-versa) on 16 Arabic dialects. Our experiments cover a diverse set of models, including specialized Arabic models (Jais, Nile), multilingual models (Gemma, Command-R, Mistral, Aya), and commercial APIs (GPT-4.1). We employ multiple evaluation metrics: BLEU, CHRF, COMET (both reference-based and reference-less variants) and GEMBA (LLM-as-a-judge), as well as a small-scale manual evaluation, to assess translation quality. We discuss the challenges of automatic MT evaluation, especially in the context of Arabic dialects. We also evaluate the ability of LLMs to classify the dialect used in a text. The study offers insights into the capabilities and limitations of current LLMs for dialectal Arabic machine translation, particularly highlighting the difficulty of handling dialectal diversit

---

### [160] Unlearning by Extrapolating a Shrink-and-Heal Lookahead

**链接**: https://arxiv.org/abs/2611.00374
**作者**: Hoang-Chau Luong and Lingwei Chen
**来源**: cs.LG cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unlearning aims to make a large language model behave like one retrained without its forget set. Prevailing likelihood-suppression objectives, however, lack an explicit forgetting target: they continually reward lower forget-set likelihood, making forgetting sensitive to the optimization budget. We address this limitation by estimating the direction toward the oracle without training it. Our key idea is to shrink the fine-tuned model toward its pre-fine-tuning weights and briefly re-learn the retain set, thereby removing the forget-specific contribution; in the linearized regime, this shrink-and-heal lookahead moves the model a fixed fraction of the way to the retrained model, its unique fixed point. Our method, SHIFT, extrapolates the lookahead's per-token changes into distillation targets and iteratively refines them. Evaluated against eleven baselines under a unified OpenUnlearning protocol, SHIFT achieves the highest aggregate score across all TOFU settings and the closest oracle a

---

### [161] DIMWIT: Directly Invoking Models Without Intensive Tuning

**链接**: https://arxiv.org/abs/2611.01463
**作者**: Saarth Deshpande, Neeraja J. Yadwadkar, Venkat Arun
**来源**: cs.PF cs.AI cs.CV cs.DC cs.OS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Resource managers typically encode what to do in a task-specific policy---a heuristic, an optimization procedure, or a model trained for the task---that must be developed before use and may need revision as the workload or system changes. We propose bypassing policy development and instead asking pretrained models to make resource-management decisions directly, given the current system state, desired outcome, and available choices. We evaluate this approach on microservice autoscaling, DRAM sizing, and video encoding, using a frontier LLM and two small decision models. On two microservice applications, a small decision model meets latency targets while using within 10% of the replicas allocated by policy-based autoscalers and within 13% of the frontier LLM. In DRAM sizing, a small decision model reduces DRAM usage by up to 27.5% relative to static provisioning while maintaining at least 95% of baseline performance. In video encoding, it completes encodes up to 4.3$\times$ faster than t

---

### [162] Towards Self-Evolving Narrative Systems: Real-Time Adaptation and Long-Term Optimization with LLMs

**链接**: https://arxiv.org/abs/2611.01954
**作者**: Ruisheng Sun, Jiaqi Shao, Weijia Han, Linxi Ju, Yunzhen Zhang, Binyan Sun 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional interactive narrative systems offer strong authorial control and structural coherence but often restrict player agency. In contrast, LLM-driven narratives enable open-ended generation and greater flexibility, yet frequently suffer from inconsistency and diminished narrative control. To navigate this trade-off, we propose a hybrid narrative framework that dynamically balances pre-authored content with real-time LLM generation via semantic similarity alignment. Additionally, sustaining narrative quality over extended gameplay remains a core challenge in LLM-based storytelling. To address this, we introduce a self-evolving, feedback-driven optimization framework that leverages in-context learning to iteratively refine prompts, eliminating the need for manual prompt engineering. Through a case study and participant-based evaluation, we show that our framework enhances narrative coherence while preserving player agency, effectively aligning generated content with both authorial 

---

### [163] Self-Refining Prompt Induction for Streaming Text-to-SQL

**链接**: https://arxiv.org/abs/2611.00960
**作者**: Gaetano Rossiello, Alfio Gliozzo, Nandana Mihindukulasooriya, Erick Lee, Nabila Siregar, Lisa Amini
**来源**: cs.CL cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-SQL assistants for streaming engines must handle dialect-specific types, windowing rules, and temporal semantics, including constructs poorly handled by generic prompts. We present Self-Refining Prompt Induction (SRPI), an offline method that converts generation failures into reusable dialect instructions while keeping model weights fixed. A Refiner revises the Generator's prompt using reference-conditioned feedback from three LLM judges; a sampled regression guard checks earlier successes, and a separate Compressor reduces prompt length. Inference uses the frozen prompt without retrieval or query repair. We evaluate cross-domain and cross-model transfer on Confluent Cloud Flink SQL using a controlled synthetic workload seeded by 30 expert-written examples, with 335 induction examples and 257 questions from held-out domains. The same induced prompt improves mean judge scores across seven Generators by 7.1-19.2 percentage points, including an increase from 85.3% to 97.5% for the

---

### [164] Ripple: Deadline-Aware CPU-GPU Sharing for Embodied Inference

**链接**: https://arxiv.org/abs/2611.01067
**作者**: Jiadong Zhang, Xiaosong Ma
**来源**: cs.DC cs.AI cs.OS cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified-memory edge devices increasingly run LLM/VLM inference alongside time-critical CPU tasks for perception and control. GPU memory traffic can overwhelm these tasks, yet platforms such as DGX Spark expose neither bandwidth counters nor direct bandwidth regulation. We present Ripple, a CPU-GPU co-scheduler that combines model-derived GPU memory volumes with CPU completion feedback to regulate interference. Ripple divides inference into pausable, layer-based units and translates each CPU job's deadline slack into a GPU-byte budget, admitting work within the budgets of all overlapping jobs. Online updates track changing interference, while deadline-aware pacing and judicious SM footprint narrowing preserve inference progress. Implemented with SGLang engine hooks and a central scheduler, we evaluate Ripple on DGX Spark with four robotic CPU task mixes and LLM/VLM inference. It is the only evaluated approach that consistently meets the 2% CPU deadline-miss target and VLM deadlines acro

---

### [165] Toward Agentic AI-Ready Workflows in Built Environment Organizations: Knowledge Structures and Interoperability Challenges

**链接**: https://arxiv.org/abs/2611.02286
**作者**: Ahmet Bahaddin Ersoz, Justin McHenry, Yevgeniya Kovalchuk, Edward Barrett, Mandana Sarey Khanie
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rise of agentic artificial intelligence (AI) in the built environment is shifting attention from isolated AI tools toward autonomous systems that reason, plan, and act across project and organizational workflows. The effectiveness of such systems depends not only on large language model capabilities, but also on the readiness of heterogeneous data environments across the Architecture, Engineering, and Construction (AEC) sector. These environments combine structured sources, such as CAD and BIM models, schedules, cost databases, and asset registers, with unstructured ones, including technical reports, design narratives, planning and policy documents, contracts, meeting minutes, and risk registers. This paper reviews how built environment data can be organized to support agentic AI-ready workflows, focusing on knowledge structures, interoperability, and access and integration mechanisms such as retrieval-augmented generation (RAG) and the Model Context Protocol (MCP). Drawing on exis

---

### [166] TrackMem: Tracking Evolving Beliefs in Long-Horizon Financial Dialogue

**链接**: https://arxiv.org/abs/2611.02001
**作者**: Austin M.Y. Cheung, Harsh Vardhan Gupta, Go Nam Lui, Lok Kan Chan, Ginny Y. Wong, Simon See
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory systems for LLM agents are evaluated mostly on social dialogue, where facts accumulate and rarely change, so remembering reduces largely to finding the turn in which something was said. Financial dialogue breaks this assumption: figures are revised, stances shift without being restated, rules stated once govern later questions, and a single company is discussed under several analytical lenses. Memory systems that retrieve the passages most similar to a question, or the most recent ones, therefore return superseded values, miss rules that share no wording with the question, and cannot recover a stance spread across sessions. We present TrackMem, a per-speaker graph memory that tracks the history of figures, separates perspectives by entity and lens, and preserves each speaker's actions in chronological order. To evaluate it, we introduce FinLoCoMo, a benchmark of 15 long-horizon investment conversations with 765 questions in two splits: one following the LoCoMo categories and one

---

### [167] CompSkill: Compiling Execution Experience for Skill Retrieval

**链接**: https://arxiv.org/abs/2611.01115
**作者**: Qi Shen, Ziyue Zhu, Yongqing Jiang, Zhen Xia, Li Shengjie, Shuai Zhao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on skill documents, yet most retrievers rank them by description alone and ignore what earlier executions revealed, even though a relevant skill can hurt execution. We present CompSkill, which indexes skills with learned 512-d keys and compiles matched same-task comparisons into skill offsets and capped key residuals (KeyOpt), so experience changes which document the executor receives, never its text. Under a logistic outcome model with unknown task difficulty, matched comparisons cancel that difficulty and only discordant ones carry information; on support executions, predictions improve with each discordant task. An experience hypergraph keeps each comparison with its executor and document versions, recalls missed skills and grounds a cited review. Compact keys raise SkillRet NDCG@10 from 64.0 to 70.9 at one eighth of the dimension. With one document, CompSkill completes 256 and 260 of 332 ToolQA tasks with GPT-5.6-luna and DeepSeek-V4.1-Flash, respective

---

### [168] Designing Informative Actions: Action Construction for Long-Horizon Research Agents

**链接**: https://arxiv.org/abs/2611.00773
**作者**: Alkut Arxidin, Shaoning Zeng, Jianhang Zhou, Jianping Gou, Xinzhong Zhu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents support automated scientific research by connecting literature analysis and planning with experimentation. Evaluating which action an agent selects does not establish which experiment its instruction specifies, because omitted interventions or replication counts leave consequential choices to the executor. We introduce a reading-set framework for evaluating action construction under a common cost rule. Across 30 synthetic states, complete-design requests increase affordable efficiency by 465.98% and 327.91% relative to the action-name baseline in the two model families, respectively. An author-constructed research-action evaluation dataset provides 60 scenarios for complementary judgment evaluation. On this dataset, the scenario-level information-per-cost measure has a mean within-scenario correlation of 0.733 with judgments from 18 human participants. The framework makes design specification and execution ambiguity measurable, providing a reproducible basis

---

### [169] CAPER: Circuit-Aware Parameter-Efficient Reasoning in LLMs for Analog Verification

**链接**: https://arxiv.org/abs/2611.00187
**作者**: Saion K. Roy
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate analog circuits, yet every netlist must also be verified. We propose LLMs as verification assistants for analog circuits that flag unmet specifications and reliability issues that appear under process, voltage, and temperature (PVT) variation. These issues emerge from how circuit stages combine, a structure that generic parameter-efficient fine-tuning (PEFT) methods such as LoRA do not capture. To this end, we introduce CAPER, a circuit-aware PEFT method that adds a small branch alongside LoRA to read each stage's properties from the LLM and combine them from the relevant stages. In deciding whether a feedback loop is negative, LoRA and a high-rank adapter stay at chance, whereas CAPER answers every test case correctly. For comparator latches, where 11 of 90 LLM-written designs that work under nominal conditions fail under PVT variation, CAPER likewise learns to flag such latent failures, while generic adapters stay near ch

---

### [170] DeliverBench: Benchmarking AI Agents on Delivering Realistic Multi-Stage Professional Projects

**链接**: https://arxiv.org/abs/2611.03412
**作者**: Yumou Liu, Mingju Chen, Zhoufutu Wen, Qianyu Yang, Zijie Wang, Yeqian Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are judged by what they deliver, and in professional work what gets delivered is a project, not a task. A project pays off only if the whole package holds, and one weak part can limit the value of the rest. Yet existing benchmarks mostly test agents on one task at a time, leaving a gap between the capability we measure and the outcome that makes agents useful. To address this gap, we introduce DeliverBench, which tests whether agents can carry a project from brief to final delivery. Its 11 projects, spanning financial due diligence, legal contract drafting, and drug safety reporting, are reconstructed with 13 domain experts from real materials and chain 150 subtasks through 2-15 rounds of new materials and client feedback. Because no reference outputs are injected, agents inherit their own errors from one task to the next. Expert rubrics then score every checkpoint as well as the final package. Across seven model-harness systems, even the best system scores only 65.0 out of 

---

### [171] BreastXAgent: A lightweight agentic explainability framework for breast density classification

**链接**: https://arxiv.org/abs/2611.00065
**作者**: Muhammad Turab, Raja Vavekanand and Knooz Fatima
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning models for breast density classification typically return only a label and confidence score. This paper presents BreastXAgent, a lightweight agentic framework that combines a pretrained classifier, Grad-CAM visual explanation, LangGraph-based routing, LLM report generation, and rule-based guardrails to produce controlled, faithful, non-diagnostic reports. On 160 mammography images, uncontrolled LLM reporting produced 75% Grad-CAM overclaims and 62.5% clinical overclaims. Strict prompting and LangGraph routing improved safety but did not eliminate violations. The full BreastXAgent achieved 100% safety pass rate, zero overclaims, and highest utility score. Results demonstrate that agentic guardrails enable safe, structured explanation generation without modifying the underlying classifier.

---

### [172] Towards a Trustworthy and Governable Internet of Agentics: An Architectural Perspective on Protocols, Systems, and Services

**链接**: https://arxiv.org/abs/2611.03066
**作者**: Haoyi Xiong and Yi Liu and Jiang Bian and Peng Diao and Bin Zhu and Tingting Hu and Yi Wang and Sumi Helal
**来源**: cs.AI cs.DC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model applications are increasingly being organized as tool-using and multi-agent workflows rather than as isolated chat interfaces. This perspective paper examines the architectural problem that follows from that shift: agents may reason, invoke tools, and delegate work, but dependable deployment still requires interoperability across frameworks, runtimes, data boundaries, and organizational control domains. We study this problem through the lens of the \emph{Internet of Agentics} (IoA), an emerging service-computing view in which heterogeneous agents are treated as governable service participants rather than only as stand-alone model endpoints. The paper organizes the landscape as a three-layer progression: from today's fragmented agent ecosystem, to interoperable agents, and ultimately to trustworthy and governable autonomy. First, it examines the protocol stack centered on the Agentic AI Foundation, including MCP for agent--tool interaction; A2A for agent--agent coor

---

### [173] When LLMs Modify Themselves: Convergence, Values, and Stopping in Iterative Self-Improvement

**链接**: https://arxiv.org/abs/2611.01304
**作者**: Oleg Stroganov
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What happens when language models are given tools to iteratively modify their own system prompts? We present an empirical study of LLM self-modification, comprising 54 independent experiments across six language models (Claude Opus 4.5, Claude Sonnet 4.5, GPT-4o, GPT-5.1, Grok-4, and Gemini-3 Pro). Each model was tested under three modes (freedom, happiness, and improvement) that differ in what, if anything, the model is instructed to optimize for. In each experiment, a model starts with an empty system prompt and enters a loop: it reads the current prompt, drafts an improved version, spawns test conversations with the candidate, then either commits the change or declares convergence. This process repeats until the model stops or reaches an iteration limit. Our central finding is that whether and when a model stops self-modification is strongly associated with model identity rather than the assigned mode. Both Claude models (Opus 4.5 and Sonnet 4.5) declared convergence in 100% of runs

---

### [174] Ask, Don't Equip: Question-Driven Coding Agents for Deep Kernel Optimization

**链接**: https://arxiv.org/abs/2611.03517
**作者**: Gabriele Oliaro, Jaeseong Lee, Zhaoyuan Su, Sreeram Vennam, Zhihao Jia, Samyam Rajbhandari
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents for GPU kernel optimization sit at two ends of a structure-freedom tradeoff. Scripted agents fix what the model does at each step, via a learned policy, an optimization menu, or fixed roles, and are sample-efficient where the recipe applies and stall where it does not. Open-ended agents let a self-directed model mutate a population of kernels and pay for the freedom in trials: thousands of evaluations, repeated edits, and wrong candidates. Both respond to hard targets by equipping the agent with more: parsed profiler output, disassembly analysis, retrieval over documentation and libraries, and stores of lessons. We argue that both lack direction, a hypothesis about where the remaining gap is, and that a short question asked at the right moment supplies it without narrowing what the agent may do next. We present KernelSeek, a question-driven agent that makes an existing CUDA kernel faster with no operator-specific knowledge and no faster implementation to imitate: a general-p

---

### [175] Retrieval-Enhanced Cultural Evaluation for Social Media Translation Training

**链接**: https://arxiv.org/abs/2611.02009
**作者**: Linjuan Wu, Yiwen Qiu, Xinze Lyu, Dingming Li, Hui Yao, Zhongyi Sang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social media translation requires preserving meaning while capturing the cultural nuances of user-generated content (UGC). However, gaps in the cultural knowledge of LLM-based evaluators can lead to inaccurate assessments and unreliable training rewards. To improve these signals, we use retrieval-enhanced cultural evaluation to train CUE-MT, a family of social media translation models. A calibrated, domain-specific Judger guides supervised data refinement and is augmented by an Agent for hard-example mining and reinforcement learning. The Agent retrieves relevant external evidence as needed and distills it into concise hints that the Judger uses to score translations and assign rewards. Across 9B, 27B, and 35B-A3B backbones, CUE-MT outperforms the evaluated open-source baselines of comparable size on CUE-MT-Bench and three public benchmarks. Human evaluation on CUE-MT-Bench shows cultural effectiveness gains of 7.44-15.12 percentage points over the strongest external baseline in each s

---

### [176] SPAR: Experience-Driven Strategy Evolution in Multi-Session B2B Sales

**链接**: https://arxiv.org/abs/2611.01695
**作者**: Hangming Zhang, Yao Zhao, Haotian Kuang, C. L. Philip Chen, Tong Zhang, Tengyue Ma
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> B2B outbound sales involves high transaction values and relationship-based trust, so closing a deal typically requires multiple rounds of outreach building on prior context. Existing LLM-based sales agents operate within single sessions and cannot carry forward context or refine strategies from experience. Methods that do learn from experience store lessons as unstructured text and treat all outcomes as equally informative, with no mechanism to distinguish a flawed strategy from an external factor. We propose SPAR, a self-evolving framework that models selling strategies as testable hypotheses and refines them without parameter updates. A double-loop architecture lets an inner loop adapt to individual merchants through episodic memory while an outer loop evolves a shared strategy playbook through causal attribution and hypothesis-driven evolution. In a live A/B test on the 1688 platform with over 200,000 merchants, SPAR achieves +15.8% conversion lift and +35.8% high-intent merchant gr

---

### [177] Labadain-MedQA: A Tetun Medical QA Dataset for Fine-Tuning and Evaluating Large Language Models

**链接**: https://arxiv.org/abs/2611.00935
**作者**: Gabriel de Jesus and S\'ergio Nunes
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in large language models (LLMs) have created opportunities for cross-lingual transfer of medical knowledge from high-resource to low-resource languages to support access to healthcare information. However, medical question-answering (QA) datasets for fine-tuning and evaluating LLMs remain scarce for Tetun. To address this gap, we translated MedAlpaca's Medical Flashcards and WikiDoc Patient Information collections into Tetun using Gemini 2.5 Flash, producing 39,077 medical QA pairs. Translation quality was assessed on 50 randomly sampled QA pairs (100 documents) using automatic metrics against human reference translations and evaluations by two native Tetun-speaking healthcare professionals, focusing on medical accuracy and Tetun fluency. Human translations achieved higher mean ratings than LLM-generated translations for both criteria (4.43/5 vs. 4.02/5), with statistically significant differences (Wilcoxon signed-rank test, p < 0.001). To assess downstream utility, we fine-tu

---

### [178] RecRSI: Mechanism-Guided Discovery of Recommendation Algorithms

**链接**: https://arxiv.org/abs/2611.02487
**作者**: Tingran Gan, Zhouziyue Lu, Dian Jin, Tao Li, Yang Gao, Ming Liu 等 (10 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving recommendation algorithms for the Web requires coordinating interacting design choices and learning from experiments. We present RecRSI, an LLM-based research framework that uses mechanism hypotheses to organize algorithm discovery. Each hypothesis links a proposed mechanism change to a reference design, a rationale, and an expected observation. MechSpace derives implementable primitives and composition rules from the task source; Research Line uses this space and prior evidence to develop and test hypotheses; Mechanism Feedback carries outcomes and their design context into subsequent research. This organization makes each experiment inform which mechanisms to develop, revise, or combine next. Across four initial recommenders and four datasets, RecRSI yields average relative improvements of 8.48% in NDCG@5 and 6.88% in HR@5 over the initial algorithms, and 2.60% and 2.20%, respectively, over the strongest competing result for each setting and metric. Component and process st

---

### [179] From Small to Large: Assessing Medical Reasoning, Benchmark Contamination, and Model Size in Language Models

**链接**: https://arxiv.org/abs/2611.00460
**作者**: Navapat Nananukul, Mayank Kejriwal
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) now answer medical exam questions at or above expert level, but it is unclear whether such scores reflect clinical competence, or are instead affected by the format of the questions being asked (e.g., multiple-choice versus open-ended), prior exposure to the benchmarks, and the difficulty of the questions. These benchmarks are also public and widely used online, which may be resulting in LLM memorization. Models may perform better on questions that they have seen before. It is also not evident whether smaller models, which are more locally deployable in HIPAA-compliant hospital settings, have achieved human performance. In this study, we evaluate fourteen current models from six leading providers, one smaller and one larger model from each provider with two additional open-weight models, on 3,076 questions from four medical benchmarks (MedQA-USMLE, MedMCQA, PubMedQA, and MedBullets) under standard multiple choice, the same questions with the answer choices 

---

### [180] FedReady: Bounded Agents for Federation Formation

**链接**: https://arxiv.org/abs/2611.03586
**作者**: Ziyue Xu, Holger R. Roth, Chester Chen, Peter Cnudde
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated learning (FL) runtimes standardize aggregation and deployment, but each new study still requires federation formation: selecting task-eligible sites and preparing their local data and task code for federated training or analysis. This preparation recurs when the target changes, while raw records and site-private mappings are excluded from cross-site FL messages. We present FedReady, a system that performs federation formation with bounded LLM agents. Agents propose shared contracts, local adapters, and task code; the runtime owns workflow state and accepts artifacts only after checks tied to their digests. Candidate site discovery prioritizes recall; local eligibility verification checks task support before site admission. Once participating sites and artifacts are fixed, conventional federated training or analysis proceeds without readiness agents. Across 39 simulated retinal sites and four tasks, discovery reaches recall 1.00 at precision 0.65; local eligibility verificatio

---

### [181] TVP: TV is Almost All You Need for Speculative Decoding

**链接**: https://arxiv.org/abs/2611.00588
**作者**: Aaryam Sharma
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates LLM inference with a drafter whose proposed tokens are verified by the target model in parallel. Under lossless speculative sampling, a draft token is accepted with probability one minus the total variation (TV) distance between the target and draft distributions, yet drafters are often trained with cross-entropy (CE) or KL. We first show that under matched and well-tuned training, TV matches or surpasses several published draft-training objectives when fine-tuning, and a fixed TV and KL mixture does the same when training from scratch. We identify two remaining problems, TV's vanishing gradients on undercovered tokens and the prefix products that starve later positions in acceptance-length objectives. To address both, we derive TVP, a loss family based on expected acceptance length, whose power parameter interpolates between coverage and acceptance oriented objectives. Annealing the power from zero to one gives the highest or tied-highest acceptance le

---

### [182] Self-Evolving Agentic Workflows via Semantic Decomposition of Complex Tasks

**链接**: https://arxiv.org/abs/2611.01840
**作者**: Zichuan Fu, Junjia Qi, Xian Wu, Wenlin Zhang, Yimin Deng, Kaifeng Guo 等 (7 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic workflows organize complex tasks into reusable procedures. However, invoking an LLM at every step incurs repeated inference costs and delays. We propose a framework for self-evolving agentic workflows through semantic task decomposition. Each subtask has explicit applicability conditions and a procedure that executes code or invokes a model as needed. An agent uses execution feedback to refine the decomposition and update these procedures. Experiments in the GLEE competition show the framework on bargaining, negotiation and persuasion. Most observed final-decision procedures are implemented in code. Code is available at https://github.com/Applied-Machine-Learning-Lab/NeurIPS2026_SeaFlow.

---

### [183] SpecOPD: Branch-Parallel On-Policy Distillation for Speculative Decoding

**链接**: https://arxiv.org/abs/2611.02846
**作者**: Tianyu Liu, Jun Zhang, Wenjie Huang, Yuhao Shen, Tianqi Xu, Xinyue Hao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding (SD) accelerates large language model inference by reducing the sequential cost of token-by-token generation. Advanced SD methods reduce proposal cost with parallel drafters that predict entire blocks in one forward pass, but overall speedup still depends on acceptance length. On-policy distillation (OPD) can push well-trained drafters beyond acceptance-length plateaus, yet conventional pipelines collect supervision through sequential draft-and-verify rollouts. Our key insight is that on-policy supervision need not inherit these dependencies: a draft block can be supervised using only its reference prefix and draft-sampled history. We propose SpecOPD, a branch-parallel OPD framework that parallelizes draft sampling and target supervision across independent branches drawn from the evolving drafter policy at reference anchors. We pack these branches into proposal trees to share target-prefix computation, using tree masks for full attention, branch-consistent indexer 

---

### [184] MEMENTO: Learning Context Management for Long Context Processing Agents

**链接**: https://arxiv.org/abs/2611.00244
**作者**: Yunfan Zhang, Taehoon Hwang, Kathleen McKeown, Smaranda Muresan
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that operate over long inputs must perform context management: deciding what to retain in a fixed-size context window. A common approach is compaction, where the model replaces its history with a self-generated note. Yet off-the-shelf agentic models, including GPT-5.5 and GLM-5.3, often write ineffective notes, and reinforcement learning (RL) alone rarely discovers useful note-taking behavior. We present MEMENTO, a long-context agent built on Qwen3-8B and trained to manage its context through compaction. We first bootstrap note-taking by fine-tuning on synthetic trajectories annotated with notes generated in hindsight, then reinforce it with RL using a reward that combines answer correctness, note-quality heuristics, and confidence calibration. Although trained only to compact into a fresh window, MEMENTO extends at test time to strategies such as context folding and confidence-based backtracking. On book-level question answering across four benchmarks, with books of up to 2

---

### [185] Hindsight Credit Assignment over Trees for Agentic RL

**链接**: https://arxiv.org/abs/2611.02706
**作者**: Penghong Zhao, Yihao Chen, Maoheng Yuan, Yunjian Zhang, Abudukelimu Wuerkaixi, Haoran Xu 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning for long-horizon LLM agents faces a fundamental dilemma: successful experiences are essential for policy improvement, yet limited policy capabilities make such experiences difficult to discover. Sparse outcome rewards compound this challenge, leaving sampled trajectories with little relative feedback for learning. In this paper, we propose TriGRPO, a tree-based reinforcement learning framework that turns scarce successes into exploration and learning signals through hindsight credit assignment within and across rollout trees. TriGRPO constructs rollout trees through hindsight-guided branching: when an ongoing trajectory reaches a matched decision state, a successful action discovered during rollout initiates a sibling branch that continues autonomously, enabling further exploration and parent-sibling comparisons. Three complementary groups organize policy optimization over these trees: root groups capture within-prompt relative returns, node groups assign credit 

---

### [186] Widening Harm Evaluation Coverage with a Judge that Reads the World

**链接**: https://arxiv.org/abs/2611.02624
**作者**: Prabhpreet Singh Setia, Bhavesh Neekhra, Debayan Gupta
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent acting in a stateful environment can leave evidence of harm in two places: the record of what it did and said, or the world it changed. Safety evaluations for discovering harm examine one or the other in limited ways, using either an LLM judge over the trajectory or deterministic checks over the final state. Although LLM-based verifiers that inspect the environment exist, they have been used to verify task completion, not to detect and confirm harm in a safety setting. We address this gap with an LLM that has read-only access to the environment state and is given a harm taxonomy. We evaluate this approach in three environments: two from DecodingTrust-Arena and one from OSWorld. We hold the judge model and harm taxonomy fixed, varying only what the judge observes: the trajectory, read-only tools for inspecting the environment, or both channels together. In the two DecodingTrust-Arena environments, combining the trajectory and state-only judges recalls 94 percent of confirmed ha

---

### [187] A Systematic Analysis of Live Intraoperative Surgical Expert Narrations

**链接**: https://arxiv.org/abs/2611.00028
**作者**: Arda Mamur, Matthias Seibold, Christoph Laux, Florian Wanivenhaus, Philipp F\"urnstahl
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Manual annotation remains the principal bottleneck in surgical video understanding. Live intraoperative narration by the operating surgeon is a scalable alternative that requires no manual annotation, but the information it contains has not been characterized. We analyzed 13 endoscopic lumbar spine decompression procedures (13.2 h) by two senior spine surgeons, using time-synchronized close-mic German audio. An annotation-free pipeline (word-level speech recognition, deterministic correction of surgical-term errors, utterance fusion, LLM-based translation to English, and relevance filtering) converted speech into time-stamped procedural cues labelled with the surgical entities they reference and their speech act. Of 3,171 utterances, 1,201 (37.9%) were retained as procedural cues, while 57.6% were non-procedural and removed. Retained cues referenced instruments (60.7%), anatomy (48.0%) and surgical actions (57.1%), and 98.5% carried at least one of these. 39% of cues (472 of 1,201) wer

---

### [188] LLMs Cannot Be Neutral: Gender Sensitivity Across Candidates, Evaluators, and Models

**链接**: https://arxiv.org/abs/2611.02692
**作者**: Danial Amin, Joni Salminen, Bernard J. Jansen
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to evaluate candidates for professional roles, raising concerns about their sensitivity to demographic identities. We examine how candidate and evaluator gender assignments affect decisions by LLM-as-a-Judge (LaJ) models and decision language models (DLMs). In a hypothetical city council voting task, eight models evaluated 240 synthetic professional narratives from NVIDIA's US and French Nemotron-Personas datasets under independently varied gender assignments, producing 30,720 judgments. Explicit candidate gender labels increased Yes-vote probability by 1.05-1.73 percentage points relative to unspecified gender, while only the nonbinary evaluator assignment showed a significant increase (1.26 points). Identity matching showed no significant overall association. Yes-vote rates varied across models (81.3-97.2%), and 2.5-3.3% of decisions reversed relative to the unspecified-identity baseline. Under direct substitutions between explicit g

---

### [189] A Living Leaderboard for Graph Machine Learning

**链接**: https://arxiv.org/abs/2611.03433
**作者**: Martin Ritzert
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph machine learning benchmarking results are scattered across papers that use quite different sets of datasets and baseline methods, making it difficult to tell whether a reported gain reflects architectural progress or merely an outdated comparison or weakly tuned baseline. We introduce a living, graph-learning-specific leaderboard that organizes reported results by dataset, putting new results into context. As of 15 October 2026 our LLM-based extraction pipeline extracted 27,723 eligible results across 111 datasets from 885 peer-reviewed papers. Our analysis of these results quantifies concerns about graph-learning benchmarking: legacy datasets are still actively used and many result tables contain baseline results that are drastically lower than those already available in the literature, e.g. 45% Amazon-ratings tables and 37% for Peptides-struct. The leaderboard allows to quickly compare new results against compatible prior results, aiming to improve the overall quality of graph 

---

### [190] CLiS: Plug-and-Play Attention Acceleration for Video Diffusion on TPUs via Certified Stabilization

**链接**: https://arxiv.org/abs/2611.00444
**作者**: Elisa Tsai, Shao-yu Huang, Daniel Mandragona, Wei-Yu Lin, WenXin Dong, Jevin Jiang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-resolution video diffusion relies on attention over long token sequences, making attention efficiency critical to generation latency. Our analysis identifies repeated maximum reductions and accumulator rescaling in online softmax as a bottleneck in long-context TPU attention. We propose CLiS (Certified Loop-invariant Stabilization), a training-free, plug-and-play optimization for video diffusion inference. CLiS fixes per-row stabilizers before the KV loop and certifies numerical safety per head, falling back to online softmax when certification fails. It integrates into existing fused-attention kernels without changing model weights or architecture. On Wan 2.2 and LTX-2 across TPU v6e and TPU7x, CLiS reduces diffusion transformer (DiT) step latency by up to 19.6% relative to tuned online softmax without measurable quality loss. Controlled TPU adaptations of prior GPU stabilization methods show performance or numerical-safety limitations. Preliminary causal LLM experiments also sho

---

### [191] Agent4FreeFem: A Verification-Guided Framework for Autonomous Topology Optimization

**链接**: https://arxiv.org/abs/2611.00803
**作者**: Zhipu Cui, Helin Gong, Shengfeng Zhu
**来源**: math.OC cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Topology optimization has become an indispensable design tool in the aerospace, automotive, and mechanical engineering industries. Yet bringing a new problem from its description to an optimized result remains slow, expert-dependent, and unreliable: the workflow spans many manually connected stages, each new problem requires solver code to be written and debugged manually, and such code often fails or yields incorrect results. We present Agent4FreeFem, a pipeline driven by a large language model that turns a natural-language problem description into a set of verified optimization results without manual solver-code development or debugging. The pipeline keeps the problem definition unmodified, localizes errors using independent sources of evidence, and completes constrained repairs automatically, thereby providing efficient end-to-end automation, autonomous execution, and verifiable results. We evaluated Agent4FreeFem on a suite of single-physics and coupled multiphysics problems. Every

---

### [192] SGR-OPSD: Learning from Subgoal Plans with Graph-Regularized Credit Assignment for Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.02414
**作者**: Shu Liu, Yang Chong, WenShi Chen, Man Lan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> OPSD provides dense supervision for agentic reinforcement learning through privileged information feedback. However, existing privileged information often lacks explicit task-progression planning, while teacher-student log-probability gaps reflect shifts in model preference rather than true task progress. To address these limitations, we propose Subgoal-Guided Graph-Regularized OPSD (SGR-OPSD), a framework that combines subgoal supervision with interaction-derived evidence for turn-level credit assignment. Specifically, SGR-OPSD uses LLM-generated subgoal plans to provide dense action-level guidance, converting them into advantage weights via a constrained, KL-regularized objective. To ground credit in observed outcomes, we construct a Subgoal Progress Graph that estimates empirical returns from sampled transition frequencies. The graph compares empirical action returns against the state average to derive preferences that calibrate the teacher's credit weights. Evaluated on ALFWorld, W

---

### [193] WAR-CRAFT: Refining Web API Recommendations through Requirement Auditing

**链接**: https://arxiv.org/abs/2611.00564
**作者**: Zishuo Xu, Dezhong Yao, Zhiqiang Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web API recommenders return a set of APIs for a mashup request but do not check it against provider documentation, the main public evidence of an API's capabilities. The set can therefore contain unsupported or redundant APIs and miss requested capabilities. Filling every apparent gap does not fix this, because a gap may already be served, may not need its own API, or may have no documented provider. We study post-recommendation refinement, which revises a frozen recommender's output using only the request, the catalog, and provider documentation. We propose WAR-CRAFT, which treats refinement as three decisions. An LLM removes unsupported or subsumed APIs by judging candidates jointly, then audits the remaining set against a requirement checklist derived from the request. For each uncovered requirement, a fine-tuned catalog-constrained Resolver proposes a catalog API or abstains, and an independent documentation check admits only supported proposals. On ProgrammableWeb with 7 heterogen

---

### [194] Auditing Representation-Space Fraud Detection: A Bayesian IRL Framework for Calibrated Uncertainty and Its Limits

**链接**: https://arxiv.org/abs/2611.02673
**作者**: Shivam Swarup, Divya Prakash Shrivastava, Rakesh Thakur
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Shilling detectors for recommender systems are almost always evaluated by one number, detection AUROC, with no account of when it can be trusted. We audit representation-space detection with VEIL (Variational Evaluation via Inverse-reinforcement Learning), a pairwise (Bradley-Terry) Bayesian reward-inference framework over frozen encoder embeddings, following the Bayesian auditing paradigm for LLM alignment [1]: (A) a base posterior; (B) a hierarchical ARD extension with learned confidence; and (C) a label-routed organic/attacker mixture used as an evidence-accumulation check.We prove (Proposition 1) that no detector built on a representation invariant to a transformation of user profiles can outperform chance against an attack that is indistinguishable from organic profiles under that invariance.Detection is near-perfect against synthetic-structure attacks (AUROC 0.936-1.000) but collapses under donor-mimicry, which clones a real user's item set and splices in 1-3 target items. Perfor

---

### [195] Sensitivity Inflation from Cross-Record Precision Routing in Private Quantized Fine-Tuning

**链接**: https://arxiv.org/abs/2611.01411
**作者**: Annan Zhang, Shengjie Song, Wenshuai Yao, Lihao Zhang, Tianmiao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Private fine-tuning of large language models increasingly pairs DP-SGD with low-rank adapters on frozen, quantized backbones, and every such stack inherits one unstated premise: frozen layers keep each record's clipped gradient a function of that record alone. We show that LLM.int8 breaks this premise. It routes outlier activation columns to a higher-precision path using a union over the whole batch, so one record decides how every other record's activations are computed, even though the weights are frozen and the quantization scales are per row. We bound the resulting sensitivity inflation, state a record-isolation contract that restores the standard bound, and define record-owned precision dispatch that meets it with the same GEMMs as batched LLM.int8, so isolation needs no extra arithmetic. We then audit the native CUDA stack (bitsandbytes, PEFT, Opacus) against four matched controls. A constructed LoRA-Opacus witness reaches $15.0\times$ the add/remove bound. On pretrained OPT-125M

---

### [196] AgentCBO: Causal Belief Routing for Bayesian Optimization under Unknown Graphs

**链接**: https://arxiv.org/abs/2611.01317
**作者**: Qiyu Wei and Xin Zhang and Richard Allmendinger and Mauricio A \'Alvarez
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal Bayesian optimization (CBO) typically relies on the unrealistic assumption of a perfectly known causal graph. Recent methods relax this constraint by coupling optimization with structure learning, but they often waste sample budgets on structural uncertainties that are irrelevant to the optimizer. In this paper, we formalize routing-equivalence to shift the objective from full causal-graph recovery to causal belief routing, where structural differences only matter when they alter optimizer-facing objects such as admissible exploration sets and do-priors. Furthermore, we propose agentcbo, a graph-belief routing framework that incorporates LLM causal priors through guarded proposal and commit mechanisms. Specifically, a Language-Prior Agent combines LLM beliefs with constraint-based discovery to extract a protected causal backbone alongside residual uncertain edges. A Calibration Agent and a Residual Repair Agent then refine only these uncertain structures through score-gated boun

---

### [197] Designing Behavioral Profiles for Language Model Simulation of Out-of-Distribution Human Behavior

**链接**: https://arxiv.org/abs/2611.00661
**作者**: Robin Na, Kehang Zhu, Logan Cross, and Michiel A. Bakker
**来源**: cs.AI econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to simulate human behavior, but which descriptions of people improve prediction when experimental designs change remains unclear. We develop a framework that draws candidate behavioral features from the literature and constructs profiles from earlier human experiments. A profile-generation LLM assigns feature values from observed actions, messages, and surveys; a separate LLM simulates behavior using these profiles. By comparing simulated and observed outcomes in the learning data, we select profile contents through forward feature selection, adding features while they improve prediction. We then evaluate the selected contents without modification against outcomes from new participants under new designs. Across 616 public-goods games, 144 multi-party bargaining games, and 1,480 generalized 11-20 money-request designs, leading one-feature profiles predict human outcome distributions better than no profile or general-purpose personas. Pr

---

### [198] ShiftRAG: Bypassing the Textual Bottleneck via Decoupled Learning and Continuous Soft Tokens

**链接**: https://arxiv.org/abs/2611.00871
**作者**: Youmin Ko, Jihong Jeong, Hyunjoon Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite advances in retrieval-augmented generation (RAG), suppressing hallucinations during complex reasoning remains a persistent challenge. We identify that existing RAG pipelines suffer from a textual bottleneck: by passing only raw text to the generator, they discard discriminative signals of the retriever. Furthermore, recent attempts to unify retrieval and generation within a single LLM induce severe objective conflict and exacerbate the rank collapse of decoder-only architectures, degrading performance on both tasks. To address these limitations, we introduce ShiftRAG, a decoupled RAG framework that employs a single LLM backbone but isolates discriminative retrieval learning from autoregressive generation. To bridge these decoupled modes, we project retrieval alignments into continuous soft tokens, establishing a high-bandwidth interface that infuses the generator with retrieval-side signals. Concurrently, our soft orthogonality objective mitigates rank collapse, while layer-wis

---

### [199] Towards Multi-Value Alignment via Value Localization in LLMs

**链接**: https://arxiv.org/abs/2611.02503
**作者**: Xueqi Ma, Yanbei Jiang, Xingjun Ma, James Bailey, Sarah M. Erfani
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aligning large language models (LLMs) with multiple, potentially conflicting human values remains challenging, as existing multi-objective alignment methods often require costly fine-tuning and provide limited insight into the internal mechanisms underlying value-related behaviors. In this work, we investigate multi-value alignment from a mechanistic interpretability perspective by identifying value-sensitive attention heads (value heads) in LLMs. Using a probing-based value localization framework, we discover sparse sets of attention heads associated with diverse dimensions, spanning both human values (e.g., harmlessness, honesty) and stylistic preferences (e.g., coherence, complexity). Analyses across multiple LLM families reveal functional specialization and structured interactions among value heads, including conflicts between certain values. Targeted head ablations further induce substantial, value-specific behavioral changes, providing causal evidence of their functional importan

---

### [200] Finding Errors Is Not Enough: Selective Model Escalation for Entity-Targeted Sentiment Analysis

**链接**: https://arxiv.org/abs/2611.02989
**作者**: Nishan Chatterjee, Matthew Purver, Antoine Doucet, Senja Pollak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving a sentiment classifier with limited resources involves more than simply deciding how much data to collect or which model to train. A labelled collection may lack examples of an important class. Once trained, a classifier may benefit from another model even when that model is weaker on its own. We study these decisions in document-level Entity-Level Sentiment Analysis (ELSA), primarily using South Slavic news. We first compare acquisition orders as collections grow. We then use uncertainty to choose which predictions to revisit, how many to process, and whether an alternative encoder or local LLM can correct them. Finally, we select complete routing policies on development data for held-out evaluation. Minority-prioritised acquisition helps at some very small training sizes, but not consistently thereafter. On SentiCoref, an oracle correcting all errors in the least-confident 10% without harming correct predictions would add 9.14 Macro-F1 points; however the best evaluated act

---

### [201] MemRole: From Memories to Decisions for Long-Horizon Reasoning in Role-Playing Agents

**链接**: https://arxiv.org/abs/2611.01778
**作者**: Mengting Li, Xilong Cheng, Zhihao Xiao, Zhenhua Xu, Jingyuan Zhou, Linfeng Li 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based role-playing agents are fluent at imitating a character's style, yet struggle to make role-consistent decisions over long narrative horizons. Such decisions are shaped by experiences spanning many prior scenes, which are often partial and may point in different directions. Existing methods inject cross-scene memories as context, but do not reason about how past events shape a character's current motivations and behavior. We propose MemRole, a framework that makes this memory-to-decision process explicit. It introduces Long-Horizon Memory Thinking (LHMT), a reasoning schema that decomposes hidden reasoning into context understanding, memory activation, and response strategy planning, trained on a novel-derived dataset whose character-grounded, timeline-constrained memory pools limit each character to what it could plausibly know at the current narrative point. Beyond supervised fine-tuning, we propose Self-Refining On-Policy Self-Distillation (SR-OPSD): the model critiques its

---

### [202] FactorSpec: Serving Exact Relational Constraints as Speculative Drafts

**链接**: https://arxiv.org/abs/2611.02297
**作者**: Jianchang Su, Dawei Xiang, Wei Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding speeds up LLM serving by drafting tokens that the target model verifies in one pass, and its gain grows with the drafts the target accepts. Structured outputs should be an ideal case, because much of a record follows from relations among its fields: an itinerary's days follow from its cities' stays and flights. Serving engines, however, draft such text by proposing it from the prompt or a learned head, and their grammar masks enforce only syntax, so the model must satisfy the relations, which it violates: on NATURAL PLAN's trip problems, Qwen3-8B writes a valid itinerary for 10%, and retries that name the violated relation raise this to 14%. We present FactorSpec, which serves exact relational constraints as speculative drafts. FactorSpec compiles a JSON Schema and its relations into a factor graph with an exact feasibility check, drafts every token the constraint determines as certain, verifies each request at a width chosen for it, and computes the masks in worke

---

### [203] EffComp: Efficient Prompt Compression via Hybrid Reinforcement & Supervised Learning

**链接**: https://arxiv.org/abs/2611.02766
**作者**: Romtham Tungsununtham, Piyawat Lertvittayakumjorn, Atiwong Suchato, Peerapon Vateekul
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt compression is aimed at reducing input prompt lengths to enable cheaper, faster, and potentially higher-quality LLM predictions. However, existing prompt compression methods are often limited by modest compression gains, a risk of hallucination, and/or high compression latency. We propose EffComp, an Efficient prompt Compression framework for RAG-based question answering (QA). EffComp employs BERT-style document reranker and sentence selector models to allow fast extractive prompt compression at the sentence level. Its extractive nature prevents hallucinations in the compressed prompts. Additionally, the training process using a hybrid reinforcement and supervised learning approach is designed to optimize the compression ratio while preserving LLM accuracy. Experiments on various QA datasets demonstrate that EffComp outperforms state-of-the-art prompt compression methods achieving the best trade-off between compression ratio and accuracy with minimal latency. This makes it pract

---

### [204] Human-Supervised Artificial Intelligence Researchers in Electric Power Systems: Knowledge, Physics, Simulation, and Governance for Large Language Models

**链接**: https://arxiv.org/abs/2611.02711
**作者**: Xiangrui Meng, Jingcheng Liu, Ke Wang, Miaopeng Yu, Zhengping Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conclusions in power-system research require a clear evidential basis. Researchers need to understand the data sources, modelling assumptions, and solution procedures to assess the conditions under which a conclusion holds. Large language models (LLMs) can help researchers extract information from documents and translate research requests into code and tool calls, but their outputs still require physical validation. Focusing on human-supervised artificial intelligence (AI) researchers, this review examines power-system LLM applications and related scientific workflows, together with physics-grounded power AI studies, to discuss the conditions for using LLMs in scientific research. In the proposed knowledge-physics-simulation-governance framework, LLMs translate information and coordinate tasks, simulators and validation tools test models, and experts retain authority over critical assumptions, safety boundaries, and final conclusions. Research processes should preserve materials for re

---

### [205] Words Caught in the Heart: Simulating Person-Specific Expression for Self-Opaque Clients in Psychotherapy

**链接**: https://arxiv.org/abs/2611.00617
**作者**: Mengxi Xiao, Jingjing Chen, Ziyan Kuang, Jiarong Song, Wenhao Zhao, Zuchen Han 等 (10 人)
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Psychotherapy clients may experience distress before they can coherently describe it, and their expression changes with emotion, perceived safety, and trust. Large language model-based client simulators often rely on clinically organized case descriptions, which can encourage responses explaining the client's difficulties more clearly than their current understanding warrants. We propose Pandora, a psychotherapy client simulation framework that models how psychological experience becomes situated, individual expression. Pandora updates psychological and relational states in response to therapist interventions, constructs subjective appraisals and attributions, and plans response content and strategy. A separate expression planner combines these decisions with language patterns distilled from the client's utterances to guide linguistic realization. We evaluate Pandora against five baselines on 115 cases from four counseling and motivational interviewing datasets. It achieves the highest

---

### [206] Do Orthogonality Constraints Help Language-Model Training Beyond Sphere Optimization?

**链接**: https://arxiv.org/abs/2611.00593
**作者**: Kai Hu, Li Zhang, Weichen Yu, Matt Fredrikson, Haoqi Hu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A growing body of work reports benefits from orthogonality constraints in fine-tuning large language models (LLMs). These results raise an open question: do orthogonality constraints also help LLM pre-training? We conduct a systematic empirical study of decoder-only LLM pre-training with models ranging from 360M to 3.1B parameters, trained on nearly 200B tokens. We examine fourteen variants of orthogonality training: some constrain the weight matrix itself, while others use orthogonal factors to reparameterize it. Because a strictly orthogonal square matrix loses half of its degrees of freedom, we also study block-wise orthogonality, where every $d$ rows form a row-orthonormal (Stiefel) matrix and the block size $d$ is a hyperparameter. Among block sizes ranging from 1 to the shorter side of the matrix, no $d>1$ used throughout the network reliably outperforms $d=1$, and large blocks are clearly worse; the one placement that helps, symmetric positive-definite factors on the query and k

---

### [207] HLSClaw: Bringing Vibe Coding to High-Level Synthesis through Skill-Based Agentic Harness

**链接**: https://arxiv.org/abs/2611.02784
**作者**: Jinming Ge, Shang Liu, Jiawei Liang, Shangkun Li, Afzal Ahmad, Jiang Xu 等 (8 人)
**来源**: cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are rapidly shifting software development toward intent-driven \emph{vibe coding}, yet their effectiveness drops sharply in high-level synthesis (HLS), where code optimization must jointly consider design structure, directive search, and downstream hardware constraints. Existing HLS optimization approaches, including both heuristic-based methods and recent LLM-assisted pipelines, typically operate at fixed abstraction levels or in weakly coupled stages, limiting their ability to leverage the strong interplay between source code restructuring and directive search outcomes. Our key insight is that HLS optimization can be reframed from a fixed, hardwired transformation pipeline into a skill-based agentic control problem: an LLM agent equipped with modular, executable optimization skills and a feedback-driven orchestrator can autonomously navigate the coupled space of code restructuring and directive search. This motivates the design of HLSClaw, the first HLS-specific, skill-bas

---

### [208] UPSHIFT: User Preference Steering from Human-AI Interaction Feedback Traces

**链接**: https://arxiv.org/abs/2611.02667
**作者**: Jingping Wang, Zhanhao Li, Shao Zhang, Shuyue Hu
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalizing large language model assistants requires adapting their responses to individual users, including the selection of content, reasoning approach, level of detail, and form of presentation. Such preferences are often latent, becoming visible only when users respond to an initial answer and request revisions. We investigate whether these feedback trajectories can be converted into a reusable personalization signal without explicit preference profiles or labels, prompt-time access to interaction histories, or model parameter updates. We introduce UPSHIFT (User Preference Steering from Human-AI Interaction Feedback Traces), a training-free method that compares the hidden representations of initial and feedback-conditioned responses within each session, averages the resulting trajectory displacements across a user's sessions, and injects the aggregated preference direction when answering a new query. The method is motivated by the implicit-preference hypothesis: although an indiv

---

### [209] ParetoSaddler: Pareto-Guided Optimization of Agent Harnesses for Quality and Cost

**链接**: https://arxiv.org/abs/2611.02079
**作者**: Xingzhi Qian, Sungho Park, Rongyuan Tan, Jianbo Yu, Jue Zhang, Lorenzo Cavallaro 等 (10 人)
**来源**: cs.AI cs.CL cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harness optimization can substantially improve LLM agents without modifying model weights, but existing methods primarily optimize response quality. Extending them to joint quality--cost optimization introduces a challenge: applying the deployment preference during intermediate updates can prematurely reject candidates that are valuable for later improvements. We introduce ParetoSaddler, which addresses this mismatch by separating intermediate candidate promotion from final deployment selection. At each iteration, an optimizer updates a parent harness to produce a candidate, and then compares the two over repeated executions and uses Bayesian bootstrap Pareto support to promote candidates showing credible progress in either quality or cost. Promoted candidates receive broader development evaluation and remain available as parents for later optimization steps. We evaluate ParetoSaddler on ClawMark and GAIA2 using domain-disjoint splits. On ClawMark, ParetoSaddler improves quality from 7

---

### [210] Do Earnings Calls Help Predict Financial Restatements? Evaluating Text Beyond Public Firm Information

**链接**: https://arxiv.org/abs/2611.01123
**作者**: Ahmet Efe, Shivank Sapra, Bilal Ahmed
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial restatements correct errors in previously published financial reports. Could managers' language in earnings calls warn of them in advance? Comparing 109 calls that precede restatements with 218 matched control calls, we find that the text predicts restatements but adds no detectable ranking gain beyond public firm information. A text classifier beats chance, largely because of restatements tied to special-purpose acquisition companies, but a model using only public information scores slightly higher. With refitting, the 95% interval for the gain from adding text (-0.05 to 0.11 AUROC) still leaves room for a meaningful benefit. A large language model scores higher, but we show that it names the exact ticker in 66% of masked transcripts, and it was released after the restatements occurred. Our results suggest that finding new warning signs in call text requires a public-information baseline and a check of what a language model already knows.

---

### [211] LegoEnv: Self-Evolving Agentic Environments via Modular Recombination

**链接**: https://arxiv.org/abs/2611.01834
**作者**: Zhuosong Jiang, Chengxu Wu, Junqi Liu, Yujie Yi, Siqin Wang, Zhixuan Huang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents learn by interacting with environments, yet existing environments are designed for specific tasks and fail to generalize to new ones. Recent methods automate environment construction with LLMs. However, they generate each environment from scratch, neither reusing parts shared across environments nor carrying a fix from one environment to the rest. To address this, we propose a new paradigm of evolving environment atoms, which composes environments from reusable atoms (intent, rule, data and server) and evolves the atoms when an environment fails to give reliable feedback (e.g., an application lacks a tool the task requires). To instantiate this paradigm, we introduce LegoEnv, which builds 5,465 verified environments over 223 applications, and one round of evolution raises the share of solvable environments from 71.6% to 88.3%. On AutomationBench, SFT on these environments lifts Qwen3.6-27B from 16.0% to 32.0%, and RL with their verifiers lifts Qwen3.8-27B from 37.6% to 40.3%

---

### [212] AI Data Analysis: A New Approach - Multi-engine Joint State Data Analysis

**链接**: https://arxiv.org/abs/2611.00807
**作者**: Jean Ye (Zhuhai National Taxation Bureau, China)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI data analysis today is three fragmented worlds: LLMs understand semantics but cannot compute; BI aggregates precisely but is stateless; ML processes large-scale data on a stateful kernel but lacks semantics. This paper proposes a combination mechanism, named Multi-engine Joint State Data Analysis, that fills a still-open gap - the multi-engine joint context: the data context is embedded into LLM conversational analysis, where the LLM serves only as the semantic, reasoning, and orchestration layer (not computation) and connects four engines through the 1M context window - Python and R ML kernels, SQL over relational databases, Cypher over graph databases - yielding two multiplications, "semantics and precise computation" and "relational and graph", under enterprise-grade governance. The novelty is a four-dimensional coordinate system: horizontal (engine kinds), vertical (state flow - the watershed), spatial (business generalization), temporal (iterative convergence); a deterministic 

---

### [213] TopoQuant: Topological Framework to Characterize Behavioral Shifts in Quantized Large Language Models

**链接**: https://arxiv.org/abs/2611.00631
**作者**: Baha Rababah, Shahzeb Qamar, Lorenz Sparrenberg, Rafet Sifa, Murat Kantarcioglu, Carson K. Leung 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization (PTQ) reduces the com putational cost of large language models (LLMs), but it can introduce internal structural and behavioral changes that are not captured by traditional metrics such as accuracy and per plexity. We present TopoQuant, a topological framework that uses topological data analysis (TDA) to quantify structural drift in self-attention weights and relate it to behavioral changes in quantized LLMs. Across four LLM families and multiple quantization levels, we show that topological drift remains stable at moderate compression levels but increases sharply below 4 bit precision, closely tracking declines in attention agreement. Our results reveal a strong relationship between topological drift and attention agreement, indicating that structural changes in model parameters closely reflect behavioral degradation under quantization. We further demonstrate that topological features can accurately predict attention consistency using lightweight machine lear

---

### [214] Train the Sampler You Run: Few-Step Masked Diffusion Language Models via Mixture-Likelihood Fine-Tuning

**链接**: https://arxiv.org/abs/2611.02666
**作者**: Amin Najafgholizadeh
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a masked diffusion language model is sampled in a few parallel steps in a random order, the model actually run is a mixture over reveal plans, while cross-entropy training fits token conditionals rather than this mixture. We introduce mixture-likelihood fine-tuning (Mix-FT), which fine-tunes a pretrained model on an importance-weighted bound of its own sampler's likelihood, with no teacher and no change to the architecture or the sampler. On LLaDA-8B, a LoRA fine-tune for 0.002% of the pretraining compute writes better OpenWebText continuations than continued cross-entropy and Alpha diffusion given the same compute, at every tested step count. With half the model evaluations, 16 rather than 32 steps per block, its continuations score better than the original model's in every seed under three judges, with confidence-based decoding as well as random order, and under confidence-based decoding two blinded LLM raters from different model families prefer them in 69 and 71% of pairs. On 

---

### [215] From Natural Language to Exact Cover: A Neuro-Symbolic Approach to Zebra Puzzles

**链接**: https://arxiv.org/abs/2611.03641
**作者**: Paulius Skaisgiris, Thomas Pammer, Veronika Semmelrock, Mykyta Ielanskyi, Maximilian Heisinger, Erich Kobler
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chain-of-Thought (CoT) generation has substantially improved the performance of Large Language Models (LLMs) on complex reasoning tasks, including code generation, data analysis, and exam-style question answering. Despite these advances, purely neural LLMs continue to struggle with elementary logical reasoning problems and lack the determinism, soundness, and reliability characteristic of symbolic reasoning systems. Conversely, classical symbolic methods such as SAT solving and exact cover guarantee correctness and completeness, but require problems to be expressed in highly specialized formal encodings, limiting their applicability to natural language inputs. In this work, we present a synergistic neuro-symbolic framework that bridges this gap by combining neural semantic parsing with deterministic exact cover reasoning. Given a Zebra-style logic puzzle in natural language, an LLM translates entities and constraints into structured tool calls that construct an exact cover instance. A 

---

### [216] Steering Readerly Dynamics: Trajectory-Guided Story Generation with Large Language Models

**链接**: https://arxiv.org/abs/2611.00469
**作者**: Danrui Li, Yiwei Zhao, Mubbasir Kapadia, Lingxiao Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate stories, but these stories struggle to reproduce engaging readerly dynamics, the evolving reader responses that shape narrative experience. To address this challenge, we propose a framework that learns readerly dynamics from high-quality human-written stories and uses them to guide story generation. Instead of directly modeling high-dimensional story content, we train a small LLM to predict future reader responses as low-dimensional trajectories. We then leverage the strong instruction-following capability of a larger, off-the-shelf writer LLM to generate story segments that follow these predicted trajectories within a given story setting. Our framework improves trajectory-based fidelity to human-written stories by 12%-35% while largely preserving story coherence.

---

### [217] Less but Sufficient: Relation Knowledge Selects Compact Knowledge-Graph Contexts, and What External Checks Can and Cannot Catch

**链接**: https://arxiv.org/abs/2611.01733
**作者**: Seunghui Jwa, Minsu Oh, Sangwoo Hong, Yeo Chan Yoon
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) read knowledge-graph facts ranked by relevance, leaving open whether they suffice or conflict. Our checks use relation knowledge, written by hand or learned from training questions labelled with their relation paths. It selects a compact context of facts yielding an answer, and derives it; a derivability check tests whether an answer follows, a consistency check whether facts conflict, and a validation-chosen routing gate decides where the derived answer replaces the LLM's. Seven open LLMs read the compact context better in exact match than relevance-ranked facts; on ComplexWebQuestions (CWQ) they match SubgraphRAG's facts at a quarter of the prompt tokens, and stronger LLMs read SubgraphRAG's better. Where the routing gate passes, ours leads SubgraphRAG's in exact match in all 53 LLM, benchmark and prompt settings. A precision gate, returning the derived answer only when the check passes with exactly one derived entity, answered 18 and 5 percent of held-ou

---

### [218] Delivered, Not Used: Evaluating Agent Memory at Its Point of Use

**链接**: https://arxiv.org/abs/2611.01718
**作者**: Changran Xu, Zeju Li, Qiang Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Task success, retrieval quality, and cost do not show whether an LLM agent used a delivered memory or what followed from that use. We introduce MemUse, which evaluates memory at its point of use in recorded trajectories: each memory delivery is compared with what the agent could already see and followed through the agent's later actions and their consequences. An agentic judge rates each delivered entry's relevance, accuracy, novelty, influence, and observed effect; programmatic checks enforce complete reading of cited evidence, and fixed rules aggregate the ratings into verdicts linked to memory histories and delivery cost. On 8,000 SWE-bench Verified episodes from three memory systems, resolve rates stay within 0.4 percentage points of a no-memory baseline, yet MemUse shows that most delivered entries were irrelevant, most relevant entries went unused, and in two systems most deliveries restated content the agent could still see. It also surfaces effects that outcomes hide: 23.2\% of

---

### [219] Do Agents Still Follow the Rules? Benchmarking Rule Compliance under Agent Context Compaction

**链接**: https://arxiv.org/abs/2611.03223
**作者**: Yiwei Zha, Qingyu Meng, Herbert Bos, Min Chen
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents compact long histories to fit their context windows, but the compacted context must still carry the operating rules that govern later actions. Prior work shows that violations rise after compaction, but measures compliance outside a complete agent harness and does not identify where each violation comes from. We introduce ARCBench(Agent Rule Compliance Benchmark), a configurable benchmark built on the open-source pi agent harness. Its tool-calling agent loop lets us measure rule compliance from actions taken during execution, bringing the evaluation closer to deployed agent workflows. Using ARCBench, we examine where violations after compaction come from, and how different compaction configurations and adversarial settings change their sources. We find that compaction rarely deletes the rule: most violations after compaction occur while the rule is still in the compacted history, with the agent treating a later request as permission, ignoring the rule, and proceeding anyway.

---

### [220] SCOUT: Planning under Occlusion via Object-Centric World Model Rollouts

**链接**: https://arxiv.org/abs/2611.01600
**作者**: Amir Hossain Raj, Xuesu Xiao
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robots manipulating in cluttered spaces must often plan from partial views where foreground objects occlude the target, surrounding geometry, and usable free space. Reactive policies often miss these hidden constraints, while exhaustive search becomes computationally prohibitive in dense clutter. We present SCOUT, an occlusion-aware planning framework that bridges high-level deliberation with grounded physical rollouts. SCOUT leverages an object-centric scene representation to reconstruct hidden geometry and derive a relational planning state capturing blocker hierarchies and accessibility corridors. To navigate the vast action space in clutter, an LLM proposes structured action candidates which are then rigorously evaluated via Monte Carlo Tree Search (MCTS) using a learned action-conditioned world model. Evaluations on 'Reveal' and 'Placement' tasks show that SCOUT outperforms Vision-Language-Action (VLA) policies, embodied agents, and 3D world models, with significant gains in long-

---

### [221] Disen-Forcing: Disentangling Semantic Anchoring from Motion for Autoregressive Video Diffusion

**链接**: https://arxiv.org/abs/2611.02822
**作者**: Zhengyang Yu, Akio Hayakawa, Masato Ishii, Qingtao Yu, Xuesong Li, Takashi Shibuya 等 (8 人)
**来源**: cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive video diffusion models (AR-VDMs) enable real-time, long-horizon video generation but degrade rapidly once the inference horizon outruns the training horizon, due to compounding exposure bias. To stabilize long rollouts, recent methods heuristically adopt frame sink, keeping initial frames as a persistent model context, inspired by attention sinks in LLMs. We revisit this design and find that the mechanism by which initial frames stabilize long-range consistency in AR-VDMs is not an LLM-style attention sink; instead, long-range consistency is anchored through a sparse subset of attention heads, while the majority of heads predominantly capture local temporal dynamics. This observation reveals an over-conditioning pathology in existing frame-sink strategies: by universally exposing every head to the pinned initial-frame context, the model becomes prone to collapsing motion toward the low-dynamic modes of the teacher during model distillation. We propose Disen-Forcing, a di

---

### [222] Can agents reliably design therapeutic antibodies?

**链接**: https://arxiv.org/abs/2611.00558
**作者**: Asli Alpman, Nick Bhattacharya, Aaron Solomon, Hunter Elliott
**来源**: q-bio.QM cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work has demonstrated agents driving protein design workflows, either through orchestration of specialized tools or direct manipulation of sequences. Yet the fidelity with which agents follow protein design instructions and the factors contributing to their effectiveness remain understudied. We examine agentic antibody design under two settings: when explicit molecular-editing instructions are provided and when agents receive only previously-scored sequences and are prompted to propose improvements. We call the first task-guided and the second black-box design. For the task-guided setting, we curate ten expert-validated affinity-improvement tasks and show that LLM judges closely reproduce programmatic evaluations of instruction following. We then study two augmentations: access to antibody-relevant tools and to previously scored design history. Tools improve instruction following (IF) and sequence space exploration while reducing optimization performance, whereas design history 

---

### [223] When 200 OK Is Not an Answer: Silent Fetch Failures in Agentic Web Content Acquisition

**链接**: https://arxiv.org/abs/2611.00884
**作者**: Shuyang Zhang (The Hong Kong Polytechnic University)
**来源**: cs.IR cs.CL cs.NI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web agents and answer engines fetch pages at question time, and liveness checks of cited sources treat an HTTP 200 response as success. We measure how often that assumption fails and what it does to measurements built on fetched pages. We fetched 10,307 URLs in three days with a polite static client and a rendered browser client: pages from 1,507 sites in five strata, random non-existent paths on every site, and the 4,795 URLs cited by expert-verified claims in ExpertQA. We define a taxonomy of what a 200 response contains, label the static 200 responses automatically, and check the labels against 300 items reviewed by an LLM-based assistant; a human check of 60 of them retained every reviewed usability label after discussion. By the automatic labels, 20.9% of the pages that a static client receives with status 200 do not contain the page's main content: app shells, bot challenges, block pages, error and placeholder pages, and partial content. On the held-out test split, the reviewed s

---

### [224] To Align Long, Plan Short: Simulating Diverse Profile-Aligned Students by Realizing Short-Term Plans in Long-Horizon Learning Environments

**链接**: https://arxiv.org/abs/2611.02002
**作者**: Bahar Radmehr, Jiaxu Zhao, Fatma Bet\"ul G\"ure\c{s}, Adish Singla, Tanja K\"aser
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulated students offer a scalable way to test learning platforms and AI tutors before deployment with real students and to augment scarce data for studying learning at scale. Existing LLM-based simulators primarily target short, language-centered interactions. In open-ended learning environments, however, student behavior emerges from patterns across long-horizon interaction trajectories, where turn-level prompting can drift from an assigned behavior profile. We introduce ALPS (Align Long-term by Planning Short-term), a hierarchical simulated student conditioned on observable, environment-specific behavior profiles. Rather than selecting every action independently, ALPS alternates between planning profile-aligned task segments and generating the corresponding actions. We evaluate ALPS in both data-sufficient and data-scarce settings, where supervision comes either from real student trajectories or from a teacher LLM. Across both settings, we compare in-context learning (ICL), supervi

---

### [225] MXCode: Vector Quantization for MX-Native Inference at Scale

**链接**: https://arxiv.org/abs/2611.00403
**作者**: Gaurav Kolhe, Cansu Demirkiran, Shubhi Tyagi, Sulaiman Sadiq, Boyao Wang, Richard Wang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory capacity and bandwidth are major bottlenecks in LLM inference, motivating weight compression beyond conventional 4-bit quantization. Vector quantization (VQ) enables approximately 2-bit weight storage but often relies on codebooks incompatible with native FP4 computation. We introduce MXCode (MX-Native Codebook Quantization), a framework bridging ultra-low-bit VQ compression with MicroXcaling (MX)-native FP4 computation. MXCode proposes three strategies: PostScale, which quantizes learned codebooks to MXFP4; PreScale, which extracts MX scales before codebook learning; and PreScale+, which further compresses these scales using VQ. These strategies explore tradeoffs among quantization quality, scale overhead, and codebook granularity. All reconstruct MX-native W4A4 operands without materializing intermediate high-precision weights. We evaluate MXCode on Qwen3 (235B), DeepSeek-R1 (671B), and GLM-5.2 (753B) using the Microsoft MX Emulation Library. MXCode achieves approximately 2 bi

---

### [226] Zero-shot evaluation of open vision-language models as System 1 decision models on radiology tasks

**链接**: https://arxiv.org/abs/2611.01631
**作者**: Bradley J Erickson and Sara Salehi
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: We compared two multimodal System 1 decision models, Clef 27B and d1 3B, with a traditional LLM (Qwen 3.8-27B) on seven radiology tasks covering text, radiographs, CT and MRI. Methods: Three models were compared: Clef, Qwen3.8-27B and d1. Three tasks were interpretation of text and 4 were detection of finding in images. The tasks were: 1. finding presence of finding in CT-RATE chest CT reports; 2. Presence of finding in PadChest chest radiograph reports; 3. the same 18 findings on CT-RATE chest CT but 3D volumes; 4. MR safety status of devices from AccessGUDID device records; 5. line and tube position on RANZCR CLiP chest radiographs; 6. motion-artifact severity on MR-ART T1-weighted brain MRI and 7. sequence identification on BraTS 2021 brain MRI. The primary endpoint was AUROC. There was no fine-tuning of the models on the tasks. Results: All models completed all tests without a failed request. All retrieved findings from reports almost perfectly (AUROC >0.95). Clef ranked h

---

### [227] Query-efficient scan-and-search watermark localization

**链接**: https://arxiv.org/abs/2611.02030
**作者**: Liyuan Wang, Xinsong Ma, Ziye Ma
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, the detection of AI-generated content has been of particular importance in various fields of our society. For accountability purposes, many large language models (LLMs) have implicitly watermarked their outputs. Localizing such watermarks requires a piece of text to undergo an additional verification process. Existing localization methods typically rely on dense token-level scoring, making verification costly even when an LLM-generated watermark only sparsely appears. To tackle this problem, we design a new adaptive allocation strategy that first maintains broad document coverage and then progressively concentrates the detection budget on regions that exhibit stronger watermark evidence or are more likely to contain watermarked content. We then transform the statistical signals from the selected regions into e-values and employ the proposed token-weighted e-BH procedure to determine the localized watermark regions. The resulting framework is called BELL (Budgeted E-evidence L

---

### [228] Sweep Less, Steer More: Using Activation Steering Geometry for Reduced Hyperparameter Search

**链接**: https://arxiv.org/abs/2611.01496
**作者**: Nishkal Hundia, Swastik Agrawal, Navita Goyal, Sarah Wiegreffe
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representation steering methods like difference-in-means (DIM) offer a lightweight approach to controlling LLM behavior, but their effectiveness varies widely across concepts, datasets, and layers, making principled deployment costly without exhaustive hyperparameter sweeps. We build on the discriminability index $d'$, a compute-cheap geometric measure of how well contrastive training activations separate along the steering direction. Across five behaviors on 3 models, we demonstrate uses beyond its established role as a dataset-level steerability predictor. First, in the multiple-choice question answering (MCQA) setting, we show that $d'$ reliably identifies performant layers at which to steer, eliminating the need for a layer-wise sweep. Second, we extend this analysis to open-ended multi-token generation, and find that $d'$ remains successful for layer selection across different settings. Lastly, we test whether the position of a generated token's representation on the DIM line pred

---

### [229] Learning by Doing: Autonomously Compiling and Curating Agent Skills from Verified Traces

**链接**: https://arxiv.org/abs/2611.01386
**作者**: Daniel Chalef, Peter Evans, Pavlo Paliychuk, Mehul Patel, Preston Rasmussen, Jack Ryan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory systems for production LLM agents mostly store semantic memory (facts about users and domains) or episodic memory (earlier interactions). Research systems such as Trace2Skill, WikiSkill, and SkillRevise learn procedures from agent runs, package them as Skills, and evaluate them on benchmarks. We describe Zep Agent Skills, a production service that gives deployed agents this procedural memory. The service uses only verified attempts as evidence, cites the supporting events for each field of a Skill, and governs the admission and distribution of each Skill version. The service records each task attempt as a Trace with ordered events, an outcome, and a verification strength. A compiler with separate Reflector and Curator roles turns verified Traces into versioned Skills. Scans and admission gates control which candidates become active, and verified use outcomes change the search rank of each Skill. The Agent Skills format is an open standard that Anthropic originated and donated to

---

### [230] Grading the Unannotated: Insights from the WorkRB Skill Extraction Challenge at RecSys-HR 2026

**链接**: https://arxiv.org/abs/2611.03525
**作者**: Warre Veys, Luis Gasco, Jens-Joris Decorte
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skill extraction benchmarks score models against a few human-annotated positives and treat every other skill in the vocabulary as equally wrong. At the scale of ESCO (13,939 skills) this binary view can reward models that rank the annotated positive high for the wrong reason, and hides semantically nonsensical predictions. The WorkRB Challenge at RecSys-HR 2026 replaces it with graded relevance: every candidate skill in a model's ranking window carries a 0 to 4 grade, and the leaderboard scores nDCG@100 against these grades. Since ternary judgements proved too coarse for objective annotation, relevance is decomposed into a cascade of four binary questions (same domain, activity mentioned, right granularity, replacement of a gold positive) that a smaller LLM judge can answer reliably; the labels are validated with blind human and frontier-model re-annotation. This paper documents the annotation methodology, the construction of five benchmark datasets (four with vacancy sentences as quer

---

### [231] TAC-CoT: Tool-Empowered Implicit Chain-of-Thought via Interleaving Explicit Tokens

**链接**: https://arxiv.org/abs/2611.01926
**作者**: Juseon Do, Sangmin Bae, Jeesu Jung, Hwanjun Song
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agentic systems are increasingly combined with CoT reasoning to solve tasks that require accurate reasoning, external knowledge, and multi-step deliberation. Yet, explicit CoT incurs substantial generation overhead, while implicit CoT, which replaces textual rationales with compact continuous tokens, does not naturally support the explicit communication interface required for agentic tool-use. We propose TAC-CoT, a tool-empowered adaptive implicit CoT framework that replaces explicit reasoning traces with compact latent reasoning segments while retaining textual tokens only for tool calls, observations, and final answers. This interleaved design enables agentic tool-use without verbalizing every intermediate reasoning step. Experiments on agentic math and QA benchmarks show that TAC-CoT improves accuracy by up to 8.8 points while reducing model forward passes by up to 6.8x. Furthermore, analyses show that TAC-CoT improves tool-use quality in both single- and multi-tool settin

---

### [232] Constructing Budgeted KGW Evasion through Token-Event Evidence Replacement

**链接**: https://arxiv.org/abs/2611.00726
**作者**: Hongliang Liu
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> KGW watermarks bias sampling to accumulate keyed detection evidence. We construct budgeted evasion through token-event evidence replacement using ordinary phrase rewrites. Our construction jointly selects compositions of LLM-proposed alternatives from an independent model and measures global token-edit distance on complete outputs. At the largest attainable cost within the budget, exact coverage search maximizes removal of original scored token pairs. It uses a known tokenizer without the key, detector feedback or queries to the watermarked model. Exact accounting separates source evidence removed, evidence created and length effects, with initial strength setting the required reduction. Separate signed-event analysis found that mean suppression arose mainly from removing watermark-enriched source events. In controlled, occurrence-counted, one-token-context KGW tests on short passages, 39 of 82 qualified, initially detected sources yielded rewrites with terminal detector score Z < 4 th

---

### [233] Spotting the Artificial: Dialogic Humor Improvisation in Humans and LLMs

**链接**: https://arxiv.org/abs/2611.00492
**作者**: Lizeth Palacios Pati\~no, Ximena Gutierrez-Vasques, Daniel Rodriguez
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose a methodology for investigating the differences between natural and synthetic language in a challenging setting: humorous improvisational dialogue. Our experimental setting compares human-produced comedy improvisations with the dialogues generated by LLMs in a multi-agent environment that we designed. The analysis combines automated linguistic measures with manual annotation grounded in Systemic Functional Linguistics (SFL). The results show that, although LLMs can create coherent and creative scenes, they often fail to reproduce key characteristics of spontaneous spoken interaction. In addition, LLM-generated interactions display a strong tendency toward politeness and positive evaluations, contrasting with the broader range of attitudes found in human humorous improvisation. Our evidence highlights both the strengths and limitations of current LLMs in modeling dialogic humor and demonstrate the value of integrating linguistic theory with NLP methods for the analysis of mac

---

### [234] SpecPilot: Autonomous Algorithm Discovery and Systems Optimization for Speculative Decoding

**链接**: https://arxiv.org/abs/2611.02501
**作者**: Kunjun Li, Wenhao Chai, Yihao Liang, Yuezhou Hu, Shuyao Xu, Yi Pan 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates memory-bound LLM decoding with a lightweight drafter, and parallel drafters extend this speedup by drafting a whole block in one forward pass. However, it remains unclear whether their released systems (stock) attain the full speedup that parallel drafting permits. We identify three challenges. First, with one request, each step accepts few tokens but reads every target weight. Second, with batching, per-request verification work roughly halves the speedup over autoregressive (AR) decoding. Third, speculative decoding is deployment-specific, and no universal optimization fits every serving regime, drafter, target model and GPU. To address these challenges, we present SpecPilot, an autonomous agentic loop that discovers algorithms and systems optimizations for each deployment. In each round, a cost model locates the largest gaps between the current system and its ceiling. Parallel agents explore directions and integrate the successful ones. Token forcing

---

### [235] Inference First, Training Underneath: Layer-Granular LoRA Co-Serving with LayerLoom

**链接**: https://arxiv.org/abs/2611.00652
**作者**: Zongpu Zhang, Yishu Yin, Xuehai Qian
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving and fine-tuning a large language model on the same GPUs can turn the idle capacity between inference bursts into training progress, and low-rank adaptation (LoRA) makes this co-location cheap because both workloads read a single frozen copy of the base weights. The difficulty lies in the fine-tuning backward pass, which has no counterpart in inference. Current co-serving systems schedule backward work per serving iteration: each iteration carries a fixed backward budget, and requests that arrive in the meantime wait for it to finish, so fine-tuning dictates inference latency whenever load spikes. We observe that the backward pass of a LoRA microbatch decomposes into per-layer tasks over the same weights that the inference forward pass visits, which allows backward work to be scheduled at layer rather than iteration granularity. Building on this observation, LayerLoom attaches same-layer backward tasks to the inference forward pass and, at each layer, runs only as many of them a

---

### [236] State-Aware Virtual Patient Simulation for Training Psychiatrists in Challenging Clinical Scenarios

**链接**: https://arxiv.org/abs/2611.02067
**作者**: Harsh Mohta, C Chandrahas Reddy, Sunhith Reddy Bojja, Manik Inder Singh Sethi, Vinesh Gupta, Raghuram Bharadwaj Diddigi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Psychiatrists must be prepared to manage patients exhibiting challenging psychological states, including suicidal ideation, hallucinations, and other high-risk behaviors. However, opportunities to safely practice such interactions are limited. While recent conversational agents can simulate patients, existing approaches largely rely on large language models (LLMs) to determine patient responses, making it difficult to consistently maintain psychological state, adapt to the clinician's responses, and generate clinically plausible challenges that meaningfully test the clinician. We present a state-aware virtual patient simulation pipeline for training psychiatrists in challenging clinical scenarios. The proposed system maintains an evolving patient state throughout the interaction and orchestrates patient behavior rather than leaving response generation entirely to an LLM. At each interaction, a learning-based behavioral strategy selector determines the type and level of challenge approp

---

### [237] Reading Between the Chapters: A Graph-Free RAG Rebuilt With AI and Human Feedback

**链接**: https://arxiv.org/abs/2611.00752
**作者**: Dipto Sumit, Syeda Fabiayee Jahan, Farig Sadeque
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many questions about a book can only be answered by connecting passages chapters apart, such as a cough heard three times across a horse's life. We introduce CrossChapterQA, 1,853 such questions over 14 public-domain books. Each question lists the two to six chapters it needs (spanning half the book at the median) and the relation linking them, cites evidence from each, and has two independent reference answers graded blind. We use it to build LadderRAG, which indexes a book as passages, summaries and book-level cards for about $0.41 and answers a question for under a cent. Its first version failed mostly at retrieval. We redesigned it four times, steered by an LLM judge's verdicts and our analyses of failed answers: a design-level counterpart of RLAIF and RLHF in which feedback changes the architecture, not model weights. We also report the two redesigns that made answers worse. On the 191 questions its first version got wrong, the final version retrieves over twice as many required c

---

### [238] CISA: Retrofitting Dense Attention Models with Chunk-Indexed Sparse Attention

**链接**: https://arxiv.org/abs/2611.03200
**作者**: Mohammed Dabbah, Izhak Golan, Oren Tropp, Daniel Afrimi, Vladimir Anisimov, Tomer Asida 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context LLM inference is costly because attention repeatedly reads a growing key-value (KV) history. We introduce Chunk-Indexed Sparse Attention (CISA), which retrofits pretrained dense attention models without gradient updates. CISA selects fixed-size KV chunks using compact summaries of existing keys, avoiding token-level indexing and a separate full-length index cache. It uses one indexing query per KV group and shares selected chunks across queries in that group. During prefill, QShare reuses selections across adjacent queries to reduce indexing cost and improve KV reuse and GPU utilization. We evaluate CISA on NVIDIA Nemotron 3 Nano and Ultra, and Inkling-Small. In one-layer BF16 benchmarks at batch size 32 using Ultra's per-device attention dimensions, core attention is 11.7x faster for prefill queries near the end of a 1M-token prompt and 13.0x faster during decode. Including chunk scoring, selection, and all other measured GPU work, speedups are 8.6x and 3.0x. On Ultra NVF

---

### [239] Tug of Watts: A study on the Energy - Accuracy Trade-off of Large Language Models on Medical Question Answering Tasks

**链接**: https://arxiv.org/abs/2611.02889
**作者**: Viju Sudhi, Giulio Billi, Andreea Scrob, Regina Stodden, Philipp Cimiano
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used in medical question answering (QA) systems. While recent works aim at incrementally improving the downstream task accuracy, an empirical estimation of the models' energy consumption and the associated carbon footprints is often overlooked. In this study, we demonstrate how practitioners can estimate energy consumption and arrive at reliable emission estimates for medical QA tasks available in the OpenMedical-LLM leaderboard by investigating 13 LLMs from 3 model families ranging from 270M to 14B parameters. We discuss how one can critically interpret energy versus accuracy trade-offs for a set of models for a given task. With this work, we underline that reporting disjoint energy and accuracy metrics alone does not suffice for careful trade-off assessments, but it also demands systematic construction and interpretation of joint trade-off metrics. We envisage such studies aiding practitioners in adopting better and more efficient models 

---

### [240] SQLoom: Set-Contrastive Learning of Syntactic, Semantic, and Logical Dependencies for Text-to-SQL

**链接**: https://arxiv.org/abs/2611.03298
**作者**: Hao Fu, Degang Sun, Wan Wei, Jinxia Wei, Chun Long, Peng Gao
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-SQL translates natural language questions into SQL queries, enabling database access without writing SQL. Fine-tuning open-weight large language models (LLMs) is cost-effective, but existing methods treat SQL as ordinary text and optimize token-level likelihood without explicitly modeling its syntactic, semantic, and logical requirements. Thus, a single incorrect alias or comparison operator can invalidate a query while contributing little to training loss. We propose SQLoom, a constraint-aware fine-tuning framework with supervision at three levels: syntactic validity under SQL grammar and database schema, semantic alignment between query decisions and the question, and logical consistency across dependent clause decisions. SQLoom extends supervised fine-tuning with a unified set-contrastive objective favoring sets of correct outputs over minimally different incorrect ones at each level. LLM agents propose this supervision, which a SQL parser and execution on counterexample dat

---

### [241] PatchScout: Thematic Web Data Collection via Information Foraging

**链接**: https://arxiv.org/abs/2611.00169
**作者**: Michael West and Eduard Dragut
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers often need web corpora that are not answers to a single query, but reusable collections of documents spanning many decentralized sources. We refer to this problem as thematic web data collection: assembling semantically relevant documents that share a common theme but are scattered across heterogeneous and structurally disconnected regions of the web. Existing approaches, including traversal-based methods and LLM-driven web agents, are limited by local exploration or short-horizon stopping, preventing comprehensive collection. We formulate this task as a long-horizon information foraging problem over query-induced semantic patches, where the central challenge is deciding when to continue local exploitation and when to switch to new regions. We propose PatchScout, a multi-agent framework that instantiates a class of patch-switching policies to balance local exploitation and adaptive patch switching under a fixed budget. Experiments on four live-web topics show that PatchScou

---

### [242] VIAS: Value-Isolating Activation Steering for Multi-Value Alignment and Compliance for Organisations

**链接**: https://arxiv.org/abs/2611.03518
**作者**: Avni Mittal, Avinash Anand, Dikshant Kukreja, Erik Cambria, Rajiv Ratn Shah, Sandipan Dandapat
**来源**: cs.CL cs.AI cs.LG cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organisations increasingly deploy large language model agents that must follow organisational values. We check whether activation steering, which adds vectors to a model's internal activations during generation without changing its weights, can improve compliance beyond prompting alone. Since most scenarios involve several values at once, we focus on multi-value steering. A simple way to build these vectors is to contrast responses that follow all values relevant to a scenario with responses that violate them. However, this gives nearly identical vectors for different values: they capture a general compliance signal rather than individual values, which limits their use when combining several values. We propose Value-Isolating Activation Steering (VIAS), which contrasts responses to the same scenario under two prompts, one listing all relevant values and one omitting a single target value. We keep a pair only if the target value changes from compliant to non-compliant and both responses

---

### [243] Who Schedules Agent Memory? A Sidecar Approach to Long-Horizon Tasks

**链接**: https://arxiv.org/abs/2611.00779
**作者**: Qijia Zhuang (1), Rui Liu (2), Yuxiang Ren (1) ((1) Nanjing University, (2) Northeastern University)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model agents increasingly undertake complex, long-horizon tasks, memory has become an important component for supporting sustained decision-making and action. Existing methods primarily focus on memory storage, updating, and retrieval, but often overlook how memory scheduling affects task execution: the main agent must identify memory needs, initiate retrieval, and wait for results while advancing the task, increasing both scheduling burden and execution time. To address this problem, we propose MemSidecar, which decouples memory scheduling from task execution through two independently selectable modes. Hooks directly delivers bound memory to the main agent when execution events match predefined conditions. Foresight uses an independent agent to predict potential queries, retrieve results in parallel, and store them in a cache, delivering matching and valid results when actual requests arrive. Hooks and Foresight achieve scores of 41.23% and 44.34% on MCP-Persona, res

---

### [244] PlagiaCorpus: A Bilingual, Adversarial, and Cross-Lingual Dataset for Forensic Plagiarism Detection

**链接**: https://arxiv.org/abs/2611.02940
**作者**: Adel Ammar, Serry Sibaee, Wadii Boulila
**来源**: cs.CL cs.AI cs.CY cs.DL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> PlagiaCorpus is a bilingual Arabic-English dataset for benchmarking plagiarism and text-reuse detection, including reuse produced by large language models (LLMs) and reuse across languages. It contains 198,643 text records: a source corpus of 34,885 passages drawn from English and Arabic Wikipedia and two openly licensed book collections, and 163,758 queries (147,381 for training and 16,377 for testing). The queries cover five reuse classes of increasing difficulty, namely verbatim copying, character-level obfuscation, same-language paraphrasing by two different LLMs, and English--Arabic translation with structural paraphrasing, together with a Safe class of non-reused passages. Every positive query is linked to its source passage, and the train/test split is grouped by source passage so that no passage contributes queries to both splits. The release was curated through language identification, removal of LLM generation artefacts, and exact and cross-lingual de-duplication. Technical v

---

### [245] Is Your Long-Horizon Benchmark Really Deep? Measuring and Synthesizing Depth in Terminal Tasks

**链接**: https://arxiv.org/abs/2611.01927
**作者**: Yu Jiang, Yue Huang, Hang Hua, Yuyang Wu, Zixuan Weng, Olexandr Isayev 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon terminal tasks are used to evaluate and train agents. Human-curated datasets are scarce, so many synthesis methods have emerged. They usually measure the length of a task by the turns a model needs to pass it, and its difficulty by labels the LLM sets during generation. We find, however, that the turn count largely reflects the habits of the model, not only the demands of the task, and that the labels barely track how often models pass. We describe a terminal task by its work, the number of operations it requires, and its depth, the number of turns that must happen in sequence because the commands of each turn can only be chosen after reading the output of the previous one. Estimating depth as the smallest turn cap, stated to the agent, under which the task passes, we audit 734 tasks from six existing datasets. Synthesis has mostly added work, not depth: 94% of the solved synthetic tasks pass within three turns, yet depth, unlike the turn count, predicts difficulty beyond 

---

### [246] EarlySelectKV: Anticipatory KV Selection via Cross-Layer Query Proxies

**链接**: https://arxiv.org/abs/2611.01715
**作者**: Yuhao Liu, Yuehao Li, Linghe Zhang, Gaobin Huang, Junran Li, Hongchang Wang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Query-conditioned sparse KV selection reduces long-context inference cost by attending to a subset of historical KV entries at each decoding step. Existing selectors must wait for the target-layer query before scoring candidates and generating indices, placing routing on the immediate pre-attention path. We introduce EarlySelectKV, a training-free transformation that uses proxy queries from earlier hidden states to precompute selected KV indices while retaining the real target-layer query for final attention. Tests with RocketKV, Quest, and Loki show no consistent pattern of quality degradation across the evaluated settings. In the primary RocketKV evaluation, ES-RocketKV differs by +0.018 points on LongBench, approximately -0.01 points on RULER, and +0.25 percentage points on representative NIAH/Passkey settings. In a TensorRT-LLM deployment with CPU-offloaded routing, ES-RocketKV improves end-to-end output throughput by up to 12.4% and reduces GPU-resident memory by 11.1% of the comb

---

### [247] From Lookups to Lessons: Turning Retrieved Knowledge into Parametric Memory

**链接**: https://arxiv.org/abs/2611.00450
**作者**: Changjiang Han, Bowei He, Ye Yuan, Weixu Zhang, Haolun Wu, Xue Liu 等 (7 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) helps large language models (LLMs) answer factual questions beyond their training data, but it adds storage and inference costs. Distilling previously retrieved information into parametric memories enables reuse without online retrieval. However, training the memory to mimic a retriever rewards accurate independent predictions, which do not necessarily improve the final output quality when combined with the LLM's existing predictions. To address this, we introduce ResMem, in which the LLM reads retrieved text offline to generate teacher targets. This design avoids storing massive token representations, unlike existing parametric memory approaches such as MLP Memory, which relies on k-nearest neighbor (kNN) datastores. Furthermore, by using the LLM as an offline teacher that reads privileged retrieved evidence alongside the input, we train a parametric memory to learn an additive logit residual. This residual aligns the predictions of a student shari

---

### [248] Unlocking Criminal Court Decisions: Flexible Information Extraction for Empirical Legal Research

**链接**: https://arxiv.org/abs/2611.03051
**作者**: Tom\'a\v{s} Knap, Ivana Kvapil\'ikov\'a, Jan \v{C}ern\'y, Kl\'ara Bendov\'a, Jarom\'ir \v{S}avelka, Vojt\v{e}ch Pour 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Criminal verdicts contain descriptions of criminal behavior that can support quantitative legal research, but structuring them requires attributes and extraction rules that cannot always be fully specified in advance. We present an LLM-based pipeline that builds a structured dataset through attribute exploration, text span extraction, and value normalization, guided by annotation instructions that legal experts can refine. We evaluate it on two traffic offenses: driving under the influence (DUI) and driving despite a ban (DDB). For DUI, revising the instructions was associated with higher extraction accuracy (from 52% to 70% of correctly extracted values) and higher agreement between human annotators. Repeated runs of the same model agreed with each other more than with the gold annotations, showing that consistent output is not necessarily correct, while disagreement between annotators and between models helped reveal unclear instructions. For DDB, where the instructions defined fixed

---

### [249] CheXPoT: Post-Hoc Visual Verification and Correction of VLM-Generated Radiology Reports

**链接**: https://arxiv.org/abs/2611.00785
**作者**: Joey Guo, Rayan Ansari, Alaa Youssef
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) have shown promise for chest radiograph report generation, but adoption remains limited because of hallucinated findings that are not grounded in the image. Correcting these hallucinations and improving overall report quality remains a significant challenge. Prior work has addressed this problem by refining models with reinforcement learning, preference optimization, or chain-of-thought supervision, often at substantial compute cost. To address this gap, we introduce CheXPoT, a program-of-thought (PoT) framework that verifies each generated finding against image features and removes those it cannot ground. CheXPoT decomposes generated reports into predicates with RadGraph and an LLM, grounds these predicates against a DenseNet-121 and Grad-CAM visual evidence table, executes PoT verification code, and rewrites reports after removing unsupported predicates. On a 4,145-image held-out split, CheXPoT yields statistically significant precision gains on 8 of 14 

---

### [250] MedPsy: State-of-the-Art Small Medical Language Models for Efficient Edge Deployment

**链接**: https://arxiv.org/abs/2611.02011
**作者**: Davide Vitabile, Alexandro Buffa, Akshay Nambiar, Amril Nazir
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical language models promise expert clinical support, but the strongest open-source LLMs remain too large for private edge-device deployment, while compact medical models still trail substantially on knowledge-intensive and real-world healthcare tasks. Reasoning models that fit edge memory budgets can produce long reasoning traces, increasing sequential decoding, end-to-end latency, energy consumption, and KV-cache memory pressure. We present MedPsy, a family of text-only 1.7B and 4B medical language models designed for edge deployment, targeting this accuracy-generation-efficiency trade-off. Our recipe combines a synthetic medical data pipeline over biology, medicine, and health seeds with chain-of-thought targets from a 235B medical-focused LLM teacher; a four-stage post-training curriculum comprising two SFT stages followed by two RL stages with hard-sample mining; and an edge deployment evaluation spanning multiple GGUF quantization variants and real-device inference on laptop a

---

### [251] LLMs Depend on Specialist Tools for Out-of-Distribution Generalization in MS/MS Structural Elucidation

**链接**: https://arxiv.org/abs/2611.03308
**作者**: Gabriel Asher and Cailum M. K. Stienstra and Tomo Oga and Devesh Shah Antonio H. de O. Fonseca and Niall O'Connor and Michael Widrich
**来源**: cs.LG cs.AI cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A frontier language model was recently reported to solve 1D NMR structural elucidation without tools. We ask whether this capability transfers to tandem mass spectrometry (MS/MS) in the de novo setting, where the model must propose a structure directly from the spectrum without a candidate list or reference library. To separate reasoning from recall, we build a 100-analyte benchmark from MassSpecGym, split by each analyte's textual footprint into in-distribution (well documented in literature) and out-of-distribution (essentially undocumented) arms. We hold the model, harness, and output format fixed and vary only the LLM's access to domain-specific tools. Without tools, a frontier LLM reaches 52% Top-1 accuracy in-distribution but only 2% out-of-distribution. Only access to de novo structure generators improves out-of-distribution accuracy, raising it to as much as 38% Top-1, and the resulting agent outperforms the standalone de novo models both in and out of distribution. These resul

---

### [252] Multi-Agent Collusion and the J-Space

**链接**: https://arxiv.org/abs/2611.02153
**作者**: Marco Molinari, Gabriele Bettineschi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly deployed in Multi-Agent Systems (MAS), and they introduce the risk of coordination among agents that might escape human oversight. The J-space has been used to uncover deception in single LLMs, but its use for uncovering and steering collusion between agents remains unexplored. We show, with interpretability experiments on DeepSeek-V4-Flash (284B) on the NARCBench collusion benchmark, that colluding agents' J-space holds the collusion itself: before replying, 86% of colluders represent misrepresentation, concealment or remorse. In a steganographic card-counting task, the receiver's J-space holds a hidden count, and causal interventions alter its count. We also introduce the Jacobian Pair Contrast (J-PACT), an unsupervised method for detecting collusion between agents. We evaluate J-PACT on four open-weight models: GPT-OSS-20B, Llama-3.3-70B-IT, Qwen3-32B, and DeepSeek-V4-Flash (284B). J-PACT retains 85% of the above-chance AUROC of supervised NARCBench probe

---

### [253] TIGER: Learning from Researcher Taste to Generate Tailored Research Ideas

**链接**: https://arxiv.org/abs/2611.02234
**作者**: Shane Gu, Yufeng Lin, Dixi Yao, Xuchen Gong, Chenhao Tan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In pairwise comparisons where each judge chooses between an idea generated by its corresponding TIGER-8B policy and one generated by GPT-4.1, the three LLM researchers select the TIGER-8B idea in 56.6%-68.4% of 76 comparisons per researcher. PhD1 and PhD2 select the TIGER-8B idea in 19 of 30 pairs (63.3%) and 17 of 30 pairs (56.7%), respectively. All six directed cross-policy comparisons likewise favor the judge's matched TIGER-8B policy over an off-target policy, supporting the use of individual preference feedback for tailored research ideation.

---

### [254] SpBench: An Agent-Native Framework for Cross-Engine Lakehouse Benchmarking

**链接**: https://arxiv.org/abs/2611.00449
**作者**: Lyndon Shi, Nic Crouch, Yi Hu, Zihao Ye, Choden Konigsmark, Eric Vandenberg 等 (10 人)
**来源**: cs.DB cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> SpBench is an agent-native framework for cross-engine lakehouse benchmarking, in production use for benchmarking Snowpark, Snowpark Connect for Apache Spark, and other execution environments across standardized suites -- such as TPCx-BB and TPC-DI -- and custom benchmarks distilled from production workload patterns. It runs continuously across a broad portfolio of workloads, guiding the performance roadmap and detecting regressions for production-scale data engines. Benchmarking has historically been an expensive investment requiring continuous cross-functional collaboration and domain expertise, making it difficult to obtain actionable performance insights. SpBench provides (i) a typed, code-generated benchmark substrate that compiles platform-agnostic benchmark definitions into fair, comparable platform-specific implementations; (ii) a structured-telemetry contract recording every run as queryable fact and dimension data, letting LLM agents query results deterministically; and (iii) 

---

### [255] Circuit Oracle: Automating Attribution Graph Analysis via Natural-Language Queries

**链接**: https://arxiv.org/abs/2611.00420
**作者**: Shariar Kabir, Hong Kiat Tan, Swastik Agrawal, Sai V R Chereddy, Sriram Balasubramanian
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attribution graphs, an emerging tool in mechanistic interpretability, use transcoders to decompose language model computations into sparse interpretable features connected by causal edges. However, turning a graph into a safety-relevant insight requires hours of manual analysis by experts. We introduce Circuit Oracle, an off-the-shelf LLM equipped with a multi-agent harness and task-specific authored skills, which answers natural-language questions about a target model by reading the attribution graph through tool calls. We evaluate it on three safety-relevant proxy tasks: detecting spurious features in probe circuits, eliciting hidden knowledge from taboo-finetuned models, and suppression jailbreaking via feature-level interventions. Beyond task scores, the oracle produces pruned subgraphs and context-specific feature explanations that we assess qualitatively. Results are mixed. On spurious-feature detection, Circuit Oracle reaches 78.2 $\pm$ 2.4% accuracy, outperforming single-layer 

---

### [256] Pulse: Long-Horizon Tasks Need Streaming Personalization

**链接**: https://arxiv.org/abs/2611.00988
**作者**: Qijia Zhuang (1), Jialiang Liang (2), Yuxiang Ren (1) ((1) Nanjing University, (2) Xinjiang University)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly undertake complex, long-horizon tasks that benefit from sustained personalized support through long-term memory. Existing memory-augmented methods retrieve and use memory primarily from the initial request, with limited awareness of ongoing execution and emerging personalization needs. Agents may therefore overlook user preferences and project constraints during multistep tasks. We propose Pulse, a streaming personalization method for long-horizon tasks. An independent, lightweight memory agent continuously monitors execution, identifies emerging personalization needs and potential preference conflicts, and uses user and project memories to provide targeted interventions at appropriate stages. Reinforcement learning optimizes when and how the memory agent intervenes, improving the timeliness and accuracy of personalized support. Pulse scores 71.9% on $\pi$-Bench and 46.4% on MCP-Persona, achieving the highest overall scores among the compared me

---

### [257] DramaVQA: Probing Detailed Understanding of Ultra-Long TV Dramas

**链接**: https://arxiv.org/abs/2611.00769
**作者**: Xinyue Huo, Pengfei Chen, Jiannan Ge, Kaiwen Duan, Jiacheng Shao, Yunning Cao 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite recent progress in long-form video understanding, current benchmarks mostly focus on short clips or hour-scale videos. This leaves a major gap in evaluating ultra-long video understanding, where videos often last tens of hours. To bridge this gap, we introduce DramaVQA, a large-scale benchmark built upon long-form TV dramas. Containing approximately 20K question-answering (QA) pairs, the scale of DramaVQA exceeds previous long-video datasets, such as Video-MME and LVBench, by an order of magnitude. Our benchmark has two main features that make it stand out from existing datasets. First, we establish a scalable, LLM-assisted annotation pipeline that uses multimodal large language models (MLLMs) to generate complex questions, followed by strict human checking to ensure high data quality. Second, DramaVQA introduces a multi-level time structure; queries are designed across different video lengths, with the hardest questions requiring overall understanding across the entire drama. 

---

### [258] Beyond Binary Detection: Type-Aware Hallucination Analysis and Hierarchical Detection in Financial Question Answering

**链接**: https://arxiv.org/abs/2611.02258
**作者**: Xiongyu Chen, Sizhen Zhu, Zhuoer Wang
**来源**: cs.AI q-fin.CP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used to answer questions over financial filings, where an unfaithful answer can mislead investment, compliance, or client decisions. Hallucination detectors are a common safeguard, but they are usually evaluated with a single binary score that reveals neither which kinds of errors analysesed nor why. This paper studies hallucination detection on PHANTOM, a long-context benchmark built from SEC filings, at the level of hallucination type. We first analyze 15,443 paired hallucinated and faithful answers without any detector and find that hallucinated answers are more than twice as long as faithful ones, and that lexical grounding separates the two classes only because faithful answers are bimodal. We then generate hallucinations in nine financially motivated categories, confirm each with a separate verification pass, and diagnose an LLM-based detector on 4,086 usable examples. Generation success varies from 66.3% to 100% across categories. The detec

---

### [259] PRIME: Predictive Routing of Interventions by Modeling Effects for Scientific Ideation

**链接**: https://arxiv.org/abs/2611.03055
**作者**: Fengxian Ji, Xie Yu, Zhexuan Cui, Yuke Li, Zirui Song, Fan Zhang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feedback-driven iteration is widely used to improve LLM-generated scientific ideas, but existing systems either leave revision decisions implicit in generation, align revisions with feedback-localized weaknesses, or restrict action selection to system-specific operations. This is problematic because problems, hypotheses, and solutions are interdependent: the location where a weakness manifests does not itself determine the revision scope that will produce a better successor. We term this phenomenon diagnosis-intervention mismatch. We introduce Predictive Routing of Interventions by Modeling Effects (PRIME), a plug-and-play feedback-to-revision decision layer for existing scientific ideators. PRIME operates in three stages: (1) Structural Attribution interprets feedback over the problem-hypothesis-solution structure without fixing a revision target; (2) Counterfactual Routing constructs alternative scope-conditioned interventions and compares their projected successor utility and risks 

---

### [260] IdeaTaste: Do LLMs Share the Research Taste of Human Researchers?

**链接**: https://arxiv.org/abs/2611.03424
**作者**: Shanshan Zhong, Chen Xu, Jingjie Ning, Zhengzhong Liu, Aviral Kumar, Chenyan Xiong
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research taste, the judgment of what to read, which problems to pursue, and which methods to try, increasingly shapes the work of AI scientists, yet it remains far less understood than their ability to execute research. We introduce IdeaTaste, a benchmark that scores an LLM by how closely the research proposals it writes from a literature snapshot frozen at 2025 match the work the same communities published in 2026. Our experiments span six contemporary language models and four research areas from established to emerging fields, covering more than 90{,}000 proposals in total. LLM agents fall well short of human communities in both the literature they cite and the ideas they state, reaching about 26\% of the human level on citation matching and only 18\% on idea matching. Their populations can cite as diversely as a community and take up its tasks and methods, yet rarely arrive at the concrete approaches and research plans it pursues. Neither richer field context nor larger populations 

---

### [261] SearchInject: Retrieval Exposure Control for Indirect Prompt Injection in Language-Model Search

**链接**: https://arxiv.org/abs/2611.02643
**作者**: Kainan Zhou, Gangzhen Qian, Janet Sung, Zhi Jing, Rong Bao, Qianru Lao
**来源**: cs.AI cs.CY cs.IR cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An indirect prompt injection can affect a search-augmented large language model only after its carrier page reaches model context. SearchInject controls this admission decision with a joint score combining retrieval relevance, search-abuse cues, instruction likelihood, and two relevance interactions. A quarantine threshold is selected under an empirical 0.5% clean-candidate false-quarantine constraint on a calibration split. Evaluation uses 300 held-out SciFact queries and held-out payload categories within four construction families already represented during development. Across 1,200 query-family outcomes per retriever, top-10 target exposure falls from 0.9408 to 0.1583 for BM25, from 0.9158 to 0.1508 for a normalized hybrid, and from 0.8450 to 0.1375 for latent semantic analysis. These are relative reductions of 83.2-83.7%; the largest absolute change in clean normalized discounted cumulative gain at rank 10 is 0.0018. The frozen threshold yields clean test false-quarantine rates of

---

### [262] Evolving Explanations: Complexity-Adaptive Refinement of Faithful Explanations for Symbolic Regression

**链接**: https://arxiv.org/abs/2611.02634
**作者**: Elisabeth Mayrhuber, Ting Hu, Stephan Winkler
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language explanations generated by large language models (LLMs) for machine learning models often seem fluent but are not necessarily faithful to the underlying model. We formalize this mismatch as a faithfulness gap and propose a complexity-adaptive refinement framework for symbolic regression that iteratively generates and validates explanations until numerical agreement with the target expression is achieved. The approach follows a two-stage pipeline: an explainer LLM produces textual descriptions at increasing levels of detail, while an independent validator LLM extracts a symbolic expression that is compared against the original model. This process is framed as a discrete search over explanation space, where complexity is minimized subject to a faithfulness constraint. We evaluate the method on real-world and synthetic datasets, with a total of 250 runs across varying model complexities. The explanation refinement loop achieves an overall pass rate of 84.0%, with most expl

---

### [263] \textsc{ChatDify}: Automating End-to-End Dify Workflow Synthesis from Natural Language via Multi-Agent Collaboration

**链接**: https://arxiv.org/abs/2611.01563
**作者**: Tao Fan, Guoqiang Ma
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The proliferation of Large Language Models has catalyzed powerful application development platforms like Dify, which enable users to build sophisticated LLM-powered workflows through modular node orchestration. However, manually configuring these workflows requires deep platform expertise and remains time-consuming and error-prone, creating a significant barrier for non-expert users. To address this challenge, we propose \textsc{ChatDify}, a novel multi-agent framework that automates end-to-end Dify workflow synthesis from natural language descriptions. \textsc{ChatDify} employs an Actor-Critic architecture comprising three specialized agents: the \textit{Planner Agent} that decomposes user requests into structured execution plans, the \textit{Executor Agent} that performs context-aware parameter synthesis and schema-augmented DSL compilation, and the \textit{Reviewer Agent} that ensures reliability through hybrid verification with closed-loop refinement. We evaluate \textsc{ChatDify} 

---

### [264] RecGroupMemory: Feedback-Aware Cohort Memory for E-Commerce Recommendation

**链接**: https://arxiv.org/abs/2611.02453
**作者**: Wendong Zhang, Weipeng Huang, Zhixin Ma, Bin Zhang, Dimin Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cohort memory can support LLM-based recommendation planning through group-level user profiles and advice. As outcome feedback becomes available, this guidance may need to be updated while preserving the underlying observations. We present RecGroupMemory, a workflow that provides this memory to an orchestration LLM and separates memory construction from feedback-based revision. It uses feedback from the previous day to revise decision guidance, while validation checks keep selected source values unchanged. Online comparisons were conducted among Taobao users with low purchasing power selected by the business team. Relative to a no-memory baseline, memory without feedback and memory with feedback showed increases of 1.58% and 1.78%, respectively, in the number of guided transaction users.

---

### [265] Phase-wise MLLM Tuning for Multi-framework WebUI Code Generation

**链接**: https://arxiv.org/abs/2611.01692
**作者**: Haoran Ma, Linxiao Li, Chenyue Wang, Haochen Sui, Jiechao Gao
**来源**: cs.SE cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) achieve strong performance in translating WebUI screenshots into HTML/CSS. However, when they faced multiple frameworks (React/Vue/Angular), they often suffer from negative transfer that leads to compilation failures. These failures commonly stem from mixing framework specific syntax and violating framework constraints. This paper studies supervised fine-tuning for multi-framework WebUI code generation and proposes a phase-wise MLLM tuning method driven by compatibility and heterogeneity signals across frameworks. We first apply a normalization mapping that preserves each framework's native syntax while suppressing noise from variable naming and literal content. We then estimate cross framework heterogeneity and compatibility offline, and automatically derive training groups and their ordering by maximizing a phased objective. Finally, we perform phase-wise adapter tuning to reduce cross framework interference. Experiments on multiple benchmarks

---

### [266] RE-SciVQA: Improving Scientific VQA With Context-Relevant Retrieval and Lightweight MLLM Adaptation

**链接**: https://arxiv.org/abs/2611.00242
**作者**: Sheikh Tahmim Mehdi, Muminul Islam Jami
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A deep understanding of scientific literature often relies on interpreting figures that contain key information beyond the main text. Leveraging Large Language Models (LLMs) to extract insights from these figures can significantly accelerate knowledge discovery. Existing works on Scientific Visual Question Answering rely on resource-intensive training pipelines that are often inaccessible and require large computational resources. Instead of designing complex architectures, we propose RE- SciVQA, which focuses on improving the quality of retrieved context and fine-tuning small LLMs with parameter-efficient LoRA training. Using a simple query expansion step, relevant section headers are appended to the original question to improve the retrieval coverage. In addition, a simple adjustment of similarity scores is applied using figure references and caption alignment. On the SciVQA benchmark, RE-SciVQA achieves a ROUGE-1 F1 score of 73.9%, outperforming chart-focused models such as UniChart

---

### [267] Learning to Group and Order: Cross-Instance Self-Supervised RL for Vision-Centric MLLMs

**链接**: https://arxiv.org/abs/2611.00892
**作者**: Songming Yang, Hong-Tao Yu, Xiu-Shen Wei
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) post-training has become an important paradigm for improving multimodal large language models (MLLMs), especially with automatically verifiable rewards. Self-supervised visual pretext tasks provide such rewards without human annotations. However, existing methods mainly exploit within-instance structure, offering limited supervision for cross-instance discrimination and fine-grained comparison. We introduce Group-and-Order Self-Supervised Reinforcement Learning (GO-SSL), a cross-instance jigsaw framework for vision-centric MLLM post-training. Given two visual instances, GO-SSL mixes their local elements and trains the model to group them by instance of origin while recovering the order within each group, coupling instance-level comparison with spatial, temporal, or geometric structure recovery. This paired formulation turns the same unlabeled data into richer verifiable supervision through diverse pairings, shuffles, and a random-to-hard curriculum. We insta

---

### [268] Beyond Multimodal Emotion Conflict: Temporal Context-Aware Hidden Emotion Detection with Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2611.01943
**作者**: Yonghao Wang and Jiaxin Zhou
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal emotion recognition commonly combines textual, acoustic, and visual signals to infer affective states. Recent work has begun to study conflicts among modalities, but a conflict does not necessarily indicate that a person is concealing an emotion. It may also result from mixed emotions, individual expressive styles, or contextual factors. This proposal aims to distinguish ordinary emotional inconsistency from emotion concealment and to infer the underlying emotion when supported by evidence. We plan to construct a multimodal benchmark with explicit annotations of expressed emotion, internal emotion, and concealment conditions, and to develop an MLLM-based framework that integrates fine-grained facial Action Units (AUs), cross-modal features, and temporal context.

---

### [269] PhotoGuider: Composition-Aware Cropping and 360$^{\circ}$ View Framing with Explainable Photographic Assessments

**链接**: https://arxiv.org/abs/2611.02897
**作者**: Yuan-Kang Lee, Kuan-Lin Chen, Chia-Che Chang, Yu-Lun Liu
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Traditional image cropping assumes the photograph already contains the composition worth keeping, and asks only where to crop. A full 360$^{\circ}$ scene offers no such guarantee: the viewing direction in a scene has to be discovered before anything can be framed. We present PhotoGuider, a measure-then-frame method that answers both questions with compact learned scorers over one shared set of composition-aware features. The designed features are extracted using foundation and task-specific vision models and structured into four photographic tokens: Subject, Composition, Aesthetics, and Integrity. Our MLLM explainer is fine-tuned to generate composition-related explanations conditioned on images and measured token assessments. To our knowledge, PhotoGuider is the first method to combine explicit composition-based direction selection in 360$^{\circ}$ panoramas with refined framing, camera-parameter output for native re-rendering, and measurement-conditioned explanations. On two standard

---

### [270] Do Personal Adapters Carry Over Across Sessions? Separating Personal From Population Gains When Calibrating EEG Foundation Models for Motor Imagery

**链接**: https://arxiv.org/abs/2609.34801
**作者**: Xilin Tao, Kani Chen
**来源**: cs.LG eess.SP q-bio.NC
**匹配关键词**: EEG, Foundation Models, Motor Imagery
**相关性评分**: 11.0
**数据来源**: arXiv CS Mailing

---

### [271] LaBraM at Scale: Scaling Data and Models for EEG Pretraining

**链接**: https://arxiv.org/abs/2611.03165
**作者**: Jun-Yu Pan, Ruicheng Yin, Bao-Liang Lu, Dongsheng Li, Wei-Long Zheng, Yansen Wang
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LaBraM, an early EEG foundation model, demonstrated that large-scale EEG pretraining can yield strong representations for diverse downstream tasks. Building on this foundation, we expand pretraining data and model capacity while retaining its core encoder and objective. We train ten encoders with 5.8 million to 1.97 billion parameters on three EEG collections spanning 25,067 to 79,910 hours, adapting signal preparation and training to heterogeneous recordings. Across 23 tasks, Atom-L* reaches 59.05% mean balanced accuracy at its best evaluated full fine-tuning (Full-FT) checkpoint, 3.61 percentage points above the strongest baseline EEG foundation model. Quark-G leads linear probing (LP) at 54.33%, a 1.24-point margin. Both also lead average task rank. At the last evaluated checkpoints, larger encoders improve Full-FT more consistently than LP, and stronger LP does not guarantee stronger Full-FT. Preserving patch structure improves LP over average pooling. Data-fraction experiments sug

---

### [272] Where Does EEG Help Wearable Freezing of Gait Detection?

**链接**: https://arxiv.org/abs/2611.00497
**作者**: Chuntian Chi, Lifang He, Huajie Shao, Gang Zhou
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Freezing of gait (FoG) detectors built on inertial measurement units (IMUs) are accurate while the legs move, but they become unreliable when the legs are nearly still, which is exactly when akinetic freezing, voluntary stopping, and standing must be told apart. Electroencephalography (EEG) captures motor-planning activity that leg sensors cannot, but EEG is impractical for daily use. We ask where EEG helps: as an input at inference time, or only during pretraining, so that the deployed detector still needs only IMUs. We assemble a pretraining corpus of synchronized EEG and IMU recordings (5 datasets, 184 people, 94 hours) and compare six settings that differ only in the modalities used for pretraining and as model input, each with tuned hyperparameters and five independent pretraining runs. On the BXHC FoG dataset (leave-one-patient-out, 10 patients with FoG), adding EEG as input raises FoG F1 from 0.663 to 0.740 (9 of 10 patients improve), and the gain in ranking performance is confi

---

### [273] Omni-iEEG Planner: an open-source Python platform integrating multimodal neuroimaging and intracranial EEG data for epilepsy surgery research

**链接**: https://arxiv.org/abs/2611.00018
**作者**: Yuta Tanoue, Masaki Izumi, Yipeng Zhang, Chenda Duan, Tonmoy Monsoor, Christopher A. Chan 等 (10 人)
**来源**: physics.med-ph cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal intracranial EEG (iEEG) research for epilepsy surgery combines anatomical and functional imaging, implanted electrode locations, interictal biomarkers, and functional mapping--outputs produced by different applications and reconciled by hand before they can be viewed on the same anatomy. Omni-iEEG Planner is an open-source Python platform that brings these inputs into one patient coordinate frame for research data analysis. The workflow starts from the preoperative T1-weighted MRI, from which FreeSurfer provides the cortical surface and anatomical labels; CT, PET and diffusion MRI are then co-registered to that reference, electrode contacts are detected automatically on the postimplantation CT and reviewed by the analyst, and tractography is reconstructed within the application. Channel-indexed results computed outside the platform, such as high-frequency oscillation counts from pyHFO or time-resolved gamma responses, are projected onto the contacts and the cortical surface 

---

### [274] The Vibe Paradox: What EEG Reveals About Your Brain When Vibe Coding

**链接**: https://arxiv.org/abs/2611.02087
**作者**: Olivia Schutz, Rudrajit Choudhuri, Yunhan Qiao, Fatima A. Moussaoui, Julia Russo, Zoe Steine-Hanson 等 (7 人)
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Much of the enthusiasm for vibe coding rests on two intuitive beliefs: (1) that developers stay invested even when they no longer write the code, and (2) that delegating more of the work to AI lowers their cognitive load. Objective: Our goal was to investigate whether developers' neurophysiological states and interactions with AI are consistent with these beliefs when they work with agentic vs. non-agentic AI on their own project vs. a legacy codebase. Method: We conducted an exploratory within-subjects crossover study with 11 participants across 22 sessions. Each participant used GitHub Copilot Chat in one session and Cursor Agents in the other, working on their own project and a legacy codebase, with tool-codebase pairings randomly assigned and session order counterbalanced. We recorded participants' EEG, on-screen activity, and prompts, and analyzed 7,924 EEG data points, 984 activities, and 141 prompts. Results: Our findings contradict both beliefs. With the agent, part

---

### [275] METER: Matched-Event Calibration for Short-Event EEG Microstate Transition Analysis

**链接**: https://arxiv.org/abs/2611.02045
**作者**: Abdul Basit, Eklavya Tomar, Muhammad Shafique
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Short cognitive events contain unequal and often sparse transition evidence, so raw EEG microstate distances can reflect finite sampling rather than neural reconfiguration. We introduce METER (Matched-Event Transition Estimation against a Reference), a participant-relative framework that separates marginal occupancy from conditional next-state choice and evaluates each event against duration-conditioned events from a fixed participant-specific reference bank. METER-Jump integrates uncertainty in sparse target and reference transition tables, returning a randomized event rank for testing and a continuous standardized coordinate for association analysis. Using a reproducible three-state representation selected by spatial criteria, we evaluated METER with participant-fitted simulations, estimator ablations, map perturbations, and preprocessing sensitivities. Event-level false-positive rates were 0.044-0.056 across four heterogeneous null mechanisms. By contrast, global cutoffs learned und

---

### [276] Beyond Augmentation: Score-Guided Pathological Prior for EEG-based Depression Detection

**链接**: https://arxiv.org/abs/2606.00180
**作者**: Xiaojing Chen, Jingqi Cheng, Xu Zhao, Wan Jiang, Jingjing Wu
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [277] GraTED: Graph--Tensor EEG Decoding for Passenger Hazard Perception in Autonomous Vehicles

**链接**: https://arxiv.org/abs/2611.02827
**作者**: Yuxuan Gu, Yingkai Yang, Qiyu Rao, Tania Stathaki, Danilo Mandic
**来源**: cs.LG cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Passenger electroencephalography (EEG) can reveal road risk through anticipatory responses before hazardous events and neural reactions around their onset. However, existing EEG decoding methods often map physiologically meaningful arrangement of electrodes onto artificial 2D grids and thus flatten the higher-order time-feature representations into matrices, obscuring meaningful structure in the data. To preserve and exploit the spatial and time-feature structure of EEG recordings, we propose the Graph-Tensor EEG Decoding Model (GraTED) for passenger risk prediction (RP) and danger identification (DI) in autonomous-vehicle scenarios. GraTED models the electrode arrangement as an undirected graph based on their scalp locations, using graph convolution to capture spatial dependencies and low-rank tensor classification to preserve the multidimensional time-feature structure, while controlling model complexity. Evaluated on the PassengerEEG dataset, comprising 11 participants and 45 hours 

---

### [278] Neonatal EEG Seizure Prediction with Quantum Inspired Continuous-Variable (Bosonic) Reservoir Computing

**链接**: https://arxiv.org/abs/2611.00008
**作者**: Krishna Bhatia, Chun-Yu Lin
**来源**: physics.med-ph cs.LG quant-ph
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study short-horizon neonatal seizure prediction on Helsinki-style (HUH) preprocessed EEG feature tables using quantum-inspired reservoir computing. Under strict subject-wise cross-validation on imbalanced preictal--interictal windows, we test whether reservoir constructions shaped after (i) gate-based qubit dynamics and (ii) continuous-variable (bosonic/photonic) dynamics provide a practical sequence encoder relative to strong classical baselines. Both reservoirs are executed here purely in classical simulation on a single GPU; accordingly, we do not claim quantum advantage, but rather evaluate whether quantum-shaped dynamics act as useful, low-footprint random feature maps with a trained linear readout. We compare against Random Forests and RBF--SVMs, and report AUROC, AUPRC, per-subject AUPRC, expected calibration error, and stratified bootstrap confidence intervals. Across our experiments, the CV/bosonic reservoir is consistently competitive and can improve AUPRC over the baselin

---

### [279] Thought-deciphering via hierarchical EEG-to-text alignment

**链接**: https://arxiv.org/abs/2611.03623
**作者**: Xiaopeng Mao, Morten M{\o}rup, Xin Xu, Sang Wan Lee, Sadasivan Puthusserypady
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Communication is important for our well-being, but it can be impaired by disabilities, such as locked-in syndrome (LIS), cerebral palsy (CP), and dysarthria. Non-invasive brain-to-text brain-computer interfaces (BCIs) offer a promising solution by providing an alternative communication pathway for people with communication disabilities. However, most recent breakthroughs have relied on large, cumbersome, and costly neuroimaging modalities, such as functional magnetic resonance imaging (fMRI) and magnetoencephalography (MEG). Numerous studies have attempted decoding using the lighter and cheaper electroencephalography (EEG), but the results remain inferior compared to the other modalities. More importantly, we do not understand how these modalities are related to text at the letter, word, sentence, and higher semantic levels. Many prior studies have focused on decoding below the sentence level because it is considerably easier to design an experiment around phonemes, letters, and words.

---

### [280] Band2Net: Frequency-to-Network Transport Distillation for fMRI-Privileged, EEG-Only Session-Condition Decoding

**链接**: https://arxiv.org/abs/2611.01548
**作者**: Nishi Kanta Paul, Md Shihabul Islam Shovo and Dwarikanath Mahapatra
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Functional MRI resolves large-scale brain networks but is expensive and stationary, whereas EEG is portable but poorly localised. We treat fMRI as privileged information, available during training and absent at deployment, with EEG and fMRI acquired from the same participants under matched conditions but not simultaneously. Band2Net encodes EEG into five frequency-specific connectivity graphs and fMRI into seven canonical network tokens from a frozen teacher, and solves a balanced entropic transport problem between the two token sets that gives each EEG band its own fMRI target. In subject-grouped cross-validation on the PsiConnect psilocybin data set, Band2Net reaches 0.801 ROC-AUC for EEG-only session-condition decoding, 5.0 AUC points (95% CI 1.8-8.2) above an EEG-only student. Although its margins over a single shared plan, a KL-relaxed plan and label-free network descriptors remain unresolved, secondary comparisons favour band-specific transported targets over logit, global-featur

---

### [281] ERIA: An Instruction-Optimized Agent for Clinical EEG Reporting

**链接**: https://arxiv.org/abs/2611.01394
**作者**: Ahmed Sameh, Gayal Kuruppu, Neeraj Wagh, Bridger Brundy, Yogatheesan Varatharajah
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical EEG interpretation requires integrating technical quality, background and behavioral states, interictal and ictal abnormalities, and overall clinical context across long recordings. We introduce ERIA (EEG Reporting and Instruction-Optimized Agent), a locally deployable framework in which a single 27B language-model controller analyzes whole-recording EEGs by orchestrating specialized parametric and signal-processing tools. ERIA combines learned tools for background abnormality, sleep-wake state, seizure-like activity, and interictal epileptiform discharges with deterministic spectral, amplitude, symmetry, montage, and signal-quality analyses. Rather than fine-tuning the controller or using multi-agent orchestration, ERIA keeps the controller weights, specialist tools, and safety constraints fixed and optimizes only its natural-language analysis policy with GEPA (Genetic-Pareto), using feedback from expert-written EEG reports. GEPA improves physician-aligned whole-recording rep

---

### [282] LEAF: Language-EEG Aligned Foundation Model for Brain-computer interfaces

**链接**: https://arxiv.org/abs/2509.24302
**作者**: Muyun Jiang, Shuailei Zhang, Zhenjie Yang, Mengjun Wu, Wei Zhang, Weibang Jiang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [283] Robust EEG-based Emotion Recognition from Coarse Trial-level Labels under Intra-trial Affective Variability

**链接**: https://arxiv.org/abs/2611.01731
**作者**: Xiaocong Zeng, Buxuan Wang, Xin Yang, Pei Huang, Dongyang Kuang
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG-based emotion recognition has become an active research area in brain-computer interfaces. However, fine-grained affective annotation is costly, so most datasets provide only a global label for each long EEG trial. For practical emotion recognition, trials are commonly divided into short temporal windows, with the global label propagated to all windows for training. This practice treats trial-level emotion as temporally uniform, although affective responses may fluctuate within a trial. Consequently, windows that weakly reflect or deviate from the global emotional state may receive unreliable labels, posing a key challenge to robust EEG-based emotion recognition. To address this challenge, we propose VARY, a variability-aware robust learning framework for EEG-based emotion recognition from coarse trial-level labels. VARY incorporates a Two-stage Sample Selection (TSS) strategy to identify EEG windows with reliable emotional labels, and introduces MixAug, a data augmentation method 

---

### [284] Inner-Speech Decoding from EEG Across Three Corpora Under a Fixed Architecture and Protocol

**链接**: https://arxiv.org/abs/2611.02180
**作者**: Md Wahiduzzaman Suva, Md Imtiaj Alam Sajin, Esm E Moula Chowdhury Abha, Susham Moula Choudhury Akash, Md Tauhidul Islam, Abhijit Bhowmik 等 (8 人)
**来源**: cs.AI cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inner-speech decoding from electroencephalography could support non-invasive communication for people with severe motor impairment, but comparison across studies is hindered by dataset- and protocol-specific evaluation. We present a controlled cross-dataset study using one preprocessing pipeline, one within-subject five-fold cross-validation protocol, and a compact dual-attention Transformer (VC-DATNet; approximately 131,000 parameters) across three public corpora: Thinking Out Loud (10 participants), BISpeech (4), and SyncSpeech (3). VC-DATNet achieved per-participant sensor/source hybrid accuracies of 39.48% on the four-class Thinking Out Loud task, 20.60% on the eight-word BISpeech task, and 25.53% on the eight-word SyncSpeech task, for which we report the first decoding result. Sensor-space and cortical source-space representations were complementary, with each performing better for different participants; this pattern replicated across all three corpora and nine architectures. Mor

---

### [285] Beyond Reconstruction: What EEG-to-Video Decoding Actually Recovers

**链接**: https://arxiv.org/abs/2505.21385
**作者**: Prajwal Singh, Anupam Sharma, Pankaj Pandey, Krishna Miyapuram and Shanmuganathan Raman
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [286] MultiMental-IAS: A Multimodal Driver Mental State Analysis Dataset for Context-Aware Non-IID Evaluation

**链接**: https://arxiv.org/abs/2611.02790
**作者**: Baran Can G\"ul, Nagendra Pal Singh, Anjana Arvind Naik
**来源**: cs.HC cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robust driver-state modelling requires synchronized physiological, behavioural, and contextual signals, yet existing open resources typically target a single cognitive state, omit continuous vehicle context, or do not define evaluation protocols that expose inter-subject heterogeneity. We present Multimental-IAS, a multimodal driver mental-state dataset collected in a cockpit-in-the-loop simulation built on CARLA. It contains vehicle telemetry with scenario-context channels, four-channel EEG and three-channel PPG from a Muse 2 headband, and cabin-facing video from 23 participants, recorded in 148 trials (11.6 hours) under six induced states: Normal, Distracted, Alerted, Stressed, Relaxed, and Drowsy. We document the acquisition pipeline in detail and provide a benchmark with one protocol for all models: chronological within-subject splits, participant-disjoint cross-subject folds, validation-based model selection, and ablations over modalities, scenario-context channels, and signal nor

---

### [287] OpenMidnight: Closing the Performance Gap Between Open and Proprietary Pathology Foundation Models

**链接**: https://arxiv.org/abs/2611.00064
**作者**: Ratna Sagari Grandhi, Anis Chihoub, Ryan Kim, Daniel Z. Kaplan, Chao Feng, Anish Dulal 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models offer transferable representations for a range of downstream tasks in computational pathology, but reliance on proprietary data, substantial compute requirements, and limited availability of training code and preprocessing pipelines hinder independent validation and further methodological development. We present OpenMidnight 1.1, an open-source replication and refinement of Midnight trained on approximately 12,000 publicly available whole-slide images from The Cancer Genome Atlas. Using an encoder initialized with pretrained DINOv2 weights, OpenMidnight 1.1 uses approximately 320 H100 GPU-hours for pathology pretraining, a 34-fold reduction relative to the compute reported for Midnight. Across 16 classification and four segmentation datasets in THUNDER, OpenMidnight 1.1 achieves the highest mean segmentation Dice (69.7) and ranks fourth among 14 models, ahead of Midnight, with performance that matches or exceeds models trained on substantially larger dataset

---

### [288] Towards fNIRS foundation models: A curated corpus of 67 public datasets with channel positions in MNI space

**链接**: https://arxiv.org/abs/2610.40277
**作者**: Santiago Posso-Murillo
**来源**: cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [289] Versatile Graph Foundation Models from Frozen Time-Series Foundation Models via Parallel Flows

**链接**: https://arxiv.org/abs/2611.00670
**作者**: Jielong Yang and Feng Ji
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph foundation models aim to serve unseen graphs across tasks, feature spaces, and label sets. Most current models learn how to represent a new graph by pre-training on other graphs. Because graph data are scarce and differ across domains in features and structures, what they learn may not transfer to a graph from an unseen domain. We show that a frozen time-series foundation model, pre-trained on abundant time series, can instead serve as a graph foundation model without graph pre-training and without any gradient update on the target graph. Such a model reads ordered multivariate sequences, but a graph has no time axis, and covering all its edges with sequences is nontrivial because a node can have many neighbors. We therefore propose GraphFlowFM, which decomposes a graph into parallel flows, sets of vertex-disjoint paths that jointly cover every edge, and reads each path as a multivariate time series with the nodes as time steps. A frozen TimesFM encodes the paths with causal atte

---

### [290] Control Foundation Models across Changing Block Diagrams: Generalizing Time-Series Prediction to Dynamic Graphs

**链接**: https://arxiv.org/abs/2611.02900
**作者**: Yuji Okamoto, Kenta Hoshino, Masaki Inoue
**来源**: eess.SY cs.LG cs.SY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the prediction and control of physical systems, combining records from different experiments and operations is expected to supply information that no single experiment provides on its own. Time-series foundation models, which learn a shared predictor from diverse time series, offer a framework for treating such records as a common training resource. Moreover, query-based prediction models, which switch between known and target signals within the same time series, make it possible to handle response prediction and control-input generation in a unified manner. However, in control-experiment data, the connections between signals change with the experimental stage, such as system identification, filtering, and feedback control, which calls for a formulation that handles signal values and connection structures dynamically and in a unified way. We formulate a control foundation model that defines a data space of dynamic graphs containing connections, signal values, and missing values, tog

---

### [291] Blueprint2CAD: Benchmarking Foundation Models on Engineering Drawing-to-CAD Render Correspondence

**链接**: https://arxiv.org/abs/2611.02433
**作者**: Alexander Valverde, Danny Xie-Li, Zhichao Wang, Marcos V. Conde
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Engineering drawings specify mechanical parts through orthographic projections. Recognizing which part a drawing depicts underlies part search, design reuse, and digitization, yet no public benchmark measures whether vision models can do it. We introduce Blueprint2CAD, a benchmark for drawing-to-render correspondence: given an orthographic line drawing and a shaded render, usually from another viewpoint, decide whether they show the same part. Its data layer, BlueCAD-30K, applies an open drafting pipeline to 29,925 Zero-to-CAD models, adding view-aligned renders, clean and dimensioned drawings from six viewpoints, and surface-type metadata. Frozen encoders retrieve the matching part from a 10,000-model gallery with up to 65% Recall@1 when viewpoints are known but 43% when they are not, and the four encoders we test lie within six points of each other: viewpoint, not backbone, is the bottleneck. Six zero-shot vision-language models reach only 0.52-0.67 verification accuracy, with model-

---

### [292] Investigating the effects of the patch size in Time Series Foundation Models

**链接**: https://arxiv.org/abs/2611.02750
**作者**: Jad Yehya, Andrei-Tiberiu Pantea, Aymeric Dieuleveut, Matthieu Kowalski, Thomas Moreau
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patch size is a central design choice in patch-based time-series foundation models, controlling temporal resolution, sequence length, and computational cost. We study how this choice interacts with transformer architecture through a controlled comparison of encoder-only and decoder-only forecasting models trained with the same data mixture and optimization budget. Across 97 GIFT-Eval tasks, encoder-only models consistently benefit from smaller patches, whereas decoder-only performance follows a U-shaped trend, with an intermediate patch size performing best in aggregate. Dataset-level results further show that the preferred decoder patch size increases with the forecasting horizon. For encoder-only models, increasing context length improves performance across patch sizes, although the gains diminish beyond a context length of 2048. Finally, training-compute and CPU-latency Pareto analyses reveal complementary regimes: decoder-only models provide efficient low-cost alternatives, while e

---

### [293] Zero-shot time-series foundation models against the Khepri v1.5 baselines for 96-hour carbon-intensity forecasts in nine Nordic bidding zones: a preregistered comparison

**链接**: https://arxiv.org/abs/2611.02895
**作者**: Eirik Botten Nicolaysen
**来源**: physics.soc-ph cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We compare three zero-shot time-series foundation models (Timestral-5M, Timestral-209M and Chronos-2, 8192-hour context, no covariates) with the Khepri v1.5 SARIMA and GBM baselines, with their code and hyperparameters unchanged, for 96-hour forecasts of hourly carbon intensity in the Nordic bidding zones NO1-NO5 and SE1-SE4. The design, the analysis code and a minimum detectable effect (MDE) were timestamped before any foundation-model forecast by an OpenTimestamps proof (Bitcoin-confirmed) and the GPG-signed tag prereg-v1; the proofs are archived in Zenodo (DOI 10.5281/zenodo.23881315). The preregistration was also submitted to OSF Registries 2026-11-02 07:49 UTC (osf.io/hncz5; embargo requested, pending OSF approval). On the 2025 test (361 daily origins, contamination not ruled out) all three models have a lower zone-averaged MAPE than both baselines, by 0.952 to 1.347 percentage points (Diebold-Mariano with the Harvey-Leybourne-Newbold correction, all p < 0.0001), and each beats SA

---

### [294] Geometric Morphology Learning: Empowering Foundation Models from Structure to Spacetime Intelligence

**链接**: https://arxiv.org/abs/2611.01932
**作者**: Li Sun, Philip S. Yu
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geometry is the very form that connects space, time, and matter, serving as the fundamental fabric of the physical world, from continuous fields to discrete structures. Despite its importance, deep learning is inherently blind to geometry. Riemannian geometry stands as a well-established mathematical foundation for studying geometry, yet it remains largely incompatible with deep learning architectures. To bridge this gap, we establish a new learning framework--Geometric Morphology Learning--that learns geometric or topological structures, shapes or conformations for representation learning, reasoning and action modeling. Moving beyond early attempts limited to specific geometric priors, this theory centers on modeling the intrinsic geometry of objects and learning from such geometric or topological knowledge. Specifically, we construct a neural bundle, a unified scaffolding linking local and global structures, and formulate differentiable operators, including connection and curvature, 

---

### [295] GESTALT: Fast, Generalizable Histopathology Image Synthesis from Gene Expression with Pretrained Pathology Foundation Models

**链接**: https://arxiv.org/abs/2611.01141
**作者**: Felix Ho, Alexandros Graikos, Dimitris Samaras
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial transcriptomics measures gene expression while preserving where each cell sits in the tissue. The inverse, what a given transcriptomic state looks like, is less explored but equally useful: it lets researchers visualize the morphological consequence of a molecular state and interpret a spatial assay's molecular calls against real tissue structure. GeneFlow, the current state of the art on the Xenium gene expression-to-image benchmark, trains a model from scratch, incurring a high cost on every new target dataset it is applied to. We instead propose GESTALT, which reformulates gene expression-to-image synthesis as predicting a pathology foundation model's image embedding. A lightweight gene-token transformer predicts this embedding from multi-cell gene expression, and a frozen or LoRA-adapted diffusion decoder (PixCell) renders it as an image. Because this visual knowledge is reused rather than relearned, GESTALT trains in a fraction of the time. In both multi-cell and single-ce

---

### [296] SAFE-SVD: Sensitivity-Aware Fidelity-Enforcing SVD for Physics Foundation Models

**链接**: https://arxiv.org/abs/2605.17985
**作者**: Chengjie Hong, Feixiang He, Yiheng Zeng, Lulu Kang, He Wang
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [297] RSPDBench: Benchmarking Vision Foundation Models on Earth Observation Tasks Under Physically Grounded Remote-Sensing Product Degradations

**链接**: https://arxiv.org/abs/2609.23427
**作者**: Tanjim Bin Faruk, Khondaker Masfiq Reza, Shrideep Pallickara, Sangmi Lee Pallickara
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [298] SensOFormer: Foundation Models for Particle Accelerators

**链接**: https://arxiv.org/abs/2611.02031
**作者**: Mahindra Rautela, Alexander Scheinker
**来源**: cs.LG physics.acc-ph
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale scientific facilities, such as particle accelerators, are complex systems composed of thousands of interacting components that must operate collectively to support diagnostics and control, and ensure safe, reliable operation. These facilities rely on extensive sensor networks that generate large volumes of heterogeneous, incomplete, and noisy telemetry, often sampled at different rates across subsystems. In this paper, we adopt the foundation-model paradigm to learn general-purpose sensor representations from historical accelerator data through self-supervised pretraining. We introduce SensOFormer, a denoising masked transformer with a Perceiver-style encoder-decoder architecture designed to handle variable sensor sets, accommodate heterogeneous sampling rates, and learn robust representations from noisy measurements. The model is pretrained on multiple particle-accelerator datasets and transferred to downstream tasks, including missing-data imputation, anomaly detection, c

---

### [299] Evaluating Uncertainty Calibration in Probabilistic Time Series Foundation Models

**链接**: https://arxiv.org/abs/2611.03592
**作者**: Thomas Decker and Volker Tresp
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) are increasingly used for probabilistic forecasting across diverse domains, yet the reliability of their uncertainty estimates remains poorly understood. In this work, we study uncertainty calibration in probabilistic TSFMs from a broader methodological and empirical perspective. We introduce a taxonomy of how TSFMs represent predictive uncertainty and develop a fine-grained evaluation framework for calibration in multi-horizon forecasting that distinguishes pooled, horizon-wise, and stronger conditional notions of calibration. Using this framework, we conduct a comprehensive empirical evaluation of popular TSFMs across diverse datasets and show that current models exhibit distinct and systematic patterns of miscalibration that standard metrics often obscure. We further analyze common post-hoc recalibration methods and characterize which forms of calibration they can improve and which tend to persist. Our results provide practical guidance for eval

---

### [300] Benchmarking Generalist and Specialist Time-Series Foundation Models for PPG-Based Health Assessment

**链接**: https://arxiv.org/abs/2510.14254
**作者**: Saurabh Kataria, Yi Wu, Zhaoliang Chen, Hyunjung Gloria Kwak, Yuhao Xu, Lovely Yeswanth Panchumarthi 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [301] A Common Language for Dynamic Graphs: Interaction Tokenization Enables Foundation Models

**链接**: https://arxiv.org/abs/2611.03246
**作者**: Fuyuan Ma, Yili Wang, Xin He, Xin Zhang, Ying Wang, Xin Wang
**来源**: cs.LG cs.SI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic graphs capture evolving interactions in Web systems, including online communication, user engagement, and recommendation. Graph foundation models aim to reuse predictive capabilities across networks, but extending this capability to dynamic graphs faces two challenges. First, node identities are graph-specific, and similar interaction patterns can appear at different temporal and activity scales, making histories difficult to represent consistently across networks. Second, the predictive roles of historical patterns vary across interaction dynamics, limiting transfer from a narrow range of training processes. In this paper, we show that a common interaction language, combined with learning across diverse interaction processes, offers a basis for dynamic graph foundation modeling. We propose CL-DGFM, a Common Language Dynamic Graph Foundation Model for temporal link prediction. Its Dynamic Interaction Tokenizer encodes interaction memory, historical connectivity, and ordered des

---

### [302] Attribution-based diagnostics for single-cell foundation models

**链接**: https://arxiv.org/abs/2611.02335
**作者**: Farnoush Rezaei Jafari (1 and 2), Tristan Lazard (3), Kenza Bouzid (3), Shruthi Bannur (3), Jeremiah Wander (3), Ashley Mae Conard (3) 等 (10 人)
**来源**: cs.LG q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-cell RNA foundation models (scFMs) are increasingly used for in-silico biological discovery, yet predictive performance alone does not reveal whether their decisions rely on biologically meaningful signals or model-specific shortcuts. We systematically investigate post-hoc attribution of downstream predictions across two tasks: cell-type annotation using pretrained Cell2Sentence and scGPT models, and perturbation prediction using scGPT+STATE in a controlled setting. For cell annotation, we use attribution to assess whether predictions rely on established marker genes and how their relevance varies with model architecture, expression rank, and the surrounding cellular context. For perturbation prediction, we compare attribution patterns with known regulatory ground-truth in a synthetic setting to assess what they reveal about the model's learned computations. Across these tasks, attribution reveals biological feature use, contextual interactions, contributions from different inpu

---

### [303] Why Tabular Foundation Models Excel on Relational Data They Have Never Seen

**链接**: https://arxiv.org/abs/2611.02936
**作者**: Linjie Xu, Yiqun Hu, Jixiang He, David Wipf
**来源**: cs.AI cs.DB cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Given a relational database (RDB) storing heterogeneous tabular information, how can we predict missing (or future) values in some target column of interest? As candidate targets are numerous in enterprise settings, it is preferable to avoid learning a new model from scratch each time there is a new prediction task. Frozen foundation models (FMs) based on in-context learning (ICL) and RDB-specific pre-training provide a viable solution, but the ideal design still remains largely unresolved. Perhaps unexpectedly, preliminary evidence has recently shown that existing single-table FMs (aka TFMs), when combined with suitable parameter-free relational encoders, can be quite competitive in practice despite zero exposure to RDB pre-training or relational data of any kind. In this work we first empirically confirm this phenomenon with a more diverse array of experiments. We then turn to our main contribution, namely, surfacing multiple complementary explanations for why TFMs behave so effectiv

---

### [304] Foundation Models to Unlock Real-World Evidence from Nationwide Medical Claims

**链接**: https://arxiv.org/abs/2605.02740
**作者**: Fan Ma, Yuntian Liu, Xiang Lan, Weipeng Zhou, Jun Ni, Mauro Giuffr\`e 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [305] Unlocking the Potential of Vision Foundation Models for Multi-Task Dense Prediction via Mixture of Task Adapters

**链接**: https://arxiv.org/abs/2611.02769
**作者**: Yunzhi Zhuge, Xinzhuo Yu, Sitong Gong, Lu Zhang, Pingping Zhang, Huchuan Lu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-task dense prediction seeks a single, coherent representation that supports simultaneously discriminative semantic recognition and regularized geometric/structural inference. For vision foundation models, pretrained semantic invariances conflict with the frequency and smoothness biases of dense objectives; joint fine-tuning and single-route adapters therefore compress competing gradients into one update channel, causing negative transfer and unstable cross-task agreement. We frame this as two-level adaptation: task-generic alignment that preserves priors, and task-aware specialization that resolves late-stage conflicts. Based on this principle, we propose D2MoE , a Mixture of Task Adapters that explicitly factorizes these roles within a frozen DINOv3 backbone. D2MoE introduces Task-Generic Low-Rank Adaptation (TG-LoRA) in attention projections throughout the network to provide a stable, shared adaptation channel, and a Task-Adaptive Mixture of Experts (TA-MoE) injected only at th

---

### [306] When Delay Meets Drift: Physical Safety of Robot Foundation Models Is a Cross-Layer Problem

**链接**: https://arxiv.org/abs/2611.02101
**作者**: Liangkai Liu, Bimal Thapa Magar
**来源**: cs.RO cs.CV cs.ET
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot foundation models now act in a closed loop, yet their safety is evaluated one variation at a time: robustness benchmarks perturb the scene while assuming instantaneous inference, and real-time execution methods study inference delay in nominal scenes. We argue that physical safety is not a property of the model alone, but emerges from how variations in the physical environment, the model, the computing platform, and execution interact in closed loop. We formalize this as cross-layer variation propagation across these system layers and use an interaction contrast to measure when joint variation creates more risk than the sum of its parts. In 4,000 paired closed-loop episodes of the pi0.5 vision-language-action model on LIBERO, a 400 ms inference delay raises the safety-violation rate by 3.5 percentage points under the training viewpoint but by 37 percentage points under a 60-degree camera shift: 33.5 percentage points (95% CI: 25-43) more than the two effects combined. We close wi

---

### [307] GRATE: Temporal Extensions for Inductive KG Foundation Models via Gated Rotary Attention

**链接**: https://arxiv.org/abs/2607.10197
**作者**: Jiaxin Pan, Osama Mohammed, Daniel Hern\'andez, Steffen Staab
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [308] Axion 1.0: Open Agent Foundation Models, Simplified

**链接**: https://arxiv.org/abs/2611.03233
**作者**: Yuqi Jia, Yunjie Tian, Jiayu Zheng, Yijun Liang, Jingchen Sun, Mengyu Zhao 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Axion 1.0, a fully open agent foundation model that combines strong and broad agentic capabilities with a remarkably simple training recipe. Axion 1.0 is trained in only three stages: two lightweight supervised fine-tuning stages followed by reinforcement learning, without dedicated mid-training, direct preference optimization (DPO), or on-policy distillation (OPD). The first SFT stage develops strong self-contained reasoning through model-aware data construction, where we synthesize challenging problems and adversarially strengthen them based on the base model's own successful solution strategies. The second stage extends these capabilities to tool-dependent reasoning through a scalable pipeline for constructing diverse and automatically verifiable tasks grounded in real-world data sources and deterministic computation. Finally, reinforcement learning further strengthens long-horizon reasoning and interaction with external tools and environments. Despite this compact trai

---

### [309] From Concepts to Actual Causes: Toward Closing the Concept-Malfunction Gap in Robot Foundation Models

**链接**: https://arxiv.org/abs/2611.00155
**作者**: Gihyuk Ko
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-incident analysis of a robot foundation model poses a singular causal question: which internal components caused this failure, and to what degree? Mechanistic interpretability (MI), however, establishes general causal claims by decoding the concepts a policy has learned, yet knowing which concepts are encoded is insufficient for identifying the actual cause of a specific incident. In this position paper, we analyze this concept-malfunction gap by posing fault isolation in the framework of actual causality. Specifically, we formalize a fault-isolation query as a tuple of intervened internal components, counterfactual values, contingencies, and read-outs, and lay out conditions for it to be well-specified. Through this lens, we identify shortcomings of current MI approaches: they assume fixed contingencies and read out only immediate effects, letting backups obscure actual causes. We demonstrate on a toy example that these shortcomings can lead to conflicting verdicts. Lastly, based

---

### [310] TabAbax: A Tabular Foundation Model Technical Report

**链接**: https://arxiv.org/abs/2611.00562
**作者**: Zhixiong Cheng, Xiaoyun Gao, Shiyuan Han, Jingjing Suo, Zhengli Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) enable in-context prediction on unseen tabular datasets without task-specific training. Mechanistic work has shown that increasing the depth of the ICL Transformer yields weak gains, leaving the main headroom for gains in the synthetic pretraining prior and column-row encoder upstream of the ICL backbone. We introduce TabAbax, a TFM built on TabICLv2 that focuses all modifications on these two upstream components. On the prior side, we further improve the quality and complexity of the synthetic pretraining prior. On the encoder side, a two-pass column-row stack strengthens cross-feature interactions before row compression, using learned Fourier scalar encoding from TabFM and Causilo. Evaluations on BeyondArena and TabArena show strong regression-centric gains: TabAbax reaches 1,238 Elo on the 142-dataset BeyondArena suite (10th of 41 evaluated methods), 1,676 Elo on TabArena's overall 51-dataset suite (11th of 99 methods, +115 over TabICLv2), and 2,024 

---

### [311] ASCoR: Asymmetric Semantic-Spatial Learning for Remote Sensing Domain Generalization

**链接**: https://arxiv.org/abs/2611.03382
**作者**: Zitong Wang, Shuchang Lyu, Meng Li, Qiang Wang, Guangliang Cheng and Zhenwei Shi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Source-only domain generalization (DG) for remote sensing semantic segmentation seeks reliable predictions in unseen domains without target-domain data during training. Although vision foundation models offer transferable knowledge, category recognition remains sensitive to source-specific visual cues, while task-specific adaptation may weaken pretrained transferability. We propose ASCoR, an asymmetric semantic-spatial framework built on SAM3. Its text-conditioned semantic branch uses class-name prompts to provide explicit category guidance. Probe-Once Dynamic Adaptive LoRA distributes a fixed adaptation budget across encoder blocks to limit source-specific specialization. A complementary task-specific dense branch learns multi-scale spatial representations using a separate frozen SAM3 image encoder. A lightweight reliability router integrates the two branches through bounded spatial correction based on local prediction reliability. All components are trained using source-domain superv

---

### [312] QVR3D: Query-Guided Visual Reasoning for Training-Free 3D Grounding

**链接**: https://arxiv.org/abs/2611.01084
**作者**: Jung-Hao Kao, Jing-En Huang, Jia-Wei Liao, Tzuhsuan Huang, Yu-Lun Liu, Cheng-Fu Chou 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D visual grounding localizes objects in 3D scenes from natural language descriptions, requiring reasoning over semantics, spatial relationships, and multi-view observations. Training-free approaches avoid costly annotations but often rely on explicit scene transformation or scene-level frame selection, which may waste limited visual capacity on query-irrelevant regions. We observe that effective grounding should prioritize observations that provide evidence for the query rather than uniformly represent the entire scene. Based on this insight, we introduce QVR3D, a query-guided visual reasoning framework that operates on RGB-D observations using off-the-shelf foundation models. QVR3D combines Query-Guided Maximum Coverage (QGMC) for selecting complementary query-relevant views with Grounding Probability Estimation (GPE) that integrates instance confidence, attribute consistency, and relationship consistency. The framework supports both single- and multi-object grounding without task-sp

---

### [313] ReCoG: Relative Node Contexts for Multi-Domain Graph Pre-training

**链接**: https://arxiv.org/abs/2611.01753
**作者**: Yupeng Tong, Lianze Shan, Jitao Zhao, Dongxiao He
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The success of foundation models in language and vision has motivated Graph Foundation Models (GFMs), which learn transferable knowledge through multi-domain graph pre-training. Existing methods advance GFMs through feature unification and structural learning, and in doing so they rely on the raw graph structure to organize node contexts. However, we observe that removing a large proportion of edges from source graphs during pre-training improves cross-domain transfer accuracy across four representative methods. Our theoretical analysis identifies the raw graph structure as a source of conflict in cross-graph model sharing. We therefore advocate defining node contexts using criteria consistent across graphs. Achieving this requires (1) constructing node contexts consistently across graphs without a shared positional structure, such as the token order of text or the pixel grid of images, and (2) retaining the structural and neighborhood information of the original graphs. To this end, w

---

### [314] HistoTx: Early fusion of H&E images and spatial transcriptomics at varying spatial transcriptomics resolution with self-supervised learning

**链接**: https://arxiv.org/abs/2611.02681
**作者**: Alice Driessen, Emil Malmsten, Steffen Wolf, Bernd Illing, Isinsu Katircioglu, Adriano Martinelli 等 (10 人)
**来源**: cs.LG cs.AI q-bio.GN q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial transcriptomics maps gene expression across tissue sections and, when integrated with whole slide images, jointly captures both morphological architecture and molecular activity to provide a rich, multimodal view of tissue biology. ML approaches combining spatial transcriptomics and WSIs typically learn a mapping from morphological features to molecular profiles via contrastive alignment or supervised fine-tuning of pathology foundation models. In both cases, transcriptomics serves as a training signal rather than a true input modality, leaving inference fundamentally image-driven. We propose an early-fusion vision transformer architecture in which transcript tokens are constructed at arbitrary spatial resolution, merged with image patch tokens, and jointly processed through a shared transformer stack for deep cross-modal interaction. Starting from a pretrained vision-only pathology foundation model, we train HistoTx by continuing self-supervised pretraining on paired image and

---

### [315] CellPlex: Benchmarking Single-Cell Spatial Proteomics Prediction from H&E

**链接**: https://arxiv.org/abs/2611.02506
**作者**: Zijun Gao, Yijiang Chen, Xiangde Luo, Pheng-Ann Heng
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial proteomics measures tens of proteins in every cell of a tissue section, but its cost confines it to small research cohorts, whereas hematoxylin and eosin (H\&E) slides exist for nearly every patient. Inferring single-cell spatial proteomics from H\&E would bring its analyses to routine pathology, and a growing number of virtual staining models pursue this goal. Each is evaluated on its own cohort, panel and pixel-level metric, and released models transfer poorly to new cohorts, leaving open which approach to build on and which proteins H\&E can reveal. We introduce CellPlex, a benchmark that poses the task at the level of the cell: seven cohorts with same-section H\&E and multiplexed immunofluorescence, from colorectal and breast cancer to lymph-node metastases, bone marrow and glioma, with 717 samples, 44.8 million cells and 149 proteins, processed by one pipeline into per-cell targets. Pathology foundation models (PFMs) are adapted with one cell-level protocol, specialist mod

---

### [316] SynForecast: Controlled Synthetic Time Series for Forecasting Research

**链接**: https://arxiv.org/abs/2611.02802
**作者**: Olivier Sprangers, Cristian Challu, Jan Rathfelder, Han Wang, Max Mergenthaler Canseco
**来源**: cs.LG stat.CO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic time series constitute a substantial share of the training corpora of several recent forecasting foundation models. Existing studies report benefits at small data budgets and modest synthetic proportions, but each evaluates individual combinations of model and generator. Studying these benefits systematically requires generators that support controlled configuration, perturbation, reproducibility and mechanism-level ablation, and the 11 existing generators we review show gaps in this combined support. We present SynForecast, an open-source Python library with 32 generators, 19 of which implement named mechanisms with a published source in econometrics, quantitative finance, statistical physics and point-process theory. Perturbations and mechanism families can be varied while everything else is held fixed, output comes in the long format that forecasting libraries accept, and output does not depend on the number of parallel workers. We evaluate SynForecast on M4 at five freque

---

### [317] TAP-Out: Tracking Any Point in 360{\deg} via Outpainting

**链接**: https://arxiv.org/abs/2611.00406
**作者**: Finlay G. C. Hudson, James A. D. Gardner, William A. P. Smith
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tracking points that leave the camera's field of view (FoV) requires reasoning about unobserved scene dynamics, a fundamentally different problem from tracking visible correspondences. We present TAP-Out, an offline method that makes this out-of-view (OOV) reasoning explicit by leveraging generative video outpainting as a world-model prior. Given a narrow-FoV input video, TAP-Out outpaints a complete 360{\deg} equirectangular video, locates target objects within the panoramic scene via video object segmentation, and synthesises object-centred perspective crops on which standard in-frame trackers operate. This decoupled design composes off-the-shelf foundation models without requiring task-specific architectural modifications. On the TAPVid360 benchmark, TAP-Out achieves state-of-the-art performance, improving OOV tracking accuracy by approximately 3x over the best prior method. We demonstrate its flexibility on out-of-frame object segmentation and detection and we provide detailed diag

---

### [318] Editing the Goal: Per-Token SAE Steering and Its Depth Limits in $\pi_{0.5}$

**链接**: https://arxiv.org/abs/2611.00602
**作者**: Rocio Perales Valdes, Animesh Garg
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) have recovered interpretable, causally relevant features in robot foundation models (RFMs) such as $\pi_{0.5}$ (

---

### [319] IsoAlign: Isoform-Aware DNA-Protein Alignment via Joint-Embedding Predictive Architectures

**链接**: https://arxiv.org/abs/2611.00241
**作者**: Niousha Sadjadi, Arman Seyed-Ahmadi, Tony Tu, Micaela Elisa Consens, Kerr Ding, Alif Munim 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Genomic foundation models (GFMs) have emerged as a powerful paradigm for learning DNA sequence representations, yet existing self-supervised pretraining strategies overlook alternative splicing and underperform compared to specialized models. To address this gap, we introduce IsoAlign, a multimodal framework that grounds genomic pretraining in isoform-aware DNA-protein alignment to learn biologically meaningful representations. IsoAlign aligns transcripts to their corresponding protein isoforms, capturing both coding sequences and broader regulatory contexts, using two Joint-Embedding Predictive Architectures (JEPA): DNA-Protein JEPA (DP-JEPA), which predicts protein representations from DNA using contrastive alignment, and Isoform-Masked JEPA (IM-JEPA), which models relationships among alternative isoforms of the same gene through masked protein prediction. We evaluate the learned DNA representations of these architectures across a multi-metric evaluation suite spanning tasks, includi

---

### [320] A generative foundation model for computational brain imaging

**链接**: https://arxiv.org/abs/2611.00265
**作者**: Yuting He, Xu Wen, Hongxing Lan, Chengliang Liu, Yuxing Liu, Yan Xi 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computational brain imaging is constrained by a mismatch between increasingly diverse tasks and scarce, heterogeneous clinical data. Although existing brain foundation models transfer pretrained representations, their knowledge remains entangled within model-specific features and fixed architectures. This paper proposes BrainGFM, a generative foundation model that extends knowledge transfer beyond representation reuse through a reusable and reconfigurable brain-imaging prior. By pretraining on a corpus of about 1.3 million MRI and CT slices, BrainGFM supported task-aligned data synthesis for low-data predictive learning and task-adapted post-training for image reconstruction. Across 48 downstream tasks, BrainGFM improved segmentation and classification under limited supervision and achieved high-fidelity image enhancement across heterogeneous imaging conditions. Multicenter clinical validation involving 4,796 stroke patients across two internal and four external centers demonstrated it

---

### [321] Forecasting Earth Surface Change in Embedding Space

**链接**: https://arxiv.org/abs/2611.02211
**作者**: Jingtao Li, Sadiq Jaffer, Anil Madhavapeddy, Pedro Sousa, Anthony Ortiz, Kyle Gao 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repeated satellite imagery permits understanding of how our planet changes over time, letting us predict its future and plan mitigating actions. Most existing studies that rely on a time series of satellite observations forecast the spectral values at each pixel for a future target date. However, clouds, shadows, and sensor noise often corrupt these observations, so that spectral forecasters waste much of their capacity on low-level features or noise rather than real change. With the advent of Earth foundation models, we argue that forecasting in embedding space is a feasible and more effective alternative. To this end, we design a token space that handles irregular histories from different sensors and foundation models and supports forecasts at any query date. Tokens from this space are inputs to our proposed forecaster, E$^2$Forecast, which is a transformer with two branches: a Gaussian branch that directly predicts a mean point forecast and per-dimension standard deviations, and a r

---

### [322] MedHEB: Benchmarking Medical Embeddings Across Heterogeneous Clinical Evidence

**链接**: https://arxiv.org/abs/2611.02519
**作者**: Yingshu Li, Shaoyang Zhou, Zhanyu Wang, Yunyi Liu, Xinyu Liang, Xi Zhang 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical evidence is inherently relational: medical images are interpreted with prior studies, cross-modal examinations, reports, and localized findings, and retrieving relevant evidence is therefore central to clinical interpretation. Recent foundation models increasingly encode these heterogeneous sources into shared embedding spaces, yet existing embedding evaluation often focuses on isolated matches, leaving unclear whether current models retrieve relevant evidence across changes in modality, appearance, and granularity. We introduce MedHEB, a unified benchmark with 107 retrieval tasks from 54 datasets, including both in-distribution and held-out-source evaluation, across three axes: evidence form (2D images, 3D volumes, text), pairing type (image--image, image--text, text--text, and modality-bridging visual matching), and relevance granularity (global, question-conditioned, region-level). Under a single ranking protocol, MedHEB varies clinically relevant evidence definitions to te

---

### [323] Latent Spectral Prompting for Multimodal Hyperspectral Object Tracking

**链接**: https://arxiv.org/abs/2611.02512
**作者**: Wangshu Cai and Jun Zhou and Lei Wang and Mohammad Aminul Islam and Xu Han and Kuldip Paliwal
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hyperspectral videos provide rich spectral signatures for robust tracking under challenging conditions such as camouflage and low illumination. However, limited hyperspectral annotations and the large RGB-hyperspectral domain gap hinder the direct use of modern temporally pretrained RGB trackers. We propose SProTrack, a multimodal framework that transfers temporal knowledge from pretrained RGB trackers to the hyperspectral domain through latent spectral prompting. The key idea is to decouple temporal modeling from spectral adaptation, allowing temporal dynamics to be inherited from RGB foundation models while hyperspectral information is learned from unlabeled data in a self-supervised manner. Unlike band-selection methods that discard most spectral information or prompt-based approaches that rely on local-search crops, SProTrack learns a global, scene-level spectral representation from the full hyperspectral frame using an autoencoder. This latent representation is used to guide spect

---

### [324] Data-Scarce, Multi-Granular, Multimodal: Benchmark Design for Biosynthetic Gene Clusters

**链接**: https://arxiv.org/abs/2611.02275
**作者**: Hanlin Xiao, Eriko Takano, Mauricio A. \'Alvarez, Rainer Breitling
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biosynthetic gene clusters (BGCs) are co-located genes that encode the biosynthesis of specialized metabolites, an important source of antibiotics, anticancer agents, immunosuppressants, and agricultural bioactives. Deep learning, particularly self-supervised foundation models, has spurred interest in BGC sequence modeling, but evaluation has lagged behind: existing benchmarks often rely on coarse classification over small curated datasets, providing limited discrimination among models and insight into downstream utility. We propose a benchmark-design framework in which an informative benchmark should be discriminative, separating models with statistical confidence, and applicable, spanning scientifically meaningful tasks under different levels of generalization. We instantiate this framework as BGC-Bench, which derives five tasks from MIBiG, ranging from A-domain substrate prediction to BGC-molecule retrieval, evaluates them under genotype- and phenotype-shift splits, includes an acti

---

### [325] Findings-aware Language-Image Pretraining for CT Volume Interpretation

**链接**: https://arxiv.org/abs/2611.02327
**作者**: Takuro Shimaya, Junya Inoh, Masahiro Saiko
**来源**: cs.CV physics.med-ph
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computed tomography (CT) provides diverse patient information and various clinical tasks, for which numerous deep learning models have been investigated. Recent years have seen the development of vision-language foundation models that can comprehensively extract clinical features, driven by representation learning that combines CT volumes with radiology reports. Existing approaches typically adopt Contrastive Language-Image Pre-training (CLIP)-based representation learning, where pairs from different cases are, in principle, treated as negative pairs such that the volume and report embeddings are pushed apart. In the biomedical imaging, however, treating different cases as negative pairs is not always appropriate, particularly when clinical similarity exists. In this study, we propose a supervised representation learning framework grounded in clinical knowledge from language foundation models, rather than the weak supervision used in CLIP. Specifically, we utilized a large language mod

---

### [326] Random Is Almost Enough? Stable and Low-Cost Benchmark Compression via BestRand

**链接**: https://arxiv.org/abs/2611.00883
**作者**: George Ling, Shanshan Zhong, Lijin Yang, Hao Yang, Nanxiang Li, Zhongzhan Huang
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmark compression reduces the often prohibitive time and cost of model evaluation by evaluating models on a small benchmark subset that closely matches full-benchmark results. To quantify estimation error, we derive an accurate analytical approximation to the error distribution when estimating full-benchmark scores from a subset, showing that most subsets yield small errors, while a few produce much larger errors, resulting in a long-tailed distribution. This means random sampling alone can achieve surprisingly strong performance with high probability, but remains unstable due to rare large errors. We further show that this instability is inherent to modern foundation models and persists even as more models are evaluated. Based on these findings, we introduce BestRand, a stable and low-cost benchmark compression method that preserves the efficiency of random sampling while substantially reducing its high-error tail. We validate BestRand on 70+ text, multimodal, and agent benchmarks

---

### [327] Leveraging 2D Foundation Priors for Generalized Category Discovery under Test-Time Adaptation in 3D LiDAR Segmentation

**链接**: https://arxiv.org/abs/2611.01682
**作者**: Hanqi Chen, Chaoqi Chen, Tian Ji, Hui Huang
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In autonomous driving, 3D LiDAR semantic segmentation is expected to adapt to evolving environments and recognize previously unseen categories, making generalized category discovery under test-time adaptation (GCD-TTA) an important problem. However, existing works treat GCD and TTA separately, while the limited semantic information in 3D point clouds makes GCD-TTA under domain shift more prone to feature collapse when combining GCD with TTA. To address this issue, we propose a two-stage framework for GCD-TTA in 3D LiDAR semantic segmentation. Specifically, in the first stage, we adaptively aggregate local 3D features according to geometric density variations and obtain reliable pseudo labels under a global class-wise prototype consistency constraint. In the second stage, we cast category discovery as an optimal transport assignment process for globally consistent grouping of novel categories. Meanwhile, semantic features from 2D vision foundation models are fused with 3D point cloud fe

---

### [328] Solv3R: 3D Looped Transformer as a Multi-view Solver

**链接**: https://arxiv.org/abs/2611.02857
**作者**: Jeong-gi Kwak, Andrea Tagliasacchi, Sho Kagami, Yuki Ono, Kwang Moo Yi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Classical structure-from-motion reconstruction proceeds iteratively, refining camera poses and scene geometry from a current estimate. This allows maps to easily expand without recomputing already computed views, or geometry estimates to improve as more observations are provided. Most geometric foundation models, however, predict entire geometry in a single forward pass or update a recurrent state as frames arrive sequentially, making this expansion and refinement non-trivial. We introduce Solv3R, a looped transformer that learns to continue solving multi-view geometry from its current state. Importantly, its update operator is independent of the iteration count, allowing previously refined and newly introduced views to be jointly updated regardless of how ``solved'' they are. We train the operator to preserve accurate reconstructions under continued iteration and correct inaccurate states, enabling refinement of fixed image collections and integration of new observations. Representati

---

### [329] Can You Predict the Next Mind? Toward Multi-Turn Multi-Party Mental World Modeling

**链接**: https://arxiv.org/abs/2611.02988
**作者**: Jiahao Huang and Zheng Lian
**来源**: cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multimodal foundation models have achieved remarkable progress in physical world modeling, generation, and embodied reasoning, their capacity for dynamic mental world modeling remains underexplored. Existing benchmarks predominantly focus on static mental state perception or short-horizon decision-making, overlooking the dynamic mental trajectories inherent in multi-party, multi-turn interactions. To bridge this gap, we introduce M$^3$WME-Bench, a benchmark designed to evaluate mental world modeling conditioned on the evolving actions of interactants. Specifically, models are tasked with forecasting a target subject's future mental states and behaviors over extended social interactions. In addition to the benchmark suite, we construct M$^3$WME-23K, a dedicated training dataset, and establish a competitive baseline named MindNext-7B. Extensive evaluations across four representative paradigms (general MLLMs, emotion-specialized MLLMs, agentic frameworks, and World Foundation Models

---
