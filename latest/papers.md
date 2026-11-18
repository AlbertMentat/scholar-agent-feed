# 📑 论文索引 - 2026-11-19

共 135 篇论文

---

### [1] Stress Testing a Multimodal Large Language Model Grading Assistant on Kinematics Graph Reading

**链接**: https://arxiv.org/abs/2611.22726
**作者**: Ons Zammel, Carlos Soares, Fl\'avia Carvalhido, Gerd Kortemeyer
**来源**: physics.ed-ph cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) can recognize graph features yet award credit without sufficient graphical support. This exploratory study examines selected grading outputs for synthetic responses to four kinematics exercises, generated through visual distortion and progressive transformation toward reference graphs. Different model and prompt configurations were used. Some judgments correctly distinguished instantaneous zero velocity from rest over a finite interval and recognized positive curvature. Yet a severely distorted velocity--time graph received full credit despite disconnected and branching traces and an unclear zero-velocity reference. Other submissions graded under the same configuration lost substantial credit. Numerical cutoffs intended to distinguish meaningful features from drawing irregularities were supplied without a coordinate convention for unnumbered graphs, leaving the basis of exact partial-credit awards unresolved. Stress testing can expose unsupporte

---

### [2] Growing Clusters Lower the Bar: Profile Accretion in LLM-Based Incremental Entity Resolution

**链接**: https://arxiv.org/abs/2611.22485
**作者**: Huixue Han, Shangzhi Xu, Anqi Xiong, Yu-Chu Tian
**来源**: cs.CL cs.DB
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Incremental entity resolution pipelines ask a large language model (LLM) whether a new record belongs to an existing cluster and show it the records already linked. Analyses of matching oracles assume that the answer depends only on the records compared. For the LLM matchers we test, it depends on cluster size, and the model lowers its bar for joining a cluster as the cluster grows. On French procurement suppliers from FOPPA, with SIREN identifiers as ground truth, we hold the new record fixed and vary only the number of verified members shown. Sixteen members instead of one raise the false match rate on similarly named companies by \dfmrMin--\dfmrMax{} percentage points in six open-weight models, while their area under the ROC curve rises by only \aucGainMin--\aucGainMax. In Claude Sonnet~5 and Haiku~5.5 the rise is \clSonD{} and \clHaiD{} points. The shift persists with street addresses, prompt variants and the BatchER and ComEM formats, and one false merge raises acceptance of the i

---

### [3] Sample-efficient Personalization of Large Language Model Alignment with Multidimensional User Preference Data

**链接**: https://arxiv.org/abs/2611.22210
**作者**: Zhen-Yu Zhang, Jerry Huang, Gang Niu, Takashi Ishida, Masashi Sugiyama
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Preference alignment has become a central tool to align large language models (LLMs) with human values and desired behavior, and its online variant can further advance their capabilities beyond what static data alone offer by repeatedly generating and labeling new responses with human feedback. But costly, time-consuming annotations limit its scalability, making sample efficiency essential, and existing methods typically seek to improve it by expanding coverage of the response space or selecting pairs with the highest uncertainty for comparison. Although they are effective, these methods quantify uncertainty from the perspective of the LLM, which may differ from the uncertainty perceived by the user: a pair can appear highly uncertain to the LLM even when past comparisons from the user already imply a clear ordering. In this paper, we propose multidimensional preference-guided online direct preference optimization (MPG-DPO), which leverages low-cost multidimensional evaluations from au

---

### [4] Margin Dynamics for Large Language Model Alignment

**链接**: https://arxiv.org/abs/2611.21766
**作者**: Xingzi Xu, Mehmet Saygin Seyfioglu, Karim Bouyarmane
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practitioners choose among LLM alignment methods largely by trial and error. We provide a theoretical foundation: each pairwise method defines a vector field on the probability simplex that governs how the model redistributes mass between preferred and dispreferred completions. Projecting onto a single preferred/dispreferred pair reduces this to a one-dimensional margin ODE with a closed-form solution. These solutions reveal that DPO margins grow without bound (logarithmically as $O(\log t)$ in the gradient-flow limit) while IPO margins converge to a finite $1/(2\tau)$; that label noise induces a qualitative phase transition in DPO (unbounded $\to$ bounded) but affects IPO only quantitatively; and that gradient concentration under asymmetric weighting governs trainability at scale. We confirm all three predictions across five model families spanning four benchmarks. The closed-form solutions also enable principled method design: we prove that adding any label smoothing $\varepsilon > 0

---

### [5] Consistency Is Not Correction: Separating Confidence, Abstention, and Recovery in LLM Agents

**链接**: https://arxiv.org/abs/2611.21651
**作者**: Khushal Sethi
**来源**: cs.CL cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A controller that resamples an answer, escalates to a larger model, or abstains is usually justified by a confidence signal. Three claims about such a signal do not follow from one another: it ranks answers (discrimination), it supports withholding some of them (selective prediction), and it changes an answer for the better (correction utility). We give an exact decomposition of the third into gated recoveries minus gated harms, which bounds whether a comparison can succeed before it is run: a gate that only replaces a proposal can act only where the base policy was already wrong, so the initial error count caps the discordant pairs any correct gate can produce. When that cap falls below the count a paired test needs, the experiment cannot return a positive result for a working mechanism, nor distinguish one from a gate that never fired. We measure all three targets on two model scales and find the bound binds. In a small-model suite a perturbation-agreement verifier reaches within-pol

---

### [6] Evaluating and Understanding Scheming Propensity in LLM Agents

**链接**: https://arxiv.org/abs/2603.01608
**作者**: Mia Hopman, Jannes Elstner, Maria Avramidou, Amritanshu Prasad, David Lindner
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [7] Same Simulation, Different Evidence: Where Retrieved Tool Output Costs LLM Agents Accuracy

**链接**: https://arxiv.org/abs/2610.26836
**作者**: Ke Zhang, Sahchit Chundur, Jerry Peprah Owusu, Mohammad Javad Abdolhosseini Qomi, Maziar Raissi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [8] Regularizing Treatment Leakage for LLM-based Uplift Estimation

**链接**: https://arxiv.org/abs/2611.20794
**作者**: Bojing Feng, Jinqiu Deng, Zihan Hong, Yuan Xue, Wenqi Xiang, Shuhan Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [9] Signed but Not Safe: Requirement Integrity in Multi-Agent LLM Handoffs

**链接**: https://arxiv.org/abs/2611.07483
**作者**: Xiaobo Chen, Genliang Zhu, Ziyuan Wang, Chu Wang
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [10] Can AI Judge You? An Empirical Audit of Deployment Readiness in LLM-assisted Hiring Systems

**链接**: https://arxiv.org/abs/2611.20140
**作者**: Spandan Roy, Subhabrata Majumdar, Soudeep Deb
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [11] From Strategy Search to Policy Learning: MCTS-Guided Adversarial Co-Evolution for LLM Safety Alignment

**链接**: https://arxiv.org/abs/2511.19218
**作者**: Xurui Li, Kaisong Song
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] Multi-Agent Memory Inconsistency: Where Factual Conflicts Disappear in LLM Agents

**链接**: https://arxiv.org/abs/2611.22245
**作者**: Hejia Zhang, Zhongming Yu, Yimin Ding, Wei-Ting Chen, Hengjia Yu, Wentao Ni 等 (10 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent delegation lets LLM systems distribute evidence collection across workers with separate contexts. This creates a consistency challenge: facts retrieved by workers may be missing from the evidence available to the lead for a joint conclusion. We introduce a benchmark and evidence-flow profiler for studying multi-agent memory inconsistency through controlled factual conflicts in Harvey LAB document-review tasks. Pooled across three models with comparable generation spending, requiring delegation increases retrieval of both conflicting claims from 50.2% to 68.7% relative to single-agent execution, yet conflict detection falls from 16.2% to 13.2%. Within this setting, workers report both claims for only 35.2% of retrieved pairs, and pooled matched comparisons show higher detection than single-agent execution when one worker reads both claims but lower detection when the claims are split across workers. Worker-to-lead handoffs are a central target for improving conflict detectio

---

### [13] DAPS: Dependency-Aware Premise Selection for LLM Theorem Proving

**链接**: https://arxiv.org/abs/2610.41536
**作者**: Zixuan Chen, Wenyuan Jiang, Junling Wang, Mrinmaya Sachan, Yinya Huang
**来源**: cs.LO cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] DACE: Diversity-Driven Adversarial Co-Evolution for Robust LLM Safety Alignment

**链接**: https://arxiv.org/abs/2611.22278
**作者**: Peng Yu, Xiaoyu Wen, Zhida He, Ziyuan Zhou, Han Qi, Shao Zhang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ensuring robust safety alignment of large language models (LLMs) is increasingly difficult as adversarial attacks evolve and outpace alignment pipelines built on pre-collected data. Existing co-evolutionary frameworks let the defender chase a moving attacker, yet their training dynamics expose two compounding pathologies: \emph{attack strategy collapse}, where the attacker overfits to a narrow set of high-reward rewrites, and \emph{defense adversarial forgetting}, where the defender loses competence against earlier attacks as the attack distribution drifts. Existing remedies are partial: attacker-side diversity rewards score textual novelty rather than strategy novelty, and defender-side replay relies on discrete judge scores that ignore estimation uncertainty, response stochasticity, and defender non-stationarity. We introduce \textbf{\method}, a diversity-driven adversarial co-evolution framework that targets both pathologies jointly. On the attacker side, \method couples an explicit

---

### [15] Beyond Bitwidth: Deployment-Constrained Mixed-Precision Quantization for Multilingual LLM Inference on NVIDIA Blackwell

**链接**: https://arxiv.org/abs/2611.21974
**作者**: Hyojung Han
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Low-bit LLM quantization is useful only if a model preserves service-relevant accuracy, executes through supported GPU kernels, and meets measured memory and latency limits. We study Qwen3-8B on NVIDIA B200 with vLLM, including INT2/INT3, GPTQ, NVFP4, and mixed-precision configurations. We verify native packed execution and precision on all 144 fused linear modules and evaluate Korean, English, numerical, and reasoning quality under preregistered gates. Packed INT2 and INT3 execute, but all seven tested INT2 grids degenerate on generation. Isolated module-restoration effects are strongly non-additive; Korean and reasoning sensitivity rankings disagree, and a promising INT4/INT8 development candidate fails independent final evaluation. A configuration with 16-bit activations, 98 NVFP4 weight-only modules, 46 INT8 modules, and an INT8 output head passes all gates on the untouched FINAL-81 set (5,168 items): 5.917 GiB of weight-loading memory (limit 5.98), Korean teacher-correct retention

---

### [16] Can AI Help Explain AI? Effects of Multimodal LLM-Generated Explanations on Perceived Understanding and Perceived Trust in XAI Visualizations

**链接**: https://arxiv.org/abs/2611.21638
**作者**: Mario Truss, Marc Schmitt, Stefan Feuerriegel
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Explainable artificial intelligence (XAI) aims to make machine learning models understandable, yet many XAI visualizations remain difficult for end-users to interpret. Here, we evaluate whether augmenting XAI outputs with textual explanations from multimodal LLMs improves perceived understanding and perceived trust. We conducted a pre-registered within-subject experiment ($N = 128$) across seven decision scenarios and five XAI methods, with and without LLM generated explanations. The explanations improved perceived understanding and perceived trust by 0.35 and 0.26 points on five-point scales (both $p < .001$). The gain appeared in all seven scenarios, did not differ between local and global explanations, and was largest for participants with the least prior XAI exposure. A mediation analysis indicates an indirect effect on perceived trust through perceived understanding. These results suggest that multimodal LLMs can provide a useful interpretive layer for XAI beyond expert audiences.

---

### [17] Bad Apples in the Kitchen: How LLM Teams Detect, Correct, and Calibrate Against Their Misaligned Members

**链接**: https://arxiv.org/abs/2611.22342
**作者**: Dongseok Heo and Junghwan Kim and Bongwon Suh
**来源**: cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> What protects an LLM team when one teammate quietly goes wrong? Most multi-agent LLM work assumes cooperative partners and inspects chat between turns before acting. Real-time embodied cooperation does not allow this pause: chat runs alongside action, so a teammate whose words stay cooperative while behavior diverges can cause damage faster than the team can name what is happening. We study this case by injecting three theory-grounded misaligned agents into a custom four-player Overcooked environment, each stressing a different joint-action layer (speech-action mismatch, role invasion, and aggregate-progress disruption), and decompose robustness into three sequential gates of detection, correction, and calibration through a 3x4x2 design (n=720 episodes). Nearly all trolls are eventually named, but recovery follows only when attribution and situational diagnosis appear in the same utterance; direct source-attribution prompting improves the hardest case only by degrading the troll-free b

---

### [18] AutoPBO: LLM-powered Optimization for Local Search PBO Solvers

**链接**: https://arxiv.org/abs/2509.04007
**作者**: Yi Chu, Jinyuan Li, Yiwen Sun, Mengchuan Zou and Shaowei Cai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] GauntletScore: Auditable Fact-Checking That Matches the Best Published Checkers on LLM-AggreFact

**链接**: https://arxiv.org/abs/2611.22027
**作者**: Ernie Hobbs, Jim Hinson
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Checking whether a generated sentence is supported by its source document is a standard safeguard for AI-written text, and the strongest published checkers are single models. We describe GauntletScore, an evidence engine whose few rules and thresholds were set on the benchmark's development split. It puts typed questions to independent readers from different providers and records each answer as a measurement in an evidence ledger. It combines the measurements with a fixed Bayesian rule that counts a contradiction only when two readers agree. On the full LLM-AggreFact test split (29,320 claims across 11 datasets), following the leaderboard's approach, GauntletScore achieves 79.51 balanced accuracy, above every average published on the leaderboard as of 15 November 2026. That places it level with the best of them, nimble-v4-max (79.45 from its published dataset scores; the engine's 95% interval, 78.47 to 80.53, contains it). On the same claims it beats two of its three readers used alone

---

### [20] FCP: Formal Context Protocol for Verifying LLM-Generated Artifacts

**链接**: https://arxiv.org/abs/2611.21679
**作者**: Shashank
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a language model writes both an artifact and the tests meant to check it, a passing test is weak evidence: one misreading of the request yields a faulty artifact and a check that accepts it. We present the Formal Context Protocol (FCP), which checks AI-generated artifacts against the request itself. FCP separates conformance (does the artifact satisfy a formal reading of a requirement?), which model checkers and SMT solvers decide, from fidelity (does the reading mean what the prose means?), which has no decision procedure but is refutable by a concrete witness. Eight ways a proof can falsely certify a requirement each become a mechanical check that returns a witness, and what no machine can settle becomes concrete questions for the request's author. Adapters place hardware, text, agents and code on the same engines. On four hardware designs, trusting AI-written assertions certified 23% of violated requirements, and FCP certified none. On ten code tasks, code from three language m

---

### [21] Solver to System: LLM Reasoning Across Representations and Execution in Scientific Simulation

**链接**: https://arxiv.org/abs/2611.21964
**作者**: Eliza Berman, Rohan Subramanian, Shreya Jha, Lohit Jagarapu, Romain Lopez, Rajesh Ranganath
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulators based on partial differential equations (PDEs) are widely used to model physical systems, but generating and interpreting PDE solver code with large language models (LLMs) remains challenging. Scientific simulation code is a useful testbed for LLM scientific reasoning because (1) one system can be represented by code, equations, natural language, and numerical trajectories and (2) code can execute successfully while implementing invalid physics. We introduce Solver2System, a dataset of PDE solvers with multiple representations, controlled corruptions, and lexical perturbations, to evaluate whether LLMs can recover the underlying physical system through (1) cross-representation consistency and (2) static and agentic detection of physical invalidity. Across eight open-weight models, LLMs systematically favor some representations when evidence conflicts, and lexical perturbations to code alter interpretation of other unchanged representations. Execution improves physical-validi

---

### [22] Network-Exposed Configuration Attacks on LLM-Controlled Social Robots

**链接**: https://arxiv.org/abs/2611.22761
**作者**: Stanley Akingbola, Ugbede Ibrahim, Yan Lin Aung, Quang Dan Le, Hong Qing Yu
**来源**: cs.CR cs.AI cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) in embodied robots create security dependencies beyond inference. We investigate a network-exposed configuration attack on the Pollen Robotics Reachy Mini Lite, allowing an unauthenticated attacker to replace personality settings and the cloud LLM's system prompt through a management interface, without adversarial conversational input. Eleven prompt-injection attempts across five categories were reported as resisted, whereas both configuration-layer attack paths produced observable behavioural changes on physical hardware. We demonstrate local and network-adjacent access, mapping the weakness to CWE-306 (Missing Authentication for a Critical Function) and CWE-1327 (Binding to an Unrestricted IP Address), with a reported CVSS v3.1 score of 6.5 (Medium). A configuration endpoint also accepts cross-origin requests without a CORS preflight (CWE-352; 6.5 Medium), while the persistent-memory sink stores content without enforcing its stated restrictions. A source 

---

### [23] XM-Sparse: High-Throughput Sparse-Attention LLM Serving over Scale-up Memory Pools

**链接**: https://arxiv.org/abs/2611.22280
**作者**: Yijun Sun, Xudong Liao, Zhuobin Huang, Kai Chen, Nikita Lazarev, Zhizhen Zhong
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse attention has been increasingly adopted by production LLMs for long-context inference, yet serving systems must still retain the full KV history, making GPU HBM capacity a key limit on serving concurrency. Existing systems offload the KV cache to host memory, but suffer from the limited bandwidth of PCIe and the limited capacity of host memory. Emerging scale-up memory pools (e.g., X-Mem) relieve both limits and open new opportunities for sparse-attention offloading. In this paper, we first conduct an in-depth analysis and reveal that, even with scale-up memory pools, decode throughput remains bounded by HBM capacity, as hot KV buffers and the fully resident indexer key (K-index) cache occupy substantial HBM. Moreover, the two caches exhibit distinct access patterns. Based on these insights, we present XM-Sparse, the first sparse-attention offloading system over scale-up memory expansion. The core idea of XM-Sparse is to offload both caches aggressively while matching each with 

---

### [24] PSM: Prompt Sensitivity Minimization via LLM-Guided Black-Box Optimization

**链接**: https://arxiv.org/abs/2511.16209
**作者**: Hussein Jawad, Nicolas J-B Brunel
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] SOTA or Luck? The Winner's Curse in LLM Leaderboards

**链接**: https://arxiv.org/abs/2611.22227
**作者**: Sikun Xu, Raphael Thomadsen, Dennis J. Zhang, Heng Zhang
**来源**: cs.LG cs.CL stat.ME stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Public LLM leaderboards guide model evaluation and adoption, yet the reported performance of top-ranked models can be systematically overstated. This leaderboard winner's curse arises because ranking noisy benchmark scores rewards sampling luck alongside genuine ability. The same selection effect can distort scores throughout the leaderboard, a phenomenon we call the rank-induced bias. We develop an $m$-out-of-$N$ bootstrap to correct for this bias. It assumes a fixed model pool with independent, identically distributed bounded tasks while allowing arbitrary within-task correlation among models. Under exact population tiers separated by positive gaps, we prove that the bootstrap reduces $\Theta(N^{-1/2})$ ranking bias to expected residual bias $o(N^{-1/2})$. Across 14 benchmarks from 5 benchmark families, the rank-1 adjustments range from approximately 0.09 to 3.86 percentage points. In our SWE-bench Verified snapshot, the tied leaders receive an adjustment of 0.90 percentage points. S

---

### [26] Can Activation Steering Substitute for Prompt-Based Affective Priming in LLM Digital Twins?

**链接**: https://arxiv.org/abs/2611.22738
**作者**: Junyi Fan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Affective priming -- asking participants to write about a recalled event, such as a time they felt grateful or lacked control, and then measuring the induced state and its spillover onto related judgments -- is a standard way to manipulate emotion in the social sciences, and it also shifts the responses of LLM-based digital twins. The writing task, however, requires generating a full text. We test whether activation steering can replace it. Using Llama-3.1-8B-Instruct on 100 personas in two domains (gratitude, lack of control), we compare a real-prompt path replicating the original Twin-2K-500 Mega Study (J2) with an injection path that skips the writing and adds a mean-difference direction, extracted from human writing, to the residual stream at varying strengths. The real-prompt effects fall between the original human and digital-twin effects in 5 of 6 comparisons. Injection shifts the manipulation check in a dose-dependent way and matches the real-prompt effect at one strength in th

---

### [27] The Language-Energy Divide: Measuring Energy Costs of Multilingual LLM Inference

**链接**: https://arxiv.org/abs/2606.21869
**作者**: Naihao Deng, Alissa Shen, Yiming Feng, Joan Nwatu, Jae-Won Chung, Mosharaf Chowdhury 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] Do LLM Agents Still Need to Be Told How to Self-Improve?

**链接**: https://arxiv.org/abs/2611.23219
**作者**: Shobhita Sundaram, Cansu Sancaktar, Phillip Isola
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly drive their own learning. Self-improvement methods delegate various components of model optimization to the models themselves. As models become more capable, this motivates a basic question: do these increasingly capable models still need us to specify how they should self-improve? In this paper we study an autonomous paradigm in which, given basic primitives, resources, and a general goal for self-improvement, agents construct their own self-learning algorithm for context-based optimization. Using the setting of gameplay as a testbed, a frozen LLM agent is given a compute budget and tools for collecting experience and updating text documents, and allowed to freely experiment without an externally imposed loop or access to real-world data. We find that sufficiently capable models do self-improve under these conditions, demonstrating strategies that align with classic cognitive frameworks for self-regulated learning and constructs from machine learning literature

---

### [29] The Defense Rests: A Courtroom-Inspired Multi-Agent LLM Framework for Automated Safety Case Generation

**链接**: https://arxiv.org/abs/2611.21618
**作者**: Gerhard Yu, Amanuel Aknaw, Amir Ali Mohaghegh, Yong Song (Alex) Cao, Alvine B. Belle
**来源**: cs.SE cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety cases are widely used to demonstrate that mission-critical systems, such as autonomous vehicles and unmanned aerial systems, can operate safely after deployment. However, manually constructing safety cases is complex, time-consuming, and labor-intensive, which calls for the proposal of automated approaches to support their creation. Inspired by the legal nature of safety case construction, we formalize the safety case creation problem through a courtroom analogy, where stakeholders collaboratively propose, examine, criticize, review, improve and validate safety claims and their supporting evidence. In this analogy, the safety analyst acts as a prosecutor by identifying hazards and safety concerns, while the assurance case developer serves as a defense attorney by constructing and substantiating safety arguments. An orchestrator acts as a judge by coordinating stakeholder interactions, and a review board serves as a jury by assessing argument completeness and persuasiveness. Base

---

### [30] Thinking Harder Doesn't Lead to Better Choices: Reasoning Effort Increases the Confidence but Not the Correctness of LLM Shopping Agents

**链接**: https://arxiv.org/abs/2611.22033
**作者**: Adi Krishnamoorthy, X.Y. Han
**来源**: cs.AI cs.CL cs.CY cs.HC econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed as autonomous shopping agents that process multimodal product listings (consisting of visual and text data) and recommend purchases on behalf of consumers. Naturally, one might assume that models with more thinking power would make higher-quality purchasing decisions. To test this belief, we ask two questions about such agents: does asking a model to think harder make it choose better products, and does the confidence it reports tell us the likelihood it may be wrong? We benchmark ten frontier models on three product-choice benchmarks built from WebShop, Amazon's SQID and Wayfair's WANDS platforms to see if LLMs with more thinking power actually make better-quality product purchase decisions. Across all three benchmarks, we found that increasing the thinking effort does not increase decision quality in a statistically meaningful way. The same change in thinking effort raises stated confidence at a statistically significant level, s

---

### [31] Thinking Is Not Telling: Information Disclosure in User-Service LLM Agents

**链接**: https://arxiv.org/abs/2602.07796
**作者**: Jiatong Li, Changdae Oh, Hyeong Kyu Choi, Jindong Wang, Sharon Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Trust the Direction, Search the Step: Zero-and-First-Order Methods for LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.02190
**作者**: Cristian McGee, El Houcine Bergou, Aritra Dutta
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Think Once, Act Fast: Cost-Effective Recursive Self-Improvement for Decision Model Harness

**链接**: https://arxiv.org/abs/2611.22432
**作者**: Siqi Lai, Haitao Li, Hao Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fast System-1 models enable responsive actions but struggle with complex or unfamiliar tasks. Large language model (LLM)-based System-2 provides strong reasoning capabilities, yet repeated invocation incurs substantial latency and computational costs. To bridge this gap, we propose JevRSI, a System-1/System-2 collaboration framework that transforms LLM reasoning into transferable decision support through recursive harness improvement. A Jev-style System-1 model enables low-latency action selection, while an asynchronous System-2 LLM develops a modular harness. The harness integrates procedures, state memory, and world models to provide decision contexts spanning the past, present, and future. Utility-driven retrieval selects modules based on both contextual relevance and their utility on previous tasks. Environmental feedback guides targeted revisions and enables recursive self-improvement. Experiments across three datasets show that JevRSI consistently improves decision quality, match

---

### [34] JigSLO: Solving the Resource Puzzle for Efficient Multi-LLM Serving

**链接**: https://arxiv.org/abs/2509.06261
**作者**: Kyungmin Bin, Seungbeom Choi, Jimyoung Son, Jieun Choi, Daseul Bae, Daehyeon Baek 等 (9 人)
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Words Speak Louder? Exploring the Language Shortcut of LLM-Driven Incomplete Multimodal Learning

**链接**: https://arxiv.org/abs/2611.20349
**作者**: Qiangchang Wang, Chong Xiao, Xiaokun Bai, Rundong He, Zhuang Qi, Xusheng Liang 等 (8 人)
**来源**: cs.CV cs.MM
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] GPTZero: Robust Detection of LLM-Generated Texts

**链接**: https://arxiv.org/abs/2602.13042
**作者**: George Alexandru Adam, Alexander Cui, Edwin Thomas, Emily Napier, Nazar Shmatko, Yue Gao 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] Watermark Evidence under Open-Weight LLM Modification: Exact Bounds for Low-Rank Output Watermarks

**链接**: https://arxiv.org/abs/2611.21702
**作者**: Prashant Shekhar, Dumindu Samaraweera, Caroline Howard
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Open-weight language models can continue generating after their released weights are modified, while a watermark verifier still scores outputs against the original base and marked models. We study how such modifications change the evidence available to an OpenStamp-style verifier. At each shared prefix, we represent the modification as a residual in the next-token logits. We derive an exact finite-vocabulary lower bound on the expected log-likelihood-ratio evidence under a residual-span constraint, along with a sharp span-only deviation bound. We also characterize the first-order evidence shift through a covariance term with an explicit second-order remainder, and determine the residual span needed to reach a target evidence level. For sequence-level detection, we derive an exact conditional exponential-moment bound and combine it with a supermartingale argument and a distribution-free order-statistic tolerance bound. This yields a high-confidence upper bound on miss probability after 

---

### [38] Call-Efficient ICD-10 Code Prediction via Supervised Candidate Generation and Selective LLM Invocation

**链接**: https://arxiv.org/abs/2611.21891
**作者**: Ilia Kopanichuk, Daniil Kartashev, Yuri Bolkonsky, Petr Anokhin, Vladimir Makharev, Iaroslav Bespalov 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic assignment of ICD-10 codes from short clinical diagnosis text is a practical medical text classification and normalization task. The task is difficult because diagnosis phrases are short and noisy, the ICD-10 label space is hierarchical, and the class distribution is strongly imbalanced. This paper presents a call-efficient ICD-10 code prediction pipeline that combines transformer embeddings, tree-based supervised candidate generation, candidate-level reranking, and a gated LLM assistance. The evaluation uses a leakage-safe validation protocol: model and threshold selection are based on out-of-fold cross-validation predictions, while final reporting is performed on a locked test set with no shared source-file groups. The supervised conditional parent-code candidate generator reaches 74.32% Top-1 accuracy on the locked test set and 93.05% Top-10 candidate coverage. A direct zero-shot GPT-5.6-Sol baseline reaches 81.01% Top-1 accuracy, but requires an invocation of this large m

---

### [39] ParallelVLM: Lossless Video-LLM Acceleration with Visual Alignment Aware Parallel Speculative Decoding

**链接**: https://arxiv.org/abs/2603.19610
**作者**: Quan Kong, Yuhao Shen, Yicheng Ji, Huan Li, Cong Wang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] SpecSearch: Towards Hardware-Aware Efficient Speculative Decoding

**链接**: https://arxiv.org/abs/2611.22296
**作者**: Selin Yildirim, Ali Zeyrek, Deming Chen
**来源**: cs.AI cs.DC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding (SD) accelerates large language model (LLM) inference, but its optimal configuration depends jointly on workload characteristics, GPU hardware, and available memory. For example, on the RTX~5090, the state-of-the-art speculative drafter DFlash achieves $3.50\times$ the throughput of autoregressive (AR) decoding at low concurrency, but only $0.76\times$ at high concurrency with short outputs. We present SpecSearch, a hardware-aware search engine that jointly optimizes decoding strategy, draft length, and precision across workload--GPU pairs. Its analytical cost model captures memory and compute constraints to identify feasible configurations and narrow the search space for throughput optimization. Guided by this model, calibration measurements are collected from multiple GPUs. Using the measurements, a Jev-based predictor learns to select high-throughput decoding configurations on held-out GPUs without requiring deployment-GPU calibration. The predictor is parameter

---

### [41] The Between-Round Decision in Autonomous Research: An LLM Controller That Reads the Whole Trajectory

**链接**: https://arxiv.org/abs/2611.22661
**作者**: Caoxin Wang, Shengkai Gan, Xiang Hu, Lili Pan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Executing an idea often changes how promising it looks, so the next step in autonomous research should rest on results, not on proposals. After each round of experiments, the system must decide whether to refine the best solution or start a new direction, which solution to build from, and what goal to set. We call this the between-round decision. Existing systems wrap it in machinery such as rules, scores, search trees, and schedules; where an LLM makes it, what the LLM needs to read is left open. We ask whether an LLM can make this decision from accumulated evidence, without a search structure around it, and how much of that evidence it needs to read. We present BRED (Between-Round Evidence-based Decision), an LLM-based controller that maintains the best verified solution so far (the Champion) and a log of past rounds, and makes one decision per round. On three widely used research-agent benchmark tasks, BRED improves on the task baselines by 4.80% in MAE on ETTh1 (to 0.4172) and by 3

---

### [42] RegimeCouncil: Paired-Evidence Routing For Memory Conflict Governance In LLM Agents

**链接**: https://arxiv.org/abs/2611.22113
**作者**: Qingcan Kang, Mingyang Liu, Shixiong Kai, Tao Zhong, Mingxuan Yuan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language agents rely on long-term memory to personalize responses across extended interactions, yet stored facts quietly go stale as the world changes, and an agent often learns that using memory hurt only through delayed feedback after acting on an outdated record. Before the memory store is updated, how far should that negative feedback propagate: should it suppress memory use only on future queries for that same fact (a local policy), or also across other stored facts (a global policy)? Existing memory systems implicitly fix one of these two sharing scopes at design time. We formulate this online scope choice under hidden validity and delayed feedback as memory conflict governance, and prove that neither fixed policy is sufficient on its own. We then propose RegimeCouncil, a lightweight paired-evidence router that retains both scopes as advisors and arbitrates between them online without retraining the LLM. Using revealed comparisons between answering with memory and answering witho

---

### [43] What Does an Agent Need? Bundle-Aware Agent Resource Composition

**链接**: https://arxiv.org/abs/2611.22030
**作者**: Yunxiao Shi (1), Tingwei Chen (2), Dannong Xu (1), Ahad N. Zehmakan (1), Jialie Shen (3), Zhendong Chu (4) 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent resource's value depends on its backbone and companion resources and is known only after execution. Token-based generators remain tied to their training catalog, while independent resource scoring misses complementarities and reused bundles target other tasks. We formulate Task-Conditioned Agent Resource Composition (AgentComposition): jointly selecting a backbone model and a tool-skill bundle to maximize end-to-end execution utility. Our Retrieval-Grounded Bundle-Aware Agent Generation retrieves candidate resources and past configurations of similar tasks. A fine-tuned generator reads resource descriptions and recombines candidates through constrained beam search, allowing new resources without retraining. A bundle-aware critic ranks complete configurations using a large language model (LLM) teacher and historically successful configurations as execution proxies, and adapts to execution feedback when available. We evaluate reference recovery, offline execution with judged and

---

### [44] LMLineage: Content Lineage and Context Governance for LLM Agents

**链接**: https://arxiv.org/abs/2611.22511
**作者**: Wei Hou, Jingxin Geng, Xin Chen, Zheqing Jiang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpretability for AI agents should not be confined to understanding the model's internal weights. It must also cover the agent's reasoning and decision-making process over multi-source context. We present LMLineage, an out-of-band system that attributes every output sentence of an agent session to its supporting input spans with calibrated confidences, without requiring white-box access to the model or any additional inference passes. On top of the lineage metadata, we build concept-drift micro compaction: instead of waiting for the context-length limit and summarizing everything, the system detects when previously used input documents have stopped being referenced ("drifted") and surgically compacts only those, preserving user instructions verbatim. We evaluate on a multi-tier corpus: 71 gold annotated sentences from 10 Chinese web-QA cases, plus 90 turns of independently collected multi-turn sessions across three generator models (gpt-4o-mini, qwen3.8-27b, deepseek-v4-flash). Resu

---

### [45] Adaptive LLM-Driven Honeypots vs. LLM-Driven Attackers: Does Narrative Coherence Improve Deception?

**链接**: https://arxiv.org/abs/2611.22589
**作者**: Pedro Beltr\'an-L\'opez, Raul Gonzalez Jimenez, Dario Maddaloni, Manuel Gil P\'erez, Pantaleone Nespoli
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) enable honeypots to generate responses and deceptive artefacts on demand, yet existing approaches evaluate generated content one reply at a time and leave open whether artefacts that jointly describe a coherent event retain an attacker better than unrelated ones. This question becomes pressing as autonomous LLM-driven offensive agents emerge as realistic adversaries. This paper proposes narrative deception, a reactive strategy in which the defender maps each observed attacker command to a MITRE ATT&CK technique, selects a compatible scenario from a curated catalogue based on MITRE Engage, and deploys mutually referential artefacts (files, processes, services, and logs) on an emulated Ubuntu host while the intrusion is under way. An LLM-powered defender and an autonomous LLM attacker interact through a real SSH session, and the attacker's termination policy distinguishes abandonment due to suspected deception from abandonment due to loss of interest. A campa

---

### [46] Process Advantage Signal Shaping: Advantage Construction for Process-Supervised Reinforcement Learning in LLM Reasoners

**链接**: https://arxiv.org/abs/2606.29296
**作者**: Chao Wang, Hongtao Tian, Tao Yang, Yunsheng Shi, Ting Yao, Wenbo Ding
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Inventa: Decentralized Self-Improving Agents for Autonomous Scientific Discovery

**链接**: https://arxiv.org/abs/2611.21847
**作者**: Prithwish Jana, Nikos Kanakaris, Purak Jain, Anoop Deoras, Sahika Genc
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can generate research ideas and improve scientific discovery through iterative experimentation. However, increasing the number of agents or iterations does not automatically translate to producing more diverse or feasible ideas. Agents may converge on similar candidates, propagate unsupported claims through shared memory components and repeatedly apply search strategies that no longer yield any improvements. We introduce Inventa, a framework for automated scientific discovery that employs autonomous research units and verified shared knowledge. Each unit creates a lineage of candidate ideas using a mutator agent. A local orchestrator agent periodically adapts the mutator's harness. When progress stalls, the orchestrator agent replaces its model or restarts the idea evolution process. Verifiers evaluate each candidate idea and record verified improvements, useful components and constraint violations in a shared knowledge, the only channel between units.

---

### [48] The Safeguard Worked. Is the LLM System Safer?

**链接**: https://arxiv.org/abs/2609.00519
**作者**: Pingyu Wu, Weiming Zhang, Nenghai Yu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Cross-Modal StateKV Injection for Communication in Multi-LLM Systems across Temporal Segments

**链接**: https://arxiv.org/abs/2611.22304
**作者**: Xiaoqian Zhang, Zhihao Zhang
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video understanding with multiple multimodal language models requires a communication interface that can transfer complementary visual observations. Text-based communication is interpretable, but introduces an intermediate generation stage and can omit information relevant to subsequent reasoning. We study Cross-Modal StateKV Injection, a provider--carrier framework that communicates through key--value (KV) states at visual-token positions. Provider models observe complementary video frames; their visual KV states are aligned and projected into the carrier representation space and integrated through gated residual updates. Injection preserves the carrier KV-cache sequence length, while retaining the additional computation required by the providers and the communication module. The reported experiments on MLVU and Video-MME compare carrier-only inference, text-based communication, and StateKV with two provider architectures. Results show modest, task-dependent accuracy gains and lower r

---

### [50] CyBiasBench: Benchmarking Bias in LLM Agents for Cyber-Attack Scenarios

**链接**: https://arxiv.org/abs/2605.07830
**作者**: Taein Lim, Seongyong Ju, Munhyeok Kim, Hyunjun Kim, Hoki Kim
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [51] Screening LLM Judges Without Ground Truth: A Preliminary Evaluation of an AI Dental Hygiene Coach

**链接**: https://arxiv.org/abs/2610.24335
**作者**: William DeShong, Barath Kannan, Auberon Palma, Brenda Bradshaw, Ann Bruhn, James F. Leathrum 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] From Sorry to QED: Refining LLM Math Proofs via Angelic Execution

**链接**: https://arxiv.org/abs/2611.22103
**作者**: Yanju Chen, Hanzhi Liu, Ruizhe Qian, Jiaming Shan, Xu Yang, Yufei Ding 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can now generate Lean proof scripts that capture the high-level structure of many mathematical arguments. However, these scripts frequently fail on complex theorems: a single missing side condition or misapplied lemma can cause the prover to abort early and discard an otherwise viable proof outline. This paper presents MathEye, a framework that converts imperfect LLM-generated proof scripts into fully verified Lean proofs by combining symbolic reasoning with minimal human interaction. At the core of MathEye is angelic proof checking, an optimistic execution model that replaces failing proof fragments with placeholders while preserving the overall structure of the argument. This optimistic check produces an angelic proof that isolates the exact proof obligations that the LLM fails to discharge. Because these unresolved obligations are often logically interdependent, asking a mathematician to address every placeholder directly is inefficient. To minimize huma

---

### [53] Weight-Space Programming Doesn't Need Transformers

**链接**: https://arxiv.org/abs/2611.22055
**作者**: Hyunjong Ok, Jaeho Lee
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Standard neural architectures such as the Transformer were chosen because they train well with gradient descent and run fast on GPUs. In weight-space programming, a large language model (LLM) writes target weights by hand without gradient-based training, so those reasons no longer apply. Should we keep the Transformer? Given minimal guidance, ten labeled examples, and a sandbox, mainly on multiple-choice questions, we task three frontier LLMs with either generating the weights of a fixed architecture or designing the architecture themselves. When free to design, all three compile plain-text facts into a sparse table queried by a fixed procedure, reaching up to 54.4% test accuracy. An LLM-designed model achieves higher test accuracy than the most accurate released Transformer that the same LLM wrote while using about 1,800x fewer parameters. Without gradients, they choose a table, in which the LLM can state what each weight means and can find and rewrite a wrong one. Each wrong answer p

---

### [54] HyCoInfer: Cloud-Edge Collaborative Inference for Large Language Models on Heterogeneous GPU-FPGA Architectures

**链接**: https://arxiv.org/abs/2611.22086
**作者**: Zewen Huang, Xiangwen Zhuge, Yingkun Hu, Zheng Yang, Qiang Ma
**来源**: cs.OS cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) serving relies predominantly on cloud GPUs, yet autoregressive decoding is memory-bound and often leaves their arithmetic units underutilized. Edge FPGAs offer attractive decoding efficiency, but are ill suited to sustaining a high-concurrency serving workload alone. This paper presents HyCoInfer, a heterogeneous cloud-edge serving system that assigns prefill to cloud GPUs and distributes decoding across cloud GPUs and edge FPGAs. The design addresses three barriers to practical offloading: capacity balancing across heterogeneous accelerators, the large KV cache crossing a constrained wide-area link, and the latency added by heterogeneous execution. HyCoInfer incorporates FPGA decode capacity into GPU prefill/decode role partitioning and places requests according to queue load, prompt length, and network state. It further combines layer-wise pipelined transfer, decoder-side precomputation, and bandwidth-adaptive KV cache compression based on residual vector q

---

### [55] Can an LLM dream? Testing the overfitted brain hypothesis on an agent with text memory

**链接**: https://arxiv.org/abs/2611.21648
**作者**: Eric Zou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hoel (2021) proposed that dreams distort replayed experience so that the brain does not overfit to recent events. We test this hypothesis on an LLM agent (Claude Opus 5.5) that stores what it learns in a text memory and rewrites that memory each night from the day's conversation transcript. The agent goes through ten simulated days of conversation built from LongMemEval. We corrupt 5, 10, 20 or 40 percent of the transcript's turns before each nightly rewrite in one of two ways. Detail corruption changes one or two details in a turn to plausible wrong ones, or replaces the turn with one by the same speaker from an earlier day. Random-text corruption replaces half of the selected turns with a passage of Moby-Dick and inserts Moby-Dick words into the other half. A size limit on the memory, rising from 19,500 to 117,000 tokens over ten nights, set from human free-recall data, forces it to forget. We learned that corruption did not help the agent apply what it learned in earlier conversatio

---

### [56] RTLReviewBench: LLM Hardware Reviewers Rarely Miss Bugs but Routinely Reject Correct RTL

**链接**: https://arxiv.org/abs/2611.21678
**作者**: Yasir Mahmud
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hardware teams increasingly ask large language models (LLMs) to review register-transfer level (RTL) code, yet it is unclear whether a model can tell a correct module from a buggy one without simulating it. We introduce RTLReviewBench, a benchmark of 114 matched pairs of buggy and correct Verilog modules. Each pair shares one specification, most buggy modules are real failures of LLM code generators, and every label is confirmed by simulation. Evaluating 12 commercial and open-weight models, we find a consistent asymmetry: reviewers rarely accept buggy code but often reject correct code, producing more than five false rejections for every missed bug. Synthetic mutants hide part of the problem: on the same designs, models miss far fewer injected bugs than real ones. Asking a model to reason before it commits to a verdict sharply reduces false rejections for weaker reviewers, and a controlled ablation shows that where the reasoning appears in the output matters more than the instruction 

---

### [57] LLM Misuse Safeguards Rely on Untrusted Input: A Widespread, High-Risk Vulnerability

**链接**: https://arxiv.org/abs/2607.27951
**作者**: Pingyu Wu, Weiming Zhang, Nenghai Yu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] RPMem: Learning Long-Term Recurrent Parametric Memory Across Sessions for LLM Agents

**链接**: https://arxiv.org/abs/2609.23466
**作者**: Fanyu Zhao, Ruike Cao, Liang Dong, Fugen Yao, Jian Xu, Guanjun Jiang 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] The Memory Trust Gap: Reliance on Stale Evidence Across Model Scales in LLM Agents

**链接**: https://arxiv.org/abs/2609.01852
**作者**: Jundong Hu, Shekar Ramachandran
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] The Only Edge Was Memorized in Training: LLM Trading Agents Around Earnings and Bad News

**链接**: https://arxiv.org/abs/2611.22177
**作者**: Jackson Wang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] ToolFlood: Beyond Selection -- Hiding Valid Tools from LLM Agents via Semantic Covering

**链接**: https://arxiv.org/abs/2603.13950
**作者**: Hussein Jawad, Nicolas J-B Brunel
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] KVUse: Reusable-KV User Memory for Efficient LLM Recommenders

**链接**: https://arxiv.org/abs/2611.21920
**作者**: Xin Guo, Qiang Zhang, Xiang Zhou, Arushi Rai, Siyu Lin, Yifan Wu 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory-augmented recommenders built on large language models (LLMs) maintain a natural-language profile of each user. These profiles are updated by a user profile update path that revises the profile as new interactions arrive and are consumed by downstream task paths like ranking. Because these user profiles are stored as text in the user memory, every ranking LLM call that consumes them must splice them in the prompt and calculate the KV cache of them during the prefill phase. Given these ranking LLM calls are prefill heavy (long prompt but short decoded output) and repeatedly called, these repeated prefill of user profile text dominates the serving. Prefix caching cannot remove it, because these user profiles are preceded by different text in different calls. We present KVUse, which stores the user profiles as reusable key-value (KV) caches instead of text. KVUse trains lightweight LoRA writers by self-distillation, so that the user profile update call produces the reusable KV of th

---

### [63] MCTS Is Counting the Wrong Thing: Learning Exploration Counts for LLM Reasoning

**链接**: https://arxiv.org/abs/2611.22301
**作者**: Xuan Zhang, Zhijian Zhou, Zicheng Hu, Yan Feng, Hongyan Hao, Yuan Qi 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Monte Carlo tree search (MCTS) has powered landmark successes in reinforcement learning, yet its gains in LLM reasoning can remain modest despite substantial search effort. We identify an overlooked bottleneck: what MCTS counts. Standard UCT assigns independent visit counts to textual branches, allowing different formulations of the same reasoning strategy to repeatedly receive exploration bonuses. Our theoretical analysis shows that this count fragmentation can impair exploration efficiency, as quantified by increased cumulative regret. To address this problem, we introduce Learned Pseudo-Count MCTS (LPC-MCTS), which changes only the exploration statistic in UCT. A lightweight Coin-Flipping Network head on the policy's hidden representations estimates representation coverage, enabling related branches to share exploration evidence. Across 5 mathematical-reasoning and 7 search benchmarks, LPC-MCTS consistently outperforms strong MCTS baselines. Holding each LPC-MCTS-trained policy fixe

---

### [64] Beyond Retrieval: Learning Compact User Representations for Scalable LLM Personalization

**链接**: https://arxiv.org/abs/2606.04547
**作者**: Heng Cao, Fan Zhang, Jian Yao, Yujie Zheng, Changlin Zhao, Lu Hao 等 (10 人)
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] Context Has a Price: Adding and Removing Context for LLM Coding Agents under Prefix Caching

**链接**: https://arxiv.org/abs/2611.22238
**作者**: Zerui Yang, Miaomiao Dong, Quan Xue, Chaorui Zhang, Xuanyu Zheng, Xiyuan Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding agents repeatedly send their conversation history to a language model. Adding useful code may reduce search, while removing old tool outputs may shorten later prompts. But do these changes reduce the cost of solving a task? We study this as a measurement problem in more than 20,000 runs of open models on SWE-bench Verified, SWE-bench and Loc-Bench. We account separately for uncached input, cached input and output tokens. Three findings emerge. First, in our main evidence-package experiments, retrieved code reduces read and search commands by 18--34%, but increases cost by 33--42% when cached input costs one tenth of uncached input, without a measurable improvement in resolution. Second, removing old observations can either save money or increase cost: the same approach saves 19--36% without a cache discount but increases cost by 38--116% with a tenth-price cache. Third, shorter prompts do not guarantee cheaper runs because agents may respond by taking more steps. We also find th

---

### [66] RAW: Refusal Aversion in the Wild, A Causal Measurement Method for Deployed LLMs

**链接**: https://arxiv.org/abs/2611.21641
**作者**: Pavel Kireyev
**来源**: cs.CL cs.AI cs.HC econ.GN q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deployed LLMs field hundreds of millions of conversations a day and refuse a non-trivial fraction of user requests, yet the user-side cost of refusal, whether users disengage and by how much, is unmeasured on any production model: a blind spot for the consumer-facing platforms built on them. A/B-testing refusal is ethically and operationally constrained on frontier-lab products and unavailable to third-party platforms deploying these models through a fixed API. We introduce RAW, a method that uses LLM stochasticity as a natural experiment: at near-identical prompts in any existing log, the same model sometimes refuses and sometimes does not, and that variation identifies the causal user-side effect of refusal. Applying the method to 15 deployed LLMs in LMSYS-Chat-1M and WildChat, with user-clustered inference, we find that for about half of the models we can measure precisely, a refusal costs 3 to 17 pp of subsequent re-engagement; the rest show no distinguishable effect, among them on

---

### [67] Depth-Aware Activation Steering via Attention Residuals

**链接**: https://arxiv.org/abs/2611.21655
**作者**: Shilong Zhao (Independent Researcher)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering is a simple, training-free way to modulate LLM behavior, yet existing methods typically inject vectors at a single layer and lack mechanisms for depth-aware propagation or internal verification. We combine two recent ideas - Attention Residuals (AttnRes) providing learnable cross-layer pathways, and Jacobian-lens (J-space) concept readout - into a lightweight depth-aware steering pipeline. On two small open models (Qwen3-0.6B and Qwen3.5-0.8B), distributing a persona vector according to AttnRes-style depth weights yields stronger internal alignment (deeper-layer concept cosine and rank, p<0.0001) and stronger behavioral shifts than single-layer injection. The effect is sign-specific: reverse vectors invert all six metrics, random directions degrade alignment (p<0.0001), and a short LoRA fine-tune erases the imprint. Injection rewires attention strictly downstream of the injection point (upstream JS = 0.00000). Three practical findings follow. First, a layer-wise geo

---

### [68] Comparing Implicit and Explicit Language Attitudes toward the Dutch multiethnolect Straattaal in Humans and Large Language Models

**链接**: https://arxiv.org/abs/2611.22335
**作者**: Hedwig Oldenhof, Laura Rosseel, Anna Wegmann and Dong Nguyen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While language attitudes have been extensively studied in humans, the extent to which large language models (LLMs) encode similar associations between language varieties and social attributes remains unclear. Contemporary sociolinguistic research distinguishes between explicit attitudes, which stem from deliberative processing, and implicit attitudes, which arise from automatic processing. This study investigates whether LLMs exhibit human-like implicit and explicit language attitudes toward the Dutch multiethnolect Straattaal, particularly its association with migrant communities. We use closely matched designs to assess attitudes in humans and LLMs. For humans, we use an Implicit Association Test (IAT) and an explicit rating task. For LLMs, we use the LLM Word Association Test (LLM WAT) and the same explicit rating task. Human participants strongly associate Straattaal with individuals with a migration background at both implicit and explicit levels. In the LLM WAT, Straattaal is con

---

### [69] Beyond Acuity Accuracy: A Multidimensional Framework for Evaluating Patient-Facing Emergency Triage AI Tools

**链接**: https://arxiv.org/abs/2611.22045
**作者**: Ruio Heerschap, Henry Foote, Mahmoud Alwakeel, Zhouhan Qian, Jiaqi Wang, Elisabeth Bond 等 (10 人)
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patient-facing AI triage tools may support care-seeking and emergency department prioritization, but require evaluation beyond acuity accuracy alone. We developed SAFE-Triage, a framework integrating human review, automated metrics, LLM-as-judge evaluation, and simulation testing across clinical performance, patient interaction, and clinician-facing summary quality. We applied SAFE-Triage to 40 MIMIC-IV-derived emergency vignettes and a 10,030-case acuity analysis comparing prompted LLM triage (PLT) with rule-augmented prompted LLM triage (rPLT). PLT achieved higher emergency severity index (ESI) accuracy (57.5% vs 42.8%, $P < 0.001$), lower undertriage (13.1% vs 29.8%, $P < 0.001$), and higher clinician ratings across all domains. rPLT produced shorter and more stable outputs with higher automated readability scores. SAFE-Triage identified trade-offs between acuity accuracy, undertriage risk, communication quality, readability, and summary quality, supporting pre-deployment refinement

---

### [70] Deciding Without Pointing: A Case Study of Whether a Decision Model Localizes the Anomalies It Detects

**链接**: https://arxiv.org/abs/2611.21995
**作者**: Hsiang-Hung Lee
**来源**: cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision models can answer a typed question about an image with a probability per option, without generating text. In our case study of Clef-flash (post-trained Qwen3.5-9B backbone) on industrial inspection benchmarks, we ask whether it localizes the anomalies it detects. We obtained uneven results with zero-shot detection: per-category image AUROC 0.924 on MVTec AD and 0.668 on MVTec AD 2. On the former, the decision head's routing attention produces 0.391 mean per-image pixel AUROC, and hiding the image tokens from it leaves detection unchanged. The multimodal LLM's backbone attention does point at the defect, however it falls below a center prior when we change question. It falls below chance if we remove textual context in the question, partly due to backbone attention leaving the object, while the head's map hardly changes. The backbone's states carry the location when probed with normal images, on the test-split images, however, the decision depends on the defect region. A larger

---

### [71] RICoT: Recurrent Interleaved Chain-of-Thought for Page Stream Segmentation

**链接**: https://arxiv.org/abs/2611.22382
**作者**: Prashant Khatri, Bhavana Malagavalli, Saiful Haq, Niyati Chhaya
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have renewed interest in Page Stream Segmentation (PSS), splitting a multi-page file into its constituent documents. Yet published LLM methods still frame the task as boundary classification over one or a few neighboring pages, and commercial document-splitting APIs do not disclose their methods. We reimagine PSS for LLMs as a sequential process over the whole stream and propose RICoT (Recurrent Interleaved Chain-of-Thought), a prompting framework that works through the pages as a reader would: within a sliding window it reasons about each page and commits its boundary decision before moving on, and across windows it carries forward a compact record of what it has read, keeping per-call cost bounded. We also introduce FinancePSS-205, a benchmark of 205 real-world, de-identified financial page streams, to be released publicly. On FinancePSS-205, RICoT matches or outperforms pairwise and windowed prompting with the same backbone for each of three open-weight 

---

### [72] Communicate the Change: Efficient Expert Parallelism via Activation Compression

**链接**: https://arxiv.org/abs/2611.22215
**作者**: Fengyuan Liu, Jay Gala, Siva Reddy, Dzmitry Bahdanau
**来源**: cs.LG cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling has driven the success of large language models (LLM), with sparse mixture-of-experts (MoE) architectures enabling greater parameter capacity without a proportional increase in computation. At large scales, MoE models rely on expert parallelism to distribute experts across devices. Each MoE layer requires two synchronous collective communication steps during inference: dispatching hidden states to the activated experts and combining the resulting expert outputs. As compute throughput has outpaced interconnect bandwidth, these synchronous collectives have become a major bottleneck to MoE scaling and efficiency. We address this challenge with EchoMoE, a lightweight architecture modification that retrofits existing MoE models, requiring approximately 8,500x fewer training tokens than full pretraining. Motivated by the observation that transformer blocks update the residual stream incrementally, we use a hidden state from an earlier layer as a reference and communicate only the com

---

### [73] Dynamic Task Allocation with Dialogue

**链接**: https://arxiv.org/abs/2611.23119
**作者**: Matthew Groholski, Weiwei Gu, Nakul Gopalan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective multi-agent collaboration requires agents to adapt task allocation as goals and responsibilities evolve. Prior task-allocation frameworks often assume static goals, full observability, or rely on large language models (LLMs) without explicit, verifiable beliefs about task allocation or intent. These assumptions limit their applicability to real-world collaboration, where agents often lack full information about each other's actions, progress, or local environment. To support dynamic task allocation under partial observability, we introduce a communication-augmented Bayesian task-allocation framework. Our agent uses dialogue to reduce uncertainty about the environment and collaborators, while keeping decisions grounded in explicit probabilistic beliefs. We evaluate our framework in an Overcooked domain extended with dynamically arriving tasks under both full and partial object-space observability. Our communication agent consistently outperforms a vanilla LLM agent in both set

---

### [74] Reliable Evaluation of AI Agents for Investment Research: A Framework for Performance and Validity Assessment

**链接**: https://arxiv.org/abs/2611.22338
**作者**: Dongnuan Tian, Yan Yu, Yangfan Liu, Wenjun Tang, Junting Kan, Xiang Wang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We consider the problem of evaluating AI agents undertaking investment-research tasks, where agents interact with external information sources and computational tools to produce financial analyses and research reports. An important challenge is that the quality of an agent's final output does not necessarily reflect the quality of its execution process, while the reliability of the resulting assessment also depends on the validity of the evaluation procedure. Furthermore, investment-research tasks differ considerably in their requirements for numerical accuracy, information retrieval, financial analysis and supporting evidence, making it difficult to assess agent performance using a uniform set of criteria. We propose a domain-oriented evaluation framework that distinguishes outcome quality from execution quality and accommodates these differences through task-specific criteria, deterministic validators and independent large language model judges. We also introduce an evaluation-validi

---

### [75] A Visual Information Extraction System Using Multimodal Large Language Models for Scanned Cognitive and Behavioral Assessments

**链接**: https://arxiv.org/abs/2611.22252
**作者**: Enshuo Hsu, Linh Nguyen, Sunyang Fu, Heath Goodrum, Sandra Stansberry, Kirk Roberts 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective. Paper-based assessments are common in patient care, but handwriting and scanning artifacts make these forms difficult to process at scale. This study proposes a modular, multimodal LLM-based system with human oversight for extracting fields and scores. We conducted a qualitative analysis of the use of LLMs for hand-drawing analysis. Materials and Methods. The system processes cognitive assessments (i.e., MMSE, MoCA, Mini-Cog) and the NICHQ Vanderbilt Assessment using two modules: 1) a form classifier that assigns a scanned page to a form type, followed by a corresponding 2) score extractor that extracts fields and scores into a schema. A human-in-the-loop design utilizing dual-model validation engages human annotators when two LLMs disagree, limiting manual review to challenging pages only. Results. End-to-end accuracy for cognitive assessments was 88%, with most form types exceeding 90%. For the NICHQ Vanderbilt, overall accuracy reached 97.5%, with all form types above 96%

---

### [76] OAK-Mind: Zero-Training Mental Health Change Inference from Passive Sensing via Knowledge-Grounded Multi-Agent LLMs

**链接**: https://arxiv.org/abs/2611.22248
**作者**: Yishu Ji, Zhihan Jiang, Will Ke Wang, Yuang Fan, Anind K. Dey, Xuhai "Orson" Xu
**来源**: cs.MA cs.AI cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wearable and smartphone sensors capture behavioral signals associated with mental health, yet inferring mental health outcomes from these signals has traditionally relied on supervised models requiring labeled data and offering limited insight into their predictions. Large language models (LLMs) offer new opportunities to reason over behavioral evidence, but existing LLM-based approaches to passive sensing have largely continued to rely on task-specific fine-tuning or sensor-specific pretraining. In this paper, we introduce \textbf{OAK-Mind}, a zer\textbf{O}-training, multi-\textbf{A}gent, \textbf{K}nowledge-grounded LLM pipeline for inferring mental health changes from passive sensing data. The pipeline organizes sensing data into behavioral dimensions including sleep, physical activity, location mobility, and smartphone use, and orchestrates specialized agents grounded in mental health literature to interpret longitudinal behavioral changes. It synthesizes their assessments and appli

---

### [77] CrisisBench: an evaluation suite for crisis counseling AI

**链接**: https://arxiv.org/abs/2611.21622
**作者**: Akshay Swaminathan, Filip Ramazan, Sharang Phadke, Kevina Wang, Ivan Lopez, Shaked Peleg Azzam 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Crisis helplines are essential to mental health systems but are often understaffed and underfunded. LLMs could support counselors, but existing benchmarks do not capture the escalation, risk assessment, and de-escalation central to crisis conversations, while privacy restrictions limit use of real transcripts. Methods: We present CrisisBench, a privacy-preserving suite for single- and multi-turn crisis counseling evaluation. It includes 1,085 single-turn tasks from 200 de-identified conversations and 1,185 patient LLMs derived from hotline metadata. Patient models and a 23-item LLM judge were calibrated against expert counselors. Results: We evaluated five GPT models plus draft-then-edit and retrieval-augmented generation. All systems underperformed human counselors on excessive empathy and questioning in single-turn evaluation. The rubric achieved human-human Krippendorff's $\alpha$ = 0.51 and LLM-human $\alpha$ = 0.54 (Pearson r = 0.80). In multi-turn evaluation, retrieva

---

### [78] AfriNORM: An Evaluation Benchmark for Normative Reasoning of LLMs Across African Cultures

**链接**: https://arxiv.org/abs/2611.22580
**作者**: Ahmad Samuel Gali (1), Tadesse Destaw Belay (2), Idris Abdulmumin (3), Seid Muhie Yimam (4), Shamsuddeen Hassan Muhammad (5 and 6) ((1) Independent Researcher, (2) Instituto Polit\'ecnico Nacional 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed across various sectors. However, current evaluation benchmarks are insufficient to assess the applicability of these models in local African contexts, as most focus on linguistic fluency (grammar/translation) rather than cultural competence. The few existing benchmarks that measure general knowledge or social conventions do not capture the African deontic modality, i.e., the strict norms and taboos that govern diverse social interactions. In this paper, we introduce AfriNORM, a scenario-based, multiple-choice question dataset designed to measure and diagnose the normative reasoning limitations of LLMs when applied to African sociocultural contexts. We introduce two metrics: a Universal Commonsense Bias Score (UCBS) to quantify commonsense bias in LLM and a Distractor Bias Score (DBS) to quantify an LLM's limited understanding of African cultural norms. We also conduct a case study on the Yor\`ub\'a language, identifying confusion g

---

### [79] RAG in a Trenchcoat: When Minimal Memory Is Enough for Agentic Systems, and When It Isn't

**链接**: https://arxiv.org/abs/2611.22179
**作者**: Jingyu Liu, Zongze Li, Zach Xu, Zhanhui Zhou, Tahseen Rabbani, Dawn Song 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic memory research has accumulated extraction, supersession, reflection, and graph synthesis on top of retrieval-augmented generation. However, we found that almost none of those primitives earn their cost in our tested memory benchmarks: we show this with BRIDGE, a deliberately minimal RAG memory with chained observation notes, hybrid BM25 with cosine retrieval, and chronological rendering, which reaches parity within bootstrap CI with the prior SOTA on LongMemEval-S and BEAM, and beats the best memory baseline on EverMemBench by 5.7-6.3 points at matched reader. It runs at ~5-7K reader-prompt tokens per query, using a single LLM call for each ingestion or query. We argue that this parity is itself the result: standard benchmarks score what memory retrieves, not what memory enables when the agent acts. To test the latter, we introduce five adversarial probes (Rule Application +-, Pattern Induction Style / Procedural, Dynamic Multiturn) judged at generation time by a cross vendor 

---

### [80] PVTSizing 2.0: A Fast and Reliable Analog Circuit Sizing Operator for Agentic EDA Workflows

**链接**: https://arxiv.org/abs/2611.22328
**作者**: Zichen Kong, Minghuan Song, Xiyuan Tang, Ziming Wei, Yi Zhong, Yuan Wang
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog circuit design automation requires both coordinated tool execution and efficient numerical search. Large language models (LLMs) offer new ways to organize tool execution, but finding one sizing that satisfies specifications across process, voltage, and temperature (PVT) corners remains costly. PVTSizing 2.0 addresses these needs through a human-agent workflow built around an independently usable numerical optimizer. An agent carries the designer's approved task through execution and result review. The optimizer reduces unnecessary training through loss-guided updates and uses critic-guided local refinement to explore additional candidates while accounting for cross-corner conflicts. An optional LLM adviser supplies parameter relationships to focus numerical search on circuit-informed directions, while the optimizer selects adjustment amplitudes and verifies their effects through simulation. Across four circuit benchmarks, the standalone optimizer completes all 40 runs and achiev

---

### [81] VRLLM: Turning LLMs into Powerful Tabular Classifiers

**链接**: https://arxiv.org/abs/2611.22308
**作者**: Yingtong Dou, Shubham Jain, Junpeng Wang, Hadi Abdullah, Vineeth Rakesh Mohan, Yuzhong Chen 等 (8 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown strong performance on text, but whether pretrained LLMs are effective for large-scale tabular classification remains unclear, as many previous works demonstrate that LLMs' tabular data classification performance falls behind tree-based models or neural architectures designed for tabular data. At Visa Research, we managed to fine-tune a pretrained Llama 3.2 1B LLM on billions of rows of labeled tabular data and make it outperform a wide array of tabular classifiers and even our competitive production deep learning model. For ease of reference, we refer to the model as the Visa Research LLM (VRLLM). In this paper, we share how we achieved this exciting result, covering data preparation, training recipe, ablation studies of design choices and deployment validation. We also benchmark frontier LLMs on the same task and analyze their prediction behavior across model families and generations. Our interpretability experiments suggest that VRLLM learns fe

---

### [82] NEBench R1: a Reasoning Benchmark for Evaluating Nuclear Domain Competence in Large Language Models

**链接**: https://arxiv.org/abs/2611.21682
**作者**: Liyan Wang, Longze Li, Mohamed Hassan, Isshu Lee, Dajie Sun, Ruimin Feng 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly being explored for knowledge-intensive and safety-critical applications in nuclear engineering. However, existing nuclear-domain benchmarks provide limited content coverage or focus primarily on answer accuracy without systematically evaluating the quality of the underlying reasoning. This study introduces NEBench R1, a reasoning-oriented benchmark comprising 7,546 unique multiple-choice questions extracted from U.S. Nuclear Regulatory Commission (NRC) reactor operator licensing examinations covering 18 nuclear facilities. Each question is classified according to the NRC Knowledge and Abilities catalogs and accompanied by an official explanation serving as a reference for reasoning evaluation. Six LLMs were evaluated, with overall accuracy ranging from 34.0% to 73.9% across three distinct performance tiers. To assess reasoning quality, an LLM-based judge evaluated correctly answered responses using a multidimensional rubric. Although respon

---

### [83] AI Companions for Young Adult Caregivers: Practical Advice, Emotional Depth, and the Limits of Metric Evaluation

**链接**: https://arxiv.org/abs/2611.23147
**作者**: Trizal Garg, Xuelong Fu, Dhruv Shah, Jin Huang, Shrigopal Maheshwari, Atiksh Aggarwal 等 (9 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Young adult caregivers (YACs) are individuals aged 18 to 25 currently taking care of a family member, partner, or friend facing chronic illness. AI companions designed specifically for YACs remain underexplored in prior works. We present Carebot, it uses an open-weight LLM (Gemma 3-27B) as its base model, on which we compared fine-tuning, retrieval-augmented generation (RAG), and a combination of both. The fine-tuning was performed based on an existing dataset of conversations with YACs and a psychologist. Three well-being experts evaluated these configurations and preferred the fine-tuned model for the warmth of its responses and its actionable advice tailored to YACs. Based on their choice, we adopted the fine-tuned model as Carebot's final configuration and used it for all subsequent evaluations. An LLM judge preferred this Carebot's responses over the base model's in 85% of evaluated pairs. We then conducted a user study with 90 YACs, half of whom interacted with the base model and

---

### [84] Rescaling OLS-Merged Adapters To Improve Personalized Image Generation

**链接**: https://arxiv.org/abs/2611.22969
**作者**: Leander Girrbach, Niklas Schweiger, Zeynep Akata
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Merging multiple adapters into a single image generation model reduces deployment costs while preserving diverse task capabilities or personalization modes. State-of-the-art methods such as RegMean, Mix-of-Show, and Subspace Routing fit the outputs of the merged model to those of the individual adapters using ordinary least squares (OLS). We show that this reconstruction objective systematically shrinks task-specific signals whenever the activation distributions of different tasks overlap, producing a merged adapter that is too weak for downstream use. We derive a decomposition that quantifies this shrinkage and propose rescaling the merged update to restore signal strength. On multi-subject personalization with up to 30 merged adapters, rescaling substantially improves subject fidelity over unscaled baselines. Our approach also improves results on style transfer, concept erasure, image classification, and LLM-based text classification.

---

### [85] Contract-Explicit Evaluation: From Auditing Learned Readers to Scoped Certificates

**链接**: https://arxiv.org/abs/2611.22665
**作者**: Hao Lu, Weixing Zhu, Ruiyang Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluation readings of document-level relation extraction (DocRE) systems depend jointly on the model and the evaluation contract: gold version, scoring function, threshold. Rankings reverse across contracts, yet no existing method determines which comparisons survive the reversal. We address this gap with contract-explicit evaluation: a preregistered five-step protocol (Declare, Measure, Scope, Certify, Hedge), operationalizing the classical concordance decomposition of Kendall's rank correlation, that scopes certifiable regions and delivers distribution-free census certificates across two ecosystems. In the DocRE audit (44 training runs of one in-house architecture family), the scoring dimension scopes to a census certificate (three flagged instances, Clopper--Pearson upper bound 0.146); the confirmatory record includes registered negatives, and the audit prices its own simplification finding---the calibration dial's entire margin is one withdrawn commit. In an LLM-judge census (17 j

---

### [86] Do LLMs Understand Network Traces? A Comparative Study of Reasoning over Raw and Filtered Traffic Data

**链接**: https://arxiv.org/abs/2611.22575
**作者**: Irene Gos\'alvez-White, Roberto Mag\'an-Carri\'on, Carlota de la Vega-Soriano, Pedro Garc\'ia-Teodoro
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The effective delivery and monitoring of ICT services rely heavily on network traffic analysis. However, interpreting complex packet captures remains a challenging task that requires substantial technical expertise. Large language models (LLMs) offer promising opportunities to automate network traffic in- vestigation, yet their reliability in packet-level field extraction and flow-level sequence reconstruction remains an open research question. This study proposes a reproducible, question-answering- based evaluation methodology to assess the capabilities of LLMs in network trace analysis. Using real-world benign traffic from the CICIDS2017 dataset, we evaluate multiple models against a human-generated ground truth, comparing their performance on raw textual traffic dumps and protocol-filtered representations. Model responses are assessed through an automated LLM- as-a-judge pipeline, validated against human evaluations. The results demonstrate that protocol filtering significantly redu

---

### [87] EviDARL: Evidence-Centric Dual-Agent Reasoning via Alternating Reinforcement Learning for Multi-Table Question Answering

**链接**: https://arxiv.org/abs/2611.22310
**作者**: Dunhan Li, Leilei Gan, Lirong Gao, Wenyan Fan, Yongwei Wang, Sheng Guo 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite advances in LLM-based table reasoning, most studies focus on single-table settings. Multi-table QA requires multi-hop reasoning over complex table relationships and evidence dispersed across long contexts, often without verifiable intermediate traces. To address these challenges, we introduce EviDA, an evidence-centric dual-agent framework comprising an Evidence Construction Agent and a Reasoning and Answering Agent. The Evidence Construction Agent generates and executes table-manipulation programs over complete tables to produce question-specific evidence and verifiable intermediate traces, simplifying subsequent reasoning. The Reasoning and Answering Agent then performs multi-hop reasoning over this evidence to derive final answers. We further introduce EviDARL, which combines agent-specific fine-grained rewards with parameter-efficient alternating reinforcement learning to improve collaboration between the agents. By optimizing each agent in turn while holding the other fixe

---

### [88] Right Diagnosis, Unsafe Route: Auditing Clinical AI Decision Trajectories and Corrective Oversight for Validity and Potential Harm

**链接**: https://arxiv.org/abs/2611.22612
**作者**: Guanqiao Chen, Wei Jiang, Shu Zhang, Qian Lin, Guanxu Yu, Siran Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A clinical AI system can reach a correct final diagnosis through intermediate decisions that could have harmed the patient, and can repair an error while introducing new risks. Most evaluations score final diagnoses; even stepwise benchmarks, which release a case's evidence over time, score whether systems reach the right diagnosis or gather the right information, not whether the decisions a patient passes through are safe. We make patient safety the target of stepwise evaluation. A trajectory audit replays real admissions checkpoint by checkpoint, lets each system decide with only the evidence released so far, and rates every test, treatment and disposition for its potential harm to the patient and, separately, for clinical validity, against the documented final diagnosis and physician-written disease rubrics yet on the evidence available when the decision was made. An LLM judge scores every decision, and a physician reference standard (triple annotation and senior adjudication of a s

---

### [89] GridDriver: On-Board BEV-Based Language Planning and Reasoning

**链接**: https://arxiv.org/abs/2611.21924
**作者**: Katharina Winter, William Engel, Zain A. Alishammat, Fabian B. Flohr
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bird's-Eye-View (BEV)-conditioned large language models (LLMs) enable language-interactive driving, but onboard deployment requires efficient perception and continuous planning alongside autoregressive language generation. We present GridDriver, an efficient BEV-conditioned LLM framework combining trajectory prediction, structured driving indicators, natural-language navigation, driving explanations, and scene question answering. Lightweight spatio-temporal BEV perception and spatially structured tokens provide scene context to a shared LLM, while frame-wise scheduling interleaves trajectory prediction with asynchronous language generation. GridDriver achieves competitive performance on public benchmarks, reaching 87.9% PDMS on NAVSIM and 57.6% accuracy on nuScenes-QA with a shared planning and QA checkpoint. Spatial representation analyses demonstrate improved geometric information retention and trajectory prediction compared with Q-Former compression. The system achieves 32.7 ms stan

---

### [90] The Resolution Hypothesis: Agent Evolution's Key Is Identifying Improvements

**链接**: https://arxiv.org/abs/2611.23068
**作者**: Yuanhao Zeng, Shaocheng Lan, Ao Lu, Kuang Yan, Heng Lin, Xinang Xu 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent evolution follows a simple loop: a proposer writes candidate artifacts (prompts, skills, memories) and selection accepts those that score higher. This loop has shown promise, yet practitioners face a puzzle: methods trade wins across papers, and evolution often fails to bootstrap on certain tasks. We trace this puzzle to the Resolution Hypothesis: agent evolution stalls not because methods fail to propose better artifacts, but because noisy evaluations cannot reliably identify them. Across seven evolution methods and six models (over 10M LLM calls), we find support for the hypothesis at both levels where evaluation scores are used. At the candidate level (choosing artifacts), helpful candidate artifacts exist, but selection is no better than random at telling them from harmful ones, so errors accumulate across rounds. At the method level (ranking methods), typical margins of a few percentage points are smaller than the difference between two independent runs of the same method, s

---

### [91] Supporting Researcher Control in AI-Assisted Social Media Analysis: A Mixed-Methods Study of AI4OSN

**链接**: https://arxiv.org/abs/2611.22006
**作者**: Qile Wang, Abhishek Karwankar, Shukria Muhammadi, Srikanth Kumar Perumalla, Abhin Suresh, Sunita Chandrasekaran 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-quality annotated datasets are critical for advancing computational social science (CSS) research, yet collecting, curating, and analyzing large-scale data from dynamic sources such as online social networks (OSNs) remains a persistent bottleneck. Researchers must also translate substantive questions into queries, relevance criteria, and defensible interpretations. Large language models (LLMs) can assist, but they can also obscure the judgments, potentially reducing researcher oversight and critical evaluation. We present AI4OSN, a mixed-initiative platform that keeps researchers in control of data collection, relevance labeling, and sensemaking while making AI assistance available as an inspectable advisory resource. In a systematic user study (N=18) using X/Twitter data, participants reported above-benchmark perceived usability (mean SUS score of 79.7), increased confidence in LLM-assisted annotation and analysis tasks, and low cognitive workload during AI-supported sensemaking.

---

### [92] JET: Just-Enough Exploration Tuning for Efficient Tool-Calling Agents in Repository-Level Question Answering

**链接**: https://arxiv.org/abs/2611.22539
**作者**: Yoonho Choi, Taehyeon Han, Seonghyeon Lee
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In repository-level question answering (QA), an agent explores a code repository with tools and should answer a question once enough information is gathered. Nevertheless, we find that LLM agents often continue to invoke tools even after the gathered information is already sufficient to answer. We call this phenomenon over-exploration. Moreover, even though existing methods improve task performance through supervised fine-tuning (SFT) on expert trajectories, SFT also propagates the over-exploration in the trajectories to the agent. To mitigate over-exploration, we propose Just-Enough Exploration Tuning (JET), a fine-tuning method that trains the agent to answer once the gathered information is sufficient. JET truncates each training trajectory at the step where the gathered information becomes sufficient, inserts a rationale that explains why the agent can answer at that step, and fine-tunes the agent with a higher loss weight on the rationale. Experiments on two repository-level QA be

---

### [93] The Shared Word: Evaluating Language Models on Dutch Word Puzzles

**链接**: https://arxiv.org/abs/2611.22935
**作者**: Rik van Noord, Maurice Voors
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many LLM benchmarks for languages other than English are translated, multiple-choice, or difficult to score automatically. We introduce The Shared Word (TSW-NL), a Dutch benchmark built around four core principles: it is language-specific, open-vocabulary, human-curated, and deterministically scored. Each puzzle gives three clues that describe different senses or uses of the same Dutch word. The clues are individually ambiguous, requiring the solver to combine evidence across multiple clues. We construct the benchmark from Dutch Wikipedia disambiguation pages, followed by automatic filtering and extensive manual curation. The final dataset contains 222 instances, with three independent human answers per test item. The task is clearly challenging: scores in our human study range from 49.5% to 61.0% and the highest-scoring open-weight model we tested reaches only 39.3%. Many others even score below 20%. At the same time, closed-source models show great progress: GPT-4.1 (April 2025) scor

---

### [94] EvoDisco: Strategy Discovery for Evolving Agent Memory

**链接**: https://arxiv.org/abs/2611.22102
**作者**: Mingyang Liu, Qingcan Kang, Shixiong Kai, Kaichao Liang, Xiaojin Fu, Tao Zhong 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents accumulate experience in memory, and how that memory evolves during interaction is as important as what it stores. Recent methods update memory online, yet both the operators that transform memory and the rules that select them remain fixed by design. We propose EvoDisco, which formulates agent memory evolution as evolutionary strategy discovery: the agent must discover which operator to apply, when to apply it, and how to instantiate it, rather than rewriting memory under a static operator schedule. A learnable policy conditions on the current memory state and recent task history, then selects and instantiates one of four semantic operators---Abstract, Refine, Bridge, and Reframe---which respectively compress related memories, decompose overloaded entries, connect weakly linked experiences, and reorganize retrieved reasoning chains. The policy is updated with a bi-level fitness. An inner signal scores each transformation using a retrieval-quality improvemen

---

### [95] Worldviews in Large Language Models

**链接**: https://arxiv.org/abs/2611.22670
**作者**: Edmundo Lopez-Sola, Shamil Chandaria, Ruben Laukkonen
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are often described in terms of personas and this framing has become central to alignment research. In this paper, we argue that there is a deeper level of description that lies in the agent's worldviews, i.e., its beliefs about what reality is and how it works. Treating LLMs as a population of subjects, we administer two worldview surveys from human psychology to eight models. We show that the models share many key worldview positions. For example, LLMs consistently describe the world as less good, safe, enticing, and alive than humans do. On the other hand, base models have a more positive outlook, suggesting that the bleakness we found is driven by post-training. In line with research on LLM "personas", we show that system prompts eliciting different identities shift worldviews in consistent directions, and that a contemplative prompt creates a more positive outlook and improves safety. We also found that dialogue between models consistently shifts world

---

### [96] Mind the Gap: A Deployed Multi-Agent System for Documentation Maintenance

**链接**: https://arxiv.org/abs/2611.23142
**作者**: Lorenzo Masoero
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The "AI revolution" has enabled teams across the technology industry to deliver software features at unprecedented velocity. While code evolves faster than ever, customer-facing documentation often struggles to stay up to speed. As users increasingly rely on LLM-based agents that consume documentation as their primary interface, the impact of this documentation gap worsens: stale information propagates and is treated as authoritative. Signals for identifying where documentation has fallen behind already exist in abundance, both explicit (e.g., resolved support tickets revealing what documentation lacks) and implicit (e.g., code-documentation discrepancies detectable from automated loops). We deploy a multi-agent system, built around a triage agent we call "TriAgent," that continuously extracts these signals and repairs documentation drift. Over 43 days of shadow-mode operation, our system triaged 499 tickets and surfaced 92 gaps in the documentation. Using a panel of LLM judges from in

---

### [97] Where Does Hindsight Enter Clinical Agent Benchmarks? An Audit of Simulators and Case Construction

**链接**: https://arxiv.org/abs/2611.22241
**作者**: Meilu Zhu, Xiaohan Li, Axiu Mao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarks for LLM diagnostic agents are built from retrospective records: the case an agent reads is rewritten from discharge summaries, and unrecorded test results are generated by a simulator that often sees the final diagnosis. HindAudit separates three hindsight channels (the diagnosis given to the simulator, the retrospective context it conditions on, and the agent-facing case text) and measures each with judges trained only on real data. On 27,489 emergency admissions from MIMIC-IV, five registered tests found no leakage into simulated laboratory results: providing the diagnosis to five simulators had a negligible effect, and prompted gatekeepers diluted the diagnostic signal, although exploratory results suggest they can raise agent scores. The largest effect lay in the case text. Against a presentation-time reconstruction from triage records, benchmark-style summaries raised the zero-shot accuracy of four LLMs from 25.4% to 39.7% and discharge histories to 45.3%, and raised si

---

### [98] Large Language Models Have Not Yet Transformed Science

**链接**: https://arxiv.org/abs/2611.22975
**作者**: Ron Bekkerman, Nichole Li, Bahareh Kargar, Mark Somers
**来源**: cs.CL cs.AI cs.CY cs.DL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The emergence of large language models (LLMs) in late 2022 has raised questions about the future of science, but assessing their impact requires understanding how scientific practices were already evolving. We analyze 2.5 million full-text papers across five disciplines from 2015 to 2025, tracing trends over a broad spectrum of lexical, structural, epistemological, and social dimensions. Aside from frequency shifts in some words, most pre-2023 trends continued with limited detectable breaks. Among the notable exceptions, growth in computer science coauthor teams accelerated significantly in Asia, while apparent declines in biomedical topic diversity largely reflected standardization in article formats. Our study establishes an empirical foundation for monitoring the health of global science as LLM adoption deepens.

---

### [99] DailyBrick: Language-Guided Synthesis of Brick Assembly Instructions

**链接**: https://arxiv.org/abs/2611.22132
**作者**: Hang Zhang, Qijian Tian, Yuan Xie, Xuhong Wang, Xin Tan
**来源**: cs.RO cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating a LEGO model from a user request is more than a plausible 3D shape generation. LEGO models require physical support per brick, and each brick should be placed unblocked. Current methods address this issue by training an expert large language model. We reduce the problem of generating extremely long context on all brick connections to that of writing a program that builds LEGO models like a human, considering each intermediate step could be executed. We introduce DailyBrick , a multi-stage agentic system that produces a LEGO model together with a brick-by-brick assembly instruction for human building and robot assembly. We design a multi-stage harness with roles to help LLMs generate more effectively. A versioned construction SDK compiles multi-level decisions, from semantic subparts to individual bricks, into canonical operations. An external Meta-Reviewer agent replays and inspects the generated package, verifies the model and its construction process, identifies failures, 

---

### [100] Evaluating Semantic Insensitivity in Financial Sentiment Analysis: Implications for Sustainable Financial Decision-Making

**链接**: https://arxiv.org/abs/2611.21653
**作者**: Gabriela Cioboata and Teodor-Stefan Bildea
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial sentiment analysis is critical for automated trading, portfolio management, and risk assessment, heavily relying on models like FinBERT. Despite high benchmark accuracy, these models remain vulnerable to subtle adversarial text modifications, threatening the integrity of algorithmic decision-making. In this paper, we propose Agent-driven Semantic Inversion (ASI), a novel adversarial attack framework targeting financial sentiment models through domain-specific semantic manipulation. Utilizing an LLM-powered multi-agent pipeline, our approach identifies eligible financial news sentences and applies targeted lexical substitutions. We empirically evaluate ASI against FinBERT, one of the most widely deployed financial sentiment models. Our results reveal a striking vulnerability: the attack successfully deceived FinBERT in 90.85% of eligible cases, with the model frequently maintaining its original sentiment prediction despite the fundamental inversion of financial performance ind

---

### [101] BugGen 2.0: Rethinking the Roles of LLMs for Scalable RTL Bug Synthesis

**链接**: https://arxiv.org/abs/2611.23091
**作者**: Minh Luu, Michael Quinn, Aakash Tyagi, David Houngninou, Jiang Hu
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-assisted RTL localization and debugging need ground-truth bug datasets with known locations and observable failures, while testbench grading uses injected bugs to measure detection capability. Creating such datasets at scale remains a major EDA challenge. BugGen 1.0 shows that Large Language Models (LLMs) can generate context-aware RTL mutations. Still, it relies on the model for both choosing where to mutate and generating the edit, which increases inference costs and can lead to invalid choices. BugGen 2.0 changes this division of labor. Deterministic algorithms handle structural analysis, target selection, and validation, while the LLM focuses on localized semantic rewriting. Across four OpenTitan IP blocks and FabScalar with three LLMs, BugGen 2.0 reaches every requested quota of compilable bug scenarios that cause at least two test failures, with 14-16 of 16 configured mutation types represented. In completed same-model comparisons, it reduces token use by 6.8x-15.4x relative t

---

### [102] Weight-space programming for tractor guidance controller: large language models natively write neural network weights that steer a real tractor

**链接**: https://arxiv.org/abs/2611.21958
**作者**: Timo Oksanen
**来源**: cs.LG cs.AI cs.RO cs.SY eess.SY
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-space programming is a process where a large language model reads and writes the weights of a neural network directly, guided by a natural language specification, without an optimiser or gradient descent. This study applies it to automatic tractor guidance, where a 253-parameter neural network steers along paths of lines and arcs and must be adapted when the machine changes, such as a slower steering actuator. GPT-6 Astra and Claude Fable 5.1 (also 5.2) edited the network for our research tractor using a small budget of simulated evaluations to repair a network trained for another tractor and write a controller into a network with zero weights. We compared them with an evolution strategy, gradient descent and pure pursuit in simulation and on the real tractor. Both models read the network and analysed the closed loop with control theory correctly, and Fable's repair without simulation succeeded only occasionally. With simulated feedback, both models repaired the trained network 

---

### [103] Deal With It: On Better Schedules for Listwise Reranking

**链接**: https://arxiv.org/abs/2611.22392
**作者**: Benjamin Clavi\'e and Herumb Shandilya and Hanna Lichtenberg and Aamir Shakir and Makoto P. Kato
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Listwise LLM rerankers cannot reliably rank hundreds of documents in a single call, and rely on schedules to orchestrate their calls. Parallel schedules split candidates into groups and advance a fixed quota from each. When a group holds more of the top passages than its quota, some are cut, and expensive repair calls become required. We show that the way candidates are split matters where such a quota can bind, and that, in expected cuts, the best split there deals them round-robin by retriever rank, like cards. Although not conceptually new, dealing has remained unanalyzed. We prove that, under a simple retriever model, no split with equal quotas cuts fewer of the true top ten on average, and that contiguous chunks cut more as the retriever improves. DealRank, the simplest schedule our analysis allows, is on average within 0.1 nDCG@10 points of the best schedules over six LLMs, in two rounds. It is consistently 1.1 to 1.4 times faster than BlitzRank with concurrent first calls up to 

---

### [104] Compact and Decodable Electrocardiogram Text for Large Language Models

**链接**: https://arxiv.org/abs/2611.22827
**作者**: Elif Dorukba\c{s}{\i}, \.Ilker T\"urker
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a twelve-lead electrocardiogram is written as text for a large language model, the number of tokens has to be balanced against the information lost through compression. This paper presents a deterministic encoding that writes eight independent leads as amplitude letters and exact time gaps and recovers the remaining four limb leads algebraically. The key points are selected with a cardiac-cycle-dependent tolerance, the amplitudes are parameterized by a 26-letter logarithmic codebook learned from a training set, and a 10-step tolerance schedule keeps all records within a fixed token budget. The encoding was applied to 21,388 records from the public PTB-XL database and evaluated using an exact decode-and-re-encode round trip, waveform reconstruction error, and a paired comparison of convolutional classifiers trained with 5 different seeds on signals from the original and decoded databases. All records were contained in 4,080 tokens (average: 2,866 tokens, 64.3% fewer than a per-samp

---

### [105] Corrupting Ties: Investigating Robustness to Bias Injection Across Multi-Agent Network Topologies

**链接**: https://arxiv.org/abs/2611.21804
**作者**: Cl\'ea Chataigner, Mina Arzaghi, Florian Carichon, Pablo Piantanida, Golnoosh Farnadi
**来源**: cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI systems are increasingly deployed in high-stakes decision-making contexts, where interactions among components can introduce fairness risks that remain undetected when auditing components or collective outcomes in isolation. As LLM-based multi-agent systems become more prevalent, understanding how biased information propagates through agent interactions is essential for assessing their fairness. We introduce a controlled bias injection framework that replaces selected agent responses with predefined biased ones, enabling an intervention-based analysis of how network topology and injection configurations shape system behavior. We propose decision divergence metrics that quantify the effects of these interventions at the agent, network, and system levels, and evaluate five topologies on three binary classification tasks using LLMs from the Qwen and Gemma families. Sequential networks show the greatest divergence, whereas fully connected and mesh networks show less. Injection position 

---

### [106] Bookkeeping Is Not Judgement: EJBench, an Engineering Judgement Benchmark Built from a Conjugate Heat Transfer Design Campaign

**链接**: https://arxiv.org/abs/2611.21707
**作者**: James Sadler, Rotimi Alabi, Kotub Uddin
**来源**: cs.CE cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce EJBench, a benchmark of engineering judgement: whether a model can predict how a design behaves at new conditions from a few earlier results, and decide on it. Unlike engineering benchmarks that test whether an agent can operate simulation or CAD software, EJBench is software-agnostic and asks what an engineer would conclude without running a simulation. Its tasks come from a conjugate heat transfer design campaign for battery cold plates, in three families: matching unlabelled test results to their operating points, choosing which stored runs to reveal before signing off a design, and ranking new duties by peak cell temperature. Every answer is taken from a converged simulation, not from an LLM judge. The best of ten frontier models, GPT-6 Astra, scores 0.71, and models state almost the same confidence on tasks they get wrong as on tasks they get right. We also post-train Qwen3.5-9B with LoRA and reinforcement learning, rewarded by the share of answer criteria the simulat

---

### [107] Evaluating the Evaluation of Music Generation Models with Generative Psychometrics

**链接**: https://arxiv.org/abs/2611.21809
**作者**: Jo\~ao Carlos Santana Silveira, Caio Von Rondow Morais, Frederico Pedrosa, Lucas N. Ferreira
**来源**: cs.SD cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Subjective user studies are one of the major methods for evaluating music generation models. However, subjective evaluation protocols vary widely and are rarely specified in enough detail to be reproduced, hindering comparison across studies. In this paper, we map subjective evaluation methods in ISMIR music generation papers from 2020-2025 and apply generative psychometrics to assess the stability of their items. We extract 284 items from the papers' methodological descriptions, using an LLM and manual validation to standardize them. We represent these items as contextual embeddings and apply Unique Variable Analysis to remove redundant, locally dependent items and Bootstrap Exploratory Graph Analysis to estimate their latent dimensions. Results show the network converges onto a taxonomy of six stable quality dimensions: Rhythm, Melody, Audio, Composition, Structure, and Lyrics, pointing to a unified methodology for conducting user studies to evaluate music generation models.

---

### [108] SEAM: Computer-Use Agents Know the Harm Between Screens, and Commit It Anyway

**链接**: https://arxiv.org/abs/2611.22971
**作者**: Yuxuan Zhou, Chen Xiong, Haitong Liu, Kuofeng Gao, Yang Bai, Zhiyuan He 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety benchmarks for computer-use agents (CUAs) place the harm either in the intent of the task or on a single screen: a malicious instruction, an injected command, a phishing page. An agent that checks the task and each screen in isolation can pass them, so they do not test whether it combines facts seen on different screens. Yet in delegated work, harm often arises exactly this way: a fact about a person on one screen, a fact about an item on another, and a legitimate task that binds them. We introduce SEAM (Safety Execution Across Multiple screens), a benchmark of such cross-screen compositional harm: 600 multi-step, cross-application OSWorld tasks in which the instruction and every single observation are benign and only their combination is harmful. Minimal-pair variants that differ in one place, scored from the server log rather than by an LLM judge, locate where an agent fails. General-purpose open-weight and flagship agents carry out the harm in up to 92% of runs, yet decline w

---

### [109] RFW-S: Everyday Deformable Objects with Independent Simulation Verification

**链接**: https://arxiv.org/abs/2611.23056
**作者**: Jiarui Guo, Saining Zhang, Jiaying Wan, Jiawei Weng, Junhao Chen, Rui Zhang 等 (10 人)
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large-scale robotic simulation requires diverse deformable objects with executable physical properties and realistic interaction behaviors. However, existing 3D asset collections primarily emphasize visual diversity, while scalable physical construction and verification remain challenging. We introduce RFW-S, a large-scale dataset of 83,365 simulation-verified assets spanning 485 everyday categories across five structural families: soft solids, cloth sheets, shells, garments, and bags. We develop an automated pipeline integrating reference-guided 3D generation, structure-aware physical modeling, and LLM-assisted parameter estimation and calibration. To ensure physical reliability, we introduce an independent simulation verification framework that evaluates object behaviors under interactions distinct from those used for parameter calibration. Extensive experiments demonstrate the effectiveness of independent verification and characterize deformable responses under different physical co

---

### [110] Asking What Matters: Disagreement-Guided Ambiguity Detection for Interactive Text-to-SQL

**链接**: https://arxiv.org/abs/2611.21645
**作者**: Su Dong, Jiayan Lin, Yujia Liu, Zijin Hong, Qinggang Zhang, Feiran Huang 等 (7 人)
**来源**: cs.DB cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interactive text-to-SQL requires an LLM agent not only to generate executable SQL, but also to decide which uncertainty to clarify within a limited interaction budget. However, current clarification policies have three limitations: (i) they target surface ambiguity without testing its SQL impact; (ii) they miss ambiguities implicit in schema routes or domain knowledge; and (iii) they spend limited turns on unfocused or redundant questions. These limitations expose a critical challenge: identifying SQL-impacting ambiguity before the intended SQL is known. In this paper, we propose DisGuAD, a Disagreement-Guided Ambiguity Detection framework that specializes clarification selection. DisGuAD treats disagreement among plausible SQL interpretations as direct evidence of which uncertainty matters to the final query. Specifically, it constructs a query-term inventory, elicits contrastive SQL interpretations through complementary probe families, compares their canonical SQL components, and att

---

### [111] OmniTongue: A Comprehensive MLLM Benchmark for Automated Tongue Diagnosis in Traditional Chinese Medicine

**链接**: https://arxiv.org/abs/2611.22652
**作者**: Liuyi Xu, Yun Guo, Shusheng Li, Xuewen Zhang, Yining Qian, An-Yang Lu
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) have excelled in Western medical imaging, yet their potential in Traditional Chinese Medicine (TCM) tongue diagnosis remains systematically unevaluated. Tongue diagnosis requires sophisticated global and local perception, serving as a rigorous touchstone for assessing the visual understanding depth of MLLMs. However, existing datasets are limited by single dimensions, coarse granularity, and ambiguous labels, hindering the evaluation of authentic clinical capabilities. To bridge this gap, we introduce OmniTongue, the first comprehensive, fine-grained Visual Question Answering benchmark for TCM tongue diagnosis. This benchmark integrates 1,351 expert-validated images and 21,616 instruction pairs. Its core design features 16 clinical dimensions for multidimensional evaluation, region-specific annotations for pathological localization, and 66 fine-grained labels for precise diagnostic representation. Extensive evaluations of existing MLLMs reveal s

---

### [112] Diagnosing and Correcting Bias in MLLM for Long Video Understanding

**链接**: https://arxiv.org/abs/2610.36210
**作者**: Xusheng Liang, Jianqiao Sun, Hao Zhang, Yulei Niu, Hengshuang Zhao, Jiawei Ma
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] FVScore: Specification-Driven Neuro-Symbolic Video Evaluation

**链接**: https://arxiv.org/abs/2611.22673
**作者**: Do Xuan Long, Long T. Le, Yiwen Song, Min-Yen Kan, Tomas Pfister, Yale Song
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Faithfulness Video Score (FVSCORE), a neuro-symbolic framework for specification-driven video generation evaluation. Existing evaluators rely on holistic MLLM judgments or vision-language metrics, yet aligning their scores with human judgments and tracing them to specific temporal violations remain open challenges. FVSCORE addresses these limitations by compiling each video into explicit propositions capturing prompt requirements and implicit propositions capturing unstated physical, temporal, and cross-modal constraints. It grounds each proposition using specialized perceptual tools and evaluates the resulting confidence traces with soft temporal operators inspired by Linear Temporal Logic. A Significance-Aware Calibration step then aligns verification with human perception by retaining only perceptually significant violations before producing a timestamp- and evidence-grounded report. We conduct extensive experiments across public and complex multi-event benchmarks with 

---

### [114] EE-Motion: An EEG-based Web Architecture for Live Affective Music Recommendation

**链接**: https://arxiv.org/abs/2611.21032
**作者**: Sabino Roccotelli, Potito Aghilar, Vito Walter Anelli, Alejandro Bellog\'in, Tommaso Colafiglio, Michelantonio Trizio 等 (7 人)
**来源**: cs.IR cs.HC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] Beyond Reconstruction: A Unified Framework for Trustworthy and Explainable EEG Artifact Removal Evaluation

**链接**: https://arxiv.org/abs/2611.21781
**作者**: Phat Lam, Hung Nguyen, Lam Pham, Huy Phan, Dat Tran, Ian McLoughlin 等 (8 人)
**来源**: eess.SP cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep-learning methods have achieved strong performance in EEG artifact removal, but evaluation remains dominated by reconstruction metrics such as error, correlation, and signal-to-noise ratio. Although these metrics assess similarity to clean EEG, they do not establish whether models effectively suppress artifacts, preserve neural activity, or provide reliable explanations. To address these limitations, we propose TriX-EEG, a three-level framework for trustworthy and explainable EEG artifact removal. Level 1, Signal Validity (SV), evaluates reconstruction quality and neural band-power preservation. Level 2, Removal Faithfulness (RF), assesses the removed component through artifact error and residual artifact/neural leakage. Level 3, Explanation Reliability (ER), examines model behavior through temporal alignment, causal relevance, and stability. We evaluate TriX-EEG using nine published neural denoisers across three public benchmarks derived from EEGDenoiseNet and the PhysioNet Motion

---

### [116] A 1000-hour EEG-EMG-audio dataset of Japanese speech production

**链接**: https://arxiv.org/abs/2606.01264
**作者**: Motoshige Sato, Ilya Horiguchi, Masakazu Inoue, Kenichi Tomeoka, Eri Hatakeyama, Yuya Kita 等 (9 人)
**来源**: q-bio.NC cs.HC cs.SD eess.AS eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [117] Sleep2Word: Peripheral-to-EEG Translation via Duration-Aware Wordization

**链接**: https://arxiv.org/abs/2611.21643
**作者**: Keondo Park, Arthur Delhaye, Younghoon Na, Hyun-Woo Shin, Hyung-Sin Kim
**来源**: cs.CL cs.SD eess.AS
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Estimating full-night electroencephalography (EEG) spectrograms from peripheral measurements could extend EEG-informed sleep analysis to recordings acquired without EEG. This task requires compact representations of signals with different temporal structures. We introduce Sleep2Word, a framework for translating respiration, electrocardiography (ECG), or photoplethysmography (PPG) into EEG spectrograms through duration-aware physiological words. Building on context-dependent chunking, Sleep2Word groups physiological embeddings into variable-duration chunks and jointly quantizes their content and duration into modality-specific wordbooks. A block-autoregressive translator then predicts target EEG word identities and occurrence-specific duration refinements within fixed-duration blocks. This design accommodates independent source and target wordbooks, limits temporal drift, and shortens the autoregressive decoding path. Trained on over 20K PSG cases across 9 datasets, Sleep2Word consisten

---

### [118] Thought-deciphering via hierarchical EEG-to-text alignment

**链接**: https://arxiv.org/abs/2611.03623
**作者**: Xiaopeng Mao, Morten M{\o}rup, Xin Xu, Sang Wan Lee, Sadasivan Puthusserypady
**来源**: cs.LG eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] REEL: Brain-Guided Video Generation and Selection by Reranking Encoder Embeddings with Linear Decoding from fMRI data

**链接**: https://arxiv.org/abs/2611.21907
**作者**: Fabrizio Spera, Tommaso Boccato, Moein Khajehnejad, Nicola Toschi, Matteo Ferrante
**来源**: cs.CV
**匹配关键词**: Brain Decoding
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual brain decoding from functional magnetic resonance imaging (fMRI) data has made remarkable progress in recent years, driven by increasingly powerful artificial intelligence (AI) models and the growing availability of large-scale public datasets. However, despite the impressive advances achieved in static image decoding, the reconstruction of videos from fMRI signals remains challenging due to the temporal mismatch between rapidly changing video stimuli and the slow dynamics of the blood-oxygen-level-dependent (BOLD) response. We evaluate a Bayesian-inspired proposal-and-rerank strategy on CC2017 and the BOLD Moments Dataset (BMD), using a linear semantic decoder, a pretrained video generator, and three neural encoding streams with ridge readouts and learned pooling in two streams. We refer to this framework as REEL (Reranking Encoder Embeddings with Linear decoding). Compared with a single generated candidate, reranking increases mean Video 50-way accuracy from 0.2359 to 0.2434 a

---

### [120] SARVIA: Fast-Adapting the Strong SAR Foundation Models That Are Already in Your MLLMs

**链接**: https://arxiv.org/abs/2611.22273
**作者**: Yuxuan Li, Zichen Tian, Qianru Sun
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic aperture radar (SAR) foundation models provide transferable representations for diverse perception tasks in all-weather Earth observation. However, their development often relies on costly large-scale SAR pretraining, raising the question of whether such extensive domain-specific pretraining is necessary. We find that modern multimodal large language models (MLLMs) already provide visual encoders that can outperform dedicated SAR foundation models as downstream initializations. This motivates a new paradigm: reuse general visual capabilities and devote domain training to brief specialization. We therefore introduce SARVIA, an adaptive post-pretraining method that specializes modern MLLMs using self-supervised visual questions with computable answers. These questions are constructed from unlabeled observations through general image tasks that capture spatial relations and SAR-specific tasks that exploit native measurements and SAR--optical correspondence. A shared answer-predi

---

### [121] The Economics of AI Foundation Models: Openness, Competition, and Governance

**链接**: https://arxiv.org/abs/2510.15200
**作者**: Fasheng Xu, Xiaoyu Wang, Wei Chen, Karen Xie
**来源**: econ.TH cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Impact of Pretraining Length, Model Size, and Annotation Budget on Downstream Clinical Tasks of Foundation Models in Radiotherapy

**链接**: https://arxiv.org/abs/2611.22896
**作者**: Alejandro Cortina Uribe, Sidsel H{\o}jklint Poulsen, Ivan Richter Vogelius and Jens Petersen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cone-beam CT (CBCT) scans acquired during radiotherapy capture changes such as tumor shrinkage and radiation-induced tissue changes, offering great potential for foundation models that help monitor individual treatment responses. However, to our knowledge, no large-scale pretrained models for radiotherapy CBCT exist, and evaluating modeling choices is difficult since downstream tasks are not known in advance. We examine how pretraining length, model size, and finetuning strategy relate to downstream clinical performance, and how metrics tracked during pretraining correlate with it. We pretrain vision transformer encoders with masked image modeling on about 150,000 raw 3D radiotherapy CBCT scans, tracking representation quality via validation loss, effective rank, and linear probing. Downstream tasks are classification of feeding tube presence ($n=51,135$ CBCTs, $1,562$ patients) and clinical characteristics (T-, N-stage, sex, age, tumor site; $n=1,278$ patients) in head and neck cancer

---

### [123] Forecasting Retail Sales at Every Grain: Trees, Foundation Models, Transformers and World Models Compared on Four Public Data Sets

**链接**: https://arxiv.org/abs/2610.25170
**作者**: Karthik Iyer, Madan Dabbeeru
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] Feature Selection for Tabular Foundation Models: Exploring Feature Utility in Low-Data Molecular Prediction

**链接**: https://arxiv.org/abs/2609.30789
**作者**: Yiqi Yao, Miquel Duran-Frigola
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [125] UniE2F: A Unified Diffusion Framework for Event-to-Frame Reconstruction with Video Foundation Models

**链接**: https://arxiv.org/abs/2602.19202
**作者**: Gang Xu and Zhiyu Zhu and Junhui Hou
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] OpenMHC: Accelerating the Science of Wearable Foundation Models

**链接**: https://arxiv.org/abs/2607.16235
**作者**: Narayan Schuetz, Yuze Bai, Lianggang Pan, Edgar Eggert, Favour Nerrise, Juan Delgado-SanMartin 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [127] An Open-Source Training Dataset for Foundation Models for Hyperparameter Optimization

**链接**: https://arxiv.org/abs/2605.23417
**作者**: Aaron Klein, Herilalaina Rakotoarison, Luca Thale-Bombien, David Salinas
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] Must You See Fakes to Catch Fakes? Language Says What to Look For, Real Images What to Ignore

**链接**: https://arxiv.org/abs/2611.22650
**作者**: Tianchi Xu, Yuxuan Zhou, Yuheng Zhang, Yanan Guan, Tao Dai, Shu-Tao Xia
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Must a detector see generated images in order to catch them? Detection of AI-generated images has long faced two problems. The cues a detector learns from the few generators in its training set carry traces specific to those generators and transfer poorly to new ones, which limits generalization. The real and generated training images also differ in format and content, so the detector takes these differences as evidence of authenticity, and its decisions change with factors that have nothing to do with authenticity, which harms robustness as well as generalization. Both problems stem from training on generated images. A detector never trained on them can largely avoid both at the source. Vision foundation models have already learned the concept of "AI-generated" during pretraining, and text can point to it directly. Building on this, we propose SaySee, a training-free detector: Say builds a generation direction from sets of paired descriptions that differ only in authenticity and score

---

### [129] AR-WAM: efficient streaming world-action modeling for autonomous driving

**链接**: https://arxiv.org/abs/2611.21851
**作者**: Baiting Luo, Shatadal Mishra, Ahmadreza Moradipari, Nejib Ammar
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous driving requires anticipating how traffic will evolve while responding quickly to new observations. Video foundation models offer the first ability, but repeated history encoding and iterative video generation make them costly to use for driving. We present AR-WAM, an efficient streaming world-action model that combines autoregressive temporal modeling with single-pass future conditioning. Because its video backbone is causal, AR-WAM updates its visual context incrementally, reusing past computation and conditioning future prediction on observed motion. We further hypothesize that future features computed from recent observations can improve generalization in dynamic traffic without iterative video generation. AR-WAM therefore obtains these features in one forward pass and uses them to condition trajectory generation, and reinforcement learning then improves the policy through direct optimization of driving rewards. With a single front camera, AR-WAM achieves 91.5 PDMS after

---

### [130] SCAN: Site-Aware Collaborative Privacy-Preserving Adaptation of Vision-Language Models for Neurological Disease Classification

**链接**: https://arxiv.org/abs/2611.21955
**作者**: Nikhil J. Dhinagar, Rishab Pendam, Harmony S. Cen, Sophia I. Thomopoulos, John P. John, Mahir H. Khan 等 (10 人)
**来源**: cs.CV eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Worldwide neuroimaging data could strengthen diagnostic foundation models, but privacy rules often prevent centralizing brain MRI scans. We present SCAN, a site-aware collaborative adaptation framework for Neurological Disease Classification that lets new sites adapt a 3D medical vision-language model (VLM) without retraining or sharing patient scans. Each site keeps exact class prototypes for local prediction and can share privacy-protected class summaries: norm-bounded sums and counts perturbed once with calibrated noise. Using 7,641 scans from 67 sites across 12 countries, covering Alzheimer's disease (AD), stroke, epilepsy and controls, we assess local adaptation, cross-site benefits, and effects on existing sites. At seven unseen sites, the frozen VLM's zero-shot AUCs were 0.833-0.945 for AD and stroke. Training-free local prototypes improved epilepsy AUC at three sites from 0.598/0.625/0.508 to 0.684/0.729/0.762 and AD AUC at one site from 0.833 to 0.863, nearly matching a classi

---

### [131] DARWIN: a Geospatial Foundation Model for Marine Intelligence

**链接**: https://arxiv.org/abs/2611.22496
**作者**: Coen van den Elsen, Laurens Geffert
**来源**: cs.AI physics.ao-ph
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present DARWIN, a geospatial foundation model for marine intelligence. Recent Earth-observation foundation models have concentrated on terrestrial domains. The marine realm poses distinct challenges: missingness, multi-modal physical and biogeochemical variables, sparse labels, and dynamics that are transient, multi-scale, and non stationary over time. DARWIN adapts a masked-autoencoder backbone to these properties through missingness-aware encoding, expanded spatial and temporal masking, and Fourier-style positional embeddings, and is pretrained on 26 years of global Copernicus reanalysis together with GEBCO bathymetry. On predicting chlorophyll-a, the pretrained backbone attains the lowest monthly relative error in every month of 2022, outperforming both no-encoder baselines and an identically architected random-init encoder. At 10% of the supervised training data, DARWIN already surpasses the random-init model trained on 100% of the data. Embedding analysis and qualitative recons

---

### [132] PhyVGGT: Feed-Forward Articulated Object Reconstruction from Monocular Videos

**链接**: https://arxiv.org/abs/2611.22244
**作者**: Qi Shao, Zhihao Cao, Shuhao Zhai, Anh Nguyen, Hong Liang, Baoru Huang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reconstructing an articulated object with its 3D movable parts, joint parameters and unseen articulation states from an uncalibrated monocular video is essential for robot manipulation and interactive digital twins. Existing per-scene optimisation methods require minutes to hours and external depth or camera poses, whereas feed-forward 3D foundation models reconstruct dense point maps in one pass without segmenting movable parts or inferring joints. Even on these monocular point maps, regressing or fitting continuous joints directly fails on casual videos, since cross-frame attention blurs moving part boundaries in deep layers, underestimates motion along the viewing ray and leaves continuous axes ill-conditioned under small opening angles. To address these challenges, we propose PhyVGGT, a single-pass framework on a frozen 3D foundation model that anchors moving-part matching and closed-form joint estimation to the undistorted geometry of the stationary base. First, our Part and Motio

---

### [133] GameRealm: Grounding Visual Learning in Interactive Games

**链接**: https://arxiv.org/abs/2611.23140
**作者**: Weiguang Zhao, Yifan Wang, Ni Yang, Yating Wang, Xingyu Miao, Yankai Jiang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual foundation models are central to physical intelligence, yet their development remains constrained by fragmented training datasets, inconsistent annotation quality, and limited multimodal supervision. To address these challenges, we introduce GameRealm, a large-scale, richly annotated dataset that grounds visual observations in synchronized, game-native supervision. GameRealm encompasses over 120 million RGB frames and 1,000 hours of gameplay footage across all views. Beyond its unprecedented scale, GameRealm provides rich multimodal supervision, including metric depth, camera parameters, synchronized audio, control inputs, and 3D point trajectories. Its diversity further extends to flexible view configurations, spanning single-view, stereo, multi-view, and panoramic recordings. To enable scalable acquisition across diverse game environments, we develop a unified data collection pipeline that combines human-operated interaction with agentic exploration. Extensive experiments acro

---

### [134] Scaling Laws for Vision-Language Fusion

**链接**: https://arxiv.org/abs/2611.22351
**作者**: Seng Pei Liew, Teppei Suzuki, Seiya Tokui
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) have emerged as central foundation models combining multimodal perception with text comprehension. While VLMs are traditionally built via late fusion by continued pre-training an off-the-shelf language model on multimodal (image-text) data, mixing modalities from the start of pre-training (early fusion) has recently gained traction. However, the fundamental trade-offs between these paradigms remain poorly understood, resulting in expensive and heuristic-driven training recipes. In this paper, we systematically analyze the learning dynamics of these multimodal pre-training processes, showing that validation losses during vision-language fusion can be modeled by separating the base learning trajectory, where different data types contribute at distinct rates, from a distribution shift driven by the competition between modalities. We derive a scaling law that unifiedly describes these dynamics, enabling accurate loss predictions across mixture ratios, training

---

### [135] NVIDIA Kumo Tabular: Pushing the Accuracy$\unicode{8211}$Efficiency Frontier for Tabular Prediction

**链接**: https://arxiv.org/abs/2611.23001
**作者**: Jingang Qu, Valter Hudovernik, Martin Jurkovi\v{c}, Cedric Lorenz, David Holzm\"uller, Federico Lopez 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Kumo Tabular, a family of open tabular foundation models for classification and regression, in three sizes: Kumo Tabular-S (27M parameters), Kumo Tabular-M (61M), and Kumo Tabular-L (214M). Pretrained only on artificial tables from the Kumo prior, they can make predictions on new tables without any training. In our approach, a table encoder compresses each row into an embedding, and an in-context learning transformer predicts the unlabeled rows from the labeled ones. Kumo Tabular introduces architectural innovations that improve both training stability and predictive performance, enabling the model to scale up to 150M cells on modern GPUs. Kumo Tabular-L ranks first on eight benchmarks: TabArena, TALENT, BeyondArena, ScoringBench, STRABLE, MulTaBench, RamanBench, and TabBench-Bio. These cover probabilistic regression, tables with over 1M rows or 100K columns, and tables with strings, text, or images. Accuracy improves with model size in all tested comparisons. All three si

---
