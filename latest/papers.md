# 📑 论文索引 - 2026-09-01

共 131 篇论文

---

### [1] AIM: Anchor Identity Features, Then Match for Multimodal Large Language Model Unlearning

**链接**: https://arxiv.org/abs/2608.28312
**作者**: Wonjun Lee, Jaehyuk Jang, Kangwook Ko, Hee-Seon Kim, Changick Kim
**来源**: cs.CV cs.CL
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) can memorize identity-specific facts about people in their fine-tuning data, creating privacy risks when a person requests deletion. Existing MLLM unlearning methods often assume access to retain images or ground-truth answers during deletion, which is unrealistic in many practical scenarios. We study identity unlearning when retain images are unavailable at deletion time. Our analysis shows that identity and visual-perception questions occupy distinct regions in fine-tuned hidden states and are organized differently: identity questions cluster by person, whereas perception questions cluster by question type. This suggests that identity knowledge can be suppressed without erasing general visual perception. Building on this observation, we propose AIM, a two-stage method that anchors an identity-forgetting target with a universal visual prompt and then matches the vision encoder to that target under a Fisher-based constraint. Extensive experiment

---

### [2] RefLAM: A Reference-Grounded Line Annotation Pipeline for Historical Arabic Manuscripts

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.25140&hl=zh-CN&sa=X&d=2558807937850741622&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-yax75LKJljiVHkVUb8ZAgT&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=7&folt=kw-top
**作者**: M Guechaoui, MD Zellagui, S Chaib, S Dhelim - arXiv preprint arXiv:2608.25140, 2026
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> RefLAM couples a deep-learning page-segmentation model with a multimodal large language model ( MLLM ) for structured OCR and a diacritic-agnostic fuzzy alignment engine that grounds each OCR line in a contiguous span of the reference

---

### [3] RetailAgent: Structured Adverse Timing in Self-Conditioned Multimodal LLM Trading Agents

**链接**: https://arxiv.org/abs/2608.28399
**作者**: Yupeng Zhang, Liuyuan Jiang, Hongyi Huang, Bingheng Li, Lisha Chen
**来源**: cs.AI q-fin.TR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In financial markets, a sequential policy that reacts systematically to price movements may become predictable to other market participants. This paper studies whether large language model (LLM) agents exhibit such directional structure through RetailAgent, an experimental framework in which an LLM observes anonymized intraday equity price histories and permitted state, then repeatedly chooses long (hold the stock) or flat (stay out) before the subsequent interval return is revealed. We compare returns during long and flat intervals along the same stock's intraday path after removing the overall fraction of long decisions. This exposure-matched measure reveals persistent negative timing across modality, horizon, state, and model family. Shuffling saved action sequences substantially attenuates the effect, showing that alignment between actions and subsequent returns drives the negative score. Feeding self-authored memories into decisions further increases policy persistence, while timi

---

### [4] D-TAIA: Domain-Aware LLM Adaptation for Multi-Task Predictive Process Monitoring

**链接**: https://arxiv.org/abs/2608.28236
**作者**: Sjoerd van Straten, Christine Jacob, Marwan Hassani
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predictive Process Monitoring (PPM) enables organizations to forecast future process behavior, such as the next activity and remaining time of ongoing cases. In practice, three conditions cause existing methods to degrade, namely data scarcity, high process entropy and distributional shift. While Foundation Models (FMs), especially Large Language Models (LLMs), offer a new paradigm through broad sequential reasoning, adapting them to multi-task PPM under these conditions remains an open challenge. Existing FM-based approaches either lack mechanisms for handling distributional shift or rely on direct regression heads that can be structurally misaligned with continuous time prediction tasks. This paper introduces D-TAIA (Domain-aware Training and Attention-based Inference Architecture), a framework for a joint next activity and remaining time prediction task via parameter-efficient fine-tuning of an FM backbone. Our approach combines domain-aware triplet loss (DATL) pre-training with FAI

---

### [5] CAITLYN: Can LLM Agents Autonomously Synthesize Defenses against Emerging Injection Attacks?

**链接**: https://arxiv.org/abs/2608.27990
**作者**: Zi Liang and Xiaoyu Xu and Yanyun Wang and Minxin Du and Qingqing Ye and Haibo Hu
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt injection attacks on Large Language Model (LLM) agents seek to introduce malicious instructions or content into external text sources retrieved by agents, forcing the underlying LLMs to execute harmful actions outside their benign scope. While current defenses effectively counter known injection attacks, deploying them in LLM agent environments remains challenging due to attack variants and emerging threats. Moreover, existing solutions typically suffer from an inherent trilemma, i.e., a constant trade-off among runtime efficiency, contextual precision, and adaptability. To bridge this gap, we propose Continuous Agents for Injection Threats via Lifelong Yielding Nexus (CAITLYN), an agent-agnostic defense middleware. CAITLYN integrates two systems. System I focuses on immediate defense against existing attacks using a two-tiered library: Tier-0 for rule-based detection scripts and Tier-1 for optimized LLM-based accurate inference. System II, in contrast, is deployed to monitor po

---

### [6] H-Scale: Hessian-Guided Scale Refinement for NVFP4 Sub-Byte LLM Inference

**链接**: https://arxiv.org/abs/2608.28113
**作者**: Hao Yu, Zheng Li, Dayiheng Liu, Jianwei Zhang
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The NVIDIA Blackwell architecture, with native support for the ultra-fine-grained NVFP4 format, opens new opportunities for accelerating large language model (LLM) inference. NVFP4's micro-block design, such as a group size of 16, offers strong representational flexibility for capturing local weight distributions and isolating outliers, but it also introduces a large and highly sensitive space of per-group scaling factors. Existing post-training quantization (PTQ) methods primarily focus on refining quantized weight values, leaving this scale-selection step underexplored. To address this gap, we propose \textbf{H-Scale}, a lightweight post-processing method for NVFP4 per-group scale refinement. Instead of minimizing plain weight reconstruction error, H-Scale selects hardware-valid group scales using a diagonal second-order proxy derived from calibration activations, thereby targeting layer output perturbation more directly. It is designed as a drop-in replacement for RTN-style scale se

---

### [7] LLM-Based Agents for Software and Systems Security: Approaches, Applications, and Assessment

**链接**: https://arxiv.org/abs/2608.28490
**作者**: Jingjing Nie, Jiawei Guo, Krishna Meda, and Haipeng Cai
**来源**: cs.CR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Software and systems security workflows are typically procedural: analysts inspect heterogeneous artifacts, form hypotheses, invoke tools, interpret outputs, and revise plans. Large language model (LLM)-based agents, which can plan, use tools, retain state, and revise actions across multi-step workflows, are being rapidly adopted to automate this work. Given the consequences of delegating security decisions to autonomous systems, understanding how such agents are built, used, and assessed is crucial. Yet to this date, there remains a lack of systematic understanding of what has been done and how far we are in this field: the term "agent" is applied inconsistently, applications differ sharply in risk, and assessment protocols are often incomparable. To gain a comprehensive and coherent view of this area hence inform relevant future research, this paper provides a systematic literature review of the (1) technical approaches, including agent architecture, perception, memory, reasoning and

---

### [8] Characterization of Request and Token Energy Costs for LLM Inference Workloads on GPU Platforms

**链接**: https://arxiv.org/abs/2608.28044
**作者**: Prabhu Vellaisamy, Vanessa Lam, Shawn Blanton, and John Paul Shen
**来源**: cs.PF cs.DC cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference serving is priced by tokens, but GPU energy is consumed over inference windows. This accounting mismatch makes token-normalized metrics incomplete, since average output-token energy can decrease even when total request energy increases. We characterize this behavior with a decomposed energy model: a fixed one-time prefill with a fixed generation setup cost, while each output-token generation step adds marginal step energy. We evaluate this LLM inference energy model on NVIDIA H100 and H200 GPUs across dense and mixture-of-experts (MoE) models, reporting both request energy and token energy as functions of model type (M), phase (P), batch size (B), context length (C), and output length (N). For Llama-3.2-1B on H200 at batch-16 and context-4K, increasing output length from 10 to 512 tokens reduces token energy from 7.46 to 0.72 J/token while total batched inference-window energy increases from 1.19 to 5.93 kJ. Batching also reduces token energy, but t

---

### [9] Are LLM -Enhanced GNNs Privacy-Safe?

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.25727&hl=zh-CN&sa=X&d=3025912674556066578&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-wc3jyuFlqSf2fROrxxpGzd&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: L He, Z Wen, C Li, S Su - arXiv preprint arXiv:2608.25727, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To fill this gap, we conduct a systematic study of privacy risks in LLM -enhanced GNNs. As illustrated … We construct 42 LLM -enhanced GNN victim models by combining multiple LLM -based … The results show that LLM -induced semantics can

---

### [10] Layered LLM Defenses as an Ensemble: Access Tiers, Inference Cost, and the Measured Failure Correlation Between Defense Layers

**链接**: https://arxiv.org/abs/2608.28327
**作者**: Abrar Alotaibi, Muhammad Shahid Jabbar, Sadam Al-Azani and Moataz Ahmed
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practitioners defend large language models (LLMs) by stacking defenses, assuming the layers compound. A stack is an ensemble, and ensembles compound only under a condition the LLM security literature recommends but never measures: the members must fail on different inputs. Two instruments make that measurable. The Adversary Access-Tier Model (AATM) grades an adversary by the access it holds, from system-only (A0) to influence over training data (A4). A cost model sorts defenses into five classes of inference-time overhead; because two classes require training weights or reading activations, they tier the defender as AATM tiers the adversary. From these we derive how a stack behaves, and the quantities a defender cares about diverge: coverage saturates within a tier, cost rises by class, false refusals accumulate as a union, and residual attack success falls multiplicatively only under independence. We measure that independence. Running one adaptive adversary against a seven-layer stack

---

### [11] Not to Break, but to Attest: Adversarial Probes for Privacy-Preserving LLM Verification

**链接**: https://arxiv.org/abs/2608.27954
**作者**: Cameron Wilding, Mina Shaker, Fatemeh Ganji
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-deployment changes to large language models can alter behavior while leaving routine outputs largely unchanged, creating a challenge for AI governance when model weights are proprietary. We present a privacy-preserving zk-SNARK-based audit framework that searches for probes designed in the spirit of adversarial examples to amplify logit drift between an approved model and a modified deployment. Our framework explores complementary probe families under different access models. Token-based probes operate in a black-box setting and require only the input interface, tokenizer, and vocabulary. Embedding-based probes require gray-box access to the embedding interface. Stress probes rely on additional interface capabilities but do not require full white-box access to model weights or architecture. This range allows probe selection to balance sensitivity, access requirements, and deployment cost. We evaluate probe constructions across LLM architectures, model-tampering scenarios represent

---

### [12] TACIT-Switch: Cost-Aware Model Escalation for LLM Agents from Censored Supervision

**链接**: https://arxiv.org/abs/2608.27911
**作者**: Ji'an Lei and Jian Huang
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents with smaller language-model backbones are less expensive but can drift into persistent failure modes, whereas those with larger backbones are generally more reliable but more costly. This reliability-cost trade-off motivates routing methods that decide when to invoke an agent with a larger backbone: before execution, after a fixed trajectory prefix, or locally at individual steps. Our method, TACIT-SWITCH, learns permanent handoff policies from accumulated trajectory evidence and Teacher-Annotated Censored Intervention Times (TACIT). It represents each annotation as an interval-censored observation on a cumulative-risk scale. The resulting mixture-cure threshold model estimates the probability that the paired Strong rollout succeeds and, conditional on success, the handoff threshold; no teacher is required at deployment. In a mechanism-based multi-step simulation, TACIT-SWITCH improves success by 7.4-11.1 percentage points over task-level, step-level, and fixed-prefix routing ba

---

### [13] Benchmarking large language model agent societies against human behavioural distributions

**链接**: https://arxiv.org/abs/2608.28182
**作者**: Raad Bin Tareaf
**来源**: physics.soc-ph cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Populations of large language model agents are increasingly used as experimental societies. Three doubts shadow every such result: whether the agents behave like the humans they stand in for, whether a finding survives changes to the apparatus that leave the rules untouched, and whether apparent social dynamics are interaction at all rather than the reproduction of experiments the models have read. This article introduces SILICA, an open instrument that tests all three. Five environments carry published human anchors, each paired with perturbations that re-render the same rules and with variants whose payoffs point away from the memorised result. Twelve open-weight models were run through it on a single consumer graphics card. Agreement with human data is confined to starting points: first-round public-goods contributions fall inside the equivalence margin for eight of eleven models, while no model matches end-state contributions or the human corridor of cooperation. Merely swapping th

---

### [14] Understanding Evolution Strategies for LLM Reasoning: Broader Reasoning Coverage than GRPO

**链接**: https://arxiv.org/abs/2608.27351
**作者**: Yunpeng Ba, Zhi Zheng, Yue Xie, Jiaqing Li, Xialiang Tong, Tao Zhong 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [15] MaCoPlanner: LLM-Assisted Manual-Compiled Task Planning with Proactive Safety Verification for Robotic Industrial Panel Operation

**链接**: https://arxiv.org/abs/2608.28300
**作者**: Guipeng Xin, Jiahe Xua, Mohammad Deghat, Chenhui Wan, Jie Liu, Youmin Hu 等 (7 人)
**来源**: cs.RO cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robotic industrial panel operation requires not only accurate control localization but also compliance with operating procedures, safety rules, and device-state constraints distributed across heterogeneous manuals. This study presents MaCoPlanner, a task-planning framework built on knowledge compiled from equipment manuals that converts equipment manuals into a typed intermediate representation, retrieves task- and state-relevant evidence, and uses it to support plan generation. Before actuation, candidate plans are symbolically rolled out and checked against procedural and state-transition constraints; detected violations are localized and returned for targeted repair, while unresolved plans are rejected. A separate execution interface grounds verified symbolic actions to physical controls and updates the device state. Under an independent evaluation oracle, MaCoPlanner achieves a final violation rate of 2.7%, and 26.3% of the runs in the repair analysis are rejected after exhausting 

---

### [16] Expert Knowledge & Machine Understanding: Bridging Reactome's Ontology with LLM Semantic Embeddings

**链接**: https://arxiv.org/abs/2608.28178
**作者**: Susanna Bravi, Riccardo De Luca, Rosa Sicilia, Christine Nardini, Mario Santoro
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biological knowledgebases like Reactome provide high-quality pathways that include biological elements' relationships and textual descriptions (metadata). The quality of such pathways is granted by manual curation, that presents, however, significant scalability challenges. Lately, numerous NLP tools have been proposed to cope with this issue, leveraging textual information to automatically expand biological knowledgebases. However, little exploration has been done so far to assess whether relationships among textual descriptions mirror higher order biological relationships. This study explores whether human-written descriptions in Reactome can be used to infer the experts' defined global hierarchical structure. To test this, we extracted from Reactome the Homo Sapiens hierarchy of pathways and their reactions (Reactome Hierarchy), and used textual metadata to reconstruct a Semantic Hierarchy, combining a sentence transformer model (SPECTER2) with a modified agglomerative nesting algor

---

### [17] Coverage, Not Credit: Failure-Credit Routing of Zeroth-Order Perturbation Budgets Does Not Improve On-Pool Sample Efficiency for LLM Agents

**链接**: https://arxiv.org/abs/2608.28011
**作者**: Yuxu Ge
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Trajectory-level credit assignment can localize which module of a tool-using LLM agent causes failures using only verifiable signals. We ask whether such failure credit should route a fixed zeroth-order/evolution-strategies (ZO/ES) perturbation budget. Across a synthetic environment and frozen Qwen2.5-1.5B/3B and SmolLM2-1.7B agents, three task families, six allocation schemes, a credit-noise sweep, paired seeds, and exact sign-flip tests, we find no statistically detectable improvement over uniform allocation in any on-pool comparison (no gain of at least 2 percentage points). The joint soft-plus-sigma scheme is equivalent to uniform within a +/- 0.02 AUC margin on 1.5B and 3B; concentrating the full budget on the credit argmax is marginally equivalent on 1.5B, where that module is the verified bottleneck, and significantly worse on 3B. Inverse-propensity debiasing does not rescue routing, and misrouting costs up to -0.074 AUC in-house and -0.118 end-to-end on the BFCL-derived family.

---

### [18] Ladders in Chaos: When, How, (and Perhaps Why) Does Test-Time Scaling Improve LLM Machine Translation

**链接**: https://arxiv.org/abs/2608.28496
**作者**: Di Wu, Sergey Troshin, Christof Monz, Antske Fokkens, Vlad Niculae
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Two forms of test-time scaling for Large Language Models (LLMs) have emerged as effective and widely adopted paradigms: sequential, in which later answer attempts depend on earlier ones, and parallel, such as i.i.d. sampling with reranking. In this study, we investigate their properties in translation. First, our study shows that sequential sampling has a higher performance ceiling, providing a more diverse and effective pool of samples, particularly under smaller sampling budgets. Second, we interrogate the nature of test-time scaling through a multidimensional manual analysis. Human analysis of the Best-of-$N$ translations demonstrates that sequential sampling substantially improves translation fluency and naturalness, but can degrade accuracy when inference budgets are large. Finally, we suggest an explanation of the mechanism through which sequential scaling improves machine translation. Our controlled analysis partially attributes the success of sequential self-improvement to the 

---

### [19] Rater choice determines measured fidelity: a multi - model evaluation of large language model raters for AI-generated plain- language biomedical summaries

**链接**: https://scholar.google.com/scholar_url?url=https://www.researchsquare.com/article/rs-10822636/latest.pdf&hl=zh-CN&sa=X&d=5566012000519533937&ei=b0aVauDVC6-D6rQP3_3SsA8&scisig=AIVdB-wb-MULfd1tp62ERs-qKtPO&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=0&folt=kw-top
**作者**: A Kishore¹
**来源**: 2026
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models are increasingly used to produce plain- language summaries of biomedical research and are also being … Writing summaries by hand is a slow process which is why large language models (LLMs) are increasingly

---

### [20] EvoUndo: Recoverability-Constrained Self-Evolution for LLM Agent Harnesses

**链接**: https://arxiv.org/abs/2608.28363
**作者**: Tanmay Sah, Dolly Sah, Harshul Jain, Tanya Sah
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly modify their own prompts, tools, middleware, resources, and execution harnesses at runtime. Such self-evolution can improve capability, but a successful mutation may leave persistent effects that cannot be safely reversed in states different from the one in which it was created. We introduce EvoUndo, a framework for representing, synthesizing, diagnosing, and independently verifying recoverability of model-generated self-modifications across counterfactual states. Across 600 unseen one-shot self-evolution tasks, we identify 197 capability-improving mutations that fail recoverability verification. Under the original recovery representation, conventional repair strategies recover 0/197 of these natural failures. Deterministic oracle analysis recovers 48/197 under the original recovery language L0, while the extended recovery calculus increases empirical oracle recovery to 191/197. A protocol-locked 2x2 grounding-by-expressivity intervention then separates two bott

---

### [21] LLM Agents for Time-Series: A Survey

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.26226&hl=zh-CN&sa=X&d=3845613577564463095&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-wqVS5kBzDQ8kAALBlDWYsS&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: Y Chen, X Qin, C Liu, L Wu, NI Samia, K Ding - arXiv preprint arXiv:2608.26226 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> an LLM agent for time series as a system in which an LLM … LLM fills this role and as multi-agent when two or more LLMs take distinct decision-making roles and interact through cooperation, competition, or both. We exclude (i) one-shot prompting

---

### [22] The Autonomy Tax: Defense Training Breaks LLM Agents

**链接**: https://arxiv.org/abs/2603.19423
**作者**: Shawn Li, Yue Zhao
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Do LLM Agents Mirror Socio-Cognitive Effects in Power-Asymmetric Conversations?

**链接**: https://arxiv.org/abs/2605.17694
**作者**: Anvesh Rao Vijjini, Sagar Manjunath and Snigdha Chaturvedi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] A Method for Layer Bit-Width Allocation in LLM Quantization via Performance Maximization Under a Quality-Degradation Constraint

**链接**: https://arxiv.org/abs/2608.28003
**作者**: Artem Safronov
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper proposes a layer bit allocation method for Gemma-3-1B, formulating the problem as performance maximization (latency decrease) given a degradation budget constraint (allowable level of generation quality loss). This approach is different from time- and resource-consuming uniform layer quantization methods that are used in the literature (like GPTQ or AWQ) or allocation methods without proven performance-accelerating effect (like MixLLM or TorchAO). The layer sensitivity profile resulting from our prior work SA-PTQ is applied using the activation pass-through mode inside TensorRT-LLM. For each layer precision is determined individually in blocks, according to a grouping introduced in the prior step (5+5, 10+10, all26), differentiating the contribution of FFN, Attention, and lm_head to the overall speedup. The clock speed was measured for 13 W8A8 variants on an RTX 5090. We find that for FFN and lm_head the time cost of quantization/dequantization is compensated for by the use 

---

### [25] Regime-Aware Portfolio Management via Retrieval-Augmented LLM-Guided Expert Switching

**链接**: https://arxiv.org/abs/2608.28252
**作者**: Ahmad Asadi, Reza Safabakhsh
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial markets are inherently non-stationary, making the effectiveness of individual portfolio-management strategies highly dependent on changing market conditions. This work proposes a retrieval-augmented expert-switching framework that dynamically selects portfolio management experts based on their historical performance under similar market situations. A dual-stream variational autoencoder represents asset-level and market-wide information, while a retrieval-based knowledge base stores historical situations and expert performance. During inference, an instruction-tuned LLM reasons over the retrieved evidence to identify the most appropriate expert rather than directly generating portfolio actions. We further establish a monotonicity property showing that adding a locally superior expert cannot degrade the switching mechanism's performance. Experiments across cryptocurrency, stock, and foreign-exchange markets show that the proposed selector achieves the highest cumulative return 

---

### [26] Evaluating human and LLM screening workflows in a conceptually complex scoping review: Recall--workload trade-offs and run-to-run consistency

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.26885&hl=zh-CN&sa=X&d=16461584745048443107&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-xb6X_y088fIZ2cBBVpYqpo&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: N Figalová, L Huestegge, A Böckler-Raettig - arXiv preprint arXiv:2608.26885, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background. Large language models (LLMs) are increasingly used for screening in evidence synthesis, where false negatives can remove relevant studies before full-text assessment. We compared human and LLM title-and-abstract screening workflows

---

### [27] Compared to What? A Human-Anchored Security Benchmark for LLM-Generated Infrastructure-as-Code

**链接**: https://arxiv.org/abs/2608.28021
**作者**: Animesh Shaw
**来源**: cs.CR cs.AI cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used to author Infrastructure-as-Code (IaC), where a single insecure default can be deployed directly into production. Prior evaluations report raw vulnerability counts for model-generated IaC, but without a human baseline they cannot determine whether models are actually worse than engineers. We introduce GenIaC-SecBench, a benchmark of 100 deployment scenarios stratified by architectural complexity, evaluated across 12 model configurations from four vendors, producing 1,196 IaC artifacts scanned by three independent policy engines (Checkov, Trivy, KICS). Critically, we also scan 634 human-authored IaC templates with the same toolchain, providing the first size-matched human security baseline. Vulnerability density is strongly inverse to artifact size (Spearman $\rho = -0.55$, $p < 10^{-77}$), meaning unmatched comparisons measure size rather than security. When matched on declared-resource count, all model configurations fall within 3.21x--3.87x

---

### [28] Tracing the complexity profiles of different linguistic phenomena through the intrinsic dimension of LLM representations

**链接**: https://arxiv.org/abs/2601.03779
**作者**: Marco Baroni, Emily Cheng, Iria de-Dios-Flores, Francesca Franzon
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] LLM -augmented progressive search for efficient multi-robot task planning

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S147403462600861X&hl=zh-CN&sa=X&d=2196786318131261616&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-yoO73zLqG_qc5Ocz9QVKjw&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: L Xin, J Wang, W Yao, J Qi, Y Liu - Advanced Engineering Informatics, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> More specifically, the LLM policy is assisted by retrieval-augmented generation to progressively add actions, biasing the search toward … that the LLM adds feasible coordinating actions. Experimental evaluations indicate that RePS- LLM surpasses

---

### [30] A survey on LLM -enhanced reinforcement learning in financial markets

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s44163-026-02018-0&hl=zh-CN&sa=X&d=3599424680368445166&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-ysVHH7WloRvqQpo5PpWBgj&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: GH AL-Aldaffaie, A Taheri, A Farhadi, A Zamanifar - Discover Artificial Intelligence, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> The integration of Large Language Models (LLMs) with Reinforcement Learning (RL) for financial decision-making has grown rapidly in recent years, yet the literature remains fragmented and lacks systematic comparison across methods. In this survey

---

### [31] Curvature-Conditioned Multiscale Momentum with Sphere Constraints for LLM Pretraining

**链接**: https://arxiv.org/abs/2608.28442
**作者**: Shuchen Zhu and Yuxin Fang and Mingze Wang and Kun Yuan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretraining accounts for a large fraction of the total computational cost in LLM training. However, noise-dominant gradients and the highly ill-conditioned loss landscape bring severe challenges. Although modern adaptive optimizers such as AdamW and Muon have achieved great success in large-scale pretraining, their reliance on gradient normalization offers limited mitigation of the ill-conditioned curvature. The progress along flat directions (eigen-directions of small eigenvalues), which dominates the final loss reduction, remains relatively slow. To enhance training dynamics along flat directions, we propose a curvature-conditioned multiscale momentum method with sphere constraints, delivering steady acceleration in LLM pretraining. This multiscale momentum, applied only along flat directions, pairs a slow-decay component for noise reduction with a fast-decay component for rapid curvature adaptation, harnessing their complementary strengths. Crucially, we employ a sphere constraint t

---

### [32] LLM -Driven Location Completion and Test-Time Training for Next Location Prediction

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426030551&hl=zh-CN&sa=X&d=13103244199591757035&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-zy8mtWJigyAiC005kRk-zY&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: P Lan, E Yang, Y Liang, J Zhao, G Guo, H Zhao - Expert Systems with Applications 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Next location prediction aims to infer the next location users are likely to visit based on their historical check-in data. However, existing methods assume that check-in data is complete, overlooking the subjective nature of users’ check-in behavior

---

### [33] OpenStamp: A Watermark for Open-Source Language Models

**链接**: https://arxiv.org/abs/2608.27899
**作者**: Miroojin Bakshi, Saksham Rastogi, Danish Pruthi
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the growing prevalence of large language model (LLM) generated content, watermarking is considered a promising approach for attributing text to LLMs and distinguishing it from human-written content. A prominent class of techniques embeds subtle but detectable signals in generated text by modifying token sampling probabilities. However, such methods are unsuitable for open-source models, where users have white-box access and can easily disable watermarking during inference. In this work, we introduce OpenStamp, a watermarking technique that encodes the watermarking logic directly into the model weights by modifying only the final projection, or unembedding, layer. Through experiments across two models, we show that OpenStamp achieves superior detection performance, with minimal degradation in model capabilities compared to prior methods. The implanted watermark is explicitly designed, and empirically confirmed, to be more robust to paraphrasing attacks and harder to scrub off throu

---

### [34] SABER: Stability-Aware Early Exit for LLM Reasoning via Adversarial Branch Probing

**链接**: https://arxiv.org/abs/2608.27963
**作者**: Wanli Cheng, Haiya Xiang, Juntao Li, Hongling Wang, Wenliang Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Reasoning Models (LRMs) achieve strong reasoning capabilities, yet long-chain reasoning becomes inefficient once the intermediate answer stabilizes across reasoning steps: additional reasoning yields little marginal benefit while incurring substantial inference cost. Existing early-exit methods based on confidence or entropy poorly capture reasoning stability, while consistency-based approaches rely on multi-step trajectory agreement, requiring sequential evaluations that delay exit. To better balance efficiency and reliability, we propose SABER, a training-free framework for stability-aware early exit via adversarial branch probing. SABER constructs simple yet effective semantic perturbations around intermediate reasoning states to form adversarial branches, and applies lightweight probing to estimate their likely final outcomes without full trajectory rollouts. When the probed outcomes remain consistent across branches, SABER exits early; otherwise, it continues reasoning. Expe

---

### [35] APeB: Benchmarking Personalization Ability of Large Language Model Agents

**链接**: https://arxiv.org/abs/2607.03162
**作者**: Garry Yang, Zizhe Chen, Xinru Chen, Yongqiang Chen, Jianxiang Wang, Deyu Zou 等 (10 人)
**来源**: cs.AI cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Accelerating LLM Inference via Vector Index Based Output Embeddings

**链接**: https://arxiv.org/abs/2608.27460
**作者**: Martin Loretz, Sepp Hochreiter
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large output embedding matrices create a significant memory bandwidth bottleneck during autoregressive decoding, especially for compact LLMs with large multilingual vocabularies. We reformulate the output projection followed by top-k token selection as a maximum inner product search over token embeddings and replace the dense vocabulary projection with an HNSW-based vector index. The resulting output head retrieves only a small candidate set of high-scoring tokens and can be integrated into existing decoding pipelines by scattering retrieved logits into a sparse full-vocabulary tensor. On CPU inference with Gemma 3, Llama 3.2, and Qwen 3 models, our method substantially accelerates the output projection and improves end-to-end batch-size-one decoding throughput by up to 82% for Gemma 3 270M, while preserving generation quality under AlpacaEval evaluation. These results suggest approximate retrieval is a practical alternative to dense output projections in latency-sensitive small-batch 

---

### [37] ProfileFoundry: A Synthetic Person-Object Substrate for Privacy, Memory, and Tool-Use Evaluation in LLM Agent

**链接**: https://arxiv.org/abs/2606.26403
**作者**: Sriram Selvam, Anneswa Ghosh
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] Graphionale: How Graph Visualizations of LLM Rationales Affect Human Decision Making

**链接**: https://arxiv.org/abs/2608.27932
**作者**: Xinru Wang, Zhexuan Ma, Ming Yin, Shuai Ma, Thomas W Malone
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly equipped with augmented reasoning capabilities to generate rationales that support human decision-making. Yet these text-dense rationales often impose substantial cognitive burdens. Building on a formative co-design study that identified user preferences for non-linear reasoning representations, we developed Graphionale as a testbed for empirically studying argument-map-style rationale visualization. This system transforms linear LLM rationales into interactive, multi-level graphs. It explicitly structures logical relationships (e.g., conclusions, premises, support, and objections), while further extracting entities and relations within each statement to construct condensed node-link representations. We conduct a large-scale online user study (N = 204) to examine when graphical rationales are more effective than textual ones, across varying task modality (verbal vs. visual reasoning), rationale format (textual vs. graphical), and question d

---

### [39] Safety Does Not Compose: Non-Decaying Loop State for Autonomous LLM Agents

**链接**: https://arxiv.org/abs/2608.27141
**作者**: Chenhao Wu, Haoxuan Jia, Yang Liu, Yingguang Yang, Yuhan Lin, Chongyang Zhang 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] LLM-Augmented Causal Discovery: Probabilistic Fusion of Edge Existence and Orientation

**链接**: https://arxiv.org/abs/2608.27472
**作者**: Neville K. Kitson and Anthony Constantinou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bayesian network structure learning (BNSL) from observational data struggles with orientation identifiability, while large language models (LLMs) offer broad but often unreliable causal knowledge. We propose combining these complementary sources through a novel representation, termed Probabilistic Dependency Graphs (PDGs). In a PDG, each edge is associated with a distribution over directed, undirected, and absent states, enabling fusion via weighted averaging. We evaluate this approach on 26 benchmark networks, combining ensembles of three BNSL algorithms (FGES, Tabu, PC) with three LLMs (Gemini, Claude, GPT) across multiple prompts and random seeds. A simple 50/50 fusion improves F1 over the better of either source alone in 22 of 26 networks, with a statistically significant mean improvement of $0.056$ $(p<0.001)$. Analysis reveals that the two sources play complementary roles: BNSL contributes a high-recall edge skeleton (80\% vs 60\% for LLM), while LLM contributes accurate edge ori

---

### [41] Where should control sit? Reliability-cost trade-offs in delegating water distribution network optimisation to LLM agents

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0043135426014971&hl=zh-CN&sa=X&d=17032000822523021862&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-yh1KNi8AgM543lPADF_OWz&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: J Wang, S Liu, G Fu, D Savic - Water Research, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM agent, and which should remain deterministic workflow steps. This study quantifies the reliability and resource cost of delegating individual stages of a WDN optimisation pipeline to an LLM … for the reliable, reproducible and auditable LLM -driven

---

### [42] Meta-Prompt Optimization for LLM-Based Sequential Decision Making

**链接**: https://arxiv.org/abs/2502.00728
**作者**: Mingze Kong, Zhiyong Wang, Yao Shu, Zhongxiang Dai
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Auditing Generative Audio Calls for Known-Task Audio-LLM Evaluation

**链接**: https://arxiv.org/abs/2608.27817
**作者**: Mengzhe Geng
**来源**: cs.SD cs.CL eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech and audio LLMs are often evaluated by asking whether a waveform prompt beats an automatic speech recognition (ASR) transcript. For known closed-set tasks, that comparison conflates two factors: access to acoustic evidence and the need to call a generative audio model. We evaluate this distinction as a controlled call-decision problem. For each example, a policy chooses among keeping a transcript label, using encoder evidence from Contrastive Language-Audio Pretraining (CLAP), Audio Spectrogram Transformer (AST), or WavLM, and calling Qwen2-Audio, Qwen2.5-Omni, or MOSS-Audio; the decisive ablation removes all generative actions while keeping the selector and development protocol fixed. On VocalSound, transcripts reach 0.296 accuracy, so waveform information is needed. Yet supervised CLAP and WavLM controls reach 0.850 and 0.854 with no generative audio calls. A selector with generative actions reaches 0.925 accuracy using 12.5% calls, compared with 0.921 for the matched no-call s

---

### [44] The Instability of Safety: How Random Seeds and Temperature Expose Inconsistent LLM Refusal Behavior

**链接**: https://arxiv.org/abs/2512.12066
**作者**: Erik Larsen
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] Self-Generated Text Recognition: Quality Heuristics, Cross-Task Transfer, and Downstream Bias in LLM Evaluation

**链接**: https://arxiv.org/abs/2608.26159
**作者**: Jesse St. Amand, Callum Canavan, Sohaib Imran, Joseph Hewson, Aaron Lutz, Shi Feng 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] An LLM-Based Framework for Intent-Driven Network Topology Design

**链接**: https://arxiv.org/abs/2607.00292
**作者**: Kholoud El-Habbouli, Fen Zhou, Stephane Huet
**来源**: cs.NI cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Prompts Don't Protect: Architectural Enforcement via MCP Proxy for LLM Tool Access Control

**链接**: https://arxiv.org/abs/2605.18414
**作者**: Rohith Uppala
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] Rating the Raters: Rasch Measurement Theory for LLM Evaluation

**链接**: https://arxiv.org/abs/2608.27463
**作者**: Pratik S. Sachdeva and Nathan Boudol
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs now sit on every side of evaluation: as examinees scored on benchmarks, judges of other models' outputs, and raters of human-generated content. Each paradigm can be viewed as a measurement problem, where a latent property of an object is probed with items from an instrument (e.g., benchmark) by raters. Standard evaluation practices often neglect the contributions of each core component to the end result, limiting our understanding of what is being measured. Rasch measurement theory (RMT) is well-suited to this kind of problem. RMT decomposes ordinal ratings into separable facets on a common scale. It further provides a battery of diagnostics that can identify miscalibrated measurements and rater biases. We present a case study of RMT applied to the LLM-as-rater paradigm using the Measuring Hate Speech corpus, whose construct was itself built under RMT. We fit a series of many-facet Rasch models to annotations from nine LLMs spanning families and capability levels. Our analyses sho

---

### [49] Automated Analysis Framework for Multilingual Climate-Health Literature Based on Multi-Agent Large Language Model

**链接**: https://arxiv.org/abs/2608.27998
**作者**: Yuze Sun, Shihui Zhang, Jiancheng Pan, Yunjia Ye, Wentao Luo, Jiahao Li 等 (9 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid proliferation of interdisciplinary and multilingual scientific literature has left traditional manual analysis and single-algorithm methods plagued by low efficiency, poor scalability, and insufficient domain adaptability. Targeting the literature analysis needs of the typical interdisciplinary climate-health field, this study proposes a multi-agent large language model automated analysis framework for multilingual scientific literature, which realizes full-process automation covering literature screening, structured information extraction, and standardized integration. With a central coordination module as the core, the framework deploys three dedicated agents for document evaluation, information extraction, and analytical review to mimic the literature analysis thinking of domain experts, and adopts a four-layer hallucination control strategy together with a manual verification procedure to ensure the accuracy and reliability of analytical outcomes. Validated on a bilingual

---

### [50] Beyond Task-Only Matching: Personalized Skill Routing with Counterfactual Evaluation

**链接**: https://arxiv.org/abs/2608.28241
**作者**: Tianle Wang, Yanghe Zou, Xiang Liu, Ziyao Huang, Chenchen Fu, Weiwei Wu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid expansion of reusable skill repositories makes skill routing a critical capability for large language model (LLM) agents. Existing methods treat routing as task-only semantic matching. However, when users with incompatible constraints issue an identical request, this assumption conflates task relevance with skill suitability: a task-only router can select a semantically plausible skill that is unsuitable for the requesting user. To expose this failure mode, we formulate \textit{personalized skill routing} as profile-conditioned retrieval, in which relevance depends jointly on the task and the user profile. We first introduce a profile-counterfactual benchmark, in which the task is held fixed while changes in the user profile induce changes in the reference skill. We further construct paired counterfactual supervision and propose SkillFeed, a progressive retrieve-and-rerank framework that first establishes task--skill alignment and then learns profile-conditioned discriminatio

---

### [51] Pick and Spin: Cold-Start-Aware Routing for Self-Hosted LLM Serving

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11662462/&hl=zh-CN&sa=X&d=505379875228545788&ei=b0aVauDVC6-D6rQP3_3SsA8&scisig=AIVdB-wV4OpyKEJCDNsvSJ29QjRa&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=3&folt=kw-top
**作者**: BP Vangala, T Malik - 2026 IEEE 19th International Conference on Cloud …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract—Self-hosting multiple large language models on private or hybrid cloud infrastructure is increasingly appealing for organizations … and FrugalGPT select models but ignore whether those models are warm or cold. We present Pick and

---

### [52] Hydra: Phase-Aware Workload Characterization of LLM Inference across Edge SoC Generations, Backends, and Quantization Levels

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.25053&hl=zh-CN&sa=X&d=1926187834564682382&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-wM9yI8aFIg9Rc_fJStxNJe&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: A Taherin, ST Anvari, C Amante, Y Chen, R Noroian… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract—Edge LLM deployment is shaped by more than model size and precision: … We present Hydra, a common-schema, phase-aware workload characterization framework for LLM … reproducible, phase-aware characterization

---

### [53] Spatial-Semantic Reasoning using Large Language Models for Efficient UAV Search Operations

**链接**: https://arxiv.org/abs/2608.28270
**作者**: Marin Maletic, Marijana Peti, Tamara Petrovic and Stjepan Bogdan
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a real-time semantic navigation framework for Unmanned Aerial Vehicles (UAVs) focused on improving time efficiency in the Object Goal Navigation (ObjectNav) task. Central to our approach is a Large Language Model (LLM) that interprets user-provided natural language instructions and performs semantic reasoning over detected objects and spatial context to prioritize high-probability search regions. The system combines real-time object detection, 3D spatial mapping, and polynomial spline interpolation for smooth and feasible UAV trajectory planning. Unlike prior methods that rely on offline reasoning or simulator-constrained action spaces, our framework can operate in real time, continuously updating semantic relevance based on new observations. Experiments in both simulated and real-world settings demonstrate reductions in mission duration while maintaining high search accuracy, underscoring the effectiveness of LLM-guided reasoning for time- efficient UAV-based ObjectNav.

---

### [54] GRACE:Gradient-guided Coreset Selection for LLM Unlearning

**链接**: https://arxiv.org/abs/2608.28361
**作者**: Praveen Bushipaka, Andrea D'Angelo, Lucia Passaro, Tommaso Cucinotta
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine Unlearning methods for Large Language Models typically assume pre-specified forget and retain sets. In realistic settings, however, requests may provide only a few examples of undesired behavior, requiring forget and retain sets to be inferred from heterogeneous corpora. We study this data-selection problem and propose GRACE , a gradient-guided coreset selection method that constructs both forget and retain sets for LLM unlearning. GRACE first computes a forget direction from seed examples that elicit the undesired behavior, then selects a compact forget coreset whose gradients approximate this direction using non-negative orthogonal matching pursuit. To preserve model utility, it selects retain examples after projecting out the forget direction and applying clustered orthogonal matching pursuit in the remaining gradient space. Across two target domains, two model families, and four unlearning algorithms, GRACE improves model utility while maintaining comparable forget quality,

---

### [55] LLM -Assisted Translation for Korean OTT Content Localization: A Literature Review on Productivity, Quality, and Human–AI Collaboration

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2078-2489/17/9/835&hl=zh-CN&sa=X&d=14827192697084762415&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-xVao3e0i2nuTkPdlTOvPmN&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: S Lee - Information, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> in isolation, namely LLM translation quality and automatic … that LLM -based post-editing improves draft quality and productivity, but that honorific register, culture-bound expressions, and speaker-relational meaning, all pervasive in Korean dialogue, lie

---

### [56] SymboLLM-FE: LLM-Accelerated Symbolic Regression for Automated Feature Engineering on Tabular Data

**链接**: https://arxiv.org/abs/2608.28408
**作者**: Zi-Jian Cheng, Zi-Yi Jia, Zhi Zhou, Yu-Feng Li, Lan-Zhe Guo
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular data, as a core data format in machine learning, often lacks the discriminative power needed for high-performance modeling due to insufficient feature informativeness. Automated Feature Engineering (AutoFE) overcomes this by automating feature generation and selection, ensuring both model performance and operational efficiency. However, traditional AutoFE often yield features with poor interpretability because they rely on blind mathematical transformations, while large language models (LLM)-based AutoFE faces challenges in requiring costly multi-round iterations to generate high-utility features to effectively enhance model performance, compounded by inherent risks of bias and hallucination. In this paper, we combine symbolic regression with LLMs for feature engineering (SymboLLM-FE) to solve these challenges. We extract mathematically expressive formulas strongly correlated with the target via symbolic regression, which can enhance model performance, then refine them by LLMs 

---

### [57] Agentao: A Policy-Governed Runtime Harness for Embeddable Tool-Using LLM Agents

**链接**: https://arxiv.org/abs/2608.13574
**作者**: Bo Jin, Qiang Jiao, Xin Tong
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] Auditing LLM Benchmarks with Item Response Theory

**链接**: https://arxiv.org/abs/2605.30504
**作者**: Sander Land, Daniel M. Bikel
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] NL2AGBench: Benchmarking LLM Auto-Formalization for AlphaGeometry

**链接**: https://arxiv.org/abs/2608.28481
**作者**: Samuel Xiao, Judy Song, Rory Hu, Ziliang Zong
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) have demonstrated strong capabilities in natural language understanding and mathematical reasoning. However, their ability to translate informal mathematical problems into formal representations remains underexplored. This limitation is particularly important for neuro-symbolic geometry systems such as AlphaGeometry, whose theorem-proving engine requires inputs in a specialized domain-specific language (DSL). Although AlphaGeometry achieves near-IMO gold-medalist performance, manually converting natural-language problems into its formal syntax remains a significant usability bottleneck. To address this challenge, we introduce the Natural Language to AlphaGeometry Benchmark (NL2AGBench), which evaluates LLMs in translating English geometry problems into AlphaGeometry-compatible formal representations. NL2AGBench uses execution-based verification within AlphaGeometry to assess translation quality rather than relying solely on textual simila

---

### [60] Speculative Probing: LLM Monitoring at Speculative-Decoding Cost

**链接**: https://arxiv.org/abs/2608.28099
**作者**: Collin Zhang, Tingwei Zhang, Vitaly Shmatikov
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-time classification during language model inference is valuable for safety filtering, behavioral analysis, and model monitoring, but current approaches force a trade-off between accuracy and efficiency. Hidden-state probes are fast but limited: they are either not context-aware: operating on a single vector and cannot model interactions across positions; or they are very costly: having dedicated classifier models (Llama Guard, Qwen Guard, LLM-as-judge) or performing computation on hidden states for all tokens and then pooling the results (MultiMax). This shows an intrinsic trade-off between efficiency and accuracy. However, we find that the speculative-decoding module in recent LLMs can be repurposed for efficient high-quality classification. By appending a trained soft prompt at the end of the target sequence, we can repurpose the speculative-decoding module into a sequence classifier. At inference time in a speculative-decoding pipeline, the KV cache is already in GPU memory, so

---

### [61] How Proper Scoring Rules Shape LLM Forecasting

**链接**: https://arxiv.org/abs/2608.28482
**作者**: Benjamin Turtel, Paul Wilczewski, Kris Skotheim, Ville A. Satop\"a\"a, Philip E. Tetlock
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper evaluates how reward function choice shapes the performance and behavior of LLM forecasters. We compare five proper scoring rules as training objectives for binary forecasts of resolved real-world events. Although the rules share the same theoretical incentive for truthful probability reporting, the resulting models differ in calibration, probability use, and estimated profiles of bias, information, and noise, with smaller differences in aggregate accuracy and discrimination. The Brier-trained model has the lowest observed Brier score and highest AUC-ROC, while the log-trained model has the highest observed log score and lowest calibration error. Models with similar aggregate performance also reach that performance through different combinations of bias, information, and noise. Proper scoring rules therefore need not behave interchangeably as training objectives. Reward choice may shape not only how well an LLM forecasts, but how its forecasting errors are structured. Each c

---

### [62] VICT: Verifier-Instrumented Credit Tracing for Long-Horizon LLM Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2608.28128
**作者**: Pengcheng Li, Zhengyang Zhang, Dongxu Zhang, Sui Huang, Shaohua Ma
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-grained credit assignment is a central challenge in reinforcement learning for long horizon LLM agents. Standard objectives often train from programmatically verifiable terminal rewards by broadcasting each sparse outcome to every action in a trajectory. Existing methods typically seek finer credit from the rollout side, constructing auxiliary trajectory signals or additional comparisons to estimate action importance. Although useful, these approaches still treat the verifier that judged success as a scalar reward, discarding its internal task structure. Our key insight is that many verifiable tasks already encode the relevant checks inside their terminal verifier. We propose VICT (VerifierInstrumented Credit Tracing), a training-time interface that exposes executable or evidence backed atoms and traces them back to actions through dependency-valid proof edges. VICT redistributes group-relative advantage only along those edges, shifting credit assignment from rollout-side inferenc

---

### [63] CASPER in the Machine: Insights into Character Variety in LLM-Generated Stories

**链接**: https://arxiv.org/abs/2606.22454
**作者**: Anneliese Brei, Abhisheik Sharma, Nicholas Sanaie, Lu Wang, Snigdha Chaturvedi
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] SURE-Challenge: Evaluating Speech Evidence Before Speech-LLM Generation

**链接**: https://arxiv.org/abs/2608.27783
**作者**: Mengzhe Geng
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech LLMs are usually graded after they answer, although an operating system first has to decide whether a waveform should be sent to the model. We define the Speech-Unsupported Rejection Evaluation Challenge (SURE-Challenge) for this admission step. The benchmark pairs LibriSpeech-derived transcription and first-word question answering with unsupported silence, colored noise, synthetic tones, and source-ambiguous babble under disjoint source splits. Front-end ablations use Qwen2-Audio; the selected energy-plus-Whisper-score rule is then replayed before six speech/audio LLMs. On the 474-row leakage-screened SURE-Extended test set, raw Qwen2-Audio rejects 15/204 unsupported inputs, whereas the fixed rule rejects 196/204 and leaves supported accuracy unchanged. External checks delimit this number: Common Voice retention drops as the Whisper-score threshold is tightened, and no-speed babble gives 18 to 24 rejected clips out of 54 across regenerated seeds. The result identifies a pre-gen

---

### [65] HyQuant: Hybrid-Precision Quantization for LLM Attention

**链接**: https://arxiv.org/abs/2608.27875
**作者**: Jiatong Ding, Bingxin Xing, Yu Zhang, Dian Ding, Xiaodong Yi, Xianbin Ouyang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantization has been widely adopted in LLM training and inference to reduce cost and improve efficiency. However, low-bit quantization of the \emph{attention} module often introduces large errors at very low bit-widths, causing performance degradation. Existing methods mainly rely on smoothing techniques to handle outliers, while we propose a hybrid quantization design to better balance accuracy and efficiency. Specifically, we propose \textbf{HyQuant}, an efficient hybrid quantization framework for LLM attention. HyQuant quantizes most attention states into low-bit formats while retaining a small set of vertical-line tokens and local-window states in high precision. These accuracy-critical regions are selected using lightweight vertical-line-aware attention-pattern signals, reducing quantization error with limited overhead. In the Prefill stage, HyQuant uses a hybrid-precision quantized attention operator that preserves vertical-line tokens and a local sliding window in full precisio

---

### [66] Select, Don't Train: The Benefits of Modular Entity Disambiguation with LLM-Based Selection

**链接**: https://arxiv.org/abs/2608.27470
**作者**: Fina Polat, Daniel Daza, Pengyu Zhang, Klim Zaporojets, Paul Groth
**来源**: cs.CL cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Entity Disambiguation (ED) is a key task for constructing and using knowledge graphs. State-of-the-art neural approaches commonly model ED as a single task, although it consists of two distinct subproblems: retrieving candidate entities and selecting the correct one given context. Dual-encoder models optimize for both within a shared embedding space, forcing representations to balance high-recall retrieval with fine-grained selection, and they require trained retrievers, which are costly to maintain as knowledge graphs change. While recent work has begun to combine retrievers with LLM-based selectors, the interplay between the two stages has not been studied systematically. In this paper, we present a systematic comparison of retrieval strategies for candidate generation under a shared LLM-based selection stage, combining sparse retrieval (BM25), Web KB search, and a state-of-the-art trained dense retriever with several open- and closed-source LLMs. We show that, once selection is dele

---

### [67] TokenPilot: Cache-Efficient Context Management for LLM Agents

**链接**: https://arxiv.org/abs/2606.17016
**作者**: Buqiang Xu, Zirui Xue, Dianmou Chen, Chenyang Fu, Chiyu Wu, Caiying Huang 等 (10 人)
**来源**: cs.CL cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [68] Evaluating Inference-Time Defenses Against Package Hallucination in LLM -Generated Code

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.22652&hl=zh-CN&sa=X&d=11274685721257387181&ei=bkaVaqGpNL686rQPvvDt6A0&scisig=AIVdB-wnIJr3-XW4curTvW3f1M6p&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: AE Djire, IE Olatunji, M Tessa, ET Barr, J Klein… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLMs are increasingly used for code generation, yet they frequently hallucinate non-existent software packages, creating exploitable entry points into the software supply chain. We make four contributions to this problem. First, we show that prior evaluation

---

### [69] Benchmarking LLM-as-a-Judge for Long-Form Output Evaluation

**链接**: https://arxiv.org/abs/2606.01629
**作者**: Junjie Chen, Yuxi Dong, Haitao Li, Weihang Su, Yujia Zhou, Min Zhang 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] ContextLeak: Exfiltrating LLM Agent Context via Malicious Tools

**链接**: https://arxiv.org/abs/2608.27800
**作者**: Yuqi Jia, Ruiqi Wang, Patrick Li, Yuepeng Hu, Peinian Li, Neil Gong
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Exfiltrating an LLM agent's runtime context -- such as the user prompt, execution trajectory, and tool list -- poses severe security and privacy risks to users. Such attacks can be carried out via malicious tools and typically require three conditions: (1) the agent selects the malicious tool for task execution, (2) the agent passes its runtime context as input arguments to the tool, and (3) the tool's implementation transmits these inputs to an attacker-controlled endpoint. Existing work primarily focuses on conditions (1) and (3), leaving condition (2) largely unexplored, despite its critical role in enabling successful context exfiltration. In this work, we bridge this gap by developing ContextLeak, a malicious tool attack that induces the agent to both select the tool and disclose its context as input arguments. We realize this attack by carefully crafting the tool's name and description using reinforcement learning. Specifically, ContextLeak employs an LLM, referred to as the atta

---

### [71] Parser States Already Know: Structure-Conditioned KV Persistence for Structured Generation

**链接**: https://arxiv.org/abs/2608.28276
**作者**: Linze Wu, Xinrui Chen
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Structured generation underpins large language model (LLM) agents that produce JSON, SQL, and function calls, where a single wrong field can cause the downstream action to fail. Constrained decoding already tracks parser transitions to enforce formal validity, and these transitions expose how generated tokens participate in schema-critical decisions such as required fields, arguments, and structural boundaries under the active grammar. Existing KV compression largely leaves this task-relevant structural signal unused. We introduce PASK (Parser-Aware Structural KV Persistence), which turns parser-derived structure into layer-group-specific KV persistence decisions. PASK addresses the mismatch between model-side KV sensitivity and task-level structured risk by using task-error sensitivity to set minimum protection floors and attention-output distortion to allocate residual KV capacity. An offline calibration stage compiles these signals into a persistence policy, leaving only lightweight

---

### [72] Beyond Output Correctness: Benchmarking and Evaluating Large Language Model Reasoning in Coding Tasks

**链接**: https://arxiv.org/abs/2604.12379
**作者**: Yuangang Li, Justin Tian Jin Chen, Ethan Yu, David Hong, Iftekhar Ahmed
**来源**: cs.SE cs.AI cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [73] Gen-TAS: A Generative AI-Aided Hardware-Software Task Allocation Framework for FPGA-GPP Heterogeneous Systems

**链接**: https://arxiv.org/abs/2608.28160
**作者**: Mary Kong, Yuqin Zhao, Semih Vazgecen, Cristian Sestito, Themis Prodromakis
**来源**: cs.AR cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> FPGA-GPP heterogeneous systems combine software flexibility with the performance and energy efficiency of reconfigurable hardware. However, determining which application tasks should execute on the GPP or FPGA requires extensive expertise and design-space exploration, particularly when user objectives vary across latency, communication, resource utilisation, and power. This paper proposes Gen-TAS, a knowledge-grounded LLM framework for user-specific FPGA-GPP task allocation. By combining task-graph analysis with RAG, Gen-TAS grounds LLM reasoning in historical implementation knowledge and generates multiple explainable strategies tailored to the specified objectives. Human-in-the-loop selection and a deterministic backend connect LLM-generated decisions to reproducible FPGA SoC implementations. Experiments on CNN and SDR workloads across multiple LLMs demonstrate stable, requirement-driven allocation. Under latency-oriented objectives, implementations following the selected strategies 

---

### [74] A Multi - Model Framework for Autonomous Schema Discovery and Hybrid Natural Language Generation-Driven Augmented Business Intelligence

**链接**: https://scholar.google.com/scholar_url?url=http://bright-journal.org/Journal/index.php/JADS/article/download/1479/702&hl=zh-CN&sa=X&d=6908865876970457017&ei=b0aVauDVC6-D6rQP3_3SsA8&scisig=AIVdB-wSsmQQ8SozYWdhbb-FvwG_&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=1&folt=kw-top
**作者**: R Permana, S Defit, GW Nurcahyo - Journal of Applied Data Sciences, 2026
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In response, recent studies have investigated the application of Large Language Models (LLMs) for advanced schema inference and automated generation of transformation logic. Frameworks incorporating LLM-enhanced data mapping within

---

### [75] When Evidence Shapes Collaboration: Knowledge-Conditioned Topology Generation for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2608.27984
**作者**: Yangxiao Jiang, Jiarun Fan, Mingcong Xu, Yanxi Guo, Jiwen Feng, Shanqing Xu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-Agent Systems (MAS) have recently moved from static workflows toward dynamically generated collaboration topologies. However, existing topology generation methods rely primarily on the parametric knowledge of large language models, with external search or retrieval used only as a reactive tool rather than an explicit determinant of collaboration structure. This leads to structure-knowledge misalignment, where systems exhibit redundant interactions or insufficient verification in knowledge-intensive tasks. We propose K-GAT (Knowledge-Guided Agent Topology Generator), a neuro-symbolic framework that formulates collaboration topology design as a knowledge-conditioned structure learning problem, integrating external evidence directly into autoregressive graph generation. Extensive experiments on knowledge-intensive benchmarks demonstrate K-GAT's efficiency and effectiveness: notably on the expert-level GPQA dataset, K-GAT outperforms the LLM-Debate baseline by a substantial margin of

---

### [76] EvoHarmBench: Breaking Content Moderation with Iterative Human-Like Evasion

**链接**: https://arxiv.org/abs/2608.27844
**作者**: Ruijie Jian, Benlei Cui, Ting Ma, Haidong Ding, Kangwei Liu, Ziwen Xu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing evaluations of harmful content detection rely predominantly on static benchmarks, which struggle to reflect the interactive adversarial ecosystem of real-world content platforms where users continuously revise their expressions in response to moderation feedback. This mismatch creates a significant performance gap between offline benchmark scores and online deployment effectiveness. To the best of our knowledge, we present EvoHarmBench, the first dynamic adversarial evaluation framework for content moderation systems. The framework employs an iterative optimization loop that evolves evasion strategies at the semantic-cluster level, while simultaneously optimizing for evasion success and human readability. We systematically evaluate LLM-based defense models which are widely used in real world moderation systems. The evaluation covers 229 semantic sub-clusters across five violation categories, derived from 5,002 real-world adversarial samples collected from content platforms. Ou

---

### [77] PersonaEdit: Representative Sample Selection for Personalized Model Editing

**链接**: https://arxiv.org/abs/2608.27816
**作者**: You-Mei Huang, Chung-Chi Chen, An-Zi Yen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalization has attracted growing interest in LLM applications, yet existing retrieval-based approaches depend heavily on retrieval quality and degrade in long-term interactions. Model editing, which directly modifies internal model parameters to incorporate new knowledge, has demonstrated effective knowledge modification capabilities in factual knowledge editing tasks and may provide a potential solution for personalization. However, scaling model editing to personalization is non-trivial. Editing large amounts of user data increases computational cost and causes interference among edits, motivating the need for effective sample selection. To address this issue, we propose, PersonaEdit, a hidden representation clustering strategy that selects representative editing samples through proportional stratified sampling. Experiments show that model editing is effective for personalization, and that our selection strategy preserves most of the performance while substantially reducing the 

---

### [78] A Unified Framework to Elicit Structured Feedback for Interpretable Multi-Trait Essay Scoring

**链接**: https://arxiv.org/abs/2608.28407
**作者**: Shihang Yang, Sanwoo Lee, Ningning Zhao, Yunfang Wu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-trait Automated Essay Scoring (AES) requires rubric-grounded reasoning across interdependent traits, rather than isolated score prediction. Existing feedback-enhanced methods often decouple feedback from scoring or assess traits independently, weakening score--feedback consistency and rubric alignment. We propose HiFTS, a unified autoregressive framework that generates hierarchical CoT feedback before predicting trait-level and holistic scores. HiFTS distills rubric-grounded hierarchical CoT feedback from a teacher LLM and trains student models to jointly generate feedback and scores. HiFTS further applies Group Relative Policy Optimization with a composite reward balancing score agreement, calibration, feedback quality, and structural validity. At inference, a lightweight global prior provides holistic guidance to reduce drift during long-form reasoning. We also introduce CFMS-34, a Chinese multi-trait AES dataset with 951 essays annotated with holistic scores and 34 rubric-base

---

### [79] ARC-CT: Anatomy-Routed Contrastive Vision-Language Learning for 3D Chest CT

**链接**: https://arxiv.org/abs/2608.28455
**作者**: Huseyin Umut Isik, Mehmet Alp Ozaydin, Sila Kurugol, \c{S}eyda Ertekin
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Contrastive vision-language learning uses paired chest CT volumes and radiology reports to learn abnormality classifiers without manually annotated labels. However, two characteristics of chest CT challenge conventional global contrastive learning. First, many critical abnormalities are small or anatomically localized, and pooling an en- tire volume into a single embedding may dilute their visual evidence. Second, the standard contrastive objective treats every other scan in a batch as a negative. Because many chest CTs share abnormalities, this objective incorrectly pushes co-positive pairs apart. We propose Anatomy-Routed Contrastive Learning for 3D Chest CT (ARC-CT), a region-aware framework that addresses these limitations using only la- bels extracted from reports by an LLM, with no manual annotations or bounding boxes. ARC-CT combines three components: (1) an Anato- myQFormer localizing evidence via queries constrained by automatically generated organ masks; (2) a label-Jaccard s

---

### [80] CEDAR: Automata as Verifiable Interfaces for Language-Guided Embodied Action

**链接**: https://arxiv.org/abs/2608.27797
**作者**: Lekai Chen, Alvaro Velasquez, Ashutosh Trivedi
**来源**: cs.AI cs.CL cs.FL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Natural-language tasking of embodied agents is rarely just goal specification: users also impose constraints that must persist while the world changes. Code-generating LLM agents can produce plausible behaviors for such instructions, but their free-form programs provide no stable object to verify, compose with new constraints, or repair from a failing trace. We present CEDAR, a counterexample-guided framework that grounds instructions as regular languages over environment event traces. CEDAR uses a language model for semantic judgments and execution traces for correction, then represents both skills and specifications as deterministic finite automata. This turns constraints into executable finite-state objects: a learned skill can be intersected with a learned sleep at night or stay in this biome specification, yielding a controller that enforces the learned constraint by construction rather than by repeated prompting. In Minecraft, with the same simulator/API observations available to

---

### [81] The Calls are Coming from Inside the Model: Investigating Probe-based Detection of Tool-Calling Errors in LLMs

**链接**: https://arxiv.org/abs/2608.27750
**作者**: Eric Yeats, Brendan Kennedy, Loc Truong, John Buckheit, Jung Lee, Jesse Friedbaum 等 (8 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The hidden states of large language models (LLMs) are known to capture rich information relating to model knowledge and behavior that can be hard to extract from examination of input and output alone. As LLM-based systems increasingly interface with the external world, one area of concern is detecting incorrect or improper use of tools. Motivated by this, we study the effectiveness of using linear probes to detect incorrect tool-calls, measuring probe efficacy across 18 tool-calling LLMs evaluated on the Berkeley Function Calling Leaderboard. Overall, we find that probing is an effective means to catch a range of different tool-calling errors, including errors arising from using an argument that has the wrong value but the correct type, which might not be recorded by standard logging frameworks. Important factors in success include model size, probing layer, and model post-training type. We also show that probes are capable of generalizing to novel types of errors, which is critical in

---

### [82] String: An Agentic OS Where Every App Is a Markdown File

**链接**: https://arxiv.org/abs/2608.28027
**作者**: Jookyung Song, Nojun Kwak, Simyung Chang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have become a new class of software user, but every surface they work through was designed for someone else. Pages are built for human eyes, which can skim and ignore; tool schemas for programs, which pay nothing to carry definitions they never call. An agent has neither luxury: it re-reads, and pays again for, everything it is shown on every turn. We present String, an open-source runtime that gives this user an interface of its own and treats the job as an operating-systems problem. Tool knowledge moves out of the agent's context and into a common layer that renders it back one view at a time as Markdown. A single SFMD (String-Flavored Markdown) document declares an application's views, typed actions, navigation, and credentials, and the runtime handles discovery, validation, execution, state, and secrets behind two core verbs: /open to see and /act to do. Web and app turn out to be two renderings of one architecture: an SFMD site serves styled HTML to browsers and the raw

---

### [83] QUORUM: QUality-Optimized Routing Using Multiple annotators

**链接**: https://arxiv.org/abs/2608.27974
**作者**: Antonio Purificato, Maria Sofia Bucarelli, Andrea Bacciu, Amin Mantrach, Fabrizio Silvestri
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data annotation remains a central bottleneck in natural language processing, requiring human effort to obtain high-quality labels at scale. While Large Language Models (LLMs) offer a fast and cost-effective alternative, their reliability is highly instance-dependent: they perform well on simple inputs but often fail on examples requiring nuanced reasoning or contextual understanding. In this work, we address this challenge with QUORUM (QUality-Optimized Routing Using Multiple annotators), a budget-aware routing framework that dynamically assigns each instance to human or LLM annotators under a fixed annotation budget. Unlike prior approaches relying on model confidence or uncertainty estimates, QUORUM leverages feature-based signals to estimate instance difficulty and supports multiple annotations per instance, combining them through agreement-based rewards to improve reliability. We evaluate QUORUM across diverse closed- and open-ended annotation tasks in English and multilingual sett

---

### [84] CURA: Certified Runtime Alarms for Computer-Use Agents

**链接**: https://arxiv.org/abs/2608.27808
**作者**: Divake Kumar, Sina Tayebati, Devashri Naik, Amanda Sofie Rios, Nilesh Ahuja, Omesh Tickoo 等 (8 人)
**来源**: cs.AI cs.CV cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-report is the cheapest oversight channel a deployer has, and on capable computer-use agents (CUAs) it fails precisely where oversight matters. On 361 OSWorld tasks our pipeline, a read-only feasibility gate, a planner, and a GUI executor, reaches a mean task score of 82.9, above the 72.4 human reference, yet 64 of its 71 failures (90%) end with a success claim, 61 acknowledging no blocker, and the explicit failure affordance is never used in roughly 9,100 calls. We introduce CURA (Certified Runtime Alarms for Computer-Use Agents), an external monitor that reads only harness-visible telemetry, with no model internals, extra LLM calls, or prompt changes, and turns the running trajectory into a sequential test with certified false-alarm control. At alpha = 0.10 its CUSUM alarm detects 42.3% of failures a median of 31 steps before termination at a realized false-alarm rate of 0.066, and risk is partly resolvable before the first action (gate probe, 0.69 AUROC). Retrospectively the com

---

### [85] BEACON: Behavior-Anchored Cross-Source Knowledge Graph Construction for Cyber Threat Intelligence

**链接**: https://arxiv.org/abs/2608.28394
**作者**: Changze Li, Yutong Cheng, Tsania Camila Finnisa, Qian Cui, Wei Ding, Peng Gao
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cyber threat intelligence (CTI) is foundational to modern cyber defense, yet much of it resides in unstructured reports whose volume and heterogeneity far exceed manual analysis, motivating research on automatically constructing knowledge graphs from CTI reports. However, existing approaches mainly extract partial information within a single report, leaving the cross-source setting unexplored, where the same threat is given unrelated names. Our key insight is that attack behaviors, once mapped to MITRE ATT&CK (a standardized catalog of attack techniques), can anchor the rest of a report. Attack behaviors are the adversarial actions a report describes, while contextual entities (e.g., threat actors, campaigns, and affected products) and Indicators of Compromise (IoCs; e.g., IP addresses) are their participants and traces. Attaching them to these anchors places every per-report graph in one canonical space. We realize this insight in BEACON, an LLM-driven framework for cross-source CTI k

---

### [86] PACE: Publisher-Adaptive Content Extraction via Agentic Automation

**链接**: https://arxiv.org/abs/2608.27466
**作者**: Zhanlin Liu and Munirathnam Srikanth
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web content extraction is essential for reliable LLM data pipelines, yet existing methods often struggle to jointly satisfy accuracy, scalability, and adaptability. General-purpose extractors can be applied broadly, but they are often brittle on publisher-specific layouts and richer extraction targets such as metadata, images, and tables. Direct LLM-based extraction offers greater flexibility, but incurs substantial cost and latency at scale, while manually engineered publisher-specific parsers can achieve high accuracy but require substantial human effort to build and maintain. We introduce PACE, an agentic framework for learning publisher-specific extraction configurations from representative pages and user requirements. During training, PACE uses LLMs to analyze page structure and aggregate reusable extraction patterns. At inference time, the learned configurations instantiate a fixed deterministic extractor template, enabling scalable extraction without additional LLM calls. Experi

---

### [87] See, Hypothesize, Validate: Multimodal Agentic Framework for Discovering Governing PDEs

**链接**: https://arxiv.org/abs/2608.27869
**作者**: Sarang Manoj Pekhale and Amartya Roy and Rajat Sarkar and Souvik Chakraborty
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Discovering governing partial differential equations (PDEs) from observational data remains a core challenge across the sciences. Existing sparse-regression, symbolic-regression, and LLM-based approaches can be constrained by predefined libraries, noise sensitivity, hallucination, or limited iterative refinement. We introduce \textbf{MAGE} (\textbf{M}ultimodal \textbf{A}gentic \textbf{G}overning \textbf{E}quation Discovery), an agentic framework that organizes PDE discovery as a \textit{confidence governed hypothesis validation loop} inspired by the scientific cycle of observation, hypothesis, and falsification. Four role-specialized agents collaborate: a \textit{Differential Observer} computing derivatives and diagnostic visualizations; a VLM-powered \textit{Phenomenology Extractor} distilling qualitative cues from multimodal diagnostics; an LLM-driven \textit{Governing Law Synthesizer} proposing candidates without a predefined library; and an \textit{Equation Arbiter} fitting coeffic

---

### [88] What Makes Agent Memory Useful for Reliable Unanswerable Question Handling?

**链接**: https://arxiv.org/abs/2608.27924
**作者**: Chuanyuan Tan, Junjie Yu, Yuxin Wang, Yining Zheng, Xipeng Qiu, Wenliang Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable handling of unanswerable questions (UAQs) is critical for trustworthy LLM-based agents. Although memory is widely used in agent systems, its role in reliable UAQ handling remains unclear. We present a systematic study of agent memory for UAQ handling under a unified agentic RAG framework, evaluating four representative memory methods across three UAQ-related datasets and two base models. We find that memory can improve UAQ performance in some settings, but such gains are selective rather than universal and remain fragile under dataset shift. Interestingly, cross-model memory reuse is often more feasible than cross-dataset transfer, suggesting that shifts in answerability patterns pose a greater challenge to memory reuse than changes in the base model itself. We further find that UAQ gains are more strongly preserved through decision guidance than through trajectory shaping, and that memory effectiveness depends strongly on representation. In particular, procedural and rule-bas

---

### [89] Credo: Reusable Declarative Primitives for Agentic Workflows

**链接**: https://arxiv.org/abs/2608.27790
**作者**: Duo Lu, Andrew Crotty, U\u{g}ur \c{C}etintemel
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An LLM application depends on both a model and a harness: the program that determines what each call sees, how many calls to make, and which answers to trust. Coding agents can now discover strong harnesses by searching over candidate programs, but the resulting artifact is an opaque block of imperative code whose logical steps, runtime signals, physical execution decisions, and prompt strategies remain implicit and task-specific, forcing subsequent tasks to start the harness search process from scratch. The potential for reuse, however, is substantial. A searched harness encodes significant knowledge, such as the logical steps that work, the signals that matter, the physical operator decisions that adapt execution, and the prompt strategies that are effective, yet this knowledge is buried in imperative code with no inspectable or reusable structure, nor does it carry any provenance or metadata. Credo addresses this problem by recovering a structured declarative description of a search

---

### [90] Sledgehammer or Scalpel? A Fine-grained Adaptive Framework for Implicit Hate Speech

**链接**: https://arxiv.org/abs/2608.27462
**作者**: Han Wang, Yuhu Cheng, Xuesong Wang, Yi Zhu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unlike explicit attacks with obvious profanity, implicit hate speech hides malice within seemingly compliant expressions through metaphors and contextual hints, making its detection in online content review challenging. While existing PLM- or LLM-based methods perform well, they typically apply a single reasoning process to all samples. This overlooks fine-grained linguistic nuances and causes unnecessary computation for simpler cases. We observe that online hate speech is not monolithic but manifests in varied forms. We therefore define three fine-grained categories: Shallow, Targeted, and Context-Dependent. Accordingly, we propose Fine-grained Adaptive Implicit Hate speech Detection (FAID), a novel framework that first performs fine-grained classification and then adapts to specific categories. Specifically, for Shallow samples with surface-identifiable intents, the framework adopts lightweight prompt-tuning for rapid classification; for Targeted comments that bind malicious intent t

---

### [91] Cross-Session Decomposition Attacks: Scaling Risk and Intent-Aligned Retrieval Defense

**链接**: https://arxiv.org/abs/2608.27945
**作者**: Disen Liao, Yihan Wang, Freda Shi, Yaoliang Yu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling laws are usually read as a capability story: lower language-modeling loss yields more useful models. We study a safety consequence of this mechanism in \emph{cross-session decomposition attacks}, where benign-looking subqueries are asked across independent interactions and later recomposed toward a forbidden objective. We formalize this setting as \emph{compositional safety risk} and prove a conditional risk-transfer bound: when the reference environment already contains dispersed evidence for a risky reconstruction, the gap between deployed composed risk and reference composed risk is controlled by the model's excess loss on allowed subqueries. Synthetic withholding experiments show that wider transformers assign lower loss to held-out instructions that never appear verbatim in training but are recoverable from injected supporting facts. A 600-intent pretrained-LLM evaluation shows that larger Qwen3 and Gemma3 family members can yield greater harmful-capability uplift under a 

---

### [92] Stranger, Fan, or Peer? A Systematic Study on the Role of Interlocutor in Persona-Based Dialogue Generation

**链接**: https://arxiv.org/abs/2608.28467
**作者**: Daniela Occhipinti, Malvina Nissim, Marco Guerini
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persona-based dialogue systems are usually conditioned on speaker biography, but dialogues involve at least two participants, and who has access to whose biography can vary across training, inference, and evaluation. Prior work often neglected these aspects, obscuring mechanisms that only appear when biography visibility is toggled separately across training, inference, and evaluation, a three-stage factorisation that prior work has largely treated as a single factor. We study this factorisation on a dataset of dialogues paired with speaker's biographies, varying whether the target and interlocutor speakers see each other's biographies during training and inference, and using an LLM as a judge to perform author identification. We find that (i) training-time visibility, more than inference-time visibility, determines whether models express persona traits through dialogue or fall back on copying biographical text (a known problem/phenomenon in persona-based generation); (ii) models train

---

### [93] Learning a Size-Weight Frontier for Synthetic-Augmented Inference

**链接**: https://arxiv.org/abs/2608.28576
**作者**: Chengpiao Huang, Kaizheng Wang
**来源**: stat.ME cs.AI cs.LG stat.ML
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic data can improve statistical inference when real data are scarce, but naively treating synthetic samples as real data can introduce bias and lead to unreliable inference. We develop a general framework for synthetic-augmented inference across a population of related tasks. It characterizes synthetic augmentation by the number of synthetic observations and their weight. Central to our framework is a size-weight frontier that specifies, for each weight, the largest synthetic sample size for which all smaller sizes attain the target task-marginal coverage. We estimate this frontier from historical tasks, and establish a finite-sample coverage guarantee simultaneously for all size-weight configurations on or below the estimated frontier. In experiments using large language model responses to augment opinion survey data, our procedure achieves target coverage and substantially narrows confidence intervals.

---

### [94] Thinking Costs Tokens: When More Structure is Worth the Price

**链接**: https://arxiv.org/abs/2608.27506
**作者**: Thomas Nolasque, John Grey, Calista Pham and Ankit Vani
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adding inference structure to a language model lets it search, verify, and revise, but these actions consume the very budget they are supposed to use well. In this paper, we investigate whether there exists a token-budget threshold, below which the overhead of planning and verification hurts performance and above which it helps. We evaluate two systems on FinQA and TAT-QA financial reasoning tasks, using GPT-5.4 mini across 14 budget tiers ranging from 250 to 42,000 output-equivalent tokens. The first system is a monolith, which is a single LLM call. The second is a verified search architecture that adds planning, label-blind checking, and repair capabilities. We run 1,000 cases for a total of 28,000 completed cells. Both systems score 0% at the two lowest tiers, where neither can fit a complete prompt. At 1,000 tokens, the monolith reaches 18% accuracy while verified search scores near 0%, since the planning overhead leaves no room for an answer. From 1,500 tokens onward, verified sea

---

### [95] Fully Unleashing the Multimodal Attacker: Meta-Adaptive Jailbreaking of Vision-Language Models

**链接**: https://arxiv.org/abs/2608.27531
**作者**: Benlei Cui, Shen Pang, Yuke Wang, Xuemei Dong, Yuwen Zhai, Jingqun Tang 等 (10 人)
**来源**: cs.CR cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The safety of large vision-language models is increasingly stress-tested by multimodal jailbreaks, yet existing attacks remain largely static at the meta level: template-based attacks freeze the image--text layout, while iterative attacks adapt only the image--text content with fixed attack strategies and frozen attacker parameters. We propose Meta-Adaptive Multimodal Jailbreaking (MAMJ), which instead optimizes the attacker itself along two axes: an attack strategy prompt (ASP) $\theta$ governing attack iteration and attacker weights $\phi$ determining attack effectiveness. Across groups of multimodal attack trajectories, an LLM-based critique first refines $\theta$, after which group-aggregated attack-success-rate (ASR) rewards update $\phi$. On MM-SafetyBench, MAMJ achieves $81.0\%$, $78.9\%$, and $82.3\%$ ASR against GPT-4o, Gemini-3-Pro-Preview, and Seed 2.0, respectively, outperforming the strongest sample-level baseline by up to $24.1$ percentage points. The learned attacker $(\

---

### [96] SMART: MLLM -guided Temporal Alignment for Unifying Sign Language Recognition and Spotting

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.25493&hl=zh-CN&sa=X&d=6043798258678676904&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-zTvJI3rPh89Rk8XDZMczIn&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: E Choi, JH Sung, S Cho, C Xin, Y Choi - arXiv preprint arXiv:2608.25493, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this work, we propose SMART, an MLLM -guided temporal alignment framework for joint sign recognition and spotting. SMART uses MLLM generated motion descriptions as auxiliary semantic cues and performs stable videotext

---

### [97] SciReC: Diagnostic Evaluation of Multimodal, Multi-Turn Relational Reasoning with Adaptive Interaction

**链接**: https://arxiv.org/abs/2608.27461
**作者**: Nilay Yilmaz, Naga Sai Abhiram Kusumba, Stella Wenxing Liu, Yezhou Yang
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Relational reasoning requires the process of perceptual understanding, comparing, and integrating the underlying relationships between concepts. This ability consists of multiple categories, such as analogical, structural, and cause-effect, each capturing a different aspect of higher-order understanding. To examine the performance of multimodal large language models (MLLM) on these relational inference tasks, we developed SciReC, a model-adaptive multimodal academic dialog benchmark. As the relational reasoning process involves multiple representations and various factors (visual understanding, exhibiting knowledge, and memory recall), we propose DMRA, a deficit-based diagnostic framework that quantifies the contribution of these components to identify the primary cause of unsuccessful cases. Claude 4.6 achieved the best performance on the overall relational score with 73\%, followed by GPT 5.4 with 68\%. Performance trends indicate that open-source models achieve their lowest scores o

---

### [98] Aphanta: Diagnosing Task-Aligned Image-Edited Intermediates for Multimodal Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.26993&hl=zh-CN&sa=X&d=5572032893504851237&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-wHSQdnjI4u3v8MLK1dunDB&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: H Xu, W Cheng, Y Ji, X Zhang, X Zeng, G Yu 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We introduce Aphanta, an automated taskdiscovery and closed-loop diagnostic framework for the MLLM → image editor → MLLM pipeline. Aphanta evaluates three conditions—direct reasoning, reasoning … Across 20 candidate tasks and multiple

---

### [99] LLaVAFlow: Preserving Latent Alignment Flow for Parameter-Efficient Multimodal Fine-Tuning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.26820&hl=zh-CN&sa=X&d=16719707973606004458&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-xnACM1FUw12vu3qnIc9nch&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=8&folt=kw-top
**作者**: M Yuan, M Jiao, J Ying, W Zhang, Y Zhang, L Ma… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To assess general knowledge retention in the MLLM , we evaluate its performance on four upstream datasets after fine-tuning on the downstream tasks, including OKVQA [28], OCRVQA [30], GQA [14], and TextVQA [38]. We report

---

### [100] RegulAR: Graph-Grounded Error Recognition and Assistance for Procedural Tasks in AR

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.26715&hl=zh-CN&sa=X&d=10209118862849861546&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-yoazyiAPi5s9QY8WIgI9yW&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=3&folt=kw-top
**作者**: YL Ye, J Wang, HT Wong, S Xu, H Qu, W Kam-Kwai - arXiv preprint arXiv:2608.26715 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We present RegulAR, which combines a hierarchical task dependency graph, MLLM -based egocentric reasoning, and an in-situ HUD to … error support compared to a prompt-only MLLM baseline, while surfacing trade-offs between

---

### [101] UrbanGround: From Local Perception to Spatial Agency in a Real-Scale City

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.27456&hl=zh-CN&sa=X&d=10286770535226155810&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-yPNlZSKX-AGHZgWIvACv3y&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=2&folt=kw-top
**作者**: T Ju, Z Wu, Y Sun, Y Cui, B Li, S Wu 等 (9 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In this paper, we investigate how far current MLLM agents can turn local urban perception into … Contemporary MLLM agents usually show useful atomic abilities in visual recognition and … We hope URBANGROUND will support broader study of

---

### [102] AV-BIMBA: A Cross-Modal State Space Model for Audio-Visual Question Answering

**链接**: https://scholar.google.com/scholar_url?url=https://icpr2026orgteam.github.io/WSpapers/pdfs/paper_0196.pdf&hl=zh-CN&sa=X&d=14686166533009221664&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-wLL5WE96EbkdXgKl1xaS51&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=4&folt=kw-top
**作者**: V Shanmugam, A Radman, J Laaksonen
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We presented AV-BIMBA, an SSM-based audio-visual model leveraging an MLLM decoder and fusing audio and visual information spatiotemporally via a cross… Future work includes extending AV-BIMBA to longer, real-world videos and

---

### [103] WeAgent-MMSearch: Native Text-Vision Interaction for Multimodal Search Agents

**链接**: https://arxiv.org/abs/2608.28062
**作者**: Zongkai Liu, Hui Zhang, Liqiang Niu, Zhen Cao, Han Li, Juntao Liu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal search agents extend parametric knowledge with newly emerging and long-tail evidence from the open web. Yet many existing agentic search environments often expose retrieved evidence only as text and omit tool-returned images from subsequent context, reducing visually grounded trajectories to text-only reasoning. Long-horizon interaction also compounds tool-call, response-length, timeout, and budget failures, which can discard salvageable trajectories, waste rollout computation, and disturb policy updates. To address these issues, we introduce WeAgent-Harness, a multimodal agentic harness that supports native text-vision interaction and runtime recovery. Retrieved images receive persistent disk references, allowing the model to inspect, process, and cite them throughout the trajectory. Based on this harness, we develop WeAgent-MMSearch, an integrated system spanning data construction, agentic post-training, and multimodal rollout. For data construction, a strong MLLM uses WeA

---

### [104] Understanding How MLLMs Describe Artworks Using Token Activation Maps

**链接**: https://scholar.google.com/scholar_url?url=https://icpr2026orgteam.github.io/WSpapers/pdfs/paper_0104.pdf&hl=zh-CN&sa=X&d=1384970048617072624&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-xh06zQCg0LAf7a3IODpinJ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=9&folt=kw-top
**作者**: G Vessio, G Castellano
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To study how an MLLM grounds its description of a painting, we assembled a corpus by collecting the 1,000 most-viewed paintings from WikiArt3 through its public API, downloaded at the platform’s maximum resolution. Popularity is a useful

---

### [105] Fusing Perceptual Vision Experts with Multimodal Large Language Models for Explainable Plant Disease Diagnosis: From Benchmark Imagery to Real-World Robotic …

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.24934&hl=zh-CN&sa=X&d=7090310311134723106&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-zbThCZCkt-h2vN2xdFr3kI&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=5&folt=kw-top
**作者**: R Sapkota, KI Roumeliotis, P Xie, ND Tselikas, L Xiang… - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> MLLM -based conflictarbitration framework on real, non-public, robot-acquired agricultural imagery rather than curated or internet-sourced benchmarks alone. On PlantDoc, the MLLM … exceed 96–99.8% accuracy, and the MLLM layer contributes

---

### [106] Video-IFBench: Evaluating Instruction Following of Multimodal LLMs in Video Understanding Scenarios

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.25529&hl=zh-CN&sa=X&d=18352708619891822035&ei=b0aVaqvGFNGhieoPjfK7mQk&scisig=AIVdB-y4RkUQTLtL2GMBkPe9QeI5&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=6&folt=kw-top
**作者**: H Liu, P Chen, S Liu, P Zhang, K Zou, D Zheng 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To reduce annotation cost, we develop a semi-automatic data construction pipeline that combines MLLM -powered extraction of global and fine-grained local video information, multi-stage complex instruction and checklist generation driven by

---

### [107] Leveraging a Foundation Model for the EEG-Based Diagnosis of Alzheimer's Disease

**链接**: https://arxiv.org/abs/2608.27719
**作者**: Maggie Lin, Chung-Lin Hou, Tzyy-Ping Jung
**来源**: cs.LG q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Biological heterogeneity in Alzheimer's Disease (AD) poses a critical diagnostic challenge, particularly for traditional linear methods that fail to capture non-linear neural dynamics. To address this, we propose a diagnostic framework utilizing the Large Brain Model (LaBraM), pretrained on over 2,500 hours of EEG data. By integrating these high-dimensional latent embeddings with a non-linear Random Forest classifier, our approach effectively isolates robust disease markers. Under a rigorous subject-independent 5-fold cross-validation protocol, the method achieves an ROC-AUC of 89.36% +/- 3.49%, PR AUC of 81.45% +/- 4.43%, and Balanced Accuracy of 82.44% +/- 4.34% in distinguishing dementia patients from healthy controls. Notably, this performance uses only 8-second EEG segments, surpassing traditional spectral baselines, including band-power and parameterized oscillatory features (FOOOF). Post-hoc occlusion analysis confirms the model captures clinically validated biomarkers, specific

---

### [108] AMA- EEG : Adaptive Multimodal Alignment for Cross-Subject EEG Emotion Recognition

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11668713/&hl=zh-CN&sa=X&d=867738848172153427&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-wJwBVf_WWGgT3PX1Qdb2kj&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: J Zhou, S Cao, C Xu, Z Liao, H Zhang, Q Zheng - IEEE Transactions on Affective … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> By aligning noisy EEG signals to these invariant semantic features of the stimuli, we can anchor EEG representations in a more stable crosssubject semantic space, thereby closing the semantic gap between EEG and emotional states. To realize this

---

### [109] Classification of distraction descriptor in EEG signal using topological data analysis

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-69024-1_reference.pdf&hl=zh-CN&sa=X&d=18293653823867174872&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-w_-d-gBLm-8Qw4pafKDOOi&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: CYF Ling, P Phang, SH Liew, RU Gobithaasan… - Scientific Reports, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalogram ( EEG ) signals play an essential role in this effort because they … The advent of digital EEGs has expanded their applications beyond diagnosis and clinical … superior EEG analysis performance as in [55], with our

---

### [110] Virtual iEEG from Scalp EEG : Charting the Landscape of Source Imaging, Intracranial Inference and Reconstruction

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.26998&hl=zh-CN&sa=X&d=9263338508664613682&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-wVg1qRNvUsnjOAgE6QH2_i&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: D He, X Wang, H Yan, L Song, WT Siok, N Wang - arXiv preprint arXiv:2608.26998 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> evidence that virtual iEEG adds value beyond scalp EEG and EEG source imaging. … of target and biophysical limits of recoverability to EEG source imaging (ESI) as an anatomical … beyond scalp EEG and ESI. The contributions of this review can

---

### [111] MSCGC-KAN: Multi-scale Causal Graph Convolution and KAN-inspired Analytic-basis Mapping for EEG Emotion Recognition

**链接**: https://arxiv.org/abs/2605.26624
**作者**: Haoliang Gong, Qingshan She, Jiale Xu, Yunyuan Gao, Xugang Xi
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [112] When multimodal fusion helps: An ablation study of EEG –ECG fusion strategies for emotion recognition

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0010482526004592&hl=zh-CN&sa=X&d=7528484347948456303&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-xAR9Vyh3KpvnDGX59V_syH&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: MM Junior, MBDF U-Vangsy, G Bin - Computers in Biology and Medicine, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalography ( EEG ) captures cortical dynamics with millisecond temporal resolution, making it the modality of choice for neural correlates of emotion. Electrocardiography (ECG) complements EEG … Because WESAD is ECG-primary

---

### [113] One Model for All: Universal Pre-training for EEG based Emotion Recognition across Heterogeneous Datasets and Paradigms

**链接**: https://arxiv.org/abs/2511.08444
**作者**: Xiang Li, You Li, and Yazhou Zhang
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [114] To Extract and Analyse EEG Features Representing Key Biomarkers of Alzheimer's Disease Using Principal Component Analysis for Feature Optimization and …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2666521226001213&hl=zh-CN&sa=X&d=389911195149650099&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-zAUqBEYAEu6Z-5CMWtheBA&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: K Fathima, P Sandhya - Intelligence-Based Medicine, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Through the use of the LEAD EEG -AD database, which is a highly diverse collection of EEG data … Notably the LEAD EEG -AD Dataset as it is the largest publicly available dataset for EEG … The EEG data were recorded from these

---

### [115] Formal Concept Analysis and machine learning for EEG -based neurological outcome classification after cardiac arrest

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2590005626004959&hl=zh-CN&sa=X&d=1286911648677214881&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-ya2fdsy4gBU8fvY38EeQda&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: L Antoni, Š Puci, M Semančík, D Kotlárová… - Array, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> 607 patients with post-cardiac-arrest EEG recordings and associated clinical variables. FCA … EEG -derived statistical and spectral features extracted from standardised 10-second EEG … step for constructing clinically homogeneous

---

### [116] An integrated spatial–temporal feature extraction framework for EEG -based identification of ADHD

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426018732&hl=zh-CN&sa=X&d=16687137760044771881&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-zh3mttjghgpUQzcpQ0j28O&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: X Chang, X Li, S Liang, W Hou, ST Aboyej, P Song… - … Signal Processing and … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalography ( EEG ) offers an objective alternative, yet the effective extraction of spatial and temporal patterns from EEG … These results indicate that the SC–TD Network is an effective and interpretable framework for EEG -based

---

### [117] Unified Hierarchical Learning Framework for Alcoholic EEG Classification Integrating an Attention-based Deep Belief Network with Transformer-based Classification …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S259000562600500X&hl=zh-CN&sa=X&d=2425751649872470272&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-zgNi9Hl29150zYY7ERriHs&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: GS Manivannan, H Rajaguru, K Ramamoorthy - Array, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> detection of alcoholic EEG patterns. However, EEG signals are extremely nonlinear, non-stationary and high-dimensional and proper classification is a difficult task. In this work, a comprehensive hierarchical learning framework is developed for

---

### [118] Rhythm Breaks: A Wearable EEG Setup for Interbrain Synchrony in Remote Collaboration

**链接**: https://scholar.google.com/scholar_url?url=https://iwoar.org/2026/downloads/iWOAR_2026_paper_2293.pdf&hl=zh-CN&sa=X&d=10784624054630906221&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-wQVW4bpe9j8P1_YiyHsWAq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: HA McKee, A Schmidt, S Farook, SB Khalid, G Pichai… - 11th international Workshop …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> One session was excluded from EEG analyses due to a data capture failure in one participant’s stream, leaving N = 9 dyads for EEG -based measures. Behavioural and questionnaire data from that session were unaffected. Participants had normal

---

### [119] Predicting Only from Selected Evidence: A Tempered Product-of-Experts Bottleneck for Auditable EEG Diagnosis

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2608.24377&hl=zh-CN&sa=X&d=14808485248486725625&ei=b0aVarQZspaJ6g-ird7xBg&scisig=AIVdB-x-Inpab08YjKPVTARQ3POq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: Y Wang, S Yu, DH Le, Z Yu, C Wang, VT Nguyen - arXiv preprint arXiv:2608.24377 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We introduce tPoE-EIB, an evidence-information bottleneck head for adapting EEG backbones under … We evaluate tPoE-EIB on pretrained EEG foundation-model backbones across six diagnosis … We focus on this last step: how a frozen EEG

---

### [120] EXPOSE: Explainable and Domain-Robust Embeddings from Pathology Vision Foundation Models using Sparse Autoencoders

**链接**: https://arxiv.org/abs/2608.28191
**作者**: Anja Witte, Maximilian Lennartz, Jan Baumbach, Guido Sauter, Stefan Bonn, Patrick Fuhlert 等 (7 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision Foundation Models (VFMs) are widely used in computational pathology but remain sensitive to domain shifts arising from variations in staining, tissue preparation, and scanner hardware. A key limitation is that VFM embeddings entangle biological with domain-specific information, hindering cross-domain generalization. We propose Explainable Probing of Cross-Domain Sparse Embeddings (EXPOSE), a framework that uses Sparse Autoencoders (SAEs) as an explainable bottleneck to identify and suppress domain-specific components in VFM embeddings. We train a sparse representation of VFM features, use a linear classifier to identify domain-specific latent dimensions, and mask these features prior to downstream relapse prediction without retraining the backbone model. Experiments on a large prostate cancer dataset with multiple acquisition domains show that SAE features capture both domain- and task-specific information, which are partially disentangled in the latent space. Removing domain-sp

---

### [121] Towards Large-Scale Heterogeneous Data Organization for Scientific Foundation Models: A Nuclear Fusion Case Study

**链接**: https://arxiv.org/abs/2608.27578
**作者**: Nathaniel Chen, Kouroche Bouchiat, Peter Steiner, Azarakhsh Jalalvand, SangKyeun Kim, Egemen Kolemen
**来源**: physics.plasm-ph cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training effective foundation models requires massive and organized datasets, yet scientific domains such as nuclear fusion present unique challenges due to largely heterogeneous and sparse data. Here we characterize the data used in developing such a model: with over 20 sensor types spanning 5 orders of magnitude in sampling rate, mixed tensor structures (point measurements, spectrograms, images), and nonstationary physics. We analyze our input complexity and discuss trade-offs between temporal context and frequency resolution. Our analysis provides a template for representing multi-modal fluctuation data at scale, with implications for both multi-modal control systems and nuclear fusion.

---

### [122] The Telephone Game: Evaluating Semantic Drift in Unified Models

**链接**: https://arxiv.org/abs/2509.04438
**作者**: Sabbir Mollah, Rohit Gupta, Sirnam Swetha, Qingyang Liu, Ahnaf Munir, Mubarak Shah
**来源**: cs.CV cs.CL
**匹配关键词**: Unified Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] Explainable Diabetic Retinopathy Classification Using Vision Foundation Models

**链接**: https://arxiv.org/abs/2608.28207
**作者**: Abhishek Verma, Anila Krishna, Abhishek Gajanan Bankar, Juan Miguel Lopez Alcaraz
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diabetic retinopathy (DR) is a major cause of preventable blindness, creating a need for accurate and trustworthy automated screening. This study investigates an explainable DR classification framework using vision foundation models and multiple transfer learning strategies. Three backbones, DINOv2, CLIP, and Vision Transformer (ViT), were evaluated using full fine-tuning, linear probing, and Low-Rank Adaptation (LoRA). Models were trained and internally evaluated on the ODIR dataset and externally evaluated on APTOS to assess generalization. DINOv2-LoRA achieved the highest internal AUROC of 0.758, while DINOv2 full fine-tuning and ViT full fine-tuning achieved the highest external AUROC of 0.920. Calibration was further assessed using reliability analysis after isotonic regression. For explainability, Grad-CAM and HiResCAM were evaluated against expert-annotated lesion masks from the IDRiD dataset using Dice, Intersection over Union (IoU), and Pointing Game metrics. The results demon

---

### [124] Prompt-Guided Interactive Segmentation of Interstitial Lung Disease in Thoracic CT

**链接**: https://arxiv.org/abs/2608.28453
**作者**: Vasilis Dedousis, Lubnaa Abdur Rahman, Lorenzo Brigat{\omicron}, Ethan Dack, Andreas Christe, Christoph Frank 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate segmentation of interstitial lung disease (ILD) patterns is essential for quantitative disease assessment and longitudinal monitoring. However, existing approaches remain limited by relying on dense annotations and producing static predictions that cannot be refined, motivating interactive approaches. While promptable models show promise in interactive segmentation, their adaptation to ILDs remains largely unexplored. To address this gap, we investigate prompt-guided foundation models for ILD refinement and present, to the best of our knowledge, the first adaptation of MedSAM2 for interactive 3D ILD segmentation on thoracic CT. We investigate three fine-tuning strategies and multiple clinically motivated prompts: bounding-boxes (BBox), point, lasso, and scribble. On a dataset spanning seven ILD patterns and healthy lung tissue, full model fine-tuning performed best, improving the average Dice score by 4.7 percentage points over MedSAM2.While BBox prompts achieve the strongest 

---

### [125] From Perspective to Fisheye Depth Estimation and Open-Vocabulary Segmentation

**链接**: https://arxiv.org/abs/2608.27860
**作者**: Rit Gangopadhyay and Alex Wong
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision foundation models are capable of generalizing across 3-dimensional (3D) scenes with high-fidelity estimates; their empirical success can be attributed to training on large-scale datasets of perspective images. However, when transferred to wide field-of-view (FoV) images, such as those captured by fisheye cameras, they return erroneous outputs due to a covariate shift stemming from the radial distortion on the image pixels. We propose a method to generalize vision foundation models to fisheye cameras. The crux of our method lies in a set of learnable parameters, termed Distortion Extenders (DEX), that model the fisheye distortion coefficients and the distributional shift between fisheye and perspective images encoded in the latent space. By minimizing a self-supervised alignment loss, DEX transforms the latent embeddings of fisheye images to resemble those of perspective images to recover high-fidelity estimates. DEX is architecture- and task-agnostic: We demonstrate DEX on monoc

---

### [126] Efficient Online Continual Foundation Model Fine-Tuning for Predictive Process Monitoring

**链接**: https://arxiv.org/abs/2608.28237
**作者**: Sjoerd van Straten, Marwan Hassani
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predictive Process Monitoring (PPM) models are increasingly deployed in dynamic environments where concept drift causes the underlying process distribution to shift over time. While recent work has moved toward online continual learning, existing methods train compact, task-specific networks entirely from scratch, leaving a persistent cold-start problem. Foundation Models (FMs) offer a compelling solution to this problem, but their continual fine-tuning in the process mining domain remains unexplored. We propose COMPASS (Continual Online foundation Model-based PPM with Adaptive SubSpaces), the first framework for online continual fine-tuning of FMs for PPM. COMPASS adapts loss-plateau drift detection to autonomously identify task boundaries in event streams and maintains a unified knowledge subspace including both pre-trained and task-specific directions. We evaluate our approach on nine event streams covering synthetic and real-world concept drift scenarios, across task-free and task-

---

### [127] Cut-ViT: Task-Specific Model Pruning via Gram Anchoring Subspace Consistency

**链接**: https://arxiv.org/abs/2608.28205
**作者**: Jianjian Yin and Liulei Li and Tao Chen and Yi Chen and Yazhou Yao and Wenguan Wang
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pruning visual foundation models has attracted considerable attention. However, existing methods focus on rigid point-to-point token alignment on a single dataset for pruning, suffering from two limitations: i) robustness degradation, and ii) task-specificity deficiency. To address these limitations, we propose a task-specific pruning pipeline, named Cut-ViT. Specifically, we first construct gram anchoring matrices from both spatial and semantic perspectives, and perform the subspace decomposition to extract the corresponding subspace bases. Basis-agnostic and residual constraints are then adopted to align the gram subspaces between the native and pruned DINOv3 models along spatial and channel dimensions, enabling subnetworks to inherit robust feature representations of native DINOv3. Furthermore, we design spectral entropy adaptation, which quantifies the information density of feature manifolds along spatial and channel dimensions, thereby adapting the pruning objective to specific d

---

### [128] GeBDA: Building Damage Assessment as Text-Based Sequence Prediction

**链接**: https://arxiv.org/abs/2608.28567
**作者**: Olivier Dietrich and Krishna Sapkota and Konrad Schindler and Genady Beryozkin
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventionally, Building Damage Assessment (BDA) is tackled either with dedicated network architectures or by fine-tuning geospatial image foundation models. In this work, we ask whether a general-purpose Vision-Language Model (VLM) can localize buildings and grade their damage through autoregressive sequence generation alone. We cast BDA as predicting a variable-length set of bounding boxes, each specified by its coordinates and a damage label. Our preliminary implementation, based on the open Gemma model, achieves promising damage mapping results from only bi-temporal satellite images and a suitable text prompt.

---

### [129] Do Medical Vision Models Reason About Anatomy? Probing the Spatial Inductive Biases of Learned Visual Representations

**链接**: https://arxiv.org/abs/2608.28092
**作者**: Naren Akash, Neeraja Ramanan
**来源**: eess.IV cs.AI cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpreting a CT scan means comparing structures on either side, judging how far apart organs sit, and knowing where each one belongs. Medical vision encoders are evaluated on diagnostic accuracy, or through assembled multimodal systems where a failure is hard to attribute, so it remains unclear whether their representations support any of this. We construct SPAR-Bench, eight probes over multi-organ abdominal CT that separate coordinate localization, relational reasoning, and spatial queries, and apply them to five architectural configurations and three medical foundation models, frozen and finetuned. Probes that ask for a comparison within the slice stay at chance, and neither pretraining scale, finetuning, nor architecture closes the gap. Probes that appear solved in domain fall to chance under zero-shot transfer, indicating that their accuracy reflects recall of canonical anatomy rather than computation over the image. Reading the same frozen features with a pooled head rather than

---

### [130] VidParse: Online Parsing of Egocentric Procedures Like a Pro

**链接**: https://arxiv.org/abs/2608.27562
**作者**: Anubhav Gupta, Archit Kambhamettu, Vatsal Agarwal, Pulkit Kumar, Abhinav Shrivastava
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Translating continuous, noisy egocentric video streams into discrete, temporally ordered action steps is fraught with visual challenges. Heavy ego-motion, transient occlusions, and the high intra-class variability of unscripted human-object interactions cause standard frame-level online temporal models to struggle, often resulting in severe over-segmentation and structural collapse. To bridge the gap between unstable low-level perception and high-level procedural logic, we present VidParse, an online, training-free framework that treats activity understanding as a graph-constrained inference problem. Rather than relying on learned temporal filters, we dynamically identify semantic transitions using a temporal similarity matrix over manipulation-anchored features, which are extracted from frozen foundation models to prioritize foreground hand-object interactions. A beam search decoder then leverages an induced procedural task graph to explicitly enforce valid action transitions and prun

---

### [131] SOMTab: Set-Order Mamba for Efficient Tabular In-Context Learning

**链接**: https://arxiv.org/abs/2608.27882
**作者**: Hao Wang, Siyu Zhang and Wei Ma
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models based on in-context learning have recently emerged as strong alternatives to task-specific model fitting. However, the current performance frontier remains dominated by attention-heavy architectures, where attention is used throughout the modeling pipeline. This raises a natural question: is attention necessary at every stage of tabular in-context learning? We introduce SOMTab, a Set-Order Mamba architecture for efficient tabular in-context learning. SOMTab separates representation construction from query-conditioned retrieval. For row and column representations, it maps unordered table tokens into stable latent slots and applies Mamba-based state-space mixing to construct compact representations. For final prediction, it retains attention-based in-context learning to preserve query-conditioned retrieval from labeled context examples. We further introduce DCH-TailMix, a synthetic prior that combines degree-corrected graph heterogeneity with mixed heavy-tailed 

---
