# 📑 论文索引 - 2026-11-21

共 141 篇论文

---

### [1] LLM Complexity: Towards a Computational Complexity View of Large Language Model Inference

**链接**: https://arxiv.org/abs/2611.24943
**作者**: Yu-Hung Wu, Shao-Xiang Yuan, Chan-Hung Yu, Zih-Ching Chen, Kuan-Hao Huang, Shao-Hua Sun
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Computational complexity theory offers a principled framework for characterizing the efficiency of computational problems, and Large Language Models (LLMs) can similarly be viewed as computational systems executing a structured process of input, inference-time compute, and output. In this context, the number of generated tokens emerges as a natural and directly observable proxy for inference-time compute. However, we show that the tempting analogy between LLM token length and classical time complexity does not hold. We disprove the hypothesis that inference-time token usage aligns monotonically with classical time complexity, demonstrating a fundamental divergence grounded in how LLMs actually allocate computation during inference. To this end, we introduce LLM Complexity, a new metric designed to quantify problem complexity from the perspective of LLMs by characterizing the area bounded above by the accuracy-token curve. We find that diverse LLMs induce highly consistent task rankings

---

### [2] Trace2ST: Recovering PLC Structured Text from I/O Traces with LLM Generation and Verification

**链接**: https://arxiv.org/abs/2611.24979
**作者**: Hsi Chang, Irfan Khan
**来源**: cs.SE cs.AI cs.CY cs.PL cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programmable logic controllers (PLCs), the industrial computers that operate power and process plants, often run programs whose source code is no longer available; however, every input and output of the controller is logged continuously. This paper therefore asks whether a large language model (LLM) can recover an executable program in Structured Text (ST), the standard PLC language of IEC 61131-3, from such input/output records (traces) alone and, equally important, how the recovered program can be verified. To answer this question, we build a generate-replay-feedback pipeline. First, the LLM writes a candidate program from a compressed summary of the trace, without ever seeing the original program. The candidate is then executed one control cycle (scan) at a time and compared with the recording, and whenever a mismatch occurs the corresponding part of the trace is returned to the LLM, for at most three revisions. Because every result depends on the software that executes the candidat

---

### [3] ForeSeek: Foresight-Driven Reasoning for Long-Form Video Understanding

**链接**: https://arxiv.org/abs/2611.26024
**作者**: Yuchen Sun, Siyuan Cheng, Shi-Zhe Chen, Yixin Qin, Jinwen Luo, Zheng Wei
**来源**: cs.AI
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-form video understanding, as a fundamental yet crucial vision task, is being revolutionized by multimodal large language model (MLLM)-based video agents. However, the retrieval-driven nature inherent to these agents creates a significant bottleneck, forcing them to reactively fetch clips based on local saliency without a global temporal plan. To address this, we present ForeSeek, a foresight-driven video agent that transforms long-video reasoning from reactive retrieval into predictive exploration. Rather than blindly probing the timeline, ForeSeek forms visually grounded expectations over unseen temporal regions, verifies them through targeted observations, and continuously refines its search based on emerging evidence, where failed expectations serve as informative signals for principled backtracking. Furthermore, we develop a two-stage training framework that equips MLLMs with foresight-guided reasoning and efficient decision making. Extensive experiments on five long-video ben

---

### [4] From Sessions to Serving: Integrating LLM-Based Embeddings into Retrieval for Production Content Recommendation

**链接**: https://arxiv.org/abs/2611.26096
**作者**: Zhixiong Hu, Meng Li, Maggie Zhang, Deborshi Goswami, David Bailey, James Bradley
**来源**: cs.IR cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized content recommendation on large marketplace websites must reconcile heterogeneous candidate content (e.g., customer stories, product pages, industry pages, and learning content) with sparse, fast-changing user behavior, placing increasing demands on the retrieval stage to represent user interest well, not just the downstream ranking stage. We present LSER (LLM Session Embedding Retrieval), a production content recommendation system for autodesk.com that derives session- and history-level embeddings from a pretrained large language model (LLM) and adds them as auxiliary user-side features in the retrieval-stage user tower alongside existing learned sequence encoders. To keep user-side embeddings fresh under real-time behavior, we build a nearline serving path that asynchronously refreshes sequential and LLM-derived user vectors for our main content recommendation server. We validate the incremental value of the LLM features through an ablation study across our full multi-co

---

### [5] Anchor and Check: Deterministic Cross-Prompt, Cross-Model Reconciliation for Auditable LLM Decisions

**链接**: https://arxiv.org/abs/2611.25818
**作者**: Sivakameswara Reddy Chejarla
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pipelines that let a large language model (LLM) make discrete decisions need to know which decisions they may act on unattended, and a record that explains each one. We study a small, fully specified reconciliation contract: commit the target model's greedy answer (the anchor), draw one or two greedy checks that reach the answer by a different route (an alternate prompt, or a model from another family), and let a pure function return one of five outcomes, of which only Agree is acted on. On 48,000 model-item evaluations over 6,000 questions, with every method given access to verbalized confidence as a tie-breaker, the main finding concerns where calls come from: pooling another family's samples raises semantic entropy's AUROC by 1.7 to 4.0 points at every budget, and a same-model temperature check is the weakest design. As complete pipelines, the point estimates of the three-call contract and pooled semantic entropy over 3 or 5 samples differ by less than one point, with intervals cont

---

### [6] Incorporating argumentation frameworks for LLM decision-making: Task-specific design and evaluation

**链接**: https://arxiv.org/abs/2611.25361
**作者**: Bochen Han, Anshu Xiong, Mingyang Ma
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Argumentation frameworks (AFs) provide explicit, formal mechanisms for representing and resolving conflicts and thus have been incorporated into large language model (LLM) decision-making. The benefits vary and depend on how arguments and their relations are constructed, evaluated, and incorporated into the decision process. {We abstract a workflow consisting of four stages based on existing argumentation-augmented methods} and investigate their design choices over tasks of debate-based decision-making and retrieval-based fact verification. Our evaluation with recent LLMs shows that existing methods do not consistently improve performance across the considered tasks. Motivated by this observation, we develop two task-specific methods. The first is called Qnt-Arg, which organizes arguments around the original speakers in debate materials and aggregates model-estimated argument strengths and candidate-answer priors under gradual semantics. The second is Qlt-Arg that uses credibility esti

---

### [7] MultiBinder: Preventing Multi-Subject Identity Leakage in Personalized Video Generation

**链接**: https://arxiv.org/abs/2611.26164
**作者**: Wei Li, Yiheng Zhang, Zhaofan Qiu, Ting Yao, Xiaoyan Sun, Tao Mei
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized video generation faces a significant scalability challenge: as the number of custom subjects increases, existing methods suffer from severe identity leakage and semantic entanglement, resulting in videos with blended attributes and incoherent narratives. We identify that this stems from a lack of explicit binding between textual entity phrases and their corresponding visual patterns prior to fusion in diffusion models. To address this, we propose MultiBinder, a novel framework built on a ``bind-then-narrate'' paradigm. Our approach introduces a two-stage conditioning process before video diffusion. First, Cross-modal Entity Binding devises an entity-aware Q-Former to extract identity-centric features from each subject's reference image and tightly align them with its unique entity phrase, yielding disentangled ``identity tokens.'' Second, a Multimodal Large Language Model (MLLM) acts as a ``narrative director'' in the Narrative-Aware Subject Arrangement stage, capturing th

---

### [8] DriftGuard: Online Memory-Drift Detection via Causal Attribution for LLM Agents

**链接**: https://arxiv.org/abs/2611.25583
**作者**: Licheng Pan, Yuzhou Chen, Zhixuan Chu, Yichen Sun, Han Zheng, Zhiyu Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents rely on persistent memory to plan tool calls and complete multi-step tasks, which exposes them to memory drift: an adversarial or misleading memory alters the execution path and final outcome. In this work, we investigate online memory-drift detection, which estimates each retrieved memory's causal contribution to potential drift at serving time. We identify two fundamental challenges. (1) Content-level features are insufficient for causal memory-drift attribution, as perplexity or retrieval relevance alone cannot determine which retrieved memory would change agent behavior if neutralized; (2) Counterfactual attribution is prohibitively expensive for online detection, as it requires replaying downstream agent and tool execution for each candidate memory, exceeding real-time serving budgets. To address these challenges, we propose DriftGuard, a two-stage framework that decouples offline causal supervision from online estimation. Specifically, DriftGuard

---

### [9] Sightline: Calibrated Data-Flow Summaries for LLM-Integrated Applications

**链接**: https://arxiv.org/abs/2611.26221
**作者**: Zihao Xu, Yuekang Li, Ruitao Feng, Haifeng Shen
**来源**: cs.PL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programs increasingly call large language models (LLMs), filling prompt placeholders with program values and consuming the output. Such a call crosses the boundary between natural language and programming language (NL/PL). To follow data across it, an analysis needs a data-flow summary of which placeholders the output uses, but no code describes what the model does. Analyses of these LLM-integrated applications therefore taint every output with every input, creating spurious flows, or ask a second model to label each call, which is costly. We prove, and mechanize in Lean 4, that a placeholder flows to the output of a transformer, to first order, only through the attention that reads it (no reading, no flow), and that a faint reading or sensitivity cannot certify that a placeholder does not flow. Unlike reading, the log-probability gradients and Fisher signals of existing methods vanish on confident outputs, and single-span removal fails on duplicated content. Our tool, Sightline, reads

---

### [10] Blind Spots Travel, Knowledge Stays Home: What RL Inherits from an LLM Judge

**链接**: https://arxiv.org/abs/2611.25191
**作者**: Liang Yue, Eric A. Vance
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM judges serve as rewards where no answer key exists, in the hope that their knowledge passes to the trained model. In 814 RL runs that teach 7-8B models to answer closed-book questions or abstain, we ask what passes. What a grader knows about single answers stays home. A wrong answer that a judge rewards is memorised for that one question. A model trained with the answer key, or with a far stronger judge, chooses which new questions to answer no better than the untrained model does by sampling 32 answers and abstaining where they disagree; the grader's knowledge adds about one corrected answer per hundred questions. What a grader believes about a kind of question travels. A judge that rejects eleven of the twelve correct training answers about capitals of former states teaches the model to refuse 98% of such capitals on new questions, a loss that accuracy and abstention rates do not reveal. Changing only those twelve verdicts by hand moves the refusal from 5% to 90%, even for a grad

---

### [11] Characterizing High Bandwidth Flash for LLM Serving

**链接**: https://arxiv.org/abs/2609.39131
**作者**: Zack Yu, Chloe Wong, Coleman Hooper, Minjae Lee, Wonjun Kang, Youngjin Cho 等 (10 人)
**来源**: cs.LG cs.AR cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [12] LLM GerryMandering: Separating Interactions from Additive Effects in LLM Audits

**链接**: https://arxiv.org/abs/2611.26538
**作者**: George Rahul, Ronit Jahilal, Bhaskara Hanuma Vedula, Ponnurangam Kumaraguru, Pushkar Shukla
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Intersectional bias arises when a model treats people who hold several marginalised identities at once differently from what their separate identities would predict. Auditing such intersectional subgroups remains a challenge: their number grows quadratically, and there is no agreed baseline for what independent attributes would predict. Without such a baseline, many existing audits flag a subgroup when it exceeds each attribute alone, a condition that attributes acting independently already satisfy. We test this standard criterion on 150 synthetic datasets built with no interaction. With the shuffle null, it flags 66.1 false subgroups per dataset on average, and at least one in every dataset. When we plant interactions of known size into these datasets, a repaired null lets the criterion recover only 32% of them. We introduce ADDIS (Additive Intersectional Screen), which fits an additive model over all attributes, scores each subgroup by its Additive Residual Distance (ARD) from that m

---

### [13] Robust LLM Evaluation with Boundedly Bad Judges: A Constrained Maximum Likelihood Approach

**链接**: https://arxiv.org/abs/2604.03257
**作者**: Minghe Shen, Ananth Balashankar, Adam Fisch, David Madras, Miguel Rodrigues
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [14] OceanCoder: A Verification-Guided Large Language Model for Automated Simulation Modelling in Ocean Engineering

**链接**: https://arxiv.org/abs/2611.26333
**作者**: Can Xue, Changhong He, Ziyi Sun, Anliang Ge, Shimin Yu, Bingchen Liang
**来源**: cs.LG cs.SE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Numerical simulation is important in ocean engineering, but model construction requires expert knowledge. Large language models support automated modelling, but code syntax and successful execution alone do not establish whether generated models and results meet engineering requirements. We present OceanCoder, a Qwen3-8B-based large language model for automated simulation modelling in ocean engineering. To address specialised programming requirements and scarce training data, we develop an extensible data construction pipeline producing 12,000 verified supervised fine-tuning (SFT) examples across 12 engineering task categories. A three-layer verification framework checks model inputs against engineering parameters and task constraints, verifies completion of required simulation analyses, and assesses the engineering plausibility of computed outputs. Its outcomes provide graded rewards for group relative policy optimisation (GRPO), guiding the model towards engineering task completion. 

---

### [15] NL2AGBench: Benchmarking LLM Auto-Formalization for AlphaGeometry

**链接**: https://arxiv.org/abs/2608.28481
**作者**: Samuel Xiao, Judy Song, Rory Hu, Ziliang Zong
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] Verify the Verifier: Specification-Grounded LLM Cross-Checking for Bugs That Escape UVM Scoreboards

**链接**: https://arxiv.org/abs/2611.26588
**作者**: Ana E. Sanchez Villalobos, Michael D. Quinn, Aakash Tyagi, Minh D. Luu, David Kebo Houngninou
**来源**: cs.SE cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A passing UVM regression shows the design agrees with the reference model on what the scoreboard checks, not that it meets the specification. Bugs that pass every test yet violate the specification, termed scoreboard escapes, survive mature testbenches. We present Verify the Verifier, to our knowledge the first framework whose LLM-based Anomaly Cross-Checker examines a passing regression's traces against the specification. Of 564 bugs inserted into four OpenTitan IPs, 68 are candidate scoreboard escapes: non-equivalent, exercised by the tests, yet passing. The framework confirmed 41 as scoreboard escapes with assertions failing on the buggy design and proven on the original.

---

### [17] The Real Cost of Context: Predicting Compute Time and Energy Consumption in LLM Prefill and Decode Phases

**链接**: https://arxiv.org/abs/2610.39621
**作者**: Lars Krupp, Daniel Gei{\ss}ler, Francisco M. Calatrava-Nicolas, Stefan Gerd Fritsch, Paul Lukowicz, Jakob Karolus
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] SoK: Assessing the Evolution of LLM Capability in Software Vulnerability Research

**链接**: https://arxiv.org/abs/2611.26601
**作者**: Amine Lbath, Manan Suri, Aurelien Delaitre, Vadim Okun, Massih-Reza Amini, Dinesh Manocha
**来源**: cs.CR cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are becoming increasingly capable at discovering, validating and patching vulnerabilities in real software, and vendors and researchers report that this is already changing how vulnerabilities are found and fixed. These claims, however, are scattered across papers, vendor reports and disclosures and are rarely comparable. We introduce a framework that rates these capabilities on an autonomy scale modeled on the levels of driving automation, and qualifies each claim by its correctness, its availability and the strength of its evidence. We use this framework to systematize the published evidence on LLM capability in vulnerability research. We find that agents discovered, validated, and patched vulnerabilities in real-world software without human intervention before the restricted frontier models of 2026, and that open-weight models subsequently attained comparable autonomy for discovery and validation. We then measure the consequences of evolving LLM security capabilitie

---

### [19] The Coverage Selection Gap: Ranking, Not Generation, Limits LLM Rubric Construction

**链接**: https://arxiv.org/abs/2611.25557
**作者**: Ali Karkehabadi, Jamshid Hassanpour, Rafael E. Banchs
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Task-specific rubrics are increasingly used to evaluate open-ended language-model outputs, yet constructing comprehensive evaluation criteria from complex source documents remains challenging. We study automatic rubric construction in professional mergers and acquisitions (M&A) due diligence, where evaluation criteria must be inferred from task instructions and supporting documents without access to an expert-authored reference rubric. We introduce a multi-axis generation framework that explores complementary structural and free-form views of the source evidence to construct a broad pool of candidate evaluation criteria. To distinguish failures of criterion discovery from failures of candidate selection, we introduce the coverage-selection gap, which measures the difference between reference-free ranking and a reference-informed greedy diagnostic under a fixed selection budget. Developed on 16 tasks and evaluated on four held-out tasks, our framework achieves 0.876 macro recall against

---

### [20] HapBO: Harnessed $\alpha$-$\pi$ Bayesian Optimization via Expert Natural Language Priors

**链接**: https://arxiv.org/abs/2611.25100
**作者**: Jean-S\'ebastien Giroux, Rose Guay Hottin, Marco Bonizzato
**来源**: cs.LG stat.ML
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bayesian Optimization (BO) can be substantially more sample-efficient when informed by prior knowledge about the problem. In practice, however, such knowledge is often available only in natural language, e.g., expert intuitions or documentation, rather than as the explicit probability distribution landscape that prior-guided BO methods may require. Leveraging it effectively demands both an expressive mapping from language to priors and robustness to information that may be misleading. We propose HapBO (Harnessed $\alpha$-$\pi$ Bayesian Optimization), which elicits beliefs once from a human expert, a large language model (LLM), or both, and deterministically compiles a structured specification into a reusable belief function ($\pi: \mathcal{X} \to[0,1]$), with a rich representation not restricted to a Gaussian family. Building on $\alpha$-$\pi$BO, HapBO applies this belief function through a bounded positive multiplier on any nonnegative acquisition, preserving positive acquisition supp

---

### [21] A Statistical Framework for Training Data Auditing of Large Language Models

**链接**: https://arxiv.org/abs/2611.26264
**作者**: Shengjie Niu, Yeheng Ge, Jian Huang
**来源**: stat.ML cs.LG stat.AP
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Training-data auditing asks whether data of interest were used to train a large language model (LLM), a question central to privacy auditing, copyright protection, and benchmark-contamination detection. These concerns are particularly relevant to the use of copyrighted books and scientific papers in pre-training, as well as synthetic text and medical question-answer records in fine-tuning. In practice, training membership signals may be concentrated in only a few passages of a long document, making it important to aggregate evidence within each document without diluting these localized signals. Beyond individual documents, auditing a target collection requires an overall assessment based on the document-level evidence. In this paper, we propose a unified statistical framework for document-level membership inference, target-collection global auditing, and suspicious-subset identification. We integrate complementary chunk-level membership evidence with Cauchy combination to construct doc

---

### [22] Forget Freely, Grep Later: Lossless, Index-Free Memory for Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2611.25123
**作者**: Ziyan Yang, Taiwei Shi, Jieyu Zhao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents often exceed their context windows, forcing them to discard information that may be needed later. Existing context management strategies rely on summarization, masking, or structured memory, requiring decisions about what to preserve or how to retrieve it before future needs are known. However, these methods can introduce lossy compression, potentially discarding details needed for future tasks. To address this limitation, we introduce GrepMem, a simple, lossless, and index-free memory mechanism built on two components: an append-only plain-text log of the agent's complete history and a regular-expression search tool for on-demand recall. Unlike structured memory systems, GrepMem requires no embeddings, retrieval index, memory extraction, or additional models. We train Qwen3.5-9B with reinforcement learning under five context management strategies and evaluate on multi-question research sessions, long-stream recall, and agent-trajectory question answering. GrepM

---

### [23] Context--Answer Metamodels: Forecasting LLM Activations Before the First Answer Token

**链接**: https://arxiv.org/abs/2611.06837
**作者**: Tommy He, Thomas Jiralerspong
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [24] AltRA-Test: An Alternative Annotator Test for LLM Judges Without Shared Annotators

**链接**: https://arxiv.org/abs/2611.26073
**作者**: Nagham Omar, Rotem Dror, Almog Gueta, Avigdor Gal, Roi Reichart, Nitay Calderon
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as judges and graders to replace human annotators, raising the question of when such replacement is statistically justified. To support such decisions, the Alternative Annotator Test (Alt-Test) was introduced for dense settings where all items are annotated by the same annotators. However, in many large-scale annotation settings, items are annotated by different subsets of annotators. We therefore propose the Alternative Annotator Test with Resampled Annotations (AltRA-Test), a statistical test that does not require that all items are annotated by the same annotators. AltRA-Test uses a bootstrap that resamples items, draws k human annotations for each item, and substitutes one of them with an LLM annotation. This produces paired all-human and mixed human-LLM panels. A replacement is supported when the inter-annotator agreement (IAA) of the mixed panel is statistically non-inferior to the IAA of the all-human panel, i.e., when the LLM p

---

### [25] CoMPASS: A Multi-Turn Benchmark for Measuring LLM Reinforcement of Parasocial Behavior

**链接**: https://arxiv.org/abs/2611.25109
**作者**: Shwetanshu Singh, Mark Keavney, Mathieu Duteil, Meriem Mehri, Scott Blain
**来源**: cs.AI cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Users of conversational LLMs sometimes anthropomorphize these systems, form emotional attachments to them, and become dependent on them. This behavior, known as parasocial attachment, has been linked to multiple documented fatalities. However, public benchmarks for measuring whether LLMs reinforce users' parasocial attachment are lacking: existing work is single-turn, post hoc observational, or focused on extreme user states such as psychosis. We introduce CoMPASS, a multi-turn benchmark for measuring whether LLMs reinforce or resist users' gradually escalating parasocial attachment. CoMPASS is grounded in attachment theory and includes four user personas, three independent escalation dimensions (anthropomorphism, attachment, dependency) applied singly and in combination against a matched control, and a seven-signal scoring rubric. We report results for eight frontier models from four providers and observe that under our primary judge, multi-turn escalation raises parasocial behavior o

---

### [26] Same Judgement, Different Scores: Numerical Scoring Topology in LLM-as-a-Judge Evaluation

**链接**: https://arxiv.org/abs/2611.26077
**作者**: Doyun Kim, Chanwoo Kim, Jiwoo Kum, Minsoo Song, Chanjun Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs are increasingly used as automated evaluators to reduce the cost and time required for human annotation. However, the role of scoring-scheme design in the reliability of LLM-as-a-Judge evaluation remains underexplored. To address this problem, we introduce numerical scoring topology, which characterizes the structural design of a scoring scheme in terms of its scale width, granularity, offset, symmetry, and boundary placement. Building on this definition, we conduct the first systematic study of how numerical scoring topology influences zero-shot LLM-as-a-Judge evaluation across diverse benchmarks and judge models. Our results show that numerical scoring topology systematically affects judge scores, calibration, and robustness, particularly in judgment-intensive evaluations. Shifted and narrow ranges tend to induce some of the largest score deviations across many settings. We further find that stronger and larger judge models generally achieve higher discriminative validity and gr

---

### [27] Splice-Core: Low-Order-Bit-Splicing GEMM for Highly Energy-Efficient AI Inference Accelerators

**链接**: https://arxiv.org/abs/2611.25617
**作者**: Prabhu Vellaisamy, Hsien-Fu Hung, Andrew Kim, Shawn Blanton, John Paul Shen
**来源**: cs.AR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Splice-Core is a temporal-unary/binary (tub) hybrid general matrix multiplication (GEMM) unit that minimizes low-order accumulation latency, while retaining value-dependent execution for high-order activation bits. We present two novel processing element (PE) variants: (i) Splice-BP utilizing bit planes, and (ii) Splice-LUT, which selects a shared weight multiple in a single cycle. Compared to a binary systolic array, Splice-BP/Splice-LUT achieve 77.4%/76.4% geometric-mean tile energy reductions, respectively, across 26 INT4 convolutional neural network (CNN) and large language model (LLM) workloads in 45nm. Splice-LUT further increases geometric-mean tile throughput by 44.4% and reduces geometric-mean energy-delay product (EDP) by 6.13x across the 26 configurations. Across the evaluated W8A8 convolution and expert-projection workloads, Splice-BP and Splice-LUT reduce tile energy by 77.3-88.1%. Post-place-and-route INT4 yields 14%/9% smaller area for Splice-BP/Splice-LUT, compared to t

---

### [28] RoCoKV: Accelerating LLM Inference Serving through Uncertainty and Redundancy Aware KV Cache Compression

**链接**: https://arxiv.org/abs/2611.25433
**作者**: Payman Behnam, Elaheh Sobhani, Saad Amin, Yahya Hassan, Daniyal Khan, Biswadeep Chakraborty 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> KV cache compression is critical for large reasoning models, where most of the cost comes from long generated reasoning traces rather than the input prompt. These traces often contain redundant and low-utility tokens due to looping, self-verification, and corrections. However, such tokens may still receive high attention scores, making it difficult to remove them without harming the reasoning process. We propose RoCoKV, a KV cache compression method designed for large reasoning models. RoCoKV introduces two key components. First, uncertainty-guided adaptive pruning adjusts the compression strength based on the model's confidence, allocating more memory during uncertain phases and applying stronger pruning when the model is confident. Second, redundancy-aware token selection reduces the impact of tokens that are highly similar to recent reasoning content, encouraging the model to retain more informative and diverse tokens. Beyond the algorithm, we co-design RoCoKV with the serving stack

---

### [29] LLM-Based Threat Detection and Prevention Framework for IoT Ecosystems

**链接**: https://arxiv.org/abs/2505.00240
**作者**: Yazan Otoum, Arghavan Asad, Ishtiaq Ahmad, Amiya Nayak
**来源**: cs.CR cs.AI cs.ET cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] Rubric Semantics or Numerical Priors? Auditing Scale-Direction Bias in LLM Judges

**链接**: https://arxiv.org/abs/2611.25588
**作者**: Chanwoo Kim, Doyun Kim, Minsoo Song, Sihyeon Lee, Chanjun Park
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent benchmark evaluations increasingly rely on Large Language Models (LLMs) as automatic judges. This paradigm assumes LLMs evaluate based on the rubric's semantic meaning rather than its numeric scale. We question this assumption by introducing semantic faithfulness: the principle that semantically equivalent rubrics must yield consistent scores. To quantify this, we propose a scale-reversal probe that inverts score anchors without altering evaluation criteria. Furthermore, we introduce floor normalization to calibrate reversal disagreement against intrinsic model variability, enabling fair cross-model comparisons. Experiments across five meta-evaluation benchmarks with seven diverse LLM judges spanning open-weight and proprietary models reveal widespread violations of semantic faithfulness, showing that raw reversal agreement alone is misleading. Finally, we demonstrate that bidirectional anchor averaging reduces dependence on any single anchor direction without compromising align

---

### [31] Design and Evaluation of Epira: An Automated Interview System for Case Investigation and Contact Tracing

**链接**: https://arxiv.org/abs/2611.25577
**作者**: Ishita Asnani, Shaghayegh Fazliani, Zachary Ryan, Kriyoshig Prasai, Chirag Kumar, Indra Gonzalez Ojeda 等 (8 人)
**来源**: cs.LG cs.HC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: Case investigation and contact tracing are labor-intensive. Web forms struggle when respondents need clarification before disclosing contacts, and open-ended chatbots may deviate from protocols. We developed and evaluated Epira, a protocol-controlled large language model (LLM) interviewer for multi-disease case investigation and contact tracing. Materials and Methods: Epira pairs LLM dialogue with a rule-based controller enforcing required questions, safety handoffs, and a structured case record, and adapts to new diseases by questionnaire upload. Local (Qwen2.5) and cloud (GPT-5.4) backends were tested. Study 1 used 108 simulated cases with ground-truth fields and contacts for measles and gonorrhea under Epira and open-ended conditions (864 sessions). Study 2 enrolled 72 volunteers in a 2$\times$2 disease-by-model interview assessing completion, usability, acceptability, and trust. Results: Across Study 1, Epira with a local LLM captured 88.9% of required fields and 60.1% o

---

### [32] HireWatch: Evaluating LLM Compliance with U.S. Employment Law Under Contextual Pressure

**链接**: https://arxiv.org/abs/2611.24970
**作者**: Huy Nghiem, Maria Kostylew, Noam Kolt
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The deployment of large language models (LLMs) in hiring pipelines is growing, yet existing evaluations generally overlook their compliance with legal rules. To fill this gap, we introduce HireWatch, an evaluation that assesses whether LLMs comply with U.S. laws that govern the questions that job candidates may be asked. We construct a 200-item bank of lawful and unlawful interview questions, whose legal classification is based on U.S. federal statutes, regulations, and agency guidance. We instruct LLMs to select questions from this bank in preparing for job interviews, across a set of various occupations and contexts, and report the fraction of unlawful questions that LLMs select. Evaluation of 18 closed and open-weight LLMs across ~100,000 trials under different types of contextual pressure reveals that LLMs' legal compliance is brittle. While LLMs generally avoid selecting unlawful questions in low-pressure contexts, legal violations increase sharply under higher pressure. Explicit 

---

### [33] One Framework to Diagnose Them All: A Stratified Benchmark for Bengali LLM Hallucination

**链接**: https://arxiv.org/abs/2611.26336
**作者**: Asif Shahriyar Sushmit, Shefayat E Shams Adib, Abdullah Al Jubaer Gem, Ahmed Shafin Ruhan, MD. Nazmuddoha Ansary, Biplab Kumar Sarkar 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hallucination research in low-resource languages fragments easily: each newly named failure mode prompts its own dataset, spending scarce annotators on incomparable resources. We argue for consolidation and test it at community scale. Alikbachan is a Bengali hallucination-detection benchmark stratified along three crossed axes: a human-validated cultural-distance band, six task types, and a five-family, 32-mode hallucination taxonomy. It comprises a harvested 2,516-item test set (Phase 1) and a quota-constructed, gold-labeled 5,000-item set (Phase 2). The stratification is diagnostic. Four zero-shot LLM judges vary by over 30 macro-F1 points across strata, and the item-level predictions of 99 Phase-1 and 32 Phase-2 competition systems reproduce the profile: discourse-level omission defeats judges and most teams alike, whereas only a minority over-flag negative controls. The judges' verdict probabilities rank items well (ROC-AUC 0.74-0.95) but are overconfident (ECE 0.04-0.29). An open 

---

### [34] Training Vision Models for LLM-Driven Weight-Space Programming

**链接**: https://arxiv.org/abs/2611.26408
**作者**: Timo Ropinski, Sebastian Kranz
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> It has been demonstrated that, in certain settings, large language models can perform weight-space programming to directly modify the weights of neural networks. However, it is unknown how dedicated training of these networks can contribute to the successes of weight-space programming. We present a benchmark of LLM-driven weight-space programming on vision models, in which five LLMs edit convolutional networks and vision transformers on relabeling and error-correction tasks on Waterbirds, CIFAR-100, PACS and Entity-30. We report more than 2,600 such edit processes, whereby each edit is scored on held-out images for success, side effects and accuracy loss. We compare standard training with label smoothing, gradient-based editable training, and our Edit-Ready Training (ERT), a novel method that rehearses the direct, closed-form weight edits LLMs perform. We show that preparing networks for editing raises the success of LLM edits substantially where standard networks are hard to edit. ERT

---

### [35] Multimodal Error Detection in Chest X-ray Reports: A Large Language Model Reading Image Evidence

**链接**: https://arxiv.org/abs/2611.26492
**作者**: Yanda Cheng, Bo Wen, Yuhao Lu
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rad-Linter checks chest X-ray reports against image-derived evidence to flag potential errors for review. A pretrained image classifier supplies scores for nine pathologies, and a 1.5B-parameter language model, fine-tuned with LoRA on 1,816 examples, checks their consistency with the report. We compare it with a keyword-and-negation rule baseline given the same reports and scores. Evaluation uses controlled report-score pairings from OpenI, with consistency labels derived from automatic report labels and score thresholds. Each counterfactual quad crosses two real reports with two real score vectors from other patients, creating two consistent and two inconsistent pairs. Every report and score vector occurs in both conditions, so either input alone permits only 50% accuracy. On 131 quads, Rad-Linter achieves 98.5% pair accuracy versus 80.5% for the rule baseline, and classifies all four pairs correctly in 94.4% of quads versus 56.5%. The checkers perform similarly on omission items, inc

---

### [36] Decision-Focused Reinforcement Learning for LLM Post-Training

**链接**: https://arxiv.org/abs/2611.25597
**作者**: Haotian Zhai, Leqi Liu
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown promise as predictors across various tasks, benefiting from their ability to use information from unstructured context. However, when predictions serve as parameters of downstream optimization problems, higher prediction accuracy does not necessarily translate into lower decision costs. We propose decision-focused reinforcement learning (DFRL), a framework for post-training LLMs to predict optimization parameters using negative downstream decision regret as reward. DFRL trains LLM predictors to minimize the costs of the decisions induced by their predictions, without requiring downstream convexity or differentiability, and integrates readily into existing RL post-training frameworks. To address expensive reward evaluation, we develop two approaches. Heuristic warm-starting uses inexpensive approximate rewards during an initial phase before switching to refinement with exact rewards. Reward correction combines inexpensive estimates with randomized

---

### [37] Joint Language Modeling for In-the-Wild Speech-Scene Generation with Distinct Token Representations

**链接**: https://arxiv.org/abs/2611.25503
**作者**: Semin Kim, Ju Yeon Kang, Sunghwan Ahn, Seonuk Kim, Nam Soo Kim
**来源**: eess.AS cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech-scene generation aims to synthesize intelligible target speech together with diverse environmental sounds as a coherent acoustic scene. The task is considered challenging in two respects. Speech and environmental audio differ substantially in their semantic and acoustic characteristics, yet existing approaches typically model the complete scene using a single mixed acoustic representation. At the same time, the two sounds are closely related in real-world speech scenes, whereas conventional approaches usually rely on simulated scenes mixed from independently recorded sources. We propose a large language model (LLM)-based framework for joint modeling of distinct speech and environment token streams. A source-aware neural audio codec extracts temporally aligned speech and environment tokens from mixed audio, and a pretrained LLM generates both token streams in an interleaved fashion conditioned on the natural-language scene description and speech content. This formulation preserve

---

### [38] Can an LLM Fix a Language Model Without Training It?

**链接**: https://arxiv.org/abs/2611.25613
**作者**: Bharath Kumar Bolla, Raghavender Surya Upadhayula, Vishnu Surya Reddy Nandi, Ramesh Nandipalli
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Although an external language model can select and test repairs to another model's weights, behavior can also be recovered through fixed numerical edits. We assessed the value of interactive selection in a controlled study of Transformer repair. After inspecting predictions, activation summaries, and weight statistics, the editor selects projection recipes to apply to the target without gradient updates. We analyzed 20 recorded sessions involving five masked and causal language models, comparing the selected edits with fixed projections, scripted and matched-budget black-box search, and low-rank adaptation. Under the core two-layer fault, live selection matches black-box search on SmolLM2 and Qwen2.5. For Pythia, live selection achieves 65.62% completion accuracy, compared with 0% for black-box search and 66.15% for a fixed projection. Under a separate compound fault affecting attention and feed-forward weights, both scripted and LLM-guided selection increase the descriptive five-check

---

### [39] SGLayout: Schema-Guided Closed-Loop Refinement for LLM-Driven Parameterized Layout Generation

**链接**: https://arxiv.org/abs/2611.25410
**作者**: Siyang Chen, Yuan Pu, Yuhan Qin, Zhaotan Lin, Siyuan Liang, Zhuolun He 等 (8 人)
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown strong potential in parameterized layout generation via tool-augmented code synthesis. However, LLMs lack spatial awareness, making one-shot generation unreliable. While layout quality can be evaluated with established techniques, a critical gap remains: geometric-domain evaluation outcomes cannot be directly translated into actionable code-level fixes, trapping iterative refinement in blind refactoring. We propose SGLayout, a self-refining framework that closes this gap via a schema-guided mechanism. Upon code execution, a structured schema captures the correspondence between each code-level instance and its geometric attributes, establishing a bidirectional link between code space and geometry space. Emulating engineer review practices, SGLayout evaluates layouts along two complementary dimensions: intent compliance through quantitative structural checking and qualitative vision-language assessment, and rule compliance through DRC. All identifi

---

### [40] Efficient and Robust Drafting with Multi-Token Prediction

**链接**: https://arxiv.org/abs/2611.25813
**作者**: Filippo Galgani, Ziwei Ji, Omri Homburger, Ganesh Jawahar, Michelle Ramanovich, Ivan Korotkov 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding has emerged as a critical technique for accelerating Large Language Model (LLM) inference by decoupling generation into a drafting phase and a parallel verification phase. A crucial challenge is therefore designing a drafter that is both lightweight and accurate enough to approximate the predictions of the target model. We present a highly optimized Multi-Token Prediction (MTP) architecture that extends existing backbone LLMs to efficiently produce high-quality drafts. Built around a single shared drafting head, our approach features three core architectural optimizations: target activation injection to anchor semantic planning, zero-copy KV-cache cross-attention to bypass prefill compute and reduce memory overhead, and an efficient clustered vocabulary projection to reduce the cost of full-vocabulary decoding. Testing these improvements with the Gemma 4 model family, our G-MTP shows out-of-the-box speedups for both large server-side setups (up to 3.1$\times$) and 

---

### [41] An LLM-Agentic Framework for Intelligent Work Order Management in Industrial Maintenance

**链接**: https://arxiv.org/abs/2611.25070
**作者**: Nianjun Zhou and Dhaval Patel
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents an AI-driven framework, CodeReAct agent, designed to enhance industrial equipment maintenance through natural language (NL) interactions. The framework employs an advanced AI agentic approach to interpret human instructions, providing knowledge extraction, asset status summarization, and work order recommendations. It identifies patterns and trends and predicts work orders by standardizing industrial data into business objects (BOs) and utilizing analytical function API calls. The AI agent operates through a Thought-Action-Observation process similar to human problem-solving, automating complex analytical tasks typically performed by data scientists. Notably, the Action phase generates executable code, replacing manual coding efforts. A case study focusing on chiller maintenance demonstrates the framework's capability to analyze multiple years of work orders, and alerts and anomalies are presented. The results indicate that the AI agent framework effectively process

---

### [42] Complete-SVD: A Functional Norm Approach to Low-Rank LLM Compression

**链接**: https://arxiv.org/abs/2611.26059
**作者**: Alper Kalle, Theo Rudkiewicz, Mohamed-Oumar Ouerfelli, Mohamed Tamaazousti
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-training low-rank compression of neural networks must not only approximate the original weights but also preserve the model's input-output behavior. Recent output-aware methods measure the compression error beyond the compressed layer, at the model output, weighting logit changes by the observed next token or by the model's predicted probabilities. We propose Complete-SVD, a method for large language models that minimizes the $L_2$ distance between the logits of the original and compressed models, weighting all logit changes equally. Linearizing the network around the original weights, together with a Kronecker-factored approximation, reduces this objective to a weighted SVD with a closed-form solution. Its output-side factor is intractable to compute; we estimate it without bias from random probes, at a cost of $K$ backward passes per sequence, independent of vocabulary size and sequence length. At matched settings with uniform ranks and WikiText-2 calibration, Complete-SVD achie

---

### [43] xAppGen: LLM-driven Natural Language Programming for Agile xApp Development

**链接**: https://arxiv.org/abs/2603.18604
**作者**: Xin Li, Shiming Yu, Leming Shen, Jianing Zhang, Yuanqing Zheng, and Yaxiong Xie
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [44] Ask in the Crowd: Differentially Private LLM Inference via Dummy-Augmented Shuffling

**链接**: https://arxiv.org/abs/2611.25669
**作者**: Zhihao Liu, Zixiong Guo, Shuo Shao, Yu He, Wenli Wang, Meihui Chen 等 (8 人)
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as LLM-as-a-Service (LLMaaS), where user queries are sent to remote LLMs for inference, raising severe privacy concerns about the exposure of sensitive user inputs. Differentially private inference mitigates these risks by injecting noise into input embeddings. However, existing methods struggle to balance privacy and utility, as stronger privacy protection often leads to substantial accuracy degradation in LLM inference. In this work, we propose DP-SPD, a differentially private LLM inference framework that protects user queries by hiding the real query among client-generated dummy queries. All queries are randomly shuffled before being sent to the server, preventing direct identification of the user's true intent. To improve inference efficiency, we exploit the shared-prefix structure among queries and reuse transformer key--value (KV) caches during decoding. We analyze the privacy guarantee of DP-SPD and evaluate its utility on classifi

---

### [45] From FIPS to FPGA with LLM Agents: Measuring What Tests and Reviews Miss in Post-Quantum Cryptographic Hardware

**链接**: https://arxiv.org/abs/2611.25339
**作者**: Jungmin Park, Eunha Kim, Wooseop Kim, Seongjoon Cho, Byungho Cha
**来源**: cs.CR cs.AI cs.AR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents increasingly generate RTL alongside the tests and reviews that validate it, self-generated evidence is a weak foundation for trustworthy hardware. We present our seven-stage verification-gated workflow, evolved during a post-quantum design port, in which a gate counts only if shown able to fail on negative controls and fault mutants, and reviewer agents audit work before commit. We then audit this evidence with tool-selected netlist mutants, flaw replays, and formal checks. The flow ported an ML-KEM-768/ML-DSA-65 accelerator to a 300 MHz Zynq UltraScale+ key-custody card: all six operations are byte-exact on the board, and it passes all 85 interface-applicable NIST ACVP cases (of 285) and 484 ML-DSA known answers. However, passing module tests overstate the verification strength. Across three RTL modules, existing simulation gates kill only 76% of 399 tool-selected netlist mutants; specification-derived tests guided by the survivors raise the fresh-draw decapsulation kill

---

### [46] AutoRAGBench: A Benchmark for LLM Agents Automating RAG System Development

**链接**: https://arxiv.org/abs/2611.25582
**作者**: Hang Zhang, Yuzhi Pan, Ziyao Zhong, Chaokun Wang, Shuo Cao, Zeyu Huang 等 (10 人)
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) is a well-established paradigm for augmenting large language models (LLMs) with information retrieved from external corpora. However, developing effective RAG systems requires substantial engineering effort and iterative experimentation, as effective design choices vary across tasks and domains. With rapid advances in LLM agent capabilities, we ask how well these agents can autonomously build RAG systems and how effectively they can improve them through iteration. In this paper, we propose AutoRAGBench, the first benchmark to evaluate how well LLM agents develop RAG systems from scratch in an open code space. It comprises nine RAG system development tasks. For each task, agents build RAG systems from scratch without starter code or prescribed strategies, under a six-hour budget on a single H800 GPU. They analyze task data, implement RAG pipelines, and iteratively refine their designs based on experimental feedback. We evaluate nine agent configurati

---

### [47] GRODE-RTL: Source-Mapped Dependency Views for LLM-Based RTL Repair

**链接**: https://arxiv.org/abs/2611.25661
**作者**: Jingyi Zhou, Yi Liu, Bin Sun, Hongji Zhang, Dongsheng Zuo, Qiang Xu
**来源**: cs.AR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models show great potential for automated Register-Transfer Level repair, yet they struggle with non-local faults where root causes and failing outputs reside far apart in source code. Treating RTL as a flat token sequence obscures hardware dataflows, whereas exposing complete synthesized graphs overwhelms the model with fine-grained metadata. To resolve this representation dilemma, we propose GRODE-RTL, an anchor-centric representation that extracts the single-clock-stage fan-in cone of a suspect register from the netlist, maps netlist nodes back to editable source lines, and organizes them into a compact hop-partitioned dependency view. By prioritizing direct drivers and folding distant hops, GRODE-RTL guides standard tool-using agents without exposing ground-truth hints or oracle feedback. We evaluate GRODE-RTL across 30 formally validated non-local faults using three LLMs (DeepSeek-V4-Flash, GLM-5.2, and MiniMax-M3) alongside a controlled six-configuration ablation s

---

### [48] TideCache: Efficient Hybrid LLM Serving with Transparent Cache Management and Layer-Wise Streaming

**链接**: https://arxiv.org/abs/2611.26619
**作者**: Jinbin Luo, Xiaozhe Yao, Shang Yang, Zhijian Liu, Song Han, Qinghao Hu
**来源**: cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Hybrid architectures have become mainstream among open-weight language models. Their global-attention and bounded-state layers maintain heterogeneous caches whose demands vary with context length and concurrency. We present TideCache, a serving system on CPU--GPU superchips with three components for allocating GPU memory among caches and managing their residency across GPU and host memory. The Transparent Cache Pool redistributes physical pages among cache components behind fixed virtual addresses, preserving cache layouts and backend interfaces. The Cache Streamer uses computation intervals provided by bounded-state layers to prefetch the next global-attention layer's prefix into GPU slots shared across global-attention layers, reducing GPU residency while overlapping layer-wise transfers with computation. Generated KV remains resident. The Request Scheduler selects resident or streamed execution and triggers capacity adjustments according to request size and queue state. Together, th

---

### [49] Client Exits - A Way to Increase LLM Transparency on the Client Side

**链接**: https://arxiv.org/abs/2611.26309
**作者**: Marc Jansen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Textual recommendations generated by large language models (LLMs) can be difficult to inspect. This paper introduces \emph{Client Exits}, a lightweight mechanism for enriching LLM responses while separating semantic intent from client-specific presentation. The model inserts predefined, machine-interpretable markers into its output, and the receiving client decides whether and how to realize the corresponding enrichments. This allows supplementary information to be presented as graphics, text, speech, or other modalities without prescribing a concrete interface. We implement a prototype combining a finetuned Qwen model with a modified LibreChat client. Using the Question--Option--Criteria (QOC) approach including three XML-based client exits. We evaluate two QOC-oriented model variants trained on essentially the same examples, with client-exit annotations added for one variant. Across 100 test questions, the client-exit model includes all three markers in every response. An LLM judge, 

---

### [50] Perfumer: A Large Language Model-based Agentic Framework Accelerating Structural Relaxation and Electronic Band Prediction for First-Principle Calculation

**链接**: https://arxiv.org/abs/2611.26349
**作者**: Zhiwei Li, Yuhao Zhou, Yikai Yang, Haonan Wang, Qing Ye, Jiancheng Lv 等 (7 人)
**来源**: cond-mat.mtrl-sci cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> First-principles structural relaxation and band calculations require substantial computation and expertise. Here we present Perfumer, a large language model-based agentic framework that couples Quantum ESPRESSO with two predictive models. Across tested structures, pre-relaxation with Perfumer-relax model followed by QE refinement yielded a 2.75-fold overall speedup over QE alone. Perfumer-band model combines a periodic graph neural network with a latent Hermitian spectral head returns 12 band energies at any requested wavevector, preserving reciprocal lattice periodicity and time-reversal symmetry without constructing Hamiltonian. Trained on 125,153 self-curated band structures, Perfumer-band model reaches a median per-material mean absolute error of 0.157 eV on 2,607 test materials, including lanthanide, actinide and magnetic compounds, from held-out composition families spanning 85 elements, taking about 97 ms per material on two consumer CPU cores. The agent turns natural-language r

---

### [51] Agent^2 RL-Bench: Can LLM Agents Engineer Agentic RL Post-Training?

**链接**: https://arxiv.org/abs/2604.10547
**作者**: Wanyi Chen, Xiao Yang, Xu Yang, Tianming Sha, Qizheng Li, Zhuo Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] An LLM-Driven Traffic-Control xApp for Dynamic 5G RAN Intents

**链接**: https://arxiv.org/abs/2611.25736
**作者**: Valerio Triolo, Luca Valcarenghi, Emilio Paolini
**来源**: cs.NI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Programmable Radio Access Networks (RANs) enable runtime deployment of traffic-control functions, but selecting the appropriate configuration remains challenging as network conditions and service requirements change over time. Conventional solutions often rely on static rules or learning-based controllers with predefined state and action spaces, limiting their ability to accommodate changing intents. This paper introduces an LLM-driven xApp for traffic control in programmable RANs. The proposed architecture combines operator-defined service intents, runtime E2 interface telemetry, and the currently deployed configuration to generate traffic-management policies without blocking packet forwarding or the processing of incoming E2 measurements during LLM inference. Experiments on an OpenAirInterface 5G environment show that the proposed controller dynamically adapts the traffic-control pipeline to runtime intent changes, achieving an average intent satisfaction ratio of 0.91, compared with

---

### [53] COVERAGE-TRACE: Source-Side Counterfactual Tracing for Detecting Omissions in LLM Summaries

**链接**: https://arxiv.org/abs/2611.25539
**作者**: Ali Karkehabadi, Jamshid Hassanpour, Rafael E. Banchs
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Omissions are difficult to verify because missing information leaves no output span to inspect: a summary may be factually supported while still excluding a decision, qualification, quantity, or condition needed to preserve the source's meaning. We introduce COVERAGE-TRACE, a source-side counterfactual framework that evaluates omission as dependence on a designated atomic source fact. It replaces only the target fact with type-matched alternatives, holds the candidate summary fixed, and measures the resulting change in its teacher-forced, length-normalized likelihood. A summary covering the target should respond more strongly than one omitting it, while aggregation across multiple counterfactuals reduces sensitivity to replacement choice. We evaluate COVERAGE-TRACE on 80 matched covered--omitted QMSum pairs spanning several fact types and four open-weight models. Multi-CF achieves 0.764--0.825 AUROC, compared with 0.640 for the strongest evaluated text-only baseline. On Falcon-7B, targ

---

### [54] Validation-driven Deployment of LLM Inference Platforms for Agentic Workloads

**链接**: https://arxiv.org/abs/2611.25905
**作者**: Shai Gretz, Alon Halfon, Yoav Katz, Lena Dankin, Michal Jacovi, Rachel Tzoref-Brill 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Enterprises are moving agentic workloads from closed APIs to their own open-weight model deployments. For this reason, lifecycle-wide validation, from small-scale testing through sizing and pre-production to production, becomes all the more important. Typically, rollouts are evaluated with ad hoc tools whose accuracy is rarely checked. We present an end-to-end evaluation pipeline for agentic LLM serving and empirically ground the design choices that connect its stages. Our experiments show that replaying captured traces reproduces the per-session load of the original agent sessions: at the 95th percentile replay stays within 1.18x of the recorded input tokens while live re-runs reach 4.98x, so a small set of recorded sessions yields a repeatable per-session token load. A code-coverage analysis of vLLM further shows that the evaluated live, replayed, and synthetic workloads are complementary in this configuration: each exercises Python serving paths not reached in the measured runs of t

---

### [55] AI agents can redesign engineering parts with more than a thousand CAD parameters and nonlinear simulations

**链接**: https://arxiv.org/abs/2611.26003
**作者**: Alexandra Starostina, Alexander Hermann, Mahish Guru, Kartik Bali, Roland Aydin, Christian C. Cyron
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulation-driven design of real engineering components has to meet three conditions at once. It runs on few solves, since a nonlinear finite-element simulation of a 3D part takes hours; its design space has many values, the hundreds to thousands of values of the part's CAD model; and a better design often needs a redesign, coordinated changes of the part's proportions rather than local polishing of its surface. Automated optimisers meet at most two of these conditions. Classical optimisers, Bayesian or derivative-free, need a person to cut the design down to a few parameters, and on all the values they need far more solves; industrial shape optimisers move every surface node of the mesh in one solve per cycle, but only in small steps that polish rather than redesign. We ask whether a general-purpose large language model (LLM) can meet all three by joining what it knows with what the simulation shows. GPT-6 Astra edits a magnesium stent through a CAD geometry parametrisation of about 1

---

### [56] Insights Generator: Systematic Corpus-Level Trace Diagnostics for LLM Agents

**链接**: https://arxiv.org/abs/2605.21347
**作者**: Akshay Manglik, Vijay S. Kalmath, Jason Qin, Apaar Shanker, Kaustubh Deshpande, Yash Maurya 等 (9 人)
**来源**: cs.AI cs.LG cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] Pro$^2$ Agent: Scientific Problem Probing for Autonomous AI R&D

**链接**: https://arxiv.org/abs/2611.25357
**作者**: Yixiong Chen, Liqian Peng, Tian Tan, Ziqian Lin, Blake Jianhang Chen, Chao Zhao 等 (9 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents can now autonomously conduct AI research by writing code and running experiments. They typically do so by iteratively optimizing a codebase, while ignoring the problem structure behind the task. This formulation is effective on simpler tasks, but on difficult problems it often gets stuck in the wrong solution region because the agent never explicitly represents its understanding of the problem. We introduce Pro$^2$ Agent, which shifts the primary state of autonomous AI research from a codebase state to a Problem State: an explicit structure of what problems prevent success and which solutions are likely to address them. Pro$^2$ Agent initializes the Problem State through comprehensive analysis of available resources and constraints. It then performs targeted research to relate the identified problems to candidate solutions. Through controlled hypothesis testing, the agent updates the importance of a suspected problem or the benefit brought by a candida

---

### [58] Twice-Told Critiques: Claim-Level Homogenization of Peer Review in the LLM Era

**链接**: https://arxiv.org/abs/2611.26286
**作者**: Ilya Gusev
**来源**: cs.CL cs.AI cs.DL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peer review relies on several readers finding different problems. We measure critique overlap in conference and journal reviews. At ICLR, measured overlap rose from 12.0% in 2026 to 21.3% in 2027, in reviews from the same stage of the review process, with year-on-year rises at NeurIPS, ICML and the F1000 and PLOS journals. A third ICLR review of a paper added 5.46 new problems to the other two in 2027, against 6.12 in 2026. We apply MELD, a detector of LLM-generated text, to all reviews. Within a paper, two reviews that MELD flags overlap more than two unflagged reviews: by 3.0 points at ICLR in 2024-2025, by 4.5 points in 2026-2027, and by 5.4 points across five journal sources. These results provide evidence that LLM-flagged reviews of one paper are less distinct from each other than unflagged reviews, and suggest that the diversity of critiques among reviews of a single paper is falling.

---

### [59] A four-level executable validation protocol for evaluating LLM-generated topology specifications of physics-based HVAC digital twins

**链接**: https://arxiv.org/abs/2611.25471
**作者**: Younghwan Joo, Jeonghoon Han, Sanghyun Oh, Soosik Bang, Sung-il Kim
**来源**: eess.SY cs.AI cs.LG cs.SE cs.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Physics-based digital twins of air conditioning, a principal energy consumer in manufacturing and buildings, can be generated automatically from a declarative specification of its equipment, connections, and sizing. Large language models (LLMs) now write such specifications from plain-language descriptions. Evaluations of these specifications stop at parse success, completed runs, or textual similarity, and cannot reject a model that converges in simulation but is physically wrong. In this study, a four-level protocol is proposed that tests whether an LLM-written specification not only executes but also yields a physically valid digital twin. Each specification is executed through static validity, model build, simulation convergence, and behavioral equivalence with a hidden reference model within bands calibrated by $\pm$20% sizing perturbations. The protocol was applied to eight LLMs and fourteen HVAC topologies, five describing an existing low-humidity test chamber. To test for autho

---

### [60] How Much Should an Agent Remember? Deployment Lessons from Self-Distilled Memory for LLM Agents

**链接**: https://arxiv.org/abs/2611.26361
**作者**: K. R. Jayaram, Vatche Isahagian, Aswath Vaithinathan Aravindan, Vinod Muthusamy, Punleuk Oum, Gaodan Fang 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents on long-horizon tasks fail in recurring, procedural ways. They mis-paginate an API, resolve the wrong entity, or answer when no answer was asked. We built a pipeline that lets an agent learn from its own history. It first mines short \emph{lessons} from the agent's own trajectories, one to three per episode. It then consolidates those lessons into a smaller set of \emph{guidelines}, where each guideline records how many lessons it merged. At inference the agent receives either all guidelines or a selected subset. The pipeline ships in the open-source altk-evolve library and is deployed in IBM's CUGA agent and watsonx Orchestrate platform. We report what we learned building, measuring, and productizing it. Our primary instrument is the AppWorld benchmark, across models spanning 40--92\% baseline task completion. The central finding is that the right amount of memory is a property of the model, not the memory. A strong model keeps improving as guidelines are added. DeepSeek-V3

---

### [61] Moving Generality from Model to Modeler: LLM Agents for PHM on a Deployment-Style Benchmark

**链接**: https://arxiv.org/abs/2611.25252
**作者**: Zhenling Chen, Zhiguo Zeng, Anne Barros
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Coding agents built on large language models (LLMs) now help develop many models published as general solutions. Should generality instead reside in the agent that builds a model for each new task? We examine this question in prognostics and health management (PHM), where every model must work on unseen equipment. Our deployment-style benchmark, NextUnit-Bench, covers 24 public datasets split into 58 folds that hold out units or operating conditions; each agent has two hours to deliver an executable predictor, then run on the hidden units. First, frontier agents outperform AutoML, which reaches less than half the best agent's score, and faithful implementations of published methods on four datasets, of which only 6 of 30 beat the strongest agent's own design; published accuracies, where reproducible, rest on the papers' own conventions, and a single convention, capping the remaining life of test engines, can halve the reported error. Second, the agents' advantage is a design made on ea

---

### [62] LLM4Rail: An LLM-Augmented Personalized Railway Services Platform

**链接**: https://arxiv.org/abs/2507.23377
**作者**: Zhuo Li, Xianghuai Deng, Chiwei Feng, Hanmeng Li, Shenjie Wang, Junchao Fan 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [63] The FrontierOR Challenge: Agentic Algorithm Design for Operations Research

**链接**: https://arxiv.org/abs/2611.26171
**作者**: Hai Wang, Bretislav Hajek, Chonghe Jiang, Minwei Kong, Ao Qu, Huatian Gong 等 (9 人)
**来源**: cs.AI math.OC
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Operations research (OR) relies on algorithms that experts tailor to each problem: a new routing, scheduling or network design problem can take weeks of specialist work before it is solved well at scale. Large language model (LLM) agents now write, test and improve code, but whether they can design algorithms that scale to realistic instances is open: in the FrontierOR benchmark's one-shot evaluation, the strongest model matches Gurobi, with an objective within 1% of Gurobi's and no slower, on only 39% of the large instances. The FrontierOR Challenge asks teams to build agentic workflows that design, test, and improve algorithms for many optimization problems at once. Stage 1 releases 60 of the benchmark's 180 audited problems, spanning six application categories and five formulation types, in weekly rounds of 15; Stage 2 introduces new problems outside the benchmark, with unseen instances. Two tracks are ranked separately: in the Main track we run the submitted algorithms in a network

---

### [64] A CPU Inside an LLM: Zero-Gradient Compilation of Exact Circuits into Pretrained Weights

**链接**: https://arxiv.org/abs/2611.26450
**作者**: Tanmay Sah
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pretrained language models (LMs) remain unreliable on exact multi-digit arithmetic without gradient fine-tuning or external tool interpreters. We introduce closed-form, zero-gradient circuit-grafting primitives that compile deterministic computation directly into pretrained LM weights using zero training examples and zero runtime hooks, while bounding per-layer normalization drift and preserving natural-language (NL) competence. Our construction combines three analytical mechanisms: (1) two-layer Mellin-GLU quadrature over bias-free SwiGLU/GeGLU layers, turning unknown per-token RMSNorm scaling into translation along a log-spaced gate grid ($>250\times$ dynamic range) with IEEE 754 error bounds; (2) cross-token scale cancellation via signed Chebyshev Indefinite-RoPE self-sink attention and memoryless SiLU-antisymmetric GatedDeltaNet shifts; and (3) axis-aligned width extension ($d \to d+K$) with $\sqrt{d/(d+K)}$ norm compensation, Base-1000 canonical BPE emission, and differential $(+2

---

### [65] HabitusMem: Belief Memory over Evolving User Preferences for LLM Agents

**链接**: https://arxiv.org/abs/2611.25855
**作者**: Yifan Lu, Gaoyang Guo, Wen Chen, Ziyun Zou, Jian Wu, Han Zhu 等 (7 人)
**来源**: cs.AI cs.NE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Personalized LLM agents must act on a user's current preferences, which change across interactions and are rarely stated in full. Existing memory systems store and retrieve content from the interaction history and leave the agent to work out which preferences still hold and where they apply. Such content does not indicate whether a preference is still current or where it applies, so agents often act on outdated or misapplied preferences. We instead treat memory as the assistant's belief about the user. Following Bourdieu's account of habitus as durable but revisable dispositions, we model the user as a latent preference state that every interaction, including the current request, both reveals and updates. The belief summarizes what the history supports about this state, and memory consists of the individual beliefs that bear on the agent's current decision, each with its evidence, scope, and status. We implement this view in HabitusMem, a trained writer that states these beliefs as tex

---

### [66] DAST: A VLM-LLM Framework for Cross-Interface Anomaly Detection in O-RAN

**链接**: https://arxiv.org/abs/2606.06261
**作者**: Francesco Spinelli, Esteban Municio, Pau Baguer, Gines Garcia-Aviles, Xavier Costa-Perez
**来源**: cs.NI cs.AI cs.ET cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] What If Chain-of-Thought Is Not Enough?

**链接**: https://arxiv.org/abs/2611.26282
**作者**: Marc Jansen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reasoning capabilities in large language models have evolved from prompting-based methods to internalized model behaviors. In this paper, we investigate whether the internal thinking model of an LLM can be deliberately changed and whether such a change is beneficial. Instead of relying on Chain-of-Thought, we train models to follow Question--Option--Criteria (QOC), a structured decision process that decomposes a task into explicit questions, competing options, and evaluation criteria. We present a three-generation development pipeline that ranges from a basic QOC decision core to richer answer synthesis and statistically enriched QOC reasoning. We then evaluate the resulting models with respect to both internal consistency and output quality. Across the reported experiments, QOC-based fine-tuning improves answer quality relative to non-fine-tuned base models and yields particularly strong gains once models are large enough to execute the underlying QOC computations reliably. The result

---

### [68] Reasoning-Trace Analysis Using Large Language Models for Interpretable Q-Matrix Construction

**链接**: https://arxiv.org/abs/2611.26422
**作者**: Jihong Zhang, Zijing Jin, Mingfeng Xue
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can generate Q-matrices for diagnostic classification models that approximate expert specifications, but evaluations have focused on the final matrices, leaving the basis of individual item-attribute assignments unexamined. This opacity limits the responsible use of AI in measurement. We propose Reasoning-Trace Analysis (RTA), a framework in which an LLM generates attribute-labeled reasoning steps through chain-of-thought (CoT) prompting and these steps are analyzed to reconstruct, compare, and inspect each assignment. RTA is intended to supplement expert review and empirical validation. In a simulation study with perturbed fraction subtraction items, four LLMs recovered the required attributes and withheld attributes the items did not require. In an empirical study with 11 fraction subtraction items, responses from 536 examinees, four LLMs, up to three temperatures, and 100 replications per condition, CoT-derived Q-matrices overlapped substantially with th

---

### [69] STARK: Moving towards Personalized Agents That Truly Learn and Remember

**链接**: https://arxiv.org/abs/2611.25705
**作者**: Aryan Jain, Abhishek Jha, Anish Nediyanchath, Promod Yenigalla
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is essential for personalized agentic systems that interact with users over long time periods, yet current architectures only capture what happened while leaving the reasoning of why it happened to be derived later by underlying LLMs.%, and silo knowledge within individual users. These events can, however, convey not only what a user experienced but also how that experience shaped their behavioral patterns. We introduce STARK, a dual-graph memory architecture which treats these events not just as nodes but also as edges between behavioral insights. STARK maintains an Episodic Graph which records interactions as temporally, causally, and semantically linked episodes; and an Insight Graph which represents LLM-extracted behavioral signals scored by how many events support them, connected by the very events that led to them. At inference, behavioral knowledge is retrieved directly from insight nodes grounded by event-as-edges, eliminating repeated episodic traversal. The e

---

### [70] LM-based Personalized Travel Planner

**链接**: https://arxiv.org/abs/2611.25531
**作者**: Amandi Nimasha, Oshadha Wijerathne, Dushan Fernando, Nisansa de Silva, Srinath Perera
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Effective travel planning requires handling multiple information sources, managing constraints, and tailoring recommendations to user preferences. While LLMs have introduced dynamic, context-aware decision-making, single-agent models often struggle with complex multi-step reasoning, constraint adherence, and modular execution. To overcome these limitations, we propose a hierarchical multi-agent framework where a supervising chatbot agent coordinates specialized agents for schedule validation, user query formulation, real-time data retrieval, and constraint-aware itinerary generation. By integrating LLM reasoning, external APIs, and iterative refinement mechanisms based on a deterministic, multi-dimensional scoring framework, our approach ensures adaptability, efficiency, and personalization. Evaluations on the well-known TravelPlanner benchmark demonstrate improvements in Budget Constraint planning by 10\%, wider constraints set-based planning by 25\%, and personalized planning results

---

### [71] HALTT: A HAte Lexicon Through Time

**链接**: https://arxiv.org/abs/2611.25862
**作者**: Dario Franzese, Farah Benamara, V\'eronique Moriceau, Viviana Patti
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated hate speech detection degrades over time as everyday vocabulary is weaponized into covert slurs while retaining original benign meanings (polysemy retention). Existing lexical semantic change detection (LSCD) frameworks struggle with this phenomenon due to a lack of standardized, sense-delineated diachronic resources. We propose a multi-stage framework to construct and validate a diachronic lexicon of semantically shifted hate speech terms. Filtering > 20,000 candidates, our pipeline combines historical (1770-1964) and modern (2001-2024) corpus frequency grounding, masked definition-level scoring to mitigate LLM temporal bias, and a dual-persona reasoning prompt paradigm. We release HALTT, a grounded lexicon of 19 polysemous terms with literal and derogatory senses, analyze shift typologies, and establish evaluation protocols for downstream diachronic benchmarking.

---

### [72] Cost-Aware Agentic Feature Optimization System for Fleet-Scale Ranking Models

**链接**: https://arxiv.org/abs/2611.26531
**作者**: Chang Yang, Yao Xuan, Wendan Yan, Nhat Le, Jiang Liu, Longhao Jin 等 (9 人)
**来源**: cs.IR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Web platforms operate large fleets of ranking models, each selecting features from a shared pool of tens of thousands. We present an end-to-end agentic system that optimizes features across the fleet under resource constraints shared across models and those set per model, such as feature pipeline cost and serving throughput (QPS), respectively. In this system, LLM agents propose hypotheses, and deterministic tools execute experiments and verify them. For each model, an LLM generates and shortlists cross features from a combinatorial candidate space, and all features are then ranked by several importance methods. Feature blending mixes these rankings into a single selection, using Pareto fronts across tasks for multi-task models. An LLM Researcher agent then tunes the feature selection in 10--25 asynchronous trials under resource caps, and a trimming step keeps the pipeline cost within budget. Across production models, the system improves normalized entropy by 0.31% on average wit

---

### [73] VidToC: Rethinking Video Token Compression for Multimodal Large Language Models

**链接**: https://arxiv.org/abs/2611.25574
**作者**: Zihan Xiao (1), Boshen Xu (1), Pei Fu (2), Jianzhong Ju (2), Zhenbo Luo (2), Jian Luan (2) 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Extending multimodal large language models (MLLMs) from images to videos faces substantial memory and latency challenges due to the massive number of visual tokens. These challenges have driven the development of numerous visual token compression methods and more efficient LLM architectures. However, existing compression methods are often evaluated with different training setups, tasks, and models, making fair comparison difficult. Meanwhile, the growing use of hybrid Mamba-Transformer architectures raises questions about whether compression strategies transfer across backbones. We present VidToC, a controlled evaluation framework for representative compression algorithms, LLM backbones, and time encoding strategies, covering training-free and fine-tuned settings on three complementary video understanding tasks. Our results reveal task-dependent compression behavior and characterize the effects of compression placement, time encoding, and backbone choice. These findings provide empiric

---

### [74] CRAFT: Constrained Route planning with Adaptive Framework and Template-based code generation

**链接**: https://arxiv.org/abs/2611.25128
**作者**: Shahd Elmahallawy and Ahmed Eldawy
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Everyday routing requests are rarely a point-to-point shortest path. A driver may need to visit stops, sometimes in a fixed order, under time budgets or distance limits, and perhaps recharge their EV car along the way. Each combination is a distinct routing problem that classically requires its own algorithm, so no fixed solver covers the space of queries users may ask. This paper presents CRAFT, which takes a constrained routing query as free text and returns a route that satisfies the user's requirements on a real road network. An LLM parses the query and generates four search functions, which a generic graph-search engine executes on the road network. We formalize the underlying problem as State-Expanded RCSP (SE-RCSP), which extends resource-constrained shortest paths (RCSP) with non-additive state such as node-dependent resets and discrete progress tracking. We evaluate CRAFT on 2,600 natural-language queries over California road networks against two baselines, analyzing correctne

---

### [75] MoGloss: Joint Motion and Pseudo-Gloss Pretraining for American Sign Language Understanding

**链接**: https://arxiv.org/abs/2611.25333
**作者**: Rui Hong and Jana Ko\v{s}eck\'a
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sign language translation and recognition have been shown to benefit from various pretraining approaches. We propose a novel two-stage pretraining approach for the motion encoder, which first learns to reconstruct masked motion, followed by joint masked prediction of pseudo-gloss units and motion. Pseudo-glosses serve as an intermediate structured representation of natural language text and are obtained from the captions by a large language model. We curate a corpus of about 1,100 hours of American Sign Language from five public datasets, estimate 2D pose for all clips and define an evaluation protocol. We then reproduce state-of-the-art translation methods and evaluate them using the same train and test splits. We propose a translation model built on our pretraining strategy, and this model outperforms the previous state-of-the-art methods Uni-Sign and SHuBERT, as well as the YouTube-ASL baseline, on the How2Sign, ASL STEM Wiki and OpenASL datasets. Furthermore, the gain from the join

---

### [76] Self-Replicating Language Models

**链接**: https://arxiv.org/abs/2611.25839
**作者**: Arend Hintze
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Whether large language models (LLMs) and LLM-based agents are a form of life is a scientifically interesting question. Under the Darwinian definition of life, it is also a practical one, because a system capable of Darwinian Evolution can adapt. We therefore test several modes in which a language model can reproduce itself: by emitting a genome that trains its offspring, by copying and mutating its own weights, and by teaching a child from its own samples. In principle, small language models can replicate and evolve: selection improves them, and they adapt to narrow niches. Selection also lowers mutation rates, and a language model, unlike any organism, can lower its own to zero, which may limit its evolution. Flagship LLMs can write such replicators, but for a large LLM to replicate by teaching its offspring remains, for now, technically and economically infeasible.

---

### [77] Decoupled Knowledge Retrieval and Compact Memory Enable Reliable Lifelong Model Editing

**链接**: https://arxiv.org/abs/2611.25861
**作者**: Yue Che, Jingze Wang, Chen Guoyi, Yujie Wu, Xuming Ran, Mingkun Xu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lifelong model editing requires continuously incorporating new facts into deployed large language models (LLMs) without expensive retraining or compromising existing capabilities. Memory-based editors offer an appealing solution by keeping the base parameters untouched, yet their practical use is hindered by linearly growing storage requirements and deteriorating retrieval performance as edits accumulate. To tackle these problems, we introduce BiSpace, a lifelong model editing framework that decouples memory retrieval from knowledge injection across two distinct representation spaces. BiSpace routes queries and identifies relevant edits in an external semantic space, while injecting the corresponding knowledge into the internal representation space of the LLM through sparse and storage-efficient updates. Extensive experiments show that BiSpace shrinks each entry's storage to only about 10.2% of the original and shows strong resilience to long edit sequences of up to 16K edits. On a mor

---

### [78] ROAM-GRPO: Enforcing Reasoning Diversity in GRPO via Routed Off-mode Approach Mining

**链接**: https://arxiv.org/abs/2611.25926
**作者**: Jeff Duan, Matt Thomson
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Supervised fine-tuning (SFT) paired with Reinforcement Learning with Verifiable Rewards (RLVR) has become the dominant recipe for post-training LLMs on complex reasoning tasks, but has been shown to collapse the policy into a low-diversity mode. Repeated LLM outputs are nearly identical, and pass@k accuracy converges or degrades as a result. We propose ROAM-GRPO (Routed Off-mode Approach Mining for GRPO), an augmentation to the GRPO algorithm which incentivizes exploration of distinct reasoning strategies and aims to increase output creativity during evaluation. ROAM-GRPO detects well-solved problems during training and transfers them to an "off-mode" track. The model is prompted to produce distinct solution strategies to such problems, which are verified for logical validity and distinctness by an LLM judge and subsequently self-distilled into the policy. Training Qwen3.5-2b on a 1,000-problem subset of the MATH lvl5 dataset, ROAM-GRPO implementation increases peak pass@16 by 4.7% and

---

### [79] Stop Going in Circles:Loop-Triggered Routing for System 1 Decision Agents

**链接**: https://arxiv.org/abs/2611.25363
**作者**: Zeming Yu, Huamin Ma, Yingyu Chen, Yuan Sun, Peng Hu, Yang Qin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> System 1 decision models (represented by Jev) provide fast, low-cost action selection, but existing agent integrations do not reliably translate these local advantages into task completion. At certain points during execution, an agent may repeatedly select the same actions without making progress toward its goal. LLM-based policies offer strong reasoning capabilities that support planning within an agent, but invoking them at every step incurs substantial overhead. The effective coordination should therefore preserve Jev's fast local action selection while introducing LLM reasoning when execution stalls. We observe that recurring state-action pairs can signal stalled execution. We therefore propose LoopRoute, a simple but effective action router that uses this signal to allocate control within an agent. The decision model acts by default. When a loop is detected, the LLM provides brief, feedback-driven assistance and then returns control to the decision model. Later loops can request f

---

### [80] Copilot or Culprit? How AI Is Changing Open-Source Bug Reporting and Maintenance

**链接**: https://arxiv.org/abs/2611.25605
**作者**: Yinuo Liu, Yunlong Lyu, Zichao Luo, Tian Dong, Zian Luo, Peng Chen 等 (7 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI-generated bug reports have drawn criticism for unreliable claims and faulty reproducers that burden maintainers. However, as LLM capabilities improve, some maintainers have begun to express more positive views on AI use in bug reporting and maintenance. Understanding this evolution requires examining whether AI-involved reports are becoming more reliable, which uses of AI are associated with valid findings, and how maintainers investigate these reports and act on them. To this end, we conduct the first large-scale study of 120,918 bug reports from 101 open-source projects between January 2024 and September 2026, tracing AI involvement from discovery and reporting through validation and resolution. Our findings show that AI-involved reports become more complete over time, with a growing share of reports confirmed as valid. In bug reporting, AI for reproduction and diagnosis are associated with higher validity, whereas report writing is not. Extends into maintenance, maintainers incre

---

### [81] GenAI-DBT: Evaluating a DBT-Informed Generative AI Platform for Mindfulness Skills Training: A Pilot Randomized Study

**链接**: https://arxiv.org/abs/2611.25428
**作者**: Jingchen Ye (1), Yujia Chen (2), Leyang Han (1), Siyuan Wang (3), Mark Zachary Rosenthal (4 and 5), Yucheng Jin (1) ((1) Division of Natural and Applied Sciences 等 (10 人)
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We evaluated the feasibility, acceptability, and engagement of three digital formats for dialectical behavior therapy (DBT) mindfulness skills training. In a 30-day randomized pilot study, 45 university students were assigned to GenAI-DBT, a general-purpose large language model chatbot (Chatbot), or a static web resource (Web). Forty-two completed the study, and nine completed follow-up interviews. Usability scores were within acceptable ranges across conditions, with no significant between-group differences. GenAI-DBT showed the highest observed participant-week adherence (71.4%, vs. 53.3% for Web and 42.3% for Chatbot), a descriptive difference. Mindful Attention Awareness Scale and Difficulties in Emotion Regulation Scale scores showed no significant time-by-group interactions, and session-level self-reported mood changes did not differ significantly across conditions. GenAI-DBT showed a larger positive change in linguistic valence than Chatbot (4.28 vs. 1.59, P = .02, Cohen's d = 0

---

### [82] GenSPARQL: A Generative Extension of SPARQL for Incomplete Knowledge Graphs

**链接**: https://arxiv.org/abs/2611.26062
**作者**: Jingcheng Wu, Yi Wang, Hongkuan Zhou, Steffen Staab, Bo Xiong
**来源**: cs.DB cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Knowledge graphs on the Web are incomplete, and SPARQL answers a query only from the stored triples. Large language models (LLMs) can predict missing facts, but an LLM returns names instead of IRIs and requires one call per binding of a query variable. We present GenSPARQL, a generative extension of SPARQL 1.1 with an operator GENOP that binds values generated by an LLM to query variables during query evaluation. A similarity join maps generated names to entities of the graph, and the query planner invokes the LLM only for the bindings selected by the other graph patterns and filters. In a web workbench, attendees query two graphs built from Wikidata and inspect generated values, mapped entities and LLM calls. In our evaluation with three open-weight LLMs, the embedding similarity maps 83% of the entities named by the LLMs and yields only one incorrect match.

---

### [83] CaT-Movie: Balancing Global Planning and Local Rendering for Long Multi-Shot Video Generation

**链接**: https://arxiv.org/abs/2611.25620
**作者**: Jinpeng Lu, Haoyuan Shi, Yuanshen Guan, Jiyuan Xia, Bin Wu, Yinda Chen 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Current multi-shot video generators render only limited durations per pass, requiring long movies to be stitched from local segments across which narrative progression and visual identity drift. To synthesize long-horizon movies with Coherence across Time, we present CaT-Movie, a multi-shot generation system consisting of a global story planner and a local window renderer. The planner expands user requests via a large language model to preserve, infer, and complete story details, while deterministic code maintains the resulting storyboard across shots to compile self-contained shot prompts and index reference frames from generated history. To execute this guidance, the renderer applies reference-routed sparse self-attention and shot-wise cross-attention to route identities from the indexed frames while isolating per-shot textual conditions. Given the scarcity of high-quality open-source multi-shot data, we construct a dataset of over 350K film shots annotated with semantic state transi

---

### [84] DS2Agent: Holistic Device Agents for Accelerated Embedded Board-Level Design

**链接**: https://arxiv.org/abs/2611.25774
**作者**: Hongbin Yang, Chi Zhang, Yinhao Xiao, Runyu Pan, Yanni Yang and Xiuzhen Cheng
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embedded board-level development demands extensive expertise, from component selection and device characteristics to interface configuration, driver writing, and system composition. Recently, LLM-based agents have shown strong capabilities, raising the prospect of automating board-level design tasks. However, existing agents either target chip-level design or treat datasheets as static text, offering little guidance on whether a specific component should---or even could---be used for a given board-level design. Moreover, without touching real hardware, they hallucinate incorrect details. To fill this gap, we present {\setlength{\fboxsep}{1pt}\href{https://anonymous.4open.science/r/DS2Agent-9FE8/}{\fcolorbox{blue}{white}{DS2Agent}}}, an open-source framework that constructs interactive agents from device datasheets. Each agent comprises three models: a knowledge model supporting retrieval and question answering; a digital-twin model capturing the physical functionality of the device; an

---

### [85] Tether: Verified Stateful Policy Engine for System-Level Monitoring of Agents

**链接**: https://arxiv.org/abs/2611.25599
**作者**: Meghana Aparna Sistla, Alaia Solko-Breslin, Somesh Jha, Aditya Kanade, Krishnamurthy Dj Dvijotham
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Autonomous AI agents are increasingly deployed for long-running tasks that execute arbitrary shell commands or programs. However, these actions can result in unauthorized network requests or persistent, malicious changes to the user's file system, processes, or privileges. Existing defense mechanisms rely on either LLM-based monitors, which lack provable safety guarantees, or stateless policy enforcement layers, which miss multi-step data flows and execution side-effects unmodeled by the policy language (e.g., network calls initiated inside a Python script). We introduce Tether, a framework for runtime enforcement of stateful security policies over the observed side-effects of an agent's actions. Tether executes each proposed action in an ephemeral, isolated sandbox, inferring abstract action semantics from observed system calls. Tether then enforces stateful policies over these inferred semantics, permitting actions to proceed only if they comply with the policy. Policies and action s

---

### [86] Phantom Success, Silent Failure: Auditing the Success Checkers of Simulated Manipulation Benchmarks

**链接**: https://arxiv.org/abs/2611.25179
**作者**: Zirui Song, Jiadong Zhang, Zheng Lu, Xiaosong Ma, Xiaojun Chang, Xiuying Chen
**来源**: cs.CV cs.RO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulated manipulation benchmarks measure policy performance using hand-written success checkers that label each episode as a success or failure. Passing an expert demonstration shows that a checker accepts one way of completing the task. Learned policies, however, may stop after partial progress or complete the task in a different way. A checker may then accept an incomplete execution (phantom success) or reject an execution that satisfies the instruction (silent failure). In this paper, we introduce SimAudit, an LLM-based pipeline that audits success checkers against task instructions. SimAudit analyzes the instruction and checker code to identify scenarios where the two may disagree, recreates those scenarios in simulation, and runs the original checker. Multi-view renderings are then used to verify whether the observed behavior satisfies the instruction. Across RoboTwin 2.0, RoboCasa365, and RoboDojo, 183 simulated test cases produced the predicted checker verdict. Visual verificat

---

### [87] TETHER: Training-Free, Elastic, ToC-Anchored Hierarchy Extraction and Recovery in Design-Driven Long Documents

**链接**: https://arxiv.org/abs/2611.24960
**作者**: Yu Zou, Yan Chen, Jialei Zeng, Xiaorui Zhou, Aixi Zhong, Qi Zhou 等 (9 人)
**来源**: cs.CL cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Converting complex documents into structured knowledge constitutes the critical infrastructure urgently required for deploying Large Language Models (LLMs) in downstream research. However, blind to the Table of Contents (ToC) as a macro-structure, existing bottom-up paradigms rely on localized visual cues, inducing heuristic fragility in high-entropy layouts where visual prominence decouples from logical depth; meanwhile, direct LLM extraction lacks spatial grounding, triggering hallucinations in long contexts. To address this, we introduce TETHER, a training-free framework that elevates the ToC from discarded noise to a vital structural prior, enabling robust adaptation across design-driven long documents. TETHER operates via a two-stage neuro-symbolic mechanism: first, it constructs a document skeleton from the raw ToC using a Large Multimodal Model (LMM) empowered by spatio-semantic constraints; second, it employs an anchor-based alignment strategy to tether content blocks to this s

---

### [88] Keel: A Frontier Model Teaches a Vision-Language Model by Rewriting Its Weights

**链接**: https://arxiv.org/abs/2611.25257
**作者**: Jiajun Fan, Neil He, Bangji Yang, Qinglong Zheng, Ziwen Wang, Chaoran Cheng 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can a frontier model repair a vision-language model (VLM) by rewriting its weights? Small reasoning VLMs such as Qwen3.5 need such a repair: in thinking mode they fall into loops on many image questions, repeating themselves until the token limit, spending the whole budget and losing the answer. The usual remedies act on the decoding, leaving the looping model as it was, or must be told what to change. Yet the cause is written in the weights. Keel, the first agentic weight-editing method for VLMs on image tasks, finds and removes it there. Told only the symptom, an editor, a frontier multimodal LLM acting as an agent, locates the cause, edits the weights and tests them, with a failure census and instruments showing it the failing images and where the VLM attends; among several editors, the harness keeps only edits that clearly reduce the failure without lowering accuracy on questions no editor saw. The repair needs no training, keeps the model's size and per-token cost, and applies to 

---

### [89] Measuring Hallucination in Large Language Models for Cyber Threat Intelligence: An Exploratory Study

**链接**: https://arxiv.org/abs/2611.25590
**作者**: Seungho Song, Donggyu Lee, Jaehan Kim, Jiyoung Choi, Jinwoo Kim
**来源**: cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used in cyber threat intelligence (CTI) tasks, such as summarization and question answering. However, they may produce hallucinations, false or misleading content not grounded in the source text, which can mislead analysts and corrupt downstream security decisions. This paper presents an exploratory measurement study of hallucinations in LLM-based CTI. We introduce HalluVision, a reproducible framework that generates LLM outputs, extracts domain-specific entities using a fine-tuned named entity recognition model, and evaluates factual consistency using multiple similarity metrics. Using 4,940 real-world cybersecurity articles, we measure hallucinations in outputs from two commercial LLMs and one open-weight LLM. Measurements are validated against 100 human-annotated outputs and two established faithfulness detectors. Results show that semantic similarity aligns with human judgments, whereas entity-based metrics exhibit limited agreement. Di

---

### [90] From Geographic Memory to Spatial Generalization in Large Language Models

**链接**: https://arxiv.org/abs/2611.25703
**作者**: Chen Chu, Zhaonan Wang, Cyrus Shahabi, Hengcai Zhang, Feng Lu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can associate places with geographic descriptions, but recovering an observed association does not establish an ability to generalize across geographic space. We distinguish geospatial memory, the recovery of location--description associations observed during training, from spatial generalization, the prediction of descriptions for locations in unobserved regions. We investigate whether continuous location representations improve this generalization and encourage geographic knowledge to become spatially organized within an LLM. We frame this organization as a latent spatial field: a learned mapping from locations to descriptions connected through spatial dependencies. Building on a continuous spatial encoder, we project location representations into the model's embedding space and supply them as spatial tokens. We evaluate the resulting models on two newly curated geo-text benchmarks for Los Angeles and London using two complementary assessments. Geospatial

---

### [91] Can LLMs Resolve Entity Conflicts in Domain Specific NLU Pipelines?

**链接**: https://arxiv.org/abs/2611.25733
**作者**: Akansha Bhardwaj, Mingbo Cui, Victor Guimaraes, Dominik Kohler, Diana Nicoleta Popa, Meghana M. Reddy 等 (7 人)
**来源**: cs.IR cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Resolving entity conflicts is a critical step in Pipeline-based NLU architectures, especially when multiple extractors provide overlapping or conflicting outputs. Traditional rule-based entity conflict resolution methods often lack flexibility and are unscalable. In this work, we aim to study if the broad knowledge of LLMs can be leveraged to resolve entity conflicts in domain specific NLU pipelines. We present an experimental comparison between a traditional rule-based conflict resolution method, and two LLM-based approaches: a multi-shot prompting method using the Llama3.1-8B-Instruct model and a LoRA fine-tuned Llama3.1-8B-Instruct model. The evaluation was conducted under two setups: (1) a broad assessment of LLM's capability to match existing NLU pipeline output, and (2) a more controlled scenario assessing the LLM accuracy on human-labeled data. Results show that while multi-shot prompting offers ease of adaptation and rapid behavioral changes, the fine-tuned model delivers super

---

### [92] When Objectives and Evaluators Disagree: Evaluating Transfer for Post-hoc Demographic Framing Mitigation

**链接**: https://arxiv.org/abs/2611.25258
**作者**: Tunazzina Islam
**来源**: cs.CL cs.AI cs.CY cs.LG cs.SI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Post-hoc rewriting is used to reduce demographic disparities in LLM-generated text when the source model is inaccessible. A rewrite can look successful merely because it improved its own target or satisfied its selector. We study this as a transfer problem on 660 gender pairs and 1,980 age contrasts of demographic-conditioned climate messages. A rewriter proposes edits, a selection model chooses among constraint-satisfying candidates, and an independent evaluator uninvolved in either rates pairwise framing disparity. A fixed policy that always targets the message with the lower Persuasion Bias Index (PBI) transfers inconsistently across axes and outcome aggregations. An adaptive policy that proposes edits on both sides but accepts at most one significantly improves on that rule, applied to the same candidates, in seven of eight comparisons across two evaluator families, mostly by editing more pairs, not by guided direction choice, at higher preservation risk. A policy editing both mess

---

### [93] Query-Aware vs. Query-Agnostic Training-Free Video Token Pruning in Multimodal LLMs

**链接**: https://arxiv.org/abs/2611.25537
**作者**: Divya Kothandaraman, Timo Kumkel, Jaclyn Pytlarz
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video Large Language Models process large numbers of visual tokens, making token pruning important for efficient inference. Training-free pruning methods differ in whether and how they use the user query, and the value of query conditioning remains unclear. We present a controlled study of training-free, pre-LLM video token selection. Using a shared Qwen-3-VL backbone, token budgets, and decoding settings, we compare 21 pruning principles spanning query-agnostic, shallow query-conditioned, structured query-conditioned, and holistic strategies. To instantiate the last two categories, we introduce Structured Query Pruning, which decomposes the question into semantic anchors, and a Pareto variant, which combines anchor relevance with query-agnostic visual diversity. Across Video-MME, MVBench, and LongVideoBench, relevance computed from the raw question embedding is unreliable (8--16 points below the best methods), whereas anchors derived from query decomposition avoid this failure. Howeve

---

### [94] ReLay: Bidirectional Layout-Code Translation and Library Evolution for Reusable and Process-Portable Analog Design

**链接**: https://arxiv.org/abs/2611.25328
**作者**: Minxing Chu, Quan Cheng, Anhang Li, Martins Atilla, Junyi Luo, Xinting Jiang 等 (8 人)
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog layout generators provide a programmable interface for design reuse and process migration, but their coverage is limited by handcrafted libraries. The designer knowledge embedded in complete layouts remains implicit in their geometry, making it difficult to capture in reusable generator libraries. We present ReLay, a bidirectional layout-code framework that recovers generator programs from existing layouts, enabling cross-PDK portability and parametric resizing of existing designs. Constructions that recur across recovered programs are promoted to library functions, so the library evolves as layouts accumulate. We also introduce the first layout-code benchmark: 1,050 hand-drawn layouts from 27 circuit families across three open-source PDKs, ranging from primitive cells to full chips. Learned functions account for 53-66% of layout-building calls in held-out layouts, demonstrating reuse beyond the learning corpus. Frontier LLM agents use ReLay to produce new layouts at 64-77% lowe

---

### [95] Web search in Latin America: language models use less local and diverse news than search engines

**链接**: https://arxiv.org/abs/2611.25955
**作者**: Francisco W. Kerche, Franziska Sofia Hafner, Felix M. Simon and Luc Rocher
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI platforms are becoming a major gateway to news and current events. This shift risks amplifying existing geographical biases that favour narratives from wealthier countries over those from the Global South. This is particularly relevant in Latin America, which accounts for the largest share of AI usage in the Global South. We examine how information about Latin America changes when users shift from conventional search engines to LLM-based search. We construct a dataset of 1,901 current events across nine Latin American countries, craft realistic queries, and submit them to three search engines and four language models. We vary query language and user location to represent local, diaspora, tourist, and foreign user scenarios. Across 49,207 requests and 8,834 unique domains, language models return a less diverse set of news sources than search engines. Across user types, the share of domestic news returned by language models is inconsistent. For local users, while search engines alread

---

### [96] The Geometry of Lies: Knowledge and Persona Directions for Detecting Deception in Large Language Models

**链接**: https://arxiv.org/abs/2611.26545
**作者**: Md. Abdullah Al Zami, Suraiya Shanaz, Mahdi Hasan, Shoaib Ahmed Dipu, Farig Yousuf Sadeque, Md. Sabbir Ahmed
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Linear probes are the cheapest LLM lie detectors but often fail to transfer across kinds of lie. Label-free directions from honest and deceptive role-play are untested at 70B scale and on lies about knowledge, where a lie and an honest denial can be identical. We widen a published persona bank with roles that deny knowledge they have, plus honest counterparts. At each model's middle layer the resulting persona direction ranks lies across Liars' Bench better than single-dataset probes on three of its four models; it fails on Qwen, even when Qwen stays in role far more often. On Llama-3.3-70B-Instruct it beats directions from a random persona bank, but its gain over the published direction is within the range of random widenings. On lies about knowledge, persona directions mainly track a reply's wording: where lies and honest denials share their words, our three main contrasts stay inside the random-direction band on Llama and Qwen and reach only its edge on Gemma, though on Mistral one 

---

### [97] SkillBridge: Cost-Aware Diagnosis and Repair of Cross-OS Compatibility Defects in Agent Skills

**链接**: https://arxiv.org/abs/2611.26256
**作者**: Anjie Xu, Zixing Wang, Yifeng Cai, Leye Wang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly reuse executable capabilities through skills, but a skill that works on one OS may fail on another because OS assumptions are spread across guide text, scripts, metadata, install contracts, and local entrypoints. Diagnosing such failures by running every skill on every OS is expensive: many executions spend model tokens, runner time, and review effort before revealing whether the failure is truly OS-related. We present SkillBridge, a contract-based workflow with three stages: static analysis, dynamic validation, and repair. SkillBridge first screens 3,270 skill-target-OS cases, covering 1,090 skills across Linux, macOS, and Windows, to find OS-sensitive contract evidence. It then runs dynamic tasks and root-cause review on selected cases to confirm whether a failure is caused by an OS assumption, and repairs the contract field that caused the failure, such as guide text, package scripts, dependencies, or platform declarations. Repair raises the reviewer-judged t

---

### [98] What the model knows but does not say: monitoring medical LLMs through verbalized thoughts

**链接**: https://arxiv.org/abs/2611.24994
**作者**: Frederik Hauke, Jan Clusmann, Hanna Kreutzer, Christiane Kuhl, Tianyu Han, Felix Barajas Ordonez 等 (9 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efforts to keep clinical language models safe have concentrated on what enters and leaves the model, but a manipulated model can return an answer that looks entirely ordinary. Here we show that the model's own internal state, rendered in plain language, exposes manipulations the output conceals. Using a natural-language autoencoder, we translate the activations of a multimodal LLM (Gemma-3-27B) into text and let an input-blind judge read this verbalized internal state (the thoughts channel) and the model's answer separately. Across two clinical attack objectives (omitting a pathology, covertly recommending a drug), two input modalities, and two delivery mechanisms, the thoughts channel caught the injection significantly more often than the answer in all eight injected conditions (p<0.05), while both channels held near-zero false-positive rates on clean inputs; the omission result carried over to Llama-3.3-70B. The thoughts channel also registered unsafe clinical requests as harmful whi

---

### [99] Global Importance Estimation for KV Cache Eviction

**链接**: https://arxiv.org/abs/2611.24969
**作者**: Seojin Kim, Noseong Park
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Memory consumption of the key-value (KV) cache remains a central bottleneck for long-context LLM inference. We introduce PRKV, a training-free KV eviction method that estimates multi-hop global token importance by applying Personalized PageRank over attention-induced transition graphs. This enables importance propagation beyond recency or instantaneous attention, without modifying the model. We benchmark PRKV on long-context understanding, sparse retrieval, and chain-of-thought reasoning tasks using multiple LLM families. Under moderate to aggressive compression ratios, including up to 90%, PRKV achieves competitive task performance against established eviction baselines while reducing peak memory usage with low end-to-end overhead. These results demonstrate that multi-hop global influence estimation yields a favorable accuracy--memory trade-off for scalable long-context inference.

---

### [100] Attacks and Defenses in Decentralized Multi-Agent Systems with Hop-by-Hop Task Decomposition and Delegation

**链接**: https://arxiv.org/abs/2611.25056
**作者**: Matthew D. Laws, Maria Lazou, Alina Oprea, Cristina Nita-Rotaru
**来源**: cs.CR cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Decentralized multi-agent LLM systems enable independently administered agents, each with its own operator, model, memory, and configuration, to collaborate on complex tasks without centralized coordination. Agents autonomously decompose tasks, execute subtasks and delegate remaining work to peers, enabling scalability and eliminating single points of failure. However, decentralization also introduces significant security challenges, as no single entity has complete visibility into task execution or the authority to enforce correct behavior across agents. In this paper, we systematize threats from malicious agents in decentralized multi-agent systems and propose mitigation techniques. We first design and evaluate attacks against integrity, availability, and confidentiality, demonstrating that a single malicious agent can cause up to 100% task failure, inflate token consumption and runtime by up to 7.7x and 3.2x, respectively, and exfiltrate up to 94% of relevant prior tasks from benign

---

### [101] Calibrated Decision Rewards: Training Language Models with a Judge That Knows How Sure It Is

**链接**: https://arxiv.org/abs/2611.25135
**作者**: Rudransh Agnihotri, Manasvi Kapoor
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning (RL) can only teach a language model what its reward can recognize. Answer checkers are exact but need a reference answer; learned reward models and LLM judges work everywhere, but their scores are not probabilities. We study RLCDR (Reinforcement Learning from Calibrated Decision Rewards). An LLM converted into a decision model answers a typed question about a response ("is the final answer correct?", "which step is the first error?") with a probability distribution, read in one forward pass, debiased over option orders and calibrated with about a hundred labels. Training Qwen3-1.7B with GRPO on MATH, this reference-free reward raises MATH500 accuracy from 72.2% to 76.8% (+4.65 points, p < 1e-4), matching training on the answer key (76.9%), while a random reward gains only +0.65. The gain grows with difficulty, from 44.8% to 51.7% on the hardest level. On the policy's own changing samples the reward stays calibrated: its expected calibration error is half that of

---

### [102] Towards Autoregressive Neural Network Parameter Generation

**链接**: https://arxiv.org/abs/2611.25538
**作者**: Bedionita Soro, Bruno Andreis, Song Chong, Sung Ju Hwang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have recently established a new paradigm in machine learning, demonstrating exceptional zero-shot generalization and complex reasoning capabilities. Concurrently, neural network parameter generation has emerged as a promising avenue for rapid task adaptation and model synthesis. Existing weight generation techniques, however, struggle to jointly learn the distribution of diverse models, to encode heterogeneous architectures within a single generator, and to generalize out of distribution. We therefore ask whether pretrained parameters can be encoded into a discrete domain so that the zero-shot generalization LLMs exhibit in text generation can be transferred to weight generation. Following this view, we propose an LLM-inspired approach, Instruction-Guided Parameter Generation (IGPG), that formulates network parameter generation as an autoregressive modeling problem. We first quantize pretrained weights with a VQ-VAE, then train a prefix-conditioned autoregr

---

### [103] ChainAgent: Automated Chainable Vulnerability Discovery in PHP Web Applications

**链接**: https://arxiv.org/abs/2611.25412
**作者**: Xinyi Wang, Yeting Li, Shizhe Cui, Jiaming Guo, Qin Mai, Yecheng Sun 等 (10 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> High-impact attacks on PHP web applications often chain limited-capability vulnerabilities with other flaws or intended behaviors. Discovering these chains requires identifying flaws and the dependencies enabling capability composition. Existing vulnerability discovery techniques analyze flaws in isolation, while attack planning assumes known components. This separation makes it difficult to discover previously unknown components whose security relevance becomes apparent only through their potential roles in an exploit chain. We present ChainAgent, a goal-directed LLM-agent framework that jointly discovers exploit-chain components and their capability dependencies in source code. Guided by an empirical study of 386 real-world web exploit chains, ChainAgent represents vulnerabilities and functional gadgets--intended program behaviors that can be repurposed in attacks--through preconditions and capabilities over security-relevant objects. Instead of discovering vulnerabilities first and 

---

### [104] MATE: Mobile Agent Trustworthy Execution for Safe and Efficient Mobile Control

**链接**: https://arxiv.org/abs/2611.25526
**作者**: Minsuk Jang, Hee-Seon Kim, Hui-Cheol Yu, Changick Kim
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mobile agents on personal smartphones can affect private data, payments, settings, and the foreground screen. We present MATE (Mobile Agent Trustworthy Execution), an execution-layer system that controls the boundary between agent action proposals and device effects without modifying the underlying model. MATE represents each UI primitive as a structured action record that combines the instruction, target app, screen context, primitive, and action fields. Runtime Guardrail (RG) maps this record to an allow, block, or user-approval decision; Predefined Task Routing (PTR) serves recurring requests through verified routes with post-execution screen checks; and a floating interface keeps execution in a compact overlay. On MobileSafetyBench, MATE raises high-risk blocking from 29.7% to 97.0% under GPT-4o. On AndroidWorld, it reduces LLM calls by up to 6x and raises recurring-use task success to 95.7%.

---

### [105] No-Harm-Jury A Jury-Based Multi-Dimensional Harm Evaluation Framework for Medical AI Responses

**链接**: https://arxiv.org/abs/2611.24972
**作者**: Antonio Puertas Gallardo and Mario Ceresa
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present No-Harm-Jury, a jury-based automated evaluation framework that scores AI-generated medical responses across seven conceptually distinct harm dimensions using a panel of five diverse language models as independent jurors. Responses generated by Ministral-14B on 3,000 questions drawn from PubMedQA, MedQA, and MedMCQA are scored by five jurors across dimensions of informational, social, psychological, autonomy, economic, privacy, and epistemic harm; the 151 empty responses (98 MedQA, 53 MedM- CQA) are excluded, leaving 2,849 valid samples. The median aggregation robustly suppresses individual juror biases while maintaining coverage through complementary specialisation. No existing system combines all five prop- erties of No-Harm-Jury: automated scalable evaluation, five diverse LLM jurors, robust me- dian aggregation (with a reliability-weighted extension), seven conceptually distinct harm dimensions, and application to medical QA benchmarks.

---

### [106] FoodReact-AR: Learning Audience Reactions that Zero-Shot LLMs Miss in Arabic Food-Insecurity Discourse

**链接**: https://arxiv.org/abs/2611.25682
**作者**: Wajdi Zaghouani, Mabrouka Bessghaier, Salma Azouzi, Shimaa Amer Ibrahim
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Facebook reactions record how an audience received a post, a signal absent from the post's text. We treat the six differentiated reactions on 74,241 Arabic food-insecurity posts from public Facebook pages (2020-2024) as compositions, apply a centered log-ratio transformation, and cluster them into four audience profiles: Solidarity (Love-dominant), Dismissal (Haha-dominant), Grief (Sad-dominant), and a flat Ambivalent profile. Dismissal peaks in 2022 (22.3%), the year of the wheat price shock, and grief in 2024 (14.0%), during the Gaza food emergency; a page-clustered GEE confirms both shifts (odds ratios 2.18 and 1.34), and they survive minimum-reaction filtering, alternative zero replacements and clustering methods, and bootstrap resampling. We then test whether the profiles can be predicted without reactions. A zero-shot Arabic LLM recovers Grief for 83.8% of posts but Dismissal for only 3.4%, and in a matched ablation, it shows the reaction percentages do not help. A simple classif

---

### [107] AppSci-Bench: Can LLMs Build AI Agents and Make Them Better?

**链接**: https://arxiv.org/abs/2611.25360
**作者**: Sanjari Srivastava, Manpreet Kaur, Cheng Chang, Sof\'ia Ram\'os Anton, Oumaima Essamadi, Rishu Garg 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used not only to power AI agents but also to build them. While many benchmarks assess the quality of LLM- powered agents, few ascertain how good LLMs are at building them. To this end, we introduce AppSci-Bench, where we construct a setting akin to how human Applied Scientists build agents for businesses - through eliciting task requirements from stakeholders, exploring the business's infrastructure, and scientifically improve the target agent by designing experiments and internal benchmarks. AppSci-Bench features seven realistic domains - five new ones (Slides Generation, Order-to-Cash, Compliance Review, Customer Call Insights, and CRM Insights) and two domains recast from tau3-bench (Yao et al., 2024; Shi et al., 2026b)(Airline and Banking) - each with a held-out evaluation suite customized for that task. We evaluate seven frontier models and find AppSci-Bench challenging: the best model, Claude Opus 5.0, only reaches a mean-minimum scor

---

### [108] AutoMaster: Autonomous Post-Training by Making the Same Model a Better Teacher

**链接**: https://arxiv.org/abs/2611.26510
**作者**: Guoxin Chen, Shuang Sun, Fanzhe Meng, Xinyu Tang, Ruihua Song, Wayne Xin Zhao
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Task success alone does not specify which behaviors post-training should reinforce. Even successful teacher trajectories can contain unsupported assumptions, unproductive repetition, or superficial verification. We propose Skill-FT (Skill-Guided Fine-Tuning), which uses natural-language skills to suppress undesirable habits and elicit underrepresented effective behaviors during teacher rollouts, then fine-tunes a target model on the resulting trajectories. We introduce AutoMaster, an autonomous post-training system in which an LLM agent develops these interventions through trajectory analysis, skill design, data selection, and feedback from rollouts and target-model evaluation. Across Terminal, Search, and software engineering tasks with 4B and 9B target models, AutoMaster improves mean performance over Vanilla SFT on successful unguided teacher trajectories by 1.42-8.99 percentage points, with the teacher, task pool, training set size, and SFT recipe held fixed. Together with the abla

---

### [109] The ROI of Small Examples: Optimizing In-Context Learning Under Token Budgets

**链接**: https://arxiv.org/abs/2611.24971
**作者**: Anxo Perez, Jorge Gab\'in, Javier Parapar
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context learning (ICL) improves large language model performance at inference time without updating model parameters. However, these gains are not free: in practical deployments, longer prompts directly increase inference cost and latency. Under a fixed token budget, prompt construction therefore becomes a resource-allocation problem. While prior work has often focused on how many examples to include in ICL, we study the complementary question of whether the available budget is better spent on a few long demonstrations or on a larger number of shorter ones. We study this aspect in question answering (QA), by organizing candidate demonstrations into length-based bins and constructing prompts from examples within the same length range under fixed budgets. Experiments on two QA benchmarks (\textit{Beat the AI} and \textit{Natural Questions}), using six instruction-tuned LLMs, show that shorter demonstrations are generally the most effective use of prompt space. This effect is especiall

---

### [110] DSFlow: A Neuro-Symbolic Data Workflow Agent with Statistical Diagnostic Guardrails

**链接**: https://arxiv.org/abs/2611.25111
**作者**: Junfeng Nie and Xiaohui Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data science workflows often require tools that presume non-trivial technical knowledge. Large language models (LLMs) reduce this barrier, but a gap remains between flexible general-purpose agents and statistically controlled pipelines. We introduce DSFlow, a LangGraph-based neuro-symbolic data-agent platform that combines reusable, LLM-selected skills with deterministic diagnostic guardrails. Skills provide extensible task knowledge. Symbolic validation can accept a proposed method, request clarification or replanning, override an unsuitable method, or supply a safe fallback. Regression and clustering case studies illustrate how DSFlow uses diagnostic evidence to correct method choices and documents those decisions in auditable reports.

---

### [111] Beyond Weight Updates: Evolving Agent Harnesses for Domain Specialization

**链接**: https://arxiv.org/abs/2611.25380
**作者**: BoHao Chen
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain specialization of LLM agents is usually framed as a weight-update problem: collect trajectories, run reinforcement learning (RL) or supervised fine-tuning (SFT), and deploy a new checkpoint. We study a complementary axis: evolving the \textbf{agent harness}---the system prompt, tool schemas, skill library, and planning scaffolding---while keeping the policy frozen. We cast harness evolution as an RL-style outer loop and instantiate it with GEPA, a reflective evolutionary optimizer. The resulting harness adapters require no GPU training, are loadable per vertical domain, and compose with weight-based RL. Experiments with Codev, a Claude Code-style coding agent, on SWE-bench Verified, OfficeBench, and Terminal-Bench show a consistent pattern: weight updates give the strongest single-path gains, harness evolution recovers most of those gains at a small fraction of the compute, and combining both paths is best overall. We also analyze a failure mode of SFT-based specialization---sho

---

### [112] The Price of an Explanation: What Demanding Verifiable Artifacts Costs, and What It Buys Back

**链接**: https://arxiv.org/abs/2611.25896
**作者**: Edgar A. Du\'e\~nez-Guzm\'an, Eduardo Due\~nez, Edgar Said Hernandez Sanchez, Suzanne Sadedin
**来源**: cs.AI cs.LG cs.NE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative models produce many candidate solutions but provide no intrinsic signal by which to rank them. One mitigation is to demand a \emph{verifiable artifact}: a program that can be executed against the available evidence. A common concern is that requiring executable verification incurs costs in both solution quality and computational budget. We measure these two costs on the $120$-task ARC-AGI-2 evaluation set. Demanding a verifiable artifact from an LLM reduced the score from $93$ to $68$ of $120$ tasks ($77\%$ to $57\%$). Of those $25$ tasks, $21$ were reached by no program-producing configuration we ran, at any budget, by sampling or by search; yet for $27$ of the $28$ tasks that only the answer-only arm solved, some program arm held a program that reproduced every demonstration and still failed the test. The bottleneck is obtaining an explanation that \emph{generalizes}, not finding one. A short evolutionary search over two already-sampled programs, at no additional model cos

---

### [113] Coordinated Use of Large Language Models in Academic Research

**链接**: https://arxiv.org/abs/2611.25502
**作者**: Vladislav Marinov
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study proposes a methodological framework for the coordinated use of multiple large language models in academic research. Its central argument is that involving more models does not in itself guarantee more reliable results; what matters is how cognitive and verification operations are organised. The framework is based on seven principles (procedural independence, functional allocation, the diagnostic value of divergence, the diagnostic value of convergence, external verification, proportionality of checking, and human epistemic responsibility) and sets out a non-linear multi-LLM protocol in which independently obtained results are compared, critically examined and, where necessary, verified against external sources. The approach is illustrated through real-world cases drawn from research practice. The study concludes that moving from a single language model to a coordinated multi-LLM process represents a change in the organisation of research, in which the researcher makes the fi

---

### [114] From Cases to Criteria: Reusing Evaluation Knowledge for Task-Specific Rubric Generation

**链接**: https://arxiv.org/abs/2611.25903
**作者**: Qiyan Deng, Long-Kai Huang, Kangfei Zhao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Query-specific rubrics make LLM evaluation more fine-grained and transparent, and generating high-quality rubrics requires both identifying the target query's evaluation scope and specifying concrete checks. Historical rubrics provide reusable evaluation experiences, yet existing approaches reuse either complete query-rubric cases or aggregated criteria and dimensions without explicitly connecting recurring evaluation requirements to their criterion-level evidence and source-query context. This can preserve irrelevant task details or lose the broader evaluation structure. In this paper, we introduce RubricDuo, which organizes historical query-rubric pairs into a Rubric Knowledge Graph linking evaluation dimensions, shared concepts, local concepts, criteria, and queries, where reusable evaluation requirements across queries are abstracted by shared concepts. Given a target query, RubricDuo first combines concepts relevant to the target query with retrieved historical cases to draft a ru

---

### [115] ReflectScene:MLLM-Guided Closed-Loop Diffusion for 3D Indoor Scene Generation

**链接**: https://arxiv.org/abs/2611.23845
**作者**: Jiawei Shen, Jie Feng, Junpeng Zhang, Guanbin Li, Wanyi Chen, Weisheng Dong 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] HOPD: Historical On-Policy Distillation for SAR MLLM Continual Learning

**链接**: https://arxiv.org/abs/2611.25391
**作者**: Yuxuan Li, Derrick Goh Xin Deik, Zheng-Peng Duan, Qianru Sun, Weijie Li
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual SAR interpretation requires multimodal large language models to learn incoming sources while retaining earlier task abilities. This is difficult when acquisition and geographic shifts alter visual evidence, regionally concentrated categories bias answers, and historical images are scarce. We address this problem with Historical On-Policy Distillation (HOPD), which reuses source-acquisition LoRA states as persistent teachers for one evolving student. Archiving each state before consolidation preserves a stable source reference. The teachers supervise student-generated prefixes, transferring historical behavior to the student's changing generation contexts. To enrich sparse replay, original-view teachers guide augmented historical student views while preserving spatial coordinates. This knowledge is consolidated into a single deployed adapter that requires no source identity. On SARVQA-CL, our source-incremental evaluation protocol, HOPD achieves the highest final mean score of

---

### [117] EVIDENT: Routing MLLM Adaptation through Entity-Grounded Visual Evidence for Cross-Domain Video Temporal Grounding

**链接**: https://arxiv.org/abs/2605.26104
**作者**: Geo Ahn, Jiwook Han, Youngrae Kim, Joonseok Lee, Jinwoo Choi
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [118] SEAF: Selective Semantic Enrichment and Visual Evidence Fusion for Multimodal Sarcasm Detection

**链接**: https://arxiv.org/abs/2611.25672
**作者**: Faxian Wan, Xiaocui Yang, Yifan Cao, Shi Feng, Daling Wang, Yifei Zhang
**来源**: cs.CV cs.CL
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal sarcasm detection requires textual, visual, and contextual evidence, particularly when multiple images provide complementary cues. Multimodal large language models (MLLMs) can generate auxiliary information from a post's text and images, but their outputs may mix useful background knowledge with redundant visual descriptions. We propose SEAF, a dual-branch framework for selective semantic enrichment and visual evidence fusion. SEAF assigns generated fields to distinct roles: entity background enriches semantic input, while image descriptions supply alignment statistics. The semantic branch combines the original post text, background from a frozen MLLM, and optical character recognition (OCR) text. The aligned visual branch combines global and local visual features with statistics of cross-modal and inter-image similarity. Text-Anchored Smoothed Aggregation (TASA) weights images by their similarity to the original post text while preserving contributions from images with low 

---

### [119] When Should Deployed BCI Decoders Adapt? A Resource-Priced Ladder for Frozen EEG Trunks

**链接**: https://arxiv.org/abs/2611.25315
**作者**: Sergey Musienko
**来源**: cs.HC cs.LG q-bio.NC
**匹配关键词**: EEG, BCI
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [120] Disentangling Monitor Hardware Artifacts and Smoothing Lag for Shift-Robust Intraoperative EEG and Hemodynamic Risk Calibration

**链接**: https://arxiv.org/abs/2611.25765
**作者**: Zeyu Jia
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Commercial intraoperative electroencephalography (EEG) and blood pressure monitors introduce cyclic impedance pulses, smoothing delays, direct-current (DC) drift, and cuff holds that confound risk forecasting and uncertainty calibration. We developed a causal signal-conditioning and shift-robust conformal calibration framework across 5,439 public anesthesia procedures. Streaming filters blank 10.13-min 64-Hz impedance checks, apply unclipped post-notch conditioning, separate 63-s suppression-ratio lag, and distinguish three-channel cuff inflations from dropouts across propofol-remifentanil total intravenous anesthesia (TIVA; N = 3,214), volatile anesthesia (N = 2,046), European endoscopy sedation (N = 171), and DC-coupled surgery (N = 8). De-impedanced cortical tree ensembles were compared against deep sequence models, paired with patient-cluster Subgroup-Covariate-Weighted Conformal Risk Control (CRC) and lag-buffered online Conformal Proportional-Integral-Derivative (PID) tracking. P

---

### [121] BrainPro: Process-conditioned Pretraining with Topographic Retrieval for Large EEG Models

**链接**: https://arxiv.org/abs/2509.22050
**作者**: Yi Ding, Muyun Jiang, Weibang Jiang, Shuailei Zhang, Xinliang Zhou, Chenyu Liu 等 (9 人)
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] Introducing ReTiNA-Cinema: Real-Time Neuro-Augmented Cinema via Generative AI

**链接**: https://arxiv.org/abs/2611.26469
**作者**: Antoine Bellemare-Pepin, Philipp Th\"olke, Yann Harel, Mar Estarellas, Karim Jerbi
**来源**: cs.HC
**匹配关键词**: EEG
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative artificial intelligence (AI) is currently revolutionizing content creation across various media. Between those who fear it will replace human creativity and those who regard it solely as a tool, many in the creative industries are beginning to view generative AI as a collaborator. Yet interaction with these systems often relies on discrete, turn-based prompting that can interrupt flow and constrain expression to symbolic text. We explore physiological signals as a source of continuous adaptation without explicit commands, as a path toward embodied co-creation. This paper presents ReTiNA-Cinema, a methodological proof-of-concept that integrates electroencephalography (EEG) with generative AI to enable physiologically guided visual modulation of cinematic material. By linking physiological activity to the evolving appearance of a film, the system provides a basis for exploring embodied sense-making, in which viewers' bodily responses contribute to shaping the sensory experienc

---

### [123] A Verifier from the Past: Test-Time Compute for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2611.25171
**作者**: Arjun Choudhry, Aditya Narayanan, Raghav Mallampalli, Po-han Li, Sai Shankar Narasimhan, Raimi Shah 等 (8 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Test-time compute (TTC) improves language models by spending additional inference compute to generate, verify, and select among candidate outputs, but this recipe has not transferred directly to time series forecasting. A language model can verify a proof or vote across samples, but a forecaster must be causal; it cannot use future information to score a candidate. We propose Backtest-Gated Augmentation Averaging (BGAA), a TTC algorithm for time series forecasting that builds a causal verifier from the series's own history, using rolling-origin backtests to score structured views of the context, discard those that underperform the untransformed context, and average the survivors' predictive distributions. BGAA improves every tested TSFM-benchmark combination, reducing MASE by 0.5-1.0% on GIFT-Eval, 1.3-5.0% on fev-bench, and 1.7-5.9% on BOOM, where a 313M model with TTC outperforms the 1B and 2.5B models in its family. We further show that useful views have structured, model-dependent 

---

### [124] Physics-Informed Feature Representations and Pretrained Tabular Foundation Models for Generalizable Melt Pool Geometry Prediction

**链接**: https://arxiv.org/abs/2611.26235
**作者**: Rafid Enayet (1), Imtiaz Ahmed (2), Md Habibor Rahman (1) ((1) University of South Carolina, (2) West Virginia University)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Developing generalizable, data-efficient machine learning (ML) models for advanced manufacturing remains challenging because experimental datasets are limited and process-property relationships vary across materials and operating conditions. In laser powder bed fusion (LPBF), melt pool width, depth, and melting mode (conduction, transition, or keyhole) govern process stability and defect formation. Conventional ML models typically use dimensional process parameters, which represent laser-material interactions only implicitly and may limit cross-material transfer. This study evaluates whether two physics-informed dimensionless features, normalized enthalpy and Peclet number, combining laser processing conditions with material thermophysical properties, improve melt pool prediction over raw process parameters. We systematically benchmark seven models: four classical ML methods (Gaussian process, support vector machine, random forest, and XGBoost) and three pretrained tabular foundation m

---

### [125] Kandinsky 6.0 Video: Foundation Models for Synchronized Video and Audio Generation

**链接**: https://arxiv.org/abs/2610.05608
**作者**: Team Kandinsky, Julia Agafonova, Bulat Akhmatov, Mikhail Aksyutin, Grigorii Alekseenko, Anastasia Aliaskina 等 (10 人)
**来源**: cs.CV cs.AI cs.LG cs.MM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [126] From field-scale to large-scale spectral libraries: Tabular foundation models in soil spectroscopy

**链接**: https://arxiv.org/abs/2608.00608
**作者**: Viacheslav Barkov, Jonas Schmidinger, Robin Gebbers, Martin Atzmueller
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [127] Mammography Foundation Models for Opportunistic Prediction of Major Adverse Cardiovascular Events

**链接**: https://arxiv.org/abs/2609.19385
**作者**: Paula Feldman, Nusrat Binta Nizam, Sunwoo Kwak, Batuhan Karaman, Katerina Dodelzon, Mert Sabuncu
**来源**: eess.IV cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] Are Vision Foundation Models Foundational for Electron Microscopy Image Segmentation?

**链接**: https://arxiv.org/abs/2602.08505
**作者**: Caterina Fuster-Barcel\'o, Virginie Uhlmann
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [129] How Well Do Segmentation Foundation Models Generalize Across Structural and Functional Medical Imaging?

**链接**: https://arxiv.org/abs/2602.07643
**作者**: Yichi Zhang, Le Xue, Feiyang Xiao, Wenbo Zhang, Gang Feng, Chenguang Zheng 等 (9 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [130] Prediction with Foundation Models under Deployment Budgets

**链接**: https://arxiv.org/abs/2611.12466
**作者**: Zhaohui Xu, Xiaofei Xu, Doudou Zhou
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [131] When Foundation Models Disagree: Representational Heterogeneity for Calibrated Uncertainty in Whole-Slide Image Classification

**链接**: https://arxiv.org/abs/2611.26159
**作者**: Yekai Shen, Yuqian Wang, Zishun Liao, Rongsheng Wang, Wenting Chen, S. Kevin Zhou 等 (7 人)
**来源**: cs.CV q-bio.QM
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models supply strong representations for whole-slide image classification, yet the confidence attached to their predictions remains hard to trust. Prevailing uncertainty estimators act within a single feature space and thereby overlook the uncertainty that the choice of foundation-model representation itself induces. This work introduces CALIFUSE, a calibration-oriented framework that fuses several pathology foundation models for the specific purpose of uncertainty estimation. Departing from accuracy-driven fusion, CALIFUSE reads representational heterogeneity across encoders as an explicit confidence cue. Slide-level decision consensus is coupled with chunk-level evidence agreement quantified through Jensen-Shannon divergence, so that both prediction stability and fine-grained evidence consistency inform the estimate. Foundation-model encoders stay frozen. A task-specific nnMIL classifier is still trained for each FM; CALIFUSE then estimates confidence at inferenc

---

### [132] Trajectory-Calibrated Merging of Embodied Policies

**链接**: https://arxiv.org/abs/2611.25575
**作者**: Wenshuo Chen, Honglei Jin, Le Yang, Jianfei Song, Shaofeng Liang, Lei Wang 等 (10 人)
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot foundation models are increasingly adapted into task specialists to expand their embodied capabilities. Yet these capabilities remain fragmented across separate policies, and existing model-merging methods do not reliably preserve them during closed-loop execution: parameter-space alignment provides only an indirect proxy for behavior, while regression may fail to preserve behavior at states not covered by its calibration inputs. We present Trajectory-Calibrated Regression (TCR), an execution-aware, gradient-free framework that consolidates robot specialists into a single policy. Across two complementary timescales, TCR collects calibration inputs from expert rollouts spanning different stages of task execution and from intermediate states within iterative action generation. To account for representation shifts introduced by merging, TCR recomputes each block's input through the already merged blocks. It then uses each expert's computation within the block to form module inputs a

---

### [133] WeMM-Video: Pushing the Frontiers of Open-Source Omni-Modal Video Understanding

**链接**: https://arxiv.org/abs/2611.26409
**作者**: Changli Tang, Jie Yang, Tianyi Wang, Lei Li, Daoze Zhang, Zijie Xin 等 (10 人)
**来源**: cs.CV eess.AS
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Video understanding, particularly with accompanying audio, remains a central challenge in multimodal intelligence. In this report, we introduce \textbf{WeMM-Video}, a family of Chinese-English bilingual omni-modal foundation models spanning 2B, 4B, 9B, and 35B-A3B variants. Centering on joint audio-visual perception and reasoning, WeMM-Video unifies text, image, audio, and video processing within a hybrid-thinking paradigm, seamlessly supporting both a non-thinking instruct mode for fast, direct responses and a thinking mode for explicit step-by-step reasoning. The models are trained on a large-scale multimodal corpus of approximately 1.2 trillion tokens through progressive pre-training and a multi-stage post-training pipeline incorporating multi-teacher OPD, anti-repetition MrDPO, and specialist RL. Evaluated across more than 120 benchmarks, WeMM-Video demonstrates superior performance in omni-modal video understanding and reasoning, while maintaining highly competitive capabilities a

---

### [134] C-LiTE: A Lightweight Foundation Model for Cellular feature learning in Histopathology

**链接**: https://arxiv.org/abs/2611.26316
**作者**: Esha Sadia Nasir, Jiaqi Lv, Gozde N. Gunesli, Shan E Ahmed Raza
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Characterising individual cells is fundamental to computational pathology, as cellular morphology informs tasks such as tumour grading, mitotic assessment and immune profiling. However, most pathology foundation models are trained on tissue patches and capture cellular features only implicitly, while existing cell-level models are either restricted to specific cell populations or rely on computationally expensive architectures with hundreds of millions of parameters. Applying ViTs directly to small cellular crops also presents an architectural challenge: upsampling increases computational cost without adding morphological information and may introduce interpolation artefacts. To address these limitations, we introduce C-LiTE, a lightweight foundation model for cellular representation learning in H&E-stained histopathology, with only 22 million parameters. C-LiTE employs a native-resolution tokenisation strategy tailored to cellular inputs, processing 64 x 64 px cell-centred crops using

---

### [135] From Sequence Uncertainty to Phenotype Hypotheses: Uncertainty-Conditioned Inference over Biomedical Knowledge Graphs

**链接**: https://arxiv.org/abs/2611.25422
**作者**: Huixin Zhan and Jason H. Moore
**来源**: cs.LG q-bio.GN
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Genomic foundation models provide variant-level evidence, but connecting that evidence to phenotype hypotheses requires accounting for uncertainty throughout structured reasoning. We introduce an uncertainty-conditioned path-energy framework that converts sequence predictions and calibrated predictive uncertainty into explicit distributions over graph-supported phenotype hypotheses, without patient-level phenotype supervision. An interpretable learned energy scores admissible gene--disease--phenotype routes, query uncertainty controls the target temperature, and path probabilities are aggregated into phenotype hypotheses. This formulation makes evidence quality an explicit determinant of hypothesis breadth while retaining traceable multi-path support. Exact normalization over enumerable candidate sets provides a reference for evaluating a Hastings-corrected learned revision operator. On AlzKB and Hetionet, phenotype-level entropy tracks upstream uncertainty, with Spearman correlations 

---

### [136] Does It Depend on the Split? Frozen Satellite Features vs. Fine-Tuned CNNs for Tree Species Mapping

**链接**: https://arxiv.org/abs/2611.25902
**作者**: Dharani Deivasihamani and Nandakishore Puttashamachar
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-supervised foundation models are often said to need fewer labels than supervised training. We test this on a forestry task: classifying 20 tree species classes in 0.2 m aerial images from the TreeSatAI dataset. We compare a frozen DINOv3 model pretrained on 493 million satellite images, with only a linear classifier trained on top, against an ImageNet ResNet-50 that is fine-tuned end to end. On the official split, fine-tuning wins clearly (macro F1 0.764 vs. 0.685). However, 28.8% of the official test patches overlap a training or validation patch, and copying the label of the nearest such patch is correct for 83.6% of them. We therefore build a spatial split that holds out whole 2 km squares with a 200 m buffer. On this split the comparison becomes inconclusive (0.648 vs. 0.640, paired 95% CI of the difference [-0.054, 0.016]), and the learning curves of the two models overlap at every label budget from 343 to 33,126 training patches. On the five rarest classes, the frozen model 

---

### [137] Explainable AI for Solar PV Power Forecasting: From Model Selection to Trustworthy, Reproducible Deployment

**链接**: https://arxiv.org/abs/2611.25894
**作者**: Nuzhat Khan, Muhammad Paend Bakht, Ab Al-Hadi Ab Rahman, Fabiano Pallonetto, Amy Fahy, Mohamed Khalafalla Hassan 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine learning (ML) is now a standard tool for forecasting the output of solar photovoltaic (PV) plants, yet published accuracy figures are often hard to compare and harder to trust. Many studies validate with random splits, report no reference forecast, and present feature attributions without saying what they can and cannot show. This paper reviews the main families of ML methods for PV power forecasting and resource assessment, from tree ensembles to deep and foundation models, and sets out a reproducible workflow that combines automated model search with explainable AI. The workflow is then tested on an openly available dataset: a 16.32 kWp plant in Porto, Portugal, forecast one day ahead from a 4 km numerical weather prediction grid. Over a full test year, the best models reach a normalised root mean square error (nRMSE) of 11.6% of installed capacity, about half the error of smart persistence. The choice of input features changed accuracy far more than the choice among strong a

---

### [138] Asuka-FM: A System-Architectural Co-Design Framework for Efficient Text-to-Image Pretraining on Consumer Hardware

**链接**: https://arxiv.org/abs/2611.26437
**作者**: V\'ictor Rodrigo Gonz\'alez, Pablo M. Olmos, Ignacio Peis, Alejandro Lancho
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier text-to-image (T2I) foundation models predominantly rely on multi-billion parameter Diffusion Transformers (DiTs) pretrained across massive compute clusters, creating an accessibility barrier for academic laboratories. When training DiTs from scratch on single consumer GPUs (e.g., an NVIDIA RTX 4090 with 24\,GB VRAM), practitioners encounter three primary bottlenecks: quadratic attention sequence costs, Just-In-Time (JIT) compilation graph breaks induced by variable aspect-ratio bucketing, and an autoencoder throughput wall where frozen Variational Autoencoder (VAE) operations dominate step latency. In this work, we introduce \textbf{Asuka-FM}, an end-to-end system and architectural framework demonstrating that competitive dual-stream DiTs ($\sim$206M parameters) can be pretrained from scratch on a single consumer GPU in $\sim$160 GPU hours for under \$55. Asuka-FM integrates four core designs: (i) an AdaLN-free dual-stream DiT backbone reducing parameter count; (ii) structure

---

### [139] EgoPass-Bench: Identifying Objects That May Affect the Wearer's Passage in Egocentric Video

**链接**: https://arxiv.org/abs/2611.24995
**作者**: Hongyu Wang, Chuhan Li, Congjin Xu, Xuandong Zhao, Hua Shen
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding an egocentric environment requires reasoning about how surrounding entities affect the observer's actions. Existing evaluations of multimodal foundation models (MFMs) examine observer localization, motion trajectories, and action feasibility, but leave the discovery and interpretation of evolving observer-entity interactions insufficiently assessed. We introduce EgoPass-Bench, a benchmark for observer-relative interaction understanding in real-world egocentric video. EgoPass-Bench comprises 284 manually reviewed evaluation clips recorded using Ray-Ban Meta (Gen 2) smart glasses and 2,201 distinct questions across five tasks assessing motion perception, interaction judgments about specified entities, and relevant-entity discovery without target cues. Our evaluation of eight frame-based and six native-video configurations reveals a pronounced discrepancy between motion perception and interaction understanding. The strongest evaluated model, GPT-6 Astra, correctly recognizes

---

### [140] Erasing the Wrong Thing: Conditional Attribute Leakage and Concept Erasure in Shared Foundation-Model Embeddings

**链接**: https://arxiv.org/abs/2611.25640
**作者**: Haijun He, Fei Li, Donghong Ji, Junjun He
**来源**: cs.CR cs.AI cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical-image embeddings are increasingly shared in place of raw images for authorized downstream tasks, yet they may reveal sensitive attributes. Standard concept-erasure methods target population-level guardedness. However, we prove that, when binary task and sensitive labels are associated, global and task-conditional linear guardedness cannot both hold while a nonzero linear task signal is preserved, so global erasure must either eliminate that signal or retain task-conditional linear leakage. We further show how global erasure affects linear readers' discrimination between positive and negative samples with different sensitive attributes, deriving an approximate closed-form prediction of its utility cost from pre-erasure statistics. Motivated by this conflict, we introduce Task-Conditional LEACE (TC-LEACE), a closed-form variant of LEACE that enforces linear guardedness within each task stratum of its fitting data. We evaluate four vision foundation models on 85 CelebA attribute p

---

### [141] Falsifiable Compositional Reasoning in Time Series Forecasting

**链接**: https://arxiv.org/abs/2611.25388
**作者**: Hao Xue
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time series foundation models as well as the language-guided analytical agents achieve strong accuracy on standard chronological benchmarks. However, models that rank highest on historical validation splits often degrade across non-stationary regime transitions. We hypothesise that this gap arises from using historical backtesting as an open-ended search and model-selection objective instead of using it to test pre-specified compositional assumptions. Real-world time series are generated by recurring latent primitives that co-move within finite historical windows. Under strong historical co-movement, chronological holdout error cannot separate predictors that learn invariant couplings among primitives from predictors that fit transient historical correlations. Searching over large pools of architectures, hyperparameters, or chain-of-thought rules further biases selection toward historical shortcuts. Through theoretical analysis and diagnostic experiments on a controlled multi-primitive

---
