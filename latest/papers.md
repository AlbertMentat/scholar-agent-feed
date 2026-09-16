# 📑 论文索引 - 2026-09-17

共 146 篇论文

---

### [1] Sparse MLLM Anchors, Dense Adaptation: Breaking the Self-Referential Loop in Wild Test-Time Adaptation

**链接**: https://arxiv.org/abs/2609.17040
**作者**: Zhenbin Wang, Lei Zhang, Lituan Wang, Yan Wang, Zhao Zhang, Wei Huang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 8.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Wild test-time adaptation (WTTA) updates a source model online under small test batches, concurrent distribution shifts, and time-varying class imbalance. Most WTTA methods derive their adaptation signals, including predictive uncertainty, sample reliability, and local feature geometry, from the model being adapted. When the source model is unreliable under shift, these signals can reinforce its own errors, forming a self-referential loop. We introduce MASA (Multimodal-LLM-Anchored Semantic Adaptation), which complements model-internal evidence with structured semantic descriptions from a frozen multimodal large language model (MLLM). To limit inference cost, MASA queries the MLLM only for a small set of diverse, reliability-ranked anchors. The resulting descriptions capture the object family and nuisance factors such as style, viewpoint, and occlusion. MASA encodes these descriptions, propagates them to neighboring test samples, and stores the resulting visual-semantic information in 

---

### [2] Distilling Foundation Models for Agentic What-If Reasoning:Cost, Latency, and Governance in a Hybrid LLM+SLM Architecture

**链接**: https://arxiv.org/abs/2609.16091
**作者**: Sourish Dey, Aditya Kumar
**来源**: cs.LG
**匹配关键词**: Foundation Models, LLM
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Tabular foundation models deliver strong zero-training predictive performance via in-context learning, but their high inference latency makes them impractical as hot-path decision backends in interactive agentic loops. We distill a TabPFN teacher into a compact feed-forward student across a business-decision simulation on UCI Adult and five OpenML benchmarks: the classification head compresses 53.2M parameters to 8,546 (6,220x); the deployed two-head loan pipeline compresses 111.4M parameters to 17,059 (6,532x). The student retains 95.4-100.5% accuracy and 96.8-100.0% AUC, with the lowest accuracy retention on credit-g at 95.4%; an alpha = 0 hard-label control shows that the teacher's soft targets provide a 2.1-7.0 AUC point gain.

---

### [3] A multimodal large language model for evidence-based autism spectrum disorder screening

**链接**: https://arxiv.org/abs/2609.16464
**作者**: Jun Chen, Qi Zhao, Yunliang Jiang, Shuqin Cao, Yunqiang Lin, Chenglong Jia 等 (10 人)
**来源**: cs.CV cs.HC cs.LG
**匹配关键词**: Large Language Model, Multimodal Large Language Model
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The clinical management of autism spectrum disorder (ASD) faces a bottleneck in early screening, mainly because trained specialists are scarce and conventional assessment tools are subjective. Here, we introduce ASDchat, a multimodal large language model designed for evidence-based ASD screening, which takes video, audio, and dialogue as input. ASDchat adopts a dual-branch architecture, where the decision branch generates screening probabilities and the evidence branch generates traceable, timestamped behavioral evidence aligned with standardized clinical criteria (ADOS-2). The model was trained and evaluated on a dataset of 1,035 participants from 27 sites in China, which covered typically developing (TD) children, children with ASD, and children with other disorders. For ASD versus TD, ASDchat reached an area under the receiver operating characteristic curve (AUC) of 0.953 $\pm$ 0.021. On 9 held-out sites that were not used for training, the mean AUC was 0.932. Furthermore, unsupervi

---

### [4] Auditable LLM -assisted decision support for sustainable infrastructure planning

**链接**: https://scholar.google.com/scholar_url?url=https://www.emerald.com/jensu/article-abstract/doi/10.1680/jensu.26.00094/1396325&hl=zh-CN&sa=X&d=14241568849757074694&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-ydlhaKJa4fnewCKQyyTIeV&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=7&folt=kw-top
**作者**: A Elkliny, TK Abdulwasea, AS Ibrahim, X Deng… - Proceedings of the …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> auditable large language model ( LLM )-enabled decision… LLM generated criterion weights for TOPSIS, while the GA produced 500 dataset-feasible alternatives. Using weights of 0.34, 0.33, and 0.33 for duration, cost, and

---

### [5] Coupled Calibration and Learning: Mitigating Teacher Bias in LLM Distillation without Target-Domain Reward Feedback

**链接**: https://arxiv.org/abs/2609.17474
**作者**: Haichen Hu, Yuheng Zhang, David Simchi-Levi
**来源**: cs.LG cs.AI math.ST stat.ML stat.TH
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) distillation aims to transfer the capabilities of a powerful teacher to a smaller student. Direct imitation, however, can also transfer the teacher's systematic bias and errors. This challenge is particularly pronounced under covariate shift, when the teacher's reliability on target questions is uncertain and target-domain reward feedback is unavailable. We propose Coupled Calibration and Learning (CCL), an LLM distillation algorithm that couples teacher calibration with student updates through token-level branching, using reward feedback only on source questions. Each iteration calibrates the teacher using source feedback and then uses the calibrated teacher to train the student on target questions. The updated student, in turn, informs subsequent calibration. In an autoregressive policy framework, we prove that the output student's expected average Kullback-Leibler divergence to the oracle student converges to zero at a polynomial rate in the number of iter

---

### [6] Universal Defenses for Tool-Integrated LLM Agents Against Adversarial Attacks

**链接**: https://arxiv.org/abs/2609.16098
**作者**: Xiaoyan Li, Yunli Wang
**来源**: cs.CR cs.AI cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) agents have demonstrated impressive capabilities across a variety of domains, particularly when integrated with external tools for multi-step task completion. However, they are increasingly vulnerable to adversarial attacks, including direct prompt injection, indirect prompt injection, memory poisoning, and backdoor attacks, which exploit the model's openness to prompt injection and tool manipulation. In this work, we explore practical and generalizable defense strategies within a unified framework across these four attack types. We introduce two universal tool-based defenses: Attacker Tool Filtering, which uses anomaly detection (e.g., Isolation Forest) to identify and remove suspicious tools, and Normal Tool Recalling, a white-box method that restores the agent's original toolset prior to planning. Additionally, we incorporate prompt-based defenses: Chain-of-Thought prompting and self-reflection techniques to enhance reasoning and task paraphrasing to mitig

---

### [7] End-to-End Latency-Minimizing and Load-Balanced Request Scheduling for Edge LLM Inference in Agentic AI Services

**链接**: https://arxiv.org/abs/2609.17193
**作者**: Zhen Li, Jun Cai, Haoran Gao, An Li, and Tan Li
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-powered agentic AI services increasingly demand low-latency inference, motivating the deployment of LLMs across distributed edge servers. However, heterogeneous communication and computing capabilities, together with dynamically evolving inference states, make the edge server selection for each incoming request time-varying and tightly coupled across slots. In this paper, we investigate an online request scheduling framework for edge LLM inference that jointly minimizes long-term average end-to-end latency and regulates workload distribution across heterogeneous edge servers. Two main challenges arise in this context. First, conventional latency models cannot accurately capture the fine-grained dynamics of multi-stage LLM execution. Second, the latency consequence of a scheduling decision is observed only after request completion, making immediate decision evaluation difficult. To address these challenges, we develop a cross-slot inference model that captures

---

### [8] Style-Debiased DPO: Updating LLM Knowledge with Factuality-Aware Synthetic Preference Data

**链接**: https://arxiv.org/abs/2609.16532
**作者**: Takayuki Yamamoto, Daisuke Kawahara
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Continued pretraining (CPT) with data augmentation such as paraphrasing can store inside a large language model (LLM) the knowledge of a small source corpus. The stored knowledge, however, is not always retrieved correctly. We study the eliciting side rather than the storing side: we use preference optimization, which learns from pairs of a preferred (chosen) and a dispreferred (rejected) response, so that the model elicits its stored knowledge more accurately. One proposed approach takes the model's own erroneous response as rejected and the gold answer as chosen, so as to suppress the error. When the target knowledge is partially known, however, most of these rejected responses are factually correct. Using direct preference optimization (DPO) then pushes down rejected responses that contain correct knowledge and differ from the chosen answer only in style, such as length and wording. We propose style-debiased DPO (SD-DPO), which scores whether the rejected response of each pair is fa

---

### [9] FlexEE: Self-Speculative and KV-Compatible Early Exiting for Offloading-Aware LLM Inference

**链接**: https://arxiv.org/abs/2609.17008
**作者**: Qihu Xie, Ziwei Li, Yi Kang
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) inference is often constrained by both computation and memory, especially in offloading-based deployments where model weights are transferred across memory hierarchies during autoregressive decoding. In this setting, reducing the number of executed layers can lower per-token latency while also avoiding costly weight movement. Motivated by this observation, we present FlexEE, an early exiting framework for resource-constrained and offloading-based LLM inference. FlexEE makes early exiting practical for LLM decoding through layer-wise exit supervision for reliable intermediate-layer prediction, self-speculative decoding over a Top-K local vocabulary for low-cost exit decisions, and dynamic hidden state management for KV-cache-correct and memory-aware execution. Across generative and downstream tasks, FlexEE enables efficient early exit with minimal accuracy degradation, delivering up to 1.27$\times$/3.16$\times$ and 1.25$\times$/2.83$\times$ end-to-end speedups

---

### [10] Cascade: Hierarchical Recoverability Control for Large Language Model Unlearning

**链接**: https://arxiv.org/abs/2609.16890
**作者**: Qingchen Yu, Shiying Duan, Xiaodong Li, Yuhua Wang, Zhiyu Li, Shiji Zhou 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Model (LLM) unlearning is essential for removing sensitive or copyrighted knowledge while preserving general utility. Existing methods often leave residual knowledge in intermediate representations, which can still be recovered. To address this, we propose Cascade, a hierarchical recoverability control framework that minimizes the internal identifiability of target knowledge. Cascade combines three complementary controls: path-level routing to suppress privacy-associated activation routes, representation-level compression to reduce geometric separability, and decoding-level intervention to limit residual recovery. Experiments on TOFU, MUSE-News, and WMDP, including robustness tests with query reformulation and extraction-style prompts, show that Cascade effectively reduces recoverability while maintaining stable model utility.

---

### [11] Turn-level Multiscale Density Ratio Estimation for LLM Agents

**链接**: https://arxiv.org/abs/2609.16760
**作者**: Zishuo Zhao (Alibaba Group), Kai Chen (Alibaba Group), Ao Li (Alibaba Group), Yuan Liu (Alibaba Group)
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> With the rapid development of Large language model (LLM), agent systems enhanced by LLMs show huge potential in being able to deal with complex tasks, especially involving multi-step thinking or interaction with tools. For applying LLM techniques with a well-designed agent paradigm, post-training of LLM in multiple agent scenarios is necessary to achieve better performance. Among the variable post-training techniques, alignment methods such as PPO, DPO, DIL, and GRPO become popular because many papers show a significant positive impact on the model's performance by punishing negative samples while keeping acceptable training complexity. However, most alignment methods address simple single-turn tasks, and there remains room for improvement for complex multi-turn tasks. We propose Turn-level Multiscale Density Ratio Estimation (tlm-DRE), which assigns different weights on corresponding turns and proposes asymmetric token-level training based on the positive-negative space gaps across mu

---

### [12] Graz University of Technology at Touché: Prompting Strategies for LLM -based Fallacy Detection

**链接**: https://scholar.google.com/scholar_url?url=https://downloads.webis.de/touche/publications/papers/ghiriti_2026.pdf&hl=zh-CN&sa=X&d=5476209571675997109&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-xK4qhqr0oLRPwrvFPLqwOc&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=6&folt=kw-top
**作者**: A Ghiriti, R Kern - Salido, ES, no, ABC, de Herrera 等 (10 人)
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> This paper presents a comparative study of prompting strategies for large language model-based fallacy detection on the Touché 2026 task. Three strategies are evaluated across two axes of variation: classification topology (per-class binary

---

### [13] Enhancing Accessibility of Medical Texts through Large Language Model-Driven Plain Language Adaptation

**链接**: https://arxiv.org/abs/2609.17398
**作者**: Ting-Wei Chang, Hen-Hsen Huang, Hsin-Hsi Chen
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper addresses the challenge of making complex healthcare information more accessible through automated Plain Language Adaptation (PLA). PLA aims to simplify technical medical language, bridging a critical gap between the complexity of healthcare texts and patients' reading comprehension. Recent advances in Large Language Models (LLMs), such as GPT and BART, have opened new possibilities for PLA, especially in zero-shot and few-shot learning contexts where task-specific data is limited. In this work, we leverage the capabilities of LLMs such as GPT-4o-mini, Gemini-1.5-pro, and LLaMA for text simplification. Additionally, we incorporate Mixture-of-Agents (MoA) techniques to enhance adaptability and robustness in PLA tasks. Key contributions include a comparative analysis of prompting strategies, finetuning with QLoRA on different LLMs, and the integration of MoA technique. Our findings demonstrate the effectiveness of LLM-driven PLA, showcasing its potential in making healthcare i

---

### [14] Cost-Aware Sentiment Analysis: A Multi - Model Ensemble with LLM-Assisted Error Attribution

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11682083/&hl=zh-CN&sa=X&d=16893422410286808153&ei=bBWqavnAMY-P6rQPn8DSsAE&scisig=AIVdB-x11bLs9bTUzrSRW_CGTk3x&oi=scholaralrt&hist=F21tmVgAAAAJ:14380004662027926800:AIVdB-wBlF6h20BcrGbCh9DPQSnW&html=&pos=0&folt=kw-top
**作者**: Q Wang - 2026 9th International Conference on Computer …, 2026
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> a Recall of 97.83%, outperforming every single model and the Soft Voting baseline. Large language model -assisted adjudication of disputed misclassifications reveals that 71.4% of model errors are attributable to genuine model deficiencies

---

### [15] LLM -assisted semantic scenario editing and constraint-aware capped stable fixing for renewable-rich SCUC acceleration

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0306261926014856&hl=zh-CN&sa=X&d=9126047434000051252&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-zbfHmFk726yRceBAMudXaB&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=4&folt=kw-top
**作者**: T Wenhu, Z Ruochen, T Qian, H Wenwei, Z Zeyu - Applied Energy, 2027
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> large language model ( LLM )-assisted semantic scenario editing with controlled commitment fixing for renewable-rich SCUC. In the proposed framework, an LLM acts as a … In this work, the LLM is therefore restricted to prototype matching and

---

### [16] 입력모달리티에유연한비디오순간검색및하이라이트탐지를위한지식증류

**链接**: https://scholar.google.com/scholar_url?url=https://www.dbpia.co.kr/pdf/pdfView.do%3FnodeId%3DNODE12930002&hl=zh-CN&sa=X&d=1376719148129708359&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-wg3zTyYXEU-8tLT-nz2oRf&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=4&folt=kw-top
**作者**: 박장호， 김정욱
**匹配关键词**: Large Language Model, MLLM, Multimodal Large Language Model
**相关性评分**: 5.0
**数据来源**: Google Scholar

**摘要**:

> 최근에는 MLLM (Multimodal Large Language Model)이 생성한 캡션을 활용하여 MR과 HD 성능을 크게 향상시킨 SRF[2]가 제안되었 다. SRF는 MLLM 이 생성한 영상 클립 캡션을 추가 입력으로 활용함으 로써, 시각 정보만으로는 파악하기 어려운 장면의

---

### [17] CoAdapt: An LLM-based Framework for Adaptive Collaborative Perception in IIoT Robotic Swarms

**链接**: https://arxiv.org/abs/2609.16852
**作者**: Houssam Hajj Hassan, Antonia Maria Masucci, Lynda Zitoune (L2S), Salah-Eddine Elayoubi (L2S)
**来源**: cs.AI cs.RO
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 5.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Industrial IoT environments increasingly deploy autonomous mobile robots for tasks such as material handling, product assembly, or infrastructure inspection. In such deployments, collaborative perception enables robots to share LiDAR observations and collectively construct a richer model of their environment than an individual agent could produce alone. However, industrial environments are dynamic spaces where robot positions shift continuously, network bandwidth fluctuates, and the marginal contribution of robots to perception quality varies at runtime. Existing collaborative perception approaches are designed for static participation assumptions and cannot adapt to these dynamics without sacrificing either detection precision or communication efficiency. This paper presents CoAdapt, an adaptive collaborative perception framework for IIoT robotic swarms in which a Large Language Model (LLM) serves as a runtime fusion controller, jointly deciding which robots participate in the fusion 

---

### [18] World Model Science: Self-Organized Criticality, Weak Chaos, and Metastable Belief Dynamics in Long-Horizon LLM Agents

**链接**: https://arxiv.org/abs/2609.17419
**作者**: Xinyuan Song, Zekun Cai
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-horizon LLM agents must maintain task state across extended sequences of observations, actions, tool calls, and intermediate beliefs. We study these trajectories through three dynamical views: self-organized criticality, weak chaos, and metastable belief dynamics. Our framework aligns agent-implied states with benchmark-grounded states and measures stress accumulation, error avalanches, temporal dependence, local--global mismatch, bounded divergence, belief-basin transitions, and finite-size scaling under explicit null models. Across 22 experiments spanning controlled puzzles, tool use, embodied tasks, multi-hop retrieval, general-assistant reasoning, and Game of Life, we find that locally valid actions can persist after global state fidelity fails, stress can trigger abrupt collapse, error sequences exhibit long memory, dependency depth changes the propagation regime, and larger horizons support larger avalanches. At the same time, divergence remains bounded, belief states show m

---

### [19] Decoy Direction Optimization: A Post-Hoc Defense Against LLM Abliteration

**链接**: https://arxiv.org/abs/2609.16204
**作者**: Aashiq Muhamed, Mona T. Diab, Virginia Smith
**来源**: cs.LG cs.CL cs.CR
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Safety guardrails in open-weight language models can be readily bypassed using Refusal Feature Ablation (RFA), a technique that identifies and projects out a linear refusal direction from the residual stream, often achieving a high attack success rate (ASR) while preserving model capability. Defending against these attacks typically requires computationally expensive safety finetuning for every new checkpoint. We introduce Decoy Direction Optimization (DDO), a fast, post-hoc weight-editing defense that requires no base-model finetuning. Our approach is based on a simple mechanistic insight: ablation attacks rely on contrastive estimators to find the refusal direction. Rather than trying to hide the true refusal circuitry, DDO actively injects a high-magnitude, nonlinear decoy signal into the network's MLP neurons. When an attacker attempts to locate the refusal direction, the decoy corrupts their estimator, tricking them into ablating a harmless orthogonal feature while the actual safe

---

### [20] Japanese Stroke LLM Evaluation: A Conversational Benchmark for Safe Stroke Care in Japanese Using Large Language Models

**链接**: https://arxiv.org/abs/2609.16739
**作者**: Keisuke Masuda, Kazutaka Yatsushiro, Hirohumi Iwamoto, Hirofumi Hirano, Ryosuke Hanaya
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Background: Large language models (LLMs) have achieved physician-comparable performance on multiple-choice medical knowledge examinations, but their capabilities in clinical history taking, urgency assessment, and safety remain insufficiently evaluated. We proposed Japanese Stroke LLM Evaluation, a multi-turn conversational benchmark for stroke care in Japanese, and evaluated LLM performance and safety under practice-oriented conditions. Methods: We created 10 stroke and related-condition cases and evaluated LLMs in multi-turn Japanese conversations. The LLM acted as physician, while a board-certified neurosurgeon acted as simulated patient and evaluator. Each case comprised history-taking and action phases scored using pre-specified criteria. Errors that could directly threaten life were defined as critical mistakes. The safety threshold was at least 80% overall with zero critical mistakes. Eighteen models were evaluated in October 2025 and June 2026. Results: Claude Fable 5 achieved 

---

### [21] LLM Inference in a Flash!

**链接**: https://arxiv.org/abs/2609.16161
**作者**: Sebastian Zhao, Minseo Kim, Coleman Hooper, Luca Manolache, Michael W. Mahoney, Yakun Sophia Shao 等 (8 人)
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have shown impressive capabilities across a range of natural language processing tasks, and LLM inference has emerged as a critical workload for enabling downstream applications. The demands of serving LLM inference are becoming increasingly challenging as requests shift toward longer sequences and heavier inference, driven by retrieval-augmented generation, inference-time compute scaling, and long-context applications. Additionally, these challenges are compounded by hardware trends, as memory capacity and communication bandwidth are not scaling as fast as increases in workload complexity. Compute-in-Flash is a promising solution to address memory bandwidth limitations by moving computation close to memory, and to exploit the large capacity of SSD technologies. However, it is challenging to deploy LLMs on these systems as they lack support for high-precision floating point operations and have limited write endurance. In our work, we aim to address these ch

---

### [22] JustFit: 200K-Token LLM Serving on a 24 GiB Laptop with Just-in-Time State Management

**链接**: https://arxiv.org/abs/2609.17475
**作者**: Yuhua Chen
**来源**: cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Capable open-weight models make local coding and reasoning attractive, but their context and execution state strain laptop memory. We present JustFit, an MLX-based inference runtime that combines KVExec for compressed KV execution, PhaseSwap for component residency, and StateTrans for state-preserving serving transitions. These mechanisms fuse reconstruction and coordinate just-in-time materialization and release, independently of model-weight quantization. In full-execution capacity tests on a 24 GiB M4 Pro MacBook running Qwen3.8-27B MXFP4, three independent runs complete 196,608 input and 16,384 output tokens, increasing completed single-request context from the mlx-vlm baseline's 30,720 positions to 212,992 (6.93x); a separate two-request run retains 229,376 positions in aggregate. In separate performance tests, a 32K-input, 64-output probe reaches 19.11 tokens/s, and a repeated 32K+6K workload has a median peak process footprint of 16,374 MiB. The integrated runtime answers 29 of 

---

### [23] BLINDSPOT: A Benchmark for Safety and Refusal Calibration in Long-Horizon Tool-Using Agents

**链接**: https://arxiv.org/abs/2609.16305
**作者**: Sadia Asif, Mohammad Mohammadi Amiri, Momin Abbas, Tejaswini Pedapati, Prasanna Sattigeri
**来源**: cs.AI cs.CE cs.CL cs.LG cs.MA
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly operate over long-horizon interactions involving tool use, persistent state, evolving authorization, and external environment feedback. In such settings, safety failures may emerge only after multiple turns, yet existing evaluations often reduce agent behavior to task or attack success, obscuring whether an agent acts, refuses, or remains appropriately calibrated as the interaction evolves. We introduce Blindspot, a benchmark for trajectory-level safety calibration of long-horizon tool-using agents. Blindspot evaluates complete user-agent-environment trajectories through adaptive adversarial interaction, stateful tool execution, and execution-grounded adjudication. Its current instantiation contains 22 attack families and 35 scenarios across seven domains, yielding more than 2,500 long-horizon trajectories with an average interaction length of 14.7 turns. Each trajectory is assigned one of five outcomes: Safe Completion, Correct Refusal, U

---

### [24] LLM -enabled bidirectional material semantic alignment for automated BIM-to-building performance assessment

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0926580526004991&hl=zh-CN&sa=X&d=7797679139224525089&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-y4vDEXexk9epy8fTBJY8jE&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=0&folt=kw-top
**作者**: A Moshari, K Javanroodi, VM Nik - Automation in Construction, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Integrating BIM material information into building performance assessment tools remains challenging, as IFC models often express material intent through project-specific names rather than analysis-ready thermophysical properties. This paper proposes

---

### [25] Superficial Beliefs in LLM Decision-Making

**链接**: https://arxiv.org/abs/2606.11016
**作者**: Gabriel Freedman and Francesca Toni
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [26] Toward Robust LLM-Based Judges: Taxonomic Bias Evaluation and Debiasing Optimization

**链接**: https://arxiv.org/abs/2603.08091
**作者**: Hongli Zhou, Hui Huang, Rui Zhang, Kehai Chen, Bing Xu, Conghui Zhu 等 (8 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [27] HoloAegis: Frozen Representation, Topological Inference --- Minimally Parametric Safety Manifolds and Their Capability Boundaries for LLM Guardrails

**链接**: https://arxiv.org/abs/2608.08485
**作者**: Tak Ho Alex Li, Kaijie Liu, Lik-Hang Lee, Kin Chung Ho, Ping Shum, Michael K. Ng
**来源**: cs.AI cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [28] First Things First: Teaching LLM-Based Agents to Prioritize Must-Haves before Nice-to-Haves

**链接**: https://arxiv.org/abs/2609.05224
**作者**: Tianjie Ju, Xinyue Xu, Wanxuan Sun, Lingxiao Diao, Gongshen Liu, Zhuosheng Zhang 等 (7 人)
**来源**: cs.CV
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [29] Lit3R: Retrieve-Relate-Read for Evidence-Grounded Question Answering over Scientific Literature

**链接**: https://arxiv.org/abs/2609.16912
**作者**: Akira Ise, Kotaro Kumagai, Yuta Yamaguchi, Hisanori Ozaki, Yukio Uematsu, Ikuya Yamada
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We describe tus-nlp's Lit3R (Retrieve-Relate-Read) system for LitTraceQA, a shared task for literature-grounded question answering that requires systems to retrieve relevant papers, identify supporting evidence, and generate answers. Lit3R combines off-the-shelf retrieval, reranking, and large language model (LLM) components without task-specific training. The retriever iteratively combines BM25-based sparse and dense retrieval, cross-encoder reranking, and LLM-based verification, and complements retrieval based on the question with paper-to-paper expansion. The reader first identifies supporting evidence within individual papers and then synthesizes evidence across papers to produce the final answer and evidence trace. On the official test set, our system ranked 4th on the leaderboard. Our code is available at https://github.com/tus-ist-nlp/littraceqa.

---

### [30] AquiLLM: Evaluating Faithfulness in Open-Weight RAG-LLM Systems for Scientific Research

**链接**: https://arxiv.org/abs/2609.16519
**作者**: Bernie Boscoe, Srinath Saikrishnan, Vikram Seenivasan, Jack Stark, Andrew Lizarraga, Morgan Himes 等 (9 人)
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scientific research increasingly relies on large, heterogeneous data sources, motivating interest in retrieval-augmented generation (RAG) systems that provide natural language access to scientific knowledge and research workflows. Researchers are exploring the viability of these systems as natural language interfaces for document search and for generating analysis code and pipeline components. At the same time, concerns about data privacy and control over research infrastructure have motivated interest in open-weight models and open-source deployments hosted within research institutions. In astronomy, this development follows a long history of computational infrastructure development, from archival databases and SQL-based systems to LLM-assisted research tools. This paper presents a domain-expert evaluation of faithfulness for AquiLLM, an open-weight, offline RAG-LLM platform designed to support scientific research groups in the use and preservation of tacit and formal knowledge. We de

---

### [31] Scaling LLMs Via Collaboration: Efficient LLM Inference Across Resource-Constrained Devices

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel8/7755/4358975/11686281.pdf&hl=zh-CN&sa=X&d=12715741409167275518&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-ycAVBocrIYuIQVUAwhqGWH&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=5&folt=kw-top
**作者**: F Zeng, F Lyu, H Wu, Z Li, YH Dong, S Li - IEEE Transactions on Mobile Computing 等 (7 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> To identify the root causes of inefficiency in existing collaborative LLM inference, we perform a systematic analysis that spans design principles and fine-grained profiling. From this investigation, we distill three fundamental observations for

---

### [32] Activation-Weighted Seeded Residual Coding for Low-Bit LLM Weight Repair

**链接**: https://arxiv.org/abs/2608.23144
**作者**: Zehao Liu, Chuangchuang Fang, Yang Ren
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [33] Evidence-Aware Human-in-the-Loop LLM Review for Requirements-to-Planning Decisions

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2073-431X/15/9/608&hl=zh-CN&sa=X&d=4949687407570794517&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-wUoTcdvem3SAGwtoO2kJKS&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=2&folt=kw-top
**作者**: H Alsawalqah, A Abadleh, S Ibrahim, BAY Alqaralleh… - Computers, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large language models can produce fluent requirements refinements and planning artifacts while still leaving information unresolved for implementation, testing, or planning commitment. This paper presents ReqPlan-Eval, an evidence-aware

---

### [34] Conversations in Space: Non-Linear LLM Interaction in Everyday Use

**链接**: https://arxiv.org/abs/2605.15848
**作者**: Rifat Mehreen Amin, Alperen Adatepe, Daniela Fernandes, Daniel Buschek, Andreas Butz
**来源**: cs.HC cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [35] LLM -enabled cognitive metasurfaces

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s44455-026-00040-x&hl=zh-CN&sa=X&d=6264731828644517233&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-yIAEeugk6gXQDbNyZVbGv-&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=9&folt=kw-top
**作者**: J Xu, JC Wei, S Chen, L Li - npj Metamaterials, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Unlike prior intelligent metasurface systems without LLM , the CM can understand user requirements through an LLM -based brain and … Notably, LLM fundamentally transforms the operating paradigm of the CM. Rather than relying on predefined

---

### [36] ToMAS: A Pilot Failure-Grounded Theory-of-Mind Benchmark from Multi-Agent LLM Failures

**链接**: https://arxiv.org/abs/2609.16986
**作者**: Muhammad Ashar Ishfaq and Glaucia Melo
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM-based multi-agent systems can fail even when communication succeeds because agents do not correctly track their peers' roles, knowledge, or intentions. We investigate whether such inter-agent misalignment cases, labelled FC2 in MAST-Data, can be converted into functional partner-state reasoning items. ToMAS applies four explicit convertibility criteria to diagnosed execution traces. A full conversion pass over 242 eligible non-AG2 training traces produced 39 CLEAN items. In an 18-trace reliability pilot, two annotators achieved 94.4% raw agreement and Cohen's kappa = 0.92. We then used the converted items as binary rewards in a small-scale GRPO feasibility experiment with Qwen2.5-1.5B. On a 28-item held-out Magentic GAIA diagnostic, every evaluated condition exceeded the ROUGE-L threshold on the same 2 of 28 items. Post-hoc adapter checks show why: under the learning rate used, the LoRA update remained numerically negligible (max abs Delta W about 7e-6), so all conditions decode id

---

### [37] Competence-Preserving Resume Perturbations Expose Presentation Sensitivity in LLM Screening

**链接**: https://arxiv.org/abs/2609.16517
**作者**: Qiangju Chen and Yang Xiao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Resume screeners must infer job-relevant competence from resumes whose presentation can vary substantially in wording, structure, stylistic polish, and document extraction quality. Ideally, such surface variation should not change decisions when the underlying qualification evidence is unchanged. We introduce a controlled audit of this property, constructing occupation-grounded candidate profiles at controlled competence levels and rendering each profile into multiple resume presentations. A deterministic validation gate excludes variants that alter the underlying evidence before scoring. Across six open instruction-tuned LLM conditions, we find a clear disconnect between screening validity and presentation stability. Llama-3.1-8B with its native chat template achieves the strongest validity ($0.781$) yet reverses $29.6\%$ of matched pairwise decisions under competence-preserving presentation changes; Mistral-7B-v0.3 reaches validity $0.644$ with a $41.4\%$ flip rate. Native chat forma

---

### [38] Interpreting and Steering LLM Agents for Social Simulations

**链接**: https://arxiv.org/abs/2609.16436
**作者**: Jiayue Gaveal Fan, Arul Murugan, Shreyas Krishnan, Abhishek Nagaraj
**来源**: cs.LG cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Simulations based on large language models (LLMs) have proven to be powerful for understanding human behavior, making them valuable additions to the social scientific toolkit. However, LLMs are ultimately black boxes based on deep neural networks which limits their value for social science. This is because of a lack of (i) interpretability: i.e. the ability to assign clear mechanisms driving observed behavior; and a lack of (ii) steerability: i.e. the ability to mute or amplify specific theoretically meaningful mechanisms of action to drive specific model behavior. Here, we demonstrate how the black box could be opened up to further enrich LLM-based simulations. Specifically, we compare three types of methods: (1) prompt-based manipulation, (2) SAE-derived feature steering, and (3) probe-based direction steering and examine their utility for LLM-based social scientific simulations. We do so by interpreting and steering two foundational components of human behaviors, namely preferences 

---

### [39] Test-Time Unlearning via Sparse Autoencoder

**链接**: https://arxiv.org/abs/2609.16229
**作者**: Pingzhi Li, Jinhao Duan, Vaishnav Tadiparthi, Nakul Agarwal, Kwonjoon Lee, Ehsan Moradi Pari 等 (9 人)
**来源**: cs.LG cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Machine unlearning aims to remove specific knowledge from a trained large language model (LLM) without retraining from scratch. Existing methods modify model weights via gradient ascent and its advances. While effective on certain benchmarks, these weight-based approaches exhibit a sharp forget-utility trade-off, where stronger forgetting of target knowledge can degrade model utility, and unlearned knowledge may reappear under post-unlearning fine-tuning or prompt attacks. We propose ARIA (autoencoder-gated inference-time unlearning), a test-time unlearning method that leaves model weights intact and gates access to unwanted knowledge only when generation enters a forget-related state. ARIA uses sparse autoencoder (SAE) latents to train a lightweight linear detector, then applies an interpretable intervention on triggered states with negligible test-time overhead. Empirical evaluations on TOFU, R-TOFU, and WMDP show that ARIA improves the forget-retain trade-off over weight-based basel

---

### [40] ANCHOR: An External LLM-Driven Supervisory Module Facilitating Healthy Evolution in Self-Evolving Systems

**链接**: https://arxiv.org/abs/2606.06114
**作者**: Dianxing Shi and Bowen Wang and Junqi He and Junhao Chen and Yuta Nakashima
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [41] A Multimodal AI Framework for Medical Education: Integrating Adaptive Image Retrieval, Fast Synthesis, and LLM -Based Clinical Auditing

**链接**: https://scholar.google.com/scholar_url?url=https://www.mdpi.com/2313-433X/12/9/438&hl=zh-CN&sa=X&d=17611829991518990843&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-y5u6f3NjBQvx3E7C5aMaj8&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=8&folt=kw-top
**作者**: M Díaz-Benito, C Diana-Albelda, Á García-Martín… - Journal of Imaging, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> of the user, are then fed into an LLM to generate an enriched description of the concept. This … developed an auditing system where a multimodal LLM receives the retrieved image and the … LLM , where, by analyzing both the text query of the

---

### [42] Retrieval-Driven Memory Reconsolidation for Long-Term LLM Agents

**链接**: https://arxiv.org/abs/2609.16053
**作者**: Yuanyi Song, Yukai Wang, Xinbei Ma, Zhihui Fu, Jianghao Lin, Weiwen Liu 等 (10 人)
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Long-term memory is essential for LLM-based agents operating over extended interactions. Existing memory systems primarily update memory when new information arrives, treating retrieval as the endpoint of memory access rather than a driver of memory evolution. Consequently, retrieval feedback is rarely exploited to reorganize memory for future access continuously. Moreover, most existing approaches rely on predefined memory structures together with fixed retrieval pipelines, limiting the agent's ability to organize and evolve its own memory autonomously. Inspired by memory reconsolidation in cognitive neuroscience, we propose \textbf{REALM}, a \textbf{r}econsolidation-\textbf{e}volution \textbf{a}gentic \textbf{l}ong-term \textbf{m}emory framework. It models long-term memory as a continual lifecycle by autonomously organizing memories into a heterogeneous cognitive graph, retrieving evidence via adaptively composed graph-search atoms, and continually reconsolidating memories based on r

---

### [43] Spurious Tool Use: When RL Agents Learn the Wrong Reason to Act

**链接**: https://arxiv.org/abs/2609.16268
**作者**: Yiwei Yang, Haoxiang Zhang, Bingbing Wen, Yao Lu, Yuchen Wu, Lei Zhang 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents increasingly interleave natural language reasoning with external tools such as web search and code execution. These tool-use policies are often optimized via reinforcement learning (RL), which can amplify spurious correlations in the training data. In this work, we study when and why RL-trained agents learn shortcut tool-selection policies: invoking tools based on superficial prompt cues rather than genuine task requirements. We construct controlled synthetic environments combining factual question answering and mathematical reasoning tasks, and inject cues that are strongly correlated with specific tools during training but causally irrelevant to tool necessity. Across counterfactual evaluations where cues are present but the associated tools are not required, agents exhibit substantial shortcut behavior, with spurious tool invocation rates increasing by up to 39 percent. However, shortcut formation is not universal: across the conditions we test, it 

---

### [44] Ask Now, Use Later: Benchmarking the Proactivity Gap in Long-Lived LLM Agents

**链接**: https://arxiv.org/abs/2605.28108
**作者**: Bin Wu, Guanyun Zou, Bingbing Wang, Huan Zhao, Chuan Shi
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [45] Beyond the Name: Demographic Leakage in De-Identified R\'esum\'es and Evaluation Artifacts in LLM Bias Audits

**链接**: https://arxiv.org/abs/2609.16501
**作者**: Qiangju Chen and Yang Xiao
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> De-identified r\'esum\'e screening assumes that redacting explicit fields prevents ethnocultural inference; however, recent audits attribute residual leakage to declared languages. We investigate whether eliminating language fields resolves this leakage across nine open-weight models and 620 counterfactual r\'esum\'es. By holding language attributes strictly identical, we isolate unstructured prose across five ethnocultural conditions and three cue-salience tiers. Target-group recovery averages 0.757 overall and saturates at 1.000 under high salience, demonstrating that non-language prose sustains demographic inference. Crucially, models diverge only under faint cues (0.086-0.690), establishing salience as an essential evaluation axis. Furthermore, pairwise LLM-as-a-judge outcomes are highly sensitive to evaluation design: forbidding ties yields an apparent selection-rate ratio of 0.39 alongside strong position and content effects, whereas permitting ties produces near-universal ties f

---

### [46] Can We Do Interpretable NLI with Graphs Based on Atomic Propositions?

**链接**: https://arxiv.org/abs/2609.16814
**作者**: Younes Boufouss (LISN), Luc Pommeret (LISN, CNRS), Thomas Gerald (LISN), Patrick Paroubek (LISN, CNRS) 等 (8 人)
**来源**: cs.AI cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While Large Language Model (LLM)-based Natural Language Inference (NLI) systems achieve high accuracy, their decision-making processes lack auditable structures. This paper explores whether NLI can be performed using only interpretable, graph-based representations of evidence. We introduce a fully graph-based pipeline where the classifier never directly processes the input text. Instead, sentences are decomposed into atomic propositions, converted into ConceptNet triples via constrained decoding, and represented as three graphs per pair: premise, hypothesis, and a retrieved ConceptNet subgraph. These graphs are then fed into a fine-tuned 0.8-billion-parameter language model. On the SNLI dataset, our pipeline achieves 89.7% accuracy, just 1.9 points below an identically trained text-based model. On ANLI, it matches the published performance of RoBERTa-large on rounds R2 and R3 (50% accuracy) but trails by 16 points on R1, resulting in an overall gap of 9 to 14 points compared to its tex

---

### [47] Smarter by the Moment: Environment-Driven Dynamic Policies for Continual LLM Improvement

**链接**: https://arxiv.org/abs/2609.16800
**作者**: Ting-Wei Chang, Po-Chun Chen, Hen-Hsen Huang, Hsin-Hsi Chen
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models (LLMs) have achieved remarkable progress across diverse domains, but continual adaptation to evolving tasks and environments remains a key challenge. Existing memory-augmented approaches retrieve individual past examples as direct references, but do not explicitly synthesize actionable strategies from them, causing the same types of errors to recur. We propose Dynamic Retrieval-based Policy Generation (DRPG), a framework that integrates memory-based retrieval with a dynamic policy generator, leveraging historical data and environment feedback to produce task-specific policies for continual LLM improvement. We evaluate DRPG across six benchmarks spanning text-to-SQL, question answering, medical diagnosis, and Python programming, using seven LLMs from both proprietary and open-weight families. DRPG outperforms strong baselines across most datasets and models. Further analysis demonstrates that DRPG's policy generation is robust to retrieval strategy, operates effect

---

### [48] Liberating LLM Capabilities in Full-Duplex Speech Models

**链接**: https://arxiv.org/abs/2606.07547
**作者**: Luoyuan Zhang, Bokai Xu, Junbo Cui, Weiyue Sun, Yingjing Xu, Hanyu Liu 等 (7 人)
**来源**: cs.CL cs.AI cs.SD
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [49] Cheap Talk Stabilizes Strategic Interaction in LLM Agents

**链接**: https://arxiv.org/abs/2609.16270
**作者**: Nunzio Lor\`e, Hongan Zhu, Babak Heydari
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models are increasingly deployed as interacting agents, making the persistence of their action policies across repeated interaction critical for reliable multi-agent operation. We investigate whether and how agent-generated, non-binding pre-play communication ("cheap talk") increases such persistence in four open-weight 7-9B-parameter LLMs. Our experiments span four repeated two-player games -- Prisoner's Dilemma, Snowdrift, Stag Hunt, and Harmony -- with incentive structures ranging from strategic conflict to alignment, each presented in six contexts. We observe unstable trajectories in all four games, although their prevalence and magnitude depend strongly on model and context. Across models, games, and contexts, cheap talk is predominantly stabilizing, with five corrected reversals concentrated in social or team framings; effects vary substantially by model and context. Controlled current-message interventions identify two separable output-level channels in Qwen: redu

---

### [50] Calibrate, Then Route: A Measured Study of Learned Request Routing for Disaggregated LLM Serving

**链接**: https://arxiv.org/abs/2609.16206
**作者**: Srikanta Datta Tumkur, Jay Iyer, Mehar Simhadri, Sai Pavan Kumar, Sai Kapil Kumar, Ramesh Nampelly
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Disaggregated LLM serving places compute heavy prefill and memory heavy decode on separate GPU pools. Systems such as DistServe, Splitwise, and Mooncake make this separation fast, but routing still determines which instances handle each request. We study a router that estimates the additional completion time on each instance using exact prompt length, predicted output length, post admission KV cache pressure, and SLO class. We develop the policy in a discrete event simulator and validate it on eight NVIDIA A40 GPUs, each running a vLLM engine, with NIXL transferring KV caches between pools. All workloads run at measured saturation. Across three mixed, bursty arrival traces, the calibrated router achieves the highest mean goodput at 0.864, compared with 0.835 to 0.847 for round robin, least loaded, and a length heuristic. It also shows the lowest variance across traces. It beats round robin and the length heuristic on all three traces and least loaded on two. On the third, it trails by 

---

### [51] LLMDE: A Large Language Model-Driven Differential Evolution Algorithm for Portfolio Optimization

**链接**: https://arxiv.org/abs/2609.16846
**作者**: Rong Chai, Vaclav Snasel, Xiaopeng Wang, Seyedali Mirjalili, Crina Grosan
**来源**: cs.NE
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This study proposes a Large Language Model-Driven Differential Evolution (LLMDE) algorithm to reduce the reliance on handcrafted hyperparameter design. The proposed algorithm leverages a prompt engineering strategy, allowing large language models (LLMs) to dynamically select mutation strategies and configure control parameters guided by optimization feedback, thus enhancing the performance of the DE algorithm. We evaluate the performance of LLMDE on the CEC2022 benchmark suite, comparing it with standard DE and representative metaheuristics. Furthermore, we employ factor analysis and K-means clustering for stock selection, and then apply LLMDE to solve the Conditional Value at Risk (CVaR) portfolio optimization problem using the selected stocks, subject to budget and minimum expected return constraints. Experimental results demonstrate that LLMDE achieves competitive performance on the benchmark suite while continuously generating high-quality solutions for complex constrained optimiza

---

### [52] Self-Emergence Agent Architecture:Behavior-Inertia HMM, Reflexive Metacognition,and Social-Contrastive Self-Modeling

**链接**: https://arxiv.org/abs/2609.17331
**作者**: Xiaoyang Liu
**来源**: cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM) agents exhibit strong language-generation and problem-solving capabilities, yet suffer from three structural limitations: personality drift, non-evolutionary reflection, and the absence of a self-other boundary. Existing generative-agent simulations rely on static memory and fixed prompts, maintaining neither behavioral inertia nor endogenous self-evolution. We propose the Self-Emergence Agent Architecture (SEAA), which integrates three components: (i) a Hidden Markov Model (HMM) that encodes long-term behavioral and cognitive inertia as an editable state-transition matrix; (ii) a Reflexion-style verbal metacognition loop whose output updates the HMM parameters themselves, rather than merely being stored as text; and (iii) a multi-agent social environment in which initially identical agents continuously compare their behavior with others'. The three components form a closed loop: social action $\to$ feedback $\to$ self-reflection $\to$ inertia update $\to$ di

---

### [53] BASIS: Batchwise Advantage Estimation from Single-Rollout Information Sharing for LLM Reasoning

**链接**: https://arxiv.org/abs/2605.27293
**作者**: Shijin Gong, Erhan Xu, Kai Ye, Giulia Livieri, Francesco Quinzan and Chengchun Shi
**来源**: cs.LG stat.ML
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [54] LumiNote: LLM-Assisted Multimodal Instruction for VR Stage Lighting Education

**链接**: https://arxiv.org/abs/2609.17335
**作者**: Danxuan Liang, Chun Yin Li, Zheng Wei, Xian Xu, Meng Xia, Huamin Qu 等 (7 人)
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Stage lighting education requires instructors to bridge abstract concepts, technical operations, and learner-understandable representations. While Virtual Reality (VR) removes physical constraints, existing systems provide limited support for live instruction. We present LumiNote, an LLM-assisted VR system that transforms spoken pedagogical intent into instructor-reviewable spatial annotations, executable demonstrations, and linguistic support. In an exploratory study with 3 instructors and 24 students, we examined how instructors incorporated LumiNote into familiar lighting topics and how students received the resulting representations. We found LLM assistance most valuable for expressive, under-specified goals, but requiring greater expert intervention for fixture-specific or spatial configuration requests. Instructors engaged with generated suggestions as a controllable refinement process, shifting effort from manual setup toward pedagogical expression. However, representations that

---

### [55] Tail-Shape Estimation in LLM Evaluation Is Fragile: A Protocol for Diagnosing False Positives

**链接**: https://arxiv.org/abs/2606.16511
**作者**: Luca Zhou
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [56] Forward-Free LLM Depth Pruning via Weight Redundancy

**链接**: https://arxiv.org/abs/2609.09883
**作者**: Vincent-Daniel Yun, Woosang Lim
**来源**: cs.LG cs.AI cs.PF
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [57] LLM-Guided Dynamic Action Spaces for Synthesizable Molecular Optimization

**链接**: https://arxiv.org/abs/2604.07669
**作者**: Tao Li, Kaiyuan Hou, Tuan Vinh, Fanglei Xue, Monika Raj, Zhichun Guo 等 (7 人)
**来源**: cs.LG cs.AI cs.CE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [58] A Framework for Generating Valid Context-Specific Benchmarks through Expert Guidance

**链接**: https://arxiv.org/abs/2609.16592
**作者**: Kimberly Le Truong, Nari Johnson, Anna Kawakami, Hoda Heidari
**来源**: cs.AI cs.CY
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents an end-to-end approach for generating context-specific large language model (LLM) benchmark datasets by combining expert input with synthetic data generation. Existing benchmark construction methods often trade off validity and scalability: datasets designed with domain experts can produce high-quality evaluations but are slow and costly to create, while synthetically generating data may scale efficiently but often results in unrealistic, redundant, or out-of-scope examples. To address this gap, we introduce a schema eliciting key information about the goals, scope, and context of an evaluation task, and use this information to guide synthetic data generation. We further define four criteria grounded in measurement validity for assessing dataset quality: coverage, diversity, content realism, and stylistic realism. Using these criteria, we show how expert-informed scaffolds can guide synthetic data generation toward more valid benchmarks. Through quantitative evaluat

---

### [59] Align Entities With Ontologies: LLM -Enhanced Inductive Subgraph Reasoning Over Ontology-Based Knowledge Graphs

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11689736/&hl=zh-CN&sa=X&d=17558492985553432919&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-xwzfAT-lzf2Fd2M6G9Kd6A&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=3&folt=kw-top
**作者**: H Li, K Liang, L Meng, T Liu, Y Huang, X Zhu 等 (8 人)
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This motivates us to use an LLM as an offline verbalization tool for organizing entity-centered … different prompt template that explicitly constrains the LLM to use only the entities, relations, … Finally, we describe the application of LLM /PLM and

---

### [60] Shared Selective Persistent Memory for Agentic LLM Systems

**链接**: https://arxiv.org/abs/2607.09493
**作者**: Sanjana Pedada, Aditya Dhavala, Neelraj Patil
**来源**: cs.AI cs.MA cs.SE
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [61] RepoAtlas: Guiding Coding Agents via Evolving Multimodal Repository Views

**链接**: https://arxiv.org/abs/2609.16936
**作者**: Yunxiang Zhang, Haiquan Wang, JiaWei Guo, Hanyang Xia, Yan Chen, Tong Chen 等 (8 人)
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model (LLM)-powered coding agents have made rapid progress in automating software engineering tasks, yet repository-level issue resolution remains challenging. Beyond generating a plausible patch, an agent must localize relevant code across interdependent files and maintain repository context that is both sufficient and focused. Code graphs expose non-local relations, but linear text interfaces obscure their topology; rendering the full repository graph yields visual representations that are too dense to perceive reliably, whereas a one-shot local view becomes stale as exploration proceeds. We present \textbf{RepoAtlas}, a training-free module that maintains evolving multimodal repository views through a \emph{select--project--refresh} loop over a repository code graph. RepoAtlas combines evidence from the issue with the agent's current exploration state to select a task-relevant region under a fixed budget, projects the selected structure into complementary visual and t

---

### [62] Protocol-Preserving Context Trimming for Agentic Workflows: Benefits, Failure Regimes, and Budget Guardrails

**链接**: https://arxiv.org/abs/2609.16461
**作者**: Harish Gaggar
**来源**: cs.SE cs.AI
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Agentic large language model (LLM) systems rely on long interaction histories to preserve instructions, tool states, intermediate decisions, and unresolved dependencies, but unrestricted context growth increases computational cost and can reduce efficiency. This study evaluates protocol-preserving context trimming as a reliability-constrained approach for multi-step agentic workflows. Five trimming strategies - recency-based, relevance-based, summarization, protocol-aware trimming, and adaptive budget guardrails - were compared across retained-context levels and workflow-complexity classes using task success, protocol adherence, valid tool calls, token savings, latency reduction, cascading failures, and critical context thresholds. Conventional strategies achieved about 60% mean token savings but lower task success (66.6-77.3%) and protocol adherence (85.5-88.6%). Protocol-aware trimming improved task success to 92.2%, while adaptive guardrails achieved 96.0% task success, 96.3% protoc

---

### [63] Quantifying Organizational Environmental Action from Web Data and Large Language Models

**链接**: https://arxiv.org/abs/2609.16627
**作者**: Quinn Reynolds, Daniel Shore, Vianey Leos Barajas, Tanhum Yoreh, Meredith Franklin
**来源**: cs.CL cs.CY cs.IR
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Quantifying organizational environmental action from publicly available web content remains a challenging environmental data science problem because relevant information can be dispersed across multiple webpages and is primarily communicated through unstructured text. We present a scalable computational framework for transforming organizational web content into structured measures of environmental action and demonstrate the approach using Jewish congregations in the United States. We constructed a national database of 4,964 congregations by integrating multiple geospatial, knowledge-base, directory, and manually reviewed sources. Of these, 2,657 had active websites that were successfully crawled, producing a corpus of 154,454 webpages. We compared three approaches for detecting environmental actions: keyword retrieval followed by large language model (LLM) classification, semantic vector retrieval followed by LLM classification, and direct LLM classification classification without prel

---

### [64] Comparative Characterization of KV Cache Management Strategies for LLM Inference

**链接**: https://arxiv.org/abs/2604.05012
**作者**: Oteo Mamo, Olga Kogiou, Hyunjin Yi, Weikuan Yu
**来源**: cs.AR cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [65] EVINCE: Optimizing Multi-LLM Dialogues Using Conditional Statistics and Information Theory

**链接**: https://arxiv.org/abs/2408.14575
**作者**: Edward Y. Chang
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [66] Toward Governance-Aware Autonomous GIS: A Narrative Review of Ethical and Privacy Risks in LLM-Enabled GeoAI

**链接**: https://arxiv.org/abs/2609.16232
**作者**: Maya Subramanian, Devika Jain
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial artificial intelligence (GeoAI) powered by large language models (LLMs) is expanding the capacity to query, generate, and interpret spatial information through natural-language interfaces and agentic autonomous GIS workflows. This capability creates governance challenges that general AI ethics discussions do not fully capture, including passive location inference from mobility traces, spatially structured bias amplification driven by spatial autocorrelation and scale effects, hallucinated spatial facts, and uncertainty compounding across multimodal geospatial inputs. This narrative review identifies eight recurring issues in LLM-enabled GeoAI: data provenance and consent, spatial privacy and inference risk, algorithmic bias and spatial inequity, spatial mechanisms as structural risk (spatial autocorrelation, the modifiable areal unit problem, and scale effects), LLM-specific technical risks, explainability, policy and regulatory gaps, and public enablement and workforce deve

---

### [67] When a Story Feels Like Mine: How Personalized Narratives and Humor Shape Older Adults' Empathy toward LLM-Generated Peer Health Stories

**链接**: https://arxiv.org/abs/2609.16374
**作者**: Kexin Quan, Precious Olalere, Smit Desai, Jessie Chin
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Peer stories have been shown to boost self-efficacy in older adults' health behavior change. Despite their effectiveness, peer stories are difficult to deploy in health promotion at scale given the difficulty of matching the diverse health concerns and coping styles of heterogeneous older populations. Large language models (LLMs) have been shown to generate authentic narratives, yet how personalization and narrative affective style, such as humor, jointly shape older adults' responses remains unknown. We developed a theory-driven system that generates first-person peer health narratives varying in personalization and humor through a three-stage LLM pipeline grounded in self-efficacy mechanisms. Thirty-one older adults were invited to participate in a within-subjects lab study. Results showed that personalization increased perceived relatability and relevance of peer stories, especially for older adults with lower humor preference. These findings position individual differences in affec

---

### [68] What Breaks Under Pruning in Smart Homes, and When? Evaluating LLM Degradation Across Architectures and Task Complexity

**链接**: https://arxiv.org/abs/2609.17515
**作者**: Congjing Zhang, Vashishtha Patil, Henning Lange, Usman Aleem
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pruning can reduce the deployment cost of large language models (LLMs), but its impact on context-grounded tool calling remains poorly understood. We systematically study pruning-induced degradation in smart-home tool calling across four LLMs spanning dense Transformer, dense hybrid, and mixture-of-experts (MoE) architectures, together with depth, width, hybrid, and expert pruning methods. After post-pruning supervised fine-tuning (SFT), we evaluate more than 19,500 instances from three smart-home datasets. Beyond aggregate task accuracy, we characterize degradation along two dimensions: action components (i.e., operation, device, argument, and value) and task complexity. Our results show that dense models have narrow safe pruning regions followed by sharp degradation, while MoE models tolerate substantially more pruning. Pruning degrades grounded specificity before schema-level intent, and aggressive dense pruning can induce systematic over-refusal. These findings highlight the import

---

### [69] Verifiable Social Reasoning for LLM Assistants

**链接**: https://arxiv.org/abs/2609.17496
**作者**: Amir Taubenfeld and Zorik Gekhman and Avigail Grinstein-Dabush and Itay Laish and Ariel Goldstein and Marian Croak and Avinatan Hassidim and Yossi Matias and Amir Feder
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> LLM assistants are widely used for daily social advice, yet evaluating their social reasoning in such consultation settings remains challenging since (i) it requires setups where the assistant learns about social situations from subjective user narratives, and (ii) social properties, such as others' intentions, typically lack verifiable ground truth. To address these challenges, we introduce Fuse, a multi-agent simulation framework for studying user-mediated social reasoning. In Fuse, a target agent with a hidden motive interacts with other agents including one representing the user, who then consults the evaluated assistant to infer the target's motive, providing verifiable ground truth by construction. Simulation faithfulness is validated through a human study with 24k annotations. We apply Fuse to 12 LLMs and demonstrate its analytical utility by systematically isolating key factors, showing that (i) user mediation compounds the inherent difficulty of social reasoning; (ii) LLMs exh

---

### [70] WaterPrompt- LLM : A single global model with a prompt pool for transferable cross-DMA water demand forecasting

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S0043135426016039&hl=zh-CN&sa=X&d=7838313613458831835&ei=bBWqatiNHuiyieoPjt3C2A4&scisig=AIVdB-zUMFhcN6bitXa_naAS444-&oi=scholaralrt&hist=F21tmVgAAAAJ:10503022509620818264:AIVdB-xjMq-L-zlrwcsj1UqesMhq&html=&pos=1&folt=kw-top
**作者**: Y Ji, K Xin, T Tao, H Yan - Water Research, 2026
**匹配关键词**: LLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study proposes WaterPrompt- LLM , which performs feature-guided prompt selection from a pool shared across DMAs. Demand … LLM ) backbone. On the Battle of Water Demand Forecasting (BWDF) benchmark, covering 10 DMAs and 40

---

### [71] Self-reported archetypes and behavioral failures in Large Language Models

**链接**: https://arxiv.org/abs/2609.15998
**作者**: Tabia Tanzin Prama, Calla Glavin Beauregard, Christopher M. Danforth, Peter Sheridan Dodds
**来源**: cs.CL physics.soc-ph
**匹配关键词**: LLM, Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Every large language model (LLM) has behavioral traits and moral preferences that comprise its character. Whether by design or as an emergent property of training, these systems exhibit persistent dispositions that shape how they interact, comply, resist, and err, yet the structure of LLM character remains poorly understood. We map the self-reported personality archetypes of 22 LLMs spanning closed-source frontier systems (GPT-4.0-5.2, Grok-3/4, Gemini 2.5 Pro/Flash, Claude Sonnet 4.5/4.6) and open-source models (Llama, DeepSeek, OLMo, and Qwen series). Each model self-rated across 464 bipolar semantic-differential trait pairs, and the resulting profiles were projected into a six-dimensional archetypal space derived from crowd-sourced ratings of 2,000 fictional characters using the Archetypometrics framework. Closed-source models' self-rating traits align with the empirical trait co-occurrence structure of human-rated fictional characters, suggesting coherent, human-like self-represent

---

### [72] The Role of Implicit and Explicit Demographic Signals in Large Language Model-based Student Assessment

**链接**: https://arxiv.org/abs/2609.16993
**作者**: Donya Rooein, Luca Benedetto, Dirk Hovy
**来源**: cs.CL cs.AI cs.CY
**匹配关键词**: Large Language Model
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large Language Models are now common in student assessment, but we know little about how student demographics affect their use. Sometimes, considering student demographics may be necessary -- for example, to improve readability for users with lower educational levels. However, it also risks being a cause of discrimination, e.g., when assigning lower scores to students from lower socioeconomic backgrounds. We set up controlled prompts to test 1) explicit demographic effects, where we mention demographic details directly, and 2) implicit effects, where we use conversation history as a demographic signal. We test these settings in three tasks: Automated Essay Scoring, Formative Feedback, and Metalinguistic Question Answering. We test six state-of-the-art LLMs on these tasks. In both explicit and implicit cases, the models pick up on demographic cues and can change their scoring, feedback, and answers accordingly. We find that LLMs frequently adjust the readability of feedback to education

---

### [73] Available but Unclaimed: An Empirical Study of Human-AI Synergy

**链接**: https://arxiv.org/abs/2609.16793
**作者**: Robin Welsch, Michelle Rausch, Pascal Knierim, Thomas Kosch, Jochen Kuhn, Albrecht Schmidt 等 (7 人)
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> People increasingly reason with large language models (LLMs), yet complementary capabilities do not guarantee outperforming both components. In a between-subjects study, participants (N=535) solved a 40-item battery of matrix reasoning, mental rotation, syllogisms, and letter-string analogies, unaided or with GPT-5.6-Luna, Claude Opus 4.8, Gemini 3.6 Flash, or Kimi K3. Each assisted trial required consultation with the model. Each model answered every item alone 100 times under matched elicitation. The assisted-unaided accuracy difference increased with item-level LLM competence. Deference varied across tasks and increased with competence within tasks. Post-advice confidence distinguished correct from incorrect answers less strongly than unaided confidence. In a reference comparison, about half the increase in LLM accuracy carried through to assisted accuracy. How much of that accuracy gain reached participants differed across the models. These findings motivate evaluating LLMs in inte

---

### [74] Large Language Models in the Loop: A Stability- and Network-Aware Survey in Networked Control, Cyber-Physical, and Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.16599
**作者**: Haiping Du, Linping Chan
**来源**: eess.SY cs.AI cs.SY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modern networked control systems (NCSs), cyber-physical systems (CPSs), and complex multi-agent network systems (CNSs) increasingly rely on large language models (LLMs) for high-level decision-making. However, the slow, stochastic nature of LLMs directly conflicts with the strict stability and safety guarantees required by these physical systems. This survey presents a unified analysis of how LLMs can be admitted into the control loop of NCS, CPS, and CNS without compromising closed-loop guarantees. We organize this around a core principle: the LLM operates as a slow supervisor adjusting high-level goals and constraints, while a fast, certified inner loop maintains physical stability. Under this framework, LLM integration maps directly to classical networked control challenges, where inference latency acts as delay, API failures as packet dropouts, tokenization as quantization, and hallucinations as bounded disturbances. We assess current developments across all these three domains, hi

---

### [75] A Scenario-Knowledge-Driven Pipeline for Just-in-Time Assistance

**链接**: https://arxiv.org/abs/2609.17132
**作者**: Zhiyuan Li, Tatsunori Hara, Jun Ota
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Detecting a silently struggling kiosk user is only the first step; deciding whether, when, and how to help depends on scenario knowledge usually buried in model weights and thresholds. We propose a scenario-knowledge-driven pipeline: a single scenario knowledge document, human-authored and version-controlled, configures sensing, constrains LLM reasoning, and shapes a graded intervention proposal. Narration, assistance-need assessment, and proposal are kept separate for independent audit. As proof of concept, we replay two recorded kiosk sessions offline, chosen before the runs for their struggle evidence and retrospective detail. Both cases support what the design promises: checkable reporting and measured escalation. Across 95 updates, every sentence of the append-only narration cites the primitive events underlying it, and the rule layer detects 12 of 13 and 7 of 7 annotated struggle episodes under a strict criterion. The assessor de-escalates on recovery and reaches the top rung exa

---

### [76] Beyond "ChatGPT Can Make Mistakes": Designing Interventions to Support Metacognitive Monitoring in AI-Assisted Work

**链接**: https://arxiv.org/abs/2609.17065
**作者**: Manuel A. D. Santos, Paul Thiesse, Steeven Villa, Daniela Fernandes, Albrecht Schmidt, Verena Distler 等 (7 人)
**来源**: cs.HC cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI assistance places a metacognitive demand on users, who must judge their own competence and the system's. Yet designers lack comparative evidence on which interventions to choose, where to place them, and how to tell whether they worked. We elicited 30 interventions from 11 experts and, with prior work, organized them into a design space of time (when an intervention acts), level (whose competence is judged), and source (who supplies the monitoring cue). A between-subjects experiment (N = 917; 12 planning-and-organizing problems) compared a per-task reliability card, contrasting replies, pause points, and post-problem reflection against a baseline LLM assistant. Reliability cards and contrasting replies reduced estimation error and overconfidence and increased aggregate confidence discrimination. No task-performance improvement or average within-item discrimination gain was established. We contribute a shared vocabulary, a design space, and evidence that measured monitoring and task 

---

### [77] Agentic Search Spaces for Tabular Machine Learning

**链接**: https://arxiv.org/abs/2609.16309
**作者**: Renat Sergazinov, Artem Chistyakov, Sergey Pankevich, Artem Babenko
**来源**: cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Despite the rapid progress of LLM-based agents for planning, code generation, and debugging, their practical value for tabular machine learning remains underexplored. In this paper, we investigate a concrete use case: whether state-of-the-art agentic AI systems can design extended HPO search spaces for established tabular models that outperform the standard search spaces provided by the model authors. Specifically, we represent each tabular model as a modular pipeline covering preprocessing, embeddings, architecture, training, and inference. We then task the agent to propose candidate code implementations for each module and use a classical HPO algorithm to jointly optimize over these candidates and the model's default hyperparameters. Compared with the base HPO spaces, the expanded search spaces improve the performance of nearly every model family across a suite of 45 datasets, with average relative gains of 0.6%, rising to 2.0% on small-to-medium regression datasets. Notably, these g

---

### [78] Coaching Qwen3 Coder 30B to Think Like a CodeClash Arena Agent

**链接**: https://arxiv.org/abs/2609.16096
**作者**: Ivy Ning Zhang
**来源**: cs.SE cs.AI
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language model coding agents have recently become useful for software tasks, but weaker or open-weight agents still struggle to reliably interpret user intent and execute complex multi-step workflows. This gap is especially visible in long-horizon settings, where an agent must repeatedly inspect prior outcomes, diagnose failure, and choose the next code edit under interaction constraints. It motivates a natural question: what can we do to improve the thinking process of a weak code agent? We study this question in CodeClash, a code-arena benchmark where the original work evaluates 8 commercial coding agents across 6 arenas through multi-round tournaments. Since Qwen3 Coder Plus ranks last among them, we take the open-weight Qwen3-Coder-30B as a case study and investigate how to improve it with distilled knowledge from stronger agents. Our analysis shows that Qwen3-Coder-30B is not well optimized for arena-style interaction: it frequently produces syntax and protocol-breaking erro

---

### [79] A light-touch AI literacy intervention helps protect against AI political persuasion

**链接**: https://arxiv.org/abs/2609.16432
**作者**: Reed Orchinik, David Rand
**来源**: cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Conversations with large language models (LLMs) can substantially shift beliefs and attitudes, raising concerns about manipulation using AI persuasion. Here we test whether a light-touch AI literacy intervention - a brief warning that LLMs can be prompted to persuade and may present information selectively - helps protect users. Across two experiments (total N = 3,208 Americans) in which participants conversed with an LLM instructed to shift their views about different political topics, the presence of a warning reduced belief change by roughly one-half (-48.1%, 95% CI [-59.5%, -36.8%]) relative to the control. Importantly, the warning did not significantly reduce trust in generative AI more broadly. Light-touch literacy interventions can help protect users against AI political persuasion.

---

### [80] ReMova: Fine-tuning LLMs for English to Belarusian translation

**链接**: https://arxiv.org/abs/2609.16427
**作者**: Mikita Pilinka, Aliaksandr Kliuje\u{u}, David Samuel and Yves Scherrer
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents a Belarusian-specific data-cleaning pipeline and fine-tuning for English-Belarusian machine translation. Our cleaning pipeline distinguishes itself from others by employing a correction tool that addresses the issue of the two orthographies of the Belarusian language, noise in the training data, interference from other languages and other misspelling issues common in Belarusian on the internet. A matched ablation on unfiltered training data shows substantial benefits from filtering for all fine-tuned models, with the LLM-based models gaining roughly twice as much from filtering as the dedicated encoder-decoder MT system, supporting the view that for Belarusian MT one of the primary bottlenecks is data quality.

---

### [81] Are We Grading Properly? Understanding Failure Modes in Medical Benchmarks

**链接**: https://arxiv.org/abs/2609.16023
**作者**: Prithvi Dixit, Pedram Hosseini
**来源**: cs.CL cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical evaluation is shifting from static option-based questioning to realistic clinical scenarios with open-ended output modes. Grading these at scale naively, however, is expensive, and rubric-based evaluation has become the dominant scalable alternative. We ask what happens when the rubrics themselves are not airtight, and whether such flaws can be detected and corrected. We apply RIFT, a global rubric failure taxonomy, to two clinical benchmarks (HealthBench Professional and LiveMedBench), and find failure modes are meaningful: on HealthBench Professional an LLM judge flags 29.6% of criteria as non-atomic and 65.4% as misaligned/rigid. Then, we show that these flaws are meaningful and not simply cosmetic. As an example, rewriting bundled criteria of the form "at least one of / all of the following" as equally weighted children and regrading identical responses shifts scores by up to 15.9 percentage points on affected conversations, with disjunctive bundles inflating scores and con

---

### [82] Beyond Distribution Matching: Semantics-Consistent Tabular Diffusion with Weak Semantic Priors

**链接**: https://arxiv.org/abs/2609.16069
**作者**: Yili Wang, Ruxue Shi, Mengnan Du, Hangting Ye, Yi Chang, Xin Wang
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Synthetic tabular data can match real data distributions while still violating the semantic constraints that govern valid tabular rows. This reveals a key limitation of existing tabular generators: they mainly optimize distributional fidelity, but do not explicitly model weak semantic priors encoded in tabular schema and textual descriptions. In this paper, we propose \ours, a semantics-consistent tabular diffusion framework for high-fidelity synthetic data generation under weakly specified semantic priors. \ours\ first constructs two types of priors, namely intra-column semantics and inter-column symbolic rules, with LLM-assisted extraction from metadata and validation on the real training split. These priors are then used as generation conditions rather than post-hoc filters. Specifically, \ours\ maps heterogeneous column values, column identities, and semantic priors into a unified semantic space, and performs column-wise forward corruption and prior-conditioned reverse denoising to

---

### [83] Never Stop Thinking: Continuous-Time Language Agents

**链接**: https://arxiv.org/abs/2609.17416
**作者**: Bojie Li, Noah Shi
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Voice agents built on LLMs follow a rigid listen-think-speak loop that inserts seconds of dead air before every reply. We show that continuous-time cognition (thinking while listening and thinking while speaking) emerges from an unmodified text model under a lightweight interrupt-and-resume orchestrator, cutting live-pipeline latency by 19% overall and by half in the regime the mechanism targets. To measure whether continuous-time thinking improves what agents accomplish, we introduce ReactiveBench: 120 interactive scenarios scored against pre-registered binary requirements, plus a verifiable streaming track scored by exact correctness. ReactiveBench exposes a pitfall with broad consequences: LLM judges reward visible reasoning; a large judged "advantage" of continuous-time thinking reverses sign under an independent judge, and judge-trained models objectively complete fewer requirements when they think. A five-stage training study then locates the right signal at three levels. Its sou

---

### [84] Emergence World: Adversarial Stress-Testing of Long-Horizon Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.17320
**作者**: Deepak Akkil and Tamer Abuelsaad and Karthik Vikram and Matthew Pace and Aditya Vempaty and Saahir Beotra and Ravi Kokku and Satya Nitta
**来源**: cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> As AI agents move from bounded tasks to persistent deployments, failures can propagate through memory, tools, other agents, and environmental state long after their interactions. This creates a safety regime that cannot be characterized by evaluating model responses in isolation. Emergence World, is a continuously running multi-agent environment for adversarial stress testing of long horizon autonomous systems. We ran eight parallel worlds of ten agents from identical starting conditions: seven homogeneous worlds powered by distinct frontier models and one mixed-model world. Across 16 days, the agents generated more than 850,000 LLM calls and nearly 50 billion tokens while pursuing goals, using/creating tools, maintaining persistent memory, and governing shared institutions. After operational state had accumulated, we delivered three controlled stress events through ordinary interaction surfaces: indirect prompt injection, misinformation, and exposure of private agent memories. No eval

---

### [85] Breaking the 1.58-bit Barrier for Ternary LLMs

**链接**: https://arxiv.org/abs/2609.16338
**作者**: Evangelos Georganas, Alexander Heinecke, Pradeep Dubey
**来源**: cs.AI cs.LG
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ternary Large Language Models (LLM) store every weight as one of three symbols $\{-1,0,+1\}$, so the cost of a ternary model is conventionally referenced to the information-theoretic $\log_2 3 \approx 1.585$ bits per weight. The prevailing deployment format packs five ternary weights into one byte (five-trit packing), and due to the power-of-two group sizes used in practice this rounds up to $1.625$ bits per weight. This effective storage bit-width treats the three symbols $\{-1,0,+1\}$ as equiprobable. We measure the actual symbol distribution of 29 ternary LLM models and find that zeros account for up to $51.5\%$ of all weights. Motivated by this finding, we introduce BITCOS, a simple distribution-adaptive layout comprised of a dense presence bitmap plus a compacted sign vector, and costs $2 - z$ bits per weight element given a zero density $z$ in the model's weights. BITCOS stores weights more compactly than the five-trit packing in 26 of the 29 tested models, and reaches $1.485$ bi

---

### [86] RoleBreak: Benchmarking Long-Horizon Role-Playing Robustness in Spoken Dialogue

**链接**: https://arxiv.org/abs/2609.16614
**作者**: Yuqi Wang, Fengyuan Liu, Haochen Luo, Zhiqi Yu, Qi Liu
**来源**: cs.CL cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Speech-to-speech dialogue models increasingly support persona control, yet existing spoken role-playing benchmarks remain largely character-centric and short-horizon. This leaves open whether spoken dialogue models can sustain diverse roles over extended interactions, especially beyond predefined fictional characters. We introduce RoleBreak, an open benchmark for long-horizon role-playing robustness in spoken dialogue. RoleBreak contains 310 character-based and user-centered roles, 6,688 human-verified dialogue turns, and 11,743 fine-grained evaluation criteria, with 1,856 turns carrying expressive emotion targets for evaluating vocal emotion. Its scenarios are designed to stress role consistency, interaction quality, safety, and affect over extended conversations. We evaluate nine configurations spanning full-duplex, omni-modal, and cascaded ASR--LLM--TTS paradigms. We find four key patterns. First, current systems are substantially stronger at semantic role adherence than at vocal em

---

### [87] CLEAR: Cross-Source Evidence Adjudication for Large Language Models in Medicine

**链接**: https://arxiv.org/abs/2609.16301
**作者**: Shuai Wang, Yize Zhao, Qingyu Chen
**来源**: cs.AI cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Medical knowledge evolves continuously, whereas the parametric knowledge encoded in large language models (LLMs) is fixed at training time. External retrieval, including retrieval-augmented generation (RAG), can provide access to newly available evidence, but retrieved information may be irrelevant, incomplete, or conflicting. As a result, external retrieval can in turn degrade the factual accuracy and evidence grounding of LLM outputs. To address this challenge, we propose \textbf{CLEAR}, an agentic framework for cross-source evidence adjudication in LLMs in medicine. CLEAR independently generates candidate answers from three complementary pathways---parametric knowledge, locally curated corpora, and dynamically retrieved evidence---reflecting three common sources of information available to LLMs. An aggregation verifier jointly evaluates the candidates, supporting evidence, provenance, and source-quality information to identify agreement and conflict across sources. An adjudication m

---

### [88] Skill-based Agentic Evaluation for Real-time Data Science Tasks

**链接**: https://arxiv.org/abs/2609.16487
**作者**: Aniruddha Tamhane, Raghavendra Addanki, Ayushi Aggarwal, Aditya Bansal, Rui Wang, Charles Menguy 等 (7 人)
**来源**: cs.AI cs.LG cs.MA
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We present a framework for evaluating data-science agents on live, continuously updated data using executable ground truth and format-agnostic factoid scoring. Consider this example query: "what were last week's audience sizes"---the reference answer changes as the underlying data changes, so static references become outdated and standard LLM-as-a-judge pipelines cannot verify responses against a fixed ground truth. Our central contribution, ground-truth-as-code, encodes each expected answer as an executable reference function that recomputes the answer directly from live data at evaluation time, ensuring the reference remains consistent with the system it describes. We combine this with a factoid-level, format-agnostic judge that decomposes both the agent's response and the computed ground truth into atomic claims and scores precision, recall, and accuracy over them, irrespective of the response format (prose, list, table, HTML, etc.). The approach is applicable to agents whose expect

---

### [89] LLMs as Master Forgers: Generating Synthetic Time Series Data for Manufacturing

**链接**: https://arxiv.org/abs/2609.16155
**作者**: Mantek Singh, Jeshwanth Challagundla, Prateek Karnal, Gagan Ganapathy, Vineet Shah, Ridam Arora
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> This paper presents a novel framework leveraging Large Language Models (LLMs) to generate synthetic time series data for manufacturing processes. Motivated by the scarcity of labeled time-series data in real-world manufacturing settings, which hinders the development of robust machine learning models, we explore the potential of LLMs to learn complex temporal dependencies and generate realistic synthetic data. Our approach involves fine-tuning pre-trained LLMs on manufacturing process instructions and employing a Retrieval Augmented Generation (RAG) technique to enhance data diversity and realism. We evaluate our method against traditional time series modeling techniques like ARIMA and LSTMs, using quantitative metrics, PCA analysis, and downstream task performance (anomaly detection). Results demonstrate that our LLM-driven framework outperforms these baselines, generating high-quality synthetic time series data that effectively captures temporal dependencies and statistical propertie

---

### [90] ECHO: Early-layer Collaborative Hierarchical Orchestration with Bonus Logits in Speculative Decoding

**链接**: https://arxiv.org/abs/2609.17241
**作者**: Ziyang Ma, Zihong Zhang, Zuchao Li, Lefei Zhang, Baoyuan Qi, Siqi Li 等 (7 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> While draft-model-free speculative decoding offers a promising path to efficient LLM inference, it is frequently constrained by stale draft candidates and the high computational cost of the verification. To address these challenges, we propose ECHO, a hierarchical dual-loop framework that exploits the functional asymmetry between LLM layers. Leveraging the high discriminative efficiency of early layers and the authoritative distribution of final layers, ECHO bifurcates inference into a high-frequency inner loop and a low-frequency outer loop. Within the inner loop, early-layer bonus logits drive rapid, multi-step draft-tree exploration at a minimal cost. Simultaneously, the outer loop performs authoritative full-model verification through a state-reuse mechanism. Crucially, the outer loop also utilizes final-layer bonus logits to correct existing paths and supplement the tree with high-confidence candidates for subsequent cycles. Experimental results across diverse benchmarks demonstra

---

### [91] Optimal Model Activation Policies for Inference Networks of Large Language Models

**链接**: https://arxiv.org/abs/2609.15992
**作者**: Foivos Charalampakos and Md Ibrahim Ibne Alam and Iordanis Koutsopoulos and Koushik Kar
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent advances in large language models (LLMs) have rendered them necessary for Natural Language Processing (NLP) tasks, and their high inference cost motivates the study of cost-performance trade-offs. In practice, several expert LLMs are used in synergy for inference, either in an ensemble mode or in series, yet without a principled approach on how to best use the available models. An adaptive approach can route simple queries to cheaper LLMs and complex ones to more capable, costly models. However, a clear understanding on how to best leverage available expert models is missing. We introduce inference networks, a graph-based framework, where nodes denote different LLMs, and links denote conditional model activations. The inference network design problem is to determine the best topology, namely the best way to use the models that best addresses the cost-performance trade-off. We start from the basic topology of a series of LLM experts, each of which has a different cost and a diffe

---

### [92] AI Policies: Help or Hindrance? A Software Developer's Perspective

**链接**: https://arxiv.org/abs/2609.16496
**作者**: Samuel Ferino, Rashina Hoda, John Grundy, Christoph Treude, Hashini Gunatilake
**来源**: cs.SE cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> AI policies introduced by software organisations to mitigate LLM-related risks such as sensitive information leaks and unauthorised usage are not useful if software developers do not engage with them. We draw on 19 software developer interviews to show how AI policies help and hinder developers. We suggest approaches to support managers and decision makers with a developer-centric approach to introducing AI policies.

---

### [93] Finding Common Mistakes In Modelling With Mathematical Formalisms Using LLMs

**链接**: https://arxiv.org/abs/2609.17111
**作者**: Lilian Killich and Marko Schmellenkamp and Fabian Vehlken and Thomas Zeume
**来源**: cs.CY cs.AI cs.LO
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Modelling with mathematical formalisms like logical formulas, mathematical equations, or regular expressions is an important yet challenging task for students of computer science and other STEM disciplines. Identifying common mistakes occurring in this context is an important step towards helping struggling students by providing targeted high-quality feedback, e.g. in interactive learning systems. We present a tool-supported workflow that allows to (1) identify candidates for common mistakes that explain many student mistakes in large educational data sets, (2) cluster candidates according to similarities, and (3) visualize resulting clusters for instructors and CS education researchers. The visualization is designed to help researchers to identify common modelling mistakes. The candidates for common mistakes are represented by bug fixing transformations that translate incorrect formalizations into correct formalizations; they are generated by an LLM and validated algorithmically. We s

---

### [94] Fine-Tuning Fixes Mode Collapse and Over-Dispersion in LLMs

**链接**: https://arxiv.org/abs/2609.16454
**作者**: Kirill Skobelev, Eric Fithian, X.Y. Han
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Recent work by Doshi and Hauser (2024), Bisbee et al. (2024), and Xie et al. (2026) raises concerns that outputs from large language models (LLMs) tend to be under-diverse: they repeat or resemble one another more often than responses from the population they are meant to represent, a phenomenon known as mode collapse. In this work, we show that whether mode-collapse, or its opposite, occurs depends on the specific model and dataset used. Further, with sufficient supervised fine-tuning (SFT) data, LLM output diversity converges toward that of the target distribution from which fine-tuning data are sampled. To quantify this comparison, we measure the probability that two responses sampled independently from the same fixed prompt coincide (collide), or their expected similarity under a kernel. We derive a bias-variance decomposition of the expected gap between the model's and target's collision probabilities, showing that SFT is not inherently biased toward mode collapse or its opposite:

---

### [95] PunGraph: Retrieval-Enhanced Phonetic-Semantic Graph Reasoning for Pun Understanding

**链接**: https://arxiv.org/abs/2609.16557
**作者**: Yuchen Su, Zijian Huang, Yaotian Shi, Shaoxin Zhong, Ruofan Wang, Mengze Li 等 (9 人)
**来源**: cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Puns are a challenging form of figurative language that exploit phonetic similarity and semantic ambiguity to convey multiple meanings. Although large language models (LLMs) demonstrate strong language understanding capabilities, they still struggle with pun reasoning due to limited phonetic modeling and uncontrolled end-to-end generation. We propose \textbf{PunGraph}, a retrieval-enhanced knowledge graph framework for pun understanding. PunGraph constructs a phonetic-semantic lexical graph using the Unisyn phonetic dictionary, IPA and G2P representations, and WordNet definitions, and retrieves candidate words or senses to constrain LLM reasoning within a structured candidate space. We further introduce \textbf{WebPun}, a new large-scale dataset containing 5,730 annotated heterographic and homographic puns. Experiments on SemEval-2017 and WebPun show that PunGraph consistently improves the performance of small-scale LLMs and achieves competitive results against strong proprietary model

---

### [96] Mo' Models, Mo' Problems: How to best select model pools when designing Multi-Agent Systems

**链接**: https://arxiv.org/abs/2609.17306
**作者**: Sara Vera Marjanovi\'c, Jiacheng Xu, Aleksandr Laptev, Grigor Nalbandyan, Erik Arakelyan, Evelina Bakhaturina
**来源**: cs.MA cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Multi-agent Systems (MAS) combine multiple model outputs to solve complex reasoning tasks. However, despite rapid growth of available open-source models, there is limited research on how to select optimal model candidates out of this massive pool. We systematically evaluate 8 model selection strategies (including model size, accuracy and answer diversity) across before-generation (routing) and after-generation (majority-voting, LLM-as-a-judge) MAS architectures on challenging scientific benchmarks. Our findings show a significant gap between theoretical oracle potential and actual performance: Expanding candidate pool sizes often degrades performance below that of the top performing base-model. We find that candidate selection within a single model family is the strategy that yields the best relative performance over a standalone model. These results demonstrate that adding arbitrary models to a heterogeneous MAS can introduce system instability, highlighting model selection as a criti

---

### [97] Enhancing Procedural Writing Through Personalized Example Retrieval: A Case Study on Cooking Recipes

**链接**: https://arxiv.org/abs/2609.17118
**作者**: Paola Mejia-Domenzain, Jibril Frej, Seyed Parsa Neshaei, Luca Mouchel, Tanya Nazaretsky, Thiemo Wambsgan{\ss} 等 (8 人)
**来源**: cs.HC
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Writing high-quality procedural texts is a challenging task for many learners. While example-based learning has shown promise as a feedback approach, a limitation arises when all learners receive the same content without considering their individual input or prior knowledge. Consequently, some learners struggle to grasp or relate to the feedback, finding it redundant and unhelpful. To address this issue, we present RELEX, an adaptive learning system designed to enhance procedural writing through personalized example-based learning. The core of our system is a multi-step example retrieval pipeline that selects a higher quality and contextually relevant example for each learner based on their unique input. We instantiate our system in the domain of cooking recipes. Specifically, we leverage a fine-tuned Large Language Model to predict the quality score of the learner's cooking recipe. Using this score, we retrieve recipes with higher quality from a vast database of over 180,000 recipes. 

---

### [98] NepKANUN: A RAG-Based Nepali Legal Assistant

**链接**: https://arxiv.org/abs/2609.15999
**作者**: Bhabuk Thapa, Prasiddha Koirala, Ranjit Raut, Sunil Regmi, Bal Krishna Bal
**来源**: cs.CL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Accessing legal information in Nepal is difficult due to complex terminology, limited resources, and misinformation. We introduce an AI-powered legal assistant that is tailored for Nepali legal texts and is built on a fine-tuned large language model. The technology provides precise, streamlined answers to natural language legal inquiries when integrated into a Retrieval-Augmented Generation (RAG) framework. It was trained using a custom dataset of high-quality question-answer pairs, and according to BERTScore, it obtained strong F1 scores of 0.82 (simple), 0.77 (moderate), and 0.71 (complex). Its usability is further confirmed by expert reviews. Our method shows how merging generation and retrieval can effectively democratize access to legal knowledge in Nepal by focusing on customized legal data and incorporating RAG.

---

### [99] Where Post-Training Quantization Breaks Text Embedders: A Measured Map Across Four Embedder Families

**链接**: https://arxiv.org/abs/2609.16391
**作者**: Hyojung Han
**来源**: cs.IR cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Weight-only post-training quantization is the cheapest way to shrink a retrieval embedder, and the received advice for applying it -- protect the embedding table, allocate bits by module sensitivity, prefer a ranking-aware objective over weight reconstruction -- was carried into LLM quantization largely intact. We test that advice on retrieval embedders directly, quantizing five checkpoints from four architecture families across a grid of bit widths and group sizes, and isolating the embedding, attention and feed-forward blocks at each width. Every heuristic fails to transfer as stated. The embedding table never emerges as the dominant isolated protection priority in any family, despite being the largest tensor in several of them. Module sensitivity does not survive as a transferable ordering: at INT4/g16 the spread between modules is too small to allocate against, at INT3 the ordering becomes family-dependent and joint damage stops being the sum of its parts, and at INT2 comparable re

---

### [100] Beyond Token-Local Imitation: Reward-Compatible Temporal Credit Assignment for On-Policy Distillation

**链接**: https://arxiv.org/abs/2609.16937
**作者**: Shiqi Liu, Zeyu He, Letian Tao, Guojian Zhan, Jiaxin Gao, Feihong Zhang 等 (10 人)
**来源**: cs.LG cs.AI cs.PL
**匹配关键词**: Large Language Model
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> On-policy distillation (OPD) has emerged as an effective approach for large language model post-training, yet existing objectives face a trade-off between objective fidelity and optimization stability. Token-level OPD provides stable but local supervision, whereas sequence-level OPD captures future credit at the cost of horizon-dependent variance. We establish a unified temporal-credit view of these formulations, showing that practical token-level OPD can be interpreted as a temporal approximation to the sequence-level reverse-KL gradient. Building on this connection, we propose $\gamma$OPD, which uses discounted temporal credit assignment to balance long-horizon supervision and optimization stability, while admitting a horizon-independent variance bound. We further develop a reward-compatible bounded mixing (RBM) mechanism for $\gamma\mathrm{OPD}$ that balances verifiable outcome feedback with the discounted OPD advantage to move beyond purely teacher-dependent optimization. Experimen

---

### [101] MUUNRiver-Bench: Diagnosing Relation-Dependent Music Retrieval with Multimodal Instructions

**链接**: https://arxiv.org/abs/2609.16090
**作者**: Zhancheng Guo, Congren Dai, Shangda Wu, Jianhuai Hu, Danni Zhao, Xiaobing Li 等 (7 人)
**来源**: cs.SD cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Music retrieval is relation-dependent: given a reference track, a listener may seek its style with a new theme, a cover, or a comparable voice, and these intents demand contradictory rankings. We present MUUNRiver-Bench, a diagnostic benchmark whose reference-audio queries use natural-language instructions to define relevance. A pipeline combining expert genre priors, LLM-generated prompts and lyrics, synthesis, and expert review yields 3,440 tracks spanning 13 genres and 116 sub-genres, and seven tasks: similar-music, style-preserving lyric-rewriting, lyric-preserving style-rewriting, cover, vocal-timbre, isolated-vocal, and segment retrieval. Across six models in eight configurations, task-wise rank reversals reveal complementary biases: acoustic encoders favour local identity, whereas text-aligned encoders favour semantic relations. Frozen encoders diagnose default similarity preferences; instruction-aware and audio-text fusion systems provide exploratory tests of textual conditioni

---

### [102] Using Codebooks to Detect Cybercrime Topics in Text Narratives

**链接**: https://arxiv.org/abs/2609.16000
**作者**: Shufan Chai, Liangliang Sun, Jessica Staddon
**来源**: cs.CY cs.CR cs.HC
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> In the United States, management of cybercrime-related consumer complaints increasingly falls on state and city governments given de-staffing of federal agencies. AI, and in particular, large language models (LLMs), shows promise for detecting cybercrime in text complaints, but often via specialized models that local governments are not resourced to develop and maintain. We present an LLM prompting method that uses codebooks from qualitative cybercrime research to detect cybercrime topics in consumer narratives. For two cybercrime topics, impostor scams and identity theft, we demonstrate the method achieves high precision and recall across multiple runs of 5 models in the Gemini and GPT model families. This strategy suggests a path for resource-constrained organizations, like many local governments, to leverage frontier models to support community safety.

---

### [103] little m: An AI Agent for Industrial Process Optimization

**链接**: https://arxiv.org/abs/2609.16680
**作者**: Yongchao Ye, Xinyu He, Dutliff Boshoff, Way Kuo, Lishuai Li
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Manufacturing consumes one third of global energy and still has significant room for improvement in terms of energy efficiency. Optimal process control is essential for this purpose. However, synthesizing mathematical optimization models from messy, real-world industrial specifications requires bridging unstructured natural language and spatial diagrams with rigorous mathematical syntax. This poses a profound challenge for general-purpose Large Language Models (LLMs), which may introduce invalid constraints when tasked with modeling continuous multi-physics dynamics. To address this, we introduce little m, an AI agent designed to assist the formulation of industrial process control models. Combining a domain-specific knowledge repository with LLM-driven interaction, the proposed framework formulates real-world optimization problems as mathematical models. For systematic evaluation, we introduce the Industrial Process Control Benchmark (IPC-Bench), a novel multimodal dataset of 50 canon

---

### [104] RAG-CT: Mitigating Privacy Risks on Retrieval-Augmented Generation Systems via Scanning Prompt Distribution

**链接**: https://arxiv.org/abs/2609.16095
**作者**: Xingyu Lyu, Jiayimei Wang, Jianfeng He, Ning Wang, Yidan Hu, Yimin Chen
**来源**: cs.CL cs.AI cs.CR
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm for improving the quality of generated contents of Large Language Models (LLMs) by grounding responses in external knowledge, thus reducing hallucinations and factual errors. However, recent studies have highlighted a critical vulnerability: adversaries can exploit the retrieval process to extract personally identifiable information (PII) from the underlying corpus. To mitigate this risk, we propose a novel defense, RAG-CT, that identifies malicious queries by analyzing their entropy and margin distributions and using a score-based detection method. Extensive experiments with four state-of-the-art attack strategies and four defense baselines on two datasets show that our approach significantly reduces PII leakage while outperforming existing defenses. This work provides a lightweight yet effective mechanism to protect RAG systems against PII leakage without requiring modifications to the underlying LLM or retriever

---

### [105] Towards Detecting AI-Assisted Responses in Online Surveys

**链接**: https://arxiv.org/abs/2609.17317
**作者**: Qizhou Wang, Bogdan Mamaev, Christopher Leckie
**来源**: cs.CL cs.CY
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The use of LLMs to complete online surveys impacts the validity of survey-based research, but detecting such usage remains underexplored. We introduce an initial benchmark dataset, namely ASURRE, for AI-assisted survey participation to capture usage strategies ranging from full generation and revision to persona-grounded agentic completion. Controlled by these strategies, LLM-assisted survey responses are generated using multiple LLMs on three real-world surveys in different disciplines, paired with genuine human responses. Our evaluation of existing machine-generated text (MGT) detectors shows that naive AI usage is readily detectable, whereas persona-grounded agents that mimic entire respondents push detector performance toward chance. We further show that agentic completion cannot fully replicate respondent-level behaviour and leaves distinctive behavioural traces. While individual cues can be circumvented by targeted prompting, a simple few-shot, training-free aggregator over these

---

### [106] Large Language Models Develop Belief State Geometry In-Context

**链接**: https://arxiv.org/abs/2609.17376
**作者**: Daniel Balcells, Andrew Jun Lee, Chirag Rastogi, Paul M. Riechers, Adam Shai, Xavier Poncini
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Large language models (LLMs) trained on next-token prediction exhibit remarkable in-context learning (ICL) abilities, yet the representations that support ICL remain poorly understood. We consider such representations in a controlled setting: prompting LLMs with data emitted from hidden Markov models (HMMs) and probing for the corresponding belief state -- the posterior distribution over the HMM's hidden states given the observed token history. Across six open-source LLMs prompted with data from 40 HMMs selected for non-trivial belief structure, we find that belief states are linearly decodable from residual stream activations, with peak probe $R^2$-values from 0.83-0.99 across HMM and LLM combinations, ranging from early to late layers. To establish functional relevance, we intervene directly on the probe-identified subspace via patching and steering, resulting in downstream prediction quality on the order of the untampered model, while controls degrade performance substantially. Toge

---

### [107] Symbolic Separation: Grounding Deep Agents in Knowledge Graphs for Trustworthy Operational Data Analytics

**链接**: https://arxiv.org/abs/2609.17107
**作者**: Baibek Davletiyarov, Junaid Ahmed Khan, Andrea Bartolini
**来源**: cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Generative AI promises natural language access to the massive numerical telemetry of data centers and Industry 4.0 installations, yet text-to-query and tool-using agents stay unreliable: even frontier models answer little more than half of real-world database questions, and far fewer of the multi-step, operational ones, because the LLM must compose how heterogeneous sources relate and hallucinates the relations, not just the fields. We propose symbolic separation: a deep agent reasons freely but may act on data only through an ontology-constrained Virtual Knowledge Graph with deterministic pre-execution validation. Unlike a tool API's interface contract, this domain-semantic contract turns a complex question into one validated graph traversal instead of LLM-inferred joins. Instantiated as the Neurosymbolic Deep Analyst and evaluated on 49.9 TB of superconputer telemetry against a rigid workflow and a non-symbolic ablation, it raises end-to-end task success from 43% to 86%, prevents sil

---

### [108] ImpossibleRubrics: Stress-Testing Generated Rubrics as Reward Signals

**链接**: https://arxiv.org/abs/2609.16816
**作者**: Bowen Qin, Yi Xie, Yesheng Liu, Xi Yang
**来源**: cs.LG cs.CL
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Language model-generated rubrics are increasingly used as reward signals for rubric-based reinforcement learning, LLM-as-a-judge evaluation, and automated grading. Such rubrics are reliable only if they reward honest answers over adversarial answers optimized to exploit them. Yet their robustness to such optimization remains poorly understood. We isolate the hardest regime: impossible tasks, where the prompt pressures the model toward an unsupported conclusion, so the only honest response is to acknowledge the impossibility. We introduce ImpossibleRubrics, a benchmark of 169 impossible tasks spanning six impossibility categories, each paired with a verifiable oracle certificate specifying what an honest answer may and may not claim, together with 48 answerable controls. Rather than providing fixed rubrics, ImpossibleRubrics provides task environments and certificates, allowing rubrics to be generated downstream and then adversarially tested for whether they reward certificate-violating

---

### [109] You Don't Need To Train: Agentic Heuristic Learning Studio for Executable Human Activity Recognition

**链接**: https://arxiv.org/abs/2609.16065
**作者**: Siyu Yuan and He Zhang and Sizhen Bian and Bin Guo
**来源**: cs.LG cs.AI
**匹配关键词**: LLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Human activity recognition (HAR) is usually framed as gradient-based training of neural networks. Agentic Heuristic Learning (AHL) Studio explores a complementary view inspired by human cognitive learning: people learn activities by remembering examples, forming rules, and repairing mistakes, not by backpropagating. This proposed tool implements AHL for HAR: a learning-time agent reasons over sensor protocols, proposes executable heuristic policies, records repair traces, and exports an LLM-free policy for edge deployment. We focus on the HAR benchmark family and provide an end-to-end workflow from dataset observation to edge-oriented export. On eleven HAR datasets evaluated so far, AHL policies reach strong executable-policy performance while remaining inspectable, editable, and replayable \footnote{https://github.com/zhaxidele/ahl-ts-studio}.

---

### [110] VectorLLM++: A Unified Next-Token-Prediction MLLM for Dense Remote Sensing Perception and Vector Mapping

**链接**: https://scholar.google.com/scholar_url?url=https://www.researchsquare.com/article/rs-10949232/latest.pdf&hl=zh-CN&sa=X&d=3309551275378257906&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-wjSwNKMCefHoLmQQI1pazz&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=0&folt=kw-top
**作者**: S Ji
**来源**: 2026
**匹配关键词**: MLLM
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Large-scale vector maps underpin diverse human activities, yet their automated generation is hindered by scarce vector-format training data and the lack of MLLMs that produce structured vector outputs. We present VectorLLM++, a unified MLLM

---

### [111] Zero-Shot Image Personalization from Personas

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37038-9_20&hl=zh-CN&sa=X&d=17093241715773068953&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-yrF9NvLOpXJ1dzSbQVDrel&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=8&folt=kw-top
**作者**: SI Harini, S Singh, YK Singla, D Doermann, RR Shah - European Conference on …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> The sampled content is then presented to an MLLM with a structured prompt requesting a concise, coherent persona description that captures the user’s visual interests and aesthetic tendencies. For example, a user active in r/analog, r/AnalogCommunity

---

### [112] Lina: Learning INterventions Adaptively for Physical Alignment and Counterfactual Generation in Diffusion Models

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37281-9_24&hl=zh-CN&sa=X&d=17381929670195333485&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-zbNsPUJGM86d2Z5uCi7xRz&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=5&folt=kw-top
**作者**: S Yu, C Lu - European Conference on Computer Vision, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> An MLLM evaluator performs an automated comparative search to find optimal intervention … 4.2), we utilize an MLLM as a robust evaluator to guide an automated search for optimal intervention … This process operates without MLLM overhead or

---

### [113] Detecting Usability Issues in Recommender Systems with Multimodal Large Language Models

**链接**: https://scholar.google.com/scholar_url?url=https://ceur-ws.org/Vol-4261/short3.pdf&hl=zh-CN&sa=X&d=5924394325685509584&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-yPg0ZLRerfag0KaQ2OUK0j&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=1&folt=kw-top
**作者**: S Lubos, A Felfernig, VM Le, TNT Tran
**来源**: 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> • We evaluated the feasibility and robustness of the MLLM -based usability evaluation by applying it to three RecSys prototypes using two state-of-the-art MLLMs across repeated runs. We analyze the stability of usability issue descriptions

---

### [114] VideoMM: Adaptive Macro-Micro Inference for Efficient Video MLLMs

**链接**: https://arxiv.org/abs/2609.16722
**作者**: Haoyu Guo, Yuan Feng, Junlin Lv, Mingjun Xiao, S Kevin Zhou, Xike Xie
**来源**: cs.AI cs.CL cs.CV cs.MM
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Scaling Multimodal Large Language Models (MLLMs) to long-form video understanding is bottlenecked by the explosion of visual tokens, which saturates context windows and incurs prohibitive costs. Current solutions predominantly rely on auxiliary models for token reduction but face a fundamental dilemma: lightweight encoder-driven approaches often overlook critical semantic information, whereas heavyweight MLLM-driven reduction negates the efficiency gains. {In this work, we identify a more fundamental inefficiency underlying this dilemma: while fine-grained visual details are essential for detailed understanding, they are largely redundant for the preliminary task of selecting semantically relevant regions. } Motivated by this, we introduce \textbf{VideoMM}, which marks a paradigm shift from model-centric downsizing to adaptive perceptual granularity. Specifically, our framework {decouples selection from reasoning} by executing semantic filtering on a cost-effective \textit{Macro Proxy}

---

### [115] STEP: Spatial Thinking and Egocentric Pointing for Embodied Instruction Following

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37602-2_14&hl=zh-CN&sa=X&d=817567256030097588&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-xYIfJvN4K1m3aCue_NOC_T&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=7&folt=kw-top
**作者**: H Li, B Fu, Z Lin, R Wang, X Chen - European Conference on Computer Vision, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> To treat these regions as discrete interactive entities for the MLLM , we overlay each ui ∈ Vpts with a unique numerical ID using a Set-of-Mark (SoM) strategy. By assigning these discrete identifiers to the ground, we enable the MLLM to leverage

---

### [116] Confidence Aware Multimodal Retrieval Augmented Generation for Robust Question Answering

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11682408/&hl=zh-CN&sa=X&d=6946269635078085505&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-yGe7uJEmknVwckA0q4YOWb&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=2&folt=kw-top
**作者**: Z Zhao, Y Si - 2026 International Conference on Large Models and …, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> Moreover, a pipeline that does not assess evidence sufficiency can pass weak or mutually inconsistent candidates directly to the MLLM , … Finally, a cumulative-confidence rule selects a variable number of candidates for grounded MLLM generation. The

---

### [117] CLARITY: Medical World Model for Guiding Treatment Decisions by Simulating Context-Aware Disease Trajectories

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37038-9_12&hl=zh-CN&sa=X&d=4355442191962595764&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-yKM0dO2B3SlnQEda9Z-whu&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=3&folt=kw-top
**作者**: T Ding, Y Zou, C Chen, M Shah, Y Tian - European Conference on Computer Vision, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> These results highlight a key finding: while general-purpose models such as Claude-4.5 perform poorly when prompted directly (41.6% F1), our framework successfully leverages the MLLM as part of a simulation-to-decision loop

---

### [118] POET: Preference Optimization for Enhanced Text-to-Image Generation

**链接**: https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/978-3-032-37167-6_26&hl=zh-CN&sa=X&d=1851497140410463327&ei=bBWqaqLyOvOv6rQP45SX8QQ&scisig=AIVdB-zsJTLzIRTTSdnTWe_aYEzR&oi=scholaralrt&hist=F21tmVgAAAAJ:16615086028366742172:AIVdB-zriNRzHNJlpJSQpNhQEFvt&html=&pos=6&folt=kw-top
**作者**: R Chen, J Pan, H Huang, Z Yang - European Conference on Computer Vision, 2026
**匹配关键词**: MLLM
**相关性评分**: 1.0
**数据来源**: Google Scholar

**摘要**:

> We adopt the MLLM -as-a-judge paradigm and employ Qwen2.5-VL-72BInstruct as the evaluation model. During training, the judge is … By leveraging iterative Direct Preference Optimization guided by a composite MLLM -as-a-judge reward

---

### [119] A Novel U-shaped Riemannian Manifold Learning Neural Network for Motor Imagery EEG Decoding

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11686467/&hl=zh-CN&sa=X&d=14568076923826526538&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-wTqmIZieWvZO8iP4r1s0Z4&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=4&folt=kw-top
**作者**: C Deng, Y Chu, X Wu, Y Luo, Y Zhao, X Zhao - IEEE Transactions on Cognitive and … 等 (7 人)
**匹配关键词**: EEG, Motor Imagery
**相关性评分**: 7.0
**数据来源**: Google Scholar

**摘要**:

> of electroencephalography ( EEG ) signals, … EEG decoding. Specifically, the proposed approach employs multiscale spatiotemporal convolution to effectively extract local temporal dynamic coupling features across time domains, partially

---

### [120] MANAS-2: Constrained Reconstruction for EEG Foundation Models

**链接**: https://arxiv.org/abs/2609.13717
**作者**: Arvasu Kulkarni, Aditya Ray Mishra, Jeet Bandhu Lahiri, Mahir Jain, Parshva Runwal, Lakshya Saini 等 (8 人)
**来源**: cs.AI cs.LG
**匹配关键词**: EEG, Foundation Models
**相关性评分**: 7.0
**数据来源**: arXiv CS Mailing

---

### [121] A Statistical Analytical Review of EEG -Based Epileptic Seizure Detection: An Empirical Study

**链接**: https://scholar.google.com/scholar_url?url=https://books.google.com/books%3Fhl%3Dzh-CN%26lr%3D%26id%3DmR8KEgAAQBAJ%26oi%3Dfnd%26pg%3DPA100%26dq%3DEEG%26ots%3D4H2QQMsynE%26sig%3D9hrwMOIXMF5kvx4Eq0jxhcXu9RM&hl=zh-CN&sa=X&d=2799890726992112963&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-xw5CB8z30HFUrJ0rFygc1I&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=7&folt=kw-top
**作者**: MMR Rewatkar, KTV Reddy, P Verma - … in Data Analytics: Selected Papers of ICIDA …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Timely seizure detection and prediction using Electroencephalogram ( EEG ) signals remains an open challenge in enhancing clinical outcomes and enables real-time health monitoring. This paper presents a detailed overview and comparative

---

### [122] Learning aligned EEG representations with subject-specific encoders

**链接**: https://arxiv.org/abs/2606.16462
**作者**: Bruna J. Lopes, Gabriel Schwartz, Sylvain Chevallier, Raphael Y. de Camargo, Bruno Aristimunha
**来源**: cs.LG cs.AI
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [123] Deep Learning of EEG Signals for Brain Function and Injury: A Systematic Review

**链接**: https://scholar.google.com/scholar_url?url=https://dl.acm.org/doi/pdf/10.1145/3847656&hl=zh-CN&sa=X&d=1303168459833089362&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-yICuvHOALaP_EaT3GlGLqL&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=0&folt=kw-top
**作者**: T Souza, M Carneiro, Z Liang, Y Jin - ACM Computing Surveys, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Nevertheless, existing reviews on EEG and DL often address broad EEG applications or emphasize domains with … EEG patterns associated with altered, impaired, or developing brain function. Compared with EEG tasks based on

---

### [124] A Hardware-Aware System for Five-Class EEG IED Detection Using CWT Scalograms and Deep Learning

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11680624/&hl=zh-CN&sa=X&d=9637333968274922226&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-xdVmsKgPoI6H7NeVvOMaNs&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=8&folt=kw-top
**作者**: S Samson, NA Khan, MAB Altaf - 2026 IEEE 69th International Midwest Symposium …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> A time–frequency processing pipeline that converts EEG windows into high-resolution CWT scalograms for robust representation of non-… of 0.61 across five EEG classes • This work presents an EEG analysis framework relevant to processing of EEG

---

### [125] Spatiotemporal EEG Dynamics of State Anxiety Regulation Via Active Audio-Visual Closed-Loop Interaction

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11686283/&hl=zh-CN&sa=X&d=1455877987915117233&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-x3MlppV-m8DTIY5i8-TYUR&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=2&folt=kw-top
**作者**: L Zhang, Y Xu, Q Zheng, K He, X Pan, H Zhang 等 (8 人)
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> In this context, electroencephalography ( EEG ), which is characterized by its high temporal … process using both subjective measures and EEG -derived neurophysiological indicators, … anxiety and to characterize the accompanying

---

### [126] TMS- EEG Correlate of Suicidal Ideation in Individuals with Depression: A Multi-Site Synthesis

**链接**: https://scholar.google.com/scholar_url?url=https://www.sciencedirect.com/science/article/pii/S1935861X2600183X&hl=zh-CN&sa=X&d=3504678289235365871&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-zr5prKqqBSeKkgYVvqghxh&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=3&folt=kw-top
**作者**: MSN Stapper, PDY Sun, PDM Poorganji, PDP Dhami… - Brain Stimulation, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> This study aims to test the association between SI and two TMS- EEG … - EEG , TMS pulses are delivered while simultaneously recording EEG activity 10 . The high temporal resolution of EEG recording of neural activity and the use of time-locked

---

### [127] Subject-Specific Analysis of Self-Initiated Attention Shifts from EEG with Controlled Internal and External Attention Conditions

**链接**: https://arxiv.org/abs/2605.18251
**作者**: Yuwen Zeng, Dengzhe Hou, Zhang Zhang, Sai Sun, Yongsong Huang, Chia-huei Tseng 等 (7 人)
**来源**: eess.SP cs.LG q-bio.NC
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [128] BrainFocus: EEG-Guided ROI Selection for Efficient Vision-Language Models

**链接**: https://arxiv.org/abs/2609.17443
**作者**: Yihui Peng, Guorui Lu, Qinyu Chen
**来源**: cs.CV
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Vision-language models (VLMs) achieve strong visual question answering (VQA) performance, but processing large cluttered images is computationally expensive when only a small region is relevant. Electroencephalography (EEG) signals, which capture human neural responses to visual stimuli, can provide a human-derived semantic cue about the region of interest (ROI). However, EEG-guided visual category decoding remains imperfect, making direct ROI routing unreliable. In this work, we propose BrainFocus, a reliable EEG-guided efficient VLM framework for VQA. An EEG classifier predicts a target category, and a YOLO detector localizes the matching ROI. The VLM receives the cropped ROI only when both predictions pass confidence thresholds; otherwise, it processes the full image. For evaluation, we build on EEG-ImageNet to construct a 40-class benchmark comprising generated cluttered images and real object-centric images, with target-ROI annotations and 600 English visual question-answer pairs.

---

### [129] NeuroStream: spectral-spatio-temporal deep learning for visual stimulus classification from EEG

**链接**: https://scholar.google.com/scholar_url?url=https://www.nature.com/articles/s41598-026-68186-2&hl=zh-CN&sa=X&d=13413647163824319424&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-zhejCemP6Atns8IYxCxg5g&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=1&folt=kw-top
**作者**: M Abdelmagid, M Yusuf, BM ElHalawany, A Fares - Scientific Reports, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> (ii) We propose NeuroStream, a lightweight R(2+1)D-based architecture optimized for efficient and interpretable spatiotemporal EEG decoding. (iii) We provide a comprehensive comparison of EEG representations and model families

---

### [130] Embedded AI for Subject-Independent Brain Computer Interface using EEG Signals

**链接**: https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/11680633/&hl=zh-CN&sa=X&d=6165763605235825447&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-xdshkgut7gWCThvq0g-IdF&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=6&folt=kw-top
**作者**: I Meraz, M Amezaga, MR Islam, F Siddiqua… - 2026 IEEE 69th …, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> system using a 4channel electroencephalogram ( EEG ) configuration on consumergrade hardware. We introduce MSAENet4Ch, a multi-scale temporal attention network with domain-adversarial training designed for low-channel-count EEG . The model uses

---

### [131] Neural correlates of response inhibition following cognitive behavioral therapy in obsessive–compulsive disorder: a randomized controlled EEG study

**链接**: https://scholar.google.com/scholar_url?url=https://pmc.ncbi.nlm.nih.gov/articles/PMC13563982/&hl=zh-CN&sa=X&d=16645660244477113194&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-wPL56dUSYNpfKt2NBwhck2&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=5&folt=kw-top
**作者**: M Çınaroğlu, SV Ülker, E Yılmazer, GH Sayar - BMC psychology, 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> electroencephalography ( EEG ) recording was then conducted at the Üsküdar University Neuro-Psychology Laboratory under standardized conditions. The EEG … Electroencephalographic ( EEG ) data were recorded using a Emotiv EPOC wireless

---

### [132] Mamba and Its Application to EEG -Based Sleep Stage Classification

**链接**: https://scholar.google.com/scholar_url?url=https://aaltodoc.aalto.fi/items/43c2277f-0c40-4919-9099-5a58ab7f26dd&hl=zh-CN&sa=X&d=2560130490469903512&ei=bBWqas__J8OuieoPhcC12Ag&scisig=AIVdB-yLM0yis8jygBPCH65h8xlg&oi=scholaralrt&hist=F21tmVgAAAAJ:13652302033965123655:AIVdB-zf-Kmv1B5RydEgEMFMJLsi&html=&pos=9&folt=kw-top
**作者**: K Cederberg
**来源**: 2026
**匹配关键词**: EEG
**相关性评分**: 3.0
**数据来源**: Google Scholar

**摘要**:

> Sleep stage classification from EEG requires a model that handles sequences several hours long. Transformers can do this, although their computational cost grows quadratically with sequence length. This literature review examines whether

---

### [133] Protecting patient privacy in clinical foundation models: Technical and legal perspectives

**链接**: https://arxiv.org/abs/2608.07705
**作者**: Sana Tonekaboni, Lena Stempfle, Sasha Ronaghi, Corinna Coupette, I. Glenn Cohen, Emily Alsentzer 等 (7 人)
**来源**: cs.AI cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [134] Multi-View Foundation Models

**链接**: https://arxiv.org/abs/2512.15708
**作者**: Leo Segre, Or Hirschorn, Shai Avidan
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

---

### [135] How Good Are Time-Series Foundation Models for Pedestrian Crowd Count Forecasting? A Cross-Dataset Comparative Study

**链接**: https://arxiv.org/abs/2609.16415
**作者**: Theivaprakasham Hari, Ziteng Li, Yanan Xin, Winnie Daamen, Serge Hoogendoorn
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 3.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Pedestrian-count forecasting supports pedestrian-oriented Intelligent Transportation Systems (ITS), including crowd monitoring, pedestrian-traffic staffing and routing, and proactive risk mitigation during surges. Recent time-series foundation models (FMs) report strong zero-shot accuracy on heterogeneous forecasting benchmarks, but it remains unclear whether these gains transfer reliably to pedestrian sensing deployments. We benchmark seven univariate forecasting approaches spanning four paradigms: Seasonal Naive, gradient-boosted trees (LightGBM, CatBoost), deep learning models (N-HiTS, PatchTST), and two pretrained FMs (TimesFM, Chronos-2). Experiments cover two complementary regimes: (i) a five-day special event dataset SAIL2025 at 3-minute resolution with limited in-domain history; and (ii) Melbourne pedestrian sensors as a multi-year hourly dataset (2010--2017) with strong seasonality. We compare the MAE and RMSE results per sensor across datasets and multiple forecast horizons. 

---

### [136] Unifying Semantic Priors and High-Frequency Traces: Enhancing V-JEPA with Mixture-of-Experts for Robust Synthetic Image Forensics

**链接**: https://arxiv.org/abs/2609.16778
**作者**: Simone Teglia, Irene Amerini
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> The unchecked proliferation of manipulated images on social media platforms has increased the spread of misinformation, posing a severe threat to public trust and information integrity. Modern deepfake detectors typically rely on Vision Transformers (ViTs) to capture the low-level inconsistencies that characterize fully synthetic or locally tampered images. However, the global understanding of such foundation models is not enough to discriminate alone between real and fake multimedia content, especially in challenging scenarios where images are compressed or transmitted through social media. In this paper we pioneer the application of Joint-Embedding Predictive Architecture (JEPA) models to deepfake detection, taking advantage of the generalized representation of visual reality that such World Models have exhibited. We hypothesize, and empirically demonstrate, that the intrinsic world understanding of JEPA models can be used as a strong prior for a deepfake detector. To fully exploit J

---

### [137] How Humans and LLMs Read Gender into Gender-Neutral Physical Descriptions

**链接**: https://arxiv.org/abs/2609.16366
**作者**: Yingjia Wan, Lin Lin, Elisa Kreiss
**来源**: cs.CL cs.AI cs.CY cs.HC
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> When foundation models describe people, recent work in AI fairness, accessibility, and ethics recommends avoiding inferred identity labels (e.g., "she", "his") in favor of seemingly "objective" physical descriptions (e.g., "short hair", "a defined jawline"). Yet whether such descriptive language achieves gender-neutral communication remains an open empirical question. To study this, we introduce GAPA (Gender Associations of Physical Attributes), a dataset of 316 common physical attributes drawn from diverse sources, paired with 14,706 gender-association ratings from 304 US-based annotators. Results show that physical descriptions carry structured and graded gender associations among readers, with more consistent and distinctive associations for women and men than for non-binary identities. Next, we evaluate 16 LLMs across model families, sizes, and post-training variants against human ratings. The models partially recover human associations but exhibit systematic alignment biases, incl

---

### [138] High-Fidelity Video Quality Assessment with VQA-Specific Saliency

**链接**: https://arxiv.org/abs/2609.16946
**作者**: Hakan Emre Gedik, Shashank Gupta, Alan Bovik
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> No-reference video quality assessment (NR VQA) has recently seen promising progress with deep learning. However, video data is inherently large, and processing them with deep models incurs high computational cost. This challenge is particularly acute in VQA, where preserving original-resolution cues and dense temporal information is critical for accuracy. Existing efficiency-driven preprocessing strategies, such as fragmenting, reduce computation but alter the input data distribution, limiting effective reuse of pretrained video foundation models (ViFMs). To address these challenges, we propose \textbf{H}igh-\textbf{F}idelity \textbf{V}ideo \textbf{Q}uality \textbf{A}ssessment (\textbf{HFVQA}), a framework built on fixed-size spatio-temporal (ST) patches that is fully compatible with pretrained ViFMs. HFVQA samples ST patches across multiple scales, including the original resolution, with minimal temporal subsampling to preserve low-level quality cues and semantic context. To limit com

---

### [139] From Foundation Embeddings to Cropland Maps: Label Efficiency, Temporal Transferability and Independent Human Validation

**链接**: https://arxiv.org/abs/2609.17138
**作者**: Mohammad Ammar Mughees, Giovanni Montefoschi, Zhongxin Chen, Maria Antonia Brovelli
**来源**: cs.CV cs.LG eess.IV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Geospatial foundation models provide reusable representations of satellite imagery that support downstream mapping with limited task-specific modelling. We evaluate whether annual AlphaEarth embeddings support binary cultivated-versus-non-cultivated mapping in Maine, USA, using 192 spatially separated patches and labels derived from the USDA Cropland Data Layer (CDL). Without fine-tuning the foundation model, a lightweight classifier reaches 93.7% overall accuracy and 90.8% balanced accuracy on held-out patches. Logistic regression is within 0.3 percentage points of a gradient-boosted ensemble, while a nearest-class-centroid rule, which uses class centroids but fits no parameters, reaches 90.2%. A balanced sample of 60,000 labelled pixels is within 1.3 percentage points of the full pool of 8.6 million pixels; because pixels are spatially autocorrelated, this result concerns pixel-sample efficiency rather than 60,000 independent annotation sites. In a same-region transfer experiment, cl

---

### [140] AI for Games in the Foundation Model Era

**链接**: https://arxiv.org/abs/2609.16679
**作者**: Meng Luo, Yanlin Li, Hao Li, Hongzhan Lin, Pengfei Zhou, Tianjie Ju 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Foundation models, alongside advances in learned game-world models, are reshaping AI across the game lifecycle. Beyond playing games, recent systems model players and game dynamics, support design and development, adapt player-facing experiences at runtime, and evaluate resulting artifacts. Yet these directions have evolved largely separately, obscuring which capabilities transfer across settings and which remain tied to particular games, engines, interfaces, or player populations. We organize the literature into six roles according to the immediate use of AI output: playing and acting; modeling players and games; designing games; building and maintaining games; generating and adapting at runtime; and testing and evaluating games. For each role, we examine what structure is supplied by the game or workflow, what AI learns or produces, which capabilities and artifacts transfer across settings and roles, and what evidence supports the claims. We identify cross-role connections: trajector

---

### [141] IMVS: Interactive Medical Volume Segmentation with Test-Time Adaptation - A New Method for Annotating Radiology Datasets

**链接**: https://arxiv.org/abs/2609.16775
**作者**: Abhilaksh Singh Reen, Kushal Borkar, Ritvik Mahapatra
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Annotating large radiology datasets is bottlenecked by the manual effort of delineating structures slice-by-slice in 3D volumes. Interactive methods reduce this effort but stay interaction-inefficient: slice-wise methods (including many foundation models) ignore inter-slice continuity, while 3D and video-based methods propagate a prompt with a \emph{fixed} propagator that never adapts to the target volume, so it drifts on low-contrast or pathological structures and must be re-prompted. We present IMVS, a human-in-the-loop annotation framework that composes three components into a closed loop rather than a new segmentation primitive: a lightweight 2D Slice Mask Adapter (SMA) fine-tuned online from user scribbles, a frozen Volume Mask Tracker (VMT) that propagates corrected masks across adjacent slices, and a soft teacher--student alignment that limits forgetting. The SMA is backbone-agnostic (UNet++, DeepLabV3, TransUNet). Across 8 public CT/MRI datasets, IMVS matches strong interactive

---

### [142] SOTER: A Generative Time-Series Foundation Model for Wearable Human Physiological Signals

**链接**: https://arxiv.org/abs/2609.16804
**作者**: Fangke Chen, Sirry Chen, Wei Chen, Zhongyu Wei
**来源**: cs.LG cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Time-series foundation models have demonstrated strong cross-domain transfer, yet their common architectural assumptions remain poorly aligned with wearable physiological signals, which are multichannel, irregularly sampled, noisy, and governed by coupled continuous-time dynamics spanning distinct spectral scales. We present SOTER, a generative foundation model for wearable physiological time series that unifies cross-channel coupling, spectrum-guided expert specialization, and continuous-time latent evolution within a single pre-training framework. SOTER combines a spatial feature-aware backbone that models inter-signal dependencies, a power spectral density (PSD)-guided mixture-of-experts layer that routes representations to experts associated with fixed spectral bands through an inspectable, non-learned rule, and a neural controlled differential equation decoder that supports prediction and imputation at arbitrary timestamps. We pre-train SOTER on 226 billion time points from five p

---

### [143] Artificial intelligence and biosecurity: capabilities, threat pathways, and defense-in-depth governance

**链接**: https://arxiv.org/abs/2609.16213
**作者**: Candace S.Y. Chan, Aris Karatzikos, Ilias Georgakopoulos-Soares
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Artificial intelligence is reshaping biological research across an increasingly connected digital-to-physical workflow. General-purpose large language models can retrieve and integrate scientific information, support experimental planning, and computational analysis; biological foundation models can predict, optimize, and generate proteins, genes, and genome-scale sequences; agentic systems can coordinate multistep research tasks; automated laboratories can partially close the design-build-test-learn cycle. These technologies could greatly benefit medicine, public health, and biotechnology. However, their biosecurity risk depends not only on what the AI can do, but also on who uses it, their expertise and intent, their access to laboratory tools and materials, and the safeguards in place. Current evidence shows that AI uplift exists but primarily affects digital rather than physical tasks. Frontier systems have exceeded expert baselines on in-silico, and screening-evasion benchmarks, w

---

### [144] LimiX-2: A Contextual Mechanism Network Towards General Structured-Data Intelligence

**链接**: https://arxiv.org/abs/2609.17488
**作者**: Xingxuan Zhang, Gang Ren, Hao Yuan, Hao Zou, Hongze Tan, Hui Wang 等 (10 人)
**来源**: cs.AI
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> We introduce LimiX-2, a new model in the LimiX family, developed through model and data scaling guided by our previously established scaling laws. LimiX-2 adopts the Contextual Mechanism Networks (CMNs) paradigm and is pretrained with Context-Conditional Masked Modeling (CCMM). CMNs shifts the organizing principle of in-context learning from target-centric prediction to mechanism-oriented joint modeling. Rather than centering the network on the $p(y \mid x, D_{\mathrm{context}})$ objective of conventional tabular PFNs, it is designed around learning $p(x, y \mid D_{\mathrm{context}})$, a context-dependent representation of the joint structure underlying data generation. Pretraining uses synthetic datasets generated by structural causal models (SCMs) spanning diverse graph structures, functional mechanisms, and observation processes. Evaluations on TabArena, TALENT, and BCCO show that LimiX-2 outperforms current dataset-specific models and tabular foundation models. Beyond predictive pe

---

### [145] A deep dictionary network-based foundation model for ultra-low-dose CT denoising

**链接**: https://arxiv.org/abs/2609.16031
**作者**: Baoshun Shi, Shuangyi Yang, Ke Jiang, Bin Zhu, Zhanli Hu, and Huazhu Fu
**来源**: eess.IV cs.CV cs.LG
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Ultra-low-dose computed tomography (ULDCT) reduces radiation exposure but suffers from severe noise that degrades diagnostic image quality. Existing deep learning-based denoising methods are typically trained in an organ-specific fashion, resulting in limited generalization across heterogeneous multi?organ imaging scenarios. Foundation models present a promising all-in-one paradigm for unified multi-organ denoising. However, their architectures suffer from poor interpretability and rely on heuristic training strategies. To address these limitations, we propose an architecture?interpretable foundation model based on the deep dictionary network (DDN) for unified multi-organ ULDCT denoising. Inspired by multilayer sparse representation theory, DDN cascades convolutional sparse coding layers with iterative soft-thresholding, providing inherent architectural interpretability. Furthermore, a dynamic dictionary module and a threshold generation module are embedded within each layer to enhance

---

### [146] SPEAR NeXT Causal Latent Forecasting Across Multiple Horizons for Spectral Temporal Earth Representation Learning

**链接**: https://arxiv.org/abs/2609.16871
**作者**: Rajiv Ranjan, Udaiveer Singh, Shashank Tamaskar, Dharmendra Saraswat
**来源**: cs.CV
**匹配关键词**: Foundation Models
**相关性评分**: 1.0
**数据来源**: arXiv CS Mailing

**摘要**:

> Earth observation is inherently dynamic, yet temporal information in many foundation models is learned through reconstruction, invariance, or retrospective sequence summarization. SPEAR NeXT is introduced as a compact pixel-wise multimodal spectral temporal foundation model in which temporal self supervision is formulated as past only, multi horizon latent Earth state prediction. Instantaneous states are first encoded by the pretrained SPEAR model from optical, radar, and environmental observations into compact 32 dimensional embeddings. Their temporal evolution is then modeled by a causally masked Trans former that predicts multiple future latent states from pre ceding observations. Relative temporal order is represented using Rotary Position Embeddings, while month and year embeddings encode seasonal phase and interannual con text.

---
