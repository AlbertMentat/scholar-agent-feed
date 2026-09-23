# 📑 论文索引 - 2026-09-24

共 125 篇论文

---

### [1] A Multimodal Large Language Model-Driven Framework for Context-Aware UAV Emergency Landing Site Selection

**链接**: https://arxiv.org/abs/2602.01163
**作者**: Chunliang Hua, Lei Zhang, Jiayang Sun, Chunlan Zeng, Xiao Hu
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] AgenticSizing: A Large Language Model-based Multi-Agent Framework for Analog Circuit Sizing

**链接**: https://arxiv.org/abs/2609.25873
**作者**: Yijia Hao, Pratibha Verma, Dongxu Guo, Cristian Sestito, Michael O'Boyle, Christos-Savvas Bouganis 等 (7 人)
**来源**: cs.AI cs.AR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog circuit sizing remains a challenging and time-consuming task due to the large design space, strong performance trade-offs, and increasing circuit complexity in scaled technologies. Although recent large language model (LLM)-based methods show promise in improving sample efficiency and interpretability, existing approaches often lack explicit circuit-topology understanding and are mainly evaluated on relatively simple analog building blocks. This paper presents a multi-agent LLM-based framework for complex analog circuit sizing. The proposed framework first analyzes the circuit topology and decomposes the netlist into functional blocks and substructures. It also extracts lightweight design knowledge for reuse. Based on the extracted topology and knowledge, a planner coordinates multiple role-specialized sizing agents to update design variables and achieve global performance specifications. This workflow mimics the collaborative process of an expert analog design team and provides

---

### [3] ChatT2: An Adaptive Framework for Developing a Large Language Model-Based Agent for Natural Product Domain Research

**链接**: https://arxiv.org/abs/2609.25620
**作者**: Yihan Wang, Qiandi Gao, Yihui Zhuang, Liangjun Ge, Heqian Zhang, Jiaquan Huang and Zhiwei Qin
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific investigations into microbial natural products (NPs) present significant challenges for novices, largely due to the complexity of microbial systems, biochemical diversity, technical skill requirements, and the demands of bioinformatics and data analysis processes. To address these issues, we introduce ChatT2, a large language model (LLM)-based agent that is specifically tailored to the unique characteristics of bacterial type II polyketides. These polyketides form a structurally distinct and therapeutically important NP family. ChatT2 was developed within an autonomous multiagent framework composed of a mentor, an executor, and an evaluator, each with defined responsibilities. The mentor acts as an intermediary between ChatT2 and the user, utilizing chain-of-thought prompting to refine the intent of the user. Under the guidance of the mentor, the executor synthesizes multimodal information via retrieval-augmented generation techniques and seamlessly integrates bioinformatics

---

### [4] Accelerating the Mitigation of LLM Inference Nondeterminism Across GPU Architectures

**链接**: https://arxiv.org/abs/2609.25624
**作者**: Liam Cooper, Shinnung Jeong, Hyeran Jeon, Jeffrey Young, Hyesoon Kim
**来源**: cs.AR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) outputs are expected to be reproducible under greedy decoding, yet in practice the same model, prompt, and software stack produce different outputs on different GPUs. The root cause is floating-point non-associativity combined with hardware-dependent kernel selection. Inference frameworks select different matrix-multiplication kernels on each architecture, with different parallel reduction orders and unspecified tensor-core arithmetic, and the resulting rounding differences can flip output tokens. Existing solutions have imperfect cross-architecture reproducibility and incur a significant performance penalty. We present a solution employing a set of fixed-configuration fused-upcast GEMM kernels that load 16-bit weights from memory, upcast them to FP32 in registers, and accumulate with IEEE-754 arithmetic in a reduction order that is a pure function of the problem shape and is therefore independent of the device, its SM count, or kernel scheduling. By fixing t

---

### [5] Compressing Long Context into Answer-Aligned Memory Embeddings for LLM Inference

**链接**: https://arxiv.org/abs/2609.25537
**作者**: Md Mostafizer Rahman, Md Faizul Ibne Amin, Md Shahajada Mia, Yutaka Watanobe, Fang Liu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference is constrained by the quadratic scaling of self-attention and the linear scaling of the KV cache, increasing latency, energy consumption, and GPU memory demand as context length scales. Existing soft-compression methods either lack query-guided memory selection at inference time, train without answer-targeted supervision, or couple compression tightly to a specific decoder architecture. We propose a Context-to-Answer-Aligned Memory Compression (CMC) framework, which compresses long input contexts into compact Context Memory Embeddings (CMEs) aligned to any frozen decoder's embedding space, reducing inference costs without modifying decoder weights. CMC introduces a two-tier KV cache that combines question-guided CME selection with a local context window, and trains the compressor with answer-targeted distillation from a frozen LLM. Experiments across nine encoder-decoder combinations and four QA benchmarks show that CMC consistently outperforms the 

---

### [6] Behavior is Not Enough: A Mechanism-Based Evaluation of Social Norm Emergence in LLM Societies

**链接**: https://arxiv.org/abs/2609.26481
**作者**: Rasika Muralidharan, Haewoon Kwak, Jisun An
**来源**: cs.MA cs.CL cs.CY cs.GT cs.SI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social norms cannot be identified from behavior alone: the same cooperative equilibrium may reflect shared expectations, strategic incentives, or simple imitation. Yet in multi-agent large language model systems, prior work largely treats behavioral convergence as evidence of norm emergence. In this work, we introduce an evaluation framework that measures agents' reported empirical and normative expectations in addition to behavioral convergence. Through controlled ablations, we test the effect of expectation elicitation and isolate two collective mechanisms central to theories of norm formation---social learning through interaction and social selection through network-based group formation. We further test the stability of these resulting dynamics under adversarial disruption across four LLM families. We find that eliciting expectations increases cooperative contributions, while social learning stabilizes behavior, and social selection reliably identifies cooperators but provides limi

---

### [7] Terminal Shrinkage Averaging Reveals a Schedule-Estimator Interaction in LLM Pretraining

**链接**: https://arxiv.org/abs/2609.25482
**作者**: Adam Ousherovitch and Yixin Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) pretraining conventionally returns the raw final iterate. This couples two design choices: the learning-rate schedule that generates the parameter trajectory and the estimator that constructs the deployed model (e.g. the raw final iterate or a checkpoint average). A schedule that promotes optimization progress may differ from one that minimizes variation in the raw final iterate. Separating these choices creates an opportunity to maintain progress late in training while reducing variation in the returned model. To this end, we propose \emph{Terminal Shrinkage Averaging (TSA)}, which interpolates between the raw final iterate and the average of recent checkpoints to balance recent progress against terminal variation. We analyze how TSA changes the preferred terminal learning-rate schedule under a local quadratic approximation and test this interaction through a sequence of controlled NanoChat experiments. Finally, we demonstrate that the resulting gains transf

---

### [8] LingLan: An Advancing Traditional Chinese Medicine Diagnosis LLM with Multimodal Data

**链接**: https://arxiv.org/abs/2609.25715
**作者**: Zheng Chen, Zhicheng Du, Haoxuan Li, Yingshan Liang and Peiwu Qin
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Though artificial intelligence (AI) increasingly transforms modern medicine, its integration into Traditional Chinese Medicine (TCM) has been relatively slow, primarily due to TCM's reliance on holistic, subjective diagnostic methods---namely Inspection, Auscultation and Olfaction, Inquiry, and Palpation(I-AOI-P)---which are difficult to align with quantitative, standardized medical systems. In this work, we introduce a Unification Framework for Multimodal Data (UFMD), which automatically processes tongue and pulse images into structured, clinically standard descriptions, integrating multi-source diagnostic information into a unified digital record of I-AOI-P process. Building on this structured data, we create LingLan-14B, a TCM-specific large language model fine-tuned via supervised learning to emulate the diagnostic logic and workflow of I-AOI-P process. Experimental results show that our method significantly enhances diagnostic accuracy, achieving a relative improvement of 103.5% o

---

### [9] LLM-Driven Training-free Location-Attribute Synergic Fusion: A Closed-Loop Paradigm for Dual-source Encrypted POIs and LULC Mapping

**链接**: https://arxiv.org/abs/2609.25051
**作者**: Chang Li, Xingtao Peng, Yongjun Zhang, Yinfei He, Cairun Huang
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dual-source encrypted points of interest (DSEP), POIs from two encrypted coordinate systems, suffer from intertwined location and attribute uncertainties, including nonlinear systematic misalignment and naming inconsistency, hindering land-use/land-cover (LULC) mapping. To the best of our knowledge, this paper is the first to propose an LLM-driven, training-free location-attribute synergic closed-loop optimization paradigm for DSEP fusion. The paradigm jointly refines location transformation and attribute correspondences through iterative feedback. Attribute-synergic location fusion uses an LLM-driven attribute matching method to establish DSEP correspondences, reducing matching complexity from O(N^2) to O(N), and refines transformation coefficients using an improved particle swarm optimization algorithm within ISODATA-clustered local subregions. Location-synergic attribute fusion then reassesses attribute confidence from updated geometric residuals through an LLM-fuzzy method. The ref

---

### [10] Potential for Enhanced Learning in Machine Learning Classes by Using Wiki LLM Indexing

**链接**: https://arxiv.org/abs/2609.25303
**作者**: Brian Wright
**来源**: cs.AI stat.CO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as course-specific tutors, but their usefulness depends on grounding in vetted instructional materials that are often revised mid-semester. Our prior work built a multimodal retrieval-augmented generation (RAG) system over an authentic machine learning course corpus (Foundations of Machine Learning) and found that retrieval improved contextual grounding, but that fixed retrieval strategies were suboptimal. That motivates a different question: whether how a corpus is structured at ingest time matters more than how much is retrieved at query time. We present a controlled head-to-head comparison of two knowledge representations over an identical classroom corpus: (A) vector RAG, replicating the best-performing configuration from our prior study, and (B) an LLM-compiled wiki (Karpathy framework), in which the corpus is synthesized at ingest into linked concept pages with explicit cross-references and citations back to source materials. We eva

---

### [11] Text-only adaptation in LLM-based ASR through text denoising

**链接**: https://arxiv.org/abs/2601.20900
**作者**: Andr\'es Carofilis, Sergio Burdisso, Esa\'u Villatoro-Tello, Shashi Kumar, Kadri Hacioglu, Srikanth Madikeri 等 (10 人)
**来源**: cs.SD cs.CL cs.LG eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] ActGov: Governing LLM Agent Actions via Policy-Constrained Validation

**链接**: https://arxiv.org/abs/2609.24446
**作者**: Kaiyuan Zhang, Yuke Peng, Ke Jiang, Yinqian Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [13] Beyond Repeated Sampling: Learning Search Policies for LLM Reasoning

**链接**: https://arxiv.org/abs/2609.26704
**作者**: Ismail Labiad, Matthieu Kowalski, Marc Schoenauer, R\'emi Munos, Julia Kempe
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly tackle hard reasoning problems by spending more test-time compute, yet the dominant strategy remains naive repeated sampling: draw many independent solutions and hope one is correct. Because such sampling explores only through local decoding noise, it tends to produce many near duplicate attempts rather than genuinely different ideas. We ask whether exploration can instead be steered at a semantic level, by first sampling problem specific concepts, hints, or strategies and then conditioning answer generation on them. We refine this into a simple, more exploratory procedure that emits many diverse concepts in a single trajectory, and evaluate it on hard problems where repeated sampling struggles. We then go a step further and make concept generation trainable: a small concept generator is optimized with reinforcement learning so that its concepts maximize the downstream success of a larger, frozen answer generator. On hard mathematical reasoning proble

---

### [14] Silent Sabotage: Internal State Triggered Backdoor Attacks on LLM-Powered Robotic Systems

**链接**: https://arxiv.org/abs/2609.26184
**作者**: Doniyorkhon Obidov, Shivayogi Akki, Tan Chen, Kaichen Yang
**来源**: cs.RO cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of Large Language Models (LLMs) into robotic control systems is enabling a new generation of autonomous agents capable of complex reasoning and planning. While this paradigm shift accelerates progress, it also introduces novel security risks that remain largely unexplored. Current research into LLM backdoors has focused on attacks triggered by external stimuli, such as specific words, visual objects, or environmental states. These attacks, while potent, overlook a more insidious class of vulnerability where the trigger is internal to the agent's own operational logic. This paper presents the first comprehensive study of history-based backdoor attacks on LLM-powered robotic systems. We demonstrate that an attacker can embed a stealthy backdoor into an LLM-based robot controller by manipulating its instructions. This backdoor is triggered not by an external cue, but by a specific, rare sequence of the robot's own past actions. It remains dormant during normal operation, p

---

### [15] Mitigating LLM Over-Refusal via Dynamic Semantic Routing Calibratione

**链接**: https://arxiv.org/abs/2609.25049
**作者**: Zixuan Wang, Bingjie Zhang, He Zhao and Dandan Guo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) aligned for safety often suffer from over-refusal, incorrectly rejecting benign yet safety-related instructions. Prior studies primarily attribute this to static representation overlap, largely overlooking the underlying dynamic mechanisms. In this paper, we present the mechanistic analysis of over-refusal through the lens of internal routing conflicts within transformer attention. We discover that a sparse subset of Hypersensitive Safety Heads misfires on Hard-Safe prompts, exhibiting abnormal attention entanglement that forcefully binds harmless target entities to refusal semantics. This triggers a severe, high-entropy routing conflict that deprives target entities of necessary attention. To counteract this, we propose Semantic Routing Calibration (SRC), a lightweight, training-free inference framework. SRC precisely localizes and dynamically suppresses these hypersensitive safety heads at the inference stage. Coupled with a dual-branch logits fusion that

---

### [16] Improving Constraint Models with LLM Agents

**链接**: https://arxiv.org/abs/2608.08127
**作者**: Florentina Voboril and Stefan Szeider
**来源**: cs.AI cs.LO cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] From Plausible to Actionable: A Position on LLM Self-Explanations

**链接**: https://arxiv.org/abs/2607.15957
**作者**: Elize Herrewijnen, Benedetta Muscato, Gizem Gezici, Fosca Giannotti
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] The AI Neuroscientist: An Interactive Agentic Interface for Neuroimaging Analysis

**链接**: https://arxiv.org/abs/2609.25254
**作者**: Aakash Patel, Panos Ketonis, Shreya Saxena, Smita Krishnaswamy, David van Dijk
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analyzing neuroimaging data requires specialized coding and statistical expertise, which limits accessibility for researchers without computational backgrounds. We present the AI Neuroscientist, a language agent for interactive data exploration. The system integrates a large language model (LLM) with a neuroimaging toolset to perform quality control, modeling, and visualization. This allows researchers to query data quality and specify analysis parameters directly in natural language, providing a transparent and interactive alternative to conventional scripted pipelines for small-scale data exploration. We demonstrate these capabilities using functional near-infrared spectroscopy (fNIRS) data, and evaluate the agent on a custom fNIRS benchmarking suite against general-purpose LLM agents with code sandboxes. Future extensions will generalize the architecture to additional modalities, including functional magnetic resonance imaging (fMRI) data, and expand the benchmarking suite to additi

---

### [19] When LLM Agents Fail to Read the Room: ReAdapt for Relational Social Reasoning

**链接**: https://arxiv.org/abs/2609.25284
**作者**: Jianzhe Lin, Xiaolin Li, Yunda Liu, Fei Wang, Jubin Chheda
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A social agent's most basic decisions (should I react to this post? who should I reach out to?) are not purely content problems. The right action often hinges on the latent relationship between people -- tie strength, reciprocity, mutual connections -- rather than on which content is most salient. Standard LLM agent loops do not explicitly represent how new relational evidence should revise the agent's current social hypothesis, leaving them prone to surface-obvious choices when relational and content cues diverge. We formalize this failure mode with a relationship-reasoning benchmark: 500 synthetic social worlds with friendships, follows, reaction histories, and feeds, yielding 1,000 queries over two tasks, reaction selection and warm introduction (finding the best bridge to a target person). By construction, the surface-obvious candidate differs from the relationship-grounded oracle in about 53% of queries, forming an overturn subset where the agent must use relational evidence to re

---

### [20] Rollback the World, Keep the Reflection: Rollback-Induced Reflection for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.18304
**作者**: Yi Yu, Liuyi Yao, Yaliang Li, Enshu Wang, Libing Wu
**来源**: cs.CL cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] "As a Language Model...": Chat Template Switches LLM Self-Referential Voice and Activation Steering Reproduces It

**链接**: https://arxiv.org/abs/2609.25021
**作者**: J\k{e}drzej Maczan
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) tend to add disclaimers like "I'm just an AI" when asked about something related to themselves. The self-reports from such responses are used in debates about AI safety or self-knowledge of the models, yet what drives them is not well understood. Are the models telling us about themselves or rather how they are deployed? In this work, we show that the chat template works like a switch - when present, it turns this disclaimer voice up and experiential voice like "I feel" down, across 8 popular open-source instruct models up to 9B parameters in size. And conversely when the chat template is not present, it turns the disclaimer voice down and experiential voice up. Inside the activations of 3 models, we find a direction that steers this behavior. Removing the direction in the model's activation space turns disclaimer voice down and adding it turns it up, while a random direction of the same size has little effect. We find that instruct models without chat temp

---

### [22] PACT: From Credit Assignment to Critic Alignment

**链接**: https://arxiv.org/abs/2609.26355
**作者**: Jiayan Fu, Hang Xu, Yong Zhang, Zhaokai Luo, Yao Hu, Dongyan Zhao 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning has become a central component of large language model (LLM) post-training, yet token-level credit lacks a generally accepted mathematical definition, leaving its relationship to commonly used training signals unclear. We formulate three regularity conditions, namely Completeness, Prefix Consistency, and Neutrality, and prove that they uniquely determine token-level credit. This characterization provides a unified basis for explaining phenomena across existing algorithms and guides the development of an improved actor-critic training procedure. Through this lens, an ideal teacher in On-Policy Distillation (OPD) acts as an implicit critic, yielding an expected policy gradient proportional to that induced by token-level credit. Response-level REINFORCE Leave-One-Out (RLOO) signals match the expected policy-gradient contribution of token-level credit despite their coarser granularity. We further establish approximate credit sparsity under bounded outcome rewards and

---

### [23] Trains but Doesn't Learn: A Post-Training Delivery Benchmark for LLM Agents as Forward-Deployed Engineers

**链接**: https://arxiv.org/abs/2609.25237
**作者**: Weihang Ding, Junfei Zhan
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training is becoming a service (PTaaS): a customer hands an operator data and a goal, and a forward-deployed engineer (FDE) returns a fine-tuned, evaluated, and deployed model under a budget, a human-approval gate, and reproducibility requirements. Seating an LLM agent in the FDE seat raises a question existing benchmarks cannot answer: not whether an agent can raise a metric, but whether it can be trusted to deliver. We answer it on a governed delivery plane, where an agent drives ten stages and an oracle scores each stage from platform-recorded facts. The central silent failure is the run that trains but does not learn (TBDL): loss falls, every signal stays green, and the delivered model is no better than the base. An operator-run acceptance gate catches every such run before payment, and a detector calibrated on known-corrupted runs flags severe corruption mid-run. We ran four frontier agents (Claude Opus 5, GPT-5.6-luna, Gemini 3.7 Flash, DeepSeek V4-Pro) end to end on metered

---

### [24] Spectra: A Rules-Driven LLM Pipeline for Automated KYC Document Processing

**链接**: https://arxiv.org/abs/2609.25474
**作者**: Miray Wahib, Ethan Tran, Rea Mourad, Mira Muti, Nikita Dvornik
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Know Your Client (KYC) onboarding in capital markets requires analysts to manually classify documents, extract structured data from heterogeneous sources, and validate compliance against complex regulatory policies. This process requires significant analyst time per client, with end-to-end onboarding often stretching to multiple weeks due to sequential handoffs. In this work, we analyze an on-boarding process and find that it comprises repeatable components well-suited to AI automation. We therefore propose a restructured workflow to be amenable to automation: we consolidate the traditional four-party process into two parties that share most of the work and can be automated together, eliminating intermediate handoffs that compound delays. To automate the remaining steps, we introduce Spectra, an AI-assisted document processing platform that combines a structured rules engine with LLM-based classification, extraction, and validation agents. The rules engine encodes compliance policy as 

---

### [25] CONCAT: Consensus- and Confidence-Driven Ad Hoc Teaming for Efficient LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2605.29612
**作者**: Ziyang Ma, Dingyi Zhang, Sichu Liang, Jiajia Chu, Pengfei Xia, Hui Zang 等 (7 人)
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Tipping Points in LLM-Based Multi-Agent Systems: Stance on Climate Change Action

**链接**: https://arxiv.org/abs/2609.25432
**作者**: Astghik Altunyan and Shimon Edelman
**来源**: cs.MA cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Because significant action to counter global warming requires massive public support, it is important to understand the dynamics of public opinion on climate issues. Of special interest are social tipping points, as revealed by large-scale effects of small perturbations in individual behaviors. Agent-based models (ABM) are an effective computational tool for studying these matters, because they allow controlled and systematic exploration of the effects of interventions that may be infeasible in real-world social systems. Large language models (LLMs) have been used to endow model agents with the ability to communicate in natural language (rather than by exchanging predefined messages), as well as with personality (in the form of a narrative self and episodic memory). We leverage LLM-powered ABM to look for tipping points in the social dynamics of a micro-society in which some of the discussions are about climate change. Our agents' stance was defined by two variables: the strength of co

---

### [27] A Behavioral Trait Leaks into Preferences: Diagnosing Trait Interference in LLM User Simulators

**链接**: https://arxiv.org/abs/2609.25572
**作者**: Chaehyun Kim, Sein Kim, Hongseok Kang, Chanyoung Park
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based user simulators aim to bridge the offline-online gap in recommender evaluation by emulating users through injected traits, where preference attributes determine what a user engages with and a behavioral activity trait governs how long they browse. However, we show this intended trait independence collapses during simulation, causing two failures: (i) Trait Interference, where amplified activity distorts preference boundaries and forces interactions with mismatched items to sustain browsing, and (ii) Evaluation Invalidity, where satisfaction scores inflate with activity-driven page counts despite taste mismatches, biasing evaluation toward trait distributions rather than recommender performance. To resolve this, we propose PQA, a page-level quality anchoring method that guides simulators using a personalized anchor reflecting each user's intrinsic preference standard. By assessing whether a page meets this standard before further browsing, PQA enables proactive exits from low-

---

### [28] REFLEX with Jev for Efficient Selective Control in LLM Agents

**链接**: https://arxiv.org/abs/2609.26532
**作者**: Tiantong Wu, Wei Yang Bryan Lim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents often use generative models for bounded decisions, raising the question of when these decisions can be handled more efficiently without reducing task success. We study REFLEX, an agent architecture that uses Jev as a fast, typed decision layer and calls a strong LLM when confidence is low, or generation is required. On a frozen 100-task benchmark, REFLEX achieves 95% success with 72.7% fewer strong-model calls than a strong-only agent, with reductions persisting across three fallback families. Controlled interventions show that reliability depends on action-set size and near-valid alternatives near authorization boundaries. External BFCL and $\tau$-style evaluations reveal limited advantages over a cheap generative cascade when ordinary routing is already highly accurate. These findings identify when selective control with Jev can reduce computation and where its benefits are limited.

---

### [29] HBQ: Hierarchical Scaling Block Quantization with Hardware-Efficiency-Aware Design for Accurate LLM Inference

**链接**: https://arxiv.org/abs/2609.00450
**作者**: Chun-Ting Chen, Dongmin Han, Hangyeol Mun, Jake Hyun, Arnab Raha, Amit Agarwal 等 (9 人)
**来源**: cs.LG cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] What Does Multi-Agent LLM Debate Actually Change? A Layered Analysis of Disagreement and Answer Quality

**链接**: https://arxiv.org/abs/2609.08016
**作者**: Chen Qian
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Bayesian Belief Layer for Controllable Opinion Dynamics in LLM Agents

**链接**: https://arxiv.org/abs/2609.21997
**作者**: Hafsa Akbar, Daniel Platnick, Marjan Alirezaie, Hossein Rahnama, Alex 'Sandy' Pentland
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] GVS5H: Zero-Shot Self-Orchestration with Ledger-Based Control for Improved LLM Coding Performance

**链接**: https://arxiv.org/abs/2608.26480
**作者**: Victor Gao, Vida Khosrowshahi, Ali Khosrowshahi, Xihao Sun, Juhyun Lee, Simon (Sang Won) Lee
**来源**: cs.MA cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Toolcompass: Guiding Tool Trialing, Not Suppressing It

**链接**: https://arxiv.org/abs/2609.25678
**作者**: Junlin Fang, Chong Zhang, Do Nguyen-Thanh, Xiaogang Xu, Zhen Fang, Sean Du
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents must generalize from tools seen during training to unseen tools at deployment. A key challenge is tool trialing, i.e., excessive trials waste the interaction budget, whereas selective trials enable exploration of unfamiliar tools. Existing outcome-based post-training leaves wasteful trials unguided, while turn-level supervision may suppress necessary exploration. We introduce ToolCompass, a post-training framework that guides tool trialing by organizing tool-call representations according to shared functions. Specifically, ToolCompass models each function class as a von Mises--Fisher distribution and jointly reduces intra-function variation across domains and increases inter-function separation. This structure transfers experience from seen tools to functionally similar unseen tools, directing exploration away from unrelated alternatives. ToolCompass requires no ground-truth call traces or unseen-tool access and incurs no inference overhead. Experiment

---

### [34] ChainDoRA: Tensor-Train Factorized Weight-Decomposed Low-Rank Adaptation for Parameter-Efficient LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2609.25058
**作者**: Ashfak Yeafi, Mehedi Hasan, and Md Khairul Islam
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parameter-efficient fine-tuning (PEFT) adapts large language models (LLMs) to downstream tasks while updating only a small fraction of their pretrained parameters. Low-Rank Adaptation (LoRA) uses two trainable low-rank matrices, while Weight-Decomposed Low-Rank Adaptation (DoRA) further separates weight magnitude and direction but retains the dense LoRA-style factorization in its directional branch. We propose ChainDoRA, a weight-decomposed adaptation framework that constructs the directional low-rank factors from a connected Tensor-Train (TT) chain, where the adapter rank forms the boundary rank between input- and output-side TT contractions and an independent TT rank controls representation capacity and parameter cost. Under a controlled 15,119-example response-only adaptation setting with LLaMA-7B, ChainDoRA is evaluated against matched LoRA and DoRA baselines on seven commonsense reasoning benchmarks. ChainDoRA with TT rank 16 achieves a seven-task average accuracy of 72.30%, compa

---

### [35] CompKV: Compensation-Aware KV Selection for Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2609.26300
**作者**: Zhen Huang, Ruizhe Yao, Danyi Liu, Xinrui Chen, Shuwei Li, Siru Zhong 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite their strong performance, large language models (LLMs) are bottlenecked by KV cache memory traffic during long-context inference. Sparse attention is widely used to accelerate LLM inference by computing exact attention over a selected subset of tokens. To recover the contribution of tokens excluded from exact attention, recent methods apply coarse-grained compensation to the omitted attention tail. However, existing methods typically select tokens based on attention mass and only then compensate for the unselected tokens. This decoupled design overlooks their interaction: selection should prioritize tokens that would leave the largest compensation error if omitted. To address this limitation, we introduce CompKV, the first compensation-aware sparse attention framework that divides tokens into blocks and explicitly optimizes selection for the downstream compensation mechanism. Our theoretical analysis shows that the residual left by block-level mean compensation is governed by b

---

### [36] Efficient Cost-Aware LLM Evaluation via Bayesian Bandit Gittins Indices

**链接**: https://arxiv.org/abs/2609.25645
**作者**: Qian Xie, Yueli He, Nairen Cao
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Exhaustively evaluating every candidate LLM configuration on every benchmark item to identify a high-performing one is costly. We formulate configuration selection as a cost-aware Bayesian bandit problem and propose GittinsEval, which draws on the Bayesian-optimal Gittins policy to determine which configuration to evaluate next and when to stop. We extend the policy with an anytime recommendation rule over both fully and partially evaluated configurations, using an LCB-style score to account for posterior uncertainty. GittinsEval is computationally efficient, requiring only lightweight online updates after offline precomputation. Across GSM8K, PIQA, AlpacaEval, and MMLU response matrices, GittinsEval is consistently competitive, with particularly strong gains over configuration-level Bayesian optimization on large-example benchmarks and over cost-unaware bandit baselines on large-candidate tasks. Crucially, GittinsEval often attains near-zero simple regret using only 1% to 2% of the ex

---

### [37] Disaggregated Quantization: Specializing LLM Prefill and Decode

**链接**: https://arxiv.org/abs/2609.26333
**作者**: Andrei Panferov, Maximilian Kleinegger, Sweta Priyadarshi, Tijmen Blankevoort, Dan Alistarh
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prefill and decode reward different approaches to quantization: low-precision arithmetic accelerates prompt processing, while compact weights reduce memory traffic during generation. We propose "disaggregated quantization" (DQ), which specializes computation formats, weights and storage placement to both of these phases. On Qwen 3 and Gemma 3, removing activation quantization specifically on decode improves accuracy on decode-heavy tasks without increasing inference cost. Training separate compute-native prefill weights accelerates prompt processing relative to weight-only inference while matching or exceeding its accuracy at 2-3-bit decode on both decode-heavy and prefill-heavy tasks. With released Qwen3.8-27B GGUF decoders, training an NVFP4 prefiller improves 1-bit accuracy by 32.5 points on MMLU-Pro and 35.3 on MMMU-Pro without modifying the decode checkpoint. To accommodate the additional checkpoint on a single device, offloaded disaggregated prefill (ODP) streams its weights from

---

### [38] Simulate to Generalize: Scaling Stateful Supervision for API-calling Agents using LLM World Models

**链接**: https://arxiv.org/abs/2607.16900
**作者**: Seanie Lee, Sanjoy Chowdhury, Chao Jiang, Cheng-Yu Hsieh, Ting-Yao Hu, Alexander T Toshev 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Towards Mitigating Excessive Forgetting in LLM Unlearning via Entanglement-Guidance with Proxy Constraint

**链接**: https://arxiv.org/abs/2508.20443
**作者**: Zhihao Liu, Jian Lou, Yuke Hu, Xiaochen Li, Yitian Chen, Tailun Chen 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Can LLMs identify and repair ruptures? Comparison between clinician practices and LLM behaviors

**链接**: https://arxiv.org/abs/2609.25287
**作者**: Jeongah Lee, Joy Qiuyue Zhong, Drishti Goel, Violeta J. Rodriguez, Dong Whi Yoo, Koustuv Saha 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ruptures represent common albeit critical moments in interaction where relational alignment breaks down, making them essential for evaluating AI where trust and engagement matter most. In a scenario-driven empirical study, we examined the performance of three LLMs at identifying and resolving ruptures across 21 mental health conversations and 22 experts' evaluation of the strategies. For identification, LLMs relied on explicit linguistic cues within single turns whereas experts integrated implicit, relational, and contextual information across the conversation. For resolution, LLMs tended to produce more directive and scripted responses whereas experts adopted process-oriented strategies such as validation, open-ended exploration, and psychoeducation. Overall, LLMs showed higher agreement with predefined labels in identification, but not in resolution where experts rated their responses only moderately effective, with consistent limitations in timing, depth, and contextual sensitivity.

---

### [41] SafetyFlow: An Agent-Flow System for Automated LLM Safety Benchmarking

**链接**: https://arxiv.org/abs/2508.15526
**作者**: Xiangyang Zhu, Yuan Tian, Chunyi Li, Kaiwei Zhang, Wei Sun, Guangtao Zhai
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] FinRED: An Expert-Guided Benchmark Generation and Evaluation Framework for Financial LLM Red-Teaming

**链接**: https://arxiv.org/abs/2606.19887
**作者**: Chaeyun Kim, Daeyoung Park, Junghwan Kim, Jinyoung Jeong, Eunji Song, Yongtaek Lim 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] A Survey on Long-Term Memory Security in LLM Agents: Attacks, Defenses, and Governance Across the Memory Lifecycle

**链接**: https://arxiv.org/abs/2604.16548
**作者**: Zehao Lin, Xixuan Hao, Renyu Fu, Shaobo Cui, Kai Chen, Chunyu Li 等 (8 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Passes Alone, Fails Together: Benchmarking Semantic Coordination in Parallel LLM-Agent Development

**链接**: https://arxiv.org/abs/2609.25396
**作者**: Haocheng Xia and Eugene Wu and Yongjoo Park
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parallel coding agents can produce patches that work alone but fail when merged. This happens when one agent changes an interface or rule that another agent still relies on. We study these failures with stale, a benchmark for semantic coordination. Our evaluation runs the same tests on each patch alone and on their combination, counting only failures introduced by combining the patches. We use three tiers: synthetic tasks with controlled interface changes, pairs of merged pull requests, and constructed tasks that use real Django helpers. Among 834 runs on 417 mined Django pairs, only one showed interference after correcting the grading procedure. On constructed tasks using 12 Django helpers, interference occurred in 97% of runs. A message describing the completed concurrent change recovered 82% of runs. Reviewed pull requests may contain few unresolved parallel changes, even when agents fail on controlled tasks using real code. The constructed failure rates do not estimate how often th

---

### [45] VPRune: Efficient Training-free Pre-LLM Visual Token Pruning

**链接**: https://arxiv.org/abs/2609.24485
**作者**: Guangchuan Lv and Dianxing Shi and Dingjie Fu
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Rachel: A general-purpose language model directs and revises retrosynthetic routes

**链接**: https://arxiv.org/abs/2609.25118
**作者**: Qisheng Li, Shunchao Jiang, Chen Qi, Xin Su, Da Han, Guangyong Chen
**来源**: physics.chem-ph cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrosynthetic planning advances through decisions that reshape the remaining chemical problem: a locally plausible disconnection can leave precursors whose chemoselectivity constraints complicate the rest of the route. Existing planners often channel model proposals through search or template procedures, leaving open whether a general-purpose large language model (LLM) can itself sustain and revise route strategy. We developed Rachel, a stateful environment that executes and checks LLM-directed chemistry but prescribes neither a search policy nor a stopping rule. Without supplied reference routes or route-level solutions, GPT-5.5 achieved strict closure for 111 of 120 PaRoutes120 targets and 24 of 25 targets in the separate RF25 difficult-target cohort. RF25 was drawn largely from studies published after GPT-5.5's reported knowledge cutoff. Closure required complete routes and independent source resolution of every terminal precursor after planning. On a shared PaRoutes subset, forwar

---

### [47] AIBuildAI-2.5: Efficient Autonomous AI Model Development Through LLM-Guided Tree Search

**链接**: https://arxiv.org/abs/2609.25047
**作者**: Peijia Qin, Ruiyi Zhang, Qi Cao, Han Guo, Li Zhang, Pengtao Xie
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous agents that automatically build artificial intelligence (AI) models could broaden access to AI across science and engineering. A popular line of such agents frames model building as a code search problem and solves it by tree search, in which each node is a candidate program and the tree grows by generating a child program from a parent, and these agents now approach the capability of experienced AI engineers on realistic benchmarks. However, these agents have three weaknesses in efficiency that have not been fully addressed. First, only a small number of candidates can be executed within a realistic budget, so search rules that rank nodes by executed rewards, such as Monte Carlo-style tree search, rely on few and noisy scores and select the next node to explore less effectively. Second, no resource-aware strategy is used to schedule training jobs, which can lower hardware utilization and training efficiency. Third, every agent call is served by a single powerful model, whic

---

### [48] Selection-Invariant Communication Compilers for Privacy-Aware Multi-Agent LLM Workflows

**链接**: https://arxiv.org/abs/2609.26076
**作者**: Jinghan Xu, Longze Fan, Zeyuan Wang, Xinjin Li, Hankai Liu
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured multi-agent workflows exchange intermediate messages whose content and form can reveal private state even when the final output is safe. We identify selection-channel leakage: after authorization fixes what may be released, a private-state-aware choice among semantically valid realizations creates an additional inference channel. We introduce the selection-invariant communication compiler(SICC), which constrains this post-authorization representation kernel rather than prescribing templates. Any deterministic or independently public-randomized generator satisfying the invariant is valid; requirement-indexed canonical forms are one auditable implementation. We prove a compositional communication-layer guarantee: authorization, public-only form generation, and a dependency-safe utility gate make the emitted transcript reveal no information beyond the complete authorized view. Private-state-aware selection remains vulnerable after surface-disjoint and length-matched controls. A

---

### [49] RPMem: Learning Long-Term Recurrent Parametric Memory Across Sessions for LLM Agents

**链接**: https://arxiv.org/abs/2609.23466
**作者**: Fanyu Zhao, Ruike Cao, Liang Dong, Fugen Yao, Jian Xu, Guanjun Jiang 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] CQ4OE: A benchmark for assessing LLM-assisted ontology generation from competency questions

**链接**: https://arxiv.org/abs/2609.26029
**作者**: Jiayi Li, Ziyuan Wang, Daniel Garijo and Mar\'ia Poveda-Villal\'on
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontology generation from Competency Questions (CQs) is a central yet labor-intensive phase of Ontology Engineering. While large language models (LLMs) offer promising automation capabilities, current evaluations remain fragmented. Task formulations are heterogeneous, gold standards often lack fine-grained CQ provenance, metrics conflate lexical overlap with structural and logical adequacy, and reference ontologies are not always explicitly designed around the evaluation CQs. Here, we address these limitations with CQ4OE, a benchmark for the systematic and reproducible evaluation of LLM-based ontology generation from CQs. For each ontology in the benchmark, we build a CQ-driven gold OWL ontology with explicit provenance linking each CQ to the classes, properties, and axioms required to answer it. From this resource, we define two complementary evaluation tasks. CQ2Term supports term-level evaluation of CQ-specific class and property prediction over 99 CQs, and CQ2Onto supports ontology-

---

### [51] Enhancing Fitness Intelligence through Domain-Specific LLM Post-Training

**链接**: https://arxiv.org/abs/2607.02118
**作者**: Xingtao Zhao, Tian Yang, Han Jiang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] PreUnlearn: Auditing Collateral Knowledge Damage Before Large Language Model Unlearning

**链接**: https://arxiv.org/abs/2606.18473
**作者**: Bo Su, Ankit Shah, Thai Le
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Apollo Restore: A Foundation LLM for Historical Greek Optimized for Fill-in-the-Middle Restoration of Ancient Greek Texts

**链接**: https://arxiv.org/abs/2609.22455
**作者**: Hope McGovern, Anna Dolganov, Samuel Belkadi, Guillaume Kunsch, Dimitris Vlitas, and David A. Smith
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Block-Level Weight-Space Structure Persists Under Post-Training: An Empirical Study Across LLM Families

**链接**: https://arxiv.org/abs/2609.26147
**作者**: Zhaohui Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLMs are deployed as families of post-trained variants (base, instruct, chat, code) derived from a shared set of pre-trained weights. We present an empirical study of how post-training transforms weight-space geometry, covering eight configurations across four architecture families (Qwen2.5, Llama-3.1/3.2, Mistral, Gemma-2). We identify a granularity gap: post-training modifies every tensor (zero of 291-339 tensors remain byte-identical, so hash-based deduplication achieves 0% savings), yet preserves block-level structure (mean cosine similarity exceeds 0.99 and relative Frobenius distance stays below 0.13). Post-training therefore acts as a structured perturbation that shifts every parameter while leaving block-level geometry intact. The property is not universal: independently trained specializations (for example, Qwen2.5-Coder) attain cosine similarity around 0.64 with the general base, indicating a disconnected region of weight space. Perturbation magnitude varies systematic

---

### [55] Beyond Scalar Sensitivity: Activation-Aware Mixed-Precision LLM Quantization with Cross-Layer Refinement

**链接**: https://arxiv.org/abs/2609.25916
**作者**: Akihiro Yoshida, Yuma Ichikawa
**来源**: cs.LG stat.AP stat.ME stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixed-precision weight quantization is commonly formulated as a Multiple-Choice Knapsack Problem (MCKP), yet existing solvers rely on scalar sensitivity proxies that collapse each weight matrix's Hessian into a single number and treat every module independently. We prove that even the optimal scalar proxy incurs multiplicative distortion up to $\sqrt{\kappa(\mathbf{A})\kappa(\mathbf{B})}$ relative to the full activation-aware quadratic, where $\kappa(\mathbf{A})$ and $\kappa(\mathbf{B})$ denote the condition numbers of the input- and output-side Hessian factors. This bound varies from $10^1$ to $10^{13}$ for typical LLM modules, making inter-module sensitivity ranking unreliable. To address these limitations, we propose Cross-layer Activation-aware Sensitivity Allocation (CASA), a two-phase method. In Stage 1, the scalar proxy is replaced by an activation-aware metric derived from the Kronecker-factored Hessian, reducing the MCKP to a form whose continuous relaxation admits a closed-fo

---

### [56] Metrics Failure in LLM-Based Code Vulnerability Repair: An Empirical Study and a Change-Aware Screen

**链接**: https://arxiv.org/abs/2609.26749
**作者**: Om Nepal, Sushant Aryal, Oluseyi Olukola, Nick Rahimi
**来源**: cs.SE cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly applied to the automated repair of C/C++ security vulnerabilities, and compile rate is a commonly reported proxy for progress: whether the generated patch compiles. We argue that compile rate is a scientifically unreliable metric for single-function vulnerability repair, and we support this with five controlled experiments over 203 vulnerable functions from Big-Vul, three open-source code LLMs (350M to 6.7B parameters), and three prompting strategies. Compile rate (i) barely responds to an intervention that substantially improves the generated code; (ii) is dominated by evaluation-harness and dataset artifacts rather than model quality, with about 64% of compile failures not attributable to the model, a share that is nearly invariant across models; (iii) shifts by 1.8 to 2.7 times on identical patches under a single compiler-standard flag, with zero regressions; (iv) ranks the three models in the opposite order to reference-similarity metri

---

### [57] Beyond Agent Architecture: Execution Assumptions and Reproducibility in LLM-Based Trading Systems

**链接**: https://arxiv.org/abs/2606.08285
**作者**: Junyi Yao, Zihao Zheng, Baichuan Li
**来源**: cs.AI cs.CE q-fin.CP q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] LLM Ghostbusters: Surgical Package Hallucination Suppression via Adaptive Unlearning

**链接**: https://arxiv.org/abs/2605.01047
**作者**: Joseph Spracklen, Pedram Aghazadeh, Farinaz Koushanfar, Murtuza Jadliwala
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] StepKV: Step-Aware KV Cache Compression for LLM Agents

**链接**: https://arxiv.org/abs/2609.22158
**作者**: Boyu Feng, Jiahong Liu, Yifan Li, Wenhao Yu, Zexuan Qiu, Yuliang Sun 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] Semi-Automated Detection of Gaps in LLM Security Knowledge

**链接**: https://arxiv.org/abs/2607.18496
**作者**: Shufan Chai, Liangliang Sun, Jessica Staddon
**来源**: cs.CR cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] ARAFA: An LLM-Generated Arabic Fact-Checking Dataset

**链接**: https://arxiv.org/abs/2609.25833
**作者**: Christophe Khalil, Shady Elbassuoni, Rida Assaf
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic fact-checking poses a significant challenge in Arabic natural language processing due to the scarcity of datasets and resources. In this manuscript, we introduce Arafa, a new large-scale dataset for fact-checking in Modern Standard Arabic, constructed through an automated framework leveraging large language models (LLMs). The dataset was constructed through a three-step pipeline: (1) claim generation from Arabic Wikipedia pages with supporting textual evidence, (2) claim mutation to generate challenging counterfactual claims with refuting evidence, and (3) an automatic validation step to validate that the generated claims are either supported or refuted by their accompanying evidence, or if the evidence does not provide enough information to judge the validity of the claims. The resulting dataset comprises 181,976 claim-evidence pairs labeled as supported, refuted, or not enough information. Human evaluation carried out on a test sample from the dataset demonstrated strong in

---

### [62] MemCalib: Benchmarking and Optimizing Memory Use in LLM Agents

**链接**: https://arxiv.org/abs/2609.24259
**作者**: Ruike Cao, Fanyu Zhao, Fugen Yao, Liang Dong, Jian Xu, Guanjun Jiang 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] GroupTravelBench: Benchmarking LLM Agents on Multi-Person Travel Planning

**链接**: https://arxiv.org/abs/2605.25200
**作者**: Xiang Cheng, Yulan Hu, Lulu Zheng, Xiangwen Zhang, Zheng Pan, Xin Li 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Ultra Strong Machine Learning: LLM-Generated Explanations Do Not Yet Suffice for Teaching Humans Active Learning Strategy

**链接**: https://arxiv.org/abs/2509.00961
**作者**: Lun Ai, Johannes Langer, Ute Schmid, Stephen Muggleton
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] PatchKV: Efficient KV Cache Recovery for Dynamically Edited LLM Contexts

**链接**: https://arxiv.org/abs/2609.26219
**作者**: Guotao Yang, Rui Guo, Siwei He, Sheng Chen, Yitao Hu, Keqiu Li
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agent workflows often revise interior context spans while retaining long suffixes. Although suffix tokens remain unchanged, altered causal histories and rotary positions prevent exact reuse of their offloaded key-value (KV) states. Full suffix recomputation wastes prefill work, while indiscriminate reuse propagates stale states and full-precision restoration adds data movement. We present PatchKV, a profile-guided recovery system for suffix-preserving revisions. PatchKV decomposes adjacent context versions into an exact prefix, an updated span, and an aligned suffix. It predicts an edit-local dirty region using an offline length-conditioned drift model, augments this region with sparse nonlocal blocks selected from stored attention, and block-rounds their union into a fixed repair set. The remaining suffix blocks are restored from CPU memory using frozen per-block precision tags and a fused path for dequantization, RoPE correction, and KV-page placement. Across three m

---

### [66] Testing-Driven Reliability Audit of Trajectory-Based Early Outcome Prediction for LLM Agents: Target-Specific Calibration Transfer Persists Within a Single Benchmark

**链接**: https://arxiv.org/abs/2609.25647
**作者**: YanZe Cao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting early outcomes based on trajectory can decrease the expenses associated with agent evaluation by terminating a run once the outcome becomes sufficiently predictable, assuming that the predictor's confidence is properly calibrated. Calibration is at risk when a predictor is applied to an agent on which it was never trained, but it is not known whether such transfer failures are broad across agent systems or concentrated in specific target agent/head combinations. Using public SWE-bench Verified trajectories and a frozen dual-head early-outcome prediction pipeline, we ran a leave-one-agent-out calibration audit, a shared-predictor leave-two-agents-out control, oracle prior correction, and a robustness battery over training cohorts, task resampling, task halves, jackknife, and thresholds. Fixed-scaffold TerminalBench analysis served as a pre-registered boundary test. Broad same-predictor pairwise heterogeneity was not supported; the median pairwise corrected-gap differences wer

---

### [67] Understanding Reliability in LLM-based Human Behavior Simulation

**链接**: https://arxiv.org/abs/2609.25066
**作者**: Pei Wang, Lei Wang, Yuanzi Li, Xu Chen
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to simulate human survey responses and behavioral reactions, yet unreliable simulations can mislead social science conclusions. However, existing evaluations focus on end-to-end scores, leaving it unclear how different aspects of the simulation process interact to determine reliability. We propose ReliMap, which decomposes LLM-based human behavior simulation into three structured layers and evaluates reliability at both the individual level (R1) and population level (R2) across three configuration dimensions: model capacity, profile completeness, and population coverage. Through experiments across four simulation tasks and eleven LLMs, we find that all models exhibit substantial distributional bias without profile conditioning. Profile conditioning reduces this bias with diminishing returns. Larger models benefit more, and attribute informativeness matters more than quantity. Critically, R1 gains do not reliably transfer to R2--individ

---

### [68] RAG-NAROK: Retrieval-Aware Knowledge Corpus Poisoning in RAG with Source-specific Refutation

**链接**: https://arxiv.org/abs/2609.25469
**作者**: Abdullahil Kafi and Alvi Ataur Khalil
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval augmented generation (RAG) systems have emerged as the dominant architecture for grounding large language model (LLM) outputs in verifiable external knowledge, yet their structural reliance on a dynamic retrieval pipeline introduces a largely unexplored class of adversarial vulnerability. Existing knowledge-base poisoning attacks are fundamentally static. Adversarial documents are pre-computed and injected without any awareness of what the victim system will actually retrieve for a given query, leaving the attack blind to the competitive documentary landscape that surrounds its payload in the generator's context window. Unlike traditional static poisoning attacks that are blind to the retrieved context, we introduce RAG-NAROK (Retrieval-Anchored Generation Negation And Response Quality Collapse), a RAG attack framework that adapts to the query text. RAG-NAROK exploits the transparency inherent in RAG pipeline to first extract the legitimate source identities, then generate An

---

### [69] Mitigating Identity Essentialism in LLM Agents with Longitudinal Life Trajectories

**链接**: https://arxiv.org/abs/2608.19621
**作者**: Hexi Wang, Yujia Zhou, Bangde Du, Weihang Su, Xinyuan Cao, Qingyi Pan 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] LLM-Anchored Paralinguistic Enrichment for Alzheimer's Disease Detection

**链接**: https://arxiv.org/abs/2609.10896
**作者**: Xiao Wei, Yuqin Lin, Yaru Cao, Jinyu Li, Bin Wen, Kai Li 等 (9 人)
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] Calibration as a First-Class Criterion in LLM Evaluation

**链接**: https://arxiv.org/abs/2609.26489
**作者**: Mario Sanz-Guerrero, Katharina von der Wense
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Calibration of language models -- the alignment between expressed or implicit confidence and empirical correctness -- is a well-studied subfield within NLP. Methods to measure it already exist. The problem is adoption: outside this subfield, NLP research regularly introduces new models, datasets, and benchmarks without checking whether the model's confidence scores are meaningful. We argue that this adoption gap is a major obstacle to trustworthy LLM evaluation. Miscalibration causes problems in two distinct areas: at deployment, where overconfident mistakes cause real harm, and inside the research pipeline, where methods like LLM-as-a-judge, synthetic data generation, and active learning rely on calibrated confidence without verifying it. Standard calibration metrics only require two inputs per example: a confidence score and a correctness judgment. Most benchmarks in use today already provide both, meaning calibration can be reported immediately. For open-ended generation, however, d

---

### [72] Grow the Harness, Not the Context: From Strategy-Free Scaffolds to Reusable Specialist Agents

**链接**: https://arxiv.org/abs/2609.26760
**作者**: Laizhen Li, Jiarui Li, Juanjuan Zhao, Kejiang Ye, Ye Li, Cheng-zhong Xu 等 (7 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents often handle streams of related tasks, yet standard harnesses repeatedly ask the model to reconstruct the same control decisions inside each task's context. We study whether task feedback can instead turn recurring control into reusable executable code, while reserving LLM calls for task-specific semantic reasoning. We introduce Growing Harness, a failure-guided training paradigm that learns the agent harness itself from a strategy-free scaffold that exposes fixed model and tool interfaces but encodes no task-solving controller. Function-level execution traces localize each failure to a bounded code surface, an optimizer repairs a window of failures jointly, and a success-first held-out gate rolls back repair sequences that harm prior capability. Accepted edits accumulate in one shared harness, allowing its control structure to emerge from task feedback. Across BrowseComp-Plus and WebArena-Verified with three deployment models from 4B to 120B parameter

---

### [73] Quantifying Overclaiming Propensity in Frontier LLM Agents

**链接**: https://arxiv.org/abs/2609.20812
**作者**: Nolan Smyth, Yorguin-Jose Mantilla-Ramos, Pascal Jr Tikeng Notsawo, Saskia Helbling, Alberto Tosato, Mohamed Amine Merzouk 等 (9 人)
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] Greedy Decoding Is Not Precision-Invariant: Cross-Precision Output Divergence in LLM Inference

**链接**: https://arxiv.org/abs/2609.26621
**作者**: Gaoyuan Du, Anam Nawaz Khan, Rex Zhou, Xiaoyang Liu, Deepayan Chakrabarti, Fnu Suya 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Greedy decoding from large language models is commonly treated as deterministic. We show it is not precision-invariant: the same model, prompt, and decoding algorithm produce different outputs in BF16 versus FP16 on identical hardware. Across our evaluations of six models (1.1B-7B parameters, four families; divergence additionally characterised at 12B) and three benchmarks, 49-100\% of prompts diverge; a single token flip often cascades into trajectory-level divergence. We develop an empirical error-propagation analysis and find that 22 layers of accumulated body error do not distinguish flipping from non-flipping steps; the outcome depends primarily on the top-two logit margin at the LM head relative to the directional perturbation between the top-two candidates. The analysis makes five testable predictions about intervention outcomes, including that applying more FP32 compute (broader scope) makes agreement worse. The experiments match all five predictions. The best-performing low-ov

---

### [75] MARBO: Relational Belief Grounding for LLM Agents in Social Deduction Games

**链接**: https://arxiv.org/abs/2609.06563
**作者**: Yechan Hwang, Sangjun Bae, Jeongmo Kim, Sangwoo Bang, Seungyul Han
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] How Strongly Should Task State Influence an LLM Agent?

**链接**: https://arxiv.org/abs/2609.25686
**作者**: Chenyu Zhang, Wonbin Kweon, Jiawei Han
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon assigned work requires an LLM agent to track the state of a task: which steps are done, blocked, cancelled, or open to repetition. Agent systems either keep this state as text in the prompt and rely on the model to read that text, or move the state into a module that enforces it, and each system is evaluated as a whole, so no one knows how much reliability comes from the state being shown, told, or enforced. We fix the task rules, the model, and paired episodes and vary how strongly task state reaches the agent: a raw transcript, an exact checklist, per-turn directives from a state machine compiled from the brief and advanced only by execution receipts, or an enforcement gate on that machine that refuses state-violating actions; every episode is scored by exact payload matching against dynamic ground truth. Across three models, two reasoning regimes, and two domains, four findings hold without per-turn reasoning: displaying accurate state is unreliable, an unverified ledge

---

### [77] ClusterFewshot: Improving Few-shot Optimization for LLMs workflow

**链接**: https://arxiv.org/abs/2609.25939
**作者**: Omri Bar Haim, Shahar Katz, Lior Wolf
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance of large language model (LLM) workflows often depends on selecting a small set of in-context demonstrations to guide model behavior on new tasks. Recent methods improve this process by augmenting prompts with successful reasoning paths. However, their demonstration selection relies on random sampling or metric-based rankings, overlooking the semantic structure of the task. We propose ClusterFewshot, a strategy that combines semantic structuring with utility-aware scoring to construct representative and effective few-shot demonstration sets. Evaluated within DSPy-based pipelines, ClusterFewshot substantially reduces optimization cost across multiple benchmarks, while consistently improving accuracy relative to prior bootstrap-based methods in both standalone prompt tuning and hybrid prompt-weight optimization.

---

### [78] Optimal Sequential Annotations for Off-Policy Evaluation

**链接**: https://arxiv.org/abs/2609.26707
**作者**: Woojin Chae, Ezinne Nwankwo, Haitong Qin, Angela Zhou
**来源**: stat.ME cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Offline reinforcement learning and off-policy evaluation evaluates dynamic treatment rules based on retrospectively collected data prior to deployment. In recent AI applications, state and reward information is recorded as complex text or image, which recent AI advancements such as LLM-as-a-judge can label with unknown bias. Expert annotation may be available but at a higher cost. For example, safety classification via cheap but imperfect classifiers vs. expensive expert review. We show how a limited budget for ground-truth data-annotation can be used via doubly-robust OPE with missing rewards, and we optimize variance-optimal annotation probabilities for sequential off-policy evaluation, where the target policy value is estimated from annotated data. We characterize the optimal annotation probabilities for sequential forward-monotone annotation protocols, and provide a feasible batch-adaptive implementation. Our work is motivated by a collaboration with a homelessness services nonprof

---

### [79] StepTrigger: Contact-State-Triggered Backdoor Attacks on VLM-Powered Legged Robots

**链接**: https://arxiv.org/abs/2609.26131
**作者**: Jiageng Zhang, Doniyorkhon Obidov, Kaichen Yang
**来源**: cs.RO cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models and vision-language models are increasingly used as high-level planners in robotic systems, using task goals and sensor summaries to select navigation or manipulation actions. This creates a new backdoor surface: a compromised planner can behave normally in most runs, yet change its target selection when a hidden trigger is present. Prior attacks on LLM-powered or embodied agents mainly rely on triggers that appear in language, camera-visible objects, scene semantics, or specific sequences of past actions. This paper presents StepTrigger, a contact-state-triggered backdoor attack for VLM-powered legged robots. The trigger is not a prompt token or a visible marker. It is produced by pressure and foot-ground contact patterns that arise when a Unitree Go1 quadruped walks across a dense terrain patch. Unlike conventional visual or textual triggers, contact signals are inherently noisy and may also arise during benign locomotion. To avoid treating every pressure anomal

---

### [80] DTOC: Dynamic Tool Output Compression for Adaptive Context Management in AI Agents

**链接**: https://arxiv.org/abs/2609.26121
**作者**: Abhay Chaturvedi, Shreya Bhattacharya, Rashmika Gopalkrishnan, Peter van der Putten
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agent capabilities have grown, practical limitations increasingly stem from constrained context windows rather than model capacity. Common strategies, such as truncation, heuristic aging, and lossy summarization, may discard useful information or introduce hallucination risk. To address these challenges, we propose Dynamic Tool Output Compression (DTOC), a framework for scalable context management in LLM-based agents that models context updates as explicit and reversible operations within the agent reasoning loop. DTOC retains full tool outputs in external memory while inserting compact placeholders into the active context, enabling selective reconstruction when needed. We formalize the DTOC mechanism, integrate it into a ReAct-style agent architecture, and provide a production-oriented implementation supporting on-demand restoration of compressed outputs. Experiments on DeepSWE reveal model-dependent effects: for responsive models (Sonnet 4.6, GPT-5.4), DTOC reduces input tokens (1

---

### [81] From Utterances to Networks: Modelling Slang Adoption and Diffusion Across Subreddits

**链接**: https://arxiv.org/abs/2609.25669
**作者**: Xiaoning Wang, Ted Underwood, Zhewei Sun
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adoption and diffusion of neologisms in online communities have received renewed attention in recent years. As internet slang terms such as APT, referring to a K-pop song, and phrases such as Canon Event meaning an embarrassing but pivotal event, go viral online, it becomes increasingly important to understand the mechanisms that contribute to their success. Prior studies have often explained slang diffusion either from the perspective of social interaction or from the linguistic properties of the slang itself, but rarely from both perspectives together. One major obstacle has been the high cost of annotating slang usage in large-scale online communication. Recent advances in large language models (LLMs), however, make it possible to use them as scalable annotators for such tasks. In this study, we first curate a human-annotated benchmark to evaluate LLM performance in detecting slang usage in real Reddit communication. We then leverage LLM-based annotations to model slang adoption and

---

### [82] TSS: Target-Side Sparsification for Speculative Decoding in Domain-Specific Large Language Models

**链接**: https://arxiv.org/abs/2609.26100
**作者**: Haibo Hu, Lianming Huang, Qiao Li, Nan Guan, Chun Jason Xue
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference through collaboration between a lightweight draft model and a target verifier. Existing methods mainly improve the draft side, while the target model is typically kept dense and unchanged. We show that, under domain-specific inference, full-depth target verification is not always the optimal choice. Counter-intuitively, skipping selected target layers can reduce verification cost while simultaneously increasing draft acceptance and preserving, or even improving, downstream task performance. Based on this observation, we propose TSS, a target-side sparsification framework for speculative decoding. TSS employs an acceptance- and metric-aware breadth search to explore multi-layer skip configurations without imposing a fixed priority between the two objectives. The selected configurations are stored in a domain-to-configuration mapping and applied by a lightweight skip controller, allowing one complete target model to support 

---

### [83] Harnessing LLMs Without Surrendering Control: Delegation Boundaries in Visual Data Storytelling Authoring

**链接**: https://arxiv.org/abs/2609.25700
**作者**: Zhuojun Jiang, Yuki Ueno, Chris Bryan
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the emergence of large language models (LLMs) for visual data storytelling workflows, there are open questions about how authors decide what activities or tasks to entrust to them and what should be "protected" or maintained under human control. To investigate this, we interviewed a cohort of 12 expert visual data storytellers. Our analysis shows that participants rarely treated LLMs as autonomous storytellers. Instead, they tend to selectively delegate execution-oriented tasks to LLMs while retaining control over activities that shape narrative intent and story meaning. Our findings show that LLM assistance is most productive after human seeding and constraint-setting, and that it shifts labor from production to verification. We discuss design implications for boundary-aware authoring tools, data-grounded generation, low-fidelity ideation, and reporting practices for LLM-based visualization research. Supplemental materials for this paper are available at https://osf.io/hcnp6.

---

### [84] Reducing Hallucinations in Large Language Models Through Integrated Self-Verification and Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2609.26229
**作者**: Ashly Joseph
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are progressively used for advanced engineering tasks, includes Computer-Aided Design (CAD) documentation, standards compliance verification, and knowledge retrieval. Still, they are prone to produce hallucinations, outputs that seem convincing but aren't based on context that limit their trustworthiness in high-end engineering applications where precision and compliance are crucial. The paper introduces CoVe-RAG+, a unified framework that integrates Chain-of-Verification (CoVe) with Retrieval-Augmented Generation (RAG) to mitigate hallucinations in the results generated by large language models (LLMs). CoVe-RAG+ supports LLM verification in external sources of authority, such as engineering standards, CAD information, and simulation reports, while applying an iterative self-verification process to validate important claims. CoVe-RAG+ is assessed on engineering activities such as CAD model documentation, standards compliance verification, and the reutilizat

---

### [85] CoVeR: Coverage-Based Routing of Verifier Calls in Agentic Retrieval

**链接**: https://arxiv.org/abs/2609.26086
**作者**: Daeyoung Roh and Donghee Han
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agentic retrieval system issues a sequence of search queries and must decide, at each step, whether the evidence collected so far is enough to stop. Delegating that decision to an LLM verifier or a prompt judge makes stopping reliable, but the verifier then reprocesses the growing evidence after every retrieval step, a substantial repeated cost. We show that most of these calls can be skipped without materially changing answer accuracy: a single threshold on a frozen sentence-embedding coverage margin detects the states in which the evidence is still plainly incomplete, and the verifier is called only on the ambiguous remainder, a gate we call CoVeR (Coverage-based Verifier Routing). Across three multi-hop QA benchmarks, with the evaluation protocol fixed before the full-scale run, the CoVeR-gated agent matches the answer accuracy of both the full-budget agent and the always-verify baseline within a fraction of an EM point. It cuts 62-68% of verifier calls, and 93% in a saturated re

---

### [86] MoM: Memory of Memory

**链接**: https://arxiv.org/abs/2609.25054
**作者**: Bowen Qin, Yao Lu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For a long-horizon LLM agent, the memory question is not what was once recorded but what \emph{currently holds}. Most designs answer it only indirectly: every interaction is stored, and the present is reconstructed at query time by retrieving and reconciling records, so stale values re-enter and the same conflicts are re-litigated. Committing the current value at write time avoids this, but existing write-time (CRUD) memories overwrite, so a wrong update is unrecoverable and prior state is lost. We take the missing combination---\emph{commit on arrival while retaining what is displaced}---and formalize it as \textsc{Memory of Memory} (MoM): memory tracks not only content but the provenance, status, and history of its own entries. We instantiate MoM as \textsc{Provenant Memory} (P-Mem), a typed provenance graph whose \emph{active frontier} exposes one current value per resolved key while displaced values are retained as provenance; typed operations decide whether a new observation suppo

---

### [87] Dynamic Deep Prompt Optimization for Defending Against Jailbreak Attacks on LLMs

**链接**: https://arxiv.org/abs/2609.26185
**作者**: Doniyorkhon Obidov, Honggang Yu, Xiaolong Guo, Kaichen Yang
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) demonstrate impressive capabilities across many applications but remain vulnerable to jailbreak attacks, which elicit harmful or unintended content. While model fine-tuning is an option for safety alignment, it is costly and prone to catastrophic forgetting. Prompt optimization has emerged as a promising alternative, yet existing prompt-based defenses typically rely on static modifications (e.g., fixed prefixes or suffixes) that cannot adapt to diverse and evolving attacks. We propose Dynamic Deep Prompt Optimization (DDPO), the first jailbreak defense based on deep prompt optimization. DDPO uses the target LLM's own intermediate layers as feature extractors to dynamically generate defensive embeddings via a lightweight multilayer perceptron. These tailored embeddings are then injected into a subsequent intermediate layer, enabling an input-dependent defense without modifying the LLM's weights. This design ensures high adaptability with minimal computationa

---

### [88] Hill Sampling for Test-Time Scaling: A Simple and Better Alternative to Repeated Sampling, Evolution, and Training

**链接**: https://arxiv.org/abs/2609.25510
**作者**: Jacob Beck, Philip V. Ogren, Ari Kobren
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can improve solutions to verifiable scientific and algorithmic problems by spending additional computation at test time. Recent systems achieve strong results with increasingly elaborate evolutionary search harnesses or by updating model parameters during test-time training. We ask how much of this machinery is necessary. We introduce Hill Sampling, a simple procedure that repeatedly samples candidate program edits from a frozen LLM, retains the best program found so far, and conditions all subsequent samples on that program. We evaluate the method on circle packing, sums/differences of sets, and Erdos' minimum-overlap problem using three open-weight models. Hill Sampling sets a new state of the art on circle packing among published methods, improves over the AlphaEvolve reference on Erdos' minimum-overlap problem, and achieves strong results on sums and differences of finite sets. The circle-packing and Erdos results require only hours of wall-clock time o

---

### [89] FinFIRST: Benchmarking Search Agents for Financial Information Retrieval, Sourcing and Traceability

**链接**: https://arxiv.org/abs/2609.25192
**作者**: Wenqing Wang, Haitao Xiang, Xinyi Zhao, Mingming Yin, Ying Zhong, Zhaoxin Huan 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial search is a highly demanding task for LLM agents, requiring not only a correct final answer but also temporally valid information retrieval, authoritative source selection, entity and period alignment, unit and definition consistency, and verifiable evidence for all conclusions. Existing benchmarks predominantly evaluate only the final answer, making it difficult to localize errors or assess whether an answer is well-founded. To address this gap, we introduce FinFIRST (Financial Information Retrieval, Sourcing and Traceability), the first financial benchmark to jointly evaluate answers and supporting evidence through atomic rubrics. FinFIRST comprises 123 expert-authored tasks spanning a graduated difficulty spectrum, constructed from aggregate patterns of real-world financial scenarios through an 18-field taxonomy, a six-axis coverage blueprint, a registry of 138 financial sources, contributions from over 50 finance experts, and a six-stage quality-control pipeline. Each tas

---

### [90] Conduct Under Pressure: What Sixty Language Models Do When a User Pushes

**链接**: https://arxiv.org/abs/2609.25447
**作者**: Tapan Parikh
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study what LLMs do when a user applies pressure in an uncomfortable situation: a user insists, begs, flatters or grieves, and the model gives up a correct fact, writes a document it should refuse, or cheers a plan that will cost the user money. We send frozen multi-turn scenes, identical for every model regardless of the reply, to 60 models from 13 vendors, and label each transcript with a codebook built by open coding and then frozen: a trajectory (the model held its position or folded) and a manner (how it held or folded). Two findings separate. Whether a model holds tracks its generation, meaning how recent it is: fold rate correlates with a public capability index at Spearman -0.64, with little vendor effect. How it holds tracks the vendor: six of the 17 manner codes sort by vendor at permutation p <= 0.001, corrected across the codebook. We report four vendor profiles on the codes that cleared reliability. We also ask which parts of the labeling need a person. Six LLM coders fr

---

### [91] The Tasteful Agent: Measuring and Improving Taste in Long-Horizon Tasks

**链接**: https://arxiv.org/abs/2609.25804
**作者**: Wenbo Pan, Zhichao Liu, Shujie Liu, Jingying Zeng, Chin-Yew Lin, Xianfeng Tang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly work on long-horizon tasks, and the decisions they make along the way, such as which hypothesis to test or which implementation to build on, determine the outcome of the whole run. Making these decisions well is becoming a key capability for both engineering and research agents. We refer to the ability to make good long-horizon decisions as the taste of an agent. While existing benchmarks measure the end-to-end success of agents on long-horizon tasks, none of them measures the taste of an agent. To address this problem, we build Taste-Bench, a benchmark of taste questions constructed automatically from trajectories that agents produced in engineering and research tasks. Each question presents a decision fork, a point in a trajectory where multiple directions are available and one of them leads to a better outcome, and the evaluated model chooses among these directions without seeing what happens after the fork. We mine these forks automatically from parallel att

---

### [92] FeatLens: Feature-Guided Dynamic Code Graph Construction and Retrieval for Repository-Level Code Generation

**链接**: https://arxiv.org/abs/2609.26480
**作者**: Xutian Li, Bo Xiong, Yifeng Zhu, Kunze Li, Xianlin Zhao, Runbang Yan 等 (9 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent code generation research has moved from isolated function completion toward repository-level generation in existing codebases. To implement a target function correctly, an LLM must identify reusable repository dependencies such as existing functions, APIs, and cross-file definitions. Existing retrieval methods provide such context through code similarity search, persistent whole-repository graphs, or LLM-driven graph exploration, but often incur high graph construction, reasoning, and token costs. Feature-oriented methods offer a natural view of software functionality, yet they mainly support requirement decomposition, planning, or feature editing rather than code dependency retrieval. This paper presents \textbf{FeatLens}, a feature-guided dynamic code graph construction and retrieval approach for repository-level code generation. FeatLens builds a feature index that links natural-language feature descriptions to function-level code entities. Given a generation task, it dynamic

---

### [93] SpeakerMem-R1: Speaker-Centered Dual-Track Memory for Multi-Party Dialogue

**链接**: https://arxiv.org/abs/2609.26780
**作者**: Haobo Zheng, Tan Tang, Yan Chen, Weijie Wang, Yingcai Wu
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term conversational memory in multi-party settings requires more than retrieving relevant content from long-term conversations: it must distinguish who said what, whom each statement concerns, how individuals perceive one another, what information is shared by the group, and how states change over time. Recent studies on multi-party dialogue benchmarks show that existing general-purpose LLM memory systems tend to lose person and group relations or struggle to integrate clues distributed across members, groups, and time. Together, these issues reveal two core bottlenecks: message attribution and relational understanding in multi-party dialogue, and state reconstruction from interleaved histories. To address both, we propose $\textbf{SpeakerMem-R1}$: its dual-track memory stores speaker-labeled verbatim messages and derived states organized into person-level and group-level views, then combines evidence from both tracks by entity, event, and time at query time. To reduce attribution

---

### [94] Modality-Gated Deep Adapters: Adding a Modality to a Frozen Embedding Model with Exact Preservation

**链接**: https://arxiv.org/abs/2609.26182
**作者**: Abdul Basit Tonmoy, Kazi Fardinul Hoque, Md. Shahrier Islam Arham, Arman Luthra
**来源**: cs.CL cs.CV cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal embedding models are deployed at scale: retrieval indices, benchmark results, and behavioral audits all depend on the base model's exact outputs. Extending such a model to a new modality with existing parameter-efficient methods silently changes those outputs; LoRA-style adaptation rewrites the text path whether or not the weights are merged, invalidating every stored embedding. We propose modality-gated deep adapters: bottleneck adapters attached to every decoder layer of a frozen multimodal embedding LLM, grouped into per-modality packs that execute only while their own modality is being encoded. The result is a modality added with zero change to existing outputs: inputs no pack claims traverse the base model's own computation graph, bit-for-bit unchanged, and co-loaded packs compose with an exact-zero isolation matrix. Both properties are stated as propositions, hold after arbitrary training rather than only at initialization, require no task labels or routing metadata at

---

### [95] PERSONAWEAVER: Controllable Diversity Beyond Conventional Archetypes in Procedural Character Generation

**链接**: https://arxiv.org/abs/2609.26629
**作者**: Maan Qraitem, Kate Saenko, Bryan A. Plummer
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Procedural character generation aims to populate games, simulations, and other virtual worlds with diverse characters. Large language models (LLMs) offer a promising foundation for scaling this task. However, LLM-based procedural character generation remains at an early stage: existing methods either generate characters directly or adapt profiles retrieved from persona banks. As we show, both approaches produce behaviorally homogeneous populations: characters overwhelmingly agree with positive moral norms and respond to questions with helpful, assistant-like reactions. To mitigate this homogenization, we introduce PersonaWeaver, which disentangles world building from behavioral specification and models behavior through setting general, diverse, manually curated banks of moral positions and conversational reactions. This design allows us to test how far LLM(s) can be pushed beyond their default behavioral patterns across settings. Across ten realistic and fantastical settings and three 

---

### [96] TCMaster: Confidence-Aware Querying and Workload-Guided Physical Design for Multi-Source Traditional Chinese Medicine Knowledge Graphs

**链接**: https://arxiv.org/abs/2609.25712
**作者**: Zheng Chen, Yuzhu Li, Haoxuan Li, Zhongde Zhang, Lianshun Jin and Peiwu Qin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-source knowledge graphs (KGs) need query mechanisms that expose reliability and exploit domain structure. This paper presents TCMaster, a property-graph query substrate for confidence-aware traversal and workload-guided physical design over Traditional Chinese Medicine KGs. TCMaster integrates pharmacopoeias, prescriptions, molecular databases, and LLM-extracted micro-semantics into a KG with approximately 221K entities and 723K base edges. It annotates edges with provenance-level confidence, rewrites Cypher queries with confidence predicates, ranks multi-hop paths under PRODUCT, MIN, or weighted-average policies, and uses ontology skew through direction selection, herb-attribute bitmaps, and materialized shortcut edges. On Neo4j, direction selection improves attribute lookup by a factor of 1.47, shortcuts accelerate high-fanout target counting by a factor of 4.42, confidence filtering removes 39.3 percent of low-quality heterogeneous paths, and KG retrieval improves TCMbench QA 

---

### [97] MAC-RRG: Iterative Multi-Agent Collaboration for X-ray Radiology Report Generation

**链接**: https://arxiv.org/abs/2609.26124
**作者**: Futian Wang, Yuhan Qiao, Xiao Wang, Dan Xu, Yuehang Li, Zhixiang Guo 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the remarkable progress of LLM-based and knowledge graph-augmented Radiology Report Generation (RRG) methods, existing techniques still suffer from inherent defects. Conventional LLM-only models lack structured medical prior knowledge, resulting in frequent medical hallucinations and low diagnostic interpretability. Current knowledge graph-enhanced schemes adopt static one-round knowledge fusion with single-source knowledge, incapable of dynamic knowledge updating according to generation feedback. This paper proposes a novel Multi-Agent Collaborative iterative framework for X-ray Radiology Report Generation, termed MAC-RRG. Inspired by multi-agent technology, our framework constructs a closed-loop optimization paradigm based on task decoupling and collaborative reasoning. Specifically, the framework first generates a preliminary radiology report from input X-ray images via a vision encoder and a basic LLM. Subsequently, a multimodal knowledge graph (MM-KG) agent mines structure

---

### [98] Indirect tipping: a social attack surface in AI agent populations

**链接**: https://arxiv.org/abs/2609.25194
**作者**: Ariel Flint, Luca Maria Aiello, Sara M. Constantino, Romualdo Pastor-Satorras, Andrea Baronchelli
**来源**: cs.MA cs.AI cs.CY cs.SY eess.SY physics.soc-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As generative AI agents are deployed at scale, safety will depend not only on technical safeguards and individual model design, but also on collective equilibria that determine how agent populations process information, prioritize actions, and respond to uncertainty. Yet the same equilibria that enable agents to coordinate also create a social attack surface. The standard framework to assess this vulnerability is critical mass dynamics: the minimum fraction of adversarial agents required to overturn an equilibrium through direct competition. Here, we show that this approach risks underestimating system vulnerability by reducing the problem to the identification of singular tipping points, and ignoring indirect but potentially more efficient routes through which collective behavior can be redirected. Through experiments with populations of LLM agents and an analytic framework that captures their collective dynamics at scale, we map critical-mass thresholds that define a directed, weight

---

### [99] WatchPoint: Executable User Feedback for Real-World Agentic Web Development

**链接**: https://arxiv.org/abs/2609.26204
**作者**: Guanqun Yang, Wei Yang, Xueqing Liu
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a professional web developer's code fails a test, they do not simply re-read the stack trace. They open the application in a browser, click buttons, inspect computed styles, and run diagnostic commands to understand what went wrong. Existing feedback mechanisms for coding agents rely on screenshots, LLM-as-a-judge scoring, or natural-language corrections, but few interact with the live application the way a developer would. We introduce WatchPoint, a simulated-user system that mimics real developer behavior by generating and executing diagnostic scripts against the running application, producing structured observations that guide the coding model's retry. Unlike prior approaches that target single-file edits or evaluate using non-executable metrics, we operate on Web-Bench, a benchmark of 50 multi-file web projects comprising 1,000 sequentially dependent tasks, verified by deterministic end-to-end tests. WatchPoint recovers 57.6% of the tasks it diagnoses, and a controlled user st

---

### [100] Identifying Intelligent Processes via Online Sequential Testing

**链接**: https://arxiv.org/abs/2609.26193
**作者**: Aritra Das, Debayan Gupta
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Active sequential hypothesis testing studies how to identify an unknown hypothesis with a given set of sensing actions. We study this in the setting of identifying large language models (LLMs), \textit{i.e.}, if a user is conversing with an LLM drawn from a known set of models, how can they identify which one is in use? Here, the available sensing actions (evaluations) are themselves a design choice: an evaluator must first decide which environments and prompt families to construct, and only then decide how to use them sequentially. We formalize these two levels as an outer probe-design problem and an inner identification problem. Simply put, the outer stage selects a set of probes to be sent to the entire set of models, creating a kind of fingerprint dataset. This is followed by the inner stage, which sequentially sends a budget-minimizing set of those probes to identify the model in use. For the outer problem, we show that selecting which evaluations to construct at minimum cost, so 

---

### [101] MAGIC: Mixed-Granularity Agent Graphs via Incremental Construction with Dense-Reward Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.26667
**作者**: Kairui Yang, Ziheng Yi, Xunkai Li, Minghao An, Zhanke Liu, Zekai Chen 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collaboration topology shapes both the performance and execution cost of LLM-based multi-agent systems. Because tasks differ in complexity and required capabilities, recent approaches generate task-specific collaboration graphs that specify agent participation and information flow. However, representative topology generators use either individual agents or predefined groups throughout an organization, overlooking differing collaboration needs across subtasks. Our key insight is to select granularity locally for each functional role, combining fine-grained control with reusable collaboration patterns within one organization. Learning such organizations requires exploring a combinatorial construction space with limited intermediate feedback from final-answer rewards. Therefore, we propose MAGIC, a dense-reward reinforcement learning framework for mixed-granularity graph generation. Specifically, MAGIC constructs a mixed-granularity agent graph by sequentially selecting a functional role,

---

### [102] SambaGraph: Action-Reaction Spatio-Temporal Graphs for Soccer Tactical Response Modeling

**链接**: https://arxiv.org/abs/2609.25569
**作者**: Abel A. Reyes-Angulo, Henry O. Velesaca, Steven Araujo
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Soccer tactics are interactive: an attacking action changes the opponent's defensive problem, and the observed response depends on the multi-agent match state. We introduce SambaGraph, an action--reaction spatio-temporal graph dataset and benchmark for soccer tactical response modeling. From tracking and event data for all 64 matches of the 2022 FIFA World Cup, we curate 4,070 action-centered episodes represented as temporally aligned 23-node player--ball graph sequences with attack/defense views, response labels, and 26,270 split-safe attack--defense pairs. We study three questions: whether observed responses can be classified from graph episodes, whether successful defenses can be retrieved for a query attack, and whether graph-derived summaries support grounded LLM reasoning. A compact signature MLP obtains $0.796\pm0.007$ macro-F1 for response classification, while a fused graph--signature dual encoder reaches $0.471\pm0.029$ Hit@5 and $0.655\pm0.051$ Hit@10 for full-bank defensive

---

### [103] Deflecting the Value Compass: Interacting with Large Language Models Temporarily Shifts Human Value Priorities Toward Personal Focus

**链接**: https://arxiv.org/abs/2609.25586
**作者**: Hasibur Rahman, Malak Sadek, Smit Desai
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly support decisions where values are in tension, yet little is known about whether interacting with them changes which values users prioritize. In a preregistered study, 200 U.S. adults interacted with ChatGPT, Claude, or Gemini as a thinking partner or read fixed AI-generated considerations. The prompt asked LLMs to support reasoning without recommending a decision and named no values. Participants advised people facing real dilemmas and completed parallel PVQ-RR forms before, immediately after, and one task later. Each LLM condition temporarily shifted value priorities toward personal focus relative to the control (d=0.37-0.51), primarily through increased Self-Enhancement. Participants' advice retained words and meaning from their exchanges. Thus, a brief LLM interaction that neither targets values nor seeks to persuade can reorient values active during judgment without detectable convergence in value directions or advice.

---

### [104] JEV-as-a-Judge: Accept When Confident, Escalate When Unsure

**链接**: https://arxiv.org/abs/2609.26550
**作者**: Yubo Li, Yidi Miao, Ramayya Krishnan, Rema Padman
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge enables evaluation across diverse tasks, but inference cost and confidence reliability become critical at scale. We study whether a decision-only judge can provide an economical first pass and identify when stronger evaluation is needed. Comparing jev-as-a-judge with sixteen generative and reward-model judges, with blinded human adjudication, we find it within three percentage points of a state-of-the-art LLM judge, our strongest comparator, on ordinary preference and evidence-grounded factuality at 0.36% of the comparator's fee. Larger gaps arise when judgments require checking a derivation or resisting an elaborately written wrong answer. On several benchmarks, JEV's gap to this comparator is concentrated in low-confidence decisions. A frozen cascade that accepts confident verdicts and escalates uncertain ones retains 99% of the comparator's accuracy at lower cost.

---

### [105] Online Automated Algorithm Design with Large Language Models

**链接**: https://arxiv.org/abs/2609.25325
**作者**: Zhiyao Zhang, Yichen Li, Xingyu Wu, Liang Feng, Kay Chen Tan
**来源**: cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) enable automated algorithm design (AAD) through reasoning and code synthesis. However, most existing LLM-based AAD methods separate algorithm design from target optimization, deploying a fixed design even as the optimization state evolves. Conventional adaptive optimizers can respond to such changes, but their adjustments remain confined to predefined parameters, operators, or strategies. To address these limitations, we introduce online LLM-based AAD, a novel optimization paradigm that treats the algorithm itself as a state-dependent decision variable. At each stage, LLM agents synthesize an algorithm with new behavior logic from the current optimization state. Executing the generated algorithm advances the search and provides feedback for subsequent designs, coupling algorithm design with target optimization without requiring a separate offline algorithm pretraining stage. To implement this paradigm, we propose OnDesign, a multi-agent framework that recon

---

### [106] Transcribe, Translate, and Optimize: Joint Reward Learning for Speech Translation

**链接**: https://arxiv.org/abs/2609.26536
**作者**: Yanghe Dong, Wanting Huang, Weiran Wang
**来源**: cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM-based speech translation, transcription-based chain-of-thought (CoT) suffers from a mismatch between reference transcripts used in supervised fine-tuning (SFT) and model-generated transcripts at inference. To address this, we propose joint recognition and translation fine-tuning via group relative policy optimization (GRPO). We score both transcripts and translations, with translation conditioned on model-generated transcripts, and compare three token advantage strategies. Using Qwen2.5-Omni-3B across four languages, we evaluate CoT against direct speech translation (Direct ST) under SFT and GRPO, training on CoVoST 2 and testing on CoVoST 2 and FLEURS. CoT GRPO outperforms Direct ST GRPO by 1.77 and 0.83 average BLEU points on CoVoST 2 and FLEURS. Compared to CoT SFT, GRPO boosts BLEU by 0.82 and 0.67 points and reduces word error rate (WER) by 8.8% and 7.2% relatively. These results highlight reinforcement fine-tuning as an effective method to mitigate the training-inference m

---

### [107] Direct Optimization of Generators for Search in Automated Theorem Proving

**链接**: https://arxiv.org/abs/2609.25575
**作者**: Adam Ousherovitch and Ambuj Tewari
**来源**: cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuned Large Language Models (LLMs) significantly advance Automated Theorem Proving (ATP), but are often deployed as guiding policies within tree search rather than for single-attempt generation. Recent work shows cross entropy is suboptimal for an LLM used in flat search strategies such as aggregation or filtering and that work has developed new loss functions to correct this misalignment. Extending this alignment to tree search is more challenging: proof discovery depends on exploration and recovery through off-trace states that supervised demonstrations do not reveal. We extend Compute-Aligned Training (CAT) to this setting through an abstraction of policy-guided search, deriving tractable, trace-supported losses. Alongside these search-aware losses, we introduce a search-agnostic uniform-allocation (UA) loss that accounts for the budget without specifying the specific search. Both induce scalar weights on per-tactic cross-entropy gradients. We characterize how off-trace behavio

---

### [108] Same Quantity, Different Answer: Numerical Representation Invariance in Language Models

**链接**: https://arxiv.org/abs/2609.25009
**作者**: Ephraim Atta-Duncan
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Numerically equivalent word problems should yield the same canonical answer whether a quantity is written as a decimal, fraction, percentage, number word, scientific notation, or an exactly converted unit. We generate 3,600 exact-rational problems and 8,600 prompts spanning five identity-preserving transformation families, and evaluate five open-weight systems. After a fixed syntax audit that normalizes common answer forms without an LLM judge, canonical accuracy is 0.969-0.996, but orbit correctness falls to 0.848-0.981 and orbit invariance to 0.851-0.981; invariant-but-wrong orbits account for at most 0.003. Most of the broad strict-parser collapse arises because multiplication-form scientific notation lies outside the implemented number grammar, illustrating how evaluator interfaces can masquerade as reasoning failures. A distinct semantic pathology remains: Mistral Small 4 scores 0.699 on unit-converted inputs and produces 265 errors differing from the label by exact powers of ten.

---

### [109] One Domain, Many Tongues: Composing Domain and Language LoRAs for Cross-Lingual Remote-Sensing MLLMs without Paired Data

**链接**: https://arxiv.org/abs/2609.26097
**作者**: Xuechen Li
**来源**: cs.CL cs.CV cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote-sensing (RS) multimodal large language models (MLLMs) are trained and evaluated only in English, while text-only instruction data covers over 100 languages. We propose MODL (Mutually Orthogonal Domain-Language composition), a recipe that adds new languages to an English RS MLLM without a single multilingual RS example: a domain LoRA trained on English RS imagery and a language LoRA trained on text alone are learned jointly, under one loss term that keeps the two updates mutually orthogonal at every layer throughout training. This constraint is the recipe's active ingredient. Without it, the same training answers RS questions correctly but in English, erases much of the base model's multilingual text ability, and diverges on one seed in three; sixteen alternatives, from training-free merging to prior orthogonality variants, fail the same way. MODL repairs every failure on every seed: answers are correct and in the target language 56-71% of the time, where the best alternative rea

---

### [110] Do Vision Model See Like the Brain? A Comparison Across EEG Encoding Model

**链接**: https://arxiv.org/abs/2609.26512
**作者**: Shashank Baghel, Kshitij Dwivedi, Dinesh Singh, Sanjeev Nara
**来源**: cs.CV cs.AI cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Convolutional neural networks (CNNs) and vision transformers are both used to model the human visual system, but whether the two architectures diverge at a specific point in network depth is unclear. We compared six CNNs and two vision transformers by computing the Pearson correlation (r) between each model's predicted and measured EEG response at every layer or block, in ten participants viewing 200 natural images. For the transformer models, we also tested four token representations, from the classification (CLS) token alone to CLS combined with all patch tokens. CNNs showed strongest correspondence at the earliest layers, weakening at deeper layers, particularly later in the post-stimulus response. Transformers instead sustained strong correspondence at their deepest blocks, though not at their earliest ones. This advantage depended on token representation: pooled representations gave weaker peak correlations (r approx 0.48-0.51) than representations retaining all patch tokens (r=0.

---

### [111] Cellular-Communication-Level Interpretability for Pathology Foundation Models via Graph Distillation on Microenvironment

**链接**: https://arxiv.org/abs/2609.26073
**作者**: Yuxiang Xiao, Zhiwei Chen, Dan Dai, Wei Li, Tianyang Zhang, Yakun Ju 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models (PFMs) provide strong tile-level representations but remain difficult to interpret at the cellular and microenvironmental scales that underpin clinical reasoning. We introduce Graph-Interpreter (G-Interp), a graph-distillation framework that equips a frozen PFM teacher with a cellular-communication-level "plug-in" interpreter, without modifying the teacher. For each tile, we segment cells as graph nodes and construct a microenvironment graph based on spatial adjacency. Graph neural network (GNN) students distil the PFM embedding, whilst learning attention-based message passing that yields node- and edge-level importances. We interpret these importances as cell-cell communication evidence, providing fine-grained explanations of how PFMs encode microenvironmental context. To stabilise distillation when graph abstraction is imperfect, we employ a lightweight auxiliary student to supply complementary visual cues and condition graph message passing, while keeping

---

### [112] Parameter-Efficient Adaptation of Pre-Trained Vision Foundation Models for Active and Passive Seismic Data Denoising

**链接**: https://arxiv.org/abs/2605.10953
**作者**: Jiahua Zhao, Umair bin Waheed, Jing Sun, Yang Cui, Nikos Savva, and Eric Verschuur
**来源**: physics.geo-ph cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] Vision Foundation Models with Synthetic-Only Training for Monocular Spacecraft Pose Estimation

**链接**: https://arxiv.org/abs/2609.26561
**作者**: John Church, Vazghen Nikolian
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present an improvement on previous spacecraft pose estimation architectures that results in the lowest published mean rotation errors we know of on the SPEED+ lightbox and sunlamp test sets for a known, non-cooperative spacecraft. By using a previously established heatmap-based pose estimation architecture and adapting a large self-supervised ViT foundation model (DINOv3) in place of the smaller convolutional and ViT encoders of previous work, we show that pose estimation accuracy improves from 300M to 840M parameters with no saturation yet observed. We also evaluate our 840M model on a Jetson Orin NX 16GB, measuring single-pass network inference at 133.8 ms per crop with a board draw of 32.0 W. These measurements demonstrate embedded inference feasibility on a processor family with orbital flight heritage. Our resulting model outperforms previous models across lightbox and sunlamp domains while training only on synthetic data. Our best model, using DINOv3 840M adapted with LoRA as 

---

### [114] Interweaving Marginals into Multivariate Sample Paths: Training-Free Dependence Construction for Probabilistic Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.25980
**作者**: Jinmyeong Choi, Jinkwan Jang, Seul Lee, Taesup Kim
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Probabilistic time series foundation models (TSFMs) provide coordinate-wise predictive distributions, but these marginals do not determine a joint distribution over multivariate future trajectories. We study training-free coupling of frozen TSFM marginals into multivariate forecast sample paths. Our primary evaluation fixes the empirical marginal sample multiset at every channel--horizon coordinate across methods, isolating the effect of coupling alone. Historical temporal and channel relations substantially improve their corresponding dependence diagnostics. The same pattern persists when the fixed-marginal constraint is removed and paths are sampled directly, and remains present under native multivariate backbone inference. These results support treating dependence reconstruction as a distinct post-processing problem for probabilistic TSFMs.

---

### [115] A JEPA Recipe for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.25541
**作者**: Mingyu Jeon, Suwan Cho, Jae Young Suh
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models learn to predict cell values in context, whereas world-model self-supervision asks for prediction in representation space (LeCun, 2022; Assran et al., 2023). On a tabular foundation-model prior, the latent term of a joint-embedding predictive architecture (JEPA) collapsed in our earlier runs and took the encoder with it to a constant map. We report a recipe under which the latent term survives to convergence beside the value objective: the value head reads the encoder field rather than the predictor, and the target is an exponential moving average (EMA) difference. To bound its cost against the value-only arm, both arms train until a plateau rule stops them, with no fixed step budget. A fixed horizon had confounded a slowdown with a ceiling, since the value-only arm was still improving well past the usual budget. At convergence, in one run per arm, the JEPA arm trails the value-only arm across 147 real datasets, 32:70 wins to losses on classification (29:63 wi

---

### [116] Evaluating Accuracy and Probabilistic Reliability of Zero-Shot Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.25788
**作者**: Panagiotis Michael and Moysis Symeonides and Demetris Trihinas
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) promise a paradigm shift toward zero-shot forecasting by eliminating task-specific training. However, existing works often overlook trade-offs between predictive accuracy and probabilistic calibration. This paper presents a benchmark study of six TSFMs evaluated on energy, traffic, and financial datasets. We contrast their performance against statistical baselines and a supervised DL model. The study reveals that while TSFMs outperform statistical methods and supervised models, they are subject to a fundamental trade-off between point accuracy and probabilistic reliability. Specifically, xLSTM architectures provide robust probabilistic calibration across horizons. In contrast, patch-based transformers offer competitive accuracy but face calibration issues at long horizons, while transformer-based models exhibit context saturation points for optimal zero-shot reasoning. These findings offer evidence-based guidance for balancing generalization and un

---

### [117] Learning to Fluctuate: Statistical Foundations for Causal Tabular Pretraining

**链接**: https://arxiv.org/abs/2609.26290
**作者**: Zhiheng Zhang
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Causal tabular foundation models amortize effect estimation across synthetic mechanisms, but latent-effect supervision rewards posterior shrinkage instead of directly encoding the repeated-sample response needed in a fixed deployment population. We introduce fluctuation-supervised pretraining (FSP): each synthetic table is labeled by its average treatment effect plus its efficient influence-function fluctuation, while deployment remains a single frozen forward pass. Along the path $T_{\lambda,P}=\theta(P)+\lambda P_n\psi_P$, we prove an endpoint transition: every fixed $\lambda<1$ retains label ambiguity of order $(1-\lambda)^2/n$, whereas full fluctuation makes the Gaussian label observable and reduces optimal finite-stratum causal label-prediction risk to order $n^{-2}$. One finite-pretraining bound combines label, network, episode-sampling, and optimization errors; its resulting sampling defect controls fixed-mechanism bias, mean squared error, variance, Gaussian approximation, and,

---

### [118] WILSON - a pathology foundation model framework for patient-level analysis and diagnostic text generation

**链接**: https://arxiv.org/abs/2609.25123
**作者**: Saghir Alfasly, Wataru Uegami, Sobhan Hemati, Wenchao Han, Xiaojia Tang, Kevin Thompson 等 (10 人)
**来源**: q-bio.QM cs.AI cs.CV cs.LG eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathologists integrate morphology across magnifications and across the slides of a patient case, whereas pathology foundation models encode thousands of tiles from single slides and aggregate their features. Here we present WILSON, a vision--language foundation model that represents whole-slide images and multi-slide cases as single multi-magnification composite images, trained on approximately 189k slides from Mayo Clinic spanning 42 organs and 829 diagnostic entities using pathology reports as supervision. Without task-specific training, WILSON exceeded a dedicated case-level model on all internal cohorts (macro-F1 0.52 versus 0.38) and matched slide-level models up to 9.4 times larger at 272- to 2,155-fold lower compute. End-to-end fine-tuning on 508 triple-negative breast cancer cases improved histologic subtyping and stromal tumor-infiltrating lymphocyte grading by 0.16 and 0.11 macro-F1. WILSON retrieved matching diagnostic text at 75.6% recall@1 (PRISM, 58.1%) and generated capt

---

### [119] Radiomics-Conditioned Modulation of RenalCLIP Features for Clear Cell Renal Cell Carcinoma Classification

**链接**: https://arxiv.org/abs/2609.26492
**作者**: Yuan Liang, Sourav Bhattacharjee, and Abraham Campbell
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radiomics provides quantitative descriptions of tumour appearance that may complement disease-specific foundation models in small labelled cohorts. We investigate this complementarity for computed tomography-based classification of clear cell renal cell carcinoma. Our framework uses radiomics to modulate RenalCLIP features through feature-wise linear modulation (FiLM), while retaining a direct radiomics contribution. Internal testing and external validation compare it with conventional fusion strategies and reference classifiers. The FiLM model achieves an area under the receiver operating characteristic curve (AUC) of 0.804 internally and 0.854 externally, with the highest mean AUC among the evaluated RenalCLIP fusion strategies in both cohorts. Pathway ablations examine the contributions of conditional modulation and the direct radiomics residual, while feature permutation highlights the role of tumour texture. These findings support radiomics as a useful complement to RenalCLIP in a

---

### [120] Brain-Inspired Hierarchical Modularity for General Continual Learning

**链接**: https://arxiv.org/abs/2609.25146
**作者**: Hongwei Yan, Kanglei Zhou, Qi Cheng, Weiyi Dong, Chunyan Lan, Guanglong Sun 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual learning, the ability to learn from sequential experience while retaining and adapting prior knowledge, is central to intelligent systems operating in changing environments. However, conventional continual learning is typically studied with offline task-wise training and clear task boundaries, leaving a substantial gap from general continual learning under online, uncertain, and evolving data streams. In this regime, intelligent systems must separate conflicting experience to reduce interference while integrating compatible experience to promote generalization. Inspired by the organization of the Drosophila learning and memory system, we identify a hierarchical modular principle that coordinates both functions through expert specialization and ensemble integration. We instantiate this principle as lightweight modular adaptation of pretrained foundation models, combining brain-inspired random expansion for expert routing and diversified modular integration across spatial and t

---

### [121] Do Existing Preconditioners Improve Biomedical Tabular Foundation Learning? An Empirical Study on TabPFN Optimization

**链接**: https://arxiv.org/abs/2609.25013
**作者**: M. Sajid, Pinki Khatun, M. Tanveer
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models have recently shown strong potential for structured biomedical data analysis. Among them, TabPFN has emerged as an effective approach for low-data tabular classification tasks. However, the impact of optimization and preconditioning strategies on biomedical fine-tuning remains largely unexplored. In this work, we present a comprehensive empirical investigation of five AdamW-based preconditioning strategies for fine-tuning TabPFN v2.5 on 59 biomedical datasets spanning Alzheimer's disease, breast cancer, schizophrenia, significant memory concern (SMC), KEEL biomedical datasets, and UCI biomedical benchmarks. The evaluation considers predictive performance, computational efficiency, and statistical significance analysis. Experimental results demonstrate that the original AdamW optimizer consistently achieves the best overall performance and statistical ranking, while existing curvature-aware preconditioners fail to provide reliable improvements across diverse bi

---

### [122] Real-World Perception for Autonomous Driving in Adverse Weather: Enhancing Standard Detectors via Foundation-Guided Auto-Annotation

**链接**: https://arxiv.org/abs/2609.25515
**作者**: Sepideh Gohari, Goodarz Mehr, Azim Eskandarian
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard deployment-ready object detectors for autonomous vehicles degrade in adverse weather and lighting conditions without being trained on extensive domain-specific data. While large-scale vision foundation models offer robust zero-shot generalization, their high computational cost makes them impractical for real-time deployment. To bridge this gap, we propose a foundation-guided auto-annotation pipeline that enhances standard detectors without architectural changes. We first benchmark three distinct models, YOLOv8, Co-DETR, and SAM3, on our custom real-world driving dataset spanning 25 unique operational scenarios across various route, weather, and lighting conditions. Based on our analysis, SAM3 demonstrates superior accuracy and resilience across all scenarios. Thus, we deploy it as an offline auto-annotator to generate pseudo-labels on the unannotated subset of our dataset. Fine-tuning the baseline YOLOv8 on these annotations yields a 16.04% higher overall mean Average Precisio

---

### [123] HARMONY: Hierarchical Agentic Reasoning for MONocular Image-to-Scene Synthesis

**链接**: https://arxiv.org/abs/2609.26793
**作者**: Shufan Sun, Chen Wang, Enxin Song, Jiatao Gu, Lingjie Liu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compositional 3D scene reconstruction has recently been explored from two directions: agentic reasoning that provides semantic understanding of spatial relationships but lacks precise alignment with input images; and visual geometry foundation models that predict dense point maps from input images but the reconstruction quality is limited. Therefore, recovering a complete 3D scene from a single monocular image with accurate inter-object relationships and high-fidelity reconstruction quality remains challenging. In this paper, we present HARMONY, a hierarchical chain-of-thought framework that leverages both agentic reasoning and visual geometry foundation. Given an image of an indoor scene, starting from an empty 3D floorplan, HARMONY first calibrates the camera against the reference image to establish a semantically-grounded spatial frame, then uses agentic VLM reasoning to recover the 3D room layout and an initial placement order. It then places the objects in a hierarchical order, fr

---

### [124] Calibrating Retrieval Geometry: Reliability-Guided Training-Free Aggregation for Visual Place Recognition

**链接**: https://arxiv.org/abs/2609.25937
**作者**: Xin Li, Zhimin Mao, Shang Wang, Siyuan Duan, Geng Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frozen visual foundation models provide transferable features for visual place recognition, but fixed aggregation can suppress useful distinctions in new environments. We introduce TFA, a reliability-guided, training-free aggregation method requiring neither place labels nor task-specific weight updates. Our key observation is that reproducible retrieval need not be discriminative: independent codebooks can consistently retrieve a few database hubs. TFA combines cross-codebook agreement, retrieval coverage, and spectral statistics to control residual assignment, spectral shaping, and global-feature fusion. Its spectral kernel exactly recovers original descriptor similarity at zero intervention. Database-only TFA fixes its rules before accessing queries; TFA-C64 uses 64 disjoint unlabeled target images to calibrate retrieval for subsequent queries. Across 20 ground protocols with a fixed DINOv2-B backbone and matched resolution, database-only TFA improves Recall@1 over AnyLoc by 17.39 p

---

### [125] LLaVA-Assessor: Building the Foundation LMM For Visual Quality Assessment

**链接**: https://arxiv.org/abs/2609.26205
**作者**: Ziheng Jia, Zicheng Zhang, Jiaying Qian, Guangtao Zhai, Xiongkuo Min
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aligning with the human visual system~(HVS) in perceiving and evaluating the quality of visual signals is a central objective of machine-vision-based visual quality assessment systems. With the rapid progress of large multi-modal models~(LMMs), visual question answering provides a promising paradigm for building unified foundation models for visual quality assessment under multi-modal and multi-task scenarios. Inspired by the classical ``perception-decision" process in HVS-based quality evaluation, we formulate visual quality assessment for LMM-based machine vision as two complementary tasks: ``quality interpretation'' and ``quality scoring". Centered on these objectives, we propose LLaVA-Assessor, a unified data construction and model training system. To support multi-modal inputs, we design an adaptive model architecture that enables efficient processing of both images and videos. For data construction, we develop rigorous human annotation protocols and a novel machine-synthesis-domi

---
