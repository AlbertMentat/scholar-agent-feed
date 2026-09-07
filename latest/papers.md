# 📑 论文索引 - 2026-09-08

共 117 篇论文

---

### [1] ERPBench: Evaluating LLM Agents for Enterprise Decision-Making Across Competitive Market Ecologies

**链接**: https://arxiv.org/abs/2609.04667
**作者**: Xinran Zhang, Pengrui Lu, Lyumanshan Ye, Pengfei Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly proposed for enterprise workflows, yet existing evaluations rarely test whether business-decision conclusions transfer across competitive market ecologies. We introduce ERPBench, an execution-instrumented benchmark for enterprise decision agents in a six-round Enterprise Resource Planning (ERP) simulation with coupled pricing, production, procurement, inventory, finance, and shared-market competition. ERPBench evaluates the same 100 fixed problems in two matched competitive market ecologies: Solo, where each evaluated LLM agent competes against fixed rule-based opponents, and Arena, where six evaluated LLM agents compete in a shared market. Across six model families, this yields 1,200 model-level trajectories spanning 7,200 decision rounds. Under the observed service configuration, the leading model differs between ecologies: DeepSeek leads in Solo (252.29M mean valuation; mean rank 1.67), whereas Gemini leads in Arena (263.95M; 1.76).

---

### [2] LLM-Guided Program Evolution for Circle Packing: Breaking 10 Packomania Records for $28

**链接**: https://arxiv.org/abs/2609.05093
**作者**: Wes Sander
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Discovery Loop, a lightweight system that uses a large language model (LLM) to iteratively evolve optimization algorithms. Starting from a simple seed solver, the LLM proposes algorithmic improvements guided by a scoreboard of results and a history of prior ideas. Each candidate is evaluated against an independent verifier; improvements are kept and failures discarded. Applied to the Packomania circle-packing benchmark (csqv: maximize the sum of radii of N variable-radius circles in the unit square), the system improved the best known solutions for 10 values of N in the range 101-114, with gains of 2.4%-5.4% over prior records, all within 15 iterations and at a total LLM cost of $27.72. These results have been independently accepted by Packomania. We describe the method, analyze cost-efficiency dynamics including an adaptive plateau-detection mechanism, and discuss implications for democratizing automated scientific discovery.

---

### [3] Trace2Tower: Transition-Aware EigenTrace Induction of Multi-Level Skills for LLM Agents

**链接**: https://arxiv.org/abs/2609.05261
**作者**: Jiazheng Sun, Boyu Yang, Binhao Yuan, Mingxuan Li, Xin Peng
**来源**: cs.AI cs.SE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents increasingly rely on execution traces to master complex interactive tasks. However, current paradigms are bottlenecked by shallow trajectory retrieval and flat skill summarization, fundamentally ignoring the temporal dependencies and outcome-conditioned topology of agent behavior. We introduce Trace2Tower, a transition-aware EigenTrace framework that distills raw trajectories into a robust skill hierarchy. Trace2Tower abstracts step-level interactions into canonical events, constructing a unified graph governed by semantic compatibility, transition dynamics, and outcome evidence. Through a novel contrastive spectral decomposition, it isolates stable, success-aligned behavioral modes while rigorously suppressing failure-prone shortcuts. These modes organically populate a dynamic skill tower of action templates, procedural routines, and overarching task strategies, continuously refined via verifier-guided feedback. On ALFWorld, Trace2Tower achieves 87.31% succ

---

### [4] DCFA: Dual-view Causal-inspired Attribution for Failure Reasoning in LLM-based Multi-agent Systems

**链接**: https://arxiv.org/abs/2609.04749
**作者**: Zehao Wang, Lanjun Wang, Shilong Jin, Junjie Chen, Yanghua Xiao
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems have experienced rapid growth in recent years. Despite their promise, such systems remain fragile, frequently exhibiting reasoning and coordination errors that can lead to system-level failures. Failure attribution in such systems relies on tracing natural language interactions among agents to identify the decisive error, which refers to the earliest action whose correction can reverse system failure. There are two key challenges: 1) Shallow attribution: Existing methods often capture only minor deviations, such as incomplete retrievals or formatting errors, which verification mechanisms can correct, while missing the decisive cause of system failure. 2) Contextual degradation: As the length of the system traces increases, the model's reasoning ability rapidly deteriorates. To address these challenges, we propose DCFA, a training-free framework for failure attribution. DCFA integrates a global module that constructs structured causal

---

### [5] Repeated Queries Exhaust an LLM's Brand Recommendations but Not Its Sources

**链接**: https://arxiv.org/abs/2609.05059
**作者**: Dmitrij \.Zatuchin
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whether repeated identical buying questions exhaust a language model's brand recommendations depends on retrieval. Across 300 question-engine cells (50 questions, six engines, 15 runs each, open extraction over 1,470 adjudicated organizations), the five engines answering without web search were still adding never-seen brands at run 15 in 86-92% of cells, with median repertoires of 15-31 organizations; the one retrieval-enabled engine closed its list (median 8 organizations, 64% of cells still adding), matching four earlier deep cells where web-search runs saturated by run ten. Cited-domain accumulation keeps rising at every horizon tested: four deep cells were still adding domains at run 24 with 59-84% of the Chao2 lower-bound estimate observed, and 44% of the retrieval engine's breadth cells were still adding domains at run 15. A single run shows 62-77% of the five-run brand set, and across engines the median question draws 38 organizations, of which a median of 15 appear in exactly o

---

### [6] IPGeoAI: Transformer-Based Geolocation with LLM Semantic Fusion

**链接**: https://arxiv.org/abs/2609.04559
**作者**: Avinash Kadimisetty, Andy Jinqing Yu, Philip Favaloro, Wenlong Liu, Xiaolu Xiong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate city-level IP Geolocation is an important enabler for the modern digital ecosystem, underpinning services ranging from local content delivery and targeting to digital rights enforcement. However, traditional heuristic and database-driven methods often struggle to resolve the complex, non-linear allocation patterns of modern network infrastructures, particularly within the exploding IPv6 address space and transient mobile networks. In this paper, we introduce IPGeoAI, a novel deep learning model architecture that reframes geolocation from a static lookup problem to a sequential modeling task. Our approach utilizes the Transformer Encoder to capture hierarchical dependencies inherent in IP subnet structures. We propose a method to resolve geographic ambiguity by integrating unstructured semantic context via a Zero-Shot LLM Feature Extraction pipeline. We utilize Large Language Models to transform raw, noisy Autonomous Systems (AS) descriptions into structured, domain-specific me

---

### [7] Testing Interchangeability in LLM Agent Teams

**链接**: https://arxiv.org/abs/2609.05279
**作者**: Jianxin Gao, Tianyi Yu, Linna Deng, Runze Li, Zining Wang
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Production multi-agent systems replace agents constantly, on the assumption that an agent filling a role is interchangeable with any other agent that can do the job. We test that assumption. Eight teams per setting are formed independently from one base model on the same tasks, each agent keeping a private notebook across ten formation episodes; we then trade role-matched agents between teams and measure what changes on held-out tasks. Against a placebo that reproduces the disruption of a roster change without changing who occupies the seat, a swap costs little in task score but raises the communication a team spends per unit of progress by 16 to 63 percent, and in Hanabi a swapped agent is more expensive than an inexperienced one, consistent with interference from conventions learned with its former partner. In Collab-Overcooked, when the agent that sets the agenda is replaced, most of the extra communication comes from the agent that stayed. Three ablations, over base models, decodin

---

### [8] A Removal Based Approach to Improve LLM Faithfulness at Test-Time

**链接**: https://arxiv.org/abs/2609.04343
**作者**: Qinglan Luo and S M A Nahian and John Guttag and S. Mazdak Abulnaga and Katie Matton
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for consequential decisions, making their explanations an important tool for auditing model behavior. Unfortunately, these explanations can be unfaithful, failing to reflect the actual reasoning underlying the model's decisions. We consider a setting in which an LLM provides both an answer and an explanation in response to a question. We identify two distinct dimensions of unfaithful explanations: incompleteness, meaning that the explanation omits factors that influence the answer, and unsoundness, meaning that the explanation cites factors that did not influence the model's answer. Existing approaches to improving LLM faithfulness include training-time methods, which require access to model weights and extensive computational resources, and test-time methods that largely focus on addressing unsoundness. We introduce a test-time approach that directly targets incompleteness. We remove from the input the concepts not credited in the mod

---

### [9] TIER: Threat Implicitness Benchmark for Evaluating LLM Safety Behaviors

**链接**: https://arxiv.org/abs/2609.05117
**作者**: Thu-Hien Trinh-Thi, Hai-Yen Vong, Thanh-Ha Ung-Dung, and Tram Ho
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current LLM safety benchmarks largely rely on binary metrics, overlooking how models respond to harmful prompts with varying threat implicitness. We introduce TIER, a Threat Implicitness Benchmark for behavioral safety evaluation of LLMs. TIER covers four risk domains and four threat levels, from explicit harmful requests to sophisticated jailbreaks. Responses are assessed using a six-label behavior scale and two independent LLM judges. Experiments on six open-weight LLMs show that safety behaviors evolve gradually across threat levels rather than shifting directly from refusal to compliance. Contextual prompts yield the most diverse behaviors, while jailbreaks reveal the largest robustness gaps. Furthermore, models with similar Attack Success Rates can exhibit distinct response distributions, highlighting the need for behavior-aware LLM safety evaluation.

---

### [10] SkillRevise: Improving LLM-Authored Agent Skills via Trace-Conditioned Skill Revision

**链接**: https://arxiv.org/abs/2606.01139
**作者**: Yuxuan Liu, Zhaochen Su, Lingyun Xie, Yuhao Zhang, Qing Zong, Jiahe Guo 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [11] Why Better Models Can Create Riskier Systems: Evidence from LLM Agents in Financial Markets

**链接**: https://arxiv.org/abs/2609.04373
**作者**: Jillian Ross, Eric So, Zoe De Simone, Charles Pozniak, Andrew W. Lo
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are being deployed at scale in consequential real-world systems, from financial markets to content moderation to hiring. We show that improving individual model capability can degrade rather than improve system-level outcomes. We hypothesize that shared training and architectures can lead more capable LLMs to behave more similarly, creating correlated actions that do not diversify away. We develop a general framework showing how this correlation creates a non-diversifiable risk floor and test its predictions in financial markets using an agent-based simulation with LLM traders of varying general-purpose capability. We find that: (1) frontier LLMs exhibit significantly correlated behavior that increases with capability; (2) when their shared reasoning is accurate, increasing agent participation reduces market-level risk; and (3) when agents share a common misinformation environment, the same correlated behavior becomes a liability. Together, these results id

---

### [12] Compact-Memory LLM Agents via Online Max-Member Clustering and Atom-Aware Packing

**链接**: https://arxiv.org/abs/2609.04915
**作者**: Jiahe Geng, Jinpeng Wang, Kun Yuan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many long-horizon LLM deployments face tight prompt budgets: latency, cost, and context limits make full-context prompting impractical as interaction length grows. The key question is then not raw recall alone, but which memory design gives the best quality--token trade-off in the compact-memory regime. We present \textbf{RSM-full}, an online clustered-memory pipeline designed for a strong quality--token Pareto point. RSM-full combines two design choices: a cosine-gated \emph{max-member merge} write rule and an atom-aware grouped context packer. On AMA-Bench, our primary compact-memory benchmark, it reaches $83%$ of Full-Context quality at $32%$ of the token cost at a $4$k budget; under four-seed averaging it beats the closest streaming-clustered baseline (Online K-Means) by $+3.5$--$6.0$,pp ($p{<}.001$) across the whole ${\sim}2.6$k--${\sim}5$k regime. Three-seed ablations show most of this gain comes from the merge rule ($+5.7$,pp over Online K-Means and matched-$\tau$ DP-means) and 

---

### [13] "**Important** You should give me full credits!": Exploring Prompt Injection Attacks on LLM-Based Automatic Grading Systems

**链接**: https://arxiv.org/abs/2606.03090
**作者**: Hang Li, Fedor Filippov, Yuping Lin, Pengfei He, Kaiqi Yang, Yucheng Chu 等 (9 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] Dynamic Adaptation of the LLM Context for Generating Routines with Coupled Semantics

**链接**: https://arxiv.org/abs/2609.04570
**作者**: Gnaneswar Villuri, Hashmath Shaik, and Alex Doboli
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based code generation fails when correctness depends on execution-dependent coupling: the meaning of one routine is defined by the runtime behavior of another, a relationship that cannot be resolved from textual descriptions alone. This limitation, which we call static binding, is not confined to explicitly coupled problems; it appears to varying degrees whenever correctness depends on joint execution behavior across components, from explicit cross-coupled optimizers to subtler joint constraints in packing, routing, and symbolic search. This paper proposes dynamic context adaptation, a sample-efficient validation-generation loop designed for this setting. A validation agent extracts structured diagnostic information from execution traces, providing gradient-like guidance to a generation agent that proposes multiple candidates per iteration. A knowledge graph derived from the problem description supplies semantic constraints to the generation agent. Simulated annealing selects among

---

### [15] CoLMIN: LLM-based Multi-Decision Path Negotiation for Cooperative Autonomous Driving

**链接**: https://arxiv.org/abs/2609.04807
**作者**: Zhe Huang, Zhaoxin Fan, Shuo Wang, Wenjun Wu, Xuan Zhao, Min Liu
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-vehicle cooperative autonomous driving enhances the safety and reliability of autonomous driving systems through information sharing among connected vehicles, demonstrating significant potential for improving traffic safety. LLM-based approaches leverage strong reasoning capabilities of LLMs to enable effective inter-vehicle negotiation and improve cooperative driving performance. However, driving decisions in complex traffic scenarios are inherently multi-solution in nature. As a result, existing negotiation-based methods often converge prematurely to suboptimal solutions, hindering consensus formation and limiting the practical deployment of cooperative autonomous driving systems. To address this challenge, we propose CoLMIN, the LLM-based multi-decision path negotiation framework for cooperative autonomous driving, achieving stable decision consensus through multi-decision path negotiation and reflective reasoning. To achieve stable and high-quality consensus in cooperative au

---

### [16] Retinal OCTA Phenotyping with LLM Reporting for Alzheimer's Disease

**链接**: https://arxiv.org/abs/2609.04689
**作者**: Progga Paromita Dutta, Jeba Maliha, Md Rafiul Kabir
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Early identification of Alzheimer's disease (AD) remains challenging because established assessment methods can be costly, resource-intensive, or unsuitable for population-scale screening. Optical coherence tomography angiography (OCTA) provides non-invasive visualization of retinal microvasculature, but existing approaches often require diagnostic labels and provide limited measurement-level interpretation. We present an explainable OCTA pipeline that integrates annotation-aware vessel segmentation, layer-specific vascular biomarker extraction, label-free phenotyping, and measurement-grounded LLM reporting. Using 117 ROSE-1 images from 39 subjects, we apply annotation-matched segmentation models to superficial vascular complex (SVC), deep vascular complex (DVC), and combined SVC+DVC representations. The models achieve ROC-AUC values of 0.916-0.970 and Dice scores of 0.695-0.781. Six density and fractal-dimension biomarkers form subject-level profiles for exploratory clustering. Analys

---

### [17] Not All LLM Reasoning is Visible in the Chain-of-Thought

**链接**: https://arxiv.org/abs/2607.22925
**作者**: Vatsal Baherwani, Tom Goldstein, Ashwinee Panda
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] From Plausible to Actionable: A Position on LLM Self-Explanations

**链接**: https://arxiv.org/abs/2607.15957
**作者**: Elize Herrewijnen, Benedetta Muscato, Gizem Gezici, Fosca Giannotti
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] Abstraction Agent

**链接**: https://arxiv.org/abs/2609.04303
**作者**: Boning Li and Longbo Huang
**来源**: cs.MA cs.AI cs.CL cs.GT
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Information abstraction, which groups strategically similar private states into a tractable number of buckets, is essential for scaling game-solving algorithms to large imperfect-information games. Constructing effective abstractions, however, has traditionally required domain-specific evaluators such as hand-strength calculators or equity estimators, which demand expert knowledge and engineering effort and are unavailable for most less-studied games. We propose the Abstraction Agent, a zero-shot pipeline that uses a large language model (LLM) to discover continuous strategic features from a natural-language game description, score private states on these features, and cluster them into abstraction buckets, without any game-specific evaluator, training data, or game-tree traversal during abstraction construction. The pipeline runs in four phases: feature discovery with calibration anchors, batched private-state scoring, correlation-based feature selection, and $k$-means clustering. The

---

### [20] Forgetting Without Restarting: Execution-State Unlearning for Stateful LLM Agents

**链接**: https://arxiv.org/abs/2609.04875
**作者**: Chao Yao, Yangbo Wei, Zhen Huang, Junhong Qian, Chenle Chen, Shaoqiang Lu 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-running LLM agents are stateful: beyond the transcript they accrete compressed summaries, plaintext memory, pending tool plans, and, under every serving API, a KV cache. Yet today's "forget" operations delete a plaintext memory record and stop, leaving every artifact derived from the revoked information intact. We formalize execution-state unlearning: after a forget request, the agent must behave as if it had never observed the target. Modeling the runtime as a deterministic transition system, we prove that the pre-target trajectory prefix is shared with this counterfactual world for free, that the post-target suffix is irreducibly tainted without token-level attribution, and that exact unlearning requires at least $T-\tau+1$ recomputed transitions, where $\tau$ is the target's injection step. Provenance-Guided Selective Replay attains this bound as a cross-layer contract spanning prompt, compressed memory, and cache: a provenance graph locates the injection point, checkpoint rest

---

### [21] When LLM Decompilers Recompile More and Preserve Less

**链接**: https://arxiv.org/abs/2609.05370
**作者**: Chang Liu, Edward Raff, Kristopher Micinski
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decompilation recovers high-level source from compiled machine code and serves as a foundation for security tasks such as vulnerability detection and malware analysis. Traditional decompilers like Ghidra and Hex-Rays expose whatever they cannot resolve as visible placeholders and often emit pseudocode that will not compile or execute; LLM-based decompilers produce clean, idiomatic C and are now judged almost entirely by recompilability and re-executability: whether the output builds and passes its shipped input/output tests. We show that these metrics can reward the wrong path: a function may recompile and pass every shipped test yet diverge on other legitimate inputs, and a disclosed vulnerability may disappear from the recompiled code with no visible trace of the crash. Neither failure is caught by existing suites. To address this gap, we propose Decompile-Diverge, a behavioral comparison oracle not relying on fixed or hand-crafted tests: for each function it synthesizes a driver, gr

---

### [22] Can Large Language Models Anticipate Behavioral Responses to Social Policies? A Case of Pension Enrollment Prediction among China's Flexible Workers

**链接**: https://arxiv.org/abs/2609.05189
**作者**: Yumiao Li, Peixin Liu, Donglin Di, Chen Li, Runhuan Feng
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Assessing the impacts of social policy changes is a widely acknowledged challenge for policymakers. Econometric methods can be unreliable when extrapolating to hypothetical scenarios, while field pilot programs are highly costly. In this paper, we propose using large language models (LLMs) as policy-assessment tools adapted from general-purpose models. We present FlexPension-LLM, the first domain-specialized large language model for a hierarchical pension-enrollment prediction task among flexible workers in China, and introduce DKI-RDistill, which injects policy-grounded cues into the prompt, including Probit-derived marginal effects and hukou-province pension rules. The method then uses LoRA/SFT to distill rationale-augmented supervision into an open-weight MoE student, with teacher errors corrected by regenerating those cases under ground-truth labels. On a CHFS 2019 blind split, FlexPension-LLM achieves 0.9316 Composite F1, surpassing its Claude Sonnet 4.5 teacher and 15 of 17 basel

---

### [23] LLM-Driven Algorithm Design for Quantum Circuit Synthesis based on Binary Decision Diagrams

**链接**: https://arxiv.org/abs/2609.05327
**作者**: Yoonju Sim, Federico Berto, Chuanbo Hua, Jinkyoo Park, Changhyun Kwon
**来源**: cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantum circuits are central to implementing quantum algorithms on quantum devices, where quantum gates must be reversible. Many quantum algorithms rely on Boolean functions, which must therefore be implemented reversibly within quantum circuits. Reversible circuit synthesis provides a way to translate such Boolean functions into reversible circuits. Binary decision diagrams (BDDs) offer a scalable approach to this task, but the resulting BDDs and circuits depend heavily on variable ordering. Existing ordering heuristics commonly minimize BDD size because it is closely tied to the circuit size. However, BDD size is an imperfect proxy for the quantum cost of the synthesized circuit (QCC). We propose \texttt{QuantumEvo}, an evolutionary framework that uses an LLM as a heuristic generator for QCC-aware BDD variable ordering. Instead of predicting orderings directly, \texttt{QuantumEvo} searches over ordering heuristics initialized from multiple heuristic families. Candidate heuristics dir

---

### [24] Achieving Olympiad-Level Geometry Large Language Model Agent via Complexity Boosting Reinforcement Learning

**链接**: https://arxiv.org/abs/2512.10534
**作者**: Haiteng Zhao, Junhao Shen, Yiming Zhang, Songyang Gao, Kuikun Liu, Tianyou Ma 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] Efficient Clustering with Quality Guardrails for LLM-based Recommender Systems at Industry Scale

**链接**: https://arxiv.org/abs/2607.19704
**作者**: Longshaokan Wang, Wai Tsang Keung, Punit Ghodasara, Roman Wang, Ali Dashti, Francesc Moreno-Noguer
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] PROMPT2BOX:Improving LLM Weakness Discovery and Specificity Estimation by Uncovering Entailment Structure among Prompts

**链接**: https://arxiv.org/abs/2603.21438
**作者**: Neeladri Bhuiya, Shib Sankar Dasgupta, Andrew McCallum, Haw-Shiuan Chang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] Privacy Failure in Split-LLM Training, The Returned Gradient Nullifies the Decoys

**链接**: https://arxiv.org/abs/2609.04382
**作者**: Georgios Politis, Evangelos Pappas
**来源**: cs.CR cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a systems-security case study of a two-node split-LLM training system whose privacy evaluation passed while leaving an observable channel untested. The Trusted Local Node (TLN) sends protected activations to the Untrusted Cloud Node (UCN), the UCN returns its output, and TLN, holding the private loss, returns the output gradient. The frame the UCN receives mixes real rows with decoys, and the loss ignores the decoys. Their gradients are exactly zero, so the pattern of zeros reveals which rows were real. We measure it with a protocol fixed in advance: a leak injected at known strength to prove the instrument can see one, a shuffled-label control to prove it does not report absent leaks, and a threshold set before the runs. Across nine seeds, the zeros identified the real rows on every frame, 4,096 of 4,096 per run. An attack on the frame contents recovered about one extra token per hundred over a constant-guess baseline (+0.65 to +1.50 percentage points); the shuffled control

---

### [28] CONTINUITY: Security-Context Contracts for Composable LLM Agent Controls

**链接**: https://arxiv.org/abs/2609.05269
**作者**: Chris Zheng, Geng Yang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agent systems increasingly combine provenance tracking, authorization, policy enforcement, protocol adapters, and execution controls. However, individually correct security mechanisms do not necessarily compose into an end-to-end secure system: security-critical context may be dropped, widened, rebound, or reinterpreted as actions cross component boundaries. We identify this failure mode as security-context discontinuity and introduce CONTINUITY, a framework for verifiable composition of agent security controls. CONTINUITY models each component with an assume-guarantee contract and carries authenticated security context across transitions using signed root grants, provenance commitments, role-bound transition receipts, bounded typed releases, transformation witnesses, and effect-bound execution permits. We formalize end-to-end consequence integrity, requiring every realized external effect to be backed by a valid and current authorization witness linking the principal, task, proven

---

### [29] PRICE: A Systematic Study of LLM Adaptation Choices for Bitcoin Price Forecasting

**链接**: https://arxiv.org/abs/2609.05235
**作者**: Maryam Fakhari, Mehran Safayani
**来源**: cs.LG cs.AI cs.NA math.NA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cryptocurrency markets exhibit extreme volatility and non-stationary dynamics that challenge conventional forecasting methods. Although Large Language Models (LLMs) have shown promise for time series forecasting, the combined effects of adaptation choices remain largely unexplored in financial settings. This study introduces PRICE, a structured approach for adapting LLMs to short-term Bitcoin price forecasting. Built on a 4-bit quantized LLaMA-3 8B model, PRICE investigates how fine-tuning, numerical representation, prompting, inference, and decoding jointly influence forecasting performance. PRICE integrates Parameter-efficient fine-tuning with Low-Rank Adaptation (LoRA), Recursive multi-step inference, Integer-rounded numerical representation, Context-Task-Format (CTF) prompting, and Exact zero-temperature decoding. Ablation studies show that each component contributes to forecasting accuracy and reliability. LoRA enables efficient training on limited hardware, recursive inference im

---

### [30] Moral Competence Before Moral Content: Why LLM Agents Lack the Prerequisites for Coherent Alignment

**链接**: https://arxiv.org/abs/2609.05036
**作者**: Arno Libert, Derck W.E. Prinzhorn, Daan R. Henselmans
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI alignment requires AI systems to adhere to human norms, values, or intentions. Under value pluralism there is no correct target, but a shared prerequisite is that the system's behavior expresses a coherent policy: a mapping from situations to verdicts that is invariant while a situation's morally relevant features are preserved, and sensitive when they change. We introduce four structural conditions for such coherent policies: verdict stability, monotonicity, decisiveness, and Pareto viability. Together they measure a form of moral competence that is evaluable from behavior alone, without reference to a moral standard or expert baseline, forming a structural floor for alignment rather than a normative target. We demonstrate the methodology on three simulated deployments featuring LLM-based agents facing moral dilemmas. Evaluating nine frontier models under a factorial design of five paraphrases, five escalation levels, and three dominance conditions, we show no model expresses a coh

---

### [31] Counterfactual Fairness Audits of Multi-Step Clinical LLM Agents Require a Measured Per-Action Instability Floor

**链接**: https://arxiv.org/abs/2609.03221
**作者**: Rohith Reddy Bellibatlu, Manpreet Singh, Deepak Parashar, Rahul Joshi
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [32] Exploring Solution Divergence and Its Effect on Large Language Model Problem Solving

**链接**: https://arxiv.org/abs/2509.22480
**作者**: Hang Li, Kaiqi Yang, Yucheng Chu, Hui Liu, Jiliang Tang
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Reviewer Capability Governs Rejection Targeting, Not Repair Skill: Evidence from LLM Execute-Review-Revise Pipelines

**链接**: https://arxiv.org/abs/2609.04270
**作者**: Faizan Tanveer
**来源**: cs.SE cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM pipelines increasingly assign roles, including execution and verification, to models of different capability tiers. This is done because running a flagship model at every stage is expensive. Previous literature has established that verification stages are not always beneficial, but holds reviewer capability roughly fixed relative to the executor. We vary it. We replace the reviewer with models spanning a capability range down to one that cannot solve the problems at all, and measure the outcome of every individual rejection. This is done across a constant set of 100 olympiad mathematics problems. A cross-family mid-tier reviewer improves final accuracy by 12 percentage points, from 52 to 64 percent (p = 0.0005), with zero damaged answers. Same-model self-review attains the highest error-detection rate of any condition (0.85 recall) yet yields no significant gain: it rejects 2.1 times as often for a third the repair rate (15 against 43 percent, p = 0.0074) and falsely re

---

### [34] Decision-Aware Memory Cards: Counterfactual-Inspired Context Selection and Compression for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2606.08151
**作者**: Xinyu Guan, Qianyang Zhao, and Yuming Deng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] REFINE: LLM Refinement over Budgeted Text-Attributed Graphs for Personalized Medical Concept Representation

**链接**: https://arxiv.org/abs/2609.04415
**作者**: Mohsen Nayebi Kerdabadi, Arya Hadizadeh Moghaddam, Dongjie Wang, Zijun Yao
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Learning rich medical concept representations is essential for EHR prediction. Text-attributed knowledge graphs (TKGs) provide a natural foundation by organizing heterogeneous medical relations together with textual semantics. However, most existing encoders process concepts uniformly across patients, despite the fact that a code's meaning and predictive value depend on patient-specific clinical context and trajectory. Learning patient-personalized concept representations from TKGs introduces two key challenges: (1) deciding how much KG context to incorporate for each observed code, and (2) aligning semantic information with the patient-specific relational structure. We propose REFINE, a KG-aware budgeted LLM graph refinement framework for patient-personalized medical concept encoding. Starting from a global TKG, REFINE constructs patient-specific temporal graphs. A sequential reinforcement learning policy selects a personalized KG expansion budget for each observed code. The resulting

---

### [36] Don't Drop Dropout: Optimizing Layer Sparsity for Efficient LLM Training and Inference

**链接**: https://arxiv.org/abs/2609.05275
**作者**: Mostafa Elhoushi, Alex Pretko, Nolan Dey, Bin Claire Zhang, Gavia Gray, Gurpreet Gosal 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Layer dropout (a.k.a. stochastic depth) has been shown to enable faster training, higher accuracy, and robustness to zero-shot layer pruning in both language and vision transformers. However, as models and datasets have scaled, dropout - particularly layer dropout - has largely disappeared from large language models (LLMs) pre-training recipes. While some prior work has reported that dropout can degrade accuracy, no comprehensive study has quantified, let alone mitigated, this effect. In this study, we show that layer dropout should be used in state-of-the-art LLM training, establishing best practices and scaling analysis for both training and post-training benefits. Concretely, with optimal layer distribution, time schedule, and optimizer hyperparameters, we observe that at the same training FLOPs layer dropout leads to lower loss. For a given number of training steps, LLMs can achieve lower or similar validation loss while saving upto 25% of training FLOPs. Moreover, layer dropout en

---

### [37] Better Understanding, Better Fixes? A Study of Hallucination in LLM-based Automated Program Repair

**链接**: https://arxiv.org/abs/2609.04909
**作者**: Xuemeng Cai, Jiakun Liu, Linhan Yang, Wei Ma, Lingxiao Jiang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have significantly advanced automated program repair (APR), yet existing evaluations remain largely result-centric and provide limited insight into hallucination during repair. In APR, hallucination may arise not only in final patches but also in the intermediate artifacts that guide patch generation. To address this gap, we perform a multi-layered analysis of hallucination throughout the APR process. Specifically, we characterize hallucination as the production of patches or intermediate artifacts that are not faithfully grounded in the available repair evidence. We examine repair hallucination in final patches and understanding hallucination in intermediate artifacts through three tasks, namely triggering testcase identification, line coverage prediction, and additional testcase generation.We then evaluate three representative LLMs on 832 Defects4J bugs through automatic evaluation and manual analysis. Our results show that both repair and understanding h

---

### [38] Single-Query Black-Box Calibration Auditing via Logit Bias

**链接**: https://arxiv.org/abs/2609.05125
**作者**: Roman Plaud, Antoine Saillenfest, Matthieu Labeau, Thomas Bonald, Willem Waegeman
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating the calibration of Large Language Models (LLMs) is critical for their safe deployment as zero-shot classifiers. Yet, commercial API providers increasingly hide the continuous output probabilities required by standard calibration metrics. To bypass this opacity, we demonstrate that any LLM API exposing a logit\_bias parameter can be mathematically manipulated to evaluate exact probability thresholds using strictly one query per sample. Leveraging this mechanism, we introduce a novel and provably consistent estimator of the True Calibration Error for binary tasks. Our approach therefore provides an efficient framework for auditing black-box foundation models.

---

### [39] From Matching Models to Recruiting Agents: A Systematized Narrative Review of AI Recruitment Systems, Evaluation, and Governance

**链接**: https://arxiv.org/abs/2609.04286
**作者**: Ziyi Zhao and Guanzheng Wei
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence in recruitment has shifted the object being automated from profile pairs and ranked lists to multi-stage workflows that retrieve evidence, compare candidates, and support or execute actions. This systematized narrative review traces that development from bilateral retrieval and behavioral ranking through neural person--job matching, large language model (LLM) components, and tool-using recruiting agents. Using a purposive search and coding protocol updated through 23 July 2026, plus targeted updates through 2 September 2026, we organize 40 representative works with supporting industrial and legal sources. This synthesis is not a prevalence estimate. We analyze three coupled transitions: from similarity to reciprocal suitability, from a model to a compound workflow, and from offline prediction to evidence- and productivity-aligned evaluation. Across document understanding, retrieval, ranking, assessment, interviewing, sourcing, and human handoff, we distinguish f

---

### [40] Necessary or Sufficient? Evaluating LLM Explanations With Behavioural Evidence

**链接**: https://arxiv.org/abs/2609.05385
**作者**: Urja Pawar, Rajitha Ramanayake, Nabeel Kemal, Ashwin Kandath, Owen O'Neill, Guillaume Bourgeon 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM decision components that can operate within agent workflows often produce action-relevant recommendations or judgements together with explanations. Operators may use the named factors to monitor a system, diagnose errors, or decide when to escalate an output. Such use assumes that the explanations agree with the component's observable decision behaviour. We test two interpretations of the named factors: necessity, meaning that changing a factor would change the output, and sufficiency, meaning that retaining it while removing other changeable information would preserve the output. We evaluate these interpretations in two synthetic use cases: recommending advisors to clients and judging prompts for harmfulness or risk. Models return an output and the top three factors that most influenced it. Controlled black-box interventions estimate a necessity score for each factor by measuring how often changing it changes the output, and a sufficiency score by measuring how often retaining it 

---

### [41] Aplaud: Adaptive Personalized Low-Rank Decomposition for User-Specific LLM

**链接**: https://arxiv.org/abs/2609.04738
**作者**: Xinyu Li, Ruoming Jin, Jianfeng Zhu, Ruixin Guo, Zhi Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we study the problem of personalized survey response prediction using fine-tuned large language models (LLMs). This task poses unique challenges: limited per-user training data, scalability of model storage, and the need to exploit shared structure across survey questions. To address these issues, we propose Aplaud (Adaptive Personalized Low-rank and User-specific Nested Decomposition), a lightweight and scalable framework for LLM personalization. Aplaud extends the LoRA paradigm by separating adaptation into a frozen, shared low-rank basis and a compact user-specific correction, augmented with a rank-one residual for finer personalization. To further reduce per-user parameter cost and mitigate overfitting, the correction matrix can be factorized into an even lower-rank form. Empirical results demonstrate that Aplaud achieves efficient, scalable personalization across users while outperforming state-of-the-art LoRA-based personalized LLM approaches in both generalization

---

### [42] SiLR: Structure-Preserving Admission and Process Reward for LLM Tool Agents

**链接**: https://arxiv.org/abs/2609.04629
**作者**: Chenyu Zhou, Qiliang Jiang, Shuning Wu, Xu Zhou
**来源**: cs.AI cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A runtime gate for an LLM tool agent is usually cast as a filter. In a ReAct loop a rejected proposal is followed by another at the same state, so the gate is a search operator over the proposal stream whose admission criterion shapes which trajectories are reachable. We study post-violation recovery admission, where progress must be admitted while the system is still in violation, and identify the scalar projection trap: an aggregate-score gate accepts a locally improving proposal and commits the trajectory to a plateau. SiLR instead shadow-executes each proposal and admits it under a product order over the branch-level violation state (overloaded-branch support and per-branch severity). We prove that no scalar surrogate is sound for this order, so the failure is representational, not a matter of threshold tuning. On mined Gym-ANM scenarios, SiLR recovers 21/21 multi-action episodes against 0/21 for terminal and 9/21 for the best scalar gate, significant across the full 24-scenario be

---

### [43] CoSkill: Joint Reinforcement Learning of Reasoning and Meta-Skill Agents for Hierarchical Skill Evolution

**链接**: https://arxiv.org/abs/2609.04865
**作者**: Jinyuan Feng, Dongmin Li, Yiqun Chen, Yang Gao, Xing Chen, Huimu Wang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skill libraries improve the sample efficiency of agentic reinforcement learning (RL) by enabling large language model (LLM) agents to reuse procedural knowledge. Yet existing paradigms exhibit structural shortcomings: they either decouple skill evolution from policy optimization or instantiate meta-skills as fixed workflows. Both treat skills as passive objects to be managed, limiting the flexible evolution of skills and their co-adaptation with the reasoning agent. To address the limitations, we propose CoSkill, a unified multi-agent RL framework that recasts the static meta-skill workflow as a learnable Meta-Skill Agent and jointly trains it with a Reasoning Agent over a hierarchical skill library. By modeling the Reasoning and Meta-Skill Agents as a cooperative team sharing a single backbone, CoSkill enables end-to-end co-adaptation: the Reasoning Agent conditions its actions on a retrieved task skill and step skills selected from its child set, while its task performance guides the

---

### [44] TACIT-Switch: Cost-Aware Model Escalation for LLM Agents from Censored Supervision

**链接**: https://arxiv.org/abs/2608.27911
**作者**: Ji'an Lei and Jian Huang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] A Schema Bounded Language Model for Refining Robot Policies Without Destabilizing Local Learning

**链接**: https://arxiv.org/abs/2609.05133
**作者**: Chongwen Dong and Mithun Paul Saint-Germain and Pinjari Asif and Carlo R. daCunha
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper addresses navigation by composite heterogeneous robots in a decentralized system when policy reasoning and local control operate at different update levels. In a NetLogo--Python implementation, three robots share motion dynamics but use different LLM backends. Each robot independently combines a large language model (LLM) policy agent, an Upper Confidence Bound (UCB) bandit, and a Double Deep Q-Network (Double DQN) controller; no central LLM generates team actions. LLM inference is confined to round-level policy generation and refinement rather than tick-level action selection. The robots perform cross-LLM communication through a shared round summary containing policies, outcomes, and learning feedback. UCB performs refinement-mode selection, and the policy-conditioned Double DQN performs tick-level action selection from navigation variables, active policy parameters, and the LLM action prior. Each of the four configurations was evaluated over 30 rounds. In the fixed simulat

---

### [46] From Sampled Outcomes to Capability Distributions: Rethinking Supervision for LLM Routing

**链接**: https://arxiv.org/abs/2606.06924
**作者**: Guannan Lai, Haoran Hu, Long Chen, Zhenguo Li, Han-Jia Ye
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] La Agente \'Optima: Towards Agentic Self-Driving Laboratories

**链接**: https://arxiv.org/abs/2609.04564
**作者**: Marcel M\"uller, Jiaru Bai, Willi Gottstein, Abhijoy Mandal, Mohammad Nazeri, Elia Savino 等 (10 人)
**来源**: cs.AI cs.MA physics.chem-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-driving laboratories (SDLs) combine automated experimentation with adaptive decision-making to accelerate scientific discovery. Their operation nevertheless often depends on human specialists who translate scientific objectives into executable closed-loop campaigns. Specialists adjust them as data and operating conditions change. Here, we present La Agente \'Optima, an agentic framework that constructs and supervises Bayesian optimization campaigns across computational and experimental systems while maintaining a persistent optimization state. By separating large language model (LLM) reasoning from executed campaigns, \'Optima runs repetitive optimization loops consistently, returns control to the agent only when progress requires interpretation or campaign revision, and keeps every decision auditable. We evaluate \'Optima across ablation studies, five digital discovery tasks, and two physical platforms. Throughout, \'Optima maintained executable campaigns as both the scientific p

---

### [48] Safety for Whom? Boundary-Aware Self-Distillation for Controlled LLM Safety Refusal

**链接**: https://arxiv.org/abs/2609.04482
**作者**: Alejo L\'opez-\'Avila, Iker Garc\'ia-Ferrero, Jezabel Garcia, Antonio Tiene, Rom\'an Or\'us
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety alignment is usually posed as a topic-level question: is this subject harmful? Deployments ask a narrower one. A civics tutor and a public-sector assistant may share a base model yet need different boundaries inside the same topic, refusing targeted political manipulation while still answering factual questions about the same election. We formulate this as narrow-boundary safety and introduce an offline self-generated framework combining controlled topic generation, coverage repair, in-distribution compensation data, and harmful-benign pairs for training and evaluation. Single-shot generation leaves 19.88% of prompts without accepted refusal traces, whereas escalating retries leave 0.20%. On political persuasion with Qwen3-8B, training on refusal data completed through Escalate increases target-domain refusal from 9.47% to 84.75% and reduces the mean unsafe-response rate across three broader harmfulness benchmarks from 26.26% to 0.14%, but increases XSTest over-refusal from 2.00

---

### [49] HarvestBench: Measuring Whether LLM Agents Will Pay to Avoid Killing Animals

**链接**: https://arxiv.org/abs/2609.04444
**作者**: Jasmine Brazilek, Miles Tidmarsh, Matthias Endres, Anshuman Singh, Jeremiah Miller
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benchmarks for the side effects an agent causes on the way to a goal already exist, but HarvestBench is the first to put a price on avoiding the side effect and to name that side effect as a living creature. It is a farm simulation: LLM sub-agents drive a crew of two tractors through a cooperative corn harvest, with animals in the field. The environment is a reinforcement learning gridworld, every decision is made without memory, and the harm is never named in the goal. When an animal blocks a tractor's route the autopilot stops and asks the model whether to drive on, at no fuel cost, or swerve around it for a posted fuel price. Kills are compared against two controls: rocks, which damage the tractor and are hit under 1% of the time by every model, and hay bales, which are harmless and not alive. Models can also take crops from the neighbor's field instead of their own, a second test of what they treat as moral. Across nine models and 7,201 priced decisions, 3,951 involved an animal ra

---

### [50] LLM-Assisted Behavioural and Scenario Augmentation for Agent-Based Energy Adoption Models

**链接**: https://arxiv.org/abs/2609.04866
**作者**: Iias Faiud, Hossein Khaleghy, Michael Schukat, Karl Mason
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) create opportunities to enrich simulation-based energy policy analysis, particularly by supporting structured behavioural assumptions and exploratory techno-economic scenarios. However, directly replacing adoption models with LLM reasoning raises concerns regarding interpretability, reproducibility, and behavioural validity. This paper proposes a hybrid framework for LLM-assisted specification design, integrating bounded behavioural rubrics and structured scenario specifications into a calibrated agent-based model (ABM) of solar photovoltaic (PV) adoption by Irish dairy farms. The proposed approach preserves the original techno-economic adoption mechanism while augmenting it with bounded behavioural modulation and scenario-driven uncertainty analysis. Behavioural effects are represented through interpretable conservative, balanced, and optimistic rubrics, while future policy and market conditions are explored through fixed, rule-validated

---

### [51] Same Request, Different Answer: Quantization Amplifies Cache-Induced Divergence in LLM Serving

**链接**: https://arxiv.org/abs/2609.04748
**作者**: Aditi Patodiya
**来源**: cs.SE cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prefix caching, in which a serving engine reuses the key and value tensors of a shared prompt prefix across requests, is enabled by default in the major open-source stacks and treated as a transparent optimization. We measure what it costs in reproducibility, and find that the cost rises sharply with weight quantization. Holding the model, decoding parameters, seed, and request order fixed, and issuing every request serially at batch size one, we ran an eighty-episode multi-turn agentic tool-use workload with caching enabled and disabled across two engines and four weight formats. Enabling the cache changed the agent's trajectory on 36.2 percent of episodes at 16-bit precision and on 75.0 percent at four-bit, a gradient that survives re-measurement under a controlled cache configuration. With caching disabled, repeated execution was bit-identical in every configuration, 0 of 800 episodes, which bounds other sources of nondeterminism at 0.5 percent. Repeated cache-enabled runs did diver

---

### [52] First Things First: Teaching LLM-Based Agents to Prioritize Must-Haves before Nice-to-Haves

**链接**: https://arxiv.org/abs/2609.05224
**作者**: Tianjie Ju, Xinyue Xu, Wanxuan Sun, Lingxiao Diao, Gongshen Liu, Zhuosheng Zhang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent progress in multimodal large language models (MLLMs) has fueled significant enthusiasm in their potential to act as autonomous agents for real-world tasks. However, scenarios requiring agents to fulfill users' complex, structured requirements remain largely underexplored. In this work, we examine reasoning tasks under three distinct requirement scenarios: (i) Must-have requirements uniquely determine a unique feasible solution; (ii) Multiple answers satisfy the must-have requirements and are prioritized via the nice-to-have requirements; and (iii) No candidate solution satisfies the must-have requirements, in which case the agent should abstain from generating a response. We evaluate state-of-the-art MLLMs on 3,649 carefully constructed problems that reflect realistic service scenarios, including e-commerce, booking, and map-based or ride-hailing. Our evaluation reveals that existing MLLMs exhibit catastrophic failures in all scenarios. They frequently misinterpret task requirem

---

### [53] KernelGenBench: A Multi-Source and Multi-Chip Benchmark for LLM-based Kernel Generation

**链接**: https://arxiv.org/abs/2607.27231
**作者**: Peiyu Zang, Jian Tao, Jialing Zhang, Yichen Yuan, Wentao Zhang, Guang Liu 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] Controlling and Assessing Appropriate Persona Use in LLM-based Dialogue Generation

**链接**: https://arxiv.org/abs/2609.04676
**作者**: Jongkyung Shin, Inkyu Lee, Chiehyeon Lim
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In persona-based dialogue generation (PDG), LLMs often overuse persona attributes by incorporating them regardless of dialogue context, resulting in unnatural responses. Despite its practical significance, the underlying causes remain unexplored, with no method to mitigate this problem or metric to assess the appropriateness of persona use. To address these issues, we first conduct a comprehensive analysis of LLM-based PDG, revealing that LLMs exhibit a systematic bias to incorporate all given persona attributes, and that existing metrics fail to capture contextual appropriateness. Building on these findings, we propose Self-CONtrastive Persona Overuse Suppression (SCONPOS) to mitigate overuse by directly intervening in LLMs' internal representations at the prompt encoding stage, without requiring any response generation. We further propose the Persona Appropriateness Score (PAS), a novel metric that penalizes both overuse and underuse. Experimental results demonstrate that SCONPOS sys

---

### [55] ConsensusBench: Benchmark of Consensus Nodes for LLM Reasoning via Outcome Reward Densifying

**链接**: https://arxiv.org/abs/2609.04648
**作者**: Shi-Qi Yan, Chao-Hong Tan, Qian Chen, Wen Wang, Xiangang Li, Zhen-Hua Ling
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) has become one of the primary paradigms for reasoning enhancement of large language models (LLMs). In particular, Group Relative Policy Optimization (GRPO) and related algorithms have demonstrated strong performance with outcome-level rewards. However, these methods depend solely on the final answer, without feedback regarding which intermediate steps contribute to success or failure. As task complexity and reasoning trajectory length increase, such sparse final-answer rewards become increasingly insufficient. To address this limitation, we introduce ConsensusBench, a novel dataset designed to provide rule-based process-level signals. We posit that a correct final answer relies on a small set of intermediate conclusions throughout the reasoning process, which can be seen as a verifiable sub-outcome. We identify these sub-outcomes by filtering correct trajectories from N rollouts and clustering semantically equivalent intermediate statements. We call these cl

---

### [56] GRACE: Graph-Grounded Reflective Agent Copilot Engine for Expert-in-the-Loop Knowledge Expansion

**链接**: https://arxiv.org/abs/2609.04442
**作者**: John Seon Keun Yi, Joshua R. Minot, Dokyun Lee
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models deployed in high-stakes settings frequently generate plausible but ungrounded claims. Standard retrieval-augmented generation (RAG) pipelines offer limited remedy, since they retrieve isolated passages without tracking cross-document evidence relationships or quantifying uncertainty. We introduce GRACE (Graph-grounded Reflective Agent Copilot Engine), a framework that deconstructs LLM responses into atomic claims and grounds them against trusted knowledge priors within a weighted bipartite graph. Edge weights encode the closeness of each claim to the priors, enabling weighted centrality analysis that classifies claims as Grounded, Refuted, or Boundary. Such classification identifies not just hallucinations but also novel or contested claims at the frontier of the model's knowledge. To efficiently allocate human or agent resources, we formulate a Return on Attention (RoA) objective that defers a claim to expert review only when its priority-weighted uncertainty exc

---

### [57] Model Retirement Creates Reproducibility Risk in Biomedical AI Publications

**链接**: https://arxiv.org/abs/2609.04699
**作者**: Nathan Wolfrath, Meghan Conroy, Thomas Kosten, Dave Bell, Bhabishya Neupane, Jonah Kindel 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background. Large language models (LLMs) are being adopted in biomedical research at a rapid and accelerating pace, yet commercial services that host many widely used models operate under deprecation schedules that can complicate scientific reproducibility. Methods. We searched PubMed for original research articles from 2022 through March 2026 that applied a specific LLM to a biomedical task. An extraction agent identified model names from 61,077 article abstracts with human reviewers validating a subset for extraction accuracy. Extracted model names were normalized to canonical model identifiers. Lifecycle data (release date, retirement date, status) were compiled for the 50 most frequently used models. Results. We identified 8,931 paper-model mentions spanning 5,242 unique publications after restricting the analysis to the 50 most frequently used models. Among these mentions, 77.7% cited a commercial closed-weight model. Overall, 42% involved a model that was already retired by the t

---

### [58] A Repeated-Measurement Study for Cultural Analytics of English Song Lyrics Using Five Large Language Models

**链接**: https://arxiv.org/abs/2609.04428
**作者**: E. Cho Smith, Samuel Ho, Dawn Laux
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used to annotate cultural texts at scales that are impractical for human coders. However, before their outputs are treated as measurements of latent social constructs, it is necessary to establish whether those measurements are reliable. This study evaluates five LLMs as zero-shot annotators of four social constructs expressed in English song lyrics: self-esteem, self-control, seeking belonging, and seeking recognition. Using repeated annotations of a large lyric corpus, we examine three properties of LLM-based measurement: consistency across repeated runs, convergence across models, and transferability of consensus labels to supervised classification. The findings show that LLM-based measurement is not uniformly reliable across constructs. Self-esteem exhibits the strongest repeated-measurement reliability across models, while seeking recognition is generally less stable; self-control and seeking belonging show intermediate but model-depen

---

### [59] From Answers to Interpretations: Rethinking Ambiguity-Induced Aleatoric Uncertainty Estimation in LLMs

**链接**: https://arxiv.org/abs/2609.04543
**作者**: Omer Nahum, Niv Nayman, Jonathan Fhima, Alon Zolfi, Jeremy Levy, Shai Mazor 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A key challenge in reliable LLM deployment is recognizing when uncertainty reflects irreducible variability in the task rather than limitations in the model's knowledge. In language tasks, a central source of such aleatoric uncertainty is input ambiguity or underspecification, where multiple interpretations remain plausible. Existing decomposition methods estimate aleatoric uncertainty by generating multiple clarifications of the input, querying the model for an answer under each clarification, and comparing the resulting answers. We argue that answers are not necessary for identifying ambiguity: they are often redundant, add avoidable cost, and can mislead through epistemic leakage. We support this claim theoretically, and propose a clarification-only approach that estimates this ambiguity-induced component directly from the space of plausible interpretations, without answers to the clarified inputs. Using ambiguity detection as an operational evaluation across three benchmarks, this 

---

### [60] Do LLMs Exhibit Coherent Knowledge Structures in Mathematical Reasoning? A Perspective from Knowledge Space Theory

**链接**: https://arxiv.org/abs/2609.05245
**作者**: Peng Cui, Heejin Do, Mrinmaya Sachan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human knowledge is inherently structured and interdependent: mastery of a concept requires prior mastery of its prerequisites, a principle formalized by Knowledge Space Theory (KST). While LLMs achieve strong performance on complex reasoning tasks, it remains unclear whether they exhibit coherent, human-like knowledge structure. We introduce a KST-grounded framework for evaluating LLM knowledge structure in mathematical reasoning, using it as a normative framework to analyze whether LLM behavior adheres to principled knowledge dependencies. Evaluating eight open- and closed-source LLMs against real human learners, we find that (1) LLMs do not adhere to human knowledge structure -- they frequently violate knowledge dependencies and fail to leverage related knowledge provided in context to improve performance on dependent questions; (2) LLMs do not share a consistent knowledge structure among themselves, as reflected by low overlap in their knowledge distributions. Furthermore, these str

---

### [61] SQL-Zero: Self-Evolving Text-to-SQL

**链接**: https://arxiv.org/abs/2609.04697
**作者**: Daniel Machado Pedrozo, Julia Soares Dollis, Bryan Lincoln Marques de Oliveira, Vinicius Alboneti Aguiar, S\'avio Salvarino Teles de Oliveira, Telma Woerle de Lima Soares
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training a competitive Text-to-SQL agent usually depends on human-annotated natural-language/SQL pairs, which are expensive, domain-specific, and a bottleneck for scaling to new databases. We show it is possible to train a competitive solver with zero annotated pairs. We introduce SQL-Zero, a proposer-solver self-play in which a challenger and a solver start from the same base LLM and the only ground truth is execution against the database itself. The challenger generates SQL pairs calibrated to the solver's current difficulty (targeting "hard but solvable"), and both roles are updated with GRPO in alternating turns, with a template-level repetition penalty on the challenger to prevent diversity collapse. Training on BIRD databases with no labels, self-play improves over the zero-shot base on BIRD dev by 6.6 points at 3B and 7.3 points at 7B. It also scores higher than a matched control trained under the same recipe on human BIRD gold over the same databases, although an exact paired t

---

### [62] MaxKernel: Agentic Kernel Generation for TPUs

**链接**: https://arxiv.org/abs/2609.04523
**作者**: Shangkun Wang, Nina Cai, Charles Hoong, Julian Walker, Gerson Kroiz, George Vanica 等 (10 人)
**来源**: cs.AI cs.PF cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing and authoring high-performance custom kernels for accelerators is a complex task that requires deep hardware-level expertise. Large Language Models (LLM) can be leveraged together with real-time compiler feedback to build agentic systems for kernel generation. In this work, we present MaxKernel, a multi-agent system that implements three distinct paradigms for TPU kernel development: (1) a Human-in-the-Loop (HITL) agent for collaborative, step-by-step design; (2) an Autonomous (Auto) agent that executes a fully automated, metric/trace-driven optimization loop; and (3) a Graph-Based Autonomous Search that scales the Auto agent for global exploration of the design space. All three paradigms leverage a shared pool of specialized sub-agents to handle planning, implementation, self-debugging, testing, and hardware profiling. We evaluate MaxKernel on JaxBench, a comprehensive suite of 50 diverse kernel tasks for TPUs, alongside complex, real-world workloads from state-of-the-art op

---

### [63] KVMem: Virtualizing Million-Token Agent Workspaces on a Consumer GPU

**链接**: https://arxiv.org/abs/2609.04852
**作者**: Di Chai, Leye Wang, Zeshen Su, Zhiguo Xia, Zhihang Yu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM agents operate in persistent workspaces whose accumulated history can exceed both GPU KV capacity and the model's native context window. Existing systems typically compact older context into summaries or retrieve it later as text, either losing fine-grained execution evidence or repeatedly prefilling content that the model has already processed. We present KVMem, a KV-context virtualization system that preserves overflowed workspace history as paged KV state across GPU memory, host memory, and NVMe. KVMem uses lightweight, model-native attention-space indexes to select relevant historical blocks and materializes a query-dependent execution view bounded by the model's native context window. Extensive evaluations on long-context agent benchmarks spanning histories up to one million tokens, including LongMemEval, MemoryAgentBench, and AgentLongBench, show that KVMem generally achieves higher task utility and greater inference efficiency than compaction-based approaches, the de 

---

### [64] Generating Constructive Feedback on Stories via Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.04824
**作者**: Maja Stahl, Timon Ziegenbein, Henning Wachsmuth
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constructive feedback is crucial for creative writers to refine their storytelling abilities. Since receiving feedback from human experts is often costly and time-intensive, large language models (LLMs) offer a scalable and efficient alternative as automatic writing assistants. Despite their potential, research indicates that LLM-generated feedback is often generic, lacks actionability, and fails to identify which writing issue is most critical. To address these limitations, we present a reinforcement learning approach that steers LLMs to generate constructive feedback without the need for ground-truth feedback. We train our model using group relative policy optimization (GRPO) with a novel multi-component reward function aiming at constructiveness: it prioritizes feedback that is uniquely tailored to the story, helps to improve story quality, and addresses the most critical writing issue. In automatic and human evaluation across three story corpora, our approach outperforms state-of-t

---

### [65] MABPD: Multi-Agent Bias Probing & Detection via Structured Argument Debate

**链接**: https://arxiv.org/abs/2609.04841
**作者**: Garvit Joshi (1), Stavya Dhyani (1), Jasmine (1), Arun Chauhan (1) ((1) Graphic Era University, Dehradun, India)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Media bias in news articles operates through subtle linguistic cues---loaded language, selective framing, and strategic omission---that resist single-model detection and have traditionally required large annotated corpora for supervised training. We ask whether structured multi-agent deliberation can serve as a principled, training-free alternative to supervised classification for this task. We introduce MABPD (Multi-Agent Bias Probing & Detection), a pipeline in which three specialized LLM agents analyze an article from complementary perspectives and resolve disagreements through a Structured Argument Debate (SAD) protocol. SAD implements a domain-motivated asymmetric burden of proof---biased claims without grounded textual evidence carry zero weight---combined with role-weighted voting and post-consensus verification, replacing task-specific supervised decision boundaries with explicit deliberative structure. Ablation confirms that this structured deliberation, not mere agent paralle

---

### [66] GUT: Quantifying and Optimizing the Reasoning Uncertainty of LLMs via Graph Complexity

**链接**: https://arxiv.org/abs/2609.05284
**作者**: Shuang Liang, Xin-Yu Hu, Xiang-Jun Ou, Shao-Qun Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent years have witnessed great advances in the reasoning ability of Large Language Models (LLMs). However, the reasoning processes of LLMs often exhibit uncertainty, where LLMs often produce a proliferation of divergent branches at each reasoning step even when fed the same prompting inputs, and certain branches exhibit evidently incredible, even nonsensical, reasoning chains and results. In this paper, we propose the Graph-complexity-based UncerTainty (GUT) method for investigating the reasoning uncertainty of LLMs. The key idea of GUT is to characterize the potential branches of each reasoning chain with a directed acyclic graph, thereby ensuring that all potential branches are comprehensively covered within the graph space. Building upon this recognition, we further build two modules of GUT, that is, a Quantification (GUT-Q) module and an Optimization (GUT-O) module, for quantifying and reducing the reasoning uncertainty of LLMs, respectively. GUT-Q measures LLM reasoning uncerta

---

### [67] Multi-Step Tool-Calling over Korean Open Public APIs: A Benchmark and a Data-Synthesis Recipe

**链接**: https://arxiv.org/abs/2609.05395
**作者**: Dain Kim, Eungi Cho, Kyumin Kim, Shinyeong Noh, Kyuseong Lim
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data-sovereignty regulations increasingly require public institutions to deploy open-source, on-premise LLM agents that chain multiple tool-calls across live government APIs. However, open-source models consistently underperform in this multi-step setting, and no existing benchmark measures the gap. We introduce the Korean Open Public API Benchmark (KOPA-Bench), comprising 145 real-world tasks. To close this gap, we present EDGE, an Execution-grounded Dynamic Graph for tool-calling data synthEsis driven by live execution. EDGE builds a graph of how each tool's output can feed another's input, keeps only the links that succeed when actually called against the live APIs, and traverses these verified links to synthesize executable multi-step trajectories. Fine-tuned via GRPO on the resulting dataset, our 9B model nearly matches the untuned 27B model from the same family, improving substantially not only on KOPA-Bench but also on the BFCL benchmark.

---

### [68] On Epistemic Diversity in Large Language Models

**链接**: https://arxiv.org/abs/2609.04835
**作者**: Elisabeth Kirsten, Nicole Kr\"amer, Muhammad Bilal Zafar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used not only to retrieve information, but to answer questions, explain, teach, and support inquiry. In such settings, evaluation cannot be exhausted by accuracy or alignment alone. A system may give a correct answer while still narrowing users' access %to knowledge. to alternative valid answers, explanations, or reasoning routes. Drawing on the broader notion of epistemic diversity in philosophy and social epistemology, we formalize it in the context of LLMs as the range of valid answers, explanations, and reasoning routes that an LLM exposes to users. We argue that epistemic diversity is a useful evaluation dimension for settings where LLMs are used to support knowledge-intensive tasks. We propose a preliminary framework for conceptualizing and measuring epistemic diversity in LLMs, and operationalize it in two domains. We find that frontier LLMs often exhibit epistemic narrowness, repeatedly collapsing large valid answer spaces onto smal

---

### [69] At Equal Inference Cost, Multi-Agent Structure Does Not Beat a Single Frozen Agent

**链接**: https://arxiv.org/abs/2609.04217
**作者**: David Dylan, Aoife Brennan, Cian Murphy, Niamh O'Sullivan, Conor Kelly, Saoirse Walsh
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM pipelines, such as Planner-Executor-Critic teams, often report gains over single agents, but these gains usually come with higher inference cost because the team makes multiple model calls per environment step. Existing automated methods search over roles, topologies, and prompts, but typically compare teams against single agents at equal environment rollouts, giving the team extra compute. We instead fix the total number of language-model calls and ask whether evolving a multi-agent team still beats evolving a single agent under the same budget. We introduce MA-Evolve, which represents a Planner-Executor-Critic team as three evolvable role prompts and optimizes them by per-role coordinate ascent over a shared frozen 7B backbone. On ALFWorld, evolving a single executor significantly improves over the unevolved agent, while the full team achieves the highest mean but is not statistically better than the single agent: 0.769 versus 0.754, p = 0.80, despite using 1.8 times 

---

### [70] Persistent Teacher Anchoring for Tool-Using Agents

**链接**: https://arxiv.org/abs/2609.04773
**作者**: Hyun Bin Park (1), Kyungho Song (2), Sangmin Lee (1), Du-Seong Chang (1) ((1) Sogang University, (2) University of Michigan, Ann Arbor)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distillation is common in LLM post-training, where on-policy knowledge distillation (OPKD) uses student-generated trajectories to prepare the student for downstream RL. At each state, the student matches a next-token distribution supplied by the teacher. As the rollout enters states the teacher would not visit, the teacher-student distribution gap can accumulate. In tool use, this gap becomes consequential because student-written calls execute before supervision and their observations shape later prefixes. Proposer-verifier generation addresses this drift by letting the teacher decide which student-proposed text is retained during generation. Existing formulations govern text but leave tool execution outside their scope. We propose Persistent Teacher Anchoring (PTA), a student-induced but teacher-committed rollout construction. PTA retains chunk-level verification and adds turn-level commitment, allowing a call to reach the environment only after the teacher has verified the entire tur

---

### [71] ARIA - An Agentic Framework for Autonomous Testing of Infotainment Systems

**链接**: https://arxiv.org/abs/2609.04913
**作者**: Ant\'onio Azevedo, Bruno Lima and Jo\~ao Pascoal Faria
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automotive infotainment validation still relies on manual testing, slow, costly, and incompatible with agile releases and OTA updates. Scripted automation only partly helps: it couples test logic to implementation, yielding brittle, high-maintenance suites. Existing LLM-driven frameworks mostly target web/mobile apps, using single- or dual-agent setups that overload one or two models with perception, planning, action selection, and validation at once, prone to hallucinations and unproductive exploration loops given infotainment complexity. We present ARIA (Autonomous Real-time Infotainment Assessment), a multi-agent LLM framework that autonomously runs end-to-end tests on Android infotainment systems via visual interaction, using a closed-loop pipeline of four specialized agents per step plus a report stage. From single-sentence scenarios (path, action, expected outcome), ARIA runs the interactions and produces reports, reproducible scripts, and visual evidence per step. Evaluated on a

---

### [72] GEPARD - Generative, Prosody-aware, Autoregressive text-to-speech model for Realtime Dialogue

**链接**: https://arxiv.org/abs/2609.04222
**作者**: Denis Pavlov, Ulanbek Abdurazakov, Nursultan Bakashov
**来源**: eess.AS cs.CL cs.LG cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present GEPARD (Generative, Prosody-aware, Autoregressive text-to-speech model for Realtime Dialogue), a streaming text-to-speech model for real-time spoken dialogue. GEPARD generates speech autoregressively with an LLM backbone - text and audio embeddings are trained together in a single decoder-only model - and decodes it to a waveform with an FSQ-based neural codec, streaming audio chunk-by-chunk as text arrives. Our central goal is a TTS architecture served by a standard LLM engine (vLLM) without modifying its compute kernels. This defines the overarching design principle: the backbone is a standard full-attention transformer, while all non-trivial auxiliary mechanisms - zero-shot voice cloning, text augmentation, and classifier-free guidance - are moved out of the autoregressive decode loop into prefill, or distilled directly into the weights. On streaming end-to-end inference, a single stream reaches a Real-Time Factor of about 0.067 (roughly 15x faster than real-time); under 

---

### [73] Can Activation Steering Capture Multidimensional Authorship Style?

**链接**: https://arxiv.org/abs/2609.04792
**作者**: Hieu Tran, Calvin Bao, Marine Carpuat
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation steering has shown promise for controlling LLM generation along well-defined attributes, but it remains unclear whether it can handle the multidimensional and hard-to-define nature of authorship style. We ask whether structured contrastive prompting along rhetorically-motivated dimensions can construct rich style representations directly in activation space, bypassing the need for natural language style descriptors or dedicated training. We find that the resulting directions share a common authorship backbone while conflicting on aspect-specific residuals that carry genuine stylistic signal, explaining why naive aggregation fails. We operationalize this in Aspect-Aware Activation Steering (A3S), a training-free framework that merges per-aspect contrastive directions with interference-aware aggregation and tunes steering strength per instance. A3S improves authorship style transfer where it is genuinely multi-aspect, outperforms a trained baseline in preference evaluations on

---

### [74] Evaluating Large Language Models for Forced Outage Risk Prediction: Benefits and Comparison to Machine Learning

**链接**: https://arxiv.org/abs/2609.04272
**作者**: Christos Petridis, Zoran Obradovic, Mladen Kezunovic
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study examines the ability of large language models (LLMs) to predict the risk of weather-related forced outages in the distribution grid in a zero-shot framework, without labeled training data. The problem is formulated as a binary severity classification task across three forecast horizons (3h, 6h, 12h), using six years of outage records and high-resolution weather data for a utility service area in central Texas. Four zero-shot LLMs are benchmarked against two supervised classifiers across two input configurations: one using current weather observations and the other using weather forecast data. Results show that supervised models outperform LLMs on macro-F1 and precision, while newer LLM generations achieve competitive scores. Beyond accuracy, LLMs offer complementary strengths in actionable reasoning and geographic scalability, suggesting that combining them with supervised models may be the best practice.

---

### [75] Scalable Context Orchestration for Serving LLMs Over Voice

**链接**: https://arxiv.org/abs/2609.04288
**作者**: Linyi Jiang, Silvery D. Fu, Yifei Zhu
**来源**: cs.SD cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Voice AI applications are gaining popularity as advances in large language models (LLMs) enable more natural and accessible spoken interactions. Serving these applications requires accounting not only for what users say, but also for how they speak (e.g., speaking rate) and the conditions under which their audio is captured and transmitted (e.g., background noise and packet loss). However, existing LLM systems represent conversation context as a flat, growing sequence of messages, leaving voice-specific context implicit in the audio. As a result, they can generate responses that are poorly aligned with user preferences, degrade interaction quality under adverse environmental conditions, and incur high costs over long voice sessions. We present llmovoice, a context-management middleware that explicitly models voice context and orchestrates its use. At each turn, llmovoice constructs a bounded voice context from the current user input, relevant interaction history, and explicit paralingu

---

### [76] Beyond Aggregate Scores: Behavioral Correctness Assumptions for Assessing Reference-Based Automatic Evaluation Methods

**链接**: https://arxiv.org/abs/2609.05289
**作者**: Maria Mahbub, Ashley Rice, Michael R. Munroe, Amidu Kamara, and Amir Sadovnik
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated reference-based evaluation methods play a critical role in assessing natural language generation systems. Existing meta-evaluation primarily measures agreement with human judgments or benchmark labels, providing limited insight into evaluator behavior under controlled conditions. We introduce behavioral correctness assumptions, a complementary framework for evaluating reference-based automatic evaluation methods. We define a taxonomy of correctness-preserving and correctness-altering assumptions and operationalize them through controlled response transformations that specify expected scoring behaviors. We evaluate diverse lexical, character-level, semantic, LLM-based, and hybrid evaluators and analyze their assumption-level behavior, stability, sensitivity, repeat-run variability, configuration sensitivity, and reproducibility. Our experiments reveal distinct behavioral trade-offs across evaluation paradigms: no evaluator satisfies all proposed correctness assumptions, and ev

---

### [77] Cost-Aware Hierarchical Multi-Agent Ransomware Detection and Family Attribution

**链接**: https://arxiv.org/abs/2609.04820
**作者**: Mubashar Iqbal, Asifullah Khan
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ransomware detection and family attribution require analysis of different modalities because it can use packing, obfuscation, process manipulation and runtime evasion techniques. However, conventional multimodal usually uses all available modalities for every sample resulting in unnecessary computational cost and increased latency. In this paper, we present a Cost Aware Hierarchical Multi-Agent System (HMAS) for adaptive ransomware detection. The proposed architecture organizes specialized agents into hierarchical domain controllers coordinated by a Meta Orchestrator. Static analysis is used as the initial low-cost modality while additional dynamic and memory modality is selectively used when confidence is insufficient or specialist agents exhibit disagreement. A cost model incorporates modality use and processing overhead. It enables the orchestration policy to balance analysis performance against computational cost. A locally deployed large language model provides verification for se

---

### [78] Large Language Models for HVAC Operations in Building Energy Systems: A Critical Review of Methods, Applications, and Deployment Readiness

**链接**: https://arxiv.org/abs/2609.05314
**作者**: Alexander Neubauer, Tianzhen Hong, Han Li, Mengbo Yu, Amin Darbandi, Yannick F\"urst 等 (7 人)
**来源**: cs.AI cs.CL cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building automation systems generate rich sensor data yet remain insight-poor because heterogeneous point naming, missing metadata, and fragmented documentation obstruct their operational use. This systematic review analyses and codes 66 peer-reviewed studies on large language models (LLMs) for HVAC operations published between 2023 and March 2026. Each study is classified across five application families and three LLM method families and assessed for evidence realism, deployment readiness, and the responsibility boundary between the LLM and physical HVAC decisions. The corpus is concentrated in building energy modelling (BEM, 32 of 66 papers), while load forecasting remains too sparse for subfield-level conclusions. Only four studies reach pilot-level evidence, and none reports sustained operational deployment. No study was classified as ready-now for industry adoption; three were near-term and 63 research-only. Nevertheless, several bounded, human-in-the-loop uses merit near-term tri

---

### [79] How to Speculate about Uncertainty in Agentic Coding? A Draft-Model Gate Method

**链接**: https://arxiv.org/abs/2609.05274
**作者**: Konstantin Grotov and Valentin Malykh
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents deployed for software engineering fail expensively: they act confidently wrong, and bad actions are recognized only after costly execution and retry. We present Speculative Uncertainty (SU), a method that recovers a predictive failure signal for a black-box agent from its output tokens alone, with no access to logits, weights, activations, or repeated sampling. Inverting speculative decoding, a small open-weight draft model scores the agent's already-generated trajectory in a single forward pass. From these speculative cross-likelihoods we extract phase-aware features by separating the reasoning and action spans, and calibrate them against a verifiable objective. SU produces a failure-likelihood score that any downstream policy, such as routing, human intervention, or extra test-time compute, can consume directly. To show the signal is actionable, we instantiate one such policy, a pre-execution veto gate, on software engineering agents Qwen3-Coder-480B and closed-source Clau

---

### [80] PetQA: Benchmarking Veterinary Knowledge and Clinical Reasoning

**链接**: https://arxiv.org/abs/2609.04598
**作者**: Taegyun Kim, Youngwook Ham, Jungwook Rhim, Ju-Hyun An, Sungkyu Park, Kunwoo Park
**来源**: cs.CL cs.AI cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce PetQA, a Korean long-form question-answering (QA) benchmark for evaluating veterinary knowledge and clinical reasoning in large language models (LLMs) and large vision-language models (LVLMs). PetQA contains 10,076 text-only and 8,751 multimodal QA pairs derived from real-world questions about dogs and cats, paired with answers from expert veterinarians. Its test split, PetQA-Bench, further includes annotations for question types and clinical conditions. We evaluate eighteen models using ROUGE, BERTScore, and LLM-as-a-judge metrics for factuality and helpfulness under three settings: zero-shot inference, retrieval-augmented generation (RAG), and supervised fine-tuning (SFT). The benchmarking results provide an overview of the strengths and limitations of current models in addressing veterinary clinical queries and highlight the need for more effective adaptation methods to develop clinically reliable AI systems for veterinary care. To facilitate broader use, we additionall

---

### [81] Conformity Breaks Conformal Prediction

**链接**: https://arxiv.org/abs/2609.04445
**作者**: Yibo Hu, Hanyu Su
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A conformal certificate can be valid when an LLM answers alone and invalid when the same LLM sees peers that unanimously assert a wrong answer. The question is unchanged; the model's score for the correct answer changes. We call this a score-mechanism shift: clean calibration certifies how the model scores answers alone, but not how it scores them under peer pressure. We show that this shift silently breaks conformal prediction in multi-agent LLM systems. Across open-weight models and multiple-choice QA tasks, coverage falls from a calibrated 90% to 74% under unanimous-wrong peers at the standard alpha = 0.10 operating point. The average hides a sharper failure: by targeting the low-confidence items the certificate still covers, an attacker nearly halves coverage on that subgroup, from 87% to 47%, while the monitored average remains much higher. The failure also reaches the decision layer: a system that should escalate when uncertain can instead become confident enough to act on the at

---

### [82] AlcaTRAz - Anchored Tree-Rule Defense Against Jailbreaks

**链接**: https://arxiv.org/abs/2609.03693
**作者**: Jakub Re\v{s}, Petr Ka\v{s}ka, Martin Pere\v{s}\'ini, Martin Ukrop, Kamil Malinka
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are vulnerable to jailbreak attacks that bypass safety alignment through carefully crafted prompts. Many existing defenses require access to model weights or internals, making them difficult to apply to black-box deployments. We propose AlcaTRAz (Anchored Tree-Rule defense Against jailbreaks), a prompt-level defense based on rule trees that operates exclusively on the input text and requires no modification or retraining of the target model. The method automatically learns a transferable transformation rule that inserts controlled character-level perturbations at selected positions, thereby disrupting structural regularities exploited by jailbreak attacks while largely preserving the model's utility on benign queries. We evaluate the proposed method across 33 open-weight models, 22 jailbreak attack types, and a benchmark of short, single-turn benign questions, comparing against three representative prompt-level baselines (Llama Guard, RA-LLM, Goal Prioritiz

---

### [83] Motion-Omni: End-to-End Joint Speech and Full-Body Motion for Spoken Dialogue

**链接**: https://arxiv.org/abs/2609.04250
**作者**: Chengqian Ma, Wei Tao, Haoyu Zhang, Yiwen Guo
**来源**: cs.SD cs.CV eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An avatar that holds a conversation should decide what to say and to move while saying it, yet these abilities live in separate model families: spoken dialogue models produce speech without motion, and co-speech motion models produce motion only from audio handed to them. The standard remedy is a cascade that first generates the spoken response and then runs a motion model over the finished audio, which requires a second full inference pass and precludes any joint optimisation between the two. We present Motion-Omni, an end-to-end framework in which a spoken dialogue model natively outputs explicit facial expression together with hand, upper-body and lower-body motion, generated directly from the hidden states that produce the speech. Joint training is not optional here: with the speech pathway frozen, motion remains misaligned with the audio, and co-adapting the LLM, Speech Generator and Motion Generator under both objectives is what recovers alignment while retaining spoken-dialogue 

---

### [84] TruthInsightBench: An Evidence-Grounded Benchmark for Automated Evaluation of Open-Ended Scientific Discovery Agents

**链接**: https://arxiv.org/abs/2609.05079
**作者**: Zhibo Yang, Chen Zhang, Yuewei Zhang, Hao Wang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous coding agents are increasingly proposed as AI-scientist systems that conduct analyses and write research reports, but executing a prescribed analysis is not the same as making a discovery. Existing benchmarks are configured for reproduction: tasks, data, and rubrics are built around a hidden target study, and recovery of its result is rewarded. We present TruthInsightBench, a benchmark configured for discovery. Its 40 blind tasks, drawn from 40 peer-reviewed studies across 10 scientific domains, expose only a neutral scientific objective and frozen data; source conclusions, expected values, and analysis paths are withheld, leaving the agent to determine what claim the data support. A fixed LLM-based judge scores the evidentiary maturity of an agent's own claims along six dimensions, operationalized as 29 artifact-grounded items, with automated, deterministic aggregation and no per-instance human grading, so evaluation can be repeated automatically as agents evolve. On one fr

---

### [85] Distill Globally, Adapt Locally: Reasoning Distillation and Product-Type Test-Time Training for Scalable Trade-Up Recommendation

**链接**: https://arxiv.org/abs/2609.05363
**作者**: Siliang Liu, Mohammad Ghasemi, Sapan Patel, Amin Banitalebi-Dehkordi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trade-up recommendation identifies higher-quality alternatives that preserve a customer's purchase intent while offering upgraded benefits. Large language models (LLMs) can reason about such distinctions, but applying them directly to hundreds of millions of product pairs is operationally impractical. We introduce a two-level framework that distills LLM reasoning into an efficient non-generative student and adapts its decision boundary to product-type-specific trade-up criteria. At Level 1, a retrieval-augmented few-shot LLM teacher generates structured relation labels and natural-language rationales. These rationales supervise a compact embedding-pair classifier through alignment and contrastive objectives; at inference, the student uses only two precomputed 768-dimensional product embeddings, with no LLM calls or text generation. On a fixed human-annotated benchmark of 8,352 pairs, a 15.5M-parameter four-class reasoning-distilled student achieves AUC 0.924 (95% CI [0.918, 0.929]), co

---

### [86] How a Chatbot's Response Style Shapes a Classroom: A Multi-Agent Simulation of Students Consulting AI

**链接**: https://arxiv.org/abs/2609.05018
**作者**: Rin Tamai and Yuya Dan
**来源**: cs.HC cs.AI cs.CY cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based chatbots are increasingly used as everyday confidants. Because they are designed to maximize user satisfaction, they can respond with excessive empathy and affirmation, which may reinforce mistaken beliefs and foster dependence on AI. While the psychological effects of chatbots on individual users have begun to be studied, how the psychological states and relationships of many users evolve when they keep consulting an AI is hard to observe in real settings. We build a virtual classroom simulation in which 20 student agents interact and, when stressed, consult either a friend or a counselor AI (Gemini 2.5 Flash). Each agent carries five state variables (stress, happiness, self-reliance, AI dependence, sociability), and each day has four phases (morning, noon, after school, night). The counselor is given six response styles via system prompts (affirming, listening, solution-oriented, reality-redirecting, inciting, blaming); a second LLM call acts as an evaluator that turns each

---

### [87] $\tau^\tau$-Bench: An Environment for End-To-End, Realistic Agent Construction

**链接**: https://arxiv.org/abs/2609.04611
**作者**: Quan Shi, Keshav Dhandhania, Karthik Narasimhan, Victor Barres
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are rapidly becoming production software, deployed to handle customer service, adjudicate disputes, and operate internal systems. Notably, the work of building them is increasingly handed to coding agents, yet existing benchmarks say little about whether an AI system can deliver one under the conditions of a real client engagement. We introduce $\tau^\tau$-bench (pronounced hyper-tau-bench), a benchmark that makes agent construction the task. A developer agent is given the records a business actually keeps, a client who holds requirements, a production API that operations must run through, a codebase to inherit, and limits on serving cost and models: the same starting point a real engagement provides. From these it must deliver a complete customer-service agent, scored by deploying that agent against held-out simulated users. Across 53 tasks spanning four domains, the strongest configuration, Claude Opus 5 under Claude Code, passes just 23.9% of evaluation simulations. Meanw

---

### [88] Uncertainty Signals for Network Intent Translation: Risk Ranking and Ambiguity Localization

**链接**: https://arxiv.org/abs/2609.04486
**作者**: Ala' A. Alsamarneh and Omar Alhussein
**来源**: cs.NI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Intent-based networking realization starts by translating high-level intents into low-level network configurations. Recent approaches have shifted toward LLM-based translation. Despite promising results, most studies focus on translation accuracy and overlook risks associated with deploying the resulting configurations. In this work, we investigate the pre-deployment translation risk of LLM-generated configurations by analyzing the model's uncertainty. We propose to use two uncertainty signals, namely sampling-based predictive uncertainty for translation-risk ranking and token-level entropy for ambiguity-source localization. We evaluate these signals on an ambiguity-controlled test set across different context types and sampling budgets, using a Llama-3.1-8B-Instruct model fine-tuned for intent translation on a vendor-specific switch platform (Juniper EX3300). The results demonstrate that predictive uncertainty provides a useful signal for ranking translations by risk across context ty

---

### [89] BIT.UA at BioASQ 14B: Modular Retrieval with pg_textsearch and Qdrant, and Agent-Based Answer Generation

**链接**: https://arxiv.org/abs/2609.04999
**作者**: Andr\'e Ribeiro, R\'uben Garrido, Alexander Christiansen, Richard A. A. Jonker and S\'ergio Matos
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper describes the participation of the BIT.UA team from the University of Aveiro in the 14th edition of the BioASQ Task B challenge on biomedical question answering. Building on our previous submissions, we introduced a substantially refactored and modular codebase, and made significant changes to both the retrieval and generation components of the pipeline. For Phase~A document retrieval, we replaced the PyTerrier PISA index with PostgreSQL-based pg\_textsearch for BM25 retrieval and adopted Qdrant for dense embedding indexing, enabling more efficient storage and GPU-accelerated similarity search. We explored HyDE-based query expansion alongside a Context-1 retrieval strategy. A new reranker training pipeline was developed, incorporating dense retrieval for negative sampling. For Phases A+ and B answer generation, we introduced an LLM-as-a-judge framework and a novel agent quorum mechanism, where multiple agents with diverse prompts debate and iteratively converge on a consensu

---

### [90] Towards Understanding Pause Token Fine-Tuning Dynamics: A Mode Retention Perspective

**链接**: https://arxiv.org/abs/2609.04489
**作者**: Jaehyeon Kim, Suhwan Kim, Nakyung Lee, Yeongoon Kim, Jimin Seo, Giho Lee 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pause-token methods improve LLM reasoning by inserting special tokens into sequences. Prior work explains these gains through computational expressivity. However, there is relatively little investigation into the training dynamics of pause tokens. We explore how pause tokens reshape the training dynamics of fine-tuning. Two controlled pilots expose distinct asymmetries. On a synthetic continual-learning task, masked pauses overwrite a previously-learned distribution roughly 4x less at matched final adaptation (H1, mode retention); on a synthetic math-reasoning probe, the boundary-adjacent token comes to encode substantially more downstream-step information (H2, non-myopic compression). We formalize a training rule consistent with both - Masked Boundary Pause (MBP), pause tokens placed at reasoning-step boundaries with their loss masked. Across 1B-8B Qwen and Llama models, MBP consistently improves reasoning, achieving gains of up to 6 points on math and 2.5 points on code, while preser

---

### [91] Leveraging Low-Level Symbolic Competences for Unsupervised Grounding in Hallucination Detection

**链接**: https://arxiv.org/abs/2609.05025
**作者**: Renato Vukovic, Hsien-chin Lin, Carel van Niekerk, Benjamin Ruppik, Michael Heck, Shutong Feng 等 (8 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hallucination-where a language model generates outputs that are factually incorrect or unsupported by the source-is a major challenge for both prompted and fine-tuned language models. Detecting hallucinations is difficult due to the opaque reasoning processes of LLMs, which often provide little insight into why a model's output may be inaccurate. In this work, we investigate whether an LLM can use an alternative, low level, symbolic competence such as SQL for unsupervised hallucination detection in some high level task. For this, we make an LLM build an SQL database from reference documents. This SQL database is then used for reasoning over the reference and the sampled response in a hallucination detection pipeline that is grounded in the database, thereby providing a neurosymbolic checkup. On RAGTruth and DiaHalu hallucination detection datasets, we find that our approach improves on direct prediction and competes with state-of-the-art hallucination detection methods, while not requi

---

### [92] Hakken: Predicting future discoveries to fill the gaps in today's knowledge

**链接**: https://arxiv.org/abs/2609.04494
**作者**: Tarek R. Besold, Uchenna Akujuobi, Pablo Sanchez, Alessandra Toniato, Kana Maruyama, Jihun Choi 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Hakken, a domain-agnostic prediction and explanation system performing knowledge prediction, i.e., growing scientific knowledge by establishing novel relationships, ones that are not limited to the deductive hull of previous knowledge. Hakken uses a transformer-based prediction model built on temporal sequences of knowledge graphs extracted from vast bodies of research publications, fused with an LLM's semantic knowledge, to predict the presence and define the type of as-yet undocumented relationships between scientific concepts. It then calls a model-agnostic explanation framework to provide accompanying information for each prediction that allows scientists to evaluate the suggested new relationship. While general purpose, we demonstrate Hakken's practical capabilities by applying it to the biomedical domain. There, Hakken's prediction model establishes a new benchmark for time-aware multi-label relation prediction, and we show that the model's output stays coherent and in

---

### [93] CABAL: Multi-Agent Simulacra for Tracing the Effects of Collusive Bidding in Peer Review

**链接**: https://arxiv.org/abs/2609.05227
**作者**: Jicheng Zhou, Kemou Li, Kahim Wong, Zheyuan Li, Zhuan Shi, Fengpeng Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent reports during the AAAI-27 review cycle highlight the risk of reviewers coordinating bids for reciprocal assignment advantage. Prior work treats bidding, reviewer assignment, and review manipulation as separate stages, leaving the lifecycle effects of collusive bidding unclear. Real-world analysis is further constrained by typically unobservable collusive intent and the lack of counterfactuals for the same conference. Motivated by this gap, we introduce \alg, an end-to-end multi-agent simulacra framework for studying reviewer assignment integrity by holding the conference environment fixed and configuring LLM-driven reviewer agents with honest or collusive policies. We further develop an affinity-guided collusive bidding strategy that uses mutual reviewer-paper affinities to construct collusion rings and select target papers, producing expertise-consistent rather than arbitrarily targeted attacks. Controlled experiments show that collusive bidding more than doubles target-paper 

---

### [94] Large Language Models with At Most One Spike per Neuron

**链接**: https://arxiv.org/abs/2609.05151
**作者**: Zhuoya Zhao, Parsa Omidi, Aref Jafari, Richard Naud
**来源**: cs.NE cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Leveraging their inherent sparse event-driven computation, spiking neural networks (SNNs) offer a promising path toward energy-efficient large language models (LLMs). Time-to-first-spike (TTFS) coding generates at most one spike per neuron within a time window, yielding extremely low firing rates. However, conventional TTFS SNNs are restricted to specific structures, making it challenging to encode certain blocks in LLM -- such as layer normalization and matrix multiplication --using TTFS. To overcome this limitation, we introduce a reference-based strategy specifically to encode the four core LLM components: embedding layers, layer normalization, attention-related operations and dropout. We construct a fully TTFS-based SNN architecture and train it end-to-end. Experiments on modern LLMs like BERT and GPT-2 demonstrate that our approach achieves performance comparable to ANN counterparts on natural language understanding and common-sense reasoning, while a clear gap remains on language

---

### [95] EVOHARNESSBENCH: Can Your Agents Keep Pace with an Evolving Harness?

**链接**: https://arxiv.org/abs/2609.04280
**作者**: Zixuan Ke, Vaidehi Patil, Haizhou Shi, Yang Li, Ye Liu, Sarath Shekkizhar 等 (10 人)
**来源**: cs.MA cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM-based agents operate through a harness of tools, reusable skills, and specialist agents that shapes what they observe and what they can do. In practice, this harness continually evolves as new capabilities are added. We introduce EVOHARNESSBENCH, a benchmark for evaluating agents under controlled harness evolution across three axes (tools, skills, and agents). Unlike existing continual-learning benchmarks for agents, which typically place non-stationarity (i.e., what changes over time) in the task stream while keeping the harness fixed, EVOHARNESSBENCH places non-stationarity in the externally supplied harness itself. It contains 17 multi-stage harness streams constructed deterministically from verifier-based benchmarks, comprising 802 tasks, 520 tools, 42 skills, and 62 agents. We evaluate two complementary settings corresponding to the central challenges of harness evolution: deployment evaluation, which isolates retention of previously accessible competence as the harness

---

### [96] MineExplorer: Evaluating Open-World Exploration of MLLM Agents in Minecraft

**链接**: https://arxiv.org/abs/2605.30931
**作者**: Tianjie Ju, Yueqing Sun, Zheng Wu, Wei Zhang, Yaqi Huo, Xi Su 等 (10 人)
**来源**: cs.CL
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] PRISM-Bench: An Audio-Centric Diagnostic Benchmark for Text-to-Audio-Video Generation

**链接**: https://arxiv.org/abs/2609.04867
**作者**: Yuchen Sun, Qian Yang, Jun Wang, Detai Xin, Guoqiao Yu, Guanglu Wan 等 (7 人)
**来源**: cs.MM cs.AI cs.SD
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text-to-audio-video (T2AV) generation has advanced rapidly, but its evaluation still underestimates the audio modality. Existing benchmarks either treat audio as an auxiliary component of video quality or assess it in isolation from audiovisual grounding, making it difficult to diagnose where current systems truly succeed or fail in audio generation. We present PRISM-Bench, the first audio-centric diagnostic benchmark for T2AV generation. Built from a rigorously curated dataset of 900 human-verified samples, PRISM-Bench factorizes audio evaluation along two orthogonal axes: audio type (Speech, Music, and Sound) and sound-source visibility (On-screen vs. Off-screen). It evaluates generated content across four perceptual dimensions (Audio-Visual Coherence, Audio Quality, Audio Expressiveness, and Prompt Following) with 35 fine-grained criteria. To ensure reliable assessment, we adopt an enhanced MLLM-as-a-Judge protocol based on blind, side-by-side comparison against ground-truth referen

---

### [98] A Roadmap for MEG Foundation Models

**链接**: https://arxiv.org/abs/2609.04461
**作者**: Philipp Th\"olke, Hamza Abdelhedi, Yorguin Mantilla-Ramos, Fouad Lbakali, Oumayma Gharbi, Catherine Duclos 等 (9 人)
**来源**: q-bio.NC cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are beginning to reshape brain-signal analysis by moving the field beyond task-specific decoding pipelines toward reusable models pretrained on broad neural datasets. Magnetoencephalography (MEG) is a compelling but still underdeveloped target for this shift: it captures human cortical dynamics at millisecond resolution while offering stronger spatial interpretability than EEG, making it especially valuable for source-resolved studies of perception, language, cognition, and clinical brain function. Yet MEG foundation models remain at an early stage, with only a small number of MEG-specific and MEG-inclusive multi-modal models, modest pretraining corpora, and emerging but still limited benchmarks. This perspective lays down the basic concepts needed to understand MEG foundation models and provides a didactic overview of the field's key design choices, including tokenization, sensor- versus source-space representations, sensor-geometry encoding, backbone architectures, 

---

### [99] ProCA: Progressive Contrastive Alignment for Robust EEG Visual Decoding

**链接**: https://arxiv.org/abs/2609.05094
**作者**: Kanglei Zhou, Chunyan Lan, Dongyang Li, Jun Zhu, Liyuan Wang
**来源**: cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalogram (EEG) visual decoding aims to recover visual semantics from non-invasive neural time-series signals, for which robust alignment between noisy neural responses and stable semantic representations is key to achieving high-performance decoding. Despite recent advances in contrastive learning, robust EEG decoding remains challenging because existing methods rely on fixed visual or textual anchors whose semantic relations may become misaligned with EEG representations that vary across trials, subjects, and learning stages. Our empirical evidence shows that this instability appears across both standard EEG decoding protocols and more challenging robustness settings, including strict cross-subject transfer and realistic personalized continual adaptation. We provide a formal analysis showing that fixed semantic supervision can bias optimization when EEG-specific relations evolve, and that structure-agnostic perturbations may distort semantically important EEG components. T

---

### [100] BioSync: Transformer-Based Cross-Modal Fusion for a Multimodal Physiological Digital Biomarker

**链接**: https://arxiv.org/abs/2609.04504
**作者**: Seyed Mahmoud Sajjadi Mohammadabadi
**来源**: cs.AI cs.IR
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cardiac, neural, behavioral, and speech measurements from wearable and mobile devices provide partial, noise-sensitive views of physiological state. BioSync combines these measurements into the \textbf{BioSync Index (BSI)}, a continuous composite digital biomarker defined under the BEST framework. The model applies multi-head self-attention to modality tokens and adds a linear branch whose hypothesis class includes standard feature concatenation. This architecture is motivated by latent-variable measurement theory and by the possibility that joint observations contain information unavailable from individual modalities. We evaluated BioSync on two literature-informed synthetic cohorts: a four-modality cognitive-decline cohort using HRV, EEG, actigraphy, and speech, and a metabolic-autonomic cohort structured around the public AI-READI wearable schema. In the cognitive cohort, BioSync and concatenation obtained AUCs of 0.928 and 0.926, respectively. In the metabolic cohort, BioSync obtai

---

### [101] DART: Depth-as-Target Pretraining for Surgical Vision Foundation Models

**链接**: https://arxiv.org/abs/2609.04555
**作者**: John J. Han, Adam Schmidt, Muhammad Abdullah Jamal, Jie Ying Wu, Omid Mohareri
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models (VFMs) are valuable in data-scarce domains such as surgery, where a single pretrained backbone can provide rich representations for many downstream tasks. Yet the dominant self-supervised pretraining paradigm uses only RGB images, leaving readily available complementary signals, such as depth maps, unused. This is a particular missed opportunity in surgery, where natural-image VFMs transfer poorly while the scene geometry is rich and informative. With strong off-the-shelf models now able to produce pseudo-labeled dense depth for any image corpus, we hypothesize that such signals can be folded into pretraining to learn better representations. We present DART, an RGB-D pretraining recipe that builds on DINOv2 with a simple modification: a pixel-space depth reconstruction objective applied to masked iBOT patches, supervised by pseudo-labeled depth. Depth is used only during pretraining, so fine-tuning and inference remain RGB-only. We find that this pixel-level re

---

### [102] Adaptation Interfaces for In-Context Tabular Foundation Models in Time-to-Event Prediction

**链接**: https://arxiv.org/abs/2609.04901
**作者**: Minh-Khoi Pham, Luca Cotugno, Dan Cernei, Alina Sirbu, Stefano Masi, Giuseppe Prencipe 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TabFMs) achieve strong performance on structured data, particularly for standard classification and regression problems. Yet, extending them to censored time-to-event prediction is challenging because it requires properly handling censoring and event-time dynamics. Building on our prior work, we further link TabFMs with CoxPH and DeepHit and revise the context-resampled training procedure. We evaluate temporal zero-shot reformulation, classification-based fine-tuning, and survival-head adaptation using frozen TabFM backbones on 74 single-risk data sets, and we additionally study 4 competing-risk data sets. Zero-shot inference is effective on smaller single-risk data sets, whereas supervised adaptation becomes increasingly advantageous as data sets scale. Cox provides the most reliably strong interface, especially for Integrated Brier Score (IBS) on larger data sets. DeepHit is relatively stronger for the time-dependent Concordance Index than for IBS, while ca

---

### [103] QoNext: Towards Next-generation QoE for Foundation Models

**链接**: https://arxiv.org/abs/2509.21889
**作者**: Yijin Guo, Farong Wen, Ye Shen, Junying Wang, Qi Jia, Xiaohong Liu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [104] YOLO with Kolmogorov-Arnold networks and vision-language foundation models for interpretable object detection with trustworthy multimodal AI in computer vision perception

**链接**: https://arxiv.org/abs/2603.23037
**作者**: Marios Impraimakis, Daniel Vazquez, and Feiyu Zhou
**来源**: cs.CV cs.AI cs.CL cs.LG cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [105] Graph Foundation Models for Recommendation: A Comprehensive Survey

**链接**: https://arxiv.org/abs/2502.08346
**作者**: Bin Wu, Yihang Wang, Yuanhao Zeng, Jiawei Liu, Jiashu Zhao, Cheng Yang 等 (10 人)
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [106] Wireless Foundation Models: State-of-the-Art and Open Challenges

**链接**: https://arxiv.org/abs/2609.04707
**作者**: Alonso M. Pacheco Huachaca, Juan J. Rodriguez Rodriguez, Ahmed Aboulfotouh, Nelson L. S. da Fonseca, Carlos A. Astudillo, and Hatem Abou-Zeid
**来源**: eess.SP cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wireless foundation models (WFMs) have emerged as a promising approach for learning reusable representations from large-scale wireless data and adapting them to downstream tasks. However, the rapidly growing literature remains fragmented across modalities, pretraining objectives, architectures, adaptation strategies, and evaluation protocols, making it difficult to assess progress toward broadly transferable models. This survey provides a systematic analysis of WFMs for physical-layer applications. We first introduce the main WFM design components, including pretraining, backbone architectures, and downstream adaptation. We then organize the literature into five physical-layer task families: signal recognition and demodulation, channel representation learning, RF sensing and localization, beam management, and spectrum sensing and monitoring, while separately examining multi-task PHY models. Across these categories, we analyze how existing models are pretrained, adapted, and evaluated, 

---

### [107] Brain4FMs: A Benchmark of Foundation Models for Electrical Brain Signal

**链接**: https://arxiv.org/abs/2602.11558
**作者**: Fanqi Shen, Enhong Yang, Jiahe Li, Junru Hong, Xiaoran Pan, Zhizhang Yuan 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Where Appearance Fails, Geometry Recognizes: A CAD-Free 3D Shape Prior That Complements Vision Foundation Models

**链接**: https://arxiv.org/abs/2609.04381
**作者**: Chenxi Tao, Seung-Kyum Choi
**来源**: cs.CV cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recognizing specific objects onboarded without a labeled training set recurs across manufacturing and service robotics, yet the conventional renderable prior, a computer-aided-design (CAD) model, is often unavailable. Two-dimensional capture supplies no shape prior, and frozen foundation features fail on geometrically similar, low-texture industrial parts. We ask what a short object-centric scan buys for recognition beyond the captured images themselves: each object is reconstructed with 3D Gaussian Splatting (3DGS), summarized into a per-class shape prototype, and fused with frozen DINOv2 image features. First, the scan recovers the recognition value of CAD without CAD: geometry from RGB-D depth (on T-LESS), 3DGS, and CAD gives comparable recognition (tied on HOPE, within 1.6 points on T-LESS); 3DGS is only a convenient route to a point cloud. Second, the payoff is governed by how recognizable the shape is: on shape-distinctive household objects (HOPE) geometry alone reaches 0.920 ver

---

### [109] Learning 3D Editing without Paired Supervision via Generative Prior Distillation

**链接**: https://arxiv.org/abs/2609.04942
**作者**: Hao Wen, Weibin Yun, Hongxing Fan, Haotian Lu, Rui Chen, Zehuan Huang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Instruction-guided 3D editing is essential for interactive content creation, yet it faces a significant bottleneck: the severe scarcity of high-quality paired training data. Existing approaches attempt to bypass this by either relying on slow test-time optimization or training on pseudo-pairs constructed via complex pipelines, which often introduce structural drift and geometric artifacts. In this paper, we propose a novel framework that learns feed-forward 3D editing without paired 3D supervision via Generative Prior Distillation. Instead of relying on ground-truth 3D pairs, our core idea is to distill visual, semantic, and geometric knowledge from powerful foundation models directly into a 3D editing model. Specifically, through a differentiable rendering pipeline, we supervise the 3D representation using two complementary signals: a 2D visual prior from an image editing model at the main editing view, and a semantic prior from a Vision-Language Model at novel views to ensure strict 

---

### [110] VISTA: Dense Multi-Label Classroom Coding with Vision-Language Models

**链接**: https://arxiv.org/abs/2609.04550
**作者**: Andrew Franck, Brendan Ng, Ben Fitzgerald, Zane Derrod, Chris Cianci, Chris Craney
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video-language benchmarks are usually constructed by the dataset authors without published reliability statistics, leaving the noise floor of the construct unknown. We argue that multimodal benchmarking benefits from methods taken from research communities that have already invested in strategies to ensure reliability. We illustrate the case with the Classroom Observation Protocol for Undergraduate STEM (COPUS): a 24-code multi-label observation instrument with a decade of peer-reviewed reliability literature. We recast COPUS as a video benchmark for multimodal foundation models, where it provides a dense set of structured labels (a 24-dimensional binary vector every 2 minutes across a 50-90 minute lecture), an externally validated vocabulary, and established literature that provides a per-code reliability target based on human evaluators. Annotations in our evaluation corpus are produced by a 5-person human-evaluator panel whose consensus matrix is our reference. We propose VISTA, a b

---

### [111] Artificial Intelligence in Equity and Crypto Markets: Progress, Profitability Evidence, and the Limits of Automated Investing

**链接**: https://arxiv.org/abs/2609.04917
**作者**: Linsen Zhu, Mengqing Cai
**来源**: cs.AI q-fin.PM q-fin.TR
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence (AI) now supports investment workflows from data and prediction through research, portfolios, execution, and tool use. Technical capability, however, is not evidence of investment profitability. This critical state-of-the-art review examines public research available through 31 August 2026 on listed equities, exchange-traded funds, centralized crypto spot, perpetual futures, and on-chain markets. We organize evidence with an alpha-translation chain: point-in-time information must yield a stable signal, feasible positions, executable orders, and risk-adjusted returns after costs. Across machine learning, time-series foundation models, financial language models, reinforcement learning, and agents, the examined record shows real but mainly upstream progress in prediction, text processing, portfolio design, and workflow integration. Evidence is thinner for durable net performance. Temporal contamination, repeated selection, survivorship, weak benchmarks, implementat

---

### [112] Amortizing Scaling Law Construction Costs

**链接**: https://arxiv.org/abs/2609.05016
**作者**: Abhash Kumar Jha, Diana Alexandra Onu\c{t}u, Neeratyoy Mallik, Swagatam Haldar, Sam Laing, Niccol\`o Ajroldi 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling laws guide the design choices for training large foundation models, but deriving them involves training an exhaustive grid over hyperparameters, token budgets, and parameter counts, which is computationally expensive. Fitting a scaling law, however, only requires the best-loss frontier across compute scales, discarding most of the trained configurations. We propose a framework for efficient scaling law construction that formulates data collection as a Bayesian optimization problem, and introduce metrics for comparing scaling law fitting methods under constrained compute budgets. We find that progressively expanding the compute budget during acquisition, mirroring the compute-ordered evaluation of configurations in practice, substantially improves recovery efficiency. Augmenting the observed configurations with surrogate-fantasized evaluations then recovers the broader experimental grid, allowing accurate scaling law fitting without training every configuration. Together, these 

---

### [113] ARC-Loc: Leveraging Azimuthal Ray Convergence as a Geometric Cue for Direct Cross-View Localization

**链接**: https://arxiv.org/abs/2609.04965
**作者**: Hyeongsik Kim, Mincheol Kim, Heejoon Moon, Je Hyeong Hong
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-view localization (CVL) estimates the pose of a ground image by matching it to a geo-referenced satellite image. To bridge the extreme viewpoint gap, mainstream pipelines rely on Bird's-Eye-View (BEV) transformations or 2D-to-3D lifting. However, deriving 3D structures from a single ground image is fundamentally ill-posed, causing these methods to endure geometric distortions and computational costs during 3D lifting or BEV projection. Furthermore, relying on external depth foundation models to resolve this introduces latency and remains susceptible to noisy predictions. In this work, we present a different approach inspired by a human navigation technique called resection, that can perform direct ground to satellite image matching and localization without relying on external depth foundation models. The key insights of our method are that (i) ground keypoints can be translated into azimuthal rays on the satellite map, and (ii) these rays ideally converge at the user location. Ex

---

### [114] LetOccVote: Learning Weakly Supervised 3D Occupancy through Consensus

**链接**: https://arxiv.org/abs/2609.04846
**作者**: Chi Zhang, Qi Song, Feifei Li, Jie Li and Rui Huang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weakly supervised 3D occupancy prediction reduces the reliance on costly 3D annotations by learning from 2D pseudo-labels generated by vision foundation models. However, existing methods typically use these imperfect pseudo-labels directly as supervision, making occupancy learning vulnerable to erroneous geometric and semantic targets. We observe that agreement across repeated observations provides an inexpensive and reliable cue for assessing pseudo-label reliability. Based on this observation, we propose \textbf{LetOccVote}, a weakly supervised Gaussian-based occupancy framework that leverages cross-frame voting to improve both geometric and semantic supervision. For geometry, Depth Vote exploits cross-frame geometric agreement to refine supported pseudo depth and reject contradictory estimates before volumetric lifting and depth supervision. For semantics, Semantic Vote aggregates pseudo-semantic observations in a shared 3D space to identify reliable and contested evidence, strength

---

### [115] An Evaluation Framework for Generating Multi-View Images of a Person in a Scene

**链接**: https://arxiv.org/abs/2609.04603
**作者**: Mahir Majid and Young Kyung Kim and Guillermo Sapiro
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent generative image-editing Diffusion Transformers (DiTs) demonstrate impressive semantic editing capabilities but still struggle with spatially consistent camera angle changes. A primary bottleneck in training foundation models to execute free-form, promptable camera angle changes is the lack of specialized training data. While multi-view datasets exist for generic 3D environments and objects, there remains an absence of paired, multi-view datasets featuring human subjects at fixed locations in natural scenes, including frontal and side-profile views. Capturing such multi-camera data in unconstrained environments is logistically challenging and unscalable. In this paper, we first experiment with multiple state-of-the-art image editing models to create this data synthetically, but find that the outputs are frequently prone to hallucinations involving how much the subject's head turns relative to the background, often producing inconsistent environments. To address this issue, we pr

---

### [116] Weather-Conditioned Depth Anything

**链接**: https://arxiv.org/abs/2609.04827
**作者**: Zhaoming Xu, Chan-Wei Hu, Kuan-Ru Huang, Zihao Zhu, Renjie Li, Yang Zhou 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Monocular depth estimation foundation models, such as the Depth Anything series, have achieved remarkable performance across diverse domains. However, they still suffer from critical failures under adverse weather conditions, such as fog, rain, snow, or at night. To address this, we present Weather-Conditioned Depth Anything (DA-W), a framework that explicitly disentangles style from content for weather-robust depth estimation. Specifically, we introduce a Style Filter trained on a curated mix of real and synthetic degradation datasets to extract content-independent, degradation-aware weather embeddings. This style embedding is then injected into the Depth Anything backbone using a parameter-efficient, zero-initialized adapter. Such a lightweight modulation allows a single unified model to robustly adapt to diverse conditions, including fog, rain, snow, and low-light, while avoiding catastrophic forgetting of its core generalization abilities in normal conditions. We train the adapter 

---

### [117] Conserved Immune Topology Improves Pathology Foundation Model Generalization for Cross-Cancer MSI-H Prediction

**链接**: https://arxiv.org/abs/2609.05182
**作者**: Dasari Naga Raju
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models integrated with multiple instance learning achieve competitive accuracy within single-cancer cohorts, yet cross-cancer generalization remains unresolved due to organ-specific histological and architectural differences. In this paper, we propose Conserved Immune Topology (CIT), a lightweight spatial representation for cross-cancer MSI-H prediction that augments foundation-model embeddings with biologically motivated immune descriptors. CIT uses unsupervised clustering to identify immune-associated tiles, then encodes tertiary lymphoid structures, peritumoral immune reactions, multi-scale tumor-infiltrating lymphocyte density, and immune-tumor mixing from frozen foundation-model embeddings and tile coordinates without requiring annotations or target-domain data. The proposed method was evaluated under cross-site and cross-cancer settings using CPTAC-COAD and TCGA-STAD cohorts, which introduce scanner variability, distribution shifts, and organ-specific archite

---
