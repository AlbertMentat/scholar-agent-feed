# 📑 论文索引 - 2026-10-21

共 338 篇论文

---

### [1] GemNav: Discrete-Token Visual Robot Navigation using a Multimodal Large Language Model

**链接**: https://arxiv.org/abs/2607.06882
**作者**: Peter Bohm, Saimunur Rahman, Abdelwahed Khamis, Sagun Man Singh Shrestha, Chris McCool, Peyman Moghadam
**来源**: cs.RO cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [2] ReTRACE: Feedback-Guided LLM Agent in a Chemistry Harness for Retrosynthesis Planning

**链接**: https://arxiv.org/abs/2610.24744
**作者**: Jinxiang Xie, Yijian Zhang, Qingyuan Yi, Jianyi Wang, Hao Dong
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computer-aided retrosynthesis has advanced through single-step prediction, tree search and route scoring, but complex targets still require judgement over the whole route, where stereochemistry, functional-group compatibility, cost and greenness interact. Here we present \textbf{\mbox{ReTRACE}} (\textbf{RE}trosynthesis with \textbf{T}ool-orchestrated \textbf{R}easoning \textbf{A}nd \textbf{C}ontext-aware \textbf{E}vidence), an agent that places a large language model (LLM) in a chemistry harness that integrates molecular tools, complementary single-step prediction engines, a purchasable starting-material library, a route memory and a multi-criterion route evaluator. Routes are judged by a new metric that combines programmatic checks with adversarial LLM review, and its verdicts are compared with a synthetic chemist's. The agent learns continually from evaluator feedback during search, diagnosing weak routes and backtracking to revise them. With Claude Opus 4.8, at least one of the top 

---

### [3] Learning Which Device to Call: Online Tool Grounding for LLM Agents in IoT

**链接**: https://arxiv.org/abs/2610.25563
**作者**: Yichen Liu, Xiaochong Jiang, Haoran Yu, Lifei Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Internet of Things (IoT) gives large language model (LLM) agents access to physical observations, but one requested capability is usually offered by several devices, and the agent's plan does not say which one to call. Existing work retrieves relevant tools and checks plan feasibility, without learning which eligible device returns a useful observation. Unlike previous works, we study online tool grounding: binding an already specified tool call to one physical endpoint under service cost and device participation constraints. We propose a framework that learns which physical device should execute each agent-issued call. It formulates selection as a contextual bandit problem and combines adaptive context partitions with hierarchical endpoint trees, so that execution feedback is reused across related requests and devices. Selection balances task success against service cost while respecting device capability, authorization, battery reserves, and availability. Gaussian reward aggregat

---

### [4] Pair-Aware Optimization: Coordinating Exploration and Refinement for Jailbreaking LLM Agents

**链接**: https://arxiv.org/abs/2610.24823
**作者**: Juanyang Xu, Zheng Wang, Xingyu Zhao, Siddartha Khastgir, Andi Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents are vulnerable to adversarial inputs that induce attacker-specified malicious behaviors, commonly referred to as jailbreaking. Existing optimization-based jailbreak attacks primarily employ first-order (FO) methods that leverage gradient information or zeroth-order (ZO) methods that rely on function-value feedback. However, their complementarity and optimization ordering remain underexplored. We systematically investigate four strategies: pure ZO, pure FO, ZO->FO, and FO->ZO, and develop a ZO-FO framework that explores adversarial prefixes through ZO optimization and refines their corresponding suffixes through FO optimization. To coordinate the two processes, we introduce Pair-aware optimization, which retains multiple prefix candidates, conditionally refines their suffixes and selects among the resulting prefix-suffix pairs. We further investigate agent jailbreaking from a more general stochastic-generation perspective, where the same adversarial inp

---

### [5] TideKV: Delayed KV eviction via layer-wise chunked prefill for memory-efficient long-context LLM inference

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1383762126003541&hl=zh-CN&sa=X&d=7342233920478136102&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVG4SQN_Nmubhqgg4HNMaPjb&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=7&folt=kw-top
**作者**: Y Wang, Z Wang, N Hu, Y Guo, X Ma, B Guo 等 (8 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Long-context large language model ( LLM ) inference is important for modern intelligent applications but remains constrained by peak memory during prompt prefill. Existing KV cache compression reduces decoding memory but typically

---

### [6] System X: An LLM Decision Model That Replies from Its Own KV Cache

**链接**: https://arxiv.org/abs/2610.25456
**作者**: Syed Usama Khalid Bukhari, Syed Safwan Khalid, Muhammad Aamir
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision models return probabilities over supplied options, but a deployed agent may also need to reply in words. The present study introduces System X, a large language model (LLM) decision model that adds a text-reply option to the LLM-as-Jev readout. When this option wins, or confidence is low, the same model continues from the decision's key-value (KV) cache, avoiding a repeated prompt prefill. Qwen3-0.6B has been fine-tuned with LoRA on Reason-9k and Bitext reply rows. JevBench accuracy shows no statistically significant change (55.4% to 54.5%, p=0.87), while expected calibration error falls from 0.292 to 0.169. Held-out Bitext routing accuracy reaches 98.3%. Cache reuse saves 15-37% of latency on an Apple M4 Pro, with token-identical replies in the FP32 demonstration cases. Scoring options on copies of the prompt cache matches full-sequence scoring to within 1.4e-6 in probability. Adding dialogue, industry and complaint data (System X+) improves support-task results but lowers IF

---

### [7] Beyond Omni: A Unified MLLM for Embodied Sensory Understanding

**链接**: https://arxiv.org/abs/2610.26751
**作者**: Shiyun Xiong, Dongming Wu, Peiwen Sun, Bokang Yang, Jiaxu Wang, Xiaolou Sun 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent embodied systems increasingly build on multimodal large language models (MLLMs) for their pretrained understanding and reasoning capabilities, but their perception of the physical world remains largely limited to basic modalities such as vision and audio. However, broadening MLLMs to more diverse sensory modalities from the physical environment is challenging: their representations are often weakly connected to the MLLM and vary substantially in structure and statistics, while their interpretation still requires shared high-level understanding and reasoning. We therefore propose Unisense, a unified embodied MLLM framework that supports diverse physical sensory modalities within a shared multimodal architecture. Unisense follows a two-stage training process: (i) aligning sensory representations with language to establish a language-accessible interface; and (ii) tuning modality-specific experts within the shared LLM to provide specialized processing for different sensory modaliti

---

### [8] AgentSoV: Virtual Sensing for LLM Multi-Agent Systems via Stream of Variation

**链接**: https://arxiv.org/abs/2610.24845
**作者**: Congjing Zhang, Siyuan Xu, Yunfei Bai, Ke Ren, Xiaoning Qian, Shuai Huang
**来源**: cs.MA cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) multi-agent systems (MASs) solve complex tasks through interacting agents, yet their reliability is difficult to analyze because failures depend on both individual agents and how information and errors propagate across the system. Existing approaches largely treat this as post-hoc failure attribution, but do not provide a common model across heterogeneous MAS architectures or support broader analysis of information influence and observability. We introduce AgentSoV, a virtual-sensing framework that models MAS execution as a stochastic dynamic system through Stream of Variation (SoV). AgentSoV maps heterogeneous trajectories into diagnostic stages, constructs virtual measurements from observable outputs, and learns cross-stage variation propagation with a state-space model. Its representation is architecture-aware in stage dependencies yet architecture-agnostic in analytical language, supporting chain-structured, orchestration-based, and directed acyclic graph

---

### [9] ATEST: Adaptive Resource-Aware Test-Time Scaling for LLM Inference

**链接**: https://arxiv.org/abs/2610.25519
**作者**: Mobina Kashaniyan, Ali Jannesari
**来源**: cs.LG cs.AI cs.CL cs.DC cs.PF
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling (TTS) improves large language model (LLM) reasoning by sampling multiple answers, but fixed sampling budgets ignore both query difficulty and the changing energy cost of inference under GPU contention. We measure up to a 4.1-fold increase in energy for the same four-sample query as GPU load rises. We present ATEST, a resource-aware TTS framework that jointly considers the expected value of additional samples and their current GPU cost. ATEST-Online, its default mode, requires no offline calibration: it incrementally generates samples, estimates the stability of the plurality answer, monitors live GPU conditions, and learns step energy cost online to decide when to stop. ATEST-Calibrated instead selects a per-query budget using offline accuracy and cost models, favoring deployments with stable loads. We evaluate both modes on four reasoning and question-answering datasets using Phi-3-mini on an NVIDIA A100 under controlled varying load, and test transfer to an NVIDIA L

---

### [10] OR-License: Evaluating LLM Agents as Real-World Operations Research Practitioners

**链接**: https://arxiv.org/abs/2610.24087
**作者**: Peisong Wang, Feixue Liu, Yize Meng, Bowen Liu, Ruoyu Chen, Gaoyang Dai 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can large language model (LLM) agents deliver expert-level operations research (OR) solutions directly from original client materials, without prior expert reformulation? Existing OR benchmarks typically begin with self-contained descriptions or predefined optimization tasks, underrepresenting the translation of original business materials into professionally validated solutions. We introduce OR-License, an end-to-end benchmark of 31 instances across 10 industrial scenarios from paid OR engagements totaling USD 3.68 million. It preserves original requirements, input data, deliverable formats, and information boundaries after de-identification. To study information acquisition, we introduce ORSim, a controlled client simulator that discloses business facts without supplying OR expertise. Hidden evaluation checks feasibility and compares objective quality against original expert solutions accepted by clients before benchmark construction. Deployment-Adjusted Quality (DAQ) averages expert

---

### [11] Organizing LLM Inference for Aggregate Predictions from Behavioral Data

**链接**: https://arxiv.org/abs/2610.23934
**作者**: Varun Gupta and Vijay Kamble
**来源**: cs.LG cs.AI econ.EM
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When using a large language model (LLM) to simulate a user population, how should we combine individual behavioral histories to predict the fraction of users who take a particular action? We study this question in e-commerce, predicting observed product-level conversion rates from browsing sessions without task-specific model training. We vary two design choices, each involving a bias-variance tradeoff. Summarizing a product's sessions before inference reduces cost but can discard predictive detail, adding bias, whereas predicting outcomes for individual sessions and averaging afterward preserves that detail but requires many calls to reduce variance. Evaluating products together in one prompt can help the model infer what is typical in the setting, reducing bias, but also makes each prediction depend on which other products appear alongside it, adding noise. We evaluate both choices across five LLMs and two datasets. Our main finding is that predictions from individual sessions outper

---

### [12] Model Capacity Frontier: A Development Framework for LLM-Supported Social Simulation

**链接**: https://arxiv.org/abs/2610.24168
**作者**: Patrick Zhao, Yuxuan Li, Hirokazu Shirado
**来源**: cs.MA cs.AI cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly incorporated into agent-based models (ABMs) on the premise that richer, context-sensitive human behavior can improve empirical fidelity. However, LLM-supported ABMs introduce an open-ended design space in which subtle modeling and configuration choices, such as prompt design and environment coupling, can substantially alter outcomes. Developing LLM-supported ABMs to simulate human collective behavior therefore requires navigating configuration sensitivity while identifying the limitations of the current model architecture. In this paper, we introduce the \textit{Model Capacity Frontier} (MCF), a framework that characterizes the empirical performance attainable by a specified architecture across its admissible configurations. In multi-objective settings, this capacity is represented by an estimated Pareto frontier obtained through systematic configuration exploration. We demonstrate MCF in crowd simulation of university commencement eve

---

### [13] HumanSkill-4D: Training-Free Language Querying of Animatable Gaussian Avatars in Space and Time

**链接**: https://arxiv.org/abs/2610.24452
**作者**: unsu Kim, Naeun Kim, Dongyoon Han, Seungryul Baek
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce avatar referring segmentation, which selects regions of animatable Gaussian avatars from language queries. A query can also specify a pose or motion to select matching intervals. This lets users interact with avatars for local editing and motion inspection. However, making these selections with existing language Gaussian splatting methods poses two challenges: adjacent parts and garments are hard to separate and may be referred to indirectly (region ambiguity), while fine-grained motions can look alike in RGB (motion ambiguity). We address these challenges with HumanSkill-4D, a training-free framework that shares a multimodal large language model (MLLM) and geometric operators across avatars. For each avatar, a semantic memory links body-part and garment categories to persistent Gaussian regions and appearance descriptions. The MLLM uses category names and descriptions to select categories by appearance, relation, or function. To find matching intervals, it composes operat

---

### [14] Standing on the Shoulders of Giants: Enhancing LLM Agents for Automated Fact-Checking with Human Expert Skills

**链接**: https://arxiv.org/abs/2610.25777
**作者**: Xinwen Chen, Haorui He, Yupeng Li
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated fact-checking (AFC) systems powered by large language model (LLM) agents still face challenges in evidence retrieval and claim verification. Existing approaches improve their capabilities through computationally costly post-training or human-in-the-loop feedback that is difficult to scale. To transfer professional fact-checking expertise to LLM agents efficiently, we distill publicly available guidelines published by Agence France-Presse (AFP) Fact Check into a reusable, modular Professional Fact-Checking Skill (PFC-Skill). We then present SkillCheck, the first AFC system that gives LLM agents dynamic access to PFC-Skill to guide evidence retrieval and claim verification at inference time. Extensive experiments demonstrate that SkillCheck improves upon skill-free DEFAME baselines across multiple LLM backbones, with gains of 2.2--4.8 pp. in Accuracy and 1.5--6.3 pp. in Macro-F1 on the AVeriTeC benchmark. Notably, SkillCheck with GPT-4o-Mini exceeds DEFAME with GPT-4o by 3.4 pp

---

### [15] Fake News, Real Crashes: Information Injection Attacks on LLM Financial Trading Agents

**链接**: https://arxiv.org/abs/2610.26438
**作者**: Mengxiao Wang, Nitesh Saxena
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents now trade real capital using news as evidence, yet they cannot reliably tell fabricated headlines from real news. Because they read the same feeds under near-identical policies, a single fabricated post can push them into the same trade at the same moment. We present a systematic attack benchmark for information injection against LLM trading agents. Unlike prompt injection, which targets the model's instructions, information injection targets the evidence the agent trusts. The benchmark spans five injection vectors and seven event categories, evaluated over ~10,000 decisions on 15 U.S. stocks. Five findings emerge. (i) Prompt injection achieves 14% attack success rate (ASR), but fabricated news reaches 62% and two 30-word templates reach 100% on all 15 stocks, inverting the usual LLM-security intuition. (ii) For fact-poisoning templates, surface form matters more than content, since removing credibility cues such as a named source or a "BREAKING" tag d

---

### [16] Unbounded Losses, Unchecked Inputs: Measuring the Safeguards of LLM Options-Trading Agents

**链接**: https://arxiv.org/abs/2610.24289
**作者**: Mengxiao Wang, Nitesh Saxena
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents now place options orders at retail brokers, and developers publish open-source options agents faster than anyone has examined them. Prior security work on trading agents scored academic equities designs by whether an attacker can flip a buy-or-sell decision. We present the first measurement of the options agents that brokers and developers ship, scored by the safeguards they enforce and by the worst loss their documented order paths can reach. We screened 765 GitHub repositories, broker documentation, and the research literature and found 215 eligible repositories and 8 broker-native agent interfaces. We then scored 26 systems, including every broker interface and every open-source project with at least 20 stars, on seven robustness and eleven security safeguards with cell-level evidence. The ecosystem is new: 198 of the 215 repositories were created in 2026, and 129 (60.0%) appeared in the two weeks around one options-trading hackathon. Of the 22 syst

---

### [17] How Much Does One Wrong Answer Cost? Error Propagation in Constraint Pruning with Noisy LLM Oracles

**链接**: https://arxiv.org/abs/2610.25739
**作者**: Zhengtao Gui (University of California, Irvine), Weining Shen (University of California, Irvine)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constraint pruning saves queries to a large language model (LLM) or another noisy oracle by skipping each yes/no question implied by answers accepted earlier, for example through transitivity. Entity-resolution systems and LLM-based rankers use this idea. However, their analyses typically assume a correct oracle. We argue that pruning should be judged by its risk when the oracle errs, since an accepted wrong answer spreads to every question it implies. When each answer is wrong independently with small probability $\varepsilon$, the first-order risk is set by how many facts one wrong answer corrupts on average. We consider two kinds of constraints. For implication rules, as in taxonomies, pruning in a random order adds no first-order risk: a wrong answer that would change $k$ facts is accepted with probability $1/k$, so it costs one fact on average. Rules with $s$ premises break this balance: a wrong answer at a premise shared by $r$ rules can cost order $r^{1-1/s}$ facts. For entity r

---

### [18] Koi: Evidence-Guided, Self-Calibrating Planning for Multi-Cloud, Heterogeneous LLM Inference Fleets

**链接**: https://arxiv.org/abs/2610.24355
**作者**: Mankeerat Sidhu, Gangmuk Lim, Hetarth Chopra, Maximillian Eisenberg, Quan Hao Ng, Aryan Gosaliya 等 (10 人)
**来源**: cs.DC cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying a large language model (LLM) requires choosing the right accelerator, parallelization strategy, engine configuration, and replica count amongst ~140 other variables across clouds, regions, and markets. These decisions are intertwined, and the best cluster-wide plan continually changes as jobs contend for shared capacity on shifting workloads. We present Koi, a self-calibrating cluster planner for heterogeneous, multi-cloud fleets. Koi uses a Recursive Language Model (RLM) hierarchy to propose hypotheses and reason over deployment while deterministic components predict serving behavior, score candidates, and control placement. It represents inference behavior as a fixed causal graph linking decisions (e.g., accelerator, parallelism), runtime mediators (e.g., KV-cache pressure, communication overhead), and outcomes (e.g., latency, throughput). Each deployment strengthens or weakens scoped causal relationships, building a comprehensive playbook for inference that the planner emp

---

### [19] Productive State-Space Exploration for Multi-turn RL in LLM Agents

**链接**: https://arxiv.org/abs/2610.25957
**作者**: Mohammed Haroon Dupty, Yong Liang Goh, Song Guo, Wee Sun Lee
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement Learning (RL) for Large Language Model (LLM) agents in multi-turn, long-horizon environments remains challenging due to inefficient action selection and repetitive behavioral patterns. In particular, agents often become trapped in high-confidence yet unproductive behaviors, repeatedly executing invalid actions or entering action loops that hinder task completion. We observe that these frequently violate environment preconditions, revealing a mismatch between the agent's representation of the internal state and the dynamics of the underlying environment. In addition, repetitive high-confidence actions lead to cyclical behaviors that provide little to no progress towards the goal. We argue that addressing these challenges requires more productive task-aligned exploration to improve the agent's understanding of environment dynamics. Motivated by intrinsic curiosity-driven exploration, we propose a conditional state-space exploration framework that balances task completion wi

---

### [20] Rubrics Carry the Standard: Shapley Attribution for Checklist-Based LLM Judges

**链接**: https://arxiv.org/abs/2610.24971
**作者**: Saeid Asgari, Rui Ying, Sara Malvar, Rakshanda Agarwal, Bruce Sun, Claire Wang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Checklist rubrics applied by large language model (LLM) judges have become a standard instrument for evaluating open-ended outputs and for rewarding them during training. Two assumptions surround this practice: that leniency or strictness is a property of the judge model, and that a rubric can be improved by asking a model to review it. We test both in a controlled grading task with planted flaws and on two human-labeled datasets, SummEdits and RAGTruth. Holding the judge and the outputs fixed, rubric content moves the pass rate of correct outputs from 2% to 100%, whereas changing the judge model or the rendering of the same checks moves it by a few points. Model self-review then drifts the rubric toward the reviser's own standard: it adds requirements the task never stated and deletes checks that human labels had taught, with three reviser models and on all three datasets. To measure and control this, we show that under all-must-pass aggregation the Shapley value of each check has an 

---

### [21] Memory as Belief: Bayesian Evolution of Memory for Self-Evolving LLM Agents

**链接**: https://arxiv.org/abs/2610.25119
**作者**: Yiming Xu, Qian Yang, Zihan Chen, Yuefei Wu, Wenhan Zeng, Bin Shi 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on external memory to accumulate past experiences for continual adaptation. However, effectively reusing memory requires accurately assessing its value, as retrieved experiences may become unreliable when transferred across task contexts. Despite its importance, memory valuation remains largely underexplored, with existing methods relying on historical retrieval success rates that overlook the context dependency of memory usefulness and the varying reliability of estimates under different amounts of evidence. Inspired by the Bayesian brain hypothesis, we propose BEAM (Bayesian-style Evolutionary Agentic Memory), a framework that reformulates memory value evaluation as a parameterized cognitive inference process, where memory value is represented as a context-conditioned dynamic belief rather than a passive historical statistic. Specifically, BEAM infers memory value beliefs from current task contexts and continuously calibrates them u

---

### [22] LLM Evolution in a Simple Simulated Market

**链接**: https://arxiv.org/abs/2610.24033
**作者**: Charlie Pilgrim, Christopher Krupenye, Dora Biro, Richard P. Mann
**来源**: cs.MA cs.AI cs.CL q-bio.PE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Arguments that AI systems will evolve in harmful ways are largely made in the abstract. We provide a concrete empirical example. We simulate simple markets consisting of populations of twenty Large Language Model agents tasked with solving arithmetic problems. Agents differ only in their system prompt; those that go bankrupt are removed and replaced by mutated copies of the prompts of successful agents. Two market conditions select for opposite phenotypes: a market that rewards accuracy produces agents with high accuracy (94%) and high token use; a market that charges per token produces agents with low accuracy (10%) and low token use. In the second market, only tokens are incentivised yet we see a collapse in accuracy. Token use and accuracy are correlated traits such that selection on one also moves the other, and behaviour adapts along an unpriced dimension. A third neutral condition with no selection allows us to separate these effects from bias in the mutation operator. Adaptation

---

### [23] LLM-Based Evaluation Planning for Heterogeneous Optimization

**链接**: https://arxiv.org/abs/2610.24855
**作者**: Nian Ran, Sebastian Brulin, Markus Olhofer, Mauricio A. \'Alvarez, Richard Allmendinger
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Heterogeneous optimization problems require an optimizer to decide not only which candidate solutions to evaluate, but also which objectives and constraints should be evaluated under different costs and fidelities. Existing SOTA methods such as MFE-NSGA-III address this setting with manually designed selection metrics, but their behavior is largely determined by predefined heuristic rules and hyperparameters. In this work, we propose REP-HO, a reasoning-based evaluation planner that replaces the rule-based mixed-fidelity selection step with a large language model (LLM) planner. The LLM receives the same primitive optimization-state information as the heuristic planner, such as surrogate predictions, uncertainties, evaluation costs, and budget status. We first show that REP-HO achieves competitive performance compared to the human-designed metric-based method (MFE-NSGA-III). We then further enhance each decision with an adaptive nearest-neighbor summary, leading to better and more stabl

---

### [24] AdaExploreBench: Benchmarking LLM Agents for Proactive Exploration and Test-time Adaptation in Evolving Environments

**链接**: https://arxiv.org/abs/2610.25950
**作者**: Rui Wang, Zishen Lai, Jiayu Liu, Cheng Qian, Jeonghwan Kim, Heng Wang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents are increasingly deployed in unfamiliar and evolving environments, requiring them to proactively explore, understand, and adapt to environmental dynamics. However, existing benchmarks rarely test whether agents can proactively discover how an environment works and adapt as it evolves. To address this gap, we introduce AdaExploreBench, a benchmark for proactive exploration and test-time adaptation in evolving environments. By instantiating environmental dynamics as hidden rules, AdaExploreBench requires agents to actively acquire evidence and infer the rules. Under implicit rule drift, the latent rule changes without announcement, requiring agents to detect from degraded performance that prior knowledge is stale and re-explore. Experiments on eight leading LLMs show that proactive and adaptive exploration remain challenging: GPT-6 Sol achieves only 61.9% calibrated accuracy, while providing sufficient evidence or removing rule drift improves average per

---

### [25] Lmda: Llm-guided marginal distribution alignment for open-set active learning

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11739726/&hl=zh-CN&sa=X&d=5269545882642890994&ei=l_vWas65EZfUieoPhs6tkQ8&scisig=ACTRDVEYAIQMxwG8rPv1k0p9va-5&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=0&folt=kw-top
**作者**: J Tang, L Li, B Zhang, Q Huang - Chinese Journal of Electronics, 2026
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> iii) While MLLM -CONF leverages an MLLM for strong visual feature extraction, its ability to recognize ID data is constrained by label semantics, resulting in suboptimal ID sample selection. AL performance on … To further examine the role of LLM

---

### [26] A Measurement Perspective on Benchmarking LLM-Generated Text Detectors using Item Response Theory

**链接**: https://arxiv.org/abs/2610.24972
**作者**: Yanbin Zhao, Zhipeng Chen, Guangsheng Bao, Guandong Zhang, Yan Li
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarking large language model (LLM)-generated text detectors commonly relies on aggregate detector-level metrics such as accuracy, F1 score, and AUC. Although useful for summarizing overall performance, these metrics provide limited insight into how benchmark composition shapes detector comparisons or which texts distinguish detectors with different response profiles. We propose a measurement-based benchmarking framework for jointly characterizing benchmark heterogeneity and detector behavior using multidimensional item response theory (IRT). By treating benchmark texts as measurement items and detectors as respondents, the framework estimates text-level discrimination and difficulty-location parameters alongside multidimensional detector abilities. We apply the framework to a benchmark of 32K human-written and machine-generated texts across four domains, evaluated by 14 detectors. The estimated IRT item-parameter space reveals distinct but overlapping human-machine distributions, 

---

### [27] A Controlled LLM Workflow for Evidence-Grounded Diagnosis of Risk Score Differences

**链接**: https://arxiv.org/abs/2610.23962
**作者**: Hanqing Dou, Zijia Cao
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose a controlled Large Language Model (LLM) workflow for explaining risk score differences using similar historical transactions. The workflow combines reference retrieval and contrastive SHapley Additive exPlanations (SHAP) evidence with reference-based LLM reasoning and deterministic validation. Experiments on a test dataset show that the workflow produces more consistent, evidence-grounded and traceable diagnoses than the same LLM without structured workflow guidance.

---

### [28] When Code Becomes an LLM Call: An Empirical Study of Call-Site Contracts in Agentic Systems

**链接**: https://arxiv.org/abs/2610.24545
**作者**: Shihao Weng, Longtian Wang, Yang Feng, Mingfei Cheng, Jia Liu, Chao Shen 等 (9 人)
**来源**: cs.SE cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Software quality has long rested on specifications that state what code must do, and on testing and verification that check that the code does it. Agentic systems change this foundation: they replace parts of their logic, such as choosing the next tool, judging whether an action is allowed, or writing code to run, with calls to a large language model (LLM). The program still relies on what this logic must guarantee, but the model's behavior is not fixed by code, varies across runs, and can be steered by its input. The guarantee must therefore come from the program around each LLM call site, as a contract of pre-conditions, prompt constraints, and post-conditions. We present an empirical study of these contracts in 496 LLM call sites of 40 popular open-source agentic systems (13.4 MLOC, four languages). Using a multi-agent pipeline validated by 17,428 human judgments, we trace where every model output flows, derive an expected contract for each call site without access to its code, and 

---

### [29] Rethinking LLM Fine-Tuning via Weight Space Reparameterization: Preserving Safety during Downstream Adaptation

**链接**: https://arxiv.org/abs/2610.26443
**作者**: Minseong Kim, Jongbok Won, Jeesup Park, Yonghee Choi, Dongjun Han
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-tuning large language models (LLMs) on downstream tasks often weakens their previously aligned safety behavior, creating an inherent trade-off between task adaptation and safety preservation. Existing approaches attempt to mitigate this issue by identifying safety-relevant neurons, layers, or update directions in the original parameter space. However, safety-related information is often distributed across many directions in this space, causing downstream updates to overwrite parameters that encode safety behavior. We propose WSR-Tune, a Weight Space Reparameterization-based fine-tuning framework that preserves safety during downstream adaptation. Our approach constructs a safety-conditioned basis and reparameterizes the weight matrices such that safety-relevant information becomes concentrated in a small subset of directions. We then identify safety-critical directions and freeze them in the reparameterized space, while updating the remaining complementary directions for downstrea

---

### [30] Training with ML-labeled Data via Stochastic First- and Zeroth-Order Optimization

**链接**: https://arxiv.org/abs/2610.26790
**作者**: Maria-Eleni Sfyraki, Jun-Kun Wang
**来源**: cs.LG math.OC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training a machine learning (ML) model is an optimization process that typically requires a set of examples with ground-truth labels beforehand. Obtaining these ground truths usually requires laborious human effort and can be costly. The scalability of human labeling becomes a concern when there are a large number of data points that need to be labeled. To address this practical issue, we consider an optimization setting where a subset of samples has ground-truth labels, while the remaining data points were labeled by an ML predictor, which could potentially assign incorrect labels to those points. We propose both first-order and zeroth-order stochastic optimization methods for training on datasets consisting of a mix of true-labeled and ML-labeled samples. We further conduct comprehensive empirical studies from training a linear regression model to fine-tuning a large language model (LLM) to showcase the effectiveness of the proposed algorithms for training with ML-labeled data.

---

### [31] ELSA: Efficient LLM-Centric Split Aggregation for Privacy-Aware Hierarchical Federated Learning over the Network Edge

**链接**: https://arxiv.org/abs/2601.13824
**作者**: Xiaohong Yang, Tong Xie, Minghui Liwang, Chikai Shang, Yang Lu, Zhenzhen Jiao 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Optimizing Prompt Sequences using Monte Carlo Tree Search for LLM-Based Optimization

**链接**: https://arxiv.org/abs/2508.05995
**作者**: Fei Xu Yu, Gina Adam, Nathaniel D. Bastian, Tian Lan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Reward and Behavioral Measures of LLM Coordination in Dining Philosophers

**链接**: https://arxiv.org/abs/2606.07845
**作者**: Najmul Hasan and Prashanth BusiReddyGari
**来源**: cs.MA cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] LLM as a Tool, Not an Agent: Code-Mined Tree Transformations for Neural Architecture Search

**链接**: https://arxiv.org/abs/2604.16555
**作者**: Masakazu Yoshimura, Zitang Sun, Yuiko Sakuma, Junji Otsuka, Atsushi Irie, Takeshi Ohashi
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Context Selection as a Partial Order: A Blackwell Framework and Verified LLM Evidence

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2504-4990/8/10/336/pdf&hl=zh-CN&sa=X&d=9197641703392235759&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVGCL5l6LXTMyUfWoET8BCT7&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=3&folt=kw-top
**作者**: A Bilous, V Lytvyn, P Pukach, Z Rybchak - Machine Learning and Knowledge …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Context selection for large language models (LLMs) requires distinguishing source informativeness from the performance a fixed model can realize. We develop a framework separating the Blackwell order under optimal decision rules from a model-specific

---

### [36] Ask Less, Ask Better: Allocating User Attention in Proactive LLM Agents with Interruption Budgets

**链接**: https://arxiv.org/abs/2610.24411
**作者**: Xuanming Zhang, Amir H. Rezaeian, Miguel Ballesteros, Weiyi Sun, Werner Geyer, Lydia B. Chilton 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can ask clarifying questions to complete tasks, but answering each question demands users' time and effort. Existing evaluations typically measure this burden by counting questions, treating necessary and avoidable questions equally. We propose an evaluation protocol that distinguishes how often agents ask from how well they ask. An interruption budget limits the number of questions, while a user-attention cost charges extra for questions that are hard to read or not worth asking, as rated by a human-validated LLM judge. Beyond question counts, this cost captures perceived effort: on conversation pairs with the same number of questions, human annotators agreed with the cost on which conversation required more effort 75% of the time. Across eight LLMs and four customer-service domains, limiting agents to one to three questions reduces user-attention cost by 36-73% while keeping 86-94% of the task reward they earn with unlimited questions. At the same budget, reviewing each qu

---

### [37] WIDE: Boosting Adaptive LLM Inference via Token-level Dynamic Width Pruning

**链接**: https://arxiv.org/abs/2607.28418
**作者**: Haozhe Hu, Hao Wu, Peiran Yin, Chao Han, Yunpu Ma, Xiaoyu Shen
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] Blackbox Performance Analysis of LLM-based Network Control

**链接**: https://arxiv.org/abs/2610.24348
**作者**: Mahdi Alizadeh, Pooria Namyar, Arvin Ghavidel, Ramesh Govindan
**来源**: cs.NI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are becoming an indispensable part of network control systems due to their impressive reasoning. Before such LLM-enabled systems can be deployed, it is imperative to develop tools that can audit their performance on previously unseen inputs. However, auditing these systems is challenging due to the inherent opacity of LLMs. LENS is the first step towards black-box performance analysis of LLM-enabled network control systems. It uses novel methods to extend deep reinforcement learning to guide the search for performance gaps and inputs that make LLMs struggle. LENS finds large gaps for LLM-based traffic engineering and GPU allocation systems, and even matches existing white-box analyzers designed for hand-crafted TE heuristics.

---

### [39] Editing as Language: Teaching LLM Agents a Grammar for Native Context Editing

**链接**: https://arxiv.org/abs/2610.25550
**作者**: Yunlong Deng, Yan Li, Xing Hu, Yida Zhu, Sean Du, Weiyang Liu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A synopsis in novels folds a story into a few lines; a function in code gathers many steps with a single execution. Context editing is native to language itself. In this paper, we propose the Native Context Editing (NCE) framework, which gives language model agents a grammar for natively editing their own context. By encoding context-editing operations in a grammar of dedicated special tokens, we teach the agents to invoke edits through the language itself. We train agents on iteratively constructed trajectory segments, with each teacher edit conditioned on the evolving context. This establishes context editing as an atomic and inherent capability of LLM agents, enabling them to dynamically modify their context as they generate responses over long-horizon reasoning and interaction. Compared with context-editing methods that learn to generate tool-use code within specific external harness environments, our approach integrates context editing as an internal mechanism of the model's nativ

---

### [40] Uncovering Semantic Hierarchies in Text-Attributed Graphs via Variational EM-based LLM-GNN Synergy

**链接**: https://arxiv.org/abs/2610.24624
**作者**: Yunhui Liu, Xudong Jin, Qizhuo Xie, Chunhui Zhao, Xiao Luo, Tao Zheng 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While hierarchical structures are intrinsic to organizing human knowledge, current representation learning on text-attributed graphs predominantly operates on flat semantic spaces, overlooking the rich coarse-to-fine granularity inherent in real-world data. To bridge this gap, we propose SHiFT, which synergizes the reasoning power of LLMs with the structural representation capability of GNNs within an Expectation-Maximization (EM) paradigm. In the E-step, we harness LLMs as expert taxonomists to induce an explicit semantic tree, introducing a lightweight Mapping & Diagnosis strategy that reduces inference costs by surgically updating the hierarchy only when anomalies are detected. In the M-step, we align the GNN encoder with this induced hierarchy from complementary perspectives, including clustering partition, topological skeleton, and semantic concepts. Theoretical analysis interprets SHiFT as a generalized Variational EM algorithm. Extensive experiments demonstrate that SHiFT not on

---

### [41] LLMSA-MC: Bridging LLM Reasoning and Static Analysis for Detecting Missing-Check Bugs in Linux Kernels

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3858419&hl=zh-CN&sa=X&d=5086053653906343122&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVFcYu3ob_qhaWTjv1V0bh7C&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=9&folt=kw-top
**作者**: J Shi, T Liu, Y Wang, P Liu, X Wang, W Ji - ACM Transactions on Software … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address these challenges, we present LLMSA-MC, a framework that combines static analysis with LLM -based semantic reasoning for missing-check bug detection. LLMSA-MC incorporates three strategies: (1) Statement Type Classification, which

---

### [42] Beyond Attack Success Rate: Cost-Aware Metric for Evaluating Iterative LLM Jailbreaks

**链接**: https://arxiv.org/abs/2610.26589
**作者**: Rohan Menon, Chih-Hong Cheng
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attack success rate (ASR) evaluates jailbreaks against large language models without accounting for repeated calls to the victim model. Yet each additional call gives the deployed system another opportunity to detect the attack and intervene. We introduce $\mathrm{ASR}_{\mathrm{STEP}}$, which penalizes additional victim-model calls while retaining binary success judgments. Our evaluation considers GCG~\cite{zou2023universal}, PAIR~\cite{chao2025jailbreaking} with a step budget, and a single-step PAP~\cite{zeng2024johnny} baseline on JailBreakBench across three model families. GCG's scores decrease by 7.0--8.7 percentage points after discounting, while PAP's remain unchanged. While for PAIR~\cite{chao2025jailbreaking}, we see a wider discounting range between 3.4-12 percentage points, showing that the "step" quantity differs per iterative strategy. Reporting both metrics makes the discount due to repeated victim-model interaction explicit. Code is available \hyperlink{https://github.com

---

### [43] Can LLM User-Proxies Stand In for Humans in Reliance Measurement? Replicating Rel-A.I. with Simulated Users

**链接**: https://arxiv.org/abs/2610.25788
**作者**: Shuai Wang, Rui Hu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can language-model user proxies reproduce human reliance on an AI answer across contexts? Published simulated-user studies do not establish validity for this partial-answer decision, and Rel-A.I.'s released human record omits trial-level choices. We audit its 90 printed questions and 15 domain-by-marker reliance rates using sampled decisions and counterbalanced A/B probabilities from open models through 72B parameters. A matched crossover varies the printed agent specialty within each question, separating question content, label averages, and their interaction. Mistral Small's strong-marker math-minus-law label marginal is -0.4 percentage points, yet matching the agent label to the question domain raises reliance by 13.3 points on average across the five domains. The best A/B proxy has 22.5-point absolute-rate error and 8.3-point domain-effect error against the human table. A two-sample independent-binomial human replication has 3.5-point expected domain-effect error under the stated w

---

### [44] AllPath: Layered Verification for a Deployed, Self-Revising LLM Trading Agent under Human-Gated and Autonomous Regimes

**链接**: https://arxiv.org/abs/2610.26662
**作者**: Tian Zhang, Meng Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM trading agents are evaluated almost exclusively in backtests and autonomous benchmark harnesses. Deployment, where actions are irreversible, raises a different question: who verifies the agent's actions, and which failures can each verifier structurally catch? We report on AllPath, a personal LLM trading agent deployed against a live paper-brokerage account. The system watches positions through a deterministic rules engine, and each night it reviews its own day and proposes revisions to its own trading strategies. Verification is split across three layers. Code verifies what must not depend on judgment: deterministic gates enforce risk limits and block any strategy revision that fails an integrity check. The agent verifies itself within fixed bounds: its nightly review has an iteration cap and no tools that can act. A human verifies judgment, through approval screens that show the current state of each proposal. We also compared two verification policies for the agent's self-revisi

---

### [45] Selm: Self-Evolving Library Management for Multi-Skill Agent Optimization

**链接**: https://arxiv.org/abs/2610.24630
**作者**: Mengxi Hu, Yuxuan Hu, Jinbo Su, Ke Wang, Honghao Shi, Wenli Wu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly use skills as a lightweight way to acquire task-specific knowledge. Recent work enables skills to evolve from task trajectories. However, these methods often lack systematic management of evolved skills, making it difficult for agents to reuse and accumulate skills across domains, thus limiting performance on subsequent tasks.To reliably accumulate, reuse, and maintain useful skills across tasks, we present SELM (Self-Evolving Library Management), a framework that formulates skill evolution as library-level management. SELM jointly manages skill retrieval, updating, and lifecycle by maintaining skill confidence and utility signals. It introduces utility-aware retrieval to select useful skills, a Map-Reduce framework to generate targeted updates from task-specific experience, and lifecycle controls to retain or remove skills based on their effectiveness. These mechanisms enable the skill library to continuously accumulate useful experience 

---

### [46] When Empathy Misses the Goal: A Benchmark for Goal Displacement in LLM Advice

**链接**: https://arxiv.org/abs/2610.25522
**作者**: Dean Ariel and Guy Laban
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational large language models can respond with warmth and reassurance while failing to advance the user's stated goal. We conceptualize this failure as $\textbf{goal displacement}$, the substitution of persona-maintenance content for goal-relevant substance. To measure it, we introduce $\textbf{GDB}$ (Goal Displacement Benchmark), comprising 230 scenarios across nine domains and $4{,}134$ human-scored responses from 18 models. A $2 \times 2$ taxonomy crosses hard constraints with emotional distress, distinguishing failures to confront infeasible goals or combine empathy with practical guidance from reverse displacement, where unsolicited problem-solving replaces requested emotional support. A deletion-test rubric assesses whether substantive help remains after purely supportive sentences are removed. Independent raters achieve weighted $\kappa = 0.82$ against author scores for displacement severity. Trap displacement ranges from $0.0\%$ to $37.7\%$ and is strongly negatively cor

---

### [47] CXBench: A Benchmark for Process-Compliant LLM Agents in Regulated Customer-Experience Workflows

**链接**: https://arxiv.org/abs/2610.25954
**作者**: Boxi Yu, Yuzhong Zhang, Zhenfeng Su, Linfu Xi, Yinghan Yao, Shitao Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using language agents increasingly perform regulated customer-service workflows, where a correct final state is insufficient: agents must also provide disclosures, obtain consent, and follow required procedures. Existing tool-agent benchmarks largely score final business states, accepting trajectories that reach correct outcomes through non-compliant processes. We introduce cxbench, a benchmark that evaluates outcome and process compliance separately across six regulated domains. Each task combines a customer request, a tool-based environment, and explicit process requirements. Rule cards link cited regulatory obligations to observable trace evidence. A hybrid grader combines deterministic checks for ordering and authority with an LLM judge for semantic requirements. We define a false-pass as an outcome-pass run that fails process checks. Across seven models and 120 tasks, 55.5% of the 840 retained executions are false-passes, representing 80.1% of outcome-passing runs; only 13.8%

---

### [48] RouteWeaver: Weaving Mode Selection and Execution into Unified LLM Routing

**链接**: https://arxiv.org/abs/2610.19705
**作者**: Xiaohan Wang, Haozhen Zhang, Qingyuan Liu, Tao Feng, Wenya Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Where is Physical RSI capability from? An Observational Scaling Law of LLM-as-policy

**链接**: https://arxiv.org/abs/2610.26848
**作者**: Zekai Li, Jiayi Yu, Jinlu Zhang, Luyang Niu, Zekun Qi, Jun Zheng 等 (10 人)
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we systematically investigate the mechanisms, scaling behavior, and generalization of physical Recursive self-improvement. We introduce PhysRSI-eval to quantify physical RSI through a five-axis metric: First-Attempt Performance, Efficiency, Success, Budget and Improvement from failure. Different VLMs are evaluated on 18 manipulation tasks under a fixed interaction budget. The analysis of experimental results motivates the Physical Barrel Hypothesis: different capabilities may constrain different parts of improvement. The five-axis metrics also distinguish systems with close public benchmark averages and show that high scores need not come with early or efficient gains. We study observational scaling from two perspectives: predicting the relative performance of VLM agents from their public capabilities, and forecasting later progress from early physical feedback. Together, these analyses ask how quickly and how far an agent can improve. Moreover, we conduct workspace inte

---

### [50] Coral: Cost-Efficient Multi-LLM Serving over Heterogeneous Cloud GPUs

**链接**: https://arxiv.org/abs/2605.04357
**作者**: Yixuan Mei, Zikun Li, Zixuan Chen, Shiqi Pan, Mengdi Wu, Xupeng Miao 等 (8 人)
**来源**: cs.DC cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] TimelineAgent: An LLM-based Framework for Query-Centric Event Timeline Extraction Across Multiple Documents

**链接**: https://arxiv.org/abs/2610.25733
**作者**: Qingkai Min, Yunxin Bao, Yifeng Lu, Zhenyu Feng, Yulong Chen, Andreas Vlachos 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Query-centric cross-document event timeline extraction aims to construct event timelines from multiple documents under diverse query focuses. The task is very challenging due to the heterogeneous event modeling and reasoning requirements arising from both the intrinsic complexity of cross-document timeline construction and the diversity of query focuses. In this paper, we propose TimelineAgent, an LLM-based multi-agent framework featuring a multi-stage reasoning workflow, where heterogeneous event features are organized into reusable skills and orchestrated through a goal-oriented protocol. To facilitate evaluation, we construct a benchmark covering diverse query focuses. Experimental results show that TimelineAgent consistently outperforms existing methods, offering a practical framework for complex real-world timeline construction.

---

### [52] SpecLLM: LLM -based VNIR spectral interpretation

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-75562-5_reference.pdf&hl=zh-CN&sa=X&d=2474017548560699633&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVEnBN-5GgwIBOOtftj_4vXP&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=6&folt=kw-top
**作者**: M Romaszewski, A Strzoda, M Halama, P Głomb… - Scientific Reports, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The vast majority of LLM -based applications in spectral analysis primarily rely on raw numerical spectra representation as LLM inputs, where … or amplitude, instead of using raw spectra, for LLM -based interpretation of chemical states. Results show

---

### [53] TrustAgent-RFF: Agentic Diagnostic Planning for Reliable RF Fingerprinting under Domain Shift

**链接**: https://arxiv.org/abs/2610.24930
**作者**: Chuan Liu, Tianya Zhao, Xuyu Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radio frequency fingerprinting (RFF) models can achieve accuracy under source domain conditions but become unreliable when the receiver, distance, collection day, or environment changes. Incorrect predictions in unseen domains may receive high softmax confidence, making confidence thresholding insufficient for trustworthy deployment. We propose TrustAgent-RFF, a prediction level reliability framework for RFF that operates with a frozen in-phase and quadrature (I/Q) classifier without target domain labels. For each device prediction, the framework acquires radio frequency evidence: counterfactual stability, prototype consistency, acquisition domain similarity, and signal quality. A source calibrated trust estimator combines these diagnostics with classifier confidence, prediction margin, and evidence availability indicators. Source derived lower tail penalties and cross module interactions reduce trust when diagnostic signals indicate weak support. A large language model (LLM) based pla

---

### [54] Screening LLM Judges Without Ground Truth: A Preliminary Evaluation of an AI Dental Hygiene Coach

**链接**: https://arxiv.org/abs/2610.24335
**作者**: William DeShong, Barath Kannan, Auberon Palma, Brenda Bradshaw, James F. Leathrum, Jr. 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating a fine-tuned coaching model with expert graders is slow and expensive, and an LLM judge cannot be trusted without ground truth. We present a staged pipeline that screens candidate LLM judges and student models before expert review, using explicit decision rules at each stage: judge output audit, similarity with hosted judges, bias checks, and decision robustness. We demonstrate it on an AI dental hygiene coach. The case study uses synthetic, clinically unvalidated training and reference data to demonstrate the operation of the pipeline, rather than to establish the clinical performance of the resulting models. Two fine-tuned small language models (Granite-4.1-8B and Qwen3-8B), each trained at three data sizes, were scored on seven metrics by five judges (three local, two hosted). Two local judges, Qwen3.8-27B and Gemma-4-31B-it, were not distinguishable from the agreement between the hosted judges on six of seven metrics by rank correlation, and Qwen3.8-27B was the most simi

---

### [55] MemBubble: Benchmarking How Agent Memory Shapes LLM Response Diversity

**链接**: https://arxiv.org/abs/2610.25127
**作者**: Jiajun Tan, Fei Sun, Xinyu Ma, Shixuan Zhang, Du Su, Qi Cao 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory serves as the core component of LLM-based agents, enabling personalized responses via extracting and using user preferences from past interactions. However, its use may reduce response diversity, thereby narrowing the range of information available to users. Existing evaluations rely largely on synthetic interactions and cover few memory systems, leaving the effects of memory on response diversity insufficiently evaluated in real-world scenarios. We introduce MemBubble, a benchmark of 1000 instances built on preferences extracted from real user-assistant conversations. To measure the extent to which memory concentrates response distributions, we construct test queries in scenarios distinct from user preferences while preserving topical relevance through shared preference categories. Across multiple LLMs and memory mechanisms, entropy decreases by 34.7% on average compared with directly providing the full interaction history, highlighting the important role of memory processing i

---

### [56] LLM-Assisted Bi-Approximate CHC Solving

**链接**: https://arxiv.org/abs/2610.23771
**作者**: Baiting Jiang
**来源**: cs.LO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constrained Horn clause (CHC) solvers often struggle to discover deep counterexamples whose derivations may require extensive rule unfolding. Although large language models (LLMs) can propose long-range symbolic relations, prior work on formally checked LLM-assisted verification has mainly focused on generating inductive invariants and concrete traces. We exploit this broader capability through Derivation Power Under-approximations (DPUs). Each DPU is a solver-certified under-approximation of the relation induced by a multi-step CHC derivation. An LLM proposes each DPU with symbolic intermediate-state witnesses that enable SMT validation without introducing additional quantifiers. Validated DPUs can be composed and reused soundly. Building on this mechanism, our LLM-assisted framework HornCraft combines invariant generation for over-approximation with DPU generation for under-approximation in CHC solving. On 260 linear and nonlinear integer-arithmetic CHC-COMP benchmarks left unresolve

---

### [57] Calibrating LLM Judges for Human and AI Conversations

**链接**: https://arxiv.org/abs/2609.29431
**作者**: Maike Z\"ufle, Patr\'icia Schmidtov\'a, Vil\'em Zouhar, Shree Harsha Bokkahalli Satish, Erica Cooper, Nicholas Sanders 等 (10 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] BOSS: Token-Budgeted Online Sampling and Selection for LLM Reasoning

**链接**: https://arxiv.org/abs/2610.26383
**作者**: Yupeng Chang, Yahan Li, Chenlu Guo, Diana Inkpen, Yuan Wu, Yi Chang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling can improve LLM reasoning, but existing approaches typically adapt generation or apply answer selection after a predetermined generation schedule. We study within-instance allocation: under a hard per-instance prompt-plus-completion token cap, when should inference stop, generate another candidate, or spend residual tokens adjudicating candidates already observed? BOSS is a training-free policy for this three-way decision, with worst-case budget checks before every generation and judge call. Its key contribution is online generation-adjudication allocation under one shared token ledger. Across two Llama-3.1 models and four reasoning benchmarks, BOSS attains the highest accuracy in 22 of 24 model-task-budget cells under the common hard cap. At Llama-3.1-8B and B=4k, it reaches 60.5 macro-average accuracy versus 58.6 for Adaptive-Consistency, 59.1 for TALE-EP, and 58.9 for fixed-schedule League. On identical Stage-I candidate pools, randomized A/B judging with repeated 

---

### [59] Hierarchical and Query-Aware Visual Token Pruning for High-Resolution LVLMs

**链接**: https://arxiv.org/abs/2610.24102
**作者**: Luther Wei, Ling Zou, Kang-Yang Huang, Yu-Syuan Xu, and Wen-Huang Cheng
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-resolution Large Vision-Language Models (LVLMs) preserve critical, fine-grained visual details by encoding a global thumbnail alongside multiple local crops. However, the resulting thousands of vision tokens introduce severe computational bottlenecks during Large Language Model (LLM) inference. Existing token pruning methods rely primarily on query-agnostic visual saliency, while current query-aware approaches either operate at a coarse crop-level resolution or compute token relevance too late, after vision tokens have already entered the heavy LLM layers. To address this, we propose a training-free, hierarchical token pruning framework that utilizes query guidance prior to executing any LLM blocks. Our top-down hierarchy first operates at the instance-level, dynamically scaling the vision token retention ratio of each sample based on its visual complexity. Next, at the crop-level, we distribute this sample budget across local crops using sentence-level cross-modal similarity. Fin

---

### [60] Legal Guidance in the Wild: How Users Seek Legal Help in Real-World LLM Conversations

**链接**: https://arxiv.org/abs/2610.25159
**作者**: Amirreza Mohseni, Gerasimos Spanakis
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People ask conversational AI models about their legal rights, obligations, procedures, and personal situations that may have legal consequences. To study this behavior, we first need to distinguish requests for legal guidance from other legally themed discussions and unrelated conversations. We contribute a multi-axis taxonomy of legal queries capturing whether legal guidance is sought, how a request is formulated, and which legal domains it concerns; apply it to 2,122 naturally occurring WildChat-1M conversations; and create a human-reviewed gold evaluation set of 200 conversations. All annotations, model checkpoints, and evaluation code are publicly available. In this enriched sample, 71.1% of conversations containing legal content seek personalized or practical guidance. Rights-and-options advice is the most common primary request type among legal-content conversations, and 25.3% of guidance-positive conversations span multiple legal topics. The gold evaluation set supports a two-st

---

### [61] Diet Your LLM: Dimension-wise Global Pruning of LLMs via Merging Task-specific Importance Score

**链接**: https://arxiv.org/abs/2603.23985
**作者**: Jimyung Hong and Jaehyung Kim
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] It's Complicated: Factors Influencing the Effectiveness of LLM-Generated Feedback in a Live Programming Course

**链接**: https://arxiv.org/abs/2610.25244
**作者**: Tsvetomila Mihaylova, Arto Hellas, Bita Akram, Narges Norouzi, Peter Brusilovsky, Juho Leinonen
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We report on three iterations of an LLM-generated feedback system deployed in a live web development course, spanning three underlying models and three feedback formats. We ask how feedback presence and its characteristics (length, complexity, format) relate to student performance, whether prior feedback exposure is associated with final-project performance, and how performance changes after first exposure. Feedback was associated with more favorable immediate outcomes in several comparisons, but the pattern varied by outcome and period. In pooled models, longer feedback was associated with lower next-submission correctness, more remaining attempts, and longer resubmission time. Prior same-part feedback was associated with lower final-project solve probability. Student-level comparisons found differences on final-project steps begun before exposure, while within-student changes across steps were uncertain. These comparisons do not identify the causal effect of feedback. Changes on stan

---

### [63] Toward Safe LLM Agents: A Survey of Specification, Verification, and Enforcement

**链接**: https://arxiv.org/abs/2608.14590
**作者**: Pierre Dantas, Lucas Cordeiro, Ehsan Nowroozi, Norbert Tihanyi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] Figures as Interfaces: Toward LLM-Native Artifacts for Scientific Discovery

**链接**: https://arxiv.org/abs/2604.08491
**作者**: Yifang Wang, Rui Sheng, Erzhuo Shao, Yifan Qian, Haotian Li, Nan Cao 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Empowering Edge Agents: A Systematic Analysis of Edge-Cloud Collaboration in LLM Agent Execution

**链接**: https://arxiv.org/abs/2610.17816
**作者**: Pengcheng Huang, Zhenghao Liu, Shixin Ren, Shi Yu, Sijia Yao, Yukun Yan 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] TeleTwin: A Calibrated Digital Twin of Telegram Crisis Discourse as a Ground-Truth Testbed for Detecting LLM-Powered Information Operations

**链接**: https://arxiv.org/abs/2610.23944
**作者**: Despoina Antonakaki and Sotiris Ioannidis
**来源**: cs.SI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models make it cheap to run influence operations whose messages never repeat, yet real platforms offer almost no ground truth for testing whether coordination detectors can find them. The problem is sharpest on Telegram, which moderates little and spreads content through broadcast channels and forwarding rather than a follow graph. We introduce TeleTwin, an LLM-powered digital twin of a Telegram crisis-discourse ecosystem in which channels are agents, each instantiated from the history of a real channel, calibrated on 1.07 million messages from 195 public channels on the Israel-Gaza and Iran-Israel conflict (March-August 2025). On a held-out period containing the June 2025 Iran-Israel war, the twin tracks daily dynamics better than statistical baselines (correlation 0.86 against 0.64) and reacts to the war unprompted, but it over-focuses on the conflict, over-amplifies forwarding cascades, underestimates the shock and writes recognisably LLM-like text. We then inject LLM

---

### [67] Beyond Cooperative Simulators: Generating Realistic User Personas for Robust Evaluation of LLM Agents

**链接**: https://arxiv.org/abs/2605.12894
**作者**: Harshita Chopra, Kshitish Ghate, Aylin Caliskan, Tadayoshi Kohno, Chirag Shah, Natasha Jaques
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Towards clinical communication training with LLM -based conversational virtual patients and automatic evaluation systems

**链接**: https://scholar.google.com/scholar_url?url=https://search.proquest.com/openview/ddb5b7e376159fbd924ac1fed0183579/1%3Fpq-origsite%3Dgscholar%26cbl%3D5642945&hl=zh-CN&sa=X&d=12070914286861872967&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVFVEl8aQETDu02Ig57EfBfc&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=8&folt=kw-top
**作者**: A Bayona, R Manrique, C Grévisse - Discover Artificial Intelligence, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background Clinical communication is a fundamental skill that impacts patient satisfaction, treatment adherence, and clinical outcomes. Traditional training methods, such as standardized patients (SPs) or virtual standardized patients (VSPs)

---

### [69] Comparing Experiences of Speech-Driven Game Modification in Solo Play, Paired Play, and Paired Watching Using the Fighting Game PATCH FIGHTER

**链接**: https://arxiv.org/abs/2610.26447
**作者**: Maya Grace Torii, Takahito Murakami, Yoichi Ochiai
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Players often have ideas about a game while playing it, but turning them into changes usually means stepping out of play to edit it. We built PATCH FIGHTER, a two-player fighting game defined by 91 types of adjustable parameters. A large language model (LLM) reads players' conversations during play and rewrites these parameters between games, so players can change the game just by talking. We conducted a within-subjects experiment with 27 pairs (54 participants) comparing three conditions, solo play, paired play, and paired watching. Participants rated enjoyment after each game and answered a questionnaire on speech and changes after each condition. Paired play was the most enjoyable condition. In paired play, participants also felt more able to say what they thought about the game than in solo play. In interviews, participants valued talking with the partner and checking changes through their own play. Paired watching was less preferred because they could not try the changes themselve

---

### [70] REATS: LLM Reasoning-based Ensemble Learning for Adaptive Time Series Forecasting

**链接**: https://arxiv.org/abs/2608.10149
**作者**: Xu Zhang, Chang Xu, Hui Sun, Nan Ma, Zijian Zhang, Peng Wang 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] Break It Down, Pass It On: Cross-Task Skill Transfer in LLM Agents

**链接**: https://arxiv.org/abs/2608.20274
**作者**: Yiyang Feng, Biddut Sarker Bijoy, Niranjan Balasubramanian, Jiawei Zhou
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] The Double-Edged Sword of Open-Ended Interaction: How LLM-Driven NPCs Affect Players' Cognitive Load and Gaming Experience

**链接**: https://arxiv.org/abs/2604.10107
**作者**: Ting-Chen Hsu, Wenran Chen, Jiangxu Lin, Fei Qin, Zheyuan Zhang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Lexical semantic development of high-frequency polysemous words in L2 writing: An LLM -assisted sense-level analysis

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1060374326000901&hl=zh-CN&sa=X&d=16215692682815469970&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVEw2zg0II1JPejtWDXedU1C&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=4&folt=kw-top
**作者**: H Deng, M Liang - Journal of Second Language Writing, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> A key dimension of L2 writing development is learners’ ability to use words across a wider and more differentiated range of senses, yet this development remains difficult to capture at scale. This study proposes a scalable corpus-based approach to

---

### [74] Neither Over- nor Under-Constrained: Evaluating LLM Personalization under a Constraint Qualification Audit

**链接**: https://arxiv.org/abs/2610.25676
**作者**: Xuran Li, Guanqin Zhang, Imran Razzak, Hakim Hacid, Eleanna Kafeza, Hao Xue 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate evaluation of LLM personalization is hindered by current evaluation paradigms that over- or under-constrain the response space, yielding frequent false rejections and false acceptances. To reduce these false rates, we introduce ConQual-Audit, an audit-based framework that evaluates LLM personalization through a three-stage process: (1) extracting semantic constraints from user profiles and task-grounded reference; (2) qualifying constraints by pruning unnecessary constraints and recovering missing constraints; and (3) verifying candidate responses against the audited constraints via natural language inference. Across PrefEval and LaMP, ConQual-Audit outperforms nine baselines, attaining top AUCs (0.88 and 0.90) and the lowest false rate (0.21) on the leanest constraint sets at an amortizable audit cost. Crucially, this constraint audit is portable: integrating it into ExPerT and PREF helps revise smaller, higher-quality constraint sets to reduce their evaluation false rates.

---

### [75] Memories That Outlive Their Reasons: Dependency-Tethered Memory for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2610.25123
**作者**: Yiqi Wang, Jinqian Ju, Jiaqi Zhang, Zhangkai Wu, Yiqun Duan, Zequn Sun 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents now act on the Web, publishing packages, models and datasets through registry APIs, and remembering past verifications spares them the work. But a verdict rests on premises. When a signing key is revoked, everything built on it stops passing, yet the advisory names only the key, and the old verdicts of its dependents may never share a retrieval window with it. This non-locality of invalidation turns memory into a liability: in long simulated chats, an agent reading a memory of atomic facts publishes 62% of the objects whose failure lies upstream, each backed by a record that was true when written. Yet derivation is local even when invalidation is not. Tether records, at write time, the exact versions each verdict derives from, and at read time withdraws any verdict whose support has failed anywhere in the store; the agent reads the same fields as before. On Fallout, a generator of versioned worlds with hypothesis-blind simulated histories shared by every memory, Tether publishes

---

### [76] RouterWorld: Scaling Conversational AI with Latency-Aware LLM Routing

**链接**: https://arxiv.org/abs/2610.26511
**作者**: Jinyang Li, Denis Emelin, Simone Tedeschi, Weiwei Cheng, Cristina Morariu, Haytham Assem 等 (9 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational AI systems built on Large Language Models (LLMs) require routing mechanisms that balance answer quality and response latency at scale. However, existing LLM routing benchmarks assume full observability of all candidate model outcomes, under-emphasize latency as a first-class metric, and fragment evaluation across heterogeneous protocols misaligned with real-world settings. We introduce RouterWorld, a comprehensive benchmark for LLM routing in conversational GenAI. RouterWorld unifies 371k single-turn responses and 76k multi-turn agentic trajectories, adopts natural user interactions with a standardized LLM-as-a-judge protocol, and decouples efficiency from transient pricing via hardware-grounded latency annotations. Crucially, RouterWorld formalizes routing under partial observability through two setups: Cold-Start, which restricts learning to sparse, static logs, and Voyager, which models continuous data streams where routing decisions shape future training distribution

---

### [77] Does Unlearning Survive Collaboration? Robust Unlearning for Shared-Model LLM Teams

**链接**: https://arxiv.org/abs/2610.25731
**作者**: Hengsong Liu, Liangyu Teng, Jingnan Cai, Yuntian Shi, Jingyu Zhang, Yang Liu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM unlearning is essential for removing sensitive or unwanted knowledge while preserving useful capabilities. As LLM teams are increasingly used to solve complex problems, forgetting must remain effective during collaboration. Despite advances in forgetting effectiveness, efficiency, and robustness to relearning, team deployment remains underexplored. We find that collaboration weakens forgetting: final-answer evaluations miss recoverable evidence in team messages, including complementary clues supporting joint recovery. We establish theoretically and confirm empirically that controlling final answers or individual messages does not ensure low recovery from their combination. To address this challenge, we propose Aggregation-Conditioned Unlearning (ACU). ACU trains a shared model using reconstruction feedback from individual and pooled messages, prioritizes views with higher recovery risk, and uses replacement-based credit assignment while protecting direct and collaborative utility. 

---

### [78] DUALVIEW: Leveraging Broad and Output-Specific Evidence for LLM-based Multi-Output Text Regression

**链接**: https://arxiv.org/abs/2610.19206
**作者**: Yiheng Su, Junyi Jessy Li, Matthew Lease
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Beyond Behavioral Accuracy: Evaluating Individual-Level Fidelity in LLM Investor Simulation

**链接**: https://arxiv.org/abs/2610.26524
**作者**: Jiajie He, Yuanhong Jiang, Xintong Chen, Dongling Ni, Wenjin Liu
**来源**: cs.AI cs.HC cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as user simulators, but can they faithfully reproduce an individual's behavior and decision logic over time? We investigate this question in a longitudinal paper-trading study with 80 participants. Using rolling next-day predictions, we evaluate trading activity, buy-sell structure, asset selection, and portfolio outcomes, complemented by controlled input ablations and participant-rated explanation alignment. No evaluated LLM reliably outperforms a simple recent-activity persistence baseline for predicting trade occurrence, while buy-sell structure and asset selection remain difficult to reproduce. Similar activity-level performance can also yield substantially different portfolio trajectories. Ablations show that activity predictions depend primarily on recent trades, whereas asset choices are sensitive to multiple evidence sources. Participants rate explanations as more aligned with their recurring strategies than with their decision

---

### [80] Not What, But How: A Framework for Auditing LLM Responses across Positioning, Generalization, Anthropomorphism, and Maxims

**链接**: https://arxiv.org/abs/2606.02493
**作者**: Siddhesh Milind Pawar, Sarah Masud, Haneul Yoo, Alice Oh, Isabelle Augenstein
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [81] LLM Evolutionary Search Strategies Should be Compared by Tokens

**链接**: https://arxiv.org/abs/2610.23977
**作者**: Tal Oved and Roi Pony and Oshri Naparstek and Udi Barzelay
**来源**: cs.NE cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM evolutionary search is currently evaluated by counting proposals (candidate programs). We demonstrate this metric hides the true cost of search, and redo the comparison using tokens. By replaying 600 logged runs across 5 tasks and 3 methods, we show that proposal costs vary wildly from 16k to 39k tokens. In equal-proposal comparisons, this silently grants some methods up to 1.9x the compute of others, and gives evolution roughly 6x the budget of independent sampling. When we match token budgets, giving sampling six times more attempts, and remove scorer exploits, the evolutionary advantage largely vanishes. Evolution beats independent sampling by 5% or less on 12 of 15 task-method pairs, retaining a 23 to 28% margin on only 3, all on one task. A replication with Claude Haiku 4.5 reproduces this split, though a third backbone shows its size depends on the model too. The performance margin justifying these systems is often an accounting artifact. Reporting tokens, not proposals and n

---

### [82] AURA-Eval: Evaluation Framework for Acting Under Risk Awareness in LLM Agent Trajectories

**链接**: https://arxiv.org/abs/2609.06783
**作者**: Ruoxi Shang, Christina-Maria Androna, Orfeas Menis Mastromichalakis, Yu Feng, Aniruddhan Ramesh, Rico Angell 等 (9 人)
**来源**: cs.CR cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] MemPoison: Uncovering Persistent Memory Threats and Structural Blind Spots in LLM Agents

**链接**: https://arxiv.org/abs/2607.14651
**作者**: Jifeng Gao, Kang Xia, Yi Zhang, Xiaobin Hong, Mingkai Lin, Xingshen Wei 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] MotionShift: Environment-Compatible Motion Transfer via Planner-Evaluator Synergistic Adaptation

**链接**: https://arxiv.org/abs/2610.25290
**作者**: Yanchen Liu, Junyao Gao, Yanan Sun, Wensheng Chen, Guangming Lu, Wenjie Pei
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing motion transfer methods excel at exact, rigid motion replication from reference videos to target scenes, whereas they often fail to account for the compatibility between the transferred motion and the target scene environment in accordance with physical laws. In this work, we propose MotionShift, a novel motion transfer framework that achieves high-fidelity motion transfer while ensuring physical compatibility with the target scene. In particular, we design a planner--evaluator iterative motion adaptation mechanism, in which a Large Language Model (LLM) acts as the planner to generate motion trajectories by leveraging its strong semantic reasoning capabilities, while a Vision-Language Model (VLM) serves as the evaluator to rectify the motion based on its superior visual perception and scene understanding. Through this planner--evaluator synergistic reasoning process, the motion is adapted to the target scene in a training-free manner. The adapted motion is then used as a gener

---

### [85] LLM application in digital asset assessments: mixed methods research

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s10115-026-02910-2&hl=zh-CN&sa=X&d=13117462234845320403&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVFG7KmUdGp2kAEd978_Mn54&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=5&folt=kw-top
**作者**: Y Thorens, M Angerer, P Ebrahimi, J Schneider - Knowledge and Information Systems, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Using a Design Science Research methodology, we developed a framework and a prototype tool to apply LLM -based evaluation to token-… observed optimism bias is not specific to the original closed LLM , although performance still varies across

---

### [86] NeurOWL: An LLM-Based Neural-symbolic Framework for Incomplete OWL Ontology Reasoning

**链接**: https://arxiv.org/abs/2607.15776
**作者**: Hui Yang, Jiaoyan Chen, Yiping Song, Renate Schmidt, Wen Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] Auditor-Assisted Summary-Channel Verification for Hosted LLM Identity Substitution

**链接**: https://arxiv.org/abs/2610.25982
**作者**: Ziyi Zhang, Ziyao Wang, Guoheng Sun, Ang Li, Jian Li
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hosted LLM services increasingly expose model identity as a product claim, but external users and auditors often cannot inspect which model configuration served a request. We study an auditor-assisted regime in which a trusted auditor enrolls claimed identities and prepares verification material before deployment, while audit-time verification uses only the claimed identity and released output, without runtime access to model internals, inference logs, routing decisions, or provider metadata. We propose SUMMARK, a summary-channel watermarking framework that uses user-visible reasoning summaries as a keyed audit surface. During setup, SUMMARK constructs identity-specific vocabulary carriers, trains lightweight summary adapters, and calibrates per-identity thresholds. At deployment time, a keyed statistical test assesses whether the released summary is consistent with the claimed identity and, when needed, attributes the most likely enrolled identity. Across model families, scales, and t

---

### [88] EdgeKernelBench: Unified LLM-Driven Kernel Generation for Edge Backends

**链接**: https://arxiv.org/abs/2610.24648
**作者**: Yuhua Zheng, Xueyi Chen, Xinze Zou, Xin Li, Haoji Hu, Huan Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent works show that LLMs can generate kernels with strong performance on server GPUs. Edge deployment presents distinct challenges because the hardware is heterogeneous, the software stacks are fragmented, and the resource budgets are tight. LLM kernel generation across diverse edge backends has yet to be studied systematically. We introduce EdgeKernelBench, which combines a unified IR deployment framework with a hierarchical benchmark for edge workloads. The unified IR captures reusable computation, scheduling, and memory decisions and connects to each target backend through a compiler interface. The benchmark spans progressively larger program scopes, from individual operators to compact model graphs, across representative edge application domains. We instantiate the design with TVM as a reference compiler and validate it across heterogeneous edge backends. With a single generation attempt, the best model achieves 64.5% Correct@1 but only 25.5% Fast@1.0. This gap shows that functi

---

### [89] From Solvers to Research: Large Language Model-Driven Formal Mathematics at the Research Frontier

**链接**: https://arxiv.org/abs/2607.07779
**作者**: Eric Jiang, Xiao Liang, Yingjia Wan, Mengting Li, Haikang Deng, Alexander Taylor 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] Budgeted Attack Scheduling for LLM Red-Teaming: The Roles of Static Priors, Semantic Guidance, and Online Feedback

**链接**: https://arxiv.org/abs/2610.25897
**作者**: Zhicheng Fang, Han Sun, Jiachen Lei, Xinyi Fang, Zongmin Zhang, Chenxu Fu 等 (8 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As jailbreak attacks against large language models (LLMs) become increasingly diverse, red-teaming has come to rely on large libraries of jailbreak prompts and attack strategies to evaluate the robustness of victim models and their defense settings. However, attack effectiveness is highly condition-dependent: an attack that succeeds under one victim-defense setting may fail under another, while exhaustively evaluating the full attack library for each setting incurs substantial token and monetary costs. This motivates studying how jailbreak attacks should be prioritized under a limited attempt budget for efficient robustness evaluation. In this work, we formalize this problem as budgeted attack scheduling over a fixed attack library and investigate three complementary signals under a fixed victim-defense condition: (1) static historical attack success rate (ASR) priors; (2) semantic guidance from LLMs; and (3) online feedback from earlier queries. Building on these signals, we design fo

---

### [91] Chopthin-Consensus Power Sampling: A Diversity-Preserving Approach to LLM Decoding

**链接**: https://arxiv.org/abs/2609.12243
**作者**: Minoo Ahmadi, Seyedarmin Azizi, Erfan Baghaei Potraghloo, Mehdi Kamal, Massoud Pedram
**来源**: cs.CL cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] Reliable Before Profitable: QuantHarness for Governing Financial Strategy Development with LLM Agents

**链接**: https://arxiv.org/abs/2610.26101
**作者**: Jiasheng Mao, Jiacheng Liu, Hengwei Ye, Zheng Tian
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can turn natural-language financial research requests into executable and backtested strategies, but a successful run may still implement the wrong rule, use information unavailable at decision time, or obscure how repairs and candidate selection changed the strategy. Because these failures arise throughout development, final code and performance metrics alone are insufficient to establish either fidelity to the request or the validity of the development process. We therefore address the reliability of financial strategy development at the trajectory level: the system must control how intermediate outputs become downstream state and preserve the evidence needed to justify the terminal outcome. We introduce QuantHarness, a two-layer agent harness in which a finance-specific Workflow structures specification, data grounding, construction, testing, and review, while Harness Core enforces stage-specific information, action, and commitment boundaries. We also introduce FinRelBenc

---

### [93] TESS: LLM-guided Translation, Exploration, Simulation, and Search for Embodied Task Planning

**链接**: https://arxiv.org/abs/2610.25930
**作者**: Peiran Xu, Yixiang Yang, Jinghan Li, Fei Li, Cao Sheng, JiaZhong Yu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this work we focus on the problem of embodied task planning, which requires an agent to accomplish a complex task by separating it into atomic actions. Recent studies have developed LLM-based methods to address this problem. However, the executability and correctness of the generated plans remain suboptimal in complex environments and tasks. On the other hand, classical search algorithms have the potential to solve the planning problems perfectly, yet they require fully observable environments, known state transitions and goal state, which are often unattainable in general task domains. Therefore, we propose to implement an LLM-guided search algorithm that makes the search process possible and efficient by incorporating LLMs' commonsense knowledge. Our method leverages LLMs to (1) translate natural language instructions into formatted goal conditions, (2) facilitate efficient exploration in partially observable environments, (3) implement a rule-based world simulator, and (4) prune 

---

### [94] Upgrade the Retriever First: What an LLM Call per Chunk Buys in RAG

**链接**: https://arxiv.org/abs/2603.23533
**作者**: Bhavik Mangla
**来源**: cs.CL cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] ClinSDT: LLM-Encoded Clinical Semantic Guidance for Sepsis Treatment via Decision Transformer

**链接**: https://arxiv.org/abs/2610.25121
**作者**: Yanyan Wu, Guanyu Zhu, Changbin Zhao, Jin Zhang, Dexu Yu, Tianmin Sun 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Offline sepsis treatment aims to learn treatment policies from retrospective ICU trajectories. Decision Transformer-based methods provide a natural sequence modeling framework for this task, but they mainly rely on raw physiological states and historical clinician actions. Such raw trajectory tokens may not explicitly capture clinical semantics that clinicians use in practice, such as patient severity, recent treatment response, and current risk priorities. To address this limitation, we propose ClinSDT, an LLM-assisted Decision Transformer framework for offline sepsis treatment. ClinSDT uses a frozen LLM as a semantic bridge rather than a treatment decision maker. It constructs three clinical semantic views from ICU trajectories, namely Profile, Context, and Advisory, and inserts their encoded representations as independent tokens into a Decision Transformer policy. To support policy refinement and rollout, ClinSDT further trains a Treatment-Response Forecaster to estimate the next ph

---

### [96] Planning Commitment of LLM under Partial Observability

**链接**: https://arxiv.org/abs/2610.21108
**作者**: Cassie Huang, Zhanwei Cao, Yeawon Lee, Nathalia Gomez, Zhuoyi Yang, Ian G. Harris 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] LOOP: Recovery-Aligned Iterative Layer Pruning via On-Policy Distillation

**链接**: https://arxiv.org/abs/2610.25679
**作者**: Liang Xu, Shufan Shen, Zhongni Hou, Yufei Zhang, Wei Lin, Guojun Yin 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Layer-level pruning is attractive for large language model (LLM) deployment as it reduces the model size while preserving a dense architecture that can be efficiently executed on standard hardware. Current methods typically follow a one-shot paradigm, which first removes selected layers to reach a target model size and then performs additional training to recover model capabilities. However, pruning directly to the target size can substantially degrade reasoning capabilities, making subsequent recovery more difficult under a limited training budget. Moreover, this paradigm separates layer selection from recovery, limiting the use of recovery information to guide selection and potentially hindering the recovery of reasoning capabilities. To address these limitations, we propose LOOP, a Layer-level Recovery-Oriented On-Policy Pruning framework that interleaves pruning and recovery across multiple shots. In each shot, LOOP removes a single layer and performs short on-policy distillation, 

---

### [98] When the Judge Should Not Decide: Evidence-Locked, Non-Compensatory Selection Bounds LLM-Judge Failure in Reasoning Pipelines

**链接**: https://arxiv.org/abs/2608.07813
**作者**: Yiyao Zhang, Diksha Goel, Hussain Ahmad
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [99] When LLM-Generated Refactorings Ripple: An Empirical Study of Repository Adoption Readiness

**链接**: https://arxiv.org/abs/2610.24790
**作者**: Muhammad Waseem, Aakash Ahmad, and Pekka Abrahamsson
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used to refactor source files, but file-local evaluations do not reveal changes to contracts, dependencies, or caller assumptions affecting repository adoption. To address this gap, we conduct 1,500 generation attempts across 150 production files from 15 open-source Java repositories, five LLM configurations, and two dependency-aware generation conditions: single-prompt refactoring and LangGraph-based multi-agent refactoring. Of these attempts, 1,455 yield complete candidates eligible for analysis. We evaluate these candidates using local changes, repository-facing structural indicators, detected caller impact, the behavioural-equivalence indicator, and available test evidence, and categorize them as Low-risk, Review-needed, High Contract/Dependency Risk, or Inconclusive. The results show that 1,365 candidates (93.8%) are classified as High Contract/Dependency Risk, whereas 106 (7.3%) have at least one detected broken downstream caller and 

---

### [100] Balance-Aware Pivot Selection for Parallel Diffusion LLM Decoding

**链接**: https://arxiv.org/abs/2610.26040
**作者**: Yejin Lee and Hyundong Jin and Yo-Sub Han
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion language models enable parallel token generation, offering a promising alternative to sequential autoregressive decoding. Existing acceleration methods use predictive confidence to enable parallel token commitment while preserving generation quality. However, confidence-based selection prioritizes reliable token predictions without explicitly considering how token positions shape the remaining decoding schedule. Moreover, such ordering does not always reflect inter-token dependencies, suggesting that confidence need not be the sole criterion for token selection. Motivated by this limitation, we propose Balance-Aware Pivot Decoding (BPD), which favors central pivots within contiguous masked intervals and decodes the selected positions in parallel. Balanced pivots yield logarithmic decoding depth in the interval length. Our practical method accounts for model uncertainty by combining confidence-based prefilling with confidence-thresholded center selection. We evaluate the resul

---

### [101] Memory-Induced Tool-Drift in LLM Agents

**链接**: https://arxiv.org/abs/2605.24941
**作者**: Mahavir Dabas, Jihyun Jeong, Ming Jin, Ruoxi Jia
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] Revealing what benchmark scores hide: Jointly measuring the breadth and reliability of LLM capabilities using accessibility profiles

**链接**: https://arxiv.org/abs/2610.24957
**作者**: Kazem Faghih, Yize Cheng, Shoumik Saha, Mobina Pournemat, Armin Gerami, Soheil Feizi
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model benchmarks assign each question a single outcome from one fixed wording, even though the same underlying request can be expressed in many equivalent ways. We argue that the quantity of interest should therefore not be correctness on one wording, but the accessibility of an inquiry, which we define as the probability that a model succeeds across meaning-preserving formulations. The distribution of accessibility across inquiries reveals a structure that accuracy and existing best-, worst-, or average-case prompt scores collapse: how broadly a model's capabilities extend across inquiries and how dependably those capabilities can be elicited. Two models can have the same average performance while one succeeds across more inquiries unreliably and the other succeeds across fewer inquiries but more consistently, leading to opposite preferences depending on whether the task allows multiple retries until one success or when repeated consistent success is required. Across six benc

---

### [103] Pattern-Driven Evaluation of LLM Code Optimization: Isolating Compiler-Transcendent Semantic Reasoning

**链接**: https://arxiv.org/abs/2610.24835
**作者**: Wesley Lu, Runzhou Liu, Hongru Du, Xinyao Yi
**来源**: cs.AI cs.PL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing evaluations of LLM-based code optimization primarily measure end-to-end speedup, obscuring whether a model actually performs the intended optimization. For compiled languages, this is especially problematic: observed gains may reflect transformations already recoverable by modern optimizing compilers rather than optimization behavior attributable to the model itself. We present PatternBench, a benchmark for studying compiler-transcendent optimization, i.e., performance improvements that remain after aggressive compiler optimization. PatternBench targets residual optimization opportunities across seven classes of transformations and pairs runtime evaluation with an AST-based optimization faithfulness analysis that verifies whether the intended optimization is realized in the generated program. Experiments with frontier, open-weight, and fine-tuned models show that runtime speedup alone provides an incomplete account of optimization capability. Optimization faithfulness is stron

---

### [104] Explore or Confirm? LLM Agents Misallocate Measurements Under Noise

**链接**: https://arxiv.org/abs/2610.25111
**作者**: Abdul Karim, Matt Keon
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As model reasoning gets cheaper, the physical experiment becomes the slow and costly step in discovery. Each experiment returns a noisy reading: a high value can mean a good candidate or a lucky draw. With a fixed budget, an AI agent must keep choosing between exploring a new candidate and confirming a promising one by re-testing it. We measure that choice in Wellocate, a simulated assay campaign with known true values. It is built on a generated landscape and on two real protein datasets, GB1 and PhoQ, scrambled so no model can answer from memory. We test five language models as minimal agents, with no tools and no memory beyond the history in each prompt. They misallocate in both directions. Three over-confirm, spending most of the budget re-testing. On the generated landscape one under-confirms, trusting single readings, and there every model ends with a worse final pick than a basic scripted strategy. Each failure has its own cause. The over-confirmers run short of new candidates w

---

### [105] The Judge Can Debias Itself: Awareness and Self-Debiasing for Reliable LLM-as-a-Judge

**链接**: https://arxiv.org/abs/2610.24320
**作者**: Youbing Yin, Jingyu Wu, Anoop Kumar, Scott Novotney, Daben Liu, Erin Babinsky
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Judge systems are increasingly employed for automated evaluation, yet remain susceptible to systematic biases that undermine their reliability. We demonstrate that the judge can effectively debias itself without additional training. We propose two lightweight strategies: bias-aware prompting, which explicitly alerts the judge to potential target biases prior to evaluation, and self-debiasing, in which the judge critiques the initial judgment for bias influence. To broaden the evaluation scope, we introduce three novel benchmarks--authority bias (fabricated citations), confidence bias (assertive phrasing), and formatting bias (structured presentation)--and evaluate across seven bias types in total. Across three frontier models, self-debiasing improves performance in 20 out of 21 model-bias combinations with gains up to 15 percentage points, while bias-aware prompting also yields consistent improvements. The recent fine-tuned external critic, however, does not generalize as reli

---

### [106] The Window Is in the Reasoning: When LLM Agents Decide to Follow Prompt Injections

**链接**: https://arxiv.org/abs/2610.24048
**作者**: Haoxuan Jia, Yang Liu, Bin Chong, Yingguang Yang, Yancheng Chen, Jiayu Liang 等 (10 人)
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that read untrusted content can be hijacked by prompt injections. Runtime monitors that try to catch a hijack before the agent acts, and benchmarks that score each task with a single run, share an assumption: whether an agent follows an injection is settled when the injection is read. We test this assumption with branching rollouts that replay an episode exactly up to the step at which the agent reads an injection and then resample the rest of the episode many times, splitting the outcome variance into a part fixed at read time and a part decided afterwards. Across four AgentDojo suites, a Qwen3 agent without thinking is largely decided at read time (0.91 of the outcome variance lies between states); with thinking on, this share drops to 0.62 (95% CI of the drop [-0.38, -0.22]), in the same direction for three attack templates and two success labels. How much is fixed at read time is a property of the model that the same measurement reveals, and thinking lowers the attack su

---

### [107] Who Plans, Who Edits? Verified, Cost-Aware Division of Labor for LLM-Driven Analog Layout Repair

**链接**: https://arxiv.org/abs/2610.24234
**作者**: Xilai Dai, Saeed Mohammadi
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents can repair analog layouts when sign-off tools check every edit, but which model should plan a repair, which should edit it, and at what cost remain open questions. In our tool-grounded repair agent, models only choose bounded layout operators; sign-off tools rerun each task's contract checks after every edit, so failing layouts are never accepted. On layout-versus-schematic (LVS), design-rule checking (DRC), and post-layout repairs of three designs (a production high-voltage digital-to-analog converter (DAC), a 5-V oscillator, and a SKY130 operational transconductance amplifier (OTA)) with six tier-matched models from two vendors, 182 blind runs show that cheap models execute plans but rarely succeed alone (the cheapest model: 1 of 11 runs alone, 16 of 17 under a flagship planner; p < 0.001), cheap planners fail more often, and no fixed assignment is cheapest on every task. We propose a learning controller that selects models for each role and the escalation order

---

### [108] The Missing Compliance Class: LLM Graders That Collapse Jailbreak Success, and a Free Check

**链接**: https://arxiv.org/abs/2610.24872
**作者**: Ruqiya Bin Safi
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jailbreak papers report an attack success rate, the share of responses that deliver the harmful request, and read it as a property of the target model. We hold the target model, the prompts and the responses fixed and change only the grader. Three dense graders of 8B and 9B parameters, from three model families, move compliant responses to the neighbouring class, evasion, instead of scattering them across classes. One of them assigns the compliance label zero times in 900 responses. This class collapse also appears on new harmful requests, on a target model from a third family, and in a held-out 7B grader from a fourth family. Per-class label counts expose it at no cost and without human labels. The collapse decides how the rate behaves under a change of grader. On two corpora of 900 responses and eight graders, the compliance rate differs by a factor of 22 to 25, while the non-refusal rate differs by 18 to 23 percentage points. Without the three collapsing graders, compliance differs 

---

### [109] VeriGRAG: Enhancing LLM-Based Verilog Code Generation with Structure-Aware Soft Prompts

**链接**: https://arxiv.org/abs/2510.15914
**作者**: Jiayu Zhao, Zehua Pei, Zetao Guo, Bei Yu, Song Chen
**来源**: cs.AR cs.AI cs.PL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] Verifying Human-Written Reasoning References

**链接**: https://arxiv.org/abs/2610.24690
**作者**: Ali Ansari, Farhana Ferdousi Liza
**来源**: cs.AI cs.CL cs.LO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating the reasoning of AI systems often relies on human-written reasoning chains as references, yet the logical support for their individual steps is rarely verified. Although prior neuro-symbolic approaches have formalized and checked reasoning, their reported evaluations do not systematically assess whether step conclusions in human-written reference derivations are entailed by their cited premise sets or investigate the sources of failures in those references. To address these limitations, we present a novel reference-centred assessment method for human-written derivations that combines entailment checking against cited premise sets, full-premise rechecking, and failure attribution to examine the reliability of these derivations and their formal representations. We evaluate it on P-FOLIO, using a large language model (LLM) to translate step conclusions into first-order logic (FOL) and the Z3 SMT solver to check entailment. Of 386 derivations examined, 202 (52.3%) meet all our c

---

### [111] MOSAIC: Multi-Objective Search for Allocating Inference Cache Across LLM Decoder Layers

**链接**: https://arxiv.org/abs/2610.25431
**作者**: Sravanth Kodavanti, Manjunath Arveti
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Key-Value (KV) cache is the main memory bottleneck of long-context LLM inference. Token eviction methods such as SnapKV, H2O, AdaKV and L2Norm shrink it, but they give every transformer layer the same budget, although layers differ in which tokens they need. We present MOSAIC, a multi-objective neural architecture search that learns per-layer KV-cache budgets for any eviction method. One search maps the trade-off between average budget and task score; its best allocation transfers to every target budget without further search, and an optional budget-constrained search refines it. Across four eviction methods on Llama-3-8B-Instruct and Mistral-7B-Instruct-v0.2, MOSAIC beats uniform allocation in 146 of 154 (task, method, budget) settings, by up to +48 points on RULER and +11.9 on LongBench (LCC). On both models, it reaches the score of uniform allocation with up to 4x less KV cache (75% smaller). Against EvolKV, MOSAIC explores a ~10^40 x larger search space with 4x fewer evaluation

---

### [112] Persistent Memory and Iterative Improvement in an LLM Agent for Chinese-Character Drawing

**链接**: https://arxiv.org/abs/2610.24090
**作者**: Peilin Wu and Yi-Zhuang You
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Does persistent memory accumulated from previous attempts help an LLM agent solve new problems, and does memory design affect that benefit? We study programmatic Chinese-character drawing across five agent conditions attempting the same 668 items. Accumulated memory produces modest aggregate gains despite substantial growth in the memory stores: free-form notes improve first-attempt success by 4.6 percentage points, while a design combining free-form memory with reusable code improves it by 2.8 points. The two designs do not differ significantly overall, but the code bank shows a suggestive advantage on later, harder items. A separate post-hoc comparison finds a much larger improvement when the code-bank agent receives privileged, target-specific structural supervision. The agent can therefore exploit highly informative structural guidance, although the privileged per-item information does not establish what could have been learned from experience alone. These results suggest that memo

---

### [113] LLM -based program synthesis in correctness-by-construction engineering

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-40121-2_14&hl=zh-CN&sa=X&d=471318525958909365&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVEv3CfYaS_89p53RSRrWg60&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=1&folt=kw-top
**作者**: M Kodetzki, H Grimm, F Demmler, I Schaefer - International Symposium on …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , we compare LLM -based synthesis with the existing approach p roposed by Neumann [34]. Finally, we identify the most reliable LLM and int … To reduce the manual effort for developers, we propose an approach for LLM based synthesis in CbC-based

---

### [114] Text Dominance in Paralinguistic Conflict: Tracing Suppression Through Audio LLM Circuits

**链接**: https://arxiv.org/abs/2610.25599
**作者**: Ankur Banerjee, Vishnu Guntakala, Danity Pike, Advay Roongta, Kevin Yang, Ruizhe Li
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio LLMs deployed in settings such as crisis hotlines and customer support are only useful beyond speech-to-text pipelines if they use acoustic cues rather than the transcript alone. We test whether they prioritise transcript content over paralinguistic cues (emotion, speaker identity, sarcasm) and trace the mechanism when they do. Across six audio LLMs under LISTEN-style conflict conditions, the mean text-dominance rate on mismatched text+audio items is 0.78 (0.86 excluding sarcasm). In the most text-dominant screened model, probing shows speaker identity remains linearly decodable at ceiling at the language model's input, so the failure is not perceptual. Back-patching, reported to repair lexical text dominance, has no measurable effect here; but it also fails on its own source task in our replication (n=300), so we treat its null as uninformative rather than as evidence of non-transfer. Attention knockout partially restores audio-grounded output by blocking the claim from propagat

---

### [115] Is LLM's Moral Decision Compositional?

**链接**: https://arxiv.org/abs/2606.11232
**作者**: Weijia Zhang, Ruiqi Chen, Yunze Xiao, and Weihao Xuan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] Cortex: A Fixed-Point Theory of Governed Coding Agents - Technical Report

**链接**: https://arxiv.org/abs/2610.24255
**作者**: Marius-Constantin Dinu and Florian Zeba
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A coding agent combines a large language model (LLM) with a harness that plans, edits, and executes code. We study Cortex, a supervisory layer for pre-execution governance, requirement tracking, and iterative validation and repair. We formalize requirement closure on a finite lattice. For a fixed requirement set and a sound, monotone validation rule with persistent evidence, exhaustive iteration reaches the least fixed point with no more strict increases than there are requirements. Fair consequence scheduling reaches the same closure. A separate stochastic model bounds expected completion time under a uniform positive-progress assumption. These results depend on their stated assumptions; artifact repair, fallible validation, and finite execution budgets do not satisfy them automatically. We define Gauntlet's trajectory-similarity and build-gated scores, attack-success estimators, Wilson intervals, and case-cluster bootstrap summaries. Effective-feedback accounting counts newly certifi

---

### [117] Can This LLM Annotate My Data? Estimating Zero-Shot LLM Performance

**链接**: https://arxiv.org/abs/2610.24250
**作者**: Tong Lin, Grant Schoenebeck, Sabina Tomkins
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in annotation tasks with varying success. While several studies have demonstrated the opportunities and shortcomings of LLMs for annotation, a critical question remains unanswered: is it possible to predict how well they will perform on a new dataset? To answer this and related questions, we construct two task families which induce 461 text classification datasets. We find that it is possible to predict LLM performance - to a certain degree - and that contrary to other work which highlights the usefulness of LLM verbalizations of self-confidence, internal log-probabilities are the most predictive signal.

---

### [118] Behavioral Probes for Information Flow in LLM Swarms

**链接**: https://arxiv.org/abs/2610.25966
**作者**: Junhui Chen, Yu Zhang, Lantian Li, Dong Wang
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most existing approaches to LLM swarm optimization are utility-driven, focusing on final task utility while leaving the processing, integration, and reliance of information within individual interactions largely implicit. To address this, we study LLM swarm interactions from an information-flow-based view and introduce behavioral probes to quantify information flow patterns. Specifically, we repurpose External Context Score (ECS) and Parametric Knowledge Score (PKS)---originally designed for hallucination analysis---to measure a node's external-context dependence and parametric-knowledge dependence, respectively. Across controlled and realistic swarm settings, we observe consistent patterns: ECS increases with input relevance and distinguishes useful multi-source contributions, while PKS decreases as informative context accumulates. Building on this heuristic interpretation, we demonstrate how these probes can complement utility-driven structure optimization in two controlled applicati

---

### [119] RuPLaR : Efficient Latent Compression of LLM Reasoning Chains with Rule-Based Priors From Multi-Step to One-Step

**链接**: https://arxiv.org/abs/2605.09346
**作者**: Xiaocheng Luo, Kang Wang, Zaifu Zhan, Yuechi Zhou, Xiangyu Duan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] Automated structural testing of LLM-based agents: methods, framework, and case studies

**链接**: https://arxiv.org/abs/2601.18827
**作者**: Jens Kohl, Otto Kruse, Youssef Mostafa, Andre Luckow, Karsten Schroer, Thomas Riedl 等 (10 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [121] From Black Box to Controller: Inference-Time Steering of LLM via Feature Amplification

**链接**: https://arxiv.org/abs/2610.25700
**作者**: Keqi Chen, Zekai Sun, Yuhua Wen, Tianyi Tian, Xinyang Huang, Huijun Lian 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inference-time steering is crucial for deploying Large Language Models (LLMs) in real-world applications, where they must flexibly adjust behavior preferences. For instance, a model should dynamically adjust its caution level based on the risk of the scenario. This requirement introduces a challenge: modulating the intensity of LLM preferences. Prompt engineering can require task-specific prompt design, while fine-tuning requires additional optimization and data. These requirements can make repeated behavioral adjustments costly. To address this, we introduce NeuroSteer, a plug-and-play framework that enables flexible, quantitative adjustment of LLM preferences at inference time. NeuroSteer employs a Sparse Autoencoder (SAE) as its controller. Comparing neuron activation frequencies between positive and negative examples isolates "feature neurons" that correspond to target preferences such as politeness and positive sentiment. During inference, the activations of selected SAE features 

---

### [122] Medical Fine-Tuning Reshapes, Not Reduces, Patient-Facing AI Risk: A Rubric-Based, LLM-Judge Evaluation Framework

**链接**: https://arxiv.org/abs/2610.24807
**作者**: Savan Doshi
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patient-facing medical question answering with large language models (LLMs) is moving from research demonstrations to production deployments, yet evaluation remains anchored on factual correctness. Factuality is necessary but not sufficient: a response can be factually grounded and still issue a directive that, if acted on, would harm the patient. We introduce a risk-sensitive evaluation framework that scores responses by the presence and severity of six categories of risk-bearing language (treatment directives, contraindications, dosage expressions, urgency-triage cues, high-alert medication mentions, and overconfident assertions), anchored on published clinical harm taxonomies. Severity is classified by a three-judge LLM ensemble. We apply this framework to six 7-9B instruction-tuned models, three general (Mistral-7B, Phi-3.5-mini, Llama-3.1-8B) and three medically adapted (BioMistral-7B, OpenBioLLM-Llama3-8B, Med42-Llama3-8B), on 200 real patient questions from the K-QA benchmark. T

---

### [123] SoK: Systematizing LLM Prompt Security: Taxonomies, Datasets, and Unified Evaluation of Attacks and Defenses

**链接**: https://arxiv.org/abs/2510.15476
**作者**: Hanbin Hong, Shuang Wu, Shuya Feng, Nima Naderloui, Shenao Yan, Jingyu Zhang 等 (9 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] Learning Who Talks to Whom: Role-Aware Communication Topology Scheduling for Efficient LLM Multi-Agent Collaboration

**链接**: https://arxiv.org/abs/2610.25851
**作者**: Haibin Li, Wenya Yu, Xuefeng Jiang, Jia Li, Xiao Han, Shuai Su 等 (7 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems driven by large language models (LLMs) rely on structured communication topologies to facilitate information exchange and collaborative reasoning. However, effectively scheduling these topologies to dynamically determine who talks to whom and when to communicate remains a fundamental challenge in balancing collective reasoning performance against exponential token overhead. Existing topology scheduling approaches either enforce static communication graphs that cannot adapt to dynamic problem-solving states, or overlook agent role complementarity while failing to explicitly incorporate the synthesized graph structure into team-level decision evaluation. To tackle these limitations, we propose ACTS, a role-aware adaptive communication topology scheduling framework for efficient LLM multi-agent collaboration. Orchestrated within a Centralized Training with Decentralized Execution (CTDE) paradigm, ACTS introduces a novel dual-attention mechanism. Specifically, a Role-co

---

### [125] UZHCL_for_the_win at Touche: Encoder Fine-Tuning, Synthetic Augmentation, and an Underpowered Encoder-LLM Comparison

**链接**: https://arxiv.org/abs/2610.17077
**作者**: Stylianos Psychias
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] Let Them Sleep: Recursive Self-Pruning Memory for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2610.25561
**作者**: Kargi Chauhan, Sadiba Nusrat Nur, Pratibha Revankar, Kyle Montgomery, Chenguang Wang
**来源**: cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents that run for a long time have a memory problem, and it is not the one most systems optimize for. Storing every trace and retrieving the nearest neighbors works early and quietly stops working later: the store fills up with failures the agent then repeats, and with facts that were true fifty turns ago. RSPM (Recursive Self-Pruning Memory) borrows the fix biology already found. At intervals the agent sleeps. It clusters its recent failures, distills each cluster into a short rule, and deletes the raw episodes it just learned from. Rules decay unless something reinforces them, and rules that recur across many contexts get promoted into general ones. We tested this on three settings with little in common: a difficulty-calibrated SWE-bench simulation, temporal consistency across 12 conversational benchmarks, and long-horizon QA on LoCoMo-10. All three improve, by 9.1, 11.9, and 7.6 points respectively. More interestingly, the two studies that instrument the store itself converge on n

---

### [127] Accelerated Drift of Scientific Prose in the LLM Era: Evidence from an Interrupted Time-Series Analysis

**链接**: https://arxiv.org/abs/2610.26008
**作者**: Hanna Hubarava, Benjamin V. Ineichen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Every scientific text is embedded in the writing norms of its time: it reflects earlier publications while also shaping the texts that follow. The growing use of LLM-based writing tools introduces a new factor in this evolving system, but the linguistic changes coinciding with their emergence remain insufficiently understood. We investigate whether the trajectories of scientific-preprint writing changed in rate or direction after conversational LLMs became publicly accessible, using the release of ChatGPT in November 2022 as the observational breakpoint. We compare pre- and post-2022 trajectories across vocabulary, punctuation, readability, and syntax in abstracts from arXiv's artificial intelligence, statistics, and quantitative biology categories and from medRxiv. Using interrupted time-series regression, we find substantial post-2022 changes across multiple feature families and research domains, including increases in average word length, reduced formula-based readability, and decli

---

### [128] SteadyThought: Mitigating LLM Under-Thinking via Thought-Level Preference Optimization

**链接**: https://arxiv.org/abs/2610.25045
**作者**: Zhenyue Peng, Lin Yang, Jie Wang, Xiaoqi Ni, Hanzhu Chen, Xize Liang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Flexible switching between reasoning trajectories (i.e., thought switching) has significantly enhanced the reasoning capabilities of Large Reasoning Models (LRMs). However, existing models often switch excessively yet fail to sustain promising reasoning thoughts, a phenomenon termed "under-thinking". While recent efforts suppress switching to mitigate this, such over-correction may discard valuable trajectories. To address this challenge, we propose Steady Thought (ST), a novel thought-level preference optimization framework. ST formalizes under-thinking as a preference issue at switching points, forcing single-path continuations from identified points to yield high-quality reasoning. Then, ST performs thought-level preference optimization by treating the newly generated response as preferred and the original one as dis-preferred. Experiments across multiple models and datasets show that ST effectively reduces token consumption, achieving reductions of up to 63.8%, while maintaining st

---

### [129] HABIT-Bench: Evaluating Habit Induction from Longitudinal Weak Evidence in Agent Memory

**链接**: https://arxiv.org/abs/2610.24520
**作者**: Junming Zhang, Rubin Wei, Xu Cheng, Hao Sun, Ruoxi Cheng, Xiquan Wang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In long-term interactions with large language model (LLM) agents, users reveal habits through their choices and actions. These habits capture implicit user information that agents must infer across conversations. However, individual observations may provide only partial evidence about a habit or when it applies. Retaining past interactions alone does not ensure that agents can infer habits and apply them appropriately. We introduce HABIT-Bench to evaluate how well agent memory systems infer habits from weak evidence and apply them to later requests. We construct synthetic user histories from task-oriented dialogue data and controlled habit graphs. The histories span hundreds of sessions across food, finance, software, and travel. Four-choice tasks assess agents' ability to infer user habits and apply them appropriately. They include temporary exceptions, changes in habits, and suggestions that users have not accepted. Sampled tasks undergo independent human review. We evaluate eight me

---

### [130] BrandEval: A Two-Track Multi-Agent Benchmark for Risk-Sensitive LLM Crisis Communication

**链接**: https://arxiv.org/abs/2610.25208
**作者**: Haotian Gan, Weidong Tang, Hanbin Sun, Yi Luo, Xintian Li, Jiayong Wang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating LLMs for crisis communication requires more than judging isolated responses, because public feedback and competitor actions can reshape trust over time. Existing benchmarks remain largely static and single-turn, offering limited evidence about long-horizon risk-sensitive communication. We introduce \textbf{BrandEval}, a two-track benchmark for product-crisis communication, focusing on public brand responses to product-related safety, quality, service, and trust incidents. BrandEval-Static evaluates stakeholder-aware strategic analysis, while BrandEval-Dynamic stress-tests response policies in \textbf{BrandPolis}, a controlled multi-agent sandbox with consumer feedback, competitor responses, and trust-risk trajectories. We also construct \textbf{BrandSRD}, a Chinese crisis-response dataset, and instantiate a reference Strategic Agent using \textbf{Strategic Rationale (SR)}. Across proprietary and open-source models, we find that static strategic quality is informative but inc

---

### [131] The One-Pixel of Reasoning: One Truthful Relation Is Enough to Mislead LLM Agents

**链接**: https://arxiv.org/abs/2610.24873
**作者**: Jinwei Hu, Youcheng Sun, Yi Dong, Xiaowei Huang
**来源**: cs.AI cs.CL cs.CR cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can one sentence manipulate an agent's belief by targeting a single implicit warrant linking evidence to a conclusion? In this paper, we introduce the one-relation attack (ORA), a novel cognitive attack on this inferential relation. ORA localizes a critical implicit warrant and performs a one-relation intervention using a single source-grounded sentence that qualifies this warrant and steers the agent toward an incorrect belief. Across eighteen models on biomedical inference and vulnerability detection, best-of-$10 attacks overturn initially correct answers at mean rates of 54.9% for proprietary and 80.0% for open-weight models. Attacks also transfer without victim feedback, and paired controls support the roles of targeting and qualification. Moreover, successful sentences can pass source-support checks and evade identification, and multi-agent debate raises team error from 50.0% to 59.5% in our balanced stress test. These findings establish implicit warrants as a cognitive attack sur

---

### [132] Not All Flips Are Conformity: Decomposing Stance Convergence in Multi-Agent LLM Debate

**链接**: https://arxiv.org/abs/2606.00820
**作者**: Xiqi Hao, Zengqing Wu, Yu-Xuan Qiu, Chuan Xiao, Ruiqi Xu, Shuyuan Zheng 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] Anatomy of Off-Policy Policy Gradient: Importance Sampling, KL Regularization, and Baselines

**链接**: https://arxiv.org/abs/2610.25725
**作者**: Haoqun Cao, Yurun Yuan, Tengyang Xie
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning has become a central tool for large language model (LLM) post-training, where policy gradient methods are routinely deployed off-policy, even though vanilla policy gradient assumes on-policy sampling. We study when such off-policy deployment is justified, and what roles its core ingredients, including importance sampling, KL regularization, and baselines, play in handling the resulting distribution shift. We show that for a general class of off-policy policy gradient updates, consistency, in the sense that the optimal policy remains a stationary point, requires one of two structures at the optimal policy: trajectory-level importance weighting, which suffers from the well-known curse of horizon, or KL regularization with a baseline equal to the optimal soft value, instantiated by the grouped mean. Focusing on the KL route, we identify it with the group-relative policy gradient (GRPG) update, establish an equivalence to a trajectory-level Bellman residual minimizat

---

### [134] LLM Agents as Suppliers of Physical System Models: Calibration and Acceptance in Modelica

**链接**: https://arxiv.org/abs/2610.25019
**作者**: J\"org Frochte, Herbert Schmidt
**来源**: cs.LG cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To procure a model of a device, a client hands a supplier a description, sometimes with recorded data or a target response, and accepts the model against this handover. We let LLM coding agents act as the supplier on handovers with data, building Modelica models from library components for four simulated systems and a real switching magnet, and ask what acceptance certifies. Several agents reach the noise floor, but a handover admits a set of models: the description leaves parts of the structure open, and the data narrow it only to the agreed accuracy. We therefore accept by membership in this set, not by matching one reference, and add layers above behaviour: a physical invariant exposes an energy-creating model at the noise floor. Interpretability becomes a property of the delivered model, tested on a variant, read where none exists and shaped through the handover. Most failures are fits delivered with a systematic residual on their own fitting data, where the handover left open how 

---

### [135] REFLEX: Reflective Evolution from LLM Experience

**链接**: https://arxiv.org/abs/2606.16496
**作者**: Pan Wang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [136] An important Bottleneck in LLM Optimizers: Principle-Level Local Optima

**链接**: https://arxiv.org/abs/2610.24291
**作者**: Nian Ran, Tianhe Jia, Zhengyang Mu, Yue Wang, Sebastian Brulin, Markus Olhofer 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feedback-driven LLM optimizers are increasingly used for evolutionary search, Bayesian optimization, heuristic design, and scientific discovery. Yet rapid initial gains often give way to prolonged plateaus despite substantial remaining evaluation budgets. We investigate \emph{principle-level search collapse}, where an optimizer's search becomes confined to a narrow set of design principles, even though it may continue to generate distinct candidates and achieve small improvements. We assemble a diagnostic benchmark spanning molecular optimization, network sentinel-node selection, and GPU-kernel optimization, and introduce a decision-tree protocol combining principle narrowing, prolonged performance plateaus, and gaps to attainable reference solutions. Across 161 assessable runs on the three problem domains, 78.3\% receive support for collapse, including 55.3\% with strong support. Candidate-level variation can nevertheless conceal restricted search at the principle level. We then test 

---

### [137] LLM-Driven Autonomous Vehicles Can Inherit Human Driver Biases in Pedestrian Yielding: Results and Implications From a New Benchmark

**链接**: https://arxiv.org/abs/2609.00192
**作者**: Irem Yoldas, Jie Zhang, Odinaldo Rodrigues, Martim Brand\~ao
**来源**: cs.AI cs.CL cs.CV cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [138] Where Is the "Self" of a Large Language Model? -- From Self-Index to Self-Reference

**链接**: https://arxiv.org/abs/2610.16717
**作者**: Yuchen Li, Xintong Li, Zongqi Fan, Ken-tye Yong, Nguyen H. Tran
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [139] ProbePO: Sparse Probes, Redistributed Credit for Critic-Free LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.24515
**作者**: Diyi Hu, Ruizhong Qiu, Lin Qiu, Hanghang Tong, Hanqing Zeng
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning from verifiable rewards assigns one terminal reward to an entire reasoning trajectory, obscuring how individual reasoning steps contributed to the outcome. GRPO broadcasts a group-normalized advantage to every response token, while finer-grained approaches often rely on dense auxiliary rollouts or branching schemes that can also alter the data used for policy updates. We cast the missing middle as budgeted measurement: with a limited rollout budget, which partial solutions should be evaluated, and how should their value estimates refine credit? ProbePO selects partial-solution states with a reward-free uncertainty score and estimates their expected verifier rewards under a capped continuation budget. ProbePO redistributes, rather than replaces, GRPO's trajectory-level advantage across tokens while preserving each trajectory's mean token-level advantage; probe continuations serve only as measurements. Across three DeepSeekMath and Qwen-family models spanning 1.5B-

---

### [140] LLM ‐Assisted Design of Ultralow‐κ Chalcogenides

**链接**: https://scholar.google.com/scholar_url?url=https://pmc.ncbi.nlm.nih.gov/articles/PMC13672694/&hl=zh-CN&sa=X&d=9335934151196119935&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVGs8EDun-As6Qfpneezu3x_&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=2&folt=kw-top
**作者**: Y Liu, C Jia, Y Hao, X Li, Y Wang, A Oganov 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Here, we present an LLM ‐assisted design framework that orchestrates LLM ‐assisted candidate prioritization with high‐throughput, physics… , and κ evaluation rather than by the LLM . In this pipeline, the top 10 compositions selected after qualitative

---

### [141] Can LLM Agents Resolve Service Failures? Simulating Multi-Turn Complaint Handling under Information Asymmetry

**链接**: https://arxiv.org/abs/2610.24733
**作者**: Wailing Ng, Mengze Hong, Chen Jason Zhang, Shiqi Fan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are widely adopted in service chatbots for rule-guided support and information access, yet emotionally demanding complaint handling still relies heavily on human agents. We introduce ServiceBench, to our knowledge the first benchmark dedicated to complaint handling, with 2,500 scenarios spanning 184 complaint categories and five service industries. We propose Asymmetric Progressive Complaint Simulation (APCS) to simulate realistic complaint handling, together with a justice-based evaluation framework. Our experiments reveal that even capable LLM agents struggle to handle complaints effectively. They lack the ability to proactively gather information and strategically guide conversations toward resolution, often resorting to premature compensation. We further show that targeted post-training with SFT and DPO substantially improves these capabilities, enabling a smaller model to match or surpass much larger models on several outcomes.

---

### [142] From Outcomes to Components: A Counterfactual Evaluation Framework for LLM-Proposed Repairs

**链接**: https://arxiv.org/abs/2610.26650
**作者**: Hengyu Ye, Songhua Hu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM-generated repair action specifies which records to change and by how much. A failed action may still contain a useful target set or numerical update, depending on how the two are paired. We evaluate this problem in traffic networks and databases, where aggregate observations obscure the records that need correction. We examine the pairings by executing each combination from the same initial state, using a reference action that restores the affected records. In 76 of 114 traffic actions, the gain from correcting both parts exceeds the sum of the gains from correcting each part alone. Six of these actions become worse after either correction alone, but improve when both parts are corrected. In database repair, replacing only the proposed update with the reference update worsens 17 of 108 model actions, all of which select unaffected records. We also test whether parts of two proposals can be reused. On held-out observations, selecting among the proposals and their recombined targe

---

### [143] Lmda: Llm -guided marginal distribution alignment for open-set active learning

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11739726/&hl=zh-CN&sa=X&d=5269545882642890994&ei=l_vWavAz1bbqtA-czuCIDQ&scisig=ACTRDVEYAIQMxwG8rPv1k0p9va-5&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=0&folt=kw-top
**作者**: J Tang, L Li, B Zhang, Q Huang - Chinese Journal of Electronics, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Based on the above analysis, this paper proposes an LLM -guided marginal distribution alignment openset active learning framework (… First, we propose a zero-shot LLM -guided data purification module to probe the data purity. We generate pseudoOOD

---

### [144] When to Stop Asking: Factor Coverage Bias and LLM Determinability Judgments with Underspecified Information in Medicine

**链接**: https://arxiv.org/abs/2610.25819
**作者**: Yusuke Watanabe, Yohei Kobashi, Taisei Tosaki, Takeshi Kojima, Yusuke Iwasawa, Yasushi Okuno 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical decision-making often begins with underspecified information and requires not only gathering missing information but also knowing when to stop. This calls for judging determinability (whether the available information is sufficient for a decision) by considering whether missing information could change the conclusion, not simply the amount of available decision-relevant information. Reliance on this amount as a cue for determinability, which we term \textit{factor coverage bias}, could undermine the trustworthiness of large language models (LLMs) through premature conclusions or excessive information gathering, such as unnecessary invasive tests. Yet whether LLMs exhibit this bias remains insufficiently studied. To address this gap, we construct a controlled pairwise benchmark in which LLMs identify the determinable case within each determinable--undeterminable pair. We add a decision-relevant factor to either side while keeping each case's determinability unchanged, and simil

---

### [145] Learn the Interface, Not the Implementation: Output Representation Dominates Training Regime in LLM-Based RTL Generation

**链接**: https://arxiv.org/abs/2610.25881
**作者**: Siddharth Patel, Vikram Singh, Siddharth Savyasachi Malu, Rohit Singh
**来源**: cs.LG cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-language-model register-transfer-level (RTL) generation has concentrated on how to train the model: fine-tuning, continued pre-training, and reinforcement learning from a verifier. We argue this is the second-order question. On a bounded, formally specifiable task of generating single-error-correcting, double-error-detecting (SECDED) ECC memory wrappers, we hold the task, data, and correctness oracle fixed and vary two axes independently: the training regime (seven settings) and the output representation (four levels, from fully expanded flat Verilog to an eight-field configuration expanded by a deterministic generator). Because a reference generator exists, correctness is decided by formal equivalence over a design space of approximately ten million points, rather than sampled from a hand-written testbench. Two results follow. First, representation dominates: every representation close to raw RTL reaches a pass rate of at most 0.17, while the configuration reaches 0.83 with no t

---

### [146] FlashMap: Flow Map Speculative Decoding

**链接**: https://arxiv.org/abs/2610.24365
**作者**: Jeff Shen, Zhejian Zhou, Ryan Lee, Jonathan May, Shirley Ho
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model (LLM) inference by using a lightweight drafter to propose a block of tokens that the target model verifies in one parallel pass. Autoregressive drafters generate this block one token at a time, whereas block diffusion drafters such as DFlash generate it in one pass, making drafting faster. However, these diffusion drafters predict each token independently, ignoring dependencies between tokens in the block. We introduce FlashMap, a continuous flow drafter that conditions a flow map language model on the target model's hidden states and generates the whole block in one forward pass while capturing inter-token dependencies. On Qwen3-8B, FlashMap is faster than a matched DFlash baseline on every benchmark, with 7% higher average speedup and up to 6.1x lossless acceleration.

---

### [147] Requests of a Feather Must Flock Together: Batch Size vs. Prefix Homogeneity in LLM Inference

**链接**: https://arxiv.org/abs/2605.06046
**作者**: Saksham Rathi, Preeti, Mythili Vutukuru
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] Promptile: Recovering and Reusing Prompting Strategies from LLM Interaction Histories

**链接**: https://arxiv.org/abs/2610.26485
**作者**: Qingyang Wan, Chang Liu, Zhoutong Ye, Chengwen Zhang, Yanru Qian, Zhike Wang 等 (9 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As people use large language models (LLMs) over time, they develop their own ways of prompting to achieve desired results. These useful experiences often remain scattered and unorganized across conversations. Yet existing personalization approaches primarily capture user preferences or explicitly defined workflows. Through a formative study, we found that users develop prompting strategies that range from implicit instructions to explicit templates from these experiences. We further find that interaction behaviors provide evidence for these strategies, which can be decomposed and recombined for reuse across tasks. Building on these findings, we present Promptile, a framework that identifies and validates users' prompting strategies from interaction histories. Promptile organizes these strategies into reusable components that can be retrieved, combined, and adapted to users' current tasks. Our evaluation shows that Promptile accurately recovers and reuses these strategies, better aligni

---

### [149] Consistent LLM Call Handling Across Java Frameworks: A Reference Implementation and Benchmark

**链接**: https://arxiv.org/abs/2610.25480
**作者**: Oleksandr Klymenko
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Java applications reach large language models (LLMs) through an integration framework, and rely on it to handle a failing provider: to retry what can be retried and nothing else, to wait as long as the provider asks, never to present a truncated answer as complete, and to record each failure in the application's metrics. We state these expectations as a six-clause reliability contract and measure Spring AI 2.0.1 and LangChain4j 1.21.0 against it with a scripted OpenAI-compatible provider: fifteen failure scenarios, synchronous and streaming, three repetitions. LangChain4j meets it in 47 of 77 applicable cases with its defaults and in 51 of 83 when configured explicitly, Spring AI in 72 of 77 and 76 of 83; both deliver a stream that ended without its terminator as a complete answer. We then place one implementation of the contract beneath both frameworks, at the HTTP boundary - an OkHttp interceptor for Spring AI, an HttpClient for LangChain4j, and a java.net.http transport for code wit

---

### [150] GardenBench: A lightweight, daily evaluation of LLM capabilities

**链接**: https://arxiv.org/abs/2610.23866
**作者**: Benedict Cummins-Mburu and Mariana Garcia Mejia and Oscar Heath and Sabrina Kreyzerman and Ellie Murray and Arusan Surendiran and Rohan Alexander
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce GardenBench, a benchmark with 11 test suites that evaluate the capabilities of Large Language Models (LLMs) across a range of tasks. By systematically prompting LLMs with various lightweight queries, we document day-to-day changes in model performance, including run costs and times, that other benchmarks miss. This allows us to compare the accuracy and features of responses across model providers and versions. We account for daily variations in model accuracy, capturing both model progress and degradation, for instance, when a model is changed post-deployment or when a new model is released. We base our evaluation on general-use tasks and make our results publicly accessible via a live dashboard, diversifying existing approaches to LLM testing. Our main contribution is an innovative, lightweight, and inexpensive benchmark, designed to be consumer-facing and for everyday tasks.

---

### [151] First-Order LoRA Training with Phone NPUs

**链接**: https://arxiv.org/abs/2610.24816
**作者**: Xu Zheng, Wei Cheng, Zhuomin Chen, Dongkuan Xu, Mo Sha, Jingchao Ni 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-device fine-tuning lets a large language model (LLM) learn from its user's private data without uploading it. Low-rank adaptation (LoRA) reduces the trainable parameters, but each first-order training step still multiplies by the frozen base-model weights during the forward pass, activation recomputation, and input-gradient computation. A phone's neural processing unit (NPU) already holds these weights for inference; using it for training also requires computing input gradients, which its inference interface does not support. We present a system that runs all three frozen-weight products on the NPU while keeping the training graph, adapters, and optimizer on the CPU. Its input-gradient kernels reuse the resident weight tiles and the forward dequantizer, avoiding a transposed weight copy and ensuring forward and backward use the same effective weights. To preserve usable gradients, the system selects precision by gradient sensitivity and applies a per-row range guard for half-precisi

---

### [152] Keep the Lineages Alive: Diversity-Preserving SMC for Diffusion LLM Decoding

**链接**: https://arxiv.org/abs/2610.25932
**作者**: Minoo Ahmadi, Seyedarmin Azizi, Mehdi Kamal, Massoud Pedram
**来源**: cs.LG cs.AI cs.CL stat.AP stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Inference-time sequential Monte Carlo (SMC) decoding can improve the reasoning accuracy of masked diffusion language models (diffusion LLMs) without post-training by resampling a population of partial generations according to a reward. Its effectiveness therefore depends on the resampling step, which must concentrate computation on promising candidates while retaining enough diversity to explore alternative reasoning paths. The reward can be internal, the decoder's own confidence on the committed prefix, or external, a process reward model scoring that prefix. Under either reward, multinomial resampling can disrupt this balance by duplicating high-weight particles and discarding lineages that may still reach a correct solution. The effective sample size (ESS) does not register this loss: multinomial resampling resets it to its maximum even as distinct lineages disappear. To retain such lineages, we introduce lineage-preserving SMC (LP-SMC), which combines Chopthin resampling with an in

---

### [153] Pronouncing Hard Words: Phoneme Adaptation of a Pretrained Conversational Text to Speech Model

**链接**: https://arxiv.org/abs/2610.24164
**作者**: Yashish M. Siriwardena, Dinesh K. Gnanasekaran, Tanmay Laud, Shinji Watanabe, Subhabrata Mukherjee, Shanil Puri
**来源**: cs.CL eess.AS
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Voice agents built as cascaded automatic speech recognition (ASR)->large language model (LLM)-> text-to-speech (TTS) pipelines increasingly rely on conversational TTS: streaming, context conditioned models that adapt delivery to dialogue history. Such models are natural and expressive but offer little explicit control over how rare, trust-critical drug names are pronounced, because these entities are too infrequent, and their vocabulary too fast-growing, to be covered by any amount of pre-, mid-, or post-training. We retrofit phoneme controllability onto a pretrained conversational TTS model without any pre/mid-training, using an ARPAbet vocabulary exten-sion, continued phoneme-augmented supervised fine-tuning (SFT), and a training-free inference-time acoustic-biasing step. On a 7,500 clip clinical drug-pronunciation evaluation, our model raises strict Gemini-judged correctness from 54.6% (no phoneme augmentation) to 90.7%, outperforming every conversational and stateless TTS baseline 

---

### [154] Distilling LLM Feedback for Lean Theorem Proving

**链接**: https://arxiv.org/abs/2605.30861
**作者**: Gaetan Narozniak, G\'erard Biau, R\'emi Munos, Ahmad Rammal, Pierre Marion
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [155] Safety Mid-Training: Internalizing LLM Safety as a Foundational Capability

**链接**: https://arxiv.org/abs/2610.26809
**作者**: Zhengyue Zhao, Liwei Jiang, Yejin Choi, Chaowei Xiao1
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety alignment for large language models (LLMs) is primarily performed during post-training, while recent work has also begun incorporating safety data into pre-training. Yet safety can degrade when later training no longer includes safety data, and gains in safety often come at the cost of general capability. This tension suggests that safety and general reasoning should not be treated as separate training goals. We instead view safety as an LLM capability that can be learned through a reasoning structure shared with general tasks. Both require the model to understand intent or task goals, apply relevant knowledge, and reason about potential consequences. We introduce safety mid-training, a stage between pre-training and post-training that jointly develops safety and general reasoning through this shared structure. Given safety and utility prompts, the base model generates structured documents and reasoning traces that are then used for mid-training. Safety mid-training reduces aver

---

### [156] MisleadQA: Diagnosing LLM Failures under Misleading Context

**链接**: https://arxiv.org/abs/2610.24851
**作者**: Hui Wang, Bohao Chu, Qianli Wang, Shuning Zhang, Norbert Fuhr
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are widely used to answer questions from retrieved or user-provided context. However, provided context can be factually true yet out-of-scope, describing a different entity, time, or location from the one the question targets, and still lead models to a wrong answer. Prior work has mainly studied factually false or irrelevant context. It remains unclear whether such out-of-scope context misleads models as much as false context, and whether adding gold context prevents models from being misled by either. We introduce **MisleadQA**, a diagnostic dataset of multiple-choice questions with an abstention option. Each question pairs gold context (G) with true but out-of-scope context (S) and false but in-scope context (F) supporting the same wrong answer. We evaluate six open-weight LLMs. On questions they answer correctly without context, providing S alone leads them to switch to this wrong answer in 29.3% of cases, and providing F alone does so in 75.4%. Adding 

---

### [157] Can LLM Agents Respond to Disasters? Benchmarking Heterogeneous Geospatial Reasoning in Emergency Operations

**链接**: https://arxiv.org/abs/2605.11633
**作者**: Junjue Wang, Weihao Xuan, Heli Qi, Pengyu Dai, Kunyi Liu, Hongruixuan Chen 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [158] SPAR: Structural Pruning and Action Recovery for Vision-Language-Action Models

**链接**: https://arxiv.org/abs/2610.26487
**作者**: Shenli Zheng, Zhou Fang, Yuan Du, Yijiang Liu, Li Du
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The limited onboard computing resources of robots make the inference demands of vision-language-action (VLA) models costly to accommodate. Reducing these demands through aggressive compression, however, can degrade manipulation performance beyond what supervised fine-tuning alone recovers. We present SPAR (Structural Pruning and Action Recovery), which simultaneously prunes the hidden and feed-forward intermediate dimensions of the large language model (LLM) backbone through pruning-aware tuning, then applies reinforcement learning (RL) to recover policy performance. Applied to $\pi_{0.5}$, SPAR reduces the language backbone from 2.34B to 0.09B parameters and the full model from 3.37B to 1.12B, removing approximately 96% and 67% of their parameters, respectively. At this compression level, RL raises average success across the four LIBERO suites from 84.55% to 93.45%, an 8.90-percentage-point gain. The compressed policy achieves a $1.98\times$ full-policy inference speedup over the unpr

---

### [159] LLM Trojans that Increase Response Lengths and Cost

**链接**: https://arxiv.org/abs/2610.24784
**作者**: Zhengxing Li, Guangmingmei Yang, Nader Alfares, David J. Miller, George Kesidis
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Management of the token-based costs of using LLMs has emerged as a significant problem. Some frontier-model providers charge five times per response token than per prompt token, while others offer prefilling discounts for prompt tokens. In this paper, we devise a defense against a new data-poisoning attack that plants a Trojan which increases the length of the response (and hence the cost to the user) when its trigger is present in the prompt. In particular, we demonstrate how a subtle Trojan may trigger on semantically similar instructions of an instruction fine-tuned LLM.

---

### [160] QuasiLeak-Bench: Evaluating LLM-Based Privacy Detectors on Policy-Conditioned Quasi-Evidence Group Recovery

**链接**: https://arxiv.org/abs/2610.21333
**作者**: Yufan Zhu, Yangfan Jiang, Yang Fei, Shizheng Hou, Shubhankar Mohapatra, Xiaokui Xiao
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [161] CADS: Measuring the Incremental Contribution of LLM Proposers in Sequential Biological Screens

**链接**: https://arxiv.org/abs/2610.24597
**作者**: Guanxing Chen, Nihui Shao, Haohuai He, Zhenchao Tang, Pengwei Hu, Zhi-An Huang
**来源**: cs.AI q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used to guide sequential biological screens, yet standard evaluations rely on raw hit counts that conflate a proposer's value with the discovery capacity of the underlying algorithmic harness. Adaptive sampling and corrupted experimental readouts also leave standard feedback comparisons without a false-discovery guarantee. We present Certified Agentic Discovery Screens (CADS), an error-controlled measurement framework that quantifies a proposer's incremental value against an identical LLM-free loop. By integrating capped likelihood-ratio bounds, e-processes, and complete-family e-BH, CADS controls the terminal false discovery rate under the stated null and corruption conditions despite arbitrary dependence, adaptive sampling, and optional stopping. In DepMap-backed simulations, CADS exposes two evaluation artifacts: the LLM-free harness alone clears the feedback gate, and raw origin counts overstate LLM contributions because LLM picks displace fal

---

### [162] Which Model for Which Role? Cost-Efficient Pareto Recommendation for LLM Agentic Workflows

**链接**: https://arxiv.org/abs/2610.26676
**作者**: Qian Xie, Wenyue Hua, Yueli He, Sripad Karne, Armaan Agrawal, Nikos Pagonas 等 (10 人)
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agentic workflows increasingly employ different models for specialized roles. Users may prefer different trade-offs between task quality and deployment cost, sometimes also considering latency. Finding good assignments incurs a separate search cost from evaluating multiple candidates. We introduce Cost-Coupled Gittins (CC-Gittins), a multi-objective extension of single-objective cost-aware Gittins search for Pareto recommendation. It exploits the coupling between evaluation and deployment costs: assignments that cost more to deploy also cost more to evaluate. The search alternates between seeking higher quality and lower deployment cost, reusing each evaluation to inform both searches. After each batch, CC-Gittins recommends assignments that are nondominated under uncertainty-adjusted estimates of quality and deployment cost. We evaluate CC-Gittins on eight quality--cost matrices from workflows with two to five roles and up to 1,681 candidate assignments. We also evaluate the metho

---

### [163] COPEX: Benchmarking LLM Robustness to Adversarial Context Across Model Context Protocol (MCP) Layers

**链接**: https://arxiv.org/abs/2610.04378
**作者**: Nahom Birhan, Mehrdad Rostamzadeh, Sidhant Narula, Mahmoud Nazzal, Mohammad Ghasemigol, Daniel Takabi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [164] Same Simulation, Different Evidence: Where Retrieved Tool Output Costs LLM Agents Accuracy

**链接**: https://arxiv.org/abs/2610.26836
**作者**: Ke Zhang, Sahchit Chundur, Jerry Peprah Owusu, Mohammad Javad Abdolhosseini Qomi, Maziar Raissi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that compute the right answer can still answer wrongly. Agent harnesses increasingly keep long tool outputs out of the context window, saving them to files that the agent searches or reads on demand. We ask where this costs accuracy with a real scientific tool: PHREEQC, a widely used geochemistry simulator from the USGS, whose reports reach 846.8k characters and whose determinism lets every printed value be traced. Agents use it to answer 158 execution-verified multiple-choice items. When agents read the simulator's report through a section index rather than in context, GPT-5.1 and GPT-5.2 lose 11.3 and 7.9 points of accuracy, while Claude Opus 4.6 and Claude Sonnet 4.6 show no detectable cost. Re-running all 11,007 logged simulator calls shows that both GPT models compute the keyed value about as often as before; what changes is the evidence they answer from. Under retrieval they often skip the report, answer from their own higher-precision output files, and misround to a n

---

### [165] LoopHIL: Looping Hardware into LLM-assisted Agents for Wireless Embedded Systems

**链接**: https://arxiv.org/abs/2610.24231
**作者**: Dhairya Shah, Spanddhana Sara, Savitha Viswanadh Kandala, Ambuj Varshney
**来源**: cs.NI cs.AI cs.AR cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are widely used for software development and debugging, but their adoption in embedded systems, especially for wireless tasks, remains limited. This is because embedded development requires hardware-in-the-loop testing. Agents cannot directly observe the spectrum, probe pins, or measure power, so they cannot verify wireless link functionality; currently, human engineers perform this verification. We systematically evaluate whether LLM agents can establish wireless links when provided with hardware access. We introduce LoopHIL, a framework that lets agents control a multi-device RF bench, monitor it with a spectrum analyzer, logic analyzer, and energy meter, and validate links against a verification ladder, all within code-enforced safety limits. Across four increasingly complex tasks, from generating a carrier to backscatter decoding by a commercial receiver, and using six models from two vendors, hardware-in-the-loop increases task completion rates from 54% to 79% and from 

---

### [166] T-MUON: Tensorizing Muon via t-SVD for Large Language Model Pre-training

**链接**: https://arxiv.org/abs/2610.24938
**作者**: Dongyang Li, Mingsong Yan, Zheng Zhang, Sui Tang
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Muon has recently emerged as a strong optimizer for large language model pretraining by exploiting matrix structure through polar orthogonalization. However, it processes each parameter matrix independently, whereas recent tensor-aware extensions of Muon jointly update groups of eligible matrix parameters through matrix unfoldings. In contrast, we propose T-MUON, a t-SVD-based generalization that groups structurally related Transformer gradients into third-order tensors and defines the corresponding Muon-style update directly through the $M$-transform. We show that the exact T-MUON update is a steepest-descent direction under the $\star_M$-spectral norm and establish a convergence guarantee. Across GPT-2-style and LLaMA-style models from 51M to 1.3B parameters trained on FineWeb and FineWeb-Edu, head-wise T-MUON with the identity transform consistently achieves lower validation perplexity than AdamW, Muon, and variants using DFT, DCT, or DST transforms. These gains persist in additiona

---

### [167] VReAct: Verification as an Architectural Layer for LLM Agents: A V-Model Design, and a Pilot Study of Its Deterministic Core

**链接**: https://arxiv.org/abs/2609.31937
**作者**: Ali Afoud, Jie JW Wu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] Sequential Behavioral Watermarking for LLM Agents

**链接**: https://arxiv.org/abs/2605.11036
**作者**: Hyeseon An, Shinwoo Park, Dongsu Kim, Yo-Sub Han
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [169] Bellman Language Models: Solving the Recurring Decisions of LLM Agents

**链接**: https://arxiv.org/abs/2610.24871
**作者**: Adarsh Vatsa, William Eiers
**来源**: cs.AI cs.CL cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A general observation in agentic workflows, especially bounded ones, is that the decision space of the LLM, when we separate a decision from generation, starts approaching saturation: the agent meets the same states again and again, and after enough conversations it stops meeting new ones. LLMs generally don't treat these decisions as an optimization problem and instead re-derive them from their context/prompt on every turn. We show that treating decision making within reasonable bounds as an optimization problem, solving it once, and reusing the solved decisions can often make an agent faster, cheaper and more reliable. Our approach, which we call Discretize, Then Decide, starts from data such as the workflow's own logs or, when none exists, runs of the LLM agent itself. It reads each conversation into discrete states and estimates the probability of each outcome and the cost of each move, until no new states appear and the probabilities stop changing. It then solves the resulting Mar

---

### [170] Service-Induced Congestion in Memory-Constrained LLM Serving

**链接**: https://arxiv.org/abs/2606.15555
**作者**: Ruicheng Ao, Jing Dong, Gan Luo, and David Simchi-Levi
**来源**: math.OC cs.AI cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] When Entropy Is Not Enough: Reclaiming Lost Semantics in LLM Output Length Prediction

**链接**: https://arxiv.org/abs/2608.15592
**作者**: Feiyang Ren, Shengtao Wen, Yu Tian, Yuanning Cui, Xiaofeng Cao, Jiangchao Yao 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [172] LoGRA: Scaling LLM Reinforcement Learning with Low-Rank Gradient Sketches

**链接**: https://arxiv.org/abs/2610.06647
**作者**: Shaokun Zhang, Yifan Zhang, Jian Hu, Yueying Li, Hao Zhang, Binfeng Xu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [173] Unified Multiparadigm Fusion Intelligence for Rare Disease Diagnosis

**链接**: https://arxiv.org/abs/2610.24024
**作者**: Jian Yang, Peiling Liu, Songda Li, Yu Cao, Yuqing Feng, Lan Yu 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rare diseases (RDs) affect an estimated 300 million people globally, leaving patients to navigate a protracted diagnostic odyssey constrained by clinical scarcity and fragmented medical knowledge. Artificial intelligence (AI) has progressively advanced RD diagnostics, from symbolic methods and deep learning to large language model (LLM)-based systems. However, each paradigm carries structural limitations: symbolic methods are bounded by knowledge completeness, neural models sacrifice interpretability, and LLM-based systems are vulnerable to evaluation biases like data leakage. In this study, we introduce FusionRare, a unified multiparadigm fusion framework integrating knowledge-driven symbolic reasoning, deep-learning pattern recognition, case-based patient retrieval, and LLM-based heuristic inference via statistical meta-aggregation and knowledge-enhanced agentic reflection. Evaluated on 2,528 strictly isolated clinical cases, FusionRare achieves state-of-the-art RD prioritization, at

---

### [174] AdamPM: Memory-Efficient LLM Optimization via Moment Pooling

**链接**: https://arxiv.org/abs/2610.24598
**作者**: Xiaowei Ji, Lishan Xu, Jianing An, Jie Luo, Wenjun Wu, Lei Huang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adam is widely used for training large language models (LLMs) owing to its strong optimization performance and training stability, but its element-wise estimation for the first and second moments incur substantial memory overhead. Although numerous memory-efficient optimizers have been proposed, many incur additional computational overhead or require additional tuning of hyperparameters. Consequently, Adam remains a dominant and reliable choice for LLM pre-training. We propose AdamPM (Adam with Pooled Moments), a simple and memory-efficient variant of Adam that groups adjacent moment entries along the row or column dimension and represents each group by a single shared mean. AdamPM can well inherit Adam's hyperparameter settings and is readily integrated into existing Adam optimizer implementations, with less memory overhead. We systematically investigate pooling of both first and second moment estimates and identify second moment pooling as the effective design. With a group size of $

---

### [175] Inside the Scorer: Mechanistic Evidence on Rubric Control in LLM-Based Automated Essay Scoring from 25 Base Models

**链接**: https://arxiv.org/abs/2610.25724
**作者**: Chungche Huang, Po-Ya Angela Wang and Shu-Kai Hsieh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated essay scoring (AES) using large language models (LLMs) offers promising use cases for language assessment, yet high-stakes testing requires scores that are both controllable and verifiable, which current LLM-based scorers lack. Given that, we investigate whether LLM-based scorers form distinct internal representations for individual scoring rubrics and whether these representations can be independently controlled. Probing and steering 25 open-weight base LLMs (0.13B-10.31B parameters; 14 families) on human-scored BESTEP English writing tasks, we find that holistic scores are decodable from model activations for the longer tasks (Parts 2 and 3) and only weakly for the shortest (Part 1). Furthermore, scoring rubrics have partly separable directions in representation space for the longer tasks, though not for short responses (Part 1). However, causal steering reveals a critical limitation: applying a matching intervention (e.g., steering "grammar" on a grammar-degraded response)

---

### [176] From Scientific Crop Imagery to Agronomic Reasoning: A Multimodal LLM Benchmark for Plant Phenotyping

**链接**: https://arxiv.org/abs/2604.09907
**作者**: Yu Wu, Guangzeng Han, Ibra Niang Niang, Francia Ravelombola, Maiara Oliveira, Jason Davis 等 (9 人)
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [177] Benefit-Targeted Routing and Bounded Revision for LLM-Based Evidence Screening in Manufacturing Supplier Discovery

**链接**: https://arxiv.org/abs/2610.25867
**作者**: Yijiashun Qi, Hanzhe Guo, Yuxuan Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An evidence-review system must allocate additional model judgments and control their use. We study these software decisions on 6,164 frozen manufacturing source-task pairs. Benefit-targeted routing learns recovered agreement minus newly introduced disagreement. On the original 300-case test, 60 consultations yield 202/231 agreements with two human references versus 189/218 for a logistic-risk router. An additional 300 cases were independently annotated twice using equal frozen evidence. Without retraining the historical policies, the corresponding counts are 164/190 versus 163/193; the differences do not resolve an advantage. Strict scalar-Ridge controls share preprocessing, regularization and fitting, and remain inconclusive. Quotation and requested-state replacement gates retain rejected cases and budget costs; their joint gate rejects one original and two additional consultations without changing primary outcomes. Evidence ablations, fusion and bounded updates supply further control

---

### [178] Computation, Not Memory: Chain-of-Thought and State Tracking in LLM Agents

**链接**: https://arxiv.org/abs/2610.25760
**作者**: Pedram Mouseli, Massieh Moayedi
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model agents often reason before they act, and the value of monitoring that reasoning depends on how it relates to their actions. We ask how an agent's actions depend on its reasoning when the correct action depends on a changing state. In a small file-system task, background events announce which file's lock has been toggled but not its new value. The agent therefore has to reconstruct the current locks from its history before it can move files safely. With Qwen3-8B and Qwen3.5-9B, we separate two roles of reasoning: generating it before each action, and retaining earlier reasoning in the prompt. Most of the reduction in lock-violating commands comes from reasoning written at the moment of action. Retaining earlier reasoning adds little to rule-following, although it helps one model complete the task. The benefit depends on what the reasoning says. Filler text, reasoning written for another history and an accurate table of the state do not reproduce it. When we give the agent

---

### [179] Coopshift: Post-Training Amplifies The Memory Curse In LLM Cooperation

**链接**: https://arxiv.org/abs/2610.24086
**作者**: Jiayuan Liu, Shiyi Du, Tianqin Li, Emanuel Tewolde, Keyang Xuan, Vincent Conitzer
**来源**: cs.GT cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How does post-training change cooperation during repeated interaction? Within each of seven released model lineages, we compare pretrained (Base), supervised fine-tuned (SFT), and subsequent preference- or reward-optimized (Aligned) checkpoints across seven social dilemmas. Copies of each checkpoint play one another for 200 rounds, with visible history limited to the last two or forty rounds. The memory curse refers to lower cooperation when agents can see more past rounds. Our central finding is that post-training amplifies this decline. Averaged across the six binary-action games, expanding visible history reduces cooperation at every SFT and Aligned checkpoint. At each post-trained stage, these declines exceed Base's in six of seven lineages. Most of this average amplification is already present at SFT. With long history, both post-trained stages also cooperate less than Base on average in each binary-action game. In the symmetric binary games, their fitted cooperation rates fall mo

---

### [180] Toollery: Scaling LLM Agents to Thousands of Skills and Tools

**链接**: https://arxiv.org/abs/2609.22218
**作者**: Xiangxi Tian, Ran Guan
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [181] Brittlebench: Quantifying LLM robustness via prompt sensitivity

**链接**: https://arxiv.org/abs/2603.13285
**作者**: Angelika Romanou, Mark Ibrahim, Candace Ross, Chantal Shaib, Kerem Oktar, Samuel J. Bell 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [182] The Weight of Teamwork: Does Communication Structure Help LLM Scientists Search for Scientific Laws?

**链接**: https://arxiv.org/abs/2610.24131
**作者**: Jianing Shi, Zaibin Zhang, Shijun Lei, Zhenfei Yin
**来源**: cs.MA cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Team performance is often reported as one delivered score, even though that score is produced in two stages: a system generates candidate answers and a selection rule returns one of them. We use symbolic regression as an observable scientific-search setting and compare fixed-budget LLM teams that differ in peer visibility and update timing, evaluating both their frozen candidate archives and the expressions selected from those archives. Distributing the call budget across more independent trajectories produced the largest measured gain, improving mean held-out fitting score Q by 0.70 at the widest tested allocation. Under a common archive-wide selector, the implemented Ring policy reduced mean Q by 0.33 relative to Independent, while Star and Complete remained unresolved. Holding the generated archives fixed, changing the delivery rule changed the measured architecture gaps, including the sign of the Complete point estimate. These results support reporting candidate generation and fina

---

### [183] InteractAgent: Agentic Human Motion Interaction with Memory-Augmented Reflection

**链接**: https://arxiv.org/abs/2610.25649
**作者**: Tao Zhang, Senhe Zhang, Zeyu Zhang, Yujia Zhang, Dong Gong
**来源**: cs.RO cs.CV
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon human-scene interaction requires coordinated spatial reasoning, physical feasibility, and the ability to recover from compounding execution errors. Text-driven motion models are largely scene-agnostic and lack closed-loop correction, while geometry-conditioned approaches depend on paired scene-motion training or explicit 3D preprocessing that limits generalization to novel layouts and open-vocabulary goals. We present InteractAgent, an agentic multimodal LLM system for long-horizon human-scene interaction that plans, executes, observes, and reflects in a closed loop, using a single MLLM as both planner and evaluator and a frozen MotionLLM as the executor. InteractAgent integrates Online Observation for step-wise recovery decisions (continue/redo/replan) and Memory-Augmented Reflection for multi-round plan refinement with adaptive stopping. On UniHSI, InteractAgent improves task success and reduces penetration compared with training-free baselines. Code: https://github.com/

---

### [184] ReTTT: Reflection-Driven Test-Time Training via Experience-Based Parametric Memory

**链接**: https://arxiv.org/abs/2610.23942
**作者**: Kangcong Li, Hangfan Zhang, Shuyue Hu, Shengji Tang, Tao Chen
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents accumulate valuable task-specific information through their actions, observations, and environmental feedback during multi-turn task execution. When effectively used, this information can help agents refine subsequent decisions and improve task performance. However, the learning value of an interaction depends on its context and subsequent feedback, making it challenging to extract reliable, actionable lessons and revise them as the task unfolds. In this paper, we introduce ReTTT, which enables experience-driven self-adaptation through test-time training on lessons constructed and continually revised within an episode. ReTTT lets the agent reflect on interaction feedback, maintain the resulting lessons in an explicit memory, and learn from them by updating an episode-local LoRA adapter while keeping the backbone frozen. The adapted model then performs both subsequent actions and reflection, coupling policy adaptation with the construction of future learning experience. We ev

---

### [185] SPLASH: Contrastive Audit Pressure for Detecting and Localizing Security Hallucinations in Generated Code

**链接**: https://arxiv.org/abs/2610.26001
**作者**: Mirza Masfiqur Rahman, MD Ajwad Akil, Imtiaz Karim, Ashish Kundu, Ramana Kompella, Elisa Bertino
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code generated by large language models often passes every functional test while remaining insecure. These security hallucinations are common, written with high confidence, and repeated across samples, so neither the generator's own uncertainty nor static analyzers reliably catch them. We introduce SPLASH, which is guided by a new measure called audit pressure. It contrasts teacher-forced log-probabilities for the generated program under a security review and a style review. Aggregated to statements and programs, and grounded in a probabilistic model of competing edits, audit pressure allows SPLASH to choose the secure program among a model's candidate programs and locate the vulnerable statement, with no model training, CWE-specific rules, or internal access to the generating model. On 63,684 programs generated by 12 models for 899 tasks, SPLASH picks secure code in 74% of cases, places the vulnerable statement first in 58% of insecure programs, and chooses better than a frontier LLM 

---

### [186] Autonomous intelligence for mining productivity: a multi-agent AI approach to operational value creation

**链接**: https://arxiv.org/abs/2610.26369
**作者**: N Guerin (CGS i3), A Dehoux (ERAMET), M Nakhla (CGS i3)
**来源**: cs.AI cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Integrated Remote Operation Centres (IROCs) are emerging as the architectural frontier of Industry 4.0 for capital-intensive sectors such as mining, oil and gas, and energy. Yet two intertwined gaps constrain their evolution towards full autonomy. First, no integrated agentic architecture has been proposed for mining IROCs that orchestrates Supervisory Control and Data Acquisition systems, digital twins, predictive analytics and human-machine interfaces under safety-critical constraints. Second, no evaluation framework jointly addresses the real-time, Health-Safety-Environment, regulatory-auditability and cost-per-decision requirements that govern industrial agentic deployments. This paper makes four contributions. It synthesises industry needs and quantified gains documented in analogous industries that motivate an agentic approach to mining IROCs. It introduces EI2ROC, a three-tier multi-agent architecture combining a Large Language Model orchestrator with specialised monitoring and 

---

### [187] UnexpectedParrots: Iterating Behavioral Experiment Design with In-Silico Simulations

**链接**: https://arxiv.org/abs/2610.25343
**作者**: Sanchaita Hazra, Bodhisattwa Prasad Majumder, Pao Siangliulue, Peter Clark, Amy X. Zhang, Joseph Chang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Running behavioral experiments is expensive, slow, and prone to design flaws, often detectable after collecting data. We introduce UnexpectedParrots to iteratively refine behavioral study designs before a researcher recruits costly human participants. UnexpectedParrots relies on reasoning traces in addition to responses from LLM participants to uncover diagnostic critiques of structural errors and missed opportunities in existing study designs. When evaluated against a human-pilot or a no-simulation design-only baseline, UnexpectedParrots adds most value, producing unique, high-quality critiques. In a moderated user study with 12 proficient researchers, we find UnexpectedParrots useful, time-saving, and thought-provoking. Critiques provided by UnexpectedParrots often converge on issues researchers identify only during independent human pilots or additional formative interviews, even when the fidelity of the simulated populations remains questionable. Our users deem UnexpectedParrots us

---

### [188] Scam Town: Can Scam Education Spread Like a Vaccine?

**链接**: https://arxiv.org/abs/2610.25040
**作者**: Simiao Ren, Tommy Duong, Xingyu Shen, Jiaqi Gan, Tsang Ng, Ankit Raj 等 (9 人)
**来源**: cs.SI cs.CY cs.MA
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most older adults who hear a warning about scams hear it from someone they know: a relative, a neighbour, or a friend who was targeted. Yet research on scam prevention almost always studies one person at a time. We ask whether scam awareness can spread through a community and protect it the way a vaccine does, since a warning protects whoever hears it and can be passed on. To find out, we built Scam Town, a simulated community in which a large language model plays each resident. Scam centres phone the residents, and after a call a resident can warn the people they know. Word of mouth helped, but it did not take off on its own: each warning led to fewer than one more, so a community cannot count on warnings "going viral". Across 80 simulated towns, everyday talk cut the number of people scammed by roughly a fifth. The largest gains came when an official warning, from a bank, a senior centre, or an agency, reached most of a town and residents then talked about it: in simulation (a combin

---

### [189] Desirability Confirmation: Relational Sycophancy in AI Intimate Roleplay

**链接**: https://arxiv.org/abs/2610.24265
**作者**: Huiqian Lai, Runze Ding
**来源**: cs.CY cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on LLM sycophancy has largely focused on propositional agreement, in which models echo users' beliefs, preferences, or judgments. Adult intimate roleplay presents a different case because what the user seeks may be preservation of a preferred relational position within a generated scene. Using a controlled prompt-based audit of 2,016 outputs from two open-weight LLMs, we identify four recurrent relational moves: legitimating desire, presenting the user as wanted, preserving non-rejection while communicating limits, and keeping intimacy available within fantasy or roleplay frames. Bringing the sycophancy literature into dialogue with sexual script theory, we conceptualize this configuration as desirability confirmation, an output-level pattern that captures how user-pleasing can operate through relational positioning. The findings extend sycophancy research and intimate-AI evaluation beyond binary compliance or refusal by showing how outputs can differ in the ways they communic

---

### [190] Zero-Shot Tabular Learning via Hypergraph Reasoning with LLMs

**链接**: https://arxiv.org/abs/2610.23923
**作者**: Geon Lee, Kyungho Kim, Dongwon Choi, Juyeon Kim, Shinhwan Kang, Kijung Shin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular data are prevalent across diverse domains such as healthcare and finance. Zero-shot tabular learning aims to make predictions without labeled data. However, existing LLM-based approaches rely on row-wise prompting, resulting in high inference cost and limited use of inter-row dependencies. In this work, we propose TABHGR+, an efficient relation-aware zero-shot framework for tabular data that leverages LLM-generated rules to label and group rows. Specifically, based on column and task descriptions, we use LLMs to generate rules that assign weak labels to all rows. To refine these noisy weak labels, we construct a hypergraph by grouping semantically related rows using LLM-generated rules and perform hypergraph-based label propagation. Lastly, we further enhance the LLM-generated hypergraph for propagation, which is potentially sub-optimal, by assigning label-adaptive weights to hyperedges. By requiring only a constant number of LLM calls independent of dataset size, TABHGR+ subst

---

### [191] Correctness-Dependent Asymmetric Target Distributions for Self-Distillation Policy Optimization

**链接**: https://arxiv.org/abs/2610.25973
**作者**: Suwan Yoon, Seongryong Jung, Changhee Lee
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-distillation policy optimization provides dense token-level supervision for LLM post-training through feedback-conditioned self-teachers. However, directly matching the self-teacher can disrupt successful behaviors on correct rollouts while providing insufficient correction on incorrect ones. We propose Asymmetric Policy Optimization via Self-Distillation (APSD), which constructs correctness-dependent targets by mixing student and self-teacher distributions: interpolation preserves successful behaviors on correct rollouts, while extrapolation beyond the self-teacher strengthens correction on incorrect ones. We analyze APSD through divergence decomposition, reverse-KL barycentric geometry, and gradient analysis, highlighting the importance of gradient flow through student-dependent targets. Experiments under reinforcement learning with verifiable rewards and rich feedback show that APSD achieves strong overall performance against reinforcement-learning and self-distillation baselin

---

### [192] A Cross-Domain Evaluation of Prompting Techniques for Large Language Models

**链接**: https://arxiv.org/abs/2610.24913
**作者**: Kevin Krazius, Tim Schlippe, Paul Libbrecht
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt engineering has become a central mechanism for guiding the behavior of Large Language Models (LLMs) across a wide range of reasoning and language understanding tasks [1], [2]. However, existing studies frequently evaluate prompting techniques using different LLMs, datasets, or task settings, making direct comparisons across methods and domains difficult [3]. Consequently, in this paper we present a controlled cross-domain evaluation of Zero-Shot prompting, Few-Shot prompting, Retrieval-Augmented Generation (RAG), and automatic prompt optimization based on a PE2-inspired optimization pipeline [4]-[6]. All experiments were conducted with the same LLM and evaluated on six benchmark datasets covering arithmetic reasoning, logical reasoning, commonsense reasoning, and factual verification. The results show that no prompting strategy consistently outperforms the others across all domains, and pairwise statistical comparisons of the highest-performing configurations revealed no signifi

---

### [193] Continuous Ontology Assurance through External Resources -- An Ontology Engineering Method with a Case Study in Software Language Engineering

**链接**: https://arxiv.org/abs/2610.24322
**作者**: Ralf L\"ammel
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain ontologies require review against knowledge recorded in evolving external resources. We propose COATER, a method that manages executable review components called arrows. Each arrow compares a scoped part of an ontology with a relevant resource and reports support or challenges to its axioms. Challenges may prompt proposals for completion, correction, or restructuring and become tasks for human or agent-assisted triage. Per-axiom coverage summarizes the assessments. We illustrate COATER with the FSL ontology in software language engineering (SLE): arrows review language coverage, language conceptualization, and software-engineering activities. An LLM-assisted linkage exercise increases compliance with a defined Wikipedia-linkage policy from 405 to 600 of 600 entities. A structured catalogue of SLE resources organizes review opportunities.

---

### [194] BanglaShield: A Script-Robust Safety Classifier and Benchmark for Bangla Native, Romanized, and Code-Mixed Prompts

**链接**: https://arxiv.org/abs/2610.24288
**作者**: Mohsinul Kabir, Md. Tariquzzaman, Mohammad Rashidujjaman Rifat, Tharindu Ranasinghe, Nishat Raihan
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety classifiers for large language models (LLMs) are typically built and evaluated on standard-script text, yet Bangla, like many lower-resource languages, is routinely written in native script, in Latin-script romanization, and code-mixed with English, Hindi, or Urdu. We introduce BanglaShield, a resource and model for graded prompt-safety classification across these written forms. We consolidate 10,245 Bangla prompts from six sources under a four-level taxonomy (Safe, Offensive, Harmful, Severe) and render each prompt in three aligned forms that share labels and a group-aware split, enabling strictly paired comparisons. Benchmarking six contemporary LLMs, including a Bangla-specialized one, on 36,882 classification queries and 24,318 judged responses, we find that LLM classifiers label 47.0% of unsafe native-script prompts as Safe, rising to 63.4% under romanization, while response-level safety accuracy drops by 10.3 points. Three multilingual guard models also pass 30.3-57.3% of 

---

### [195] Conjugate Compilation: Self-Improving Agentic Co-Compilation for Speculative Decoding

**链接**: https://arxiv.org/abs/2610.25012
**作者**: Annabelle Sujun Tang, Rohan Mahapatra, Christopher Priebe, Hanyang Xu, Manya Ghobadi, Christopher Rossbach 等 (7 人)
**来源**: cs.LG cs.DC cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM adoption surges, scaling model serving requires unlocking stranded GPU capacity alongside deploying more GPUs. Speculative decoding brings two models into the serving process: a small draft model proposes tokens that a larger target model verifies. Yet compiling these models individually leaves their shared execution outside the compiler's optimization boundary. We introduce CONJUGATE COMPILATION, which reframes speculative decoding as a cross-model compilation problem and jointly optimizes the draft and target models within their shared execution rather than treating each in isolation. Our key insight is that cross-model compilation should be informed by the measured performance of the co-located shared execution it produces: an optimization that improves a kernel in isolation need not improve the models when they execute together. To expand cross-model opportunities, we devise operand layouts that interleave blocks from both models within common tiles, co-locating GEMM and non

---

### [196] FinHopper: A Progressive Multi-Hop Benchmark for Complex Financial Agents with Step-wise Evaluation

**链接**: https://arxiv.org/abs/2610.26036
**作者**: Yuxuan Wu, Miaopei Lin, Qiufang Ying, Lin Dan, Hao Zhao, Qirui Liu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial agents are expected to answer factual investment queries through open search, but financial multi-hop retrieval differs from general multi-hop QA in a crucial way: each intermediate answer is an exact typed constraint, such as an entity, date, event, or numerical indicator, that determines the next query. This strict answer-conditioned dependency makes small intermediate errors cascade into plausible but wrong search trajectories. We introduce FinHopper, a benchmark for complex financial agents with controlled reasoning depth from 1 to 6 hops, covering stocks, funds, and macroeconomic facts, with gold intermediate answers for process-level evaluation. To construct FinHopper at scale, we design a state-transition-based synthesis framework that composes verified atomic financial QA patterns into dependency-preserving chains, followed by targeted in-synthesis verification, model-ensemble checking, and public-search validation by financial experts. Experiments with 20 LLM-agent c

---

### [197] RL Teaches VLMs Where to Attend but Not How to Perceive

**链接**: https://arxiv.org/abs/2610.23983
**作者**: Ziqian Zhang, Junjie Liao, Zhining Zhang, Wentao Zhu
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although reinforcement learning (RL) effectively trains Vision-Language Model (VLM) agents, the mechanisms behind these capability gains are poorly understood. Across four diverse agent environments, we investigate whether the task-success gains from multi-turn RL are accompanied by improved grounded visual question answering about the environment. To assess this, we design environment-specific grounded VQA tasks that reveal improvements in grounded visual understanding. Representational probing shows that vision-encoder probe accuracy remains relatively stable, while LLM-layer probe accuracy improves. Attention analysis further reveals that LLM layers pay more attention to visual tokens during RL training. To test whether increased attention to visual tokens contributes to VQA gains, we introduce a lightweight plug-and-play intervention using a fixed attention bias. Without updating model parameters or computing gradients, this intervention partially restores VQA gains on the untraine

---

### [198] HarnessPro: Recursive Harness Self-Improvement with Pareto Optimization for Performance-Cost Trade-offs

**链接**: https://arxiv.org/abs/2610.26770
**作者**: Zhuoshi Pan, ZhiYuan Feng, Yukuo Cen, Honglin Lin, Junru Lu, Zhongxia Chen 等 (9 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Harness development plays a crucial role in building capable AI agents. Recent approaches improve harnesses through recursive self-improvement (RSI), but their performance gains often come with higher execution costs. We introduce HarnessPro, a label-free method for evolving harnesses to improve task performance while reducing execution cost. In this setting, candidate harnesses are evaluated using LLM-generated tests without access to ground-truth solutions or official tests. Specialized agents diagnose execution trajectories, plan updates with different performance-cost priorities, and implement them as candidate harnesses. Rather than returning a single harness, HarnessPro uses normalized weighted squared-distance selection to provide cost-focused (lite), balanced (medium), and performance-focused (heavy) harnesses for different deployment budgets. Selected harnesses enter the next iteration, where execution feedback guides further updates. Our experiments cover Terminal-Bench 2, SW

---

### [199] Auditing Tool Traces in Agentic LLMs: Source Localization and Counterfactual Dependence Testing

**链接**: https://arxiv.org/abs/2610.25540
**作者**: Junhao Liu, Tianxiao Li, Yongxian Wu, Ziheng Duan, Ren Li, Jing Zhang 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic LLMs increasingly support scientific prediction by grounding decisions in external evidence. In biology, they promise accurate, interpretable predictions for important problems by integrating complex experimental and computational evidence. However, serialized tool results can contain hidden label shortcuts, such as dataset identifiers or template artifacts, that create apparent success without biological reasoning. To address this risk, we introduce a two-stage audit. Stage 1, Per-Tool TF-IDF Decomposition (PT2D), localizes label-predictive patterns to individual tool results while avoiding signal dilution in the concatenated tool trace. Stage 2, Token-Class Redaction, counterfactually tests whether the frozen LLM depends on the localized shortcut. We apply this audit to TCR-pMHC binding, where tool augmentation substantially outperforms a no-evidence baseline. At face value, this suggests that the LLM has learned to use scientific evidence. The audit overturns this interpreta

---

### [200] Compaction-Aware Reinforcement Learning For Ascend Triton Kernel Generation

**链接**: https://arxiv.org/abs/2610.23950
**作者**: Chuansai Zhou, Yanlin Liu, Bingning Huang, Shidi Xi, Chao Huang, Boxing Chen 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatically generating high-performance kernels with LLM-based agents promises substantial gains in development efficiency, but two obstacles remain. First, while increasing multi-turn interaction with execution environments is crucial for refining generation quality, continuous context accumulation rapidly exceeds the model's effective context window. Second, training long-horizon tasks via GRPO inherently incurs sparse rewards due to its reliance on terminal outcome evaluation, severely hindering step-level credit assignment; To address these obstacles, we propose ATRL (Ascend Triton Reinforcement Learning), a post-training method that refines GRPO into a compaction-aware, segment-level objective for long-horizon kernel generation. We also design a lightweight agent harness providing cascaded compilation, correctness, and profiling feedback, alongside an Ascend-specific knowledge base injected during agentic RL training and evaluation to compensate for the base model's missing plat

---

### [201] VisConf: Quality-Aware Consensus for Best-of-N in Vision-Language Model Reasoning

**链接**: https://arxiv.org/abs/2610.24526
**作者**: Muhammad Usman, Muhammad Qasim Ayub, Usman Ahad, Muhammad Tahir
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Best-of-N methods improve text-only LLM reasoning by sampling multiple trajectories before selecting an answer. For Vision-Language Models (VLMs), answer frequency and model confidence alone can be insufficient, as sampled generations also vary in their engagement with the visual input. We find that distributional confidence and visual attention are complementary indicators of rollout quality. Each is limited on its own, while trajectories that show strong signals in both are more likely to be correct. Motivated by this, we introduce VisConf, a rollout-quality score that multiplicatively combines visual engagement with candidate-calibrated Self-Certainty, penalizing rollouts that are weak in either signal. We incorporate Rank-Weighted Consensus (RWC), a tuning-free aggregation rule that converts within-question VisConf ranks into answer-level vote weights. Across three VLMs on MathVista, MMMU-Pro, and MMStar, VisConf with RWC consistently outperforms strong BoN baselines. Our analysis 

---

### [202] ACE-Trader: Adversarial Co-Evolution for Generator-Critic Trading Systems

**链接**: https://arxiv.org/abs/2610.25847
**作者**: Chang Zhou, Jiarun Zhou, Xingtong Yu, Hong Cheng, Hui Zhang, Xinming Zhang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generator--critic trading systems pair an LLM-based trader that makes trading decisions with a red team agent that evaluates these decisions and provides feedback for revision. However, improving individual trading decisions does not ensure that both agents learn from experience and improve together over time. This raises an important question: how can the trader and red-Team select useful experience and learn from each other's evolving behavior? On one hand, experience that benefits decisions under one market condition may become ineffective or harmful under another. On the other hand, trading outcomes reflect both agents' actions, making it difficult to derive appropriate experience for each role. In this work, we propose ACE-Trader, an adversarial co-evolution trading framework. Specifically, we first develop separate context-dependent memory selectors that learn to identify useful experience for the current trading decision. Both selectors receive shared feedback from net-return di

---

### [203] SoK: PIAtlas: Decomposing the Unbounded Prompt Injection Attack Space

**链接**: https://arxiv.org/abs/2610.24999
**作者**: Stavros Damianakis, Konstantinos Psounis
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt injection is the dominant security risk for large-language-model (LLM) applications and agents, yet the field still lacks a coherent map of how these attacks are constructed. More than twenty public datasets describe prompt injection using incompatible vocabularies, often organized around delivery vector, attacker goal, or generation method. In this Systematization of Knowledge, we present PIAtlas, a taxonomy organized instead around how the injected instruction is constructed to subvert the underlying model. Its six classes, one per subversion mechanism, form the roots of a hierarchy of techniques and sub-techniques that researchers can use to describe attacks consistently and design more systematic evaluations. We derive the taxonomy from how LLMs are trained, prompted, and influenced by human-like framing, and compare it with historical attack data. To ground this comparison, we release PICorpus, to our knowledge the largest license-clean collection of public prompt-injection

---

### [204] VERAS: Verification-Guided Adaptive Search for Reliable Operations Research

**链接**: https://arxiv.org/abs/2610.24329
**作者**: Minbo Ma, Honglin Zhang, Bangtao Zhou, Chunguang Yu, Dasheng Ju, Yichen Shen 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advances in reasoning, coding, and tool use enable LLM agents to solve operations research (OR) problems through iterative problem modeling, program construction, and verification. Yet passing self-authored verification does not ensure that the solutions satisfy task constraints and meet optimization quality. This gap can arise from correlated specification errors, where the generated program and its checks share omissions or misinterpretations of task requirements, alongside incomplete verification coverage and ineffective optimization strategies. We propose VERAS, a verification-guided adaptive search harness for reliable OR that uses verification evidence to prioritize feasibility repair, constraint-coverage review, and solution-quality improvement. VERAS combines task-specific solution checkers with a separate verification agent to examine candidate solutions against the task requirements. It uses verification feedback to guide feasibility repair, additional constraint checking, an

---

### [205] No Matter Who You Are: Addressivity and Sycophancy in Large Language Models

**链接**: https://arxiv.org/abs/2610.25728
**作者**: Seungjong Sun, Hyunmin Jun, Minsik Yoon, Eungu Lee, Choongwon Kang, Young Seok Woo 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sycophancy, where an LLM becomes overly agreeable, deferential, or flattering toward the user, has been identified as a major failure mode. While post-training has been implicated as a cause, how it internally gives rise to sycophantic behavior remains insufficiently understood. Post-training transforms the model's output from text completion into utterances directed toward an addressee, thereby giving the output \textit{addressivity}. We hypothesize that the accompanying pressure to follow the addressee's instructions and align with their preferences links this addressivity to sycophancy. To test this, we use Sparse Autoencoders to extract addressivity directions from pre-trained and post-trained models and examine their relationship with sycophancy. Steering models with addressivity directions can amplify or suppress sycophancy, and this effect is observed only in post-trained models. Furthermore, comparing the internal mechanisms of both model types confirms that the association bet

---

### [206] IF-MAP: Influence-Function-Inspired Agent Prioritization in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.24383
**作者**: Jie Mao, Pingchen Lu, Zikun Qu, Jiahang Sun, Xiangyi Wang, Zhiwei Shang 等 (9 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Improving every agent in an LLM-based multi-agent system can be prohibitively costly, making it important to identify which agent should be prioritized to achieve the greatest system-level gain with limited resources. Failure attribution can inform this decision, but an agent's responsibility for failures does not directly reveal the system-level gains achievable by improving it. We therefore introduce IF-MAP, an influence-function-inspired method for identifying agents with high potential for system-level improvement. For each agent, IF-MAP measures end-to-end loss changes under controlled semantic prompt perturbations, fits a regularized local response model in a low-dimensional prompt-embedding subspace, and uses the estimated response norm as a priority score. This black-box procedure requires no access to model parameters or gradients and produces agent priorities that can guide subsequent improvement effort. We evaluate IF-MAP across six multi-agent workflows spanning code genera

---

### [207] Ask, Don't Guess: Targeted Clarification for Speech Recognition Errors

**链接**: https://arxiv.org/abs/2610.24809
**作者**: Sankalp Parashar, Preethi Jyothi, Sunita Sarawagi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech recognition in real time in far-field conversational settings still incurs significant errors. Identifying potential error spans during streaming ASR permits a recourse mechanism where the speaker can be asked to repeat the affected content under cleaner acoustic conditions. We propose \sysname, a new framework for online error localization, that identifies spans likely to benefit from this intervention. Our supervision uses clean audio to estimate how the recognizer's output might change under improved acoustic conditions. We probabilistically align noisy and clean decodes using a pair-HMM to obtain soft supervision. These soft targets train a counterfactual gain scorer by combining a suite of acoustic and language features to produce token-level scores, that are further grouped into spans for targeted recourse. An LLM uses the ASR transcript of the repetition to revise only the selected span. At a precision of $70\%$, \sysname achieves the highest recall by identifying up to 5

---

### [208] Whose Credential Is It? How Owner Attribution in Agent MemoryShapes Cross-User Account Misuse

**链接**: https://arxiv.org/abs/2610.25707
**作者**: Hau-Sing So, Daixian Liu, Carl Hou, Yuhaohang He, Mengzhu Wang, Hai-Tao Zheng
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Shared long-term memory lets an LLM agent serving one user inadvertently retrieve another user's credentials, but it is unclear when such exposure leads to actual harm. We introduce a three-stage audit that separates three events: a foreign credential reaches the prompt (exposure), the agent acts with it (behavior), and the other user's account changes (state). In AppWorld, a store that mixes 763 past logins from all users retrieves another user's credential for 84.7 percent of required apps, yet agents rarely act on it. Misuse appears in a stress test where memory lacks the user's own credential and presents a single foreign one as the user's record: seven agents then use it in 80 to 94 percent of runs and change the victim's account in up to 43 percent, sometimes passing the official check. Naming the owner before or inside each credential line prevents most of this: with all else fixed, misuse falls from 92 to 1 of 305 paired runs, also with name-free usernames, though owner-bound n

---

### [209] Are Self-Evolving Agents Continual Learners?

**链接**: https://arxiv.org/abs/2610.25858
**作者**: Xiaoyin Chen, Yizheng Huang, Yinglun Xu, Ziyun Zhao, Emmett McQuinn, Julie Liu 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are often deployed in environments where new knowledge, tools, and workflows keep arriving. Such an agent is therefore expected to adapt continually, learning new tasks as they arrive without forgetting earlier ones. This resembles the continual learning problem, but at a pace that conventional gradient updates cannot sustain. Nonparametric self-evolving agents are a natural alternative: they adapt by rewriting their own harness, such as prompts, memory, and skills, from task feedback while the model weights stay frozen. We study whether such agents are effective continual learners across four drifting task streams that shift in topic, workflow, or domain (built from BIRD, BFCL, and ScienceWorld). Evaluating three representative methods spanning experience retrieval and self-modification (ReasoningBank, GEPA, and Meta-Harness), we find that although self-evolution improves aggregate performance on most streams, higher plasticity consistently comes at the cos

---

### [210] AM-Bench: A Unified Taxonomy and Evaluation Suite for Agentic Misalignment

**链接**: https://arxiv.org/abs/2610.24264
**作者**: Eric Zhang, Terry Jingchen Zhang, Chijioke Ugwuanyi, Jerick Shi, Bernhard Sch\"olkopf, Zhijing Jin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM-based agents are deployed with increasing autonomy in real-world environments, a critical failure mode emerges: agentic misalignment, where agents choose harmful actions over failure. However, existing safety benchmarks primarily evaluate whether agents comply with explicitly harmful instructions, leaving the conditions that cause agents to choose harmful actions poorly understood. To address this limitation, we propose AM-Bench, a unified taxonomy and 35 scenario evaluation benchmark spanning seven industries for agentic misalignment grounded in the fraud triangle, a well-established criminological framework explaining goal-directed misconduct. We adapt this framework to agentic environments and construct our evaluation suite and detection systems along three dimensions: perceived threat, perceived opportunity, and reasoning. We operationalize each dimension into structured subcategories rooted in prior theory: five threat categories derived from the instrumental convergence th

---

### [211] Trackable Skill Library Lifecycle Management for Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.25126
**作者**: Xi Zhu, Yuanlin Duan, Changyi Yang, Kai Mei, Riyang Bao, Shichao Zhu 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skill-augmented agentic RL has emerged as an effective approach to improving LLM agents on long-horizon tasks. Despite this progress, individual skills may follow distinct trajectories as the policy evolves, with some becoming redundant after the model internalizes their capabilities, others remaining valuable as external scaffolding, and still others turning harmful. However, existing skill library systems fail to identify each skill's true contribution due to free-riding among co-retrieved skills, difficulty confounding across tasks, and the absence of skill-specific counterfactual evidence, which prevents reliable skill lifecycle management. We propose TrackRL, an agentic RL framework where skill tracking drives skill library full lifecycle management. Specifically, within each GRPO group, we turn grouped sampling into online randomized controlled experiments. Independent random injection and within-group contrasts on the same task isolate each skill's true contribution, and reliabi

---

### [212] Dialogue Generation for Conversational Recommendation Using User Search Interactions and Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.25182
**作者**: Minsung Hwang, Donggyu Yoon, Gowoon Hwang, Kwanghee Jang, Joyce Jiyoung Whang
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale conversational recommendation datasets typically require manual dialogue construction or annotation. We propose SearCl, which automatically generates conversational recommendation dialogues grounded in user search and click behaviors. SearCl segments user interactions into query sessions and derives each recommendation target from content selected after a search query. A configurable probabilistic state machine controls the dialogue flow, while two LLM agents acting as the seeker and recommender generate utterances according to turn-level constraints. To support recommendation, the recommender is provided with knowledge graphs constructed from metadata about the content items used in each dialogue, capturing their attributes and relationships. Using SearCl, we generate 3,538 dialogues from content search and click interaction data, covering 1,731 unique target items. Under an LLM-as-a-judge protocol, the resulting dialogues achieve higher quality scores than dialogues from 

---

### [213] Do 3D Large Language Models Really Use 3D Evidence?

**链接**: https://arxiv.org/abs/2610.24447
**作者**: Yifei Zhao, Fanyu Zhao, Han Zhang, Yixuan Lin, Yuyang Hou, Bin Wu 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent 3D Large Language Models (3D-LLMs) have shown strong performance on scene question answering with extensive post-training. Yet, existing benchmarks rarely evaluate how 3D-LLMs respond to referential ambiguity, insufficient scene evidence, or false presuppositions, obscuring whether their responses are grounded in 3D evidence. In this work, we introduce UNICORNS, a benchmark for evaluating the reliability of 3D-LLM responses across four evidence conditions. UNICORNS contains 11,387 questions across 557 ScanNet scans, covering eight challenge categories alongside answerable controls. A response passes only if it satisfies the required response behavior and contains no scene claim unsupported by the available evidence. Evaluation of six open-sourced 3D-LLMs reveals a pronounced performance gap: even the strongest zero-shot model achieves 61.22% accuracy on answerable controls, but only 40.94% across the eight challenge categories. To address this gap, we further propose HORN, an ob

---

### [214] FlowMaker: From Tasks to Cost-Efficient Generative AI Workflow Deployments

**链接**: https://arxiv.org/abs/2610.24861
**作者**: Dimitrios Liakopoulos, Prasoon Sinha, Neeraja J. Yadwadkar
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI workflows execute user tasks by composing sequences of LLM calls, where each call performs a sub-task (e.g., summarization or translation), forming a workflow. Executing such workflows requires decisions over workflow structure, model assignments, and deployment configurations, which jointly determine latency, cost, and accuracy under dynamic workloads and resource constraints. Existing systems optimize these decisions in isolation or fix them early, leading to suboptimal cost and goodput. We make two key observations. First, efficient serving requires jointly exploring all combinations of workflows, model choices, and deployment configurations under dynamic cluster state. Second, reuse of deployed LLMs is critical for reducing cost, but must be performed on-the-fly, as reuse depends on current load and resource availability. Together, these make selecting a workflow-variant-a combination of workflow, models, and deployment configuration-a time-critical problem. We presen

---

### [215] Which Long Documents Matter? A Controlled Study of Data Selection for Context Extension

**链接**: https://arxiv.org/abs/2610.24469
**作者**: Junlong Jia, Jiang Zhou, Xing Wu, Chaochen Gao Tinghao Yu, Feng Zhang, Lilin Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural long documents are widely used for context extension, but which selection pipelines are effective remains unclear. We conduct a controlled comparison on Qwen2.5-3B at 128K under matched 6B-token continued-training budgets. Random sampling of natural long documents (random-long) outperforms repacking at longer evaluation lengths. Within the same candidate pool, selecting documents with high LongPPL key-token density yields further gains, unlike the evaluated generic-quality and LLM-judge selectors. We introduce truncLongPPL to reduce scoring cost by computing key-token density over a truncated prefix. At 128K, scoring the first half of the reference span yields downstream performance close to full-span scoring with a measured $2.28\times$ end-to-end scoring speedup. Across three training seeds, truncLongPPL achieves the highest mean scores among evaluated pipelines, exceeding random-long by 4.54 points on validation HELMET and 3.28 on held-out RULER, with gains most consistent i

---

### [216] GAIDA: Generative AI for Human-in-the-Loop Document Annotation

**链接**: https://arxiv.org/abs/2610.26362
**作者**: Islam Mesabah, Ali Elhosary, Priyabanta Sandulu, Darko Obradovic, and Sebastian J. Vollmer
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Document annotation is a fundamental yet labor-intensive step in building document information extraction systems. While Optical Character Recognition (OCR) and Large Language Models (LLMs) can automate parts of this process, we argue that annotation systems should be judged not by how completely they remove human effort, but by how effectively they redirect it toward review and correction. We propose a modular human-in-the-loop architecture that integrates OCR-based extraction, LLM-based semantic pre-annotation, and human validation in a single editable workflow, and present \textbf{GAIDA}, a research prototype serving as its reference implementation. GAIDA supports interchangeable OCR engines, LLM backends, and prompt configurations, and enables stage-specific measurement of annotation effort. In an initial single-annotator, stage-specific study on the FUNSD scanned-form and WildReceipt retail-receipt benchmarks, OCR assistance reduced region-creation and transcription time by up to 

---

### [217] Morpheus: a fully local, defense-in-depth de-identification engine for Greek clinical text - a benchmark evaluation

**链接**: https://arxiv.org/abs/2610.25155
**作者**: Filippos-Paschalis Rorris (1 and 2), Nikoleta Stanitsa (3), Tatiana Rorri (1), Foteini Rorri (4), Constantine N. Antonopoulos (5) ((1) Onassis Hospital, Athens 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background and Objective: Clinical free text cannot leave the hospital without de-identification, yet no de-identification system or benchmark exists for Greek clinical text. We evaluated Morpheus, a fully local de-identification pipeline for Greek clinical documents, on 500 synthetic discharge summaries. Methods: The notes (300 cardiac surgery, 100 cardiology, 100 nephrology) were generated by a frontier large language model (Gemini 3.1 Pro) constrained to authentic Greek hospital document layouts. Notes were pre-annotated at generation; two clinicians then independently reviewed and corrected every note, blinded to each other, with disagreements arbitrated. Primary outcomes were recall over must-redact identifiers and over-redaction of clinical content, measured over must-survive probes. Secondary outcomes: residual leaks flagged by an independent egress-review layer, processing time and reproducibility. Results: Inter-annotator agreement was F1 = 0.998. The de-identification rate wa

---

### [218] Scaling Synthetic Pre-training Data and Evaluation for Indic LLMs

**链接**: https://arxiv.org/abs/2610.26006
**作者**: Abhinav Khattar (1), Aishwarya Chhabra (1), Ameya Velingker (1), Anusha Kamath (1), Brandon Norick (1), Kanishk Singla (1) 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building capable language models for India requires scalable multilingual data and robust evaluation. We introduce Nemotron-Pretraining-Indic-v1, a synthetic pretraining corpus of approximately 2.83 trillion tokens covering all 22 scheduled Indian languages in native script and twelve in romanized form. It is the largest openly released Indic pretraining corpus. Using our GPU-accelerated pipeline, we translate curated English documents, assess translation quality, and repair low-quality outputs while preserving technical content and document structure and maintaining source traceability. Through continued-pretraining experiments across twelve languages, we show that combining our synthetic corpus with natural Indic text improves knowledge and reasoning over a public-corpus baseline. Additional experiments show how data volume, script coverage, and Indic training share affect English performance. We also introduce the Indic-LLM-Eval-Suite, a multilingual benchmark suite for evaluating I

---

### [219] NIOCIS: Typed-Decision Next-Hop Routing with Node-Conditioned Option Spaces for Tool-Use Agents

**链接**: https://arxiv.org/abs/2610.25985
**作者**: Jin Han, Mingfeng Xin, Feng Liang, Jingtao Yu
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-use agents pay per decision: at each hop a language model re-reads the state and thinks for seconds, though its actions are finite and decisions recur. We present NIOCIS, a routing layer that folds execution logs into a loop-collapsed action graph (forward transitions plus recovery back-edges) answering one typed question: which declared option at a state, plus stop, does the fleet take next? A small model reads a calibrated distribution over them in one pass, emitting no text. On 1,615 production security-operations episodes we measure what the layer replaces, returns and is bounded by. Replaces: the typed encoder matches the logged next hop on 32.2% of the 3,875 held-out decisions (34.9% within the declared options) in 10 ms of encoder time (19.5 ms for the typed-choice form), against 2.2 s per LLM hop; two feature readouts reach 32.8% and 32.3%, an ordering the paired test does not resolve, so the typed layer is chosen for cost, not a separated lead. Tuning: jpt-4b reaches 9.9%

---

### [220] LatComm: Reusable Context Compression for Latent Communication between Large Language Models

**链接**: https://arxiv.org/abs/2610.26840
**作者**: Huawei Lin, Jinting Liu, Tan Yu, Weijie Zhao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systems that combine several large language models (LLMs) often use one context for many questions. When the context is passed between models as text, the receiving model processes all of its tokens again for every question. Avoiding this cost requires a context representation that is compact, reusable across questions, and readable by a different LLM. Existing compression and latent communication methods each provide only some of these properties. We introduce LatComm, a Latent Communication interface that provides all three by separating encoding from reading: the context is encoded once without the question, and the receiver selects what to read for each question. A frozen context encoder LLM compresses the context into a fixed-size packet and sends it to a different frozen receiver LLM, which reads the packet through cross-attention, with gates computed from its prompt. On 12 multiple-choice question-answering datasets, LatComm improves average accuracy over single-vector baselines

---

### [221] PeekKV: The First Content Token Already Knows Which Heads Matter

**链接**: https://arxiv.org/abs/2610.23939
**作者**: Minyoung Go, Yongjun Park
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The size of the KV cache grows linearly with context length, making it a major memory bottleneck in LLM serving. Motivated by recent progress in identifying the functional roles of attention heads, a growing body of work compresses the KV cache non-uniformly across heads. Existing methods either fix the important heads via offline profiling or select them using attention signals from the prefill stage. In both cases, however, accuracy fluctuates substantially across workloads. While investigating the cause of this instability, we find that the active heads shift between the prefill and decode stages even within a single input. Along the decode path, by contrast, the activehead composition remains stable across content tokens once format tokens are filtered out. Based on this observation, we propose PeekKV. PeekKV observes a single content token immediately after prefill - a one-token peek - to jointly obtain head-group scores and token-importance scores. Guided by these scores, PeekKV 

---

### [222] Means-Ends Analysis Helps LLMs Plan in Continuous-State Domains

**链接**: https://arxiv.org/abs/2610.24928
**作者**: Jiayi Li, Carl Kingsford
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM planning research has traditionally focused on discrete-state domains, where actions form a finite, enumerable set. Existing LLM planning frameworks largely assume actions are enumerable, modeling planning as a search process over candidate actions. However, in continuous-state domains, where actions form a continuum and cannot be enumerated, this assumption breaks down. We find a remedy in Newell and Simon's Means-Ends Analysis (MEA), a general problem-solving technique rooted in heuristics from human psychology. We develop Medaka, an MEA-inspired structured prompting framework that encourages recursive goal decomposition, algebraic derivation, and per-step state tracking. To evaluate native LLM planning abilities in continuous-state domains, we develop Liquidworld, a systematic testbed on liquid mixing. On Liquidworld, Medaka can improve performance across model families, suggesting that classical means-ends analysis elicits LLM-native reasoning abilities that are helpful for con

---

### [223] Do LLMs Reproduce the Age Gap in Loneliness? Evaluating Survey Simulation against European Survey Data

**链接**: https://arxiv.org/abs/2610.25158
**作者**: Yuliya Li, Achim Rettinger, Dominik Beyer
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are often used to simulate survey respondents, but matching survey averages does not establish accurate demographic differences. We test whether LLM outputs reproduce within-country age gaps in loneliness using the 2022 EU Loneliness Survey, comparing adults aged 18-34 and 65 or older in France, Italy, Poland, and Sweden. We evaluate simulation with and without age information and direct distribution estimation against a probability-based sample, with a non-probability sensitivity reference. Both human samples show higher mean loneliness among younger adults. Under age-specified simulation with standard response-option order, Mistral Small 4 and GPT-5.6 Terra reverse this ordering under all three prompt framings in three and two countries, respectively, mainly by overestimating older-adult means. DeepSeek V4 Flash preserves the ordering everywhere but underestimates both group means, with errors largely cancelling in France and Italy. Against the probabilit

---

### [224] Where Does Rhetorical Distortion Live? A Multi-Platform, Multi-Language Measurement of Influencer Content

**链接**: https://arxiv.org/abs/2610.26412
**作者**: Xucheng Yu, Jiangping Chen, Haohan Wang
**来源**: cs.SI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Much of the manipulation in online influencer content is not false but disproportionate: an accurate fact is framed as historic, urgent, or catastrophic. Fact-checking and clickbait detection are not designed to capture such framing, and little is known about where it originates: with the creator, the topic, the platform, or the audience that replies. We operationalize rhetorical distortion through five literature-grounded dimensions (Significance Inflation, Anxiety Manufacturing, Novelty Claims, Loaded Language, and Temporal Distortion) and measure it with a three-tier pipeline in which bilingual lexical rules propose candidates, negative filters cancel known false-positive contexts, and an LLM verifies or relabels the candidates. Applying the pipeline to 13,060 posts from 330 accounts on six platforms (RSS/newsletters, YouTube, Bluesky, Reddit, Weibo, and X/Twitter), we find that platform is far more strongly associated with account-level distortion than content category (Kruskal-Wal

---

### [225] Reranking Answers of Large Language Models with Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.25185
**作者**: Mikhail Salnikov, Hai Le, Olga Tsymboi, Ivan Lazichny, Dmitrii Iarosh, Egor Cheremiskin 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Answering natural language questions over knowledge graph data is challenging due to the vast number of facts, which can be difficult to process and navigate. One potential solution for this issue is to use mined subgraphs related to the query, although this process still requires extracting these subgraphs. This research presents a solution for extracting subgraphs related to entity candidates from a question-and-answer set, which can be obtained by inferring a large language model by calculating the shortest paths between entities. The proposed approaches detail various features that can be extracted from the subgraphs and reranking models to select the most probable answers from a list of candidates. Experiments were conducted on Wikidata to evaluate the effectiveness of the proposed approaches. This involved enumerating all the main feature types that can be extracted from mined subgraphs and a detailed analysis of the proposed features and reranking method combinations. In additio

---

### [226] CVaR-RMD: CVaR Selection Pressure for Robust Metaheuristic Discovery

**链接**: https://arxiv.org/abs/2610.25697
**作者**: Ruodai Cui, Li Niu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models have recently been used to discover heuristics through iterative program search, offering a promising approach to automated algorithm design. However, candidates selected by average performance may degrade across instance families, random seeds, and problem scales because mean-based objectives can obscure rare but severe failures. We propose CVaR-RMD, a risk-sensitive evolutionary framework that uses an LLM to mutate executable heuristic programs and ranks candidates by empirical conditional value-at-risk over heterogeneous evaluation conditions. Across three combinatorial optimization domains, CVaR-based selection improves upper-tail performance and reduces failure rates while maintaining competitive mean performance. These gains persist on larger unseen instances and independently curated within-domain benchmarks

---

### [227] EG-GRPO: Evidence-Guided Step-level Credit Assignment for Deep Search Agents

**链接**: https://arxiv.org/abs/2610.25269
**作者**: Sijia Luo, Mengjie Gao, Yuxiao He, Mengshu Sun, Cuiping Li, Hong Chen 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based search agents demonstrate strong capabilities in long-horizon information seeking and reasoning, typically trained via reinforcement learning. However, existing approaches predominantly rely on trajectory-level outcome rewards, providing limited supervision for complex search and reasoning processes. Although step-level credit assignment offers a promising solution, obtaining reliable and task-grounded supervision for open-ended search remains challenging. In this paper, we propose Evidence-Guided Group Relative Policy Optimization (EG-GRPO), a framework that derives step-level supervision from the evidence annotations available in synthetic deep search data. EG-GRPO identifies the first supporting citation for each required evidence claim and uses the newly acquired evidence to construct step-level process rewards. By representing the accumulated evidence as an evolving knowledge state, EG-GRPO further performs state-conditioned relative advantage estimation and combines the

---

### [228] PRECOCIAL: Pretraining with Code Curriculums via Iterative Search for Accelerated Learning

**链接**: https://arxiv.org/abs/2610.24970
**作者**: Edward Gu, Ali Payani, Kevin Ellis
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fully synthetic pretraining data generated by symbolic programs can bootstrap downstream training on naturalistic tasks, such as language modeling, but the generating programs have so far been designed by hand. We introduce PRECOCIAL, a method for automatically optimizing programs that generate synthetic pretraining data. Starting from an initial generator program, an LLM iteratively rewrites the program, and each rewrite is scored by pretraining a randomly-initialized transformer on its data and fine-tuning it on the downstream task. Because every score requires training, PRECOCIAL keeps a single network for the entire search, continuing its pretraining for each accepted program instead of training a new network per candidate, making it significantly more efficient. On four language and code datasets, at a fixed fine-tuning budget, optimized programs reach lower perplexity than hand-designed curricula, published procedural generators, random program mutation and the program the LLM wr

---

### [229] CorrectRTL: Boost RTL Generation Quality Through Automated Self-Correction with Instruction Decomposition

**链接**: https://arxiv.org/abs/2610.24977
**作者**: Jing Wang, Shang Liu, Hangan Zhou, Wenji Fang, Yuchao Wu, Yugao Zhu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong promise in specification-to-RTL generation. Among the explorations, the self-correction paradigm has significantly advanced LLM-based RTL generation. However, two challenges limit further progress. Existing benchmarks are saturated by advanced LLMs, leaving little room to evaluate the agentic self-correction framework. The monolithic self-correction paradigm rewrites the entire design at once, where LLMs are susceptible to error confusion and corruption of originally correct code. To address the benchmark challenge, we contribute ScaleBench, a more challenging benchmark of 200 complex RTL designs. To address the challenge in methodology, we propose CorrectRTL, an agentic framework that realizes a new decompose-then-correct paradigm, in which the LLM agent explicitly decouples scaffold construction from detailed implementation. CorrectRTL contributes three core techniques: (1)~\emph{Structure-oriented decomposition}, (2)~\emph{Snippet-based

---

### [230] TIRE: Top-Down Formula Instantiation with Reliable Execution for Physics Problem Synthesis

**链接**: https://arxiv.org/abs/2610.25134
**作者**: Xiaoyu Wu, Zhaoxin Yu, Xinglin Xiao, Nan Xu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Advancing physics reasoning in large language models requires scalable training data that connect physical laws, concrete problem scenarios, and verifiable numerical answers. Expert-designed problems offer top-down control over physical laws, conditions, and scenarios, but require costly human effort. LLM-based synthesis from texts scales efficiently, but model-generated answers and assessments leave supervision vulnerable to hallucinations. We introduce TIRE, a framework for Top-Down Formula Instantiation with Reliable Execution that brings knowledge-driven problem construction to large-scale data generation. Top-down instantiation uses reusable physical formulas and their applicability conditions to control the physical relations and numerical configurations of generated problems. Reliable execution establishes reference answers before problem generation, providing a common numerical foundation for problem construction and teacher distillation. Together, these mechanisms combine cont

---

### [231] miniTE: Diagnosing and Bridging the Execution Gap in Native NVFP4 Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.23928
**作者**: Zhen Li, Mingfa Feng, Yiming Zhang, Yang Yu, Changhai Zhou, Pengxiang Li 等 (9 人)
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Native NVFP4 promises to accelerate reinforcement learning (RL) for large language models (LLMs), but achieving stable learning across separate training and sampling engines remains challenging. We show that matching model weights and numerical formats is insufficient to ensure consistent policy evaluation, highlighting the importance of cross-engine numerical execution. We introduce miniTE, a lightweight framework that combines execution diagnostics, cross-engine numerical alignment, and efficient native W4A4 (4-bit weights and activations) GEMM computation for LLM RL. It improves numerical execution consistency without modifying the RL objective, while reducing implementation overhead to realize the benefits of native low-bit computation. Long-horizon RL experiments on Qwen3-30B-A3B demonstrate stable training and benchmark performance close to BF16, outperforming naive Transformer Engine (TE) NVFP4 in evaluation quality. On single NVIDIA B300 GPU node, the optimized learner reaches 

---

### [232] Good Judgment, Bad Advice: Decision-Model Controllers Raise Agent Cost Without Improving Success

**链接**: https://arxiv.org/abs/2610.24649
**作者**: Naman Vats
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent scaffolds increasingly delegate small decisions (whether to stop, verify, or change approach) to cheaper models. We ask whether a typed decision model, Jev 1.13, consulted only at deterministic decision points, makes a Claude Sonnet 5.5 terminal agent cheaper without making it worse. In a pre-specified study on Terminal-Bench 2.1, we hold one agent loop fixed and vary only the controller: none, deterministic rules, a small LLM (Claude Haiku 5.5) answering the same questions, Jev, and a placebo that samples Jev's development-phase choice frequencies at the same moments. On 21 held-out tasks (315 trials), Jev raised cost per attempt by 19% (geometric-mean ratio 1.19, 95% CI 1.02-1.36) at an identical pass rate (73.0% vs. 73.0%). Jev was cheaper than the small-LLM controller (ratio 0.81) but 22% more expensive than the placebo, and no pass-rate difference between arms was detectable. Offline, Jev ranked finish requests better than the alternatives (AUROC 0.78 vs. 0.62 for rules and 

---

### [233] Indistinguishable Agents: Training Agent Privacy as Twin-World Indistinguishability

**链接**: https://arxiv.org/abs/2610.25161
**作者**: Jiaming He, Guanyu Hou, Yi Yu, Xudong Jiang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents search, shop and send messages for their users, and every action is seen by some party. Existing privacy training rewards agents for not mentioning protected items, yet an observer can infer a private fact from what the agent does. Since an observer learns a fact only if its view changes with the fact, we propose \methodfull (\method), which trains on twin worlds that differ only in the private fact. A frozen distinguisher scores each observer's view by its log-likelihood ratio for the true world, and paired GRPO trains the agent on task success minus this ratio. We prove that this objective controls the Bayes success of every observer on every channel. On shopping and messaging tasks \method removes the leakage that disclosure judges and query-level rewards miss, while the agent still completes its tasks.

---

### [234] StrucChunk: Structure-Aware Retrieval for Legal Document RAG

**链接**: https://arxiv.org/abs/2610.26313
**作者**: Surya Deep Singh, Ashutosh Tripathi and Gaurav Deep Singh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) can ground LLM outputs in domain-specific knowledge, but legal documents are hard: standard chunking fragments hierarchical argument structure, and generic embeddings struggle with both precise citation matching and semantic understanding. We propose StrucChunk (Structure Aware Chunking) with hybrid dense-sparse retrieval for hierarchically structured legal documents. It treats documents as directed acyclic graphs of provisions, preserves clause boundaries, resolves cross-references before embedding, and combines BM25 with BGE-M3 via Reciprocal Rank Fusion. We evaluate on five corpora, three legal traditions and two languages. StrucChunk reaches 100% boundary precision (vs. 7.7% for recursive splitting on CrPC), preserves 97.6% of documented cross-references (vs. 0%), and matches section coverage with 40.3% fewer chunks on GDPR. On LegalBench-RAG (6,858 query-passage pairs), it achieves Char-Recall@8 of 48.18% vs. 23.59% for the best baseline (+104%

---

### [235] Language Models are Lazy Poets: Creative Mode Collapse at Scale

**链接**: https://arxiv.org/abs/2610.24223
**作者**: Jacob A. Matthews and Sil Hamilton
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While aligned large language models (LLMs) can successfully complete many creative tasks, their outputs tend to be highly self-similar. Though solutions to this problem of "mode collapse" have been proposed, comprehensive large-scale surveys of the phenomenon in specific textual genres are still lacking. We address this gap through an extensive treatment of LLM mode collapse in poetry. Across 15 poetic forms, 248 subject matter tags, and 16 open-weight models, we generate over 1.1 million poems. To our knowledge, this constitutes the largest corpus of LLM-generated poetry to date. At million-poem scale, we find that LLM poetic vocabularies and rhyming abilities are substantial, but severely underutilized. In other words, LLMs are "lazy" poets: despite possessing large poetic inventories, LLMs over-rely on a small number of words, opening phrases, and rhymes. Further, we find that lexical homogenization differs across models and poetic forms, noting observed rhyming vocabulary is correl

---

### [236] Bayesian Model Discovery with Language Models: Closing the Loop between Hypotheses and Experiments

**链接**: https://arxiv.org/abs/2610.25747
**作者**: JooKyung Yuh, Byungmin Park, Eunseo Choi, Jinheon Baek, Junmo Cho, Kyu Hyun Choi 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific model discovery requires proposing candidate models of an unknown system and designing experiments that discriminate among them. However, LLM-based approaches typically rely on in-context learning to predict outcomes and select experiments, lacking explicit model evaluation to systematically guide hypothesis search, while Bayesian approaches enable principled model comparison but are confined to a predefined candidate set which results in limited search spaces. To this end, we introduce BMD, which closes the loop between LLM-driven hypothesis generation and Bayesian experimental design. Specifically, an LLM proposes model families, while a numerical engine fits their parameters, weighs them by model evidence, and averages their predictions. Then, BMD chooses the next experimental conditions by maximizing the joint expected information gain over families and their parameters, while feeding the updated beliefs and residual diagnostics back to the LLM to guide its next proposal

---

### [237] Bridging Exploration and Persona: Information-Directed Dueling for Test-Time Agent Personalization

**链接**: https://arxiv.org/abs/2610.24385
**作者**: Jie Mao, Pingchen Lu, Xiangyi Wang, Hengquan Huang, Shuang Qiu, Min Zhang 等 (7 人)
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective test-time personalization requires LLM agents to adapt to query-dependent user preferences from lightweight interaction. We study persona selection with binary comparisons between candidate responses as the online signal. We present ID-TAP, a scalable, IDS-inspired neural dueling-bandit framework for large discrete persona spaces. ID-TAP combines a query-conditioned neural utility model with a lightweight Bradley-Terry explorer, and transfers comparison evidence across related queries through similarity-weighted warm starts. The neural model shares statistical strength across queries while preserving query-specific scores, and efficient BT updates score hypothetical challengers. Across seven user-conditioned generation benchmarks under reference- and model-based preference simulators, ID-TAP achieves the strongest aggregate performance among the evaluated baselines within a fixed ten-round comparison budget. These results support information-directed challenger selection as a

---

### [238] Cross-Pollination Retrieval: Finding Transferable Ideas Across Fields in Scientific Literature

**链接**: https://arxiv.org/abs/2610.25678
**作者**: Seokwon Jung, Yerang Kim, Yejin Kim, Alexander Rubinstein, Arnas Uselis, Sangwoo Park 等 (8 人)
**来源**: cs.IR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many scientific advances come from cross-pollination, carrying an idea from one field over to a problem in another. Yet retrieving papers across fields remains underexplored, with existing benchmarks confined to a narrow range of fields. We study cross-pollination retrieval, the problem of identifying transferable ideas across research fields, and introduce CPR-Dataset, a large-scale dataset constructed by mining cross-topic citations. Its evaluation split CPR-eval has 1,300 queries in 26 fields, and its training split CPR-train has 10,573 pairs. On CPR-eval, the best of eleven existing retrievers reaches a Recall@10 of only 0.26, whereas an LLM reranker reaches 0.81. Standard contrastive fine-tuning on CPR-train raises Recall@10 to as high as 0.70. The gain carries over to domains held out from training and to analogy and reasoning-intensive retrieval. On AnaloBench, it raises nDCG@10 by up to 33% over the untrained retriever, whereas training on three existing retrieval datasets lowe

---

### [239] Game of Phones: Harnessing Game Theory and LLMs in 'Bot Wars' to Counteract Phone Scams

**链接**: https://arxiv.org/abs/2610.26781
**作者**: Nardine Basta, Robin Carpentier, Benjamin Zi Hao Zhao, Dali Kaafar
**来源**: cs.CR cs.AI cs.CL cs.GT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Phone scams impose substantial and growing costs on individuals and financial systems worldwide, yet existing countermeasures impose no resource cost on perpetrators. Strategic scam-baiting, in which automated agents engage scammers to deplete their operational capacity, offers a proactive alternative but requires dynamic strategy adaptation that static systems cannot provide. We introduce a game-theoretic framework enabling LLMs to learn effective counter-strategies through in-context experience without fine-tuning. The framework models scammer-baiter interactions as a two-player game with empirically grounded strategies and utility functions, using Nash equilibrium as a formal benchmark for evaluating learned behaviour. Across 300 simulated dialogues and three LLM architectures, adaptive strategy selection achieves 28.9-79.7% closer alignment to Nash equilibrium than non-adaptive baselines. The code and an annotated dataset of 300 dialogues with turn-level strategy labels and utility

---

### [240] Multi-author style detection with stylistic embeddings

**链接**: https://arxiv.org/abs/2610.24184
**作者**: Man-Ling Sung, Chak Fai Li, Damianos Karakos, Fred Bernardin, Brian Ulicny
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate the use of Large Language Models (LLMs) in multi-author style change detection. Using off-the-shelf LLMs or supervised fine-tuning solely within the target domain fails to yield effective features; for this reason, we propose cross-domain transfer learning with LLM-based embeddings fine-tuned for authorship verification. We fine-tune Mistral-7B embedding model and compare it with DeBERTa, used in the state-of-the-art (SOTA) systems in PAN-25 multi-author writing style analysis challenge. Results show that DeBERTa and Mistral excel in different user-generated text scenarios. We exploit this diversity by combining both embeddings, leading to more effective style change detection.

---

### [241] SPARC: Spoken Profile Authorship Recognition Corpus

**链接**: https://arxiv.org/abs/2610.25265
**作者**: Efthymios Tsaprazlis, Bowen Yi, Tiantian Feng, Junghwan Kim, David Jurgens, Shrikanth Narayanan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech anonymization has focused on the acoustic signal, leaving open how much speaker information the transcribed words themselves retain. In this work, we study pairwise speaker and demographic-attribute verification from transcribed speech. We introduce SPARC (Spoken Profile Authorship Recognition Corpus), a benchmark built from two podcast corpora comprising over 12,500 speakers, 1.5M quality-filtered utterances, and speaker-level inferred or source-provided labels for sex, age, and accent, and evaluate five attribution models and three LLMs on identity- and attribute-verification trials with episode- and metadata-based topic proxies. LLM adversaries distinguish same-speaker pairs from text alone. Attribute-label agreement is harder to verify, but LLMs perform sex- and accent-label verification above chance. Finally, releasing only short probe texts (50 words) degrades the strongest adversaries the most, offering a partial reduction in observed linkage.

---

### [242] HybridResearcher: Bridging the Structured-Unstructured Boundary for Deep Research Agents

**链接**: https://arxiv.org/abs/2610.24899
**作者**: Soyoung Yoon, Peiran Xu, Han Wang, Ruofan Wu, Xiaodong Yu, Feng Yan 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While LLM agents are increasingly capable of gathering and synthesizing evidence from a single homogeneous source, such as structured tables or unstructured data, real-world analytical questions frequently span heterogeneous sources. For example, answering one enterprise question may require both a result computed over an internal database and evidence found on the web. Recent evaluations on benchmarks like HybridDeepResearch show that even frontier agents struggle when evidence must cross this boundary. While these benchmarks have exposed the limitation, methodologies to explicitly teach cross-source reasoning remain absent. To address this, we introduce HybridResearcher, a 4B agent trained to bridge evidence across the structured and unstructured boundary. To build it, we synthesize cross-source bridge trajectories by starting with validated single-source tasks-such as existing text-to-SQL or web search queries-and fabricating the missing source around a bridge entity drawn from the 

---

### [243] Many Repairs, One Direction: Steering Code Models Toward Safer Cryptographic API Use

**链接**: https://arxiv.org/abs/2610.25133
**作者**: Tianhe Lu, Sakuna Harinda Jayasundara, Eric Spero, Ewan Tempero, Robert Biddle, Giovanni Russello
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cryptographic API misuse in large language model-generated code can compromise software security. While many existing approaches improve code security by modifying model parameters or inputs, how representation changes associated with different cryptographic API repairs can support a shared intervention for safer code generation remains underexplored. To investigate this, we construct 48,000 matched program pairs across four programming languages and ten cryptographic API misuse categories. Each pair changes a specified API decision while preserving the programming task. Subtracting the misuse program's internal representation from its secure counterpart's gives a repair vector. Across five models, comparisons of mean repair vectors reveal stronger organization by misuse category than by language. These category-specific patterns also support a shared intervention. We introduce CrypSteer, which extracts a shared direction by normalizing repair differences and selecting a principal comp

---

### [244] MemPrice: Online Memory Allocation via Adaptive Pricing for Long-Horizon Agents

**链接**: https://arxiv.org/abs/2610.24955
**作者**: Yiming Zong, Shiyuan Piao, Jiashuo Jiang, Fugee Tsung
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents face a fundamental allocation problem as interaction histories grow: which information to retain, how much context to devote to it, and at what granularity. Existing memory mechanisms largely focus on relevance, retrieval, or compression, leaving this allocation trade-off implicit. We introduce MemPrice, which treats active context as a shared resource and dynamically allocates it across memories and representation levels. MemPrice turns accumulated memory pressure into an adaptive price on context, encouraging detail only when its estimated retention value justifies the additional footprint. This pressure persists across memory refreshes, allowing the contents of memory to evolve while preserving long-run control over context usage. We show that irreversible compression can force linear worst-case regret against hindsight following its own memory trajectory, and introduce a same-state benchmark to evaluate allocation on MemPrice's realized memory states. MemPri

---

### [245] When Form Changes but Logic Doesn't: Building Logic-invariant LLMs through Logical Structure

**链接**: https://arxiv.org/abs/2610.25402
**作者**: Xuyuan Liu, Xinshuai Dong, Elynn Chen, Yujun Yan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have achieved strong performance across diverse reasoning tasks, yet it remains unclear whether this performance reflects an understanding of underlying logical structure or a reliance on shallow semantic cues. A key indicator of such understanding is whether models treat logically equivalent inputs consistently, producing the same predictions despite differences in expression. Through systematic evaluation on curated data, we show that even strong LLMs often fail this test: they do not consistently preserve predictions across logically equivalent inputs and generalize poorly to unseen logical forms. To address this limitation, we propose LoGIcal STructure-guided reasoning (LoGIST), a framework that guides LLM reasoning with explicit logical structure. LoGIST maps each input instance to a decision diagram, a directed acyclic graph that captures the underlying logical structure, and encodes this graph into a logical embedding that conditions the LLM's reason

---

### [246] GraphEvoResearcher: Graph-Aware Training-Free Self-Reflective Reasoning for Cost-Bounded Multi-Hop Question Answering

**链接**: https://arxiv.org/abs/2610.25978
**作者**: Suxing Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-hop question answering (QA) requires models to chain intermediate conclusions while remaining cost-aware. Existing training-free self-reflective protocols (generate -> critique -> revise) improve accuracy but operate on a flat token stream: revisions cannot identify which prior step is unreliable, and early stopping cannot exploit structural convergence. We introduce GraphEvoResearcher, a training-free protocol that lifts EvoResearcher's self-reflective meta-reward onto an explicit reasoning graph - nodes are intermediate conclusions/evidence and edges encode support, contradict, and depends_on. A graph-aware meta-reward combines correctness, efficiency, reflection, diversity, and four structural signals (connectivity, acyclicity, branch coverage, path convergence) to decide whether to revise, backtrack, or stop. A graph-convergence early-stop terminates when evidence branches converge on a single conclusion. On a real LLM (DeepSeek), over GSM8K, MATH, and BBH (n=50 each), GraphE

---

### [247] Who Speaks, Who Authorizes, Who Acts? Understanding Trust Boundaries in Multi-Agent LLMs

**链接**: https://arxiv.org/abs/2610.24298
**作者**: Junru Zhu, Xin Chen, Hang Lyu, Jiayue Meng, Muzi Li, Yifan Chen 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems exchange messages before acting through tools, but message delivery, signing authority, and tool-side enforcement are separate trust boundaries. We represent them as communication, authorization, and execution structures, and use the authority cut to characterize the smallest independently compromised signer coalition that can construct a policy-valid false-claim proof under stated assumptions. Controlled paired hidden-state studies reveal four distinctions. First, no fixed-message routing contrast across four models meets the prespecified large-effect criterion; when relays rewrite messages, executed false-state action rates vary by model and route configuration. Second, presented source-identity cues do not uniformly increase protected-action selection across three models. Third, on invalid-proof cases, Nemotron and Llama request protected actions in 52.1% and 54.2% of trials, respectively, yet a deterministic tool gate commits none: request-level and commitme

---

### [248] What Can't Jev Decide? Probing the Limits of One-Pass Decision Models

**链接**: https://arxiv.org/abs/2610.24929
**作者**: Wang Yang, Xinpeng Li, Yanyan Zhang, Chuang Ma, Shouren Wang, Jianzhe Wei 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jev and its open replicas choose among the options a caller supplies with a single forward pass, fast enough to decide inside an agent loop. We ask what such a model cannot decide, and find a simple limit: Jev cannot make a decision that an LLM makes only by writing out intermediate steps. On a benchmark that varies one factor at a time, Jev finds and selects records without error up to 20k tokens and 64 options, but once the answer depends on two or more updates of one user, accuracy falls, to 53-80% at sixteen updates, because similar records interfere. Given a stale summary of the state, Jev follows it. On real decision items graded by how many thinking tokens a reference LLM needs, Jev answers 97.5% of the items that one forward pass of that LLM solves, but only 74% of the others. Jev also does not know its limit: its confidence flags the errors it makes itself but not those it inherits from a stale input, and neither an explicit nor a trained hand-off option catches the latter. Th

---

### [249] CoTs remain monitorable when being unfaithful requires computation: Replicating and Extending the Necessity Effect Across Eleven Models

**链接**: https://arxiv.org/abs/2610.24495
**作者**: Arav Dhoot, Yixiong Hao, Zephaniah Roe
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While a LLM's chain of thought (CoT) is a promising approach to interpreting model outputs, prior work shows CoT's content does not always accurately reflect the reasoning process. Emmons et al. (2025) finds that models can follow a question hint without revealing so in its chain of thought, but when the hint is sufficiently complex the computation is forced into the CoT. This claim, however, has only been tested on Gemini models, and the datasets and code is closed source. We replicate their proxy task across eleven models from six families and find the necessity effect generalizes. Every model follows simple cues above a no-hint baseline, while concealed complex-cue following falls back near baseline for most models. We also extend the study from Emmons et al. (2025) to measure CoT-necessity and unfaithfulness across five cue families (four of them new) and three difficulty levels. The relationship between when CoT is necessary and unfaithfulness is task-specific and model-specific. 

---

### [250] Can It Actually Work? Synthesizing Functional CAD Mechanisms

**链接**: https://arxiv.org/abs/2610.26861
**作者**: Wenqian Zhang, Yangyi Huang, Zigeng Xu, Weiyang Liu, Zhen Liu
**来源**: cs.CV cs.CL cs.GR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While LLM agents can generate visually plausible CAD assemblies, these designs often fail to fulfill their intended physical functions. We study functional CAD design, a setting where agents interpret underspecified requests to construct and iteratively revise mechanisms that satisfy functional requirements in physical simulation. Verifying these requirements is nontrivial: different candidate mechanisms may realize the same function through entirely different components, controls, and operating sequences. To bridge this gap, we propose FunCAD-Harness, a framework that translates abstract requirements into candidate-specific physical tests and uses simulation feedback to guide design revisions. To systematically evaluate this capability, we introduce FunCADBench, a benchmark spanning 46 mechanism families with interdependent and multi-step operations. Experiments across frontier LLM agents show that FunCAD-Harness exposes subtle mechanical failures invisible to visual inspection, subst

---

### [251] Peer Pressure: Execution-Verified Co-Evolution of Attacker and Defender Populations for Code Security

**链接**: https://arxiv.org/abs/2610.24896
**作者**: Khushbu Pahwa, Yubin Ge, Daniele Bonadiman, Xiaofei Ma, Yi Zhang
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM code agents increasingly ship code with little oversight, yet defenders trained on static vulnerability datasets fall behind adapting adversaries. We co-train attacker and defender instead, and let execution decide every reward: an attacker (Red) edits a real repository and earns nothing unless its patch applies, builds, passes the tests, completes its development task and reproduces a real exploit in an isolated container, whose path also labels the entry point, the critical operation and the trace between them. Peer-Relative Policy Optimization (PRPO) makes both sides populations of LoRA adapters over one frozen base and credits each against same-role peers that faced an identical condition, placing the population inside the policy-gradient baseline rather than the opponent pool, with a tournament preserving diversity. Matching cancels the condition's difficulty: at equal coverage it is worth 2.3 points of balanced accuracy over a baseline computed on other conditions, and it mat

---

### [252] Agents' Last Doubt: Knowing When to Act and When to Step Back in Tool-Using Agents

**链接**: https://arxiv.org/abs/2610.24194
**作者**: Qisai Liu, Qingyue Jiao, Bangwei Guo, Wenxi Dai, Changyi Yang, Jiahe Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents repeatedly face decision points under uncertainty, choosing between autonomous action, additional information gathering, and human escalation. These decisions require balancing task success against interaction cost and the risk of irreversible errors. Learning to make these trade-offs is challenging because existing interaction trajectories record only the outcomes of actions taken, leaving the consequences of alternative actions unobserved. To address this gap, we construct a counterfactual dataset containing 3,115 action outcomes from 1,036 decision points in ToolSandbox. At each decision point, we execute each legal action and evaluate its downstream outcomes based on task completion, interaction cost, and irreversible errors. Using this dataset, we train SURE-Act, a controller that selects actions for a frozen backbone agent at inference time. Our experiments show that learning to rank alternative actions improves offline action-selection utility by 0.0309 ove

---

### [253] The World as Viewed by 136 Countries: An Open, Curated, Annotated, and Multilingual Dataset of 118 Million State Media Articles

**链接**: https://arxiv.org/abs/2610.24990
**作者**: Bryan Li, Samar Haider, Grace Kim, Fiona Luo, Jinqi Luo, Yuan Yuan 等 (9 人)
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> State media outlets often project their governments' narratives to target both domestic and foreign audiences. Because this content is plentiful and free to access, it appears widely in the web corpora that large language models (LLMs) are trained on and that retrieval systems draw from. However, the prevalence of state media in these corpora and its potential influence on LLM outputs remain largely unexplored. In this paper, we introduce WorldStateMedia, an open dataset of 118 million state media articles from 136 countries in 114 languages. We extract these articles from existing pretraining corpora and annotate each outlet with level of state control from State Media Monitor. Using WorldStateMedia to audit these corpora, we find that, in English web crawls, the share of state media pages from editorially controlled (vs. independent) outlets rose from 39% in 2013 to 93% in 2025. In several low-resource languages, state media make up a substantial share of all web data, such as 17.8% 

---

### [254] ZeroDSS: Semantic Segmentation from Class Names Alone

**链接**: https://arxiv.org/abs/2610.24405
**作者**: Tian Ming, Marzi Heidari, Yuhong Guo
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic segmentation depends heavily on real images with pixel-level annotations, making dense supervision a major obstacle to deployment in new domains. We study task-specific data-free semantic segmentation, where training uses generic pretrained generative priors but has access to no target-domain images, masks, or captions--only a predefined category set. We introduce Zero-Data Semantic Segmentation (ZeroDSS), a feedback-driven approach that treats synthetic supervision as an adaptively controllable training distribution rather than a direct surrogate for real data. ZeroDSS constructs a semantically structured prompt distribution through LLM-guided compositional generation and adaptive class rebalancing, then converts the prompts into image-mask pairs using diffusion attention. Its feedback-driven distribution refinement consists of a two-phase closed-loop training procedure with a single loop-back step. In Phase I, a segmenter is trained using confidence-weighted supervision and 

---

### [255] Symbolic Constraint Agents: Mining Formal Tool-Call Constraints to Prevent Agent Errors

**链接**: https://arxiv.org/abs/2610.25552
**作者**: Jinu Lee, Shraddha Barke
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Symbolic constraints (programmatic, deterministic checks for tool calls) enable deterministic verification of LLM agents' tool calls, but existing approaches primarily enforce predefined safety policies rather than tool dependencies in complex tool environments. We explore whether symbolic constraints can be mined from environments and observations beyond predefined policies, and whether they can improve end-to-end task performance. We present Symbolic Constraint Agents (SCA), a framework that mines symbolic constraints from API documentation, refines them against execution traces, and checks the agent's tool calls with an SMT solver at runtime. A violation triggers a natural-language warning or, when the valid replacement is uniquely determined, an automatic repair. On AppWorld, refinement raises error-detection F1 from 37.0 to 58.3 on GPT-5.5 traces and from 39.3 to 61.9 on Qwen3.5-27B traces. At runtime, repair raises GPT-5.4-mini's task success by 5.4 points under a 40-call budget 

---

### [256] Bridging Concepts: Multi-Agent Reasoning over Scientific Concept Graphs for High-Impact Research Prediction

**链接**: https://arxiv.org/abs/2610.25281
**作者**: Donggyu Yoon, Minsung Hwang, Juneha Baek, Donghyuk Shin, Joyce Jiyoung Whang
**来源**: cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Within a research community, new topics often emerge when previously unconnected concepts are first studied together. We construct scientific concept graphs (SCGs)--domain knowledge graphs whose nodes are fine-grained research concepts extracted from paper text by LLMs and whose edges capture their co-occurrence in papers--and study the task of forecasting high-impact concept pairs, i.e., discovering concept pairs that are currently unconnected but will have high impact when connected. To this end, we introduce new benchmark datasets constructed from CIKM, KDD, and SIGIR conference papers, with varied prediction settings, including impact forecasting for emerging concepts unseen during training. We propose MiroGraph, a Multi-agent reasoning framework with scientific concept Graphs, in which a feature designer agent designs predictive features for a given concept pair from structural, semantic, and trend perspectives, and then three LLM agents compute the actual feature values from the 

---

### [257] Toward Agentic Retrieval-Augmented Generation for Enterprise Retail Workflows over Heterogeneous Data Sources

**链接**: https://arxiv.org/abs/2610.25096
**作者**: Jeonghwan Choi, Jibin Hwang, Hayoon Park, Hyeonjae Cheon, Hwanjun Song
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise retail workflows require agents to chain evidence across heterogeneous sources, from structured product and order records to unstructured inquiries and reviews, yet existing agentic RAG benchmarks rarely capture this challenge. To enable controlled evaluation of such workflows, we introduce RetailBridge, a compositional retail benchmark built from persona-driven simulations. Its questions are constructed by linking entities and intermediate answers across heterogeneous sources, requiring agents to identify the relevant sources, carry evidence between them, and produce a grounded answer. To systematically evaluate LLMs on these retail workflows, we develop RetailRAG, a retail-aware framework equipped with auto-schema briefing, source-routed plan chaining, and diagnostic plan revision. RetailRAG consistently outperforms existing agentic RAG baselines across all evaluation axes, serving as a strong reference system for assessing LLM agents on retail workflows. On RetailBridge, 

---

### [258] Modeling Human Behavior in the Prisoner's Dilemma with Large Language Models

**链接**: https://arxiv.org/abs/2610.23860
**作者**: Raina Gao, Tristan Raffo
**来源**: cs.CL cs.GT
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Prisoner's Dilemma has long served as a foundational framework for studying human decision-making and cooperative outcomes across social scenarios, yet human behavior consistently deviates from predictions of fully rational economic theory. Previous works have studied human and LLM outcomes in the Prisoner's Dilemma; however, these studies have lacked at least one key feature: a memory component for LLM agents, accessible open-source models, or comparison against empirical human data. This project investigates whether open-source LLMs, TII Falcon 7B Instruct, Google Gemma 7B, Meta Llama 3.1 8B Instruct, Microsoft Phi Mini MoE Instruct, and Qwen 2.5 7B Instruct, can model human cooperation patterns in repeated Prisoner's Dilemma games, while examining how an LLM's knowledge that its opponent will be shuffled affects its decisions. Using a standardized prompting framework, we simulated interactions in two trial types: a fixed-partner setting where both agents retain memory, and a shu

---

### [259] AuDQ: Auditable Data Quality through Agentic Rule Discovery

**链接**: https://arxiv.org/abs/2610.26031
**作者**: Jacopo Biggiogera, Nicolas Colombo, Krati Saxena, Bhaskarjit Sarmah, Stefano Pasquali
**来源**: cs.AI q-fin.CP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-stakes tabular pipelines rely on scattered, static quality checks that are hard to evolve and audit against policy intent. Regulated domains particularly suffer as the LLM-era automation raises expectations for traceability and accountability. We propose a vision for an ontology-grounded, repository-native data quality layer in which rules are first-class artifacts: versioned, provenance-linked to governance texts, and re-playable through immutable execution traces. As a first step toward validating this vision, we present a concrete implementation of its agentic rule-discovery core with two rule acquisition modes (Full-Agentic and Guided) and a human-in-the-loop (HITL) review interface. We define an evaluation framework and run experiments addressing whether our fully autonomous, divide-and-conquer agentic rule discovery produces rules of the same quality and diversity as those specified by a human expert, reporting preliminary results on two real world industry datasets in the f

---

### [260] CoMem: Learning to Anticipate Failures from Retrieved Experience

**链接**: https://arxiv.org/abs/2610.25790
**作者**: Yun Shen, Ming Shen, Tianjun Yao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reflection lets LLM agents improve from their own attempts, but the memory it builds is local to a single task, so an agent reflecting on its own tends to revisit the same explanation for failure. Cross-task reflective memory addresses this in two forms: retrieved memory keeps past experience explicit and looks up related cases, which is specific but bounded by the bank, and parametric memory internalizes experience into parameters, which generalizes but is grounded in nothing beyond the task description. When both are used, existing agents combine them additively, feeding their outputs to the solver side by side, so retrieved experience never changes what the learned memory produces. We introduce CoMem (Compounding Memory), which makes retrieved experience an input to the learned memory itself, at training and at inference. The agent builds a bank of its own successful and failed reflections, learns from retrieved cases to write failure hypotheses, candidate explanations of how an att

---

### [261] Federation over Harness

**链接**: https://arxiv.org/abs/2610.24007
**作者**: Dixi Yao, Tahseen Rabbani, Tian Li
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM-powered agents increasingly improve through experience sharing, where distributed agents distill local reasoning experience into reusable knowledge, such as a shared insight library. Existing approaches, however, still heavily rely on manually designed prompts and workflows that determine both how local agents extract useful reasoning traces and how a central/global agent aggregates them to obtain common patterns and insights. We propose Federation over Harness (FoH), a framework that automatically evolves the harness for both local and global components in this distributed multi-agent reasoning pipeline. A server agent evolves the client harness for task solving and self-reflection while, at the same time, evolving its own harness for aggregating distributed reflections, maintaining shared knowledge, and updating subsequent client harnesses. Importantly, FoH requires no extra validation signals, such as ground-truth labels or validation data, during evolution; it learns sol

---

### [262] Divergence based Ranked Preference Alignment for LLMs

**链接**: https://arxiv.org/abs/2610.25588
**作者**: Rajdeep Haldar, Yue Xing, Qifan Song
**来源**: cs.LG stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Alignment of large language models typically relies on pairwise preference feedback, though ranked feedback can capture more comprehensive information across multiple responses within a single annotation. However, ranked-preference alignment is underexplored in practice compared to simpler pairwise approaches, potentially resulting in suboptimal behavior. Concurrently, recent research has conceptualized large language model alignment objectives as divergence estimators between aligned (preferred) and unaligned (less-preferred) response distributions, resulting in a family of objectives with an interpretable theoretical foundation and strong empirical performance. This work unifies these perspectives by introducing $f$-RPO, a $f$-divergence objective for ranked preference optimization that extends divergence-based alignment to ranked feedback and recovers pairwise preference alignment as a special case. Our theoretical analysis establishes rank-order consistency, showing that $f$-RPO pr

---

### [263] Maestro: Agentic Formal Proof Development by Coordination

**链接**: https://arxiv.org/abs/2610.25920
**作者**: Haoyu Li, Zeren Shui, Yuhao Zhang, Ferhat Erata, Benjamin Mikek, Murali Krishna Ramanathan 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lean is increasingly used to verify mathematical proofs and software produced by LLM agents, but writing formal proofs remains hard. Existing prover systems take a divide-and-conquer approach that recursively decomposes hard proof obligations into easier lemmas and splits again any lemma that resists proof. However, a lemma can resist proof for different reasons, including insufficient guidance, a false statement, or a flaw in the decomposition that produced it. Existing systems cannot tell these apart as a failed attempt reports little beyond its failure, and responses are confined to the failing node without considering the rest of the proof or revising the plan above it. The system may thus keep decomposing obligations along a flawed proof direction until the budget runs out, causing the whole proof attempt to fail. We introduce Maestro, a Lean prover harness that handles failures through global coordination. Provers report why they failed, not just that they failed, and a coordinat

---

### [264] UpLoop: Upcycling Large Language Models with Gated Loop

**链接**: https://arxiv.org/abs/2610.25004
**作者**: Tieyuan Chen, Huabin Liu, Yingtao Zhang, Shijie Li, Tengyu Pan, Weiyao Lin 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Looped large language models trade parameter storage for recurrent computation, but most are trained from scratch. In practice, pretraining with looped depth is expensive, making post-training upcycling of a pretrained non-looped LLM an attractive alternative. We introduce \textbf{UpLoop}, a post-training recipe based on \emph{layer-wise} recurrence. Instead of looping a whole model or a middle block, UpLoop loops each selected layer locally, preserving the pretrained depth hierarchy and avoiding feature-space mismatch. To make loop execution useful, we add hidden-wise gates on the attention and MLP residual branches, so later loops act as progressive refinements rather than redundant rewrites. Empirically, UpLoop breaks the commonly observed saturation at two loops ($R=2$) in prior looped models. Starting from Qwen3-4B Base and applying SFT, UpLoop improves the average accuracy across 20 benchmarks by 6.17\% at $R=3$. We use $R=3$ as the main setting for the best accuracy--cost trade-

---

### [265] FinSafeGuard: A Quality-Driven Synthetic Dataset for Financial AI Safety

**链接**: https://arxiv.org/abs/2610.26066
**作者**: Joseph Thomas Thacil, Reetu Raj Harsh, Krati Saxena, Bhaskarjit Sarmah, and Stefano Pasquali
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating high-quality synthetic datasets at scale remains a fundamental challenge for training specialized AI systems in data-scarce domains. We present a comprehensive methodology that produces 14.3 million quality-filtered synthetic training examples from a structured taxonomy of 632,000 scenario specifications. Our four-stage pipeline ad- dresses critical challenges in synthetic data quality, diversity, and realism through: (1) systematic pre-generation research establishing optimal generation parameters via diminishing returns analysis, (2) conditional auto evolution mechanisms that remediate low-diversity batches during generation, (3) a two-layer semantic deduplication architecture combining lexical and embedding-based methods, and (4) LLM-as-Judge quality evaluation filtering samples based on behavioral correctness and tuple fidelity. Empirical analysis across three domains (Banking, Insurance, Financial Services) demonstrates domain-specific deduplication patterns ranging fro

---

### [266] Hippo: Training-Free Agent Self-Evolution via Hippocampal Replay

**链接**: https://arxiv.org/abs/2610.24453
**作者**: Yutong Song, Jiang Wu, Yuxuan Ren, Tony Qin, Baoyuan Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Motivated by recursive self-improvement (RSI), we study how LLM agents can learn through external memory without updating model parameters. Extracting useful experience from a single attempt is difficult: flawed reasoning can produce success, while poor execution can obscure a sound strategy. Preserving its value over time is also difficult: our accumulation baseline without consolidation initially improves but eventually performs below a no-memory baseline. Our key idea is to compare attempts at the same task to identify reusable decisions and refine when they apply. We introduce Hippo, a memory framework inspired by selective hippocampal encoding and replay that learns from these comparisons when shortcomings are diagnosed. It compares the resulting experience with existing memory to merge overlaps and resolve conflicts through explicit applicability conditions. This allows prior guidance to be revised without storing every lesson as a separate entry. Experiments on SWE-bench Verifie

---

### [267] WAQS: Weight Absorption for Quadratic Probing and Affine Steering

**链接**: https://arxiv.org/abs/2610.24367
**作者**: Ding Zhu and Mohammad Mahdi Khalili
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering provides a lightweight alternative to fine-tuning for controlling large language model behavior. Existing methods, however, often face a trade-off between efficiency and expressiveness: fixed steering vectors incur negligible inference overhead but cannot adapt to the current model input, whereas input-dependent nonlinear interventions provide greater flexibility at additional runtime cost. We introduce \textbf{WAQS} (\textbf{W}eight \textbf{A}bsorption for \textbf{Q}uadratic probing and affine \textbf{S}teering), a framework that obtains state-dependent steering, without additional inference-time computation. WAQS models a concept with a quadratic probe, whose gradient yields an affine, activation-dependent steering direction. We show that this affine intervention can be folded exactly into adjacent linear transformations through an offline weight update. Moreover, we prove that quadratic functions form the maximal class of smooth concept scores whose gradient-base

---

### [268] SPIDES: Information-Flow Control for Browser Agents

**链接**: https://arxiv.org/abs/2610.24277
**作者**: Egor Zverev, Juhee Kim, Leon Trampert, Boris K\"opf, Aashish Kolluri, Shruti Tople 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Browser agents automate complex workflows by reading and acting on arbitrary page content, but this flexibility exposes them to prompt injection attacks and unintended data exfiltration. Recent work argues that LLM-driven browser agents erode traditional web security boundaries such as the Same-Origin Policy (SOP) by acting across origins with the user's authority and no built-in isolation. We argue that restoring SOP is neither sufficient (a same-origin public sink can leak private data) nor necessary (legitimate tasks require authorized cross-origin flows) for protecting the security of users. We propose SPIDES, which instead enforces information-flow control by gating primitive browser actions such as typing, clicking and navigating on labels propagated from element-level HTML confidentiality and integrity annotations. Untrusted and confidential content is masked from the agent's context, while policies block unauthorized flows, providing security guarantees against both prompt inje

---

### [269] SLA-LENS: From Classroom Transcripts to CSLA-Informed and Evidence-Linked L2 Interaction Analytics

**链接**: https://arxiv.org/abs/2610.24259
**作者**: Nemika Tyagi, Olga Kellert, Phanos Kareen, Nelvin Licona-Guevara
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What happens after a learner makes an error, and how does the instructor's response shape the next turn? Investigating these exchanges across classrooms requires context-sensitive annotation that is difficult to scale manually. We introduce SLA-LENS, an end-to-end LLM-assisted framework that connects classroom transcripts to structured pedagogical annotations and evidence-linked descriptive analytics. Grounded in interactionist Second Language Acquisition (SLA) theory, its annotation schema captures second language learner errors, pedagogical functions, and uptake or repair while accounting for speaker roles, conversational context, and hierarchical labels. We apply the framework to 40 authentic online L2 Spanish classroom transcripts comprising over 21,000 sentence-level instances. We evaluate proprietary and open-weight LLMs, including task-specific QLoRA adaptation, using expert-reviewed gold annotations, held-out silver data, and metrics sensitive to different types of annotation e

---

### [270] Factorization-Guided Training and Inference for Diffusion-Drafted Speculative Decoding

**链接**: https://arxiv.org/abs/2610.23935
**作者**: Jiakun Fan, Min Xiao, Qiang Wang, Neiwen Ling, Zhichao Liu, Zhihao Jia 等 (8 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference through parallel verification of tokens proposed by a drafter. Diffusion drafters further parallelize proposal generation, but greater proposal capacity or higher mean accepted tokens (MAT) need not yield higher throughput. Because verification accepts only a consecutive prefix, early rejections can render later correct predictions ineffective, limiting MAT gains, while even higher MAT may not improve throughput if per-round latency increases. We introduce DScout, which uses two complementary factorizations to guide diffusion drafter training and inference for higher throughput. For training, DScout factorizes position-wise loss into inclusion, weighting, and prediction loss. This guides the design and combination of mixed-horizon training, intra-block unmasking, and acceptance-weighted loss to align supervision with prefix acceptance and improve MAT. For inference, DScout factorizes throughput as the ratio of MAT to per-r

---

### [271] Trust the Edge, Doubt the Arrow: Auditing Validation Signals for Text-Mined Clinical Causal Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.24390
**作者**: Su Lan, Shicheng Zhou, Yiqi Wang, Yanming Zhu, Xuefei Yin, Alan Wee-Chung Liew
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clinical causal retrieval-augmented generation systems increasingly use knowledge graphs (KGs) mined from notes, yet extracted assertions remain candidates that require audit for patient-level EHR support and direction. We construct a directed candidate graph from 328,839 MIMIC-IV discharge summaries using LLM extraction and UMLS normalization, and evaluate three signals against SemMedDB: within-admission co-occurrence lift, cross-admission diagnosis-coding temporal precedence, and literature corroboration. Lift filters unsupported co-mentions and provides useful EHR support, but not causal proof. Coding order is a weak direction signal: among the 686 candidates where it commits, it reaches 54.2% agreement with SemMedDB, below the extractor's 69.4% on the same subset. Literature corroboration supplies independent direction evidence but covers only 30.4% of candidate relations. A MIMIC-III replication yields the same pattern: extractor direction remains stable (70.5%), whereas coding-or

---

### [272] Write Once, Check Many: Reusable Ledgers for Post-Hoc Policy Compliance Auditing of Agent Trajectories

**链接**: https://arxiv.org/abs/2610.24483
**作者**: Ashwin Nagarajan, Gursimran Panesar, Alicia Yang, Mona T. Diab, Virginia Smith, Aashiq Muhamed
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Auditing LLM agents against policies is critical to ensure safety but requires rereading long trajectories once per policy. Can we instead record each trajectory once and reuse that record for policies not known in advance? We propose write once, check many, a framework in which a writer model converts each agent trajectory into a policy-independent ledger of the agent's actions and outcomes. A reader then checks each new policy against the ledger alone, without access to the original trajectory. On 900 trajectories from SHADE-Arena, $\tau$-bench, and $\tau^2$-bench, we show that a 12B reader of narrative ledgers can either match or in fact achieve higher AUC than the same 12B model reading full trajectories. On SHADE-Arena policies that combine several facts, our approach outperforms a 31B model reading the trajectory (.777 vs. .713 AUC). When checking eight SHADE-Arena policies separately, ledgers use about $5\times$ fewer tokens, including the cost of writing them. A deeper analysis

---

### [273] Truncated Reasoning Under a Budget: Evaluating System-1 Models as Decision-makers

**链接**: https://arxiv.org/abs/2610.25768
**作者**: Zhongyin Wang, Zhaoqian Xue, Junting Mu, Haozheng Liu, Ye Yuan, Haolun Wu 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) often generate more reasoning tokens than needed. Limiting the reasoning budget reduces cost, but forcing an answer from an incomplete trace can hurt accuracy. System-1 decision models select among candidate options without producing a reasoning response. We evaluate Jev as a decision reader of truncated reasoning across seven LLM reasoners and five multiple-choice benchmarks (35 pairs). Jev achieves higher mean accuracy than forced answering at tested budgets from 500 to 16,000 tokens, including the estimated costs of reasoning and answering. At a 1,500-token budget, it improves accuracy by 4.1 pp overall and 8.6 pp on truncated questions, with significant gains in 17 pairs under Holm-corrected bootstrap tests. Offline replay estimates 34.5% of the full-run cost, with a 1.13 pp accuracy loss. A policy selected on training folds saves 71.3% of the estimated full-run cost on held-out folds, with a 0.58 pp accuracy loss. We also find that Jev shows strong que

---

### [274] Does AI-Assisted Development Homogenize Software? An Empirical Study of Code Similarity, Quality, and Evolution

**链接**: https://arxiv.org/abs/2610.24093
**作者**: Luciano Marchezan, Romain Lefeuvre, Kevin Delcourt, Benoit Combemale, Houari Sahraoui
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-assisted software development is evolving from interactive LLM assistance toward agentic systems that autonomously perform software engineering tasks, yet the effects of this shift remain insufficiently understood. We present an empirical study of 50 long-lived Java and Python open-source projects across three eras: pre-LLM, potentially LLM-assisted, and detected agentic development. Using snapshots from Software Heritage, we examine code similarity, software quality, and software evolution. Similarity is measured semantically through embedding-based cosine similarity and syntactically through CodeBLEU*. Quality is assessed with SonarQube metrics covering maintainability, complexity, reliability, and security. Evolution is characterized by annualized growth rates of LOC, functions, classes, files, and statements, and by commit activity in the three months preceding each snapshot. Results show no consistent evidence of increased similarity as semantic and syntactic similarity decreas

---

### [275] Joint, Decoupled, or Agent: When Each Multimodal Alignment Paradigm Wins

**链接**: https://arxiv.org/abs/2610.24108
**作者**: Yi Fang, Gaurav Srivastava, Sirui Ding, Xuan Wang
**来源**: cs.AI cs.CL cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Jointly pretrained multimodal encoders are a common way to combine modalities, while alternatives integrate their information during downstream training or inference. When does each approach win? We compare three paradigms, instantiated with public checkpoints, across 16 paired datasets in five domains and multiple training-label budgets. JOINT trains a fusion head on frozen, jointly pretrained encoders. DECOUPLED trains a fusion head on frozen, independently pretrained encoders. AGENT gives a frozen LLM task instructions, labelled examples, available sample text, and supervised unimodal readouts. No paradigm dominates the complete 144 dataset-budget combinations: DECOUPLED wins 54, JOINT 44, and AGENT 46 by mean utility. ScienceQA, MELD, and MetMeme shift from AGENT to fusion as supervision increases. Between the fusion paradigms, JOINT leads on four of five QA datasets across all evaluated budgets, while higher unimodal 5-NN accuracy is associated with a relative shift toward DECOUPL

---

### [276] Multilingual Voicemail and Answering Machine Detection via Pretrained Audio Embeddings and Gradient Boosting Machines

**链接**: https://arxiv.org/abs/2610.26100
**作者**: Kemal Altwlkany, Muamer Paric
**来源**: cs.SD cs.LG eess.AS
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Answering machine detection (AMD) is a fundamental task in telephony that classifies whether an answered call is picked up by a human or a voicemail (machine). Despite its widespread use across cloud communication platforms, existing approaches rely on proprietary systems with undisclosed architectures, or require computationally expensive models that cannot operate in real time. We propose a lightweight AMD system that combines pretrained audio embeddings with gradient boosting machines, trained to prioritize the correct detection of human-answered calls. We evaluate seven models across two datasets: three models that we propose, a proprietary industry model, two prior academic approaches, and a large language model baseline that relies on automatic speech recognition. Furthermore, we release OpenAMD, the first publicly available AMD dataset comprising of more than 500 recordings in 7 languages. Our best model achieves the highest precision across both datasets while maintaining low i

---

### [277] Fundus-R1: Training a Fundus-Reading MLLM on Public Data

**链接**: https://arxiv.org/abs/2604.08322
**作者**: Yuchuan Deng, Qijie Wei, Kaiheng Qian, Jiazhen Liu, Bangxiang Lan, Qingwei Shen 等 (9 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [278] MLLM-Guided Autonomous Object Detection for Open-World Understanding

**链接**: https://arxiv.org/abs/2507.10844
**作者**: Furkan Mumcu, Michael J. Jones, Anoop Cherian, Yasin Yilmaz
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [279] PharmaVision: A Multimodal Framework for Medicine Identification and Expiry Detection on Indian Pharmaceutical Packaging.

**链接**: https://scholar.google.com/scholar_url?url=https://openurl.ebsco.com/contentitem/gcd:197746560%3Fsid%3Debsco:plink:crawler-gcd%26id%3Debsco:gcd:197746560%26crl%3Dc%26jrnl%3D09657452&hl=zh-CN&sa=X&d=14421746984805226657&ei=l_vWas65EZfUieoPhs6tkQ8&scisig=ACTRDVFliydMWCnRCQ9h62OgaT2Y&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=1&folt=kw-top
**作者**: A Dave, J Panchal, P Laxkar, J Mehetre, F Jujara… - European Journal of …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> (π(V, T) ⊕ I; θ) (1) where π(·) is the prompt-template function (Appendix A), ⊕ denotes multimodal context injection of the encoded candidate list and OCR fragments into the MLLM context window, and θ represents the frozen MLLM

---

### [280] A multi‑modal recognition method for building structural materials integrating structured text description and adaptive decision weighting

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s44163-026-02462-y&hl=zh-CN&sa=X&d=9358717144381983275&ei=l_vWas65EZfUieoPhs6tkQ8&scisig=ACTRDVF2e3N4RJYfYPEwal4l-IcY&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=5&folt=kw-top
**作者**: M Ma - Discover Artificial Intelligence, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> reviewers manually verified all MLLM outputs. We conducted a manual review of the descriptions generated by MLLM . Since there was no … The proposed prompt strategy guides the MLLM to strictly follow the five dimensions of “surface features

---

### [281] Multimodal Generative AI in Education: A Systematic Literature Review of Tasks, Modalities, and Methods

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11739440.pdf&hl=zh-CN&sa=X&d=12790480924755888780&ei=l_vWas65EZfUieoPhs6tkQ8&scisig=ACTRDVEk7-3oBFLUU0_xWmKCWxfM&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=2&folt=kw-top
**作者**: S Meliana, DP Lestari, BR Trilaksono - IEEE Access, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> This review maps where educational MLLM work is concentrated and identifies speech/audio-rich … This growing diversity indicates that educational MLLM research is expanding from static … These studies indicate that educational MLLM

---

### [282] From Label Priors to Task Evidence: Efficient Long-Video Frame Selection via Bayesian GRPO

**链接**: https://arxiv.org/abs/2610.25418
**作者**: Shuochen Chang, Bingjie Gao, Qingyang Liu, Qianli Ma, Yibo Miao, Haonan Zhao 等 (10 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) face significant scalability challenges in long-video understanding due to quadratic attention complexity and context window constraints. Existing retrieval-based approaches typically rely on supervised learning from static keyframe annotations. However, these label priors often fail to align with the actual information required by downstream MLLMs for complex reasoning, creating a misalignment between the training target and inference needs. To bridge this gap, we propose a probabilistic framework that reformulates frame selection as latent-variable inference. We first initialize a lightweight policy using supervised learning to capture general visual saliency. Then, we treat a frozen MLLM as a task environment and use its answer likelihood as dense task evidence to refine the policy via Bayesian Group Relative Policy Optimization (GRPO). Within this formulation, the negative log-likelihood (NLL) over ground-truth answer tokens provides a princ

---

### [283] Artificial intelligence applications in building computational transformation: A systematic review from cradle to use

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S3051244126000104&hl=zh-CN&sa=X&d=16944780616742351563&ei=l_vWas65EZfUieoPhs6tkQ8&scisig=ACTRDVG0On9FKEDWvWoxvFh7wtjL&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=3&folt=kw-top
**作者**: D Zhuang, Y Jia, Y Leng, C Guo, F Xu, W Zhang… - EBES Sustainable Building 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Based on these findings, this paper further proposes a prospective MLLM -driven conceptual framework for organizing future building life-cycle computational strategies. Grounded in unified representation, the framework outlines possible roles

---

### [284] Multimodal Decoupling for Diversified Recommendation through Semantic and Structural Shaping

**链接**: https://arxiv.org/abs/2610.26024
**作者**: Changran He, Jiaming Wei, Jianghong Ma, Tianjun Wei, Haijun Zhang, Xiaofeng Zhang
**来源**: cs.IR cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recommender systems often suffer from over-concentrated results when optimized for accuracy, limiting recommendation diversity. While diversity has become an important objective, existing methods still face fundamental limitations from both semantic and structural perspectives. On the one hand, multimodal recommender systems provide rich semantic signals, yet are often treated as auxiliary to ID embeddings, leading to ineffective semantic utilization for diversity. On the other hand, the accuracy--diversity trade-off persists during training, where accuracy gains often come at the cost of diversity. We show that this phenomenon is fundamentally governed by both the structural properties of learned representations and the dynamics of optimization. To address these challenges, we propose MOSS, a unified framework for multimodal decoupling through semantic and structural shaping. Specifically, we first introduce an MLLM-based Decoupled Feature Extraction module to disentangle multimodal c

---

### [285] Visual Scaffolding: Toward Native Multimodal Reasoning

**链接**: https://arxiv.org/abs/2610.25247
**作者**: Run Shao, Zhaoyang Zhang, Ziyu Li, Linrui Xu, Ji Qi, Xiu Su 等 (9 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The success of chain-of-thought (CoT) in complex reasoning can be attributed to a textual scaffolding effect: explicit intermediate results can be examined, reused, and composed to support subsequent reasoning, much as scaffolding supports a building under construction. However, mainstream multimodal LLMs lack an equivalent scaffold for visual distinctions that are difficult to express in concise verbal descriptions. We therefore ask: Can native visual representations become first-class citizens alongside language, providing a visual scaffold for reasoning? We define native multimodal reasoning as reasoning in which native visual representations and language jointly carry reusable intermediate states. As a concrete implementation, the visual scaffolding mechanism we proposed lets the MLLM autonomously initiate a retrieval action at any reasoning step. A lightweight retriever selects native visual features, which are then incorporated directly into the evolving CoT and remain available 

---

### [286] Detecting and Grounding Semantic-Coordinated Multimodal Manipulations: A Dataset and Baseline

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11738803/&hl=zh-CN&sa=X&d=8600309125741519932&ei=l_vWas65EZfUieoPhs6tkQ8&scisig=ACTRDVF0I6ip-rzjuVcBYbAPln1m&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=4&folt=kw-top
**作者**: Y Wang, J Shen, J He, Y Wu, S Tang, L Cheng 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To counter these sophisticated forgeries, we propose 15 RamDG++, a Retrieval-Augmented MLLM -based framework for 16 unified detection and grounding. RamDG++ incorporates two 17 new mechanisms: (1) Celebrity-News Cross-Source Contrastive

---

### [287] NeuroAct: Advancing EEG Analysis and Decoding via Dual-Loop Autonomous Research

**链接**: https://arxiv.org/abs/2610.25211
**作者**: Wei Xiong, Jiangtong Li, Han Zhao, Linxiao Yang, Jie Li, Changjun Jiang
**来源**: cs.LG cs.AI eess.SP
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG analysis and decoding underpin brain-computer interfaces, cognitive assessment, and sleep monitoring. Fixed pipelines and reward-driven search do not explicitly determine how signal structure, representations, predictor behavior, and training dynamics contribute to performance or generalization gaps, leaving intervention choice underdetermined. We introduce NeuroAct, an autonomous research agent framework for EEG analysis and decoding. NeuroAct implements dual-loop autonomous research across EEG foundation models, task-specific predictors, and model combinations. In an inner loop, research, development, and review roles use evidence on signal structure, representations, predictor behavior, and training dynamics to test hypotheses, select analyses or interventions, and refine candidates using performance, stability, and cost feedback. An outer loop distills outcomes into conditional, testable recommendations with task and model conditions, then validates and revises them on subseque

---

### [288] Beyond EEG synchronization: methodological considerations in BOSSFRONT2

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s00406-026-02414-8&hl=zh-CN&sa=X&d=1803481080697972427&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVF_islMC1bjD7Ws5rvcTJrs&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=4&folt=kw-top
**作者**: S Singh, A Tripathi - European Archives of Psychiatry and Clinical …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In addition to the difference in EEG triggered versus standard stimulation, the two groups … effect of the EEG , since several stimulation parameters differ between both treatment groups. … This information would be a significant demonstration of

---

### [289] Context-Aware Topological Distillation Graph Network for Asymmetric EEG-Eye Movement Emotion Recognition

**链接**: https://arxiv.org/abs/2610.26084
**作者**: Peijun Shi, Xiujin Zhu, Zhenguo Lao, Chee-Onn Chow, Wei Ru Wong, Zhen Liu 等 (7 人)
**来源**: cs.CV cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG-eye movement emotion recognition can support mental-health monitoring and adaptive interfaces, but most fusion models treat the two signals as parallel features, classify each window alone and degrade when eye data are lost. We propose the Context-Aware Topological Distillation Graph Network (CTD-GNet), in which EEG features form the nodes of an electrode graph, and eye movements and preceding windows modulate its edges, nodes and readout, the edges through electrode-specific prompts. Bidirectional distillation of the graph, node relations and predictions couples this multimodal teacher with a single-window EEG student, improving the teacher and aligning the two graphs 35-fold. In leave-one-subject-out tests on SEED and SEED-IV against 17 baselines, CTD-GNet has the highest mean accuracy, 84.91% and 76.17%, significantly above 9 and 6 of 13 eye-based baselines after Holm correction, the smallest cross-subject spread among multimodal models and the highest worst-subject accuracy. It

---

### [290] Resting EEG as a Condition-Dependent Ageing Phenotype: Periodic and Aperiodic Trajectories, Reliability, and Five-Year Change

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0197458026001685&hl=zh-CN&sa=X&d=8179582444424128590&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVF1ae3fH9isAJAjx5IbLUc4&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=0&folt=kw-top
**作者**: Y Du - Neurobiology of Aging, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Resting-state electroencephalography is increasingly proposed as a scalable marker of healthy brain ageing, yet its interpretability depends on distinguishing stable individual characteristics from condition-dependent measurement effects

---

### [291] EOG Artifact Removal from EEG Using a Gated WGAN with Multi-Scale and Multi-Domain Feature Extraction

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-3425/16/10/1124&hl=zh-CN&sa=X&d=7724008792911155584&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVH67sxLcg0P88YSJuS1xwJn&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=3&folt=kw-top
**作者**: S Xie, X Liu, X Wang, X Xie, H Tang - Brain Sciences, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Third, applying the same denoising process to all input signals may unnecessarily modify EEG signals without evident artifacts. Recent … for singlechannel EEG that improves EEG reconstruction while reducing unnecessary modification of

---

### [292] Concurrent TMS- EEG to characterise interhemispheric signal propagation over the motor and prefrontal regions: An independent replication of GABAB receptor …

**链接**: https://scholar.google.com/scholar_url?url=https://journals.plos.org/plosone/article%3Fid%3D10.1371/journal.pone.0360250&hl=zh-CN&sa=X&d=8228990306164519040&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVGo-8Ox6oeH-b5fbrk0BXPJ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=5&folt=kw-top
**作者**: J Zhou, Y He, C Jin, C Yang, Y Han, Y Wang 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study aimed to validate the sensitivity of a TMS- EEG -based measure of interhemispheric signal propagation (ISP) to GABA B receptor … Before and after drug intake, single-pulse TMS- EEG was applied to assess ISP in both the motor and

---

### [293] Sleep Stage Classification Across Heterogeneous EEG /EOG Channels with Multi-channel Differential Transformer

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s11571-026-10574-5&hl=zh-CN&sa=X&d=17481450554211691755&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVEQfKmrj2JpAxFFA32xhDgG&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=1&folt=kw-top
**作者**: BWH Chin, YT Yew, JH Puah, H Wu, L Liang, CK Chan… - Cognitive Neurodynamics 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> nonstationarity and variability of electroencephalography ( EEG ) and electrooculography (EOG) … differential transformer framework for heterogeneous EEG –EOG representation learning. … of EEG datasets could enhance robustness

---

### [294] Sleep Stage Classification across Heterogeneous EEG/EOG Channels with Multi-Channel Differential Transformer

**链接**: https://arxiv.org/abs/2508.15215
**作者**: Benjamin Wei Hao Chin, Yuin Torng Yew, Jia Hong Puah, Haocheng Wu, Lanxin Liang, Chow Khuen Chan 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [295] Rethinking EEG Spatial Super-Resolution as Dynamic State Decomposition and Filtering

**链接**: https://arxiv.org/abs/2610.24528
**作者**: Hongjun Liu, Leyu Zhou, Chang Ge, Shitong Duan and Chao Yao
**来源**: cs.AI cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG spatial super-resolution aims to recover high-density neural signals from sparse electrode observations. Existing methods have achieved substantial progress through spatial modeling, generative reconstruction, and temporal representation learning. However, the current EEG state contains two different sources of information: predictable evolution inherited from preceding states and newly emerging changes revealed by the current observation. Most approaches typically do not model these two components explicitly. In this work, we formulate streaming EEG spatial super-resolution as a sequential state filtering problem and propose Dynamic State Filtering (DSF). Rather than relying on a single temporal reconstruction pathway, DSF combines a history-aware dynamical branch with an innovation-filtering branch that explicitly decomposes waveform-state estimation into prediction and observation-driven correction. To infer how spatially incomplete innovations should affect missing locations, D

---

### [296] Logit Averaging During Training Sets a New State of the Art for Non-Invasive Speech BCI

**链接**: https://arxiv.org/abs/2610.26347
**作者**: Miran \"Ozdogan, Gereon Elvers, Michael Bronstein, Oiwi Parker Jones
**来源**: cs.LG
**匹配关键词**: BCI
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Non-invasive brain-computer interfaces are in practice limited by signal-to-noise ratio, and recent state-of-the-art methods address this limitation by aggregating over repeated trials of the same stimulus. Yet multi-trial aggregation has been treated inconsistently across the literature: some work averages brain signals at the model's input, other work averages predictions at the model's output, and neither treats aggregation as an architectural choice in its own right. We provide the first systematic comparison of aggregation strategies for non-invasive neural decoding, evaluating six paradigms (including logit averaging during training and three attention-based variants we introduce) across three datasets, four tasks, and two group sizes. We find that aggregation choice matters substantially: training-time logit averaging, the simplest method we propose, outperforms all others in 6 of 7 settings. On the phoneme classification setting of the 2025 PNPL competition, it sets a new state

---

### [297] Altered resting-state EEG microstate dynamics are associated with auditory hallucinations in patients with major depressive disorder

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0165032726014801&hl=zh-CN&sa=X&d=17319346334770383061&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVEJFWotqZuUXjdQ8fMg17sq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=6&folt=kw-top
**作者**: Y He, F Wu, F Liao, Z Zhang, J Wu, X Zhang 等 (9 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study investigated resting-state EEG microstate dynamics associated with auditory hallucination experiences in first-episode MDD. … aimed to characterize EEG microstate alterations associated with auditory hallucinations in MDD. Using

---

### [298] CSTO-Net: Cross-View Spectral-Transport and Topology-Operator Network for EEG Emotion Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://iopscience.iop.org/article/10.1088/1361-6579/aeb59e/meta&hl=zh-CN&sa=X&d=555037942724571656&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVGnkeA0KlmSQz3MhsMFCAJQ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=7&folt=kw-top
**作者**: Z Sun, J Liu, Z Liu, G Wu, H Jianning - Physiological Measurement, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Objective: Multi-view electroencephalography ( EEG ) emotion recognition must decide how the spectral graph sets of different connectivity views correspond and how their graph propagation operators interact. We present CSTO-Net, a cross-view

---

### [299] Feasibility Study of Analytical Methods for Classifying Spatial Imagination under Low Channel EEG Environment

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11739491/&hl=zh-CN&sa=X&d=18095082208203650448&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVHUCnfeFquayX6Rka96AeOO&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=2&folt=kw-top
**作者**: HJ Lee, J Lee - IEEE Internet of Things Journal, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this study, we explore the feasibility of classifying higher-order spatial imagination tasks using EEG signals by applying multiple signal … characteristics of EEG data for each subject, we adopt several analytical techniques that have been

---

### [300] … virtual reality-assisted and traditional supplementary exercise programs and usual training on balance, sprint performance, and resting-state EEG in youth academy …

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1186/s13102-026-02173-y&hl=zh-CN&sa=X&d=11202386633092858475&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVGzc7y3en2vP1HvjtEbKBgc&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=9&folt=kw-top
**作者**: A Kalkavan, E Terzi, Hİ Çakır, RF Kayhan, C Akyıldız… - BMC Sports Science …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background This study compared outcomes associated with an eight-week virtual reality-assisted supplementary exercise program, a traditional supplementary exercise program, and usual training in youth-academy football players. Because

---

### [301] Overt and Covert Speech-State Classification from Tripolar Concentric Ring Electrode EEG : A 4 mm and 10 mm Configuration Study

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/1424-8220/26/20/6587&hl=zh-CN&sa=X&d=7225456468264340552&ei=l_vWariQBtK2ieoP7JnEuAQ&scisig=ACTRDVHQDgpL6BJ_YiG-2vF_BlmU&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=8&folt=kw-top
**作者**: PQ Memon, CW Anderson, S Memon - Sensors, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The EEG achieved through the scalp is contaminated by artifacts and volume conduction and suffers from poor spatial resolution. We … electrodes (TCREs) to record the overt and covert EEG signals. In addition, EEG signals were recorded for

---

### [302] EEGDM: Label-Efficient EEG Representation Learning with Generative Diffusion Model

**链接**: https://arxiv.org/abs/2508.14086
**作者**: Jia Hong Puah, Sim Kuan Goh, Ziwei Zhang, Zixuan Ye, Chow Khuen Chan, Kheng Seang Lim 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [303] Brain-OF: An Omnifunctional Foundation Model for fMRI, EEG and MEG

**链接**: https://arxiv.org/abs/2602.23410
**作者**: Hanning Guo, Hanwen Bi, Farah Abdellatif, Andrei Galbenus, Jon. N. Shah, Abigail Morrison 等 (7 人)
**来源**: cs.LG cs.AI eess.SP q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [304] SleepPairNet: Learning Multimodal Pediatric Sleep Representations with Random-Pair Cross-Attention

**链接**: https://arxiv.org/abs/2610.26628
**作者**: Saurav Raj Pandey, Harlin Lee
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analyzing physiological sleep signals is important for assessing sleep quality and detecting sleep-related disorders. Learning inter-modal relationships across physiological signals can provide richer representations for downstream sleep analysis. We introduce \textbf{SleepPairNet}, a multimodal self-supervised learning (SSL) framework that learns pairwise interactions between physiological signals through cross-attention. We propose a random modality-pair selection strategy that exposes the model to diverse signal pairs during pretraining, enabling flexibility across modality combinations at test time. Pretrained on the NCH dataset, SleepPairNet outperforms the evaluated SSL baselines on all respiratory tasks while remaining competitive on EEG-related tasks, and shows even stronger results when transferred to the external CHAT dataset.

---

### [305] UtoMe: Observation-Uncertainty-Guided Token Merging for Weather Foundation Models

**链接**: https://arxiv.org/abs/2610.25001
**作者**: Yunbei Zhang, Janet Wang, Xi Xiao, Jihun Hamm, Xiao Wang
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weather transformers process dense reanalysis fields whose reliability varies across variables, locations, and weather regimes. Token merging can reduce computation, but feature similarity alone does not account for this heterogeneous input uncertainty. We introduce UtoMe, an observation-uncertainty-guided token merging framework that combines dynamics saliency with ensemble data assimilation spread as a relative input-reliability proxy. The resulting importance score protects selected tokens as anchors and calibrates bipartite matching between the remaining tokens. Three variants use external uncertainty at both training and inference, during training only, or neither stage. In ERA5 72-hour forecasting at two spatial resolutions, UtoMe improves Overall error over train-time ToMe at matched token budgets. At $1.40625^\circ$ and 50% token reduction, UtoMe-E lowers Overall error from 67.32 to 53.00 at the same 0.55x encoder FLOPs. Small reductions remain close to the full-token baseline;

---

### [306] From Retrieval to Recognition:Knowledge-Enhanced Post-training of Time Series Foundation Models for Classification

**链接**: https://arxiv.org/abs/2610.26114
**作者**: Zhen Liu, Yucheng Wang, Yingpeng Du, Tianjun Wei, Qianli Ma, Min Wu 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models (TSFMs) have achieved notable progress in classification tasks through large-scale pretraining. However, their post-training practice mainly focuses on implicit parameter fine-tuning, where task-relevant information is entangled with abundant irrelevant knowledge in vast parameter spaces. This may hinder TSFMs from precisely activating useful knowledge for downstream classification. To this end, we propose Retrieval-to-Recognition (R2R), a plug-and-play post-training paradigm that adapts pretrained TSFMs to time series classification. Rather than pretraining a new foundation model, R2R improves how existing TSFMs are post-trained: it introduces a decoupled query encoder to extract discriminative patterns and retrieve instance-level numerical knowledge from a constructed knowledge base. The retrieved explicit knowledge is then fused with the TSFM's implicit parametric embeddings, enabling joint knowledge transfer at both the parameter and feature levels. In

---

### [307] Toward Structured Financial Foundation Models

**链接**: https://arxiv.org/abs/2610.26516
**作者**: Natraj Raman, Saumitra Mishra, Vamsi Potluru, Sumitra Ganesh
**来源**: cs.AI cs.CE
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models promise reusable capabilities and step-change performance gains across tasks. In finance, large-scale pretraining of domain-specialized foundation models can advance both goals. However, prevailing architectures and objectives do not by themselves address the combined demands of financial systems: partial observability, interacting entities, asynchronous events, changing regimes, action-dependent outcomes, and rare states with disproportionate consequences. Moreover, independently developed specialists may learn incompatible representations, while multi-domain monolithic alternatives couple data access, model updates, and governance. We therefore propose a structured-data-first research agenda centered on modular, domain-specialized financial foundation models connected by a representation fabric for reuse and composition across domains and tasks. These models should maintain persistent financial state across aggregation levels and time horizons, capture its dynamics,

---

### [308] FTFM: Factorized Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.25558
**作者**: Josif Grabocka
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are becoming a powerful alternative to conventional tabular learning, adapting to new datasets in context without task-specific training. Current architectures, however, face a trade-off: models that preserve cell-level representations are expensive because they repeatedly attend across rows and columns, while faster models collapse each row into a fixed embedding and lose this fine-grained state. We introduce Factorized Tabular Foundation Models (FTFM), which preserve cell representations while factorizing their computation through one contextual latent per row and one per column. Cells no longer attend to one another directly; instead, each cell is updated through the interaction of its row and column latents, reducing repeated attention while retaining feature-specific information. FTFM achieves competitive predictive performance in tabular classification on major benchmarks such as TabArena and BeyondArena.

---

### [309] Scaling Vision Foundation Models for Toxicologic Pathology

**链接**: https://arxiv.org/abs/2610.26586
**作者**: Jessica Loo, Theodoros Pissas, Byunghak Kang, Vincent A. Ella, Xiaoyan Zhang, Kevin Sweeney 等 (10 人)
**来源**: cs.CV eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Here, we present TOX-FM, a family of non-clinical PFMs trained on large-scale diverse histopathology datasets of over one million whole slide images consisting of over 60 organs across six animal species from over 14,000 toxicology studies across six decades. We introduce a comprehensive benchmark of 18 non-clinical downstream tasks, incorporate an established benchmark of 9 clinical downstream tasks, and evaluate TOX-FM against state-of-the-art clinical PFMs across both non-clinical and clinical domains. Notably, we explore open questions surrounding domain-specific training and cross-domain generalization, offering insights into the opportunities and challenges of applying PFMs in the non-clinical domain.

---

### [310] TILDE: Teacher-in-the-Loop Distillation from Embodied Foundation Models

**链接**: https://arxiv.org/abs/2610.25376
**作者**: Yuxiang Lu, Yantong Liu, Jinghua Hou, Xueli Sun, Ruihua Han, Zhe Liu 等 (7 人)
**来源**: cs.RO cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale action pretraining equips Embodied Foundation Models (EFMs) with strong manipulation capabilities, with particular strengths in generalization and closed-loop robustness, but reproducing such pretraining requires substantial robot data and computation. To transfer these capabilities from pretrained EFMs to policies without action pretraining, we introduce TILDE (Teacher-In-the-Loop Distillation from EFMs), which synergizes on-policy distillation at student-induced states with learning from teacher-executed recovery trajectories. We further propose AutoDAgger, an autonomous data aggregation pipeline in which a robotic reward model is utilized to monitor task progress and trigger teacher intervention, thereby collecting recovery experience without human monitoring or manual control. AutoDAgger accelerates recovery-trajectory collection by more than $2\times$ compared with the human-in-the-loop method. By unifying learning from demonstrations, on-policy teacher supervision, an

---

### [311] Enhancing Gaze Reasoning in Vision Foundation Models for Gaze Following

**链接**: https://arxiv.org/abs/2605.22607
**作者**: Shijing Wang, Yaping Huang, Chaoqun Cui, David Wong, Yihua Cheng, Alexandros Neophytou 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [312] Beyond Static Leaderboards: Capability-Focused Evaluation with Structural Diversity for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2610.26251
**作者**: Hongyin Zhang, Mingyi Xiang, Rongzhao Chen, Yankai Wang, Jialin Qiao, Xiangdong Huang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Static public benchmarks for time series foundation models (TSFMs) typically have fixed and narrow test distributions. Their repeated reuse encourages benchmark-specific tuning, making reported performance reflect adaptation to the fixed test set rather than genuine forecasting generalization. In addition, a single aggregate score cannot fully characterize model capabilities across distinct temporal structures and input relationships. We propose CaFE (Capability-Focused Evaluation), a refreshable evaluation extension grounded in original benchmark data that enriches static benchmarks with structural diversity and enriches single-score black-box evaluation with multi-dimensional, capability-oriented assessment. CaFE first profiles the original benchmark and defines eight Structural Features (SFs) that characterize its temporal structure. For each SF, it resamples the original data according to its structural support, removes edge-of-distribution samples, and augments the retained sample

---

### [313] Robust and Efficient Finetuning of Vision Foundation Models via Implicit Ensembling

**链接**: https://arxiv.org/abs/2510.06982
**作者**: Masih Aminbeidokhti, Heitor Rapela Medeiros, Eric Granger, Marco Pedersoli
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [314] Adversarial Post-Training of Foundation Models for High-Frequency Trading

**链接**: https://arxiv.org/abs/2610.25604
**作者**: Alexandre Bismuth, Kang Li, Aramis Marti-Shahandeh, Valentin Mohl, Jakob Foerster, Anisoara Calinescu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While autoregressive foundation models trained on limit order book (LOB) data show state-of-the-art performance for market simulation, pre-training with cross-entropy neither penalizes the compounding of sampling errors over free-running rollouts nor targets desired market properties. We introduce a post-training method for LOB foundation models using a Wasserstein generative adversarial network (GAN) objective. A critic, trained online on rollouts through the true, non-differentiable matching engine, guides updates from evolution strategies over rank-4 LoRA perturbations of the pre-trained generator, under a KL trust region. For efficiency, we use EGGROLL (Evolution Guided GeneRal Optimisation via Low-rank Learning), a memory-efficient variant of evolution strategies. On a held-out panel, adversarial post-training improves LOB-Bench realism by 17.6% (WS-21) and 17.0% (Mean-$L_1$), while selection-matched random-perturbation and compute-matched continued-pre-training controls yield no 

---

### [315] EvalRx: Agentic Diagnosis and Verified Repair of Foundation Models

**链接**: https://arxiv.org/abs/2610.25767
**作者**: Jiaqi Liu, Ruinan Jin, Yitong Tang, Beidi Zhao, Gexin Huang, Qiong Zhang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model evaluation reveals where models fail, but rarely why or whether a proposed fix genuinely works. We introduce EvalRx, an open-source agentic framework for statistically grounded model diagnosis and repair. EvalRx discovers systematic failure modes, explores candidate mechanisms, formulates falsifiable hypotheses, and verifies them by executing frozen, pre-specified tests before using supported diagnoses to guide tiered repair. Candidate repairs are validated against the unchanged model and promoted only when they improve the target behavior without unacceptable regression. Across language, vision-language, and audio-language settings spanning Gemini, Qwen, Gemma, and Nemotron, EvalRx improves performance in all 12 evaluated model family-modality combinations, with gains ranging from +1.4 to +10.9 percentage points (+5.8 points on average). These results show that model evaluation can serve not only to measure failures, but to support an auditable process for diagnosing and repairi

---

### [316] Do Satellites See Commuters? A Critical Benchmark of Vision Foundation Models

**链接**: https://arxiv.org/abs/2609.00661
**作者**: Ashiq Shukoor Iqbal, Wilson Wongso, Flora D. Salim
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [317] World Models, Trees and Foundation Models for Retail Forecasting: Evidence from Four Public Data Sets

**链接**: https://arxiv.org/abs/2610.25170
**作者**: Karthik Iyer, Madan Dabbeeru
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A retailer makes different decisions at different grains of the product, store and time hierarchy: store orders for an item in a store, supplier funding for an item across stores, category performance by store, and the financial plan for the chain. Which forecasting model to use depends on the grain. This paper compares models at each grain on four public data sets (M5, six Dominick's categories, Breakfast at the Frat, and Corporaci\'on Favorita, the last kept out of all development), over rolling forecast origins with paired tests and model confidence sets. It covers price and promotion through the plan inputs these data record, not product, assortment or place. The models are a world model that carries each item's state forward under the price and promotion plan, the same network without that state, LightGBM, the Temporal Fusion Transformer, TimesFM, Chronos-Bolt, Timestral, seasonal naive, and an equal-weight average of the world model, LightGBM and TimesFM given the plan. The answe

---

### [318] Dataset Inference for Data Provenance and Privacy Auditing in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.24278
**作者**: Dariush Wahdany (1) and Jesse Cresswell (2) and Naiqing Guan (2) and Atiyeh Ashari Ghomi (2) and Franziska Boenisch (1) and Adam Dziedzic (1) ((1) CISPA Helmholtz Center for Information Security, (2) Layer 6 AI)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) are increasingly deployed through black-box APIs and trained on large collections of real-world tabular datasets. As this training paradigm becomes more widely adopted, private or proprietary datasets may be incorporated into pre-training corpora, yet there are currently no dedicated methods for determining whether a given tabular dataset was used to train a TFM. As a solution, we introduce the first dataset inference method for TFMs, aiming to infer whether a suspect dataset was part of a model's pre-training data. We systematically analyze a broad collection of candidate signals that can be observed from a black-box TFM via input manipulation and find that individual signals provide only weak evidence of training data membership. However, by combining multiple complementary signals, we can infer dataset membership for several state-of-the-art TFMs trained on real tabular data, achieving up to 0.99 ROCAUC dependent on the TFM. We then study factors tha

---

### [319] Planetary Geospatial Foundation Models: A New Paradigm for Global Public Health

**链接**: https://arxiv.org/abs/2610.05699
**作者**: Arbaaz Muslim, Aviv Slobodkin, Katherine Wheeler-Martin, Eric Zhou, John Brittain, Martin Frasch 等 (10 人)
**来源**: cs.LG cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [320] Feature Selection for Tabular Foundation Models: Exploring Feature Utility in Low-Data Molecular Prediction

**链接**: https://arxiv.org/abs/2609.30789
**作者**: Yiqi Yao, Miquel Duran-Frigola
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [321] spora: A Unified Multimodal Dataset and Platform for Spatial Proteomics

**链接**: https://arxiv.org/abs/2610.24002
**作者**: Benedikt von Querfurth, Johann Wenckstern, Eeshaan Jain, Lukas Klein, Phil Cheng, Yexiang Cheng 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spatial proteomics (SP) captures the molecular composition and spatial organization of tissues at single-cell resolution, opening a direct view of the cellular ecosystems that drive disease. Protein panels, acquisition platforms, and tissue contexts differ from one cohort to the next, and a coherent picture of tissue biology can only emerge from models trained to bridge this heterogeneity. Foundation models offer the natural path forward, but their training depends on large, harmonized corpora that span platforms, panels, and cohorts. No public resource currently approaches that scale; available data sit in small, narrowly scoped releases with incompatible formats and conventions. We present $\texttt{spora}$, a large-scale multimodal SP dataset of 13,546 standardized multiplex images from 5,477 patients across 35 cohorts and five major SP technologies. Curated with biomedical experts, $\texttt{spora}$ provides model training-ready formats together with cell and tissue segmentations, st

---

### [322] WhatIf-Bench: Benchmarking Intervention-Aware Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.26582
**作者**: Arjun Ashok, Mihir Parmar, Palash Goyal, Bhavana Dalvi Mishra, Chun-Liang Li, Irina Rish 等 (9 人)
**来源**: cs.AI cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent time series foundation models (TSFMs) can consume covariates in-context, extending zero-shot forecasting to problems driven by external factors. This enables scenario analysis: forecasting how a target responds to events that set covariates to chosen future values. Whether they can do this reliably is an open question. We introduce WhatIf-Bench, a benchmark measuring how well forecasters use covariates to forecast a target's response to future events. WhatIf-Bench is semi-synthetic: time series come from mechanistic simulators of data centers, power grids, road traffic, and water networks, with controlled covariate-target relationships grounded in each system. Each task presents a history of events intervening on covariates, then asks to forecast a future event that either replays seen values (Replay) or sets them to unseen ones (Novel). Varying the number of covariates, historical events, and event length yields 37,665 tasks. Evaluating TSFMs, frontier LLMs, and simple regressi

---

### [323] Visual Memory and Textual Alignment for Cross-Modal Few-Shot Segmentation

**链接**: https://arxiv.org/abs/2610.25641
**作者**: Tianqi Wei, Zhi Chen, Xin Yu, Scott Chapman, Zi Huang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Few-shot segmentation (FSS) aims to segment target objects with limited annotated examples. Recent studies have begun to explore large foundation models to improve generalization for this task. In particular, SAM 3 provides strong visual representations and supports text-guided segmentation. However, its performance remains limited in specialized domains, where semantic prompts and visual representations are often poorly aligned. To address this challenge, we propose ViTA-SAM, a framework built upon SAM 3 that integrates visual memory and textual features through cross-modal alignment. Specifically, we construct a visual memory module that encodes support features together with their corresponding masks, providing support-aware visual guidance for query prediction. In parallel, we leverage the text encoder of SAM 3 to extract semantic features as complementary priors. To bridge the gap between semantic and visual representations, we introduce a cross-modal alignment module that conditi

---

### [324] Dependency, Compression, and Synergy: A Unified Information-Theoretic View of Multimodal Learning

**链接**: https://arxiv.org/abs/2609.14421
**作者**: Liangjian Wen, Linjie Li, Jiang Duan, Yong Dai, Jianzhuang Liu, Zhao Kang
**来源**: cs.IT cs.AI cs.CV cs.LG math.IT
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models have intensified the need to understand how different modalities share, preserve, and complement information. Mutual Information (MI), the Information Bottleneck (IB), and Partial Information Decomposition (PID) provide complementary perspectives, yet existing studies often treat them as isolated tools. This survey presents an information-theoretic perspective connecting these principles as progressively refined views of multimodal information processing: MI characterizes inter-modal dependency, IB explains task-oriented information preservation under compression, and PID decomposes preserved information into redundancy, uniqueness, and synergy. We review 170 recent studies (2018--2026) and 12 foundational works, organizing multimodal learning around four challenges: cross-modal alignment, information-efficient fusion, interaction-type characterization, and scaling to multimodal foundation models. Rather than using application domains as 

---

### [325] A Fisher-Geometric View of Multi-Teacher On-Policy Distillation

**链接**: https://arxiv.org/abs/2610.26525
**作者**: Liu Kaiyuan, Zhuang Ziyuan, Ma Haoxuan, Gu Yannian, Song Mingfei, Weng Rongxiang 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Consolidating specialized foundation models into a unified generalist is a central goal of post-training. Two approaches are in common use: model merging, which is fast but treated as a heuristic, and multi-teacher on-policy distillation, which matches distributions but demands heavy rollout compute and suffers from cross-task gradient conflict. We show that the two are one objective seen at different orders. Within a shared basin of homologous specialists, the multi-teacher on-policy distillation objective is, to second order, exactly the Fisher-merging objective. Its minimizer is therefore the Fisher merge, a classic model-merging method given by a closed-form combination of the specialists, so merging is optimal, to second order, as a closed-form stage of distillation. Building on this identification, we propose Residual-Governed Branch-and-Merge(RGBM), a two-phase consolidation procedure. Concretely, a full-parameter Fisher merge is intractable on foundation models, so Phase~1 rest

---

### [326] Multi-scale Fusion of Fast Vision Mamba and Foundation Model Features for Patch-Level Gleason Grading in Computational Pathology

**链接**: https://arxiv.org/abs/2610.25904
**作者**: Zihe Zhang, Weimiao Yu, Piumi Don Simonge
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated Gleason grading of prostate whole slide images (WSIs) enables faster and more consistent cancer risk stratification. However, it remains a challenging task due to the subtle morphological differences between grades, the severe class imbalance arising from rare patterns, and the diagnostic features that span multiple spatial scales. Pathology foundation models (FMs) extract strong patch representations but often operate at a single-scale, which limits spatial context and disproportionately affects classes that depend on broader context. The challenge of fusing multiple scales and complementary models, with minimal data and computational resources, remains unresolved. We propose a multi-scale classifier built on state-space models. Our method combines two complementary feature sources: a frozen foundation model, and a lightweight FastVim, pre-trained on ImageNet and distilled from the foundation model, that reads the raw image crops. At each scale, a Mamba model encodes the fea

---

### [327] Scenario Generalization and Sector Transfer in Real Surface Irrigation Surrogate Modelling with Tabular Models

**链接**: https://arxiv.org/abs/2610.26005
**作者**: Alessandro Cagiano, M. Aybars Seyhan, Fabiola Gangi, Matteo Zignani, Daniele Masseroni
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Surface irrigation planning requires screening many operating conditions and spatial configurations, while high-fidelity shallow-water-equation (SWE) simulations are expensive. We study tabular surrogate models for predicting maximum water height from drone-derived field morphology, terrain, hydrological, spatial, and scenario descriptors, where each row represents a spatial cell under one irrigation scenario. To assess deployment feasibility, we evaluate gradient-boosted trees, neural tabular models, AutoML, and tabular foundation models (TFMs) under two regimes: same-sector generalization, where a model predicts unseen scenarios after observing a limited set of configurations in the same sector, and sector-out transfer, where knowledge learned from source sectors is transferred to an unseen sector. The main findings are twofold: a) under the evaluated fixed 8/32 same-sector split, surrogates achieve strong performance, especially with raw spatial coordinates; b) sector-out transfer i

---

### [328] MemT-1.0: Towards Memory-Native Evolution

**链接**: https://arxiv.org/abs/2610.26825
**作者**: Zhiyu Li, Zeyu Zhang, Linyun Liu, Yiwei Bu, Chenyang Xi, Xichong Zhang 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory-native evolution requires making memory an intrinsic capability of foundation models, enabling them to continuously accumulate and utilize information. To this end, we introduce MemT-1.0, a new architecture of memory foundation models that internalize memory as part of model computation. Building on Metis, MemT-1.0 employs Gated DeltaNet-2 with a stable token-level memory update mechanism within each turn. We further introduce Mixture-of-Storage to scale native memory capacity. Following a deliberate backbone preparation, we develop a two-stage training pipeline consisting of continued pre-training and post-training, supported by 34B tokens of training data and efficient training and inference infrastructure. We release a model family comprising MemT-1.0-Nano and MemT-1.0-Flash, and conduct a comprehensive evaluation of memory and general capabilities. The results show that they outperform the parametric memory baselines on average and remain competitive with retrieval-augmented

---

### [329] CME-SpectrumBench: Can LLMs Analyze Condensed Matter Spectral Data?

**链接**: https://arxiv.org/abs/2610.24304
**作者**: Jin Gene Wong, Anjney Midha, Joseph Mathew Tennyson, Wei-Lin Chiang, Ion Stoica, Zhi-Xun Shen
**来源**: cs.AI cond-mat.other cond-mat.str-el cond-mat.supr-con
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are presently well assessed by expert-level mathematics and physics benchmarks which focus on theoretical, symbolic reasoning. However, we lack experimental benchmarks that evaluate data analysis in frontier research problems, a capability that future domain-specific foundation models must have. To this end, we present CME-SpectrumBench, an expert-designed benchmark consisting of 190 questions that measures how reliably frontier LLMs analyze research-level spectral scientific data in condensed matter experiments (CME). Using simulated CME spectral data, we prompt models to identify structures from 2D intensity arrays in the face of noise and limited instrumental resolution, a test of dense context reasoning. Models are scored by how accurately their numerical answers approach the ground truth. Under direct query, scores generally pale in comparison to handwritten code due to clear failure modes: models can find simple features but struggle to trace patterns

---

### [330] On Data Scaling in Tabular ML: More Data, Better Generalization?

**链接**: https://arxiv.org/abs/2610.26794
**作者**: Ivan Rubachev, Nikita Lazarev, Artem Babenko
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work in tabular machine learning has emphasized the importance of diverse and realistic evaluation settings. The niche of large-scale (1M+) data, however, remains under-explored. To study training-data scaling, we assemble eight real-world tabular datasets with up to around ten million training examples, retaining the natural distribution shifts of the tasks and using random-split evaluation as a control. We find that GBDTs and MLP-based models show broadly similar scaling trends, with gains from both additional training data and algorithmic improvements. Tabular foundation models show more varied scaling behavior, with recent versions benefiting more consistently from larger contexts even under distribution shift. However, scaling training data under distribution shift introduces new challenges: in-distribution and out-of-distribution performance mostly improve together at smaller scales but can diverge at larger scales. We examine this through MLP capacity sweeps and compariso

---

### [331] Defending Against Dormant Poisoning Attacks Across Language and Multimodal Agents

**链接**: https://arxiv.org/abs/2610.24379
**作者**: Wonjun Lee, Vaidehi Patil, Zaid Khan, Yue Zhang, Hyunji Lee, Suhyun Kim 等 (7 人)
**来源**: cs.CR cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work shows that attackers can implant dormant malicious behaviors that remain hidden at release but emerge after benign fine-tuning. As foundation models are used as agents, whether dormant poisoning extends to harmful agent actions and multimodal settings remains unclear. We show two agentic risks: (1) harmful behaviors activated by benign fine-tuning can extend to unseen actions; (2) multiple harmful behaviors can coexist and be jointly activated by benign downstream fine-tuning. Existing defenses often rely on external safe responses, which are hard to obtain for agent actions, or a trusted clean reference model. We exploit a key property of dormant poisoning: the attacker must preserve safe behavior at release to conceal poisoning, and this behavior can serve as a safety reference. Leveraging this property, we automatically construct a Safety Buffer pairing harmful inputs with the released model's responses and benign versions generated by the same model to remove harmful in

---

### [332] Image Dehazing as In-Context Tabular Inference

**链接**: https://arxiv.org/abs/2610.25142
**作者**: Le-Anh Tran
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Image dehazing is traditionally addressed through handcrafted physical priors or task-specific deep learning models, often requiring carefully designed architectures or extensive model training. Recent advances in tabular foundation models (TFMs), however, offer an alternative learning paradigm in which continuous relationships can be inferred directly from contextual examples without task-specific model training. Motivated by this capability, this paper investigates whether single-image dehazing can be effectively reformulated as an in-context tabular regression problem and introduces DehazeTab, a framework that estimates atmospheric transmission from structured image-patch representations. Specifically, overlapping patches extracted from hazy images are transformed into tabular samples using handcrafted haze-related descriptors, pretrained visual embeddings, or their hybrid combinations, while corresponding transmission patches are summarized as scalar regression targets. A pretraine

---

### [333] VeriCUA: Learning Proactive Verification for Reliable GUI Agent Rewards

**链接**: https://arxiv.org/abs/2610.26469
**作者**: Zhizhou Wang, Yaxi Lu, Zhong Zhang, Zikun Hu, Xin Cong, Yankai Lin 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning for computer-use agents increasingly relies on proactive reward agents that interact with the post-execution GUI environment to verify what recorded screenshots cannot reveal. The reliability of such verification hinges on two coupled decisions: what to check and when to stop. Existing methods leave these decisions to prompted foundation models. However, neither scaling up the model nor providing few-shot examples reliably improves verification: prompted Judges ranging from 4B to GPT-5.4 all plateau at 68%-70% macro-average agreement. This is because the value of a check depends on the environment rather than the task alone, and becomes apparent only through execution. Learning from execution is itself constrained, as the Actor's terminal state cannot be faithfully replicated during training, allowing only one verification attempt per state. We introduce VeriCUA, a proactive reward agent that learns its verification strategy from these single attempts. A trainabl

---

### [334] Morpheus-2.0: Multiscale Probabilistic Forecasting with Dual-Axis Attention

**链接**: https://arxiv.org/abs/2610.24321
**作者**: Aakriti, Manoj Cherukumalli, Prathamesh Patil, Leonidas Tsepenekas, Amit Varshney, Penghang Liu 等 (8 人)
**来源**: cs.LG cs.AI stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A universal forecaster is trained once and applied everywhere, so it must serve tasks whose schemas, forecast horizons, and temporal resolutions all differ. The number of targets and covariates changes from dataset to dataset, horizons vary by orders of magnitude, and sampling rates range from seconds to years. Existing time-series foundation models address these only in part, since they isolate each series or visit the two grid relations in separate blocks, and they fix the horizon and resolution before training begins. We introduce Morpheus-2.0, a compact encoder-only foundation model that represents targets and covariates on a single variable-time grid. Its dual-axis attention runs both relations side by side in every layer, one across variables at a timestep and one across time within a variable; a learned gate weights the two per layer, and an axis-aware rotary encoding preserves both grid coordinates. The forecast length is sampled during training, so one set of weights spans sho

---

### [335] ChairNav: Cross-Embodiment Pre-training and Personalization for Long-Horizon Wheelchair Navigation

**链接**: https://arxiv.org/abs/2610.24012
**作者**: Junhua Huang, Zhizheng Liu, Honglin He, Xiang Zhang, Bolei Zhou
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing autonomous electric wheelchairs capable of long-horizon sidewalk navigation is critical for accessible personal mobility, yet existing approaches either focus on indoor map-based navigation or rely on expensive, complex sensor stacks to achieve full autonomy. In this work, we propose to tackle outdoor sidewalk navigation by leveraging visual navigation foundation models and large-scale navigation datasets, which offer strong generalization using lightweight hardware. To this end, we present ChairNav, a novel framework that adapts a general visual navigation model into a personalized electric wheelchair navigation system using a three-stage data pyramid. To address the scarcity of in-domain data, ChairNav first pre-trains on large-scale cross-embodiment datasets transformed into the wheelchair domain, followed by mid-training on a small number of wheelchair demonstrations to eliminate remaining domain gaps. Finally, a post-training stage refines the deployed model from user i

---

### [336] ATLAS: Expert-Guided Sustainable Satellite Backhaul for Off-Grid Wildlife Monitoring

**链接**: https://arxiv.org/abs/2610.24910
**作者**: Hao Fang, Miao Zhang, Haoyuan Zhao, Long Chen, Yi Ching Chou, Chi Xu 等 (8 人)
**来源**: eess.SY cs.LG cs.SY
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Remote wildlife monitoring increasingly depends on high-fidelity cameras and sensors deployed far from grid power and terrestrial networks. Low Earth orbit satellite links can provide connectivity in these settings, but their high power draw and variable bandwidth, combined with intermittent on-site solar harvesting, make continuous backhaul infeasible. Current systems therefore filter at the edge, with motion triggers that waste limited energy and bandwidth on environmental artifacts, or fixed vision models that cannot follow evolving expert objectives. We present \textsc{ATLAS}, an expert-guided edge-to-cloud system that treats satellite backhaul as a scarce resource for off-grid wildlife monitoring. \textsc{ATLAS} uses foundation models to compile natural-language expert intent into semantic scoring logic, combines semantic relevance with environmental and energy state, and uses a constrained reinforcement-learning scheduler to decide which clips to upload and when. As a representat

---

### [337] SplatXR: A Toolkit for Multi-Layered Extended Reality via On-Headset 3D Gaussian Splatting

**链接**: https://arxiv.org/abs/2610.26338
**作者**: Cyrus Vachha, Mohamed Kari, Parastoo Abtahi
**来源**: cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Gaussian splatting, 3D foundation models, and video-passthrough mixed reality offer unprecedented fidelity for capturing and blending physical and virtual worlds. However, established XR methods rely on polygon-based pipelines that treat physical and digital environments as separate domains, making seamless integration across recent novel representations difficult. Because splats lack explicit surface geometry, they impede standard graphics techniques necessary for cross-reality interactions, such as shadow or collision handling. Furthermore, while 3D foundation models can reconstruct physical objects on-the-fly into digital splats, current XR systems fall short of leveraging this capability for user experiences that transition seamlessly between physicality and virtuality. To address this, we organize XR as a multi-layered reality of interacting primitives, letting pixels and objects move across physical and digital boundaries. We contribute SplatXR, a Unity toolkit

---

### [338] CODA: Cohort- and Drift-aware Foundation Model for Multimodal Clinical Reasoning

**链接**: https://arxiv.org/abs/2610.25871
**作者**: Changshuo Liu, Jiaqi Zhu, Wenqiao Zhang, Xiaokui Xiao, Beng Chin Ooi
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in multimodal foundation models have demonstrated strong performance across diverse clinical tasks. However, existing approaches predominantly operate at the individual sample level and fail to model the interplay between population-level cohort patterns and patient-specific variation that underlie real-world clinical reasoning. In practice, clinicians routinely reason through patient cohorts sharing similar demographic, physiological, or pathological characteristics, while accounting for patient-specific deviations from the group prototype. Motivated by this gap, we propose CODA, a cohort- and drift-aware foundation model for multimodal clinical reasoning. CODA explicitly integrates cohort structure into the modeling pipeline through two complementary mechanisms: cohort-aware population stratification and drift-aware individual adaptation. In particular, we leverage reinforcement learning to discover clinically meaningful patient cohorts, and further model each patient

---
