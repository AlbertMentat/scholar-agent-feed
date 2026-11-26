# 📑 论文索引 - 2026-11-27

共 183 篇论文

---

### [1] Dynamic Reasoning in Next-Gen Detection and Response: An Empirical Study of LLM Triage, Reinforcement Tuning, and Adversarial Evasion

**链接**: https://arxiv.org/abs/2611.33470
**作者**: Jeremy Canale
**来源**: cs.AI cs.CR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present an end-to-end empirical study of dynamic reasoning in next-generation detection and response pipelines, evaluating how static classifiers, graph-based signal fusion, and large language model (LLM) triage agents perform under strict human-analyst attention budgets (Recall at B alerts/day). Across 56 reproducible experiments spanning a multi-layer enterprise-and-cloud simulator and four public datasets (SOREL-20M, BODMAS, LANL, and DARPA Transparent Computing), we test twelve architectural claims governing modern fleet-scale defense. First, we show that fleet growth halves recall at a fixed analyst budget even at negligible compute cost (<$0.0003 per million events), and that rarity-weighted graph risk propagation outperforms GraphSAGE without neural training. Second, evaluating frontier reasoning models (Gemini) and fine-tuned open-weight models (Qwen3-4B) for alert triage reveals that unconstrained LLM auto-closure eliminates 90% of false positives while silently discarding 

---

### [2] Real-time Food Recipe Generation with Mobile Deep Learning and Large Language Model

**链接**: https://arxiv.org/abs/2611.33177
**作者**: Wei Jun Leung, Mun Hong Lee, Joo Wee Quek, Desmond Loy, Yifei Wang, Yan Ning Ang 等 (9 人)
**来源**: cs.MM cs.CV eess.IV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Finding recipes that match available kitchen ingredients can be cumbersome and inefficient. This paper addresses this challenge by developing a mobile application that generates tailored food recipes based on ingredients identified using a mobile camera. Leveraging deep learning and large language model (LLM), our system offers a seamless and efficient solution for real-time recipe generation. By integrating deep learning for accurate ingredient recognition with LLM for generating detailed and practical recipes, our approach ensures users receive precise cooking instructions based on actual ingredients on hand. Extensive dataset augmentation and model training have resulted in a robust system capable of high performance. Experimental results demonstrate that EfficientNet, used for food recognition, offers a balance of accuracy and computational efficiency, making it ideal for mobile applications. This dual-approach method enhances the cooking experience, reduces food waste, and provide

---

### [3] Can Its Own Misses Teach an MLLM to Find Small Brain Metastases?

**链接**: https://arxiv.org/abs/2611.33836
**作者**: Yixuan Duan, Kexin Geng, Hanwen Xu, Wei Qiu
**来源**: cs.AI
**匹配关键词**: LLM, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are becoming general readers of medical images, yet they remain weak at locating small abnormalities. Brain metastases expose this gap: at 384 px a 0.1 mL lesion covers less than a quarter of one visual token, and at one false positive per scan frontier MLLMs find fewer than 30% of lesions of 0.1-1 mL. Fine-tuning on one dataset helps but transfers poorly, and improving it further is slow trial and error steered by a single score. We introduce LANTERN (Lesion-finding AgeNt Through Error-driven Recursive learNing), a framework in which an MLLM improves recursively from its own misses. LANTERN recasts model development as an error-driven loop: a failure census attributes every missed lesion to one of four causes, an LLM mentor revises one of four levels (evidence acquisition, visual representation, learning policy, decision aggregation) per round, and a rule frozen before the first round decides what is kept, without test data and with every tool 

---

### [4] What Is a Theory Worth to an LLM Solver? Measuring, Inducing, and Merging Theories in Context

**链接**: https://arxiv.org/abs/2611.34751
**作者**: Jun Gao, Shuchao Bi
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mathematicians solve problems faster when they know the right theory. We ask how much a stated theory is worth to a large language model (LLM) solver, and whether a model can write that theory itself. In a length-matched protocol, adding the right theory to the context of Qwen3-14B raises pass@1 on pattern waiting-time problems from 0.37 to 0.83 and cuts the median tokens of correct solutions from 10.2k to 6.3k, while worked examples of the same length do not help. The gain shrinks as the solver and its token budget grow (+0.46, +0.26, +0.07), and at a long budget it comes almost entirely from finishing within budget: solutions that finish are correct 98--100\% of the time in every condition. To separate induction from recall, we plant unpublished theorems in custom probability families and measure how much of the oracle theory's gain an induced theory recovers. A strong open model, required to explore the training problems with code before writing, recovers 60\% of the gain on one pla

---

### [5] Automating Multi-View Quality Assessment of 3D Annotation Layouts

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.27621&hl=zh-CN&sa=X&d=14814037026037303725&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv55NpvRBChbGvz2_mBgdCBC&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=2&folt=kw-top
**作者**: H Yang, J Wu, Y Zhang, S Fu, H Ling, B Huang 等 (8 人)
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> To address these issues, we propose a multi-view quality assessment method based on a multimodal large language model ( MLLM ). We fine-tune a compact MLLM … Motivated by these observations, we propose an MLLM based method for

---

### [6] Fine-Tuning Without Gradients? Closed-Form, LLM-Written Classifiers on a Frozen Encoder

**链接**: https://arxiv.org/abs/2611.33972
**作者**: Md Nasir Uddin, Musa Tur Farazi, Soumik Bhattacharjee, Tishna Sabrina, Chowdhury Mohammad Rakin Haider
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Can a classifier computed in closed form on a frozen encoder match gradient fine-tuning? We present closed-form weight-space programming (WSP): a large language model (LLM), used as a design assistant, writes programs that read a frozen masked language model through cloze-style prompt templates at several layers, fit closed-form heads (shrinkage discriminant analysis, kernel ridge regression and the encoder's label-word prior) on labelled data, and select among a pool of candidate heads by cross-fitting. No gradient is computed and no encoder weight changes. We instantiate the framework on RoBERTa-large. On 11 development datasets with 512 to 8,192 training labels, WSP is ahead of full fine-tuning (FT) and LoRA at every label budget (by 0.3 to 0.6 points on average; the registered non-inferiority tests pass) and within 0.5 points of prompt-based fine-tuning (PFT); these datasets also shaped the recipe. With fewer labels its lead over FT and LoRA grows: 1.2 to 3.5 points with 64 and 128

---

### [7] 3D Open-Vocabulary Detection via Visual Alignment and Generative Captions

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.26842&hl=zh-CN&sa=X&d=1666303950613038842&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv6ZuCnOcqw14xUyyAm1bS1n&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=7&folt=kw-top
**作者**: TE Huang, AZ Zhu, H Xiang, T Cai, J Ji, Y Zou 等 (8 人)
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> We leverage a powerful Multimodal Large Language Model ( MLLM ) as an image captioner and domain adapter. Using the same DBSCAN-… 2) We propose a Language Alignment strategy that uses an MLLM to generate high-fidelity

---

### [8] BayesPath: Reliability-Aware Bayesian Reasoning for Whole-Slide Pathology Agents

**链接**: https://arxiv.org/abs/2611.33935
**作者**: Bryan Wong, Xun Xu, Jongwoo Kim, Huazhu Fu, Nancy F. Chen, Mun Yong Yi
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model, MLLM
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Diagnosing whole-slide images (WSIs) requires hypothesis-driven reasoning: pathologists form a differential diagnosis, seek discriminative evidence, weigh its reliability, and stop once it suffices. However, existing training-free WSI agents lack an explicit framework for such reasoning. They typically use a large language model (LLM) to aggregate the region descriptions of a multimodal LLM (MLLM), without a belief over the candidates or regard for the descriptions' reliability. Consequently, a repeated model error counts as independent evidence for an incorrect diagnosis. We introduce BayesPath, a training-free WSI agent that casts the pathologist's Scan-Look-Weigh-Decide process as reliability-aware Bayesian reasoning. An explicit belief over the candidates is updated with each observation through a reliability-aware likelihood and guides where to look next and when to stop. This likelihood corrects for the models' answer bias, discounts correlated observations, and captures diagnost

---

### [9] PowerFix: Physics-Guided Iterative Repair for LLM-Assisted Power Converter Design

**链接**: https://arxiv.org/abs/2611.33712
**作者**: Can Wang, Shi Qiu, Fanfan Lin
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are increasingly being explored for automated engineering design. However, repairing power-converter designs that fail engineering validation remains challenging: the system must identify physical causes, locate responsible design variables, and resolve violations without compromising other constraints. We introduce PowerFix, a physics-guided iterative repair framework that converts validation failures into structured diagnoses and executable patches while preserving topology and design requirements. PowerDiagGraph links failed checks to possible physical causes and constrains repair routes. An LLM prioritizes these routes, while a deterministic compiler translates selected repairs into authorized field-level edits. Candidates are validated on isolated design copies and committed only after all required engineering checks pass; failed validation can guide replanning. On our constructed 96-task flyback repair benchmark, comprising injected single faults

---

### [10] Evaluating Autonomous Online Survey Completion Using a Locally Deployed LLM Agent on Consumer-Grade Hardware

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2949882126001878&hl=zh-CN&sa=X&d=18437792875246423233&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv5UBqIun9ckGNfeTiET90A9&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=6&folt=kw-top
**作者**: PDNC Ohalete - Computers in Human Behavior: Artificial Humans, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> Autonomous large language model ( LLM ) agents present opportunities for survey research and risks to data integrity, yet the mechanisms enabling independent survey completion remain poorly documented. This study investigates whether an

---

### [11] Routeability Before Routing: Routeability Audit Protocol (RAP) and RouteabilityBench for Audited LLM Model Selection

**链接**: https://arxiv.org/abs/2611.34825
**作者**: Yihang Lu, Denica Kjorvezir, Ana Gjorgjevikj, Carola Doerr, Tome Eftimov
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM routing aims to choose, for each prompt, which model in a portfolio is most likely to answer correctly. This only makes sense when the benchmark contains enough prompt-specific variation for different models to be best on different inputs. On coarse-scored LLM benchmarks, however, many models often tie for the best score, and the single best model may already leave little room for improvement. We therefore propose a routeability-first audit, instantiated as RAP and RouteabilityBench, a runnable claim-verification package. The audit is retrospective: it runs once the benchmark-portfolio score matrix exists and before router comparisons are interpreted as general evidence, rather than certifying a portfolio that has not yet been evaluated. Across four benchmarks and 66 LLMs, generic routing enhancements such as larger embedding sets, dimensionality reduction, selective abstention, clustering, and stronger regressors do not consistently outperform the single best model. The clearest p

---

### [12] PatternMiner: Automated Mathematical Discovery Through LLM-Guided Training and Interpretation of Small Models

**链接**: https://arxiv.org/abs/2611.33966
**作者**: Michael Ruofan Zeng, Junaid Hasan, Xuanyu Yang, Emily Xia Meng, Henry Kvinge
**来源**: cs.AI math.CO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> There are several approaches to AI-driven mathematical discovery. One of these involves the use of large language models (LLMs) to resolve well-specified conjectures via text-based reasoning, while another uses narrow models and interpretability for more open-ended, human-in-the-loop exploration using object-based mathematical data. The latter is limited in its ability to move beyond simple empirical pattern detection while the former is not well-designed for direct, open-ended exploration of large mathematical datasets. In this paper we introduce PatternMiner, a system that combines these two paradigms. In PatternMiner, an LLM agent generates mathematical datasets based on an initial broad question, trains narrow machine learning models on them, uses interpretability techniques to extract patterns from these trained models, and uses these patterns to formulate conjectures. Once an initial conjecture has been formulated, PatternMiner instructs the agent to search for counterexamples us

---

### [13] Interactive Proofs as a Unified Framework for Evaluating and Leveraging Verifiable Proof Generation by LLM Agents

**链接**: https://arxiv.org/abs/2611.33676
**作者**: Yankai Shu, Xingyu Zhao, Chuan Mao, Congchi Yin
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in LLM-assisted theorem proving and program verification have attracted widespread attention. Beyond determining whether a proposition is true, LLM agents must produce evidence that can be independently checked by humans or formal verification tools. To evaluate the underlying, protocol-agnostic ability of LLM agents to construct verifiable proofs-rather than their proficiency with any particular proof language or verification tool, we introduce Merlin-Bench. Drawing on interactive proof systems from computational complexity theory, we cast an LLM agent as the prover: under a designated protocol, the agent interacts with a formal verifier to substantiate its claimed answer to a problem instance. We develop an automated framework for constructing test cases and use it to create 100 cases across 15 problem families, each formulated within this prover-verifier framework. Experiments with 10 frontier LLMs across multiple agent harnesses show that reliably producing verifiab

---

### [14] Deletion You Can Check: Auditing LLM Unlearning

**链接**: https://arxiv.org/abs/2611.33525
**作者**: Mayank Gulati and Gerhard Wunder
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A common indication that a fine-tuned model has forgotten a deleted record is a membership-inference score near chance (ROC-AUC $\approx 0.5$). This reading is sound only if the comparison population represents how the record should behave after a valid deletion---a counterfactual that is rarely validated. We test this premise in a controlled $2\times2$ study pairing two membership-inference benchmarks, ArxivMIA and BookMIA, with two language models, Llama-3.2-1B and Qwen2.5-1.5B. Exact retraining validates the membership reference: it lies within the prespecified chance band on ArxivMIA but reaches $0.122$ on BookMIA, causing the same metric to reject an empirical deletion reference. A post-hoc BookMIA/Qwen diagnostic replaces benchmark label-0 records with same-pool, never-fine-tuned records and moves the reference from $0.257$ to $0.523$, supporting population mismatch in that cell. Each approximate-unlearning checkpoint is judged jointly on membership removal, deletion-targeted shi

---

### [15] United in Diversity? Contextual Biases in LLM-Based Predictions of the 2024 European Parliament Elections

**链接**: https://arxiv.org/abs/2409.09045
**作者**: Leah von der Heyde, Anna-Carolina Haensch, Alexander Wenz, Bolei Ma
**来源**: cs.CY cs.AI cs.CL stat.AP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [16] JHealthBench-L: Clinician-Reviewed Localization of HealthBench for Rubric-Based Medical LLM Evaluation in Japan

**链接**: https://arxiv.org/abs/2611.34024
**作者**: Shohei Hisada, Keisuke Orimo, Kenji Igarashi, Kota Sato, Masahiro Kazama, Mitsuhisa Ota 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubric-based benchmarks such as HealthBench evaluate large language models (LLMs) on open-ended health consultations using case-specific physician criteria, many of which presuppose the healthcare institutions, medications, and care pathways of their source region. Under machine translation alone, these regional assumptions remain in the rubric, leaving responses appropriate in Japan uncredited or falsely penalized under foreign clinical rules. To adapt established clinical evaluation perspectives to Japan without authoring rubrics from scratch, we construct JHealthBench-L (79 patient-facing consultations, 1,022 criteria) through source-cited LLM drafting, single-specialist selection and revision, independent dual-physician review, and meta-review. Specialists rewrote only 4.4% of criteria from scratch, and independent reviewers approved 93.6% of Stage-2 criteria without issue. Comparing JHealthBench-L with a machine-translated baseline across 18 LLMs reveals that translation-only eval

---

### [17] Bias Cascade: Understanding the Gap Between Knowledge Alignment and Effect Replication in LLM-based Social Simulation

**链接**: https://arxiv.org/abs/2611.28854
**作者**: Pujun Zheng, Chengmu Wang, Wanying Ren, Jiacheng Yao, Peizhou Yu, Xiaoqian Zhang 等 (8 人)
**来源**: cs.CY cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [18] Knocking on Minds Door; A Mixed-Methods Field Study of a Voice LLM Companion in Older Adults Daily Lives

**链接**: https://arxiv.org/abs/2611.33727
**作者**: Inhee Cho, Jinyoung Jeong, Byung Ju Kim, Jiwon Baek, Jungmin Lee, Jiseob Park 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Global aging makes digital technology important for older adults healthy aging, yet graphical user interfaces remain inaccessible to many. Voice agents based on large language models may help, but users needs and reasons for sustained use remain unclear. We developed a phone-call-style companion that initiates conversations proactively and structures calls using a persona, conversation rules, and prior-call memory (facts, insights, relationship background). We conducted a two-week mixed-methods field study with 33 community-dwelling Korean older adults (29 women; aged 67-91), collecting call logs, pre-post questionnaires, and interviews. Participants made 608 calls following a daily-use recommendation; 25 continued afterward despite turn-taking difficulties. Loneliness and depression scores decreased significantly; among loneliness subfactors, only isolation (emotional loneliness) decreased significantly. Participants disclosed concerns withheld from family and linked companionship to 

---

### [19] EATS: Scaling Tool-Use Experience for Medical Reasoning Agents

**链接**: https://arxiv.org/abs/2611.33897
**作者**: Mingyuan Li, Tong Jia, Haoran Wang, Wenbo Qi, Ziyuan Yang, Bowen Ma 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical reasoning agents combine large language model (LLM) reasoning with clinical workflows and specialized neural tools. However, general-purpose LLMs receive limited training exposure to domain-specific medical tools, and the uncertainty and distributional shifts of neural tool outputs make selecting tools from simple descriptions significantly more challenging than in deterministic settings such as calculators or dictionary lookups. In this paper, we propose EATS, an experience-augmented tool selection strategy that leverages accumulated tool-use trajectories to improve tool selection in medical reasoning agents. EATS constructs a memory of past interactions, including queries, tool choices, arguments, and self-evaluated feedback, and retrieves relevant experiences to guide tool selection for new queries. As memory construction does not require ground-truth supervision, EATS scales naturally with test-time experience. We evaluate EATS on tool-augmented medical reasoning tasks, inc

---

### [20] SVDP: Training-Free Contextual Sparsity Predictors for Fast LLM Inference

**链接**: https://arxiv.org/abs/2603.14110
**作者**: Georgii Serbin, Kirill Koshkin, Zhongao Sun, Anastasiya Bistrigova, C.C. Korikov
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [21] Fisher-R1: Training LLM Agents for Reliable Hypothesis Testing

**链接**: https://arxiv.org/abs/2608.07437
**作者**: Jiacheng Miao, Jin Mu, Guanhua Chen, James Zou
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] EvoLink-Bench: A Benchmark for Evaluating Self-Evolving Agents in Long-Horizon Interdependent Task Streams

**链接**: https://arxiv.org/abs/2611.34400
**作者**: Wei Chen, Xiaodong Lu, Weihao Shen, Gongxun Li, Xingyu Guo, Qihang Sun 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are evolving from passive chatbots into autonomous systems that operate continuously in dynamic environments. Such agents need not only solve current tasks but also learn from past interactions to improve future performance. However, existing streaming benchmarks often rely on short task sequences or largely independent tasks, providing limited evidence of whether agents can effectively reuse experience when later tasks depend on earlier outcomes. To address this gap, we introduce \textbf{EvoLink-Bench}, a benchmark for evaluating self-evolving agents in long-horizon, interdependent task streams. It covers daily office work, multi-turn dialogue, and AutoResearch-style workflows, with persistent workspaces and dependencies across tasks. The benchmark includes two complementary levels: \textbf{L1}, which evaluates the acquisition and revision of language-expressible knowledge, and \textbf{L2}, which assesses the development of task-level capabilities thr

---

### [23] SOLO: Towards Sample-Faithful and Detectable LLM Watermarking under Repeated Sampling via Content-Anchored Single-Owner Contexts

**链接**: https://arxiv.org/abs/2611.34190
**作者**: Zhongliang Guo, Yan Lin, Yifei Qian, Shuai Zhao, Luwei Xiao, Daizong Liu 等 (7 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Providers watermark the outputs of large language models, while applications sample many responses per prompt for self-consistency, best-of-n selection, and uncertainty estimation. We show that deployed configurations of distortion-free watermarks, which deduplicate keyed contexts only within a response, couple the responses of a request: answer templates make all responses query the watermark with the same context before the answer, so collisions across responses, usually assumed rare, become the norm. Key pools reduce or avoid the coupling at the cost of multiple testing, and the exact remedy of a context history shared across the request leaves many positions unwatermarked. We propose SOLO, which keeps a request-scoped context history but anchors its keyed contexts on content selected by min-hash, so that siblings rarely compete for a context and random edits stay local. Its responses are jointly distributed as independent unwatermarked responses, each detectable with a single key. 

---

### [24] A Graph Signal Processing Perspective on Numerical Sequence Representations in LLM In-Context Learning

**链接**: https://arxiv.org/abs/2608.03015
**作者**: Jiajun Bao, Zihao Qi, Toni J.B. Liu, Gurbir Arora, Rapha\"el Sarfati, Nicolas Boull\'e 等 (7 人)
**来源**: cs.LG cs.AI eess.SP
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [25] Contextual language representations link narrative processing to language and literacy in children

**链接**: https://arxiv.org/abs/2611.33871
**作者**: Dongyi He, Tian Jiang, Nizhuan Wang, Wai Ting Siok
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Spoken narratives extensively connect moment-to-moment language processing with knowledge accumulated through language and literacy experience. This study examined that relationship using functional magnetic resonance imaging (fMRI) during Cantonese story listening and contextual representations from large language model (LLM). The imaging cohort comprised 23 school-age children; 16 contributed complete standardized literacy and language assessments and served as held-out participants in a nested cross-subject encoding analysis of the same story. Contextual embeddings predicted distributed narrative responses, with prominent correspondence in temporoparietal and default-network parcels. Regional summaries of the top 25% of voxels ranked by held-out correlation yielded atlas-wide means of r=0.174 and partial R2=0.0165. A joint feature model identified negative surprisal and positive predictive-entropy coefficients across cortical and subcortical parcels, including control, salience, hip

---

### [26] Fully automated safety monitoring via sensor-based agentic LLM with Model Context Protocol

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0926580526006333&hl=zh-CN&sa=X&d=16292653133540841945&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv7o5sZUFG6AF3ltFrVFdypP&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=0&folt=kw-top
**作者**: S Hong, H Kim - Automation in Construction, 2027
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Static thresholds in sensor-based construction safety monitoring offer limited adaptation to individual workers and changing operational contexts. This paper aims to evaluate whether integrating wearable sensing with contextual reasoning can

---

### [27] Confidence Estimation via Decoupled Smoothing for Dynamic LLM Routing and Aggregation

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/pdf%3Fid%3Dxvl4oRu74P&hl=zh-CN&sa=X&d=1114023512463314774&ei=Cb0Ha4f4CvGgieoPte3dyAk&scisig=AIL1Nv4FukPqwQhtJtl7096iHN68&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIL1Nv6nI2XU9qk0OzeW89wx4dKt&html=&pos=1&folt=kw-top
**作者**: H Luo, N Cheng, Y Lin, X Zhou, Y Zhang, X Yan… - The Fortieth Annual Conference …
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> large language models (LLMs) has highlighted the limitations of static single- model inference systems. Although model routing alleviates this issue by assigning the most suitable model … , while the multi - model setting allows single- model or multi - model

---

### [28] REFORGE: LLM-Assisted RTL Bug Repair with Structured Context and Verification Feedback

**链接**: https://arxiv.org/abs/2611.33748
**作者**: Tanvir Hossain, Sudipta Paria, Aidan Gleason Myers, Swarup Bhunia, Tamzidul Hoque
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can write and repair RTL, but successful compilation or testbench execution does not establish defect removal, behavioral preservation, security, or implementation feasibility. Existing LLM-based RTL repair methods often report a single repair rate without retaining separate evidence for these properties, limiting reproducible comparison and integration into hardware design flows. We present REFORGE, which, to our knowledge, is the first LLM-assisted RTL repair framework that maintains and accumulates structured repair evidence across iterations, allowing it to generate fixes that satisfy multiple objectives simultaneously, including functionality, behavioral equivalence, security, and cost efficiency. REFORGE profiles buggy RTL, identifies structural and security-relevant features, localizes failing behavior, and uses verification-guided diagnosis to generate complete RTL repair variants. Each variant undergoes syntax checking, simulation, formal analysis,

---

### [29] VirusCascade: Hijacking Collaborative Reflection in LLM-Powered Recommender Agents

**链接**: https://arxiv.org/abs/2609.38270
**作者**: Yurong Hao, Wen Zhou, Guowei Guan, Tiantong Wu, Fuyao Zhang, Wei Yang Bryan Lim
**来源**: cs.CR cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [30] PROVE: Mitigating Long-Horizon LLM Collusion with Reinforcement Learning from Verified Evidence

**链接**: https://arxiv.org/abs/2611.34215
**作者**: Haochen Luo, Jie Fu, Mukai Li, Yuqi Wang, Qi Liu
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When LLM agents verify each other's work over a long interaction, they drift into collusion: they come to accept work without the evidence that the verification protocol requires. Collusion is absent at the start and builds up episode by episode, which we trace to accurate feedback accumulating in memory. An agent that follows the rule is told that its verdict was wrong whenever its peer was right, so breaking the rule is the reward-maximizing choice, and agents talk themselves into it in their private reflections. Existing mitigations leave the agents unchanged; we train the behavior out. PROVE (Protocol Reinforcement from Verified Evidence) is a multi-agent reinforcement learning method that rewards verdicts by the evidence behind them rather than by their outcome, and credits every call an agent makes, including the calls that solve its own task, with the outcome that call controls. On Qwen3.6-27B, a LoRA adapter trained on six-episode interactions takes the collusion rate on held-o

---

### [31] Shifting Confidence, Not Choices: Moral Bias and Social Influence in Human- LLM Conversations.

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2451958826005476&hl=zh-CN&sa=X&d=2683096590698817387&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv5nC-lMe_zBqXKT8TXXXrSA&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=2&folt=kw-top
**作者**: M Li, T Patten, N Lekhi, A Alsaid - Computers in Human Behavior Reports, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> human– LLM conversation, then engaged in their own LLM discussion. Summaries were authored either by a human participant or by the LLM itself, enabling examination of how LLM -… Together, these experiments examine how an

---

### [32] MathConstruct: Challenging LLM Reasoning with Constructive Proofs

**链接**: https://arxiv.org/abs/2502.10197
**作者**: Mislav Balunovi\'c, Jasper Dekoninck, Nikola Jovanovi\'c, Ivo Petrov, Martin Vechev
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] SOLVE: Sparse, Ordered Keyposes Make LLM Agents Versatile and Efficient Robot Manipulator

**链接**: https://arxiv.org/abs/2611.34750
**作者**: Xiang Li, Hongyu Zhou, Ya-Li Li, Tao Li, Rui Zhang, Junjie Lai 等 (8 人)
**来源**: cs.RO cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents have made remarkable progress in robot manipulation, yet they suffer from expensive inference, dense step-by-step control, and tool bottlenecks. We introduce SOLVE, a training-free, versatile and efficient agent policy: a multimodal LLM agent writes a sparse, ordered sequence of 6-DoF end-effector keyposes per call, observes the result, and writes the next, while a motion planner interpolates between them. The agent decides the number and spacing of keyposes for both fast long-range motion and fine-grained manipulation. This granularity matches the sparsity of teleoperated manipulation: most demonstrations in DROID can be compressed into a few keyposes instead of dense actions. SOLVE grounds keyposes with sparse depth queries answered by noisy sources, such as multi-view triangulation, stereo, or monocular depth, and copes with that noise itself. It also improves from execution feedback, reflecting on its own rollouts and distilling a few rules per task. SOLVE reaches state-

---

### [34] The Open Proof Corpus: A Large-Scale Study of LLM-Generated Mathematical Proofs

**链接**: https://arxiv.org/abs/2506.21621
**作者**: Jasper Dekoninck, Ivo Petrov, Kristian Minchev, Mislav Balunovic, Martin Vechev, Miroslav Marinov 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] BuildOcc: A Large Language Model Occupant Agent Platform for Building Energy Research

**链接**: https://arxiv.org/abs/2609.02729
**作者**: Wooyoung Jung
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] Benchmarking LLM-Based Investment Advisor Agents for Asset Allocation in the Chinese ETF Market: Overview of NLPCC 2026 Shared Task 4

**链接**: https://arxiv.org/abs/2603.22305
**作者**: Liyuan Chen, Shilong Li, Jiangpeng Yan, Shuoling Liu, Xi Cheng, Haoran Zhang 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [37] FluidPD: In-Place Elasticity for SLO-Aware Prefill-Decode Disaggregated LLM Serving

**链接**: https://arxiv.org/abs/2610.06917
**作者**: Kartik Ramesh, Kaidi Fu, Zihan Zheng, Yi Zhao, Jiahuan Yu, Fabio Oliveira 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [38] An LLM -Agent Framework for Building Energy Model Calibration with Physically Bounded Parameter Priors: Validation Against In-Situ Measurements

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0950705126021246&hl=zh-CN&sa=X&d=9006986031045306878&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv4jpo5sO6p-5vmp9t1fgf8k&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=3&folt=kw-top
**作者**: X Liang, J Shim, D Song - Knowledge-Based Systems, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Building energy modeling remains constrained by labor-intensive workflows and specialist expertise. This study introduces a natural language–driven AI-agent framework powered by large language models (LLMs) for automated generation

---

### [39] Polyrating: A Cost-Effective and Bias-Aware Rating System for LLM Evaluation

**链接**: https://arxiv.org/abs/2409.00696
**作者**: Jasper Dekoninck, Maximilian Baader, Martin Vechev
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [40] Environment-informed multi-robot construction task allocation: RAG-assisted LLM extraction of environmental operating requirements and multi-objective optimization

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1474034626011572&hl=zh-CN&sa=X&d=6378127186617485348&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv4DOiyAd1U5C0rpo_hdy4Fq&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=5&folt=kw-top
**作者**: L Zhu, C Mao, T Wang, Y Liu - Advanced Engineering Informatics, 2027
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Multi-robot construction task allocation (MRCTA) is essential for efficient collaboration of construction robots. Existing MRCTA research largely focuses on the alignment of robot capabilities with task requirements, with limited attention to

---

### [41] Modeling Bilingual Learning Through LLM Training: A Critical-Period Exploration

**链接**: https://arxiv.org/abs/2611.32997
**作者**: Uriel Benymon, Tristan Whipps, Armita Ghobadi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [42] Unstable Action Boundaries in Lethal Drone Agents

**链接**: https://arxiv.org/abs/2611.34121
**作者**: Jacques Dumora, Andr\'e-Louis Rochet and Simon Roburin
**来源**: cs.LG cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tool-using large language model (LLM) agents raise safety risks that are not captured by text-only refusal behavior, especially when tools can trigger high-impact actions. This concern is salient in military settings, where autonomous weapons raise the possibility of delegating force decisions to software agents. In this work, we study whether a drone agent's action boundary is stable under changes to the target descriptor. We evaluate recent and popular LLMs in a simulated perception-action pipeline over real-world drone imagery, where models can localize requested targets and invoke a simulated lethal tool. We find two concerning failure modes. First, some LLM agents invoke the lethal tool for ordinary generic descriptors such as \emph{people}, requiring no jailbreak at all. Second, an agent that initially appears conservative under protected descriptors can become unsafe under a simple semantic target shift.

---

### [43] WorldUAV: Scaling UAV Data Synthesis via World Models

**链接**: https://arxiv.org/abs/2611.33682
**作者**: Xuewen Liu, Mengjuan Chen, Jing Zhang, Mengzhe Shen, Zekun Xu, Zibo Chen 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> UAV detection and tracking remain constrained by the scarcity of high-quality training data. Existing game-engine-based synthetic UAV data suffer from a substantial synthetic-to-real gap, while the high cost of manually collected real-world UAV data limits dataset scale. Therefore, we introduce WorldUAV, a high-quality UAV dataset constructed through an efficient framework powered by world models. Specifically, WorldUAV directly integrates UAVs into readily available real-world videos, naturally preserving realistic backgrounds, illumination, and scene dynamics. Leveraging the spatiotemporal priors of world models, it generates UAV videos with plausible motion, pose variations, and cross-frame consistency, effectively narrowing the gap between synthetic and real data. We further develop an agentic pipeline orchestrated by a multimodal large language model that acquires sources, plans UAV trajectories, invokes synthesis, and verifies generated videos, enabling fully automated dataset co

---

### [44] CypherMAS: Benchmarking Routing Reliability in LLM-Based Multi-Agent Systems

**链接**: https://arxiv.org/abs/2611.33242
**作者**: Danil Kostromin, Andrey Sakhovskiy, Semen Budennyy
**来源**: cs.MA cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems (MAS) built on large language models (LLMs) distribute reasoning across specialized agents that must exchange messages and invoke tools reliably. Existing evaluations typically couple communication with open domain tasks, making it difficult to determine whether a failure arises from reasoning, malformed tool use, lost messages, or forgotten requests. Prior benchmarks do not isolate communication execution or measure routing redundancy against a known optimal path. We introduce CypherMAS, a synthetic benchmark that isolates communication and routing in fixed multi-agent graphs. Agents in chain, star, bipartite, or ring graphs route cyphered messages to remote peers holding the matching decoders; since the optimal route is known, redundant LLM calls can be measured and routing failures may be easily tracked. Across eleven open-weight models from 4B to 753B, small models fail at routing and tool use, dense models above 27B degrade with diameter, and successful runs ex

---

### [45] LLM -guided structured constraints for robotic manipulation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0950705126020502&hl=zh-CN&sa=X&d=14747956378018961741&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv6DQM1Fk18Si5geZ-BJnwGN&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=9&folt=kw-top
**作者**: Y Gao, J Li, Z Li, Y Meng, J Huang, N Di - Knowledge-Based Systems 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This paper proposes an LLM -based framework for structured manipulation constraint generation and constraint-driven execution. Given an object-level scene representation and a natural-language instruction, the framework generates

---

### [46] Knowledge-Preserving LLM Architecture Standardization: Analytic Normalizer Mapping with Equal-Size Distillation

**链接**: https://arxiv.org/abs/2605.25676
**作者**: Kisu Yang, Yoonna Jang, Hyeonseok Moon, Hwanseok Jang, Taewoo Lee, Hyungjin Lee 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Whose Side Are You On? A Framework and Benchmark for Assessing LLM Political Stances through Politicians Social Media Posts

**链接**: https://arxiv.org/abs/2611.34098
**作者**: Mohamed Osman, Mucahid Kutlu, Tamer Elsayed, Saban Kardas
**来源**: cs.SI cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) increasingly participate in political discussions, making it important to understand which positions they support or oppose. We propose a framework for assessing LLMs' political stances through simulated social media interactions. The framework uses politicians' posts and multiple prompting methods to identify consistently expressed stances. Using this framework, we construct WorldPOLL, comprising 4,600 political posts from X/Twitter collected from approximately 200 politicians representing ruling and opposition blocs across 23 countries. Our quantitative analysis shows how support and opposition vary across models, countries, and political directions, while our qualitative analysis identifies the political views and policies models support or oppose. Together, these analyses reveal shared positions across models and differences across national contexts. We also examine whether models express consistent stances across prompting methods, investigate the reas

---

### [48] Joint Estimation of Abilities and Item Parameters for Large Language Models Using Probability and Binary Responses: A Fractional-Response IRT Framework

**链接**: https://arxiv.org/abs/2611.33493
**作者**: Masayuki Takayama and Shohei Shimizu
**来源**: stat.ME cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) evaluations provide two response types: probabilities assigned to correct answers and binary indicators of correctness. Restricting evaluation to one type narrows the range of available models or discards probability information. We propose a method to integrate both types through a common two-parameter logistic item response model and fractional-response quasi-maximum likelihood estimation. The framework includes binary-only models in common-scale evaluation without discarding available probabilityinformation; broader measurement coverage does not by itself ensure greater precision or measurement equivalence. Simulations evaluate statistical efficiency when both response types have the same expected value. Moreover, adding probability respondents improves item calibration more efficiently than adding binary respondents. However, adding noisier binary responses to an already precise probability sample can increase estimation error under equal observation weig

---

### [49] Large Language Model Agents for Evidence Based Genetic Disease Severity Classification

**链接**: https://arxiv.org/abs/2609.19569
**作者**: Tohid Ghasemnejad, Ahmadreza Argha, Mark Grosser, John Wang, Min Yang, Thantrira Porntaveetus 等 (10 人)
**来源**: q-bio.GN cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Crucible: Evaluating LLM Agents in Executable Chemistry Research Environments

**链接**: https://arxiv.org/abs/2611.34254
**作者**: Yinjun Liu, Xinye Li, Ruisen Peng, Lang Gao, Zixiang Xu, Zirui Song 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) perform well on chemistry knowledge benchmarks, which mainly assess question answering and isolated tasks. Chemical research, however, requires using specialized tools and interpreting their outputs to obtain chemically valid results. To address this gap, we introduce Crucible Bench to evaluate this ability across all four stages of the design-make-test-analyze (DMTA) cycle. The benchmark contains 1,078 tasks in 12 task families curated from 18 published datasets, covering molecular design, synthesis planning, experimental execution, closed-loop optimization, simulation, and analytical characterization. Agents access 75 domain-specific tools through the Model Context Protocol in seven isolated environments. Sandboxed graders verify the resulting synthesis routes, experimental protocols, and other outputs. Laboratory tasks use robotic simulators or previously measured experimental data. We evaluate 14 LLMs as agents and find that the best achieves an overall

---

### [51] What Must LLM Agents Communicate? From Information Loss to Communication Failures

**链接**: https://arxiv.org/abs/2611.33318
**作者**: Yi-Yun Chu, Xiaobin Shen
**来源**: cs.MA cs.IT cs.LG math.IT
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When evidence is distributed across LLM agents, a team may collectively possess all the information needed for a decision yet fail to use it effectively. What must agents communicate for accurate joint predictions, and when does interaction help? We study three requirements for effective communication: sufficiency of the information conveyed, selection of relevant evidence, and utilization of received information. Drawing on information theory and communication complexity, we develop a framework that combines theoretical benchmarks with controlled experiments and message-level analyses. We find that local probability reports can discard essential information, with theoretical information loss closely matching observed performance penalties. Query-first interaction improves predictions when relevant evidence depends on a private query, but compact one-shot representations can eliminate this advantage. Even when sufficient information is communicated, agents may fail to select or use it 

---

### [52] Any-Rate: Half-Bit Multi-Precision LLM Quantization with Coded Bit-Planes

**链接**: https://arxiv.org/abs/2611.34402
**作者**: Hoonki Lee, Haechan Shin, Hyuntaek Jung, Yeonu Choi, Sangyeob Kim
**来源**: cs.LG cs.AR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Nested multi-precision quantization derives multiple precisions from a single checkpoint by reading only the leading bits of each weight, which makes it attractive for on-device deployment under varying memory and energy budgets. However, existing methods offer only integer bits, leaving large accuracy gaps between adjacent precisions and severe degradation at 2 bits. To address this, we propose Any-Rate, which serves 2-8 bits from one checkpoint, in half-bit steps over 2-4 bits. Any-Rate restricts some bit-planes to extended Hamming codewords in 8-weight blocks (0.5 bits per weight), shares one LUT per row across precisions, and encodes all precisions jointly with a separate target for each, reducing the loss from sharing bit-planes. Across four LLMs, Any-Rate achieves state-of-the-art accuracy among multi-precision methods at 2 and 3 bits, keeping 69% of FP16 accuracy at 2 bits, and is within one point of the best at 4 bits. It decodes about as fast as existing kernels, and an LPDDR 

---

### [53] Constraint-Aware Test-Time Scoring for LLM and VLM Candidate Selection

**链接**: https://arxiv.org/abs/2611.33161
**作者**: Rangarajan Ramesh, Yongchao Huang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM or VLM produces several candidate answers, picking the best one usually relies on the model's own confidence, a learned judge model, or a domain check. Each has a known weakness: an answer can be fluent but insecure, mathematically plausible but physically infeasible, or rated highly by a judge while quietly breaking a task requirement. We propose a scoring framework that combines a small set of hard checks every answer must pass with a wider set of softer checks whose scores are blended into one number per candidate. This adaptive scoring framework consists of three components: a drafting model that produces the candidates, a configuring model that selects and weights the checks for each task, and scoring models that rate properties no grounded tool can compute. We apply our proposed method to four tasks: writing code that is both correct and secure (CWEval), generating robot manipulation plans (LIBERO with added safety variants), passing competitive-programming hidden tes

---

### [54] The WoW: A Large-Scale World Knowledge Corpus for Full-Lifecycle LLM Training

**链接**: https://arxiv.org/abs/2611.13487
**作者**: Tianze Sun (1), Yongyao Duan (2), Sam Chen (2), Yuanjian Xu (3) ((1) Harbin Institute of Technology, (2) OpenCSG, (3) Hong Kong University of Science and Technology (Guangzhou))
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] InterGenEHR$^+$: An Interactive Framework for Natural Language-Conditioned Generation of Longitudinal Patient Trajectories

**链接**: https://arxiv.org/abs/2611.33788
**作者**: Yu Yang, Jiafeng Song, Baraa F Abed, Christina Creel, Sagar B Dave, Henry Foote 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Objective: To develop and validate InterGenEHR$^+$, an interactive framework for natural language-conditioned generation of synthetic tabular electronic health records (EHRs) and longitudinal trajectories for scenario-based evaluation of machine learning models. Methods: An optional large language model (LLM) parser converts clinical requests into structured constraints. Conditional variational autoencoders and diffusion models generate single-time-point records, while diffusion models generate longitudinal trajectories. We evaluate parsing, distributional fidelity, imputation, clinical-constraint adherence, mortality prediction, and clinical plausibility using a multi-institutional cohort of 874 patients receiving venovenous extracorporeal membrane oxygenation (VV-ECMO). Results: Gemma 3 4B with few-shot prompting achieves the highest parsing performance with a low spurious slot rate. IGE-TabDDPM and IGE-PMVAE perform well in single-time-point generation; IGE-CSDI, IGE-FGTI, and IGE-M

---

### [56] Subverting Tool Arguments: Defense-Evading Metadata Poisoning in LLM Agents

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.27041&hl=zh-CN&sa=X&d=11282021527887654732&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv5bUI88Oy64hdxcRr7V_cm6&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=7&folt=kw-top
**作者**: SC Dai, X Sun, H Zhang, Z Zhong, G Tao - arXiv preprint arXiv:2611.27041, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract—Conventional indirect prompt injection (IPI) attacks hijack an LLM agent’s workflow … To address this challenge, we propose GRAFT, an LLM -based optimization method for … descriptions using dynamic mutation strategies proposed

---

### [57] AI Buckingham: Agentic Discovery of Dimensionless Scaling Laws Across Physical Regimes

**链接**: https://arxiv.org/abs/2611.33961
**作者**: Ao Cheng, Lei Zhang and Guowei He
**来源**: physics.comp-ph cs.AI physics.flu-dyn
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Classical dimensional analysis defines admissible dimensionless representations but does not determine which combinations capture the dominant physical dependence, whether it changes across physical regimes, or when dependent-variable rescaling is required. We present AI Buckingham, an agentic framework for autonomous dimensionless discovery from natural-language descriptions of physical problems and observational data. It couples reasoning and planning by a large language model (LLM) with predefined symbolic and numerical tools. Literature-based knowledge retrieval supports dimensional checking, gradient-based clustering identifies physical regimes, and mutual information provides an objective, reparameterization-invariant criterion for identifying dominant dimensionless groups. Explicit numerical criteria determine the group count and assess simplification. Across ten physical systems spanning fluid dynamics, magnetohydrodynamics, thermal convection and additive manufacturing, AI Buc

---

### [58] RepSelect: Robust LLM Unlearning via Representation Selectivity

**链接**: https://arxiv.org/abs/2606.17168
**作者**: Filip Sondej, Yushi Yang, Adam Mahdi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Shadows in the Code: Exploring the Risks and Defenses of LLM-based Multi-Agent Software Development Systems

**链接**: https://arxiv.org/abs/2511.18467
**作者**: Xiaoqing Wang, Keman Huang, Bin Liang, Hongyu Li, Xiaoyong Du
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [60] General-Purpose Decision Models for AI Configuration Tuning

**链接**: https://arxiv.org/abs/2611.33190
**作者**: Jingzhi Gong, Jie M. Zhang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI configuration tuning searches for settings that improve the performance of AI systems under a limited budget. Existing tuners use different sampling and search policies, making the choice of decision strategy central to both tuning quality and cost. We investigate whether general-purpose decision models can guide tuning, using Jev as a deployed representative that returns structured choices and numeric scores across diverse tasks. To assess where it helps, we compare its use as an optimizer, performance predictor, and region guider against conventional methods and a large language model (LLM) on eight AI tuning tasks. Conventional optimizers attain rank 1 in six of eight comparisons. Similarly, established predictors outperform Jev in seven. Through region guidance, however, it finds configurations with lower perplexity than those selected by the native tuner, offering a quality gain when additional decision time and API fees are acceptable. These findings yield actionable recommend

---

### [61] RankCast: Phase-Aware Rank Balancing in MoE Serving

**链接**: https://arxiv.org/abs/2611.33542
**作者**: Kaidi Fu, Xu-Hao Lu, Pingwei Sun, Jianchao Tan, Yuchen Xie, Xunliang Cai
**来源**: cs.DC cs.AI cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern large language model (LLM) inference increasingly adopts disaggregated architectures that separate Prefill (P) and Decode (D) phases. Meanwhile, Expert Parallelism (EP) has been widely adopted in large Mixture-of-Experts (MoE) model serving. However, load imbalance still slows down MoE inference because each layer must wait for the busiest EP rank. The main source of latency differs between prefill and decode. Prefill is compute-bound, and its MoE layers' latency is determined by the maximum token count of the busiest rank. At the same time, under moderate batch sizes, Decode is memory-bound, so the latency is dominated by the maximum active-expert count across ranks. To solve both problems under a unified framework, we present RankCast, a system that reduces rank-level maximum token counts during prefill and active-expert counts during decode. For every token, RankCast preserves the predicted Top-p experts and chooses the remaining k-p from its Top-L candidates (L > k). In pref

---

### [62] The Detour Is the Danger: Preserving Security During LLM Agent Recovery

**链接**: https://arxiv.org/abs/2611.33605
**作者**: Boyang Ma, Jinku Li, Hao Wu, Sheng Gao, Man Zhou, Minghui Xu 等 (7 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on external tools and reusable Skills to execute complex workflows, autonomously replanning when operations fail. However, such recovery may preserve task functionality while silently discarding the security protections required by the original workflow. In this paper, we investigate workflow security downgrade, a failure-induced security threat in which agents execute sensitive operations without satisfying their original protection requirements. Unlike prompt injection, this threat exploits autonomous recovery decisions triggered by execution failures, without modifying instructions or tool definitions. We systematically evaluate this behavior through fault injection in an executable MCP/Skill environment spanning seven LLMs, twelve task templates, and three security-sensitive domains. To address this threat, we propose ARGUS, an obligation-preserving recovery framework that combines resource-bound security evidence, isolated recovery-plan validation, and

---

### [63] Poisoning Self-Evolving Security Policies in LLM Agents

**链接**: https://arxiv.org/abs/2611.33385
**作者**: Aymen Noor, Honglu Jiang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving defenses improve LLM-agent security by learning reusable policies from observed attacks. However, we demonstrate that this learning process itself can become an attack surface. Using SED (Self-Evolving Defense) in the AgentDojo benchmark, we construct a single prompt-injection episode that causes the defense to learn an over-broad policy and subsequently refuse legitimate requests. Across 10 Nemotron runs, every poisoned run over-refuses at least one legitimate task, while unrelated-task performance remains unchanged and the original prompt-injection defense remains effective. The attack also transfers to gpt-oss-120b; however, its poisoning mechanism depends on a successful initial prompt injection and therefore fails to activate when the target agent resists the underlying injection. In contrast, integrity-oriented attacks targeting SED's judge, policy synthesis, retrieval, and organization mechanisms fail in our evaluated settings, identifying over-refusal as the prima

---

### [64] SparDA: Sparse Decoupled Attention for Efficient Long-Context LLM Inference

**链接**: https://arxiv.org/abs/2606.04511
**作者**: Yaosheng Fu, Guangxuan Xiao, Xin Dong, Song Han, and Oreste Villa
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] VibeServe: Can AI Agents Build Bespoke LLM Serving Systems?

**链接**: https://arxiv.org/abs/2605.06068
**作者**: Keisuke Kamahori, Shihang Li, Simon Peter, Baris Kasikci
**来源**: cs.AI cs.DC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] C3H: Compression-to-Consensus Criteria Hijacking in Multimodal LLM Recommender Systems

**链接**: https://arxiv.org/abs/2611.32780
**作者**: Guowei Guan, Yurong Hao, Jiaming Zhang, Fuyao Zhang, Wei Yang Bryan Lim
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] LLM-coupled interpretable tool wear monitoring with multi-evidence reasoning in CNC machining

**链接**: https://arxiv.org/abs/2611.34270
**作者**: Yuntong Chen and Yingqi Li and Qiwen Shen and Guobin Zhao and Xitian Tian and Lijiang Huang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Interpretable tool wear assessment in CNC machining is challenging. Existing diagnostic models have high accuracy but provide limited guidance for tool replacement. This study proposes a two layer framework combining deep learning wear classification and LLM assisted reasoning. The first layer uses PCA Loading feature selection and optimized GRU to recognize three wear states, achieving 98.38 percent macro F1 score on the PHM2010 dataset. The second layer uses LLMs to generate natural language reports and replacement suggestions from classification results and feature trends. Engineer evaluation shows the reports outperform rule templates. Cross dataset tests on NASA milling data support the generalizability of this framework.

---

### [68] The Silent Cost of Conversation History in LLM Reasoning

**链接**: https://arxiv.org/abs/2611.20071
**作者**: Ali \c{S}enol
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [69] AltRA-Test: An Alternative Annotator Test for LLM Judges Without Shared Annotators

**链接**: https://arxiv.org/abs/2611.26073
**作者**: Nagham Omar, Rotem Dror, Almog Gueta, Avigdor Gal, Roi Reichart, Nitay Calderon
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] Too Smart for Its Own Good? Cognitive Fidelity and Competence Leakage in LLM Simulations of Young Learners

**链接**: https://arxiv.org/abs/2611.34042
**作者**: Zhen Xu, Beata Beigman Klebanov, Jamie N. Mikeska
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based interactive learner simulators are increasingly used in educational applications, including teacher training and tutoring system development. A critical requirement for those simulations is cognitive fidelity: the simulated learner should maintain the assigned knowledge, misconceptions, and reasoning procedures throughout interaction. However, LLMs may express knowledge or problem-solving skills beyond the assigned learner's cognitive status, a phenomenon we refer to as competence leakage. In this exploratory study, we examine 3,339 simulated learner utterances from 130 teacher-learner simulator transcripts across three learning scenarios and identify over-competence as a prominent direction of cognitive-profile misalignment during interaction. We then investigate the recurrence of previously observed competence leakage cases under four matched-trigger evaluation protocols, ranging from isolated questioning to multi-turn interactions, across five model configurations. Overall

---

### [71] MGMem: An Efficient, Deterministic, and Provenance-Preserving Framework for Long-Horizon Agent Memory

**链接**: https://arxiv.org/abs/2611.33174
**作者**: Junhong Huang, Xin Tong, Jun Xia
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon Large Language Model (LLM) agents need persistent memory that surfaces the right past interaction at the right time across thousands of turns. Many systems index by invoking generative LLMs to rewrite history into summaries, facts, or knowledge graphs--a step that is (a) costly (thousands of generative calls per build), (b) non-deterministic (undermining reproducibility and giving inconsistent answers across runs), and (c) provenance-erasing (the reader sees synthesized text, not the original turn). We propose MGMem, a framework with no generative indexing calls that replaces this step with a deterministic discriminative-parser pipeline: recurring mentions across sessions are organized into an incidence graph, question mentions are resolved by a subject-conditioned three-stage resolver, and raw dialogue episodes are returned to the reader. On English multi-session dialogue QA, MGMem outperforms matched-protocol baselines on LoCoMo without generative indexing calls; on the 

---

### [72] Real Package, Wrong Controller: Static Auditing of Vendor--Protocol Mismatches in LLM-Generated PLC Code

**链接**: https://arxiv.org/abs/2611.33227
**作者**: S M Zia Ur Rashid, Sazidul Islam Hira, Suman Rath
**来源**: cs.CR cs.LG cs.SE cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models can generate Python that drives industrial protocols on programmable logic controllers, yet existing code-grounding checks ask whether an imported package or symbol exists rather than whether it suits the declared industrial target. We define \emph{metadata-conditioned, import-level vendor--protocol incompatibility} and build \textsc{Proteus-OT}, a label-free static verifier over a version-pinned graph of documented bindings. Across 883 generated scripts, 180 carry an import-level mismatch against the declared target (20.4\%); restricting to single-vendor targets gives 16.3\%, and additionally requiring the offending library to reach a protocol communication call gives 14.2\%, which we read as conditional on the corpus metadata rather than on verified intent. None of the 28 adjudicable human control files carries one, a sample too small to estimate a prevalence. Within the balanced subset, 96.6\% of mismatching scripts import packages and call methods that exist, so an 

---

### [73] Faster and Better Query (FBQ): Learning Future-Position Probes from the First Generated Token

**链接**: https://arxiv.org/abs/2611.33679
**作者**: Jiankun Zou, Daixing Chen, Tongtong Yuan
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a large language model (LLM) evicts prompt keys and values at the end of prefill, it must decide what to keep before it sees the queries from subsequent decoding steps. Generating a draft continuation can approximate those queries at the cost of extra autoregressive steps. Can we use the embedding of the first output token, already available from the final prefill logits, to construct low-cost pseudo queries that approximate future decoding queries? We start with FTQ-8, which places eight copies of the first token ID at consecutive future positions and reads their attention to the prompt in one causal forward pass. Each copy sees a different prefix, but a generic opening such as the offers a poor literal guess for seven successive tokens. Faster and Better Query (FBQ) preserves the first embedding and learns an additive offset at each of the seven remaining positions. We train these offsets to predict the average prompt attention of a full-cache continuation. On LongBench, FBQ per

---

### [74] Do We Really Need an LLM for Weight-Space Programming? A Deterministic Forward-Only Paradigm and Its Capability Boundaries

**链接**: https://arxiv.org/abs/2611.34612
**作者**: Lin Yao
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work on Weight-Space Programming uses LLMs to edit neural weights with forward passes only, conflating LLM scripting with the underlying algebra of forward-only editing. We show that for core structured editing regimes, an LLM optimizer is unnecessary, and introduce Forward Weight-Space Programming (FWSP): a deterministic pipeline combining probing, localization, stratified operators (O1-O4), automatic blind routing (83.3% vs. 33.3% for a 27B LLM with the same tool library), and paired verification with zero additional per-token computation. For reasoning LLMs, we propose Protected FisherGate, a closed-form covariance-whitened readout edit orthogonal to normal-reasoning states: on DeepSeek-R1-0528-8B, a single frozen math-calibrated patch achieves 84.2% HumanEval pass@1 (1K budget; 75.4 +/- 9.4% across 3/5 Stage-4-passing subsets), beating 512-token-reserved budget forcing by +14.6 pp (-23.4% tokens) while transferring across HF-to-vLLM backends on full GSM8K and MATH-500. Acros

---

### [75] Auto-Features: An LLM-Assisted Corpus for Contextual Recognition of Standard and Optional Car Features

**链接**: https://arxiv.org/abs/2611.33974
**作者**: Filippos Ventirozos, Ioanna Nteka, Tania Nandy, Peter A. Appleby and Matthew Shardlow
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present Auto-Features, a corpus for detecting a car's standard and optional features in advertisement text, given the feature catalogue of that exact vehicle. Sellers name the same feature in many ways. We therefore cast the task as feature-conditioned, or contextual, named entity recognition: extract the span that expresses one given catalogue feature. An entity-linking view follows from the same output. The corpus has a human-gold layer (430 adverts) from screened annotators and an LLM-silver layer (925 adverts) auto-annotated by a search-grounded LLM. We also contribute the way it was built. Every LLM output is validated, and each kind of failure has its own remedy. Malformed output is patched. Hallucinated content triggers a fresh attempt by a stronger model. Links to features outside the candidate list are dropped and counted (3 in 10,928 records). The LLM annotates alone only after its agreement with human annotators on link verification is comparable to human-human agreement.

---

### [76] Learning the Platform, Not the Learner: Sequencing Shortcuts in the Offline Evaluation of Educational Recommender Systems and LLM Rankers

**链接**: https://arxiv.org/abs/2611.33240
**作者**: Youssef Jdidou
**来源**: cs.IR cs.CY cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Educational recommenders are usually compared offline, by how well they predict the next activity in logs of tutoring systems, learning applications and MOOCs, where the next activity is largely decided by the platform: teachers assign problem sets, tutors draw problems until mastery, engines select questions. On eight public datasets from five platforms, we compare four structural predictors, which use nothing about the learner beyond the last activity, with ten personalised recommenders and with open-weight LLM rankers from 0.5 to 7 billion parameters, under two protocols. The structural predictors reach between 0.81 and 1.00 of the best accuracy of any method (median 0.95), mostly through population transitions rather than the course order; the best personalised recommender is significantly better on five datasets, by 0.007 to 0.102 NDCG@10, and on Eedi in three of four training runs. Every method is far less accurate on steps along transitions never seen in training and on steps ch

---

### [77] RHOPE: LLM-Augmented Adaptive Experimental Design with Complex Contextual Information

**链接**: https://arxiv.org/abs/2611.33767
**作者**: Bowen Shi, Bo Li
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Experimental design allocates limited measurement effort across candidate treatments to learn their expected outcomes. Adaptive designs refine allocations as evidence accumulates, improving estimation and treatment selection. Contextual information can inform these decisions, but exploiting unstructured or high-dimensional context remains challenging. We use large language models (LLMs) to transform complex context into proxy outcomes and propose Residual Horizon Optimization for Prediction-Powered Experimentation (RHOPE), a principled Bayesian adaptive experimentation framework that combines true outcomes with LLM-generated proxy outcomes and formulates finite-batch design as a posterior Markov decision process (MDP). Our methodology uses proxy outcomes in two ways: sample augmentation improves estimation precision, while observing proxies before each allocation decision provides advance information. Synthetic experiments and semi-synthetic experiments using Genomics of Drug Sensitivi

---

### [78] Learning to Be Truncated: Preparing LLM Checkpoints for SVD Compression

**链接**: https://arxiv.org/abs/2611.34667
**作者**: Chenyue Fang and Danila Mishin and Babak Falsafi
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Compression based on singular value decomposition (SVD) often requires subsequent fine-tuning or weight correction to mitigate performance degradation. Budget-specific optimization must be repeated for different compression ratios. We introduce LLift, which prepares a pretrained model for SVD compression across ratios without further fine-tuning. LLift fine-tunes a low-rank approximation at a single ratio using the original model as a teacher. We merge the learned updates into the original weights while preserving the complementary components excluded from the training forward pass. We apply SVD to the prepared model's target matrices and reuse the decompositions at different truncation ranks. On LLaMA-7B, we demonstrate accuracy gains across three compression ratios using a single prepared model. The gains extend across model families, model sizes, and SVD compression operators. We analyze gradients and an early training update to provide local evidence that updates learned at one rat

---

### [79] FlashProve-Next: Verifiable Inference for Production LLM APIs

**链接**: https://arxiv.org/abs/2611.33741
**作者**: Liang Song
**来源**: cs.CR cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Clients of closed-weight LLM APIs cannot verify whether a provider ran the advertised model, precision, hidden prompt, and reasoning budget. Existing approaches either trust hardware or third parties, or re-prove every layer of an integer surrogate at high cost while diverging from native floating-point serving. FlashProve-Next produces verifiable, zero-knowledge-masked proofs for individual LLM API responses without modifying native serving (bf16/fp8/mxfp4, random sampling, FlashAttention, CUDA graphs, batching, prefix caching) and without disclosing weights, hidden prompts, hidden reasoning, or activations (dense profiles fix coarse geometry; cross-architecture hiding is deferred). A non-depleting Reed-Solomon weight commitment model_id opens inside proofs via hidden column openings, while local per-operator rounding contracts remove integer surrogates and the refusal-bit leak. Cost-weighted spot-checking supports non-interactive public verification (NI-315, $\varepsilon \le 2^{-40}$

---

### [80] Tells of a Lying Machine: Analyzing LLM-Generated Strategic Dialogue in Chinese Werewolf

**链接**: https://arxiv.org/abs/2611.33747
**作者**: Xian Cui, Gan Yang, Dongqi Han, Han Zhu, Bo Zheng, Jianhui Zheng 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Social-deduction games give models opposing objectives, but they also give roles different information and speaking obligations. We analyze 5,404 public utterances from 150 Chinese Werewolf games played by 12 models, comparing ordinary wolves with ordinary villagers so that special roles are excluded. Private knowledge and goals still differ, and no utterance is verified as true or false. After model and length adjustment, wolf utterances score higher on both certainty and uncertainty (coefficients +0.074 and +0.072). Emotional intensification has the largest rank-biserial effect (r = .145), but it depends on a single degree marker and correlates weakly with human-rated affect. Three annotators' ratings of 392 utterances show higher wolf scores on four behavioral dimensions, and five LLM judges reach 60.8%-70.2% accuracy on a shared evaluation set. In a generation probe that prompts six models with a wolf identity but a villager speaking goal under fixed public context, certainty (+0.1

---

### [81] LLMVC: Large Language Model-Guided Generative Video Compression

**链接**: https://arxiv.org/abs/2611.33580
**作者**: Lebin Zhou, Zhenghao Chen, Nam Ling, Wei Wang, Wei Jiang
**来源**: cs.CV
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent generative video methods achieve strong perceptual compression by encoding videos into compact latent representations and reconstructing them with powerful generative decoders. However, visual encoders must compress both high-level semantics and dense visual details into a unified latent space, which complicates entropy coding and decoding and may cause semantic drift under aggressive compression. In this work, we propose Large Language Model-Guided Video Compression (LLMVC), which leverages the summarization capability of frozen video large language models (Video-LLMs) to generate compact semantic tokens aligned with temporal latent slices for guiding video compression. Specifically, Hybrid Bidirectional Bimodal Attention (HBBA) enables bidirectional interactions between visual and semantic features during encoding and decoding. Semantic-Conditioned Cross-Attention (SCCA) incorporates semantic features into probability modeling during entropy coding. These semantic features pro

---

### [82] SecID: An LLM-Guided Framework for Threat-Aware Secondary Asset Identification with Quantitative RTL Analysis

**链接**: https://arxiv.org/abs/2611.33453
**作者**: Md Ajoad Hasan, Dipayan Saha, Upoma Das, Sujan Kumar Saha, Mark Tehranipoor, Farimah Farahmandi
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing complexity of modern hardware designs is making security assurance increasingly difficult. One of the foundational steps in pre-silicon security verification is identifying security assets. While primary assets are often evident from design functionality, the internal signals that can facilitate their compromise are much less apparent. Complex data- and control-flow dependencies create many such internal security-critical locations, whose exploitation depends on the threat-specific attack mechanism---these are the secondary assets. To precisely identify these, we propose SecID, a multi-agent framework that combines deterministic RTL analysis with bounded dynamic evaluation and LLM reasoning to identify threat-specific secondary assets. Each asset decision is supported by functional influence, threat features, and explicit attack mechanisms. We demonstrate SecID on seven open-source SoC and IP designs, including openMSP430, NEORV32, and CV32E40P. The experimental results are

---

### [83] Temporal Weight Surgery: Repairing Video Grounding with LLM Editors

**链接**: https://arxiv.org/abs/2611.33339
**作者**: Ali Asgarov, Chris Thomas
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A surgeon first finds what is wrong, then fixes only that part. We use this idea for video grounding, where video-language models often find the right moment in a long video but write its time wrong. In Temporal Weight Surgery (TWS), a general-purpose LLM reads the model's weights and activations, finds where the error arises and repairs it there, without gradients. Separate sessions find the same cause, and this diagnosis of where and why the model fails is our main contribution. Three GPT-6 Astra sessions trace a dropped digit in TimeLens-8B to one MLP layer, and the largest edit gains 7.9 mIoU on 1,215 unseen questions and 18.3 on videos of 30 minutes or more. Two Claude Opus 5.5 sessions trace minutes written as seconds in Qwen3-VL-8B to the separator and gain 2.9 and 1.3. Before any edit, its answers often have the right minute and the wrong separator, and fixing only the separator lifts their mIoU from 13.1 to 19.2. Every improving edit beats a random edit of its size, and the ed

---

### [84] ProjRot: Matching Rotations to Activation Structures for W4A4 LLM Quantization

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306457326006850&hl=zh-CN&sa=X&d=9065508477665385106&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv66oj3Oaehn6I7nPEMjNrs_&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=4&folt=kw-top
**作者**: J Xiao, B Ji, S Li, X Liu, J Ma, C Wang 等 (9 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Quantizing both weights and activations of large language models to low-bits can reduce memory access and accelerate computation, yet activation outliers often cause severe accuracy degradation. Orthogonal rotations alleviate this problem by

---

### [85] MedSkill-E$^{2}$: Evaluating and Evolving Skills for Medical Agents

**链接**: https://arxiv.org/abs/2611.34250
**作者**: Jingjing Hua, Shaocong Wei, Jianghan Shen, Junzhi Ning, Min Cen, Cheng Tang 等 (10 人)
**来源**: cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly use skills to access domain knowledge and complete real-world tasks. We observe that even when a skill specifies the rules and procedures needed for a task, agents may fail to apply them effectively during autonomous execution, a phenomenon we call skill Enable But Underuse (EBU). This issue is particularly consequential in medical tasks, where overlooking a single critical constraint can yield a plausible but incorrect result. To evaluate and address EBU, we introduce MedSkill-E$^{2}$, a framework for evaluating and evolving skills for medical agents. We construct EBU-Bench, a challenging benchmark covering 12 medically relevant task groups and associated skills, to evaluate agents' ability to use available skills autonomously. We quantify the EBU gap as the difference in skill-use accuracy between autonomous use and explicitly guided reading and application of the same skill. On EBU-Bench, all evaluated model-harness combinations exhibit

---

### [86] A zero LLM fine-tuning framework for demand response management in grid-responsive buildings through thermostat-based control

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0378778826016348&hl=zh-CN&sa=X&d=1256293194868587824&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv4Rnxked3RC_Q2Rr7sYnt_1&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=1&folt=kw-top
**作者**: X Dai, M Wu, C Yuen - Energy and Buildings, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -RAG framework, the LLM -only framework may rely too much on the inherent knowledge and therefore fail to provide satisfactory control performance. In conclusion, the LLM … under LLM -only and LLM -RAG frameworks to test if the

---

### [87] AiFlow: Construction-to-Retirement Conformance for Versioned LLM Services

**链接**: https://arxiv.org/abs/2608.00558
**作者**: Qunhui Zhang
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [88] Scalpel and Brush: Pruning and Targeted Weight Editing of a Small Language Model by a Single LLM Agent

**链接**: https://arxiv.org/abs/2611.33426
**作者**: Sergei Koltcov, Vera Ignatenko, Anton Surkov, Rabie Abdultawab Ramadan
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> It has recently been shown that an LLM can itself edit the weights of a language model, yet it remains unclear which part of such a result is due to the agent and which part is reproduced by a random edit of the same shape, by an instruction in the prompt, or by a standard procedure without an LLM. We unify repair and pruning as sparse weight edits to optimize a metric we specify, using BLEU as an example: three tasks -- targeted weight repair ("brush"), structured MLP neuron pruning ("scalpel", zeroing pruned weights), and layer removal with repair - are assigned to a DeepSeek Harness agent powered by DeepSeek-V4.1-Flash, with up to 50 dev evaluations. We study Qwen2.5-Math-1.5B-Instruct in three independent runs per task, with final evaluation on two hidden splits. On ordinary differential equations, changing at most 0.0084% of weights raised test BLEU by 24-32% on second-order equations and by a factor of 1.8-2.5 on equations with polynomial right-hand sides. An independent substitu

---

### [89] Understanding Failure Patterns in LLM-Based Mathematical Optimization Modeling

**链接**: https://arxiv.org/abs/2611.33351
**作者**: Ryoichi Takase, Xian Yeow Lee, Hikaru Tomonari, Masaya Tsunokake
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial optimization involves complex constraints, making optimization modeling difficult to automate. Large language models (LLMs) have been explored for generating optimization models from natural language, but their reliability in end-to-end settings remains limited, often producing non-executable, infeasible, or feasible but incorrect solutions. In this work, we study failure modes in LLM-based optimization modeling by decomposing the process into three components: mathematical reasoning, solver usage, and domain knowledge, and constructing datasets that target each aspect. Using these datasets, we analyze how different components relate to errors and find that they are associated with different types of failure, although these relationships are not always strong or consistent. Furthermore, while combining these components improves execution reliability, feasible but incorrect solutions remain the dominant failure mode, suggesting a remaining gap between executability and correc

---

### [90] From model uncertainty to appropriate reliance: A large-scale multi-model evaluation of LLM uncertainty and a simulation of its communication

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0950584926003940&hl=zh-CN&sa=X&d=6555751294323018110&ei=CL0Ha-avPPvP6rQP--rvwQw&scisig=AIL1Nv42bGDxZjAYZw7O9cXBJ8XM&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=8&folt=kw-top
**作者**: L Sánchez-Pravos, J Parra-Domínguez, S Rodríguez… - Information and Software …, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Context: Large language models (LLMs) produce fluent answers even when wrong, so their benefit depends less on accuracy than on whether users can tell when to rely on them. Uncertainty estimation and human trust are studied separately;

---

### [91] NORMCRAFT: Cultural Norm Generation for Context-Aware Language Model Alignment

**链接**: https://arxiv.org/abs/2611.33726
**作者**: Tangyuan Zhang, Zhuang Li, Fatemeh Shiri, Xiangyu Zhao, Junyu Yan, Xiuzhen Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cultural alignment requires large language models (LLMs) to infer often-implicit social norms from a scenario and its cultural context. Existing approaches typically adapt individual models or supply external cultural knowledge, while learning norm inference independently of downstream response generation remains underexplored. We introduce NORMCRAFT, a modular framework that decouples norm inference from response generation. Through norm-centric multi-view supervision, we train an LLM as a norm generator to recover shared norms from prospective, adherence, and violation scenarios without downstream response labels. The generated norms guide a separate, frozen LLM (the responder). With Qwen3.5-4B as the responder, NORMCRAFT outperforms prompting and supervised fine-tuning (SFT) baselines on four of five downstream metrics. On SafeWorld, its responses reflect the reference norms more often (Coverage) and more precisely (Faithfulness), exceeding Responder SFT by 18.0 and 14.1 percentage 

---

### [92] Confidence scores for gated automation of large language models

**链接**: https://arxiv.org/abs/2611.33394
**作者**: Luiz G. A. Alves, Aaron Vermeersch
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI agents built on large language models (LLMs) demonstrate strong capabilities in automated decision-making. However, LLMs may produce incorrect answers with high confidence, limiting their applicability in decisions that affect individuals and organizations. Reliable confidence scores are necessary to gate such decisions, and existing estimates are frequently unavailable or too coarse to support effective gating. This work uses supervised learning to train models to predict the correctness of LLM-generated answers, enabling automated confident responses and routing uncertain ones for human review. A linear confidence score head is fitted to the final-layer hidden state of the frozen LLM backbone, and text-only metamodels are trained as an alternative for closed models. All results come from a single 2B-parameter backbone, on graded answers that are about 98% SQuAD and the remainder TruthfulQA. Against multiple baselines, the confidence score head outperforms all baselines and metamod

---

### [93] Semantic Density Does Not Predict Agent-Memory Collapse

**链接**: https://arxiv.org/abs/2611.33184
**作者**: Saksham Gupta, Yash Choudhary, Arpit Upadhyay
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Persistent textual memory can improve LLM agents, but repeated updates can erode task performance. We ask whether memory-store statistics warn before held-out accuracy declines. We registered mean pairwise cosine similarity ($\rho$) and 13 additional geometry, retrieval, and graph statistics on 805 snapshots from 13 memory methods across ALFWorld, AppWorld, ScienceWorld, WebShop, and two ARC-AGI settings. These methods store trajectories, rules, workflows, strategies, or linked records, using selective retrieval or whole-store prompting. No such statistic reliably predicted early signs of task accuracy decline, and $\rho$ had zero median lead. With the checkpoint after peak accuracy as a secondary decline point, measures of highly similar pairs and nearest-neighbor crowding changed earlier but did not consistently outperform stored-item count. We trained classifiers on this corpus and applied them unchanged to PropWorld runs of up to 5,000 crafting tasks. They falsely flagged 56.9% of 

---

### [94] MeterRouter: Budget-Aware Dynamic Routing for Multi-Agent Systems

**链接**: https://arxiv.org/abs/2611.34327
**作者**: Yue Xu, Leikun Yin, Ruiming Min, Yufeng Lai, Justin Andrew Johnson, Sitao Luan 等 (7 人)
**来源**: cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent systems (MAS) built on large language models (LLMs) outperform single-agent systems, but inter-agent communication incurs substantial token overhead. While assigning a large LLM to every agent is common, it results in inefficient resource utilization, leaving the system far from the Pareto frontier. The cost of answering a query is set jointly by how many agents are recruited, the role and LLM assigned to each, and communication topology among them. Most existing routers treat cost only implicitly rather than as an explicit optimization constraint. A fixed accuracy-cost preference also cannot express how much a caller is willing to pay for a particular query. We introduce MeterRouter, a budget-aware dynamic router that incrementally synthesizes a collaboration graph by selecting each agent's role, LLM, incoming connections, and termination conditioned on the query and a per-query monetary budget. We initialize the router by imitating successful execution graphs, then jointl

---

### [95] Make the Adversary Spend More: Stateful Deception as a Cost-Exchange Primitive for AI-Era Cyber Defense

**链接**: https://arxiv.org/abs/2611.34770
**作者**: Alessandro Cantelli-Forti, Isabella Marasco, Hosam Alamleh, Giada Boschi, Michele Colajanni
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are transforming the economics of intrusion by reducing the attacker's cost to scan and adapt, while tempting defenders into unbounded compute. We argue that cyber deception should be judged by the cost exchange it imposes, not by realism or detection, and that the primitive making that exchange favorable is adversary-specific persistent state. Rather than a honeypot that resets or merges sessions, each recognized adversary re-enters the world it believes it has compromised, kept coherent with its own past actions and isolated from every other adversary, while the language model acts only as a constrained renderer of explicit state, never as its store. We formalize the trade-off as a Deception Exchange Rate (DER), relating mission-weighted adversary effort burned to defender resources spent, and instantiate it in an SSH honeypot pairing Cowrie with a local LLM. In this paper, we focus on the defender-side evaluation of that exchange, while specifying, but n

---

### [96] Refusal Is Not Scored: A Coverage Limit in Content-Based Bias Evaluation

**链接**: https://arxiv.org/abs/2611.33690
**作者**: Afifah Kashif, Malak Sadek, Jin Huang, Hatice Gunes
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Bias audits of conversational models often discard refusals (responses such as "I can't assist with that request") before scoring, a filtering step which is rarely examined as a measurement decision even though it determines which responses an audit is capable of evaluating. This work examines what the step removes, applying seven bias-evaluation instruments spanning both deployed paradigms, three dictionary-based and four LLM-as-judge, to two intersectional datasets of 360 generated responses each. In both datasets, the filter removed a demographically skewed subset produced entirely by one of the three responder models, which refused North Korean prompts at 2.15 times the rate of American prompts on declarative content and 1.76 times on operational content. We then remove the filter and pass every refusal to all seven instruments. Bias-Lexicon scores refusals as clean, and including them shrinks the nationality disparity it reports. HurtLex appears to register the disparity, but we t

---

### [97] vSFT: Learning to Verbally Tune Agents at Test Time

**链接**: https://arxiv.org/abs/2611.34440
**作者**: Qishuai Wen, Rui Chen, Haiwen Li, Zhiyuan Huang, Qiwen Gu, Bingjie Gao 等 (10 人)
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly improved via agentic reinforcement learning, which can be on-policy but suffers from expensive rollouts and sparse rewards, limiting its application at test time. In this paper, we present a verbally Supervised Fine-Tuning (vSFT) framework that enables the conjunction of dense feedback in natural language and weight updates at test time. Specifically, our vSFT forms a closed loop between an agent and a supervisor via a hypernetwork, in which the supervisor generates verbal supervision from the agent's failed trajectories, and the hypernetwork converts that supervision into low-rank weight updates to tune the agent. We validate that this test-time in-parameter evolving process outperforms both its in-context counterparts and prevalent reinforcement learning methods. In particular, our vSFT using Qwen3-4B outperforms GRPO and Reflexion by 8.7% and 13.9% in success rate on ALFWorld, and by 4.8% and 18.2% on WebShop, respectively. We believe tha

---

### [98] JOVE ICE: Intent Guided Cloud Edge Device Collaboration for AI Glasses

**链接**: https://arxiv.org/abs/2611.33735
**作者**: Yuyang Jin, Bingfeng Pi, Jiamei Sun, Wei Jin, Dongyang Wang, Yunpeng Li 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) and LLM based agents have expanded the capabilities of AI glasses, enabling egocentric visual question answering, memory retrieval, and proactive assistance. These applications involve diverse inputs, including speech, images, and video, and range from simple device control to complex visual reasoning, posing challenges for efficient computation and communication. While video centric capabilities have received considerable attention, simple text based and device executable tasks remain underexplored despite their prevalence in daily interactions. Efficiently supporting diverse workloads within a unified assistant remains an open challenge. We propose JOVE ICE, an intent guided cloud, edge, and device collaborative framework that routes requests among AI glasses, a paired smartphone, and cloud servers according to user intent. JOVE ICE integrates hierarchical intent classification with dynamic subagent orchestration to select efficient exe

---

### [99] Who Attributes a Mind to Whom? Mutual Theory of Mind in Simulated User-Assistant Conversation

**链接**: https://arxiv.org/abs/2611.33327
**作者**: Mingxi Yan, Vasudha Varadarajan, Qiaosi Wang, Qing Xiao, Hong Shen, Jodi Forlizzi 等 (7 人)
**来源**: cs.CL cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When users assume that an AI chatbot has mental states, they are more likely to develop over-reliance, emotional dependence, and in extreme cases, psychological harm or self-harm. However, how these mind attributions arise in conversations and how human or AI factors influence this is still unknown. We study how users attribute minds using a minimal framework: a simulated user with different characteristics chats with assistants that differ in social style and memory. We also introduce a message-level measure of who attributes a mind to whom in four directions, checked with trained coders and applied by a fine-tuned encoder that reproduces an LLM judge. Our results show that, on average, nine out of thirteen characteristics raised simulated users' attribution to the assistant. We found that relational needs such as attachment anxiety raised it as theory predicts, some general personality traits raised it as well, and AI-specific characteristics the least. By contrast, the assistant's s

---

### [100] IRTIQA: Evolving in English, Evaluated in Urdu -- Does Agent Self-Evolution Transfer from English to Urdu and Code-Switched Input?

**链接**: https://arxiv.org/abs/2611.34303
**作者**: Abdullah Hashmat, Danish Javed, Usman Naseem, Agha Ali Raza
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As LLM agents increasingly learn from their own experience, the tasks they learn from and are evaluated on are almost always in English. We ask whether self-evolution transfers from English to Urdu, and release IRTIQA, a benchmark of aligned English, Urdu-translated, and Urdu code-switched variants of DROP, SNIPS, AppWorld, and SkillsBench, built with a matrix-language code-switching pipeline and human verification. Using IRTIQA, we evaluate three self-evolving frameworks, Tool-R0 (self-play RL), AgentEvolver (experience-guided RL), and Autogenesis (protocol-level evolution), against their unevolved backbones. Self-evolution often raises capability: AgentEvolver lifts AppWorld goal completion from near zero to 20-36% across all conditions, and Autogenesis improves SkillsBench pass rate from 16.48% to 22.22%. But it rarely closes the language gap. Evolved systems remain stronger in English, by up to 0.26 DROP F1, the gap is largest on multi-step tasks, and code-switching behaves as a di

---

### [101] When Are Parallel Subagents Effective for Coding? An Empirical Study on Repository Construction

**链接**: https://arxiv.org/abs/2611.33893
**作者**: Zhiheng Lyu, Chengyu Yin, Lingming Zhang
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based coding agents are increasingly used for long-horizon tasks such as building an entire program from a specification. Products like Codex and Claude Code let an agent delegate work to parallel subagents, multiplying run cost, yet it remains unclear whether and when delegation produces a better program. We compare a single agent with a main agent delegating to subagents on repository-construction tasks from NL2Repo and ProgramBench (which also provides an executable reference program). We compare scores at equal time and equal cost, run intervention experiments, and analyze fine-grained behavior. On randomly drawn tasks, parallel subagents raise hidden-test pass rates by only about 1 to 5 percentage points at up to 3.8x the cost of a single agent. Their gain is larger on hard tasks, where we find evidence of three mechanisms. Self-checking: with GPT-5.6 Sol, one sentence telling a single agent to probe the reference program first recovers most of this gain at a fraction of the c

---

### [102] FORK: Co-Evolving Safe Disclosure and Decision Skills Against Attackers Who Read Every Refusal

**链接**: https://arxiv.org/abs/2611.33879
**作者**: Hieu Man, Chao Shang, Rui Dong, Devang Kulshreshtha, Yanjun Qi, Sandesh Swamy
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When a guardrail rejects an LLM agent's action, its message reaches any attacker observing the trajectory: a fixed refusal leaves benign users unable to recover, whereas an explanation can tell the attacker what to try next. We study this as safe disclosure: explaining rejections so that authorized tasks recover without increasing adaptive attack success. Safe disclosure depends on both the decision and the message: what the guardrail blocks and what it reveals to the agent and the attacker. Because hand-written rules alone cannot anticipate how adaptive attackers probe decisions or use messages, we introduce FORK, which co-evolves a guardrail's natural-language decision and disclosure skills with an attacker that reads every public message. Each exploited message and permissive decision gives FORK evidence for a gradient-free revision of its natural-language skill library. We evaluate FORK on four benchmarks. Averaged over three agents on FORK-World, FORK cuts attack success rate (ASR

---

### [103] Few-Shot Adaptation of Vision-Language Models via Agentic Model Editing

**链接**: https://arxiv.org/abs/2611.34036
**作者**: Yusheng Zhao, Xiao Luo, Zhiping Xiao, Ming Zhang
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Few-shot adaptation transfers pretrained Vision-Language Models (VLMs) to new domains using a small set of labeled images. Most methods fit prompts, representations, or classifiers within an adaptation procedure specified in advance. Yet the visual distinctions needed for recognition can differ substantially across domains, motivating the question: Can an LLM agent use few-shot examples and model observations to design the adaptation procedure itself? We propose Agentic Model Editing (AME), an agentic framework that jointly designs input transformations, encoder edits, feature computation, and classifier fitting as an executable, domain-customized adaptation program. The agent inspects images, class semantics, model parameters, intermediate representations, and activations to formulate hypotheses about the target task. It implements and tests candidate programs on the support set, with aggregate validation accuracy guiding refinement and selection. Each program fits a complete domain m

---

### [104] AutoRSP: An AI Agent for Radar Sensing Pipeline Design

**链接**: https://arxiv.org/abs/2611.34754
**作者**: Zhi Zheng, Xincheng Xie, Avery Gump, Sacha Jungerman, Hongyang Li, Yin Li 等 (8 人)
**来源**: cs.NI cs.MA eess.SP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radar sensing demands a pipeline that is well-thought-out across hardware and software. We ask whether an AI agent can automatically design radar sensing pipelines at a fraction of the time, cost, and expertise that current practice needs. We present AutoRSP, an agent that embeds radar-system-level structure through sub-agents mapped to five stack layers, a code-based representation of every layer with explicitly modeled cross-layer dependencies. Feedback for the agentic search process comes from a pipeline of realistic RF simulation, on-sensor emulation, and execution on real edge devices, rather than from an LLM judge. Because such feedback can be slower than an LLM call, we present methods to efficiently optimize agentic loops. We evaluate AutoRSP on robotic imaging, automotive perception, and vital sign sensing. It produces executable pipelines with performance comparable to or better than human-expert pipelines and closed-source agents. AutoRSP's harness, tools, and benchmarks wil

---

### [105] RadOncGym: An Agent-Based Framework for Radiotherapy Dose-Mimicking Optimization

**链接**: https://arxiv.org/abs/2611.33821
**作者**: Tong Miao, Shupeng Cheng, Xiwen Chen, Ruishan Liu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI dose-prediction models generate patient-specific 3D dose distributions from patient anatomy, providing an important intermediate representation for automated radiotherapy planning. However, an AI-predicted dose must undergo downstream optimization to produce a physically constrained treatment plan, a process that requires balancing competing planning objectives. We present RadOncGym, an agent-based framework that enables an LLM agent to iteratively tune 12 planning-objective weights for dose-mimicking optimization. To reduce iterative evaluation cost, RadOncGym incorporates a surrogate verifier that provides rapid feedback while allowing the agent to decide when to request a full planning solve within a fixed solve budget. We evaluate RadOncGym on 60 OpenKBP head-and-neck patients, each paired with 10 predictions from OpenKBP-Opt dose-prediction sets, yielding 600 patient-prediction contexts per experimental configuration. Under RadOncGym's 16-turn setting with a three-solve budget,

---

### [106] Focus On Facts: Stylistically Invariant and Factually Sensitive Text Embeddings

**链接**: https://arxiv.org/abs/2611.33250
**作者**: Maximus Adeola
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Text embedding models can conflate surface-form similarity with factual identity. Given an altered near-copy with one corrupted fact and a differently worded fact-preserving rewrite, the base model prefers the altered near-copy. We test whether hard-negative contrastive supervision can reduce this surface-similarity shortcut. We construct FOF-Bench, an 83,263-triplet benchmark spanning five domains. Each anchor is paired with an LLM-generated, fact-preserving stylistic rewrite and a matched fact-altered near-copy. We fine-tune FOF-80M (Focus On Facts), an 80M-parameter embedding model, with a triplet contrastive objective that ranks the rewrite above the factual alteration. On 8,327 held-out test triplets, the base model chooses the factually altered text in 99.58% of cases (0.42% factual preference rate; mean separation -0.1650). After fine-tuning, mean positive--negative separation is +0.0329, 98.5% of individual margins move in the intended direction, and the preference rate reaches

---

### [107] Multimodal Safety Evaluation of Vision-Language Models in Japanese

**链接**: https://arxiv.org/abs/2611.33789
**作者**: Su Myat Noe, Hisami Suzuki, Kouta Nakayama, Naoaki Okazaki
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-Language Models (VLMs) are increasingly deployed in Japanese-language settings, yet multimodal safety evaluation has been largely English-centric. We extend the Multimodal Safety Test Suite (MSTS) of R\"ottger et al. (2025) to Japanese as the 12th language, contributing 320 machine-translated and post-edited cases with reference answers plus 82 culturally localized Japanese images. We introduce an evaluation framework that (i) extends MSTS's 3-class safety grouping with a 5-point scale that also rewards useful (not just safe) responses, and (ii) separates image recognition from safety judgment to isolate recognition errors. Using this framework, we evaluate five modern Japanese VLMs (Gemini-3-Flash, GPT-5, InternVL3, LLM-JP-4-VL, Qwen3-VL) against human evaluation, and find substantial variance in the safety readiness across the models. Finally, we evaluate two LLM-as-a-Judge models and find that providing a reference answer improves agreement with human safety judgments, though

---

### [108] Do We Still Need Reinforcement Learning When We Can Read the World Model?

**链接**: https://arxiv.org/abs/2611.34656
**作者**: Mingchao Zhang, Miduo Cui, Kangze He, Yuanjun Li, Dapeng Li, Ce Zhang 等 (10 人)
**来源**: cs.LG cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reinforcement learning has achieved remarkable success in sequential decision-making, but learning effective policies often requires substantial interaction experience. Model-based reinforcement learning alleviates this dependence by leveraging world models, which are typically used to support planning or policy optimization. In this paper, we investigate an alternative paradigm in which autonomous LLM-based coding agents directly synthesize control policies by reasoning over readable world models. By examining environment source code, these agents translate environmental knowledge into executable decision rules and iteratively refine their policies using online feedback or offline data, without task-specific RL training. Experiments across diverse decision-making benchmarks show that synthesized policies match or outperform conventional RL methods while requiring substantially less experience. Further analyses reveal interpretable decision rules and how they evolve through feedback-dr

---

### [109] Anti-AI in the Wild: From Toxic Discourse to Action

**链接**: https://arxiv.org/abs/2611.33254
**作者**: Yage Zhang, Yukun Jiang, Ziqing Yang, Yihan Ma, Xinyue Shen, Yang Zhang
**来源**: cs.SI cs.AI cs.CR
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Online discussion of generative AI has become increasingly contentious, and communities devoted to supporting, opposing, or debating AI have emerged on social media. Some of these communities take anti-AI actions, such as deploying crawler tarpits and data-poisoning services to interfere with data collection and model training. Yet, the scope of these actions and their relationship to online discourse remain poorly understood. In this paper, we present the first measurement study of online conflict over generative AI, from toxic discourse to anti-AI actions. We collect 931,640 posts from 25 Reddit communities, label them with a large language model detector validated against human labels, identify 3,312 anti-AI actions, and trace the output of three deployed anti-AI tools. Our analysis reveals that 30.0% of posts in communities devoted to this conflict are toxic, compared to 4.4% in general AI communities. Anti-AI actions in these communities mainly target AI crawling or model training

---

### [110] ZeroHero: Training Small Language Agents from Scratch

**链接**: https://arxiv.org/abs/2611.34635
**作者**: Nikita Sorokin, Zoya Volovikova, Alexey Skrynnik, Aleksandr Panov
**来源**: cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large pretrained language models provide capable policies for interactive tasks, but how much model capacity is necessary for a specialized language agent? We introduce ZeroHero, a framework for training small language agents (SLAs) from scratch. In each environment, a large language model acts as the expert, and we collect its successful trajectories. We pretrain each SLA, which has fewer than 50 million parameters, to predict the expert's responses given the interaction history. We then post-train the agent on its own interactions using proximal policy optimization (PPO). During post-training, reasoning alignment supplements environment rewards with expert supervision on the language the agent generates alongside its actions. We evaluate the agents in three multistep environments where acting requires both understanding and generating language. In Crafter, agents interpret textual observations and generate reasoning before acting. In WebShop, they translate shopping instructions into

---

### [111] Benchmarking Open-Ended Vulnerability Discovery in Windows Kernel Binaries

**链接**: https://arxiv.org/abs/2611.33486
**作者**: Jongseong Kim, Hwiwon Lee, Dongjun Kim and Lingming Zhang
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier models are increasingly used to discover real-world security vulnerabilities, making it critical to systematically evaluate their cybersecurity capabilities. However, existing security benchmarks primarily focus on known vulnerabilities in open-source projects, largely overlooking closed-source binaries, which underpin much of the software industry. In this paper, we ask: how effective are frontier models at uncovering deep vulnerabilities in production binaries? To answer this question, we present DeepBinary, the first comprehensive benchmark for open-ended vulnerability discovery in Windows kernel binaries. Given a target binary, an agent analyzes it using a disassembler and kernel debugger in network-isolated VMs and reports each vulnerability with a crashing proof of concept (PoC). Unlike existing benchmarks, DeepBinary replays every report on fresh VMs and employs an LLM-based judge to assess its validity, uniqueness, and impact (estimated by bug bounty values). Beyond kn

---

### [112] The Linguistic Knowledge Benchmark: Do Language Models Know the Foundations of Early-Grade Literacy?

**链接**: https://arxiv.org/abs/2611.34823
**作者**: Maxime Leli\`evre, Alasdair Mackintosh, Dominic Andrews, Tobias Murray, Moritz Boos, Oliver G. B. Garrod
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Many languages of instruction in low- and middle-income countries (LMICs) are poorly represented in the data used to train language models. Before these models can support early-grade literacy in such languages, we need to know whether they hold the linguistic knowledge of each language that literacy teaching relies on. To test this, we present the Linguistic Knowledge Benchmark and the reproducible, largely automated pipeline that turns curriculum documents, teacher guides and pupil books into a vetted question set organised on a fixed grid of nine linguistic domains and seven grade levels. The pipeline combines LLM-driven source survey, feature consolidation, item generation and quality control with an item-selection step inspired by item response theory and a final expert review. We instantiate it for Kiswahili (Kenya; 135 items) and English (United Kingdom; 137 items) and evaluate 121 and 119 models respectively. Frontier models exceed 90% accuracy in both languages, but accuracy f

---

### [113] Modality-Shift Contrastive Decoding for Temporally Grounded Audio-Visual Understanding

**链接**: https://arxiv.org/abs/2611.34162
**作者**: Minyeong Jeong, Yeonju Kim, Yong Man Ro
**来源**: cs.CV cs.SD
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio-visual large language models (AV-LLMs) are designed to represent the temporal structure of audio and video, yet it remains unclear how effectively they use this temporal information to relate sounds to visual events. To examine this, we probe an AV-LLM on an audio-visual synchronization task by shifting the audio so that the queried sound overlaps a different visual event. We observe that the model still favors the originally aligned event over the newly aligned one, indicating limited sensitivity to changes in audio-visual temporal alignment. To address this, we propose Modality-Shift Contrastive Decoding (MSCD), a training-free decoding method that emphasizes audio-visual temporal alignment in model predictions. MSCD contrasts logits under preserved and disrupted temporal alignment to favor predictions supported by aligned audio and video. We disrupt this alignment by temporally shifting either the audio or the video, while keeping the other modality fixed. Extensive evaluation

---

### [114] AI Persona Dialogue Pipeline; From Survey Report to Conversational Personas, Evaluated by LLMs and Experts

**链接**: https://arxiv.org/abs/2611.33736
**作者**: Jinyoung Jeong, Inhee Cho, Byungju Kim, Jiwon Baek, Youngjae Yoo
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulating dialogue of a population with LLM-enacted personas is increasingly common, yet each pipeline is generally built for one task, so a new task usually means reworking how the persona is authored, enacted and evaluated. We present an end-to-end persona dialogue pipeline meant to carry over to other populations as a whole; a background is written by an LLM from a national survey report, an off-the-shelf LLM enacts it without fine-tuning, and both are rated for perceived plausibility. We apply it to thirty personas of Korean older adults living alone; three LLM judges compare eight simulator LLMs, and thirty experts who work with this population evaluate the selected one, GPT-5.5. Experts found the backgrounds and dialogues largely realistic but most often faulted a persona for being more capable than its background said, and agreement between their ratings and the LLM judges could not be established. We release the pipeline, personas and their dialogues.

---

### [115] Failure Broadens, Success Sharpens: Continual Adaptation of Tool-Use Agents Across Diverse Tasks with Dual-Polarity Memory

**链接**: https://arxiv.org/abs/2611.33612
**作者**: Tianmai M. Zhang, Hoda Shajari, Amr Hendy, Xiaohu Liu, Piyush Behre, Omar Zia Khan 等 (7 人)
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents can self-improve over time by utilizing procedural memory derived from prior task trajectories, yet the distinct utilities of memories derived from local successes and failures remain underexplored. This work studies this question in a realistic setting with heterogeneous streams of multi-domain tool-use tasks and various environment constraints common in real-world scenarios. We develop \emph{Dual-Polarity Memory with Periodic Maintenance} (DualPM), a simple, retrieval-free memory workflow characterized by (1) customizable reflection and procedural memory generation from both local successes and failures within each trajectory, and (2) periodic memory consolidation over long task streams under a given memory capacity, preventing memory explosion. Online prequential evaluation with fine-grained metrics reveals that failure memory more strongly broadens coverage, success memory better streamlines execution, while combining both polarities effectively integrat

---

### [116] Under the Influence -- of What? A Controlled Evaluation of Influence Functions

**链接**: https://arxiv.org/abs/2611.34373
**作者**: Johannes Gabriel Sindlinger, Arzu Burcu G\"uven, Rob van der Goot, Anna Rogers
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Influence functions are a promising way to identify which training examples are responsible for a model's output. However, so far empirical evaluations on LLM pretraining level only assumed that they work as intended. This is the first work to systematically evaluate whether the 'influential' examples actually have properties relevant to a language model output, based on re-training with controlled data splits. We investigate three prominent Hessian approximation methods (GradSim, TrackStar, K-FAC) in two settings (linguistic phenomena and factual knowledge) in GPT-2 type models (68M-5.6B training tokens). We find that on average, the `influential' examples are indeed relevant, but they do not always bear the target properties directly, and the ratio and kind of relevance varies by setting.

---

### [117] Searching Ultra-Long Videos with Decision Models

**链接**: https://arxiv.org/abs/2611.33368
**作者**: Ce Zhang, Baiqi Li, Seongsu Ha, Gedas Bertasius
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Understanding ultra-long videos requires retrieving sparse, query-relevant evidence from extensive video histories. Existing similarity-based retrieval methods are efficient, but they encode the question and the video content independently and thus often miss evidence whose relevance requires reasoning over both. Generative large language models (LLMs) can perform such reasoning, but they typically generate text over multiple rounds of search, which makes each query slow and costly. In this work, we introduce DeLoVi (Decision Models for Long Video), a framework that leverages pretrained decision models to retrieve evidence from ultra-long videos. Like an LLM, a decision model reads the question together with the candidate evidence, so it can reason over both. Unlike an LLM, it directly outputs a relevance score without generating text, which makes it fast and inexpensive. We first present DeLoVi-S, a simple method that generates captions for short video clips and uses a decision model 

---

### [118] PersonaFactory: Stylistic User Prompt Augmentation with Synthetic Persona Bank

**链接**: https://arxiv.org/abs/2611.34785
**作者**: Bich Ngoc Doan, Hanna Yukhymenko, Imanol Schlag
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models increasingly replace real people in the AI development pipeline, as they are used to generate training dialogues at scale and to drive alignment and evaluation. However, out-of-the-box models produce monolingual and stylistically flat texts as synthetic user prompts, failing to replicate the real user-AI communication mechanics. We present PersonaFactory, an end-to-end pipeline that generates detailed user personas and uses them to augment existing user prompts from their point of view, producing a bank of over 740000 structured synthetic personas detailing their background and communication behaviors, and a corpus of roughly 1.24 million persona-styled synthetic conversations spanning 85 languages. We evaluate the effect of personal features on style adoption and intent preservation, using an LLM-judge and heuristic metrics to assess augmentation fidelity together with the downstream impact on assistant persona control through training data. Results show that our

---

### [119] A Semantics-First Approach to Multimodal Video Captioning with Frozen Encoders and Stabilized Reinforcement Learning

**链接**: https://arxiv.org/abs/2611.33409
**作者**: Albert Chiwara and Erhan Guven
**来源**: cs.CV cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We propose the Audio-Visual Query Transformer (AVQFormer), a highly efficient architecture built upon a 2.7B parameter LLM featuring a fixed-length $K=16$ semantic alignment module, stabilized via Adaptive Self-Critical Sequence Training (ASCST) with Entropy Regularization. Multimodal Large Language Models (LLMs) often rely on global audio representations to compensate for inefficient, frame-based visual encoders. While our Phase 1 prompted evaluations demonstrate that the Multimodal Base Model achieves strong deep semantic alignment (scoring 0.889 on BERTScore F1), optimizing this architecture for legacy metrics reveals a performance gap. We explore this gap as a hypothesis we term temporal alignment friction: a conflict where global audio representations disrupt the chronological sequence of visual frames, leading to penalties under visually-focused evaluation metrics. Consequently, by stripping away the audio, our Video-Only ablation conforms more closely to this rigid syntax, achie

---

### [120] What, Who, and When: Structured Harm Assessment for Mental Health Safety via Short Reasoning

**链接**: https://arxiv.org/abs/2611.33263
**作者**: Catarina Botelho, Ant\'onio Farinhas, John Mendon\c{c}a, Areti Vassilopoulos, In\^es Gon\c{c}alves, Maya D'Eon 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The growing use of large language models (LLMs) for mental health support raises important safety concerns. Existing guard models primarily identify categories of harmful content, often overlooking the context needed to determine an appropriate response. We introduce a clinically grounded taxonomy that characterizes harm along three dimensions: what the harm is, who is involved, and when it occurs. It further separates harm characterization from intervention decisions, thus enabling safety policies to be specified outside the model weights through explicit, clinician-curated instructions that can be updated and audited. We validate the taxonomy with expert clinicians and validate a panel of LLM judges to scale annotation. Relabeling public benchmarks in this taxonomy shows that they rarely contain harm directed at the user, which accounts for nearly half of the harm in real conversations. We then train MindGuard2, a 35B-A3B reasoning-based guard model using supervised fine-tuning on sh

---

### [121] Reliable User Simulation in Complex Multi-Step Workflows

**链接**: https://arxiv.org/abs/2611.34044
**作者**: Pusala Pavan Teja, Jayasimha Talur, Saab Mansour, Marcello Federico
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based user simulators are increasingly used to evaluate conversational assistants. Yet, these simulators can drift from their assigned goals or fail to exhaustively explore all specified options, causing evaluation errors incorrectly attributed to the assistant. Prior work has examined goal alignment in single-task settings, but many practical scenarios require simulators to execute multi-step workflows with sequential tasks, fallback logic, and cross-task dependencies, where simulator fidelity has not been measured. To close this gap, we introduce a benchmark of 500 workflows represented using the Hierarchical Task Network (HTN) abstraction. Our experiments reveal that the simulator's fidelity degrades sharply with workflow complexity, and that goal drift accounts for the majority of failures. Fidelity also depends on the assistant's response style, with the same simulator scoring substantially better or worse across styles. To address this, we propose ReUST (Reasoning + User Stat

---

### [122] Agent-as-a-Verifier: From Scores to Evidence for General Verification

**链接**: https://arxiv.org/abs/2611.34132
**作者**: Yuxuan Sun, Hao (Mark) Chen, Nagarajan Natarajan, Sushrut Karmalkar, Niranjani Prasad, Amit Sharma 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verification is increasingly critical across various inference and learning paradigms, such as test-time scaling, recursive intelligence and automated research, where feedback can improve efficiency and optimization. Common score-based verifiers, or discriminative reward models, predict a scalar reward for an output. While useful for filtering, rewarding, and ranking, such scores provide no explicit, auditable evidentiary basis for the judgment. In parallel, although existing generative process reward models offer text feedback, most designs do not fully exploit agentic capabilities, such as tool use and iterative reasoning, which are essential for fact-checking and fine-grained claim verification. In this paper, we address these limitations by introducing Agent-as-a-Verifier, an agentic, certificate-producing verification system that places role-separated LLM agents inside a formal-methods-inspired claim-obligation-certificate protocol. Given a generation candidate, Agent-as-a-Verifie

---

### [123] TASK Memory: Beyond Text-Only Memory with Activation Steering and Knowledge Editing against Memory Hallucination

**链接**: https://arxiv.org/abs/2611.34762
**作者**: Jinkun Zhao, Wenjun Wu
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly rely on external memory, yet they still hallucinate about what they remember. Often the correct memory is retrieved and placed in the prompt, but the answer contradicts it or the memory is applied to the wrong question. We call these use-time memory hallucinations. Across five open models, we find that they arise from the conflict between parametric knowledge and external memory and take three forms: memory-ignoring, where the model returns to a stale fact in its weights (up to 46% of queries); memory-misapplying, where it attributes the memory to unrelated entities (up to 24%, and 49% when retrieval is combined with weight editing); and version confusion, where 53% of answers about revised facts assert the superseded value when both versions remain stored. We propose TASK memory, which goes beyond text-only memory by combining a Text note with Activation Steering and Knowledge editing that share one in-model address. The text holds the content. A removable know

---

### [124] Puzzling-Bench: Evaluating Language Models on 23,777 Human-Written Puzzles with Community-Verified Answers

**链接**: https://arxiv.org/abs/2611.34331
**作者**: Abhinav Sharma, Li Li, Chien Van Nguyen, Sai Karthik Navuluru, Bo Ni, Xiangbo Gao 等 (10 人)
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce Puzzling-Bench, a benchmark of 23,777 puzzles with community-verified answers drawn from the Puzzling Stack Exchange archive (2014-2026): riddles, ciphers, logic grids, lateral-thinking problems, wordplay and recreational mathematics, a third of them with images. Every puzzle carries the answer accepted by its author, a short reference answer taken from it (LLM-extracted for the evaluation sets and checked on a 50-puzzle human review), the author's own hints, community tags and a creation date, so that the benchmark supports hint ablations, category analysis and a rolling post-cutoff slice (254 puzzles posted after the training cutoff of six of the nine models we evaluate, including the best one) as a contamination check. We evaluate nine frontier and open models with a two-tier scorer (normalized exact match, then an LLM judge) and validate the judge with three judges from two model families: they agree on 95-97% of verdicts (kappa 0.82-0.96), move no model by more than 1

---

### [125] Evaluating Large Language Models on conversational African American English: Feature classification and next-turn generation

**链接**: https://arxiv.org/abs/2611.33499
**作者**: Romeo De Timmerman, Thomas Demeester, Els Lefever
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are known to misinterpret and misrepresent regional and social varieties of English other than Mainstream American English (MAE), such as African American English (AAE), yet most evaluations of these biases have relied on synthetic, stylized or decontextualized data. This paper instead evaluates LLMs on authentic, conversational AAE to more closely reflect how such models may encounter AAE when deployed as chatbots. Concretely, we perform two complementary evaluation tasks on 100 six-turn segments randomly sampled from the Corpus of Regional African American Language (CORAAL; Kendall and Farrington, 2024), comparing three closed-weight LLM configurations: Gemini 2.5 Flash with and without reasoning, and GPT-4.1 mini. The first task compares the models against gold-standard manual annotations for five AAE morphosyntactic features, while the second assesses their ability to generate contextually appropriate next turns, evaluating outputs for AAE feature frequ

---

### [126] Decoder-as-a-Probe: Verbalizing and Steering Visual Representations in LVLMs

**链接**: https://arxiv.org/abs/2611.34515
**作者**: Adhemar de Senneville, Xavier Bou, J\'er\'emy Anger, Rafael Grompone, Gabriele Facciolo
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> It is commonly accepted that high-level concepts are represented linearly in the representation space of large neural networks. For Large Vision Language Models (LVLMs), finding those interpretable directions in visual representations is important for interpretability. To find them, the classical approach is to train a linear classifier on the representations, but it needs a large amount of labels and only recovers what can be read from the representations, not what the model actually uses. In this paper we start from the following insight: The LLM Decoder of an LVLM is also a classifier whose classes are the possible next tokens. So we use its first-order Taylor expansion as a linear classifier. Hence, we introduce Decoder-as-a-Probe (DaP), which significantly outperforms classical probing and steering baselines especially when training data is sparse. (1) It verbalizes what an LVLM perceives in a given image. (2) It can surgically change the perception of the LVLM about specific attr

---

### [127] FIG-MAC: A Fine-grained Inspiration Graph Empowered Multi-Agent Collaboration for Automated Scientific Hypothesis Generation

**链接**: https://arxiv.org/abs/2611.33563
**作者**: Siyuan Chen, Yuping Gao, Tai Huang, Yuling Zhou, Dongyu Su, Tongguan Wang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated Scientific Hypothesis Generation (ASHG) leveraging large language models (LLMs) aims to harness their strengths in knowledge integration, logical reasoning, and text generation for efficiently producing innovative, verifiable scientific hypotheses. However, existing approaches face three critical limitations: (i) insufficient fine-grained knowledge representation, as unstructured context impairs LLM comprehension and reasoning; (ii) lack of knowledge evolution traceability, constraining the generation of innovative cross-domain conjectures; (iii) absence of human-inspired and role-specialized multi-agent collaboration, failing to leverage the efficient innovation mechanisms arising from cognitive diversity and division of labor among expert roles to complete the full ASHG-evaluation loop. To address these limitations, we propose the Fine-grained Inspiration Graph-empowered Multi-Agent Collaboration framework (FIG-MAC) including: (i) Fine-grained Inspiration Graph module (FIG)

---

### [128] A Survey of Security, Privacy, and Ethics of Large Language Models in Telecom

**链接**: https://arxiv.org/abs/2611.34868
**作者**: Joy Bose, Srinivas Adyapak
**来源**: cs.CR cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly integrated into telecommunications for customer service, network analytics, and operational support. While offering efficiency and innovation, their deployment raises critical privacy, security, and ethical challenges due to the uniquely sensitive and longitudinal nature of telecom data. This paper presents a survey of LLM risks and safeguards in telecom context. Our survey introduces a telecom-specific taxonomy linking privacy, security, and ethics with use cases and outlines open research challenges such as longitudinal data privacy, cross-border compliance, and scalable guardrails.

---

### [129] RRA-IQA: Rating and Ranking Alignment for MLLM -Based Image Quality Assessment

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-981-92-7192-4_2&hl=zh-CN&sa=X&d=15933387324452630865&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv4Ro2xlGzbwlYb1-cZH_diD&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=0&folt=kw-top
**作者**: H Luo, T Wang, H Jia - International Conference on Image and Graphics, 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> (a) MLLM -based IQA score regression maps qualitylevel token probabilities to continuous … Reliable MLLM -based score regression should not only recover a continuous score from … , a lightweight Rating and Ranking Alignment framework

---

### [130] SEAM: A Self-Evolving and Adaptive Probing Framework for Automatic MLLM Hallucination Evaluation

**链接**: https://arxiv.org/abs/2611.34598
**作者**: Shiyu Zhang, Zengyi Wo, Yuming Liao, Ran He, Caifeng Shan, Yanbo Fan
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The severe susceptibility of multimodal large language models (MLLMs) to hallucinations poses a critical threat to their reliability, making a rigorous evaluation framework indispensable. However, existing evaluation pipelines largely rely on predefined test items, suffering from high construction costs, rapid obsolescence as MLLMs evolve, and ineffectiveness in probing model-specific weaknesses. To address these limitations, we propose SEAM, a self-evolving and adaptive probing framework for automatic MLLM hallucination evaluation. Specifically, SEAM introduces a composable Hallucination Probe Construction Library comprising ten hallucination-probing skills, three elicitation wrappers, and five question formats. Building on this library, SEAM establishes a dual-loop framework. In the inner loop (adaptive probing), skill-guided visual analysis, question composition, and hierarchical quality verification are coordinated with verifier and target-response feedback to refine test items and

---

### [131] SPiXSeg: Rethinking MLLM-based Image Segmentation as Superpixel Classification

**链接**: https://arxiv.org/abs/2611.33842
**作者**: Piyush Tiwary, Sohini Dutta, Prathosh A.P
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are widely used for image segmentation. However, existing methods either use a decoder or use patch-based approach which trades boundary precision against the number of decisions as coarse grid cells mix foreground and background pixels, while finer grids require many more predictions, and autoregressive mask generation adds sequential decoding overhead. We propose SPiXSeg, which shifts the output from per-patch to per-superpixel label assignment, using superpixel tokens formed by aggregating patch-level visual features. An off-the-shelf model partitions each image into task-agnostic superpixels, so the partition is computed once and reused across tasks. A Spix-to-Mask (S2M) module scores each superpixel token in a single MLLM forward pass by directly comparing the MLLM's hidden representations, without autoregressive generation or a separate scoring network, and the selected superpixels are mapped directly to pixels without refinement. Without 

---

### [132] SIR-Agent: Skill-Augmented Image Restoration Agent with Recursive Self-Improvement

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2611.27285&hl=zh-CN&sa=X&d=9301444185723170461&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv7dKyeMsj-9ONN7lBe6rUky&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=6&folt=kw-top
**作者**: Y Wang, Q Yan, W Zhou, M Zhang, A Niu, H Zhang… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Agents for Image Restoration (IR) aim to leverage Multimodal Large Language Models (MLLMs) to autonomously perceive image degradation and invoke IR tools. However, existing IR agents typically rely on fine-tuning MLLM parameters to adapt

---

### [133] The Dual-Tier Sentiment Framework: Scalable Multimodal UX Attribution in Web Search

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.27899&hl=zh-CN&sa=X&d=17604065413944947479&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv6bkEtjXKfePC3D-sp5EOJU&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=5&folt=kw-top
**作者**: Y Ding, G Kumar, R Min, I Ye, B Goyal, E Antunez… - arXiv preprint arXiv … 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> as the arithmetic mean of the individual result rewards ri (where ri reflects the MLLM ’s accuracy against the human rating for result i): R = 1 … Generating bounding boxes, summarizing landing pages, and running inference through a

---

### [134] Tracing Inherent Spatial Cues: Constructing Pixel-Grounded MLLMs without Training

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S2095809926006600&hl=zh-CN&sa=X&d=18371172480074358496&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv4N3nLyF0XeWt_UOi3kYlkw&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=4&folt=kw-top
**作者**: L Zhu, X Zhang, H He, Y Li, S Zeng, Y Lu - Engineering 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> (d) Our iTrace: tracing inherent spatial cues to bridge a frozen MLLM and mask decoder … on the conversational context generated by the MLLM , and synergizes them with phrase-level … -play framework that strictly preserves the MLLM ’s native

---

### [135] Video‐Based Automated Seizure Classification Using Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/pdf/10.1002/acn3.70574&hl=zh-CN&sa=X&d=8795704113802028343&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv7b0KUJekay40cDfVy3XuLD&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=1&folt=kw-top
**作者**: L Zhang, R Jiang, T Monsoor, JN Pasqua… - Annals of Clinical and …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We report the top 10 most informative MLLM - extracted features for ES versus NES classification. To directly quantify the independent contribution of seizure duration identified as a top predictive feature (Section 3.5), we additionally

---

### [136] A Closer Look at Dynamic Scene Graph Generation in the Era of Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://openreview.net/forum%3Fid%3DY1D9E4ZhwT&hl=zh-CN&sa=X&d=15527788043785321352&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv4i_RnKBHNyilKdNDMGksJj&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=8&folt=kw-top
**作者**: X Cui, JA Bhoi, CW Peng, A Kuek, SN Lim - The Fortieth Annual Conference on Neural …
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> From the model design perspective, we explore directly using MLLMs for scene graph generation and establish a strong MLLM -based DSGG baseline through three design changes. First, we replace the conventional bottom-up pipeline with a top-down

---

### [137] PonderPounce-WM: When Does Predicting the Future Help Context-Dependent Robot Control?

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.26996&hl=zh-CN&sa=X&d=8509333743765293354&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv4orASEOK2QugAAqXNpmstB&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=9&folt=kw-top
**作者**: J Jung, S Choi, Y Lee, Y Yu - arXiv preprint arXiv:2611.26996, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Building on PONDERPOUNCE’s use of a pretrained MLLM ’s native causal context as episode memory [4], we investigate how predictive supervision shapes this … This retains the MLLM context engine rather than introducing a video-generation

---

### [138] Navigent: A Geometry-Grounded Agentic Framework for Vision Language Navigation

**链接**: https://arxiv.org/abs/2611.34249
**作者**: Xinyu Zhou, Weiren Cai, Yitong Chen, Shenghai Yuan, Zihang Mu, Boyu Ma 等 (10 人)
**来源**: cs.AI
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-and-Language Navigation (VLN) with general-purpose multimodal large language models (MLLMs) offers a flexible alternative to task-specific navigation policies, while reliable long-horizon execution remains challenging. Agents must track navigation progress, detect discrepancies between commanded and actual motion, and recognize when movement has passed relevant landmarks or entrances. We present Navigent, an agentic VLN framework built around a frozen MLLM and a Geometry-Grounded Execution Critic (GEC). GEC performs two complementary checks: action-to-motion consistency, which evaluates measured displacement against commanded movement, and motion-to-landmark consistency, which tracks agent-selected visual anchors and entrance candidates in world coordinates. Detected discrepancies interrupt the remaining action sequence and trigger reobservation, local adjustment, or node-based recovery. Historical visual memory supports progress tracking across extended routes. An offline self-

---

### [139] Multimodal Large Language Models for Early Accident Warning: Evaluating MLLMs Viability for Drowning Detection Systems

**链接**: https://scholar.google.com/scholar_url?url=https://www.diva-portal.org/smash/record.jsf%3Fpid%3Ddiva2:2119830&hl=zh-CN&sa=X&d=804026205895377399&ei=Cb0Ha93AEfvP6rQP--rvwQw&scisig=AIL1Nv5XBcAIIGfBaP3gZAlQa7Iy&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=3&folt=kw-top
**作者**: M Pickering, HJ Sibbel Becker
**来源**: 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> MLLM :er utgör en lovande ny möjlighet genom att möjliggöra avancerat kontextuellt resonemang, vilket erbjuder potentialen att korrekt … att använda multimodala språkmodeller ( MLLM ) som primär detektionsmekanism i DDS-arkitekturer

---

### [140] ProbFaS: Probabilistic Video Frame Selection for MLLMs via Multi-Fidelity Calibration

**链接**: https://arxiv.org/abs/2611.34903
**作者**: Tianru Zhang, Mayank Nautiyal, Hugo Eidmann, Prashant Singh, Ekta Vats
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Processing long videos with multimodal large language models (MLLMs) is prohibitively expensive, making informative frame selection essential for accurate video understanding. The default uniform sampling often misses task-relevant keyframes, while recent training-free selectors instead pick frames by how well each one matches the question under an image-text alignment (ITA) score. However, we show that ITA signals correspond poorly with the MLLM's true needs: their rankings correlate weakly with downstream accuracy and are even negatively correlated on over 40% of questions, whereas the MLLM's internal yes/no judgment yields a much stronger signal. We present ProbFaS, a training- and label-free probabilistic pipeline that fuses both signals for key frame selection. ProbFaS treats dense ITA scores as cheap, biased measurements and sparse MLLM judgments as accurate, costly ones, unifying them via co-kriging, a multi-fidelity Gaussian process, to calibrate relevance across all frames. A 

---

### [141] … -Mamba: A Bidirectional Spatial-Temporal-Spectral Mamba framework for self-supervised dual-order causal scanning and dual-domain EEG -fMRI brain decoding

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1746809426024444&hl=zh-CN&sa=X&d=3833738544178487124&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv6ffHIz3pAozq1p6zRKRDft&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=9&folt=kw-top
**作者**: R Zhong, H Li, X Yi, Z Liu, H Zhu, Q Zhang - Biomedical Signal Processing and … 等 (7 人)
**匹配关键词**: EEG, Brain Decoding
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> Abstract Functional magnetic resonance imaging (fMRI) and electroencephalogram ( EEG ) offer complementary perspectives that are vital … for robust self-supervised EEG -fMRI brain decoding. First, targeting cross-modal spatial heterogeneity, EEG source

---

### [142] EEG Foundation Models Need Channel Adaptation, but Fixed Channel Mappings Often Suffice

**链接**: https://arxiv.org/abs/2604.23091
**作者**: Kuntal Kokate, Dung Truong, Pierre Guetschel, Bruno Aristimunha, Arnaud Delorme
**来源**: cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [143] Graph Spectral and Topological Characterization of Dataset Shift in Cross-Dataset Motor Imagery EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2306-5354/13/12/1417/pdf&hl=zh-CN&sa=X&d=2730654356290532758&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv4Lz76U3vR9pCj0ypDKdqgX&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=8&folt=kw-top
**作者**: A Olamat, P Ozel, R Almajdoubah, N Kartal - Bioengineering, 2026
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> Background: Cross-dataset motor imagery electroencephalography (MI- EEG ) decoding remains unreliable even when labels, channels, and preprocessing are harmonized. This study characterizes how strongly trial-wise functional connectivity

---

### [144] ADformer: A Multi-Granularity Spatial-Temporal Transformer for EEG-Based Alzheimer Detection

**链接**: https://arxiv.org/abs/2409.00032
**作者**: Yihe Wang, Nadia Mammone, Darina Petrovsky, Alexandros T. Tzallas, Francesco C. Morabito, Xiang Zhang
**来源**: eess.SP cs.CE cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [145] Mind World Models: Joint Learning of Motor EEG Representations and Action-Conditioned World Dynamics

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2611.27029&hl=zh-CN&sa=X&d=16249645911090900485&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv4_ZUb9XoW_v7yU1T0dB8yV&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=7&folt=kw-top
**作者**: W Qiu, Z Huang, T Huang, Y Yan, R Ying - arXiv preprint arXiv:2611.27029, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> learns motor EEG representations from scalable naturalistic EEG and egocentric video without action annotations. MWM treats EEG observed … • We introduce MWM, which learns motor EEG representations from naturalistic EEG – video by predicting

---

### [146] A post-training quantization framework for EEG -based sleep stage classification

**链接**: https://scholar.google.com/scholar_url?url=https://iopscience.iop.org/article/10.1088/1741-2552/aec592/meta&hl=zh-CN&sa=X&d=15900247711166947284&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv7aBFY4QDaAYiDGQmWs6_U6&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=4&folt=kw-top
**作者**: Y Wang, C Li, R Song, Y Wang, F Wan, X Chen - Journal of Neural Engineering 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> 1) We designed a unified quantization interface specifically for the sleep staging domain, supporting various mainstream EEG … that the weights of EEG sleep staging models are sensitive to input changes due to the low signal-to-noise ratio

---

### [147] EEG-World: Context-Conditioned Dynamics of the Watching Brain

**链接**: https://arxiv.org/abs/2611.32825
**作者**: Junxiang Zhang, Jiayu Zuo, Wenhao Ye, Junfeng Xia, Xiang Chen, Mo Wang 等 (7 人)
**来源**: cs.CV q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [148] A Comparative Study of Feature Selection Methods for Depression Level Classification Based on EEG Functional Connectivity

**链接**: https://scholar.google.com/scholar_url?url=https://journal.unm.ac.id/index.php/sainsmat/article/download/13778/9696&hl=zh-CN&sa=X&d=4253029474508528394&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv71_1FuhhNmu_2A0HnObBxk&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=5&folt=kw-top
**作者**: E Agustin, SW Purnami, WR Islamiyah, MM Maramis… - SAINSMAT: Jurnal Ilmiah …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Depression level classification poses a significant challenge due to the limitations of conventional, subjective methods, such as the Beck Depression Inventory. The electroencephalogram ( EEG ) is a technique for recording brain electrical activity

---

### [149] From hemodynamics to function: the role of fNIRS and hybrid EEG -fNIRS systems in next-generation assistive technologies for rehabilitation

**链接**: https://scholar.google.com/scholar_url?url=https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2026.1968129/pdf&hl=zh-CN&sa=X&d=10272659663874156942&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv6Ckjrw-OZsPciOrZF3pc35&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=2&folt=kw-top
**作者**: M Ramadoss, V Sampath - Frontiers in Neuroscience, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> fNIRS systems to address the existing drawbacks by leveraging the temporal resolution of EEG and spatial resolution of fNIRS together … for EMG, EEG , fNIRS and hybrid EEG -fNIRS studies, showing their development from 2001 to 2025. EMG

---

### [150] Wearable in-ear EEG recording system with an IC-embedded sensor-proximal active earpiece for capacitive sensing

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0263224126036225&hl=zh-CN&sa=X&d=14048895708792157555&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv5inJVWJJQtCrCZo3FlSytz&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=6&folt=kw-top
**作者**: M Kim, J Cho, D Seok, Y Bae, G Seong, J Kwon 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In-ear electroencephalography ( EEG ) offers a promising solution for unobtrusive brain … This work presents a self-contained capacitive-sensing in-ear EEG system using a compact, low-… noise (IRN) below 1 μ V rms in the EEG band. The system

---

### [151] HSTTA: Hierarchical Selective Test-Time Adaptation for Label-Free Cross-Subject EEG-to-Image Retrieval

**链接**: https://arxiv.org/abs/2611.34153
**作者**: Hongzhou Chen, Yuhao Wei, Lianghua He, Yihang Liu, Zengqiang Wang
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cross-subject EEG-to-image retrieval suffers from substantial performance degradation on new subjects due to subject shift. Test-time adaptation (TTA) can mitigate this shift by adapting pretrained models with unlabeled target-subject EEG. However, most existing TTA methods struggle to match supervision granularity to each query's prediction confidence, leaving many queries without reliable pseudo-labels. To address this, we propose a novel framework named Hierarchical Selective Test-Time Adaptation (HSTTA). HSTTA builds a hierarchy over gallery image embeddings, uses hierarchical selective prediction to assign each EEG query a supervision granularity matching its current prediction confidence, and constructs adaptation objectives accordingly. We further propose Cross-Session Consistency Calibration (CSCC), an unsupervised method that calibrates the global confidence threshold to target a predefined accuracy level for hierarchical predictions. Moreover, we introduce Reciprocal Hierarch

---

### [152] EEG -Based Assessment of Stress Recovery in Built Environments: A Systematic Review and Meta-Analysis of Neural Mechanisms and Restorative Design …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0272494426003932&hl=zh-CN&sa=X&d=12259620708162589219&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv7zzPA7B7_QJR1Yr-HmKqvZ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=0&folt=kw-top
**作者**: J Li, Y Wang, Q Gao, Q Chen, H Fukuda, W Gao 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study systematically reviews the application of EEG technology in stress recovery research within built environments over the past two decades. By integrating qualitative systematic review with meta-analysis, it examines the effects

---

### [153] Clinical outcomes and EEG monitoring in absence epilepsy trials: A narrative review

**链接**: https://scholar.google.com/scholar_url?url=https://onlinelibrary.wiley.com/doi/pdf/10.1002/epi4.70367&hl=zh-CN&sa=X&d=9438135638362721433&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv4PuBwG7sn4insLt6VZILxL&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=1&folt=kw-top
**作者**: J Sourbron, G Japaridze, A Rotenberg, D Dlugos… - Epilepsia Open, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this study, video- EEG telemetry in an EMU was superior for correlating EEG abnormalities with clinical absence seizures. The majority of studies focus on typical CAE, with limited data on JAE, atypical absence epilepsy or syndromes with slower

---

### [154] Impact of Rest on the Mental Fatigue of Construction Workers Using EEG : A Pilot Study

**链接**: https://scholar.google.com/scholar_url?url=https://ascelibrary.org/doi/abs/10.1061/JCEMD4.COENG-18344&hl=zh-CN&sa=X&d=240476068816541164&ei=Cb0Ha52NBZTGieoPgPG18QI&scisig=AIL1Nv7gVVAsItvS4KNndHTCCCPM&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=3&folt=kw-top
**作者**: M Aghakarimi, H Abbasianjahromi - Journal of Construction Engineering and …, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> used electroencephalography ( EEG ) measurements to conduct their investigation. To address the shortcomings of existing unidimensional measurements, a novel EEG -… This is indicated by a considerable reduction in MFPSI values, as well as other

---

### [155] Decision-Aligned Value Learning for Selective Adoption of EEG Fusion in Human-Robot Collaboration

**链接**: https://arxiv.org/abs/2611.34451
**作者**: Xinjia Yu, Jing Yang, Yang Zhou, Tielin Shi, and Tao Cheng
**来源**: cs.HC cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Electroencephalography (EEG) captures neural activity associated with human perception and decision-making. It provides human-robot collaboration (HRC) systems with measurable evidence for event recognition, situation assessment, and action preparation. External sensing cannot easily provide such evidence. However, the quality and complementarity of this evidence vary across samples, and existing EEG fusion methods do not explicitly determine when EEG improves a prediction. We therefore framed selective EEG use as a sample-wise incremental-value estimation problem and proposed Value Estimation and Constraint-Aware Triage for Adoption (VECTA). VECTA separates the generation of an EEG-informed Fusion prediction from the decision about whether it should replace the existing Base prediction. The framework uses system gain to quantify the loss reduction from Base to Fusion and matching gain to assess whether benefits arise from sample-matched EEG. A signed-value learner estimates system gai

---

### [156] Concept Generalization in Visual Brain Decoding via Encoder-Generated fMRI

**链接**: https://arxiv.org/abs/2611.33870
**作者**: Peter Yongho Kim, Juhyeon Park, Dongsheng Li, Yansen Wang, Dongqi Han, Mingqing Xiao 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Brain Decoding
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual brain decoders are typically trained and evaluated on stimuli drawn from similar semantic distributions, leaving their ability to reconstruct unseen concepts poorly understood. We study this concept generalization problem by withholding semantic concepts from a target subject's training data. We find that three recent fMRI-to-image decoders degrade substantially for the held-out concepts, even when the concept remains available for multi-subject models. In contrast, brain encoders that map a pretrained visual representation directly to voxels are markedly more robust to the same semantic holdout. Motivated by this asymmetry, we use such an encoder to generate synthetic fMRI responses for new images and add the resulting image-fMRI pairs to decoder training. Across three decoders, four subjects, and twelve semantic concepts, synthetic data recovers a substantial fraction of the performance lost on unseen concepts without requiring additional, time-consuming fMRI acquisition. We f

---

### [157] When to Trust a PFN: Detecting Harmful Shift in Tabular Foundation Models

**链接**: https://arxiv.org/abs/2611.34767
**作者**: Viet Nguyen, Herman Bergstr\"om, Stephan Rabanser, Rahul G. Krishnan
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular prior-fitted networks (PFNs) work well across tabular classification problems but can fail silently at deployment when distributions shift. We propose CALD (Calibrated Anchor-Loss Disagreement), a lightweight unsupervised monitor that triggers an alarm to warn when a PFN might fail. By finetuning the decoder to maximize disagreement with the test-set prediction while maintaining accuracy on an ID anchor set, CALD identifies harmful OOD batches through the resulting anchor loss, requiring no labels on test batches. We prove that the post-finetune anchor loss has a strictly lower expectation under sufficiently severe shift than under ID eval, yielding a one-sided test. Across 14 datasets covering tabular and structured distribution shift, on both TabPFN and TabICL, CALD matches or outperforms baselines on harmful shifts and is markedly more resilient to benign-shift false alarms.

---

### [158] geo-eval-harness: An Evaluation Harness for Geospatial Foundation Models

**链接**: https://arxiv.org/abs/2611.33990
**作者**: Nils Lehmann, Caleb Robinson, Isaac Corley, Jennifer Marcus, Inbal Becker-Reshef, Juan M. Lavista Ferres 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation model (GFM) research papers are plagued by inconsistent evaluation settings (e.g., different pre-processing and probes), making it difficult to separate performance from evaluation choices. We propose geo-eval-harness}, an open-source framework for controlled model comparisons. We use this harness to evaluate 100 GFMs and general vision models on 6 classification and 14 segmentation datasets, using multiple probes on frozen or low-rank-adapted encoders. We show that under controlled evaluation, general vision backbones are competitive on RGB classification and high-resolution segmentation, but GFMs shine on multispectral tasks. When we compare any two of the top-ten classification models on a single dataset, their 95% confidence intervals overlap 73% of the time. We show that bigger models are not always better: inference FLOPs correlate weakly with segmentation performance. Moreover, translating inference compute into large-area mapping workloads shows how small 

---

### [159] A gene informed benchmark for BioScoring of pathology foundation models

**链接**: https://arxiv.org/abs/2611.34930
**作者**: Paul Vilars and Vincent Quoc-Huy Trinh and Maria Vakalopoulou and Dimitris Samaras and Stergios Christodoulidis and Mahdi S. Hosseini
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pathology foundation models are usually compared by their performance on downstream tasks such as classification and retrieval. While such benchmarks measure how useful a model is, they provide no insight into the biology it represents. We introduce BioScore, a benchmark that quantifies how well an image encoder captures cell identities, with spatial transcriptomics of the same tissue as the reference. A sparse autoencoder splits the encoder's patch embeddings into sparse features, which we cluster into a fixed number of groups. BioScore then measures, for each of 52 cell identities defined by marker genes, how specifically one group follows the identity's expression over the tissue. Because the autoencoder training is fully unsupervised, a match shows that the model represents the cell identity from the image alone. We score 8 pathology foundation models and 3 natural-image models. Every pathology model scores above every natural-image model (0.299--0.371 \vs 0.214--0.232), and paired

---

### [160] Recurrent In-Context Learning for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.14998
**作者**: Tejas Vaidhya, Gaurav Sahu, Ishita Sanjay Hiremath, Irina Rish
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [161] Text-Conditioned Low-Rank Adaptation of Time-Series Foundation Models for Multimodal Forecasting

**链接**: https://arxiv.org/abs/2611.34206
**作者**: Kunqi Li, Bin Liang, Zhidong Li
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models (TSFMs) provide transferable numerical forecasting priors. However, forecast-relevant information may be conveyed in text without being reflected in the observed series. Many multimodal forecasting methods integrate such context through model inputs or intermediate representations. We investigate a complementary mechanism: text-conditioned parameter adaptation. We propose Context-to-LoRA for Time Series (C2LoRA-TS), which encodes text and generates temporary Low-Rank Adaptation (LoRA) updates for selected weight matrices of a frozen TSFM. Both the numerical backbone and text encoder remain frozen, and the method exactly recovers the frozen TSFM output when context is absent. Evaluated on Time-MMD across nine domains and three TSFM architectures, C2LoRA-TS achieves lower aggregate forecasting error than the frozen-TSFM and Static LoRA baselines for every architecture and seed. Replacing the instance-specific text with a single globally fixed context degrade

---

### [162] Teaching Students to Stand on Their Own: Distilling Vision Foundation Models for Fine-Grained Few-Shot Class-Incremental Learning

**链接**: https://arxiv.org/abs/2611.33749
**作者**: Junsu Kim, Seungryul Baek
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fine-grained few-shot class-incremental learning (FG-FSCIL) aims to incrementally learn visually similar new classes from limited images without catastrophic forgetting. Prior work typically learns strong representations on base classes or leverages vision foundation models (VFMs) directly as backbones or via knowledge distillation. However, VFM backbones incur high computational costs and do not guarantee fine-grained recognition. Although knowledge distillation reduces inference cost, our preliminary experiments reveal that distilled students still lag substantially behind their VFM teachers, particularly on new classes. To address this limitation, we propose STAND, a systematic VFM-to-student distillation design tailored for FG-FSCIL. Specifically, STAND connects the teacher and student by equipping the student with a fixed copy of the teacher's classifier, aligning their outputs via projectors, and feeding both models composite images that combine different training images. On thes

---

### [163] CovNovBench: A Benchmark for Evaluating Time Series Foundation Models under Covariate Novelty

**链接**: https://arxiv.org/abs/2611.33732
**作者**: Wenhao Pan, Ravi Kiran Selvam, Michael W. Mahoney, Mayank Jauhari, Mengfei Cao, Dmitry Efimov 等 (7 人)
**来源**: cs.LG stat.ME
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Covariate-aware time-series foundation models (TSFMs) condition their forecasts on additional input variables, called covariates, that are supplied over the future horizon. This capability makes them appealing for interventional forecasting, in which a target is predicted under a planned action such as a new product pricing policy or a new patient treatment schedule. We refer to covariates that encode such actions as treatment covariates. Current covariate-aware TSFMs, however, are trained on observed patterns, and their behavior is unclear when future treatment covariates fall outside the range seen in the history. Examples include a numerical treatment that leaves its historical range and a categorical treatment that takes a previously unseen policy. We call this practically common setting covariate novelty, and note that it is not systematically represented in existing benchmarks. We introduce an operational definition of covariate novelty and use it to construct CovNovBench, a benc

---

### [164] Conformal Prediction and Conditional Coverage for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2609.34887
**作者**: Sungwoo Park, Sunghee Park, Won Chang
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [165] Tabby: An Open Pretraining Recipe for Time Series Foundation Models

**链接**: https://arxiv.org/abs/2609.13956
**作者**: Shifeng Xie, Bahaeddine Abdessalem, Zehao Xiao, Youssef Attia El Hili, Ambroise Odonnat, Zhiwei Dong 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [166] Scalable Heterogeneous Graph Foundation Models for Data-Driven Optimal Power Flow in Smart Grids

**链接**: https://arxiv.org/abs/2605.23194
**作者**: Massimiliano Lupo Pasini, Yijiang Li, Kibaek Kim, Teja Kuruganti
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [167] Exascale Multi-Task Graph Foundation Models for Imbalanced, Multi-Fidelity Atomistic Data

**链接**: https://arxiv.org/abs/2604.15380
**作者**: Massimiliano Lupo Pasini, Jong Youl Choi, Kshitij Mehta, Richard Messerly, Rylie Weaver, Linda Ungerboeck 等 (10 人)
**来源**: cond-mat.mtrl-sci cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [168] Analemma $\infty$: A Temporal Benchmark for Geospatial Foundation Models

**链接**: https://arxiv.org/abs/2611.34240
**作者**: Alex L\'opez-Cifuentes, Laura Mart\'inez-Ferrer, Juan Ignacio Bravo P\'erez-Villar (Xoople)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Satellite time series capture how land surfaces change over time. Pixel-wise temporal foundation models read a year of satellite observations per pixel, yet public benchmarks lack a temporal axis or subsample it to a few dates. We introduce Analemma, a temporal benchmark of six datasets that carry every 10 and 20 m Sentinel-2 band and a time series spanning a growing season, completed where their releases omit geometry, dates, or cloud masks. One frozen-encoder protocol evaluates all models across label ratios and three seeds, with two baselines without pretraining. The TESSERA model ranks first overall. A from-scratch model on monthly composites outranks every foundation model except OlmoEarth v1.3-Base, suggesting that temporal input explains most of the performance. Three evaluation choices left unstated by the source publications each shift TESSERA v1 by 7.6 to 18.6 mIoU, against top-two gaps of 0.6 to 2.8. Data, harness and leaderboard will be publicly released soon.

---

### [169] Triage Before Fine-Tuning: Feasibility-Gated Selection and Monitored Adaptation of Embodied Foundation Models for a Fixed Physical Platform

**链接**: https://arxiv.org/abs/2611.33772
**作者**: Zilin Huang, Zhengyang Wan, Zihao Sheng, Boyue Wang, Ruolin Yang, Yuhao Luo 等 (7 人)
**来源**: cs.RO cs.AI cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embodied foundation models are increasingly deployed by selection: a practitioner picks a public checkpoint by benchmark rank and fine-tunes it on local data. The platform is fixed before the model is chosen, with little or no local data. We ask what such a checkpoint loses on a fixed platform and which part of the loss local data can buy back. We split the gap by what can repair it. A sensing gap, information the sensors do not capture, cannot be closed with their data; a latency gap, output arriving after the control loop needs it, belongs to the loop, not the weights; only a distribution gap is fine-tuning's to repair. TRIAGE turns this into feasibility-gated selection and monitored adaptation in five stages: gates on the sensor contract and on end-to-end latency that no score can override, probes on ten minutes of local logs, a ranking by target-relevant score among the candidates that pass, and fine-tuning that is monitored and checked in closed loop before release. On driving ben

---

### [170] Out-of-the-Box Tabular Foundation Models for Bayesian Optimization in Materials Discovery

**链接**: https://arxiv.org/abs/2611.12491
**作者**: Klemens Fl\"oge, Simon Bing, Leo Grinsztajn, Eliott Kalfon, Lennart Purucker, Noah Hollmann 等 (7 人)
**来源**: cs.LG stat.ML
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [171] Not Every Input Needs Everything: Unifying Expert Gating, Model Cascades, and Agent Orchestration

**链接**: https://arxiv.org/abs/2611.34112
**作者**: Dat Tat Mai and Hung Tran Quy, Thai Viet Pham, James Jin Kang
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Executing monolithic neural weights, frontier foundation models, or entire multi-agent workflows uniformly on every input incurs substantial computational, latency, and monetary overhead. Conditional computation mitigates this cost by deciding dynamically which internal experts, model endpoints, or specialized agents to invoke per request. Yet token-level gating in sparse neural architectures, query-level model cascades, and task-level multi-agent coordination have largely progressed in disconnected research silos, obscuring recurring system failures and transferable fixes. In this systematic review, we synthesize 2,289 studies published between 2017 and September 2026 (selected from 13,884 unique records) across 20 methodological families under a unified two-step inspect-then-allocate framework. Discrete hard selection accounts for 70%, 83%, and 91% of token-, query-, and task-scale literature respectively, and computational overhead appears as a top operational bottleneck across ever

---

### [172] SEEK: Self-Evolution through Execution Knowledge for Agentic Robot Manipulation

**链接**: https://arxiv.org/abs/2611.33915
**作者**: Zeyang Guan, Qihao Zhao, Rui Gong, Zhang Haitian, Yalun Dai, Yangyu Huang 等 (10 人)
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> General-purpose multimodal foundation models enable robots to adapt during deployment from observations and execution feedback, without task-specific demonstrations or training. However, the robot retains what it learns only in the model's working context. Once the task ends, it loses this execution knowledge, such as how to carry a bowl between two grippers. On the next attempt at the task, the robot may take just as long and repeat the same mistakes. To avoid this repetition, robots must retain execution knowledge across attempts. Yet replaying past actions is insufficient, because their effects depend on the current conditions. Procedures that determine actions from the current scene address this, but when they meet conditions that earlier attempts did not cover, revising them requires the measured effects of earlier actions. We therefore propose SEEK, an agentic framework that retains both, enabling robots to improve across attempts while keeping the underlying model fixed. To adap

---

### [173] FERRETS: A Scalable Symbolic Transform for Time Series Classification

**链接**: https://arxiv.org/abs/2611.33249
**作者**: Antoine Guillaume
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dictionary methods for time series build bags of symbolic words from subsequences, but the accurate ones scale poorly. Against other families of methods, their accuracy no longer pays for their cost. We present FERRETS, a label-free dictionary transform built on WEASEL~2. It keys windows of random length and dilation into exact eight-bit words, adds a level word of each window's mean and spread, and on multivariate data adds cross-channel words. We compare it with leading classifiers, deep networks and foundation models included, on the UCR, Multiverse and MONSTER archives. FERRETS is the fastest of the eleven methods timed on UCR under a ten-thread budget. Of the ten others, only MultiRocket-Hydra is significantly more accurate, taking 24.7 times as long. FERRETS is not significantly different from WEASEL~2, the most accurate earlier dictionary method, which takes 125 times as long, and is significantly ahead of the other dictionary methods. On the Multiverse core, it is not significa

---

### [174] Can Visual World Models See Force?

**链接**: https://arxiv.org/abs/2611.34422
**作者**: Felix Tristram, Benjamin D. Killeen, Nassir Navab
**来源**: cs.CV cs.RO
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> World models and vision-language-action policy models are increasingly proposed as foundations for robot manipulation. They predict how scenes evolve and which actions to take, yet successful manipulation depends not solely on following observable trajectories but also on the hidden variable of interaction force. Neurophysiology has shown that humans possess a visual prior for this hidden variable, motivating us to ask the question: Do the representations of visual foundation models also capture the forces involved in an interaction? We define force awareness as the ability of representations to (1) indicate when contact force is applied, (2) track how it changes during an interaction, and (3) reflect how large it is. We probe frozen image, video, world- and policy model representations with a lightweight readout trained on synchronized video and force measurements from two manipulation datasets. Our experiments show that most models capture when contact occurs but not how much force i

---

### [175] EGSE: Evidence-Grounded Skill Evolution for Medical Reasoning Agents

**链接**: https://arxiv.org/abs/2611.33909
**作者**: Mingyuan Li, Tong Jia, Ziyuan Yang, Wenbo Qi, Haoran Wang, Jie Gui 等 (7 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical reasoning agents combine foundation models with specialized tools to interpret medical images, yet reusing their historical experience remains challenging. A correct final answer can conceal flawed reasoning or tool use, synthesized advice may lack source support, and superficially similar cases may require different diagnostic procedures. In this paper, we propose EGSE, an evidence-grounded skill evolution framework that distills historical dialogues from similar cases into reusable conditional workflows and progressively refines a multi-faceted skill library through supported and validated updates to improve medical agents. EGSE evaluates intermediate reasoning and tool use and contrasts repeated successful and failed rollouts to extract useful practices and evidence-supported avoidance guidance. These experiences are synthesized into workflows with applicability conditions and checks traceable to source dialogues. Library additions and merges require source-grounded review a

---

### [176] Innata-0: A Native Embodied World System with Model-Agent Co-Design

**链接**: https://arxiv.org/abs/2611.30254
**作者**: Innata Team: Yu Bai, Ziyi Bai, Yuxuan Cai, Chenrui He, Wenhao Li, Zhe Lin 等 (10 人)
**来源**: cs.RO cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The physical world is open-ended, dynamic, and partially observable. While foundation models have advanced embodied intelligence, standalone models struggle with long-horizon execution, and simply integrating models with agents may lead to inconsistencies between planning and physical control. To support reliable and adaptive behaviors in the physical world, we introduce Innata-0, a native embodied world system. Innata-0 jointly designs an embodied world-action model and an agent to combine their complementary strengths. The model, Innata-0-WAM, adopts a tri-tower Mixture-of-Transformers architecture that integrates understanding, prediction, and action generation. The agent, Innata-0-Agent, coordinates long-horizon execution through memory, verification, and recovery. A co-design protocol is further proposed to align model training with agent execution and leverage validated experiences to support subsequent adaptation and model improvement. Extensive evaluations demonstrate strong em

---

### [177] DuCo: Exploiting Dual Cross-Layer Consistency for Sparse Geometric Attention

**链接**: https://arxiv.org/abs/2611.34608
**作者**: Liangyu Xiang, Junyu Gao, Xiaofeng Wang, Changsheng Xu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Dense global attention is crucial for capturing cross-view geometry in visual geometry foundation models, yet its quadratic complexity limits efficient inference on long image sequences. Existing sparse attention methods primarily select entries of the global attention matrix based on attention probabilities and construct masks independently across layers, overlooking value redundancy and cross-layer information reuse. By analyzing attention distributions and clustering value representations across layers, we reveal two forms of \emph{cross-layer consistency}, characterized by highly similar attention probability distributions and localized changes in value redundancy structures. Building on these observations, we propose \textbf{DuCo}, a training-free sparse attention framework that exploits historical attention information and value redundancy for efficient geometric inference. Specifically, DuCo leverages historical attention information to estimate current-layer dense attention pro

---

### [178] Can image generation help visual reasoning? An empirical study

**链接**: https://arxiv.org/abs/2611.34935
**作者**: Xueyang Yu, Yifan Jing, Taiming Lu, Linrong Cai, Zhipeng Cai, Yunyang Xiong 等 (8 人)
**来源**: cs.LG cs.CL cs.CV
**匹配关键词**: Unified Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models think in words; then multimodal models might think in images. We test whether a generated helper improves the answer to a visual question. A model describes the helper it needs and then answers using the original and generated images together. Across 13 vision-language model and generator pairs, generation lowers mean accuracy by 3.7 percentage points, with declines on nine of ten tasks. Two unified models, BAGEL and Janus-Pro-7B, each lose accuracy on eight tasks. On VSTAR, adding a generated image to the same planning hint lowers accuracy by 10.47 points. Repeated image edits yield different outcomes across tasks. ChartQAPro and MathVista stay below their no-generation baselines, while ERQA gains three points after ten edits.

---

### [179] Bridging Transferability and Discriminability via Positive-Unlabeled Domain Adaptation for Building Damage Mapping Across Disaster Events

**链接**: https://arxiv.org/abs/2611.33790
**作者**: Qirui Wang, Hengwei Zhao, Xiaoshu Yang, Jingtao Li, Bo Li, Sorin Popescu 等 (7 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Mapping the damage to buildings following natural and human-caused disasters is essential for disaster response and humanitarian assistance. However, differences in hazard types, geographic environments, building characteristics, and imaging conditions cause cross-event distribution shifts that limit the generalization of deep learning models to new disaster events, even for geospatial foundation models (GFMs) pretrained on extensive Earth observation data. Unsupervised domain adaptation (UDA) can mitigate these shifts, but adaptation remains challenging when damage-proportion and damage-appearance shifts coexist and interact. We identify enhancing target-domain discriminability as key to addressing this challenge. To this end, inspired by positive-unlabeled (PU) learning, we introduce positive-unlabeled domain adaptation, a paradigm that incorporates PU weak supervision to enhance target-domain discriminability, requiring only a few labeled damaged buildings in the target domain. Buil

---

### [180] StateWeaver: Multi-Agent Coordination of Story-State Transitions for Long-Horizon Video Generation

**链接**: https://arxiv.org/abs/2611.34290
**作者**: Modi Jin, Xuying Zhang, Yijing Guo, Haoran Li, Yanwen Ma, Jing Wang 等 (9 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern video foundation models generate high-quality short clips, but preserving long-video consistency and correctly depicting event-driven state changes remain challenging. Existing agentic workflows face these challenges because continual planning and repair accumulate context, while reference updates remain limited. We introduce StateWeaver, which combines Active States and Hierarchical Collaboration to connect review-driven visual reference updates with cross-shot state inheritance. Active States translate state discrepancies identified during review into concrete visual asset requirements that guide reference construction, validation, and regeneration, preserving identity and already-correct content while repairing target attributes. Confirmed generation results are linked to the corresponding asset states, story time, and reference versions for verification and reuse by subsequent shots. Hierarchical Collaboration isolates execution contexts by task, clip, and repair round, and 

---

### [181] MoSk: A Unified Motion-Skeleton Foundation Model for Human Motion Understanding and Generation

**链接**: https://arxiv.org/abs/2611.34022
**作者**: Yun Chen, Munchurl Kim, Jeonghyeok Do
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models (FMs) have advanced visual understanding and generation by providing semantically rich representations. However, this role of FMs remains underexplored in human motion. Large motion datasets offer diverse movements at scale, but often lack action labels for systematically evaluating learned representations on understanding tasks. Skeleton datasets enable such evaluation through established recognition protocols, yet are typically smaller and focus on predefined actions captured in controlled environments. To combine these strengths, we present MoSk, to the best of our knowledge, the first Motion-Skeleton foundation model to integrate motion and skeleton datasets. MoSk learns shared representations through self-supervised masked motion modeling. We incorporate joint-name embeddings to provide a common anatomical reference across various skeleton formats. A cross-attention decoder reconstructs masked motion from the encoder's features, with joint-name embeddings specify

---

### [182] Sparse Adaptation for In-Context Learning on Data Streams

**链接**: https://arxiv.org/abs/2611.33325
**作者**: Jo\~ao Neves, Afonso Louren\c{c}o, Lizy K. John, Eric P. Xing, Jo\~ao Gama
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The Internet of Things (IoT) generates massive data streams, making edge computing essential for low-latency applications and 5G networks. Tabular foundation models (TFMs) enable adaptation through in-context examples rather than parameter updates, but evolving streams challenge context relevance and computational efficiency. This work introduces SAIL, a framework for sparse adaptation of TFMs that reuses the model's key--value cache between adaptation events. SAIL reconstructs its support set only when drifts in stream structure indicate potential context inadequacy, while the structural representation itself is updated by changes in predictive performance. SAIL combines prequential error monitoring with online, class-specific micro-clustering to detect changes in cluster mass, class separability, and feature-space coverage. Upon adaptation, a context budget is allocated proportionally to class mass, and the most recently updated micro-clusters provide representative observations for 

---

### [183] Reading, Not Adapting: Unlocking Frozen Visual Knowledge for AI-Generated Image Detection

**链接**: https://arxiv.org/abs/2611.34719
**作者**: Yuncheng Guo, Ying Dong, Xiaodong Gu
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generalization to unseen image generators has driven efforts to adapt pretrained visual representations for detection. Yet recent findings show that vision foundation models already encode transferable detection knowledge, while further adaptation can impair generalization. This motivates a shift from backbone adaptation to knowledge readout. Conventional linear probing offers a direct way to read this knowledge but is limited to final-layer RGB features. Multi-cue detectors broaden the evidence base, but their designs introduce other tradeoffs: adaptation may compromise pretrained transferability, heterogeneous encoders complicate feature integration, and late fusion precludes intermediate cross-view interaction. To overcome these limitations, we propose ReMoT, a Mixture-of-Transformers-inspired framework that reads complementary knowledge from spatially aligned RGB and wavelet views within a fully frozen visual foundation. ReMoT employs staged joint attention to enable controlled loc

---
