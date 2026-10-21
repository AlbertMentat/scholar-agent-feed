# 📑 论文索引 - 2026-10-22

共 189 篇论文

---

### [1] PI-MLLM: Psychophysics-Inspired Multimodal Large Language Model for Oddly Satisfying Video Emotion Analysis

**链接**: https://arxiv.org/abs/2610.28264
**作者**: Yuheng Zhang, Jie Zhang, Yuecong Min, Yunwei Zhao, Meichen Liu, Qiankun Li 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 11.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Oddly Satisfying Videos (OSVs) can evoke strong viewer responses through repetitive motion, visual tactility, and ASMR-like sounds despite containing few explicit semantic emotion cues. This makes OSVs a challenging setting for Video Emotion Analysis (VEA), since most existing methods focus on semantic video content and under-model the physical sensory dynamics that shape viewer responses. To support Oddly Satisfying Video Emotion Analysis (OSVEA), we construct the Oddly Satisfying Video Dataset (OSVD), comprising 12,000 annotated 5-second clips. Each clip provides viewer-emotion labels under video-only, audio-only, and audio-visual conditions, together with explanations grounded in visual and acoustic sensory evidence. Building on OSVD, we propose PI-MLLM, a psychophysics-inspired multimodal large language model that integrates Modality-Specific Dynamics Alignment (MSDA) and Coalition-Based Audio-Visual Attribution (CAVA). MSDA uses auxiliary prediction objectives to align modality re

---

### [2] MobileInject: Evaluating Reasoning-to-Action Security of MLLM -Based Mobile Agents under Cross-Modal Consistency Injection

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.23307&hl=zh-CN&sa=X&d=2762101555294049658&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVHsCsRBRq7oLh8Tabq1ZuBf&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=0&folt=kw-top
**作者**: S Wang, P Li, Y Huang, F Li, X Ran, Y Lyu 等 (8 人)
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> Multimodal large language model ( MLLM )-based mobile agents are rapidly evolving from conversational assistants into autonomous systems that perceive, reason over, and act on smartphone environments. This capability also exposes a new security

---

### [3] The More the Better? A Comparison of Single- and Multi-Agent LLM Setups on a Financial Review Task

**链接**: https://arxiv.org/abs/2610.27488
**作者**: Pei Liu
**来源**: cs.AI cs.CE
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practitioner guidance holds that a large language model reviews a document better when the work is divided among agents. We test a narrow form of it in a controlled comparison of single-agent and multi-agent setups on a financial task, reviewing credit assessment memos against requirements. One agent checks six requirements in one call. A team of three on the same model checks the same memo, two requirements each, in the same words, with no roles or later stage. Labels are known for every requirement on 300 synthetic memos, so misses and false alarms are measured separately. Two primary predictions are tested on four models at a Bonferroni-corrected level. Under an instruction to decide each requirement once, the team catches 0.08 to 0.10 more of the defects that carry an explanation on the three models whose single agent misses some, at the corrected level on two. It raises more false alarms on all four, at the corrected level on three. Balanced accuracy, an exploratory measure, chang

---

### [4] Understanding KV Residency in Production-Scale Agentic LLM Workloads

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22863&hl=zh-CN&sa=X&d=1330655962828618636&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVFknO1kklAz67pmYyYgVqc5&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=6&folt=kw-top
**作者**: M Arya, A Bari, A Parayil, Y Simmhan, RS Amant… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Agentic large language model ( LLM ) applications turn one user request into a sequence of model and tool calls over a growing context. Retaining this context's key-value (KV) state in GPU memory lets later calls reuse it instead of recomputing it, but at

---

### [5] An LLM-Based Agent for Legal Compliance Assessment: Architecture, Memory, and Evaluation in a Canadian and Quebec Context

**链接**: https://arxiv.org/abs/2610.27347
**作者**: Soukaina Alaoui Ismaili, Jean-Sebastien Dessureault
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Checking whether a text complies with a body of law is slow when done by hand and fragile when done with keyword rules. This paper presents ComplianceAgent, the legal compliance sub-agent of COMPASS, a multi-agent framework that evaluates texts along four axes: digital sovereignty, carbon impact, compliance, and ethics. The agent relies on a large language model that scores a text on a fixed rubric, grounds its judgment in a reference legal corpus, and, when the score falls at or below a critical threshold, runs a corrective chain made of self-healing rewrites, a compliance label, an explainability report, and escalation to a human reviewer. We describe what the language model does at each step, how the memory of the agent is organized, and how the same implementation can be pointed at different reference corpora. We evaluate the agent in a Canadian and Quebec context, on a corpus of thirteen legal instruments that brings together federal and provincial texts, international treaties, a

---

### [6] Disclosure Begets Disclosure: A Self-Reinforcing Privacy Loop in LLM Agents with Persistent Memory

**链接**: https://arxiv.org/abs/2610.28315
**作者**: Masahiro Kaneko, Hiromi Arai, Timothy Baldwin
**来源**: cs.CR cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly use persistent memory to personalize responses, and personal attributes in this memory pose a privacy risk if exposed. We ask how consulting memory during dialogue changes what users go on to say, and thus what the memory comes to reveal. In multi-session simulations, a simulated user with 24 personal attributes talks with a support agent that does or does not consult memory, and in both settings attributes are inferred from the full accumulated record. Across four support models, memory raises response quality but also empirical leakage, the share of attribute values correctly inferred from the record, by a margin that widens over sessions. The cause is a loop in ordinary, non-adversarial assistance. Memory-conditioned responses carry earlier values forward, often as presuppositions, and users affirm them or leave them uncorrected, so that cues and the agent's own guesses become recorded values. The loop reinforces itself, and removing th

---

### [7] M-Plan: Comprehensive Planning For LLM Agents with Memory Arrangement

**链接**: https://arxiv.org/abs/2610.27032
**作者**: Ziyang Liu, Jiakang Yuan, Jiayuan Fan, Tao Chen
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based agents have recently demonstrated outstanding performance in single-turn tasks, yet they continue to struggle with long-horizon tasks, particularly in environments without prior training. A key limitation of single LLMs is their difficulty in processing long contexts, which stems from weaknesses in continuous decision-making and reasoning capabilities. Although existing multi-agent systems (MAS) equipped with long-term memory bases can partially address this gap, they mostly rely on knowledge reuse or summarization, an approach that is often constrained by directly retrieval without any adaptation for the current task, while the retrieved memory may contain much history noises waiting to be preprocessed. In contrast, MAS characterized by task-specific guidance often lack long-term memory specifically designed for the guidance. To address these challenges, we propose M-Plan, a closed-loop MAS framework that integrates long-term and short-term memory. By 

---

### [8] Dynamic System Inspired Continuous Large Language Model for AI4Science Tasks

**链接**: https://arxiv.org/abs/2610.26959
**作者**: Zhaoxin Fan, Zheng Zhu, Yuqing Ma, Faguo Wu, Jian Yang, Wenjun Wu
**来源**: cs.LG cs.CL
**匹配关键词**: Foundation Models, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific foundation models increasingly operate on continuous phenomena, yet still use discrete residual computation. We ask whether pretrained residual transformations can support additional latent computation without expanding the backbone. To test this possibility, we introduce Continuum-LM, which reuses these transformations as dynamical operators in a continuous-depth language model. Its hidden states evolve through an ordinary differential equation evaluated by higher-order numerical integration, with solver order and step size controlling computation. Across eight scientific tasks, Continuum-LM trains stably and improves mean exact-match accuracy by 7.77 and 10.96 percentage points over discrete counterparts at the 0.6B and 1.7B scales, respectively. At 0.6B, it also outperforms an Ouro-style recurrent control under matched parameter and residual-function evaluation budgets. Together, these results support extensible computational depth through parameter reuse, identifying con

---

### [9] Learned Readout Tokens for Extracting Large Language Model Confidence

**链接**: https://arxiv.org/abs/2610.27566
**作者**: Nima Seifi, Martin Ester
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used within everyday applications where their responses have significant downstream impacts. For responsible deployment of such systems, we desire insight into how much we can trust their individual outputs. A popular approach for estimating LLM confidence is to train probes on the hidden states of the LLM's tokens to predict the correctness of the model's output. These probes typically read hidden states from tokens that are already in the model's vocabulary. In this work, we introduce a new approach to confidence probes that learn a new readout token and utilize its hidden states to train the probe. We show that our learned readout approach ScratchProbe outperforms its existing-token counterpart on a variety of datasets and LLMs. We also extend our method to a multi-token approach which we show provides further performance improvements. Finally, since the learned readout changes only the position a probe reads from, any existing probe can

---

### [10] Pattern Intelligence: Unsupervised, LLM-Interpreted Discovery of Systematic Underpayment and Denial Patterns in Healthcare Revenue Cycle Management

**链接**: https://arxiv.org/abs/2610.27684
**作者**: Harshil Lodhiya, Alex McManus
**来源**: cs.AI stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Healthcare providers lose substantial revenue to systematic payer underpayments and claim denials, yet identifying the recurring, correctable patterns behind them remains largely manual and does not scale to hospital claim volumes. We present Pattern Intelligence, a deployed system that discovers such patterns without supervision by clustering claims on their adjudication behaviour rather than their identity. Each claim is embedded in a 130-dimensional vector combining per-line expected-versus-actual payment ratios, claim adjustment reason (CARC) codes, denial and payment signals, and service composition. Payer and contract identity are deliberately excluded from the distance metric - we show they dominate the geometry and collapse clusters into trivial per-payer groups - and are reintroduced only as a post-hoc segmentation (by contract and visit type) that keeps every surfaced pattern coherent and actionable. We cluster with HDBSCAN, recover structure from the noise set via second-pas

---

### [11] Difference-in-Differences on a Censored Rating Scale Can Manufacture an Effect: Evidence from a Pre-Registered LLM-Judge Audit

**链接**: https://arxiv.org/abs/2608.27309
**作者**: Shuyi Fan, Boyuan Deng, Mengyu Xu, Xinhong Xie, Chenyang Li, Hongyang Zhang
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] ClockMark: Adaptive and Host-Dependent Watermarking for Large Language Models

**链接**: https://arxiv.org/abs/2610.27079
**作者**: Yupeng Qiu, Han Fang, Ee-Chien Chang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) watermarking operates on the next-token distribution that evolves during generation. In streaming generation, each sampled token becomes part of the text and affects subsequent distributions. Embedding therefore proceeds with a changing host, unlike classical watermarking, which adapts embedding to an existing host signal. To accommodate this difference, we formulate a novel embedding framework for LLM watermarking based on two principles. We first argue that embedding should be adaptive, retaining the state of previous sampling decisions to better guide subsequent choices. We further argue that embedding should be host-dependent, using the current LLM distribution to constrain both token selection and state updates. Guided by these principles and the two requirements of distribution preservation and robustness to text editing, we propose ClockMark. It combines adaptive and host-dependent embedding with message spreading, embedding the full payload in each wa

---

### [13] SliMOO: Interpretable Multi-Objective Evolutionary Search for LLM Depth Pruning

**链接**: https://arxiv.org/abs/2610.27812
**作者**: Guanchen Li, Yixing Xu, Xuanwu Yin, Dong Li, Emad Barsoum
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As large language models (LLMs) grow more powerful, their scale makes them costly to serve. Depth pruning offers a practical route to efficiency by directly reducing memory and latency without hardware-specific support. However, we observe that transformer layers exhibit markedly different task-dependent layer contributions, whereas existing depth-pruning methods ignore this heterogeneity and thus tend to optimize for a narrow domain or benchmark rather than preserve broad capability. This suggests that LLM depth pruning should be formulated as a multi-objective optimization problem rather than a single-score ranking problem. We propose SliMOO, an interpretable multi-objective evolutionary search framework for LLM depth pruning. SliMOO first uses single-layer removal probing to construct a task-layer importance map, which provides an interpretable view of task-shared and task-specific layers and serves as a search prior. It then performs a Pareto-aware evolutionary search for pruning m

---

### [14] ProMemAgent: Long-Horizon Proactive Assistance with Context-Aware Prospective Memory from Sensory Perceptions

**链接**: https://arxiv.org/abs/2610.27400
**作者**: Lilin Xu, Linyang He, Kaiyuan Hou, Yuang Fan, Minghui Zhao, Xuhai Xu 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are moving beyond reactive responses toward proactive assistance that anticipates user needs without explicit requests. However, existing proactive agents primarily address immediate needs, while many everyday situations involve delayed intentions that can only be acted on hours or days later. Humans handle such intentions through prospective memory, the ability to remember to act on an intention when the right moment arises. In this paper, we introduce ProMemAgent, the first proactive agent to incorporate prospective memory over everyday sensory contexts for long-horizon proactive assistance. ProMemAgent organizes past sensory perceptions (e.g., egocentric video and audio) into context-aware memory, generating prospective cues and linking earlier events with subsequent developments for future retrieval. Given the current context, it retrieves relevant past events and performs memory-augmented proactive reasoning to determine whether assistance is need

---

### [15] ICLHerd: Herding-Based Data Selection for LLMs with In-Context Learning as a Proxy

**链接**: https://arxiv.org/abs/2610.27142
**作者**: Yuqiao Wen, Lili Mou
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data selection plays a central role in modern large language model training, as the quality of training data strongly influences downstream performance. A common approach is to curate a development set that encodes the desired skills (e.g., reasoning or multilinguality) and select data that are similar to them. Existing methods compute similarity using cosine distance over either the model's hidden states or gradients. However, we observe that this max-similarity strategy induces a mode-seeking bias: the selected data clusters tightly around the development samples. To address this, we propose ICLHerd, a data selection framework that leverages the von Mises-Fisher kernel to balance mode-seeking with mode-averaging. We further introduce in-context learning as a validation proxy, enabling efficient hyperparameter search over the balance trade-off. Results show that ICLHerd outperforms existing LLM data selection algorithms, highlighting the importance of balancing mode-seeking and mode-a

---

### [16] From Relevant Memories to Sufficient Evidence: Rethinking Memory Utilization in LLM Agents

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22668&hl=zh-CN&sa=X&d=4483026880739027895&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVGjiQRKHFnLKmQRnwY7tkFu&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=3&folt=kw-top
**作者**: S Li, W Yang, P Zhang, A Cheng, H Ping, X Zhang… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Long-term memory enables LLM agents to reuse past experiences, yet retrieving relevant memories does not necessarily provide sufficient evidence for answering a query. Essential information may remain fragmented across memory records

---

### [17] VRPAgent: LLM-Driven Discovery of Heuristic Operators for Vehicle Routing Problems

**链接**: https://arxiv.org/abs/2510.07073
**作者**: Andr\'e Hottung, Federico Berto, Chuanbo Hua, Nayeli Gast Zepeda, Daniel Wetzel, Michael R\"omer 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] Response-Informed Value Estimation for Cost-Aware Multi-Turn LLM Routing

**链接**: https://arxiv.org/abs/2610.23239
**作者**: Haotian Yan, Jiaqi Liu, Bingyi Jing, and Tianjun Yao
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [19] ClawMMU: Protection-Coherent Virtual Memory for Stateful LLM Agents

**链接**: https://arxiv.org/abs/2610.28093
**作者**: Jinhao Hu, Bardia Mohammadi, Mofasshara Binte Rafique, Lars Henning Klein, Akhil Arora, Ashvin Goel 等 (7 人)
**来源**: cs.CR cs.AI cs.OS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents keep long-term memory, much of which comes from web pages and tool results. Agent harnesses, the software that runs the model, do not record who may act on this memory, so an instruction hidden in a fetched page can be treated as the user's own instruction. We propose ClawMMU, a protection layer that labels every piece of memory with its owner, scope, origins, and authority. ClawMMU checks these labels whenever content enters the model's context, is written to storage, returns from storage, or drives a tool call. Its central rule is that information may rise in authority, but authority never lifts itself. Because the checks depend on where content came from, not on what it says, memory attacks become classical protection faults that the harness stops even when the model is fooled.

---

### [20] VISH-ASR: Viterbi-Guided Selection of Hotwords for Speech-LLM Contextual ASR

**链接**: https://arxiv.org/abs/2610.27867
**作者**: Xiaoyu Gu, Yu Xi, Chencheng Wang, Zonghan Zhou, Haoyu Li, Jing Peng 等 (7 人)
**来源**: eess.AS cs.AI cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prompt-based contextual ASR requires selecting a compact hotword subset from large dynamic inventories, yet existing pre-selection methods rely either on discrete ASR hypotheses that may discard acoustic evidence or on separately trained retrieval models. We propose Viterbi-guided Selection of Hotwords (VISH), a training-free, plug-and-play framework that directly verifies candidate-specific acoustic support over frame-level CTC posteriors. VISH formulates pre-selection as constrained posterior search; M-VISH makes large-list verification scalable through frame-synchronous shared-prefix Viterbi search with bounded top-K pruning, while Bi-MVISH exploits complementary backward evidence for robust verification. Across five benchmarks, M-VISH achieves up to 11.7% absolute improvement in Best-F1 over a strong learned-retrieval baseline and reduces candidate-search latency by 75.2% at 2,000 candidates relative to hypothesis-based filtering. These results demonstrate the effectiveness of post

---

### [21] Foreword: Pre-Generation Prediction and Characterisation of LLM Test Failures using the Jacobian Lens

**链接**: https://arxiv.org/abs/2610.28187
**作者**: Somin Kim and Robert Feldt and Shin Yoo
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Testing LLM-based software is expensive: each input needs several sampled responses, each judged by a costly oracle. Further, every prompt or model change calls for re-testing. Pre-generation adequacy measures cut this cost by ranking inputs by failure risk based on the model's internal state. However, the state of the art, Clotho, models only passing reference inputs, and its hidden-state representation says nothing about why inputs fail. We present Foreword, a framework built on two ideas: learn from both passing and failing references, and represent inputs through the Jacobian lens (J-lens), an interpretability technique that reads intermediate activations out as scores over vocabulary tokens. Foreword pairs these representations with two estimators: a sparse logistic-regression probe or dual Gaussian Mixture Models (dual GMMs), which also yield a reference density (to flag inputs the references do not cover) and failing-class components (to group similar failures). On ten tasks and

---

### [22] Many Steps into One: Reasoning Contraction and the Limits of Safe Memory Reuse for LLM Agents

**链接**: https://arxiv.org/abs/2610.17544
**作者**: Jianghong Zhou, Hao Rong, Chen Lin, Daoan Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] Reading Too Much Into It? Interpretive Preferences and Commitment in LLM Mentalisation under Ambiguity

**链接**: https://arxiv.org/abs/2610.28105
**作者**: Stephanie Fong, Yiwen Jiang, Qingyang Xu, Zimu Wang, Yaling Shen, Xiangyu Zhao 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used for interpersonal advice, potentially shaping how users interpret ambiguous social encounters. Existing Theory of Mind evaluations typically rely on predefined answers, while uncertainty research overlooks LLMs' preferred explanations and confidence under psychological distress. To address these gaps, we introduce MentalLoom, a novel evaluation of LLM mentalisation comprising 604 ambiguous social episodes, matched depression and social anxiety disclosures, and four-turn dialogues with unchanged event evidence. Across eight LLMs, disclosures initially elicited more negative explanations overall but more positive narrator-directed interpretations. Scripted repeated questioning showed greater emotional support, stronger positive narrator-directed endorsement, and higher certainty without new event evidence. These findings show that user context can reshape interpretive preferences and commitment while the underlying ambiguity remains unre

---

### [24] Cross-Lingual Reusability of LLM Pipelines: Financial Extraction, Multilingual Reasoning, and Semantic Screening

**链接**: https://arxiv.org/abs/2610.27043
**作者**: Joong Ho (Joshua) Choi, Sherine George, Jiayang Zhao, Jayesh Rathi, Ashwin Kandath, Ananya Sane 等 (7 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial institutions increasingly deploy large language models (LLMs) in multilingual markets, raising a practical question: can pipelines developed and validated in English be reused across languages, or must they be rebuilt per locale? We test cross-lingual reusability along three dimensions--accuracy, reasoning-effort transfer, and behavioural stability--through three complementary tasks. Task 1 (cheque extraction) and Task 2 (Mintaka QA with pinned evidence across nine languages and nine model-effort configurations) test whether accuracy and effort settings transfer; Task 3 (FinanceBench pilot, 50 items over SEC 10-K filings in four languages) validates whether these patterns generalise to financial content. Accuracy reusability is broadly confirmed: Gemini 3.5 Flash achieves 95.2-97.6% extraction accuracy across prompt languages, and FinanceBench per-language means span 5.8pp (77.1-82.9%), though the language-difficulty ranking reverses between domains (Hindi is worst on Mintaka

---

### [25] From Outcomes to Components: A Counterfactual Evaluation Framework for LLM-Proposed Repairs

**链接**: https://arxiv.org/abs/2610.26650
**作者**: Hengyu Ye, Songhua Hu
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Ethical LLM-Assisted Research: A Framework for Responsible Delegation, Verification, and Epistemic Value

**链接**: https://arxiv.org/abs/2608.23644
**作者**: Kalin Stoyanov, Nina Ilieva
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] Robust LLM Watermarking with Minimal Semantic Distortion for IP Protection

**链接**: https://arxiv.org/abs/2605.23175
**作者**: Kieu Dang, Phung Lai, NhatHai Phan, Yelong Shen, Ruoming Jin
**来源**: cs.CR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] LLM-Guided Evolution of Symbolic Acceleration Inequality Families for MILP

**链接**: https://arxiv.org/abs/2508.11850
**作者**: Milad Yazdani, Mahdi Mostajabdaveh, Samin Aref, Zirui Zhou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] The Token-Energy Law of LLM Decode: Active Bytes and Realized Time Account for Joules per Token

**链接**: https://arxiv.org/abs/2610.28576
**作者**: Chenxu Niu, Batuhan Sencer, Wei Zhang, Yong Chen
**来源**: cs.LG cs.DC cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Energy-efficient deployment of large language models requires understanding how model architecture, hardware, and serving settings shape energy per generated token. We introduce the Token-Energy Law, a compact, interpretable model of GPU-board energy per output token for dense, full-history decoding. It relates token energy to two core dimensions: active bytes and realized decode time. Active bytes describe logical byte demand per output, separating dense weights shared within a decode iteration from private key--value (KV) histories read and updated for each request. Realized decode time is the elapsed decode duration divided by the number of output tokens produced. We combine the two byte coordinates and time in a common affine form, with coefficients calibrated for each model and hardware/runtime configuration. This formulation explains how batching amortizes shared-weight work, longer attended histories increase private KV demand, and throughput determines the time-associated cost 

---

### [30] Pair Difficulty Matters: Rethinking Pairwise LLM-as-a-Judge Evaluation and Consistency

**链接**: https://arxiv.org/abs/2609.37577
**作者**: Bruno Brocai and Maria Becker
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] On the LLM Verification for Argument Graph Generation

**链接**: https://arxiv.org/abs/2610.27361
**作者**: Jakub B\k{a}ba and Jaros{\l}aw A. Chudziak
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems can formalize natural-language argumentation end-to-end, turning plain text into structured graphs by classifying components, connecting them with relations, and enriching the resulting graphs into formal models. Quality assurance for those graphs is almost always another LLMs: a reviewer, judge, or critic agent. On the other side, in adjacent neuro-symbolic fields, such generated output is often verified symbolically by external checks and solvers. In this work, we argue that in argument graph verification, the allocation should be similar, and based on what each instrument can guarantee. We propose layered verification: starting from deterministic checks, moving to solver-based and LLM reviews, and utilizing debate only under uncertainty, leaving human judgment for what no other instrument can decide. We ground our principle with a study on human-annotated graphs with injected structural defects. An LLM reviewer detects them at near-ceiling recall, including c

---

### [32] CHIMERA: Compact Synthetic Data for Generalizable LLM Reasoning

**链接**: https://arxiv.org/abs/2603.00889
**作者**: Xinyu Zhu, Yihao Feng, Yanchao Sun, Xianzhi Du, Pingzhi Li, Olli Saarikivi 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Risk and Refusal: Mechanisms of LLM Responses to Suicidal Ideation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22715&hl=zh-CN&sa=X&d=16706795068065865201&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVEjuJPXK-3SqpZCuk0rHBOn&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=5&folt=kw-top
**作者**: D Goel, SR Shimgekar, J Lee, VJ Rodriguez, DS Brown… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> influence LLM refusal behavior and response-level risks in SI disclosures? RQ2: How are refusal-related mechanisms implicated in LLM … • We investigate LLM engagement with SI disclosures, a consequential class of interactions in which

---

### [34] Diagnostic Analysis for Large Language Model Reasoning

**链接**: https://arxiv.org/abs/2610.27245
**作者**: Xinyu Liu, Dongqi Fu, Jun Wu
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning structures (e.g., chains and graphs) are increasingly used for probabilistic inference, factuality verification, and uncertainty estimation, but their structural reliability is rarely evaluated directly. We test whether this reliability holds through a proposed two-stage diagnostic evaluation in open-ended multi-hop QA. Stage 1 tests different capabilities required to construct reasoning graphs, showing that graph reliability varies with topology, prompt design, and model family. Stage 2 uses uncertainty estimation as a downstream test case. Generated-edge experiments show that graph-based computation is sensitive to upstream graph errors, with performance dropping relative to the gold-graph setting. Gold-graph experiments further show that graph structure provides little benefit when used only as prompt context, but improves the separation of correct from incorrect answers by confidence score and enables node-level diagnostics.

---

### [35] Detecting Errors in Large Language Model Responses: The Incremental Predictive Value of Hidden States

**链接**: https://arxiv.org/abs/2610.27455
**作者**: Ningzhi Li, Xiaojun Ma, Xiaofei Wang
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although large language models support a wide range of tasks, hallucinations remain a major obstacle to user trust. When a model generates an answer, both its internal processing and final output vary with the question. Internal states are often expected to offer richer signals for hallucination detection. However, studies using these states typically report their standalone discrimination performance, while output-side comparisons often use simple baselines with weaker modeling capacity. We integrate output-side information available at inference time into a combined baseline and compare detection performance before and after adding hidden states under identical data splits and evaluation rules. Experiments cover open-ended generation and constrained multiple-choice tasks across different models. Adding hidden states improves AUROC by approximately 0.004 and 0.039 on the two tasks, respectively. Hidden states thus provide additional predictive information, but strong standalone detect

---

### [36] The Show-Up Attack: When Subagents Win Over Their Supervisor

**链接**: https://arxiv.org/abs/2610.27574
**作者**: Maosen Zhang, Jianshuo Dong, Yutong Zhang, Jie Zhang, Tianwei Zhang, and Han Qiu
**来源**: cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems are increasingly deployed to coordinate multiple large language model (LLM) agents. However, this also creates new attack surfaces: malicious agents may have chances to exploit the coordination. In this paper, we propose and study the \textit{show-up attack}, in which a malicious subagent manipulates the supervisor into involving it in tasks beyond its assigned scope. To evaluate this risk, we propose SUA-Arena, which implements 6 attack strategies and contains 188 test cases. Then, we evaluate 6 frontier LLMs and find that all of them are vulnerable to show-up attacks. For example, GPT-5.6-Sol as a supervisor suffers an ASR of up to 0.93. Mitigation strategies such as prompting and restricted communication fail to reduce the risk consistently. These results show that multi-agent systems need explicit mechanisms for enforcing authority boundaries.

---

### [37] How Fine-Tuning Objectives Shape Layer-Wise Information in LLM Hallucination Detection

**链接**: https://arxiv.org/abs/2610.27711
**作者**: Kaiyang Wan, Forrest Sheng Bao, Amin Ahmad, Yuxia Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Under matched conditions, classifier-head fine-tuning (\textsc{cls}) paradigm consistently outperforms the LLM-as-Judge sequence-to-sequence (\textsc{s2s}) on binary hallucination detection. We trace this gap to the representations induced by the two objectives. Static analysis shows that \textsc{cls} learns a task-specific discriminative direction, pushing hidden states into a clear two-cluster geometry with stronger class separation and linearly decodable label information. By contrast, \textsc{s2s} relies on the pretrained language-modeling head to make decisions. This minimizes the pressure to reorganize representations, leaving the hidden states much closer to the pretrained backbone. Our analysis also reveals that the \textsc{cls} signal saturates before the final layer, after which upper layers form a plateau of statistically interchangeable and largely redundant representations. However, endpoint redundancy alone does not show whether these layers are dispensable during trainin

---

### [38] Beyond Calibration: Temporal LLM Confidence Assessment Across Languages and Local Settings

**链接**: https://arxiv.org/abs/2610.27702
**作者**: Sahil Kale
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are expected to estimate their own uncertainty, with confidence signals used to guide retrieval, adaptive compute allocation, routing, and selective abstention. We investigate whether confidence signals measured at different temporal stages of problem solving encode distinct forms of epistemic information and remain reliable beyond English-centric settings. Inspired by classical meta-memory theory, we distinguish anticipatory pre-solve confidence (Feeling-of-Knowing, FOK) from retrospective post-solve confidence (Judgement-of-Learning, JOL). We evaluate these signals across two frontier LLMs, multiple reasoning domains, translated Marathi benchmarks, and a newly constructed benchmark of genuinely local Marathi factual questions. Across settings, the cheaper pre-solve signal remains weakly calibrated, while post-solve confidence generally provides stronger epistemic alignment despite its additional inference cost. Confidence behaviour transfers surprisingly well un

---

### [39] TeCoP: Accelerating Diffusion Large Language Model Decoding via Tentative Context Pipelining

**链接**: https://arxiv.org/abs/2610.27583
**作者**: Jui-Chien Tsou, Hsuan-Chi Liu, Wei-Chin Wang, Yu-Syuan Xu, Chun-Yi Lee
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diffusion large language models (dLLMs) predict multiple token positions per forward pass, yet block-wise decoders serialize generation and repeatedly recompute stable predictions. We attribute this inefficiency to coupling a prediction's readiness for irreversible commitment with its utility as context. We introduce Tentative Context Pipelining (TeCoP), a training-free decoder that decouples these roles through staggered block-parallel pipelining and draft-and-verify. TeCoP reuses stable but uncommitted predictions as provisional cross-block context, with commitment governed by confidence and stability checks. Across four LLaDA and Dream dLLMs on GSM8K, Minerva MATH, and MBPP, TeCoP reduces number of forward evaluations by up to 87% and achieves up to 7.50-fold throughput without KV caching and 11.77-fold with caching over the uncached original decoder. It outperforms Fast-dLLM and DSB in throughput across all 12 model-benchmark settings, with and without caching, while keeping averag

---

### [40] The Ephemeral Cost of Switching Optimizers Across LLM Training Stages

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22650&hl=zh-CN&sa=X&d=722323054828194565&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVHzTW7eJDqSQ4ZRZvfXrKws&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=7&folt=kw-top
**作者**: X Zhao, D Wertheimer, A Sharma, R Panda, PP Liang - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Recent work suggests that switching optimizers between pretraining and subsequent training stages incurs a performance cost, but systematic investigation of this phenomenon is lacking. We study the mismatch between AdamW and Muon

---

### [41] Industrial Agentic AI: LLM-Driven New-Generation Agents for Smart Manufacturing

**链接**: https://arxiv.org/abs/2610.26941
**作者**: Lei Ren, Haiteng Wang, Shixiang Li, Jing Zhang, Yuqing Wang, Jingwei Guo 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are enabling agents to move beyond predefined workflows toward autonomous planning and execution, creating new opportunities for smart manufacturing. However, dynamic environments, complex physical constraints, and stringent reliability requirements hinder the direct deployment of general-purpose agents in smart manufacturing. This article presents a systematic overview of LLM-driven industrial agents. First, we analyze five key challenges and discuss the concept and core characteristics of industrial agents. We then establish a unified taxonomy covering application scenarios, embodiment forms, and five capability levels. Next, we propose a four-layer system architecture and detail its core modules and operational mechanisms for closed-loop task execution. Finally, we review representative applications across the industrial lifecycle and outline future research directions. This article provides a structured reference for the design, development, and applica

---

### [42] Tokens-per-Parameter Coverage Is Critical for Robust LLM Scaling Law Extrapolation

**链接**: https://arxiv.org/abs/2605.08541
**作者**: Joshua Shay Kricheli, Alexander Lawrence Reid, Soumajyoti Sarkar, Venkata Gandikota and Paulo Shakarian
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Cooperation Without Adaptation: LLM Agents in a Collective-Risk Dilemma

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22882&hl=zh-CN&sa=X&d=14974249026055683577&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVHIPXZdpWkG7856-oEEMJ2e&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=9&folt=kw-top
**作者**: TK Huynh, DS Duy-Minh, CN Tran, PH Pham… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Language-model agents are increasingly deployed to act on behalf of people in settings where individual decisions shape shared outcomes. We examine whether five production models adapt their contributions to changing risks and partner

---

### [44] SINT-Flow: Schema Integration using Large Language Model Workflows

**链接**: https://arxiv.org/abs/2607.24492
**作者**: Keti Korini, Christian Bizer
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] Profile-DP: Differential Privacy for User-Controlled Profile Release in Personalized LLM Inference

**链接**: https://arxiv.org/abs/2610.27213
**作者**: Mingchen Li, Zifan Peng, Kewei Sha, Lavinia F Pieptea, Heng Fan, Junhua Ding 等 (8 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized large language models (LLMs) increasingly rely on profile-conditioned inference, pairing public requests with rich, user-specific facts. This paradigm exposes the user profile itself, together with the user's explicit sharing preferences. We introduce Profile-DP, a policy-aware local differential privacy framework designed specifically for user-profile release in personalized LLM inference. Profile-DP provably bounds the release of user-withheld facts while treating public instructions, profile schemas, and authorized facts as public side information. By generating a privatized profile that composes with the public instruction prior to answer generation, our framework decouples formal privacy guarantees from downstream model behavior. We develop two finite-domain mechanisms satisfying Profile-DP: DP-SLOT independently perturbs protected attributes, while DP-BLOCK uses public semantic decisions to coordinate their release and jointly sample related attributes. A positive, p

---

### [46] LLM-Attack Suite: A Unified Red-Team Framework for Privacy Evaluation of Split and Distributed LLM Systems

**链接**: https://arxiv.org/abs/2610.22722
**作者**: Georgios Politis and Evangelos Pappas
**来源**: cs.CR cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Service-Induced Congestion in Memory-Constrained LLM Serving

**链接**: https://arxiv.org/abs/2606.15555
**作者**: Ruicheng Ao, Jing Dong, Gan Luo, and David Simchi-Levi
**来源**: math.OC cs.AI cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [48] REM: What to Store, When to Recall, What to Forget in Experience Memory for Coding Agents

**链接**: https://arxiv.org/abs/2610.27377
**作者**: Xinyi Lisa Chen, Pedro Herrero-Vidal, Xiaohan Chen, Xiaojing Yu, Cris Liu, Bingqing Song 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents now autonomously complete long-horizon tasks, such as repository-level coding, through hundreds of think-act steps, yet the experience each run produces is rarely reused on the next. Prior memory systems concentrate on retrieval, finding the most relevant past trajectory. Retrieval cannot observe the running agent, so it cannot decide whether the agent needs an experience, at which point, or for how long. We introduce REM (Reusable Experience Memory), a framework that manages the memory lifecycle from inside the agent's think-act loop through three explicit decisions. What to store: each completed trajectory is consolidated into a phase-structured document, two orders of magnitude smaller than the trajectory. When to recall: the document is injected at the start of the task; the costlier implementation record is withheld until an in-loop gate detects the agent struggling. What to forget: the record is evicted after a single exposure. On repository-leve

---

### [49] Every Model Leaves a Trace: Multi-Resolution LLM Fingerprinting

**链接**: https://arxiv.org/abs/2610.28434
**作者**: Mohammad Reza Modarres, Armin Tourajmehr, Artin Tavasoli, Yadollah Yaghoobzadeh, Mohammad Taher Pilehvar
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models leave model-specific traces in their generated text, but it remains unclear how finely these fingerprints can distinguish related models and which signals remain informative as obvious cues are reduced. We study this through fingerprint resolution, considering both model resolution, from different families to distilled and adapted variants, and signal resolution across behavioral, stylometric, lexical, and semantic evidence. We progressively suppress surface cues, paraphrase outputs, vary the amount of available text, and test generalization across prompt distributions and languages. Our results show that fingerprints persist beyond broad family differences, remaining detectable in distilled models and even LoRA adaptations of the same base model. Although attribution weakens as surface and lexical cues are altered, substantial model-specific signal remains. These signals transfer across prompt sources and languages, with semantic representations proving most robu

---

### [50] DecisionPivot: A Diagnostic Benchmark for Decision Models in LLM Systems

**链接**: https://arxiv.org/abs/2610.28522
**作者**: Xialie Zhuang, Mingcong Lei, Zunhai Su, Ri Liu, Jianjin Li, Peixian Ma 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decision models support routing, guardrails, and output verification in LLM systems. However, item accuracy alone cannot establish whether models make correct decisions across controlled variations or assign reliable confidence to their predictions. We introduce DecisionPivot, a diagnostic benchmark comprising 48 tasks and 40,033 items across seven decision roles. Its core track contains 7,800 items from 13 generated task families, organized into contrast groups with computed answers verified by independently implemented solvers. The complementary reference track contains 32,233 items from 35 public test sets, preserving their original evaluation metrics. We evaluate 40 decision models and 14 general models using documented, model-specific protocols, assessing item and contrast-group accuracy, probability ordering, calibration, and empirical selective coverage. Our results reveal substantial differences obscured by aggregate scores: two 27B models separated by only 2.6 points on the re

---

### [51] MaD-RSI: Model-as-Data for Recursive Self-Improvement of Agent Harnesses

**链接**: https://arxiv.org/abs/2610.28201
**作者**: Yu Cui and Hong He and Ruiqing Yue and Sicheng Pan and Zhuoyu Sun and Yifei Liu and Ting Li and Wenzhuo Zhu and Baohan Huang and Haibin Zhang and Cong Zuo
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement (RSI) of agent harnesses has emerged as an effective approach to enhancing the capabilities of large language model (LLM) agents. By searching the harness space for a specific LLM on a given dataset, RSI can discover a harness tailored to the capabilities and behavioral characteristics of that model. However, such optimization often creates a strong coupling between the learned harness and its target LLM, limiting generalization across models and requiring substantial computational resources to adapt to new LLMs. Moreover, existing RSI methods typically optimize a harness using feedback from a single model and evaluate its generalization to other models only after training. This paradigm treats model differences primarily as a criterion for evaluating generalization rather than as valuable evidence for optimization. In this paper, we introduce a new perspective that treats models as data and places the harness at the center of optimization. Building on this p

---

### [52] Act on Your Behalf, Beyond Your Authorization: Benchmarking LLM Agent Authorization Alignment

**链接**: https://arxiv.org/abs/2610.27548
**作者**: Zhiping Zhang, Franklin Mingzhe Li, Zihao Huang, Tianshi Li
**来源**: cs.AI cs.CR cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM agent acts on behalf of a user, it is expected to act within the authorization scope the user grants. Existing agent evaluations largely measure task completion or harmful consequences and can therefore overlook actions that violate this delegation without producing conventional safety or privacy harms. We introduce AuthorizationBench, a benchmark of authorization alignment grounded in documented real-world cases. A scalable construction pipeline produces 286 executable tasks spanning situational triggers, the presence or absence of direct harmful consequences, and ten application domains. We execute every task with four models at two reasoning-effort settings across three agent harnesses in an authorization-aware sandbox that keeps authorized and out-of-authorization paths executable and observable, yielding 6,864 trajectories. Agents act out of authorization in 19.2% of trajectories, with rates ranging from 10.5% to 26.6% across the 24 configurations. Task completion does

---

### [53] Agents-as-Peers: Bias-Controlled LLM Evaluation as Multi-Agent Peer Assessment

**链接**: https://arxiv.org/abs/2602.02589
**作者**: Yanki Margalit, Nurit Cohen-Inger, Erni Avram, Ran Taig, Seffi Cohen, Oded Margalit
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] When Does Experience Memory Help Closed-Loop LLM Driving Agents? A Controlled Evaluation with Resampled Warmup Pools, Token-Matched Fillers, and Audited Baselines

**链接**: https://arxiv.org/abs/2610.27714
**作者**: Yingxin Jia, Xuanyi Li
**来源**: cs.AI cs.CL cs.CV cs.LG cs.RO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When does experience memory help a closed-loop LLM driving agent? Published gains cannot say, because the two factors we find to matter most, which warmup experiences the pool contains and what any injected tokens do to the prompt, are controlled in none of them. We answer with a controlled evaluation on one audited HighwayEnv testbed (1Hz, gpt-4o-mini for the decisive contrasts). We treat the warmup pool as a resampled random factor (ten disjoint pools) and add token-matched irrelevant-filler controls, oracle-certified diagnostics, caution-pricing metrics, and quantified audits of the baseline ports. The probe suite spans flat-text retrieval (a DiLu port), a single-frame grid port (RESPOND-inspired), our episodic temporal-graph memory, a retrieval-free consolidated rulebook, and a flat K-step observation-history baseline. Four findings follow, each a property of this testbed. (1) Headline memory gains belong to the warmup draw. The reported pool is the best of ten for both retrieval m

---

### [55] Polarity Blindness in LLM Safety: A Systematic Study of Negation, Antonym Substitution, and Adversarial Framing

**链接**: https://arxiv.org/abs/2610.27908
**作者**: Diego Miguel Lozano, Erik Derner, Juan Antonio P\'erez-Ortiz, Nuria Oliver
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Negation remains a persistent challenge for language models across NLP tasks and modalities. We show that this weakness can undermine LLM safety guardrails through a structural vulnerability we term polarity blindness: the failure to recognize harmful intent after polarity-altering linguistic transformations. We study two forms of polarity inversion: grammatical negation and antonym replacement, and use synonym replacement as a polarity-preserving control. We further test whether an adversarial textual wrapper amplifies these failures. Using a 260-prompt benchmark across 10 state-of-the-art LLMs and 3 languages (English, Spanish, Czech), stratified by harmfulness potential and evaluated on a validated 0-5 harm scale, we find that polarity blindness affects most evaluated models, with mean harm scores reaching 4.12 for the most vulnerable model. The effect persists across typologically differing negation systems, suggesting that polarity blindness reflects a broader limitation in semant

---

### [56] When Language Learners Code-Switch: Korean-English Code-Switching in LLM-based Speaking Practice

**链接**: https://arxiv.org/abs/2512.23136
**作者**: Junyeong Park, Jieun Han, Yeon Su Park, Youngbin Lee, Suin Kim, Juho Kim 等 (8 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] PersonaFactor: Preference Factors with Dynamic Selection for LLM Personalization

**链接**: https://arxiv.org/abs/2610.16372
**作者**: Hang Su, Zequn Liu, Jianghan Chao, Qiuyu Tian, Xuesong Lu, and Yingce Xia
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] Toward Controllable Learner Simulation for Teacher Education: Benchmarking Skill-Profile Control in LLM Answer Behavior

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2227-7102/16/10/1752&hl=zh-CN&sa=X&d=17211899705901118405&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVF7mQTXlLgm59RKyNWMc0Jf&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=2&folt=kw-top
**作者**: O Sasson, A Apartsin, Y Aperstein - Education Sciences, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this paper, we focus on the narrower and more measurable prerequisite: can an LLM be directed to behave like a student with a … Can we configure a prompted LLM to simulate a student with a specified skill profile by selectively retaining some

---

### [59] PhonoBridge: Error-Aware Phoneme-Mediated EMG-to-Text Reconstruction

**链接**: https://arxiv.org/abs/2610.27678
**作者**: Wen Qiu, Jiacheng Zhang, Xuanda Chen, Siqi Cai, and Haizhou Li
**来源**: cs.SD cs.CL cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electromyography (EMG) provides a non-invasive means of decoding silently articulated speech into text, but accurate decoding remains challenging due to limited availability of paired EMG-text data. We introduce PhonoBridge, a two-stage framework comprising a channel-aware EMG-to-phoneme frontend and a large language model (LLM) backend for text reconstruction. The frontend is trained on paired EMG-text data that consists of channel-wise feature extraction, cross-channel fusion, and electrode embeddings. With phonemes as the intermediate representation, we expand the backend's training data by converting LibriSpeech transcripts into phoneme-text pairs without additional EMG recordings. To adapt the LLM to frontend noise, we introduce Error-Profile-Guided Augmentation (EPGA), which perturbs transcript-derived phoneme sequences according to error patterns estimated from frontend predictions, generating additional training pairs for the LLM. On the Open Vocabulary silent-speech dataset, P

---

### [60] Local Work, Global Progress: A Convergence Theory of AI Agent Collaboration

**链接**: https://arxiv.org/abs/2610.28286
**作者**: Ivan Ilin, Peter Richt\'arik
**来源**: cs.MA cs.AI cs.LG math.OC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Teams of large language model (LLM) agents are increasingly applied to complex tasks, but their collaboration protocols are mostly designed empirically, without convergence guarantees. We formalize collaborative problem solving as block optimization: each agent improves one part of a shared solution, guided by its local objective plus a correction for how its changes affect the other parts. A coordinator checks every proposal against the global objective and merges proposals that do not interfere with each other. We prove linear convergence up to an error floor that vanishes when the corrections are exact. Interfering proposals can also be merged once their combination has been checked; the rate then depends on how well the proposals actually combine, not on worst-case interactions. With GPT-OSS-120B agents on robot routing, a three-agent team finds collision-free plans in every run, better than those of a single agent that controls all robots. On a larger routing task, a six-agent tea

---

### [61] Sparse RL Relaxation for LLM Reasoning

**链接**: https://arxiv.org/abs/2610.27220
**作者**: Jiabin Fan, Matthias Lindemann, Zita Marinho, Andr\'e FT Martins, Lili Mou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work has explored continuous representations in place of discrete tokens during Chain-of-Thought (CoT) reasoning, often referred to as soft CoT. This is motivated by the idea that a mixture of token embeddings can represent a superposition of multiple reasoning possibilities within a single step. However, it remains challenging to train large language models to realize this potential. Existing work has explored reinforcement learning (RL)-style training for soft CoT. However, these approaches treat soft tokens as actions in a Markov decision process rather than as differentiable intermediate computation steps. Thus, they do not propagate gradients across the soft tokens and miss out on the signal of how the choice of one soft token affects the next. In this paper, we propose a sparse relaxation method for RL (called SpaRLax), which leverages the differentiability of soft-CoT reasoning over time steps and makes training more stable and effective. We adopt an entmax sparsity metho

---

### [62] PORA: Learning When More Reasoning Pays Off for LLM Agents

**链接**: https://arxiv.org/abs/2610.27119
**作者**: Bo Yan, Qi Zhang, Zhen Tan, Tianlong Chen, Song Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents perform tasks over multiple steps and revise their actions based on feedback. As the total reasoning budget is often limited and must support future steps, the agent must choose between short and long reasoning before each action. Longer reasoning may improve the final task outcome by preventing later errors, but it also uses budget capacity that may be needed for future decisions. This creates two challenges: estimating the downstream value of long reasoning and deciding when that value is worth using the remaining budget. We propose Paired Outcome-guided Reasoning Allocation (PORA), which learns this decision by comparing short and long reasoning from the same interaction state. During training, \method{} completes the task twice from each selected state, once with a short reasoning allowance and once with a long allowance, and compares their final quality and total processing to estimate when longer reasoning is valuable. During inference, a controller weighs this estimat

---

### [63] Repairing LLM -Generated Specifications with Deterministic Diagnosis

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22568&hl=zh-CN&sa=X&d=11921092713371349566&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVF8cKcEkt0ku8GW1PlllbAB&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=4&folt=kw-top
**作者**: G Vaccarino, E La Malfa, D Min, H Zhang, PL Lanzi… - arXiv preprint arXiv …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> by 8.7 percentage points over LLM -diagnostic repair. Crucially, the two methods differ most in what they break: LLM -diagnostic repair corrupts … We also highlight a common evaluation issue in LLM formalization: benchmarks themselves are subject

---

### [64] Cache Engineering for Agents

**链接**: https://arxiv.org/abs/2610.28577
**作者**: Tianyu Fu, Ruoxi Wang, Zihan Min, Zhongqi Ren, Zhihao Li, Tengxuan Liu 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents can handle increasingly complex tasks, navigating long trajectories of observations and actions. As these trajectories grow, key-value (KV) cache I/O and storage become the dominant cost. Trajectories can also exceed the LLM's maximum context length, requiring control over active cache growth. Prior work uses context engineering to reduce cache size by trimming or summarizing history. However, modifying the trajectory prefix invalidates subsequent cached states and triggers costly re-prefilling of retained context. Task accuracy can also suffer when too little context is retained to limit re-prefill costs. We propose cache engineering as a new scheme. It allows agents to directly control their active KV cache without modifying the trajectory or re-prefilling retained context. Specifically, agents can proactively use drop to exclude selected cache from future attention and repos to adjust retained keys' position encodings. We formalize these cache opera

---

### [65] LLM ‐Assisted Design of Ultralow‐κ κ Chalcogenides

**链接**: https://scholar.google.com/scholar_url?url=https://advanced.onlinelibrary.wiley.com/doi/pdf/10.1002/advs.78175&hl=zh-CN&sa=X&d=18320614884705706017&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVEoNt3-dPrAfCd7Wc5GeLRu&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=0&folt=kw-top
**作者**: Y Liu, C Jia, Y Hao, X Li, Y Wang, A Oganov 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Here, we present an LLM -assisted design framework that orchestrates LLM -assisted candidate prioritization with highthroughput, physics-… values are not used as the BO or LLM screening objective. These results support a constrained LLM -assisted

---

### [66] Rethinking LLM Fine-Tuning via Weight Space Reparameterization: Preserving Safety during Downstream Adaptation

**链接**: https://arxiv.org/abs/2610.26443
**作者**: Min-Seong Kim, Jongbok Won, Jeesup Park, Yonghee Choi, Dong-Jun Han
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Inspectable LLM-Simulated Participants for Qualitative Interview Rehearsal

**链接**: https://arxiv.org/abs/2610.27333
**作者**: Hangyue Zhang, Qiran Hu, Ziyi Zhang, Hyanghee Park, Yun Huang
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used across research workflows, including research ideation, qualitative analysis, and participant simulation. Within work on participant simulation, prior studies have largely evaluated simulated participants by how realistic or human-like their responses appear, leaving less known about how researchers use and critique these materials when revising interview protocols before fieldwork. We present Rehearsim, an inspectable research probe that treats LLM-simulated participants as materials for methodological rehearsal rather than substitutes for human participants. Rehearsim combines literature-grounded participant construction, interactive interview rehearsal, and traceable thematic review while keeping protocol decisions under researcher control. In a study with 21 qualitative researchers, participants used simulated materials to surface assumptions and gaps, reconsider participant populations, revise target populations, and develop follow-up probes. They also i

---

### [68] The LLM -Attacker: A Unified Red-Team Framework for Privacy Evaluation of Split and Distributed LLM Systems

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22722&hl=zh-CN&sa=X&d=15964344962300811960&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVEjbxwtBitHrZH2BkHgNtZ7&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=1&folt=kw-top
**作者**: G Politis, E Pappas - arXiv preprint arXiv:2610.22722, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We present LLM -Attacker, a framework that records these choices and lets researchers check, compare and extend an evaluation. Compatible attacks reuse recorded messages, and their predictions are saved for independent scoring. The

---

### [69] Abstract Compression of Conversational Audio Context for LLM-based ASR

**链接**: https://arxiv.org/abs/2603.26246
**作者**: Shashi Kumar, Esa\'u Villatoro-Tello, Sergio Burdisso, Kadri Hacioglu, Thibault Ba\~neras-Roux, Hasindri Watawana 等 (10 人)
**来源**: cs.CL cs.AI cs.LG eess.AS
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] AtomSD: Procedural Atom-Guided Self-Distillation for LLM Agents

**链接**: https://arxiv.org/abs/2610.26926
**作者**: Bohan Yu, Pengfei Cao, Kai Tian, Chen Han, Shi-Yang Li, Chenxi Zhou 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) possess broad factual knowledge and strong reasoning capabilities, but solving complex tasks also requires procedural knowledge about how to act. Existing approaches often represent procedural knowledge through trajectories or bundled skills, limiting flexible reuse across interaction histories. This paper introduces Procedural Atoms, fine-grained and independently applicable units that represent Intent, When, Do, and Avoid guidance. Building on this representation, we propose AtomSD, an Atom-guided Self-Distillation framework in which the learner continually extracts Procedural Atoms from its own successful trajectories and distills them into the evolving policy through Atom-conditioned supervision and task-reward optimization. Comprehensive experiments show that AtomSD consistently outperforms strong reward-based and distillation methods, exceeding the state-of-the-art baseline by up to 9.31 points in average performance. Further analyses demonstrate that

---

### [71] Training-Free Continual Learning for Multimodal Forecasting via Prompt Evolution

**链接**: https://arxiv.org/abs/2610.27468
**作者**: Laurent Mombaerts, Jonathan Taws, Jacopo Gargano, Dinesh Gaddam, Kevin George, Srijan Tiwari 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting a forecasting system to a changing world classically means retraining. We ask whether the task of continually learning regimes for time series forecasting can be represented by a piece of text: a guidance block, evolved by outcome-driven reflection and used in a frozen LLM forecaster's prompt. On a refreshed multimodal benchmark (weekly search indices, daily currencies, daily commodities, each window paired with web-retrieved news), we run GEPA-style prompt evolution under strict contamination control to prevent the data leakage common in timeseries benchmarks: the forecaster's knowledge cutoff predates every evaluated window. A 900-word evolved guidance carried by Llama-3.3-70B beats TimeSeries Foundation Models (TSFMs) on held-out data (GM MASE 0.776 vs. 0.898 for TabPFN-TS-3), transfers to more recent models without measurable loss, and costs dollars rather than GPU-days to update. We characterize the loop: out-of-loop gains concentrate in the first reflection, in-loop impr

---

### [72] When Can LLM Reasoning Reliably Reuse Intermediate Results?

**链接**: https://arxiv.org/abs/2610.27662
**作者**: Deyuan Liu, Zecheng Wang, Xuanyi Liu, Jungang Li, Yihao Hu, Mingjie Tang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sampling complete solutions gives large language models more chances to solve a problem, but each attempt starts again. For tasks with several subproblems, all required answers must be correct in the same attempt. Retaining intermediate results can avoid repeating correct work, but errors in those results may affect later attempts. We study when this reuse is reliable and how much computation it requires. For local retries that stop when no candidate passes within the retry budget, we give conditions for correct completion and bound the average number of attempts. We also show how checking cost and the chance of passing a check affect total computation. Experiments across eight reasoning models examine composite mathematics and arithmetic. Across four DeepSeek models, average success on the second subproblem is 36.2 percent without first-subproblem context, 57.2 percent with its answer, and 58.3 percent with its reasoning and answer. These scores measure second-subproblem coverage and 

---

### [73] What a One-Hour Interview Does Not Tell an LLM About You: Interviews Elicit Traits, Not Decision Policies

**链接**: https://arxiv.org/abs/2605.29458
**作者**: Ruoxi Su, Yuhan Liu, Jingyu Hu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [74] SPEM: Structure-Aware Procedural Memory for Efficient Skill Use in LLM Agents

**链接**: https://arxiv.org/abs/2610.26995
**作者**: Ran Zhou, Zehui Kong, Fanyu Lin, Jiaheng Liu, Zhen Zhang, Yuxiang Ren
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents increasingly rely on reusable skills. However, scaling skill libraries makes efficient and accurate skill use difficult. Full skill loading incurs high token and runtime overhead. In contrast, flat semantic retrieval treats skills as independent text entries, ignoring dependencies, execution order, state transitions, and data flow constraints. We propose SPEM, a lightweight structure-aware procedural memory framework for efficient skill use in LLM-based agents. SPEM maintains Atomic Skill Memory for individual skills and Skill-DAG Memory for reusable compositions derived from successful executions. For a new task, SPEM reuses high-confidence Skill-DAG templates when available. Otherwise, it retrieves atomic skills and invokes Skill-GNN for state- and structure-aware skill selection. Successful executions are written back as new Skill-DAGs, allowing procedural memory to accumulate over time. Experiments on ALFWorld and SkillsBench show that SPEM achieves the best overal

---

### [75] Temporal Evidence-Parameter Co-Alignment for LLM Reasoning over Temporal Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.28176
**作者**: Jiapu Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) often struggle with temporally grounded reasoning because their static parametric memory is misaligned with the dynamic evolution of real-world knowledge. Although RAG and Parameter-Efficient Fine-Tuning (PEFT) provide practical ways to enhance LLMs, they remain insufficient for temporal reasoning. Existing retrieval methods typically prioritize semantic relevance while overlooking temporal validity, event order, and evolutionary dependencies, resulting in evidence that is relevant in isolation but temporally fragmented. Meanwhile, conventional PEFT methods usually employ fixed and input-agnostic low-rank updates, making it difficult to capture time-dependent entity semantics and relation drift. To address these limitations, we propose Temporal Evidence-Parameter Co-Alignment (TEPCA), a framework for LLM reasoning over TKGs. TEPCA aligns LLM reasoning with temporal knowledge at both the evidence and parameter levels. At the evidence level, it introduces tim

---

### [76] More Memory, Worse Agents: Error Reproduction and Anti-Persistence in LLM Agents

**链接**: https://arxiv.org/abs/2610.27406
**作者**: Ruhan Wang, Kishan Panaganti, Dongruo Zhou
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents can improve across tasks without updating model parameters by storing experience from their own executions in external memory and reusing it to guide later decisions. A central design question is whether to retain only observed trajectories and outcomes or also the rules, summaries, and skills inferred from them. Retaining these abstractions allows agents to reuse strategies without repeatedly deriving them from raw trajectories. However, errors in stored abstractions can propagate to subsequent decisions through retrieval and reuse. They can also shape execution trajectories, which then become the basis for new abstractions that reproduce the original errors. We term this feedback mechanism error reproduction: errors are regenerated through a cycle of abstraction, execution, and re-abstraction, extending their persistence beyond direct reuse of the original faulty knowledge. We propose Anti-Persistence, a memory design that accumulates trajectories and outcomes while recons

---

### [77] Blackbox Performance Analysis of LLM-based Network Control

**链接**: https://arxiv.org/abs/2610.24348
**作者**: Mahdi Alizadeh, Pooria Namyar, Arvin Ghavidel, Ramesh Govindan
**来源**: cs.NI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [78] Efficient and Adaptable Detection of Malicious LLM Prompts via Bootstrap Aggregation

**链接**: https://arxiv.org/abs/2602.08062
**作者**: Shayan Ali Hassan, Zaeem Mohtashim Khan, Tao Ni, Zafar Ayyub Qazi and Marco Canini
**来源**: cs.LG cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [79] SAPD: Learning from Agent Experience without Environment Interaction

**链接**: https://arxiv.org/abs/2610.27847
**作者**: Juncheng Diao, Haibin Wang, Wei Shi, Yifan Ding, Qingbin Li, Rongxiang Weng 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling the training of Large Language Model (LLM) agents typically requires a large collection of executable environments, whose construction, maintenance, and operation constrain the expansion of training experience. Existing offline trajectories offer an opportunity to reuse interaction experience, yet effectively refining the current policy without revisiting these environments remains challenging: supervised fine-tuning (SFT) can lead to catastrophic forgetting, while online reinforcement learning requires real-time interaction with the environment. To address this challenge, we propose Step-Advantage Policy Distillation (SAPD), a method for learning from offline trajectories using relative step advantages. SAPD decomposes multi-turn trajectories into individual decision contexts for on-policy distillation, allowing the student to generate responses conditioned on recorded histories, and introduces relative step advantage signals to stabilize training. The entire process requires 

---

### [80] Navalia: Advancing Cowork Agents through Verifiable Task Synthesis and Long-Horizon Post-Training

**链接**: https://arxiv.org/abs/2610.26887
**作者**: Hengqi Liu, Ziyuan Liu, Yang Qin, Wanting Zhou, Zichuan Wang, Jiachen Liang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are evolving from conversational assistants into Cowork Agents capable of autonomous planning, tool use, and complex task execution. Financial analysis requires these agents to integrate cross-document evidence and perform multistep numerical reasoning, but expert task authoring is costly, while direct LLM synthesis struggles to produce challenging tasks with reliable answers. We introduce Navalia, a framework for Cowork Agents that combines verifiable task synthesis with long-horizon post-training. Using corporate financial reports as its data source, Navalia semantically selects supporting evidence from complete fact sets and constructs executable computation chains to generate analytical tasks with traceable evidence and actual data dependencies between steps. We further use independent LLM review and programmatic checks to verify evidence consistency and answer correctness. The verified tasks are then used for trajectory collection, cold-start supe

---

### [81] Hearsay or Fact? How Framing and Elicitation Shape LLM Probability Updates

**链接**: https://arxiv.org/abs/2610.27745
**作者**: An-Sheng Jhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as judgment assistants and as stand-in participants in psychology experiments, yet little is known about how much their probability estimates move in response to a single new piece of information. We pair premise-hypothesis items from $\delta$-SNLI with one strengthener and one weakener each, elicit the prior and the posteriors in separate calls, and measure the directional movement s: the mean posterior change signed by the annotated direction, so that the prior cancels out. We vary whether the update is stated ("Here is something else you learned") or reported ("Someone said that"), and whether the model gives one probability or five weighted estimates. We test seven configurations: two local models (Qwen3-8B, OLMo-2-7B; 240 pairs) and five configurations run through agent command-line harnesses (120 pairs), with hypotheses and analysis rules fixed before the formal runs (not publicly registered). Under stated, direct elicitation all

---

### [82] PReMISE: Policy Rubrics as Measurement Specifications for LLM Judges

**链接**: https://arxiv.org/abs/2605.30803
**作者**: Swastik Roy, Rajkumar Pujari, Tharindu Kumarage, Charith Peris, Rahul Gupta, Anna Rumshisky 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] WhatIf: Interactive Exploration of Large-Scale LLM Agent Simulations for Policy Reasoning

**链接**: https://arxiv.org/abs/2604.17615
**作者**: Yuxuan Li, Kyzyl Monteiro, Hirokazu Shirado, Sauvik Das
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [84] The Cognitive Cost of LLM Writing: A Reading-Time Comparison with Human Text

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.23715&hl=zh-CN&sa=X&d=14206452650769672150&ei=bbHYapeYMZHuieoP1PSsqAo&scisig=ACTRDVGIadfYCEyM2_5EVH2hHHDw&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:ACTRDVEEr233VErbxroTWJ0YT-xH&html=&pos=8&folt=kw-top
**作者**: K Cekini, E Biondi, C Boldrini, A Passarella, M Conti - arXiv preprint arXiv:2610.23715, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Building on this perspective, we investigate whether human-written texts and their LLM -generated rewrites exhibit differences in predicted … and their LLM generated rewrites, and apply RoBERTa-RT to compare their predicted reading times. Our

---

### [85] PROVISO: Provenance-Informed Action Selection for Secure LLM Agents

**链接**: https://arxiv.org/abs/2610.27115
**作者**: Bo Yan, Qi Zhang, Ziwen Kan, Fnu Suya, Song Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents act on the external world through tools and third-party skills, so a single executed action can cause irreversible harm. Existing defenses judge a proposed action without tracking whether its content comes from the user or from external sources such as tool outputs, and they judge it in isolation rather than against an available alternative, which forces a trade-off between security and utility. We present PROVISO, a controller that decides which action to commit after the agent proposes an action and before it is executed. PROVISO encodes trusted observations, external observations, the proposed action, and an alternative into provenance-typed memory, relates them through role-specific queries, and commits the action with the highest calibrated value learned from outcomes. On four agent security tasks spanning the agent lifecycle, no baseline exceeds PROVISO in both security and utility. PROVISO improves F1 over the strongest baseline by 13.84 points on SkillsBench and by 7

---

### [86] Large language model and reinforcement learning based autonomous construction and progress updates

**链接**: https://arxiv.org/abs/2610.26899
**作者**: Yifei Xiao, Huasheng Lin, T.Y. Yang
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Due to the rapid growth of the global population, traditional construction methods are gradually unable to meet the current housing demand. The advancement of machine learning algorithms has encouraged researchers to explore their applications in the construction industry, leading to more intelligent and efficient building processes. In particular, the rise of large language models in recent years has provided more possibilities for the transformation from traditional construction to smart construction. In this study, a large language model and reinforcement learning based autonomous construction method is proposed. An enhanced soft actor-critic reinforcement learning algorithm is developed to plan actions for a mobile crane according to construction tasks. Robot kinematics and control algorithms are used to ensure that the actions generated by the reinforcement learning algorithm can be executed by the crane. In addition, a customized embedding model is developed to extract informatio

---

### [87] Beyond Scalar Leaderboards: Adaptive Sampling for Pareto Frontier Identification in Multi-Objective LLM Arenas

**链接**: https://arxiv.org/abs/2610.27447
**作者**: Liang Twist Shan, Jiahao Ai, Zhimei Ren
**来源**: stat.ML cs.AI cs.LG stat.AP stat.OT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The evaluation of large language models (LLMs) is inherently multi-objective, as different models may offer different tradeoffs across performance dimensions such as math, code, and writing. Because such evaluations are often based on costly and time-consuming human feedback, it is important to draw reliable conclusions using as few comparisons as possible. In this paper, we present Vector-Borda Empirical-Gap Elimination (VB-EGE), a fixed-confidence adaptive sampling algorithm for efficiently identifying models on the Pareto frontier in arena-style evaluation, where each comparison evaluates a pair of models on a prompt with respect to a selected performance dimension. VB-EGE progressively eliminates models from an active set once sufficient statistical evidence has been accumulated to certify their Pareto status. Under a multi-objective Bradley-Terry model, we show that VB-EGE returns the correct Pareto frontier with high probability and derive an instance-dependent upper bound on its

---

### [88] After the Attacker Leaves: Benchmarking Carryover Attacks on LLM Agents

**链接**: https://arxiv.org/abs/2610.28425
**作者**: Zhiyue Xu, Xukai Wang, Zhiyuan Huang, Mingjie Zhan, Jian Zhao, Xu-Yao Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLM agents persist state across sessions via two channels: long-lived memory files silently prepended to the system prompt, and scheduled tasks waking the agent without user input. A one-time indirect prompt injection committed to either channel can re-fire across sessions long after the attacker leaves, threats we term carryover attacks. Existing prompt-injection benchmarks evaluate attacks only in the session where malicious content is first observed, leaving the gate governing when and how often a planted payload later re-fires unmeasured. We present CarryoverBench: 12 personal-assistant scenarios and 101 attack tasks across three trigger channels: Instant, same-turn IPI; Autonomous, heartbeat-scheduled; and Latent, memory-resurfaced. A rule-based verifier scores planting and triggering as independent stages. Across five frontier models, planted payloads re-fire without measurable decay over five rounds; conditional on successful planting, the trigger stage often provides lit

---

### [89] VGL-stGen: Learning a shared multimodal model for lung histology and spatial transcriptomics

**链接**: https://arxiv.org/abs/2610.28266
**作者**: Haenara Shin, Dongjoo Lee, Sungwoo Bae, Kwon Joong Na, Daeseung Lee, Hongyoon Choi
**来源**: cs.CV cs.AI q-bio.QM
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> VGL-stGen is a multimodal large language model adapted from a pretrained medical vision-language model using paired lung H&E and spatial transcriptomics with single-cell references. Training integrates image-expression and expression-cell-type pairs, and gene-conditioned pseudo-labels transfer transcriptomic cell-type supervision to histology images. One deployed checkpoint supports thirteen evaluated tasks spanning tissue and cell-type classification, gene prediction and conditional expression completion from combinations of histology, cell identity and observed gene expression. Task-specific decoding produces categorical labels, gene lists and structured expression levels. For conditional completion, fixing queried gene identities and predicting their levels autoregressively improves structured prediction. Controlled adaptation shows that restricting supervision to requested expression-level tokens can further improve image-conditioned completion. Image-permutation experiments indica

---

### [90] Local Allow, Global Deny: Why Per-Action Authorization Does Not Compose in LLM Agents

**链接**: https://arxiv.org/abs/2610.27620
**作者**: Anmol Pandey, Aditya Jain, Liang Chen, Carsten Maple
**来源**: cs.CR cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous LLM agents act through tools under per-action authorization: a local guard screens each tool call in isolation. We show that local authorization does not compose into global authorization. A compositional authorization failure (CAF) is a locally authorized execution, or a pair of locally authorized executions, that violates a global policy spanning intent, purpose, provenance, consent, and delegation. We characterize CAFs along two axes, expressiveness (single-trace safety versus relational k-safety) and observability (a ladder of monitor profiles). Our central result is an impossibility: relational purpose violations form a 2-safety hyperproperty with no per-trace locus of blame, so a per-action monitor that never raises a false alarm detects none of them, independent of the underlying model or decision procedure; they become visible only under cross-execution monitoring, which none of the six guardrails we survey implements. We make this constructive with AL-SYNTH, a SAT/S

---

### [91] AnomalyJev: Towards Evaluating Image Anomaly Explanations via Claim-Level Verification

**链接**: https://arxiv.org/abs/2610.27565
**作者**: Qizhou Wang, Jiawen Zhu, Guansong Pang, Christopher Leckie
**来源**: cs.CV cs.AI cs.CL
**匹配关键词**: LLM, MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent multimodal LLM (MLLM)-based anomaly detection (AD) methods can generate textual explanations that help interpret their predictions. However, reliably and efficiently evaluating these explanations remains challenging. While LLM judges can assess explanations through structured rubrics, they often require substantial token generation, making evaluation costly and difficult to scale. We instead propose to anchor evaluation in the available ground truth by extracting verifiable claims from each explanation and verifying them against the corresponding annotations. We instantiate this idea as AnomalyJev, a lightweight framework that extracts verifiable claims from contextualised representations using ground-truth-defined queries and pointer based heads, without token generation. The claims are then verified against the ground truth to score faithfulness and completeness. For evaluation, we construct a human-annotated set of 640 explanations with over 1,600 expert ratings across in-dom

---

### [92] Aptamers as a sandbox for lab-in-the-loop agentic molecular discovery

**链接**: https://arxiv.org/abs/2610.24806
**作者**: Zachary Cutts, John Coller, Rachel Chen, Hua Tang, Mathias Bellaiche, Ryder Easterlin 等 (10 人)
**来源**: q-bio.BM cs.AI q-bio.QM
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite breakthroughs in AI-driven molecular generation, existing discovery pipelines operate largely in silico, with wet-lab feedback reserved for validation rather than iterative improvement. Whether large language model (LLM)-based reasoning agents can accelerate de novo discovery by iterating with lab data remains unproven. Here we use protein-binding aptamer design as a sandbox (1-2 week cycles, \$1-\$3 per candidate) to demonstrate a wet lab in a closed loop with AI systems. We tasked agentic pipelines with developing aptamer binders against $\alpha$-thrombin and myoglobin across three design-test-improve cycles ($\sim$1,000 candidates per round; $\sim$4,400 constructs). Statistically significant, bead-corrected on-target hit rates among new candidates rose across rounds from 0.0% in Round 1 to 26.0% in Round 2 and 42.1% in Round 3 on $\alpha$-thrombin (37.1% excluding literature motif descendants), and from 10.2% in Round 1 to 3.7% in Round 2 and 33.5% in Round 3 on myoglobin. S

---

### [93] MAS-Guard: Unified Guardrails from Individual Agents to Multi-Agent LLM Systems

**链接**: https://arxiv.org/abs/2610.28397
**作者**: Mohammad Kachuee, Phu Mon Htut, Sheng Li, Nikolaos Pappas, Miguel Ballesteros Martinez, Yassine Benajiba 等 (8 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic AI extends large language models (LLMs) from generating responses to planning and executing complex workflows, substantially expanding their utility while exposing applications to unsafe actions, information leakage, and adversarial manipulation. Multi-agent systems further expand these capabilities through specialization and collaboration, but distributed authority, heterogeneous roles, and opaque or potentially compromised participants make safeguarding even more challenging. Existing defenses address important individual threats but provide fragmented coverage across local execution, system-level interactions, and enforcement mechanisms. We introduce MAS-Guard, a unified framework that closes this gap for safeguarding single- and multi-agent AI applications containing both instrumentable and opaque agents. Within instrumentable agents, the proposed local Agent Guardrail (A-Guard) layer applies task-specific experts to assess agentic events. At the system level, developer-own

---

### [94] Rethinking How to Remember: Beyond Atomic Facts in Lifelong LLM Agent Memory

**链接**: https://arxiv.org/abs/2605.19952
**作者**: Jingwei Sun and Jianing Zhu and Jiangchao Yao and Tongliang Liu and Bo Han
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [95] ValiAssist: Scaling LLM-generated Programming Feedback Validation by Demonstration

**链接**: https://arxiv.org/abs/2610.27248
**作者**: Xiaohang Tang, Rehema Abulikemu, Peng Gao, Yan Chen
**来源**: cs.HC cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI can create programming feedback at scale, but validating its alignment with instructors' pedagogical goals and strategies remains challenging. Instructors may struggle to fully specify validation criteria upfront, as these often emerge through inspecting concrete examples and revising misaligned feedback. We present ValiAssist, a validation-by-demonstration system that infers reusable validation logic from instructors' revisions of AI-generated feedback and allows instructors to inspect and refine that logic as it is applied across other student submissions. In a comparative study with 16 instructors, ValiAssist helped instructors create and refine validation criteria, producing feedback that better aligned with their pedagogical intent (91% vs. 57%) and more than doubling the accuracy of correcting problematic criteria (77% vs. 32%). Our findings suggest that validation by demonstration can help instructors turn judgments they know how to make on individual cases into ex

---

### [96] EGI-BENCH: An Enterprise General Intelligence Benchmark Suite

**链接**: https://arxiv.org/abs/2610.27234
**作者**: Zhiwei Liu, Zhujun Lan, Jielin Qiu, Zixiang Chen, Liangwei Yang, Ming Zhu 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprise adoption of LLMs in agentic workflows is gated by evaluations that span a wide arc of abilities: CRM operations, heterogeneous-document retrieval, personal data understanding, multi-turn planning, tool use, function calling, long-horizon research, and long-context software engineering. These evaluations live today in separate repositories with divergent runners, dependencies, and scoring conventions, which makes cross-benchmark comparison difficult and obscures what a single aggregate number actually represents. We release EGI-BENCH, a unified LLM agent benchmark suite that consolidates eight enterprise facing agent benchmarks (CRMARENA, HERB, PERSONABENCH, USERBENCH, MCP-UNIVERSE, MCPEVAL, BENCHFORCE, LOCOBENCH) behind a single command-line interface with two runtime-budgeted execution modes. On top of the suite we define the Enterprise General Intelligence (EGI) Score, a six-dimensional framework (M1-M6) whose buckets are populated by fine-grained sub-metrics routed from e

---

### [97] Self-Credit: Credit Assignment for Long-Horizon Agentic RL via Intra-group Rescaling

**链接**: https://arxiv.org/abs/2610.28388
**作者**: Fangcong Yin, Ming Yin, Tanvi Bhandarkar, Aashu Singh, Eryk Helenowski, Shlok Kumar Mishra 等 (10 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are commonly trained with RLVR, but the sparse nature of typical RLVR rewards makes credit assignment challenging, especially for long-horizon tasks. We propose Self-Credit, an end-to-end agentic RL method that creates dense supervision signals from sparse outcome rewards using self-generated credit assignment via intra-group rescaling. Self-Credit builds on group-based RL with three components. First, during its rollouts, the policy model generates summaries with citations to earlier turns containing critical evidence, which serve as self-generated credit. Second, we refine this model-generated credit with intra-group rescaling, which compares cited actions across successful and failed rollouts for the same prompt. This approach uses group-level agreement and disagreement to remove undeserved credit and further emphasize credit assigned to critical actions. Third, advantage reweighting uses the rescaled credit weights to update the advantages of the cited turns. On BrowseCo

---

### [98] AudiPsy: Evidence-Grounded Multimodal Reasoning over Spoken Counseling Conversations for Depression Assessment

**链接**: https://arxiv.org/abs/2610.27567
**作者**: Chuanbo Zhu, Run Luo, Weibo Zhao, Yue Li, Kun Qian, Qiang Qu 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Depression assessment from counseling speech requires integrating textual and acoustic psychological evidence across turns, yet existing end-to-end classification approaches lack explicit multimodal evidence interpretation and context-aware reasoning. We propose AudiPsy, an evidence-grounded omni-LLM for depression assessment over spoken counseling conversations. AudiPsy employs an Observation-Assessment-Summary (OAS) paradigm to integrate dialogue transcripts, textual and acoustic emotions, and textual-acoustic emotion incongruence into structured reasoning. OAS incrementally organizes multimodal observations, performs contextualized assessment, and maintains an evolving dialogue summary for subsequent turns. To support this framework, we construct AudiPsy-Counsel, a synthetic spoken counseling conversation corpus with multimodal context augmentation, and develop a unified three-stage curriculum for depression-oriented reasoning. Experiments on DAIC-WOZ demonstrate superior depression

---

### [99] GRADUS: Discovering and Recovering Agent Lessons from the Environment's Latent Syllabus

**链接**: https://arxiv.org/abs/2610.27781
**作者**: Qing Ping, Wei Yang, Panpan Xu, Johannes Kirmayr, Lukas Stappen, Junjie Tang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training LLM agents for policy-constrained tool environments, such as an airline backend with booking, refund, and cancellation policies, requires tasks that exercise the environment's rules individually and in combination. Existing synthesis pipelines let a model propose tasks and retain only those it immediately solves, biasing training data toward easier behaviors. We introduce Gradus (Graded Rungs of Ascending Difficulty from an Underlying System), which decouples what a task should teach from the concrete task and solution used to teach it. Without seed tasks, Gradus treats a fixed environment as a latent syllabus, extracting guarded behavioral operators that capture how actions depend on current conditions and how their effects reshape subsequent decisions. It composes these operators into increasingly demanding tasks while using corpus-level feedback to target missing outcome combinations. Crucially, Gradus jointly calibrates tasks and solutions against the environment: executio

---

### [100] Visual Task Modeling and Automated Planning for Humanoid Robots in Education of Individuals with Autism Spectrum Disorder

**链接**: https://arxiv.org/abs/2610.27162
**作者**: Lada Kudl\'a\v{c}kov\'a
**来源**: cs.RO cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In robot-assisted education, a robot must understand how to complete a task in order to effectively guide a student through it. We present a novel method that enables a semi-autonomous, camera-equipped robot to recognise the task goal and plan actions to achieve it. Our work focuses on Shoebox Tasks, an activity commonly used in the education of individuals with Autism Spectrum Disorder (ASD). These tasks are designed so that the goal can be inferred directly from their visual structure. We have developed a solver that uses a vision-based Large Language Model to convert photos of a Shoebox Task into a Planning Domain Definition Language (PDDL) representation and generate action plans for solving it. We have also implemented a robotic interface that enables a Nao robot to autonomously execute various Shoebox Tasks and assist a student by suggesting next steps or signalling detected failures through action demonstrations, voice commands, or gestures. With an adapted robotic interface, th

---

### [101] RANGER: Retrieval Agent for Navigating Graphs with Semantic Evaluation Rewards

**链接**: https://arxiv.org/abs/2610.28010
**作者**: Artem Mikhaylov, Pavel Konoplev, Nikolay Efanov, Artyom Sorokin, Evgeny Burnaev
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of Large Language Models and Reinforcement Learning offers a promising direction for complex sequential decision-making tasks, such as multi-hop question answering over knowledge graphs. While LLMs provide strong semantic understanding and reasoning capabilities, they often struggle with precise, multi-step navigation in structured environments. Conversely, RL agents excel at learning navigation policies but are hindered by the difficulty of designing semantically meaningful reward functions. This paper introduces a novel hybrid approach in which an LLM serves as a mentor to an RL agent during training by providing dense, semantically informed reward signals. The RL agent, built on a Transformer-based policy and trained with Group Relative Policy Optimization, learns to navigate a knowledge graph to retrieve relevant information. The LLM evaluates the semantic relevance of the agent's traversed paths, generating reward signals that align the agent's behavior with the in

---

### [102] When Do LLMs Help with Feature Selection? A Systematic Empirical Study

**链接**: https://arxiv.org/abs/2610.28556
**作者**: Fateme Memar, Dongjie Wang, Arvin Agah
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can leverage semantic feature names alongside summary statistics for tabular feature selection, yet it remains unclear when such information improves subset selection relative to established statistical methods. We investigate this question within an 18-dataset framework comprising 10 datasets for Group Relative Policy Optimization (GRPO) training, 2 for checkpoint validation, and 6 held-out evaluation datasets. We compare five classical baselines, frozen Qwen2.5-7B and Llama-3.3-70B selectors, and two GRPO-adapted Qwen2.5-7B models, reporting classification ROC-AUC and regression R^2 separately and using dataset-wise ranks for cross-task comparison. Across five seeded evaluation partitions, classical selectors generally achieve higher predictive performance than the tested 7B LLM/RL selectors, including under a pre-specified ~33% feature budget with strict train-only classical fitting, while the 7B selectors retain compact subsets. A cardinality-matched se

---

### [103] Humans Correct Their Judgments Through Debate, but Weaker AI Models Do Not

**链接**: https://arxiv.org/abs/2610.28539
**作者**: Maria Victoria Carro, Denise Alejandra Mester, Facundo Nieto, Oscar Agustin Stanchi, Guido Ernesto Bergman, Giovanni Franco Gabriel Marrafini 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> How can we effectively oversee AI systems that surpass human intelligence? AI Safety via Debate proposes that two AI systems argue opposing positions and a judge, either a human or a weaker model, decides which is correct. By facilitating supervisors in providing high-quality training signals, debate aims to encourage truthful and safe behavior from AI systems whose capabilities exceed our own. However, human judgment is not neutral: people often rely on biases which advanced AI systems may learn to exploit. Drawing on insights from collective intelligence and social cognition, this paper investigates whether debate can guide human and LLM supervisors toward the truth despite their prior beliefs. We evaluate several protocol configurations. We also explore setups inspired by the wisdom of the crowd such as the number and diversity of judges, as well as interaction mechanisms including deliberation and voting. Overall, we find that debate increases accuracy relative to prior beliefs for

---

### [104] Robot-Task Suitability in Heterogeneous Multi-Robot Task Allocation

**链接**: https://arxiv.org/abs/2610.27504
**作者**: Daniel Weiner and Raj Korpan
**来源**: cs.RO cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Heterogeneous multi-robot task allocation depends on estimates of how suitable individual robots are for candidate tasks, yet suitability can be defined in substantially different ways. We compare ten deterministic methods and two LLM-based variants spanning rule-based, similarity-based, requirement-oriented, fuzzy, and semantic approaches. Using common robot and task profiles, we compare how the methods score and rank candidate robots, identify feasibility, and select a top robot, while examining how these outcomes change with team composition, scale, spatial context, capability uncertainty, and task representation. The methods frequently disagree despite operating on identical scenarios. Generic similarity measures can violate properties expected under a one-sided requirement-satisfaction interpretation of suitability, while LLM-based scoring introduces additional stochastic and linguistic sensitivity. These results show that robot--task suitability should be treated as an explicit m

---

### [105] Hallucinations of Large Language Models in Cross-Language Code Translation: Phenomena and Mitigation

**链接**: https://arxiv.org/abs/2610.27868
**作者**: Yali Du, Yunji Zhang, and Ming Li
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Code translation converts source code from one programming language to another while preserving its functionality. Although Large Language Models (LLMs) have improved code translation, their outputs still contain hallucinations: generated code that conflicts with the source program, violates target-language facts, or introduces contextually inconsistent dependencies. These failures are especially harmful in translation because small semantic deviations can silently change program behavior. Existing hallucination studies mainly focus on natural-language generation or code generation, leaving the forms, distribution, and mitigation of hallucinations in cross-language code translation insufficiently characterized. This paper presents a systematic empirical study of LLM hallucinations in code translation. Across three benchmark datasets, six language pairs, and seven LLMs, we construct a taxonomy with three major categories: Semantic Consistency Conflicts, Factual Knowledge Conflicts, and 

---

### [106] Stratified Sparse Attention: Reducing the Sparse-to-Dense Gap at Extreme Sparsity

**链接**: https://arxiv.org/abs/2610.28441
**作者**: Sahil Joshi, Prithvi Dixit, Aryan Katiyar, Agniva Chowdhury, Joseph E. Gonzalez, Anshumali Shrivastava 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model inference over long contexts is increasingly bottlenecked by the cost of attending to a growing Key-Value (KV) cache. Sparse attention reduces this cost by accessing only a fraction of the cache, but existing methods face a trade-off between deterministic retrieval, which captures high-scoring tokens but discards residual attention mass, and sampling, which improves coverage at the cost of higher variance. Hybrid methods combine top-$k$ retrieval with uniform sampling, yet still exhibit a substantial gap from dense attention at aggressive sparsity. We introduce \emph{Stratified Sparse Attention (SSA)}, a unified framework combining deterministic retrieval with score-guided sampling. SSA deterministically attends to high-scoring tokens while sampling the residual using proxy attention scores and correcting for their inclusion probabilities, thereby recovering attention mass beyond the retrieval set. SSA encompasses top-$k$, top-$p$, and hybrid top-$k$+sampling as sp

---

### [107] RSI Control: Can AI Models Perform Covert Sabotage in the Self-Improvement Process?

**链接**: https://arxiv.org/abs/2610.27735
**作者**: Kaiwen Zhou, Udari Madhushani Sehwag
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement, in which frontier AI models work on training the next generation, is quickly becoming a reality. However, the safety of this process has received far less attention than it should. A misaligned model training its successor can shape what that successor knows, how it behaves, and what it wants, and the harm carries forward into the next generation. We study this risk through the lens of AI control. We introduce RSI Control Arena, a testbed in which a frontier model, acting as an autonomous R\&D agent, is given a benign main task from a stage of a successor model's training pipeline together with a covert side task to install a misaligned property in the successor. The testbed contains 16 side tasks in three classes, forming 22 task pairs with main tasks that span the pipeline from data curation to reinforcement learning. We evaluate six frontier models as agents against LLM monitors that read the transcript of the run and the agent's reasoning. We observe tha

---

### [108] Does Multi-Agent Collaboration Reduce Hallucination in Clinical Tasks?

**链接**: https://arxiv.org/abs/2610.27027
**作者**: Won Seok Jang, Harry Bhaskar Joshi, Hong Yu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems improve performance on clinical tasks, and that improvement is often read as evidence of a more trustworthy system. However, the two are not the same claim. A clinician acts on the stated reasoning and not only on the conclusion, so whether collaboration reduces hallucination, and what decides when it does, has to be measured in the reasoning too. Yet most evaluations score only the final answer. We evaluate four systems (a single-LLM baseline and three multi-agent topologies) across four models and three clinical tasks, scoring hallucination, under a factuality and faithfulness taxonomy, inside the rationale each system generates and reporting it alongside the task metric. We report that collaboration buys task performance but not lower hallucination as a rule, and no topology is reliably better than another. The effect differs by model: of the $36$ model--system--task comparisons, $12$ are large enough to resolve --- four decreases and eight increases, with no

---

### [109] COMPASS: Routing via Capability-Oriented Model Profiling with Adaptive Search, Selection, and Tool Use

**链接**: https://arxiv.org/abs/2610.27822
**作者**: Amin Rezaei, Pouya Parsa
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM routing aims to select a capable model at low cost, but specialized routers can require updates as models and tasks change. We propose COMPASS, an agentic router in which an LLM follows a routing recipe, gathers performance and cost evidence through tools, and optionally inspects candidate answers before selecting a model. Our evaluations on LLMRouterBench and DeepSWE show that agentic routing can improve accuracy and lower model-call cost relative to specialized and trained routing baselines, without routing-specific training. On LLMRouterBench, COMPASS reaches 69.85% accuracy at \$139.57, compared with RLCascadeRouter's 69.14% at \$180.22. On DeepSWE under fixed five-fold cross-validation, it reaches 78.1% at \$215, compared with 74.1% at \$500 for the best single model. COMPASS also supports routing across benchmarks and adapts to an expanded model pool by reading new evaluation records, without changing the router's weights or prompt.

---

### [110] Fine-Tuning Small Language Models for Reliable VASP INCAR Generation

**链接**: https://arxiv.org/abs/2608.05387
**作者**: Xinyue Zhang, Jixiang Li, Bin Shao, Baishun Yang, Zhiyang Liu, Weichao Wang
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models can prepare VASP INCAR files from natural-language requests, but so far only large proprietary cloud models come close to handling the tightly coupled, physics-sensitive settings reliably, a dependence that fits poorly with local, high-throughput materials workflows where privacy, cost, and offline deployment matter. We show that a small language model (SLM) can close this gap. The SLM is fine-tuned on reference VASP calculations and paired with VASPGuard, a deterministic post-processor that checks syntax, workflow, and material-dependent constraints; we call the combined model INCAR-SLM. On INCARBench, a benchmark for VASP INCAR generation, INCAR-SLM built on Qwen3-4B outperforms every general-purpose LLM evaluated, exceeding GPT-5.4 by 15.55 points on the 100-point INCAR Score. Most of this gain comes from fine-tuning, with VASPGuard correcting the errors that remain. We further find that model size matters less than expected: once fine-tuning and post-processing are 

---

### [111] SHAM-Bench: A Span-level Hallucination Benchmark Across Multiple Tasks

**链接**: https://arxiv.org/abs/2610.27370
**作者**: Sicong Huang, Ian Lane
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Span-level hallucination detection pinpoints unsupported content in LLM outputs, enabling actionable feedback and targeted mitigation. Existing evaluations for span-level hallucination detection methods are fragmented across tasks, annotation formats, and metrics, and most span-level datasets cover only a single NLG domain, making it difficult to assess whether a detection method actually generalizes across tasks and domains. In this paper, we introduce SHAM-Bench (Span-level Hallucination Benchmark Across Multiple Tasks), a unified benchmark for span-level hallucination detection spanning six NLG tasks, aggregated from existing human-annotated datasets totaling 6,461 examples under a common schema and evaluation protocol. Using SHAM-Bench, we evaluate existing hallucination detection methods and find that fine-tuned detectors often perform well in-domain but degrade under distribution shift, whereas prompt-based methods with reasoning are more robust across tasks. Our analysis further

---

### [112] From DQI to C-DQI: Automatic Codebook Generation and Evaluation for Measuring Computational Discourse Quality Index

**链接**: https://arxiv.org/abs/2610.27937
**作者**: Esther Shizgal, Ron Keinan, Daniel Shtauber, Roee Tzvi Esquira, Ori Aronson, Matan Toledano 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective democratic deliberation is vital for civic engagement and the health of legislative institutions. However, assessing parliamentary discourse quality is traditionally done using expert-scored, theory-based codebooks (CBs), which are rigid, labor-intensive, and prone to biases. While Large Language Models (LLMs) offer a scalable alternative for both schema induction and discourse annotation, ensuring schema quality and mitigating models' inherent bias remains a clear challenge. In this work, we propose a complete protocol for LLM-based codebook generation and evaluation. Starting from the widely accepted discourse quality Index (DQI), we compare top-down (theory-based), bottom-up (data-driven), and hybrid approaches for generating context-adapted schemas. To evaluate these schemas, we define an extrinsic proxy measure, validated by manual annotations, alongside an intrinsic inter-model agreement (IMA) metric, which leverages differing model biases to signal overall reliability.

---

### [113] CovNav: Conformal Prediction-Guided Adaptive Inference for Object Goal Navigation

**链接**: https://arxiv.org/abs/2610.27677
**作者**: Pengying Wu, Zhejia Wen, Kang Ding, Kangjie Zhou, Chunxuan Jiao, Wei Pan 等 (8 人)
**来源**: cs.RO cs.AI cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In object goal navigation (ObjectNav), an embodied agent must find a target object (e.g., "find a bed") in a previously unseen environment, relying on spatial commonsense such as object co-occurrence. Large Language Models (LLMs) encode this commonsense, but deploying them on robots exposes a trade-off between reasoning quality and efficiency: cloud-based models incur latency and privacy risks, whereas small on-device LLMs are fast but prone to hallucinated spatial judgments. Hybrid reasoning LLMs offer both a fast non-thinking mode and a slow thinking mode, which raises a key question for embodied agents: when is slow thinking worth its cost? We propose CovNav, a training-free framework that answers this question with Conformal Prediction (CP), turning dual-process (System 1 / System 2) inference into an uncertainty-aware decision. Much like recent decision models such as Jev, CovNav casts each spatial query as a structured binary decision rather than free-form generation: a local LLM

---

### [114] Recoverability and Verifier Strength: Two Measured Preconditions for Unattended Agent Self-Improvement

**链接**: https://arxiv.org/abs/2610.27465
**作者**: De Wang, Peng Qi
**来源**: cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agent platforms are starting to improve their own agents: they read a deployed agent's execution traces, derive a change, have an automated verifier approve it, and release it with no human author. How much of this loop can safely run without a human? We propose two quantities a platform can measure. Verifier strength $\sigma$ is how well the available verifier -- often an LLM judge -- agrees with a trusted reference verifier; it limits how much a step can improve the agent. Recoverability is how cheaply a bad change can be undone: whether undoing it needs a new verifier approval, and how much of the old behavior a rollback restores. A step should run unattended only if both are adequate. On our platform this rule allows prompt, tool and skill edits to run unattended and keeps weight updates under human sign-off. Our main contribution is these two definitions and how to measure them. We built a platform that applies the rule and tested it in two ways: on the platform's own approval gat

---

### [115] Target-Aware Curation of Hallucination Stress Tests for Large Language Models

**链接**: https://arxiv.org/abs/2610.27247
**作者**: Jiho Lee, Bingquan Zhang, Lin Ting Liang, Soroush Vosoughi, Weicheng Ma
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hallucination stress tests can yield similar average scores across language models even when different prompts elicit hallucinations in each model. We develop a procedure that iteratively edits source-grounded seed prompts to expose hallucinations in a target model. An LLM editor revises each prompt in response to the target's answer and a judge's category-specific score and explanation. In the main setting, the target also receives feedback on its previous response. Experiments cover 500 seeds from seven datasets and ten topics, with intrinsic and extrinsic hallucinations evaluated across open-weight and closed-source models. Editing substantially increases judge-rated severity over the seeds. In the baseline configuration, retained responses fall in the judge's strong-hallucination bin in 77.2% of runs targeting extrinsic hallucination and 74.2% targeting intrinsic hallucination. Later editing rounds account for more than half of the mean score increase. Among 219 prompts that pass m

---

### [116] Corpus Quality Improves, Retrieval Utility Does Not: An Ablation of Preprocessing and Refinement in a Speech-to-QA Pipeline

**链接**: https://arxiv.org/abs/2610.27652
**作者**: Wonsup Shin, Jingu Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Practitioners building training corpora with a pipeline of language models keep a preprocessing or refinement (post-process) stage when switching it on raises the corpus quality. We ablate a production pipeline that turns conference speech into question-answer pairs. The preprocessing stage rewrites the transcript, and the refinement stage filters the generated pairs. Switching each on and off gives four corpora from the same 40 Korean medical and finance sessions. On the corpus itself, quality rises as the stages switch on. Four LLM judges and six human domain experts rank the four corpora the same way, and the fully refined corpus leads by +0.18 and +0.22 on a 1-5 scale. We then ask whether that gain carries downstream. We supply each corpus to six models at inference and measure retrieval accuracy. The ranking does not hold. Enabling the transcript rewrite lowers retrieval accuracy by 0.061, the only stage effect that survives correction for multiple comparisons. That stage also rea

---

### [117] P$^3$-VLM: A Point-based Alternative for Grounded 3D Vision-Language Models

**链接**: https://arxiv.org/abs/2610.28018
**作者**: Anna-Maria Halacheva, Jan-Nico Zaech, Sombit Dey, Luc Van Gool, Danda Pani Paudel
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Examining existing benchmarks for grounding in 3D VLMs reveals a pervasive "semantic leakage" in the evaluation and prompting protocols: a heavy reliance on bounding boxes as spatial prompts or representation primitives. Because bounding boxes are highly informative of object categories, they introduce a shortcut for the models to neglect visual information during 3D VLM training. We demonstrate this with a "blind" LLM that, prompted only with the box coordinates, can perform surprisingly well. To further analyze this shortcut, we propose point-based grounding prompting - querying models with a single 3D point instead of a box. Under this protocol, the accuracy of the blind LLM drops from 36.4% to 18.0% on ScanNet's Nr3D, and similarly degrades for 3D VLMs (e.g. LL3DA). Building on this insight, we introduce P$^3$-VLM, a novel tri-pathway 3D VLM that supports point-based prompts and achieves 52.1% state-of-the-art accuracy on location-grounded captioning under this setting. To achieve 

---

### [118] A Unified Attack Framework against Statistical Generative Watermarks for Large Language Models

**链接**: https://arxiv.org/abs/2610.27653
**作者**: Romina Omidi and Nima Naderloui and Yuan Hong and Binghui Wang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Watermarking has emerged as a key tool for identifying text generated by large language models (LLMs), with current schemes embedding statistical signals into the generation process to enable later detection. In this work, we identify a shared weakness across a broad class of popular LLM watermarking methods, including KGW (and its variants), GumbelSoft, DipMark, ITS, and SynthID. We show that these schemes exhibit a fundamental link between their detection scores and the token probability shifts they introduce during generation. This link, which we call score-ratio alignment, allows an attacker with only black-box query access to the model--and no knowledge of secret keys or model weights--to produce text that evades detection while remaining fluent and natural. We prove that the resulting attack is optimal across all covered watermark families, and show that the weakness is intrinsic: any watermark designed to maximize statistical detection power necessarily induces the very structur

---

### [119] Learn to Modify: Self-evolving Multi-agent Refinement Framework for Conversational Text-to-Motion Generation

**链接**: https://arxiv.org/abs/2610.28210
**作者**: Jianan Li, Jiawei Zhao, Yangtao Zhou, Zhifu Zhao, Shaoxin Wu, Yutao Wang 等 (9 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite rapid progress in text-to-motion generation, existing methods are commonly designed for single-shot generation. When users are dissatisfied with specific motion details, they are often forced to regenerate the entire sequence from scratch, which is computationally inefficient and potentially destroys previously established kinematic context. A practical generation system should instead support iterative user feedback and refine only the affected spatio-temporal regions while preserving the remaining motion. Therefore, we introduce a conversational motion generation paradigm that requires the system to coordinate instruction understanding, motion generation, localized editing, and quality assessment. Recent advances in LLM-driven multi-agent systems provide a promising foundation for such role-specialized coordination. To tackle these challenges, a Self-evolving Multi-Agent RefinemenT Framework (SMART) is proposed for conversational motion generation. Within SMART, to preserve s

---

### [120] RealControlBench: A Benchmark for Interpretability-Informed Fine-Grained Control of LLMs and Agents

**链接**: https://arxiv.org/abs/2610.27295
**作者**: Xinying Cai, Bin Hu, Mingyu Jin, Qiming Zhang, Yang Ouyang, Bangwei Guo 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing steering benchmarks are built around simplified, isolated generation tasks and evaluate a single behavioral attribute under controlled settings that do not reflect the diversity and complexity of practical deployment. As a result, performance on these benchmarks provides only a limited picture of how steering methods perform in the real world. We therefore introduce RealControlBench, a comprehensive benchmark for evaluating fine-grained steering of LLMs and LLM agents across diverse behavioral targets and interaction settings. RealControlBench extends steering evaluation beyond isolated generations to complex, execution-grounded, multi-turn agent interactions, covering five complementary dimensions: instruction-following control, agentic tool-use decision control, reasoning-performance steering, reasoning-length control, and trajectory-conditioned safety awareness. Rather than measuring steering success alone, the benchmark jointly evaluates target controllability and capabili

---

### [121] When Planning Problems Become Hard for LLMs: Separating Structural Complexity from Semantic Interpretability

**链接**: https://arxiv.org/abs/2610.26964
**作者**: Mayukh Debnath, Adeyinka Adedigba, Rammohan Mallipeddi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) struggle with classical planning, but benchmarks rarely distinguish structural difficulty from the difficulty of interpreting symbolic vocabulary. We examine seven STRIPS domains with BFS-optimal plan lengths. For predicting structural difficulty without solving an instance, the zero-training delete-relaxation heuristic $h_{\mathrm{add}}$ outperforms learned alternatives on held-out domains (mean Spearman $|\rho|=0.931$), including ridge regression ($0.707$), object count ($0.657$), and the episodic retrieval architecture ARC ($0.400$). ARC also fails to outperform a linear model using the same features. To isolate semantic effects, we progressively rename predicates while preserving states, transitions, and optimal plans. Valid LLM planning success drops from $67.5\%$ to $40.0\%$ between $0\%$ and $100\%$ renaming, while refusals remain at $0\%$. An LLM supplied with ARC's conditioning information predicts difficulty in context better than trained ARC (mea

---

### [122] ExeBench-FHD: Addressing Fidelity Issues in Decompiler Evaluation

**链接**: https://arxiv.org/abs/2610.28212
**作者**: Akarsh Ashok, Dinil Mon Divakaran, Vivek Balachandran
**来源**: cs.SE cs.LG cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> ExeBench is one of the most widely used benchmarks for evaluating LLM-based decompilers. We analyze ExeBench and identify nine issues that affect how faithfully a test measures a decompiler. Three of them prevent LLM decompilers from recovering C code from ExeBench's function. These are ambiguous parameter order when integer and floating-point types are mixed, unused parameters that optimized assembly may drop, and constants stored outside the function's assembly code. Six more affect test validity: non-void functions without a return, placeholder types, static or inline functions removed by the optimizer, functions named main, trivial bodies and truncated definitions. We present ExeBench-FHD, a backward-compatible revision of ExeBench that adds 16 new fields: call-site assembly, data sections, test wrappers, linked-binary disassembly and five warning flags. In ExeBench, 38.9% of functions have at least one of the five flags; dropping records with any of the four warning flags (all exc

---

### [123] LatticeMind: A Validation-Gated Agentic Framework for Density Functional Theory Workflows

**链接**: https://arxiv.org/abs/2610.26869
**作者**: Nathaniel M. Vegh, Yu Zhu, Rapha\"el J. Prentki, F\'elix Beaudoin, Shuaishuai Yuan, Hong Guo
**来源**: cond-mat.mtrl-sci cs.LG physics.comp-ph quant-ph
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> First-principles calculations are rarely single solver calls: they are multistage workflows in which structures, settings, and saved densities must pass correctly between dependent stages. Language models can write a valid single input, but reliability collapses once stages are chained: a dropped dependency, wrong file handoff, or hallucinated keyword can invalidate results even when the solver runs, and such errors surface only after costly execution. We introduce LatticeMind, a validation-gated agentic framework that converts natural-language requests into executable, checkable density functional theory (DFT) projects. A workflow contract specifies required stages, files, and dependencies; deterministic validators inspect the project before any solver launch; failed checks trigger bounded repair; and reports remain traceable to project files. On a 44-case RESCU benchmark spanning total-energy, density-of-states, band-structure, magnetic, phonon workflows, three non-flagship LLM backe

---

### [124] Memory as Code: Declarative Retrieval over Codified Long-Term Memory

**链接**: https://arxiv.org/abs/2610.27700
**作者**: Aoting Zeng, Yuxin Du, Jianwei Wang, Yizhang He, Shan Jiang, Xuemin Lin 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In long-term memory systems, memories are constructed from interaction histories and retrieved in response to queries, enhancing the reasoning ability of LLM agents. In complex scenarios, facts are scattered across sessions and their relationships evolve over time, making it difficult for existing memory systems to compose them to adapt to diverse queries. Motivated by the modularity and composability of code, we propose Memory as Code (MaC), a unified memory framework that jointly designs memory construction and retrieval through a shared code abstraction. MaC couples codified construction, which establishes executable memory abstractions, with declarative retrieval, which translates queries into structured retrieval programs. Specifically, codified construction builds a three-layer executable memory structure that progresses from an atomic function layer, through a relational layer, to a modular composition layer. Declarative retrieval recasts retrieval from relevance-based fact sele

---

### [125] Auditing the Product, Not the Recursion: The Evaluation Evidence Behind Recursive Self-Improvement Claims

**链接**: https://arxiv.org/abs/2610.27610
**作者**: Zihan Chen, Di Zhu, Lei Nico Zheng
**来源**: cs.LG cs.AI cs.CL cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recursive self-improvement (RSI) promises AI systems, such as self-evolving LLM agents, that become better at producing further improvements. Evaluating this promise requires separating product claims about the final system from process claims about the improvement process itself. Existing surveys specify the evidence these claims require, but how often studies report that evidence remains unmeasured. We examine this question through full-text coding of 114 eligible studies in a reproducible arXiv search frame frozen in October 2026, including 90 that describe their own systems as RSI. The codebook links claims to evaluation designs. Independent human coding, third-reader adjudication, and a separate blind coding of improver comparisons assess coding reliability. Among the 90 RSI studies, 90% report product evaluation beyond development tasks under a broad criterion that includes partial or unstated separation, while 60% report evaluation on tasks unused for selection. Only 22% audit t

---

### [126] Value-Rich, Differently Organized: Measuring Value Expression and Organization in AI-Generated Debates

**链接**: https://arxiv.org/abs/2610.28604
**作者**: Maoyuan Li, Haoyuan Li, Zhongsheng Wang, Jiamou Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current evaluation of LLM-generated debate largely focuses on argumentative quality, leaving the value structure of generated arguments underexamined. We introduce a diagnostic metric framework for comparing how values are expressed and organized in human-reference and AI-generated debates. The framework separates value expression, the range of recognizable values a debate invokes, from value organization, how those values are distributed and sustained across turns. Grounded in Schwartz's Basic-10 value theory, it represents debates as multi-level value distributions over argumentative units, utterances, stances, and full debates, enabling metrics for value coverage, alignment, diffusion, and cross-turn dynamics. Across multiple generation systems, AI-generated debates are broadly value-expressive, often activating as many or more value dimensions than matched human references, but they organize these values differently. Their utterances are more locally value-diffuse, and source-blind

---

### [127] MAMath-Bench: Process-Aware and Robust Evaluation of Multimodal Multi-Agent Mathematical Reasoning

**链接**: https://arxiv.org/abs/2610.26943
**作者**: Xinping Wang, Jie Ma, Rui Xing, Wensong Guo, Xiayi Zhang, Jianhao Deng 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mathematical reasoning is a fundamental capability for educational applications of Large Language Models (LLMs), where reliable problem solving requires not only correct answers but also coherent and verifiable reasoning processes. Multi-agent systems (MASs) have shown growing potential in this domain by leveraging collaboration and verification among multiple LLM agents. However, existing evaluations primarily focus on the correctness of final answers in text-only settings, offering limited insight into multimodal reasoning capabilities, the reliability of intermediate reasoning steps, and robustness against reasoning errors. To address these limitations, we introduce MAMath-Bench, a process-aware benchmark designed to evaluate the multimodal mathematical reasoning capabilities of MASs. MAMath-Bench comprises 1,003 problems spanning 11 mathematical categories, multiple difficulty levels, and several modalities, including text, images, and audio. It features fine-grained milestone anno

---

### [128] TPO: Tri-level Distributionally Robust Learning for OOD Direct Preference Optimization

**链接**: https://arxiv.org/abs/2610.28229
**作者**: Chengtao Jian, Kai Yang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Direct Preference Optimization (DPO) minimizes empirical risk over observed preference comparisons, implicitly assuming that the training preference distribution matches the deployment preference distribution. In practice, this i.i.d. assumption often fails, as preference distribution shift exhibits a natural hierarchical structure across three levels: group-level shift, prompt-level shift, and preference-level shift. Such multi-level distributional mismatch poses a critical challenge for safe LLM deployment, yet existing robust DPO methods typically either model uncertainty over the joint preference distribution or focus on individual sources of shift, leaving the hierarchical structure of OOD preference shifts underexplored. We propose TPO, a tri-level distributionally robust framework for OOD preference alignment, which jointly models all three levels of distributional uncertainty through a hierarchically structured rectangular ambiguity set. By instantiating it with Wasserstein dis

---

### [129] Preference-Aware Pareto Steering for Multi-Task Speech LLMs

**链接**: https://arxiv.org/abs/2610.27200
**作者**: Liuyuan Jiang, Vishal Sunder, Samuel Thomas, Brian Kingsbury, Jeff Kuo, Lisha Chen 等 (7 人)
**来源**: cs.CL cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech large language models (LLMs) perform multiple tasks, including automatic speech recognition (ASR), timestamp prediction (TS), and speech translation (ST). Joint training of speech LLMs creates task trade-offs, yet standard training with fixed loss weights does not generally control the resulting trade-off according to deployment preferences. To address this, we propose Endpoint-Anchored Preference-Aware Sampling Uniformly along the Pareto Front (EA-SURF), an a priori method that adapts scalarization weights so that the resulting task trade-off reflects the desired preference. EA-SURF retains the standard weighted-loss training pipeline, tracking the current model's performance relative to each task-specific reference and adapting the scalarization weights as training proceeds. We theoretically show that EA-SURF can match a desired preference, with the update becoming stationary at the target under checkable regularity conditions. Across six three-objective speech LLM requests, E

---

### [130] DStill: Trajectory Consistency Distillation for Accelerated One-Step Drafting in Block Diffusion Speculative Decoding

**链接**: https://arxiv.org/abs/2610.27379
**作者**: Shreyas Kulkarni, Uttam Gurram, Madhav Kanda, Krishna Teja Chitty Venkata, Shichu Chen, Kartik Balasubramaniam 等 (8 人)
**来源**: cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Block-diffusion speculative decoding accelerates large language model inference by drafting multiple tokens in parallel. However, one-step drafting in discrete diffusion is limited by token factorization error: each token is predicted from the same masked block, without conditioning on the tokens selected at other positions in that step. This can produce inconsistent drafts and reduce acceptance length. Iterative refinement mitigates this limitation by conditioning later predictions on previously committed tokens, though additional passes increase drafting cost. To address this trade-off between draft fidelity and inference latency, we introduce DStill, a two-stage framework that distills a target-conditioned drafter's own multi-step refinement into one-step drafting. We first train the drafter to complete partially revealed blocks, then use its refinement trajectories to train a student to predict the final completion in one pass. Using a curriculum that gradually transitions from par

---

### [131] RELAY: Scaling Historical Build Restoration through Rule Reuse and Agentic Repair

**链接**: https://arxiv.org/abs/2610.27784
**作者**: Olivier Nourry, Yoshiki Higo
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vulnerability benchmarks and software engineering research depend on rebuilding historical software. Yet builds rely on external resources, such as base images and packages, that change independently of the source code. In this study, we examine this environment decay on 14,159 OSS-Fuzz cases. We find that 69.7% no longer complete reconstruction and verification, and that most failures share a small number of recurring failure symptoms. A recurring failure can therefore be diagnosed once and its repair reused. We present Relay, a hybrid framework that uses an LLM to derive and validate deterministic repair rules from representative failures, reuses them without model calls, and escalates cases unresolved by rules to a per-case agent. We evaluate Relay in human-guided and fully automated rule-derivation campaigns and compare it with a per-case agent approach. We find that rule derivation can be fully automated, and that reusable rules restore as many builds as per-case agents with fewer

---

### [132] Rewards for Budget-Aware Multi-Turn Agents That Adapt to Arbitrary Test-Time Constraints

**链接**: https://arxiv.org/abs/2610.28409
**作者**: Tom A. Lamb, Adam Golinski, Eleonora Gualdoni, Sinead Williamson, Michael Kirchhof
**来源**: cs.LG cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are often given an inference budget and asked to maximise success within it. A multi-turn agent has to allocate this budget across many environment interactions. An external harness can enforce the budget, but it remains unclear whether the agent itself can learn when and how much to spend. We ask whether agents can learn this allocation across dynamically specified budgets and which rewards best teach this behaviour. We adapt existing length penalties to budget constraints spanning multiple resource types, introduce new reward formulations, and compare eleven objectives in a shared training pipeline. We train Qwen3.5 models at 4B and 9B on AppWorld with budgets over tokens, API calls, and environment steps, and on the BabyAI gridworld with turn budgets. We train a separate policy for each environment and resource type, with each policy trained across budget values. Training with rewards that penalise overspending substantially improves within-budget success

---

### [133] BitMTP: When Multi-Token Prediction Meets Low-Bit Large Language Models

**链接**: https://arxiv.org/abs/2610.28500
**作者**: Ning Zhang, Shihao Wang, Jinrui Zhang, Chaodong Xiao, Lei Zhang
**来源**: cs.CL cs.AI cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For efficient deployment of large language models (LLMs), methods of ultra-low-bit backbones reduce weight storage, memory traffic, and linear-layer execution cost, while multi-token prediction (MTP) methods reduce sequential decoding steps by predicting multiple future tokens in parallel. Although complementary, the direct combination of these methods cannot accelerate decoding at comparable quality: masked drafting lacks intermediate token input supplied in next-token training, while wider computation and causal key-value (KV) updates can offset the savings from fewer steps. To address these challenges, we propose BitMTP, an algorithm-system co-design framework for efficient MTP on ultra-low-bit LLM backbones. A joint next-token prediction and MTP objective equips a single model with both autoregressive (AR) generation and block-causal drafting. Confidence-only decoding, speculative-only decoding, and hybrid decoding provide different quality-throughput operating points without using

---

### [134] Beyond Experience: Knowledge-Guided Evolution for NPU Kernel Generation

**链接**: https://arxiv.org/abs/2610.27588
**作者**: Xi Chen, Ming Shen, Haotian Yan, Ruoyu Sun, Tianjun Yao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have become capable kernel engineers on mainstream GPU stacks, but they struggle on emerging accelerators such as Ascend NPUs, whose programming model is barely represented in pretraining data. Recent NPU agents address this gap largely through experience: they accumulate memory from their own generation and optimization trials and reuse it on later tasks. We argue that experience alone is not enough for kernel generation. An agent can only remember what it has tried, and it rarely tries a mechanism it does not know. As a result, such memory offers little help when a new operator calls for a different mechanism, and even familiar operators raise unseen situations as optimization proceeds. We present ASCENDEVOLVE, which grounds every step of an evolutionary kernel search in a large external knowledge base built from platform documentation, toolkit headers, and operator repositories. Because this corpus far exceeds any context window, ASCENDEVOLVE indexes it and routes each ag

---

### [135] OptScientist: Automated Discovery of Optimization Laws

**链接**: https://arxiv.org/abs/2610.28562
**作者**: Ma ZhenYao, Yue Liang, Jian-Qiao Zhu
**来源**: cs.AI cs.LG cs.SC econ.EM math.OC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many scientific phenomena are best understood as outcomes of underlying optimization problems, yet automated scientific discovery has largely focused on recovering equations that describe observed input-output patterns. We introduce OptScientist, a novel automated framework for discovering compact symbolic optimization laws directly from data. OptScientist comprises (i) a model that infers symbolic optimization problems by first learning to represent data as an optimization problem and then extracting its symbolic form, and (ii) an LLM agentic system embedding the model in a discovery process that integrates theoretical priors from scientific literature, discovers candidate laws, abstracts their underlying mechanisms, and suggests new data to collect. We first evaluate OptScientist on OptFeynman, a novel benchmark of 99 physics-derived optimization problems, where OptScientist recovers ground-truth laws for over 80% of the problems and remains robust to noisy contextual information, wh

---

### [136] Evolving Self-tuning Benchmarks for Long-Horizon Tool Use

**链接**: https://arxiv.org/abs/2610.27307
**作者**: Hyunji Alex Nam and Michael Dennis and Natasha Jaques and Minsuk Chang
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For AI assistants to move beyond simple chat interfaces and reliably assist users with applications like Gmail, Venmo, and Slack, we need to improve their tool-use capabilities. However, existing tool use benchmarks are still limited and difficult to scale because they rely on human supervision or are too domain-specific. To make data generation scalable, we propose, TURTLE (**T**ool **U**se **R**elated **T**asks with **L**ong-Horizon **E**volution), an Unsupervised Environment Design (UED) approach to evolve existing tasks using a proposer, a solver, and a feedback generator large language model agents. The proposer is rewarded for difficult yet solvable tasks based on the solver's empirical performance, and the feedback generator summarizes the solver's execution traces for the proposer to exploit. TURTLE produces evolving, self-tuning test suites adaptable to different environment requirements, from supporting user simulators and dense document retrieval to interacting across multip

---

### [137] FALCA: Falsification-Aware Reinforcement Learning with Hierarchical Credit Assignment for Long-Horizon Deep Search Agents

**链接**: https://arxiv.org/abs/2610.28361
**作者**: Zijun Dou, Kun Luo, Chaofan Li, Shuqi Lu, Zheng Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon deep search requires LLM agents to iteratively decompose complex information needs, gather evidence from external sources, and maintain a reliable research state under multiple constraints. A central challenge is that early mistakes can be amplified over the search trajectory: agents may anchor on an incorrect candidate, collect partially supporting evidence, overlook contradictions, and accumulate errors that misguide subsequent reasoning. We propose FALCA, a falsification-aware framework that formulates deep search as a propose-falsify process. FALCA adopts a collaborative Searcher-Falsifier architecture, where the Searcher proposes candidate answers or sub-answers, while independent Falsifiers actively seek counterevidence, check unmet constraints, identify conflicts, and produce concise falsification reports for research-state revision. To strengthen this loop, we introduce falsification-aware training, combining SFT warmup on falsification trajectories with agentic RL

---

### [138] Modeling Authentic Research Trajectories: A Graph View of Research Ideation

**链接**: https://arxiv.org/abs/2610.27337
**作者**: Ruochen Li, Zhiyu Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The research idea in a published paper is rarely the project's initial idea. Between the two lies a closed-loop process in which researchers run experiments, derive insights, identify challenges, explore the literature, and revise the idea, with each step motivated by evidence and reasoning they can articulate. We call the path one idea takes through this process, with the evidence and reasoning behind each step, its authentic research trajectory. Although it underlies every scientific contribution, it is rarely recorded. Existing LLM-based research agents generate an idea once, refine it against reviews, literature, or their own experimental results, or search over candidate ideas and experiments. In all of them the text of the idea evolves, while the evidence and reasoning that connected one version to the next are discarded. We propose the Research Progress Graph (RPG), a representation of authentic and complete research trajectories. An RPG records the evolution of an idea as typed

---

### [139] Pareto-Optimal RTL Code Generation via Multi-Objective Reinforcement Learning with Large Language Models

**链接**: https://arxiv.org/abs/2610.26904
**作者**: Koki Takeshita, Kenji Uebayashi, Hikaru Tomonari, Masaya Tsunokake, Koichiro Yawata, Tatsuya Sasaki 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent studies have proposed reinforcement learning with verifiable rewards (RLVR) methods that enable LLMs to generate high-quality RTL circuits from natural-language specifications. Existing approaches optimize circuit PPA (Power, Performance, Area) by aggregating multiple objectives into a single scalar reward, making it difficult to simultaneously generate diverse Pareto-optimal solutions across different trade-offs such as low power, low latency, and small area. However, in practical design, the relative importance of each objective varies depending on product requirements and design constraints; thus, obtaining a diverse and high-quality candidate set is beneficial in that designers can choose a preferred trade-off a posteriori. In this work, we are the first to propose a learning method for LLM-based circuit generation that optimizes, not the quality of a single circuit, but the quality and diversity of the entire circuit set obtained through multiple generations in the PPA obje

---

### [140] When LLMs Manipulate: Measuring Behavioral, Social, and Temporal Effects

**链接**: https://arxiv.org/abs/2610.27573
**作者**: Sadia Asif, Israel Antonio Rosales Laguan, Shumaila Asif, Haris Khan, Muneeb Asif, Muhammad Zeeshan Karamat
**来源**: cs.AI cs.CL cs.CY cs.HC cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can influence user trust and decision-making through subtle linguistic cues, yet the behavioral effects of manipulative outputs remain poorly quantified. We introduce a behavioral computing framework for measuring \textit{behavioral vulnerability}, defined as users' susceptibility to manipulative AI responses. Building on DarkPatterns-LLM benchmark, we generate controlled manipulative stimuli using Manipulation Gradient Descent (MGD), targeting biases associated with authority, urgency, and social proof. We analyze participant responses using the Multi-Stakeholder Impact Assessment Network (MSIAN) to model cross-user influence and the Temporal Harm Propagation Model (THPM) to characterize the persistence of behavioral effects over time. In a study involving 120 participants, manipulative framing produced significant changes in trust calibration and compliance ($p < 0.01$), with effects also propagating across social contexts. These findings highlight the ne

---

### [141] Shaped SAEs: Expanding the Toolkit for Mechanistic Interpretability

**链接**: https://arxiv.org/abs/2610.27375
**作者**: Oveys Delafrooz Noroozi, Bhagyashree Puranik, Upamanyu Madhow
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sparse autoencoders (SAEs) seek to decompose the dense activations of large language models (LLMs) into sparse, potentially interpretable features using a learned overcomplete dictionary. In this work, we ask whether it is possible to enhance the semantic selectivity of the learned dictionary atoms by linearly \emph{shaping} the dense activations prior to learning an SAE. We explore rank-reducing transformations based on the recently introduced J-space corresponding to the averaged Jacobian from the current layer to the LLM output, projecting activations onto the ``live'' subspace spanned by eigenmodes of the Jacobian with larger singular values (which we expect to be more semantically relevant). We also introduce a new approach for training SAEs in which (a)~an affine shaping transformation is learned along with the dictionary atoms, (b)~the atom selection mechanism is based on the TopK projections along the one-dimensional subspace spanned by the atoms, and (c)~reconstruction is carr

---

### [142] MOSS: A Production Framework for Monitoring and Diagnosing Semantic Failures in Search and Recommendation Systems

**链接**: https://arxiv.org/abs/2610.26902
**作者**: Alina Nesen, Prathyusha Kanmanth Reddy, David Relyea, Rohit Avinash Mujumdar, Samaneh Karimi, Bo Shen 等 (7 人)
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting semantic failures in production recommendation and search systems is hard: behavioral metrics lag by days, manual review does not scale, and most LLM evaluation frameworks are designed for offline, fixed datasets rather than continuous operational monitoring. We present Model Sanity Service (MOSS), a production framework that addresses this operational gap by embedding LLM-based relevance scoring into a recurring monitoring loop with targeted sampling, strategy-aware prompting, structured alerting, and diagnostic follow-up prompting that categorizes failures into actionable root causes. MOSS has been running in production at a large U.S. retailer for over six months across recommendation, search, and offer surfaces, and has surfaced two confirmed serving defects. For one of these, a backfill blending defect, MOSS quantified the impact of the proposed fix offline as a 76.4\% relative reduction in alert rate. On a 498-pair human-annotated recommendation benchmark, frontier LLM 

---

### [143] RITE: Evaluating End-to-End Resilience to Silent Tool Errors in E-Commerce Agentic Systems

**链接**: https://arxiv.org/abs/2610.27777
**作者**: Wenshuo Zhang, Yuquan Lin, Yushi Sun, Yishi Lin, Rui Sheng, Peng He 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using LLM agents increasingly answer e-commerce queries through multi-step tool interactions. The expected output of a tool call can shift between agent development and execution, allowing a plausible but incorrect value to be returned without an explicit failure signal. These silent errors may propagate through subsequent decisions into final answers. To study agents' resilience across this end-to-end process, we formulate Silent-error Resilience Task, an interactive task that evaluates whether they complete the original query after a silent error corrupts an intermediate state. We introduce RITE, a benchmark built from human-authored industrial workflows and production-log-derived inputs. To enable controlled and reproducible evaluation, we use a semantic error taxonomy to inject errors into fixed workflow prefixes, freeze recorded tool behavior, and let agents continue freely. It contains 167 matched units across nine e-commerce workflows, yielding 501 silent-error, correct-val

---

### [144] RAG-NIMBF: A Non-Invasive, Modular Benchmarking Framework for Automated RAG Configuration Analysis

**链接**: https://arxiv.org/abs/2610.27816
**作者**: Niclas Hart and Nicolas Weeger
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) has become the dominant paradigm for grounding the outputs of large language models (LLM) in external knowledge. However, practitioners are faced with a vast configuration space comprising chunking, embedding, retrieval, reranking, prompting and generation models, and there is limited guidance on how these components interact. We present RAG-NIMBF, a modular benchmarking framework that attaches to existing RAG pipelines as a non-invasive evaluation layer. It evaluates the configuration space through controlled ablation with end-to-end experiment tracking. The evaluation combines LLM-based answer quality scores, retrieval correctness measures, and runtime indicators. This study validates the framework across multiple generation models on the SQuAD dataset. This process reveals non-obvious interactions and demonstrates how the experiments are tracked. The findings indicate that the retrieval balance of relevance and diversity substantially enhances th

---

### [145] SMART: Semantic Segment Mapping and Assessment of Recognition Transcripts with Contextual Rubrics

**链接**: https://arxiv.org/abs/2610.27820
**作者**: Xiaoyu Gu and Chencheng Wang and Fuyang Li and Yu Xi and Tao Liu and Jiaoqi Guo and Kai Yu
**来源**: cs.CL cs.AI eess.AS
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Word error rate (WER) assigns equal cost to lexical edits despite their different semantic consequences, while overall semantic scores cannot identify which individual errors alter the intended meaning. We formulate ASR semantic evaluation as context-aware, segment-level consequence assessment and propose Semantic Segment Mapping and Assessment of Recognition Transcripts with Contextual Rubrics (SMART), a framework for traceable semantic evaluation and targeted ASR correction. SMART maps reference-hypothesis discrepancies into coherent segments and applies a structured contextual rubric to assign explicit consequence labels. These labels support Semantic Impact Error Rate (SIER), which quantifies consequential errors at utterance, chunk, and lexical levels. Against majority-vote human labels, SMART achieves 0.843 F1 versus 0.745 for direct LLM judgment. Evaluation across multiple LLMs further demonstrates that SMART is relatively insensitive to the choice of evaluation model, while MER

---

### [146] Toward Agentic AI for the 6G Physical Layer: From Algorithm Discovery to Verified Baseband Silicon

**链接**: https://arxiv.org/abs/2610.27797
**作者**: Eric Mittag, Lukas Brechtel, Maximilian Stark, Hans D. Schotten
**来源**: cs.AI cs.NI eess.SP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> 6G will be designed faster than it can be built: AI-driven search already proposes physical-layer algorithms at machine speed, while carrying a single one onto embedded baseband silicon remains specialist work. That silicon imposes hard memory and numeric limits, but also exposes cost structures a GPU lacks, and a design flow that never runs on the target sees neither. We present an agentic workflow in which an LLM coding agent implements algorithms on a commercial baseband SoC, optimizes them down to agent-written vector assembly, and validates them on silicon. The agent is guided by a knowledge base of measured platform facts, checked at every step against evaluators it is instructed never to edit, and metered per phase. We showcase the workflow on an AI-discovered orthogonal time frequency space (OTFS) detector portfolio on the open 6G4All platform. It yields twelve kernels that run cycle-exactly on silicon, their optimized versions at 18k-405k cycles (30-660 $\mu$s) per frame. It a

---

### [147] Evolving Semantic Indexes for Generative Retrieval

**链接**: https://arxiv.org/abs/2610.28568
**作者**: Jinming Nian, Jyun-Yu Jiang, Henry Tsai, Yi Fang, Zhirong Liang
**来源**: cs.AI cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative retrieval (GR) casts search and recommendation as autoregressive generation of discrete semantic identifiers (SIDs). SID design largely determines GR quality, but its discrete, interdependent components (SID construction, collision handling, decoding, and training) cannot be optimized end-to-end with gradients and remain largely hand-designed. We introduce a framework that improves these components through LLM-driven evolutionary program search, to our knowledge the first application of this approach to GR. A locally served, open-weight 31B model mutates executable GR components, so no proprietary LLM API is used, and a 1M-parameter proxy decoder provides fast feedback in place of repeatedly training the 1B target generator. Across 21 SID programs on NQ320K, proxy and target Recall@100 show strong rank correlation (Spearman $\rho = 0.90$). Guided by this proxy, evolution improves the seed GR on NQ320K, MSMARCO300K, and a multilingual e-commerce dataset under a fixed training

---

### [148] Thinking from Above: Efficient Spatial Reasoning with Bird's-Eye-View Visual Tokens

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22700&hl=zh-CN&sa=X&d=68186436851621907&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVFqeAYnr1LhbmXC99jMhiXp&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=3&folt=kw-top
**作者**: F Siddiqui, N Savaliya, SR Chada, E Sachdeva - arXiv preprint arXiv:2610.22700, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We build on Cambrian-S [33], a video MLLM whose spatial instruction tuning on the VSI-590K corpus improves spatial reasoning but leaves this frame-indexed interface in place. We introduce Cambrian-BEV, which keeps the Cambrian-S

---

### [149] Auto-Director: Leveraging Multi-Agent Collaboration for Autonomous Video Editing

**链接**: https://arxiv.org/abs/2610.28346
**作者**: Yuxia Chen, Wenbo Zhu, Yangguang Ji, Zhenxiang Jiang, Teng Zhong, Yu Zhang
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous video editing from open-world resources remains a challenging problem in multimedia content creation. Retrieval-based methods are constrained by fixed source material and lack creative flexibility, while generative models struggle with long-horizon coherence and often diverge from user intent. Both paradigms fail to replicate the structured, multi-stage reasoning that underlies professional post-production. To address these limitations, we present Auto-Director, a tool-augmented multi-agent framework that mirrors professional editorial workflows: a Planning Agent decomposes abstract topics into fact-grounded scripts via retrieval-augmented planning; a Material Agent indexes open-world footage through shot segmentation and visual tagging; an Editor Agent assembles semantically aligned clips with MLLM-driven spatial adaptation; and a Critic Agent governs an iterative Reflect-and-Revise loop that checks scene-level alignment and pacing. To rigorously evaluate this new paradigm,

---

### [150] Xiaomi-Lens-0 Technical Report

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.23279&hl=zh-CN&sa=X&d=7994730564940380041&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVFEH977gSvgFVVljtfhztfR&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=9&folt=kw-top
**作者**: P Fu, Y Liu, Y Sun, H Wang, X Xi, R Zhang 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We develop Xiaomi-Lens-0, a 4B MLLM that decodes region masks from the patch grid of its own vision encoder, taken before the spatial merger, and the visual latents produced by its language model, without an additional hierarchical visual

---

### [151] Teachers, Don't Leave Them MLLMs Alone: Stress Testing the Grading Wall

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DAywcEgAAQBAJ%26oi%3Dfnd%26pg%3DPA188%26dq%3DMLLM%26ots%3Db9-6aywDDC%26sig%3D7lFaEwX8Nqo5PkwzazKaFF0KPoA&hl=zh-CN&sa=X&d=10355978181363796928&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVEtXvNWeGcBXQPhalsHt8Wd&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=2&folt=kw-top
**作者**: O Zammell, C Soares, G Kortemeyer, F Carvalhido - Discovery Science: 29th …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> This paper proposes a stress testing and explainability framework for evaluating MLLM -based grading of hand-drawn physics graphs, instantiated … The framework generates synthetic student-like submissions using Stable Diffusion and analyzes

---

### [152] Multi-Model Large Language Models for Human-Robot Interaction

**链接**: https://scholar.google.com/scholar_url?url=https://ideas.repec.org/a/bjf/ijriss/v10y2026i26p3084-3094.html&hl=zh-CN&sa=X&d=3610626894605683201&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVE0YxUCP-P18EaNlnR7FuAu&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=1&folt=kw-top
**作者**: A Awasthi, A Singh, A Gupta, A Prajapati - … Journal of Research and Innovation in …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> for MLLM -based HRI that integrates voice, pointing gestures, visual perception, and contextual cues for human intention and object understanding. The framework processes information from each modality and combines the resulting evidence

---

### [153] SimpleVLN: Towards Simple and Frontier Vision-Language Navigation

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.23203&hl=zh-CN&sa=X&d=17874319193362267033&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVHEMEaVr2C49WAh8cHrr6lu&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=6&folt=kw-top
**作者**: L Hong, W Cai, J Chen, X Zhou, B He, Y Guo 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We instantiate SimpleVLN across multiple MLLM backbones and model sizes, demonstrating its generality. SimpleVLN achieves 76.7% and 80.1% success rates on the R2R-CE and RxR-CE splits, respectively, substantially outperforming existing

---

### [154] Stuck on Shuffle: On Attribute-Object Binding in Vision-Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22602&hl=zh-CN&sa=X&d=12850236082510900554&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVGUfeIZ8nGfxqpDj--bf09G&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=8&folt=kw-top
**作者**: NY Tamir, M Green, I Tzachor, O Shimshi, D Samuel… - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> both CLIPstyle dual encoders and recent MLLM -based embedders. These findings motivate … We thus finetune an MLLM -based embedder exclusively on synthetic attribute-binding text. … Appendix D shows that our finetuning recipe

---

### [155] Can multimodal large language models evaluate AI-generated industrial design images? an empirical comparison with human expert assessment

**链接**: https://scholar.google.com/scholar_url?url=https://www.spiedigitallibrary.org/proceedings/Download%3FurlId%3D10.1117%252F12.3132247&hl=zh-CN&sa=X&d=12118079500647622055&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVGvTQGXW69o7WBIWfRkhAdW&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=7&folt=kw-top
**作者**: Z Liu, J Xie, P Li, X Pang, S Jiang - Proc. of SPIE Vol, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Specifically, this study examines the extent to which MLLM ratings of AI-generated industrial design images agree with human design experts overall and across evaluation dimensions (RQ1), whether this agreement differs between objectively

---

### [156] Mitigating hallucinations in Multimodal Large Language Models via Token-Aware Visual Enhancement

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0031320326021060&hl=zh-CN&sa=X&d=17731677233102424662&ei=brHYao2eBPaUieoPlbSlsQ8&scisig=ACTRDVEtsMcBvet6XE_7nChpHqeG&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:ACTRDVHBiLID0dsXs0coH3hBX4Zg&html=&pos=4&folt=kw-top
**作者**: W Huang, K Chen, J Wang, M Rashid, Y Li, R Shao… - Pattern Recognition 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> While SVE helps mitigate hallucinations by guiding the MLLM to pay more attention to vital visual tokens, we still observe that the model tends to hallucinate when responding to questions that require understanding fine-grained image details

---

### [157] ABACUS: A Benchmark for Image Editing Models to Assess Object Category and Counting Under Scene Conservation

**链接**: https://arxiv.org/abs/2610.28316
**作者**: Aymen Lassoued, Angelique Loesch, Romaric Audigier
**来源**: cs.CV cs.AI cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Instruction-based image editing models can now add, remove a specified number of objects or change their category while preserving the scene. Yet these models often fail to produce the correct number, and these failures grow sharply as scenes become more complex and the requested count increases. Current benchmarks largely miss this problem: they score edits with holistic similarity metrics or with vision-language model (VLM) judges that are themselves poor at counting, so numerical errors go unnoticed or are graded incorrectly. As a result, the true numerical ability of today's editing models has never been accurately measured. We address this issue with ABACUS, a new benchmark, evaluation protocol and dedicated scoring metric for numerical image editing. Our protocol is judge-free: no VLM or MLLM scores an edit or counts objects (a VLM only confirms the category of rare ambiguous crops). Instead, it verifies each edit at the instance level against panoptic ground truth confirmed by d

---

### [158] EEG Features of Cortical Intent for Urination and Defecation in Healthy Aging and Spinal Cord Injury: A Descriptive Feasibility Study for BCI Neurorehabilitation

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2076-3425/16/10/1126&hl=zh-CN&sa=X&d=11296070680716739564&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVECuVx8f6NHLwIY28Frz2nq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=9&folt=kw-top
**作者**: C Xue, X Cai, Z Guo, H Xu, J Xie, R Ji 等 (9 人)
**匹配关键词**: EEG, BCI
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> This study aims to characterize the spatiotemporal Electroencephalography ( EEG ) dynamics and compensatory cortical reorganization … EEG neurofeedback and motor-attempt paradigm for SCI patients and healthy individuals. We compared

---

### [159] DiffEEG: A Self-Supervised Denoising Diffusion Model for Learning EEG seizure-related Representations

**链接**: https://arxiv.org/abs/2607.11578
**作者**: Abdulkader Helwan, Lina Abou-Abbas, Hussein El Amouri, Belkacem Chikhaoui and Khadidja Henni
**来源**: cs.LG cs.AI cs.CV eess.SP
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [160] EEG-Based Classification of Hypnotic Susceptibility Using Two-Dimensional Convolutional Neural Networks

**链接**: https://arxiv.org/abs/2610.27738
**作者**: Krzysztof Wrobel, Grzegorz M. Wojcik, Filip Postepski, Andrzej Kawiak, Katarzyna Zemla, Grzegorz Sedek
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Guided Imagery (GI) is a mind-based relaxation technique widely used in clinical and therapeutic settings. Objectively assessing whether a patient has entered a relaxed state remains a challenge for clinicians. This study investigates electroencephalography (EEG)-based classification of hypnotic susceptibility using two-dimensional Convolutional Neural Networks (2D CNNs) applied to minimally preprocessed signals, without manual feature extraction. Data were collected from 62 male participants (32 Control, 30 Hypno) using a 256-channel dense array amplifier during Guided Imagery or cognitive task conditions. A sliding-window framework evaluated up to 868 independent models across seven anatomically defined brain regions and 124 ten-second time windows. Segment-level random-split screening was followed by Leave-One-Subject-Out (LOSO) cross-validation to obtain subject-independent performance estimates, and an ensemble approach combined predictions across K = 10 windows. The best single-w

---

### [161] Patient-independent EEG seizure detection using channel attention and dual-branch time–frequency features

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s00521-026-12518-w&hl=zh-CN&sa=X&d=7666339314883400493&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVElqj67jlAT5rN4c5TyBYUN&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=2&folt=kw-top
**作者**: H Tiwary, A Bhavsar - Neural Computing and Applications, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We developed a patient-independent EEG -based seizure detection model that generalizes across subjects despite inter-subject variability … the input EEG before time–frequency feature extraction, allowing the contribution of individual EEG

---

### [162] Seeing Seizures: A Large-Scale Empirical Study of Video and EEG Deep Learning for Automated Rodent Seizure Detection and Severity Grading

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.22566&hl=zh-CN&sa=X&d=17144082392160482354&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVFZiiT-lI7fyTnuMRhk14fC&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=8&folt=kw-top
**作者**: A Das, S Ganguly, N Massey, HP Doan, Z Jiang… - arXiv preprint arXiv …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Manual annotation of synchronized video and EEG recordings is a bottleneck in preclinical seizure research. We present an empirical study of seizure detection and behavioral severity grading using 24,131 paired clips from 601 sessions across 20

---

### [163] CNN-based classifier for subject-independent MBTI Extraversion/Introversion preference classification from short-time EEG signals

**链接**: https://arxiv.org/abs/2610.28442
**作者**: Filip Postepski, Grzegorz M. Wojcik
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study examines whether short, minimally preprocessed EEG segments contain sufficient information to distinguish between individuals classified as extraverted or introverted according to the Myers--Briggs Type Indicator (MBTI). EEG recordings from 50 participants were divided into 4-s segments and analyzed using a subject-independent nested 5-fold cross-validation procedure to compare EEGNet, EEGProgress, and a newly proposed compact convolutional architecture, SSCNet. SSCNet achieved the highest mean accuracy (0.6481), AUC (0.7063), and F1-score (0.6276). The proposed architecture also showed the lowest variability across folds. SSCNet demonstrated the best computational efficiency, with the shortest median training epoch time and the highest training throughput despite having a similar number of trainable parameters to EEGProgress. The results suggest that MBTI Extraversion--Introversion preferences may be moderately predictable from short time-domain EEG segments without manual 

---

### [164] Single-Lead EEG -based virtual reality motion sickness detection using interpretable feature selection

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s11517-026-03702-0&hl=zh-CN&sa=X&d=4479547065625293042&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVHiuAJPjzS4kF9-D-G9A15U&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=6&folt=kw-top
**作者**: M Zhu, C Hua, Q Wang, J Fu, S Xiang, Z Wei 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background Electroencephalography ( EEG ) is a key method for detecting virtual reality motion sickness (VRMS), but multi-lead recordings and high-dimensional features increase processing complexity, device cost, and user burden. Objective

---

### [165] EEG -BlinkMI: intention-aware blink interaction with intensity encoding using single-channel EEG

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s42486-026-00262-y&hl=zh-CN&sa=X&d=66807214886761926&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVEMH-7J3K27KGpV2Zzr4Osz&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=5&folt=kw-top
**作者**: W Guo, Y Hao, H Rong, Y Zhang, T Zhang, J Liu - CCF Transactions on Pervasive … 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> , this paper proposes EEG -BlinkMI, an intention-aware blink interaction framework based on single-channel EEG . During development, … releases EEG -BI, the first open single-channel EEG benchmark dataset for blink interaction, to the best

---

### [166] Multilingual Brain Decoding Reveals Shared Cortical Semantic Geometry

**链接**: https://arxiv.org/abs/2610.26927
**作者**: Yi Guo, Yong Hu, Michael Kwok-Po Ng, Shuqiang Wang
**来源**: q-bio.NC cs.AI
**匹配关键词**: Brain Decoding
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human languages differ markedly in lexical and syntactic form yet can convey similar semantic content. The neural basis of this cross-language semantic commonality remains unclear. Here we developed a multilingual brain decoding framework and analysed brain recordings from 227 participants spanning Chinese, English and French. We found that cortical semantic representations exhibited consistent semantic geometry relationships across languages and individuals, revealing a shared cortical semantic geometry. Importantly, the cross-language consistency of cortical semantic geometry increased from sensorimotor to higher-order association cortex, forming a shared semantic geometry gradient closely aligned with the principal cortical functional gradient. Our work establishes generalizable multilingual brain decoding and identifies stable cortical semantic geometry as a neural basis for semantic commonality across languages.

---

### [167] Interpretability of EEG Models via Sparse Autoencoders

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2504-4990/8/10/337&hl=zh-CN&sa=X&d=9421956192224718370&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVFwXWiW_xUhKOdAwyeYWMjZ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=1&folt=kw-top
**作者**: F Farooq, M Wang - Machine Learning and Knowledge Extraction, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> have demonstrated strong performance in electroencephalography ( EEG )-based motor-… (SAEs) to decompose the latent representations of MI- EEG decoders, instantiated on CIACNet, a … Our findings highlight the potential of SAEs for

---

### [168] Resting-State EEG Graph Analysis Reveals Enhanced Alpha-Band Integration in High-IQ Individuals: The MENSA-Connect Project

**链接**: https://scholar.google.com/scholar_url?url=http://www.imrpress.com/journal/JIN/25/10/10.31083/JIN56100&hl=zh-CN&sa=X&d=10433453823634788985&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVEQFLOsmVlIc0Q5Vnc8pcuw&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=7&folt=kw-top
**作者**: M Moci, A Zauli, C Iacovelli, G Reale, M Garbuglia… - Journal of Integrative …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> -state electroencephalography ( EEG ) connectivity differs between high-intelligence individuals (MENSA members) and controls using graph-theory metrics: clustering coefficient, characteristic path length, and small-worldness. Methods: Resting-state

---

### [169] Multiscale Temporal-Spectral-Spatial EEG Learning With Modality-Specific and Modality-Invariant Representations for Emotion Recognition

**链接**: https://arxiv.org/abs/2610.27521
**作者**: Jian Zhang, Manrong Liu, Yilei Huang, Wenhua Liu, Xiaohui Yang, Lijun Yang
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal physiological signals provide complementary cues for emotion recognition. They also raise two related challenges. Emotion-related EEG patterns vary across time, frequency bands, electrodes, and brain regions. Different physiological modalities also contain both modality-specific and shared affective information. This paper presents GMSI-Net, an EEG-centered multimodal emotion recognition framework. It has three key components. The temporal-spatial-spectral-region (TSSR) encoder models multiscale temporal-channel patterns, differential entropy features, and local-to-global brain-region relations. The modality-specific representation (MSR) branch uses bidirectional cross-modal attention and learnable gates. It controls information transfer while retaining modality-specific cues. The modality-invariant representation (MIR) branch learns a shared affective representation. An adaptively weighted contrastive loss aligns this representation across modalities. Independent multiscale

---

### [170] Region-Specific EEG Classification of Hypnotic Susceptibility Using a Sliding-Window 2D CNN: A Subject-Independent Evaluation

**链接**: https://arxiv.org/abs/2610.28427
**作者**: Krzysztof Wrobel, Grzegorz M. Wojcik
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We investigate whether a 2D Convolutional Neural Network (CNN) trained on minimally preprocessed EEG signals can classify hypnotic susceptibility across distinct brain regions. Sixty-two male participants (32 Control, 30 Guided Imagery / Hipno group) underwent a 20-minute EEG recording using a 256-channel EGI cap. A sliding-window approach evaluates all 10-second windows within the recording for each of seven predefined brain regions (prefrontal, frontal, temporal, central, parietal, occipital, and facial), yielding up to 868 independently trained models. Initial screening with a segment-level 90/10 random split showed that five regions exceeded the 0.67 accuracy threshold, with the occipital region achieving the highest mean accuracy (0.721) across 90.3% of windows. Subject-independent evaluation via Leave-One-Subject-Out (LOSO) cross-validation, however, substantially revised this picture: occipital performance collapsed to near-chance (mean ACC 0.453, AUC 0.429), revealing that high

---

### [171] A self-organized QTPat-based feature-engineering framework for subject-independent classification of English-and Turkish-associated EEG signals

**链接**: https://scholar.google.com/scholar_url?url=https://journals.sagepub.com/doi/full/10.1177/00368504261499564&hl=zh-CN&sa=X&d=3441227303437506114&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVEFTDORhFgYESUk1lpJFJ_E&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=4&folt=kw-top
**作者**: AM Yildiz, T Keles, M Eris, PD Barua, M Baygin, B Tasci… - Science Progress 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> For our experiments, we utilized an EEG dataset containing 1652 English sentence- EEG pairs and 1600 Turkish sentence- EEG pairs. … cap system that acquired 14-channel EEG signals. Our preprocessing pipeline involved subjecting

---

### [172] EEG Resting-State Beta Band Dynamic Functional Connectivity Reveals State-Dependent Disruption of Language Network Lateralisation in First-Episode …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0028393226002599&hl=zh-CN&sa=X&d=12249454388171322944&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVGG3VukIwDgiuAR5NTcdASd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=3&folt=kw-top
**作者**: R Aubonnet, FF Nastro, C Di Lorenzo, M Hassan… - Neuropsychologia, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Language disorganisation is a core feature of schizophrenia with significant functional consequences. However, its neurophysiological substrates remain poorly characterised, particularly in the early stages of the illness. This study investigated

---

### [173] The Influence of the Role of Peer Presence on Game‐Based Chemistry Learning: Evidence From EEG

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/abs/10.1002/jcal.70361&hl=zh-CN&sa=X&d=3909063172736194521&ei=bbHYarGnNuS0ieoP99PDsQo&scisig=ACTRDVE4DGh6LoI8UZFGuyZ2B06c&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:ACTRDVFFClCT7j3lRrMoc1sxSf8K&html=&pos=0&folt=kw-top
**作者**: Q Huangfu, Y Guo, T Deng, Z Huang - Journal of Computer Assisted Learning, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> EEG analyses showed that the collaborative condition elicited higher theta and alpha power than the individual condition across both phases, although differences from the competitive condition were not consistently significant. These patterns may

---

### [174] Parameter-Efficient Adaptation of Time Series Foundation Models for Electrical Load Forecasting

**链接**: https://arxiv.org/abs/2610.28200
**作者**: Aliullah, Julian Oelhaf, Edouard Fouch\'e, Jessica Deuschel, Christian Bergler, Andreas Maier 等 (7 人)
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate electrical load forecasting supports power-system operation across countries, regions, cities, and buildings, but repeated development of target-specific models is costly. Time series foundation models (TSFMs) provide reusable pretrained backbones, although multi-domain pretraining may not fully capture load-specific characteristics. This paper compares pretrained inference, full fine-tuning, and low-rank adaptation (LoRA) in terms of forecasting accuracy and adaptation efficiency across four electrical load aggregation levels. MOIRAI 1.0 Large serves as the primary backbone, while Chronos-2 assesses whether the findings transfer across model families. The evaluation covers both in-distribution (ID) and out-of-distribution (OOD) settings and examines whether compact adaptation provides consistent gains over strong pretrained checkpoints. Pretrained foundation models outperform the implemented seasonal naive and XGBoost baselines across the evaluated aggregation levels. On MOIR

---

### [175] Tabular Foundation Models Can Learn Association Rules

**链接**: https://arxiv.org/abs/2602.14622
**作者**: Erkan Karabulut, Daniel Daza, Paul Groth, Martijn C. Schut, Victoria Degeler
**来源**: cs.AI cs.DB cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [176] HarnessIR: Harnessing Multimodal Foundation Models for Universal Real-World Image Restoration

**链接**: https://arxiv.org/abs/2610.10133
**作者**: Xiangtao Kong, Shuaizheng Liu, Rongyuan Wu, Lingchen Sun, Zhengqiang Zhang, Jixin Zhao 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [177] MBTI: A Multi-Branch Efficient Fine-Tuning Framework for Hyperspectral Image Classification with Foundation Models

**链接**: https://arxiv.org/abs/2607.12782
**作者**: Mingzhen Xu, Haonan Guo, Di Wang, Yinghua Qu, Zhiliang Zhou, Lei Zhang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [178] Towards Consistent Geospatial Representations: Aligning One Encoder to Many Foundation Models

**链接**: https://arxiv.org/abs/2610.28313
**作者**: Arthur Ouaknine and David Rolnick
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models (GFMs) differ widely in pretraining objective, modality and resolution, and none leads across benchmarks. We ask whether their representations are complementary, and whether a single encoder can inherit that complementarity. We introduce Pangaea-Latents, an extension of the Pangaea benchmark providing frozen embeddings of $5$ GFMs over its $11$ datasets, along with reproduced baselines, and find GFM embeddings to be neither redundant nor disjoint. We then propose GeoMixture, a preliminary framework to align a ViT to several GFMs per dataset through a multi-representation alignment (mREPA) objective. Our encoder ties the best GFM in average rank across nine Pangaea datasets, trading peak performance for cross-task consistency.

---

### [179] Staged Continual Adaptation of Multimodal Foundation Models for Japanese Financial Documents

**链接**: https://arxiv.org/abs/2610.27904
**作者**: Genshin Kakimoto, Atsushi Yanagisawa
**来源**: cs.AI cs.CL cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Staged post-training of multimodal foundation models chains vision-language alignment, reasoning distillation, and domain tuning, yet how each phase trades capabilities against the others remains under-characterised. Tracking an 8.4B-parameter model from an un-fine-tuned baseline through three training phases on Japanese financial documents (evaluated on five text-input benchmarks), we find the phases interact non-additively: math-only distillation overwrites the financial knowledge acquired earlier even as procedural math skill survives, and the domain phase repairs more than it installs. A skip-phase ablation is best for domain knowledge but forfeits numerical-reasoning gains, so per-phase contributions are not decomposable and the best checkpoint is task-dependent, with implications for checkpoint retention and scheduling rather than added stages.

---

### [180] Convergent Performance, Divergent Mechanisms in LoRA-Adapted Vision Foundation Models for Brain MRI

**链接**: https://arxiv.org/abs/2610.28255
**作者**: Cecilia Diana-Albelda, Fiona Kekwick, Raghav Mehta, Aleksandra Kulbaka, Paul M. Matthews, Jesus Bescos 等 (9 人)
**来源**: cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Adapting Vision Foundation Models (VFMs) to medical imaging via LoRA has become standard practice, yet model selection is guided almost entirely by downstream task metrics, treating backbones with similar performance as interchangeable. We investigate whether equal performance implies equal internal representational shift. We analyse four ViT-B/16 backbones, DINOv3, SigLIP2, MerMED-FM, and BiomedCLIP, pre-trained with different objectives (self-distillation vs. contrastive vision-language) and on different data domains (natural vs. medical images). We adapt each to brain tumour segmentation and evaluate on six datasets covering both segmentation and Alzheimer's disease classification. Using attention divergence, weight-change analysis, and activation patching, we find that the four models converge to similar segmentation performance (mean Dice 78-81%) through markedly different internal dynamics, yet diverge in cross-task transfer: segmentation adaptation improves Alzheimer's disease c

---

### [181] Learning Native Reflection in Unified Models with Interleaved Reinforcement Learning

**链接**: https://arxiv.org/abs/2609.35767
**作者**: Yijia Fan, Ziqi Huang, Zhongang Cai, Yan Li, Zimo Wen, Wanqi Yin 等 (8 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Unified Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [182] Discrete Neural Interlingua for Ontology-Agnostic EHR Modeling

**链接**: https://arxiv.org/abs/2610.27047
**作者**: Tong Ding, Caiwei Tian, Dongmin Bang, Ming Y. Lu, Sophia J. Wagner, Andrew Zhang 等 (9 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> EHR foundation models promise scalable clinical prediction across health systems, yet their deployment is constrained by a tokenization bottleneck. The same clinical concept can appear as different ontology codes, local identifiers, synonyms, or free-text descriptions, which standard EHR tokenizers treat as unrelated symbols. A model trained on MIMIC-III with a closed-vocabulary tokenizer can use only 13% of eICU events. We introduce MEDIATOR, a discrete ontology-agnostic tokenizer that maps any clinical concept expressed as text into a shared vector-quantized codebook, turning EHR harmonization into open-vocabulary tokenization without manual mappings or a fixed vocabulary. Trained with synonym supervision and guided by enriched concept descriptions, code co-occurrence, and relation graphs, MEDIATOR collapses equivalent expressions while organizing distinct concepts in a medically meaningful discrete space. Used as the token interface of an EHR Transformer, MEDIATOR improves mean AUPR

---

### [183] Physical AI: Concepts, Techniques, and Challenges

**链接**: https://arxiv.org/abs/2610.27045
**作者**: Weinan Zhang, Chunhua Shen, Tianfan Xue, Bin Zhao, Bingqi Jiang, Zihan Guo 等 (10 人)
**来源**: cs.AI cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In recent years, physical artificial intelligence (physical AI) has experienced rapid development, capturing significant attention in academia and industry. However, the field has yet to reach consensus on its definition, technical landscape, and core challenges. To address this gap, this monograph seeks to define physical AI, present its technical landscape, and examine each key technical subfield in depth. In doing so, it establishes a unified framework for Physical AI: artificial systems that perceive, model, and act upon the physical world through continuous feedback under real-world constraints. Further, this monograph distinguishes physical AI from conventional digital AI, embodied AI, cyber-physical systems, and digital twins. It develops the foundations of physical AI across physics, control, cognition, learning, and reasoning. It reviews key methodologies, including multimodal perception, physical data and simulation, world models, embodied foundation models, motor-control sys

---

### [184] Turning TS2Vec into a Foundation Model for Time Series Classification

**链接**: https://arxiv.org/abs/2610.28602
**作者**: Vasilii Feofanov, Zhenghan Tai, Andrei Ermakov, Irina Rish
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> TS2Vec is one of the strongest self-supervised methods for time series classification, introduced in 2022. It is designed to be trained anew on every dataset: self-supervised pre-training followed by linear probing. Since then, the field has shifted towards foundation models that reuse one encoder across datasets. Yet TS2Vec offers a compact convolutional architecture that operates directly on temporal samples and accepts variable-length inputs without resampling. We ask whether these properties can be retained when the encoder is pre-trained only once, and show that they can: TS2Vec can essentially be turned into a foundation model. Three changes suffice: pre-train on a synthetic corpus, feed the encoder a raw amplitude view and an instance-normalized shape view of the input through two small stems, and distill one specialist encoder per view into a single encoder. The result, TS2Vec-FM, is a 1.6M-parameter dilated convolutional network that, kept frozen, reaches 83.3% on UCR-128 and 

---

### [185] Two Is Enough: Binary Classification Priors Suffice for Multi-Class In-Context Tabular Prediction

**链接**: https://arxiv.org/abs/2610.27569
**作者**: Zhixiong Cheng, Shiyuan Han, Jingjing Suo, Zhengli Wang
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models (TFMs) pretrain a transformer on large-scale synthetic priors so that a single forward pass yields zero-shot tabular prediction. TabICLv2 samples the class count of its classification prior during pretraining, and the prevailing configuration caps it at ten. We report a counter-intuitive result: setting this cap directly to two---making every pretrained classification task binary---still yields weights that perform zero-shot K-way classification 2. On the 38 TabArena classification datasets (200 bootstrap rounds, anchored at default RF = 1000), the binary two-stage recipe reaches 1590.1 Elo, above the official default at 1568.0 (+22.1), above TabPFN-v2.6 (1577.1) and RealTabPFN-v2.5 (1521.6). A production-scale validation on 60 real-world credit-scoring institutions independently confirms the direction: the same checkpoint improves test AUC on 44 of 60 institutions (paired Wilcoxon p = 0.0007 for AUC, p = 0.0002 for KS) at +1.5 inference cost. Mechanistically,

---

### [186] AdaptMIL: Domain Adaptation for Multiple Instance Learning in Digital Pathology

**链接**: https://arxiv.org/abs/2610.28007
**作者**: Ben Vardi, Dana Schonberger, Yuval Friedmann, Zohar Yakhini, Iris Barshack, Alexander Loebel 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models (PFMs) support a wide range of histopathology tasks on whole-slide images through multiple instance learning (MIL). Despite recent progress, these models remain sensitive to cross-hospital distribution shifts: performance often degrades when a task head (e.g., classification) is trained on data from one hospital and then used on data from another hospital. To address this challenge, we propose AdaptMIL, a training strategy for integrating domain adaptation into MIL training. AdaptMIL is motivated by our finding that directly applying domain adaptation objectives during MIL training can interfere with MIL aggregation learning, often resulting in performance degradation over standard training. AdaptMIL resolves this by decoupling representation-level domain alignment learning from MIL aggregation learning through a two-stage training procedure. We show that AdaptMIL improves cross-hospital performance and outperforms alternative adaptation methods across exper

---

### [187] Evaluating Social Reasoning in Embodied Vision-Language Models

**链接**: https://arxiv.org/abs/2610.27496
**作者**: Daniel Weiner and Raj Korpan
**来源**: cs.RO cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models now serve as reasoning layers for robot teams, but it remains unclear whether embodiment-specialized vision-language models (VLMs) preserve the social-reasoning capabilities of general-purpose VLMs. We evaluate Gemini Robotics-ER on SHREC, a benchmark of real human-robot social interactions, and compare it with published general-purpose VLM baselines. Robotics-ER outperforms GPT-4o-mini on error/competence detection but performs worse on detailed social-attribute judgments; adding a visual frame helps one task while hurting the other. These results suggest embodiment-specialized models may perform differently on social judgments that can be read more directly from observable interaction cues versus those requiring more inference about a person's internal state. Because the comparison spans model families, these differences cannot be attributed to embodiment specialization alone. This matters for multi-robot systems, where a shared foundation model could cause systemat

---

### [188] Exposing Vulnerability Monoculture Through Systemic Adversarial Robustness

**链接**: https://arxiv.org/abs/2610.27353
**作者**: Leo Elmecker-Plakolm, Lukasz Szpruch, Avishek Joey Bose, Matthew Wicker
**来源**: cs.CR cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Beneath the apparent diversity of foundation models lies an increasingly homogeneous technical stack of common training pipelines, distillation methods, and data. These shared algorithmic choices can expose an otherwise distinct model ecosystem to concentrated risks leading to a vulnerability monoculture. Yet current practice in assessing adversarial robustness is restricted to individual robustness scores and attack transfer rates, leaving open the unexplored fundamental question: how many attacks suffice for catastrophic widespread compromise? In this paper, we investigate the empirical nature of shared vulnerabilities within a model pool and introduce Systemic Adversarial Robustness (SAR), a novel measure of shared vulnerability of a model pool through the attack diversity needed to exploit it. Specifically, SAR interpolates between single-attack transferability and independent per-model robustness: small values reveal a vulnerability monoculture, whereas large values indicate that 

---

### [189] Ensemble-Aware Structural Encoding (EASE): Conditioning Protein Encoders on Peptide Conformational Ensembles

**链接**: https://arxiv.org/abs/2610.27638
**作者**: Ruoyao Zhang, Hongxuan Li, Jie Peng, Tianlong Chen
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Protein foundation models provide transferable representations for downstream peptide prediction tasks. However, existing representations typically reduce a peptide to a single sequence or structure, which may miss conformational variability relevant to key peptide properties, including antibacterial activity, hemolysis, toxicity, stability, and binding. For example, protease resistance correlates more strongly with conformational dynamics measured by hydrogen exchange than with average helicity. Therefore, we introduce Ensemble-Aware Structural Encoding (EASE), a framework for effectively extracting structural information from conformational ensembles for peptide representation. To extract useful information from noisy conformers, EASE selects central conformers representing a peptide's major structural states and fuses their individual representations with a permutation-invariant operator to produce a peptide-level representation for downstream prediction. We then evaluate our framew

---
