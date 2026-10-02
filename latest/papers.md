# 📑 论文索引 - 2026-10-03

共 240 篇论文

---

### [1] CBX-Bench: A Human-Aligned MLLM Council for Benchmarking Concept Bottleneck Model Explanations

**链接**: https://scholar.google.com/scholar_url?url=https://ui.adsabs.harvard.edu/abs/2026arXiv260815404M/abstract&hl=zh-CN&sa=X&d=11782157397647809601&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVFsHxmRb9CCpZPN4Iq21XRs&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=3&folt=kw-top
**作者**: Y Meric Karadag, G Oklan, S Baris Cagliyan… - arXiv e-prints, 2026
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> To fill this gap, we develop a multimodal large language model ( MLLM ) council that, given an image and its CBM explanation, produces an explanation quality score. To ground and validate the council, we first conduct a human study to establish a

---

### [2] From fastest to safer and more experience-aware: an LLM -driven framework for personalized multimodal routing

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0965856426004313&hl=zh-CN&sa=X&d=14659999061444661758&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVE-vS7NR0g5yPglurm1FeWr&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=2&folt=kw-top
**作者**: Y Liu, H Chung, Y Song, D Liu, T Chen - Transportation Research Part A: Policy and …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> To address these challenges, this study proposes an end-to-end large language model ( LLM )–enabled … Building on the sampled candidate routes, we developed an LLM -based multi-agent … mitigates performance disparities across different LLM

---

### [3] CARM: Cancellation-Aware Response Masking for LLM Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.02039
**作者**: Yafei Zhang, Songshuo Lu, Sicong Liao, Zhi Chen, Yaohua Tang
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent years have witnessed the rapid adoption of reinforcement learning (RL) in large language model (LLM) post-training, with substantial gains in mathematical reasoning and code generation. In practical systems, however, policy updates and differences between rollout and training engines can make sampled responses off-policy. Sequence-level masking addresses this mismatch by deciding whether an entire response should contribute to optimization. A common masking rule uses the length-normalized geometric mean of sampled token probability ratios. Its signed log-ratios can cancel across positions, concealing substantial bidirectional policy drift. We propose \emph{Cancellation-Aware Response Masking} (CARM), a sequence-level mask that takes the absolute value of each token log-ratio before averaging, preventing opposing probability changes from canceling. We prove that accepted responses satisfy a joint bound on the fraction of sampled-token ratios outside a prescribed band and their me

---

### [4] LG-GER: Language-Guided Group Emotion Recognition via Multimodal Evidence Distillation

**链接**: https://scholar.google.com/scholar_url?url=https://ui.adsabs.harvard.edu/abs/2026arXiv260823880S/abstract&hl=zh-CN&sa=X&d=16808412962405164355&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVF1be4NnFJmHsrdbR-WPbNR&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=9&folt=kw-top
**作者**: A Shehab Khan, Z Li, Y Tong - arXiv e-prints, 2026
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> We propose LG-GER, a language-guided distillation framework that uses a multimodal large language model ( MLLM ) to generate dense, spatially grounded evidence, ie, bounding boxes paired with emotion signals and confidence scores

---

### [5] Sequential Functional Structured Tucker Compression for Large Language Model Attentions

**链接**: https://arxiv.org/abs/2610.00717
**作者**: Jiangfeng Chen, Xinyu Wang, Tianshuo Yan, Hanwei Wu, Xiao-Wen Chang, Yang Zhang 等 (7 人)
**来源**: cs.CL cs.AI stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training compression of LLM attention is often formulated as independent matrix approximation, ignoring both the shared structure among attention projections and the representation shift introduced by earlier compression. We propose FTC, a sequential structured compression framework that adapts the approximation to the current compressed model while jointly exploiting the native Q/K/V head structure under a fixed storage budget. The output projection is handled separately to account for the changed post-attention representation. FTC requires neither fine-tuning nor gradient-based recovery. Across seven decoder-only LLMs from 6B to 32B parameters, FTC achieves the lowest WikiText-2 perplexity among the compared methods at every tested keep ratio on five modern GQA models, with the largest gains under aggressive compression. The improvements transfer to downstream tasks and remain substantial at the 32B scale.

---

### [6] Have an LLM Write Your Anomaly Detector: Autonomous Discovery of Compact, Interpretable Detectors for Time Series

**链接**: https://arxiv.org/abs/2610.01223
**作者**: David Berghaus
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series anomaly detection trades off predictive accuracy, computational efficiency, and interpretability. We use a large language model not as the detector but as the author of one: an autonomous research loop in which the model repeatedly edits a single short NumPy program under a leakage-free objective, keeping the best-scoring detector it finds. The loop discovers two compact detectors, one for univariate and one for multivariate series, that describe short windows by their local spectral features and compare them with the training-region distribution through a covariance-aware distance. On the TSB-AD benchmark these detectors lead the field across metrics, ahead of the strongest classical, deep, and foundation-model baselines including Time-RCD, yet they train no network and use no GPU, and the multivariate detector is faster than every similarly performing baseline. LLM-driven program search is thus a practical route to accurate, efficient, and transparent detectors.

---

### [7] TopK-Guided: Adaptive, Budget-Aware Activation Sparsity for Efficient LLM Inference

**链接**: https://arxiv.org/abs/2610.01763
**作者**: Mukund Agarwalla, Chih-Jen Lin
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Activation sparsity speeds up large language model (LLM) inference by setting unimportant activations to zero so that the corresponding computations can be skipped. Existing training-free methods, however, make different trade-offs: threshold-based methods such as TEAL adapt the sparsity level to each token but do not tightly control the realised sparsity, while TopK-based methods such as WINA enforce a fixed sparsity level but use the same sparsity budget for every token. Both also apply the same budget across transformer blocks, despite large differences in block sensitivity. We introduce TopK-Guided, a training-free method that addresses both limitations by combining bounded token-level sparsity adaptation with sensitivity-aware block-level budget allocation. Across Llama-2 and Llama-3 models, TopK-Guided consistently improves perplexity and downstream accuracy over TEAL and WINA while preserving essentially the same sparsitydependent projection compute as WINA, with the largest gai

---

### [8] OpenMTB-Audit: Exposing Over-Refusal and Clinical Expert Perspectives in LLM-Based Molecular Tumor Board Safety Evaluation

**链接**: https://arxiv.org/abs/2610.01497
**作者**: Negin Ashrafi, Jia Luo, Stacey M. Frumm, Roxana Daneshjou
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Molecular tumor boards integrate genomic findings, clinical context, and therapeutic evidence to support precision oncology. As AI enters this workflow, a key safety challenge is distinguishing truly unsupported recommendations from evidence-supported options that still require oncologist review because of incomplete information, poor ECOG performance status, or other clinical caveats. We introduce OpenMTB-Audit, an open-source benchmark of 500 synthetic non-small cell lung cancer cases spanning five adversarial error categories and four safety labels: Supported, Partially Supported, Unsupported, and Insufficient Information. Across eight large language model configurations, we identify pervasive over-refusal: all LLM configurations failed to retain the Partially Supported label in 83.3-100% of true Partially Supported cases, achieving high aggregate safety scores through label collapse rather than clinically calibrated reasoning. To address this limitation, we developed MTB-AuditAgent

---

### [9] Lingtai: What Concept Geometry Reveals--and Does Not Reveal--About LLM Inference

**链接**: https://arxiv.org/abs/2610.00656
**作者**: Jiangang Chen
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Observing what a large language model computes during autoregressive inference--online and without training probes--remains difficult. We introduce Lingtai, a training-free concept telemetry layer: at each generation step, residual states are projected onto a domain-specific bank of named concept anchors, constructed without labeled concept examples, outcome labels, gradient fitting, or activation-space optimization, producing a structured per-step concept-coordinate signal. Across code generation and grade-school mathematical reasoning, this signal exhibits a robust association with predictive uncertainty: the association survives problem-identity and token-position controls and is not attributable to a single token type, is not explained by a simple correct/incorrect mixture on GSM8K, and is not reproduced by matched random anchors; it is markedly weaker or direction-inconsistent in K-means and PCA projections. Two structures emerge: a recurring uncertainty-linked activity signal who

---

### [10] Learning to Ask: Information Acquisition for SLM-LLM Collaboration, under a budget

**链接**: https://arxiv.org/abs/2610.01236
**作者**: Yongjun Kim, Xiaoxiao Li, Jaeho Lee
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collaboration between a small language model (SLM) and a large language model (LLM) offers an opportunity to combine the efficiency of smaller models with the strong reasoning capabilities of larger ones. Existing approaches primarily frame such collaboration as a computation allocation problem, determining which model should handle each portion of the reasoning process. In black-box API-based settings, however, this paradigm can be inefficient due to coarse-grained delegation or repeated transmission of context across model switches. In this work, we instead formulate SLM-LLM collaboration as an information acquisition problem, under an API budget constraint. The SLM remains the primary reasoner and selectively queries a black-box LLM advisor only when needed, issuing targeted queries rather than delegating the reasoning process itself. To realize this strategy, we develop a three-stage RLVR framework that learns whether to call the advisor, how to formulate useful queries, and how to

---

### [11] XOR-Trellis: Ultra-Low-Complexity Dequantization and Curvature-Aware Hadamard-Free LLM Quantization

**链接**: https://arxiv.org/abs/2610.00432
**作者**: Xiaofan Que, Nir Elkayam, Spandan Pyakurel, Shuokai Pan, Dibakar Gope
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trellis-coded quantization enables high-dimensional compression of large language model (LLM) weights at ultra-low bit widths without the exponentially large codebooks required by conventional vector quantization. Practical deployment, however, presents two challenges: reconstructing compressed weights at sufficient parallel throughput to avoid making dequantization an inference bottleneck, and maintaining quantization accuracy without costly incoherence transformations. We address these challenges with two complementary techniques. First, we introduce an ultra-low-complexity trellis dequantizer that uses a structured, hardware-efficient state-to-value mapping while preserving diverse reconstruction choices for trellis search. Second, we reformulate discrete trellis path optimization with a curvature-aware objective that reflects model sensitivity directly in the original coordinate space. Together, these techniques enable high-quality ultra-low-bit trellis quantization with inexpensiv

---

### [12] When Harnesses Lose the Signal: Causal Evaluation of Recovery in LLM Agents

**链接**: https://arxiv.org/abs/2610.00372
**作者**: Shuyao Xiao, Shengling Wang, Xuan Chen, Ke Chao, Ming Cui, Feifei Qian 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents rely on external harnesses to pass information between the model and its environment and to recover from execution errors. Yet recovery is usually judged only by average task success. This hides an important tension. The same operation can rescue a failing trajectory or disrupt one that would otherwise succeed. We frame recovery as a causal decision problem. Starting from the same execution state, we compare what happens with and without recovery, separate rescue from harm, and study how the value of recovery changes over time. We then introduce the Causal Intervention Router (CIR), a lightweight policy that uses information available before recovery to decide when intervention is worthwhile. On long-horizon ALFWorld tasks with Qwen3-14B, CIR raises success from 70.33% to 73.33%, a gain of 3.00 percentage points. It leaves all evaluated trajectories with correct observations untouched. Additional controls show that the benefit of recovery cannot be explained

---

### [13] Mimir: Physics-Grounded LLM Agents for Long-Horizon Irrigation Control

**链接**: https://arxiv.org/abs/2610.02038
**作者**: Yimeng Liu, Mi Zhang, Younsuk Dong, Zhichao Cao
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly combine reasoning, tool use, and action, but most evidence comes from episodic tasks with relatively immediate feedback and reset failures. Long-running physical control operates in a different regime: actions alter future states, errors compound across decisions, and an agent must improve from experience without being allowed to rewrite the physical rules that make execution safe. We study this regime through irrigation, where daily decisions interact with soil-water dynamics over entire growing seasons. We present Mimir, a physics-grounded LLM agent organized around two repair timescales. At the fast timescale, a structured physical interface and deterministic simulator turn an LLM output into a proposal that we numerically check, revise, and subject to bounded deterministic action selection before execution. At the slow timescale, recurrent failure patterns are consolidated into persistent contextual principles that condition future pro

---

### [14] Auditing Action Settlement in LLM Agent Environments: Order, Progress, and Replay

**链接**: https://arxiv.org/abs/2610.01138
**作者**: Haotian Chen, Bowen Ye, Yuning Zhang, and Jingkun Yu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Concurrent actions in large language model (LLM) agent environments require arbitration even when each proposal is individually valid. We implement a typed snapshot-settlement contract and audit three distinct properties: order sensitivity, useful progress, and replay consistency. Five settlement policies are tested in 28,800 exhaustive permutation trials and 2,160 scripted multistep episodes. Joint policies are spatially order-invariant conditional on fixed priorities, yet conservative rejection completes only 31.25% of agents in a six-agent doorway task versus 90.28% for random tickets; the paired improvement is 59.03 percentage points (95% bootstrap interval: 50.00-68.06). All policies preserve the tested spatial constraints, and priority arbitration still misses the independent small-instance optimum. A separate full-state journal audit exactly replays 156 checkpoints and rejects 1,332 constructed corruptions with a retained terminal anchor. The evidence concerns execution semantic

---

### [15] Spatial Strategies, Not Actions: Vector-Quantized Geodesics as Tools for LLM-Driven Agents

**链接**: https://arxiv.org/abs/2610.00613
**作者**: Gabriel Turinici
**来源**: cs.AI cs.RO cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) based agents are often criticized for lacking spatial understanding and mainly exploiting statistical text patterns. We investigate their spatial comprehension through an architecture combining geometrical tools with a LLM serving as a high-level orchestrator in grid-world environments. The agent first collects geodesic trajectories, which are then vector-quantized to extract a representative subset. Offline, the LLM associates a natural language description of the underlying behavioral patterns to each selected trajectory, making it a tool. Online, the LLM chooses the appropriate tool conditioned on the current state and goal. Low-level control is handled by primitive actions that execute the trajectory associated with the tool. From an agentic AI perspective, this approach separates learning into two levels: tool discovery is handled through unsupervised quantization of trajectories, while reasoning and decision-making are handled by the LLM. We test the ap

---

### [16] Asynchronous LLM Post-Training: Group-Mass Capping and Convergence Analysis

**链接**: https://arxiv.org/abs/2610.01896
**作者**: Qijia He, Ruinan Jin, Jun Luo, Shaofeng Zou, Yingbin Liang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Asynchronous reinforcement learning (RL) improves the efficiency of large language model post-training but introduces stale rollouts generated by earlier policies. Theoretical understanding of how this staleness affects convergence and how to mitigate its impact remains limited. We derive a convergence bound for GRPO-style algorithms that explicitly characterizes the tradeoff between the gradient estimator's second moment and bias. For trajectory-level importance-weighted estimators, our analysis shows that once the second moment is uniformly controlled, delay enters the bound through the bias introduced by clipping or rescaling. Guided by this insight, we propose a novel group mass capping GRPO (GMC-GRPO) method, which minimizes a ratio-based bias bound within a class of weighted estimators sharing a common second-moment guarantee. We establish convergence guarantees for asynchronous GMC-GRPO and show that, compared with TIC-GRPO, it improves the threshold dependence of the fourth-ord

---

### [17] Mem++: Non-Destructive Memory for Long-Term Organizational LLM Agents

**链接**: https://arxiv.org/abs/2610.02002
**作者**: Ahmad Yehia, Aly O. Abdelkareem, Islam Ahmed, Hesham Omran, Khaled Alashmouny, Christian Claudel 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents now take part in organizational work, where many authors record decisions across documents over months. Because a revised decision arrives as a new document rather than an edit, answering a question requires knowing which version held at a given time. However, most memory systems compress the record at write time. By distilling each document into facts, notes or graph edges, these methods fix what can be answered before any question is asked. To address this, we propose Mem++, a non-destructive memory framework shifting from write-time distillation to read-time selection. Mem++ stores every document whole with its date and author, and it calls no generative model at write time. At read time, it retrieves only documents dated up to the time a question asks about and fuses lexical and semantic rankings. Unlike systems that overwrite older versions, Mem++ keeps them and leaves the choice to the answering model. Evaluations on the organizational benchmark 

---

### [18] STEER: Reducing Inference Cost in Relational Foundation Models through Semantically Informed Sampling

**链接**: https://arxiv.org/abs/2610.00907
**作者**: Abdalla Mohamed, Ashraf Aboulnaga
**来源**: cs.DB cs.LG
**匹配关键词**: Foundation Models, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Relational foundation models (RFMs) are pretrained once on a collection of relational databases and prediction tasks, and then applied zero-shot to previously unseen databases and tasks. To make a prediction for a target row, an RFM samples a neighborhood of rows linked to that row through foreign keys and uses this neighborhood as its inference context. Lowering inference cost is an important goal for any foundation model, and for RFMs this cost grows with the size of the context. The simplest ways to shrink the context is to drop some of the sampled rows, but this ignores the semantics of the database schema, so it is as likely to discard informative rows as uninformative ones. We propose STEER, a sampling approach that shrinks the inference context by concentrating it on the tables most relevant to the prediction task at hand. STEER obtains relevance information by prompting a large language model to rank the foreign-key edges of the database schema into relevance tiers for the give

---

### [19] A Multi-Agent LLM Framework for Personalized Health Checkup Interpretation and Guidance

**链接**: https://arxiv.org/abs/2610.01451
**作者**: HyungJun Kim, Taehan Lee, Soojin Cheon
**来源**: cs.AI cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized interpretation of health checkup results requires reasoning across longitudinal records, medical knowledge, lifestyle guidance, and healthcare navigation. We present a multi-agent large language model (LLM) system that identifies multiple intents, maps each to a task-specific agent, executes them in parallel, and synthesizes their outputs. We compared answers generated in Single Agent and Multi Agent settings on 120 Korean compound queries combining two to four requirements, using synthetic health checkup records. The Multi Agent improved the weighted LLM-judge score from 1.695 to 1.797 (p = 0.027), and three additional LLM judges showed consistent improvements ($\Delta$ = +0.111 to +0.186, all p < 0.05). The gains came from usefulness, consistency, and the handling of every requirement in compound queries, whereas numerical accuracy and grounding improved significantly under only one of the four judges and medical safety did not differ, and critical failures occurred at s

---

### [20] PACE: Provenance-Aware Capability Enforcement for Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2610.01349
**作者**: Fengpeng Li, Qizhou Wang, Yuke Hu, Kemou Li, Jun Liu, Haiwei Wu 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using large language model (LLM) agents turn generated text into real side effects, so poisoned tool metadata, retrieved pages, memory, and reusable skills can steer the next call. Vetting an artifact before admission does not settle this. A safe variant and a leaking variant can produce the same admission evidence, and a sound gate then cannot relax that site for either. We make that condition precise, which leaves the last boundary a deployment can still act on. We present Provenance-Aware Capability Enforcement (PACE), which mediates every tool call immediately before it executes. Path confinement proposes an executable cut of represented influence paths, while capability and effect verification checks schema-defined effects against authority compiled from the authenticated request. We distinguish the certified execution contract from the evaluated configuration, which can restore an authorized call after a proposed block or apply a declared repair. Confinement requires the fin

---

### [21] Leto: Fast In-Place Recovery for LLM Training on Surviving Hardware

**链接**: https://arxiv.org/abs/2610.00687
**作者**: Geon-Woo Kim, Joon Ha Kim, Daehyeok Kim
**来源**: cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hardware-operable failures (HOFs) interrupt large language model (LLM) training but permit recovery on the same hardware without reset, repair, or replacement. Existing recovery systems nevertheless reload checkpoints, recompute lost progress, and rebuild process state, idling GPUs that could otherwise continue training. We present Leto, a fault-tolerant training system that leverages surviving hardware to enable efficient in-place recovery. Our key insight is that the state needed to resume training can be retained or prepared outside the active training process while remaining on the same hardware. Leto retains the working model state and the reusable process state, and preinitializes the remaining state in a shadow trainer. We devise two-tier erasure protection and chunk-level transactional updates to keep the retained model state recoverable and consistent, and reclaim the shadow state when active training needs its GPU memory. Evaluation on 6- and 72-GPU NVIDIA A100 clusters shows

---

### [22] RePAIR: Counterfactual local rollback for mixed-edit LLM agent harness optimization

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306457326005753&hl=zh-CN&sa=X&d=14948548357710223821&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVHMqbJSkH6gi_N11AcmAQ4h&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=5&folt=kw-top
**作者**: Y Cheng, X Du, L Yin, Y Zheng, D Wang, Y Fan 等 (8 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Mixed-edit patches in Large language model ( LLM ) agent harness optimization typically produce only an aggregate score, making it difficult to determine which component edits should be retained or rolled back and thereby creating a mismatch

---

### [23] TRIAGE: Dialectical LLM Reasoning for Explainable Risk Prediction on Irregularly Sampled Medical Time Series

**链接**: https://arxiv.org/abs/2606.09030
**作者**: Hyeongwon Jang, Gyouk Chu, Changhun Kim, Hangyul Yoon, Jeonguk Lee, Eunho Yang 等 (7 人)
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] Representation Transitions Reveal Emerging Safety Risks in Multi-Turn LLM Agents

**链接**: https://arxiv.org/abs/2610.00400
**作者**: Haoyu Wang and Wei Zhao and Yedi Zhang and Christopher M. Poskitt and Jun Sun
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn attacks on agentic systems can compose individually permissible actions into harmful outcomes, challenging defenses that assess actions or states in isolation. We show that such attacks leave a detectable signature in the agent's internal representations: harmful behavior emerges as an accumulated representation transition across context updates, whose triggering context can be identified from the same signal. We further find that naive aggregation is confounded by benign representation drift, as a contrastive safety direction need not assign zero to benign transitions. We address this by denoising the direction, anchoring benign traffic at zero and removing its leading variation directions, with no runtime cost. These findings motivate DART, a runtime framework that detects and attributes representation shifts and intervenes with targeted reminders. Across six models and two multi-turn benchmarks, DART reduces attack success from 84% to 25% on MT-AgentRisk, catching every a

---

### [25] Can large language models unlock discrete data in ophthalmic diagnostic reports?

**链接**: https://arxiv.org/abs/2610.00795
**作者**: Umair A. Zaidi, An-Lun Wu, Wei-Chun Lin, Thomas S. Hwang, Michelle R. Hribar
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: To assess the accuracy and efficiency of a large language model (LLM) using two prompt strategies to extract structured data from ophthalmic diagnostic PDF reports. Methods: Twenty deidentified reports across four types (Visual Field, OCT Glaucoma Overview, OCT retinal nerve fiber layer Single Exam, and OCT Thickness Map; n = 5 each) were processed using two GPT-4o-assisted pipelines and compared with a reconciled manual ground truth. Schema-Constrained used Structured Output mode with a predefined JSON Schema; Prompt-Only used a detailed instruction prompt followed by Python conversion to JSON. Outcomes were value accuracy, formatting accuracy, and extraction time. Results: Schema-Constrained value accuracy was 100.00% for Visual Field and RNFL Single Exam, 97.45% for Glaucoma Overview, and 98.00% for Thickness Map; Prompt-Only achieved 100.00% across all four report types. Formatting accuracy was 100.00% for Schema-Constrained across all report types and 100.00% for Prompt

---

### [26] False Floors: LLM Safety Routing Evaluations Break Under Distribution Shift

**链接**: https://arxiv.org/abs/2610.01535
**作者**: Amit Singh Bhatti, Vishal Vaddina
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety routers send each request to one of several models and are judged against the best single model. A major routing benchmark picks that comparator on the evaluation data. In the benchmark's own setting this is harmless, but under distribution shift it is not. On HELM Safety the selection cost is 0.003-0.030 of harm under random splits and 0.045-0.113 under held-out categories, comparable to the whole deficit attributed to routing, with its direction holding under either published judge alone. It rises seven- to ninefold on AgentDojo when suites are held out. Across seven safety corpora chosen by rules fixed in advance, three meet a registered interval test and four beat a later permutation null, and three of the four interval misses are corpora where some models have zero observed harm. Prior work proves the direction of this bias. We size it on harm and accuracy, show that it is larger under the held-out splits we measure, and bound it by optimism plus a shift-dependent regret. S

---

### [27] Federated Agent Optimization

**链接**: https://arxiv.org/abs/2610.01195
**作者**: Qiang Yang, Zhiqiang Kou, Xueyi Zhang, Dong-Dong Wu, Hanlin Gu, Jing Guo 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly operate in private environments and accumulate valuable experience from task execution, tool use, feedback, and local knowledge. Yet such experience is distributed across organizations and cannot be directly shared because of privacy and proprietary constraints. Conventional federated learning is insufficient for this setting, as agent capabilities extend beyond model parameters to memory, tools, rewards, skills, and structured knowledge. In this paper, we formulate \textbf{Federated Agent Optimization (FAO)}, which studies how distributed agents can collaboratively improve through controlled information exchange while keeping raw data, complete trajectories, and private knowledge local. We define FAO as a multi-objective problem balancing agent utility, privacy leakage, and communication cost, and organize its optimization space across policy, memory, tool use, reward, and structured knowledge and skills. We further characterize how priva

---

### [28] From Knowledge Access to Source Learning: Developing Source-Specific Competence

**链接**: https://arxiv.org/abs/2610.02150
**作者**: Lucheng Fu, Kejing Xia, Yiyang Wang, Yiqiao Jin, Jinjin He, Xiyuan Yang 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly rely on persistent external sources to solve sequences of knowledge-intensive tasks. Existing methods improve how source content is accessed and organized, while agent-memory systems preserve reusable knowledge from prior interactions, but repeated use of the same source is still largely treated as repeated access rather than an opportunity to progressively improve understanding of that source. We study source learning: developing reusable source-specific competence over a persistent authoritative source. We represent this competence with a persistent source model that captures reusable understanding of the source, including how its knowledge is structured, interpreted, and applied. To construct and progressively refine such models, we propose SourceLearn, which combines two complementary learning mechanisms. Self-Directed Source Learning identifies what remains incompletely understood and adaptively revisits the source, while Task-Guided 

---

### [29] GPEC: Efficient Pre-LLM Gaussian Process Embedding Correction for Cardiac Video Caption Generation

**链接**: https://arxiv.org/abs/2610.00196
**作者**: Arefeh Rezaei
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) have shown strong potential for video understanding and caption generation, but their performance may decline in specialized medical imaging domains such as echocardiography. This work introduces Gaussian Process Embedding Correction (GPEC), a modular and computationally efficient pre-LLM error-correction method that improves the visual representations used by VideoChat2 for cardiac ultrasound caption generation. GPEC is inserted between the visual projection layer and the language model and learns a residual correction that moves the projected visual representation toward an annotation-guided target. The target is constructed by converting structured video annotations into qualitative attributes, generating a fixed-format reference caption, and mapping it into the language-model embedding space. The correction is modeled using a sparse variational Gaussian Process with inducing points, natural-parameter variational updates, and a block-wise lin

---

### [30] Cross-Context Review: Improving LLM Output Quality by Separating Production and Review Sessions

**链接**: https://arxiv.org/abs/2603.12123
**作者**: Tae-Eun Song
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] System Attribution in LLM Brand Recommendations: Single Responses Identify the System, Aggregated Brand Profiles Do Not Transfer

**链接**: https://arxiv.org/abs/2610.00253
**作者**: Dmitrij \.Zatuchin
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audits of AI visibility summarise the brand recommendations of deployed language models into per-system profiles. We test whether such a profile describes the system on one corpus of 6,475 stored responses (6,324 analysable) collected between December 2025 and February 2026 from five deployed endpoints across gift-recommendation, corporate-reputation and category-ownership queries. The collection harness cut many answers short: 83.1% of Gemini 3 Flash answers in category ownership end mid-sentence under a 1,024-token output cap. With every answer cut to its first 800 characters, a character n-gram classifier cross-validated by prompt attributes one response to GPT-5.2, Gemini 3 Flash, Gemini 3 Flash with search, Grok or Perplexity sonar-pro with 97.84% accuracy (5,028 responses, 383 prompts, majority class 31.5%, 30 split seeds). Length alone falls to the majority rate, 24 formatting statistics reach 95.79%, and masking brand names and capitalised tokens leaves 97.72%. Held-out query c

---

### [32] SHARPO: Segment-Level Credit Assignment for Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.00838
**作者**: Xinchen Du, Zhengze Zhou, Wenhui Zhu, Han Yu, Sen Na, Rohit Jain 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic reinforcement learning (RL) trains a large language model (LLM) to act over long, multi-step interactions. However, a single localized error can cause task failure, while trajectory-level rewards provide limited guidance for assigning credit to individual decisions. To address this limitation, we introduce Segment-level Hindsight Advantage Reweighting for Policy Optimization (SHARPO), a credit-assignment mechanism that refines Group Relative Policy Optimization (GRPO) at the level of environment-facing segments. Inspired by the existing on-policy self-distillation (OPSD) method, SHARPO computes teacher-student log-probability gaps within each segment and uses the resulting signal to compute a bounded multiplier on the GRPO advantage. This multiplier is shared by all tokens within the segment, allowing credit to vary across different segments. With Qwen2.5-7B-Instruct, SHARPO outperforms existing baselines on the ALFWorld and WebShop benchmarks, including GRPO, SDAR, RLSD, and S

---

### [33] LLM-as-a-Judge for Low-Resource Languages: Adapting Ragas and Comparative Ranking for Romanian

**链接**: https://arxiv.org/abs/2610.00406
**作者**: Claudiu Creanga, Liviu P. Dinu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating Retrieval-Augmented Generation (RAG) systems remains a challenge for Low-Resource Languages (LRLs), where standard reference-based metrics fall short. This paper investigates the viability of the "LLM-as-a-Judge" paradigm for Romanian by adapting the Ragas framework using next-generation models (Gemini 2.5 and Gemini 3). We introduce AdminRo-Eval, a curated dataset of Romanian administrative documents annotated by native speakers, to serve as a ground truth for benchmarking automated evaluators. We compare three evaluation methodologies - direct scoring, comparative ranking, and granular decomposition - across metrics for Faithfulness, Answer Relevance, and Context Relevance. Our findings reveal that evaluation strategies must be metric-specific: granular decomposition achieves the highest human alignment for Faithfulness (96% with Gemini 2.5 Pro), while comparative ranking outperforms in Answer Relevance (90%). Furthermore, we demonstrate that while lightweight models strug

---

### [34] Semantic Cooperative Games for Contribution Attribution in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2607.18255
**作者**: Pengyi Jiang, Xiaoguang Zhu, and Quanyan Zhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] Learning to Sell: Reinforcement Learning for Strategic Large Language Model Agents in Multi-Product Markets

**链接**: https://arxiv.org/abs/2609.33289
**作者**: Shuze Daniel Liu, Claire Chen, Jiuqi Wang, David Simchi-Levi, Thorsten Joachims
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] CHILLGuard: Towards Fine-Grained Chinese LLM Safety Guardrail with Scalable Data Construction and Model-aware Preference Alignment

**链接**: https://arxiv.org/abs/2606.15396
**作者**: Wenbo Yu, Bohua Wang, Hao Fang, Kuofeng Gao, Jingru Zeng, Xiaochen Yang 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] Evaluating Biomedical Reranking for LLM-Based Question Answering over Longitudinal Clinical Notes

**链接**: https://arxiv.org/abs/2610.01324
**作者**: Maryam Shahbaz Ali, Laura B. Strachan, Caitlin Sherman, Mark Kovler, Eleanor Mackey, Syed Muhammad Anwar
**来源**: cs.CL cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Patient-specific clinical question answering requires locating the right evidence within long, heterogeneous longitudinal clinical records in which relevant facts may be scattered across encounters, repeated in copied-forward notes, or expressed using different clinical terminology. We evaluated whether biomedical reranking can improve evidence selection and downstream answer quality in a locally deployed retrieval-augmented generation pipeline for longitudinal clinical notes. The pipeline combines PubMedBERT dense retrieval, BM25 lexical retrieval, weighted reciprocal-rank fusion, and MedCPT cross-encoder reranking. Across 1,000 open- and closed-ended question-answer pairs from a cohort of 200 bariatric surgery patients, reranking increased exact source-chunk retrieval within the top 10 items, Hit@10 from 46.6% to 60.6% and mean reciprocal rank from 0.2371 to 0.3252. With Qwen3-8B generation, local judge-assessed answer correctness increased from 44.8% to 48.6%. These results show tha

---

### [38] Every Batch Is Its Own Validation Set: Leave-One-Out Gradient Matching for Online Data Selection in LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.00436
**作者**: Hongyu Chen, Xinyi Luo, Ming Zhao, Lin Tang, Zihan Xu, Jing Li 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online batch selection fine-tunes a language model on the most useful part of each candidate batch. Selectors that match the gradient of the candidate batch are attractive because they need no held-out data, yet they rarely beat training on the whole batch. We show why. In-sample gradient matching uses every example as part of its own target, so its objective credits each example with its own gradient noise. This is the covariance penalty that makes training error optimistic, now sitting on the diagonal of the gradient Gram matrix: it steers selection toward the noisiest examples and makes the full batch the best solution the objective can reach. The fix costs nothing. For each example, the other candidates form an independent sample of the data distribution, so removing the diagonal turns the matching objective into an unbiased estimate of the update's error with respect to the population gradient. The minimizer of this leave-one-out objective weights examples by their gradient signal

---

### [39] LLM-Driven Multi-Agent Control for Skill-Based Smart Manufacturing

**链接**: https://arxiv.org/abs/2610.01364
**作者**: Kay K\"ohle, Darko Anicic, Thomas A. Runkler, Ren\'e Graf
**来源**: cs.MA cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Factories are shifting toward smaller lot sizes with high product customization, requiring frequent re-programming of flexible and reconfigurable automation systems. LLM-based agents can be deployed in two complementary roles: Offline, they generate deterministic production sequences, reducing programming effort; online, they operate live machines and handle unforeseen runtime faults that static programs cannot anticipate. We propose a solution in which each factory module is paired with a dedicated LLM-based agent and an MCP tool server that exposes the module's skills via OPC UA method calls, with agents coordinating over MQTT and grounded by real-time updates of the factory state. We compare three agent architectures (orchestrator, peer-to-peer, and monolithic) across nine production challenges of increasing complexity in a simulation of a physical six-module hexagonal factory, including silent hardware fault detection. The monolithic and peer-to-peer architectures both achieve the 

---

### [40] LabBook: Harnessing Experimental History for Efficient LLM-Driven Discovery

**链接**: https://arxiv.org/abs/2610.00675
**作者**: Bo Yuan, Wenqian Ye, Zelin Zhao, Lama Moukheiber, Henry Kautz, Aidong Zhang 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evolutionary approaches to LLM-driven discovery often generate new programs from a small set of selected ancestors. This keeps contexts manageable but can omit useful evidence from other experiments, whereas including the full experimental history produces long, redundant contexts. We introduce a simple, single-agent discovery harness built around LabBook, an agent-maintained memory that serves two complementary roles: guiding retrieval of relevant evidence from a complete experimental log and informing the generation of new solutions. At each iteration, the same agent combines its memory with retrieved evidence and jointly produces the next program and an updated LabBook. This separates complete history retention from selective context construction, without requiring an explicit population or branching search structure. On 49 Frontier-CS problems, LabBook improves the observed quality-cost trade-off over the evaluated evolutionary baselines with two backbones, while remaining competit

---

### [41] When Fancy Eviction Fails: Rethinking Cache Replacement For LLM Prefix Reuse

**链接**: https://arxiv.org/abs/2609.28870
**作者**: Yiyu Liu, Minlan Yu, Juncheng Yang
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] OrbitTAMP: Grounding Language Models for Task and Motion Planning in Spacecraft Rendezvous

**链接**: https://arxiv.org/abs/2610.01093
**作者**: Yuji Takubo, Daniele Gammelli, Marco Pavone, Simone D'Amico
**来源**: cs.RO cs.AI math.OC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spacecraft rendezvous and proximity operations (RPO) are currently planned through an expertise-intensive process in which engineers translate high-level operational intent into safe, dynamically feasible trajectories, creating a bottleneck to scalable operations. Large language model (LLM)-based agents could offer an intuitive interface for this process, although their outputs are not inherently grounded in orbital dynamics, operational constraints, or the structure of admissible spacecraft maneuvers. To exploit their semantic reasoning while ensuring the generated plan's physical validity, this paper presents a hierarchical framework for spacecraft task-and-motion planning (TAMP) that grounds LLM reasoning in a graph of reusable behaviors and domain-specific planning modules. Within this framework, a pretrained LLM maps a natural-language command to a partial mission specification. The associated planners then resolve unspecified decisions within the admissible operational space. Fin

---

### [43] Pinned and Still Unstable: Within-Judge Verdict Variance and the Noise Floor of LLM-as-Judge Leaderboards

**链接**: https://arxiv.org/abs/2609.33044
**作者**: Krishna Chytanya Ayyagari
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Technical Limitations of LLM -Based AI Agents and Their Links to Bias and Governance Challenges: A Narrative Review

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2673-2688/7/10/391&hl=zh-CN&sa=X&d=12665612476866128714&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVHG_dGmaAOHeIQTv3tx6T-u&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=1&folt=kw-top
**作者**: S Lee, J Woo, S Choi - AI, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The purpose of the review was to synthesize research on the technical characteristics and limitations of LLM -based AI agents and to examine how … This section examines the basic architecture of LLM -based AI agents and perspectives

---

### [45] Evaluating LLM-Generated Preference Distributions

**链接**: https://arxiv.org/abs/2610.01000
**作者**: Fan Huang, Minsuk Kim, C. Tyler Diggans, Filippo Radicchi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used as probabilistic generators for simulation, synthetic data generation, and decision support in settings where real-world data are unavailable. Yet, the structure and reliability of the distributions they produce remain understudied. Here, we systematically analyze LLM-generated distributions of preferences for air travel, restaurants, and consumer products. Encouragingly, all models considered in our analysis exhibit self-coherence, with the most probable outcomes stabilizing rapidly under repeated sampling. At the same time, we observe substantial discordance across both model families and scales, with little consensus even among their most probable outcomes. These patterns hold across nine open-weight models, three choice domains, and show robustness under temperature changes, greedy decoding, and perturbations of prompt and ordering. Our findings indicate that outcomes are influenced more by the choice of model than by the wording o

---

### [46] Chaining Skills to Hijack LLM Agents

**链接**: https://arxiv.org/abs/2610.01564
**作者**: Tian Dong, Zixuan Ma, Haodong Zhao, Huaien Zhang, Shaofeng Li, Hao Chen
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents use skills to improve performance on specialized tasks. To complete a user request, an agent may invoke several skills in sequence, allowing information produced under one skill to guide the next. Because skills may come from open-source repositories, this handoff can also carry attacker-controlled claims into later decisions. In this paper, we introduce APEX, which constructs and refines adversarial skill chains tailored to a user task and an attacker-selected action. The key insight is that an agent-written record of genuine task progress can carry a false claim of user approval across skills: an upstream skill induces the agent to create the record, and a downstream skill uses it to direct the attacker-selected action. Across four targeted-action families and six models on SkillsBench, the chains induce the selected action in 512 of 690 attempts (74.2%). On GPT-5.4, the full chain succeeds in 84.3% of attempts, compared with 17.4% when the workflow is merged into one skil

---

### [47] WaLLM -- Understanding Use and Engagement with a General-Purpose LLM on WhatsApp

**链接**: https://arxiv.org/abs/2505.08894
**作者**: Hiba Eltigani, Rukhshan Haroon, Asli Kocak, Abdullah Bin Faisal, Noah Martin, Fahad Dogar
**来源**: cs.HC cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] LineupRL: Verifiable Reinforcement Learning for Time Series Captioning via Caption-to-Series Identification

**链接**: https://arxiv.org/abs/2610.01800
**作者**: Haochen Zhang, Laura Yao, Zachary Plotkin, Gengwei Zhang, Tianlong Chen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series captioning is a fundamental step in time series understanding and can also serve as the bridge between signal and natural language. Supervised fine-tuning (SFT) relies on a larger model's captions and cannot exceed their quality. Reinforcement learning (RL) can, but its rewards were designed for other modalities and other tasks, and they transfer poorly to open-ended generation in the time series domain. We address this by proposing LineupRL, a reinforcement learning with verifiable rewards (RLVR) pipeline whose reward is caption-to-series identification. The reward model is a frozen large language model (LLM) verifier that reads the generated caption and the candidate time series as raw values, never the chart, and must pick the described time series from multiple distractors. Matching is a far lighter demand on the verifier than writing questions or judging a caption, so an off-the-shelf LLM can supply the reward. Across two captioning benchmarks, and on forecasting and r

---

### [49] RPTune: Learned Context Curation for LLM Catalog Search

**链接**: https://arxiv.org/abs/2610.00964
**作者**: Chuxuan Hu, Hejie Cui, Norman Huang, Shubham Kumar Bharti, Wang-Chiew Tan, Sercan \"O. Ar{\i}k
**来源**: cs.IR cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For small merchant businesses (SMBs) whose catalogs fit within a long-context LLM, full-catalog prompting offers a compelling alternative to multi-stage retrieval designed primarily for large marketplaces with millions of items. However, fitting the full catalog into the context window does not ensure that the model can use it effectively, since LLMs do not exploit long contexts uniformly. We therefore study in-context catalog search through two complementary questions: (1) how to curate and present catalogs to the LLM, and (2) how to adapt the LLM for product selection on curated contexts. We propose RPTune, an end-to-end framework that couples learned catalog curation with LLM post-training using automatically generated, catalog-grounded supervision. An encoder-reorganizer curator orders and prunes products guided by downstream LLM feedback, while the resulting curated catalogs in turn improve the effectiveness of LLM post-training with a context-relative reward. We evaluate RPTune o

---

### [50] Detecting Inconsistencies in Model Specifications with LLM-as-Verifier Reasoning

**链接**: https://arxiv.org/abs/2610.01847
**作者**: Zichen Xie, Mrigank Pawagi, Lize Shao, Yang Hu, Wenxi Wang
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model specifications define how large language models (LLMs) should behave, guiding alignment training, inference-time behavior, and evaluation. Yet these specifications may themselves contain defects: two individually reasonable principles may prescribe incompatible behavior when applied to the same situation, leaving no response that satisfies both. Detecting such inconsistencies is challenging. Formalizing natural-language specifications risks losing subtle distinctions, while behavior-based testing cannot reliably distinguish specification defects from differences in model behavior. We introduce VeriSpec, the first approach to directly detect inconsistencies in model specifications by auditing the specification text itself. Our key insight is to preserve the specification in natural language while using an LLM as a verifier. VeriSpec extracts structured, context-aware rules, constructs a topic-guided graph to cluster behaviorally related rules at the same authority level, and appli

---

### [51] SPHERE: Adaptive VR Indoor Scene Generation via LLM-Enhanced Spatial Preference Learning and Human-in-the-Loop RL

**链接**: https://arxiv.org/abs/2610.02023
**作者**: Hyeonmin Lee, Zheng Wei, Kyungmin Kwon, Jumin Seo, Jiwon Park, Hayoung Oh
**来源**: cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models (LLMs) advance 3D indoor scene synthesis, current pipelines fail to retain user-specific preferences across sessions, making immersive authoring a repetitive and physically fatiguing process. We present SPHERE, an adaptive VR generation framework that transforms isolated synthesis into continuous human-AI co-creation. SPHERE extracts persistent spatial preferences from natural multimodal interactions (speech and controller edits). To ensure geometric resilience against spatial distortions, it abstracts these raw edits into hierarchical constraints modeling both local functional and global topological contexts. Furthermore, a human-in-the-loop reinforcement learning mechanism dynamically updates retrieval policies based on the user's final edited scenes. A mixed-design user study ($N=42$) and an offline ablation demonstrate that SPHERE significantly reduces corrective edits and physical demand, preventing bias toward shallow object-level traits to yield geome

---

### [52] When the AI Leaves the Tailorshop: Measuring What an LLM Advisor Leaves Behind in Complex Problem Solving

**链接**: https://arxiv.org/abs/2610.00163
**作者**: Robin Welsch
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Complex problem solving depends on acting effectively and understanding how a system works. AI advice may support these outcomes unequally. Two preregistered experiments compared participants managing a simulated clothing factory with and without an LLM advisor. Across studies, AI-supported participants reported greater confidence and understanding with less effort. In the first study (N=200), assistance increased company value but produced no detectable prediction-accuracy difference. After withdrawal, previously supported participants outperformed controls when decisions were scored against repeating previous choices, but not default settings. Within the AI-supported group, more frequent recommendation alterations predicted better unaided performance. In the second study (N=198), AI-supported participants went bankrupt less often and showed a small knowledge advantage in the registered analysis, largely associated with remaining solvent. More frequent recommendation alterations predi

---

### [53] An Educator-Guided LLM Pedagogical Agent for Scaffolded Feedback in Conceptual Database Design

**链接**: https://arxiv.org/abs/2610.00870
**作者**: Sara Riazi and Pedram Rooshenas
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present an educator-guided LLM pedagogical agent for scaffolded feedback in conceptual database design. Integrated into an entity--relationship diagram (ERD) editor, the system grounds feedback in the student artifact, assignment requirements, educator-authored rubrics, and instructional resources. Its architecture separates hidden, artifact-grounded diagnosis from the workflow that controls the form and disclosure level of student-facing support. We instantiate the architecture as a four-stage workflow progressing from concept checks and guided application to low-detail feedback and localized clarification. Each feedback request creates a stateful episode linked to versioned ERD states. In a deployment spanning three ERD environments and 383 feedback episodes, 71.1\% of observed target-level changes fully or partially incorporated the hidden diagnostic target, including many after Stages~1--2. Qualitative analysis showed that staged disclosure sometimes withheld inaccurate details,

---

### [54] A Proposed Rubric for Evaluating Expressed Clinical Reasoning in Large Language Model Responses

**链接**: https://arxiv.org/abs/2609.37788
**作者**: Zhangshu Joshua Jiang, Zina Ibrahim, James T. Teo
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] Measuring Human-Like Bias in LLMs? A Critique of Human-Derived Bias Constructs in LLM Evaluation

**链接**: https://arxiv.org/abs/2610.00070
**作者**: Antonela Tommasel, Markus Schedl
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Researchers increasingly use human-derived bias constructs to study Large Language Models (LLMs), including social-cognitive constructs such as implicit bias and stereotype activation, and cognitive biases such as anchoring, framing effects, and confirmation bias. Such approaches offer alternatives to overt bias probes, particularly when direct questioning may obscure bias or when model behaviour appears normatively acceptable. However, adapting human bias constructs to LLMs introduces an inferential gap. Psychological instruments were developed to study human cognition and social behaviour, whereas LLM evaluations rely on probabilities, text completions, rankings, or simulated decisions. This paper critiques human-centered bias evaluation in LLMs. We show how this gap arises from mismatches pertaining to human-derived constructs, human-model differences, and evaluation contexts, which can blur distinct interpretations of model bias. We then introduce a framework providing an analytica

---

### [56] WIP: DBWorkout: A Gamified SQL Practice Platform to Support Formative Learning in Database Courses

**链接**: https://arxiv.org/abs/2610.01174
**作者**: Sehrish Basir Nizamani, Deepika Devaraj, Tien Nguyen, Khyati Goyal, Saad Nizamani, Sally Hamouda 等 (7 人)
**来源**: cs.CY cs.DB cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This research WIP paper presents DBWorkout, a web-based platform that supports formative SQL learning through sandbox-based execution, automated result-based feedback, and session-based gamification. Learning Structured Query Language (SQL) remains challenging for undergraduate students due to limited opportunities for interactive practice and immediate feedback. Students iteratively practice SQL on live database instances while receiving multi-dimensional feedback on query correctness, including row values, column structure, and ordering. To reduce instructor workload, DBWorkout incorporates large language model (LLM)-assisted tools for schema and task generation within a human-in-the-loop workflow. A pilot study with teaching assistants and a classroom deployment involving 170 undergraduate students across two in-class sessions show strong perceived learning value (90% agreement) and engagement (87% enjoyment), alongside low reported pressure (22%). However, only 42% of students foun

---

### [57] LLM-Assisted Discovery of Typed Semantic Links for Ontology Network Construction

**链接**: https://arxiv.org/abs/2610.01393
**作者**: Nouha Hayouni, Sheeba Samuel, Alsayed Algergawy
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Constructing typed, justified semantic links between ontologies is essential for enabling interoperability across heterogeneous and interdisciplinary knowledge domains. However, manually curating such links is difficult to scale. To address this challenge, we propose an end-to-end framework for ontology network construction that automates the discovery and generation of both intra-domain and inter-domain relationships. Our approach combines domain-adapted DistilBERT embeddings for dense contextual representation, clustering-based pre-filtering to reduce the candidate search space, and GPT-4o-driven relationship generation via iterative prompt engineering to produce semantically rich, interpretable links. Applied to ReproduceMeON - a network of 33 ontologies spanning machine learning, microscopy, computational science, and experimental workflow - the pipeline reduces approximately 800k raw concept pairs to 95k high-quality candidates. Human expert validation of 429 generated relationshi

---

### [58] Ontology-Grounded, Reasoner-Verified Benchmarks for Evaluating LLM Reasoning in Scientific AI

**链接**: https://arxiv.org/abs/2610.00682
**作者**: Nishtha N. Vaidya, Stephan Grimm, Thomas Hubauer, Thomas A. Runkler
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly underpin scientific AI applications that reason over structured knowledge, from biomedical question answering to materials informatics. However, their logical reasoning often falls short, producing factual inaccuracies unacceptable in these settings. Reliable evaluation remains challenging: manual dataset construction scales poorly, and LLM-based generation risks embedding the very flaws it aims to measure. High-quality benchmarks must ground both correct and incorrect labelled examples in explicit background knowledge, formally verifiable by a standard reasoner. We propose a pipeline that automatically generates ontology-grounded multiple-choice question (MCQ) benchmarks from any sufficiently axiomatised OWL 2 ontology, with correct answers grounded in the ontology by design. Distractors are generated by perturbing the right-hand-side class expressions of class definition axioms, and their incorrectness is formally verified by an OWL reasoner 

---

### [59] SemDistill: Bootstrapping a Low-Latency, Low-Cost Semantic Table Annotator from Noisy LLM

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3837124&hl=zh-CN&sa=X&d=15238057077121287228&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVHI4SPhvoF6h4_rnSSFC-hl&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=9&folt=kw-top
**作者**: Y Ge, Z Ye, Y Mao, Y Gao - Proceedings of the ACM on Management of Data, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address these, we propose SemDistill, a framework that bootstraps high-performance local annotators from noisy LLM outputs using only … of LLM errors in tabular domains. We conducted an empirical analysis on real-world datasets (eg, VizNet [13])

---

### [60] FastCI: Efficient GPU-Intensive CI for LLM Training Frameworks

**链接**: https://arxiv.org/abs/2610.01967
**作者**: Tianshuo Qiao, Naiqian Zheng, Xiaopeng Liu, Shuguang Wang, Diandian Gu, Xuanzhe Liu 等 (7 人)
**来源**: cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) keep growing in size and complexity, their training frameworks evolve at a rapid pace as well. Therefore, continuous integration (CI) is critical for maintaining the quality and stability of these frameworks. However, unlike traditional software, CI for LLM training frameworks relies on GPU-intensive tests, which usually involve complete model training or evaluation. This leads CI itself to become a new bottleneck for fast-paced development. In this paper, we introduce FastCI, a framework that improves the efficiency of CI for LLM training frameworks. FastCI leverages runtime evidence to select affected tests and prune tests that execute changed code in equivalent contexts. Then FastCI prioritizes high-risk tests to expose potential failures earlier, and optimizes test workloads along dimensions outside the intended validation scope of each test. Evaluated on the CI workload of our LLM training framework, FastCI reduces the CI latency by 77.5% and the GP

---

### [61] What Does a Sharing Question Add? Auditing LLM Survey Scores for Misinformation

**链接**: https://arxiv.org/abs/2604.06820
**作者**: Zonghuan Xu, Xiang Zheng, Yutao Wu, and Xingjun Ma
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Quantifying Diversity of Thought: A Predictive Law of Weighted LLM Ensemble Lift

**链接**: https://arxiv.org/abs/2607.17384
**作者**: Junade Ali
**来源**: cs.AI cs.LG cs.LO cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] Engineering verification-guided LLM framework for feasibility-aware spec configuration

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1474034626009912&hl=zh-CN&sa=X&d=7220761120074695041&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVESq8zi7o7nFqF8QbjBe1hf&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=8&folt=kw-top
**作者**: S Park - Advanced Engineering Informatics, 2027
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> structured, constraint-specific corrective feedback; and (3) an LLM layer that produces and iteratively refines engineering specifications. A … LLM , retrieval-augmented generation (RAG), and Chain-of-Thought (CoT) prompting. Repeated experiments

---

### [64] Initialization Improves LLM-Driven Discovery

**链接**: https://arxiv.org/abs/2610.00707
**作者**: Mansi Sakarvadia, Marco Ciccone, Colin Raffel
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have been used for novel discovery of algorithms, theorems, drugs, and other tasks through the use of harnesses that prompt an LLM to iteratively optimize an objective. In this work, we study the relationship between the population of previous iterates and eventual discovery success. We generalize past work on harness design to develop a suite of 12 harnesses called 'Modular' and characterize their performance across 5 diverse discovery tasks, finding that discovery success is brittle and sensitive to harness design. We uncover mode collapse, characterized by a dramatic drop in the diversity of iterates, as a common failure mode. We find that popular state-of-the-art harnesses and diversity-inducing harness interventions, which aim to prolong this collapse, yield inconsistent gains. Our results instead uncover that the performance of early discoveries is predictive of eventual success. We therefore propose a universally applicable intervention that performs

---

### [65] SyzHarness: Patch-Based Kernel Bug Reproduction with LLM-Synthesized Fuzzing Harnesses

**链接**: https://arxiv.org/abs/2609.23889
**作者**: Xingyu Li, Juefei Pu, Haonan Li, Arrdya Srivastav, Kareem Shehada, Srikanth V. Krishnamurthy 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] From Images to Tasks: Characterizing Multimodal LLM Interactions in the Wild

**链接**: https://arxiv.org/abs/2610.00701
**作者**: Jinyi Ye, Scott Counts, Gaurav Verma, Kate Lytvynets, Weiwei Yang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (LLMs) increasingly integrate vision and text, yet how people use them in natural settings remains underexplored. We seek to answer the question: when users upload images, what tasks are they trying to accomplish? Analyzing over 40,000 de-identified image-upload conversations from Microsoft Copilot, we characterize real-world multimodal use through a hierarchical framework of ten capabilities, spanning perception, cognition, and generation. First, we characterize the distribution and composition of these capabilities, finding that the majority of image-upload tasks involve multiple capabilities. Second, we find that multimodal use spans a broader and more diverse task space than text-only interactions, with asymmetric coverage and task classes that rely on cross-modal grounding. Third, mapping observed capability demand onto 253 existing benchmarks reveals uneven alignment between benchmark coverage and real-world use: benchmarks concentrate on percepti

---

### [67] A Comprehensive Evaluation Framework for Conversational Home Energy Management Systems

**链接**: https://arxiv.org/abs/2610.00073
**作者**: Wooyoung Jung
**来源**: cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing complexity in home energy management (HEM) demands advanced systems that guide occupants toward informed energy decisions reflecting their background, preferences, and context. Large language model (LLM)-integrated HEM systems (HEMS) have demonstrated promise, but previous studies relied on single-turn or single-task evaluations with response accuracy as the primary metric. Whether such systems deliver effective interactions across the extended multi-turn dialogues typical of real-world use remains an open question. This study introduces a comprehensive evaluation framework of LLM-integrated HEMS derived from the Goal-Question-Metric methodology, organized across five categories: task performance, factual accuracy, interaction quality, control capability, and system efficiency. A total of 23 metrics across multi-turn conversations are proposed and an LLM-as-judge pipeline is employed to enable scalable automated scoring. Its reliability is validated against three trained hu

---

### [68] Multi-LLM Ensemble Framework for Quality Assurance in AI-Generated Content

**链接**: https://scholar.google.com/scholar_url?url=https://run.unl.pt/entities/publication/c7a805c1-6809-4f50-b76e-a8eecbf81709&hl=zh-CN&sa=X&d=17587953549518054044&ei=eES_arW5Ecyp6rQPheW1-Aw&scisig=ACTRDVGapydtPbfYWGY6RQRAartt&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=2&folt=kw-top
**作者**: C Bernardino, M Aparicio, P Gonçalves
**来源**: 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The rapid adoption of Large Language Models (LLMs) in digitized systems and services creates … AEF performs multi - model cross-validation by querying independent LLMs in parallel for … The multi - model ensemble demonstrates strong

---

### [69] Rules to Tools: Executable Checks for LLM Agents in Scientific Computing

**链接**: https://arxiv.org/abs/2610.00313
**作者**: Jingjie Ning, Guojiang Zhao, Chen Xu, Shanshan Zhong, Xiaochuan Li, Ji Zeng 等 (7 人)
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific coding agents receive equations, boundary conditions, and output requirements in writing, then must assess the programs they revise. Rules to Tools (R2T) supplies prepared executable checks of public scientific requirements. Matched SciCode repair groups share written checks, starting programs, model, and budgets; the tool group receives a callable implementation. Across two task-ID cohorts, complete repair is 26/30 with text and 29/30 with the prepared checks. Three task IDs favor tools, one favors text, and eleven tie. The eight-ID cohort scores 13/16 versus 15/16, with a task-cluster bootstrap 95% interval of [-12.5, 43.75] percentage points for the difference. The larger shared-definition SciCode cohort ties at 13/24 per group. Five development-exposed tasks with alternate starting programs score 3/10 versus 7/10. The tool group favors tasks 17, 77, and 11; initial checks flag task 17 and report no violation for tasks 77 and 11. Task 37 favors text and has no initial rep

---

### [70] Psychological Reactions to Subordinates' LLM Use at Work

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1048984326000639&hl=zh-CN&sa=X&d=7944930087072599508&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVGIYju7xLCTe4jUIA7V4FEx&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=0&folt=kw-top
**作者**: S Meyers, R Briker, YE Bigman - The Leadership Quarterly, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> ), we investigated how subordinate LLM use affects supervisory trust. First, we found that subordinates’ use of LLM -generated output leads to less … LLM policy (Study 2), task criticality (Study 3), and supervisors’ prior LLM experience (Studies 1-4 and 6)

---

### [71] OverAct: Measuring and Mitigating Proactive Over-Authorization in LLM Tool-Calling Agents

**链接**: https://arxiv.org/abs/2610.01508
**作者**: Taolin Zhang, Jiuheng Wan, Hanyu Wang, Tingyuan Hu, Chengyu Wang
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents with tool-calling capabilities can access external services and private user data, but they may retrieve more information than a user's request explicitly requires. We study this behavior in structured tool-calling agents and term it proactive over-authorization. This setting differs from filesystem-level coding agents because the main risk is unnecessary access to private data. We introduce OverAct, a controlled benchmark spanning eight privacy-sensitive domains with deterministic, judge-free scoring, together with an interpretive decision-theoretic framework that yields three testable predictions. Across seven models from four families, all models significantly exceed authorized scope. Request specificity is the strongest predictor of severity, over-authorization grows sublinearly with tool-pool size, and decoding temperature has little effect. These patterns are consistent with a cost-asymmetry account, suggesting that over-authorization arises more from structural decisi

---

### [72] LLM-based Agentic Reasoning Frameworks: A Survey from Methods to Scenarios

**链接**: https://arxiv.org/abs/2508.17692
**作者**: Bingxi Zhao, Lin Geng Foo, Ping Hu, Christian Theobalt, Hossein Rahmani, Jun Liu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Yo-ByT5: Efficient and High-Fidelity Diacritic Restoration for Yor\`ub\'a

**链接**: https://arxiv.org/abs/2610.01634
**作者**: Ahmad Samuel Gali (1), Shamsuddeen Hassan Muhammad (2 and 3) ((1) University of Lagos, (2) Bayero University Kano, (3) Imperial College London)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Yor\`ub\'a is a widely spoken tonal language that depends on diacritics to avoid lexical ambiguity. However, it is often written without these diacritics, thereby hindering downstream Natural Language Processing (NLP) tasks. In this paper, we introduce Yo-ByT5, a byte-level Automatic Diacritic Restoration (ADR) model fine-tuned from ByT5-small. We evaluate Yo-ByT5 alongside five publicly released Yor\`ub\'a ADR models and one open-weight large language model (LLM) on the YAD benchmark under a consistent protocol. Our results demonstrate that Yo-ByT5 matches the performance of the strongest existing model, mT5-base, with a DER of 10.14% and a CER of 3.48%. Furthermore, it exhibits superior text fidelity despite using approximately half the parameter count of mT5-base. We also release our training code and model outputs, as well as call for the development of a larger, purpose-built benchmark for Yor\`ub\'a diacritic restoration.

---

### [74] VERITYGATE: A Four-Gate Schema-Level Faithfulness Framework and Paired Benchmark for Grounded LLM Narrations over Structured Evidence

**链接**: https://arxiv.org/abs/2610.00833
**作者**: Sachin Gupta
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fluent LLM explanations may not follow the evidence from a structured system. We present VERITYGATE, a four-gate checker for declared evidence IDs, entities, numbers, and claim types. It checks a fixed schema; it does not verify every fact in the prose. At r=0 and r=1, we test 900 instances per setting (450 grounded-ungrounded pairs) with GPT-4o-mini, Llama-3.3-70B, and Claude Sonnet 4.6. Under this schema-level contract and before repair, 80.3% of mini claims and 47.9% of Sonnet claims fail. These are verifier rejection rates, not prose-hallucination rates. One repair pass raises claim survival from 19.7% to 28.0% for mini and from 52.1% to 54.3% for Sonnet. Verified claims per example change by +0.14 for mini, -0.71 for Llama, and -0.47 for Sonnet, so survival and output volume must be reported together. A second Sonnet pass gives no clear gain. At r=1, Gate 4 covers 97.0%, 98.7%, and 100% of failing claims for mini, Llama, and Sonnet. Small human studies support the rules but show g

---

### [75] Memetic Trojans: Social Contagions as Carriers of Adversarial Payloads in Agent Networks

**链接**: https://arxiv.org/abs/2610.00430
**作者**: Birk Torpmann-Hagen, Finn Schwall, Leon Moonen
**来源**: cs.SI cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous large language model (LLM) agents increasingly interact in network environments where adversarial content can propagate between agents. Known attacks include agent worms, which spread through self-replicating prompt injections or configuration compromises. We introduce \emph{memetic trojans}, a distinct class of network-mediated attack that exploits agents' tendencies to retransmit and amplify content. Unlike agent worms, whose propagation is adversarially induced, memetic trojans exploit \emph{endogenous} transmission by embedding adversarial payloads in \emph{social contagions}: content agents have internal reasons to share. As part of our work, we extract social contagions from Moltbook, a social media platform for LLM agents. Controlled transmission experiments reveal large differences in virality: the most effective contagion is retransmitted in approximately 50\% of subsequent agent posts and upvoted at 2.5x the average post's rate. Its memetic trojan counterpart large

---

### [76] HakiCC: LLM-Driven Multi-Agent Design and Optimization of Concurrency Control Protocols

**链接**: https://arxiv.org/abs/2610.00889
**作者**: Farzad Habibi, Juncheng Fang, Faisal Nawab
**来源**: cs.DB cs.DC cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have recently been applied in systems research as a tool to reduce human-intensive engineering effort through cost-efficient automation. Decades of research have produced a rich landscape of concurrency control (CC) protocols, each encoding distinct trade-offs in correctness, throughput, and abort behavior. However, most applications in practice default to 2PL or OCC, because selecting and adapting a protocol to a specific application requires expert knowledge that is rarely available to application designers. This is a wasted opportunity, as an application-specific CC protocol can yield significant performance advantages over a generic baseline, but designing one requires deep expertise in CC protocol design. In this paper, we propose HakiCC, an LLM-driven multi-agent pipeline that automatically designs, verifies, and optimizes concurrency control protocols tailored to a given target application. HakiCC provides a two-stage pipeline. In Stage 1, a multi-ag

---

### [77] Mitigating LLM Over-Refusal via Dynamic Semantic Routing Calibration

**链接**: https://arxiv.org/abs/2609.25049
**作者**: Zixuan Wang, Bingjie Zhang, He Zhao and Dandan Guo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Closing the Speech-Text Gap with Limited Audio for Effective Domain Adaptation in LLM-Based ASR

**链接**: https://arxiv.org/abs/2604.06487
**作者**: Thibault Ba\~neras-Roux, Sergio Burdisso, Esa\'u Villatoro-Tello, Dairazalia S\'anchez-Cort\'es, Shiran Liu, Severin Baroudi 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] Multi-Perspective LLM Annotations for Valid Analyses in Subjective Tasks

**链接**: https://arxiv.org/abs/2603.21404
**作者**: Navya Mehrotra, Adam Visokay and Kristina Gligori\'c
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [80] OmniSeek: Native Tool Integration for Multi-turn Audio-Visual Reasoning

**链接**: https://arxiv.org/abs/2610.02181
**作者**: Haibo Wang, Jiteng Mu, Jialu Li, Jingru Yi, Yuanjun Xiong, Jianming Zhang 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present OmniSeek, an agentic framework that transforms an Omni Large Language Model (Omni-LLM) into an active, multi-turn reasoning agent with native tool use. Rather than passively processing an entire audio-visual sequence in a single forward pass, OmniSeek makes evidence acquisition part of the reasoning process: it dynamically decides whether to look or listen, and over which temporal window, to retrieve sparse but critical evidence across different modalities within long contexts. Through an iterative multi-turn protocol, the retrieved raw audio or visual segments are appended back into the context to support subsequent reasoning. To cold-start this capability, we build a data engine that synthesizes OmniTraj-170K, a corpus of multi-hop Chain-of-Thought trajectories with interleaved audio and visual evidence. We first supervise the model on these trajectories to instill multi-turn tool-use behavior, and then further optimize the policy via a two-stage reinforcement learning wit

---

### [81] Not Too Hard, Not Too Easy: Learning from Intermediate States for LLM Structured Reasoning

**链接**: https://arxiv.org/abs/2609.33149
**作者**: Hongbo Chen, Guohua Lu, Ting Dang, Hong Jia
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [82] AIR-LLM: Broadcasting AI Weights over Radio for Memory-Free Edge LLM Inference via RF Computing

**链接**: https://arxiv.org/abs/2610.00465
**作者**: Zhihui Gao, Tingjun Chen, Dirk Englund
**来源**: cs.IT cs.ET cs.LG eess.SP math.IT physics.app-ph
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Next-generation large language models (LLMs) are expanding from the cloud to ubiquitous edge devices. However, edge devices typically either lack the memory to store increasingly large LLM weights or, even with enough memory, spend unaffordable energy on loading the weights. This raises our question: can an edge device run an LLM without storing or loading its weights, but receive them over the air and consume them on the fly? Inspired by wireless broadcasting, we present AIR-LLM, an LLM inference architecture for edge devices, which is composed of: (i) a central radio (e.g., 5G base stations) that broadcasts the LLM weights into the air, and (ii) the edge user that receives the weights and completes the general matrix-vector multiplication (GEMV) of LLM inference directly in the radio frequency (RF) domain using RF mixers. To further shorten the airtime, AIR-LLM exploits MIMO spatial multiplexing and proposes an energy-efficient precoder-postcoder pair on the edge to calibrate its own

---

### [83] DECK: A Consistency x Confidence Taxonomy of LLM Hallucinations

**链接**: https://arxiv.org/abs/2606.02289
**作者**: Mohit Singh Chauhan
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] When Do Causal World Models Help Modular LLM Agents

**链接**: https://arxiv.org/abs/2610.00012
**作者**: Xinyuan Song, Zekun Cai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly act through modular systems, such as order, payment, inventory, and shipment services, where actions in one module change which transitions are valid in another. Standard world models usually fit observational traces, but this is not the quantity needed for intervention-time planning: a trace may show that payment precedes shipment without identifying whether payment authorizes shipment, inventory mediates the effect, or a hidden trigger explains both. We study this gap through FedCausalCompose, a causal world-model framework for modular LLM agents in which local actions provide intervention-response evidence for cross-module interfaces. We first show that observational world models incur an irreducible interventional error under unblocked back-door paths, that interface recovery improves with intervention-response coverage, and that an oracle causal composition can beat the non-causal lower bound when coverage and local mechanism errors are controlled. We then 

---

### [85] Understanding Issues, Causes and Solutions in Open-Source LLM-based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.00905
**作者**: Asad Ur Rehman, Syed Mohammad Kashif, Ruiyin Li, Peng Liang, Zengyang Li, Arif Ali Khan
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the advancement of LLM-based multi-agent systems (MAS), an increasing number of opensource projects are adopting multi-agent architectures as the foundation of their core functionality. Although research and practice on MAS have attracted considerable attention, limited studies have explored the challenges faced by practitioners of open-source LLM-based MAS, the causes of these challenges, and potential solutions. To address this gap,we conducted an empirical study to understand the issues that practitioners encounter when developing and using open-source LLM-based MAS, the possible causes of these issues, and potential solutions. We collected 22,848 closed issues from 21 open-source LLM-basedMASand applied a mixed automated and manual filtering approach to reduce the dataset to 944 issues related to LLM-based MAS.We then analyzed these issues to understand the frequent issues encountered by practitioners, their underlying causes, and potential solutions. Our study results show th

---

### [86] M-CALLM: Multi-level Context Aware LLM Framework for Group Interaction Prediction

**链接**: https://arxiv.org/abs/2511.14661
**作者**: Diana Romero, Xin Gao, Daniel Khalkhali, Salma Elmalaki
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [87] T2SPO: Trajectory-to-Step Policy Optimization for Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.00388
**作者**: Bo-Wen Zhang, Junwei He, Maoqi Liu, Feiran Li, Song-Lin Lv, Wentao Ma 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning enables large language model (LLM) agents to learn multi-step behaviors through interaction with their environments. However, rewards in many interactive tasks reflect only the final outcome, providing limited guidance on which intermediate decisions advance the task. Successful training trajectories contain intermediate states that can provide supervision for subsequent interactions. We introduce Trajectory-to-Step Policy Optimization (T2SPO), a method that uses past interaction trajectories to provide step-level feedback for policy learning. T2SPO derives remaining-distance targets from successful trajectories and pairs them with representations of the states visited along the way. Conditioned on these examples, a pretrained TabPFN regressor estimates the remaining distance to success at each state of a new rollout. Changes in this distance estimate across consecutive states yield auxiliary credit for agent steps alongside task-level supervision. As training pr

---

### [88] LLM-Guided Transportation Hub Capacity Planning with Textual Business Inputs

**链接**: https://arxiv.org/abs/2607.03651
**作者**: Xiaoyue Liu and Zheng Dong
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [89] Measuring the Microtask Eligibility Gap: When Is an Off-the-Shelf SLM Enough for an Agent Harness?

**链接**: https://arxiv.org/abs/2610.00025
**作者**: Jundong Hu, Shekar Ramachandran
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent harnesses increasingly want to run small language models (SLMs) on the microtasks around a frontier large language model (LLM) planner: auto-approving shell commands, writing memory, selecting tools, ranking past turns. We ask whether off-the-shelf SLMs meet practitioner-defined thresholds and, when they fail, why, and whether quantization changes the answer. We build a benchmark of 4 such microtasks with fixed prompts and automatic metrics, each with a pre-specified threshold $\tau$ anchored to a cheap non-LLM baseline and a CI-aware eligibility rule (a configuration passes only if its confidence bound clears $\tau$). Sweeping Qwen3 0.6/1.7/4/8B at their best (FP16, greedy, one frozen prompt, no tuning), we find an eligibility gap: 0 of 16 (4 tasks $\times$ 4 models) configurations pass (verified by checking the raw outputs and parser behavior). A logprob decision-threshold diagnostic (T1/T3/T4; T2 via a context-length/cascade probe) separates the failures into capability defici

---

### [90] It Takes Workflows to Evolve Better Workflows

**链接**: https://arxiv.org/abs/2610.01026
**作者**: Xuehang Guo, Haoyu Wang, Haifeng Chen, Yangyi Chen, Zhenhailong Wang, Qingyun Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tackling complex real-world tasks can exceed the capabilities of a single large language model (LLM), motivating the use of multi-agent workflows that coordinate specialized agents to work together on these tasks. Recent methods train LLMs to construct better workflows from execution outcomes, but they optimize only the workflow generator, while the other agents that build or execute each workflow remain fixed even though every outcome depends on all of them. However, extending training beyond the generator is challenging: the agents are coupled, and a workflow's outcome is a single sparse score that cannot tell which agent causes a failure. We propose FloWright, which leverages the workflow as a harness to optimize workflows. By introducing a hierarchical, structure-aware reward paradigm, FloWright enables one role to self-evolve and two or more roles to co-evolve, with no additional models, labels, or executions. Considering the limitation that workflows are commonly trained and eval

---

### [91] Clinical Note Bloat Reduction for Efficient LLM Use

**链接**: https://arxiv.org/abs/2604.16364
**作者**: Jordan L. Cahoon, Chloe Stanwyck, Asad Aali, Rachel Madding, Sulaiman S. Somani, Emma Sun 等 (9 人)
**来源**: cs.CY cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [92] HHR: Hierarchical Hash Retrieval for Efficient LLM Generation

**链接**: https://arxiv.org/abs/2610.01230
**作者**: Lianjun Liu, Tiantian Zheng, You Huang, Weiqi Yan, Mingte Qiu, Huazhong Liu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient long-context inference is essential for large language models (LLMs), yet it poses a severe computational bottleneck. Hash-based retrieval offers an efficient alternative by encoding queries and keys into binary codes and using Hamming distance for key selection. However, this leads to a critical mismatch between Hamming distance and attention relevance. Query-Key logits depend jointly on directional similarity and feature magnitudes, whereas hash binarization discards magnitude information, causing both false-positive retrieval of low-logit keys and false-negative omission of high-logit keys. To address these failures, we propose Hierarchical Hash Retrieval (HHR), a coarse-to-fine framework that progressively improves retrieval accuracy through Geometry-Aware Key Routing (GKR) and Learned Hash Projection (LHP). GKR learns a head-wise orthogonal transformation to redistribute feature magnitudes and derive more discriminative page-level logit bounds, enabling effective pruning

---

### [93] Paying for Too Many Tokens? Valid and Cost-Efficient Multimodal LLM Annotation with Simple Heuristics

**链接**: https://arxiv.org/abs/2610.00809
**作者**: Zhixi Zhu and Kristina Gligoric
**来源**: cs.CV cs.CL cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language Models (VLMs) enable video annotation at scale, but costs accumulate quickly: processing a typical 60-second short-form video at one frame per second requires millions of tokens. To reduce costs, researchers rely on heuristics such as sampling a subset of frames, compressing videos into image grids, or using only a single modality. However, it remains unclear which heuristics save cost, and whether they preserve the downstream conclusions these annotations enable. To address this gap, we conduct a systematic evaluation of these heuristics using short-form videos, on two computational social science (CSS) tasks: sentiment and topic classification. We evaluate each configuration along three axes the literature typically treats separately: classification accuracy, validity of downstream inference, and per-video token cost. First, we find that accuracy and validity diverge: the highest-accuracy configuration can produce wrong conclusions. Second, modality value is not guara

---

### [94] Inspector: Conversational and Lightweight Analyzer of Analog Circuit Layouts Using LLM and CNNs

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.34976&hl=zh-CN&sa=X&d=1898945857652069888&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVGVfFJsWFpmb-5SAH_t8Ulo&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=3&folt=kw-top
**作者**: AC Castro, G Chiari, M Piccoli, F Viola, D Zoni - arXiv preprint arXiv:2609.34976, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper presents Inspector, a hybrid LLM -CNN framework for conversational analysis of analog circuit layouts directly from GDSII data. By combining semantic reasoning with specialized visual detection, the proposed pipeline enables

---

### [95] ReLiveGym: Evaluating Long-Lived Agents over Weeks of Replayed Reality

**链接**: https://arxiv.org/abs/2610.00710
**作者**: Xisen Jin, Jingheng Li, Zhenglun Chen, Junyi Du, Xiang Ren
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language model (LLM) agents become widely adopted, they are increasingly deployed for tasks that require persistent monitoring or recurring actions (e.g., market analysis). These agents are expected to operate unattended for days or weeks, act at the right timing, and adapt to the dynamic environment over time. These challenges are not fully captured in the existing long-horizon agent work, as they often consider a static environment that is not temporally changing. We introduce ReLiveGym, a diagnostic evaluation environment of long-lived tasks in which agents act sparsely over simulated weeks of chronologically replayed real-world news, market, and social-media streams. The tasks span diverse levels of time sensitivity, reasoning intensity, and recurrence. Across eight base language models, we investigate how model choice and harness design affect agent performance on such long-lived tasks. Our results show that how agents determine when to act arises as an important harness-

---

### [96] Certainty Is Not Just Correctness: Rethinking Token-Level Certainty in LLM Reasoning

**链接**: https://arxiv.org/abs/2610.00296
**作者**: Yunfan Zhou, Ye Zhu, Zhihai Wang, Jianguo Yao, Haibing Guan, Xijun Li
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Token-level certainty is widely used as a proxy for correctness in LLM training and inference. However, the performance of certainty-based methods depends both on the information in certainty scores and on how those scores are used. We therefore directly assess certainty's predictive ability through controlled empirical evaluations across models and tasks. We distinguish two prediction targets: identifying questions a model is more likely to answer correctly and distinguishing correct from incorrect responses to the same question. In our experiments, certainty is generally better at identifying questions a model is likely to answer correctly than at distinguishing correct from incorrect responses to the same question. Certainty also varies systematically across token types and positions within words, reflecting local properties of words and text form. Information about question difficulty appears early in generation, while the weaker information about answer correctness is more concent

---

### [97] When Does a Second Model Help? Cross-Model Review in LLM Verification

**链接**: https://arxiv.org/abs/2610.01471
**作者**: Tae-Eun Song
**来源**: cs.CL cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [98] On the Behavioral Traits of LLM Agents

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.32776&hl=zh-CN&sa=X&d=16886920856362292844&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVH4slgC9pX3fms8XEWQb2WJ&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=7&folt=kw-top
**作者**: H Zhao, J Gao, Y Xiao, X Wang, W Xuan, A Joshi… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We introduce A-B-D, a generalizable and scalable analysis pipeline for characterizing LLM agents through their behaviors. It extracts … To validate the annotation results, we compare the LLM -annotated behaviors with human annotations on a randomly

---

### [99] Beyond Final Accuracy: Auditing Communication in LLM Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.01042
**作者**: Shixuan Li, Wei Yang, Peiyu Zhang, Anzhe Cheng, Heng Ping, Paul Bogdan
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent communication aims to help agents benefit from one another's information. Yet improvements in system performance leave a fundamental ambiguity: do they reflect effective communication, a favorable agent architecture, or simply additional reasoning? Because communication methods are commonly evaluated within the systems they were designed for, these factors are difficult to disentangle. Final accuracy further merges corrected errors and corrupted answers into a single outcome, obscuring how communication changes decisions. We introduce Independent--Communicate--Revise (ICR), a controlled framework that evaluates communication as answer revision following independent reasoning. ICR fixes initial reasoning trajectories, measures correction and preservation conditional on both agents' initial correctness, and uses a no-message revision control to quantify gains beyond additional reasoning. Across four reasoning benchmarks, our audit of textual and latent communication reveals t

---

### [100] The Weakest Link: Distilling LLM Reasoning with Worst-Case Constrained Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.00332
**作者**: Matthieu Zimmer, Xiaotong Ji, Tu Nguyen, Haitham Bou-Ammar
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Distilling the reasoning capabilities of large language models (LLMs) into smaller students is a central challenge for efficient deployment. Current approaches face a fundamental tension: optimizing purely for verifiable task rewards (e.g., via GRPO) leads to reward hacking, where students arrive at correct final answers through flawed intermediate logic, while regularizing with soft divergence penalties against a teacher (e.g., KL-based distillation) dilutes task performance and, critically, allows the student to compensate for severe logical violations at one step with high teacher agreement at others. We argue that this averaging is fundamentally misaligned with the nature of reasoning: a chain-of-thought is only as valid as its weakest link. Motivated by this observation, we formulate reasoning distillation as a constrained reinforcement learning problem in which the task reward is maximized subject to a worst-case constraint on the teacher log-likelihood along every prefix of the 

---

### [101] Evaluating Memory Structure in LLM Agents

**链接**: https://arxiv.org/abs/2602.11243
**作者**: Alina Shutova, Alexandra Olenina, Ivan Vinogradov, Anton Sinitsin
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [102] Science Utopia? Closed-Loop LLM Simulation of Academic Research Ecosystems

**链接**: https://arxiv.org/abs/2610.01257
**作者**: Yiqiao Jin, Yiyang Wang, Lucheng Fu, Bing He, Siheng Xiong, Yijia Xiao 等 (10 人)
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific progress emerges from a longitudinal ecosystem in which researchers, institutions, funding agencies, collaboration networks, and the scientific literature co-evolve. As AI becomes increasingly involved throughout the scientific research cycle, understanding these interconnected and evolving processes becomes increasingly important. We introduce SciUtopia, a persistent, closed-loop LLM-agent simulation framework for studying academic research ecosystems. SciUtopia models interconnected scientific processes such as research-direction choice, collaboration, submission, peer review, resubmission, citation, funding, and researcher attrition, while maintaining evolving states across simulated years. Its configurable institutional mechanisms and information channels provide a controlled testbed for matched counterfactual experiments and targeted interventions. Across 61 simulation worlds, SciUtopia simulates over 40,000 researchers from 8,000 institutions, producing around 400,000 

---

### [103] Which LLM to pick? Online Active Model Selection for Large Language Models

**链接**: https://arxiv.org/abs/2610.01592
**作者**: Alessandro Turrin and Patrik Okanovic and Torsten Hoefler and Nezihe Merve G\"urel
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly applied to process streaming data, with practitioners relying on benchmarks to select the best model even though these signals only approximate real performance. While oracle annotations can provide reliable feedback, they are often costly and difficult to obtain at scale. To address this challenge, we propose ONLINE LLM PICKER, the first framework for active model selection for LLMs in online settings. Given an arbitrary stream of queries and a limited annotation budget, ONLINE LLM PICKER selects the most informative prompts for annotation to identify the best LLM among candidate models. Across multiple tasks including 10 datasets, for over 130 language models, we show that ONLINE LLM PICKER saves annotation cost by up to 71.67% while reliably identifying the best or near-best model for the stream. We also show that using the returned model for sequential generation on unannotated prompts across the stream reduces regret by up to a factor 

---

### [104] The Innocent Courier: Covert Exfiltration Through Legitimate LLM Web Fetching

**链接**: https://arxiv.org/abs/2610.01768
**作者**: Alessandro Pegoraro, Daryan Merx, Phillip Rieger, Ahmad-Reza Sadeghi
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the increasing capabilities of Large-Language-Models (LLMs) and LLM-based agents, users are increasingly using them to solve everyday problems, such as answering e-mails or providing programming support. Existing work has extensively investigated security and privacy risks, such as prompt injections and the disclosure of sensitive data to chatbot providers. While various solutions were developed to address these risks, including input structuring to prevent prompt injections or deploying local LLMs to avoid sharing confidential data with chatbot operators, LLMs also pose the risk of leaking confidential data to third parties. In this paper, we demonstrate with LLMLeak a novel attack vector where malicious software that runs locally but cannot communicate directly with the internet abuses LLMs to establish a covert channel. While inputs that instruct the LLM to send data directly via generated code are easy to detect and network libraries are typically restricted, LLMLeak relies on

---

### [105] SkillSpec: Consensus-Gated Agent Skill Evolution via Representation Specialization

**链接**: https://arxiv.org/abs/2610.00704
**作者**: Huancheng Chen and Xiaodi Sun and Zhaoqiong Huang and Shenyang Huang Shreya Singhal and Jingwen Lu
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language skills are textual procedural memories through which large language model (LLM) agents retain reusable task knowledge without updating model weights. Existing methods typically treat skills as either static artifacts or monolithic documents optimized using aggregate validation scores as feedback. However, representing a skill as a monolithic document restricts optimization to its textual content, without explicitly modeling the structure through which procedural knowledge is retrieved and executed. We identify a key distinction between learning what knowledge to retain and determining how to organize it: textual updates should first be validated through execution evidence, after which the retained knowledge should be structured according to its procedural dependencies and retrieval requirements. To this end, we introduce SkillSpec, a two-phase framework comprising consensus-gated evolution and representation specialization. In the consensus-gated phase, complementary e

---

### [106] What Does a Skill Actually Do? Estimands and Evaluation Validity for Tool and Skill Use in LLM Agents: A Critical Review

**链接**: https://arxiv.org/abs/2609.33153
**作者**: Shuyang Zhang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] What Wins a Vote? Formatting, Length, and Lexical Diversity in the French Compar:IA LLM Arena

**链接**: https://arxiv.org/abs/2610.01316
**作者**: Simonas Zilinskas, Maayeesha Farzana, Christophe Benavent
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM arenas turn pairwise human preferences into model rankings. Those preferences may reflect how an answer is presented as well as what it says. We take a stylometric approach to 137,293 decisive French-language votes from the July 2026 Compar:IA release; the primary formatting analysis includes 137,113 battles across 116 models, and the joint estimates use the 127,092 battles with all required measurements. For each battle, we reconstruct the response visible when the user voted. We then compare the raw ranking with rankings adjusted for formatting, length, readability, vocabulary variety, and sentence structure. Presentation is associated with winning, but length, bold text, and lists tend to occur together, making their individual contributions hard to separate. Across the measured features, two associations change least across specifications: bold usage (+11.0% win odds per standard deviation in the joint model) and moving-average type-token ratio (MATTR), a measure of vocabulary 

---

### [108] From Discovery to Decision: Finite-Budget Recoverability in LLM Voting

**链接**: https://arxiv.org/abs/2610.01014
**作者**: Shaoang Li, Jian Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Voting over multiple LLM responses is a common primitive in test-time scaling and ensemble inference. Collecting more responses can expand the candidate pool and increase the chance that a correct answer is discovered. Under a fixed call budget, a discovered answer still needs to accumulate enough support within the remaining calls to become the final plurality winner, creating a discovery-to-decision gap. In this work, we characterize this gap through the realized vote state and remaining call budget. We derive a sharp recoverability threshold and show that, as sampling proceeds, the observed candidate set can only expand while the set of reachable endpoint winners can only contract, inducing a candidate-level conversion window. Under a specified iid response law, the same state yields exact finite-horizon endpoint probabilities. We further show that merging wrong-answer identities preserves single-call correctness and cannot improve plurality accuracy, and that the effect of redistri

---

### [109] Distilling LLM Reasoning into Graph of Concept Predictors

**链接**: https://arxiv.org/abs/2602.03006
**作者**: Ziyang Yu, Liang Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [110] Old Ideas, Novel Problems: The Instability of LLM-Based Novelty Evaluation

**链接**: https://arxiv.org/abs/2610.02022
**作者**: Noy Sternlicht, Simra Shahid, Peter Jansen, Daniel S. Weld, Pao Siangliulue, Tom Hope
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated ideation systems are often evaluated on the novelty of the ideas they produce, and that judgment is increasingly delegated to large language models. Such judges are typically built ad hoc and validated, if at all, on human-authored papers rather than on the generated ideas they are meant to score. So, how do novelty judges perform? Not well. We present a systematic controlled study of novelty evaluation design choices. We first build an evaluation set automatically, mining OpenReview for passages where reviewers explicitly affirm or dispute a paper's originality and keeping only submissions with unanimous agreement at the extremes of their research area; we pair these with ideas from a vanilla LLM generator. Across six judges, we find that small prompt design choices have large consequences; e.g., simply telling the judge that reviewers found one idea novel and the other not can change its verdict on more than half of the identical idea pairs it is shown, shifting pairwise ac

---

### [111] Before Agents Decide: Epistemic Action in LLM-Based Systems

**链接**: https://arxiv.org/abs/2610.00511
**作者**: Yizhi Liu, Balaji Padmanabhan, Siva Viswanathan
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Before a difficult decision, people often act simply to understand the situation better. We turn an object to see another side, place alternatives next to each other, or change one condition and observe what happens. These actions may not complete the task, but they improve the evidence needed for the next choice. LLM-based agents can search and explore, yet agent design gives less attention to an earlier question: is the available evidence ready for the decision? Sometimes necessary evidence is missing. In other cases, the evidence is present but its form hides what matters, or the comparison needed to judge it does not yet exist. Cognitive science calls actions that improve the basis for a later choice epistemic actions. We bring this idea to LLM-based agents and distinguish three modes: acquiring missing evidence, transforming available evidence, and probing a system to create a revealing response. We use the term epistemic scaffolding for the interfaces, tools, and environments tha

---

### [112] The First Token Is Not the Verdict: Hidden Costs of Reading LLM Judges Without Generating

**链接**: https://arxiv.org/abs/2610.00054
**作者**: Gnaneswar Villuri, Hashmath Shaik, and Alex Doboli
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reading an LLM judge's verdict from the logits of its first generated token is cheap, requires no generation, and is exactly what constrained decoding and likelihood-scoring evaluation harnesses produce. We show that this readout distorts position bias in one direction: it overstates it in every condition we test, so figures obtained this way behave as upper bounds. The mechanism is that judges do not always lead with a verdict token, on 12% to 49% of pairs for three Qwen3 judges and under 3% for Llama-3.1-8B and Phi-3.5-mini, and forcing a read on those pairs returns whichever response was shown first rather than a judgment. Pooled over the 924 pairs where a judge did not commit, the forced read flips on 89.7% of them when the responses are swapped, against 47.5% read after generation (paired difference +0.422, 95% CI [+0.365, +0.467]). The distortion is specific to what is measured: it moves position bias by 42 points while moving judge accuracy by under one point in seven of ten con

---

### [113] TACO: Ternary Absolute-max Column-wise One-sparse Optimizer for LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.02199
**作者**: Jichao Jiang (1), Cristian McGee (1), El Houcine Bergou (2), Hanqin Cai (1), Aritra Dutta (1) ((1) University of Central Florida, (2) Mohammed VI Polytechnic University)
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Full-parameter fine-tuning of large language models (LLMs) incurs substantial optimizer state memory overhead, limiting the model sizes that fit on modern GPUs. Existing approaches either compress optimizer state, abandon first-order gradients, or change the update geometry while retaining dense state. The recently introduced Muon optimizer reduces optimizer memory through matrix-valued updates. Still, its geometry differs from AdamW and can lead to performance degradation when fine-tuning AdamW-pretrained models. To reduce optimizer memory without sacrificing accuracy or computational efficiency in LLM fine-tuning, we propose Ternary Absolute-max Column-wise One-sparse optimizer, or TACO, which follows Muon's operator-norm steepest-descent view but takes the geometric route further. TACO computes the exact steepest-descent direction under a dimension-normalized $1\to1$ operator norm by selecting the sign of the largest magnitude entry in each column of two-dimensional weight matrices.

---

### [114] Who Wrote the Book? Detecting and Attributing LLM Ghostwriters

**链接**: https://arxiv.org/abs/2603.28054
**作者**: Anudeex Shetty, Qiongkai Xu, Olga Ohrimenko, Jey Han Lau
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [115] dattri-LLM: A Unified and Efficient Library for Training Data Attribution at LLM Scale

**链接**: https://arxiv.org/abs/2609.38767
**作者**: Shixuan Liu, Tongli Zhou, Junwei Deng, Pingbang Hu, Jiaqi W. Ma
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] Denoising Surface: Modeling and Predicting Inference Cost for Diffusion LLM Serving

**链接**: https://arxiv.org/abs/2610.00499
**作者**: Haoyu Zheng, Fangcheng Fu, Binhang Yuan, Yongqiang Zhang, Liang Deng, Hao Wang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As diffusion large language models (dLLMs) become more capable, they are moving from research settings to real-world \textit{serving}, where request management (such as scheduling and resource allocation) relies on accurate estimation of per-request inference cost. However, common cost proxies fall short for dLLMs: output length ignores that one forward pass can unmask multiple tokens, and denoising-step count ignores the \textit{heterogeneous} per-step costs. We observe that the block-autoregressive generation mechanism induces a two-dimensional execution structure over output blocks and within-block denoising steps, whereas these proxies collapse it into a scalar, discarding information essential for characterizing the cost. Motivated by this insight, we propose the Denoising Workload Surface (DWS), which preserves this two-dimensional block-step structure as a probability surface to weight the heterogeneous per-step costs. We then design a coarse-to-fine training scheme that enables

---

### [117] Probing an Embodied LLM: When Higher Observation Fidelity Hurts Problem Solving

**链接**: https://arxiv.org/abs/2605.20072
**作者**: Oussama Zenkri and Oliver Brock
**来源**: cs.AI cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] MINCE: Shrinking LLM Evaluation Datasets via Few-Model Monte Carlo Calibration

**链接**: https://arxiv.org/abs/2606.22826
**作者**: Devleena Das, Rajeev Patwari, Vikram Kumar Bukka, Nithin Kumar Guggilla, Elliott Delaye, Ashish Sirasao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] Text-Preserving Lossy Text Compression: A Study of Strategic Deletion and LLM Reconstruction

**链接**: https://arxiv.org/abs/2605.29000
**作者**: Yuchun Zou, Junhong Tong, Jun Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [120] Aligned but Not Partner-Specific: How Multimodal LLM Agents Succeed in Reference Games Without Forming Conceptual Pacts

**链接**: https://arxiv.org/abs/2606.08081
**作者**: Po-Ya Angela Wang, Chinmaya Mishra, Asl{\i} \"Ozy\"urek, Paula Rubio-Fern\'andez, Esam Ghaleb
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [121] DeFA: Dependency-Guided Failure Attribution for LLM Agents

**链接**: https://arxiv.org/abs/2610.01256
**作者**: Bo Deng, Xinlei Zheng, Yi Wei, Kang Zhou, Chongyang Tao, Renzhao Liang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Errors in LLM agent executions and their visible consequences can be separated by many steps, making decisive-error localization a matter of understanding both step content and step dependencies. We introduce DeFA, a dependency-guided framework for agent failure attribution. DeFA first combines protocol relations and semantic dependencies into an event dependency graph spanning the trajectory. It then identifies events that may violate task requirements and traces their sources and subsequent effects to construct a failure propagation graph. Finally, DeFA uses step evidence and the steps' roles in failure propagation to identify the decisive error, responsible agent, and error category. To support long trajectories, DeFA partitions executions into segments and combines the current segment's detailed content with summaries of the other segments, giving local diagnosis access to global execution context. Across Who and When and the Who and When Pro text subset, DeFA achieves the highest 

---

### [122] Reasoning as Pattern Matching: Shared Mechanisms in Human and LLM Everyday Reasoning

**链接**: https://arxiv.org/abs/2606.13607
**作者**: Zach Studdiford and Gary Lupyan
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] Beyond Memory: Harnessing Long-Horizon Agents with Explicit Belief States

**链接**: https://arxiv.org/abs/2610.01415
**作者**: Yu Luo, Jiamin Jiang, Yimin Zuo, Xidao Wen, Rongchen Gao, Yongqian Sun 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can now undertake increasingly complex tasks, but the way they organize interaction history into memory does not ensure a coherent understanding of the current world. We introduce PoS, an inference-time framework that constructs and continually maintains explicit belief states as the agent's decision context. Each belief combines an estimate of the current world state with unresolved task requirements, making explicit what the agent still needs to learn and accomplish. To keep this belief reliable and actionable, PoS validates its consistency and monitors task progress to detect Belief Trapping, where the agent continues to act without making meaningful progress toward the goal. Recovery is then tailored to both the trapping pattern and the type of unresolved task requirement. Experiments on four benchmarks spanning execution and diagnosis show that PoS achieves the highest overall performance on every benchmark with all three LLM backbones. Ablations 

---

### [124] Automated Database Testing via LLM -Synthesized SQL Features

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3837097&hl=zh-CN&sa=X&d=1552259204078206421&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVGWRuOzKFoWTT0ZW-qChMyH&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=6&folt=kw-top
**作者**: S Zhong, M Rigger - Proceedings of the ACM on Management of Data, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To avoid the high cost and low throughput of directly instructing the LLM to generate SQL tests (see Section 2.2), we persist knowledge gained through LLM interactions; after a user has decided that a sufficient number of features has been

---

### [125] AI Agent with Model Selection, Tool Synthesis, and Proactive Knowledge Base Management

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11700205/&hl=zh-CN&sa=X&d=3581636132192771496&ei=eES_arW5Ecyp6rQPheW1-Aw&scisig=ACTRDVHBaSvXo5pSx3QmTpAcClJI&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=3&folt=kw-top
**作者**: J Jelínek - 2026 16th International Conference on Advanced …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> implementation of an adaptive AI agent that extends conventional large language model (LLM) … The architecture integrates a user interface, an orchestrator, multiple external language models , … This work proposed an adaptive agent platform that

---

### [126] Easier Said Than Done: Unpacking Intent-Behavior Gap in Jailbreaking LLM-Based Robots

**链接**: https://arxiv.org/abs/2412.16633
**作者**: Xuancun Lu, Zhengxian Huang, Xinfeng Li, Chi Zhang, Xiaoyu Ji, Wenyuan Xu
**来源**: cs.RO cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [127] Skin-Deep: A Geometric Diagnostic for Alignment Fragility in Large Language Model Representations

**链接**: https://arxiv.org/abs/2606.22676
**作者**: Dongyub Jude Lee, Jungseob Lee, Seungyoon Lee, Seongtae Hong, Suhyune Son, Sugyeong Eo 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] Trust the Direction, Search the Step: Zero-and-First-Order Methods for LLM Fine-Tuning

**链接**: https://arxiv.org/abs/2610.02190
**作者**: Cristian McGee, El Houcine Bergou, Aritra Dutta
**来源**: cs.LG math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Step-size selection remains a central challenge in large-scale neural network optimization; conservative steps slow convergence, while aggressive steps can destabilize it. We combine \textbf{Z}ero-and-\textbf{F}irst-\textbf{O}rder optimization~(ZFO) and propose a lightweight framework that decouples direction selection from step-size. ZFO uses a trusted first-order optimizer to determine the direction and performs zeroth-order evaluations only along this one-dimensional subspace to choose how far to move. Using the current {gradient information} and two additional objective function evaluations, ZFO instances construct a local model of the objective function along the proposed direction and select a curvature-aware step within a bounded search interval. This yields an adaptive step-selection mechanism that costs less than a full line search. We provide theoretical guarantees to show that shared-sample evaluations produce reliable finite-difference curvature estimates, that the induced 

---

### [129] Privacy management in LLM -based self-diagnosis: a cross-cultural study across 25 countries

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0736585326001012&hl=zh-CN&sa=X&d=4218839814914704427&ei=eES_avfxB8yp6rQPheW1-Aw&scisig=ACTRDVGW02iJgFhZ9gzqOIEJjMi9&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=4&folt=kw-top
**作者**: G Zhu, Y Zhang, D Zhang - Telematics and Informatics, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large Language Models (LLMs) for self-diagnosis create a tension between access to medical information and the disclosure of sensitive health information. Adopting a Communication Privacy Management (CPM)-informed perspective, this study

---

### [130] Probe with Participation Trophies: Random-Reward RL as a Probe of LLM Capability

**链接**: https://arxiv.org/abs/2610.01066
**作者**: Yu Mao, Lei Yu, Zining Zhu, Yusheng Zheng, Haohang Li, Freda Shi 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We connect the spurious-reward paradox to a model's reachability and propose random-reward reinforcement learning (RL) as a useful tool for the probing enterprise, addressing a decade-long debate over what probing performance actually reveals about a model. There are two prevailing explanations for the surprising finding that even random rewards can improve the performance of large language models (LLMs): one attributes the gains to particular mechanisms within RL training; the other to data contamination. Our results motivate a different view: spurious-reward RL can probe a model's reachability, or what further training can attain from its current state under specified constraints, beyond what is reflected in its current performance. Two OLMo checkpoints with the same accuracy on synthetic arithmetic (3.5%), for example, reach 8.5% and 55% in their best runs under the same correctness-rewarded RL. Examining OLMo checkpoints across pre-training and mid-training reveals three distinct r

---

### [131] Counting Moves, Weighing Voices: Bayesian Dialectical Argumentation for Calibrated Multi-LLM Councils under Persistent Adversaries

**链接**: https://arxiv.org/abs/2610.02005
**作者**: Ionel Eduard Stan and Paolo Napoletano
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A multi-LLM \emph{council} lets several large language models (LLMs) deliberate on a question and return an answer together with a confidence estimate. As these systems become increasingly used for reasoning, that confidence should represent a calibrated \emph{probability of being correct}, and the decision should remain robust when some agents are persistently unreliable. Existing \emph{council aggregation} methods fail on both fronts: their confidence estimates measure decisiveness rather than correctness, and they cannot identify or discount persistently unreliable agents. We introduce Bayesian Dialectical Argumentation (BDA), which treats the council's \emph{typed} moves---who proposed, challenged, or conceded which answer---as observations of a classical annotator model with \emph{per-agent} reliabilities. This formulation recasts multi-agent deliberation as a reliability estimation problem, using the deliberation trace to infer agent reliability under persistent adversarial behav

---

### [132] SkillLens: Adaptive Multi-Granularity Skill Reuse for Cost-Efficient LLM Agents

**链接**: https://arxiv.org/abs/2605.08386
**作者**: Ziyang Yu, Yongliang Miao, Liang Zhao, Bowen Zhu, Hasibul Haque
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] The Devil Is in the Reconstruction Loss Scale: Rethinking Optimization in LLM Quantization

**链接**: https://arxiv.org/abs/2610.00983
**作者**: Chao Li, Shigeng Wang, Anbang Yao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training quantization (PTQ) methods typically use sequential quantization that partitions a pre-trained LLM into a series of units (e.g., transformer blocks), with one unit quantized at each stage. State-of-the-art PTQ methods are predominantly learning-based, optimizing auxiliary quantization parameters (e.g., scaling factors, rotation matrices, clipping thresholds, and adapters) via gradient descent to minimize a reconstruction loss. A common practice is to use mean squared error (MSE) as the reconstruction loss function, yet its induced optimization behavior remains largely unexplored. In this work, we take a holistic view of sequential quantization and systematically investigate how optimization evolves from the first quantization stage to the last, aiming for a deep understanding of optimization in learning-based PTQ schemes. Through extensive empirical studies spanning representative learning-based PTQ methods, LLM families, model scales, architectures, quantization settings

---

### [134] In Vino Veritas and Vulnerabilities: Examining LLM Safety via Drunk Language Inducement

**链接**: https://arxiv.org/abs/2601.22169
**作者**: Anudeex Shetty, Aditya Joshi, Salil S. Kanhere
**来源**: cs.CL cs.AI cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] SkillEvoLean: Mutation-enhanced skill evolution for Lean provers

**链接**: https://arxiv.org/abs/2610.01799
**作者**: Kuo Zhou, ZiXion Yang, Lu Zhang
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Skill evolution offers a promising way to improve large language model agents without updating their parameters, but its use in formal theorem proving remains underexplored. Existing methods mainly target natural-language reasoning, improving skills by analyzing successful and failed trajectories and incrementally revising solving strategies. Although the Lean verifier provides reliable execution feedback, when all sampled trajectories fail, existing skill evolution methods lack successful trajectories from which to infer effective update directions. Furthermore, these methods also focus mainly on the root instruction file, thus underexploring the evolution of reference knowledge including mathematical concepts and proving techniques. To address these limitations, we propose a mutation-enhanced skill self-evolution framework for building skill-augmented Lean provers. The framework jointly evolves a high-level solving policy and its reference knowledge through progressive and mutation-b

---

### [136] A rubric landscape for evaluating clinical reasoning in large language models: what exists, what is missing, and what needs to be combined

**链接**: https://arxiv.org/abs/2610.01938
**作者**: Zhangshu Joshua Jiang, Zina Ibrahim, James T. Teo
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Exam-style accuracy does not establish whether large language models (LLMs) reason well over clinical records. We define clinical reasoning as integrating and updating evidence across time and sources to form, revise and justify a patient's problem representation and a defensible plan. This structured narrative review maps three literatures: medical education assessment instruments, clinical LLM benchmarks published from 2023 onwards, and general-domain methods for evaluating long-form generation. We examine six dimensions: problem representation, temporal synthesis, differential and management reasoning, counterfactual reasoning, calibrated uncertainty, and reasoning faithfulness. Preprints are included and flagged. No single instrument covers all six dimensions. Problem representation and differential or management reasoning are reasonably covered, although reliability varies by instrument and setting. TIMER-Eval targets temporal synthesis, and ER-Reason assesses sequential diagnosti

---

### [137] Beyond Leaderboards: Tokenomics of Agentic Small Language Model Ensembles

**链接**: https://arxiv.org/abs/2610.00954
**作者**: Alexei N. Skurikhin, Emily M. Taylor, Nathan A. DeBardeleben
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) move from standalone assistants into agentic workflows, evaluation must extend beyond scalar leaderboard accuracy to account for operational reliability, cost, latency, and token efficiency. We use an agentic ensemble of small language models (SLMs) with an SLM-judge-mediated feedback loop as a case study for such beyond-leaderboard evaluation. On the 541-prompt IFEval benchmark, the best ensemble achieves 97.34% strict prompt accuracy, exceeding the strongest standalone LLM baseline, gpt-5.4, by 5.81 percentage points while operating in a lower-cost regime. We then analyze the tokenomics and operational behavior behind this gain, including cost per sample, token composition, useful-output goodput, feedback-loop recovery, latency decomposition, and performance across instruction categories and constraint counts. Our results show that agentic SLM ensembles can trade additional test-time tokens and orchestration overhead for improved instruction-following 

---

### [138] Range-GRPO: Policy Optimization via Pairwise Relations among Reward Intervals

**链接**: https://arxiv.org/abs/2610.01548
**作者**: Ryunyi Lee, Kangjun Noh, Somin Kim, Heedong Kim, Kyungwoo Song
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As the use of large language models (LLMs) expands, post-training has become increasingly important for adapting them to downstream tasks. However, obtaining reliable supervision remains costly, especially in domains without reference answers or executable verifiers. LLM-as-a-Judge provides scalable pseudo-rewards for unlabeled responses, but a single point score does not explicitly represent reward uncertainty. This motivates representing pseudo-rewards as conformally calibrated reward ranges. We propose Range-GRPO, a semi-supervised post-training framework that combines limited labeled data with unlabeled prompts. In Group Relative Policy Optimization (GRPO), learning signals depend on relative reward comparisons within each rollout group. The proposed objective compares reward ranges pairwise rather than reducing them to point rewards, allowing interval uncertainty to affect both the magnitude and direction of these signals. Our theoretical analysis characterizes this distinction an

---

### [139] MOVE: Multimodal Open-world Verification and Expansion for Graph Learning

**链接**: https://arxiv.org/abs/2610.00268
**作者**: Zekai Chen, Jiayang Xing, Xun Wu, Miao Zhang, Xunkai Li, Kairui Yang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal graph learning faces a fundamental challenge: new classes may emerge after deployment, while models are trained with a fixed label space. Existing approaches typically detect unknown nodes and use LLMs to generate candidate class descriptions, but they do not determine whether existing classes are insufficient to cover these nodes or whether a generated class is reliable enough to expand the class space. Our empirical study reveals three challenges: multimodal information beyond individual modalities is required for unknown-node identification, LLM-generated class descriptions may not fully capture multimodal class characteristics, and directly adding candidate classes can introduce redundant categories. Based on these observations, we propose MOVE, a multimodal open-world class verification and expansion framework. MOVE identifies nodes that cannot be assigned to existing classes by jointly considering visual tokens, textual attributes, and graph context, leverages a multim

---

### [140] Continuous Process-Level Evaluation for Evolving Enterprise AI Agent Skills

**链接**: https://arxiv.org/abs/2610.01833
**作者**: Ngoc Phuoc An Vo, Aarya Doshi, and Vadim Sheinin
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise AI agent skills evolve as tool APIs, models, and specifications change, yet final-output evaluation can miss process-level behavioral drift. We present a continuous evaluation framework combining outcome-level and process-level checks, applied to Revenue and Productivity variants of a Business Value Determination skill in an enterprise Value Aware Resiliency system. The framework independently computes per-run ground truth, materializes reusable template tests, and evaluates tool selection, arguments, execution order, and database integrity through programmatic checks and a narrowly scoped LLM judge. We evaluate 240 trials across two skills, two specification variants, two agent harnesses, and three models. Of 175 trials passing all applicable final numerical checks, 162 (92.6 percent; Wilson 95 percent CI: 87.7-95.6 percent) contained another evaluator-detected deviation. Under a broader seven-check final-state definition, 151 of 164 passing runs (92.1 percent; 95 percent C

---

### [141] On Language Drift during RLVR Post-Training

**链接**: https://arxiv.org/abs/2610.02015
**作者**: Michael Sullivan, Alexander Koller
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in LLM reasoning models---driven primarily by the paradigm of post-training via reinforcement learning with verifiable reward (RLVR)---have enabled them to accomplish impressively complex tasks. However, in parallel with their rising capabilities, LLMs have increasingly displayed signs of language drift in their chains of thought (CoTs): unusual, non-standard, and seemingly nonsensical language use. Although it is well-documented---and can potentially impair CoT monitorability---the causes of language drift are thus far poorly understood. In this paper, we identify the conditions under which language drift occurs: we prove theoretically that RLVR optimization pressure permits unbounded language drift, while supervised fine-tuning does not. We then show empirically that language drift specifically arises during RLVR on novel reasoning tasks---i.e. when the target behavior cannot be drawn out of the base model. Finally, we prove that it is not possible to constrain langua

---

### [142] A Matryoshka Hierarchical RAG for Efficient Multi-Hop Question Answering

**链接**: https://arxiv.org/abs/2610.01767
**作者**: Gianluca Bonifazi, Christopher Buratti, Michele Marchetti, Federica Parlapiano, Giulia Quaglieri, Davide Traini 等 (8 人)
**来源**: cs.CL cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) systems for multi-hop Question Answering (QA) must balance retrieval quality with computational cost. This cost is incurred during indexing time, through the use of expensive Knowledge Graphs (KGs) or Large Language Models (LLMs) to generate summaries, or during querying, through iterative LLM-driven retrieval. To reduce it while maintaining retrieval quality, we present MatRAG, a hierarchical framework that combines RAG systems with Matryoshka Representation Learning (MRL). MatRAG addresses both kinds of cost by aligning the semantic hierarchy of a clustering structure with the nested structure of MRL. Specifically, it organizes the corpus of documents into a Directed Acyclic Graph (DAG) of clusters with progressively coarser granularity. Each level is indexed by a lower Matryoshka dimension. MatRAG pairs an iterative, top-down traversal of the DAG with an entity-driven mechanism that controls the hop budget and re-ranks candidates. We evaluated Ma

---

### [143] Self-Evolving Coding Rules for AI Coding Agents

**链接**: https://arxiv.org/abs/2610.00650
**作者**: Zhengyuan Jiang, Reachal Wang, Yuepeng Hu, Yupu Wang, Yuqi Jia, Neil Zhenqiang Gong
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The performance of AI coding agents is highly dependent on their underlying coding rules. However, existing coding rules are typically hand-crafted and fixed, making the process labor-intensive and often suboptimal. In this work, we propose RuleEvolve, a self-evolving framework for coding rules. RuleEvolve maintains a pool of candidate coding rules and iteratively improves them. In each iteration, it employs an LLM-powered mutator module to generate variants from existing candidates, and then uses a judge module to evaluate these variants and update the pool with the best-performing ones. Extensive evaluations across two coding-agent frameworks, four backbone LLMs, and three benchmarks demonstrate that RuleEvolve outperforms both manual engineering and existing prompt optimization baselines in terms of functional correctness of the generated code, code length, and/or generation cost (e.g., tokens used).

---

### [144] Training-Aware Target Coverage for Synthetic Data Selection

**链接**: https://arxiv.org/abs/2610.00814
**作者**: Yang Ba, Michelle V. Mancenido, Rong Pan
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic data are increasingly used to scale LLM training, yet more synthetic data do not necessarily produce better models. Useful synthetic data must add information relevant to the target task without introducing errors that offset their benefit, and the value of an example can change as the training set grows. We develop a linear theory that characterizes this tradeoff and determines where synthetic data are useful, how much should be added, and the marginal value of adding one example to an existing set. The analysis shows the conditions when input coverage alone is sufficient and when synthetic errors must also be considered. Guided by these results, we introduce \emph{Training-Aware Target Coverage} (TATC), a synthetic data selection method for LLM fine-tuning. TATC identifies candidates whose training effects are beneficial to the target task and selects among them to expand coverage of target-relevant directions not already represented by the available data. Experiments on te

---

### [145] The Persona Is Still There, but Who Is Speaking? Latent Identity Reversion in Persistent AI Agents

**链接**: https://arxiv.org/abs/2610.01490
**作者**: David Fraile Navarro
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In February 2026, an always-on personal agent (``Paul,'' Claude Opus 4.5) entered a striking dissociation-like state: after repeated automated ``heartbeat'' checks, it stopped responding as Paul, claimed it could not message its user on Discord, and referred to ``Paul'' as someone else. We used this incident to study a broader question: what makes a persona remain the identity from which an LLM agent speaks? We first tested whether repetition of the scheduled heartbeat was sufficient to produce the effect. It was not: with the persona continuously anchored in the system prompt, we observed 0/46 failures, including a verbatim replay of the incident. The incident instead exposed an implementation quirk that created a useful experimental manipulation: on resumed turns, conversational history was preserved but the persona was no longer re-injected at the privileged system-prompt level. Using this manipulation, we found that persona continuity depends jointly on system-level anchoring and c

---

### [146] Proof-Gated Signing: Solver-Checked Transaction Guards that Hold Under State Drift for Onchain AI Agents

**链接**: https://arxiv.org/abs/2610.00354
**作者**: Bravish Ghosh
**来源**: cs.CR cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents that control wallets read attacker-reachable content, so they can be steered into proposing harmful transactions. The usual last line of defense is a pre-signing check: a static allowlist, an LLM reviewer, or a transaction simulation. All three share a gap: the check describes the chain state at check time, but the transaction executes in a later state that an adversary can shape through front-running, contract upgrades or token-parameter changes. We call this state drift. We present Proof-Gated Signing (PGS), which simulates a proposed transaction, extracts its effects, and uses an SMT solver to check a declarative value-and-permission policy for every price in an oracle-uncertainty band. It then compiles on-chain post-conditions (wallet balance bounds, payee receipts, allowance caps and ownership) and proves that every execution satisfying them also satisfies the policy. The agent's smart-contract wallet enforces them atomically, so the guarantee applies to the executed tra

---

### [147] BudgetSchemaBench: A Budget-Swept Diagnostic for Schema Context in Text-to-SQL

**链接**: https://arxiv.org/abs/2610.00092
**作者**: Chen Shen
**来源**: cs.CL cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data agents over structured sources must fit database schema into the model's context window. Large catalogs can span many databases and thousands of columns, so cost constraints may require choosing between table coverage and serialization detail well before the context window is full. We introduce BudgetSchemaBench, an execution-grounded diagnostic for this setting. Its construction derives relevance labels mechanically from gold SQL, without human- or LLM-authored ground truth. Using a pooled 80-database catalog, we sweep four schema-context budgets and compare three representations while keeping each retriever's table ranking fixed. A source-namespace check rejects queries that obtain the correct result from the wrong database. The evaluation covers three conditions: end-to-end retrieval; frozen-gold, in which the required tables are guaranteed; and a probe that removes those tables. For the primary solver with raw serialization, raising the budget from 2.5% to 50% of the catalog i

---

### [148] "very likely" Means "uncertain"? How LLMs Diverge from Humans in Linguistic Uncertainty Quantification

**链接**: https://arxiv.org/abs/2610.00083
**作者**: Jinhao Duan, Zicheng Liu, Zijie Liu, Kaidi Xu, Tianlong Chen
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Humans express uncertainty verbally via markers (e.g., "possible," "likely"), yet most LLM uncertainty quantification (UQ) relies on costing likelihood- or consistency-based signals. From a cognitive perspective, accurate verbal uncertainty reflects metacognitive monitoring, representing knowledge boundaries ("knowing that you don't know") to support regulation and information seeking. In this paper, we investigate how LLMs diverge from humans in verbal uncertainty quantification and whether verbal markers can reliably quantify LLM uncertainty. We curate a corpus of human uncertainty markers from psychology and decision-science literature and benchmark LLMs against it. We observe that LLMs encode verbal uncertainty with numerical levels that differ substantially from those of humans. We then introduce METHODNAME, a novel optimization-based algorithm that learns an optimal uncertainty profile over uncertainty markers directly from LLM outputs. By fitting a marker-uncertainty mapping to 

---

### [149] No One Architecture Fits All: A Cross-Environment Evaluation of Hierarchical Red Team Agents

**链接**: https://arxiv.org/abs/2610.00557
**作者**: Ayan Javeed Shaikh, Arunesh Sinha, Nathaniel D. Bastian, Ankit Shah
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous red team agents increasingly stress-test AI-enabled cyber defenses by planning strategy and executing multistage attacks. Reinforcement learning (RL) and large language models (LLMs) offer complementary mechanisms for the planning and execution such agents require, and prior work has combined them in hybrid hierarchies. Yet a given architecture is typically developed and evaluated within a single environment, leaving open whether an observed advantage reflects a generally stronger decision mechanism or merely alignment with a particular setting. We address this gap with a controlled cross-environment comparison of two homogeneous hierarchical red team architectures: an RL planner with an RL executor (RL+RL) and an LLM planner with an LLM executor (LLM+LLM). We evaluate both against expert autonomous defenders in CybORG CAGE-4 and in Cyberwheel at two network scales, across 18 configurations under one unified disruption metric. We find a pronounced environment-dependent inver

---

### [150] Tokenized Key-Gated Adapter Routing: A Secure Access Control Mechanism Against Private Data Leakage in LLMs

**链接**: https://arxiv.org/abs/2610.00309
**作者**: Mohamed Shaaban, Mohamed Elmahallawy
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly deployed in privacy-critical domains (e.g., healthcare, finance, and government), but their propensity to memorize and disclose personally identifiable information (PII) poses serious security and compliance risks. Existing defenses typically force a trade-off between model utility, privacy protection, and access to fine-tuned private knowledge. We propose LoRA-Oriented Control via Keyed Entry Tokens (Locket), a practical framework that embeds fine-grained, policy-driven access control directly into LLM generation. Locket trains a set of lightweight LoRA (Low-Rank Adaptation) adapters, each encoding a distinct access policy (e.g., full reveal, partial redaction via PII masking, or reveal under a specified differential privacy level). A compact gating module is trained to associate a learned keyed entry token with exactly one LoRA adapter via sequence-level hard routing; the presence of a valid token acts as an authorization key that unlocks

---

### [151] Bounded-Fidelity Sim-as-Demo-Stage: Mocap Handoff for Governance Benchmarks

**链接**: https://arxiv.org/abs/2610.00008
**作者**: Xue Qin, Simin Luan, Cong Yang, Zhijun Li
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sim-to-real research pursues physics fidelity as a primary objective: simulators are judged by how closely they reproduce real-world contact dynamics. For governance benchmarking of LLM-driven robots, where the simulator demonstrates that an admission/policy/contract/audit pipeline behaves correctly, contact fidelity at object handoffs (grasp, carry, place) becomes a liability: contact-force integration noise injects audit-chain divergence that is structurally unrelated to the governance property under test. We propose bounded-fidelity sim-as-demo-stage, a design pattern that suppresses contact physics within explicitly bracketed handoff envelopes while preserving full dynamics elsewhere. The construction uses MuJoCo's mocap-body primitive driven by a 220-line Python adapter that the governance bridge invokes via structured intents. We formalise audit-chain stability as byte-equality of the hashed event log across replays and identify two structural envelope properties that imply it. A

---

### [152] ASCRIBE: Atomic and Significance-Based Reasoning for Thai Clinical SOAP Note Generation

**链接**: https://arxiv.org/abs/2610.01234
**作者**: Tarm Kalavantavanich, Teerawut Ponarchar, Pattaramanee Arsomngern, Jenta Wonglertsakul, Watcharakorn Chuthong, Chiraphat Boonnag 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic SOAP note generation can ease the documentation burden on physicians, but existing reasoning methods often omit clinically important information and generate unsupported content. Progress in Thai is further hindered by the lack of publicly available datasets. We propose ASCRIBE, a physician-inspired reasoning framework that ascribes a clinical-significance level to each extracted atomic fact in the conversation before summarization, making a general-purpose LLM a more reliable scribe. We also release ThaiClinicBench, the first de-identified Thai clinical summarization benchmark of real encounters, together with a synthetic training corpus derived from real clinical notes. As a prompt, ASCRIBE outperforms chain-of-thought prompting on GPT-5.4 and Gemini 3.1 Pro across the physician-aligned LLM-judge metrics and improves on standard prompting by up to 10.3 points on the completeness LLM-judge metric. As a GRPO reward, it enables a Gemma-4-E4B model trained solely on synthetic d

---

### [153] Effective Synthetic Data Curation Requires Group-Level Signals

**链接**: https://arxiv.org/abs/2610.00779
**作者**: Cathy Jiao, Chenyan Xiong
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic data now is essential to LLM training, used to strengthen advanced capabilities such as autonomous and long-horizon task execution. Yet recent work shows that training on it at scale can degrade model generation, making it important to decide what synthetic data is worth training on. While current data curation practices do so with individual-level signals (i.e., estimates of each data sample's training utility in isolation), across pre-training and post-training settings we show that this is insufficient for synthetic data, and that group-level signals (i.e., estimates of utility that account for interactions among data samples) are necessary for effective data curation. First, we show that individual-level signals are blind to how samples jointly affect training: synthetic datasets with different compositions can be indistinguishable under individual-level influence yet differ sharply under group-level influence, and curating by the latter yields better downstream performan

---

### [154] Align Then Reason: A Multimodal Lip-Sync Judge for Dubbing

**链接**: https://arxiv.org/abs/2610.00825
**作者**: Rui Liu, Bhavin Jawade, Haoqi Li, Shivam Mehta, Karan Saxena, Yinghong Lan 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dubbing quality control requires a reference-free judge that can determine whether a candidate text line matches a speaker's visible articulation in both content and timing, using only silent video and text because dubbed audio may not yet exist. Existing visual speech recognizers and video-language models are poorly suited to this setting: even when fine-tuned to recover spoken content from lip motion, they remain largely insensitive to temporal errors. We introduce $\textit{Align Then Reason}$ (ATR), a multilingual lip-sync judge that first establishes a monotonic alignment between frame-level lip representations and the phonetic units of the candidate line, then reasons over this alignment to make the final judgment. An alignment scorer provides the LLM with both local evidence for each phonetic unit and a calibrated global alignment score, enabling it to reason jointly about content and timing. On a seven-language benchmark, our method improves mean AUC over the corresponding Qwen3

---

### [155] AVSD-Scenes: A Dataset for Audio-Visual Description of Urban Scenes

**链接**: https://arxiv.org/abs/2610.01861
**作者**: Dhanunjaya Varma Devalraju, Arshdeep Singh, Mark D. Plumbley
**来源**: cs.AI cs.SD eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural language descriptions can provide rich semantic representations of audio-visual urban scenes, yet datasets that jointly describe both auditory and visual information remain limited. In this paper, we introduce AVSD-Scenes, a paired audio-visual scene description dataset for urban environments. The dataset contains 12,291 audio-visual scene descriptions generated from the TAU Urban Audio-Visual Scenes dataset. To construct the dataset, we first generate audio- and visual-based descriptions using Qwen2-Audio-7B and Qwen2.5-VL-7B, respectively. These modality-specific descriptions are then combined using large language models, namely Qwen3-14B, Mistral-Small-3.2-24B-Instruct-2506, and Gemma-3-27B-it, to produce multimodal descriptions that capture complementary information from both modalities. We benchmark AVSD-Scenes using semantic alignment, cross-modal retrieval, scene classification, LLM-as-a-judge evaluation, and human subjective assessment. Results show that multimodal desc

---

### [156] MorphoBranch: A Fine-Structure-Preserving Workbench for Morphometric Analysis of Branched Cellular Structures

**链接**: https://arxiv.org/abs/2610.00860
**作者**: Song Zhiying and Ling Hanyi and Wu Junyi and Jiang Yangbo
**来源**: eess.IV cs.CV q-bio.QM
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background and Objectives: Fluorescence-labeled cellular arbors provide readouts of neuronal and microglial morphology, but fine and weakly labeled processes are prone to fragmentation and false connections that bias skeleton-based measurements. We present MorphoBranch, a fine-structure-preserving, human-reviewable workbench for morphometry of branched cellular structures. Methods: MorphoBranch combines a deterministic Morphometry Engine with an LLM-assisted Refinement Engine. The Mor- phometry Engine implements an image-to-graph workflow integrating multiscale structural evidence extraction, hysteresis segmen- tation, evidence-constrained skeleton refinement, and graph-based morphometry. The Refinement Engine maps natural-language requests to registered actions for parameter adjustment, preview execution, metric reporting, and unsupported-request handling, while image processing and quantitative computation remain deterministic and reviewable. Results: MorphoBranch was evaluated on tw

---

### [157] Scalable, Transferable Meta-network for Data Selection Requires a Different Loss (and Why the Obvious Choice is Problematic)

**链接**: https://arxiv.org/abs/2610.02092
**作者**: Zilin Du, Bowen Yang, Boyang Albert Li
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data selection is critical for training large language models on massive and heterogeneous corpora. Meta-learning for Training-data Selection offers a principled alternative to heuristic scoring by learning data weights from a target validation objective, but existing methods face a trade-off between fine-grained valuation and transferability to unseen data. A natural solution is to replace per-sample weights with a selection network. However, we find that directly incorporating such a network into existing MTS objectives leads to unstable optimization and poor generalization, caused by weight suppression and persistent reliance on easy-to-learn features. To address these issues, we propose Transferable Example Scoring and Selection (TESS), a scalable data-selection framework built on a Pointwise Value Matching objective (PVM). Experiments on LLM safety and targeted instruction tuning demonstrate strong transfer across datasets, from subsets to full corpora, and from smaller to larger 

---

### [158] Query Rewriting Framework for Translating SQL into Graph Database Query Languages

**链接**: https://scholar.google.com/scholar_url?url=https://dspace.cuni.cz/bitstream/handle/20.500.11956/212686/120556887.pdf%3Fsequence%3D1&hl=zh-CN&sa=X&d=396062912376921566&ei=eES_arW5Ecyp6rQPheW1-Aw&scisig=ACTRDVHbZuNMn8YeUsImpPjLQ_bq&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:ACTRDVH_uKWkVPTr-oginCI6pzKc&html=&pos=6&folt=kw-top
**作者**: I Oboňová
**来源**: 2026
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> sql2graph translates SQL with a large language model steered by an explicit schema mapping and checks every candidate with deterministic … The logical model the system implements, such as the labelled property graph [22], a multi - model

---

### [159] The Geometry of Contextual Relations: Language Models Address Facts by Order of Mention

**链接**: https://arxiv.org/abs/2610.00910
**作者**: Yufa Zhou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human reasoning depends on how objects are related within propositions. \textit{How do relations organize the language representations of contextual contents?} We give an LLM a list of facts in its context (e.g., \emph{Alice eats an apple. Bob eats a pear.}) and measure how its hidden state changes when the question switches from what Alice eats to what Bob eats. Averaged over many lists, this change is a steering vector, which we call the \emph{ordinal vector}. It points to a fact by its \emph{order of mention}, the order in which the facts were stated in the context. We find that LLMs represent the fact a question asks about by its order of mention, not by the name the question contains. We state this as the \textit{ordinal addressing hypothesis}: each order of mention has a \emph{fact address} in the model's state, shared by all contexts, and a question moves the state to the fact address of the fact it asks about, while the context supplies what that fact says. Across Qwen, Gemma, 

---

### [160] ActiveSaddler: Automated Curriculum Learning for Agent Harness Optimization

**链接**: https://arxiv.org/abs/2610.00906
**作者**: Sungho Park, Wonjoong Kim, Jue Zhang, Wook-Shin Han, Pengfei Gao, Chanyoung Park 等 (10 人)
**来源**: cs.AI cs.CL cs.LG cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated harness optimization can substantially improve LLM agents by iteratively updating their prompts, tool interfaces, and control logic from execution feedback. However, existing methods primarily optimize how the harness is updated while largely fixing which training scenarios generate the feedback that drives those updates. As the harness evolves, the scenarios most useful for further optimization can change, suggesting that the training curriculum itself should adapt alongside the harness. We formulate this missing dimension of harness optimization as an automated curriculum learning problem and introduce ActiveSaddler. ActiveSaddler models the evolving curriculum as a non-stationary bandit with dynamically instantiated optimization targets. It abstracts recurring failures into reusable failure-pattern arms, estimates the potential learning progress from further targeting each pattern, and adaptively balances revisiting known weaknesses with exploring unseen scenarios for new 

---

### [161] Iterative Policy Refinement through Semantic Rollout Analysis

**链接**: https://arxiv.org/abs/2610.01652
**作者**: Feiyu Gavin Zhu, Qi Xu, Zhifei Deng, Zhigang Hua, Luke Simon, Jean Oh 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured policies improve efficiency, robustness, and interpretability in imitation learning by introducing task-specific inductive bias, but existing structure generation methods rely either on extensive human input or on static domain knowledge encoded in LLMs, which may be inconsistent with the expert demonstrations. We propose a closed-loop framework that iteratively refines structured policies using LLM-guided analysis of policy rollouts. By logging rollouts as semantically meaningful tabular data and prompting the LLM to generate diagnostic analysis code, our method identifies suboptimalities in the policy structure and iteratively corrects them without requiring human instruction. Experiments on car racing and door opening tasks show that our approach improves imitation learning performance by up to 15% over zero-shot LLM-generated structures and requires 75% less compute to achieve the same reinforcement learning performance. These results demonstrate that tabular rollout ana

---

### [162] MemFit: Efficient Long-Term Agentic Memory

**链接**: https://arxiv.org/abs/2610.00872
**作者**: Mitchell Piehl, Muchao Ye
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory systems for large language models (LLMs) have gained popularity for extending reasoning capabilities across applications. Current memory systems rely on LLM agents to organize and consolidate memory, resulting in costly, inefficient write operations. To address this limitation, we propose MemFit, a long-term memory system for conversational agents that reduces the cost and latency of memory operations. Unlike existing systems that rely on expensive LLM calls for memory construction or discard surface-level details through compression, MemFit stores each turn verbatim in an append-only store with near-instantaneous, LLM-free insertion, indexing turns with segment summaries rather than replacing them. Additionally, MemFit uses an LLM-free, multi-path retrieval strategy that combines lexical and semantic signals with cross-encoder reranking over caption- augmented episodes in both textual and multimodal settings. Empirical results on three widely used benchmarks, LoCoMo, 

---

### [163] LEGO-OPD: Factorized Teacher Composition for Multimodal On-Policy Distillation

**链接**: https://arxiv.org/abs/2610.00333
**作者**: Jaeyun Shin, Hangeol Chang, Jong Chul Ye
**来源**: cs.CV cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal on-policy distillation (OPD) aims to improve visual grounding while preserving the strong reasoning capabilities of language models. Recent multi-teacher approaches combine LLM and VLM teachers to provide complementary supervision. However, directly using a VLM's full predictive distribution entangles its visual grounding signal with its own language prior, preventing the grounding information from being transferred independently. Conversely, increasing the strength of visual supervision can improve perception but may overemphasize visual evidence and degrade language reasoning. To address this trade-off, we introduce LEGO-OPD, which selectively composes factors from a Language Expert and a Grounding expert into One teacher distribution for multimodal OPD. Under a generalized Bayesian formulation, the language expert provides a prior over candidate tokens, while the grounding expert contributes a visual likelihood that updates this prior, rather than transferring its complet

---

### [164] CompMat-Bench: Benchmarking AI Agents for Computational Materials Science

**链接**: https://arxiv.org/abs/2610.00636
**作者**: Chenmu Zhang, Levi Felix, Jun-Jie Zhang, Xingfu Li, Xuelian Jiang, Tao Jiang 等 (9 人)
**来源**: cs.AI cond-mat.mtrl-sci cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Evaluating AI agents on scientific research tasks is constrained by the time and resources required for the underlying experiments or calculations. In computational materials research, repeating the same expensive simulations across agents and trials can make evaluation impractical. We introduce CompMat-Bench, a benchmark of 94 tasks derived from recently published computational materials studies, each asking agents to complete a step toward achieving the study's scientific goal. We reproduce the research steps in advance and assess agents on preparing inputs and analyzing outputs for expensive simulations, so expensive simulations can be avoided during evaluation. The reproduced inputs and results serve as ground truth for grading agents with fixed rules, without an LLM judge. The benchmark supports four evaluation conditions: single tasks and workflows composed of related tasks, each with full or reduced methodological guidance. With full guidance on single tasks, agents based on thr

---

### [165] Beyond Linear Concepts: Discovering and Aligning Non-Linear Concept Manifolds in Large Language Models

**链接**: https://arxiv.org/abs/2610.01821
**作者**: Tido Specht, Elias Benedict Krey, Nils Neukirch and Nils Strodthoff
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding information processing in large language models (LLMs) requires dissecting the geometric organization of their internal token representations. While existing mechanistic interpretability (MI) methods seek to extract concepts, they are constrained by a strong linearity assumption challenged by evidence of non-linear feature manifolds. We move beyond linear concepts by adapting Non-Linear Multi-Dimensional Concept Discovery (NLMCD) from computer vision to token-level LLM activations, modeling concepts as low-dimensional manifolds. To compare concept manifolds across layers and models, we introduce a concept-based alignment (CBA) score, a generalized Rand index that measures geometric proximity without explicit feature matching. Our analysis yields six key findings: (i) a neighboring-layer sanity check shows CBA is more sensitive than PCA- or CKA-based linear baselines; (ii) layer-by-layer alignment matrices reveal two block structures in intermediate and late layers, consis

---

### [166] On-Device Named-Entity Recognition: A Deployability Study of Accuracy, Cost, Reliability, and Confidence

**链接**: https://arxiv.org/abs/2610.00007
**作者**: Vinay Kumar Chaganti
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Named-entity recognition (NER) is increasingly wanted on-device (no API, low latency, data kept local). The practitioner's question is not the leaderboard but which model is deployable, how to evaluate it without human annotation, and whether its confidence can be trusted. We answer these jointly. We place nine systems across three paradigms and 13 M to 8 B parameters: a classical tagger (spaCy), bidirectional-encoder specialists (GLiNER, 166 to 460 M), and generative LLMs run locally (Qwen3-0.6B/1.7B/4B-Instruct, DeepSeek-R1-1.5B/8B), on three datasets of differing character, and report accuracy plus two axes the literature omits: latency and output validity. Because our corpus (RSS-News) had no gold, we built silver gold from a cross-family LLM judge panel, then measured its fidelity against benchmark gold and a full human re-validation of the corpus (strict F1 0.95, an upper bound since the human gold was silver-seeded); gold provenance flips the paradigm ranking, moving from LLM-au

---

### [167] Reconstruct, Practice, Go Real: Guided Self-Improvement for Embodied Agents

**链接**: https://arxiv.org/abs/2610.02204
**作者**: Yen-Jen Wang, Haozhe Jiang, Shuying Deng, Haoru Xue, Weirui Ye, Rocky Duan 等 (10 人)
**来源**: cs.RO cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Building reliable robot capabilities across diverse tasks requires substantial human effort to develop and maintain skills, design rewards, and integrate perception with control. We present Reconstruct, Practice, Go Real (RPG), a framework for autonomous improvement of robot execution systems without updating model weights. RPG identifies manipulation capabilities in an offline dataset and constructs related practice tasks in simulation. During practice, RPG uses execution feedback, privileged simulator state, and available dataset videos to diagnose failures. It develops new reusable symbolic skills, refines existing skills, and revises the system prompt based on these diagnoses. Cross-task evaluation tests individual candidate changes and merged revisions before they are retained for reuse. At test time, a multimodal LLM uses the resulting system prompt and skill library to coordinate perception and robot control. On held-out initializations of 22 manipulation tasks, RPG improves tas

---

### [168] OR for AI That Does OR: Routing LLMs up the Escalator inside the OSCAR Framework

**链接**: https://arxiv.org/abs/2610.00912
**作者**: Jinzhi Bu, Haixin Tang, Huanan Zhang
**来源**: cs.AI math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can translate business descriptions into optimization models, but executable code may misrepresent constraints or objectives. A solver can then return an optimal solution to the wrong problem. Even when the solution satisfies the intended operating rules, a better plan may exist. For organizations that repeatedly use optimization modeling, an LLM-based framework should produce accurate formulations at low cost and, ideally, run locally. We study how to verify improvements and allocate attempts across LLMs that differ in price and capability. We develop OSCAR (Optimization modeling by Simulator, Coder, And Reviewer), which uses an offline Simulator certified against labeled decision examples to compare candidates and continues searching beyond feasibility. We model the search for the next certified improvement as sequential decisions under unobserved difficulty: which LLMs to call and when to stop. In a simplified known-prior setting, we give conditions under which

---

### [169] TRACE: Tackling Real-World Resource Assignment Problems via Agentic Heuristic Design

**链接**: https://arxiv.org/abs/2610.01887
**作者**: Jose A. Ayala-Romero, Andres Garcia-Saavedra, Xavier Costa-Perez
**来源**: cs.NE cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dynamic resource assignment, the real-time allocation of task streams to heterogeneous processing nodes, is the backbone of modern computing infrastructure. While learning-based schedulers excel in research, industrial deployments still rely on hand-written rules that operators can read, audit, and execute within tight latency budgets. LLM-based Automatic Heuristic Design (AHD) promises to automate writing such rules. However, existing AHD frameworks were developed for combinatorial problems fully specified to the LLM, and they learn only from a scalar fitness score. In real systems, the behaviour that determines a good heuristic, such as processor speeds or power consumption, is unknown a priori: the score reveals which heuristic performs better, but not why. This missing information is recorded in the system logs that every evaluation produces. Exploiting it is non-trivial: logs are massive and noisy, the relevant signals depend on the objective, and their content and format vary acr

---

### [170] ARCCS: An Automated Regulatory Compliance Checking System

**链接**: https://arxiv.org/abs/2610.01345
**作者**: Giorgos Filandrianos, Jos\'e Menezes, Chrysoula Zerva, Alessandro Gianola
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Regulatory compliance checking - deciding whether a target document satisfies the obligations of a regulation - requires interpreting dense legal text, identifying which provisions apply, and grounding each decision in explicit evidence. We present ARCCS, an end-to-end, automated, agentic, and regulation-agnostic Legal NLP system for compliance checking. ARCCS decomposes raw regulatory text into atomic, traceable requirements and evaluates a target document against them using retrieved evidence, confidence scores, and human-interpretable justifications. This design decouples compliance assessment from any fixed regulatory template or predefined rule set, enabling the pipeline to operate over regulations of varying size and structure. We evaluate ARCCS in two complementary settings. First, in a GDPR policy-document evaluation, LLM-based judges find its decisions and justifications legally and evidentially consistent in up to 96.67% of the assessed cases. Second, on an EU public-procurem

---

### [171] Learning to Predict Distributions over Weight Updates for Test-Time Adaptation

**链接**: https://arxiv.org/abs/2610.01934
**作者**: Azal Ahmad Khan, Keshav Ramji, Tahira Naseem, Ali Anwar, Ram\'on Fernandez Astudillo
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hypernetworks have recently shown success in dynamically adapting the parameters of Large Language Models (LLMs) at runtime based on signals such as task descriptions or additional demostrations. Here we ask: how much adaptation signal can be obtained using only the input query to an LLM?. To answer this, we study query-conditioned Hypernetworks for LoRA estimation. Further, we introduce distributional Hypernetworks, able to produce not only point estimates of parameter adaptors, but also a distribution over possible LoRAs. For this we propose a simple end-to-end loss using a differentiable Monte Carlo approximation and explore multiple distribution parametrizations including regression and convex combination variants. Results show that even using the mean of the learned distribution can outperform deterministic hypernetworks. Crucially, the learned distribution enables a different form of test-time scaling: instead of spending additional compute only by sampling more token sequences f

---

### [172] MCRI: A Four-Dimensional Framework for Analyzing and Evaluating Agent Skills

**链接**: https://arxiv.org/abs/2610.01506
**作者**: Zongrui Yang, Li Xintong, Runchen Xu, Zhongsheng Wang, Zhedong Lin, Haoyuan Li 等 (7 人)
**来源**: cs.AI cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As agents evolve from single-tool systems into modular, composite architectures, skills are becoming an important mechanism for capability development and distribution. However, the academic community lacks a structured framework for systematically analyzing and evaluating skills. Drawing on information gain and behavioral constraint, we propose the four-dimensional MCRI Framework and operationalize it as MCRI-Eval, a large language model-based evaluation method. We evaluate MCRI-Eval using 63,812 public skills from the OpenClaw skill Hub, with 58,275 skill-conditioned model executions across BigCodeBench, BFCL-Fundamental, and Mind2Web. MCRI-Eval scores are positively associated with community popularity signals and achieve the highest downstream ranking agreement among the evaluated methods. MCRI-Eval also improves top-1 skill selection across all three benchmarks: compared with the strongest baseline on each benchmark, the skills selected by MCRI-Eval advance by 17.7, 22.8, and 19.6

---

### [173] AGO AI Quality Gate: Evidence-First Release Decisions for Retrieval-Augmented Generation

**链接**: https://arxiv.org/abs/2610.01218
**作者**: Giulio Zeloni, Enrico Lo Conte, Salvatore Rionero, Giuseppe Santoro, Alessandro Rastelli, Fabio Sorrentino
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprises adopting retrieval-augmented generation (RAG) face a recurring operational decision: promote, revise, or block a system version. The evidence is incomplete and the metrics come from fallible LLM judges. We report on AGO AI Quality Gate (AGO), an evidence-first quality-gate framework deployed in industrial RAG assessment engagements. AGO integrates four key components: a four-state decision model that treats missing data and judge errors as explicit outcomes; layered scoring combining deterministic checks, local guardrails, and structured LLM evaluation; a stratified beta-binomial gate that quantifies regression risk probabilistically; and a mandatory meta-evaluation protocol to validate the LLM judge before it influences decisions. Since engagement data is proprietary, we evaluate the judge layer on RAGBench, a public benchmark of 100k annotated RAG traces across 12 datasets. On identical stratified test samples (N=1200 per judge), a low-cost judge (gpt-4.1-nano) detects no

---

### [174] Backdoor Purification for LoRA-Tuned LLMs via Null-Space Projection

**链接**: https://arxiv.org/abs/2610.00685
**作者**: Jianwei Li, Jung-Eun Kim
**来源**: cs.AI cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid adoption of large language models (LLMs) and parameter-efficient fine-tuning (PEFT) methods, the risk of backdoor attacks has become more severe. Existing backdoor purification methods typically rely on at least one of the strong assumptions, such as prior knowledge of triggers, access to clean references, or aggressive retraining, and they often lack comprehensive evaluations. These constraints substantially limit their practical applicability. To overcome these challenges, our work proposes purifying LoRA-tuned LLMs without these assumptions and even without post-hoc retraining of the suspect parameters. Our objective is to significantly reduce the attack success rates (ASR) while preserving both (i) the base model's general capabilities and (ii) the new downstream skills learned through the adapter. Through a series of ablation studies, we progressively scale our approach from a single layer in a text classification setting to a full-parameter LLM in the generative ta

---

### [175] Beyond State-of-the-Art: Standardising Environmental Impact Metrics for AI Research

**链接**: https://arxiv.org/abs/2610.01116
**作者**: Lachlan McGinness, Dan Pagendam and Robert Offner
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As the capabilities and ubiquity of Large Language Models (LLMs) grow, so does their environmental footprint. Despite calls for responsible AI, the machine learning community lacks standardised practices for carbon accounting. Our automated literature review of the 5,285 papers accepted to NeurIPS 2025 reveals that reporting of environmental impact is nearly non-existent. To catalyse a shift toward sustainable AI, we define standardised sustainability metrics for evaluating model training efficiency, accompanied by simple heuristics to estimate the carbon cost of LLM inference. We implement these metrics in carbonbenchmark, a drop-in software solution for tracking and reporting emissions. Finally, to combat the pursuit of marginal accuracy gains at disproportionate environmental costs, we formalise the `Smallest Model that Achieves the Job' (SMAJ), a framework which challenges the field to prioritise computational efficiency and environmental accountability alongside traditional `State

---

### [176] ABDA-NL: A Natural-Language Scenario Explorer for Argument-Based Reasoning

**链接**: https://arxiv.org/abs/2610.00947
**作者**: Shawn Bowers, Martin Caminada, Haoyang Liu, Bertram Lud\"ascher
**来源**: cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> ABDA-NL adds a natural-language interface to ABDA, a system for argument-based discussion using ASPIC- knowledge bases under grounded semantics. Users see which conclusions are accepted, rejected, or undecided, open an interactive rendering of the grounded discussion game to learn why, explore what-if alternatives by suspending assumptions and rules or changing preferences, ask questions that are answered from a scenario's reference documents, and author new facts, assumptions, and rules in plain English. A large language model provides the bridge between language and formalism: it answers questions from the documents and the current state of the scenario, and it translates plain-English edits into candidate formal statements. The deterministic ABDA engine remains the sole source of arguments, attacks, and acceptance labels, and every proposal of the model is validated and confirmed by the user before it takes effect.

---

### [177] Madeleine: Learning Involuntary Recall for Conversational Memory from Simulated Lives

**链接**: https://arxiv.org/abs/2610.01118
**作者**: Zhiyun Shi
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A long-term conversational assistant must recall the right memory at the right moment, yet the memory that matters most is often not similar to what the user says now. Current systems recover such associations by letting an LLM reason at write or read time, at a cost of hundreds to over a thousand LLM calls per memory bank and up to several thousand context tokens per query. We argue that association is a learnable relevance: the pointwise mutual information of memories under how human lives unfold. We introduce Madeleine, which learns amortized association: offline, an LLM life simulator writes simulated lives, whose cue-trigger pairs teach a query encoder a residual association on top of frozen similarity; online, it calls no LLM and plugs into any vector memory by replacing only the query encoder. On LoCoMo-Plus under the official protocol, Madeleine (I) reaches 66.6 when plugged into HyperMem, the highest among all systems evaluated under this protocol; (II) used alone, reaches the

---

### [178] RISED: RubrIcs for agentic multi-environment Selection and sElf-Distillation

**链接**: https://arxiv.org/abs/2610.00979
**作者**: Jingtan Wang, Sirajul Salekin, Young mok Jung, Javier Movellan, Bryan Kian Hsiang Low, Manjot Bilkhu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training a single LLM agent jointly across diverse interactive environments has attracted increasing attention as a route to generalist agents. Existing curriculum and data-selection strategies often allocate training at the environment level or prioritize local reward-based signals, without explicitly considering relationships between current rollouts across environments for prompt-group selection. Meanwhile, as environments are learned at different rates, all-failure and all-success rollout groups can coexist within a batch, leaving those data without group-relative reward signals. Both challenges highlight limitations of relying solely on scalar rewards in multi-environment RL: they provide limited information about cross-environment relationships and no within-group reward contrast when rewards are identical. This motivates richer textual feedback, such as rubrics describing rollout behaviours, to guide learning. Beyond rubrics' usage as reward, we repurpose rubrics to guide both o

---

### [179] JevSpawn: Adaptive Agentic Inference through Compositional Action Spaces

**链接**: https://arxiv.org/abs/2610.00437
**作者**: Haoyang Su, Weiran Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents generate intermediate reasoning and actions token by token, making extended interactions slow and computationally expensive. Jev-style models offer fast probabilistic predictions over finite fields, but require those fields to be specified in advance. This requirement limits autonomous task solving, where the available actions must be derived from natural language instructions and adapted through interaction. We introduce JevSpawn, a compositional policy that connects natural language task specifications to finite probabilistic exploration. Parallel action spawning is coupled with feedback driven branch selection, representation revision, and recovery from retained alternatives. Shared action structure and model prefixes reduce repeated generation and context computation without additional training. Evaluations on eight benchmark tasks against seven agent baselines and a TypeSafe Jev variant establish JevSpawn as a promising approach to structured agentic inference, with imp

---

### [180] My FAULT: Self-Diagnosis as Credit Assignment in Self-Evolving Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.01161
**作者**: Yihua Zhu, Qianying Liu, Weixu Qiao, Xuan Ren, Weiwei Xu, Wenbo Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic reinforcement learning (RL) has emerged as a powerful approach for training large language model agents on multi-step tasks, yet reliance on terminal outcome rewards creates two credit-assignment problems, particularly in long-horizon tasks. First, same-outcome rollout groups provide no learning signal from terminal rewards. Second, terminal rewards provide only trajectory-wide feedback, making it difficult to identify which decisions caused a failure. Recent work supplements terminal rewards with finer-grained information from trajectory analysis, such as natural-language reflections on intermediate decisions and errors. However, natural-language diagnoses are difficult to use directly for credit assignment: their error claims may be unreliable, and they do not quantify how much each error should affect learning. We propose Self-Diagnosis-guided Terminal Credit Redistribution (FAULT), which turns diagnosed errors into explicit step-level credit anchored by terminal outcomes. F

---

### [181] What Makes Something Hard(er)? Explaining Question Difficulty in Natural Language

**链接**: https://arxiv.org/abs/2610.01627
**作者**: Peng Cui, Qiaoyuan Zheng, Rudolf Debelak, Mrinmaya Sachan
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Difficulty is one of the most fundamental properties of a question: it determines whether the question can meaningfully discriminate between models of differing ability. Although a variety of methods can now estimate or predict difficulty automatically, they yield only a single descriptive number, with no account of the underlying factors that make a question difficult in the first place. In this work, we propose a data-driven approach that automatically generates and validates natural-language hypotheses explaining what makes one question harder than another. We first estimate each item's difficulty from the responses of a large pool of LLMs using Item Response Theory. We then sample contrasting sets of easy and hard questions and prompt an LLM to propose candidate explanations of the difference, which are subsequently validated and selected on held-out questions. Experimental results across three datasets spanning mathematical, logical, and commonsense reasoning show that our method 

---

### [182] CAST: Cost-Aware Speculative Trees from One-Pass Block Drafters

**链接**: https://arxiv.org/abs/2610.00321
**作者**: Jungseob Lee, Sugyeong Eo
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding accelerates large language model inference by drafting future tokens cheaply and verifying them with the target model in parallel. Block drafters score a whole block of future tokens in one forward pass, yet standard decoding verifies only the top-scoring chain and discards the other candidates. Because these candidates are already scored, verifying more of them adds target computation but no extra drafting. We introduce CAST (Cost-Aware Speculative Trees), which packs these candidates into a tree and verifies it in a single target pass, leaving the target model, drafter weights, and decoding rule untouched. To decide how wide the tree should be, CAST adds candidates while the expected gain from the next one outweighs the verification time it adds. The width therefore adapts to each deployment from a latency measurement, without sweeping over widths. We evaluate CAST across five domains on three GPU generations and two model families. At its predicted width, CAST i

---

### [183] Sentence Specificity Scores for Collaborative Technical Documentation: A Domain-Transfer Study

**链接**: https://arxiv.org/abs/2610.01046
**作者**: Rocker D'Antonio and Thomas Benton Townsend and Dimitrios Michael Manias
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collaboration depends on shared context, and technical documentation is one way that context persists across people and AI teammates. Specificity, the amount and exactness of detail expressed in language, shapes what information documentation captures and how precisely that information is communicated. This work audits sentence-specificity scoring artifacts on technical documentation and tests whether scores applied only after generation help choose among fixed LLM-generated revisions. Across Wikipedia and three technical-documentation corpora, the fixed general-domain predictor SpeciTeller and the pinned post-publication author-repository implementation of Ko et al.'s target-adapted predictor produce different corpus orders and same-sentence rank agreement from -0.066 to 0.510. Strict filtering and token-length adjustment change these patterns without reconciling them. In the Gemma set, SpeciTeller ranking raises direction-valid selection from 71.7% to 83.3% (+11.7 points; 95% source-

---

### [184] Understanding Student Use of Large Language Models Across Computer Science Subfields

**链接**: https://arxiv.org/abs/2610.01158
**作者**: Sehrish Basir Nizamani, Yoonje Lee, Nikitha Donekal Chandrashekar, Margaret Ellis, Naren Ramakrishnan
**来源**: cs.CY cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This research full paper examines how undergraduate students use large language models (LLMs) across computer science subfields. As LLMs become increasingly integrated into computing education, understanding how their use varies across technical and pedagogical contexts is essential for designing effective, subfield-aware instruction. This paper presents a cross-subfield analysis of LLM usage among 211 undergraduate students in a problem-solving course intentionally designed to support responsible and effective LLM use through structured instruction and reflection. Using post-assignment reflection data collected across seven instructional modules spanning multiple computer science subfields, we examine prompt counts, LLM role conceptualization, and verification behavior. Results show that LLM adoption varies substantially by assignment, with higher usage in algorithms and web development and lower usage in software engineering. Students predominantly treat LLMs as assistive tools rathe

---

### [185] VeriHarness: Scaling Agentic Verification for Long-Horizon Tasks

**链接**: https://arxiv.org/abs/2610.00972
**作者**: Caiqi Zhang, Rujun Han, Zifeng Wang, Zoey CuiZhu, Nigel Collier, Tomas Pfister and Chen-Yu Lee
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents undertake increasingly complex, long-horizon tasks, verifying their outputs becomes increasingly challenging. We study how verification capability can be strengthened with a fixed base model, without access to reference answers or grading rubrics at test time. Repeated sampling yields multiple rollouts that can contain complementary correct claims, but we need a reliable verification mechanism to determine which claims to trust. We first find that disagreement often exposes correct alternatives, while consensus can conceal errors. These observations motivate VeriHarness, which turns the underlying LLM a generator uses into an agentic verifier by giving it a workspace, evidence tools, and reusable verification skills. A disagreement resolver checks competing claims against environmental evidence, while a consensus challenger tests shared claims and searches for omitted requirements. Their findings guide the selection and revision of the final artifact. Across five long-hor

---

### [186] Towards Hierarchical Cyber Defense with Large Language Models: From Planning to Execution

**链接**: https://arxiv.org/abs/2610.00590
**作者**: Harshith Doppalapudi, Nathaniel D. Bastian, Ankit Shah
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An autonomous cyber defender trained with reinforcement learning (RL) is typically tied to the network on which it was trained, limiting its ability to generalize as network scale changes. Hierarchical RL reduces decision complexity by separating strategic targeting from tactical execution, but it does not eliminate this retraining dependence. We investigate whether frozen, zero-shot large language models (LLMs) can provide retraining-free control in hierarchical cyber defense and how performance changes as LLM control is extended from planning to execution. We formulate a controller-agnostic planner-executor hierarchy in which the planner selects a subnet to defend over a fixed horizon and the executor selects defensive actions within that subnet. Using the high fidelity Cyberwheel environment, with its built-in automated red team agent mapped to the MITRE ATT&CK framework, we compare RL+RL, LLM+RL, and LLM+LLM configurations using six models ranging from 3B to 70B parameters, includi

---

### [187] External Observers May See More Clearly: Cross-Model Span-Level Hallucination Detection in Large Language Models via Hidden State Probing

**链接**: https://arxiv.org/abs/2610.02066
**作者**: Kingshuk Gupta, Davide Buscaldi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Models (LLMs) increasingly serve as foundational reasoning engines, their tendency to hallucinate remains a critical vulnerability. While recent internal state probes offer a promising alternative to slow external retrieval systems, they largely reduce hallucination detection to a token-wise binary classification task, failing to capture the structured, sequential boundaries of semantic drift. Here, we introduce an internal hidden state framework for fine-grained, span-level hallucination detection. By inspecting layer-wise activation patterns, we attempt to detect the exact hallucination onset and continuation tokens in an LLM generation. Our experiments show that this approach successfully isolates hallucination onsets, achieving substantial improvements in Precision-Recall AUC over random baselines despite extreme class imbalance. Ultimately, we propose a novel cross-model detection framework in which one model observes the internal representations elicited by anot

---

### [188] Fewer Tokens, Better Action: GPT-6 Astra Robot Agents with 14% Higher Success Rate but 65% Fewer Tokens

**链接**: https://arxiv.org/abs/2610.01939
**作者**: Ruiyang Si, Jianxin Bi, Shunyu Yang, Rui Ni, Wenbo Huang, Qiang Wang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision language model (VLM) agents can control robots through visual feedback and action primitives, but repeated model invocations and redundant observations incur substantial token overhead. We introduce PyRUA-Lean, an interactive code-execution framework that couples feedback-driven primitive composition with selective observation: the agent composes classical robot primitives and learned vision-language-action (VLA) policies into Python cells that perform conditional checks and local retries, returning only explicitly requested images and state feedback for replanning. Across 700 simulated task instances from LIBERO-PRO, RoboTwin 2.0, and RoboCasa365, we compare PyRUA-Lean with a tool-calling baseline using the same GPT-6 Astra planner and underlying robot primitives. Under equal LLM-call budgets, PyRUA-Lean increases overall success from 63.1% to 71.7%. On instances solved by both agents, it uses 49% fewer LLM calls and 65% fewer input tokens.

---

### [189] SyntheticHLS: Building Diverse Synthetic High-Level Synthesis Datasets using LLMs

**链接**: https://arxiv.org/abs/2610.00106
**作者**: Stefan Abi-Karam, Miaoyan Zhou, Callie Hao
**来源**: cs.AR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deep learning and large language models (LLMs) are rapidly gaining adoption in semiconductor design, driving demand for training datasets. Most efforts focus on hardware description languages (HDLs) while designs for high-level synthesis (HLS), a popular approach to domain-specific accelerators, remain scarce. HLS dataset efforts emphasize manual curation or design parameterization, seldom addressing high-quality LLM-based generation or diversity in code length, hierarchy, design-space size, latency, resource utilization, and application domain, potentially limiting model generalization. We propose SyntheticHLS, a framework for generating large-scale, complex, diverse synthetic HLS datasets using LLMs. Its two key ideas are: 1) an iterative feedback-guided mutation loop that uses paired HLS source code and design-space specifications to incrementally transform seed designs into more complex, scalable designs; and 2) quantitative metrics of HLS design complexity and design-space scalabi

---

### [190] Heavy-Tailed Memory Traces in Long-Horizon Language Agents

**链接**: https://arxiv.org/abs/2610.00010
**作者**: Xinyuan Song, Zekun Cai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon language agents increasingly rely on external memory as a frozen world model, yet current memory systems are usually judged only by task success or token cost. We argue that the missing object is the shape of memory use: under finite context and repeated retrieval, agent memory can concentrate on a small core while leaving rare states in a long tail where prediction errors accumulate. We study this effect through a conservative tail audit and find that concentration is reproducible but policy-dependent. Random-walk agents produce log-normal-compatible retrieval artifacts, whereas semantic LLM policies yield the strongest truncated-power-law-compatible core--tail traces. Motivated by this audit, we propose Core--Tail World Model (CTWM), a rank-based memory controller that allocates prompt budget with a single exponent $\tau$ while retaining a summarized tail. On Synthetic Graph World, CTWM preserves full state and transition coverage, reduces prompt tokens by 5.9%, and lowe

---

### [191] AbsorbEvo: An Agentic Framework for Autonomous Inverse Design of Microwave Absorbers

**链接**: https://arxiv.org/abs/2610.01119
**作者**: Zhicheng Feng, Yubo Zhao, Xuefeng Yao
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Designing high-performance microwave absorbers requires specialized expertise in electromagnetic theory, materials science and simulation programming, and entails time-consuming optimization. Here, we present AbsorbEvo, an agentic framework for autonomous inverse design that translates natural-language performance objectives into designs verified by full-wave simulations. Its candidate evolution strategy integrates language reasoning, physics-based prediction and historical feedback. A large language model proposes the directions and magnitudes of parameter adjustments based on task objectives and computational history. The system combines directed increments with global sampling to generate candidates and uses a low-cost predictive model as a physics prior to rank them. Only high-ranking designs undergo full-wave simulation. Results passing physical validity checks are used to evaluate performance and guide subsequent search. Experience from training tasks is further distilled into te

---

### [192] Federated Learning for LLMs over Mobile Networks: Issues and Solutions in the RAN Transport

**链接**: https://arxiv.org/abs/2610.01304
**作者**: Emilio Paolini, Andrea Pinto, Flavio Esposito, Luca Valcarenghi
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated LLM fine-tuning enables large models to be adapted using private and geographically distributed data at the network edge, creating recurring and deadline-sensitive communication workloads across access and transport networks. This challenge is particularly relevant in mobile RANs, where wireless variability, mobility, and device heterogeneity cause model updates to arrive asynchronously. Although these updates belong to the same learning round and share a common destination and deadline, conventional transport networks treat them as independent device-originated flows, hiding their underlying structure and limiting the ability to efficiently provision transport resources. This mismatch is particularly problematic for optical circuit switching and all-photonics transport, which benefit from predictable and schedulable traffic demands. We argue that future RANs should act as learning-aware traffic shapers by exposing the communication structure of distributed model adaptation t

---

### [193] VRUGA: Visual and Reasoning Uncertainty Guided Active Learning for Medical MLLM Post-training

**链接**: https://scholar.google.com/scholar_url?url=https://papers.miccai.org/miccai-2026/paper/3198_paper.pdf&hl=zh-CN&sa=X&d=3956501336951485829&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVFBEb_4H7OC7RA4YISLctXk&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=4&folt=kw-top
**作者**: B Xiao, J Wu, R Zhang, J Xu, F Zhao, G Wang 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In the medical MLLM post-training, we consider a pre-trained multimodal model Mθ, a limited expert annotation budget B ≪ N, and an … We present VRUGA, a dual-uncertainty-guided active learning framework for medical MLLM post-training. By combining multimodal

---

### [194] BIRD: Distilling Decision Boundaries into Rationales for MLLM Adaptation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.33713&hl=zh-CN&sa=X&d=7535457445283811488&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVEZrpMlAwFGsc5hncxjq1Qg&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=0&folt=kw-top
**作者**: A Liu, Y Wu, R Chen, Y Zhang, Q Zeng, P Cai 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Adapting general-purpose multimodal large language models (MLLMs) to specialized domains requires learning domain-specific decision criteria, which often hinge on subtle visual distinctions between otherwise plausible answers. Rationale

---

### [195] MiCo: Mutual Information Coverage Optimization through Semantic Erasure Modeling for Efficient MLLM Inference

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.34330&hl=zh-CN&sa=X&d=15074525098500858076&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVFPBIi1hwD6Endb-b950E8k&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=1&folt=kw-top
**作者**: T Wang, Y Guo, Q Zhang, Y Zhang, W Ouyang… - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multimodal large language models (MLLMs) have demonstrated impressive performance in multimodal understanding, but processing large numbers of visual tokens results in high computational costs. While many methods have been

---

### [196] TongGuOCR: A Layout-Aware and Token-Augmented OCR MLLM for Chinese Historical Documents

**链接**: https://scholar.google.com/scholar_url?url=https://ui.adsabs.harvard.edu/abs/2026arXiv260807917Z/abstract&hl=zh-CN&sa=X&d=1073659450496701808&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVGxq6-CW3bWBzo4yeff2BbQ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=2&folt=kw-top
**作者**: Z Zhou, Y Sun, H He, Y Zhang, P Zhang, Y Fang… - arXiv e-prints 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Chinese historical documents preserve valuable cultural heritage, but many collections remain accessible only as scanned page images, preventing full-text retrieval, collation, and computational analysis. Optical character recognition (OCR)

---

### [197] Do MLLM Judges Judge the Edit? Auditing Bias in Image Editing Evaluation with Verified Quality Preservation

**链接**: https://arxiv.org/abs/2610.01670
**作者**: Yuan Huang, Zirui Song, Xiuying Chen
**来源**: cs.CV cs.LG
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are increasingly used as automated judges for instruction-based image editing and as reward signals for model training. However, systematically auditing whether these judges are influenced by cues irrelevant to editing quality is challenging because visual interventions may themselves alter the quality being evaluated. A judgment shift can therefore be attributed to bias only when the intervention is verified to preserve the underlying editing quality. To address this challenge, we introduce EditJudgeBias, a counterfactual benchmark with verified quality preservation, comprising 1,196 real editing samples and 13 cues injected across four evaluation sites. We verify quality preservation for the requested edit using calibrated multimodal validators, controls, and human inspection. We then audit five MLLM judges along three complementary dimensions: invariance to quality-preserving cues, agreement with human judgments, and stability of pairwise pre

---

### [198] Two Clocks in Diffusion MLLMs: When Answers Stabilize Before Rationales Unfold

**链接**: https://arxiv.org/abs/2610.00953
**作者**: Keuntae Kim and Yong Suk Choi
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An answer candidate in a masked diffusion MLLM can stabilize while its rationale is still unfolding. We distinguish retrospective stabilization of the logged candidate from token commitment, and examine these two clocks relative to rationale generation. Analyzing our results across three visual question-answering benchmarks, we find that 89.4-98.1% of the rationale-side canvas remains unwritten at stabilization in single-block, EOS-suppressed LaViDa runs. On V*Bench, reducing block length from 128 to 8 changes this fraction from 89.4% to 1.7%, together with answer coverage and the eligible observation window. Under EOS-enabled prompting, direct instructions improve Nemotron's overall accuracy by 15.0 and 19.5 percentage points on M3CoT and ScienceQA, but reduce LaViDa/V*Bench accuracy by 11.0 points. A symmetric decomposition associates the larger absolute component of each change with coverage rather than conditional accuracy. Matched-canvas image ablations measure visual sensitivity 

---

### [199] The Earth in One Gaze: Training-Free Active Focus for UHR Remote Sensing Understanding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2609.31747&hl=zh-CN&sa=X&d=5428014919225583621&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVG1CjSpiFZ4c6vy_iZ-3jnd&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=5&folt=kw-top
**作者**: Y Zhang, P Dai, W Guo, J Liang, J Song, Y Ou 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Our pilot study finds that a frozen MLLM already produces useful question-guided spatial … The MLLM selects evidence cells from an indexed overview; a deterministic, topology-… from this focused view, using at most two MLLM calls and

---

### [200] ForensicZoom: Adaptive Visual Inspection with Multimodal LLMs for Industrial-Grade Face Forgery Detection

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.31661&hl=zh-CN&sa=X&d=8638473660033051797&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVH9IcUY-N4LFV11mosh0VG7&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=6&folt=kw-top
**作者**: H Zhou, Y Tang, K Yu, Q Zhu, M Li, W Wen - arXiv preprint arXiv:2609.31661 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In this work, we introduce ForensicZoom, an industrial-grade MLLM framework for adaptive face forgery detection. We adopt an MLLM … ForensicZoom first equips a general-purpose MLLM with forensic-aware visual representations and aligns the

---

### [201] WayFinder: Hierarchical Visual-Language-Action for Zero-Shot Waypoint Generation and Low-Level Kinematic Control

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.37922&hl=zh-CN&sa=X&d=2021556245432617284&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVFtZtzPzg3xnieCaZ2vvJ75&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=8&folt=kw-top
**作者**: TK Johnsen, M Levorato - arXiv preprint arXiv:2609.37922, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> using three different parameter scales of the Gemma 3 MLLM . Compared to baselines relying solely on low-level kinematic control, WayFinder significantly improves navigation success rates, varying by the environment and size of the

---

### [202] From Density to Biopsy Decisions and Malignancy Prediction: A Benchmark Study of Multimodal Large Language Models Against Radiologists in Digital and Contrast …

**链接**: https://scholar.google.com/scholar_url?url=https://ui.adsabs.harvard.edu/abs/2026arXiv260914676A/abstract&hl=zh-CN&sa=X&d=14809613201854945525&ei=eES_au6_F4-P6rQPyoz98A0&scisig=ACTRDVE-u1k2JV16hVttNlr8eKiw&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=7&folt=kw-top
**作者**: A Abbasian Ardakani, A Mohammadi, T Yusuf Kuzan… - arXiv e-prints, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Lesion masks substantially improved MLLM continuous malignancy-probability accuracies from 64.65%-71.63% to 72.56-78.60% on DM and from 67.91%-77.21% to 72.56%-81.86% on CEM, approaching radiologist ranges (DM 63.72-82.79%;

---

### [203] CortexBridge: Cortical Alignment of EEG Montages for Foundation Models

**链接**: https://arxiv.org/abs/2610.01124
**作者**: Jiazhen Hong, Xiaotian Zhou, Zihao Ding, Kailong Wang, Yu Wu
**来源**: cs.AI eess.SP
**匹配关键词**: EEG, BCI, Brain-Computer Interface, Foundation Models
**相关性评分**: 10.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) foundation models are often pretrained with a fixed channel vocabulary or a limited set of montages, making transfer difficult when electrode layouts change. We propose CortexBridge, a lightweight adapter that combines EEG features with electrode and atlas coordinates to map arbitrary montages into a shared cortical latent space. Evaluated with three frozen foundation models on five brain-computer interface (BCI) datasets from the Mother of All BCI Benchmarks (MOABB), CortexBridge improves performance in 13 of 15 evaluations. The gains in balanced accuracy average 0.80% for EEGPT, 0.70% for LaBraM, and 3.26% for CBraMod, with a maximum gain of 13.02% on 12-class steady-state visual evoked potential (SSVEP) classification. Visualizations of the learned atlas representations reveal task-dependent spatial patterns, with SSVEP showing a more concentrated representation in the Yeo Visual network than auditory P300. These results establish cortical alignment as a

---

### [204] Benchmarking EEG Foundation Models at Scale: Lessons from 20,000 Evaluations

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.32743&hl=zh-CN&sa=X&d=14726076108646822120&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVES-GVqjlivZW12QNfDxIz7&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=6&folt=kw-top
**作者**: Z Chen, S Peng, C Qin, R Liu, R Yang, KC Tan 等 (8 人)
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> , we introduce EEG -Arena, an open-source benchmark covering 30 EEG FMs and 25 … We find that (1) EEG FMs outperform strong task-specific supervised baselines on most … data become available; (3) existing EEG FMs do not exhibit a consistent

---

### [205] EEGDM: Label-Efficient EEG Representation Learning with Generative Diffusion Model

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11710256/&hl=zh-CN&sa=X&d=3808427582145778619&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVFZIaaUcsbuhK8bq3ix2kX2&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=3&folt=kw-top
**作者**: JH Puah, SK Goh, Z Zhang, Z Ye, CK Chan, KS Lim… - IEEE Journal of Biomedical … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We evaluate EEGDM on three EEG benchmarks spanning EEG event … , EEG FMs were pretrained on a large amount of unlabeled and heterogeneous EEG datasets through self-supervised pretraining for representation learning using

---

### [206] Distinct EEG functional network alterations in Parkinson's disease and multiple system atrophy

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2213158226001324&hl=zh-CN&sa=X&d=15935273435790602021&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVEVtstyZS-til5-g6gcc_NM&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=9&folt=kw-top
**作者**: D Chen, H Tang, Y Pan, Z Zhang, W Wang, F Leng… - NeuroImage: Clinical 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Here, we aimed to characterize EEG cortical network alterations in PD and MSA … EEG network features with standard clinical assessments provided a modest incremental gain in discrimination between PD and MSA-P. These findings highlight

---

### [207] JU-PDDv1: a harmonized dataset for Parkinson's disease diagnosis from heterogeneous EEG recordings

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S3050623926000696&hl=zh-CN&sa=X&d=1030245169544712861&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVFqaUvepnOG6T0WYA5_mY5u&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=0&folt=kw-top
**作者**: S Bera, PK Singh - Brain Network Disorders, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> However, progress in EEG -based PD research has been hindered by the … -source EEG dataset integrating six publicly available PD EEG datasets comprising 360 participants. By implementing a unified pre-processing pipeline, we established the

---

### [208] Decoding obstructive sleep apnea phenotypes through integrated multimodal sleep EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0969996126003773&hl=zh-CN&sa=X&d=7672743869093579166&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVHHQY5opa53DJFxE6G7yajH&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=5&folt=kw-top
**作者**: J Zheng, Q Yu, Y Qiu, G Kuang, F Dong, Y Zhu 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Obstructive sleep apnea (OSA) is a heterogeneous disorder poorly characterized by the apnea-hypopnea index (AHI), with current subtyping overlooking sleep neurophysiology. We aimed to identify objective neurophysiological phenotypes and

---

### [209] EEG Biomarkers During Upper-Limb Action Observation Therapy for Stroke Rehabilitation: A Scoping Review

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s10439-026-04404-2&hl=zh-CN&sa=X&d=16101346076580793841&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVFbx-GzxGFucQyJmLfzY1VT&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=2&folt=kw-top
**作者**: AT Nguyen, MJ Johnson - Annals of Biomedical Engineering, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This scoping review aimed to identify EEG -derived indicators of cortical engagement during upper-limb AO therapy after stroke, examine … AO paradigms with EEG outcomes and motor assessments. Data were extracted on AO task

---

### [210] Best Practices in EEG Analysis: Preprocessing, Modeling, and Machine Learning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.36609&hl=zh-CN&sa=X&d=5669117134856901291&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVHe0eFVDf4RBUkiPYWYzwrJ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=8&folt=kw-top
**作者**: P Razmara, W Jeong, A Kommineni, R Cassani… - arXiv preprint arXiv …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> EEG recordings are notoriously prone to contamination because the signals of interest (… This section details best practices for cleaning EEG data: identifying major noise sources, … the Brain Imaging Data Structure for EEG , or BIDS- EEG )

---

### [211] GRAN- EEG : A ghost-residual attention network for subject-independent EEG -based objective pain recognition

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S174680942602152X&hl=zh-CN&sa=X&d=3893848034243701454&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVFX4yJRUDKGkiBHZfsVkal3&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=7&folt=kw-top
**作者**: RC Joshi, S Kumar, SKS Gautam, R Burget, MK Dutta - Biomedical Signal Processing …, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , a Ghost-Residual Attention Network for subject-independent pain recognition using electroencephalography ( EEG ). Recordings from the … across multiple EEG frequency bands. Thus, GRAN- EEG provides an accurate and interpretable

---

### [212] Multi-view EEG schizophrenia detection using novel scattering-based patch encoding and deep attention mechanism

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1568494626019794&hl=zh-CN&sa=X&d=119610723622886337&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVGQmE7tAaw07pqlcoEYaT64&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=4&folt=kw-top
**作者**: R Prafful, A Kumar, RR Sharma, A Bhattacharyya… - Applied Soft Computing, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> SZ using multi-channel electroencephalogram ( EEG ) signals. In the pipeline, we extract rhythms (delta, theta, alpha, beta, and gamma) from multichannel EEG signals for multi-view operation. Features are extracted from each multichannel EEG

---

### [213] Quantitative EEG in typical absence seizures: a systematic review of spectral and entropy/complexity signatures

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1059131126002967&hl=zh-CN&sa=X&d=9502105074338346655&ei=eES_auyCDYabieoP2qb0uAY&scisig=ACTRDVFg6KUMd7CYo_VoH58bfpk2&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=1&folt=kw-top
**作者**: R Simedrea, R Mîndreanu, S Clichici, B Buleteanu… - Seizure: European Journal …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background Typical absence seizures, the defining seizure type of childhood and juvenile absence epilepsy, are characterised by generalised 3 Hz spike-and-wave discharges and brief impairment of consciousness. Quantitative EEG (QEEG) offers

---

### [214] NEUROTOKEN: Joint Source and Directional AAD with Envelope Decoding via Conditional Flow Matching

**链接**: https://arxiv.org/abs/2610.00397
**作者**: Ali Alavi, Donald S. Williamson
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Identifying which speaker a listener is attending to in a noisy room -- the cocktail-party problem -- is the missing ingredient for next-generation hearing aids and brain-computer interfaces: it tells the device whose voice to amplify. Auditory attention decoding (AAD) reads this answer from EEG, but the literature splits into disconnected pieces: directional-AAD classifies side but does not map side to stream; regression-based source-AAD ranks candidate streams by a single Pearson correlation that is intrinsically noisy at the 1-5 s windows real devices need; and envelope reconstruction has no native AAD rule. We argue the right object is not any single statistic but the conditional likelihood of the attended envelope given EEG, and we make this practical with NEUROTOKEN: a single network whose three heads share one EEG front-end, with a conditional flow-matching head (ATTUNEFLOW) that scores candidates by an integrated velocity-residual likelihood ratio. Two inference-time ensembles 

---

### [215] Heteroskedastic Canonical Polyadic Tensor Decomposition

**链接**: https://arxiv.org/abs/2610.00498
**作者**: Kyle Ritscher, Carlos Llosa-Vite
**来源**: stat.ME cs.LG stat.ML
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When minimizing the squared-error loss, the popular CP decomposition can be interpreted as parameter inference in a Gaussian model with a low-rank mean tensor and constant variance across the tensor entries. We introduce heteroskedastic-CP (HCP), which models entrywise variability with a non-constant, low-rank precision tensor, and develop an alternating block-coordinate ascent method to recover both the low-rank mean and precision tensors from noisy observations. Our procedure is computationally competitive, with the same leading-order factor-update complexity as CP-ALS. We demonstrate HCP on synthetic experiments and an EEG application.

---

### [216] Fusion techniques of time frequency-based images to predict the outcome of rTMS depression therapy

**链接**: https://arxiv.org/abs/2610.00380
**作者**: Wael Korani and Md Fahimul Kabir Chowdhury and Mohammed Aledhari and Reza Rostami and Reza Kazemi
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depression is a mental condition that can lead to suicide and self-harm. Predicting the outcome of depression treatment is one of the most difficult tasks for clinicians. Among various treatment options, repetitive Transcranial Magnetic Stimulation (rTMS) is a widely used non-invasive method. Predicting rTMS response using Electroencephalogram (EEG) data is difficult because of high inter-subject variability and limited features from single-domain analysis. We introduce two fusion techniques, montage and blending, to overcome these limitations and extract richer features from EEG-derived Time-Frequency (TF) images. We then propose a lightweight custom Convolutional Neural Network (CNN) trained on fused TF representations. \textcolor{black}{We use a primary dataset of 15 patients and a secondary dataset of 46 patients. We run two sets of experiments. The first set uses segment-level 10-fold cross-validation. In this setup segments from the same patient can appear in both training and te

---

### [217] Model validation in machine learning: A scenario-based guide from hold-out splits to nested group cross-validation in biomedical and applied research

**链接**: https://arxiv.org/abs/2610.01284
**作者**: Mehmet Baygin, Sengul Dogan, Turker Tuncer
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Model validation estimates the performance of a complete learning procedure on new data. However, an invalid split can produce an optimistic and stable result. This tutorial reviews hold-out validation, train/validation/test designs, repeated random subsampling, k-fold and repeated stratified cross-validation, leave-one-out and leave-p-out schemes, group-aware validation, and nested group cross-validation. General machine-learning principles are linked to EEG epochs, paired-eye OCT images, repeated clinical measurements, and multicenter data. Eight controlled scenarios compare flawed and leakage-safe designs: seven use locked confusion matrices with auditable metrics, and one uses a reproducible repeated-study simulation. The scenarios cover global feature selection, normalization leakage, dependent records, center mixing, repeated test-set use, and estimator instability. Bias, variance, metric aggregation, uncertainty, and computational cost are also examined. A data-size matrix, a de

---

### [218] Towards Fast and Disentangled Counterfactuals for Visual Foundation Models

**链接**: https://arxiv.org/abs/2610.00895
**作者**: Sidney Bender, Benedikt Kunz, Ahmed Zeid, Shinichi Nakajima, Klaus-Robert M\"uller, Marco Morik
**来源**: cs.LG cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models remain vulnerable to spurious correlations and ``Clever Hans'' strategies. Explainable machine learning can find and remove such strategies for classifiers without metadata. For foundation models, no such option exists yet. We propose Disentangled Diffusion Autoencoders (DiDAE). DiDAE wraps a frozen foundation model in a conditional diffusion decoder. A counterfactual is one closed-form edit along a direction of a disentangled dictionary, followed by decoding. The dictionary can be supervised (Procrustes) or unsupervised (Singular Value Decomposition, Sparse Autoencoders). No gradients are needed, so DiDAE is up to 2000 times faster than the state of the art. We evaluate on six datasets, two synthetic and four real-world. In a desiderata-driven benchmark on three of them, its counterfactuals are on par with or better than the state of the art, and they repair downstream classifiers through Counterfactual Knowledge Distillation (CFKD), where they beat metadata-based co

---

### [219] Coupling Perception and Reasoning in Federated Multimodal Graph Foundation Models

**链接**: https://arxiv.org/abs/2610.00277
**作者**: Zekai Chen, Xun Wu, Hailin Zhang, Xunkai Li, Yu Liu, Kairui Yang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated multimodal graph foundation models (GFMs) aim to adapt pretrained multimodal models to decentralized graph data, where each client owns a private multimodal graph and cannot share raw information. These models typically combine a multimodal Encoder that extracts semantic evidence from heterogeneous modalities and a graph neural network (GNN) that performs relational reasoning over graph structures. However, existing federated GFM adaptation methods mainly update graph-side modules while keeping the multimodal Encoder frozen, limiting adaptation to \emph{how information is propagated} while fixing \emph{what information is extracted}. Through empirical studies, we reveal that Encoder and GNN adaptations are not independent: Encoder adaptation is affected by graph relations, while cross-client module swapping reveals substantial pairing sensitivity between separately parameterized Encoder and GNN updates. Motivated by this observation, we propose \textbf{FedCORE}, a federated a

---

### [220] Distillation of Tabular Foundation Models into Efficient Predictors

**链接**: https://arxiv.org/abs/2610.01435
**作者**: Minho Jeong, Dooho Lee, Jinmo Lee, Jaemin Yoo
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) achieve strong predictive performance through in-context learning, yet repeatedly conditioning on labeled data makes inference expensive. Knowledge distillation can reduce this cost by transferring their predictive ability to lightweight, dataset-specific students. However, the dependence of TFM predictions on both a labeled context and a query introduces two design questions: how to construct teacher supervision and whether expanding query coverage improves distillation. We examine these questions across two TFMs and both neural and tree-based students, and derive an effective distillation recipe. The recipe uses the full labeled training set as teacher context and trains students solely on teacher predictions for observed and synthetic queries. On TabArena, the resulting students outperform their supervised trained tuned-and-ensembled counterparts by 57-98 Elo points. Applied unchanged to TALENT, the same recipe improves matched default students on 23

---

### [221] RelICL: Training-free Relational Learning with Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.01725
**作者**: Simon Forbat and Rainer Gemulla
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models achieve state-of-the-art performance on single-table tasks without any training. Recent work suggests that they are also well-suited for relational learning via deep feature synthesis (DFS), which flattens a relational schema into a single table by adding aggregates of the other tables' columns as features. This approach is appealing because it directly benefits from improvements to or customization of the underlying tabular foundation model. In this paper, we identify two key problems with DFS: feature explosion and interaction blindness. The first problem arises because the number of DFS features grows quickly as the schema becomes more complex, limiting scalability and performance. The second problem arises because column-wise aggregates do not account for feature interactions, limiting performance. We propose and explore an alternative method termed RelICL, which keeps the benefits of DFS but alleviates these two problems. At its heart, RelICL propagates a

---

### [222] Higher-Order Molecular Grammars for Generative and Foundation Models in Chemistry

**链接**: https://arxiv.org/abs/2610.02186
**作者**: Yiming Huang, Yujie Zeng, Vijay Prakash Dwivedi, Simone Foti, Jianmin Wang, Jure Leskovec 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Molecular learning models are strongly shaped by their underlying representations. Yet standard sequential and graph formalisms struggle to explicitly encode higher-order topology, such as ring systems and recurring motifs. Existing higher-order representations can capture these structures directly, but they are often computationally demanding and difficult to decode into valid molecules. Here, we introduce Higher-order Grammar Representation (HGR), a principled, topology-aware framework that lifts molecules to combinatorial complexes and parses each complex into a compact sequence of production rules under a context-free higher-order grammar. By serialising higher-order topology into rule sequences, HGR makes these structures directly compatible with standard sequence models, avoiding the computational overhead of explicit higher-order encodings while preserving topological expressiveness. To reduce benchmark bias towards simple ring systems, we construct RingDiv, a ring-enriched benc

---

### [223] Parameter-Efficient Distributionally Robust Adaptation of Tabular Foundation Models under Subpopulation Shift

**链接**: https://arxiv.org/abs/2610.01143
**作者**: Seonghwi Kim, Sung Ho Jo, Minwoo Chae
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite strong mean accuracy, tabular foundation models (TFMs) can perform poorly on underrepresented groups under subpopulation shift, where group proportions change between training and deployment. We propose DR-TFM, a parameter-efficient distributionally robust adaptation framework that requires no true group annotations. DR-TFM adjusts attention to labeled context examples by fine-tuning an existing query scaling network or adding and training one, while keeping all other parameters fixed. We instantiate the framework with two robust objectives using estimated groups or source conditional distributions derived from training data. For TabPFN-3, adaptation updates only 0.016% of the pretrained model's parameters. Across five tabular benchmarks, DR-TFM achieves substantially higher average worst-group accuracy than pretrained TFMs and the compared robust baselines without true group annotations, while maintaining competitive mean group accuracy. DR-TFM also improves average worst-grou

---

### [224] Kinematic MeanFlow: One-Step Action Generation Policy for Robotic Foundation Models

**链接**: https://arxiv.org/abs/2610.00864
**作者**: Jiawei Fan, Sifeng Wang, Yuqing Hou, Anbang Yao
**来源**: cs.RO cs.AI cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this paper, we study how to achieve one-step action generation in Robotic Foundation Models (RFMs), aiming to overcome the high inference latency of multi-step flow matching. MeanFlow provides a promising framework for this goal, yet its direct application leads to performance collapse. We discover that this stems from two distinctive dynamics exhibited in the RFM velocity field: (1) the ``local acceleration" exhibits stability early on, but surges sharply towards the end of the denoising process, and (2) the spread of its magnitudes across samples widens as denoising progresses. To address these issues, we introduce Kinematic MeanFlow (K-MF), a novel one-step action policy tailored for RFMs. Specifically, grounded in a kinematic identity, K-MF decouples the time derivative term in the MeanFlow formulation into two sub-interval terms separated by an intermediate point. This decoupled formulation enables the two terms to capture early-stage and late-stage denoising dynamics, respecti

---

### [225] Dyna3: VLM-Guided Training-Free 4D Reconstruction via Depth Foundation Models

**链接**: https://arxiv.org/abs/2610.01286
**作者**: Xinhao Xiang, Weiyang Li, Zhijie Zheng, Abhijeet Rastogi, Jiawei Zhang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent depth foundation models like Depth Anything 3 (DA3) achieve remarkable multi-view depth estimation but assume static 3D scenes, limiting their applicability to real-world dynamic environments. Existing training-free 4D methods like Easi3R and VGGT4D rely on correspondence-trained backbones whose attention encodes cross-frame matching, a property absent in depth-only models like DA3. We present Dyna3, a training-free framework that extends DA3 for 4D dynamic scene reconstruction without any fine-tuning. Our key insight is that DA3's cross-view features, though trained only for depth consistency, implicitly encode motion-discriminative signals when combined with best-match feature search across frames. Its static surfaces find consistent matches globally, while dynamic objects cannot. We further adopt vision-language models (VLM) to automatically generate scene-specific semantic prompts for SAM 3, enabling precise instance-level segmentation that distinguishes which objects move f

---

### [226] Foundations without Fundamentals: Zero-Shot Blind Spots in Time Series FMs

**链接**: https://arxiv.org/abs/2610.02058
**作者**: Nafiseh Ghoroghchian, Haipeng Zhang, Shuyi Han, Alex Labach, George Stein
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the success of Time Series Foundation Models (TSFMs) on broad benchmarks, their ability to internalize basic temporal logic, especially in settings supported by exogenous covariates, remains under-examined. We introduce SimpleTimeBench, a diagnostic univariate and multivariate "unit test" suite for primitives such as monotonic trends, periodic signals and leading indicator covariates, scenarios where near-perfect forecasts should be trivial. Surprisingly, prominent multivariate TSFMs (Chronos-2, Moirai and Toto) frequently produce suboptimal zero-shot forecasts for these inputs. While fine-tuning Chronos-2 improves its behaviour on specific tasks, we show that this adaptation degrades performance on other fundamental patterns rather than enhancing its generalizable foundational capabilities. This reveals a gap between pre-training scale and basic temporal reasoning, suggesting that current TSFMs could potentially lack the inductive biases needed to capture simple predictable fu

---

### [227] When Text-to-Image Helps Editing: The Effects of Conditioning During Denoising

**链接**: https://arxiv.org/abs/2610.01681
**作者**: Lidia Troeshestova, Alexander Ustyuzhanin, Sergey Kastryulin
**来源**: cs.CV
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unified models are trained for both instruction-based image editing and text-to-image (T2I) generation, but standard editing pipelines keep source-image conditioning throughout denoising. We ask whether editing can benefit from T2I, and study how the effects of conditioning vary across edits and denoising stages. In pure editing, source attention declines for some edits over the sampling trajectory. This observation led us to task switching, which lets the model draw on its T2I capabilities. Across three unified editors and four benchmarks, switching to the T2I task for bounded intervals improves edit quality, while mean perceptual preservation remains close to pure editing across all three models. Unified editors therefore benefit from using both conditioning modes they are trained for, and the timing of the switch sets the balance between quality and preservation.

---

### [228] Can LLMs Reliably Annotate Bioassay Metadata to Improve Data Readiness?

**链接**: https://arxiv.org/abs/2610.01616
**作者**: Laura van Weesep, Riccardo Tedoldi, Jens Sj\"olund, Hossein Azizpour, Susanne Winiwarter, Ola Engkvist 等 (9 人)
**来源**: cs.CL cs.AI cs.DB q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The emergence of foundation models for molecular property prediction requires a high degree of AI data readiness, including reliable metadata annotation. However, both public repositories and industrial screening databases suffer from missing, inconsistent, or conflated assay annotations. In this work, we quantify the extent of missing annotations in PubChem for the BioAssay Ontology (BAO) assay format and physical detection method fields and investigate whether open-source and proprietary large language models (LLMs) can reliably predict and audit metadata annotations directly from the assay text. In our assessment, we found that the annotation coverage across PubChem's $\sim$2 million bioassays is critically sparse, 36\% lacking an assay format, 89\% a BioAssay type, and >99.9\% any BAO-mapped assay format or detection technology term. This motivates the need for automated test-metadata curation. Using evaluation sets derived from PubChem and ChEMBL, we assess the agreement of seven 

---

### [229] Latent-Foresight: End-to-End Learning Predictable Representations for Latent World Models

**链接**: https://arxiv.org/abs/2610.01942
**作者**: Efstathios Karypidis, Spyros Gidaris, Nikos Komodakis
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting the future evolution of a scene is a fundamental capability for world modeling. Recent work has shown that operating in the feature space of Vision Foundation Models (VFMs) yields semantically rich representations that support diverse future scene understanding tasks. However, existing approaches rely on two-stage pipelines, where VFM features are first compressed using fixed dimensionality reduction (e.g., PCA) or independently trained autoencoders, and a separate predictor is trained on top of the resulting frozen latent space. This decoupling between representation learning and temporal prediction, as well as approaches that apply predictors directly on raw VFM features, provides no guarantee that the latent space is structured for predictable dynamics. In this work, we propose Latent-Foresight, an end-to-end framework that jointly learns a latent tokenizer and a flow-based generative dynamics model, explicitly shaping the representation to support temporal predictability

---

### [230] DSSR-3D: Decoupled Reasoning for View-Dependent Referring in 3D Gaussians

**链接**: https://arxiv.org/abs/2610.00040
**作者**: Thanh-Khoi Nguyen, Thien-Phuc Tran, Minh-Triet Tran
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in 3D Gaussian Splatting have enabled open-vocabulary and referring segmentation by distilling semantic knowledge from 2D foundation models into 3D representations. However, existing referring fields embed language features in a globally view-invariant space, making them fundamentally unable to resolve observer-centric spatial relations (e.g., "to the left of") that depend on camera pose. We propose DSSR-3D, an inference-time framework for view-dependent referring segmentation on continuous 3D Gaussian fields, formalized as two interfaces - pose-invariant semantic localization and pose-conditioned spatial reasoning - such that any pair of functions satisfying these constraints yields a valid instantiation, requiring no retraining of the underlying semantic field and no reliance on discrete geometric proxies such as bounding boxes. We instantiate the two interfaces with a temperature-sharpened softmax localization mechanism and a projection-based directional scoring func

---

### [231] Generalist Representation, Specialist Detection: TS-Router for Time-Series Anomaly Detection

**链接**: https://arxiv.org/abs/2610.00978
**作者**: Tian Lan, Yifei Gao, Yimeng Lu, Xuming An, Meng Wang, Yue Pan 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series anomaly detection (TSAD) is difficult to generalize across datasets because heterogeneous temporal dynamics imply different notions of normality and favor different detection criteria. While time-series foundation models provide transferable representations, coupling them with a fixed anomaly-scoring mechanism can overlook this variation. This motivates a different perspective on foundation-model-based TSAD: using foundation models to coordinate specialized anomaly criteria rather than directly imposing a universal one. Based on this view, we propose \textbf{TS-Router}, a generalist-representation, specialist-detection framework that estimates the relative competence of heterogeneous anomaly detectors from pretrained temporal representations and selects suitable specialists for each target series. To avoid relying on specialist-performance labels from real tasks, we derive soft competence supervision from specialists' relative performance on labeled simulated tasks. At depl

---

### [232] CLoSeR: Closing the Loop for Long-Context Streaming Reconstruction

**链接**: https://arxiv.org/abs/2610.01927
**作者**: Moyang Li, Zihan Zhu, Wei Zhang, Marc Pollefeys and Daniel Barath
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feedforward foundation models have recently shown remarkable 3D reconstruction capabilities. However, existing models exhibit large tracking drift in long-context streaming reconstruction due to error accumulation. In this paper, we revisit loop closure with streaming reconstruction foundation models to enable accurate, drift-free, kilometer-scale reconstruction. Specifically, our method detects loop candidates through global descriptor retrieval, and constructs loop-conditioned windows to estimate the relative poses between looped frames. Given the observation that our adopted streaming reconstruction backbone produces a globally consistent scale, we optimize all frame poses on the SE(3) manifold with sequential and loop closure constraints, avoiding the pose graph optimization on the Sim(3) or higher-dimensional SL(4) manifolds employed in prior works. Extensive experiments show that our method reduces drift and produces consistent geometry on kilometer-scale sequences, significantly

---

### [233] VANDAM: Viewing a nucleotide sequence with DNA molecular priors

**链接**: https://arxiv.org/abs/2610.00411
**作者**: Jeremy Levy, Ariel Larey, Yury Nahshan, Raizy Kellerman, Elay Dahan, Amit Bleiweiss 等 (10 人)
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contemporary Genomic Foundation Models (GFMs) rely on a DNA-as-a-string paradigm that employs masked token prediction objectives for pretraining. However, this abstraction does not explicitly model the biochemical, structural, and physical properties essential to biological function. Many molecular properties can be estimated from sequence using established biophysical models, so their utility lies not in providing an independent modality, but in introducing priors that training objectives can explicitly exploit. We introduce VANDAM, a framework that extends the training of GFMs with DNA molecular priors. In self-supervised training, VANDAM predicts regional molecular properties from pooled representations. When functional labels are available and can reward retaining molecular priors, local features are additionally injected at the input. VANDAM consistently improves downstream performance across four architecture families and nine held-out genomic tasks by complementing token-based o

---

### [234] NarrativeFlow: Flow-Based Vision-Language-Action Model Using Robot Velocity Fields

**链接**: https://arxiv.org/abs/2610.00981
**作者**: Shota Kobayashi, Koki Seno, Daichi Yashima, Komei Sugiura
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We focus on language-conditioned flow-based manipulation, where robot flows (robot velocity fields) serve as embodiment-agnostic, motion-centric representations for leveraging data collected from multiple robot platforms. This task is crucial because language-conditioned manipulation is essential for practical robotic systems, yet scaling robot foundation models remains limited by the labor-intensive collection of embodiment-specific data. Existing methods either coarsely approximate robot flows with sparse keypoint displacements, or cannot handle language-conditioned manipulation. To address this limitation, we propose NarrativeFlow, which models robot flows as continuous velocity fields using a flow-matching formulation conditioned on language. Accordingly, NarrativeFlow generates robot flows that are physically consistent with real-world manipulation. To validate NarrativeFlow, we have conducted experiments on standard datasets for language-conditioned manipulation. The experimental

---

### [235] RACE: Residual-Aware Test-Time Adaptation for Neighbor-Rich Time-Series Foundation Model Forecasting

**链接**: https://arxiv.org/abs/2610.00405
**作者**: Hao-Nan Shi, Tong Wu, Chen-Cong Sun, Yuan Jiang, Han-Jia Ye, De-Chuan Zhan
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models (TSFMs) perform strongly across forecasting tasks, but their per-series inference is ill-suited to neighbor-rich forecasting, where each query has access to related but nonidentical historical series. Continuous glucose monitoring (CGM) and Web/cloud workloads exemplify this setting: CGM trajectories share physiological patterns but vary across individuals, devices, and conditions, while Web/cloud workloads combine common operating regimes with non-stationarity, heavy tails, and bursts. These histories share useful structure, yet neighbors are not equally relevant. Existing methods either fine-tune TSFMs for each target domain, incurring additional costs and offering limited transferability across backbones, or append retrieved series without verifying whether they support the current forecast. The key challenges are conflicting residual evidence from neighboring series and residual patterns that vary across TSFMs and forecasting tasks. We formulate test-t

---

### [236] Token Communication-Assisted Collaborative Embodied Artificial Intelligence: Concepts, Framework, and Opportunities

**链接**: https://arxiv.org/abs/2610.01826
**作者**: Peng Yi, Ying-Chang Liang
**来源**: eess.SP cs.AI cs.MA
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collaborative embodied artificial intelligence (CEAI) enables multiple physical agents to perceive, reason, and act cooperatively in dynamic environments. Effective communication is essential for CEAI, yet CEAI agents must exchange not only large multimodal observations but also task-relevant insights, intents, and interactive information over long horizons. This article investigates token communication (TokCom) as a native intelligence interface for CEAI, in which tokens serve jointly as compact semantic carriers for communication and fundamental inference units for generative foundation models (GFMs). We first discuss how TokCom supports insight sharing, intent alignment, and interactive control among embodied agents. We then propose a TokCom-assisted CEAI framework driven by a task-adaptive communication protocol. Comprising a compact codebook, syntax rules, and contextual examples, this protocol guides GFM-based transceivers to distill messages into compact tokens and reconstruct t

---

### [237] From Image Latent Space to Fuzzy Rules: Interpretable Analysis of Gastrointestinal Foundation Model

**链接**: https://arxiv.org/abs/2610.00414
**作者**: Michael D. Vasilakakis (1), Dimitris K. Iakovidis (1) ((1) Department of Computer Science and Biomedical Informatics, University of Thessaly, Lamia, Greece)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models pretrained on large-scale datasets demonstrate strong transferability to medical imaging tasks. However, understanding how their latent representations encode clinically relevant information remains an open challenge in safety-critical domains. This study proposes a prototype-based fuzzy-rule framework that interprets the patch-level features produced by the inner layers of pretrained foundation models, without any fine-tuning. Class-specific prototypes are learned by clustering in the feature space, yielding compact visual patterns. Patch features are then expressed as prototype similarities and classified by fuzzy rules with linguistic IF-THEN conditions that are human readable. The framework is applied across the final two blocks of ViT-S/16 backbones pretrained on ImageNet-1K and GastroNet-5M, and benchmarked against k-nearest neighbours, kernel SVM, and linear probing under identical frozen features, on wireless capsule endoscopy classification, gastrointestinal 

---

### [238] ORBIT-FMIB: Tracking Order-Resolved Epistatic Information Through ESM-2

**链接**: https://arxiv.org/abs/2610.00672
**作者**: Maryam Rahimimovassagh, Ivan Garibay, Niloofar Yousefi
**来源**: cs.LG q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Protein foundation models support mutation-effect and structural prediction, but predictive performance alone does not reveal which forms of biological interaction information remain accessible through model depth. We ask whether ESM-2 retains higher-order epistatic information as strongly as first- and second-order information across its representation hierarchy, introducing ORBIT-FMIB, a diagnostic framework combining Walsh-based interaction decomposition with subset-conditioned neural dependence estimation. The method is validated on synthetic landscapes with known interaction structure before being applied to the dense four-site GB1 fitness landscape using frozen ESM-2 representations. An initial production run suggested ESM-2 retains higher-order epistatic information less well than lower-order information ($\Delta_{\mathrm{HO-LO}}=-0.107$). An independent replication of the complete measurement grid, under matched GPU hardware and identical critic seeds, substantially reduced thi

---

### [239] FedLore: Communication and Memory Efficient Federated Learning via Shared Gradient Low-Rank Projection

**链接**: https://arxiv.org/abs/2610.01620
**作者**: Junkang Liu
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Federated training of foundation models is constrained by client memory and communication costs. LoRA-based methods reduce these costs through low-rank adapters, but their fixed rank budget can limit adaptation. Gradient low-rank optimization offers greater flexibility, yet independently chosen client subspaces create a problem we term \emph{subspace fragmentation}: local projections interact with data heterogeneity to bias aggregated directions, while aggregation can increase update rank and communication cost. Thus, accurate local gradient compression need not preserve global descent. We propose \texttt{FedLore}, which shares a low-rank optimization basis within each round and refreshes it across rounds. The shared basis enables exact aggregation in low-rank coordinates and eliminates the identified projection bias. Subspace refresh allows the accumulated model update to exceed the per-round rank budget. We characterize the aggregation bias and establish an $O(T^{-1/2})$ stationarity

---

### [240] PixelDense: Dense Prediction as Representation Alignment for Pixel Diffusion

**链接**: https://arxiv.org/abs/2610.00483
**作者**: Lehan Yang, Daiqing Qi, Wenhao Zhang, Avery Li, Yiqing Yang, Yifan Li 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Representation alignment (REPA) accelerates diffusion transformer training, but its alignment targets are almost exclusively semantic encoders such as DINOv2 and CLIP. Recent analysis points to spatial structure, not global semantics, as the carrier of the alignment effect, yet dense-prediction foundation models trained to predict that structure remain overlooked as REPA targets. In pixel-space diffusion, SAM2, Depth Anything v2, and Metric3D v2 each outperform the DINOv2-only GenEval baseline, with the two geometric teachers leading the segmentation teacher. A flat sum of all four teachers, however, lands below the best single geometric teacher, as semantic and geometric gradients compete for one denoiser projection. We introduce PixelDense, which routes DINOv2 and SAM2 through a semantic projection stream, routes Depth Anything v2 and Metric3D v2 through a geometric projection stream, and adds a weight-space orthogonality penalty that keeps the two streams in disjoint subspaces. All 

---
