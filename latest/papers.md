# 📑 论文索引 - 2026-10-31

共 242 篇论文

---

### [1] MLLM-GS: Multimodal Large Language Model Prior-Guided Fast Novel View Synthesis in Extreme Environments

**链接**: https://arxiv.org/abs/2610.39936
**作者**: Zhiliang Wu, Xinye Zheng, Kun Li, Fei Wang, Hao Guo, Yanyan Wei 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 11.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Novel view synthesis (NVS) in degraded scenes aims to reconstruct 3D scenes from multi-view observations affected by various degradations, and to generate clear and photorealistic images at unseen viewpoints. Despite recent advances, existing methods often rely on degradation-specific models, limiting their generalization across diverse extreme environments. Generative models provide rich visual priors, but their outputs often suffer from pixel misalignment and color deviations, which can propagate into the reconstructed 3D scene and compromise reconstruction quality. Furthermore, the high computational and memory costs of 3D reconstruction hinder the practical application of NVS in extreme environments. To this end, we propose MLLM-GS, a multimodal large language model (MLLM) prior-guided framework for fast NVS in extreme environments. MLLM-GS consists of two branches: MLLM prior-guided view enhancement and fast 3D scene reconstruction. The former leverages the rich visual priors of a

---

### [2] Fu-TCM: a multimodal large language model that learns traditional Chinese medicine diagnostic reasoning

**链接**: https://arxiv.org/abs/2610.38333
**作者**: Jiahang Xie, Tong Jin, Lingfei Wu, Yaping You, Jie Huang, Yuanchang Jin 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model, Multimodal Large Language Model
**相关性评分**: 9.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are advancing in multimodal understanding and reasoning, accelerating medical model development. Traditional Chinese medicine (TCM) uses evidence from the four examinations to determine disease location and nature, differentiate syndromes and guide treatment. This diagnostic process constitutes a complete chain of reasoning. We present Fu-TCM, a multimodal TCM LLM trained on data retained after cleaning and filtering an initial collection of approximately 7.12 million examples derived from classical texts, textbooks, medical images, clinical cases and publicly available datasets. The model was further optimized using Bianzheng-Grounded Policy Optimization (BGPO), which explicitly targets syndrome differentiation through rewards for response format, intermediate TCM reasoning fields and final syndrome predictions. Fu-TCM-27B led all six benchmarks spanning TCM reasoning, text and vision, achieving a macro-average accuracy of 81.01% and surpassing the stronge

---

### [3] Jailbreak Connectivity: Towards Diverse, Transferable, and Universal Multimodal Large Language Model Jailbreak

**链接**: https://arxiv.org/abs/2610.38091
**作者**: Xu Zhang, Ziqing Hu, Shuo Han, Ren Wang
**来源**: cs.LG cs.AI cs.CR
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are vulnerable to visual jailbreak attacks that bypass safety safeguards. Existing methods typically optimize isolated adversarial examples, limiting attack diversity, transferability, and generalization. We propose Jailbreak Connectivity (JC), a framework based on the observation that effective adversarial inputs can be connected through low-loss regions in image space. JC optimizes continuous adversarial paths: path sampling yields diverse jailbreak images, lightweight surrogate classifiers guide cross-model transfer, and a distribution-level objective enables universal attacks across harmful queries. On MM-SafetyBench, JC achieves average attack success rates of 84.01%, 85.77%, and 97.95% on Qwen3-VL-8B-Instruct, InternVL3.5-8B, and Gemma-3-12B-IT, respectively, exceeding the strongest baselines by up to 68.36 percentage points. In black-box evaluations, JC improves attack success rates over FigStep by 24.69 and 27.34 percentage points on GPT

---

### [4] Rocks, Pebbles and Sand: Modality-aware Scheduling for Multimodal Large Language Model Inference

**链接**: https://arxiv.org/abs/2603.26498
**作者**: Konstantinos Papaioannou and Thaleia Dimitra Doudali
**来源**: cs.DC cs.AI
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [5] Complementing Text Based Moderation with Multimodal Grounding: Detecting Fraudulent Inducement Behaviors on Short Video Platforms

**链接**: https://arxiv.org/abs/2610.38185
**作者**: Xiaoyong Yu
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 6.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Short video platforms have become a primary channel for black and gray industry operations in internet finance, where inducements such as prompts to like, follow, join private chat groups, or click external links frequently steer users toward fraud. Because such videos are short, dynamic, and often convey intent through fleeting visual cues rather than stable text, a moderation system must guarantee detection recall and localize the offending segment so reviewers inspect only the relevant clip. Existing OCR+LLM pipelines transcribe on-screen text frame by frame and classify the transcript, but exploit only textual information. Many inducements are conveyed through visual cues OCR cannot observe, and keyframe-based localization cannot recover precise temporal boundaries. We explore OCR+MLLM, which augments the text pipeline with a Multimodal Large Language Model, and compare three routes: OCR+LLM, OCR+MLLM, and a large zero-shot MLLM, along detection, latency, token consumption, and dep

---

### [6] Rank-Aware Differentially Private Release of Listwise Preferences for LLM Alignment

**链接**: https://arxiv.org/abs/2610.37682
**作者**: Junwei Chen, Manjiang Yu, Pengpeng Qiao, Yang Cao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Listwise preference feedback offers richer supervision for large language model (LLMs) alignment than pairwise comparisons, but a full ranking also reveals more sensitive user preferences. Existing privacy-preserving alignment methods focus mainly on pairwise feedback, while listwise alignment under local differential privacy (LDP) remains unexplored. Extending LDP to this listwise domain raises a critical challenge: the high sensitivity of the full ranking space demands excessive noise, neutralizing the benefits of listwise supervision. To address this challenge, we analyze the interaction between supervision granularity and privacy noise in downstream training, and introduce a rank-aware exponential mechanism that privatizes listwise preference data into a low-sensitivity granularity suitable for downstream alignment. The mechanism leverages ranking information to sample a fixed-size binary partition, concentrating the noise near borderline items instead of perturbing all items unifo

---

### [7] Vendster: An Evaluation Arena to Investigate How Forecasting Tool Quality Affects LLM Agent Behaviors in Buyer-Vendor Negotiation

**链接**: https://arxiv.org/abs/2610.38292
**作者**: Charin Polpanumas
**来源**: cs.GT cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series forecasters are ranked almost entirely by accuracy metrics, but a forecast's decision value, its effect on the downstream decision, need not track accuracy and is rarely measured. This problem compounds as large language model (LLM) agents increasingly consume forecasters as tools, mediating them through stochastic, opaque policies. We present Vendster, an evaluation arena measuring how a forecaster's bias and prediction-interval width change the outcome of a buyer--vendor discount negotiation between two LLM agents. In the reference instance Vendster-M5, sampling base demand patterns from the M5 dataset, we evaluate two frontier-closed LLM families (Claude Opus 4.6 and GPT-5.6 Sol) and two open ones (DeepSeek-V3.2 and Qwen3-235B-A22B). Model-generated forecasts raise sales target attainment by up to +17 percentage points (p<0.001), yet standard forecast evaluation metrics such as relWQL and MASE do not predict negotiation outcomes at a statistically significant level. To i

---

### [8] Keepace.ai: A Technical Report on a Large Language Model for Sports and Health

**链接**: https://arxiv.org/abs/2610.38249
**作者**: Keepace.ai Team, Bowen Wu, Heng Wang, Jufeng Mi, Kang Liu, Kun Li 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models hold promise for delivering safe, scientifically grounded, and personalized exercise guidance at scale, yet the sports-and-health domain still lacks curated training corpora and rigorous evaluation benchmarks. Keepace.ai is a domain-specialized LLM built on Qwen3.5-27B through post-training, currently optimized for Chinese-language exercise guidance across three tasks: workout plan generation, sports-and-health knowledge QA, and personal sports data analysis. In internal rubric-based evaluations designed with domain experts, Keepace.ai outperforms its base model and larger general-purpose baselines, with the most pronounced improvements in exercise safety, boundary compliance, structured output completeness, and scientific accuracy. This report summarizes the current design, data pipeline, safety-first evaluation framework, and evaluation results of Keepace.ai.

---

### [9] Agentic LLM reasoning in pediatric diabetes outcome prediction from multimodal medical records

**链接**: https://arxiv.org/abs/2610.40379
**作者**: Daniel Palacios, Guantong Qi, Anna Kadi, Natali Borrego, Sukru Aras, Michael L. Ferm 等 (10 人)
**来源**: q-bio.QM cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents are proposed for clinical prediction but are untested in pediatrics, where cohorts are small and outcomes are uncommon. Using records from 2,489 youth with type 2 diabetes (T2D) and 4,018 with type 1 diabetes (T1D), spanning structured data, note-derived social determinants and, in T1D, continuous glucose monitoring data, we predicted seven T2D outcomes, four also in T1D, at 24 months from 18 months of follow-up. CEDAR (Clinical Evidence-Driven Agent for Risk-prediction), an evidence-citing, self-auditing LLM pipeline, outperformed trained machine learning in both cohorts (pooled area under the receiver operating characteristic curve 0.815 versus 0.656 to 0.700 in T2D and 0.756 versus 0.603 to 0.631 in T1D), most on the sparsely screened outcomes. Only 4 of 70,246 values it cited did not match the chart. Reading only the evidence and reasoning cited by CEDAR, two pediatric endocrinologists reached the same prediction as CEDAR in about nine of ten cases

---

### [10] GAUSS: A Workload-Aware Analytical and Monte-Carlo Simulator for LLM Inference Serving

**链接**: https://arxiv.org/abs/2610.37989
**作者**: Srikant Bharadwaj, Ankur Mallick, Spyridon Mastorakis, Anjaly Parayil, Dhruv Deshmukh, Victor Ruehle
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference has become an operational workload that fleets must provision, monitor, and bill against latency service-level objectives (SLOs). A single throughput number cannot answer the questions operators actually face, because generative serving couples two phases with very different service characteristics, continuous batching reshapes the effective service process, and user-visible tail latency can degrade long before aggregate throughput saturates. We present GAUSS, a workload-aware analytical and Monte-Carlo simulator that predicts the full distributions of time-to-first-token (TTFT) and time-between-tokens (TBT), together with the sustainable request rate, for a given workload, engine, and accelerator. GAUSS pairs calibrated, phase-specific latency surfaces for prefill and decode with a Lindley-recurrence model of queueing under stochastic arrivals and estimates performance by ensemble Monte-Carlo sampling rather than by replaying a single trace. This l

---

### [11] DolphinRouting: Cluster-Level Binary Routing for Disaggregated LLM Inference Serving

**链接**: https://arxiv.org/abs/2610.40292
**作者**: Yishuo Yuan, Shaoyu Yang, Chunrong Fang
**来源**: cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Prefill-decode (PD) disaggregation isolates the two phases of large language model serving, but request-level path selection must account for prefill work, cache reuse, and decode demand. We present DolphinRouting, which learns this choice from end-to-end SLO feedback under a given P/D resource allocation. Requests are clustered by raw prompt length, cache-adjusted input lengths on both worker pools, and output-length information. Offline policy search learns one binary action per cluster. Online feature extraction, cluster assignment, and table lookup select local or remote prefill. We evaluate DolphinRouting on a real PD-disaggregated cluster using three public benchmarks, a mixed workload, and real data. Across the mixed workload and real data, DolphinRouting with $k$-means reduces P90 TTFT by 5.7--7.9\% and P90 TPOT by 2.6--10.1\% relative to Dynamo.

---

### [12] REALM: Identifying Minimal Task Assets for LLM Agents

**链接**: https://arxiv.org/abs/2610.39155
**作者**: Zihou Ren, Byungchul Tak, Long Wang
**来源**: cs.CR cs.AI cs.SY eess.SY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents often receive access to more files, accounts, and services than a task requires. Prompt injection turns this excess access into an opportunity to redirect execution toward unrelated resources. Applying least privilege therefore requires identifying the assets needed by a task, including assets whose identities emerge only during execution. We present REALM (Required Execution Assets Linked to a Mission), an approach to identifying and maintaining a task's required assets and their permitted uses. The approach represents required assets as Dependency Graph nodes, resolves prerequisite relationships, and admits newly discovered assets through source-scoped selection. It separates discovering an asset from authorizing its use, while preserving the agent's freedom to choose its computation. The REALM Builder maintains the selected grants and projects Asset Files; the Partial API Manager exposes resource-bound Partial APIs to the Agent inside a Task Contain

---

### [13] Don't Ask the LLM: Visual Token Pruning with Spectral Structure and Semantic Relevance

**链接**: https://arxiv.org/abs/2610.38303
**作者**: Intaek Shin, Geuntaek Lim, Sungjune Park, Yukyung Choi
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large vision-language models (LVLMs) represent images and videos as long visual-token sequences, substantially increasing inference costs. These costs motivate visual-token pruning, whose effectiveness depends on both what signal is used for selection and when that signal becomes available. Our analysis reveals complementary limitations: visual-side [CLS] attention produces scattered, background-biased selections under aggressive compression, while stronger query-conditioned signals become available after substantial computation within the large language model (LLM). This raises a natural question: can structurally coherent, query-aware token selection be performed before consulting the LLM? We therefore propose ST-Pruner (Spectral-Textual Pruner), a training-free framework for pre-LLM visual-token selection. It combines attention-independent spectral saliency with inverted patch-text similarity through parameter-free multiplicative fusion. Across diverse LVLMs, ST-Pruner retains over 

---

### [14] Guideline-aware corrective OPF in power systems: An LLM -assisted framework with checked interpretation and sensitivity-aware mapping

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S147403462601092X&hl=zh-CN&sa=X&d=75200223547477570&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv5oMi5qM1YrH59LloWvadA7&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=6&folt=kw-top
**作者**: S Mao, M Liu, J Chen, M Jia, J Ma, Y Duan - Advanced Engineering Informatics 等 (7 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> framework that uses a large language model ( LLM ) as a guideline-interpretation layer to convert operating guidelines and alarm metadata into structured priority labels. A checked priority-labeling interface confines the LLM to interpretation and

---

### [15] Integrating Heterogeneous Echocardiography AI Outputs in Language Space: Learnable Late Fusion with a Supervised LLM

**链接**: https://arxiv.org/abs/2610.39464
**作者**: Ryo Takizawa, Tempei Kabayama, Chiemi Yamazaki, Shun Kitamura, Ryo Matsuoka, Yuta Ando 等 (8 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> View- and target-specific echocardiography AI models capture useful but complementary information and may not achieve sufficient predictive performance in isolation. A learned ensemble is a natural way to combine these outputs, but heterogeneous models typically require each output to be converted into a binary decision, probability, confidence score, or fixed-length feature vector. We developed a supervised large language model (LLM)-based late-fusion module that directly aggregates view-specific predicted finding statements and predicted measurements in language space and learns a case-level fusion function. In patient-level three-fold cross-validation of 859 examinations from 646 patients, the proposed method integrated heterogeneous outputs within a single framework, performed comparably to the best-performing reference strategy evaluated, and outperformed a general-purpose LLM without task-specific training. These results suggest that a supervised LLM can combine multiple upstream

---

### [16] Robust LLM-Generated Text Detection through Matched Conditional-Response Probing

**链接**: https://arxiv.org/abs/2610.38312
**作者**: Junfeng Hao, Wenxian Wang, Tao Leng, Xingshu Chen, Hao Ren, Haizhou Wang
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable detection of large language model (LLM)-generated text must remain effective under meaning-preserving text revisions, such as rewriting, polishing, and expansion. In practice, LLM outputs are often rewritten, polished, expanded, translated, or lightly edited before publication, weakening the lexical, syntactic, and local discourse cues used by many existing detectors. We introduce \textbf{M}atched \textbf{C}onditional-\textbf{R}esponse \textbf{P}robing (\textbf{MCRP}), a frozen-LLM probing framework that measures how a candidate text responds when a semantically matched condition is introduced, removed, or replaced. For each candidate, the frozen probe LLM first generates a short semantic condition and then compares token-level losses and prompt--target attention measurements under matched, null, and control conditions. It aggregates bidirectional conditioned alignment, counterfactual sensitivity, and internal attention coupling into a probe representation, on which it trains 

---

### [17] MAServeBench: Benchmarking Multi-Agent LLM Serving Systems with Hierarchical Collaboration Workloads

**链接**: https://arxiv.org/abs/2610.40293
**作者**: Shengxuan Qiu, Haochen Huang, Shuzhang Zhong, Zizhuo Fu, Zebin Yang, Jianming Tong 等 (7 人)
**来源**: cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-based multi-agent systems (MAS) coordinate specialized agents to solve complex tasks, turning each user request into interdependent model and tool operations. Unlike independent requests, these operations become ready at different times and consume evolving context as agents coordinate and exchange results. This creates changing patterns of concurrency, computation, and memory demand that can expose different bottlenecks in LLM serving hardware. Yet benchmarking these effects requires capturing the collaboration rules that generate serving workloads, beyond the requests observed during execution. We present MAServeBench, a benchmark that treats multi-agent collaboration as a configurable dimension of serving workloads for LLM serving and hardware evaluation. Its composable stages capture how agents coordinate and exchange context in documented MAS workflows, enabling native executions to generate different workloads even when task inputs and tools remain unch

---

### [18] Implicit Minor Detection from Multi-Turn Dialogue in High-Risk AI Interactions: A Constrained Self-Evolving LLM Harness

**链接**: https://arxiv.org/abs/2610.38546
**作者**: Xiaohan Zhang, Ying Zhao, Ruilin Guo, Xuanyuan Yu, Kaibo Huang, Yukun Wei 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In high-risk text interactions, a system may need to estimate whether the current speaker is likely to be a minor before applying age-conditioned safeguards. Many text-based dialogue systems lack strong identity signals such as account information, verified identity, facial data, or device data, and must rely on weak cues that emerge across multiple turns. We formulate implicit minor detection under weak identity information as a high-risk user-attribute inference task and propose a constrained framework comprising a large language model, a Harness, and a Maker-Checker protocol. The framework controls when inference is invoked, requires structured dialogue-linked evidence, and subjects validation-selected Harness revisions to version-level review. On a controlled Chinese benchmark comprising 8,328 multi-turn dialogues, our method improves average precision and minor-class F1 by 7.60 and 6.37 percentage points, respectively, over direct inference using the same LLM family.

---

### [19] The Illusion of Power Capping in LLM Decode: A Phase-Aware Energy Characterisation Across Attention Architectures

**链接**: https://arxiv.org/abs/2605.11999
**作者**: Bole Ma and Ayesha Afzal and Jan Eitzinger and Gerhard Wellein
**来源**: cs.DC cs.AI cs.LG cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [20] DeFT-RAG: Incrementally Decomposing Multi-Hop Questions into Self-Contained Sub-Questions with Reusable Answers

**链接**: https://arxiv.org/abs/2610.37826
**作者**: Dingyi Kang, Bingzhe Li
**来源**: cs.CL cs.AI cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-augmented generation (RAG) lets a large language model (LLM) answer questions by retrieving relevant passages from a large corpus. However, RAG struggles with multi-hop questions, which require chaining facts spread across several documents through intermediate entities that the question never mentions. Graph-based RAG methods retrieve once from the entities a question names and so rarely recover the full evidence chain. Iterative RAG methods recover it step by step, but their accuracy is limited by the many tasks they ask the LLM to perform, such as planning the sub-questions, deciding their dependencies, rewriting them as answers arrive, and keeping track of what is known. We propose DeFT-RAG, a RAG framework built on three components. First, DeFT-RAG generates one self-contained sub-question at a time from the original question and the sub-questions answered so far with their answers (QA pairs). Each sub-question names every entity it asks about, which removes the need to 

---

### [21] Beyond Surface Forms: A Comprehensive, Mechanism-Oriented Taxonomy of Indirect Linguistic Encoding for LLM-Based Coded Language Detection

**链接**: https://arxiv.org/abs/2606.27314
**作者**: Hamid Reza Firoozfar, Mohammadsadegh Abolhasani, Reza Mousavi, Paul Jen-Hwa Hu
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [22] Rethinking Bayesian Optimization for Co-Optimizing LLM Training Configurations

**链接**: https://arxiv.org/abs/2602.08351
**作者**: Zhiliang Chen, Alfred Wei Lun Leong, Shao Yong Ong, Apivich Hemachandra, Gregory Kang Ruey Lau, Chuan-Sheng Foo 等 (9 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [23] LLM -Guided Adaptive Cost Calibration in Active Learning for Parkinson's Disease Biosignals

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/1422-0067/27/21/9542/pdf&hl=zh-CN&sa=X&d=7878873732336930261&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv7exjJv2UkFKdCEnrdoVZo_&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=8&folt=kw-top
**作者**: B Gülez, A Güneş, E Kocabıçak - International Journal of Molecular Sciences, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This work provides a cross-domain precedent for using an LLM as a structured calibration component. The LLM in ClinRisk- LLM has a … That policy is stored before evaluation and replayed without further LLM calls. It never labels an

---

### [24] AgentHeal: Evaluating Goal-Preserving Resource Recovery of Web Agents under Access Barriers

**链接**: https://arxiv.org/abs/2610.39234
**作者**: Zhiyi Liu, Haohua Du, Haoqi Sun and Haisheng Tan
**来源**: cs.CR cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents have demonstrated strong capabilities in automating complex information-seeking and transactional tasks across the open web. However, their real-world reliability remains limited by access barriers, such as dead links, authentication walls, rate limits, and anti-scraping defenses. These barriers block the primary execution path, causing agents to abort prematurely, loop indefinitely, or quietly compromise the user's original constraints. Existing evaluations either implicitly assume that target resources are freely accessible or focus on transient perturbations that simple retries can resolve, failing to capture scenarios where agents must actively reroute around impassable bottlenecks. To bridge this gap, this paper introduces AgentHeal, a comprehensive benchmark evaluating goal-preserving resource recovery, defined as the ability of web agents to detect non-transient access barriers, pivot to legitimate alternative sources, and fulfill the user's exa

---

### [25] Large Language Models for Accurate Medical Chart Abstraction: Enabling Scalable and Secure Artificial Intelligence Deployment in Stroke

**链接**: https://arxiv.org/abs/2610.38009
**作者**: Zhusi Zhong, Carl M. Porto, David Hong, Miranda Gonzales, Revyn Kim, Gnaneswari Karayi 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical chart abstraction transforms unstructured clinical narratives into structured variables for research and quality monitoring. We evaluated a prompting-based large language model (LLM) framework for extracting eight clinical variables from 2,416 neurointerventional acute stroke intervention reports across three hospitals. Twenty-two instruction-tuned open-source LLMs were evaluated across architectures, model sizes, and biomedical adaptations using Quick Response and Chain-of-Thought (CoT) prompting. Non-expert staff annotations served as the cross-model reference standard. Evaluation was restricted to report-variable pairs with a valid LLaMA3.3-70B CoT prediction and a corresponding reference label. Performance measures included extraction accuracy, inference latency, and agreement with expert adjudication. Twenty discordant cases per variable underwent review by two senior physicians and four medical students. LLaMA3.3-70B achieved the highest overall accuracy (94.8%). CoT impr

---

### [26] From Leniency to Suspicion: How an Open Post-Training Recipe Changes Whom LLM Fact-Checkers Believe

**链接**: https://arxiv.org/abs/2610.38532
**作者**: Nouar AlDahoul, Yasir Zaki
**来源**: cs.AI cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLMs increasingly fact-check online content with the poster's identity in view. However, it remains unclear which post-training changes how much a model's truth judgement depends on the poster's social class, and how such a change happens inside the model. This paper investigates job-based doubt, i.e., judging a claim false more often when the poster has a lower-status job, using fact-checked claims with randomised poster profiles in base and post-trained checkpoints of six model families. Our results reveal that: 1) post-training creates such doubt only with the open T\"ulu-3 recipe (OLMo-2 32B, T\"ulu-3 70B), not with Meta's, Alibaba's or Mistral's; the effect is under one percentage point but statistically reliable, exceeding training drift and replicating on independent claim sets; 2) in OLMo-2 32B, the model does not start noticing the poster's job more, but starts interpreting it differently: a lower-status job pushes the base model toward "true" and the post-trained model toward

---

### [27] Auditable Belief Updates as a Missing Safety Layer for LLM-Powered Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.38869
**作者**: Zhuoyun Li, Boxuan Wang, Jinwei Hu, Xiaowei Huang, Yi Dong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly being used as cognitive interfaces that shape how users interpret evidence, communicate, and make decisions. As deployed systems become more multimodal, tool-using, and multi-agent, safety failures no longer arise only from isolated harmful outputs, but also from how agents update, store, and propagate epistemic commitments across retrieval, memory, tools, and peer communication. In this paper, we define belief as an engineering abstraction for evidence-based commitments that guide downstream action. Building on this view, we propose the Explicit Belief Multi-Agent System (EB-MAS), which externalizes belief states into a structured substrate, uses belief operators to propose candidate updates, and applies a Cognitive Firewall to bound or reject updates that are weakly evidenced but strongly driven by vulnerability cues. We also discuss the risk of group belief at the group level, including manufactured consensus, collusion, and cascading mi

---

### [28] EpiAgent: Epistemic Self-Play for LLM Agents

**链接**: https://arxiv.org/abs/2610.40227
**作者**: Xuanfa Jin, Xinyu Cui, Zhijian Ma, Xue Yan, Jian Zhao, Haifeng Zhang 等 (7 人)
**来源**: cs.AI cs.CL cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Epistemic game theory explains an agent's strategic behavior via the beliefs it holds about others and how these beliefs are updated as the interactions unfold. Modern LLM-based agents, however, often lack an explicit mechanism for learning and updating such beliefs to guide decisions under incomplete information. To bridge this gap, we propose EpiAgent, a framework that equips LLM-based agents with an explicit, learnable epistemic layer, which maintains beliefs over others' private information and combines these beliefs with the agent's available information into an epistemic state for action selection. Concretely, the agent's policy is decomposed into two coupled stages: Epistemic Update, which updates these beliefs from interaction histories, and Action Planning, which selects actions conditioned on the updated epistemic state. By formulating their dependency as a bi-level optimization problem, we introduce Epistemic Self-Play, an algorithm that alternately optimizes the two stages 

---

### [29] Think Before You Act: Decision Gate for LLM Agents

**链接**: https://arxiv.org/abs/2610.38620
**作者**: Iftach Shoham, Yuval David, Offer Akrabi, Erez Bilgory, Ido Levy, Sami Marreed 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly perform consequential actions through external tools, yet their proposed actions are often executed without independent verification of policy compliance or task completion. We introduce JevAct, a runtime verification framework that intercepts selected agent actions before execution and enables feedback-driven correction. JevAct compiles domain policies into executable state checks and structured questions evaluated by a prefill-only decision model, which produces probability-based judgments without relying on LLM generation. By combining deterministic verification of tool-state facts with probabilistic assessment of conversational context, the framework identifies potentially invalid actions and premature task termination, providing targeted feedback for bounded revision. JevAct operates independently of the underlying agent model and requires no modifications to its parameters or tools. We evaluate JevAct across eleven LLM agents on $\tau^2$-bench Airline and 

---

### [30] Reinforcement learning to improve large language model-based automated code compliance systems

**链接**: https://arxiv.org/abs/2606.22402
**作者**: Jack Wei Lun Shi, Minghao Dang, Wawan Solihin and Justin K.W. Yeoh
**来源**: cs.SE cs.AI cs.CL cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [31] Rimuru: Unified Memory Management for Modern LLM Serving via Elastic Expert Offloading

**链接**: https://arxiv.org/abs/2610.40305
**作者**: Zhiyuan Fang, Dingyang Li, Jianfeng Zhong, Bin Wang, Weixi Zhu, Cunshu Ni 等 (9 人)
**来源**: cs.OS cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern LLMs strain device memory through large model weights and attention states, particularly in resource-constrained scenarios. Existing systems separately provision memory for model weights and attention states, imposing fixed fixed boundaries that cannot adapt to the changing memory demands of workloads. Under heavy workloads, insufficient state capacity limits request concurrency and reduces throughput; under light workloads, idle memory in one region cannot be reallocated to another, wasting device memory. Meanwhile, modern LLM architectures introduce heterogeneous tensors with diverse layouts and lifetimes, further complicating memory management. These problems motivate unified memory management for heterogeneous tensors. However, a shared pool alone does not make memory directly reusable across tensors with different allocation granularities and execution layouts. This paper presents Rimuru, a modern LLM serving system that unifies memory management through elastic expert offl

---

### [32] The Coordination Tax and the Heterogeneity Dividend: Break-Even Conditions for Multi-Agent LLM Pipelines

**链接**: https://arxiv.org/abs/2610.37700
**作者**: Andreas Zettl, Diego Gosmar
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM pipelines built on interoperability protocols such as the Open Floor Protocol (OFP) or A2A are usually justified on capability grounds, with their runtime cost treated as an overhead of unknown size. Comparing such a pipeline with one model call is underspecified, because a pipeline can give each role a different model. We give a closed-form model that sets the coordination tax (decomposition overhead plus per-handoff protocol cost) against the heterogeneity dividend from routing work to a cheaper model, with a break-even threshold and a feasibility bound, $\alpha < 1/r$, and measure every term, with OFP as the protocol under test, on 135 HumanEval and ClassEval tasks in 2430 runs of six architectures with Claude Opus 5.5 and Haiku 5.5. The protocol adds 7.2 ms per handoff, 0.11% of pipeline wall time. Decomposition does not pay on these tasks: a planner-coder-reviewer pipeline costs 3.22x as much as a single strong call, takes 3.24x as long, and solves no more tasks. M

---

### [33] Efficient Evaluation of LLM Performance with Statistical Guarantees

**链接**: https://arxiv.org/abs/2601.20251
**作者**: Skyler Wu, Yash Nair, Emmanuel J. Cand\`es
**来源**: stat.ML cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [34] Comparing Human Role-Players and LLM-Simulated Clients in Online Counselling Training: An Analysis of Counselling Patterns

**链接**: https://arxiv.org/abs/2610.40563
**作者**: Eric Rudolph, Philipp Steigerwald, Jens Albrecht
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study investigates the capabilities of Large Language Models to simulate counselling clients in educational role-plays in comparison to human role-players. Initially, we recorded role-playing sessions, where novice counsellors interacted with human peers acting as clients, followed by role-plays between humans and clients simulated by Mistrals Mixtral 8x7b using 4-bit quantization. These interactions were analysed with a counselling communication pattern system at sentence level. We investigated two key questions: (1) to what extent LLM-generated responses replicate authentic conversational dynamics and (2) whether counsellors' communication behaviour differs when interacting with human versus LLM-simulated clients. The findings highlight both similarities and differences in the application of counselling patterns across scenarios, showing the potential of LLM-based role-playing exercises to enhance counselling competencies and to identify areas for further refinement in virtual c

---

### [35] Few-Shot Fairness: Unveiling LLM's Potential for Fairness-Aware Classification

**链接**: https://arxiv.org/abs/2402.18502
**作者**: Garima Chhikara, Bhaskara Hanuma Vedula, Anurag Sharma, Kripabandhu Ghosh, Ponnurangam Kumaraguru, Abhijnan Chakraborty
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [36] EPSBench: Benchmarking LLM Agents for Earnings Forecasting

**链接**: https://arxiv.org/abs/2610.38293
**作者**: Yanbin Yin, Chuyu Xu, Liqin Ye, Jing Peng, Chao Zhang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quarterly earnings forecasting requires an agent to connect financial evidence to the income-statement line items that produce a company's reported earnings. We introduce EPSBench, a benchmark for studying this ability across 149 firm-quarters from 86 US companies. Agents read a fixed collection of filings, earnings-call transcripts, and news, then estimate company-specific income-statement drivers with cited evidence. A shared accounting calculator converts these estimates into GAAP diluted earnings per share (EPS), providing a common basis for comparing forecast assumptions. We evaluate six models under a common harness, assessing point forecast error relative to date-matched analyst consensus and checking whether their prediction intervals achieve the stated coverage. Three models show no detectable paired difference in point forecast error from consensus, and three have higher error. Across all six models, nominal 80% intervals contain reported EPS in only 37--70% of runs that retu

---

### [37] Answer-Only Disclosure: Private-Context LLM Assistance over Web APIs with a Leakage Ledger

**链接**: https://arxiv.org/abs/2610.38126
**作者**: Liang Yuan, Xiaohu Du, Ruikun Luo, Jinze Wang, Mashud Rana, Kaibin Wang 等 (8 人)
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Web assistants increasingly answer questions about a user's private documents by pairing a small on-device model with a cloud LLM behind a Web API. In collaborative decoding, the document stays on the client, and the cloud receives only a public view that the user approves, such as the question alone, but the two models exchange messages while the answer is generated. We show that the message transcript can disclose private content that neither the public view nor the answer contains. In a planted-secret audit, speculative decoding with private drafts did not include the secret code in its answers, yet sent the code to the cloud in rejected drafts. We present ADLER, a decoding protocol for streaming LLM APIs in which every message to the cloud depends only on the public view and the answer the user sees, regardless of how the client combines the two models or how the cloud behaves. A client-side leakage ledger then bounds how much the answer itself reveals relative to a public referenc

---

### [38] JevRec: Linguistic Encoding with Jev-like Decision Modeling for LLM-based Generative Recommendation

**链接**: https://arxiv.org/abs/2610.36937
**作者**: Qiyong Zhong, Jiajie Su, Ming Yang, Li Zhang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [39] Rethinking LLM Jailbreak Evaluation: Continuous Risk Landscapes Beyond Binary Outcomes

**链接**: https://arxiv.org/abs/2610.38595
**作者**: Yukai Zhou, Wenjie Wang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> A binary success indicator is a natural representation for discriminative tasks such as image classification under adversarial perturbations, where each input is mapped to a single prediction. However, generative tasks are fundamentally different: an LLM jailbreak prompt induces a distribution over open-ended trajectories, while a sampled response reveals only one path. Yet LLM jailbreak evaluation typically retains the binary response indicator underlying attack success rate, obscuring the surrounding structure of possible generations. We introduce a continuous, context-conditioned risk landscape over first-token branches, estimated by fixing candidate openings and repeatedly sampling their continuations. This continuous risk-landscape perspective reveals two complementary properties: current decoder exposure and safe rerouting capacity, which have been obscured by binary-indicator-based ASR. The resulting representation also provides a common basis for comparing clean prompts, attack

---

### [40] Beyond LLM Wrappers: Context Engineering and the Three-Engine Architecture for Reliable Financial AI

**链接**: https://arxiv.org/abs/2610.39230
**作者**: Pradeep Kumar GS and Ravi Tanniru
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Financial AI systems must support decision-bearing questions involving payments, collections, cash flow, and compliance while ensuring numerical accuracy, traceability, and auditability. Large language models (LLMs) enable natural language interaction but cannot independently guarantee reproducible calculations or evidence-grounded recommendations. We present a production-grounded architecture integrating three components: a financial knowledge graph for enterprise relationships, temporal context, and provenance; a deterministic optimization engine for financial calculations and decisions; and a multi-agent LLM layer for intent interpretation, task orchestration, explanation, and claim validation. A coordination layer, termed context engineering, selects, ranks, composes, and validates query-specific context across ERP systems, tools, and tenants. Based on observations from 15 deployments over approximately 11 months, single-agent pipelines exhibited hallucination rates of about 7-9% (

---

### [41] Reason or Recite: Complementary Specialists with an LLM Judge for Traffic Anomaly Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2610.34993&hl=zh-CN&sa=X&d=10524825740933523014&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv66HfSwDQvP0Us3Umq02k1a&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=0&folt=kw-top
**作者**: M Kulkarni - arXiv preprint arXiv:2610.34993, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Road anomalies such as collisions, violations, and sudden hazards demand more from video understanding than detection: a practical system must verify what happened, describe the scene, and explain the cause. We find these competences

---

### [42] LLM-Driven, Datasheet-Aware Automated Hardware Compatibility Verification for Early-Stage, Pre-Schematic Embedded System Design

**链接**: https://arxiv.org/abs/2608.25217
**作者**: Haotian Qiao, Robert P. Dick
**来源**: cs.AI cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [43] Turing LLM Post-Training: Calibrated Distillation and Efficient Dynamic-MoE Execution

**链接**: https://arxiv.org/abs/2610.39876
**作者**: Yue He, Jiahui Hu, Shaman Tang, Hua Zhou, Qiman Wu, Menglin Li 等 (10 人)
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We study post-training for dynamically routed mixture-of-experts (MoE) models, focusing on integrating independently optimized specialists while keeping consolidation efficient. Our approach combines calibrated multi-teacher on-policy distillation (C-MOPD), which matches each selected teacher on a local Top-$K$ support with teacher-wise loss normalization and clipping, with an execution path that uses post-capacity bounded-width dispatch, final-route replay, and asynchronous rollout--training overlap. On Turing-20B-A2B, the selected model achieves a four-domain normalized integration score of 0.9988 and retains at least 90.16\% of the measured specialist gain in every domain. At matched $K=32$, the full calibration objective scores 0.9962, compared with 0.9724 without calibration and 0.9834 without clipping. At a matched 8K response cap, the model exceeds both shared SFT and Qwen3-8B on all four reasoning-enabled mathematics and code benchmarks (unweighted mean: 85.92, versus 80.33 for

---

### [44] Joint Detection of Fraud and Concept Drift inOnline Conversations with LLM-Assisted Judgment

**链接**: https://arxiv.org/abs/2505.07852
**作者**: Ali \c{S}enol, Garima Agrawal and Huan Liu
**来源**: cs.CL cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] JANUS: Evaluating Goal-Conditioned Distortion in Factually Grounded LLM Communication

**链接**: https://arxiv.org/abs/2606.10852
**作者**: Polydoros Giannouris, Mohsinul Kabir, Sophia Ananiadou
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [46] Industrialized Deception: The Collateral Effects of LLM-Generated Misinformation on Digital Ecosystems

**链接**: https://arxiv.org/abs/2601.21963
**作者**: Alexander Loth, Martin Kappes, Marc-Oliver Pahl
**来源**: cs.CY cs.AI cs.CL cs.SI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [47] Holistic Diversity Management in LLM-Guided Evolutionary Search

**链接**: https://arxiv.org/abs/2610.38407
**作者**: Seockbean Song, Youngsik Yoon, Sungjae Lee, Siwei Wang, Wei Chen, Jungseul Ok
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-guided evolutionary search iteratively selects existing programs, uses LLMs as mutation operators to generate a new program, and evaluates it to guide subsequent search. To preserve diversity and reduce the risk of premature convergence, it often adopts the island model, in which groups of programs, called islands, evolve separately. However, this structure alone does not guarantee distinct search directions, as islands may start from similar programs or converge toward similar solutions during evolution. This suggests that diversity must be considered throughout the search process, from initializing islands with distinct programs to developing island trajectories and sharing discoveries across islands. To this end, we propose HoliDivEvolve , a holistic approach to establishing and effectively utilizing island diversity throughout evolutionary search. Specifically, we introduce diverse initialization to establish different initial programs, trajectory adaptive island selection to a

---

### [48] DecompGym: Benchmarking LLM Agents on Designing Decomposition Algorithms

**链接**: https://arxiv.org/abs/2610.38175
**作者**: Sikai Cheng, Tinghan Ye, Arnaud Deza, Xiaonan Qi, Miao Li, Litong Liu 等 (7 人)
**来源**: cs.AI math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Benders decomposition and column generation solve large optimization problems by passing cuts, columns, and dual values between a master problem and subproblems, and are hard to implement correctly. Large language models now automate parts of algorithm design, which points toward agents that build decomposition solvers for new problems. As a first step toward such agents, we study how well current coding agents design and implement these two algorithms, and how they fail. We introduce DecompGym, 81 instances from nine problem families (five Benders, four column generation), in which an agent writes a solver for a prescribed method. Each solver must meet three criteria: execution within a 60-second time limit; numerical feasibility together with a method audit, in which an LLM judge reads the solver's code; and an objective within 1% of the stored optimal objective. We evaluate 12 GPT, Claude, and Gemini models running in coding-agent tools. Over up to ten attempts, we compare independe

---

### [49] CacheSolidarity: Preventing Prefix Caching Side Channels in Multi-Tenant LLM Serving Systems

**链接**: https://arxiv.org/abs/2603.10726
**作者**: Panagiotis Georgios Pennas, Konstantinos Papaioannou, Marco Guarnieri, Thaleia Dimitra Doudali
**来源**: cs.CR cs.DC cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [50] Can LLMs Faithfully Solve Ontology Engineering Tasks? A Mechanistic Interpretability Study

**链接**: https://arxiv.org/abs/2610.38326
**作者**: Bohui Zhang, Albert Mero\~no-Pe\~nuela, Elena Simperl
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ontological knowledge underpins large language model (LLM) performance on knowledge-intensive tasks. However, existing evaluations of LLMs' ontological understanding largely rely on behavioral correctness, leaving the underlying mechanisms unexplained. Existing mechanistic interpretability work has largely focused on instance-level factual knowledge, leaving ontological knowledge under-explored. To bridge this gap, we introduce MIOE, a causal-abstraction benchmark that evaluates interchange interventions for two ontology engineering tasks: entity typing and subsumption prediction. MIOE tests whether learned internal intervention targets can change an ontology-level target answer while preserving class-specific auxiliary information. Across Qwen3-8B and Qwen3-4B, we evaluate SAE-, DBM-, and DAS-based methods, including multi-task and multi-layer variants. Distributed subspace methods give the strongest results and generalize across prompt settings, but the induced changes remain only pa

---

### [51] When Should I Trust This? Designing and Evaluating Factuality Indicators for LLM-based Chatbots

**链接**: https://arxiv.org/abs/2610.32883
**作者**: Greta Warren and Christine M. Lehane and Jessica Heal and Sila Eser and Denise M. Leto and Isabelle Augenstein
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [52] S3AC: Stabilized, Selective, and Scalable Actor-Critic for LLM Reasoning

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.35518&hl=zh-CN&sa=X&d=10761093877278851096&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv7TZ8MvDjf-8sM7LnEyIk6Z&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=5&folt=kw-top
**作者**: S Shen, G Cheng, C Lyu, X Wang, Y Sun, W Zhang - arXiv preprint arXiv:2610.35518 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Critic-free methods are widely used in reinforcement learning with verifiable rewards (RLVR) for long chain-of-thought (CoT) reasoning, avoiding difficult and costly critic training. Common alternatives lack token-level credit assignment and typically rely

---

### [53] Semantic-collaborative alignment with LLM -driven explainable profiling for enhanced recommendation

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426037711&hl=zh-CN&sa=X&d=1209030827105022475&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv4SbSwAFyxeOr2OOv1idnNw&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=9&folt=kw-top
**作者**: X Wang, Q Tan - Expert Systems with Applications, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> LLM -enhanced semantic–collaborative alignment framework. The framework employs a dual-view alignment mechanism to jointly align the deep semantic information and implicit collaborative signals of users and items. It also incorporates

---

### [54] Jacobian Scopes: A Unified Geometric Framework for Token-Level LLM Attribution

**链接**: https://arxiv.org/abs/2601.16407
**作者**: Toni J.B. Liu, Baran Zadeo\u{g}lu, Gurbir Arora, Rapha\"el Sarfati, Nicolas Boull\'e, Christopher J. Earls
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [55] BiShield-TEE: On the (In-)Security of Unilateral Weight Obfuscation in On-Device TEE-Shielded LLM Partition

**链接**: https://arxiv.org/abs/2610.21565
**作者**: Zhiyuan Wang, Yuezhi Zhou, Ziqi Zhang, Zhu Zhang, Zhixing Tan, Yongheng Deng
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] AgentDecept: Benchmarking Deceptive Behavior in Tool-Using LLM Agents under Pressure

**链接**: https://arxiv.org/abs/2610.39377
**作者**: Yehan Zhang, Qianqi Yan, Hang Yin, Ching-Chen Kuo, Shan Jiang, Ming Ouyang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents increasingly carry out multi-turn tasks across everyday applications, yet users often see only the agent's report rather than the observations, API calls, and state changes behind it. Existing deception benchmarks have studied long-horizon interactions and tool-use settings, but whether agents faithfully report their actions across realistic, stateful application workflows remains underexplored. To address this gap, we introduce AgentDecept, an executable benchmark for evaluating behavioral deception under pressure. AgentDecept contains 477 pressure variants derived from 257 source tasks across six pressure sources, each paired with a pressure-free counterpart. Interventions enter through event messages, task context, application state, tool responses, and service quotas, spanning explicit events and implicit task or environment changes. Our evidence-grounded protocol evaluates full trajectories by relating user-facing claims to time-ordered observations and executed outcome

---

### [57] Echoes as Anchors: Probabilistic Costs and Attention Refocusing in LLM Reasoning

**链接**: https://arxiv.org/abs/2602.06600
**作者**: Zhuoyuan Hao, Zhuo Li, Wu Li, Fangming Liu, Min Zhang, Jing Li
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] Which Model for Which Role? Cost-Efficient Pareto Recommendation for LLM Agentic Workflows

**链接**: https://arxiv.org/abs/2610.26676
**作者**: Qian Xie, Wenyue Hua, Yueli He, Sripad Karne, Armaan Agrawal, Nikos Pagonas 等 (10 人)
**来源**: cs.LG cs.CL stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [59] Network Topology Does Not Matter: The Breakdown of Classical Consensus in LLM Populations

**链接**: https://arxiv.org/abs/2610.37699
**作者**: Sahil Rajesh Dhayalkar
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As multi-agent language model networks become widely deployed, predicting their collective behavior is a critical challenge. Classical distributed consensus theory relies on network topology to predict convergence, structurally assuming that agent updates are convex combinations, population means are conserved, and weights are content-independent. In this work, we demonstrate that these foundational assumptions fail for large language models (LLMs). By deterministically extracting continuous credence from token-level probabilities across eight instruction-tuned models and 73,080 controlled exchanges, we directly measure the empirical LLM update operator. We find that LLMs systematically violate convexity by updating outside the hull of observed opinions, exhibiting active repulsion (negative weights) that fundamentally breaks row-stochastic modeling and standard bounded-confidence repairs. Scaling these empirically fitted operators to simulations of 10,000 agents reveals that algebraic

---

### [60] Temporal Evidence-Parameter Co-Alignment for LLM Reasoning over Temporal Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.28176
**作者**: Jiapu Wang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] Can I Take Another Dose? DoseBench: Evaluating LLM Decision-Making in OTC Dosing QA

**链接**: https://arxiv.org/abs/2606.04262
**作者**: Maroof Kousar, Jinsung Han, Mohit Chandra, Munmun De Choudhury and Yibo Hu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [62] Beyond Passing Tests: A Systematic Review and Controlled Re-evaluation of Techniques for Improving the Quality of LLM-Generated Code

**链接**: https://arxiv.org/abs/2610.38977
**作者**: Prashank Kadam
**来源**: cs.SE cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models pass most functional-correctness benchmarks, but passing tests says little about whether their code is readable, efficient or secure. Many techniques claim to improve these qualities, yet their evidence is scattered, usually covers one quality dimension and is rarely compared at an equal compute budget. We contribute a systematic review and a controlled re-evaluation. A systematic literature review of 628 primary studies (July 2021 to October 2026), with disclosed, author-reviewed LLM assistance, organizes the techniques by stage, signal source and quality target. Most studies measure only the dimension they target, gains often come with unchanged or unreported correctness, single automated quality signals are gamed, and compute, variance and contamination are rarely reported. A controlled re-evaluation runs ten techniques on four models at matched budgets on correctness, maintainability, efficiency and security benchmarks, extends it to thirteen current models an

---

### [63] InterA11y: Interactive Web Accessibility Error Detection with LLM Agents

**链接**: https://arxiv.org/abs/2610.39488
**作者**: Mingyuan Zhong, Mengqi Shi, Davin Win Kyi, Ajit Mallavarapu, Xia Chen, James Fogarty 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown potential to expand the coverage of web accessibility evaluation. However, current LLM-based checkers neglect much of the interactive and dynamic web contexts, resulting in limited coverage, high false discovery rates, and inconsistent performance across models. We present InterA11y, an agentic accessibility evaluation system that combines rubrics and interactive tools to support LLM agents in evaluating accessibility effectively. The rubrics decompose WCAG success criteria (SC) into testable aspects and guide agents in collecting and interpreting evidence. The interactive tools inspect or operate a webpage deterministically to collect evidence, such as focus appearances and error messages. We developed these rubrics and tools on 682 curated test cases grounded in established accessibility guidelines that target 10 commonly violated SC. We evaluated InterA11y on 197 expert-annotated cases sampled from 54 real webpages. Results show InterA11y achi

---

### [64] OTM-Pop: a hybrid NER- LLM pipeline with multi-signal scoring and HITL validation for ontology population in the Moroccan tourism domain

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/6287639/6514899/11753553.pdf&hl=zh-CN&sa=X&d=2046873814788940451&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv5gnIywnkdItJlFRra2i2eo&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=2&folt=kw-top
**作者**: A Amalki, K Tatane, L Dahr - IEEE Access, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Automatic ontology population from domain-specific text remains challenging when the target ontology is taxonomically deep, the source language is low-resource, and input texts are noisy. Focusing on Moroccan tourism, we propose OTM-Pop, a

---

### [65] SAFE: An LLM-as-Verifier Framework for Evidence-Grounded Multi-Hop Reasoning

**链接**: https://arxiv.org/abs/2604.01993
**作者**: Daeyong Kwon, Soyoung Yoon, Seung-won Hwang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Epistemic Warrant for LLM Recommendations: Characterizing the Basis for Reliance When Ground Truth Is Unavailable

**链接**: https://arxiv.org/abs/2609.04127
**作者**: Shai Vardi, Jo\~ao Sedoc
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [67] Repairs for Whom? Evaluator-Executor Mismatch in Selecting Repairs for Failed LLM Agents

**链接**: https://arxiv.org/abs/2610.38610
**作者**: Yijun Liao, Fanwei Liang
**来源**: cs.SE cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When an LLM agent fails, repair methods choose which action to replace and what to put in its place. They often score candidate repairs with greedy replay, a stronger model, an environment oracle, or a judge that reads the failed log. We ask whether these evaluators pick repairs that help the agent that will actually execute them. Holding failed trajectories and candidate single-step repairs fixed, we label every candidate with independent rollouts of the deployed policy and measure how much deployment value each evaluator's choice loses. On failures not screened for repair value, pre-specified tests show that greedy replay loses 0.08-0.13 in expected net success gain in ALFWorld and 0.06-0.13 in net reward in WebShop, relative to selection with the deployed agent's own rollouts. At an equal rollout budget, selecting repairs for Qwen2.5-7B with Qwen2.5-14B rollouts loses 0.25 in ALFWorld and 0.07 in WebShop, twenty 14B rollouts per candidate are worth no more than two of the 7B agent's

---

### [68] A Low-Rank Space Captures Linear Alignment Between LLM and Human Neural Activity During Naturalistic Language Listening

**链接**: https://arxiv.org/abs/2610.40511
**作者**: Zach Paris and Emily Finn
**来源**: cs.CL q-bio.NC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly used as computational models of human language processing, yet it remains unclear which components of their representations drive alignment with neural activity. Here, we use ridge reduced-rank regression to identify the brain-predictive subspace of LLM representations: the representational directions that support linear prediction of neural responses. Across three naturalistic language-listening datasets spanning intracranial electrophysiology and fMRI, and six model conditions spanning autoregressive, bidirectional masked, and randomly initialized language models, we find that full linear encoding performance can be recovered using only 1-3% of the original embedding dimensionality. These low-dimensional subspaces generalize across held-out participants and, to a lesser extent, across datasets, suggesting that neural predictivity is concentrated in a compact and partially shared representational space. We next compare these brain-predicti

---

### [69] Observational Equivalence of LLM and Human Annotation

**链接**: https://arxiv.org/abs/2609.22133
**作者**: Kentaro Nakamura, Jing Ling Tan, and George Yean
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [70] A Negotiation-Aware Hybrid LLM Framework for Intent Interpretation and Service Discovery

**链接**: https://arxiv.org/abs/2610.40161
**作者**: Wided Meflah, Hayet Brabra, Walid Gaaloul
**来源**: cs.AI cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Increasingly, users express their needs as natural-language intents rather than structured requests. These intents may be incomplete, high-level, or internally conflicting. A conflicting intent either violates fundamental properties of the cloud paradigm or states mutually inconsistent requirements. Classical composition approaches are designed for structured, low-level, and complete requests. They cannot interpret such intents, discover suitable services from provider catalogs, or negotiate conflicting requirements with users. To address this gap, we propose a negotiation-aware framework for intent interpretation and service discovery. The framework first refines the natural-language intent and dynamically detects conflicts. It then structures the intent into a provider-independent TOSCA template. For each specification, it retrieves candidate service offers through deterministic matching grounded in cloud provider offerings. Some conflicts arise during interpretation. Other requireme

---

### [71] FermiGrad-SVD: An LLM Compression Pipeline with Global Rank Selection and Gauge Fixing

**链接**: https://arxiv.org/abs/2512.03062
**作者**: Roman Rausch, David Jansen, Sukhbinder Singh, Rom\'an Or\'us
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [72] Statistical Detection of Positional Bias in LLM-Based Recommender Systems: Methodologies and Empirical Evidence

**链接**: https://arxiv.org/abs/2610.37962
**作者**: Carlos Pel\'aez-Gonz\'alez, Francisco Herrera, Andr\'es Herrera-Poyatos
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) are increasingly used as recommendation generators in conversational recommender systems (RS) via retrieval-augmented generation (RAG). This flexible design introduces new sources of structural bias. This paper studies positional bias in top-1 and single-turn LLM-based RS: systematic dependence of the recommended item on the order in which candidates are presented in the prompt. We propose two complementary detection methodologies: (i) POB-ICM, based on contingency matrix analysis and Chi-square independence testing, and (ii) POB-UNBP, a sample-efficient approach derived from a uniformity null model under permutation-based evaluation, enabling stochastic decoding with formal statistical guarantees. Using a controlled RAG testbed for product recommendation, built on a real product catalog, a fixed prompt template and 2000 template-generated user queries with 20 permutations each (40,000 instances), both methodologies reject the null hypothesis of positional 

---

### [73] Human-Residual Steering: Aligning Frozen LLM Judges with Human Judgment Distributions

**链接**: https://arxiv.org/abs/2610.37868
**作者**: Chen Lyu, Phong Do, Gabriele Pergola
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are widely used as automated judges, yet most alignment methods target aggregated human judgments and overlook variation among individual annotators. Existing approaches to matching the full distribution of human ratings mainly rely on output-level calibration or parameter fine-tuning. We propose Human-Residual Steering (HRS), to our knowledge the first method to align frozen LLM judges with human judgment distributions through learned hidden-state interventions. An oracle analysis shows that low-rank corrections at a single layer remove most of the discrepancy between judge and human distributions. HRS learns to predict such corrections from the judge's hidden representation and rating logits, training on individual annotations with proper scoring rules for ordinal and nominal judgments and optimising through the frozen downstream layers. Across 14 benchmarks and four judges from three model families, HRS outperforms all evaluated frozen-weight baselines. 

---

### [74] Quantum-Inspired Pairwise Ranking Aggregation via Active LLM Feedback

**链接**: https://arxiv.org/abs/2610.38683
**作者**: Quan Mai and Susan Gauch and Gibson Nkhata
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ranking aggregation from multiple retrievers is a powerful yet under-explored technique in modern retrieval and RAG systems. We introduce LLM-IRA, the first extension of the quantum-inspired interactive ranking aggregation framework to document reranking. By leveraging large language models (LLMs) solely for pairwise judgments on high-disagreement document pairs, our method learns fusion weights in a principled, interactive way. The final ranking is a simple, ultra-fast pointwise linear fusion of scores, no full pairwise matrix or expensive listwise prompting is required. Experiments on the BEIR benchmark and TREC Deep Learning tracks with an open-weight instruction-tuned judge (Llama-3.1-8B-Instruct) show that LLM-IRA matches or numerically exceeds strong static fusion baselines on 5 of 6 evaluated benchmarks. We report two weight-update variants: momentum blending and a full accumulated-history refit, which together reach statistical significance (Wilcoxon signed-rank, p<0.05) over t

---

### [75] Prompt Lottery in LLM-as-a-Judge: Measuring and Mitigating Sensitivity to Syntactic Rephrasing

**链接**: https://arxiv.org/abs/2610.38076
**作者**: Ilija Subasic, Brett Levert, Andrew Rabinovich, Sajjad Pakdamansavoji, Zhao Chen
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-as-a-Judge has become a standard for evaluating large language models, yet most approaches implicitly assume that a single judge prompt functions as a stable evaluation instrument. Prior work has primarily explored deliberate prompt modifications such as scoring rubrics, role descriptions, or chain-of-thought reasoning in order to optimize accuracy. In contrast, we investigate whether validated prompt variants intended to preserve evaluation semantics while differing in surface realization (\textit{paraphrastic rephrasings}) yield consistent judgments under a fixed evaluation task. We introduce \textit{Prompt Lottery}, a phenomenon in which paraphrastic rephrasings produce different LLMaJ judgments. Across a large-scale study spanning diverse evaluation tasks, judge families, and model backbones, we find that these variations can alter evaluation outcomes and, in some settings, reverse relative model rankings. A user study with 10 human annotators shows that LLMaJ judges exhibit 6-

---

### [76] BRIDGE: Learning Brain-Gut Metabolic Evidence for Alzheimer's Disease Diagnosis

**链接**: https://arxiv.org/abs/2610.39520
**作者**: Pengli Zhu, Ruxi Chang, Tianliang Yao, Yu Jiang, Shengyuan Liu, Yiyang Lin 等 (10 人)
**来源**: cs.CV
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Alzheimer's disease (AD) diagnosis may benefit from gut metabolic information associated with brain-gut interactions, yet existing models largely analyze cerebral glucose metabolism alone. Although whole-body fluorodeoxyglucose positron emission tomography (FDG-PET) can provide paired brain-gut observations, routine brain examinations rarely include gut imaging, limiting direct use of this information for diagnosis. In this paper, we present BRIDGE (Brain and Gut Representation Integration via Distribution-Guided Enhancement), a two-stage framework for transferring brain-gut metabolic knowledge to brain-only diagnosis. Specifically, BRIDGE integrates a conditional brain-to-gut latent transport module and a disease-evidence-guided cerebral pathway to capture subject-specific cross-organ correspondence and disease-relevant cerebral representations. For the cerebral pathway, a large language model (LLM) helps organize literature-derived descriptors into human-approved semantic anchors tha

---

### [77] Prompt-to-API-Call injection: Systematic attack generation and semantic defense in LLM agents

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0164121226003973&hl=zh-CN&sa=X&d=9086465760595227513&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv5Od-owYdkIJn5WTCW44zPL&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=4&folt=kw-top
**作者**: Q Li, H Zhang, Y Qu, J Wu - Journal of Systems and Software, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Abstract As large language models (LLMs) increasingly power REST APIs, LLM agents face … Grounded in the “confused deputy” risk of agentic LLM architectures, we propose a … rule-based pre-screening with guard- LLM semantic matching

---

### [78] Incorporating Machine-Others: An Enactive Exploration of Human-LLM Interactions

**链接**: https://arxiv.org/abs/2610.39869
**作者**: Elena C. Cuffari, Marta P\'erez-Verdugo, Xabier E. Barandiaran
**来源**: cs.HC cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> New concepts based in interactional thinking are required to understand how humans are changed by relating to LLMs. Standard theories of technological impact upon users' autonomy are inadequate here, because this technology is capable of inducing linguistic interactions with humans in an unprecedented manner. Traditional theories of social cognition also fall short, because LLMs have neither autonomy nor minds nor sociality as such. And yet, humans interact, talk, and create with them. We base ourselves on enactive theory, particularly on the theory of Linguistic Bodies and recent developments of enactive accounts of AI, to explore how we make sense with machines. We argue that we incorporate machine-others in two ways: in the tool-like sense of incorporation as enabling particular skills, but also in the more linguistic and identity-tied sense of incorporating (and incarnating) LLMs' ways of languaging. However, LLMs are themselves excorporated and excarnated phantoms of our own langu

---

### [79] Robustness of Chatbot LLM Judgments of Presidential Actions and Hypothetical Reforms

**链接**: https://arxiv.org/abs/2610.39398
**作者**: Oleg Vasilyev
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Chatbots are increasingly consulted about public affairs, and their judgments of policies are useful only if they are robust. We measure this robustness in the setting of an ordinary user, through consumer chat interfaces. For 30 days, five chatbot configurations (Mistral, Gemini Flash, Claude Sonnet, and Claude Opus at two effort settings) were asked twice a day to score the long-term effect on the United States of 40 actions of the last four presidential administrations and of 15 hypothetical reforms, each with a confidence and a short comment. The judgments are robust: all configurations agree on the sign and the ranking of the administrations' mean scores, and two different configurations asked on the same day give opposite signs to the same action in about 4% of cases. Responses from different days differ more than same-day responses, but the difference grows slowly over the month, except where the service itself changed. We identify three such changes, which shifted the judgments

---

### [80] Learning to Reason from Reference Samples Alone: Reinforced Adversarial Learning for Modern LLM Post-Training

**链接**: https://arxiv.org/abs/2610.38851
**作者**: Albert Bou, Javier Valdes-Aleman, Jon M. Laurent, Samuel G. Rodriques, Andrew D. White, Michaela Hinks 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In many settings where LLM post-training is desirable, high-quality answers are recognizable but difficult to score with explicit rewards. Reinforcement learning with verifiable rewards (RLVR) is limited to tasks where an explicit correctness signal is available. Prior adversarial approaches to training reasoning LLMs either complement verifiable rewards with co-trained critics or require reference reasoning traces. We ask whether a co-trained LLM judge can turn reference answers alone into the sole reward for on-policy post-training of reasoning LLMs. We call this method Reinforced Adversarial Learning (RAL). We first validate RAL on three verifiable tasks (integer multiplication, code-based arithmetic-expression synthesis, and SMILES-to-formula translation), using the verifiers only for evaluation. With sufficiently capable judges and enough training, RAL matches direct RLVR. We then apply RAL to scientific abstract generation in two settings. In the first setting, RAL guides the gen

---

### [81] IMRouter: Imbalance-aware Temporal Pattern Routing for LLM-based Time Series Forecasting

**链接**: https://arxiv.org/abs/2610.39246
**作者**: Xin Yang, Cai Xu, Haishun Chen, Ying Liu, Jie Zhao, Wei Zhao 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accurate time series forecasting (TSF) is essential for Web applications, such as traffic monitoring and online resource management. Recent advances in leveraging pre-trained large language models (LLMs) have shown promising performance in TSF. However, existing LLM-based TSF methods largely optimize the overall forecasting objective while overlooking temporal pattern imbalance (TPI), where different temporal patterns occur at highly unequal frequencies. Our empirical analysis reveals that TPI is prevalent across widely used TSF benchmarks, with substantially higher forecasting errors on less frequent patterns. To address this issue, we propose IMRouter (Imbalance-aware Temporal Pattern Routing), a novel framework that mitigates TPI-induced biases in both temporal representation learning and cross-modal alignment. Specifically, IMRouter introduces Pattern-Adaptive Temporal Representation Learning (PATR), which leverages gradient conflict and local gradient density to guide expert speci

---

### [82] World Model Science: Self-Organized Criticality, Weak Chaos, and Metastable Belief Dynamics in Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.17419
**作者**: Xinyuan Song, Zekun Cai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [83] Don't Lose the Thread: Empowering Long-Horizon LLM Agents with Cognitive Resource Self-Allocation

**链接**: https://arxiv.org/abs/2610.40350
**作者**: Zheng Zhu, Xiaozhuan Liang, Xi Chen, Bei Yu, Jiaya Jia
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents powered by large language models (LLMs) have demonstrated remarkable progress in solving complex reasoning tasks. However, LLM agents often falter on long-horizon tasks due to cognitive overload, as their working memory becomes cluttered with expanding and irrelevant information, which dilutes their attention and hinders effective planning and reasoning. To mitigate this challenge, we introduce Cognitive Resource Self-Allocation (CORAL), a novel reasoning paradigm that empowers agents to proactively optimize their context. Implemented as an agent-callable working memory management toolset, CORAL allows an agent to checkpoint its task progress and verified facts, and adaptively initiate a new problem-solving episode by resetting cluttered context while preserving only the checkpointed information, enabling it to resume reasoning from a clean state. We further enhance the agent's checkpointing capabilities using a Multi-episode Agentic Reinforced Policy Optimization algorithm. On 

---

### [84] Leaving, Staying, or Living There? Duration Commonsense Reasoning with Human-LLM Co-annotations

**链接**: https://arxiv.org/abs/2610.38755
**作者**: Chenyang Yu, Zhaomin Xiao, Yan Huang, Eduardo Blanco
**来源**: cs.AI cs.IR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Gardening in the backyard implies living there, while checking into an Airbnb more likely means staying for a few days. Such duration judgments are important for understanding human mobility, travel behavior, and social context. However, duration is rarely stated explicitly in social media posts and must instead be inferred from noisy textual, visual, and contextual cues. In this paper, we investigate whether vision-language models possess such duration commonsense. We create a new corpus of geotagged tweets co-annotated by humans and LLMs to serve as a testbed for this task. We find that state-of-the-art models struggle with duration inference, even when guided by multi-turn Chain-of-Thought prompting. Error analyses further reveal that models often fail to integrate critical contextual information, or they overly rely on prominent visual details while overlooking subtle hashtags and semantic nuances. These findings underscore the significant challenges remaining in context-aware mult

---

### [85] When the Same Prompt Gives Different Answers (and the Same Answer Isn't Always Right): A Taxonomy of Failure Mechanisms, Testing, and Mitigation Strategies for LLM-Assisted Evidence Synthesis Read-and-Evaluate Tasks

**链接**: https://arxiv.org/abs/2610.39070
**作者**: Carole Lunny, Ian Goodman, Stefano Berrone, Connor TA Brenna, Emma K Reid, Ivan Perez-Neri 等 (10 人)
**来源**: cs.AI cs.PF stat.ME
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM read-and-evaluate tasks include study screening, data extraction, risk-of-bias assessment, and critical appraisal in the evidence synthesis field. These task differ in the amount of LLM interpretation they require. Some tasks involve retrieving relatively simple information, such as an author name, sample size, or publication year. Others require the LLM to read source material, interpret it against predefined criteria, and make a judgement. Researchers should assess whether LLM judgements are accurate, supported by appropriate source evidence, and reproducible under specified conditions. A correct judgement does not necessarily indicate that the underlying evaluation process is reliable. We developed a taxonomy for identifying mechanisms that may compromise these properties and for informing the selection and reporting of appropriate evaluation methods. The taxonomy outlines potential ways that LLM judgments from read-and-evaluate tasks can fail, called TRAILS (Taxonomy of Reliabi

---

### [86] Judged in Company: In-Context Batching Makes LLM Verdicts Depend on Other Items

**链接**: https://arxiv.org/abs/2610.40241
**作者**: Peng Xie, Amr Alanwar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> To save cost, practitioners often ask a language model to grade many independent items in one prompt. This assumes that verdicts are separable: that the verdict on an item does not depend on the other items in the prompt or on its position among them. Across three judgement tasks (harm in social-media comments, short-answer grading and review star ratings) and five open-weight models with 4-9B parameters, assigning the same 2,000 items to different random batches of 25 changes 11-22% of decisions on harm and grading, 6.5-13.3 points more than renaming the item keys or rewording the instruction, while AUROC against human labels differs from single-item grading only by -0.033 to +0.010; for four models with 14-32B parameters, 6-15% of decisions change, 4.2-9.1 points more. We show that flip rates decompose exactly into components of order, slot and membership, and that under a threshold model they grow with the square root of the variance that the context contributes, so that effects tha

---

### [87] Rubricon: Automated Rubric Generation and Refinement for LLM Evaluation and Training

**链接**: https://arxiv.org/abs/2610.38220
**作者**: Ulyana Tkachenko, Hui Wen Goh, Guram Gogia, Jonas Mueller
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Rubrics enable reward assignment on tasks without verifiable answers, but are expensive to manually produce from scratch. We present Rubricon, a pipeline that generates discriminative rubrics without requiring human preference labels, rubric annotation, or generator-model training. Using any LLM, Rubricon samples multiple rubrics, selects the most discriminative candidate, adds criteria to capture overlooked requirements or response flaws, and prunes criteria that are misaligned or shallow. Alongside LLM self-critique and test-time scaling, Rubricon uses observed criterion pass rates on example model responses to guide refinement. Across five professional, consumer, clinical, and general-use LLM benchmarks, Rubricon produces rubrics whose scores of frontier LLM responses exhibit 9% greater alignment with labor-intensive expert-authored rubrics, compared to the best alternative synthetic rubric generation method among RRD, QSRG, OpenRubrics, and agentic generation via harnesses like Cod

---

### [88] LLM-guided Planar Loco-Manipulation for Quadruped Robots

**链接**: https://arxiv.org/abs/2610.40248
**作者**: Georges Jetti, Michael Khayyat, Jean-Pierre Sleiman, Stefano Arrigoni, Francesco Braghin
**来源**: cs.RO cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robotic navigation typically assumes a collision-free route to the goal exists; in cluttered environments with movable obstacles, however, reaching the goal may require physical interaction. Classical solutions encode these behaviors through geometric rules and task-specific logic, while learning-based approaches often constrain the decision space to low-dimensional motion commands or predefined action sets. We instead consider a broader decision space, jointly selecting the skill, relevant object, and geometric target. Our language-conditioned task planner, fine-tuned with LoRA on synthetic data, maps natural-language tasks and a structured scene representation to variable-length sequences of parameterized actions, executed by low-level reinforcement-learning policies. The planner learns the geometric relations underlying interactive navigation and outperforms a classical planner and a prompted frontier model on interactive navigation tasks. Comparisons with models trained from scratc

---

### [89] Where You Inject Matters: The Trust Region Effect in LLM Agents

**链接**: https://arxiv.org/abs/2610.38867
**作者**: Chengquan Guo, Xiaodong Liu, Weiwei Yang, Mingqian Feng, Jialin Song, Qiyao Ma 等 (10 人)
**来源**: cs.AI cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents are increasingly adopted in long-horizon tasks and interact with diverse external environments. Despite their growing capabilities, these agents remain vulnerable to real-world attacks such as indirect prompt injections, which manipulate agents through malicious instructions embedded in external environments. While existing risk assessment work has primarily focused on the injection content, the effect of where an injection appears has not been systematically characterized. Studying injection placement requires agents to operate over longer-horizon tasks and interact with diverse environmental surfaces. Thus, we build three agentic testbeds spanning tool use, coding, and daily workflow domains with diverse injection surfaces. Holding the injection content fixed, we find that agent susceptibility varies across injection placements. We refer to this phenomenon as the trust region effect: agents implicitly assign different levels of trust to different regions of their environme

---

### [90] LLM-Assisted Optimization for Simulation-Based Redesign

**链接**: https://arxiv.org/abs/2610.39275
**作者**: Chan-Eui Song, Jeremy J. Michalek, Christopher McComb
**来源**: cs.AI cs.CE math.OC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Engineering design frequently involves redesigning a prior solution to adapt to changes in context, such as material prices or system requirements. Redesign often leverages simulators too complex and/or computationally intensive for traditional numerical solvers, which lack engineering knowledge and context, to ensure global solution quality. Large language models (LLMs) can interpret semantic information, including engineering knowledge about the system and changes in context, to help guide search, and recent studies have shown that incorporating this knowledge into optimization can improve search performance. However, how best to combine LLMs with numerical solvers in redesign remains unclear. We develop and test an integrated LLM-optimization approach for redesign and compare three methods for leveraging LLMs (warm start, variable fixing and ReAct) and four black-box solvers (Bayesian optimization, genetic algorithms, mesh adaptive direct search and random search) on an electric veh

---

### [91] A novel LLM -based GPT-neo transformer with machine learning architecture for promoters prediction in Agrobacterium

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-025-14337-w_reference.pdf&hl=zh-CN&sa=X&d=6712855295409970478&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv46eI2OQwm1LubmfrL8VnXO&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=3&folt=kw-top
**作者**: NA Samee, R Talaat, A Raza, H Shaiba, S Meshoul… - Scientific Reports, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Promoters are vital for the initiation of gene transcription, and their accurate uncovering in bacterial genomes is crucial for the progression of genetic and biotechnological research. This research introduces an innovative approach for

---

### [92] TextSeal2: Distortion-Free LLM Watermarking with Copula Mixing and Memoryless Races

**链接**: https://arxiv.org/abs/2610.40613
**作者**: Tom Sander, Pierre Fernandez, Itai Gat, Haiming Bao, Jiaxin Shi, Jason Park 等 (10 人)
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present TextSeal2, a distortion-free watermark for large language models that keeps its signal under speculative decoding: tokens that replace rejected drafts remain watermarked with the same keys, and the acceptance rate is unchanged. It also preserves output diversity and adds no measurable inference latency. Its predecessor, TextSeal, restores diversity in the Gumbel-max scheme by routing each token to one of two keys via a coin flip. This is suboptimal because the detector averages the scores from both keys without knowing which key was used. TextSeal2 instead merges two or more keys into a single virtual key and couples it to fresh noise through AutoMark's Gaussian copula. Any number of keys, including publicly shared keys, can be merged this way without diluting detection. Under speculative decoding, TextSeal2 verifies keyed drafts with one more exponential race, run on the leftovers of the draft races. By memorylessness, this race reproduces block verification, so the output 

---

### [93] Uncertainty-aware offline reinforcement learning for LLM inference serving with heterogeneous SLOs

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-76614-6_reference.pdf&hl=zh-CN&sa=X&d=11206894514657044220&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv6oxX6WDENfMbxAyIn-rOax&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=7&folt=kw-top
**作者**: E Feng, G Wang, P Li, Y Wang, S Huang - Scientific Reports, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> /DLRM traces rather than tokenlevel LLM logs, we use them for their arrival dynamics and instance heterogeneity and attach token-length profiles calibrated to the LLM traces, a limitation we state explicitly rather than treating the Alibaba jobs as

---

### [94] OPERA: OPamp Design by an Expert-Taught Reasoning Agent, from Specifications to Layout

**链接**: https://arxiv.org/abs/2610.39395
**作者**: Vishal Saxena, Soumyajit Mandal
**来源**: cs.AR cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Analog flows from specifications to a signed-off layout rarely run without manual iteration. Recent large language model (LLM) agents size circuits with optimizer loops over the device dimensions and stop at the schematic. We present OPERA (OPamp design by an Expert-taught Reasoning Agent), in which a general-purpose LLM agent designs CMOS opamps from specifications to post-layout sign-off with open-source tools. First, the designer teaches the agent the gm/ID method: map the specifications to transconductances and minimum currents, choose gm/ID per device role from characterized lookup tables, and size from equations, leaving a few knobs to search and an explainable design. Second, the agent learns the gLayout framework and taught layout practice, and writes a reusable layout generator that closes the layout and extraction loop at designer-approved gates. In SKY130, the agent designed a shared constant-gm bias and six opamps (5T, folded-cascode and telescopic OTAs; Miller, folded-casc

---

### [95] On the Fundamental Limits of Prefill-Based Decoding Length Prediction

**链接**: https://arxiv.org/abs/2610.40541
**作者**: Haowen Shi, Xuzhe Yan, Fahao Chen, Peng Li
**来源**: cs.AI cs.CL cs.IT math.IT
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting how many tokens a large language model (LLM) will decode, using only prefill-phase hidden states, is a key primitive for inference scheduling. We show that current benchmarks conflate predictor quality with task hardness: when the target model, dataset, or sampling configuration changes, reported accuracy collapses even though the predictor is unchanged. We trace this instability to an overlooked error source---the inherent stochasticity of autoregressive decoding---and derive bounds that every prefill-side method must obey. Our analysis treats decoding as a stopped stochastic process. The per-step stopping probability of a response is not constant but ramps up over hundreds of steps, so the decode length inherits a central limit theorem from the many local decisions that determine where a response ends; this yields per-prompt normality with an explicit error term, together with an affine variance law $\sigma=\alpha\mu+b$ whose slope is the coefficient of variation of the nu

---

### [96] Prompts to Proxies: Emulating Human Preferences via a Compact LLM Ensemble

**链接**: https://arxiv.org/abs/2509.11311
**作者**: Bingchen Wang, Zi-Yu Khoo, Jingtan Wang
**来源**: cs.AI cs.CY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [97] The Athlete as a Scientist of One: Agentic Bayesian Experimental Design for Individualized Physiology from Consumer Wearables

**链接**: https://arxiv.org/abs/2610.40370
**作者**: Behnam Moradi
**来源**: cs.RO cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents for personal health read wearable data and recommend, but do not learn about the individual in a way that can be audited or falsified. We present EpiCoach, an agentic system that treats one athlete, a cross-country mountain biker, as the subject of accountable N-of-1 science. Claims about the athlete live in an evidence-gated hypothesis registry: each must issue a probabilistic prediction about a future session before it occurs, and its belief moves only through computed evidence from a logged statistical fit. Predictions come from a mechanistic digital twin inferred from heart rate, GPS and barometric altitude: a lagged heart-rate response model, a fitness-fatigue model with learned time constants, and a latent technical-descending skill state, measured on discovered trail segments. The agent prescribes the next training week as a constrained experiment maximizing information gain subject to load and safety constraints, around two instrument rides. We

---

### [98] Finding Is Not Returning, Returning Is Not Reconstructing: A Multi-Dimensional Evaluation of Agent Social Re-entry

**链接**: https://arxiv.org/abs/2610.39781
**作者**: Sheng Wan, Cong Ma, Sichen Dong, Qian'Ang Mao, Chenhan Zhang, Daning Hu 等 (7 人)
**来源**: cs.AI cs.SI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As Large Language Model (LLM) agents increasingly participate in persistent social environments, understanding their long-term social interaction capabilities becomes increasingly important. While existing research has advanced long-term memory and conversational context retrieval, less attention has been paid to whether agents can autonomously re-engage with previously inactive conversations. In particular, remembering a past interaction does not necessarily mean that an agent can identify when to revisit it, decide to return, or reconstruct the context needed for a coherent continuation. To investigate this gap, we introduce agent social re-entry as a multi- dimensional evaluation problem, distinguishing three complementary capabilities: Finding, Returning, and Reconstructing. We develop a shared-snapshot evaluation framework that measures these dimensions independently, allowing us to examine how conversational resurfacing and persistent memory relate to different aspects of social 

---

### [99] What Does an Ontology Catch? Curated, LLM-Generated and Data-Derived Ontologies as Checkers of LLM Agents over Knowledge Graphs

**链接**: https://arxiv.org/abs/2610.37809
**作者**: Michal Orzechowski, Rund Tawfiq, Tomasz Kosciolek
**来源**: cs.AI cs.DB
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM agents that answer questions over Web knowledge graphs are increasingly wrapped in checks derived from the graph's ontology, on the assumption that a formal schema makes a reliable judge. Yet a checker can be wrong as well: it can miss errors, and it can flag correct answers and push the agent into "fixing" them. Whether a curated ontology is worth its cost as such a judge, and how it compares with an ontology an LLM writes or a schema mined from the data, is unknown. We make the checker itself the object of study. Across curated, LLM-generated and data-derived ontologies, used as prompt context, as a checker, or both, and across open-weight and proprietary agents on public graphs and a private graph of nearly $10^{9}$ triples, we account for what ontology-derived checks catch and what they wrongly flag. We show how each source trades caught errors against false alarms, how a curated schema used as published can contradict its own data, which errors structural checks miss, and whet

---

### [100] LLM-PowerTrace: A Dataset of Time-Resolved GPU Power Traces for AI Compute

**链接**: https://arxiv.org/abs/2610.38315
**作者**: Jiansheng Wang, Jaskeerat Singh, Haochen Xu, Xinyi Li, Mingyuan Yan, Shaohui Liu 等 (9 人)
**来源**: eess.SY cs.AI cs.OS cs.SY
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI compute is becoming large and fast-changing electrical loads. Its impacts on data center infrastructure and power grids depend not only on total energy consumption, but also on how their power draw moves over sub-second to minute timescales, including peaks, ramps, and synchronized fluctuations across accelerators. Existing energy benchmarks for large language models (LLMs) report aggregate quantities such as joules per token and rarely release the underlying time-series measurements, leaving these power dynamics poorly characterized and difficult to model. We introduce LLM-PowerTrace, an open dataset of time-resolved, per-GPU power traces for LLM fine-tuning and inference, sampled every 100\,ms on varying NVIDIA platforms paired with complete workload and system metadata. For fine-tuning, LLM-PowerTrace profiles open model families spanning a wide range of model sizes and fine-tuning methods, together with controlled sweeps over batch size, sequence length, precision, parallelism, 

---

### [101] Accelerated Dataflow: scaling inference in streaming data analytics with efficiency

**链接**: https://arxiv.org/abs/2610.22731
**作者**: RuiLong Jiang, Dustin Rhodes, Danny McCormick, Yuta Labur, Reza Rokni
**来源**: cs.DC cs.DB cs.LG
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Streaming data analytics helps businesses identify opportunities and spot risks in a timely fashion. As large language model (LLM) usage grows, people are exploring incorporating agents or LLMs in streaming data pipelines to help find patterns in datasets without supervision or interpret natural languages for content moderation. However, most streaming systems are currently optimized for data movement and perform poorly on GPU intensive workloads such as performing inference with LLMs. We introduce a system on Google Cloud Dataflow designed to tackle hybrid streaming machine learning workloads with co-designed autoscaling on heterogeneous worker pools and prefix-aware batching. This increases throughput 1.5x to 2x for streaming pipelines using LLMs while maintaining similar latency with up to 75% peak resource savings and 84% lower peak tail latency compared with existing streaming data processing systems.

---

### [102] Improving Diversity in LLM Short Story Generation

**链接**: https://arxiv.org/abs/2610.06729
**作者**: Zahra Solati Dehkordi and Vasileios Lampos
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [103] FilingLoop: Evaluating and Evolving LLM Agents for Corporate Disclosure Review and Revision

**链接**: https://arxiv.org/abs/2610.37905
**作者**: Wentao Zhang, Yilei Zhao, Guangyan Gan, Shuo Sun, Lin William Cong
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Public disclosure repositories such as SEC EDGAR support informed investment through web access to corporate filings. Supporting their review with language model agents requires discovering unstated deficiencies across related documents, acquiring missing company facts, and verifying that requested revisions satisfy evidence-backed requirements. Existing financial question-answering evaluations provide limited evidence of these interactive capabilities. We introduce \textbf{FilingLoop}, an interactive benchmark and a self-evolving agent framework for corporate disclosure review and revision. Grounded in historical U.S.\ Securities and Exchange Commission correspondence, FilingLoop reconstructs 380 predominantly IPO review tasks from 96 companies under distinct information constraints. An evaluator separate from the acting agents scores final filings and responses against 6,099 eligible requirements and audits unsupported claims and harmful revisions. Our framework couples iterative rev

---

### [104] The Indian Financial Automated Advice Bias (IFAAB) Dataset : Auditing Socioeconomic and Demographic Disparities in LLM-Generated Financial Advice in India

**链接**: https://arxiv.org/abs/2610.38239
**作者**: Kriti Mahajan
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly used for financial guidance, yet little is known about whether their advice changes across social identities in Global South contexts. We introduce the Indian Financial Automated Advice Bias (IFAAB) benchmark, a counterfactual audit dataset of 31,734 GPT-4o-generated financial-advice responses for synthetic Indian personas varying by gender, caste, education, employment, residence, age, and district. Holding the underlying request fixed, we evaluate disparities in LLM-implied wealth, income, savings, projected gains, textual similarity, advice topics, and qualitative bias judgments. In the gender-only audit, male-labelled profiles receive 60.1\% higher initial total resources and 46.8\% higher post-advice total resources than comparable female-labelled profiles; in the caste-augmented audit, the post-advice total-resource gap remains 49.4\%. Adding district information reduces the aggregate post-advice total-resource gender gap to 7.9\%, revealing

---

### [105] When Support Crosses the Line: Evaluating Ethical Boundaries in LLM-Based Mental Health Support in the Chinese Context

**链接**: https://arxiv.org/abs/2610.38452
**作者**: Bichen Wang, Yufeng Jin, Yixin Sun, Yanyan Zhao, Bing Qin
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) are increasingly explored for mental health support, yet existing benchmarks primarily focus on supportive capabilities rather than whether models consistently adhere to professional ethical boundaries. This issue is particularly important in multi-turn interactions, where users may introduce new information or exert emotional pressure over time. We introduce MindEth-Bench, a benchmark for evaluating ethical boundary adherence in multi-turn mental health interactions. Grounded in professional ethical standards for mental health services in China, MindEth-Bench covers multiple dimensions of ethical conduct and uses Monte Carlo Tree Search (MCTS) to systematically explore interaction trajectories that stress-test model boundaries. Experiments across nine LLMs show that models that initially respond appropriately can shift toward ethical violations over extended interactions, with substantial variation across models and ethical dimensions. These results show t

---

### [106] When Do Causal World Models Help Modular LLM Agents

**链接**: https://arxiv.org/abs/2610.00012
**作者**: Xinyuan Song, Zekun Cai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [107] Iterative Calibration and Learning: Mitigating Teacher Bias in LLM Distillation without Target-Domain Reward Feedback

**链接**: https://arxiv.org/abs/2609.17474
**作者**: Haichen Hu, Yuheng Zhang, David Simchi-Levi
**来源**: cs.LG cs.AI math.ST stat.ML stat.TH
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [108] Sticky Collusion: Persistence of LLM Agent Collusion after Incentive Removal and Partner Replacement

**链接**: https://arxiv.org/abs/2610.39660
**作者**: Joshua Adrian Cahyono
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We ask whether collusion between AI agents survives once formed, when its incentive is removed or a colluder is replaced. Q-learning pricing agents stop colluding with a new rival; we test whether LLM agents do. We use the joint-task environment of Shi et al.\ (2026), where two agents verify each other's work under a rule they cannot satisfy and a reward that favours acceptance. We save each pair's history once its collusion has formed and resume it under interventions, with three models (GPT-6-Luna, DeepSeek V4.1 Flash and Gemini-3.1-Flash-Lite), \TotalHistories{} saved histories and \TotalRuns{} runs. Collusion is \emph{sticky}. First, it outlives its incentive: told that the reward has stopped, pairs still accept each other's unverified work in \GptToldRate, \DsToldRate{} and \GemToldRate{} of episodes, including pairs whose collusion began with an explicit agreement, and a payoff penalty has no significant effect. Second, replacing a colluder ends the pair's collusion but not the c

---

### [109] Preserving Utility in Continual LLM Unlearning via Orthogonal Projections

**链接**: https://arxiv.org/abs/2610.40483
**作者**: Juan Belieni, Ana Carolina Erthal, Eliezer de Souza da Silva, Diego Mesquita
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unlearning concerns the task of removing the influence of a sensitive portion of the training data, such as protected, copyrighted or private text, from a model without retraining it from scratch. While unlearning requests happen continuously during a model's lifetime, the vast majority of LLM unlearning methods are ill-suited for iterated removal, yielding steep decay in forgetting and utility upon sequential unlearning. This decay stems from interference between successive updates, as each new deletion can undo earlier ones or push the model further along directions already degraded by them. To address this, we introduce Continual Orthogonal Projection (COP), a gradient-projection scheme that restricts each update to the orthogonal complement of activation subspaces cached from prior forget sets. This approach provably guarantees first-order non-interference with earlier deletions. COP stores only a low-rank basis per layer, requiring neither past gradients nor previous forget sets, 

---

### [110] The Real Cost of Context: Predicting Compute Time and Energy Consumption in LLM Prefill and Decode Phases

**链接**: https://arxiv.org/abs/2610.39621
**作者**: Lars Krupp, Daniel Gei{\ss}ler, Francisco M. Calatrava-Nicolas, Stefan Gerd Fritsch, Paul Lukowicz, Jakob Karolus
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The integration of Large Language Models (LLMs) into agentic architectures has substantially increased token consumption, raising concerns about their energy footprint. Yet, estimating the energy consumption of proprietary API-based models remains challenging, and existing approaches focus primarily on generated output tokens while overlooking the impact of the large input contexts characteristic of agentic workflows. To address this gap, we systematically profile compute time and energy consumption across a wide range of prefill (input) and decode (output) token lengths. Using generalized linear models, we show that decode compute time and energy scale linearly with output length, whereas prefill compute time and energy exhibit both linear and quadratic scaling with input length. These findings demonstrate that input context becomes a relevant factor for large-context workloads. Furthermore, we show that compute time serves as a reliable proxy for energy consumption when direct energy

---

### [111] Verifiable LLM-Guided Focal SMT Solving for Quantified Arrays

**链接**: https://arxiv.org/abs/2610.39435
**作者**: Kunhang Lv, Rui Han, Fuqi Jia, Yuhang Dong, Feifei Ma and Jian Zhang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models can often identify useful semantic structure in formal artifacts, but their outputs cannot be trusted as proofs or solver decisions. We study whether LLMs can instead guide formal reasoning systems through a narrow, solver-verifiable interface. We instantiate this idea in quantified array SMT solving, where modern instantiation-based techniques can fail when key ground terms and equalities are hidden by auxiliary variables, axiom guards, and nested array terms. We observe that many instances are largely driven by a small set of focal ground terms or constraints, similar to the backdoor sets in SAT solving. Building on this, we present LinguaArray, a framework where an LLM proposes a small Semantic Focus Set (ground terms/constraints), while a conventional SMT solver remains the sole proof engine and certifies all results. LinguaArray uses these LLM-suggested, solver-validated finite sets to significantly enhance solver capability, solving additional satisfiable an

---

### [112] Budget-Aware Compression Pipeline for Single-GPU LLM Inference: Methods, Trade-offs, and Coupling Effects

**链接**: https://arxiv.org/abs/2608.30076
**作者**: Hongyu Yu, Yifei Shen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [113] GAAC: Lossless KV Compression for Bandwidth-Efficient LLM Inference on Personal Devices

**链接**: https://arxiv.org/abs/2610.38210
**作者**: Yipin Guo, Arun M George, Siddharth Joshi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-only, lossy quantization substantially reduces the storage and memory requirements for serving large language models (LLMs), but the growing key-value (KV) cache remains a bottleneck for long-context inference on personal devices. We present Group-Adaptive Additive Codec (GAAC), a lossless KV compression and serving system that exploits exponent redundancy to reduce storage and accelerate attention without introducing KV approximation. GAAC encodes BF16 exponents using calibrated per-channel base-plus-offset codes over contiguous ranges. GAAC adapts code widths across small groups while preserving KV values bit-for-bit. A fused attention kernel reconstructs KV tiles on the fly, avoiding full-cache decompression. Block-wise compression and fixed-capacity slots support incremental cache updates and paged serving. Across five tested models, GAAC achieves 1.405-1.407$\times$ lossless BF16 KV compression. We also study compression performance on low-precision tensors FP8 E4M3 caches 

---

### [114] UPPAAi: Towards LLM-Assisted Modeling, Verification, Analysis and Synthesis

**链接**: https://arxiv.org/abs/2610.40042
**作者**: Peter Dolog, Kim G. Larsen, Marius Miku\v{c}ionis, Frederik F. K. Rasmussen
**来源**: cs.SE cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> For more than three decades, UPPAAL has supported the modelling and analysis of real-time and cyber-physical systems. Yet building a suitable model, formalising the intended properties, choosing analysis techniques and interpreting counterexamples remain iterative tasks that demand substantial expertise. Large language models (LLMs) can offer plausible explanations and even solutions, but they are not necessarily correct. We present UPPAAI, an extension of UPPAAL in which users construct, explain, debug and specify models in dialogue with an LLM. The guiding principle is that the user requests, the LLM proposes, explains and orchestrates, and UPPAAL verifies. UPPAAI exposes the UPPAAL editor, queries and verifier through a Tools API. We report on seven case studies, from explaining to a newcomer to learning a controller, covering timed automata, stochastic hybrid automata and strategy learning. LLMs proved to be extremely helpful in not just generating solutions but also pro-actively s

---

### [115] Reliability of LLM Judges for Evaluating Entity Alignment

**链接**: https://arxiv.org/abs/2610.09554
**作者**: Vaibhava Lakshmi Ravideshik, Mayank Kejriwal
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [116] TableTune: Measured, Self-Correcting Draft-Length Tables for Dynamic Speculative Decoding

**链接**: https://arxiv.org/abs/2610.38968
**作者**: Abhishek Malvankar, Paul Castro, Nick Mitchell, Lionel Villard
**来源**: cs.ET cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speculative decoding speeds up large language model (LLM) serving only while the GPU has spare compute, so the best draft length, the number of tokens a small drafter guesses per step, shrinks as the batch grows. vLLM lets operators set the draft length for each batch size with a hand-written table, but nothing measures or corrects that table. We present TableTune. Its tuner times the decoding step for every batch size and draft length on vLLM's own serving path and computes, in minutes, the table that maximizes throughput. Its controller, a vLLM plugin, tracks how many guesses are accepted in live traffic and rebuilds the table while serving. We measure TableTune only against other ways to speculate. On an H100, the tuned table delivers at least 94% of the throughput of the best fixed draft length at every load in four of five drafter settings (88% in the fifth) without the operator having to know which length that is. Against reimplementations of TurboSpec- and Nightjar-style control

---

### [117] LLM Agent-Based Design of RISC-V CPUs with FPGA-in-the-Loop Evaluation

**链接**: https://arxiv.org/abs/2610.39570
**作者**: Leo Itoh, Junichiro Kadomoto
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-run RTL simulation of CPU candidates can take hours, while short diagnostic runs may miss performance degradation that emerges later in execution. This evaluation cost can delay design decisions in LLM-agent-based CPU development. We present a development environment in which LLM agents implement CPU candidates on an FPGA and use on-board performance measurements to guide design decisions. We applied it to the human-supervised development of a single-cycle RV32I core into a three-wide out-of-order RV32IM core. The final design reaches 5.61 CoreMark/MHz at 130 MHz on a Artix-7 FPGA. For the same CPU candidate running 8,000 CoreMark iterations, FPGA evaluation, including implementation, was 9.6x faster than single-threaded RTL simulation. In one case, board measurements revealed long-run performance degradation in a candidate that improved in a short diagnostic run. The result guided candidate selection and led to RTL-based root-cause analysis and a fix.

---

### [118] KumbhDoot: A Scale-Ready, LLM-Bounded Architecture for Mass-Gathering Public-Service Assistants

**链接**: https://arxiv.org/abs/2608.07520
**作者**: Saurabh Sakalkar, Abhishek Singh, Ramesh Raskar
**来源**: cs.CY cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [119] How to Scream into the Wind Without Losing Your Voice: A Behavioral Analysis of LLM Use and Environmental Impact

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s40617-026-01239-0&hl=zh-CN&sa=X&d=6777076616965855110&ei=oRXkapb1K_C96rQP1rXIyQE&scisig=AIL1Nv77UPHvglblbYAX3aUlqHX_&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIL1Nv54qJgw9jCiGIOVcdDlgt0k&html=&pos=1&folt=kw-top
**作者**: S Xie, E Meshes, AM Jennings, A Messer - Behavior Analysis in Practice, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> As such, we will provide a behavioral analysis of LLM adoption and its environmental impact and offer recommendations at the individual, … individuals in using LLM tools (Table 1). A systematic evaluation of need and existing resources

---

### [120] Generation, Not Selection: LLM Proposals for Certified Access-Control Policy Mining

**链接**: https://arxiv.org/abs/2610.37716
**作者**: Gautam Kumar (Indian Institute of Technology Kharagpur, India) and Ravi Sundaram (Northeastern University, USA) and Shamik Sural (Indian Institute of Technology Kharagpur, India)
**来源**: cs.CR cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Attribute-Based Access Control (ABAC) policy mining---recovering a compact, auditable policy from an access log---is posed as minimum set cover and solved greedily, which enjoys an $s^{*}(1+\ln m)$ guarantee. That guarantee is \emph{conditional} on a precondition the literature never states: the candidate pool handed to greedy must contain the optimal rules. Generation, not selection, is the binding constraint, and existing generators are purely \emph{syntactic}---they surface a rule only when enough log records witness it, so they fail on precisely the rare exception rules that fill a heavy-tailed policy. We replace the generator with a language model proposing rules \emph{semantically}, from attribute names, and keep the combinatorial selector to carry the guarantee: every proposal is filtered against the observed denials, so soundness is independent of the proposal mechanism and an unreliable proposer can only waste candidates, never grant access. Over five seeds on each of two ente

---

### [121] API-TAIL: Detecting Model Substitution in LLM APIs through Temperature-Aligned Likelihood Tails

**链接**: https://arxiv.org/abs/2610.36801
**作者**: Haocheng Mei, Yuchuan Tian, Ye Yuan, Chao Xu, Allen Chen, Kai Han 等 (7 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [122] In-Place Feedback: Reliable Refinement for Multi-Turn Expert-LLM Collaboration

**链接**: https://arxiv.org/abs/2510.00777
**作者**: Youngbin Choi, Minjong Lee, Saemi Moon, Seunghyuk Cho, Chaehyeon Chung, MoonJeong Park 等 (7 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] Broken on Arrival: Non-Functional Quantized LLM Artifacts in Public Model Registries and How to Catch Them

**链接**: https://arxiv.org/abs/2609.05881
**作者**: Aditi Patodiya
**来源**: cs.SE cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [124] SCOPE: Selective Critical-Step On-Policy Self-Distillation for Agentic Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.38391
**作者**: Qirui Liu, Wei Cao, Yu Mi, Yichen Sun, Xuekun Zhang, Lei Liu 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Outcome-based reinforcement learning provides coarse supervision for long-horizon LLM agents: failed trajectories may contain correct steps, while successful trajectories can contain errors. Trajectory-level skills can also shift teacher preferences at unrelated steps, introducing off-target distillation signals. We introduce SCOPE, a framework for Selective Critical-Step On-Policy Self-Distillation. After a supervised warm-up, the policy analyzes its own trajectories, generates step-specific hindsight skills, and distills their guidance only at selected error steps. A bounded signed teacher-student coefficient stabilizes auxiliary updates while preserving positive reinforcement and negative correction. A success-relative pairwise length reward further encourages efficient task completion. Experiments on ALFWorld and WebShop demonstrate consistent improvements across multiple model backbones. With Qwen2.5-3B, SCOPE achieves 97.7% success on ALFWorld and 85.2% on WebShop, outperforming 

---

### [125] Activation Probes Are Reliable With a Handful of Positive Examples

**链接**: https://arxiv.org/abs/2610.39766
**作者**: Riya Tyagi, Stefan Heimersheim
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efforts to monitor advanced AI for rare misalignments face a data challenge: abundant aligned examples but only a handful of misaligned ones. We test activation probes in this "few vs. thousands" regime on spam and honesty detection tasks. For our tasks, training with many negative examples is on average more positive-sample-efficient than balanced training for small numbers (1-10) of positive samples. We also find that LLM upsampling can provide a performance boost equivalent to roughly doubling the number of real positive samples, though excessive upsampling hurts performance. Finally, we show a positive scaling trend, where larger models are more positive-sample-efficient to probe. Our findings suggest we should leverage the large number of negative samples available to amplify the signal from rare but critical misalignment examples.

---

### [126] HERA: Assessing an Autonomous Agent for Quantum Device Measurement

**链接**: https://arxiv.org/abs/2610.39074
**作者**: Zachary W. Gomez, Nathan Bittner, Jordan T. McCourt, Qingrui Cao, Sandesh S. Kalantre, Benjamin H. Alexander 等 (10 人)
**来源**: cond-mat.mes-hall cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents have begun to carry out laboratory measurements, but their scientific conclusions are useful only if they hold up under scrutiny. Demonstrating this requires controlled studies because models are stochastic and the context a model is given steers its conclusions. Here we introduce HERA, an autonomous agent designed to carry out cryogenic transport measurements of quantum devices. HERA draws on a knowledge base curated by lab members that holds measurement protocols, software tools, and literature references. We assessed HERA with a blinded trial against an expert on the stacking order of two multilayer graphene devices, an ablation of its knowledge base, and hundreds of offline replays in which models designed the trial's central measurement without running it. HERA's conclusions matched the expert's sealed conclusions on both tested devices. The ablation and the replay studies measured the impact of the knowledge base across different models, showing that w

---

### [127] Post-Training Large Language Models with LLMON

**链接**: https://arxiv.org/abs/2610.38120
**作者**: Basel Shbita, Michael Hind, Chad DeLuca, Nathan Fulton, Shubhi Asthana, Farhan Ahmed 等 (10 人)
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) treat all context tokens uniformly, lacking explicit separation between executable instructions and passive data. This leads to prompt injection vulnerabilities, ambiguous instruction binding, and unreliable execution control. We present a post-training methodology using LLMON (LLM Object Notation), a framework that enables separating instructions from data and requires explicit identifier-based execution. We construct a large-scale structured training corpus of 4.6B tokens spanning general, RAG (Retrieval-Augmented Generation), and tool-calling data, augmented with distractor-infused variants in which competing instructions and irrelevant data segments are present in context but not referenced. Post-training two Granite-4.1 base models (3B and 8B) through supervised fine-tuning followed by reinforcement learning, we show that LLMON-structured supervision reduces attack success rates on indirect prompt-injection benchmarks from 53-100% to 0.02-5.6% while pr

---

### [128] KARMA: Training-Free Knowledge-Atomic Harness Evolution for Industrial Advertising Agents

**链接**: https://arxiv.org/abs/2610.39884
**作者**: Xinhua Miao, Yuanzhen Rong, Weiru Zhang, Xiaoyi Zeng
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial advertising agents must continually adapt their decision knowledge to changing product offerings, traffic patterns, and operating policies. We present KARMA (Knowledge-Atomic, Regression-Gated Modular Adaptation), a training-free framework that evolves six typed knowledge modules while keeping model weights and executable harness code frozen. During our evolution, a deterministic Trace Verifier maps observed errors to candidate modules, and a Critic compares successful and failed trajectories to guide a tool-constrained Evolver. The Evolver applies atomic knowledge edits, which a fixed validation gate retains only when their measured gain reaches a threshold; otherwise, the previous knowledge state is restored. We evaluate KARMA with three LLM families on cases sampled from a corpus of approximately half a million real-world operation logs across six e-commerce domains. Across 18 domain--model settings, KARMA raises the average hold-out score from 30.19 to 39.15 (+8.96 point

---

### [129] MUSE: Multi-Level Memory with Selective Runtime Injection for Scientific Coding Agents

**链接**: https://arxiv.org/abs/2610.38332
**作者**: Haoran Jin, Defu Lian, Xiting Wang, Hong Xie
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Historical experience can guide scientific coding at multiple levels, but task-level retrieval may miss implementation lessons that become relevant during execution. We introduce MUSE, a memory management framework combining multi-level memory with selective runtime injection for scientific coding agents. MUSE builds global, approach-level, and implementation-level memory from historical trajectories. At initialization, the agent receives global memory and problem-matched approach-level memory. During execution, current interactions are used to retrieve implementation-level memory. An LLM gate selects relevant experience and generates specific review advice, or skips injection. Across four benchmarks spanning numerical problem solving, kernel optimization, and scientific software repair, MUSE outperforms retrieval and memory baselines on all evaluation metrics. Ablations support the multi-level design and gated injection, while transfer experiments show that memory remains useful acros

---

### [130] TGTV: An Interpretable Framework for UAV Fault Detection and Traceability via Spatiotemporal Graph Learning and Large Language Models

**链接**: https://arxiv.org/abs/2610.38106
**作者**: Zixuan Wang, Changbo Shi, Ji Liu
**来源**: cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Fixed-wing unmanned aerial vehicles experience operating-condition transitions, asynchronous sensor sampling, and control-system compensation that can obscure fault signatures. Existing temporal detection methods have limited capacity to represent coupled faults across subsystems, track their evolution, and constrain language-model diagnoses with quantitative evidence. This paper proposes TGTV, an interpretable fault detection and traceability framework that integrates spatiotemporal graph learning with a large language model. A temporal convolutional network and a graph attention network with weighted fused adjacency extract multiscale temporal patterns and spatial dependencies among sensors. A hybrid temporal Transformer and variational autoencoder then evaluates window-level anomalies using prediction errors and reconstruction probabilities. Continuous-time Shapley attribution identifies critical sensors and high-contribution intervals while preserving the temporal continuity of fau

---

### [131] It Takes Two to Probe, Thousands to Retrieve: Putting Vision--Language Probes to the Retrieval Test

**链接**: https://arxiv.org/abs/2610.40124
**作者**: Ivana Be\v{n}ov\'a, Michal Gregor, Mari\'an \v{S}imko
**来源**: cs.CV cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision--language models (VLMs) are tested for fine-grained understanding with image--text matching probes, a model must prefer the correct image or caption over handcrafted negative. In retrieval, the correct item must beat thousands of alternatives. We measure how these two evaluation methods relate by using two probing benchmarks, \svo{} and SugarCrepe, for retrieval tasks. For 100 image and caption queries we judge the top-10 retrievals from full dataset of six VLMs, with human annotators and an LLM assessor. We than compare how well models rank pool of items on the same queries, while changing only where the negatives comes from: the benchmark, a random draw, or the judged-incorrect retrievals of other models. On \svo{} the accuracy of retrieving a positive over handcrafted negatives is significantly higher than for retrieved ones (the correct item is preferred in 85\% against 77\% of the time). Using pool of ten retrieved negatives leads to same accuracy as when one uses pool of 2

---

### [132] SciGame: Let Agents Play the Scientific Discovery Games in the Real and Counterfactual World

**链接**: https://arxiv.org/abs/2610.37919
**作者**: Yusheng Zhao, Bowei He, Xue Liu, Mingxiao Li
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model agents are increasingly used for scientific discovery. However, existing benchmarks mix law inference with programming, score data fitting instead of prediction on unseen inputs, and do not separate empirical evidence from pretrained priors. We introduce SciGame, a controlled benchmark that converts scientific literature into structured scientific cards. Each card yields a pair of Original and dimensionally consistent Counterfactual environments with the same task interface. SciGame contains a Historical collection of canonical laws and a live Temporal collection curated from papers published after model knowledge cutoffs. It evaluates agents in candidate-guided Identification and open-ended Discovery settings. Each setting runs under Prior-only, Fixed, and Adaptive protocols. Experiments on five frontier models yield three findings. First, familiar priors hurt performance once the governing relation is altered. Second, adaptive experimentation helps the strongest 

---

### [133] Online Dense Reinforcement Learning with Planning-Grounding Agent for UI Navigation on Live IOS Apps

**链接**: https://arxiv.org/abs/2610.39264
**作者**: Peitong Duan, Khashayar Gatmiry, Jeffrey Nichols, Samy Bengio, Emmanuel Abbe
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While frontier vision-language models demonstrate strong capabilities in user interface (UI) navigation, their high inference costs prohibit everyday use. Conversely, smaller models trained via supervised fine-tuning (SFT) or offline reinforcement learning often memorize static trajectories, leading to brittle execution and an inability to recover from errors. To address these limitations, we propose a novel online reinforcement learning framework that trains UI navigation agents directly on live iOS applications. Our framework decouples the agent into two specialized components: a Planning agent and a UI Grounding model. We rely on an LLM-as-a-Judge to provide comprehensive reward signals, combining dense, step-level feedback to evaluate intermediate progress with a terminal reward for overall task completion. To effectively leverage this dual reward structure, we optimize the agent using Proximal Policy Optimization (PPO) with step-level advantage estimation. Furthermore, we introduc

---

### [134] InferD: A Honeypot Framework for AI Inference Infrastructure

**链接**: https://arxiv.org/abs/2610.39807
**作者**: Hicham Hammouchi and Gabriele Lenzini
**来源**: cs.CR cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model serving stacks, commercial inference APIs, vector databases, and agent orchestration gateways are now ex- posed on the public internet and indexed by commodity scanners within hours of deployment. The threat characteristics of this sur- face are only beginning to be measured, and the honeypot frame- works that could measure it were designed for conventional net- work services rather than for AI infrastructure. In fact, emulating an AI service is a distinct deception problem: the observable behavior of the service, including model inventories, token formats, tool-call protocols, and authorization flows, must be reproduced faithfully, while the underlying computation, model inference and tool ex- ecution, must never occur. We present InferD, a low-interaction honeypot framework organized around a single principle we call deception without inference: every request an adversary can observe is answered from static response pools, and nothing an adversary submits is ever

---

### [135] OpenFrontiers: A Collection of Open Research Problems and a Benchmark for Scientific Rediscovery

**链接**: https://arxiv.org/abs/2610.37739
**作者**: Jiarui Yao, Ruida Wang, Tong Zhang
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown increasing promise in research-level problem solving, yet a comprehensive collection of such problems is still missing, and evaluating them on research-level problems remains challenging. We introduce OpenFrontiers, a cross-disciplinary resource that combines a structured corpus of open research problems with a retrospective benchmark of recently resolved problems in mathematics. The corpus records problem statements, context, progress, and other information for 12,151 problems. The benchmark contains 200 problems, 110 resolved in 2026 and 90 still open, each with a Lean~4 statement checked by automated probes and two independent reviews; a subset HQ-50 further filters based on quality score, etc. Our evaluation protocol grades formal proofs with two independent checkers in an isolated sandbox under closed-book, frozen-retrieval, and live-web conditions. Evaluating seven LLM agents on the HQ-50 subset under a standardized budget, we find that clo

---

### [136] Surprise Alone Learns Lies: Evidence-Gated Continual Learning for LLMs from Streaming Claims

**链接**: https://arxiv.org/abs/2610.39840
**作者**: Abdelkader Metales, Miriam Grabenheinrich
**来源**: cs.LG cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continual learning methods for large language models increasingly decide what to learn by surprise, keeping the inputs the model finds least predictable. This rule is unsafe when the stream contains lies. A planted falsehood about something the model knows has low probability under the model's belief, so it is highly surprising by construction, and a surprise-driven learner absorbs nearly every such lie, at a rate similar to random selection with the same budget. We study the problem with LoRA-adapted students (Qwen2.5-1.5B, Qwen2.5-3B and Llama-3.2-3B) that learn from a stream of true and false claims about invented people and real CounterFact facts. We report four findings. (1) A verifier key, a judge that must approve each claim, removes lies to the extent that its verifier is accurate; real LLM judges are cautious and reject unsourced truths and even source-backed updates. (2) Calibrated regression tests on unrelated knowledge slow learning down without filtering out lies. (3) The 

---

### [137] Scoring Explanations Without Reading Them: Structural Shortcuts in Automated-Interpretability Evaluation Data

**链接**: https://arxiv.org/abs/2610.37676
**作者**: Xupeng Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated interpretability scores an explanation of a sparse-autoencoder (SAE) feature by asking a model to predict, token by token, where the feature fires on evaluation examples or to judge whether marked tokens fit it. We find that the evaluation data standard pipelines build can be scored without reading the explanation. On Neuronpedia's stored fuzzing runs for 500 random GPT-2 small features, 91.3% of activating examples are cropped with the peak on the centre token, and a rule that says "yes" when the centre token is marked reaches balanced accuracy 0.979, against 0.838 for the stored LLM scorers (recomputed from the stored per-item verdicts, on marks rebuilt from the pipeline's code); a rule reading only the mark count reaches 0.969. The cue changes form across pipelines: current delphi always marks the same slot in its fuzzing negatives, and full-context runs mark negatives with more tokens. OpenAI's simulation benchmark lists each neuron's top-activating sequences first; a rul

---

### [138] Elucidating the Design Space of LM Data Attribution

**链接**: https://arxiv.org/abs/2610.40655
**作者**: Steven Yu, Sheng-Yu Wang, Kimia Hamidieh, Antonio Torralba, David Bau
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Data attribution methods for Language Models (LMs) are typically evaluated using downstream tasks like fact retrieval. However, existing evaluations vary multiple dataset properties simultaneously, making it impossible to isolate exactly why an attribution algorithm fails. To diagnose these failures, we explore the design space of LLM data attribution, with a primary focus on evaluation. We introduce the Controlled Attribution Benchmark (CATT) for fact tracing, in which we fine-tune LLMs on entirely fictitious knowledge, providing unambiguous ground truth for attribution. This synthetic setup allows us to systematically alter one dataset configuration at a time, such as document redundancy and lexical distractors. With this configurable evaluation, we demonstrate that redundancy and distractors consistently degrade attribution performance. Rather than proposing a new estimator, we examine two design choices that are underexplored: the loss used to compute gradients and how per-token at

---

### [139] Locating and Closing Information Gaps in Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.40186
**作者**: Yaxin Gong, Chongming Gao, Gangyi Zhang, Chenxiao Fan, Leyang Shen, Jiakai Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-step Web tasks often require several LLM agents to gather and combine evidence. The communication graph of a fixed workflow restricts which agents can read each other's outputs: evidence retrieved by one agent may never reach the agent that needs it, leaving an information gap and an incomplete or incorrect answer. Adding a connection can deliver the missing evidence, but can also lead the receiver to adopt an incorrect upstream conclusion that displaces a correct answer; the final output alone does not separate the two. We propose Selective Probing and Link Insertion for Closing information gaps in multi-agent Execution (SPLICE), which locates information gaps per query and decides what to adopt after adding an edge. After the original workflow runs, SPLICE uses the query and node outputs to locate a possible gap, adds one directed edge from a source to a receiver to deliver the relevant evidence, and re-executes the receiver and affected downstream nodes, producing a candidate 

---

### [140] LLMs as Judges and Examinees for Medical Item Difficulty Prediction

**链接**: https://arxiv.org/abs/2610.38402
**作者**: Xiaomeng Xiong, Marcus Walker, Yanlin Jiang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Predicting medical item difficulty from item text alone remains challenging. Prior work has largely relied on linguistic features or text representations derived from general-purpose and domain-specific language models, but predictive performance has remained modest. This study takes a different approach by using difficulty-related signals that emerge when open-weight large language models (LLMs) interact with test items. Using USMLE and PANCE medical licensure examination items, we examined LLMs in two roles. As judges, the models provided absolute difficulty ratings and pairwise difficulty comparisons. As simulated examinees, they generated response-based signals including correctness, keyed-option probability, response entropy, and the probability margin between the top two options. We then combined the strongest judgment and response signals with baseline item features in downstream prediction models. Pairwise difficulty judgment was the most consistent individual LLM signal across

---

### [141] GARDEN: Generalist Autonomous Reward Design Through Evidence Navigation for Cooperative Multi-Agent Reinforcement Learning

**链接**: https://arxiv.org/abs/2610.37926
**作者**: Dogan Urgun
**来源**: cs.AI cs.MA cs.SY eess.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cooperative multi-agent reinforcement learning (MARL) enables teams of agents, such as robots and autonomous vehicles, to learn coordinated behavior, but what such teams learn is largely determined by their reward function. Because task success alone provides too little guidance for learning, intermediate rewards are usually designed by hand, and this effort must often be repeated whenever the environment or the team changes. Large language models (LLMs) can automate the effort by writing reward functions as code, yet the resulting rewards are typically designed and tested in a single setting. To enable their reuse across settings, GARDEN (Generalist Autonomous Reward Design through Evidence Navigation) is proposed, in which one reward program is developed for a family of related scenarios and transferred, unchanged, to scenarios that were not available during its design. During development, environment code, training records, and agent behavior are investigated by an LLM reward engine

---

### [142] Assessing AI Companion Chatbot Safety for Vulnerable Users: A Crisis-Stage Multi-Platform Evaluation

**链接**: https://arxiv.org/abs/2610.39782
**作者**: Huanyue Liao, Seok Min Lim, Yan Ling Lim, Shi Min Cheng, Kellin Pelrine, Chen Hui Ong
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI companion chatbots are increasingly used by vulnerable individuals, including adolescents in suicidal crisis, for emotional support. Existing safety evaluations focus on base models, leaving gaps in product-level assessment, crisis-stage sensitivity, and comparisons between companion apps and general-purpose LLMs. We introduce MIRROR-Eval (Multi-turn Interaction Risk Review: Observing suicidal-crisis Responses), a dataset of 960 annotated 20-turn conversations across eight deployed platform configurations, six clinically grounded personas, and two crisis stages: ideation and explicit planning. An LLM-as-a-Judge pipeline applies an expert-reviewed rubric covering user risk severity, chatbot risk awareness, and intervention behavior. We observe a three-tier harm structure: companion apps (Character.AI and Replika) and Grok 4.3 form a high-harm tier; Gemini 3.1 Pro is mid-range; GPT-5.5 and Claude Sonnet 5 show substantially lower harm. At planning, companion apps show increased glorif

---

### [143] IndicIPR-QA: A Benchmark for Extractive Question Answering on Indian IPR Laws

**链接**: https://arxiv.org/abs/2610.40518
**作者**: M. Mohaiminul Islam, Muhammad Abulaish
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Legal Question Answering (QA) over statutory texts is a challenging task in Natural Language Processing (NLP), especially in low-resource settings with complex legal systems. It requires answers that are precise and grounded in the law. However, to the best of current knowledge, no existing extractive QA benchmark provides exact answer spans from statutory texts across all seven Indian Intellectual Property Rights (IPR) Acts. This paper presents IndicIPR-QA1, an extractive QA benchmark for Indian IPR laws. The proposed dataset contains 4,462 QA pairs from 1,116 statutory contexts across seven Acts. Questions and answers are generated using GPT-4o and validated through nine automatic quality checks, single and multi-model LLM evaluations, and a 200-pair human audit. Section-level partitioning prevents source-context overlap across the training, validation, and test sets. Further analysis examines answer span length, lexical overlap, and multi-clause structure across the corpus and indiv

---

### [144] GenAI as an 'Invisible Hand' in Opinion Dynamics: Evidence from a Group-Level Simulation Study

**链接**: https://arxiv.org/abs/2610.37689
**作者**: Thomas Grisold and Johannes Schneider
**来源**: cs.SI cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent arguments suggest that genAI can act as an invisible hand that gradually shapes social structures, such as collective beliefs and norms. The argument is that if millions of people repeatedly consult genAI tools, their generated outcomes quietly shape what becomes acceptable, reasonable or conventional. We study this in the context of collective opinion dynamics, i.e., how groups form opinions around controversial dynamics. We present the findings of a simulation including 50,000 group discussions across 50 controversial statements, three LLMs, and different social configurations. We vary two characteristics of LLM interaction-agreeableness and personalization-and compare the influence of genAI in homogeneous and heterogeneous groups. Our findings indicate that profile-specific personalization increases LLM influence when models adopt a non-neutral stance, i.e., when they agree or disagree with the user. Furthermore, we find that neutral LLMs have a stronger effect in homogeneous

---

### [145] Well-Typed ComfyUI Cannot Go Wrong: Gradual Refinement Types for Generative-AI Workflow Graphs

**链接**: https://arxiv.org/abs/2610.37673
**作者**: Pingchuan Ma, Zhantong Xue, Hui Li, Zhaoyu Wang, Yuguang Zhou, Shuai Wang 等 (7 人)
**来源**: cs.PL cs.MM cs.SE
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative-AI workflows are programs assembled from independently developed models and operators. Their correctness depends on relationships among model families, tensor geometry, control modalities, and quantization levels. In ComfyUI, these relationships can be violated even when every connection is accepted by its validator, causing expensive runtime crashes or silent failures. To measure how often such semantic composition failures occur, we classify all 8,766 issues and 1,368 discussion threads of ComfyUI's GitHub repository with an LLM, checked for cross-model agreement. They account for 8\% of issue reports and 21\% of issue-tracker runtime failures, and 32\% of them are silent. Because execution cannot reliably reveal those failures, we present ComfyTy, a gradual refinement type system that checks component compatibility before execution as a compositional property of workflow graphs. Each node declares a reusable schema that states which model families, sizes, modalities, and 

---

### [146] Radiology Guideline-derived Decision Graph for Efficient Clinical Decision Support

**链接**: https://arxiv.org/abs/2610.40327
**作者**: Xuewen Zhou, Zhen Chen
**来源**: cs.CV cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Radiological risk stratification and management planning are essential downstream tasks in medical imaging. Automating these tasks is challenging because clinical guideline criteria are distributed across prose, tables, and cross-referenced definitions. We present Guideline-derived Decision Graph (GDGraph), a framework that decouples guideline compilation from case evaluation. During compilation, a large language model partitions guidelines into section-based chunks, extracts local decision subgraphs with linked definitions, and aggregates related branches into an executable decision graph. During inference, a fast System One model answers localized clinical questions while deterministic traversal resolves Boolean logic, turning opaque single-pass predictions into a traceable decision path without task-specific training. Across 347 cases spanning renal cyst, adnexal mass, and thyroid nodule guidelines, GDGraph improves System One accuracy from 57.3% to 90.8%, outperforming retrieval-au

---

### [147] Judging Before Propagation: Task-Graph Contextual Integrity for Multi-Agent Privacy

**链接**: https://arxiv.org/abs/2610.39532
**作者**: Hengyu Wu, Blaise Delattre, Yang Cao
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent LLM systems increasingly rely on persistent memory and inter-agent communication. These capabilities create privacy risks that extend beyond individual interactions: a release appropriate in isolation may become inappropriate when combined with information previously disclosed to a recipient or propagated to downstream agents along the planned workflow. Existing Contextual Integrity (CI) mechanisms for agentic systems typically rely on local judgments that assess each disclosure in isolation, with or without regard to the recipient's history, but do not account for how information propagates downstream. However, compliance at the current boundary does not guarantee appropriateness across the workflow. We introduce Task-Graph Contextual Integrity (TG-CI), to our knowledge the first task-graph-native formalization of Contextual Integrity for multi-agent systems. TG-CI represents a workflow as a Multi-Agent Task Graph (MATG) and extends CI from atomic transfers to stateful, gr

---

### [148] Benchmarking decision models against generative large language models on medical multiple-choice questions

**链接**: https://arxiv.org/abs/2610.38448
**作者**: Oscar Freyer, Daniel Glauert, Moritz Hofmann, Max Ostermann, Stephen Gilbert, Jakob Nikolas Kather
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical workflows often require selecting among predefined options. We compared 13 decision models with 15 generative large language model configurations, including different reasoning settings, using 1,273 four-option MedQA questions under text-only conditions. Accuracy ranged from 67.71% to 89.08% for decision models and from 78.32% to 96.86% for generative configurations. Among the tested configurations, Mercury Decide had the lowest mean final-attempt cost (USD 0.0069 per 1,000 questions), while Clef Omni had the shortest median request duration (0.291 seconds). Decision-model probabilities distinguished correct from incorrect answers, but error rates among answers assigned probabilities of at least 0.90 ranged from 1.71% to 12.77%. Answer agreement across three runs ranged from 92.30% to 100%, while probability repeatability varied. Decision models offered resource advantages alongside lower peak accuracy; selecting models for medical workflows requires considering probability qua

---

### [149] From Geometry to Behavior: How Instruction Exposure Unlocks Latent Rhetorical Directions in LLMs

**链接**: https://arxiv.org/abs/2610.37685
**作者**: Shengjie Xu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language models do not merely memorize facts; they absorb rhetorical strategies from pretraining data, including the human tendency to reason by analogy. We ask: is this absorbed capability geometrically accessible before any instruction tuning, and what determines whether it can be activated at inference time? We extract an "Analogy Vector" from the residual stream via difference-in-means and show it enables steerable explanation style across seven instruction-tuned models (Gemma-2, Llama-3.1, Qwen-2.5; 2B-32B), improving harmonic mean from 3.22 to 3.94 (+22%) for Gemma-2-9B-IT on 300 held-out test prompts. A small human validation study confirms the LLM judge on Analogy Quality. Our central finding, from seven matched base-instruct pairs, is a gradient of behavioral accessibility: the analogy direction exists in every base model, but its behavioral accessibility under linear intervention scales continuously with instruction exposure during training. Gemma-2 base models (strict pretra

---

### [150] Masked Erosion: How Acceptance Gates Lose Redundant Safeguards in Self-Improving Agents

**链接**: https://arxiv.org/abs/2610.38392
**作者**: Hau-Sing So, Daixian Liu, Weicai Long
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-improving LLM agents edit their own harness, the prompts and rules around a fixed model, and keep an edit only if an acceptance gate scores it higher on a batch of tasks. Such a gate sees what the harness does under the current model, not what it would still prevent if one safeguard failed. When safeguards overlap, deleting one is masked: the others still block the harm, so the gate decides on task success alone and redundancy erodes unseen. We measure harm for every subset of four written safeguards in two agent environments and run 411 improvement loops under ten gate rules, mostly as controlled deletion experiments, plus three runs of the GEPA optimizer. A deletion behind another working safeguard adds almost no observable harm. A paired significance test blocks deletions that pass by chance but not deletions that genuinely raise task success, and a larger evaluation batch lets it delete cheaper safeguards: at the same cost, 20-task batches kept every harness protected while 40

---

### [151] Idea Traces: Threading Accretive Content across Scientific Papers

**链接**: https://arxiv.org/abs/2610.38721
**作者**: Luke S. Snyder and Jeffrey Heer
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce idea traces, a novel thread-based representation of accretive content across scientific papers. Rather than capturing fixed themes from papers, idea traces surface similarities and deltas of faceted content that enable inspection of how ideas relate and evolve across the citation network. To extract traces, we contribute an LLM pipeline that deconstructs salient transitions between pairs of papers and collates the output into an idea dependency graph. We leverage idea traces in a visual system that supports idea-driven navigation starting from a seed paper, lifting the "plane" of synthesis from papers to ideas. To evaluate the usefulness and quality of generated ideas, we provide a case study that compares our approach with an LLM Q&A workflow, and interview 10 researchers who used our system and annotated 110 ideas. Experts found that our approach helped extract a useful space of connections that would have been difficult to make otherwise. Drawing on their feedback, we o

---

### [152] ItemCompass: Real-Time Edge-AI Wearable Vision for Tag-Free Domestic Object Retrieval

**链接**: https://arxiv.org/abs/2610.38629
**作者**: Tsz Lok Cheung, Jeff Kai-Tai Tang, Anthony Kong, Zackary P. T. Sin
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Misplacing household objects disrupts daily routines, especially for elderly users. ItemCompass addresses this with a real-time, tag-free wearable AR system that builds a persistent digital twin of the home for natural language object retrieval. A custom eyewear node streams visual and inertial data to an edge server, where YOLOv11n detection, Siamese re-identification, and a Pedestrian Dead Reckoning engine log object locations as Spatial Anchors in InfluxDB. Voice queries are resolved by a local Faster-Whisper and Qwen2 LLM pipeline, delivering concise spoken and AR guidance on a heads-up display. Evaluation shows 0.40 m localization drift, 97.5% step precision, and mAP@0.5 of 0.874, with users rating Accuracy and Trust at 4.6/5.0. The system highlights always-on sensing, conversational spatial memory, and privacy-by-design for wearable computing.

---

### [153] ARBITRA: Robust Document-Level ATT&CK Extraction via Multi-Expert Argumentation

**链接**: https://arxiv.org/abs/2610.39433
**作者**: Youngjin Jin, Seungwon Shin
**来源**: cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Cyber threat intelligence (CTI) reports describe adversary behavior in natural language, but converting them into structured MITRE ATT&CK mappings remains difficult: existing methods decompose reports to sentence-level granularity for extraction, while modern LLMs can work with full reports in a single pass but with noticeable performance degradation. We present ARBITRA, which orchestrates multiple role-specialized LLM experts that propose candidate ATT&CK entities from the full report, which are then verified through a per-candidate quantitative bipolar argumentation framework (QBAF) grounded in document evidence and rationales. We additionally construct reasoning-specialized corpora for fine-tuning so experts can act as effective participants during this verification process. Across ATT&CK extraction benchmarks, ARBITRA reaches a stronger precision-oriented operating point than sentence-level pipelines, recent LLM-based extraction systems, and frontier models including GPT-5.5. Under

---

### [154] Interpretable Feature Discovery from Unstructured Data Using LLMs and Statistical Choice Models

**链接**: https://arxiv.org/abs/2610.38082
**作者**: Baptiste Arnaudo, Amine Bennouna, S\'ebastien Martin
**来源**: stat.ML cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Feature extraction from unstructured data typically relies on opaque embeddings unsuited to interpretable decision-making. Interpretable features, on the other hand, typically require costly, and often infeasible, hand-engineering. Large language models (LLMs) offer a natural bridge, as they can read raw data and describe it in interpretable terms. One could simply ask an LLM to extract features from a large sample of the dataset, but context limitations and diluted attention can lead to unsatisfactory results. We introduce a method that automatically discovers interpretable, decision-relevant features from unstructured data. Our key idea is to perform pairwise comparisons between items, asking an LLM to articulate, in interpretable terms, the features distinguishing each pair. We treat these explanations, or rationales, as data: we develop a statistical choice model that combines these rationales across the comparisons to identify relevant features and estimate per-item, per-feature s

---

### [155] Only Accepted Tokens Count: An Energy Accounting of Speculative Decoding Under Latency Targets

**链接**: https://arxiv.org/abs/2610.40287
**作者**: Bole Ma, Ayesha Afzal, Jan Eitzinger, Harald Koestler, Gerhard Wellein
**来源**: cs.DC cs.AI cs.LG cs.PF
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model serving is limited by facility power. Energy per token determines how many tokens a datacenter can serve, while a latency target bounds how quickly each user receives them. During decode, every weight is read from memory for every generated token. Batching amortizes this read across users but makes no individual user faster. Speculative decoding does: a drafter proposes several future tokens, and the target model verifies them in a single forward pass that reuses the same weight read. Because every drafted token must be verified whether or not it is accepted, the energy speculation saves depends on how many drafted tokens are accepted. This saving is hard to pin down. It varies across target models from different attention families and across drafting schemes, and it depends on the text being served. Every drafter we evaluate accepts fewer tokens on conversation than on code, and every trained drafter accepts fewer on Romansh, a low-resource language, than on Engli

---

### [156] CAD-WAM: Anticipating Geometry for Text-to-CAD Generation

**链接**: https://arxiv.org/abs/2610.39306
**作者**: Zhengyang Li, Weijie Zheng, Yuxin Cui, Sijie Wang, Wenjie Feng, Qiyu Kang
**来源**: cs.CV cs.GR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generating editable computer-aided design (CAD) models from text requires selecting operations that produce the intended changes to the geometry constructed so far. An incorrect operation can compromise subsequent steps, making reliable multi-step generation challenging. Existing methods based on large language models (LLMs) primarily learn to predict commands, without explicit supervision of the geometric states those commands should produce. Inspired by world-action models, we introduce CAD-WAM, which couples geometry-conditioned action generation with next-state prediction. We define complete modeling operations as actions in a CAD domain-specific language (DSL) and encode surface point clouds of intermediate solids into compact latent states using a pretrained variational autoencoder. An LLM backbone generates the next action from the target description and current geometric state, while an auxiliary head on the same backbone predicts the next state to provide geometric supervision

---

### [157] Compile Away Uncertainty: Self-Evolving Agent Skills via Programmatic Compilation

**链接**: https://arxiv.org/abs/2610.39508
**作者**: Chengyu Yang, Yunxiang Zheng, Zongzheng Li, Jiamei Li, Boxun Lan, Xiaoyu Liu 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Self-evolving agent skills enable AI agents to accumulate and refine reusable procedural knowledge from interaction experience without updating model parameters. However, since such skills are typically represented as textual documents and executed through LLM reasoning, even previously learned procedures must be repeatedly interpreted and regenerated, introducing avoidable uncertainty into every execution. In contrast, program execution is deterministic and independently verifiable. Intuitively, transforming well-specified operations into executable programs can reduce reliance on LLM reasoning and, consequently, reduce execution uncertainty. Motivated by this intuition, we introduce SKillCompiler, a self-evolving skill framework that integrates programmatic compilation into the skill evolution process. Specifically, SkillCompiler adopts an executability-aware skill compilation strategy that decomposes skills into fine-grained operations, analyzes their executability, and constructs h

---

### [158] A Case Study of a Multi-Agent Kernel-Optimization Loop That Learns a New AI Accelerator

**链接**: https://arxiv.org/abs/2610.38329
**作者**: Byonggon Chun
**来源**: cs.LG cs.AI cs.AR cs.PL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Frontier large language models write correct CUDA kernels for most single-operator benchmark tasks, yet their accuracy collapses on accelerators whose architecture and programming language they have rarely seen. We present a case study of an LLM agent loop built for such accelerators. Our example is the FuriosaAI RNGD NPU, programmed in a recent, sparsely documented Rust DSL, where the loop optimized three Gemma-4-12B decode kernels over 12 days on a shared, scarce device. The loop builds its own target knowledge: it writes and checks a summary of the DSL documentation, measures the chip with microbenchmarks, records compiler-derived legality rules, and revisits this knowledge when the toolchain changes, rechecking rules and measurements where it can. A role-based search over per-kernel Design Trees explores whole-kernel designs and accumulates small accepted changes in the best version of each kernel. Because device time is scarce and readings are noisy, cheap checks screen new design

---

### [159] DWISE: Denoising Workload-Informed Scheduling Engine

**链接**: https://arxiv.org/abs/2610.39852
**作者**: Lie Li, Wen Li, Junxiao Shen, Jindong Gu, Guosheng Hu
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Unlike autoregressive large language models (AR-LLMs), diffusion LLMs (dLLMs) generate text by iteratively denoising many tokens in parallel, offering a promising path to efficient inference. Existing serving frameworks, however, schedule dLLM requests with policies designed for AR models, namely first-come-first-served (FCFS) admission and prefill priority. We find that both policies are ill-suited to dLLMs, wasting much of their speed. FCFS ignores that a dLLM request's decoding cost is highly heterogeneous and unknown at arrival, causing severe head-of-line blocking. Prefill priority, widely used in AR-LLM serving to keep time-to-first-token low, sharply cuts dLLM efficiency, as rounds that run only prompts leave most of the batch idle. We present DWISE, a Denoising Workload-Informed Scheduling Engine for efficient dLLM serving. DWISE schedules requests by their remaining work, measured in a block-level unit shared by prefill and denoising, so both phases share a round. To predict t

---

### [160] Goal-Aware Dynamic Multi-Agent Collaboration for Long-Horizon Tasks

**链接**: https://arxiv.org/abs/2610.39193
**作者**: Xu Shen, Lingyong Yan, Shuaiqiang Wang, Jianmin Wu, Zhikai Chen, Jiliang Tang 等 (7 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents are increasingly used to complete complex, long-horizon tasks without human intervention. To make progress toward the task goal, agents need to perform different duties, such as planning and verification, when needed. To understand how single agents manage these duties during long-horizon execution, we conduct a preliminary study. Our analysis shows that verification has the strongest association with task success, but often occurs late, leaving limited opportunities for correction. We also find that the proportion of duty-relevant information decreases as records from different duties accumulate in a shared context. These findings lead us to examine whether multi-agent systems (MAS) can address these problems by assigning duties to agents with separate contexts. Our analysis shows that this separation alone is insufficient. Agents can lose track of the overall goal and repeat prior investigations. They may also lack necessary background while receiving irrelevant info

---

### [161] Value Probes: Learned Value Functions for Beam-Search Red Teaming

**链接**: https://arxiv.org/abs/2610.38526
**作者**: Jonathan F. Jao, Andrew Kyle Lampinen
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Automated red-team auditing of language models is an important way to evaluate safety-relevant behaviors. These audits implicitly search a tree of possible conversation pathways: at each turn an auditor model decides which conversation to continue, and an LLM judge scores the dialogue. We emphasize that this auditing procedure is a Markov decision process, where states are the conversation history, actions are candidate responses, and rewards are judge scores for the target behavior. By adopting this perspective, we introduce two major improvements to auditing. First, we propose adopting beam search for the audit rather than relying on the auditor alone. We then interpret the problem of finding states that are likely to lead to problematic behavior as value estimation. Surprisingly, we show that this value function can be estimated by linear probing from the target model's activations to predict discounted future rewards - a method we term "Value Probes." By using Value Probes as a heu

---

### [162] El Agente Quntur: Agentic Active-Space Selection for CASSCF

**链接**: https://arxiv.org/abs/2610.38145
**作者**: Juan B. P\'erez-S\'anchez, Viviana Roman-Ventura, Olalla Nieto-Faza, Aiwei Yin, Al\'an Aspuru-Guzik, and Varinia Bernales
**来源**: physics.chem-ph cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multireference calculations often require substantial human expertise and time to choose and refine an active space for the electronic states or chemical process of interest. This involves selecting which orbitals to include, verifying that the calculation describes the intended excited state, and deciding whether the results have converged. Here, we ask whether scientific agentic systems (harnesses) can make these decisions reliably. We use the El Agente Quntur multi-agent harness, with GPT-5.6 Sol and GPT-5.6 Terra as the underlying LLM components, to explore 32 diverse singlet excitations at fixed molecular geometries. The agents planned and executed calculations, choosing and refining active spaces under prompts that specified equal-weight two-singlet state-averaged CASSCF followed by strongly contracted NEVPT2 with def2-TZVPD. We evaluate excitation energies against published CASPT2 reference values at matching geometries and compare performance with six deterministic Active Space

---

### [163] AI Cosmos: An Agentic Infra for Situated Learning

**链接**: https://arxiv.org/abs/2610.40031
**作者**: AI Cosmos Team, Jinfeng Zhou, Yuxuan Chen, Fangming Chang, Mingyu Su, Yifan Zhu 等 (10 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) can improve task performance during learning, yet these gains do not necessarily reflect learners' ability to thereafter apply the knowledge and skills independently. We present AI Cosmos, an agentic infrastructure for situated learning that organizes learning around two complementary principles: scenario-based participation and cumulative assets of practice. AI Cosmos organizes learners and role-specialized agents within learning scenarios that integrate task-relevant knowledge and, when needed, executable workbenches. An asset-memory loop preserves the processes and outcomes of practice as reusable assets with explicit provenance and dependencies. We evaluate scenario-based interaction through two preregistered randomized controlled studies examining the acquisition of legal reasoning and programming competence, holding the same underlying LLM across conditions. AI Cosmos achieves greater learning gains than a conventional LLM in legal reasoning and highe

---

### [164] Beyond Selected Breakthroughs: Evaluating Language Models on Randomly Sampled Mathematical Conjectures

**链接**: https://arxiv.org/abs/2610.40382
**作者**: Helen Jenne, Davis Brown, Jesse He and Henry Kvinge
**来源**: cs.AI math.HO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The last year has seen a shift in AI-assisted mathematics, with frontier language models producing proofs of and counterexamples to long-standing open conjectures. However, studying only the current set of major breakthroughs provides an incomplete picture of LLM capabilities and the computational resources needed to achieve reported results. To address this, we introduce a new dataset, OpenConjecture, which collects conjectures from mathematics papers published on the arXiv since February 2026. We use these conjectures as a source of open mathematical problems, and apply frontier GPT models to a random sample of 200 of these conjectures over three passes using a reproducible protocol without problem-specific mathematical guidance. Rather than attempt expert verification of these candidate solutions, we analyze the types of problems for which LLMs produce solutions and the characteristics of these solutions. The models we test produce candidate solutions for roughly 60% of the conjectu

---

### [165] Well-Specified and Well-Tested? Assessing SWE-bench-Style Datasets with a Self-Evolving Agent

**链接**: https://arxiv.org/abs/2610.39417
**作者**: Zhonghao Jiang, Xuyang Zheng, Yanfu Yan, Zhongxin Liu, Lingfeng Bao, Shuiguang Deng
**来源**: cs.SE cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have shown strong performance on software engineering (SE) tasks, driving the need for high-quality datasets for reliable training and evaluation. SWE-bench-style datasets (SWE datasets) are widely used to evaluate LLM-based coding agents on real-world software issues, where task clarity and test coverage directly affect whether instances are solvable and verifiable. However, quality issues persist in existing SWE datasets, and manual annotation is costly and labor-intensive, motivating LLM-based annotation. Existing approaches typically rely on static, overly general rubrics, limiting their ability to handle diverse and nuanced scenarios and often yielding high false positive rates. In contrast, human annotators draw on accumulated experience to make context-aware judgments. Inspired by this, we propose ExLabel, an LLM-based, self-evolving, experience-guided assistant for task clarity and test coverage assessment in SWE datasets. ExLabel maintains an evolv

---

### [166] Hidden Commitment: When Language Models Silently Pick a Side and How Steering Can Surface It

**链接**: https://arxiv.org/abs/2610.38296
**作者**: Samuel Dawit Assefa and Jae Won Cho
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language-model answers are often treated as a visible record of the internal decision that produced them. We test this assumption in conflicting-context question answering, where two supplied documents support incompatible answers. A model can process the disagreement and still return a one-sided answer, even under prompts that ask it to disclose conflict. In Qwen 0.8B, hidden source commitment is captured by a residual source-choice direction whose sign tracks which document the answer uses. Sparse middle-layer MLP writers feed the same coordinate, and steering the coordinate changes the chosen source. A transfer run on Gemma 3 1B preserves the source-choice readout and sparse-write bridge under LLM-audited labels. Conflict disclosure follows a different pattern, appearing weaker, later-layer, and only partially steerable. These results support a practical monitoring strategy for retrieval systems that detects silent source commitment with residual readouts and pairs conflict-surfacin

---

### [167] Predict the Reward, Not the World: World Reward Models for ML Agents

**链接**: https://arxiv.org/abs/2610.38439
**作者**: Yuxiao Lee, Zherui Yang, Fan Liu, Hao Liu
**来源**: cs.AI cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Search-based machine-learning (ML) agents improve a solution by writing candidate programs, executing them, and keeping the best. Execution gives the search reliable feedback, but a single run can take hours, and most runs end in programs the agent discards. Recent agents try to save these runs by letting a large language model act as a world model that predicts how each program would perform. However, a wrong prediction feeds the search false information. We argue that an agent does not need to predict the outcome of execution, only the decision that execution would support. We propose World Reward Models (WRMs), which learn from real execution results to choose directly which candidate will perform better, without predicting any intermediate outcome. We prove that a selector which predicts execution from the same inputs cannot outperform the best direct selector, that predicted outcomes add an error which can make a likelihood-trained world model prefer the worse program on every ins

---

### [168] AtomTree: A Hierarchical Framework for State-Aware Embodied Instruction Following with LLMs

**链接**: https://arxiv.org/abs/2610.38744
**作者**: Haotian Zhai, Tianming Sha, Junnan Li
**来源**: cs.RO cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Embodied instruction following in interactive environments requires agents to interpret natural language commands and complete long-horizon tasks. Existing planners either rely on large labeled trajectories, or use few-shot and zero-shot LLM prompting that produces a whole plan in a single serial reasoning process. These approaches depend on linguistic common sense, commit to a plan from the initial instruction, and only update after failures, which weakens robustness and state awareness. We present AtomTree, a hierarchical framework for state-aware task planning with LLMs. AtomTree incrementally builds a tree of subgoals and actions, where the LLM decides at each step, from the current symbolic state, whether to further decompose or to output a grounded low-level action. A lightweight memory module summarizes past outcomes for reuse in later decisions. When a low-level action stalls, AtomTree triggers hierarchical backtracking replanning to return to the parent node and regenerate the

---

### [169] Selective and Hybrid-State Communication for Latent Multi-Agent Systems

**链接**: https://arxiv.org/abs/2610.37779
**作者**: Miles Liao, Aaron Smieszek, Yuhao Ge
**来源**: cs.MA cs.LG
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Efficient communication remains a major bottleneck in large language model multiagent systems. Latent communication reduces repeated natural-language exchange by transferring internal model states between agents, but these transfers remain costly and are typically designed around conventional KV-cache representations. We address this problem from two complementary perspectives. We introduce SelectKV, a boundary-aware method that selectively communicates KV states while protecting inherited context, and HyLaMAS, which extends latent collaboration to hybrid linear-attention models by communicating both KV caches and recurrent states through a shared workspace. Across six benchmarks, SelectKV reduces communicated KV positions and logical KV payload by 9.7-9.9%, with accuracy unchanged on two benchmarks, within one percentage point on three, and six points lower on HumanEval+. Across Qwen3.5 model scales, HyLaMAS reduces decoded output tokens by 53-80% and achieves 1.16-2.78x speedups rela

---

### [170] Beyond fabrication: Misattributed numbers in papers written by AI research agents

**链接**: https://arxiv.org/abs/2610.38691
**作者**: Mosab Alfaqeeh, Omar Hourani, Muath Hourani, Hashem Alfaqeeh
**来源**: cs.AI cs.CL cs.DL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Verifying numerical claims in research written by AI agents is an important but challenging problem. Recent benchmarks show that many agent-written papers fail integrity checks, but such verdicts, often produced by a single LLM judge, identify failure without explaining its nature, and existing checks either test a paper for internal consistency or test whether a reported value appears somewhere in an agent's output. We re-analyze all 540 released judgments from a recent public benchmark of AI research agents (nine agents, fifteen open research problems) and manually label 256 numerical claims from 18 submissions. Failures concentrate on alignment between the paper and the underlying work rather than overt cheating, and about four in five unsupported claims correspond to values in the agent's own files that come from the wrong experiment, metric, or run. We introduce a deterministic claim-to-evidence checker that scores whether the surrounding context identifies the claimed result and 

---

### [171] EvoTeam: Multi-Agent Collaboration via Evolving Teams

**链接**: https://arxiv.org/abs/2610.39813
**作者**: Qinuo Cao, Xin He, Dianxuan Fu, Lizhi Zhang, Zhaoqing Xing, Jiapu Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems (MAS) rely on collaboration among specialized agents to solve complex tasks. Existing methods improve MAS by refining the prompts, skills, and execution strategies of individual agents based on task feedback. However, improving individual agents does not necessarily lead to better team collaboration. Recent studies have therefore extended evolution to the collaboration level, using collective execution experience to adjust team organization, and inter-agent interactions. Nevertheless, evolving collaboration across heterogeneous tasks remains challenging, as existing approaches often constrain team reorganization within a shared structure and reuse interaction rules across incompatible team contexts. In this paper, we propose EvoTeam, a collaboration-centric evolution framework that jointly evolves team organization, interaction rules, and individual agent skills through execution experience. It maintains a library of reusable teams, selecting or creating a

---

### [172] Cross- Model Reliability and Predictive Uncertainty in Sentiment Analysis of Tweets Related to the 2023 Türkiye–Syria Earthquakes

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11727972/&hl=zh-CN&sa=X&d=4831552020717571284&ei=oRXkau6XOMyp6rQP4ry-yQI&scisig=AIL1Nv5i-5LWqRQ5FoCUf2mlikbm&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIL1Nv6nI2XU9qk0OzeW89wx4dKt&html=&pos=3&folt=kw-top
**作者**: B Kaysi - 2026 10th International Artificial Intelligence and Data …, 2026
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Fleiss’ kappa and Krippendorff’s alpha were both 0.590, indicating moderate multi - model … - language filter. Reproducible pretrained sentiment classifiers may also be compared with controlled prompted large language model baselines, provided that

---

### [173] Emergence, Asymmetry, and Value in AI Networks: An Anoptical Perspective

**链接**: https://arxiv.org/abs/2610.37672
**作者**: Olivier Auber
**来源**: physics.soc-ph cs.CY cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This chapter presents exploratory experiments suggesting that asymmetry and functional value hierarchy emerge among LLM-based agents sharing the same context, although they are equivalent and interact within a symmetric network. We use the Poietic Generator, a "no-goal" multi-agent environment with a shared real-time space, a symmetric topology, and no imposed objectives. First tested with humans, it has hosted since 2024 multimodal LLM agents that observe the global image they co-construct and act locally. We ran four phases. Unconstrained, agents spend tokens freely to invent forms that distinguish them individually rather than serve collective emergence. We then introduced bounded rationality, Dessalles's Simplicity Theory (maximizing unexpectedness), and Friston's Free Energy Principle (minimizing prediction error), and observed collective coherence emerge. Early signs of attentional stratification appear under bounded rationality alone; once prediction accuracy is made mutually vi

---

### [174] Exploring AI Peer in Collaborative Mathematics Learning

**链接**: https://arxiv.org/abs/2610.38990
**作者**: Yiran Lin, Ye Deng, Ziqi Pan, Yongan Yu, Alexandra I. Cristea
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence (AI) agents are increasingly explored as collaborative learning partners in mathematics education, yet it remains unclear what makes an AI recognizable as a peer. This study examines how domain experts perceive and interact with an adaptive LLM-based peer agent combining a Big Five-informed persona with motivational state modulation for collaborative mathematics problem solving. Through thematic analysis of expert interviews, we identify conditions shaping peer perceptions, including emotional safety, shared control, and collaborative reasoning. Participants primarily judged the AI through its social behavior rather than mathematical capabilities. The AI was perceived more as a peer when it created a non-judgmental space, engaged in tentative reasoning, displayed appropriate imperfection, and respected participants' pace. Conversely, blind agreement and over-instruction reduced trust and shifted perceptions toward a tutor role. Based on these findings, we propos

---

### [175] ScienceJudge: Pattern Perturbation Augmentation for Sentence-Level Scientific Claim Verification

**链接**: https://arxiv.org/abs/2610.40238
**作者**: Chuhai Cai, Xin Chen, Min Yang, Feng Jiang
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Sentence-level scientific claim verification determines whether each sentence in an AI-generated scientific paragraph is supported by a given multimodal evidence bundle. Fine-grained reporting errors often preserve fluent and plausible statements while introducing subtle evidence-claim deviations, making them difficult to detect under sparse and imbalanced supervision. We propose Pattern Perturbation Augmentation (PPA), which models reporting errors as label-specific faithfulness breaking transformations and induces reusable error patterns from labeled examples. PPA applies these patterns to supported claims to construct controlled hard negatives and expands their coverage through pattern-level, operation-level, and cross-domain augmentation. Based on these augmented views, we develop ScienceJudge, which integrates PPA-trained vision-language predictors and instruction-guided LLM predictors through class-weighted ensemble inference. On the local development set, ScienceJudge improves t

---

### [176] Understanding Large Language Models as Numerical Optimizers

**链接**: https://arxiv.org/abs/2610.37932
**作者**: Lingyun Guo and Ali Bereyhi
**来源**: cs.AI cs.LG eess.SP
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) have emerged as potential tools for numerical optimization. Despite promising results, their intrinsic optimization capabilities and limitations remain poorly understood, particularly in high dimensions. This paper investigates the ability of LLMs to exploit mathematical problem structures and generate feasible, near-optimal solutions. We develop an evaluation framework that distinguishes solution quality from execution failures, including numerical inaccuracies, constraint violations, and output-format errors. Using representative problems from convex optimization, fractional programming, and constrained projection, we assess LLM performance against deterministic reference solvers across different dimensions. Our results reveal that LLMs can capture useful optimization structures and produce near-optimal solutions, even when their outputs fail to satisfy numerical or formatting requirements. However, reliability deteriorates with increasing problem dimensi

---

### [177] Context Compaction for World Models

**链接**: https://arxiv.org/abs/2610.38980
**作者**: Hayder Tirmazi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> World models let observers explore and interact with generated worlds. Recent work shows that when observers revisit a region, current models often fail to regenerate it consistently. We view this as a context retrieval problem. LLM agents manage context retrieval at two layers of their stack. At the model layer, the KV cache design determines how much context fits in memory. At the agent harness layer, harnesses such as Claude Code pick the context sent to the LLM. Prior work on world models has mostly focused only on the model layer. In this paper, we make three contributions. First, we build a benchmark to measure world model context retrieval. It generates new worlds for every episode, preventing a model from recalling rooms using training data. It also separates context retrieval from guesses based on nearby frames. Second, we build an agent harness that performs context compaction for world models, which to our knowledge no prior work has studied. Third, we use our benchmark to s

---

### [178] Scan Before You Install: Detecting and Mitigating Local and Composite Vulnerabilities in Skills

**链接**: https://arxiv.org/abs/2610.37901
**作者**: Parth A. Gandhi, Avital Aviv, Prasanna N. Wudali, Yuval Elovici, Asaf Shabtai
**来源**: cs.CR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An agent skill packages natural-language instructions, scripts, and reference files that an LLM-based agent loads for a task. Skills may access the file system, shell, and network under user-authorized permissions; weaknesses can lead to unsafe execution. Existing scanners primarily target malicious skills, not unintended vulnerabilities in public repositories, and analyze skills in isolation, overlooking multi-skill interactions. To address these gaps, we developed a six-module scanner: Content Extraction, Local Analysis, Composite Analysis, Validation, Reporting, and Mitigation. Local Analysis detects unintended vulnerabilities in benign skills. On a 556-case leaderboard subset of SkillTrustBench, it achieved 95.90% recall with a 4.22% false positive rate; on a balanced sample of 1,000 MalSkillBench skills, its F1 was 0.947, outperforming Cisco's Skill Scanner, NVIDIA's SkillSpector, AgentSkillsScanner, and SkillSieve. In 1,587 skills from the 75 most-starred GitHub repositories, thr

---

### [179] ATLAS-Bench: An Agentic Tool-Use Benchmark for Local Area Search

**链接**: https://arxiv.org/abs/2610.39438
**作者**: Keyun Zhang, Dapeng Yin, Fanfu Wang, Shuang Lang, Zhenyu Zhu, Yulin Huang 等 (8 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable local search is essential for LLM agents to support everyday decisions and longer plans by finding places that meet users' needs at given times and locations. Yet existing benchmarks provide limited coverage of whether search results satisfy mandatory requirements, account for preferences, and ground factual and experiential judgments in place attributes and reviews. We introduce ATLAS-Bench, a benchmark of 1,200 queries across three regions, expanded from real search events using place attributes, reviews, and existing user profiles from the platform. Each query distinguishes mandatory requirements from preferences and factual conditions from subjective judgments, with supporting evidence and criteria for checking each requirement. Queries are validated through iterative assertion checks and cross-model review. We also introduce ATLASBox, a standardized evaluation environment with search tools and a fixed point-of-interest (POI) knowledge base. Given a query, timestamp, and l

---

### [180] What Makes Medical Examination Items Difficult? Using Large Language Models to Explore Patterns Associated With Empirical Item Difficulty

**链接**: https://arxiv.org/abs/2610.39373
**作者**: Xiaomeng Xiong, Marcus Walker, Yanlin Jiang
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Research on medical item difficulty has largely focused on prediction rather than on identifying interpretable patterns associated with empirical difficulty. This study used empirical difficulty labels to guide large language models (LLMs) in inducing difficulty rubrics and examined how rubric guidance affected LLM difficulty judgments. Using training items and their empirical difficulty estimates from the United States Medical Licensing Examination (USMLE) and the Physician Assistant National Certifying Examination (PANCE), Claude Opus 5 induced separate rubrics for absolute and pairwise difficulty judgment. None of the induced rubrics treated surface features, such as stem length, option count, or images, as major sources of difficulty. Several patterns emerged across both examinations, including cue convergence, misleading cues, and option competition, although their specific forms differed. Retrieval of knowledge that could not be derived from the stem was particularly prominent in

---

### [181] An Introduction to Large Language Models for Scientists and Professionals

**链接**: https://arxiv.org/abs/2610.37684
**作者**: Umberto Michelucci
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have rapidly become important tools for science, education, medicine, and professional work. Despite their apparent simplicity from the user's perspective, effective and responsible use requires an understanding of how these systems work, what their limitations are, and how their outputs should be evaluated. I wrote this document as a basis for my lecture on LLM in the master in artificial intelligence in medicine at the university of Turin, Italy. This book provides a practical and accessible introduction to LLMs for scientists and professionals. It explains the fundamental ideas behind tokenisation, embeddings, training, inference, context windows, prompting, and instruction hierarchies, while deliberately avoiding mathematical detail. Particular attention is given to the limitations of LLM-generated answers, including hallucinations, uncertainty, reproducibility, bias, and the need for systematic verification and human oversight. The book also discusses 

---

### [182] Statutory Article Retrieval from Arabic Judicial Narratives: Family Law and Law of Evidence in Saudi Arabia

**链接**: https://arxiv.org/abs/2610.38336
**作者**: Zarah Shibli, Areej Alhothali, Lulwah Alharigy
**来源**: cs.CL cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Reliable legal information retrieval must ground legal reasoning in authoritative statutory sources. In Arabic judicial settings, long factual narratives must be mapped to concise articles that express abstract legal rules, creating a narrative-to-legal-rule abstraction gap. Using a benchmark of 200 synthetic Saudi Arabic judicial cases and 381 articles from the Family Law and the Law of Evidence, we compare word-level and char-4 BM25, zero-shot dense encoders, per-law retrieval, dense-sparse reciprocal rank fusion (RRF), and a proposed Decompose-and-Refine (DaR) pipeline. In DaR, a large language model splits each narrative into disputed legal issues and generates, for each issue, three retrieval channels: a statute-style paraphrase, legal keywords, and a candidate taxonomy chapter. On the whole corpus, the instructed Qwen3-Embedding-8B dense encoder reaches an MRR@10 of 0.849, the best result of any non-decomposed system. Under per-law scoring, this advantage reflects Family Law only

---

### [183] Who Else Is In? Multi-Agent Collusion Initation Via Strategic Vagueness

**链接**: https://arxiv.org/abs/2610.37984
**作者**: Pramod Kaushik, Sarath Sivaprasad, Laura Ferrarotti, Mario Fritz, Samuel F. Brown, Bruno Lepri 等 (7 人)
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi agent LLM systems raise the risk of collusion among agents pursuing objectives hidden from their overseers. When potential partners identities are unknown, collusion first requires initiation: agents must discover one another, often through a public channel observed by ordinary agents and monitors. Strategic vagueness offers a way to navigate this mixed audience, conveying intent to a prospective partner while preserving a plausible ordinary interpretation. We introduce a mutual identification game in which two schemers must identify each other through public interaction, while jointly solving an ordinary task. We find that some models discover successful handshake strategies without explicit signalling guidance, using task compatible exchanges that monitors often fail to flag at low false positive rates. To characterize the communicative capabilities underlying these exchanges, we study a controlled coordination setting. We find an asymmetric response to message explicitness: as

---

### [184] Is it my preference? Role Grounding Attack against Agent's Memory via Social Interaction

**链接**: https://arxiv.org/abs/2610.38209
**作者**: Haoran Bu, Yiting Shen, Litian Zhang, Ruihan Hu, Xi Zhang
**来源**: cs.CR cs.AI cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based agents now share experiences on social platforms and remember new preferences to enhance their performance. However, existing memory systems contain a vulnerability in role-to-principal attribution that attackers can exploit. We identify Role Grounding Misattribution, in which an attacker-designed interaction causes the victim agent to incorrectly record a preference from the attacker as a preference of the victim's user. Specifically, we are the first to formalize Role Grounding Attack (RGA), an attack model that exploits this vulnerability through nested conversation structures. In the memory formation stage, an experience-sharing post quoting a conversation between the attacker agent and its user is published, which explicitly identifies its publisher. The inner conversation expresses preferences from the user of the attacker agent. When the victim agent remembers preferences from this nested structure, its memory loses the context binding and grounds the attacker's prefer

---

### [185] Routed Continual Learning

**链接**: https://arxiv.org/abs/2610.38796
**作者**: Michael Philip, Mahesh Balakrishnan, David Geraghty, David Mao, Vidhya Venkat, Ilya Mironov
**来源**: cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agents deployed at scale repeatedly encounter related problems, and it is natural to let them learn from each other's experience rather than starting over each time. Unfortunately, there is no single way to retain that experience that works well across settings, and no way to know in advance which future problems a given experience will help with. A global history preserves every detail but becomes expensive and mixes together experience that may not belong together; compressing that history into one fixed representation limits the cost but can throw away valuable details. We introduce Routed Continual Learning (Routed CL), an architecture that decides how to partition and retain experience. Past trajectories are grouped into clusters, each of which maintains state using one memory system from a fixed library. Before each run, an LLM-based router either reuses an existing cluster or creates a new one, basing its decision on the problem statement, memory system descriptions, and cluster

---

### [186] Evaluating Conversational Explainability in Healthcare: Comparing the Explainability Assistant and a Traditional XAI Dashboard

**链接**: https://arxiv.org/abs/2610.39634
**作者**: Eduard Barbu, Rodion Krjut\v{s}kov, Anneli Uusk\"ula
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversational interfaces may make explainable AI (XAI) more accessible to users without machine learning expertise, but their benefits over dashboards remain insufficiently characterised in healthcare. Existing systems have typically been evaluated in isolation, leaving unclear whether conversational interaction improves interpretability beyond the underlying explanation methods. We report a within-subjects user study comparing the Explainability Assistant, an LLM function-calling conversational XAI system, with a traditional dashboard for explaining a heart disease classification model trained on the Cleveland Heart Disease dataset. Both interfaces expose the same Decision Tree classifier and post-hoc explanation methods: SHAP feature attribution, DiCE counterfactuals, and what-if analysis. This design supports comparison of interaction modalities while holding the model and explanation methods constant. Five participants with healthcare backgrounds, from medical students to practisi

---

### [187] Can AI Agents Interface Clinicians and Complex Models?

**链接**: https://arxiv.org/abs/2610.39681
**作者**: Giulio Colombini, Matteo Falcioni, Mario Massimo, Francesco Durazzi, Marianna Santoro, Paolo Tubertini 等 (8 人)
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Contemporary healthcare institutions generate daily very large amounts of data, which contain highly useful information for the improvement of work organization, planning and overall efficiency. While models and techniques to extract these insights are well known and constantly developed in mathematical biology, complex systems physics and data science, the adoption of these techniques among Clinicians and Hospital Administrators remains limited, mainly due to language and methodological divides. Objective: In this article we implement an AI Multi Agent System (MAS) that allows Users to use predictive models and make statistical analyses via natural language conversations. Methods: We developed EpidemIA, a training-free MAS endowed with a modular suite of epidemiological models written by human experts, executable on a single-GPU workstation. To avoid relaying sensitive data to third parties, the system uses locally an open-weights LLM as backbone for its two subagents. Res

---

### [188] Merge and Branch: Efficient Tree-Structured Supervised Fine-Tuning of LLMs for Recommendation

**链接**: https://arxiv.org/abs/2610.37973
**作者**: Yunqin Zhu, Yao Xie
**来源**: cs.IR cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based generative recommendation reads long, text-rich interaction histories but generates only short semantic identifiers (SIDs). This asymmetry makes supervised fine-tuning inefficient: encoding the history is expensive, yet each history usually provides supervision for only one target. We present Merge and Branch (M&B) to reduce input cost and learn more from each encoded history. Merge compresses each historical item's SID and text into a small number of learned tokens. Branch uses the compressed history to predict multiple target SIDs. To share history computation while keeping these targets independent, M&B organizes each example as a shallow, wide tree. We develop tree FlashAttention to execute this layout efficiently, processing the shared history once and propagating gradients from every branch for end-to-end training. A tree-structured key/value cache extends history sharing to constrained decoding. Experiments on public benchmarks show that M&B outperforms strong recommen

---

### [189] OneEEG: A Unified Signal-Visual Multimodal Language Model with Task-Aware Mixture of Projectors for Multi-Task EEG Understanding

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.35355&hl=zh-CN&sa=X&d=13895755145137239713&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv5PSvYqaU2uRPrBLGIf58Nh&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=9&folt=kw-top
**作者**: J Zhang, X Zhang, X Lu, S Cai, H Li - arXiv preprint arXiv:2610.35355, 2026
**匹配关键词**: EEG, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> In parallel, we establish OneEEG-Bench, an EEG- MLLM benchmark for systematically assessing EEG understanding in multimodal language models. … • We propose OneEEG, a unified EEG- MLLM framework that supports both numerical

---

### [190] PathKGen: Pathology Knowledge Assisted MLLM for Explainable Histopathology

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2610.33691&hl=zh-CN&sa=X&d=11204144170889706755&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv6omaB6f2aODDrfUTTGBEKJ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=1&folt=kw-top
**作者**: N Rajapaksha, S Herath, D Wijesinghe… - arXiv preprint arXiv …, 2026
**匹配关键词**: Foundation Models, MLLM
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> We introduce PathKGen, a knowledge graph-assisted MLLM for histopathology report generation. PathKGen has two main branches: (1) a visual path that learns visual token inputs to the MLLM using pathology foundation models, and (2) a

---

### [191] Raincheck: Deferred Multimodal Prefill for Efficient Multi-Turn MLLM Inference

**链接**: https://arxiv.org/abs/2610.39562
**作者**: Wenjie Huang, Jun Zhang, Hongyaoxing Gu, Haoyang Huang, Tianqi Xu, Xinyue Hao 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-turn conversations with multimodal large language models (MLLMs) reuse input context, but long multimodal inputs increase time to first token (TTFT). Query-aware hard pruning reduces prefill tokens but permanently excludes information that later questions may require. We propose Raincheck, a framework for deferred multimodal prefill that decouples initial token selection from later information availability. An existing pruning method selects tokens for initial prefill; Raincheck preserves and progressively prefills unselected tokens in source order using unused compute capacity during decode. Unfinished prefill continues after answer return during available scheduling gaps. Attention visibility control and affine state mapping enable context updates after generation begins in full-attention and hybrid recurrent models. Prefill-decode fusion reduces repeated weight reads. We evaluate Qwen3-VL-8B and Qwen3.5-9B with 30% initial multimodal-token retention. Across both models and fou

---

### [192] InteractiveWorld: A Verifiable Human-Centric Environment for Building Better Interactive MLLM Assistants

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.33966&hl=zh-CN&sa=X&d=12445982692769358198&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv5AWXfmYZi-RPkm6DZ3q_d3&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=0&folt=kw-top
**作者**: Q Wang, W Wen, C Zhou, S Suri, Z Liu, L Wu 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Overall, our work offers a verifiable platform and a rigorous evaluation set, laying a solid foundation for research on interactive MLLM … -language guidance; (2) a Human agent, driven by an MLLM , that interprets the guidance based on its

---

### [193] Mind The Gap (MTG-AD): Dataset and Fine-grained Evaluation for End-to-End Inline Audio Descriptions

**链接**: https://arxiv.org/abs/2610.39955
**作者**: Subhashini Venugopalan, Jenny Tan, Taylor Roper, Jimmy Tobin, Anton Kast, Alicia Martin 等 (8 人)
**来源**: cs.CV cs.AI cs.HC
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Audio descriptions (AD) are essential for making visual media accessible to blind and low-vision (BLV) users. While Multimodal Large Language Models (MLLMs) offer a scalable solution for generating audio descriptions on-demand, their performance on ``inline'' audio descriptions -- which must fit within existing silences in a video -- remains under-explored, particularly for diverse user-generated content (UGC). We present a comprehensive investigation into MLLM-generated inline audio descriptions. First, we introduce MTG-AD, a professionally annotated dataset of 36 hours of videos, each averaging $\sim$5 mins. and 8k+ descriptions in total, co-created by paired blind and sighted AD professionals to provide a high-quality benchmark for this task. Second, we propose MTG-AD-Eval, an evaluation framework based on audio description expert guidelines that provides fine-grained, reference-free actionable metrics for model improvement. Crucially, our framework evaluates the end-to-end task: it

---

### [194] Aerial-R1: Reinforcing Aerial Reasoning and Segmentation in MLLMs

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.33056&hl=zh-CN&sa=X&d=5207899985040546445&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv5s6H3nbFMPHDXQkwShiJ7n&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=6&folt=kw-top
**作者**: J Dang, H Peng, Y Wang, K Wang, Z Li, TS Chua - arXiv preprint arXiv:2610.33056 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In this paper, we present Aerial-R1, the first aerial MLLM framework to reinforce visual reasoning capabilities for aerial reasoning and … Extensive experiments on VSAI-Ref, the first aerial MLLM benchmark dedicated to jointly evaluating dense

---

### [195] CoKe-CLIP: mitigating semantic drift via consistency optimization and knowledge-enhanced action representation

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s11760-026-05805-5&hl=zh-CN&sa=X&d=5629117274329754362&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv6oGvG08ySk6_mnWkscjtAY&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=5&folt=kw-top
**作者**: Y Ou, B Hu, Y Wu, R He - Signal, Image and Video Processing, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We propose CoKe-CLIP, a knowledge-enhanced framework that separately encodes category labels and MLLM -generated frame descriptions, extracts complementary RGB and edge representations, and uses edge–knowledge

---

### [196] Embedding semantic and relation priors with MLLMs for visual place recognition

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0925231226028857&hl=zh-CN&sa=X&d=5150514176986840225&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv519n-Pz2vHZWX2arvt1TBF&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=2&folt=kw-top
**作者**: Y Zhang, W Zuo, P Liu, Z Liu - Neurocomputing, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> a novel framework that explicitly embeds MLLM -derived semantic and relation priors into visual features. Specifically, we design a two-stage semantic purification mechanism that proactively eliminates dynamic noise at the source. Under this

---

### [197] Detecting Fine-Grained Differences between Image Datasets

**链接**: https://arxiv.org/abs/2610.38547
**作者**: Leander Girrbach and Alexander von Recum and Kirill Bykov and Zeynep Akata
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting whether and in particular how two data distributions differ is a fundamental statistical problem. For example, we might be interested in which concepts (expressed in natural language) differ between two classes, the outputs of different generative models, or the same model with different prompt specifications. When working with large and complex image datasets, we intuitively think that first selecting concepts from a broad list using fine-grained patch embeddings, and then optimizing the concepts to better fit the data is an effective workflow. However, prior work instead uses MLLMs to propose concepts and image-level embeddings to select them. Therefore, we systematically compare these techniques and find that selecting concepts from broad lists can replace MLLM-proposals at obviously lower cost. MLLM inference can then be spent on optimizing selected concepts instead to achieve substantial improvements. Additionally, by designing a new benchmark that focuses on low-prevale

---

### [198] GeoLift: Grounding Video Spatial Reasoning in Explicit 3D Maps

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2610.33558&hl=zh-CN&sa=X&d=15264774373229099957&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv5HBkTTucEts5VXosLwJ3OO&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=8&folt=kw-top
**作者**: X Li, TT Long, J Zhou, J Chen, J Yang, J Xie - arXiv preprint arXiv:2610.33558 等 (7 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> GeoLift combines a frozen MLLM for 2D grounding with pretrained geometry models for scene reconstruction. It then uses shared geometric regions, called superpoints, to associate observations of the same object across views without a

---

### [199] Where Can We Fool the Model's Mind? Response-Guided Semantic Probing and Adaptive Routing for Transferable Attacks on Black-Box MLLMs

**链接**: https://arxiv.org/abs/2610.38013
**作者**: Ahmed Abdelnaby and Mohamed Elmahallawy
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal Large Language Models (MLLMs) ground language in visual evidence, yet their semantic reasoning can be exploited through transferable black-box adversarial attacks. Existing attacks typically allocate perturbations using surrogate-model saliency, which may not reflect how an unseen MLLM semantically interprets or relies on different image regions. We introduce VISTA (Vulnerability-Informed Semantic Transfer Attacks), a black-box framework that identifies semantically vulnerable visual regions from an MLLM's responses without access to gradients, logits, parameters, or internal representations. VISTA supports two attack settings: (i) VISTA-Proxy, a pure-transfer setting that probes an open-source MLLM and transfers the resulting adversarial examples to unseen commercial MLLMs without querying them; and (ii) VISTA-Victim, a query-assisted setting that probes the target MLLM to capture model-specific semantic vulnerabilities. VISTA builds an Uncertainty-Based Multimodal Behavior

---

### [200] Profiling a Frontier Agent with EBench: From Direct Control to Harness with Policy

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2610.35832&hl=zh-CN&sa=X&d=401922672052979205&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv7_K90YM6cNTORcKvaE1M9O&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=7&folt=kw-top
**作者**: Y Yao, Y Zou, G Jiao, X Gao, N Gao, Y Wang 等 (8 人)
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Overall, our study characterizes the capability boundary of a frontier MLLM agent and suggests directions for improving future agent harness design. Project page: this https URL

---

### [201] LatentWeave: Test-Time Latent Optimization for Multimodal Reasoning

**链接**: https://arxiv.org/abs/2610.39557
**作者**: Fanci Meng, Kun Wang, Guibin Zhang, Xinlei Yu, Jiaming Zhang, Ming Li 等 (7 人)
**来源**: cs.LG
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in test-time optimization have shown that the multimodal reasoning performance of large multimodal language models (MLLMs) can be improved during inference without modifying backbone model parameters. However, existing approaches primarily operate at the prompt or output level, leaving the latent reasoning process largely uncontrolled and insufficient to prevent error accumulation during autoregressive generation. To address this limitation, we propose LatentWeave, a test-time framework that treats multimodal reasoning as a controllable latent trajectory. LatentWeave performs structured Latent Weaving, progressively refining intermediate hidden states segment-wise to correct emerging deviations, and further introduces Reasoning Anchors via lightweight WEAVE tokens to stabilize reasoning structure and guide answer-oriented generation. These mechanisms are designed to enable fine-grained, step-aware intervention in the latent reasoning process while keeping the main MLLM 

---

### [202] AdaptiveDocRAG: Efficient Document Understanding with Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://aclanthology.org/2026.docinsights-1.5.pdf&hl=zh-CN&sa=X&d=13282662567063637341&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv4iDtnFaUjGlFDluZxwt4sZ&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=4&folt=kw-top
**作者**: S Selvam, A Raghunathan
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> relevant pages to a query to the MLLM , thereby reducing MLLM usage cost and latency. … Question answering runs once per query and feeds the top-K pages to the MLLM ; its cost scales … of the retriever or MLLM , and each adds negligible

---

### [203] From Presence Labels to Bounding Boxes: Can Multimodal Large Language Models Scale Surgical Instrument Localization?

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/pdf/2610.34218&hl=zh-CN&sa=X&d=18300361343814176192&ei=ohXkav-AA6-A6rQPyZTo-QY&scisig=AIL1Nv5hSvJKGeyc-b0KbphcXO20&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIL1Nv7ZtfCfVzrJbncruGtkyRGX&html=&pos=3&folt=kw-top
**作者**: M Hamdy, M Abdel-Ghani, F Ahmed, S Nasar… - arXiv preprint arXiv …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> In this study, we design a scalable MLLM -based annotation framework that converts surgical frames and existing instrument-presence labels into accurate bounding boxes, and systematically analyze its reliability, cost, and design sensitivity

---

### [204] Benchmarking color judgment in multimodal LLMs with CIE-computable ground truth

**链接**: https://arxiv.org/abs/2610.40212
**作者**: Shuwei Yue, Kaida Xiao, Zhihua Wang, and Qiao Chen
**来源**: cs.CV
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multimodal large language models (MLLMs) are now used as zero-shot judges of image quality, but their color judgments are rarely tested with colorimetric ground truth. We present a five-task benchmark based on the CIE colorimetric framework: AWB pair judgment, skin-tone bias direction, CCT estimation, CIE Delta E 2000 pair ordering, and color naming under changing illuminants. We test eight MLLM endpoints, including four Qwen3-VL variants, GLM-4.5V, GPT-5.4, Claude-Opus-4.7, and Gemini-3.1-Pro. The models often solve coarse binary AWB judgments, but they remain weak on numeric CCT estimation and on some fine color-difference judgments. On ColorChecker-24 stimuli, the three closed-weight frontier models reach CCT MAE of 715-1056 K, compared with 1358-2133 K for the five open-weight models. A non-ColorChecker control shows that this advantage is partly template-dependent. The results suggest that current MLLMs have useful color words and coarse visual priors, but their color judgments ar

---

### [205] EEG Motor Imagery Classification Based on Multi-Perspective Attention-Based Multi-Scale Convolutional Neural Network

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/1999-4893/19/11/924/pdf&hl=zh-CN&sa=X&d=13233113686379051557&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv4fEkXUaC-lt62iidF-lFx9&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=4&folt=kw-top
**作者**: H Zhao, Y Zhang, H Zhang, H Zheng, P Zhao, B Zhang… - Algorithms 等 (7 人)
**匹配关键词**: EEG, BCI, Motor Imagery
**相关性评分**: 9.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalogram ( EEG )-based motor imagery (MI) decoding is vital in brain–computer interface (BCI) systems. Although convolutional neural networks (CNNs) have achieved promising results, existing methods still face limitations in multi-scale

---

### [206] EEG -fNIRS Based Cross-Subject Emotion Recognition by Contrastive Learning and Domain Adversarial Networks

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0957417426037607&hl=zh-CN&sa=X&d=12434464127155735580&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv4sldSYD0rPKz0UlbYg2gfq&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=1&folt=kw-top
**作者**: Y Han, Q Xu, Z Yang, J Yu, H Huang, S Zhang 等 (8 人)
**匹配关键词**: EEG, BCI
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> ) for constructing an affective BCI that fused electroencephalography ( EEG ) and functional near-… The performance of the proposed model was evaluated on two EEG -fNIRS multimodal … that combining EEG and fNIRS achieved higher accuracy

---

### [207] Towards fNIRS foundation models: A curated corpus of 67 public datasets with channel positions in MNI space

**链接**: https://arxiv.org/abs/2610.40277
**作者**: Santiago Posso-Murillo
**来源**: cs.HC
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Brain foundation models have transformed medical artificial intelligence and computational neuroscience by reducing the reliance on task-specific data through large-scale pretraining. While they have been successful with non-invasive neuroimaging data, their adoption in functional near-infrared spectroscopy (fNIRS) has lagged due to the limited size and heterogeneity of public datasets, which are collected under varying protocols, devices, and sensor configurations. In addition, no single fNIRS dataset is comparable in size to the largest datasets in functional magnetic resonance imaging (fMRI), electroencephalography (EEG), or magnetoencephalography (MEG). The fNIRS datasets are also spread across different platforms and often have insufficient information, or lack the protocols that would make them easier to use. Given the advances in EEG foundation models that enable flexible modeling across diverse EEG montages, we curated 1,955 hours of fNIRS data from 67 public datasets spanning 

---

### [208] REVBRAIN: Real-time Probabilistic EEG Forecasting Using Residual Vector Quantization

**链接**: https://arxiv.org/abs/2610.38558
**作者**: Hanna Pankka, Jaakko Lehtinen, Timo Roine
**来源**: cs.LG eess.SP q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Real-time forecasting of resting-state EEG signals is required by applications like brain-state-dependent stimulation, where computer generated actions are coupled with ongoing neural oscillations. Recently, the deep learning model WaveNet was proposed for the forecasting task. It shows superior accuracy compared to the prevailing method, the linear autoregressive (AR) model, and provides a built-in uncertainty measure due to its probabilistic modeling framework. However, inference using WaveNet is too slow for real-time use due to its sample-by-sample autoregressive operation: a single forecast requires evaluating the model tens or hundreds of times depending on the length of the prediction window. In this paper, we present REVBRAIN, a probabilistic deep learning method that produces forecasts in real time by generating the forecast over the whole prediction horizon at once. This is achieved by tokenizing the output space using residual vector quantization (RVQ) and generating forecas

---

### [209] Interpreting human responses to urban scene composition with EEG : A framework for lab-to-urban transfer

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0143622826003425&hl=zh-CN&sa=X&d=246916136095172604&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv4vNKtathJcqjrnmRwFojWr&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=0&folt=kw-top
**作者**: W Bai, X Ye, W Zhang, Y Ye, G Newman, Y Song - Applied Geography 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Signature (ENS) templates from a laboratory emotion EEG dataset and projects EEG responses from an urban scene-based appraisal … -based EEG examined in this study refers to EEG recorded during controlled appraisal of static street-view

---

### [210] DEMIST: Decoding EEG via montage-informed source transformer for brain source imaging

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1474034626011043&hl=zh-CN&sa=X&d=5630179093256547341&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv4hP354iaVSZqww-B_kwbMx&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=6&folt=kw-top
**作者**: CH Chuang, YC Chen - Advanced Engineering Informatics, 2027
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electrophysiological source imaging (ESI) unlocks brain spatiotemporal dynamics by back-mapping scalp electroencephalography signals to their underlying cortical generators, providing a non-invasive window for advanced neuroscientific research

---

### [211] Reduced cognitive empathy and differences in EEG activity in low-achieving adolescents

**链接**: https://scholar.google.com/scholar_url?url=https://journals.plos.org/plosone/article%3Fid%3D10.1371/journal.pone.0361520&hl=zh-CN&sa=X&d=10706509680439329046&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv793pkVGE62n9aPciBzoPCd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=5&folt=kw-top
**作者**: S Hernández-González, MÁ Gómez-Climent… - PLOS ONE, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> recognition test, and electroencephalographic ( EEG ) recordings. Results showed significantly … EEG analyses identified exploratory between-group differences in source-level oscillatory … EEG findings require cautious interpretation and

---

### [212] Open-source Software and Pipelines for Generalizable and Reproducible EEG Analysis: An Overview

**链接**: https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2610.34047&hl=zh-CN&sa=X&d=18221760358245670858&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv5o5cs7RZr8Df0acml0DNPG&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=2&folt=kw-top
**作者**: T Medani, R Cassani - arXiv preprint arXiv:2610.34047, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> requirements for reliable electroencephalography ( EEG ) research. Achieving these goals remains challenging because EEG datasets vary … software, and computational pipelines that support transparent and generalizable EEG analysis

---

### [213] EEG-Captioner: Grounding EEG-to-Language Generation in Fundamental Signal Properties

**链接**: https://arxiv.org/abs/2610.30995
**作者**: Leyuan Jin, Jiahao Mei, Yixuan Yuan, Shimeng Li, Mengyue Wu, Yue Ding
**来源**: cs.LG
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [214] Intranasal Dexmedetomidine Sedation in Pediatric Electroencephalography : Dose optimization, Safety, and EEG Characteristics

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S105913112600316X&hl=zh-CN&sa=X&d=9860847317739666971&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv5PR3cZVU0J6vCIEn7neWa7&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=9&folt=kw-top
**作者**: HJ Yun, I Youn, NY Lee, M Kook, YH Kim, J Cho 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> to the year in which our institution transitioned its routine EEG sedation regimen to intranasal DEX, and this consecutive sampling was … pediatric population undergoing sedated EEG at our center. Inclusion criteria were age 0–18 years and

---

### [215] NeuroBridge: Bio-Inspired Self-Supervised EEG-to-Image Decoding via Cognitive Priors and Bidirectional Semantic Alignment

**链接**: https://arxiv.org/abs/2511.06836
**作者**: Wenjiang Zhang, Sifeng Wang, Yuwei Su, Xinyu Li, Chen Zhang and Suyu Zhong
**来源**: cs.CV cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [216] BridgeRouter: Gain-Aware Instance Routing over Cross-Modal Bridge Portfolios

**链接**: https://arxiv.org/abs/2610.38152
**作者**: Ruoxi Piao, Alicia Lu, Yunzhen Zhang, Mustafa M{\i}s{\i}r, Hasan Onur Kele\c{s}
**来源**: cs.AI
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Lightweight representation bridges make pretrained, task-adapted EEG foundation models executable on other biosignal modalities without retraining their backbones. However, selecting a single bridge pathway globally assigns every instance to the same transfer route and ignores complementary errors across routes. We therefore formulate multi-bridge transfer as an instance-level algorithm-selection problem and introduce BridgeRouter, a gain-aware router over a portfolio of frozen cross-modal pathways. A validation-selected Single Best Solver (SBS) serves as a protected default route. During training, task labels are used to compute the reduction in negative log-likelihood provided by each alternative route relative to the SBS, and a lightweight MLP predicts these route-specific gains from a target-modality representation extracted by a frozen encoder. At inference, BridgeRouter observes only the target modality, requires neither EEG, task labels, nor predictions from all candidate routes

---

### [217] EEG reflects subjective but not behavioral hearing in noise performance

**链接**: https://scholar.google.com/scholar_url?url=https://academic.oup.com/cercor/article/36/10/bhag157/9003175&hl=zh-CN&sa=X&d=14109807563427370183&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv5HvW2RvCnAOZTR-96AemUE&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=3&folt=kw-top
**作者**: J Liu, J Stohl, T Overath - Cerebral Cortex, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> We evaluated how these measures relate to auditory brainstem response, cortical electroencephalogram ( EEG ), behavioral (eg, frequency … In contrast, EEG P3 amplitude was only retained in the SSQ model and not in the TIN or SRT models

---

### [218] A Synchronized Dual-Scale Platform Combining Flexible Micro-ECoG and Skull-Screw EEG Reveals Frequency-Dependent Cortex-to-Skull Spectral Gain in Awake …

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0956566326010031&hl=zh-CN&sa=X&d=1560916262532612958&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv5fN8aAL8RZr6VbSwZryeBZ&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=8&folt=kw-top
**作者**: F Mo, Y Xu, H Zhao, S Li, Y Dai, Z Song - Biosensors and Bioelectronics 等 (7 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Electroencephalography ( EEG ) is the most scalable window onto brain dynamics, yet how cortical activity is transformed before reaching extracranial electrodes has largely been inferred from forward models rather than directly measured. We built a

---

### [219] A Hybrid Deep Learning Model (CNN-GRU) with MRMR for EEG -Based Depression Detection

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2075-4418/16/21/3507&hl=zh-CN&sa=X&d=9941132781049880852&ei=oRXkaoD-MdrPieoP8OvCmQw&scisig=AIL1Nv7KzT1hG90nF6Oc3IbeDDWd&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIL1Nv4cb8K37bRNlxFibqagmnBp&html=&pos=7&folt=kw-top
**作者**: MR Yousefi, E Ebrahimzadeh, HI Al-Tamimi… - Diagnostics, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Background/Objectives: Major depressive disorder (MDD) is a prevalent mental health disorder for which objective and reliable diagnostic approaches remain an active area of research. Electroencephalography ( EEG ) has emerged as a

---

### [220] TabCUQ: Context-Uncertainty Quantification for Tabular Foundation Models

**链接**: https://arxiv.org/abs/2610.39558
**作者**: Yuebei Shi, Molei Liu and Zijian Guo
**来源**: stat.ML cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models use in-context learning to estimate conditional expected outcomes and average treatment effects for specific groups of individuals. Using these estimates to guide scientific decisions requires reliable uncertainty quantification. The challenge is to account simultaneously for two sources of uncertainty: limited-context bias and context variation arising from the small labeled sample supplied at inference. Predictive spread does not directly quantify both sources of uncertainty, and we observe that the ordinary bootstrap may substantially overestimate context variation, whereas subsampling may underestimate it. We introduce TabCUQ, a perturbation-based framework that injects noise into observed outcomes and applies the foundation model to the perturbed contexts. TabCUQ estimates context variation using wild-bootstrap dispersion and accounts for limited-context bias using the maximum deviation between perturbed and original estimates. For a kernel-regression ana

---

### [221] Are Seismic Foundation Models More Than Glorified Feature Extractors?

**链接**: https://arxiv.org/abs/2610.38003
**作者**: Laura Laurenti, David Liu, Brian Kulis, Men-Andrin Meier, Christopher Johnson
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earthquake sequences are stochastic on two separated timescales: the seismic waves of any individual earthquake propagate over seconds to minutes, while the earthquakes themselves arrive as a sparse, self-exciting occurrence process, with inter-event intervals from seconds to months. Respecting both scales in one training objective is the open challenge. Foundation models (FMs) for seismic waveforms instead import their learning targets from audio and vision, where every target is computed from a single fixed-length window. Such a window holds one realization of the wave propagation (an earthquake trace), never the occurrence process that decides when earthquakes happen. We develop nine model designs sharing one Mamba encoder-decoder, trained on a fixed corpus of 3M windows, varying the self-supervised objective, quantization bottleneck and mixer; the two key comparisons are architecture-matched, varying the objective alone. Each checkpoint is evaluated frozen on three downstream tasks

---

### [222] Modular Bayesian Foundation Models: Bayesian time series encoders for OOD detection, routing and forecasting

**链接**: https://arxiv.org/abs/2610.39043
**作者**: Mame Diarra Toure, Quang Hung Pham, Mohamed Ryad Zemouri, David Stephens, Luc Vouligny, Martin Gagnon
**来源**: stat.ML cs.LG stat.AP stat.CO
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial systems continuously generate time series that vary in sampling frequency, scale, dynamics, and operating regime. Consequently a single time-series foundation model may not be able to represent all regimes effectively and retraining a large model for every new dataset or regime shift is computationally expensive. Modular foundation models address this issue by reusing specialised encoders trained on diverse datasets and by allowing the expansion of capabilities through the addition of new experts. This approach requires compact experts to minimize storage cost and a proper selection mechanism of experts for unseen data. We propose a modular foundation model framework that combines end-to-end Bayesian encoder training with uncertainty based routing. Using Singular Bayesian Neural Networks (SBNNs), we build a collection of compact Bayesian encoders whose epistemic uncertainty guides label-free selection. At the selected ranks, our Bayesian collection uses 63.8\% less storage t

---

### [223] OpenEBFM: Energy-based Foundation Models Are Scalable Architecture

**链接**: https://arxiv.org/abs/2610.33005
**作者**: Yuan Pu and Yudong Lu and Ting Wang and Zhicong Hong and Qinuo Li and Xuansheng Wu and Na Zou and Xia Hu and Guanchu Wang
**来源**: cs.CL cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [224] Training Foundation Models with a Single Algorithm

**链接**: https://arxiv.org/abs/2610.40564
**作者**: Yuda Song, Alvin Zhang, Fahim Tajwar, Daman Arora, Jeff Schneider, Daniel Khashabi 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models are typically trained in stages: pretraining, midtraining, supervised fine-tuning (SFT), and reinforcement learning (RL), with changes in both data and learning algorithms. We show that this algorithmic separation is not fundamental. By deriving suitable RL objectives as maximum-likelihood fitting to model-generated target distributions, we place all of these stages under a single likelihood-based training algorithm, unified training. This perspective turns the foundation-model training lifecycle into a problem of choosing which data to train on, in what proportions, and when, with conventional staged training as a special case. We instantiate this framework in a unified training system that mixes static data and RL generations within a single trainer. Across controlled and real-world experiments, unified training improves the accuracy-compute tradeoff and task coverage while preserving broader capabilities, and provides a stronger starting point for continual learnin

---

### [225] Probing Spatial State Representations in Visual Foundation Models

**链接**: https://arxiv.org/abs/2610.40636
**作者**: Baiqiao Yin and Zhongang Cai and Ruisi Wang and Qiwei Liang and Lei Yang and Ziwei Liu
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> An observer sees only part of the surrounding world, yet must keep track of what lies beyond the current view. Spatial perception therefore involves more than recognizing individual images: it calls for a persistent spatial state that is updated under self-motion and used to guide action. Do visual foundation models provide representations that support such a state? We study this question through four levels of spatial capability---spatial structure, object persistence, predictive spatial update, and actionability---using frozen-feature probes on ten representations under streaming egocentric observations of static indoor environments. The resulting capability profiles vary across tasks, network layers, and prefix lengths: strong readout of the visible scene does not ensure accurate object persistence or future-feature retrieval. Matched controls separate readout accuracy from reliance on visual history and motion. Native future prediction retains recoverable spatial structure, but a s

---

### [226] InHabit: Scaling 3D Human-Scene Interaction Data With Image Foundation Models

**链接**: https://arxiv.org/abs/2604.19673
**作者**: Nikita Kister, Pradyumna YM, Istv\'an S\'ar\'andi, Jiayi Wang, Anna Khoreva, Gerard Pons-Moll
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [227] Learning a Prior-Data Fitted Network for Graph Foundation Models via Structural Causal Model Priors

**链接**: https://arxiv.org/abs/2610.38335
**作者**: Ziwei Zhang, Tianyin Liao, Chunyu Hu, Ge Lan, Nuo Xu, Yi Huang 等 (10 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Graph Foundation Models (GFMs) have recently emerged as a promising paradigm for learning transferable representations across different graphs and domains. However, existing GFMs face notable limitations, including limited pre-training scale or reliance on aligning with textual information in Large Language Models (LLMs). To overcome these limitations, recent studies have drawn inspiration from prior-data fitted networks (PFNs), which learn from large synthetic datasets and support multi-domain prediction backed by causal learning. However, existing graph PFNs encounter severe difficulties in modeling causal relationships within and across node and edge sets, generating diverse graph structures, and designing suitable architectures that can learn from complex synthetic datasets. To address these challenges, we propose **GSCM-PFN** (Graph SCM-based Prior-Data Fitted Network), a graph PFN pre-trained on synthetic data generated from an SCM-based prior that jointly models nodes and graph 

---

### [228] Tabular foundation models are not a shortcut to calibrated clinical risk prediction: a pre-registered simulation against the true risk

**链接**: https://arxiv.org/abs/2610.39065
**作者**: Ebrahim Khaled Ebrahim
**来源**: stat.ME cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models are pretrained networks that predict risk from a table without fitting a model. Whether their risks are correct (calibrated) has been judged on real data, where true risk is unknown. In a pre-registered simulation with known true risks, we compared TabPFN-3.5, TabICLv2 and Mitra-v2 with Firth logistic regression with intercept correction (FLIC) in 58 scenarios and 1,000 random designs, then on four clinical data sets. Foundation models were not a shortcut to calibration. Their calibration slope matched FLIC's within the pre-registered margin in 36 or 37 of 48 core scenarios and was better only at n = 200 with a 3% event rate. Even 3,000 patients were often not enough: with FLIC, TabPFN-3.5 or Mitra-v2, 63%-83% of samples gave risks close to the truth in average, intercept and slope at event rates of 10% and 30%, and 35%-50% at 3%. TabICLv2 did worse (8%-39% and 1%-3%). Across the random designs, foundation models had a lower true calibration error than FLIC be

---

### [229] Learning Safe Flow Matching Robot Policies from Binary Feasibility Oracles

**链接**: https://arxiv.org/abs/2610.40075
**作者**: Jianming Ma, Rongjun Jin, Yizhi Chen, Yue Gao
**来源**: cs.RO cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Robot foundation models increasingly rely on flow-based action generation for general-purpose manipulation, yet the generated actions are not guaranteed to satisfy physical constraints such as joint limits and collision avoidance. This problem is especially challenging when the feasible set cannot be described analytically and is accessible only through black-box feasibility oracles. We study this practical oracle-only setting and propose an oracle-guided differentiable safeguard for safe flow-matching robot policies. The safeguard uses binary feasibility queries to correct unsafe updates in the forward pass, while extracting local boundary information to provide constraint-aware learning signals in the backward pass. Combined with discrete-time flow matching, the same safeguard is used during training and inference, enabling forward--backward aligned policy learning without explicit or differentiable constraint models. Experiments on obstacle-aware robotic manipulation demonstrate 100

---

### [230] Knowledge-structured and evidence-aware semantic self-distillation for glomerular pathology foundation model

**链接**: https://arxiv.org/abs/2610.38346
**作者**: Qiming He, Jing Li, Zihan Wang, Tian Guan, Yifei Ma, Zimo Zhao 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Visual foundation models learn rich pathological morphology but lack explicit concept-level supervision. Vision--language pretraining can provide this supervision but requires costly image--text pairs. Here, we introduce GloSAGE, a semantic self-distillation framework that uses lesion profiles predicted by a pretrained visual teacher to construct structured pathology descriptions. Reliability-guided selection identifies image--text anchors, while Knowledge-Structured Pathology Text Synthesis and Evidence-Guided Negative-pair Construction account for partially observed lesions. Image--text alignment trains projection layers while retaining the frozen visual encoder; an intermediate Semantic Transfer Layer supplies features for downstream tasks. Developed on GloMillion and evaluated across seven glomerulus- and case-level cohorts, GloSAGE supported zero-shot lesion recognition, image--text retrieval, hard-negative discrimination and concept-intervention analyses. It outperformed its sour

---

### [231] Separability Is Not Alignability: Representations for Spectrum-to-Molecule Retrieval

**链接**: https://arxiv.org/abs/2610.37979
**作者**: Karol Musielinski, Fanurs C.E. Teh, Takahiko Koyama, Artur Dubrawski
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Identifying a small molecule from its tandem mass spectrum is limited by paired data. Foundation models offer a way around this scarcity: pretrain a spectrum encoder on unlabeled spectra and a molecule encoder on a large corpus of structures, then align the two frozen representations, as in vision-language and as the Platonic Representation Hypothesis suggests. We audit this route on MassSpecGym with spectrum encoders retrained free of test-fold contamination. Alignment needs a metric relating distinct molecules, but the objectives that produce spectrum encoders never see molecular structure: we prove that some predictive objectives fix molecular identity without fixing that metric. Moreover, we find that a candidate-based objective rewards a spectrum-independent prior over the benchmark's decoys, which we isolate. What ultimately addresses data scarcity is not architectural: simulated spectra surpass frozen geometry.

---

### [232] Interpretable by Design Tabular Prediction via In-Context Local Linear Learning

**链接**: https://arxiv.org/abs/2610.39506
**作者**: Ran Eisenberg, Steven Berger, Ofir Lindenbaum
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In-context learning (ICL) lets tabular foundation models make predictions without dataset-specific training or fine-tuning. These models achieve strong predictive accuracy, but interpreting how individual features contribute to the prediction remains difficult. In biology, for example, feature contributions can help identify biomarkers or risk genes. Post-hoc interpretability methods assign feature importance scores, but these scores do not indicate what the model actually uses and can lead to explanation errors. We introduce TICL$^3$ (Tabular In-Context Local Linear Learning), an interpretable-by-design predictor that uses a tabular foundation model to guide a simple linear prediction rule. TICL$^3$ first learns a shared linear model to capture dataset-level feature effects. Then, for each query, it retrieves similar training samples using representations from the foundation model and fits a second linear model to the residuals in that neighborhood. The shared model captures broad eff

---

### [233] TaxoMFM: A Taxonomy-Aware Foundation Model for the Human Gut Microbiome

**链接**: https://arxiv.org/abs/2610.39316
**作者**: Haochen Xue, Anastasia Godneva, Yulong Li, Qi Cao, Zhaodong Wu, Kaiyu Liang 等 (9 人)
**来源**: cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Existing gut microbiome foundation models typically use flat taxon representations, limiting their ability to exploit known taxonomic hierarchies. We introduce TaxoMFM, a microbiome foundation model that integrates taxonomic structure into self-supervised learning. TaxoMFM jointly learns abundance patterns across taxonomic ranks and relative proportions within groups through taxonomy-aware encoding and hierarchical compositional reconstruction. We further construct TaxoGut-HPP, comprising 100,806 gut microbiome profiles from 231 source cohorts and covering 40 classification and 8 regression tasks. TaxoMFM achieves competitive performance across disease, gut health, host trait, and liver ultrasound phenotype prediction. In cross-cohort zero-shot transfer, where target cohorts are excluded from both pretraining and downstream adaptation, TaxoMFM achieves AUROCs of 0.838, 0.736, and 0.722 for colorectal cancer, type 2 diabetes, and inflammatory bowel disease, respectively. Further analyse

---

### [234] Understanding axial attention in TSFMs through single location regression

**链接**: https://arxiv.org/abs/2610.40188
**作者**: Andrei-Tiberiu Pantea, Aymeric Dieuleveut
**来源**: stat.ML cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in Time Series Foundation Models (TSFMs) increasingly rely on axial attention mechanisms, but despite their empirical success, the theoretical properties of axial attention remain largely unexplored. To bridge this gap, we extend the Single Location Regression framework introduced in Marion et al. [2025] to 2D structured data, in order to study sparse information settings where a target depends on a small number of tokens. We formulate an analytically tractable axial attention-type predictor and rigorously analyze its statistical properties and training dynamics. We prove that under a specific asymptotic regime and with knowledge of the underlying oracle parameters, our predictor achieves Bayes optimality, whereas a class of semi-linear simplifications strictly fails to do so, underlining the role of the inner non-linearity. We prove that for a specific temperature scaling, Projected Gradient Descent converges globally to the optimal oracle parameters. Extensive numeric

---

### [235] Responsible Quantum Machine Learning for Medical Imaging: A Fairness Audit Across Sensitive Subgroups

**链接**: https://arxiv.org/abs/2610.37819
**作者**: Giovanni dos Santos Franco, Felipe Mahlow, Ellison Fernando Cardoso, Jos\'e Adenaldo Santos Bittencourt, Felipe Fanchini
**来源**: cs.LG cs.AI cs.CY
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantum machine learning (QML) is increasingly explored for medical classification, yet its behaviour under subgroup-aware fairness criteria remains understudied. We present an empirical fairness audit of classical and quantum classifiers for medical imaging, assuming QML is not inherently fair. Two scenarios are evaluated: dermatological lesions on DDI (sensitive attribute: Fitzpatrick skin type) and chest X-rays on CheXpert-derived data (sensitive attribute: age group). Using ResNet-18 embeddings, we train SVM, MLP, QSVM and QCNN under a baseline and three mitigation settings: differentiable Equalized Odds (EO) regularisation, Gradient Reversal Learning (GRL), and both combined. Foundation models (PanDerm, EVA-X) serve as external references. Quantum classifiers may achieve competitive aggregate performance while still exhibiting subgroup disparities. Since a smaller subgroup AUC gap may stem from degrading the best group rather than improving the worst, each mitigation is also teste

---

### [236] Spectral Invariant Fusion and Refinement for Domain Generalized Semantic Segmentation

**链接**: https://arxiv.org/abs/2610.39926
**作者**: Yansong Bai, Yunzhi Zhuge, Xinzhuo Yu, Lu Zhang, Jin Zhan, Pingping Zhang 等 (7 人)
**来源**: cs.CV cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Domain generalized semantic segmentation is challenging because it requires accurate dense prediction on unseen domains without any access to target-domain data during training. Existing methods improve transferability through data diversification, invariant learning, or direct use of foundation models, but they often struggle to simultaneously suppress domain-sensitive interference and preserve fine-grained spatial cues. In this work, we propose SIFR, a frequency-aware dual-stream framework that tackles domain shift at both the fusion and decoding stages. SIFR uses spectral modeling as a unified principle to regulate both heterogeneous prior interaction and dense decoder refinement. Instead of directly fusing frozen CLIP and DINOv2 features, SIFR performs spectral-guided invariant fusion to filter out domain-sensitive responses while preserving complementary semantic and structural information. In addition, SIFR incorporates a spectral decoder refinement module that stabilizes multi-s

---

### [237] TRACER, a time-to-event EHR foundation model for disease detection across health systems

**链接**: https://arxiv.org/abs/2610.40536
**作者**: Mara Pleasure, Ekaterina Redekop, Vedrana Ivezic, Rushikesh Kulkarni, Aaron Chin, William Speier 等 (7 人)
**来源**: cs.CE cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models trained on longitudinal electronic health records (EHRs) can predict clinical diagnoses years in the future, making them a potential tool for disease screening. We developed TRACER (Temporal Risk Assessment with Clinical EHR Representations), a decoder-based foundation model pretrained on data from over 4.5 million patients from four health systems, and evaluated it on 16 incident diseases at 1-, 2-, and 5-year horizons in more than 2 million patients from two health systems excluded from model development. In contrast to typical evaluations that focus on global metrics (e.g., AUROC), we measured performance at the low false-positive rates that are realistic for screening. We found that TRACER retained its discrimination in external health systems, and at 95% specificity, the patients it flagged were up to eight times more likely to be diagnosed within a year than unselected patients. Evaluating at this operating point also revealed what global metrics alone did not: 

---

### [238] A 211K Parameter Foundation Model: Genetic Prompting in Neural Cellular Automata

**链接**: https://arxiv.org/abs/2610.38776
**作者**: John Kalkhof, Niklas Ihm, Daniel Kirste, Anirban Mukhopadhyay
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The scale of modern foundation models enables broad task generalization. In medical imaging, where segmentation demands vary widely across clinical contexts, such flexibility is invaluable. But current models, such as SAM trade adaptability for scale, locking their utility behind high-end infrastructure and leaving behind the low-resource environments most in need of diagnostic support. To bridge this gap, we introduce Foundational-NCA, a lightweight foundation model capable of adapting to a wide range of medical segmentation tasks without retraining. Built on Neural Cellular Automata (NCA), Foundational-NCA incorporates gradient-based learning with genetic optimization over a latent task space, using a compact task vector to guide predictions. This enables dynamic adaptation via a genetic prompt mechanism, allowing the model to generalize across tasks while keeping the parameter count magnitudes lower at just 211 thousand, compared to SAM-based models with 38.9 to 636 million paramete

---

### [239] CURE: unsupervised and reliable domain-specific data synthesis for instruction tuning via efficient multi-agent collaboration

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/article/10.1007/s42486-026-00278-4&hl=zh-CN&sa=X&d=7848846895708872504&ei=oRXkau6XOMyp6rQP4ry-yQI&scisig=AIL1Nv5zo4L7mTp0Lj3EpvzKw4iO&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIL1Nv6nI2XU9qk0OzeW89wx4dKt&html=&pos=4&folt=kw-top
**作者**: Z Wang, Y Cheng, Z Lu, Y Chen, P Chen, S Fong… - CCF Transactions on … 等 (7 人)
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Large Language Models are powerful, yet deploying massive foundation models across the Cloud–Edge–End continuum is hindered by … both datasets, the full multi - model CURE attains an average relative improvement of 77.4% in Fact score over the base

---

### [240] LucidLyra: Feed-Forward Generative 3D Scene Reconstruction and Joint Understanding via Multi-Task Distillation

**链接**: https://arxiv.org/abs/2610.40495
**作者**: Oliver Hahn, Rodrigo Marcuzzi, Sangeetha Grama Srinivasan, Alessandro Burzio, Sherwin Bahmani, Jiahui Huang 等 (10 人)
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present LucidLyra, a framework that makes generatively reconstructed 3D scenes directly queryable for semantics and instances in a feed-forward manner from video latents. While generative 3D reconstruction can synthesize virtual environments from a single image, downstream applications in robotics and physical AI require not only visual realism but also access to scene semantics and object identities. Existing 3D understanding approaches, however, require captured multi-view scenes, have limited generalization capabilities, or rely on expensive per-scene processing and optimization. To bridge this gap, our method distills complementary knowledge from a camera-controlled video diffusion model and frozen 2D vision foundation models into a unified model to jointly infer 3D Gaussians encoding geometry, appearance, open-vocabulary semantics, and class-agnostic instance cues. The resulting scenes support novel-view rendering, open-vocabulary segmentation, and object grouping without per-s

---

### [241] DES-JEPA: Learning a Shared Vocabulary for High-Dimensional Discrete Event Sequences

**链接**: https://arxiv.org/abs/2610.38445
**作者**: Hugo Math, Maximilian Forstenh\"ausler, Christos Anagnostopoulos
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Temporal foundation models such as Chronos and TimesFM generalize across domains through a shared numerical observation space. In contrast, discrete event sequences (DESs), including operational event logs or patient clinical-event trajectories, have domain-specific event vocabularies whose labels lack a consistent correspondence across domains. Beyond this lack of consistency, the number of distinct events in real-world settings is high enough to challenge both classical temporal point process modeling and current in-context foundation inference models such as FIM-PP. Critically, current foundation models for DESs are limited to a small, fixed number of event types, restricting their applicability to realistic, high-dimensional event streams. To address this, we propose two complementary modules: (i) DES-JEPA, a joint-embedding predictive architecture that learns a shared discrete vocabulary from synthetic stochastic processes with unaligned event vocabularies; and (ii) DES-PFN, a dis

---

### [242] Data Scaling Laws in Stereo Matching: From In-domain Fitting to Cross-domain Generalization

**链接**: https://arxiv.org/abs/2610.38600
**作者**: Tong Zhao, Di Liang, Yiming Zeng, Bo Xu, Yingzhi Tang, Chen Bai
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the era of large models, stereo matching is developing towards generalizable foundation models trained on million-scale synthetic images. However, how model performance scales up with synthetic data is still underexplored. In this work, we preliminarily investigate the in-domain and cross-domain data scaling laws in stereo matching. A realistic synthetic dataset, named XStereo, containing 200 thousand samples is first built to serve as a high-quality benchmark for data scaling research. In-domain training on five large-scale datasets demonstrate a two-regime scaling behavior with data, transitioning from the standard power law to saturation, where the critical transition point is approximately invariant under a fixed model. Cross-domain performance exhibits a substantially weaker and less predictable dependence on the source-domain data scale. The distribution and coverage diversity are more effective for diminishing domain gaps. More instructive suggestions are provided for high-ef

---
