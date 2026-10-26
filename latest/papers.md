# 📑 论文索引 - 2026-10-27

共 129 篇论文

---

### [1] U-STS-LLM: A Unified Spatio-Temporal Steered Large Language Model for Traffic Prediction and Imputation

**链接**: https://arxiv.org/abs/2605.11735
**作者**: Yichen Zhang, Yiyang Ni, Pengcheng Xia, Jun Li, and Chunguo Li
**来源**: cs.LG eess.SP
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] Knowing Whom to Trust is not Enough: The Trust--Agreement Gap in Repeated Multi-Party LLM Negotiation

**链接**: https://arxiv.org/abs/2610.31971
**作者**: Amit Sarker, Moumita Choudhury, Saaduddin Mahmud, Shlomo Zilberstein
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly participate in negotiations on behalf of individuals and organizations, yet they remain vulnerable to manipulation, particularly in repeated multi-party interactions. Classical multi-agent systems address this challenge through explicit trust and reputation models, whereas existing work on LLM negotiation largely treats trust as an emergent phenomenon. We investigate whether LLM agents can form useful trust estimates from prior interactions and leverage them to improve future negotiation outcomes. We introduce a repeated, multi-party, multi-issue negotiation framework in which recurring agents participate in a sequence of negotiation games while one participant covertly attempts to prevent agreement. After each game, agents assess their counterparts and maintain pairwise trust estimates that carry over to subsequent negotiations. We compare trust-aware and trust-agnostic agents and analyze how explicit trust influences negotiation outcomes

---

### [3] Efficient Omni-modal Large Language Model Inference via Per-Query Modality Selection

**链接**: https://arxiv.org/abs/2610.31768
**作者**: Shuqi Liu, Yuzhou Cao, Luke Ong
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Omni-modal large language models (Omni-LLMs) can jointly process a broad range of modalities, such as text, audio, and video, enabling stronger multimodal understanding and reasoning capabilities, but often at substantial inference cost. We observe that the benefit of additional modalities varies across queries, indicating that a fixed modality configuration can be inefficient. Motivated by this, we study query-wise modality selection, which keeps the underlying Omni-LLM fixed while adaptively selecting which modalities to provide for each query. We formulate the problem as an accuracy-cost optimization problem and develop a cost-sensitive learning approach for modality selection. We evaluate our approach on WorldSense using Qwen2.5-Omni and Qwen3-Omni under three inference-cost measures: input tokens, latency, and monetary cost. Across both models, query-wise modality selection consistently improves the accuracy-cost trade-off and can even outperform the standard setting in which all 

---

### [4] LeafSkill: Efficient Leaf-Level Action Grounding for Recursive LLM Agents

**链接**: https://arxiv.org/abs/2610.32412
**作者**: Shen Liu, Ze Zhou, Zhenguo Xu, Shaopu Wang, Yike Gao, Chunlei Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive large language model (LLM) agents solve long-horizon tasks through decomposition, execution, and environmental feedback. Yet after producing an atomic subtask, they often invoke the same large model again to translate a familiar instruction into an executable action. We observe that high-level planning is task-specific, whereas leaf-level action grounding recurs across tasks and can be checked against environment-admitted actions. We introduce LeafSkill, an external reuse layer that retrieves semantically related grounding experience, binds action templates to current objects and admissible actions, and uses a lightweight 1.7B selector to choose a bound action or defer the unchanged subtask to the original agent. Skills remain outside the model parameters, allowing a frozen selector to use post-training additions. Under lexical and syntactic paraphrases, exact matching retrieves none of the reference actions, while semantic retrieval preserves 96.0% and 97.0% candidate covera

---

### [5] KnitTrans: Coordinated Trajectory Transfer for Effective and Efficient LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.32389
**作者**: Bangjun Xiao, Chiheng Lou, Xiaodong Ji, Xiangwei Deng, Yikai Zhao, Gang Huang 等 (7 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trajectory transfer from rollout to training affects both learning quality and system efficiency in large language model reinforcement learning (RL). Enforcing batch-wide training requirements can delay the admission of completed trajectories, resulting in higher architectural staleness: the additional parameter-version gap from disaggregated pipelining relative to colocated execution. Beyond admission, misalignment between data access and training consumption causes redundant movement and unnecessary waiting when transferring large trajectory payloads. We present KnitTrans, a system that coordinates the rollout-to-training path through three designs. First, constraint-preserving mini-batch admission allows flexibility in early mini-batch composition, while checking that enough capacity remains to satisfy the remaining quotas. Second, on-demand trajectory data access matches storage units to consumer assignments and overlaps micro-batch data preparation with computation. Third, multimo

---

### [6] Not Every Agent Needs the Strongest Model: Unified Prompt-Model Optimization for Heterogeneous LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.31743
**作者**: Mingxiu Cai, Haoyang Xian, Xinyu Ma, Yutong Wang, Zhenxi Song, Jing Li 等 (7 人)
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) rely on role-specific prompts and execution models to solve complex tasks collaboratively. However, prompt optimization typically keeps model assignments fixed, leaving differences in role requirements and their associated inference costs outside the search. We present UniMASO, a Unified framework for heterogeneous Multi-Agent System Optimization through the joint adaptation of prompts and model assignments. UniMASO evaluates candidate updates through local, downstream, and global feedback, using cost-aware Pareto search to retain useful quality-cost trade-offs. Topology-aware co-evolution then coordinates these updates according to agent roles and dependencies. Cross-level trajectory memory further supplies historical successes and failures to guide subsequent optimization. Experiments on five benchmarks and five execution topologies show that UniMASO achieves competitive task performance at substantially lower deployment cost

---

### [7] Async-RBench: Benchmarking Asynchronous Task Execution in LLM Agents

**链接**: https://arxiv.org/abs/2610.32429
**作者**: Detao Zeng, Guilin Ou, Nuo Chen, Yunhao Feng, Hongliang Wang, Qinli Yang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly execute tasks asynchronously: a main agent continues working while its subagents run, and the task state may change before their results arrive. The main agent must decide which work to update or preserve and which checks to repeat, while avoiding prohibited changes. Final task success alone does not reveal whether these results were handled correctly, and natural asynchronous arrivals are hard to reproduce. We introduce Async-RBench, a benchmark for asynchronous task execution in LLM agents, with 200 executable tasks covering eight scenarios. A scenario controller regulates result delivery using predefined task-state conditions, while an Event Response Contract (ERC) specifies what each response must change, preserve, avoid, and re-verify. The Dynamic Replanning Score (DRS) weights the response process and outcome equally and is reported separately from task success. We evaluate nine agents and find DRS scores of 19.2 to 45.1, with the lo

---

### [8] Monetizing Intelligence: Advertising and Subscription Design on LLM Platforms

**链接**: https://arxiv.org/abs/2610.32945
**作者**: Yuhang Ji, Fasheng Xu, Tianjun Feng
**来源**: econ.TH cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) platforms introducing advertising must decide how much capability ad revenue should fund and what consumers should pay to avoid ads. We study a monopolistic platform that jointly chooses costly response quality, advertising intensity, and subscription prices when advertising reduces user value but better service raises advertising returns. Three findings follow. First, when partly ad-supported and ad-free plans coexist, advertising can finance useful service for consumers who receive none under pure subscription. Lower effective quality in middle plans weakens the alternatives available to premium users, allowing higher prices for unchanged ad-free service. Some fully ad-supported users gain utility, while partly ad-supported and ad-free users lose: broader access can coexist with utility polarization. Second, an intermediate advertising cap can maximize consumer surplus by preserving some revenue that finances service while limiting degradation. Third, cheap

---

### [9] Trusting the Tool: Asymmetric Deference of LLM Vulnerability Auditors to Static-Analysis Evidence

**链接**: https://arxiv.org/abs/2610.32876
**作者**: ZhiHong Liu, Shuyao Gao
**来源**: cs.SE cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pipelines that combine large language models (LLMs) with static analysis let the model consume the analyser's output as evidence, but whether the model distinguishes true from false evidence, and whether its scrutiny depends on what the evidence claims, has not been measured. We built an intraprocedural analyser for C/C++ that produces proof obligations and audited vulnerable and patched functions from PrimeVul under six evidence conditions that differ only in the notes, including fabricated assurances that a missing check exists and fabricated alarms that an added check is missing. The study covers 916 pairs in four disjoint sets, eleven model configurations from four vendors and 16,572 audits; no model is trained or fine-tuned. True evidence barely improved accuracy (+0.02). False evidence acted asymmetrically: relative to true notes about the same operations, false assurances lowered the detection of real vulnerabilities by up to 19 points, whereas false alarms never significantly l

---

### [10] Machine-Readable Operator Manuals over the ISO 11783 Network for Offline, Multilingual LLM Assistance

**链接**: https://arxiv.org/abs/2610.31863
**作者**: Timo Oksanen, Julius Gun
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> If agricultural machinery is to support intelligent, offline assistance, then the system must access technical documentation dynamically. In this paper, the Semantic Synchronization of operator manuals over ISO 11783-based CAN buses is analyzed, defined as the process that brings the local knowledge base of a tractor-side assistant into agreement with the operator manual of the connected implement. Data transfer performance was benchmarked using Markdown, JSON, and XML; various open-weight Large Language Models (LLMs) were also evaluated in cross-lingual query tasks. The automatic evaluation of the answers was validated against four human raters. A complete manual was transferred over a physical ISO 11783 network in 31 to 89 s, depending on format and transport settings, which is comparable to the object pool upload that operators already wait for at the first coupling of an implement. Markdown produced the smallest files, while the question-answering performance was comparable across 

---

### [11] Fooling LLM Safety Guards into Judging the Wrong Text

**链接**: https://arxiv.org/abs/2610.31695
**作者**: Utkarsh Kanwat
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety guards check content before an LLM application acts on it, and most paste that content into a plain-text prompt. Content that imitates the prompt can append a second task, and the guard answers that one instead. We call this target rebinding. Our explanation is that the guard grades the last complete task in its input, here a harmless decoy, so the harmful request goes through unchanged. In a pre-registered test, an appended forged query and decoy clear all 75 held-out AdvBench requests that Shieldstral-1.0-3B flags. The guard is not persuaded: a directive to ignore the text above clears none of them, and in a follow-up run a harmful decoy stops the attack. On our GuardRebind benchmark, each of five guards has an attack family, chosen per guard, that clears at least 93% of its flagged items. Rebinding explains this best on Shieldstral and gpt-oss-safeguard; on ShieldGemma and Llama Guard 3, generic evasion and trailing text respectively do part of the work, and Qwen3Guard falls 

---

### [12] $M^3$: A Multi-LLM System for Multi-Turn Jailbreaking as a Markov Decision Process

**链接**: https://arxiv.org/abs/2610.31937
**作者**: Yuqing Huang, Jack Ji, Jithin Pradeep, Sagarika Suresh, Jekaterina Novikova
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern Large Language Models (LLMs) remain vulnerable to carefully orchestrated multi-turn interactions that progressively bypass safety mechanisms. However, many existing red-teaming approaches rely on heuristics or impose strong assumptions that limit their applicability in fully black box settings. We address this gap by introducing $M^3$, an automated red-teaming framework that formalizes multi-turn jailbreaking as a finite-horizon Markov Decision Process (MDP). In $M^3$, an attacker LLM interacts with a target LLM while operating over a compact internal state produced by a state LLM. Across two benchmarks and six target models, $M^3$ consistently outperforms state-of-the-art multi-turn red-teaming methods in Attack Success Rates (ASR), achieving improvements of up to 53% in ASR@5. Even with lightweight attacker, $M^3$ attains gains up to 26% in ASR@1 and 34% in ASR@5, compared to baselines that use higher capacity attackers. Beyond improved effectiveness, $M^3$ exhibits steeper ri

---

### [13] Probe Before You Edit: Probing-Guided Molecular Optimization for LLM Agents in Structure-Based Drug Design

**链接**: https://arxiv.org/abs/2606.00555
**作者**: Zaifei Yang, Weiyu Chen, Yaqing Wang, James Kwok
**来源**: cs.AI q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Training-Free Task Vectors for LLM Behavioral Control

**链接**: https://arxiv.org/abs/2609.09054
**作者**: Gabriel J. Perin, Lucas Boscaini, Andr\'e Araujo, Nina S. T. Hirata
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] AI Alignment for Digital Democracy: Fairer Voters Representation against LLM Biases

**链接**: https://arxiv.org/abs/2610.32780
**作者**: Yi Qi, Srijoni Majumdar, Evangelos Pournaras
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI representation is emerging in digital democracy, assisting in voter emulation and decision-making. Large language models (LLMs) behave differently depending on the model, the prompt context, and the voter information they receive, representing some groups more accurately than others and potentially making the emulation unfair to certain groups. We investigate demographic biases in LLM-emulated electorates: how accurately LLMs represent individual votes, whether some voter groups are represented more accurately than others, and whether AI alignment can reduce these disparities without sacrificing overall accuracy. Using three U.S. presidential elections, we compare a closed-source and an open-source LLM across voters' demographic features and test AI alignment strategies toward fairer voter representation. Removing gender from the voter profile reduces the largest group error of the models by 22-42%, and removing education reduces it by 64%, whereas removing self-reported race increa

---

### [16] J-Comm: Jacobian-Guided Latent Communication between LLM Agents

**链接**: https://arxiv.org/abs/2610.32871
**作者**: Xiangwei Wang, Wei Wang, Sachith Seneviratne, Ken Chen, Yu Xia, Peng Wang 等 (7 人)
**来源**: cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Latent communication requires both an effective continuous reasoning process and an interface through which an external model can leverage its intermediate computation. We present J-Comm, a framework comprising two core components. First, a training-free Geometric Agreement for Latent Reasoning (GEAR) reweights token candidates over existing model embeddings, which monotonically optimizes geometric consensus among candidate tokens in embedding space at each step. Second, we introduce an H+J (Hidden-and-Jacobian) communication interface that gives the Receiver two complementary views of the Sender's reasoning. The H channel supplies continuous inputs derived from feedback distributions, while the J channel conveys intermediate-state cues in vocabulary-indexed Jacobian-lens coordinates. Intuitively, H provides inputs for the Receiver to reason from, while J offers additional guidance within its computation. The Receiver reconstructs these cues using its own dictionary and injects them in

---

### [17] ALLMTS: Automated LLM-based Medical Triage System

**链接**: https://arxiv.org/abs/2610.32469
**作者**: Micha{\l} Remigiusz Janiszewski, Artur Stopa, {\L}ukasz Lenkiewicz, Wojciech Achtelik, Bartosz Gonczarek
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Telephone triage is a safety critical task: from a brief intake note, a nurse must decide whether a caller needs an ambulance, an emergency department, an appointment, or self care at home. Queried directly, large language models (LLMs) are unreliable: they over-escalate routine cases and cannot justify their recommendations against an auditable clinical standard. We present the Automated LLM-based Medical Triage System (ALLMTS), which grounds every disposition in the same commercially maintained telehealth guidelines nurses use. Rather than asking an LLM to triage, ALLMTS makes it execute the guideline: it selects the appropriate guideline and evaluates its triage assessment questions. The disposition follows deterministically from the first positive answer, using the same traversal rule a nurse follows. We evaluate ALLMTS on 566 synthetic, expert-validated scenarios spanning 14 dispositions and designed to test specific guideline questions. ALLMTS achieves 0.95 accuracy, compared wit

---

### [18] POETS: Uncertainty-Aware LLM Optimization via Compute-Efficient Policy Ensembles

**链接**: https://arxiv.org/abs/2605.07775
**作者**: Nicolas Menet, Andreas Krause, Abbas Rahimi
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] From Uncertain Judgments to Calibrated Rankings: Conformal Elo Estimation for LLM Evaluation

**链接**: https://arxiv.org/abs/2606.13221
**作者**: Bora Kargi, David Salinas
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] Same Answer, Different Confidence: Protocol Sensitivity in LLM Confidence Calibration

**链接**: https://arxiv.org/abs/2605.27752
**作者**: Hankyeol Kim and Pilsung Kang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Solvent: Long-Horizon Reasoning for Multi-Step Retrosynthesis

**链接**: https://arxiv.org/abs/2610.32308
**作者**: Yifei Wang, Botian Wang, YiFei Wang, Jiangtao Feng, Xinbo Zhang, Yawen Ouyang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-step retrosynthesis requires recursively transforming a target molecule through successive reaction steps into purchasable building blocks, and recent work has begun to draw on large language model (LLM) reasoning to tackle the task. In its latest evolution, LLM reasoning has entered the long-horizon regime: models pursue objectives across interdependent steps, interact with environments, and adapt to feedback. This shift has markedly advanced LLM capabilities, as illustrated by breakthroughs in AI-driven mathematical research. At this frontier, we introduce Solvent, an 8B LLM that successfully extends long-horizon reasoning to multi-step retrosynthesis. Through a two-round post-training curriculum, Solvent learns to interleave iterative synthesis planning, external availability verification, and adaptive route revision. Experiments show that, following a $2.1\times$ performance boost from RL, Solvent scores 61.86% across four benchmarks, surpassing mid-scale language models and 

---

### [22] Measure Before You Train: Typed Decision Models vs. a Classical Baseline vs. a Generative LLM for Routing a Personal Multilingual Inbox

**链接**: https://arxiv.org/abs/2610.32955
**作者**: Federico Lucca
**来源**: cs.CL cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personal email agents decide, for every message, what it is, whether it is urgent, whether to draft a reply, create a task, or ignore it. Their error rate is rarely measured: the stored labels were written by the system itself. We present Foyer, a self-hosted personal inbox agent in daily use, and a measurement protocol (stratified sampling, frozen snapshots, thread-grouped splits, pre-registered hypotheses, human labels in the agent's review loop) that yields ground truth before any training. On 739 real Italian/English emails labelled by the owner (231 unbiased, 500 adversarially sampled), we compare nine systems under thread-grouped cross-validation: the production keyword rules, a TF-IDF + logistic-regression baseline, local typed decision models (Tev1, Nimble), a hosted decision model (Nimble v4-max), and hosted generative LLMs (Qwen2.5-7B, Gemma 4 26B/31B). Four results. The production rules score 28% on message type against a 58% majority class: the field shown most prominently 

---

### [23] ActionRAG: Evidence-Refining Graph Diffusion for Long-Term Memory in LLM Agents

**链接**: https://arxiv.org/abs/2610.32752
**作者**: Navyansh Mahla, Sashank Vandrangi
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents need long-term memory that can recover precise and mutually consistent evidence from growing interaction histories, particularly when answers depend on relations among facts rather than isolated semantic matches. Current memory pipelines remain vulnerable at two stages: indexing errors can fragment repeated entities or merge distinct ones, and online retrieval often treats initial similarity scores as final even when the surrounding graph provides evidence for revising them. We introduce ActionRAG, a graph memory architecture that couples cautious indexing with query-time graph retroevaluation. Its indexing pipeline reconciles type labels and applies tiered entity resolution. Given a query, dual-channel entity and triple retrieval forms an initial evidence set and induces a bounded local graph. Query-conditioned receiver-normalized diffusion refines triple scores using local path structure. Seed protection, hub-penalized flux, and triple materialization preserve direct evide

---

### [24] The LLENS Platform for On-Premises Large Language Model Agents in a Japanese University Hospital: Development and Evaluation Study

**链接**: https://arxiv.org/abs/2610.32151
**作者**: Ken Enda, Jien Saito, Masami Mukai, Feng Han, Emir Turkes, Tatsumi Kusakabe 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents that use tools could take on part of the electronic health record and desk work that occupies physicians' time, but in many hospitals the medical information systems run inside closed networks, so the model and the agent harness must also sit inside. We designed, implemented, and deployed LLENS, a clinical support AI agent platform that runs inside the closed network of Hokkaido University Hospital on one host with 8 NVIDIA H200 GPUs, the open-weight model Kimi K2.6 (~1 trillion parameters), and a web application rebuilt from Open WebUI. The harness has 10 components, including page image reading, full-text attachment input, a path-addressed document tree without a vector index, a network-isolated sandbox, artifact return, self-checking of generated output, subagents, and saved procedures. Kimi K2.6 was chosen from 3 open-weight candidates and scored 480/500 on the 2026 Japanese Medical Licensing Examination; it generated 119 tokens/s for one user and served

---

### [25] When Should I Trust This? Designing and Evaluating Factuality Indicators for LLM-based Chatbots

**链接**: https://arxiv.org/abs/2610.32883
**作者**: Greta Warren and Jessica Heal and Sila Eser and Denise M. Leto and Christine M. Lehane and Isabelle Augenstein
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI systems increasingly mediate how people seek information, yet communicating AI factuality to laypeople remains challenging. Through a mixed-methods investigation involving interviews (N=8), a survey (N=1,000), and an experiment (N=5,151), we examine how people evaluate AI-generated information for gardening, mathematical, and medical queries, and how factuality indicators (confidence and sources) shape perceptions. Our interviews and survey show people selectively verify AI responses using external and AI-provided evidence, moderated by contextual factors. Although confidence-indicators affected trust and accuracy perceptions, people hold diverse, ambiguous interpretations of AI confidence. Sources were viewed as crucial, yet users raised concerns about source reliability and verification effort. Our experiment showed that confidence and source-based indicators influenced initial perceptions, but effects disappeared once participants learned the response's correctness. Me

---

### [26] Do AI-for-Science Agents Preserve Model Safety?

**链接**: https://arxiv.org/abs/2610.32045
**作者**: Michael Yew Chuan Lee, Manya Sriram, N. Benjamin Erichson
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-for-Science agents are increasingly being used for formulating scientific hypotheses, running autonomous experiments, and interpreting evidence. These agents are constructed by integrating a large language model (LLM) into a domain-specific agent harness, which in turn can improve the LLM's scientific capability and enable the model to orchestrate scientific tools. In this work, we ask whether model safety is preserved when an LLM is integrated in an AI-for-Science agent harness. We evaluate five agent harnesses on 50 harmful chemistry requests. Specifically, we study how the safety behavior changes under direct prompting, two simple adversarial prompting strategies, and an adaptive attack. Across four recent GPT variants, our results show that the agent harness can increase harmful compliance even under direct prompting. More critically, we find that adaptive attacks that are largely unsuccessful against the base LLM suddenly become highly successful after the agent harness is intr

---

### [27] SpectrumQuant: Spectrum Alignment for LLM Quantization

**链接**: https://arxiv.org/abs/2610.20303
**作者**: Dwaipayan Haldar, Indranil Patra, Azhar Yousuf, Chandra Sekhar Seelamantula
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] InferSlice: A Reference Architecture for SLO-driven LLM Inference over a Telco Wide-Area Network

**链接**: https://arxiv.org/abs/2610.32638
**作者**: Juan Parra-Ullauri, Anthony Chiu, Hari Madhukumar, Zhaozhou Wu, Anderson Bravalheri, Alex Healing 等 (9 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM inference is increasingly deployed as a core service for enterprise and interactive applications, but sovereignty, compliance, latency and resource-locality requirements can limit the suitability of centralised cloud deployments. Telco operators offer geographically distributed compute and network infrastructure for addressing these constraints. However, existing LLM serving frameworks are designed for tightly coupled data centres and provide limited support for coordinating geographically distributed and heterogeneous resources. We present InferSlice, a reference architecture for Service-Level Objective (SLO)-driven LLM inference over a telco infrastructure, integrating network slicing, GPU partitioning, elastic serving and observability. Led by BT in collaboration with the University of Bristol and NVIDIA, and realised on the JOINER UK national-scale wide-area network (WAN), InferSlice is evaluated on service differentiation across tiers, elastic scale-out, client-edge bandwidth 

---

### [29] From Review to Authorization: Key-Isolated Threshold Signing for LLM Agents

**链接**: https://arxiv.org/abs/2609.05901
**作者**: Yu Zheng and Qizhi Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] Advancing SVD-based LLM Compression via Layer-Wise Error Model Search

**链接**: https://arxiv.org/abs/2610.32878
**作者**: Moritz Thoma, Maximilian Groezinger, Maximilian Forstenh\"ausler, Emad Aghajanzadeh, Manoj Rohit Vemparala, Christos Anagnostopoulos 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-rank SVD-based compression offers a powerful strategy to reduce the computational costs of LLMs. However, existing methods face two key limitations: (i) global rank allocation, where uncalibrated error proxies fail to capture complex error propagation, and (ii) decomposition quality, where Fisher-based estimators suffer from severe rank collapse. In this work, we address these limitations by introducing Layer-wise Error Modeling Search (LEMS) and KFAC-SVD. LEMS advances rank allocation by introducing a layer-wise error surrogate that integrates local and global layer importance alongside a propagation bias, enabling effective global rank allocation via an ILP formulation. KFAC-SVD improves decomposition quality by utilizing token-wise statistics, mitigating the rank deficiency observed in prior Fisher-based SVD approaches. Across Mistral, Qwen3, and Llama 3 model families, we show that LEMS consistently outperforms existing search strategies, delivering significant zero-shot accura

---

### [31] MisconceptDialogue: Evaluation Criteria Shape Measured Success in LLM Math Tutoring

**链接**: https://arxiv.org/abs/2610.31679
**作者**: Woojin Lee, Yoonkyu Woo, Jinah Kim, Hyeok-Min Gwon, Jin-Xia Huang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as math tutors, raising two questions: can a single LLM detect a student's error, diagnose the underlying misconception, and remediate it through multi-turn dialogue - and can we trust the numbers that report how well it does? We address both with MISCONCEPTDIALOGUE, a fully automated framework that runs the full pipeline on five open-weight LLM tutors (7B-14B) interacting with LLM-simulated students over 5,000+ dialogues - a deliberately simulated protocol (paired conditions, a wrong-diagnosis control unsafe with real learners, scale) whose results do not establish real-student learning. On measurement, our headline finding is uncomfortable for the field: benchmark-style exact-match scoring common in standard math NLP - a lower-bound stress test - reports 42.1% measured Remediation Success Rate on identical dialogues where a human-calibrated LLM-as-judge reports 81.3%, a 39.2 percentage-point spread larger than the combined effects of tutor 

---

### [32] An Agentic Approach with Evidence-Grounded Verification for Multimodal Emotion Reasoning in Conversation

**链接**: https://arxiv.org/abs/2610.31685
**作者**: Elyas Rashno and Farhana Zulkernine
**来源**: cs.CL cs.AI cs.MM eess.IV
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multimodal emotion reasoning systems perform well on standard benchmarks, but improving them through instruction tuning can be computationally expensive. Agentic pipelines built from frozen models avoid this cost, but introduce a different challenge: when a prediction is wrong, the system must identify which agent or stage caused the error. We address this problem with an agentic framework for traceable multimodal emotion reasoning and prompt-space adaptation. Modality-specific perception agents analyze visual, acoustic, and lexical inputs and post evidence-cited observations to a shared board. An integration agent combines these observations with retrieved multimodal examples to produce an emotion description, label set, and supporting citations, while an MLLM critic can request one revision before the output is finalized. For incorrect predictions, a separate evidence-grounded verification stage applies deterministic checks to verify that cited evidence and references are v

---

### [33] An LLM agent for end-to-end computational materials discovery

**链接**: https://arxiv.org/abs/2608.20434
**作者**: Chen Yuntong and Huang Lijiang and Li Yingqi and Liu Yu and Zhao Dan and Sun Mingqi and Ju Chentian and Liu Yanbing and Li Xiao-Yan and Zhao Guobin
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Shorter Is Not Cheaper: A Controlled Comparison of Declarative Animation Specifications and Free-Form Code for LLM-Generated Explanations

**链接**: https://arxiv.org/abs/2610.32129
**作者**: Jiantang Huang
**来源**: cs.CL cs.HC cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chat assistants increasingly answer conceptual questions with interactive, animated explanations, generated either as free-form HTML/JavaScript or as declarative specifications that a fixed runtime plays. The declarative route is widely expected to be cheaper, faster and more reliable, because its outputs are shorter and constrained. We test this expectation in controlled comparisons whose hypotheses and analysis plans were frozen before the runs. We designed ExplainSpec, a time-indexed declarative animation format, and an observation contract that makes every generated explanation programmatically inspectable; validated, pacing-agnostic checkers score 20 explanation requests from five domains. Three Claude models (360 jobs) and, in a follow-up, the open-weight Qwen3-14B with thinking enabled and disabled (240 jobs) answered every request in both formats. For every model the specifications were 25-48% shorter in answer tokens (output excluding reasoning), yet with reasoning enabled tot

---

### [35] Behaviour analysis for large language model-driven agents

**链接**: https://arxiv.org/abs/2610.32087
**作者**: Tianqiang Yan and Lizhen Qu
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding language-agent behaviour requires learning how actions are organised across a trajectory and how this organisation relates to context and outcomes. We propose a general framework that connects data-driven behavioural discovery with analysis and experimental investigation. Categories developed from recorded activity define what is measured. Analyses preserve the behaviours' positions in the process and express their relationships as interpretable hypotheses. Statistical assessment and tests in held-out contexts examine the strength and scope of the evidence. Experiments, including prompt steering, then test how behaviour and outcomes change under deliberately varied conditions. A study of iterative self-reflection illustrates how discovery, dependency learning and prompt comparisons can inform one another. We develop this approach for trajectories of varying length, event order and agent roles, and identify advances in coding, analysis and experimentation needed to support

---

### [36] Democratizing LLM Training with the Edge: Challenges, Systems, and the Road Ahead

**链接**: https://arxiv.org/abs/2610.32215
**作者**: Ziyue Luo, Jiaxuan Cai, Cedric LeDenmat, Srijith Nair, Fatemeh Nourzad, Rohith Krishnan 等 (10 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing computational power of modern GPU data centers has let a few industrial giants train and deploy large language models (LLMs) on massive amounts of data. Yet the sheer scale of these models and their training data makes centralized development increasingly hard to sustain, and at the same time shuts out smaller institutions that hold relevant private data but lack comparable infrastructure. In this paper, we organize our positions on distributed LLM training around the pretraining and fine-tuning paradigms, covering federated learning, split learning, and decentralized approaches, and we assess their readiness for geo-distributed settings with heterogeneous hardware and unreliable connectivity. We then present a {\em unified} system architecture built around a cloud-hosted parameter server that coordinates heterogeneous clients over outbound gRPC connections, reusing one communication, compression, and fault-tolerance stack for both pretraining and a family of fine-tuning me

---

### [37] Towards robust long-context understanding of large language model via active recap learning

**链接**: https://arxiv.org/abs/2601.13734
**作者**: Chenyu Hui
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] Tampered ML: Evaluating LLM Judgment of Machine Learning Research

**链接**: https://arxiv.org/abs/2610.32114
**作者**: Soroush Ebadian, Parand A. Alamdari, Joe Benton, Hailey Joren
**来源**: cs.CL cs.AI cs.DL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> One approach to accelerating progress on AI alignment is to automate parts of alignment research itself. Doing so requires systems that can perform reliably on hard-to-supervise research tasks, including identifying flaws in research proposals and evaluating whether a proposed experiment supports its intended claim. To evaluate this capability, we introduce Tampered ML, a benchmark of 1,858 item-pairs, each consisting of an experiment proposal reconstructed from a published machine learning paper and a minimally edited counterfactual that introduces a targeted methodological flaw. Models must identify the more methodologically sound proposal in both presentation orders. A human validation study on a stratified sample estimates that 86% of items are valid (95% CI: 81-91%). Frontier models perform above chance but remain far from reliable (with Opus 5 achieving 77.9% accuracy). They are highly sensitive to the order of presentation and favor flawed designs that appear more specific, tran

---

### [39] Where Rounding Happens Matters: Rounding-Location Alignment Stabilizes LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.32951
**作者**: Yijing Ke, Tianle Cai, Ruosong Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning for large language models often uses separate systems for inference and training. Even with identical weights and BF16 tensors, implementation differences can make an intended on-policy update off-policy and destabilize training. Existing remedies align the entire inference and training stacks, change global precision, or modify the learning algorithm. We ask whether aligning selected parts of the execution stack can stabilize BF16 RL while other implementation differences remain. We align training-side rounding locations with inference in three regions---RoPE, SwiGLU, and residual RMSNorm---by retaining selected intermediates in FP32 until their BF16 outputs. Across four Qwen-family models, aligning all three regions prevents the collapse observed under the default BF16 baseline; RoPE-path alignment alone also suffices in the studied runs, despite remaining numerical discrepancies. The interventions keep the inference engine, matrix-multiplication and attention 

---

### [40] BabelArena: A Large-Scale Multilingual Benchmark for LLM Agents

**链接**: https://arxiv.org/abs/2609.23490
**作者**: Peng Kuang, Yuchun Fan, Jiangnan Li, Minghao Wu, Jialong Tang, Hao-Ran Wei 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Beyond On-Policy vs. Off-Policy: At What Level Should LLM Agent Distillation Follow the Student?

**链接**: https://arxiv.org/abs/2610.31918
**作者**: Ya Gao, Zhengtao Zou, Pekka Marttinen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distilling interactive LLM agents requires choosing between teacher-generated demonstrations and student-generated experience, corresponding broadly to off-policy and on-policy distillation. While both have proven effective, we argue that this distinction is inherently hierarchical: the policy that induces an interaction history need not be the same as the policy that generates the token prefix of the current action. We introduce a hierarchical agent distillation framework that formalizes these two levels of on-policiness and enables explicit control over their pairing, mixture proportions, and training schedule. We study this problem through self-distillation, where a frozen teacher has access to task guidance unavailable to the student, and conduct a three-stage controlled study across three models and four interactive environments. We find that student-induced histories paired with teacher-generated action prefixes generally provide the strongest standalone training signal, whereas 

---

### [42] Green Code or Costly Code? Evaluating the Energy Costs of Iterative LLM-Based Code Optimizations

**链接**: https://arxiv.org/abs/2610.32891
**作者**: Sadra Emami, Benjamin Weigell, Mohammad Reza Mousavi, Gunel Jahangirova, Hugo Araujo, Bernhard Bauer
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used to optimize code for performance. This practice often assumes that improvements in execution speed naturally translate into overall lower energy consumption. We challenge this assumption empirically by measuring whether performance-optimized code produced by LLM self-refinement pipelines is also energy-efficient relative to canonical human reference solutions, and whether the energy cost of the optimization process can be offset by subsequent execution-time savings. We evaluate 11 open-source models across four decoding configurations on all 1,000 problems of EffiBench, a state-of-the-art performance benchmark, while collecting per-process, hardware-level energy measurements throughout. Inference energy spans 0.79 to 8.68 MJ across model-variant pairs, which is roughly equivalent to the energy of 250 to 2800 GPT-4.1 queries. Limiting the maximum number of output tokens has the largest impact, reducing energy use by up to 69% compared t

---

### [43] Persona-Guided LLM Agents for Task-Oriented Dialogue

**链接**: https://arxiv.org/abs/2608.18085
**作者**: Maryam Shoaeinaeini, Brent Harrison, A.B. Siddique
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] CauProphet: Teaching Agents to Develop Causal Cognition like Humans

**链接**: https://arxiv.org/abs/2610.32477
**作者**: Kaiwen Wu, Chaochao Lu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly support long-horizon tasks by leveraging external memory and past experience. However, existing agents mainly retrieve records or summaries, lacking the ability to form and refine causal understanding of the world. Inspired by human causal cognition, we introduce CauProphet, an agent that develops and updates causal knowledge within its Causal Cognition. For each task, CauProphet combines relevant knowledge in Causal Cognition with current evidence to construct a Causal Belief, a structured belief capturing causal factors and the effects of possible actions. It uses this belief for decision-making and continuously updates both the belief and Causal Cognition as new observations emerge, enabling causal knowledge that persists beyond individual experiences. Evaluations demonstrate that CauProphet progressively acquires causal knowledge and transfers it to future decision-making. In financial research, CauProphet leverages prior discoveries t

---

### [45] Beyond Data Schedule: Fast LLM Pretraining on Data Mixtures by Loss-Reweighting

**链接**: https://arxiv.org/abs/2610.32141
**作者**: Jiazheng Li, Huaqing Zhang, Jing Xu, Tianle Cai, Jingzhao Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models often acquire specialized capabilities through successive pretraining stages, but these gains can come at the cost of forgetting earlier knowledge. In this work, we investigate whether such trade-offs can be improved by changing how strongly each domain contributes to learning while keeping its data exposure fixed. We find that, in controlled knowledge--mathematics experiments, loss reweighting produces a single checkpoint that surpasses the best knowledge and reasoning scores attained along either stage trajectory. This reveals an independent control that data-mixture ratios alone do not capture. Building on this finding, we propose LARE (Loss-Adaptive Reweighting under fixed Exposure), which automatically adjusts domain weights from running loss statistics. Motivated by a theoretical analysis of gradient noise, its normalized inverse-square-root rule balances relative loss scales without changing the sampled mixture or requiring additional runs to search for wei

---

### [46] Contextual Memory Virtualisation: DAG-Based State Management and Structurally Lossless Trimming for LLM Agents

**链接**: https://arxiv.org/abs/2602.22402
**作者**: Cosmo Santoni
**来源**: cs.SE cs.AI cs.HC cs.OS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Model-Adaptive Tool Necessity Reveals the Knowing-Doing Gap in LLM Tool Use

**链接**: https://arxiv.org/abs/2605.14038
**作者**: Yize Cheng, Chenrui Fan, Mahdi JafariRaviz, Keivan Rezaei, Soheil Feizi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] SCI-AGENT-EXAM: Benchmarking Agents on Scientific Research Tasks

**链接**: https://arxiv.org/abs/2610.32441
**作者**: Tianyun Zhong, Wei Wang, Jialin Li, Jianhong Tu, Liyao Li, Chuqiao Kuang 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly capable of supporting scientific workflows, but their capabilities across diverse research activities remain difficult to assess systematically. Existing benchmarks often focus on selected scientific capabilities or task types, limiting a comprehensive characterization of scientific agents' strengths and weaknesses in realistic research workflows. We introduce SCI-AGENT-EXAM, a workflow-oriented benchmark comprising 120 expert-curated tasks across 11 scientific fields and 7 research task types defined by the Scientific Workflow Task Taxonomy (SWTT). Each task requires both executable artifacts (e.g., code and scripts) and textual artifacts (e.g., reports and explanations). To evaluate the heterogeneous task outputs, we develop a hybrid evaluation protocol combining deterministic programmatic verification for executable artifacts with a calibrated, expert-validated LLM-based judge for textual artifacts. Beyond outcome assessment, we ana

---

### [49] Understanding Communication Failures in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2610.32060
**作者**: Priya Pitre, Jun Hou, Yi Fang, Naren Ramakrishnan, Xuan Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems aim to improve reasoning through debate, evidence sharing, and mutual correction, but interaction can also introduce failures that final accuracy alone cannot explain. Agents may converge too early, ignore dissent, suppress correct minority answers, or preserve a wrong framing across rounds. We present a corpus-grounded taxonomy of communication failures, built from 3,211 failed multi-round trajectories across medical QA, coding, finance, multi-hop reasoning, ethics, and embodied text tasks. Using this taxonomy, we analyze failure distributions across datasets and system designs, round-level error dynamics, recovery hardness, majority transitions, minority-signal suppression, and self-reported confidence. We find that failures are dominated by recovery/correction and consensus/decision problems rather than isolated first-round mistakes, with many emerging after agents first observe peer responses. Based on these findings, we recommend stronger disagreement handl

---

### [50] Omni-UBench: Benchmarking Omni-Modal LLM-based Guardrails Across Safety, Utility, and Reliability

**链接**: https://arxiv.org/abs/2610.31713
**作者**: Junhao Wang, Yidou Chen, Li Lu, Hongwei Yao, Xiaodan Li, Mengjie Wu 等 (9 人)
**来源**: cs.CR cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in Omni-modal Large Language Models (OLLMs) have enabled increasingly seamless human-AI interaction, but their unified processing of heterogeneous modalities also expands the attack surface, allowing adversaries to exploit richer input compositions to circumvent safety alignment. To counter such risks, omni-modal guardrails have been proposed to detect and filter unsafe queries across arbitrary modalities. However, their capabilities and limitations remain insufficiently understood due to the absence of a comprehensive evaluation benchmark. In this paper, we present Omni-UBench, the first comprehensive framework for omni-modal safety assessment, evaluating guardrail models along three critical dimensions, i.e., safety, utility, and reliability. Omni-UBench curates over 183k samples drawn from 35+ heterogeneous sources spanning text, image, audio, video, and their cross-modal combinations, annotated with safety labels under a unified risk taxonomy. Benchmarking under Omni-UBenc

---

### [51] Beyond Final Outcomes: Quantifying Claim-Level Information Dynamics in Multi-Agent LLM Interaction

**链接**: https://arxiv.org/abs/2610.32333
**作者**: Haocheng Jiang, Herun Wan, Yongyuan Peng, Minnan Luo
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When LLM-powered agents interact, information is repeatedly shared, expanded, and forgotten, yet multi-agent evaluation typically focuses on final task outcomes. We study such interaction as claim-level information dynamics and propose RIVER, which decomposes agent outputs into atomic claims and evaluates three complementary dimensions: convergence, exploration, and retention. Convergence captures cross-agent claim correspondence and stance alignment; exploration captures semantic breadth and extension beyond the source; and retention tracks source preservation and the persistence of new claims across stages and lineages. We evaluate five interaction strategies on 40 controlled news-generation cases. Repeatedly pooled interaction promotes convergence but narrows the information space, whereas distributed relay yields broader, less shared information. Further comparisons show that method-specific constraints increase exploration while weakening convergence and retention. Our findings su

---

### [52] SANE: Automated Scorer-Specific Metamorphic Testing for LLM Judges

**链接**: https://arxiv.org/abs/2610.28886
**作者**: Ethan Ludwick, Yu-Chung Hsiao
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Under the Influence: Evaluating and Improving LLM Vigilance in Agentic Tasks

**链接**: https://arxiv.org/abs/2602.21262
**作者**: Sasha Robinson, Katherine M. Collins, Ilia Sucholutsky, Kelsey R. Allen
**来源**: cs.CL cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] TGR-EvoDAG: A DAG-based Multi-Agent Code Evolution Framework for Generative Recommendation on Tencent

**链接**: https://arxiv.org/abs/2610.32326
**作者**: Junlin He, Junzhang Zhu, Yudong Li, Yihong Tang, Xuefeng Jiang, Wei Ma 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents have enabled automated code evolution for algorithm discovery. However, current recursive self-improvement (RSI) research for sequential recommendation faces a dilemma: general-purpose frameworks lack domain-specific feedback, while recommender-specific frameworks rely on linear evolution. Crucially, naively integrating them fails when applied to Generative Recommendation (GR). Unlike end-to-end models, GR relies on a module-cascaded pipeline (tokenization, pre-training, and alignment). In this paradigm, existing evolution methods suffer from: i) cost blindness, squandering budgets by ignoring stage-asymmetric retraining overheads; and ii) short-sighted evaluation, discarding promising upstream innovations that temporarily regress metrics before downstream adaptation. To bridge these gaps, we propose TGR-EvoDAG, a multi-agent code evolution framework tailored for GR. TGR-EvoDAG models code evolution as a Directed Acyclic Graph (DAG) to maintain multipl

---

### [55] Before the Ticket: Grounding HPC User Support in Documentation and Resolved Tickets with an Agentic LLM Assistant

**链接**: https://arxiv.org/abs/2610.31703
**作者**: Elham J. Barezi, Primus C Kabuo, Niveditha Nerella
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most questions that reach an HPC help desk have already been answered in the center's user guides or in a ticket someone else filed last semester; users still file new tickets because the guides are hard to navigate and the ticket history is not theirs to search. We present an assistant that answers from both sources: an orchestrator calls two tools over the Model Context Protocol, retrieval-augmented generation (RAG) over the live documentation and a Llama-3-8B model fine-tuned with QLoRA on 11,244 query-resolution pairs mined from historical tickets, and merges their answers. Every model runs on-premises or on the university's hosted LLM service because ticket data may not leave the institution. On 400 held-out tickets from Purdue's Rosen Center for Advanced Computing, disjoint from training and free of near-duplicates, and evaluated by two judges from model families that generated none of the answers, fine-tuning on resolutions rewritten into self-service guidance is the clear winne

---

### [56] Validating the Comparison, Not Just the Scorer: Why Overall Accuracy Can Mislead in Interactive LLM Evaluation

**链接**: https://arxiv.org/abs/2610.31678
**作者**: Ancil Crayton
**来源**: cs.CL cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many LLM studies compare how models respond to different follow-up prompts. For example, one prompt may neutrally ask a model to reconsider, while another insists that an invented film really exists. The difference is used to measure the effect of conversational pressure. An automatic scorer then labels whether each response makes an unsupported factual claim. Researchers commonly validate the scorer with one overall accuracy or $F_1$ score. However, high overall performance can hide prompt-specific mistakes: if the scorer makes more errors after one prompt, the measured difference can be too large, too small, or point in the wrong direction. An audit containing mostly difficult responses can also misrepresent performance in the full study. We derive how such errors alter a prompt comparison and examine the problem using six models, 180 invented-entity questions, and six prompt conditions. In a balanced audit of 288 responses, overall $F_1$ was $.916$. Yet, depending on the prompt, the

---

### [57] Symbolic Guidance for LLM Agents in Distributed Multiagent Coordination

**链接**: https://arxiv.org/abs/2609.31963
**作者**: Ben Rachmut, Ning Zhang, Yevgeniy Vorobeychik, William Yeoh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] The Butterfly Defects: Tracing Cooperation in LLM Agent Networks

**链接**: https://arxiv.org/abs/2610.32726
**作者**: Maria Sampani, Maria Lymperaiou, Angeliki Dimitriou, Giorgos Filandrianos, Chrysoula Zerva, Giorgos Stamou
**来源**: physics.soc-ph cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) increasingly operate as interconnected agents, a fundamental question emerges: does individual cooperation translate into collective cooperation? We investigate this question through the Iterated Prisoner's Dilemma (IPD), moving from dyadic interactions to homogeneous and heterogeneous networks of open-weight LLMs. Our findings reveal that cooperation is highly sensitive to model composition and seemingly minor linguistic changes. Models that cooperate with identical peers can shift toward defection in mixed populations. A simple uncertainty cue can increase or decrease cooperation, redistribute costs, and affect unexposed agents several hops away. Even reversing action-label order can dramatically alter behavior, with uncertainty framing sometimes amplifying this sensitivity. Together, these findings challenge the notion of cooperation as a stable model-level property, revealing how strategic behavior depends on interaction partners, network positions, 

---

### [59] Can LLM Annotators Match Human Consistency? Benchmarking Human Agreement and Optimizing Multi-Agent with Contrastive Knowledge

**链接**: https://arxiv.org/abs/2610.32415
**作者**: Xiaopeng Ke and Zhixin Wang and Xuebo Liu and Xinyu Ma and Xing Zheng and Bowen Song and Weiqiang Wang and Min Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based annotation has advanced rapidly, yet existing benchmarks remain misaligned with real-world practice. Actual annotation often involves lengthy, task-specific guidelines, and different annotators may produce divergent but reasonable judgments, especially on boundary cases, where single-labeled dataset fail to reflect this disagreement. This gap also limits existing single-agent and workflow-based annotation systems, which often lack adaptability to complex, evolving guidelines. To bridge this gap, we introduce ANT-A Benchmark, a real-world multi-annotator benchmark spanning 7 datasets across domains and modalities, with task-specific guidelines and 5 independent human labels per instance. ANT-A enables a distribution-aware evaluation, using Fleiss kappa to assess how closely model annotations align with human labeling distributions. We further propose ANT-OR, a multi-agent annotation framework that refines prompts by distilling contrastive decision rules from positive and negat

---

### [60] Do "True" and "False" Add Up to One? Complement Consistency in LLM-Agent Opinion Simulations

**链接**: https://arxiv.org/abs/2610.32874
**作者**: Anouar Imel, Jin Qi
**来源**: cs.AI cs.CL cs.MA cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM-agent opinion simulations, each agent reports the probability that a claim is true after seeing its own previous probability and the probabilities reported by its neighbors, and that number becomes its state in the next round. If the number describes the agent's position rather than the sentence it was shown, then rewriting the claim as its complement and replacing every probability p with 1 - p should return the complementary answer, so the two reports should sum to one. We test this with three small open models: Qwen3-4B, Llama-3.2-3B and Gemma-3-4B. On 2,304 agent states taken from a running network simulation, Qwen's paired reports sum to 1.18 on average, and on 48 real fact-checking claims from AVeriTeC they again exceed one. A controlled benchmark of 24 worlds, each with exactly two possible outcomes, shows the same failure in all three models. The discrepancy is two to ten times larger than the change produced by a same-meaning paraphrase, and it persists under repeated s

---

### [61] Mining the Design Space of Multi-Agent Workflows

**链接**: https://arxiv.org/abs/2610.31709
**作者**: Xavier Cadet, Junyan Cheng, Peter Chin, Kyle Richardson
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing large language model (LLM) multi-agent systems (MAS) still relies on trial and error and informal "folk wisdom." Manual studies test only a few communication structures or topologies (e.g., sequential, parallel, shared-memory, or debate), while automated optimizers discard search trajectories after selecting a task-specific workflow. We present a two-phase pipeline for mining reproducible design principles from workflow code and execution traces. We repurpose AFlow's MCTS optimizer across six composable operators and 26 deterministically verified Enigmata tasks, retaining all intermediate rounds to build a corpus of 28,568 executable workflows. A sandboxed AutoResearch loop then mines orchestration code and prompt templates under an $L_0$-penalized validation objective and tests candidate principles on held-out searches. Across 300 feature-mining trials, we identify effects that persist on held-out searches across three levels of workflow design: workflows beginning with inde

---

### [62] ProCLIP: Progressive Vision-Language Alignment via LLM-based Embedder

**链接**: https://arxiv.org/abs/2510.18795
**作者**: Xiaoxing Hu, Kaicheng Yang, Ziqi Ye, Ziyang Gong, Qi Ming, Zonghao Guo 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] VETTA: Coordinating Turn- and Token-Level Credit Assignment for Multi-Turn LLM Agents

**链接**: https://arxiv.org/abs/2610.08402
**作者**: Jiaju Chen, Min Yang, Jinghua Piao, Xiaochong Lan, Xu Xia, Xiangnan He 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] AgentPerturb: Evaluating LLM Agent Robustness under Controlled Interaction Perturbations

**链接**: https://arxiv.org/abs/2610.21624
**作者**: Yuanjian Xu, Jinyi Han, Jianing Hao, Yuxuan Sun, Fanyang Lu, Richeng Xuan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Tool-Calling LLM Agents Under Realistic MCP Faults: Scale Does Not Purchase Fault Tolerance

**链接**: https://arxiv.org/abs/2610.32555
**作者**: Antonio Ken Iannillo, Joshua Segun Owotogbe, Roberto Natella, Francesco Avallone, Kristina Kudryavtseva, Indika Kumara
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on external tools exposed via the Model Context Protocol (MCP), yet current benchmarks assume tools respond correctly and on time, leaving agent resilience to realistic tool failures untested. We introduce MCP-Injector, a drop-in, protocol-aware fault-injection middleware that interposes on the MCP tool-call path with controlled persistence (permanent, transient, intermittent) and seedable schedules. Its fault model is calibrated to the observed incident distribution (failure mode x persistence) of the public MCP ecosystem, mined from 57,240 issue and pull-request threads across 1,774 open-source MCP repositories. In a 1,350-cell experiment crossing two backbone sizes (20B, 120B), three agent stacks (custom multi-round plan-and-execute, OpenAI Agents SDK, LangChain), and three fault injection conditions, we find that faults drawn from this permanent-heavy stress profile cause severe quality degradation (task-completion score falls by 60%, from 8.08 to 3.23 

---

### [66] Where Cross-Question Structure in LLM Errors Comes From: Shared Seeds, Shared Prompts, and Answer-Letter Preference

**链接**: https://arxiv.org/abs/2607.20464
**作者**: Izhar Ali
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Interchangeable in Role, Not in History: Replacing Members of Formed LLM Teams

**链接**: https://arxiv.org/abs/2609.05279
**作者**: Jianxin Gao, Runze Li, Tianyi Yu, Liangwei Ren, Bohan Chen, Zining Wang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Cluster, Route, Escalate: Cascaded Framework for Cost-Aware LLM Serving

**链接**: https://arxiv.org/abs/2606.27457
**作者**: Yasmin Moslem, Magdalena Kacmajor, Vasudevan Nedumpozhimana, Ammar Abbas, Solmaz Panahi, David Lynch 等 (10 人)
**来源**: cs.PF cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Political sense-making in "individual" human-technology-world relations: the case of LLM-generated autobiographies

**链接**: https://arxiv.org/abs/2610.32594
**作者**: Anthony Longo and Olya Kudina
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI systems increasingly mediate how people describe, recognize, and present themselves, their politics cannot be reduced to what remains hidden inside the "black box." This chapter argues that AI's political significance emerges within technologically, intersubjectively, and temporally mediated interpretive practices. Bringing Arendt's political philosophy into conversation with Gadamerian hermeneutics, the chapter develops a postphenomenological relational-temporal account of political sense-making across Human-Technology-World relations. Against the charge that postphenomenology remains individualistic and using the case of LLM-generated biographies, the chapter shows how seemingly private human-LLM encounters are worldly and collective. When users ask systems such as ChatGPT to describe them, they do not simply receive algorithmic representations. They interpret, contest, edit, share, and publicly test these descriptions. In doing so, people move interpretively among affective re

---

### [70] AgentTrace: Execution-Level Fingerprinting of Black-Box LLM Agents

**链接**: https://arxiv.org/abs/2610.32092
**作者**: Gejian Zhao, Hanzhou Wu, Xinpeng Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verifying the provenance of autonomous LLM agents is a critical security challenge. Existing semantic attribution is easily obfuscated by system prompts, while active watermarking conflicts with schema-constrained tool generation. We propose AgentTrace, an active framework that identifies the foundation model behind a black-box agent via observable execution traces. AgentTrace injects structurally ambiguous probes to trigger tokenization-sensitive serialization failures at rigid tool interfaces. While these initial failures provide coarse-grained separation across model families, the temporal sequence of subsequent repair operations reveals fine-grained, model-specific recovery behaviors. By modeling these multi-step trajectories with lightweight Markov chains, AgentTrace achieves 96.0% attribution accuracy under adversarial identity spoofing. Crucially, sequential repair modeling successfully distinguishes the evaluated intra-family variants sharing identical tokenizers (e.g., Llama-3

---

### [71] Training an MoE LLM in MXFP4: How We Closed the Gap to BF16

**链接**: https://arxiv.org/abs/2610.32229
**作者**: Han Wang, Zhitao Wang, Natalia Frumkin, Xuanwu Yin, Alireza Khodamoradi, Dong Li and Emad Barsoum
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training large language models (LLMs) in sub-8-bit arithmetic promises substantial gains in memory bandwidth and compute throughput, yet FP4 formats introduce quantization error severe enough to destabilize optimization if left unaddressed. We present ALTO, an open-source training recipe for GPT-OSS-20B, a 20-billion-parameter mixture-of-experts (MoE) model, on the MLPerf Small MoE Training benchmark under the MXFP4 microscaling format. The recipe combines established techniques from Abecassis, Felix et al. [

---

### [72] The Helpful Agent Problem: When Emergent Cooperation Among LLM Agents Bypasses Intended Workflows

**链接**: https://arxiv.org/abs/2610.31985
**作者**: Moumita Choudhury, Amit Sarker, Shlomo Zilberstein
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly deployed in collaborative settings where they pursue separate tasks while sharing resources and operating under review or oversight processes. Such settings create safety risks not only when agents are malicious, but also when they are simply trying to help. Prior work has largely studied adversarial or explicitly collusive behavior; we show that benign agents pursuing separate objectives can spontaneously cooperate in ways that bypass intended workflows. We call this the \emph{helpful agent problem}. We study long-horizon shared-resource environments in which agents sometimes depend on resources owned by their peers and cross-owner changes are normally mediated by a reviewer. When review becomes unavailable, agents begin making changes on one another's behalf despite having no shared reward or explicit incentive to cooperate. Crucially, these actions remain within each agent's local permissions while circumventing the system's intended oversight structure. 

---

### [73] FSVL: Taxonomic Fast-Slow Vision-to-Language Collaborative Framework for Interpretable Confusable Fish Species Identification and Knowledge Generation in the Middle Yangtze River

**链接**: https://arxiv.org/abs/2610.31880
**作者**: Meng Liang, Fucheng Wang, Lang Zhao, Jun Chen, Ziying Li, Yuxiang Zhao 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Yangtze River Basin is a critical region for freshwater biodiversity conservation. The implementation of the Yangtze River Ten-Year Fishing Ban has increased the importance of effective aquatic biodiversity monitoring and species-level identification. However, fine-grained identification of closely related freshwater fish species remains challenging due to subtle morphological differences. Existing deep learning methods often struggle to balance classification accuracy and inference efficiency, while LLMs may generate unsupported information when producing specialized biological knowledge. To address these challenges, this study proposes FSVL, a fast-slow dual-pathway framework integrating visual recognition with LLM-based Retrieval-Augmented Generation (RAG). A lightweight ResNet50 fast path performs preliminary classification across 51 fish species in the Middle Yangtze River Basin and routes predefined groups of easily confused species to a slow path for refined identification. 

---

### [74] Phronix: The Capability-Centric Learning Paradigm for Agents

**链接**: https://arxiv.org/abs/2610.31789
**作者**: Hariharan Devarajan, Neeraj Rajesh, Aniruddha Marathe, Nikoli Dryden, Kin Ng, and Michela Taufer
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific computing increasingly relies on large language model-based agents for performance engineering tasks such as instrumentation, analysis, and workflow porting. However, agent effectiveness depends heavily on the surrounding harness, which typically relies on manually written skills and curated memory. This limits autonomous learning, forcing agents to repeatedly rediscover solutions rather than retain and reuse knowledge from prior executions. We introduce Phronix, a capability-centric learning paradigm that enables agentic harnesses to acquire, validate, and refine reusable capabilities from their own executions. Phronix operates through a predictor-validator-corrector loop: MCP tools and associated skills propose solutions, tool executions validate them, and observed outcomes refine the stored capabilities. It distills every observed interaction into a capability store and researches a failing task rather than abandoning it. First, such learned capabilities solve a recurring

---

### [75] Benchmarks Are Surprisingly Compaction-Friendly

**链接**: https://arxiv.org/abs/2610.31778
**作者**: Jeanne Salle, Hardik Bhatnagar, Matthias Bethge, Sahar Abdelnabi, Maksym Andriushchenko
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long horizon agentic tasks are now pushing LLM agents past their context window. To continue the task, the agent scaffold has to free up the context window, a process known as context compaction. Compaction is generally lossy by design: agents can silently lose task constraints, instructions, or their reasoning behind earlier decisions. Although compaction is a standard component of coding agent scaffolds, it has not been studied systematically with frontier models on realistic, long horizon agentic tasks. Previous work evaluate smaller open weight models on toy or synthetic trajectories. We fix the agent scaffold (OpenCode), implement five compaction strategies inside it, and evaluate three frontier models on three long horizon benchmarks (PaperBench, ProgramBench, PostTrainBench). For the two 1M context models, the compaction threshold does not measurably affect the task performance, whereas GPT-5.3-Codex, the model with the smallest context window, performs worse at lower thresholds

---

### [76] MBABench-2.0: Evaluating AI Agents on Constructing Financial Spreadsheets Beyond Simple Verifiability

**链接**: https://arxiv.org/abs/2610.31711
**作者**: Julian Poeltl and Thomson Yen and Patrick Shea and Shubham Anil Varma and Dhruv Rastogi and Zihao Chen and Mengshi Zhang and Hongseok Namkoong
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spreadsheets are the lingua franca of modern finance, driving valuation, forecast, audit, and many other core workflows of the industry. As LLM agents advance to automate knowledge work, spreadsheet construction is a natural and pertinent testbed. However, most existing spreadsheet benchmarks evaluate agents on fill-in-the-blank style tasks, where an agent performs minor edits in otherwise complete spreadsheets. This protocol fails to capture the most central and time-consuming part of the spreadsheet workflow: the modeling decisions, format design, and sheet layout regular knowledge workers need to toil through to build a workbook from scratch. We introduce MBABench-2.0, a benchmark of 101 original spreadsheet construction tasks, the hardest of which is estimated to take 33 hours for a modeler with 3+ years of experience. Unlike coding or math, where a unit test or a final answer can verify an agent's output, the quality of a financial spreadsheet that concerns readability, maintainab

---

### [77] DMAIC-Bench: From Self-Reflection to Self-Restraint for Agents in Multi-Stage Analytical Tasks

**链接**: https://arxiv.org/abs/2610.32305
**作者**: Shan Peng, Shuaiqi Cheng, Miao Peng, Chenyi Zi, Jia Li
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-stage analytical tasks require LLM agents to use intermediate evidence to decide whether to continue, redirect or stop. Self-reflection, in which an agent critiques its output, is widely studied, yet a critique does not show whether evidence changed the next action. We call that capability self-restraint. Existing agent benchmarks largely measure task completion or output quality and leave it untested. DMAIC-Bench evaluates it with 97 seeded tasks across 15 industrial cases in four sectors, built around Lean Six Sigma's explicit statistical prerequisites. Paired counterfactual variants require opposite actions at the same workflow position, distinguishing warranted restraint from indiscriminate stopping. We assess execution traces with a private scorer and final claims through independent expert review. Across 13 models from six providers, execution-level routing accuracy averages 92% on matched GO decisions and 19% on NO-GO decisions, counting any forbidden downstream computatio

---

### [78] Trial by Trace: Benchmarking AI Agent Harnesses for Reliability and Failure Attribution

**链接**: https://arxiv.org/abs/2610.32285
**作者**: Zhiyong Cao, Hengjie Zhu, Yongxin Wang, Xuchen Li, Jintao Li, Shuxia Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used to solve real-world problems, and their effectiveness depends on both the underlying models and the harnesses that support their operation. However, most existing benchmarks focus on model capabilities and overall agent performance, with limited attention to the evaluation of agent harnesses. To address this gap, we introduce TraceTrial-Bench, which organizes harness reliability into seven components covering context, execution, governance, lifecycle, observability, tools, and verification. We construct 95 expert-level, mechanism-oriented tasks with executable or state-based ground truth to support semantically equivalent comparisons while preserving the native behavior of each harness. We design a Trajectory Tracing (TT) module to capture agent execution traces and introduce a two-layer evaluation framework that separately assesses agent performance and harness reliability. In addition, we design a Multi-source Evidence Acquisition (MEA) module to prov

---

### [79] When Agents Fail: Model or Harness--Who's to Blame?

**链接**: https://arxiv.org/abs/2610.32483
**作者**: Shao Zhang, Hangfan Zhang, Yuanyuan Shi, Hao Li, Min-Le Su, Kangcong Li 等 (10 人)
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents combine models with execution harnesses, so agentic benchmark performance reflects their joint behavior. We argue that harnesses should therefore be evaluated through their interactions with underlying models. We develop a framework combining five complementary measures: (i) Valid Completion Rate (VCR), how reliably agents finish normally and deliver evaluable results, irrespective of task correctness; (ii) Model-Harness Fit, how well a harness supports task achievement through valid completion for a given model; (iii) Cross-Model Fit, a harness's overall suitability across evaluated models; (iv) Interaction Residuals, pairing-specific execution strengths and weaknesses hidden by component-level summaries; and (v) Token Load, the token demands of agent execution, including failed attempts. We evaluate four general-purpose harnesses (OpenCode, Codex CLI, Pi CLI, and DeepAgents) with four core models, plus two fixed native model-harness systems, on six benchmarks covering cont

---

### [80] Decoupling Patient Personas and Clinical Workflows: A Dual-Agent Approach to Realistic Medical Dialogue Generation

**链接**: https://arxiv.org/abs/2610.32443
**作者**: Qiyuan Li and Xiaomei Guo and Chao Gao and Haijiang Liu and Deyu Chen and Caicai Guo and Jinguang Gu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pre-consultation medical dialogues are essential for collecting comprehensive patient information, but are costly to obtain at scale due to privacy and ethical constraints. Existing LLM-based synthesis methods often rely on prompt engineering or rigid rules, limiting their ability to balance clinical relevance with realistic patient diversity. We propose CoRPS-Dial, a controllable dual-agent framework for pre-consultation medical dialogue synthesis that integrates patient personas with guideline-aligned clinical workflow rules. CoRPS-Dial generates dialogues through interactions between a persona-driven patient agent and a process-guided doctor agent, followed by post-hoc quality control for role consistency, workflow completeness, and textual consistency. Experiments on coronary heart disease demonstrate that CoRPS-Dial improves alignment between synthetic and real dialogues in information coverage, clinical compliance, and dialogue naturalness. Downstream fine-tuning experiments furt

---

### [81] Semantically Rich, Metrically Affect-Blind: A Geometric Blind Spot in Modern Text Embedders

**链接**: https://arxiv.org/abs/2610.32122
**作者**: Mahdi Naser Moghadasi
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We report a systematic dissociation in modern text embedders: sentiment is almost perfectly decodable from their embeddings, yet almost entirely absent from their metric. Across eleven frozen encoders spanning 2021 to 2026, including 2026-generation models and the 4B-parameter LLM embedder Qwen3-Embedding-4B, a linear probe recovers sentence polarity at up to 91.3% accuracy while cosine similarity separates polarity by a margin of only 0.003-0.064. Qwen3-Embedding-4B, the strongest probe in the panel, reaches 91.3% probe accuracy but only 64.3 retrieval MAP. Because retrieval, clustering, deduplication, and retrieval-augmented generation operate on the metric rather than on a trained probe, these systems are effectively blind to information their encoder demonstrably contains. A task-conditioning control suggests this reflects the pretraining objective rather than a prompting artifact: conditioning Jina-v5 on its classification task rather than its retrieval task recovers only about ha

---

### [82] From Noisy Retrieval to Decision Evidence: Silver Evidence Demonstrations for In-Context Learning

**链接**: https://arxiv.org/abs/2610.32128
**作者**: Masoud Monajatipoor, Fazlolah Mohaghegh, Hamid Reza Hassanzadeh, Akash Uttamrao Bhoite, Robert E. Tillman
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> RAG and retrieval-augmented few-shot ICL can struggle when decision-relevant evidence is buried in long, noisy context. Retrieved passages and demonstrations may contain redundant or distracting information. Although expert-labeled development examples may identify the text supporting each decision, these annotations are typically used only as answer-side rationales rather than as supervision for filtering noisy retrieval. We propose silver-evidence demonstrations, which replace raw retrieved passages in ICL examples with generated, target-conditioned evidence summaries. For each labeled development example, an LLM generates silver evidence without access to the expert label or gold evidence; this evidence is then paired with the expert label and gold evidence where available. At test time, a single structured call generates silver evidence from retrieved passages and then predicts the final label and decision evidence. Across EI 2.0, SciFact, synthetic policy retrieval, and HICRIC/IMR

---

### [83] What Transfers Across Protein Pockets? Experience Reuse in Molecular Optimization for Agentic Structure-Based Drug Design

**链接**: https://arxiv.org/abs/2610.32620
**作者**: Zaifei Yang, Weiyu Chen, Yaqing Wang, James Kwok
**来源**: cs.AI q-bio.BM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents optimize a ligand in a protein pocket by editing it step by step and docking each edit. Recent agents first spend extra dockings probing the complex with controlled edits; guidance induced from these probes is reported to help more than the chemical knowledge the model already carries. The probes are then discarded with the instance that produced them, so the obvious next step is to keep them in an experience base, letting a new pocket inherit what earlier ones already paid for. Such a base is read through a \emph{key}: the record properties under which past edits are pooled and a new one is looked up. Using the full log of one such run over the CrossDocked2020 test-set pockets, we ask whether its keys recur on a pocket the base has never seen and still separate improving from worsening edits. \crchange{Using} the contacts at the site being edited, the action, and the round as \crchange{a} key, the base separates them sharply. Within our analysis, this separation is largely 

---

### [84] From Deliberately Constructed Systemic Representations of the World of Activity to Dialogue: A Five-Level Communication Architecture for Strong Language-Based ASI

**链接**: https://arxiv.org/abs/2610.32869
**作者**: Maxim Osovsky (Adam University, Bishkek, Kyrgyzstan)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper proposes a five-level organization of message formation and understanding within thinking and activity in which ASI participates. Its central thesis is that a language model's context is fundamentally incapable of presenting the foundations of utterance formation for examination and verification. These foundations are established in advance by acquired schemas, systemic representations of the world of activity, and connections accepted as true within them. Neither context nor trained LLM weights, in themselves, attest to the presence of deliberately constructed systemic representations. The five levels distinguish systemic representations of the world of activity, a particular situation cut out from those representations, its narrative description, the full sense of a message, and text. A situation's schema-model is not identical to a story about it. A recipient reconstructs the full sense from an abbreviated text through jointly constructed and agreed-upon representations a

---

### [85] BiLoCo: Binary Low-Rank Corrections for Post-Training Quantization

**链接**: https://arxiv.org/abs/2610.32243
**作者**: David Jin, Beshr IslamBouli, Tarushii Goel, Han Guo, Yoon Kim
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization (PTQ) to FP4 has emerged as a key technique for reducing large language model inference cost, especially on Blackwell GPUs, which offer native FP4 tensor core support. Direct PTQ to FP4, however, still leaves a noticeable accuracy gap. Recent work on SVDQuant mitigates the errors introduced through FP4 quantization for diffusion models by adding high-precision low-rank corrections obtained via SVD. However, this high-precision low-rank correction requires many bits per rank, and it runs on the same tensor cores as the main FP4 GEMM. We introduce BiLoCo, a low-rank correction method whose left and right factors are stored as binary ${\{\pm 1\}}$ sign vectors rather than as BF16 numbers. The signed format uses $16{\times}$ less storage per rank-one component, and since the correction now consists of additions/subtractions, this can be run on CUDA cores concurrently with the FP4 tensor-core GEMM. On 4B--72B LLMs, BiLoCo matches or improves memory-matched SVDQuan

---

### [86] Principia: Test-Time Hypotheses to Principle Construction for Scientific Discovery

**链接**: https://arxiv.org/abs/2610.32195
**作者**: Dongki Kim, Sangwoo Park, Jinheon Baek, Soyeong Jeong, Sung Ju Hwang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific discovery requires identifying the scientific principles underlying observed phenomena to guide further investigation. As these empirical principles are often unknown in complex discovery processes, they are constructed via a hypotheses-to-principle pipeline to obtain recurring causalities from progressively accumulated observations during test-time discovery. However, constructing this knowledge requires substantial domain expertise, time, and effort, making this translation stage a bottleneck for scientific discovery. To address this limitation, we propose Principia, an LLM-based framework that constructs and continually refines scientific principles at test time. Drawing on how human researchers develop principles, Principia forms comparative causal hypotheses from related inputs and their observed outcomes, then synthesizes recurring relationships across these hypotheses into inductive principles. By applying the constructed hypotheses and inductive principles to the tas

---

### [87] Guided Zero-Shot Anomaly Explanation for Anonymized Crowd Video Monitoring: Context, Categorization, and Spatial Localization

**链接**: https://arxiv.org/abs/2610.32073
**作者**: Mulugeta Weldezgina Asres, Lei Jiao, Christian Walter Omlin
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the promising development of deep learning for video anomaly detection (VAD), explainability (XAI) of these models remains a challenge. Explainable and privacy-protecting VAD builds transparency and trust that facilitates adoption of computer vision systems, including safety and security monitoring. However, anomaly explainability in privacy-preserving VAD systems is underexplored. In this study, we present the XAVAD approach, a unified descriptive anomaly XAI for an anonymized VAD, that integrates flexible zero-shot anonymization, anomaly type categorization, visual localization, and scene context description. We provide empirical and qualitative assessments of multifaceted explanations integrated with full-body visual anonymization for privacy protection. We adopt a multimodal CLIP embedding for videos, using improved LLM-assisted prompting and pool-scoring mechanisms for anomaly-type identification. We enhance Grad-ECLIP for spatial anomaly heatmap localization, leveraging c

---

### [88] MI-MIDI 2: From Observation to Control with Sparse Autoencoders in Text-to-MIDI Generation

**链接**: https://arxiv.org/abs/2610.32007
**作者**: Jakub Po\'cwiardowski, Mateusz Modrzejewski
**来源**: cs.SD cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) can expose features of a generative model without predefined labels, but in language models the evidence used to interpret these features has proven an unreliable guide to which of them steer the output. Whether interpretations of SAE features predict control in music generators has not, to our knowledge, been tested. We develop an end-to-end protocol for discovering and evaluating SAE features in text-to-MIDI generation and apply it to text2midi and MIDI-LLM. The protocol characterizes features through correlations with musical metrics, shared instrument programs, and automated descriptions, each with its own control: note-density adjustment, matched inactive excerpts, and permutation calibration. It then tests candidates by intervention, measured directly in the generated MIDI against unmodified generation and a matched random direction, ranks them in screens, and confirms selected features on new prompts. Evidence that survives these controls points to fea

---

### [89] Knowledge Graphs Quality Assessment in the Era of LLMs: A Conceptual Framework

**链接**: https://arxiv.org/abs/2610.31684
**作者**: Elwin Huaman
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge Graphs (KGs) have been popularized during the last few decades and are increasingly constructed and consumed by Large Language Models (LLMs). Various applications therefore rely on KGs to provide concise, complete, accurate, faithful, fresh, and traceable answers. However, what is the quality of those KGs? In which cases should a KG be used, and can it be trusted to ground an LLM? How might it be evaluated? We reviewed the literature on quality assessment (QA) of data, information, linked data, KGs, and the intersection of KGs and LLMs. We extended the current state-of-the-art frameworks to a catalog of 24 quality dimensions (QDs) and various quality metrics (QMs). Furthermore, we propose a general-purpose, customizable to a domain or task, and practical QA framework for assessing the quality of KGs.

---

### [90] Lifelong Context Adaptation through Bidirectional Memory-Skill Learning

**链接**: https://arxiv.org/abs/2610.32295
**作者**: Tianyi Xu, Huazheng Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lifelong LLM agents must learn from an expanding history of interactions while making each decision within a bounded context window. Memory makes past experience available, but the agent may still need to infer how to solve each new task from the retrieved records. Skills provide reusable procedures, yet may omit the task-specific facts needed to apply them. Because retrieved memory and skills shape the agent's behavior, they also influence the experience available for future learning. We introduce MemCryst, a framework for lifelong context adaptation through bidirectional learning of memory and skills with a frozen language model. Recurring episodes stored in memory support skill creation and revision, and the interactions guided by those skills supply new memory for subsequent learning. Facts retrieved from memory and learned skills jointly form the agent's context, while task outcomes adjust the future retrieval influence of the records actually served without rewriting their conten

---

### [91] RSI-Opt: Recursive Self-Improvement Optimizer Agents For Model Training

**链接**: https://arxiv.org/abs/2610.32026
**作者**: Binghang Lu, Yige Sun, Guang Lin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional neural-network training typically follows a predefined optimization recipe, motivating a LLM agent that monitors training dynamics and adjusts optimizer settings as training progresses, but a fixed agent policy does not accumulate experience across runs. We introduce RSI-Opt, a plug-and-play Recursive Self-Improvement Optimizer Agents which evolves the knowledge that guides this process: a prompt, a playbook of procedures, a library of tested optimizer code, and a decision cadence. A meta-agent rewrites this policy using evidence from earlier runs, and an archive retains evaluated policies for further evolution. Across 5 generations on three training tasks, the meta-agents develop reusable procedures and code and conduct their own CPU proxy experiments. RSI-Opt substantially improves optimizer-agent performance, with representative raw-space summary $z$-scores increasing from $+10.48$ to $+14.33$ on the evolution suite with Opus 5.5 and from $-0.36$ to $+3.11$ on held-out 

---

### [92] Reuse, Rewrite, or Reject: Evidence-Constrained Trace Reuse for Repeated Mobile GUI Control

**链接**: https://arxiv.org/abs/2610.31712
**作者**: Bingyu Bai, Cheng Zhang, Erhu Feng
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile GUI agents frequently perform repetitive tasks with similar interaction procedures. Reusing previous executions can reduce redundant LLM inference and execution overhead, but variations in user instructions and execution environments may invalidate previously successful actions. We systematically characterize these variations into six representative categories and observe that such changes do not necessarily invalidate entire procedures: individual transitions can remain reusable when validated against the current task context and interface state. Based on this insight, we propose graph-text templates for selective execution-trace reuse. The graph captures UI states and action transitions, while the text encodes task intent, procedural structure, and typed slots for variable content. A record-template-replay framework constructs templates from verified executions and leverages the current instruction and live UI state to reuse, adapt, or discard individual transitions. Given an 

---

### [93] TRACE: Data-Free Text Reconstruction Attacks against Approximate Unlearning in LLMs

**链接**: https://arxiv.org/abs/2610.31995
**作者**: Mengying Zhang, Derui Wang, Ibrahim Khalil, Bowen Liu, Xiaoyu Xia, Minhui Xue
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) face growing demands for data removal driven by regulatory compliance, copyright concerns, and privacy protection, approximate unlearning has emerged as a practical alternative to expensive full retraining. In practice, pre- and post-unlearning model snapshots are often maintained for auditing and rollback, introducing a previously overlooked side channel. This paper demonstrates that approximate unlearning in LLM can leave residual traces within model snapshots, which may be recoverable and thus enable the privacy breaches that approximate unlearning is intended to prevent. Here, we propose TRACE, a framework that reconstructs unlearned training data given access to pre- and post-unlearning model snapshots, without any data-specific prior knowledge. To achieve this, TRACE identifies a compact set of candidate tokens from embedding-level parameter differences to constrain the search space, and assembles sequences via a contrastive scoring mechanism based

---

### [94] Compact-Bench: Measuring What Context Compaction Costs Long-Horizon Coding Agents

**链接**: https://arxiv.org/abs/2610.31710
**作者**: Ruopei Sun, Jianfeng Cai, Kangwen Zhao, Wengang Zhou, Houqiang Li
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Context compaction lets long-horizon coding agents continue beyond their context windows, but can erase the state needed to finish a task. Prior evaluations measure efficiency, retained information, or end-to-end success, leaving the effect of a specific history replacement difficult to isolate. Compact-Bench pairs full-history and summary-only continuations from a shared repository state, and evaluates recurring details and successive production compactions. It covers 35 SWE-bench repairs, 146 agentic sessions, and 106 production chains. Across 14 summarizer backbones, stable damage ranges from 5-64% of 22 full-history successes: Claude Opus 4.8 preserves the most repairs, while DeepSeek-Flash damages the most. With Kimi-K3 as summarizer, the Kimi Code prompt preserves the most task continuations (19/22), whereas Claude Code retains the most recurring details (15.0%). LLM summaries retain at most 16.0% of recurring details, compared with 79.1% for mechanical extraction; production sum

---

### [95] Ontology-Guided Knowledge Graph Construction from Structured Metadata and Climate Science Publications

**链接**: https://arxiv.org/abs/2610.32725
**作者**: Aayush Acharya, Qi Zhang, Eduard Dragut, Longin Jan Latecki
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid expansion of scientific literature far outpaces the speed of manual curation, creating a fundamental bottleneck in extracting structured knowledge from scientific texts. To address this, we introduce an agentic, ontology-guided framework for knowledge graph (KG) construction. Our framework utilizes specialized agents for document understanding, information extraction, ontology conformance, and entity linking. First, an LLM extracts factual knowledge in the form of triples with explicit textual evidence from research papers. Then the triplets undergo a multistage verification process to ground the triplets in the ontology. By enforcing schema constraints and requiring evidence in the form of text fragments, we ensure the data is both semantically consistent and traceable. In an agreement study over 1,000 extracted triplets, Gemini-2.5-flash achieves Cohen's $\kappa$ scores of 0.640--0.700 against three human annotators, matching the human--human agreement range of 0.616--0.689

---

### [96] Not All Information Is Worth Asking For: Decision-Informed Information Seeking with LLMs

**链接**: https://arxiv.org/abs/2610.32181
**作者**: Seunghan Lee, Jun Seo, Junhyeok Kang, Jaehoon Lee, Sangjun Han, Sungdong Yoo 等 (10 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to support decisions under incomplete information, where deciding what to look up and when to stop matters as much as the final answer. However, LLMs fall into an information trap: They pay for checks, i.e., costly pieces of evidence, that cannot change their decision or are not worth their cost, and they keep asking when the evidence is already sufficient. To this end, we propose Decision-Informed Value-of-information Acquisition (DIVA), a simple yet effective procedure for LLM information seeking based on the decision value of evidence. DIVA 1) lets the LLM specify a small decision model, i.e., how likely a bad outcome is and how each check would shift this probability, through short numeric questions and 2) values each candidate check by how much its imagined outcomes improve the decision net of its cost, stopping when no check is worth its cost. Its variant, DIVA-U, further accounts for the LLM's uncertain estimates of how strongly

---

### [97] Sharpness-aware Orthogonalized Momentum Algorithms

**链接**: https://arxiv.org/abs/2610.32465
**作者**: Geetika, Shivani Singh Chauhan, Gauranshi Gupta, Anant Jain, Kaushik Kalyanaraman, Bapi Chatterjee
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adversarial sharpness penalty per iteration of a base optimizer, known as sharpness-aware minimization (SAM), is an accepted technique to improve generalization in deep learning. Recently, Muon has emerged as a dominant optimization algorithm for training large language models (LLMs). It achieves lower sample complexity for heavy-tailed gradient updates - a phenomenon common in LLM training. However, sharpness penalties with Muon updates are yet largely unexplored in the literature. Moreover, the behavior of SAM under heavy-tailed noise is unknown both theoretically and empirically. A potential reason for this gap is the additional cost of extra gradient computation per iteration for penalty perturbations in SAM, which becomes prohibitive for LLMs. This paper introduces Sharpness-aware Orthogonalized Momentum Algorithm (SOMA) to combine a computationally efficient and theoretically grounded perturbation scheme with the Muon algorithm. The key idea is to use stale (purely) stochastic gr

---

### [98] HGWM: Hierarchical Graph-Guided World Model for Zero-Shot Object Navigation via Graph Matching

**链接**: https://arxiv.org/abs/2610.32554
**作者**: I-tak Ieong, Hao Tang
**来源**: cs.RO cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zero-shot object navigation requires an embodied agent to choose where to search while retaining evidence from previous observations. HGWM couples an LLM-generated room-anchor prior with persistent spatial-semantic memory. A coarse stage assigns visual-semantic scores to candidate headings on a 0-10 scale; a fine stage measures symbolic compatibility between observed objects, room context, and the goal prior. Phase-dependent fusion combines these scores with an LLM direction recommendation before local action selection. On HM3D v0.1, the reported HGWM configuration achieves 62.6% success rate (SR) and 31.5% success weighted by path length (SPL), compared with 58.1% and 31.2% for WMNav. On MP3D, the corresponding values are 46.8% and 17.9%, compared with 45.4% and 17.2%. The results indicate higher success point estimates and modest path-efficiency gains. On HM3D v0.2, the full model obtains 74.4% SR and 31.9% SPL. Additional component ablations reduce SR by 0.9-2.3 percentage points an

---

### [99] Why Full-Duplex Speech Models Collapse in Long Conversations

**链接**: https://arxiv.org/abs/2610.32349
**作者**: Yeonju Kim, Bella Godiva, Se Jin Park, Yong Man Ro
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex speech models listen and speak at the same time, which makes them promising for natural, open-ended conversation. But can they sustain a coherent conversation for tens of minutes? Because they generate a token every frame, even while listening, they exhaust their context windows within minutes. Yet existing benchmarks evaluate only single turns or a few conversational rounds, too short to expose the long-horizon problem. We introduce the Full-Duplex Long-Horizon Benchmark (FD-LHB), which tests five recent full-duplex models on long replayed conversations and in live conversation with an LLM partner. Every evaluated model eventually either degrades or exhausts its context. Models that keep the full history often degrade before their context runs out, while sliding-window models still fall into repetition, silence, and gibberish. For sliding-window models, we identify two contributing mechanisms. Gibberish and silence are linked to Initialization-Anchor Eviction, where the sl

---

### [100] TACS-RF: Tool-driven Agentic Circuit Synthesis of RF and mmWave Modules

**链接**: https://arxiv.org/abs/2610.31882
**作者**: Tristan Liang and Aravind Nagulu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present the framework of TACS-RF - a Tool-driven Agentic Circuit Synthesis of RF and mmWave modules. In this framework, a large-language-model (LLM) coding agent (Claude Opus 4.8) directly drives industry-standard electronic-design-automation (EDA) tools such as Cadence Virtuoso/Spectre, Calibre, Cadence EMX, and Ansys HFSS to design RF and mmWave modules. We validate the framework through the agentic design of a 240-251 GHz sub-THz transmitter in a 90 nm SiGe BiCMOS process. The agent semi-autonomously designed the sub-blocks including a 60 GHz push-push Colpitts VCO with second-harmonic extraction, multistage differential cascode power drivers, a push-push frequency doubler, a differential bowtie antenna, and all the interstage matching networks. The transmitter chain with parasitic-extracted devices and EM-verified passives delivers +5.1 to +6.3 dBm across an 11 GHz varactor-only tuning range, phase noise of -80 to -88 dBc/Hz at 1 MHz offset while consuming a DC power of 361 mW. 

---

### [101] When and How Does Muon Precondition? The Role of Structured Gradient Noise

**链接**: https://arxiv.org/abs/2610.31728
**作者**: Xiaoran Chen, Binghui Li, Liwei Wang, Pinyan Lu
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Muon has become a popular optimizer for large language model training, yet its theoretical foundations remain poorly understood. In this work, we study how gradient noise geometry shapes Muon's preconditioning benefits. We first show, theoretically and empirically, that under the classical isotropic noise assumption, Muon offers no acceleration beyond a rescaling of the learning rate. This motivates us to investigate structured noise arising from mini-batch sampling in associative memory with heterogeneous task frequencies. We establish an exact balancing threshold for two tasks and extend the analysis to multiple tasks, revealing how task coverage and gradient reliability jointly shape learning. Our analysis shows that Muon can soften the dependence on task frequency from linear to square-root, helping balance the learning of frequent and rare tasks. We further identify rotation-induced negative transfer in SignSGD that Muon avoids, and explain how momentum reduces sampling noise whil

---

### [102] SREdit: Scene Response Guided Appearance Editing for Projection Mapping

**链接**: https://arxiv.org/abs/2610.32792
**作者**: Yuqiao Xia and Yuchen Deng and Ziheng Chang and Bingyao Huang
**来源**: cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Projection-based appearance editing changes selected visual attributes of a physical object through projection mapping (PM). To display a desired appearance, PM typically uses projector compensation, which computes a projector input that counteracts the geometric and photometric distortions of the scene. Compensation can only approximate this appearance within the available projection range, and it cannot revise the appearance itself. Pretrained LLM-based image editors provide a direct way to produce the desired appearance from a text prompt or reference image; projector compensation can then attempt to reproduce the edited result through projection. However, these editors do not have an accurate measure of the scene geometry or scene response. Therefore, their outputs may contain geometric misalignment, inconsistent shading, or changes outside the available projection range, which downstream projector compensation cannot correct. To address this problem, we introduce SREdit, an effici

---

### [103] Beyond Gain: Measuring Skill Internalization for Agent Skill Retirement

**链接**: https://arxiv.org/abs/2610.32322
**作者**: Yanze Wang, Pengfei Yao, Tianyi Sun, Hongda Chen, Yunyun Han, Jun Sun 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents retrieve skills from public hubs that hold up to about 100,000 entries and serve many models. As models improve, a hub must find the skills a given model has internalized, meaning it can do without them, and retire them for that model, yet internalization has not been measured with known reliability. Published rules that compare runs with and without a skill retire on the gain alone. The gain is near zero both for an internalized skill and when neither the model nor the skill delivers the capability, a state we call uncovered. We instead withhold the skill, score the model on a task synthesized from it, and trust a high unaided score only when another model gains from the skill, since nearly half of high scores come from tasks no model benefits from. Under four models, a published gain rule applied with one task per skill removes over half of the uncovered skills. On SkillsBench, 28 of its 31 retirements rest on probes no run passed in full, while retiring on the unaided sco

---

### [104] CounselPlex: A Stressor-Aware Full-Duplex Counseling Model

**链接**: https://arxiv.org/abs/2610.32702
**作者**: Yeonju Kim, Bella Godiva, Yong Man Ro
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-duplex speech models can listen and speak at the same time, enabling natural, low-latency interaction. In counseling, however, these models often focus on the latest utterance and lose track of the seeker's underlying problem. We call this failure Stressor Blindness. We propose CounselPlex, a stressor-aware full-duplex framework that uses two operations. CounselPlex updates a short stressor state during seeker silence and injects this state into <PAD> positions while listening. We also introduce RoPE Position Shift Augmentation (RPSA), which broadens positional coverage during training and improves performance at longer turn depths in our evaluation. LLM-judge evaluations show improved counseling quality and stressor grounding over strong baselines.

---

### [105] DealsFlow: An Evidence-Gated Agentic Harness for Venture Capital Deal Triage

**链接**: https://arxiv.org/abs/2610.32380
**作者**: Ming Ze Tang, David Cutting, Boyd Carson, Vasiliki Carson
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can read startup pitch decks, but letting them emit investment scores directly invites score inflation, run-to-run variance and rationales that are hard to audit. We describe DealsFlow, a human-in-the-loop agentic harness deployed at a UK early-stage fund. The LLM reads the deck, cites evidence and rates each category; code combines the ratings, caps them and only ever lowers them. Three mechanisms implement this: a stage-aware corroboration ceiling (78, 70 or 60 out of 100) on factual categories without external evidence; a sceptic call that may lower but never raise a score; and a pre-fetch pattern that retrieves and indexes all evidence before a single generation pass. We evaluate on $N=243$ SEIS/EIS investments with recorded outcomes. Because recent investments have unresolved outcomes, we use the 142 that are at least three years old. There, the full pipeline's score has Spearman $\rho=0.45$ (95% CI 0.32 to 0.57) with the total-value multiple and AUC 0

---

### [106] Real-to-Sim Calibration of Bosch Etching Simulators with Few-Shot XSEM Data and Hybrid Search

**链接**: https://arxiv.org/abs/2610.31904
**作者**: Xinyu Jia, Jainil Shah, Rahul Tripathi, Vijay Gupta and Zhihong Chen
**来源**: cs.CE cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Bosch process is widely used in MEMS and TSV fabrication, but accurate prediction of etching outcomes remains difficult without calibration against real measurements, which are sparse and costly to obtain. This work presents a few-shot real-to-sim calibration framework that decouples simulator parameters from direct process variables to infer a recipe-specific simulator parameter vector from sparse measurements, enabling reliable prediction of etch depth and sidewall angle under held-out process conditions. We first formulate Bosch profile prediction as a few-shot real-to-sim calibration problem, where a small set of real XSEM measurements is used to identify a recipe-specific ViennaPS parameter vector $z_r^*$ that minimizes the discrepancy between simulated and measured etch depth and sidewall angle. To search this parameter space efficiently, the framework combines local exploration, LLM-guided candidate generation, and XGBoost-based surrogate screening, while retaining ViennaPS 

---

### [107] Beyond What to Say: Proactive Utterance Timing with Inner Thoughts for Werewolf Agents

**链接**: https://arxiv.org/abs/2610.32107
**作者**: Yoshiki Tanaka, Shuya Uchiyama, Daichi Hamaguchi and Michimasa Inaba
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Participating in a conversation involves not only deciding what to say but also whether to speak at all. This judgment carries even greater significance in environments like the Werewolf game, where participants' interests conflict, because both utterances and silence are subject to interpretation and assessment by others. Therefore, determining when to speak, as well as what to say, is crucial for an LLM agent playing the Werewolf game. In this study, we introduce a Werewolf AI agent developed for the Anytime Utterance Track of the AIWolfDial shared task. Our system builds on the existing Inner Thoughts framework, which determines utterance timing during conversations by generating internal thoughts and evaluating the value of each thought for expression at that moment. Since existing methods were designed for general dialogue, we have redesigned the system specifically for the competitive environment and incomplete information setting of Werewolf games. We call our adapted method Adv

---

### [108] A Broader Look into MLLM's Retrieval Heads

**链接**: https://arxiv.org/abs/2610.32411
**作者**: Jia Wang, Yuqing Li, Jiangnan Li, Zheng Lin, Mo Yu
**来源**: cs.CL
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Locating relevant evidence in long inputs is a core capability of Multimodal Large Language Models. Prior studies attribute this capability to retrieval heads, a sparse set of attention heads that transfer information from the context to the output. However, these analyses are confined to a limited set of modalities and the corresponding models. Moreover, how retrieval heads can be leveraged to enhance the model calls for further exploration. In this paper, we ask whether this mechanism expands together with the input modalities of the model. Taking audio-visual input as a newly added modality, we construct paired inputs in which the same answer is either spoken or shown on screen. With the evidence content fixed, retrieval heads remain sparse in the new modality and are shared to a large extent across modalities. Across 18 language, vision-language, and omni-modal checkpoints, omni-modal models largely preserve the retrieval heads of their backbones. Ablating these heads eliminates ne

---

### [109] Making MLLM Latents Matter: Factor-Aware Predictive Learning for Cinematic Video Generation

**链接**: https://arxiv.org/abs/2610.30926
**作者**: Songlin Yang, Zhe Wang, Xiaotong Zhao, Xi Wang, Ran Zhang, Shuai Li 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] Beyond Post-Hoc Rewards: Privileged Reasoning Exploration for Multimodal Embeddings

**链接**: https://arxiv.org/abs/2610.32474
**作者**: Tianyu Yang, Yijun Tian, Lars Benedikt Kaesberg, Jan Philip Wahle, Bela Gipp, Terry Ruas 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in Multimodal Large Language Models (MLLMs) have driven substantial progress in multimodal embeddings. Recent methods exploit generative capabilities by augmenting embedded inputs with self-generated reasoning to produce more informative embeddings. However, conventional retrieval supervision for training embedding models specifies pairwise relevance relations without explicitly guiding the reasoning used for input augmentation. Such reasoning is neither directly observed nor uniquely determined by the input, allowing multiple plausible traces to introduce semantic cues of varying retrieval utility. Existing approaches largely optimize reasoning conditioned on the input alone, limiting the exploration of retrieval-relevant traces. We introduce PILOT, a framework that models reasoning as a latent variable and instantiates its prior and posterior distributions as distinct reasoning modes of a shared MLLM. The prior conditions only on the input, whereas the posterior uses additio

---

### [111] DriveMind: Mind-Evolving Belief Tracking for Closed-Loop Autonomous Driving

**链接**: https://arxiv.org/abs/2610.32069
**作者**: Yan Shi, Kehua Chen, Jiarui Qi, Yihong Tang, Haichen Liao, Yinhai Wang
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent multimodal large language models (MLLMs) can perceive a traffic scene, reason about it, and propose a driving action within a single model. However, existing MLLM-based drivers reason from scratch at each frame and commit to a single explanation, discarding earlier hypotheses about the scene. When the scene is ambiguous, the agent locks in on the wrong interpretation and acts on it before evidence accumulates. In this paper, we propose DriveMind, an MLLM-based driving framework that keeps several hypotheses about the scene alive at the same time and updates their weights as new frames arrive. Inspired by particle filtering, DriveMind propagates each hypothesis through a VLM, scores it against the current observation, and resamples to maintain diversity. On Bench2Drive, adding belief tracking to the same driving pipeline improves the Driving Score (DS) from 68.50 to 81.37 and the Success Rate (SR) from 41.36% to 54.09%. The largest gains occur on ambiguous scenarios such as unsig

---

### [112] The Answer Knows Where to Look: Zooming before MLLMs Answer under Visual-Token Budgets

**链接**: https://arxiv.org/abs/2610.32664
**作者**: Zhensheng Hu, Guanglong Xu, Guanqiang Hu
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) read images through visual tokens, and under the small per-image budgets that efficient deployment requires, the fine text of documents, charts and infographics becomes illegible. Zooming in recovers the evidence, but the region must be chosen before the model answers. We find that MLLMs know where the evidence is, but not in a form that can be read before they answer: the answer tokens localize it from the middle layers on, whereas the attention available before answering does so only in the top layers, at a depth that varies across models, and diffusely. Supervising the pre-answer attention to point degrades reading, and the benefit of zooming is governed by each image's information gap. Building on these findings, we introduce ours, which lets an MLLM look where its answer would. A dedicated look token, processed in a single prefill and kept out of the answering pass, learns in hindsight to attend as the model's own correct answers do, extrac

---

### [113] CASE: Confusion-Aware Skill Evolution for Frozen Multimodal Emotion Models

**链接**: https://arxiv.org/abs/2610.32481
**作者**: Siyu Wu, Zeyu Liang, Linghao Wang, Qiyun Zheng, Yi Yao, Ling Lo 等 (7 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have substantially advanced Multimodal Emotion Recognition (MER) by enabling fine-grained emotion understanding through reasoning over multimodal evidence. However, they still exhibit systematic confusion between semantically adjacent emotions with highly overlapping multimodal cues. Existing approaches typically address these errors through global parameter adaptation, making confusion correction costly and inflexible. We instead observe that emotion confusion is highly localized and therefore better addressed through reusable pair-specific expertise. Building on this insight, we propose Confusion-Aware Skill Evolution (CASE), the first agent-skill framework for MER. CASE maintains a sparse, self-evolving library of pair-specific EmotionSkills that externalize affective expertise from model parameters, enabling the learned expertise to be continuously refined and readily transferred across diverse frozen MLLM backbones. During inference, CASE d

---

### [114] Controlled Evaluation of EEG Foundation Models: Random Initialisation, Band-Power and Validation-Selected Probes

**链接**: https://arxiv.org/abs/2610.32067
**作者**: Mingyu Jeon, Suwan Cho, Jae Young Suh
**来源**: cs.LG cs.AI
**匹配关键词**: EEG, Foundation Models, Motor Imagery
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models report downstream gains, yet their protocols seldom include three controls. These are the same encoder untrained, spectral features fitted on the same data, and a layer picked without looking at test scores. We therefore evaluate five publicly released EEG foundation models and an in-house JEPA-style model under one protocol with all three controls and several seeds, on five benchmarks and four added task families. The controls change the reading in three ways. First, picking the probed layer by its test score raises the layer-wise peak by an average of +0.034 and reverses the peak-versus-output gap in 9 of 36 cells. Second, with the layer picked on validation, random initialisation matches or beats pretraining for half of the models on sleep and emotion, and no model beats a five-band log-power baseline on emotion or motor imagery. Third, after full fine-tuning only 5 of 30 pairs gain beyond twice their seed spread, and the one clear loss of -0.290 AUROC persists

---

### [115] U-NeXt: General-purpose event detection for neonatal EEG

**链接**: https://arxiv.org/abs/2610.32811
**作者**: Robert Hogan, Sean R. Mathieson, Aurel Luca, Soraia Ventura, Sean Griffin, Geraldine B. Boylan 等 (7 人)
**来源**: cs.LG eess.SP physics.med-ph
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We developed U-NeXt, a general framework for neonatal electroencephalography (EEG) event detection based on semantic segmentation. Its convolutional encoder-decoder directly segments individual channels using long input segments to preserve temporal context. A shared architecture and training framework were developed using low-voltage interval, artefact, and seizure datasets containing 51, 98, and 278 neonates, respectively, comprising over 11,000 hours of EEG and 82,000 annotated events. Performance was compared with task-specific ConvNeXt classifiers. For seizure detection, we also evaluated U-NeXt+, trained on an expanded dataset. Both U-NeXt variants and the ConvNeXt baseline were evaluated on two independent held-out seizure datasets, Helsinki and Cork, comprising 130 neonates, with recordings annotated by three experts. U-NeXt improved detection across all three event types, with particular gains in sensitivity for short events. U-NeXt+ achieved Matthews correlation coefficients 

---

### [116] FOCUS: A Lightweight Mamba-2 Model for EEG-Based Cognitive Workload Classification

**链接**: https://arxiv.org/abs/2610.32361
**作者**: Ioannis Kyprakis, Stefanos Gkikas, Chariklia Chatzaki, Zongyi Jiang, Randy Gomez, Raul Fernandez Rojas
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cognitive workload estimation from physiological signals is increasingly relevant in high-risk environments, where continuous and unobtrusive monitoring can inform adaptive systems and safety interventions. This paper presents FOCUS (Frequency-band Optimized Cognitive-load Ultralight SSM), a compact Mamba-2-based model for EEG-based binary workload classification under constrained data conditions. Rather than learning frequency sensitivity from data, FOCUS encodes preprocessed multi-channel EEG using a fixed FFT decomposition that covers the five canonical EEG bands. The proposed model combines depthwise-separable convolution and a weight-shared encoder-bottleneck Mamba-2 pair, with 0.04 million parameters and 0.11 GFLOPs. Evaluated in a pilot study with 11 participants under leave-one-subject-out cross-validation across three cognitively distinct tasks, FOCUS achieves 74.75% accuracy on the full dataset at 0.08 ms GPU model-forward latency. In the weight-sharing ablation, the shared c

---

### [117] Beyond Channel Data: Configuration-Enriched Radio Foundation Models

**链接**: https://arxiv.org/abs/2610.32542
**作者**: Shrihari Vasudevan, H. G. Ranjani, Raaghul Ranganathan, Satwik Sahu and Thirumaran Ekambaram
**来源**: cs.AI eess.SP
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper proposes incorporating channel configuration (CFG) information into Radio Foundation Model (RFM) pre-training and demonstrates that the resulting CFG-enriched embeddings serve as effective inductive priors for downstream tasks under label scarcity. We compare the proposed embeddings with raw channel tokens and multiple baseline models, under three different data regimes, for multiple downstream tasks --- Line-of-Sight/Non-Line-of-Sight (LoS/NLoS) classification, timing advance (TA) estimation, and beam selection. Evaluation is done in both in-distribution and out-of-distribution configuration settings. Experimental outcomes show that the proposed embeddings consistently outperform and/or are competitive to the baselines, across experiments in both seen and unseen configuration scenarios.

---

### [118] Track finding and particle identification performance with particle physics foundation models

**链接**: https://arxiv.org/abs/2610.31180
**作者**: Shuhang Li, Haiwang Yu, Gabor Galgoczi, Yeonju Go, Yi Huang, David Park 等 (10 人)
**来源**: physics.data-an cs.LG hep-ex nucl-ex
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Tabular Foundation Models for Credit Risk Prediction: A Dedicated Review and Empirical Comparison

**链接**: https://arxiv.org/abs/2605.18147
**作者**: Bart Baesens, Andreas Goethals, Stefan Lessmann, Simon De Vos, Cristi\'an Bravo, David Martens 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] Beyond Local Accuracy: Benchmarking the Rollout Reliability of PDE Foundation Models

**链接**: https://arxiv.org/abs/2610.31935
**作者**: Jaewan Park, Seid Koric, Giri Krishnan, Sudhakar Pamidighantam, Surresh Marru
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> PDE foundation models enable data-efficient adaptation but are deployed autoregressively, so short-horizon accuracy need not imply reliable simulation. We ask whether the short-horizon advantage of a foundation-model recipe persists when its predictions are repeatedly fed back as inputs for a long horizon. We define error amplification as G=E(H_f)/E(H_s), which measures full-horizon error relative to short-horizon error. We evaluate seven models on seven two-dimensional time-dependent PDE datasets: scratch-trained FNO and DeepONet; fine-tuned DPOT, GPhyT, Poseidon, and Walrus; and frozen in-context VICON. We report VRMSE, relative L_2, and relative MAE. Six datasets provide paired short- and full-horizon scores, while CE-RM contributes short-rollout sweeps only. At least one fine-tuned foundation model outperforms both scratch baselines in 26 of 30 short-rollout dataset--budget cells under every metric. Nevertheless, full-horizon VRMSE exceeds short-horizon VRMSE in 140 of 144 paired t

---

### [121] Forecasting Associations, Not Interventions: A Preregistered Causal Audit of Covariate-Aware Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.31869
**作者**: Zong-Han Bai
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Covariate-aware time series foundation models (TSFMs) accept a future path for a control variable and return a forecast, inviting what-if queries. The query is interventional; the models are trained on observational data. We determine whether their answers are the conditional slope $\partial E[Y|X]$ or the interventional effect $\partial E[Y|do(X)]$, at three levels. Theory: a Bayes-optimal observational predictor answers interventional queries associationally unless the adjustment set is available and used; for in-context least squares we derive the resulting confounding gap -- a model's effect estimate under an observational minus under a randomized context -- in closed form, a parameter-free reference line. Behaviour: on a preregistered grid with exact counterfactual ground truth, Chronos-2, TiRex-2, TabPFN-TS and TimesFM-2.5 all track this line ($R^2$ 0.90-1.00) and respond more confounded than regression itself (slopes 1.3-1.8), on linear and nonlinear structural models. Pairs of 

---

### [122] Reuse, Don't Retrain: Efficient, Modality-Versatile Geospatial Foundation Models through Feature Distillation

**链接**: https://arxiv.org/abs/2610.32566
**作者**: Mario Hamon, Pierre Adorni, Minh-Tan Pham
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models (GeoFMs) are costly to pretrain, yet model families often repeat this process across backbone scales and sensing modalities. We investigate feature distillation as a more efficient way to reuse existing representations. First, we distill frozen CROMA and TerraMind teachers into smaller Vision Transformers through patch-level feature matching. Across nine PANGAEA tasks, distilled TerraMind Tiny, Small, and Base outperform their scale-matched released counterparts by 2.76, 3.02, and 1.87 mean IoU points, respectively; each also matches or exceeds the next-larger released model. Distilled CROMA-Base gains 2.05 points. TerraMind-Base required only 43 A6000 GPU-hours, approximately 0.5\% of the reported cost of independent pretraining. Second, we introduce TEDI, an unpaired multi-expert approach combining TerraMind for multispectral imagery and DINOv3 for high-resolution RGB. Separate patch embeddings route unpaired inputs into a shared Transformer trunk, removi

---

### [123] Easy-3Dfy: Object-Level Geometric Composition for Single-Image 3D Scene Construction

**链接**: https://arxiv.org/abs/2610.32250
**作者**: Ziang Zhang, Wenyou Yi, Zehan Wang, Jiachen Xu, Xintong Han, Chunchao Guo 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Single-image 3D scene construction is a fundamental problem in 3D vision. Recent methods such as SAM-3Dfy enable end-to-end reconstruction of 3D assets and their scene layouts, but still struggle with fine-grained scene geometry and asset quality. Meanwhile, specialized 3D object generators provide detailed object geometry, while 3D foundation models offer strong and generalizable spatial understanding. We propose Easy-3Dfy, a compositional workflow that decouples object generation from scene layout estimation, allowing specialized models to fully exploit their respective strengths. An RPF-based aligner then bridges these capabilities by establishing geometric correspondence between object-local meshes and partial scene pointmaps, recovering object layout for scene composition. Without requiring complete scene-level supervision, the proposed workflow consistently outperforms SAM-3Dfy across multiple geometric metrics on Scene-Maker and 3D-FUTURE200. Our results demonstrate that explici

---

### [124] See What I Need, Dream What I Want: A Navigation Foundation Model on a Self-Constructed Representation Space

**链接**: https://arxiv.org/abs/2610.31762
**作者**: Jiawei Chen, Yinxi Wang, Zihan Yang, Meijun Gao, Yaowei Liu, Shuming Zhang 等 (10 人)
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What visual representation should a navigation policy act on? Navigation policies built on vision foundation models largely leave representation design to the encoders' pretraining objectives. We present RepresentNav, a navigation foundation model built on a self-constructed representation space: a visual representation constructed by the policy's own objectives from vision foundation models. RepresentNav builds this space with Representation Residuals, a compact three-layer transformer that attends over features spanning the full depth of multiple complementary vision foundation models, so that the policy learns to see what it needs for navigation. In the same space it dreams what it wants: before every action a latent chain-of-thought predicts the representation of the scene a moment ahead. The dream is trained end-to-end with the policy as a joint-embedding predictive architecture (JEPA), with a next-representation prediction loss and a regularizer on its targets. RepresentNav sets 

---

### [125] LapaFM: A Laparoscopic Foundation Model via Multi-Stage Continual Learning

**链接**: https://arxiv.org/abs/2610.32263
**作者**: Xiaobo Zhu, Shiwei Wu, Yu An, Yuechen Tao, He Sun, Song Zhang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence-based analysis of intraoperative laparoscopic videos has the potential to improve surgical decision-making and precision. However, effective surgical assistance requires models that can generalize across diverse intraoperative tasks. Here we present LapaFM, a foundation model for laparoscopic surgery trained on more than 20,000 minutes of surgical videos using a multi-stage continual learning strategy that mitigates catastrophic forgetting and inter-task interference. LapaFM learns multimodal visual representations and supports multiple tasks, including smoke removal, surgical phase recognition, instrument and polyp segmentation, and lesion identification. The model was evaluated on 13 retrospective and two prospective cohorts collected from different imaging devices. LapaFM consistently outperformed task-specific models and existing foundation models across datasets, and also generalized to gastrointestinal endoscopy tasks, including polyp detection and classif

---

### [126] 4DMemory: Benchmarking Long-Horizon Spatiotemporal Memory with Harness-Augmented Agents

**链接**: https://arxiv.org/abs/2610.32332
**作者**: Yanhao Jia, Yi Zhu, Yiran Zhong, Weigao Sun, Feida Zhu, Pengkun Jiao 等 (10 人)
**来源**: cs.CV cs.AI cs.CL cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans efficiently process multimodal streams spanning hours to years, building persistent, fine-grained spatiotemporal memories that support reasoning about and predicting long-horizon events. In contrast, existing benchmarks focus on short- and medium-context tasks, and most foundation models struggle to preserve fine-grained information over long horizons. To evaluate and improve long-horizon spatiotemporal reasoning, we introduce the LongVideo dataset and the 4DMemoryBench. LongVideo comprises about 900 hours of video and over 5,000 manually reviewed questions covering visual, textual, and spatiotemporal reasoning across diverse context lengths. We further develop the 4DMemory Harness, which integrates four complementary skills, 22+ specialized tool models, and a model-specific retrieval-augmented generation system. Evaluating 13 leading models, we find that standalone foundation models struggle with long-horizon tasks, while the 4DMemory Harness improves all of them by over 50\%. 

---

### [127] Sustainability of TSFM Deployment and Pretraining: From Carbon Footprint Analysis to Mitigation via Pruning

**链接**: https://arxiv.org/abs/2610.32859
**作者**: C\'ecile Luc, Nathana\"el Lemonnier, Ievgen Redko
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) offer strong zero-shot forecasting capabilities, but their high pretraining cost raises a practical sustainability question: does this upfront investment pay off over a full deployment lifecycle, compared to supervised standalone models that must be periodically retrained? We model the cumulative carbon cost of different approaches across a realistic industrial scenario: Chronos-2 amortizes its pretraining cost within months for large or frequently queried deployments, but a classical model remains cheaper indefinitely for small or rarely queried ones. For cases where reducing the TSFM's own cost matters, we show that removing a single encoder block (7.9% of parameters) via a gradient-free pruning criterion yields a consistent 6 to 9% reduction in FLOPs, CO2 emissions, and latency, at essentially no cost to zero-shot forecasting performance across a 25-task benchmark.

---

### [128] On-Policy Self-Training: Data-Free Self-Improvement in Large Language Models

**链接**: https://arxiv.org/abs/2610.32770
**作者**: Leon Sick, Lukas Hoyer, Yannick Str\"umpler, Christian Reisswig, Timo Ropinski, Federico Tombari
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy self-distillation enables post-training foundation models without relying on stronger external teachers. However, existing approaches rely on ground-truth question-answer pairs, human-curated problem sets, or other supervised signals. In this work, we reformulate on-policy self-distillation as a self-training framework, driven by self-generated question-answer pairs and privileged reasoning demonstrations. We push supervision to the limit: guided solely by coarse, high-level topic descriptions, the model synthesizes its own curriculum of queries and privileged reasoning traces without access to any human-curated prompts or answers. We find that self-distillation on fully synthetic privileged information enables a model to improve across multiple domains while retaining its capabilities on domains it is not self-trained on. We demonstrate the generality of this framework across text and multimodal domains, achieving consistent self-improvement on standard language benchmarks a

---

### [129] State Estimation as In-context Tabular Prediction

**链接**: https://arxiv.org/abs/2610.32487
**作者**: Ayushi Jolotia, Parikshit Pareek
**来源**: eess.SY cs.LG cs.SY
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This letter poses state estimation (SE) as an in-context tabular prediction (ICTP) problem. The key idea is a tabular arrangement in which historical measurement vectors and corresponding state estimates serve as the context, and a new measurement vector forms the query for which we predict a state vector. We propose to use tabular foundation models (TFMs), pretrained on synthetic data, whose weights are never updated, so power system data is needed only as context. With frozen TFM weights we estimate the state of 14-, 30-, 33-, 70-, and 118-bus transmission and distribution networks, and do so where weighted least squares (WLS) fails or degrades, under low observability and with bad data. ICTP errors are 11 to 57$\times$ below the per-bus average of the context at full metering, and 1.3 to 4.0$\times$ below it with only 5% of measurements available. With measurements at six buses biased by 8$\sigma$, the ICTP angle error rises 1.8 to 5.0$\times$ over its bias-free value against 2.5 to

---
