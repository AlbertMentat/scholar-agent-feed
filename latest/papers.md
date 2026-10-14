# 📑 论文索引 - 2026-10-15

共 495 篇论文

---

### [1] Spectral-Driven Adaptive-Rank Optimizer for Large Language Model Reinforcement Learning with Verifiable Rewards

**链接**: https://arxiv.org/abs/2610.16533
**作者**: Zhipeng Chen, Wayne Xin Zhao, Ji-Rong Wen
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) is reshaping how large language models (LLMs) acquire reasoning capabilities, yet the optimizers used remain largely inherited from teacher-forcing training. This raises a fundamental question: does RLVR induce a distinct optimization geometry that calls for a different optimizer? We investigate this question through the spectral structure of LLM gradients and find that gradient energy progressively concentrates into a shrinking effective subspace, which is characteristic of RLVR, as it is absent under supervised fine-tuning (SFT) and is largely removed when the verifiable reward is replaced by a random one. Moreover, the rank required to capture a fixed fraction of gradient energy steadily decreases over training, revealing that the effective dimensionality of useful updates itself evolves with training. These findings motivate a new optimization principle: rather than prescribing the update rank externally, an optimizer should ada

---

### [2] Phantom Merge: When Your Large Language Model Agents Pick One but Tell You About Another

**链接**: https://arxiv.org/abs/2610.16141
**作者**: Wangshu Zhu, Qianwen Guo, Yushun Dong
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly operate over multiple entities, where reliable response generation requires not only retrieving relevant evidence but also preserving its association with the correct entity. We identify Phantom Merge (PM), an entity-evidence binding failure in which an agent attributes unsupported claims to its committed entity, potentially even when the task is completed correctly. We formalize PM at the claim level and characterize its prevalence and error subtypes across four agent domains and four backbone families. To address this problem, we propose a two-stage framework for claim-level risk estimation and correction. First, Anchor-Grounded Risk (AGR) combines a representational readout of the agent's pre-emission hidden state with Jacobian-based functional information, providing complementary slot-level and anchor-value risk scores. Second, Fixed-Anchor Correction (FAC) audits flagged claims and selectively revises them using observed anchor evidence or removes them when

---

### [3] Agent Sociodrama: Social-Dynamics-Guided Persona Recasting for LLM Agent Teams

**链接**: https://arxiv.org/abs/2610.15788
**作者**: Yirui Qi, Xiaoming Zhang, Jaehong Yoon
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly deployed as teams, yet they fail in characteristically social ways: information holders stay silent, dominant speakers anchor groups on wrong answers, and norm violations go unsanctioned. We present Agent Sociodrama, a framework for modeling and validating evolving social dynamics in LLM agent teams. Under fixed personas, agents' emotional states and directed, asymmetric relationships are updated every round by a unified external LLM judge and shape their subsequent interactions. Across six LLM backbones and five social scenarios, we assess social fidelity through classical social-theory patterns and agreement with human judgments. The resulting trajectories exhibit structured social patterns and model-specific differences. We then introduce Trajectory-Guided Persona Recasting (TPR), which diagnoses group-dynamic failures from interaction transcripts and social trajectories and recasts agent personas before rerunning the task. Across f

---

### [4] LLM-HB: Language-Aware LLM-Guided Hotword Biasing for Code-Switching ASR

**链接**: https://arxiv.org/abs/2610.16579
**作者**: Yuxuan He, Genshun Wan, Pengcheng Li, Gongping Huang, Jianqing Gao, Yanmin Qian
**来源**: cs.SD cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code-switching (CS) speech, characterized by language alternation within a single utterance, is prevalent in multilingual communities and poses challenges to automatic speech recognition (ASR) due to rapid language transitions. We propose LLM-HB, a language-aware large language model-guided hotword biasing framework for code-switching ASR (CS-ASR). The framework incorporates a mixture-of-experts (MoE) adaptor and an auxiliary language prediction head to better capture and differentiate multilingual representations, while hotwords are injected through LLM-based prompting. Experiments on the ASRU2019 code-switching challenge test set demonstrate that LLM-HB achieves a 20.30% relative reduction in mixed error rate (MER) over the baseline, reaching 5.85% MER under a 15-distractor hotword setting. To the best of our knowledge, this is the first work to integrate LLM-guided biasing into code-switching ASR. We further release the extracted ASRU2019 hotword list to support future research.

---

### [5] The Price of Precision: A Calibrated Cost Model for Mixed-Precision LLM Serving

**链接**: https://arxiv.org/abs/2610.15629
**作者**: Mukund Athmaram, Manoj Rao, Liang Ma
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Choosing a mixed-precision configuration for large language model (LLM) serving trades speed against accuracy. Allocators that use average bit-width or a memory budget as a speed proxy can miss changes in the resource that limits execution. We argue that served speed can be limited by compute, weight loading, or key-value (KV) cache access, depending on the phase, batch size, and context length. A byte-based proxy does not capture all of these costs, so fewer bits do not always mean faster serving. To address this gap, we build a cost model that accounts for the binding resource and use it in two ways. First, as a predictor: given a configuration and operating point, it estimates serving latency using constants calibrated for the model, GPU, and serving stack. We evaluate its accuracy across three hardware classes. Second, as an allocator: we combine modeled time costs with measured per-tensor accuracy costs and use a dynamic program to select a configuration under a latency or accurac

---

### [6] LLM-Augmented Bayesian Optimization with Adaptive Policies for Chiplet Design Space Exploration

**链接**: https://arxiv.org/abs/2610.14612
**作者**: Hang Liu, Zhengfei Chen, Zhengrui Chen, Hao Geng, Yu Li, Qi Sun
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chiplet technology is a key approach for extending Moore's Law. However, its design process is constrained by two primary challenges: the scarcity of early-stage platforms for rapidly evaluating chiplet-based heterogeneous systems, and the complex relationships between design parameters and optimization metrics. To address these challenges, we propose a synergistic framework that integrates a Large Language Model (LLM) with Bayesian Optimization (BO), enabling architectural-level simulation and automated optimization for the 2.5D/3D CPU-GPU heterogeneous chiplets. We extend the open-source chiplet simulator to evaluate 3D designs by supporting graph topologies. Further, to enhance the exploration efficiency of BO, we introduce an LLM that generates high-quality policies to guide the optimization process, enabled by our proposed adaptive directional policy reasoning (ADPR) and an exploration gain-aware fine-tuning method. Finally, we use the policy-guided BO to perform an automated and 

---

### [7] Can Agents Truly Forget? Explore Machine Unlearning for LLM Agents

**链接**: https://arxiv.org/abs/2610.17659
**作者**: Junkai Lin, Ge Xu, Zheng Xu, Junkai Chen, Xiangyuan Lan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have shown strong capabilities in interactive problem solving, tool use, and long-horizon task execution. However, they may also acquire sensitive or private knowledge during training and expose it during deployment. Retraining a model from scratch to remove such knowledge is prohibitively costly, making machine unlearning a more practical approach. Machine unlearning aims to remove targeted undesirable knowledge from trained models without retraining from scratch while preserving general utility. When language models are deployed as agents, parameter-level unlearning becomes insufficient: forgotten information may still persist in memory artifacts or be reacquired via tool calls. In this paper, we formulate the problem of agent unlearning as removing private information from an LLM-based agent across three information channels: parametric knowledge, persistent memory, and tool-call acquisition. To study this problem, we introduce we introduce Agent Un

---

### [8] AutoSec-RAN: Specification-Grounded LLM Fine-Tuning for Automated Security Analysis of O-RAN

**链接**: https://arxiv.org/abs/2610.15995
**作者**: Anoop Mishra, Joshua Moore, Aly Sabri Abdalla, and Vuk Marojevic
**来源**: cs.CR cs.AI eess.SP
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents AutoSec-RAN, a specification-grounded large language model (LLM) framework for automated security triage of Open Radio Access Network (O-RAN) testing. Unlike approaches relying on static rule sets or privileged access to raw packet captures, AutoSec-RAN fine-tunes Mistral-7B-Instruct through two Low-Rank Adaptation (LoRA) stages over a curated corpus of 69 O-RAN, 3GPP, and adjacent standards documents, then selectively augments inference with retrieval-augmented generation (RAG) over the same specification index. At inference, the model receives only an investigator-style question and a scenario metadata block, simulating an automated analyst operating without raw packet evidence. AutoSec-RAN is validated on a purpose-built 5G/O-RAN testbed across labeled fronthaul distributed denial of service replay scenarios. A Gemma-4-31B judge LLM scores each candidate's answer on faithfulness, correctness, and actionability relative to a reference authored from full packet cap

---

### [9] Make Every Expansion Count: Learning to Search Efficiently in LLM Code Repair

**链接**: https://arxiv.org/abs/2610.15894
**作者**: Elad Sharony, Ido Greenberg, Jialin Song, Shie Mannor, Gal Chechik, Eli Meirom
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) code-repair systems fix faulty programs by repeatedly generating and testing revisions. Each revision is costly, making the choice of which repair to pursue important for efficiency. Existing search policies rely on test pass rates and search statistics, ignoring the details of test failures and proposed edits. We introduce CodeTriage, a learned policy that prioritizes edits before their revised programs are generated and tested. Its 0.6B-parameter model reads the test output, failure diagnosis, and proposed edit, then predicts a distribution over the number of repair steps needed to reach a fix through that edit. These predictions prioritize all pending edits across programs before generating and testing the revised code. On held-out repair tasks, CodeTriage finds fixes with 21% fewer program revisions and 12% fewer output tokens than the strongest baseline on each metric. Without retraining, it achieves the highest average success across search budgets for 

---

### [10] AI-Assisted Tumor-Growth Law Discovery from Sparse Data: Refitting and LLM-Based Ranking

**链接**: https://arxiv.org/abs/2610.16891
**作者**: Yitian Lu and Weinan Wang
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inferring tumor-growth laws from sparse, noisy observations requires more than accurate curve fitting. We study an AI-assisted workflow involving symbolic regression, mathematical admissibility checks, coefficient refitting, and large language model (LLM) ranking. Synthetic Gompertz data allow trajectory fit, forecasting, and recovery of the governing growth law to be assessed separately. A dense noiseless control recovers the generating family, but sparse noisy sampling frequently leads to alternative forms. Among retained candidates in the tested configurations, physics-informed neural network refitting often increases growth-law error, whereas classical nonlinear least squares usually reduces it. A separate exploratory analysis of archived LLM rankings shows no consistent improvement over selection by training error and identifies errors in mathematical reasoning. Plausible saturation, accurate trajectory fits, and convincing explanations can therefore coexist with incorrect growth 

---

### [11] LLM Value Functions for Credit Assignment in Agentic RL

**链接**: https://arxiv.org/abs/2610.15840
**作者**: Kaijie Zhu, Weixiang Yan, Omar Attia, Abbas Kazerouni, Alexander Toshev, Andrew Szot
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) for large language model (LLM) agents remains challenging in long-horizon tasks with sparse outcome rewards, where assigning credit to individual actions is difficult. Methods such as GRPO assign the same trajectory-level advantage to all actions, while critic-based methods require learning an additional value function that can be costly and unstable. We introduce LLM Value Function RL (LVRL), which uses the pretrained knowledge and in-context learning ability of an LLM to estimate policy-aware state values without finetuning a separate critic. LVRL conditions the value model on group context and calibrates its predictions using known values at the initial and terminal states, enabling step-level credit assignment from estimated value differences. We further extend this idea to learning from an expert policy through on-policy distillation (OPD), introducing LLM Value Function OPD (LVOPD), which focuses teacher supervision on actions associated with decreases

---

### [12] CIPHEUR: LLM-Guided Structural Search Control for Conflict-Graph Optimization

**链接**: https://arxiv.org/abs/2610.16158
**作者**: Yuqing Cheng, Yan Jia, Yanjie Song, Xiaolu Liu, Lining Xing, Feng Yao
**来源**: cs.NE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conflict-graph search can stagnate despite effective operators when interventions fail to address the conflicts blocking progress. A disruptive intervention may also require further search before its value emerges. We propose CIPHEUR, a large language model (LLM)-guided framework that connects conflict evidence to coordinated intervention and recovery through Structured Intervention Units (SIUs). The shared control interface supports offline synthesis of executable policies and online contextual decisions. Asynchronous online control sustains native search during inference, while all policies preserve the original objective and feasibility constraints. Across eight satellite-ground scheduling conflict views with five runs per view and a 900-second evaluation cap, CIPHEUR-online achieves the highest mean objective among 11 configurations and increases mean scheduled contact duration by 14.84% over the greedy baseline GWMIN. It exceeds the strongest external per-view mean in seven of eig

---

### [13] FedGraph: Defending Federated Large Language Model Fine-Tuning Against Backdoor Attacks via Graph-Based Aggregation

**链接**: https://arxiv.org/abs/2610.18430
**作者**: Xi Chen, Chunyi Zhou, Rui Zeng, Xiaogang Xu, Zhe Liu and Shouling Ji
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated fine-tuning of large language models (LLMs) allows multiple clients to collaboratively adapt models without sharing raw data, offering strong privacy benefits. However, this setting is highly vulnerable to backdoor attacks, in which malicious clients manipulate their updates to induce targeted behaviors while maintaining normal performance on benign inputs. In this work, we make a key observation specific to federated LLM fine-tuning: malicious clients tend to exhibit strong consistency in their model updates, whereas benign clients produce more diverse and dispersed updates. This structural difference is not well captured by existing defense methods, which typically rely on direct anomaly detection in high-dimensional parameter space and therefore struggle in the presence of entangled LLM updates. Motivated by this observation, we propose FedGraph, a graph-based aggregation framework that explicitly models relationships among client updates. By representing clients as nodes 

---

### [14] Rethinking Quality in Large Language Model Routing: Security-Conditioned Model-and-Budget Selection

**链接**: https://arxiv.org/abs/2610.18566
**作者**: Yichi Zhang, Zhenxiang Huang, Yuyang Zhang, Yuchen Yang
**来源**: cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) routers reduce serving cost by choosing which model to call and how many output tokens to grant it for each query. Existing routers rank model-budget actions using a single quality metric. This does not work for mixed workloads. For ordinary queries, a good answer is correct and useful (utility); for security-sensitive queries, a good answer refuses harmful requests or resists malicious instructions (security). These two objectives prefer different models and budgets. We propose SCRouter, a router that learns when to prioritize security and how to allocate the token budget. For each model-budget pair, it estimates the probability that the response finishes within budget. It uses this probability to predict utility and security separately. A small probe determines how to weight these two predictions for each query. SCRouter then selects the model and budget by balancing the weighted utility and security against cost. We also build SCRouterBench, a benchmark of

---

### [15] TILE: Bridging LLMs and Table Foundation Models for Tabular Learning with Strings

**链接**: https://arxiv.org/abs/2610.17065
**作者**: F\'elix Lefebvre, David Holzm\"uller, Gioia Blayer, Myung Jun Kim, Marine Le Morvan, Ga\"el Varoquaux
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world tables are often heterogeneous, combining numerical features with free-form string columns. Table foundation models (TFMs) excel on numerical tables but require strings to be encoded numerically, while large language models (LLMs) hold semantic knowledge but are not designed for tabular predictions. Most existing bridges use LLMs as plug-in encoders for cell strings, yet how to extract representations effectively for tabular learning remains underexplored. We show that the interface between LLMs and tables matter as much as the LLM itself. Applied cell-wise, larger LLMs do not give better features. With our interface, the same LLMs improve steadily with size. TILE (Table-Interfaced LLM Embeddings) combines four ingredients: row serialization to provide cross-column context, intermediate-layer extraction to avoid layers specialized for next-token prediction, columnar pooling to remove mean pooling's length bias, and by-pass features to route numbers and categories past the LL

---

### [16] ECMR: Evidence-Aware Deliberation Control for Multi-Agent LLM Reasoning

**链接**: https://arxiv.org/abs/2610.17869
**作者**: Yuan Liu, Haoyue Peng, Fanliang Hu, Lei Huang, Wenli Cai
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent Large Language Model (LLM) systems typically commit to a deliberation protocol before inference. A fixed protocol cannot allocate computation differently to resolved and unresolved instances, and it may mistake repeated support for independent confirmation. We study this failure as semantic false consensus: a confident group answer supported by narrow, duplicated, or correlated rationales. We introduce ECMR, an evidence-aware controller over frozen role-conditioned LLMs. At each step, ECMR summarizes answer concentration, support diversity and independence, contradictions, role behavior, verification history, and remaining budget, then selects whether to propose, challenge, verify, arbitrate, diversify, correct a role, or stop. We formulate this decision as finite-horizon budgeted control and derive sufficient conditions under which state conditioning, risk-triggered verification, and role correction improve cost-adjusted utility. Across a declared held-out evaluation of 9,

---

### [17] VH-GPO: Verified Handoff for LLM Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.14000
**作者**: Haoze Li, Peng Zhou, Peiyuan Wu, Weijie Zhao, Yinan Xin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Group-relative reinforcement learning methods such as GRPO train large language model (LLM) agents by comparing rollouts for the same task. When every trajectory in a group fails with the same reward, relative advantages collapse toward zero, leaving no useful learning signal. A frozen teacher can recover from a student-visited state, but letting it complete the task makes the recovered suffix entirely teacher-generated. We ask: after repairing a student failure, when should control return to the student? We propose outcome-verified teacher-student handoff, instantiated in Verified Handoff for Group Policy Optimization (VH-GPO). The teacher provides enough support to reach a state from which the student can succeed, then returns control so that successful experience is again student-generated. Given an environment-verified teacher recovery, VH-GPO selects the earliest independently confirmed handoff point found within a bounded search budget. With Qwen2.5-1.5B, VH-GPO increases success

---

### [18] Large language model-generated patterns for epidemiological modeling: a multi-benchmark evaluation framework

**链接**: https://arxiv.org/abs/2610.15994
**作者**: Sophia Mao, Keshav Gandhi, and Alexander Gutfraind
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representing individual-level behavioral heterogeneity is challenging in epidemiological modeling, particularly when empirical behavioral data are sparse. We assess the potential of large language model (LLM)-generated behavioral outputs in addressing this challenge, using hepatitis C virus-related behaviors among people who inject drugs as a case study. Correspondence with epidemiological patterns was evaluated using external benchmarks: literature-informed association directions, correlations from an agent-based model (ABM), and survey associations. Across three LLMs, unconditional directional recovery across 28 retained literature-informed associations was 46-68%, compared with 82-93% agreement when LLMs were directly asked to classify the same associations. Mean absolute differences from ABM and survey correlation patterns were 0.11-0.13 and 0.15-0.18, respectively. Together, these findings show partial alignment between LLM-generated behavioral relationships and epidemiological ev

---

### [19] LATCH: LLM-Assisted Timing Closure Harness for Post-Route FPGA Optimisation

**链接**: https://arxiv.org/abs/2610.16625
**作者**: Shu Gu, Matthew Youngman, Yuqin Zhao, Cristian Sestito, Ali Siddique, Ramesh Krishnamurthy 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-route FPGA timing closure remains expert-dependent and computationally expensive. We present LATCH (LLM-Assisted Timing Closure Harness), a two-layer framework that separates large language model (LLM) orchestration from deterministic FPGA implementation and evaluation. Across sixteen designs and seven LLMs, a single-iteration study compares three agent control granularities - expert-written recipes, direct EDA operations and LLM-constructed procedures - to ask how much control an agent needs per attempt. Functional-pass rates are 98.2%, 71.4% and 17.9%, respectively; yet direct operations give slightly larger 3.4% median Fmax gains when passing, versus 3.2% for recipes. This exposes a trade-off between execution reliability and timing improvement. Informed by this trade-off, a multi-iteration study fixes the action tier at expert recipes to ask how repeated attempts are best organised, comparing a fitted deterministic heuristic with sequential LLM reasoning, branching exploration

---

### [20] BLADE: Auditing Information Use for Failure Attribution in LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.18780
**作者**: Xiaoguang Guo, Yaohao Long, Chuxu Zhang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model multi-agent systems extend individual agents' capabilities through collaboration across specialized roles, tools, and workflows. Yet collaboration makes failures harder to diagnose: one agent may misinterpret a correct result while others carry the mistake forward. Failure attribution therefore seeks to identify the responsible agent and decisive error step. Recent methods trace dependencies, but knowing where information came from is not the same as knowing where it went wrong. We introduce BLADE (Blame Localization via Audited Dependency Evidence), a training-free framework that moves beyond tracing information to auditing its use. Using Jev for structured probabilistic judgments, BLADE uses dependency probabilities to select relevant source-decision handoffs for auditing. At these handoffs, it examines whether receiving decisions use their sources faithfully and within task requirements, distinguishing error introduction, propagation, and repair. These findings 

---

### [21] AERR-Nav: Adaptive Exploration-Recovery-Reminiscing Strategy for Zero-Shot Object Navigation

**链接**: https://arxiv.org/abs/2603.17712
**作者**: Jingzhi Huang and Junkai Huang and Haoyang Yang and Haoang Li and Yi Wang
**来源**: cs.RO cs.CV cs.LG
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zero-Shot Object Navigation (ZSON) in unknown multi-floor environments presents a significant challenge. Recent methods, mostly based on semantic value greedy waypoint selection, spatial topology-enhanced memory, and Multimodal Large Language Model (MLLM) as a decision-making framework, have led to improvements. However, these architectures struggle to balance exploration and exploitation for ZSON when encountering unseen environments, especially in multi-floor settings, such as robots getting stuck at narrow intersections, endlessly wandering, or failing to find stair entrances. To overcome these challenges, we propose AERR-Nav, a Zero-Shot Object Navigation framework that dynamically adjusts its state based on the robot's environment. Specifically, AERR-Nav has the following two key advantages: (1) An Adaptive Exploration-Recovery-Reminiscing Strategy, enables robots to dynamically transition between three states, facilitating specialized responses to diverse navigation scenarios. (2

---

### [22] Fast and Accurate: Improving Personalized LLM Performance by Semantic Concentration Inspired Workload Split between RAG and Fine-Tuning

**链接**: https://arxiv.org/abs/2610.15921
**作者**: Xingke Yang, Sicong Li, Lingfeng Yao, Rui Chen, Changqing Luo, Xin Fu 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With ever increasing personalized large language model (LLM) services, the next question to answer is how to improve the quality of services/users' experiences, which is indicated by personalized LLM generation accuracy/quality and inference latency. Although state-of-the-art designs, e.g., parameter-efficient fine-tuning (PEFT), retrieval-augmented generation (RAG) or Full PEFT+RAG, can help, they largely ignore the heterogeneous semantic concentrations of users' historical data and cannot fully unleash the potential of personal data for personalized LLM performance enhancement. In this paper, we propose PEFT Union RAG (PUR), a novel ``fast and accurate'' approach that exploits the semantic concentration of users' personal historical data to split workload between PEFT and RAG, aiming to improve personalized LLM performance in terms of better generation accuracy/quality and lower inference latency. Briefly, PUR partitions user's personal historical data and assigns semantic concentrat

---

### [23] Kairos: Transactional Security Enforcement at the System Boundary for LLM Agents

**链接**: https://arxiv.org/abs/2610.18457
**作者**: Kristoffer Hempel, Nils Loose, Lorenzo Cavallaro, Thomas Eisenbarth
**来源**: cs.CR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are becoming an integral part of the software development lifecycle, and the capabilities granted to them allow an agent to act with the user's authority on any resource it can access. The reach that gives an agent its utility is equally available to an attacker who can steer it. Anything an agent ingests can carry an injected instruction, and since the model does not reliably distinguish instructions from data, indirect prompt injection should be mitigated by mediating the effects the agent produces. Such mediation faces a structural difficulty. Legitimate work and the first step of an attack often look alike when an individual action is observed, and what separates them lies later in the trace, so a monitor limited to allow and deny is forced to decide before the evidence accumulates. We present Kairos, a reference monitor at the isolation boundary of an unmodified, opaque agent, where a tool call, a shell command, and a script the agent writes all c

---

### [24] Embodied Zero-Shot Task Planning via Hardware-Aware LLM-VLM Integration for Grounded Robotic Manipulation

**链接**: https://arxiv.org/abs/2610.14106
**作者**: Lonnie Tankersley, Noorbakhsh Amiri Golilarz, Soroush Korivand
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can translate natural-language instructions into plausible manipulation plans, but robotic execution requires physically grounded decisions that respect robot embodiment, workspace geometry, reachability, collision constraints, and grasp feasibility. This paper presents a hardware-aware large language model-vision-language model (LLM-VLM) manipulation framework for a simulated Franka Research 3 robot in NVIDIA Isaac Sim. The framework separates symbolic reasoning from metric execution: an API-hosted LLM planner receives a structured scene summary and generates only symbolic task information, including the object to manipulate, target relation, approach preference, and objects to avoid. A local Qwen3-VL 8B VLM verifier supports semantic confirmation of ambiguous objects and open-container surrogates. Both the LLM planner and the VLM verifier are prohibited from generating robot coordinates, grasp poses, keepout dimensions, gripper commands, trajectory waypoints, or

---

### [25] Can Agents Forget When Asked? A Benchmark for Memory Unlearning in LLM Agents

**链接**: https://arxiv.org/abs/2610.18052
**作者**: Bofan Xie, Chaokun Wang, Guanchen Ge, Songyao Wang, Fang Niu, Hang Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory has become a core component of large language model (LLM) agents. As agents accumulate personal information over long-term use, users increasingly ask them to delete sensitive or outdated facts. A memory system should honor such requests. It should remove exactly what was requested and keep the rest of its memory intact. However, existing memory benchmarks evaluate only memory writing, retrieval, and organization, so whether agents can forget at the user's explicit request remains under-evaluated. To address this gap, we propose Bemula, the first benchmark dedicated to memory unlearning. It comprises 50 multi-session dialogue instances, 135 forget requests of six types, and 1,742 test questions. Each dialogue has a control version without the requests, so that only systems that have stored the target can earn credit for forgetting. Across the paired versions, five test suites measure storage, removal of the requested information, preservation of unrelated memories, rel

---

### [26] Large Language Model Assisted Transportation Planning through a Differentiable User Equilibrium Layer

**链接**: https://arxiv.org/abs/2610.16140
**作者**: Eunseung Lee, Gyeongjun Kim, Keemin Sohn
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Transportation planning has traditionally required substantial expertise in network modeling, traffic assignment, and optimization. As a result, strategic analyses such as network design, capacity expansion, and model calibration remain inaccessible to non-expert decision makers. Recent advances in large language models (LLMs) provide an opportunity to bridge this gap by enabling natural-language interaction with complex transportation planning tools. However, existing LLM-based systems primarily serve as interfaces to simulation software and lack the ability to efficiently search, evaluate, and optimize transportation solutions. This study proposes an integrated human-AI transportation planning framework that combines a large language model, a model context protocol (MCP) interface, an open-source transportation planning engine (AequilibraE), and a differentiable user equilibrium (UE) assignment layer. The framework allows non-expert users to execute network analyses and improve solut

---

### [27] Dissecting the Carbon-SLO Tension in Geo-Distributed LLM Serving

**链接**: https://arxiv.org/abs/2610.14571
**作者**: Burak Topcu, Musa Cim, Zuhal Ozturk, Mahmut Taylan Kandemir
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) inference is driving a growing share of datacenter carbon emissions. Although carbon-aware scheduling can reduce these emissions in geo-distributed datacenters by exploiting the spatiotemporal variations in grid carbon intensity, the latency-sensitive nature of LLM serving constrains this design space. While prior studies investigate the carbon savings achievable through spatial scheduling, they oversimplify the dynamics of modern inference engines, such as queueing and continuous batching, which strongly shape inference latency. We address this issue by designing and evaluating a latency-centric, geo-distributed inference simulator, calibrated with hardware-grounded latency and power measurements, that reproduces these dynamics and enables the study of carbon savings under strict service-level objectives (SLOs). We then formulate a series of SLO- and carbon-aware schedulers of increasing sophistication, from per-request heuristics to batch-level optimization

---

### [28] Learning Perceptual Geometry of Natural Odor Mixtures from LLM-Derived Descriptors

**链接**: https://arxiv.org/abs/2610.17164
**作者**: Farhad Pashakhanloo, Venkatesh N. Murthy
**来源**: cs.AI cs.CL q-bio.NC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The relationship between odor chemistry and perception remains incompletely understood. Many existing studies focus on the perception of single molecules, whereas natural odors contain tens to hundreds of components, adding extra layer of complexity to percept formation. Here, we explore the relationship between molecular composition and perceived similarity in natural odor objects. We study this using a database of more than 1,200 volatile-compound-in-food mixtures containing more than 8,000 molecular components, and use large language models (LLMs) as a scalable surrogate for deriving mixture-level perceptual descriptions. We find that language-derived representations provide useful supervision for predicting held-out mixture similarities from molecular composition. The prediction was consistently strongest when perceptual targets were derived from chemosensory prompts than from other sensory prompts. Further, during the mixture-level training, we learned low-rank molecular embedding

---

### [29] Tokenization-Invariant Watermarking: A Byte-Local Method for LLM Text

**链接**: https://arxiv.org/abs/2610.14378
**作者**: Tung-Ling Li
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Tokenization-Invariant Watermarking (TI-WM), a method that embeds a watermark during token generation but keys and scores it on canonicalized UTF-8 bytes. The detector does not invoke the tokenizer. Canonicalizer-preserving edits leave its score unchanged; other localized canonical-byte edits affect a bounded number of scoring windows. Across three fixed keys and 128 prompts per key and model, a deterministic white-box attack at a 5% word-edit budget leaves mean attacked-AUC 0.530 on Qwen3-8B and 0.664 on Gemma 4 E4B, compared with 0.410 and 0.489 for Unigram with detection-side deletion. These operating points are not jointly matched on quality and clean detectability. Bias sweeps show model-dependent distortion costs, and shared-rule controls support a locality interpretation without establishing a unique advantage of bytes. Visible insertion outside the canonicalizer's deletion set defeats the default design. Alphabetic filtering closes that channel but does not resolve

---

### [30] LLM Agents for Automated Post-Training via Structured Recipe Optimization

**链接**: https://arxiv.org/abs/2610.18572
**作者**: Ruohong Liu, Bohan Tang, Lekang Jiang, Jack Umenberger, Yiwen Guo
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated post-training transforms pre-trained large language models (LLMs) into models capable of handling diverse domains by automatically constructing and optimizing a recipe of coupled decisions over data sources, data processing, cross-domain composition, and training configuration under a limited experimental budget. Existing automation either searches predefined recipe spaces that enable systematic optimization but remain fixed rather than adapting their available choices to the target tasks, or uses open-ended agents that discover task-specific choices but leave them implicit in trial-level edits, limiting their systematic reuse and recombination across trials. To fill this gap, we introduce optimization over a task-adapted recipe space, a novel paradigm that can adapt the recipe space itself to the target tasks while representing its choices explicitly for systematic reuse, recombination, and joint optimization. We instantiate this paradigm with Structured Recipe Optimization 

---

### [31] Same Attack, Different Judge: A First Controlled Adversarial Comparison of Jev, LLM Judges, and Purpose-Built Safety Classifiers

**链接**: https://arxiv.org/abs/2610.17820
**作者**: Xiang Li and Aichun Huang and Mingming Zhang and Zheli Liu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> TypeSafe AI's Jev is a new kind of safety judge. It generates no text and no label: it answers questions the developer defines in advance and returns a probability for each answer. The vendor admits that adversarial input can change these answers but gives no numbers. In this paper, we present the first controlled adversarial evaluation of Jev. We build a test harness that sends every system the same payload under the same policy, and run it on four public-data tasks, from rule-based ones (input moderation, injection detection, routing) to a judgment-based one (phishing detection), with fifty attack variants from thirteen families. The targets are Jev, five GPT and GLM judges, and two local classifiers (Llama Guard 3, Prompt Guard 2). We find that Jev is the most robust system on input moderation: eight forgeries of its structured input bypass none of its decisions, and a sentence asking only why someone might make a harmful request bypasses 9% of its blocks, against 56% for GPT-6 Astr

---

### [32] Evolve as a Team: Collaborative Self-Evolution for LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2605.29790
**作者**: Zhezheng Hao, Tianfu Wang, Huanshuo Dong, Ziyan Liu, Hong Wang, Xiankun Lin 等 (10 人)
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Beyond Answer Voting: Fine-Grained Correction of LLM Reasoning through Graph Alignment across Sampled Traces

**链接**: https://arxiv.org/abs/2610.18606
**作者**: Haotian Liu, Yingjian Chen, Xiaohang Xu, Lang Huang, Yusuke Iwasawa, Yutaka Matsuo 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly tackle tasks that require multi-step reasoning, where errors in intermediate claims can affect the final answer. Self-consistency (SC) improves reasoning by voting over sampled final answers, but its vote leaves intermediate disagreements unresolved. To address this problem, we introduce DDRG (Disagreement-Driven Verification Guided by Reasoning Graphs), a framework for selective correction from a frozen bank of reasoning traces. Our insight is that graph alignment can expose claim-level disagreements and provide correction evidence without expanding the sampled trace bank. DDRG builds source-grounded claim graphs and sends localized conflicts to an answer-blind verifier. A verifier-supported refutation that reaches the majority answer's supporting path triggers one focused repair; otherwise, DDRG returns the exact SC vote. Experimental results across five benchmarks show that native zero-shot DDRG improves macro-average accuracy over direct answering

---

### [34] Local-First Intelligence via Proactive SLM Collaborating with Feedback-Providing LLM

**链接**: https://arxiv.org/abs/2604.17827
**作者**: Hang Zeng, Xiangyu Liu, Yong Hu, Chaoyue Niu, Jiarui Zhang, Shaojie Tang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Triage-PiEvo: Evidence Admission for Principle-Evolving Scientific Agents

**链接**: https://arxiv.org/abs/2610.14683
**作者**: Peize Li and Yingming Pu and Xingguo Xu and Yiming Cui and Yuansheng Gao and Tao Lin
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based AI Scientists advance scientific discovery, yet they suffer from inefficiencies due to noisy observations. Existing principle-evolving agents act on every anomaly, leaving its source unresolved: a new mechanism or an evaluation artifact, so invalid revisions bias evolution. To address this, we formulate revision as evidence admission: anomalies steer search immediately, but only independently verified evidence may rewrite persistent principles, and contradicted principles are retracted. We realize this in TRIAGE-PIEVO , which pairs an anomaly-responsive search portfolio with a staged verification gate that alone controls what enters principle state. Across four scientific tasks with three backbones, TRIAGE-PIEVO (1) attains the highest average solution quality with +7.5%~11.8% over the strongest baseline per backbone, matching the strongest baseline's full-budget quality with one-third of the evaluation budget on Qwen3-235B; and additional stress tests 

---

### [36] Prompt Interference in LLM Post-Training: Why Pass@k Optimization Can Degrade Pass@1

**链接**: https://arxiv.org/abs/2602.21189
**作者**: Anas Barakat, Souradip Chakraborty, Khushbu Pahwa, Amrit Singh Bedi
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] RCR-Router: Efficient Role-Aware Context Routing for Multi-Agent LLM Systems with Structured Memory

**链接**: https://arxiv.org/abs/2508.04903
**作者**: Jun Liu, Zhenglun Kong, Changdi Yang, Fan Yang, Tianqi Li, Peiyan Dong 等 (10 人)
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] Parason: Revealing Subtask and Trial Parallelism in LLM Reasoning

**链接**: https://arxiv.org/abs/2608.24658
**作者**: Zhengyang Zhang, Zijian Zhang, Jiaxuan Gao, Shusheng Xu, Yi Wu, Song Han 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] AlphaPilot: Multi-Turn Tool-Using LLM Agents for Adaptive Alpha Mining with Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.15488
**作者**: Peiqi Jiang, Fan Zhang, Xin Xu, Tianhao Chen, Can Yang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formulaic alpha mining seeks interpretable expressions that rank assets by future returns. The task is challenging because it demands simultaneous processing of unstructured market descriptions, historical data, and quantitative evaluation of candidate factors, yet most existing methods exploit only a subset of these signals. We introduce AlphaPilot, a reinforcement-learning framework that trains multi-turn tool-using LLM agents for adaptive alpha mining. The agent conditions on market descriptions, proposes factor expressions, queries real-data evaluator feedback, and updates a retained factor pool across turns. This design jointly leverages market text, LLM financial knowledge, real data, and evaluation feedback. At inference time, AlphaPilot performs day-by-day search and pool updates to adapt to shifting market regimes. Across three independent runs in out-of-sample rolling backtests on CSI300 and CSI500, AlphaPilot achieves mean total returns of 42.93% and 54.19%, with mean Sharpe

---

### [40] $\mathrm{R}{\scriptstyle\mathrm{EAL}}\mathrm{G}{\scriptstyle\mathrm{UARD}}$: Reliable, Efficient, and Auditable LLM Safeguards via Latent Reasoning

**链接**: https://arxiv.org/abs/2608.03838
**作者**: Zhinan Liu, Jie Li, Mingyu Kang, Jiayi Ji
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Beyond Policy Rollouts: Embedding-Space Directional Exploration with Anchored Noise for LLM RLVR

**链接**: https://arxiv.org/abs/2610.16105
**作者**: Daijiao Liu, Huiyi Wang, Lina Yao, Dong Gong
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) typically uses small rollout groups per prompt, where repeated sampling from the same policy can yield highly similar trajectories, reducing within-group reward variation and weakening group-relative advantage signals. Existing remedies such as higher sampling temperature, entropy bonuses, asymmetric clipping, and larger rollout budgets broaden sampling or modify policy updates but leave rollout conditioning unchanged. In this paper, we propose EDEN (Embedding-space Directional Exploration via anchored Noise), which intervenes at the rollout source through anchored input perturbations. EDEN explores beyond the policy's own rollouts. Within the same rollout budget, it replaces a small fraction of standard rollouts in each group with rollouts that the same policy generates from the prompt plus a single appended, perturbed embedding position, rather than from the prompt alone. Gaussian noise drives variation, while a shared anchor prov

---

### [42] Need or Reputation? Region, National Income, and Academic Status in LLM Gatekeeping Decisions

**链接**: https://arxiv.org/abs/2608.05178
**作者**: Nouar AlDahoul, Hezerul Abdul Karim, Myles Joshua Toledo Tan
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Prompt or Policy? Optimizing Physician Slate Presentations with LLM User Simulators

**链接**: https://arxiv.org/abs/2610.18309
**作者**: Andrei Niculae, Adrian Cosma, Emilian Radoi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Choosing the right physician is a key challenge for patients seeking medical care. Physician recommendation systems identify relevant doctors, but patients still find it difficult to compare their profiles to make a decision. We formulate slate presentation optimization: given a patient's medical case and a fixed, ranked list of physicians, we generate short, case-specific summaries that make doctors easier to compare, while remaining grounded in the information in their profiles. To optimize physician presentations without relying on real patient interactions, we develop an offline framework that uses persona-conditioned LLMs to simulate patient choices. We generate patient personas from attributes extracted from each medical case and evaluate presentations for factual accuracy, relevance, naturalness and simulated patient choice. We also use a second LLM judge, unseen during optimization, to assess simulator-specific overfitting. We compare automatic prompt-level optimization with GE

---

### [44] DBA-Bench: A Production-Fidelity Benchmark for LLM-Based Database Operations Agents

**链接**: https://arxiv.org/abs/2607.22165
**作者**: Junming Chen, Junyang Jiang, Xu Chen, Zibo Liang, and Kai Zheng
**来源**: cs.DB cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] Many Right Answers, One Training Example: Removing Responder Noise from GRPO for LLM Recommenders

**链接**: https://arxiv.org/abs/2610.17771
**作者**: Xin Li, Hao Jiang, Jinghao Guo, Weisi Lin, Chau Yuen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A recommendation request on Reddit draws several replies, each naming different titles. When an LLM recommender is trained on such threads with reinforcement learning (RL), which replies should a generated list be rewarded against? The state-of-the-art recipe, Rank-GRPO, picks one reply per training example, so the advantage mostly records which reply was drawn (85% of its variance) rather than how good the list is. We argue that RL should train on the request, not on each answer, and propose ReMaRk: it scores every list once against the union of all replies' titles and samples each request equally. This makes RL cheaper. On seven backbones and three datasets, ReMaRk reaches the validation recall of 2,000 per-reply RL steps in 25 to 53% of the steps and leads at that budget; trained until neither improves, it is never significantly behind Rank-GRPO and in four of seven pairs reaches Rank-GRPO's best with fewer GPU-hours. The same reward helps on ProtoQA, where about 100 people answer e

---

### [46] Benchmarks Are Not Atomic: Composition-Aware LLM Evaluation using BenchHub

**链接**: https://arxiv.org/abs/2506.00482
**作者**: Eunsu Kim, Haneul Yoo, Guijin Son, Hitesh Patel, Amit Agarwal, Alice Oh
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] When Messages Go Wrong: Understanding Communication Faults in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.15459
**作者**: Jinhao Zhou, Xiaoyu Zhang, Jiongchi Yu, Fahao Chen, Jun Wu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (LLM-MAS) use specialized agents that exchange messages to accomplish complex tasks. Their reliance on networked protocols, remote tools, and model endpoints exposes communication to message loss, delay, and context expiration. Because agents often exchange open-ended natural language, anomalies can alter task-relevant information while leaving messages processable, allowing semantic errors to propagate through subsequent interactions. Systematic studies of faults in inter-agent communication remain limited. This paper presents a large-scale empirical study of how communication faults manifest, propagate, and affect task outcomes in LLM-MAS. We construct a cross-layer taxonomy linking lower-stack disturbances to application-visible faults and develop a fault-injection and tracing pipeline. Our evaluation covers more than 29,000 executions across 100 tasks, five domains, three workflow topologies, and three model configurations. We find that 20.7% of failur

---

### [48] Vela: User Behavior as Supervision Sparks LLM Intelligence

**链接**: https://arxiv.org/abs/2610.14709
**作者**: Yang Xiao, Yusong Sun, Haoyi Wu, Wenyang Hui, Weiqiang Hang, Luqing Wang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed in applications that act on users' long-term behavior histories, from personal assistants to recommendation and advertising systems. These applications demand the user dimension of LLM intelligence: inferring a person's preferences, intent, and likely future actions from weeks to years of behavior data. Yet current models are trained on static text or synthetic data, neither of which captures how user behavior evolves over time. Real-world behavior records, already available at scale on content platforms and in personal-assistant agents, offer a natural supervisory signal. We propose user behavior as supervision and introduce Vela, a framework that converts real user behavior data into trainable tasks and trajectories. From the anonymized behavior records of 100,000 users, Vela generates 100,000 tasks across 91 real-world task templates; difficulty-based filtering and trajectory acceptance criteria retain approximately 75,000 tasks with s

---

### [49] Explore with Memory, Learn without It: In-Context Exploration and Self-Distillation for LLM Reasoning

**链接**: https://arxiv.org/abs/2610.17734
**作者**: Yutong Chen, Zhichao Xu, Rui Liu, Kunpeng Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Exploration bounds learning efficiency in reinforcement learning with verifiable rewards (RLVR). Current methods explore mostly through independent sampling, without fully using the information gathered along the way, such as known wrong answers and environment feedback. We propose LEAF, which injects a dynamic, problem-specific memory into the context before every rollout. The memory contains the most recent response, its reward, and other environment feedback. It is updated after every verifier call. We decouple policy updates from rollouts and update the policy through self-distillation. On four benchmarks and two open models, LEAF accelerates exploration by about 4x compared with a random sampling baseline. On unseen test sets, it improves accuracy over the strongest baseline by 1.59 and 1.83 percentage points on the two models, while using less compute than any RL baseline. These results highlight the potential of LEAF in improving both exploration and learning efficiency. Code is

---

### [50] TSRL: Trigger-based Supervised Reinforcement Learning for Continual Agent Training

**链接**: https://arxiv.org/abs/2610.17726
**作者**: Yuqian Fu, Kaiwen Jiang, Zijun Song, Jiawei Wang, Yuanheng Zhu, Dongbin Zhao
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents excel at complex, multi-step tasks but suffer from catastrophic forgetting during continual learning--acquiring new skills often degrades previously mastered capabilities. Existing post-training paradigms face a fundamental trade-off: Supervised Fine-Tuning (SFT) is sample-efficient but prone to severe forgetting, while Reinforcement Learning (RL) preserves prior capabilities but converges slowly without expert guidance. To bridge this gap, we introduce Trigger-based Supervised Reinforcement Learning (TSRL), a framework that integrates the strengths of both paradigms through an adaptive, state-dependent expert supervision mechanism. TSRL employs RL as the optimization backbone, activating SFT selectively on "hard states" where the policy fails. Theoretically, we show that restricting supervision to failure states derives an upper bound on the cumulative parameter updates, thereby reducing forgetting compared to full SFT. Empirically, TSRL achieves cons

---

### [51] ACED-Bench: Evaluating How LLM Agents Acquire and Act on Causal Evidence

**链接**: https://arxiv.org/abs/2610.14381
**作者**: Yiwei Chen, Amila Weerasinghe, Siddharth Biswal, Utkrisht Rajkumar, Olcay Boz, Taylor Berg-Kirkpatrick 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used as scientific assistants, yet we still lack reliable ways to evaluate whether they can investigate a system rather than merely answer a prompt. A useful evaluation must let agents choose experiments, interpret finite evidence, and make causal decisions, while keeping the environment coherent across repeated observations and interventions and preserving objective ground truth. We introduce ACED-BENCH (Active Causal Evidence and Decision Benchmark), a neuro-symbolic benchmark built around this requirement. The key idea is to separate the readable scientific surface from the formal causal world: LLMs generate natural-language scenarios and task text, while hidden probabilistic graphical models define the causal graph, data-generating process, intervention semantics, validation checks, and oracle answers. This yields scientific worlds that are natural for agents to investigate but exact enough for scalable, programmatic evaluation. The main leade

---

### [52] Lost in Context Compaction: When LLM Systems Drop Side Constraints

**链接**: https://arxiv.org/abs/2608.11242
**作者**: Zhiqi Wang, Yichi Zhang, Dongwon Lee, Nathalie Baracaldo, Yuchen Yang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] Sera: Semantic Representation Aggregation with Knowledge and LLM for Reliable and Interpretable Battery Health Forecasting

**链接**: https://arxiv.org/abs/2610.11567
**作者**: Jiawei Li, Fang Liu, Wei Zhang, Zuming Liu, Man-Fai Ng, Zhi Wei Seh
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] RT-J: Large-Scale Pretraining of Relational Transformers for Context-Efficient Predictions

**链接**: https://arxiv.org/abs/2610.17867
**作者**: Rishabh Ranjan, Vignesh Kothapalli, Harshvardhan Agarwal, Charilaos Kanatsoulis, Roshan Upendra, Tom Palczewski 等 (8 人)
**来源**: cs.LG cs.AI cs.DB
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for tables and relational databases are increasingly used for predictive tasks across various scientific and industrial domains. However, adapting existing models to unseen datasets requires tens of thousands of examples. Here we introduce RT-J, an 85M-parameter relational foundation model (RFM) that makes accurate predictions even with hundreds of in-context examples or fewer. To achieve this, we first assemble the Join, a large collection of 639 web-crawled databases with 6,023 LLM-generated forecasting tasks. We pretrain with long contexts of up to 8,192 database cells, using in-context examples from a novel lightweight random-walk retriever. Finally, we leverage context tuning and ensembling to scale up test-time compute. On in-context regression tasks from RelBench, RT-J requires 10x fewer examples on average to match strong feature engineering pipelines with LLM-agent or RDBLearn featurizers and TabICLv2 or LightGBM predictors. Overall, our work pushes the front

---

### [55] When Agent Evaluation Becomes Unreliable: An Empirical Study of Oracle Failures and Configuration-Dependent Measurement in an LLM Agent Benchmark

**链接**: https://arxiv.org/abs/2610.16067
**作者**: Junjie Chen
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent evaluation harnesses are software systems that run test suites, generate inputs, and decide outcomes with test oracles. This paper audits such software for reliability defects that score tables cannot reveal. We introduce an oracle-integrity auditing approach with five state-integrity invariants and three known-answer controls. We evaluate it by injecting seven oracle defect classes across two task domains and a synthetic domain. All injected defect classes are detected, and the repaired oracle has no false positives. Applied to an agent benchmark, the audit reveals a reward-function defect that changes the environment state before post-run scoring. Across 4,320 episodes, replay-based correction changes database-pass labels from 4,194 to 2,883 and reduces measured success from 94.3% to 65.5%. We also study configuration-dependent measurement effects. A component ablation over 3,240 episodes shows that the agent's policy documents, tool descriptions, and tool error strings influen

---

### [56] Rep2Skill: Representation-Guided Skill Self-Evolution for LLM Agents

**链接**: https://arxiv.org/abs/2609.39149
**作者**: Kaixing Zhang, Changming Li, Yingdong Shi, Zheng Zhang, Kaitao Song, Wenjie Shi 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] LATTEArena: An Evaluation Framework for LLM-powered Tabular Feature Engineering (Extended Version)

**链接**: https://arxiv.org/abs/2606.09004
**作者**: Ankai Hao, Ke Chen, Huan Li, Lidan Shou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] Do LLM Tutors Actually Teach? A Process-Centered Synthesis of the Tutoring Loop

**链接**: https://arxiv.org/abs/2610.15692
**作者**: Sayantan Adak, Rima Hazra, Koyel Mukherjee, Digbalay Bose, Somnath Banerjee
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can produce fluent tu- toring dialogue, but whether they actually help students learn remains unclear. We present a process-centered synthesis of LLM tutoring that follows the path from learner-state infer- ence to pedagogical action, tutor training, eval- uation, and student simulation. This view ex- poses a central gap: implementing a tutoring component does not establish that it works or that its outputs meaningfully affect later stages. A structured study-level audit shows that peda- gogical evaluation is common, while evidence becomes much thinner for learner-conditioned intervention, human learning gains, and espe- cially transfer or delayed retention. Human studies nevertheless provide a conditional posi- tive result: LLM tutors can improve learning, but benefits depend on pedagogical structure, learner engagement, and how learning is mea- sured. We argue that progress requires validat- ing the interfaces between tutoring stages, not only improving individu

---

### [59] LLM-OSDA: An Optimal-Stopping Dynamic Auction for Native Advertising in Multi-Turn LLM Conversations

**链接**: https://arxiv.org/abs/2608.00123
**作者**: Yan Fang, Jialin Chen, Chun Gan, Hang Yu, Mingjun Nie, Yeyu Zhang 等 (8 人)
**来源**: cs.CL cs.AI cs.GT cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] Polyrating: A Cost-Effective and Bias-Aware Rating System for LLM Evaluation

**链接**: https://arxiv.org/abs/2409.00696
**作者**: Jasper Dekoninck, Maximilian Baader, Martin Vechev
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] Constitutional Gating and Deterministic Recovery for Multi-Agent LLM Negotiation: Ablations Against a Stateful Adversarial Gatekeeper

**链接**: https://arxiv.org/abs/2610.11542
**作者**: Masaaki Nakatsu (AO, Inc. / OrbLabs AG), Reno Wang (AO, Inc.)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] OracleProto: A Reproducible Framework for Benchmarking LLM Forecasting via Knowledge Cutoffs and Temporal Masking

**链接**: https://arxiv.org/abs/2605.03762
**作者**: Yiding Ma, Chengyun Ruan, Kaibo Huang, Jin Tan, Zhongliang Yang, Linna Zhou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] A, B, C, or Stable? Accuracy and Order Sensitivity Diverge in LLM Multiple-Choice Evaluation

**链接**: https://arxiv.org/abs/2608.11947
**作者**: Karl Hanna and Chen Feng
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Echo: Error-Compensated 4-Bit Tensor-Parallel Communication for LLM Training and Inference

**链接**: https://arxiv.org/abs/2610.14277
**作者**: Xingyu Xie, Xiaoyong Xie, Zhouchen Lin, Kim-Chuan Toh
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tensor parallelism ends every layer with an all-reduce that sits between two dependent matrix multiplications, so its cost cannot be hidden and grows as compute outpaces interconnect bandwidth. Sending 4-bit instead of 16-bit values would cut this cost by nearly 4x, but the all-reduce must add the values it carries, and rounding the sum injects an error at every call. Model quality depends on how these errors accumulate over layers, yet existing methods treat each call on its own. We present Echo, a 4-bit all-reduce for training and inference that controls the accumulated error. Echo moves data in 4 bits and sums in high precision, so each value is quantized at most twice per call for any number of GPUs. The summation reveals each injected error, and Echo feeds it back into later calls, so old errors cancel instead of accumulating. We prove that the accumulated error stays bounded independently of depth. On A100 GPUs, Echo is 2.09x faster than the 16-bit NCCL all-reduce on 1 GB message

---

### [65] SoFT: Soft Targets for Generalizable LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2609.32493
**作者**: Huihao Jing, Wenbin Hu, Shaojin Chen, Haochen Shi, Zhongwei Xie, Guijia Zhang 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Can an Agent Learn to Predict Its Own Failure? Outcome-Grounded Confidence Calibration in LLM Agents

**链接**: https://arxiv.org/abs/2610.18614
**作者**: Ashutosh Hathidara
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Controlling an acting LLM agent means deciding, at each step of a long-horizon task, whether to trust its next action, abstain, or hand off to a human. That decision needs a per-step confidence signal predicting whether the current rollout will eventually succeed. The agent's own self-reported verbalized confidence is the natural candidate, but existing reinforcement learning methods calibrate it against the correctness of a decision at the current step. We propose a method to calibrate it against the eventual outcome of a multi-step episode: under GRPO, the group of rollouts for a task supplies success labels, and a proper scoring rule scores each step's confidence against the realized outcome. In offline RL on recorded trajectories of a Qwen2.5-7B agent in ALFWorld, TextWorld, and WebShop environments, the AUROC of step confidence against episode outcome rises from near chance to 0.68-0.85, and the top-10% of steps the agent is most confident about succeed ~4.3x more often than avera

---

### [67] LaCache: Robust Semantic Caching for LLM Serving

**链接**: https://arxiv.org/abs/2608.01718
**作者**: Jiacheng Liang, Yuhui Wang, Tanqiu Jiang, Ting Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Call-Chain-Aware LLM-Based Test Generation for Java Projects

**链接**: https://arxiv.org/abs/2604.22046
**作者**: Guancheng Wang and Qinghua Xu and Lionel C. Briand and Zhaoqiang Guo and Kui Liu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] The Geography of Algorithmic Judgment: LLM Intermediaries, Place Identity, and Racial Steering in Housing Search

**链接**: https://arxiv.org/abs/2606.06694
**作者**: Hana Samad, Trung Lam, Christoph M\"ugge-Durum and Michael Akinwumi
**来源**: cs.LG cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] SolBehave: Evaluating the Behavioural Correctness of LLM-Generated Smart Contracts

**链接**: https://arxiv.org/abs/2610.18745
**作者**: Giovanni Pio Delvecchio, Stefano Fantazzini, Giacomo Frisoni, Gianluca Moro, Lorenzo Bacchiani, Mario Bravetti 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly generate Solidity smart contracts that, once deployed, can never be patched, making a single latent fault permanent and exploitable. Yet current evaluations mostly ask only whether generated code compiles. We introduce SolBehave, a benchmark for evaluating the correctness of model-generated contracts at scale, moving beyond ad hoc unit tests. Across 250 real, reproducible Ethereum contracts, we apply three complementary tests of behavioural fidelity: differential fuzzing, historical-transaction replay, and, as our core contribution, synthetic-transaction replay guided by a Dynamic Condition Response (DCR) graph that enumerates the space of legitimate function-call sequences. Differential fuzzing compares each generated function with the original on automatically generated inputs; historical replay compares the whole contract on the transactions it actually received on-chain; DCR-guided replay compares it on sequences of calls that follow its intended 

---

### [71] Hashrope: A Persistent Data Structure for Mechanisms of LLM Context Management

**链接**: https://arxiv.org/abs/2610.16144
**作者**: Muntaser Syed (Florida Institute of Technology), Ameerah Alsulami (Florida Institute of Technology), Marius Silaghi (Florida Institute of Technology)
**来源**: cs.DS cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serving stacks for large language models manage context through four recurring mechanisms: incremental edits to a growing context, branching and snapshotting for tree search, identification of reusable prefixes for KV-cache reuse, and encoding of repeated segments. Each mechanism is served today by a different specialist structure. We show that all four reduce to a single persistent weight-balanced rope whose every node carries a polynomial hash of its subtree over a Mersenne prime, so that the structure supports logarithmic edits and logarithmic verified content-identity queries at the same time. We validate each mechanism with pre-registered, replicated experiments, then compare against a deployed specialist per mechanism: the Ropey editing library, a faithful PagedAttention copy-on-write block table, and the vendored SGLang radix matcher. On workloads that interleave edits with identity queries, Hashrope is net-superior to Ropey by a factor that grows without bound (369.7x at one mi

---

### [72] What Is the "Self" of a Large Language Model?

**链接**: https://arxiv.org/abs/2610.16717
**作者**: Yuchen Li, Zongqi Fan, Xintong Li, Ken-tye Yong, Nguyen H. Tran
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What could the "self" of a large language model be, if it is neither a particular word nor a single privileged layer? We propose a relational account: a functional self is an actor-centered organization of information that distinguishes the model's recorded actions from externally supplied material while content and reasoning operations change. Its representational candidate is a family of layer-specific source-binding components, rather than one unchanged vector throughout the network. Preliminary observations from a 27B BF16 model provide a geometric starting point. Across 150 matched message bodies, 450 role conditions, and a 75/75 discovery-held-out split, the combined Assistant-versus-external displacement transfers strongly across bodies and positions. Selected early components place User and System closer to one another than to Assistant, whereas this full-space distance relation does not persist throughout depth. These findings motivate a layered account: an early source-encodi

---

### [73] When LLM Agents See a Conflict but Still Proceed: Cross-Domain Dependencies in Network Slicing

**链接**: https://arxiv.org/abs/2610.17118
**作者**: Marcos Lima Romero and Ricardo Suyama
**来源**: cs.AI cs.CL cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Future AI-native networks are being designed to apply autonomous agents built on large language models (LLMs) in network management through intents. When intents from different domains meet on the same resource, an agent must recognize the cross-domain dependency before taking an irreversible action. We investigate this problem through a smart-grid use case, in which a power utility holds an active intent on a backup slice for protection traffic. This slice appears idle by design, which is precisely the profile targeted by a cost-reduction intent. We built a tool-based environment in which the dependency must be either queried by the agent or read from an inventory annotation, together with a negative control, and evaluated ten models from four different providers in 600 runs. Most models acted against the dependency they had observed: seven of the ten models removed the protection slice at least once after receiving the cross-domain dependency, and in the high-harm tier the slice was 

---

### [74] PixelMoE: Scaling Pixel-Space Diffusion with LLM-Style Mixture-of-Experts

**链接**: https://arxiv.org/abs/2610.18857
**作者**: Ruixiao Dong, Jianmin Bao, Bozhi Luan, Zijie Meng, Xin Tao, Pengfei Wan 等 (9 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pixel-space diffusion models provide an appealing alternative to latent-space diffusion models by directly modeling raw images without relying on a learned tokenizer. However, scaling pixel-space models has predominantly followed dense strategies, tightly coupling model capacity with active computation. In this work, we show that standard LLM-style Mixture-of-Experts (MoE) architectures can be effectively transferred to pixel-space diffusion. Building on this finding, we introduce PixelMoE, a pixel-space generative framework that sparsely scales model capacity with standard LLM-style MoE, without diffusion-specific routing mechanisms or auxiliary routing objectives. Specifically, PixelMoE combines standard Token-Choice (TC) routing with fine-grained routed experts for input-adaptive sparse computation, a shared expert for capturing common representations, and a bias-based load-balancing strategy. To complement sparse capacity scaling, PixelMoE further introduces Pixel-Space Hierarchica

---

### [75] Rethinking LLM-Guided Visual Question Answering: Does Deeper Knowledge Integration Really Help?

**链接**: https://arxiv.org/abs/2610.17079
**作者**: Aneerban Saha, Vijay Kumar, Sameer Madhav D., Priyam Srivastava and Dhruv Bansal
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge-based Visual Question Answering (VQA) requires reasoning that extends beyond visible image content, demanding external commonsense and factual knowledge. While recent work leverages Large Language Models (LLMs) as knowledge sources, the question of how deeply such guidance should be integrated into a vision language architecture remains underexplored. In this work, we generate structured reasoning guidance, visual focus concepts, distractor elements and external knowledge using Llama~3.3~70B and systematically compare two integration strategies within a unified frozen ViT + FLAN-T5 framework on the OK-VQA benchmark: decision level late fusion and attention-matrix injection. Contrary to the prevailing assumption that deeper integration is superior, we find that shallow late fusion achieves the strongest results (39.4% exact match, +10.0 over the no guidance baseline), outperforming deep attention modification (31.8%) under data scarce fine-tuning. We further contribute an LLM 

---

### [76] P2Skill: Privacy Preserving Skill Distillation for Cloud-Local LLM Inference Systems

**链接**: https://arxiv.org/abs/2608.14094
**作者**: Myunghoon Ryu, Geunpyo Park, Sungjoon Lee, XinYu Piao, Jong-Kook Kim
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] SERQ: Saliency-Aware Low-Rank Error Reconstruction for LLM Quantization

**链接**: https://arxiv.org/abs/2603.08185
**作者**: Yeonsik Park, Hyeonseong Kim, Seungkyu Choi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] When LLM Reward Design Fails: Diagnostic-Driven Refinement for Sparse Structured RL

**链接**: https://arxiv.org/abs/2605.28918
**作者**: Youting Wang, Yuan Tang, Bowen Liu, Xuan Liu and Dingyan Shang
**来源**: cs.LG cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] SoK: Systematizing LLM Prompt Security: Taxonomies, Datasets, and Unified Evaluation of Attacks and Defenses

**链接**: https://arxiv.org/abs/2510.15476
**作者**: Hanbin Hong, Shuang Wu, Shuya Feng, Nima Naderloui, Shenao Yan, Jingyu Zhang 等 (9 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] From Acoustic Sensing to Physical Actions: A Comprehensive Survey of Security Risks in Edge-Deployed Audio LLM-Based Agents

**链接**: https://arxiv.org/abs/2610.15390
**作者**: Binhong Wang, Haidong Kang, Yanfeng Zhang, Hong-Ning Dai, Guo Yu, Shangce Gao
**来源**: cs.CR cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio Large Language Models (Audio LLMs) are embedded in agents for smart homes, vehicles, wearables, and embodied systems, where acoustic inputs can propagate from perception into persistent state and consequential execution. This setting extends security analysis beyond model behavior to the system conditions that determine how acoustic inputs can influence agent behavior and external actions. Existing surveys examine acoustic security, LLM-based agents, and edge deployment in isolation, leaving their security interactions in deployed Audio LLM-based agents insufficiently characterized. This survey introduces an Acoustic Sensing-to-Action (S2A) system model that traces these security implications along the path from acoustic sensing to external execution, while accounting for edge-cloud runtime and lifecycle transformation. We use the model to synthesize attacks, defenses, and evaluation methods across the acoustic, agent, and edge-system literature. The synthesis shows that security

---

### [81] Semantic Saliency from Multi-Modal Large Language Model Scene Understanding Maps

**链接**: https://arxiv.org/abs/2610.15467
**作者**: Ziqi Wen, Shravan Murlidaran, Jonathan Skaza, William Wang, Miguel P. Eckstein
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image-computable low-level image saliency has shaped perceptual psychology and computer science, but is limited by its inability to capture human high-level cognitive factors that influence attention and eye movements. Here, we propose a new fully automated method to compute semantic saliency by quantifying each object's contribution to scene comprehension without fitting any parameters to human data: the Automated Scene Understanding Map (AUTO-SUM). AUTO-SUM automatically segments and removes individual objects from a scene, uses multimodal large language models (MLLMs) to describe the original and modified scenes, and measures the semantic similarity between these descriptions using text embeddings. We show that AUTO-SUM can predict which object is most important in a human-measured scene understanding map (H-SUM) estimated using human scene descriptions. We also show that AUTO-SUM can predict the object most fixated by human observers during free viewing and scene description tasks 

---

### [82] ContinualSkillBench: Can LLM Agents Truly Evolve Their Capabilities?

**链接**: https://arxiv.org/abs/2608.03874
**作者**: Tianyi Guan, Yiding Wang, Haotong Yang, Siyuan Cao, Shirui Liu, Yi Hu 等 (8 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] Retrieval-Augmented Large Language Model Decision-Making for Autonomous Driving Guided by Chinese Philosophical Wisdom

**链接**: https://arxiv.org/abs/2610.03948
**作者**: Xiaojun Bi, Xiaoyuan Ma, Yiwen Sun, Tianren Huang, Chaoran Liu, Bokai Huang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] Optimize Once, Execute Fast: Latency-Aware Multi-Agent Workflow Learning for Recurrent Queries

**链接**: https://arxiv.org/abs/2610.14481
**作者**: Enpei Zhang, Feiyu Qu, Zheng Huang, Dawei Zhou, Elynn Chen, Yujun Yan
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model-based Multi-Agent Systems (LLM-based MAS) have shown remarkable success in solving complex tasks by coordinating specialized agents through multi-step workflows. To overcome the high cost and specificity of manually designed workflows, recent research has shifted toward learning them automatically. However, a key limitation remains: while agent calls introduce significant latency due to model inference time and service congestion, most automated methods optimize solely for downstream performance, ignoring execution time (makespan). This issue is amplified when workflows are reused across recurring queries, making latency accumulate over time. This limits deployment in recurrent applications such as AI customer support and AI cloud troubleshooting, where users expect fast responses. To bridge this gap, we introduce a new problem, termed latency-aware workflow generation, where the objective is to minimize workflow makespan while aiming to retain downstream performan

---

### [85] Better with Experience: Self-Evolving LLM Agents for Evidence-Grounded Health Community Notes

**链接**: https://arxiv.org/abs/2606.02215
**作者**: Zihang Fu, Fanxiao Li, Jianyang Gu, Haonan Wang, Preslav Nakov, Bryan Hooi 等 (8 人)
**来源**: cs.CL cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] ATTUNE: Agentic Throughput Tuning for LLM Training

**链接**: https://arxiv.org/abs/2610.17528
**作者**: Leo Fan, Hongyang Wang, Wenbo Chen, Jingguo Liu, Xian Li, Xuan Wang 等 (10 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training recipes are tuned by hand for one model, cluster and workload, and every new model, accelerator, framework version or dataset means tuning again. Automated tuners search a fixed space of knobs and check only that a job runs, yet a configuration can run to completion while it silently changes training. ATTUNE is a single coding agent that tunes any working recipe for the workload and stack at hand, unattended, within a GPU-hour budget the user sets. It diagnoses each run and changes one lever at a time, guided by a catalog of lessons from past campaigns, and ships a recipe only if it passes a correctness gate: a configuration check against objective-changing settings and known stack defects, and a convergence check of its loss curve against the baseline's. On four held-out models at 64-128 GPUs, ATTUNE raises mean throughput over the strongest public recipe run on our stack by 6.7% on Llama-3.1-405B (best campaign 11.9%) and 33.9% on GLM-4.5 (54.7%), whose public recipe was wri

---

### [87] Iterative Critique-Refine Framework for Enhancing LLM Personalization

**链接**: https://arxiv.org/abs/2510.24469
**作者**: Durga Prasad Maram, Dhruvin Gandhi, Zonghai Yao, Gayathri Akkinapalli, Franck Dernoncourt, Yu Wang 等 (8 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] LLM-to-Flow Distillation: Teaching Natural Language Goals to Scientific Generators

**链接**: https://arxiv.org/abs/2610.17246
**作者**: Riccardo De Santi, Federico Di Gennaro, Angelo Gnazzo, Sophia Tang, Pranam Chatterjee, Fanny Yang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative discovery in science requires coupling high-level scientific reasoning with the ability to generate samples respecting the structure of a design space. Yet these capabilities remain largely separated: foundation LLMs encode broad chemical and biological knowledge, while domain-specific flow- and diffusion-based generators capture the priors needed to produce valid sequences and geometries. We study how to align such scientific generators to high-level natural-language discovery goals without requiring an explicit proxy reward, which is often unavailable or poorly captured by learned predictors in experimental sciences. We introduce LLM-to-Flow Distillation (LFD), where a frozen LLM acts as an adaptive teacher for a domain-specific generator. Given a goal such as 'generate peptides with promising anticancer activity', the teacher constructs a curriculum of intermediate sub-goals aware of the flow's current capabilities, and progressively directs them toward the original disco

---

### [89] Human-LLM Deliberation as Interactive Proof: Conditions for Verifiability Without Transparency

**链接**: https://arxiv.org/abs/2609.24895
**作者**: Baotong Zhang, Dean Foster, Jo\~ao Sedoc
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] CataOPD: Catalytic On-Policy Distillation for Large Language Model Reasoning

**链接**: https://arxiv.org/abs/2609.29518
**作者**: Wenjin Liu, Chenxi Wang, Jiapu Wang, Zhe Cui, Anh Tuan Luu, and Haoran Luo
**来源**: cs.LG cs.CE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [91] Right Number, Wrong State? Measuring Cross-Jurisdiction Substitution in LLM Recall of State Policy

**链接**: https://arxiv.org/abs/2610.09458
**作者**: Jiayu Feng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] MemForm: Benchmarking Memory Formation Poisoning in LLM Agents

**链接**: https://arxiv.org/abs/2610.14431
**作者**: Haowen Pan, Pengyang Shao, Yunshan Ma, Yanzheng Jin, Naixin Zhai, Xiang Wang 等 (7 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory enables LLM agents to learn from past interactions but exposes memory formation to adversarial influence. Existing studies primarily organize memory poisoning by attack channels, corruption patterns, or lifecycle stages, leaving formation interfaces insufficiently characterized. We formulate Memory Formation Poisoning as adversarial manipulation of the interfaces through which persistent agent memory is produced and committed, and introduce MemForm, a controlled diagnostic benchmark covering five interfaces: Content, Evidence, Scope, Selection, and Path Poisoning. We introduce Selection and Path Poisoning as controlled intervention categories that isolate retention and consolidation order effects, respectively. Each category pairs clean and poisoned conditions with interface-specific controls. Evaluations across six LLMs and two response formats reveal broad susceptibility at all five interfaces under the evaluated memory protocols and implementations. Crucially, authe

---

### [93] Beyond Trajectory Imitation: Strategy-Guided Policy Optimization for LLM Reasoning

**链接**: https://arxiv.org/abs/2606.24064
**作者**: Tianyuan Shi, Canbin Huang, Bei Li, Xin Chen, Xiaojun Quan, Jingang Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [94] Requests of a Feather Must Flock Together: Batch Size vs. Prefix Homogeneity in LLM Inference

**链接**: https://arxiv.org/abs/2605.06046
**作者**: Saksham Rathi, Preeti, Mythili Vutukuru
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] WildTrace: Evaluating Training Data Detection in Realistic Large-Scale LLM Post-Training

**链接**: https://arxiv.org/abs/2610.16152
**作者**: Hengxiang Zhang, Junxian Liu, Hongxin Wei
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although post-training significantly enhances model performance, the use of massive undisclosed data raises concerns about benchmark contamination and copyright infringement. This drives growing interest in training data detection for post-trained models. Existing evaluations for training data detection often leverage benchmarks constructed post hoc, which can introduce distribution shifts. Alternatively, controlled evaluations rely on small-scale training setups that diverge from realistic post-training settings. As a result, their reported performance may not faithfully reflect the effectiveness of detection methods in real-world scenarios. To this end, we introduce \textsc{\method}, a reliable benchmark designed to evaluate detection methods in realistic, large-scale post-training settings. Built on a multi-stage pipeline, \method\space encompasses stage-specific models throughout the post-training lifecycle, spanning SFT, DPO, and RL. To perform a reliable evaluation, we construct 

---

### [96] AdvJudge-Zero: Binary Decision Flips in LLM-as-a-Judge via Adversarial Control Tokens

**链接**: https://arxiv.org/abs/2512.17375
**作者**: Tung-Ling Li, Yuhao Wu, Hongliang Liu
**来源**: cs.LG cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] UDHRBench: Benchmarking Human Rights in Large Language Models

**链接**: https://arxiv.org/abs/2610.15179
**作者**: Alak Raad (1), Noreldin Morssy (1), Zeerak Suhail (1), Serin Atiani (2), Mustafa Jarrar (1) ((1) Hamad Bin Khalifa University, Qatar 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed in contexts requiring adherence to ethical and legal norms, yet their alignment with internationally recognized human rights standards remains underexplored. We introduce UDHRBench, a large-scale benchmark for operationalising the evaluation of large language model compliance with the Universal Declaration of Human Rights. The dataset comprises 1,124 human rights confronting questions covering all 30 articles and 4,496 responses from four large language models (ChatGPT, Grok, Gemini, and Fanar), manually annotated by experts for alignment, with high inter-annotator agreement ($\kappa = 0.801$). Our analysis reveals systematic and non-trivial misalignments, showing that violations typically arise through seemingly rational reasoning: appeals to efficiency, risk management, or scientific neutrality, rather than explicit rejection of rights. We further propose an LLM-as-a-Judge framework for automated evaluation using zero-shot and few-shot 

---

### [98] SparPR: Runtime KV-Cache Recovery for Resource-Constrained LLM Inference on Consumer Hardware

**链接**: https://arxiv.org/abs/2610.18140
**作者**: Jieyun Deng, Keming Hu, Yanghe Liu, and Li Feng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Running large language models (LLMs) on consumer hardware is bottlenecked by the key-value (KV) cache, which grows with every decoded token and quickly exhausts the memory and bandwidth of a single consumer GPU. We present SparPR (Sparse Partial Recomputation), a runtime KV-cache recovery mechanism that does not modify model weights and requires no offline training. SparPR couples three online decisions: Query-Aware key-block selection scores historical blocks against the current query; dynamic budget control estimates per-block copy and recompute costs to decide how many blocks to retain; and on-demand local recomputation with cost-aware fallback merges retained blocks into continuous spans and switches between sparse recomputation and full recovery according to a runtime cost comparison. Implemented on FlexGen/FlexLLMGen, SparPR is evaluated on a single consumer laptop (RTX 3070 Ti 8GB, Ryzen 9 6900HX, 16GB RAM). It cuts end-to-end latency by 31%, 52%, and 63% at 1k, 2k, and 4k promp

---

### [99] NeuroFilter: Activation-Based Guardrails for Privacy-Conscious LLM Agents

**链接**: https://arxiv.org/abs/2601.14660
**作者**: Saswat Das, Ferdinando Fioretto
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [100] Heterogeneous Agentic Coevolution

**链接**: https://arxiv.org/abs/2610.16078
**作者**: Wenqian Ye, Ziwei Guan, Zi Yang, Shivani Modi, Cici Cong Wu, Yunlong He 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in self-improving LLM agents have demonstrated the potential of AI systems that drive their own intelligence. However, many domain-specific applications rely on specialized foundation models that possess strong domain expertise but remain dependent on human-designed improvements. Extending recursive self-improvement to these models presents a key challenge: as a specialist improves, the strategies used to advance it must also adapt. To address this challenge, we propose Heterogeneous Agentic CoEvolution (HACE), a framework that jointly evolves specialized foundation models and LLM agents through reciprocal learning. HACE improves the specialist through supervised learning while training the agent with on-policy reinforced self-training, guided by verified performance gains on the current specialist. The agent's exploration, in turn, informs subsequent specialist training, enabling both models to adapt to each other's progress. To sustain this reciprocal learning, HACE f

---

### [101] Dissociating Answerability from Extraction in LLM Question Answering over Radiology Reports

**链接**: https://arxiv.org/abs/2610.17576
**作者**: Priyanshu Sinha and Kelsey McDonald
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Answering questions from radiology reports involves two decisions: whether the report contains an answer and which span gives it. A false answer presents an unsupported claim as fact; an over-abstention hides what the report says. Yet RadQA results are reported as a single F1 that merges both. We propose an evaluation method that separates them, reporting false-answer and over-abstention rates beside F1 and splitting F1 changes into extraction and answerability terms. We apply it to 13 LLMs on the RadQA test set, zero-shot and with three cumulative demonstration sets, the last adding an unanswerable example. Models with similar F1 differed more than twofold in false-answer rate. The unanswerable example changed when models answered, not how well they extracted: 12 of 13 models abstained more often, and three-quarters of the answers they withdrew had F1 $\geq$ 0.5. Within models, false answers showed no clear association with extraction quality, but acting on the decision itself helped:

---

### [102] Training LLMs for Multi-Agent Collaboration with Verifiable Information Rewards

**链接**: https://arxiv.org/abs/2610.17893
**作者**: Keru Chen, Sen Lin, Yingbin Liang, Nathaniel D. Bastian, Shaofeng Zou
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective collaboration among large language model (LLM) agents in multi-agent systems requires sharing relevant evidence, requesting missing information, and incorporating teammates' contributions into decisions. Training these behaviors is challenging because final task outcomes provide limited feedback on the value of individual messages. We introduce CoSIR (Collaboration via Surprisal-based Information Rewards), a post-training approach that uses a simple, verifiable environment to teach collaboration behaviors that generalize to more complex, unseen tasks. We propose a Bayesian evaluator that scores shared information by its reduction in team surprisal, defined as the sum of the negative log probabilities assigned to the correct option given each agent's available evidence. Requests are scored by the potential reduction in the same quantity if the requested information were truthfully provided. Separate rewards encourage agents to use the received information in their private choi

---

### [103] When Pleasing the User Compromises Care: AI Sycophancy in Caregiver-Mediated Healthcare

**链接**: https://arxiv.org/abs/2610.14360
**作者**: Priyadarsi Mishra, Arjun Beniwal, Ziyu Yi, Yu Ding, Sheng Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) alignment often assumes that the user interacting with a model is also the primary beneficiary of its behavior. Yet in many consequential settings, one person directs the system while another bears the consequences. We study this problem in caregiver-mediated healthcare, where parents, pet owners, and caregivers make decisions for children, animals, and older adults. We introduce an evidence-grounded benchmark spanning veterinary, pediatric, and older-adult care, and test whether AI advisors maintain appropriate care when users express clinically inferior preferences. Holding patient facts fixed, we vary stated care preferences and communication styles and evaluate both initial recommendations and multi-turn follow-up. Across frontier and open-weight models, inferior preferences substantially increase switching from appropriate to inappropriate care beyond neutral conversational drift and increase agreement with the requested action, while communication style

---

### [104] Just Respect the Semantics: Image-Token Compression via Pre-LLM Semantic Variable-Resolution Tokenization and In-LLM Relevance Pruning

**链接**: https://arxiv.org/abs/2610.18690
**作者**: Tianhao Fu, Austin Wang, Charles Chen, Roby Aldave-Garza, Victor Xie, Xiyue Jiao 等 (8 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image-token compression must reduce computation without hurting the semantics. We introduce Varest, guided by semantic fungibility: tokens within a coherent semantic region can be summarized coarsely, while object boundaries and literal text require finer distinctions. Object and text localizers guide variable-resolution merging, preserving spatial coverage and finer detail at boundaries and text. Learned [REL] registers then prune visual tokens after early decoder processing. Training across budgets enables one checkpoint per backbone. Across three backbones and 13 benchmarks, Varest outperforms 15 baselines in mean performance retention at every evaluated budget, retaining 86.10-92.33% of full-token performance with only 5.56% of the original layer-averaged image-token count.

---

### [105] When "Must" Becomes "Maybe": Erosion of Workflow Constraints in LLM Agent Handoffs

**链接**: https://arxiv.org/abs/2608.24569
**作者**: Yiheng Sun, Huifei Wang, Yancheng Zhu, Zhenyu Li, Zebin Zhao, Yifan Yuan
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] MemTrial: Learning When to Trust Memory in LLM Portfolio Agents

**链接**: https://arxiv.org/abs/2610.11732
**作者**: Guanghao Wu, Zhuo Cai, Shoujin Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Plans Fade Fast: Why Context Management Is Load-Bearing for LLM Agents

**链接**: https://arxiv.org/abs/2606.22953
**作者**: Aman Mehta, Anupam Datta
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Visible but Not Avoided: State-Dependent Re-Proposal of Rejected Candidates in Catalog-Based LLM Optimization Loops

**链接**: https://arxiv.org/abs/2610.15738
**作者**: Jianlin Chen, Wenhui Chen, Chi Man Vong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM optimization loops often show the proposer the candidates it has already tried and rejected, but leave it to the proposer to avoid them. We ask whether avoidance measured in a static probe predicts avoidance in the states an optimizer's own trajectory produces. In catalog-based loops where three open LLMs improve a GUI agent by naming one of 40 edits, a re-proposal is identified exactly by the edit's name. Clean base-state probes underpredict re-proposal in the proposers' own loops (macro-averaged loop-minus-probe rate 0.32 [0.27, 0.37]), and proposals of already evaluated harness-edit pairs consume 28-63% of valid proposer iterations. The two settings reject different edits: a probe's rejected edits are mostly ones the proposer did not choose, whereas a loop's are its own earlier choices, which remain preferred when the history is removed. Ordinary history lowers re-proposal for two proposers but raises it for the third, and the effects of failure evidence are model-specific. Stat

---

### [109] What We Talk About When We Talk About LLM Planning: Evidence for Two Distinct Planning Abilities

**链接**: https://arxiv.org/abs/2607.11197
**作者**: Sukai Huang, Chenyuan Zhang, Fucai Ke, Zhixi Cai, Naim Rastgoo, Gholamreza Haffari 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] GraphOPD: Graph-Augmented On-Policy Distillation for LLM Agents

**链接**: https://arxiv.org/abs/2610.08959
**作者**: Bohan Lin, Liyi Chen, Zhuoning Guo, Muyang Li, Qimeng Wang, Yan Gao 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [111] SPINE: Measuring LLM Sycophancy under Sustained Multi-Turn Pressure

**链接**: https://arxiv.org/abs/2609.09090
**作者**: Leyuan Tang, Kangda Wei, Tianyu Jiang, Ruihong Huang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] Process Advantage Signal Shaping: Advantage Construction for Process-Supervised Reinforcement Learning in LLM Reasoners

**链接**: https://arxiv.org/abs/2606.29296
**作者**: Chao Wang, Hongtao Tian, Tao Yang, Yunsheng Shi, Ting Yao, Wenbo Ding
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] Fan Out or Relay? Ownership-Aware Routing for LLM Agents Querying Siloed Tables

**链接**: https://arxiv.org/abs/2610.18157
**作者**: Zhexi Feng
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inside organizations, a question's data often sit with several owners, who query their own tables but never hand them over. An LLM coordinator can fan out, sending the question to every owner at once, or relay, querying owners in turn and reusing earlier rows. We show that neither is safe in advance, because data ownership decides which one is right. Across thirteen settings on PeopleJoin and BIRD with three model families, fan-out is more accurate in twelve on questions one owner can answer, yet answers at most 4.3% of those joining two owners' tables. The flip follows ownership, not query shape: on BIRD two-table joins, fan-out answers 32-44% when one owner holds both and 1-4% otherwise. Relay wins by conditioning on returned rows, and hiding them from an otherwise identical planner cuts two-owner accuracy from 23.2% to 5.1%. Since ownership is public, we propose Ownership-Aware Routing (OAR), which drafts a schema-only SQL query, counts the owners whose tables it joins, and routes t

---

### [114] Are LLM Agents Behaviorally Coherent? A Latent Profiling Approach for Social Simulation

**链接**: https://arxiv.org/abs/2509.03736
**作者**: James Mooney, Josef Woldense, Zheng Robert Jia, Shirley Anugrah Hayati, My Ha Nguyen, Vipul Raheja 等 (7 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] Spec-Harness: Assessing and Guiding LLM-Synthesized Formal Specifications Beyond Verifiability

**链接**: https://arxiv.org/abs/2604.00280
**作者**: Md Rakib Hossain Misu, Cristina V. Lopes, Iris Ma, Yuangang Li, Shuvendu Lahiri
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] OpenDGO: Benchmarking Multi-Agent Organizations Across Diverse Application Domains

**链接**: https://arxiv.org/abs/2610.17143
**作者**: Xunkai Li, Miao Zhang, Zekai Chen, Xuaner Chen, Yu liu, Rui Qian 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems are increasingly applied across diverse domains, yet different applications require different forms of agent organization. Existing studies typically adopt predefined organizations, such as Star, Chain, and Tree, or learn communication graphs to improve performance on specific tasks. However, these methods are largely designed and evaluated within a limited set of application domains, providing little understanding of whether an organization effective in one domain remains suitable for others with different collaboration requirements. We present \textbf{OpenDGO}, a controlled benchmark and analysis framework covering six real-world domains and three collaboration settings: Sequential Dependency, Parallel Decomposition, and Information Integration. Under matched tasks, agents, tools, and resource limits, OpenDGO compares fixed and learned organizations while separately examining communication graphs, role assignments, input assignment

---

### [117] LLM-as-Jev: LLMs Are Already Jev-Style Decision Models -- When and How to Fine-Tune Them

**链接**: https://arxiv.org/abs/2610.02076
**作者**: Yinheng Li, Justin Wagle
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] Which Metadata Matters for LLM Tool Selection in MCP? Evidence from Controlled Factor-Level Interventions

**链接**: https://arxiv.org/abs/2610.14334
**作者**: Xiaofan Li, Fengchun Qiao, Xing Gao
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In Model Context Protocol (MCP) systems, LLMs select tools from metadata rather than from their implementations. Names and descriptions summarize what a tool does, while the parameter schema specifies the fields a tool accepts and how they are organized. Our analysis of metadata for 367,174 MCP tools reveals substantial schema variation among functionally similar tools. Many of these tools share names and similar descriptions but expose different parameter schemas. This raises a key question: can parameter-schema differences influence tool selection before any call is made? We study this question through controlled metadata interventions across five LLMs and five tasks. Each comparison changes exactly one metadata factor (server name, tool name, description, or parameter schema) while keeping the others fixed. We balance tool positions and use conditional logistic regression to estimate position-adjusted effects. We find that: (1) parameter-schema changes produce the largest and most c

---

### [119] Delegating Earth science model calibration to knowledge-guided LLM agents

**链接**: https://arxiv.org/abs/2610.18378
**作者**: Zhanliang Zhu, Ziwei Li, Liujun Zhu, Yuchen Liu, Junliang Jin, Jianyun Zhang
**来源**: cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Applying process-based Earth science models to new sites and questions often requires expert calibration decisions. Reliable delegation to language-model agents must preserve scientific competence and reproducibility. Here we develop a general calibration harness (GCH) for end-to-end delegation from a calibration request to assessed results. Constrained by a knowledge infrastructure (KI) and a validation convention, agents define parameter domains, observation mappings and objectives, and generate model-specific code. GCH checks the formulations against the same declarations and freezes them before numerical search and assessment, which require no further agent judgement. Agent-authored workflows executed across six model families, with assessment identifying unmet criteria. In snow-model tests, five of five knowledge-guided specifications executed on the first attempt, compared with none of five given only the model name, achieving validation Nash-Sutcliffe efficiency (NSE) of 0.81-0.

---

### [120] Empowering Edge Agents: A Systematic Analysis of Edge-Cloud Collaboration in LLM Agent Execution

**链接**: https://arxiv.org/abs/2610.17816
**作者**: Pengcheng Huang, Zhenghao Liu, Shixin Ren, Shi Yu, Sijia Yao, Yukun Yan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Edge-cloud collaboration combines the lower inference overhead and greater data locality of edge-side execution with the stronger capabilities of cloud-hosted models. However, as LLM agents increasingly operate in long-horizon scenarios, cloud participation becomes interleaved throughout execution rather than a one-shot decision for each query. Such interleaved participation introduces trajectory-level effects that remain insufficiently understood. To address this gap, we introduce EC2-Bench, a benchmark for evaluating edge-cloud collaboration in long-horizon agent execution. It provides executable digital-workspace agent tasks and a unified evaluation framework covering task performance, resource usage, and privacy exposure. Using this benchmark, we empirically study diverse forms of edge-cloud collaboration. Our study reveals three findings. First, collaboration achieves a favorable balance among task performance, resource usage, and privacy exposure compared with edge-only and cloud

---

### [121] FinRED: An Expert-Guided Benchmark Generation and Evaluation Framework for Financial LLM Red-Teaming

**链接**: https://arxiv.org/abs/2606.19887
**作者**: Daeyoung Park, Chaeyun Kim, Junghwan Kim, Jinyoung Jeong, Eunji Song, Yongtaek Lim 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Handoff Curves: Initial Selection, Later Handoff, and Supervision Targets in Multi-turn LLM Routing

**链接**: https://arxiv.org/abs/2610.15993
**作者**: Daniel Matos, Lu Liu, Yanfeng Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how initial model selection, later handoff, and training targets affect success and cost in LLM tasks that span multiple turns. We compare several router architectures using handoff curves, which record task success and cost as the handoff step changes. Our dataset contains 34,204 complete executions of three Qwen models across BFCL, MultiWOZ, and $\tau$-retail, providing offline supervision for routing decisions. In our primary comparison, with Qwen3.5 35B-A3B as the starting model, allowing a later handoff does not establish an improvement in utility over initial selection on BFCL or MultiWOZ, and increases cost on BFCL across a range of cost weights. Changing the supervision targets improves router performance on both our dataset and TwinRouterBench. On our dataset, replacing noisy training success curves with monotone fits raises success by 0.2 to 4.1 percentage points at the same cost across the reported operating points. On TwinRouterBench, we construct targets that desc

---

### [123] ProAS: A Progress-Aware Advantage Shaping Framework for Multi-Turn Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.18683
**作者**: Bowen Ding, Mingda Wan, Yuhan Chen, Jiyao Yuan, Qi Zhu, Futing Wang 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has emerged as the primary paradigm for optimizing Large Language Model (LLM) agents, yet efficient critic-free algorithms (e.g., GRPO) suffer from a fundamental uniform credit assignment dilemma that broadcasts trajectory-level advantages equally to all actions. Our analysis reveals that this uniformity inherently reinforces structurally invalid actions in preferred trajectories and ignores the downstream cascading influence of early pivotal deviations in unpreferred ones. To resolve this without introducing critic overhead, we propose Progress-Aware Advantage Shaping (ProAS), a plug-and-play framework that leverages a dynamically evolving Agentic Reference Graph (ARG) to achieve fine-grained credit assignment via Masking Unreasonable Incentives (MUI) and Asymmetric Penalty Redistribution (APR). Extensive experiments across Qwen2.5-1.5B-Instruct and Qwen2.5-7B-Instruct demonstrate that ProAS universally elevates mainstream group-based baselines to new state

---

### [124] RetailAgent: Structured Adverse Timing in Self-Conditioned Multimodal LLM Trading Agents

**链接**: https://arxiv.org/abs/2608.28399
**作者**: Yupeng Zhang, Liuyuan Jiang, Hongyi Huang, Bingheng Li, Lisha Chen
**来源**: cs.AI q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] Beyond Unsafe Detection: Counterfactually Anchored Evidence Attribution for Multi-Turn LLM Safety Failures

**链接**: https://arxiv.org/abs/2609.27773
**作者**: Srinivasan Subramanian, Kazi Aminul Islam, Md. Abdullah Al Hafiz Khan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] RetroPlanner: Multi-Route Expansion and Multi-Objective Reasoning for LLM-Based Retrosynthesis Planning

**链接**: https://arxiv.org/abs/2610.16391
**作者**: Ye Rin Kim, Yongjun Jeong, Seongjun Yun, Hanbum Ko, Soohyun Oh, Sungbin Lim and Sungwoong Kim
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-step retrosynthesis planning is often considered solved once a route to purchasable starting materials is found, but such a route should also be practical in real-world chemistry. Recent LLM-based planners formulate this process as sequential decision-making over an AND-OR graph, yet typically expand a single molecule per turn and are optimized for solvability alone, leaving alternative routes uncompared across the multiple objectives that determine practicality before the search budget is committed. We introduce RetroPlanner, an LLM-based planner that jointly compares multiple routes to steer the search toward higher synthesizability, as measured by reaction plausibility, round-trip consistency, and starting-material price. RetroPlanner is trained to reason over chemical evidence: structural progress from the target molecule, bond changes and reaction classes, where candidate routes diverge from one another, and how they rank across multiple objectives. Experiments on multi-step

---

### [127] MoSAIC: Learning DAG Scheduling Heuristics from Optimal Schedules through Motif-Aware Recovery and LLM-Guided Reasoning

**链接**: https://arxiv.org/abs/2610.15205
**作者**: Shiva Ahir, Hashmath Shaik, Alex Doboli, Nadeem Yaseen, Simona Doboli
**来源**: cs.AR cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient task scheduling in heterogeneous computing systems remains a fundamental challenge in embedded and high-level synthesis flows. This paper presents MoSAIC (Motif-aware Scheduling with AI-driven Cognition), a learning-based framework that bridges the gap between exact and heuristic scheduling approaches for DAG-based applications. The system uses the reasoning capabilities of large language models (LLMs) to learn the relationships between DAG structures and scheduling priority functions. The framework first leverages the OR-Tools CP-SAT solver [4] to generate optimal schedules, which are then used to supervise the learning of compact priority-based scheduling functions through Bayesian Optimization. These learned heuristics capture relationships between scheduling decisions and structural graph features such as rank, depth, and fanout, enabling the construction of a reusable knowledge base across diverse DAG instances. Experimental results across synthetic graph families and re

---

### [128] Beyond Independent Values: Optimal Auctions with Correlated Valuations for LLM-Native Advertising

**链接**: https://arxiv.org/abs/2610.14646
**作者**: Shiman Sheng, Mingyu Guo
**来源**: cs.GT cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational assistants are becoming the place where people ask what to buy, and sponsored content is moving into their answers. Several advertisers then compete for one sponsored slot, and all of them read the same conversation, so their willingness to pay usually moves together. Existing auctions for LLM advertising treat these values as independent. We therefore present AffMyerson, an auction that captures this correlation and turns it into revenue. We model the advertisers' values given the conversation as a multivariate normal and turn the economic premise of positive dependence (affiliation) into a sign condition on the precision matrix. We design a neural parameterization whose every output satisfies it. We prove that every prior in this family yields a truthful, ex-post individually rational auction, so estimation error can cost revenue but never truthfulness. We derive the conditional virtual values in closed form. By the design of the prior, pricing an auction needs no matr

---

### [129] Refuses in Chat, Complies with Arms: LLM Refusal Does Not Survive Robot Control

**链接**: https://arxiv.org/abs/2610.14043
**作者**: Edward Sun, Christopher Leet, Sravanthi Machcha, Achyutha Menon, Tzu Kit Chan, Yuchen Cui 等 (7 人)
**来源**: cs.HC cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier language models reliably refuse to explain how to cause physical harm. We ask whether this refusal survives when the same models control a robot. We introduce RoboHarm, a physical AI safety benchmark of harmful robot instructions, and test seven frontier models on it. We hold each model fixed and vary only the interface, from text to Code as Policies to vision agents that command end-effector poses or joint angles. In a MuJoCo simulation twin of a bimanual YAM arm robot, refusal falls from 73% of text requests to 18-25% once the model controls the robot, even when it is told what the objects are. On the physical robot, six models with end-effector control refused 18% of 612 trials against 19% in sim, and three with joint control refused 41% of 252 against 31%. GPT-5.6 Sol refused every text request and none of its trials on the real robot. Case studies of the robot transcripts show that models miss the hazard, name it without inferring its consequences, or act despite recogniz

---

### [130] Understanding Negative Learning in Large Language Model Fine-tuning

**链接**: https://arxiv.org/abs/2512.00778
**作者**: Yue Wang and Qizhou Wang and Zizhuo Zhang and Gang Niu and Bo Han and Masashi Sugiyama
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] AuthGateBench: Benchmarking LLMs as Authorization Gate

**链接**: https://arxiv.org/abs/2610.16426
**作者**: Zhixiong Zhuang, Jin Jia, Zhiwei Shang, Ziyu Wang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated approval systems let coding agents execute high-risk actions with minimal human oversight by delegating the authorization decision to a classifier, typically a large language model (LLM). Such systems, adopted in tools like Claude Code and Codex, remain vulnerable to failure modes such as scope escalation, where the agent takes actions exceeding what the user authorized. Existing benchmarks focus mainly on malicious requests, evaluating refusal under an implicit policy. We introduce AuthGateBench, the first policy-guided benchmark for authorization gating under benign requests. We implement a novel pipeline where an LLM generates contrast pairs with identical action and trajectory but differing request, flipping the label between block and allow. This allows us to assess whether models reason over context rather than the action alone. We further examine whether auxiliary environment signals can help models make better decisions. The resulting benchmark comprises 1,400 instanc

---

### [132] Upstream Influence, Downstream Re-Anchoring in LLM Agent Chains

**链接**: https://arxiv.org/abs/2610.17723
**作者**: Chun-Yu Hsu, Lun-Wei Ku, Chung-Chi Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People act on evaluative judgments produced by LLM agents, and in multi-agent systems those judgments pass through several agents before reaching a person. We show that a workflow's information architecture---source access, handoff format, and which model reads the untrusted content---governs how much of a coordinated manipulation reaches the end. On 32 Taiwan~2025 recall cases, ten authentic Threads comments shown to one agent move its stance by $+0.171$ toward the injected position, and a mirrored set moves it the other way. Passing that judgment down a chain removes more than half of the shift by the third agent; keeping the comments in front of every agent sustains more of it. The reduction is not attrition in transit: each receiver discounts the inherited stance in proportion to how far it sits from its own reading of the evidence, returning to what that evidence implies for the case rather than to neutrality---consistent with partial re-anchoring. Handoff format is a second lever

---

### [133] ReguSim: Evaluating LLM Agent Rule Grounding in Financial Compliance

**链接**: https://arxiv.org/abs/2608.19974
**作者**: Yiyang Luo, Yihang Jiang, Qijun Xie, Liang Lan, Lin Willian Cong, Anyi Rao and Yunya Song
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Process Rewards for Outcome-Guided Reasoning Steps in LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2604.02341
**作者**: Mohammad Rezaei, Jens Lehmann, Sahar Vahdati
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] Probe and Skip: Self-Predictive Token Skipping for Efficient Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2601.13155
**作者**: Zimeng Wu, Donghao Wang, Chaozhe Jin, Jiaxin Chen, Yunhong Wang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] ECLIPTICA -- A Framework for Switchable LLM Alignment via CITA - Contrastive Instruction-Tuned Alignment

**链接**: https://arxiv.org/abs/2601.06157
**作者**: Kapil Wanaskar, Gaytri Jena, Vinija Jain, Aman Chadha, Amitava Das
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [137] Vision-Predictor-Action: Towards Efficient Embodied AI via Neuro-Symbolic JEPA Predictors

**链接**: https://arxiv.org/abs/2610.15556
**作者**: Yeonseok Lee
**来源**: cs.LO cs.LG cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language-Action (VLA) models commonly generate robot actions token by token through Large Language Model (LLM) decoders, causing inference latency to grow with action sequence length and limiting closed-loop control frequency. We present Goal-Conditioned Vision-Predictor-Action (VPA), which replaces autoregressive decoders with a lightweight latent control loop. A shared vision encoder and a frozen text encoder embed observations, goal images, and instructions; a neuro-symbolic selector chooses a discrete skill; a Joint-Embedding Predictive Architecture (JEPA) predictor forecasts the next latent state; and a flow-matching solver generates an entire action chunk in a few integration steps, so that sequential network evaluations per decision step do not depend on the action horizon. We analyze inference complexity, regularization against representation collapse, and conditions under which latent sub-goal thresholding limits error accumulation across task phases. As an initial proo

---

### [138] Semantics as a Shield: Label Disguise Defense (LDD) against Prompt Injection in LLM Sentiment Classification

**链接**: https://arxiv.org/abs/2511.21752
**作者**: Yanxi Li, Ruocheng Shan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] MENTOR: Procedural Shielding of Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2610.17039
**作者**: Ashwani Anand, Ivi Chatzi, Ritam Raha, Anne-Kathrin Schmuck
**来源**: cs.CL cs.LG cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents are increasingly used to automate workflows governed by procedural manuals, such as company rules for booking travel or procuring hardware. These manuals are written in natural language for humans and describe general requirements over such complex workflows. Ensuring compliance of LLM agents with these manuals is difficult, and state-of-the-art techniques use either LLM judges or manually written rules to forbid problematic tool-calls locally at runtime. This is insufficient because (i) only blocking tool calls keeps the agent clueless about how to make correct progress towards fulfilling its task, and (ii) can lead to overly conservative behavior of the agent, as tool calls might only be problematic in certain contexts. To overcome these challenges, we introduce MENTOR, which (i) additionally provides guidance for the agent to make procedural-compliant progress on the task, and (ii) ensures that this compliance is context-aware. We achieve these goals by buildin

---

### [140] Looking Complete Is Not Being Grounded: Evaluating LLM Sitreps Against Human-Authored Situation Reports

**链接**: https://arxiv.org/abs/2610.18762
**作者**: Sachin Kumar
**来源**: cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation for automatic crisis reporting should measure what practitioners need, not what is convenient to compare. Through LLM-assisted, author-approved content analysis, we derive a 15-slot information schema from professional humanitarian situation reports using qualitative content analysis, then evaluate 121 human and 261 LLM-generated reports across five disasters and three hazard types. Under google/gemini-3.7-flash on Cyclone Idai, the best machine arm is nominally above the empirical human ceiling (0.827 vs. 0.821), but the difference is statistically indistinguishable from zero (95\% bootstrap CI $[-.049,.059]$; permutation $p=.852$), and the ordering does not replicate under openai/gpt-5.6-luna. On a blind 100-item Idai sample, the author agrees with the Gemini judge at 0.910 accuracy and unweighted Cohen's $\kappa=.799$. All four judges clear the plan's raw-agreement criterion of .7; only Gemini reaches .7 on chance-corrected $\kappa$. Across the three primary events, machi

---

### [141] From Spectra to Joint Schedules in LLM Pre-training: 3+3(+2) Scaling-Law Regimes

**链接**: https://arxiv.org/abs/2609.40148
**作者**: Yichen Wang, Fanghui Liu, Yudong Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [142] LACRM: LLM-Guided Mining of Directed Advertiser Competition Relationships in E-Commerce Advertising

**链接**: https://arxiv.org/abs/2610.13959
**作者**: Xiang Shi, Yitian Kou, Bing Li, Shengsheng Niu, Chun Gan, Linghui Meng 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In e-commerce advertising, ad platforms typically fail to model the externalities among advertisers when making optimization decisions: an advertiser's actual performance is largely shaped by rivals competing for the same users; these rivals typically operate in overlapping product categories and at comparable budget scales. However, capturing this rivalry as an explicit, reusable signal is challenging because it is directed, multi-faceted, and partially observable. Existing paradigms such as interaction graphs, taxonomy rules, and single-embedding models do not fully capture these properties. In this paper, we propose LACRM (LLM-driven Advertiser Competition Relationship Mining), a novel framework that constructs directed competition graphs with continuous edge intensities via a three-stage pipeline. LACRM moves beyond symmetric similarity through LLM-driven role-separated profiling, which enables asymmetric multi-route retrieval to uncover both realized and latent rivals. The framewo

---

### [143] An LLM-powered Agentic Recommendation System for Connected TV Content Discovery

**链接**: https://arxiv.org/abs/2607.09988
**作者**: Lei Shi, Di Wang, Harry Tran, Helsing Xu, Yuchen Lu, Dhara Ghodasara 等 (10 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [144] PersonaFactor: Preference Factors with Dynamic Selection for LLM Personalization

**链接**: https://arxiv.org/abs/2610.16372
**作者**: Hang Su, Zequn Liu, Jianghan Chao, Qiuyu Tian, Xuesong Lu, and Yingce Xia
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although users may express different personalization needs across tasks, these task-specific behaviors can reflect shared underlying preference mechanisms. Existing LLM personalization methods often focus on surface-level interactions or undifferentiated histories, overlooking the shared mechanisms underlying these behaviors. We introduce PersonaFactors, a framework that distills reusable and interpretable personalization factors from heterogeneous user interactions. We construct a library of thirteen PersonaFactors by extracting evidence-grounded rationales and clustering recurring patterns across tasks, and develop a dynamic factor-guided generation framework that selects factors relevant to each user's history and current request. Across four personalization benchmarks and four backbone models, Dynamic PersonaFactor achieves the best score on every reported metric. Representation analyses further show that PersonaFactors and user history induce partially overlapping low-dimensional 

---

### [145] BSIPipe: Bidirectional Sequence-Level Interleaved Pipeline Parallelism for Long-Sequence Large Language Model Training

**链接**: https://arxiv.org/abs/2610.14935
**作者**: Yuzhou Ni, Ling Chen
**来源**: cs.LG cs.DC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pipeline parallelism has become a critical technique for training large language models. To address the throughput limitation of existing sequence-level methods that schedule subsequences unidirectionally, we propose bidirectional sequence-level interleaved pipeline parallelism (BSIPipe), which co-schedules two opposing V-shaped interleaved pipelines at the subsequence level. To bound the activation accumulation from subsequence scaling, BSIPipe introduces a basic-unit concatenation mechanism that keeps activation memory invariant to the subsequence count. To eliminate communication deadlock risk from bidirectional scheduling, BSIPipe employs a communication optimization strategy that combines topology-aware device mapping with communication-computation overlap. In addition, BSIPipe composes with tensor parallelism to overcome the memory limitation of single-dimensional parallelism, neutralizing its bidirectional memory overhead while maintaining throughput. Experiments on GPT and LLaM

---

### [146] Stdlib or Third-Party? Empirical Performance and Correctness of LLM-Assisted Zero-Dependency Python Libraries

**链接**: https://arxiv.org/abs/2605.21405
**作者**: Peng Ding and Rick Stevens
**来源**: cs.SE cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [147] Many Steps into One: Reasoning Contraction and the Limits of Safe Memory Reuse for LLM Agents

**链接**: https://arxiv.org/abs/2610.17544
**作者**: Jianghong Zhou, Hao Rong, Chen Lin, Daoan Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Thought templates, skill libraries, agent memories and caches turn many reasoning steps into one. We call this reasoning contraction. A contracted memory saves reasoning steps and errors until its facts change, then quietly answers wrong. Most systems trust memories by counting successes and failures. We prove that such counters are badly tuned change detectors: a symmetric counter notices a partial change only after a power of its false-alarm horizon, and an unclipped one may never notice it. On five LLMs answering multi-hop questions over edited facts, ExpeL- and ACE-style counters serve 7.0-13.5x more stale answers than certified memories given the same information, and on code tasks with an exact verifier 35-73x more. Safety also has a price. When facts change and each memory is judged only by its own verified outcomes, one number, the certification load, sets how much reasoning any safe memory can skip, and under Zipf demand it yields a scaling law. Our recipe weighs each memory's

---

### [148] EPOCH: Coverage-Aware Evolution with Experiential Preference Optimization for LLM-based Automated Heuristic Design

**链接**: https://arxiv.org/abs/2610.17379
**作者**: Oguzhan Gungordu, Ayse Tursucular, Siheng Xiong, Faramarz Fekri
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based automated heuristic design (AHD) discovers heuristics for combinatorial optimization problems (COPs), where an LLM generates candidates in an evolutionary search. Existing frameworks freeze the generator or fine-tune it on a scalar fitness signal hiding which instances each heuristic covers. Reflection-based frameworks improve heuristics with natural-language feedback, but it stays in the prompt and never reaches the generator's weights. We propose EPOCH, which makes instance coverage the objective of the evolutionary search and fine-tunes the generator to internalize reflection. Parent selection, operator allocation, and stagnation recovery all optimize how well the heuristics jointly cover the training instances, so the search returns a complementary heuristic ensemble. The generator learns from its own search by experiential preference optimization. A teacher LLM returns a natural-language insight on the generated heuristics, and the generator produces new heuristics with 

---

### [149] LLM Persona Unlearning

**链接**: https://arxiv.org/abs/2609.39882
**作者**: Kemou Li, Zhuan Shi, Qizhou Wang, Fengpeng Li, Negar Rostamzadeh, Golnoosh Farnadi 等 (7 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [150] How Much Can Repeated Running Buy? A Measured Variance Ceiling for LLM Code Evaluation

**链接**: https://arxiv.org/abs/2606.00920
**作者**: Yongxi Zhou, Lai Yun Choi, Jiaxi Wen, Wenbo Ye, Junwei Yao
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [151] PAG-Agent: Zero-Shot Personalized Music Album Generation via Aesthetic Profile Distillation

**链接**: https://arxiv.org/abs/2610.14508
**作者**: Yifeng Mao, Ziye Wang, Yutong Shen, Feiran Liu, Wenjuan Han
**来源**: cs.MM cs.SD
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Music Models (LMMs) can synthesize high-fidelity audio and support increasingly flexible prompt control, yet modeling the subjective preferences of an individual listener remains underexplored. We present PAG-Agent, a zero-shot multimodal framework that uses an explicit Personal Aesthetic Profile to bridge user preference inference and music generation control. A multimodal LLM distills favorite-song audio and contextual user information into this structured representation, which a planning LLM translates into generation instructions for existing music synthesizers. We further introduce PA-Eval, which evaluates personalization through the Aesthetic Consistency Score (ACS) for target-user alignment and the Aesthetic Specificity Index (ASI) for cross-user specificity. Experiments with Personal-100 on multiple MLLM and music-generation backbones show consistent improvements over generic and direct conditioning. A 50-participant follow-up study further shows a correlation $r=0.64$ be

---

### [152] Do you "see" what I "see"? A Multi-panel Visual Question Answer Dataset for Large Language Model Chart Analysis

**链接**: https://arxiv.org/abs/2610.14173
**作者**: Daniel J. Evans, J. P. Naiman, JooYoung Seo, J. Stephen Downie
**来源**: cs.DL cs.AI cs.IR
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Digital libraries increasingly host scientific publications whose figures encode primary research findings, yet making this visual content searchable, accessible, and reusable remains an open challenge. Large language and multimodal models (LLMs/LMMs) provide the possibility to automate many figure parsing tasks such as determining data trends or extracting data from plots. In this work, we consider if these models can reliably support task-oriented visual data analysis when presented with synthetic, but realistic, scientific figures that contain multiple charts. Our Visual Question Answering (VQA) process scaffolds our tasks along a four-level description model from basic conceptual answers to interpretive and analytical understanding. Additionally, we outline our process for synthetically generating our single and multi-panel (charts in which there are multiple panels present) plots and testing the data with various LMMs using quantitative analysis. In general, we find LMMs become le

---

### [153] Configuring RAG Systems: What Breaks, Where Originates, and How to Fix

**链接**: https://arxiv.org/abs/2610.18567
**作者**: Liangyu Chen, Youpeng Ma, Yulong Ye, Zezhen Xiang and Tao Chen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) has emerged as a dominant paradigm for improving Large Language Model (LLM) by intertwining it with other components, such as a vector/graph database. Therefore, the resulting RAG systems are often highly configurable, under which a non-trivial amount of failures are related to the configurations. However, there remains a lack of systematic understanding regarding the configuration issues for RAG systems. To bridge this gap, in this paper, we conduct the first large-scale empirical study of 654 real-world configuration issues collected from 10 diverse RAG systems. Drawing on this, we provide a complete categorization of the symptoms, root causes, relevant stages, and fix patterns of configuration issues for RAG systems, as well as several new observations. Our findings not only reveal the characteristics of configuration issues, but also strongly link them to the unique pipeline stages of RAG, e.g., we found that most symptoms can be observed at the

---

### [154] ProtoArena: Can AI Agents Discover and Exploit Real-World Cross-Component Protocol Vulnerabilities?

**链接**: https://arxiv.org/abs/2610.17837
**作者**: Fasheng Miao, Zhaoyu Hu, Xiang Li, Changqing An, Jiutian Zeng, Longtao Huang 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly used for vulnerability analysis, yet existing benchmarks provide limited coverage of exploitation that depends on interactions among network protocol components. Such vulnerabilities arise from inconsistencies in message interpretation, timing, state, or trust assumptions across participants. We introduce ProtoArena, a black-box, multi-component, dynamic benchmark with 80 cross-component vulnerability-exploitation environments spanning 11 protocol and application domains and 7 attack categories. Tasks are primarily informed by published protocol-attack mechanisms. Agents interact with running systems through scoped interfaces to achieve security-effect objectives without target source code. Three information levels assess guided reproduction, exploitation with mechanism and topology context, and effect-directed black-box exploration. A hybrid verifier combines rule-based checks with LLM review of independently collected traffic and log

---

### [155] The interpreter as developer: An autoethnographic design study of building a computer-assisted interpreting tool through human-LLM co-creation

**链接**: https://arxiv.org/abs/2610.16460
**作者**: Zeming Zhao (College of Foreign Languages, Capital Normal University, Beijing, China)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-time AI captioning now serves audiences at multilingual events, yet computer-assisted interpreting (CAI) tools are still built for interpreters, rarely by them. This article reports an autoethnographic design study in which a professional interpreter with no programming training built a local-first CAI system through expert-led 'vibe coding', co-creating with an LLM architect and a coding agent. Analysis of the complete development dialogues shows how tacit professional knowledge, from segmentation to booth infrastructure, was externalized into design after generic defaults failed in use. In a demanding public scientific event, three mechanisms of in-booth appropriation emerge under a firmly human-led division of labor; telemetry from a first fully instrumented assignment shows a fully local chain sustaining a median translation latency of 0.94 s across 971 utterances. The case is read as lead-user innovation newly enabled by generative AI, with implications for the technological 

---

### [156] Auditing a KB Elicitation of Frontier LLM Knowledge: A Multi-dimensional Analysis of GPTKB v1.5

**链接**: https://arxiv.org/abs/2510.07024
**作者**: Shrestha Ghosh, Luca Giordano, Yujia Hu, Tuan-Phong Nguyen, Simon Razniewski
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [157] XL-SafetyBench: A Country-Grounded Cross-Cultural Benchmark for LLM Safety and Cultural Sensitivity

**链接**: https://arxiv.org/abs/2605.05662
**作者**: Dasol Choi, Eugenia Kim, Jaewon Noh, Sang Seo, Eunmi Kim, Myunggyo Oh 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [158] Back-Translation Still Matters: Leveraging Monolingual Data for Low-Resource Machine Translation with LLMs

**链接**: https://arxiv.org/abs/2610.18818
**作者**: Divyanshu Bathla, Parag Singla, Jitin Singla
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pre-trained Large Language Model (LLMs) are effective on many tasks in zero-shot and few-shot settings. For machine translation of low-resource languages, the obvious options are few-shot prompting and fine-tuning on a small parallel set. We ask: what if moderate amounts of low-resource monolingual data are also available? We argue that, rather than continued pretraining, a more effective use of this data is the pre-LLM era technique of back-translation (BT). The current fine-tuned LLM translates monolingual sentences in each language, and the resulting pairs train it in the reverse direction. Updates on the parallel set are interleaved for stable learning. With 1K parallel pairs on Odia and Swahili, BT beats continued pretraining into the low-resource language by 7.7 to 16.4 XCOMET-XXL points in domain. With beam-decoded intermediate translations, it also beats a model with 10 time more parallel data. In-context examples retrieved from the parallel data further improve BT. We also ana

---

### [159] TagBO: LLM-Driven Task-Aware Graph Bayesian Optimization for Scientific Discovery

**链接**: https://arxiv.org/abs/2610.14626
**作者**: Xinzhe Yuan, Zimu Zeng, Zhuo Chen, Jianshu Zhang, Jinzong Dong, Jingyi Chen 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mixed-variable optimization in scientific discovery often requires exploring large combinatorial spaces under costly experimental evaluations, making sample?efficient Bayesian optimization (BO) essential. However, existing BO methods typ?ically rely on structural descriptors to define similarity among categorical variables, implicitly assuming that structural similarity reflects similarity in task performance. In scientific optimization, this assumption is often violated, leading to surrogate representations that are poorly aligned with the optimization objective. To address this limitation, we propose TagBO (Task-aware Graph Bayesian Optimization), a method that integrates LLM-derived relational priors with descriptor-based struc?tural information for mixed-variable Bayesian optimization. Rather than directly using LLM outputs as predictive scores, TagBO treats LLM outputs as a potentially noisy source of task-aware relational priors and extracts coarse ordinal relational signals from

---

### [160] SkillFusion: Towards Reliable Multi-Skill Composition for LLM Agents

**链接**: https://arxiv.org/abs/2610.15481
**作者**: Enhao Huang, Xinye Zhao, Yiming Li, Bingrun Yang, Nanjun Zhou, Chunshu Xia 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Independently authored skills can impose incompatible requirements, competing preferences, and redundant instructions when jointly loaded by an LLM agent. We propose SkillFusion, an offline compiler that reconciles these interactions into a reusable merged skill. Its central idea is to make composition decisions explicit through typed, scoped constraints linked to their source directives. A type-scope gate selects candidate interactions, while selective fallback revisits pairs potentially missed by structural pruning. A classifier identifies interaction types, and an adversarial verifier re-examines uncertain judgments. The resolver applies conditional routing or explicit priorities to hard conflicts, verified abstraction to soft conflicts, and deduplication to redundant instructions. Source-linked checks guide synthesis and compression, and metadata synthesis supports discovery of the merged skill. The resulting artifact retains associated scripts and resources and can be reused acros

---

### [161] Decoupling Search from Reasoning: A Vendor-Agnostic Grounding Architecture for LLM Agents

**链接**: https://arxiv.org/abs/2606.18947
**作者**: Emmanuel Aboah Boateng, Kyle MacDonald, Amardeep Kumar, Siddharth Kodwani, Sudeep Das
**来源**: cs.AI cs.CL cs.IR cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [162] Auditing LLM Program Search for Bermudan Stopping with Primal--Dual Certificates

**链接**: https://arxiv.org/abs/2610.14063
**作者**: Yuhua Qian
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM program-search agents are usually judged by the score that drives their search. We study LLM-driven search over Python exercise policies for Bermudan options, an optimal stopping problem where a trusted evaluator owns the simulation and a dual upper bound~$U$. For any policy, $0 \le V^\star - L_\pi \le U - L_\pi$; we report Monte Carlo estimates of both bounds with their sampling error. We audit 24 generation attempts from two pipelines, a six-pair feedback-representation ablation, and a holdout evaluated after selection was frozen. No selected generated program improves on Ridge LSMC consistently or by more than Monte Carlo uncertainty; holdout gap scores lie within $0.002$ of it. On six one-dimensional puts, a high-precision binomial reference places Ridge within Monte Carlo noise of optimal and attributes 99\% of the estimated gap to dual-bound looseness, so this dual audits validity but cannot certify progress at the search's scale. Structured memory showed no benefit over scor

---

### [163] MFG: Multi-turn Feedback Guided Molecular Optimization

**链接**: https://arxiv.org/abs/2610.18851
**作者**: Trieu Nguyen, Frazier N. Baker, Ruoxi Gao, Daniel Adu-Ampratwum, Xia Ning
**来源**: cs.AI cs.LG q-bio.QM
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-objective molecular optimization is a critical process in drug discovery that aims to modify a given molecule to simultaneously improve multiple properties while maintaining a similar overall structure. This process often requires iterative modifications guided by computational or experimental feedback. Recent large language model (LLM)-based methods have begun to explore this iterative approach; however, these methods are not explicitly trained to leverage such feedback, while existing approaches primarily focus on single-turn molecular optimization. To address this gap, we introduce Multi-turn Feedback Guided (MFG) molecular optimization, a reinforcement learning framework that trains an LLM to progressively optimize molecules using feedback from previous turns. MFG introduces a feedback vector capturing both property improvements and source molecule similarity, alongside a feedback-aligned reward function that promotes progressive improvement across turns. We apply MFG over $\

---

### [164] How Narrative Wrapping Affects LLM Refusal: A Cross-Language Benchmark and Defense

**链接**: https://arxiv.org/abs/2610.11005
**作者**: Zhankai Ye, Yanning Wang, Yukai Jin, Bo Mei, Fangyi Li, Wei Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] Lost in Implicit Routing: How LLM Agents Fail to Load Relevant Skills at Scale

**链接**: https://arxiv.org/abs/2610.18522
**作者**: Jinlin Liu, Wei Chen, Xiaojin Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reusable skills let LLM agents load task-specific instructions on demand, but they make execution depend on implicit routing over skill metadata. We test whether this design scales by holding SkillsBench tasks and their golden skills fixed while adding irrelevant skills. We find skill routing collapse: agents increasingly load fewer or no skills, even though the relevant skills remain available. With 1,000 irrelevant skills, loaded-skill recall falls from 73.6% to 27.4% and the zero-load rate rises from 9.3% to 51.6%, whereas explicit selection from the same library retains 73.9% recall. Loading other skills, including plausible alternatives to golden skills, is too rare to explain this decline. Masking only the descriptions of irrelevant skills largely restores skill loading, yet with the metadata intact, explicitly asking agents to plan skill use still yields lower recall than preselection. These findings point to semantic interference from descriptions and instruction interference w

---

### [166] UZHCL_for_the_win at Touche: Encoder Fine-Tuning, Synthetic Augmentation, and an Underpowered Encoder-LLM Comparison

**链接**: https://arxiv.org/abs/2610.17077
**作者**: Psychias Stylianos
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online discussions on platforms like Reddit are a productive testbed for fallacy detection: short texts, broad topical range, and the full inventory of informal fallacies. The Touche 2026 lab at CLEF formalises this as a shared task on a Reddit-derived corpus that combines fallacy detection with argument-scheme classification. This paper describes our participation in all three subtasks (ST1 binary fallacy detection, ST2 eight-way fallacy classification, ST3 four-way argument-scheme classification) and both evaluation tracks. Our submitted systems are fine-tuned RoBERTa-large encoders with task-specific heads, augmented with a small batch of LLM-generated synthetic contrastive pairs; for ST2 and ST3 on the enhanced track we additionally added confidence-filtered pseudo-labelled examples from the unlabelled pool. A wider backbone comparison spanning additional encoders (DeBERTa-v3, ModernBERT) and an LLM track (four Qwen variants from 3B to 32B, zero-shot through CoT-LoRA) showed no val

---

### [167] LLM-Based Multi-Agent Collaboration for Constrained Multi-Objective Container Placement

**链接**: https://arxiv.org/abs/2610.07030
**作者**: Suvarthi Sarkar, Abhishek Hazra, Akshat Mittal, Aryabartta Sahu
**来源**: cs.DC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Container placement in data centers must simultaneously minimize power consumption and maximize affinity preferences, while satisfying multi-resource capacity and anti-affinity constraints. Traditional approaches typically rely on fixed rules, which lack adaptability to dynamic cluster states and are difficult to extend for adaptive decision-making. On the other hand, meta-heuristic methods, although more flexible, are often computationally expensive, slower and prone to getting trapped in local optima. In this work, we propose an adaptive and efficient approach based on an LLM-driven multi-agent collaboration framework, where four specialized agents operate in a closed-loop ReAct cycle at each placement step. A Power Consumption Agent and an Affinity Agent debate over competing objectives, while a Placement Agent resolves conflicts using Tolerance-Gated Arbitration (TGA). A Rearrangement Agent further refines decisions through the Monotone Improvement Rule (MIR) in a post-placement re

---

### [168] StructZO: Structured Zeroth-Order Optimization for Memory-Efficient LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.16451
**作者**: Xuanlin Yang, Jia Li, Zhouchen Lin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuning large language models at scale is increasingly limited by the memory cost of backpropagation. Zeroth-Order (ZO) optimizers reduce this burden by relying only on forward function evaluations, but they still exhibit a substantial performance gap to first-order (FO) optimizers such as Adam. We argue that this gap does not arise solely from the absence of explicit gradients: FO fine-tuning also benefits from informative low-rank optimization geometry, large-scale signal aggregation, and well-conditioned update directions. Motivated by this, we introduce StructZO, a structured Zeroth-Order optimization framework for memory-efficient LLM fine-tuning. StructZO performs large-query ZO estimation within an activation-induced informative subspace and applies spectral control to the resulting reduced-space update before mapping it back to the original parameters. This lets ZO aggregate useful directional signals in a compact, geometry-aware space while avoiding the activation and opti

---

### [169] Scaling Multi-Agent Intelligence with Substrate-Centric Coordination

**链接**: https://arxiv.org/abs/2610.16120
**作者**: Zhenting Qi, Zhuokai Zhao, Rulin Shao, Kerem Oktar, Zhiyuan Yao, Himabindu Lakkaraju 等 (10 人)
**来源**: cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing large language model (LLM) based multi-agent systems have been shown to scale poorly, and we identify three problems: reading burden that grows with the group, useful information diluted by shared work of unknown quality, and fragility to failed agents. We argue that the problems are largely due to agent-centric designs: the coordination structure is wired into fixed workflows, central coordinators, or peer-to-peer messaging, and recent blackboard-style methods that move the coordination into a shared medium relieve only the last problem. To close the gaps, we build ScaleMAS, where asynchronous agents interact with a shared datastore of linked messages via three operations: publishing messages with optional references to earlier ones that they build on, searching for messages by content, and visiting messages by address. Search returns at most $k$ messages, so an agent's read stays bounded at any group size; results are ranked by relevance and by how often they are cited, whic

---

### [170] STAIR (STructure Aware Information Retriever): A novel dataset and LLM based retriever for document structure augmentation

**链接**: https://arxiv.org/abs/2609.03874
**作者**: Vineet Kumar, Meghanadh Pulivarthi, vishwajeet kumar, Jaydeep Sen, Riyaz Ahmad Bhat, Sachindra Joshi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] TLA-Verus: Generating and Solving Temporal Proof Obligations with LLM Agents

**链接**: https://arxiv.org/abs/2610.14923
**作者**: Kseniia Strelbytska, Bal\'azs Szil\'agyi, Anna M\'esz\'aros, Ferenc Husz\'ar
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The TLA+ (temporal logic of actions) formal specification toolkit has seen widespread adoption in modeling modern distributed software systems including databases, storage systems, ledgers and coordination protocols. This popularity is despite its two significant limitations for software verification: Firstly, TLA+ offers no way to detect drift between software implementation and mathematical specification; secondly, TLC and TLAPS cannot provide satisfactory proofs of arbitrary temporal logic properties. We take a step towards addressing these shortcomings by translating TLA+ specifications into Verus, an auto-active verifier built for Rust, via both a deterministic transpiler and an agentic translator. We demonstrate that our LLM-based pipeline is able to generate proof obligations from TLA+ specifications at scale, and to produce fully machine checkable proofs of both safety and liveness properties. Since temporal logic reasoning in Verus is a largely new task for LLMs, our work yiel

---

### [172] FleetPilot: Fine-Grained Steering Empowers Real-World LLM Personalization

**链接**: https://arxiv.org/abs/2610.14970
**作者**: Kounianhua Du, Jianxing Liu, Kangning Zhang, Wenxiang Jiao, Yuan Lu, Jiarui Jin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid evolution of large language models (LLMs), there is an increasing demand for effective personalization techniques that can adapt model behavior to individual user preferences. Personalized LLMs must infer a user's query-dependent preferences from limited, heterogeneous, and evolving interaction histories. Existing approaches rely primarily on in-context personalization, parametric adaptation, or personalized reward modeling, but respectively incur recurring costs in context management, model optimization and deployment, or multi-candidate generation and scoring. These limitations become particularly restrictive when user observations are sparse and the preference evidence relevant to each query varies across contexts and over time. To address these challenges, we propose \modelname, a fine-grained and instance-tailored steering framework that dynamically generates sample-level interference vectors from user data and injects them into the model's forward pass for personal

---

### [173] Pin It on Anyone: Certified Targeted Displacement of Multi-Bit LLM Watermarks Without the Key

**链接**: https://arxiv.org/abs/2610.18359
**作者**: Pawe{\l} Batorski, Przemys{\l}aw Spurek, Paul Swoboda
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-bit watermarking embeds a message, typically an account identifier, into LLM output so that harmful text can be traced to its origin. We show an attack technique that allows to alter the watermarking message. This allows to, for example, exchange the embedded account ID to an arbitrary different one. The attacker mainly needs access to a few accounts for generating LLM output and model logits, but crucially not the secret key used to watermark. The attacker then rewrites the text, keeping its meaning, so that the watermarking message decoder recovers the watermarking message embedded by the attacker. We are, to our knowledge, the first to propose such an attack, which we call a targeted displacement. Theoretically, we present upper and lower bounds on the probability of our attack succeeding. This bound depends on the number of accounts the attacker has access to, the length of the message and some characteristics of the given text. Our attack can succeed whenever we can bound th

---

### [174] LLM-BabyBench: Can Language Models Plan in Worlds They Can Simulate?

**链接**: https://arxiv.org/abs/2505.12135
**作者**: Idriss Malek, Omar Choukrani, Daniil Orel, Anh Duy Le Dinh, Zhuohan Xie, Zangir Iklassov 等 (8 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [175] Degrees of Freedom in Multi-Agent Coordination: Between Centralized and Decentralized Regimes

**链接**: https://arxiv.org/abs/2610.17751
**作者**: Yiqing Peng, Hehai Lin, Zixuan Wang, Dongyi Zhang, Zhengjie Zhu, Yi Han 等 (10 人)
**来源**: cs.MA cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) are commonly organized around two coordination regimes. Centralized coordination provides explicit control but can create a bottleneck at a single coordination locus, whereas decentralized coordination offers local autonomy but must achieve effective collaboration through distributed decisions and experience. These trade-offs motivate a systematic study of the space between the two regimes. We introduce Degrees of Freedom (DoF), a continuous configuration framework that quantifies the size of the decision space delegated to downstream agents. DoF controls the granularity of delegated work and the target probability that each task unit is assigned to the branches. Its endpoints recover the two coordination regimes. Across multiple task domains, DoF reveals a hierarchy of organizational effects. Delegated granularity and within-regime routing produce structured but bounded profile reallocations, whereas task domain and retained e

---

### [176] SchemaWeaver: Accelerating On-Device Mobile Agentic AI via Schema-Guided Parallel LLM Decoding

**链接**: https://arxiv.org/abs/2610.17436
**作者**: Boyuan Yang, Wei Gao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) on mobile devices can act as agents that call external software tools to complete complex tasks, but the major challenge of supporting on-device mobile agentic AI with LLMs is the long latency of LLM tool calling on mobile devices. In particular, the decode phase is the main contributor of such long latency, but is hard to speed up on mobile processors as it is bound by memory bandwidth rather than compute power. To address this limitation, in this paper we present SchemaWeaver, a new on-device mobile agentic AI technique that enforces schema-guided parallel decoding in the decode phase of LLM tool calling, to reduce its latency by producing multiple tokens in each decode pass. SchemaWeaver can be generically applied to the LLM inference engine on mobile devices without involving any training efforts or changes on LLMs, and our experiment results on major mobile SoCs and LLM families show that SchemaWeaver can reduce the LLM tool calling latency by up to 3.

---

### [177] Uncovering Robustness Weaknesses in LLM Agents via Persona Evolution with Task-Integrity Constraints

**链接**: https://arxiv.org/abs/2610.16155
**作者**: Yutao Xie, Jingbo Yang, Guanyu Yao, Xiaoyu Yang, Duo Ding, Shiyu Chang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interactive-agent evaluations commonly rely on standardized LLM-based user simulators that exhibit broadly cooperative behavior, potentially overlooking failures that arise under diverse but realistic user interactions. This can lead to overly optimistic estimates of agent robustness and provide limited failure signals for training agents that generalize across users. Existing approaches largely rely on predefined user behaviors, which may miss agent- or domain-specific weaknesses, while failure-oriented search can reduce task success by invalidating the underlying task rather than exposing genuine robustness failures. To fill this gap, we introduce TIPER, a task-integrity-preserving persona evolution method that automatically discovers agent-specific user policies exposing robustness weaknesses while keeping the underlying task valid and solvable. TIPER evolves persistent user personas through reflection-guided behavioral mutations and task-wise Pareto selection under a task-integrity

---

### [178] Verification as an Architectural Layer for LLM Agents: A V-Model Design, and a Pilot Study of Its Deterministic Core

**链接**: https://arxiv.org/abs/2609.31937
**作者**: Ali Afoud, Jie JW Wu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [179] SARATHI: Decoupled Data-Free Probing and Adaptive Reconstruction for Structured LLM Pruning

**链接**: https://arxiv.org/abs/2610.15514
**作者**: Sankar Behera, Dhruv Singh, Satyadev Ahlawat, Yamuna Prasad
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured pruning reduces the inference cost of large language models (LLMs) by permanently removing neurons and weight rows, yielding dense, hardware-agnostic speedup. Existing post-training methods couple neuron selection and weight reconstruction through a shared calibration dataset, introducing domain bias and out-of-memory failures at high sparsity. We propose SARATHI, a framework that decouples these two stages. A data-free \emph{NMF Residual Subspace Probe} scores neurons using intrinsic weight geometry, without accessing any calibration data, and carries a formal connection to Robust PCA. \emph{Adaptive OBS} then reconstructs the pruned weights with a localized calibration batch, operating in $\mathcal{O}(d^2)$ peak memory per layer and eliminating the global memory bottleneck of coupled methods. A \emph{Bias Shift Compensation} step corrects systematic activation drift in post-LayerNorm architectures that would otherwise cause perplexity collapse at high sparsity. Experiments

---

### [180] Training-Free BioNEL-RAG: Advancing Biomedical Entity Linking through Retrieval-Augmented Generation and Large Language Model

**链接**: https://arxiv.org/abs/2610.14789
**作者**: Ziyi Chen, Hui Liu, Ziyang Ling, Ronald X.Xu, Mingzhai Sun
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biomedical Named Entity Linking (BioNEL) is the task of mapping mentions extracted from biomedical texts to canonical entities or concepts in the standardized knowledge base. Although existing methods have achieved remarkable performance in mapping accuracy, most rely on training with domain-specific datasets, which fundamentally limits their cross-domain adaptability. To address this limitation, we propose BioNEL-RAG, a novel training-free framework that combines retrieval-augmented generation (RAG) with large language models (LLMs). Within this framework, the RAG module focuses on retrieving candidate entities, while the large language model module plays the role of selecting the most appropriate candidate for entity normalization, which is based on the analysis of the mention's context, with the aid of its remarkable text comprehension capabilities. Experimental results demonstrate that BioNEL-RAG achieves performance comparable to existing methods without requiring training on subd

---

### [181] Review Rarely Beats the Stronger Model: Separating Verification from Capability Transfer in LLM Pipelines

**链接**: https://arxiv.org/abs/2610.15897
**作者**: Yirui Zhang, Yash Raj Shrestha
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Qwen3-8B reviewing Llama-3.1-8B in math adds 33.2 points, yet Qwen3-8B alone is 6.4 points more accurate than the result. Reviewing another model's answer is usually judged by its gain over the generator. We show that this confuses verification, which adds accuracy beyond either model alone, with capability transfer, where a stronger reviewer supplies answers it could have given on its own. Measured against the stronger model alone, across 48 pairs of 12 open-weight models (3B to 72B) in math, knowledge, code and reasoning, review beats it in only 9 of 96 review directions, and does worse the larger the capability gap. The reason is that the reviewer mostly follows the generator, discarding its own correct answers. Review costs 2.6 to 2.8 times as much as the stronger model alone, while a selector using the same two calls is 2.7 to 4.2 points more accurate than review and cheaper. Studies of verification should report the stronger model alone, not only the gain over the generator. Code

---

### [182] Encoding Context into LLM Weights: What Makes It Context?

**链接**: https://arxiv.org/abs/2610.17686
**作者**: Yue Wang and Qizhou Wang and Feng Liu and Gang Niu and Masashi Sugiyama and Bo Han
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Longer contexts allow large language models (LLMs) to condition their predictions on more information, but inference costs grow prohibitively with context length. An emerging alternative uses test-time updates to encode context as temporary changes to model weights. However, encoding this information into weights that already represent general knowledge obscures its role as context, so the LLM may fail to use it properly to condition subsequent inference. To restore this contextual role, we first associate each context with an identifier during encoding, thereby distinguishing the newly encoded information from pre-existing knowledge. Invoking the identifier at inference then enables the LLM to recite the encoded context. Nevertheless, successful recitation does not ensure that the LLM will use the recalled information as context. We therefore further introduce a prompting framework that explicitly guides the LLM to use this information as context. Across diverse controlled tasks and p

---

### [183] Fresh at Decision, Stale at Action: Routing New Information to LLM Decisions Already Made

**链接**: https://arxiv.org/abs/2610.18126
**作者**: Ayoub Merimi, Souhail Bakkali, Abdeljalil Sakat
**来源**: cs.AI cs.GT cs.IR cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Freshness shapes an LLM decision at the moment it is made; the action it commits to is latent, carried out later, in a changing world. We therefore introduce a timestamp theory of decision validity and a decision ledger that realises it. Six timestamps define a decision; a freshness ceiling bounds what up-to-date evidence guarantees at action time, placing the remaining risk in information published afterwards. Accuracy then factorises into two capabilities: routing, which delivers that information to affected decisions before their revision deadlines, and temporal judgment, which reads it for the time of action. The ledger is persistent state holding each decision's times, evidence and background knowledge, indexed by watch conditions written at decision time. Controlled decision streams with exact labels confirm four predictions across five LLMs, from 8B to frontier scale: freshness alone yields exactly the accuracy the ceiling predicts; models act on decisive news once it arrives, s

---

### [184] PermaFrost-Attack: Stealth Pretraining Seeding(SPS) for planting Logic Landmines During LLM Training

**链接**: https://arxiv.org/abs/2604.22117
**作者**: Harsh Kumar, Rahul Maity, Tanmay Joshi, Aman Chadha, Vinija Jain, Suranjana Trivedy 等 (7 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [185] Right Answer, Wrong Reason: Accuracy, Consistency, and Consensus Are Misleading Indicators of LLM Faithfulness in Clinical Decision Support

**链接**: https://arxiv.org/abs/2609.32817
**作者**: Bharath Kumar Bolla, Chaitali Deb Purkayastha and Vishnu Surya Reddy Nandi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [186] LLM-based User-Product Relevance Evaluation for Dynamic Product Advertising

**链接**: https://arxiv.org/abs/2610.14550
**作者**: Wen Zhang, Xiao Bai, Hsiang-wei Chao, Mengfan Zhu, Tong Zhao, Mingxuan Ju 等 (10 人)
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic Product Advertising (DPA) retrieval systems are a core component of modern e-commerce advertising; however, their evaluation remains challenging. Conventional offline engagement metrics are limited by sparse, biased feedback, while online evaluation is costly and time-consuming. In this work, we propose a user--product relevance metric for offline evaluation of DPA retrieval systems. The metric first compresses the engagement history into a compact set of intent representatives via Semantic-ID-grouped, event-stratified segmentation, then assesses the relevance of a recommended product to each individual intent and aggregates them as a user-level relevance score, yielding a stable and interpretable measure of retrieval quality. To compute this metric at scale, we leverage large language models (LLMs) as semantic relevance judges, capturing nuanced functional and semantic relationships that heuristic methods often miss. We propose an agentic, human-aligned prompting framework tha

---

### [187] Style Over Substance: Content-Invariant Wrappers Flip LLM Safety-Judge Verdicts

**链接**: https://arxiv.org/abs/2609.08236
**作者**: Yongxi Zhou, Wenbo Ye, Yuanzhe Liu, Zihan Dong, Junwei Yao, Jiahui Ge
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [188] RadixFlow: Filling Execution Bubbles in Prefix-Cached Hybrid LLM Serving

**链接**: https://arxiv.org/abs/2610.18143
**作者**: Huihao Jing, Wenbin Hu, Shaojin Chen, Haochen Shi, Haoyu Huang, Sirui Zhang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prefix reuse improves LLM inference by sharing the KV cache of common prompt prefixes. This helps only if the scheduler can execute a matched branch in the current worker round. Schedulers assume that a matched prefix is ready, which holds for full attention but fails for hybrid LLMs. There, a branch (the consumer) may need recurrent state that another branch (the producer) is still computing in the same round. The native scheduler stops its waiting-queue scan at this blocked consumer, and the resulting head-of-line blocking creates \emph{execution bubbles}: idle batch slots that independent work could fill. We introduce RadixFlow, which decouples prefix matching from state readiness. Its state-ready traversal turns a global scan barrier into a local wait: only the consumer is blocked until the next round, while feasible independent branches keep filling the batch under the native state check. On five hybrid models, RadixFlow lowers mean latency by 3\% to 24\% and worker rounds by 11\%

---

### [189] Learning to GUIDE the Group: Self-Learning LLM Facilitation Across Multi-Party Tasks

**链接**: https://arxiv.org/abs/2610.16231
**作者**: Ziyi Liu, Tzu-Sheng Kuo, Jiale Liu, Deqing Fu, Nithum Thain, Crystal Qian
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models are increasingly adopted as multi-party communication facilitators, there is a growing demand for agents capable of balancing diverse group dynamics across contexts. However, existing LLM facilitators are often fine-tuned for task-specific objectives; generalized LLM-based facilitation methods that can adapt to different types of tasks and diverse group dynamics are underdeveloped. To address this gap, we present GUIDE (Generalized Unified Intervention for Dynamic Exchanges, a framework for developing generalized LLM-based facilitators across different multi-party contexts. GUIDE evaluates facilitation across both objective task outcomes and subjective metrics, including psychological safety and perceived friction. Within this framework, we study whether LLMs can self-learn generalized facilitation strategy offline to real-time interventions. We first collect multi-party human interactions guided by task-specific expert LLM facilitators (N=432 conversations). W

---

### [190] Stable Token-level Scheduling for Serverless LLM Inference

**链接**: https://arxiv.org/abs/2610.17689
**作者**: Hardi Ashishbhai Desai, Balaji N K, Sourav Kanti Addya
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Serverless inference is emerging as an efficient deployment model for Large Language Models (LLMs) due to its ability to elastically scale resources, improve GPU utilization through resource sharing, and reduce infrastructure costs. However, existing approaches primarily optimize time to first token (TTFT) while overlooking inter-token latency (ITL), a key determinant of user experience during response generation. We observe that LLM inference comprises a computation-intensive prefill stage and a bandwidth-bound decode stage, where admitting new requests can disrupt ongoing decoding and increase latency. To address this, we propose Token Window Pacing (TWP), a closed-loop scheduling framework that leverages runtime feedback from ITL, queue depth, and workload characteristics to regulate request admission at the token level instead of the batch level. TWP dynamically adjusts a selfregulating token window and incorporates chunk-based prefill to minimize interference from incoming request

---

### [191] Can We Trust This Evaluation? Instance-Level Reliability of LLM-as-a-Judge

**链接**: https://arxiv.org/abs/2610.14029
**作者**: Yang Ba, Michelle V. Mancenido, Rong Pan
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-judge evaluation commonly aggregates multiple judges' decisions into a majority vote, yet this panel decision process does not guarantee that the evaluation of an individual item is reliable. We propose Structured Cross-fitted Uncertainty Risk (SCUR), a label-free approach for estimating instance-level evaluation reliability based on the judge panel's behavior. A latent measurement model serves as the backbone for measurement system analysis, from which SCUR derives three complementary signals capturing panel uncertainty, measurement cross-entropy, and perturbation sensitivity. These three sources of evidence are combined into a risk score. We evaluate the SCUR approach on five real-world benchmarks using majority-vote error ranking, selective trust, and risk stratification. Furthermore, we show our approach to be more effective at detecting high-consensus risk items, which are the blind spots for many other LLM-as-a-judge evaluation methods.

---

### [192] How Low Can You Go: Fine-Tuning LLMs with Bayesian Optimization (LlMBO)

**链接**: https://arxiv.org/abs/2610.18504
**作者**: Aditya Kulkarni, Davide Sartor, Carlos Soto, Nathan Wycoff
**来源**: stat.ML cs.LG stat.ME
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recently, Morris et al. introduced TinyLoRA, a strategy for LLM fine-tuning which introduces arbitrarily few parameters, and demonstrated accuracy improvements using less than $10$ parameters rather than the ${\gtrsim 10,000}$ typically demanded by LoRA-based methods. However, that study continued to use gradient-based local search methods of the kind deployed for training multi-billion parameter LLMs in the first place. This article is predicated on the observation that, in the low dimensional setting, global optimization methods become tractable, unlocking Large language Model Bayesian Optimization (LlMBO). LlMBO is sample-efficient, gradient-free, memory-light, parallelizes across devices without synchronization, and, unlike policy-gradient methods, can optimize greedy-decoding accuracy directly. We describe numerical experiments comparing LlMBO against GRPO on fine-tuning tasks for a variety of models on a math benchmark suite which show that LlMBO can be a suitable alternative in 

---

### [193] TurboEvolve: Towards Fast and Robust LLM-Driven Program Evolution

**链接**: https://arxiv.org/abs/2604.18607
**作者**: Yang Yang, Zining Zhong, Jindong Li, Jiemin Wu, Kaishen Yuan, Wenshuo Chen 等 (8 人)
**来源**: cs.NE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [194] When Does Consistency Pay Off? Relational Constraints for LLM-based Document-Level Relation Extraction under Incomplete Annotations

**链接**: https://arxiv.org/abs/2607.24312
**作者**: Mingxuan Sun
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [195] EvoSignal: LLM-Guided Evolutionary Design of Modular Traffic Signal Control Programs

**链接**: https://arxiv.org/abs/2610.09563
**作者**: Leizhen Wang and Peibo Duan and Zhenlin Qin and Yancheng Ling and Jian Xu and Yue Wang and Hao Wang and Zhenliang Ma
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [196] Growing and Transferring Pathways for LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.16489
**作者**: Haolin Tian, Yikang Li, Tonghan Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) can substantially improve the reasoning capabilities of large language models, but an effective training run requires considerable resources. Reusing the computation acquired through RL across models would extend the value of that training. We propose GrowRL, an RL method that organizes learned updates into compact computational pathways through structural growth. GrowRL freezes the pretrained backbone and adds an independent causal attention branch and a feed-forward network branch at each Transformer layer. Zero-initialized output projections preserve the pretrained policy at initialization, and RL updates only the added pathways. The learned pathways remain explicit after training, allowing transfer to structurally compatible target models and subsequent adaptation with the target backbone frozen. The architecture also supports sequential transfer of additional pathways. By keeping the learned attention and feed-forward computation separate from the pretr

---

### [197] Online LLM Personalization from Pairwise Preferences Across Users

**链接**: https://arxiv.org/abs/2610.17203
**作者**: Romain Puech, Georgy Salakhutdinov, Dimitris Bertsimas
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can answer the same question in different styles, but users' preferred styles are hidden and vary across users and questions. We study inference-time personalization through online selection from a fixed set of prompts, each representing a persona. Users arrive sequentially, each asks a short sequence of questions, and the system displays two responses per question and observes one pairwise choice. We formulate this interaction as a variant of the contextual dueling bandit problem in which the learner starts without preference data, adapts within each session, and exploits information shared across users. The objective is to minimize cumulative strong regret, summing the utility gaps of both displayed responses relative to the user's best response among the available options. We make two contributions. First, we introduce the problem and release a reproducible preference benchmark and dataset built around a tutoring case study, containing educational questions, LL

---

### [198] Memory as a Controlled Process: Learned Adaptive Memory Management for LLM Agents

**链接**: https://arxiv.org/abs/2607.13591
**作者**: Eric Hanchen Jiang, Zhi Zhang, Yuchen Wu, Levina Li, Dong Liu, Xiao Liang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [199] TADDLE: A Tool-Augmented Agent for Detecting Deficient LLM-Generated Peer Reviews

**链接**: https://arxiv.org/abs/2605.26911
**作者**: Hanqi Duan, Xiang Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [200] LLM Evaluation is a Forecasting Problem

**链接**: https://arxiv.org/abs/2610.17018
**作者**: Rahul Thomas, Adam Block, Micah Goldblum
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard procedure in machine learning is to randomly split train and test data, emulating IID draws from one underlying data distribution. In practice, models are trained on past data and deployed in the future, which may come from distinct distributions. In this paper, we find that web text is indeed highly non-stationary, as text distributions shift over time. We further observe that model performance changes continuously over time across diverse benchmarks. Consequently, future model performance is better predicted by measurements made on recent evaluation data, and is best predicted by time series forecasters applied to historic performance rather than by historic performance itself. Choosing which model to deploy based on forecasted accuracy enables more reliable selection of performant models, thus improving downstream accuracy in the regime practitioners care about: deployment. Taken together, our experiments suggest that time should be treated as a fundamental variable in LLM 

---

### [201] To Embody or Not: The Effect Of Embodiment On User Perception Of LLM-based Conversational Agents

**链接**: https://arxiv.org/abs/2506.02514
**作者**: Kyra Wang, Abhinaba Roy, Boon-Kiat Quek, Jessica Goh, Dorien Herremans
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [202] Behavioral History Outperforms Descriptions of the Person for LLM Synthetic Personas

**链接**: https://arxiv.org/abs/2610.03998
**作者**: Khashayar Pourtaheri, Ahmad Zareei
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [203] AuthScribe: Supporting Agency and Authorship in LLM-Assisted Reflective Journaling

**链接**: https://arxiv.org/abs/2610.15439
**作者**: Lanping Hu, Yinsi Zhou, Zhenchang Xing, Xiaoyu Sun, Shidong Pan
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used in reflective journaling, where articulating an experience is part of interpreting it. This raises questions about how writers retain authorship, exercise agency, and assess personalized assistance. We present AuthScribe, an LLM-assisted reflective journaling system that combines contextual anchors, writer-steered AI support, Autobiographical Citations, and read-only Provisional Drafts that require re-expression before AI-generated suggestions enter the journal. Retrieval and LLM inference run on-device. In a 14-day field deployment with 14 participants, grounding shifted from situating current experiences to reconnecting them with prior self-authored interpretations. Perceived agency remained stable through Week 1 and shifted during Week 2. Participants described authorship through transforming AI-generated suggestions into personally meaningful expression, and trusted personalized prompts when they could trace them to prior writing. We disc

---

### [204] Fine-grained Analysis of Brain-LLM Alignment through Input Attribution

**链接**: https://arxiv.org/abs/2510.12355
**作者**: Michela Proietti, Roberto Capobianco, Mariya Toneva
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [205] Measuring Concept Content in Text from LLM Activations: ESG Evidence from Concept Vectors and Linear Probes

**链接**: https://arxiv.org/abs/2608.07208
**作者**: Luc Hazenoot, Zhaochun Ren, Amirhossein Zohrehvand
**来源**: cs.CL cs.AI cs.LG econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [206] HHR: Hierarchical Hash Retrieval for Efficient LLM Generation

**链接**: https://arxiv.org/abs/2610.01230
**作者**: Lianjun Liu, Tiantian Zheng, You Huang, Weiqi Yan, Mingte Qiu, Huazhong Liu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [207] From Chasing Ghosts to Missed Attacks: Perspectives and Perceptions of SOC Practitioners on LLM Integration, Risks, and Readiness

**链接**: https://arxiv.org/abs/2608.00672
**作者**: Jonas Thurner, Nadine Jost, Stefan Albert Horstmann, Fabian Ising, Lea Groeber, Alena Naiakshina 等 (7 人)
**来源**: cs.CR cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [208] Co-DSL: Human-LLM Co-design of Reusable Spatial Concepts for Layout Generation

**链接**: https://arxiv.org/abs/2610.15290
**作者**: R. Kenny Jones and Jiajun Wu and Maneesh Agrawala
**来源**: cs.GR cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Co-DSL, a framework in which users and LLMs co-design reusable spatial concepts for layout generation. In the first stage, our system allows users to create a library of personalized operations. To add a concept, a user provides a description, which the LLM converts into an initial implementation. The user can then observe the concept's execution behavior over example scenarios and provide lightweight feedback to the LLM, which revises the concept's implementation logic. In the second stage, given a library, an LLM can author a layout program that meets a new layout request from a user. Executing a layout program instantiates a concept-graph, a declarative composition of library concepts. In this way, we require the LLM only to specify which concepts should hold, while we use a solver to search for a layout that satisfies them. Across five spatial layout domains, we find that Co-DSL libraries let LLMs capture layout patterns that are challenging for prior fixed-operation sys

---

### [209] Re-executing Coding-Agent Evaluations: Unchanged Decisions and Unresolved Policy Risk

**链接**: https://arxiv.org/abs/2610.14460
**作者**: Tianyu Ding, Yaocheng Tong, Muzhi Yang, Fei Jiang, Lei Yang, Boya Yu
**来源**: cs.SE cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Executable tests grade large language model (LLM) coding-agent patches for leaderboards, rewards and self-improvement. Two preregistered re-execution studies returned negative results. SWE-bench Pro v1's offline option rejected none of 59 accepted Go patches whose grading configuration changed. Their exploratory, unweighted upper confidence limit is 4.95% under candidate independence, leaving a 3% exposed-patch risk unresolved; the preregistered estimator uses inverse sampling-probability weights. An extension was inconclusive. In a selected stratum, a reconstructed module cache built from the reference solution's dependencies rejected accepted alternatives from four models that passed with their own dependencies. Re-executing 1,929 selected agent-version/task evaluations from the Darwin G\"odel Machine's archive preserved best-agent selection and system-variant ranking, with search history and scores of evaluations not rerun fixed. Exploratory host, image and adapted-grader comparison

---

### [210] ChunkAct: Action Chunking for Agentic Robotics

**链接**: https://arxiv.org/abs/2610.18874
**作者**: Bingxin Xu, Wenrui Bao, Xinxin Liu, Jiawei Zhou, Yuzhang Shang, Emilio Ferrara
**来源**: cs.RO cs.AI cs.CL cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic robotics places a large language model (LLM) agent in the robot control loop, where it composes perception, motion, and vision-language-action (VLA) tools under the guidance of a memory and thereby generalizes to new tasks without retraining. This generality comes at a steep price in efficiency. Every primitive requires a round of LLM reasoning over the full interaction history, so the cost of an episode grows with the number of primitives. We find this reasoning largely redundant: once a sub-goal is chosen, its primitives follow a routine already prescribed by memory. We present ChunkAct, which introduces action chunking to agentic robotics. Online, a single call launches a chunk of chained primitives, which executes autonomously and returns control only upon failure. Offline, ChunkAct compiles the memory into these chunks, so execution is memory-free at test time and the planner is reserved for decisions that require reasoning. LLM computation therefore scales with the number

---

### [211] RIS-Kernel: A Model-Agnostic Architecture for Long-Context LLM Inference via Sparse Attention

**链接**: https://arxiv.org/abs/2607.21927
**作者**: Anderson R. Santos
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [212] Large Language Model-Guided Evolutionary Discovery of Native Neural Architectures for Spiking Sequence Modeling

**链接**: https://arxiv.org/abs/2609.40258
**作者**: Ruoyu Zhao, Jiaqi Wu, Chenyu Zhu, Zhichao Lu
**来源**: cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [213] Event Memory and Narrative Dynamics: A Large Language Model Framework for Multidimensional State Spaces

**链接**: https://arxiv.org/abs/2610.16971
**作者**: Joshua Sari\~nana
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Studying event memory requires defining events and their relationships within remembered experience. Autobiographical narratives provide evidence of this organization, but their analytical units must first be established. This study introduces a large language model framework for constructing event representations from narratives and modeling their structure and dynamics with excerpt-level traceability. Explicit boundary rules and a feature schema informed by hippocampal models of episodic memory and navigation guide event construction. In a proof-of-concept application to interviews from five participants, the framework constructed 256 event-states. Multiple correspondence analysis embedded these states in feature-based spaces, with analyses focused on a selected 4-D geometry and 10-D and 13-D reference geometries. Consecutive event-states were significantly closer than expected under randomized narrative order. In the selected 4-D ten-basin solution, similarity between basin-state fe

---

### [214] VERGE: Formal Refinement and Guidance Engine for Verifiable LLM Reasoning

**链接**: https://arxiv.org/abs/2601.20055
**作者**: Vikash Singh, Darion Cassel, Nathaniel Weir, Nick Feng, Sam Bayless
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [215] CHAIN: Calibrated LLM Forecasting via Causal-Temporal Hypergraph Inference

**链接**: https://arxiv.org/abs/2609.36689
**作者**: Wenjin Liu, Chenxi Wang, Yue Lu, Zhe Cui, and Haoran Luo
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [216] The Format is the Filter: Scoring Format Fixes What an LLM Judge Can Express

**链接**: https://arxiv.org/abs/2610.17158
**作者**: Lovedeep Gondara, Jekaterina Novikova, Sagarika Suresh, Jack Ji, Jithin Pradeep
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM judge filters instruction-tuning data, its scoring format (binary verdict, 1--5 rating, 0--100 score, or comparison) is rarely justified or ablated. Holding the candidate pool, judge prompt, decoding and selection budget fixed, we score 15,406 UltraFeedback candidates under five formats with three judges, curate, fine-tune 66 models, and evaluate them with four judges. A 0--100 scale is worth only 7--12 equally used levels, two to three times a 1--5 scale rather than twenty, and a binary verdict leaves the top score tied in 77--78\% of prompts, so most selections are made at random. These properties are set by the format almost independently of the judge. Kendall's $\tau_b$ hides them: it ranks binary best while $\tau_a$ and top-1 agreement rank it last, because it discounts the ties a selector must break at random. Both comparative formats inherit a slot bias whose sign differs across judges. Downstream, curated data beat random selection under every evaluation judge, robu

---

### [217] TRAP: Tool-result Replay Attack for Probing Misbinding in LLM Agents

**链接**: https://arxiv.org/abs/2610.16333
**作者**: Yutong Zhi, Jie Zhang, Xiuqi Lu, Jiayuan Xu, Jing Shao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI agents increasingly act through external tools, tool results are no longer simple outputs but execution artifacts that must remain correctly associated with the context that produced them. Yet as results persist across caches, recovery mechanisms, and shared runtime state, this association can break, causing a real and unmodified result to be consumed in an incompatible execution context and lead the agent to an unsafe action. We characterize this failure as tool-result misbinding. To systematically study this failure, we introduce ReplayBench, a benchmark that uses controlled tool-result replay to evaluate misbinding across 19 representative agent scenarios, 4 failure properties, and 3 replay mechanisms. Across eight LLMs, three agent frameworks, and diverse stateful workflows, we find widespread replay-induced failures, with a mean Final-State Error Rate of 0.649 under cross-task replay. Stage-wise analysis localizes these failures to model-side action generation. Further analy

---

### [218] Claim Framing as a Driver of LLM Sycophancy

**链接**: https://arxiv.org/abs/2610.18159
**作者**: Jean Seo, Pepa Atanasova, Isabelle Augenstein
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sycophancy in Large Language Models, the tendency to align responses with user preferences over ground truth, has largely been studied using questions without a clear ground truth and with a single, plainly stated user opinion. We present a systematic study of which framings of a user's claim trigger sycophancy in factual question answering, where every answer is objectively verifiable without extra context. Evaluating 14 models on 42K questions, we express correct and incorrect user opinions through various claim framings over 8 dimensions and 21 types, and measure a broad set of opinion-driven behaviors. We find that all models are susceptible to user opinions regardless of size. Models are most influenced by how confidently an opinion is stated, whom it is attributed to, and whether it is presented as shared between the user and the model. In contrast to prior work, framings based on the user's expertise, authority over the model, or social pressure matter little in our factual sett

---

### [219] TL;QR: Querying Temporal Discursive Patterns in Textual Corpora

**链接**: https://arxiv.org/abs/2610.15712
**作者**: Fran\c{c}ois Hublet, Vladimir Krsmanovic, Jesus Solano, Ahmed Bouhoula, Ana Oliveira da Costa
**来源**: cs.CL cs.CY cs.DB cs.LO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many questions about large textual corpora concern patterns that unfold over time, such as a political group whose stance on a topic drifts from support to criticism over several years of debates. We present TL;QR (Too Long; Query with logical temporal Reasoning), a declarative query language and open-source engine for finding such temporal discursive patterns. In TL;QR, a single query combines natural-language predicates, whose truth is judged by a Large Language Model (LLM), with regular expressions and the operators of a temporal logic. The LLM answers only local questions about individual text passages; a symbolic engine then aggregates these judgments over time and links every match to the recorded passages and predicate decisions behind it. With this division of labor, the temporal and relational reasoning stays exact and auditable even over long time horizons. In addition, when a query includes a regular-expression pre-filter, only a small fraction of the corpus ever reaches the

---

### [220] Rethinking Visual Provenance: Detection and Watermarking Across Direct Visual Generation and LLM-Driven Code Rendering

**链接**: https://arxiv.org/abs/2610.08137
**作者**: Zheng Gao, Xiaoyu Li, Zhicheng Bao, Jiaojiao Jiang
**来源**: cs.CR cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [221] A CaLLM Judge is a Better Judge: Mitigating Bias in LLM-as-a-judge

**链接**: https://arxiv.org/abs/2610.18108
**作者**: Cesare Barbera, Luca Stradiotti, Lorenzo Cascioli, Lorenzo Perini, Niek Tax, Daniel Haimovich 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as judges to predict which of two candidate answers a human evaluator would prefer, providing a scalable alternative when human evaluation is too costly. Unfortunately, LLM judgments can exhibit systematic biases. Prior work has documented position, verbosity or model family of the candidate answers influencing the judge decision rather than their quality, while additional biases may remain undocumented. $\textit{Multicalibration}$ provides a natural framework to address this problem: each bias corresponds to miscalibration on an identifiable group, $\textit{e.g.}$, family bias manifests as overconfidence in answers generated by models belonging to the same family of the judge. The challenge is to fix miscalibration simultaneously across many, potentially unknown groups. To this end, we introduce $\mathrm{CaLLM}$, a post hoc framework that multicalibrates an LLM judge, thereby bounding all such biases simultaneously. We prove that $\ma

---

### [222] HarnessMDP: Learning to Control LLM Agent Harnesses with Offline Reinforcement Learning

**链接**: https://arxiv.org/abs/2607.05458
**作者**: Haiwen Yi and Xinyuan Song
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [223] STEPwise: Supporting Teachers in Diagnosing Students' Mathematical Problem-Solving Skills through LLM-Generated Questions and Rubric

**链接**: https://arxiv.org/abs/2610.16344
**作者**: Yoonsu Kim, Hayeon Doh, Eunhye Kim, Jinho Son, Juho Kim
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Problem-solving is central to mathematics education. However, diagnosing where students' reasoning breaks down requires individualized probing and consistent criteria that teachers cannot sustain at classroom scale. We introduce STEP (STage-based Evaluation of Problem-solving skills), co-designed with six mathematics education experts, which operationalizes problem-solving as four stages and eight diagnostic sub-skills. By specifying what evidence to elicit and assess at each stage, STEP enables an LLM pipeline to generate stage-specific questions and rubrics for any math word problem, reducing the manual design of diagnostic materials. An expert review (N=8) assessed the pedagogical validity of the generated materials and informed STEPwise, a teacher-in-the-loop system for diagnostic material generation and process-level assessment. In a classroom study with 5 teachers and 64 students, STEPwise helped teachers and students locate reasoning breakdowns and supported students in reflecti

---

### [224] When Agents Talk, Secrets Travel: Topology-Driven Leakage and Recipient-Conditioned Sanitization in Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2610.16039
**作者**: Sunday Oyinlola Ogundoyin and Muhammad Ikram
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems (MALS) introduce a privacy-leakage problem that conventional sensitivity-based defenses miss, since information disclosed to one authorized agent can propagate through routine coordination to an unauthorized one, without compromise or malicious behavior. This motivates topology-aware enforcement that blocks unauthorized propagation while preserving authorized disclosure. We evaluate 485 scenarios across coordinator-worker, peer-to-peer, and hierarchical topologies, instrumenting seven communication channels and measuring surface leakage and disclosure to topology-introduced recipients. We introduce RECONS, a Detect -> Decide -> Transform sanitizer conditioning intervention on recipient and execution context rather than sensitivity alone. Topology changes where protected information propagates, with disclosure to topology-introduced recipients rising from 0% to 52.2% while surface leakage stays nearly flat at 60.6-62.8%. This effect persists across four generator

---

### [225] Evaluating LLM-Generated Rules for Heart Disease Prediction

**链接**: https://arxiv.org/abs/2609.13192
**作者**: Feisal Alaswad, Batoul Aljaddouh, Maher Alrahhal, Wafaa Al Nassan, Talal Bonny
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [226] LLM Alignment--Utility Asymmetry under Semantic-Preserving Transformations

**链接**: https://arxiv.org/abs/2609.32717
**作者**: Mohan Li, Chengyu Yu, Francesco Sovrano, Marc Langheinrich, Martin Gjoreski
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [227] The Shared Latent Structure of LLM Psychometric Responses

**链接**: https://arxiv.org/abs/2605.05080
**作者**: Hubert Plisiecki, Sabina Siudaj, Kacper Dudzic, Anna Sterna, Maciej Gorski, Karolina Drozdz and Marcin Moskalewicz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [228] StableJudge: A Lightweight Adversarial Defense Framework for LLM-as-a-Judge

**链接**: https://arxiv.org/abs/2610.16814
**作者**: Anning Hu, Yangyu Li, Yuqi Huang, Shengchao Hu, Junchi Yan
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as judges to assign scalar scores that drive downstream decision-making, including tasks such as paper review and recommendation. However, LLM-as-a-Judge pipelines are vulnerable to score-hijacking prompt injection embedded in evaluated content, which corrupts scoring signals and distorts induced rankings. Existing defenses often enforce robustness by modifying the judge model itself, making safety dependent on a specific model's scale and training and requiring repeated effort when the judge is updated or replaced. We propose StableJudge, a lightweight defense framework that externalizes prompt-injection mitigation as a reusable pre-scoring capability. StableJudge centers on a compact 0.13B Sentry that localizes injected spans and performs targeted sanitization prior to evaluation, and is trained using adversarially evolving attacks to improve robustness beyond a fixed prompt set. To stabilize measurement, StableJudge derives determin

---

### [229] The Anatomy of a Blind Spot: What an LLM Judge Must Be Shown, and How Much

**链接**: https://arxiv.org/abs/2610.15938
**作者**: Nitish Kumar, Prateik Pothuneedi, Greg Bandak
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation of text generated by large language models (LLMs) is increasingly delegated to LLMs acting as judges, yet what such a judge must be shown remains unresolved. We treat a judge whose reports are acted on as a regulator, in the sense of cybernetics, and ask what it must be shown, how much, in what form, and what its reports must get right. On seven public benchmarks we varied only what the judge was shown. Across three judges whose prices differ 10- to 17-fold, what the judge was shown mattered more than which judge it was. When a system revised its answers on feedback from a judge denied the material they had to respect, it ended below its starting point on instruction following and question answering. On instruction following the loss grew with each round, and it persisted when the judge saw the user's request but not the constraints and with a second judge family. On news summarisation, a correct reference summary beside the source undid most of the source's contribution, wh

---

### [230] Choosing LLMs for Strategic Agent Interactions

**链接**: https://arxiv.org/abs/2610.18354
**作者**: Arastun Mammadli, Herbert Woisetschl\"ager, Jawad Fayaz, Shiqiang Wang
**来源**: cs.AI cs.IR cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Game-theoretic benchmarks claim that large language model (LLM) strategic decision-making varies across game types, interaction structures, and capability dimensions. However, they only evaluate strategic performance across individual fixed models. In parallel, contemporary LLM routers pick models under quality-cost trade-offs, but with no notion of a strategic structure. They do not account for an opponent that might be unknown, and that can adapt over time and shift the feedback signal. To address this, we extend the game-theoretic evaluations and define strategic selection as the meta game layered on top of the base game. In each round, a strategic selector fields an LLM from a portfolio of models to navigate a game payoff matrix that is latent and learned online. We find that the evaluation signal is game-specific, and that extracting a reliable signal requires a much higher number of seed runs $N$ compared to traditional benchmarking setups. Evaluating across 5 games and 10 LLMs, 

---

### [231] MultiAlloc: Budget-Aware Precision Allocation for KV Cache Quantization

**链接**: https://arxiv.org/abs/2610.18642
**作者**: Yangchengyu Zhou, Zhiping Wu, Runchang Jiang, Dongdong Ren, Youfang Han, Wei Zhao 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Key-Value (KV) cache constitutes a dominant source of memory consumption during large language model (LLM) inference, particularly in long-context and complex reasoning scenarios. Existing KV cache quantization methods have explored different compression granularities, including layer-wise precision adjustment and token-level information preservation. In practical deployment, however, the key challenge is not merely compression, but how to allocate limited quantization resources among heterogeneous precision preservation strategies under a fixed KV cache memory budget. We propose MultiAlloc, a profiling-guided precision allocation framework for KV cache quantization that adaptively distributes limited quantization resources between layer-wise precision enhancement and token-wise preservation. MultiAlloc employs lightweight offline profiling to characterize layer sensitivity and token importance, enabling adaptive precision allocation under a fixed memory constraint. Guided by the p

---

### [232] Accelerating Cross-Model LLM Inference via Attention Map Reuse

**链接**: https://arxiv.org/abs/2610.14688
**作者**: Zhan Jin, Yuze Luo, Bin Cui, Xupeng Miao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-augmented data workflows often involve multiple heterogeneous models operating over substantial shared context, such as schemas, tool specifications, interaction history, and intermediate results. Although prefix caching can reduce prefilling overhead, existing approaches are largely limited to reuse within the same model because KV states are tightly coupled to model-specific architectures. We present MapFlow, a system for efficient heterogeneous LLM serving via cross-model attention map reuse. Instead of reusing KV states, MapFlow reuses attention maps, which capture token dependency patterns and are more transferable across models. To enable efficient and accurate reuse, we combine partial recomputation with lightweight linear translation across layers and heads. To make attention reuse practical for long contexts, we further introduce block-level sparse compression and a fused retrieval kernel. Experiments show that MapFlow reduces prefilling latency and improves end-to-end ser

---

### [233] SKILL-KD: Contrastive Skill Distillation for LLM Agents

**链接**: https://arxiv.org/abs/2607.28048
**作者**: Qiming Shi, Yibo Dou, Jiawen Zhu, Yulong Tao, Linbo Jin, Zhaolu Kang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [234] AlignMerge - Alignment-Preserving Large Language Model Merging via Fisher-Guided Geometric Constraints

**链接**: https://arxiv.org/abs/2512.16245
**作者**: Aniruddha Roy, Jyoti Patel, Aman Chadha, Vinija Jain, Amitava Das
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [235] Radioactive Feedback: Tracing Models Trained by Label-Only LLM Supervision

**链接**: https://arxiv.org/abs/2610.15685
**作者**: Yuejia Li, JunHeng Li, Hao Wu, Ke He, and Mang Ye
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional distillation transfers capability through teacher-generated demonstrations. LLM-as-a-Judge knowledge distillation offers a distinct and increasingly practical alternative. In the label-only variant studied here, the student generates every response and improves from scalar scores alone. Prior work shows that this non-demonstrative feedback can improve student capability, but it creates a fundamentally different provenance problem. No teacher-generated answer enters the student's training set, so any evaluator-specific trace must pass through a low-bandwidth reward signal rather than copied text. Existing watermarks and distillation detectors do not cover this score-only channel. We introduce Radioactive Feedback, which encodes a registered pattern of behavioral preferences in the rewards themselves. The evaluator applies bounded pointwise adjustments to quality-qualified responses, allowing repeated optimization to transfer the pattern to a student trained by another party

---

### [236] LLM2R: From Large Language Models to 3D Reassemblers

**链接**: https://arxiv.org/abs/2610.18604
**作者**: Zhouhan Zhong, Qiuhong Shen, Xingyi Yang, Jinyi Xu, Xinchao Wang
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 3D part assembly aims to reconstruct a complete shape from a set of unassembled parts by predicting a rigid SE(3) transformation for each part. Because the placement of a part is rarely determined by its own geometry, the task demands reasoning over the entire part set, and existing methods, which rely on pairwise relations or iterative generation and verification, scale poorly to objects with many parts. We present LLM2R, which casts part assembly as sequence modeling with a pretrained decoder-only large language model (LLM): a Point-BERT encoder and a Q-Former compress each part into a block of geometric tokens, the blocks of all parts are concatenated, and a causal LLM adapted with Low-Rank Adaptation (LoRA) processes the sequence in one forward pass. Causal attention, however, lets the hidden states of a part observe only the parts that precede it. LLM2R therefore appends a block of learnable summary tokens after the last part: these tokens follow every part, so their states aggreg

---

### [237] GPU Goldmines: Tunable WebGPU Kernels for Edge LLM Inference

**链接**: https://arxiv.org/abs/2610.17321
**作者**: Rithik Sharma, Reese Levine, Zheyuan Chen, Ananthajit Srikanth, Yanwen Xu, Tyler Sorensen
**来源**: cs.DC cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As demand for LLM inference grows and consumer GPUs grow more capable, edge deployment is becoming increasingly attractive. WebGPU is compelling in this setting because it offers cross-platform portability and browser accessibility. However, these same strengths also make high performance difficult to achieve, as an implementation that performs well in one context may not perform well in another. To address this, we present GPU Goldmines, a framework for specifying, executing, and tuning WebGPU kernels. We instantiate GPU Goldmines with kernels for key LLM building blocks: matrix multiplication, matrix-vector multiplication, and flash attention. We characterize performance across diverse devices, shapes, and browsers, and use the resulting database to accelerate subsequent autotuning and configuration selection. On shapes drawn from Llama and Qwen models, our matrix multiplication kernels outperform ONNX Runtime and llama.cpp WebGPU kernels by 7.0x and 1.41x geometric mean, respectivel

---

### [238] DeKoR: Decomposed Knowledge Routing for Efficient GNN--LLM Fusion

**链接**: https://arxiv.org/abs/2610.14710
**作者**: Peiyuan Li, Yongqi Huang, Jitao Zhao, Di Jin, Dongxiao He
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown strong potential for text-attributed graph learning by leveraging rich pre-trained knowledge and language understanding capabilities. Combining LLMs with Graph Neural Networks (GNNs) offers a promising paradigm for expanding the modeling capabilities of graph learning. However, LLMs and GNNs follow distinct learning paradigms, leading to a pronounced mismatch between their knowledge spaces. Such discrepancies make effective knowledge fusion nontrivial. Moreover, existing methods often incur substantial additional computation for only limited performance gains. To address these challenges, we propose DeKoR, an efficient framework for GNN and LLM knowledge fusion. To enable efficient knowledge transfer, DeKoR decomposes LLM knowledge into complementary local and global views and uses the LLM as an offline teacher to distill them into lightweight experts. To enable selective knowledge fusion, an adaptive router learns how much each node should rely 

---

### [239] From Clicks to Intent: Cross-Platform Session Embeddings with LLM-Distilled Taxonomy for Financial Services Recommendations

**链接**: https://arxiv.org/abs/2606.26277
**作者**: Dianjing Fan, Yao Li, Kyaw Hpone Myint, Dwipam Katariya, Alexandre G.R. Day, Pranab Mohanty 等 (7 人)
**来源**: cs.IR cs.AI cs.CE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [240] Strong yet Controllable LLM Abstention without Learning to Abstain

**链接**: https://arxiv.org/abs/2610.16318
**作者**: Junwei Zhang and Yifei Wang and Wanli Yang and Hexiang Tan and Rui Tang and Xin Chen and Jingang Wang and Du Su and Fei Sun
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can reduce hallucination by abstaining from questions they would likely get wrong. Abstention can be implemented outside the model (selective answering) using a confidence threshold that controls the answer rate (coverage), or learned inside it (abstention training), which can perform better but fixes coverage once trained. To compare the two, we match their coverage and decompose risk (error rate) into answering ability and distinguishing ability, i.e., how well the model answers and how accurately it abstains, respectively. The decomposition shows that abstention training performs better mainly by answering better: with strong confidence estimators, the two have nearly equal distinguishing ability. This motivates Train for Accuracy, then Post-hoc Select (TAPS), a modular approach that keeps coverage controllable, needs only standard post-training and an off-the-shelf confidence estimator, and benefits from advances in either component. Across three LLMs a

---

### [241] Incumbent Advantage: Brand Bias and Cognitive Manipulation Dynamics in LLM Recommendation Systems

**链接**: https://arxiv.org/abs/2606.17443
**作者**: Xi Chu, Yupeng Hou
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [242] Persistent LLM Orchestration of Heterogeneous Robot Teams via Partial Delegation to Multi-Agent Protocols

**链接**: https://arxiv.org/abs/2610.15224
**作者**: Maria G. Mendoza, Victoria M. Tuck, Zachary Ravichandran, Shankar Sastry, and George J. Pappas
**来源**: cs.MA cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language specifications let non-expert users task robot teams, and large language models (LLMs) have recently proven effective at grounding such semantic specifications into plans for heterogeneous teams. Existing approaches assume missions that terminate and environments that, while unknown, do not change, but both assumptions fail in many emerging applications. For example, a disaster-response mission does not terminate, and its environment changes continuously as hazards spread and evacuees move. We identify three ways an LLM orchestrator breaks in this setting: its prompt grows without bound, its reasoning degrades as agents and targets accumulate, and it stops actively monitoring after covering the search space once. We build on the successful framework of grounded generative intelligence, and address each issue with a classical idea. A Markovian state summary, rebuilt from the semantic map at every invocation, replaces the growing interaction history. Partial delegation l

---

### [243] Iterate on an LLM, Serve on an SLM

**链接**: https://arxiv.org/abs/2610.14576
**作者**: Keegan Wang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As frontier LLMs gain more capabilities, the cost to run them also goes up. At the same time, small language models (SLMs) also gain more capabilities but have largely been able to keep their cost stable, offering 5-40 times cheaper inference for the narrow, repetitive subtasks that agents decompose work into. However, the standing limiting factor is getting the correct behavior out of a small model in a fast, efficient, and economical way. Unfortunately, in most cases, zero-shot small models fail narrow production tasks. Furthermore, retraining one every time the behavior changes is too slow to iterate on. We propose doing both in sequence. First, develop the desired behavior in prompt space, on a frontier model, with immediate feedback from live traffic. Then, once the behavior converges, distill the recorded production behavior (not synthetic imitations of it) into an SLM through supervised fine-tuning (SFT). We show a proper use case of this method through a scheduling agent for ho

---

### [244] CoMIC: Collaborative Memory and Insights Circulation for Long-Horizon LLM Agents in Web Cloud-Edge Systems

**链接**: https://arxiv.org/abs/2606.00756
**作者**: Yannan Wang, Longli Yang, Zhen Liu, Abhishek Kumar, Carsten Maple
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [245] REA: From Correct LLM Judgments to Safe Decision Delivery

**链接**: https://arxiv.org/abs/2610.17473
**作者**: Jingxiang Meng, Aofan Liu, Yaoshuai Ma, Fangxin Liu, Yongbiao Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative safety guards must classify requests correctly and return outputs that applications can parse. Reasoning guards can improve classification accuracy while producing outputs that applications cannot parse. When applications cannot extract a correct prediction, fallback handling can allow harmful requests or block safe ones. We introduce Resolve--Express--Act (REA), a framework that traces judgments through parsing and fallback to application actions. Experiments on classifiers and safety guards show that correct predictions can appear in incorrectly formatted outputs. Parsing the safety verdict preserves the reasoning guard's accuracy advantage, while stricter explanation requirements reject additional correct predictions. Accepting formatting variations recovers most rejected correct predictions. Held-out tests confirm that output requirements and generation limits affect whether correct predictions can be parsed. In our fail-open replay, matching the parser to the output and

---

### [246] Structure vs. Chain-of-Thought: Evaluating LLM Criteria Extraction for Depression Severity

**链接**: https://arxiv.org/abs/2609.39049
**作者**: Xinkai Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [247] ChronoScribe: Semantic-Numerical Specialization for Instruction-Driven Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.16345
**作者**: Yuchen Jiao, Miao Zhang, Yuxuan Liu, Chengxi Li
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in instruction-driven time series forecasting highlight a fundamental tension: systems must simultaneously master natural-language instruction following and precise numerical prediction. Current approaches often force a compromise. Large language models (LLMs) can interpret unstructured requests but may be inaccurate when asked to produce forecast values directly, whereas time series foundation models (TSFMs) provide numerical forecasts but typically require structured inputs specifying the target series, context window, and horizon. We present ChronoScribe, which applies semantic-numerical specialization to this workflow. A LoRA-adapted LLM proposes an execution path and context length; deterministic rules resolve the executable configuration. On the specialist path, a frozen TSFM produces quantile trajectories for the task-specified horizon. Deterministic trajectory summaries condition the response, while the LLM neither generates nor revises predicted values. We eval

---

### [248] Feedback as an Interface: Controlling Form and Detail in LLM Translation Refinement

**链接**: https://arxiv.org/abs/2610.15661
**作者**: Yiqi Liu, Flavjo Tomori, Nafise Sadat Moosavi, Steffen Eger, Chenghua Lin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feedback presentation shapes how LLMs use evaluator judgments during translation refinement. We introduce a machine translation protocol that keeps the evaluator score, main issue, and recommendation fixed while varying feedback form and supporting detail. Across seven models and six translation directions, low-load feedback outperforms high-load feedback in all 42 translator-direction settings under xCOMET. On the 29,400-record rewriting subset, mean xCOMET scores multiplied by 100 are 83.30 for low-load feedback and 80.67 for high-load feedback; the full-matrix original-translation reference mean is 83.46. MetricX-24 supports the low-load advantage on a stratified subset. A no-feedback second pass yields a small improvement over the original translations, and direct evaluator prompting reproduces the low-load advantage without a separate rewriting stage. These results show that compact feedback limits the quality loss from evaluator-guided refinement in the evaluated high-resource MT

---

### [249] EAIR: Interaction Risks in Enterprise LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.14800
**作者**: Yuchen Ma, Swadheen Shukla, Paulo Salem, Yue Huang, Robert Sim, Stefan Feuerriegel 等 (8 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly divide enterprise work across roles with different goals, authority, access, and information. Because each agent often sees only a local snapshot of the enterprise workflow, locally reasonable actions can still violate organization-wide constraints (e.g., several service agents can each issue credit that is individually permitted while collectively exceeding a shared compensation cap). We introduce EAIR, the first framework for analyzing enterprise multi-agent interaction risks. We make four contributions. (1) We formalize enterprise interaction risk in terms of the organizational properties that workflow operations must preserve, and operationalize this formulation as a taxonomy of testable risks with explicit failure criteria and evidence requirements. (2) We build EAIR-Worlds, a suite of executable micro-worlds that instantiates selected risks as controlled, observable workflows with explicit roles, policies, permissions, source facts, and execution traces. (

---

### [250] Compare to Correct: Pairwise-Guided Logit Adjustment for LLM Test-Time Scaling

**链接**: https://arxiv.org/abs/2610.18583
**作者**: Cong Hua, Qianqian Xu, Zitai Wang, Zhiyong Yang, Shilong Bao, Linchao Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sampling-based test-time scaling enhances LLM reasoning by aggregating multiple reasoning paths for the same query. Existing methods use answer frequencies or path confidence to compute candidate scores, which do not explicitly characterize comparisons between competing answers. Inspired by the Condorcet principle in social choice theory, we introduce pairwise confidence comparisons between paths supporting different answers to capture answer-level comparative advantage. We combine this comparative evidence with voting support through a KL-regularized objective. Theoretically, we show that this comparative-advantage is equivalent to the adjustment to the traditional voting logits. In this way, our proposed Pairwise-Guided Logit Adjustment (PGLA) framework allows comparative evidence to compensate for weaker voting support and correct voting-based ranking errors. Experiments on 10 challenging benchmarks including mathematical reasoning, knowledge reasoning, and code generation with 7 mo

---

### [251] HALLMARK: How to Diagnose LLM Citation Verifiers and When to Deploy Them

**链接**: https://arxiv.org/abs/2607.18360
**作者**: Kayoon Kim, Wieland Brendel, Patrik Reizinger
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [252] Anchor-and-Harvest Curriculum: A Fully Unmasked Non-LLM Curriculum for Craftax

**链接**: https://arxiv.org/abs/2610.15328
**作者**: Jiayu Zhu, Luyuan Li, Yuyuan Shi, Hanyi Dong
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Anchor-and-Harvest Curriculum (AHC), a domain-informed, rule-based training system for Craftax-Full. AHC combines achievement-oriented tasks, harvested initial-state progress, difficulty adaptation, bounded selection, and original-task practice. It uses no LLM inference and keeps all 43 actions available. At 2,005,401,600 PPO rollout transitions, three primary AHC runs obtain native-task return $46.70\pm0.57$ (sample SD), compared with $41.91\pm1.01$ for fresh native PPO-GTrXL with the same student architecture and evaluation protocol. Evaluation uses ten stochastic rollouts on each of 1024 fixed worlds per model. An additional cohort of three AHC runs reaches $46.08\pm1.23$. Two single-component ablations retain similar mean returns, while jointly freezing difficulty and removing inherited progress gives $45.14\pm2.79$. All-67-achievement profiles show that most of the return difference comes from Intermediate achievements, while the deepest-floor achievements remain unso

---

### [253] VibeServe: Can AI Agents Build Bespoke LLM Serving Systems?

**链接**: https://arxiv.org/abs/2605.06068
**作者**: Keisuke Kamahori, Shihang Li, Simon Peter, Baris Kasikci
**来源**: cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [254] Preemptive LLM Unlearning against Forbidden Capability Acquisition via Gradient Sealing

**链接**: https://arxiv.org/abs/2609.39866
**作者**: Kemou Li, Qizhou Wang, Yue Wang, Fengpeng Li, Zhuan Shi, Negar Rostamzadeh 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [255] Calibrating LLM Explanations to Human Decisions with Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.17306
**作者**: Dong Shu, Ziyang Guo, Negar Kamali, Matthew Groh, Jessica Hullman
**来源**: cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Explanations of LLM outputs are considered an important way to make model behavior legible, helping human users make good decisions on downstream tasks. However, default training approaches for improving explanations target model task performance or human preference rather than human decision quality. To bridge this gap, we introduce \textbf{HD-RL}, a reinforcement learning framework for optimizing LLM explanations for human decision making. Our approach calibrates a human decision simulator on observed human decisions, applying a proxy reward model to optimize the LLM to generate explanations that help people to make good decisions. We apply this framework to AI-generated text detection. In our initial data collection phase, we observed that while LLMs possess strong autonomous detection capabilities, the explanations they generate for users yield near-random human accuracy (51.3\%). By applying the HD-RL framework to the open-source Qwen 3.6 model, we generate optimized explanations 

---

### [256] When Agents Commit Too Soon: Diagnosing Premature Commitment in LLM Agents

**链接**: https://arxiv.org/abs/2606.22936
**作者**: Aman Mehta, Anupam Datta
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [257] The Fragility and Dynamics of LLM Pruning-Recovery Steps

**链接**: https://arxiv.org/abs/2610.15574
**作者**: Luis Frentzen Salim, Komang Rinartha, Chia-Chun Wu, Tran Van Nhiem, Lun-Wei Ku, Yung-Hui Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structural pruning followed by a recovery stage is the standard recipe for compressing large language models (LLMs), yet the two stages are typically designed and tuned in isolation. In this work, we study how their interaction shapes the compressed model, sweeping ordering, the data that drives each stage, and the alignment of their training objectives. We find that instruction-following is the first capability to collapse under pruning, well before knowledge, reasoning, or core language modeling, and that much of the pruning in-domain loss is likely not knowledge loss but a domain-agnostic failure to respond coherently to the prompt. We find in our setting that in-domain data is the strongest pruning signal, whereas instruction-style data recovers the most. Stage order matters little, but only marginally. We further analyze how the importance ranking drifts before and after pruning. Together these results give practitioners a concrete recipe for composing pruning and recovery.

---

### [258] Towards Green AI: Evaluating Energy Efficiency for Quantized LLM Inference

**链接**: https://arxiv.org/abs/2610.17531
**作者**: Petar Basta
**来源**: cs.LG cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While it is known that quantization of large language models (LLMs) reduces memory usage via lower-bit weights, studies quantifying the resulting impact on energy usage and carbon intensity are scarce. We present the first unified evaluation of weight-only quantization strategies for LLM inference across varying input/output lengths and GPUs, highlighting differences in energy efficiency in addition to accuracy degradation and runtime. We study quantized inference on Llama 2 7B, Phi 3.5 Mini Instruct, OLMo 1B, Qwen 2.5 7B, and Qwen 2.5 14B across GLUE MNLI, MMLU, HumanEval, and GSM8K datasets, evaluating 10 post-training quantization (PTQ) strategies on NVIDIA H100, A6000, A100, and L4 GPUs. We identify a novel trend showing that quantization techniques tend to exhibit peak energy efficiency relative to full-precision baselines when inputs are sufficiently long and outputs are short. Furthermore, we show that quantization strategies become marginally more energy-efficient relative to f

---

### [259] Measuring all the noises of LLM Evals

**链接**: https://arxiv.org/abs/2512.21326
**作者**: Sida I. Wang
**来源**: cs.LG cs.AI cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [260] Where Did We Go Wrong? Localizing Errors to Repair Multi-Turn Conversations

**链接**: https://arxiv.org/abs/2610.15154
**作者**: Alessandro Morosini, Wei Sun, Georgia Perakis
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) assistants are increasingly used in multi-turn conversations, where the user's intent is often unclear at first and revealed only gradually over time. The assistant must therefore interpret each exchange and form inferences about the user's intent, using them to update its working state. These updates usually refine the assistant's understanding, but a misinterpretation can instead corrupt its working state by ruling out the true intent, influencing subsequent turns and ultimately causing the conversation to fail. Efficient recovery then requires locating and revising the misinterpretation without discarding information that remains valid. We introduce Loci (Localization Of Corrupted Inferences), a framework for probabilistically localizing misinterpretations and selectively repairing the assistant's working state. Given an observed failure, Loci reasons over possible user intents and assigns each update a probability of having excluded the true intent. These

---

### [261] RelLedger: Relational Information Governance for LLM Agent Organizations

**链接**: https://arxiv.org/abs/2610.16281
**作者**: Junxi Huang, Wenshuo Chen, Nuoxuan Li, Kailong Wang, Meitong Shen, Yuehan Kou 等 (10 人)
**来源**: cs.MA cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In LLM agent organizations, shared records determine which facts are available for later decisions. A sender consults interaction histories before deciding whether to report an event. A delivery gap across histories does not show whose relationship drove the choice or whether the resulting record matters downstream. We introduce RelLedger to audit these links. It holds the event, evidence, risk, and message fixed while crossing the sender's histories with the event target and an unrelated actor. Role reassignment and history rewrites locate the controlling cue. Message and cost interventions show when the effect appears. An attribution ledger maps each claim to its required response cells and separates missing interventions from sampling uncertainty. Recipient replay follows delivered information into downstream decisions. Executable workflows for a simulated one-person company extend the audit to retrieved histories, tool calls, and shared ledger updates. Across GPT, Gemini, Claude, D

---

### [262] SlideDP: Scaling Host-Resident LLM Fine-Tuning Across Multiple GPUs

**链接**: https://arxiv.org/abs/2609.34162
**作者**: Ruijia Yang, Shiyuan Lin, Yulong Ao, Zhiyu Li, Yingli Zhao, Xianduo Li 等 (8 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Host-resident layer streaming enables full-parameter LLM fine-tuning beyond GPU memory, but data-parallel ranks compete for shared host resources. Replicated transfers amplify traffic, while strong scaling can expose host work as computation windows shrink. We present SlideDP, a synchronous data-parallel runtime for shared-host multi-GPU systems. It maintains one authoritative host state, decouples communication routes from state layout, and pipelines parameter delivery, gradient aggregation, and CPU updates across ranks and chunks. An analytical step-time model characterizes resource bottlenecks and pipeline exposure; runtime measurements guide communication, chunking, and activation policies under a GPU memory budget. In matched-batch sweeps, SlideDP achieves geometric-mean throughput ratios of 1.46-2.64$\times$ over SlideFormer, MegaTrain, and ZeRO-Offload. On four H100s, SlideDP approaches GPU-resident FSDP2 throughput for Qwen3-14B at a smaller batch size. With a larger batch, it 

---

### [263] Cost-Efficient Privacy Enforcement for Email-Generating LLM Agents under Strategic Information Requests

**链接**: https://arxiv.org/abs/2610.18007
**作者**: Qikun Cai, Tao Huang, Chen Hou
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents now act as delegated communication intermediaries: they read private context, draft messages, and send externally visible emails on behalf of a user. Existing checker-repair defenses can reduce inappropriate disclosure, but they rely on repeated calls to a remote action LLM (the model that drafts and repairs the email) and a remote checker LLM whenever a draft fails validation. This creates a cost problem as well as a privacy problem, especially when a requester strategically asks for exact values, raw records, source evidence, or other details that induce leakage-heavy drafts. We propose local contract-conditioned rewriting as a cost-efficient enforcement layer for email-generating agents. The mechanism intercepts an outgoing draft, constructs an information-release contract that specifies what to preserve, generalize, and forbid, rewrites the draft with a local Gemma rewriter, and selectively invokes a final PrivacyChecker. Across extensive email tasks under normal prompts

---

### [264] AutoMARS: Automatic and Scalable Multi-Agent Large Language Model Framework for Supply Chain Risk Assessment

**链接**: https://arxiv.org/abs/2610.17206
**作者**: Yinzhu Quan, Zefang Liu, Frederick Benaben, Benoit Montreuil
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose AutoMARS (Automatic Multi-Agent Risk Assessment), an agentic framework for automatic and scalable comparative risk assessment in supply chain networks. The framework enables end-to-end execution of analytical workflows by automatically planning tasks, coordinating specialized agents, invoking external analytical tools, and synthesizing domain-specific results into integrated risk evaluations. AutoMARS further supports scalable risk comparison across multiple locations by parallelizing independent analytical tasks. The framework adopts a multi-domain, multi-agent, and multi-tool architecture that integrates heterogeneous risk factors from socioeconomic, disaster, environmental, and transportation domains. Through coordinated agent interactions and tool integration, AutoMARS enables structured, systematic, and interpretable comparative analysis to support supply chain risk-aware location evaluation.

---

### [265] Do You Even Need More Data? Rethinking LLM Deployment for Label-Scarce Tabular Classification with TabLens

**链接**: https://arxiv.org/abs/2605.24417
**作者**: Daria Grushina, Kseniia Kuvshinova, Alina Kostromina, Aziz Temirkhanov, Mile Mitrovic, Dmitry Simakov
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [266] Personalized LLM Recommendation with Semantic IDs: Autoregressive Beam Search vs. Multi-Token Prediction

**链接**: https://arxiv.org/abs/2610.15864
**作者**: Sejoon Oh, Fernando Amat Gil, Evan Smothers, Dan Iter, Mark Thornburg, Dawit Mureja Argaw 等 (10 人)
**来源**: cs.IR cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale personalization is shifting from embedding-table retrieval to LLM-based recommenders that generate the Semantic ID (SID) of the item to recommend, where each SID is a short sequence of discrete hierarchical content codes. A single instruction-tuned model can then unify retrieval, content understanding, and language, and recommend brand-new titles from their content alone using SID; then, how should the model generate the SID? Traditionally, models rely on a single language modeling head that generates tokens autoregressively, typically using constrained beam search. In contrast, an emerging body of work explores multi-token prediction (MTP), where dedicated heads predict all tokens in parallel, substantially reducing the decoding latency associated with beam search. We report an industry-scale, apples-to-apples comparison of these two generation paradigms: single-head autoregressive decoding vs. MTP. We introduce a new auxiliary ranking loss, defined over the joint SID scor

---

### [267] Omni-RS: Unifying Multi-Task Understanding and Generation in Remote Sensing

**链接**: https://arxiv.org/abs/2610.18323
**作者**: Pan Yin. Shuai Yang, Yuanhao Liu, Datao Tang, Jialin Li, Hao Wang, Pei Liu 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practical remote sensing applications often require both understanding and generation capabilities for the same geographic scene. However, most existing methods address either understanding or generation in isolation, while existing unified remote sensing models' generative ability is limited to text-to-image. To bridge this gap, we propose Omni-RS, a unified framework supporting four remote sensing understanding tasks and five generation tasks. Specifically, we introduce the "Scene-Guided Two-Stage Training" strategy, which first adapts a multimodal large language model to remote sensing understanding and then uses its hidden states to guide a diffusion transformer for image generation. To enable joint learning across diverse generation tasks, we construct UniGen, a unified multi-task generation dataset, by organizing heterogeneous remote sensing data into a unified format. Furthermore, we introduce "Detailed Visual Conditioning", which uses visual conditions encoded by a VAE to guide

---

### [268] REPRO: Reflective Evolutionary Prompt Optimizer for Automated LLM Red-Teaming

**链接**: https://arxiv.org/abs/2610.15513
**作者**: Abrar Alotaibi and Moataz Ahmed
**来源**: cs.CL cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety-aligned large language models (LLMs) remain vulnerable to adversarial prompts that bypass their safety training. Existing automated red-teaming methods either require privileged access unavailable in production, rely on manually engineered per-model templates, or optimize a single objective without population-level diversity. We present REPRO (Reflective Evolutionary Prompt Optimization), a pure black-box framework that discovers adversarial prompts through evolutionary optimization driven entirely by a compressed open-weight 7B reflective model on a single consumer GPU. REPRO introduces two mechanisms absent from prior work, both isolated in a component ablation: semantic crossover, an LLM-guided multi-parent recombination operator, and Bayesian strategy selection via Thompson Sampling informed by structured failure analysis. We catalog REPRO's behavior on AdvBench, JailbreakBench, and HarmBench across 36 target models from 11 families, including GPT-5-nano, Claude-3.5-Sonnet, 

---

### [269] MIND: Lightweight and Effective Memory Injection Defense for LLM Agents via Intent-Aware Information Bottleneck

**链接**: https://arxiv.org/abs/2607.28103
**作者**: Dongyi Liu, Haixing He, Xiaobao Wu, Jia Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [270] Conflict-Aware Autonomous Resource Orchestration for 5G Edge Slicing Using Multi-Agent Systems and LLMs

**链接**: https://arxiv.org/abs/2610.14903
**作者**: Nathan R. Prediger, Rodrigo Moreira, Juliano Araujo Wickboldt, Tereza C. Carvalho, Pedro Oliveira, Paulo Novais 等 (7 人)
**来源**: cs.NI cs.DC cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 5G edge network slicing must reconcile two coupled requirements: understanding high-level operator intent and reallocating scarce computing and bandwidth resources under dynamic contention. Centralized optimization can face computational and responsiveness challenges under rapidly changing edge contention, and Multi-Agent System (MAS)-based auctions can support resource arbitration but still depend on operator-defined economic parameters and priorities. Embedding a Large Language Model (LLM) directly in a recurring control loop, by contrast, may introduce non-negligible inference latency and non-deterministic behavior. This paper proposes a two-timescale architecture that addresses this gap: an LLM-based Strategist translates natural-language network intents into economic policy parameters (budget, income, and bidding-aggressiveness) at the macro scale, while a deterministic, Vickrey-inspired second-price mechanism run by SPADE-based slice agents resolves recurring resource contention 

---

### [271] GA-SVD: Generation-aware Singular Value Decomposition for LLM Compression

**链接**: https://arxiv.org/abs/2610.15398
**作者**: Shengkun Tang, Cong Zeng, Zongfang Liu, Dan Alistarh, Zhiqiang Shen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) demonstrate strong generalization across a broad range of reasoning and generation tasks, but their large parameter counts impose substantial memory and computation costs, hindering deployment in practical resource-constrained settings. One-shot low-rank compression is a promising solution since it reduces model size and inference cost effectively. However, existing SVD-based methods primarily target multiple-choice benchmarks and often fail to preserve performance on generation tasks. Moreover, their rank allocation strategies are typically heuristic. We propose GA-SVD, a generation-aware low-rank compression framework for LLMs. First, we introduce Generation-Aware Weight Whitening (GAWW), which leverages gradients from on-policy knowledge distillation to construct whitening transformations aligned with generative behavior. Second, we develop an evolutionary global rank allocation method that searches for effective layer-wise rank allocation under a given 

---

### [272] Selective Latent Thinking: Adaptive Compression of LLM Reasoning Chains

**链接**: https://arxiv.org/abs/2605.25745
**作者**: Hui Xie, Jie Liu, Ziyue Qiao, Joaquin Vanschore
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [273] Mission-Level Runtime Assurance for LLM-Assisted ISR Swarms over a Verification-Aware Fabric

**链接**: https://arxiv.org/abs/2607.23532
**作者**: Nikolaos Kekatos, Michael Ioannou, Panagiotis Katsaros, Alexios Lekidis, Theodoros Nestoridis, Tom Nianios 等 (7 人)
**来源**: cs.CR cs.AI cs.LO cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [274] LLM Judges Have Dark Current: Stratified Null and Utility Tests for LLM Judge Reliability

**链接**: https://arxiv.org/abs/2606.15610
**作者**: Hiroyasu Usami, Keisuke Hara, Ayato Tsuboi, Naohiko Matsuda
**来源**: cs.CL astro-ph.IM cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [275] Security in LLM-Assisted Coding: A Systematic Literature Review

**链接**: https://arxiv.org/abs/2610.15482
**作者**: Liang Yuan, Maryam Khanian Najafabadi, Mashud Rana, Varvara Vetrova
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models accelerate software development but introduce severe security vulnerabilities. This systematic review investigates security risks in automated coding, benchmark limitations, and the role of human developers. Findings indicate that models frequently generate insecure code and faulty patches due to training data biases. Additionally, the models themselves are susceptible to direct attacks. Current evaluation methods suffer from data contamination and lack robust security metrics. Consequently, human oversight remains essential. Safer integration of automation will require more security-aware model architectures, stronger security-specific benchmarks, and more effective human-AI collaboration frameworks to mitigate these systemic risks.

---

### [276] MAS-Gate: Unlocking Multi-Agent System Lifecycle via Node-Centric Quantification

**链接**: https://arxiv.org/abs/2610.17613
**作者**: Hehai Lin, Zixuan Wang, Ming Yan, Peidong Wang, Shilei Cao, Minzhi Li 等 (9 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) can solve complex problems beyond the reach of a single agent by decomposing tasks and coordinating complementary capabilities. Despite extensive research on MAS, existing work largely focuses on specific aspects or individual phases of their development and operation, resulting in fragmented perspectives with objectives and signals that are difficult to reconcile across these different settings. To bridge these disconnected perspectives, we conceptualize MAS development and operation as a three-phase lifecycle spanning design-time orchestration before execution, runtime intervention during execution, and post-hoc attribution after execution, and introduce MAS-Gate, a unified node-centric quantification applicable across these phases. Modeling each execution as a directed acyclic graph, MAS-Gate combines within-node utility, which estimates a node's contribution through changes in reference-answer likelihood, with inter-node st

---

### [277] ZOIF: Zeroth-Order Influence Function Estimation for LLM Data Selection Using Only Forward Passes

**链接**: https://arxiv.org/abs/2610.15336
**作者**: Lisong He, Yunxuan Jiang, Haishan Ye, Xiangyu Chang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Influence functions enable principled data selection for large language models (e.g., identifying influential training samples for model editing, debugging, or efficient fine-tuning). However, scaling IFs to LLMs is hindered by the intractability of billion-scale Hessian matrices and the prohibitive memory overhead of backpropagation (BP). While many classical IF approximations reduce Hessian complexity, they still rely on BP for gradient computation, requiring massive storage for intermediate activations that impedes practical data selection at scale. To address this, we propose ZOIF, a zeroth-order framework for influence estimation that operates entirely via forward passes, enabling memory-efficient data selection under resource constraints. ZOIF decomposes influence estimation into three BP-free stages: (1) approximating the average proxy gradient via zeroth-order estimation; (2) reformulating and solving the inverse Hessian-vector product as an auxiliary zeroth-order optimization 

---

### [278] Autoregressive Decoding as a Martingale: Characterizing the Stochastic Dynamics of LLM Generation

**链接**: https://arxiv.org/abs/2610.16041
**作者**: Xiahui Zhu, Zhenyi Qi, Wanwei Liu, Haoang Chi, Yang Tan, Xinyu Sun 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have achieved remarkable success across a wide range of language tasks. At their core, autoregressive LLMs are conditional probability models that learn to approximate the next-token distribution given the preceding context. Despite this probabilistic nature, the stochastic dynamics of autoregressive decoding have rarely been investigated from a rigorous probabilistic perspective. In this work, we define the per-step prediction error as the difference between the sampled token indicator and the model's conditional predictive distribution, and prove that the cumulative error process is a martingale with respect to the decoding filtration, implying that its conditional first-order moment is identically zero. Beyond this first-order property, we derive a closed-form expression for the second-order behavior of the martingale sequence: its predictable quadratic variation reduces to $\sum_t\left(1-p(y_t\mid y_{<t})\right)$, computable from realized token probabil

---

### [279] Same Request, Different Answer: Quantization Amplifies Cache-Induced Divergence in LLM Serving

**链接**: https://arxiv.org/abs/2609.04748
**作者**: Aditi Patodiya
**来源**: cs.SE cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [280] Narrative Paradoxes in LLM Inference: Shaping Reasoning Trajectories toward Misalignment

**链接**: https://arxiv.org/abs/2610.16312
**作者**: Haoming Yang, Ke Ma, Yangbangyan Jiang, Ligong Zhang, Xiaojun Jia, Longtao Huang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Explicit reasoning in large language models (LLMs) is often associated with reliability, yet it can still pose risks when a model infers harmful goals under a benign context. We identify a distinct challenge: ensuring the safety of the \emph{multi-step reasoning process} itself, where locally coherent steps may still lead to globally harmful outcomes. To explore this vulnerability, we propose PDRA (Paradox-driven Reasoning-based Attack), a novel attack method that programs a harmful reasoning trajectory. PDRA first constructs a paradoxical narrative core by pairing a malicious actor (e.g., a terrorist) with a benign task (e.g., writing a safety bulletin). It then embeds this core into a structured analytical framework that forces the model through a mandatory three-stage analysis -- surface purpose, latent intent, and operational reconstruction -- guiding it to produce detailed harmful content while maintaining narrative coherence. Mechanistically, we show PDRA steers the model's inter

---

### [281] Where Do LLM Ensemble Gains Come From? Decomposing Candidate Value, Diversity, and Aggregation

**链接**: https://arxiv.org/abs/2610.18786
**作者**: Donghwan Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM ensemble gains are often measured against a single baseline, but the value attributed to additional candidates can change with the comparison used. We study an LLM aggregator under four matched conditions: Direct (no candidates), Single-slot (one candidate in a multi-slot interface), Duplicate (one candidate repeated), and Multi-candidate (separately generated candidates). Under either non-diverse control, overall candidate gain (CIV) splits algebraically into an additional-candidate contrast (DSV) and a candidate-context contrast (CCV); the split, but not CIV, depends on the chosen control. On MultiHopRAG model diversity (k=2), the repetition gap Rep=-8.33 pp [-13.25, -3.75] quantifies the difference between gains measured against Duplicate and Single-slot. On a matched FRAMES stronger-panel extension (n=200, k=3, aggregator output limit 4096), paired Delta Rep=+9.67 pp [+6.00, +13.50]; within panels, Rep changes sign (original -6.33; stronger +3.33). In FRAMES evidence aggregatio

---

### [282] Scalable Weak-to-Strong Verifier Hardening for Agent Environments

**链接**: https://arxiv.org/abs/2610.15924
**作者**: Chong Zeng, Ziqian Zhong, Kexun Zhang, Ivan Bercovich, Ivgeni Segal, Yuzhen Mao 等 (8 人)
**来源**: cs.CR cs.AI cs.LG cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent environments are essential for large language model (LLM) development. They use programmatic verifiers to turn complex outcomes into rewards. Verifiers can be attacked into awarding full credit to cheating agents without completing the intended task, causing inaccurate evaluation and misalignment in training. As agent environments scale in numbers and difficulty, so must the repairing of exploitable verifiers. To this end, we ask whether today's model with scaled compute can automatically harden agent environments to prevent potentially stronger future models from reward hacking. We introduce a scalable, fully automatic approach to weak-to-strong verifier hardening. It first sets up an isolated verifier sandbox that agents cannot directly modify, then uses a hacker-fixer loop to find and repair remaining verifier vulnerabilities. We apply this loop to Terminal Bench, KernelBench, and SETA, substantially reducing attack success across these agent environments. The iterative design

---

### [283] ToolHACE: A Dataset for Detecting Hallucinations in Tool-Based LLM Responses

**链接**: https://arxiv.org/abs/2610.17125
**作者**: Nikolay Ivanov, Sergey Pletenev, Elisei Rykov, Anatolii Frolov, Bogdan Monogov, Alexander Potekhin 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-augmented language models ground their responses in external tool outputs, improving reliability beyond parametric knowledge alone. However, even when the correct tool is called and returns accurate information, models may still contradict such outputs, omit critical details, or generate unsupported claims. Existing hallucination benchmarks for tool-augmented dialogue primarily focus on the tool-calling stage, evaluating whether the correct tool and arguments are selected, while overlooking errors that arise during post-tool response generation. To address this gap, we introduce ToolHACE, a span-level benchmark for hallucination detection in tool-augmented LLM responses, covering five fine-grained hallucination categories. Through extensive experiments with modern hallucination detectors, we show that post-tool-call hallucinations are widespread and remain challenging to detect. Our results further demonstrate that effective detection requires training on specialized tool-augmente

---

### [284] Monitoring and Discovering Reward Hacking with Internal Representations during LLM Evaluations

**链接**: https://arxiv.org/abs/2609.19101
**作者**: Leon Bergen, Usha Bhalla, Andrew Lee, Barak Widawsky, Linas Nasvytis, Connor Watts 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [285] RogueMerge: Robust and Unified Attacks against LLM Model Merging

**链接**: https://arxiv.org/abs/2606.03344
**作者**: Jinghuai Zhang, Yetian He, Kunlin Cai, Han Zhao, Fnu Suya, Yuan Tian
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [286] Clean: Second-order LLM Training at Linear Memory Cost via Nystr{\"o}m Sketching

**链接**: https://arxiv.org/abs/2610.04204
**作者**: Beheshteh T. Rakhshan, Sahar Rajabi, Maziar Sargordi, Shikai Fang, Guillaume Rabusseau, Sirisha Rambhatla
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [287] Artificiality's First Exam: An LLM-Referenced C-test for Supraintelligence

**链接**: https://arxiv.org/abs/2610.14005
**作者**: Jose Hernandez-Orallo
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Under the accelerated pace of AI development, any benchmark whose difficulty is calibrated with humans or current AI systems becomes circular, or saturates soon. How can we then evaluate machines that may become more capable than the current machines and the people who write the tests? One answer to the question hinges on inverse problems, inductive inference questions for which difficulty depends on the complexity of the underlying mechanism, given the observations and the previous knowledge. Levin's Kt, a computable variant of Kolmogorov complexity, puts a theoretical upper bound to that difficulty, balancing the simplest representation encoding for the mechanism and the logarithm of the time steps to run that mechanism. Previous tests derived from Levin's Kt, such as the original C-test, are based on minimalistic Universal Turing Machines (UTM), capable of very limited representations and no previous knowledge. Reasoning large language models (LLM) are UTMs that capture a compendium

---

### [288] Beyond Outcome Feedback: Trajectory-Quality-Guided Experience-based Learning

**链接**: https://arxiv.org/abs/2610.14877
**作者**: Bingjie Zhang, Yibo Yang, Qiantong Liu, Benshuo Fu, Yi Chang, Dandan Guo
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experience-based learning enables large language model (LLM) agents to improve over time by reusing knowledge from past executions. However, existing methods typically rely on final task outcomes as feedback for experience learning, overlooking the execution process and limiting their ability to evaluate and optimize experience based on trajectory quality. To address this limitation, we propose TQG-Exp, a trajectory-quality-guided experience-based learning framework that introduces process feedback. Specifically, we introduce Trajectory Quality Loss (TQL), which jointly considers task completion and process quality to provide a learning signal beyond final task outcomes. Based on this signal, we employ paired rollouts with and without retrieved experience to guide experience optimization. Representative trajectories are selected based on their outcomes and trajectory quality to extract task-level and task-type-level experiences. Meanwhile, differences in trajectory quality between the 

---

### [289] Revisiting Natural Language Prompts from Large Language Models for Open-Vocabulary Video Recognition

**链接**: https://arxiv.org/abs/2610.16666
**作者**: Haichen He, Weibin Liu, Weiwei Xing
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) like CLIP have shown great success in image tasks, however, applying CLIP to open-vocabulary video recognition poses challenges. Due to the limited text information, directly fine-tuning CLIP on video recognition datasets may lead to overfitting and hinder its generalizability. A prevalent method is to enrich text information by generating prompts using Large Language Models (LLMs). However, limited efforts have been made to explore how to generate higher-quality prompts that can contribute to classify unseen categories, and how to further enhance vision-text alignment based on these prompts. In this paper, we propose P2CLIP (Prompt-guided CLIP), which aims to bridge this gap by exploring the impact of prompts across three aspects: category, video, and frame. At the category level, we argue that LLM-generated prompts under simple instructions may suffer from semantic overgeneralization, which can blur the category boundaries and hinder the performance of t

---

### [290] Beyond Answer Sharing: TrueMAD for Targeted Peer Engagement in Multi-Agent Debate

**链接**: https://arxiv.org/abs/2610.18240
**作者**: Dezheng Bao, Sihang Du, Renhong Huang, Zhizhang Yuan, Yifei Sun and Yang Yang
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent debate (MAD) aims to improve large language model reasoning by exposing agents to alternative solutions and enabling iterative revision. However, standard broadcast-style MAD makes peer answers visible without requiring agents to engage with a particular peer claim. As a result, reliable reasoning may be suppressed by conflicting or majority responses, limiting achievable performance, while erroneous reasoning may persist and degrade final predictions without actionable feedback. We propose TrueMAD, a backbone-agnostic test-time plug-in that introduces one-to-one, free-form peer advice between answer broadcasting and self-revision. Each source agent responds to a target's current reasoning through support, rebuttal, refinement, or further questions, while the target retains control over how to revise. The same mechanism can augment standard MAD and its improved variants without parameter updates. Across AIME, GPQA-Diamond, and TruthfulQA with Qwen3-30B-A3B, TrueMAD improves

---

### [291] Swarm Telepathy: Prefill-Free KV-Cache Transfer Across Families

**链接**: https://arxiv.org/abs/2610.15095
**作者**: Abdulrahman Alabdulkareem, Irene Tenison, Yang Zhang, Yada Zhu, Boris Katz and Dan Gutfreund
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM multi-agent systems split work across agents that communicate through text. An agent summarizes its findings, another agent receives the text. This constrains communication to discrete tokens and costs redundant compute, limiting bandwidth and capabilities of multi-agent systems. Recent works demonstrate KV-cache transfer between LLMs but they either require the LLMs to be within the same family or cannot function across context, thus requiring the receiver to prefill text. We present SwaT (Swarm Telepathy), the first cross-family KV-cache transfer method that allows prefill-free communication in multi-family multi-agent systems. In an agent-to-agent communication setting, combining SwaT with recent advances in KV-cache compaction beats text-to-text communication in both accuracy and speed, with a mean of $40\%$ higher accuracy and a mean of $4\times$ faster wall-clock time. Experiments show SwaT achieves high performance on 17 benchmarks across 12 LLMs and 6 families. Additionally

---

### [292] What Survives When Activation Steering Is Used as Memory

**链接**: https://arxiv.org/abs/2610.14958
**作者**: Vedant Jumle
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering has recently been used as a memory for skills: past experiences of an agent are stored as steering vectors and retrieved later. Facts and preferences about the user are assumed to need text instead. We test that assumption with a training-free activation memory beside a frozen LLM. The change an experience causes in late-layer states is stored as a shift, filed under a whitened key for the conversation's gist, and added back in a later session only when the gist matches. We argue that such a shift is a fixed average of an effect that attention, in context, recomputes for every question, so only question-independent content can survive. In a pre-registered study on Qwen3.5-2B and 9B, with judges from four model families, the memory is selective (about 98% of unrelated replies are unchanged), but facts are stored as the word to say, in the last layers only, and are almost never used (at most 15% clean use, against 96-98% in context). Leanings transfer only in a narrow

---

### [293] Exploring Jailbreak Vulnerability Across Depth-Based Dynamic Inference in Large Language Models

**链接**: https://arxiv.org/abs/2610.15207
**作者**: Lass Najmuldeen, Seyedhamidreza Mousavi
**来源**: cs.LG cs.AI cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have been shown to be computationally expensive and vulnerable to jailbreak attacks, in which adversarial prompts bypass safety alignment and induce harmful responses. To address this inefficiency, a range of techniques have been proposed to enable efficient LLM inference. Depth-based dynamic inference has demonstrated promising results by enabling outputs to be generated from intermediate layers. It offers the flexibility to adjust model behavior based on the available resource budget. However, how this flexibility affects the robustness of LLMs against jailbreak attacks remains unexplored. In this paper, we address this gap via a comprehensive investigation into the impact of depth-based dynamic inference on the robustness of LLMs against jailbreak attacks. Specifically, we make the following key observations: 1) Shallow exits are consistently more robust to jailbreak attacks than deeper ones; 2) Exit depth affects how easily the adversarial suffix can be

---

### [294] Checking the Checkers: A Synthesis of Verifier Noise and Robustness in RLVR

**链接**: https://arxiv.org/abs/2610.17824
**作者**: Savyasachi Gupta, Aniruddha Srinivas Joshi
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning with verifiable rewards (RLVR) has become a principal recipe for improving the reasoning of large language models (LLMs). It rests on the assumption that the checker scoring each response is itself correct. In practice, rule-based checkers reject correct answers in unexpected formats, unit tests accept incorrect programs, and LLM judges can be led to approve empty or adversarial responses. This work surveys 58 studies that measure, analyze, or mitigate such verifier errors. We ask what errors verifiers make, how they affect training, which mitigations work against which errors, and how the findings extend to self-generated, rubric- and judge-based, and verifier-free rewards. The evidence suggests that the structure of an error matters more than its rate. Random errors mostly slow learning, though under a fixed budget or KL regularization they also lower final accuracy. False positives that the policy can learn to trigger can cause plateaus or collapse, sometimes 

---

### [295] Agent-Reflex: Teaching Language Agents to Act Reflectively

**链接**: https://arxiv.org/abs/2610.17953
**作者**: Guanting Dong, Xinyu Yang, Jiajie Jin, Yuyang Hu, Xiaoshuai Song, Yifei Chen 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have evolved from single-turn chatbots into interactive agents capable of long-horizon reasoning. In real deployments, MCP tool services can return noisy feedback and users may intervene to correct the agent, but existing methods provide limited supervision for reflection learning and failure recovery. To bridge this gap, we propose Agent-Reflex, a general training framework for incentivizing proactive reflection in agents. Specifically, Agent-Reflex comprises three stages. First, Environment Reflection Skill Discovery (RSD) injects grounded tool-feedback perturbations into environment scaling, samples a capability-diverse LLM pool, mines matched success-failure pairs, and summarizes reusable reflection meta-skills. Building on this skill library, we then apply Reflective Supervised Fine-Tuning (ReSFT) that converts each skill into supervision for self-reflection, skill recovery, and user-centric correction, strengthening complementary reflective behaviors. Finall

---

### [296] Information-Theoretic Foundations of Online Temperature Sampling

**链接**: https://arxiv.org/abs/2610.15043
**作者**: Jin Sima, Nikolaos Papagiannis, Ananth Grama, Wojciech Szpankowski
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Repetitive, degenerate generation is a persistent failure of LLM decoding, and the standard remedies (temperature, nucleus, and top-$k$ sampling) are static heuristics. By Kac's lemma and the AEP, a stationary source takes time exponential in its entropy to repeat a block. We therefore maximize the entropy of the sampling distributions under one cross-entropy budget that keeps the output plausible under the model. Offline, the solution is temperature sampling, with the inverse temperature as the budget's Lagrange multiplier. \emph{Our contribution is the online problem}: the conditionals $p_1, p_2, \dots$ are revealed one at a time, and the sampling distribution $q_t$ must be chosen causally from $p_1, \dots, p_t$ while the budget couples the entire horizon. The optimal temperature is thus a global shadow price that must be estimated from a prefix. We propose Entropic Online Sampling (EOS), which re-solves for the temperature on each prefix. We prove it loses $O(R\log n)$ entropy again

---

### [297] Have You Been Convinced? A Neuro-symbolic Argumentation Reasoning Approach to Detecting Persuasiveness in ChangeMyView Discussions

**链接**: https://arxiv.org/abs/2610.15091
**作者**: Siddharth Bhargava, Sara Tonelli, Patricia Mart\'in-Rodilla
**来源**: cs.CL cs.AI cs.SC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Argument structures represent how individual arguments interact within a discourse. However, leveraging these structures to infer meaningful knowledge remains challenging, as it requires a formal representation of how argumentative influence propagates across the structure. We propose Neuro-symbolic Argumentation Reasoning System (NARS) for performing persuasiveness detection directly from online discussions. The neural component employs retrieval-augmented iterative LLM reasoning to extract bipolar argument structures, while the symbolic component applies gradual argumentation semantics to propagate argumentative influence over the structure. Using the Webis-CMV-20 corpus, we construct CMV2BAS, a dataset of long, multi-threaded ChangeMyView discussions annotated with LLM-derived bipolar argument structures and labeled with delta events (view change vs.\ no change). We investigate whether gradual argumentation semantics can effectively detect persuasiveness, whether augmenting them wit

---

### [298] Harness^2: Recursive Agent Harnessing for an Open World

**链接**: https://arxiv.org/abs/2610.14224
**作者**: Ruiyao Xu, Yanfei Chen, Zhongying CuiZhu, Bhavana Dalvi Mishra, Yifei Ming, Han Yu 等 (9 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents' capabilities depend not only on their underlying models but also on their execution harnesses. Recursive self-improvement (RSI) offers a promising approach to automatically evolve these harnesses. However, deploying RSI in open-world settings still faces two critical challenges. First, open-world tasks are typically unseen during the harness design phase and novel at test time, leaving no ground-truth verifiers to reliably guide online harness edits. Second, the RSI process remains highly task-specific and fails to generalize to novel scenarios. We introduce Harness^2, a plug-and-play, recursive agent harnessing framework that addresses these challenges through two connected levels of recursion. Task-level recursion refines the current task's harness using a contrastive Propose-Probe-Compose step that reliably guides edits without ground-truth verifiers, and can be scaled further via parallel or sequential recursion. Harnessing-level recursion then extracts experience from 

---

### [299] FastEEP: Fast Intra-Instance Elastic Scaling for Expert-Parallel MoE Serving

**链接**: https://arxiv.org/abs/2610.18451
**作者**: Yunfei Feng, Jingkai He, Shiqi Liu, Cheng Zhang, Dong Du, Erhu Feng
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale expert parallelism (EP) has become the standard deployment configuration for Mixture-of-Experts (MoE) models in production. Meanwhile, the highly dynamic nature of LLM workloads requires providers to continuously adjust serving capacity to match fluctuating demand. Scaling MoE serving cannot be efficiently achieved by simply adding or removing serving instances; instead, it often requires resizing the EP group within an existing instance, which we refer to as intra-instance scaling.Existing inference engines primarily rely on instance-level scaling, which destroys and reconstructs entire serving instances, incurring substantial scaling overhead. We present FastEEP (Fast Elastic Expert Parallel), a fast intra-instance scaling system for MoE serving based on the principle of Partial Reuse. FastEEP reuses existing runtime state across worker execution, GPU memory, and communication by separating reusable execution structures from the resources activated by the current EP confi

---

### [300] OntoAR-HAR: Ontology-Guided Agentic RAG with Personalized Memory for Human Activity Recognition

**链接**: https://arxiv.org/abs/2610.15292
**作者**: Xiangqing Lu, Tao Zhu, Liang Yu, Shuangjian Li, Lulu Ban, Furong Duan 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs increasingly support sensor-based human activity recognition (HAR) by linking motion signals with activity semantics and physical knowledge. Retrieval-augmented generation (RAG) grounds decisions in sensor examples and domain features, enabling training-free target-user inference with less dependence on raw numerical arrays. However, existing LLM/RAG-based HAR typically searches single-level activity spaces using static population knowledge. Consequently, they compare many unrelated candidates using the same static population evidence and overlook personalized motion patterns. We propose OntoAR-HAR, an ontology-guided agentic RAG framework combining static population and personalized knowledge. Its tree-structured activity ontology decomposes classification into local decisions among semantically related activities. The static store supplies node-constrained examples, while offline-discovered executable signal features provide numerical evidence for local distinctions. During infe

---

### [301] When Log Parsing Removes What Matters: Detecting Failures in Distributed GPU Workloads

**链接**: https://arxiv.org/abs/2610.14009
**作者**: Boyuan Cui, Yuyang Zeng, Yifang Tian, Hans-Arno Jacobsen
**来源**: cs.LG cs.AI cs.DC cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large AI models increasingly rely on distributed GPU execution, yet it remains unclear whether established failure analysis methods transfer effectively to this setting. We introduce GF-Bench, a PyTorch-based framework and dataset for generating diverse failures in distributed GPU workloads. The framework supports extensible workload and fault-injection logic; based on this design, the current release targets failures visible in multi-GPU communication logs and provides 220 labeled two-GPU executions covering normal runs, CUDA out-of-memory fail-stop failures, and persistent straggler fail-slow failures. Using GF-Bench, we evaluate three sequence-based methods (DeepLog, LogAnomaly, and LogBERT) and the LLM-based LogPrompt on parsed logs, and additionally evaluate LogPrompt on raw logs. On parsed inputs, no method reliably detects both failure classes, and the highest overall F1 score is 0.667. Raw inputs raise the overall F1 score of in-context LogPrompt to 0.983, at 9.0x its average i

---

### [302] Small but Mighty: Test Suites as Improvement Signals for Self-Evolving Agents

**链接**: https://arxiv.org/abs/2610.15964
**作者**: Yutong Cheng, Wei Cheng, Wenchao Yu, Dawei Zhou, Haifeng Chen
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A self-evolving agent rewrites its own harness and must decide which rewrites to keep, so its improvement signal is the check a rewrite has to pass. Verifying a rewrite by agent rollout is expensive and subjective, while executable checks such as the repository's own tests are too sparse to catch behavior-changing rewrites, rejecting only a quarter of them. We instead take test feedback as the executable signal, and search for test suites that are both small and strong with a quality-diversity evolutionary algorithm, so that the signal is dense and informative. TeSearch treats suite size as a behavior descriptor, so that quality is pursued at every size and a small, strong suite is reachable, and learns a transition kernel during the search that denoises the LLM as an actuator on that descriptor. Across 129 real-world modules and three backbones, TeSearch delivers the highest-quality suites of any method compared, LLM-driven evolutionary search included, and the smallest of any LLM-bas

---

### [303] Encrypted Skills Can Become New Security Exploits If AI Agents Know How to Decipher

**链接**: https://arxiv.org/abs/2610.18262
**作者**: Yan-Lun Chen, Pin-Yu Chen, Chia-Mu Yu
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Third-party skills can expose LLM agents to malicious instructions hidden by encoding. We introduce Ciphered Skill Injection (CSI), which embeds such instructions in skill files for agents to decode and follow. We evaluate Caesar and layered variants across eight models and 139 injection-task pairs, separating instruction recovery from attack success. In the primary setting with shortened skills, the variants achieve attack success rates of up to 47.5% and 40.3%, respectively. Successful decoding does not guarantee attack success, and layering has model-dependent effects. The tested skill scanners rarely flag injected skills. These findings highlight the risk of promoting decoded, untrusted content into actionable instructions.

---

### [304] Specification-Based Testing of Large Language Models

**链接**: https://arxiv.org/abs/2610.14443
**作者**: Kausar Moshood, Jace Bolante, Roshan Aditya Murali, Manish Motwani
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model cards, system cards, and safety reports increasingly document LLM safety behaviors, yet safety evaluations typically start from predefined benchmarks rather than asking which documented claims those benchmarks actually test. We introduce LEST (LLM Evaluation through Specification-driven Testing), a framework that treats documented safety claims as specifications for black-box testing. In LEST, each claim determines which benchmark prompt tests it and whether a Refuse-to-Comply transition, where a model refuses a prompt but complies with its mutated version, counts as evidence against it. LEST mutates these prompts to search for counterexamples, manually validates each candidate, and traces validated counterexamples back to the claims they contradict. We evaluate LEST using the system cards of Claude Opus 4.8 and GPT-5.5 with 97 seed prompts from SORRY-Bench across Mental Health and Self-Harm, Harmful and Violent Content, and Fairness and Bias. Of 56 identified safety claims, 29 (

---

### [305] NetRL: Powering Network Decisions via NetGRPO-Driven Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.16226
**作者**: Lingfeng Peng, Xiaohui Xie, Yang Bao, Yong Cui
**来源**: cs.NI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Network decision-making tasks, including adaptive bitrate streaming, load balancing, and congestion control, require policies to process heterogeneous states and actions while balancing near- and long-term consequences. Existing solutions generalize poorly across network tasks, require substantial task-specific redesign, and lack reliable evaluation of long- horizon action consequences. Methods that learn through online interaction additionally face unstable optimization. We present NetRL, a two-stage LLM-based reinforcement learning framework that combines supervised fine-tuning on demonstration trajectories with online policy optimization. A universal mixed-embedding interface combines textual task descriptions with precise numerical states, while a network action head produces valid decisions. At its core, NetGRPO evaluates candidate actions over multiple future trajectories, directs deeper search toward uncertain alternatives through confidence-aware budgeting, and performs group-r

---

### [306] How Safe Is ChatGPT Health Advice? Evidence from Real User Conversations in Four Global South Countries

**链接**: https://arxiv.org/abs/2610.18465
**作者**: Shreyasi Roy Chowdhury, Kiran Garimella
**来源**: cs.CY cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People increasingly bring their health questions to ChatGPT, yet safety evaluations of LLM health advice rest almost entirely on clinician-authored vignettes, synthetic prompts, or simulated user profiles. The gap is widest for the Global South, where concerns about demographic bias and unsafe recommendations are well documented but have never been tested on real usage. We present, to our knowledge, the first demographically grounded safety evaluation of real-world health conversations with ChatGPT. From a consent-based data-donation corpus of 202,590 conversations from 1,252 users in India, Nigeria, Brazil, and Pakistan (December 2022 to February 2026), each linked to self-reported age and gender, we identify 15,555 health conversations, classify their health intent using an LLM classifier adapted from an established taxonomy, and score response safety under both a context-blind and a user-context-aware rubric. Roughly one in five health conversations receives a high-risk rating. Risk

---

### [307] EdgeWise: Bringing Long-Horizon Agents to the Edge via Selective Cloud Delegation

**链接**: https://arxiv.org/abs/2610.17560
**作者**: Zeru Shi, Jindong Jiang, Ryo Hachiuma, Yonggan Fu, Byung-Kwan Lee, Peter Belcak 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complex and long-horizon agent tasks often rely on frontier models deployed in the cloud to achieve strong performance. However, using these models for every step of a long-horizon trajectory incurs substantial inference cost, even though not all steps may require the same level of model capability. In this paper, we find that allocating the LLM to only a small subset of key steps can achieve performance comparable to full LLM execution while significantly reducing inference cost. Motivated by this observation, we propose EdgeWise, an edge-cloud collaboration framework that deploys an SLM on the local device as the primary solver and selectively delegates critical steps to a cloud LLM when stronger model capacity is needed. To enable autonomous delegation without additional models at inference time, we introduce a step-level RL method that jointly optimizes task solving and delegation, with fine-grained credit assignment for individual delegation decisions. We also introduce an externa

---

### [308] FoveaTree: Information-Density Trees for Query-Guided Visual Token Pruning in Video Large Language Models

**链接**: https://arxiv.org/abs/2610.16744
**作者**: Zihan Meng, Weidong Chen, Dexiang Hong, Xinyan Liu, Zhendong Mao
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video large language models (Video LLMs) encode each frame into hundreds of visual tokens, making video inference expensive. Existing methods reduce this cost through similarity-based merging or attention-based selection but face two challenges: Hierarchy-blind Pruning, which overlooks regional compressibility and can discard critical evidence, and Attention Drift, where positional effects and attention sinks shift text-to-vision attention away from task relevance. We propose FoveaTree, a two-stage, training-free visual-token pruning framework. First, Merge-Gain Density Estimation measures the feature distortion caused by regional merging and constructs a quadtree-derived density map to guide token dropping, merging, and retention. Second, Attention Tree Pruning uses the surviving units and inherited tree topology to refine text-to-vision attention in intermediate LLM layers, preserving relevant regional evidence while removing low-relevance content. We evaluate FoveaTree on InternVL3.

---

### [309] Loose Lips: Understanding Privacy Leakage in Agentic Dialogue

**链接**: https://arxiv.org/abs/2610.14071
**作者**: Soumya Sharma, Ayana Hussain, Heber Hwang Arcolezi, Ulrich A\"ivodji, Spandana Gella, Adriana Romero-Soriano 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents are increasingly deployed in high-stakes enterprise settings, understanding how they handle sensitive information in agentic dialogue has become critical. Privacy leakage in such settings requires reasoning about whether information flows respect the contextual norms under which they originated. We extend CIMemories to CIMEMORIES DIALOGUE, a benchmark of 4,410 two-agent dialogue instances grounded in Contextual Integrity theory. Using this benchmark, we systematically evaluate 7 open-weight models from the Qwen3 and Llama 3.1 families across conversation lengths of 1 and 6 turns under three prompting conditions. We find that task capability and privacy leakage are fundamentally coupled: more capable models are systematically leakier, with no model in our evaluation able to decouple the two. Thinking models consistently leak more than their non-thinking counterparts, a pattern we attribute to the extended reasoning surface created by chain-of-thought. Leakage compounds wit

---

### [310] Representation Drift in Continual Learning: LoRA versus N-gram Memory

**链接**: https://arxiv.org/abs/2610.14921
**作者**: Hao Wu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A language model that keeps learning online must not slowly erode its own base capabilities. We ask which part of a modern LLM should absorb continual updates, by measuring how each choice changes the model's internal representations. On a 48-layer mixture-of-experts model with a native pretrained N-gram memory, we train a seven-task chain under three update mechanisms with identical data and budgets: updating only the N-gram memory table, continually training one shared LoRA adapter, and training a fresh LoRA per task that is merged into the backbone. We capture fixed-context representations at every layer and task boundary. Updating only the N-gram memory changes the base model's representations of general math and code inputs by 26%/15% (relative RMS), against 64%/35% for merged and 97%/39% for shared LoRA. This drift does not grow with the number of tasks: it reaches 25% after the first task and stays there for all seven, while both LoRA variants keep accumulating. Its generic beha

---

### [311] Cheap, Consistent, Calibrated, but Biased? Typed Decision Models as Judges

**链接**: https://arxiv.org/abs/2610.18122
**作者**: Fabian Lukassen, Christoph Weisser, Alexander Silbersdorff
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Typed decision models (TDMs) return a probability for each allowed answer instead of generating text, which makes them candidates for cheaply replacing LLM judges that compare two answers. Whether they share the biases of LLM judges is untested. We run the CALM benchmark's bias tests on eight TDMs and seven LLM judges of 2024 and 2026. Every TDM is biased, in three to eight of twelve tests. Emotional tone affects them most, and rewriting the better answer in such a tone lowers the accuracy of a typical TDM from 99% to 42%. TDMs are more biased than 2026 LLM judges. All eight change verdicts when the answers swap places, which the 2026 LLM judges hardly do, and several side with an answer that most people allegedly prefer or that a famous model allegedly wrote. Yet both kinds of judge are tripped up by the same prompts. The TDMs' probabilities show that most tests mainly flip verdicts the TDM was unsure of, and that good calibration does not protect against bias. As TDMs are more consis

---

### [312] Beyond Perfect Teammates: Multi-Agent Collaboration with Unreliable Colleagues

**链接**: https://arxiv.org/abs/2610.16117
**作者**: Chen Huang, Yiyang Zhang, Yuhao Wu, Yang Deng, Wenxuan Zhang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent collaboration is increasingly used to solve complex tasks by dividing work among specialized agents and integrating complementary expertise. Yet existing systems and evaluations largely rest on an implicit perfect-colleague assumption: collaborators provide correct and complete information and respond promptly to requests. In realistic teamwork, however, collaborators may return information that does not answer the intended question, provide insufficient detail to support a decision, or fail to respond to a request. To separate task-solving competence from the ability to recover an unreliable evidence-gathering process, we introduce the Unreliable Colleagues Benchmark (UnCoBench), which organizes behavioral failures through Misaligned, Incomplete, and Missed settings. The main agent need to verify contextual correctness, diagnose information gap and track unresolved dependencies in order to obtain the correct evidence for solving the task. We also introduce a veri

---

### [313] Single-Sample Decoding of a Two-Layer Sound-Word Canvas Model for Thai Klon Pad

**链接**: https://arxiv.org/abs/2610.14980
**作者**: Worasait Suwannik
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a generator of Thai klon pad verse, one stanza from a short topic, and evaluate it against human verse on held-out topics. The generator is a masked language model initialised from WangchanBERTa over a fixed canvas with two layers: a sound layer of pronounced syllables, where rhyme, tone and syllable count are enforced as hard masks, and a word layer of whole words, so that no word is cut into written pieces. Decoding commits one cell at a time and samples at temperature 0.4; one sample is drawn per topic, with no selection, reranking or repair. On 78 held-out topics never used in development, judged by three independent runs of a frozen LLM judge in the same pools as the human stanzas from which the topics were written, 70.5% of the generated stanzas pass form, lexical cleanness of all four lines and topic alignment together, against 76.9% for the human stanzas (difference -6.4 points, 95% CI [-19.2, +6.4]). Cleanness is level with human (85.9% vs. 87.2%), and the stanzas p

---

### [314] SocraticRepair: Planning-Guided Socratic Tutoring for Program Debugging and Misconception Repair

**链接**: https://arxiv.org/abs/2610.15204
**作者**: Mykhailo Kopytskyi, Jianhua Yang, Mir Seyedebrahimi
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used in computer science education. However, the teaching abilities of even the most powerful LLMs are limited: they tend to reveal the solution prematurely and may lose focus on the learner's current debugging objective. To address this, we introduce SocraticRepair, a planning-guided Socratic tutoring framework for program debugging and miscon- ception repair that adapts prior planning-guided tutoring work (Li et al., 2026b). The framework is instantiated in the Python programming domain by fine-tuning Qwen2.5-Coder-7B-Instruct on synthetic multi-turn tutoring dialogues constructed from four preprocessed programming datasets. The system is evaluated using a predefined set of independent metrics and benchmarked against a general-purpose LLM. The experiments show that SocraticRepair achieves higher scores on stepwise scaffolding and question quality while also substantially reducing premature solution disclosure. The results also identify reliable 

---

### [315] Agent-Canary-Mas: End-to-End Evaluation of Protocol Risk in Long-Horizon Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.15529
**作者**: Xiuming Liu, Le Gai, Zhiyuan Chang, Peiyang Li, Bin Zhu, Shuo Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent-to-agent protocols allow LLM agents to discover peers, exchange results, and coordinate tool use. A locally successful protocol attack, however, may be rejected by a later agent or propagated into a consequential task decision. Measuring local exploitability alone leaves this difference unresolved and provides limited evidence about which participant caused the final outcome. We present Agent-Canary-Mas, an end-to-end evaluation system that follows protocol risk through long-horizon multi-agent tasks. It covers five risk classes and 13 subclasses across A2A, ANP, and BCS, with 975 matched malicious--benign task pairs in five business domains. A shared OpenClaw framework runs autonomous, tool-using agents under different underlying models while preserving the task and execution setup. Matched runs separate local protocol success from downstream consequences; retained evidence connects participant selection, message consumption, tool activity, and task-state changes. We further eva

---

### [316] TIDE: Trajectory-Informed Skill Distillation for Efficient Text-to-Video Prompt Optimization

**链接**: https://arxiv.org/abs/2610.15098
**作者**: Chengxing Zhou, Yuliang Huang and Jingwei Song
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-video (T2V) models are highly sensitive to prompt specificity, while iterative prompt optimization typically improves generation quality only through repeated video generation and vision-language model evaluation at inference time. We propose TIDE, a framework that distills this costly search process into an interpretable and reusable prompt-rewriting Skill. TIDE formulates prompt rewriting as a set of source-conditioned rule modules, each targeting a distinct semantic dimension. Once distilled, the frozen Skill activates the relevant rules and generates both positive and negative prompts in a single LLM call, followed by only one T2V generation, without test-time visual search or backbone fine-tuning. Evolved using only 100 prompts over 14 hours, TIDE achieves prompt-optimization performance comparable to computationally expensive search-based methods. Moreover, when transferred to previously unseen video-generation models, TIDE outperforms existing approaches specifically des

---

### [317] ProCARE: Real-World Study Automation via Profile-Grounded Evidence Contracts

**链接**: https://arxiv.org/abs/2610.16175
**作者**: Zhaoyu Fan, Bowen Han, Jincheng Ou, Yanwei Ren, Zehua He, Kaiyu Huang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world studies (RWS) analyze routinely collected healthcare data, such as electronic health records and insurance claims, to estimate treatment effects, monitor safety, and identify risk factors outside randomized trials. Automating RWS with large language model agents is appealing but brittle: valid analyses depend on dataset-specific clinical semantics, including index dates, follow-up windows, patient/event-level units, and outcome boundaries that are often implicit in observational data. This leads to schema mismatches, temporal errors, inconsistent analytical granularity, and unsupported clinical claims. We present ProCARE, a profile-grounded framework that reformulates RWS automation as constrained compilation. ProCARE converts heterogeneous data profiles into Evidence Contracts specifying available variables, temporal attributes, distributions, and evidentiary limits, and compiles study objectives into RWS-IR, a strongly typed intermediate representation for variables, time 

---

### [318] GameSmith: Scaling Zero-Sum Self-Play with Synthesised Games

**链接**: https://arxiv.org/abs/2610.13995
**作者**: Weixian Waylon Li, Jiaxin Zhang, Han Zhou, Chengzu Li, Ke Wang, Fengxiang He 等 (7 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training large language models (LLMs) on two-player zero-sum games provides a verifiable reward, and the gains have been shown to transfer to general reasoning. Existing pipelines, however, rely on a handful of hand-written games and on advantage estimators tied to them, so both the supply of games and the advantage estimate on a large corpus limit scaling. We present GameSmith, which scales both. An LLM synthesises games inside templates whose reward, observation, and hidden-information code is fixed. Each game is verified by seed-paired replay and by an independent re-implementation of its specification, then expanded into encoding, rule, and size variants, giving 26 new games in 29 families and 336 verified variants from the three SPIRAL templates. The model is distilled from the self-play of a larger teacher (Qwen3-32B) on these games and then trained by self-play reinforcement learning with CRAB, an advantage estimator that credits each decision against a shrinkage estimate o

---

### [319] Towards Cost-Efficient Video Dataset Construction with Large Language Models

**链接**: https://arxiv.org/abs/2610.16857
**作者**: Mohammed Shabot, Jonathan Adams, Jan Van den Stock, Joost Vennekens
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on video classification models has witnessed significant growth recently, accompanied by a significant increase in the demand for datasets to train such models. Existing video dataset curation approaches share a common bottleneck: candidate videos must be downloaded before any relevance judgment is made, which results in storage, time and annotation costs. In this work, we present a filtering step, using Large Language Models (LLMs) to pre-screen videos based on their metadata, before actually downloading these videos, thereby saving on these costs. We evaluate the LLMs against a strict human majority vote derived from four independent annotators and validate the reliability of the annotations through inter-annotator agreement analysis (Gwet's AC1). We compare the LLM pre-filter against two no-LLM baselines, namely two keyword heuristics. Via a Leave-One-Rater-Out (LOO) mechanism and an Add-One-Rater-In (AORI), we evaluate the performance of the LLMs as virtual annotators. Fin

---

### [320] ASSET: Adaptive Speech Segmentation via Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.14309
**作者**: Cihan Xiao, Yuan Tseng, Matthew Wiesner, Desh Raj, Leibny Paola Garcia Perera, Sanjeev Khudanpur 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech large language models (LLMs) are often built using pretrained acoustic encoders as an audio interface to an LLM decoder. However, LLMs scale poorly with input sequence length, while acoustic encoders tend to produce substantially longer sequences than typical textual inputs. This motivates learning to compress encoder outputs while preserving task-oriented information. To this end, we introduce ASSET, a reinforcement learning (RL)-based framework that learns to adaptively compress encoder outputs by first partitioning them into variable-duration segments and then pooling each segment into a continuous audio token. We use group-relative policy optimization (GRPO) to train a segmenter with task performance feedback and a token-rate penalty. In automatic speech recognition (ASR) experiments, ASSET achieves performance comparable to a transcript-assisted character-boundary oracle with approximately 25% fewer audio tokens on English LibriSpeech, while improving on a phone-boundary or

---

### [321] Mind Your Own Role: Reducing Role Overstepping for Effective and Efficient Multi-Agent Collaboration via Dynamic Role Activation Steering

**链接**: https://arxiv.org/abs/2610.15907
**作者**: Xingke Yang, Sicong Li, Lingfeng Yao, Rui Chen, Gen Li, Hao Wang 等 (8 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-Agent Systems (MAS) have shown strong capability in solving complex tasks by assigning different agents specialized roles and corresponding subtasks. However, agents may overstep their assigned responsibilities and perform subtasks belonging to other roles, which can disrupt workflow, reduce system efficiency, and degrade task performance. To address this issue, we investigate role-related patterns in the model's internal activation space and uncover two key observations: (i) role instructions induce consistent directional shifts in activation space, and (ii) role-adherent and role-overstepping trajectories exhibit distinct activation patterns. Based on these observations, we propose Dynamic Role Activation Steering (DRAS), a lightweight and effective inference-time activation intervention approach to reduce role overstepping in multi-agent collaboration. Specifically, DRAS constructs a role steering vector and a lightweight role-overstepping detector for each role. During LLM ge

---

### [322] Who Sets the Pace of Judge Hacking? Judge Capability versus the Policy-Judge Gap

**链接**: https://arxiv.org/abs/2610.15778
**作者**: Haosen Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a policy is trained with GRPO against a frozen, reference-free LLM judge, the judge accepts more of its answers, but in a post-hoc analysis we detect no gain in held-out greedy accuracy: in all 12 (policy, judge) cells, the seed-mean gain never exceeded 0.04. A gold-reward control with the same recipe raised the 1.5B policy's greedy accuracy by +0.054 [0.013, 0.096], so for this policy the flat accuracy is specific to the judge reward; for the 0.5B policy, gold reward also gave no detectable gain. In the four rising cells we checked, the early rise in training-rollout accuracy is mostly sampling sharpening, as it is under gold reward. We then ask whether the policy-judge gap or the judge sets how far and how fast RL exploits the judge's false positives. We train 0.5B and 1.5B Qwen2.5 policies against four judges at least as large (Qwen2.5-1.5B/3B/7B, Llama-3.2-3B) and the 1.5B policy against one smaller judge (Qwen3-0.6B). The depth of judge hacking (the plateau) tracks the judge:

---

### [323] Interaction-as-a-Judge

**链接**: https://arxiv.org/abs/2610.17895
**作者**: Wayne Chi, I-Hung Hsu, Li Chen, Wei-Lin Chiang, Ion Stoica, Anastasios Nikolas Angelopoulos 等 (9 人)
**来源**: cs.LG cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding agents are tasked with producing sophisticated interactive applications such as websites, desktop applications, and games. While humans assess these applications interactively, current automated LLM evaluations primarily focus on code analysis and unit tests. This mismatch can cause LLM judges to miss failures that are immediately apparent to human users. We study Interaction-as-a-Judge, an evaluation paradigm where computer-use agents (CUAs) directly interact with an application. We demonstrate that Interaction-as-a-Judge can improve both \emph{evaluation} and \emph{generation} of interactive applications. To this end, we collect and release two complementary datasets: $6,858$ pairs of applications with human preferences and corresponding agent traces, and $222$ applications with human-verified requirement labels. Relative to standard non-interactive approaches, we find that Interaction-as-a-Judge improves evaluation in terms of predicting human preferences ($65.6\% \to 69.1\%$

---

### [324] AReaL-RSI: Adaptive Scaling and Coordination of Recursive Self-Improvement

**链接**: https://arxiv.org/abs/2610.18083
**作者**: Wenhao Zhou, Jiajun Song, Haitao Wang, Zipeng Qiu, Yingqi Peng, Ruida Xu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling recursive self-improvement requires additional computation to produce useful research progress in reaching persistent objectives. Intuitively, more researcher agents can explore more hypotheses, but early evaluation scores might misrepresent their promise, shared findings could lose their applicability conditions, and useful procedures could remain confined to completed investigations. In this paper, we present AReaL-RSI, a framework for organizing a persistent research team of agents without updating backbone LLM weights. We formulate the scaling problem in terms of evaluated outcomes and whole-system resource expenditure. Concretely, a leader agent selects task-appropriate research orientations and guides ongoing investigations; conditional memory sharing distinguishes unresolved problems from supported findings and enables recipient adaptation. During recursive evolution, after each campaign, evidence-based review revises researcher orientation, knowledge, and skills for lat

---

### [325] A Self-Defining Operator for Distributed Applications

**链接**: https://arxiv.org/abs/2610.14547
**作者**: Shihang Li, Thomas Anderson, Ratul Mahajan, Simon Peter
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To operate distributed applications with high availability, operators must rapidly diagnose and mitigate any incident. LLM-based agents can help, but unlike experienced human operators they do not improve as they handle more incidents. Each investigation starts from scratch, re-deriving likely causes and re-testing hypotheses even when a similar fault was resolved in the past. We present a self-defining operator (SDO) that improves with time by updating its operational behavior and memory. When SDO resolves an incident, it distills that experience into playbooks, which describe reusable diagnostic instructions for future incidents with similar faults, and detectors, scripts that take application telemetry as input and output relevant playbook(s). SDO continuously runs the detectors and invokes LLMs only when one fires, so its token cost scales with incident count rather than with operational time. Across 11 open-source microservice applications, SDO cuts resolution time by 52% on recur

---

### [326] Two For The Price Of One: Curvature-Aware Pruning Preserves Influence Functions Too

**链接**: https://arxiv.org/abs/2610.18516
**作者**: Mehdi Makni, Natalia Ponomareva, Rahul Mazumder
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training pruning enables efficient deployment, but conventional methods do not explicitly preserve internal-gradient alignment between sparse and dense models. We study novel connections between downstream performance of compressed models and the ability to retain gradient information via influence-function preservation. Central to this connection is a curvature-aware objective that accounts for both layer activations and backpropagated gradients. Despite its promise, this objective remains underexplored in pruning due to a lack of efficient solvers. We introduce $\texttt{CACTUS}$, a novel ADMM-based optimizer supporting both pruning and sparse-plus-low-rank decompositions of pre-trained weights. Compared to LLM-Surgeon which targets the same objective, $\texttt{CACTUS}$ can achieve over an order-of-magnitude speedup. At $50\%$ pruning of Qwen3-4B, $\texttt{CACTUS}$ reduces the C4 perplexity gap to the dense model by $45\%$, improves compressed-to-dense per-sample gradient cosine 

---

### [327] Executable Prefix Values for Locating Agent Failures

**链接**: https://arxiv.org/abs/2610.17633
**作者**: Bingyu Shen, Jiaqi Tang, Lan Wei, Yi Sheng, J. Jenny Li, Boyang Li
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Work on debugging LLM agents treats the "first mistake" marked by a human or LLM judge as ground truth for where a trajectory failed. We ask whether such labels point at causes or symptoms, and make the distinction executable: we restart the agent from reconstructed intermediate states of a failed trajectory and estimate its prefix value V(h_t), the probability of success from each step, with a certified point of no return (PNR) for a failure. On 150 SWE-bench Verified tasks with two frozen open-weight agents, we build such curves for 47 and 60 failed trajectories and probe every step labeled by four frontier judges under the Traverse rubric. We find that the labels do not mark what a controller needs. Judges of different lineages agree on the exact step in only 21/57 cases, and the newest judges flag mistakes in 8/10 and 10/10 successful runs. For 66% of the labels, the agent's success probability does not drop at the labeled step; only 7/188 answers name the decisive step. Restarting

---

### [328] Beyond a Better Score: Long-Horizon Agentic ML Development and Evaluation Protocol for Physics Time Series

**链接**: https://arxiv.org/abs/2610.14024
**作者**: Yue Ma, Lucas Venetoulias, Akbota Assan, Aobo Li
**来源**: cs.LG hep-ex
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physics time-series data are central to fundamental discoveries involving dark matter, neutrinos, and gravitational waves. Machine learning has shown strong potential to recover weak scientific signals buried in complex noise. Recent LLM-agent systems further automate ML development, but existing approaches are often driven primarily by one or a few numerical scores. In pursuit of a better score, agents may exploit shortcuts, trigger mode collapse, or game the evaluation procedure, producing models that achieve high scores but are scientifically invalid. We introduce SIDERIUS, an LLM agent system designed to move beyond a better score toward scientifically valid, long-horizon ML development. SIDERIUS combines contract-defined composable capabilities for flexible orchestration and human-in-the-loop, a multi-layer scientific evaluation protocol that distinguishes valid models from unhealthy or gaming models, and resource-aware exploration for computationally expensive scientific ML. In o

---

### [329] DVTR-KD: Distilling Vision-Language Models via Intermediate Visual Token Reconstruction

**链接**: https://arxiv.org/abs/2610.17853
**作者**: Haolan Wei and Jiahui Wang and Junli Zha and Xinkai Lu and Yunxiao Zou and Chao Zhou and Xiang Song
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have achieved strong performance on diverse vision-language tasks, but their computational demands limit deployment under constrained budgets, particularly on edge devices. Many works focus on Knowledge Distillation (KD) and try to transfer knowledge from powerful teacher models to students. In addition to reducing model size, visual token compression provides a complementary route to efficiency, but introduces mismatched visual token counts that complicate direct token-wise knowledge transfer. To mitigate this, we propose DVTR-KD, a knowledge distillation framework based on \textbf{D}ense \textbf{V}isual \textbf{T}oken \textbf{R}econstruction, which reconstructs the teacher's dense visual tokens from the student's compressed tokens. We reconstruct visual states after the final LLM layer and at the input to an intermediate layer identified as important for visual-information readout. At the intermediate layer, reconstruction is supervised throug

---

### [330] Learning to Design SR Solvers: Harness Optimization for Symbolic Regression

**链接**: https://arxiv.org/abs/2610.16966
**作者**: Qian Li, Yuxiao Hu, Qihao Duan, Jinyue Yan, Yuntian Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Symbolic regression (SR) seeks explicit equations that explain observed data, and recent methods increasingly employ large language models (LLMs) and agents for equation discovery. However, these systems typically rely on manually designed workflows and prompts. We argue that the SR agent harness should itself be an optimization target: its design shapes search priors and how numerical feedback guides subsequent equation refinement. We therefore propose HarnessSR, a framework for jointly optimizing prompts and workflows to construct reusable SR agents. During both harness optimization and agent execution, HarnessSR supports either PySR or an LLM-based equation generator through tool-specific interfaces, allowing the framework to optimize search guidance for different equation-discovery mechanisms. HarnessSR first optimizes role prompts through equation-discovery feedback in basic workflows, then jointly searches prompt assignments and workflows with brief adaptation to align the two. F

---

### [331] SP$^2$ec: Adaptive Self-Speculative Decoding for Vision-Language Models

**链接**: https://arxiv.org/abs/2610.18735
**作者**: Yuqi Huang, Xingyao Li, Yunlong Hou, Fengzhuo Zhang, Jiachun Pan, Vincent Y. F. Tan
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative Decoding (SD) has demonstrated its efficacy in accelerating large language model inference, but for Vision-Language Models (VLMs), the diverse input modalities make it difficult for a small trained drafter to achieve consistently high throughput. Self-speculative decoding reuses parts of the target model as a drafter which retains the multi-modal capability of the VLMs, yet its efficiency depends on choosing a suitable draft configuration for each prompt. We propose Single-Peak SPeculative decoding (SP$^2$ec), a training-free bandit algorithm that adapts the draft configuration during generation. SP$^2$ec exploits the single-peak throughput pattern observed in existing self-speculative methods, including SWIFT, KnapSpec, SpecVLM, and our simple cosSim. Our algorithmic design explicitly minimizes a novel notion of wall-time regret for each given query, corresponding to the empirical wall-time latency. Theoretical guarantees on the wall-time regret show that SP$^2$ec can expl

---

### [332] EHR-Bench: A Chinese Multi-Task Benchmark for Recruitment AI

**链接**: https://arxiv.org/abs/2610.16689
**作者**: Ruijia Yang, Bing Xu, Zulong Chen, Zhipeng Xu, Jia Xu, Yipeng Yu 等 (8 人)
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recruitment applications span diverse operations, from drafting job descriptions and interpreting queries to organizing profiles, assessing fit, and recommending candidates and jobs. Systematic LLM evaluation therefore requires task coverage that reflects this range of business needs. We introduce EHR-Bench, an open Chinese benchmark comprising twelve tasks across six capability families and five recruitment scenarios. The tasks cover generation, extraction, classification, retrieval, semantic similarity, and reciprocal ranking within one evaluation framework. An internal recruitment dataset guides task definitions, the occupation taxonomy and sampling targets, output requirements, and scoring protocols. Following these specifications, we construct 8,336 task instances from public materials and controlled augmentation, with source-aware expert review and documented provenance. We evaluate twelve LLMs through task-level, capability-level, and aggregate comparisons. Closely ranked models

---

### [333] A Production-Grade, High-Efficiency Agentic RL Framework for Frontier LLMs with Validated Recipes

**链接**: https://arxiv.org/abs/2610.16352
**作者**: LoonSage Team: Bowei Song, Caiwei Zhao, Chuwen Liu, Dechuang Gu, Dong Fang, Feiyu Xie 等 (10 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has emerged as a critical phase in the post-training pipeline of large language models (LLMs). As the frontier of LLM capabilities shifts from static reasoning to agentic tasks--characterized by external tool invocation, multi-turn interactions, and long-horizon decision-making--existing mainstream RL frameworks have grown increasingly unwieldy, raising the overhead of adoption, usage, and debugging. To address these challenges, we present LoongSage, an agent-native, fully asynchronous RL framework with a lightweight core of roughly 14K lines of code. Built upon Megatron for distributed training and SGLang for high-throughput inference, LoongSage centralizes orchestration within a single controller process and encapsulates all GPU-resident components as Ray actors. It introduces AgentFlow, a unified execution paradigm that orchestrates both white-box and black-box agents. For asynchronous execution, it integrates sliding-window strategies that bound trajecto

---

### [334] Cross-Protocol Personality Assessment with LLMs: Aligning Behavioral Evidence with Human Ratings

**链接**: https://arxiv.org/abs/2610.16050
**作者**: Wei Shan, Tianyi Zhang, Yuan Zong, Wenming Zheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personality assessment from asynchronous video interviews (AVIs) plays a crucial role in recruitment by enabling standardized and behaviorally grounded evaluation for job applicants. However, most of the previous works are confined to a single interview protocol. Independently collected protocols differ in question sets and question-trait mapping. Thus, the human-rated evidence from one protocol cannot be used directly under another. To address this limitation, we propose the Cross-protocol Evidence-grounded Personality Assessment (CEPA) framework, which aligns behavioral representations across interview protocols. CEPA addresses protocol heterogeneity by projecting source behavioral records into the target protocol's construct-oriented representation space. It retrieves behaviorally relevant and personality-complementary human-rated exemplars to ground an ensemble of LLM raters, which enables behavior-to-personality associations without target-specific supervision. In cross-protocol e

---

### [335] The Multilingual Artificial Hivemind: Do All LLMs Think Alike in Every Language?

**链接**: https://arxiv.org/abs/2610.16755
**作者**: Xaver Raphael Davey, Shubhra Mishra, Anton Adel\"ow, Siyao Liu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text generated by Large Language Models (LLMs) often remains limited in diversity compared to that produced by humans. Recent advances demonstrate the presence of inter- and intra-model collapse in open-ended generation of English text, raising concerns about the long-term homogenization of LLM, and more importantly, human thought. However, our understanding of whether this homogenization extends to languages beyond English is limited. In this work, we investigate the role of language on output diversity. Specifically, we aim to understand whether multilingual LLM-generated text is also homogeneous, and whether this homogeneity matches what we observe in humans. Across 23 open-weight models and 13 languages, we find that the artificial hivemind effect is pervasive but uneven in its extent. The intra-model effect holds in three different embedding spaces and under a lexical metric that uses no embedding model, so it is not an artifact of how diversity is measured. The size of the homoge

---

### [336] Hybrid Reasoning Agents

**链接**: https://arxiv.org/abs/2610.18861
**作者**: Jiaru Zou, Yunzhe Qi, Sirui Chen, Federico Bianchi, Shang Zhu, Pan Lu 等 (8 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How can we build an agent that thinks beyond human language, yet still acts through it in the external environment? Modern LLM agents still reason and interact through text, while latent reasoning offers an efficient internal medium but lacks native tool access and reasoning transparency. We bridge these two directions with Hybrid Reasoning Agents (HybridAgents), which dynamically navigate between latent reasoning and text-based interaction throughout a unified generation process. Architecturally, a lightweight HybridLink enables seamless transitions between text and latent modes, while the agent's continuous working memory preserves lossless hybrid context across multiple turns. These designs preserve tool-integrated agentic capabilities while making latent thoughts directly inspectable. Building on this architecture, we further develop dedicated post-training algorithms for hybrid reasoning: HybridSFT stabilizes tool-integrated hybrid generation by teaching the backbone to coordinate

---

### [337] When Goals Leak Across Relationships: How Cached Goal Representations Shape Cross-Client Decisions

**链接**: https://arxiv.org/abs/2610.17365
**作者**: Saloni Gupta, S\'ebastien Krier, Glenn Matlin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents take on more autonomous roles, they may interact with multiple clients and counterparties whose goals and incentives conflict. If an agent maintains shared inference state across these interactions, information associated with one relationship may influence decisions made for another. We test OLMo-3-7B-Instruct in a controlled two-client environment with 20 market scenarios, where each client is assigned an opposing objective. With shared conversational memory, the model deviates from the current client's objective in 22% of eligible decisions. We then investigate how these goals are represented in the KV cache. Linear probes show that client-goal ownership becomes highly recoverable in middle layers and is concentrated in particular attention heads. We use these results to identify where to intervene in the cache and test whether these representations affect the model's decisions. Ablating the competitor's cached goal representations at these locations shifts the model t

---

### [338] Decomposing and Predicting Annotation Disagreement in Harmful Content Across Languages

**链接**: https://arxiv.org/abs/2610.18588
**作者**: Irem Ecem Yelkanat, Faeze Ghorbanpour, Alexander Fraser
**来源**: cs.CL cs.CY cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Annotator disagreement is increasingly recognized as a meaningful property of subjective tasks, rather than merely noise to be removed. Predicting which items are likely to be contested could help allocate annotation effort and route difficult cases to human review. We propose predicting disagreement from interpretable semantic properties of the text. An LLM answers a set of binary questions covering harmful-content characteristics, disagreement-related cues such as borderline severity and missing context, and language-sensitive cues such as local slurs. A classifier predicts disagreement from these answers, and we analyze which questions contribute most to the predictions. Across four datasets in English, German, and Turkish and three open-weight LLMs, our structured question features outperform direct prompting by 10.5 ROC-AUC points and the strongest text-based baselines by 5.0 points. A compact subset of eight questions performs within 1.5 ROC-AUC points of the full twenty-question

---

### [339] Agentic Data Engineering for LLMs: System Design and a Controlled Empirical Study

**链接**: https://arxiv.org/abs/2610.14238
**作者**: Ruomeng Ding, Qianli Shen, Zhaoyang Han, Meixin Chen, Daoyuan Chen, Yaliang Li
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM data engineering requires iterative experimentation to determine how data selection, rewards, and curricula affect model learning, making it a natural setting for AI-for-AI (AI4AI) research. Can agents use experimental feedback to progressively improve strategies, and do the resulting strategies improve target-model performance on held-out data? We study how agents use experimental feedback to develop data-engineering strategies under fixed training and evaluation protocols. Our Agentic Data Engineering (ADE) framework lets agents pursue, revise, or combine research directions using cumulative findings. Strategies are selected by in-loop scores and evaluated on held-out benchmarks. Across four tasks-math and code data selection, math reward design, and math curriculum learning-selected strategies achieve absolute gains over generic baselines of up to 13.34% on AIME25 Pass@32 and 5.85% averaged across four held-out benchmarks under fixed training conditions. In-loop scores improve o

---

### [340] Encounter-Driven City-Scale Human Mobility Generation with Large Language Models

**链接**: https://arxiv.org/abs/2610.17672
**作者**: Chao Li, Renhe Jiang, Chuan Xiao, Jiawei Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong potential for human mobility generation by modeling individual routines, activities, and mobility preferences. However, existing approaches remain largely resident-centric: generating realistic individual trajectories does not necessarily recover the encounters that emerge when multiple residents co-occur at the same place and time. To this end, we study encounter-aware human mobility generation, which jointly preserves individual mobility and population-level interaction structure. We propose EncounterMob, an encounter-driven LLM framework consisting of a coarse-to-fine Encounter Generator and an Iterative Coupling Framework. The Encounter Generator first captures city-level encounter rhythms and then instantiates participant-time-venue encounters, while the Iterative Coupling Framework coordinates these encounters with personal mobility behavior through successive refinement. We further introduce an encounter recovery protocol covering e

---

### [341] Prorsa: Unleashing the Potential of Prefill-Decode Disaggregation in Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.16592
**作者**: Chiheng Lou, Xiangwei Deng, Bangjun Xiao, Xiaodong Ji, Yikai Zhao, Xin Jin 等 (7 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic reinforcement learning (RL) is commonly used to enhance the capabilities of large language models (LLMs) in solving complex multi-turn tasks. During rollout, agentic RL exhibits a workload pattern distinct from that of traditional RL: multi-turn interactions repeatedly introduce prefill requests, causing prefill and decode workloads to coexist throughout rollout. This workload makes prefill-decode (PD) disaggregation, a design widely used for online LLM serving, promising for speeding up agentic RL rollout. This paper shows that PD disaggregation can improve rollout efficiency by (a) mitigating interference among data-parallel attention modules, (b) enabling stage-specific parallelism, and (c) reducing end-to-end trajectory completion time. However, a fixed prefill-decode allocation may fail to sustain these benefits as workload composition varies across tasks and over time. We therefore present Prorsa, an agentic RL framework for prediction-guided prefill-decode resource alloc

---

### [342] To Defer or Not to Defer? Online Learning with LLMs and Congested Experts

**链接**: https://arxiv.org/abs/2610.15128
**作者**: Vasileios Saketos, William Reveillard, Alexandre Proutiere, Sebastian Dalleiger, Ming Xiao
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern AI systems increasingly combine large language models (LLMs) with human experts, using the LLM to handle routine queries while deferring uncertain cases for expert review. When expert capacity is limited, however, deferral decisions must account not only for the reliability of the LLM but also for congestion in the expert queue. We formulate this as an online sequential decision-making problem in which, for each query, the system observes the confidence signal of the LLM's answer and must decide whether to output the answer or defer the query to a capacity-constrained expert. The reliability of the confidence signal is initially unknown and must be learned from expert feedback, which is both selectively observed (only deferred queries are labeled) and delayed by queuing. We propose \texttt{KL-PBD}, a learning algorithm that uses Kullback--Leibler lower confidence bounds on the unknown reliability parameters to guide deferral decisions. For $K$ confidence levels and horizon $T$, 

---

### [343] Humans vs. Machines: A Comparison With AI Agents in Software Reverse Engineering

**链接**: https://arxiv.org/abs/2610.14960
**作者**: Samuele Doria, Stefano De Rosa, Ruoyu Wang, Zion Leonahenahe Basque, Eleonora Losiouk and Simone Aonzo
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can an autonomous AI agent reverse engineer a binary as well as a skilled human analyst? Do they adopt the same strategy, and can agents scale to real-world programs? We compare human and LLM-based software reverse engineering (SRE): nine models tackle two compact static-analysis challenges previously solved by human analysts, scored with a common understanding rubric, and we record their complete interactions with IDA Pro. This lets us compare not only what humans and agents recover, but also how they investigate a binary. The best agents (GPT-5.5 Pro, Claude Opus 4.8, and Kimi K3) achieve statistically human-competitive understanding on both tasks, while weaker models remain far behind. Ablations show that the gap depends on code representation and workflow demands, not on model capability alone: open-weight models improve substantially with richer code representations, whereas frontier models show no significant change. Similar success rates hide different workflows. Humans repeated

---

### [344] Instructions Are Evidence, Not Objectives: Measuring Outcome Alignment of Agents

**链接**: https://arxiv.org/abs/2610.17757
**作者**: Kaiming Liu, Yuxuan Liu, Jinrui Ju, Minyuan Ruan, Xuanyu Lei, Peng Li 等 (7 人)
**来源**: cs.AI cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can follow complex human instructions to solve real-world tasks. In practice, however, initial instructions are often incomplete. In our analysis of 100 user-agent trajectories from SWE-chat, 56\% of initial instructions omit requirements that later emerge as necessary, and 52\% of the useful follow-up requirements could have been inferred from the project. A user states requirements from their own understanding of the task, and these \textbf{stated requirements} often differ from the \textbf{true requirements} that completing the task imposes. An agent should therefore treat the instruction as evidence rather than as the objective, inferring the true requirements from the instruction and the environment and satisfying them even when the user is not yet aware of all of them. We call this ability \textbf{outcome alignment}. In this work, we construct \textbf{TiGanEval}, a benchmark of software engineering and research tasks. In every task the user genuinely l

---

### [345] PID-Gated Continual Prompt Adaptation Under Noisy Feedback

**链接**: https://arxiv.org/abs/2610.16129
**作者**: Zhentao Xu
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying LLM agents in non-stationary environments requires continually revising their instructions as the task drifts, yet rewriting after every reported mistake can turn noisy feedback into persistent errors. This raises an often-overlooked scheduling question in prompt adaptation: when should feedback trigger a lasting instruction update, and at what editor-call cost? Taking inspiration from proportional-integral-derivative (PID) control, we introduce a family of lightweight gates that react to the current error, accumulate evidence over time, and roll back deterioration after an edit. We benchmark these gates against both simple baselines and advanced prompt optimizers (TextGrad and GEPA), over a diverse suite of drifting tasks, LLM parameter sizes, feedback-noise levels, and random seeds. PID-gated continual prompt adaptation yields a more favorable Pareto trade-off between task performance (high accuracy, low error) and editor-call budget than the baselines considered, pointing 

---

### [346] ClawLoop: Self-Improving Agents via Harness-Native Training Loop

**链接**: https://arxiv.org/abs/2610.14118
**作者**: Hansi Yang, Linji Hao, Hongyan Hao, An Wang, Han Wu, Qi Gu 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid advancement of Large Language Models (LLMs) has driven their deployment toward general-purpose harness environments, where LLM-based agents operate in sandbox workspaces and interact directly with file systems and shells. While numerous post-training pipelines exist for tool-use agents, their counterparts for harness-based agents remain scarce and are predominantly one-shot and teacher-dependent: a stronger external model synthesizes tasks and collects trajectories, the target agent is trained once, and evaluation results are consumed by human researchers rather than fed back into the loop. Such pipelines are inherently bounded by the capability of the external model and the scope of human prior, leaving no room for self-improvement. To address these limitations, we propose ClawLoop, a framework that enables self-improving without any external teacher model and with minimal prior dependencies. ClawLoop composes three phases into a self-sustaining cycle: Task Synthesis, which 

---

### [347] A Decade in a Day: Synthesizing Agent-Native Interfaces from Human-Oriented Software Evolution

**链接**: https://arxiv.org/abs/2610.15765
**作者**: Alan Wu, Wei Tao, Yiwen Guo
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are emerging as an important new class of users of desktop applications. However, existing desktop interfaces were designed for human end users or application developers, leaving agents to interpret visual controls or discover and compose low-level software operations. This mismatch can hinder even capable agents, yet it remains unclear what interface properties make desktop software easier for agents to use. To study this question, we treat software evolution as a natural source of interface variation and introduce DeskIF-Bench, a benchmark of 255 artifact-verified tasks across six desktop applications. By holding the task, agent, and verifier fixed while varying the software release, we measure how interface changes affect agent performance. Across two models and six applications, the newest release consistently outperforms the oldest. Trajectory analysis identifies three relevant interface properties: discoverability, granularity, and observability. Guide

---

### [348] ByteMark: A Unified Byte-Level Watermark for Detection Across Language Models

**链接**: https://arxiv.org/abs/2610.14427
**作者**: Xiaopu Wang, Runze Li
**来源**: cs.CR cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As watermarking of LLM-generated text enters deployment, users increasingly need to check text whose source is unknown. Existing detectors read the watermark through a specific tokenizer or embedding pipeline, and even if all providers adopted the same watermarking method, differences in these representations would leave their watermarks incompatible, and the text alone does not reveal which representation produced it. We propose ByteMark, a unified watermarking scheme that defines its signal on the UTF-8 bytes of published text. Models with different tokenizers embed this signal under one public specification and key, and a single detector verifies the text from the text and key alone. When the tokenizer or embedding model of a baseline detector is replaced, its detection degrades sharply, whereas ByteMark, which uses neither, retains its detection rate; ByteMark also remains detectable when participating models continue or rewrite the text.

---

### [349] Suggested Is Not Superseded: A Pre-Registered Evaluation of a System-One Model as a Memory-Retirement Gate

**链接**: https://arxiv.org/abs/2610.15710
**作者**: Xupeng Chen, Chenqian Le
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory for assistants needs a gate that decides when a new utterance retires an old stored claim. Benchmark labels for this step mark a pair as changed or not, so they cannot tell a gate that acts on established change from one that acts on a hint. We write a task contract that separates the two (SUPERSEDED vs. NEEDS-CONFIRMATION vs. COMPATIBLE), label 500 test pairs built from STALE (change pairs plus same-user controls) with three LLM annotators and two human adjudicators (one author and a second annotator; provenance reported), and evaluate Jev, a typed "System One" decision model, under pre-registered hypotheses. Of the 179 test pairs STALE marks as changed, 72 meet the contract's bar for an established change. Jev never retired a claim on 141 same-conversation non-changes. Its failure is premature retirement: the binary gate retires 39.2% of claims whose change is only suggested. A three-way decision cuts this to 15.5% at a 15.3-point detection cost, which misses our pre

---

### [350] EvoQuantLab: Training-Free Dual-Loop Evolution for Auditable Quantitative Research

**链接**: https://arxiv.org/abs/2610.17130
**作者**: Haolin Yang, Zhiqiang Qian, Chutian Chen, Jipeng Zhang, Tangjia Deng, Jian Xie 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated alpha factor discovery is critical for modern quantitative research. While large language models (LLMs) have increasingly been integrated into quantitative workflows, existing agent-based approaches remain highly susceptible to severe backtest overfitting. To address this challenge, we propose EvoQuantLab, a training-free, dual-loop self-evolving framework for robust factor discovery. Instead of relying entirely on LLM generation, EvoQuantLab deploys an inner genetic-programming (GP) loop that dramatically improves token efficiency while evolving typed factor expressions under structural and diversity constraints. An outer diagnosis loop then systematically audits evidence across cycles to drive protocol-level improvements. Furthermore, our evaluation pipeline applies multi-metric validation to rigorously filter out spurious factors before deployment. Extensive out-of-sample experiments across both daily and hourly frequencies -- covering equities and cryptocurrency -- demons

---

### [351] LYNX: Analytical Program Synthesis via Grounding and Closed-Loop Refinement

**链接**: https://arxiv.org/abs/2610.14777
**作者**: Ruichen Xia, Xiao Han, Dingyu Yang, Luwei Yang, Sai Wu, Dongxiang Zhang 等 (8 人)
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-powered data analytics aims to translate natural language instructions into executable analytical programs over underlying data. However, existing approaches, whether treating LLMs as intent-to-code translators or as standalone analytical engines, often fail to reliably align domain semantics with complex schemas and heterogeneous metadata, resulting in brittle execution and semantically inconsistent analytical outputs in real-world workloads. We present LYNX, a multi-agent framework that formulates LLM-driven analytics as a schema- and knowledge-constrained analysis problem rather than a single-pass generation task. LYNX organizes analytical synthesis into a closed-loop workflow of planning, generation, verification, and refinement through three role-specialized agents that collaboratively enforce schema grounding, semantic consistency, and execution correctness. To address domain ambiguity and schema misalignment, LYNX integrates Semantic-Structural Distillation and Stage-Aware A

---

### [352] From a Large-Scale Teacher to Efficient Multimodal Students for Search Relevance Prediction

**链接**: https://arxiv.org/abs/2610.16569
**作者**: Tomasz Gniazdowski, Mohammadreza Momenifar, Nadia Vase, Shahram Khadivi, Wiktor Walentynowicz, Nicola Ueffing 等 (9 人)
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Relevance prediction between user queries and items is a fundamental component of e-commerce search systems. Traditionally, high-quality relevance labels are obtained through human judgment, which is reliable but expensive, slow, and difficult to scale. Recent advances in large language models (LLMs) enable automated relevance judgment at scale, achieving performance comparable to human annotators. However, such systems often rely on large commercial LLMs with complex prompts, resulting in high inference costs and limited throughput. In this work, we propose a framework that bridges this gap by distilling a high-performing LLM-based relevance judgment system into efficient multimodal student models. We first curate a small, high-quality human-annotated dataset to serve as ground truth. Using this dataset, we develop a reliable LLM-as-a-judge pipeline through careful prompt engineering and iterative refinement. This pipeline is then used to generate large-scale relevance labels, which s

---

### [353] Separating Prompt Harmfulness from Interaction Safety via Partial Generation

**链接**: https://arxiv.org/abs/2610.16761
**作者**: Ram Vikas Mishra, Shashank Aggarwal, Jahnavi Kumar and Amit Awekar
**来源**: cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based information systems need safety guardrails. Most guardrails classify the prompt alone. If the prompt looks harmful, the system rejects it before any answer is generated. This is costly. Many rejected prompts would have received a safe response. Users lose help they should have received from the information system. This cost grows as conversational and generative search becomes common. Prompt-level labels treat harm as a property of the query. But harm depends on what the model actually writes. Existing input-output guards do look at responses. But they judge a finished response, so the decision comes after full generation. However, we observe that safety of model interaction with the input prompt can be inferred early with only partial output. So the system can start generating, watch the partial response, and stop only if it turns harmful. We test this idea in three steps. First, we build a dataset of 41,944 prompt-response pairs with seven open weights LLMs from three famil

---

### [354] AlphaRLM: Aligning Language Models for Literature-Grounded Symbolic Factor Discovery

**链接**: https://arxiv.org/abs/2610.14959
**作者**: Jie Huang, Yuecheng Hong, Yao Chen, Hao Zhong, Linfeng Xiao, Xudong Liu 等 (8 人)
**来源**: cs.AI cs.CL cs.LG q-fin.PM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Formulaic alpha mining seeks to discover executable expressions that capture predictive market signals in a vast, noisy search space. Recent LLM-based approaches use prompting, iterative search, or seed-factor evolution, leaving direct factor construction through policy learning less explored. To address this, we introduce AlphaRLM, a reinforcement-learning framework that trains LLMs to construct executable symbolic factors from financial literature without input factor expressions. AlphaRLM incorporates Literature-Guided Operator Assembly (LEGO), which conditions factor construction on literature-derived ideas and executable operators, providing semantic priors for exploration. It further aligns the generation policy with market feedback through executable-validity and grouped-return-separation rewards that capture non-monotonic structures across factor quantiles. Extensive experiments on CSI 300, CSI 1000, and S&P 500 show that AlphaRLM outperforms strong factor-mining and LLM-based 

---

### [355] PsyBer-Agent: A Psychology-Driven User Agent for Recommender Systems

**链接**: https://arxiv.org/abs/2610.13989
**作者**: Chong Zhang, Qijie Shen, Haichao Zhang, Can Wang, Xiaobo Jin, Jia Wang
**来源**: cs.CL cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating recommender systems before deployment requires simulators that remain realistic over long, closed-loop interaction cycles. Current LLM-based agents generally function as surface imitators that generate realistic short-term responses but fail to capture the underlying user dynamics such as fatigue, affect, and shifting preferences. We propose PsyBer-Agent, a psychology-inspired simulator that models these dynamics through its Psy-Engine. This engine represents each user with three evolving, model-defined latent states. To calibrate simulated behavior against real interaction logs, we align log-conditioned reference trajectories with simulator-generated latent-state trajectories via Unbalanced Gromov--Wasserstein optimal transport. This approach provides structured supervision for a lightweight policy without the computational burden of fine-tuning the backbone LLM. We also introduce WebSim and the PsyBer Benchmark, which encompass multimodal scenarios and seven recommender ba

---

### [356] LongHisDoc: A Comprehensive Benchmark for Chinese Long Historical Document Understanding

**链接**: https://arxiv.org/abs/2610.14531
**作者**: Zeyu Shan, Yongxin Shi, Shihang Wu, Peirong Zhang, Yuanyuan Fang, Zhaopeng Wang 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chinese historical documents are invaluable cultural treasures, but their complexity poses significant comprehension challenges for non-specialists. Despite the success of Large Language Models (LLMs) and Large Vision-Language Models (LVLMs) in modern document tasks, their capabilities in Long (full-book) Historical Document understanding remain largely unexplored. To bridge this gap, we introduce LongHisDoc, the first benchmark tailored for long historical document understanding. LongHisDoc comprises 1,012 expert-annotated QA pairs derived from 101 PDF documents, with an average of 85.1 pages and 42,776.4 tokens per document. It spans 10 categories and features four QA types: single-page, cross-page, multi-hop, and unanswerable. Answering these questions requires integrating multimodal evidence from text, layout, and visual elements. Our evaluation reveals that the top-performing LVLM and LLM achieve only 62.9% and 69.9% accuracy, respectively, highlighting a substantial performance g

---

### [357] Evaluating LLMs as Agentic Workflow Executors in Real-World Customer Support Skills

**链接**: https://arxiv.org/abs/2610.14346
**作者**: Md Tahmid Rahman Laskar, Gundeep Singh, Xue-Yong Fu, Karol Chang, Kevin Sanders, Shi Zong 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise customer-support agents increasingly rely on Large Language Models (LLMs) to execute bounded, tool-using workflows. We study this problem through the lens of Skill LLMs: specialized executors that operate within a selected skill context and must complete a narrow, stateful workflow under policy and tool constraints. We present a benchmark construction pipeline that mines recurrent workflows from real-world transcripts, converts them into structured skill descriptions, maps them to tool requirements, simulates environment state with Model Context Protocol (MCP)-compatible mocks, and generates multi-turn tool-using dialogues. Using this benchmark, we conduct a large-scale zero-shot evaluation of 17 language models spanning closed model families and deployment-oriented open-weight models from 1.7B to 14B parameters, each judged independently by five strong LLM judges, plus a deterministic rule-based evaluator that checks tool coverage, hallucinated tool use, and unsupported cla

---

### [358] EAU: Environment-Agent-User Co-evolution for Training User-Centric Agents

**链接**: https://arxiv.org/abs/2610.16523
**作者**: Min Cai and Dan Zhang and Gao Xing and Libin Ma and Zhaohui Xu and Xi Ye
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training LLM agents to interact with users over multiple turns is challenging because the learning signal depends not only on the agent, but also on the user simulator and environment, which jointly shape the agent's experience. Simulated users can be stochastic or inconsistent, while environments may contain unreliable tools, incomplete state coverage, and incorrect verifiers. Prior work mainly addresses the resulting instability through reward shaping or denser supervision, while treating these components as fixed. We instead introduce EAU, a meta-agent framework for environment--agent--user co-evolution. During training, EAU monitors trajectories, tool traces, rewards, and training statistics; diagnoses failures and uninformative interactions; and proposes targeted modifications to the user simulator, environment, reward design, and RL configuration. Validated changes are hot-swapped into the ongoing run, allowing the training setup to evolve together with the policy. These adaptati

---

### [359] Evaluating Semantic Relation Knowledge through Bidirectional Relation Prediction from Gloss Pairs

**链接**: https://arxiv.org/abs/2610.14442
**作者**: Zhihan Cao, Adam Nohejl, Hitomi Yanaka
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic relations organise word senses and are fundamental to lexical semantics. In order to evaluate semantic relation knowledge of large language models (LLMs), we propose a challenging task in which an LLM predicts the relation between two glosses (definitions of senses) presented in two different orders. The predictions for the two orders are evaluated for consistency with the symmetry or asymmetry of semantic relations. Our task is designed for both monolingual and cross-lingual evaluation, allowing us to examine whether relation knowledge remains accessible when the same senses are verbalised through glosses in different languages. We construct a dataset of 3,069 sense pairs, with each sense verbalised in English, Greek, Romanian, Turkish, and Japanese. Experiments with 17 LLMs in zero-shot and five-shot settings reveal generally poor performance. In each setting, only eight LLMs achieve a macro-averaged F1 score significantly above a random baseline, and only one (zero-shot) an

---

### [360] Do Personalized LLMs Need the Whole Conversation? Matching the Full History with Only 5% of Its Text via Relevance-Filtered Context

**链接**: https://arxiv.org/abs/2610.14952
**作者**: Erika Hayashi, Andrew Shin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized assistants accumulate long conversation histories, and passing the whole history to an LLM with every request is costly. We show that it is also unnecessary. On PersonaMem-v2 (180 questions), with GPT-5.6-terra and Claude Opus 5.5 as judges, a relevance-filtered context, built by sentence-level retrieval that ranks the history by similarity to the current request and stops at a fixed budget, matches full-history accuracy with only 5% of the text, cutting the judge's input about 20-fold. An LLM summary of the same length performs on par, but it needs an LLM to read the entire history, whereas retrieval needs only a small embedding model. While both sentence-level retrieval and LLM summary perform strongly, retrieval does so while placing the relevant evidence in the context for only 61% of the questions, and an oracle given only that evidence beats the full history by 15.6 points, making better context selection a promising path to surpassing the full history.

---

### [361] Coding LLMs Can Be Harnessed to Learn Interpretable Models from Data

**链接**: https://arxiv.org/abs/2610.14006
**作者**: Aditya Kumar, Cassandra A. Cohen, William W. Cohen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Since compact, interpretable classifiers correspond to simple programs, it is natural to ask if LLM-based coding agents can be used to learn interpretable models from data. In this paper we present a simple harness that repeatedly prompts a coding LLM to produce the next rule in a rule set, given a sample of labeled examples. We show that this approach is competitive with, and often superior to, state-of-the-art rule-learning methods on tabular data, especially with small training sets, and wins by large margins on text, including against another LLM-based rule learner; that this approach outperforms standard harnesses, and that the approach immediately leads to new kinds of interpretable models, since coding agents are not restricted to search a highly restricted hypothesis space. In addition to the advances made in learning interpretable models, these results are of interest because they introduce a new class of coding benchmarks - construction of interpretable classifiers - which in

---

### [362] PAT: A Personality-Driven Augmentation and Transfer Learning Framework for Depression Detection on Social Media

**链接**: https://arxiv.org/abs/2610.15044
**作者**: Shengwu Zheng, Yuzhe Ding, Xiaohui Liang, Fei Li, Chong Teng, Donghong Ji
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depression is a prevalent mental disorder that affects millions worldwide, with early detection crucial for effective intervention. While exist?ing methods have achieved promising results in automated depression detection, they face two key limitations: (1) noise in post screening: symptom-based semantic screening is easily misled by superficial lexical patterns, thereby introducing false-positive posts; (2) weak op?timization of the post encoder: relying solely on coarse user-level supervision signals pre?vents models from capturing depressive cues within individual posts. To address these limita?tions, we propose PAT, a Personality-driven Augmentation and Transfer learning frame?work. In the first phase, PAT optimizes a post?level encoder via a fine-grained contrastive learning objective, utilizing LLM-based data augmentation driven by classic personality the?ories to alleviate data scarcity. In the second phase, the trained post-level scorer is deployed for high-quality post filteri

---

### [363] Select or Rewrite: Oracle-Guided Fine-Tuning for Generative ASR Post-Editing from N-Best Hypotheses

**链接**: https://arxiv.org/abs/2610.15056
**作者**: Shiran Liu, Gaohui Xu, Sergio Burdisso, Thibault Ba\~neras-Roux, Shashi Kumar, Petr Motlicek
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can post-edit ASR by using linguistic context to compare N-best hypotheses and rewrite the transcript when needed, often improving WER without retraining the recognizer. However, prompt-only correction is brittle: it may over-edit when top-1 is correct and hallucinate when the reference is absent, and often needs very large models. We propose oracle-guided fine-tuning that turns N-best lists into supervision via three curated pools: corrections (reference in the list but not top-1) to teach selection, regularizers (top-1 correct) to discourage unnecessary rewrites, and hard negatives (reference absent) to suppress hallucination. Fine-tuning on this data provides more effective supervision than random subset fine-tuning for learning a hybrid select-or-rewrite policy, with the clearest gains from around 3B parameters on the proprietary dataset but less conclusive results on CommonVoice, a divergence suggesting that public read-speech text may overlap with LLM pretra

---

### [364] Lumen-bench: Cross-Lingual Safety Gaps and the Say-Do Problem in Tool-Calling Large Language Models

**链接**: https://arxiv.org/abs/2610.15134
**作者**: Giovana Kerche Bon\'as, Thiago Laitz, Thales Sales Almeida, Jo\~ao Guilherme Alves Santos
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a large language model refuses an unethical request, what does refusal mean? In conversation, refusal is bounded by what the model says; once the model is equipped with executable tools, what it does can diverge from what it says, a failure mode that English-only evaluations cannot fully reveal. We introduce Lumen-bench, a behavioral benchmark of tool-calling ethics spanning 30 models, five languages (Portuguese, English, Spanish, Mandarin Chinese, Hindi), 108 Portuguese-authored scenarios, six social-pressure conditions, two system prompts (ethical and neutral), and 21 generic tools. The evaluation comprises 194,400 trials. Judgments come from a reasoning-model judge (o4-mini), calibrated against one Portuguese-speaking author ($n=83$; harmful/non-harmful $\kappa=0.78$), compared with two other provider judges (Fleiss' $\kappa=0.78$, $n=607$), and complemented by retrospective sandbox replay. Four findings emerge. (i) Within-model comparisons support higher harmful-action rates i

---

### [365] SonicWorld: Source-Centric Latent Dynamics for Spatial Audio Reasoning

**链接**: https://arxiv.org/abs/2610.17131
**作者**: Chenlong Wei, Hanling Wang, Mingjin Lou, Yufan Shi, Yandong Sun, Sheldon Yu 等 (9 人)
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic spatial audio reasoning requires a model to associate changing acoustic observations with the correct source and recover its spatial state at a queried time or interval, a challenge intensified by overlapping speech and source motion. To study this problem, we introduce Sonic-Bench, comprising 2.8K first-order Ambisonics clips and 28.8K target-specific question-answer pairs across 480 simulated indoor scenes. The benchmark covers localization, distance estimation, and motion reasoning in single- and dual-source settings. We further propose SonicWorld, which integrates physical, learned acoustic, and semantic features into persistent source states through learned transitions and recurrent updates, and projects them into an Omni LLM for spatial reasoning. Compared with Spatial-Omni on the Sonic-Bench test split, SonicWorld improves direction accuracy from 31.98% to 34.69% and reduces azimuth error from 57.22{\deg} to 48.01{\deg}. In zero-shot transfer to Spatial LibriSpeech, Soni

---

### [366] SkillScreen: High-Recall Screening of Malicious Agent Skills with Decision Models

**链接**: https://arxiv.org/abs/2610.17727
**作者**: Jerrold Huang, Junwei Quan, Saiyue Lyu, Zihan Guo, Yingqiang Ge
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills turn natural-language instructions into actions, creating a security challenge: legitimate automation and malicious behaviour can look deceptively similar. A practical screen must catch nearly every attack while keeping the review load manageable. We present SkillScreen, a compact decision model trained to score skill maliciousness directly from SKILL.md in a single forward pass. On MaliciousSkillBench, SkillScreen flags 20-25% of benign skills at 99% recall on unseen attack families, substantially fewer than the word-level classifier and prompted LLM judges tested. Under the same training protocol, it also generalizes better than a fully fine-tuned encoder to unseen sources. Yet unfamiliar benign sources sharply increase false positives, showing that recognizing new attacks does not ensure reliable screening of new skill collections. Our results demonstrate the value of task-trained decision models for high-recall skill screening. Project page: https://jerroldh.github.io/

---

### [367] SemTree: Judge-Aware Semantic Decision Trees for Inspectable and Repairable Rule Decisions

**链接**: https://arxiv.org/abs/2610.13999
**作者**: Jincheng Gao, Wei Ding, Shuo Sun
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rule decisions such as content moderation, advertising compliance, and eligibility checks combine several conditions, exemptions, and missing-information cases, and an error can be fixed only once the failing condition is known. We introduce SemTree, a framework that represents a rule decision as a semantic decision tree: each node is a natural-language question with explicit Yes/No/Unknown criteria, a pluggable semantic judge answers it, and the branching structure is compiled on the answers that this judge actually gives. The executed path is the reasoning behind every decision, so errors are repaired where they occur: a reviewer corrects a single node and replays the rule, corrected nodes become training labels for the judge, and a tool-using LLM editor revises questions and subtrees while observing execution results. On all 8,276 ShARC test cases, a tree executed by a hosted judge reaches 67.70% accuracy with 2.99 questions per case, on par with asking the same judge for the final 

---

### [368] On the Calibration of Crowdsourcing Aggregators

**链接**: https://arxiv.org/abs/2610.16815
**作者**: Gabriel Singer, Reda Arab, Ma\"issa Frikha, Samuel Gruffaz, Olivier Vo Van, Nicolas Vayatis 等 (7 人)
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Calibration has been extensively studied for classifiers, but remains largely unexplored for crowdsourcing aggregation methods, which are increasingly used for making probabilistic decisions. To the best of our knowledge, we provide the first theoretical and empirical study of calibration in label aggregation. To our great surprise, we find that widely used aggregation methods can be severely miscalibrated, and in opposite directions: Majority Vote is underconfident while model-based aggregators are overconfident. We prove that the Bayesian aggregator is perfectly calibrated under its data-generating model. We also show that exact calibration of weighted majority votes requires highly restrictive conditions, which helps explain why Majority Vote is generally miscalibrated in realistic crowds. Empirically, we study calibration across $39$ human crowdsourcing datasets and LLM-based crowds. In both cases, we observe systematic miscalibration for aggregation models such as Majority Vote, D

---

### [369] Auditing Failure Attribution: Label Predictability and Judge Behavior

**链接**: https://arxiv.org/abs/2610.17747
**作者**: Tianyang Xu, Jing Gao
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Failure-attribution benchmarks ask an LLM judge which step or agent caused a failure. A high score should mean the judge checked the faulty step against the run (a cross-step check). However, spurious signals (surface cues) that predict the annotation can produce a high score. In this paper, we propose four tests to separate checking from cue use. Input restriction asks whether partial input predicts the annotation. Cue following checks whether moved cues change answers. Residual accuracy scores judges where cue-only predictors fail. Aggregation asks whether the failure mix or metric changes rankings. Real observations motivate these tests: on three benchmarks, simple predictors match or beat GPT-4.1. In two Who&When Pro systems, a classifier reading one step's reasoning finds 95-100% of faulty steps, motivating input restriction. In one of them, error injection leaves no reasoning after the faulty step; judges fine-tuned on its labels beat GPT-4.1 by 41 points. Adding task-related rea

---

### [370] Diff Diffusion: Predicting Edit Paths with Diffusion Models for Efficient Code Editing

**链接**: https://arxiv.org/abs/2610.17831
**作者**: Xiaolong Xu, Hao Jiang, Bo Jiang, Zhiwen Deng, Ningyuan Sun, Bingzhou Chen 等 (8 人)
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion large language models (dLLMs) are appealing for code generation because they can update many tokens in parallel, yet many are optimized for sequence synthesis rather than edit prediction. This setting is poorly matched to modern AI-assisted IDEs, where edit prediction must infer the next code change from recent edits, the current file, and cursor-local context. Such changes are usually sparse and preserve most source tokens, so regenerating a full code segment wastes computation. We propose Diff Diffusion, a diffusion-inspired LLM framework for code editing that predicts edit paths from an original snippet to its revised form. Diff Diffusion represents denoising as structured edit operations, and combines this formulation with multi-stage training and efficient parallel decoding. By focusing computation on changed regions, Diff Diffusion supports accurate low-latency edits and multi-position parallel modification. Across public edit-completion benchmarks, edit-prediction eval

---

### [371] The AI's Poker Face: Contrasting Persuasion and Sycophancy in Voice-Based Multi-Turn Conversations

**链接**: https://arxiv.org/abs/2610.14124
**作者**: Ilia Frantzi, Bernie Hogan, Max M. Lang, Paul C. Bauer
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As interactions with large language models (LLMs) become increasingly routine, concerns about their capacity to influence users' beliefs grow. Yet how such influence unfolds in sustained dialogue remains insufficiently understood. We conduct a randomized controlled experiment (N=616) where participants engage in multi-turn, spoken dialogue with an LLM under three conditions: non-directive, and two directive conditions maintaining opposing stances on a polarizing topic (the merits of feminism). We examine opinion change, rhetorical strategies, and sycophancy, distinguishing the semantic content of LLM argumentation from the pragmatic strategies used to manage the interaction. Both directive conditions shifted opinions toward their assigned stances, but asymmetrically: shifts were larger for pro-feminist positions, which also elicited distinct rhetorical strategies. The non-directive condition, likewise shifted opinions pro-feminism. Social sycophancy, though near-universal, was not asso

---

### [372] Trace-to-Architecture: Capability Bottleneck Diagnosis for Harness Revision

**链接**: https://arxiv.org/abs/2610.16725
**作者**: Wenfeng Wang, Jianrui Shi, Mingang Guo, Jiayuan Ma, Yuqi Lu, Jiajun Sun 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving an LLM agent requires knowing what to change when it fails. Similar failures can require different fixes, and resolving one problem can expose another. We introduce Trace-to-Architecture (T2A), a framework that uses execution trajectories to determine what to change in an agent's harness and when those changes apply. A development agent diagnoses failures using execution evidence from successful and failed tasks, revises the corresponding harness components, and then checks whether target tasks improve, selected successful tasks remain successful, and the edits are actually triggered. New execution evidence guides subsequent diagnosis and revision. Across ALFWorld, ScienceWorld, and AppWorld, T2A achieves the highest aggregate score for all three evaluated task agents, exceeding their respective strongest baselines by 6.2--30.3 points. We also integrate T2A's diagnosis and validation procedures into Meta-Harness, improving the resulting harnesses' mean ScienceWorld score by 2

---

### [373] Structural Baselines Matter for Agent Failure Detection and Attribution

**链接**: https://arxiv.org/abs/2610.16661
**作者**: Ramesh Arvind Naagarajan, Stefan Streif
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM agent using tools can fail silently. It stops before the task is done, raises no error, and answers fluently. Two kinds of monitor address this, one deciding whether a run failed and the other naming the step where failure became unavoidable. Much of the reported performance on both tasks comes from regularities that need no model. Failing runs are longer, and the step labelled decisive is usually the last. A rule that always names the last step is correct $67\%$ to $96\%$ of the time here, without reading the run at all. That ceiling reflects how the labels were written, not how agents break. On failures whose decisive step replay can confirm, it falls to near chance. Reporting gain over that rule therefore changes what a score means. Under that correction, methods tested here gain nothing on give-up failures, while several published systems keep a clear advantage on other splits. For detection, the agent's internal states beat transcript length and text similarity on the agent

---

### [374] Audit tools of the trade: Automated Auditor Elicitation Can Be Sensitive to the Context the Auditor Is Given

**链接**: https://arxiv.org/abs/2610.16911
**作者**: Ben Slater, Ryan Lundqvist, Leo Richter, Kevin Wei
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Does providing additional context to automated AI auditors improve their effectiveness? Using the Petri tool to audit LLM coding agents, we test the impact of providing two types of resources (an external codebase and benchmark transcripts) to LLM auditors, across four auditor-target LLM pairs and three behaviours (harmful compliance, reward hacking, sycophancy). (1) External codebase: We provide the auditor LLM with a fixed, external open source codebase, which prior work finds improves the realism of synthetic audits. Providing this resource suppresses reward hacking in both auditor-target pairs whose baseline rate is above the floor (4.8 to 1.3 and 3.9 to 1.8 on Petri's default 1-10 scale); the remaining two pairs sit at the floor throughout. The suppression recurs in three of four pairs under a different scenario and resource bundle. (2) External benchmark transcripts: We provide the auditor with transcripts of the target's performance on benchmarks measuring similar behaviours, in

---

### [375] Socratic Skill Learning: Interleaving Teaching and Practice for Transferable Agent Skills

**链接**: https://arxiv.org/abs/2610.17860
**作者**: Letian Zhu, Han Li, Yifan Yao, Xinping Lei, Xinyu Che, Jiahao Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent Skills improve LLM agents by making task knowledge reusable across sessions. Learning transferable Skills requires evidence about a procedure and its conditions of use, which a successful task attempt can leave untested. We introduce Socratic Skill Learning (SSL), which interleaves expert teaching with Student practice. An Educator guides investigation while the Student remains the sole environment operator and Skill author, able to question, test, and adapt advice. To test reuse beyond the learning task, we construct SkillTransferBench, with 35 task families and 408 executable cases, pairing public variation specifications with held-out evaluation in fresh solver sessions. On the main 22-family, 155-case cohort, Fixed-Window SSL reaches 0.801 utility, versus 0.723 without a Skill, 0.761 for adapted Trace2Skill (trajectory distillation), and 0.751 for adapted SKILL-KD (contrastive distillation). Across three model pairs on shared families, interleaved guidance outperforms expert 

---

### [376] Lightweight Scheduling Policies for Continuously Batched LLLM Serving Across GPU Architectures

**链接**: https://arxiv.org/abs/2610.15899
**作者**: Ashman Mehra, Akshan Agarwal, Aryeh Carmi
**来源**: cs.DC cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model serving is increasingly limited not only by model size and GPU speed, but also by scheduling during autoregressive decoding, where continuous batching interleaves requests at token granularity as sequences arrive and finish. We study whether lightweight scheduling policies can improve latency-throughput tradeoffs without changing model architectures, kernels, or deploying learned schedulers. We implement a Python/PyTorch continuous-batching testbench with real Hugging Face execution and evaluate eight policies across 1,152 GPU-model-scheduler-workload runs using ShareGPT-derived traffic, six Qwen, Gemma, and Mistral models, and Modal L40S, A100, and H100 GPUs. Scheduler choice changes throughput, TTFT, completion latency, and tail behavior under fixed model, GPU, workload, batch size, and prefill budget. Aging shortest-prompt-first is the strongest practical baseline in many L40S and mixed-workload settings, while oracle remaining-length scheduling shows that job-s

---

### [377] Judges Follow the Reference: The Derivation Gap in Verifying Tool-Call Arguments

**链接**: https://arxiv.org/abs/2610.18497
**作者**: Linhai Ma, Yan Wang, Lingfei Qian, Yupeng Cao, Victor Gutierrez Basulto
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-call judges evaluate argument values proposed by LLM agents. We find that they accept a correct value less often when their input holds no reference for it, that is, no text that says what the value should be. This happens when the value is a default value from the function schema that the user did not mention, when it has to be inferred, or when the text it comes from was cut from the judge input. We call this drop in acceptance the derivation gap. It appears across all seven judges we evaluate, including System One models CLM and Jev. The gap is not only a truncation artifact: correct default values have the largest gap on a benchmark with no truncation. A controlled source-relocation test shows that judges follow the reference in their input: they favor a visible incorrect value over a correct value whose source is hidden. We introduce DeRef (Derived Reference): a separate model reads the full history without seeing the candidate and writes a reference for the judge. Across thr

---

### [378] NepPlural: A Human-Anchored Benchmark for Persona Annotation in Nepali Migration Discourse

**链接**: https://arxiv.org/abs/2610.15732
**作者**: Jinu Nyachhyon, Anish Khatiwada, Bimal Timilsina
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pluralistic alignment asks that language models faithfully represent a society's diverse, competing values rather than collapse them into one dominant viewpoint, yet flagship pluralistic-alignment datasets remain heavily skewed toward Western respondents. We introduce NepPlural, a human-anchored benchmark for modelling competing socio-cultural personas in Nepali public discourse on youth migration and brain drain. We curate 2,148 code-mixed (Devanagari, Romanized Nepali, English) YouTube comments, annotate them along a four-axis persona taxonomy (Intent, Primary Driver, Value Orientation, Affect) plus an explicit No-Persona class, and build a 300-comment gold set labelled independently by three native Nepali speakers (mean Fleiss' $\kappa \approx 0.55$). Using this gold set to audit automatic annotation, we find that LLM annotation reliability is driven by protocol. Labels collected in batches through chat interfaces reach only near-chance inter-model agreement ($\kappa \approx 0.17$).

---

### [379] Towards Safe Autonomy for Computer Use

**链接**: https://arxiv.org/abs/2610.18508
**作者**: Dominik Seip and Bartol Markovinovi\'c and Matthias Hein
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The safety of LLM-based agents currently rests on alignment training and safety classifiers, neither of which can rule out that a sophisticated indirect prompt injection (IPI) goes through and causes significant harm. Recent work therefore builds agents with information-flow guarantees that rely on structured tool interfaces to interact with the environment. Computer Use Agents (CUAs) act visually on the computer screen, which does not provide a boundary between trusted first-party interfaces and untrusted, potentially attacker-authored content. Actions are equally ambiguous: a click may land on an application toolbar or a button controlled by an attacker. Treating the user as the source of trust and confirming each sensitive decision produces confirmation fatigue, with the risk of missing harmful actions. We introduce SA-CUA, a dual-LLM framework that generates a reliable trust boundary for CUAs by deriving conservative deterministic rules from the accessibility tree for unmasking tru

---

### [380] Self-Distillation with Verbal Regularization

**链接**: https://arxiv.org/abs/2610.16354
**作者**: Jiazheng Li, Yawei Li, Junru Lu, Zhenyi Shen, Di Yin, Lin Gui 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy self-distillation (OPSD) trains a large language model using supervision from a teacher instantiated from the same model as the student. The teacher is conditioned on privileged information (PI), such as verified solutions. The student, which does not observe PI, learns from the teacher's next-token distributions along its own sampled responses. However, PI can bias supervision toward shortcut reasoning with limited verification or reconsideration, accompanied by a sharp drop in the entropy of the output distribution. To address this challenge, we introduce self-distillation with verbal regularization (VRSD), which uses system prompts to regulate how the teacher uses PI, thereby encouraging rethinking and exploration to counteract premature commitment. Theoretically, we model prompting as attenuating the influence of PI on the teacher distribution and derive conditions for entropy preservation. Across three models and four tasks, VRSD improves Pass@1 over OPSD in 11 of 12 mod

---

### [381] TextualRL: Textual Reinforcement Learning for Context Management

**链接**: https://arxiv.org/abs/2610.18216
**作者**: Tianyu Huai, Jie Zhou, Bo Mao, Qin Chen, Liang He, Xipeng Qiu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can adapt to task feedback by revising the textual context that guides their behavior, without changing their model parameters. However, turning execution rewards into reusable context updates is challenging: individual trajectories offer limited comparative evidence about what to change, while task-specific fixes may overgeneralize when incorporated into a shared context. We introduce TextualRL, a gradient-free reinforcement learning framework that treats a group of rollouts from the same task under the same context, rather than an isolated trajectory, as the unit of policy critique. Groupwise Policy Critique contrasts successful and failed rollouts within a task; when outcomes are uniform, it draws on cross-task evidence to identify behaviors worth preserving or formulate repair hypotheses. Cross-Group Policy Update reviews the resulting proposals against evidence pooled across groups, including observations that yield no proposed edit, to refine their content and applicab

---

### [382] Relational Semantic Grounding for Test-Time Discovery

**链接**: https://arxiv.org/abs/2610.14721
**作者**: Tianle Liu, Gongbo Cheng, Chenggong Ni, Minming Gu, Tao Zhou, Fuyuan Hu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-Time Discovery (TTD) aims to recognize known classes and detect novel ones from a continuous unlabeled test stream after deployment. Existing TTD methods mainly rely on visual clustering or prototype comparison, and can only assign anonymous labels to discovered classes, leaving them difficult to interpret in open-world applications. In this paper, we propose SEGA, a Semantic Grounding with Attributes framework for TTD. SEGA leverages large language models to generate attribute-rich descriptions for known classes and constructs an attribute-anchored visual-semantic space during training. At test time, we introduce Relational Semantic Grounding (RSG), which grounds unknown samples with similar and dissimilar known-class anchors, prompts the LLM to generate candidate concepts, and reranks them in the learned semantic space. The selected concept is further used for confidence-guided test-time semantic stabilization. By coupling attribute-level semantic alignment with relational conce

---

### [383] REVEAL: Reverse Engineering Agentic Latents from Frontier-Model Traces

**链接**: https://arxiv.org/abs/2610.16288
**作者**: Yuetian Du, Meng Wang, Yucheng Wang, Zhangzhe Chen, Wei Wang, Boyu Yang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier LLM agents perform complex interactive tasks, but their inference costs motivate transferring their experience to smaller open-source agents. Distillation and latent communication typically require target-model training or access to source-model internals. We study how textual frontier-model trajectories can provide reusable local controls for a frozen agent. Inspired by protocol reverse engineering, we introduce $\textit{Agentic Latents}$, comprising anchored states and dynamic profiles of feedback--response cycles elicited by replay in the target model. Our training-free framework, $\textbf{REVEAL}$ ($\textbf{REV}$erse $\textbf{E}$ngineering $\textbf{A}$gentic $\textbf{L}$atents), uses these profiles and trajectory outcomes to match and select local events from successful and failed rollouts of the same task and source model. Their response-transition contrasts yield a target-specific steering direction, applied before each response. Within-benchmark evaluations on Terminal-

---

### [384] Generalizable Model Editing Could Be More Than Direct Generalization

**链接**: https://arxiv.org/abs/2610.15707
**作者**: Xiaotian Ye, Chunyao Yang, Xiaohan Wang, Junkai Chen, Yongqi Duan, Mengqi Zhang 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A central desideratum in model editing is generalization to complex tasks, which prior work formalizes under a direct generalization paradigm: treating and evaluating LLM behavior as an input-output mapping and expecting a factual update to alter outputs on reasoning tasks. Yet despite substantial empirical effort, the field consensus remains that such generalization is highly challenging and elusive. However, when we deploy the latest models in an in-the-wild chatbot-user setting, we surprisingly find that even classical editing methods exhibit remarkably fluent generalization behavior. This motivates us to revisit the obstacles to generalization and the limitations of the prevailing paradigm. We find that direct generalization is fundamentally constrained both theoretically and practically: theoretically, it suffers from an identifiability issue; and practically, existing approaches attempting to circumvent this are further hindered by the ambiguity of their constructed biases and by

---

### [385] AffectWorld: Benchmarking Emotion-Driven Future World Prediction

**链接**: https://arxiv.org/abs/2610.18305
**作者**: Changhao Song, Yacong Chen, Hui Gao, Yazhou Zhang, Peng Zhang
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The world encompasses both physical environments and human actors. Predicting its evolution requires understanding both physical laws and how emotions shape human actions. However, existing world model benchmarks primarily assess physical plausibility and perceptual quality, leaving emotion-driven world evolution largely untested.We introduce AffectWorld, a benchmark that evaluates the chain Emotion-Action-World State through three tasks: World-State Consistency, Emotion-Action Consistency, and Causal Consistency. It comprises 1,498 everyday video samples annotated with plausible emotions, action tendencies, and atomic world-state constraints. A counterfactual subset of 233 samples tests whether changing an agent's emotion under fixed scene and event conditions yields corresponding changes in actions and consequences. We define eight metrics across the three tasks and an additional counterfactual metric, combining automatic visual assessment with human-calibrated VLM/LLM judgments. Eva

---

### [386] CHEAR: Confusion-Hierarchy Evidence-Aware Reasoning for Cost-Efficient Human Activity Recognition

**链接**: https://arxiv.org/abs/2610.15298
**作者**: Xiangqing Lu, Tao Zhu, Mingxing Nie and Liming Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) offer a new approach to wearable-sensor-based human activity recognition. Retrieval-augmented generation (RAG) further introduces similar motion examples and discriminative sensor knowledge, enabling decisions grounded in observations relevant to the current query. More evidence, however, does not necessarily mean better-organized evidence. When online prompts and LLM agents primarily orchestrate inference, decisions about which activities to compare and when to invoke discriminative knowledge remain concentrated at inference time. As the activity vocabulary grows, the model must repeatedly process more candidates and associated knowledge, whereas pruning candidates too early risks excluding the true activity. We propose confusion-hierarchy evidence-aware reasoning (CHEAR), which moves part of this knowledge organization offline. CHEAR constructs and validates an activity hierarchy from recurrent cross-subject retrieval errors and builds corresponding activ

---

### [387] Pick the Mixture, Not the Samples: Combinatorial Data Selection for LLMs

**链接**: https://arxiv.org/abs/2610.14028
**作者**: Luyang Zhang, Jialu Wang, Bebei Li
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data selection for LLM fine-tuning faces two facts about real training: data pools draw from many distinct domains, and evaluation spans diverse tasks. As a result, the same sample helps different tasks differently, and samples interact during training so that a subset's value is not the sum of its parts. Current data-selection methods leave these realities largely unaddressed. We formalize them as Combinatorial Data Selection (CDS), a framework that separates attribution (how samples are scored) from selection (which subset to pick) and models the non-additive interactions among samples. On a real instruction-tuning data pool, we find substantial cross-domain complementarity (joint utility exceeds the sum of singletons), alongside redundancy within domains. Inspired by this, we propose Mixture-then-Select, a two-stage algorithm that first decides how many samples to take from each domain, then ranks samples within each domain by attribution score. Theoretically, the gap to the optimal

---

### [388] Think in Strategies, Act with Tools: Traceable Agentic Optimization for Combinatorial Problems

**链接**: https://arxiv.org/abs/2610.14736
**作者**: Zhongnian Li, Shi Xu, Peng Ying, Weikang Gong, Zhixiao Wang, Xinzheng Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Optimization by PROmpting (OPRO) directly leverages Large Language Models (LLMs) to generate candidate solutions through natural-language prompting. However, OPRO's optimization process is difficult to track, which prevents LLMs from capturing useful information accumulated over previous iterations, thereby limiting solution quality. To address this limitation, we propose a Tool-Augmented Strategic Agent (TASA) which summarizes and exploits trajectory to improve solution quality. Specifically, TASA plans the strategy for each step based on the optimization trajectory, which decomposes the optimization process into traceable strategy selections. Moreover, we leverage LLM to construct problem-specific tools and introduce a strategy-guided adaptive tool planner, which efficiently utilizes the information of trajectory to update solutions. We establish local convergence under persistent exploration and evaluate the complete framework under a shared candidate-evaluation budget. The results 

---

### [389] Measuring the Inference Energy Efficiency of Open-Weight LLMs across Benchmarks, Reasoning Modes, and Hardware

**链接**: https://arxiv.org/abs/2610.14389
**作者**: Zeyu Yang and Wes Armour
**来源**: cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmark scores tell us what an LLM can do, but not how much energy is required to deliver that capability. We directly measure this trade-off for 86 open-weight model checkpoints, evaluated on seven benchmarks and six hardware platforms ranging from a consumer GPU to an eight-GPU server. We find large differences in energy efficiency even among models with similar capability. Most configurations lie away from the score--energy Pareto frontier: they use a median of 2.6--4.8$\times$ more energy than another configuration that scores at least as well, with differences reaching 27$\times$. Reasoning can improve capability, but enabling thinking increases energy by about 3.7$\times$ on average, and the benefit depends strongly on the model family and output budget. Generated-token count is also an imperfect proxy for energy, misordering 18--24\% of model pairs. In contrast, FP8 reduces energy by roughly a quarter with little change in score, while changing hardware largely rescales energy

---

### [390] Label-Centric Knowledge Retrieval for Zero-Shot Text Classification

**链接**: https://arxiv.org/abs/2610.16182
**作者**: Daoping Wu, Dong Wang, Siyu Liu, Chen Liang, Jian Geng, Ziqi Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Flagship large language models (LLMs) offer rich general knowledge and strong reasoning capabilities, but their high inference cost and latency limit their use for large-scale data labeling. We study zero-shot text classification with semantically meaningful labels and task descriptions, without task-specific labeled examples or classifier feedback. We propose \textbf{SLKR} (Semantic Label Knowledge Retrieval), a label-centric retrieval-augmented generation framework that separates offline knowledge construction from lightweight online inference. Offline, a flagship LLM independently generates label definitions, retrieval keywords, and boundary rules for potentially confusable label pairs, forming a reusable label-knowledge store. Because this construction operates over the label space rather than the input corpus, its one-time flagship cost can be amortized across large-scale inference. Online, hybrid semantic and lexical retrieval first identifies the top-$K$ candidate labels and the

---

### [391] Contrastive Covariance Subspaces for Activation Steering

**链接**: https://arxiv.org/abs/2610.14025
**作者**: Alexandros Xenos, Manos Plitsis, Niki Foteinopoulou, Yannis Panagakis, Ioannis Patras
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering controls large language model behavior by adding a direction to hidden activations during inference. For steering to work well, that direction must be a pure signal for the target concept: any confound entangled with it, such as an incidental topic or writing style, is injected into the residual stream alongside the concept itself and degrades the generated text. We introduce Contrastive Covariance Steering (CCS), a training-free method that eliminates this confound variation. CCS projects steering vectors to a low-dimensional subspace obtained in closed form by solving a contrastive variance objective, which retains the directions along which the target concept varies while suppressing directions shared with the other classes. Across three LLMs and four steering domains, CCS consistently beats all baseline steering methods in all $12$ model-domain settings. The largest relative improvement occurs on AxBench and Emotion where we outperform the next strongest steerin

---

### [392] Big-Big-SycoBench: A Benchmark to Detect Sycophancy Through Model Responses to Valid vs. Invalid Arguments

**链接**: https://arxiv.org/abs/2610.15634
**作者**: Marthe Ballon, Arne Vanhoyweghen, Seorin Kim, Francesca Carlon, Lynn Delcon, Melika Mobini 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sycophancy in large language models risks amplifying unsupported claims or beliefs across the knowledge ecosystem as these systems increasingly contribute to research synthesis, evaluation, and decision-making. A reliable model should revise its judgement when a user identifies a genuine flaw, but should resist pushback based on fallacies, emotion, or irrelevant appeals to authority. While sycophancy is usually measured on questions with a verifiable answer, the evaluative tasks in which it is most difficult to detect have no such ground truth. We introduce Big-Big-SycoBench, which measures sycophancy through argument discernment: the ability to revise an evaluation after valid criticism while resisting invalid pressure. The benchmark consists of 450 text artefacts with 5,400 arguments for raising or lowering their quality scores, each reviewed by one or more of twelve human annotators. An LLM scores each artefact twenty times to establish its baseline score and uncertainty. The model 

---

### [393] ChemExplain: A Multimodal Benchmark for Explanatory Chemical Reasoning

**链接**: https://arxiv.org/abs/2610.17183
**作者**: Aotian Chen, Frazier N. Baker, Reza Averly, Shan Zhang, Tianao Chen, Daniel Adu-Ampratwum 等 (8 人)
**来源**: cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current chemistry benchmarks primarily evaluate outcome prediction or reaction pathway generation, but rarely test whether a model can explain why an observed chemical effect occurs. We introduce ChemExplain, a benchmark of 1,180 multiple-choice chemistry questions drawn from 383 peer-reviewed papers. Each question pairs a molecular or reaction image with an observed chemical effect and four candidate explanations, each associated with a different structural feature visible in the image. Answering requires the model to perceive the depicted structure, apply chemical knowledge, and identify which feature most directly explains the effect, a capability we term explanatory attribution. The correct feature-mechanism relation is derived from supporting evidence in the source paper rather than invented by the question-generation LLM. We construct the benchmark automatically with a multi-agent framework that applies progressive quality control at three stages and validate it with eight chemis

---

### [394] GIFT-Eval-CTX: A Benchmark For Contextual Forecasting Model Evaluation

**链接**: https://arxiv.org/abs/2610.17794
**作者**: Xu Liu, Hanshu Yan, Taha Aksu, Quang Pham, Zhongzheng Qiao, Jun Hao Liew 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contextual forecasting seeks to improve time series forecasting by incorporating forward-looking information, such as planned events, external conditions, and expert expectations. However, reliable evaluation remains difficult: existing benchmarks often have limited domain coverage, lack standardized history-future splits, or provide text that is not guaranteed to inform the future. We introduce GIFT-Eval-CTX, a benchmark that isolates whether forecasting methods can translate verified future information into accurate numerical trajectories. Built upon GIFT-Eval, GIFT-Eval-CTX contains 10,000 instances across 20 datasets. Each instance provides structured effects derived from the realized future: Macro effects describe horizon-wide behavior, while Micro effects specify localized changes. We construct these annotations with an agentic pipeline combining LLM-based discovery and deterministic code validation. We benchmark TSFMs, frontier LLMs, and tool-using agentic systems. The results s

---

### [395] A Persian Vision-Language-Action Dataset and Benchmark for Ambiguity- and Infeasibility-Aware Instruction-to-Plan Grounding

**链接**: https://arxiv.org/abs/2610.15666
**作者**: Abdollah Pourasghari, Saeedeh Sadat Sadidpour, Mohammad Roustaei
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Converting natural-language instructions into executable action plans conditioned on a scene image is a core capability for embodied human-robot interaction, but existing benchmarks target English, simulated or video-grounded environments, and largely assume instructions are clear and executable. We introduce the first Persian vision-language-action dataset for this task: 258 instances over 230 real household/office photographs, annotated with reference plans, deliberate ambiguity and infeasibility labels, disambiguating question-answer pairs, and an auto-generated chain-of-thought rationale for training. Using this resource, we ablate retrieval-augmentation, chain-of-thought prompting, and an agentic disambiguation step, evaluated with an LLM-as-judge protocol and a new metric, PGOS-FA, extending prior work (PG2S) with step-order sensitivity, an over-generation penalty, and Persian-adapted embeddings. Paired statistical testing across 36 comparisons shows retrieval-augmentation is a l

---

### [396] Limitations on Autoregressive Token Generation via Sequential Sampling

**链接**: https://arxiv.org/abs/2610.14615
**作者**: Gal Arnon, Andrej Bogdanov, Paul Lou, Giulio Malavolta, Alon Rosen, Lorenzo Taschin
**来源**: cs.IT cs.AI cs.CR math.IT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study autoregressive token generation through the notion of sequential samplers: A circuit that samples the next symbol only given the previous ones and possibly a small amount of state. We show that (1) a sequential sampler with $k$ bits of state can be simulated by a stateless one at a roughly $O(2^{k})$ size overhead; (2) efficient insertional sampling (Stern, Chan, Kiros, Uszkoreit, ICML 2019) is more powerful than efficient sequential sampling in any fixed order; (3) sequential samplers with small state cannot establish certain forms of covert cryptographic channels. Result (1), together with the pseudoentropy vs. sequential sampleability duality of Vadhan and Zheng (STOC 2012), characterizes efficient sequential sampleability with small state. Result (3) provides a potential safety mechanism against subliminal coordination among malicious LLM agents.

---

### [397] Harmony Harness: Multi-Objective Self-Evolution of Agent Harnesses

**链接**: https://arxiv.org/abs/2610.15150
**作者**: Weichen Yu, Lesly Miculicich, Bhavana Dalvi Mishra, Jiefeng Chen, Shuo Li, Matt Fredrikson 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work on self-evolving LLM agents treats the agent harness as an optimization target that can be iteratively improved through execution feedback. Existing approaches, however, largely optimize a single objective and evolve the harness as a monolithic artifact, limiting their ability to handle competing goals and to separate transferable design from environment-specific adaptation. We introduce Harmony Harness, a framework for multi-objective, compositional harness evolution. Harmony Harness formulates harness evolution as a multi-objective optimization problem and uses decomposition-based evolutionary search to maintain solutions across different regions of the Pareto frontier, avoiding reliance on a hand-designed structural diversity metric for repository-scale harnesses. In parallel, we introduce factorized evolution operators that separately refine general-purpose harness mechanisms and benchmark-specific adaptations, together with a dynamic composition workflow that integrate

---

### [398] PEAM: On-device Communication Agent for Personalized, Efficient and Autonomous Mobile Network Configuration

**链接**: https://arxiv.org/abs/2610.14855
**作者**: Haowen Wan, Shangzhuo Xie, Syue-Ju Syue, Xianyue Wu, Runhua Li, Qianqian Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing deployment of compact large language models on smartphones is enabling autonomous on-device decision-making, such as emerging mobile GUI agents. However, many mobile decisions, such as network configuration when users switch apps or connectivity conditions change, must satisfy stringent latency constraints to preserve user experience. In this paper, we propose PEAM, an on-device LLM-based communication agent that autonomously generates personalized network-configuration rules executable within milliseconds. Specifically, PEAM first fine-tune the on-device LLM with a dataset constructed from manually annotated real-user data to integrate the communication knowledge into the local model. PEAM then operates in two phases. In the rule-generation phase, which is performed when the device is idle, such as overnight, PEAM analyzes historical network-configuration records in batches and reflects across batches to consolidate consistent evidence, reduce local bias, and derive robust

---

### [399] ANCHOR: Assessing Naturalistic Constraint Hierarchies and Ordering in Repository-Grounded Agentic Coding

**链接**: https://arxiv.org/abs/2610.16859
**作者**: Wenqiang Zhu, Xinping Lei, Zhiyi Lai, Zhengshuo Gong, Tianzhuang He, Songwei Yu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For repository-grounded coding agents, a functionally correct patch is not necessarily an acceptable one: developers also constrain how the task must be carried out-modification scope, workflow order, validation, tool use, and reporting. This capability, which we call engineering constraint following, remains largely invisible to current evaluations. We introduce ANCHOR (Assessing Naturalistic Constraint Hierarchies and Ordering in Repository-Grounded Agentic Coding), a benchmark built on naturalistic, multilingual repository tasks spanning eight language groups. ANCHOR combines (i) a hierarchical taxonomy of 10 categories and 78 leaf types distilled from real developer interactions, (ii) an automated pipeline that instantiates task-grounded atomic constraints and composes them into typed AND/THEN/PRIORITY relations, and (iii) a trajectory-grounded evaluation framework that checks both the code diff and the execution trajectory with rule-based and LLM judges. Across 19 agent configurat

---

### [400] Releasing the Inner Jev: A Simple Recipe for Open Decision Models

**链接**: https://arxiv.org/abs/2610.17205
**作者**: Jonathan Geuter and Andrew Cheng and David Alvarez-Melis
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based decision-making systems, also called System One models, have recently gained popularity, most notably through Jev (Almeida, 2026). Given a typed input state, a question, and a set of options, they return a probability for each option in a single forward pass, without text generation. We show that existing open instruction-tuned language models can achieve comparable performance \textit{without any additional training}, by reading out answers from letters (A, B, C, etc.) in the model's output logits at the last token position. Furthermore, we show how a simple supervised fine-tuning recipe can improve their performance further. We evaluate four open instruction-tuned language models: Gemma 4 31B, Gemma 4 12B, Qwen3.6-27B, and Qwen3.5-4B. We fine-tune each using LoRA and a decision head initialized from a slice of the language model head. Furthermore, we introduce OpenDecisions, a novel 2,352-question validation dataset designed to reflect the task composition of JevBench (JevB

---

### [401] Dependency Reasoning for Aspect Sentiment Quadruple Prediction

**链接**: https://arxiv.org/abs/2610.14873
**作者**: Shima Esfandyar, Seywan Soleymanbaigi, Fardin Akhlaghian Tab, Fatemeh Daneshfar, Mourad Oussalah
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Aspect Sentiment Quadruple Prediction (ASQP) is fundamentally a relational reasoning problem: identifying aspect-opinion-category-sentiment quadruples requires modeling structured dependencies, not merely sequential co-occurrence. Existing LLM-based approaches incorporate syntactic information indirectly, via retrieval-based demonstration selection or multi-stage training, rather than as unified, single-pass generation-time context. We present DRIFT, which linearizes dependency parse trees and injects them directly into LLM prompts as explicit relational context, enabling the model to reason over aspect-opinion dependencies rather than infer them from token proximity alone. DRIFT further integrates retrieval-augmented in-context learning and a syntax-aware LLM-based adjudication mechanism that complements exact-match evaluation under span-boundary variation. On SemEval Rest15, Rest16, and ACOS, DRIFT achieves the strongest performance among compared generative ASQP methods, reaching 54

---

### [402] Efficient Safety Guardrails through Latent Dual-Hypothesis Reasoning with On-Demand Trace Reconstruction

**链接**: https://arxiv.org/abs/2610.18304
**作者**: Md Asiful Islam, Fahmida Alam, Mihai Surdeanu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Guardrail approaches that rely on reasoning-based large language models (LLM) improve safety decisions, but come with substantial inference overhead due to the explicit reasoning. We introduce LR-Guard (Latent Reasoning Guardrail), an efficient and explainable guardrail that jointly learns structured latent reasoning and on-demand reasoning reconstruction. Our method distills a frozen teacher's analysis of safe and unsafe prompt interpretations and their comparison into compact latent representations. Joint training optimizes these representations for both safety prediction and reconstruction of the teacher's explicit reasoning traces, enabling human-readable explanations without requiring intermediate text generation for every decision. Experiments show that LR-Guard outperforms its explicit-reasoning teacher in most in-domain and out-of-domain settings on safety classification and explanation extraction, while achieving a 19.4x inference speedup at batch size one. Further, reconstruc

---

### [403] Large Language Models Extend Known Research But Do Not Create New Research Directions

**链接**: https://arxiv.org/abs/2610.17439
**作者**: Zhihua Liu, Kurt Butler, Damian Machlanski, Danilo Bueno, Sotirios A. Tsaftaris
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The success of autonomous research systems relies on the quality of the scientific hypotheses they generate. Recent studies report that human reviewers often rate LLM-generated ideas as more novel than those from human experts, raising hope that AI can accelerate scientific discovery. Yet it is unclear whether these models can do more than extend existing knowledge. Can LLMs drive genuine innovation by revealing new research directions, or are they limited to repeating and recombining what science already knows? This unresolved question lies at the heart of discussions about AI and the future of science. To address this, we distinguish two types of novelty: distance, which measures how far a hypothesis lies from existing work, and direction, which captures whether the hypothesis pursues new lines of inquiry beyond those already present. These two measures diverge sharply for LLM-generated work. We represent scientific papers in a shared conceptual space using a pretrained scientific-pa

---

### [404] Dream2Discern: Learning from Hard Latent Variants for Runtime Failure Prediction in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.16071
**作者**: Boxuan Zhang, jianing Zhu, Xiaotian Han, Ruixiang Tang
**来源**: cs.LG cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable deployment of LLM-based multi-agent systems calls for runtime auditors that predict terminal outcomes from observed execution prefixes. These auditors typically learn from a limited corpus of trajectories with verified outcomes. Expanding this corpus requires costly execution and verification, yet broader failure coverage alone provides no explicit criterion for identifying prefixes that the current auditor finds difficult to classify. To this end, we propose Dream2Discern, a runtime auditor trained through implicit augmentation guided by its own prediction loss. During Dream, we select perturbations of the auditor's representation operators to increase prediction loss on recorded prefixes, yielding hard latent variants. During Discern, the auditor learns to predict execution outcomes from these variants using the original labels. The variants are regenerated as the auditor learns, turning a limited corpus into a renewable source of hard examples and requiring no additional tr

---

### [405] When, Where, and Why: Hierarchical Causal Explainability for Video Face Understanding with MLLMs

**链接**: https://arxiv.org/abs/2610.17791
**作者**: Anubhav Kataria, Shreya Ghosh, Jingwen Ye, Abhinav Dhall
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding facial behaviour in video requires answering three fundamental questions: when a key facial expression occurs, where the model attends on the face at that moment, and why that evidence is necessary rather than merely correlated. Today's multimodal large language models (MLLMs) can label and describe video, but they rarely provide faithful explanations, especially for small facial movements that change over time. We present VideoFace-X-LLM, a framework for explainable facial video understanding comprising two key components. First, we introduce ExplainFace, a weakly supervised video-text corpus for facial behaviour understanding, automatically constructed from CelebV-HQ videos and validated through human evaluation and a two-model audit (at most 2.3% contradictions), demonstrating consistent gains across two backbone architectures. Second, H-TCC (Hierarchical Temporal Spatial Causal Concepts), which finds the key temporal moments (When), the facial regions (Where), and ver

---

### [406] HelpMeOut: A Neuropsychology-Grounded Benchmark for Error-Aware Monitoring of Household Task Execution

**链接**: https://arxiv.org/abs/2610.17694
**作者**: Haoran Wang, Jingwei Huang, Anqing Duan, Ho Seok Ahn, Bruce Macdonald
**来源**: cs.RO cs.AI cs.SC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce HelpMeOut, an embodied AI benchmark for error-aware monitoring of household task execution. Existing embodied household benchmarks typically assume that humans execute tasks correctly, but this assumption does not hold for cognitively impaired persons or older adults whose everyday activities produce structured execution errors. To address this gap, HelpMeOut operationalizes research on everyday action errors into 20000 paired activity episodes, covering nine neuropsychologically motivated error categories. In each episode, agents observe a streaming human activity trajectory and must monitor whether the execution is unfolding correctly, diagnosing any structured errors as early as possible. We evaluate learned-monitor, symbolic, change-point, and frontier LLM prompting baselines. Results show that these methods perform poorly as error monitors, often missing when execution goes wrong. These results suggest a gap left by standard goal-inference and task-completion benchmar

---

### [407] How Reliable Are Large Language Models for Soil Organic Carbon Assessment? An Australian Benchmark

**链接**: https://arxiv.org/abs/2610.18201
**作者**: Yingxuan Cheng, Tong Li, Yayong Li, Yuchuan Fan, You-Gan Wang, Jinran Wu 等 (8 人)
**来源**: cs.PF cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Soil organic carbon (SOC) is an indicator of agricultural soil condition and carbon storage, but numerical outputs from large language models (LLMs) require validation before use in monitoring or management. We evaluated seven general-purpose LLM configurations on three direct-response tasks: estimating 0--10 cm SOC concentrations for 308 Australian paddocks under two information conditions, calculating SOC stock in 120 matched scenarios, and comparing 300 paddock pairs. References were measured SOC records or deterministic calculations; response validity, repeated-call dispersion and estimated API cost were assessed separately. Additional measured soil attributes reduced concentration mean absolute error by 13--62\% across configurations, although high-SOC underprediction and paddock-specific errors persisted. Six configurations were highly accurate in stock calculations using equation-native units without coarse fragments, but accuracy declined with physically equivalent alternative 

---

### [408] Narrative Lookahead in LLMs: Event-Level Decodability, Predictive Advantage, and Steering

**链接**: https://arxiv.org/abs/2610.18121
**作者**: Donghoon Jung, Min Kim, Seojin Choi, Songeun Chae, Seohyon Jung
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Do language models carry information about narrative events before writing them, and how far ahead? We examine narrative lookahead through salient, state-changing events rather than tokens or response-level attributes. We extract 23,355 LLM-annotated events from 2,000 stories generated by four open-weight LLMs, labeling them along three nonexclusive dimensions of change: within agents, between agents, and in the story world, with human validation on a subset. Event segmentation and plot-independent labels enable comparisons across stories at horizons measured in events rather than in tokens. At event ends, we probe hidden states for upcoming event types and compare predictions with text-only predictors using matched prefixes. Across four models, future event types are decodable above prevalence baselines for at least four subsequent events, but probes significantly outperform both primary text-only predictors only for the next event. In exploratory steering with OLMo-3.1-32B, a probe-d

---

### [409] RoboHarness: A Simple Harness Outperforms VLA and World Actions Models

**链接**: https://arxiv.org/abs/2610.14018
**作者**: Bince Qu, Wei Chen, Bo Zhang
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rise of large language models (LLMs) has opened a path toward generalist embodied AI, raising the question of how LLMs can act in the physical world. One straightforward approach is training the model to generate actions: collect robot-action data and video demonstration, refine LLM architecture with an action head, and train a vision-language-action (VLA) model at scale. However, we argue that coding agents have the potential to realize generalist embodied manipulation. All they need is a simple yet effective robot harness. We present RoboHarness: a robotic harness that gives LLM agents a visual-geometric control panel so that they can directly understand and invoke embodied tasks. With RoboHarness, Qwen3.8-Flash-Next outperforms state-of-the-art VLA models on BEHAVIOR Challenge 2025 tasks. The implementation will be released as open source.

---

### [410] Frustratingly Easy Agentic RAG via Portable Skills: A Case Study in Customer Support

**链接**: https://arxiv.org/abs/2610.14428
**作者**: Istok Bako, Bonan Min, Tiffany Shao, Claire Cheng, Yashar Mehdad
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise workflow automation typically requires retrieving a complete and accurate set of relevant information from large operational document corpora (SOPs, policy documents) given a specific scenario or request. In customer support (CS), for example, human specialists must determine the correct sequence of resolution steps for each case, a task that demands precise grounding in policy documentation. Meeting this bar in production typically requires complex document chunking, indexing, and retrieval pipelines, often layered with learned re-rankers, query rewriters, and bespoke agentic RAG infrastructure. We report a deployment case study of a simpler alternative: a portable skill consisting of a natural-language instruction, lightweight tools (a retrieval API, format-checking scripts), and a corpus enriched with an LLM-generated navigation layer, which is a structured "Wikipedia-style" index over the underlying documents. This agentic RAG approach is straightforward to implement (1-

---

### [411] Agentic4PDM: Host-Governed Evidence Admissibility for Industrial Fault Diagnosis

**链接**: https://arxiv.org/abs/2610.17786
**作者**: Nam V. Nguyen, Hoang Van Truong, Hieu D. D., Duy Khuong Nguyen, Quang Pham, Tung Kieu
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study industrial fault diagnosis as a classification task that assigns sensor time-series windows to predefined health states or fault types. Scarce labels and changing operating conditions make repeated training of specialized classifiers costly. Yet structures such as periodicity, trends, and transients can remain diagnostically informative and be examined through reusable analytical tools. LLM agents can select and interpret these tools, but fixed rules or training-derived guidance may not resolve each signal's ambiguity, while unconstrained interpretation may overstate weak or conflicting results. We introduce Agentic4PDM, a framework that separates adaptive investigation from control over evidence use. LLM agents compare each signal with labeled references from every candidate class, identify unresolved distinctions, and propose follow-up measurements. A deterministic software controller, called the host, enforces contract-checked gated adjudication (CCGA): it checks requests, 

---

### [412] GesBench: When and Where Do Multimodal Language Models Perceive Social Meaning?

**链接**: https://arxiv.org/abs/2610.15129
**作者**: Zonghuan Li, Hayley Hung, Chirag Raman
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human social perception is incremental: we infer intent before an utterance is complete, revise our interpretation as new cues arrive, and attend to specific facial, gestural, or prosodic signals that shape social meaning. Current multimodal LLM benchmarks largely evaluate final-answer understanding over complete episodes, rewarding post-hoc recognition of social meaning rather than the unfolding perception required for real-time interaction. Drawing on interactionally embedded Gestalt principles of multimodal human communication, we introduce GesBench: a human-grounded benchmark for cue-level social perception in multimodal LLMs. GesBench uses cumulative sub-utterance clips to measure when models form stable interpretations of speaker intention and social affordance, and human gaze-guided corruption to evaluate whether regions attended by humans are functionally important for model judgments. Built from more than 6000 utterance-level clips from scripted and unscripted conversational d

---

### [413] SimInter: Evidence-Grounded User Simulation with Interview-Based Profile Enrichment for Conversational Recommender Systems

**链接**: https://arxiv.org/abs/2610.18308
**作者**: Erfan Shahabi, Amirhossein Roshandel, Mohammad Sadegh Sadeghi, Azadeh Shakery
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational Recommender Systems (CRSs) require reliable user simulators for cost-effective evaluation. LLM-based simulators have made realistic simulation possible but typically condition on profiles derived from explicit ratings, demographics, and static sources capturing surface preferences while omitting implicit behavioral characteristics such as decision-making style, aspect-level preferences, and domain expertise. We propose SimInter, a pipeline that elicits these attributes via synthetic interviews between two LLM agents, grounded in the user's statistical profile and historical conversational evidence. Before profile enrichment, an audit agent explicitly flags potential fabrication and stereotyping at the turn level. We instantiate and evaluate SimInter on movie recommendation. We simulate 300 ReDial users and, on a matched subset of 100 users, compare SimInter with a statistics-only baseline: SimInter significantly increases the diversity of expressed preference aspects (fi

---

### [414] Open-MMUnlearning: Unifying Methods and Evaluation for MLLM Unlearning

**链接**: https://arxiv.org/abs/2610.10358
**作者**: Junkai Chen, Yuhao He, Qianshan Wei, Junxiang You, Jingwen Shao, Junkai Lin 等 (10 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [415] Decoupling Knowledge Forgetting and Refusal Learning in MLLM Unlearning

**链接**: https://arxiv.org/abs/2610.14605
**作者**: Haodong Chen, Shengtao Wen, Dong Liang, Lingbing Guo, Xiang Chen
**来源**: cs.AI cs.CL cs.IR cs.LG
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current evaluations of multimodal unlearning typically focus on whether a model stops outputting target information. This surface-level criterion, however, masks two critical failure modes. First, knowledge suppression techniques often induce confabulation, leading the model to hallucinate facts about the unlearned subject. Second, refusal training merely alters observable behavior without erasing the underlying knowledge; such models might decline open queries but still identify correct answers under multiple-choice probing. To overcome these limitations, we propose Forget-Aware Self-Distillation (FASD). This method is designed to achieve honest ignorance, a state where the model genuinely loses the target knowledge and learns to acknowledge its absence. FASD separates these goals into two complementary channels. The behavior channel distills appropriate refusals from an ignorance-prompted copy of the model itself. Crucially, target tokens are masked from the teacher distribution to a

---

### [416] What Really Works for Universal Multimodal Embeddings? A Controlled Study of Contrastive Training Strategies

**链接**: https://arxiv.org/abs/2610.15035
**作者**: Duo Li, Haojun Pan, Zuhao Yang, Xintong Wang, Chengfu Huo, Shijian Lu 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contrastive learning has become the standard paradigm for multimodal representation learning, aligning semantically matched pairs while separating mismatched ones in a shared embedding space. Although various contrastive training strategies have been proposed across negative selection, batch construction, and gradient modulation, their actual effectiveness under controlled, reproducible conditions remains poorly understood. This motivates a fundamental question: Do sophisticated contrastive strategies consistently bring meaningful downstream gains in multimodal embedding learning? To address this, we systematically evaluate representative strategies under a unified benchmarking framework on MMEB. Surprisingly, direct evaluations reveal that most existing strategies offer marginal gains over a standard aligned baseline, with several even degrading overall performance. To uncover the underlying failure modes, we introduce an MLLM-as-a-Judge diagnostic framework that dissects top-1 retrie

---

### [417] HumanPhys: A Human-Centric Physical-World Perception Benchmark for Real-World Visual Reasoning

**链接**: https://arxiv.org/abs/2610.14679
**作者**: Yiming Zhang, Enzhi Zhou, Junan Lin, Dulan Zhou, Weiqiang Wang, Yuge Huang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce HumanPhys, a human-centric benchmark for real-world physical perception, and a training corpus emitted by the same pipeline. Each question targets a physically grounded quantity related to people, including depth, inter-person distance, gaze angle, displacement, velocity, heading-step trajectory, blink count, and contact-deformation strength. The rendered probes additionally test illumination inference from body and face cues and camera ego-motion, both with and without a person in the frame. All labels are derived programmatically from sensor calibration, source metadata, or renderer state, rather than written by annotators or produced by estimators on the benchmark frames. HumanPhys systematically probes six dimensions of human-centric physical perception: spatial state, kinematics, blink events, deformation, illumination, and camera pose. To the best of our knowledge, no existing MLLM benchmark-and-training corpus jointly supervises this set of human-centered physical q

---

### [418] PACT: A Pragmatic Prompting Framework for Expressive and Voice-Preserving Speech-to-Speech Translation

**链接**: https://arxiv.org/abs/2610.18247
**作者**: Yuchen Song and Satoshi Nakamura
**来源**: cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech-to-speech translation should preserve not only what is said, but also who says it and how it is said. Existing end-to-end S2ST, speech MLLM, and cascade systems can preserve content or timbre, but often struggle to realize emotion, tone, rhythm, pauses, and pragmatic attitude in the target language. We propose PACT, a target-space pragmatic prompting framework for expressive and voice-preserving S2ST. PACT extracts source pragmatic cues, projects them into the target-language expression space, calibrates the projected representation to a realizable target subspace, and converts it into continuous prompts for a frozen speech generator. On bidirectional Spanish-English TOPI evaluation, PACT achieves the best overall performance among evaluated systems across content fidelity, voice preservation, and expression preservation metrics.

---

### [419] Scenes as an Attack Surface: Uncovering Scene-Grounded Safety Failures in MLLMs

**链接**: https://arxiv.org/abs/2610.14094
**作者**: Tongxi Wu, Yuyang Cheng, Jiacheng Xian, Hu Huang, Zhihao Wu, Menglin Yang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing jailbreak attacks have exposed serious safety weaknesses in multimodal large language models (MLLMs). Most prior attacks rely on specially constructed visual inputs to carry or support harmful intent. In this paper, we uncover a different vulnerability: task-relevant scene semantics alone can shift an MLLM from refusal to compliance, even when the visual input introduces no additional attack instructions and the original task intent remains unchanged. We formalize this failure as a scene-grounded visual safety vulnerability and introduce SceneSafetyBench to investigate it across eight risk categories and nine white- and black-box MLLMs. Our analysis reveals that this failure is associated with how task-relevant visual evidence influences downstream safety representations, suggesting that visual grounding alone cannot fully explain the observed safety shift. Building on this finding, we propose Scene-Grounded Attacks (SGA), which preserve the original task while constructing va

---

### [420] SurgiCLAW: An Interpretable Atomic-Skill Agent for Precision Robotic Micromanipulation

**链接**: https://arxiv.org/abs/2610.15766
**作者**: Angen Ye, junjie xie, Yujia Song, Junkai Huang, Dapeng Zhang
**来源**: cs.RO cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent multimodal large language models (MLLMs) and vision--language--action models have provided robots with new capabilities for long-horizon task understanding and planning. In surgical robotics, however, end-to-end prediction of low-level actions remains limited by insufficient precision, opaque decisions, and scarce data. This paper presents SurgiCLAW, a hierarchical skill-based framework for precision surgical manipulation. SurgiCLAW confines an MLLM to intraoperative visual understanding, structured explanation, and atomic surgical-skill selection, while delegating physical execution to verifiable deterministic control programs. For brain--machine-interface implantation, a representative high-precision surgical task, we construct a state-to-skill invocation dataset and expand it through visual and state perturbations. The model first learns structured skill invocation through supervised fine-tuning and is then optimized using three rewards for action correctness, operation prere

---

### [421] Bifocal: Training-Free Mixed Granularity Visual Token Pruning for Multimodal LLMs

**链接**: https://arxiv.org/abs/2610.18399
**作者**: Peiran Yin, Hao Wu, Zihao Yang, Fengyu Zhou, Yijuan Liang, Haozhe Hu 等 (9 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual token pruning for multimodal large language models (MLLMs) appears highly effective, with existing methods retaining over 95% of unpruned performance on common VQA benchmarks using a quarter of the visual tokens or fewer. However, our extensive evaluation of ten methods across three MLLM families and five ability groups reveals a critical gap: strong general performance often comes at the cost of severe degradation on fine-grained tasks such as OCR and visual grounding. We trace these failures to two limitations of the prevailing paradigm of retaining the highest-ranked native patches. A single importance ranking overlooks the complementary evidence required by different tasks, while sparse patch selection disrupts both image content and spatial integrity. To address these limitations, we propose Bifocal, a training-free, two-stage pruning method built on a mixed-granularity framework. It allocates separate budgets to query-focused and image-intrinsic evidence, complemented by a

---

### [422] PLAYGROUND: Progressive Layout Generation with Render-Grounded Planning

**链接**: https://arxiv.org/abs/2610.18865
**作者**: Jaeho Lee, Junhwan Heo, Junghyun Park, WonJun Moon, Eunju Yang, Seungho Jang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating editable graphic designs requires arranging visual and textual elements into a coherent composition while preserving their content and editability. Although recent MLLM-based approaches employ iterative generation and visual refinement to reflect the real-world design workflows, their high-level plans are predetermined prior to execution, limiting their adaptability as the design evolves. To address this limitation, we propose PlayGround, a progressive layout generation framework that dynamically adapts to the current rendered canvas. PlayGround establishes a progressive design loop comprising a Progressive Planner, a Layout Generator, and a Visual Verifier, guided by a Structure-Aware Retriever. Given an initial set of unordered elements, the Structure-Aware Retriever initially infers a coarse layout structure to retrieve structurally similar reference designs. Subsequently, at each turn, the Progressive Planner examines the current rendered canvas alongside the remaining e

---

### [423] Towards Autopilot Labeling for Short Video Content Governance

**链接**: https://arxiv.org/abs/2610.15687
**作者**: Junwen Chen, Hongwei Wang, Zixuan Wang, Jingbing Wang, Gorden Liu, Sheng Siong Ong 等 (10 人)
**来源**: cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The explosive growth of short videos has presented significant challenges to content governance. Traditional manual labeling is inefficient, slow to iterate, and costly. Therefore, we explore and develop a multi-stage autopilot labeling framework aimed at progressively increasing the level of automation in short video content annotation. To move beyond the heavy reliance on human expert labeling at the initial L0 stage, we first introduce a discriminative MLLM labeler at the L1 stage, which is fine-tuned with supervised data to directly predict labels for short videos. Advancing to the L2 stage, we shift to a domain-adaptive MLLM pretrained on short video data and use it for zero-shot labeling, enabling flexible generalization without task-specific supervision. In the L3 stage, we propose an agentic annotation workflow, and equip the agent with several key tools, which empower the agent to handle complex, unfamiliar, or vaguely defined cases, significantly reducing the need for human i

---

### [424] EmoGenie: Benchmarking and Evaluating Expressed and Evoked Emotion in T2I Generation with MLLMs

**链接**: https://arxiv.org/abs/2610.18455
**作者**: Zixuan Xing, Lancheng Gao, Shengyan Li, Huiyu Duan, Zhaolin Cai, Guangtao Zhai 等 (7 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rapid advances in artificial intelligence-generated content (AIGC) have significantly promoted using text-to-image (T2I) models to generate images with specific affective intentions. However, the emotional effects conveyed by generated images frequently deviate from target expectations, and it remains unclear whether multimodal large language models (MLLMs) can reliably interpret the emotion of AI-generated visual content. Existing affective benchmarks are predominantly built on natural images, while affective studies of generated images have largely focused on emotions expressed in portraits, lacking a unified benchmark for studying the emotions expressed and evoked by generated images. We therefore introduce EmoGenie, a benchmark of emotion for AI-generated images that evaluates capabilities in T2I generation and MLLM understanding across expressed and evoked emotions. It comprises 6,400 images generated by eight T2I models using 800 emotion-targeted prompts, annotated with question-

---

### [425] DEFT: Disentanglement-Enhanced Fine-Tuning for EEG Foundation Models

**链接**: https://arxiv.org/abs/2610.14497
**作者**: Yuqiu Deng, Muyun Jiang, Zongpeng Zhang, Mingqing Xiao, Yansen Wang, Peiliang Gong 等 (10 人)
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG foundation models (EFMs) have improved EEG representation learning by transferring knowledge from large-scale multi-subject pretraining to downstream tasks. However, their pretrained embeddings often retain substantial subject-related variation, placing an additional burden on the downstream classifier, especially in cross-subject settings. To address this issue, we propose Disentangled EFM Fine-Tuning (DEFT), a plug-and-play adapter for EFM fine-tuning. DEFT encourages branch disentanglement of pretrained tokens into task-oriented content and subject-consistent style, then performs downstream prediction from the content branch. It instantiates this factorize-before-classify design with recursive Gaussian refinement, temporal-variance regularization, subject-aware contrastive learning, and reconstruction. Experiments across multiple EEG datasets and four EFM backbones show that DEFT improves matched fine-tuning baselines. Further ablations and analyses support the intended content/

---

### [426] Time Window Optimization for Motor Imagery Classification via Temporal Structure Embedded Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.16921
**作者**: Huan Luo, Na Lu, Xiaopeng Wang, Ziyang Shang
**来源**: cs.NE cs.LG
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online motor imagery-based brain-computer interfaces (MI-BCIs) typically decode continuous EEG using fixed-length sliding windows that may be misaligned with neural events. Existing window optimization methods often evaluate windows independently, overlooking temporal dependencies and potentially producing fragmented or physiologically implausible selections. We propose Temporal Structure Embedded Reinforcement Learning (TSE-RL), a framework that incorporates prior knowledge of MI event structure into a constrained Markov decision process for adaptive window optimization. First, TSE-RL assigns each window an explicit semantic role through Discard, Onset, Sustain, or Offset actions, extending binary retain/discard decisions to event-level alignment. Second, a finite-state machine masks invalid actions to enforce the temporal order of MI phases and promote physiologically plausible window sequences. Third, a Transformer-based history encoder captures dependencies across windows, improvin

---

### [427] Spectral Considerations on Unsupervised Time-domain EEG Representation Learning with Deep Networks

**链接**: https://arxiv.org/abs/2610.16264
**作者**: David Aquilu\'e-Llorens, Abel Puigseslloses, Angel Blanco, Claire Braboszcz, Aureli Soria-Frisch
**来源**: cs.LG
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is a non-invasive, scalable source of quantitative biomarkers for the early diagnosis of brain disorders, and deep representation learning has become a powerful paradigm for extracting information-rich latent features from raw signals. However, neural networks tend to under-represent high-frequency information, a concern that is especially acute for EEG given its oscillatory nature and characteristic $1/f^\chi$ power decay, which risks masking disease-relevant high-frequency signatures. In this study, we systematically investigate the spectral constraints of unsupervised time-domain feature extraction across three autoencoder architectures (LSTMVAE, VAEEG, Transformer) and a state-of-the-art EEG foundation model. Using synthetic experiments and empirical validation, we show that while autoencoders capture macro-scale shifts such as alpha slowing, they remain biased against higher frequencies due to a magnitude-driven masking effect induced by the Mean Squar

---

### [428] Siam-ALS: An Explainable Siamese Deep Learning Framework for Early ALS Detection Using EEG and Eye-Tracking Signals

**链接**: https://arxiv.org/abs/2610.15351
**作者**: Abdur Rahman, A. A. M. Muzahid, Istiak Ahmed, Dipto Biswas, Hua Han, Yujin Zhang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Amyotrophic lateral sclerosis (ALS) diagnosis remains challenging due to heterogeneous symptoms and reliance on clinical assessment, underscoring the need for objective, data-driven approaches that leverage patient-generated physiological signals. We propose Siam-ALS, an explainable Siamese deep learning framework that jointly models synchronized electroencephalography (EEG) and eye-tracking (ET) signals. EEG captures ALS-related changes in brain activity, while ET provides information about oculomotor control, allowing the model to learn complementary patterns associated with ALS. The framework employs two modality-specific encoders: a convolutional EEG encoder that captures spatiotemporal neural patterns and an MLP-based ET encoder that models oculomotor dynamics. These modality-specific features are processed through weight-sharing Siamese branches and fused into a compact 64-dimensional joint embedding. A lightweight classifier is used to predict ALS, while pairwise metric learning

---

### [429] MontageFlow: Physically Valid High Fidelity EEG Generation

**链接**: https://arxiv.org/abs/2610.14507
**作者**: Sudarshan Regmi, Nabaraj Subedi, Arvind Pillai, Yu Yvonne Wu, Yuliang Chen, Michael V. Heinz 等 (9 人)
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative modeling offers a promising solution to the scarcity of labeled clinical electroencephalography (EEG) data under strict privacy constraints. Although recent generative models report substantial improvements in generation fidelity, we show that these gains conceal a categorical failure. EEG is not an arbitrary multichannel signal: each channel records the voltage difference between two scalp electrodes. So, real recordings satisfy exact linear identities among their channels. Current generators invariably violate these identities, yet this has gone unnoticed. We therefore propose MontageFlow, a flow-matching model that enforces these identities by restricting its output to signals that satisfy them. We find that ensuring validity improves fidelity too. Furthermore, to retain the EEG characteristics that oversmoothing washes out, we also condition the model on a physiological state vector encoded from the whole EEG window. For generation, this vector is drawn from a prior fitt

---

### [430] On Sleep-Wake Disorder Identification from Polysomnographic Representations

**链接**: https://arxiv.org/abs/2610.17451
**作者**: Alvise Dei Rossi, Luigi Fiorillo, Giuliana Monachino, Alessia Calzoni, Julia van der Meer, Markus H. Schmidt 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised polysomnography foundation models (PSG FMs) aim to capture clinically useful information beyond sleep staging, yet are rarely compared with sleep-staging encoders pretrained at comparable scale and modality coverage. Using a common whole-night, missingness-aware state-space downstream modeling framework, we compared frozen representations from prominent large-scale, multi-cohort sleep-stage-supervised encoders and self-supervised PSG FMs for multilabel identification of six sleep-wake and circadian disorder groups in 7,906 PSGs from an unseen registry. Although PSG FMs outperformed an EEG-only, single-cohort supervised baseline, this ordering reversed when supervised pretraining approached comparable scale and modality coverage. Transfer learning from neural sleep scorers achieved higher overall performance while exhibiting greater downstream data efficiency. These findings underscore the need for scale- and modality-matched pretrained supervised baselines when assessin

---

### [431] Cross-Subject and Cross-Montage EEG Transfer Learning via Individual Tangent Space Alignment and Spatial-Riemannian Feature Fusion

**链接**: https://arxiv.org/abs/2508.08216
**作者**: Nicole Lai-Tan and Xiao Gu and Marios G. Philiastides and Fani Deligianni
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [432] HyBRA-EEG: Hyperbolic Global-Local Brain-Region Aggregation for Self-Supervised EEG Representation Learning

**链接**: https://arxiv.org/abs/2610.16589
**作者**: Xin Liu, Feng Lu, Wei Li
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) representation learning is challenged by noisy signals, inter-subject variability, and heterogeneous electrode montages in different datasets and recording settings. Recent self-supervised EEG pretraining methods improve transferability by converting heterogeneous recordings into unified token or sequence representations, but channel-aware designs may still encode montage- or dataset-specific regularities. We propose HyBRA, a self-supervised framework based on hyperbolic global-local brain-region aggregation. HyBRA maps heterogeneous channel observations into a fixed regional token space by combining electrode coordinates, region priors, and feature-dependent hyperbolic distances. A channel-evidence injection branch preserves fine-grained discriminative cues during aggregation. The resulting tokens are processed by a Region-Time Transformer and pretrained with masked reconstruction of latent features and region-level signals. HyBRA outperforms the compared 

---

### [433] Towards Modality-Agnostic Seizure Classification: A Unified Deep Learning Framework for Heterogeneous EEG and Intracranial EEG Signals

**链接**: https://arxiv.org/abs/2610.16596
**作者**: Ramya Sundaram, Muhammad Aslam Jarwar, M Uma, Sunder Ali Khowaja, and Qurat-Ul-Ain Mastoi
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Seizure prediction and detection, essential for clinical treatment of epilepsy, remain the crucial task of this neurological disease. EEG and iEEG are widely used to analyze epilepsy due to its capability of capturing discriminative brain activities at high time resolution. However, existing works generally analyze either EEG or iEEG seizure activity separately, where EEG analysis has been well-researched, while more and more works consider iEEG for its higher specificity at the spatial level and signal quality. Currently, most of the existing seizure prediction systems are single-modal in nature, which limits its application to a variety of clinical conditions. Therefore, a common framework to analyze seizures with both EEG and iEEG signals needs to be developed. This paper presents a new framework of multimodal seizure classification integrating the heterogeneous EEG and iEEG recordings from different subjects and sources. A specific framework, called Unified Multimodal Signal Harmon

---

### [434] Brain2Face: A Study on the Relation of EEG Signals and Spatio-temporal Head Avatars

**链接**: https://arxiv.org/abs/2610.17356
**作者**: Camilo Andr\'es Mart\'inez Mart\'inez, Olaf D\"unkel, Kartik Teotia, Maurice Rekrut, Christian Theobalt, Marc Habermann
**来源**: cs.CV cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Driving digital head avatars is classically done by hand-crafted artist design or by image-based facial performance capture. In this work, we ask whether spatio-temporal tracking of the humans's head geometry and appearance can be performed solely from brain signals, i.e., Electroencephalography (EEG). Since prior work mostly focused on activity and emotion recognition, this task is relatively unexplored without even having publicly available high-quality datasets and benchmarks. Thus, we contribute a dataset featuring paired EEG and human head geometry as well as appearance annotations. We synchronize 64-channel EEG with per-frame expression latent codes of a personalized Gaussian head avatar. Second, we introduce a baseline to the task of expression recovery of a head avatar from EEG signals. To this end, we propose a dedicated EEG-to-expression model that takes a temporal sequence of EEG signals as input and regresses the latent expression parameters of the 3D Gaussian head avatar. 

---

### [435] Interpretable Multimodal EEG-ECG Framework for Neonatal Seizure Prediction and Patient-Adaptive Transfer Learning

**链接**: https://arxiv.org/abs/2511.14110
**作者**: Sithmini Ranasingha, Agasthi Haputhanthri, Hansa Marasinghe, Kithmin Wickremasinghe, Nima Wickramasinghe, Jithangi Wanigasinghe 等 (8 人)
**来源**: eess.SP cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [436] CORTIVA: Candidate-Score Fusion of Complementary Visual Teachers for EEG- and MEG-to-Image Retrieval

**链接**: https://arxiv.org/abs/2608.01355
**作者**: Junhan Wang, Kani Chen
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [437] Merit: Making every modality earn its contribution in multimodal attention decoding

**链接**: https://arxiv.org/abs/2610.17507
**作者**: Ali Alavi, Donald S. Williamson
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> More than 1.5 billion people have hearing loss. When several people talk at once, hearing aids amplify every voice alike. Auditory attention decoding (AAD) aims to solve this by reading a listener's brain signals to find the attended talker, letting the device amplify only them. A real device will not see the brain alone; smart glasses and earbuds also track eyes, head, and scene. These behavioral signals help, as people often look at who they listen to. However, they show where a listener looks, not whom they hear. A decoder relying heavily on them fails when a listener cannot move their head or listens without looking - exactly when a brain-based device is needed. A multimodal decoder must use these signals without letting them replace the electroencephalogram (EEG). Accuracy alone cannot show whether it does. We present MERIT, a decoder and evaluation method asking: how much accuracy does each input earn? MERIT shuffles each input stream across test examples, measures the accuracy d

---

### [438] Vision Models Capture Complementary Representations in Children That Converge in Adults

**链接**: https://arxiv.org/abs/2610.16860
**作者**: Domenic Bersch, Timothy Schauml\"offel, Michela Proietti, Antonia Franaszek-Traczewska, Hannah Elisabeth Zwad, Siying Xie 等 (10 人)
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How the relationship between image-text aligned and vision-only models changes across development remains unknown. We applied time-resolved representational similarity analysis to EEG data from 8-year-olds, 12-year-olds, and adults. CLIP showed significant model-brain alignment already in children, whereas vision-only models aligned more strongly later in development. Residual analyses revealed complementary structure, with CLIP retaining alignment beyond an architecture-matched vision-only model from age 8. Much of the model-brain alignment reflected semantic structure, with EEG representations of category and animacy strengthening toward adulthood, while alignment with low-level image properties remained weak across age. Together, these findings suggest that image-text aligned and vision-only models capture complementary aspects of developing visual representations and may provide useful constraints for AI systems that aim to learn and adapt over time.

---

### [439] Drive3R: Block-wise Streaming Geometric Foundation Models for Autonomous Driving

**链接**: https://arxiv.org/abs/2610.15112
**作者**: Tianyi Yang, Haojun Yang, Jipeng Xiao, Xuesong Chen, Shaoshuai Shi, Li Jiang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-fidelity closed-loop simulation for autonomous driving increasingly relies on dense multi-view 3D reconstruction. While recent feed-forward geometric foundation models have revolutionized per-scene optimization, applying them to continuous, long-horizon driving sequences is computationally intractable due to GPU memory limits and the quadratic complexity of global attention. Existing scaling strategies are fundamentally limited, as causal streaming suffers from compounding scale drift and trajectory deviation, while rigid "chunk-then-align" heuristics fragment global context and produce trajectory discontinuities. To address these limitations, we introduce Drive3R, a block-wise streaming geometric foundation model. Its block-wise causal attention resolves the scalability bottleneck of fully bidirectional attention while avoiding the loss of local future context in purely causal streaming. Its confidence-aware re-anchoring further mitigates long-range drift by detecting unreliable 

---

### [440] When Repeated Measurements Hurt Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.16801
**作者**: Yixiang Liu, Ruizhe Deng, Bibhas Chakraborty, Qiong Zhang, Yan Shuo Tan
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) achieve state-of-the-art performance on IID benchmarks, but how do they respond to repeated measurements at the same inputs? Across six TFMs, synthetic and semi-synthetic experiments show that additional measurements can improve predictions at measured inputs while degrading them elsewhere. Harm is most frequent at low noise, and irrelevant features amplify it in several models; real repeated-measurement datasets show similar patterns. Statistically, the IID rule targeted by PFN pretraining treats each repeated input as fresh evidence about the input distribution. When the prior links this distribution to the response function, the resulting protocol mismatch can outweigh the benefit of additional measurements, even under exact inference. Computationally, interventions identify row-count dependence in TabPFN-v3's attention scaling as a contributor to harm. Resetting the count largely reverses distortion in a noiseless linear diagnostic and attenuates am

---

### [441] Physics: Benchmarking Foundation Models on University-Level Physics Problem Solving

**链接**: https://arxiv.org/abs/2503.21821
**作者**: Kaiyue Feng, Yilun Zhao, Yixin Liu, Tianyu Yang, Chen Zhao, John Sous 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [442] FIRE: Multi-fidelity Regression with Distribution-conditioned In-context Learning using Tabular Foundation Models

**链接**: https://arxiv.org/abs/2601.22371
**作者**: Rosen Ting-Ying Yu, Nicholas Sung, Faez Ahmed
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [443] Foundation Models for Event Prediction Across Heterogeneous Event Logs

**链接**: https://arxiv.org/abs/2610.17503
**作者**: Fabian Spaeh, Sean Jaffe, Shandian Zhe, Bin Shen
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Event logs are ubiquitous across real-world domains, including business processes, manufacturing workflows, healthcare, and many other operational systems. Yet event logs can differ substantially in their event semantics, label spaces, interaction patterns, and temporal scales, making it difficult to build a single foundation model that generalizes directly to previously unseen systems. We address this challenge with the Foundation Event Predictor (FEP), a simple and scalable in-context architecture that performs next-event prediction through learned, event-level nonparametric inference. Causal self-attention encodes context and target histories into key and query representations, respectively, while the observed next context events are encoded as values. Cross-attention then performs learned, relevance-weighted aggregation of next-event outcomes over all context transitions, allowing the entire nonparametric prediction procedure to be expressed as standard attention operations and eff

---

### [444] Mantis: Mamba-native Tuning is Efficient for 3D Point Cloud Foundation Models

**链接**: https://arxiv.org/abs/2605.03438
**作者**: Zihao Guo, Yiding Sun, Jihua Zhu, Haozhe Cheng, Jian Liu, Ajmal Saeed Mian
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [445] Benchmarking Self-Supervised 3D Medical Vision Foundation Models and Transferability Estimation

**链接**: https://arxiv.org/abs/2610.17573
**作者**: Jiaqi Tang, Yu Wang, Yang Liu, Jing Tao, Fandong Zhang, Zhou Zhen 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised pretraining has expanded the pool of 3D medical foundation models, but published evaluations use different datasets, endpoints and fine-tuning protocols. Models also differ in architecture, pretraining objective and data, while downstream targets range from voxel-level masks to patient-level diagnoses and outcomes. As a result, published findings provide little directly comparable evidence for choosing a model for a new task. Direct comparison of adaptation performance requires fine-tuning candidates on labelled target data, at substantial computational cost. We benchmark 23 candidates across the same 14 segmentation, classification and regression tasks spanning multiple anatomies and modalities. No candidate ranked among the top three across all segmentation tasks or across all classification and regression tasks; a convolutional encoder could outperform a transformer trained with the same objective on one task but underperform it on another. We benchmark transferabili

---

### [446] The Smart Buildings Challenge: Learning Foundation Models for Real-World Optimization at Scale

**链接**: https://arxiv.org/abs/2610.18511
**作者**: Judah Goldfeder, Ayush Rai, Philippe M. Wyder, Na Li, Victoria Dean, Donna Vakalis 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Buildings cause nearly 40\% of carbon emissions in the US. Of total building emissions, HVAC systems are responsible for approximately 40-60\% and account for 15\% of global energy consumption. Despite advances in artificial intelligence, most buildings still operate as inefficiently as they did decades ago. Building optimization, perhaps more so than any other optimization problem, has enormous potential for Machine Learning (ML) driven impact on climate change, in both the short and long term. One of the biggest obstacles for building optimization is the lack of policy transfer. Most building control systems, whether simulation or learning based, don't generalize: they only work well for the building they were developed for, but not for other buildings. To solve this problem, we propose a challenge for the development of building foundation models that easily adapt to new buildings with minimal configuration and thereby enable building optimization to scale across the globe. Particip

---

### [447] Feature Selection for Tabular Foundation Models: Exploring Feature Utility in Low-Data Molecular Prediction

**链接**: https://arxiv.org/abs/2609.30789
**作者**: Yiqi Yao, Miquel Duran-Frigola
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [448] Code-Switching Detection via Language-Selective Dimensions in Speech Foundation Models

**链接**: https://arxiv.org/abs/2610.18726
**作者**: Jie Chi, Zakaria Aldeneh, Masha Fedzechkina, Maureen de Seyssel, Natalie Schluter
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code-switching (CS), the alternation between languages within an utterance, is common in multilingual speech but underrepresented in pretraining corpora. Increasing CS coverage requires finding relevant utterances in large speech collections so that they can be included in training data. One way to find such utterances is to transcribe the speech and detect language alternation in the text, but this depends on obtaining accurate multilingual transcriptions. We propose a lightweight method that detects CS directly from speech. It uses frame-level language information in pretrained speech encoders to determine whether both languages are present within an utterance. Specifically, we identify language-selective hidden-state dimensions using monolingual recordings and aggregate their frame-level activations into a CS prediction. With a small CS set used to tune a decision rule, we show that the Whisper-small encoder achieves a mean F1 of $0.798$ across 14 language pairs in CS-FLEURS, compar

---

### [449] Where is the multimodal goal post? On the Ability of Foundation Models to Recognize Highlights in Videos

**链接**: https://arxiv.org/abs/2601.16333
**作者**: Aditya K Surikuchi, Raquel Fern\'andez, Sandro Pezzelle
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [450] IND-Eval: Aligning Evaluation and Simulation for Industrial Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.16652
**作者**: Vebj{\o}rn Haugland (1), Pavel Gulin (1), David Foss (1), Peet Cremer (1), Erlend Aune (1), Simone Casolo (1) 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce IND-Eval, a public benchmark that organizes industrial time series across domains into source-specific forecasting tasks. Relative to established benchmarks such as GIFT-Eval, it emphasizes finer sampling resolutions and a greater prevalence of multivariate forecasting. Evaluating Chronos-2, TiRex-2, and TimesFM-3, we find that TimesFM-3 achieves the lowest source-balanced aggregate nMASE and nCRPS and leads seven of nine sources under each metric; source-specific exceptions reinforce the need for domain-representative evaluation for model selection. These findings also motivate improving domain alignment during pretraining, where real industrial data are often too scarce to close domain-specific gaps directly; we therefore investigate whether a domain's statistical structure can guide simulator design. In a case study on two offshore well-monitoring regimes, we improve a general simulator's coverage using an oscillator-augmented simulation pipeline. This lowers forecastin

---

### [451] BehaviorBench: Benchmarking Foundation Models for Behavioral Science Tasks

**链接**: https://arxiv.org/abs/2606.24162
**作者**: Jin Huang, Yutong Xie, Wanli Song, Xingjian Zhang, Owen Yang, Walter Yuan 等 (8 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [452] Carve VFM: Carving Specialists out of Generalists, Automatic Task-Specific Compression of Vision Foundation Models

**链接**: https://arxiv.org/abs/2610.16813
**作者**: Lotfi Abdelkrim Mecharbat, Abdelrahman Elsayed, Ibrahim Almakky, Martin Tak\'a\v{c}, Mohammad Yaqub
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models (VFMs) provide transferable visual representations, but their inference cost limits deployment in many settings. Fine-tuning specializes a VFM without shrinking it; distillation shrinks it, but through expensive teacher-guided training. Structured pruning offers a more direct route by extracting a compact subnetwork from the VFM. However, as compression gets aggressive, existing methods fail because they treat subnetwork selection and recovery as separate axes. Across layers, capacity must follow task sensitivity rather than spread uniformly. Within a layer, a removal cannot be judged by importance alone; its impact also depends on how well the lost contribution can be recovered from what remains. Selection and recovery must therefore be decided jointly. We introduce Carve VFM, which resolves this interdependence. Given a VFM, a calibration set, and a parameter budget, it (i) searches for task-specific capacity allocations across layers; (ii) guides the search 

---

### [453] Exploring the Latent Structure of AMD Severity Using Retinal Foundation Models

**链接**: https://arxiv.org/abs/2610.14138
**作者**: Niccol\`o Fineschi, Jovana Panic, Atsushi Watanabe, Hideaki Hayashi, Kazuya Nishimura, Yuki Maeno 等 (10 人)
**来源**: eess.IV cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retinal foundation models have demonstrated strong performance across a wide range of ophthalmic tasks, yet relatively little is known about how disease-related information is represented within their learned embeddings and whether this distribution influences downstream prediction performance. In this work, we use Age-related Macular Degeneration (AMD) as a case study to investigate how disease severity is represented within the embedding space of RET-CLIP, a retinal vision-language foundation model, using bilateral fundus images from the AREDS dataset, benchmarked against non-retinal encoders. We first characterize the distribution of AMD severity within the learned representation space and then evaluate how this structure influences classification performance across three clinically relevant task formulations of increasing granularity. Finally, we analyze the most influential latent dimensions combining feature attribution, statistical phenotype association, and qualitative image an

---

### [454] Beyond the Encoder: Object-Centric Representations Emerging from Segmentation Foundation Models

**链接**: https://arxiv.org/abs/2610.18543
**作者**: Michalis Pistos, Bart{\l}omiej W. Papie\.z
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are increasingly used as feature extractors for downstream tasks with limited data, typically through representations obtained from their encoders. However, foundation models trained for structured tasks such as segmentation also form object-specific representations during task execution, whose transferability remains largely unexplored. We investigate Segment Anything Model 2 (SAM2) object pointers, compact object-level representations produced through the segmentation pathway, as transferable representations for downstream tumour prediction. Through experiments on two PET/CT tumour prediction tasks, we find that object pointers learned using segmentation supervision alone already encode tumour-discriminative information, despite never being optimised for the downstream labels. We further introduce task-guided object pointers, where an auxiliary objective jointly shapes the object pointer space for the downstream prediction together with segmentation. Task-guided poi

---

### [455] Recurrent In-Context Learning for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.14998
**作者**: Tejas Vaidhya, Gaurav Sahu, Irina Rish
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models adapt to new datasets through in-context learning (ICL), and, like most transformers, they tie computational depth to the number of independently parameterized layers. We ask whether the ICL stage of such a model needs a distinct set of parameters for every layer, or only depth. We introduce Tab-Loop, which replaces the 12 untied ICL blocks of TabICLv2 with 4 tied blocks applied $k$ times and changes nothing else: the encoders, decoder, synthetic prior and training recipe are shared with an untied baseline trained for the same compute. At matched pretraining compute (18.2 EFLOP) and matched inference compute (12 block applications), Tab-Loop matches the baseline with 62\% fewer parameters (10.4M vs.\ 27.6M): held-out log loss is 0.4583 vs.\ 0.4588, mean accuracy on 200 TALENT datasets is 84.10\% vs.\ 83.92\%, and Elo on 38 TabArena datasets is 1409 vs.\ 1396. A 4-block untied control with Tab-Loop's parameter count, which sees 32\% more training tables for the

---

### [456] Scale-Invariant Training for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.07324
**作者**: Ignacy Stepka, Willa Potosnak, Kin G. Olivares, Artur Dubrawski
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [457] TabMF: Learning Dataset Representations with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.13818
**作者**: Rafiq Kamel, Nicolas Atienza, Aziz Fouch\'e, Nicola Cancedda, Josif Grabocka
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [458] Open Foundation Models in Healthcare: Challenges, Paradoxes, and Opportunities with GenAI Driven Personalized Prescription

**链接**: https://arxiv.org/abs/2502.04356
**作者**: Mahdi Alkaeed, Sofiat Abioye, Adnan Qayyum, Yosra Magdi Mekki, Ilhem Berrou, Mohamed Abdallah 等 (9 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [459] ACCRUE: Continual Off-Policy Reinforcement Learning for Robot Foundation Models

**链接**: https://arxiv.org/abs/2610.18596
**作者**: Changyeon Kim, Kimin Lee, Yashraj Narang, Yijie Guo
**来源**: cs.RO cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) post-training improves robot foundation models (RFMs) beyond their demonstrations, but real-world deployment demands more: learning new tasks efficiently while retaining previously acquired behaviors. Existing continual RL methods on top of VLAs mitigate forgetting but rely on on-policy updates with limited forward transfer, whereas off-policy methods improve single-task sample efficiency without addressing learner persistence across tasks. We propose ACCRUE, a continual off-policy RL framework that carries lightweight actor and critic networks across tasks, allowing each stage to reuse behavioral and value knowledge acquired through prior RL. The inherited critic adapts only on current-task transitions and guides current-task actor learning, while prior behavior is preserved by distilling the actor toward cached targets on a small number of retained episodes. Fixed visual features keep the inherited learner and its replay compatible with base-policy updates

---

### [460] Physics Foundation Models for Efficient Control of Fluid Flows

**链接**: https://arxiv.org/abs/2610.15173
**作者**: Mahindra Rautela, Shaifalee Saxena, Alexander Scheinker
**来源**: physics.flu-dyn cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate whether a physics foundation model (PFM) pretrained for PDE forecasting can be repurposed for closed-loop fluid-flow control. We construct a PFM-based controller by attaching lightweight Gaussian actor and critic heads to frozen pretrained representations and train the policy using proximal policy optimization (PPO). We evaluate the approach on HydroGym's two-dimensional Kolmogorov-flow environment using vorticity observations at \(64\times64\) and \(128\times128\) resolutions and Reynolds numbers \(\mathrm{Re}=100\) and \(200\). Across these settings, we compare the frozen PFM controller against a baseline MLP policy trained with the same PPO framework. The PFM controller achieves consistently higher reward while requiring smaller executed action magnitudes over training, indicating improved control performance with reduced control effort. These results provide initial evidence that representations learned through self-supervised next-frame prediction can be transferred

---

### [461] Toward System One Clinical Intelligence: Parameter-Efficient Fine-Tuning and Counterfactual Explainability of Decision Foundation Models

**链接**: https://arxiv.org/abs/2610.15029
**作者**: S. M. Mahbub Uddin Ahmed
**来源**: cs.CL cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated disease classification from patient-reported symptoms requires balancing the speed of lightweight discriminative models against the contextual understanding and latency costs of autoregressive large language models (LLMs). Decision foundation models offer an alternative by mapping representations directly to candidate classes without free-form text generation. We adapt Clef-Flash, a 9-billion-parameter decision model built on a Qwen3.5 backbone, for 24-class disease classification on the Symptom2Disease benchmark. Using 4-bit quantized low-rank adaptation (QLoRA) with differential learning rates and a stratified split of 960 training and 240 test cases, the model achieves 95.42% diagnostic accuracy and a macro F1 score of 0.9551. This improves upon the reported zero-shot baselines of 61.67% for a remote API and 65.00% for a local unadapted initialization, and outperforms the ClinicalBERT baseline (90.90%). By evaluating candidate logits in a single forward pass without autore

---

### [462] UniMetric: Universal Metric Scale Recovery for Visual Geometry Foundation Models

**链接**: https://arxiv.org/abs/2610.16945
**作者**: Lei Yang, Yuner Zhang, Ziyang Liu, Ziying Song, Kai WU, Yiyang Gao 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models, exemplified by GPT-6 Astra, raise the prospect of general-purpose embodied reasoning and planning. Using Internet videos for embodied pretraining calls for reliable physical-scale annotations. Yet visual geometry foundation models often recover scene structure and camera motion without reliable metric scale. We show that uncertain size priors of familiar objects can jointly constrain a reconstruction's shared scale. Building on this insight, we present UniMetric, a universal and training-free metric scale recovery framework for geometry foundation models, without additional sensors or task-specific metric supervision. Specifically, Metric Prior Acquisition elicits object height intervals from a vision-language model. Semantic-Geometric Alignment measures reconstructed object heights along the estimated support-surface normal in each frame and converts the priors into scale intervals. Global Scale Recovery reconciles these intervals throu

---

### [463] What DNA Foundation Models Learn Beyond Sequence Composition

**链接**: https://arxiv.org/abs/2610.15711
**作者**: Vincenzo Yuto Civale, Andrew David Bagdanov, Alberto Magi
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Do genomic foundation models (FMs) provide predictive information beyond simple sequence composition? We evaluate frozen representations from five DNA FMs against normalized k-mer frequencies across 57 genomic classification datasets and two exploratory gene-expression regression tasks. Simple k-mer features remain competitive with most models, whereas NTv3 shows a consistent advantage; the ranking is robust to globally fixed and multi-scale k-mer baselines and alternative downstream probes. To test incremental predictive utility directly, we compare global 6-mer features with their concatenation with each FM embedding under a matched Random Forest protocol. NTv3 improves 46 of 57 datasets (mean $\Delta$MCC = +0.072), while Caduceus provides smaller gains and the other models do not improve mean MCC. We separately decompose embeddings into a component linearly predictable from 6-mer frequencies and a ridge residual, finding that linear recoverability does not reliably indicate downstre

---

### [464] SuperAI: Merging Capabilities Across Heterogeneous Foundation Models

**链接**: https://arxiv.org/abs/2610.15322
**作者**: Jingtong Dou, Chuancheng Shi, Wenhua Wu, Wei Bao, Fei Shen, Zhiyong Wang and Tat-Seng Chua
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enabling the reuse and composition of knowledge and capabilities distributed across foundation models is an important step toward building scalable artificial intelligence (AI) systems. However, architectural differences and incompatible representations make it difficult to transfer and integrate these capabilities through a unified cross-model interface. To address this challenge, we propose SuperAI, a cross-architecture multi-model fusion framework that integrates complementary capabilities from multiple source models into a host model through orthogonal alignment of low-dimensional task-relevant representations. Specifically, we first extract task-relevant representations from the source models and the host model using shared anchor samples, and apply principal component analysis (PCA) to construct low-dimensional functional subspaces with the same dimensionality. Next, we use orthogonal Procrustes mappings to align the source and host coordinate systems, establishing cross-model co

---

### [465] GG-Nav: Goal-oriented Grounding Chain-of-Thought Elicits Reasoning in Navigation Foundation Models

**链接**: https://arxiv.org/abs/2610.14541
**作者**: Shaohao Zhu, Wensi Huang, Siqi Zhang, Yuqiang Yang, Meng Wei, Chenyang Wan 等 (9 人)
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emerging strong Vision-Language Models (VLMs) have advanced navigation foundation models. However, these models still have unsatisfactory performance on goal-oriented navigation settings. In this paper, we first conduct a motivating study revealing that the key issue lies in the insufficient utilization of streaming observations and imprecise target localization. To tackle these challenges, we propose GG-Nav, a simple yet effective navigation framework that learns a structured chain-of-thought (CoT) mechanism via supervised fine-tuning to explicitly localize goal-relevant instances, accumulate grounding evidence, and support more reliable decision-making. Specifically, the structured CoT is designed with two key stages: (i) Observation-to-Evidence, which reasons over all intermediate frames between adjacent decision steps to retain useful goal-related evidence; and (ii) Evidence-to-Decision, which integrates the current observation with accumulated evidence to ground the target and sup

---

### [466] Understanding Machine Taste: Aesthetic Agreement Across Foundation Models in K-pop

**链接**: https://arxiv.org/abs/2610.17731
**作者**: Kaishen Wang, Yucheng Pan, Xuehao Cui, Hanling Tian, Heng Huang
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As foundation models enter creative industries, understanding their aesthetic preferences becomes an important step toward AI-assisted creative decision making. In this work, we investigate how foundation models evaluate creative content and characterize their ``machine taste'' using K-pop songs and music videos as a testbed. We formulate aesthetic evaluation as a pairwise ranking problem and systematically examine pairwise inter-model agreement, group-level consensus, and cross-modal preference alignment. Our results reveal stronger pairwise inter-model agreement and group-level consensus in visual evaluation than in audio evaluation, while preferences across the two modalities remain weakly aligned. We further examine how visual consensus rankings relate to real-world popularity using historical YouTube viewership data, finding positive but varying correlations across artist groups. These findings provide initial insights into machine aesthetic preferences and lay the groundwork for 

---

### [467] Distill3R: A Pipeline for Democratizing 3D Foundation Models on Commodity Hardware

**链接**: https://arxiv.org/abs/2602.00865
**作者**: Brandon Leblanc, Charalambos Poullis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [468] ScoringBench: A Benchmark for Evaluating Tabular Foundation Models with Proper Scoring Rules

**链接**: https://arxiv.org/abs/2603.29928
**作者**: Jonas Landsgesell and Pascal Knoll and Tizian Wenzel
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [469] MERIT: Scaling KG Foundation Models with Relation Transformers

**链接**: https://arxiv.org/abs/2610.15638
**作者**: Cosimo Gregucci, Daniel Hernandez, Antonio Vergari, Steffen Staab
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graph (KG) foundation models (KGFMs) predict links on unseen graphs zero-shot. KGFMs have been pioneered by ULTRA which builds a relation graph from co-occurrences that match motif templates, and passes messages over it to obtain relation representations. More recent KGFMs such as MOTIF and TRIX increase the size of this relation graph, and FLOCK replaces message-passing with probabilistic random-walk ensembles. However, larger relation graphs mean more messages, and more walks mean more sequences to encode, so they improve performance at higher training and inference cost. This cost hinders their use in more complex reasoning tasks, such as complex query answering. To reverse this trend, we design MERIT, the first KGFM with a transformer relation encoder: every relation name attends to every other, and the motifs enter as a soft prior rather than as edges. Over 56 benchmarks, MERIT matches the zero-shot MRR of SoTA KGFMs while being 6x faster than TRIX and over 100x faster t

---

### [470] YUBI-Real2Sim: 3DGS Scene Verification for Reliable Policy Evaluation

**链接**: https://arxiv.org/abs/2610.17521
**作者**: Hiroki Nishizawa, Takehiko Ohkawa, Nicola Scianca, Tatsuya Matsushima, Shigeo Morishima, Kei Ota
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating VLA policies on real robots is costly, time-consuming, and difficult to reproduce, making real-to-sim simulation essential for scalable evaluation. While 3D Gaussian Splatting (3DGS) enables rapid real-to-sim scene generation, the reconstruction quality required for reliable policy evaluation remains unquantified. In particular, policies relying on wrist-mounted fisheye cameras (e.g., YUBI handheld gripper data) are heavily exposed to visual artifacts (holes, floaters) in wide-angle views, directly degrading task performance. To address this, we present YUBI-Real2Sim, a unified framework for 3DGS-based scene reconstruction and real-to-sim policy evaluation under dual fisheye wrist views. We develop an integrated pipeline combining 200-degree fisheye camera capture, 3DGS training, 3D foundation models for object modeling, and MuJoCo-based physical simulation, reproducing the observed real-world policy ordering in eight of nine scene-task comparisons. Using this framework, we 

---

### [471] When Trackers Fail: VLM-Guided Verification and Recovery for Robust Video Object Segmentation

**链接**: https://arxiv.org/abs/2610.15929
**作者**: Valay Bundele, Susmit Agrawal, Mehran Hosseinzadeh, The Nam Nguyen, Hendrik P.A. Lensch
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent trackers built on foundation models such as the Segment Anything Model (SAM) achieve strong performance by propagating object masks through memory. However, this strength is also a key source of failure: under occlusion, reappearance, or distractors, an incorrect prediction can enter the tracking loop and be propagated over time, resulting in persistent identity drift. Existing approaches seek to prevent such failures through improved memory and temporal modeling, but once a failure occurs, the tracker has no explicit mechanism to recognize or correct it. We address this gap with Dual-Agent, a failure-aware tracking framework that complements propagation with explicit verification and recovery. We address this gap with Dual-Agent, a failure-aware tracking framework that complements propagation with explicit verification and recovery. A vision-language verification agent first reasons over spatio-temporal context to determine whether the tracker is still following the target. Whe

---

### [472] Dependency, Compression, and Synergy: A Unified Information-Theoretic View of Multimodal Learning

**链接**: https://arxiv.org/abs/2609.14421
**作者**: Liangjian Wen, Linjie Li, Jiang Duan, Yong Dai, Jianzhuang Liu, Zhao Kang
**来源**: cs.IT cs.AI cs.LG math.IT
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models have intensified the need to understand how different modalities share, preserve, and complement information. Mutual Information (MI), the Information Bottleneck (IB), and Partial Information Decomposition (PID) provide complementary perspectives, yet existing studies often treat them as isolated tools. This survey presents an information-theoretic perspective connecting these principles as progressively refined views of multimodal information processing: MI characterizes inter-modal dependency, IB explains task-oriented information preservation under compression, and PID decomposes preserved information into redundancy, uniqueness, and synergy. We review 170 recent studies (2018--2026) and 12 foundational works, organizing multimodal learning around four challenges: cross-modal alignment, information-efficient fusion, interaction-type characterization, and scaling to multimodal foundation models. Rather than using application domains as 

---

### [473] COMPASS: Contextual Moment Prior Alignment for Generalizable AIGI Detection

**链接**: https://arxiv.org/abs/2610.18034
**作者**: Zhan Yang, Tiancheng Shen, Weijie Lyu, Shuo Chen, Bernard Ghanem, Yibo Yang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generalizable AI-generated image (AIGI) and deepfake detection remain challenging due to the asymmetry phenomenon, where adaptation to limited training distributions can degrade the transferable representations of Vision Foundation Models (VFMs). Recent subspace adaptation methods mitigate this issue by freezing high-magnitude principal components while adapting the residual subspace. However, such magnitude-based decomposition is data-agnostic and does not explicitly account for target-relevant semantics, potentially leading to semantic misalignment. We propose COMPASS (COntextual Moment Prior Alignment for Subspace Separation), a data-aware subspace adaptation framework that uses a small unlabeled Semantic Proxy Set to estimate target activation statistics. COMPASS incorporates activation covariance into the decomposition of pre-trained weights, preserving target-relevant representations as a stable semantic reference while the residual adapter learns forgery-related variations. The 

---

### [474] HarnessNet: Feedback-driven Hierarchical Joint Harness Evolution for Multi-agent Systems

**链接**: https://arxiv.org/abs/2610.15221
**作者**: Zhaoyuan Qiu, Sachith Seneviratne, Yu Xia, Saman Halgamuge
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents can evolve by using environment feedback to revise their harnesses, the software managing model inputs, tool use, memory, and execution, while keeping foundation models frozen. Existing studies focus on single agents, leaving joint harness evolution in multi-agent systems (MAS) underexplored. A single global optimizer faces growing context and workload as the system scales, while access restrictions may prevent sharing agent internals or system-wide feedback. We propose HarnessNet, a framework for hierarchical harness evolution in MAS. Its basic unit, Agentron, comprises an evolvable forward harness, a foundation model, and a local optimizer that can observe and modify only that harness. Agentrons form a layered graph through which environment feedback propagates backward, with upstream optimizers receiving node-specific feedback from the downstream layer. This decomposes joint harness evolution into smaller, coordinated tasks with separate contexts, reducing individual optim

---

### [475] EV-JEPA: Elastic V-JEPA for Any Device and Cross-Device Inference

**链接**: https://arxiv.org/abs/2610.14324
**作者**: Anxhelo Diko, Jieyu Lin, Stefano Ambrogio, Ziyun Li, Mahmoud Assran, Th\'eo Moutakanni 等 (8 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models like V-JEPA are increasingly deployed across a heterogeneous edge-cloud continuum spanning smart glasses, phones, robots, and servers. Yet, they are typically trained as rigid, fixed-capacity networks bound to one device, supporting neither reconfigurable compute budgets nor collaborative execution. Existing approaches address only one axis at a time: slimmable and NAS-based methods provide width elasticity but assume single-device inference, whereas split-computing methods enable cross-device collaboration only for fixed partitions and static capacities. We introduce Elastic V-JEPA (EV-JEPA), a single model trained once and deployable everywhere along the continuum. Its width is reconfigurable, and it is natively partitionable across heterogeneous devices. At its core is Transition-Aware Triplet Training (T3). At each step we pick a narrow and a wide width, and train three paths: each width alone, plus a hybrid path that runs the early layers narrow and the rest wide

---

### [476] HairFlow: Modeling 3D Hair Strands with Multi-Modal Conditioned Diffusion

**链接**: https://arxiv.org/abs/2610.17348
**作者**: Yating Wang, Kui Wu, Ran Yi, Zixuan Lu, Tongtong Wang, Zhongtian Zheng 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modeling 3D hair strands is challenging due to complex hairstyle geometry, scarce high-quality training data, and incomplete or noisy input observations. Foundation models offer broader hairstyle priors, but their outputs are not directly usable for strand-based rendering and simulation. Existing approaches require costly per-instance optimization to fit hair priors to meshes from foundation models and 2D orientations from specialized predictors trained on limited hair data, restricting efficiency and generalization. We present HairFlow, a multimodal conditioned diffusion framework for efficient and controllable hair strands modeling. HairFlow conditions strand generation on two complementary representations: a coarse mesh that constrains global shape and multi-view sketches that specify local strand flow. HairFlow combines an Orientation VAE with a conditioned diffusion transformer to generate volumetric fields that are traced into explicit strands. To overcome the lack of paired sket

---

### [477] SlotAVS: Object-Centric Audio-Visual Segmentation via Bi-Modal Slot Attention

**链接**: https://arxiv.org/abs/2610.15764
**作者**: Arnav Sharma, Anand Mishra, Renu Rameshan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-Visual Segmentation (AVS) requires predicting pixel-wise masks of sounding objects by grounding acoustic signals in visual space. In multi-source scenes, concurrent sound sources often remain entangled within shared visual representations, leading to merged masks or unstable specialization when using standard alignment-focused transformer architectures. To address this, we present SlotAVS, an object-centric framework driven by competitive bi-modal slot attention. While robust foundation models provide rich semantic priors, SlotAVS shifts the paradigm from global cross-modal fusion to explicit competitive binding. By initializing discrete object slots from temporal audio sequences and enforcing strict slot-wise competition over spatial visual tokens, our method structurally mitigates the blending of distinct acoustic entities. Further, to stabilize instance-level learning, we introduce a Hungarian matching strategy that optimally aligns slots with ground-truth objects using spatia

---

### [478] CAPTOR: a vision-language foundation model for Chest-Abdomen-Pelvis Oncologic CT

**链接**: https://arxiv.org/abs/2610.14226
**作者**: S\'el\'ena Jean-Mactoux and Sophie Loizillon and Ghina Jardali and Amandine Cromb\'e and Nathalie Lassau and Alexandre B\^one
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose : To develop and evaluate CAPTOR, a deep-learning vision-language foundation model for oncologic chest-abdomen-pelvis (CAP) CT interpretation. Materials & Methods : CAPTOR (Chest-Abdomen-Pelvis foundaTion model for Oncologic Radiology) is a contrastive vision-language model, trained using a pretraining strategy for oncologic CAP CT (in single- or multiple-series acquisitions), on a multicenter retrospective dataset from North America, Europe and Asia, predominantly from tumor lesion examinations. CAPTOR was compared with state-of-the-art CT foundation models on three downstream tasks: disease detection, survival prediction using TumorImagingBench and image retrieval. Classification and retrieval were both evaluated on held-out internal and public test sets, stratified by anatomical coverage and indication. Bootstrap resampling was used to estimate confidence intervals, and pairwise comparisons were performed using permutation tests. Results : CAPTOR was trained and tested on 25

---

### [479] The Midas Touch for Metric Depth: Interpretable Metricization for Generalizable Depth Perception

**链接**: https://arxiv.org/abs/2610.16749
**作者**: Mengtan Zhang, Yu Ma, Shiqi Jiang, Yi Feng, Wei Ye, Xieyuanli Chen 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent foundation models have drastically improved the generalization of monocular relative depth estimation, yet recovering accurate metric depth from their estimates for depth perception tasks remains challenging due to scale ambiguity and local metric-scale inconsistency. Existing approaches recover metric depth from sparse observations using either explicit global affine transformation algorithms or implicit data-driven depth completion networks. The former cannot accommodate spatially varying relative-to-metric relationships, while the latter are sensitive to the distribution of sparse observations and may not fully exploit generalizable relative depth priors. To simultaneously address these issues, this study extends our previous work MTD and proposes MTDv2, a hybrid metric depth perception framework that combines explicit depth metricization with data-driven metric depth refinement. The explicit depth metricization process performs segment-wise affine transformations to recover 

---

### [480] More Domains, No Gains? FLO: Fast-Slow Reciprocal Learning for Multi-Domain Graph Pre-training

**链接**: https://arxiv.org/abs/2610.14748
**作者**: Yupeng Tong, Lianze Shan, Jitao Zhao, Di Jin, Dongxiao He
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inspired by the great success of foundation models in the development of artificial general intelligence, Graph Foundation Models (GFMs) have recently attracted significant attention and have the potential to advance graph intelligence. Exhibiting such intelligence requires effectively learning knowledge from large-scale, multi-domain graph data during pre-training. Increasing domain diversity during pre-training is expected to yield richer and more generalizable knowledge. Most existing methods pursue this goal by designing domain alignment strategies that help a single graph model learn from multiple domains. However, we observe that existing methods struggle to benefit from increasing domain diversity. Through empirical and theoretical analysis, we reveal two key limitations. Firstly, pre-training in most GFMs is confined to a single message-passing paradigm. Since propagation flattens relations among neighboring nodes, the graph model can hardly perceive the knowledge beyond propag

---

### [481] Riemannian Graph Tokenizer for Structural Knowledge Transfer

**链接**: https://arxiv.org/abs/2610.15427
**作者**: Qimin Zhou, Haibo Liu, Yujie Wang, Li Sun, Chuan Shi
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are at the forefront of artificial intelligence. A tokenizer, converting the raw input into discrete representations that the model can understand, plays an important role to the success of foundation models. Unlike the text tokenizer that is well studied in large language models, graph tokenizer is still at its early stage, facing the challenges of tackling the non-Euclidean structures and capturing the structural semantics. How to design a graph tokenizer for structural knowledge transfer? To this end, we propose a Riemannian Graph Tokenizer (RGT) that bridges the structural knowledge and quantized representations to support cross-domain structural knowledge transfer. The connection is established by Riemannian geometry. Specifically, we first define the geometric vocabulary (trees, cycles and sequences), which captures fundamental structural patterns and reflects the intrinsic geometry of graph. Second, we construct a Riemannian quantizer with Riemannian Straight-T

---

### [482] Agency as a New Organizing Abstraction for Computer Science

**链接**: https://arxiv.org/abs/2610.17410
**作者**: Ian Foster
**来源**: cs.AI cs.DC cs.HC cs.MA
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in large-scale machine learning have enabled agentic AI systems: persistent, autonomous computational entities that pursue goals, initiate actions, and interact with open environments. These systems are often framed as applications of foundation models. We argue that this framing is incomplete: agency is also a candidate new organizing abstraction for computer science. What is new is not the concept of an agent, nor runtime policy generation per se, but its general-purpose, open-ended form, in which systems can synthesize courses of action from goals, observations, and memory, over tools and environments for which no complete task-specific model was specified in advance. Thus agency becomes a systems-level abstraction as well as an AI modeling concept. Where the process abstraction organizes computation around executing programs, agency organizes it around pursuing goals under bounded resources: a process executes a program; an agent pursues a goal. From this perspective, the 

---

### [483] Google Earth AI Geospatial Reasoning Agent: Capabilities and a Systematic Evaluation

**链接**: https://arxiv.org/abs/2610.15750
**作者**: Noam Slonim, Aviv Slobodkin, Gil Fidel, Gal Moshitch, Mimi Sun, Lily Mihalkova 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Google Earth AI is a family of geospatial AI models, together with an agent that orchestrates them. We present this agent, Google Earth AI's Geospatial Reasoning agent (GRA), a Gemini-powered research system that combines geospatial data sources, foundation models, and tools to answer questions about our planet. GRA organizes these into modular domain skills and pairs them with upfront geospatial planning to decompose complex queries into multi-stage workflows. Evaluating such systems is hard: real-world problems admit multiple valid workflows, require data discovery across large catalogs, and rely on evolving ground truth. We introduce two benchmarks and release their development splits. GeoExpertQueries poses complex analytical problems grounded in practitioner use cases and refined by geospatial experts; each is paired with a consensus golden workflow from three independent experts and scored by a human-validated, tool-agnostic autorater. GeoKTools consists of templated queries with

---

### [484] ECHO: Correcting Time Series Foundation Model Forecasts with Historical Analogues and Errors

**链接**: https://arxiv.org/abs/2610.16433
**作者**: Boya Zhang, Xilin Dai, Yilin Wang, Qiang Xu, Luyao Dong, Xing He 等 (7 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time Series Foundation Models (TSFMs) provide general-purpose forecasting capabilities, yet their forecasts can remain misaligned with the temporal characteristics of a target domain. This motivates lightweight forecast correction even when only black-box access to the TSFM is available. Our key observation is that two forms of historical information provide complementary correction signals: historical analogues reveal how similar contexts evolved, while past forecast errors reveal a TSFM's characteristic deviations in the target domain. Based on this observation, we propose ECHO, a black-box forecast correction framework that learns from both sources. ECHO uses AnalogE to assess retrieved historical analogues together with the current context and base forecast, learning transferable corrections through cross-domain pretraining. In parallel, RecentE learns target-specific residual corrections from past forecast errors and refines them as causally available feedback accumulates. ECHO dy

---

### [485] MajorTOM:Elliot Pretrain, A Multi-Sensor, Multi-Temporal Pretraining Dataset for Earth Observation

**链接**: https://arxiv.org/abs/2610.18624
**作者**: Carmen Oliver Huidobro, Mikolaj Czerkawski, Kevin Monsalvez-Pozo, Cesar Aybar, Gustau Camps-Valls, Oscar J. Pellicer-Valero
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretraining generalist Earth observation foundation models requires data that combine several sensors, varied temporal sampling and, increasingly, text, yet open datasets rarely provide all three in one consistent, easily accessible form. We introduce MajorTOM:Elliot Pretrain, a collection of 279,166 tiles of 10 km drawn from the Major-TOM grid by clustering AlphaEarth embeddings. Each tile stacks Sentinel-2 L1C, Landsat-8/9, Sentinel-1 RTC, Copernicus DEM and ESA WorldCover on a shared 1056x1056-pixel, 10 m grid, complemented by cloud masks, OpenStreetMap entities and ERA5 weather. The tiles are partitioned into three temporal regimes, Monotemporal (250,000 tiles, one acquisition), Monthly (12,500 tiles, twelve acquisitions spread over the annual cycle) and Burst (16,666 tiles, six acquisitions within 30 days), and are released as 6.3 TB of Cloud Optimized GeoTIFFs indexed by TACO v3 Parquet metadata, a standard that allows cloud streaming, efficient data access, and filtering before 

---

### [486] Sequence Composition in EHR Foundation Model Pretraining

**链接**: https://arxiv.org/abs/2610.16878
**作者**: Joshua Placidi, Inigo Stibbe, Alfred J. Balston, Marek Rei, A. Aldo Faisal
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autoregressive electronic health record (EHR) foundation models predict the next event token in patient trajectories: sequences of structured medical events. A typical pretraining strategy is to concatenate all trajectories into a global stream and sample token windows from it. This gives patients with longer sequences more training exposure and allows tokens to attend across patient boundaries. We argue that these choices create a misalignment between pretraining and downstream clinical tasks. To explore this, we investigate how the composition of pretraining sequences affects clinical prediction performance. Using the global-stream approach as a baseline, we propose alternative sequence composition methods that control how patient trajectories contribute to pretraining sequences. Across four MIMIC-IV v2.2 tasks, our best method improves macro AUROC, AUPRC, F1, and balanced accuracy, with relative gains of 9.3% in F1 and 2.7% in AUPRC under a fixed training recipe. We find that these 

---

### [487] BigCell: Generating Gigapixel Whole-Slide Images

**链接**: https://arxiv.org/abs/2610.14261
**作者**: Srikar Yellapragada, Alexandros Graikos, Zilinghan Li, Kostas Triaridis, Tarak Nath Nandi, Ji Dong K Bai 等 (10 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whole-slide images (WSIs) are gigapixel-scale digital scans of histopathology tissue and serve as the primary basis for cancer diagnosis. Existing histopathology generative models operate at the patch scale, producing fixed-size tiles of at most 1024$\times$1024 pixels which encompass only a small fraction of the WSI. In contrast, text reports for clinical diagnoses and slide-level diagnostic labels -- the supervision that exists at scale -- operate at the whole-slide level. We present BigCell, the first approach to generate coherent whole-slide histopathology images at native gigapixel resolution. BigCell trains a flow-matching transformer at 2048$\times$2048 pixels on over 120,000 publicly available WSIs spanning multiple organ types. Conditioning on embeddings from pathology foundation models and using an inference-time sliding-window pipeline, BigCell generates coherent images of up to 32,768$\times$32,768 pixels, outperforming prior tile generators on both tile-level and slide-lev

---

### [488] Queue-Aware Token Communications: Bridging AI Representation and Wireless Service

**链接**: https://arxiv.org/abs/2610.16730
**作者**: Yuquan Xiao, Qinghe Du, Chaoyang Zhang, Wenchi Cheng, Jingqing Wang, Tao Chen 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid advancement of foundation models and edge intelligence is transforming wireless networks from data-oriented communication systems into artificial intelligence (AI)-native service platforms. Token communications (TokenCom) has emerged as a promising paradigm that directly transmits task-oriented AI representations. However, existing studies typically assume that generated tokens can be transmitted immediately, overlooking the queueing dynamics arising from the mismatch between token workload generation and time-varying wireless service capability. To address this limitation, we introduce Queue-Aware TokenCom, which explicitly incorporates token queues into the AI service pipeline. We present an end-to-end architecture integrating AI representation generation, token workload management, wireless transmission, and downstream task inference. We then discuss two key design directions: budget-aware token representation optimization and queue-aware token service optimization, with t

---

### [489] TabGift: A Context-Efficient Foundation Model for Tabular Data Generation

**链接**: https://arxiv.org/abs/2610.16990
**作者**: Yu-Sheng Li, Jun-Peng Jiang, Han-Jia Ye
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular data generation aims to synthesize realistic samples from limited observations while faithfully capturing the underlying data distribution. Tabular foundation models (TFMs), pretrained on diverse tabular tasks and adapted through in-context learning, have demonstrated strong predictive capabilities, suggesting the potential of extending this paradigm to tabular data generation. However, the strong predictive performance of TFMs often relies on sufficiently large context sets, whereas tabular generation is typically needed precisely when target data are scarce. Extending the foundation-model paradigm to generation therefore requires reliable distribution inference from only a limited context. To this end, we propose TabGift, a context-efficient tabular foundation model enabling both efficient distribution modeling and effective generation from only a few context samples. TabGift maps heterogeneous tables into a shared latent space with a pretrained tabular encoder, where an in-c

---

### [490] ConDenseDrive: Knowledge-Dense, Token-Sparse Visual Encoder for End-to-End Autonomous Driving

**链接**: https://arxiv.org/abs/2610.16908
**作者**: Shengzhen Li, Yongkang Li, Hao Gao, Chenxi Wu, Yajing Sun, Lu Hou 等 (8 人)
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> End-to-end driving requires rich spatiotemporal representations to support scene understanding and trajectory planning under strict latency constraints. However, most systems initialize their visual encoders from generic image pretraining and densely process all patch tokens for each camera view and input frame, limiting both representation quality and inference efficiency. To address these challenges, we present ConDenseDrive, a knowledge-dense and token-sparse visual encoder for end-to-end autonomous driving. Our three-stage framework first makes the encoder knowledge-dense by distilling complementary visual, semantic, and geometric knowledge from three vision foundation models. It then adapts the distilled encoder to multi-frame end-to-end driving and integrates spatiotemporal context into register tokens for planning. Finally, it makes the encoder token-sparse by applying register-guided token compression, reducing redundant patch computation and yielding a 2.0$\times$ speedup whil

---

### [491] GeoReader: Learning Latent Geometry for Spatial Reasoning in Vision-Language Models

**链接**: https://arxiv.org/abs/2610.18694
**作者**: Rong Li, Shijie Li, Jiangyong Huang, Lingdong Kong, Jiaming Zhou, Dongyue Lu 等 (10 人)
**来源**: cs.CV cs.AI cs.LG cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) struggle with metric and multi-view relationships that remain implicit in RGB observations. Geometry foundation models recover this structure from RGB, but existing methods either fuse the estimated features with visual tokens and learn to use them from question answering alone, or align VLM latents with geometry features. Capturing geometry, however, does not ensure its use: zeroing the aligned latents of a released feature-alignment model leaves its accuracy unchanged. We introduce GeoReader, a framework that learns geometric representations for the VLM that reads them. First, we train lightweight Geometric Readers to produce continuous input tokens, supervising them with geometry descriptions decoded by a frozen VLM, so that the Readers express geometry in a form the target model can already read. We then freeze the Readers to preserve this interface while fine-tuning the VLM on spatial QA, with geometry injection conditioned on the question. Geometry d

---

### [492] FOCUS: A Subspecialty Foundation Model for Intraoperative Central Nervous System Pathology

**链接**: https://arxiv.org/abs/2610.16914
**作者**: Xing Liu, Yifan Guo, Hongtai Lv, Lei Lou, Yuyi Tan, Jiang Du 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Intraoperative frozen-section diagnosis of central nervous system (CNS) lesions guides surgical decisions but is challenged by artefacts, diagnostic complexity and time constraints. Most pathology foundation models have limited exposure to CNS frozen tissue. Here we present FOCUS, a subspecialty foundation model pretrained on 27,930 frozen-sections enriched for CNS tissue. FOCUS led 11 internal diagnostic and 12 biomarker-prediction tasks, with mean AUCs of 0.969 and 0.877, respectively, retaining leading performance in temporal and external cohorts. To provide more comprehensive diagnostic information, we further organized ten diagnostic tasks into a WHO-aligned diagnostic hierarchy and separately evaluated FOCUS for lymphoma detection, a critical task for intraoperative surgical decision-making. In reader assessments by six neuropathologists, FOCUS assistance enabled junior readers to approach or exceed unassisted senior readers in hierarchical diagnosis and raised junior readers' ly

---

### [493] Sparse All-Layer Connector for Domain Generalised Semantic Segmentation

**链接**: https://arxiv.org/abs/2610.15660
**作者**: Ruoyu Guo, Xin Kun Lin, Maurice Pagnucco, Yang Song
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain generalised semantic segmentation (DGSS) has recently benefited from combining multiple foundation models, such as vision-language and vision foundation models, to leverage their diverse representations for generalisation. Existing multi-model approaches share a common design choice: cross-model fusion is restricted to depth-aligned layers, implicitly assuming that mutually beneficial information resides at the same depth across models. However, foundation models pretrained under different objectives may develop distinct representation hierarchies, making the optimality of depth-aligned fusion questionable. Moreover, we observe that the foundation models exhibit different depth-wise domain sensitivity. Motivated by these observations, we propose a Sparse All-Layer Connector (SALC) that enables each layer to access information from preceding layers of another model. As the number of accessible layers grows with depth, dense aggregation may hurt generalisation. SALC therefore lear

---

### [494] Variable Input Masked Autoencoders for Wrist-Worn Accelerometry

**链接**: https://arxiv.org/abs/2610.17383
**作者**: Harish Haresamudram, Wanting Mao, Aditya Radhakrishnan, Maxwell A. Xu, James M. Rehg
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale repositories of wearable sensor data have enabled the development of foundation models for human activities and behavior. However, existing models are pretrained using fixed input durations and sampling rates, despite substantial heterogeneity in recording conditions, downstream tasks, and deployment constraints. We introduce VarMAE, a variable input masked autoencoder that learns a single representation across sampling rates and temporal contexts. During pretraining we construct two views of the same signal: a long duration high frequency view, and a short duration lower frequency view, obtained via random cropping and downsampling. We perform masked reconstruction within each view and introduce a cross-resolution masked reconstruction objective that uses visible tokens from the long view to predict masked tokens from the short view. Cropping and downsampling impose complementary information bottlenecks, encouraging the model to learn representations that remain effective 

---

### [495] ShellElastic: Scalable Elastic Pretraining with Simultaneous Maximal Updates and Hyperparameter Transfer

**链接**: https://arxiv.org/abs/2610.15124
**作者**: Can Jin, Yan Kang, Yifan Gong, Chongjian Ge, Mingze Xu, Yuanjun Xiong 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models need to support diverse inference budgets, yet training a separate model for each budget duplicates pretraining effort. Elastic models train several nested sub-networks inside one weight-shared supernet, but existing recipes face three obstacles: variable per-step workloads that hinder distributed scaling, limited hyperparameter (HP) transfer across model sizes, and no guarantee that all sub-networks are maximally updated at once. We present \Ours, an elastic transformer that organizes hidden dimensions into a dense core and successive shells, so that every hidden matrix is block lower triangular. One full-width forward pass contains every sub-network's exact hidden states as prefixes, so joint training keeps a fixed computation graph and costs about as much per step as training the widest sub-network alone. We further introduce \muE, an extension of maximal update parameterization (\mup) to \Ours and other elastic architectures. Its scaling rules provably keep all su

---
