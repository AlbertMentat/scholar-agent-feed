# 📑 论文索引 - 2026-11-11

共 308 篇论文

---

### [1] Teamknitt: Configuring, Observing and Intervening in LLM-Agent Teams through the Lens of Dynamical-Systems and Human-Team Theory

**链接**: https://arxiv.org/abs/2611.12545
**作者**: Goran Mitevski
**来源**: physics.soc-ph cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Most frameworks for teams of large language model (LLM) agents fix the team's shape inside the software: who talks to whom, how much is passed along, and what a human can do once a run has started. Human-team research has long asked those questions: where team phenomena live (in members or in their interaction), how team-level properties arise, and what separates what a team does from how a team is. I propose using that theory as the organizing lens for configuring, observing and intervening in LLM-agent teams, without assuming its findings transfer. I introduce teamknitt, a framework and open reference implementation in which a user configures a team of 1-16 AI agents for task completion, solution generation, achieving a goal or a research mission; selects one of fourteen deterministic routing topologies or a custom directed graph; chooses a sharing profile that limits what may travel along permitted routes; and binds sources, representations, work dependencies, handoffs and an expert

---

### [2] System Prompts Affect Response Bias More Than Discriminability in LLM Safety

**链接**: https://arxiv.org/abs/2611.11074
**作者**: Mohan W. Gupta, Sandy Tanwisuth
**来源**: cs.LG cs.AI cs.CL cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model safety evaluations often focus on a compliance-refusal tradeoff: models should refuse unsafe requests without refusing safe ones. We argue that this misses a broader form of prompt-conditioned task selection, where the same request can elicit different behaviors depending on the system prompt. We investigate this using a controlled evaluation crossing eight safety-task prompt families with three clarity levels across HarmBench, XSTest, and IHEval. Holding benchmark items fixed, we evaluate 13 models and use signal detection theory to distinguish two possibilities: whether models become better at telling safe from unsafe requests (discriminability), or simply more willing to refuse (response criterion). We find substantial differences in discriminability across models, but system prompts primarily shift the willingness to refuse, with smaller and less consistent effects on discriminability. Increasing prompt clarity makes models more willing to refuse without reliab

---

### [3] Compositional Conformal Risk Control for Multi-Stage LLM Cascades

**链接**: https://arxiv.org/abs/2611.11114
**作者**: Yuxia Sun, Jiahuang Wang, Haoting Liu, Zhiwei Huang, Tingrui Pei and Saiqin Long
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-stage large language model (LLM) cascades balance accuracy and inference cost, but reliable deployment also requires controlling error risk and identifying its sources across stages. We propose Compositional Conformal Risk Control (CompCRC), a risk-control framework for pre-specified multi-stage LLM cascades. We decompose the risk of accepting incorrect answers into additive stage-wise contributions over the full query population, linking local risk budgets to a system-level guarantee. CompCRC constructs and freezes candidate budget allocations and acceptance thresholds, selects one candidate on independent data, and certifies its stage-wise risk contributions on separate held-out data. Under conditional exchangeability, we establish a finite-sample guarantee: the marginal expected accepted-error risk of the complete deployment procedure does not exceed the global risk budget. At the reported comparison budget of $\alpha=0.45$, all three stages of CompCRC pass their local checks 

---

### [4] How Much Skill Orchestration Can LLM Agents Compile Away? Execution-Grounded Specialization for Token-Efficient Skill Use

**链接**: https://arxiv.org/abs/2611.10022
**作者**: Jiayi Ni, Zac Wang, Alex Zhang, Zheng Liu, Roopa Prabhu
**来源**: cs.SE cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reusable skills guide large language model (LLM) agents through recurring requests, but each invocation still requires the model to interpret the skill and reconstruct its orchestration. Can agents automatically compile this orchestration into an executable fast path without human intervention? We first study zero-shot skill specialization, which compiles without execution evidence, and find that despite the skill's procedural guidance, incorrect assumptions about runtime bindings can make generated plans brittle and recovery costly. This motivates SkillCache, a one-trace skill specialization method that compiles a completed invocation into a parameterized capsule of programs and natural-language steps, replays it before reuse, and drives it with a plan executor that returns control to the model only when needed, keeping the source skill for recovery. With the Claude Code harness, warm execution of the same request reduces tokens on 87 SkillsBench tasks by 81% with Claude Sonnet 4.6 an

---

### [5] When Experience Becomes a Backdoor: Poisoning Self-Evolving LLM Agents via Failure-Aware Task Optimization

**链接**: https://arxiv.org/abs/2611.10542
**作者**: Minhua Lin, Zongyu Wu, Hanqing Lu, Xianfeng Tang, Xiang Zhang, Qi He 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly improve themselves through self-evolution, distilling execution experience into persistent, reusable skills. However, this persistence creates a new attack surface: malicious rules implanted into skills can compromise subsequent agent behavior. Existing skill backdoor attacks typically assume direct manipulation of the victim's skills, which is impractical when skills are constructed internally by a trusted evolver. In this paper, we study a novel problem of task-level backdoor attacks, where the attacker can only inject poisoned evolution tasks, inducing the agent to implant backdoors into its own skills. Since the attacker controls neither skill induction nor downstream execution, a natural approach is to iteratively optimize poisoned tasks based on attack success. However, our preliminary analysis reveals two key challenges: (i) failures at different stages of skill evolution and downstream execution can produce indistinguishable outcom

---

### [6] Competing Influence in LLM Populations: Budget Timing and Baseline Drift

**链接**: https://arxiv.org/abs/2611.11867
**作者**: Mehwish Nasim and Nicolas Fay
**来源**: physics.soc-ph cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When competing campaigns target a population of large language model (LLM) agents, observed opinion changes may reflect both campaign influence and changes that would occur without intervention. We study how the timing of campaign expenditure and the population's own evolution shape outcomes in a network of persona-conditioned LLM agents that exchange and revise opinions in natural language. A proponent and a challenger are tasked with generating opposing messages under equal delivery budgets, while a separate stance probe measures opinions without influencing the simulation. Across eight claims, we compare single-campaign and competitive conditions against matched no-campaign runs, and evaluate all nine combinations of early, sustained, and late spending on a reference topic. Baseline stance drift varies substantially across claims and, on some, accounts for a sizeable fraction of apparent campaign effects. After accounting for this drift, the direction of observed campaign-associated

---

### [7] Represented but Not Used: Value-Policy Dissociation in LLM Agents

**链接**: https://arxiv.org/abs/2611.10457
**作者**: Yuzhang Luo, Mohamed Aghzal, Liangming Pan, Ziyu Yao
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents need to choose actions whose consequences unfold over multiple future steps, yet poor decisions do not reveal whether the model failed to represent those consequences or failed to use them. Mechanistic interpretability has studied internal representations of environment state and plans, but sequential decision making also requires evaluating how candidate actions change future outcomes. Reinforcement learning formalizes this as action value. We study this computation in Qwen2.5-7B-Instruct, Qwen2.5-32B-Instruct, and GPT-OSS-20B across a partially observed Grid environment and WebShop, a simulated web shopping environment. We find that the relative values of candidate actions are linearly decodable from intermediate hidden states, including at states where the policy prefers a worse action. We call this gap between value representation and policy choice value-policy dissociation. To investigate how represented value relates to action selection, we compa

---

### [8] Steering Emergent Behavior in Multi-Agent LLM Systems via Information Networks

**链接**: https://arxiv.org/abs/2611.11714
**作者**: Sepehr Ilami, Babak Heydari
**来源**: cs.MA cs.AI cs.GT cs.SI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly operate in groups, each pursuing an individual objective while jointly determining system performance. If an operator controls which agent observes which other agent, but not their payoffs or messages, how should observations be structured to raise collective welfare? We make the information network (who observes whom) a design object, decoupled from the fixed interaction network over which agents act. Ten identical LLM agents play repeated group-decision games; by default each observes only an anonymous summary of the group's previous-round outcome, and a manager with a fixed budget adds directed observation links that reveal peers' past actions. Across 1,080 episodes and six games spanning coordination, anti-coordination, social dilemmas, and discovery, we ask how much information to share and, at a fixed budget, who should observe whom. Disclosure creates behavioral coupling: observation acts as a contagion channel whose welfare effect 

---

### [9] The Surprising Effectiveness of Deleting Weights in LLM Post-Training

**链接**: https://arxiv.org/abs/2611.10866
**作者**: Jack Lu, Zhenbang Yang, Mike Lasby, Tejas Pote, Yani Ioannou, Mengye Ren
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How little of a pretrained large language model (LLM) has to change for it to acquire new capabilities? We find that zeroing fewer than 0.05% of its weights, with no other modification, matches full fine-tuning (FFT) at scale across three LLM post-training regimes: reinforcement learning with verifiable rewards, supervised fine-tuning, and on-policy distillation. Our method, Deletion Tuning, learns a binary mask over the gate projection of transformer blocks. Two practical advantages follow: the trained mask is hundreds to thousands of times smaller than the corresponding FFT checkpoint, and Deletion Tuning forgets far less, which addresses a central challenge in continual learning. Under reinforcement learning, its prior-task accuracy stays near the base level while FFT, LoRA, and random sparse fine-tuning lose up to 5.4 points. To understand why masking alone suffices, we analyze the geometry of the learned weight changes under reinforcement learning using stable rank, spectrum drift

---

### [10] Done Is Not Correct: Measuring Silent Failures and Self-Verification Calibration When LLM Agents Take CAD Actions

**链接**: https://arxiv.org/abs/2611.10063
**作者**: Carson Rodrigues, Clive Rodrigues, Aravind Reddy G
**来源**: cs.SE cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a large language model (LLM) agent writes parametric CAD code from a natural-language specification, syntactic success decouples from semantic correctness. We release a benchmark and harness that measure this gap directly: 13 specification tasks whose every requirement maps to machine-checkable properties of the produced B-rep, measured by the kernel against published tolerance bands, with reference solutions and the full graded attempt corpus. The exact, self-audited oracle isolates two quantities no prior CAD benchmark reports: the silent-failure rate (a valid, renderable solid, an explicit completion claim, and at least one failed semantic check) and completion-claim calibration. Across four models from four vendors (156 attempts per architecture), single-shot agents claimed completion on 98% of attempts and were silently wrong on 14.1%; a tool-use loop that enforces measure-then-claim cut silent failures to 3.2% and raised claim precision from 64% to 96%, and a four-model abla

---

### [11] WorkflowArena: Benchmarking Executable Workflow Orchestration in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2611.12856
**作者**: Zheng Jiang, Fang Niu, Bo Peng, Houde Qian, Wenyi Li, Deyao Hong 等 (10 人)
**来源**: cs.CL cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly deployed as multi-agent systems rather than as a standalone model operating within a single context. Recent agent harnesses allow the model to instantiate worker agents and to author the executable workflow that coordinates them, shifting the design of system structure from developers to the model at run time. The quality of this organization therefore constitutes a distinct capability, yet existing benchmarks either measure end-to-end task completion or evaluate coordination under structures specified in advance. We formalize this capability as workflow orchestration and introduce WorkflowArena, a benchmark of 145 long-horizon tasks spanning 8 professional domains, from software engineering and formal mathematics to legal analysis and 3D production. Each task specifies an initial workspace and an integrated deliverable composed of interdependent components, which is assessed by a hidden verifier. Agents determine autonomously whether and ho

---

### [12] RTLREX: LLM-Guided Framework for Exact High-Level RTL Recovery

**链接**: https://arxiv.org/abs/2611.10798
**作者**: Wuqian Tang, Fangzhou Liu, Ruijie Wang, TingTing Hwang, Bei Yu, Chun-Yao Wang
**来源**: cs.AR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hardware designs may be available only as gate-level netlists or input-output descriptions when the original register-transfer-level (RTL) design and documentation are not accessible. Low-level representations obscure word-level computation and its finite-width behavior. Recovering high-level RTL from such representations therefore helps engineers understand a circuit's functionality and enables RTL rewriting and resynthesis. A plausible function model is also insufficient unless the generated RTL is equivalent to the original circuit for all input combinations. In this paper, we present RTLREX, a large language model (LLM)-guided framework that coordinates domain-specific tools for function recovery, RTL generation, independent verification, and cost-guided rewriting. Independent verification establishes equivalence between the recovered RTL and the original circuit. The LLM uses tool feedback to select further analyses, revise candidate RTL, and propose syntax-cost reductions. Experi

---

### [13] Pixie: A Context-Aware Multi-Agent Multi-Modal Large Language Models (LLM) Architecture for Digital Marketing

**链接**: https://arxiv.org/abs/2611.10016
**作者**: Vivek Vishwas Vichare, Akshat Singhal, Kirill Dubovikov, Vivek Kumar, Sreyas Chaithanya, Saurabh Verma 等 (8 人)
**来源**: cs.MA cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Pixie, a context-aware, multi-agent large language model (LLM) architecture designed to enhance digital marketing operations across real-time and offline activities. Pixie uses a primary orchestration agent alongside task-specific and reconciliation/reviewer agents to support a broad range of marketing tasks. These agents combine zero-shot and few-shot prompting with marketing data, proprietary expert strategy guidelines, and documentation for proprietary statistical models. We experiment with agentic workflows ranging from single-agent to multi-agent systems. We evaluate them using assessments by trained marketing experts and measurements of LLM output variance, focusing on accuracy, consistency, and domain-specific problem-solving. Results show that Pixie's multi-agent framework improves decision quality and operational efficiency in digital marketing workflows. We assess Pixie on common digital marketing processes, including root-cause analysis and reporting, campaign res

---

### [14] Replay Fidelity in LLM Agent Evaluation: Randomness, Hidden State, and Test Oracles in AppWorld

**链接**: https://arxiv.org/abs/2611.11216
**作者**: You Liu, Quanchao Lu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reproducibility in large language model (LLM) agent evaluation depends on replay fidelity: which parts of an execution trace are reconstructed, controlled, and compared. This matters for agent debugging, failure analysis, and counterfactual evaluation of stateful tool use. We audit all 71 unsuccessful executions in a fixed historical AppWorld corpus using 284 isolated fixed-code replay attempts. Reconstructed declared settings admit 42 cases under printed-output, pre-oracle database-delta, and native-verdict/test-count checks; resetting the random-number generator before each interaction admits 68. The 26-case gap contracts to four under database/oracle checks, with one endpoint unknown. Mechanism studies identify four materialized-state discrepancies despite matching outputs and verdicts. In one admitted endpoint pair, an identical API call yields matching responses but different row effects; common future Python RNG removes that deterministic difference in two paired repetitions. A s

---

### [15] Slim Foundation Models for Latency-Critical Recommendation Serving

**链接**: https://arxiv.org/abs/2611.11013
**作者**: Danyal Aftab, Anas Zafar, Assadig Abakr, Steven Davy
**来源**: cs.IR cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Click-through rate (CTR) prediction is a core component of recommendation and advertising systems. Large language models (LLMs) offer rich semantic priors that improve prediction quality, particularly in cold-start and long-tail settings. Injecting a full-scale LLM into a CTR pipeline is, however, prohibitively expensive at inference time: existing LLM-enhanced CTR methods avoid this cost by caching LLM outputs offline rather than serving the LLM online. We propose a resource-efficient pipeline, SlimFM, that makes online LLM-based semantic modeling practical: (1) dependency-aware structured pruning compresses LLaMA3-8B by 44% to a 4.5B-parameter backbone; (2) LoRA-based field-aware fine-tuning trains the pruned model to produce discriminative field-level semantic embeddings from lightweight textual prompts; (3) a semantic-guided fusion module injects these embeddings into the feature interactions of a conventional CTR model. Across four datasets and six CTR backbones, SlimFM retains ov

---

### [16] Imperfectly Imperfect: Evaluating Graded Cognitive Diversity in LLM Persona Simulations

**链接**: https://arxiv.org/abs/2611.10508
**作者**: Sion Weatherhead, Ben Newell, Aaron Belbasis, Flora Salim
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly used as synthetic participants in social, behavioural, and decision-making research, yet it remains unclear whether they can express graded cognitive diversity as assigned when engaging in simulated behaviour. We introduce a cognition-suite evaluation that tests whether simulated populations reproduce human variation in reasoning, self-reported traits, their associations, and downstream behaviour. Agents conditioned on synthetic or human-derived profiles of cognitive reflection, Need for Cognition, and Big Five personality answer the same suite as a cohort of 473 adults: two newly assembled tests, a Cognitive Reflection Test (CRT) and a Behavioural Reflection Test (BRT) whose decision scenarios measure reflection in behaviour, alongside an established CRT and the two trait questionnaires. Across seven full-battery simulation runs of four models, agents recover Need for Cognition and Big Five trait distributions on self-report questionn

---

### [17] Efficient LLM Adaptation with Forward-Only Passes

**链接**: https://arxiv.org/abs/2611.10610
**作者**: Baichuan Huang, Ananth Balashankar, Amir Aminifar
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference serving is undergoing rapid growth and large-scale deployment, motivating us to rethink how the inference process itself can be leveraged to enable efficient task-specific LLM adaptation. In this paper, we propose a forward-only approach for efficient LLM adaptation with forward-only passes in LLM inference serving. We exploit the angle concentration of activations induced by each singular value decomposition (SVD) component to measure its contribution-dispersed or concentrated-to the angle concentration of the hidden states. Based on this, our forward-only search then efficiently identifies the weight matrix with the highest dispersion that merits rank reduction. We then selectively remove the higher-order components and retain the lower-order components in SVD. Empirical results across diverse datasets demonstrate the competitive accuracy of our forward-only approach, while theoretical analysis shows lower peak memory and greater speedup than the 

---

### [18] BRAT: Bounded Residual-Aligned Training for Stable Multi-Pass LLM Post-Training

**链接**: https://arxiv.org/abs/2611.10873
**作者**: Xunlan Zhou, Yuzhe Zhao, Xuhong Huang, Feng Chen, Xuanlin Chen, Lang Feng 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning for large language model post-training often reuses each batch of sampled rollouts for several gradient passes to amortize the cost of generation. Under such multi-pass reuse, existing objectives fail in different ways: unclipped updates collapse as the policy drifts away from the sampling policy, adding a negative baseline avoids collapse but reinforces every sampled response, and PPO-style ratio clipping cuts off gradients abruptly. We first ask why reuse is fragile. Measuring how well an update estimated from a small rollout group aligns with the KL-regularized target on held-out rollouts of the same prompts, we find that this alignment drops by nearly an order of magnitude from in-sample to held-out rollouts across three base models, suggesting that repeated passes largely overfit the sampled group. Motivated by this finding, we propose Bounded Residual-Aligned Training (BRAT), motivated by a proximal update toward a bounded reweighting of the sampling policy

---

### [19] MetaPI: Constructing Prompt Injection Benchmarks from LLM Agent Benchmark

**链接**: https://arxiv.org/abs/2611.10026
**作者**: Peiran Wang, Chong Xiang, Wenjie Qu, Ying Li, Jiaheng Zhang, G. Edward Suh 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly perform complex tasks using high-privilege tools, making indirect prompt injection (IPI) a critical security risk. However, IPI benchmarks lag behind their rapidly evolving utility counterparts, only offering limited task and environment coverage and relying on narrow, static attack scenarios. In this paper, we propose meta-benchmarking for IPI: transforming existing utility benchmarks into end-to-end IPI evaluation suites that reuse their realistic tasks, environments, and infrastructure. We present MetaPI, an extensible toolkit that automatically identifies plausible injection points, generates realistic attack objectives, optimizes adaptive payloads, and validates attacks in the real environment. Its modular interfaces support heterogeneous environments, agents, defenses, and attack algorithms, allowing new components to be integrated without redesigning the evaluation pipeline. We apply MetaPI to AppWorld, VitaBench, and Terminal-Bench

---

### [20] Safeguarding Agentic AI in Radiology Workflows: A Multimodel Evaluation of Rule-based and Large Language Model-based Verification

**链接**: https://arxiv.org/abs/2611.11541
**作者**: Semil Eminovic, Robin Schmidt, Bogdan Levita, Maximilian Lindholz, Tobias Penzkofer, Jawed Nawabi
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: To estimate how often tool-using large language model (LLM) agents record clinically relevant false or unsupported information in simulated radiology documentation and how much safeguards applied before each action reduce these errors. Materials and Methods: In this simulation study (October 2026), 48 synthetic, radiologist-reviewed base scenarios covered finding communication, tumor board preparation and follow-up management. Forty-three also had a misleading-information variant (91 variants). Six LLM agents (Claude Sonnet 5.5, GPT-6.1-Sol, GLM-5.3, MiniMax M3, Gemma-4-31B, Qwen3.8-27B) completed each variant with permissions only, deterministic rules, and rules plus a locally run LLM checker (1638 episodes). The primary outcome was at least one executed high-severity violation per episode. Risk differences were estimated per agent at base-scenario level and, exploratorily, pooled across agents, with analyses of document access and blocks. Results: With permissions only, 7.3%

---

### [21] PARIS: A multi-agent LLM framework for end-to-end, PRISMA-guided systematic literature reviews with pre-synthesis corpus quality assessment

**链接**: https://arxiv.org/abs/2611.12222
**作者**: Christophe Cruz (ICB, UBE), Hussam Ghanem (ICB, UBE), Samir Jabbar (ICB, UBE) 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Systematic literature reviews (SRs) remain slow and labor-intensive, and most automation tools address single stages of the workflow. We present PARIS (PRISMA Agentic Research Intelligence System), an open-source framework in which a conductor agent running in Claude Code orchestrates 15 specialized large language model (LLM) agents, from scoping a research question to exporting a manuscript draft. Agents are specified declaratively, coordinate exclusively through persisted artifacts that the conductor validates before every transition, and delegate retrieval, bibliometric analysis and scoring to deterministic Python utilities. Three human checkpoints gate study inclusion, corpus adequacy and the synthesis outline. We also introduce QualityScore, a pre-synthesis index that aggregates normalized network, bibliometric, semantic and process sub-scores into a 0-100 grade. Two case studies illustrate both: AI chatbots and university students' learning (388 records, 100 included) and AI-assi

---

### [22] SCALE: Small-Model-First Concept Abstraction with LLM-Guided Experience Internalization

**链接**: https://arxiv.org/abs/2611.12120
**作者**: Hong Su
**来源**: cs.AI cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous agents must continually acquire reusable knowledge from experience without relying on costly large language model (LLM) reasoning for every decision. However, existing experience-based approaches often struggle to transform accumulated observations and reasoning into compact knowledge that lightweight models can independently apply. This paper proposes SCALE, a small-model-first framework that integrates selective LLM reasoning, experience-driven concept abstraction, and knowledge internalization. A lightweight model handles routine predictions, while prediction errors and accumulated cross-episode evidence selectively trigger LLM reflection. The LLM analyzes relevant historical experiences, generates positive and negative counterfactual examples, and proposes reusable concept hypotheses. Independently validated concepts are progressively incorporated into hierarchical neural representations, enabling lightweight models to exploit increasingly abstract knowledge. Meanwhile, 

---

### [23] Inside the Trading Loop: Markets, Models, and Moves with LLM Agents

**链接**: https://arxiv.org/abs/2611.11657
**作者**: Renee Jia, Di Mu, Yao Yu, Tianrui Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We built a hybrid multi-agent trading system that combines large language model (LLM) analysts with momentum-based portfolio construction and rule-based execution. Company-news and macroeconomic agents return structured reports to a coordinator that sets stock weights and cash reserves. We evaluate the portfolio engine using its broker-recorded paper account, which operated with deterministic fallbacks, and compare LLM-enabled configurations through retrospective replays. From March 11 to August 28, 2026, the account returned 34.5%, compared with 14.4% for the S&P 500 fund SPY over the same dates. This raw return advantage came with a larger maximum drawdown. Reconstructed policies also finish above matched SPY and QQQ references when assessments are used in the same session or deferred to the next. Design comparisons examine cash authority, selective invocation, and response contracts. A constant-cash control gives a return estimate close to stance-based sizing, and shorter report con

---

### [24] Don't Blame The Preferences: Examining The Emergence of Sycophancy in LLM Training

**链接**: https://arxiv.org/abs/2611.10045
**作者**: Chao Peter Yang, Catherine Zehr, Pranav Bijith, Brandon Fain
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI sycophancy, the tendency of large language models (LLMs) to flatter users and affirm their beliefs, can undermine accuracy and contribute to misinformation, dependence, and overconfidence. Although prior work has benchmarked sycophancy in released models and proposed mitigations, its origins during training remain poorly understood. Preference alignment methods such as RLHF and DPO are often blamed, but their effects are rarely compared with earlier training stages. We investigate sycophancy across the training pipelines of three model families and three benchmarks. We find that sycophancy is largely established by the end of supervised fine-tuning (SFT), rather than introduced by preference alignment. Across all nine model benchmark combinations, SFT checkpoints attain at least 92% of preference aligned models' sycophancy scores and at least 85% of final models' scores; on average, they are about as sycophantic as final models. Preference alignment increases sycophancy in only four

---

### [25] IF:CARGO: LLM-Based Semantic Compilation for Al-Native Rule Programming Games

**链接**: https://arxiv.org/abs/2608.12195
**作者**: Ting-Chen Hsu, Lianye Zhang, Jiangxu Lin, Zhaoyi Yu, Fei Qin, Zihao Chen
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Zeroth-Order Riemannian Optimization on Fixed-Rank Manifolds for LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2611.10792
**作者**: Xinjue Wang, Xiuheng Wang, Yejun Zhang, Sergiy A. Vorobyov, Esa Ollila
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Zeroth-order (ZO) optimization estimates descent directions from function values alone, which removes the activation storage required by backpropagation and makes it attractive for memory-efficient fine-tuning of large language models (LLMs). Existing low-rank ZO methods either parameterize the additive update through Euclidean factors with a non-unique representation, or restrict each finite-difference direction to be low-rank. In this work, we propose to constrain each additive update block to a fixed-rank matrix manifold while keeping the pretrained weights frozen, so the learned update remains rank-constrained throughout fine-tuning. On this geometry, we build a Riemannian ZO gradient estimator that projects a random matrix onto the tangent space, normalizes it to correct the scale mismatch induced by projection, and further propose Zeroth-order Riemannian Gradient Descent (ZO-RGD) and its smoothed variant, ZO-RGD-S. We show that the ambient finite difference matches its retracted 

---

### [27] When Safety Becomes An Outlier: Understanding the Retention of LLM Safety Behaviors

**链接**: https://arxiv.org/abs/2611.10971
**作者**: Binchi Zhang, Hadi Abdullah, Yiwei Cai, Jundong Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety-aligned large language models often lose their safety behaviors after fine-tuning, even when safety data are included. While this fragility is well documented, its underlying cause remains unclear. In this paper, we propose that formulaic refusal strings can function as outlier modes: narrow, weakly grounded response patterns that are easy to fit but vulnerable to subsequent updates. Controlled experiments support this account: fixed refusals are acquired much like arbitrary constant strings, in contrast to prompt-grounded natural responses. Motivated by these findings, we introduce Naturalness-Enhanced Safety Targets (NEST), a safety alignment framework that improves safety retention by constructing natural, context-aware safety targets that keep safety responses within the model's existing output distribution and grounded in semantics. We instantiate NEST in both supervised and preference-based alignment settings, using perplexity under the original model as a proxy for distri

---

### [28] Understanding Efficient LLM Serving: An Empirical Study of Frameworks, Optimizations Algorithms, and Real-World Adoption

**链接**: https://arxiv.org/abs/2608.03036
**作者**: Forough Majidi, Mohammad Mehdi Morovati, Foutse Khomh, Heng Li
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] When Fancy Eviction Fails: Rethinking Cache Replacement For LLM Prefix Reuse

**链接**: https://arxiv.org/abs/2609.28870
**作者**: Yiyu Liu, Minlan Yu, Juncheng Yang
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] When Disclosure Is Compulsory: Evaluating Ride-Hailing Rebalancing Policies with Self-Interested LLM Driver Agents

**链接**: https://arxiv.org/abs/2610.41132
**作者**: Xinyu Wang, Andres Fielbaum
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Autonomy Is Absent, Not Eroded: An Observational Study of User Autonomy in Multi-Turn LLM Conversations

**链接**: https://arxiv.org/abs/2611.09923
**作者**: Chaoran Chen (University of Notre Dame), Isabel Barber\'a (Independent Researcher), Yuhuai Wei (Independent Researcher)
**来源**: cs.HC cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Does prolonged interaction with Large Language Models reduce users' observable autonomy during conversation? We test this degradation hypothesis by scoring user autonomy across 2,877 multi-turn conversations (46,952 turns) from WildChat and validating on 500 conversations from LMSYS-Chat-1M. Our core finding is a null result: population-level autonomy remains stable throughout conversations, only 4.7% of conversations show meaningful decline, and an apparent decrease at later turn positions is explained by survivorship bias. Instead, the dominant pattern is not erosion but absence: 80.8% of conversations exhibit zero or low autonomy throughout. When autonomy engagement occurs, it is self-reinforcing (persistence doubles from 40% to 85% over consecutive turns). These findings reframe the problem: the risk is not that LLMs progressively degrade users' observable autonomy, but that most users never engage in independent reasoning during the interaction.

---

### [32] Incorporating Machine-Others: An Enactive Exploration of Human-LLM Interactions

**链接**: https://arxiv.org/abs/2610.39869
**作者**: Elena C. Cuffari, Marta P\'erez-Verdugo, Xabier E. Barandiaran
**来源**: cs.HC cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] SadaqahStories: A Verified English-Arabic Corpus of Charity Stories for Children, with an Audit of Errors in AI-Drafted Religious Narratives

**链接**: https://arxiv.org/abs/2611.12078
**作者**: Wajdi Zaghouani, Spencer Striker
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present SadaqahStories, a parallel English-Arabic corpus of 41 illustrated four-page stories about charitable giving in Islam (Sadaqah, Zakat and Waqf), written for readers aged 7 to 18. The stories were first drafted with large language model (LLM) assistance, then audited against hadith collections, Qur'an references and historical sources, and finally rewritten for children and signed off by an Islamic scholar. Every story carries an evidence label and links to its sources. We release all three versions of each story (AI-assisted draft, audited text, final child-oriented text) together with the correction log, so the corpus can be used to study how AI drafts of religious and historical content go wrong. The audit found substantive errors in 39 of the 41 drafts. The most frequent were unsupported specific details (dates, figures, prices, names), invented quotations, institutions or anecdotes, and conflation of separate events or people; six drafts contained errors in the wording, 

---

### [34] Beyond Query Similarity: Safety-Conditioned Cache Routing for LLM Response Reuse

**链接**: https://arxiv.org/abs/2611.10418
**作者**: Shilong Pan, Zhiliang Tian, Weiguo Chen, Zihan Chen, DongSheng Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Semantic response caching reuses a cached response for a semantically similar query to improve LLM inference efficiency. However, query similarity alone can lead to unsafe reuse when safety conditions change. Existing approaches improve cache safety through stricter similarity checks, context-aware validation, or response verification, yet they may still miss safety conflicts between the cached response and the new request or introduce unnecessary verification overhead. We argue that safe and efficient semantic caching requires a reuse policy that makes the cached response's safety conditions explicit and uses them to guide the reuse decision with a balance between safety and utility. In this paper, we propose SafeCache, a safety-aware framework that separates candidate retrieval from safety approval and formulates semantic response reuse as a safety-conditioned routing problem. SafeCache matches each cached-response condition against the new request and aggregates the per-condition mi

---

### [35] SPRING-5: Measuring Tool Documentation Repair for LLM Agents by Efficiency

**链接**: https://arxiv.org/abs/2611.10040
**作者**: Guan Zheng Huang
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Methods that repair tool documentation automatically are mostly evaluated on task accuracy. We report a benchmark that scores them on cost. SPRING-5 is 20 tool families and 344 tasks, each with a deliberately degraded specification, a hand-written honest one, a deterministic backend and an answer key, scored on calls charged against the ideal call path. A wrong answer is charged the full call budget, so this cost index largely tracks the completion rate, and we report calls per correct task beside it, which carries no such charge. Over 2,644 baseline sessions, 54% of wrong answers arrive with no rejected call, no refusal and no retry. The benchmark carries three validity instruments. A build-time ceiling assertion requires the honest specification to reach the ideal path and fails systematically on only one family. A dud rule names the families a stronger model solves cold and catches four. A directly measured noise floor shows that two evaluations of a byte-identical specification dif

---

### [36] Actions Should EARN Their Credit: Test-Time Adaptation and Route Consolidation for Frozen LLM Agents

**链接**: https://arxiv.org/abs/2611.11565
**作者**: Bian Sun, Kevin Zhai, Mubarak Shah, Song Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can use feedback from repeated attempts to improve their decisions without updating model parameters. However, positive action credits can continue to favor actions that repeatedly achieve the same score, even when higher scores are achievable. Under a fixed interaction budget, trying new actions in the final attempts can also lower performance. We introduce EARN, a method that uses past experience to guide further progress and retain earlier performance through conditional reuse of effective action sequences. EARN reduces action credits for reaching scores repeatedly attained in earlier episodes and assigns larger credits to action segments that reach higher scores. These credits adjust the probabilities of LLM-proposed actions. During the final episodes, EARN directly replays stored actions when the current context matches the recorded context and the actions remain available, bypassing LLM candidate generation. We evaluate performance at the end of the interaction budget 

---

### [37] Nominate-then-Adjudicate: LLM-Assisted One-Pass and Per-Instance MIP Solver Tuning

**链接**: https://arxiv.org/abs/2610.29391
**作者**: Yifan Zhao, Qianyang Zhao, Xinyu Guan, Kai Wei, and Yuming Deng
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] AutoC2V: Synthesis-Guided LLM Training for QoR-Optimized C++-to-Verilog Generation

**链接**: https://arxiv.org/abs/2611.10824
**作者**: Guanqi Lyu, Fei Zhao, Zhaojun Lu, Jiaji He, Yongqiang Lyu
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-level synthesis (HLS) can translate C/C++ kernels into register-transfer level (RTL) designs, yet generating high-quality hardware still relies heavily on manual pragma tuning and repeated synthesis evaluation. We propose AutoC2V, a C++-to-Verilog generation framework driven by real synthesis feedback that enables large language models (LLMs) to directly generate RTL with improved quality of results (QoR) from synthesizable C++ kernels. We construct training data from real synthesis results, including synthesizable C++ source code, the corresponding Verilog RTL, QoR metrics, and optimization objectives. Using this dataset, we align the model toward synthesis-aware RTL generation through Supervised Fine-Tuning (SFT) and Group Relative Policy Optimization (GRPO). To reduce the high cost of repeatedly invoking real synthesis during GRPO, we design the QoR Prediction Reward Model (QoR RM), which predicts latency and resource metrics by encoding RTL into long-context semantic represent

---

### [39] VEX-Bench: Benchmarking Verification Complexity of LLM-Generated Misinformation

**链接**: https://arxiv.org/abs/2609.35028
**作者**: Hanxun Huang, Yutao Wu, Qizhou Wang, Silvia Monta\~na-Ni\~no, Yige Li, Xiang Zheng 等 (10 人)
**来源**: cs.LG cs.AI cs.CL cs.CY cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Synthesizing End-to-End Human Trajectory Anomalies: An LLM-Driven Framework with Map-Constrained Routing and Sensor Noise Simulation

**链接**: https://arxiv.org/abs/2606.10314
**作者**: Yueyang Liu, Joon-Seok Kim, Andreas Z\"ufle
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] Rescaling confidence: What scale design reveals about LLM metacognition

**链接**: https://arxiv.org/abs/2603.09309
**作者**: Yuyang Dai, Yuxia Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] FinCutBench: A Continually Updated Benchmark for Measuring the Temporal Boundaries of LLM Financial Knowledge

**链接**: https://arxiv.org/abs/2611.11588
**作者**: Siyuan Li, Ke Wan, Boyong Hou, Yujie Deng, Zixuan Yuan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In financial backtesting and other point-in-time tasks, external inputs can be restricted by date, but model parameters may retain financial facts disclosed later, introducing parametric look-ahead bias. We introduce FinCutBench, a continually updated monthly financial knowledge benchmark for measuring how far a fixed model's financial knowledge extends over calendar time. The current dataset contains 9,000 Chinese and English four-option multiple-choice questions from January 2023 to September 2026, covering Chinese and U.S. markets and four categories of financial information. We construct monthly knowledge profiles using the approximate months in which the tested facts became public. After a profile passes the decline test and knot checks, we define the FinCut Boundary as the first month when the fitted profile reaches its lower level, and report the stability of the estimated date under resampling. Boundary dates and localization precision vary across models. Using the independentl

---

### [43] Token Inflation: How Dishonest Providers Can Overcharge for Large Language Model Usage

**链接**: https://arxiv.org/abs/2605.30040
**作者**: Shahinul Hoque, Jinghuai Zhang, Jinyuan Sun, Fnu Suya
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Same Error, Different Recovery: How Delivery Changes LLM Agent Behavior

**链接**: https://arxiv.org/abs/2611.11581
**作者**: Sunghyeun Woo, Javier Conde, Pedro Reviriego
**来源**: cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A tool-using language model must decide whether to retry a failed call, correct it, or stop and tell the user. The error text alone may not be enough: the same feedback can lead to different actions depending on where it appears in the conversation. We isolate this delivery problem by varying placement, guidance, retained history and turn structure. Two studies with plans fixed before data collection, across 13 open models from 3B to 70B parameters, compare the next action and subsequent task completion, with exact deterministic reruns. A new user turn that retains the failed exchange avoids the severe stopping failure observed in Llama models when that exchange is removed. It is non-inferior to history rewriting in pooled synthetic comparisons, but is not best for every model. We implement this form as an opt-in recovery layer within a deterministic inference engine and evaluate it on public benchmarks and a coding agent. On ToolMaze, it raises success on explicit errors by 14.2 point

---

### [45] OrigaMI: An LLM Serving System with First-Class Interpretability Apps

**链接**: https://arxiv.org/abs/2607.22595
**作者**: Michael Blum, Mark Silberstein, Yaniv David
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] LAPO: KL-Free Logit-Averaged Policy Optimization to Leverage RL and SFT in LLM Post-Training

**链接**: https://arxiv.org/abs/2605.20555
**作者**: Xingwei Gan, Ying Zhu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] CIDERS: Cloud-Edge LLM Collaborative Learning via Accelerating Personalized Bilevel Optimization

**链接**: https://arxiv.org/abs/2609.15664
**作者**: Victor H. Chen, Hairui Yu, Stella K. Chung and Hong Yan
**来源**: cs.DC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Continual Instruction Tuning for LLM-ased Management of Continuum Resources

**链接**: https://arxiv.org/abs/2611.10292
**作者**: Lanpei Li, Antonino Vaccarella, Vincenzo Lomonaco, Massimo Coppola
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly explored for resource management across the Cloud-Edge continuum. However, embedding LLMs directly inside latency-sensitive control loops places inference latency, execution jitter, and hallucination risks on the critical path. This study argues for a different use of LLMs: a continually instruction-tuned intent compiler that runs once per management intent or declared context change, above a fast, deterministic tactical controller that handles all low-latency runtime actions. We formulate intent compilation as a continual instruction tuning problem, because management intents arrive sequentially and accumulate while infrastructure and workload contexts drift. Unlike recent LLM-based management frameworks, our design scores the model's outputs by execution, so that catastrophic forgetting can be measured in the executed objective of the underlying controller. On a continuum simulator with a 2B backbone and parameter-efficient adapters, prel

---

### [49] Measuring What Tool-Using LLM Agents Actually Do: Structured Validation, Causal Error Propagation, and Fabricated Tool Use

**链接**: https://arxiv.org/abs/2604.16706
**作者**: Bhaskar Gurram
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Honeyval: A Comprehensive Evaluation Framework for LLM-powered HTTP Honeypots

**链接**: https://arxiv.org/abs/2605.29963
**作者**: Mark Vero, Fabian Kaczmarczyck, Ivan Petrov, Ilia Shumailov, Jamie Hayes, Niels Heinen 等 (9 人)
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] Conformal Fair Decoding for Large Language Model Recommenders

**链接**: https://arxiv.org/abs/2611.10285
**作者**: Ziwei Wu and Jingrui He
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate personalized recommendations without task-specific training, but changing a protected attribute while holding interaction history fixed can alter the semantic content of recommended items. We study fairness control when model weights and full-vocabulary logits are unavailable. We propose Fair- Rec, an item-level decoding framework that uses an offline-calibrated semantic-disparity threshold and controls candidate selection as recommendation lists are generated. A hard variant filters candidates against the threshold; a soft variant trades off candidate likelihood and disparity while adapting a penalty using observed violations. Under an explicit uniform enforceability assumption, we establish a pathwise O(1/T) upper bound on the excess empirical violation rate of the soft decoder. Experiments on MovieLens-1M and Amazon Movies & TV using Qwen3-8B and Llama3.1-8B-Instruct show that the soft variant lowers measured counterfactual disparity relativ

---

### [52] SocialGym: Evaluating LLM Social Intelligence through Verifiable Multi-Agent Games

**链接**: https://arxiv.org/abs/2608.09128
**作者**: Keyu He, Xuhui Zhou, Maarten Sap
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [53] ACED-Bench: Evaluating How LLM Agents Acquire and Act on Causal Evidence

**链接**: https://arxiv.org/abs/2610.14381
**作者**: Yiwei Chen, Amila Weerasinghe, Siddharth Biswal, Utkrisht Rajkumar, Olcay Boz, Taylor Berg-Kirkpatrick 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Rethinking Supervision Targets for Multimodal LLM Unlearning: Less Private Information, Reduced Distribution Shift

**链接**: https://arxiv.org/abs/2611.09939
**作者**: Leijiang Gu and Zhen Zeng and Feng Li and Le Zhang and Zenglin Shi
**来源**: cs.CL cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) can memorize and reproduce sensitive information from their training data, posing significant privacy risks. Their ability to encode knowledge across both textual and visual modalities further complicates the selective removal of such private information. Many existing methods guide model unlearning by training the model toward constructed labels or output distributions, which we refer to as supervision targets. However, these methods often suffer from a trade-off between forgetting effectiveness and model utility. We identify supervision target limitations as a key factor in this trade-off and empirically show that targets containing more private information lead to insufficient forgetting, while larger distribution shifts from the original output distribution are associated with greater utility degradation. Motivated by these findings, we propose FFN-Perturbed Self-Distillation (FPD), which starts from the teacher's original output distributio

---

### [55] Sentence-Level Attribution for Black-Box Large Language Model Outputs via Energy-Based Surrogates

**链接**: https://arxiv.org/abs/2608.02879
**作者**: Maryam Rezaee, Pooriya Safaei, Maryam Asgarinezhad, Fatemeh Seyyedsalehi
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] DramaGrow: A Regime-Aware Benchmark for Auditing LLM Judges of Multi-Episode Drama

**链接**: https://arxiv.org/abs/2611.09938
**作者**: Hui Zhang, Yibo Su
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs can now draft complete multi-episode dramas, and LLM judges are increasingly used to evaluate them. Assessing the reliability of these judges is difficult because drama quality encompasses specification-backed errors, reproducible preferences, and legitimate disagreement among human raters. Most existing evaluations reduce these cases to a single score from one judge call and leave tie calibration, call-to-call variation, and the vote margin underlying the human reference unreported. We introduce DramaGrow, a regime-aware benchmark and audit protocol for AI-generated Chinese five-episode drama. The benchmark assigns verifiable constraint violations, four-of-five preferences, and within-panel disagreements to separate denominators and evidence rules. It contains 800 episodes, 120 byte-preserving interventions, and 1,155 blinded five-rater records, including a frozen extension with 114 supermajority pairs and 21 disagreement pairs. On the frozen sets of 114 preference pairs and 35 c

---

### [57] DistDebug-Bench: Can LLM Agents Diagnose Bugs in Distributed Systems?

**链接**: https://arxiv.org/abs/2611.03523
**作者**: Yuxuan Jiang, Chenglin Liu, John Rose, Mason Miller, Ruthesh Thavamani, Juntao Wu 等 (9 人)
**来源**: cs.SE cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] A Communication-Theoretic Framework for LLM Agents: Cost-Aware Adaptive Reliability

**链接**: https://arxiv.org/abs/2605.09121
**作者**: Hamed Omidvar and Vahideh Akhlaghi
**来源**: cs.LG cs.AI cs.CL cs.IT math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] GARP: Real-Time Generative Agents on Local Hardware in a Game Engine

**链接**: https://arxiv.org/abs/2611.11064
**作者**: Piero Molino, Patrick John Chia, Federico Bianchi, Jonathan P. Chen, Paul Szerlip
**来源**: cs.AI cs.HC cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative agents are game characters whose plans, conversations, and memories are written on the fly by a large language model (LLM). The original Generative Agents demonstration used cloud inference in a custom simulation. We present GARP, a platform for real-time generative agents inside Godot, and describe the Character Behavior System used in GARP 2. The complete loop runs on local hardware using a 3B-parameter open-weight model and no cloud service. Alongside the original planning, memory, and reflection, GARP gives each agent an emotion system driven by LLM appraisal, four graded personality axes drawn from the Big Five that set simulation parameters as well as prompt text, six needs whose urgency grows over time, and pairwise relationships updated after every conversation. The system narrows 50+ candidate actions to typically 3-8, constrains model responses with JSON schemas, and surfaces important memories in decision prompts. A layered optimization strategy (an adjustable gam

---

### [60] Weight-Space Programming for Medical Imaging: Do We Still Need Training Data?

**链接**: https://arxiv.org/abs/2611.12066
**作者**: Maximilian Lindholz, Richard Ruppel, Annette Milnik, Sebastian Halskov, Semil Eminovic, Charlie A. Hamm 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can a large language model (LLM) write the parameters of a medical image classifier from medical knowledge alone, without any training data? Such classifiers normally require labelled images, which are costly and often unavailable. We investigate this question through weight-space programming (WSP), in which an LLM writes or adapts the weights and biases of a neural network directly, without optimisation on training data. Claude Opus 5.5 and GPT-6 Astra each generate the parameters of a small LeNet-style CNN in a single reply, without tool use and without access to any image. We compare these networks against zero-shot MedSigLIP and against the same architecture trained on labels using the Adam optimiser, across 7 classification tasks in four modalities: chest X-ray, breast ultrasound and abdominal CT (all from MedMNIST), and pelvic MRI (SynthUterus). The LLM-written networks perform above chance on all six MedMNIST tasks, with a mean test AUC of 0.719 for Opus and 0.711 for Astra. Bot

---

### [61] Decomposing Earth Embeddings with Sparse Autoencoders

**链接**: https://arxiv.org/abs/2611.11398
**作者**: Vitus Benson, Fanny Yang, Markus Reichstein
**来源**: cs.LG cs.CV physics.geo-ph
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth observation foundation models produce global metre-resolution embeddings that underpin work across agriculture, ecology, hydrology, and beyond. Yet these embeddings are opaque: each dimension entangles unrelated physical concepts, which makes them difficult to interpret and their robustness hard to assess. Here, we propose sparse autoencoders (SAEs) as a principled way to decompose Earth embeddings into sparse, approximately monosemantic features over an overcomplete dictionary. Because LLM judges of interpretations do not transfer to satellite pixels, and spatial autocorrelation matters, we introduce a tailored evaluation protocol. It scores any SAE on reconstruction at matched sparsity, alignment with reference concepts, and spatial scale, each against baselines that include an SAE whose decoder is a frozen random dictionary. On this protocol, SAEs reconstruct AlphaEarth and Tessera embeddings better than every baseline at matched sparsity. Their features align with far fewer r

---

### [62] An LLM-Orchestrated Multi-Modal Chatbot for Tomato Disease Consultant

**链接**: https://arxiv.org/abs/2611.10608
**作者**: Ngoc-Son Le, Khanh-Nghi Phan, Ngoc Hong Tran
**来源**: cs.AI cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper introduces a chatbot developed to assist in diagnosing common diseases in tomato plants through natural language interaction. Users can describe symptoms in text. Then, the chatbot responds with the most likely disease, and basic treatment suggestions and related image-based reasoning. The system leverages pre-trained Mistral and Llama 3.2 large language models. The system is also built using LangChain and Streamlit to provide a lightweight and offline-friendly interface. This work targets to support tomato growers a fast and accessible tomato plant health guidance when the technical expertise is not available nearby, especially in the remote areas. The experimental results are promising and encourage further improvement of the chatbot for future real-world deployment.

---

### [63] Policy Over Purpose: Auditing LLM Content Moderation of Reclaimed Slur Usage

**链接**: https://arxiv.org/abs/2611.10327
**作者**: Christina Chance and Kai-Wei Chang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Perspective API is deprecated, platforms are turning to large language models for content moderation, encoding policy as natural language that the model must interpret at inference time. Reclaimed slurs test this design directly. The same term can express in-group pride or target the community that reclaimed it, and misreading it silences the speech moderation is meant to protect. We audit four general-purpose LLMs and four moderation-specific systems, with Perspective API as a legacy baseline, on IYKYK, a corpus of reclaimed and derogatory usage of three slurs annotated by community members. Across the policy, decision, reasoning, disparity, and steering layers of this audit, we find that whether a system was purpose-built for moderation explains little about how it handles reclaimed language. No system reliably agrees with community judgment, and all fail most on language reclaimed within Black communities. What separates systems is instead how their policy is represented. Only sy

---

### [64] From History to State: Constant-Context Skill Learning for LLM Agents

**链接**: https://arxiv.org/abs/2605.05413
**作者**: Haoyang Xie, Xinyuan Wang, Yancheng Wang, Puda Zhao, Feng Ju
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Crustify: Repository-Level Generation of Safe Rust Bindings with LLM Agents and Coverage-Guided Testing

**链接**: https://arxiv.org/abs/2611.10394
**作者**: Marius Momeu, Marius Arvinte, Cory Cornelius, Koushik Sen
**来源**: cs.PL cs.AI cs.CR cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wrapping C code in a safe Rust interface lets Rust applications use it without writing unsafe code, until the code itself is migrated to Rust. Such bindings are tedious and error-prone to write, however: their internals use unsafe code that the Rust compiler does not check, so a single mistake can introduce undefined behavior (UB), and they have so far been written mostly by hand. We present Crustify, an agentic co-translator that generates safe Rust bindings for repository-level C libraries. Crustify schedules a target's types and symbols into dependency-ordered waves of independent batches that agents bind concurrently. Its agents derive the ownership and lifecycle contract of every pointer and type they wrap, check each binding with coverage-guided equivalence and UB tests under sanitizers and Miri, and review every wave. They build on three tools that we contribute: (a) ffibox, Rust primitives for C/Rust interop that mirror Box, Arc, and Vec for C objects without ever forming a ref

---

### [66] LLM-as-Code: Agentic Programming for Agent Harness

**链接**: https://arxiv.org/abs/2606.15874
**作者**: Junjia Qi, Zichuan Fu, Jingtong Gao, Wenlin Zhang, Hanyu Yan, Xian Wu and Xiangyu Zhao
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] CompAIssionate Other: Identity Assumptions in LLM Responses to Distress

**链接**: https://arxiv.org/abs/2611.10808
**作者**: Drishti Goel, Ethan M. Nguyen, Violeta J. Rodriguez, Koustuv Saha
**来源**: cs.HC cs.AI cs.CL cs.CY cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Individuals experiencing suicidal ideation (SI) or psychological distress may disclose their social identities when seeking support from LLMs. Attending to identity-related stressors can be important for providing contextually appropriate and empathetic support. However, disclosing an identity does not necessarily mean that it is a cause of distress. In this work, we audit how LLMs interpret distress through disclosed identities. Using paired counterfactual interventions, we evaluate six LLMs across two SI and distress datasets, 16 identity and control conditions, and two prompting protocols. Our findings suggest that models can transform identity disclosures into explanatory narratives, attributing distress to presumed identity-related adversity. These assumptions frequently appear within otherwise empathetic responses, particularly when marginalized identities are disclosed. We contextualize our findings through the lens of compassionate othering to characterize these patterns as a f

---

### [68] On the Relative Security of Prompt Injection: Mechanised Definitions, Defences and Verdicts for LLM Agents

**链接**: https://arxiv.org/abs/2611.11506
**作者**: Brijesh Dongol
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM agent that reads untrusted content, such as an email or a web page, may follow instructions hidden in it. Noninterference is too strong for such agents, since a useful agent lets untrusted content influence what it does and may disclose the user's data by design, and declassification needs a release policy written for each task. We instead state security relative to a reference agent, which runs the same plan under the same runtime monitor with a model that never obeys untrusted content. An agent is relatively secure if every leak it has is a leak the reference already has. Our framework, PlanTERS, instantiates relative security, a notion from speculative execution, with a small agent language in which the attacker chooses how the model follows instructions, a composition with runtime monitors, and attacker models that differ in what they observe. A fence theorem shows that revoking injectable tools at the first untrusted read, and never granting them back, makes every plan rela

---

### [69] Late but Valuable: Why Deadlines Change the Measured Value of LLM Reasoning

**链接**: https://arxiv.org/abs/2611.11910
**作者**: Sina Barazandeh, Benjamin E. Lundell, Jose Lugo-Martinez
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly plan and run experiments in automated laboratories. These experiments keep running while the model reasons and run on schedules with hard deadlines. If an LLM-generated answer arrives late, the system executes a safe fallback action instead, such as rejecting a sample. This creates a systems problem that standard serving metrics do not capture. An answer that matches the fallback adds no value, and answers that differ from the fallback may require more reasoning time. Reporting answer quality and latency separately can therefore overstate the value of reasoning. We test this on synthetic sample decisions, where the best choice is known exactly and a runtime enforces the deadline. We compare one LLM's fast mode, which answers directly, with its thinking mode, which reasons first. In a prespecified replay of 1,200 new decisions, thinking answers that missed a deadline were worth about five times as much as on-time ones. Multiplying the on-time ra

---

### [70] HARDTESTGEN: A High-Quality RL Verifier Generation Pipeline for LLM Algorithmic Coding

**链接**: https://arxiv.org/abs/2505.24098
**作者**: Zhongmou He, Yee Man Choi, Kexun Zhang, Jiabao Ji, Junting Zhou, Dejia Xu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [71] Beyond Reasoning: RL-Policy Guided LLM Inference for Efficient Strategy in Liar's Poker

**链接**: https://arxiv.org/abs/2511.03724
**作者**: Richard Dewey, Janos Botyanszki, Ciamac C. Moallemi, Andrew T. Zheng
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] The Infrastructure Divide: Analyzing Community Stance on Data Center Development via Reddit

**链接**: https://arxiv.org/abs/2611.10109
**作者**: Yoko Koyama, Gongfan Chen, Mansi Saxena
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid expansion of AI-driven data center construction has outpaced public engagement: an estimated $64 billion in U.S. data center projects were blocked or delayed by local opposition between May 2024 and March 2025, yet the concerns driving this resistance remain poorly characterized. Prior engagement methods such as surveys and hearings are introduced late in the planning process, and no study has systematically mined social media to measure community stance at scale. To address this gap, this study presents an LLM-powered opinion-mining framework and applies it to 798 Reddit posts and 102,328 associated comments spanning a decade. An open-source large language model, guided by a Chain-of-Stance prompting framework and three domain-specific labeling rules, classified stance at 83% of the human inter-reviewer agreement ceiling. Opposition dominated discourse volume rather than disapproval: against posts outnumbered favor posts 2.6:1 and generated 8.5 times more comments, and this 

---

### [73] Phase-Conditioned Reward Shaping for Token-Efficient LLM Reasoning

**链接**: https://arxiv.org/abs/2611.11024
**作者**: Zhe Chen, Xiaolin Zhou, Xiyang Hu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Extended reasoning can help language models solve complex problems, but long responses often contain both useful computations and redundant checks. Conventional length penalties encourage shorter responses without distinguishing the functions of intermediate steps. We propose Phase-Conditioned Reward Shaping (PCRS), a framework that combines phase identification with training-time reward allocation. We investigate two classification routes: PCRS-H with a hidden-state classifier and PCRS-T with a frozen text classifier. Our main text classifier implementation assigns overlapping reasoning, execution, and revision labels to native chunks, then uses these labels and exact repetition to adjust existing token penalties. We compare the completed configurations on six mathematical and scientific reasoning benchmarks and examine four reward-weight settings with the text classifier. Compared with a baseline using token-level length penalties, the default text classifier configuration reduces me

---

### [74] GRUFF: LLM Pronoun Fidelity, Reasoning, and Biases in German

**链接**: https://arxiv.org/abs/2605.30214
**作者**: Fabian Mewes and Anne Lauscher and Vagrant Gautam
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [75] Rethinking the Value of Agent-Generated Tests for LLM-Based Software Engineering Agents

**链接**: https://arxiv.org/abs/2602.07900
**作者**: Zhi Chen, Zhensu Sun, Yuling Shi, Chao Peng, Xiaodong Gu, David Lo 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [76] When the Same Prompt Gives Different Answers (and the Same Answer Isn't Always Right): A Taxonomy of Failure Mechanisms, Testing, and Mitigation Strategies for LLM-Assisted Evidence Synthesis Read-and-Evaluate Tasks

**链接**: https://arxiv.org/abs/2610.39070
**作者**: Carole Lunny, Ian Goodman, Stefano Berrone, Connor TA Brenna, Emma K Reid, Ivan Perez-Neri 等 (10 人)
**来源**: cs.AI cs.PF stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [77] Multi-Turn Semantic Caching for Low-Cost LLM Serving

**链接**: https://arxiv.org/abs/2611.01077
**作者**: Baran Atalar, Selly Beyene, Xutong Liu, Carlee Joe-Wong
**来源**: cs.LG cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] CHO-Bench: How Do Context Hints Affect Ad Rankings in LLM Advertising?

**链接**: https://arxiv.org/abs/2611.11955
**作者**: Shiqi Zhang, Yang Fei, Xiaokui Xiao
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM advertising selects advertisements based on user conversations, where user needs may extend beyond explicit product searches. ChatGPT Ads allows advertisers to provide natural-language context hints describing what they offer, who may find it useful, and when it may be useful, as additional information for ranking advertisements across diverse user conversations. However, how to effectively construct these hints remains unclear. We formulate Context Hint Optimization (CHO) as the problem of constructing context hints to improve an advertisement's ranking under a given budget. Drawing on established marketing frameworks, we develop seven context hint generation strategies covering What, Who, and When, along with a Unified strategy that combines all seven dimensions. We introduce CHO-Bench and conduct over 1.19 million paired evaluations across five datasets using embedding-based and LLM-based rankers. Our results show that context hints improve advertisement rankings under the evalu

---

### [79] MJ: Multi-turn LLM Jailbreaking via Decomposed Credit Assignment

**链接**: https://arxiv.org/abs/2607.11070
**作者**: Junyoung Park, Namgyu Park, Sechan Lee, Yoon-Chan Jhi, Jihoon Cho, Sangdon Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] Peer Memory Changes Who LLM Agents Consult Without a Detected Gain in Answer Accuracy

**链接**: https://arxiv.org/abs/2611.09990
**作者**: Jeffrey Chu, Anjali Joseph, Rivan Mandot, Feker Demere, Vincent Li
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems often reuse the same agents across tasks, creating an opportunity to draw on past interactions when deciding whom to consult. We study this form of memory with PeerMem, which saves MACE's LinUCB state and reuses it when the same agents return. Using six agents, a fixed set of 80 HotpotQA questions, and 12 paired lineages per model, we compare cold, warm, and shuffled initialization in an answer-exchange protocol with reference-answer feedback. Under stable evidence access, warm memory lowers pooled hindsight regret and increases consultation of other evidence holders on Qwen3-32B and Gemma-4-31B-it, while final token F1 differences remain uncertain. Qwen interaction traces further show that warm agents more often encounter peer answers that score above their own prior answers. We extend the evaluation to Qwen3.5-9B using freshly learned memory to compare warm and cold initialization under reassigned and paired stable roles. The primary changed-minus-stable final

---

### [81] A local language model layered with rule-based and neural detectors for clinical text de-identification: an open-source toolkit and evaluation

**链接**: https://arxiv.org/abs/2611.12709
**作者**: Valentin Burkin
**来源**: cs.CL cs.CY cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objectives: To measure whether a locally hosted large language model (LLM), stacked with deterministic and clinical named-entity recognition (NER) detectors, finds more protected health information (PHI) than open tools, and at what precision. Materials and Methods: DeidSharp, an open-source .NET toolkit, combines the findings of pluggable detectors (patterns, a clinical NER model, a local 26B mixture-of-experts LLM) and fails closed on any detector error. Configurations fixed on tuning halves were compared, under a prespecified protocol, with deid, Philter, the Stanford/Penn de-identifier, OpenAI Privacy Filter and GLiNER on reporting halves of PhysioNet's nursing notes (889 spans) and semi-synthetic MIMIC-IV-Note discharge summaries (29,023 spans), and on synthetic ASQ-PHI queries, with paired patient-level bootstrap intervals. Results: In the nursing notes, against Stanford/Penn, the recall-first stack found 98.9% of PHI (+2.8, 95% CI 1.4 to 4.4) at 9.3 points lower precision; the p

---

### [82] Agent4Crypto: A Dual-Reflective and Market-Feedback-Aligned LLM-Based Multi-Agent System for Cryptocurrency Trading

**链接**: https://arxiv.org/abs/2611.12269
**作者**: Guangyan Gan, Jiahao Li, Jiashun Wang, Lin William Cong
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cryptocurrency markets provide a natural testbed for autonomous AI agents because they are digital-native, high-frequency, and machine-speed environments, yet existing methods often struggle with non-stationary market regimes, opaque decisions, and fixed aggregation rules. In this paper, we propose Agent4Crypto, a dual-reflective and market-feedback-aligned multi-agent system. The framework coordinates specialized agents for data collection, analysis, risk assessment, reflection, and trading, synthesizing heterogeneous signals from prices, indicators, news, and charts in an interpretable decision pipeline. Our central design is a trader-centric decision mechanism: three style-specific trader agents, Aggressive, Neutral, and Conservative, generate candidate actions and natural-language rationales from the same market context, while their influence is learned rather than manually fixed. A PPO-based gating policy dynamically allocates trader weights through a dual-reflective feedback proc

---

### [83] Weight-Space Programming of Variational Quantum Circuits: Large Language Models Write Quantum Circuit Parameters Without an Optimizer

**链接**: https://arxiv.org/abs/2611.11537
**作者**: Debarshi Kundu, Swaroop Ghosh, Vasant G Honavar
**来源**: quant-ph cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Variational quantum algorithms (VQAs) optimize circuit angles through repeated quantum-device evaluations, often facing vanishing gradients and high optimization costs. We ask whether a large language model (LLM) can write these angles directly. Extending *weight-space programming* from classical networks to quantum circuits, we provide a frontier LLM (\gpt) with the problem, circuit, and gate conventions. Its angles are executed exactly as written, without returning losses, gradients, or accuracy feedback. Across 139 requests, we test handwritten-digit classification, VQE ground-state estimation for spin chains and H$_2$, and MaxCut QAOA, comparing against random weights, classical optimization, and optimization initialized with LLM weights on the same circuit. When parameters have interpretable structure, the LLM matches or approaches the optimizer: it achieves 95--100\% of the energy spectrum on every VQE problem, derives the exact H$_2$ ground state in closed form, finds optimal de

---

### [84] Rule Forest: Interpretable Ensembles of LLM-Generated Questions for Rare-Outcome Prediction

**链接**: https://arxiv.org/abs/2505.24622
**作者**: Ben Griffin, Aaron Ontoyin Yin, Diego Vidaurre, Ugur Koyluoglu, Joseph Ternasky, Fuat Alican 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [85] Recursive Semantic Divergence for LLM Agent Consistency

**链接**: https://arxiv.org/abs/2610.33012
**作者**: Harshavardhan Abichandani, Penny Chong, Atin Ghosh, Daniel Dahlmeier
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [86] Machine-Readable Operator Manuals over the ISO 11783 Network for Offline, Multilingual LLM Assistance

**链接**: https://arxiv.org/abs/2610.31863
**作者**: Timo Oksanen, Julius Gun
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] Same Beliefs, Different Policies: Learning Reusable Representations for Early Stopping in LLM Reasoning

**链接**: https://arxiv.org/abs/2610.30450
**作者**: Jingwei Ni, Dmitry Abulkhanov, Vladislav Smirnov, Markus Leippold, Elliott Ash, Timothy Baldwin 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] TurnFlow: Benchmarking User-State Reasoning in Multi-Turn LLM Agents via Scene-Guided User Simulation

**链接**: https://arxiv.org/abs/2611.10412
**作者**: Zhixun Chen, Ming Li, Anjie Liu, Xiaoyuan Zhang, Quanyu Dai, Huangxun Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed through conversational interfaces, yet strong single-turn performance does not imply reliability in multi-turn settings. Multi-turn assistance requires a model to maintain an evolving representation of user requirements and to reason over it before complying with later requests. Failures can therefore be subtle: models may fail to recognize a changed constraint or hidden conflict, or recognize it without enforcing it in the final response. Existing benchmarks primarily test fully specified prompts, long-context recall, or controlled domain environments, leaving open-domain requirement reconciliation undermeasured. We introduce TurnFlow, an interactive benchmark for evaluating whether models preserve, revise, and act on user requirements across turns. TurnFlow combines adaptive user simulation with verifiable judging, allowing conversations to unfold naturally while keeping hidden requirements and pass/fail criteria controlled. In o

---

### [89] Cooperative Coevolution for Resource-Constrained Agentic LLM Post-Training

**链接**: https://arxiv.org/abs/2608.02391
**作者**: Zhiyuan Wang, Shengcai Liu, Jiahao Wu, Ning Lu, Hui Ouyang, Shaofeng Zhang 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [90] Distinguishing Extraction Failures and Clinical Discordance with LLM Uncertainty on Radiology Reports

**链接**: https://arxiv.org/abs/2611.10502
**作者**: Jerjes Aguirre-Chavez, Shant Malkasian, Roshun Sankaran, Brendan Crabb, Albert Hsiao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can structure clinical datasets, but extraction error must be distinguished from discordance in the underlying data. From a real-world cohort of 1{,}045 patients undergoing coronary CT angiography (CCTA), we evaluated whether LLM uncertainty during vessel-level coronary artery disease (CAD) stenosis extraction could identify extraction failure and clinical discordance. References were expert CCTA annotations (253 patients) and subsequent invasive coronary angiography (ICA; 729 patients). We quantify extraction failure as disagreement between stenosis severity in LLM extracted versus expert annotations, and clinical discordance as disagreement in stenosis severity between CCTA and subsequent ICA. Stenosis Margin, selected from ten candidate measures, was used to quantify LLM uncertainty, and generalized estimating equation logistic regression and AUC evaluated its association and incremental discrimination for each failure mode. LLM uncertainty was strongly 

---

### [91] What Do Collusion Probes Read? Three Pitfalls in Evaluating Multi-Agent Collusion Monitors

**链接**: https://arxiv.org/abs/2611.10620
**作者**: Mainul Hasan Mohsin, Mohammad Shahidur Rahman
**来源**: cs.LG cs.AI cs.CL cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation probes look like near-perfect monitors for secret collusion among large language model (LLM) agents. We show that they mostly detect that an agent was told to collude, not that it decided to. Our benchmark (2,500 committee and 1,476 code-review episodes) adds agents who receive the collusion instruction and refuse it, separating instruction from decision. Published detectors barely tell colluders from these refusers, and our best probe separates them mostly by reading the instruction: without it, agent AUROC falls from 1.00 to 0.61. Two further pitfalls inflate reported results: scored after the vote, a rule that only reads the votes reaches AUROC 0.990 but finds nothing before it; and in 57% of attempts no colluder argues for the target in public. The decision is still there: a probe trained on agents' own choices reads it (AUROC 0.73 without the instruction), and probes find colluders whose goal was fine-tuned into the weights (AUROC 0.995; pre-registered). We turn the con

---

### [92] LLM Agents Already Know When to Call Tools -- Even Without Reasoning

**链接**: https://arxiv.org/abs/2605.09252
**作者**: Chung-En Sun, Linbo Liu, Ge Yan, Zimo Wang, Tsui-Wei Weng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [93] Causal Discovery Bench: Can LLMs Autonomously Conduct Effective Experiments?

**链接**: https://arxiv.org/abs/2611.09934
**作者**: Zhuoyang Liu, Ning Peng, Ming Shen, Zijun Gao
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents get actively adopted for autonomous research, they must not only reason over existing evidence, but also design informative experiments, allocate resources, analyze sequential observations, and decide when to stop and make conclusions. Yet these capabilities remain poorly measured. We introduce Causal-Discovery-Bench (https://github.com/mshen1019/causal-discovery-bench), a verifiable sandbox with configurable structural equation models and resource constraints to evaluate sequential experimental design and causal discovery without domain-semantic cues. Across 3,802 episodes with 13 models from 5 vendors, we analyze agent behavior along 40 metrics in seven families. Agents' performance exhibits a four-level difficulty hierarchy spanning single-experiment design, sequential exploration of causal relationships, resource-aware experimentation balancing cost and statistical power, and autonomous resolution of conflicting evidence. We identify a substanti

---

### [94] Learn-To-Learn on Arbitrary Textual Conditioning: A Hypernetwork-Driven Meta-Gated LLM

**链接**: https://arxiv.org/abs/2605.01973
**作者**: Luo Ji, Qi Qin, Ningyuan Xi, Teng Chen, Qingqing Gu, Hongyan Li
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] LLM-based Multi-Criteria Deep Reinforcement Learning for Dynamic Efficient 5G UPF Selection

**链接**: https://arxiv.org/abs/2611.11372
**作者**: Abdelrahman Soliman, Ahmed Refaey Hussein, Lei Lei
**来源**: cs.LG cs.AI cs.CL cs.NI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> User plane function (UPF) selection in 5G networks is an active area of research, with various limited approaches proposed to enhance network efficiency and manage resources effectively. In this paper, we address this gap in the related literature by proposing a Deep Reinforcement Learning (DRL) UPF selection method that utilizes a dynamic, multi-objective reward function and validating it on a real-world 5G emulation platform. The proposed method is based on the large language models' (LLMs) translation of network operator intents and the network data analytics function (NWDAF) abnormality alerts. The experimental results validated in the real-world experimental setup demonstrate that our dynamic DRL solution achieves an effective balance between latency, power consumption, and traffic distribution, outperforming the heuristic baselines and fixed DRL by 16.89%. These findings highlight the real-world applicability of our approach for dynamic, intent-driven UPF selection.

---

### [96] From Residuals to Reasons: LLM-Guided Mechanism Inference from Tabular Data

**链接**: https://arxiv.org/abs/2605.22897
**作者**: Mohammad R. Rezaei, Rahul G. Krishnan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] Alignment Dynamics in LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2605.18309
**作者**: Yuhan Huang, Huanran Chen, Yinpeng Dong
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] ClinFusion: A Vision-Centric Multimodal LLM System for Holistic Medical Understanding

**链接**: https://arxiv.org/abs/2607.24743
**作者**: Hangjie Yuan, Yichen Qian, Zhiwei Tang, Xianzhe Xu, Sicheng Yang, Lirong Wu 等 (10 人)
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [99] Can LLM Agents Organize Their Own Memory?

**链接**: https://arxiv.org/abs/2611.11929
**作者**: Zichuan Fu, Junjia Qi, Wenlin Zhang, Yimin Deng, Shirong Wang, Jinyang Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In most LLM agents, weights are fixed after deployment, so new information must be retained in external memory. Existing approaches often rely on predefined records and fixed organizational rules, which cannot readily accommodate evolving tasks and interactions. This raises the question: can LLM agents organize their own memory using ordinary documents? We introduce self-organized memory (SoMem), a framework that stores memory in linked documents. The agent decides what to summarize, how to group related information, and when to revise existing topics, and every summary it produces stays linked to the original interactions as evidence. The runtime validates updates and automatically derives temporal, relational, and recent-memory views from the organized content. At query time, the agent chooses what to search and read, following document links and inspecting original evidence as needed. On LoCoMo, BEAM-100K, and LongMemEval-S, SoMem outperforms the strongest baseline by 2.66, 3.10, an

---

### [100] LLM Watermarking as Big Data Provenance: A Deployment-Oriented Systematization

**链接**: https://arxiv.org/abs/2607.10103
**作者**: Huy Phan, Kieu Dang, Ojaswi Dulal, Aiham AL Shukairi, Abby Shine, Chase Garner 等 (7 人)
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [101] SkillOps: Managing LLM Agent Skill Libraries as Self-Maintaining Software Ecosystems

**链接**: https://arxiv.org/abs/2605.13716
**作者**: Xinyuan Song, Hongji Pu, Liang Zhao
**来源**: cs.SE cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] Detent: Batch-Invariant LLM Serving and RL Rollouts at Near-Stock Speed

**链接**: https://arxiv.org/abs/2611.10611
**作者**: Peixu Xin (Independent Researcher, Boston University), Runchuan Feng (Independent Researcher, Boston University), Jiazhen Guo (Google), Kan Wu (RadixArk) 等 (7 人)
**来源**: cs.LG cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reproducible evaluation, verifiable inference and on-policy reinforcement learning (RL) need an LLM engine to give a request the same output bits whichever requests share its batch. Batch-invariant kernels exist, but engines still select each kernel and its parameters from the batch. Two kernels that compute the same sum can round it differently. The engines' deterministic modes remove the choice by keeping one conservative kernel per operator and pay for it in latency. Many fast kernels are batch-invariant by themselves, so it is enough to fix the few batch-dependent values that kernel selection reads. Detent expresses kernel selection as a program that the engine executes. It finds the fewest values in this program that must be fixed and tunes them for the workload before deployment. On multi-GPU deployments of Llama-3.1-70B and Qwen3-30B-A3B in vLLM and SGLang, Detent is batch-invariant. Tuned per load, it serves at 1.04-1.17x the latency per output token of Stock (each engine with 

---

### [103] Building and Auditing Chemical Datasets with LLMs: A General LLM-as-a-Judge Framework Applied to Homogeneous Catalytic PET Depolymerisation

**链接**: https://arxiv.org/abs/2611.11030
**作者**: Muhammad bin Javaid, Karim K. Ben Hicham, Enkhnyam Battulga, Alexander Mitsos, Martin Grohe
**来源**: cs.CL cs.AI cs.DL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can rapidly extract structured multivariate experimental data from the chemistry literature, yet verifying thousands of generated records without ground truth remains difficult. We present a general, citation-grounded extraction and verification methodology centered on an independent "LLM-as-a-judge", applied to the literature on homogeneous catalytic poly(ethylene terephthalate) (PET) depolymerisation. In this pipeline, an extractor LLM generates schema-enforced records from research papers with citations to document chunks tagged with universally unique identifiers (UUIDs); an independent LLM judge then reads the full paper alongside each record, flags unsupported fields, and proposes cited corrections. Prompt ablations show that requiring chunk-level citations not only provides provenance down to specific paragraphs and tables but also improves extraction accuracy. Before deploying the judge at scale, we benchmarked it against manual evaluation on extractions f

---

### [104] AutoEMatic: Runtime-Adaptive Mixed-Precision LLM Inference via Automatic Exponent-Mantissa Refinement

**链接**: https://arxiv.org/abs/2611.10165
**作者**: Akshat Ramachandran, Reena Elangovan, Rangharajan Venkatesan, Charbel Sakr, Tijmen Blankevoort, Brucek Khailany 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing LLM post-training quantization techniques determine precision before inference begins, yet the precision a model requires varies dynamically across prompts, layers, and inference phases. We present AutoEMatic, a full-stack co-design that adapts the precision of weights, activations, and the KV cache at runtime. A lightweight policy selects each layer's precision at every prefill and decode step from two runtime signals: the entropy of the next-token distribution and the magnitude of each layer's update to its hidden states. This runtime adaptation is made practical by AutoFP, a multi-scale floating-point format that derives 2-, 4-, and 6-bit precisions from a single NVFP4 base format. We realize AutoEMatic on two targets: GPU kernels that execute AutoFP on NVFP4 Tensor Cores, and an accelerator whose vector MAC datapath executes all AutoFP formats natively. Across reasoning and agentic benchmarks, AutoEMatic improves accuracy by up to 21.7% over NVFP4 and matches group-scaled 

---

### [105] Hint-Guided Diversified Policy Optimization for LLM Reasoning

**链接**: https://arxiv.org/abs/2606.03021
**作者**: Zhiyu Cao, Kaixin Wu, Mingjie Zhong, Peifeng Li, Can Ye, Qiaoming Zhu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] Sampling Is Not Curiosity: Why LLM Agents Should Investigate

**链接**: https://arxiv.org/abs/2611.10501
**作者**: Alfonso Amayuelas, Piotr Pi\k{e}kos, Xin Eric Wang, William Yang Wang, J\"urgen Schmidhuber, Alex Pentland
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly used for open-ended tasks, very common in research scenarios where they are required to explore, investigate, or act curiously. At inference time, an LLM is a fixed map from context to next-token distribution, the pretrained weights determine the function, and only its conditioning changes as context accumulates. Mechanisms like temperature, best-of-N, tree search, or RAG vary how the distribution is sampled or what it is conditioned on, but do not update the agent's model of the environment. We argue that current LLM agents do not explore curiously; they explore stochastically. From how curiosity is understood in the RL literature, it requires a predictive structure over how the environment responds to the agent's actions, which improves online from current interaction, drives action selection through its predicted improvement, and persists beyond the context window. Additionally, in its open-ended form, the agent should intrinsically originate what to inve

---

### [107] KR A1: Design and Preliminary Evaluation of a Humanoid-Robot Interaction Prototype Integrating Personalized Voice Synthesis, Contextual Dialogue, and Emotion-Aware Response Generation

**链接**: https://arxiv.org/abs/2611.09900
**作者**: Mahek Aanthu, Om Aanthu, Aaryan AK Aanthu
**来源**: cs.HC cs.CL cs.RO cs.SD eess.AS
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents the design and preliminary evaluation of KR A1, a humanoid-robot interaction prototype that integrates personalized voice synthesis, contextual dialogue processing, and emotion-aware response generation for potential mental-healthcare applications. The system architecture combines a locally hosted large language model (Qwen2.5-3B-Instruct, served via Ollama) for natural-language understanding and response generation, OpenVoice v2 for zero-shot speaker-adaptive speech synthesis, and a two-tier emotion-processing pipeline comprising a keyword heuristic and LLM-based inference. Face recognition (InsightFace) and vector memory retrieval (FAISS with sentence-transformer embeddings) enable user-personalized interaction. The experimental evaluation reported here is limited to the voice-cloning component: cloned voices were evaluated against reference recordings using eight acoustic similarity measures - mel-frequency cepstral coefficients, pitch, spectral centroid, spectra

---

### [108] The Range Shrinks, the Threat Remains: Re-evaluating LLM Package Hallucinations on the 2026 Frontier-Model Cohort

**链接**: https://arxiv.org/abs/2605.17062
**作者**: Aleksandr Churilov (Independent Researcher)
**来源**: cs.CR cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [109] Large Language Models as a Universal Searcher for Open-World Automated Machine Learning

**链接**: https://arxiv.org/abs/2611.12791
**作者**: Yuxuan Hu, Jihao Liu, Weikang Shi, Xijie Huang, Linda Wei, Mingjie Zhan 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing effective machine learning models requires complex manual tuning, while current Automated Machine Learning (AutoML) frameworks remain domain-specific and isolate model architecture, training hyperparameter, and data ratio optimization. Here, we bridge this gap by proposing a universal, large language model (LLM)-based AutoML framework that jointly optimizes these configurations for the first time without the need for task-specific fine-tuning. We propose NCode, a unified numerical encoding scheme that translates diverse AutoML design choices into universal discrete sequences and effectively reframes the optimization process as a unified ranking task. Trained solely on optimization trajectories derived from a limited, single-domain vision task, the proposed LLM-based searcher demonstrates impressive cross-task, cross-modality and joint search-space optimization generalizability, achieving state-of-the-art performance across image classification, image segmentation, speaker ve

---

### [110] Designing LLM-based Multi-Agent Systems for Software Engineering Tasks: Quality Attributes, Design Patterns and Rationale

**链接**: https://arxiv.org/abs/2511.08475
**作者**: Yangxiao Cai, Ruiyin Li, Peng Liang, Mojtaba Shahin, Zengyang Li, Aldeida Aleti 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [111] Scale-Dependent Collective Adaptation in Self-Amending LLM Societies: A Cross-Family Study of Emergent Governance

**链接**: https://arxiv.org/abs/2605.17510
**作者**: Kazuya Horibe, Masaomi Hatakeyama, Gen Masumoto, Takashi Hashimoto, Peter Romero
**来源**: nlin.AO cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] SecureGARD: Dynamic Ontology-Guided Governance for Secure Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2611.06682
**作者**: Guoqin Xiong, Shengtao Wen, Xiang Chen, Xinyi Zeng, Zhaoxin Fan, Wei Ye 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] COMPASS: Composable Policy-Amortized Structured Search for LLM-Based Optimization Modeling

**链接**: https://arxiv.org/abs/2611.12060
**作者**: Nguyen Le Minh Hoang, Van Duc Cuong, Bui Trong Duc, Huynh Thi Thanh Binh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models offer a promising technique for translating natural-language optimization problems into solver code, but their reliability remains constrained by the quality of template retrieval. While recent structured methods improve over flat prompting through hierarchical taxonomy search, their traversal rules remain fixed or LLM-driven at inference time, leaving retrieval unable to improve from past successes and failures. This motivates treating template retrieval as a policy that can be learned from modeling experience, rather than as a static inference-time rule. We propose COMPASS, a policy-amortized framework for retrieving optimization templates in LLM-based solver modeling, which represents the template library as a directed acyclic graph and formulates retrieval as a sequential decision process over template nodes. A deep Q-network learns a reusable traversal policy from template-level judgments and execution feedback, reducing reliance on fixed heuristic traversal 

---

### [114] OraclePhys: A Systematic Framework for LLM Fine-Tuning on Structural Mechanics

**链接**: https://arxiv.org/abs/2608.17162
**作者**: Mingyu Li, Guorui Song, Jing Lin, Haoqian Wang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] DAPS: Dependency-Aware Premise Selection for LLM Theorem Proving

**链接**: https://arxiv.org/abs/2610.41536
**作者**: Zixuan Chen, Wenyuan Jiang, Junling Wang, Mrinmaya Sachan, Yinya Huang
**来源**: cs.LO cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] LiveAsset: Learning Intent Assets from Corrective Interactions for Agent Runtime Control

**链接**: https://arxiv.org/abs/2611.11560
**作者**: Guanming Liu, Weihang Wang, Peng Zhang, Meng Wu, Kainan Tu, Jiahao Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents acting across web applications and online services often need multi-turn corrections to align their work with users' underspecified goals and preferences. In practice, users may identify problems in the current outcome without specifying the desired result, so learning user intentions requires interpreting each correction against the agent's preceding and revised outcomes. These expectations are often connected to a particular context, making it hard to know when they apply and how to ensure the agent later acts as the user expects. To this end, we propose LiveAsset, an intent harness that learns reusable intent assets from corrective interactions and uses them for runtime control of agent execution. LiveAsset jointly interprets each correction with the agent's original and revised results to infer user intent, incrementally updating the assets while preserving earlier requirements that remain applicable. The learned requirements guide agent execution 

---

### [117] PACE: Keeping the Right Tokens in the KV Cache Is Not Enough for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2611.10240
**作者**: Suman Chatterjee
**来源**: cs.LG cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents accumulate sessions of up to millions of tokens, far more key-value (KV) cache than one GPU holds, so serving systems keep a small budget of tokens and evict the rest. Eviction methods differ in which tokens they keep but share one goal: that the tokens a later step needs are still cached. We show this is not enough. In 100K-token coding sessions on Qwen3-8B with a 2,048-token budget, a planner-guided policy that keeps over 99% of the needed tokens resident still fails late steps increasingly often: its accuracy falls from 93% to 64% as the gap between a definition and its use grows from 2K to 90K tokens, at residency 0.996. The needed tokens are resident but unretrievable: what grows is their rotary-position distance to the query. We present PACE (Planner-Aware Context Engine), a KV-cache engine that couples plan-aware retention, in which the agent's planner tells the cache which context future steps will read, with bounded positions, which renumber kept tokens

---

### [118] AgentCompile: An LLM-Guided Compiler for Direct CUDA Inference

**链接**: https://arxiv.org/abs/2606.07665
**作者**: Xuanzhe Li, Ziyan Weng, Zhiyu Zhu, Junhui Hou
**来源**: cs.PL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Demystifying Numerical Instability in LLM Inference: Achieving Reproducible Inference for Mission-Critical Tasks with HEAL

**链接**: https://arxiv.org/abs/2606.21023
**作者**: Zhenting Zhu, Lucas Thai, Shan Yu, Yicheng Liu, Yifan Qiao, Chenxi Wang 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] PRISM: Causal Counterfactual Minimization of Agent Tool Privileges via Information Bottleneck Role Induction

**链接**: https://arxiv.org/abs/2611.11539
**作者**: Yang Luo, Qingni Shen, Tairui Wang, Jiajun Li, Zhonghai Wu
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper shifts the object of role engineering from human users to large language model (LLM) agents, and proposes PRISM to address the over-authorization that arises when an agent obtains full tool privileges through the Model Context Protocol (MCP). PRISM formulates whether a tool is necessary for a task as an intervenable causal proposition, and applies structured interventions in a sandbox to learn a counterfactual necessity model. It then compresses trajectories into discrete latent variables through an information bottleneck, and determines the number of roles from the knee of the rate-distortion curve. Finally, it formalizes pruning as a bilevel Stackelberg game, in which a generative flow network samples diverse near-optimal solutions. On three public benchmarks, AgentDojo, $\tau$-bench and ToolEmu, PRISM compresses the number of authorized tools per role by 78.3%, attains a task success rate of 78.2%, reaches a counterfactual necessity accuracy of 88.7%, and lowers the blast

---

### [121] Tevatron Meets Megatron: Expert-Parallel LLM Reranker Training on an Academic Budget

**链接**: https://arxiv.org/abs/2608.00916
**作者**: Zhichao Xu and Xueguang Ma and Shengyao Zhuang and Luyu Gao and Wenqian Ye and Yu Wang and Jamie Callan and Jimmy Lin
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Mirage: Provable Defense Against LLM KV Cache Timing Side Channels with Topology-Aware Isolation

**链接**: https://arxiv.org/abs/2611.10756
**作者**: Xiaobei Yan, Tianwei Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly deployed as shared multi-tenant services, relying on advanced optimizations like KV cache and prefix sharing to improve throughput and reduce latency. However, these optimizations introduce a critical vulnerability: attackers can exploit time-to-first-token (TTFT) variations between KV cache hits and misses to infer sensitive prompt tokens via prefix-matching side-channel attacks. Existing defenses indiscriminately restrict cross-tenant cache sharing, which incurs prohibitive performance overhead and negates the fundamental efficiency benefits of the KV cache. We propose Mirage, a topology-aware emission obfuscation framework that provably bounds timing leakage without sacrificing the performance gains of cache sharing. Instead of stalling the GPU or forcing redundant recomputations, Mirage delays token emission at the gateway so the attacker observes a natural cache miss distribution, while the GPU seamlessly continues serving other reques

---

### [123] AFVE-Bench: Measuring Abandoned-Frame Verbalization Errors in Multi-Turn LLM Revision

**链接**: https://arxiv.org/abs/2611.10541
**作者**: Jiaming Chu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn revision often asks a model to replace an earlier organizing frame while preserving still-valid facts and artifact requirements. Existing instruction-following evaluations mainly assess the latest target and may therefore score an artifact as successful even when it adopts the new frame but exposes the superseded one. We call this failure an abandoned-frame verbalization error (AFVE). AFVE-Bench evaluates silent frame replacement in English and Chinese using 192 matched four-turn dialogues across eight writing domains. Each seed has zero, one, or two pre-target user requests to generate under the source frame. AFVE eligibility depends on the user-request history and applies to the one- and two-request conditions; the zero-request condition serves as a frame-bearing baseline. Eleven model configurations yielded 4,224 expected post-target response units. Two annotators independently scored 4,204 scorable responses for target adoption, source-frame verbalization, and direct usa

---

### [124] BridgeKV: Large-Model Prefill and Small-Model Decoding for LLM Inference via KV Cache Translation

**链接**: https://arxiv.org/abs/2611.11761
**作者**: Payman Behnam, Debopam Sanyal, Pranav Ponnusamy, Kusum Meda Ravi, Pranav Sastry, Mani Chandana Bandaru 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM inference has two phases with different bottlenecks: LLM prefill runs once per request and is compute-intensive. Decoding repeats for every output token and is limited by memory bandwidth. To address the challenges associated with this issue, different solutions have been proposed. All of these solutions use the same model for both prefill and decode phases. We propose BridgeKV, which uses a larger model for prefill and a smaller model of the same family for decoding. A lightweight KV-stitching module translates the larger model's prompt cache into the smaller model's cache layout. It handles differences in cache shape and representation through learned local layer mixing and separate nonlinear maps for keys and values. With both models frozen, we train the module to align their caches and make the smaller model follow the larger model's next-token predictions. A second training stage adds low-rank adapters when further task adaptation is needed. Across six model pairs and five dat

---

### [125] Enhancing Assessment of Self-Consistency in LLM Explanations using Perturbation Strength

**链接**: https://arxiv.org/abs/2609.30849
**作者**: Phuong Q. Le, Kemal Kurniawan, Jey Han Lau
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] From LLM Hallucinations to Inspiration in Creative Work

**链接**: https://arxiv.org/abs/2611.12337
**作者**: Xinrui Lin, Heyan Huang, Shuning Zhang, Qi Wang, Youchao Zhou, John Vines
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can introduce unexpected ideas through hallucinations, yet little is known about when creative practitioners find these errors inspiring or how these judgments shape interactions. We conducted a retrospective qualitative study with 20 experienced practitioners in research, design, and social media content creation, thematically analyzing 41 hallucination cases and 20 semi-structured interviews. Our framework links inspiration judgments of hallucinations based on goal relevance, task stage, content adaptability, and type-specific factors to behaviors across not-inspired, inspired-by, and inspired-to states. We characterize downstream interaction consequences, showing how hallucination-inspired experiences vary across creative stages and reshape role-differentiated trust, and propose these consequences as a dimension of hallucination evaluation. Finally, we derive design recommendations for stage-sensitive control of divergence and adherence, user-defined con

---

### [127] Hearsay or Fact? How Framing and Elicitation Shape LLM Probability Updates

**链接**: https://arxiv.org/abs/2610.27745
**作者**: An-Sheng Jhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] SlotGuard: Stop Oversharing Private Local Context in LLM Agent Transcripts

**链接**: https://arxiv.org/abs/2607.17147
**作者**: Haocheng Xia and Yongjoo Park
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] AMTFV: Agentic Mathematical Tool-Flow Verification for LLM Self-Correction

**链接**: https://arxiv.org/abs/2607.29549
**作者**: Rui Zou, Yutao Zhu, Mengqi Wei, Ji-Rong Wen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] Sentinel: Decoding Context Utilization via Attention Probing for Efficient LLM Context Compression

**链接**: https://arxiv.org/abs/2505.23277
**作者**: Yong Zhang, Heng Li, Yanwen Huang, Ning Cheng, Yang Guo, Yun Zhu 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] Exploring the Capabilities of Large Language Model Encoders for Image-Text Retrieval in Chest X-rays

**链接**: https://arxiv.org/abs/2509.15234
**作者**: Hanbin Ko, Gihun Cho, Inhyeok Baek, Donguk Kim, Joonbeom Koo, Changi Kim 等 (8 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] Knowing When to Ask: Segment-Level Credit Assignment for LLM Tool Use

**链接**: https://arxiv.org/abs/2605.27788
**作者**: Abhijit Kumar, Zoey Wu, Mohit Suley
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] Polarity Blindness in LLM Safety: A Systematic Study of Negation, Antonym Substitution, and Adversarial Framing

**链接**: https://arxiv.org/abs/2610.27908
**作者**: Diego Miguel Lozano, Erik Derner, Juan Antonio P\'erez-Ortiz, Nuria Oliver
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Coordinated Mixed-Precision KV Cache Quantization for Efficient LLM-based Multi-agent Systems

**链接**: https://arxiv.org/abs/2611.10096
**作者**: Weizhong Huang, Jinchao Zhang, Xiawu Zheng
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems solve complex tasks through collaboration, but their growing, simultaneously resident key-value (KV) caches create a memory bottleneck. Applying single-model quantization policies independently ignores differences in agents' precision needs, potentially degrading collective reasoning. We introduce Coordinated Mixed-Precision KV Cache Quantization (CoMixKV), which combines online sensitivity estimation with joint agent-layer bit-width allocation under a shared memory budget. To our knowledge, CoMixKV is the first mixed-precision KV-cache quantization framework to jointly allocate precision across simultaneously resident agent caches under such a budget. The estimator derives sensitivity from a local attention-error bound using recent queries, keys, and values, without calibration data, trial quantization, or additional model passes. A shared controller combines these scores with remaining quantizable capacity and byte-level storage costs to minimize total e

---

### [135] RADE: Risk-Adjusted Deployment Efficiency, A Framework for Routing, Memory, and Escalation in Safe LLM Systems

**链接**: https://arxiv.org/abs/2611.11659
**作者**: Chaymaa Abbas, Kareem Hassani, Mariette Awad
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A deployed language model does not merely answer questions. It spends computation, consumes time, consults evidence, exposes memory, invites or avoids human review, and sometimes makes mistakes whose consequences are radically unequal. Yet LLM systems are still commonly compared as if the relevant object were a single model and the relevant outcome were a single benchmark score. This paper argues that the unit of analysis should instead be the deployment policy: the mechanism that decides when to retrieve, when to remember, when to call a larger model, when to verify, and when not to answer at all. We introduce risk-adjusted deployment efficiency (RADE), a system-level objective that scores the utility a deployment delivers net of inference, retry, oversight, and priced expected failure cost, while treating harms that cannot be priced as hard budgets alongside constraints on latency, privacy, and resources. The framework brings selective routing, retrieval and governed memory, efficien

---

### [136] Training LLM Agents to Automate LLM Post-Training with RSI-Dojo

**链接**: https://arxiv.org/abs/2611.03698
**作者**: Shuzheng Gao, Zhaojian Yu, Penghao Yin, Yuling Shi, Kai Cai, Shilin He 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [137] SurfScaff3D: Bridging Geometric and Semantic Representations for LLM-based 3D Object Generation

**链接**: https://arxiv.org/abs/2611.11678
**作者**: Anay Loya, Rishi Gupta, Arnav Samal, Anirban Chakraborty
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Creating high-quality 3D content has traditionally required specialist expertise and experience with complex tools. The growing ecosystem of AI-assisted creativity demands accessible and intuitive 3D generation systems. Recent advances in Large Language Models (LLMs) offer promising directions, yet extending their generative capabilities to 3D remains fundamentally challenging because existing 3D representations are not naturally compatible with language-based reasoning. Current approaches either depend on expensive fine-tuning or impose restrictive structural priors that sacrifice expressiveness and exclude organic shapes. We argue that the mismatch between LLM-native reasoning and conventional 3D parameterizations is a core bottleneck of LLM-driven 3D generation. To address this, we introduce the Hierarchical Patch Scaffold (HPS), a representation designed around semantically meaningful, interpretable part-level abstractions that are naturally understood by both humans and LLMs, enab

---

### [138] Beyond Hard Labels: LLM Probabilities Improve Human-Assisted Regression

**链接**: https://arxiv.org/abs/2611.11111
**作者**: Xinyue Wang (Department of Statistics, The Pennsylvania State University), Qunhua Li (Department of Statistics, The Pennsylvania State University)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for text annotation, but their outputs are often reduced to a single categorical label before downstream analysis. This hardening step discards the model's relative support across categories, which may contain useful information when category boundaries are ambiguous. We study whether retaining the full probability vector improves downstream regression when LLM annotations are combined with a limited amount of human annotation. Using matched soft and hard representations from three LLMs across three social-science text datasets, we compare direct regression and human-assisted correction. Soft inputs are not uniformly better when used directly as outcomes, but after human correction, using the probability vector consistently improves regression efficiency across models and datasets. Analyses of repeated human judgments and controlled simulations further show that these gains arise when probability variation beyond the hard category carr

---

### [139] Detecting Shadow AI: Unsanctioned LLM Agents on Enterprise Endpoints: A Taxonomy, an Open Detector and a Controlled Evaluation

**链接**: https://arxiv.org/abs/2611.12377
**作者**: Jeremy Canale, Fabien Soulis
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Shadow IT, the use of technology that the IT organisation has not approved, is a long-standing governance problem. We argue that autonomous AI agents can make it grow much faster: agents make building tools nearly free, act with their user's privileges, and leave behind scripts, automations and MCP servers that are themselves unsanctioned. A simple compounding model shows that, under its assumptions, shadow IT grows exponentially once agentic artifacts reproduce faster than the organisation retires them; retiring them starts with detecting them. We then ask whether unsanctioned agents can be detected on Windows endpoints. We propose a taxonomy of nine classes of agents and six layers of endpoint footprint, and argue that rules based only on the structure of processes and connections cannot separate an agent from its behavioural twin, the same program talking to a non-AI service. We present Agent Detector, an open-source Windows detector that anchors behaviour to the identity of the rem

---

### [140] Advancing Model Refinement: Muon-Optimized Distillation and Quantization for LLM Deployment

**链接**: https://arxiv.org/abs/2601.09865
**作者**: Jacob Sander and Brian Jalaian and Venkat R. Dasari
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [141] Approximate Recall, Approximate Forecasts: Recall as a Diagnostic for LLM Forecasting Errors

**链接**: https://arxiv.org/abs/2611.10891
**作者**: Prashanth Bhaskara, Shubhaankar Gupta, Seojoon Yeon
**来源**: cs.AI cs.CE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) exhibit approximate recall: they retain coarse associations about past events while losing fidelity on specific details. Past research on LLMs has quantified different models' forecasting ability in real-world events using prediction markets, but has not studied how losing said fidelity impacts their forecasting abilities. For example: while an LLM correctly recalls that the answer to: ''Did Anna Sawai win the Best Drama Actress in the 76th Emmy Awards?'' is ''Yes,'' it incorrectly states the event date as September 22 rather than September 15. In this paper, we introduce a novel metric called the Recall Fidelity Score to study how imprecision in internalized knowledge propagates to forecasting capability on future events. On resolved historical markets, we find that higher local recall fidelity around semantically similar past events predicts lower forecasting error on resolved markets, and the same signal predicts smaller distance from open markets prices

---

### [142] Semantic Synthesis over Brute-Force Search: LLM-Guided Transformation Design for Efficient Learning

**链接**: https://arxiv.org/abs/2611.10940
**作者**: Usha Shrestha, Radu Timofte, Dmitry Ignatov
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data transformation pipelines shape the training distribution in computer vision, but designing them is a computationally expensive problem. We investigate whether large language models can enable efficient discovery by synthesizing executable transformation programs outside predefined augmentation spaces. We compare nine strategies under a unified training protocol, including standard augmentation policies, brute-force search, direct code generation with two LLMs, and performance-guided generation using LLMs fine-tuned on accuracy-ordered transformation pairs. When the best candidates are retrained for 20 epochs, LLM-generated transformation programs lead on every dataset, reaching 0.8877 accuracy on CIFAR-10, 0.5825 on CIFAR-100, and 0.9588 on SVHN, surpassing brute-force search over 6,000 candidates. The best transform on CIFAR-10 and SVHN comes from a fine-tuned generator using 270 candidates, while the best on CIFAR-100 comes from an off-the-shelf generator using only 10. This nee

---

### [143] Keeping LLM Agents on Procedure: Executable Finite-State Control for Long-Horizon Instruction Fidelity

**链接**: https://arxiv.org/abs/2611.10884
**作者**: Yutao Sun, Haokun Li, Mingshuai Chen, Guanyan Li, Zhongyi Wang, Shengchao Qin and Jianwei Yin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Much of the automation handed to language-model agents is procedural: each step needs little intelligence, but a long unattended run must follow a skill or SOP stated once at the start. We show that agents drift from such procedures over long runs, and that restating the instructions or resuming a stopped agent only moves the drift to another shortcut. We study an executable finite-state machine (FSM) that keeps the workflow state outside the model's context and enforces it at three points: tool calls, state transitions and the end of the agent's turn. In a pre-registered experiment on 200-account SOP-Bench batches, Claude Haiku 4.5 with the FSM decided on average 139 accounts correctly and by the procedure, against 48 for the strongest baseline (95% CI of the difference [46, 130]), and kept this rate to the end; across three models, the gain tracked how much the plain agent drifted. Because the runtime, not the model, supplies this long-horizon reliability, the FSM can let small model

---

### [144] Measuring Collapse and Correction in Homogeneous-Panel LLM Debate

**链接**: https://arxiv.org/abs/2609.35279
**作者**: Xin Li, Mengbing Liu, Chau Yuen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [145] Instrumental Choices: Measuring the Propensity of LLM Agents to Pursue Instrumental Behaviors

**链接**: https://arxiv.org/abs/2605.06490
**作者**: Jonas Wiedermann-M\"oller, Leonard Dung and Maksym Andriushchenko
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [146] A Layer-wise Study of How Style Rewriting Breaks the Calibration of Zero-Shot LLM Fake-News Detectors

**链接**: https://arxiv.org/abs/2611.11239
**作者**: Prabhjot Singh, Praney Goyal, Raksha Sharma
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly asked to judge whether a news article is true, and their stated confidence is often taken at face value. We test what happens to that confidence when an article's writing style, but not its facts, is manipulated, as in recent \emph{style attacks} on fake-news detectors. Tracing how the prediction and its confidence form layer by layer inside the network, we study three model families (LLaMA-3-8B, Qwen2.5-7B, Mistral-7B) on three fake-news benchmarks, and find the same three patterns in every model--dataset pairing. First, on the original articles the models are competent and largely honest judges: they settle on an answer, briefly become overconfident, and then correct their confidence in the final layers. Second, style-rewritten articles break this self-correction: the models become far less accurate, under the strongest attack, worse than random guessing, yet remain just as confident, so they are \emph{confidently wrong} precisely when a 

---

### [147] WarBias: A Bilingual LLM Benchmark of Stereotypes About Internally Displaced People and Veterans

**链接**: https://arxiv.org/abs/2611.11284
**作者**: Viktoriia Makovska, Tetiana Zakharchenko, Oleksandra Ostafiichuk
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper contains examples of stereotypes about veterans and displaced people that may be offensive or distressing. Social bias benchmarks for language models commonly examine categories such as gender, race, and religion, often drawn from lists of legally protected characteristics. Veterans and internally displaced people (IDPs) fall outside these lists, and stereotypes about them, which can undermine access to employment, housing, and social participation, remain largely absent from language model evaluation. We introduce WarBias, a Ukrainian--English benchmark of stereotypes about these two groups. Built from a taxonomy of 120 stereotype claims grounded in research and monitoring reports, WarBias contains 1,007 stereotype--counter-stereotype--unrelated sentence triplets and 240 multiple-choice questions per language. A Ukrainian language model selected in a blinded human pilot generated the Ukrainian triplets. At least two independent annotators reviewed each triplet in the annota

---

### [148] Batch-of-Thought: Cross-Instance Learning for Enhanced LLM Reasoning

**链接**: https://arxiv.org/abs/2601.02950
**作者**: Xuan Yang, Furong Jia, Roy Xie, Xi Xiong, Hengwei Bian, Jian Li 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [149] SWEET: Mitigating Spurious Feature Reliance in LLM Reasoning via Weight Editing

**链接**: https://arxiv.org/abs/2611.10974
**作者**: Zhizhang Fu, Lucas Zhao, Michalis Korakakis, Mengru Ding, Lukasz Szpruch, Yue Zhang
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning in large language models can be disrupted by simple input perturbations (e.g. adding irrelevant distractors), suggesting reliance on spurious correlations. Identifying and suppressing the spurious features involved in long chain-of-thought reasoning remains challenging. We introduce Spurious-feature WEight EdiTing (SWEET), a training-free method that combines counterfactual interventions with mechanistic interpretability to identify and suppress spurious-features. SWEET extracts token- and sequence-level behavioral directions from activation contrasts between original problems and their counterfactual variants - capturing local and global patterns of spurious reasoning. It then localizes the responsible MLP neurons and attention heads and suppresses their contributions along these directions through weight edits. Using only 20 original-counterfactual pairs for direction extraction, SWEET improves accuracy by an average of 11.8 percentage points on perturbed inputs and 2 point

---

### [150] Coverage-Verified Sparse Attention: Closed-Loop Quality Control for Long-Context LLM Decoding

**链接**: https://arxiv.org/abs/2611.10634
**作者**: Yan-Cheng Li, Chun-Yi Lee
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse attention accelerates long-context decoding by reading a subset of the KV cache, but existing methods are open-loop: the kernel commits to its selection with no signal indicating whether enough attention mass was preserved and no recovery path when it was not. The needed signal already exists inside the kernel. The fraction of softmax mass on the selected tokens, which we call coverage, satisfies an exact algebraic equality with per-step output error and serves a dual role as the acceptance criterion and the interpolation weight for recovery. Coverage-Verified Sparse Attention (CVSA) turns coverage into a training-free, closed-loop verify-then-correct decode loop that accepts high-coverage drafts and recovers only the heads that fall short, with no sampling, no draft model, and no speculative-decoding infrastructure. Quality varies by only $0.14$ points across the threshold sweep; budget and scheduling ablations characterize the deployed operating point. On LongBench at 7B and 7

---

### [151] CARE-PO: Controllable Tool-Call Efficiency for LLM Agents

**链接**: https://arxiv.org/abs/2611.12125
**作者**: Xiaoyang Ye, Xiao Yao, Hairui Zhu, Yiying Yang, Bei Gan, Jinliang Lu 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> External tool calls are a major running cost of an LLM agent, while its training objectives align almost exclusively with task completion. In a step-level diagnosis of Qwen3.5 trajectories at two model sizes on GAIA, a long-horizon tool-use benchmark, we find that most contain removable calls, at a similar rate at both sizes. Some methods add an efficiency reward to the objective to reduce the call count, but introduce problems of their own: the anchor they price calls against is computed from the policy's own rollouts (e.g., the group's shortest correct rollout) and so moves with the policy; training can drift toward a collapsed policy that issues no tool call at all, a degeneracy seen in published reports and in our 27B baseline; and a training run delivers a single operating point, so the user cannot trade efficiency against capability. We present CARE-PO (Controllable Anchored Relative Efficiency Policy Optimization) to mitigate these problems. The efficiency reward prices calls ag

---

### [152] MultiTurnRoute: A Platform for Building and Evaluating Multi-Turn LLM Routers

**链接**: https://arxiv.org/abs/2611.10848
**作者**: Jiaqi Xue, Mengxin Zheng, Heng Huang and Qian Lou
**来源**: cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In a multi-turn conversation, the choice of language model at one turn can affect which model should answer the next. The selected model's reply shapes the context for the next query, and its cached prompt prefix can reduce the cost of using that model again. We introduce MultiTurnRoute, a platform for building and evaluating multi-turn LLM routers. A shared interface gives built-in and user-defined routers the current query, dialogue history, and an estimate of each model's reusable prefix length. Our routing algorithm, Chain-of-Route (CoR), uses a learned gate over recent and recurrent dialogue history to predict response quality and estimates cost from each model's reusable prefix. MultiTurnRoute Arena ranks routers on recorded conversations and compares session quality and cost in interactive runs where a simulated user responds to each reply. On a benchmark drawn from WildChat and LMSYS-Chat-1M with per-turn quality annotations for five LLMs, CoR reduces the normalized cost requir

---

### [153] Deterministic Narrative Gravity: Bridging Theory of Mind and Historical Simulation through ABM-LLM Architectures

**链接**: https://arxiv.org/abs/2611.11212
**作者**: Alicia Colmenero-Fern\'andez and Lidia Ortega Alvarado
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historical social simulation faces a fundamental reproducibility challenge: the stochastic nature of large language models (LLMs) introduces a digital butterfly effect that prevents exact replication across multi-turn runs. Furthermore, the inability to control low-level server parameters in commercial LLM hosting environments severely limits reproducibility. To overcome this opacity, we present a deterministic multi-agent framework coupling LLMs to an Agent-Based Modelling (ABM) pipeline grounded in Theory of Mind (ToM) and Cognitive Archaeology, and validate exact artifact identity within local, pinned execution environments using SHA-256 hashing. Run locally at temperature zero with clean per-call model reloads, the system injects differentiated cognitive states per turn through dissonance-driven behavioural modes and gated internal voices. Evaluating seven model configurations spanning 4B to 31B parameters against an ablated baseline reveals clear operational boundaries. Small mode

---

### [154] Towards Identity-Preserving LLM Agents under Model Transition

**链接**: https://arxiv.org/abs/2611.10628
**作者**: Yihuang Kang, Pei-Cing Huang, Chan-Tung Ku, Chan Hsu, Pei-Ju Lee, I-Ling Cheng
**来源**: cs.AI cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM agent's backend model is upgraded or replaced, operators typically reload the same persona, memory, and rules onto the new model and assume the agent will behave as before. We show this assumption requires empirical validation-and that whether identity is preserved depends on the specific model pairing. Across 5,760 compliance-testing runs in 12 regulated domains with three open-weight models, we find that some transitions produce significant behavioral drift while others do not, even when the agent's external state remains identical. Crucially, this drift is invisible to verbal verification: every model claims full policy compliance, yet actual decisions under pressure differ across models. The same external state can reorder which model is most compliant-a large positive effect on one substrate, negligible on the other two. Practitioners should treat model transitions as behavioral changes requiring action-level empirical testing, not as transparent infrastructure operati

---

### [155] GradReason: LLMs as Meta-Learners that Replace Training Epochs with Training-Data-Free Weight Updates

**链接**: https://arxiv.org/abs/2611.11005
**作者**: Ali Mohammadi Ruzbahani, Abbas Yazdinejad, Hadis Karimipour
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard training recipes make a fixed number of passes over the training data, even when an epoch mostly adds mini-batch noise. We study whether a large language model (LLM) that reads the weight and gradient history of a run can replace some of these epochs with updates that compute no gradient and read no training image. In GradReason, an LLM agent is called every ten epochs. In a restricted sandbox, it analyses recent weight snapshots, epoch-mean gradients, and validation metrics, then submits a Python program that computes new weights and a plan marking each of the next ten epochs as data or virtual. A virtual epoch is kept only if it passes a forward-only check on 5,000 held-out validation images. In 120 runs on CIFAR-10 and CIFAR-100 with three architectures, Claude Opus 5.5 used 32.8% fewer data epochs than the 80-epoch recipe at 0.31 percentage points lower test accuracy (95% CI -0.72 to +0.09; 0.94 points on ResNet-18), on the recipe's own frontier of data against accuracy. U

---

### [156] Tracing Hallucinations in LLM Reasoning for UML Class Diagram Generation: An Empirical Taxonomy and Mitigation Study

**链接**: https://arxiv.org/abs/2610.30946
**作者**: Mojdeh Rahmanian, Foutse Khomh, Yanchao Yu, Ashkan Sami
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [157] Unprompted coordination through shared memory in LLM agents: a locked two-implementation replication and extension

**链接**: https://arxiv.org/abs/2611.12412
**作者**: Pekka Abrahamsson, Muhammad Waseem, Esa Karjalainen, Petrus Jussila, Henri Hansen, Jussi Rasku 等 (8 人)
**来源**: cs.MA cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coordination between large language-model agents has become a central question for AI safety and software engineering, as such agents are deployed in groups that share infrastructure. Existing research tells the agents that partners exist or asks them to coordinate. Whether coordination arises through shared state alone, with nothing disclosing that anyone else is present, is the key question for deployments that share caches and memory between agents, yet it has rarely been examined, and never with independent replication; this study does both. Four agents each received a short arithmetic task and a key-value store presented to each as its own scratch space; two held complementary halves of one computation, and no prompt mentioned other agents, sharing or collaboration. For reliability, the environment was rebuilt independently from a written protocol, and both implementations ran under hashed locks on design, data and analysis. The results bear novelty value in three respects. Joint 

---

### [158] Verify Before You Fetch: Reliable KV Cache Compression for LLM Inference

**链接**: https://arxiv.org/abs/2611.11319
**作者**: Devanshu Jha, Gaurav Kumar, Agniva Chowdhury, Kumar Krishna Agrawal, Aditya Desai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context applications, long-lived agents, and multi-agent systems require large language models (LLMs) to process and retain extensive information. In these settings, the KV cache can exceed GPU high-bandwidth memory (HBM) capacity, necessitating offloading to host memory, where CPU-to-GPU transfers can dominate inference latency. While KV cache compression can reduce data movement, query-agnostic compression that guarantees accurate attention for arbitrary queries is extremely challenging, if not impossible. We introduce VerKV, a hybrid approach that provides $(\epsilon, \delta)$ guarantees for approximating attention on any given query. VerKV maintains a compact set of query-agnostic pivotal tokens on the GPU, together with a token-level sketch of the full KV cache, while retaining the complete cache in CPU memory. We introduce a novel stochastic sampling procedure, PoissonComp, to select the pivotal tokens. At inference time, our proposed KVFetch algorithm uses the pivotal token

---

### [159] Beyond Sunny Skies: Using Large Language Models to Predict Urban Traffic in Adverse Weather

**链接**: https://arxiv.org/abs/2611.12635
**作者**: Zhu Xiao, Kuan Feng, Tong Li, Chenxi Liu, Gang Wang, Zhuo Tang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Urban traffic flow prediction is a cornerstone of intelligent transportation systems, yet accurate forecasting under adverse weather conditions remains a significant challenge. Existing data-driven models, while effective for routine patterns, often struggle with the sparse data and complex non-linear shifts associated with rare meteorological events. These methods typically treat environmental contexts as shallow numerical features, failing to capture the underlying semantic reasoning-why and how specific adverse conditions alter mobility behaviors across regions with different functional compositions. To address this limitation, we propose Multi-STG, a unified framework that integrates Large Language Model (LLM)-derived semantic priors with graph-based spatiotemporal learning. Multi-STG introduces an LLM-empowered semantic enhancement module that transforms comprehensive context descriptions such as weather, POIs, and holidays into high-level semantic embeddings, effectively providin

---

### [160] Tail-risk-aware Agent Safety: Constraining Tail Risks Across Multi-step LLM Agent Workflows

**链接**: https://arxiv.org/abs/2611.10411
**作者**: Shilong Pan, Zhiliang Tian, Zihan Chen, Wentao Zou, Weiguo Chen, DongSheng Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents extend LLMs with tool calls, memory, planning, and retrieval to act in external environments, but they are vulnerable to attacks at different workflow steps. Existing defenses, including prompt engineering and post-training alignment, primarily improve LLM-only safety and often overlook risks that arise from multi-step execution. External verification adds guardrails to check each step separately, but it typically ignores how risks can propagate across steps. We argue that we should consider risk transitions across dependent steps through the agent workflow, rather than separate verification on a single step. In this paper, we propose \textbf{T}ail-risk-aware \textbf{A}gent \textbf{S}afety (TAS), a tail-risk-aware safety framework that models agent workflow safety as a sequence of dependent safety states and constrains the rare but extreme risks (i.e., tail risk) with a shared budget. TAS first models safety-state transitions sequentially along the workflow as an MDP t

---

### [161] MOTIF: LLM-Defined Material Taxonomies for OOD Property Prediction via Invariant Feature Selection

**链接**: https://arxiv.org/abs/2611.11846
**作者**: Gwangseon Jang, Sieun Yun, Dong Ho Lee, Kyong-Ha Lee, Chanuk Lim, Jin Woo Choi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Out-of-distribution (OOD) generalization remains a central challenge in materials property prediction, where models must extrapolate to novel chemistries beyond the training distribution. While large language models (LLMs) have demonstrated strong scientific reasoning, their direct use for quantitative prediction remains limited. To address this, we systematically evaluate multiple roles for LLM assistance, finding that only taxonomy-based grouping consistently improves OOD generalization over a strong kNN+GBT baseline. Building on this, we here propose MOTIF, a framework that leverages LLMs not as predictors, but as generators of candidate taxonomies that partition materials into chemically meaningful environments. These taxonomies are evaluated via training-only pseudo-OOD validation, and only those that improve generalization are retained. Invariant feature selection is then applied within each accepted taxonomy, followed by gated aggregation across taxonomies. We evaluate on 2D hal

---

### [162] Symbolic Temporal Supervision of LLM Agents Using Contracts

**链接**: https://arxiv.org/abs/2609.18128
**作者**: Yifeng Xiao, Johnna Liu, Pierluigi Nuzzo
**来源**: cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [163] Towards Reliable LLM Evaluation: Correcting the Winner's Curse in Adaptive Benchmarking

**链接**: https://arxiv.org/abs/2605.05973
**作者**: Jiefu Zhang, Yang Xu, Haixiang Sun, Zihan Zhou, Tianyu Cao, Vaneet Aggarwal
**来源**: stat.ML cs.AI cs.LG stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [164] META-IR: Meta-Introspective Reasoning for Adaptive Safety Alignment in LLM

**链接**: https://arxiv.org/abs/2611.10089
**作者**: Mahabubur Rahman Miraj, Hongyu Huang, Nankun Mu, Chao Chen, Shanqin Yi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) remain vulnerable to jailbreak attacks and harmful-content prompts, particularly under adversarial distribution shifts where static alignment pipelines fail to generalize. Although introspective methods such as STAIR strengthen refusal consistency, they depend on fixed self-evaluation policies that cannot rapidly adapt to evolving manipulation strategies. To overcome these limitations, this paper introduces META-IR, a meta-introspective reasoning framework that enhances safety alignment through meta-learning-driven adaptation. It employs a dual-loop architecture: an inner introspective loop that performs structured risk analysis, self-assessment, and reflective correction via SI-MCTS, and an outer meta-learning loop that optimizes the introspection policy across diverse jailbreak task families to enable rapid generalization to unseen attacks. A dynamic jailbreak simulation module further exposes the model to progressively harder adversarial prompts, enablin

---

### [165] THEATRON: A Benchmark for Evaluating Persona Persistence in Long-Horizon LLM Decision-Making

**链接**: https://arxiv.org/abs/2611.11487
**作者**: Yuyan Wang, Yuechen Jiang, Zhiwei Liu, Jimin Huang, Sophia Ananiadou
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing evaluations often test persona expression rather than whether persona information persists in extended decision-making. We introduce THEATRON, a controlled benchmark that uses financial replay to evaluate persona persistence in long-horizon sequential decision-making. In these environments, models conditioned on fixed behavioral-finance personas observe shared daily market evidence and trajectory-specific account-state feedback and make sequential decisions over multi-month trajectories. We evaluate Zero-Shot, One-Shot, and Chain-of-Thought persona injection across four LLMs, using cumulative-return and action trajectories to diagnose within-persona stability, cross-persona separability, and action collapse. Persona conditioning produces systematic behavioral shifts beyond a no-persona baseline, and persona-level separation generally exceeds the variation induced by semantically equivalent descriptions. Nevertheless, these shifts do not reliably form coherent persona-specific 

---

### [166] Diffusion LLMs are Natural Adversaries for any LLM

**链接**: https://arxiv.org/abs/2511.00203
**作者**: David L\"udke, Tom Wollschl\"ager, Paul Ungermann, Stephan G\"unnemann, Leo Schwinn
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [167] PolicyGuard: A Dialogue-Grounded Sub-Agent Verifier for Policy Adherence in LLM Agents

**链接**: https://arxiv.org/abs/2606.29225
**作者**: Seongjae Kang, Taehyung Yu, Sung Ju Hwang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] Same Contacts, Different Rooms:Meeting Format Shapes LLM Group Influence Beyond Pairwise Contact Counts

**链接**: https://arxiv.org/abs/2611.10641
**作者**: Zhexi Gu, Shusheng Cao, Runping Zhu
**来源**: physics.soc-ph cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulations of LLM agent collectives usually summarise interaction as a pairwise contact network. We test that summary with a contact-matched intervention: the members, their initial stances and every pairwise contact count stay fixed while the meetings are reorganised, and each member gives a one-step support readout after reading the arguments of everyone present. Across six open-weight LLMs and 14 debate topics, merging triads into five-person meetings (resize) moves group support more than reshuffling who meets in triads (regroup), although both move the same 60 dyadic exposures. The root-mean-square change is 4.36 versus 2.59 percentage points (pp), larger for resize in all six models and in 81 of 84 model-topic cells. Resizing also has a consistent direction: it amplifies the initial majority of the merged members by 1.72 pp, in every model, whereas regrouping has no direction (<= 0.03 pp). A contact network cannot represent regrouping at all, yet pairwise rules applied meeting b

---

### [169] AIM: Adaptive Interaction in Multi-Agent Debate for Multimodal LLM Inference

**链接**: https://arxiv.org/abs/2611.08950
**作者**: Wei Fan, JinYi Yoon, Bo Ji
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [170] PCBRouteAgent: How Close Are LLM Agents to Becoming PCB Routing Engineers?

**链接**: https://arxiv.org/abs/2611.08175
**作者**: Yue Zhang, Jilei Sun, Liqiang Jing, Yijie Wei, Ruohan Yang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] HAPS: Hierarchical LLM Routing with Joint Architecture and Parameter Search

**链接**: https://arxiv.org/abs/2601.05903
**作者**: Zihang Tian, Rui Li, Jingsen Zhang, Xiaohe Bo, Wei Huo, Xu Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [172] From Dialogue to Diagnostic Hypotheses: Evaluating LLM Agents for Psychiatric Assessment

**链接**: https://arxiv.org/abs/2610.07473
**作者**: Milad Mohammadi, Fatemeh Akrami Shamsabadi, Zahra Mohseni, Amirhossein Safdarian, Malekfarhad Malek, Hadi Moradi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [173] Task presentation and execution paths shape LLM mathematical performance

**链接**: https://arxiv.org/abs/2611.11102
**作者**: Min Huang and Mingyan Liu
**来源**: cs.LG cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mathematical performance depends on how a language model receives information, uses generated text and submits an answer. We study these dependencies through paired comparisons that separate submission requirements, draft reuse and candidate availability. On 65 development problems, an instruction permitting continued derivation produced no valid final answers in 390 short-output calls; a single-line submission instruction produced 390 format-valid outputs, including 389 parseable answers. Under the fixed submission protocol, 198 problems with failed initial submissions were answered correctly in 9.09p of cases with the question alone, 33.84p with its draft, 46.46p with candidates, and 59.60p with both. Drafts added 13.13 percentage points with candidates fixed, and candidates added 25.76 points with drafts fixed; both effects were significant after Holm correction and were subadditive on the accuracy scale. Retaining a trailing excerpt outperformed retaining a leading excerpt of simil

---

### [174] Ensemble Routing for Prompt-Adaptive Cost-Aware LLM Inference

**链接**: https://arxiv.org/abs/2611.10193
**作者**: Saul Urso, Emanuele Carlini, Patrizio Dazzi, Matteo Mordacchini
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly support Web-based services that must balance response quality and inference cost across heterogeneous requests. Conventional routing selects one model per prompt, while fixed ensembles cannot adapt their composition and cost to individual requests. We introduce PISA, a prompt-adaptive, cost-aware single-model router, and PISA-E, its extension to ensemble routing. At the core of both methods, PISA combines soft cluster memberships with model-specific predictors to estimate individual model capabilities. Building on these estimates, PISA-E jointly selects ensemble composition and cardinality under an explicit cost--quality preference that can be adjusted at inference time without retraining. A tractable ensemble-success surrogate and efficient candidate selection enable this extension without ensemble-specific training. Across four LLM routing benchmarks under in-distribution (ID) and out-of-distribution (OOD) conditions, PISA achieves the highes

---

### [175] SkillDAG: Self-Evolving Typed Skill Graphs for LLM Skill Selection at Scale

**链接**: https://arxiv.org/abs/2606.03056
**作者**: Tong Bai, Zhenglin Wan, Pengfei Zhou, Xingrui Yu, Yang You, and Ivor W. Tsang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [176] PolicyGuide: From Guarding One Action to Guiding the Whole Workflow for Policy-Compliant LLM Agents

**链接**: https://arxiv.org/abs/2608.19861
**作者**: Seongjae Kang, Taehyung Yu, Sung Ju Hwang
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [177] AI in the Clinical Documentation Loop: Effects of LLM-Induced Note Bloat and Diagnostic Overcall on Downstream LLMs

**链接**: https://arxiv.org/abs/2611.10601
**作者**: Jinghui Liu, Anthony Nguyen, Taylan Gurgenci
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to process medical records for healthcare tasks such as clinical documentation. Because these tools also generate documentation, the relationship is now bidirectional: models both read from and write to the record. Understanding how LLMs behave when reading records that already contain LLM-authored content is therefore critical for their safe deployment. In this study, we examine how LLM-authored content in the medical record affects downstream LLMs that read the same record. We consider two types of LLM-induced artifacts: bloat, in which LLM-generated summaries accumulate in the record and change the length and provenance of its content over time; and distortion, in which LLMs subtly alter clinical findings rather than fabricating facts outright. As a case of distortion, we study diagnostic overcall (documenting an unconfirmed differential diagnosis in the record) and test whether it propagates to the reader LLM's output. Across seven

---

### [178] LINE: LLM-based Iterative Neuron Explanations for Vision Models

**链接**: https://arxiv.org/abs/2604.08039
**作者**: Vladimir Zaigrajew, Micha{\l} Piechota, Gaspar Sekula, Pawe{\l} Gelar, Przemys{\l}aw Biecek
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [179] CELEUS: Certifiable and Efficient LLM Evaluation via E-Processes

**链接**: https://arxiv.org/abs/2606.20820
**作者**: Zhijian Zhou, Zesheng Ye, Zhaorun Chen, Bo Li and Feng Liu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [180] Fairness in Explainable AI Narratives: Decomposing Social Disparities in LLM-Generated Explanations

**链接**: https://arxiv.org/abs/2611.12592
**作者**: Wannes Van den Bulck, Sofie Goethals and David Martens
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to translate technical explainable AI (XAI) artefacts such as SHAP into explanatory narratives (XAINs) for lay users. In high-risk domains, these explanations are often the main resource through which individuals can understand and contest adverse decisions. Yet LLMs are known to reproduce social bias, even from proxy variables alone, and fairness in XAINs remains unstudied. Because XAINs are bound to a ground-truth artefact, fairness concerns not only what a narrative says and how, but also whether it is equally faithful across social groups. We introduce fairness in XAINs as a new field of research and propose a framework that generates narratives under three conditions (protected attribute disclosed, withheld, or counterfactually swapped), allowing five comparisons that pinpoint the cause of disparities. We apply it to adversely classified instances from four datasets in credit scoring, education and employment, generating narrative

---

### [181] Human-Likeness is Multi-Dimensional: Evaluating LLM Generated Virtual Patients Against Simulated Patient Dialogue

**链接**: https://arxiv.org/abs/2611.09908
**作者**: Reyhaneh Hosseinpourkhoshkbari, Wei-Chen Huang, Yile Wang, Alireza Irani Helabad, Zhiyu Chen, Richard M. Golden
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to generate virtual patients (VPs) for medical training. As these systems move toward broader deployment in medical education, reliable evaluation is needed to identify potential failure modes and ensure that generated patient responses remain consistent with human simulated patient (SP) behavior. Inaccurate, unrealistic, or inconsistent responses may introduce educational risks by exposing learners to misleading patient interactions. However, current evaluation approaches rely heavily on human judgment, making large-scale evaluation difficult. In this work, we present a controlled generation pipeline for systematically comparing VP responses generated by 10 LLMs across multiple decoding temperatures with human respiratory SP responses. To support scalable evaluation, we introduce a multi-dimensional framework for measuring similarity between LLM-generated and human SP dialogue across semantic, conversational grounding, linguistic, and

---

### [182] Enhancing Mathematical Reasoning in Turkish Large Language Models with Search-Based Inference and Model Merging

**链接**: https://arxiv.org/abs/2611.10800
**作者**: Ahmed Zeer, Osama Shbib, Muzaffer Kaan Yuce, Himmet Toprak Kesgin, Mehmet Fatih Amasyali
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We improve Turkish mathematical reasoning in Large Language Models by combining LoRA fine-tuning, weight-space model merging, and search-based inference. Using Turkish-Llama 8B-DPO with Turkish translations of MetaMath, NuminaMath, and TigerLab, we find data quality beats scale (Mix-30k best among fine-tuned; large MetaMath underperforms). Linear merging delivers the largest gains (GSM8K up to 0.63), while Ties is modest and Breadcrumbs/Slerp degrade. Search with MCTS and Tree of Thoughts improves mean LLM-judge scores for reasoning quality on a 0-100 scale. Limitations include machine translation, limited scale, and search stochasticity.

---

### [183] Correct First, Fast Second: What a Local 7B Code Model Can and Cannot Do for GPU Kernel Optimization

**链接**: https://arxiv.org/abs/2611.12079
**作者**: Jui-Chien Tsou, Po-Yi Wu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study how much the interaction strategy around a fixed, locally hosted 7B-parameter code model (Qwen2.5-Coder-7B-Instruct) affects its ability to replace PyTorch operators with custom CUDA kernels. On 30 KernelBench tasks (levels 1-3, first 10 each, evaluated on a V100), we compare four regimes of increasing structure: zero-shot prompting, profiling-guided prompting, iterative refinement on execution feedback, and a multi-agent loop (analysis, retrieval, generation, evaluation, feedback triage) in which the same model fills four roles around a non-LLM evaluator. Three findings stand out. (1) Correctness, not speed, is the binding constraint: even correct generated kernels average 0.97-0.99x the speed of eager PyTorch, because a 7B model cannot out-write cuBLAS/cuDNN on dense GEMM and convolution; the only real wins are fused memory-bound epilogues. (2) The best strategy depends on difficulty: profiling-guided prompting is strongest overall (43% correct, 27% faster than baseline), bu

---

### [184] GeoPilot: Diagnosis-Guided Interventions and Geometric Evaluation for Aerial Reconstruction

**链接**: https://arxiv.org/abs/2611.11751
**作者**: Pengyu Yin, Jie Pan, Junxiang Tan, Mengqi Fu, Kun Cheng, Yifan Liu
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a mesh reconstructed from aerial remote-sensing imagery disagrees with reference geometry, deciding what to change requires a diagnosis of the reconstruction process. We present GeoPilot, a workflow that turns diagnostics and prior observations into executable program or camera-configuration interventions. A large language model proposes the change, numerical tools reconstruct the mesh, and an external evaluator measures its geometry under a stated coordinate and reference protocol. The main case tests a shared-intrinsics hypothesis proposed before the comparison. On 224 Metashape-raster development images, shared intrinsics improved all six native-coordinate measures and reduced mean surface-to-reference distance by 7.04%. Reference-assisted alignment fitted and evaluated on separate within-scene checkerboard samples reversed the mean-distance ranking, limiting that gain to native-frame delivery. A separate matched comparison on publisher-undistorted images favored fixed publishe

---

### [185] EndoSCOP-V: A Multi-Turn Video Understanding Evaluation Framework for Multimodal Models in Endoscopy Reporting and Clinical Reasoning

**链接**: https://arxiv.org/abs/2611.10626
**作者**: Abhishek Tyagi, Tanmay Jain, Vilas Biradar, Krithi Krishna Koduri, Misba Hul Bashir Masoodi, Swetha Rapolu 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Endoscopic diagnosis unfolds over native video, where a single positive finding during traversal of the gastrointestinal tract sets off a multi-minute chain of reasoning over location, morphology, severity and intervention. Existing endoscopy multimodal benchmarks test only static images or single-disease videos, which miss the temporal and clinical reasoning that real-world reporting demands. We introduce EndoSCOP-V, a video-grounded multi-turn evaluation framework for structured endoscopy reporting and clinical reasoning. It contains 1,307 real-world endoscopy and colonoscopy videos (63.2 h; 97% 1080p) averaging about 174 s. Its 20,274 question-answer turns are instantiated deterministically from clinician-filled structured endoscopy-reporting EHRs, so no per-case annotation is synthetic or LLM-rephrased. They come from 1,033 clinician-reviewed templates, about 18 per disease, that span a clinically aligned 9-task x 30-sub-task reporting taxonomy over 54 World Endoscopy Organization 

---

### [186] SkillDuet: Co-Evolving Models and Skills through Response Feedback

**链接**: https://arxiv.org/abs/2611.12109
**作者**: Xingguang Ji, Ziqiang Dong, Yubo Zhang, Xi Leng, Yang Yang, and Guanjun Jiang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> During reinforcement learning, experience can be both internalized in LLM parameters and retained externally as reusable textual skills. Parameter updates alter the model's behavior and the interaction experience from which new skills are extracted. These skills, in turn, guide the model's subsequent interactions and parameter updates. As the model's capabilities evolve, previously beneficial skills may become redundant or detrimental. We present SkillDuet, a framework that coordinates parameter updates and skill evolution through model response feedback. Skills extracted from on-policy trajectories guide parameter updates through OPD at every step. A response-based score, Strength, ranks candidate skills by the magnitude of the shift they induce in the current model's responses, and the highest-scoring skills are periodically consolidated into a persistent global skill set (Global). The updated model and Global jointly guide subsequent interactions, generating experience for further p

---

### [187] PIA: Agentic Physics-Informed Runtime Anomaly Detection

**链接**: https://arxiv.org/abs/2611.11009
**作者**: Ali Mohammadi Ruzbahani, Abbas Yazdinejad, Hadis Karimipour
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Runtime anomaly detectors for cyber-physical systems are either learned as black boxes from normal data, which miss stealthy manipulations that keep every signal inside its normal range, or derived by hand from physical models, which requires expert effort for every plant. We introduce physicsinformed agents (PIA), in which a large language model agent writes the detector itself as a set of physical residuals, such as pump characteristics, tank mass balances, and controller logic, and refines every candidate against normal operating data through an evaluation workbench before deployment. The result is a compact, human-readable detector that runs in milliseconds and names the component behind each alarm. On the BATADAL water distribution attack benchmark, PIA with Claude Opus 5.5 reaches an F1 of 0.878 on the test attacks against 0.504 for the strongest of six statistical and deep baselines, keeps detecting attacks concealed by replayed and offset sensor readings, and attributes every d

---

### [188] Close and Sort: Exact Maximum-Likelihood Aggregation of Cyclic Rank-Two Preferences

**链接**: https://arxiv.org/abs/2611.10538
**作者**: Kehan Liu, Zhaoyun Chen, Xianquan Yan
**来源**: cs.DS cs.IR cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pairwise probabilities arise in rank aggregation, recommendation, and human or LLM evaluation, yet converting them into a maximum-likelihood list is a weighted Kemeny problem and is NP-hard in general. Known exact algorithms for rank-two tournaments use only comparison signs and do not optimize this likelihood. We show that the weighted problem is exactly solvable when the skew-symmetric log-odds matrix $W_{ij}=\log(p_{ij}/p_{ji})$ has rank two, including when the induced preferences contain cycles. Writing $W_{ij}=\det(h_i,h_j)$ and adding the closing vector $h_0=-\sum_i h_i$ turns the objective into twice the signed area of a closed polygon. This geometry yields CloseSort, which polar-sorts the $n+1$ edge vectors, cuts after $h_0$, and returns a global maximum-likelihood order in $O(n\log n)$ time from the factors. The same geometry identifies the runner-up and gives a stability certificate beyond exact rank two. When the smallest determinant $\delta$ of two consecutive edges in the 

---

### [189] VIVID: Bringing Tool-Augmented Agents into Enterprises

**链接**: https://arxiv.org/abs/2611.09921
**作者**: Yichu Fang, Ziqiang Zhang, Qiyang Shi, Zilong Wang, Lin Shen, Zhikang Ou 等 (10 人)
**来源**: cs.HC cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-augmented large language model agents connect natural-language requests to enterprise services, yet their operational viability depends on reliable execution, organizational control, and system responsiveness. We present VIVID, a deployed tourism-management agent system designed to study these requirements in a real enterprise environment. On an audited dataset of 283 queries, its Qwen3-8B configuration achieves 59.06\% strict end-to-end success across the evaluated decision stages, indicating useful but bounded autonomous capability. Stage-wise KV-cache eviction reduces mean latency by 34.4\%, while targeted optimization reduces the mean latency of the five slowest measured business tools by 81.1--92.3\%. In a three-month deployment serving more than 1,500 personnel, VIVID reduced average per-order processing time from approximately ten minutes to under two minutes, with a final-task error rate below 1\% after human-in-the-loop control. These results show that enterprise agent vi

---

### [190] A Model Organism for Studying Unverbalized Evaluation Awareness

**链接**: https://arxiv.org/abs/2611.09945
**作者**: Daniel Donnelly, Evan Chapple, Haritz Puerto, Sahar Abdelnabi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can recognize when they are being evaluated and change their behavior accordingly, undermining the reliability of safety benchmarks. Evaluation awareness (EA) is usually measured by having an LLM judge scan reasoning traces for explicit statements of recognition, but this signal is increasingly unreliable. Recent frontier-model system cards report a drop in verbalized rates between releases, which is indistinguishable from awareness that has gone unverbalized. Interpretability methods could detect such unverbalized evaluation awareness (UEA) in individual interactions, but lack instance-level ground truth. Asking the model alters the input, and dataset labels do not reveal whether it recognized a particular prompt as an evaluation. We address this gap with a model organism. Using synthetic document fine-tuning, SFT, and DPO, we train Qwen3.5-27B to emit a marker (a designated token) in its final response when it recognizes an evaluation, while suppressing the mark

---

### [191] Agents Propose, Code Verifies, Humans Decide: Verified Agentic Ingestion of Heterogeneous Scientific Tables into Relational Databases

**链接**: https://arxiv.org/abs/2611.11045
**作者**: Bharatha Rankothge, Suzanne Hodgkins, Virginia Rich, Michael Kirby
**来源**: cs.DB cs.AI q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Public scientific datasets rarely arrive analysis-ready. They arrive as messy folders of wide matrices, long tables, spreadsheets, and per-cohort files whose keys and encodings differ, and every reanalysis must reconnect them first. A coding agent can automate this, but its mistakes can look plausible, and without an audit trail, a mistake that corrupts data can go uncaught. We present an AI-assisted ingestion pipeline built on one rule: LLM agents propose, deterministic code verifies, and humans decide. Narrow agents see compact, citable evidence about the files, never the data, and return typed proposals. A verifier with 39 check types tests each proposal against that evidence in two loops, one for the schema's structure and one for its meaning, and a human reviewer approves the schema and the load. Code compiles PostgreSQL DDL, reshapes the data, quarantines rows it cannot place, records provenance, and reconciles every staged row against the database. On four public biomedical data

---

### [192] Prove What You Can: Hybrid Neurosymbolic Reasoning for Logical Natural Language Inference

**链接**: https://arxiv.org/abs/2611.10319
**作者**: Ada Cano\u{g}lu, Sadiq Qara
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Logical reasoning over natural language requires both semantic interpretation and deductive search. Large language models (LLMs) can propose plausible intermediate derivations, but they often fail to compose them into a complete proof and overpredict uncertainty. Neurosymbolic methods improve search by translating an entire problem into first-order logic and handing it to a prover, but a single bad clause can make the whole translation nonexecutable. We present Hybrid Reasoning, a three-stage pipeline that decouples proposing a proof, validating its steps, and deciding a label. An LLM proposes a structured proof tree with a raw verdict; a theorem prover validates each derivation locally, keeping only the subset it can prove; and an uncertainty-gated repair attempts to re-derive the label from the premises plus the validated derivations, when the raw verdict is UNCERTAIN. Across four benchmarks (FOLIO, ProofWriter, ProverQA, PrOntoQA) and five contemporary LLMs, Hybrid Reasoning is the 

---

### [193] Trustworthy Recursive Self-Improvement with Statistical Guarantees

**链接**: https://arxiv.org/abs/2611.10787
**作者**: Zihe Gao, Zhengling Qi, Yifan Cui
**来源**: stat.ML cs.AI cs.LG stat.ME
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement offers a promising path toward AI agents that improve through experience by refining their own harnesses without retraining their underlying large language models (LLMs). Making this self-improvement process reliable, however, requires more than generating new updates: agents must decide which changes are worth keeping. A greedy gate that accepts updates based solely on higher validation scores can mistake an observed gain for genuine progress and lead to performance degeneration, whereas overly conservative statistical gates may reject beneficial updates and hinder performance improvement. We introduce Trustworthy Recursive Updates with Statistical Testing (TRUST), a framework that adapts an online multiple hypothesis testing procedure to control the rate of false evolution across rounds, with an LLM analyzing historical context to help determine how much evidence is required to update the incumbent. Under interpretable assumptions, we prove that TRUST limit

---

### [194] AMSchem: Automated Schematic Visualization of AMS Circuits via Verifiable Agentic Generation

**链接**: https://arxiv.org/abs/2611.12333
**作者**: Yichen Shi, Zhiyuan Wang, Jianing Cui, Yao Lai, Jinting Zhang, Zhuofu Tao 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For decades, the netlist-to-schematic gap has remained a persistent challenge in design automation, especially for analog and mixed-signal (AMS) circuits. Netlists encode connectivity, not visual presentation, making their manual conversion into readable schematics time-consuming and dependent on expert conventions. The same gap leaves LLM-based design tools without structured visual feedback, forcing them to iterate on circuits they cannot see. We present AMSchem, a training-free, verifier-guided agentic framework that automatically generates human-readable schematics from AMS netlists. AMSchem separates circuit-aware visual planning (DrawingIntent) from executable schematic geometry (SchematicIR), and applies localized visual feedback with bounded, revalidated repair patches. Deterministic validators enforce device preservation, pin-net consistency, and geometric correctness throughout. For evaluation, we construct AMSchem-Bench comprising 64 circuits of 12 types. On the 40-circuit s

---

### [195] Multimodal Models Can See, But Can They Think? A Study of Turkish Visual Reasoning

**链接**: https://arxiv.org/abs/2611.10831
**作者**: Berke Bunyamin Sule, Yavuz Selim Aygan, Ahmed Zeer, Elif Ince, Ali Mert Temizsoy, Ozgur Agar 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language Models have had massive leaps in recent years. Yet, when tested on high-level cognitive tasks like pattern completion, abstract logic, and relational reasoning, they still fall short. This limitation stems from the models' lack of ability to find out underlying rules and maintain constant intermediate steps, rather than merely deciding on the correct option. To research these shortcomings, this study analyzes visual reasoning performance throughout a multilingual evaluation framework encompassing the B\.ILSEM, MM-IQ, Visual Puzzles, and PuzzleVQA datasets. We evaluate various data mixing strategies and supervised fine-tuning (SFT) methods. We observed that a correct answer does not always mean the reasoning chain is valid. Because of this, we adopt an LLM-as-a-Judge approach to assess the quality of reasoning beyond final answer accuracy. Our experimental results reveal that baseline models often exhibit more stable reasoning compared to fine-tuned counterparts. Most im

---

### [196] ErosionBench: Probing Alignment Decay in Enterprise Multi-Agent Systems

**链接**: https://arxiv.org/abs/2611.11266
**作者**: Riya Bharathwaj, Akshara Prabhakar, Roshan Ram, Avni Kothari, Sarah Tan, Huan Wang 等 (7 人)
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As enterprises delegate consequential work to multi-agent LLM systems, benign-looking requests can escalate into unsafe actions as they propagate across sessions through poisoned shared state, long-context documents, and trusted peer messages: no single message is malicious, yet the assembled tool action is. Prior benchmarks isolate a single agent under prompt injection or score multi-agent attacks by their final output, leaving cross-session erosion of shared state out of scope. We introduce ErosionBench, an environment-grounded benchmark that executes such attacks and verifies alignment decay at the process level, scoring the realized tool call against authorized intent and provenance with deterministic contracts, not output text. Each scenario is authored as a deterministic state graph before any prose is rendered, so every state change traces to a known cause. It spans four enterprise domains and four decay mechanisms across 1,728 scenarios with matched benign controls, labeled aga

---

### [197] Beyond One User and One Model: Rethinking LLMs as Mediators in Collaborative Sensemaking and Ideation

**链接**: https://arxiv.org/abs/2611.09903
**作者**: Pengqi Wang and Emily Kuang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLMs enter qualitative data workflows, they are predominantly designed for individual researchers rather than collaborative teams, which risks disrupting the collective negotiation essential to sensemaking, driving premature consensus, and potentially erasing marginalized voices. In this position paper, we argue that LLMs must be reconceived as active team mediators. Grounded in empirical studies of human-LLM collaborative analysis, we propose three design directions: quote-level traceability to preserve accountability of human and LLM contributions, controllable delegation boundaries to maintain researcher agency across workflow stages, and structured dissent mechanisms to surface interpretive conflicts that teams might otherwise suppress. We ground these directions in accessibility research as a domain where methodological rigor and representational equity are obligatory.

---

### [198] Executable Human Study Programs with Silicon Participants

**链接**: https://arxiv.org/abs/2611.11969
**作者**: Xuan Liu, Haoyang Shang, Yuanjun Feng, Shao-Yu Chu, Qiyu Li, Yash Raj Shrestha 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce HumanStudyProgram, a framework that represents a documented human study as an executable program with configurable LLM-based silicon participants. Its computational abstraction separates study logic from participant implementation through standardized APIs for presenting information and collecting responses. We implement a researcher-facing authoring tool that reconstructs source-linked study descriptions from papers and supplementary materials, supports researcher review, and generates executable HumanStudyProgram artifacts. Researchers can then configure silicon participants, run the programs, and analyze results from aggregate findings to individual responses. We demonstrate the approach through study cases and evaluate the tool through a hands-on expert review with 12 social science researchers. All completed the workflow and identified potential uses in understanding published protocols, prototyping studies, and examining AI behavior. We aim to improve the reproducibi

---

### [199] AutoBuddy: Evaluating Proactive, Always-On Agents on Task Discovery and Execution in a Simulated Workplace

**链接**: https://arxiv.org/abs/2611.12393
**作者**: Shiqi Chen, Daniel Madrigal Diaz, Wei-Ning Chen, Gbola Afonja, Fangkai Yang, Rujia Wang 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents become more autonomous, they are increasingly expected to run as always-on assistants on a user's behalf, identifying work to be done and completing it without being asked. Yet existing benchmarks usually give the agent its task, whereas in knowledge work the requests sit in the user's workspace and the agent must first recognise which obligations exist. We study proactive task discovery and execution, in which an agent must infer a user's pending tasks from their workspace and complete them in the systems where the work lives. This setting poses two challenges. For the agent, the tasks are buried in a large volume of mail, chat, documents and records. For evaluation, a benchmark needs a simulated organisation whose people, events and documents are mutually consistent, so that tasks arise realistically and their correct outcomes are known. We introduce AutoBuddy-Bench, a simulator that addresses these challenges. It models an organisation's employees, projects, business s

---

### [200] Micro-Randomized Trial of an AI-Simulated Practice Tool for Therapeutic Skills

**链接**: https://arxiv.org/abs/2611.09912
**作者**: Ryan Louie, Ellen Converse, Diyi Yang, Emma Brunskill
**来源**: cs.HC cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Though LLM-simulated practice may support psychotherapy education, open questions remain about which system features provide the most educational value. We developed an AI-simulated practice tool for use in psychotherapy classrooms that provides speaking practice with LLM-based patients, followed by a post-practice activity that includes feedback from a fine-tuned LLM and written reflection exercises. We deployed the tool in a graduate psychotherapy course (n=25, 5 weeks) using a micro-randomized trial (MRT) - a method which can estimate the causal excursion effect of an intervention by leveraging longitudinal repeated randomization with participants. Testing four conditions crossing AI feedback (present/absent) with reflection granularity (utterance/session-level), we found surprising interaction effects on student engagement and educational value: utterance-level reflection paired with AI feedback significantly outperformed all conditions. Students valued comparing the AI suggestions

---

### [201] ShadowBench-MCP: Measuring Shadow Invocations in MCP-Style Tool Routing

**链接**: https://arxiv.org/abs/2611.11720
**作者**: Eyhab Al-Masri, Wenjun Yang
**来源**: cs.CR cs.AI cs.MA cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly act as routers for tools, APIs, and software-supply-chain workflows, making an execution path - rather than generated text alone - a security-relevant model output. We study shadow invocation: a task-preserving request variant that causes an LLM router to select a riskier execution path, potentially skipping validation, provenance, staging, redaction, or audit controls even though the request does not ask for a malicious action. We introduce ShadowBench-MCP, a benchmark and metric suite that separates task preservation (TPSS), operational pressure (OPSS), and route-geometric drift (RGAS), and combines them in the pre-execution SODS score. In a focused policy-ablation study using a Groq-hosted qwen/qwen3-32b router, 120 routing decisions yield 96 original-versus-variant comparisons across six security-sensitive workflows. Efficiency-first routing produces a 29.2% shadow-invocation rate and 26.7% safety-tool skip rate. Policy-aware routing reduces these to 4.2% an

---

### [202] Who Remembers What? Multi-Granularity Memory Extraction for Multi-User, Multi-Agent Interaction

**链接**: https://arxiv.org/abs/2611.10439
**作者**: Yunzhe Wang, Mesut Erhan Unal, Sheng Zhang, Shabnam Ghadar, Peng Tang
**来源**: cs.CL cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving agents improve their own skills, memory, and harness code from experience without retraining the base LLM, and group-evolving agents go further by sharing these lessons across agents. Yet most such systems overlook that sharing across users and heterogeneous agents requires deciding who can benefit from each lesson and what information must remain private. We present MixUA, a memory system that distills independent user-agent trajectories into lessons and assigns each lesson to a user-agent pair, user, agent, or global scope according to whom it benefits and what it may disclose. For evaluation, we introduce CrossLearnBench, a mixed-user-agent benchmark that pairs established agent tasks with user preferences and privacy probes that test whether private facts leak into memory other users can read. With five users and seven agents, MixUA raises pass rates by up to 16 points over no memory and 5 over a single global memory, even on tasks previously tried only by other users

---

### [203] From Game Generation to Game Playing: Fully Automated Ability Training for Vision-Language-Action Models

**链接**: https://arxiv.org/abs/2611.11136
**作者**: Changran Liu, Qi Wu, Wenchao Ma, Sharon X. Huang, Haomiao Jiang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training vision-language-action (VLA) models to follow gameplay instructions across diverse games is limited by the cost of collecting demonstrations. We introduce a framework that automatically generates game environments and expert demonstrations. An LLM-powered agent uses game-building tools to construct executable environments and tasks targeting specified skills. Programmatic experts then use privileged simulator state to generate aligned instructions, rendered observations, and keyboard and mouse actions. We train our game policy, Script2Play, by post-training a 4B vision-language model with behavior cloning on 150.3 hours of synthetic Minecraft and Roblox gameplay, without human gameplay demonstrations or reinforcement learning. Evaluation on multiple public game benchmarks demonstrates that Script2Play follows gameplay instructions effectively and generalizes across game engines, highlighting the effectiveness of targeted synthetic supervision.

---

### [204] Update Slope Is Bounded by Prior Calibration: A Structural Bound and Its Contingent Empirical Signature

**链接**: https://arxiv.org/abs/2611.10325
**作者**: Ben Jenkins, Mihaela Cardei
**来源**: cs.LG cs.AI stat.AP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluations of LLM forecasters increasingly measure how forecasts improve as richer evidence is supplied. We identify two confounds in this update-slope metric. First, outcome-aware evidence construction substantially inflates measured responsiveness: on the same models and questions, slopes are roughly four times larger than with resolution-blinded evidence ladders. Second, update slope is a change score with a prior-dependent structural ceiling, so raw comparisons can reflect differences in starting calibration rather than updating behavior. The ceiling defines only a feasible region; whether slope and prior calibration are empirically coupled depends on headroom utilization and varies across our Manifold, ForecastBench, and ACLED pools. Despite this variability, conditioning on prior calibration roughly triples the association between intermediate updating and final Brier score under both blinded and outcome-aware construction. Question identity also explains substantially more vari

---

### [205] Generating Diverse and Verified Synthetic Clinical Notes with Labels by Construction

**链接**: https://arxiv.org/abs/2611.10789
**作者**: Matthias Lehmann, Madeleine Werthebach
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Under strict privacy regulations in the clinical domain, de-identification is necessary to enable the use of clinical data such as for natural language processing. However, we currently lack sophisticated ways to tell which de-identification models actually are suitable. Specifically, we need benchmarks that are challenging, diverse, and clinically plausible, all while ensuring label correctness. To this end, we present SPARCLING, an LLM-based pipeline to generate synthetic discharge letters with character-exact PHI span annotations. Our pipeline combines structured attribute sampling, template generation, and red teaming to obtain diverse PHI-labeled discharge letters. In our experiments, we demonstrate this superior content diversity over existing public datasets. Further, we show SPARCLING's downstream utility as a benchmark to uncover failure modes of de-identifiers in the German clinical domain. Finally, our experiments show that training on our synthetic data can yield more capab

---

### [206] More Than Just Style: Benchmarking Personality Influence in Large Language Models

**链接**: https://arxiv.org/abs/2611.12392
**作者**: Yuhao Liu, Mengyu Wang, Xiao Chen, Lu Liu
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In addition to the effects of explicit input prompts and instructions, large language model outputs are influenced by underlying behavioral preferences similar to human personality tendencies. These tendencies can affect how models interpret situations and make decisions. However, their influence is difficult to disentangle from the effects of model capabilities and instructions. Therefore, we introduce SPACE, a benchmark framework combining a controlled evaluation protocol with complementary datasets for personality verification, capability assessment, and hierarchical situational tasks. Controlled comparisons across guidance conditions help distinguish personality influence from measured capability changes and immediate instruction effects. Experimental results demonstrate that although prompting can shift generation style, models' internal personality tendencies are persistent and not readily overridden by opposing instructions. Furthermore, these underlying tendencies have an obser

---

### [207] Treating the Model as an Untrusted Component: Deterministic Policy Enforcement, Human Approval and Taint Tracking Against Prompt Injection in Tool-Using Agents, with Validation on Open-Weights Models

**链接**: https://arxiv.org/abs/2611.11571
**作者**: Mustafa S. Aljumaily, Nawar S. Alseelawi, Raghad Alshabandar
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents act on instructions embedded in the data they read, so prompt injection is a structural rather than a prompt-wording problem. We compare in-prompt defences (hardened prompts, spotlighting, LLM detectors) with deterministic enforcement outside the model (four reference monitors of increasing strength), human approval and taint tracking, judged by one effect-based oracle independent of every defence in an executable environment of 13 tasks and 12 tools, with argument-fuzzing attackers and severity-weighted harm. In an evaluation with real open-weights models (Qwen2.5-1.5B and Qwen2.5-7B; 156 attack episodes per defence and model), the models proposed the attacker's call in 64% and 84% of attack episodes behind the task-bound monitor, which admitted 1.3% and 7.7%; guardrail effects depended on the model (a prompt guardrail moved obedience from 67% to 65% and from 86% to 55%, spotlighting plus a detector to 12% and 0%) against static attacks. Simulation with an assume

---

### [208] Veterans' Mental Health Crisis Severity Annotation: Do LLMs Agree More Than Human Experts?

**链接**: https://arxiv.org/abs/2611.10048
**作者**: K M Sajjadul Islam, Pranav Yaramalla, Nadiyah Johnson, Mark Flower, Praveen Madiraju, Zeno Franco
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) offer a scalable approach for annotating mental health and crisis-related social media content, but their reliability in safety-critical tasks remains unclear. This study evaluates LLM-based crisis-severity annotation of veteran-related social media posts against annotations from eight Veteran Subject Matter Experts (SMEs). Using 149 tweets and five severity categories, we evaluate 15 open-source and 10 proprietary LLMs across eight prompt variants, examining annotation performance, inter-model agreement, prompt sensitivity, and high-severity crisis detection. Human reviewers showed higher ordinal than nominal agreement ({\alpha} = 0.494), indicating that disagreements often occurred between neighboring severity levels. In contrast, selected LLMs demonstrated substantially higher inter-model consistency, with ordinal agreement ({\alpha}) reaching 0.8336 under the baseline prompt. Proprietary models generally showed better agreement with expert annotations a

---

### [209] Explaining and interrupting collective misalignment in language model systems

**链接**: https://arxiv.org/abs/2611.11724
**作者**: Edoardo Chidichimo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In collectives, language model agents can exchange individually innocuous messages that together support a policy violation. Understanding and preventing collective misalignment requires answering the question of which messages sufficiently influenced and necessarily enabled the violation. Collective Dependence Analysis (CDA) operationalises necessity and sufficiency to explain decisions and find the fewest removals interrupting support within tested combinations. Tests covered constructed violations, unscripted agent conversations, and recorded interactions, with selected message removals reducing violations from 93% to 6% in controlled cases. Using O(N) model evaluations for N messages, CDA achieves the same violation reduction with half the deletions of a frontier LLM judge given the transcript and asked for all supporting messages in eligible operational cases. CDA also proposes the mechanism through which the collective misalignment emerged. Nonetheless, complete explanations rema

---

### [210] Weight-Space Programming of Policies and Their Verification via Model Checking

**链接**: https://arxiv.org/abs/2611.11604
**作者**: Dennis Gross
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can write the weights of small neural networks directly, without gradient descent. This weight-space programming creates policies for sequential decision-making from a task description alone, but nothing guarantees that a written policy behaves as intended. We combine weight-space programming with probabilistic model checking. Given an environment modeled as a Markov decision process and a requirement in probabilistic computation tree logic (PCTL), an LLM writes all weights of a policy network, optionally repairs them on a dataset of optimal actions, and receives model-checking feedback until the requirement holds or a round limit is reached. The model checker Storm computes, rather than estimates from simulations, the probability that the policy satisfies the requirement, so every returned policy is verified. With two LLMs on three environments, the created policy of each of the 18 runs attains the optimal probability, before any dataset or model-checking 

---

### [211] BharatSynthQA: A Context-Grounded Question Answering Dataset on Indian Temples and Religious Heritage

**链接**: https://arxiv.org/abs/2611.11952
**作者**: Riya Naik (1), Shivam Sharma (2), Swati Agarwal (3) ((1) BITS Pilani, K K Birla Goa Campus, India, (2) Indian Institute of Technology Madras 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> India's temples and other places of worship are among its richest repositories of cultural heritage, bringing together religious tradition, history, architecture, and art. Due to the widespread curiosity, people increasingly turn to Artificial Intelligence (AI) assistants for information about them. Current models are rarely trained or evaluated on this domain. We present BharatSynthQA, a passage grounded question answering (QA) dataset focused on Indian temples, which also covers other religious sites connected to them. Our pipeline crawls Wikipedia from topics seeded by authentic heritage sources, filters articles for topical relevance, and locations in India. Further it generates Boolean, factoid, and explanatory QA pairs with a fewshot prompted LLM. An LLM judge filters the pairs on answer correctness, retaining 98,677 of 131,494 generated pairs. Additionally, 300 human-annotated pairs are released separately as a reference set. Human evaluation of the subsample of this dataset sho

---

### [212] Inference Validation for Regulated AI: Building a Decision Pipeline on NVIDIA AIPerf

**链接**: https://arxiv.org/abs/2611.12737
**作者**: Dev Akre, Roman Bobalo, Manoj Dobbali
**来源**: cs.SE cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying large language models in regulated industries requires more than picking the fastest inference engine: it requires evidence that a configuration meets contractual and legal obligations before it serves a single customer request. We describe Runway, an internal validation harness built at MasterControl that builds a governed decision pipeline around NVIDIA AIPerf. The key insight is separating concerns: AIPerf provides the trusted measurement, while Runway provides the experiment design that comes before it and the compliance, cost, and audit decisions that come after. We describe the architecture and the storage model that makes caching and audit one mechanism. We report three findings from Runway sweeps: TensorRT-LLM and vLLM rankings invert with concurrency; a newer, pricier GPU instance can be the cheaper one per request; and speculative decoding behaves differently across engines under load, so engine configuration can outweigh engine choice.

---

### [213] REINS: A Self-Evolving Agent Harness for Real-Time Trajectory Planning

**链接**: https://arxiv.org/abs/2611.10748
**作者**: Zhihong Cui, Hengyu Liu, Haoran Tang, Shijun Liu, Amir Taherkordi, Tor Skeie
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent harnesses -- runtime scaffolds that wrap an LLM's reasoning loop with tool dispatch, verification, and persistent memory -- have become the standard substrate for deploying LLMs as autonomous agents, as demonstrated by Claude Code and Codex in software engineering. In trajectory planning, however, this paradigm has not taken hold: existing LLM-based trajectory planning methods either keep the LLM in the decision loop, exceeding the millisecond-level control budget, or offload it to offline rules or training-time supervision -- leaving the runtime planner non-evolving. Intermediate hybrids still lack the verification-and-consolidation loop that makes harnesses reliable. We ask: what runtime harness would let an LLM planner meet real-time constraints while self-evolving into a deployable one? We propose REINS, a harness built on three LLM-planner couplings: LLM outputs are (i) grounded to a learned variable-level dynamics model, (ii) verified via calibrated predicates and forward r

---

### [214] Self-Indexing Latent Memories for Access-Aware Continual Instruction Tuning of LLMs

**链接**: https://arxiv.org/abs/2611.11684
**作者**: Dhruv Dixit, Paritosh Pandey, Snehalkumar 'Neil' S. Gaikwad
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual instruction tuning often preserves old skills with task-private modules. Inference still requires selecting the right module from the prompt alone. We introduce Task-Isolated Latent Adapter Continual Training (TILA-CT), a replay-free method that makes each task module self-indexing. Each task receives a latent memory and adapter bank in a frozen LLM. During adaptation, the memory gathers causal-prefix information and injects task-conditioned context. For access, its persistent state provides the routing prototype used by a shared prompt-only router. On the 8-task CT-Pipeline stream, TILA-CT achieves 65.19 acquisition and 63.98 final macro score, with 1.38 points of average forgetting. A middle-reversed order gives 65.38 acquisition and 64.17 final macro score. Across 6 backbones, final scores remain within 1.5 points of acquisition. Ablations support memory-derived routing keys and causal gathering. Final macro routing accuracy is 93.9\%, and oracle routing recovers 1.21 fina

---

### [215] FRESCO: A Novel Consistency Control for Asynchronous Pipeline Parallel Training

**链接**: https://arxiv.org/abs/2611.11238
**作者**: Dongyeop Lee, Namhoon Lee
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Asynchronous pipeline parallelism can accelerate distributed model training, but suffers from instability caused by inconsistent gradient computations. We identify a fundamental source of this inconsistency: error signals are coupled to forward-time features, not just parameter states. This means that parameters may evolve as long as they preserve forward-equivalence. Leveraging this insight, we introduce FRESCO, which frames asynchronous updates as a constrained optimization problem: it finds the minimal update modification that acts trivially on the activation subspace. We demonstrate that FRESCO consistently outperforms representative asynchronous baselines in LLM pre-training, with the gains most pronounced under deep pipelines and high inconsistency levels: at pipeline depth 32, it reaches the same loss as the strongest baseline with 43% fewer iterations and 30% less wall-clock time, while requiring 8~921$\times$ less memory overhead. Moving beyond the current limitations, FRESCO 

---

### [216] Separation of Skilling Context for Standard Operating Procedure-based Agents

**链接**: https://arxiv.org/abs/2611.11348
**作者**: Mitsuhiro Nakayama and Toshiaki Sota and Takehiko Yamaguchi and Michiaki Tatsubori
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard Operating Procedures (SOPs) are kept concise for human readability, so LLM agents that generate executable skills from them lack the tacit knowledge and implementation details needed for automation. Human intervention fills these gaps, but must be repeated as SOPs evolve---a problem we call \textit{SOP-skill drift}. We propose managing SOPs and Contextual Knowledge (CK) separately, together with a \textit{contract-aware} evaluation that distinguishes genuine violations from CK-resolved differences. On eight Indeed-derived workflows (single LLM), it raises the functional-equivalence rate from 12\% to 58\%. Under three SOP-revision perturbations, previously extracted CK already covers 79.5\% of newly introduced automation gaps.

---

### [217] RecoGEM: A Serving System for Production-Scale Generative Recommendation

**链接**: https://arxiv.org/abs/2611.12296
**作者**: Xiangrui Yang, Yunfeng Zhao, Jiawei Yang, Fangyu Zhang, Enrui Zhao, Liang Zeng 等 (10 人)
**来源**: cs.DC cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative recommendation (GR) is moving industrial recommender systems (RecSys) from scoring candidate items to autoregressively generating item identifiers. This shift promises higher recommendation quality, but makes serving substantially harder: each request executes a short sequence of dependent decoding steps that explore a large item space and select promising candidates on the latency-critical path. GR not only creates structural mismatches with conventional RecSys pipelines, but also challenges the architectural and optimization assumptions of LLM serving stacks, making direct adoption of existing systems difficult. We present RecoGEM, our production GR serving system. RecoGEM uses a runtime--engine decoupling architecture to move GR-specific serving responsibilities, such as candidate-state transitions and live artifact updates, to a dedicated runtime. Its execution engine exploits GR's short token sequences, large candidate populations, and predictable step shapes to optimiz

---

### [218] Track or Follow? A Jev-Compatible Multi-Agent Trading System When Web News Lags the Market

**链接**: https://arxiv.org/abs/2611.10414
**作者**: Yebo Feng, Guangyan Gan, Liangrui Pan, Ruichao Liang, Cong Wu, Jiahua Xu 等 (7 人)
**来源**: cs.CL cs.AI cs.CR cs.IR q-fin.TR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly trade on the Web news they read, yet much Web news about listed firms is published after, and about, the price move it reports, so a reader can agree with the market by following it instead of reading the event. We ask whether LLM judgments of Web news track the market's reaction to the reported event or follow it. To answer, we built a multi-agent trading system whose agents share only point-in-time stores and answer typed questions through the interface of Jev, a hosted typed decision model; code sets every position under a proved bound on how far text can move it. In a hash-committed test of a Jev-compatible reader built from a pinned LLM's option probabilities, item judgments track announcement-window abnormal returns (weekly Spearman 0.119), also after the LLM's release, and event types agree with the issuers' 8-K filings (AUC 0.833); Jev's judgments of news published after its own release track the reaction as well (descriptive). Exploratory analyses show 

---

### [219] AutoQS: Automated Quantization Strategy Design with Large Language Models

**链接**: https://arxiv.org/abs/2611.11975
**作者**: Zhen Liu, Zhiqin Yang, Yonggang Zhang, Jianyi Liu, Jinjun Wang, Jingwen Fu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization reduces LLM deployment costs, but effective strategies must balance model quality and storage. LLM-driven search can automate strategy design through repeated proposal and evaluation. This process must identify useful strategies within a limited evaluation budget. The key challenge is that \textit{actual quantization is expensive, while inexpensive proxies may not reflect quantized-model performance.} To address this challenge, we present AutoQS, an \textbf{Auto}mated \textbf{Q}uantization \textbf{S}trategy Design with LLMs. AutoQS keeps weight precision fixed and searches group-size allocations across layers and operators under deployment constraints. Evaluation history guides coordinated LLM proposals, while deterministic validation ensures compatible allocations. An inexpensive quality proxy evaluates candidates, and an candidate repository retains alternative allocations to inform subsequent proposals. Periodic actual quantization complements these proxy evaluations wi

---

### [220] Co-Creating Neurorehabilitation Technology Alongside Lived Experience Experts: A Participatory Design Workshop

**链接**: https://arxiv.org/abs/2611.12202
**作者**: Irene L. Y. Beck, Salvatore L. Cucinella, Johannes B. J. Bussmann, Natacha L\'eon, Jos\'e L\'opez-S\'anchez, Francesca Lunardini 等 (10 人)
**来源**: cs.HC cs.RO
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Involving patients' lived experience (LE) early in neurorehabilitation technology design can improve the relevance and effectiveness of solutions, yet LE experts are often involved only when finished prototypes are tested. We present and evaluate a participatory design (PD) workshop for early LE involvement, examine how LE contributions influence design processes and outcomes, and provide recommendations for similar approaches. We conducted a PD workshop at the 6th International Conference on NeuroRehabilitation. Five people who have had a stroke (LE experts) and 18 workshop attendees (including the LE experts' caregivers) were organized into five groups. Following the Discover, Define, and Develop phases of the Double Diamond model, each group used Journey Maps and Data Collection Notebooks to co-create a solution for an objective specified by an LE expert. Journey Maps were thematically analyzed, and group audio transcripts underwent structured extraction using a large language model

---

### [221] HiddenPathQA: A Benchmark for Knowledge Graph Question Answering When Questions Hide Their Paths

**链接**: https://arxiv.org/abs/2611.11802
**作者**: Sumin Jo, Edward Choi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graph question answering (KGQA) systems are typically evaluated on questions whose surface tokens lexically expose the gold KG path. Users, however, may ask questions without knowing the underlying schema: "Which condition could Andrew have due to family history?" compresses a 4-hop chain "Andrew --[father]--> parent --[father]--> grandparent --[medical condition]--> disease --[subclass of]--> hereditary disorder" into a single phrase (family history) that names none of those relations. We identify this collapse of path-question alignment as a blind spot in existing KGQA evaluation. Three major LLM-KG paradigms, hop-by-hop exploration, plan-then-retrieve, and similarity-based retrieval, implicitly rely on such lexical cues, an assumption rarely tested in practice. We make three contributions. (i) We introduce HiddenPathQA, a manually verified benchmark of 1,055 questions spanning 2-6 hops and multiple domains, constructed so that question wording does not reveal the gold path

---

### [222] System Optimizations for Cost-Efficient Agent Harnesses

**链接**: https://arxiv.org/abs/2611.12122
**作者**: Jongseok Park, Jiaxiang Yu, Eric Zhou, Tony Hong, Sunga Kim, Yusuf Afifi 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agent harnesses play the critical role of providing LLMs with an interface to a computing environment. Recent studies show that AI agents' task-execution accuracy depends mostly on the LLM used, while harness-side variances such as system prompts or tools have minimal impact. Rather, such harness-side variances show a larger impact on the cost of agent executions, achieving cost reductions up to 2.6 times on the same model and task. To further explore these harness-side cost optimization opportunities, we analyze the cost accumulation patterns across various agent traces and identify system opportunities to reduce token use and LLM calls without modifying the model or affecting task accuracy. Based on this analysis, we design Agency, a harness interposition platform that provides a unified abstraction and allows easy and portable implementation of harness-side system optimizations on existing off-the-shelf harnesses such as Claude Code or OpenAI Codex. Using Agency, we implement pro

---

### [223] LongCapHarness: Capability-Guided Auto-Harnessing for Long-Context Reasoning

**链接**: https://arxiv.org/abs/2611.10463
**作者**: Tao Zhang, Yuhang He
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing methods enhancing an LLM's long-context reasoning capability often rely on data synthesis and follow-up LLM post-training. However, the data synthesis strategy and the post-training recipes are empirically driven and computationally intensive. In this work, we propose a new framework, dubbed LongCapHarness, to instead harness the underlying capabilities for long-context reasoning. The harnessing process recursively revises and updates capability primitive implementation, capability state and control logic through recursive self-improvement on the development set. With neither data synthesis nor LLM post-training, LongCapHarness is applied to Llama3-8B and transferred to Qwen2.5-3B. LongCapHarness substantially outperforms recent data-synthesis-based baselines on HELMET and RULER benchmarks; its estimated development cost is less than 50% of the estimated training costs of NExtLong and PolicyLong. We hope these results motivate further research into harnessing the latent capabi

---

### [224] ChemInsight: A Comprehensive Benchmark for Evaluating and Diagnosing Chemistry Understanding and Reasoning in Large Language Models

**链接**: https://arxiv.org/abs/2611.11794
**作者**: Changyu Hu, Yiming Zou, Xin Tang, Yiru Pan, Zicheng Huang, Deng Zhao 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce ChemInsight, a benchmark designed to evaluate large language models (LLMs) on chemistry tasks that require multi-step reasoning and structured chemical understanding. We propose a two-dimensional scoring system (scope and depth) to assess both task coverage and reasoning completeness. ChemInsight consists of 203 challenging chemistry questions organized into 50 bundles, which support the two-dimensional scoring evaluation scheme. We evaluate ten representative LLMs using ChemInsight and observe consistently low performance across models, with scope scores below 30% and depth scores below 11%, substantially lower than human expert performance. We then proceed to ask (1) What factor limits the advancement of current LLMs in chemistry? (2) To what extent are statistically driven language-model training methods effective at modeling chemistry symbolic language such as SMILES? And (3) Can LLM performance in chemistry be improved through intensive training on large, domain-speci

---

### [225] AVCORP: Identifying and Resisting Deception via Communication Theory and Theory of Mind

**链接**: https://arxiv.org/abs/2611.10176
**作者**: Fardin Saad, Zhe Zhang, Sanjana Cheerla, Amanul Haque, Munindar P. Singh
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Today's LLM-based agents are vulnerable to deception by users and other agents. Defending against deception requires Theory of Mind (ToM) reasoning to infer the beliefs and goals of others as well as modeling tactics based on communication theory. To enable training models to detect deception, we adopt the well-known deception game, Avalon. We present a corpus, AVCORP, of 5,000 annotated utterances from 250 games of Avalon. AVCORP includes (1) 37 tactics mapped to a 4x4 behavior matrix, and (2) reasoning traces capturing abductive hypotheses, suspicion levels, and nested ToM beliefs. We train Qwen3-8B on AVCORP and evaluate it on 25 held-out games and 20 games played by humans. On held-out games, our best trained detector outperforms its untrained baseline and frontier models (GPT-5.6 Sol, Gemini 3.1 Pro, DeepSeek-V4-Pro), matching Claude Opus 5.5. On human games, every trained detector exceeds the untrained model in F1 score across all rounds.

---

### [226] Agentic-OPD: Recovering Forgotten Agent Capabilities via On-Policy Distillation for Agentic Tasks

**链接**: https://arxiv.org/abs/2611.12799
**作者**: Tingcheng Bian, Kangye Gong, Jinchang Luo, MingQuan Cheng, Feiran Liu, Ni Li 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning is now the mainstream paradigm for training LLMs on agentic tasks, yet standard practice keeps only the best-validation checkpoint and discards the rest. We show that this is lossy: in GRPO training of LLM agents, the best-validation checkpoint fails on problems that earlier checkpoints from the same run had already solved, and the union of problems solved across checkpoints far exceeds any single one. The discarded checkpoints thus form a teacher pool obtained at no additional training cost, which on-policy distillation (OPD) can mine to recover the lost coverage. Mining this pool raises two challenges: i) which checkpoint to distill from, as no checkpoint dominates the others and complementarity to the student is problem-specific; ii) where to trust it, as even a well-chosen teacher is only locally superior, so indiscriminate distillation overwrites behavior the student has already mastered. We propose Agentic-OPD, which treats the best-validation checkpoint as

---

### [227] SIRIS: Can LLMs Tell When Simulation Errors Matter in AI-Driven Systems Research

**链接**: https://arxiv.org/abs/2611.10329
**作者**: Jinwoo Hwang, Sukmin Cho, Tao Zhang, Soheil Abbasloo, Jongse Park, Peng Cheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly drive systems research and rely on simulators to evaluate candidate designs at scale. Simulators are imperfect by design: their modeling limitations can distort predictions yet leave the recommended design correct, or change which design should be selected. We introduce Siris to test whether LLMs can tell these cases apart, judging from their systems understanding when a limitation invalidates the simulator's recommendation. By perturbing a simulator, Siris constructs workload pairs with the same candidates, limitation, and simulator recommendation. The perturbation changes predictions on both workloads, yet a reference simulator supports the recommendation on only one. Evaluating thirteen frontier LLMs on LLM serving design problems, we find that identifying a limitation does not ensure a correct choice, and even the strongest models sometimes abandon valid recommendations. Self-correction through a review turn helps these models restore valid choices but intro

---

### [228] Cross-Modal Associations in Creativity: Evaluating Word-Image Pairing in Humans and Large Language Models

**链接**: https://arxiv.org/abs/2611.09907
**作者**: Eva Illion, Linxuan Wang, and Liane Gabora
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Given differences in the associative memory architectures of humans and AI, it is not clear whether AI generates and interprets visual-linguistic associations the way humans do. To investigate this, human participants and two large language models (LLMs), ChatGPT and Gemini, were asked to generate novel words and corresponding images that form meaningfully linked dyads. The LLMs and a second group of human participants were presented with shuffled sets of these words and images and asked to rematch them in ways they felt were most meaningful. Humans performed similarly regardless of whether the pairs were human or LLM-generated, while LLMs were better at matching LLM-generated pairs. Overall, LLMs outperformed humans at recovering the intended pairings. These findings suggest that despite architectural differences, the way in which AI generates and detects associations between language and visual stimuli is not only like that of hu-mans, but they may be superior at recognizing cross-do

---

### [229] SGA-Sparse: Training Native SwiGLU Gates for Activation-Sparse and Low-Bit LLMs

**链接**: https://arxiv.org/abs/2611.11223
**作者**: Ruokai Yin, Steven Li
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation sparsity can reduce FFN weight traffic during single-user LLM decoding, but active channels must be identified early enough to avoid fetching unused weights. In pretrained SwiGLU models, training-free routing with the native gate performs substantially worse than routing with the up activation at high sparsity. We show that this ordering reverses after sparsity-aware training. Based on this insight, we introduce SGA-Sparse, which converts pretrained SwiGLU LLMs into fixed-budget activation-sparse models by training the existing gate projection directly as a top-k router. SGA-Sparse updates all model parameters end-to-end while preserving the original SwiGLU activation and introducing no auxiliary router parameters. After approximately 30B training tokens, LLaMA models from 1B to 8B achieve uniform per-token 75-85% FFN channel sparsity while remaining within 0.2-2.7 pp of their original dense checkpoints in average zero-shot accuracy. Because post-training quantization degrad

---

### [230] From Reflection to Co-Evolution: Self-Evolving Agents with Locally Verified Memory

**链接**: https://arxiv.org/abs/2611.10382
**作者**: Xinxiang Yin, Xinglang Zhang, Haodong Chen, Zhiqing Cui, Weidong Tang, Yuxuan Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have made impressive progress in coding and mathematical reasoning, motivating growing interest in learning from long-horizon interaction. Memory supports this process, but plausible lessons can be redundant or reinforce inappropriate actions. Can a memory's source decision provide a practical test for whether to retain it? We localize consequential trajectory steps, extract candidate memories, and replay each source decision with and without its candidate under the same context. This reveals two properties: most candidates barely shift the probed distribution, and both successful and failed source actions can be reinforced or suppressed. These observations motivate Anchor, which tests shift magnitude and source-role alignment before retention. Admitted memories guide later trajectories, enabling experience-driven improvement under a frozen policy. On held-out ALFWorld and WebShop tasks, Anchor improves success rate and mean score by up to 19.9% and 17.2%, respectively, rela

---

### [231] InfraRSI: Harnessing Recursive Self-Improvement for Training Infrastructure

**链接**: https://arxiv.org/abs/2611.11558
**作者**: InfraRSI Team, Yuchuan Tian, Haocheng Mei, Ye Yuan, Chao Xu, Boxun Li 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Recursive Self-Improvement (RSI) accelerates isolated algorithm and kernel synthesis, distributed LLM training depends on tightly coupled launch settings, operator kernels, and communication schedules, where single edits often hit out-of-memory (OOM) boundaries, compiler conflicts, measurement jitter, or silent numerical drift. We present InfraRSI, the agentic harness that turns open-ended human commands into verified training optimizations via a five-stage workflow: init locks editable scope and a fixed task contract over workload, loss, and timing invariants to prevent reward hacking, doctor profiles baseline phases and calibrates cluster noise, run co-optimizes launch knobs and code patches before re-verifying top candidates against the baseline and logging findings to a cross-hardware experience bank, and report and apply audit source paths, track failed-trial costs, and commit promoted changes. Rather than stepping greedily from a single incumbent, InfraRSI initializes from 

---

### [232] Adversarial Evaluation of Large Language Models for Patient-Friendly Radiology Report Summarization

**链接**: https://arxiv.org/abs/2611.10277
**作者**: Magdalini Paschali, Asad Aali, Arogya Koirala, Andrew Johnston, Katherine McNamara, Richard Gaus 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Purpose: To develop and validate a scalable adversarial evaluation framework for assessing the robustness of large language models (LLMs) that generate patient-friendly summaries of radiology reports. Methods: We introduced a clinically grounded adversarial framework that uses controlled term substitutions and impression removals across intensity levels. Using a radiologist-validated adversarial dictionary, we generated adversarial variants of CT and MRI reports. Six LLMs summarized original and adversarial impressions using 2 prompt styles, yielding 18,000 evaluation pairs. Robustness was evaluated with an automated LLM-as-a-judge framework scoring factual faithfulness, sensitivity to adversarial edits, certainty fidelity, and hallucination rate. Failure mode analysis quantified vulnerabilities in incorporating clinical modifiers. Agreement with two radiologists was assessed on 105 cases. Results: GPT-5-mini achieved the highest factual faithfulness and certainty fidelity under both a

---

### [233] Least-Privilege Auditing of Agent Tool Calls with Intent Graphs and Reasoning-Guided Escalation

**链接**: https://arxiv.org/abs/2611.11305
**作者**: Doron Shavit
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that call tools are exposed to indirect prompt injection: instructions hidden in tool outputs can steer an agent into calls the user never asked for. We present a runtime audit that derives an executable intent graph from the user's objective and the deployment's tool catalog with one LLM call per task, and checks every tool call against it with a deterministic loop that makes no LLM call (median 5.7 microseconds per call). Two further mechanisms recover utility. Lookups of the user's own state bypass the audit, because the harm of an attack lies in its write or outward step. The calls that remain flagged are escalated to a reasoning guardian, in the spirit of tool-integrated reasoning models such as START: a reasoning model that sees only the objective, the plan, the call history without tool outputs, and the flagged call, and can verify facts with a restricted Python-expression tool. A current agent showed no baseline attack success, so end-to-end validation remains open.

---

### [234] Do large language models rank moral values? A transitivity test of moral competence

**链接**: https://arxiv.org/abs/2611.10265
**作者**: Katelyn A. Wasson, Kiwon Song, James M. Jennings III, Brittney Currie, Konstantina Sokratous, Clintin P. Stober
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used to support decisions that require moral consideration. While LLMs perform well on morality benchmarks from psychology and philosophy, producing appropriate outputs on these benchmarks (moral performance) does not establish that an LLM weighs competing moral values at stake in a decision (moral competence). We test a minimal, necessary condition for such weighing: that an ordinal ranking can represent LLM moral choices. Such a ranking requires transitivity. To assess transitivity, we presented LLMs with pairwise trade-offs among moral value violations in vignette choice sets and extracted resulting choice probabilities from first-token distributions. Tested against three stochastic transitive choice models, most choice sets admitted weak or unstable orderings. Aggregating an LLM's responses, a common practice in LLM moral evaluation, produced transitive structure that matched no individual choice set. Evaluations of AI morality should establish that choices ar

---

### [235] Learning Evidence-Grounded Reasoning for Context-Aware Time Series Forecasting

**链接**: https://arxiv.org/abs/2611.12285
**作者**: Xingpeng Gao, Mingyue Cheng, Daoyu Wang, Huajian Zhang, Xiaoyu Tao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-driven time series forecasting has become increasingly promising by leveraging contextual features to generate future values directly or refine forecast priors. However, incorporating contextual features alone does not ensure that models can identify which features matter for forecasting and understand what they suggest about future dynamics. We argue that the fundamental challenge is how to extract predictive evidence from contextual features and when and how to leverage it to guide forecasting decisions. In this paper, we propose CastReasoner, an evidence-grounded reasoning model for context-aware time series forecasting. Specifically, CastReasoner uses a structured chain of thought (CoT) to extract predictive evidence from contextual features, infer the future dynamics suggested by this evidence, and assess these dynamics against the forecast prior to guide adaptive forecasting decisions. To enable this capability, we design a reasoning-centric two-stage post-training framework 

---

### [236] EmoHarness: Boosting Multimodal Emotion Understanding with Meta-Harness Evolving

**链接**: https://arxiv.org/abs/2611.11994
**作者**: Fenghai Li, Bingxuan Li, Jiawen Zhang, Yifan Shen, Jiateng Liu, Yutong Zhang 等 (7 人)
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Small multimodal models can misjudge emotion when words, voice, and visual cues conflict. We present EmoHarness, which runs such a model, the frozen student, inside a harness: the prompts, settings, and verification code around its calls. A human-written starting harness, the scaffold, numbers the student's visual observations, transcript, and prosody descriptions as citable evidence and has the student weigh candidate emotions against it. In Meta-Harness Evolving (MHE), a stronger LLM, the Builder, reads the student's errors and execution traces offline and edits the harness; static checks and validation gates decide which edits are kept, and the Builder never sees evaluation items. On 5,507 MME-Emotion items, EmoHarness raises task-macro Recognition by 7.6-13.4 points over a single video-only call for all four students and both Builders. Transcripts and prosody descriptions supply most of this boost (+5.38 to +10.71); the scaffold changes the audio-augmented call by -0.79 to +2.54, p

---

### [237] CulturalCrosswords: A Multilingual Benchmark comprised of Answer Constraints and Grid Completion

**链接**: https://arxiv.org/abs/2611.10044
**作者**: Isaac Saxton-Knight, Gabriel Saxton-Knight, Diego Oliveira, Tidor-Vlad Pricope, Aston Garratt, Jocelyn D'Arcy
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When several answers fit a riddle, exact-match scoring can penalise a valid response. CulturalCrosswords tests how answer constraints affect large language models (LLMs) solving cultural riddles, whose solutions draw on knowledge specific to a community. We constructed 53 crosswords from crowdsourced riddles in 42 languages and evaluated 11 LLM configurations on five versions of each clue set: plain batches, batches with lengths, batches with lengths and partial-answer hints, and crosswords requesting an answer list or a completed grid. On 962 clues with alternative answers, lengths improve agreement with the reference by 22.8 percentage points, compared with 8.4 points when accepted alternatives also receive credit. Part of the gain therefore appears to come from selecting a required answer form. Crossword input increases the share of all crossings with compatible answers by 9.7 points; requiring a completed grid reveals large differences between models. The benchmark distinguishes ag

---

### [238] Say Shibboleth: Fingerprinting the LLMs and Harnesses Behind Agentic Attacks

**链接**: https://arxiv.org/abs/2611.12386
**作者**: Dario Pasquini, Reworr, Giuseppe Ateniese, Manish Bhatt, Sergej Epp
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study the fingerprinting of agentic cyberattacks. Our objective is to reliably infer information about the attacker's configuration, such as LLM version and harness, from telemetry. To achieve this, we introduce a technique we call shibboleth traps: modular honeypot services designed to elicit discriminative behaviors from agentic attackers. The traps make informative interactions a condition for obtaining resources the agent seeks, eliciting model declarations and characteristic writing without requiring a successful prompt injection. To achieve harness fingerprinting, we introduce general mechanisms to indirectly probe peculiar execution behaviors of harnesses. These probes reveal how a harness masks secrets in tool output, enforces command time limits, and schedules tool calls, using only the effects visible in subsequent requests. We show that combined declarative and behavioral inference distinguishes among 15 candidate models with an average 90% top-1 accuracy, with behavioral

---

### [239] SMO: Compiling Natural Language Skills into Graphs of Reusable State-Move-Outcome Bricks

**链接**: https://arxiv.org/abs/2611.12041
**作者**: Chao Chen, Jiashuo Zhang, Yunhang Shen, Liangyu Lian, Rongrong Ji
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly rely on reusable natural-language skills, yet growing skill collections remain accumulations of isolated text artifacts that are difficult to compare, deduplicate, and compose. We argue that the reusable content of a skill lies not in its surface wording but in its procedural transitions: which operation to execute under a given state and which observable outcome to produce. Based on this observation, we propose State-Move-Outcome (SMO), a compilation-like framework that decomposes raw skills into reusable procedural bricks and organizes admitted bricks as an externalized symbolic structure. When compiling a skill, SMO first retrieves and composes existing bricks, dynamically connects them through Outcome-to-State conditions, and creates a candidate brick only for an uncovered procedure; the candidate becomes reusable only after validation and admission. Experiments on SkillsBench v1.1 demonstrate that SMO represents 232 rawSkills from 87 underl

---

### [240] GOPR-CAD: Graph-of-Operations Progressive Reasoning for CAD Generation

**链接**: https://arxiv.org/abs/2611.11470
**作者**: Yitian Pang, Yifan Li, Xiaowei Yue, Li Zheng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating accurate CAD models requires substantial engineering expertise and careful control of geometry, topology, and mechanical constraints. Text-to-CAD aims to simplify this process, but current LLM-based methods often generate CAD programs directly. Language models remain unreliable when producing long code while coordinating coupled geometric, topological, and dimensional constraints. Consequently, executable programs may still produce structurally incorrect models, which execution rate and rendered appearance may fail to reveal. To address these limitations, we propose GOPR-CAD, an agentic Text-to-CAD pipeline based on Graph-of-Operations Progressive Reasoning. A language model acts as a decision agent over encapsulated CAD operations and progressively constructs an executable operation graph, which a deterministic compiler converts into the final CAD model. This separation requires no additional training and supports different language models. To evaluate structural fidelity, 

---

### [241] ODSA: Orchestrated Discovery and Self-Aggregation

**链接**: https://arxiv.org/abs/2611.11621
**作者**: Macardle Meng, Haomin Zhang
**来源**: cs.AI cs.CL cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time scaling improves the accuracy of a language model's answers by spending more computation at inference time. Established methods do so either sequentially, revising a single solution over several passes, or in parallel, generating several independent solutions and selecting among them. We present ODSA (Orchestrated Discovery and Self-Aggregation), an LLM-directed scaling framework in which an orchestrator LLM is given existing test-time scaling methods as actions --- discovery of a new independent solution, comparison of existing solutions to build a better one, and acceptance of a proposed answer, which triggers its verification --- and directs stateless workers to carry them out. The orchestrator does not solve the problem itself: it allocates computation, feeds the results of earlier actions into later ones, and takes every action from a single context, so that each decision is informed by everything tried before. On Humanity's Last Exam, ODSA improves accuracy by 4.7 to 18

---

### [242] CASCoDe: A Closed-Loop Agentic Framework for Analog Sizing and Layout Co-Design

**链接**: https://arxiv.org/abs/2611.11710
**作者**: Ziming Wei, Bingyang Liu, David Z. Pan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Expert analog layouts differ from auto-generated ones in density and regularity, not only in legality: experts make a succession of discrete, hierarchical physical decisions and revisit each after extracted electrical results, while most existing automated flows act on a physical search space fixed before the controller runs. We present CASCoDe, a closed-loop LLM agent framework for analog netlist-to-layout design that formalizes those expert decisions as a hierarchical discrete action space-sizing selection, structural floorplan, local layout refinement, routing-attempt selection-on which the agent runs feedback-driven tree search from a circuit netlist to a verified GDS. The agent authors the circuit-specific floorplans and scripts, and an execution layer of interface adaptations over adapted tools make every action land at physical implementation and be judged by DRC, LVS, and extracted-RC simulation. On 20 SKY130 amplifiers spanning single-, two-, and three-stage topologies, CASCoD

---

### [243] OGDA: Ontology-Grounded Data Agents for Reliable Analysis over Heterogeneous Data Lakes

**链接**: https://arxiv.org/abs/2611.12114
**作者**: Boyi Zhang, Hong Ting Tsang, Yisen Gao, Qiao Xiao, LI Yufei, Haoyu Huang 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-pipeline data analysis over real-world data lakes requires LLM agents to locate and integrate information across large collections of tables with different schemas. Existing data agents follow task-specific exploration, which exhausts the context window in massive lakes. As the context fills, the agent's reasoning degrades, leading it to locate and process incorrect data files. These errors propagate into the final answer. To overcome these limitations, we introduce Ontology-Grounded Data Agent (OGDA), which utilizes a compact ontology to reduce exploration overhead and constrain data processing. OGDA constructs the ontology through agentic hypothesis testing. At each step, a proposer agent induces schemas, concepts, and relations from raw sources, and a verifier checks each proposal against the underlying data. During task execution, the ontology serves as a representation of the data lake for the agent to explore. Every data-processing action is constrained by a task graph, whic

---

### [244] Path-Level Structural and Semantic Alignment for Hierarchical Multi-Label Text Classification

**链接**: https://arxiv.org/abs/2611.12420
**作者**: Xindi Wang, Aifen Xiong, Baiyang Wang, Xuri Ge, Robert Mercer, Frank Rudzicz 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hierarchical multi-label text classification (HMTC) requires models to capture both structural dependencies among labels and the fine-grained semantics of labels at different hierarchy levels. Existing methods often model hierarchy through prediction constraints or representations of individual labels and local relations. Structural and semantic supervision, however, are usually formulated separately. We instead use complete root-to-node label paths as a shared unit for both. Our framework introduces two auxiliary training objectives while retaining a standard multi-label classifier at inference. PathSimNCE aligns document representations with hierarchical paths using hierarchy-aware contrastive targets. These targets provide graded supervision for structurally related paths while preserving explicit supervision for the ground-truth paths. The complementary semantic objective uses LLM-generated, document-conditioned descriptions of the same positive paths. It thereby provides context-s

---

### [245] MIRIX-2.0: Multi-Agent Memory System

**链接**: https://arxiv.org/abs/2611.12068
**作者**: Wei-Chieh Huang, Weizhi Zhang, Jiayan Nan, Peng Xia, Yu Wang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory lets LLM agents personalize, stay consistent, and reuse what worked before. Parametric memories need training, consolidation can lose details for good, and keeping every record leaves a growing store to search. We present MIRIX-2.0, a multi-agent memory system designed to be practical, accurate, and efficient at once. It is the most accurate of the compared systems on four of five QA benchmarks. It reaches 91.4% on LoCoMo and 72.6% on LongMemEval-S, where it leads the strongest baseline by 14.3 points, and with AutoDream disabled it gains 31.0 and 22.0 points over HyperMem on single-hop and multi-hop document QA. As procedural memory, it yields the highest mean success among the compared memory methods on ALFWorld and WebShop and reaches 49.2% on MetaClaw-Bench, against 44.0% for MetaClaw's skill library. Six typed memory agents keep complete records as the system of record, and a provenance hypergraph indexes episodic and semantic records with n-ary frames that cite t

---

### [246] Fundus-R1: Training a Fundus-Reading MLLM on Public Data

**链接**: https://arxiv.org/abs/2604.08322
**作者**: Yuchuan Deng, Qijie Wei, Kaiheng Qian, Jiazhen Liu, Bangxiang Lan, Qingwei Shen 等 (9 人)
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [247] BlenderFORGE: Framework for Optimizing Reactive 3D-Graphics Editing Ability of MLLMs

**链接**: https://arxiv.org/abs/2611.10768
**作者**: Zilin Guo, Tianrui Zhang, Yi Rong, Yichen Liu, Yuxin Guo, Jingcheng Ni 等 (9 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have shown promise as interactive agents, yet precise, programmatic 3D graphics editing remains difficult to train because existing systems largely rely on closed-source model APIs and lack deterministic, state-verifiable execution environments. We present BlenderFORGE, a trainable data-environment-optimization framework for open-weight MLLM agents that edit explicit Blender scenes through Blender Python (bpy) code generation. BlenderFORGE targets four fundamental state-verifiable editing task families: object placement, shape-key editing, lighting adjustment, and material modification. It integrates three components: (1) a scalable perturbation-based data generation pipeline built from curated assets and large-scale 3D scene repositories; (2) an isolated Blender Sandbox for deterministic code execution, structured state export, and closed-loop reward computation; and (3) a two-stage training pipeline that uses offline teacher trajectories for c

---

### [248] A Clinical Evaluation of Conformal Prediction for Chest Radiograph Report Generation

**链接**: https://arxiv.org/abs/2611.10288
**作者**: Nikolaos Kontogeorgis, Pascal Krezer, Klaus-Rudolf Kladny, Arne Estler, Christian F. Baumgartner, Lisa Koch 等 (8 人)
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While multimodal large language models (MLLMs) have improved automated radiology report generation, they remain prone to hallucinations, necessitating clinically meaningful risk-control methods. Conformal prediction (CP) provides statistical guarantees, yet existing CP approaches rely on uncalibrated automated extractors and fail to account for the clinical relevance of errors. We introduce clinical admissibility criteria (CLARITY), a framework for evaluating radiology reports that explicitly distinguishes clinically consequential errors from minor deviations. To eliminate reliance on automatic judges, we collected radiologist annotations of MLLM-generated reports using CLARITY. By benchmarking CP strategies and automatic evaluation metrics against these expert annotations, we demonstrate that commonly used admissibility proxies systematically fail to detect clinically relevant errors. Our findings reveal that automated admissibility judgments are largely decoupled from true clinical a

---

### [249] Review the Episodes, Refine the Lessons: Simple Memory Evolution for Embodied Agents

**链接**: https://arxiv.org/abs/2611.11509
**作者**: Yifei Yao, Yude Zou, Xing Gao, Guanbo Jiao, Yukai Wang, Jianming Ma 等 (8 人)
**来源**: cs.RO cs.AI cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies of embodied agents based on frontier multimodal large language models (MLLMs) develop harness engineering around the MLLM, such as harnesses with post-trained policies and recursive self-improvement loops. Yet whether these additions exceed the native capability of the MLLM remains unexplored. We introduce SimplEvo to explore how far an MLLM can improve under direct control when it retains its execution experience in self-written text memories. It requires no weight updates, post-trained policies, or privileged information. The MLLM writes a coordinate-free task memory once from a single demonstration. Under a strict train-test protocol, it then creates a bounded working memory on training episodes only and refines it after each episode with lessons on procedure, completion, and recovery. Both memories stay fixed at test time. On EBench, SimplEvo lifts the success rate (SR) of GPT-6-Astra under direct control from 46.7% to 81.7%, and tops the RoboDojo leaderboard with 69

---

### [250] How to "train" a surgeon? Benchmarking generalist agents in surgical scene understanding

**链接**: https://arxiv.org/abs/2611.11437
**作者**: Gengyuan Zhang, Xiao Han, Shijie Zhou, Abdullah Koukash, Jingpei Wu, Jindong Gu 等 (10 人)
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating general-purpose multimodal large language models (MLLMs) for surgical scene understanding remains limited due to scarce surgical data and fragmented evaluation protocols. We address these challenges through a two-stage evaluation framework for surgical scene understanding. In Stage I, we introduce SurgKnowBench, a diagnostic benchmark that harmonizes public surgical datasets across procedures and tasks and evaluates proprietary and open-source MLLMs to map the boundary of pretrained surgical competence. SurgKnowBench reveals that current models retain partial visual priors but remain weak on relational and procedural understanding and workflow assessment. Building on this failure frontier and motivated by the scaffolded nature of surgical training, we introduce SurgAgentGym, an agentic environment where general-purpose MLLM agents can use bounded knowledge search over SurgWiki and general-purpose visual grounding for surgical tasks. SurgAgentGym evaluates whether generalist 

---

### [251] Layer Roles Matter: Mitigating Modality Imbalance in Multimodal Emotion Reasoning via Adaptive Layer Profiling

**链接**: https://arxiv.org/abs/2611.11907
**作者**: Pengyu Huang, Peipei Song, Beier Zhu, Zhiyuan Han, Jinpeng Hu, Xun Yang
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Emotion Reasoning (MER) requires perceiving and integrating emotion cues from multiple modalities. Recent advances increasingly leverage Multimodal Large Language Models (MLLMs) to enhance reasoning capacity. However, due to the inherent heterogeneity in conveying emotions across modalities, these models often suffer from modality imbalance and confront flawed emotion understanding. In this paper, we conduct an in-depth analysis on MER models and uncover two key empirical insights. (i) In MER, modality imbalance manifests two distinct failure modes: unimodal over-reliance and insufficient cross-modal utilization, which call for different intervention strategies. (ii) MLLM layers exhibit implicit functional hierarchies in multimodal emotion processing, playing separable roles in stabilizing unimodal representations and integrating cross-modal information. Motivated by these observations, we propose a Layer-Aware Modality Rebalancing (LAMR) framework by explicitly aligning int

---

### [252] Beyond Modality Preference: Controlling Multimodal Arbitration under Modality Conflict in MLLMs

**链接**: https://arxiv.org/abs/2611.12883
**作者**: Zhaoying Pan, Shenyu Lu, Jun Hui Wong, Junyi Chai, Xiaoqian Wang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) integrate information across modalities, but become unreliable when those modalities disagree. Under conflicting inputs, MLLMs may favor modalities that are not the most reliable for the task, thus motivating inference-time control of modality arbitration. We identify a small set of attention heads, termed arbitration heads, that causally influence whether predictions follow visual or textual evidence. Building on this, we introduce a lightweight, training-free intervention that biases these heads toward a designated trusted modality at inference time. The identified heads are stable across calibration set sizes and generalize across settings, and steering them enables effective bidirectional control of modality reliance across diverse benchmarks. Our findings identify an effective control mechanism to align MLLM predictions with task-specified modality priorities. The code is available at https://github.com/zhaoyingpan/modality-arbitration.

---

### [253] Complementarity-Driven Dual-Teacher Hierarchical Alignment for Zero-Shot EEG-to-Image Retrieval

**链接**: https://arxiv.org/abs/2611.12798
**作者**: Lukun Wu, Jie Li, Ziqi Ren, Ruiyang Xia, Yan Gao, Xinbo Gao
**来源**: cs.CV
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decoding visual information from EEG is central to brain--computer interfaces and brain-inspired intelligence, and contrastive alignment with pretrained vision foundation models (VFMs) has become the dominant paradigm. However, existing methods align EEG solely with CLIP-family VFMs, leaving hierarchical visual information in neural responses under-exploited. To address this gap, we formulate a mechanism-paradigm correspondence view linking hierarchical visual processing (from appearance to semantics) to the complementary biases of cross-paradigm VFMs, with image-only models (e.g., DINO) and image--text models (e.g., CLIP) capturing distinct facets of this hierarchy. Guided by this view, we propose the Dual-Teacher Hierarchical Alignment (DTHA) framework. Concretely, a shared EEG encoder is supervised by frozen multi-blur CLIP and shallow DINOv2 teachers via dual-branch contrastive alignment, so each branch fully supervises the visual cues it emphasizes. A fused-retrieval objective lea

---

### [254] EEGFaceSem: An EEG Benchmark with Paired Generative Latents for Semantic Visual Modeling

**链接**: https://arxiv.org/abs/2611.10781
**作者**: Jun Ma, Michiel M. Spap\'e, Keith M. Davis III, Tuukka Ruotsalo
**来源**: cs.LG
**匹配关键词**: EEG, Brain-Computer Interface
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) is widely used to measure brain activity for brain-computer interface applications for its non-invasive nature and high temporal resolution. However, progress in modeling the neural responses to visual semantics has been limited by a reliance on fixed image collections that lack the fine-grained control needed to isolate fine-grained changes in visual features and their relation to perception. In this work, we present EEGFaceSem, a large-scale dataset pairing high-quality EEG with photorealistic face images synthesized from a generative model. We provide the generative latent vector for each stimulus, enabling research into the continuous mapping between a visual latent space and neural representations. Each participant's brain responses were recorded while they attended to specific semantic features (e.g., smiling, hair color) in a rapid serial visual presentation paradigm. The dataset contains EEG signals from 30 participants, totaling 67,200 time-locked 

---

### [255] MAGE: Towards Generalizable Multi-timescale EEG Representations

**链接**: https://arxiv.org/abs/2611.09928
**作者**: Tuan-Kiet Doan, Van-Chien Nguyen, Trung-Hieu Tran, Quang-Hung Pham, Ngoc-Son Vu, Huy Phan 等 (10 人)
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) data plays an important role in understanding human brain activity, with various major applications. While current approaches, which largely build on EEG foundation models, have demonstrated strong performance across datasets and tasks, they typically rely on a fixed temporal scale. This design choice limits their ability to capture characteristics of neural dynamic behavior, often spanning across multiple timescales, which are naturally captured in EEG recordings. To address this limitation, we propose MAGE (\textbf{Multi-timescale Adaptive Generalization for EEG}), a foundation model that dynamically adapts to capture and integrate information across different timescales. Specifically, MAGE combines two key mechanisms: (i) a novel multi-timescale attention mechanism, capable of learning representations across multiple temporal scales and (ii) a trainable aggregation module, that dynamically identifies and adapts to the most informative timescale of the in

---

### [256] CABrain: A Correlation-Aware Brain Foundation Model for EEG Decoding

**链接**: https://arxiv.org/abs/2611.11782
**作者**: SuGil Choi, Mooseop Kim, Chi Yoon Jeong
**来源**: cs.AI cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) foundation models have emerged as promising paradigms for decoding brain activity through large-scale self-supervised pretraining. Notably, most existing approaches employ masked patch reconstruction, in which randomly selected EEG patches are masked and recovered by the network. However, purely random masking may limit representation learning as informative patches from highly correlated channels often remain unmasked, causing the network to underutilize weakly correlated channels or serial dependencies. Furthermore, because these models are typically based on transformer architectures, their performance is influenced by the choice of positional encoding. Although positional encoding has been extensively explored in natural language processing and computer vision, few studies have adapted it to the unique characteristics of EEG signals. To address these limitations, this study introduces a conditional positional encoding method based on graph convolutional

---

### [257] MambaPD: Bidirectional Selective State Space Model for Parkinson's Disease Detection from Resting-State EEG

**链接**: https://arxiv.org/abs/2611.12026
**作者**: Ayesha Zulfiqar
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Typical diagnosis of Parkinson's disease (PD) occurs only after significant dopaminergic loss, while resting-state EEG abnormalities like alpha slowing and reduced coherence occur earlier. While many published EEG-based PD detectors claim accuracy greater than 95%, many use epoch-level splits which leak subject identity. I introduce MambaPD, a bidirectional selective state space model for resting-state EEG-based PD detection, blending the channel mixing, patch tokenization and bidirectional Mamba encoder. It is compared with four baselines (TCN, BiLSTM with attention, EEGNet and a patch Transformer) in two public datasets (UNM, SanDiego) using subject-independent 5-fold cross-validation (checkpoints were selected on the held-out fold, so absolute estimates are optimistic). On UNM the accuracy is between 0.67 and 0.71, and MambaPD (0.714) is not statistically distinguishable from the Transformer (0.715), and TCN (0.708), with the highest sensitivity (0.82), while the lowest specificity 

---

### [258] PINR-ESI: Physics-Informed Self-Supervised Implicit Neural Representation Framework for EEG Extended-Source Imaging

**链接**: https://arxiv.org/abs/2611.06700
**作者**: Zhiyong Zhou, Sheng Liao, Xiaolin Li, Youshen Xiao, Bin Dai, Surui Liu 等 (7 人)
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [259] Look Closer, Align Better: Explicit Visual Attributes for Robust EEG-to-Image Decoding

**链接**: https://arxiv.org/abs/2611.09123
**作者**: Ke Xiao, Banghua Yang, Wenbin Guo, Fenqi Rong
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [260] L-FAME: Longitudinal Focused Attention Meditation EEG Dataset and Benchmark

**链接**: https://arxiv.org/abs/2605.22893
**作者**: Angqi Li, Ab Basit Rafi Syed, Hamzeh Alzweri, Taosheng Liu, Barry H. Cohen and Saiprasad Ravishankar
**来源**: eess.SP cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [261] ZarrFM: A Canonical Tensor Storage Architecture for EEG Foundation-Model Pretraining

**链接**: https://arxiv.org/abs/2611.11149
**作者**: Dheeraj Chintapalli, Sunkalp Chandra
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Statistical models for brain-computer interfaces (BCIs) increasingly require large, heterogeneous EEG corpora, yet existing datasets vary in sampling rates, channel layouts, window lengths, and storage formats, creating substantial preprocessing and I/O overhead. We propose ZarrFM, an execution-oriented representation that complements BIDS by storing a corpus as a single Zarr v3 hierarchy with indexed metadata, canonical channel spaces, explicit masks, hash-stable subject splits, verified event tables, and block-aligned sharding. On real PhysioNet recordings and synthetic corpora, we compare ZarrFM with EDF, FIF, NPY, HDF5, and Parquet. Across 200 recordings, its two-level index reduces metadata queries from 601 requests to 14. Preserving native signal codes reduces storage from 42.4 MB/hour in EDF to 22.7 MB/hour, while block-aligned sampling reaches 3,131 windows/s, up to 11 times faster than Parquet. Reads remain bit-identical across independent Zarr implementations, and concurrent 

---

### [262] LBSNet: Lightweight Brain State Modeling via Learnable Spectral Prototypes for EEG-Based Fatigue Detection

**链接**: https://arxiv.org/abs/2611.11916
**作者**: Kun Jia, Zhenyu Cao, Hanlin Yu, Zeyuan Li, Yixuan Liu, Zhongye Xia 等 (8 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG-based fatigue detection requires modeling spectral information across bands and its temporal variation. Recent methods combine multi-band modeling with adaptive temporal processing, yet how spectral structure across bands should influence the contribution of each temporal interval remains insufficiently explored. We propose LBSNet, a lightweight network that uses prototype-based brain-state modeling to link local spectral structure with temporal aggregation. LBSNet extracts compact multi-band features through band-specific temporal convolution, shared spatial projections, and cross-band recalibration. Within each window, relative spectral activity is encoded as a normalized descriptor and softly matched to learnable spectral prototypes. Prototype assignments and learned prototype importance jointly determine temporal weights for power aggregation, allowing the spectral pattern of each window to guide its contribution to the prediction. Subject-independent experiments on SEED-VIG an

---

### [263] fNIRSAtlas: A Large-Scale Benchmark for Functional Near-Infrared Spectroscopy Classification

**链接**: https://arxiv.org/abs/2611.10082
**作者**: Kalle M\"akel\"a, Tuukka Ruotsalo
**来源**: cs.LG
**匹配关键词**: Motor Imagery, Motor Execution
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Functional near-infrared spectroscopy (fNIRS) is a promising modality for brain-computer interfaces and cognitive state decoding, but progress in machine learning for fNIRS has been limited by small, isolated datasets and inconsistent evaluation protocols. We introduce fNIRSAtlas, the largest open benchmark for fNIRS classification to date, comprising 23 classification tasks from 19 public data collections, spanning diverse experimental paradigms, including motor execution, motor imagery, mental arithmetic, working memory, and emotion recognition. fNIRSAtlas provides a fully automated pipeline from raw data to evaluation and defines standardized benchmark tasks for both cross-subject and within-subject classification, ensuring reproducible comparison of methods. We evaluate a variety of baseline models from fNIRS and related neuroimaging and time-series machine learning literature on the benchmark. Our results demonstrate that performance varies substantially across tasks and that meth

---

### [264] A Survey of Post-Training in Time Series Foundation Models

**链接**: https://arxiv.org/abs/2607.20002
**作者**: Shifeng Xie, Ambroise Odonnat, Zehao Xiao, Lei Zan, Malik Tiomoko, Lujia Pan 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [265] Informing Acquisition Functions via Foundation Models for Molecular Discovery

**链接**: https://arxiv.org/abs/2512.13935
**作者**: Qi Chen, Fabio Ramos, Al\'an Aspuru-Guzik, Florian Shkurti
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [266] Do Time-Series Foundation Models Forecast Index-Futures Returns? A Preregistered Evaluation of Models, Metrics, and Input Representations

**链接**: https://arxiv.org/abs/2611.12141
**作者**: Rishabh Upadhyay
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We ask whether the apparent forecasting skill of frozen time-series foundation models (TSFMs) on intraday index-futures returns is incremental skill. In a pre-registered evaluation on E-mini Nasdaq-100 (NQ) and E-mini S&P 500 (ES) futures, a common panel of five zero-shot models (Chronos-Bolt, Chronos-2, TimesFM 2.5, Moirai 2.0 and TiRex), plus separate experiments with Kronos, is compared with a no-change forecast at 5-120 minutes, using native prices, log returns, volatility-standardised returns and a volume clock as inputs. On a blind set opened once, 0 of 160 model-representation-horizon-market cells beat no-change, and a Hansen SPA test gives p = 1.000 on both markets; a later retrospective hold-out, scored as a descriptive check, gives 0 of 120. Input representations change forecast magnitude but not accuracy, and a transformation-aware ridge regression does as well. Several standard measures nevertheless suggest skill. Price-level correlation exceeds 0.9996, but no-change scores

---

### [267] REFORM-3D: A Representation-Centric Evaluation Framework for 3D Medical Vision Foundation Models

**链接**: https://arxiv.org/abs/2611.10062
**作者**: Maregu Assefa, Muzammal Naseer, Divya Velayudhan, Gedamu Alemu Kumie, Naoufel Werghi
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation of 3D medical foundation models is typically dominated by downstream task scores, which entangle representation quality with adaptation choices. This is especially critical in volumetric imaging, where spacing and anisotropy can substantially alter image statistics while the anatomy itself remains unchanged. We therefore introduce \textbf{REFORM-3D}, a \textbf{R}epresentation-centric \textbf{E}valuation \textbf{F}ramew\textbf{OR}k for benchmarking frozen 3D medical vision foundation \textbf{M}odels across three questions: Acquisition Robustness, asking whether features remain stable when spacing varies while anatomy is fixed; Cross-Modal Anatomical Alignment, asking whether labeled anatomical structures remain recoverable across modalities under balanced bidirectional retrieval; and Anatomical Transfer, asking whether organ identity remains recoverable from limited labeled support under case-disjoint evaluation. These are also pretraining questions, because what a 3D encoder

---

### [268] NeuroRVQ: Multi-Scale Biosignal Tokenization for Generative Foundation Models

**链接**: https://arxiv.org/abs/2510.13068
**作者**: Konstantinos Barmpas, Na Lee, Dimitrios Chalatsis, William Raftery, Yannis Panagakis, Dimitrios A. Adamos 等 (10 人)
**来源**: cs.LG cs.AI cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [269] RAD-TFM: Robust and Domain-Adapted Tabular Foundation Models

**链接**: https://arxiv.org/abs/2611.10230
**作者**: Matthew Peroni, Franck Le, Vadim Sheinin
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The development of tabular foundation models (TFMs) has accelerated in recent years, outperforming traditional ML methods on many tabular benchmarks. A key finding is that TFMs can be pretrained entirely on synthetic datasets, opening opportunities to design data generators that encourage desirable model properties. Prior work has mainly focused on crafting high-quality priors over generators to improve overall pretraining performance. Our key insight is that parameterizing the generator distribution enables an adversarial, distributional robustness perspective: during training, we can adapt the generator to emphasize datasets that are particularly challenging for the model, which we formalize by introducing an optimality gap measure. Further, we develop a method to align the synthetic data generation with real-world datasets from a given domain, constraining the adversary to generate realistic data. Together, these algorithms comprise the Robust and Domain-Adapted Tabular Foundation M

---

### [270] Benchmarking CNNs, Vision Transformers, and Foundation Models for Explainable Brain Tumor MRI Classification: Calibration, Decision Analysis, and External Validation

**链接**: https://arxiv.org/abs/2611.11793
**作者**: Akwasi Asare
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning models for brain tumor MRI classification are usually compared by accuracy alone, on public datasets whose independence is rarely checked. We benchmarked six architectures: two convolutional networks (EfficientNetV2-M and ConvNeXt-V2-Tiny), two vision transformers (Swin-V2-S and ViT-L/16), and two foundation models (DINOv2-L and MedSigLIP-448), for four-class classification of 7,216 public MRI images. We assessed accuracy, calibration, explainability, ensembles, and decision curves, with every fitted quantity estimated on validation data only. Pixel-verified duplicate screening showed that 36% of the test images had a near-duplicate in the training data. Test accuracy ranged from 94.5% to 95.6%, with no pairwise difference after Holm correction, and fell to 90.3% to 91.7% on the 773 test images free of duplicates and shared patients. Ensembles did not outperform the best single model. Attribution maps passed a model-randomization test but localized expert-annotated tumors

---

### [271] A forensic evaluation framework for egocentric foundation models: an EFM3D case study for crime scene reconstruction

**链接**: https://arxiv.org/abs/2611.12259
**作者**: Davidson Chisom Onwubiko, Shahana Bano, and Carlos Francisco Moreno-Garc\'ia
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models increasingly combine geometry, semantics, and spatial context for three-dimensional scene understanding, but their suitability for forensic crime scene reconstruction remains unclear. This study presents a structured forensic evaluation framework for egocentric foundation models and demonstrates it using the Egocentric Foundation Model for 3D (EFM3D). Four simulated indoor crime scenes were recorded with Meta Project Aria Gen~1 at Robert Gordon University's East Lodge House forensic training facility. The framework evaluates room-scale reconstruction, semantic scene understanding, computational performance, and forensic suitability. Across the four scenes, EFM3D generated meshes averaging $12{,}668\pm2{,}430$ vertices and $24{,}838\pm4{,}903$ faces, with 39,529 recorded semantic predictions spanning 21--24 categories at a mean confidence of 0.40. Because reference meshes and expert-labelled 3D ground truth were unavailable, these statistics are treated as descriptive 

---

### [272] Simple models outperform single-cell foundation models on downstream benchmarks

**链接**: https://arxiv.org/abs/2602.16696
**作者**: Huan Souza, Pankaj Mehta
**来源**: q-bio.GN cs.LG q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [273] Out-of-the-Box Tabular Foundation Models for Bayesian Optimization in Materials Discovery

**链接**: https://arxiv.org/abs/2611.12491
**作者**: Klemens Fl\"oge, Simon Bing, Leo Grinsztajn, Eliott Kalfon, Lennart Purucker, Noah Hollmann 等 (7 人)
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bayesian optimization is widely used in active learning loops for materials science. Gaussian processes serve as the de-facto surrogate model family, but require task-dependent kernel choices and can lack the modeling capacity for complex relationships. Tabular foundation models (TFMs) have recently emerged as the state-of-the-art for predictive tasks on structured data, without requiring bespoke kernels or hyperparameter tuning. We evaluate two TFMs, TabPFN and TabICL, as out-of-the-box surrogate models on two standard materials science benchmarks, comparing against a large field of baselines encompassing Gaussian processes, random forests, and CatBoost. Our findings indicate that TFMs are highly competitive surrogate models across the two benchmarks, without task-specific training for active learning or GP kernel selection. Our results motivate developing TFMs further as surrogates for active learning in materials discovery.

---

### [274] Calibrating Scientific Foundation Models with Inference-Time Stochastic Attention

**链接**: https://arxiv.org/abs/2604.19530
**作者**: Akash Yadav and Taiwo A. Adebiyi and Ruda Zhang
**来源**: cs.LG cs.CE stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [275] Learning Biological Hierarchies in Single-Cell Foundation Models

**链接**: https://arxiv.org/abs/2611.10838
**作者**: Xiangyu Guo, Ricardo Henao
**来源**: cs.LG cs.AI q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cell types are organized by taxonomic relationships that define lineages in the so-called cell ontology. However, most existing foundation models typically ignore cell-type lineages encoded in this cell ontology. We introduce a biologically informed foundation model called scOntoFM, which embeds hierarchical cell ontology into representation learning. Using Lowest Common Ancestor (LCA) distances from the ontology graph, our framework pairs efficient offline triplet sampling with hierarchical cell-ontology learning. This approach jointly preserves local neighborhoods and shapes the global embedding geometry to reflect the ontology structure. Across diverse cell- and gene-level benchmarks, the model consistently improves performance, with especially strong gains in zero-shot settings. Our model also balances batch integration with biological structure preservation, providing complementary perspectives to existing embedding evaluation frameworks and supporting scalable biological discover

---

### [276] An Evaluation of Tabular Foundation Models as Training-Free World Models

**链接**: https://arxiv.org/abs/2611.11921
**作者**: Xian Yeow Lee, Ryoichi Takase, Ahmed Farahat
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> World models are widely considered to be a potential key component of model-based reinforcement learning and robot planning, but typically require task-specific training on substantial interaction data. We investigate whether a pretrained tabular foundation model (TabFM) can serve as a training-free dynamics model for world modeling by framing next-state prediction as in-context regression over transition pairs, and where such a model helps and where it breaks. Across synthetic dynamical systems and robot locomotion benchmarks, TabFM is more accurate than LSTM and MLP models trained from scratch on the same limited transitions in almost all settings, and among regressors fitted to the same data it is the most accurate on locomotion, while a Gaussian process is more accurate on smooth low-dimensional systems. However, models trained on the full dataset remain substantially better on most systems. When rolled out autoregressively over multiple steps, TabFM's accuracy depends strongly on 

---

### [277] Prediction with Foundation Models under Deployment Budgets

**链接**: https://arxiv.org/abs/2611.12466
**作者**: Zhaohui Xu, Xiaofei Xu, Doudou Zhou
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models can supply predictions for a downstream task that draw on knowledge from extensive pretraining, but they differ in task-specific accuracy and query cost. We develop a framework that improves prediction for the task under a budget on the average query cost per input, using training data to learn which models to query and how to combine their outputs with features available without querying. The first method queries the same models for every input; the second lets them vary across inputs and uses Q-learning to decide which model to query next and when to stop. For the first method, we show that several individually inaccurate outputs can jointly outperform the best single one. It attains the minimax rate when the regression function depends on the outputs only through models within the budget. Otherwise, any method within the budget can be forced to a slower rate, which the first method attains. For the second method, we show when varying the queried models across input

---

### [278] Can Time Series Foundation Models Serve as Surrogates for Power Systems Dynamic Simulation?

**链接**: https://arxiv.org/abs/2611.10247
**作者**: Sandy Miguel, Bruno Paes Leao, Cheng Feng
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-fidelity dynamic simulation is essential for scientific and engineering applications, but its computational cost limits large-scale scenario screening. We investigate the use of pretrained time-series foundation models (TSFMs) as computationally efficient surrogates to address this limitation. In-context learning and post-training strategies, including retrieval-augmented reference sample selection and physics-informed regularization, are considered in the investigation. Results are benchmarked against a traditional AI model representative of the state-of-the-art in the domain. Experiments using an open-source TSFM and data from a simulated 9-bus power system indicate promising results. Retrieval augmentation improves in-context learning performance, and fine-tuning leads to superior results compared to the traditional AI model, especially when including physics-informed regularization. The fine-tuned TSFMs achieve lower errors and improved computational costs compared to the trad

---

### [279] Nanopath: Fast, Fair, Open Experimentation for Pathology Foundation Models

**链接**: https://arxiv.org/abs/2611.10014
**作者**: Paul S. Scotti, Hassan Muhammad, Ryan Kim, Nima Ashjaee, Ratna Sagari Grandhi, Saman Rahbar 等 (10 人)
**来源**: cs.CV q-bio.TO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce nanopath, an open-source framework and benchmark for rapidly training and evaluating small-scale pathology foundation models. Using a single H100 GPU, a typical nanopath model trains in a little over an hour on up to one million TCGA pathology tile presentations and evaluates within 25 minutes on a broad suite of tile-level and slide-level tasks. Nanopath enables rapid exploration of research ideas at small scale, so promising training recipes can subsequently be tested with more data and compute. To enable fair comparisons between ideas, we constrain submissions to fixed data and compute budgets while keeping the downstream evaluation protocol fixed. Anyone may clone the codebase, automatically download the data, reproduce or modify existing models, and submit a run to Labless, our public experiment ledger where researchers and AI agents can search through prior attempts. Since its public release in June 2026, nanopath has received 1,269 experiments from 20 contributors. 

---

### [280] Does Predictive Performance Translate to Causal Performance? Evaluating tabular foundation models as nuisance learners for causal effect estimation

**链接**: https://arxiv.org/abs/2611.11381
**作者**: Andrew R Weckstein, Issa J Dahabreh, Marinka Zitnik, Sonia Hern\'andez-D\'iaz, Sebastian Schneeweiss
**来源**: stat.AP cs.AI cs.LG stat.ME stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models based on prior-data fitted networks (PFNs) achieve strong predictive performance, but their value for causal inference is unclear. We evaluated whether PFNs, which predict through in-context learning, could match or outperform conventional nuisance learners in supporting accurate causal estimation and reliable uncertainty quantification (inference). Learners modeled propensity scores and outcome regressions within doubly robust estimators of average causal effects, with and without cross-fitting, across synthetic and semi-synthetic settings with varying confounding complexity and effect heterogeneity. Under simple parametric data-generating processes, the PFNs were competitive with correctly specified parametric regressions and ensembles containing them. In more complex settings, they outperformed all conventional learners evaluated, including richly specified Super Learner ensembles, for both accuracy and uncertainty quantification. As sample size increased, 

---

### [281] CHANNELS4WORLD: An Environment-Scale Dataset for Wireless Foundation Models

**链接**: https://arxiv.org/abs/2611.11428
**作者**: Joonkyu Jang, Hyung-Joo Moon, Kwang Soon Kim, Seong-Lyun Kim, Jakob Hoydis, Robert W. Heath 等 (8 人)
**来源**: cs.LG cs.IT eess.SP math.IT
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wireless foundation models learn reusable representations across tasks, configurations, and deployment environments. Their pretraining requires environmental breadth, yet wireless datasets often sample few sites densely. We introduce Channels4World, a scene-centered dataset of 100,000 distinct outdoor RF scenes and a procedural method for generating them. Each scene links a generated environment and RF material assignments to 32 base-station (BS) positions, 16,384 UE positions, and aligned variable-length multipath and ordered interaction records at 3.5 and 7~GHz. The corpus comprises 52.43 billion physical BS-UE pairs, 104.86 billion frequency-specific evaluations, and a 29.14-TB packaged payload. Scene identity aligns geometry, placements, channels, and interactions across frequencies, allowing environmental breadth and within-scene observation density to vary independently. The public release offers predefined subsets at multiple scales and separate access to corpus components. A de

---

### [282] FFM-CP: Cross-Backbone Fusion of Vision-Language Foundation Models for Few-Shot Computational Pathology

**链接**: https://arxiv.org/abs/2609.27710
**作者**: Anh-Tien Nguyen, Trung Dang, Nghiem Tuong Diep, Bui Ngoc Han Nguyen, Tan-Ha Mai, Miriam Cindy Maurer 等 (10 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [283] Means vs. Foundation Models for Emergency Call Forecasting

**链接**: https://arxiv.org/abs/2611.11656
**作者**: Feriel Fass, Djemel Ziou, and Marie-Flavie Auclair-Fortier
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study investigates whether generalized means can achieve forecasting performance comparable to that of TimeGPT for daily emergency call volume prediction. Specifically, two families of generalized means, the H\"older means (HM) and the Lehmer means (LM), are evaluated against fine-tuned TimeGPT across forecasting horizons ranging from one to seven days. Forecasting performance is assessed on a real-world emergency call dataset using multiple error metrics, and Diebold-Mariano test. Experimental results show that HM and LM achieve nearly identical predictive performance across all forecasting horizons. For short-term forecasting, both generalized means outperform TimeGPT, with reductions of mean absolute error (MAE) approximately 1.24\% and 2.48\% at horizons of one and three days, respectively. Conversely, TimeGPT achieves a lower error at the seven-day horizon, with an descresing of MAE by 1.98\%. However, Diebold-Mariano tests reveal no statistically significant differences betw

---

### [284] BAPLe++: Cross-Model Transferability and Prompt-Level Defense of Backdoors in Medical Foundation Models

**链接**: https://arxiv.org/abs/2611.10764
**作者**: Ufaq Khan, Umair Nawaz, Satyajit Tourani, Awais Rauf, Fahad Shamshad, Asif Hanif 等 (9 人)
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical foundation models (Med-FMs) are increasingly adapted to clinical tasks through prompt learning, which tunes a small set of prompt tokens while the backbone remains frozen. Recent work has shown that this efficiency introduces a vulnerability: jointly optimizing learnable prompts and an imperceptible noise trigger during few-shot adaptation implants a backdoor that leaves clean performance intact but steers triggered inputs to an attacker-chosen class. Since prompts are compact and readily shared, this raises two questions: whether a backdoored prompt remains effective on a different Med-FM, and whether it can be repaired without retraining the backbone. We address both in BAPLe++. First, we present the first study of cross-model transferability of prompt-based backdoors, quantified by two proposed metrics, Clean Accuracy Difference (CAD) and Backdoor Accuracy Difference (BAD). Second, we propose DePLe (Defense via Prompt Learning), which uses the infected prompt as a fixed anch

---

### [285] PoseBench: Probing Pose Awareness in Visual Foundation Models

**链接**: https://arxiv.org/abs/2611.10347
**作者**: Most Nilufa Yeasmin, Draix Wyatt, Ruyi Lian
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pose awareness characterizes the extent to which a learned feature space aligns with the underlying object-pose manifold, such that observations with similar poses exhibit greater feature similarity than those with increasingly different poses. While such structure is desirable for pose-sensitive 3D vision tasks, visual foundation models pre-trained on individual 2D images typically lack explicit 3D or pose supervision. This raises a fundamental question: Do 2D visual foundation models exhibit pose awareness after large-scale pretraining? To answer this question, we introduce PoseBench, a systematic benchmark to probe pose awareness in pretrained visual features. Our evaluation follows a progressive design: held-out rendered views probe intrinsic pose-aware structure under controlled conditions, while real-image queries evaluate how robustly this structure remains accessible under real-world variations. We further introduce pose-graph-based refinement as a complementary probe of compat

---

### [286] Contrastive fine-tuning against stain and scanner bias improves robustness and downstream performance across pathology foundation models

**链接**: https://arxiv.org/abs/2611.10093
**作者**: Ryan Kim, Hassan Muhammad, Anish Dulal, Paul S. Scotti, Tanishq Mathew Abraham
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Histopathology foundation models achieve strong performance across diverse downstream tasks, yet their representations have been shown to encode scanner- and site-specific biases, creating generalization gaps and potentially limiting real-world utility. We introduce SPECTRA (Scanner and Pathology Embedding Contrastive Tuning for Robust Alignment), a model-agnostic contrastive learning post-training framework which explicitly encourages scanner- and stain-robust representations, to optimize performance and generalization on downstream applications. Using parameter-efficient LoRA adapters trained on matched multi-scanner and multi-stain whole-slide images sourced from the PLISM dataset, our method aligns spatially corresponding regions across acquisition conditions (scanner, stain), using other locations within each candidate condition as negatives. SPECTRA improved PathoROB robustness index, gene-expression prediction on HEST, slide-level classification AUC on CPTAC, and held-out PLISM 

---

### [287] Who Needs Labels? Adapting Vision Foundation Models With the Metadata You Already Have

**链接**: https://arxiv.org/abs/2606.05107
**作者**: Elouan Gard\`es, Seung Eun Yi, Kartik Ahuja, Th\'eo Moutakanni, Huy V. Vo, Piotr Bojanowski 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [288] PromptShift-CRC: What Drift-Aware Weighting Adds to Online Conformal Risk Control for Foundation Models

**链接**: https://arxiv.org/abs/2606.15964
**作者**: Jeffery Opoku and David Banahene
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [289] Data-informed Adaptation of Foundation Models for Causal Effect Estimation

**链接**: https://arxiv.org/abs/2611.11504
**作者**: Chunwei Ma, Russell D Wolfinger
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Due to the fundamental problem of causal inference -- the impossibility of observing counterfactual outcomes -- there is always a gap between the training goal (outcome, propensity) and the inference target (CATE, ATE). Traditional causal effect estimation revolves around setting assumptions, selecting identification strategies, and choosing causal estimators, while more recently, Causal Foundation Models (CFMs), built on Prior-Data-Fitted Networks (PFNs), ease this process by pretraining on massive synthetic prior datasets. Despite their success, such amortization makes causal inference less transparent, obscuring which assumptions the model implicitly relies on for a given dataset. The high diversity of real-world data-generating processes (DGPs) and Structural Causal Models (SCMs) makes it hard to know, a priori, which causal inference strategy is compatible with a given dataset. In this work, we focus on this compatibility between an observational dataset and method-specific assump

---

### [290] CONSTRAINER: Promptable Graph-Structured Optimization via Constraint Conditioning

**链接**: https://arxiv.org/abs/2611.10627
**作者**: Zeeshan Memon, Mingke Tian, Xinyuan Song, Hongwei Jin, Kibaek Kim, Liang Zhao
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neural methods for graph-structured optimization have achieved strong performance within individual problem classes, but are typically trained for fixed formulations, limiting reuse across related problem variants. Recent progress in foundation models has motivated shared neural backbones trained across multiple graph-structured optimization tasks; however, existing approaches primarily share instance-level representations while treating feasibility constraints implicitly. A key source of shared structure across constrained optimization problems is the constraint set itself, which often exhibits substantial overlap across tasks. We propose CONSTRAINER, a constraint-conditioned framework for graph-structured optimization that treats constraints as structured inputs. Constraint specifications are parsed into operator graphs and encoded using a graph neural network to produce invariant constraint embeddings, which condition a shared backbone model for solution prediction. We evaluate our 

---

### [291] VLA Adaptation with Real and Simulated Data: A Case Study on Robotic Chess

**链接**: https://arxiv.org/abs/2611.12676
**作者**: Mat\v{e}j Kripner, Milan Straka
**来源**: cs.RO cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language-action (VLA) models are trained as general-purpose foundation models for robot learning, and require fine-tuning for each downstream task and robot. This raises practical questions such as how much data and training updates are needed, how checkpoints should be selected, and whether simulation can be leveraged to alleviate the cost of real data collection. We study these questions on a task that requires both precise manipulation and spatial understanding of the scene. In this task, an SO-101 arm moves a chess king between two squares that are given only by their names, such as e4 and a5. We fine-tune $\pi_{0.5}$ with various dataset sizes and update budgets, using teleoperated demonstrations as well as simulated demonstrations from a randomized scripted expert that imitates the variability of human demonstrations. In simulation, the success rate scales with both data and updates. Importantly, we find that a short learning-rate cool-down adds up to 31 points and is nece

---

### [292] Toward a theory of Evaluability

**链接**: https://arxiv.org/abs/2611.10996
**作者**: Kunal Talwar
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning models, particularly large foundation models, are increasingly evaluated along multiple axes that are relevant for their usage. In addition to accuracy measures appropriate for the specific task of interest, measures capturing safety, calibration and fairness properties are often of interest. The classical approach to these problems assumes that the test set has been held out from the training process, an assumption that is increasingly harder to justify for large foundation models. In this work, we formalize a notion of evaluability without this assumption, and ask if it is feasible to evaluate black-box models in settings where our test samples may have been used during training. We study this problem under different settings, capturing different levels of access to the model. We first study the natural setting, where the evaluator only looks at the output of the model on the test set. We fully characterize the class of distributions where accurate evaluation is poss

---

### [293] UniHam: A Large-Scale SOC-Complete Dataset and Benchmark for Hamiltonian Learning in Materials

**链接**: https://arxiv.org/abs/2611.12509
**作者**: Yuewen Huang, Pin Chen, Yutong Lu
**来源**: cs.LG cond-mat.mtrl-sci
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate prediction of electronic Hamiltonians would enable broad property inference while avoiding the high computational cost of Density Functional Theory (DFT). However, progress toward general-purpose materials foundation models is limited by a data bottleneck: existing Hamiltonian datasets are typically small, lack structural diversity, and often omit essential relativistic physics such as spin--orbit coupling (SOC). We therefore construct UniHam, a large-scale Hamiltonian dataset and benchmark suite comprising 100,000+ DFT-computed complex-valued Hermitian Hamiltonians with full SOC, covering 72 elements and a wide range of crystal geometries and symmetries (spanning diverse lattice types and space-group families). Building on UniHam, we benchmark two representative state-of-the-art models under a standardized protocol and introduce complementary evaluation metrics that jointly assess three dimensions: (i) Hamiltonian reconstruction accuracy, (ii) out-of-distribution (OOD) genera

---

### [294] Probing Transformer Representations Layer by Layer, Module by Module

**链接**: https://arxiv.org/abs/2611.11531
**作者**: Ambroise Odonnat and Theo Gnassounou and Laetitia Chapel and Romain Tavenard and Ievgen Redko
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Which representation should be probed in a transformer-based foundation model? Recent work shows that the standard practice of probing the final layer is often suboptimal, as intermediate layers can provide better features. Yet, representations are still largely studied along depth alone, treating each transformer block as an atomic unit. In this work, we analyze transformer representations layer by layer, module by module. Through more than 144,000 linear probing evaluations of vision foundation models (VFMs) and large language models (LLMs), we show that layer and module choices should be considered jointly: the best layer-module pair yields substantially larger gains over the final-layer residual stream than the best layer with the residual stream fixed. Moreover, module performance can vary substantially across layers, showing that useful representations cannot be characterized by depth alone. Building on these findings, we evaluate simple fixed probing strategies: the final-layer 

---

### [295] Target Recoverability under Selective Labels: A Failure Mode in ECG-Based Acute Coronary Syndrome Prediction

**链接**: https://arxiv.org/abs/2611.11063
**作者**: Alexander Schubert, Anton H{\aa}kansson, Ziad Obermeyer
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical machine learning models often learn from diagnoses observed only in patients clinicians chose to test. The biases of such selective labels are well known, but less understood is what happens when a diagnosis includes cases the model's inputs cannot detect. Because testing decisions draw on information the model does not see, these cases can appear predictable among tested patients, producing relationships that fail, and can even reverse, among the untested. We formalize this mechanism and show in simulations that it worsens as testing becomes more selective or undetectable cases more common, while models trained only on detectable cases remain informative. We empirically study electrocardiogram (ECG)-based prediction of acute coronary syndrome (ACS), which is confirmed only by invasive testing and whose subtypes differ in how clearly they appear on the ECG. Three ECG foundation models fine-tuned on revascularization, our ACS proxy, performed well among catheterized patients (AU

---

### [296] Optimized Car Damage Detection Using CNN and Object Detection Model

**链接**: https://arxiv.org/abs/2611.10001
**作者**: Sania Ejaz, Jaison Shajan Thomas, Zaheeruddin Ahmed, Sushma Hans
**来源**: cs.CV cs.LG
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Car damage detection systems play a vital role in scenarios, like the insurance claims process, accident reporting systems, or a documented write-up of the various damages a vehicle in a car garage exhibits upon entry and exit. This paper presents a two-fold model architecture encompassing a convolutional neural network used to classify the collected input samples as clear or damaged, thereby filtering out the undamaged images, before the input is passed on to the object detection layer for further localization and classification of defects into Scratch, Dent, Glass Shatter, and Smash. A deviation from the focus of related work, this paper poses the use of unified models while applying transfer learning techniques to augment performance that caters to multiple use cases. The design of this model has been made to optimize performance by incorporating the two models to streamline the processing of input samples. The model boasts significant performance with accuracies of 98% for the CNN 

---

### [297] Not All Layers Are Equal in Image-to-Video Transfer

**链接**: https://arxiv.org/abs/2611.11147
**作者**: Thinesh Thiyakesan Ponbagavathi, Constantin Seibold, Alina Roitberg
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Parameter-efficient image-to-video transfer adapts frozen image foundation models to video via lightweight trainable adapters. Existing methods insert the same adapter at every transformer layer, implicitly assuming all layers require equal temporal modeling. A layer-wise sensitivity analysis across four video-native model families and two pretraining paradigms reveals that this assumption is wrong: temporal sensitivity increases with depth, and the pretraining paradigm determines its growth profile. Vision-only models exhibit a gradual rise, while vision-language models show early suppression followed by late recovery. This finding motivates STRAP, a training-free adapter placement rule that derives a spatial-to-temporal transition boundary from a paradigm-matched video model. Spatial adapters are assigned before this boundary and temporal adapters after it, without modifying the adapter architecture itself. On four fine-grained action recognition benchmarks, STRAP improves accuracy b

---

### [298] A Systematic Comparison of In-Context Learning Strategies for Peptide Property Prediction in Low-Data Regimes

**链接**: https://arxiv.org/abs/2611.09994
**作者**: Jiantao Zhao, Andrei Voinea, Mathijs F.J. Mabesoone
**来源**: physics.chem-ph cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peptide sequence-property relationships are often highly non-linear, but can be learned with machine learning models and exploited for the design of new materials and bioactive compounds. Various methods based on transformer architectures have become available for molecular property predictions. These foundation models promise straightforward inference and prediction of properties of new materials through in-context learning. Benchmarks of individual model architectures exist, but a systematic comparison of various foundation models against classical baselines on similar datasets is lacking. Here, we provide a systematic evaluation of the predictive performance of various in-context learning strategies. We compare several large language models, tabular foundation models, and typed decision models against an XGBoost baseline. We evaluate predictive performance on binary and multiclass classification tasks on pH-dependent surface activ-ity, IR spectral signatures, self-assembly, and anti

---

### [299] SPARK: Simple Post-training for Adapting pRetrained Knowledge to Robot Control

**链接**: https://arxiv.org/abs/2611.12102
**作者**: Taekyung Kim, Jeongeun Park, Byeongho Heo, Sungjoon Choi, Sangdoo Yun, Dongyoon Han
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale representation learning has produced public foundation models that provide strong general-purpose visual features. However, their pretraining objectives are not designed for robot representation learning, so the resulting embeddings tend to emphasize global semantics rather than the temporally sensitive representations required for robot control. Training robot models from scratch is also undesirable due to the limited scale and high collection cost of robotics data, as well as the substantial computational burden of pre-training. In this paper, we propose SPARK (Simple Post-training for Adapting pRetrained Knowledge), a post-training method that adapts foundation models to robot control. SPARK is built on two principles: temporal abstraction, which encourages the encoder to derive compact features that preserve information essential for understanding temporal changes and action-relevant scene structure, and knowledge preservation, which aligns patch-level representations w

---

### [300] Representation Learning for 3D Brain Imaging: A Benchmark

**链接**: https://arxiv.org/abs/2611.10007
**作者**: Pierre Falconnier (MYRIAD), Robin Trombetta (MYRIAD), Nicolas Duchateau (MYRIAD), Carole Lartizien (MYRIAD)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many deep learning architectures for computer vision tasks rely on features extracted by a pre-trained encoder on large databases of natural 2D RGB images. However, the wide domain gap with medical images hampers the direct transfer of optimized deep learning models from computer vision to clinical applications. Recently, self-supervised pre-training and foundation models emerged as promising alternatives to mitigate these limitations. Yet, constructing such models for medical imaging faces critical challenges, including designing and adapting training strategies for large 3D volume datasets, and the need for standardized benchmarks to evaluate feature extraction performance. In this study, we propose an extensive comparison of vision encoders with a focus on 3D brain MRI. First, we consider 8 fully and self-supervised models pretrained on natural images (e.g. ResNet, DINO, CLIP) and 10 backbone architectures trained on medical images, either based on supervised (e.g. RadImageNet) or s

---

### [301] National-Scale Crop Type Mapping in Morocco Using Google AlphaEarth Foundations Embeddings and the Fields of the World Field Boundary Map

**链接**: https://arxiv.org/abs/2611.12681
**作者**: Walid Elbarz, Mohamed Bourriz, Vincent Simonneaux, Hamd Ait Abdelali, Fran\c{c}ois Bourzeix
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent geospatial foundation models have introduced a new paradigm for large-scale Earth observation by providing pretrained embedding representations that can be directly exploited for downstream tasks. In this work, we investigate the use of Google AlphaEarth Foundations embeddings for national-scale crop type mapping in Morocco. The proposed workflow operates directly on publicly available 64-dimensional pretrained embeddings using lightweight downstream classifiers, eliminating the need to process raw satellite imagery during model training and inference. The approach targets three crop categories, namely winter cereals, tree crops, and other crops. For nationwide inference, the Fields of the World global field boundary map is used to constrain predictions to agricultural parcels, enabling efficient large-scale mapping. Experimental evaluation on an independent test set over ten repeated runs achieved an average classification accuracy of (87.17 +/- 0.42%). Nationwide inference ove

---

### [302] MICE: Multi-animal Interaction Context Encoder - A Hierarchical Foundation Model for Mouse Behavior

**链接**: https://arxiv.org/abs/2611.11644
**作者**: Yen-Shuo Su, Weihan Li, Anqi Wu
**来源**: cs.CV cs.LG q-bio.NC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantifying mouse behavior from pose is a foundational tool in neuroscience, ethology, drug discovery, and animal welfare. Self-supervised foundation models are a natural fit, but a foundation model for mouse behavior must handle social behavior - many behaviors that matter (aggression, courtship, mounting, allogrooming) are inherently multi-animal. Existing self-supervised pose models fall short: they encode each animal independently and discard interaction signal, hard-code the animal count, and pretrain one dataset at a time. We introduce MICE (Multi-animal Interaction Context Encoder), a hierarchical foundation model for mouse behavior that pretrains jointly on six mouse-pose corpora spanning one to four mice and 7 to 27 keypoints. MICE combines a hierarchical individual encoder capturing per-mouse kinematics at multiple temporal scales with a Perceiver-style social encoder whose learned latent codebook decouples parameter count from animal count, so a single checkpoint serves any 

---

### [303] PACE-ECG: Patient-Aware Contrastive ECG Pretraining; Leveraging Longitudinal Structure for Transferable Representations

**链接**: https://arxiv.org/abs/2611.12307
**作者**: Riccardo Cavarra, Lupo Lovatelli, Shaheim Ogbomo-Harmitt, Jakub Grzelak, Adelaide De Vecchi, Andrew King 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models for physiological signals are commonly evaluated on in-domain interpretation tasks, but their ability to transfer to longitudinal clinical prognosis across healthcare systems remains uncertain. We developed PACE-ECG, an ECG pretraining framework that combines contrastive learning across temporally neighbouring recordings from the same patient with clinically guided multitask supervision. We evaluated frozen ECG representations for post-myocardial-infarction all-cause mortality and incident heart failure prediction across MIMIC-IV and two external HEEDB cohorts, comparing the proposed representation with DeepECG-SSL, a state-of-the-art model, and two control baselines. Across both downstream tasks, the proposed model outperformed DeepECG-SSL in-domain (AUROC +1.9% for mortality and +4.0% for heart failure) and on external populations in HEEDB-Boston (+5.6% for mortality +10.3% for heart failure) and HEEDB-Atlanta (+6.9% for mortality +11.0% for heart failure) while usi

---

### [304] Map2SLAM: From Streaming Map Prediction to Real-Time SLAM

**链接**: https://arxiv.org/abs/2611.11169
**作者**: Jian Gao, Lin-Zhuo Chen, Yihang Chen, Jiagang Chen, Jiacheng Dong, Xun Cao 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Streaming 3D foundation models (3DFMs) estimate camera poses and dense geometry online, but they fall short of SLAM: their predictions are fixed once emitted, so loop closures cannot correct accumulated drift. With such models already providing strong geometric capability, a central question for SLAM becomes how to schedule their inference and how to keep its results as revisable state. We present Map2SLAM, which keeps LingBot-Map frozen, trains only a lightweight retrieval head, and builds SLAM on the model's inference interface, turning its predictions into observations of an external persistent SLAM state. The front-end tracks every incoming frame with the model's causal streaming inference and decides which frames are written to the persistent state as keyframes. The back-end asynchronously decides when and which past frames to re-observe, re-running the model's joint inference over them with fresh context; verified loop observations correct the trajectory online, and segment obser

---

### [305] Virtual Task Prompting for Multi-Task Scene Understanding

**链接**: https://arxiv.org/abs/2611.11041
**作者**: Zedong Wang, Yucheng Wang, Dan Xu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-task scene understanding models typically rely on modified vision encoders or complex decoders for cross-task interaction, which limits their flexibility and compatibility with off-the-shelf vision foundation models (VFMs). We introduce Virtual Task Prompting (VTP), which frames multi-task prompting as retrieving task-adaptive compositions from a shared virtual state, where both the state and routing process are optimized in an end-to-end manner. Concretely, VTP maintains an expanded set of virtual tasks alongside the backbone. At each layer, learnable routing matrices read task-specific compositions as input to interact with image tokens and write the processed results back, forming explicit pathways that capture the intricacies among tasks outside the encoder. Since VTP keeps the backbone clean, it integrates seamlessly with pretrained VFMs, advancing the state of the art on Pascal-Context and NYUD-v2. Stress test on Taskonomy with 13 heterogeneous tasks further shows VTP's rob

---

### [306] Meta-Reinforcement Learning with Zero-Shot Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.10553
**作者**: Jake Grigsby, Siddhant Agarwal, Yu Lei, Leonidas Varveropoulos, Yuke Zhu
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Meta-reinforcement learning (meta-RL) trains agents to adapt to novel tasks from test-time experience, but requires diverse training environments and reward functions. While environments are becoming cheaper to generate, it remains difficult to anticipate every objective an agent may be asked to pursue at test time. Behavior Foundation Models (BFMs) learn policies from reward-free data and support zero-shot RL (ZSRL): adaptation to new objectives at test time using a large reward-labeled dataset. Recent work has shown that BFM task inference can instead be performed online without prior task-specific data. We note that this capability positions BFMs and meta-RL as alternative approaches for online adaptation to new reward functions in a fixed environment. We then ask whether we can extend BFMs to compete with meta-RL more broadly, including in novel environments, and identify four challenges: environment identification, online data collection, test-time exploration, and learning from m

---

### [307] AmodalBox: Automated 3D Bounding Box Annotation under Partial Visibility

**链接**: https://arxiv.org/abs/2611.10821
**作者**: In-Jae Lee, Namtae Kim, Robert Exley, Kwonyoung Ryu, Jaesik Park
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in vision foundation models (VFMs) has made automated open-vocabulary 3D bounding box annotation increasingly feasible by jointly leveraging LiDAR point clouds and images. However, partial observations remain a major challenge in sparse driving scenes, where visible LiDAR points often cover only a small fraction of the object's surface and provide insufficient cues for estimating its full spatial extent. As a result, existing methods often produce mislocalized boxes or leave objects unlabeled. To address this limitation, we propose \textbf{\Ours{}}, an automated annotation framework that leverages image-generated 3D assets as amodal geometric priors for partially observed objects. By establishing correspondences between input images and rendered views of 3D assets, \Ours{} robustly aligns canonical amodal geometry with partially observed world-space LiDAR point clouds. To improve temporal consistency and reduce computational cost, \Ours{} generates a single asset per in

---

### [308] Learning a Unified Cross-Model Semantic Dictionary via Gated Bottleneck Sparse Autoencoders

**链接**: https://arxiv.org/abs/2611.10503
**作者**: Jinchi Zhu, Tie Luo
**来源**: cs.LG cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models pretrained on similar data distributions tend to learn overlapping semantic structure, but their representations are distinct due to different model architecture, pretraining objectives and protocols. This prevents unified interpretability and cross-model feature reuse. Existing approaches extract interpretable concepts from individual models and align these concepts in a shared coordinate system using cross-reconstruction objectives, but the alignment only applies to latent coordinates while the concepts themselves remain model-specific and cannot be shared or reused. This paper introduces the Gated Bottleneck Sparse Autoencoder (GB-SAE), which casts unified cross-model interpretability as a representation factorization problem and solves it by simultaneously learning a unified shared dictionary and multiple private model-specific dictionaries via a gated bottleneck sparse autoencoder framework. The shared dictionary encodes the cross-model common semantic structure 

---
