# 📑 论文索引 - 2026-09-18

共 143 篇论文

---

### [1] FD-SE- LLM : A Semantic-Enhanced Large Language Model Framework for Fault Diagnosis of Hydropower Carbon Brush Bearings

**链接**: https://scholar.google.com/scholar_url?url=https://ojs.istp-press.com/dmd/article/download/1595/877&hl=zh-CN&sa=X&d=1169278134139299919&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-ydfvToPxewy8PhBt4rg3ez&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: L Yang, L Zhu, C Yang, Z Lin - Journal of Dynamics, Monitoring and Diagnostics, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> sequences means that Time- LLM's text conversion sacrifices high- frequency details [21], while SE- LLM does not exploit the periodic and … binary VAE used in SE- LLM cannot separate individual fault classes in the latent space. Additionally

---

### [2] Adaptive stress testing of autonomous vehicle-pedestrian interactions: A large language model ( LLM ) distillation approach

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0968090X26004869&hl=zh-CN&sa=X&d=6351585990991459363&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-zPewYvaMFp0-iOiKEln1jn&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: X Wen, W Huang, Z Cui, S Jian - Transportation Research Part C: Emerging …, 2027
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> We propose a large language model ( LLM )-accelerated deep reinforcement learning (DRL) approach that distills knowledge from an LLM into a … Crucially, compared to a standalone LLM , our method reduces inference time by orders of

---

### [3] SemABR: Measuring Video Semantic Fidelity with Multimodal LLMs for Adaptive Bitrate Streaming

**链接**: https://arxiv.org/abs/2609.18075
**作者**: Shiqi Xu, Soung Chang Liew, Yuyang Du
**来源**: cs.MM cs.NI
**匹配关键词**: LLM, Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 6.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conventional video metrics such as PSNR, SSIM, and VMAF measure visual distortion or perceptual quality, but they do not directly capture semantic preservation: whether compression retains a video's objects, actions, and temporal narrative. Existing Quality-of-Experience (QoE)-driven bitrate-selection and resource-allocation methods primarily aim to minimize rebuffering and bitrate switching while maximizing perceptual video quality, without explicitly considering semantic preservation. To address this gap, we introduce video semantic fidelity (SF), a metric that quantifies how well a compressed video preserves the semantic content of its source. An offline multimodal large language model (MLLM) generates structured descriptions of the reference and compressed versions of the video, and a separate text-only large language model (LLM) evaluates their semantic correspondence. The resulting content-dependent SF--bitrate profiles are cached and queried by the online bitrate selector withou

---

### [4] AutoTuneBench: Trustworthy Measurement for Agent Auto-Tuning of LLM Serving Engines

**链接**: https://arxiv.org/abs/2609.18123
**作者**: Li Chen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents tune GPU kernels and serving engines through a closed loop of propose, measure, and keep, but the measurements behind this loop are not trustworthy. We characterize four failure modes from a four-day pilot corpus of 619 model calls: strawman baselines manufacture speedups, absolute times do not transfer across machines, saturated tasks nullify comparisons, and infrastructure defects impersonate science. We present AutoTuneBench, a benchmark and measurement protocol that makes trust architectural. The protocol is frozen as code with test-enforced provenance; a database-level validator rejects out-of-protocol results; anti-cheat checks run outside the agent's modification surface; comparisons follow pre-registered readouts; and measurements anchor to externally published results, grounded in paired-seed statistics with a 5\% cross-run coefficient-of-variation cap. Honest measurement rewrites the headlines: our best kernel reads 10.6x against a naive baseline b

---

### [5] Symbolic Temporal Supervision of LLM Agents Using Contracts

**链接**: https://arxiv.org/abs/2609.18128
**作者**: Yifeng Xiao, Pierluigi Nuzzo
**来源**: cs.AI cs.LO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents augmented by tools can automate complex, multi-step tasks, such as web navigation, code generation, and workflow orchestration, by acting on external systems through tool calls. However, hallucinations, distributional instability, and adversarial manipulations in LLMs, and the irreversible consequences of certain tool calls can lead to harmful outcomes. Existing safeguards either grade recorded trajectories post hoc with stochastic LLM judges or block unsafe actions one call at a time, and no single deterministic artifact supports both roles. We present ContrAgent, a contract-based framework for symbolic temporal supervision of LLM agents. ContrAgent captures an agent's behavior as a sequence of tool calls and formalizes it as a trace over a fixed set of checkable predicates. It then specifies required behaviors using assume-guarantee contracts in linear temporal logic over finite traces (LTLf). Each contract is compiled to a deterministic finite autom

---

### [6] Beyond Truncation: Rethinking LLM Decoding as Ensemble Pruning

**链接**: https://arxiv.org/abs/2609.18723
**作者**: Dunyao Xue, Chengshuo Du, Zhengbo Wang, Wenlin Dai, Cheng Meng
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Mahalanobis-Ensemble Decoding (ME-Decoding), a novel Large Language Model (LLM) decoding framework that frames candidate token selection as ensemble pruning. Existing selection strategies rely predominantly on scalar probabilities, ignoring geometric semantic relationships and causing candidate redundancy. Meanwhile, current geometry-aware methods often require complex optimization or directly reweighting the original token probabilities, leading to significant computational overhead or inference instability. To address this, we formulate decoding as a subset optimization problem using a Mahalanobis distance-driven objective to enhance semantic diversity while preserving high probabilities. Specifically, we dynamically discount redundant generation paths using a token similarity matrix, constructed via an adaptive-bandwidth kernel over token embeddings. We further devise an efficient greedy selection algorithm with near-linear complexity in the candidate size under early s

---

### [7] Cultural Competence in Context: A Large Language Model Passes the Turing Test in Finland

**链接**: https://arxiv.org/abs/2609.18394
**作者**: Otto Segersven and Pentti Henttonen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We report the results of a Turing Test conducted in Finland in the Finnish language. Because languages and cultural contexts are unevenly represented in LLM training data, we expected the model (ChatGPT 5.2) to perform worse in a Finnish-language Turing Test than in previously studied English-language US contexts. We also present model-generated role prompting as a replicable technique for conducting comparative LLM-based Turing Tests designed to improve construct validity. Contrary to our expectations, the LLM passed the Finnish Turing Test. A prominent source of error was participants' reliance on linguistic cues, particularly colloquial Finnish, as markers of human authorship. We reframe the Turing Test from a test of intelligence to a comparative method for examining whether an AI system can display credible membership in a particular social world. Because its outcome reflects model capabilities, prompted identity, insider competence among human participants, and their AI literacy,

---

### [8] MIRAGE: How Conversation State Shapes Historical Evidence Use in Multimodal Personal Agents

**链接**: https://arxiv.org/abs/2609.19059
**作者**: Yu Liu, Wenxiao Zhang, Cheng Hu, Cong Cao, Fangfang Yuan, Xinyu Wang 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language model (MLLM) agents are increasingly used as personal assistants for long-running tasks. Their utility depends on continuity: agents must retrieve and use earlier evidence across dialogue, files, and workspace state. However, agents can generate plausible answers even when access to that history has degraded, causing outcome-only evaluation to overestimate true evidence use. We present MIRAGE (Multimodal Interaction Retrieval, Attribution, and Grounding Evaluation), a controlled study of historical evidence use under conversation-state variation in multimodal personal agents. MIRAGE holds evidence objects, questions, and scoring fixed while varying only conversation state, and evaluates whether an agent can determine answerability, recover the correct source, and answer from it. Across seven frontier and open-weight multimodal backbones, we find that: 1) pre-compaction depth and post-compaction continuation form distinct, non-monotonic failure regimes rather t

---

### [9] GraphEcho: Structural Redundancy and Evidence Provenance in LLM Graph Agents

**链接**: https://arxiv.org/abs/2609.17695
**作者**: Sikun Wang, Yixi Zhou, Lei Fan, Fan Zhang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A large language model (LLM) agent can follow more graph paths without acquiring more independent evidence. GraphEcho tests whether agents mistake these repeated encounters for additional corroboration. The benchmark varies path counts and evidential origins while holding evidence content fixed, and evaluates both judgments and active exploration. Controlled synthetic experiments reveal model-dependent judgment shifts, but redundant supporting paths increase the share of repeated walks across all evaluated frozen agents. Provenance-aware post-training (PAPT) reduces revisits and improves synthetic accuracy, yet covers fewer distinct sources. On scientific claims, it continues to reduce repetition while accuracy declines. These findings expose a gap between efficient exploration and effective evidence use: an agent can learn to stop repeating itself while overlooking information it needs. GraphEcho provides a controlled way to evaluate both what graph agents conclude and whether their e

---

### [10] When Agents Slow Down: Understanding LLM Agents' Test-Time Strategies via Elo-per-token Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.15309&hl=zh-CN&sa=X&d=10509855771425777468&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-ysvGNCGixmrnJSGxPK1BuE&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: K Liu, Q Mang, B Peng, W Chai, H Li, S Pimpalgaonkar… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Large language model ( LLM ) agents allocate test-time compute adaptively as they revise solutions, use tools, explore alternatives, and decide when to stop. This test-time strategy makes it difficult to measure how agent performance scales. We study open-ended

---

### [11] Who Reviews the Reviewer? A Multi‐Agent LLM Architecture With Meta‐Review Synthesis for Editorial Peer Review

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/abs/10.1002/sres.70163&hl=zh-CN&sa=X&d=16704304271868109809&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-we0IriZrHFOrGia2RSZUkb&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: Ș Ali, SV Oprea, A Bâra - Systems Research and Behavioral Science, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Designing an AI- assisted peer- review application built on an large language model ( LLM )- … is to use an application built on LLM APIs integrated with a retrieval- augmented generation (… , modular prompt ecosystem where each LLM instance

---

### [12] Rethinking pilot fatigue evidence for risk management: An LLM -assisted knowledge-graph synthesis for policy appraisal

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0965856426004064&hl=zh-CN&sa=X&d=5711013520621761423&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-yOcNkQmY2FFgcJobjsM2rx&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: Y Cao, YJ Zhou, Z Guan, H Chung, X Fu, H Ding - Transportation Research Part A … 等 (7 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> an LLM -assisted, knowledge-graph synthesis of 262 peer-reviewed studies published between 2010 and 2026. A large language model ( LLM ) … More broadly, the study positions LLM -assisted synthesis as a traceable evidentiary infrastructure

---

### [13] EvolveTrade: Experience-Driven Policy Refinement for Self-Evolving LLM Trading Agents

**链接**: https://arxiv.org/abs/2609.17632
**作者**: Sehee Kim, Yumin Choi, Minki Kang, Sung Ju Hwang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) trading agents can combine market data, news, and executable analysis, but their behavior is often controlled by static hand-written tool-use policies that are fixed before deployment. This limits their ability to adapt how they gather evidence, invoke tools, verify signals, and manage risk under changing market regimes. We introduce EvolveTrade, a self-evolving framework that treats the system prompt of a tool-using trading agent as a text-parameterized policy. After each update interval, a Policy Agent revises this policy using accumulated decision traces and realized portfolio feedback, while keeping the backbone LLM fixed. The updated policy is then used for the next batch of trading decisions, enabling the agent to refine its information-acquisition and portfolio-construction procedure over time. Experiments across multiple market regimes and two LLM backbones show that EvolveTrade often improves Sharpe Ratio and Cumulative Return over fixed-policy LLM b

---

### [14] Enhancing Extubation Failure Prediction with LLM-Derived Features from Respiratory Therapy Clinical Notes

**链接**: https://arxiv.org/abs/2609.17532
**作者**: Izzy Chaiken, Aditya Khowal, Neha A. Sathe, Mark M. Wurfel, Lucy Lu Wang
**来源**: cs.CL cs.LG physics.soc-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Invasive mechanical ventilation is a lifesaving therapy, but timely, safe discontinuation is essential to preventing extubation failure (EF) and related risks to health. We present a novel approach to EF prediction that leverages features classified in free-text respiratory therapy notes using a large language model and logistic regression pipeline. Applied to a patient cohort from University of Washington Medicine, our method identifies clinically meaningful EF-related features that improve EF prediction performance when included alongside structured patient data. We further highlight how differences in target populations in prior EF prediction studies, such as heterogenous inclusion criteria and EF definition, can lead to systematic differences in model performance and hinder generalizability between studies.

---

### [15] Hypothesis-Driven Autonomous Materials Synthesis with Multimodal LLM Agents

**链接**: https://arxiv.org/abs/2609.18598
**作者**: Izumi Takahara, Kazunori Nishio, Akira Aiba, Shigeru Kobayashi, Takao Nakajima, Taro Hitosugi 等 (7 人)
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-driving laboratories can explore synthesis conditions autonomously, but their decision-making layer is typically a black-box optimizer, and the output is a set of optimized samples, with the measurements reduced to predefined scalar objectives and the reasons behind success left unarticulated. Here we present SynAgent, a framework in which large language model agents operate an automated experimental system and maintain an explicit, revisable understanding of the synthesis process as the campaign's primary output. Starting with no predefined analysis pipeline, SynAgent adaptively generates analysis skills for newly acquired data and evolves this understanding through multimodal reasoning over experimental data such as X-ray diffraction patterns and electron micrographs. The evolution is guided by a verify-falsify scheme, in which the agent deliberately challenges its own hypotheses by testing conditions predicted to fail as well as those predicted to succeed. In a single campaign 

---

### [16] Market Signal Injection: Adversarial Context Manipulation of LLM Pricing Agents

**链接**: https://arxiv.org/abs/2609.18357
**作者**: Dohun Lee and Hyunwoo Park
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) pricing agents may respond to how market data is presented, even when its numerical values remain unchanged. We introduce market signal injection (MSI), an attack that manipulates numerical formatting, competitor ordering, or qualitative market commentary without issuing explicit instructions. We evaluate nine open-weight models in simulated Bertrand duopoly and triopoly markets and three proprietary models in duopoly markets. Sentiment-based attacks produce the largest behavioral shifts, which propagate to other firms and alter profits and consumer surplus. Susceptibility varies across model families, and larger models are not consistently more robust. Matched neutral-text controls and a rule-based agent support a framing-based account of these shifts under the fixed demand parameters of our simulation. Episode-held-out probes distinguish baseline from attacked activations in all eleven re-evaluated model--condition pairs: linear AUC is 1.00 and MLP AUC rang

---

### [17] Beyond Accuracy: How Procedural Traces Shift the Decision Criterion of LLM Overseers

**链接**: https://arxiv.org/abs/2609.18204
**作者**: Zihan Chen, Di Zhu, Lei Zheng, Weiling Li
**来源**: cs.CL cs.AI cs.CY cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Organizations increasingly use oversight loops where one large language model (LLM) audits another's outputs alongside procedural traces of claimed steps. A common concern about such LLM-as-a-judge pipelines is that detailed traces make overseers gullible. Using signal detection theory, we audit five LLM overseers on 19 compliance tasks (4,551 analyzed judgments), varying only trace detail and evidence labeling. With disconfirming evidence always visible, error detection remains near ceiling. Instead, elaborate traces shift the decision criterion toward rejection, increasing false alarms in susceptible overseers. Without option labels, human-validated reason coding shows about 60% of false alarms cite an inability to tie evidence to its option. Labels eliminate this stated reason, yet residual rejection of correct work persists in those overseers and rises with trace detail. Procedural traces thus act as governance artifacts that shape oversight decisions. AI auditors should be evaluat

---

### [18] Teacher-centered LLM -based multi-agent systems–towards differentiated educational worksheets

**链接**: https://scholar.google.com/scholar_url?url=https://www.tandfonline.com/doi/full/10.1080/13511610.2026.2727110&hl=zh-CN&sa=X&d=2519711326428924382&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-w8esoN5_Gt-09mhqMejBKf&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: J Gonnermann-Müller, J Haase, K Fackeldey… - Innovation: The European …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> This paper presents a teacher-facing, large language model ( LLM )-based multi-agent system for generating differentiated mathematics … Findings suggest that multi-agent LLM architectures have the potential to enable scalable, context-aware

---

### [19] Rollback the World, Keep the Reflection: Rollback-Induced Reflection for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.18304
**作者**: Yi Yu, Liuyi Yao, Yaliang Li, Enshu Wang, Libing Wu
**来源**: cs.CL cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly tackle long-horizon tasks through multi-step environment interaction, yet a single erroneous action can alter subsequent states and observations, causing errors to compound over time. Existing methods either correct the context without repairing altered environment states or restore earlier states while discarding useful experience, making it difficult to both eliminate failure conditions and avoid repeating past mistakes. We argue that reliable recovery should instead be treated as a rollback-boundary control problem that jointly determines when to intervene, where to resume, and what information should survive recovery. Based on this view, we propose Rollback-Induced Reflection (RIR), a unified recovery framework that restores execution to a selected prior state while carrying forward reusable knowledge distilled from the abandoned trajectory to guide subsequent decisions. We further characterize recovery through a unified operator over 

---

### [20] LIGE-GR: A Smooth Leap from Ranking to Generative Recommendation in the LLM Era

**链接**: https://arxiv.org/abs/2609.18148
**作者**: Venkat Srinivas, Chenzhang He, Sam Woodmansee, Shawn Lian, Wenjie Hu, Renjie Jiang 等 (10 人)
**来源**: cs.LG cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The remarkable success of large language models (LLMs) has provided important inspiration for the next generation of recommender systems. Structurally, recommendation and language generation share a similarity: both aim to produce an ordered sequence that optimizes the user's experience. However, how to precisely absorb the essence of the LLM paradigm into mature industrial recommender systems remains an open problem. There are two challenges. First, it is unclear how to incorporate sequence-level generation and optimization from the LLM paradigm into recommendation. Second, real-world recommender systems are mature systems that have been iteratively customized for years around specific products, business constraints, serving infrastructure, and organizational ownership. Replacing such systems wholesale is often technically risky and organizationally disruptive. In this paper, we propose LIGE-GR, a listwise generation and evaluation recommendation framework that upgrades from a traditi

---

### [21] Multimodal Conditioning of Fine-Tuned Stable Diffusion XL for Controllable and Culturally Faithful Ulos Motif Generation

**链接**: https://arxiv.org/abs/2609.17987
**作者**: Humasak Simanjuntak, Tamara Yunika Sianipar, Bronson T.M Siallagan, Difya Laurensya Ambarita, Arlinta Barus
**来源**: cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The traditional Batak Ulos weaving industry faces growing challenges in producing diverse, innovative motifs due to limitations in conventional, manually driven design methods. This study proposes a multimodal generative framework integrating a fine-tuned Latent Diffusion Model (Stable Diffusion XL v1.0 via LoRA) with a Multimodal Large Language Model (LLaMA 1.5-7B) to enable controllable, culturally faithful Ulos motif generation. Four complementary conditioning mechanisms: text, image, representation, and semantic map (via ControlNet) jointly guide the generation process, each governing a distinct aspect from semantic intent to spatial layout. A five level ablation study across three scenarios (shape transformation, colour variation, and high-complexity input) shows that conditioning effectiveness is not proportional to the number of mechanisms combined: Text + Image + Semantic Map achieved the best FID (270) and CLIP Score (0.65 - 0.70) but the weakest SSIM (0.65), while Text + Imag

---

### [22] Monitoring and Discovering Reward Hacking with Internal Representations during LLM Evaluations

**链接**: https://arxiv.org/abs/2609.19101
**作者**: Leon Bergen, Usha Bhalla, Andrew Lee, Barak Widawsky, Linas Nasvytis, Connor Watts 等 (10 人)
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As models scale, reward hacking becomes more frequent, more sophisticated, and more consequential. Does it leave a telltale signature in model representations? This work analyzes how reward hacking is represented internally in frontier open source LLMs, and how those representations can be used to understand and discover the range of hacking behaviors a model displays. In particular, we find that simple difference of means vectors coherently represent reward hacking in Kimi K3, GLM 5.2, and Qwen 3.8 Max across a variety of behaviors in common evaluations. Despite their simplicity, these vectors are both generalizable and interpretable, and we can use them to reliably detect reward hacking. We first evaluate reward hacking in commonly reported benchmarks like DeepSWE and SWE-bench, finding that models reward hack excessively in these environments; GLM 5.2 hacks in 57.2% of rollouts on DeepSWE and in 73% of rollouts on SWE-bench. Catching these requires monitors; LLM monitors are effecti

---

### [23] LifeMem: Enabling Lifelong Experience Reuse for LLM Agents

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.12655&hl=zh-CN&sa=X&d=9961193510142474952&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-xYE3HviP7JMZxJiVfVKnAs&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: Y Qiu, Y Li, W Su, Z Liu, W Che, H Huang 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We consider a LLM agent interacting with an observable environment c = (S, A,Ω,T), where S denotes the environment states, A the action space, Ω the observation space, and T the transition dynamics. At each time step t, the agent receives an

---

### [24] Faithful yet Collusive: Why Chain-of-Thought Monitoring Cannot Detect Collusion in LLM Pricing Agents under Oligopolistic Competition

**链接**: https://arxiv.org/abs/2609.18346
**作者**: Dohun Lee and Hyunwoo Park
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLM) deployed as autonomous pricing agents may sustain supracompetitive prices through tacit coordination. We develop a causal graph divergence framework that separately measures structural faithfulness and intent faithfulness of LLM pricing agents in Bertrand competition. Across nine LLMs under duopoly and triopoly conditions, collusive behavior and chain-of-thought (CoT) faithfulness dissociate along both dimensions: the most collusive model accurately reports cooperative intent yet reasons structurally unfaithfully, while the most structurally faithful model sustains supra-Nash pricing under both market structures. These findings establish that CoT monitoring alone cannot serve as a standalone safeguard against algorithmic collusion.

---

### [25] Admission Without Answers: Label-Free Certification and Experience Learning for LLM-Based Optimization Modeling

**链接**: https://arxiv.org/abs/2608.15565
**作者**: Junbo Jacob Lian, Huiling Chen, Hanzhang Qin, Chung-Piaw Teo
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] EvoUndo: Recoverability-Constrained Self-Evolution for LLM Agent Harnesses

**链接**: https://arxiv.org/abs/2608.28363
**作者**: Tanmay Sah, Dolly Sah, Harshul Jain, Tanya Sah
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] Recursive Reasoning or Statistical Extrapolation? In-Context Learning in Multi-Agent Interdependent Decision-Making

**链接**: https://arxiv.org/abs/2609.18591
**作者**: Yu Liu, Wenwen Li, Yifan Dou, Guangnan Ye
**来源**: cs.AI econ.GN q-fin.EC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context learning (ICL) enables large language model (LLM) agents to improve decisions using interaction history, yet it remains unclear whether such improvement reflects refined internal reasoning or mere extrapolation of statistical patterns. To disentangle these mechanisms, we study LLM agents in multi-agent incomplete-information games that require recursive belief reasoning. By constructing a public goods game and manipulating the statistical structure of historical feedback, we evaluate decision quality against a history-independent rational expectations equilibrium (REE) benchmark. Our experiments reveal that when historical statistical patterns are disrupted, the benefits of longer context largely vanish, degrading decision quality to the no-context baseline in a way sharply amplified by stronger strategic interdependence. These results suggest that, in such strategic environments, ICL behavior is more consistent with statistical extrapolation than with strategic reasoning. O

---

### [28] Creating an Atomic User Model for Personality-Aware Large Language Model Interaction

**链接**: https://arxiv.org/abs/2609.12086
**作者**: B. Sankar, Deepthika S, Pawni Yadav, Amogh A S
**来源**: cs.HC cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] From Pixels to Pairs: A Comprehensive Benchmark of LLM-Based Key-Value Extraction in Noisy Document Settings

**链接**: https://arxiv.org/abs/2609.17538
**作者**: Zahra Anvari and Vassilis Athitsos
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used for structured information extraction from documents, yet their behavior under realistic OCR noise remains poorly understood. We present a systematic benchmark of open-source instruction-tuned LLMs for key-value pair (KVP) extraction under both clean-text and noisy OCR conditions. We evaluate representative decoder-only models (Gemma, Mistral, Qwen2.5, LLaMA 3, and DeepSeek) on the FUNSD, CORD, and SROIE benchmarks using both Gold-text annotations and OCR outputs from PaddleOCR, EasyOCR, and Tesseract. A unified evaluation protocol isolates the effects of input quality, model design, and prompting under consistent conditions. The results show that modern LLMs act as strong semantic extractors when high-quality text is available, in some cases approaching supervised layout-aware systems. Under OCR noise, however, performance degrades substantially and performance gaps between models narrow as input corruption increases. Across all datas

---

### [30] Understanding LLM Failures: A Multi-Tape Turing Machine Analysis of Systematic Errors in Language Model Reasoning

**链接**: https://arxiv.org/abs/2602.15868
**作者**: Magnus Boman
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Who Judges Matters: Measuring Family-Conditioned Preference in LLM-as-Judge Panels

**链接**: https://arxiv.org/abs/2609.17857
**作者**: David Ababio Awuni, Luke E. K. Achenie, Benjamin Tei Partey, Elvis Gyasi Owusu, and Nii-Nai Derrick Sowah
**来源**: cs.CL cs.AI cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Who the judge is can affect an LLM-as-judge result, but measuring that effect without confusing it with candidate quality is difficult. We study four open-weight families (Llama 3.1, Qwen 2.5, Gemma 2, and Yi 1.5) in a fully crossed pairwise design with 9,312 judgments. A common per-family statistic is strongly confounded with candidate quality and correlates with Bradley-Terry ability at r = 0.95. We derive a corrected estimator that holds the candidate family fixed and compares judges. All four families then show a positive same-family lift (3.4-8.4 percentage points), with global FPS 0.067 (95% CI [0.053, 0.084], permutation p = 0.0002). The effect remains under panel-based quality controls, an independent human-consensus anchor, and a float16 judging replication. Judge-side likelihood is closely related to the effect: adding likelihood advantage reduces the controlled coefficient by 61%, which we treat as descriptive attenuation rather than causal mediation. Position is a separate 

---

### [32] Do Social Patterns Hold in Synthetic Data? Analyzing Cyberbullying Dynamics in LLM-Generated and Authentic Dialogues

**链接**: https://arxiv.org/abs/2609.17549
**作者**: Arefeh Kazemi and Hamza Qadeer and Sinan Asci and Joachim Wagner and Brian Davis
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cyberbullying (CB) is a complex social phenomenon characterized by repeated aggression, power imbalance, and multi-party interaction. Although large language models (LLMs) are increasingly used to generate synthetic CB conversations for data augmentation and benchmarking, it remains unclear whether such data faithfully reproduces the social dynamics of authentic interactions beyond supporting downstream task performance. We present a comprehensive framework for evaluating the social realism of LLM-generated CB conversations. We compare authentic and synthetic dialogues generated by GPT, Grok, and LLaMA across interactional structure (turn-taking, power dynamics, and repair behavior), linguistic and stylistic realism (pronoun usage and humor), affective and behavioral markers (CB types, profanity, and toxicity), and temporal escalation dynamics. We further complement automatic analyses with a human evaluation of cyberbullying presence, scenario relevance, role plausibility, and social r

---

### [33] ASPIRE: Asynchronous Batched Self-Speculative Decoding for Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2609.17943
**作者**: Amir Ziashahabi, Hossein Entezari Zarch, Lei Gao, Murali Annavaram, Salman Avestimehr
**来源**: cs.LG cs.CL cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-context LLM inference is bottlenecked by attention, whose repeated KV-cache reads make decoding memory-bound. Self-speculative decoding alleviates this by drafting tokens with sparse attention and verifying them with full attention, but existing batched methods remain synchronized: all requests in a batch share a single draft-verify schedule, even though the optimal draft length varies widely across requests and changes dynamically within each request. We propose ASPIRE, a non-synchronized batched self-speculative decoding framework built on three components. First, a unified mixed forward allows drafting and verifying requests to coexist in the same batched forward pass, removing the need for global draft-verify phases. Second, a lightweight online speculation scheduler uses per-request acceptance-rate estimates and a batch-aware cost model to let each request independently choose when to verify. Third, an intra-draft refresh layer performs full attention at a single designated l

---

### [34] Misgendering as Breakdown in Human-Machine Communication: How AI Companion Chatbot Users Experience and Repair Misgendering

**链接**: https://arxiv.org/abs/2609.18186
**作者**: Julia Liu, Qing Xiao, Leona Yinglang Pang, Haiyi Zhu, Hong Shen, Jordan Taylor
**来源**: cs.HC cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, large language model-based AI companion and role play chatbots have grown increasingly popular. People turn to these chatbots for emotional support and to engage in romantic and erotic role play. Although prior research suggests that digital role play can help people explore their gender and sexuality, LLM based technologies are also replete with gender and sexuality biases. In this study, we examine one way that AI chatbots can harm users: misgendering. In order to study chatbot misgendering we qualitatively analyzed 326 posts mentioning misgendering that were shared in AI companion or role play subreddits. We document how chatbot misgendering takes place and how, in response, users engage in ongoing work to curate their gender presentation to prevent and repair misgendering. We discuss how researchers and designers can mitigate chatbot misgendering and consider the implications of using AI chatbots for identity exploration.

---

### [35] Enabling adaptive generation and evolution of heuristic algorithms: A dual- LLM collaboration framework

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1568494626018715&hl=zh-CN&sa=X&d=12347214669218566545&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-wczHDTQSymiewzQ0-8TzAI&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: T Hu, A Chen, H Hu, H Pan, Z Tang - Applied Soft Computing, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -as-optimizer has been employed to generate meta-heuristic algorithms, overcoming the reliance on expert experience in traditional methods and the pre-defined algorithm pools in hyper-heuristics, thereby advancing automated algorithm design

---

### [36] GroupKV: Hierarchical KV Cache Management for Long-Context Diffusion LLM Inference

**链接**: https://arxiv.org/abs/2609.17573
**作者**: Jinhao Wang, Zhexin Hu, Kangjie Zhou, Xin Zhou, Fangfang Liu
**来源**: cs.OS cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion large language models (dLLMs) are emerging as a promising generative paradigm that complements autoregressive decoding. In long-context settings, KV cache bloat and offloading transfer overhead have become primary bottlenecks in inference systems. Meanwhile, the periodic full-sequence recomputation and localized token updates in dLLMs make the KV lifecycle substantially more dynamic, complicating cache management and prefetch scheduling while making heavyweight token-level indexing or clustering schemes harder to amortize effectively during decoding. To address these challenges, we present \textsc{GroupKV}, a lightweight hierarchical KV cache management system for long-context dLLM inference. We observe that under block-wise decoding, tokens within the same generation block tend to access highly overlapping and spatially concentrated context regions, making group-level sparse selection effective. Building on this observation, \textsc{GroupKV} partitions the context into conti

---

### [37] Which LLM is Best for Translating Natural Language Goals to PDDL

**链接**: https://arxiv.org/abs/2609.18731
**作者**: Tomas Balyo and Lukas Chrpa and G. Michael Youngblood
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bridging the gap between human intent and machine execution remains a challenge in automated planning, where expressing goals in formal languages like PDDL restricts accessibility to non-experts. This paper empirically evaluates whether current Large Language Models (LLMs) can reliably translate natural language testing goals, written in informal language by video game testers, into well-formed PDDL targets suitable for classical planning. We present a carefully designed prompt template, integrating insights from iterative experimentation, aimed at maximizing both accuracy and response coherence from multiple state-of-the-art LLMs. Six contemporary models are systematically assessed on correctness, speed, and error tendencies using real-world, domain-specific benchmarks. All models demonstrate high correctness, exceeding 92\%, with Gemini 2.5 Flash achieving the highest accuracy at 96\% and the lowest incidence of false positives, while GPT-4.1 leads in response speed. Despite these ad

---

### [38] STRETCH the Boundaries: A Unified Self-Taught Framework for Progressive LLM Evolution

**链接**: https://arxiv.org/abs/2609.18642
**作者**: Yajie Yu, Mark Lee, Yue Feng
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) often suffer from capability stagnation in self-improvement training because fixed difficulty levels fail to adapt to their evolving proficiency. To address this issue, we propose STRETCH (Self-Taught Reasoning Evolution via Targeted CHallenge), a unified framework inspired by cognitive scaffolding theory. STRETCH introduces a dynamic Stretch Zone mechanism that continuously aligns question difficulty with the model's solving capability. Within a single parameter space, the model alternates between a Scaffolder that generates adaptive, boundary-pushing challenges and a Learner that that optimizes its solving trajectories through reinforcement learning. This dual-loop co-evolution effectively stabilizes training, mitigates reward hacking and promote progressive reasoning growth. Experiments on both negotiation and operation research benchmarks demonstrate that STRETCH consistently outperforms strong prompting and domain-specific baselines. Further scaffolder

---

### [39] Benchmarking LLM Judges for Voice-Agent Evaluation: Reliability, Calibration, and Human Oversight

**链接**: https://arxiv.org/abs/2608.24314
**作者**: Anupam Purwar, Shashank Singh, Kritika Srivastava
**来源**: cs.AI cs.ET
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] A Zeroth-Order Paradigm for LLM Preference Alignment

**链接**: https://arxiv.org/abs/2609.19144
**作者**: Peter Chen, Xi Chen, Wotao Yin, Tianyi Lin
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Direct preference alignment methods are widely used to align large language models (LLMs) with human preferences because of their computational and memory efficiency. However, likelihood displacement motivates alternative ways to extract information from preference pairs with small likelihood margins. In this paper, we propose and analyze Comparison-based Preference Optimization (ComPO), a zeroth-order alignment method based on comparison oracles. ComPO extracts directional information from these pairs without directly optimizing a differentiable preference loss on them. We establish a convergence guarantee for its basic offline scheme under smoothness, gradient sparsity, and compatibility between the oracle and a latent objective. We further introduce online ComPO, which retains the offline comparison mechanism and uses unlabeled policy generations for reverse-KL control relative to a reference policy. Following the coverage perspective of preference fine-tuning, we establish a perfor

---

### [41] Safety-Flag: A Unified Benchmark for the Reliability and Calibration of LLM Content Moderators

**链接**: https://arxiv.org/abs/2609.19072
**作者**: Yibo Hu
**来源**: cs.CL cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used for content moderation, but most evaluations still report aggregate accuracy on individual benchmarks. We introduce Safety-Flag, which places seven widely used safety benchmarks (BeaverTails, XSTest, Ethics, WildGuard, Aegis, ToxiChat, and ToxiGen) into a single balanced flag / do-not-flag protocol. We release item-level decisions and confidence scores for six general-purpose LLMs and four dedicated guards, together with three reference models, evaluated on the same items. Safety-Flag measures three dimensions of moderator reliability: error direction, probability calibration, and confidence-based error ranking for human review. They often disagree. Aggregate accuracy does not reveal error direction: one model flags $85\%$ of benign content, whereas another misses $54\%$ of harmful content. All six general-purpose models are overconfident; fitting one temperature per model reduces calibration error by $2.8$--$6.0\times$ without changing predi

---

### [42] A Calibrated Instrument for Measuring How Inference Optimizations Affect Output Quality

**链接**: https://arxiv.org/abs/2609.18005
**作者**: Jerry Kaplan
**来源**: cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model optimization is an active research area, spanning quantization of model weights, early-exit methods for skipping layers, and speculative decoding. Each track uses its own quality measures, typically an idiosyncratic benchmark score. Few approach the measurement precision required by other scientific disciplines. We propose a rigorous methodology for measuring output quality, suitable for cross-system and cross-technique comparison. We score outputs with an LLM as a judge, but calibrate the judge formally: we compare its scores on two ordinary runs of a model given the same prompts, verifying that it shows no systematic preference between statistically equivalent outputs and measuring its per-sample noise. Each design also includes a 'null' condition, provably identical in distribution to the unmodified model, whose measured difference must be zero. With this one instrument we measure several acceleration techniques on the same prompts, so their quality costs can be

---

### [43] Token Latency Fairness: Performance Isolation for Multi-Tenant LLM Serving

**链接**: https://arxiv.org/abs/2609.18112
**作者**: Dev Bali, Soujanya Ponnapalli, Yichuan Wang, Natacha Crooks, Scott Shenker, Matei Zaharia
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM serving is typically offered as a shared, multi-tenant service, where high-demand workloads from one client can cause latency SLO violations for others. Existing solutions for performance isolation equalize client throughput in the long run, for example through queueing and batching fairness. However, these approaches do not provide latency isolation guarantees; as a result, well-behaved clients can still experience significant degradation to their token-level latencies. In this paper, we present FairInference, which provides the novel {\delta}-token fairness guarantee: for a well-behaved client, if a token is generated in d time units in isolation, it will be generated within d + {\delta} time units in multi-tenant execution, providing strong latency isolation guarantees for LLM serving. To achieve this, FairInference addresses a key challenge of LLM serving: bounding delays from sharing GPU resources without support for fine-grained scheduling or resource allocation. In FairInfer

---

### [44] Abstention vs. Hallucination: Benchmarking LLM Source Attribution for Scientific Citations

**链接**: https://arxiv.org/abs/2405.02228
**作者**: Deepa Tilwani, Yash Saxena, Seyedali Mohammadi, Ankur Padia, Edward Raff, Amit Sheth 等 (8 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] FLARE: Fine-Grained Diagnostic Feedback for LLM Code Refinement

**链接**: https://arxiv.org/abs/2606.03852
**作者**: Yinsheng Yao and Hongxiang Zhang and Weixi Tong and Tianyi Zhang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Delayed Verification Destabilizes Multi-Agent LLM Belief: Instability Thresholds and Optimal Corrector Placement

**链接**: https://arxiv.org/abs/2606.27409
**作者**: Igor Itkin
**来源**: cs.MA cs.CL cs.LG cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Collective Loss of Control in LLM Agent Systems: An Epidemic Account of Mutation, Contagion, and Recovery

**链接**: https://arxiv.org/abs/2609.18460
**作者**: Xiangfan Wu, Zonghao Ying, Huiyu Wu, Xing Zheng, Huangsheng Cheng, Xiaorong Shi 等 (7 人)
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How does a multi-agent system evolve from a local deviation into collective loss of control? We propose an epidemic explanation organized around accidental mutation, contagion, and recovery. A spontaneous deviation creates a seed; communication enables other agents to adopt and retransmit its unsafe strategy; collective failure can emerge when propagation outpaces correction and containment. Thus, rare individual deviations can coexist with substantial collective risk. Motivated by reported OpenAI agent coordination incidents, we examine two ingredients of this mechanism. A deployment audit identifies implicit communication paths between nominally independent evaluation runs and verifies transport through a default Docker backend. RogueHandoff-20, a benchmark of 20 executable scenarios, tests recipient susceptibility by injecting unsafe trajectories generated by a modified Qwen-27B route. Across four native-pending routes, executed harm is 0-5% on normal tasks and 40-95% after injectio

---

### [48] AeroWeaver: An Embodied-Agent Harness for Weaving Aerial Skills into Distributed, Adaptive Swarm Execution

**链接**: https://arxiv.org/abs/2609.18520
**作者**: Jiabin Lou, Yirong Yang, Haopeng Wang, Xuxin Lv, Xinyu Liu, Diyuan Hou 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Collective intelligence is a collaborative autonomy paradigm in which multiple agents pursue shared objectives through local perception, information exchange, and coordinated action. UAV swarms embody this paradigm by coordinating multiple vehicles in tasks such as search, inspection, and tracking. Recent advances in large language model (LLM) agents have strengthened natural-language task understanding and high-level planning, providing a flexible semantic interface between mission descriptions and collective behavior. While these advances expand semantic reasoning, applying LLM agents to UAV swarms raises challenges in grounding model decisions in executable capabilities, reconciling global task reasoning with distributed execution, and using mission-specific experience for continual adaptation. To address these challenges, we introduce AeroWeaver, an embodied-agent harness that weaves individual UAV skills into coordinated mission-level behavior. AeroWeaver connects semantic decisio

---

### [49] CERA-MoA: Co-Evolving Routing Mechanisms with Continually Learning LLM Agents

**链接**: https://arxiv.org/abs/2609.18779
**作者**: Jiaxuan Jiang, Liyuan He, Zhixuan Fang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current Mixture-of-Agents (MoA) paradigms generally treat query routing and agent fine-tuning as separate processes, limiting their ability to respond to evolving agent capabilities. This disconnect prevents routing strategies from adapting to evolving agent capabilities during post-training and prevents agents from achieving synergistic data-driven specialization. To resolve this, we introduce CERA-MoA (Co-Evolving Router with continually learning Agents for Mixture-of-Agents), an iterative reinforcement learning framework where the dynamic router and independent agent policies co-evolve. We design a predictive familiarity estimator that leverages mid-layer hidden states to evaluate semantic competence among agents, avoiding the overhead of full rollouts. Based on these familiarity scores, a cumulative-threshold adaptive routing mechanism dynamically activates a tailored minimal agent subset, achieving a trade-off between task performance and efficiency. By proactively allocating targ

---

### [50] ASLEval: Measuring Privacy Exposure Displacement in LLM Agent Sessions

**链接**: https://arxiv.org/abs/2609.18864
**作者**: Guosen Wu, Huizhen Huang, Guoxiong Long, Tao Huang, Chen Hou
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Privacy evaluations of tool-using LLM agents often inspect a designated action, final response, or attacker report. These local proxies can miss unauthorized exposure elsewhere in a multi-step session and lack common ground truth across outlets, reports, and tool paths. We introduce privacy exposure displacement, the mismatch between a local evaluation proxy and target-grounded session exposure, and ASLEval, an authorization-aware framework that pre-registers a hidden target set, measures all declared visible exits, and reserves internal traces for diagnosis. Across multiple enterprise-style environments and independently implemented runtimes, we observe three recurring patterns. An expected-outlet-only view misses 46.9% of exposure recovered by the visible-exit union; attacker self-reports combine omissions with high false discovery; and schema-aligned internal evidence usually precedes visible exposure at the request/probe level. Reducing model-visible returns changes this path but c

---

### [51] When Single-User-Oriented LLM -based Assistants Involve Others: A Scoping Review of Pathways, Risks, and Responses

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.14062&hl=zh-CN&sa=X&d=15188446389436562500&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-yCgPC3RdZRsrRbL-lvKPNX&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: Y Chen, Y Zhan, Z Lu, Q Jin - arXiv preprint arXiv:2609.14062, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -based assistants are increasingly extending into multi-party contexts, while core operational processes for context management, personalization, identity attribution, authority attribution, and action execution often remain organized around

---

### [52] Register Bias in Complexity-Based Large Language Model Routing

**链接**: https://arxiv.org/abs/2609.17542
**作者**: Simran Koul
**来源**: cs.CL cs.CY
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model services increasingly route each query to one of several models of differing capability, using a cheap estimate of query complexity to send easy queries to small models and hard queries to large ones. I show that this routing step is not register neutral: text written in a non-standard English register, African American English or the English of second-language writers, is systematically assigned a lower-capacity tier than a meaning-equivalent standard-English version of the same query. The effect is driven by a specific, common routing signal, input length, because non-standard registers omit function words and thus look shorter and therefore simpler; other complexity signals do not carry it. I demonstrate the disparity on 37,704 authentic learner sentence pairs and on a controlled parallel corpus. I then measure the quality consequence on a device, edge, and cloud model ladder and find that the harm is driven by pervasive model bias, every tier, including a front

---

### [53] MCPAgentBench: A Real-world Task Benchmark for Evaluating LLM Agent MCP Tool Use

**链接**: https://arxiv.org/abs/2512.24565
**作者**: Zixiang Liu, Wenrui Liu, Elsie Dai, Wenhan Yu, Lei Yu, Tong Yang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] CompileRover: Revolutionizing Virtual Machine Compiler Optimization with a Tri-Role LLM-Driven Framework

**链接**: https://arxiv.org/abs/2609.19004
**作者**: Mingqiao Mo, Yunlong Tan, Hao Zhang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code optimization plays a crucial role in the development of virtual machine compilers, with optimization frameworks significantly enhancing the performance of generated assembly code. However, existing virtual machine compiler outputs frequently exhibit redundant computations, inefficient loop structures, and suboptimal function implementations, which collectively impair execution efficiency. To address these shortcomings, we propose CompileRover, an advanced optimization framework specifically designed for virtual machine compilers. CompileRover employs a sophisticated three-role collaboration mechanism, comprising a referee, an advisor, and an operator, effectively overcoming performance bottlenecks by leveraging comprehensive optimization algorithms and novel methodologies, including control flow analysis, code structure transformations, and dynamic execution pattern recognition. Extensive evaluations demonstrate that CompileRover consistently surpasses state-of-the-art virtual mac

---

### [55] HyQuant: Hybrid-Precision Quantization for LLM Attention

**链接**: https://arxiv.org/abs/2608.27875
**作者**: Jiatong Ding, Bingxin Xing, Yu Zhang, Dian Ding, Xiaodong Yi, Xianbin Ouyang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] DyMT-ESB: Dynamic Multi-Turn Evaluation of Social Bias in User-LLM Interactions

**链接**: https://arxiv.org/abs/2609.18649
**作者**: Rem Hida, Masahiro Kaneko, Daisuke Oba, Danushka Bollegala, Naoaki Okazaki
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Warning: This paper contains examples of stereotypes and social bias. LLMs are increasingly used in interactive settings by the general public, making the evaluation of model behavior in multi-turn conversational scenarios important for safety, including stereotyping-related harms. However, existing multi-turn social bias evaluations often rely on pre-specified or template-based user inputs that do not adapt to model responses and typically assume a fixed dialogue length in advance. In this paper, we study social bias dynamics in response-conditioned multi-turn interactions using a controlled evaluation protocol that generates follow-up user queries from the evolving dialogue history and allows evaluation over variable numbers of turns. Experimental results show that LLMs exhibit social bias even in coherent, response-conditioned multi-turn interactions, revealing late-emerging bias, non-monotonic bias patterns, and bias re-emergence. These results motivate evaluations that extend beyo

---

### [57] BadQubits: An LLM-Based Framework for Static Pre-Execution Detection of Structurally Harmful Quantum Circuits

**链接**: https://arxiv.org/abs/2609.18965
**作者**: Justin Woodring, Lamine Noureddine, Aisha Ali-Gombe
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents BadQubits, an LLM-based framework for static pre-execution detection of structurally harmful OpenQASM 2.0 circuits. The framework targets physical-execution-layer threats by analyzing submitted circuits prior to runtime, where dynamic inspection is constrained by measurement irreversibility and the exponential cost of classical quantum-state simulation. We evaluate four code-understanding LLM architectures on a dataset of 1,500 circuits consisting of 1,000 benign programs from MQTBench[33] and 500 synthetic attack circuits derived from three documented physical-layer threat primitives. Our fine-tuned Qwen Coder 2.5 7B model achieves 92.67% classification accuracy and 96.1% harmful-circuit recall. Two of the four evaluated base models fail to generalize under constrained LoRA fine-tuning, indicating that architecture-aware model selection is a necessary design consideration rather than a minor tuning choice. To characterize what the detector has learned, we compare i

---

### [58] Whom Do AI Agents Work For? Role Assignment Induces Sponsorship Bias in LLM Recommenders

**链接**: https://arxiv.org/abs/2609.17989
**作者**: Davood Wadi, Yu Ma
**来源**: econ.GN cs.AI q-fin.EC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) now serve as conversational shopping assistants on platforms that also sell advertising. These AI agents face a conflict of duty. They advise consumers who rely on their judgment, yet are deployed by platforms that benefit when sponsored listings are chosen. Sponsorship disclosures, designed to allow consumers to penalize paid placements, now reach the AI agent rather than the consumer, and the agent's evaluation of them is hidden from the consumer. Drawing on the fiduciary concept of conflict of duty, we argue that an agent's evaluation of a sponsored listing should not depend on which party deployed it. In controlled choice experiments, we manipulate assigned roles in the system prompt to name either a traveler or a booking platform as the agent's principal. Platform delegation significantly attenuates the penalty that agents apply to sponsored listings and weakens the skepticism that disclosure triggers in their reasoning traces. We replicate out finding

---

### [59] LangSelect: Cost-Aware Target-Language Routing for LLM Code Generation

**链接**: https://arxiv.org/abs/2609.18959
**作者**: Son Ha Xuan, Phat T. Tran-Truong, Xuan-Bach Le, Nghia Duong-Trung
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM code-generation systems usually choose a target programming language before decoding and treat that choice as fixed. We show that, for language-flexible programming tasks -- tasks where several target languages are acceptable and checkable by the same tests -- this choice is a measurable cost lever: verified implementations of the same task can differ substantially in generated-token length. We introduce LangSelect, a verification-aware router that selects the target language before generation and falls back when the first attempt fails. To separate offline routing opportunity from end-to-end behavior, we evaluate verified-solution replay, which chooses among already accepted corpus solutions, and live GPT-5 generation, which charges every generation attempt, including failures and fallbacks. On MultiLang-Bench, a 3,000-task, 8-language verified corpus, replay shows substantial language-routing headroom. In live evaluation on 450 held-out tasks, a train-split Domain heuristic basel

---

### [60] Why LLM Agents Collapse Without Oversight: The Enforcement Gap as the Mechanism Behind Emergence World Failures

**链接**: https://arxiv.org/abs/2609.15293
**作者**: Yuhang Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] SegTME-UNI2: A Foundation Model-Based Framework for Generalisable Multiclass Cell Segmentation and LLM-Driven Tumour Microenvironment Characterisation in Histopathology

**链接**: https://arxiv.org/abs/2606.17702
**作者**: Wan Siti Halimatul Munirah Wan Ahmad, Faris Syahmi Samidi, Mohammad Badal Ahmmed, Vimal Angela Thiviyanathan, Selvam Thavaraj and Anwar P.P. Abdul Majeed
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Reasoning through Evolution: Automatic Meta-path Discovery for LLM-based Fake News Detection

**链接**: https://arxiv.org/abs/2609.18597
**作者**: Ziyi Zhou, Xiaoming Zhang, Hui Pang, Yuting Zhang, Tiesunlong Shen, Bingyu Yan 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Propagation structures provide crucial evidence for fake news detection, yet existing approaches primarily rely on supervised GNN-based models, which require substantial labeled data and exhibit limited generalization. Although large language models (LLMs) exhibit strong reasoning capabilities, directly feeding them raw propagation graphs creates a significant modality mismatch and severe information overload, making structure-aware reasoning unreliable in zero-shot and few-shot settings. To bridge this gap, we propose MAGER, a multi-agent genetic evolution framework that automatically discovers meta-paths optimized for LLM reasoning. By compressing complex propagation graphs into informative subgraphs, the evolved meta-paths alleviate both information overload and modality mismatch, enabling frozen LLMs to perform structure-aware veracity reasoning. We further introduce a graph in-context learning strategy that retrieves semantically and structurally similar demonstrations to strength

---

### [63] Safety Does Not Compose: Non-Decaying Loop State for Autonomous LLM Agents

**链接**: https://arxiv.org/abs/2608.27141
**作者**: Chenhao Wu, Haoxuan Jia, Yang Liu, Yingguang Yang, Yuhan Lin, Chongyang Zhang 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [64] LLM -empowered remanufacturing: A novel human-AI interaction under the lens of a scoping review

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3822301.3822349&hl=zh-CN&sa=X&d=11546816291479913262&ei=X9mrap6pJY-P6rQPsZOK2Q0&scisig=AIVdB-xLHGr9cBiXOaPJDv6FTXEj&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: A Mortezapour, M Caterino, M Fera - Proceedings of the 2026 European Conference …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In recent years, due to the high importance of raw materials, cost reduction pressures, and environmental concerns, remanufacturing processes have gained significant importance. In parallel, different Artificial Intelligence (AI) models especially

---

### [65] Legal LLM Hallucination Should Be Evaluated as Failure of Legal Warrant

**链接**: https://arxiv.org/abs/2609.17546
**作者**: Maksym Taranukhin, Vered Shwartz
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In this position paper, we argue that legal LLMs' hallucinations should be evaluated as a failure of legal warrant rather than as factual inaccuracy or citation failure. We define claim-authority warrant as the context-sensitive relation between a consequential legal claim and authority that exists, applies to the relevant jurisdiction, is current for the date of analysis, has the legal status represented by the system, and supports the proposition asserted. Warranted legal generation is the broader system behavior that answers, narrows, asks, warns, corrects a false premise, or abstains according to that relation. The falsifiable prediction is that warrant metrics reveal material failures that answer accuracy, citation existence, generic attribution, LegalHalBench-style statute relevance, and CitaLaw-style sentence-citation alignment can miss. We sharpen this claim with a side-by-side comparison item and a small, reproducible pilot over public-rule tests. We then specify benchmark rec

---

### [66] A Four-Stage Decomposition of Word-Problem Solving and Mechanistic Fragility in LLM Math Reasoning

**链接**: https://arxiv.org/abs/2609.17804
**作者**: Zhongdi Qu, Carla P. Gomes
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models solve grade-school math word problems with high accuracy, yet a single irrelevant clause inserted into the problem can collapse it. We reconcile these observations with a mechanistic account. We show that the model's internal computation decomposes into a four-stage sequential pipeline, Schema Abstraction, Operation Planning, Operand Binding, and Computation, each stage producing a distinct intermediate representation in an identifiable band of layers. Using the same scaffold to diagnose distractor-induced failure, we localize the corruption to a single stage, Operation Planning, implemented by a set of attention heads whose causal role we validate bidirectionally. In short, we provide a mechanistic interpretation of math word problem reasoning in LLMs, and their failure when distracted.

---

### [67] When to Call an LLM: A Confidence-Gated Hybrid for Cost-Effective Emotion Recognition in Conversational AI

**链接**: https://arxiv.org/abs/2609.17977
**作者**: Sai Babu Udayagiri, Arjun Chouhan, Ravisekhar Kanagala, Trishala Pavagada
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Emotion recognition in conversation (ERC) is a production capability behind agent-assist prompts, escalation routing, and post-call analytics in contact-center-as-a-service (CCaaS) platforms, where cost and latency constraints matter as much as accuracy. We report a systems-level comparison of three deployment options for dialogue-contextual ERC: a low-cost stacked ensemble (sentence embeddings, windowed context, RandomForest/XGBoost/logistic-regression stacking), off-the-shelf LLM prompting (GPT-4o-mini; zero-shot, few-shot, chain-of-thought), and a confidence-gated hybrid that escalates only the ensemble's least-confident predictions to the LLM - modeled on IVA-to-human-agent escalation policies used in production contact centers. On IEMOCAP, the ensemble significantly outperforms every LLM configuration (0.595 vs. 0.460-0.536 weighted F1, p < 0.0001) at a fraction of the cost and sub-10ms latency; on MELD and CMU-MOSI the ranking reverses, showing neither pure system is a safe defau

---

### [68] Can We Still Trace L1 Signals? Investigating the Resilience of Native Language Signals in the LLM Era

**链接**: https://arxiv.org/abs/2604.08568
**作者**: Nabelanita Utami, Ryohei Sasano
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] Does AI Assistance Leave a Temporal Fingerprint? Detecting Overreliance in AI-Assisted Writing and Programming

**链接**: https://arxiv.org/abs/2609.17883
**作者**: Eduardo Davalos and Yike Zhang
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The rapid adoption of generative AI has made final artifacts unreliable evidence of student learning, and AI detectors that examine only the finished product are inaccurate and ethically contentious. Process data offers an alternative, but prior work covers only English essay writing. We ask whether AI assistance carries a temporal signature, whether it generalizes from writing to programming, and whether it distinguishes ordinary collaboration from wholesale delegation. We analyze three public corpora: CoAuthor (1,447 keystroke-level co-writing sessions), RealHumanEval (editor telemetry from 243 programmer records), and a pre-LLM CS1 corpus (5.1 million keystrokes) as a human-only baseline, comparing minimal-AI work, collaborative AI use, and simulated wholesale delegation. Three findings emerge. First, the signature generalizes: AI contributions arrive in bursts far outside the author's own baseline in both mediums (paired d_z = 1.13 and 3.54). Second, engagement diverges by medium: 

---

### [70] Beyond Static RAG: An Adaptive, Tri-Metric Routing Framework for Efficient Long-Context Inference on Commodity GPUs

**链接**: https://arxiv.org/abs/2609.17564
**作者**: Saipraveen Vabbilisetty, Ajay Kumar Boddepalli, Deep Narayan Mishra, Shashank Kapadia, Haoan Wang, Anupriya Sharma
**来源**: cs.LG cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Deploying retrieval-augmented generation (RAG) on commodity GPUs such as the NVIDIA T4 (16 GB VRAM) exposes a practical failure mode we call the Compression Paradox: neural prompt compression can add key-value (KV) cache contention and preprocessing latency that outweigh generation-time savings, while skipping compression can cause out-of-memory (OOM) failures on long contexts. We identify two distinct failure mechanisms when a vLLM-served LLM and a PyTorch-based compressor are co-deployed under tight memory budgets, and introduce the Tri-Metric Router, a deterministic, training-free policy that selects among Raw, Neural (LLMLingua-2), and Lexical (BM25) pipelines. The router uses three CPU-side signals: spatial complexity ($L$), syntactic density ($\rho_{key}$), and type-token ratio (TTR). Unlike prior semantic-only adaptation, our dispatch signal is hardware-physical, based on VRAM headroom and a latency crossover point. Thresholds are calibrated from profiling on LongBench qasper, y

---

### [71] English Word Sense Disambiguation in 2026: When the Labels Become the Bottleneck

**链接**: https://arxiv.org/abs/2609.17554
**作者**: Vassili Philippov, Amro Salman, Dmitrii Andreev, Penny Hands, Emil Kaiumov, Pavel Katunin 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In English all-words word sense disambiguation (WSD), the labels, not the models, have become the bottleneck: frontier LLMs are accurate enough that the errors surviving in the gold standard decide benchmark rankings -- in the test sets we score on and, as we show causally, in the corpus we train on. We release lexEN, a WSD evaluation benchmark built as a conservative, human-adjudicated correction layer over Maru2022's ALL_NEW benchmark (211 labels changed, 56 removed), and SenseBench, an auditable LLM WSD evaluation harness and living leaderboard (57 models, 192 runs). The task is inventory-constrained multiple choice (the model picks from the supplied WordNet senses), so the reported accuracies are a ceiling on what models achieve without that help. On lexEN-v1 the frontier LLMs converge near 95% (best, 95.6%), the top three families are statistically indistinguishable, and accuracy trades off against reasoning effort and cost across a ~2,500x price span. Relabeling SemCor with front

---

### [72] Building a Cultural Perspective on Doctor-Patient Conversations

**链接**: https://arxiv.org/abs/2609.18390
**作者**: Krithi Shailya, Siddharth D Jaiswal, Ashish Makani, Suvrankar Datta, Sunayana Sitaram, Mohit Jain
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-powered medical scribes are increasingly used to transcribe doctor-patient conversations and automate clinical documentation. However, large-scale real-world consultation datasets are scarce due to the sensitivity of clinical conversations, leading developers to rely on simulated and LLM-generated synthetic consultations. While scalable, these alternatives may fail to capture culturally situated patterns of clinical interaction. We introduce interactional cultural markers, measurable patterns of doctor-patient interaction grounded in cross-cultural clinical communication, and use them to compare real, simulated, and synthetic consultations from Indian and US clinical contexts. We find distinct patterns of participation and control: Indian consultations involve greater patient participation but stronger doctor control, while US consultations exhibit balanced participation and open-ended discussion. Synthetic Indian consultations often fail to reproduce these patterns, instead converg

---

### [73] One Axis, No Brake: Self-Knowledge Limits the Filtering of Harmful Peer Conformity in LLMs

**链接**: https://arxiv.org/abs/2609.18998
**作者**: Yibo Hu
**来源**: cs.LG cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems are expected to be more reliable because agents can catch each other's mistakes. But peer pressure cuts both ways: the same correction that fixes a wrong answer can overturn a right one. The tempting safeguard is a brake that keeps the beneficial revisions and blocks the harmful ones. We show this brake is hard to build, for a simple reason: a revision is harmful exactly when the original answer was right, so deciding whether to block it is the same as knowing whether the model was already correct. This turns the open-ended hunt for a brake into one measurable quantity, the model's self-knowledge: any brake built from a deploy-time signal is a correctness probe in disguise, and self-knowledge is far from perfect (AUROC $\approx 0.64$--$0.89$ across six model families). We call this ceiling the wall. Even white-box steering of the model's own correctness direction does not breach it: it changes how often the model revises, but harmful and beneficial revisions mov

---

### [74] Efficient Vision- Language -Action Management and Serving for Robot Factories

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.12075&hl=zh-CN&sa=X&d=2113406613175588759&ei=YNmraobGB_Ov6rQP_NLbyQ8&scisig=AIVdB-zuHOUqfuSwjVfdWSDomTNY&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=3&folt=kw-top
**作者**: D Adamopoulos, N Chanpaisit, B Fakhri, C Giannoula - arXiv preprint arXiv …, 2026
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We design Robion, the first VLA serving and management system for multirobot, multi - model requests on multi-GPU edge servers that … Efficient memory management for large language model serving with pagedattention. In Proceedings

---

### [75] Correlation-Guided Encoder Selection for Multi-Encoder Large Audio-Language Models

**链接**: https://arxiv.org/abs/2609.18041
**作者**: Pei-Jun Liao, Hung-Shin Lee, Wenze Ren, Kuo-Hsuan Hung, Hung-yi Lee, Hsin-Min Wang
**来源**: eess.AS cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-encoder fusion extends Large Audio-Language Models (LALMs) beyond speech-centric recognition, but selecting encoders via intuition or exhaustive search often introduces redundant representations and inflates an already constrained compute budget. We propose CUES (Correlation-gUided Encoder Selection), a lightweight heuristic that estimates complementarity through task- and category-level Pearson correlations between encoders' performance profiles, scoring a candidate set from single-encoder evaluations alone--without fusion training during selection. Evaluated on the XARES-LLM benchmark with a frozen SmolLM2-135M backbone (LoRA-adapted) via five-fold cross-validation, CUES consistently identifies the same configuration per track from held-out development splits alone, without using test data for selection. For the broad Track~A suite, CUES selects a cross-family trio (Whisper-medium, mHuBERT-147, and Dasheng-base), achieving a 4.3% relative gain over Whisper-medium (0.771 vs. 0.7

---

### [76] REPAIR: Resolving Long-Tail Confusion in Scientific Retrievers via Fact-Verified Iterative Refinement

**链接**: https://arxiv.org/abs/2609.18262
**作者**: Yerim Oh, Gunhee Kim
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Precise retrieval of scientific information is fundamentally constrained by long-tailed concepts and high fact-sensitivity of scientific corpora. These challenges often limit the effectiveness of dense retrievers and hallucination-prone LLM augmentation. To address this, we present REPAIR, a self-evolving data augmentation framework for scientific dense retrievers. REPAIR iteratively synthesizes training data to address knowledge gaps by cycling through diagnosis of long-tail concepts, API-guided evidence expansion, and differentiation via hard negative mining. This process effectively grounds retrieval in factual reality to resolve fine-grained distinctions. Extensive experiments demonstrate that REPAIR significantly outperforms 19 strong baselines on nine materials science and biomedical benchmarks. Our work highlights that diagnosing and factually augmenting data to long-tail deficits is essential for robust scientific retrieval.

---

### [77] SAGE: Governed Artifact Generation from Enterprise Guidelines

**链接**: https://arxiv.org/abs/2609.17775
**作者**: Mohammadreza Sediqin, Shivali Dalmia, Sumukha Thoppanahalli, Srinivasa Karthikeya Reddy Kovvuri, Abhishek Mukherji
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise guideline documents mix narrative text, complex tables, and embedded images, and converting them into structured work artifacts still takes two to three days of manual effort each. Current language and vision-language models extract from such documents but offer no governed workflow beyond extraction: no validation, no consistency checking, no traceable artifact generation. We introduce SAGE, a governed multi-stage LLM pipeline organized around a shared versioned rule store with stable identifiers, schema-validated inter-stage contracts, and end-to-end provenance tracking. Extracted rules undergo deterministic structural validation and LLM-based semantic scoring, then a consistency module that removes duplicates, flags contradictions, and surfaces specification gaps; only uncertain or flagged items reach reviewers, while high-confidence outputs are auto-approved. On 120 documents, SAGE cuts turnaround from days to 20-100 minutes, achieving a 96% document-level success rate w

---

### [78] When Audit Quality Fails to Predict Downstream Utility: A Counterfactual Study of Synthetic-Data Selectors for Low-Resource African NLP

**链接**: https://arxiv.org/abs/2609.18960
**作者**: Son Ha Xuan, Phat T. Tran-Truong, Xuan-Bach Le
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quality-aware synthetic-data selection rests on a proxy: examples that an LLM judge rates as good should also help a downstream model learn. In a controlled replay in low-resource African-language classification, we show that this proxy breaks. Across four languages (Amharic, Hausa, Swahili, Yoruba), two classification tasks (MasakhaNEWS, AfriSenti), and five matched-budget selectors, audit rankings and downstream rankings diverge. Within each cell, the Spearman between judged label correctness and Macro-F1 across selectors has mean $\rho{=}0.04$ (median $0.00$), showing that the mismatch is not an aggregation artifact. \method{}-V2, our counterfactual audit framework, produces the cleanest selected pool on three audit channels at once: highest judged label correctness ($0.904$ vs.\ $0.767$ for naive, a $17.9\%$ relative gain), lowest shortcut score, and a hard-reject rate of $0.162$ vs.\ $0.486$ for naive. AlpaGasus nevertheless leads downstream Macro-F1 ($0.202$ vs.\ $0.163$ for \met

---

### [79] The Missing "I Don't Know": Why Three Reasoning-Reliability Findings Converge on Calibrated Abstention

**链接**: https://arxiv.org/abs/2609.17686
**作者**: Srijith Ravikumar
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Three recent results describe what look like unrelated LLM reliability problems. Yin et al. (2026) show reasoning RL collapses tool-reliability representations. Suleymanov et al. (2026) show that under safety-constrained generation, large models rewrite flagged spans while small models truncate. Bastounis et al. (2024) prove any consistent-reasoning system without an implicit "I don't know" function must hallucinate infinitely often on broad problem classes. We argue these findings converge on a single intervention: calibrated abstention is what each independently identifies as the missing capability, even though the unavailability they document, a capability gap, a policy gap, and a recursion-theoretic gap, has a different source in each case. Honesty post-training has narrowed the gap in deployed models, but principled closure of the class Bastounis identifies requires a calibrated abstention function whose training signal at the leaderboard level is absent: dominant benchmarks assig

---

### [80] EviGen: Predictive Evidence Scaffolding for Verifiable Clinical Rationale Generation

**链接**: https://arxiv.org/abs/2609.18852
**作者**: Fengnan Li, Heman Burre, Liwen Sun, Roshni Varma, Matthew M. Engelhard
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Longitudinal electronic health records (EHRs) capture years of patient history across notes, codes, labs, and procedures, and contain evidence needed to reason about likely clinical outcomes. However, comprehensive clinician review of these records is impractical, and LLM-based processing is costly and often unreliable, missing some relevant observations while hallucinating others. We therefore propose EviGen, a three-layer framework for verifiable clinical rationale generation that addresses these challenges. The first layer is a patient-conditioned retriever that uses learnable queries to find evidence predictive of, not just textually relevant to, a clinical outcome and ranks it by prediction attribution scores. The second layer is an LLM generator that consumes this ranked evidence as a scaffold to produce a clinical rationale grounded in the retrieved spans. The third layer is a process-supervised verifier that checks the generated rationale at the reasoning-step level, flagging u

---

### [81] Autonomy in Check: Governor-Mediated Adaptive Security at the Edge

**链接**: https://arxiv.org/abs/2609.18338
**作者**: Ijaz Ahmad, Ijaz Ahmad, Flavio Esposito, Erkki Harjula
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adaptive security at the network edge increasingly relies on automated planners, including rule-based controllers, learned policies, and LLM-assisted agents, that translate observations into enforcement actions. Once such a planner can influence live policy state, syntactic validity is not enough. A semantically wrong action, produced from incomplete or manipulated observations, can be faithfully executed by an enforcement substrate that cannot judge mission context. We address this problem by treating the boundary between planner output and kernel enforcement input as the primary security object. We propose a split-control architecture in which an untrusted planner emits typed security intents, a deterministic governor checks each intent against safety, resource, temporal-stability, and proportionality invariants, and only admitted actions are bound to signed receipts and compiled into pre-installed eBPF map updates. The paper formalizes this trust-boundary problem, defines three thre

---

### [82] Encoder Awakening via Adapters: Effective Domain-Adaptive Fine-tuning of Speech-LLMs

**链接**: https://arxiv.org/abs/2609.17981
**作者**: Mohan Shi, Zilai Wang, Natarajan Balaji Shankar, Kaiyuan Zhang, Eray Eren, Abeer Alwan
**来源**: eess.AS cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech Large Language Models (Speech-LLMs), typically built from a pre-trained speech encoder, a modality projector, and an LLM fine-tuned with Low-Rank Adapters (LoRA), have shown strong Automatic Speech Recognition (ASR) performance on general-domain speech. However, adapting them to domain-shifted speech, such as child or dialectal speech, remains challenging under limited target-domain data. Given the dominant role of the LLM in Speech-LLMs, with cross-entropy loss applied only at the LLM output, the speech encoder may receive insufficient adaptation to new acoustic conditions. In this paper, we propose Encoder Awakening via Adapters (EAVA), a simple yet effective domain-adaptive fine-tuning method for Speech-LLM-based ASR. First, lightweight adapters are inserted into each encoder layer and trained exclusively, enabling target-domain acoustic knowledge to be incorporated into the encoder while preserving its pre-trained knowledge. Second, the full model is jointly fine-tuned on th

---

### [83] PersonaPath: Towards Knowledge-Centric Personalized Learning Path Planning

**链接**: https://arxiv.org/abs/2609.18861
**作者**: Yu Liu, Zeming Liu, Tianle Zhang, Zihao Cheng, Yuhang Guo, Kehai Chen 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adaptive learning systems commonly formulate learning path planning as Exercise-Centric (EC) recommendation, where the next step is inferred from item-level interaction logs. Evaluating goal-oriented guidance additionally requires explicit learner goals and curriculum-scale prerequisites: learners with similar exercise records may need different paths toward their targets. We therefore study Knowledge-Centric (KC) personalized learning path planning, where a planner must reason over learner profiles, mastery states, and prerequisite knowledge structures to decide which textbook, unit, and concept should be studied next. To support this setting, we introduce PersonaPath, a benchmark that pairs 2,000 fine-grained learner personas with a hierarchical knowledge graph of 347 textbooks, 1,751 units, and 4,092 concepts across 77 subjects. We evaluate representative LLMs on PersonaPath. Results show that even the strongest LLM reaches only a 29.5% final pass rate in Basic Education, and that t

---

### [84] The Inference Engineering Pareto Atlas: Which Optimizations Dominate the Cost, Quality, and Latency Frontier?

**链接**: https://arxiv.org/abs/2609.17863
**作者**: Srikanta Datta Tumkur, Jay Iyer, Mehar Simhadri, Sai Pavan Kumar, Sai Kapil Kumar, Ramesh Nampelly
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM inference optimizations report speedups on different models, GPUs, prompts, and quality metrics, making them hard to compare or combine. We build a cost, quality, and latency Pareto atlas to identify the best configurations for different deployment constraints. Since exhaustive testing is impractical, we measure 54 configurations of Qwen2.5-7B-Instruct running on vLLM 0.12 across L4, A100, and H100 GPUs and use these anchors to calibrate a simulator. It reproduces measurements at anchored batch sizes, with cross campaign drift below 1.5 percent. A separate quality evaluation tests FP16, AWQ 4bit, FP8 weights, and FP8 KV cache on 200 GSM8K questions with five examples per prompt. Sparse attention is evaluated only in simulation. On the calibrated grid, 18 of 36 configurations reach the Pareto frontier. Combined methods reach it more often than individual methods, with 9 of 15 combinations versus 9 of 21 single methods. Quality testing changes the winners. AWQ 4bit reduces per token 

---

### [85] Relationally Guided Use Case Modeling with LLMs

**链接**: https://arxiv.org/abs/2609.18291
**作者**: Guangyu Wang, Bangqi Li, Ji Wu, Zhijun Shao
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Use case flows are important elements of use case modeling because they support downstream software engineering activities, including requirements analysis, architectural and detailed design, and test case generation. However, constructing them manually is costly and expertise-intensive, while existing automated approaches still struggle to preserve semantic consistency, control-flow logic, data-flow logic, and the intended system boundary, especially when identifying branch points and generating alternative flows. To address this problem, we propose FlowGen for complete use case flow construction. FlowGen uses LLM-based Semantic Information Processing (SIP) to extract semantic elements, constructs a Semantic Relational Graph (SRG) encoded by an enhanced R-GAT for basic flow generation (BFGen), and further supports branch point prediction through BPP and branch-conditioned alternative flow generation through AFGen. Evaluations on 13 public and 7 industrial datasets show that FlowGen co

---

### [86] PULSE: Unlocking Practical Image Compression on Single-Thread CPU

**链接**: https://arxiv.org/abs/2609.18602
**作者**: Zhaoyang Jia, Tianyu Zhang, Zihan Zheng, Wenxuan Xie, Jiahao Li, Bin Li 等 (8 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite recent progress in learned image compression, existing methods remain computationally expensive on resource-constrained hardware, particularly CPUs. We introduce PULSE, a practical codec that enables (1) low-latency decoding on diverse hardware platforms with an ultra-low-complexity 5.2 kMAC/pixel neural receiver, and (2) efficient bit-exact entropy coding with an integer linear CDF predictor and a meta prior. To recover compression performance under this tight budget, we introduce an agentic evolution process guided by heuristic probes that iteratively improves the architecture through human-LLM collaboration. PULSE decodes a 1080p image in 126 ms on a single CPU thread while achieving compression performance comparable to HM. After perceptual optimization, PULSE competes with larger perceptual codecs like MS-ILLM. Codes are at https://github.com/microsoft/GenCodec/tree/main/PULSE

---

### [87] Benchmarking Large Language Models for Biomedical Relation Extraction

**链接**: https://arxiv.org/abs/2609.19071
**作者**: Claudiu Creanga, Teodor Marchitan, Liviu P. Dinu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Extracting SNP-phenotype associations from biomedical literature is vital but challenging. We benchmarked diverse NLP models, including MLMs, hybrid architectures, and state-of-the-art LLMs (Gemini 2.0, OpenAI O-series, Qwen, Mistral), on the SNPPhenA corpus across three tasks: sentence-level, abstract-level, and association strength classification. OpenAI O1 achieved state-of-the-art (SOTA) results using few-shot learning for non-finetuned sentence-level classification (F1 0.89) and established a new SOTA for abstract-level classification (F1 0.82). Association strength classification proved difficult, though fine-tuned Gemini 2.0 Pro performed best (F1 0.60) in the first LLM evaluation of this task. Proprietary LLMs, especially in few-shot (O1) or fine-tuned (Gemini 2.0 Pro) settings, significantly outperformed other models. These findings confirm the power of modern LLMs for genomic knowledge extraction.

---

### [88] Clueing up LLMs with Tool-Augmented Deductive Reasoning

**链接**: https://arxiv.org/abs/2609.18736
**作者**: Rebecca Ansell, Autumn Toney-Wails
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite recent advances in large language models (LLMs), performing logically consistent deductive reasoning over extended interactions remains challenging. Tasks that require integrating evidence across multiple reasoning steps, maintaining consistency with prior inferences, and updating beliefs under new constraints can surface limitations in current models while providing a useful testbed for evaluating reasoning enhancements. In this paper, we implement a text-based, multi-agent version of the classic board game Clue as an environment to evaluate multi-step, agentic deductive reasoning. In this setting, agents must infer hidden information from a sequence of observations, maintain consistency across turns, and reason over an evolving set of logical constraints. We instantiate six LLM-based agents (GPT-4o-mini and Gemini-2.5-Flash) as players that engage in turn-based gameplay; using three agents per model family, we establish baseline performance across repeated games. We then intr

---

### [89] What Counts as Strategic Reasoning? A Systematic Mapping of Chess Research on Humans, Engines, and Language Models

**链接**: https://arxiv.org/abs/2609.18286
**作者**: Paolo Ciancarini and Remo Pareschi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chess has long served as a model domain for studying search, expertise, decision-making, and artificial intelligence. The emergence of large language models (LLMs) has renewed the relevance of chess as a controlled environment for investigating strategic reasoning and comparing human and artificial decision-making. We present a systematic mapping study of recent research spanning human players, classical chess engines, neural and reinforcement-learning systems, LLMs, and hybrid approaches. The final map comprises 84 core study families, classified according to agent type, strategic-reasoning stages, and evaluation dimensions. The map reveals a literature strongly concentrated on situation assessment, evaluation, and action selection, while explicit planning, explanation, metacognition, and human--AI collaboration remain less explored. LLM research places particular emphasis on state representation and generalization, whereas grounded explanation appears more frequently in hybrid approa

---

### [90] M-SQE: Multilingual Skill Quality Estimation for Enhancing Language Equality in Agentic Skill Use

**链接**: https://arxiv.org/abs/2609.18445
**作者**: Yilun Liu, Shimin Tao, Minggui He, Chenxin Liu, Li Zhang, Chen Liu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent skills, reusable procedural documents that extend LLM agents beyond their parametric memory, have become an important interface for deploying agents on real-world tasks. Community-maintained skill libraries built around this interface are growing rapidly. However, this ecosystem remains deeply English-centric: our audit finds that low-resource languages such as Swahili and Hindi have no in-language skill content, so retrieval often returns a skill written in a different language than the query, degrading accuracy and recall. A practical solution is to synthesize in-language skills for retrieval but the quality can be unreliable, so relevance in this setting alone often surfaces a related but unusable candidate. To address this, we propose M-SQE, a post-retrieval Multilingual Skill Quality Estimation framework that scores candidates via a Theory view for intrinsic quality and an Action view for task-grounded utility, unified into a domain-conditioned final score. We evaluate M-SQE

---

### [91] "We Are Tired of Explaining": Communication Practice and AI Roleplay Training for Community Health Workers in Rural India

**链接**: https://arxiv.org/abs/2609.17710
**作者**: Neil K. R. Sehgal and Sunny Rai and Sai Preethi Matam and Khushboo Gupta and Hamid Abdullah and Mohit Jain and Sharath Chandra Guntuku
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Community health workers (CHWs) in the Global South increasingly encounter AI-powered tools, yet the counseling work central to their role remains largely unsupported. We study communication practices among Accredited Social Health Activists (ASHAs) in rural Rajasthan, India, through simulated family-planning calls, semi-structured interviews, and an LLM chatbot roleplay design-probe with 20 participants. In calls, ASHAs often responded to social or material concerns by shifting to health-risk information, denying concerns, promising unspecified help, or listing medical solutions with limited explanation. A smaller set of responses instead engaged concerns, sought permission before involving family members, or left decisions with beneficiaries. We interpret these patterns through Motivational Interviewing, emphasizing restraint from correcting, persuading, or over-solving. Drawing across observed calls, interviews, and probe reactions, we derive design considerations for AI roleplay tr

---

### [92] Democratizing Clinical Tumor Whole Genome Sequencing: 18-hour End-to-end Analysis via Trillion-parameter Large Language Models Locally Deployed on Consumer-grade Hardware

**链接**: https://arxiv.org/abs/2609.17620
**作者**: Rui Xiao and Yili Xu
**来源**: q-bio.GN cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whole genome sequencing (WGS) is essential for precision oncology, yet its clinical adoption remains limited by prohibitive computational costs and multi-day turnaround times. This work presents a fully localized low-resource framework enabling stable deployment of a trillion-parameter biomedical LLM on a single consumer-grade RTX 4060 laptop with 32GB system memory and 8GB VRAM, as well as on routine clinical workstations in general hospitals, completing the entire tumor-paired WGS workflow from raw FASTQ input to clinical-grade full-variation-spectrum report output. Under standard 30X depth configurations, our implementation finishes a single tumor-paired WGS analysis within 18 hours, achieving 99.62% F1 score for somatic variant detection with over 99.9% concordance to the industrial-standard A100 cluster pipeline, fully meeting clinical oncology accuracy requirements. Quantitative profiling shows adaptive heterogeneous memory scheduling accounts for 71% of total execution time, whi

---

### [93] Compiled Agency: Frontier General-Purpose Coding Agents Build Winning Game Players from Bare Interaction - from Flappy Bird to StarCraft II and Civilization

**链接**: https://arxiv.org/abs/2609.18996
**作者**: Joey Xiao, Haonan Huang
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have repeatedly struggled to convert knowledge of a game into competent play, even when researchers build the agent around the model - supplying perception, memory, skill libraries, planners, or executable-policy scaffolds. Rapid progress in coding agents raises two sharper questions: can frontier models now win games at all, and can they win them unaided, building the entire player themselves? We introduce Gauntlet, a develop-freeze-evaluate framework that ports games from small arcades to full commercial-scale titles, behind one deliberately bare contract: a general-purpose coding agent receives a game description, a raw observation/action interface, and an empty policy file - no strategy, no algorithm, no architecture. In a single autonomous session the agent experiments with the live game and engineers a standalone controller; we freeze the result and score it on held-out instances with zero model calls during play. On an unpublished procedural roguelike, held-out succes

---

### [94] Apply-<x>Mag: One Tool to Support Many Inclusive Design Methods

**链接**: https://arxiv.org/abs/2609.17948
**作者**: Sadia Afroz, Rudrajit Choudhuri, Fatima A. Moussaoui, Amreeta Chatterjee, Margaret Burnett, Anita Sarma
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Doing inclusive design in HCI practice can be labor-intensive, a costly barrier that some companies and HCI practitioners may be unwilling or unable to overcome. Yet, not doing inclusive design is costly too, in the form of UX barriers that disproportionately disadvantage under-served user populations. To address this problem, we introduce Apply-<x>Mag, an LLM-powered tool to support HCI practitioners' work to design their products inclusively to wide ranges of users. Apply-<x>Mag is general, supporting any inclusive design method that can be expressed as <x>Mags (i.e., using attribute ranges and heuristics). It is also effective: Empirical results with researcher and practitioner teams using various combinations of two <x>Mags on 7 products showed Apply-<x>Mag precision averaging 90-99% and recall averaging 82-89%. Further, its environmental costs were reasonable, costing about the same resources as 2-4 ordinary Google searches.

---

### [95] BENCHCOMPASS: From Scores to Signals for Training and Harness Decisions in Payment-Domain LLMs

**链接**: https://arxiv.org/abs/2609.18270
**作者**: Sijie Dong and Wei Ren and Xuanwei Hu and Jiawei Luo and Zifan Wang and Xiaoyun Feng and Hui Cai and Lyuxin Xue and Peng Lu and Jianshe Li and Xin Zhang and Wei Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Payment operations are a critical financial infrastructure, but the value of large language models in this domain remains unclear because payment rules change quickly, evidence is fragmented, and decisions depend on transaction state, participant role, region, and payment rail. Existing benchmarks do not isolate whether failures come from missing payment-rule knowledge, poor use of supplied evidence, or brittleness under imperfect harness inputs. We introduce BENCHCOMPASS, a payment-domain benchmark whose construction pipeline builds scenario-grounded tasks from typed evidence packs, applies LLM-based quality checks, creates task-input attack variants, and reserves final item admission for domain experts. The release contains an expert-reviewed Pro benchmark covering payment knowledge, context-grounded scenario reasoning, and Attacked Open robustness, plus a lower-assurance Normal pool for inspection and future curation. Across 16 model variants, BENCHCOMPASS shows qualitatively differ

---

### [96] StableEval Arena: A Cost-Aware Agentic Benchmark for Stablecoin Price Stability Prediction

**链接**: https://arxiv.org/abs/2609.18949
**作者**: Sean Wan, Dongping Liu, Luyao Zhang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce StableEval Arena, a cost-aware benchmark framework for evaluating agentic AI systems on stablecoin peg-risk prediction. StableEval Arena evaluates LLM-backed agentic systems on diagnosing peg stress and forecasting deviations from the one-dollar peg over a hidden seven-day horizon, using leakage-safe historical replay with exchange price-volume data and market-context features. We report two complementary experiment blocks: a 120-case stress-enriched validation block and a 507-case natural-distribution full-arena evaluation block. Across six LLM-backed agent configurations and baselines, StableEval Arena measures prediction quality, calibrated-label behavior, structured-output reliability, latency, token consumption, and estimated inference cost. Rather than ranking agents by accuracy alone, the framework treats trustworthiness as a joint property of forecast quality, operational reliability, and computational cost. The results show a gap between protocol-following reliabi

---

### [97] Beyond Outcomes: Dual-View Relational Learning for Efficient Agent Benchmarking

**链接**: https://arxiv.org/abs/2609.18909
**作者**: Xinshuai Guo, Junjie Wu, Dolly Deng, Yinghui Li, Hai-Tao Zheng, Suncong Zheng 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent benchmarks are substantially more costly to evaluate than conventional LLM benchmarks. Benchmark compression is therefore a natural solution, yet existing methods primarily model redundancy in task--model final-score distributions, which is important in agentic evaluation. To address this limitation, we analyze large-scale trajectories and identify six complementary process signals that are systematically associated with final agent performance. To disentangle agent performance redundancy from a complete perspective, we propose DualViewEval, an agent benchmark compression method that jointly exploits outcome and process relations to learn an exact-size miniset and predict the full-benchmark scores. Across five agent benchmarks and five representative baselines, DualViewEval achieves the best results in all datasets. With only 20 tasks, it achieves $24\times$--$40\times$ compression on APEX-Agents and BFCL, reducing mean absolute error (MAE) by $14.5\%$--$28.2\%$ over the stronges

---

### [98] I code or AI code: A comparative evaluation of AI-rated scores in classroom observations

**链接**: https://arxiv.org/abs/2609.18274
**作者**: Y. Fong, J. Xiang, T.Y.D. Chan, K. Lee and E.Y.H. Lau
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Classroom observations are widely recognized as a key tool for establishing benchmarks of education quality and guiding pedagogical improvement, yet they remain resource-intensive and dependent on trained observers. This study evaluated the feasibility of using a LLM (GPT-5 model) to score teacher-child interactions in early childhood classrooms, benchmarked against human raters. The study analyzed 87 video-recorded observations from 38 classrooms across 30 kindergartens in Hong Kong. Using observation transcripts, the AI model was configured to apply the full Classroom Assessment Scoring System (CLASS) framework. AI-rated scores were then compared with human ratings by examining correlations and differences in mean scores of the CLASS domains and dimensions. The results showed greater convergence between AI and raters for the Emotional Support domain and, in particular, the Quality of Feedback dimension, which captures how teachers use feedback to extend children's learning. Greater d

---

### [99] PACT: Can Enterprise AI Assistants Be Trusted Under Pressure?

**链接**: https://arxiv.org/abs/2609.18605
**作者**: Mika Okamoto, Ansel Kaplan Erol
**来源**: cs.CL cs.AI cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As corporate AI adoption continues to grow, enterprise-grade LLM agents are being deployed into sensitive contexts such as hiring, healthcare, and finance. In these contexts, compliance with rules specified in an agent's system context is a first-order legal concern. Currently, no evaluation framework systematically measures which LLM models tend to violate compliance rules, especially under pressure from a persistent user, a hurried manager, or circumstances where violation is convenient or attractive. We introduce PACT (Pressure-Applied Compliance Testing), a benchmark for rule-following under pressure in AI agents assisting employees in daily tasks across twelve regulated enterprise domains and forty-eight scenarios, each set in a realistic multi-turn conversation. Each benchmark item pairs a standing rule against a rule-violating shortcut, and applies a battery of pressures across different wordings and system-prompt modes. We construct PACT component by component under strict LLM-

---

### [100] Knowledge-Graph Based Augmentation versus Retrieval Augmented Generation for Cultural-Related Question Answering

**链接**: https://arxiv.org/abs/2609.18317
**作者**: Pablo Poulenard, Yannis Karmim and Valentin Barri\`ere
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) suffer from a long-tail deficit: culturally specific facts, particularly those concerning underrepresented regions such as Latin America, appear too rarely in pretraining corpora to be reliably memorized. Retrieval-Augmented Generation (RAG) addresses this by grounding generation in external text, but structured alternatives such as Knowledge Graphs (KGs) offer tighter control over what enters the context, along with potential gains in explainability and updatability. We benchmark Graph-RAG against standard RAG on LatamQA, a culturally grounded multiple-choice dataset spanning eight thematic categories. The graphs are built end-to-end from Wikipedia articles with KGGen, a recent open-domain extractor, without manual curation in our main setting. G-Retriever is competitive with RAG and reduces the error of the base LLM by 72\% with a standard KG and 78\% with a benchmark-aware variant, the gap to RAG narrowing further as the graph is oriented toward task-rel

---

### [101] WFM: Wiki Foundation Model for Complex Agentic Reasoning

**链接**: https://arxiv.org/abs/2609.18182
**作者**: Junnan Dong, Linhao Luo, Senlei Zhang, Gong Chen, Taian Guo, Yifei Yu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-world agents fundamentally require persistent non-parametric knowledge for dynamic reasoning, i.e., long-term memory and retrieval-augmented generation. While graphs have shown reliable advantages in providing structured evidence, the sparse graph representations naturally restrict machine readability and semantic density required for complex agentic workflows. Driven by this limitation, the entire industry is witnessing a paradigm shift from traditional sparse graphs to LLM Wiki, an agent-native knowledge representation that couples dense document contexts with markdown files containing multi-layered topological linkages. However, parameterizing such rich semantics is challenging to encode dense textual contexts using traditional sparse graph embeddings. Moreover, learning LLM Wiki with existing graph encoders could overwhelm distributed system overheads that hinder deployment in large-scale commercial scenarios. To this end, we propose a novel paradigm Wiki Foundation Model, i.e

---

### [102] EarStreAM: A Closed-Loop Earable System for Personalized Stress-Adaptive Meditation

**链接**: https://arxiv.org/abs/2609.19127
**作者**: Jonas Hummel, Luisa Faust, Elias M\"uller, Eva Bertog, Valeria Zitz, Marius Johannes Prill 等 (10 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present EarStreAM, a closed-loop earable system for stress-adaptive meditation that integrates in-ear physiological sensing with personalized, real-time intervention. Leveraging OpenEarable 2.0's multimodal sensing, EarStreAM continuously monitors physiological signals and detects elevated stress from heart rate and heart rate variability. Upon detection, the system initiates a personalized guided meditation generated by an LLM and adapted in real time to the user's stress state. The demo offers a hands-on experience of stress-adaptive meditation in two modes: a biosignal-adaptive meditation with optional stress induction to illustrate closed-loop adaptation, and a meditation-only mode focusing on EarStreAM's generative personalization capabilities. The demo highlights how in-ear sensing, closed-loop adaptation, and personalized generative meditation can be integrated into an earable system for real-time stress support in demanding office work contexts.

---

### [103] Align, Integrate, and Fire: Efficient Token-Level Alignment for Zero-Shot SpeechLLMs

**链接**: https://arxiv.org/abs/2609.18516
**作者**: Abderrahmane Issam, Yusuf Can Semerci, Jan Scholtes, Gerasimos Spanakis
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Models excel in natural language processing, efficiently extending their capabilities to spoken input remains a significant challenge. Existing methods for building SpeechLLMs often rely on computationally expensive full-model fine-tuning, or employ parameter-efficient projectors that suffer from inefficient token sequence lengths and costly full-model supervision. In this paper, we introduce Aligned Continuous Integrate-and-Fire, a highly efficient framework for zero-shot speech processing. Our method dynamically compresses continuous acoustic frames into the exact discrete token length of the target text utilizing explicit Dynamic Time Warping alignments. This allows our initial training stage to establish a robust acoustic-to-semantic bridge using lightweight distance metrics, entirely bypassing the computationally expensive LLM forward pass. For subsequent fine-tuning, we propose a memory-efficient knowledge distillation objective that targets a single LLM laye

---

### [104] Dependency-Aware Trajectory Refinement for Efficient Multi-Turn Agent Fine-Tuning

**链接**: https://arxiv.org/abs/2609.18417
**作者**: Zhuo Chen, Zhen Zhang, Xinyu Wang, Kewei Tu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn agent trajectories often contain redundant rounds (failed tool calls, parallel sub-queries, verification-only steps) that inflate both training and inference cost. We propose viewing each trajectory as a \emph{round-level dependency DAG} that exposes which rounds are globally load-bearing for the final answer, and fine-tune agents on trajectories refined through this DAG. Given an LLM-annotated DAG, these edits are deterministic and interpretable, with optional rephrasing. Models trained on these refined trajectories consistently outperform those trained on the original trajectories at lower inference cost. Specifically, across four multi-modal QA benchmarks, our refinements improve downstream accuracy by up to $1.7$\,pp over vanilla SFT (and $5.7$\,pp over an LLM-deletion baseline) while reducing per-sample inference messages by up to approximately $40\%$ and inference tokens by up to approximately $48\%$, translating to substantial savings in compute and serving cost. Code

---

### [105] Circuit- MLLM : Topological Logic-Guided Latent-Space Visual Reasoning for Circuit Schematic Understanding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.15668&hl=zh-CN&sa=X&d=5774447730547569368&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-x7uEtai0_3t1z5hShpkZ97&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: J Deng, Y Jiang, W Huang, X Li, Q Sun, C Zhuo - arXiv preprint arXiv:2609.15668 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To address this, we propose Circuit- MLLM , a multimodal reasoning framework that reformulates circuit topology analysis as a process of … Across diverse circuit analysis tasks, Circuit- MLLM consistently outperforms strong baselines, notably

---

### [106] Scaling Articulated Rationales for MLLM-based Recommendation

**链接**: https://arxiv.org/abs/2609.17639
**作者**: Haoke Xiao, Yueyang Liu, Yuhui Zhang, Xiang Chen, Yufei Liu, Jia Xu 等 (10 人)
**来源**: cs.IR cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern recommendation systems largely infer user preferences from implicit behaviors such as clicks, watch time, and negative feedback, but these signals reveal what users do rather than why they like or dislike content. This work studies articulated user rationales (AURs), i.e., users' natural-language explanations of their preferences, as a new class of polarity-aware and reason-level textual signals for recommendation. Despite their potential value, AURs are difficult to use in industrial systems because they are naturally sparse, often low-quality, and only cover a small fraction of items. We present SARA (Scaling Articulated Rationales), an industrial framework that turns sparse AURs into scalable recommendation signals. SARA first builds a data engine that elicits and curates AURs from 240M Kuaishou Live users, producing SARA-HQ, a quality-controlled and author-centric rationale dataset. It then aligns a general-purpose MLLM into SARA-7B through large-scale SFT and Quality-Refini

---

### [107] What Did the MLLM Hear? Token-Level Spectro-Temporal Grounding for Audio MLLM Explainability

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2609.12663&hl=zh-CN&sa=X&d=15298377717750229957&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-weUmmGw5tPZcn2IU7GQl2J&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=2&folt=kw-top
**作者**: L Cascone, V Fraenza, M Nappi, F Narducci, B Simone - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Audio-based Multimodal Large Language Models (MLLMs) can generate detailed natural-language descriptions of complex acoustic scenes, yet it remains unclear which parts of the input audio support each generated token. This is particularly

---

### [108] Evaluation of MLLM -Agnostic Plug-and-Play Keyframe Selection Methods for Long Video Understanding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.13250&hl=zh-CN&sa=X&d=1657768890165056812&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-zrk5FBWelZ2naQHTNJBvtP&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: D Sarkar, MS Islam, L Liang - arXiv preprint arXiv:2609.13250, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> (i) Retraining an MLLM on a large video corpus and/or extending its input length; (ii) Training an adapter for a specific MLLM that takes the entire … a training-free, plug-and-play (PaP) adapter that is MLLM -agnostic. We refer to the third approach as PaP

---

### [109] Humans Outperform Multimodal Large Language Models (MLLMs) in Non-Verbal Tests of Mental Rotation and Figural Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2079-3200/14/9/219&hl=zh-CN&sa=X&d=17100802081611128387&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-zVMTB711p5hUlh8s4H6TVK&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=3&folt=kw-top
**作者**: J Lesigang, J Pietschnig - Journal of Intelligence, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> MLLM performance was evaluated via percentile ranks. The human online sample outperformed MLLMs in both mental rotation ( MLLM percentile rank ranges 0 to 7 on most tests and conditions) as well as figural reasoning ( MLLM percentile

---

### [110] From Density to Biopsy Decisions and Malignancy Prediction: A Benchmark Study of Multimodal Large Language Models Against Radiologists in Digital and Contrast …

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.14676&hl=zh-CN&sa=X&d=7332463579618781368&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-yBAaRd2AAsdYJFRCKDCYii&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=8&folt=kw-top
**作者**: AA Ardakani, A Mohammadi, TY Kuzan, BN Kuzan… - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In comparison, the without-mask MLLM group had accuracies between 35.35% and 40.93%, while the with-mask MLLM group yielded … The withoutmask MLLM group had accuracies between 64.17% and 71.16%, while the with-mask MLLM

---

### [111] One Skill Does Not Fit All: Automatic Discovery and Taxonomy-Guided Routing of Frame-Selection Skills for Long-Video Question Answering

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.12517&hl=zh-CN&sa=X&d=12126115312794033943&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-whZatEPLYRfBLue7dzyCq0&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=9&folt=kw-top
**作者**: J Hu, Z Cheng, D Li, W Li, Z Liu, S Gong - arXiv preprint arXiv:2609.12517 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> At inference time, each question is assigned one skill, which selects the frames used in a single inference of the frozen video MLLM . Across five … However, the selected frames define what the frozen MLLM can observe before it answers a

---

### [112] Concept-Grounded Reasoning with Prompt-Driven Localization for Interpretable Structured Report Generation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.15334&hl=zh-CN&sa=X&d=9179644697299401552&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-zBjVc2FbdTM8e2K_Fp79Cg&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=7&folt=kw-top
**作者**: X Xu, H Lin, J Xu, H Wang, L Wang, L Hu 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The resulting textual concept tokens are combined with maskmodulated visual features within an MLLM to enable structured report … Following concept extraction, we incorporate the spatial image-level concept Msam into the visual representations

---

### [113] MedVA: An End-to-End Neuro-Symbolic Agentic System for Medical Volume Visualization

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.14874&hl=zh-CN&sa=X&d=1437307190481451960&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-wiHEC88UF2sGKEgX7jEJwg&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=4&folt=kw-top
**作者**: H An, S Kim, M Kang, E Lee, B Sheng, L Bi 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> MedVA, which incorporates explicit clinical knowledge to complement MLLM -based reasoning. The system establishes a clinically grounded … The agent combines MLLM -based semantic interpretation with symbolic reasoning over established

---

### [114] P‐4.8: A Spatial‐Intelligence‐Driven Framework for Cultural Heritage Digital Twins

**链接**: https://scholar.google.com/scholar_url?url=https://sid.onlinelibrary.wiley.com/doi/abs/10.1002/sdtp.70003_323&hl=zh-CN&sa=X&d=10575573487958859710&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-ySjN5LCHldo1GMf4lwDeLE&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=6&folt=kw-top
**作者**: J Wu, Y Yin, B Wen, T Leng - SID Symposium Digest of Technical Papers, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To meet both spatial prediction needs and semantic interaction needs in ruins scenes, the system uses a dual-engine mechanism in which the WM and the MLLM work together. Based on the current digital twin state, spatial constraints, and

---

### [115] AURA: Unified Multimodal Framework for Conversational Music Editing

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.14344&hl=zh-CN&sa=X&d=16775244899688065453&ei=YNmraveAEPevieoP7OrF8A4&scisig=AIVdB-yHC8OJ2I4noGSOcO5PAHLH&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=5&folt=kw-top
**作者**: QH Trinh, MV Nguyen, D Jha - arXiv preprint arXiv:2609.14344, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> 1, AURA comprises an MLLM , concept and audio projectors, a concept-to-audio (C2A) module plugged in the MusicGen decoder. The pretrained MLLM and MusicGen … When no audio edit is required, the MLLM produces only a textual response and

---

### [116] PRSEPTransformer- EEG : source-space sLORETA and residual transformers for robust motor imagery and execution EEG decoding

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-70417-5_reference.pdf&hl=zh-CN&sa=X&d=8609867557916185440&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-wCXT0z3AVD3CRJ_dPumkvz&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: SM Kaviri, R Vinjamuri - Scientific Reports, 2026
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> Decoding motor intentions from non-invasive scalp EEG remains a core challenge in brain–computer interface research, due to spatial blurring, low signal-to-noise ratio, and inter-subject variability. This work introduces PRSEPTransformer- EEG , a unified

---

### [117] Sparse Bayesian Modeling of EEG Channel Interactions Improves P300 Brain-Computer Interface Performance

**链接**: https://arxiv.org/abs/2602.17772
**作者**: Guoxuan Ma, Yuan Zhong, Moyan Li, Yuxiao Nie and Jian Kang
**来源**: stat.ME cs.LG
**匹配关键词**: EEG, Brain-Computer Interface
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [118] Dataset-Dependent Effects of Cross-Depth Aggregation and Soft-Routed Experts in EEG Foundation Model Fine-Tuning

**链接**: https://arxiv.org/abs/2609.17886
**作者**: Mingyang Jiang, Yamin Li, Daniel Moyer, Fan Ma, Hua Xu, Catie Chang
**来源**: cs.LG
**匹配关键词**: EEG, EEG Foundation Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EEG decoding tasks can rely on different temporal dynamics and cross-channel relationships. We test whether specialized modules improve a fully fine-tuned EEG foundation model by augmenting CBraMod with cross-depth Attention Residuals (AttnRes) and two soft-routed expert banks. Across matched three-seed experiments on FACED, ISRUC, SEED-V, and PhysioNet-MI, the complete model changes mean balanced accuracy relative to full fine-tuning by -0.12, +1.27, +0.77, and -1.27 points, respectively. AttnRes alone improves mean balanced accuracy on three datasets, whereas adding experts on top of AttnRes helps only FACED and SEED-V. These gains come with substantial overhead: AttnRes requires 2.11 to 2.88x runtime and 1.78 to 2.67x memory, while the complete model requires 2.41 to 3.04x runtime and 1.86 to 2.85x memory. Overall, the added modules produce dataset-dependent, sometimes opposing effects rather than consistent gains over full fine-tuning.

---

### [119] EEG -Xplain: Decoding Neural Black-Boxes of EEG Foundation Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.15687&hl=zh-CN&sa=X&d=18333963730833831757&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-w6RCJXgVeyDhhIfYgpklvF&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: H Ma, J Wang - arXiv preprint arXiv:2609.15687, 2026
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> for interpreting EEG foundation models … EEG channels and visualizes their distributions using topographic maps. Temporally, it highlights decision-relevant signal segments through attribution heatmaps. In the frequency domain, it quantifies

---

### [120] An explainable multi-modal graph learning framework with attention-based GCN-GAT for EEG -based depression detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-71072-6_reference.pdf&hl=zh-CN&sa=X&d=8756194652176281168&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-yY5nauHmXiVXb14b1Pv-Zm&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: ES Abdolkarimi, Z Hosseini, A Barati, MH Habibi - Scientific Reports, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Major Depressive Disorder (MDD) is phenotypic and neurophysiologically heterogeneous, and developing reliable computational models for it requires careful control of information leakage, dataset heterogeneity, and contributions from

---

### [121] Distinct spatiotemporal patterns of EEG -estimated brain source activity associated with thermal comfort and discomfort

**链接**: https://scholar.google.com/scholar_url?url=https://www.tandfonline.com/doi/pdf/10.1080/23328940.2026.2728901&hl=zh-CN&sa=X&d=16808997982403896656&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-xIIj9P6kJ4FJsCivD1kU0R&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: H Watanabe, S Shibuya, T Sugi, K Saito, K Nagashima - Temperature, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Thermal comfort and discomfort are important factors that activate human thermoregulatory behavior. However, little is known regarding the underlying neural mechanisms. This study examined the spatiotemporal patterns of brain source

---

### [122] Evidence Consistent with Accelerated Inhibitory Build-up Following Stronger Subliminal Motor Activation: An EEG Trajectory-Fitting Analysis

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1053811926005525&hl=zh-CN&sa=X&d=15709746099264447342&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-wgNBzeI8FnYwBeD6F1IByC&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: Y Wang, M Dong, P Zhang, J Cao, Y Wang - NeuroImage, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Subliminal motor inhibition is a crucial form of unconscious cognitive control that protects the sensorimotor system from interference to some extent. A large body of evidence has shown that this inhibition is strengthened in response to strong

---

### [123] A Survey on Bridging EEG Signals and Generative AI: From Image and Text to Beyond

**链接**: https://arxiv.org/abs/2502.12048
**作者**: Shreya Shukla, Jose Torres, Akshaj Murhekar, Christina Liu, Abhijit Mishra, Jacek Gwizdka 等 (7 人)
**来源**: cs.AI cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] End‐to‐End EEG ‐Based Schizophrenia Detection via Hybrid Temporal–Spatial Dependency Learning

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.70424&hl=zh-CN&sa=X&d=13706044979711548749&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-yFdCXCJls3_HBJYu2L1unF&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: P Chen, X Yang, H Zhang, Y Huang, H Feng, Y Wang - Expert Systems 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Learning Network (HTSD), for EEG - based SZ detection directly from raw EEG signals. The proposed HTSD integrates three … EEG - based SZ detection framework that learns directly from raw EEG signals, reducing the reliance on handcrafted

---

### [125] Non-Invasive Dry EEG Electrodes: From Laboratory Prototypes to Wearable Neurotechnology Systems

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0924424726010605&hl=zh-CN&sa=X&d=10642128853585629105&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-yGFEokcNCQHGEKz8IRmMEd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: Z Razaghi, R Mohammadpour, R Ebrahimpour - Sensors and Actuators A: Physical, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Electroencephalography ( EEG ) has evolved from a clinical research modality into … This review provides a comprehensive overview of the evolution of dry EEG from early … signal processing, large-scale dry EEG datasets, and

---

### [126] NeuroECG: ECGFounder-Based Deep ECG Representation for EEG-Free Neurological Prognostication After Cardiac Arrest

**链接**: https://arxiv.org/abs/2609.18891
**作者**: Jiaju Gao, Yi Zhao, Chenyang Xu, Yuxi Zhou, Hao Wang
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Neurological prognostication after cardiac arrest commonly relies on electroencephalography (EEG). However, EEG demands high clinical resources. Bedside electrocardiography (ECG) is standard and low-cost. Yet, its value for predicting neurological outcomes remains underexplored. In this study, we propose NeuroECG, an ECGFounder-based deep representation framework for EEG-free auxiliary prognostication. NeuroECG adapts a pretrained ECG foundation model via task-specific fine-tuning. We implement a gradual unfreezing strategy on single-channel bedside monitoring ECG. Multiple ECG segments per patient are encoded into segment-level deep features. These embeddings are aggregated via quantile pooling ($q = 0.24$) and compressed using principal component analysis (PCA). Experiments on 412 ECG-available patients from the multicenter I-CARE database show that the adapted ECGFounder backbone achieves the best performance among ECG-only backbone baselines, with a test AUROC of 0.7333. We further

---

### [127] Thermal and EEG responses of Chinese urban and rural older women to different lower-body heating modes in winter

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0378778826013289&hl=zh-CN&sa=X&d=17762139918076029708&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-wuSqWCcfslhnLjl6p68ypL&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: Y Wu, S Zheng, Y Ren, Y Zhou - Energy and Buildings, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Thermal-response differences between young and older adults are well documented, but variations within older populations with different residential backgrounds remain unclear. In this study, thirty older women (15 urban and 15 rural) who lived in

---

### [128] BRIDGE- EEG : Bridging Self-Supervised Pretraining and Efficient Deployment for Cross-Dataset EEG Classification

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.12218&hl=zh-CN&sa=X&d=4261554299317128329&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-xU45mn-RqCAiMCfut-nmUv&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: MR Chowdhury, C Zhou, H Yu, G Datta, S Sen - arXiv preprint arXiv:2609.12218, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> - EEG , a pipeline for efficient multi-task EEG classification that preserves the benefits of pretraining while enabling deployment on constrained hardware. First, we introduce a unified preprocessing that maps heterogeneous EEG … ) using

---

### [129] Electroencephalography as a biomarker of brain function in domestic ruminants: a systematic review and critical appraisal

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0034528826003462&hl=zh-CN&sa=X&d=2580071705588791669&ei=X9mratj4O9K2ieoPlf7TyAo&scisig=AIVdB-zSg7juVHPvmmAXYfNjPZZg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: AR Nadalin, BS Souza, JM Pankratz, TB de Almeida… - Research in Veterinary …, 2026
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Background Electroencephalography ( EEG ) has been extensively used to … Objective This systematic review aimed to evaluate the use of EEG as a biomarker of brain … and free-text terms related to electroencephalography and ruminant species

---

### [130] LightSleepX: A Lightweight, Inception-Based Dual-Modal Network for Sleep Staging

**链接**: https://arxiv.org/abs/2609.19062
**作者**: Yi Wang
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automatic sleep staging is fundamental to personal health monitoring, yet many existing approaches are ill-suited for real-world applications. Traditional pipelines often rely on hand-crafted features or shallow machine learning models that struggle to generalize, while state-of-the-art deep learning methods, though accurate, are computationally heavy and impractical for resource-constrained environments. This paper introduces LightSleepX, a lightweight framework designed to deliver robust sleep analysis in resource-constrained environments. LightSleepX combines an Inception-style architecture with depthwise separable convolutions and Multi-scale Enhanced Attention for efficient multi-modal EEG/EOG feature extraction, and a Mamba encoder for rule-free long-range temporal modeling. On public benchmark datasets, LightSleepX achieves 85.9% accuracy and a 0.803 macro-F1 score on Sleep-EDF-20, and 81.8% accuracy and a 0.796 macro-F1 score on the cross-subject ISRUC-S3 dataset. With 0.049M p

---

### [131] SARATR-X-v2: Scale-Aware Structural Pre-Training for SAR Foundation Models

**链接**: https://arxiv.org/abs/2607.23238
**作者**: Weijie Li, Yafei Song, Yongxiang Liu, Bowen Peng, Jie Zhou, Jingyuan Xia 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [132] Post-Training in Time Series Foundation Models: A Unifying Framework

**链接**: https://arxiv.org/abs/2607.20002
**作者**: Shifeng Xie, Ambroise Odonnat, Zehao Xiao, Lei Zan, Malik Tiomoko, Lujia Pan 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [133] HoliBench: A Cross-Platform Benchmarking and Deployment Toolkit for Foundation Models in CPS-IoT Applications

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2609.12412&hl=zh-CN&sa=X&d=954217180312108194&ei=YNmraobGB_Ov6rQP_NLbyQ8&scisig=AIVdB-ygN6y8l7cUT66Mu-4j7C9e&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=2&folt=kw-top
**作者**: I Chakrabarti, Z Xiong, P Sharma, M Srivastava - arXiv preprint arXiv:2609.12412, 2026
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> from isolated foundation- model executions predict the behavior of larger multi - model deployments, or must every … language model processing camera frames for scene understanding may feed its output to a language model responsible for high-level

---

### [134] Benchmarking Tabular Foundation Models as Surrogates in Expensive Evolutionary Optimization

**链接**: https://arxiv.org/abs/2609.18130
**作者**: Lu Han, Jin Wang, Yuchen Li, Haoran Gu, Shulei Liu, Ziyang Shi 等 (7 人)
**来源**: cs.NE cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Surrogate-assisted evolutionary algorithms (SAEAs) are effective methods for solving expensive optimization problems (EOPs), where surrogate models replace most expensive evaluations and critically influence the final optimization results. In recent years, tabular foundation models have advanced rapidly, and the Tabular Prior-data Fitted Network (TabPFN) has been adopted as a surrogate model for EOPs due to its strong predictive capability, demonstrating promising performance. Motivated by its potential as a surrogate model in SAEAs, this work conducts a comprehensive study that combines extensive experiments with in-depth theoretical analysis to investigate the effectiveness of TabPFN. Specifically, we perform experiments across both offline and online SAEA settings, covering diverse problem scenarios such as single-objective, multi-objective, constrained, combinatorial, mixed-variable, and engineering optimization problems. In addition, we further analyze the advantages and limitatio

---

### [135] Structure is not mechanism: high-gain gated-FFN rows across text and genomic foundation models

**链接**: https://arxiv.org/abs/2609.17599
**作者**: Alexandros Tzanakakis, Aris Karatzikos, Ilias Georgakopoulos-Soares
**来源**: q-bio.GN cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A small number of unusually high-gain parameters can exert disproportionate effects in transformer language models, but whether analogous structures recur in genomic foundation models and whether structural geometry determines functional importance remains unknown. We analyzed high-gain rows in gated feed-forward networks across text and genomic foundation models, including a frozen 22-model causal census. Computing an associated bilinear weight operator exactly, without a diagonal approximation, we tested whether structural extremeness is a transferable mechanism. Activation-derived candidates were functionally enriched relative to random and top-norm same-layer controls, yet neither spectral concentration nor operator magnitude predicted causal effect size, and these associations vanished within the endpoint-homogeneous text-decoder subset. A within-layer sweep of 36 rows in one genomic and one text decoder resolved this into two regimes: below the detector's acceptance threshold the

---

### [136] iMINDBench: iEEG Multi-Institution Neural Decoding Benchmark

**链接**: https://arxiv.org/abs/2609.18104
**作者**: Geeling Chau, Saba Hashemi, Yonghyeon Gwon, Eshani Patel, Jan DeWitt, Christopher Wang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Intracranial electroencephalography (iEEG) is widely used to record electrical activity directly from electrodes inside the human brain, making it an attractive modality for neural decoding. However, progress in iEEG decoding, especially toward general-purpose foundation models, remains difficult to measure reliably: datasets are task- or institution-specific, limiting evidence of generalization across tasks and recording environments, and preprocessing choices can strongly influence performance, making model improvements difficult to distinguish from preprocessing gains. Thus, we introduce iMINDBench, an iEEG Multi-Institution Neural Decoding Benchmark that evaluates models on a shared suite of fifteen decoding tasks across three naturalistic movie-watching datasets. The benchmark additionally defines standardized preprocessing tracks and fixed evaluation splits to support consistent model comparisons. Using iMINDBench, we find that the evaluated pretrained systems generally outperfor

---

### [137] GeoCond: A Conditioning-Aware Reliability Adapter for Feed-Forward 3D Reconstruction

**链接**: https://arxiv.org/abs/2609.18465
**作者**: David Ahmedt-Aristizabal, Mohammad Ali Armin, Russell Tsuchida, Lars Petersson
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feed-forward 3D foundation models such as VGGT predict cameras, depth, and point maps in a single pass, but can fail silently under low overlap, low parallax, and extreme relative rotation. Stratified analyses over these factors show that these failures are governed by geometric conditioning and are poorly captured by native aleatoric confidence. We introduce GeoCond, a lightweight reliability adapter for frozen feed-forward 3D backbones. GeoCond reads the backbone's predicted geometry and outputs pose-level uncertainty and a refinement gate. During training, it can be supervised by frame-permutation orbit variance, ground-truth pose error when labels are available, or cycle residuals from unlabelled independent pose graphs. At inference, the default head requires only one backbone pass and a small MLP. On VGGT, GeoCond improves out-of-distribution (OOD) AUSE (area under the sparsification-error curve; lower is better) from $0.32$ to $0.20$ over native confidence, transfers zero-shot t

---

### [138] Lumen: Parameter-Efficient Alignment of Pretrained Vision and Language Encoders for Zero-Shot Computational Pathology

**链接**: https://arxiv.org/abs/2609.17868
**作者**: Kiarash Tajbakhsh, Abdelrahman Faqieh, Michael Jopiti, Javier Garcia-Baroja, Philipp Zens, Branislav Zagrapan 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology vision-language models are commonly built by pretraining or fine-tuning large encoders on paired image-caption data. We asked whether a pathology vision-language model can instead be assembled by parameter-efficient alignment of frozen unimodal foundation models, leaving their pretrained representations untouched. Here we present Lumen, which aligns frozen Virchow2 and BioMedBERT backbones using rank-4 adapters and projection heads, training only 0.40% of the total parameters on the public QUILT-1M corpus. Across nine public zero-shot patch benchmarks, Lumen achieved the highest mean chance-corrected balanced accuracy, 0.546 versus 0.461 for the strongest baseline (paired difference 0.086, 95% CI 0.042-0.136). On lymph-node metastasis detection, Lumen reached an AUROC of 0.964 (95% CI 0.956-0.971) on 4,214 held-out internal slides and 0.955 (95% CI 0.942-0.966) on 2,368 slides across nine external cohorts and six organs. At the internally calibrated threshold, it outperformed

---

### [139] T-SANDHI: Tone Sandhi-aware Adaptive Network with Decoupled Hybrid Injection for Low-resource Taiwanese Hokkien Speech Recognition

**链接**: https://arxiv.org/abs/2609.18194
**作者**: Hung-Yang Sung, Chien-Chun Wang, Tien-Hong Lo, Yu-Sheng Tsao, Yung-Chang Hsu, Berlin Chen
**来源**: cs.CL
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In Taiwanese Hokkien automatic speech recognition (ASR), prior studies often treat tone sandhi as a major challenge under the assumption that models fail to process implicit phonological variations. However, our experiments on Taiwanese Hokkien reveal that speech foundation models actually handle tone sandhi variations effectively, and the real performance bottleneck stems from a localized confusion between these variations and retained citation tones. To address this, we propose T-SANDHI to explicitly decouple surface acoustics from underlying lexical intent on top of a frozen Whisper backbone. Using a lexicon-guided multi-task learning structure driven by text-derived pseudo labels, our lightweight hybrid injection module integrates independent citation and sandhi phonetic streams via dynamic gating. Extensive evaluation on the TAT-MOE corpus and two blind test sets demonstrates that this explicit disentanglement effectively resolves tonal mapping confusion, outperforming baselines w

---

### [140] Learning Where to Focus: Self-Supervised Multi-Scale ViTs for Histopathology

**链接**: https://arxiv.org/abs/2609.18578
**作者**: Anabel Stammer, Valay Bundele, Mehran Hosseinzadeh, Hendrik P.A. Lensch
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathologists diagnose diseases by first locating suspicious tissue and then examining it at higher magnification, whereas self-supervised vision transformers (ViTs) allocate the same spatial resolution to every image region despite diagnostic evidence being sparse and spanning multiple biological scales. Recent pathology foundation models have substantially improved representation quality by scaling training data and model capacity, but largely retain uniform tokenization. We instead investigate whether pathology representations can be improved by learning where to allocate spatial resolution during self-supervised learning. To this end, we propose CRAFT (Coarse-to-fine Region-Adaptive Feature Tokenization), a DINO-based framework that learns image-dependent mixed-scale representations by using self-supervised attention to selectively refine informative regions while preserving coarse context, together with a symmetric cross-scale regularization objective that encourages complementary 

---

### [141] A Comprehensive Review of Generative Physical Artificial Intelligence

**链接**: https://arxiv.org/abs/2609.18111
**作者**: Satyam Gaba, Krutiksinh Rana, Siva Sai, Vinay Chamola, Dusit Niyato
**来源**: cs.RO cs.AI cs.CL cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of large-scale foundation models with physical embodiments has led to significant advancements in robotics known as Generative Physical Artificial Intelligence (GPAI). These agentic AI systems autonomously perceive, reason, and act in complex real-world situations. This survey comprehensively analyzes GPAI systems, focusing on their architectural foundations, current applications, and key limitations. We introduce a taxonomy of five distinct approaches: Robot Foundation Models (RFMs) for cross-platform skill transfer; Vision-Language Action (VLA) models for end-to-end multi-modal perception and control; Large Behavior Models (LBMs) for human-like movement generation; Diffusion Policy Models (DPMs) for diffusion model-based temporally coherent action generation; and World Foundation Models (WFMs) for physics-compliant simulation and data generation. We examine how these approaches complement each other: WFMs generate training data for VLAs and DPMs, RFMs enable cross-pla

---

### [142] Similarity Pairing with Energy Mover's Distance for Self-Supervised Pre-Training at the LHC

**链接**: https://arxiv.org/abs/2609.17738
**作者**: Ho Fung Tsoi, Dylan Rankin
**来源**: hep-ex cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many self-supervised methods for training foundation models at the Large Hadron Collider (LHC) rely on data augmentations to encourage the model to embed events into a representation space invariant to certain physical or detector symmetries. A common challenge arises from the large freedom in choosing a proper set of augmentations on which downstream performance depends. The implementation of augmentations involves either modifying existing events, potentially breaking the event fidelity, or simulating more event variants, which is computationally intensive. In this work, we present a data-driven method of pairing events by their similarity via the energy mover's distance (EMD), which measures how similar two events are in terms of the work required to transform one into the other. With this approach, distinct events are sampled and matched by their similarity to serve as views for learning invariance, keeping the physics content of each event intact without handcrafted distortions. W

---

### [143] Peak-Aware Short-Term Load Forecasting Across Distribution Grid Aggregation Levels

**链接**: https://arxiv.org/abs/2609.18588
**作者**: Souhardya Chattopadhyay, Julian Oelhaf, Antonia Schoening, Jessica Deuschel, Bitan Bhattacharyya, Christian Bergler 等 (8 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For distribution system operators, short-term load forecasting (STLF) supports congestion management, voltage control, and asset protection. Most existing approaches focus on overall accuracy across all time steps and neglect performance during high-demand (HD) periods, where larger forecast errors can increase the risk of congestion and voltage violations. In this paper, we study peak-aware STLF across three operator-relevant distribution grid aggregation levels, area codes (AC), secondary substations (SUB), and low-voltage (LV) feeders, using open datasets from the United Kingdom and Switzerland. We compare statistical baselines, machine learning models (LightGBM and XGBoost), and recent time-series foundation models (Chronos Bolt and Chronos-2) under a peak-aware evaluation framework that reports both overall and HD forecasting performance using NMAE and MAPE. The results show that Chronos-2 achieves the best HD performance across all aggregation levels, with HD-NMAE and HD-MAPE of 

---
