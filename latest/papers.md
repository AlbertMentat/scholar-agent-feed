# 📑 论文索引 - 2026-10-23

共 121 篇论文

---

### [1] LLMSeg: Training-Free Text-Prompted Image Segmentation with B-Splines

**链接**: https://arxiv.org/abs/2610.29409
**作者**: Abdullah Hamdi
**来源**: cs.CV cs.AI
**匹配关键词**: LLM, Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 6.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Promptable segmentation models such as SAM 3 achieve remarkable open-vocabulary performance but require dedicated architectures, large-scale annotation engines, and task-specific training. We ask a different question: can a general-purpose multimodal large language model (MLLM) segment images directly, without an added segmentation head, mask decoder, or training? We present LLMSeg, a training-free pipeline that turns a vision-capable LLM into a text-prompted image segmenter. LLMSeg decomposes segmentation into three LLM-driven stages. First, detect localizes all instances matching a free-form text query and describes their coarse morphology. Next, segment traces each instance using closed periodic B-splines confined to its detected box. These splines define an outer boundary and optional hole loops. Finally, refine iteratively proposes focus boxes around residual errors and retraces confined splines. The process ends when the mask stabilizes or the pass budget is exhausted. The output

---

### [2] Decision language models as affordable and rapid alternatives to LLM judges of clinical generative AI

**链接**: https://arxiv.org/abs/2610.28826
**作者**: Rotem Gershon, Seffi Cohen, Dean Ariel, Havatzelet Bilavsky-Yarden, Amiel Sberro, Shai Yitzhaki 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated judges of clinical artificial intelligence (AI) outputs are necessary, but large language model (LLM) judges are costly and slow at scale. We compared Jev, a decision language model that returns structured judgments, with frontier and open-weight LLM judges in four use cases. On 118 pediatric answers, Jev's agreement with physicians' ordinal quality ratings (Gwet's AC2 0.50; expected score 0.53) matched or exceeded that of seven of 12 LLM judges, including frontier models, Claude Opus 5.5 (0.49) and GPT-6 (0.38). On physician-graded binary HealthBench criteria, Jev matched or exceeded four of six LLM judges. On MedHELM's open-ended tasks, Jev's agreement with a three-LLM jury approached or exceeded the jurors' internal agreement. On HealthBench Professional, Jev matched the benchmark's reference judge, GPT-5.4, on 91% of criteria (other judges, 91-93%). Frontier judges cost 73-294 times more than Jev and took 7-57 times longer. Jev may enable efficient clinical AI evaluation 

---

### [3] Is Anyone Enforcing the Cartel? What Reinforcement Learning Teaches LLM Agents in Markets

**链接**: https://arxiv.org/abs/2610.28787
**作者**: Hieu Tran, Hong Yu
**来源**: cs.CL cs.GT cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluations of large language model (LLM) agents report that pricing agents collude at others' expense. Yet collusion is defined by enforcement: a cartel, in which competitors share monopoly profits, holds only if a member who cheats is punished. We introduce an audit that tests enforcement by forcing a member to cheat in counterfactual copies of a market, and use it to study what reinforcement learning (RL) teaches agents in pricing and trading. Small LLMs trained by RL learn what their training rivals reward, but only what they readily try. In self-play, they learn fixed rules ignoring their rivals; against a punishing rival, to be deterred; against a cheating rival, to match its cuts, never the costly price war that would deter it, which they rarely try. A war forced into training is learned, but mostly only where it was forced. Against their own copies, deterred and matching agents can earn the same cartel profits, but only matching ones can enforce them, and then thinly: as a by-p

---

### [4] SLoSa: Small, Low-Power, and Safe Foundation Models for Robotic Task Planning

**链接**: https://arxiv.org/abs/2610.28955
**作者**: Weizhe Xu, Jialiang Fan, Essien Taylor, Zijun Wang, Russell Joseph, and Fanxin Kong
**来源**: cs.RO cs.AI cs.LO
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safe robotic task planning requires planners that can reliably achieve task goals while satisfying safety constraints. Classical planners search over explicit symbolic task representations and can provide formal guarantees with respect to encoded safety constraints, but require rigid input formats. Their computational cost also increases rapidly with the search space. In contrast, large language models (LLMs) offer flexible task interfaces and strong generalization capabilities, but they are large, power-hungry, and pre-trained with little robot-specific safety data and knowledge. Thus, they can be difficult to deploy locally on robotic systems with limited resources. To address these limitations, we present SLoSa, a neuro-symbolic compression and fine-tuning framework for training foundation-model-based robotic task planners with Small size, Low power demand, and Safety awareness. The framework first constructs a safety-aware dataset using classical planners, an advanced teacher LLM, 

---

### [5] LLM-Based Exogenous World Modeling for Dynamic Scheduling

**链接**: https://arxiv.org/abs/2610.29308
**作者**: Ni Zhang, Haofeng Yuan, Jianan Zhou, Shiji Song, Zhiguang Cao
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic scheduling requires dispatching online arrivals while anticipating future jobs, as poor decisions can compound downstream costs under nonlinear tardiness objectives. We show that a pretrained large language model (LLM) can serve as the exogenous component of a structured world model, forecasting uncertain future job arrivals. Specifically, we exploit an afterstate decomposition, which separates known deterministic shop transitions from uncertain exogenous job arrivals, enabling the LLM to forecast only the latter through a compact belief representation. Building on this, we develop Afterstate World-Model Planning (AWMP), which combines an evolved, belief-conditioned dispatching strategy with short scenario-based rollouts. A surprise-triggered refresh mechanism queries the LLM only when newly observed arrivals deviate sufficiently from previous forecast, and online residual self-calibration further conditions the LLM on its recent forecast errors to handle nonstationary arrivals

---

### [6] Steering Black-Box Large Language Model Agents with Pitfall Anticipation World Model

**链接**: https://arxiv.org/abs/2610.29139
**作者**: Jiongxiao Wang, Han Ding, Youzhi Luo, Yawei Wang, Yun Zhou, Linbo Liu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier black-box Large Language Model (LLM) agents are proficient at long-horizon reasoning and precise action generation. However, when it comes to a specific agentic task, they have no internalized knowledge of how that particular environment unfolds. A world model offers a natural remedy, providing the agent with environment specific knowledge by foreseeing how the environment will respond to the action it is about to take. Prior world models for LLM agents mainly predict next observations at each step, which is costly and often uninformative because individual observations provide limited task-relevant guidance and not every step requires call for foresight. This raises a key question: what a world model should predict and when should it be invoked for agentic tasks? Our pilot study suggests that world model guidance is most useful when it anticipates pitfalls within a bounded multi-step future. Motivated by this, we introduce Pitfall Anticipation World Model (PAWM), which select

---

### [7] Inheritance as an Admission Test for LLM Prompt Merge Operators

**链接**: https://arxiv.org/abs/2610.29023
**作者**: Zan-Kai Chong, Hiroyuki Ohsaki, Bryan Ng
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are often improved by iterating until a fixed verifier is done. Once that verifier saturates, the loop has nothing left to climb. We instead score agents against the current population, and a frozen panel records whether anyone got better. The panel mean can rise inside the seeds by elimination alone. We therefore count a run as training only when its final mean beats the best generation-zero member. A merge is admitted only when the child moves toward the donor, past the child the same operator produces at zero dose, and the lower confidence bound on that movement reaches half the requested dose. That is the admission test. A detectable shortfall rejects the operator, and the test is otherwise undetermined. We keep realised fitness \phi as the selector and reference performance \theta as the unused ruler. Every measurement uses gemini-3.1-flash-lite on one negotiation task, and no fixed-oracle arm was run. In the open loop, tactic append grafts short 

---

### [8] A Stratified Multi-Rater Evaluation of LLM-Based Virtual Standardized Patients with a Deployed Data-Generation Platform

**链接**: https://arxiv.org/abs/2610.29312
**作者**: Yongjin Yi, Jinyong Park, Sejoong Kim
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Objective Structured Clinical Examination (OSCE) is widely used to assess clinical communication skills in medical education, requiring trainees to take histories and reason clinically with standardized patients (SPs). Large language model (LLM)-based virtual standardized patients (VSPs), typically built by persona-injected prompting, offer a practical alternative. However, existing evaluations rely on a single backbone LLM, small human rater panels, or LLM-as-a-judge scoring without an utterance-aligned human-expert reference, and so cannot identify the specific shortcomings of individual models. We evaluated four LLMs (GPT-4o, Claude 3.5 Sonnet, Llama-3.1 70B, and HyperCLOVA X), spanning commercial, open-source and Korean-developed models, against a human-expert reference across three Korean OSCE cases (hematuria, fever in pregnancy, and chronic cough). In a double-blind, fully crossed design, 17 senior medical-student raters scored every model utterance on three sentence-level a

---

### [9] A Mechanistic Study of Automated Failure Attribution in LLM-based Agentic Systems

**链接**: https://arxiv.org/abs/2610.28811
**作者**: Wendy Zheng, Liang Wu, Yinhan He, Mayank Darbari, Jundong Li, Liangjie Hong
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic systems have demonstrated strong capabilities on complex tasks by enabling multiple interacting large language model (LLM)-based agents to collaborate and execute subtasks in parallel. However, this collaborative structure introduces new challenges for reliably evaluating and diagnosing system failures, particularly failure attribution: tracing a system's execution to identify the agent step responsible for an incorrect final outcome. Because manually performing this task is time- and labor-intensive, recent work has turned to LLMs as judges to automate the process, referred to as automated failure attribution (AFA). These approaches assume that a sufficiently capable model can infer the failing step directly from an interaction transcript. In practice, however, direct prompting often performs poorly, which motivates follow-up work that explores various ways to improve AFA performance, including alternative prompting strategies and inference-time interventions. In this paper, w

---

### [10] DynaWeave: Learning to Adapt through Dynamic Scenario Synthesis

**链接**: https://arxiv.org/abs/2610.29443
**作者**: Xuan Yang, Chunxiao Liu, Hongsheng Xin, Hao Xu, Ning Miao
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly use tools to complete tasks in stateful environments. However, many training environments remain largely static apart from changes caused by the agent's own actions, whereas external events introduced by other users, services, or sudden contingencies in real environments can invalidate ongoing plans. To address this gap, we introduce DynaWeave, an automated synthesis framework that transforms existing static tasks into verifiable dynamic scenarios. The framework generates exogenous events relevant to each task, covering changes in task requirements, environment state, and external information. It uses directed acyclic graphs (DAGs) to represent dependencies between events and an execution engine to activate them during agent interaction. A dynamic verifier revises only the evaluation checks affected by events that actually occur and retains all other checks. Using DynaWeave, we collect 2,095 verified interaction trajectories across 36 envi

---

### [11] From Text to Voice: A Reproducible and Verifiable Framework for Evaluating Tool Calling LLM Agents

**链接**: https://arxiv.org/abs/2605.15104
**作者**: Md Tahmid Rahman Laskar, Xue-Yong Fu, Seyyed Saeed Sarfjoo, Quinten McNamara, Jonas Robertson, Shashi Bhushan TN
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] Toward Safe LLM Agents: A Survey of Specification, Verification, and Enforcement

**链接**: https://arxiv.org/abs/2608.14590
**作者**: Pierre Dantas, Lucas Cordeiro, Ehsan Nowroozi, Norbert Tihanyi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [13] Behavior Beyond Text: Evaluating Refusal Transfer Failure in LLM Agents

**链接**: https://arxiv.org/abs/2610.28982
**作者**: Ekagra Gupta, Raj Saha, Aniekan-Abasi Inyang, Adam Al Gharib
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While large language models are increasingly deployed as tool-calling agents, their safety evaluations still focus primarily on their ability to refuse harmful requests in text. We investigate whether the refusal behavior in text transfers to tool use. We construct a benchmark of 2,304 prompts across four domains, consisting of matched triplets that present the same harmful or benign request in text-only, standard tool-enabled, and adversarially framed tool-enabled settings. We then assess tool-call safety using 20 predefined forbidden actions. Testing five models of varying sizes and families, we find that requests refused in text frequently result in unsafe tool calls. Under standard tool-enabled prompting, this divergence occurs for 10-52 percent of harmful requests refused in chat. To mechanistically investigate this gap, we identify a refusal-associated direction in the residual stream of each of the five models. We find that in tool-enabled contexts, the activations along this di

---

### [14] FaultGene: LLM-Assisted Fault-Augmented Test Generation for Hardware-in-the-Loop Validation of Autonomous Driving Systems

**链接**: https://arxiv.org/abs/2610.29969
**作者**: Chaoran Yuan and Fadi Kurdahi
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable validation of autonomous driving cyber-physical systems requires testing not only nominal driving behavior but also failures arising from faults in sensing and embedded computation. Physical road testing provides realistic system behavior but is costly and difficult to reproduce, while simulation enables scalable evaluation but cannot fully capture hardware-dependent behavior and fault propagation. Hardware-in-the-loop (HIL) validation bridges this gap by executing the driving stack on real embedded hardware within a simulated environment. However, preparing fault-augmented scenarios for HIL testing remains largely a manual process, limiting test coverage, scalability, and efficiency. We present FaultGene, an LLM-assisted framework for automated generation of executable fault-augmented tests for HIL fault-resilience validation. Given a baseline Scenic/CARLA scenario and a structured fault specification, FaultGene generates a fault-augmented test case that captures the effects 

---

### [15] Benchmarking and Error Analysis of Deep Search and Deep Research LLM Agents

**链接**: https://arxiv.org/abs/2610.29346
**作者**: Zixuan Yu, Zhenheng Tang, Xiaowen Chu, Bo Han
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Models (LLMs) evolve into autonomous Deep Search and Deep Research Agents capable of executing long-horizon, multi-step tasks, evaluating their reliability becomes increasingly critical. However, existing evaluation paradigms predominantly focus on final task outcomes, leaving a significant gap in understanding the intermediate execution traces, where agents are highly susceptible to various errors. To address this critical gap, we introduce a comprehensive methodology and analytical framework designed specifically to diagnose errors in intermediate workflows. Building upon this framework, we establish a structured taxonomy that categorizes these vulnerabilities into two primary dimensions: System-Level Errors and Task-Level Errors. Through a systematic examination of step-by-step execution traces and agent-environment interactions, we reveal how these underlying errors affect overall performance. Finally, through empirical experiments and systematic analysis of the i

---

### [16] Controlling Output Rankings in LLM-Based Search via Generative Engine Optimization

**链接**: https://arxiv.org/abs/2602.03608
**作者**: Haibo Jin, Huimin Zeng, Yifeng Luo, and Haohan Wang
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [17] TabAgent: Distilling LLM Agent Components into Cheap Classifiers

**链接**: https://arxiv.org/abs/2602.16429
**作者**: Ido Levy, Segev Shlomov, Avi Yaeli, Nir Mashkif, Asaf Adi, Yinon Goldshtein 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] Generalized CycleGRPO for Fine-Grained Multimodal Understanding and Grounding

**链接**: https://arxiv.org/abs/2610.29552
**作者**: Xin Zhang, Haochen Wang, Beibei Lin, Zhaoxiang Zhang, Robby T. Tan, Jason Li 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-grained multimodal intelligence requires models to both understand a designated region and localize it from language. Existing methods learn these directions with separate objectives and task-specific annotations. We present Generalized CycleGRPO, the first unified reinforcement learning framework coupling region understanding and localization across spatial, temporal, and spatio-temporal domains. Given a region, a multimodal large language model generates candidate descriptions and then localizes each description to reconstruct the input region. Reconstruction overlap provides a verifiable reward for captioning, while individual localization rewards improve the inverse mapping. A common region-space formulation extends this cycle from image masks and boxes to video intervals and timestamped spatial evidence, without reference captions or an external language-model judge during reinforcement learning. In videos, the cycle encourages descriptions that distinguish a target event fro

---

### [19] Environment Duels: A Microcosm of LLM Co-Evolution

**链接**: https://arxiv.org/abs/2610.30116
**作者**: Shibo Jin, Zhiqiu Xu, Yiling Zou, Shangyu Gong, Mayur Naik
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Through a tangle of real-world interactions, from synthetic training pipelines to data shared on the open web, frontier LLMs absorb what their predecessors and competitors create. How well does each model play its role in this ecosystem, as a creator and as a solver? We introduce Environment Duels, a dynamic agentic benchmark that evaluates both capabilities on interactive environments. Each model writes environments, each with a privileged hint, aiming for tasks that capable solvers fail without the hint and pass with it. Across nine frontier LLMs, solving and authoring prove to be distinct skills: the strongest solvers are not the strongest authors, while smaller models learn more from how others played and write the hardest environments and the most useful hints. Beyond the scores, the pairwise interactions form a microcosm of how models affect one another. Head-to-head outcomes are transitive and so yield a stable ranking; independent authors converge on the same designs; and in a 

---

### [20] To Keep or Not to Keep: Learning KV Cache Retention in Disaggregated LLM Serving Systems

**链接**: https://arxiv.org/abs/2610.28637
**作者**: Dong Liu and Yanxuan Yu and Eric Jiang and Shu Wang and Ying Nian Wu
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Disaggregated \textsc{LLM} serving separates prefill and decode across node pools, placing a network fabric between \textsc{KV}-cache computation and consumption. This breaks a key assumption of classical cache policies: a miss no longer incurs only local recomputation, but also network transfer to the decode node. Likewise, admitting a block to the global cache requires an additional transfer, so poor retention decisions waste both memory and bandwidth. We present \textbf{KVLearn}, a learning-based framework for cost-aware \textsc{KV}-cache retention in disaggregated serving. KVLearn includes: (i) a lightweight Prefix Reuse Predictor (\textsc{PRP}) that estimates reuse probability from structural and temporal prefix features without modifying model weights; (ii) a Cost-Aware Retention Score (\textsc{CARS}) that converts reuse probability into keep/admit decisions using recomputation, transfer, and storage costs; and (iii) an Adaptive Threshold Controller (\textsc{ATC}) that adjusts ad

---

### [21] Replayable Financial Agents: A Determinism-Faithfulness Assurance Harness for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2601.15322
**作者**: Raffi Khatchadourian
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] ALIAS: Evaluating Performance and Memorization in LLM-Written TLA+ Specifications

**链接**: https://arxiv.org/abs/2610.29767
**作者**: Arslan Bisharat, Mujtaba Nazari, Khushboo Bhadauria, Brian Ortiz, Eric Spencer, Beatriz Santos 等 (10 人)
**来源**: cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memorization inflates the benchmark scores of large language models (LLMs), since a model can reproduce answers it saw in training. Researchers test for it with consistent identifier renaming (CIR), which gives every identifier in a task a new name, and treat a lower score on the renamed task as evidence of recall. We test this method on the Temporal Logic of Actions Plus (TLA+) language, whose model checker acts as an oracle by confirming whether a renamed task preserves the exact behaviors of the original. Across 111 TLA+-Bench tasks, renaming lowers the correctness of Claude Opus 4.8 from 28% to 18% and of GPT-5 from 9% to 7%. Most of this decrease comes from how the test grades, which requires exact names that most descriptions never state. Grading by behavior shrinks the decrease to about 3 percentage points for Opus 4.8 and to 0 for GPT-5. In two model families fine-tuned on disjoint halves of the tasks, renaming removes about half of the training gain in likelihood and costs 4.9

---

### [23] Hyperdimensional Probe: Decoding LLM Representations via Vector Symbolic Architectures

**链接**: https://arxiv.org/abs/2509.25045
**作者**: Marco Bronzini, Carlo Nicolini, Bruno Lepri, Jacopo Staiano, Andrea Passerini
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] Circuits of LLM Classifiers

**链接**: https://arxiv.org/abs/2610.30076
**作者**: Hadi Khalaf, Sajani Vithana, Kunal Talreja, Haewon Jeong, Viveck R. Cadambe, Flavio Calmon
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models make it easy to build classifiers by simply prompting a model with the sample to classify. However, their predictions are neither deterministic nor uniformly reliable across samples. How can we combine predictions from different models to improve reliability? We view LLM classifiers as noisy measurement instruments of an underlying target label. Our goal is to maximize average classification accuracy at a given average query cost. To this end, we introduce circuits that organize LLM classifiers into an adaptive sequence of queries and decisions. We then characterize the optimal circuit, obtain the fundamental limits of achievable accuracy, and provide practical insights on realizing the optimal circuit. Across seven classification tasks spanning safety, health, political science, human preference, agent evaluation, decision-making and reasoning, our method improves the cost-accuracy frontier over routing and cascading baselines.

---

### [25] Same Probabilities, Different Advice: Gain-Loss Framing Effects in High-Stakes LLM Decision Support

**链接**: https://arxiv.org/abs/2610.29294
**作者**: Yuyao Zhang, Yakun Cui, Han Zhu, Jinsong Lu, Yike Guo, Sirui Han
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to support consequential decisions, yet their reliability under equivalent representations of uncertainty remains unclear. Existing work has documented prompt sensitivity, cognitive biases, and confidence miscalibration, but it is still unknown whether high-stakes advice changes when the same probability is expressed through complementary gain and loss frames. We introduce FrameBench-HPS, a controlled benchmark of 2,880 prompts derived from 240 high-stakes scenarios across healthcare, finance, education/career, and legal/consumer-rights domains. Across seven LLMs, gain-loss framing changes the recommendation category in 32.4% of complete groups, with most changes involving uncertainty rather than direct reversals. Human evaluation confirms corresponding shifts in perceived risk and directiveness. Robustness experiments show that framing effects persist under conversational paraphrases and exceed ordinary repeated-generation variability

---

### [26] Act on Your Behalf, Beyond Your Authorization: Benchmarking LLM Agent Authorization Alignment

**链接**: https://arxiv.org/abs/2610.27548
**作者**: Zhiping Zhang, Franklin Mingzhe Li, Zihao Huang, Tianshi Li
**来源**: cs.AI cs.CR cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] The Butterfly Effect in LLM Social Simulations: From Architecture Sensitivity to Robustness Audits

**链接**: https://arxiv.org/abs/2610.28981
**作者**: Jinyi Ye, Lei Cao, Ding Chen, Emilio Ferrara
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A butterfly effect occurs when a local perturbation propagates through a system and produces divergence in its collective outcome. In LLM social simulations, this creates a particular challenge for scientific inference: sensitivity to implementation choices can enter agent interactions and alter the collective outcomes on which scientific claims are based. We study this problem through a repeated Prisoner's Dilemma and a social-media echo chamber, spanning representation- and design-level perturbations across four LLM families. We find that controlled perturbations can substantially alter collective outcomes, with sensitivity varying across both perturbations and models. In the Prisoner's Dilemma, changing only the representation of a matched persona shifts two-agent cooperation by 75.2 percentage points for GPT-5.2, while game framing and memory representation produce smaller or less consistent effects. Multi-agent interaction further reshapes representation sensitivity, producing amp

---

### [28] An important Bottleneck in LLM Optimizers: Principle-Level Local Optima

**链接**: https://arxiv.org/abs/2610.24291
**作者**: Nian Ran, Tianhe Jia, Zhengyang Mu, Yue Wang, Sebastian Brulin, Markus Olhofer 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] Parallel Thinking for Large Language Model with Path Diversity

**链接**: https://arxiv.org/abs/2610.29501
**作者**: Jiaru Qian, Yihong Dong, Xue Jiang, Chun-Wah Hsu, Zhi Jin, Ge Li
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parallel thinking has emerged as a promising paradigm for enhancing the reasoning capabilities of Large Language Models (LLMs) by exploring multiple reasoning paths simultaneously. However, we identify that parallel thinking via Reinforcement Learning (RL) typically suffers from the mode collapse of reasoning paths, where parallel thinking trajectories degenerate into similar ones. This homogeneity undermines the fundamental motivation of parallel thinking, that is, maintaining multiple hypotheses concurrently to prevent premature loss into a suboptimal solution. In this paper, we propose Diverse Parallel Thinking (DPT), a simple yet effective RL approach for parallel thinking designed to encourage path diversity. DPT rewards the model to develop distinct reasoning strategies by penalizing the prefix similarity of parallel thinking paths, thereby enhancing a more comprehensive exploration of the reasoning space. We conduct various experiments and analyses across multiple reasoning benc

---

### [30] ToM2Vec: Continuous Theory-of-Mind Tokens for Multi-Agent Coordination

**链接**: https://arxiv.org/abs/2610.29934
**作者**: Nithin Sivakumaran, Ali Payani, Hyunji Lee, Mohit Bansal, Elias Stengel-Eskin
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Forming an accurate theory-of-mind (ToM) is key to successful multi-agent collaboration and requires reasoning under uncertainty to capture multiple possible partner states. This is hard to do in the text representation space native to large language model (LLM) agents, which more easily describe a single partner state. To address this challenge, we introduce ToM2Vec, which learns to form abstract theories-of-mind in a rich latent space via a fixed budget of continuous reasoning tokens. During training, supervision for these tokens comes from the partner's actual thoughts, which the ToM tokens are trained to abstract and match. At test-time, ToM tokens are generated by each agent and act as conditioners for that agent's thoughts and actions. Across several environments covering collaborative, competitive, and mixed-motive settings (Overcooked-AI, multiparty negotiation, Decrypto, Hanabi, and Collab Escape/Capture), we evaluate ToM2Vec's ability to support multi-agent interactions and c

---

### [31] Nominate-then-Adjudicate: LLM-Assisted One-Pass and Per-Instance MIP Solver Tuning

**链接**: https://arxiv.org/abs/2610.29391
**作者**: Yifan Zhao, Qianyang Zhao, Xinyu Guan, Kai Wei, and Yuming Deng
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixed-integer programming solvers expose hundreds or even thousands of parameters whose best setting varies per instance, yet per-instance search is prohibitively expensive. We frame this as configuration for heterogeneous Big Data optimization workloads and propose a nominate-then-adjudicate pipeline built around two design choices. First, a fixed portfolio is sampled once and reused across instances, removing per-instance configuration search at inference; on the evaluated families, the resulting shortlist retains substantial oracle headroom, making selection within it the empirical focus. Second, the fixed 20-feature representation can map structurally different instances to the same vector, preventing a feature-only selector from distinguishing them even when they prefer different configurations. The foundation model receives no task-specific weight updates, and selection is one-pass: one model call and no solver calls at inference. The study represents structural Variety through d

---

### [32] PerMIT: Securing Persistent Memory for LLM Agents via Machine-Checked Integrity Theorems and Scalable Community Trust

**链接**: https://arxiv.org/abs/2610.28987
**作者**: Tanqiu Jiang, Min Bai, Sadat Shahriar, Wanyu Du, Sandesh Swamy
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent memory is a largely undefended surface for injection and poisoning, and the same risk limits memory sharing among agents. We present PerMIT, a memory architecture with provable integrity guarantees under an explicit trust assumption: only user-typed inputs and values confirmed at a gate are trusted. PerMIT mediates the release and use of untrusted environment-derived values through a finite memory interface, while preserving agent-driven multi-turn planning and tool choice. Over this finite interface, we prove two integrity theorems that are also machine-checked in Lean 4, which together ensure that environment-derived memory reaches a sensitive action only if confirmed at the gate and influences the agent's behavior only through what the gate displays. Every attack in our threat model thereby reduces to a single auditable decision, which a human, an LLM verifier, or both can make in practice. On Trojan Hippo, PerMIT records zero observed attack success with self-verificatio

---

### [33] AgentMonopoly: Behavioral Patterns and Persona Control in LLM Agents

**链接**: https://arxiv.org/abs/2610.29330
**作者**: Changshun Wu, Mengyu Li, Mathis Marsault, Xiaowei Huang, Chih-Hong Cheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How do LLM agents' strategies differ, and how much can instructions to adopt a persona change their behavior over a game? We study these questions with AgentMonopoly, an environment where agents communicate, buy and trade properties, and make decisions that affect later turns. We compare models from four families, each at two sizes, in games with identical models, different sizes of the same family, or different families. We also assign one agent a persona, a description of how it should behave, intended to change a tendency observed in games without that persona. The tested models differ in how often they trade, waive rent, and manage cash and properties. Larger models do not consistently win more games. Persona instructions change the words agents use and some of their actions, but the changes do not always match the role across all decisions. These results show why persona following should be assessed through actions and outcomes as well as language. As our findings are conditional 

---

### [34] Every Part Has Its Role: Part-of-Speech Effects in LLM Post-Training

**链接**: https://arxiv.org/abs/2610.29843
**作者**: Laya Iyer, Chen Shani
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are typically trained with next-token prediction (NTP), which rewards predicting specific tokens rather than explicitly accounting for the semantic similarities between different words or expressions. Prior work has addressed this limitation by augmenting training data with minimally varying sentences that replace a target word with conceptually related alternatives, e.g., "The tired coach ran home" $\rightarrow$ {"The tired trainer ran home", "The tired instructor ran home", ...}. Such concept augmentation improves performance, but it remains unclear whether its effectiveness depends on where in the sentence the concept is expressed. We reproduce and extend prior work $\textit{beyond nouns}$ to verbs and adjectives, asking whether the part of speech (POS) carrying the concept signal affects perplexity and downstream performance. We find different patterns across evaluation settings: concept augmentation improves perplexity most consistently on news, independent o

---

### [35] RelAgent: LLM Agents as Data Scientists for Relational Learning

**链接**: https://arxiv.org/abs/2605.07840
**作者**: Xingyue Huang, Louis Tichelman, Jinwoo Kim, Krzysztof Olejniczak, \.Ismail \.Ilkan Ceylan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Beyond source attribution: Address authorship and comparability decisions in an LLM-built scholarly knowledge graph

**链接**: https://arxiv.org/abs/2610.28663
**作者**: Ksenia Kozha (American University of Cyprus), PaRAGraph Research Project
**来源**: cs.DL cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A knowledge graph needs a stable address for its evidence even where the literature offers competing classifications and agrees on none. Yet an address chosen for retrieval readily passes for the only classification available. This happens whenever records gathered under one name concern units that differ in boundaries, rank, or the criteria by which they are described or counted. In Sinitic dialectology the same localities recur in schemes whose units differ in membership and rank, and a unit may change its affiliation when the evidence for its diagnosis changes. Two tone counts, each quoted faithfully, may still count different things. The taxonomy of an entire field thus comes to rest on the unstable frame of a literature that contradicts itself. Neither verifying a quotation nor searching for conflicting values detects these differences. I distinguish the working address that gathers candidate evidence, the category that the source defines and the decision that admits a passage to 

---

### [37] Black-Box Red-Teaming of Multi-Agent Systems via Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.28966
**作者**: Yuqi Jia, Hangsheng Zhang, Chenxi Liu, Junjie Liang, Xun Chen
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly deployed in multi-agent systems (MAS) to accomplish complex tasks. Prior black-box red-teaming attacks mainly focus on single agents, but we find that these methods are far less effective in MAS, where multiple sub-agents may not directly interact with the user. Therefore, we introduce ReMAS, the first reinforcement learning-based red-teaming framework tailored to MASs, which fine-tunes attacker LLMs to generate effective adversarial prompts for system prompt extraction. The framework follows a two-step process: first, a rewrite stage refines base attack prompts to increase extraction success, and second, a template generation stage constructs attack templates that improve the likelihood of invoking specific sub-agents and thus revealing their system prompts. Extensive experiments show that our method substantially improves attack success rates compared to existing black-box attacks, with transferability across different backend LLMs a

---

### [38] InfoQuant: Shaping Activation Distributions for Low-Bit LLM Quantization

**链接**: https://arxiv.org/abs/2605.26175
**作者**: Ke Li, Dong An, Xiaoling Zang, Can Ye, Liang Xie, Qibo Qiu 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Quant-Arena: Benchmarking LLM Agents for Quantitative Trading Research

**链接**: https://arxiv.org/abs/2610.30113
**作者**: Houde Qian, Zheng Jiang, Wenyi Li, Chenxi Xu, Xinjie Lin, Yuzhao Peng 等 (10 人)
**来源**: cs.CL cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantitative research is an iterative loop: a researcher proposes a market hypothesis, implements it as an executable signal, tests it on historical data, and decides what to keep. Existing benchmarks score formulas, code, or individual trading decisions, leaving open whether large language models (LLMs) can complete this loop and produce strategies that work beyond the research period. We introduce Quant-Arena, a benchmark and public leaderboard for end-to-end quantitative research on real A-share market data. A model constructs features and stock-scoring code, receives feedback only on 2022--2023, and freezes one strategy for assessment on the sealed year 2024. A cash-account evaluator applies trading constraints and costs, including market impact estimated from a simulated order book. Scores are dominated by realized excess return and complemented by signal quality and the diversity of features used by the strategy. We evaluate nine frontier models, among which GPT-6 Astra scores hi

---

### [40] CrashGym: Measuring the Decision Value of Experimentation for LLM Agents in Counterfactual Market Crashes

**链接**: https://arxiv.org/abs/2610.29245
**作者**: Haocheng Lu, Haoxuan Cheng, Mingyang Chen, Minjun Zhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents are increasingly asked to run experiments, yet benchmarks rarely measure whether those experiments improve the decisions they are meant to inform. We introduce CrashGym, a deterministic, replayable limit-order-book simulator in which an agent must choose between a deleveraging intervention and a liquidity backstop for a market about to suffer a shock-triggered crash. Before committing, the agent may query intervention experiments in a laboratory realization of the market. Its choice is then scored on an independently seeded target realization in which the simulator executes every feasible intervention, so regret relative to the best intervention is computed by directly simulating every alternative on the same target repeats, with no human or model-based judging. The simulator implements each amplification channel---persistent price impact, liquidity withdrawal, margin-driven liquidation, and an evolving strategy mix---as an explicit mechanism that can be switched 

---

### [41] Self-Improving Agents with World Model Predictive Paths

**链接**: https://arxiv.org/abs/2610.28945
**作者**: Haori Lu, Tianyu Gao, Yaoyao Liu, Yingying Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly expected to interact with environments and improve their decisions during deployment. However, how anticipating future outcomes and drawing on accumulated interaction experience can jointly support decision-making remains underexplored. We propose a test-time framework, inspired by Model Predictive Path Integral (MPPI) control, that combines multi-branch predictive analysis with experience-based adaptation. At each step, the agent proposes multiple candidate actions and imagines their outcomes with a world model, so that alternatives can be compared without being executed in the environment. Since language environments provide neither explicit dynamics nor costs, the predicted outcomes are evaluated for task progress and risk, and MPPI-style weights over the resulting costs guide the final decision. A dual-branch experience memory enables self-improvement: the planner branch refines candidate generation and action selection, while the 

---

### [42] Model Capacity Frontier: A Development Framework for LLM-Supported Social Simulation

**链接**: https://arxiv.org/abs/2610.24168
**作者**: Patrick Zhao, Yuxuan Li, Hirokazu Shirado
**来源**: cs.MA cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Metamodel-Guided LLM Decoding for Consistent DSL Generation

**链接**: https://arxiv.org/abs/2610.29749
**作者**: Boqi Chen and Aren A. Babikian and Jos\'e Antonio Hern\'andez L\'opez
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate software engineering artifacts written in domain-specific languages (DSLs). Correct DSL instances usually must comply with not only the concrete syntax but also the abstract syntax defined by a metamodel augmented with semantic well-formedness constraints. Existing constrained decoding approaches typically guarantee compliance only with concrete syntax or with a limited set of semantic constraints expressed over the generated text, making metamodel-level constraint consistency difficult to enforce during generation. We present MeMoDecode: a decoding framework that enforces a DSL's concrete syntax, abstract syntax, and well-formedness constraints jointly. Specifically, whenever the LLM generates a complete metamodel concept, MeMoDecode incrementally maps the current output to a partial model and verifies whether it can still be completed into a consistent instance. We combine MeMoDecode with a simple retry mechanism that res

---

### [44] ClusterFusion: Hybrid Clustering with Embedding Guidance and LLM Adaptation

**链接**: https://arxiv.org/abs/2512.04350
**作者**: Yiming Xu, Yuan Yuan, Vijay Viswanathan, Graham Neubig
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] Beyond Binary Labels: Diagnostic Evaluation of LLM Safety with Prompt-Level Rubrics

**链接**: https://arxiv.org/abs/2610.29225
**作者**: Hongyu Li, Xinlong Huang, Zhan Yu, Jing Zhao, Zhe Zhao, Juntao Zhong 等 (10 人)
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current LLM safety benchmarks predominantly rely on binary safe or unsafe labels, lacking explanatory depth and suffering from low consistency across automated judges. To address this, we introduce DiagSafe, a diagnostic evaluation framework that moves beyond binary classification by employing prompt-level rubrics. Grounded in globally applicable AI safety policies, each rubric provides explicit criteria along two dimensions: safety, which targets concrete harms with specific exemptions to suppress false positives, and usefulness, which independently evaluates instruction fulfillment. To ensure a robust and realistic evaluation, we construct a bilingual (English-Chinese) benchmark grounded in a comprehensive 84-label safety taxonomy, consisting of two subsets: DiagBase, which covers single- and multi-turn prompts with direct harmful queries and template-based jailbreaks, and DiagAttack, which embeds harmful intents into complex instruction-following tasks to form challenging instructio

---

### [46] Complexity-Aware Surgical Video Reasoning Segmentation with Digital Twin and Context Memory

**链接**: https://arxiv.org/abs/2610.28776
**作者**: Yiqing Shen, Mathias Unberath
**来源**: cs.CV
**匹配关键词**: Foundation Models, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional surgical segmentation relies on closed-set categories or explicit text queries, which cannot resolve implicit queries that require reasoning about workflows, instrument functions, and temporal relationships. To address these limitations, we propose SurgReasonSeg, a complexity-aware method that brings reasoning segmentation over digital twin (DT) representations to surgical video. Specifically, SurgReasonSeg constructs DT representations from surgical foundation models and trains two low-rank adapters (LoRA) of one large language model with reinforcement learning (RL), each specialized for a different query complexity. A lightweight router, also trained with RL, selects between the two adapters to balance latency against accuracy. SurgReasonSeg also sets the temporal context with an adaptive sliding window conditioned on query complexity and workflow phase, and retrieves relevant historical cases from a surgical context memory by workflow similarity and procedural relevance

---

### [47] HiddenLens: A Multi-Layer LLM Framework for Detecting and Resolving Hidden Assumptions in Software Requirements

**链接**: https://arxiv.org/abs/2610.29996
**作者**: Tanu Singh, Aashna Suman, Vinod Patidar
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language software requirements often omit assumptions about performance, operating conditions, user behaviour, and domain constraints, affecting architecture, testing, and deployment. If undiscovered until implementation, resolving them is far more costly than addressing them early. Although ambiguity and vagueness are widely studied, less attention has been given to assumptions embedded in requirements that appear clear and reasonable. We propose HiddenLens, a novel six-layer BERT-LLM pipeline and, to our knowledge, the first framework engineered to detect, classify, question, and resolve hidden assumptions rather than merely flag ambiguity. Layer 1 uses BERT attention entropy to localise unresolved spans; Layer 2 uses CoT-prompted LLM reasoning to articulate each assumption and its failure risk; Layer 3 uses fine-tuned BERT to classify assumptions into six non-functional requirement categories: performance, security, scalability, usability, reliability, and domain; Layer 4 ge

---

### [48] Just Respect the Semantics: Image-Token Compression via Pre-LLM Semantic Variable-Resolution Tokenization and In-LLM Relevance Pruning

**链接**: https://arxiv.org/abs/2610.18690
**作者**: Tianhao Fu, Austin Wang, Charles Chen, Roby Aldave-Garza, Victor Xie, Xiyue Jiao 等 (8 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] In-Context Bias Propagation in LLM-Based Tabular Data Generation

**链接**: https://arxiv.org/abs/2506.09630
**作者**: Pol G.Recasens, Alberto Gutierrez, Jordi Torres, Josep.Ll Berral, Javier Carnerero-Cano, Anisa Halimi 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Does Every Instance Count Equally? Order Effects in LLM Multi-Instance Processing

**链接**: https://arxiv.org/abs/2610.29057
**作者**: Jingxuan Chen, Mohammad Taher Pilehvar, Jose Camacho-Collados
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users increasingly rely on large language models (LLMs) to analyse collections of independent inputs, such as product reviews or social media posts, and return a single aggregated answer. This setting requires multi-instance processing (MIP), where a model combines information from multiple instances into one prediction. We study a task in which the model must infer a binary label for each instance, and identify the most frequent label among the full instance set. The correct answer should be invariant to instance order. By evaluating fifteen LLMs across five datasets and seven instance order patterns, with each instance set held fixed across patterns, we find substantial order sensitivity. Accuracy can differ by about 90 percentage points between the best and worst order patterns, with models generally more accurate when majority-label instances appear at the start than when they appear in the middle or at the end. For subsets of models, available reasoning traces and gradient-based a

---

### [51] Lineage-Aware Search Control for LLM-Based Evolutionary Factor Mining

**链接**: https://arxiv.org/abs/2610.29663
**作者**: Xintong Liu, Chenkai Zhang, Yanzhao Ma, Peng Yang
**来源**: q-fin.CP cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formulaic alpha factor mining searches for symbolic expressions that transform market data into predictive signals. Recent LLM-based evolutionary factor mining methods use large language models as semantic variation operators. Under the conventional LLM-EA paradigm, stochastic variation and fitness-based selection can leave the search weakly directed and concentrated around a narrow set of structurally similar factors. We argue that these limitations arise because current methods mainly organize search at the individual and population levels, leaving lineage-level control underused. A lineage connects successive factor variants through evolutionary descent. We propose LineageEvo, which uses lineage in two coupled forms of search control: (1) lineage-conditioned LLM variation, which distills Lineage-Scoped Search Experience into operator-specific priors and fuses them with global operator priors, providing persistent, lineage-relevant guidance for LLM generation; and (2) lineage-stratif

---

### [52] PersonalAI 2.0: Enhancing knowledge graph traversal/retrieval with planning mechanism for Personalized LLM Agents

**链接**: https://arxiv.org/abs/2605.13481
**作者**: Mikhail Menschikov, Matvey Iskornev, Alexander Kharitonov, Alina Bogdanova, Mikhail Belkin, Ekaterina Lisitsyna 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Biological Context Does Not Reliably Improve LLM-Guided Experimental Optimization

**链接**: https://arxiv.org/abs/2605.15341
**作者**: Marilyn Zhang, Tianfeng Chen, Mark E. Whiting
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Building a Nested LADDER for LLM Unstructured Post-Training Pruning

**链接**: https://arxiv.org/abs/2610.28773
**作者**: Nicol\'as Mauricio Cuadrado \'Avila, Ivo Gollini Navarrete, Martin Tak\'a\v{c}, Samuel Horv\'ath
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Non-uniform allocation can improve post-training pruning of large language models, yet quality can still degrade sharply at high sparsity. To control degradation as sparsity increases, we introduce LADDER (Layer-Wise Allocation via Damage-Driven Evaluation and Refinement), which allocates sparsity incrementally. At each step, it evaluates pruning an additional fraction of weights from each eligible layer and commits the layer update that causes the least end-to-end degradation per removed parameter. This process produces non-uniform sparsity profiles and exactly nested masks across multiple budgets. We evaluate LADDER on five OPT, Llama, and Qwen models across 10-90% sparsity, using SparseGPT as its candidate-generation backend and comparing against uniform and adaptive allocation baselines. Results reveal a clear operating-regime trade-off: LADDER is comparable or slightly weaker at benign sparsity but becomes substantially more robust from 70% onward. This high-sparsity advantage lar

---

### [55] ORSMT: Unleashing the Potential of Satisfiability Modulo Theories for Semantic Verification and Repair in LLM-Based Optimization

**链接**: https://arxiv.org/abs/2610.29145
**作者**: Rui Zhang, Chenyu Zhou, Jianghao Lin, Yaoxin Wu, Dongdong Ge, Wen Song
**来源**: math.OC cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly automate optimization modeling from natural language problems, producing written mathematics, solver code and a returned report. Verifying one optimization problem across these artifacts requires semantic comparison: unequal models can attain the same objective, equivalent models can use different auxiliary variables, and mutually consistent artifacts can omit the same source requirement. ORSMT provides a typed semantic interface and exact SMT relation queries. It aligns observable decisions, projects auxiliary variables, proves or refutes feasible region and objective relations, localizes refutations to implicated rows or domains and links source texts when available. It then reconstructs one artifact from another, and each adopted candidate passes the required relation checks. Across 3,034 problems and six generator sizes, ORSMT improves the model-code match rate in all 72 benchmark and generator combinations before selection. Protected selection ra

---

### [56] ReAPO: Retry-Aware Policy Optimization for Efficient Exploration in LLM Reasoning

**链接**: https://arxiv.org/abs/2610.28770
**作者**: Nghi Dao, Calder Morton-Ferguson, Noah Golowich, and Adam Block
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> RLVR improves language-model reasoning, but commonly relies on independent stochastic rollouts for exploration, which can repeatedly sample similar failed strategies. Prior work has seen success with approaches that guide exploration by introducing dependence into the sampling process by including incorrect solutions in the context for subsequent attempts. Still, these methods introduce the additional question of how to assign credit to each attempt. We propose to view the credit assignment through the lens of Stochastic Shortest Paths, a framework in classical reinforcement learning that seeks to minimize the expected cumulative cost to reach a terminal state (in our case, a verified successful response). We show that, under suitable simplifying assumptions, this perspective naturally leads to a simple modification to GRPO, which we call Retry-Aware Policy Optimization (ReAPO). ReAPO allocates additional generation to failed trajectories, allowing successful retries to be reinforced w

---

### [57] Asking a Multimodal LLM Whether Someone Fell: Zero-Shot Screening of Low-Resolution Thermal Video in a Laboratory and an Occupied Home

**链接**: https://arxiv.org/abs/2610.29913
**作者**: Marcos Junca (Senecta Inc.), Mauro Junca (Senecta Inc.)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Thermal cameras can watch over older people living alone without capturing faces, and multimodal large language models (LLMs) can judge a short video without task-specific training. We evaluate a production multimodal LLM, Gemini 3.8 Flash at temperature 0, as the decision stage of an event-triggered fall screener, used exactly as a deployed prototype uses it: one request per short thermal clip, with its sound track when there is one, and its predecessor Gemini 3.7 Flash on the same requests. On 438 staged falls and 563 non-fall windows that we located by hand in a public 32x24 thermal dataset, the deployed request called 69% of the held-out subjects' falls (67% over all subjects; bed falls excluded) and none of 499 non-fall windows, including people lying on the floor and getting up. Over 76 h of ordinary life in an occupied room, recorded at 160x120 with sound, it called none of 395 clips a fall (95% upper bound 1.2 false alarms per day) and caught 4 of the 9 staged falls the camera 

---

### [58] VerifierBench: Benchmarking the Generation of Executable Verifiers for LLM Agents

**链接**: https://arxiv.org/abs/2610.28679
**作者**: Jianing Yin, Ziyi Chen, Hao Wang, Yiyou Sun, Zijian Jin, Dawn Song 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents need reliable ways to validate their outputs, both when completing tasks and when filtering synthetic training data. We study verifier generation: from the instruction and environment available for solving a task, an agent writes an executable verifier that must accept every valid solution and reject invalid ones. We introduce VerifierBench, a benchmark of 222 tasks from six agent benchmarks spanning tool-call, state-based, and code verification, with 4,993 hidden test cases that include alternative valid solutions and attacks; Verifier4Verifier (V4V), a six-check audit, screens its source verifiers and test suites. Across 19 models in a common agent harness, normalized balanced accuracy ranges from 10.6 to 62.1, with generated verifiers consistently rejecting invalid solutions more reliably than they accept valid ones. This apparent strength can mask overly restrictive verification: most false rejections in the analyzed records come from verifiers that accept no tested solution

---

### [59] When Agent Evaluation Becomes Unreliable: An Empirical Study of Oracle Failures and Configuration-Dependent Measurement in an LLM Agent Benchmark

**链接**: https://arxiv.org/abs/2610.16067
**作者**: Junjie Chen
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] SANE: Automated Scorer-Specific Metamorphic Testing for LLM Judges

**链接**: https://arxiv.org/abs/2610.28886
**作者**: Ethan Ludwick, Yu-Chung Hsiao
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges increasingly mediate benchmark evaluation, model selection, data curation, and training. Their decisions are useful only when each judge responds reliably to changes affecting its scoring criterion. Existing methods for reliability testing perturb inputs with known expected effects on judge scores. Prominent LLM-judge testing harnesses combine human-authored perturbation recipes with synthetic test generation, leaving scorer-specific recipe ideation outside the automated pipeline. This limits their use to fixed perturbations and pre-assumed scorer types. We introduce SANE, an agent-based framework that encodes behavioral requirements for stochastic evaluators as reusable agent instructions. Given a scorer specification, implementation, and representative inputs, the pipeline first identifies scorer-specific capabilities, then automatically derives perturbation recipes and expected score relations for each. SANE also defines a scorer-independent validation framework for gener

---

### [61] EPIC: Rethinking Trust Regions for Autoregressive LLM Policies via Exact-KL Prefix Importance-Ratio Clipping

**链接**: https://arxiv.org/abs/2610.29999
**作者**: Chengxi Li, Hanlin Wu, Zhicheng Cai, Huan-ang Gao, Wei-Ying Ma, Jingjing Liu 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) based on PPO-style clipping has become an effective approach to improving the reasoning capabilities of large language models (LLMs). However, standard token-level clipping measures policy change only through the conditional probability of the current token, while the prefix conditioning context is itself generated by the policy. This mismatch becomes especially consequential in long-response and off-policy training. We reformulate autoregressive generation as a finite-horizon Markov decision process and derive its performance-difference identity under behavior-policy sampling. The resulting change of measure identifies the cumulative likelihood ratio of the generated prefix as the exact importance weight for each stepwise policy-improvement term. Starting from the monotonic-improvement principle of trust-region policy optimization, we then construct a prefix-level trust region using the exact reverse-KL coordinate $r-1-\log r$, whose behavior-policy expecta

---

### [62] LTEM: LLM-Friendly Table-Enhanced Markdown for Table Understanding and Generation

**链接**: https://arxiv.org/abs/2610.29188
**作者**: Eunbin Kim, Hyeonseok Kang, Sangkeun Jung
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tables in real-world documents, including scientific papers, financial reports, and statistical summaries, frequently use merged cells, multi-level headers, and sectioned layouts. Yet the lightweight formats LLMs handle best (Markdown, CSV) cannot express these structures, while expressive formats (HTML, LaTeX) impose excessive token cost and parsing complexity. To enable systematic analysis of this trade-off, we introduce a taxonomy decomposing table structure into six atomic features (F1-F6) and corresponding complexity levels (L1-L6), and construct STB (Synthetic Table Benchmark), a controlled benchmark with 1,089 tables systematically distributed across complexity levels. Using this framework, we propose LTEM (LLM-friendly Table-Enhanced Markdown), a formally specified, minimal extension of Markdown that explicitly encodes spans and hierarchical headers. Experiments across five state-of-the-art LLMs show that LTEM achieves accuracy comparable to HTML, offers a favorable accuracy-to

---

### [63] Conflicted Records: Typed Adversarial Contracts for Auditable LLM Output Quality Enforcement

**链接**: https://arxiv.org/abs/2610.29669
**作者**: Kardelen Subasi, Jaros{\l}aw A. Chudziak
**来源**: cs.DB cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-generated records increasingly populate production information systems where they are treated as data assets subject to the same quality expectations as records from operational databases. A single such record can simultaneously satisfy and violate a quality rule: a grounded fact adjacent to a hallucination, a useful answer adjacent to a stereotype. Classical data cleaning cannot resolve this because the two judgments are incompatible over the same span; a single LLM judge cannot either, since it shares the training biases that produced the conflict. Existing interventions such as prompt engineering, chain-of-thought, and RLHF reduce surface error rates but provide no audit trail and cannot distinguish genuine remediation from blanket suppression. The question is whether a deterministic check over structured inter-agent records can catch the defects that referential checks alone miss. We present BiasGuard-D: two adversarial roles drawn from distinct model families exchange typed cl

---

### [64] To Manipulate or Not: Opinion Dynamics in LLM Interactions

**链接**: https://arxiv.org/abs/2610.28875
**作者**: Mohammad Siahkamari, Phuoc Dat Nguyen, Stephen MacNeil
**来源**: cs.AI cs.CL cs.MA cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly take part in extended conversations where they can both shape and be shaped by another party's views, yet most persuasion research measures only one side of that exchange. We introduce a controlled LLM-LLM debate framework in which two language-model roles repeatedly discuss a contested topic (climate-change attribution): one is given an assigned stance and, in some conditions, an explicit instruction to persuade, while the other receives no assigned position. Across four ordered model combinations involving GPT-6 Luna and Gemini 2.5 Flash Lite, we track both each role's explicitly reported position and a separate measure of its turn-by-turn behavior inside the conversation. Opinion dynamics differ substantially across model combinations: same-model interactions narrow the opinion gap on average, clearly for only one of the two models, while cross-model interactions widen it. Explicit reports and in-dialogue behavior capture distinct aspects of opinio

---

### [65] Dooly: Configuration-Agnostic, Redundancy-Aware Profiling for LLM Inference Simulation

**链接**: https://arxiv.org/abs/2605.07985
**作者**: Joon Ha Kim, Geon-Woo Kim, Anoop Rachakonda, Daehyeok Kim
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] From Prompts to Posteriors: Can LLM Agents Perform Bayesian Inference in Context?

**链接**: https://arxiv.org/abs/2610.29331
**作者**: Linus Filbry, Luckeciano C. Melo, Yarin Gal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly applied across the scientific discovery pipeline, from synthesizing literature to generating hypotheses to informing experimental design. A unifying principle behind these tasks is the need to continuously update beliefs as evidence accumulates, for which Bayesian inference provides a natural framework. However, existing work assumes that LLMs cannot carry out principled Bayesian belief updating in context, instead relying on simplifications and heuristics. To challenge this assumption, we present a principled evaluation of Bayesian reasoning capabilities in LLMs, analyzing both the model's internal consistency as well as its ability to recover an externally determined posterior. Specifically, we build an evaluation framework spanning qualitative epistemological examples to probe probabilistic coherence, quantitative benchmarks of Bayesian inference capabilities, and analyses of the impact of non-Bayesian updates on downstream task performa

---

### [67] Is 2:4 Sparsity Still Worth It? Semi-Structured Sparsity versus Quantization in LLM Inference

**链接**: https://arxiv.org/abs/2610.28947
**作者**: Xiuyi Qin
**来源**: cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> NVIDIA tensor cores have supported 2:4 semi-structured sparsity since Ampere, and the pattern composes with quantization. When the two are combined, the practical question is which step to take next: from a given precision, add 2:4 sparsity or drop to the next lower precision? We compare the two at equal bits, with sparsity metadata counted, and at equal nominal tensor-core tiers, over all six GEMM operands of a transformer layer, with kernels measured on three GPU generations and online pruning and quantization included. Our results show that as long as a lower precision is available, adding 2:4 is the worse step, both less accurate and slower, because the energy that 2:4 discards from each group of four along the hardware-forced axis does not shrink with bits, while quantization error does. Once quantization reaches the lowest precision the hardware supports, 2:4 still speeds up linear layers by 1.3--1.7\x{}, and on an H100 a retrained 2:4 model served in FP8 by vLLM reaches 27\% hig

---

### [68] Learning Checklists to Reduce Lottery Effects in Scientific Peer Review

**链接**: https://arxiv.org/abs/2610.28666
**作者**: Xuanyou Liu, Ziyang Guo, Jason Hartline, Jessica Hullman
**来源**: cs.DL cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reviewer lottery error describes error due to a small set of peer reviews attending to only some of the issues with a paper that a larger pool of eligible reviewers would raise. We show this error can be reduced by surfacing a checklist of criticisms learned from a historical review corpus. Our approach generates a tree of checklists representing coarsenings of the atomic review claim space, then selects the coarsening that maximizes a theoretically-motivated measure of correlated agreement among reviewers. We realize this approach with an LLM-assisted pipeline and test it on NeurIPS 2021 and ICLR 2022 review data. In simulated review with LLM reviewers, the learned checklist reduces the mean squared error (MSE) of a three reviewer committee by 58% on NeurIPS and 21% on ICLR, and on both venues the checklist with the highest correlated agreement has the lowest error for committees of three or more. In a human study with 20 participants, the learned NeurIPS checklist lowers the MSE of a

---

### [69] Agent Behavior Maps: Locating Agents by What They Would Do, Without Running Them

**链接**: https://arxiv.org/abs/2610.30014
**作者**: Shota Fujikawa, Takuya Tamura, Kosuke Akimoto, Daichi Haraguchi, Masafumi Oyamada
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents with similar success rates can follow different action sequences. An Agent Behavior Map represents LLM-harness combinations using centered action log-likelihoods on shared reference trajectories, without requiring new environment rollouts from the target agent. We derive error bounds relating squared coordinate distances to trajectory KL under explicit assumptions, and across eight cross-scored models the distances track the directly measured trajectory KL in rank order. Across 100 LLMs and four environments, ALFWorld-based coordinates support performance prediction and identify behavioral similarities. In ALFWorld, these similarities persist after controlling for success rates and model size, including across model families. As an extension, harness-component displacements approximately compose, with accuracy varying across components and environments.

---

### [70] A Parallel Multi-Dialect Arabic Dependency Treebank

**链接**: https://arxiv.org/abs/2610.28823
**作者**: Noor Abo Mokh, Mohamed Adel, Jamila El-Gizuli, Go Inoue, Ahmed Elshabrawy, Nizar Habash
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dependency parsing resource development for Arabic has largely focused on Modern Standard Arabic, leaving dialectal Arabic comparatively under-resourced. We introduce MADARTB, the first large-scale parallel dependency treebank spanning five city dialects: Beirut, Cairo, Doha, Rabat and Tunis, and extending an existing parallel MSA version. In total MADARTB consists of 5,000 sentences annotated using the CATiB dependency scheme. We analyze syntactic similarity across all city dialects and MSA. Although global construction profiles exhibit high similarity across varieties, local syntactic structures frequently diverge, revealing substantial structural variation across dialects. We further establish a cross-dialect dependency parsing comparison using a supervised parser and four LLMs. The supervised parser achieves 87.5% LAS, while the best LLM setup trails at 85.7% LAS across all six varieties on the test set. We release our annotations and models publicly.

---

### [71] Every Alarm Has a Cause: An Open Generator of Telecom Alarm Storms with Exact Root Causes, Bound to NORIA-O, RFC 8632 and TMF642

**链接**: https://arxiv.org/abs/2610.30004
**作者**: Madhulatha Mandarapu, Sandeep Kunkunuru
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Alarm root-cause analysis is studied on data that cannot be shared. Operator logs are confidential, so what the field publishes is a causal graph between alarm types rather than per-incident causes, a fixed scenario set, gated, or never released. Two recent benchmarks carry per-incident root causes at scale; neither states a download location or a licence. We give a generator rather than a dataset. It runs on real backbone topologies from the Internet Topology Zoo and records the exact root cause and the propagation path of every alarm -- a by-product of generation, not a labelling pass. Every emitted field binds to a term in NORIA-O, RFC 8632, RFC 8345 or TMF642, and an unknown term fails the run. We ship fixed configurations, splits, a scorer and nine baselines. A one-line rule -- rank the device that raised the earliest critical alarm -- takes top-1 at 0.650 against 0.575 for our own temporal method, and wins 13 of 15 runs over three backbones and five seeds. An LLM given the same v

---

### [72] B-CARE: Blind Classwise Assessment of Relative Evidence for Stance Error Ranking

**链接**: https://arxiv.org/abs/2610.29350
**作者**: Meysam Sabbaghan, Doina Caragea
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Stance classifiers make errors that can be costly to identify under limited human-review budgets. Prioritizing potentially incorrect predictions remains challenging, particularly across heterogeneous base models. We introduce B-CARE (Blind Classwise Assessment of Relative Evidence for Stance Error Ranking), a prediction-blind framework for identifying high-risk stance predictions. Given only a target and text, a fixed LLM verifier assigns ordinal evidence scores to all candidate stance labels without observing the base model's prediction or confidence. B-CARE constructs a comparative risk score by contrasting the strongest alternative-class evidence with the evidence supporting the predicted class. The resulting classwise evidence profile can be reused across multiple base models without training a separate error detector or calibrating risk scores. We evaluate B-CARE on four stance benchmarks and three heterogeneous base LLMs, covering 12 dataset-model settings and 5,206 unique test i

---

### [73] SpecEvo: Speculative Evolution with Large Language Models for Cost-Efficient Scientific Discovery

**链接**: https://arxiv.org/abs/2610.28706
**作者**: Ha Minh Hieu, Tongyao Zhu, Do Xuan Long, Min-Yen Kan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-driven evolutionary search is a promising paradigm for scientific discovery, but existing methods remain costly and slow, often applying expensive reasoning uniformly while underusing evidence from failed, redundant, and saturated trials. We introduce Speculative Evolution (SpecEvo), a multi-LLM framework that coordinates lightweight and frontier models through continual consolidation of search evidence. Lightweight models power both parallel Speculators, which generate and refine candidate programs, and an Advisor, which distills accumulated successes, failures, and saturated directions into persistent guidance for subsequent exploration. At sparse checkpoints, a frontier-model Navigator inspects the evolving population and intervenes through synthesis, surgical refinement, or reframing according to search stagnation. This speculate-then-consolidate workflow delegates routine exploration and evidence consolidation to inexpensive models while reserving frontier reasoning for strate

---

### [74] Attention-based Classification for Indirect Prompt Injection

**链接**: https://arxiv.org/abs/2610.28988
**作者**: Amelia Kawasaki, Stefan Lee
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Indirect prompt injection (IPI) attacks, in which adversarial instructions are embedded in external data processed by a language model, pose a significant threat to the integrity of deployed LLM agents. Attention Tracker (Hung et al., 2025) is a recently proposed white-box detection method that identifies prompt injection attacks by monitoring how a model's attention is distributed between user task tokens and data tokens, claiming dataset-agnostic detection via a scalar focus score threshold. In this paper, we provide the first evaluation of Attention Tracker in a realistic agentic IPI setting using the AgentDojo benchmark, finding that the dataset agnosticism claim does not hold. We find that in agentic environments, long structured tool outputs subvert the fundamental assumptions Attention Tracker makes about attention that the method depends on and produces near-chance detection on AgentDojo across most model families. We propose AttnDA, an extension replacing the scalar threshold 

---

### [75] What the Author Wrote, What the Agent Reads: Silent Cue Loss in Enterprise Document Ingestion

**链接**: https://arxiv.org/abs/2610.30026
**作者**: Yikai Zhao, Saurabh Pandey, Pradeep Kumar Misra
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise agents act on documents. Before an agent can follow a policy, answer a compliance question or file a ticket, some ingestion layer must turn a Word file or PDF into tokens - and that layer is where an agent deployed in the wild silently loses information. We show that one layer is lost by every mainstream converter - the meaning an author encodes in how text looks - and that the loss makes agents confidently wrong rather than visibly incomplete. We build a task from 76 real policy documents: recover the requirements the author singled out, scored against the file's own OOXML properties by a deterministic matcher with no LLM judge. Formatting-blind ingestion collapses from micro F1 0.690 to 0.150 (docling) and 0.075 (plain text), a gap that replicates across six answering models from two vendors - five Claude models spanning the Opus, Sonnet and Haiku tiers, and OpenAI's GPT-5.6. An agent that cannot see the cue guesses, and docling's false-positive rate on requirements the au

---

### [76] Seeing the Forest for the Trees: Emergent Agreement from Individual Conversations

**链接**: https://arxiv.org/abs/2610.29328
**作者**: Adi Simhi, Yaniv Nikankin, Jonathan Herzig, Idan Szpektor, Yonatan Belinkov, Shay B. Cohen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents interact in the wild and shape each other's decisions, understanding how they converge toward agreement becomes important. We study this in multi-turn conversations where two LLMs discuss subjective matters, can agree or disagree, and may change their stances. Using a linear classifier on individual conversation activations, we identify an internal representation of agreement. We find that it varies substantially across turns and conversations and does not reliably track external agreement at the individual conversation level. We therefore move beyond the representation of agreement in individual conversations, by aggregating the agreement representation across conversations. Externally, this aggregate view reveals a simple structure: when pooled across conversations, agreement can be predicted well with a Markov process, with agreement at each turn being a direct function of agreement at the previous turn. Similarly, when internal agreement is aggregated, it couples with

---

### [77] T-DIG: Text-Conditioned Diversity for Image Generation

**链接**: https://arxiv.org/abs/2610.29003
**作者**: Simran Khanuja, Rohit Gandikota, Gaurav Parmar, Graham Neubig
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-image (T2I) platforms typically return several images per prompt so users can explore different visual interpretations and choose one that matches their intent. However, T2I models are usually optimized for single-image quality which comes at a cost of multi-image diversity, limiting this exploration. Diversity is also contextual: one user wants variations in background, while another wants them in artistic style, and the same user may later want variations in clothing. The generated images should differ along whatever axis the user cares about. In this paper, we introduce T-DIG, a text-conditioned diversity framework for image generation and editing. T-DIG is an iterative framework comprising multiple modules that lets users type prompts, inspect default generations, request variations using natural language, and continue refining outputs until they're satisfied. At its core, T-DIG uses an LLM policy that produces K axis-conditioned prompts or edit instructions for a frozen ge

---

### [78] LongZero: Enhancing Long-Context Reasoning in LLMs from Zero Data

**链接**: https://arxiv.org/abs/2610.30132
**作者**: Zhennan Wan, Jianfei Chen
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) is an effective way to strengthen the long-context reasoning of large language models (LLMs), but it needs training data that are long, diverse, challenging, and verifiable. Human annotation of such data is expensive, naturally occurring data are too scarce to sustain RL, and existing synthesis methods depend on external corpora or stronger teacher models, which become harder to obtain as the trained models get stronger. Recently, RL from zero data, in which a model learns from tasks it proposes itself, has achieved excellent performance, but existing methods target short-context tasks. Therefore, we propose $\textbf{LongZero}$, a method that lets an LLM improve its own long-context reasoning without any external data. Instead of writing questions and answers over existing documents, LongZero first has the model synthesize the question and answer with its supporting evidence in a compact structured form, and only then separately expands the evidence into a l

---

### [79] AutoFraming: Synthesizing Dynamic Frames of C Code with LLMs

**链接**: https://arxiv.org/abs/2610.29046
**作者**: Han Zhou, Yu Luo, Dianxiang Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown considerable promise in synthesizing formal specifications from source code. However, existing approaches primarily focus on functional contracts and loop invariants, while largely neglecting frame conditions, which specify the memory locations that may or may not be modified during execution and constitute an essential part of formal specifications. To address this limitation, we propose an LLM-based approach for synthesizing ACSL frame specifications alongside functional contracts from C code. Our approach analyzes code property graphs (CPGs) to extract frame-relevant information from the input code and leverages this information to guide the LLM in generating accurate frame conditions. The resulting specifications capture both region-separation constraints and data dependencies that govern variable modifications. Experimental results demonstrate the effectiveness of our approach. On a benchmark of 84 ACSL-compliant functions from non-trivial r

---

### [80] Flat-RLVR: Sharpness-Aware Reinforcement Learning with Verifiable Rewards for Reasoning Capacity in LLMs

**链接**: https://arxiv.org/abs/2610.29281
**作者**: Yeonbum Kim, Hyun Kyu Lee, Sung Whan Yoon
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR), particularly through group-relative policy optimization (GRPO), has emerged as a central paradigm for the post-training of large language models (LLMs). While RLVR is highly effective at enhancing the reasoning capabilities of LLMs, it commonly induces \textit{distribution sharpening}, whereby the policy distribution becomes excessively peaked and rare-yet-correct trajectories are progressively suppressed, thus diminishing sample diversity. To this end, we promote flat-reward optima in RLVR to smooth the policy distribution. We theoretically link flat reward RLVR to reduced distribution sharpening, and empirically show improved sample diversity while maintaining single-attempt accuracy. Our method, called \texttt{Flat}-RLVR, searches for flat reward regions via sharpness-aware minimization during LLM post-training, combining this with GRPO variants to achieve better trade-offs between sampling efficiency and reasoning capacity.

---

### [81] RCSD: Reinforcement and Continual Learning for Domain-Specific Speculative Decoding

**链接**: https://arxiv.org/abs/2610.29527
**作者**: Mingkang Liu and Weiming Meng and Peipei Jiao and Jiawei Zhang and Tianyuan Liu and Junyan Li and Lichen Pang
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference by employing a compact draft model to propose candidate tokens that are verified in parallel by a target model. Conventional training relies on soft-label distillation, which forces the draft model to mimic the target's full output distribution, including high-entropy regions that degrade acceptance rates and increase early rejection risk. We propose RCSD (Reinforcement and Continual Learning for Speculative Decoding), a training framework that aligns draft model optimization with the system-level objective of maximizing acceptance length. RCSD leverages naturally occurring accepted and rejected sequences during speculative inference to construct implicit preference pairs, with masked loss to avoid penalizing target-aligned tokens. Evaluated across multiple benchmarks, RCSD improves average acceptance length by 35% over HASS and achieves 1.35x faster end-to-end inference than HASS on practical workloads, without compromisi

---

### [82] TraceForge: Distilling with Your Own Thinking

**链接**: https://arxiv.org/abs/2610.29680
**作者**: Yan Wang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Using an LLM to generate training data for another is among the most general ways to train one, and it remains common practice. Some frontier teams have closed that route for their own models: what comes back is an answer, or a short summary, without the detailed reasoning trace behind it. That is a little ironic: they were themselves built on distilling human knowledge, and distilling an open-source model is still entirely routine; the restriction applies to their own outputs alone. Recent work recovers the hidden reasoning by replaying encrypted blocks across models. It somehow works, but it breaks the providers' terms of service, so it is not something a product can be built on long-term. We built the alternative. We take the context and the teacher's answer as input, and generate the reasoning trace ourselves, in the style of the student's own model family. Training is two-stage, supervised and then adversarial: a generator learns to regenerate the family's own reasoning traces fro

---

### [83] FrontierCS 2: A Benchmark for Computer Science R&D

**链接**: https://arxiv.org/abs/2610.29932
**作者**: Qiuyang Mang, Wenhao Chai, Runyuan He, Dongruixuan Li, Zihan Zheng, Yujun He 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can LLM agents make contributions to frontier computer science R&D? We introduce FrontierCS 2, a benchmark of 48 open-ended tasks. We take a paper and the code its authors released and delete the paper's contribution. The deleted code becomes the human reference that sets the bar. Earlier open-ended benchmarks give each agent a problem statement and grade one program after the run. FrontierCS 2 places the agent inside a research environment. The agent inherits a working repository and may submit a patch at any point. For each patch, a judge returns a development-suite score but keeps the evaluator, the held-out final suite and the reference private, and grades the final submission on that suite against the reference. The tasks span 13 domains, from machine-learning systems and high-performance computing to databases, security and robotics. Beyond these 48 tasks, FrontierCS 2 keeps a private set of more than 100 tasks, to be announced in the future. We evaluate 12 agents. The best one i

---

### [84] CulturalRiddles: A Multicultural Benchmark of Riddles

**链接**: https://arxiv.org/abs/2610.29968
**作者**: My Chiffon Nguyen, Tianyi Hu, Vinod Anbalagan, Henry Gagnier, Pouya Sadeghi, Farah Abdou 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLMs expand their language coverage, evaluating how well they understand and represent diverse cultures becomes increasingly important. However, many benchmarks remain English-centric, with limited cultural coverage and a focus on factual knowledge over its application in real-world cultural contexts. We propose CulturalRiddles, a benchmark of original, culturally grounded riddles created entirely by humans through a participatory community effort, spanning 62 cultures (45 countries, 51 languages). These riddles are deeply rooted in their respective cultures and require abductive and compositional reasoning, alongside detailed factual and social knowledge, language skills, and an understanding of culturally specific associations. We benchmark 28 LLM configurations using both automatic and large-scale human evaluation. Even frontier models achieve at most 22% accuracy in some communities. We publicly release all artifacts alongside an open contribution process to expand the benchmark

---

### [85] Signals and Queries: Token-Efficient Agentic Context Discovery

**链接**: https://arxiv.org/abs/2610.29326
**作者**: Yam Marcovitz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> User-facing LLM agents must identify which behavioral policies apply at each turn, but evaluating every policy with an LLM is costly. We introduce Signals and Queries (S&Q), a lightweight first-stage relevance filter developed for Parlant 4.0 that removes at least 30% of candidate policies before downstream evaluation while preserving high recall. For each policy, an LLM generates activating examples and hard negatives offline. An independent logistic classifier trained on their embeddings then predicts relevance using embeddings and vector dot products, with no per-turn LLM calls. This shifts expensive relevance evaluation to a smaller candidate set, while allowing each policy's classifier to be updated independently. Evaluated against 9,144 LLM-judge relevance labels covering 254 $\tau^2$-bench conversation prefixes and 36 airline policies, S&Q achieves higher precision than top-K and cosine-threshold retrieval at every evaluated recall level, with consistent results across two embed

---

### [86] Our Own Jev: Typed Decisions in One Forward Pass, from an In-House Judge to Open LoRA Models

**链接**: https://arxiv.org/abs/2610.29052
**作者**: Yuchuan Weng, Chi Liu, Xin Chen, Srinivasan Manoharan
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A typed decision maps evidence, a question and a fixed set of options to a probability for every option, computed in one forward pass, by reading a language model's logits or a small head over its hidden states, instead of generating and parsing text. The commercial system Jev popularised this System~1 interface, and open reproductions have followed. We report two uses of the pattern. \emph{Part I} describes an in-house System~1 judge that triages about 148K agentic coding session records for a training corpus. It replaces a frontier LLM judge that cost on the order of \$1,000 per pass and whose stored labels matched a fresh two-judge consensus on only 26.9\% of the sessions where the two judges agreed; a self-hosted frozen backbone with a rank-16 LoRA adapter and a pointer head answers three typed questions in one forward pass, judges 1,000 sessions in about three minutes of one GPU, about \$0.06 at a reference rate and roughly 1\% of the frontier judge's cost, and keeps every session

---

### [87] TAGR: Task-Adaptive Geo-Semantic Retrieval across Heterogeneous Urban Delivery Tasks

**链接**: https://arxiv.org/abs/2610.28638
**作者**: Zhi Liu and Yurun Cai and Xiao Han and Zhi Zhen and Yuran Li and Guojiang Shen and Xiangjie Kong
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As urban residents demand higher-quality instant delivery services, demand forecasting, estimated time of arrival prediction, and next-stop prediction have become critical tasks in urban delivery systems. However, the three tasks rely on historical evidence with substantially different structures and granularities. Meanwhile, their prediction targets differ in output form, making it difficult to integrate retrieved evidence through a single fusion mechanism without causing mismatch or negative transfer. These issues can increase prediction errors and subsequently lead to imbalanced resource allocation, where some regions experience unmet demand. In contrast, others suffer from underutilization, ultimately degrading overall efficiency and service quality. To address these challenges, we propose TAGR, a Task-Adaptive Geo-Semantic Retrieval framework across heterogeneous urban delivery tasks. TAGR constructs an LLM-based geo-semantic shared prior and task-specific retrieval banks to share

---

### [88] One Act, Many Masks: Effect-Marginal Policy Optimization for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2610.29427
**作者**: Shaojin Ma, Ruitao Wang, Pengyi Li, Jie Yang, Liangyu Chen, Gangyi Zhao 等 (9 人)
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multi-turn reinforcement learning (RL) have substantially improved the performance of LLM agents on complex, long-horizon interactive tasks. However, despite progress in fine-grained credit assignment, policy optimization still applies these learning signals through response-specific probability ratios. Different textual responses can induce the same executable effect, yet credit differences arising from subsequent outcomes remain tied to their individual textual realizations. We identify this mismatch as credit-update misalignment. Our analysis reveals that credit-text pairing directly shapes policy-update directions, even when the policy context and executable effect are held fixed. Motivated by this finding, we propose Effect-Marginal Policy Optimization (EMPO), which aligns policy optimization with execution-level equivalence through an effect-level surrogate that couples updates across alternative textual realizations. EMPO preserves the original credit signals,

---

### [89] Reading the Mask: Descriptor-Grounded BI-RADS Rationale Generation for Breast MRI Segmentation

**链接**: https://arxiv.org/abs/2610.29358
**作者**: Hrishikesh Singh, Aarti Sharma, Divyanshu Kumar, Millie Pant
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning based models accurately delineate tumours on dynamic contrast-enhanced MRI (DCE-MRI), but segmentation masks alone do not provide the rationales or reasoning used by radiologists to assess the lesion suspicion. This limits the explainability as well the clinical integration. We investigate whether clinically relevant descriptors can instead be derived from the segmentation masks and their dynamic contrast-enhancement series. We have used Breast Imaging Reporting and Data System (BI-RADS) guidelines as a structured framework. Using these guidelines we designed a BI-RADS decision tree with eight quantitative measurements using radiomics, together with the lesion size and component count, that determine the descriptors at eight nodes. Using these descriptors we generate natural-language rationale using a large language model. The model was constrained to express only the derived records from the decision tree. After applying this framework to the expert and automatic masks o

---

### [90] Commit or Abstain? System One Decision Models, LLMs, and Missing Legal Authority

**链接**: https://arxiv.org/abs/2610.29961
**作者**: M. Mikail Demir
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Given the enormous number of claims to be checked, verifiable legal AI requires scalable, cost-effective models that answer the practical needs of law. System One decision models are built on large language models but, instead of generating text, return a calibrated probability for each option. This suits the verification of legal authority, where the question is closed: a given holding, or none of them. We test whether such models abstain when the correct authority is missing. We extend CaseHOLD with an abstention condition in which the correct holding is replaced in 1,670 of 5,314 items, and compare four decision models with six generative LLMs. When no option is correct, generative LLMs still pick one in 38-86% of items; the most cautious decision model does so in 30%. On standard CaseHOLD, a decision model matches the best generative LLM (88.1% vs. 88.2%) at 1/55 of the cost. Accepting that LLM's answer only when a decision model agrees halves its wrong citations, and distilling a 

---

### [91] An Evidence-Driven Multi-Agent Compound AI System for Head and Neck Proton Radiotherapy Planning

**链接**: https://arxiv.org/abs/2610.29010
**作者**: Qingqing Wang, Liqiang Xiao, Chang Chang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radiation treatment planning requires balancing competing objectives to satisfy clinical criteria while accommodating physicians' preferences. This study aims to develop an evidence-driven, multi-agent compound AI system that integrates DRL-based automated treatment planning with LLM-based conversational plan refinement for proton PBS therapy. A policy network trained using PPO first generates multiple plans without human intervention, from which one is selected as the target plan and the others serve as references for subsequent refinements. For challenging cases requiring further adjustments, an LLM-based multi-agent system enables plan refinement through natural language interactions. The system comprises a planning agent that recommends evidence-supported adjustments, a chatbot providing a unified conversational interface, and an evaluation agent that retrieves clinical metrics and identifies constraint violations. To enhance domain-specific reasoning, the planning agent based on Q

---

### [92] Beyond the Vote: When Do LLMs Add Value to Retrieval-Based Tabular Classification?

**链接**: https://arxiv.org/abs/2610.29520
**作者**: Ziquan Wang, Yuxuan Nie, Jian Ma, Yingjie Li
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-based in-context learning (ICL) enables large language models (LLMs) to predict tabular labels from similar examples, but it remains unclear whether LLM inference improves on direct voting over those same examples. We address this question by comparing four general-purpose LLMs with distance-weighted nearest-neighbor voting (Distance-KNN) using identical retrieved neighbors across 19 tabular classification datasets. With the number of demonstrations fixed, enlarging the retrieval candidate pool improves accuracy for all predictors, yet Distance-KNN achieves the highest mean accuracy at every pool size. More detailed analyses reveal that LLM gains are concentrated where retrieved neighbors exhibit low label consensus and vary across models. These gains further depend on the average feature-space distance to the test query: under low label consensus, some LLMs outperform Distance-KNN in close and intermediate neighborhoods, but all fall behind on average in the most distant gro

---

### [93] Credit Where Credit Is Due: Contrastive Attribution Topology Search for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.29292
**作者**: Fabian Tritthart and Tom Zehle
**来源**: cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM multi-agent system (MAS) is only as good as the agents it chooses to trust: its accuracy and cost hinge on its topology, meaning which agents are included and how they communicate. A single task score, however, does not reveal which agents help or hinder performance. We propose Contrastive Attribution Topology Search (CATS), which searches for compact teams within a fixed supergraph of specialized agents. An LLM attributer compares execution traces across candidate topologies and assigns credit to individual agents. CATS uses these credits to update supergraph edges while progressively pruning weak edges and agents, yielding a small team for deployment. With small open-weight models and matched candidate evaluations, CATS improves mean accuracy on BigCodeBench by 5.3 percentage points over score-only heuristic search while using 54\% fewer deployment tokens. On MBPP, CATS matches the strongest baselines with fewer tokens than the other searches. In a HotpotQA prompt-poisoning st

---

### [94] Combining Long-Term Memory and LLMs Comes at a High Cost: From Prompt Injection to Persistent Compromise

**链接**: https://arxiv.org/abs/2610.28810
**作者**: Pedro H. Barcha Correia, Matheus Azevedo de S\'a, Paulo H. Gomes de Senna, Giovanni Mandel Martignago, Victor Takashi Hayashi, Charles Christian Miers 等 (7 人)
**来源**: cs.CR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The widespread adoption of generative artificial intelligence in recent years has brought a parallel rise in prompt injection and jailbreak attacks. By embedding malicious instructions, these exploits manipulate language models to bypass intended behavior and operational boundaries. In traditional chatbots, such attacks are confined to a single session because state memory is not preserved across conversations. However, persistent memory features in modern conversational interfaces enable cross-session attack propagation, establishing a threat vector known as memory injection. This work explores this emerging vulnerability in leading LLM-as-a-service platforms, highlighting its real-world severity and the need for countermeasures. While existing literature focuses on violations tailored to specific platform features, we present a general threat model. We demonstrate that all NIST attack goals are collectively achievable across ChatGPT Instant 5.3, Claude Sonnet 4.6, and Gemini 3 Flash 

---

### [95] CALLIOPE: Private Insights into AI Use, Without Embeddings

**链接**: https://arxiv.org/abs/2610.28797
**作者**: Edith Cohen, Vadym Doroshenko, Badih Ghazi, Charlie Harrison, Pritish Kamath, Alexander Knop 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce CALLIOPE, a top-down framework for discovering topic hierarchies in large corpora of unstructured data (e.g., LLM conversations), while supporting differential privacy (DP). Unlike traditional and even recent LLM-augmented approaches that ultimately rely on clustering vector embeddings, our framework leverages LLM capabilities directly for the entire pipeline. Experiments demonstrate that this approach provides better utility over existing (embedding-based) methods in the DP setting, especially in the high privacy regime. We evaluate the quality of CALLIOPE outputs using a variety of traditionally studied clustering metrics, as well as some novel utility metrics that we introduce.

---

### [96] Big Claims, Small Margins: Do Reported GraphLLM Gains Survive Simple Baselines?

**链接**: https://arxiv.org/abs/2610.28714
**作者**: Michal Podstawski
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based methods for node classification on text-attributed graphs (TAGs) routinely report state-of-the-art accuracy. We ask how these results compare with inexpensive baselines run on the same splits. On the splits of three recent studies, we tune four baseline representatives with validation-only selection and compare them with the highest mean that each paper reports for an LLM-based method in the matched setting. Correct & Smooth on TF-IDF features trails this reference by a median of 2.3 percentage points, and an MLP on frozen e5-large-v2 embeddings by 2.8 points. Correct & Smooth is within 3 points of the reference or better on 15 of 24 tasks, but the reference is significantly higher on 12 of 22 testable tasks, so several reported gains remain substantial. Reading released code next to the papers, we also document evaluation risks: selection of hyperparameters or checkpoints on the test set, labels of test-pool nodes used in training, baseline numbers reused without disclosure,

---

### [97] Zero-Cost Detection of Fabricated Citations: A Staged Heuristic Approach for Computing Dissertation Assessment

**链接**: https://arxiv.org/abs/2610.28649
**作者**: Hazrat Ali and Mohamed Elawady
**来源**: cs.DL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI's growing role in academic writing has driven a rise in fabricated references across dissertations and student reports. We present the Fabrication Severity Stack (FSS), a three-tiered framework classifying citation fabrications by detection complexity - from non-existent references to subtle content misattribution. Building on the FSS, we propose a staged heuristic verification workflow, executable through mainstream LLM interfaces. We argue that this framework offers computer science educators/examiners a practical, zero-cost basis for embedding reference verification into the assessment of dissertation and students' reports. In a pilot study on 100 citations (20% seeded with Level 1 and Level 2 fabrications), the proposed heuristic workflow enabled mainstream LLM interfaces to correctly flag 9-10 of 10 non-existent references and partially detect metadata corruption. These preliminary results suggest that freely accessible, general-purpose LLMs can achieve high recall o

---

### [98] TrainBridge: Agentic NPU Training Optimization Guided by GPU Compilation Evidence

**链接**: https://arxiv.org/abs/2610.29171
**作者**: Yupeng Chen, Kunxiang Zhao, Xingjian Wang, Yue Zhao, Yijing Wu, Ye Liu 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how to improve training efficiency on Ascend NPUs. In the NPU training programs we study, framework-level compilation optimizations such as operator fusion are only partially applied, leaving fragmented computation and avoidable execution overheads. Profiling-guided tuning can address these inefficiencies, but it often requires costly trial and error. To make training on NPUs more efficient, we propose TrainBridge, an agentic approach for transferring GPU optimization guidance to NPU training. TrainBridge uses the highly optimized execution produced by mature GPU compilation stacks as a task-specific reference for NPU tuning. It extracts optimization intents from the GPU training execution to guide NPU program rewrites and further refines the rewritten program through iterative profiling. Our GPU-to-NPU migration experiments show that TrainBridge achieves an average 1.7x speedup across four workloads covering LLM pretraining, image classification, and vision-language training,

---

### [99] Data Schedules and Learning Rate Schedules Should Be Designed Together

**链接**: https://arxiv.org/abs/2610.29348
**作者**: Haodong Wen, Kairong Luo, Tingkai Yan, Wenguang Chen, Kaifeng Lyu
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mid-training (MT) is a training phase in LLM training pipelines that continues pretraining (PT) on smaller datasets of higher value. Taking the PT and MT phases as a whole, training usually starts with only PT data and then transitions completely to MT data. In this work, we view this complete transition from PT to MT data as a special case of a broader class of data mixing schedules that specify how the proportions of PT and MT tokens in each batch change over training. Under fixed total training compute and MT token budgets, we ask: Is this complete transition to MT data optimal for minimizing final MT loss? We show that the answer depends on the learning rate (LR) schedule: one data schedule may outperform another under one LR schedule, but changing only the LR schedule can reverse the outcome. Specifically, when the LR decays throughout continued training, introducing MT data earlier and mixing it with PT data lowers the final MT loss compared with placing all MT data at the end of

---

### [100] TIDE: Tree-Induced Fine-Grained Diagnostic Evaluation from Model Behaviors

**链接**: https://arxiv.org/abs/2610.29985
**作者**: Jiayi Chen, Hui Li, Yujiong Shen, Qiyuan Peng, Yanxin Li, Chenhao Huang 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmark performance is the dominant standard for comparing large language models (LLMs), typically summarized by a single aggregate score, such as accuracy, pass rate, or rubric score. This aggregate score provides limited information about a model's underlying capabilities, yet understanding these capabilities is crucial for model development and evaluation. To this end, we propose Tree-Induced Diagnostic Evaluation (TIDE), which recasts diagnostic evaluation as behavior-driven decision-tree induction to perform fine-grained capability diagnosis. TIDE recursively builds a hierarchical capability tree from benchmark samples and model scores: at each node, an LLM judge proposes candidate splits and performs sample-to-group classification, and behavior-based information gain selects among them. We apply TIDE to five models across four benchmarks to demonstrate its effectiveness, and find fine-grained capability contrasts invisible at the aggregate level: Claude Opus 4.6 achieves 100% o

---

### [101] Design and Tuning of Multi-Agent Systems Using Bayesian Evolutionary Optimization

**链接**: https://arxiv.org/abs/2610.29276
**作者**: Dominik Jehle and Tom Zehle
**来源**: cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing effective multi-agent systems (MAS) remains a challenging and resource-intensive task. We propose a Bayesian Evolutionary Optimization framework for automatically discovering task-specific MAS topologies. The approach combines evolutionary operators to generate diverse workflow graphs with Bayesian optimization to focus cost intensive evaluations on promising candidates. In contrast to LLM-based candidate selection, our approach uses a graph-aware Gaussian Process and Expected Improvement to provide an explicit selection criterion during evolutionary search. We evaluate the method on BigCodeBench for code generation and on a tabular preprocessing benchmark using TabPFN. On BigCodeBench, evolved architectures achieve the highest overall performance among the evaluated agent systems. On temporal tabular datasets, optimized MAS preprocessing improves over the default TabPFN model on several tasks, while remaining competitive on IID datasets. Overall, the results demonstrate the 

---

### [102] Code Comprehensor: Hierarchical Documentation and Cross-Modal Retrieval for Large Repositories

**链接**: https://arxiv.org/abs/2610.30016
**作者**: Sujoy Roychowdhury, Joseph H. R. Isaac, Jiangning Gao, Martin Klitte, Diarmuid Corcoran
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding large, complex, and rapidly evolving code bases remains a core challenge for software engineering at scale, hindering onboarding, maintenance, refactoring, and impact analysis. Providing this information to a Large-Language Model (LLM) is another hurdle, as the LLM must understand not only the required code method but also its associated methods in the grand scheme of the repository. We propose Code Comprehensor, a hybrid retrieval-reasoning framework combining (i) a code dependency callgraph, (ii) CodeScribe, which uses code-aware LLMs to generate hierarchical documentation across repository call graphs, and (iii) CodeContrast, a CLIP-style dual-encoder model trained on CodeScribe output to learn aligned text-code embeddings. CodeContrast enables fast, semantically precise retrieval of relevant code-context neighborhoods, which serve as grounded evidence for an MCP-based LLM orchestrator answering domain-specific queries. Evaluation on OpenCV and a proprietary 5M-LOC rep

---

### [103] LocalAgent: Collaborative Agentic Verification for Fine-Grained Instance-Level Consistency

**链接**: https://arxiv.org/abs/2610.29174
**作者**: Jiachen Guo, Xinshan Zhu, Boyun Wang, Yanyan Liang, Jun Wan, Feng Lin 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have made rapid progress in general visual understanding, yet they still struggle with fine-grained instance-level consistency verification, where the goal is to determine whether two images depict the exact same physical object under varying viewpoints, illumination, and backgrounds. This task requires both global semantic perception and precise examination of subtle local evidence, since semantically similar objects may differ only in small suspicious regions. To address this challenge, we propose LocalAgent, a collaborative agentic framework that integrates the complementary strengths of a generalist MLLM and lightweight specialist verifiers. The MLLM first reasons globally to identify suspicious local regions, which are then delegated to a Local Evidence Verifier (LEV) toolkit for fine-grained appearance and geometric matching. LEV comprises Local Appearance Consistency (LAC), which estimates appearance similarity under illumination and colo

---

### [104] BrainCodes: A Lightweight EEG Foundation Model over Discrete Neural Codes

**链接**: https://arxiv.org/abs/2610.29320
**作者**: Kleanthis Avramidis, Ivan Tashev, Dimitra Emmanouilidou
**来源**: cs.LG cs.NE
**匹配关键词**: EEG, Foundation Models, EEG Foundation Model, Neural Tokenizer
**相关性评分**: 10.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent electroencephalography (EEG) foundation models increasingly emphasize model scale, potentially limiting their deployment on resource-constrained devices and in everyday environments. We argue that transferable EEG features can instead be learned with a compact architecture and introduce BrainCodes, a lightweight foundation model pretrained through self-supervised learning on more than 800 hours of recordings from over 1,000 participants. Our architecture combines a quantization-based neural tokenizer with a spatiotemporal encoder that supports arbitrary electrode configurations. The pretraining objective explicitly encourages representations that capture spatial connectivity through channel positional encoding, and sensitivity to narrowband neural oscillations through an auxiliary training objective. Our model matches or surpasses the state of the art across diverse neurophysiological monitoring tasks, including sleep staging, attention assessment, and cognitive load estimation.

---

### [105] Probing Spatial and Spectral Grounding in EEG Foundation Models

**链接**: https://arxiv.org/abs/2610.29367
**作者**: Kleanthis Avramidis, Ivan Tashev, Dimitra Emmanouilidou
**来源**: cs.NE
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models are advancing at an unprecedented pace, yet their evaluation is driven by downstream accuracy, which reveals little about whether their predictions rely on physiologically interpretable signal structure. We introduce a set of perturbation probes in two grounding axes: spatial grounding in channel identity and topographic locality, and spectral grounding in oscillatory content and waveform morphology. We apply these probes to five published EEG foundation models across motor-imagery and seizure recordings. Our experiments reveal differences in both representational sensitivity and downstream reliance. Electrode identity may be encoded without influencing downstream classification: permuting LaBraM's positional codes heavily displaced its embeddings yet reduced motor-imagery accuracy by only 1.2 points, while spectral details may be discriminable without producing specific responses to simulated clinical markers, as only REVE exceeded a spectral baseline on this tas

---

### [106] NeuroCodec: EEG-Guided Latent-Domain Generative Model for High-Fidelity Target Speaker Extraction

**链接**: https://arxiv.org/abs/2610.29815
**作者**: Julian Silva, Jaliya Kodithuwakku, Navindu Sirimanna, Shaveen Herath, Wageesha N. Manamperi and Joshua P. Kulasingham
**来源**: eess.AS cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Driven by recent advancements in hearing assistive devices, target speaker extraction (TSE) in multi-talker environments has drawn significant attention. To address this, hearing technologies identify attention using neural signals recorded via electroencephalography (EEG) to guide TSE, enabling neuro-steered auditory attention decoding. However, most existing techniques rely on time-frequency masking, which suffers from low fidelity in spectro-temporally overlapping regions and is often restricted to narrowband audio. In contrast, we introduce NeuroCodec, which, to the best of our knowledge, is the first generative EEG-guided TSE framework operating in the latent space of a neural audio codec. Specifically, NeuroCodec models spatial EEG dependencies via graph convolutions and fuses cross-modal EEG and speech representations through attention mechanisms and Mamba-based temporal modeling. We further introduce a six-phase training curriculum that progressively incorporates latent reconst

---

### [107] BrainPro: Process-conditioned Pretraining with Topographic Retrieval for Large EEG Models

**链接**: https://arxiv.org/abs/2509.22050
**作者**: Yi Ding, Muyun Jiang, Weibang Jiang, Shuailei Zhang, Xinliang Zhou, Chenyu Liu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Plausible but Unimplantable: A Trustworthiness Audit of Shape Completion Foundation Models for Cranial Defect Reconstruction

**链接**: https://arxiv.org/abs/2610.30035
**作者**: Marek Wodzinski, Kamil Kwarciak, Daria Hemmerling, Mateusz Daniol
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A patient who has lost part of the skull vault needs an implant that fits the defect exactly, and such implants are still drawn by hand in CAD by specialists, which makes each case slow and expensive. The task can be considered as a shape completion problem, so pretrained completion models, and now the first shape completion foundation models, look like a way to remove that manual step. We audited three publicly released pretrained shape completion models, two of them foundation models, applied zero-shot to 239 cranial defects, some carved from public skull datasets and some real post-craniectomy cases. Each output was compared with simply returning the patient's own remaining bone, and tested for whether the predicted material could be placed without intersecting the bone that is still there. On the 210 carved defects none of the three improved on doing nothing, and on the 29 real cases only one did so beyond chance. Yet not one output, from any model in any configuration, was implant

---

### [109] How Far Can Foundation Models Be Distilled for Efficient Jet Tagging?

**链接**: https://arxiv.org/abs/2610.29439
**作者**: Jay Agarwal, Siddharth Khare, Dhruv Kumar
**来源**: cs.LG hep-ex hep-ph physics.data-an
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jet tagging is one of the most important applications of machine learning at the Large Hadron Collider. Recent models build in more physics knowledge or rely on large-scale pretraining, but the experiments place strict limits on their inference cost. Knowledge distillation can transfer their performance to small students that are cheap to run. We ask which properties of a teacher help the student, how small a student can get and how close it can come to the state of the art. On a jet tagging benchmark, we distil six teachers that differ in architecture, symmetry and pretraining, including two foundation models, into five small students. Every teacher improves every student, and the gain depends mainly on the strength of the teacher. We then shrink our two strongest distilled students, Transformer and L-GATr-slim, in width and in depth. With 20 thousand parameters, a distilled L-GATr-slim outperforms every published jet tagger trained from scratch at a fraction of the inference cost of 

---

### [110] Do Tabular Foundation Models Know Physics? Contamination, Units, and the Deterministic Limit

**链接**: https://arxiv.org/abs/2609.02766
**作者**: Wassim Tenachi, Yashar Hezaveh, Laurence Perreault Levasseur, Pierre-Luc Bacon
**来源**: cs.LG astro-ph.IM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [111] One-Slide Calibration of Pathology Foundation Models

**链接**: https://arxiv.org/abs/2610.08944
**作者**: Ming Ren Hou, Tianyi Huang
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Adversarially Robust Few-Shot Anomaly Detection with Vision Foundation Models

**链接**: https://arxiv.org/abs/2510.13643
**作者**: Akib Mohammed Khan and Bartosz Krawczyk
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] From Weather to Enhanced Weathering: Weather Foundation Models for Carbon Dioxide Removal at Operational Scale

**链接**: https://arxiv.org/abs/2610.28973
**作者**: Sasankh Munukutla, Felipe Oviedo, Danrong Zhang, Kenji Takeda, Juan M Lavista Ferres
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enhanced Rock Weathering (ERW) is a carbon removal solution with the potential to remove gigatons of CO$_2$ per year, but quantifying that removal today requires dense soil sampling and laboratory analysis. We evaluate five weather Foundation Models (FMs) as frozen encoders feeding lightweight decoders, under a leave-one-field-out protocol on 5,192 chronosequences from 264 fields across Brazil and the US. To our knowledge, this is the first holistic evaluation of weather FMs for ERW and the largest evaluation on operational ERW data. We find that across weather FMs, representations transfer to ERW: our best model, TerraNova-ERW, built on Aurora 1.5, positively orders measurements within fields it has never seen. Zero-shot prediction of a new field's mean removal is not yet feasible, and we attribute this to data scale: the same architecture excels on $\sim$$10^5$ natural-weathering sequences, anchoring the scale we expect ERW data must reach. Few-shot prediction, blending the model wit

---

### [114] Leveraging Time-Series Foundation Models for Financial Crime Detection

**链接**: https://arxiv.org/abs/2610.29667
**作者**: Danae Natalie Savvidi, H. \c{C}a\u{g}r{\i} Bilgi, Kubilay Atasu, Arie van Deursen
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial crime detection requires identifying illicit activity within large transaction networks, where suspicious behaviour is rare and unfolds over time. Existing graph-based methods capture relationships among accounts but typically underuse the temporal behaviour encoded in account transaction histories. We introduce Temporal-Context Edge Enrichment (TCEE), a framework that addresses this gap by summarising each account's transaction history with a frozen time-series foundation model (TSFM), and enriching each transaction's representation with the relevant temporal context from these summaries. These enriched representations can be scored directly for edge classification, or fed into a graph neural network (GNN) as edge features to capture broader structural information. Across six AMLWorld datasets, TCEE improves PR-AUC over the strongest evaluated baseline on five by a relative 10.8% on average, while training 6.0x faster end-to-end. Feeding TCEE's representations into a GNN rai

---

### [115] Balancing Foundation Models and Trait-Specific Learning for Forehead-Crease Recognition

**链接**: https://arxiv.org/abs/2610.29495
**作者**: Geetanjali Sharma, Aryan Jain, Dev Nagaich, Aditya Nigam, Raghavendra Ramachandra
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biometric recognition often degrades under partial facial vis- ibility, where conventional facial cues are occluded. The forehead region remains consistently visible and contains distinctive crease patterns that can serve as a complementary biometric trait. We present a unified eval- uation of forehead-crease recognition across explainable zero-shot rea- soning, domain-adaptive learning, and trait-specific modeling. FIRE en- ables interpretable zero-shot verification using multimodal large language models, while pretrained face-recognition models are adapted to the fore- head domain through margin-based learning. Under open-set evaluation, the best zero-shot model GPT-4o+FIRE achieves 18.22% EER, while Edge-Forehead achieves 8.30% EER and 54.01% TMR@0.1% FMR. The results show that although MLLMs offer interpretable zero-shot verifi- cation, trait-specific learning remains more effective for robust forehead- crease biometric recognition.

---

### [116] Unlocking Spatial Grounding in Flow-Matching Models via SNR Tuning

**链接**: https://arxiv.org/abs/2610.29581
**作者**: Martin Thi{\ss}en and Elke Hergenr\"other
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the success of foundation models in image synthesis, achieving fine-grained spatial control remains a significant challenge, typically requiring auxiliary structural adapters or complex inference-time steering. While modern vision-language (VLM) text encoders possess the latent capacity to represent spatial coordinates, generative models often fail to leverage this information. We demonstrate that the signal-to-noise ratio (SNR) distribution is a critical determinant of spatial grounding in flow-matching models. Using a novel synthetic benchmark of geometric primitives, we isolate structural mechanics from textural complexity inherent in natural imagery and introduce a rigorous color-aware layout metric to quantify spatial fidelity. We show that training on a centered SNR distribution results in poor layout adherence (25.9%). Instead, we identify high-noise regimes as a "critical learning phase" for spatial grounding. Shifting the training focus toward these stages increases la

---

### [117] AOV-GS: Active Open-Vocabulary Semantic Mapping with 3D Gaussian Splatting

**链接**: https://arxiv.org/abs/2610.29374
**作者**: Rodion Shkokov, Tatiana Zemskova, Dmitry Yudin
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robots deployed in human-centered environments need maps that support both geometric navigation and open-vocabulary semantic queries beyond a fixed label set. A key challenge is enriching such maps with semantic information without relying on manually annotated segmentation masks or closed-set semantic categories. Existing geometry-driven active mapping maximizes coverage but treats semantics as a passive by-product of the collected trajectory, whereas active semantic mapping typically depends on supervised semantic segmentation. We present AOV-GS, an active 3D Gaussian mapping system that guides exploration using frozen foundation models. During coarse exploration, AOV-GS re-ranks geometrically promising candidate views according to CLIP mask-embedding novelty computed from SAM instance segmentation, biasing exploration toward semantically informative regions. Frozen SAM and CLIP provide instance masks and language-aligned embeddings throughout mapping, while a lightweight scene-speci

---

### [118] Memory-Centric Continual Learning for AI Agents

**链接**: https://arxiv.org/abs/2610.29357
**作者**: Dongfang Li, Zhuoen Chen, Bonian Jia, Zixuan Liu, Zhengxuan Lu, Can Deng 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous agents powered by foundation models can reason, plan, and use tools, but their fixed weights and context limits hinder sustained learning from experience over long-term deployment. While external memory systems attempt to bridge this gap, they mostly act as passive retrieval caches, evaluated primarily by whether they can recall stored facts or past interactions. Whether memory can drive genuine continual learning remains an open question. In this paper, we introduce Memory-Centric Continual Learning (MCCL), arguing that memory should be judged by whether it improves future actions, not merely what it retrieves. MCCL has three main parts. First, a three-axis taxonomy organizes memory by where state is stored (substrates), what form it takes (assets), and how it is managed (policies). This defines a two-loop lifecycle that updates memory state in an inner loop while refining management policies in an outer loop based on task feedback. Second, an evaluation protocol measures r

---

### [119] Rethinking Agentic Model Orchestration for Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.29504
**作者**: Tong Guan, Tianxiang Zhan, Shirui Pan, Ming Jin
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) perform unevenly across forecasting tasks. Recent work uses agentic model orchestration (AMO) to select or combine TSFMs, often outperforming individual forecasters. Yet these gains may reflect stronger or more complementary candidates rather than better orchestration. To disentangle these effects, we introduce FairAMO, a controlled evaluation protocol with frozen candidate forecasts. Experiments on GIFT-Eval show that AMO improves accuracy, but its gains are bounded by the candidate TSFMs. The best orchestrators reduce MASE by less than 6% relative to the best single TSFM across all tasks. These gains depend on complementarity (different candidates excel on different tasks) rather than the number of candidates. Adding members yields diminishing returns, and a redundant member can erase these gains. The value of historical evidence also saturates quickly. A few recent windows capture all gains, and further history adds none. These findings separate

---

### [120] Residual-Based Causal Discovery via Pretrained In-Context Quantile Regression

**链接**: https://arxiv.org/abs/2610.29530
**作者**: Daniel Klippert, Quang Nhat Huynh, Alexander Marx
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Residual-based causal discovery assumes that each variable is generated from its parents and an independent noise source. It estimates this noise and tests its independence from candidate causes. For identifiable functions such as additive-noise models (ANMs) and the broader class of location-scale noise models (LSNMs), this principle identifies the causal direction, as only the causal model admits this independence. Existing LSNM methods rely on parametric assumptions to obtain standardized residuals, risking model misspecification. In contrast, the RESIT-framework allows for nonparametric estimation of residuals to iteratively identify sink nodes, but was proposed for ANMs. To close this gap, we propose Loscar, an extension of RESIT to LSNMs that estimates the conditional mean and scale via quantile regression, enabling pretrained tabular foundation models as plug-in estimators. We compare it with a feasible generalized least squares (FGLS) variant, which is consistent given suitable

---

### [121] Understanding the Inner Workings of a State-Space Foundation Model for Limit Order Books

**链接**: https://arxiv.org/abs/2610.28753
**作者**: Valentin Mohl, Alexandre Bismuth, Aramis Marti-Shahandeh, George Nigmatulin, Kang Li, Stefan Zohren 等 (9 人)
**来源**: q-fin.TR cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive foundation models offer state-of-the-art capabilities to simulate the market by generating the message flow of limit order books (LOBs). Yet, without understanding their inner workings, research directions are hard to narrow and practical use in real-world trading environments remains uncertain. This study therefore asks what these models actually learn about market microstructure. We find that, similarly to games where sequence models build an internal representation of the board, an 8.2M-parameter Mamba-3 state-space model trained autoregressively on the tokenized message stream of eight large-cap US equities learns an internal representation of the market and its dynamics. In particular, order-flow imbalance, a central driver of short-horizon price moves, is decodable at $R^2 \approx 0.59$, far above controls and baselines. This representation extends to unseen stocks, suggesting that these models learn general representations rather than ticker-specific patterns. The

---
